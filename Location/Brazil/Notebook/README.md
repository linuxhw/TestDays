Linux in Brazil - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

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

Total: 9247

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion 11 x360 PC         | [a1271c4465](https://linux-hardware.org/?probe=a1271c4465) | May 07, 2022 |
| Samsung       | 670Z5E                      | [3ded76a717](https://linux-hardware.org/?probe=3ded76a717) | May 07, 2022 |
| HP            | ProBook 645 G1              | [c8bd8caf2f](https://linux-hardware.org/?probe=c8bd8caf2f) | May 07, 2022 |
| Samsung       | 550XDA                      | [a616d83a41](https://linux-hardware.org/?probe=a616d83a41) | May 07, 2022 |
| Intel         | W7650                       | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [6a3cbcae26](https://linux-hardware.org/?probe=6a3cbcae26) | May 06, 2022 |
| Gateway       | NV55C                       | [2cbbfa9c42](https://linux-hardware.org/?probe=2cbbfa9c42) | May 06, 2022 |
| Dell          | Vostro 15 5510              | [e2b06a4a28](https://linux-hardware.org/?probe=e2b06a4a28) | May 05, 2022 |
| Philco        | 10D                         | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| Acer          | Aspire A315-41G             | [af3af97b7d](https://linux-hardware.org/?probe=af3af97b7d) | May 05, 2022 |
| Toshiba       | IS 1413G                    | [8ca57528af](https://linux-hardware.org/?probe=8ca57528af) | May 04, 2022 |
| Acer          | Aspire E1-532               | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Toshiba       | IS 1413G                    | [3bc61ca207](https://linux-hardware.org/?probe=3bc61ca207) | May 04, 2022 |
| Dell          | Inspiron N4010              | [f1e24327ba](https://linux-hardware.org/?probe=f1e24327ba) | May 04, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [3c081a7012](https://linux-hardware.org/?probe=3c081a7012) | May 04, 2022 |
| Dell          | Inspiron 5558               | [3cab561b32](https://linux-hardware.org/?probe=3cab561b32) | May 04, 2022 |
| Dell          | Inspiron 3501               | [2b5958e2dd](https://linux-hardware.org/?probe=2b5958e2dd) | May 04, 2022 |
| Samsung       | RV415/RV515                 | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| Dell          | Inspiron 3583               | [f5e954ea5e](https://linux-hardware.org/?probe=f5e954ea5e) | May 04, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N70... | [9da4b1ddc5](https://linux-hardware.org/?probe=9da4b1ddc5) | May 03, 2022 |
| Acer          | Aspire F5-573G              | [2136362d58](https://linux-hardware.org/?probe=2136362d58) | May 03, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [1d4b493814](https://linux-hardware.org/?probe=1d4b493814) | May 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [f9db97e5d3](https://linux-hardware.org/?probe=f9db97e5d3) | May 03, 2022 |
| Dell          | Inspiron N4010              | [61f313c65a](https://linux-hardware.org/?probe=61f313c65a) | May 03, 2022 |
| Dell          | Inspiron 3583               | [bd62b32976](https://linux-hardware.org/?probe=bd62b32976) | May 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4516542417](https://linux-hardware.org/?probe=4516542417) | May 03, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Acer          | Aspire A315-23G             | [f749343aee](https://linux-hardware.org/?probe=f749343aee) | May 03, 2022 |
| HP            | Pavilion dv6                | [7587fe8761](https://linux-hardware.org/?probe=7587fe8761) | May 03, 2022 |
| HP            | Pavilion dv6                | [bf79099573](https://linux-hardware.org/?probe=bf79099573) | May 03, 2022 |
| Acer          | Aspire E1-531               | [ab72c3ae3f](https://linux-hardware.org/?probe=ab72c3ae3f) | May 03, 2022 |
| Dell          | Inspiron 3583               | [c47758f125](https://linux-hardware.org/?probe=c47758f125) | May 03, 2022 |
| Dell          | Inspiron 5566               | [ba926f40d8](https://linux-hardware.org/?probe=ba926f40d8) | May 02, 2022 |
| Avell High... | B.ON                        | [5de402efe5](https://linux-hardware.org/?probe=5de402efe5) | May 02, 2022 |
| Acer          | Aspire F5-573               | [f571b0dc6f](https://linux-hardware.org/?probe=f571b0dc6f) | May 02, 2022 |
| Acer          | Aspire E1-532               | [88080c45b1](https://linux-hardware.org/?probe=88080c45b1) | May 02, 2022 |
| Dell          | Vostro 5470                 | [8fbdd05b2a](https://linux-hardware.org/?probe=8fbdd05b2a) | May 02, 2022 |
| Toshiba       | Satellite M55               | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [72f6ebfc11](https://linux-hardware.org/?probe=72f6ebfc11) | May 01, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [0205c9da07](https://linux-hardware.org/?probe=0205c9da07) | May 01, 2022 |
| Dell          | Vostro 5470                 | [85d403928b](https://linux-hardware.org/?probe=85d403928b) | May 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [414334d8e3](https://linux-hardware.org/?probe=414334d8e3) | May 01, 2022 |
| Avell High... | A70 MOB                     | [cb532b211e](https://linux-hardware.org/?probe=cb532b211e) | May 01, 2022 |
| LG Electro... | P430-G.BC41P1               | [527905ca3b](https://linux-hardware.org/?probe=527905ca3b) | May 01, 2022 |
| Toshiba       | IS 1413G                    | [6d0ad0b8f2](https://linux-hardware.org/?probe=6d0ad0b8f2) | May 01, 2022 |
| Acer          | F5-573                      | [47c8b0dd51](https://linux-hardware.org/?probe=47c8b0dd51) | May 01, 2022 |
| Dell          | Inspiron 3583               | [52c4caf797](https://linux-hardware.org/?probe=52c4caf797) | May 01, 2022 |
| Acer          | Aspire 5741                 | [f82c315ff4](https://linux-hardware.org/?probe=f82c315ff4) | May 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [34df7ab926](https://linux-hardware.org/?probe=34df7ab926) | May 01, 2022 |
| HP            | EliteBook 8440p             | [31fdda39b1](https://linux-hardware.org/?probe=31fdda39b1) | May 01, 2022 |
| HP            | EliteBook 8440p             | [5a3254d19c](https://linux-hardware.org/?probe=5a3254d19c) | Apr 30, 2022 |
| Dell          | Inspiron 15-3567            | [589f58c857](https://linux-hardware.org/?probe=589f58c857) | Apr 30, 2022 |
| HP            | EliteBook 8440p             | [3782e39a43](https://linux-hardware.org/?probe=3782e39a43) | Apr 30, 2022 |
| Acer          | V5-171                      | [a07ba20ff0](https://linux-hardware.org/?probe=a07ba20ff0) | Apr 30, 2022 |
| Dell          | System XPS L502X            | [77e1846d8d](https://linux-hardware.org/?probe=77e1846d8d) | Apr 30, 2022 |
| Itautec       | Infoway w7535               | [ac87d9e508](https://linux-hardware.org/?probe=ac87d9e508) | Apr 30, 2022 |
| Positivo      | S14CT01                     | [7260e4f199](https://linux-hardware.org/?probe=7260e4f199) | Apr 30, 2022 |
| Lenovo        | G40-70 80GA                 | [fcd20cb250](https://linux-hardware.org/?probe=fcd20cb250) | Apr 30, 2022 |
| Positivo      | S14CT01                     | [dec0b170c2](https://linux-hardware.org/?probe=dec0b170c2) | Apr 30, 2022 |
| Toshiba       | IS 1413G                    | [8074a86bc7](https://linux-hardware.org/?probe=8074a86bc7) | Apr 30, 2022 |
| Acer          | Aspire A514-54              | [70efbbb6c7](https://linux-hardware.org/?probe=70efbbb6c7) | Apr 30, 2022 |
| Philco        | 14I                         | [03bb0fdeef](https://linux-hardware.org/?probe=03bb0fdeef) | Apr 30, 2022 |
| Acer          | V5-171                      | [8500a1c376](https://linux-hardware.org/?probe=8500a1c376) | Apr 30, 2022 |
| Dell          | Inspiron N4010              | [e1369b0428](https://linux-hardware.org/?probe=e1369b0428) | Apr 29, 2022 |
| Avell High... | B.ON                        | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| Dell          | Inspiron 3421               | [15a2c261da](https://linux-hardware.org/?probe=15a2c261da) | Apr 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Dell          | Inspiron 5547               | [a5d8e73a23](https://linux-hardware.org/?probe=a5d8e73a23) | Apr 28, 2022 |
| Dell          | Inspiron 5547               | [be4ab0fd27](https://linux-hardware.org/?probe=be4ab0fd27) | Apr 28, 2022 |
| Acer          | Aspire A515-54              | [4ff968ef61](https://linux-hardware.org/?probe=4ff968ef61) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [995f77010e](https://linux-hardware.org/?probe=995f77010e) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [e2293170b3](https://linux-hardware.org/?probe=e2293170b3) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| Dell          | Inspiron 5570               | [8105c6bf09](https://linux-hardware.org/?probe=8105c6bf09) | Apr 28, 2022 |
| Acer          | Nitro AN515-44              | [11b568f82d](https://linux-hardware.org/?probe=11b568f82d) | Apr 28, 2022 |
| Samsung       | 670Z5E                      | [7867dbccf7](https://linux-hardware.org/?probe=7867dbccf7) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [a63dc69025](https://linux-hardware.org/?probe=a63dc69025) | Apr 28, 2022 |
| Samsung       | 670Z5E                      | [39efe61675](https://linux-hardware.org/?probe=39efe61675) | Apr 28, 2022 |
| Dell          | Vostro 3560                 | [56d52ea265](https://linux-hardware.org/?probe=56d52ea265) | Apr 28, 2022 |
| Dell          | Inspiron 5566               | [49396d0706](https://linux-hardware.org/?probe=49396d0706) | Apr 28, 2022 |
| Dell          | Inspiron 3583               | [740919a383](https://linux-hardware.org/?probe=740919a383) | Apr 28, 2022 |
| Dell          | Inspiron 5566               | [695d362d8f](https://linux-hardware.org/?probe=695d362d8f) | Apr 27, 2022 |
| Dell          | XPS 13 9310                 | [d394f4e0d9](https://linux-hardware.org/?probe=d394f4e0d9) | Apr 27, 2022 |
| Dell          | Vostro 15 3515              | [7c99d7d4c5](https://linux-hardware.org/?probe=7c99d7d4c5) | Apr 27, 2022 |
| Unknown       | Unknown                     | [e77a313003](https://linux-hardware.org/?probe=e77a313003) | Apr 27, 2022 |
| Lenovo        | ThinkPad T480 20L6SJN400    | [294a5ef80c](https://linux-hardware.org/?probe=294a5ef80c) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b7ac79ff8f](https://linux-hardware.org/?probe=b7ac79ff8f) | Apr 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [593ee8ccf3](https://linux-hardware.org/?probe=593ee8ccf3) | Apr 27, 2022 |
| Dell          | Inspiron 3583               | [8f10e59515](https://linux-hardware.org/?probe=8f10e59515) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9e7c77d251](https://linux-hardware.org/?probe=9e7c77d251) | Apr 27, 2022 |
| Acer          | Aspire A315-34              | [a49e25f2b8](https://linux-hardware.org/?probe=a49e25f2b8) | Apr 27, 2022 |
| Positivo      | S14SL01                     | [f8bdbe707d](https://linux-hardware.org/?probe=f8bdbe707d) | Apr 27, 2022 |
| Dell          | Latitude 5410               | [1a67b58656](https://linux-hardware.org/?probe=1a67b58656) | Apr 27, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f3c9dd19da](https://linux-hardware.org/?probe=f3c9dd19da) | Apr 26, 2022 |
| Dell          | Inspiron 3583               | [bca722d45d](https://linux-hardware.org/?probe=bca722d45d) | Apr 26, 2022 |
| Google        | Relm                        | [edd0a8864b](https://linux-hardware.org/?probe=edd0a8864b) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | [d4b7580074](https://linux-hardware.org/?probe=d4b7580074) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | [d994ff2a13](https://linux-hardware.org/?probe=d994ff2a13) | Apr 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [64cd863479](https://linux-hardware.org/?probe=64cd863479) | Apr 26, 2022 |
| Acer          | Aspire A315-41              | [a42b1cda2c](https://linux-hardware.org/?probe=a42b1cda2c) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| Acer          | Aspire A515-45              | [128cdc0a61](https://linux-hardware.org/?probe=128cdc0a61) | Apr 26, 2022 |
| Dell          | Inspiron 5447               | [0adfe1cfb9](https://linux-hardware.org/?probe=0adfe1cfb9) | Apr 25, 2022 |
| Toshiba       | Satellite S55-C             | [05afb55e10](https://linux-hardware.org/?probe=05afb55e10) | Apr 25, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [89debf3e0e](https://linux-hardware.org/?probe=89debf3e0e) | Apr 25, 2022 |
| Dell          | Inspiron 1525               | [47a349b8db](https://linux-hardware.org/?probe=47a349b8db) | Apr 25, 2022 |
| Unknown       | Unknown                     | [8f76034215](https://linux-hardware.org/?probe=8f76034215) | Apr 25, 2022 |
| Acer          | Nitro AN515-44              | [319cbc94dd](https://linux-hardware.org/?probe=319cbc94dd) | Apr 25, 2022 |
| Sony          | SVS13A25PBS                 | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Dell          | Inspiron N4050              | [7b82407cba](https://linux-hardware.org/?probe=7b82407cba) | Apr 25, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [7423afe5a1](https://linux-hardware.org/?probe=7423afe5a1) | Apr 25, 2022 |
| Dell          | Inspiron 7460               | [6a67f6de58](https://linux-hardware.org/?probe=6a67f6de58) | Apr 25, 2022 |
| Google        | Bobba                       | [008afa9913](https://linux-hardware.org/?probe=008afa9913) | Apr 25, 2022 |
| Sony          | VPCEH25FM                   | [bceedddb01](https://linux-hardware.org/?probe=bceedddb01) | Apr 24, 2022 |
| Apple         | MacBookPro9,1               | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| Avell High... | C65 MOB                     | [b8e185c194](https://linux-hardware.org/?probe=b8e185c194) | Apr 24, 2022 |
| Samsung       | 550XCJ/550XCR               | [4f5bd4cb03](https://linux-hardware.org/?probe=4f5bd4cb03) | Apr 23, 2022 |
| Toshiba       | IS 1413G                    | [d5918f0d93](https://linux-hardware.org/?probe=d5918f0d93) | Apr 23, 2022 |
| Google        | Bobba                       | [a5c612d7ec](https://linux-hardware.org/?probe=a5c612d7ec) | Apr 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3e3f727deb](https://linux-hardware.org/?probe=3e3f727deb) | Apr 23, 2022 |
| Acer          | Nitro AN515-44              | [6e05fa6a88](https://linux-hardware.org/?probe=6e05fa6a88) | Apr 23, 2022 |
| Gateway       | NE570                       | [1cb22c0c86](https://linux-hardware.org/?probe=1cb22c0c86) | Apr 23, 2022 |
| Unknown       | Unknown                     | [f45406567e](https://linux-hardware.org/?probe=f45406567e) | Apr 23, 2022 |
| Lenovo        | ThinkPad P50 20EQS64N1N     | [c3d792a237](https://linux-hardware.org/?probe=c3d792a237) | Apr 23, 2022 |
| Google        | Bobba                       | [5ad66cbf53](https://linux-hardware.org/?probe=5ad66cbf53) | Apr 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [e97ab3fc6c](https://linux-hardware.org/?probe=e97ab3fc6c) | Apr 22, 2022 |
| Acer          | Aspire A515-54G             | [9eeb0ced39](https://linux-hardware.org/?probe=9eeb0ced39) | Apr 22, 2022 |
| Samsung       | 550XDA                      | [379e724ba3](https://linux-hardware.org/?probe=379e724ba3) | Apr 22, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [f3e50d22aa](https://linux-hardware.org/?probe=f3e50d22aa) | Apr 22, 2022 |
| Positivo      | W942SW_SW1                  | [36b0510bae](https://linux-hardware.org/?probe=36b0510bae) | Apr 22, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [d90f38b2ad](https://linux-hardware.org/?probe=d90f38b2ad) | Apr 22, 2022 |
| Samsung       | 550XDA                      | [a3011752e2](https://linux-hardware.org/?probe=a3011752e2) | Apr 22, 2022 |
| Acer          | Aspire F5-573G              | [c4cfcaf69e](https://linux-hardware.org/?probe=c4cfcaf69e) | Apr 22, 2022 |
| Dell          | Inspiron 1525               | [b5dbaddd84](https://linux-hardware.org/?probe=b5dbaddd84) | Apr 22, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [f5f36d1c44](https://linux-hardware.org/?probe=f5f36d1c44) | Apr 22, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [05dfaaa5c7](https://linux-hardware.org/?probe=05dfaaa5c7) | Apr 21, 2022 |
| Acer          | Nitro AN515-51              | [6a3938aa9c](https://linux-hardware.org/?probe=6a3938aa9c) | Apr 21, 2022 |
| Acer          | Nitro AN515-51              | [db446247f1](https://linux-hardware.org/?probe=db446247f1) | Apr 21, 2022 |
| Dell          | Inspiron 5447               | [b5f1325640](https://linux-hardware.org/?probe=b5f1325640) | Apr 21, 2022 |
| Dell          | Inspiron 5447               | [f68123a23d](https://linux-hardware.org/?probe=f68123a23d) | Apr 21, 2022 |
| Acer          | Aspire 1410                 | [703c2ec84a](https://linux-hardware.org/?probe=703c2ec84a) | Apr 21, 2022 |
| Acer          | Nitro AN515-55              | [49bb0bd1ff](https://linux-hardware.org/?probe=49bb0bd1ff) | Apr 21, 2022 |
| Positivo      | W940TU                      | [4d03effd28](https://linux-hardware.org/?probe=4d03effd28) | Apr 20, 2022 |
| Positivo      | W940TU                      | [971493b883](https://linux-hardware.org/?probe=971493b883) | Apr 20, 2022 |
| Philco        | Unknown                     | [16719246ff](https://linux-hardware.org/?probe=16719246ff) | Apr 20, 2022 |
| Samsung       | 550XDA                      | [66cb0691e0](https://linux-hardware.org/?probe=66cb0691e0) | Apr 20, 2022 |
| HP            | Pavilion dv6                | [8a3a510921](https://linux-hardware.org/?probe=8a3a510921) | Apr 20, 2022 |
| Acer          | Aspire A315-23              | [5593faa826](https://linux-hardware.org/?probe=5593faa826) | Apr 20, 2022 |
| Acer          | Nitro AN515-44              | [5549666ce7](https://linux-hardware.org/?probe=5549666ce7) | Apr 20, 2022 |
| Intel         | W7650                       | [edb281c81e](https://linux-hardware.org/?probe=edb281c81e) | Apr 20, 2022 |
| HP            | ElitePad 1000 G2            | [05daf3f64b](https://linux-hardware.org/?probe=05daf3f64b) | Apr 20, 2022 |
| Intel         | W7650                       | [cdf0885f07](https://linux-hardware.org/?probe=cdf0885f07) | Apr 20, 2022 |
| Positivo      | Q464C                       | [b68073fbe4](https://linux-hardware.org/?probe=b68073fbe4) | Apr 20, 2022 |
| Positivo      | Q464C                       | [31c6ba5157](https://linux-hardware.org/?probe=31c6ba5157) | Apr 20, 2022 |
| HP            | ProBook 440 G5              | [288c8e99b2](https://linux-hardware.org/?probe=288c8e99b2) | Apr 20, 2022 |
| Acer          | Aspire E5-574               | [6f1f7031bb](https://linux-hardware.org/?probe=6f1f7031bb) | Apr 19, 2022 |
| HP            | Pavilion Laptop 14-bk0xx    | [61ebff551a](https://linux-hardware.org/?probe=61ebff551a) | Apr 19, 2022 |
| Acer          | Aspire A315-23              | [4b9d2c67fe](https://linux-hardware.org/?probe=4b9d2c67fe) | Apr 19, 2022 |
| Dell          | Latitude 3410               | [d932874d9c](https://linux-hardware.org/?probe=d932874d9c) | Apr 19, 2022 |
| Positivo      | N1250                       | [c2dfeaab53](https://linux-hardware.org/?probe=c2dfeaab53) | Apr 19, 2022 |
| Dell          | XPS 13 9310                 | [0f924d06d6](https://linux-hardware.org/?probe=0f924d06d6) | Apr 19, 2022 |
| Acer          | Aspire A315-42G             | [3654d1f0fa](https://linux-hardware.org/?probe=3654d1f0fa) | Apr 19, 2022 |
| Samsung       | 370E4K                      | [b3d7575f01](https://linux-hardware.org/?probe=b3d7575f01) | Apr 18, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [746e2ea0d2](https://linux-hardware.org/?probe=746e2ea0d2) | Apr 18, 2022 |
| Unknown       | Unknown                     | [b903351314](https://linux-hardware.org/?probe=b903351314) | Apr 18, 2022 |
| Dell          | Inspiron 5567               | [e9f6594677](https://linux-hardware.org/?probe=e9f6594677) | Apr 18, 2022 |
| Dell          | Inspiron 5567               | [d6b72a0160](https://linux-hardware.org/?probe=d6b72a0160) | Apr 18, 2022 |
| Avell High... | B.ON                        | [6f37e0aabc](https://linux-hardware.org/?probe=6f37e0aabc) | Apr 18, 2022 |
| Toshiba       | IS 1413G                    | [1b3267b605](https://linux-hardware.org/?probe=1b3267b605) | Apr 18, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N70... | [db5f56be25](https://linux-hardware.org/?probe=db5f56be25) | Apr 18, 2022 |
| HP            | ElitePad 1000 G2            | [f7888cc252](https://linux-hardware.org/?probe=f7888cc252) | Apr 18, 2022 |
| Samsung       | RV415/RV515                 | [e2462a2328](https://linux-hardware.org/?probe=e2462a2328) | Apr 17, 2022 |
| Positivo      | Mobile                      | [0cfa1a5e22](https://linux-hardware.org/?probe=0cfa1a5e22) | Apr 17, 2022 |
| Gateway       | NE570                       | [d4b1bdce70](https://linux-hardware.org/?probe=d4b1bdce70) | Apr 17, 2022 |
| Apple         | MacBookPro7,1               | [4def2a51dc](https://linux-hardware.org/?probe=4def2a51dc) | Apr 17, 2022 |
| Lenovo        | G40-80 80JE                 | [28c58e21e0](https://linux-hardware.org/?probe=28c58e21e0) | Apr 16, 2022 |
| Positivo      | H14BU08                     | [43d44df3d2](https://linux-hardware.org/?probe=43d44df3d2) | Apr 16, 2022 |
| Dell          | Inspiron 5458               | [5f7dafa5b9](https://linux-hardware.org/?probe=5f7dafa5b9) | Apr 16, 2022 |
| Toshiba       | IS 1413G                    | [e9e45e7f91](https://linux-hardware.org/?probe=e9e45e7f91) | Apr 16, 2022 |
| Toshiba       | IS 1413G                    | [e51d0544a1](https://linux-hardware.org/?probe=e51d0544a1) | Apr 16, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b07e7e9974](https://linux-hardware.org/?probe=b07e7e9974) | Apr 16, 2022 |
| Positivo B... | VJC141F11X-B0111L           | [5ea499eca7](https://linux-hardware.org/?probe=5ea499eca7) | Apr 16, 2022 |
| Acer          | Aspire E1-572               | [27d5f97167](https://linux-hardware.org/?probe=27d5f97167) | Apr 16, 2022 |
| HP            | Pavilion dv6                | [639a7422d8](https://linux-hardware.org/?probe=639a7422d8) | Apr 16, 2022 |
| Compaq        | Presario CQ-29              | [4c37a60084](https://linux-hardware.org/?probe=4c37a60084) | Apr 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [3b30ef3d55](https://linux-hardware.org/?probe=3b30ef3d55) | Apr 15, 2022 |
| Intel         | W7650                       | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Dell          | Inspiron 7559               | [5302420f94](https://linux-hardware.org/?probe=5302420f94) | Apr 15, 2022 |
| Dell          | Latitude 5420               | [7b97392ed4](https://linux-hardware.org/?probe=7b97392ed4) | Apr 15, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0646755403](https://linux-hardware.org/?probe=0646755403) | Apr 15, 2022 |
| Dell          | Latitude 5420               | [7ef3e515d9](https://linux-hardware.org/?probe=7ef3e515d9) | Apr 15, 2022 |
| Dell          | Inspiron 3481               | [69d336ac59](https://linux-hardware.org/?probe=69d336ac59) | Apr 15, 2022 |
| Dell          | XPS L322X                   | [eee5065a27](https://linux-hardware.org/?probe=eee5065a27) | Apr 14, 2022 |
| Dell          | Inspiron N4010              | [d29ff8a54e](https://linux-hardware.org/?probe=d29ff8a54e) | Apr 14, 2022 |
| Acer          | Aspire A514-54              | [8c6aae59db](https://linux-hardware.org/?probe=8c6aae59db) | Apr 14, 2022 |
| HP            | G42                         | [e717533860](https://linux-hardware.org/?probe=e717533860) | Apr 14, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [a7f25c6027](https://linux-hardware.org/?probe=a7f25c6027) | Apr 14, 2022 |
| Toshiba       | IS 1413G                    | [f8f13d5514](https://linux-hardware.org/?probe=f8f13d5514) | Apr 14, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [3752ecab33](https://linux-hardware.org/?probe=3752ecab33) | Apr 14, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a8061e68ff](https://linux-hardware.org/?probe=a8061e68ff) | Apr 14, 2022 |
| Gateway       | NE570                       | [3635e5c663](https://linux-hardware.org/?probe=3635e5c663) | Apr 14, 2022 |
| Acer          | Aspire A514-54G             | [af418a6f28](https://linux-hardware.org/?probe=af418a6f28) | Apr 13, 2022 |
| Dell          | Inspiron 7560               | [1bb75ffe05](https://linux-hardware.org/?probe=1bb75ffe05) | Apr 13, 2022 |
| Samsung       | 270E5J/2570EJ               | [4aeb8de6f6](https://linux-hardware.org/?probe=4aeb8de6f6) | Apr 13, 2022 |
| Lenovo        | BS145-15IIL 82HB            | [e595769424](https://linux-hardware.org/?probe=e595769424) | Apr 13, 2022 |
| Toshiba       | Satellite U845W             | [c8b77c70a6](https://linux-hardware.org/?probe=c8b77c70a6) | Apr 13, 2022 |
| Multilaser    | M11W                        | [4be432c77a](https://linux-hardware.org/?probe=4be432c77a) | Apr 13, 2022 |
| Avell High... | B.ON                        | [0e81f76e2b](https://linux-hardware.org/?probe=0e81f76e2b) | Apr 13, 2022 |
| Gateway       | NE570                       | [068d4c39f2](https://linux-hardware.org/?probe=068d4c39f2) | Apr 13, 2022 |
| Acer          | Aspire E5-553G              | [abebd4506d](https://linux-hardware.org/?probe=abebd4506d) | Apr 13, 2022 |
| Apple         | MacBookPro8,1               | [fad4436356](https://linux-hardware.org/?probe=fad4436356) | Apr 13, 2022 |
| Dell          | Inspiron N4010              | [9fa510fc02](https://linux-hardware.org/?probe=9fa510fc02) | Apr 13, 2022 |
| Dell          | Vostro 3500                 | [080cbf45eb](https://linux-hardware.org/?probe=080cbf45eb) | Apr 13, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [85062520f7](https://linux-hardware.org/?probe=85062520f7) | Apr 13, 2022 |
| Dell          | Vostro 5470                 | [e79417a89e](https://linux-hardware.org/?probe=e79417a89e) | Apr 13, 2022 |
| Positivo      | Mobile                      | [1bd294322c](https://linux-hardware.org/?probe=1bd294322c) | Apr 12, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [24545103f4](https://linux-hardware.org/?probe=24545103f4) | Apr 12, 2022 |
| Dell          | Vostro 5490                 | [0e748100fa](https://linux-hardware.org/?probe=0e748100fa) | Apr 12, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [73bb0eeab0](https://linux-hardware.org/?probe=73bb0eeab0) | Apr 12, 2022 |
| ASUSTek       | X451CA                      | [865aec543f](https://linux-hardware.org/?probe=865aec543f) | Apr 12, 2022 |
| Intel         | W7650                       | [4bd778e810](https://linux-hardware.org/?probe=4bd778e810) | Apr 11, 2022 |
| Dell          | Latitude 5420               | [8f23343086](https://linux-hardware.org/?probe=8f23343086) | Apr 11, 2022 |
| Acer          | Nitro AN515-44              | [6748a96716](https://linux-hardware.org/?probe=6748a96716) | Apr 11, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [e6adfda5ec](https://linux-hardware.org/?probe=e6adfda5ec) | Apr 11, 2022 |
| Intel         | W7650                       | [7c970783e1](https://linux-hardware.org/?probe=7c970783e1) | Apr 11, 2022 |
| Dell          | Latitude E5400              | [0ac76c891f](https://linux-hardware.org/?probe=0ac76c891f) | Apr 11, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [50f8111e57](https://linux-hardware.org/?probe=50f8111e57) | Apr 10, 2022 |
| LG Electro... | U460-G.BG51P1               | [33afe2c679](https://linux-hardware.org/?probe=33afe2c679) | Apr 10, 2022 |
| Dell          | Inspiron 5458               | [7b3a49ec3c](https://linux-hardware.org/?probe=7b3a49ec3c) | Apr 09, 2022 |
| Dell          | Inspiron 15-3567            | [3ffa339c32](https://linux-hardware.org/?probe=3ffa339c32) | Apr 09, 2022 |
| Positivo      | N1250                       | [c64a47d6fc](https://linux-hardware.org/?probe=c64a47d6fc) | Apr 09, 2022 |
| Acer          | Aspire E1-531               | [9dbe75c090](https://linux-hardware.org/?probe=9dbe75c090) | Apr 09, 2022 |
| HP            | G42                         | [32fad98d60](https://linux-hardware.org/?probe=32fad98d60) | Apr 09, 2022 |
| Positivo      | S14CT01                     | [a98fcbb9f2](https://linux-hardware.org/?probe=a98fcbb9f2) | Apr 08, 2022 |
| LG Electro... | S430-G.BC33P1               | [95f8d514d6](https://linux-hardware.org/?probe=95f8d514d6) | Apr 08, 2022 |
| Acer          | Aspire E5-553G              | [cdc96ed221](https://linux-hardware.org/?probe=cdc96ed221) | Apr 08, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | [ca8d7c1137](https://linux-hardware.org/?probe=ca8d7c1137) | Apr 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [cd93e2fd82](https://linux-hardware.org/?probe=cd93e2fd82) | Apr 08, 2022 |
| Positivo      | NB50TH                      | [8b6dbaa2a6](https://linux-hardware.org/?probe=8b6dbaa2a6) | Apr 08, 2022 |
| Dell          | Latitude 5420               | [b107483192](https://linux-hardware.org/?probe=b107483192) | Apr 07, 2022 |
| HP            | ProBook 445 G7 Notebook ... | [0d15f8a702](https://linux-hardware.org/?probe=0d15f8a702) | Apr 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [54bc7d6864](https://linux-hardware.org/?probe=54bc7d6864) | Apr 07, 2022 |
| Dell          | Vostro 3560                 | [f29ab972e7](https://linux-hardware.org/?probe=f29ab972e7) | Apr 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [297454c537](https://linux-hardware.org/?probe=297454c537) | Apr 07, 2022 |
| HP            | ZBook 15 G6                 | [d98ca9a688](https://linux-hardware.org/?probe=d98ca9a688) | Apr 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [0f8f2d9229](https://linux-hardware.org/?probe=0f8f2d9229) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| Positivo      | S14SL01                     | [092f7c7d2b](https://linux-hardware.org/?probe=092f7c7d2b) | Apr 07, 2022 |
| Intel         | Shark Bay Client platfor... | [8b1a97afe3](https://linux-hardware.org/?probe=8b1a97afe3) | Apr 06, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [a6c37e7ee4](https://linux-hardware.org/?probe=a6c37e7ee4) | Apr 06, 2022 |
| Positivo      | Mobile                      | [024848f840](https://linux-hardware.org/?probe=024848f840) | Apr 06, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [7ba2d85c09](https://linux-hardware.org/?probe=7ba2d85c09) | Apr 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3719a80289](https://linux-hardware.org/?probe=3719a80289) | Apr 06, 2022 |
| Acer          | Nitro AN515-44              | [8c8679b57b](https://linux-hardware.org/?probe=8c8679b57b) | Apr 06, 2022 |
| Samsung       | 270E5J/2570EJ               | [0887c85f98](https://linux-hardware.org/?probe=0887c85f98) | Apr 06, 2022 |
| Dell          | Inspiron 5458               | [6caf8b778d](https://linux-hardware.org/?probe=6caf8b778d) | Apr 06, 2022 |
| Acer          | Aspire E5-576               | [520cbf0afa](https://linux-hardware.org/?probe=520cbf0afa) | Apr 06, 2022 |
| Dell          | Inspiron 5458               | [d430c4bae4](https://linux-hardware.org/?probe=d430c4bae4) | Apr 06, 2022 |
| LG Electro... | C400-G.BC22P1               | [652cd5fc07](https://linux-hardware.org/?probe=652cd5fc07) | Apr 06, 2022 |
| LG Electro... | C400-G.BC22P1               | [1f6514f558](https://linux-hardware.org/?probe=1f6514f558) | Apr 06, 2022 |
| ASUSTek       | 1015PE                      | [0643abbf5b](https://linux-hardware.org/?probe=0643abbf5b) | Apr 05, 2022 |
| Multilaser    | PC121                       | [f93e89718f](https://linux-hardware.org/?probe=f93e89718f) | Apr 05, 2022 |
| Dell          | Inspiron 15-3567            | [a5e25a491a](https://linux-hardware.org/?probe=a5e25a491a) | Apr 05, 2022 |
| Acer          | Nitro AN515-44              | [e007605c2c](https://linux-hardware.org/?probe=e007605c2c) | Apr 05, 2022 |
| ASUSTek       | GL502VT                     | [7f0692eb54](https://linux-hardware.org/?probe=7f0692eb54) | Apr 05, 2022 |
| Multilaser    | PC121                       | [31f2c02434](https://linux-hardware.org/?probe=31f2c02434) | Apr 05, 2022 |
| Philco        | 14H                         | [4408057803](https://linux-hardware.org/?probe=4408057803) | Apr 04, 2022 |
| Acer          | Aspire A515-45              | [eb69a7978b](https://linux-hardware.org/?probe=eb69a7978b) | Apr 04, 2022 |
| Dell          | Inspiron 5448               | [b8e5b302de](https://linux-hardware.org/?probe=b8e5b302de) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [4fdc33f1a2](https://linux-hardware.org/?probe=4fdc33f1a2) | Apr 04, 2022 |
| HP            | ElitePad 1000 G2            | [d479e2ae4a](https://linux-hardware.org/?probe=d479e2ae4a) | Apr 04, 2022 |
| Acer          | Nitro AN515-52              | [08491e74ef](https://linux-hardware.org/?probe=08491e74ef) | Apr 04, 2022 |
| Lenovo        | G400s VILG1                 | [93c2d9ec80](https://linux-hardware.org/?probe=93c2d9ec80) | Apr 03, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ecdd532a2c](https://linux-hardware.org/?probe=ecdd532a2c) | Apr 03, 2022 |
| Acer          | Nitro AN515-44              | [ab77f43b05](https://linux-hardware.org/?probe=ab77f43b05) | Apr 03, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [2f79554fe5](https://linux-hardware.org/?probe=2f79554fe5) | Apr 03, 2022 |
| HP            | Pavilion dm1                | [6b26166587](https://linux-hardware.org/?probe=6b26166587) | Apr 03, 2022 |
| Samsung       | 270E5J/2570EJ               | [2911dea3f0](https://linux-hardware.org/?probe=2911dea3f0) | Apr 02, 2022 |
| Dell          | Inspiron 7559               | [312811bfc3](https://linux-hardware.org/?probe=312811bfc3) | Apr 02, 2022 |
| Positivo      | S14CT01                     | [93170d0c1b](https://linux-hardware.org/?probe=93170d0c1b) | Apr 02, 2022 |
| Dell          | Inspiron 7559               | [a4c9ba22ca](https://linux-hardware.org/?probe=a4c9ba22ca) | Apr 02, 2022 |
| Dell          | Inspiron 5402               | [039209129c](https://linux-hardware.org/?probe=039209129c) | Apr 02, 2022 |
| Dell          | Inspiron 5402               | [45b26abf42](https://linux-hardware.org/?probe=45b26abf42) | Apr 02, 2022 |
| Acer          | Nitro AN515-44              | [53c0c6467d](https://linux-hardware.org/?probe=53c0c6467d) | Apr 01, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [9173259aed](https://linux-hardware.org/?probe=9173259aed) | Apr 01, 2022 |
| Avell High... | C62 MOB                     | [ca7d796269](https://linux-hardware.org/?probe=ca7d796269) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [eba4514371](https://linux-hardware.org/?probe=eba4514371) | Apr 01, 2022 |
| HP            | G42                         | [4768d00265](https://linux-hardware.org/?probe=4768d00265) | Apr 01, 2022 |
| Dell          | Inspiron 15-3567            | [47059c6626](https://linux-hardware.org/?probe=47059c6626) | Apr 01, 2022 |
| HP            | ElitePad 1000 G2            | [b6da5f9629](https://linux-hardware.org/?probe=b6da5f9629) | Apr 01, 2022 |
| Acer          | Nitro AN515-44              | [6a7bc096c0](https://linux-hardware.org/?probe=6a7bc096c0) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [606eb17f56](https://linux-hardware.org/?probe=606eb17f56) | Apr 01, 2022 |
| Multilaser    | PC13X                       | [d62e1676c3](https://linux-hardware.org/?probe=d62e1676c3) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [6b0cd44dbb](https://linux-hardware.org/?probe=6b0cd44dbb) | Apr 01, 2022 |
| Avell High... | A70 MOB                     | [9e095642f0](https://linux-hardware.org/?probe=9e095642f0) | Apr 01, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [21a9f5c811](https://linux-hardware.org/?probe=21a9f5c811) | Apr 01, 2022 |
| ASUSTek       | X102BA                      | [78ecf202d2](https://linux-hardware.org/?probe=78ecf202d2) | Apr 01, 2022 |
| Acer          | Nitro AN515-51              | [61a7788bfa](https://linux-hardware.org/?probe=61a7788bfa) | Mar 31, 2022 |
| Avell High... | B.ON                        | [d2628705e8](https://linux-hardware.org/?probe=d2628705e8) | Mar 31, 2022 |
| HP            | ElitePad 1000 G2            | [2ce0540229](https://linux-hardware.org/?probe=2ce0540229) | Mar 31, 2022 |
| HP            | ElitePad 1000 G2            | [f43d64639e](https://linux-hardware.org/?probe=f43d64639e) | Mar 31, 2022 |
| Multilaser    | PC13X                       | [e0e93fcf81](https://linux-hardware.org/?probe=e0e93fcf81) | Mar 30, 2022 |
| Acer          | Aspire 5050                 | [d01eb61b5a](https://linux-hardware.org/?probe=d01eb61b5a) | Mar 30, 2022 |
| Lenovo        | G40-80 80JE                 | [47c1543863](https://linux-hardware.org/?probe=47c1543863) | Mar 30, 2022 |
| HP            | Pavilion dv5                | [29096b57ad](https://linux-hardware.org/?probe=29096b57ad) | Mar 30, 2022 |
| Samsung       | 530XBB                      | [cf7f06b3fe](https://linux-hardware.org/?probe=cf7f06b3fe) | Mar 30, 2022 |
| Dell          | Vostro 15 3515              | [b61b3e31e7](https://linux-hardware.org/?probe=b61b3e31e7) | Mar 30, 2022 |
| Dell          | Inspiron 15-3567            | [323f2d9a1c](https://linux-hardware.org/?probe=323f2d9a1c) | Mar 30, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [af894bb443](https://linux-hardware.org/?probe=af894bb443) | Mar 30, 2022 |
| Dell          | Vostro 5402                 | [9fde02b49a](https://linux-hardware.org/?probe=9fde02b49a) | Mar 30, 2022 |
| Philco        | 14I                         | [f49a55854c](https://linux-hardware.org/?probe=f49a55854c) | Mar 30, 2022 |
| Avell High... | B.ON                        | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Acer          | Nitro AN515-44              | [36681f4a2f](https://linux-hardware.org/?probe=36681f4a2f) | Mar 28, 2022 |
| HP            | Pavilion g4                 | [5f8c09baeb](https://linux-hardware.org/?probe=5f8c09baeb) | Mar 28, 2022 |
| Dell          | Inspiron N5110              | [23eba220fc](https://linux-hardware.org/?probe=23eba220fc) | Mar 28, 2022 |
| Positivo      | Q464C                       | [16e296228a](https://linux-hardware.org/?probe=16e296228a) | Mar 28, 2022 |
| Acer          | Aspire A315-23G             | [94a20fae0d](https://linux-hardware.org/?probe=94a20fae0d) | Mar 28, 2022 |
| Intel         | W7650                       | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Multilaser    | PC13X_DS                    | [7f7481d038](https://linux-hardware.org/?probe=7f7481d038) | Mar 27, 2022 |
| Acer          | V5-171                      | [e1a668bda2](https://linux-hardware.org/?probe=e1a668bda2) | Mar 27, 2022 |
| Acer          | Aspire A315-41              | [1c9b405e1b](https://linux-hardware.org/?probe=1c9b405e1b) | Mar 27, 2022 |
| Acer          | Aspire A515-51              | [94cfb244c9](https://linux-hardware.org/?probe=94cfb244c9) | Mar 27, 2022 |
| Acer          | Aspire A515-51              | [b596ec9c95](https://linux-hardware.org/?probe=b596ec9c95) | Mar 27, 2022 |
| Toshiba       | Satellite A135              | [cf23c9bdb5](https://linux-hardware.org/?probe=cf23c9bdb5) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [f457ad3a65](https://linux-hardware.org/?probe=f457ad3a65) | Mar 27, 2022 |
| Dell          | Latitude 3410               | [503bb0a712](https://linux-hardware.org/?probe=503bb0a712) | Mar 27, 2022 |
| Dell          | Latitude 3410               | [5590356e12](https://linux-hardware.org/?probe=5590356e12) | Mar 27, 2022 |
| Acer          | Aspire A515-54G             | [b4864a1611](https://linux-hardware.org/?probe=b4864a1611) | Mar 27, 2022 |
| Dell          | Latitude E6430              | [1e9495c4f6](https://linux-hardware.org/?probe=1e9495c4f6) | Mar 27, 2022 |
| HP            | ElitePad 1000 G2            | [73be67de2c](https://linux-hardware.org/?probe=73be67de2c) | Mar 27, 2022 |
| Dell          | Inspiron 5548               | [710ec26531](https://linux-hardware.org/?probe=710ec26531) | Mar 27, 2022 |
| Positivo      | Q232A                       | [fe29ba6b10](https://linux-hardware.org/?probe=fe29ba6b10) | Mar 27, 2022 |
| Acer          | Aspire ES1-572              | [06ef38ab3e](https://linux-hardware.org/?probe=06ef38ab3e) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [d4655e802a](https://linux-hardware.org/?probe=d4655e802a) | Mar 26, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [081389ed06](https://linux-hardware.org/?probe=081389ed06) | Mar 26, 2022 |
| HP            | ElitePad 1000 G2            | [5861c8e75a](https://linux-hardware.org/?probe=5861c8e75a) | Mar 26, 2022 |
| Acer          | Aspire E5-573G              | [b78f0137ba](https://linux-hardware.org/?probe=b78f0137ba) | Mar 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [a7d9a4a0de](https://linux-hardware.org/?probe=a7d9a4a0de) | Mar 26, 2022 |
| Apple         | MacBookPro7,1               | [ca93a32a4b](https://linux-hardware.org/?probe=ca93a32a4b) | Mar 25, 2022 |
| Alienware     | m15 R6                      | [5505410995](https://linux-hardware.org/?probe=5505410995) | Mar 25, 2022 |
| Dell          | Vostro 7590                 | [1a15d49b97](https://linux-hardware.org/?probe=1a15d49b97) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [1ab1216e5b](https://linux-hardware.org/?probe=1ab1216e5b) | Mar 25, 2022 |
| Dell          | Vostro 5402                 | [b47655a721](https://linux-hardware.org/?probe=b47655a721) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [29d034d804](https://linux-hardware.org/?probe=29d034d804) | Mar 25, 2022 |
| Sony          | VGN-FW180D                  | [9bbcb3d0ac](https://linux-hardware.org/?probe=9bbcb3d0ac) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [ca13a081ff](https://linux-hardware.org/?probe=ca13a081ff) | Mar 25, 2022 |
| Samsung       | 550XDA                      | [3b0cca4251](https://linux-hardware.org/?probe=3b0cca4251) | Mar 25, 2022 |
| Avell High... | B.ON                        | [19b689aa12](https://linux-hardware.org/?probe=19b689aa12) | Mar 25, 2022 |
| Acer          | Aspire A315-23G             | [19cb24e20c](https://linux-hardware.org/?probe=19cb24e20c) | Mar 25, 2022 |
| Dell          | Latitude 7380               | [d3302e2138](https://linux-hardware.org/?probe=d3302e2138) | Mar 24, 2022 |
| Dell          | Vostro 5490                 | [1017a921d7](https://linux-hardware.org/?probe=1017a921d7) | Mar 24, 2022 |
| HP            | Pavilion 11 x360 PC         | [7c506671a1](https://linux-hardware.org/?probe=7c506671a1) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Lenovo        | V15 G2 ITL 82ME             | [f89824dbc7](https://linux-hardware.org/?probe=f89824dbc7) | Mar 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9612c1e4bd](https://linux-hardware.org/?probe=9612c1e4bd) | Mar 24, 2022 |
| Acer          | Aspire E5-553G              | [930cc740b2](https://linux-hardware.org/?probe=930cc740b2) | Mar 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [08c4b3b7a5](https://linux-hardware.org/?probe=08c4b3b7a5) | Mar 24, 2022 |
| Dell          | Vostro 5490                 | [bc18447c4b](https://linux-hardware.org/?probe=bc18447c4b) | Mar 24, 2022 |
| HP            | Pavilion g4                 | [bbb464378e](https://linux-hardware.org/?probe=bbb464378e) | Mar 23, 2022 |
| HP            | Laptop 15-db0xxx            | [ef1af7bbae](https://linux-hardware.org/?probe=ef1af7bbae) | Mar 23, 2022 |
| AMI           | Cherry Trail CR             | [af80d44a27](https://linux-hardware.org/?probe=af80d44a27) | Mar 23, 2022 |
| Dell          | Inspiron 3442               | [687fcb0605](https://linux-hardware.org/?probe=687fcb0605) | Mar 23, 2022 |
| Dell          | Vostro 5481                 | [82934a5fbf](https://linux-hardware.org/?probe=82934a5fbf) | Mar 23, 2022 |
| Positivo      | H14BT58                     | [3380c2e20d](https://linux-hardware.org/?probe=3380c2e20d) | Mar 23, 2022 |
| Acer          | Nitro AN515-44              | [4e75dbe2d2](https://linux-hardware.org/?probe=4e75dbe2d2) | Mar 23, 2022 |
| Acer          | Aspire 5750                 | [ef32f1be04](https://linux-hardware.org/?probe=ef32f1be04) | Mar 23, 2022 |
| Positivo      | C14CU51                     | [1ca3c10e9b](https://linux-hardware.org/?probe=1ca3c10e9b) | Mar 23, 2022 |
| Acer          | Nitro AN515-44              | [d2733b3c95](https://linux-hardware.org/?probe=d2733b3c95) | Mar 22, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [edaf75da5f](https://linux-hardware.org/?probe=edaf75da5f) | Mar 22, 2022 |
| Avell High... | B.ON                        | [28dd4cfea0](https://linux-hardware.org/?probe=28dd4cfea0) | Mar 22, 2022 |
| Dell          | Latitude 3410               | [d81534df3a](https://linux-hardware.org/?probe=d81534df3a) | Mar 22, 2022 |
| Sony          | VPCEH10EB                   | [921d432c3c](https://linux-hardware.org/?probe=921d432c3c) | Mar 22, 2022 |
| Dell          | Inspiron 5437               | [3b5a987609](https://linux-hardware.org/?probe=3b5a987609) | Mar 22, 2022 |
| Dell          | Inspiron 5566               | [de3d4db2c5](https://linux-hardware.org/?probe=de3d4db2c5) | Mar 22, 2022 |
| LG Electro... | R480-L.B211P1               | [0ab46e5aba](https://linux-hardware.org/?probe=0ab46e5aba) | Mar 22, 2022 |
| Dell          | Inspiron 5423               | [ea335b5e3b](https://linux-hardware.org/?probe=ea335b5e3b) | Mar 21, 2022 |
| ASUSTek       | K40IJ                       | [dbc0e61f47](https://linux-hardware.org/?probe=dbc0e61f47) | Mar 21, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [6b216c3e7c](https://linux-hardware.org/?probe=6b216c3e7c) | Mar 21, 2022 |
| Dell          | Latitude 3410               | [6d78749bd6](https://linux-hardware.org/?probe=6d78749bd6) | Mar 21, 2022 |
| Multilaser    | MLSH1H LINUX                | [fcf20188d2](https://linux-hardware.org/?probe=fcf20188d2) | Mar 21, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [0626cf6142](https://linux-hardware.org/?probe=0626cf6142) | Mar 21, 2022 |
| Acer          | Aspire A515-51G             | [aaf1f9eb09](https://linux-hardware.org/?probe=aaf1f9eb09) | Mar 20, 2022 |
| LG Electro... | A410-G.BC51P1               | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Apple         | MacBook5,2                  | [26c6fa4da4](https://linux-hardware.org/?probe=26c6fa4da4) | Mar 20, 2022 |
| Dell          | Latitude E6430              | [50348e45ec](https://linux-hardware.org/?probe=50348e45ec) | Mar 20, 2022 |
| Acer          | Aspire A315-23G             | [b5abf934a3](https://linux-hardware.org/?probe=b5abf934a3) | Mar 20, 2022 |
| Acer          | Aspire E1-571               | [ef43a1dac3](https://linux-hardware.org/?probe=ef43a1dac3) | Mar 20, 2022 |
| Dell          | Inspiron 7520               | [3617d07720](https://linux-hardware.org/?probe=3617d07720) | Mar 20, 2022 |
| Acer          | Nitro AN515-44              | [519b33398d](https://linux-hardware.org/?probe=519b33398d) | Mar 20, 2022 |
| Samsung       | 550XDA                      | [a5d8eebb8c](https://linux-hardware.org/?probe=a5d8eebb8c) | Mar 20, 2022 |
| Lenovo        | G550 2958                   | [ada99ba65e](https://linux-hardware.org/?probe=ada99ba65e) | Mar 19, 2022 |
| Compal        | NCL60/61                    | [39c9e97e85](https://linux-hardware.org/?probe=39c9e97e85) | Mar 19, 2022 |
| Dell          | Inspiron 5502               | [9719c4cdeb](https://linux-hardware.org/?probe=9719c4cdeb) | Mar 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [be18e33911](https://linux-hardware.org/?probe=be18e33911) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | [8366f92538](https://linux-hardware.org/?probe=8366f92538) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | [8f96005683](https://linux-hardware.org/?probe=8f96005683) | Mar 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [3693169add](https://linux-hardware.org/?probe=3693169add) | Mar 19, 2022 |
| Digibras      | NH4CU03                     | [7970a8e8d2](https://linux-hardware.org/?probe=7970a8e8d2) | Mar 19, 2022 |
| Positivo      | Mobile                      | [a1eb18d712](https://linux-hardware.org/?probe=a1eb18d712) | Mar 18, 2022 |
| Dell          | Inspiron 5566               | [7ab3aba611](https://linux-hardware.org/?probe=7ab3aba611) | Mar 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [3f17145276](https://linux-hardware.org/?probe=3f17145276) | Mar 18, 2022 |
| Philco        | 14I                         | [ceefb7fc2f](https://linux-hardware.org/?probe=ceefb7fc2f) | Mar 18, 2022 |
| Itautec       | Infoway w7535               | [e963149321](https://linux-hardware.org/?probe=e963149321) | Mar 18, 2022 |
| Acer          | Aspire A514-54G             | [9dc0d76053](https://linux-hardware.org/?probe=9dc0d76053) | Mar 17, 2022 |
| Lenovo        | G40-80 80JE                 | [c41639222f](https://linux-hardware.org/?probe=c41639222f) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [47a984d336](https://linux-hardware.org/?probe=47a984d336) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [75909ee2fc](https://linux-hardware.org/?probe=75909ee2fc) | Mar 17, 2022 |
| Acer          | Nitro AN515-44              | [be2d436df6](https://linux-hardware.org/?probe=be2d436df6) | Mar 17, 2022 |
| Acer          | Nitro AN515-44              | [05d071af74](https://linux-hardware.org/?probe=05d071af74) | Mar 16, 2022 |
| Acer          | Nitro AN515-44              | [83d37bb724](https://linux-hardware.org/?probe=83d37bb724) | Mar 16, 2022 |
| Positivo      | W942SW_SW1                  | [bd035566a4](https://linux-hardware.org/?probe=bd035566a4) | Mar 16, 2022 |
| Acer          | Nitro AN515-44              | [e5d7cda06b](https://linux-hardware.org/?probe=e5d7cda06b) | Mar 16, 2022 |
| Dell          | Inspiron 5502               | [09340e0b12](https://linux-hardware.org/?probe=09340e0b12) | Mar 16, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [be15e65580](https://linux-hardware.org/?probe=be15e65580) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | [62038e09e8](https://linux-hardware.org/?probe=62038e09e8) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | [cbebb0b476](https://linux-hardware.org/?probe=cbebb0b476) | Mar 15, 2022 |
| Intel         | powered classmate PC        | [6938945c70](https://linux-hardware.org/?probe=6938945c70) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| Lenovo        | ThinkPad R61 7733B46        | [d2220c6c2e](https://linux-hardware.org/?probe=d2220c6c2e) | Mar 14, 2022 |
| Dell          | G3 3500                     | [7c50a4be17](https://linux-hardware.org/?probe=7c50a4be17) | Mar 14, 2022 |
| Acer          | Aspire E5-553G              | [ebeea29eda](https://linux-hardware.org/?probe=ebeea29eda) | Mar 14, 2022 |
| HP            | ProBook 6465b               | [95ecc6cdbd](https://linux-hardware.org/?probe=95ecc6cdbd) | Mar 14, 2022 |
| Dell          | G3 3500                     | [65879fdfa3](https://linux-hardware.org/?probe=65879fdfa3) | Mar 14, 2022 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [38f9d1058f](https://linux-hardware.org/?probe=38f9d1058f) | Mar 14, 2022 |
| Positivo      | C14RV01                     | [c3bea5a62d](https://linux-hardware.org/?probe=c3bea5a62d) | Mar 14, 2022 |
| Dell          | Inspiron 3421               | [9636a8d68a](https://linux-hardware.org/?probe=9636a8d68a) | Mar 14, 2022 |
| Positivo      | Q232A                       | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| Positivo      | N1250                       | [e0ac8b69f1](https://linux-hardware.org/?probe=e0ac8b69f1) | Mar 13, 2022 |
| Acer          | Aspire E5-571               | [824c5eb97d](https://linux-hardware.org/?probe=824c5eb97d) | Mar 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [6b62eaea48](https://linux-hardware.org/?probe=6b62eaea48) | Mar 13, 2022 |
| Acer          | Aspire A515-52G             | [e86cb3194d](https://linux-hardware.org/?probe=e86cb3194d) | Mar 13, 2022 |
| HP            | Pavilion g4                 | [97be773922](https://linux-hardware.org/?probe=97be773922) | Mar 12, 2022 |
| HP            | Pavilion g4                 | [4ec085dcd5](https://linux-hardware.org/?probe=4ec085dcd5) | Mar 12, 2022 |
| Positivo      | S14CT01                     | [198fc329a3](https://linux-hardware.org/?probe=198fc329a3) | Mar 12, 2022 |
| Avell High... | B.ON                        | [3632f15fda](https://linux-hardware.org/?probe=3632f15fda) | Mar 12, 2022 |
| Dell          | Inspiron N4030              | [7828723d3d](https://linux-hardware.org/?probe=7828723d3d) | Mar 12, 2022 |
| Dell          | Inspiron N4030              | [22c9e04b22](https://linux-hardware.org/?probe=22c9e04b22) | Mar 12, 2022 |
| Dell          | Inspiron 5590               | [30f82f9c0a](https://linux-hardware.org/?probe=30f82f9c0a) | Mar 12, 2022 |
| Philco        | 10D                         | [c983be3bb0](https://linux-hardware.org/?probe=c983be3bb0) | Mar 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [a6ec683476](https://linux-hardware.org/?probe=a6ec683476) | Mar 11, 2022 |
| HP            | 1000                        | [c43fd3bfa5](https://linux-hardware.org/?probe=c43fd3bfa5) | Mar 11, 2022 |
| Acer          | Aspire A515-54              | [e5242e79bd](https://linux-hardware.org/?probe=e5242e79bd) | Mar 11, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [734698831b](https://linux-hardware.org/?probe=734698831b) | Mar 11, 2022 |
| Acer          | Aspire 5250                 | [a3f9e83752](https://linux-hardware.org/?probe=a3f9e83752) | Mar 11, 2022 |
| Dell          | Vostro 5471                 | [8248b17f01](https://linux-hardware.org/?probe=8248b17f01) | Mar 11, 2022 |
| ASUSTek       | X451CAP                     | [9a92c2571b](https://linux-hardware.org/?probe=9a92c2571b) | Mar 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| Acer          | Nitro AN515-54              | [cca64bfd46](https://linux-hardware.org/?probe=cca64bfd46) | Mar 10, 2022 |
| Dell          | Inspiron 7520               | [2e4bdb96fa](https://linux-hardware.org/?probe=2e4bdb96fa) | Mar 10, 2022 |
| Lenovo        | G400s VILG1                 | [d20ef03d37](https://linux-hardware.org/?probe=d20ef03d37) | Mar 10, 2022 |
| Chuwi         | HeroBook Air                | [674a4fbede](https://linux-hardware.org/?probe=674a4fbede) | Mar 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | [282f0e1f65](https://linux-hardware.org/?probe=282f0e1f65) | Mar 10, 2022 |
| Acer          | Aspire A315-56              | [dbc222289c](https://linux-hardware.org/?probe=dbc222289c) | Mar 10, 2022 |
| Dell          | Inspiron 3583               | [7280c9c630](https://linux-hardware.org/?probe=7280c9c630) | Mar 10, 2022 |
| Positivo      | S14CT01                     | [89ff3431e1](https://linux-hardware.org/?probe=89ff3431e1) | Mar 09, 2022 |
| Sony          | VJF153                      | [5aa5f532b7](https://linux-hardware.org/?probe=5aa5f532b7) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | [490da26167](https://linux-hardware.org/?probe=490da26167) | Mar 09, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [849f4141ce](https://linux-hardware.org/?probe=849f4141ce) | Mar 09, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [49503537f5](https://linux-hardware.org/?probe=49503537f5) | Mar 09, 2022 |
| Positivo      | CHT12CP                     | [fa7f40245b](https://linux-hardware.org/?probe=fa7f40245b) | Mar 09, 2022 |
| Dell          | Latitude 5420               | [81bcf5ce9c](https://linux-hardware.org/?probe=81bcf5ce9c) | Mar 09, 2022 |
| Acer          | Predator G3-572             | [56f568ccef](https://linux-hardware.org/?probe=56f568ccef) | Mar 08, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [e1e3698dbc](https://linux-hardware.org/?probe=e1e3698dbc) | Mar 08, 2022 |
| Samsung       | 550XDA                      | [cca05024ce](https://linux-hardware.org/?probe=cca05024ce) | Mar 08, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c7025ac75e](https://linux-hardware.org/?probe=c7025ac75e) | Mar 08, 2022 |
| Dell          | Vostro 3550                 | [25951f4351](https://linux-hardware.org/?probe=25951f4351) | Mar 08, 2022 |
| Dell          | Inspiron 5458               | [16f5e2d856](https://linux-hardware.org/?probe=16f5e2d856) | Mar 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f118a17b6e](https://linux-hardware.org/?probe=f118a17b6e) | Mar 08, 2022 |
| System76      | Lemur Pro                   | [69ce23b9f3](https://linux-hardware.org/?probe=69ce23b9f3) | Mar 07, 2022 |
| Acer          | Predator G3-572             | [156e7734be](https://linux-hardware.org/?probe=156e7734be) | Mar 07, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [88c5f71c1d](https://linux-hardware.org/?probe=88c5f71c1d) | Mar 07, 2022 |
| Sony          | SVE15111EBS                 | [5e2a00d875](https://linux-hardware.org/?probe=5e2a00d875) | Mar 07, 2022 |
| HP            | G42                         | [a6ea4c70b4](https://linux-hardware.org/?probe=a6ea4c70b4) | Mar 07, 2022 |
| Samsung       | 767XCL                      | [7685cdcfb9](https://linux-hardware.org/?probe=7685cdcfb9) | Mar 07, 2022 |
| HP            | G42                         | [77c16390cc](https://linux-hardware.org/?probe=77c16390cc) | Mar 07, 2022 |
| Sony          | SVE15111EBS                 | [49294d3345](https://linux-hardware.org/?probe=49294d3345) | Mar 06, 2022 |
| Acer          | Aspire A315-23G             | [852b569ef5](https://linux-hardware.org/?probe=852b569ef5) | Mar 06, 2022 |
| Avell High... | 1513                        | [c2a1be9b32](https://linux-hardware.org/?probe=c2a1be9b32) | Mar 06, 2022 |
| Sony          | SVE15111EBS                 | [f6c420fad1](https://linux-hardware.org/?probe=f6c420fad1) | Mar 06, 2022 |
| Lenovo        | G40-80 80JE                 | [2bf4890b1b](https://linux-hardware.org/?probe=2bf4890b1b) | Mar 06, 2022 |
| Dell          | Inspiron 5547               | [45abb29457](https://linux-hardware.org/?probe=45abb29457) | Mar 06, 2022 |
| Sony          | SVE15111EBS                 | [2a9bee0a38](https://linux-hardware.org/?probe=2a9bee0a38) | Mar 06, 2022 |
| Acer          | Aspire 4745Z                | [a3021ea674](https://linux-hardware.org/?probe=a3021ea674) | Mar 06, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [632b62bd7c](https://linux-hardware.org/?probe=632b62bd7c) | Mar 06, 2022 |
| Dell          | Inspiron 5547               | [d7c3e61995](https://linux-hardware.org/?probe=d7c3e61995) | Mar 06, 2022 |
| Positivo      | C14RV01                     | [2ac19f368f](https://linux-hardware.org/?probe=2ac19f368f) | Mar 06, 2022 |
| Dell          | Inspiron 5437               | [6b892c83ff](https://linux-hardware.org/?probe=6b892c83ff) | Mar 06, 2022 |
| Samsung       | 767XCL                      | [e01c76fd80](https://linux-hardware.org/?probe=e01c76fd80) | Mar 06, 2022 |
| Samsung       | 767XCL                      | [a45c6cfda9](https://linux-hardware.org/?probe=a45c6cfda9) | Mar 05, 2022 |
| Acer          | Aspire 5733                 | [79a1d21f1e](https://linux-hardware.org/?probe=79a1d21f1e) | Mar 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [54a840498f](https://linux-hardware.org/?probe=54a840498f) | Mar 05, 2022 |
| Positivo B... | VJC141F11X-B0111L           | [5699a5d3e2](https://linux-hardware.org/?probe=5699a5d3e2) | Mar 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [14fc889e5f](https://linux-hardware.org/?probe=14fc889e5f) | Mar 05, 2022 |
| Dell          | Inspiron N4030              | [ac4c492fcf](https://linux-hardware.org/?probe=ac4c492fcf) | Mar 05, 2022 |
| Dell          | Inspiron N4030              | [e5e17e5138](https://linux-hardware.org/?probe=e5e17e5138) | Mar 05, 2022 |
| Acer          | Aspire A515-51G             | [a578472a20](https://linux-hardware.org/?probe=a578472a20) | Mar 05, 2022 |
| Avell High... | A40 LIV                     | [6056996dfb](https://linux-hardware.org/?probe=6056996dfb) | Mar 05, 2022 |
| Positivo      | Q232A                       | [0244ef1064](https://linux-hardware.org/?probe=0244ef1064) | Mar 05, 2022 |
| Positivo      | Q232A                       | [1f2ae579f6](https://linux-hardware.org/?probe=1f2ae579f6) | Mar 05, 2022 |
| Acer          | Aspire A515-54              | [5119ee3a39](https://linux-hardware.org/?probe=5119ee3a39) | Mar 05, 2022 |
| Samsung       | 767XCL                      | [fddef2f8df](https://linux-hardware.org/?probe=fddef2f8df) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [be345eb07f](https://linux-hardware.org/?probe=be345eb07f) | Mar 04, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [779a3314fd](https://linux-hardware.org/?probe=779a3314fd) | Mar 04, 2022 |
| Positivo B... | VJFE52F11X-XXXXXX           | [d40ec33f5e](https://linux-hardware.org/?probe=d40ec33f5e) | Mar 04, 2022 |
| Avell High... | C62 MOB                     | [7557a0afed](https://linux-hardware.org/?probe=7557a0afed) | Mar 03, 2022 |
| Acer          | Aspire E5-553G              | [5597750b89](https://linux-hardware.org/?probe=5597750b89) | Mar 03, 2022 |
| Acer          | V5-171                      | [8c620eae72](https://linux-hardware.org/?probe=8c620eae72) | Mar 03, 2022 |
| Acer          | Aspire A515-51              | [77e4345afe](https://linux-hardware.org/?probe=77e4345afe) | Mar 03, 2022 |
| Sony          | VPCCW2UFX                   | [47587383d1](https://linux-hardware.org/?probe=47587383d1) | Mar 03, 2022 |
| Avell High... | A70 MOB                     | [09b1cd7548](https://linux-hardware.org/?probe=09b1cd7548) | Mar 03, 2022 |
| Dell          | Inspiron 3583               | [f87b97e105](https://linux-hardware.org/?probe=f87b97e105) | Mar 03, 2022 |
| OEM           | I42IL1                      | [0920ee7ed1](https://linux-hardware.org/?probe=0920ee7ed1) | Mar 03, 2022 |
| Positivo      | H14BT58                     | [5bcf783e8d](https://linux-hardware.org/?probe=5bcf783e8d) | Mar 02, 2022 |
| Positivo      | S14SL01                     | [7cea537f9c](https://linux-hardware.org/?probe=7cea537f9c) | Mar 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [35507d8b67](https://linux-hardware.org/?probe=35507d8b67) | Mar 02, 2022 |
| Positivo      | S14SL01                     | [066bae4a89](https://linux-hardware.org/?probe=066bae4a89) | Mar 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [9444d52862](https://linux-hardware.org/?probe=9444d52862) | Mar 02, 2022 |
| Lenovo        | G40-80 80JE                 | [476396ef7c](https://linux-hardware.org/?probe=476396ef7c) | Mar 02, 2022 |
| Samsung       | 670Z5E                      | [fd7ddf8a96](https://linux-hardware.org/?probe=fd7ddf8a96) | Mar 01, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [8c1bcab1d9](https://linux-hardware.org/?probe=8c1bcab1d9) | Mar 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ecd28158cc](https://linux-hardware.org/?probe=ecd28158cc) | Mar 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2d76cb0d68](https://linux-hardware.org/?probe=2d76cb0d68) | Mar 01, 2022 |
| Samsung       | 370E4K                      | [2aaabbb5c7](https://linux-hardware.org/?probe=2aaabbb5c7) | Mar 01, 2022 |
| Philco        | O E M                       | [47cc99022d](https://linux-hardware.org/?probe=47cc99022d) | Mar 01, 2022 |
| Acer          | Aspire E5-553G              | [f38fb6bf3f](https://linux-hardware.org/?probe=f38fb6bf3f) | Feb 28, 2022 |
| Acer          | Aspire 5050                 | [38a96041fa](https://linux-hardware.org/?probe=38a96041fa) | Feb 28, 2022 |
| Acer          | Aspire 5050                 | [c43798eb21](https://linux-hardware.org/?probe=c43798eb21) | Feb 28, 2022 |
| Dell          | Inspiron 5566               | [f0c13794e9](https://linux-hardware.org/?probe=f0c13794e9) | Feb 28, 2022 |
| Toshiba       | Satellite S55-C             | [e194d9993d](https://linux-hardware.org/?probe=e194d9993d) | Feb 28, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [122a25202d](https://linux-hardware.org/?probe=122a25202d) | Feb 28, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [846c33b65f](https://linux-hardware.org/?probe=846c33b65f) | Feb 28, 2022 |
| Acer          | Aspire A315-23G             | [21165232d6](https://linux-hardware.org/?probe=21165232d6) | Feb 28, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [cc638e722f](https://linux-hardware.org/?probe=cc638e722f) | Feb 27, 2022 |
| LG Electro... | C400-G.BC22P1               | [fb656318f6](https://linux-hardware.org/?probe=fb656318f6) | Feb 27, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [7cc9909959](https://linux-hardware.org/?probe=7cc9909959) | Feb 27, 2022 |
| Acer          | Aspire 5050                 | [6d4bc4aec1](https://linux-hardware.org/?probe=6d4bc4aec1) | Feb 27, 2022 |
| Positivo      | C14CU41TV                   | [7cabe0e07c](https://linux-hardware.org/?probe=7cabe0e07c) | Feb 27, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [e65c4dc3c7](https://linux-hardware.org/?probe=e65c4dc3c7) | Feb 26, 2022 |
| ASUSTek       | X451CAP                     | [733cc22d43](https://linux-hardware.org/?probe=733cc22d43) | Feb 26, 2022 |
| Samsung       | 550XDA                      | [460d65857c](https://linux-hardware.org/?probe=460d65857c) | Feb 26, 2022 |
| Samsung       | 550XDA                      | [a41870c5b7](https://linux-hardware.org/?probe=a41870c5b7) | Feb 26, 2022 |
| Samsung       | RF511/RF411/RF711           | [567a2d4073](https://linux-hardware.org/?probe=567a2d4073) | Feb 26, 2022 |
| HP            | Pavilion g4                 | [0e40990ec2](https://linux-hardware.org/?probe=0e40990ec2) | Feb 26, 2022 |
| Positivo B... | VJFE52F11X-B1111S           | [893011f788](https://linux-hardware.org/?probe=893011f788) | Feb 26, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [dfea927361](https://linux-hardware.org/?probe=dfea927361) | Feb 26, 2022 |
| Dell          | Inspiron 5537               | [72d6263861](https://linux-hardware.org/?probe=72d6263861) | Feb 26, 2022 |
| Acer          | Aspire E5-553G              | [17586d38de](https://linux-hardware.org/?probe=17586d38de) | Feb 26, 2022 |
| Dell          | Inspiron 5448               | [2458e07e0d](https://linux-hardware.org/?probe=2458e07e0d) | Feb 25, 2022 |
| Acer          | Aspire A315-42G             | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [9e276a3e5b](https://linux-hardware.org/?probe=9e276a3e5b) | Feb 25, 2022 |
| Acer          | Nitro AN515-44              | [8340571f28](https://linux-hardware.org/?probe=8340571f28) | Feb 25, 2022 |
| Acer          | Aspire A315-53              | [903ce0415a](https://linux-hardware.org/?probe=903ce0415a) | Feb 25, 2022 |
| Lenovo        | G40-80 80JE                 | [c55ba8cab2](https://linux-hardware.org/?probe=c55ba8cab2) | Feb 25, 2022 |
| Samsung       | RV415/RV515                 | [ba023e3489](https://linux-hardware.org/?probe=ba023e3489) | Feb 24, 2022 |
| Acer          | Aspire A315-34              | [d02db54216](https://linux-hardware.org/?probe=d02db54216) | Feb 24, 2022 |
| LG Electro... | S425-G.BC31P1               | [d08e9c2b6c](https://linux-hardware.org/?probe=d08e9c2b6c) | Feb 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [cbdc973c33](https://linux-hardware.org/?probe=cbdc973c33) | Feb 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b1354ad7df](https://linux-hardware.org/?probe=b1354ad7df) | Feb 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [7f2fc1617a](https://linux-hardware.org/?probe=7f2fc1617a) | Feb 24, 2022 |
| Samsung       | 530XBB                      | [88ec5ad0c4](https://linux-hardware.org/?probe=88ec5ad0c4) | Feb 24, 2022 |
| HP            | Pavilion dv4 2055br         | [11dee71ccf](https://linux-hardware.org/?probe=11dee71ccf) | Feb 24, 2022 |
| HP            | Pavilion dm1                | [cc944526a3](https://linux-hardware.org/?probe=cc944526a3) | Feb 24, 2022 |
| HP            | Pavilion dm1                | [6553871bc1](https://linux-hardware.org/?probe=6553871bc1) | Feb 24, 2022 |
| Toshiba       | IS 1412                     | [3621d1064d](https://linux-hardware.org/?probe=3621d1064d) | Feb 24, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [19a31feaf4](https://linux-hardware.org/?probe=19a31feaf4) | Feb 22, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [34efccbe97](https://linux-hardware.org/?probe=34efccbe97) | Feb 22, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [91c3328a21](https://linux-hardware.org/?probe=91c3328a21) | Feb 22, 2022 |
| Acer          | V5-171                      | [2ef877834d](https://linux-hardware.org/?probe=2ef877834d) | Feb 22, 2022 |
| Dell          | Latitude 3420               | [fb586744c3](https://linux-hardware.org/?probe=fb586744c3) | Feb 22, 2022 |
| LG Electro... | R410-L.D211P1               | [db073c90fd](https://linux-hardware.org/?probe=db073c90fd) | Feb 22, 2022 |
| Positivo      | Mobile                      | [5192d94c20](https://linux-hardware.org/?probe=5192d94c20) | Feb 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c4ba00804b](https://linux-hardware.org/?probe=c4ba00804b) | Feb 22, 2022 |
| Lenovo        | ThinkPad T420 4180LVP       | [f044c1a44d](https://linux-hardware.org/?probe=f044c1a44d) | Feb 21, 2022 |
| Acer          | Aspire E5-553G              | [750e864bf2](https://linux-hardware.org/?probe=750e864bf2) | Feb 21, 2022 |
| Acer          | Aspire E5-553G              | [c84d38d52f](https://linux-hardware.org/?probe=c84d38d52f) | Feb 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [d8c0892058](https://linux-hardware.org/?probe=d8c0892058) | Feb 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [fa1b42a476](https://linux-hardware.org/?probe=fa1b42a476) | Feb 21, 2022 |
| Positivo      | Smash                       | [68fd957c2e](https://linux-hardware.org/?probe=68fd957c2e) | Feb 21, 2022 |
| Acer          | Aspire A315-54              | [1a5f1021df](https://linux-hardware.org/?probe=1a5f1021df) | Feb 21, 2022 |
| Acer          | Aspire A515-54G             | [388a17923c](https://linux-hardware.org/?probe=388a17923c) | Feb 20, 2022 |
| Multilaser    | PC130                       | [4a49294d21](https://linux-hardware.org/?probe=4a49294d21) | Feb 20, 2022 |
| Multilaser    | PC130                       | [4681b7ae9e](https://linux-hardware.org/?probe=4681b7ae9e) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | [65c44b63d6](https://linux-hardware.org/?probe=65c44b63d6) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | [d8c4226f82](https://linux-hardware.org/?probe=d8c4226f82) | Feb 20, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [e844adcca1](https://linux-hardware.org/?probe=e844adcca1) | Feb 20, 2022 |
| HP            | Pavilion dv4 2055br         | [726c38b448](https://linux-hardware.org/?probe=726c38b448) | Feb 20, 2022 |
| Acer          | Aspire A315-34              | [642e1f0705](https://linux-hardware.org/?probe=642e1f0705) | Feb 20, 2022 |
| Acer          | Aspire A315-34              | [8c976c5259](https://linux-hardware.org/?probe=8c976c5259) | Feb 20, 2022 |
| Acer          | Nitro AN515-44              | [198452fc15](https://linux-hardware.org/?probe=198452fc15) | Feb 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [8a64c8dde8](https://linux-hardware.org/?probe=8a64c8dde8) | Feb 19, 2022 |
| Acer          | Aspire A515-54G             | [5d973743c8](https://linux-hardware.org/?probe=5d973743c8) | Feb 19, 2022 |
| Acer          | Nitro AN515-44              | [c73dc0aa9f](https://linux-hardware.org/?probe=c73dc0aa9f) | Feb 19, 2022 |
| Dell          | Inspiron 5590               | [f1f8a3c656](https://linux-hardware.org/?probe=f1f8a3c656) | Feb 19, 2022 |
| LG Electro... | U460-G.BG51P1               | [493da7c326](https://linux-hardware.org/?probe=493da7c326) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86af1dc736](https://linux-hardware.org/?probe=86af1dc736) | Feb 19, 2022 |
| Acer          | Aspire 4738                 | [f4b2c409f4](https://linux-hardware.org/?probe=f4b2c409f4) | Feb 19, 2022 |
| Positivo      | CHT14B                      | [c2f39e4414](https://linux-hardware.org/?probe=c2f39e4414) | Feb 19, 2022 |
| Positivo      | CHT14B                      | [674256dc2a](https://linux-hardware.org/?probe=674256dc2a) | Feb 19, 2022 |
| Samsung       | RC420/RC520/RC720           | [0b554c2d97](https://linux-hardware.org/?probe=0b554c2d97) | Feb 19, 2022 |
| Positivo      | S14CT01                     | [eac3e2cb5d](https://linux-hardware.org/?probe=eac3e2cb5d) | Feb 19, 2022 |
| Lenovo        | ThinkPad T440 20B7008ABR    | [b690de8548](https://linux-hardware.org/?probe=b690de8548) | Feb 19, 2022 |
| Acer          | Nitro AN515-44              | [cce1f45d54](https://linux-hardware.org/?probe=cce1f45d54) | Feb 19, 2022 |
| Lenovo        | Yoga 500-14IBD 80NE         | [8b199e2a77](https://linux-hardware.org/?probe=8b199e2a77) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ef345f036b](https://linux-hardware.org/?probe=ef345f036b) | Feb 19, 2022 |
| Acer          | Aspire V5-471               | [700b7ea8e8](https://linux-hardware.org/?probe=700b7ea8e8) | Feb 18, 2022 |
| Avell High... | B.ON                        | [9ef94d96d1](https://linux-hardware.org/?probe=9ef94d96d1) | Feb 18, 2022 |
| Acer          | Aspire 5741Z                | [93f3b53e77](https://linux-hardware.org/?probe=93f3b53e77) | Feb 18, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [c2df5bb692](https://linux-hardware.org/?probe=c2df5bb692) | Feb 18, 2022 |
| Intel         | W7650                       | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |
| Dell          | Latitude E5430 non-vPro     | [e0837f8e22](https://linux-hardware.org/?probe=e0837f8e22) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440 20B7003LBR    | [74fa6de20d](https://linux-hardware.org/?probe=74fa6de20d) | Feb 18, 2022 |
| Compaq        | Presario CQ-17              | [02d0a5926f](https://linux-hardware.org/?probe=02d0a5926f) | Feb 18, 2022 |
| Avell High... | B.ON                        | [3b3e1a7730](https://linux-hardware.org/?probe=3b3e1a7730) | Feb 18, 2022 |
| ATI           | BONEFISH                    | [caa7c41c75](https://linux-hardware.org/?probe=caa7c41c75) | Feb 17, 2022 |
| Positivo      | W942SW_SW1                  | [4a66255bed](https://linux-hardware.org/?probe=4a66255bed) | Feb 17, 2022 |
| Avell High... | B.ON                        | [26b25d67d6](https://linux-hardware.org/?probe=26b25d67d6) | Feb 17, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [311429d9ef](https://linux-hardware.org/?probe=311429d9ef) | Feb 16, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e03bf2b8a8](https://linux-hardware.org/?probe=e03bf2b8a8) | Feb 16, 2022 |
| Acer          | Nitro AN515-44              | [21d0529167](https://linux-hardware.org/?probe=21d0529167) | Feb 16, 2022 |
| Dell          | Inspiron 5468               | [06eaa64926](https://linux-hardware.org/?probe=06eaa64926) | Feb 15, 2022 |
| Intel         | W7650                       | [16cb290b88](https://linux-hardware.org/?probe=16cb290b88) | Feb 15, 2022 |
| LG Electro... | C400-G.BC22P1               | [e202260efb](https://linux-hardware.org/?probe=e202260efb) | Feb 14, 2022 |
| Avell High... | B.ON                        | [736bab4e42](https://linux-hardware.org/?probe=736bab4e42) | Feb 14, 2022 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [dfe8d18c8d](https://linux-hardware.org/?probe=dfe8d18c8d) | Feb 14, 2022 |
| Positivo      | CHT12CP                     | [d0d94ff35a](https://linux-hardware.org/?probe=d0d94ff35a) | Feb 14, 2022 |
| System76      | Galago Pro                  | [6ecd530026](https://linux-hardware.org/?probe=6ecd530026) | Feb 14, 2022 |
| Samsung       | 550XBE/350XBE               | [6846e14550](https://linux-hardware.org/?probe=6846e14550) | Feb 14, 2022 |
| Acer          | V5-171                      | [0200220f80](https://linux-hardware.org/?probe=0200220f80) | Feb 14, 2022 |
| System76      | Galago Pro                  | [b3b3e5cfa0](https://linux-hardware.org/?probe=b3b3e5cfa0) | Feb 14, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [aa3ec329c6](https://linux-hardware.org/?probe=aa3ec329c6) | Feb 14, 2022 |
| Dell          | Inspiron 1525               | [3db88da0ec](https://linux-hardware.org/?probe=3db88da0ec) | Feb 13, 2022 |
| Sony          | VGN-Z550N                   | [2ea7027f87](https://linux-hardware.org/?probe=2ea7027f87) | Feb 13, 2022 |
| HP            | 250 G7 Notebook PC          | [f2968206ac](https://linux-hardware.org/?probe=f2968206ac) | Feb 13, 2022 |
| Dell          | Latitude E7440              | [a43b6273dd](https://linux-hardware.org/?probe=a43b6273dd) | Feb 13, 2022 |
| Apple         | MacBookAir6,2               | [d7da9b2ff3](https://linux-hardware.org/?probe=d7da9b2ff3) | Feb 13, 2022 |
| Acer          | Aspire E5-553G              | [0303c5a132](https://linux-hardware.org/?probe=0303c5a132) | Feb 13, 2022 |
| Acer          | Aspire A315-53              | [2a2ca89607](https://linux-hardware.org/?probe=2a2ca89607) | Feb 13, 2022 |
| Dell          | Latitude E5450              | [09fa63b2aa](https://linux-hardware.org/?probe=09fa63b2aa) | Feb 13, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [de30d6bb15](https://linux-hardware.org/?probe=de30d6bb15) | Feb 13, 2022 |
| Acer          | Aspire A514-54              | [1f5dd04a09](https://linux-hardware.org/?probe=1f5dd04a09) | Feb 13, 2022 |
| Acer          | Aspire A315-23              | [2e9d58f492](https://linux-hardware.org/?probe=2e9d58f492) | Feb 13, 2022 |
| Dell          | Inspiron 3421               | [dd5c587aaa](https://linux-hardware.org/?probe=dd5c587aaa) | Feb 13, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80W2      | [045c989217](https://linux-hardware.org/?probe=045c989217) | Feb 13, 2022 |
| ASUSTek       | K84C                        | [4ca657e962](https://linux-hardware.org/?probe=4ca657e962) | Feb 12, 2022 |
| Dell          | Latitude 5490               | [4de050de9d](https://linux-hardware.org/?probe=4de050de9d) | Feb 12, 2022 |
| Lenovo        | G40-80 80JE                 | [efb0663602](https://linux-hardware.org/?probe=efb0663602) | Feb 12, 2022 |
| ASUSTek       | X540NA                      | [a9271fbd9f](https://linux-hardware.org/?probe=a9271fbd9f) | Feb 12, 2022 |
| Positivo      | N4340                       | [45302cfd33](https://linux-hardware.org/?probe=45302cfd33) | Feb 12, 2022 |
| Dell          | Inspiron 1545               | [037faea8f6](https://linux-hardware.org/?probe=037faea8f6) | Feb 12, 2022 |
| Acer          | Aspire 5738                 | [5124a5816c](https://linux-hardware.org/?probe=5124a5816c) | Feb 12, 2022 |
| Samsung       | 530XBB                      | [4da9be49c4](https://linux-hardware.org/?probe=4da9be49c4) | Feb 12, 2022 |
| ASUSTek       | K84C                        | [338aea772f](https://linux-hardware.org/?probe=338aea772f) | Feb 11, 2022 |
| Philco        | 10D                         | [562bb178d4](https://linux-hardware.org/?probe=562bb178d4) | Feb 11, 2022 |
| LG Electro... | A410-G.BC51P1               | [0caedcc26b](https://linux-hardware.org/?probe=0caedcc26b) | Feb 11, 2022 |
| Acer          | Nitro AN515-44              | [dbacdb1c14](https://linux-hardware.org/?probe=dbacdb1c14) | Feb 11, 2022 |
| ASUSTek       | X102BA                      | [401e015fff](https://linux-hardware.org/?probe=401e015fff) | Feb 11, 2022 |
| Acer          | Nitro AN515-44              | [f886f43d19](https://linux-hardware.org/?probe=f886f43d19) | Feb 11, 2022 |
| Samsung       | 670Z5E                      | [d6a821dc5b](https://linux-hardware.org/?probe=d6a821dc5b) | Feb 11, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [c400d6b3f2](https://linux-hardware.org/?probe=c400d6b3f2) | Feb 11, 2022 |
| Digibras      | CL341                       | [f3b678924d](https://linux-hardware.org/?probe=f3b678924d) | Feb 11, 2022 |
| HP            | ProBook 640 G4              | [c155b2bd06](https://linux-hardware.org/?probe=c155b2bd06) | Feb 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [bd8513dc66](https://linux-hardware.org/?probe=bd8513dc66) | Feb 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6a4a06344a](https://linux-hardware.org/?probe=6a4a06344a) | Feb 10, 2022 |
| ASUSTek       | Z450UAK                     | [d619483cc3](https://linux-hardware.org/?probe=d619483cc3) | Feb 10, 2022 |
| Sony          | VGN-Z550N                   | [92a2b7000d](https://linux-hardware.org/?probe=92a2b7000d) | Feb 10, 2022 |
| Sony          | VGN-Z550N                   | [9d1ed43ea9](https://linux-hardware.org/?probe=9d1ed43ea9) | Feb 10, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [b53861af9b](https://linux-hardware.org/?probe=b53861af9b) | Feb 09, 2022 |
| Avell High... | B.ON                        | [299d30a86c](https://linux-hardware.org/?probe=299d30a86c) | Feb 09, 2022 |
| ASUSTek       | X200MA                      | [dfb7099c69](https://linux-hardware.org/?probe=dfb7099c69) | Feb 09, 2022 |
| Positivo B... | VJFE52F11X-B1111S           | [75e404cde1](https://linux-hardware.org/?probe=75e404cde1) | Feb 09, 2022 |
| Acer          | Nitro AN515-54              | [3f2bbe863b](https://linux-hardware.org/?probe=3f2bbe863b) | Feb 09, 2022 |
| Lenovo        | IdeaPad G485 QAWGE          | [6e92f61334](https://linux-hardware.org/?probe=6e92f61334) | Feb 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [6e83303f73](https://linux-hardware.org/?probe=6e83303f73) | Feb 09, 2022 |
| Samsung       | 530XBB                      | [dd0298264f](https://linux-hardware.org/?probe=dd0298264f) | Feb 09, 2022 |
| Dell          | XPS L421X                   | [f84aa1d978](https://linux-hardware.org/?probe=f84aa1d978) | Feb 09, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [6140bf02fa](https://linux-hardware.org/?probe=6140bf02fa) | Feb 09, 2022 |
| Dell          | XPS L421X                   | [e869731d45](https://linux-hardware.org/?probe=e869731d45) | Feb 09, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0d09c987ef](https://linux-hardware.org/?probe=0d09c987ef) | Feb 09, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [3dffdcc5d3](https://linux-hardware.org/?probe=3dffdcc5d3) | Feb 09, 2022 |
| Razer         | Blade                       | [688d6b74bc](https://linux-hardware.org/?probe=688d6b74bc) | Feb 09, 2022 |
| Positivo      | N600                        | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Positivo      | N600                        | [1591046f31](https://linux-hardware.org/?probe=1591046f31) | Feb 08, 2022 |
| Acer          | Nitro AN515-44              | [74eb28f4a3](https://linux-hardware.org/?probe=74eb28f4a3) | Feb 08, 2022 |
| Dell          | Inspiron 15-3567            | [c5f7e8a1d6](https://linux-hardware.org/?probe=c5f7e8a1d6) | Feb 08, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [9aa6cb1e41](https://linux-hardware.org/?probe=9aa6cb1e41) | Feb 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [4b3eedcd91](https://linux-hardware.org/?probe=4b3eedcd91) | Feb 08, 2022 |
| Samsung       | 550XDA                      | [ec92003cdd](https://linux-hardware.org/?probe=ec92003cdd) | Feb 08, 2022 |
| Samsung       | 550XCJ/550XCR               | [36b7150c17](https://linux-hardware.org/?probe=36b7150c17) | Feb 08, 2022 |
| Sony          | VPCF236FM                   | [08bf40800a](https://linux-hardware.org/?probe=08bf40800a) | Feb 08, 2022 |
| Dell          | Inspiron 3542               | [9d53729c91](https://linux-hardware.org/?probe=9d53729c91) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Gateway       | NV55C                       | [27fd1ff7f1](https://linux-hardware.org/?probe=27fd1ff7f1) | Feb 07, 2022 |
| Acer          | Nitro AN515-54              | [38aadf36ea](https://linux-hardware.org/?probe=38aadf36ea) | Feb 07, 2022 |
| Lenovo        | ThinkPad E490 20N9A02FBR    | [f7c6505e86](https://linux-hardware.org/?probe=f7c6505e86) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| Acer          | Aspire A315-23G             | [09e661535f](https://linux-hardware.org/?probe=09e661535f) | Feb 07, 2022 |
| Acer          | Aspire E1-571               | [37a64d4872](https://linux-hardware.org/?probe=37a64d4872) | Feb 06, 2022 |
| Lenovo        | G40-80 80JE                 | [dd6e3f3a64](https://linux-hardware.org/?probe=dd6e3f3a64) | Feb 06, 2022 |
| Positivo      | C14CU51                     | [c3d5c7e4a7](https://linux-hardware.org/?probe=c3d5c7e4a7) | Feb 06, 2022 |
| Acer          | Aspire E5-553G              | [d6f8f41bc5](https://linux-hardware.org/?probe=d6f8f41bc5) | Feb 06, 2022 |
| Samsung       | 550XDA                      | [9c9b8d6672](https://linux-hardware.org/?probe=9c9b8d6672) | Feb 06, 2022 |
| Acer          | Aspire E5-553G              | [1f5badca6e](https://linux-hardware.org/?probe=1f5badca6e) | Feb 06, 2022 |
| ASUSTek       | K42F                        | [8bab320535](https://linux-hardware.org/?probe=8bab320535) | Feb 06, 2022 |
| Acer          | Aspire A315-53              | [345a864747](https://linux-hardware.org/?probe=345a864747) | Feb 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a41632fc91](https://linux-hardware.org/?probe=a41632fc91) | Feb 05, 2022 |
| Acer          | Nitro AN515-43              | [bf8d058c93](https://linux-hardware.org/?probe=bf8d058c93) | Feb 05, 2022 |
| Dell          | Inspiron 5537               | [79e02b1ade](https://linux-hardware.org/?probe=79e02b1ade) | Feb 05, 2022 |
| Samsung       | 530XBB                      | [ccc2c811de](https://linux-hardware.org/?probe=ccc2c811de) | Feb 05, 2022 |
| Itautec       | Infoway w7730               | [c3d571b041](https://linux-hardware.org/?probe=c3d571b041) | Feb 05, 2022 |
| HP            | Pavilion dm1                | [4b0fcd3df5](https://linux-hardware.org/?probe=4b0fcd3df5) | Feb 04, 2022 |
| Acer          | Nitro AN515-44              | [37c0fc9564](https://linux-hardware.org/?probe=37c0fc9564) | Feb 04, 2022 |
| Acer          | Nitro AN515-44              | [417bb2f526](https://linux-hardware.org/?probe=417bb2f526) | Feb 04, 2022 |
| Positivo      | Mobile                      | [762406b308](https://linux-hardware.org/?probe=762406b308) | Feb 04, 2022 |
| Acer          | Aspire V3-571               | [9a2365cd5c](https://linux-hardware.org/?probe=9a2365cd5c) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [1f4e97ac28](https://linux-hardware.org/?probe=1f4e97ac28) | Feb 04, 2022 |
| Dell          | Inspiron 7520               | [9b5cf9015f](https://linux-hardware.org/?probe=9b5cf9015f) | Feb 04, 2022 |
| Dell          | Latitude 5420               | [bbf52a52c3](https://linux-hardware.org/?probe=bbf52a52c3) | Feb 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [a720c94820](https://linux-hardware.org/?probe=a720c94820) | Feb 03, 2022 |
| Dell          | Latitude 5420               | [29b1f9a6d4](https://linux-hardware.org/?probe=29b1f9a6d4) | Feb 03, 2022 |
| Acer          | Aspire 5738                 | [fc543d0d57](https://linux-hardware.org/?probe=fc543d0d57) | Feb 03, 2022 |
| Acer          | Aspire A315-23G             | [ebc65d68d9](https://linux-hardware.org/?probe=ebc65d68d9) | Feb 03, 2022 |
| Dell          | Inspiron 7520               | [f260feda72](https://linux-hardware.org/?probe=f260feda72) | Feb 03, 2022 |
| Dell          | Inspiron N4050              | [1add69d20a](https://linux-hardware.org/?probe=1add69d20a) | Feb 03, 2022 |
| Samsung       | RV415/RV515                 | [1762291c98](https://linux-hardware.org/?probe=1762291c98) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | [a7b8841235](https://linux-hardware.org/?probe=a7b8841235) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | [f8f690a2b4](https://linux-hardware.org/?probe=f8f690a2b4) | Feb 02, 2022 |
| Samsung       | RV415/RV515                 | [1fc021cf65](https://linux-hardware.org/?probe=1fc021cf65) | Feb 02, 2022 |
| LG Electro... | S425-G.BC31P1               | [fa414c50c0](https://linux-hardware.org/?probe=fa414c50c0) | Feb 02, 2022 |
| Intel         | W7650                       | [930e8f9b6a](https://linux-hardware.org/?probe=930e8f9b6a) | Feb 02, 2022 |
| Intel         | W7650                       | [5ea44e43ef](https://linux-hardware.org/?probe=5ea44e43ef) | Feb 02, 2022 |
| Sony          | SVS13A25PBS                 | [9072890c1d](https://linux-hardware.org/?probe=9072890c1d) | Feb 02, 2022 |
| Sony          | SVS13A25PBS                 | [894e40654e](https://linux-hardware.org/?probe=894e40654e) | Feb 02, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6ad31c02f7](https://linux-hardware.org/?probe=6ad31c02f7) | Feb 02, 2022 |
| Dell          | Inspiron 5423               | [087f6b0b86](https://linux-hardware.org/?probe=087f6b0b86) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | [9d8d2dafa1](https://linux-hardware.org/?probe=9d8d2dafa1) | Feb 02, 2022 |
| Acer          | Nitro AN515-55              | [f12174ddb8](https://linux-hardware.org/?probe=f12174ddb8) | Feb 02, 2022 |
| Samsung       | 670Z5E                      | [874f163f65](https://linux-hardware.org/?probe=874f163f65) | Feb 02, 2022 |
| Notebook      | W35xSTQ_370ST               | [7b278e62d8](https://linux-hardware.org/?probe=7b278e62d8) | Feb 01, 2022 |
| Notebook      | W35xSTQ_370ST               | [5cc8e8f8d3](https://linux-hardware.org/?probe=5cc8e8f8d3) | Feb 01, 2022 |
| Samsung       | 270E5J/2570EJ               | [ac0fd77d33](https://linux-hardware.org/?probe=ac0fd77d33) | Feb 01, 2022 |
| HP            | ProBook 6465b               | [aca95b9f2d](https://linux-hardware.org/?probe=aca95b9f2d) | Feb 01, 2022 |
| Avell High... | B.ON                        | [845b25e77d](https://linux-hardware.org/?probe=845b25e77d) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d3a9e62b95](https://linux-hardware.org/?probe=d3a9e62b95) | Feb 01, 2022 |
| ASUSTek       | N53Ta                       | [7b343f4dfd](https://linux-hardware.org/?probe=7b343f4dfd) | Feb 01, 2022 |
| Acer          | Aspire E5-553G              | [93038a58a7](https://linux-hardware.org/?probe=93038a58a7) | Feb 01, 2022 |
| Lenovo        | ThinkPad Edge 05782GP       | [fc49fcb2f6](https://linux-hardware.org/?probe=fc49fcb2f6) | Jan 31, 2022 |
| Dell          | Inspiron 3576               | [4ea07fe50a](https://linux-hardware.org/?probe=4ea07fe50a) | Jan 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [54b9aa9f99](https://linux-hardware.org/?probe=54b9aa9f99) | Jan 31, 2022 |
| Acer          | Aspire A315-23G             | [d60beb8456](https://linux-hardware.org/?probe=d60beb8456) | Jan 31, 2022 |
| Itautec       | Infoway a7420               | [b58a27017b](https://linux-hardware.org/?probe=b58a27017b) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | [cf01ca64c3](https://linux-hardware.org/?probe=cf01ca64c3) | Jan 31, 2022 |
| Samsung       | R430/P430/R480              | [b08c9147e6](https://linux-hardware.org/?probe=b08c9147e6) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | [17015b4fbe](https://linux-hardware.org/?probe=17015b4fbe) | Jan 30, 2022 |
| Acer          | Aspire A315-23              | [7cf619e5e4](https://linux-hardware.org/?probe=7cf619e5e4) | Jan 30, 2022 |
| Acer          | Aspire A515-51              | [d38f4418f9](https://linux-hardware.org/?probe=d38f4418f9) | Jan 30, 2022 |
| Acer          | Aspire A515-51              | [f1987d67dc](https://linux-hardware.org/?probe=f1987d67dc) | Jan 30, 2022 |
| Acer          | Aspire A514-54              | [094fd8e853](https://linux-hardware.org/?probe=094fd8e853) | Jan 29, 2022 |
| Positivo      | H14BT58                     | [1469696155](https://linux-hardware.org/?probe=1469696155) | Jan 29, 2022 |
| Acer          | Nitro AN515-44              | [313d4824d2](https://linux-hardware.org/?probe=313d4824d2) | Jan 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4a98af8b6c](https://linux-hardware.org/?probe=4a98af8b6c) | Jan 29, 2022 |
| Acer          | Aspire A315-53              | [e0b0cbe190](https://linux-hardware.org/?probe=e0b0cbe190) | Jan 29, 2022 |
| Dell          | Inspiron 1525               | [cf0c5309ad](https://linux-hardware.org/?probe=cf0c5309ad) | Jan 29, 2022 |
| Toshiba       | Satellite S55-C             | [467509424b](https://linux-hardware.org/?probe=467509424b) | Jan 28, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [95423d6649](https://linux-hardware.org/?probe=95423d6649) | Jan 28, 2022 |
| Positivo      | Mobile                      | [c461425f95](https://linux-hardware.org/?probe=c461425f95) | Jan 28, 2022 |
| Acer          | Aspire 5738                 | [f35d941d2a](https://linux-hardware.org/?probe=f35d941d2a) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| Dell          | Inspiron 7560               | [ce1c4e39c2](https://linux-hardware.org/?probe=ce1c4e39c2) | Jan 28, 2022 |
| Acer          | Aspire E5-553G              | [6e72e70430](https://linux-hardware.org/?probe=6e72e70430) | Jan 28, 2022 |
| Acer          | Nitro AN515-53              | [dfcbe10351](https://linux-hardware.org/?probe=dfcbe10351) | Jan 28, 2022 |
| Dell          | Inspiron 15 3515            | [22a2219833](https://linux-hardware.org/?probe=22a2219833) | Jan 27, 2022 |
| Lenovo        | ThinkPad Edge E431 62779... | [622d718c89](https://linux-hardware.org/?probe=622d718c89) | Jan 27, 2022 |
| Positivo      | S14BW01                     | [b406634127](https://linux-hardware.org/?probe=b406634127) | Jan 27, 2022 |
| Acer          | Aspire A315-23G             | [f741575389](https://linux-hardware.org/?probe=f741575389) | Jan 27, 2022 |
| Dell          | Vostro 3500                 | [a952a9ecbb](https://linux-hardware.org/?probe=a952a9ecbb) | Jan 27, 2022 |
| Sony          | SVE14A15FBP                 | [df5205f4d5](https://linux-hardware.org/?probe=df5205f4d5) | Jan 27, 2022 |
| Positivo      | Harrison                    | [320f20f33d](https://linux-hardware.org/?probe=320f20f33d) | Jan 27, 2022 |
| Alienware     | x15 R1                      | [4d82c0e97f](https://linux-hardware.org/?probe=4d82c0e97f) | Jan 26, 2022 |
| Positivo B... | VJFE43F11X-XXXXXX           | [ef86245dd3](https://linux-hardware.org/?probe=ef86245dd3) | Jan 26, 2022 |
| Dell          | Inspiron 5502               | [d3df4ed8e6](https://linux-hardware.org/?probe=d3df4ed8e6) | Jan 26, 2022 |
| Acer          | Aspire E5-574G              | [0dab243a9d](https://linux-hardware.org/?probe=0dab243a9d) | Jan 26, 2022 |
| Acer          | Aspire E5-574G              | [eedcd1e054](https://linux-hardware.org/?probe=eedcd1e054) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [3e03426280](https://linux-hardware.org/?probe=3e03426280) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [4a3755734e](https://linux-hardware.org/?probe=4a3755734e) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [4283316d8a](https://linux-hardware.org/?probe=4283316d8a) | Jan 26, 2022 |
| Acer          | Aspire 4741                 | [bb695da9c9](https://linux-hardware.org/?probe=bb695da9c9) | Jan 26, 2022 |
| Acer          | Aspire A515-52G             | [57a443437c](https://linux-hardware.org/?probe=57a443437c) | Jan 26, 2022 |
| Acer          | Aspire V3-772               | [52bad055e2](https://linux-hardware.org/?probe=52bad055e2) | Jan 26, 2022 |
| Samsung       | 550XCJ/550XCR               | [934887404f](https://linux-hardware.org/?probe=934887404f) | Jan 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [8f09e74061](https://linux-hardware.org/?probe=8f09e74061) | Jan 26, 2022 |
| Acer          | Nitro AN515-52              | [e9f06efa7a](https://linux-hardware.org/?probe=e9f06efa7a) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [041c78217d](https://linux-hardware.org/?probe=041c78217d) | Jan 26, 2022 |
| Sony          | SVS13125PBB                 | [ad2c655a36](https://linux-hardware.org/?probe=ad2c655a36) | Jan 25, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [1816cd81d3](https://linux-hardware.org/?probe=1816cd81d3) | Jan 25, 2022 |
| HP            | G42                         | [3d3f5f2d07](https://linux-hardware.org/?probe=3d3f5f2d07) | Jan 25, 2022 |
| Compal        | Unknown                     | [d1d374e6df](https://linux-hardware.org/?probe=d1d374e6df) | Jan 25, 2022 |
| Dell          | G3 3500                     | [57dd97e7c8](https://linux-hardware.org/?probe=57dd97e7c8) | Jan 25, 2022 |
| Itautec       | Infoway N8755               | [34a8012b59](https://linux-hardware.org/?probe=34a8012b59) | Jan 25, 2022 |
| Dell          | Inspiron 5567               | [e0eb175311](https://linux-hardware.org/?probe=e0eb175311) | Jan 25, 2022 |
| Positivo      | Mobile                      | [9b53719e46](https://linux-hardware.org/?probe=9b53719e46) | Jan 25, 2022 |
| Positivo      | Mobile                      | [b5e6002477](https://linux-hardware.org/?probe=b5e6002477) | Jan 25, 2022 |
| Dell          | Inspiron 5566               | [184ff94e21](https://linux-hardware.org/?probe=184ff94e21) | Jan 25, 2022 |
| Dell          | Latitude 5420               | [3aad8f46c6](https://linux-hardware.org/?probe=3aad8f46c6) | Jan 24, 2022 |
| HP            | 250 G7 Notebook PC          | [032ee6d6c0](https://linux-hardware.org/?probe=032ee6d6c0) | Jan 24, 2022 |
| Dell          | Inspiron 3583               | [9ea2007217](https://linux-hardware.org/?probe=9ea2007217) | Jan 24, 2022 |
| Acer          | Aspire A315-34              | [8a843419b7](https://linux-hardware.org/?probe=8a843419b7) | Jan 23, 2022 |
| Positivo      | Q464C                       | [c5fa0e3561](https://linux-hardware.org/?probe=c5fa0e3561) | Jan 23, 2022 |
| Acer          | Nitro AN515-44              | [a74c254bb3](https://linux-hardware.org/?probe=a74c254bb3) | Jan 23, 2022 |
| Acer          | Aspire A315-23G             | [310b719b15](https://linux-hardware.org/?probe=310b719b15) | Jan 23, 2022 |
| Dell          | Vostro 1014                 | [16809ca9dd](https://linux-hardware.org/?probe=16809ca9dd) | Jan 22, 2022 |
| Acer          | Aspire A315-54              | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| Dell          | Latitude 3420               | [5cb8ff854b](https://linux-hardware.org/?probe=5cb8ff854b) | Jan 21, 2022 |
| HP            | 250 G7 Notebook PC          | [44abfe4d29](https://linux-hardware.org/?probe=44abfe4d29) | Jan 21, 2022 |
| Lenovo        | G400s VILG1                 | [4a721e7678](https://linux-hardware.org/?probe=4a721e7678) | Jan 21, 2022 |
| Dell          | Latitude 3420               | [2882c1a5d4](https://linux-hardware.org/?probe=2882c1a5d4) | Jan 21, 2022 |
| Sony          | SVS13125PBB                 | [6f5c214fe0](https://linux-hardware.org/?probe=6f5c214fe0) | Jan 21, 2022 |
| Acer          | Nitro AN515-44              | [e9a3d35409](https://linux-hardware.org/?probe=e9a3d35409) | Jan 21, 2022 |
| Acer          | Aspire A315-23G             | [164b959848](https://linux-hardware.org/?probe=164b959848) | Jan 21, 2022 |
| Philco        | 14I                         | [5006ca52e2](https://linux-hardware.org/?probe=5006ca52e2) | Jan 21, 2022 |
| Avell High... | C62 MOB                     | [11de4173b1](https://linux-hardware.org/?probe=11de4173b1) | Jan 21, 2022 |
| Positivo      | ES10IS2                     | [c4980689e4](https://linux-hardware.org/?probe=c4980689e4) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f5e870f95b](https://linux-hardware.org/?probe=f5e870f95b) | Jan 21, 2022 |
| Sony          | VPCYB15AB                   | [1d7c8aa76a](https://linux-hardware.org/?probe=1d7c8aa76a) | Jan 21, 2022 |
| Acer          | Aspire A315-41G             | [03a8c77758](https://linux-hardware.org/?probe=03a8c77758) | Jan 20, 2022 |
| Acer          | Aspire A315-41G             | [df698a1427](https://linux-hardware.org/?probe=df698a1427) | Jan 20, 2022 |
| Dell          | Inspiron 3583               | [1ab15ca104](https://linux-hardware.org/?probe=1ab15ca104) | Jan 20, 2022 |
| Acer          | Aspire A315-23G             | [c1b18abd63](https://linux-hardware.org/?probe=c1b18abd63) | Jan 20, 2022 |
| Lenovo        | B490 37722QP                | [6b32b6b8ef](https://linux-hardware.org/?probe=6b32b6b8ef) | Jan 20, 2022 |
| Multilaser    | UB32X                       | [bd6f4152df](https://linux-hardware.org/?probe=bd6f4152df) | Jan 20, 2022 |
| Dell          | Latitude E6330              | [c7b076f945](https://linux-hardware.org/?probe=c7b076f945) | Jan 20, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [6a311bab4a](https://linux-hardware.org/?probe=6a311bab4a) | Jan 19, 2022 |
| Positivo      | H14BU08                     | [8fb0d7e730](https://linux-hardware.org/?probe=8fb0d7e730) | Jan 19, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [0779d5bf00](https://linux-hardware.org/?probe=0779d5bf00) | Jan 19, 2022 |
| Acer          | Nitro AN517-51              | [fbcf7fffa8](https://linux-hardware.org/?probe=fbcf7fffa8) | Jan 19, 2022 |
| Samsung       | 550XDA                      | [cf44d057a0](https://linux-hardware.org/?probe=cf44d057a0) | Jan 19, 2022 |
| Lenovo        | B490 37722QP                | [3113fb2078](https://linux-hardware.org/?probe=3113fb2078) | Jan 18, 2022 |
| ASUSTek       | N46VM                       | [0a88f88571](https://linux-hardware.org/?probe=0a88f88571) | Jan 18, 2022 |
| Acer          | Nitro AN515-54              | [b6d4b36704](https://linux-hardware.org/?probe=b6d4b36704) | Jan 18, 2022 |
| Positivo      | S14SL01                     | [01a64fab08](https://linux-hardware.org/?probe=01a64fab08) | Jan 18, 2022 |
| ASUSTek       | N46VM                       | [4d85d5ff13](https://linux-hardware.org/?probe=4d85d5ff13) | Jan 18, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [839a67f960](https://linux-hardware.org/?probe=839a67f960) | Jan 18, 2022 |
| Positivo      | Mobile                      | [5f360ec080](https://linux-hardware.org/?probe=5f360ec080) | Jan 18, 2022 |
| Dell          | Inspiron N5110              | [719d452709](https://linux-hardware.org/?probe=719d452709) | Jan 18, 2022 |
| Dell          | Inspiron 3421               | [1f699a9a4d](https://linux-hardware.org/?probe=1f699a9a4d) | Jan 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [92d72ff4a1](https://linux-hardware.org/?probe=92d72ff4a1) | Jan 17, 2022 |
| LG Electro... | U460-G.BK51P1               | [de3d27183a](https://linux-hardware.org/?probe=de3d27183a) | Jan 17, 2022 |
| Compal        | NBLBX                       | [87344a7bf7](https://linux-hardware.org/?probe=87344a7bf7) | Jan 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7a5ba5f560](https://linux-hardware.org/?probe=7a5ba5f560) | Jan 16, 2022 |
| Dell          | Inspiron 5490               | [b3a3cf01c7](https://linux-hardware.org/?probe=b3a3cf01c7) | Jan 16, 2022 |
| Acer          | Aspire A315-53              | [4bcdec655f](https://linux-hardware.org/?probe=4bcdec655f) | Jan 16, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [30c9fe2f5f](https://linux-hardware.org/?probe=30c9fe2f5f) | Jan 16, 2022 |
| Lenovo        | ThinkPad T420 4180AG3       | [2c3cd27ad2](https://linux-hardware.org/?probe=2c3cd27ad2) | Jan 16, 2022 |
| Samsung       | 550XDA                      | [14e342e56d](https://linux-hardware.org/?probe=14e342e56d) | Jan 16, 2022 |
| Samsung       | 550XDA                      | [6c0b2cc195](https://linux-hardware.org/?probe=6c0b2cc195) | Jan 16, 2022 |
| Dell          | Vostro 5470                 | [1e97f26a27](https://linux-hardware.org/?probe=1e97f26a27) | Jan 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [5ede90aefe](https://linux-hardware.org/?probe=5ede90aefe) | Jan 15, 2022 |
| Dell          | Inspiron 1420               | [35d076d3df](https://linux-hardware.org/?probe=35d076d3df) | Jan 15, 2022 |
| Multilaser    | UB32X                       | [f65b37d922](https://linux-hardware.org/?probe=f65b37d922) | Jan 15, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [c52da73717](https://linux-hardware.org/?probe=c52da73717) | Jan 14, 2022 |
| Acer          | Aspire A515-54              | [3ea50d80ec](https://linux-hardware.org/?probe=3ea50d80ec) | Jan 14, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2d1fa4cb30](https://linux-hardware.org/?probe=2d1fa4cb30) | Jan 14, 2022 |
| LG Electro... | R580-G.BP21P1               | [925fe25a7c](https://linux-hardware.org/?probe=925fe25a7c) | Jan 13, 2022 |
| HP            | 240 G6 Notebook PC          | [792a79c2fb](https://linux-hardware.org/?probe=792a79c2fb) | Jan 13, 2022 |
| Dell          | Latitude 5420               | [ab13df4cd4](https://linux-hardware.org/?probe=ab13df4cd4) | Jan 13, 2022 |
| Dell          | Vostro 3300                 | [d9ee3ea8d1](https://linux-hardware.org/?probe=d9ee3ea8d1) | Jan 13, 2022 |
| Lenovo        | G40-70 80GA                 | [6321546415](https://linux-hardware.org/?probe=6321546415) | Jan 12, 2022 |
| Dell          | Inspiron 1545               | [f598674489](https://linux-hardware.org/?probe=f598674489) | Jan 12, 2022 |
| Dell          | Inspiron 1545               | [2a29726d59](https://linux-hardware.org/?probe=2a29726d59) | Jan 12, 2022 |
| Acer          | Aspire A515-51              | [b4c83278e2](https://linux-hardware.org/?probe=b4c83278e2) | Jan 12, 2022 |
| Dell          | Inspiron 7348               | [acd1da8f35](https://linux-hardware.org/?probe=acd1da8f35) | Jan 12, 2022 |
| Compal        | NCL60/61                    | [3f71d0d088](https://linux-hardware.org/?probe=3f71d0d088) | Jan 12, 2022 |
| ASUSTek       | Z550SA                      | [322fa160ae](https://linux-hardware.org/?probe=322fa160ae) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | [6b764029b7](https://linux-hardware.org/?probe=6b764029b7) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | [60f264617e](https://linux-hardware.org/?probe=60f264617e) | Jan 11, 2022 |
| Acer          | Aspire V5-471               | [7411a4cc5e](https://linux-hardware.org/?probe=7411a4cc5e) | Jan 11, 2022 |
| Dell          | Vostro 3300                 | [5ed8f41517](https://linux-hardware.org/?probe=5ed8f41517) | Jan 11, 2022 |
| Dell          | Vostro 3300                 | [f67eed490e](https://linux-hardware.org/?probe=f67eed490e) | Jan 11, 2022 |
| Apple         | MacBookPro9,2               | [34acf9099a](https://linux-hardware.org/?probe=34acf9099a) | Jan 11, 2022 |
| Acer          | Aspire A315-34              | [52197b0dea](https://linux-hardware.org/?probe=52197b0dea) | Jan 11, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [12077557be](https://linux-hardware.org/?probe=12077557be) | Jan 11, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [73dbecedf2](https://linux-hardware.org/?probe=73dbecedf2) | Jan 11, 2022 |
| Dell          | Vostro 1520                 | [2278a225cd](https://linux-hardware.org/?probe=2278a225cd) | Jan 11, 2022 |
| Dell          | Inspiron N5110              | [c9765c772f](https://linux-hardware.org/?probe=c9765c772f) | Jan 11, 2022 |
| Positivo      | N600                        | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| Acer          | Nitro AN515-55              | [33159068d9](https://linux-hardware.org/?probe=33159068d9) | Jan 10, 2022 |
| ASUSTek       | K53SD                       | [dfa3a6df3f](https://linux-hardware.org/?probe=dfa3a6df3f) | Jan 10, 2022 |
| ASUSTek       | K53SD                       | [c7ec6cce32](https://linux-hardware.org/?probe=c7ec6cce32) | Jan 10, 2022 |
| Lenovo        | B490 37722LP                | [c36fa4c158](https://linux-hardware.org/?probe=c36fa4c158) | Jan 10, 2022 |
| LG Electro... | A530-T.BE76P1               | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Acer          | Aspire A315-34              | [609662084d](https://linux-hardware.org/?probe=609662084d) | Jan 09, 2022 |
| Dell          | Inspiron 7560               | [18daf15e61](https://linux-hardware.org/?probe=18daf15e61) | Jan 09, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [6b6c84515a](https://linux-hardware.org/?probe=6b6c84515a) | Jan 09, 2022 |
| Dell          | Latitude E5400              | [4f72d3dae0](https://linux-hardware.org/?probe=4f72d3dae0) | Jan 09, 2022 |
| HP            | ProBook 6450b               | [cf1a585619](https://linux-hardware.org/?probe=cf1a585619) | Jan 09, 2022 |
| Dell          | Inspiron 5557               | [fb29216e68](https://linux-hardware.org/?probe=fb29216e68) | Jan 09, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [ceb31a41b4](https://linux-hardware.org/?probe=ceb31a41b4) | Jan 08, 2022 |
| Lenovo        | G460 20041                  | [feff8775da](https://linux-hardware.org/?probe=feff8775da) | Jan 08, 2022 |
| Dell          | Inspiron 7560               | [a17707c45d](https://linux-hardware.org/?probe=a17707c45d) | Jan 08, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [6c9118e320](https://linux-hardware.org/?probe=6c9118e320) | Jan 08, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [103f52795a](https://linux-hardware.org/?probe=103f52795a) | Jan 08, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [c87cec55bd](https://linux-hardware.org/?probe=c87cec55bd) | Jan 07, 2022 |
| HP            | Compaq 6910p (GX316UC#AB... | [0ffa23c15e](https://linux-hardware.org/?probe=0ffa23c15e) | Jan 07, 2022 |
| HP            | 240 G6 Notebook PC          | [079d91dda3](https://linux-hardware.org/?probe=079d91dda3) | Jan 07, 2022 |
| Dell          | Latitude 5420               | [ab3973e74b](https://linux-hardware.org/?probe=ab3973e74b) | Jan 07, 2022 |
| Dell          | Latitude 5420               | [517adf10a8](https://linux-hardware.org/?probe=517adf10a8) | Jan 06, 2022 |
| Acer          | Aspire A315-23G             | [d22f32f071](https://linux-hardware.org/?probe=d22f32f071) | Jan 06, 2022 |
| Acer          | Aspire A315-42              | [5222b66726](https://linux-hardware.org/?probe=5222b66726) | Jan 05, 2022 |
| Samsung       | 550XDA                      | [1bdf544285](https://linux-hardware.org/?probe=1bdf544285) | Jan 05, 2022 |
| Lenovo        | Y720-15IKB 81CQ             | [13cbd87036](https://linux-hardware.org/?probe=13cbd87036) | Jan 05, 2022 |
| Dell          | Inspiron 5566               | [8355b9f07c](https://linux-hardware.org/?probe=8355b9f07c) | Jan 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcc46e9fcb](https://linux-hardware.org/?probe=bcc46e9fcb) | Jan 05, 2022 |
| HP            | ProBook 4430s               | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | IdeaPad Z470                | [b6c0836e89](https://linux-hardware.org/?probe=b6c0836e89) | Jan 04, 2022 |
| Dell          | Inspiron N5110              | [d15eb36c4f](https://linux-hardware.org/?probe=d15eb36c4f) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| ASUSTek       | K46CA                       | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Dell          | Vostro 5402                 | [c66b09770b](https://linux-hardware.org/?probe=c66b09770b) | Jan 04, 2022 |
| Dell          | Vostro 5402                 | [e41a208158](https://linux-hardware.org/?probe=e41a208158) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| HP            | Pavilion dv2700             | [c8aafbbc8d](https://linux-hardware.org/?probe=c8aafbbc8d) | Jan 04, 2022 |
| Dell          | Inspiron 5402               | [3cae008c9d](https://linux-hardware.org/?probe=3cae008c9d) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
| Samsung       | 750XBE/730XBE               | [5608016bcb](https://linux-hardware.org/?probe=5608016bcb) | Jan 03, 2022 |
| HP            | ENVY TS 15                  | [bb57e8f3b9](https://linux-hardware.org/?probe=bb57e8f3b9) | Jan 03, 2022 |
| Dell          | Inspiron N5110              | [b0877f3054](https://linux-hardware.org/?probe=b0877f3054) | Jan 03, 2022 |
| Dell          | Inspiron 15-3567            | [8bec3c5b12](https://linux-hardware.org/?probe=8bec3c5b12) | Jan 03, 2022 |
| Dell          | Inspiron 5458               | [47887a95e0](https://linux-hardware.org/?probe=47887a95e0) | Jan 02, 2022 |
| Positivo      | Q464C                       | [6b04ee9d48](https://linux-hardware.org/?probe=6b04ee9d48) | Jan 02, 2022 |
| Dell          | Inspiron 3583               | [4b12ee93be](https://linux-hardware.org/?probe=4b12ee93be) | Jan 02, 2022 |
| HP            | Compaq Presario CQ43        | [af69f165f8](https://linux-hardware.org/?probe=af69f165f8) | Jan 02, 2022 |
| HP            | Compaq Presario CQ43        | [6e0b499d88](https://linux-hardware.org/?probe=6e0b499d88) | Jan 02, 2022 |
| Samsung       | 300E5M/300E5L               | [3d96bb9bc2](https://linux-hardware.org/?probe=3d96bb9bc2) | Jan 02, 2022 |
| Dell          | Inspiron 1428               | [29a20cfbd9](https://linux-hardware.org/?probe=29a20cfbd9) | Jan 02, 2022 |
| Apple         | MacBookPro9,2               | [d70ae1191d](https://linux-hardware.org/?probe=d70ae1191d) | Jan 02, 2022 |
| Dell          | Inspiron 15-3567            | [355b4fcf61](https://linux-hardware.org/?probe=355b4fcf61) | Jan 02, 2022 |
| Digibras      | NH4CU03                     | [ffd9717d80](https://linux-hardware.org/?probe=ffd9717d80) | Jan 02, 2022 |
| Acer          | Nitro AN515-44              | [be76922082](https://linux-hardware.org/?probe=be76922082) | Jan 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [f6393f5788](https://linux-hardware.org/?probe=f6393f5788) | Jan 01, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [e0415c1970](https://linux-hardware.org/?probe=e0415c1970) | Jan 01, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [d7774870db](https://linux-hardware.org/?probe=d7774870db) | Jan 01, 2022 |
| Dell          | Inspiron 5480               | [cf92148eac](https://linux-hardware.org/?probe=cf92148eac) | Jan 01, 2022 |
| HP            | G60                         | [08350a2b75](https://linux-hardware.org/?probe=08350a2b75) | Jan 01, 2022 |
| Toshiba       | AS 1301                     | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| Dell          | Inspiron 7560               | [1521c2f202](https://linux-hardware.org/?probe=1521c2f202) | Jan 01, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [74de092c5f](https://linux-hardware.org/?probe=74de092c5f) | Jan 01, 2022 |
| Positivo      | SW6H                        | [a7566e6187](https://linux-hardware.org/?probe=a7566e6187) | Jan 01, 2022 |
| Dell          | Inspiron 7560               | [1b7b408372](https://linux-hardware.org/?probe=1b7b408372) | Dec 31, 2021 |
| Dell          | Inspiron 7560               | [18fb6b8c3d](https://linux-hardware.org/?probe=18fb6b8c3d) | Dec 31, 2021 |
| Acer          | Aspire VX5-591G             | [0a7a64e88d](https://linux-hardware.org/?probe=0a7a64e88d) | Dec 31, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [0bfa74fa9f](https://linux-hardware.org/?probe=0bfa74fa9f) | Dec 31, 2021 |
| Dell          | Latitude E6230              | [fd4e9c6d43](https://linux-hardware.org/?probe=fd4e9c6d43) | Dec 31, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [2ddd424f94](https://linux-hardware.org/?probe=2ddd424f94) | Dec 31, 2021 |
| Lenovo        | G460 20041                  | [65aab50b2c](https://linux-hardware.org/?probe=65aab50b2c) | Dec 31, 2021 |
| Dell          | Inspiron 5458on             | [265cd0c910](https://linux-hardware.org/?probe=265cd0c910) | Dec 31, 2021 |
| Samsung       | 270E5G/270E5U               | [0f92fab3db](https://linux-hardware.org/?probe=0f92fab3db) | Dec 31, 2021 |
| Dell          | Inspiron 5447               | [0012b60e04](https://linux-hardware.org/?probe=0012b60e04) | Dec 31, 2021 |
| Dell          | Inspiron 5447               | [ee494391f7](https://linux-hardware.org/?probe=ee494391f7) | Dec 31, 2021 |
| Samsung       | 550XDA                      | [8f01f7ab00](https://linux-hardware.org/?probe=8f01f7ab00) | Dec 30, 2021 |
| Dell          | Inspiron N5110              | [f73a2b3505](https://linux-hardware.org/?probe=f73a2b3505) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | [17548c6fc7](https://linux-hardware.org/?probe=17548c6fc7) | Dec 30, 2021 |
| HP            | Unknown                     | [e1eb3d8838](https://linux-hardware.org/?probe=e1eb3d8838) | Dec 30, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [c076e4939e](https://linux-hardware.org/?probe=c076e4939e) | Dec 30, 2021 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e4d3f29412](https://linux-hardware.org/?probe=e4d3f29412) | Dec 30, 2021 |
| Acer          | Nitro AN515-54              | [deb4e10a41](https://linux-hardware.org/?probe=deb4e10a41) | Dec 29, 2021 |
| Dell          | Inspiron N5110              | [3e4ab4e082](https://linux-hardware.org/?probe=3e4ab4e082) | Dec 29, 2021 |
| Dell          | Latitude 5420               | [42e63fd746](https://linux-hardware.org/?probe=42e63fd746) | Dec 29, 2021 |
| Dell          | Latitude 5420               | [ae4bf2544b](https://linux-hardware.org/?probe=ae4bf2544b) | Dec 29, 2021 |
| Acer          | Nitro AN515-44              | [0ba9ee7a74](https://linux-hardware.org/?probe=0ba9ee7a74) | Dec 29, 2021 |
| Dell          | Inspiron 5490               | [863f8366a7](https://linux-hardware.org/?probe=863f8366a7) | Dec 29, 2021 |
| Dell          | Inspiron 5490               | [6214557268](https://linux-hardware.org/?probe=6214557268) | Dec 29, 2021 |
| Acer          | Aspire A315-34              | [93ddeaab25](https://linux-hardware.org/?probe=93ddeaab25) | Dec 29, 2021 |
| Apple         | MacBookPro9,2               | [18a966b290](https://linux-hardware.org/?probe=18a966b290) | Dec 29, 2021 |
| Samsung       | RF511/RF411/RF711           | [7c247b0c9f](https://linux-hardware.org/?probe=7c247b0c9f) | Dec 29, 2021 |
| Acer          | Aspire A315-54K             | [b662c9c046](https://linux-hardware.org/?probe=b662c9c046) | Dec 28, 2021 |
| Samsung       | RF511/RF411/RF711           | [5cff8b82d5](https://linux-hardware.org/?probe=5cff8b82d5) | Dec 28, 2021 |
| Acer          | Aspire A315-34              | [af582ea780](https://linux-hardware.org/?probe=af582ea780) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| Dell          | Inspiron 15-3567            | [be839fd24d](https://linux-hardware.org/?probe=be839fd24d) | Dec 28, 2021 |
| Dell          | Inspiron 7560               | [5ad630b5e5](https://linux-hardware.org/?probe=5ad630b5e5) | Dec 28, 2021 |
| ASUSTek       | G74Sx                       | [7ae1568f36](https://linux-hardware.org/?probe=7ae1568f36) | Dec 27, 2021 |
| Dell          | Inspiron 5537               | [f4878864ec](https://linux-hardware.org/?probe=f4878864ec) | Dec 27, 2021 |
| Avell High... | A70 MOB                     | [dac7555e81](https://linux-hardware.org/?probe=dac7555e81) | Dec 27, 2021 |
| ASUSTek       | X45U                        | [55d2da3313](https://linux-hardware.org/?probe=55d2da3313) | Dec 27, 2021 |
| Acer          | Aspire A315-53              | [eaee471d35](https://linux-hardware.org/?probe=eaee471d35) | Dec 27, 2021 |
| Dell          | Inspiron 5570               | [d0059fcd5a](https://linux-hardware.org/?probe=d0059fcd5a) | Dec 27, 2021 |
| Sony          | SVT11125CBS                 | [961f242a60](https://linux-hardware.org/?probe=961f242a60) | Dec 27, 2021 |
| Acer          | Aspire A315-23G             | [8262ba8f4a](https://linux-hardware.org/?probe=8262ba8f4a) | Dec 27, 2021 |
| Acer          | Aspire A315-53              | [5e78de369f](https://linux-hardware.org/?probe=5e78de369f) | Dec 27, 2021 |
| Acer          | Aspire A315-53              | [8cf9037edf](https://linux-hardware.org/?probe=8cf9037edf) | Dec 27, 2021 |
| Dell          | Inspiron 3583               | [adcf14bf31](https://linux-hardware.org/?probe=adcf14bf31) | Dec 27, 2021 |
| Positivo      | V142N_4G                    | [fb167e6518](https://linux-hardware.org/?probe=fb167e6518) | Dec 27, 2021 |
| OEM           | I38II                       | [52bc5190dd](https://linux-hardware.org/?probe=52bc5190dd) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| Acer          | Nitro AN515-44              | [d0bf339bdf](https://linux-hardware.org/?probe=d0bf339bdf) | Dec 26, 2021 |
| Dell          | Inspiron 7572               | [661d4c5b99](https://linux-hardware.org/?probe=661d4c5b99) | Dec 26, 2021 |
| Dell          | Inspiron 5502               | [42837842b9](https://linux-hardware.org/?probe=42837842b9) | Dec 26, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9a6b436bcb](https://linux-hardware.org/?probe=9a6b436bcb) | Dec 26, 2021 |
| Avell High... | A62 LIV                     | [06de3a03ad](https://linux-hardware.org/?probe=06de3a03ad) | Dec 26, 2021 |
| HP            | Compaq Presario CQ43        | [19fc1f14de](https://linux-hardware.org/?probe=19fc1f14de) | Dec 26, 2021 |
| Acer          | Aspire M5-481T              | [2515a869a5](https://linux-hardware.org/?probe=2515a869a5) | Dec 26, 2021 |
| Acer          | Aspire M5-481T              | [1ef9b940b2](https://linux-hardware.org/?probe=1ef9b940b2) | Dec 26, 2021 |
| Acer          | Aspire A315-42G             | [453f75585c](https://linux-hardware.org/?probe=453f75585c) | Dec 25, 2021 |
| LG Electro... | A410-G.BC51P1               | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Lenovo        | V470 439627U                | [7c44d560dc](https://linux-hardware.org/?probe=7c44d560dc) | Dec 24, 2021 |
| HP            | Compaq Presario CQ43        | [8a9469ae9b](https://linux-hardware.org/?probe=8a9469ae9b) | Dec 24, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [6eec25d058](https://linux-hardware.org/?probe=6eec25d058) | Dec 24, 2021 |
| Acer          | Aspire 5250                 | [bef8e4334a](https://linux-hardware.org/?probe=bef8e4334a) | Dec 23, 2021 |
| Positivo B... | VJFE42F11X-XXXXXX           | [f6beaa3bcc](https://linux-hardware.org/?probe=f6beaa3bcc) | Dec 23, 2021 |
| Dell          | System Vostro 3450          | [9499015c46](https://linux-hardware.org/?probe=9499015c46) | Dec 23, 2021 |
| Acer          | Nitro AN515-54              | [3a101db74b](https://linux-hardware.org/?probe=3a101db74b) | Dec 23, 2021 |
| Acer          | Aspire A315-34              | [40e8ac4ece](https://linux-hardware.org/?probe=40e8ac4ece) | Dec 23, 2021 |
| Lenovo        | V470 439627U                | [71387b4f47](https://linux-hardware.org/?probe=71387b4f47) | Dec 23, 2021 |
| Positivo      | CHT14B                      | [ae9f7801cf](https://linux-hardware.org/?probe=ae9f7801cf) | Dec 23, 2021 |
| Positivo      | CHT14B                      | [3efc353498](https://linux-hardware.org/?probe=3efc353498) | Dec 23, 2021 |
| Dell          | Vostro 3480                 | [99e4c4339b](https://linux-hardware.org/?probe=99e4c4339b) | Dec 22, 2021 |
| Dell          | Inspiron 5447               | [83331a9c7c](https://linux-hardware.org/?probe=83331a9c7c) | Dec 22, 2021 |
| Lenovo        | ThinkPad E14 20RBS3LV00     | [c3ff7fe60b](https://linux-hardware.org/?probe=c3ff7fe60b) | Dec 22, 2021 |
| Lenovo        | ThinkPad E14 20RBS3LV00     | [4a65927165](https://linux-hardware.org/?probe=4a65927165) | Dec 22, 2021 |
| Dell          | Inspiron 5547               | [605e3df140](https://linux-hardware.org/?probe=605e3df140) | Dec 22, 2021 |
| ASUSTek       | G74Sx                       | [ac5f615cbd](https://linux-hardware.org/?probe=ac5f615cbd) | Dec 22, 2021 |
| Dell          | Inspiron 5437               | [c44547da71](https://linux-hardware.org/?probe=c44547da71) | Dec 22, 2021 |
| OEM           | B14HM21                     | [8b8a787f86](https://linux-hardware.org/?probe=8b8a787f86) | Dec 22, 2021 |
| Acer          | Aspire E1-571               | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Acer          | Aspire E1-571               | [842eae5b1d](https://linux-hardware.org/?probe=842eae5b1d) | Dec 22, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [985fc37716](https://linux-hardware.org/?probe=985fc37716) | Dec 22, 2021 |
| Apple         | MacBookPro7,1               | [5994dbd498](https://linux-hardware.org/?probe=5994dbd498) | Dec 21, 2021 |
| HP            | Compaq Mini 311-1100        | [d1aaa6b464](https://linux-hardware.org/?probe=d1aaa6b464) | Dec 21, 2021 |
| ASUSTek       | X55U                        | [6c10bfc423](https://linux-hardware.org/?probe=6c10bfc423) | Dec 21, 2021 |
| Apple         | MacBookPro7,1               | [5f47284626](https://linux-hardware.org/?probe=5f47284626) | Dec 21, 2021 |
| Dell          | Inspiron 15-3567            | [6c17de2a03](https://linux-hardware.org/?probe=6c17de2a03) | Dec 21, 2021 |
| Apple         | MacBookPro4,1               | [855e5ba65d](https://linux-hardware.org/?probe=855e5ba65d) | Dec 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9775119696](https://linux-hardware.org/?probe=9775119696) | Dec 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [148afb76d9](https://linux-hardware.org/?probe=148afb76d9) | Dec 21, 2021 |
| Avell High... | A62 LIV                     | [b2108dd133](https://linux-hardware.org/?probe=b2108dd133) | Dec 21, 2021 |
| HP            | G42                         | [9253a8caf5](https://linux-hardware.org/?probe=9253a8caf5) | Dec 20, 2021 |
| ASUSTek       | X555UB                      | [32b9121efc](https://linux-hardware.org/?probe=32b9121efc) | Dec 20, 2021 |
| Dell          | Inspiron 15-3567            | [44d2768522](https://linux-hardware.org/?probe=44d2768522) | Dec 20, 2021 |
| Dell          | Inspiron N4030              | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| Digibras      | NH4CU03                     | [517425552d](https://linux-hardware.org/?probe=517425552d) | Dec 19, 2021 |
| Samsung       | 270E5J/2570EJ               | [a15986fe04](https://linux-hardware.org/?probe=a15986fe04) | Dec 19, 2021 |
| Dell          | Inspiron N4050              | [069b0b5d94](https://linux-hardware.org/?probe=069b0b5d94) | Dec 19, 2021 |
| Acer          | Unknown                     | [21b566f81d](https://linux-hardware.org/?probe=21b566f81d) | Dec 19, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [fbd0755545](https://linux-hardware.org/?probe=fbd0755545) | Dec 19, 2021 |
| MSI           | GT80 2QC                    | [68b70c6ff9](https://linux-hardware.org/?probe=68b70c6ff9) | Dec 19, 2021 |
| HP            | Compaq Presario CQ43        | [95d53051a2](https://linux-hardware.org/?probe=95d53051a2) | Dec 19, 2021 |
| HP            | Compaq Presario CQ43        | [7841090d93](https://linux-hardware.org/?probe=7841090d93) | Dec 18, 2021 |
| Apple         | MacBookPro8,1               | [44b1bbbb9c](https://linux-hardware.org/?probe=44b1bbbb9c) | Dec 18, 2021 |
| Acer          | Nitro AN515-53              | [a9affc8e28](https://linux-hardware.org/?probe=a9affc8e28) | Dec 18, 2021 |
| Dell          | Inspiron 5490               | [861cccd79f](https://linux-hardware.org/?probe=861cccd79f) | Dec 18, 2021 |
| Samsung       | 550XDA                      | [6b3fd04b47](https://linux-hardware.org/?probe=6b3fd04b47) | Dec 18, 2021 |
| Acer          | Aspire 5733                 | [3854ed74f2](https://linux-hardware.org/?probe=3854ed74f2) | Dec 17, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [57431951a3](https://linux-hardware.org/?probe=57431951a3) | Dec 17, 2021 |
| Acer          | V5-171                      | [2058672bcf](https://linux-hardware.org/?probe=2058672bcf) | Dec 17, 2021 |
| Positivo      | C14CR21TV                   | [e9cbfcb4b8](https://linux-hardware.org/?probe=e9cbfcb4b8) | Dec 17, 2021 |
| HP            | Pavilion 14                 | [be9e6368e4](https://linux-hardware.org/?probe=be9e6368e4) | Dec 17, 2021 |
| Acer          | Aspire A515-52              | [c21343c233](https://linux-hardware.org/?probe=c21343c233) | Dec 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d3de4858ff](https://linux-hardware.org/?probe=d3de4858ff) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | [58eb588f8b](https://linux-hardware.org/?probe=58eb588f8b) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | [84cabc70f7](https://linux-hardware.org/?probe=84cabc70f7) | Dec 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ecf858d3fa](https://linux-hardware.org/?probe=ecf858d3fa) | Dec 16, 2021 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [7ca51b2384](https://linux-hardware.org/?probe=7ca51b2384) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Positivo      | S14BW01                     | [94de31910c](https://linux-hardware.org/?probe=94de31910c) | Dec 16, 2021 |
| Acer          | Aspire E1-571               | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| Acer          | Aspire 5750Z                | [6a4339303f](https://linux-hardware.org/?probe=6a4339303f) | Dec 15, 2021 |
| Samsung       | 275E4E/275E5E               | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| Dell          | Inspiron N5010              | [061faf00df](https://linux-hardware.org/?probe=061faf00df) | Dec 15, 2021 |
| Acer          | Aspire A315-34              | [c76d68c4fd](https://linux-hardware.org/?probe=c76d68c4fd) | Dec 15, 2021 |
| ASUSTek       | K43U                        | [d7df2cd94e](https://linux-hardware.org/?probe=d7df2cd94e) | Dec 15, 2021 |
| Dell          | Vostro 5402                 | [e57dc7794c](https://linux-hardware.org/?probe=e57dc7794c) | Dec 15, 2021 |
| Dell          | Vostro 5402                 | [2cc6e5b35b](https://linux-hardware.org/?probe=2cc6e5b35b) | Dec 15, 2021 |
| Unknown       | Unknown                     | [9e4b4af367](https://linux-hardware.org/?probe=9e4b4af367) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Dell          | Inspiron N5110              | [885ea098ef](https://linux-hardware.org/?probe=885ea098ef) | Dec 15, 2021 |
| Acer          | Nitro AN517-51              | [214ea4e512](https://linux-hardware.org/?probe=214ea4e512) | Dec 15, 2021 |
| Dell          | Vostro 3583                 | [ce55356c09](https://linux-hardware.org/?probe=ce55356c09) | Dec 15, 2021 |
| Positivo      | W942SW_SW1                  | [8022ee0ceb](https://linux-hardware.org/?probe=8022ee0ceb) | Dec 14, 2021 |
| Acer          | Nitro AN515-44              | [4a44000cf0](https://linux-hardware.org/?probe=4a44000cf0) | Dec 14, 2021 |
| Acer          | Nitro AN517-51              | [9002ea7794](https://linux-hardware.org/?probe=9002ea7794) | Dec 14, 2021 |
| Dell          | Inspiron 15 5510            | [dd29feeb10](https://linux-hardware.org/?probe=dd29feeb10) | Dec 14, 2021 |
| Digibras      | NH4CU03                     | [97b0f21219](https://linux-hardware.org/?probe=97b0f21219) | Dec 14, 2021 |
| Acer          | Aspire A315-23              | [9e321117dd](https://linux-hardware.org/?probe=9e321117dd) | Dec 13, 2021 |
| Acer          | Nitro AN515-44              | [44d2be94f6](https://linux-hardware.org/?probe=44d2be94f6) | Dec 13, 2021 |
| Samsung       | RV415/RV515                 | [16af5a00db](https://linux-hardware.org/?probe=16af5a00db) | Dec 13, 2021 |
| Acer          | Aspire A515-52              | [ef791632cf](https://linux-hardware.org/?probe=ef791632cf) | Dec 13, 2021 |
| Dell          | Vostro 5402                 | [2074bdb7a5](https://linux-hardware.org/?probe=2074bdb7a5) | Dec 13, 2021 |
| Dell          | Vostro 5490                 | [2259c467c8](https://linux-hardware.org/?probe=2259c467c8) | Dec 13, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [770a0db869](https://linux-hardware.org/?probe=770a0db869) | Dec 13, 2021 |
| Digibras      | NH4CU03                     | [5ffb383677](https://linux-hardware.org/?probe=5ffb383677) | Dec 13, 2021 |
| Sony          | VPCYB15AB                   | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| Avell High... | A70 LIV                     | [3930fc87b1](https://linux-hardware.org/?probe=3930fc87b1) | Dec 12, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [499d539995](https://linux-hardware.org/?probe=499d539995) | Dec 12, 2021 |
| MSI           | Katana GF66 11UC            | [4160ab78a5](https://linux-hardware.org/?probe=4160ab78a5) | Dec 12, 2021 |
| Acer          | Aspire A515-52              | [d9958d2f46](https://linux-hardware.org/?probe=d9958d2f46) | Dec 12, 2021 |
| Positivo      | CHT14B                      | [6ebdfd7b1f](https://linux-hardware.org/?probe=6ebdfd7b1f) | Dec 12, 2021 |
| Acer          | Nitro AN515-44              | [f5ae8cd0ac](https://linux-hardware.org/?probe=f5ae8cd0ac) | Dec 12, 2021 |
| Dell          | Inspiron 3421               | [b18adbf17f](https://linux-hardware.org/?probe=b18adbf17f) | Dec 11, 2021 |
| Dell          | Vostro 3550                 | [ffd4903a50](https://linux-hardware.org/?probe=ffd4903a50) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [7d7873b658](https://linux-hardware.org/?probe=7d7873b658) | Dec 11, 2021 |
| Dell          | Vostro 3550                 | [8fa258429d](https://linux-hardware.org/?probe=8fa258429d) | Dec 11, 2021 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [3c1c997421](https://linux-hardware.org/?probe=3c1c997421) | Dec 11, 2021 |
| Acer          | Nitro AN515-44              | [1acc5eb194](https://linux-hardware.org/?probe=1acc5eb194) | Dec 10, 2021 |
| Acer          | Aspire A514-53              | [eb51cb66cb](https://linux-hardware.org/?probe=eb51cb66cb) | Dec 10, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [1c9ca21f4e](https://linux-hardware.org/?probe=1c9ca21f4e) | Dec 10, 2021 |
| Acer          | Aspire A315-23              | [ed02327600](https://linux-hardware.org/?probe=ed02327600) | Dec 10, 2021 |
| Lenovo        | V14 G2 ITL 82NM             | [939be3ba51](https://linux-hardware.org/?probe=939be3ba51) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [176194b06f](https://linux-hardware.org/?probe=176194b06f) | Dec 10, 2021 |
| OEM           | I38II                       | [b4db17dc1d](https://linux-hardware.org/?probe=b4db17dc1d) | Dec 10, 2021 |
| Acer          | Aspire A315-34              | [862ca9280c](https://linux-hardware.org/?probe=862ca9280c) | Dec 10, 2021 |
| Acer          | Aspire A514-53              | [90975ac5a8](https://linux-hardware.org/?probe=90975ac5a8) | Dec 09, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [17d73377a6](https://linux-hardware.org/?probe=17d73377a6) | Dec 09, 2021 |
| LG Electro... | A410-G.BC49P1               | [5f952dc625](https://linux-hardware.org/?probe=5f952dc625) | Dec 09, 2021 |
| Dell          | Inspiron 7472               | [64b7b3a797](https://linux-hardware.org/?probe=64b7b3a797) | Dec 09, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [d32c954439](https://linux-hardware.org/?probe=d32c954439) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [24da5b4ebe](https://linux-hardware.org/?probe=24da5b4ebe) | Dec 08, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [eff62b036a](https://linux-hardware.org/?probe=eff62b036a) | Dec 08, 2021 |
| Razer         | Blade 15 Advanced Model ... | [ccc253bb9a](https://linux-hardware.org/?probe=ccc253bb9a) | Dec 08, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [b8c7e334d0](https://linux-hardware.org/?probe=b8c7e334d0) | Dec 08, 2021 |
| Dell          | Vostro 3583                 | [5c12c4090b](https://linux-hardware.org/?probe=5c12c4090b) | Dec 08, 2021 |
| HP            | Unknown                     | [33ca2db025](https://linux-hardware.org/?probe=33ca2db025) | Dec 07, 2021 |
| Dell          | Vostro 5481                 | [aff3262599](https://linux-hardware.org/?probe=aff3262599) | Dec 07, 2021 |
| Avell High... | B.ON                        | [5bfb9e677a](https://linux-hardware.org/?probe=5bfb9e677a) | Dec 07, 2021 |
| Avell High... | B.ON                        | [d2b832ea0a](https://linux-hardware.org/?probe=d2b832ea0a) | Dec 07, 2021 |
| Dell          | Inspiron 5566               | [9fa66d6287](https://linux-hardware.org/?probe=9fa66d6287) | Dec 07, 2021 |
| Dell          | Inspiron 5566               | [4bc9eb7cea](https://linux-hardware.org/?probe=4bc9eb7cea) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [ad406a6f63](https://linux-hardware.org/?probe=ad406a6f63) | Dec 07, 2021 |
| Dell          | Inspiron 7520               | [d4b308c0c8](https://linux-hardware.org/?probe=d4b308c0c8) | Dec 07, 2021 |
| Intel         | HuronRiver Platform         | [95d3387e6c](https://linux-hardware.org/?probe=95d3387e6c) | Dec 07, 2021 |
| Samsung       | 550XDA                      | [948f6de494](https://linux-hardware.org/?probe=948f6de494) | Dec 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [1b7cc00c10](https://linux-hardware.org/?probe=1b7cc00c10) | Dec 07, 2021 |
| Acer          | Aspire A315-34              | [7fe252c0cd](https://linux-hardware.org/?probe=7fe252c0cd) | Dec 07, 2021 |
| Acer          | Nitro AN515-44              | [88d9ee29b4](https://linux-hardware.org/?probe=88d9ee29b4) | Dec 07, 2021 |
| Dell          | Latitude 3420               | [4885c88ddc](https://linux-hardware.org/?probe=4885c88ddc) | Dec 06, 2021 |
| Positivo      | J14AL11                     | [2e5fd22945](https://linux-hardware.org/?probe=2e5fd22945) | Dec 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [059c42fd1a](https://linux-hardware.org/?probe=059c42fd1a) | Dec 06, 2021 |
| Acer          | Aspire A515-52              | [9df7d7ad8f](https://linux-hardware.org/?probe=9df7d7ad8f) | Dec 06, 2021 |
| Acer          | Aspire E1-421               | [a7c18d534d](https://linux-hardware.org/?probe=a7c18d534d) | Dec 06, 2021 |
| Acer          | Nitro AN515-54              | [7763d72707](https://linux-hardware.org/?probe=7763d72707) | Dec 06, 2021 |
| Toshiba       | IS-1253                     | [0b8914d4c8](https://linux-hardware.org/?probe=0b8914d4c8) | Dec 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ed493cd76f](https://linux-hardware.org/?probe=ed493cd76f) | Dec 05, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a838b63586](https://linux-hardware.org/?probe=a838b63586) | Dec 05, 2021 |
| Acer          | Aspire E1-572               | [a3524e5c56](https://linux-hardware.org/?probe=a3524e5c56) | Dec 05, 2021 |
| Acer          | Aspire A315-34              | [b4382c3b38](https://linux-hardware.org/?probe=b4382c3b38) | Dec 04, 2021 |
| Positivo      | NB50TH                      | [705bae2d39](https://linux-hardware.org/?probe=705bae2d39) | Dec 04, 2021 |
| Acer          | Aspire A514-54G             | [ff52dd520c](https://linux-hardware.org/?probe=ff52dd520c) | Dec 04, 2021 |
| Acer          | Nitro AN515-54              | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Avell High... | B.ON                        | [91a81934ed](https://linux-hardware.org/?probe=91a81934ed) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | [bc211e09fd](https://linux-hardware.org/?probe=bc211e09fd) | Dec 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [2b7412b23b](https://linux-hardware.org/?probe=2b7412b23b) | Dec 04, 2021 |
| Dell          | Inspiron 5490               | [21da3b7e37](https://linux-hardware.org/?probe=21da3b7e37) | Dec 03, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [58020d3b39](https://linux-hardware.org/?probe=58020d3b39) | Dec 03, 2021 |
| Sony          | SVE14A15FBP                 | [4a5895c643](https://linux-hardware.org/?probe=4a5895c643) | Dec 03, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [29ff3edb05](https://linux-hardware.org/?probe=29ff3edb05) | Dec 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [59795a80ef](https://linux-hardware.org/?probe=59795a80ef) | Dec 03, 2021 |
| Dell          | Inspiron 15-3567            | [4012763f85](https://linux-hardware.org/?probe=4012763f85) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| LG Electro... | S460-G.BG31P1               | [bbdfd3b78e](https://linux-hardware.org/?probe=bbdfd3b78e) | Dec 02, 2021 |
| Positivo      | H14BT58                     | [7e692b3a7a](https://linux-hardware.org/?probe=7e692b3a7a) | Dec 02, 2021 |
| Acer          | Nitro AN515-44              | [a824747d21](https://linux-hardware.org/?probe=a824747d21) | Dec 02, 2021 |
| Dell          | Inspiron 15-3567            | [6491dbee12](https://linux-hardware.org/?probe=6491dbee12) | Dec 02, 2021 |
| Dell          | Inspiron N4050              | [46f1d21cbc](https://linux-hardware.org/?probe=46f1d21cbc) | Dec 02, 2021 |
| Acer          | Aspire A315-23              | [5c74762b22](https://linux-hardware.org/?probe=5c74762b22) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | [4f46a6c92a](https://linux-hardware.org/?probe=4f46a6c92a) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | [1521941a87](https://linux-hardware.org/?probe=1521941a87) | Dec 02, 2021 |
| Apple         | MacBookAir6,2               | [4a21fcd64f](https://linux-hardware.org/?probe=4a21fcd64f) | Dec 02, 2021 |
| Philco        | 14F                         | [ab69e64295](https://linux-hardware.org/?probe=ab69e64295) | Dec 02, 2021 |
| Avell High... | B.ON                        | [a7513f22ee](https://linux-hardware.org/?probe=a7513f22ee) | Dec 02, 2021 |
| Acer          | Aspire A315-34              | [9bbfd01bca](https://linux-hardware.org/?probe=9bbfd01bca) | Dec 01, 2021 |
| Acer          | Aspire A315-53              | [18d91295e1](https://linux-hardware.org/?probe=18d91295e1) | Dec 01, 2021 |
| Dell          | Inspiron N5110              | [3027af9a0e](https://linux-hardware.org/?probe=3027af9a0e) | Dec 01, 2021 |
| Dell          | Inspiron 5502               | [6522739036](https://linux-hardware.org/?probe=6522739036) | Dec 01, 2021 |
| Dell          | Inspiron 5502               | [3438f86ded](https://linux-hardware.org/?probe=3438f86ded) | Dec 01, 2021 |
| Samsung       | 550XDA                      | [30c24b17f4](https://linux-hardware.org/?probe=30c24b17f4) | Dec 01, 2021 |
| Acer          | Nitro AN515-54              | [991967c2ff](https://linux-hardware.org/?probe=991967c2ff) | Nov 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [74ce8e4fbe](https://linux-hardware.org/?probe=74ce8e4fbe) | Nov 30, 2021 |
| Dell          | Inspiron 7460               | [0a6feb58e7](https://linux-hardware.org/?probe=0a6feb58e7) | Nov 30, 2021 |
| Dell          | Vostro 5471                 | [3da13c5e1b](https://linux-hardware.org/?probe=3da13c5e1b) | Nov 30, 2021 |
| Acer          | Nitro AN515-44              | [7edf9fe1b5](https://linux-hardware.org/?probe=7edf9fe1b5) | Nov 30, 2021 |
| Acer          | Aspire A515-51G             | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Acer          | Nitro AN517-51              | [e7af37db76](https://linux-hardware.org/?probe=e7af37db76) | Nov 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ecc61836da](https://linux-hardware.org/?probe=ecc61836da) | Nov 30, 2021 |
| Dell          | Inspiron N5110              | [7532ace96c](https://linux-hardware.org/?probe=7532ace96c) | Nov 29, 2021 |
| Dell          | G5 5590                     | [e569e56450](https://linux-hardware.org/?probe=e569e56450) | Nov 29, 2021 |
| HP            | Compaq Presario CQ40        | [677782bf59](https://linux-hardware.org/?probe=677782bf59) | Nov 29, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [26cba9b931](https://linux-hardware.org/?probe=26cba9b931) | Nov 29, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [a716e055d8](https://linux-hardware.org/?probe=a716e055d8) | Nov 29, 2021 |
| Dell          | Inspiron 15-3567            | [3a2bf12582](https://linux-hardware.org/?probe=3a2bf12582) | Nov 29, 2021 |
| Acer          | Nitro AN515-43              | [10754c360e](https://linux-hardware.org/?probe=10754c360e) | Nov 29, 2021 |
| Acer          | Nitro AN515-44              | [71e47d66a9](https://linux-hardware.org/?probe=71e47d66a9) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | [7add4c45f0](https://linux-hardware.org/?probe=7add4c45f0) | Nov 28, 2021 |
| Dell          | Vostro 5402                 | [aa9b2c7788](https://linux-hardware.org/?probe=aa9b2c7788) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | [c3ac874c98](https://linux-hardware.org/?probe=c3ac874c98) | Nov 28, 2021 |
| Acer          | Aspire 5050                 | [22057607c1](https://linux-hardware.org/?probe=22057607c1) | Nov 28, 2021 |
| Philco        | OEM                         | [3d13f6a539](https://linux-hardware.org/?probe=3d13f6a539) | Nov 28, 2021 |
| Dell          | Inspiron 5447               | [bbdd9f0b69](https://linux-hardware.org/?probe=bbdd9f0b69) | Nov 28, 2021 |
| Acer          | Aspire 5050                 | [7935d8067b](https://linux-hardware.org/?probe=7935d8067b) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | [02b7a680cd](https://linux-hardware.org/?probe=02b7a680cd) | Nov 28, 2021 |
| Dell          | Inspiron 5421               | [2bf059f608](https://linux-hardware.org/?probe=2bf059f608) | Nov 27, 2021 |
| Acer          | Nitro AN515-54              | [b63d468197](https://linux-hardware.org/?probe=b63d468197) | Nov 27, 2021 |
| Login Info... | LOG-MB47II7                 | [1c2d866625](https://linux-hardware.org/?probe=1c2d866625) | Nov 27, 2021 |
| Acer          | Aspire A515-51              | [942114b7ed](https://linux-hardware.org/?probe=942114b7ed) | Nov 27, 2021 |
| Dell          | Inspiron 7572               | [08c282da3a](https://linux-hardware.org/?probe=08c282da3a) | Nov 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [16be623c84](https://linux-hardware.org/?probe=16be623c84) | Nov 27, 2021 |
| Dell          | Inspiron 7559               | [e2b7b798a8](https://linux-hardware.org/?probe=e2b7b798a8) | Nov 27, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [8a5475fd42](https://linux-hardware.org/?probe=8a5475fd42) | Nov 26, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [8c0a3a65ba](https://linux-hardware.org/?probe=8c0a3a65ba) | Nov 26, 2021 |
| LG Electro... | Z430-G.BE41P1               | [d2a91c1633](https://linux-hardware.org/?probe=d2a91c1633) | Nov 26, 2021 |
| LG Electro... | Z430-G.BE41P1               | [10770dac94](https://linux-hardware.org/?probe=10770dac94) | Nov 26, 2021 |
| Positivo      | Mobile                      | [f67e7cf244](https://linux-hardware.org/?probe=f67e7cf244) | Nov 25, 2021 |
| Avell High... | B.ON                        | [5fd318217e](https://linux-hardware.org/?probe=5fd318217e) | Nov 25, 2021 |
| Positivo      | Mobile                      | [aa89357d9f](https://linux-hardware.org/?probe=aa89357d9f) | Nov 25, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [1ec79ee5e6](https://linux-hardware.org/?probe=1ec79ee5e6) | Nov 25, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [cd408c48d0](https://linux-hardware.org/?probe=cd408c48d0) | Nov 25, 2021 |
| Dell          | Inspiron 5437               | [3c089ce814](https://linux-hardware.org/?probe=3c089ce814) | Nov 25, 2021 |
| Dell          | Vostro 5402                 | [a10a19ecfb](https://linux-hardware.org/?probe=a10a19ecfb) | Nov 25, 2021 |
| Samsung       | RF511/RF411/RF711           | [df371e2ae6](https://linux-hardware.org/?probe=df371e2ae6) | Nov 25, 2021 |
| Dell          | Inspiron 5537               | [be435b0de0](https://linux-hardware.org/?probe=be435b0de0) | Nov 25, 2021 |
| Dell          | Inspiron 5537               | [d09709c348](https://linux-hardware.org/?probe=d09709c348) | Nov 25, 2021 |
| HP            | ProBook 6460b               | [a072a6246d](https://linux-hardware.org/?probe=a072a6246d) | Nov 25, 2021 |
| Acer          | Nitro AN515-54              | [4766af9ef7](https://linux-hardware.org/?probe=4766af9ef7) | Nov 25, 2021 |
| Multilaser    | PC024                       | [7979d1f6b5](https://linux-hardware.org/?probe=7979d1f6b5) | Nov 25, 2021 |
| LG Electro... | S425-L.BC24P1               | [6d6d4fca9b](https://linux-hardware.org/?probe=6d6d4fca9b) | Nov 24, 2021 |
| Dell          | Inspiron 1564               | [7cb7c080e6](https://linux-hardware.org/?probe=7cb7c080e6) | Nov 24, 2021 |
| Toshiba       | STI NA 1401                 | [e2440e4557](https://linux-hardware.org/?probe=e2440e4557) | Nov 24, 2021 |
| Positivo B... | VJFE43F11X-XXXXXX           | [64e0d3193c](https://linux-hardware.org/?probe=64e0d3193c) | Nov 24, 2021 |
| Acer          | Aspire A515-54              | [35daf15c62](https://linux-hardware.org/?probe=35daf15c62) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b6bfa4b827](https://linux-hardware.org/?probe=b6bfa4b827) | Nov 24, 2021 |
| Acer          | Aspire A315-53              | [9dcd5129ea](https://linux-hardware.org/?probe=9dcd5129ea) | Nov 24, 2021 |
| Acer          | Aspire E5-511               | [d4bfc15ece](https://linux-hardware.org/?probe=d4bfc15ece) | Nov 24, 2021 |
| Samsung       | RV419                       | [61ed787e01](https://linux-hardware.org/?probe=61ed787e01) | Nov 24, 2021 |
| Acer          | Aspire A515-54              | [ba05aeb5fe](https://linux-hardware.org/?probe=ba05aeb5fe) | Nov 23, 2021 |
| HP            | ENVY 17                     | [55408e2f19](https://linux-hardware.org/?probe=55408e2f19) | Nov 23, 2021 |
| Acer          | Aspire 5338                 | [db097f4f70](https://linux-hardware.org/?probe=db097f4f70) | Nov 23, 2021 |
| Dell          | Inspiron 11-3168            | [b7b3b8ef38](https://linux-hardware.org/?probe=b7b3b8ef38) | Nov 23, 2021 |
| Dell          | Vostro 1510                 | [3eb9def4af](https://linux-hardware.org/?probe=3eb9def4af) | Nov 23, 2021 |
| Acer          | Nitro AN515-44              | [9fd987e7d8](https://linux-hardware.org/?probe=9fd987e7d8) | Nov 23, 2021 |
| Dell          | Inspiron 7560               | [8a73006911](https://linux-hardware.org/?probe=8a73006911) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | [d29d6c2f61](https://linux-hardware.org/?probe=d29d6c2f61) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | [6e361a8715](https://linux-hardware.org/?probe=6e361a8715) | Nov 23, 2021 |
| Acer          | Nitro AN515-43              | [457a2ff293](https://linux-hardware.org/?probe=457a2ff293) | Nov 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ef65932064](https://linux-hardware.org/?probe=ef65932064) | Nov 23, 2021 |
| Sony          | VGN-FZ480E                  | [18898ae0ab](https://linux-hardware.org/?probe=18898ae0ab) | Nov 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [423bdd7d74](https://linux-hardware.org/?probe=423bdd7d74) | Nov 21, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bb0a461d82](https://linux-hardware.org/?probe=bb0a461d82) | Nov 21, 2021 |
| ASUSTek       | K43E                        | [5d93c9b5e1](https://linux-hardware.org/?probe=5d93c9b5e1) | Nov 20, 2021 |
| Positivo      | CHT12CP                     | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Dell          | Inspiron 5566               | [c5dc9a3bde](https://linux-hardware.org/?probe=c5dc9a3bde) | Nov 20, 2021 |
| Toshiba       | IS 1462B                    | [682a8f788c](https://linux-hardware.org/?probe=682a8f788c) | Nov 20, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [31cebd4e96](https://linux-hardware.org/?probe=31cebd4e96) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [0be43eb710](https://linux-hardware.org/?probe=0be43eb710) | Nov 19, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9462d546b4](https://linux-hardware.org/?probe=9462d546b4) | Nov 19, 2021 |
| Positivo      | C14CR21                     | [a771171160](https://linux-hardware.org/?probe=a771171160) | Nov 19, 2021 |
| Acer          | Aspire 4745                 | [9edc4a1dd4](https://linux-hardware.org/?probe=9edc4a1dd4) | Nov 19, 2021 |
| Dell          | Inspiron 5402               | [495017ce96](https://linux-hardware.org/?probe=495017ce96) | Nov 19, 2021 |
| LG Electro... | S460-G.BG31P1               | [96d8266022](https://linux-hardware.org/?probe=96d8266022) | Nov 19, 2021 |
| HP            | Compaq Presario CQ50        | [75700ea22a](https://linux-hardware.org/?probe=75700ea22a) | Nov 19, 2021 |
| Acer          | Aspire F5-573G              | [ac573c69d3](https://linux-hardware.org/?probe=ac573c69d3) | Nov 18, 2021 |
| Samsung       | 550XCJ/550XCR               | [d850875f62](https://linux-hardware.org/?probe=d850875f62) | Nov 17, 2021 |
| Samsung       | 550XCJ/550XCR               | [e4919b1254](https://linux-hardware.org/?probe=e4919b1254) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | [585419cd38](https://linux-hardware.org/?probe=585419cd38) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | [9dff5423c9](https://linux-hardware.org/?probe=9dff5423c9) | Nov 17, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [30520d2f19](https://linux-hardware.org/?probe=30520d2f19) | Nov 17, 2021 |
| Acer          | Nitro AN515-44              | [d71fa6378d](https://linux-hardware.org/?probe=d71fa6378d) | Nov 17, 2021 |
| Positivo      | Mobile                      | [9b83c09ad3](https://linux-hardware.org/?probe=9b83c09ad3) | Nov 17, 2021 |
| Dell          | Inspiron 5437               | [dc16c3ef7d](https://linux-hardware.org/?probe=dc16c3ef7d) | Nov 17, 2021 |
| Samsung       | 550XDA                      | [607bff4b5f](https://linux-hardware.org/?probe=607bff4b5f) | Nov 17, 2021 |
| Acer          | Aspire F5-573G              | [217880cca8](https://linux-hardware.org/?probe=217880cca8) | Nov 17, 2021 |
| Dell          | Inspiron 7560               | [84b417f9d3](https://linux-hardware.org/?probe=84b417f9d3) | Nov 17, 2021 |
| Lenovo        | ThinkPad E14 20RBS2D100     | [f3a3d2668d](https://linux-hardware.org/?probe=f3a3d2668d) | Nov 17, 2021 |
| Lenovo        | ThinkPad E14 20RBS2D100     | [e0a279ef7e](https://linux-hardware.org/?probe=e0a279ef7e) | Nov 16, 2021 |
| Acer          | Aspire E1-421               | [52cc14391a](https://linux-hardware.org/?probe=52cc14391a) | Nov 16, 2021 |
| ASUSTek       | K43E                        | [ce875ce67c](https://linux-hardware.org/?probe=ce875ce67c) | Nov 16, 2021 |
| Lenovo        | IdeaPad Z460 0913           | [0bb3eea006](https://linux-hardware.org/?probe=0bb3eea006) | Nov 16, 2021 |
| ASUSTek       | K43E                        | [bd2dad5f8e](https://linux-hardware.org/?probe=bd2dad5f8e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | [dbaa27643e](https://linux-hardware.org/?probe=dbaa27643e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | [aad4a92e0e](https://linux-hardware.org/?probe=aad4a92e0e) | Nov 16, 2021 |
| LG Electro... | X140-G.BG12P1               | [337924a30c](https://linux-hardware.org/?probe=337924a30c) | Nov 16, 2021 |
| LG Electro... | X140-G.BG12P1               | [abe339e912](https://linux-hardware.org/?probe=abe339e912) | Nov 16, 2021 |
| ASUSTek       | X751LJ                      | [79030e87e9](https://linux-hardware.org/?probe=79030e87e9) | Nov 15, 2021 |
| Dell          | Inspiron 3442               | [b6630ba66c](https://linux-hardware.org/?probe=b6630ba66c) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [74ce7d98c6](https://linux-hardware.org/?probe=74ce7d98c6) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [180bbba91c](https://linux-hardware.org/?probe=180bbba91c) | Nov 15, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [f998266e76](https://linux-hardware.org/?probe=f998266e76) | Nov 15, 2021 |
| Dell          | Inspiron 7520               | [ca5c253749](https://linux-hardware.org/?probe=ca5c253749) | Nov 14, 2021 |
| Lenovo        | G470 20078                  | [cd92d6030e](https://linux-hardware.org/?probe=cd92d6030e) | Nov 14, 2021 |
| Acer          | Nitro AN515-44              | [328668f616](https://linux-hardware.org/?probe=328668f616) | Nov 14, 2021 |
| Acer          | Aspire A315-34              | [29d6ad8b6f](https://linux-hardware.org/?probe=29d6ad8b6f) | Nov 14, 2021 |
| Dell          | Inspiron 3442               | [832b5007b0](https://linux-hardware.org/?probe=832b5007b0) | Nov 14, 2021 |
| Dell          | Vostro 3460                 | [3a6a636384](https://linux-hardware.org/?probe=3a6a636384) | Nov 14, 2021 |
| OEM           | I38II                       | [0b2d349414](https://linux-hardware.org/?probe=0b2d349414) | Nov 14, 2021 |
| Positivo      | H14SU08                     | [5e9259bbd3](https://linux-hardware.org/?probe=5e9259bbd3) | Nov 14, 2021 |
| Samsung       | RF511/RF411/RF711           | [ffbf11ec7f](https://linux-hardware.org/?probe=ffbf11ec7f) | Nov 14, 2021 |
| Samsung       | RF511/RF411/RF711           | [8968b7142d](https://linux-hardware.org/?probe=8968b7142d) | Nov 14, 2021 |
| Samsung       | 270E5J/2570EJ               | [bb0216f047](https://linux-hardware.org/?probe=bb0216f047) | Nov 13, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ed343e426b](https://linux-hardware.org/?probe=ed343e426b) | Nov 13, 2021 |
| Login Info... | LOG-MB47II7                 | [4a568a9bdf](https://linux-hardware.org/?probe=4a568a9bdf) | Nov 13, 2021 |
| HP            | Pavilion 11 x360 PC         | [3eaabe505d](https://linux-hardware.org/?probe=3eaabe505d) | Nov 13, 2021 |
| HP            | Pavilion 11 x360 PC         | [8f763c3644](https://linux-hardware.org/?probe=8f763c3644) | Nov 13, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [06699211b6](https://linux-hardware.org/?probe=06699211b6) | Nov 13, 2021 |
| Acer          | Aspire A515-54              | [7f5b5d0c7a](https://linux-hardware.org/?probe=7f5b5d0c7a) | Nov 13, 2021 |
| Acer          | Aspire A315-34              | [e9840b2a27](https://linux-hardware.org/?probe=e9840b2a27) | Nov 13, 2021 |
| Positivo      | V142N_4G                    | [6afdf02b96](https://linux-hardware.org/?probe=6afdf02b96) | Nov 13, 2021 |
| Acer          | Nitro AN515-54              | [2a98c5ad7b](https://linux-hardware.org/?probe=2a98c5ad7b) | Nov 13, 2021 |
| Samsung       | 550XDA                      | [69fe372895](https://linux-hardware.org/?probe=69fe372895) | Nov 12, 2021 |
| Samsung       | 550XDA                      | [61a4dbe6b6](https://linux-hardware.org/?probe=61a4dbe6b6) | Nov 12, 2021 |
| ASUSTek       | X541UAK                     | [7d4b51e485](https://linux-hardware.org/?probe=7d4b51e485) | Nov 12, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3bbda8b194](https://linux-hardware.org/?probe=3bbda8b194) | Nov 12, 2021 |
| Dell          | Inspiron 15-3567            | [e8879e98df](https://linux-hardware.org/?probe=e8879e98df) | Nov 12, 2021 |
| Samsung       | 370E4K                      | [f076dae1f9](https://linux-hardware.org/?probe=f076dae1f9) | Nov 12, 2021 |
| Dell          | G5 5590                     | [5965461af0](https://linux-hardware.org/?probe=5965461af0) | Nov 12, 2021 |
| Dell          | G5 5590                     | [42c0049b50](https://linux-hardware.org/?probe=42c0049b50) | Nov 12, 2021 |
| Dell          | Latitude 3420               | [d58aa8a60c](https://linux-hardware.org/?probe=d58aa8a60c) | Nov 11, 2021 |
| Dell          | Vostro 5402                 | [db067048aa](https://linux-hardware.org/?probe=db067048aa) | Nov 11, 2021 |
| Dell          | Inspiron 5584               | [ae7c7124b8](https://linux-hardware.org/?probe=ae7c7124b8) | Nov 11, 2021 |
| Acer          | Aspire A515-52              | [665fa7f7f2](https://linux-hardware.org/?probe=665fa7f7f2) | Nov 11, 2021 |
| Acer          | Nitro AN515-55              | [b0556699a5](https://linux-hardware.org/?probe=b0556699a5) | Nov 11, 2021 |
| Samsung       | 370E4K                      | [a296e36d75](https://linux-hardware.org/?probe=a296e36d75) | Nov 11, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [0d059f1720](https://linux-hardware.org/?probe=0d059f1720) | Nov 11, 2021 |
| Dell          | Inspiron 3442               | [d43bbede7b](https://linux-hardware.org/?probe=d43bbede7b) | Nov 11, 2021 |
| Dell          | G3 3579                     | [de2e21fc7d](https://linux-hardware.org/?probe=de2e21fc7d) | Nov 11, 2021 |
| Toshiba       | NA 1402                     | [a32237ae56](https://linux-hardware.org/?probe=a32237ae56) | Nov 11, 2021 |
| Dell          | Vostro 3480                 | [25a0c10009](https://linux-hardware.org/?probe=25a0c10009) | Nov 11, 2021 |
| Dell          | Inspiron 3501               | [f5eba44619](https://linux-hardware.org/?probe=f5eba44619) | Nov 11, 2021 |
| Dell          | Vostro 3480                 | [a4167ceb73](https://linux-hardware.org/?probe=a4167ceb73) | Nov 11, 2021 |
| HP            | Pavilion 14                 | [1ed6c4bf90](https://linux-hardware.org/?probe=1ed6c4bf90) | Nov 10, 2021 |
| HP            | Pavilion 14                 | [4772b8de9b](https://linux-hardware.org/?probe=4772b8de9b) | Nov 10, 2021 |
| Dell          | Vostro 3500                 | [5842108f8f](https://linux-hardware.org/?probe=5842108f8f) | Nov 10, 2021 |
| Samsung       | 550XCJ/550XCR               | [3fad218eef](https://linux-hardware.org/?probe=3fad218eef) | Nov 10, 2021 |
| Acer          | AOD257                      | [f9faa5980e](https://linux-hardware.org/?probe=f9faa5980e) | Nov 10, 2021 |
| Acer          | AOD257                      | [3ecb22f1c0](https://linux-hardware.org/?probe=3ecb22f1c0) | Nov 10, 2021 |
| Acer          | Nitro AN515-55              | [d3b67380f0](https://linux-hardware.org/?probe=d3b67380f0) | Nov 10, 2021 |
| Toshiba       | STI NA 1401                 | [f1d5056f39](https://linux-hardware.org/?probe=f1d5056f39) | Nov 10, 2021 |
| Samsung       | 370E4K                      | [0e84b827bd](https://linux-hardware.org/?probe=0e84b827bd) | Nov 10, 2021 |
| Dell          | Inspiron 7520               | [580bcd40a3](https://linux-hardware.org/?probe=580bcd40a3) | Nov 10, 2021 |
| Samsung       | 550XBE/350XBE               | [0597be3c31](https://linux-hardware.org/?probe=0597be3c31) | Nov 09, 2021 |
| Samsung       | 550XBE/350XBE               | [3dcebc581d](https://linux-hardware.org/?probe=3dcebc581d) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [bc08546f3f](https://linux-hardware.org/?probe=bc08546f3f) | Nov 09, 2021 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [ac46929783](https://linux-hardware.org/?probe=ac46929783) | Nov 09, 2021 |
| Dell          | Vostro 5402                 | [6d46de50cb](https://linux-hardware.org/?probe=6d46de50cb) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [325cc5e53a](https://linux-hardware.org/?probe=325cc5e53a) | Nov 09, 2021 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | [fc450330af](https://linux-hardware.org/?probe=fc450330af) | Nov 09, 2021 |
| Samsung       | R430/R480/R440              | [04996a81f4](https://linux-hardware.org/?probe=04996a81f4) | Nov 08, 2021 |
| HP            | Pavilion dv7                | [a19e73fd27](https://linux-hardware.org/?probe=a19e73fd27) | Nov 08, 2021 |
| ASUSTek       | K42F                        | [a0fc0b335f](https://linux-hardware.org/?probe=a0fc0b335f) | Nov 07, 2021 |
| Dell          | Inspiron 5490               | [abf9aa4a6c](https://linux-hardware.org/?probe=abf9aa4a6c) | Nov 07, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [4b98da95b0](https://linux-hardware.org/?probe=4b98da95b0) | Nov 06, 2021 |
| Positivo      | Mobile                      | [17b00479c7](https://linux-hardware.org/?probe=17b00479c7) | Nov 06, 2021 |
| Dell          | Inspiron 15-3567            | [9c14e4d461](https://linux-hardware.org/?probe=9c14e4d461) | Nov 06, 2021 |
| Positivo      | W942SW_SW1                  | [3a8406ec90](https://linux-hardware.org/?probe=3a8406ec90) | Nov 06, 2021 |
| Lenovo        | G50-80 80R0                 | [a24e6b4e38](https://linux-hardware.org/?probe=a24e6b4e38) | Nov 06, 2021 |
| Lenovo        | G50-80 80R0                 | [94d7421e0c](https://linux-hardware.org/?probe=94d7421e0c) | Nov 06, 2021 |
| Acer          | Aspire 5250                 | [effc5cc35d](https://linux-hardware.org/?probe=effc5cc35d) | Nov 06, 2021 |
| Dell          | G3 3590                     | [aa237dfc61](https://linux-hardware.org/?probe=aa237dfc61) | Nov 06, 2021 |
| Acer          | Aspire XXXX                 | [2e486fd092](https://linux-hardware.org/?probe=2e486fd092) | Nov 05, 2021 |
| Avell High... | A70 LIV                     | [b4d7b0e021](https://linux-hardware.org/?probe=b4d7b0e021) | Nov 05, 2021 |
| Dell          | Inspiron 5547               | [6ebd71080f](https://linux-hardware.org/?probe=6ebd71080f) | Nov 04, 2021 |
| Dell          | Inspiron 5547               | [df08a534fa](https://linux-hardware.org/?probe=df08a534fa) | Nov 04, 2021 |
| HP            | Pavilion dv4                | [d37c348339](https://linux-hardware.org/?probe=d37c348339) | Nov 04, 2021 |
| Acer          | Aspire A515-51              | [6b5f820af1](https://linux-hardware.org/?probe=6b5f820af1) | Nov 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [3e926045ee](https://linux-hardware.org/?probe=3e926045ee) | Nov 04, 2021 |
| Toshiba       | IS 1462B                    | [a5538db795](https://linux-hardware.org/?probe=a5538db795) | Nov 04, 2021 |
| Positivo      | Mobile                      | [36163a2c6c](https://linux-hardware.org/?probe=36163a2c6c) | Nov 04, 2021 |
| Acer          | Aspire A514-54              | [8724bc9bbf](https://linux-hardware.org/?probe=8724bc9bbf) | Nov 04, 2021 |
| Acer          | Aspire A514-54G             | [8908b4165a](https://linux-hardware.org/?probe=8908b4165a) | Nov 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [661a73d3c5](https://linux-hardware.org/?probe=661a73d3c5) | Nov 03, 2021 |
| Dell          | Inspiron 5566               | [d6b72b3f64](https://linux-hardware.org/?probe=d6b72b3f64) | Nov 03, 2021 |
| Sony          | VGN-FZ480E                  | [715e1bfcd5](https://linux-hardware.org/?probe=715e1bfcd5) | Nov 03, 2021 |
| Dell          | Inspiron 5437               | [8326fcc8b9](https://linux-hardware.org/?probe=8326fcc8b9) | Nov 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1b665c64fd](https://linux-hardware.org/?probe=1b665c64fd) | Nov 02, 2021 |
| Dell          | Vostro 5402                 | [b15e80cab7](https://linux-hardware.org/?probe=b15e80cab7) | Nov 01, 2021 |
| Acer          | Nitro AN515-44              | [754d944557](https://linux-hardware.org/?probe=754d944557) | Nov 01, 2021 |
| Acer          | Aspire E1-531               | [8c7226d96a](https://linux-hardware.org/?probe=8c7226d96a) | Nov 01, 2021 |
| Dell          | Vostro 5402                 | [f7fa163f1f](https://linux-hardware.org/?probe=f7fa163f1f) | Nov 01, 2021 |
| Dell          | Latitude E6430              | [d35b1ab829](https://linux-hardware.org/?probe=d35b1ab829) | Nov 01, 2021 |
| Toshiba       | Satellite S55-C             | [9bb9999a3a](https://linux-hardware.org/?probe=9bb9999a3a) | Nov 01, 2021 |
| Dell          | Inspiron 5437               | [2d4b614d02](https://linux-hardware.org/?probe=2d4b614d02) | Nov 01, 2021 |
| Acer          | Aspire A315-53              | [4faa88a423](https://linux-hardware.org/?probe=4faa88a423) | Nov 01, 2021 |
| Toshiba       | Satellite S55-C             | [1cc5699354](https://linux-hardware.org/?probe=1cc5699354) | Nov 01, 2021 |
| Acer          | Aspire A515-54G             | [807a8b23ce](https://linux-hardware.org/?probe=807a8b23ce) | Nov 01, 2021 |
| Dell          | Vostro 5471                 | [8182230d1d](https://linux-hardware.org/?probe=8182230d1d) | Nov 01, 2021 |
| Standard      | AHV                         | [a960753588](https://linux-hardware.org/?probe=a960753588) | Oct 31, 2021 |
| Standard      | AHV                         | [1478edca39](https://linux-hardware.org/?probe=1478edca39) | Oct 31, 2021 |
| Dell          | Inspiron 5437               | [0f2394b49d](https://linux-hardware.org/?probe=0f2394b49d) | Oct 31, 2021 |
| Toshiba       | IS 1412                     | [c0faa178a2](https://linux-hardware.org/?probe=c0faa178a2) | Oct 31, 2021 |
| Dell          | Inspiron 5437               | [3e3fea2e0f](https://linux-hardware.org/?probe=3e3fea2e0f) | Oct 30, 2021 |
| Dell          | Inspiron 5421               | [d70e2b74d0](https://linux-hardware.org/?probe=d70e2b74d0) | Oct 30, 2021 |
| Dell          | Inspiron 5421               | [d4d3ebf711](https://linux-hardware.org/?probe=d4d3ebf711) | Oct 30, 2021 |
| Samsung       | 270E5G/270E5U               | [31ae4d8fda](https://linux-hardware.org/?probe=31ae4d8fda) | Oct 30, 2021 |
| Dell          | Vostro 5402                 | [5434b808b5](https://linux-hardware.org/?probe=5434b808b5) | Oct 30, 2021 |
| Acer          | Nitro AN515-54              | [bc9dc107d1](https://linux-hardware.org/?probe=bc9dc107d1) | Oct 30, 2021 |
| Dell          | Inspiron 5420               | [8bd0954be7](https://linux-hardware.org/?probe=8bd0954be7) | Oct 30, 2021 |
| Dell          | Vostro 5402                 | [3914304341](https://linux-hardware.org/?probe=3914304341) | Oct 30, 2021 |
| Lenovo        | G480 20149                  | [ee0a6fc9ca](https://linux-hardware.org/?probe=ee0a6fc9ca) | Oct 30, 2021 |
| Sony          | SVF15213CBB                 | [1d79ed8874](https://linux-hardware.org/?probe=1d79ed8874) | Oct 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [88286c36e9](https://linux-hardware.org/?probe=88286c36e9) | Oct 29, 2021 |
| Dell          | Latitude 7420               | [20266b5994](https://linux-hardware.org/?probe=20266b5994) | Oct 29, 2021 |
| Dell          | System XPS L502X            | [8f052d2acb](https://linux-hardware.org/?probe=8f052d2acb) | Oct 29, 2021 |
| Acer          | Aspire F5-573G              | [1be6c8dc87](https://linux-hardware.org/?probe=1be6c8dc87) | Oct 29, 2021 |
| Acer          | Aspire A515-54G             | [7463facb20](https://linux-hardware.org/?probe=7463facb20) | Oct 29, 2021 |
| Acer          | Aspire A515-54G             | [270d4c1d21](https://linux-hardware.org/?probe=270d4c1d21) | Oct 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f1941a09e5](https://linux-hardware.org/?probe=f1941a09e5) | Oct 28, 2021 |
| Toshiba       | STI NA 1401                 | [c8075f4483](https://linux-hardware.org/?probe=c8075f4483) | Oct 28, 2021 |
| Dell          | Vostro 14-5480              | [5d323af087](https://linux-hardware.org/?probe=5d323af087) | Oct 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [31c9d5b545](https://linux-hardware.org/?probe=31c9d5b545) | Oct 28, 2021 |
| Dell          | Vostro 14-5480              | [e2c5f1bdea](https://linux-hardware.org/?probe=e2c5f1bdea) | Oct 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [89afa44bcf](https://linux-hardware.org/?probe=89afa44bcf) | Oct 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [27d2383b87](https://linux-hardware.org/?probe=27d2383b87) | Oct 27, 2021 |
| BESSTAR Te... | X400                        | [9cfc0bb300](https://linux-hardware.org/?probe=9cfc0bb300) | Oct 27, 2021 |
| Dell          | Vostro 3400                 | [608e1f800d](https://linux-hardware.org/?probe=608e1f800d) | Oct 27, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [f3400508fb](https://linux-hardware.org/?probe=f3400508fb) | Oct 27, 2021 |
| Lenovo        | ThinkPad T480 20L6SCWK00    | [feb7f2a285](https://linux-hardware.org/?probe=feb7f2a285) | Oct 27, 2021 |
| Sony          | VGN-FZ480E                  | [2af35086e4](https://linux-hardware.org/?probe=2af35086e4) | Oct 27, 2021 |
| Sony          | VGN-FZ480E                  | [83564443b9](https://linux-hardware.org/?probe=83564443b9) | Oct 26, 2021 |
| Acer          | Aspire A315-53              | [e348a818bd](https://linux-hardware.org/?probe=e348a818bd) | Oct 26, 2021 |
| Acer          | Aspire A315-53              | [ac77c040ba](https://linux-hardware.org/?probe=ac77c040ba) | Oct 26, 2021 |
| Dell          | Inspiron 5537               | [e2d02f71bc](https://linux-hardware.org/?probe=e2d02f71bc) | Oct 26, 2021 |
| Dell          | Inspiron 5570               | [c01fa4b013](https://linux-hardware.org/?probe=c01fa4b013) | Oct 26, 2021 |
| HP            | Unknown                     | [f31ac36b11](https://linux-hardware.org/?probe=f31ac36b11) | Oct 25, 2021 |
| Dell          | Inspiron N5110              | [df7b7986f5](https://linux-hardware.org/?probe=df7b7986f5) | Oct 25, 2021 |
| Dell          | Inspiron N5110              | [d9e192761c](https://linux-hardware.org/?probe=d9e192761c) | Oct 25, 2021 |
| Acer          | AO722                       | [832ca83fcd](https://linux-hardware.org/?probe=832ca83fcd) | Oct 25, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | [d3720f9145](https://linux-hardware.org/?probe=d3720f9145) | Oct 25, 2021 |
| Dell          | Latitude 3420               | [e330d77b1f](https://linux-hardware.org/?probe=e330d77b1f) | Oct 25, 2021 |
| HP            | Pavilion 14                 | [e12e55583d](https://linux-hardware.org/?probe=e12e55583d) | Oct 25, 2021 |
| ASUSTek       | X555LF                      | [984c7c6778](https://linux-hardware.org/?probe=984c7c6778) | Oct 25, 2021 |
| Dell          | Latitude E5430 non-vPro     | [39348a932e](https://linux-hardware.org/?probe=39348a932e) | Oct 25, 2021 |
| Dell          | System XPS L502X            | [3397631304](https://linux-hardware.org/?probe=3397631304) | Oct 25, 2021 |
| Compaq        | Presario CQ-25              | [ff46dc73d4](https://linux-hardware.org/?probe=ff46dc73d4) | Oct 25, 2021 |
| Acer          | Nitro AN515-43              | [bcc833ac3c](https://linux-hardware.org/?probe=bcc833ac3c) | Oct 25, 2021 |
| Acer          | Aspire VX5-591G             | [6ad3cf44dc](https://linux-hardware.org/?probe=6ad3cf44dc) | Oct 24, 2021 |
| Positivo      | C14CR21                     | [9f3a43bc94](https://linux-hardware.org/?probe=9f3a43bc94) | Oct 24, 2021 |
| Acer          | Nitro AN515-43              | [1e8a2612aa](https://linux-hardware.org/?probe=1e8a2612aa) | Oct 24, 2021 |
| Acer          | Aspire A315-34              | [f901b7640e](https://linux-hardware.org/?probe=f901b7640e) | Oct 24, 2021 |
| Acer          | Aspire A515-54G             | [fdbf1831d8](https://linux-hardware.org/?probe=fdbf1831d8) | Oct 24, 2021 |
| Acer          | Aspire A515-54G             | [a81bf18dd8](https://linux-hardware.org/?probe=a81bf18dd8) | Oct 24, 2021 |
| Dell          | Inspiron 3583               | [217767cb69](https://linux-hardware.org/?probe=217767cb69) | Oct 23, 2021 |
| Acer          | Acadia V1.42                | [01122f69f4](https://linux-hardware.org/?probe=01122f69f4) | Oct 23, 2021 |
| Dell          | Latitude 3420               | [ed2568dfa1](https://linux-hardware.org/?probe=ed2568dfa1) | Oct 23, 2021 |
| Acer          | Aspire A315-23G             | [09f6196e70](https://linux-hardware.org/?probe=09f6196e70) | Oct 23, 2021 |
| Dell          | Inspiron N5010              | [557421f62e](https://linux-hardware.org/?probe=557421f62e) | Oct 23, 2021 |
| Dell          | Inspiron N5010              | [f5703d2f8f](https://linux-hardware.org/?probe=f5703d2f8f) | Oct 23, 2021 |
| Acer          | Nitro AN515-54              | [af65c254d8](https://linux-hardware.org/?probe=af65c254d8) | Oct 23, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6f89504680](https://linux-hardware.org/?probe=6f89504680) | Oct 23, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [80a124f9cd](https://linux-hardware.org/?probe=80a124f9cd) | Oct 23, 2021 |
| HP            | Pavilion dv4-1120br         | [10e4cb83a8](https://linux-hardware.org/?probe=10e4cb83a8) | Oct 23, 2021 |
| Dell          | Latitude 3400               | [7f519c2721](https://linux-hardware.org/?probe=7f519c2721) | Oct 23, 2021 |
| Dell          | Inspiron 3583               | [8d8e23af16](https://linux-hardware.org/?probe=8d8e23af16) | Oct 23, 2021 |
| Acer          | Acadia V1.42                | [11b24034fc](https://linux-hardware.org/?probe=11b24034fc) | Oct 23, 2021 |
| Acer          | Nitro AN517-51              | [271c2188cb](https://linux-hardware.org/?probe=271c2188cb) | Oct 23, 2021 |
| Dell          | Inspiron 3437               | [5c433f99b1](https://linux-hardware.org/?probe=5c433f99b1) | Oct 22, 2021 |
| Positivo      | S14BW01                     | [6b146fc86e](https://linux-hardware.org/?probe=6b146fc86e) | Oct 22, 2021 |
| Dell          | Inspiron N4050              | [970402d06d](https://linux-hardware.org/?probe=970402d06d) | Oct 22, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [f06d6b9f20](https://linux-hardware.org/?probe=f06d6b9f20) | Oct 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0ec4e1e668](https://linux-hardware.org/?probe=0ec4e1e668) | Oct 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [88f5592418](https://linux-hardware.org/?probe=88f5592418) | Oct 22, 2021 |
| HP            | Pavilion g4                 | [3b86797a83](https://linux-hardware.org/?probe=3b86797a83) | Oct 22, 2021 |
| Samsung       | 300E5K/300E5Q               | [967d1d28ce](https://linux-hardware.org/?probe=967d1d28ce) | Oct 22, 2021 |
| Dell          | Inspiron N4050              | [85a514f622](https://linux-hardware.org/?probe=85a514f622) | Oct 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [19f7ba4a63](https://linux-hardware.org/?probe=19f7ba4a63) | Oct 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [703d0f2090](https://linux-hardware.org/?probe=703d0f2090) | Oct 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [3fe556cde3](https://linux-hardware.org/?probe=3fe556cde3) | Oct 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [0413ebb72c](https://linux-hardware.org/?probe=0413ebb72c) | Oct 21, 2021 |
| Acer          | Nitro AN515-54              | [1ef866386c](https://linux-hardware.org/?probe=1ef866386c) | Oct 21, 2021 |
| HP            | Pavilion dm1                | [1408d15ece](https://linux-hardware.org/?probe=1408d15ece) | Oct 21, 2021 |
| Dell          | Inspiron N5110              | [5153e99cce](https://linux-hardware.org/?probe=5153e99cce) | Oct 21, 2021 |
| Samsung       | 900X5T                      | [4f39e11826](https://linux-hardware.org/?probe=4f39e11826) | Oct 21, 2021 |
| Samsung       | 900X5T                      | [3e27247540](https://linux-hardware.org/?probe=3e27247540) | Oct 21, 2021 |
| Lenovo        | G470 20078                  | [394cdd726f](https://linux-hardware.org/?probe=394cdd726f) | Oct 21, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [cd748cc7d4](https://linux-hardware.org/?probe=cd748cc7d4) | Oct 20, 2021 |
| Lenovo        | G470 20078                  | [3ad2e537e7](https://linux-hardware.org/?probe=3ad2e537e7) | Oct 20, 2021 |
| Lenovo        | G550 2958                   | [25cfcf0ca1](https://linux-hardware.org/?probe=25cfcf0ca1) | Oct 20, 2021 |
| Acer          | Nitro AN515-44              | [e00a2deae3](https://linux-hardware.org/?probe=e00a2deae3) | Oct 20, 2021 |
| Acer          | Aspire 5750                 | [b66eb36016](https://linux-hardware.org/?probe=b66eb36016) | Oct 20, 2021 |
| Lenovo        | IdeaPad Flex14 20308        | [33d071cbec](https://linux-hardware.org/?probe=33d071cbec) | Oct 20, 2021 |
| Dell          | Inspiron 5481               | [beb9349c6e](https://linux-hardware.org/?probe=beb9349c6e) | Oct 20, 2021 |
| Intel         | W7650                       | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [f1f5f6bf59](https://linux-hardware.org/?probe=f1f5f6bf59) | Oct 19, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [a174c1781d](https://linux-hardware.org/?probe=a174c1781d) | Oct 19, 2021 |
| Toshiba       | STI NA 1401                 | [6e93fdc0c9](https://linux-hardware.org/?probe=6e93fdc0c9) | Oct 18, 2021 |
| LG Electro... | A410-K.BE43P1               | [a4bb8bffd7](https://linux-hardware.org/?probe=a4bb8bffd7) | Oct 18, 2021 |
| Dell          | Inspiron N5110              | [3aa7fc8e09](https://linux-hardware.org/?probe=3aa7fc8e09) | Oct 18, 2021 |
| Login Info... | LOG-MB47II7                 | [b277a4e2db](https://linux-hardware.org/?probe=b277a4e2db) | Oct 18, 2021 |
| Lenovo        | ThinkPad E490 20N9001FBR    | [7c1d310221](https://linux-hardware.org/?probe=7c1d310221) | Oct 18, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [374e69046b](https://linux-hardware.org/?probe=374e69046b) | Oct 18, 2021 |
| Positivo      | C14CR21                     | [ef9930e6f9](https://linux-hardware.org/?probe=ef9930e6f9) | Oct 17, 2021 |
| Positivo      | C14CR21                     | [942958ab88](https://linux-hardware.org/?probe=942958ab88) | Oct 17, 2021 |
| Acer          | Aspire A315-23G             | [66d1015de7](https://linux-hardware.org/?probe=66d1015de7) | Oct 17, 2021 |
| Dell          | G3 3579                     | [28d725057f](https://linux-hardware.org/?probe=28d725057f) | Oct 17, 2021 |
| Dell          | G3 3579                     | [a81715d288](https://linux-hardware.org/?probe=a81715d288) | Oct 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [383e24fcf5](https://linux-hardware.org/?probe=383e24fcf5) | Oct 17, 2021 |
| Acer          | Aspire A515-54G             | [baebf9648a](https://linux-hardware.org/?probe=baebf9648a) | Oct 17, 2021 |
| Acer          | Aspire A515-54G             | [a306e628c3](https://linux-hardware.org/?probe=a306e628c3) | Oct 17, 2021 |
| Samsung       | 370E4K                      | [e96252931e](https://linux-hardware.org/?probe=e96252931e) | Oct 17, 2021 |
| Samsung       | 550XDA                      | [b4026018fe](https://linux-hardware.org/?probe=b4026018fe) | Oct 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [397c4c2aca](https://linux-hardware.org/?probe=397c4c2aca) | Oct 16, 2021 |
| LG Electro... | A550-C.BE55P1               | [cac46f39f4](https://linux-hardware.org/?probe=cac46f39f4) | Oct 16, 2021 |
| Acer          | Nitro AN515-54              | [ec55317836](https://linux-hardware.org/?probe=ec55317836) | Oct 16, 2021 |
| Positivo      | C14CR21                     | [07aaf675fd](https://linux-hardware.org/?probe=07aaf675fd) | Oct 16, 2021 |
| Unknown       | Unknown                     | [3233e1293c](https://linux-hardware.org/?probe=3233e1293c) | Oct 15, 2021 |
| ASUSTek       | Z550SA                      | [9728ec8a83](https://linux-hardware.org/?probe=9728ec8a83) | Oct 15, 2021 |
| Acer          | Nitro AN517-51              | [a6d2f51c46](https://linux-hardware.org/?probe=a6d2f51c46) | Oct 15, 2021 |
| OEM           | I41SI                       | [814ebd5dd1](https://linux-hardware.org/?probe=814ebd5dd1) | Oct 15, 2021 |
| LG Electro... | U460-G.BG31P1               | [082c923ad8](https://linux-hardware.org/?probe=082c923ad8) | Oct 15, 2021 |
| LG Electro... | U460-G.BG31P1               | [a2979e1c5f](https://linux-hardware.org/?probe=a2979e1c5f) | Oct 15, 2021 |
| Positivo      | S14SL01                     | [5d92191da4](https://linux-hardware.org/?probe=5d92191da4) | Oct 15, 2021 |
| Dell          | Inspiron 1525               | [39495897d7](https://linux-hardware.org/?probe=39495897d7) | Oct 15, 2021 |
| Dell          | Vostro 5402                 | [eec2fcfa3b](https://linux-hardware.org/?probe=eec2fcfa3b) | Oct 15, 2021 |
| HP            | EliteBook 8470p             | [3c24201057](https://linux-hardware.org/?probe=3c24201057) | Oct 15, 2021 |
| Lenovo        | ThinkPad E490 20N9CTO1WW    | [69243ba50f](https://linux-hardware.org/?probe=69243ba50f) | Oct 14, 2021 |
| Acer          | Aspire A315-23G             | [f8f343d12b](https://linux-hardware.org/?probe=f8f343d12b) | Oct 14, 2021 |
| Dell          | G3 3590                     | [3165d77a8e](https://linux-hardware.org/?probe=3165d77a8e) | Oct 14, 2021 |
| Positivo      | Smash3                      | [3c9fe4acb8](https://linux-hardware.org/?probe=3c9fe4acb8) | Oct 14, 2021 |
| Positivo      | Smash3                      | [ab60c4e746](https://linux-hardware.org/?probe=ab60c4e746) | Oct 14, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [a4834f8957](https://linux-hardware.org/?probe=a4834f8957) | Oct 13, 2021 |
| HP            | ProBook 445 G7 Notebook ... | [83045a6763](https://linux-hardware.org/?probe=83045a6763) | Oct 13, 2021 |
| HP            | ENVY TS m6 Sleekbook        | [8ada30dc90](https://linux-hardware.org/?probe=8ada30dc90) | Oct 13, 2021 |
| Samsung       | 550XCJ/550XCR               | [4121b728e7](https://linux-hardware.org/?probe=4121b728e7) | Oct 13, 2021 |
| Samsung       | 550XCJ/550XCR               | [125473d905](https://linux-hardware.org/?probe=125473d905) | Oct 13, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [77065a0cd8](https://linux-hardware.org/?probe=77065a0cd8) | Oct 13, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [a8e5248d3d](https://linux-hardware.org/?probe=a8e5248d3d) | Oct 13, 2021 |
| Acer          | Aspire E1-572               | [dc154fe7c0](https://linux-hardware.org/?probe=dc154fe7c0) | Oct 13, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [589e47b071](https://linux-hardware.org/?probe=589e47b071) | Oct 13, 2021 |
| Positivo      | S14BW01                     | [0f03880266](https://linux-hardware.org/?probe=0f03880266) | Oct 13, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [82498fffc2](https://linux-hardware.org/?probe=82498fffc2) | Oct 12, 2021 |
| Acer          | Aspire A315-53              | [60eb0f3782](https://linux-hardware.org/?probe=60eb0f3782) | Oct 12, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [60b294879d](https://linux-hardware.org/?probe=60b294879d) | Oct 12, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5caa8b5a71](https://linux-hardware.org/?probe=5caa8b5a71) | Oct 12, 2021 |
| Acer          | Aspire A315-53              | [0a00ed81de](https://linux-hardware.org/?probe=0a00ed81de) | Oct 12, 2021 |
| Acer          | Aspire A315-42G             | [5b667bff5d](https://linux-hardware.org/?probe=5b667bff5d) | Oct 12, 2021 |
| HP            | Pavilion dv2000 (RP408UA... | [31a42ed2b6](https://linux-hardware.org/?probe=31a42ed2b6) | Oct 12, 2021 |
| Avell High... | A60 MUV                     | [e6b31a5408](https://linux-hardware.org/?probe=e6b31a5408) | Oct 12, 2021 |
| Acer          | Aspire A315-23G             | [6476999787](https://linux-hardware.org/?probe=6476999787) | Oct 12, 2021 |
| ASUSTek       | Z550MA                      | [dc911b6ef4](https://linux-hardware.org/?probe=dc911b6ef4) | Oct 12, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [edd8f01f22](https://linux-hardware.org/?probe=edd8f01f22) | Oct 12, 2021 |
| Dell          | G3 3590                     | [4c5db870d5](https://linux-hardware.org/?probe=4c5db870d5) | Oct 12, 2021 |
| Positivo      | S14BW01                     | [0a725f31b4](https://linux-hardware.org/?probe=0a725f31b4) | Oct 11, 2021 |
| Samsung       | 550XCJ/550XCR               | [5dd4cb8920](https://linux-hardware.org/?probe=5dd4cb8920) | Oct 11, 2021 |
| ASUSTek       | X510UR                      | [40a5b25871](https://linux-hardware.org/?probe=40a5b25871) | Oct 11, 2021 |
| Dell          | Inspiron 3442               | [c471d24818](https://linux-hardware.org/?probe=c471d24818) | Oct 11, 2021 |
| Samsung       | 550XBE/350XBE               | [34b3be8c54](https://linux-hardware.org/?probe=34b3be8c54) | Oct 11, 2021 |
| ASUSTek       | X451CAP                     | [3312d93006](https://linux-hardware.org/?probe=3312d93006) | Oct 11, 2021 |
| Acer          | Nitro AN515-43              | [e6eee85025](https://linux-hardware.org/?probe=e6eee85025) | Oct 11, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [61e272a119](https://linux-hardware.org/?probe=61e272a119) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f5147cd609](https://linux-hardware.org/?probe=f5147cd609) | Oct 10, 2021 |
| Acer          | Nitro AN515-44              | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E1-571               | [661aa3980f](https://linux-hardware.org/?probe=661aa3980f) | Oct 10, 2021 |
| Acer          | Aspire E5-571               | [d68a1a657f](https://linux-hardware.org/?probe=d68a1a657f) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b4efb9e18](https://linux-hardware.org/?probe=5b4efb9e18) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [3abe7cda22](https://linux-hardware.org/?probe=3abe7cda22) | Oct 10, 2021 |
| Samsung       | 550XCJ/550XCR               | [11f6b37f01](https://linux-hardware.org/?probe=11f6b37f01) | Oct 10, 2021 |
| Samsung       | 550XCJ/550XCR               | [c0ae5669be](https://linux-hardware.org/?probe=c0ae5669be) | Oct 10, 2021 |
| Samsung       | 550P5C/550P7C               | [3c7018cbdf](https://linux-hardware.org/?probe=3c7018cbdf) | Oct 10, 2021 |
| Digibras      | NH4CU53                     | [2d576fc462](https://linux-hardware.org/?probe=2d576fc462) | Oct 10, 2021 |
| Acer          | Aspire A315-23G             | [c97f94ce2f](https://linux-hardware.org/?probe=c97f94ce2f) | Oct 10, 2021 |
| HP            | Pavilion g4                 | [ec01cc8010](https://linux-hardware.org/?probe=ec01cc8010) | Oct 10, 2021 |
| Dell          | Inspiron 5447               | [689944cbda](https://linux-hardware.org/?probe=689944cbda) | Oct 10, 2021 |
| Dell          | Inspiron 1545               | [ce0b4be791](https://linux-hardware.org/?probe=ce0b4be791) | Oct 10, 2021 |
| Acer          | Aspire ES1-411              | [04643df6f1](https://linux-hardware.org/?probe=04643df6f1) | Oct 10, 2021 |
| LG Electro... | A530-T.BE76P1               | [393852d904](https://linux-hardware.org/?probe=393852d904) | Oct 10, 2021 |
| Acer          | Nitro AN515-54              | [47d670e622](https://linux-hardware.org/?probe=47d670e622) | Oct 10, 2021 |
| Acer          | Nitro AN515-54              | [5bba08307b](https://linux-hardware.org/?probe=5bba08307b) | Oct 10, 2021 |
| Toshiba       | Satellite C655              | [39f61ad9fd](https://linux-hardware.org/?probe=39f61ad9fd) | Oct 09, 2021 |
| HP            | TouchSmart tm2              | [4a04d297c6](https://linux-hardware.org/?probe=4a04d297c6) | Oct 09, 2021 |
| Sony          | SVT13115FBS                 | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| Acer          | Nitro AN515-54              | [f15efc966d](https://linux-hardware.org/?probe=f15efc966d) | Oct 08, 2021 |
| Dell          | G3 3500                     | [b4e985bcba](https://linux-hardware.org/?probe=b4e985bcba) | Oct 08, 2021 |
| Multilaser    | UB32X                       | [e5e22df913](https://linux-hardware.org/?probe=e5e22df913) | Oct 08, 2021 |
| OEM           | Unknown                     | [81ab5eba46](https://linux-hardware.org/?probe=81ab5eba46) | Oct 08, 2021 |
| Sony          | VPCEA20FB                   | [de4d94232e](https://linux-hardware.org/?probe=de4d94232e) | Oct 07, 2021 |
| Sony          | VPCEA20FB                   | [52e6abba3c](https://linux-hardware.org/?probe=52e6abba3c) | Oct 07, 2021 |
| ASUSTek       | X751LJ                      | [08ba22fc67](https://linux-hardware.org/?probe=08ba22fc67) | Oct 07, 2021 |
| OEM           | Unknown                     | [d7843090fc](https://linux-hardware.org/?probe=d7843090fc) | Oct 07, 2021 |
| Lenovo        | B320-14IKB 81CC             | [d2b36ea612](https://linux-hardware.org/?probe=d2b36ea612) | Oct 07, 2021 |
| Dell          | Inspiron 7560               | [f04c214239](https://linux-hardware.org/?probe=f04c214239) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9ed170f601](https://linux-hardware.org/?probe=9ed170f601) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [97f69ae3fa](https://linux-hardware.org/?probe=97f69ae3fa) | Oct 07, 2021 |
| Philco        | 14I                         | [0080a4ef97](https://linux-hardware.org/?probe=0080a4ef97) | Oct 07, 2021 |
| Philco        | 14I                         | [ff6fc89ff5](https://linux-hardware.org/?probe=ff6fc89ff5) | Oct 07, 2021 |
| Acer          | Aspire ES1-533              | [a1a36f11f4](https://linux-hardware.org/?probe=a1a36f11f4) | Oct 07, 2021 |
| Dell          | Latitude 5400               | [53a7573a6f](https://linux-hardware.org/?probe=53a7573a6f) | Oct 06, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [eb4d94004c](https://linux-hardware.org/?probe=eb4d94004c) | Oct 06, 2021 |
| Sony          | VPCEH40EB                   | [aa24653464](https://linux-hardware.org/?probe=aa24653464) | Oct 06, 2021 |
| Sony          | VPCEH40EB                   | [ea7ca4b810](https://linux-hardware.org/?probe=ea7ca4b810) | Oct 06, 2021 |
| Acer          | Aspire A515-54              | [d5dbcb7130](https://linux-hardware.org/?probe=d5dbcb7130) | Oct 06, 2021 |
| Acer          | Aspire A515-54              | [4ca9b7c23a](https://linux-hardware.org/?probe=4ca9b7c23a) | Oct 06, 2021 |
| Dell          | Inspiron 5570               | [d4931747ca](https://linux-hardware.org/?probe=d4931747ca) | Oct 05, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [e9b9d62598](https://linux-hardware.org/?probe=e9b9d62598) | Oct 05, 2021 |
| Dell          | Inspiron 5537               | [edd8cf99a2](https://linux-hardware.org/?probe=edd8cf99a2) | Oct 05, 2021 |
| Dell          | Inspiron N4010              | [717531e025](https://linux-hardware.org/?probe=717531e025) | Oct 05, 2021 |
| Acer          | Aspire A315-23G             | [9622936906](https://linux-hardware.org/?probe=9622936906) | Oct 04, 2021 |
| Dell          | Inspiron 5537               | [dc1d70608c](https://linux-hardware.org/?probe=dc1d70608c) | Oct 04, 2021 |
| HP            | 240 G1                      | [9aba4f2689](https://linux-hardware.org/?probe=9aba4f2689) | Oct 03, 2021 |
| Dell          | Vostro 3550                 | [e8fd995776](https://linux-hardware.org/?probe=e8fd995776) | Oct 03, 2021 |
| Sony          | VPCEH10EB                   | [c75fe465b1](https://linux-hardware.org/?probe=c75fe465b1) | Oct 03, 2021 |
| Acer          | Nitro AN515-54              | [f6aeb86bde](https://linux-hardware.org/?probe=f6aeb86bde) | Oct 02, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [3047b3ec7c](https://linux-hardware.org/?probe=3047b3ec7c) | Oct 02, 2021 |
| Dell          | Inspiron 3421               | [8169f29a6a](https://linux-hardware.org/?probe=8169f29a6a) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | Unknown                     | [56e7fa3c9b](https://linux-hardware.org/?probe=56e7fa3c9b) | Oct 02, 2021 |
| Acer          | Aspire A315-34              | [ffb9699d7a](https://linux-hardware.org/?probe=ffb9699d7a) | Oct 02, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [c2fda06302](https://linux-hardware.org/?probe=c2fda06302) | Oct 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [c79d1def32](https://linux-hardware.org/?probe=c79d1def32) | Oct 01, 2021 |
| Samsung       | 550XDA                      | [03b0767f75](https://linux-hardware.org/?probe=03b0767f75) | Oct 01, 2021 |
| Acer          | Aspire ES1-431              | [e8ca351107](https://linux-hardware.org/?probe=e8ca351107) | Oct 01, 2021 |
| Acer          | Aspire ES1-431              | [6e3f9142f0](https://linux-hardware.org/?probe=6e3f9142f0) | Oct 01, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [f5565dfb2a](https://linux-hardware.org/?probe=f5565dfb2a) | Oct 01, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [090eee57b7](https://linux-hardware.org/?probe=090eee57b7) | Oct 01, 2021 |
| Dell          | Inspiron 7520               | [2968458879](https://linux-hardware.org/?probe=2968458879) | Oct 01, 2021 |
| Dell          | Inspiron N5110              | [a0cb946b8a](https://linux-hardware.org/?probe=a0cb946b8a) | Oct 01, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2e10a8baf0](https://linux-hardware.org/?probe=2e10a8baf0) | Sep 30, 2021 |
| Positivo      | Mobile                      | [9e098ffe5e](https://linux-hardware.org/?probe=9e098ffe5e) | Sep 30, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [60fe11ee00](https://linux-hardware.org/?probe=60fe11ee00) | Sep 30, 2021 |
| Dell          | Inspiron 7520               | [964476869c](https://linux-hardware.org/?probe=964476869c) | Sep 30, 2021 |
| Dell          | Inspiron 7520               | [2fe59d03eb](https://linux-hardware.org/?probe=2fe59d03eb) | Sep 30, 2021 |
| Acer          | Aspire A315-23G             | [b8b2183bc1](https://linux-hardware.org/?probe=b8b2183bc1) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| Positivo      | Mobile                      | [fb85092913](https://linux-hardware.org/?probe=fb85092913) | Sep 30, 2021 |
| Positivo      | Mobile                      | [e45a4b5186](https://linux-hardware.org/?probe=e45a4b5186) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| Samsung       | 270E5G/270E5U               | [5b9a273adf](https://linux-hardware.org/?probe=5b9a273adf) | Sep 29, 2021 |
| Acer          | Aspire VX5-591G             | [949ac66eff](https://linux-hardware.org/?probe=949ac66eff) | Sep 29, 2021 |
| Positivo      | Smash3                      | [fe185c2e3f](https://linux-hardware.org/?probe=fe185c2e3f) | Sep 29, 2021 |
| Acer          | Aspire E5-573G              | [6c15236ba3](https://linux-hardware.org/?probe=6c15236ba3) | Sep 29, 2021 |
| Lenovo        | B320-14IKB 81CC             | [a460edd4e8](https://linux-hardware.org/?probe=a460edd4e8) | Sep 29, 2021 |
| Acer          | Aspire A315-23G             | [f7a5bd6c04](https://linux-hardware.org/?probe=f7a5bd6c04) | Sep 29, 2021 |
| Dell          | Inspiron 7520               | [f3e306d3de](https://linux-hardware.org/?probe=f3e306d3de) | Sep 29, 2021 |
| Acer          | TravelMate P449-G2-M        | [17a839112e](https://linux-hardware.org/?probe=17a839112e) | Sep 28, 2021 |
| Acer          | TravelMate P449-G2-M        | [bde64491bc](https://linux-hardware.org/?probe=bde64491bc) | Sep 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [c81def3b2e](https://linux-hardware.org/?probe=c81def3b2e) | Sep 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [50601caf44](https://linux-hardware.org/?probe=50601caf44) | Sep 28, 2021 |
| CCE           | Capella & IbexPeak-M Chi... | [062fa178c0](https://linux-hardware.org/?probe=062fa178c0) | Sep 28, 2021 |
| Acer          | Aspire V5-471               | [a9e4f4822e](https://linux-hardware.org/?probe=a9e4f4822e) | Sep 28, 2021 |
| Positivo      | Mobile                      | [960cbb831a](https://linux-hardware.org/?probe=960cbb831a) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Positivo      | S14BW01                     | [6a9cecbb0e](https://linux-hardware.org/?probe=6a9cecbb0e) | Sep 27, 2021 |
| Acer          | Aspire E1-471               | [dc9d130047](https://linux-hardware.org/?probe=dc9d130047) | Sep 27, 2021 |
| Acer          | Aspire 4553                 | [70acc3adae](https://linux-hardware.org/?probe=70acc3adae) | Sep 27, 2021 |
| Digibras      | NH4CU53                     | [f0615abf72](https://linux-hardware.org/?probe=f0615abf72) | Sep 27, 2021 |
| HP            | Pavilion g4                 | [bb0793d3ab](https://linux-hardware.org/?probe=bb0793d3ab) | Sep 27, 2021 |
| HP            | Pavilion g4                 | [029c21cd2d](https://linux-hardware.org/?probe=029c21cd2d) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | [721c266b6b](https://linux-hardware.org/?probe=721c266b6b) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | [00d9651c96](https://linux-hardware.org/?probe=00d9651c96) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | [f290c9b80f](https://linux-hardware.org/?probe=f290c9b80f) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | [82bd2ec7eb](https://linux-hardware.org/?probe=82bd2ec7eb) | Sep 27, 2021 |
| Sony          | VPCEA47FX                   | [630184b246](https://linux-hardware.org/?probe=630184b246) | Sep 27, 2021 |
| Dell          | Inspiron 1420               | [2d74e1dee2](https://linux-hardware.org/?probe=2d74e1dee2) | Sep 27, 2021 |
| Positivo      | W940TU                      | [0153e89101](https://linux-hardware.org/?probe=0153e89101) | Sep 27, 2021 |
| Positivo      | EC10IS1                     | [3e75f71b33](https://linux-hardware.org/?probe=3e75f71b33) | Sep 26, 2021 |
| Gateway       | NE56R                       | [09c06599e4](https://linux-hardware.org/?probe=09c06599e4) | Sep 26, 2021 |
| Positivo      | W940TU                      | [fc44f175b0](https://linux-hardware.org/?probe=fc44f175b0) | Sep 26, 2021 |
| Dell          | Inspiron 1420               | [6786f73aaa](https://linux-hardware.org/?probe=6786f73aaa) | Sep 26, 2021 |
| LG Electro... | X140-G.BG12P1               | [626d49a6a9](https://linux-hardware.org/?probe=626d49a6a9) | Sep 26, 2021 |
| Acer          | Aspire E5-571               | [67c627caba](https://linux-hardware.org/?probe=67c627caba) | Sep 26, 2021 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [8c5d298498](https://linux-hardware.org/?probe=8c5d298498) | Sep 26, 2021 |
| Lenovo        | ThinkPad X200 2024A16       | [36fb1f3891](https://linux-hardware.org/?probe=36fb1f3891) | Sep 26, 2021 |
| Acer          | Aspire A515-54G             | [65f21b6089](https://linux-hardware.org/?probe=65f21b6089) | Sep 26, 2021 |
| HP            | Pavilion 14                 | [2ab5781fef](https://linux-hardware.org/?probe=2ab5781fef) | Sep 25, 2021 |
| HP            | ProBook 6465b               | [dbff45c387](https://linux-hardware.org/?probe=dbff45c387) | Sep 25, 2021 |
| Dell          | Inspiron 5502               | [b484f4f0cc](https://linux-hardware.org/?probe=b484f4f0cc) | Sep 25, 2021 |
| Dell          | Inspiron 5402               | [a48ffce26d](https://linux-hardware.org/?probe=a48ffce26d) | Sep 25, 2021 |
| Dell          | Latitude E6430              | [cf0b1842b5](https://linux-hardware.org/?probe=cf0b1842b5) | Sep 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5dc4b1b49b](https://linux-hardware.org/?probe=5dc4b1b49b) | Sep 25, 2021 |
| Gateway       | NE56R                       | [ae70cb194b](https://linux-hardware.org/?probe=ae70cb194b) | Sep 25, 2021 |
| Positivo      | Smash3                      | [ee8284c509](https://linux-hardware.org/?probe=ee8284c509) | Sep 24, 2021 |
| Lenovo        | G40-70 80GA                 | [f2f6396a3c](https://linux-hardware.org/?probe=f2f6396a3c) | Sep 24, 2021 |
| LG Electro... | X140-G.BG12P1               | [d5bb2a15f6](https://linux-hardware.org/?probe=d5bb2a15f6) | Sep 24, 2021 |
| Positivo      | CHT12CP                     | [0a2987d902](https://linux-hardware.org/?probe=0a2987d902) | Sep 24, 2021 |
| Dell          | Inspiron 3584               | [4f8cf87cd0](https://linux-hardware.org/?probe=4f8cf87cd0) | Sep 24, 2021 |
| Avell High... | B.ON                        | [45c4ec81ea](https://linux-hardware.org/?probe=45c4ec81ea) | Sep 24, 2021 |
| Positivo      | Smash3                      | [9789e38ff6](https://linux-hardware.org/?probe=9789e38ff6) | Sep 23, 2021 |
| Acer          | Nitro AN515-54              | [1f03dc33de](https://linux-hardware.org/?probe=1f03dc33de) | Sep 23, 2021 |
| Philco        | 14F                         | [093b9632e8](https://linux-hardware.org/?probe=093b9632e8) | Sep 23, 2021 |
| Dell          | System Inspiron N4120       | [5da38a8b5e](https://linux-hardware.org/?probe=5da38a8b5e) | Sep 23, 2021 |
| Acer          | Nitro AN515-54              | [abdedf857f](https://linux-hardware.org/?probe=abdedf857f) | Sep 23, 2021 |
| Positivo      | NB50TH 11144919             | [25c060dd59](https://linux-hardware.org/?probe=25c060dd59) | Sep 23, 2021 |
| Positivo      | CHT12CP                     | [1473ddbea8](https://linux-hardware.org/?probe=1473ddbea8) | Sep 22, 2021 |
| Lenovo        | ThinkPad T480 20L6SCWK00    | [d8f862995c](https://linux-hardware.org/?probe=d8f862995c) | Sep 22, 2021 |
| Dell          | Inspiron 6000               | [f48bad44cd](https://linux-hardware.org/?probe=f48bad44cd) | Sep 22, 2021 |
| Dell          | Inspiron 6000               | [9b3cde9b5f](https://linux-hardware.org/?probe=9b3cde9b5f) | Sep 22, 2021 |
| Positivo      | NB50TH 11144919             | [8aea8bce96](https://linux-hardware.org/?probe=8aea8bce96) | Sep 22, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [86fcd8882b](https://linux-hardware.org/?probe=86fcd8882b) | Sep 22, 2021 |
| Acer          | Aspire E5-571               | [2c3343049c](https://linux-hardware.org/?probe=2c3343049c) | Sep 22, 2021 |
| Dell          | G5 5590                     | [90e0f568ef](https://linux-hardware.org/?probe=90e0f568ef) | Sep 22, 2021 |
| Dell          | G5 5590                     | [484c36584c](https://linux-hardware.org/?probe=484c36584c) | Sep 22, 2021 |
| Toshiba       | IS 1442                     | [26b3724f40](https://linux-hardware.org/?probe=26b3724f40) | Sep 22, 2021 |
| ASUSTek       | X510UR                      | [fb80dd8209](https://linux-hardware.org/?probe=fb80dd8209) | Sep 22, 2021 |
| Dell          | Vostro 5402                 | [9662887c26](https://linux-hardware.org/?probe=9662887c26) | Sep 22, 2021 |
| Apple         | MacBookPro9,2               | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| Samsung       | 550XCJ/550XCR               | [e886fe36b0](https://linux-hardware.org/?probe=e886fe36b0) | Sep 22, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [04f654bbf6](https://linux-hardware.org/?probe=04f654bbf6) | Sep 22, 2021 |
| HP            | ProBook 445 G7 Notebook ... | [c9a187f9b5](https://linux-hardware.org/?probe=c9a187f9b5) | Sep 22, 2021 |
| Samsung       | RV415                       | [9fbf78d306](https://linux-hardware.org/?probe=9fbf78d306) | Sep 21, 2021 |
| Lenovo        | G40-70 80GA                 | [8ba031b32f](https://linux-hardware.org/?probe=8ba031b32f) | Sep 21, 2021 |
| Acer          | Aspire E5-571               | [984abecd8d](https://linux-hardware.org/?probe=984abecd8d) | Sep 21, 2021 |
| Apple         | MacBookPro8,1               | [a08d8ecd94](https://linux-hardware.org/?probe=a08d8ecd94) | Sep 21, 2021 |
| Acer          | Aspire A315-54              | [f06a523887](https://linux-hardware.org/?probe=f06a523887) | Sep 21, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [cc973ea077](https://linux-hardware.org/?probe=cc973ea077) | Sep 21, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [be7dfbdb8e](https://linux-hardware.org/?probe=be7dfbdb8e) | Sep 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | [9d2e1404e3](https://linux-hardware.org/?probe=9d2e1404e3) | Sep 20, 2021 |
| Dell          | Inspiron 5537               | [e118644949](https://linux-hardware.org/?probe=e118644949) | Sep 20, 2021 |
| Dell          | Inspiron 5537               | [e713d93c95](https://linux-hardware.org/?probe=e713d93c95) | Sep 20, 2021 |
| Unknown       | Unknown                     | [2380a0486d](https://linux-hardware.org/?probe=2380a0486d) | Sep 20, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [fb681f1d38](https://linux-hardware.org/?probe=fb681f1d38) | Sep 20, 2021 |
| Acer          | Aspire A515-51              | [aa89265aaf](https://linux-hardware.org/?probe=aa89265aaf) | Sep 20, 2021 |
| HP            | Pavilion dv6                | [05a48a70a1](https://linux-hardware.org/?probe=05a48a70a1) | Sep 19, 2021 |
| Positivo      | S14CT01                     | [0d1ab84e09](https://linux-hardware.org/?probe=0d1ab84e09) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Apple         | MacBook4,1                  | [92c40f2b14](https://linux-hardware.org/?probe=92c40f2b14) | Sep 19, 2021 |
| Acer          | Nitro AN515-54              | [25fd382b32](https://linux-hardware.org/?probe=25fd382b32) | Sep 19, 2021 |
| Notebook      | W65_W67RN,RC1,RCY           | [c3f2419a83](https://linux-hardware.org/?probe=c3f2419a83) | Sep 18, 2021 |
| Notebook      | W65_W67RN,RC1,RCY           | [63dde78ef0](https://linux-hardware.org/?probe=63dde78ef0) | Sep 18, 2021 |
| HP            | G42                         | [0e9914c9cc](https://linux-hardware.org/?probe=0e9914c9cc) | Sep 18, 2021 |
| Acer          | Aspire A515-54              | [e44f6e672e](https://linux-hardware.org/?probe=e44f6e672e) | Sep 18, 2021 |
| Acer          | AO725                       | [8b4adc738c](https://linux-hardware.org/?probe=8b4adc738c) | Sep 18, 2021 |
| Dell          | Inspiron 15-3567            | [44902b132d](https://linux-hardware.org/?probe=44902b132d) | Sep 18, 2021 |
| Dell          | Latitude 3490               | [bf645d2394](https://linux-hardware.org/?probe=bf645d2394) | Sep 17, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [69e45df388](https://linux-hardware.org/?probe=69e45df388) | Sep 17, 2021 |
| Lenovo        | G460 0677                   | [6f23b54ef5](https://linux-hardware.org/?probe=6f23b54ef5) | Sep 17, 2021 |
| Positivo      | Mobile                      | [6f701d72fd](https://linux-hardware.org/?probe=6f701d72fd) | Sep 17, 2021 |
| Acer          | Aspire F5-573G              | [fb99d0767d](https://linux-hardware.org/?probe=fb99d0767d) | Sep 17, 2021 |
| Acer          | Aspire V3-572G              | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| Unknown       | Unknown                     | [d7b86e803f](https://linux-hardware.org/?probe=d7b86e803f) | Sep 16, 2021 |
| HP            | Laptop 15-db0xxx            | [94284ba5b0](https://linux-hardware.org/?probe=94284ba5b0) | Sep 16, 2021 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [1982fe12c4](https://linux-hardware.org/?probe=1982fe12c4) | Sep 16, 2021 |
| Dell          | Inspiron 7520               | [1141e79a29](https://linux-hardware.org/?probe=1141e79a29) | Sep 16, 2021 |
| Dell          | Vostro 5402                 | [670c2b0df7](https://linux-hardware.org/?probe=670c2b0df7) | Sep 16, 2021 |
| Dell          | Vostro 5402                 | [134631220f](https://linux-hardware.org/?probe=134631220f) | Sep 16, 2021 |
| Acer          | Predator PH315-52           | [30772ab737](https://linux-hardware.org/?probe=30772ab737) | Sep 16, 2021 |
| Acer          | Predator PH315-52           | [7fd7b5116f](https://linux-hardware.org/?probe=7fd7b5116f) | Sep 16, 2021 |
| HP            | Laptop 15-bs1xx             | [226f916086](https://linux-hardware.org/?probe=226f916086) | Sep 15, 2021 |
| Samsung       | 700Z3C/700Z5C               | [8307888e2a](https://linux-hardware.org/?probe=8307888e2a) | Sep 15, 2021 |
| Dell          | Inspiron 7520               | [28e7ace40d](https://linux-hardware.org/?probe=28e7ace40d) | Sep 15, 2021 |
| Dell          | Inspiron 3437               | [67069e48f0](https://linux-hardware.org/?probe=67069e48f0) | Sep 15, 2021 |
| Dell          | Inspiron 1545               | [8cdc0019ed](https://linux-hardware.org/?probe=8cdc0019ed) | Sep 15, 2021 |
| Acer          | Nitro AN515-54              | [6a3592ad63](https://linux-hardware.org/?probe=6a3592ad63) | Sep 15, 2021 |
| Dell          | Vostro 3560                 | [571644e06b](https://linux-hardware.org/?probe=571644e06b) | Sep 14, 2021 |
| Lenovo        | ThinkPad T450s 20BWZ0CKU... | [a9e206d41b](https://linux-hardware.org/?probe=a9e206d41b) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [785f6c0a11](https://linux-hardware.org/?probe=785f6c0a11) | Sep 14, 2021 |
| Dell          | Inspiron 15-3567            | [7e486cd179](https://linux-hardware.org/?probe=7e486cd179) | Sep 14, 2021 |
| Dell          | Latitude 3400               | [bfc68e0d9b](https://linux-hardware.org/?probe=bfc68e0d9b) | Sep 14, 2021 |
| Acer          | Aspire S3                   | [1c1964dc70](https://linux-hardware.org/?probe=1c1964dc70) | Sep 14, 2021 |
| Acer          | Nitro AN515-54              | [8f215120c2](https://linux-hardware.org/?probe=8f215120c2) | Sep 13, 2021 |
| Dell          | Inspiron 5402               | [f6865a8228](https://linux-hardware.org/?probe=f6865a8228) | Sep 13, 2021 |
| Acer          | Aspire A515-54              | [d27165285a](https://linux-hardware.org/?probe=d27165285a) | Sep 13, 2021 |
| Lenovo        | BS145-15IIL 82HB            | [c731e4ee9d](https://linux-hardware.org/?probe=c731e4ee9d) | Sep 13, 2021 |
| Lenovo        | BS145-15IIL 82HB            | [267d8551a9](https://linux-hardware.org/?probe=267d8551a9) | Sep 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7e31c12fab](https://linux-hardware.org/?probe=7e31c12fab) | Sep 13, 2021 |
| Qbex          | UDPAIOQBEX01                | [34c385cfe4](https://linux-hardware.org/?probe=34c385cfe4) | Sep 13, 2021 |
| Lenovo        | ThinkPad E14 20RB0028BR     | [8b1b3a98ba](https://linux-hardware.org/?probe=8b1b3a98ba) | Sep 12, 2021 |
| Dell          | Inspiron 1545               | [271309ac53](https://linux-hardware.org/?probe=271309ac53) | Sep 12, 2021 |
| Gateway       | NE56R                       | [1cf7429528](https://linux-hardware.org/?probe=1cf7429528) | Sep 12, 2021 |
| Dell          | Inspiron 5420               | [bc80b42442](https://linux-hardware.org/?probe=bc80b42442) | Sep 12, 2021 |
| Dell          | Inspiron 5448               | [2a2625d85f](https://linux-hardware.org/?probe=2a2625d85f) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1465a2e9d6](https://linux-hardware.org/?probe=1465a2e9d6) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| Digibras      | NH4CU53                     | [5f2f500f7a](https://linux-hardware.org/?probe=5f2f500f7a) | Sep 10, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [dd09fcf11e](https://linux-hardware.org/?probe=dd09fcf11e) | Sep 10, 2021 |
| ASUSTek       | X45U                        | [ebb2079624](https://linux-hardware.org/?probe=ebb2079624) | Sep 10, 2021 |
| Positivo      | C14RV01                     | [fc6fa07b38](https://linux-hardware.org/?probe=fc6fa07b38) | Sep 10, 2021 |
| HP            | EliteBook 840 G6            | [797c4816b1](https://linux-hardware.org/?probe=797c4816b1) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| Dell          | XPS 13 9370                 | [8dfaed35a4](https://linux-hardware.org/?probe=8dfaed35a4) | Sep 09, 2021 |
| ASUSTek       | K84C                        | [6a6f283e0f](https://linux-hardware.org/?probe=6a6f283e0f) | Sep 09, 2021 |
| Itautec       | Infoway a7420               | [282046f0c0](https://linux-hardware.org/?probe=282046f0c0) | Sep 09, 2021 |
| Dell          | Inspiron 7348               | [d0d5054fe1](https://linux-hardware.org/?probe=d0d5054fe1) | Sep 09, 2021 |
| LG Electro... | A530-T.BE76P1               | [844d7b2492](https://linux-hardware.org/?probe=844d7b2492) | Sep 09, 2021 |
| LG Electro... | A410-K.BE43P1               | [7add887914](https://linux-hardware.org/?probe=7add887914) | Sep 08, 2021 |
| Dell          | Inspiron N4030              | [8944573827](https://linux-hardware.org/?probe=8944573827) | Sep 08, 2021 |
| Acer          | Aspire F5-573G              | [527f58e3a8](https://linux-hardware.org/?probe=527f58e3a8) | Sep 08, 2021 |
| HP            | Pavilion dv4-1120br         | [07bd9042be](https://linux-hardware.org/?probe=07bd9042be) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion dv4-1120br         | [e56dba587b](https://linux-hardware.org/?probe=e56dba587b) | Sep 08, 2021 |
| HP            | G42                         | [bd7069bf8d](https://linux-hardware.org/?probe=bd7069bf8d) | Sep 07, 2021 |
| Acer          | Aspire E1-571               | [6eb800a8c2](https://linux-hardware.org/?probe=6eb800a8c2) | Sep 07, 2021 |
| Acer          | Nitro AN515-54              | [62020026f9](https://linux-hardware.org/?probe=62020026f9) | Sep 07, 2021 |
| Acer          | Nitro AN515-44              | [550876baee](https://linux-hardware.org/?probe=550876baee) | Sep 07, 2021 |
| Acer          | V5-171                      | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| Acer          | Nitro AN515-54              | [ff1e6a6f98](https://linux-hardware.org/?probe=ff1e6a6f98) | Sep 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [1b6daffa3e](https://linux-hardware.org/?probe=1b6daffa3e) | Sep 07, 2021 |
| Positivo      | MOBILE                      | [dbef32639d](https://linux-hardware.org/?probe=dbef32639d) | Sep 07, 2021 |
| LG Electro... | S425-L.BC24P1               | [f3a726fe5e](https://linux-hardware.org/?probe=f3a726fe5e) | Sep 06, 2021 |
| Positivo      | MOBILE                      | [a309a16af9](https://linux-hardware.org/?probe=a309a16af9) | Sep 06, 2021 |
| Samsung       | 550XBE/350XBE               | [b6ebf59cfa](https://linux-hardware.org/?probe=b6ebf59cfa) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Dell          | Vostro 5490                 | [b6e28c84c8](https://linux-hardware.org/?probe=b6e28c84c8) | Sep 06, 2021 |
| LG Electro... | A410-K.BE43P1               | [889fd56c8b](https://linux-hardware.org/?probe=889fd56c8b) | Sep 05, 2021 |
| Dell          | Inspiron N4050              | [486c5704ac](https://linux-hardware.org/?probe=486c5704ac) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Lenovo        | ThinkPad P50 20EQS64N1N     | [51637c3908](https://linux-hardware.org/?probe=51637c3908) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | [e4b4aa030b](https://linux-hardware.org/?probe=e4b4aa030b) | Sep 05, 2021 |
| Acer          | Aspire 6935                 | [6380b270a4](https://linux-hardware.org/?probe=6380b270a4) | Sep 05, 2021 |
| Dell          | System Vostro 3460          | [e725d75229](https://linux-hardware.org/?probe=e725d75229) | Sep 05, 2021 |
| Acer          | Aspire 4736Z                | [4e468942bb](https://linux-hardware.org/?probe=4e468942bb) | Sep 05, 2021 |
| Acer          | Aspire 4736Z                | [fdc2390413](https://linux-hardware.org/?probe=fdc2390413) | Sep 05, 2021 |
| Dell          | Inspiron N4050              | [b86818b509](https://linux-hardware.org/?probe=b86818b509) | Sep 05, 2021 |
| Intel         | SharkBay Platform           | [a19a4b3125](https://linux-hardware.org/?probe=a19a4b3125) | Sep 05, 2021 |
| Acer          | Nitro AN515-52              | [e0579175c3](https://linux-hardware.org/?probe=e0579175c3) | Sep 05, 2021 |
| ASUSTek       | GL553VD                     | [340d7d28d0](https://linux-hardware.org/?probe=340d7d28d0) | Sep 05, 2021 |
| ASUSTek       | GL553VD                     | [a1dd62b9c8](https://linux-hardware.org/?probe=a1dd62b9c8) | Sep 04, 2021 |
| Dell          | Latitude 3490               | [304e16b939](https://linux-hardware.org/?probe=304e16b939) | Sep 04, 2021 |
| Dell          | Latitude 3490               | [edc14d7a25](https://linux-hardware.org/?probe=edc14d7a25) | Sep 04, 2021 |
| Positivo      | MOBILE                      | [6d447067b0](https://linux-hardware.org/?probe=6d447067b0) | Sep 04, 2021 |
| Dell          | Inspiron 7572               | [5fa8f9c97d](https://linux-hardware.org/?probe=5fa8f9c97d) | Sep 04, 2021 |
| Dell          | Inspiron 7572               | [107f6fe7d8](https://linux-hardware.org/?probe=107f6fe7d8) | Sep 04, 2021 |
| Acer          | Nitro AN515-44              | [01078048fe](https://linux-hardware.org/?probe=01078048fe) | Sep 04, 2021 |
| Samsung       | 275E4E/275E5E               | [1503acee14](https://linux-hardware.org/?probe=1503acee14) | Sep 04, 2021 |
| Acer          | Nitro AN515-44              | [328451404d](https://linux-hardware.org/?probe=328451404d) | Sep 04, 2021 |
| Lenovo        | IdeaPad G485 QAWGE          | [e4e83ad591](https://linux-hardware.org/?probe=e4e83ad591) | Sep 04, 2021 |
| HP            | G42                         | [cace650582](https://linux-hardware.org/?probe=cace650582) | Sep 03, 2021 |
| Positivo      | S14CT01                     | [f766cef59e](https://linux-hardware.org/?probe=f766cef59e) | Sep 03, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [0d9d760140](https://linux-hardware.org/?probe=0d9d760140) | Sep 03, 2021 |
| Acer          | Nitro AN515-44              | [556461d567](https://linux-hardware.org/?probe=556461d567) | Sep 03, 2021 |
| HP            | Pavilion g4                 | [383792988a](https://linux-hardware.org/?probe=383792988a) | Sep 02, 2021 |
| Acer          | Aspire A515-54              | [71929d46ed](https://linux-hardware.org/?probe=71929d46ed) | Sep 02, 2021 |
| Toshiba       | Satellite C655              | [1a24fad6d9](https://linux-hardware.org/?probe=1a24fad6d9) | Sep 02, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [7a7454a9ae](https://linux-hardware.org/?probe=7a7454a9ae) | Sep 02, 2021 |
| Acer          | Unknown                     | [e05afa34e0](https://linux-hardware.org/?probe=e05afa34e0) | Sep 02, 2021 |
| Toshiba       | IS 1412                     | [ae90a1e459](https://linux-hardware.org/?probe=ae90a1e459) | Sep 02, 2021 |
| HP            | Pavilion 14                 | [351766240c](https://linux-hardware.org/?probe=351766240c) | Sep 02, 2021 |
| Acer          | Aspire A515-54G             | [ac85e51b51](https://linux-hardware.org/?probe=ac85e51b51) | Sep 02, 2021 |
| Positivo      | C41TB                       | [d100e19cde](https://linux-hardware.org/?probe=d100e19cde) | Sep 01, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2bcede7edc](https://linux-hardware.org/?probe=2bcede7edc) | Sep 01, 2021 |
| Positivo      | C41TB                       | [e904092d0d](https://linux-hardware.org/?probe=e904092d0d) | Sep 01, 2021 |
| ASUSTek       | X550LN                      | [46a61ffaa2](https://linux-hardware.org/?probe=46a61ffaa2) | Aug 31, 2021 |
| Samsung       | 550XCJ/550XCR               | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| Acer          | Nitro AN515-54              | [7a1f1f60c1](https://linux-hardware.org/?probe=7a1f1f60c1) | Aug 31, 2021 |
| Acer          | Nitro AN515-54              | [88ff21e302](https://linux-hardware.org/?probe=88ff21e302) | Aug 31, 2021 |
| HP            | Pavilion dv9000 (RP250UA... | [0c205a9a39](https://linux-hardware.org/?probe=0c205a9a39) | Aug 31, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [372bae9a90](https://linux-hardware.org/?probe=372bae9a90) | Aug 31, 2021 |
| Ultra         | UB422                       | [80ab2e8dfb](https://linux-hardware.org/?probe=80ab2e8dfb) | Aug 31, 2021 |
| Ultra         | UB422                       | [b8580b548d](https://linux-hardware.org/?probe=b8580b548d) | Aug 31, 2021 |
| HP            | ENVY Laptop 17m-ae1xx       | [d92f056ec4](https://linux-hardware.org/?probe=d92f056ec4) | Aug 31, 2021 |
| HP            | ENVY Laptop 17m-ae1xx       | [a2bd6f37f5](https://linux-hardware.org/?probe=a2bd6f37f5) | Aug 31, 2021 |
| Acer          | Nitro AN515-43              | [580efac81c](https://linux-hardware.org/?probe=580efac81c) | Aug 30, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [35c20c8cde](https://linux-hardware.org/?probe=35c20c8cde) | Aug 30, 2021 |
| Dell          | Inspiron 5420               | [e2c3cab1e6](https://linux-hardware.org/?probe=e2c3cab1e6) | Aug 30, 2021 |
| Acer          | Aspire A515-54G             | [d072375b90](https://linux-hardware.org/?probe=d072375b90) | Aug 30, 2021 |
| ASUSTek       | X55U                        | [b37f7fdf24](https://linux-hardware.org/?probe=b37f7fdf24) | Aug 30, 2021 |
| PC Special... | Standard                    | [d0f28adb7f](https://linux-hardware.org/?probe=d0f28adb7f) | Aug 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [05e455f345](https://linux-hardware.org/?probe=05e455f345) | Aug 29, 2021 |
| Dell          | Inspiron N5110              | [b833562cba](https://linux-hardware.org/?probe=b833562cba) | Aug 28, 2021 |
| Lenovo        | G40-70 80GA                 | [aed5859ee4](https://linux-hardware.org/?probe=aed5859ee4) | Aug 28, 2021 |
| Lenovo        | ThinkPad L450 20DS0090BR    | [d70471f6ed](https://linux-hardware.org/?probe=d70471f6ed) | Aug 28, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [24a34a526e](https://linux-hardware.org/?probe=24a34a526e) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| Dell          | Vostro 14-5480              | [7f02b7109c](https://linux-hardware.org/?probe=7f02b7109c) | Aug 28, 2021 |
| Dell          | Vostro 14-5480              | [d258b6a34d](https://linux-hardware.org/?probe=d258b6a34d) | Aug 28, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7945f91910](https://linux-hardware.org/?probe=7945f91910) | Aug 28, 2021 |
| Philco        | 14I                         | [b317859f95](https://linux-hardware.org/?probe=b317859f95) | Aug 27, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [96188348ae](https://linux-hardware.org/?probe=96188348ae) | Aug 27, 2021 |
| Dell          | Inspiron 5566               | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Itautec       | Infoway w7535               | [f7d8a66820](https://linux-hardware.org/?probe=f7d8a66820) | Aug 27, 2021 |
| Lenovo        | G460 0677                   | [c1aef4b748](https://linux-hardware.org/?probe=c1aef4b748) | Aug 27, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [4b3639d80e](https://linux-hardware.org/?probe=4b3639d80e) | Aug 27, 2021 |
| Acer          | Nitro AN515-44              | [b962febc08](https://linux-hardware.org/?probe=b962febc08) | Aug 27, 2021 |
| Acer          | Nitro AN515-44              | [9860810902](https://linux-hardware.org/?probe=9860810902) | Aug 27, 2021 |
| Dell          | Inspiron 5566               | [21f8762e74](https://linux-hardware.org/?probe=21f8762e74) | Aug 26, 2021 |
| Acer          | Nitro AN515-51              | [93805b6685](https://linux-hardware.org/?probe=93805b6685) | Aug 26, 2021 |
| Dell          | Inspiron 5566               | [42184613d7](https://linux-hardware.org/?probe=42184613d7) | Aug 26, 2021 |
| Dell          | Inspiron 3421               | [06a0a6486b](https://linux-hardware.org/?probe=06a0a6486b) | Aug 26, 2021 |
| ASUSTek       | S400CA                      | [d1c2760711](https://linux-hardware.org/?probe=d1c2760711) | Aug 26, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [9e833b1841](https://linux-hardware.org/?probe=9e833b1841) | Aug 25, 2021 |
| HP            | Mini 110-3100               | [2bca9a30ab](https://linux-hardware.org/?probe=2bca9a30ab) | Aug 25, 2021 |
| HP            | Compaq Presario CQ40        | [536d19c594](https://linux-hardware.org/?probe=536d19c594) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| OEM           | I41SI1                      | [5eb737349b](https://linux-hardware.org/?probe=5eb737349b) | Aug 25, 2021 |
| Acer          | Nitro AN515-43              | [a2810491aa](https://linux-hardware.org/?probe=a2810491aa) | Aug 25, 2021 |
| Positivo      | C14CU51                     | [76dacbccfb](https://linux-hardware.org/?probe=76dacbccfb) | Aug 25, 2021 |
| Acer          | Nitro AN515-43              | [051ab1f020](https://linux-hardware.org/?probe=051ab1f020) | Aug 25, 2021 |
| Acer          | Aspire A315-56              | [bf1f07bd8f](https://linux-hardware.org/?probe=bf1f07bd8f) | Aug 25, 2021 |
| Unknown       | Unknown                     | [a722690d72](https://linux-hardware.org/?probe=a722690d72) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| Compaq        | Presario CQ-17              | [4580d3fd1e](https://linux-hardware.org/?probe=4580d3fd1e) | Aug 25, 2021 |
| Acer          | Aspire A315-34              | [2bafe062e1](https://linux-hardware.org/?probe=2bafe062e1) | Aug 25, 2021 |
| Dell          | Inspiron 1564               | [2447fab09a](https://linux-hardware.org/?probe=2447fab09a) | Aug 25, 2021 |
| Dell          | Inspiron 5490               | [0899ac7f63](https://linux-hardware.org/?probe=0899ac7f63) | Aug 24, 2021 |
| LG Electro... | S460-G.BG31P1               | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| Lenovo        | ThinkPad T410 2537NP8       | [e17d2f91ab](https://linux-hardware.org/?probe=e17d2f91ab) | Aug 24, 2021 |
| Dell          | Inspiron 6000               | [fae1a81289](https://linux-hardware.org/?probe=fae1a81289) | Aug 24, 2021 |
| Dell          | Inspiron 6000               | [f4ae3e605a](https://linux-hardware.org/?probe=f4ae3e605a) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Toshiba       | QOSMIO X875                 | [e1a32c586a](https://linux-hardware.org/?probe=e1a32c586a) | Aug 24, 2021 |
| Itautec       | W7655                       | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Acer          | Nitro AN517-51              | [71ccda2082](https://linux-hardware.org/?probe=71ccda2082) | Aug 24, 2021 |
| Itautec       | W7655                       | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| Acer          | Nitro AN515-44              | [9d3109723f](https://linux-hardware.org/?probe=9d3109723f) | Aug 24, 2021 |
| HP            | 14                          | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| HP            | Pavilion 11 x360 PC         | [aae4194abb](https://linux-hardware.org/?probe=aae4194abb) | Aug 24, 2021 |
| Acer          | Nitro AN515-54              | [5305fab05a](https://linux-hardware.org/?probe=5305fab05a) | Aug 24, 2021 |
| Unknown       | Unknown                     | [a12413ac7e](https://linux-hardware.org/?probe=a12413ac7e) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| Acer          | Swift SF314-52              | [25ce57f1be](https://linux-hardware.org/?probe=25ce57f1be) | Aug 23, 2021 |
| Acer          | Swift SF314-52              | [cef75c8a5a](https://linux-hardware.org/?probe=cef75c8a5a) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Positivo      | C14CR21                     | [c4ae2acc0b](https://linux-hardware.org/?probe=c4ae2acc0b) | Aug 23, 2021 |
| Acer          | Nitro AN515-44              | [fd63229980](https://linux-hardware.org/?probe=fd63229980) | Aug 23, 2021 |
| Acer          | Aspire 4736Z                | [a8d66e3be1](https://linux-hardware.org/?probe=a8d66e3be1) | Aug 23, 2021 |
| Dell          | Vostro 1014                 | [9979ecdb25](https://linux-hardware.org/?probe=9979ecdb25) | Aug 23, 2021 |
| LG Electro... | N450-P.BE55P1               | [45e186ba9b](https://linux-hardware.org/?probe=45e186ba9b) | Aug 23, 2021 |
| LG Electro... | N450-P.BE55P1               | [c36379f182](https://linux-hardware.org/?probe=c36379f182) | Aug 23, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [ab8a4f01d9](https://linux-hardware.org/?probe=ab8a4f01d9) | Aug 22, 2021 |
| Unknown       | Unknown                     | [e492f61253](https://linux-hardware.org/?probe=e492f61253) | Aug 22, 2021 |
| Unknown       | Unknown                     | [cd6f08757d](https://linux-hardware.org/?probe=cd6f08757d) | Aug 22, 2021 |
| Acer          | Nitro AN515-44              | [cc4028eb7e](https://linux-hardware.org/?probe=cc4028eb7e) | Aug 22, 2021 |
| Acer          | Aspire 4553                 | [df2b36e50f](https://linux-hardware.org/?probe=df2b36e50f) | Aug 22, 2021 |
| Acer          | Aspire ES1-572              | [07e3a21f1c](https://linux-hardware.org/?probe=07e3a21f1c) | Aug 22, 2021 |
| Dell          | Inspiron 3583               | [0c1b7de3c6](https://linux-hardware.org/?probe=0c1b7de3c6) | Aug 22, 2021 |
| Dell          | Inspiron 5458               | [be003da971](https://linux-hardware.org/?probe=be003da971) | Aug 22, 2021 |
| ASUSTek       | S301LA                      | [24c5da75b2](https://linux-hardware.org/?probe=24c5da75b2) | Aug 21, 2021 |
| Acer          | Aspire 4553                 | [6f2a2ea051](https://linux-hardware.org/?probe=6f2a2ea051) | Aug 21, 2021 |
| Itautec       | Infoway w7535               | [ea3f721976](https://linux-hardware.org/?probe=ea3f721976) | Aug 21, 2021 |
| Acer          | Nitro AN515-44              | [c8d4e3b3d3](https://linux-hardware.org/?probe=c8d4e3b3d3) | Aug 21, 2021 |
| Dell          | Inspiron N5110              | [b36aeef8a9](https://linux-hardware.org/?probe=b36aeef8a9) | Aug 21, 2021 |
| Positivo      | Mobile                      | [e4a47e39b6](https://linux-hardware.org/?probe=e4a47e39b6) | Aug 21, 2021 |
| Avell High... | 1513                        | [ae529ae231](https://linux-hardware.org/?probe=ae529ae231) | Aug 20, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [b5ff89deed](https://linux-hardware.org/?probe=b5ff89deed) | Aug 20, 2021 |
| Sony          | VGN-FW235J                  | [cf6cd49762](https://linux-hardware.org/?probe=cf6cd49762) | Aug 20, 2021 |
| Samsung       | RV419                       | [ba6f454b7d](https://linux-hardware.org/?probe=ba6f454b7d) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6c1165c1e8](https://linux-hardware.org/?probe=6c1165c1e8) | Aug 19, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [c3ee19c6e2](https://linux-hardware.org/?probe=c3ee19c6e2) | Aug 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [aac5b963b0](https://linux-hardware.org/?probe=aac5b963b0) | Aug 19, 2021 |
| HP            | EliteBook 820 G1            | [cc95a4d3a9](https://linux-hardware.org/?probe=cc95a4d3a9) | Aug 19, 2021 |
| Philco        | 14L                         | [55ea231ff3](https://linux-hardware.org/?probe=55ea231ff3) | Aug 19, 2021 |
| Dell          | Inspiron 3583               | [2827e2a235](https://linux-hardware.org/?probe=2827e2a235) | Aug 19, 2021 |
| Acer          | Nitro AN515-44              | [4cb9827a7f](https://linux-hardware.org/?probe=4cb9827a7f) | Aug 19, 2021 |
| Acer          | Aspire A315-42              | [5d7d169777](https://linux-hardware.org/?probe=5d7d169777) | Aug 19, 2021 |
| Positivo      | Q232A                       | [f76d2dc489](https://linux-hardware.org/?probe=f76d2dc489) | Aug 19, 2021 |
| Acer          | Nitro AN515-54              | [52732fb8ca](https://linux-hardware.org/?probe=52732fb8ca) | Aug 19, 2021 |
| Dell          | Vostro 1014                 | [e2df3814b5](https://linux-hardware.org/?probe=e2df3814b5) | Aug 19, 2021 |
| Positivo      | C14CR01                     | [3840d4dd93](https://linux-hardware.org/?probe=3840d4dd93) | Aug 19, 2021 |
| Acer          | Aspire F5-573G              | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell          | Vostro 5402                 | [680ab5d19d](https://linux-hardware.org/?probe=680ab5d19d) | Aug 19, 2021 |
| HP            | 14                          | [cd7597d02c](https://linux-hardware.org/?probe=cd7597d02c) | Aug 18, 2021 |
| Positivo      | WCBT1013                    | [83538351b9](https://linux-hardware.org/?probe=83538351b9) | Aug 18, 2021 |
| Acer          | Nitro AN515-55              | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| Notebook      | N85_N870HL                  | [76e346d6a9](https://linux-hardware.org/?probe=76e346d6a9) | Aug 18, 2021 |
| Dell          | Inspiron 3481               | [9ed5edd900](https://linux-hardware.org/?probe=9ed5edd900) | Aug 18, 2021 |
| Gateway       | NE56R                       | [24dbdd4cdc](https://linux-hardware.org/?probe=24dbdd4cdc) | Aug 17, 2021 |
| Acer          | Nitro AN515-54              | [646a9b0d66](https://linux-hardware.org/?probe=646a9b0d66) | Aug 17, 2021 |
| Samsung       | 275E4E/275E5E               | [26f7b81074](https://linux-hardware.org/?probe=26f7b81074) | Aug 17, 2021 |
| Dell          | Latitude E6430              | [6ef784ba77](https://linux-hardware.org/?probe=6ef784ba77) | Aug 16, 2021 |
| Dell          | Inspiron 7520               | [124324c600](https://linux-hardware.org/?probe=124324c600) | Aug 16, 2021 |
| Itautec       | Infoway                     | [f66edac6bd](https://linux-hardware.org/?probe=f66edac6bd) | Aug 16, 2021 |
| Itautec       | Infoway                     | [94c198d530](https://linux-hardware.org/?probe=94c198d530) | Aug 16, 2021 |
| Dell          | Inspiron 7520               | [bfd895d451](https://linux-hardware.org/?probe=bfd895d451) | Aug 16, 2021 |
| Lenovo        | ThinkPad E490 20N9CTO1WW    | [4d4823043b](https://linux-hardware.org/?probe=4d4823043b) | Aug 16, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |
| Acer          | Aspire A315-33              | [a35ed6ad38](https://linux-hardware.org/?probe=a35ed6ad38) | Aug 15, 2021 |
| Acer          | Nitro AN515-44              | [d7303a008e](https://linux-hardware.org/?probe=d7303a008e) | Aug 15, 2021 |
| Acer          | Nitro AN515-44              | [c30f044292](https://linux-hardware.org/?probe=c30f044292) | Aug 15, 2021 |
| Samsung       | 550XDA                      | [244a7e0557](https://linux-hardware.org/?probe=244a7e0557) | Aug 15, 2021 |
| Samsung       | 550XDA                      | [a4a0ff8db8](https://linux-hardware.org/?probe=a4a0ff8db8) | Aug 15, 2021 |
| Positivo      | EC10IS1                     | [b980b4ac41](https://linux-hardware.org/?probe=b980b4ac41) | Aug 15, 2021 |
| HP            | Unknown                     | [11a771b463](https://linux-hardware.org/?probe=11a771b463) | Aug 15, 2021 |
| Acer          | Aspire A515-54G             | [b259e8a5e4](https://linux-hardware.org/?probe=b259e8a5e4) | Aug 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4cfe1daabe](https://linux-hardware.org/?probe=4cfe1daabe) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ffa5f6a0e](https://linux-hardware.org/?probe=1ffa5f6a0e) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d00e9f1724](https://linux-hardware.org/?probe=d00e9f1724) | Aug 14, 2021 |
| Samsung       | 550XCJ/550XCR               | [a0310af3b9](https://linux-hardware.org/?probe=a0310af3b9) | Aug 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [eda5da5e9d](https://linux-hardware.org/?probe=eda5da5e9d) | Aug 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [518309e6c8](https://linux-hardware.org/?probe=518309e6c8) | Aug 14, 2021 |
| SiS           | M672 Board SI94B-20+SI96... | [8268c73ee9](https://linux-hardware.org/?probe=8268c73ee9) | Aug 14, 2021 |
| Acer          | Aspire F5-573               | [8a33fea383](https://linux-hardware.org/?probe=8a33fea383) | Aug 14, 2021 |
| Acer          | Aspire F5-573               | [cada2d25da](https://linux-hardware.org/?probe=cada2d25da) | Aug 14, 2021 |
| Samsung       | 550XCJ/550XCR               | [7645f25b97](https://linux-hardware.org/?probe=7645f25b97) | Aug 13, 2021 |
| HP            | Pavilion g7                 | [cf766b8d76](https://linux-hardware.org/?probe=cf766b8d76) | Aug 13, 2021 |
| Acer          | Aspire ES1-572              | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Samsung       | 500R5L/501R5L/500R5P        | [921a3dd63a](https://linux-hardware.org/?probe=921a3dd63a) | Aug 13, 2021 |
| Toshiba       | STI NI 1401                 | [29e772749b](https://linux-hardware.org/?probe=29e772749b) | Aug 13, 2021 |
| Quanta        | QL5 TBD                     | [be465dec60](https://linux-hardware.org/?probe=be465dec60) | Aug 13, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [a858b600af](https://linux-hardware.org/?probe=a858b600af) | Aug 13, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [7f2119c011](https://linux-hardware.org/?probe=7f2119c011) | Aug 13, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6f0b883adb](https://linux-hardware.org/?probe=6f0b883adb) | Aug 13, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [5d036af9c0](https://linux-hardware.org/?probe=5d036af9c0) | Aug 13, 2021 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | [d6050ff7fd](https://linux-hardware.org/?probe=d6050ff7fd) | Aug 12, 2021 |
| Acer          | Aspire E5-574               | [7fb046bc6a](https://linux-hardware.org/?probe=7fb046bc6a) | Aug 12, 2021 |
| Dell          | Latitude 3480               | [183e87c32a](https://linux-hardware.org/?probe=183e87c32a) | Aug 12, 2021 |
| Acer          | Nitro AN515-44              | [be5e662b8b](https://linux-hardware.org/?probe=be5e662b8b) | Aug 12, 2021 |
| Dell          | Vostro 3500                 | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |
| HP            | EliteBook 840 G3            | [922c919fee](https://linux-hardware.org/?probe=922c919fee) | Aug 12, 2021 |
| Acer          | Nitro AN515-54              | [59cbec874f](https://linux-hardware.org/?probe=59cbec874f) | Aug 12, 2021 |
| HP            | EliteBook 840 G3            | [f8b250c60d](https://linux-hardware.org/?probe=f8b250c60d) | Aug 12, 2021 |
| Acer          | Aspire A315-42              | [d0df04d5c7](https://linux-hardware.org/?probe=d0df04d5c7) | Aug 12, 2021 |
| ASUSTek       | S400CA                      | [30f4447442](https://linux-hardware.org/?probe=30f4447442) | Aug 12, 2021 |
| Philco        | 14I                         | [4e890d95af](https://linux-hardware.org/?probe=4e890d95af) | Aug 12, 2021 |
| Philco        | 14I                         | [573449b1ca](https://linux-hardware.org/?probe=573449b1ca) | Aug 12, 2021 |
| Acer          | Nitro AN515-54              | [278d8c1623](https://linux-hardware.org/?probe=278d8c1623) | Aug 12, 2021 |
| Acer          | Nitro AN515-54              | [80e53d2ec8](https://linux-hardware.org/?probe=80e53d2ec8) | Aug 12, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [a95c474a81](https://linux-hardware.org/?probe=a95c474a81) | Aug 12, 2021 |
| Positivo B... | VJFE41F11X                  | [4b6dfe8371](https://linux-hardware.org/?probe=4b6dfe8371) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | [4139a3a855](https://linux-hardware.org/?probe=4139a3a855) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | [48573ed425](https://linux-hardware.org/?probe=48573ed425) | Aug 11, 2021 |
| Gateway       | NE56R                       | [4b7d585336](https://linux-hardware.org/?probe=4b7d585336) | Aug 11, 2021 |
| Digibras      | NH4CU53                     | [815877fb99](https://linux-hardware.org/?probe=815877fb99) | Aug 11, 2021 |
| Dell          | Inspiron 3421               | [c7b2e290c1](https://linux-hardware.org/?probe=c7b2e290c1) | Aug 11, 2021 |
| Acer          | Aspire ES1-531              | [7e9380ffa9](https://linux-hardware.org/?probe=7e9380ffa9) | Aug 11, 2021 |
| ASUSTek       | K43E                        | [26bc81cf3a](https://linux-hardware.org/?probe=26bc81cf3a) | Aug 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [476430ab6f](https://linux-hardware.org/?probe=476430ab6f) | Aug 11, 2021 |
| Acer          | Aspire 3810TZ               | [6b7176e5ed](https://linux-hardware.org/?probe=6b7176e5ed) | Aug 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [8fa18dec63](https://linux-hardware.org/?probe=8fa18dec63) | Aug 10, 2021 |
| HP            | Pavilion dv6700             | [ebf6b956cb](https://linux-hardware.org/?probe=ebf6b956cb) | Aug 10, 2021 |
| Samsung       | RV419                       | [66823b7d4d](https://linux-hardware.org/?probe=66823b7d4d) | Aug 10, 2021 |
| Dell          | Inspiron 7460               | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung       | R430/R480/R440              | [bd73bb6812](https://linux-hardware.org/?probe=bd73bb6812) | Aug 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b820018534](https://linux-hardware.org/?probe=b820018534) | Aug 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1f76a0939f](https://linux-hardware.org/?probe=1f76a0939f) | Aug 10, 2021 |
| Clevo         | W240HU/W250HUQ              | [24fa19e6a1](https://linux-hardware.org/?probe=24fa19e6a1) | Aug 09, 2021 |
| Lenovo        | ThinkPad X230 2325GB9       | [6e5ea08d23](https://linux-hardware.org/?probe=6e5ea08d23) | Aug 09, 2021 |
| HP            | ProBook 6465b               | [8d7f457e6e](https://linux-hardware.org/?probe=8d7f457e6e) | Aug 09, 2021 |
| Lenovo        | G400s VILG1                 | [fafcd58ccb](https://linux-hardware.org/?probe=fafcd58ccb) | Aug 09, 2021 |
| Pegatron      | B34C                        | [0a163fa2df](https://linux-hardware.org/?probe=0a163fa2df) | Aug 08, 2021 |
| Pegatron      | B34C                        | [a87801960b](https://linux-hardware.org/?probe=a87801960b) | Aug 08, 2021 |
| Dell          | Inspiron 7560               | [6c973f6f58](https://linux-hardware.org/?probe=6c973f6f58) | Aug 08, 2021 |
| Dell          | Inspiron 3583               | [e5cd3c79a9](https://linux-hardware.org/?probe=e5cd3c79a9) | Aug 07, 2021 |
| ASUSTek       | X451CAP                     | [2158b6df09](https://linux-hardware.org/?probe=2158b6df09) | Aug 07, 2021 |
| Dell          | Inspiron 3583               | [fa7e7858e1](https://linux-hardware.org/?probe=fa7e7858e1) | Aug 07, 2021 |
| Clevo         | P170EM                      | [f101b2b318](https://linux-hardware.org/?probe=f101b2b318) | Aug 07, 2021 |
| Dell          | Inspiron 3421               | [dc8767625f](https://linux-hardware.org/?probe=dc8767625f) | Aug 07, 2021 |
| ASUSTek       | K43E                        | [eddd994d41](https://linux-hardware.org/?probe=eddd994d41) | Aug 07, 2021 |
| Dell          | Inspiron 5452               | [0c9b3ec7a9](https://linux-hardware.org/?probe=0c9b3ec7a9) | Aug 07, 2021 |
| ASUSTek       | K43E                        | [b2b2898af3](https://linux-hardware.org/?probe=b2b2898af3) | Aug 07, 2021 |
| HP            | ProBook 4430s               | [5187fa9afd](https://linux-hardware.org/?probe=5187fa9afd) | Aug 07, 2021 |
| Samsung       | RC420/RC520/RC720           | [2b8b502924](https://linux-hardware.org/?probe=2b8b502924) | Aug 07, 2021 |
| ASUSTek       | Z450UAK                     | [51f0a2a12b](https://linux-hardware.org/?probe=51f0a2a12b) | Aug 07, 2021 |
| Dell          | Vostro 5402                 | [de89abacfd](https://linux-hardware.org/?probe=de89abacfd) | Aug 07, 2021 |
| Dell          | Inspiron 3421               | [52f396865d](https://linux-hardware.org/?probe=52f396865d) | Aug 07, 2021 |
| Sony          | VPCEB15FB                   | [15c824ba8c](https://linux-hardware.org/?probe=15c824ba8c) | Aug 07, 2021 |
| Positivo      | CHT14B                      | [c8d89d2cde](https://linux-hardware.org/?probe=c8d89d2cde) | Aug 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8e20b8e1ff](https://linux-hardware.org/?probe=8e20b8e1ff) | Aug 06, 2021 |
| Notebook      | Titanium B155 MAX           | [f1fd39abcd](https://linux-hardware.org/?probe=f1fd39abcd) | Aug 06, 2021 |
| Dell          | Inspiron 5558               | [d0439be169](https://linux-hardware.org/?probe=d0439be169) | Aug 06, 2021 |
| Dell          | Inspiron 7572               | [a41678d0ce](https://linux-hardware.org/?probe=a41678d0ce) | Aug 06, 2021 |
| Dell          | Inspiron 7572               | [aea38e48c7](https://linux-hardware.org/?probe=aea38e48c7) | Aug 06, 2021 |
| Notebook      | Titanium B155 MAX           | [2311d7a604](https://linux-hardware.org/?probe=2311d7a604) | Aug 05, 2021 |
| Unknown       | Unknown                     | [608425d791](https://linux-hardware.org/?probe=608425d791) | Aug 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6fe693a80e](https://linux-hardware.org/?probe=6fe693a80e) | Aug 05, 2021 |
| HP            | ProBook 6465b               | [73822c2796](https://linux-hardware.org/?probe=73822c2796) | Aug 05, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0291d9e90b](https://linux-hardware.org/?probe=0291d9e90b) | Aug 05, 2021 |
| Gateway       | NE56R                       | [9e422aada7](https://linux-hardware.org/?probe=9e422aada7) | Aug 05, 2021 |
| Lenovo        | G460 0677                   | [18dd5bf1b0](https://linux-hardware.org/?probe=18dd5bf1b0) | Aug 05, 2021 |
| Dell          | Inspiron N5110              | [62a2bc2760](https://linux-hardware.org/?probe=62a2bc2760) | Aug 04, 2021 |
| Acer          | Aspire A515-54              | [a1d988707a](https://linux-hardware.org/?probe=a1d988707a) | Aug 04, 2021 |
| Dell          | Inspiron N5110              | [7b3adeea0b](https://linux-hardware.org/?probe=7b3adeea0b) | Aug 04, 2021 |
| OEM           | I41SI                       | [949fab8463](https://linux-hardware.org/?probe=949fab8463) | Aug 04, 2021 |
| Acer          | Aspire A515-54              | [f1c771a10e](https://linux-hardware.org/?probe=f1c771a10e) | Aug 04, 2021 |
| Dell          | Latitude 3410               | [b90142817a](https://linux-hardware.org/?probe=b90142817a) | Aug 04, 2021 |
| Dell          | G5 5590                     | [946f31a6ac](https://linux-hardware.org/?probe=946f31a6ac) | Aug 04, 2021 |
| Gateway       | NE56R                       | [8ff4c3c2e2](https://linux-hardware.org/?probe=8ff4c3c2e2) | Aug 04, 2021 |
| Gateway       | NE56R                       | [410babdbe5](https://linux-hardware.org/?probe=410babdbe5) | Aug 04, 2021 |
| Dell          | Vostro 3400                 | [575772d086](https://linux-hardware.org/?probe=575772d086) | Aug 04, 2021 |
| Dell          | Vostro 3400                 | [cf87b58d05](https://linux-hardware.org/?probe=cf87b58d05) | Aug 04, 2021 |
| ASUSTek       | X510UR                      | [8e08727583](https://linux-hardware.org/?probe=8e08727583) | Aug 03, 2021 |
| Samsung       | RV415                       | [941435e9c5](https://linux-hardware.org/?probe=941435e9c5) | Aug 03, 2021 |
| Lenovo        | ThinkPad T460 20FN002VUS    | [7e1580d21a](https://linux-hardware.org/?probe=7e1580d21a) | Aug 03, 2021 |
| Dell          | Inspiron 5301               | [2387a6a66c](https://linux-hardware.org/?probe=2387a6a66c) | Aug 03, 2021 |
| HP            | ProBook 4540s               | [42b95781f5](https://linux-hardware.org/?probe=42b95781f5) | Aug 03, 2021 |
| Acer          | Aspire A315-54K             | [9c4ca39872](https://linux-hardware.org/?probe=9c4ca39872) | Aug 03, 2021 |
| Lenovo        | G460 0677                   | [1563cdbde9](https://linux-hardware.org/?probe=1563cdbde9) | Aug 02, 2021 |
| HP            | EliteBook 840 G3            | [8c090ed819](https://linux-hardware.org/?probe=8c090ed819) | Aug 02, 2021 |
| HP            | Pavilion g4                 | [8db8c40052](https://linux-hardware.org/?probe=8db8c40052) | Aug 02, 2021 |
| HP            | EliteBook 840 G3            | [db33a4a9ff](https://linux-hardware.org/?probe=db33a4a9ff) | Aug 02, 2021 |
| Unknown       | Unknown                     | [e24e46e21d](https://linux-hardware.org/?probe=e24e46e21d) | Aug 02, 2021 |
| Acer          | Aspire A315-41G             | [24a1d5180b](https://linux-hardware.org/?probe=24a1d5180b) | Aug 02, 2021 |
| Acer          | Nitro AN515-54              | [f46595224c](https://linux-hardware.org/?probe=f46595224c) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Dell          | Inspiron 3584               | [e05a37c968](https://linux-hardware.org/?probe=e05a37c968) | Aug 02, 2021 |
| Positivo      | W540EU                      | [9b2fe3c683](https://linux-hardware.org/?probe=9b2fe3c683) | Aug 02, 2021 |
| Acer          | Nitro AN515-51              | [a31f6e35a8](https://linux-hardware.org/?probe=a31f6e35a8) | Aug 02, 2021 |
| Samsung       | 800G5M/800G5W               | [72323e95ac](https://linux-hardware.org/?probe=72323e95ac) | Aug 01, 2021 |
| Digibras      | NH4CU53                     | [9c3d346f18](https://linux-hardware.org/?probe=9c3d346f18) | Aug 01, 2021 |
| Dell          | Inspiron 3421               | [b91e9c9b04](https://linux-hardware.org/?probe=b91e9c9b04) | Aug 01, 2021 |
| Acer          | Nitro AN515-43              | [41f3382476](https://linux-hardware.org/?probe=41f3382476) | Aug 01, 2021 |
| Acer          | Nitro AN515-43              | [a84b8b8484](https://linux-hardware.org/?probe=a84b8b8484) | Aug 01, 2021 |
| Acer          | Nitro AN515-54              | [80dfa52021](https://linux-hardware.org/?probe=80dfa52021) | Aug 01, 2021 |
| Acer          | Aspire A515-51              | [986d2d52fe](https://linux-hardware.org/?probe=986d2d52fe) | Aug 01, 2021 |
| Acer          | Aspire A315-54K             | [494562b622](https://linux-hardware.org/?probe=494562b622) | Aug 01, 2021 |
| Acer          | Aspire A515-54G             | [8431041495](https://linux-hardware.org/?probe=8431041495) | Aug 01, 2021 |
| Acer          | Aspire A515-54G             | [8218aa8198](https://linux-hardware.org/?probe=8218aa8198) | Aug 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e88f8edeb9](https://linux-hardware.org/?probe=e88f8edeb9) | Jul 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e5e3591da2](https://linux-hardware.org/?probe=e5e3591da2) | Jul 31, 2021 |
| Dell          | Inspiron 5458               | [bd589490df](https://linux-hardware.org/?probe=bd589490df) | Jul 31, 2021 |
| Dell          | Inspiron 5547               | [5956d016c4](https://linux-hardware.org/?probe=5956d016c4) | Jul 31, 2021 |
| Samsung       | 270E5J/2570EJ               | [f9ae9a1b3e](https://linux-hardware.org/?probe=f9ae9a1b3e) | Jul 30, 2021 |
| Lenovo        | G400s VILG1                 | [48553f1ff1](https://linux-hardware.org/?probe=48553f1ff1) | Jul 30, 2021 |
| Sony          | VGN-FW190E                  | [76c6658153](https://linux-hardware.org/?probe=76c6658153) | Jul 30, 2021 |
| Sony          | VPCEH30EB                   | [ec33405baf](https://linux-hardware.org/?probe=ec33405baf) | Jul 30, 2021 |
| Acer          | Nitro AN515-54              | [f70d19b81f](https://linux-hardware.org/?probe=f70d19b81f) | Jul 30, 2021 |
| HP            | ProBook 6460b               | [7d52bd3983](https://linux-hardware.org/?probe=7d52bd3983) | Jul 30, 2021 |
| HP            | 250 G7 Notebook PC          | [d5c1760f1e](https://linux-hardware.org/?probe=d5c1760f1e) | Jul 30, 2021 |
| Acer          | Aspire F5-573               | [8ca138437d](https://linux-hardware.org/?probe=8ca138437d) | Jul 30, 2021 |
| Alienware     | 17 R2                       | [897bcbbe33](https://linux-hardware.org/?probe=897bcbbe33) | Jul 30, 2021 |
| Acer          | Nitro AN515-54              | [1978fa6aeb](https://linux-hardware.org/?probe=1978fa6aeb) | Jul 30, 2021 |
| Digibras      | NH4CU03                     | [3b8fda5c89](https://linux-hardware.org/?probe=3b8fda5c89) | Jul 30, 2021 |
| Acer          | Nitro AN515-54              | [bd29363ad5](https://linux-hardware.org/?probe=bd29363ad5) | Jul 29, 2021 |
| Acer          | Nitro AN515-54              | [eace9bc218](https://linux-hardware.org/?probe=eace9bc218) | Jul 29, 2021 |
| Dell          | Inspiron 3583               | [ac429960eb](https://linux-hardware.org/?probe=ac429960eb) | Jul 29, 2021 |
| Acer          | Aspire F5-573               | [b9659974d6](https://linux-hardware.org/?probe=b9659974d6) | Jul 29, 2021 |
| Dell          | Inspiron 5402               | [88a300abb6](https://linux-hardware.org/?probe=88a300abb6) | Jul 29, 2021 |
| Acer          | Nitro AN515-55              | [43b20b25c7](https://linux-hardware.org/?probe=43b20b25c7) | Jul 29, 2021 |
| Acer          | Nitro AN515-55              | [40bb3424a8](https://linux-hardware.org/?probe=40bb3424a8) | Jul 29, 2021 |
| Acer          | Aspire E5-574               | [cfe7be64c7](https://linux-hardware.org/?probe=cfe7be64c7) | Jul 29, 2021 |
| Samsung       | 550XCJ/550XCR               | [334e198807](https://linux-hardware.org/?probe=334e198807) | Jul 29, 2021 |
| Acer          | Aspire 5742                 | [cc4e3c3712](https://linux-hardware.org/?probe=cc4e3c3712) | Jul 28, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [09419fd70a](https://linux-hardware.org/?probe=09419fd70a) | Jul 28, 2021 |
| Acer          | Aspire A515-52G             | [46e28144ec](https://linux-hardware.org/?probe=46e28144ec) | Jul 28, 2021 |
| Positivo      | S14BW01                     | [2c773d0a85](https://linux-hardware.org/?probe=2c773d0a85) | Jul 28, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [a1e01af796](https://linux-hardware.org/?probe=a1e01af796) | Jul 28, 2021 |
| Positivo      | H14BT58                     | [4bd1d4c963](https://linux-hardware.org/?probe=4bd1d4c963) | Jul 28, 2021 |
| Acer          | Nitro AN515-52              | [68e8608d11](https://linux-hardware.org/?probe=68e8608d11) | Jul 28, 2021 |
| Digibras      | NH4CU03                     | [29e30b2f47](https://linux-hardware.org/?probe=29e30b2f47) | Jul 28, 2021 |
| Acer          | Nitro AN515-55              | [6355762450](https://linux-hardware.org/?probe=6355762450) | Jul 28, 2021 |
| Acer          | Nitro AN515-55              | [d83b05ee2d](https://linux-hardware.org/?probe=d83b05ee2d) | Jul 28, 2021 |
| ASUSTek       | Z450UAK                     | [4e15167795](https://linux-hardware.org/?probe=4e15167795) | Jul 28, 2021 |
| Dell          | Inspiron N4050              | [8445a26a9a](https://linux-hardware.org/?probe=8445a26a9a) | Jul 28, 2021 |
| Clevo         | M720R                       | [a52f0f2d7c](https://linux-hardware.org/?probe=a52f0f2d7c) | Jul 27, 2021 |
| Positivo      | MOBILE                      | [f73fc27d4a](https://linux-hardware.org/?probe=f73fc27d4a) | Jul 27, 2021 |
| Positivo      | CHT12CP                     | [85ff7d5708](https://linux-hardware.org/?probe=85ff7d5708) | Jul 27, 2021 |
| Sony          | SVE15125CBW                 | [75fd5f573d](https://linux-hardware.org/?probe=75fd5f573d) | Jul 27, 2021 |
| ASUSTek       | G73Jh                       | [e7af78fad2](https://linux-hardware.org/?probe=e7af78fad2) | Jul 26, 2021 |
| Samsung       | QX310/QX410/QX510/SF310/... | [ac0d1596c6](https://linux-hardware.org/?probe=ac0d1596c6) | Jul 26, 2021 |
| Dell          | Precision 5540              | [82e2f9c381](https://linux-hardware.org/?probe=82e2f9c381) | Jul 26, 2021 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | [000f7a827b](https://linux-hardware.org/?probe=000f7a827b) | Jul 26, 2021 |
| Positivo      | MOBILE                      | [e5b8b3d91a](https://linux-hardware.org/?probe=e5b8b3d91a) | Jul 26, 2021 |
| Dell          | Inspiron 1545               | [74149faa68](https://linux-hardware.org/?probe=74149faa68) | Jul 26, 2021 |
| Dell          | Inspiron 1545               | [519d8ddd2b](https://linux-hardware.org/?probe=519d8ddd2b) | Jul 26, 2021 |
| Acer          | Aspire ES1-411              | [ead7fa07f8](https://linux-hardware.org/?probe=ead7fa07f8) | Jul 26, 2021 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [75a01751c3](https://linux-hardware.org/?probe=75a01751c3) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | [561ec14e6b](https://linux-hardware.org/?probe=561ec14e6b) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | [068e66bfae](https://linux-hardware.org/?probe=068e66bfae) | Jul 25, 2021 |
| Dell          | System XPS L502X            | [5b8b12ee95](https://linux-hardware.org/?probe=5b8b12ee95) | Jul 25, 2021 |
| Acer          | Aspire A315-42G             | [bfb12f37c8](https://linux-hardware.org/?probe=bfb12f37c8) | Jul 25, 2021 |
| Dell          | System XPS L502X            | [c0068476a5](https://linux-hardware.org/?probe=c0068476a5) | Jul 25, 2021 |
| Intel         | W7645                       | [8465fa1bd1](https://linux-hardware.org/?probe=8465fa1bd1) | Jul 25, 2021 |
| Dell          | Latitude E7440              | [d07ef29ea4](https://linux-hardware.org/?probe=d07ef29ea4) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| Samsung       | RF511/RF411/RF711           | [42762c8986](https://linux-hardware.org/?probe=42762c8986) | Jul 25, 2021 |
| Samsung       | RF511/RF411/RF711           | [b5d92e9f80](https://linux-hardware.org/?probe=b5d92e9f80) | Jul 25, 2021 |
| Digibras      | NH4CU03                     | [9c841f3605](https://linux-hardware.org/?probe=9c841f3605) | Jul 24, 2021 |
| HP            | ProBook 6465b               | [c510c740d4](https://linux-hardware.org/?probe=c510c740d4) | Jul 24, 2021 |
| Multilaser    | PC024                       | [2e48bf495b](https://linux-hardware.org/?probe=2e48bf495b) | Jul 24, 2021 |
| Dell          | Vostro 5470                 | [dd78839cfd](https://linux-hardware.org/?probe=dd78839cfd) | Jul 24, 2021 |
| Dell          | Inspiron 3583               | [46f1655ef9](https://linux-hardware.org/?probe=46f1655ef9) | Jul 24, 2021 |
| Digibras      | US41II1                     | [d754670ad9](https://linux-hardware.org/?probe=d754670ad9) | Jul 23, 2021 |
| Multilaser    | PC024                       | [d079b16a02](https://linux-hardware.org/?probe=d079b16a02) | Jul 23, 2021 |
| Dell          | Inspiron 7560               | [3cc56271ad](https://linux-hardware.org/?probe=3cc56271ad) | Jul 23, 2021 |
| Compaq        | Presario CQ-17              | [5635d81ecf](https://linux-hardware.org/?probe=5635d81ecf) | Jul 23, 2021 |
| Compaq        | Presario CQ-17              | [1b96ec0a4d](https://linux-hardware.org/?probe=1b96ec0a4d) | Jul 23, 2021 |
| Dell          | Inspiron 7560               | [46032a26c5](https://linux-hardware.org/?probe=46032a26c5) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2640930f28](https://linux-hardware.org/?probe=2640930f28) | Jul 23, 2021 |
| Dell          | Inspiron N4010              | [e1c1df1682](https://linux-hardware.org/?probe=e1c1df1682) | Jul 23, 2021 |
| Acer          | Aspire A315-34              | [69ef9cdbb5](https://linux-hardware.org/?probe=69ef9cdbb5) | Jul 23, 2021 |
| Acer          | Aspire A315-34              | [8f2809e187](https://linux-hardware.org/?probe=8f2809e187) | Jul 22, 2021 |
| Toshiba       | Satellite S55t-B            | [6f1ca4c9fd](https://linux-hardware.org/?probe=6f1ca4c9fd) | Jul 22, 2021 |
| Dell          | Latitude E5500              | [36da1c5256](https://linux-hardware.org/?probe=36da1c5256) | Jul 22, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [022685129b](https://linux-hardware.org/?probe=022685129b) | Jul 22, 2021 |
| Positivo      | C41TB                       | [fa578942bc](https://linux-hardware.org/?probe=fa578942bc) | Jul 22, 2021 |
| Sony          | VPCEH30EB                   | [cac0bb6997](https://linux-hardware.org/?probe=cac0bb6997) | Jul 22, 2021 |
| Acer          | Predator PH315-52           | [a3fc6e5400](https://linux-hardware.org/?probe=a3fc6e5400) | Jul 22, 2021 |
| Dell          | Latitude 5410               | [cb463b1fc3](https://linux-hardware.org/?probe=cb463b1fc3) | Jul 22, 2021 |
| Dell          | Latitude 3410               | [4446f22eb0](https://linux-hardware.org/?probe=4446f22eb0) | Jul 22, 2021 |
| Dell          | Inspiron N4030              | [e4d4d87612](https://linux-hardware.org/?probe=e4d4d87612) | Jul 22, 2021 |
| Dell          | Latitude 3410               | [15a8bcf96d](https://linux-hardware.org/?probe=15a8bcf96d) | Jul 21, 2021 |
| Dell          | Latitude 3410               | [4058065b38](https://linux-hardware.org/?probe=4058065b38) | Jul 21, 2021 |
| Dell          | Inspiron 7572               | [0b2a96b6d7](https://linux-hardware.org/?probe=0b2a96b6d7) | Jul 21, 2021 |
| ASUSTek       | K84C                        | [3c199f4247](https://linux-hardware.org/?probe=3c199f4247) | Jul 21, 2021 |
| OEM           | I41SI                       | [ee7129e197](https://linux-hardware.org/?probe=ee7129e197) | Jul 21, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [e8094ccb5e](https://linux-hardware.org/?probe=e8094ccb5e) | Jul 20, 2021 |
| ASUSTek       | K46CM                       | [0940de0aa3](https://linux-hardware.org/?probe=0940de0aa3) | Jul 20, 2021 |
| Dell          | Inspiron N5110              | [e2b2f0f7b9](https://linux-hardware.org/?probe=e2b2f0f7b9) | Jul 20, 2021 |
| Acer          | Aspire A315-41              | [09872beb4e](https://linux-hardware.org/?probe=09872beb4e) | Jul 20, 2021 |
| HP            | Pavilion dv6500             | [e4aa7493f2](https://linux-hardware.org/?probe=e4aa7493f2) | Jul 19, 2021 |
| ASUSTek       | X510UR                      | [deab3977f1](https://linux-hardware.org/?probe=deab3977f1) | Jul 19, 2021 |
| ASUSTek       | X510UR                      | [ded2c79fd6](https://linux-hardware.org/?probe=ded2c79fd6) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8fc400a46a](https://linux-hardware.org/?probe=8fc400a46a) | Jul 18, 2021 |
| Acer          | Aspire A315-54K             | [10eac9e8d2](https://linux-hardware.org/?probe=10eac9e8d2) | Jul 18, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [9b9629e155](https://linux-hardware.org/?probe=9b9629e155) | Jul 18, 2021 |
| Dell          | Vostro 3560                 | [68d21d8f50](https://linux-hardware.org/?probe=68d21d8f50) | Jul 18, 2021 |
| Lenovo        | ThinkPad X270 20HNA003CD    | [51faf0c18d](https://linux-hardware.org/?probe=51faf0c18d) | Jul 18, 2021 |
| Dell          | Latitude E6330              | [1495c91445](https://linux-hardware.org/?probe=1495c91445) | Jul 18, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [198a7eece4](https://linux-hardware.org/?probe=198a7eece4) | Jul 18, 2021 |
| LG Electro... | S425-G.BC34P1               | [3b7ad3360a](https://linux-hardware.org/?probe=3b7ad3360a) | Jul 18, 2021 |
| Google        | Kip                         | [4239289cf3](https://linux-hardware.org/?probe=4239289cf3) | Jul 17, 2021 |
| Notebook      | W35xSTQ_370ST               | [b6e8dea799](https://linux-hardware.org/?probe=b6e8dea799) | Jul 17, 2021 |
| Acer          | Aspire A315-53              | [734ffe5fc6](https://linux-hardware.org/?probe=734ffe5fc6) | Jul 17, 2021 |
| ASUSTek       | K45VM                       | [916d9c7dfe](https://linux-hardware.org/?probe=916d9c7dfe) | Jul 17, 2021 |
| Avell High... | A62 LIV                     | [a1398c199a](https://linux-hardware.org/?probe=a1398c199a) | Jul 17, 2021 |
| Avell High... | A62 LIV                     | [2e01a9aa5b](https://linux-hardware.org/?probe=2e01a9aa5b) | Jul 17, 2021 |
| Dell          | G3 3500                     | [12e1eb1ce7](https://linux-hardware.org/?probe=12e1eb1ce7) | Jul 17, 2021 |
| Itautec       | Infoway w7430               | [47b6a65565](https://linux-hardware.org/?probe=47b6a65565) | Jul 17, 2021 |
| Dell          | Inspiron N5110              | [bc346613d6](https://linux-hardware.org/?probe=bc346613d6) | Jul 16, 2021 |
| Philco        | 14I                         | [97af09cd5c](https://linux-hardware.org/?probe=97af09cd5c) | Jul 16, 2021 |
| Dell          | Inspiron N5110              | [ebd4b8cec5](https://linux-hardware.org/?probe=ebd4b8cec5) | Jul 16, 2021 |
| Sony          | SVE15111EBS                 | [65df293d03](https://linux-hardware.org/?probe=65df293d03) | Jul 16, 2021 |
| Unknown       | Unknown                     | [a24da0bb81](https://linux-hardware.org/?probe=a24da0bb81) | Jul 16, 2021 |
| Dell          | Inspiron N5110              | [cd4e9e008d](https://linux-hardware.org/?probe=cd4e9e008d) | Jul 16, 2021 |
| Positivo      | CHT12CP                     | [f339240754](https://linux-hardware.org/?probe=f339240754) | Jul 15, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [3c3dba14b5](https://linux-hardware.org/?probe=3c3dba14b5) | Jul 15, 2021 |
| Toshiba       | K201                        | [85abf16ca0](https://linux-hardware.org/?probe=85abf16ca0) | Jul 15, 2021 |
| Samsung       | 800G5H/800G5S               | [43c5271ff4](https://linux-hardware.org/?probe=43c5271ff4) | Jul 15, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [327a33843c](https://linux-hardware.org/?probe=327a33843c) | Jul 15, 2021 |
| Dell          | Latitude E6420              | [e2e96ce9d8](https://linux-hardware.org/?probe=e2e96ce9d8) | Jul 14, 2021 |
| Intel         | W7645                       | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E14 20RBS7WC00     | [4d34393d9f](https://linux-hardware.org/?probe=4d34393d9f) | Jul 14, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| Unknown       | Unknown                     | [832a7cbb12](https://linux-hardware.org/?probe=832a7cbb12) | Jul 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d3a3591561](https://linux-hardware.org/?probe=d3a3591561) | Jul 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f4d511f3fa](https://linux-hardware.org/?probe=f4d511f3fa) | Jul 14, 2021 |
| Teclast       | TbooK 10 S                  | [096daaa093](https://linux-hardware.org/?probe=096daaa093) | Jul 14, 2021 |
| Acer          | Nitro AN515-54              | [c8642b1182](https://linux-hardware.org/?probe=c8642b1182) | Jul 14, 2021 |
| ASUSTek       | X450LCP                     | [3c6fb338b5](https://linux-hardware.org/?probe=3c6fb338b5) | Jul 13, 2021 |
| Lenovo        | ThinkPad E14 20RB002UBR     | [e4dc8e2dbc](https://linux-hardware.org/?probe=e4dc8e2dbc) | Jul 13, 2021 |
| LG Electro... | Z330-G.BE51P1               | [8c69de9f09](https://linux-hardware.org/?probe=8c69de9f09) | Jul 13, 2021 |
| Dell          | Inspiron 1545               | [e4d655b420](https://linux-hardware.org/?probe=e4d655b420) | Jul 13, 2021 |
| ASUSTek       | S400CA                      | [982b30ab33](https://linux-hardware.org/?probe=982b30ab33) | Jul 13, 2021 |
| Acer          | Nitro AN515-51              | [130fff31f2](https://linux-hardware.org/?probe=130fff31f2) | Jul 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [81a878aea5](https://linux-hardware.org/?probe=81a878aea5) | Jul 12, 2021 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [afedd27cb5](https://linux-hardware.org/?probe=afedd27cb5) | Jul 12, 2021 |
| HP            | ENVY 17                     | [9530254987](https://linux-hardware.org/?probe=9530254987) | Jul 12, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [cd32be6d20](https://linux-hardware.org/?probe=cd32be6d20) | Jul 12, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [35eef02824](https://linux-hardware.org/?probe=35eef02824) | Jul 11, 2021 |
| Qbex          | UDPAIOQBEX01                | [9b96573429](https://linux-hardware.org/?probe=9b96573429) | Jul 11, 2021 |
| Lenovo        | G460e 1049                  | [444c0fb58d](https://linux-hardware.org/?probe=444c0fb58d) | Jul 11, 2021 |
| Megaware      | W240BU                      | [8144e0b1ed](https://linux-hardware.org/?probe=8144e0b1ed) | Jul 11, 2021 |
| Lenovo        | G460e 1049                  | [89b02002a5](https://linux-hardware.org/?probe=89b02002a5) | Jul 11, 2021 |
| Samsung       | 300E5K/300E5Q               | [1c4febdfb6](https://linux-hardware.org/?probe=1c4febdfb6) | Jul 11, 2021 |
| ASUSTek       | X550EA                      | [197d3df7ef](https://linux-hardware.org/?probe=197d3df7ef) | Jul 11, 2021 |
| Dell          | Inspiron 7520               | [c48b21407b](https://linux-hardware.org/?probe=c48b21407b) | Jul 11, 2021 |
| Intel Clie... | A60 MUV                     | [f2c8c49a38](https://linux-hardware.org/?probe=f2c8c49a38) | Jul 11, 2021 |
| Dell          | Vostro 3500                 | [ff5e8e2016](https://linux-hardware.org/?probe=ff5e8e2016) | Jul 10, 2021 |
| Gateway       | NE56R                       | [94fe19c4ee](https://linux-hardware.org/?probe=94fe19c4ee) | Jul 10, 2021 |
| ASUSTek       | K84C                        | [42cc44efde](https://linux-hardware.org/?probe=42cc44efde) | Jul 10, 2021 |
| Dell          | XPS 15 9560                 | [83250f42ef](https://linux-hardware.org/?probe=83250f42ef) | Jul 09, 2021 |
| Dell          | Vostro 5470                 | [aff224171e](https://linux-hardware.org/?probe=aff224171e) | Jul 09, 2021 |
| Itautec       | Infoway                     | [93a997fc2d](https://linux-hardware.org/?probe=93a997fc2d) | Jul 09, 2021 |
| Toshiba       | IS 1412                     | [b293f94839](https://linux-hardware.org/?probe=b293f94839) | Jul 09, 2021 |
| Acer          | Aspire E5-571               | [aa752be0c2](https://linux-hardware.org/?probe=aa752be0c2) | Jul 09, 2021 |
| Lenovo        | ThinkPad T450 20BUS41100    | [039b1c7dcb](https://linux-hardware.org/?probe=039b1c7dcb) | Jul 09, 2021 |
| Lenovo        | ThinkPad T450 20BUS41100    | [720670f2fe](https://linux-hardware.org/?probe=720670f2fe) | Jul 09, 2021 |
| Acer          | Aspire A515-54G             | [e7561debf6](https://linux-hardware.org/?probe=e7561debf6) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [cca31087c0](https://linux-hardware.org/?probe=cca31087c0) | Jul 08, 2021 |
| Dell          | Inspiron 7472               | [6f6b7cbdf5](https://linux-hardware.org/?probe=6f6b7cbdf5) | Jul 08, 2021 |
| Acer          | Nitro AN517-51              | [20e31ad5b3](https://linux-hardware.org/?probe=20e31ad5b3) | Jul 08, 2021 |
| Acer          | Nitro AN517-51              | [90e68f86cf](https://linux-hardware.org/?probe=90e68f86cf) | Jul 08, 2021 |
| Dell          | Latitude E6420              | [4facd06f69](https://linux-hardware.org/?probe=4facd06f69) | Jul 08, 2021 |
| Acer          | Aspire 4745Z                | [1fb1281214](https://linux-hardware.org/?probe=1fb1281214) | Jul 08, 2021 |
| Dell          | Inspiron 3421               | [3731513550](https://linux-hardware.org/?probe=3731513550) | Jul 08, 2021 |
| Dell          | Inspiron 3421               | [38c7582eb5](https://linux-hardware.org/?probe=38c7582eb5) | Jul 08, 2021 |
| Toshiba       | IS 1412                     | [dca13f88c7](https://linux-hardware.org/?probe=dca13f88c7) | Jul 08, 2021 |
| Samsung       | 300E5M/300E5L               | [26b85ebbce](https://linux-hardware.org/?probe=26b85ebbce) | Jul 07, 2021 |
| Acer          | Nitro AN515-54              | [4b3c9afde7](https://linux-hardware.org/?probe=4b3c9afde7) | Jul 07, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [c431ee437b](https://linux-hardware.org/?probe=c431ee437b) | Jul 07, 2021 |
| Standard      | AHV                         | [b2c72bc162](https://linux-hardware.org/?probe=b2c72bc162) | Jul 07, 2021 |
| Dell          | Vostro 3460                 | [d24bfb0cba](https://linux-hardware.org/?probe=d24bfb0cba) | Jul 07, 2021 |
| Acer          | Aspire E5-574               | [72aa4529ca](https://linux-hardware.org/?probe=72aa4529ca) | Jul 07, 2021 |
| Acer          | Aspire E5-574               | [8360c2bcdc](https://linux-hardware.org/?probe=8360c2bcdc) | Jul 07, 2021 |
| Sony          | VPCSB25FB                   | [6de928a758](https://linux-hardware.org/?probe=6de928a758) | Jul 07, 2021 |
| Acer          | Aspire 4736Z                | [efefc68616](https://linux-hardware.org/?probe=efefc68616) | Jul 07, 2021 |
| Acer          | Nitro AN515-52              | [8f6373fbf1](https://linux-hardware.org/?probe=8f6373fbf1) | Jul 07, 2021 |
| Acer          | Aspire 4745Z                | [c0534127fe](https://linux-hardware.org/?probe=c0534127fe) | Jul 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8e3d43d0c9](https://linux-hardware.org/?probe=8e3d43d0c9) | Jul 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [307428e41c](https://linux-hardware.org/?probe=307428e41c) | Jul 07, 2021 |
| Lenovo        | IdeaPad Z470                | [dd85c4e64c](https://linux-hardware.org/?probe=dd85c4e64c) | Jul 06, 2021 |
| Intel         | HuronRiver Platform         | [bcb40b4146](https://linux-hardware.org/?probe=bcb40b4146) | Jul 06, 2021 |
| Dell          | Latitude 5490               | [baf09f99e3](https://linux-hardware.org/?probe=baf09f99e3) | Jul 06, 2021 |
| Acer          | Aspire A515-54G             | [4a19b59c46](https://linux-hardware.org/?probe=4a19b59c46) | Jul 06, 2021 |
| Toshiba       | IS 1412                     | [914f5ee7dd](https://linux-hardware.org/?probe=914f5ee7dd) | Jul 06, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [273cea91c3](https://linux-hardware.org/?probe=273cea91c3) | Jul 06, 2021 |
| Acer          | V5-171                      | [1000a5aa83](https://linux-hardware.org/?probe=1000a5aa83) | Jul 06, 2021 |
| ASUSTek       | 1015PE                      | [051265df6e](https://linux-hardware.org/?probe=051265df6e) | Jul 05, 2021 |
| Acer          | AOD270                      | [c829f9921a](https://linux-hardware.org/?probe=c829f9921a) | Jul 05, 2021 |
| Acer          | Aspire 1410                 | [57c8c863ae](https://linux-hardware.org/?probe=57c8c863ae) | Jul 05, 2021 |
| Acer          | Aspire 1410                 | [59a3f54dc6](https://linux-hardware.org/?probe=59a3f54dc6) | Jul 05, 2021 |
| Acer          | Predator PH315-52           | [9768281e5c](https://linux-hardware.org/?probe=9768281e5c) | Jul 05, 2021 |
| Acer          | Predator PH315-52           | [e5b46dfbae](https://linux-hardware.org/?probe=e5b46dfbae) | Jul 05, 2021 |
| Acer          | Aspire A515-54G             | [f926fbd545](https://linux-hardware.org/?probe=f926fbd545) | Jul 04, 2021 |
| Login Info... | LOG-QAL30                   | [3376c8f541](https://linux-hardware.org/?probe=3376c8f541) | Jul 04, 2021 |
| HP            | ProBook 6465b               | [dd03f5f10c](https://linux-hardware.org/?probe=dd03f5f10c) | Jul 04, 2021 |
| HP            | ProBook 6465b               | [27a6794579](https://linux-hardware.org/?probe=27a6794579) | Jul 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f2d67e7bde](https://linux-hardware.org/?probe=f2d67e7bde) | Jul 04, 2021 |
| Lenovo        | IdeaPad Z470                | [97f380d55e](https://linux-hardware.org/?probe=97f380d55e) | Jul 04, 2021 |
| Acer          | Aspire A515-51              | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| Acer          | Aspire A515-41G             | [a16bbe7db7](https://linux-hardware.org/?probe=a16bbe7db7) | Jul 03, 2021 |
| Acer          | Aspire A515-41G             | [ce5d5b0086](https://linux-hardware.org/?probe=ce5d5b0086) | Jul 03, 2021 |
| Acer          | AO722                       | [3f8c0961a3](https://linux-hardware.org/?probe=3f8c0961a3) | Jul 03, 2021 |
| Lenovo        | B40-70 80F3000CBR           | [1c25814a0d](https://linux-hardware.org/?probe=1c25814a0d) | Jul 03, 2021 |
| Lenovo        | B40-70 80F3000CBR           | [88b35fd418](https://linux-hardware.org/?probe=88b35fd418) | Jul 03, 2021 |
| Acer          | Nitro AN515-54              | [3be93cbc0c](https://linux-hardware.org/?probe=3be93cbc0c) | Jul 03, 2021 |
| Dell          | Latitude 3440               | [2488842dfc](https://linux-hardware.org/?probe=2488842dfc) | Jul 03, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [e735a4421a](https://linux-hardware.org/?probe=e735a4421a) | Jul 02, 2021 |
| Positivo      | EC10IS1                     | [56138bf27a](https://linux-hardware.org/?probe=56138bf27a) | Jul 02, 2021 |
| Acer          | Predator PH315-52           | [a69b63dc2b](https://linux-hardware.org/?probe=a69b63dc2b) | Jul 02, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [a6415f17f7](https://linux-hardware.org/?probe=a6415f17f7) | Jul 02, 2021 |
| Avell High... | A75 RTX MUV/ G1575 RTX M... | [1d31a2326c](https://linux-hardware.org/?probe=1d31a2326c) | Jul 02, 2021 |
| Gateway       | NE56R                       | [06b945a761](https://linux-hardware.org/?probe=06b945a761) | Jul 02, 2021 |
| Sony          | VGN-FE880E                  | [920adf56ec](https://linux-hardware.org/?probe=920adf56ec) | Jul 02, 2021 |
| Sony          | VGN-FE880E                  | [6ae2ef9b19](https://linux-hardware.org/?probe=6ae2ef9b19) | Jul 02, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [dfb688fc60](https://linux-hardware.org/?probe=dfb688fc60) | Jul 02, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [5fffdfae1d](https://linux-hardware.org/?probe=5fffdfae1d) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Unknown       | Unknown                     | [99c56b3bda](https://linux-hardware.org/?probe=99c56b3bda) | Jul 01, 2021 |
| HP            | Pavilion dv2600             | [6db4e087c0](https://linux-hardware.org/?probe=6db4e087c0) | Jul 01, 2021 |
| Positivo      | S14CT01                     | [a2a7c040a8](https://linux-hardware.org/?probe=a2a7c040a8) | Jul 01, 2021 |
| Positivo      | S14CT01                     | [2988ca2bae](https://linux-hardware.org/?probe=2988ca2bae) | Jul 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002VUS    | [13ca6385ce](https://linux-hardware.org/?probe=13ca6385ce) | Jul 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [a92028f13a](https://linux-hardware.org/?probe=a92028f13a) | Jul 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002VUS    | [fbb0cc180c](https://linux-hardware.org/?probe=fbb0cc180c) | Jul 01, 2021 |
| Acer          | Aspire A515-51              | [6ee9cba880](https://linux-hardware.org/?probe=6ee9cba880) | Jul 01, 2021 |
| Acer          | Aspire A515-51              | [c2eb051f8c](https://linux-hardware.org/?probe=c2eb051f8c) | Jul 01, 2021 |
| Acer          | Aspire E1-471               | [35271c8973](https://linux-hardware.org/?probe=35271c8973) | Jul 01, 2021 |
| Acer          | Aspire E1-471               | [384d51f444](https://linux-hardware.org/?probe=384d51f444) | Jul 01, 2021 |
| HP            | Pavilion g4                 | [552e43c438](https://linux-hardware.org/?probe=552e43c438) | Jun 30, 2021 |
| Acer          | Aspire A315-23G             | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| HP            | Pavilion g4                 | [fa58b1dd24](https://linux-hardware.org/?probe=fa58b1dd24) | Jun 30, 2021 |
| Dell          | Inspiron 7472               | [0624b57fad](https://linux-hardware.org/?probe=0624b57fad) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [937053a530](https://linux-hardware.org/?probe=937053a530) | Jun 30, 2021 |
| HP            | EliteBook 8470p             | [e0e0307e93](https://linux-hardware.org/?probe=e0e0307e93) | Jun 30, 2021 |
| Dell          | Vostro 3560                 | [70106921f8](https://linux-hardware.org/?probe=70106921f8) | Jun 30, 2021 |
| Dell          | Vostro 3560                 | [0ef7327bae](https://linux-hardware.org/?probe=0ef7327bae) | Jun 30, 2021 |
| Dell          | G3 3579                     | [e8247fe520](https://linux-hardware.org/?probe=e8247fe520) | Jun 30, 2021 |
| Positivo      | Smash                       | [78aff01d49](https://linux-hardware.org/?probe=78aff01d49) | Jun 30, 2021 |
| Positivo      | Smash                       | [4b5d1c11ff](https://linux-hardware.org/?probe=4b5d1c11ff) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | [e09b0ac6cf](https://linux-hardware.org/?probe=e09b0ac6cf) | Jun 30, 2021 |
| Acer          | Predator PH315-52           | [fbe99870e9](https://linux-hardware.org/?probe=fbe99870e9) | Jun 29, 2021 |
| HP            | G42                         | [111aa8ff1b](https://linux-hardware.org/?probe=111aa8ff1b) | Jun 29, 2021 |
| Login Info... | LOG-MB47II7                 | [a4a339a28c](https://linux-hardware.org/?probe=a4a339a28c) | Jun 29, 2021 |
| Login Info... | LOG-MB47II7                 | [ad2829b254](https://linux-hardware.org/?probe=ad2829b254) | Jun 29, 2021 |
| Dell          | Inspiron N5110              | [b24be80abf](https://linux-hardware.org/?probe=b24be80abf) | Jun 29, 2021 |
| Dell          | Inspiron 3421               | [1900fb77ec](https://linux-hardware.org/?probe=1900fb77ec) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | [caa1dadc98](https://linux-hardware.org/?probe=caa1dadc98) | Jun 29, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [67e302d5d5](https://linux-hardware.org/?probe=67e302d5d5) | Jun 29, 2021 |
| Acer          | Aspire E5-473               | [4ee1cfe01b](https://linux-hardware.org/?probe=4ee1cfe01b) | Jun 28, 2021 |
| Acer          | Nitro AN515-54              | [42e31b505d](https://linux-hardware.org/?probe=42e31b505d) | Jun 28, 2021 |
| Samsung       | RV415/RV515                 | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| Samsung       | 300E5K/300E5Q               | [ae7eded1e1](https://linux-hardware.org/?probe=ae7eded1e1) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| Dell          | Vostro 1000                 | [9230a6f1a1](https://linux-hardware.org/?probe=9230a6f1a1) | Jun 28, 2021 |
| Acer          | Nitro AN515-54              | [db60dbc891](https://linux-hardware.org/?probe=db60dbc891) | Jun 27, 2021 |
| Philco        | 14I                         | [6d8ccae707](https://linux-hardware.org/?probe=6d8ccae707) | Jun 27, 2021 |
| Multilaser    | PC301                       | [55b685927b](https://linux-hardware.org/?probe=55b685927b) | Jun 27, 2021 |
| Lenovo        | ThinkPad X100e 28762FP      | [95661d2e39](https://linux-hardware.org/?probe=95661d2e39) | Jun 27, 2021 |
| Acer          | Aspire 3000                 | [d0c68c57a8](https://linux-hardware.org/?probe=d0c68c57a8) | Jun 26, 2021 |
| ASUSTek       | 1005HA                      | [e3bbe8cc57](https://linux-hardware.org/?probe=e3bbe8cc57) | Jun 26, 2021 |
| Positivo      | CHT14B                      | [4fd6be9b48](https://linux-hardware.org/?probe=4fd6be9b48) | Jun 26, 2021 |
| HP            | Pavilion dv6                | [44c09f0096](https://linux-hardware.org/?probe=44c09f0096) | Jun 26, 2021 |
| Dell          | Inspiron 1545               | [0f2110892b](https://linux-hardware.org/?probe=0f2110892b) | Jun 26, 2021 |
| ASUSTek       | X510URR                     | [980f6dda35](https://linux-hardware.org/?probe=980f6dda35) | Jun 25, 2021 |
| Acer          | Nitro AN517-51              | [91a3c1eeed](https://linux-hardware.org/?probe=91a3c1eeed) | Jun 25, 2021 |
| Dell          | Inspiron 3583               | [bc81dcf649](https://linux-hardware.org/?probe=bc81dcf649) | Jun 25, 2021 |
| Dell          | Vostro 5490                 | [60568dfa0d](https://linux-hardware.org/?probe=60568dfa0d) | Jun 25, 2021 |
| Acer          | Aspire E1-572P              | [b6b916afd7](https://linux-hardware.org/?probe=b6b916afd7) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7b98c8285d](https://linux-hardware.org/?probe=7b98c8285d) | Jun 24, 2021 |
| Acer          | Nitro AN515-54              | [2d9860375c](https://linux-hardware.org/?probe=2d9860375c) | Jun 24, 2021 |
| Acer          | Nitro AN515-54              | [9d6c6de501](https://linux-hardware.org/?probe=9d6c6de501) | Jun 24, 2021 |
| Acer          | Predator G9-793             | [6004b8b462](https://linux-hardware.org/?probe=6004b8b462) | Jun 24, 2021 |
| Dell          | Inspiron N7110              | [e58da0d3ca](https://linux-hardware.org/?probe=e58da0d3ca) | Jun 23, 2021 |
| ASUSTek       | GL553VD                     | [34990aa49f](https://linux-hardware.org/?probe=34990aa49f) | Jun 23, 2021 |
| Acer          | Nitro AN517-51              | [22656657b7](https://linux-hardware.org/?probe=22656657b7) | Jun 23, 2021 |
| Acer          | Aspire A515-54G             | [a655a71d5e](https://linux-hardware.org/?probe=a655a71d5e) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | [6a9946fc87](https://linux-hardware.org/?probe=6a9946fc87) | Jun 23, 2021 |
| Acer          | Nitro AN515-54              | [e3cd8efc89](https://linux-hardware.org/?probe=e3cd8efc89) | Jun 23, 2021 |
| Acer          | Aspire 5742G                | [d48812cf75](https://linux-hardware.org/?probe=d48812cf75) | Jun 23, 2021 |
| Acer          | Aspire 5742G                | [50ba6ab503](https://linux-hardware.org/?probe=50ba6ab503) | Jun 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [598de53955](https://linux-hardware.org/?probe=598de53955) | Jun 23, 2021 |
| Acer          | Aspire A515-54G             | [bda57ce6d5](https://linux-hardware.org/?probe=bda57ce6d5) | Jun 22, 2021 |
| Gateway       | NE56R                       | [46cf5e62d0](https://linux-hardware.org/?probe=46cf5e62d0) | Jun 22, 2021 |
| Acer          | Aspire 5742                 | [38f25268b8](https://linux-hardware.org/?probe=38f25268b8) | Jun 22, 2021 |
| Samsung       | RV415                       | [4165ffec30](https://linux-hardware.org/?probe=4165ffec30) | Jun 22, 2021 |
| ASUSTek       | X450LA                      | [243cc91799](https://linux-hardware.org/?probe=243cc91799) | Jun 22, 2021 |
| Positivo      | W940SU2                     | [7baff31673](https://linux-hardware.org/?probe=7baff31673) | Jun 21, 2021 |
| Positivo      | WCBT1013                    | [58031e1391](https://linux-hardware.org/?probe=58031e1391) | Jun 21, 2021 |
| Multilaser    | PC301                       | [71d16b6679](https://linux-hardware.org/?probe=71d16b6679) | Jun 21, 2021 |
| Unknown       | Unknown                     | [02161cf811](https://linux-hardware.org/?probe=02161cf811) | Jun 21, 2021 |
| ASUSTek       | X510UR                      | [6e3f8bf6f9](https://linux-hardware.org/?probe=6e3f8bf6f9) | Jun 21, 2021 |
| Google        | Peppy                       | [2e7909a66d](https://linux-hardware.org/?probe=2e7909a66d) | Jun 21, 2021 |
| Google        | Peppy                       | [a97829b01e](https://linux-hardware.org/?probe=a97829b01e) | Jun 21, 2021 |
| Acer          | Aspire A515-51G             | [4d5b39c58c](https://linux-hardware.org/?probe=4d5b39c58c) | Jun 21, 2021 |
| Dell          | Vostro 5490                 | [35a2b0b4d4](https://linux-hardware.org/?probe=35a2b0b4d4) | Jun 21, 2021 |
| Acer          | Predator G9-793             | [ae4824f52e](https://linux-hardware.org/?probe=ae4824f52e) | Jun 20, 2021 |
| Samsung       | 300E5M/300E5L               | [ad36de48aa](https://linux-hardware.org/?probe=ad36de48aa) | Jun 20, 2021 |
| Samsung       | 300E5M/300E5L               | [d33a8c2c35](https://linux-hardware.org/?probe=d33a8c2c35) | Jun 20, 2021 |
| Dell          | Inspiron 5480               | [185f257a83](https://linux-hardware.org/?probe=185f257a83) | Jun 20, 2021 |
| Dell          | Inspiron N7110              | [41512cfc6a](https://linux-hardware.org/?probe=41512cfc6a) | Jun 20, 2021 |
| Positivo      | CHT12CP                     | [a563fa0660](https://linux-hardware.org/?probe=a563fa0660) | Jun 20, 2021 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | [3e980445c3](https://linux-hardware.org/?probe=3e980445c3) | Jun 20, 2021 |
| Dell          | Inspiron 3501               | [0fa2846047](https://linux-hardware.org/?probe=0fa2846047) | Jun 20, 2021 |
| HP            | EliteBook 850 G1            | [e93b924262](https://linux-hardware.org/?probe=e93b924262) | Jun 20, 2021 |
| Philco        | 14F                         | [343861b100](https://linux-hardware.org/?probe=343861b100) | Jun 20, 2021 |
| ASUSTek       | X510UR                      | [54866c0b56](https://linux-hardware.org/?probe=54866c0b56) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Unknown       | Unknown                     | [57f6314001](https://linux-hardware.org/?probe=57f6314001) | Jun 19, 2021 |
| Sony          | VPCF126FM                   | [672f451299](https://linux-hardware.org/?probe=672f451299) | Jun 19, 2021 |
| Sony          | VPCF126FM                   | [302348533b](https://linux-hardware.org/?probe=302348533b) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| Acer          | Aspire E1-572               | [5d9f586d72](https://linux-hardware.org/?probe=5d9f586d72) | Jun 19, 2021 |
| HP            | 18-5600br                   | [d0583b92ed](https://linux-hardware.org/?probe=d0583b92ed) | Jun 19, 2021 |
| HP            | 18-5600br                   | [cd3657d994](https://linux-hardware.org/?probe=cd3657d994) | Jun 19, 2021 |
| HP            | 18-5600br                   | [cae1aa1394](https://linux-hardware.org/?probe=cae1aa1394) | Jun 18, 2021 |
| HP            | 18-5600br                   | [e3f995175a](https://linux-hardware.org/?probe=e3f995175a) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Acer          | Aspire E5-511               | [d878d6167a](https://linux-hardware.org/?probe=d878d6167a) | Jun 18, 2021 |
| Acer          | Aspire E5-511               | [c5bc434261](https://linux-hardware.org/?probe=c5bc434261) | Jun 18, 2021 |
| HP            | PRESARIO CQ42               | [8be9119cb4](https://linux-hardware.org/?probe=8be9119cb4) | Jun 18, 2021 |
| Positivo      | H14BT58                     | [51b9ba65e0](https://linux-hardware.org/?probe=51b9ba65e0) | Jun 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [04fa70e3af](https://linux-hardware.org/?probe=04fa70e3af) | Jun 18, 2021 |
| Acer          | Nitro AN515-54              | [f6b425c110](https://linux-hardware.org/?probe=f6b425c110) | Jun 18, 2021 |
| Samsung       | RV415                       | [3870ff85f0](https://linux-hardware.org/?probe=3870ff85f0) | Jun 18, 2021 |
| Lenovo        | ThinkPad E490 20N9S12C00    | [bcc92e3cf2](https://linux-hardware.org/?probe=bcc92e3cf2) | Jun 17, 2021 |
| Dell          | Inspiron 13-5378            | [5246eabc5f](https://linux-hardware.org/?probe=5246eabc5f) | Jun 17, 2021 |
| Acer          | Aspire E5-574G              | [5263e616d8](https://linux-hardware.org/?probe=5263e616d8) | Jun 17, 2021 |
| Positivo      | C14CU51                     | [4b0a7fd707](https://linux-hardware.org/?probe=4b0a7fd707) | Jun 17, 2021 |
| Acer          | Nitro AN517-51              | [af372ea58f](https://linux-hardware.org/?probe=af372ea58f) | Jun 17, 2021 |
| Samsung       | 550XDA                      | [76abc737ce](https://linux-hardware.org/?probe=76abc737ce) | Jun 17, 2021 |
| Acer          | Nitro AN515-54              | [245cf00853](https://linux-hardware.org/?probe=245cf00853) | Jun 17, 2021 |
| Dell          | Vostro 5490                 | [ad8c871406](https://linux-hardware.org/?probe=ad8c871406) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | [9072bce23d](https://linux-hardware.org/?probe=9072bce23d) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | [b557ccbf94](https://linux-hardware.org/?probe=b557ccbf94) | Jun 17, 2021 |
| Dell          | Inspiron 5423               | [37e7a9d827](https://linux-hardware.org/?probe=37e7a9d827) | Jun 17, 2021 |
| Acer          | Aspire V3-571               | [2d37a6fdb3](https://linux-hardware.org/?probe=2d37a6fdb3) | Jun 16, 2021 |
| HP            | G42                         | [6c7ca36345](https://linux-hardware.org/?probe=6c7ca36345) | Jun 16, 2021 |
| HP            | ProBook 640 G1              | [24da04505e](https://linux-hardware.org/?probe=24da04505e) | Jun 16, 2021 |
| Acer          | Aspire A315-53              | [e4943aaa7f](https://linux-hardware.org/?probe=e4943aaa7f) | Jun 16, 2021 |
| Acer          | Aspire A315-53              | [9ea373a7f8](https://linux-hardware.org/?probe=9ea373a7f8) | Jun 16, 2021 |
| Acer          | Aspire 4743                 | [354c46b2ae](https://linux-hardware.org/?probe=354c46b2ae) | Jun 16, 2021 |
| Dell          | Inspiron 3542               | [aa9140b37e](https://linux-hardware.org/?probe=aa9140b37e) | Jun 15, 2021 |
| Positivo      | C41TB                       | [3824885cc3](https://linux-hardware.org/?probe=3824885cc3) | Jun 15, 2021 |
| Dell          | Vostro 3500                 | [51a5eb8469](https://linux-hardware.org/?probe=51a5eb8469) | Jun 15, 2021 |
| Acer          | Aspire E5-571               | [736aea2a9f](https://linux-hardware.org/?probe=736aea2a9f) | Jun 15, 2021 |
| Dell          | Inspiron N4050              | [98919ec26c](https://linux-hardware.org/?probe=98919ec26c) | Jun 15, 2021 |
| Acer          | Nitro AN515-54              | [943e70a605](https://linux-hardware.org/?probe=943e70a605) | Jun 15, 2021 |
| Lenovo        | BS145-15IIL 82HB            | [e1e37c4609](https://linux-hardware.org/?probe=e1e37c4609) | Jun 15, 2021 |
| Intel         | W7645                       | [8cc3ed81ef](https://linux-hardware.org/?probe=8cc3ed81ef) | Jun 15, 2021 |
| Lenovo        | G400s VILG1                 | [ba5bdaa498](https://linux-hardware.org/?probe=ba5bdaa498) | Jun 15, 2021 |
| Intel         | W7650                       | [05cc2213db](https://linux-hardware.org/?probe=05cc2213db) | Jun 15, 2021 |
| Positivo      | Mobile                      | [050aa55013](https://linux-hardware.org/?probe=050aa55013) | Jun 14, 2021 |
| Dell          | Inspiron 5548               | [11bea838aa](https://linux-hardware.org/?probe=11bea838aa) | Jun 14, 2021 |
| Dell          | Inspiron 3576               | [86382f1779](https://linux-hardware.org/?probe=86382f1779) | Jun 14, 2021 |
| Acer          | Aspire A315-23G             | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Acer          | Nitro AN515-54              | [d0a7fa08b3](https://linux-hardware.org/?probe=d0a7fa08b3) | Jun 13, 2021 |
| HP            | 18-5600br                   | [2fca89986a](https://linux-hardware.org/?probe=2fca89986a) | Jun 13, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ba473cd8fd](https://linux-hardware.org/?probe=ba473cd8fd) | Jun 13, 2021 |
| ASUSTek       | X550CA                      | [b751bbacb8](https://linux-hardware.org/?probe=b751bbacb8) | Jun 13, 2021 |
| Positivo B... | VJC141F11X-B0111L           | [116a3f8f3e](https://linux-hardware.org/?probe=116a3f8f3e) | Jun 13, 2021 |
| ASUSTek       | X55U                        | [e7a144d475](https://linux-hardware.org/?probe=e7a144d475) | Jun 13, 2021 |
| ASUSTek       | X55U                        | [03e3c8e7a7](https://linux-hardware.org/?probe=03e3c8e7a7) | Jun 13, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [51991fb796](https://linux-hardware.org/?probe=51991fb796) | Jun 13, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [aa066e1c37](https://linux-hardware.org/?probe=aa066e1c37) | Jun 13, 2021 |
| Sony          | SVT13115FBS                 | [221d6f05d3](https://linux-hardware.org/?probe=221d6f05d3) | Jun 13, 2021 |
| Sony          | SVT13115FBS                 | [5ee39642ac](https://linux-hardware.org/?probe=5ee39642ac) | Jun 13, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | [d77b922d69](https://linux-hardware.org/?probe=d77b922d69) | Jun 13, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [f9f886db6b](https://linux-hardware.org/?probe=f9f886db6b) | Jun 13, 2021 |
| Positivo B... | VJC141F11X-B0111L           | [94ffffd81e](https://linux-hardware.org/?probe=94ffffd81e) | Jun 13, 2021 |
| Samsung       | RF511/RF411/RF711           | [768755d03d](https://linux-hardware.org/?probe=768755d03d) | Jun 12, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | [ee4b73374d](https://linux-hardware.org/?probe=ee4b73374d) | Jun 12, 2021 |
| HP            | Pavilion dv5                | [d9f46a83a2](https://linux-hardware.org/?probe=d9f46a83a2) | Jun 12, 2021 |
| Samsung       | 700Z3C/700Z5C               | [01e22d19b3](https://linux-hardware.org/?probe=01e22d19b3) | Jun 12, 2021 |
| Lenovo        | ThinkPad Edge E430 3254T... | [f737e3a7ad](https://linux-hardware.org/?probe=f737e3a7ad) | Jun 12, 2021 |
| ASUSTek       | X556URK                     | [228de7fa0e](https://linux-hardware.org/?probe=228de7fa0e) | Jun 12, 2021 |
| Samsung       | 300E5M/300E5L               | [990648bf2c](https://linux-hardware.org/?probe=990648bf2c) | Jun 12, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [edc0d32baa](https://linux-hardware.org/?probe=edc0d32baa) | Jun 12, 2021 |
| Acer          | Nitro AN517-51              | [6a1ada92f8](https://linux-hardware.org/?probe=6a1ada92f8) | Jun 12, 2021 |
| Acer          | Nitro AN517-51              | [2ecd9ea4b7](https://linux-hardware.org/?probe=2ecd9ea4b7) | Jun 12, 2021 |
| ASUSTek       | X550LN                      | [67bbff8363](https://linux-hardware.org/?probe=67bbff8363) | Jun 11, 2021 |
| ASUSTek       | X550LN                      | [b37374d9f8](https://linux-hardware.org/?probe=b37374d9f8) | Jun 11, 2021 |
| LG Electro... | P420-G.BC44P1               | [d55ddc4ab6](https://linux-hardware.org/?probe=d55ddc4ab6) | Jun 11, 2021 |
| Dell          | XPS L421X                   | [0b60a71fff](https://linux-hardware.org/?probe=0b60a71fff) | Jun 11, 2021 |
| Dell          | XPS L421X                   | [c45f0e21c0](https://linux-hardware.org/?probe=c45f0e21c0) | Jun 11, 2021 |
| Dell          | Inspiron 5548               | [9c821bc1eb](https://linux-hardware.org/?probe=9c821bc1eb) | Jun 11, 2021 |
| Intel         | W7645                       | [8341b70970](https://linux-hardware.org/?probe=8341b70970) | Jun 11, 2021 |
| Dell          | Vostro 3550                 | [3043e7d13d](https://linux-hardware.org/?probe=3043e7d13d) | Jun 11, 2021 |
| Lenovo        | IdeaPad Y430 20005          | [ef8d0e4b6a](https://linux-hardware.org/?probe=ef8d0e4b6a) | Jun 11, 2021 |
| HP            | G42                         | [9e70487afb](https://linux-hardware.org/?probe=9e70487afb) | Jun 11, 2021 |
| LG Electro... | P420-G.BC44P1               | [3706159069](https://linux-hardware.org/?probe=3706159069) | Jun 10, 2021 |
| ASUSTek       | 1015PE                      | [d1ee176a23](https://linux-hardware.org/?probe=d1ee176a23) | Jun 10, 2021 |
| HP            | ProBook 640 G2              | [b4c6c47243](https://linux-hardware.org/?probe=b4c6c47243) | Jun 10, 2021 |
| Acer          | Aspire A315-54K             | [755664a6d6](https://linux-hardware.org/?probe=755664a6d6) | Jun 10, 2021 |
| Acer          | Nitro AN517-51              | [5cb8ba3d0d](https://linux-hardware.org/?probe=5cb8ba3d0d) | Jun 10, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | [7c80f3ebd2](https://linux-hardware.org/?probe=7c80f3ebd2) | Jun 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [241e4071cc](https://linux-hardware.org/?probe=241e4071cc) | Jun 10, 2021 |
| Acer          | Aspire 3000                 | [57f93cbf62](https://linux-hardware.org/?probe=57f93cbf62) | Jun 09, 2021 |
| Acer          | Aspire 3000                 | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Acer          | Aspire 5742                 | [2cbf5797c7](https://linux-hardware.org/?probe=2cbf5797c7) | Jun 09, 2021 |
| Acer          | Nitro AN515-54              | [8c6e41fe04](https://linux-hardware.org/?probe=8c6e41fe04) | Jun 09, 2021 |
| Avell         | 1711                        | [8fb30a5f8f](https://linux-hardware.org/?probe=8fb30a5f8f) | Jun 09, 2021 |
| Acer          | Aspire 5742                 | [07bd5e87d7](https://linux-hardware.org/?probe=07bd5e87d7) | Jun 09, 2021 |
| Dell          | Precision 5540              | [40e400cb8e](https://linux-hardware.org/?probe=40e400cb8e) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Positivo B... | VJFE41F11X-XXXXXX           | [067e9189bb](https://linux-hardware.org/?probe=067e9189bb) | Jun 08, 2021 |
| Positivo      | Q232A                       | [f16fe719b8](https://linux-hardware.org/?probe=f16fe719b8) | Jun 08, 2021 |
| Dell          | Inspiron 5548               | [2ac85efa40](https://linux-hardware.org/?probe=2ac85efa40) | Jun 08, 2021 |
| Quanta        | QL3 TBD                     | [bdb6375793](https://linux-hardware.org/?probe=bdb6375793) | Jun 08, 2021 |
| Sony          | SVS13112FXB                 | [9ce22cf208](https://linux-hardware.org/?probe=9ce22cf208) | Jun 08, 2021 |
| Lenovo        | ThinkPad T450s 20BWZ0CKU... | [144680789b](https://linux-hardware.org/?probe=144680789b) | Jun 08, 2021 |
| Acer          | Nitro AN517-51              | [907bcbc57d](https://linux-hardware.org/?probe=907bcbc57d) | Jun 08, 2021 |
| Lenovo        | ThinkPad T410 2537OD4       | [3f2898df3f](https://linux-hardware.org/?probe=3f2898df3f) | Jun 07, 2021 |
| Apple         | MacBookAir4,1               | [6719cd98ee](https://linux-hardware.org/?probe=6719cd98ee) | Jun 07, 2021 |
| Acer          | Aspire A315-34              | [da0e968ed6](https://linux-hardware.org/?probe=da0e968ed6) | Jun 07, 2021 |
| Acer          | Aspire A315-53              | [c54e5ca421](https://linux-hardware.org/?probe=c54e5ca421) | Jun 07, 2021 |
| Acer          | Nitro AN517-51              | [d087cc40ee](https://linux-hardware.org/?probe=d087cc40ee) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Samsung       | 300E5K/300E5Q               | [5319df9212](https://linux-hardware.org/?probe=5319df9212) | Jun 06, 2021 |
| Dell          | Inspiron 7391               | [8aa75cc36c](https://linux-hardware.org/?probe=8aa75cc36c) | Jun 06, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [81eb461a61](https://linux-hardware.org/?probe=81eb461a61) | Jun 06, 2021 |
| Dell          | Inspiron 1525               | [412bb1ecf5](https://linux-hardware.org/?probe=412bb1ecf5) | Jun 06, 2021 |
| LG Electro... | N450-P.BE55P1               | [0151392f82](https://linux-hardware.org/?probe=0151392f82) | Jun 05, 2021 |
| LG Electro... | N450-P.BE55P1               | [5665115bf7](https://linux-hardware.org/?probe=5665115bf7) | Jun 05, 2021 |
| Dell          | Inspiron 3543               | [184390c71d](https://linux-hardware.org/?probe=184390c71d) | Jun 05, 2021 |
| Dell          | Inspiron 3543               | [c0186e4617](https://linux-hardware.org/?probe=c0186e4617) | Jun 05, 2021 |
| HP            | 240 G4 Notebook PC          | [1c8a62b98b](https://linux-hardware.org/?probe=1c8a62b98b) | Jun 05, 2021 |
| HP            | 240 G4 Notebook PC          | [a69f20c299](https://linux-hardware.org/?probe=a69f20c299) | Jun 05, 2021 |
| HP            | Pavilion g4                 | [507b8c8a2b](https://linux-hardware.org/?probe=507b8c8a2b) | Jun 05, 2021 |
| Dell          | Latitude E5470              | [5b65572d25](https://linux-hardware.org/?probe=5b65572d25) | Jun 05, 2021 |
| Dell          | Inspiron 5423               | [25ef3ff7a3](https://linux-hardware.org/?probe=25ef3ff7a3) | Jun 05, 2021 |
| Acer          | Nitro AN515-54              | [a55e132655](https://linux-hardware.org/?probe=a55e132655) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | Pavilion g4                 | [485fd080c7](https://linux-hardware.org/?probe=485fd080c7) | Jun 05, 2021 |
| Dell          | Inspiron 3583               | [08dbd93be1](https://linux-hardware.org/?probe=08dbd93be1) | Jun 04, 2021 |
| Acer          | Nitro AN515-43              | [4b725ca633](https://linux-hardware.org/?probe=4b725ca633) | Jun 04, 2021 |
| Acer          | Nitro AN515-43              | [3ded8fe948](https://linux-hardware.org/?probe=3ded8fe948) | Jun 04, 2021 |
| Apple         | MacBookPro8,2               | [dfdbae77cf](https://linux-hardware.org/?probe=dfdbae77cf) | Jun 04, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [43a9dc51d9](https://linux-hardware.org/?probe=43a9dc51d9) | Jun 04, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [4023b437d2](https://linux-hardware.org/?probe=4023b437d2) | Jun 04, 2021 |
| Positivo      | Mobile                      | [03cafdec17](https://linux-hardware.org/?probe=03cafdec17) | Jun 04, 2021 |
| Positivo      | S14CT01                     | [ca501443b2](https://linux-hardware.org/?probe=ca501443b2) | Jun 03, 2021 |
| Sony          | VPCSB15GB                   | [43a9d38ca0](https://linux-hardware.org/?probe=43a9d38ca0) | Jun 03, 2021 |
| Dell          | Inspiron 3442               | [7d7527b0ab](https://linux-hardware.org/?probe=7d7527b0ab) | Jun 03, 2021 |
| Dell          | Inspiron 3442               | [ea6242b48b](https://linux-hardware.org/?probe=ea6242b48b) | Jun 03, 2021 |
| Acer          | Nitro AN517-51              | [90e861b8cf](https://linux-hardware.org/?probe=90e861b8cf) | Jun 03, 2021 |
| Dell          | Latitude E6410              | [dd2824f257](https://linux-hardware.org/?probe=dd2824f257) | Jun 03, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [46e622d002](https://linux-hardware.org/?probe=46e622d002) | Jun 02, 2021 |
| Samsung       | 550P5C/550P7C               | [c62eb032da](https://linux-hardware.org/?probe=c62eb032da) | Jun 02, 2021 |
| Dell          | Latitude 5410               | [c3b9079d72](https://linux-hardware.org/?probe=c3b9079d72) | Jun 02, 2021 |
| Acer          | Nitro AN517-51              | [c825606f49](https://linux-hardware.org/?probe=c825606f49) | Jun 02, 2021 |
| HP            | Pavilion g4                 | [daca0ddd7e](https://linux-hardware.org/?probe=daca0ddd7e) | Jun 02, 2021 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [d1a55d8429](https://linux-hardware.org/?probe=d1a55d8429) | Jun 02, 2021 |
| HP            | Pavilion dv6500             | [a1be6eeba3](https://linux-hardware.org/?probe=a1be6eeba3) | Jun 02, 2021 |
| Acer          | Aspire A515-51G             | [96d11b9071](https://linux-hardware.org/?probe=96d11b9071) | Jun 01, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [3738ced25d](https://linux-hardware.org/?probe=3738ced25d) | Jun 01, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9db9ae4dc2](https://linux-hardware.org/?probe=9db9ae4dc2) | Jun 01, 2021 |
| Itautec       | Infoway W7425               | [2463f2748c](https://linux-hardware.org/?probe=2463f2748c) | Jun 01, 2021 |
| Acer          | Nitro AN517-51              | [895977603b](https://linux-hardware.org/?probe=895977603b) | Jun 01, 2021 |
| Dell          | Inspiron 3501               | [3e23b17d66](https://linux-hardware.org/?probe=3e23b17d66) | Jun 01, 2021 |
| Dell          | Inspiron 3501               | [06f2762b06](https://linux-hardware.org/?probe=06f2762b06) | Jun 01, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [3db60d4f9a](https://linux-hardware.org/?probe=3db60d4f9a) | Jun 01, 2021 |
| LG Electro... | R410-L.B211P1               | [87829d9551](https://linux-hardware.org/?probe=87829d9551) | Jun 01, 2021 |
| LG Electro... | R410-L.B211P1               | [0edd88def9](https://linux-hardware.org/?probe=0edd88def9) | Jun 01, 2021 |
| Positivo      | Mobile                      | [f6e75312a4](https://linux-hardware.org/?probe=f6e75312a4) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| Acer          | Aspire 3100                 | [d38f5b09d2](https://linux-hardware.org/?probe=d38f5b09d2) | Jun 01, 2021 |
| Acer          | Aspire 3100                 | [fbcd23ac31](https://linux-hardware.org/?probe=fbcd23ac31) | May 31, 2021 |
| ASUSTek       | X550CA                      | [08930695bc](https://linux-hardware.org/?probe=08930695bc) | May 31, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [de11ab3cc4](https://linux-hardware.org/?probe=de11ab3cc4) | May 31, 2021 |
| Login Info... | LOG-QAL30                   | [4caf31da4e](https://linux-hardware.org/?probe=4caf31da4e) | May 31, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [13d155653f](https://linux-hardware.org/?probe=13d155653f) | May 31, 2021 |
| Positivo      | S14SL01                     | [20f25688a9](https://linux-hardware.org/?probe=20f25688a9) | May 31, 2021 |
| Acer          | Aspire A315-56              | [883283c763](https://linux-hardware.org/?probe=883283c763) | May 31, 2021 |
| Positivo      | CHT14B                      | [1b5e908cff](https://linux-hardware.org/?probe=1b5e908cff) | May 31, 2021 |
| Acer          | Aspire A315-34              | [c4fa352d95](https://linux-hardware.org/?probe=c4fa352d95) | May 30, 2021 |
| Acer          | Aspire E5-573G              | [d8a334e94c](https://linux-hardware.org/?probe=d8a334e94c) | May 30, 2021 |
| LG Electro... | A410-K.BE43P1               | [61b0c0fce0](https://linux-hardware.org/?probe=61b0c0fce0) | May 29, 2021 |
| HP            | Pavilion dv5                | [cc56876d48](https://linux-hardware.org/?probe=cc56876d48) | May 29, 2021 |
| Sony          | VGN-NS120AH                 | [2ab87a40cc](https://linux-hardware.org/?probe=2ab87a40cc) | May 29, 2021 |
| Dell          | Vostro 3460                 | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Samsung       | 550XBE/350XBE               | [6d896a2155](https://linux-hardware.org/?probe=6d896a2155) | May 29, 2021 |
| Daten Tecn... | ESTELAR                     | [f19e7920ca](https://linux-hardware.org/?probe=f19e7920ca) | May 29, 2021 |
| Dell          | Latitude E5250              | [d543a99d1e](https://linux-hardware.org/?probe=d543a99d1e) | May 29, 2021 |
| Acer          | Aspire A315-56              | [313b51bb15](https://linux-hardware.org/?probe=313b51bb15) | May 28, 2021 |
| Dell          | Inspiron N4050              | [7ba7aedccd](https://linux-hardware.org/?probe=7ba7aedccd) | May 28, 2021 |
| Dell          | Inspiron N4050              | [e6b666b3f4](https://linux-hardware.org/?probe=e6b666b3f4) | May 28, 2021 |
| HP            | Pavilion Sleekbook 14 PC    | [069ea1cb31](https://linux-hardware.org/?probe=069ea1cb31) | May 28, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [20d4a3a8f9](https://linux-hardware.org/?probe=20d4a3a8f9) | May 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [413764a8d9](https://linux-hardware.org/?probe=413764a8d9) | May 28, 2021 |
| Samsung       | 370E4K                      | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| Samsung       | 270E5G/270E5U               | [e1c73da54a](https://linux-hardware.org/?probe=e1c73da54a) | May 28, 2021 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [7a7114baf9](https://linux-hardware.org/?probe=7a7114baf9) | May 28, 2021 |
| Acer          | Nitro AN517-51              | [ce68155512](https://linux-hardware.org/?probe=ce68155512) | May 28, 2021 |
| Acer          | Aspire 4720Z                | [88218a10f4](https://linux-hardware.org/?probe=88218a10f4) | May 28, 2021 |
| Lenovo        | IdeaPad Z400 VIWZ1          | [635eb2015b](https://linux-hardware.org/?probe=635eb2015b) | May 27, 2021 |
| Samsung       | 300E5K/300E5Q               | [7b58dd9a13](https://linux-hardware.org/?probe=7b58dd9a13) | May 27, 2021 |
| Acer          | Aspire E5-571               | [58b4832d53](https://linux-hardware.org/?probe=58b4832d53) | May 27, 2021 |
| Acer          | Nitro AN515-52              | [9971e42809](https://linux-hardware.org/?probe=9971e42809) | May 26, 2021 |
| HP            | Pavilion dv6700             | [4e93c68985](https://linux-hardware.org/?probe=4e93c68985) | May 26, 2021 |
| HP            | Pavilion dv6700             | [a114e32ffb](https://linux-hardware.org/?probe=a114e32ffb) | May 26, 2021 |
| ASUSTek       | K84C                        | [90b6f7f3b9](https://linux-hardware.org/?probe=90b6f7f3b9) | May 26, 2021 |
| Dell          | G3 3500                     | [d4dca72327](https://linux-hardware.org/?probe=d4dca72327) | May 26, 2021 |
| Sony          | SVT13115FBS                 | [21b82a1d69](https://linux-hardware.org/?probe=21b82a1d69) | May 26, 2021 |
| Acer          | Aspire A315-23G             | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Multilaser    | PC301                       | [041c47a5f0](https://linux-hardware.org/?probe=041c47a5f0) | May 25, 2021 |
| LG Electro... | N450-P.BE55P1               | [a5b16bff78](https://linux-hardware.org/?probe=a5b16bff78) | May 25, 2021 |
| ASUSTek       | 1015PX                      | [2117f02a4f](https://linux-hardware.org/?probe=2117f02a4f) | May 25, 2021 |
| Intel         | HuronRiver Platform         | [bea9269412](https://linux-hardware.org/?probe=bea9269412) | May 25, 2021 |
| Lenovo        | V310-14ISK 80UF0004BR       | [834dfabed8](https://linux-hardware.org/?probe=834dfabed8) | May 25, 2021 |
| Lenovo        | V310-14ISK 80UF0004BR       | [ce7b65f353](https://linux-hardware.org/?probe=ce7b65f353) | May 25, 2021 |
| Acer          | Aspire A315-41G             | [8dab17c109](https://linux-hardware.org/?probe=8dab17c109) | May 25, 2021 |
| Acer          | Nitro AN517-51              | [f2d3447b1d](https://linux-hardware.org/?probe=f2d3447b1d) | May 25, 2021 |
| Acer          | Nitro AN517-51              | [a32823ebe7](https://linux-hardware.org/?probe=a32823ebe7) | May 25, 2021 |
| Intel         | Intel powered classmate ... | [b49664c3de](https://linux-hardware.org/?probe=b49664c3de) | May 25, 2021 |
| Intel         | Intel powered classmate ... | [60f674f91f](https://linux-hardware.org/?probe=60f674f91f) | May 25, 2021 |
| Dell          | Inspiron N5110              | [45bcac0d81](https://linux-hardware.org/?probe=45bcac0d81) | May 25, 2021 |
| Multilaser    | PC301                       | [84be1288f4](https://linux-hardware.org/?probe=84be1288f4) | May 25, 2021 |
| Positivo      | H14SU08                     | [71d457e09d](https://linux-hardware.org/?probe=71d457e09d) | May 25, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [37cdca6b96](https://linux-hardware.org/?probe=37cdca6b96) | May 25, 2021 |
| Clevo         | W251ESQ/W270ESQ             | [2e6b9a2d9f](https://linux-hardware.org/?probe=2e6b9a2d9f) | May 25, 2021 |
| Acer          | Aspire ES1-572              | [a44408977c](https://linux-hardware.org/?probe=a44408977c) | May 24, 2021 |
| Acer          | Aspire ES1-572              | [c4b5516587](https://linux-hardware.org/?probe=c4b5516587) | May 24, 2021 |
| LG Electro... | N450-P.BE55P1               | [f0d9747885](https://linux-hardware.org/?probe=f0d9747885) | May 24, 2021 |
| HP            | Compaq 6730b (GW687AV)      | [46da8b54f1](https://linux-hardware.org/?probe=46da8b54f1) | May 24, 2021 |
| Samsung       | 300E5M/300E5L               | [2bcd802792](https://linux-hardware.org/?probe=2bcd802792) | May 24, 2021 |
| Dell          | Inspiron 5537               | [c2bcf71036](https://linux-hardware.org/?probe=c2bcf71036) | May 24, 2021 |
| ASUSTek       | X550LN                      | [1a805c94a1](https://linux-hardware.org/?probe=1a805c94a1) | May 24, 2021 |
| Dell          | Vostro 3560                 | [6c15b9e41a](https://linux-hardware.org/?probe=6c15b9e41a) | May 24, 2021 |
| Dell          | Vostro 1014                 | [c91523855c](https://linux-hardware.org/?probe=c91523855c) | May 24, 2021 |
| Acer          | Aspire A315-23G             | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| HP            | G42                         | [4b5396aa6d](https://linux-hardware.org/?probe=4b5396aa6d) | May 24, 2021 |
| Acer          | Aspire A315-56              | [4dfcc836ea](https://linux-hardware.org/?probe=4dfcc836ea) | May 24, 2021 |
| Acer          | Aspire A315-56              | [afe3ba24b3](https://linux-hardware.org/?probe=afe3ba24b3) | May 24, 2021 |
| Acer          | Aspire A315-56              | [f1ec26a398](https://linux-hardware.org/?probe=f1ec26a398) | May 24, 2021 |
| Samsung       | RV415                       | [6b56b1d1ce](https://linux-hardware.org/?probe=6b56b1d1ce) | May 23, 2021 |
| Samsung       | RV415                       | [05759e0cf0](https://linux-hardware.org/?probe=05759e0cf0) | May 23, 2021 |
| Dell          | Inspiron 7472               | [cb2e47587e](https://linux-hardware.org/?probe=cb2e47587e) | May 23, 2021 |
| Dell          | Inspiron 5548               | [7dd454cdee](https://linux-hardware.org/?probe=7dd454cdee) | May 23, 2021 |
| Dell          | Inspiron 5548               | [c45f33e2e3](https://linux-hardware.org/?probe=c45f33e2e3) | May 23, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | [93b4f5b14e](https://linux-hardware.org/?probe=93b4f5b14e) | May 22, 2021 |
| Dell          | Inspiron N4050              | [6a6087308a](https://linux-hardware.org/?probe=6a6087308a) | May 22, 2021 |
| Dell          | Inspiron N4050              | [66e0510411](https://linux-hardware.org/?probe=66e0510411) | May 22, 2021 |
| Dell          | Inspiron 3583               | [0d671acb94](https://linux-hardware.org/?probe=0d671acb94) | May 22, 2021 |
| Multilaser    | PC301                       | [c68bb3678d](https://linux-hardware.org/?probe=c68bb3678d) | May 22, 2021 |
| Acer          | Aspire A315-53              | [bedafbad9b](https://linux-hardware.org/?probe=bedafbad9b) | May 22, 2021 |
| Positivo      | CHT14B                      | [4aab647b4f](https://linux-hardware.org/?probe=4aab647b4f) | May 22, 2021 |
| OEM           | U50SI1                      | [660022b46f](https://linux-hardware.org/?probe=660022b46f) | May 21, 2021 |
| Acer          | Aspire A515-51              | [e922639ff6](https://linux-hardware.org/?probe=e922639ff6) | May 21, 2021 |
| Dell          | Inspiron 3583               | [795d0a220d](https://linux-hardware.org/?probe=795d0a220d) | May 21, 2021 |
| Acer          | Aspire A515-51              | [fb6d9ec50b](https://linux-hardware.org/?probe=fb6d9ec50b) | May 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [c9a0b1991a](https://linux-hardware.org/?probe=c9a0b1991a) | May 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [398efe5207](https://linux-hardware.org/?probe=398efe5207) | May 21, 2021 |
| Lenovo        | G40-70 80GA                 | [6cc37604a4](https://linux-hardware.org/?probe=6cc37604a4) | May 21, 2021 |
| Dell          | Vostro 3500                 | [83a315e28f](https://linux-hardware.org/?probe=83a315e28f) | May 21, 2021 |
| Dell          | Latitude E6430              | [b489ee68c9](https://linux-hardware.org/?probe=b489ee68c9) | May 21, 2021 |
| Sony          | VGN-Z570AN                  | [13d58b8d90](https://linux-hardware.org/?probe=13d58b8d90) | May 21, 2021 |
| Sony          | VGN-Z570AN                  | [e6c7882e05](https://linux-hardware.org/?probe=e6c7882e05) | May 21, 2021 |
| Dell          | Inspiron 7460               | [b766b75906](https://linux-hardware.org/?probe=b766b75906) | May 21, 2021 |
| Acer          | Aspire A315-53              | [a66bc12897](https://linux-hardware.org/?probe=a66bc12897) | May 21, 2021 |
| Toshiba       | Satellite S55t-B            | [e15d1f937b](https://linux-hardware.org/?probe=e15d1f937b) | May 20, 2021 |
| Lenovo        | Unknown                     | [9c573ae2fa](https://linux-hardware.org/?probe=9c573ae2fa) | May 20, 2021 |
| Samsung       | 530U3C/530U4C               | [be4c126c06](https://linux-hardware.org/?probe=be4c126c06) | May 20, 2021 |
| Samsung       | 530U3C/530U4C               | [a7aa09da10](https://linux-hardware.org/?probe=a7aa09da10) | May 20, 2021 |
| Acer          | Aspire A315-23G             | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Digibras      | CL341                       | [f826cc9bfa](https://linux-hardware.org/?probe=f826cc9bfa) | May 19, 2021 |
| Digibras      | CL341                       | [9c5001bbf9](https://linux-hardware.org/?probe=9c5001bbf9) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS2820... | [4ec9eaac2f](https://linux-hardware.org/?probe=4ec9eaac2f) | May 19, 2021 |
| Multilaser    | PC301                       | [bfdfb54a4a](https://linux-hardware.org/?probe=bfdfb54a4a) | May 19, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [d8c380ffa3](https://linux-hardware.org/?probe=d8c380ffa3) | May 19, 2021 |
| Dell          | Inspiron 7472               | [2858f29938](https://linux-hardware.org/?probe=2858f29938) | May 19, 2021 |
| Dell          | Inspiron 3421               | [4c5ee61420](https://linux-hardware.org/?probe=4c5ee61420) | May 19, 2021 |
| Sony          | VPCYB35AB                   | [2b76ee0822](https://linux-hardware.org/?probe=2b76ee0822) | May 18, 2021 |
| ASUSTek       | 1005HA                      | [e819e51835](https://linux-hardware.org/?probe=e819e51835) | May 18, 2021 |
| ASUSTek       | X510URR                     | [51577f00b4](https://linux-hardware.org/?probe=51577f00b4) | May 18, 2021 |
| ASUSTek       | X510URR                     | [e373dac808](https://linux-hardware.org/?probe=e373dac808) | May 18, 2021 |
| Acer          | Nitro AN515-54              | [38688703f4](https://linux-hardware.org/?probe=38688703f4) | May 18, 2021 |
| Dell          | Inspiron 5420               | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Acer          | Aspire A515-54G             | [7f53433bc2](https://linux-hardware.org/?probe=7f53433bc2) | May 18, 2021 |
| Dell          | Inspiron N5010              | [b512b8997f](https://linux-hardware.org/?probe=b512b8997f) | May 17, 2021 |
| Samsung       | 760XBE                      | [641aa732da](https://linux-hardware.org/?probe=641aa732da) | May 17, 2021 |
| Positivo      | Smash                       | [044d8ca250](https://linux-hardware.org/?probe=044d8ca250) | May 17, 2021 |
| Positivo      | Smash                       | [1295454840](https://linux-hardware.org/?probe=1295454840) | May 17, 2021 |
| Dell          | G5 5590                     | [18621bd612](https://linux-hardware.org/?probe=18621bd612) | May 17, 2021 |
| Dell          | G5 5590                     | [3f55c4844d](https://linux-hardware.org/?probe=3f55c4844d) | May 17, 2021 |
| Multilaser    | PC301                       | [b7adb90c84](https://linux-hardware.org/?probe=b7adb90c84) | May 17, 2021 |
| Acer          | Aspire A315-23G             | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [8f3f5142e4](https://linux-hardware.org/?probe=8f3f5142e4) | May 17, 2021 |
| Lenovo        | ThinkPad T440p 20AW009YB... | [1dda6f002e](https://linux-hardware.org/?probe=1dda6f002e) | May 16, 2021 |
| ASUSTek       | X550CA                      | [b719c419ce](https://linux-hardware.org/?probe=b719c419ce) | May 16, 2021 |
| Dell          | Inspiron 1545               | [e1f7cfefe3](https://linux-hardware.org/?probe=e1f7cfefe3) | May 16, 2021 |
| Dell          | Inspiron 5566               | [c9a9ff9bea](https://linux-hardware.org/?probe=c9a9ff9bea) | May 16, 2021 |
| Acer          | Nitro AN515-54              | [4baf8ea323](https://linux-hardware.org/?probe=4baf8ea323) | May 16, 2021 |
| Positivo B... | VJC141F11X-B0111L           | [2732044ef3](https://linux-hardware.org/?probe=2732044ef3) | May 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [328c6d995c](https://linux-hardware.org/?probe=328c6d995c) | May 16, 2021 |
| HP            | Pavilion dv7                | [29cf28adfd](https://linux-hardware.org/?probe=29cf28adfd) | May 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [65fc953d84](https://linux-hardware.org/?probe=65fc953d84) | May 15, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [1bdd9ddf9f](https://linux-hardware.org/?probe=1bdd9ddf9f) | May 15, 2021 |
| Acer          | Aspire A315-23G             | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| Positivo      | C14CR21TV                   | [8af930f7e1](https://linux-hardware.org/?probe=8af930f7e1) | May 15, 2021 |
| Positivo      | CHT14B                      | [4150e4dfc3](https://linux-hardware.org/?probe=4150e4dfc3) | May 15, 2021 |
| Positivo      | CHT14B                      | [44c6e9a6e3](https://linux-hardware.org/?probe=44c6e9a6e3) | May 15, 2021 |
| Lenovo        | G40-70 80GA                 | [619b20ccfb](https://linux-hardware.org/?probe=619b20ccfb) | May 15, 2021 |
| Lenovo        | G40-70 80GA                 | [c674fa597f](https://linux-hardware.org/?probe=c674fa597f) | May 15, 2021 |
| Positivo B... | VJC141F11X-B0111L           | [de219cb53b](https://linux-hardware.org/?probe=de219cb53b) | May 15, 2021 |
| LG Electro... | A410-K.BE43P1               | [48978860b6](https://linux-hardware.org/?probe=48978860b6) | May 15, 2021 |
| Dell          | Inspiron 5448               | [6b49f5eb63](https://linux-hardware.org/?probe=6b49f5eb63) | May 15, 2021 |
| Avell High... | A60 MUV                     | [70c5e3699a](https://linux-hardware.org/?probe=70c5e3699a) | May 14, 2021 |
| Acer          | Nitro AN517-51              | [3b3e402229](https://linux-hardware.org/?probe=3b3e402229) | May 14, 2021 |
| Acer          | Nitro AN517-51              | [6416e3f4cb](https://linux-hardware.org/?probe=6416e3f4cb) | May 14, 2021 |
| Multilaser    | PC301                       | [8a77e5f988](https://linux-hardware.org/?probe=8a77e5f988) | May 14, 2021 |
| Acer          | Nitro AN517-51              | [8e75fa7a0c](https://linux-hardware.org/?probe=8e75fa7a0c) | May 14, 2021 |
| Samsung       | 760XBE                      | [8065c7647a](https://linux-hardware.org/?probe=8065c7647a) | May 14, 2021 |
| Dell          | Latitude 3410               | [ea2fa485c5](https://linux-hardware.org/?probe=ea2fa485c5) | May 14, 2021 |
| Dell          | Latitude 3410               | [5cfbec7c42](https://linux-hardware.org/?probe=5cfbec7c42) | May 14, 2021 |
| Acer          | Predator PH315-52           | [0afa1e0fdf](https://linux-hardware.org/?probe=0afa1e0fdf) | May 14, 2021 |
| Lenovo        | G50-80 80R0                 | [7f333e8860](https://linux-hardware.org/?probe=7f333e8860) | May 14, 2021 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [0f6653a472](https://linux-hardware.org/?probe=0f6653a472) | May 14, 2021 |
| Acer          | Nitro AN517-51              | [af2e3e4bc4](https://linux-hardware.org/?probe=af2e3e4bc4) | May 13, 2021 |
| Acer          | Nitro AN517-51              | [ba44769424](https://linux-hardware.org/?probe=ba44769424) | May 13, 2021 |
| Samsung       | N150/N210/N220              | [2b2eb4d2ba](https://linux-hardware.org/?probe=2b2eb4d2ba) | May 13, 2021 |
| Samsung       | N150/N210/N220              | [ef1bdc06a0](https://linux-hardware.org/?probe=ef1bdc06a0) | May 13, 2021 |
| HP            | Pavilion g4                 | [43b7ffe89b](https://linux-hardware.org/?probe=43b7ffe89b) | May 13, 2021 |
| Multilaser    | PC301                       | [9d6cce1dd7](https://linux-hardware.org/?probe=9d6cce1dd7) | May 13, 2021 |
| HP            | ProBook 440 G1              | [433b504b91](https://linux-hardware.org/?probe=433b504b91) | May 13, 2021 |
| Acer          | Nitro AN517-51              | [36da7f6654](https://linux-hardware.org/?probe=36da7f6654) | May 13, 2021 |
| Unknown       | Unknown                     | [0f0153e2db](https://linux-hardware.org/?probe=0f0153e2db) | May 12, 2021 |
| Dell          | Inspiron 5448               | [c023a99051](https://linux-hardware.org/?probe=c023a99051) | May 12, 2021 |
| Dell          | Inspiron 5448               | [a29c60aea5](https://linux-hardware.org/?probe=a29c60aea5) | May 12, 2021 |
| Positivo      | Mobile                      | [0148616dc8](https://linux-hardware.org/?probe=0148616dc8) | May 12, 2021 |
| Dell          | Inspiron 1525               | [22f4b67d9b](https://linux-hardware.org/?probe=22f4b67d9b) | May 12, 2021 |
| LG Electro... | S460-G.BG31P1               | [6b07e6e09b](https://linux-hardware.org/?probe=6b07e6e09b) | May 12, 2021 |
| Apple         | MacBookPro7,1               | [1644a8c7ca](https://linux-hardware.org/?probe=1644a8c7ca) | May 12, 2021 |
| Apple         | MacBookPro7,1               | [3ea73b6512](https://linux-hardware.org/?probe=3ea73b6512) | May 12, 2021 |
| Dell          | Inspiron N5010              | [c4c9a421b7](https://linux-hardware.org/?probe=c4c9a421b7) | May 12, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [a6c9fc2a1d](https://linux-hardware.org/?probe=a6c9fc2a1d) | May 12, 2021 |
| ASUSTek       | X550LN                      | [7023b380c0](https://linux-hardware.org/?probe=7023b380c0) | May 11, 2021 |
| Dell          | Inspiron 3421               | [bc949e1978](https://linux-hardware.org/?probe=bc949e1978) | May 11, 2021 |
| Dell          | Inspiron 3421               | [799a7a5a1a](https://linux-hardware.org/?probe=799a7a5a1a) | May 11, 2021 |
| Dell          | Inspiron 7520               | [fdf52a6676](https://linux-hardware.org/?probe=fdf52a6676) | May 11, 2021 |
| Acer          | Aspire A515-52G             | [88bcad1e01](https://linux-hardware.org/?probe=88bcad1e01) | May 11, 2021 |
| Dell          | Inspiron 3584               | [3b02e9ef83](https://linux-hardware.org/?probe=3b02e9ef83) | May 11, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [6617f76415](https://linux-hardware.org/?probe=6617f76415) | May 11, 2021 |
| HP            | G62                         | [1edf487b56](https://linux-hardware.org/?probe=1edf487b56) | May 11, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | [2543210bfd](https://linux-hardware.org/?probe=2543210bfd) | May 11, 2021 |
| Apple         | MacBookPro7,1               | [f46c4ef44d](https://linux-hardware.org/?probe=f46c4ef44d) | May 10, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [a71682ef0b](https://linux-hardware.org/?probe=a71682ef0b) | May 10, 2021 |
| Positivo      | Q4128C-S                    | [15db0dcbec](https://linux-hardware.org/?probe=15db0dcbec) | May 10, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | [bb0d6e1883](https://linux-hardware.org/?probe=bb0d6e1883) | May 10, 2021 |
| Unknown       | Unknown                     | [3e034cbfe1](https://linux-hardware.org/?probe=3e034cbfe1) | May 10, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80W2      | [79b6d733ee](https://linux-hardware.org/?probe=79b6d733ee) | May 10, 2021 |
| HP            | 240 G4 Notebook PC          | [71d02dd054](https://linux-hardware.org/?probe=71d02dd054) | May 10, 2021 |
| Dell          | Latitude E5510              | [bef6827e9a](https://linux-hardware.org/?probe=bef6827e9a) | May 09, 2021 |
| ASUSTek       | X550LN                      | [4f117c46f3](https://linux-hardware.org/?probe=4f117c46f3) | May 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [50b19105c9](https://linux-hardware.org/?probe=50b19105c9) | May 09, 2021 |
| LG Electro... | A410-K.BE43P1               | [dd6a1734a8](https://linux-hardware.org/?probe=dd6a1734a8) | May 09, 2021 |
| CCE           | Capella & IbexPeak-M Chi... | [66bfdc09b1](https://linux-hardware.org/?probe=66bfdc09b1) | May 09, 2021 |
| Acer          | Nitro AN515-54              | [c0e36c44f5](https://linux-hardware.org/?probe=c0e36c44f5) | May 08, 2021 |
| Positivo      | C41TB                       | [060b2d882f](https://linux-hardware.org/?probe=060b2d882f) | May 08, 2021 |
| Dell          | Inspiron 3583               | [1edc624fd5](https://linux-hardware.org/?probe=1edc624fd5) | May 08, 2021 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [155ecefe3c](https://linux-hardware.org/?probe=155ecefe3c) | May 07, 2021 |
| Acer          | Nitro AN515-54              | [f2dc66dfb8](https://linux-hardware.org/?probe=f2dc66dfb8) | May 07, 2021 |
| Dell          | Inspiron 7520               | [518dc99f15](https://linux-hardware.org/?probe=518dc99f15) | May 07, 2021 |
| ASUSTek       | T100TAS                     | [0b8e360f8a](https://linux-hardware.org/?probe=0b8e360f8a) | May 07, 2021 |
| HP            | 450                         | [d4423fe417](https://linux-hardware.org/?probe=d4423fe417) | May 07, 2021 |
| HP            | 450                         | [077791949e](https://linux-hardware.org/?probe=077791949e) | May 07, 2021 |
| Digibras      | NH4CU53                     | [5238325455](https://linux-hardware.org/?probe=5238325455) | May 07, 2021 |
| Digibras      | NH4CU53                     | [c974b54241](https://linux-hardware.org/?probe=c974b54241) | May 07, 2021 |
| Positivo B... | VJFE43F11X-XXXXXX           | [1862615e66](https://linux-hardware.org/?probe=1862615e66) | May 07, 2021 |
| Multilaser    | PC301                       | [2bbc116611](https://linux-hardware.org/?probe=2bbc116611) | May 06, 2021 |
| Multilaser    | PC301                       | [e8c1f6996f](https://linux-hardware.org/?probe=e8c1f6996f) | May 06, 2021 |
| Positivo      | MOBILE                      | [645443231f](https://linux-hardware.org/?probe=645443231f) | May 06, 2021 |
| Acer          | Swift SF314-42              | [31dd47cfcb](https://linux-hardware.org/?probe=31dd47cfcb) | May 06, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [f6fb2d4e35](https://linux-hardware.org/?probe=f6fb2d4e35) | May 06, 2021 |
| Dell          | Inspiron 3584               | [884499ef14](https://linux-hardware.org/?probe=884499ef14) | May 06, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [b2dbc7da71](https://linux-hardware.org/?probe=b2dbc7da71) | May 06, 2021 |
| Digibras      | NH4CU53                     | [b3f257cef8](https://linux-hardware.org/?probe=b3f257cef8) | May 05, 2021 |
| Acer          | Nitro AN515-54              | [fba713de6b](https://linux-hardware.org/?probe=fba713de6b) | May 05, 2021 |
| Acer          | Nitro AN515-54              | [236a42921f](https://linux-hardware.org/?probe=236a42921f) | May 05, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [87f849e52f](https://linux-hardware.org/?probe=87f849e52f) | May 05, 2021 |
| HP            | G42                         | [4a107897cf](https://linux-hardware.org/?probe=4a107897cf) | May 05, 2021 |
| Digibras      | NH4CU53                     | [d19301aa15](https://linux-hardware.org/?probe=d19301aa15) | May 05, 2021 |
| Digibras      | NH4CU53                     | [c831b37bae](https://linux-hardware.org/?probe=c831b37bae) | May 05, 2021 |
| Acer          | Aspire A515-41G             | [69afcebb9a](https://linux-hardware.org/?probe=69afcebb9a) | May 05, 2021 |
| Dell          | Latitude E6410              | [5c29371d72](https://linux-hardware.org/?probe=5c29371d72) | May 05, 2021 |
| Lenovo        | 720-15IKB 81CQ              | [d761210fe9](https://linux-hardware.org/?probe=d761210fe9) | May 05, 2021 |
| Dell          | Inspiron 5590               | [6901f8a463](https://linux-hardware.org/?probe=6901f8a463) | May 05, 2021 |
| Dell          | Inspiron 5590               | [e187b95783](https://linux-hardware.org/?probe=e187b95783) | May 05, 2021 |
| Acer          | Aspire A515-51G             | [ab92d875c3](https://linux-hardware.org/?probe=ab92d875c3) | May 04, 2021 |
| Acer          | Aspire A515-51              | [ea1d5762db](https://linux-hardware.org/?probe=ea1d5762db) | May 04, 2021 |
| Acer          | Aspire A515-41G             | [38e06153e9](https://linux-hardware.org/?probe=38e06153e9) | May 04, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [1cd6106673](https://linux-hardware.org/?probe=1cd6106673) | May 04, 2021 |
| Lenovo        | 720-15IKB 81CQ              | [94eee77f90](https://linux-hardware.org/?probe=94eee77f90) | May 04, 2021 |
| Unknown       | Unknown                     | [0a82b79706](https://linux-hardware.org/?probe=0a82b79706) | May 04, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [0c612ea2a3](https://linux-hardware.org/?probe=0c612ea2a3) | May 04, 2021 |
| Dell          | Inspiron 3442               | [1f0cf22837](https://linux-hardware.org/?probe=1f0cf22837) | May 04, 2021 |
| Dell          | Inspiron 3442               | [0875a2798d](https://linux-hardware.org/?probe=0875a2798d) | May 04, 2021 |
| Dell          | Vostro 5490                 | [c89b28e2f3](https://linux-hardware.org/?probe=c89b28e2f3) | May 03, 2021 |
| Samsung       | 300E5K/300E5Q               | [f857e8de08](https://linux-hardware.org/?probe=f857e8de08) | May 03, 2021 |
| Dell          | Latitude E6430              | [ae54b2b764](https://linux-hardware.org/?probe=ae54b2b764) | May 03, 2021 |
| Acer          | Aspire A315-33              | [b859199e22](https://linux-hardware.org/?probe=b859199e22) | May 03, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [db99936c38](https://linux-hardware.org/?probe=db99936c38) | May 03, 2021 |
| HP            | EliteBook 8760w             | [8608522c5a](https://linux-hardware.org/?probe=8608522c5a) | May 03, 2021 |
| HP            | EliteBook 8760w             | [fe3b8cb6bc](https://linux-hardware.org/?probe=fe3b8cb6bc) | May 03, 2021 |
| Dell          | G3 3579                     | [64c3bf76af](https://linux-hardware.org/?probe=64c3bf76af) | May 03, 2021 |
| Dell          | Latitude E5510              | [4e52a8c4d3](https://linux-hardware.org/?probe=4e52a8c4d3) | May 03, 2021 |
| Dell          | Vostro 5490                 | [b852cc3b14](https://linux-hardware.org/?probe=b852cc3b14) | May 03, 2021 |
| Dell          | Vostro 5490                 | [43ecd6539f](https://linux-hardware.org/?probe=43ecd6539f) | May 03, 2021 |
| Sony          | VPCS13AGX                   | [4764b6428f](https://linux-hardware.org/?probe=4764b6428f) | May 03, 2021 |
| Sony          | VPCS13AGX                   | [d1301f4c8d](https://linux-hardware.org/?probe=d1301f4c8d) | May 03, 2021 |
| Acer          | Aspire A315-34              | [5c217da8c4](https://linux-hardware.org/?probe=5c217da8c4) | May 02, 2021 |
| Lenovo        | ThinkPad T470 20HES1HD01    | [4eb1086713](https://linux-hardware.org/?probe=4eb1086713) | May 02, 2021 |
| Positivo B... | VJFE43F11X-XXXXXX           | [77ad837583](https://linux-hardware.org/?probe=77ad837583) | May 02, 2021 |
| Acer          | Aspire F5-573               | [f5a8b02dc3](https://linux-hardware.org/?probe=f5a8b02dc3) | May 02, 2021 |
| Acer          | Aspire V3-572PG             | [d81e5ab43c](https://linux-hardware.org/?probe=d81e5ab43c) | May 02, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [bcccb164dc](https://linux-hardware.org/?probe=bcccb164dc) | May 01, 2021 |
| HP            | G42                         | [dd8ca2760f](https://linux-hardware.org/?probe=dd8ca2760f) | May 01, 2021 |
| Lenovo        | ThinkPad X270 20HNA003CD    | [836cddeafe](https://linux-hardware.org/?probe=836cddeafe) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [857022f167](https://linux-hardware.org/?probe=857022f167) | May 01, 2021 |
| Acer          | Nitro AN517-51              | [bf33efa182](https://linux-hardware.org/?probe=bf33efa182) | May 01, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | [471a5fed37](https://linux-hardware.org/?probe=471a5fed37) | May 01, 2021 |
| Dell          | Inspiron 15-3567            | [85bfb2950b](https://linux-hardware.org/?probe=85bfb2950b) | Apr 30, 2021 |
| Gigabyte      | M2432                       | [354e017032](https://linux-hardware.org/?probe=354e017032) | Apr 30, 2021 |
| Gigabyte      | M2432                       | [59243622d0](https://linux-hardware.org/?probe=59243622d0) | Apr 30, 2021 |
| Lenovo        | 100-14IBY 80R7              | [61af9638d2](https://linux-hardware.org/?probe=61af9638d2) | Apr 30, 2021 |
| Positivo      | S14CT01                     | [d6ad6f67a7](https://linux-hardware.org/?probe=d6ad6f67a7) | Apr 30, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [dc004ba87d](https://linux-hardware.org/?probe=dc004ba87d) | Apr 30, 2021 |
| Dell          | Inspiron 13-5378            | [e36e444bac](https://linux-hardware.org/?probe=e36e444bac) | Apr 29, 2021 |
| LG Electro... | U460-G.BG51P1               | [4fb97c4677](https://linux-hardware.org/?probe=4fb97c4677) | Apr 29, 2021 |
| Dell          | Latitude D531               | [096370a055](https://linux-hardware.org/?probe=096370a055) | Apr 29, 2021 |
| Acer          | E1-510                      | [5c34c6dc90](https://linux-hardware.org/?probe=5c34c6dc90) | Apr 29, 2021 |
| Samsung       | 270E5J/2570EJ               | [48c0082d7e](https://linux-hardware.org/?probe=48c0082d7e) | Apr 29, 2021 |
| Positivo      | W942SW_SW1                  | [8e09ae02e6](https://linux-hardware.org/?probe=8e09ae02e6) | Apr 29, 2021 |
| Positivo      | W942SW_SW1                  | [4c63d890bc](https://linux-hardware.org/?probe=4c63d890bc) | Apr 29, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [fe5be9fb83](https://linux-hardware.org/?probe=fe5be9fb83) | Apr 29, 2021 |
| Toshiba       | IS 1423G                    | [63604595ca](https://linux-hardware.org/?probe=63604595ca) | Apr 29, 2021 |
| Toshiba       | IS 1423G                    | [6fd7935ac7](https://linux-hardware.org/?probe=6fd7935ac7) | Apr 28, 2021 |
| LG Electro... | U460-G.BG51P1               | [9d623df5e4](https://linux-hardware.org/?probe=9d623df5e4) | Apr 28, 2021 |
| Itautec       | Infoway                     | [01e1f5151c](https://linux-hardware.org/?probe=01e1f5151c) | Apr 28, 2021 |
| LG Electro... | S425-L.BC22P1               | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| Acer          | Aspire F5-573G              | [fdabc1d291](https://linux-hardware.org/?probe=fdabc1d291) | Apr 28, 2021 |
| Acer          | Aspire F5-573G              | [2e2cc93814](https://linux-hardware.org/?probe=2e2cc93814) | Apr 28, 2021 |
| Dell          | Inspiron 13-5378            | [9edeb6f6ad](https://linux-hardware.org/?probe=9edeb6f6ad) | Apr 28, 2021 |
| HP            | Laptop 14-cm0xxx            | [220e290fcb](https://linux-hardware.org/?probe=220e290fcb) | Apr 28, 2021 |
| Lenovo        | ThinkPad T430 2347G2P       | [c1fa54ec47](https://linux-hardware.org/?probe=c1fa54ec47) | Apr 28, 2021 |
| Dell          | Vostro 5490                 | [1e0725c7f7](https://linux-hardware.org/?probe=1e0725c7f7) | Apr 28, 2021 |
| Acer          | Aspire 5734Z                | [936f72a9f5](https://linux-hardware.org/?probe=936f72a9f5) | Apr 28, 2021 |
| Dell          | Inspiron 3421               | [9c92d353d4](https://linux-hardware.org/?probe=9c92d353d4) | Apr 28, 2021 |
| Acer          | Nitro AN515-54              | [3685e8d706](https://linux-hardware.org/?probe=3685e8d706) | Apr 27, 2021 |
| Multilaser    | PC132                       | [f3844ad90d](https://linux-hardware.org/?probe=f3844ad90d) | Apr 27, 2021 |
| Acer          | AFT                         | [1a35724745](https://linux-hardware.org/?probe=1a35724745) | Apr 27, 2021 |
| Acer          | Aspire A315-53              | [d79183eb2c](https://linux-hardware.org/?probe=d79183eb2c) | Apr 27, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [004380d8f4](https://linux-hardware.org/?probe=004380d8f4) | Apr 27, 2021 |
| Dell          | Latitude E6420              | [7dbd1d34b7](https://linux-hardware.org/?probe=7dbd1d34b7) | Apr 27, 2021 |
| Sony          | VPCYB35AB                   | [cdaa0ecd8d](https://linux-hardware.org/?probe=cdaa0ecd8d) | Apr 27, 2021 |
| Sony          | VPCYB35AB                   | [727ae4ccc1](https://linux-hardware.org/?probe=727ae4ccc1) | Apr 27, 2021 |
| Positivo      | C41TB                       | [1d746150af](https://linux-hardware.org/?probe=1d746150af) | Apr 26, 2021 |
| LG Electro... | A410-K.BE43P1               | [59c2086399](https://linux-hardware.org/?probe=59c2086399) | Apr 26, 2021 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [303f687cb8](https://linux-hardware.org/?probe=303f687cb8) | Apr 26, 2021 |
| Toshiba       | IS 1442                     | [ef9ff84d34](https://linux-hardware.org/?probe=ef9ff84d34) | Apr 26, 2021 |
| HP            | Pavilion dv5                | [014f848744](https://linux-hardware.org/?probe=014f848744) | Apr 26, 2021 |
| Lenovo        | G460 20041                  | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| Compal        | HGL31I                      | [d1d8a50709](https://linux-hardware.org/?probe=d1d8a50709) | Apr 26, 2021 |
| Compal        | HGL31I                      | [69fca71300](https://linux-hardware.org/?probe=69fca71300) | Apr 26, 2021 |
| LG Electro... | A410-K.BE43P1               | [e909bbda9e](https://linux-hardware.org/?probe=e909bbda9e) | Apr 26, 2021 |
| Acer          | Aspire 5733                 | [3b48abe35c](https://linux-hardware.org/?probe=3b48abe35c) | Apr 26, 2021 |
| HP            | 240 G4 Notebook PC          | [85a3f96dff](https://linux-hardware.org/?probe=85a3f96dff) | Apr 25, 2021 |
| Acer          | Aspire A515-51              | [fa63002527](https://linux-hardware.org/?probe=fa63002527) | Apr 25, 2021 |
| Positivo      | C41TB                       | [179c326307](https://linux-hardware.org/?probe=179c326307) | Apr 25, 2021 |
| Positivo      | Mobile                      | [8be7f4099a](https://linux-hardware.org/?probe=8be7f4099a) | Apr 25, 2021 |
| Lenovo        | ThinkPad T420 4180M8P       | [1fe655cf93](https://linux-hardware.org/?probe=1fe655cf93) | Apr 25, 2021 |
| Dell          | System XPS L502X            | [1cc0642748](https://linux-hardware.org/?probe=1cc0642748) | Apr 25, 2021 |
| HP            | 246 G7 Notebook PC          | [a1ab7115cf](https://linux-hardware.org/?probe=a1ab7115cf) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Acer          | Aspire M5-481PT             | [b8da2787da](https://linux-hardware.org/?probe=b8da2787da) | Apr 25, 2021 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [05bd929025](https://linux-hardware.org/?probe=05bd929025) | Apr 25, 2021 |
| Samsung       | 270E5J/2570EJ               | [4b75101836](https://linux-hardware.org/?probe=4b75101836) | Apr 25, 2021 |
| Samsung       | 270E5J/2570EJ               | [560e714442](https://linux-hardware.org/?probe=560e714442) | Apr 25, 2021 |
| Acer          | Aspire F5-573               | [f2894e1f89](https://linux-hardware.org/?probe=f2894e1f89) | Apr 25, 2021 |
| Acer          | Aspire F5-573               | [a210d6d564](https://linux-hardware.org/?probe=a210d6d564) | Apr 25, 2021 |
| LG Electro... | 23V545-G.BK31P1             | [23ca62db00](https://linux-hardware.org/?probe=23ca62db00) | Apr 24, 2021 |
| LG Electro... | 23V545-G.BK31P1             | [d1565a2e25](https://linux-hardware.org/?probe=d1565a2e25) | Apr 24, 2021 |
| Samsung       | 300E5M/300E5L               | [2386be709a](https://linux-hardware.org/?probe=2386be709a) | Apr 24, 2021 |
| Dell          | Vostro 1014                 | [3d8f2e2b96](https://linux-hardware.org/?probe=3d8f2e2b96) | Apr 24, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [8f49103dc5](https://linux-hardware.org/?probe=8f49103dc5) | Apr 24, 2021 |
| Acer          | Aspire V3-571               | [8fa3307dc8](https://linux-hardware.org/?probe=8fa3307dc8) | Apr 24, 2021 |
| Acer          | Nitro AN515-54              | [78740e55a7](https://linux-hardware.org/?probe=78740e55a7) | Apr 24, 2021 |
| Acer          | Unknown                     | [cd6b0eabe2](https://linux-hardware.org/?probe=cd6b0eabe2) | Apr 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c2e0fc28f8](https://linux-hardware.org/?probe=c2e0fc28f8) | Apr 23, 2021 |
| HP            | EliteBook 8440p             | [05febf7abc](https://linux-hardware.org/?probe=05febf7abc) | Apr 23, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [779f54d3c6](https://linux-hardware.org/?probe=779f54d3c6) | Apr 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b6bf66b28e](https://linux-hardware.org/?probe=b6bf66b28e) | Apr 23, 2021 |
| HP            | G62                         | [dbbbd046ee](https://linux-hardware.org/?probe=dbbbd046ee) | Apr 23, 2021 |
| Toshiba       | IS 1422                     | [f52456fce9](https://linux-hardware.org/?probe=f52456fce9) | Apr 22, 2021 |
| Toshiba       | IS 1422                     | [9443f68502](https://linux-hardware.org/?probe=9443f68502) | Apr 22, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [e98d7b3ad4](https://linux-hardware.org/?probe=e98d7b3ad4) | Apr 22, 2021 |
| OEM           | I40SI1                      | [04737d1a75](https://linux-hardware.org/?probe=04737d1a75) | Apr 22, 2021 |
| Positivo      | S14SL01                     | [7746cc4610](https://linux-hardware.org/?probe=7746cc4610) | Apr 22, 2021 |
| Alienware     | 17 R2                       | [494e22b607](https://linux-hardware.org/?probe=494e22b607) | Apr 22, 2021 |
| HP            | Pavilion g6                 | [13bcf0c25a](https://linux-hardware.org/?probe=13bcf0c25a) | Apr 22, 2021 |
| Positivo      | S14SL01                     | [f1cc01bb29](https://linux-hardware.org/?probe=f1cc01bb29) | Apr 22, 2021 |
| ASUSTek       | X401U                       | [c2a6402a22](https://linux-hardware.org/?probe=c2a6402a22) | Apr 22, 2021 |
| Acer          | Predator PH315-53           | [15549ca0ed](https://linux-hardware.org/?probe=15549ca0ed) | Apr 21, 2021 |
| Positivo      | C14CR21                     | [e396067726](https://linux-hardware.org/?probe=e396067726) | Apr 21, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c4f21a1871](https://linux-hardware.org/?probe=c4f21a1871) | Apr 21, 2021 |
| Apple         | MacBookPro11,1              | [443252b02a](https://linux-hardware.org/?probe=443252b02a) | Apr 21, 2021 |
| ATI           | BONEFISH                    | [c4d6f442ce](https://linux-hardware.org/?probe=c4d6f442ce) | Apr 21, 2021 |
| Toshiba       | IS 1412                     | [57d6bfc205](https://linux-hardware.org/?probe=57d6bfc205) | Apr 21, 2021 |
| Dell          | Inspiron 3576               | [0b15d5d9d1](https://linux-hardware.org/?probe=0b15d5d9d1) | Apr 21, 2021 |
| Dell          | Inspiron N4020              | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3835eff7c6](https://linux-hardware.org/?probe=3835eff7c6) | Apr 21, 2021 |
| Dell          | Inspiron 3442               | [8b54dfbb8c](https://linux-hardware.org/?probe=8b54dfbb8c) | Apr 21, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ba7a3bd259](https://linux-hardware.org/?probe=ba7a3bd259) | Apr 21, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [9866eb07e6](https://linux-hardware.org/?probe=9866eb07e6) | Apr 21, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d7a945866a](https://linux-hardware.org/?probe=d7a945866a) | Apr 20, 2021 |
| HP            | ProBook 440 G1              | [1324768a15](https://linux-hardware.org/?probe=1324768a15) | Apr 20, 2021 |
| Dell          | Inspiron 7559               | [2dfdf7148f](https://linux-hardware.org/?probe=2dfdf7148f) | Apr 20, 2021 |
| Samsung       | 800G5M/800G5W               | [f9fd9e5602](https://linux-hardware.org/?probe=f9fd9e5602) | Apr 20, 2021 |
| Lenovo        | G40-80 80JE                 | [399e4eb45d](https://linux-hardware.org/?probe=399e4eb45d) | Apr 20, 2021 |
| Dell          | Inspiron 3480               | [6c8f65bf2e](https://linux-hardware.org/?probe=6c8f65bf2e) | Apr 20, 2021 |
| Apple         | MacBookPro11,1              | [7da4bf77ed](https://linux-hardware.org/?probe=7da4bf77ed) | Apr 20, 2021 |
| HP            | 2000                        | [d8ce8df35a](https://linux-hardware.org/?probe=d8ce8df35a) | Apr 20, 2021 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [9180bd6615](https://linux-hardware.org/?probe=9180bd6615) | Apr 20, 2021 |
| Lenovo        | ThinkPad T460 20FMS6C200    | [7f900f8923](https://linux-hardware.org/?probe=7f900f8923) | Apr 20, 2021 |
| Itautec       | Infoway w7440               | [084490a1f9](https://linux-hardware.org/?probe=084490a1f9) | Apr 20, 2021 |
| Dell          | Inspiron N4020              | [f03d856fe1](https://linux-hardware.org/?probe=f03d856fe1) | Apr 20, 2021 |
| Samsung       | 800G5M/800G5W               | [536f1dd4fe](https://linux-hardware.org/?probe=536f1dd4fe) | Apr 20, 2021 |
| Dell          | Inspiron N5010              | [d54729d43d](https://linux-hardware.org/?probe=d54729d43d) | Apr 20, 2021 |
| Dell          | System XPS L502X            | [0fea972b34](https://linux-hardware.org/?probe=0fea972b34) | Apr 20, 2021 |
| Dell          | System XPS L502X            | [109f6db0da](https://linux-hardware.org/?probe=109f6db0da) | Apr 20, 2021 |
| HP            | Notebook                    | [d61733d8ee](https://linux-hardware.org/?probe=d61733d8ee) | Apr 20, 2021 |
| Toshiba       | NI 1403                     | [32d3859912](https://linux-hardware.org/?probe=32d3859912) | Apr 19, 2021 |
| HP            | 2000                        | [0265f74d4a](https://linux-hardware.org/?probe=0265f74d4a) | Apr 19, 2021 |
| Dell          | Inspiron 15-3567            | [5f12b3083c](https://linux-hardware.org/?probe=5f12b3083c) | Apr 19, 2021 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [aaf8987d29](https://linux-hardware.org/?probe=aaf8987d29) | Apr 19, 2021 |
| Positivo      | S14CT01                     | [5b0b6f4197](https://linux-hardware.org/?probe=5b0b6f4197) | Apr 19, 2021 |
| Dell          | Vostro 1014                 | [ff6e067312](https://linux-hardware.org/?probe=ff6e067312) | Apr 18, 2021 |
| Dell          | Vostro 1014                 | [84a1787483](https://linux-hardware.org/?probe=84a1787483) | Apr 18, 2021 |
| ASUSTek       | X450LCP                     | [2e6844c2a0](https://linux-hardware.org/?probe=2e6844c2a0) | Apr 18, 2021 |
| ASUSTek       | UX31E                       | [325abb24b4](https://linux-hardware.org/?probe=325abb24b4) | Apr 18, 2021 |
| Acer          | Aspire A315-34              | [90d9379d50](https://linux-hardware.org/?probe=90d9379d50) | Apr 18, 2021 |
| Positivo      | C14CR21                     | [2829ea9d87](https://linux-hardware.org/?probe=2829ea9d87) | Apr 17, 2021 |
| Acer          | Aspire A315-34              | [c10e0391bc](https://linux-hardware.org/?probe=c10e0391bc) | Apr 17, 2021 |
| HP            | Pavilion 11 x360 PC         | [a4d6817276](https://linux-hardware.org/?probe=a4d6817276) | Apr 17, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [a37c76c160](https://linux-hardware.org/?probe=a37c76c160) | Apr 17, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [335a444bbd](https://linux-hardware.org/?probe=335a444bbd) | Apr 17, 2021 |
| Dell          | Inspiron 5468               | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| ASUSTek       | UX31E                       | [28ac4e6ef9](https://linux-hardware.org/?probe=28ac4e6ef9) | Apr 17, 2021 |
| HP            | Pavilion dv6                | [1f7c25614f](https://linux-hardware.org/?probe=1f7c25614f) | Apr 17, 2021 |
| HP            | Pavilion dv6                | [50f5e0cc11](https://linux-hardware.org/?probe=50f5e0cc11) | Apr 17, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1759cb61d3](https://linux-hardware.org/?probe=1759cb61d3) | Apr 16, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [b62215e929](https://linux-hardware.org/?probe=b62215e929) | Apr 16, 2021 |
| Dell          | Inspiron 5458               | [3ca820a73c](https://linux-hardware.org/?probe=3ca820a73c) | Apr 16, 2021 |
| Toshiba       | IS 1412                     | [e80ec8fb27](https://linux-hardware.org/?probe=e80ec8fb27) | Apr 16, 2021 |
| Acer          | Aspire A315-56              | [8478d04872](https://linux-hardware.org/?probe=8478d04872) | Apr 15, 2021 |
| LG Electro... | S425-L.BC22P1               | [b087767c04](https://linux-hardware.org/?probe=b087767c04) | Apr 15, 2021 |
| LG Electro... | S425-L.BC22P1               | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| OEM           | I40SI1                      | [df56cb647a](https://linux-hardware.org/?probe=df56cb647a) | Apr 15, 2021 |
| Acer          | Aspire F5-573               | [82de91c65b](https://linux-hardware.org/?probe=82de91c65b) | Apr 15, 2021 |
| Dell          | Vostro 3500                 | [5480240e10](https://linux-hardware.org/?probe=5480240e10) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [400305194d](https://linux-hardware.org/?probe=400305194d) | Apr 15, 2021 |
| Toshiba       | NI 1403                     | [a3789d1a53](https://linux-hardware.org/?probe=a3789d1a53) | Apr 15, 2021 |
| Positivo      | CHT14B                      | [98a1d3fba5](https://linux-hardware.org/?probe=98a1d3fba5) | Apr 15, 2021 |
| Acer          | Aspire A515-54G             | [aa70eaaaec](https://linux-hardware.org/?probe=aa70eaaaec) | Apr 14, 2021 |
| Lenovo        | G460 20041                  | [5afa7d8b4d](https://linux-hardware.org/?probe=5afa7d8b4d) | Apr 14, 2021 |
| Lenovo        | G460 20041                  | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Lenovo        | G400s VILG1                 | [b33c69951a](https://linux-hardware.org/?probe=b33c69951a) | Apr 14, 2021 |
| Sony          | SVS13A25PBS                 | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| Quanta        | TWJ                         | [a53bd3833a](https://linux-hardware.org/?probe=a53bd3833a) | Apr 14, 2021 |
| HP            | Pavilion Sleekbook 14 PC    | [62c27647b9](https://linux-hardware.org/?probe=62c27647b9) | Apr 14, 2021 |
| HP            | Pavilion Sleekbook 14 PC    | [f7e5bcea67](https://linux-hardware.org/?probe=f7e5bcea67) | Apr 14, 2021 |
| Acer          | Aspire A515-54G             | [d1a0206cd7](https://linux-hardware.org/?probe=d1a0206cd7) | Apr 14, 2021 |
| Dell          | Vostro 3500                 | [a0d23769ed](https://linux-hardware.org/?probe=a0d23769ed) | Apr 14, 2021 |
| Unknown       | Unknown                     | [0675c3788e](https://linux-hardware.org/?probe=0675c3788e) | Apr 14, 2021 |
| Unknown       | Unknown                     | [1f31c55841](https://linux-hardware.org/?probe=1f31c55841) | Apr 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5af507f808](https://linux-hardware.org/?probe=5af507f808) | Apr 14, 2021 |
| Dell          | Inspiron 3480               | [75f43079fb](https://linux-hardware.org/?probe=75f43079fb) | Apr 13, 2021 |
| Dell          | Vostro 5470                 | [81095b075b](https://linux-hardware.org/?probe=81095b075b) | Apr 13, 2021 |
| Dell          | Inspiron 3480               | [dce5f8220a](https://linux-hardware.org/?probe=dce5f8220a) | Apr 13, 2021 |
| Dell          | Inspiron 15-3567            | [783d3428bb](https://linux-hardware.org/?probe=783d3428bb) | Apr 13, 2021 |
| Dell          | Inspiron 3421               | [b99847bcbe](https://linux-hardware.org/?probe=b99847bcbe) | Apr 13, 2021 |
| Dell          | Latitude 5410               | [15a26d0647](https://linux-hardware.org/?probe=15a26d0647) | Apr 13, 2021 |
| Dell          | Latitude 5410               | [c7638179d7](https://linux-hardware.org/?probe=c7638179d7) | Apr 13, 2021 |
| Dell          | Vostro 3500                 | [00c5001233](https://linux-hardware.org/?probe=00c5001233) | Apr 13, 2021 |
| MSI           | GT70 2OC/2OD                | [bffa087e39](https://linux-hardware.org/?probe=bffa087e39) | Apr 13, 2021 |
| MSI           | GT70 2OC/2OD                | [e529250394](https://linux-hardware.org/?probe=e529250394) | Apr 13, 2021 |
| Dell          | Inspiron 5566               | [3f063b636f](https://linux-hardware.org/?probe=3f063b636f) | Apr 13, 2021 |
| Acer          | Aspire M5-582PT             | [8abc23484b](https://linux-hardware.org/?probe=8abc23484b) | Apr 13, 2021 |
| Sony          | VPCSC41FM                   | [b04963620c](https://linux-hardware.org/?probe=b04963620c) | Apr 13, 2021 |
| Dell          | Inspiron 5557               | [fe3648804d](https://linux-hardware.org/?probe=fe3648804d) | Apr 12, 2021 |
| Dell          | Inspiron 5570               | [f3c725bd98](https://linux-hardware.org/?probe=f3c725bd98) | Apr 12, 2021 |
| Acer          | Aspire 5251                 | [821b6dbcb3](https://linux-hardware.org/?probe=821b6dbcb3) | Apr 12, 2021 |
| Acer          | Aspire A514-53              | [f56ecc6299](https://linux-hardware.org/?probe=f56ecc6299) | Apr 12, 2021 |
| Itautec       | Infoway w7535               | [5bf6a27a57](https://linux-hardware.org/?probe=5bf6a27a57) | Apr 12, 2021 |
| Dell          | Inspiron 5448               | [de44f5f457](https://linux-hardware.org/?probe=de44f5f457) | Apr 12, 2021 |
| Samsung       | 370E4K                      | [71a369010e](https://linux-hardware.org/?probe=71a369010e) | Apr 12, 2021 |
| Dell          | Inspiron N5010              | [e809ca489d](https://linux-hardware.org/?probe=e809ca489d) | Apr 12, 2021 |
| Lenovo        | Yoga 510-14ISK 80UK         | [9b61901e8b](https://linux-hardware.org/?probe=9b61901e8b) | Apr 11, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 875       | 14.33%  |
| Ubuntu 18.04      | 590       | 9.66%   |
| Pop!_OS 20.04     | 190       | 3.11%   |
| Linux Mint 20     | 188       | 3.08%   |
| Linux Mint 19.3   | 162       | 2.65%   |
| OpenMandriva 4.2  | 152       | 2.49%   |
| Linux Mint 19.1   | 121       | 1.98%   |
| Ubuntu 19.04      | 117       | 1.92%   |
| Linux Mint 20.1   | 114       | 1.87%   |
| Ubuntu 19.10      | 106       | 1.74%   |
| Linux Mint 20.2   | 103       | 1.69%   |
| Arch              | 98        | 1.6%    |
| KDE neon 20.04    | 92        | 1.51%   |
| Zorin 15          | 89        | 1.46%   |
| Debian 10         | 82        | 1.34%   |
| Manjaro           | 81        | 1.33%   |
| Fedora 35         | 75        | 1.23%   |
| Pop!_OS 21.10     | 71        | 1.16%   |
| Fedora 34         | 71        | 1.16%   |
| Fedora 32         | 70        | 1.15%   |
| Endless 3.7.8     | 68        | 1.11%   |
| Pop!_OS 21.04     | 67        | 1.1%    |
| Endless 3.9.5     | 67        | 1.1%    |
| Linux Mint 20.3   | 65        | 1.06%   |
| Xubuntu 20.04     | 64        | 1.05%   |
| Kubuntu 20.04     | 61        | 1%      |
| Zorin 16          | 60        | 0.98%   |
| Ubuntu 16.04      | 60        | 0.98%   |
| Fedora 33         | 60        | 0.98%   |
| Pop!_OS 20.10     | 59        | 0.97%   |
| Ubuntu 20.10      | 56        | 0.92%   |
| OpenMandriva 4.3  | 55        | 0.9%    |
| Linux Mint 19.2   | 54        | 0.88%   |
| Debian 11         | 50        | 0.82%   |
| Endless 3.9.1     | 49        | 0.8%    |
| Ubuntu 18.10      | 47        | 0.77%   |
| Endless 3.8.6     | 46        | 0.75%   |
| Endless 3.7.4     | 46        | 0.75%   |
| Endless 3.9.4     | 43        | 0.7%    |
| Endless 3.8.7     | 43        | 0.7%    |
| Endless 3.9.3     | 41        | 0.67%   |
| Ubuntu 21.10      | 40        | 0.65%   |
| Endless 3.8.4     | 39        | 0.64%   |
| Ubuntu 21.04      | 38        | 0.62%   |
| Arch Rolling      | 38        | 0.62%   |
| Xubuntu 18.04     | 37        | 0.61%   |
| Fedora 31         | 36        | 0.59%   |
| Ubuntu MATE 20.04 | 34        | 0.56%   |
| Endless 3.8.0     | 30        | 0.49%   |
| Endless 3.8.3     | 29        | 0.47%   |
| Manjaro 20.0.3    | 27        | 0.44%   |
| Lubuntu 20.04     | 27        | 0.44%   |
| Endless 4.0.2     | 26        | 0.43%   |
| LMDE 4            | 24        | 0.39%   |
| Endless 3.9.0     | 23        | 0.38%   |
| Endless 3.8.5     | 23        | 0.38%   |
| Debian Testing    | 22        | 0.36%   |
| Endless 3.7.5     | 21        | 0.34%   |
| Debian 9          | 21        | 0.34%   |
| Ubuntu 22.04      | 20        | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1909      | 32.5%   |
| Linux Mint    | 796       | 13.55%  |
| Endless       | 765       | 13.03%  |
| Pop!_OS       | 385       | 6.56%   |
| Fedora        | 321       | 5.47%   |
| OpenMandriva  | 219       | 3.73%   |
| Debian        | 171       | 2.91%   |
| Manjaro       | 168       | 2.86%   |
| Zorin         | 153       | 2.61%   |
| Arch          | 128       | 2.18%   |
| Xubuntu       | 110       | 1.87%   |
| KDE neon      | 108       | 1.84%   |
| Kubuntu       | 99        | 1.69%   |
| Lubuntu       | 62        | 1.06%   |
| Ubuntu MATE   | 52        | 0.89%   |
| ROSA          | 45        | 0.77%   |
| Elementary    | 45        | 0.77%   |
| openSUSE      | 44        | 0.75%   |
| Deepin        | 30        | 0.51%   |
| Kali          | 29        | 0.49%   |
| LMDE          | 28        | 0.48%   |
| Clear Linux   | 23        | 0.39%   |
| Ubuntu Budgie | 22        | 0.37%   |
| LinuxFX       | 21        | 0.36%   |
| ArcoLinux     | 12        | 0.2%    |
| BlackPanther  | 11        | 0.19%   |
| Reborn OS     | 9         | 0.15%   |
| Peppermint    | 8         | 0.14%   |
| EndeavourOS   | 8         | 0.14%   |
| BigLinux      | 8         | 0.14%   |
| MX            | 7         | 0.12%   |
| CentOS        | 7         | 0.12%   |
| Solus         | 6         | 0.1%    |
| Parrot        | 6         | 0.1%    |
| Gentoo        | 6         | 0.1%    |
| Void Linux    | 4         | 0.07%   |
| Slackware     | 4         | 0.07%   |
| Garuda Linux  | 4         | 0.07%   |
| PostmarketOS  | 3         | 0.05%   |
| Devuan        | 3         | 0.05%   |
| Artix         | 3         | 0.05%   |
| RHEL          | 2         | 0.03%   |
| PCLinuxOS     | 2         | 0.03%   |
| Oracle Linux  | 2         | 0.03%   |
| GNOME OS      | 2         | 0.03%   |
| Funtoo        | 2         | 0.03%   |
| Chrome OS     | 2         | 0.03%   |
| BlackArch     | 2         | 0.03%   |
| Alpine        | 2         | 0.03%   |
| UbuntuDDE     | 1         | 0.02%   |
| Q4OS          | 1         | 0.02%   |
| PureOS        | 1         | 0.02%   |
| Pardus        | 1         | 0.02%   |
| Nitrux        | 1         | 0.02%   |
| Netrunner     | 1         | 0.02%   |
| Mageia        | 1         | 0.02%   |
| Linux Lite    | 1         | 0.02%   |
| LFS           | 1         | 0.02%   |
| Generic       | 1         | 0.02%   |
| Freespire     | 1         | 0.02%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 470       | 7.12%   |
| 5.8.0-14-generic         | 251       | 3.8%    |
| 5.10.14-desktop-1omv4002 | 146       | 2.21%   |
| 5.4.0-19-generic         | 113       | 1.71%   |
| 5.3.0-28-generic         | 107       | 1.62%   |
| 5.4.0-7634-generic       | 75        | 1.14%   |
| 5.4.0-48-generic         | 72        | 1.09%   |
| 5.4.0-40-generic         | 71        | 1.08%   |
| 4.15.0-46-generic        | 70        | 1.06%   |
| 5.4.0-26-generic         | 63        | 0.95%   |
| 5.4.0-58-generic         | 60        | 0.91%   |
| 5.4.0-52-generic         | 59        | 0.89%   |
| 5.16.7-desktop-1omv4003  | 55        | 0.83%   |
| 5.4.0-47-generic         | 54        | 0.82%   |
| 5.3.0-19-generic         | 50        | 0.76%   |
| 5.11.0-35-generic        | 50        | 0.76%   |
| 5.3.0-46-generic         | 47        | 0.71%   |
| 5.3.0-23-generic         | 47        | 0.71%   |
| 5.0.0-32-generic         | 47        | 0.71%   |
| 5.4.0-29-generic         | 44        | 0.67%   |
| 4.18.0-15-generic        | 44        | 0.67%   |
| 5.4.0-65-generic         | 43        | 0.65%   |
| 5.3.0-40-generic         | 42        | 0.64%   |
| 5.0.0-37-generic         | 42        | 0.64%   |
| 5.4.0-39-generic         | 41        | 0.62%   |
| 5.4.0-80-generic         | 40        | 0.61%   |
| 5.0.0-25-generic         | 39        | 0.59%   |
| 5.4.0-70-generic         | 38        | 0.58%   |
| 5.11.0-7620-generic      | 38        | 0.58%   |
| 4.18.0-16-generic        | 38        | 0.58%   |
| 5.4.0-37-generic         | 37        | 0.56%   |
| 4.15.0-20-generic        | 37        | 0.56%   |
| 5.13.0-30-generic        | 36        | 0.55%   |
| 5.3.0-51-generic         | 35        | 0.53%   |
| 5.11.0-37-generic        | 35        | 0.53%   |
| 5.11.0-27-generic        | 35        | 0.53%   |
| 5.4.0-72-generic         | 34        | 0.52%   |
| 5.4.0-45-generic         | 33        | 0.5%    |
| 5.3.0-53-generic         | 33        | 0.5%    |
| 5.4.0-74-generic         | 32        | 0.48%   |
| 5.8.0-50-generic         | 31        | 0.47%   |
| 5.4.0-54-generic         | 31        | 0.47%   |
| 5.0.0-23-generic         | 31        | 0.47%   |
| 5.4.0-7642-generic       | 30        | 0.45%   |
| 5.4.0-66-generic         | 30        | 0.45%   |
| 5.0.0-13-generic         | 30        | 0.45%   |
| 4.18.0-17-generic        | 30        | 0.45%   |
| 4.15.0-47-generic        | 30        | 0.45%   |
| 5.8.0-7630-generic       | 29        | 0.44%   |
| 5.8.0-43-generic         | 29        | 0.44%   |
| 4.18.0-25-generic        | 29        | 0.44%   |
| 5.13.0-7620-generic      | 28        | 0.42%   |
| 5.8.0-41-generic         | 27        | 0.41%   |
| 5.4.0-91-generic         | 27        | 0.41%   |
| 5.4.0-73-generic         | 27        | 0.41%   |
| 5.3.0-62-generic         | 27        | 0.41%   |
| 5.13.0-39-generic        | 27        | 0.41%   |
| 5.4.0-56-generic         | 26        | 0.39%   |
| 5.3.0-42-generic         | 26        | 0.39%   |
| 5.8.0-44-generic         | 25        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 1734      | 27.9%   |
| 5.8.0   | 582       | 9.37%   |
| 5.3.0   | 534       | 8.59%   |
| 4.15.0  | 506       | 8.14%   |
| 5.11.0  | 386       | 6.21%   |
| 5.0.0   | 320       | 5.15%   |
| 4.18.0  | 229       | 3.69%   |
| 5.13.0  | 210       | 3.38%   |
| 5.10.14 | 148       | 2.38%   |
| 4.19.0  | 100       | 1.61%   |
| 5.10.0  | 74        | 1.19%   |
| 5.16.7  | 55        | 0.89%   |
| 5.15.0  | 31        | 0.5%    |
| 5.16.11 | 29        | 0.47%   |
| 5.7.9   | 26        | 0.42%   |
| 4.4.0   | 24        | 0.39%   |
| 5.15.15 | 20        | 0.32%   |
| 5.15.5  | 19        | 0.31%   |
| 4.9.0   | 19        | 0.31%   |
| 5.9.16  | 17        | 0.27%   |
| 5.7.0   | 17        | 0.27%   |
| 5.6.19  | 16        | 0.26%   |
| 5.16.15 | 16        | 0.26%   |
| 5.3.18  | 15        | 0.24%   |
| 5.11.12 | 15        | 0.24%   |
| 5.16.19 | 14        | 0.23%   |
| 5.9.11  | 13        | 0.21%   |
| 5.15.8  | 13        | 0.21%   |
| 5.7.10  | 12        | 0.19%   |
| 5.13.13 | 12        | 0.19%   |
| 4.18.16 | 12        | 0.19%   |
| 5.8.18  | 11        | 0.18%   |
| 5.15.23 | 11        | 0.18%   |
| 5.14.0  | 11        | 0.18%   |
| 4.9.60  | 11        | 0.18%   |
| 5.6.0   | 10        | 0.16%   |
| 5.11.11 | 10        | 0.16%   |
| 5.1.0   | 10        | 0.16%   |
| 5.6.15  | 9         | 0.14%   |
| 5.15.11 | 9         | 0.14%   |
| 5.14.10 | 9         | 0.14%   |
| 5.12.9  | 9         | 0.14%   |
| 5.8.15  | 8         | 0.13%   |
| 5.7.8   | 8         | 0.13%   |
| 5.6.6   | 8         | 0.13%   |
| 5.17.1  | 8         | 0.13%   |
| 5.16.12 | 8         | 0.13%   |
| 5.15.7  | 8         | 0.13%   |
| 5.13.19 | 8         | 0.13%   |
| 5.12.4  | 8         | 0.13%   |
| 5.9.10  | 7         | 0.11%   |
| 5.8.16  | 7         | 0.11%   |
| 5.8.14  | 7         | 0.11%   |
| 5.8.13  | 7         | 0.11%   |
| 5.4.52  | 7         | 0.11%   |
| 5.4.50  | 7         | 0.11%   |
| 5.3.7   | 7         | 0.11%   |
| 5.15.6  | 7         | 0.11%   |
| 5.14.14 | 7         | 0.11%   |
| 5.12.8  | 7         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1805      | 29.36%  |
| 5.8     | 652       | 10.61%  |
| 5.3     | 577       | 9.39%   |
| 4.15    | 506       | 8.23%   |
| 5.11    | 451       | 7.34%   |
| 5.0     | 344       | 5.6%    |
| 5.10    | 313       | 5.09%   |
| 5.13    | 263       | 4.28%   |
| 4.18    | 245       | 3.99%   |
| 5.16    | 165       | 2.68%   |
| 5.15    | 145       | 2.36%   |
| 4.19    | 117       | 1.9%    |
| 5.7     | 101       | 1.64%   |
| 5.9     | 67        | 1.09%   |
| 5.6     | 67        | 1.09%   |
| 5.14    | 65        | 1.06%   |
| 5.12    | 60        | 0.98%   |
| 4.9     | 43        | 0.7%    |
| 5.5     | 32        | 0.52%   |
| 5.1     | 29        | 0.47%   |
| 4.4     | 27        | 0.44%   |
| 5.17    | 25        | 0.41%   |
| 5.2     | 15        | 0.24%   |
| 4.13    | 7         | 0.11%   |
| 4.20    | 5         | 0.08%   |
| 4.14    | 4         | 0.07%   |
| 4.10    | 4         | 0.07%   |
| 4.1     | 4         | 0.07%   |
| 3.10    | 4         | 0.07%   |
| 4.17    | 2         | 0.03%   |
| 4.8     | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 5490      | 97.07%  |
| i686   | 163       | 2.88%   |
| armv7l | 3         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 2925      | 49.8%   |
| Unknown         | 953       | 16.23%  |
| KDE5            | 476       | 8.1%    |
| X-Cinnamon      | 434       | 7.39%   |
| XFCE            | 357       | 6.08%   |
| KDE             | 159       | 2.71%   |
| MATE            | 155       | 2.64%   |
| Cinnamon        | 119       | 2.03%   |
| LXQt            | 55        | 0.94%   |
| Unity           | 45        | 0.77%   |
| Pantheon        | 38        | 0.65%   |
| Deepin          | 36        | 0.61%   |
| Budgie          | 31        | 0.53%   |
| LXDE            | 29        | 0.49%   |
| KDE4            | 25        | 0.43%   |
| i3              | 16        | 0.27%   |
| GNOME Classic   | 8         | 0.14%   |
| awesome         | 4         | 0.07%   |
| GNOME Flashback | 2         | 0.03%   |
| Enlightenment   | 2         | 0.03%   |
| xmonad          | 1         | 0.02%   |
| Trinity         | 1         | 0.02%   |
| sway            | 1         | 0.02%   |
| Openbox         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 4836      | 83.71%  |
| Unknown | 477       | 8.26%   |
| Wayland | 439       | 7.6%    |
| Tty     | 25        | 0.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4048      | 69.57%  |
| GDM     | 655       | 11.26%  |
| SDDM    | 462       | 7.94%   |
| TDM     | 283       | 4.86%   |
| LightDM | 206       | 3.54%   |
| GDM3    | 132       | 2.27%   |
| KDM     | 26        | 0.45%   |
| XDM     | 3         | 0.05%   |
| SLiM    | 2         | 0.03%   |
| MDM     | 1         | 0.02%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pt_BR   | 3822      | 66.24%  |
| Unknown | 901       | 15.62%  |
| en_US   | 899       | 15.58%  |
| C       | 77        | 1.33%   |
| en_GB   | 22        | 0.38%   |
| pt_PT   | 20        | 0.35%   |
| es_ES   | 8         | 0.14%   |
| POSIX   | 3         | 0.05%   |
| fr_FR   | 3         | 0.05%   |
| en_CA   | 3         | 0.05%   |
| de_DE   | 3         | 0.05%   |
| es_MX   | 2         | 0.03%   |
| ru_RU   | 1         | 0.02%   |
| ja_JP   | 1         | 0.02%   |
| it_IT   | 1         | 0.02%   |
| es_CL   | 1         | 0.02%   |
| es_AR   | 1         | 0.02%   |
| em_US   | 1         | 0.02%   |
| ar_EG   | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 2904      | 50.33%  |
| EFI  | 2866      | 49.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4712      | 81.81%  |
| Unknown | 375       | 6.51%   |
| Overlay | 302       | 5.24%   |
| Btrfs   | 286       | 4.97%   |
| Xfs     | 33        | 0.57%   |
| Zfs     | 16        | 0.28%   |
| Tmpfs   | 13        | 0.23%   |
| Ext3    | 9         | 0.16%   |
| Ext2    | 9         | 0.16%   |
| F2fs    | 3         | 0.05%   |
| Aufs    | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4183      | 72.6%   |
| GPT     | 1087      | 18.86%  |
| MBR     | 492       | 8.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5226      | 91.6%   |
| Yes       | 479       | 8.4%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4473      | 78.13%  |
| Yes       | 1252      | 21.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell                   | 1298      | 22.95%  |
| Acer                   | 1166      | 20.62%  |
| Lenovo                 | 686       | 12.13%  |
| Samsung Electronics    | 462       | 8.17%   |
| Hewlett-Packard        | 405       | 7.16%   |
| Positivo               | 386       | 6.83%   |
| ASUSTek Computer       | 289       | 5.11%   |
| Sony                   | 129       | 2.28%   |
| LG Electronics         | 78        | 1.38%   |
| Apple                  | 67        | 1.18%   |
| Itautec                | 60        | 1.06%   |
| Semp Toshiba           | 57        | 1.01%   |
| Digibras               | 57        | 1.01%   |
| Avell High Performance | 52        | 0.92%   |
| Unknown                | 52        | 0.92%   |
| Intel                  | 39        | 0.69%   |
| Toshiba                | 32        | 0.57%   |
| Philco                 | 32        | 0.57%   |
| OEM                    | 30        | 0.53%   |
| Multilaser             | 29        | 0.51%   |
| Positivo Bahia - VAIO  | 25        | 0.44%   |
| Compaq                 | 24        | 0.42%   |
| Notebook               | 22        | 0.39%   |
| Compal                 | 17        | 0.3%    |
| Gateway                | 16        | 0.28%   |
| MSI                    | 14        | 0.25%   |
| Google                 | 13        | 0.23%   |
| Clevo                  | 12        | 0.21%   |
| eMachines              | 9         | 0.16%   |
| Quanta                 | 8         | 0.14%   |
| Alienware              | 7         | 0.12%   |
| CCE                    | 6         | 0.11%   |
| Standard               | 5         | 0.09%   |
| LNV                    | 5         | 0.09%   |
| Timi                   | 4         | 0.07%   |
| Login Informatica      | 4         | 0.07%   |
| IDEALMAX               | 4         | 0.07%   |
| Pegatron               | 3         | 0.05%   |
| Megaware               | 3         | 0.05%   |
| Gigabyte Technology    | 3         | 0.05%   |
| TPVAOC                 | 2         | 0.04%   |
| System76               | 2         | 0.04%   |
| Razer                  | 2         | 0.04%   |
| Qbex                   | 2         | 0.04%   |
| Phoenix/SiS            | 2         | 0.04%   |
| ODM                    | 2         | 0.04%   |
| Haier                  | 2         | 0.04%   |
| Daten Tecnologia       | 2         | 0.04%   |
| Coradir                | 2         | 0.04%   |
| Chuwi                  | 2         | 0.04%   |
| ATI                    | 2         | 0.04%   |
| VIT                    | 1         | 0.02%   |
| Ultra                  | 1         | 0.02%   |
| TUXEDO                 | 1         | 0.02%   |
| Teclast                | 1         | 0.02%   |
| SiS                    | 1         | 0.02%   |
| Pine Microsystems      | 1         | 0.02%   |
| PC Specialist          | 1         | 0.02%   |
| Packard Bell           | 1         | 0.02%   |
| ONKYO                  | 1         | 0.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                         | 129       | 2.28%   |
| Positivo MOBILE                             | 113       | 2%      |
| Unknown                                     | 84        | 1.49%   |
| Acer Aspire A315-53                         | 64        | 1.13%   |
| Samsung 340XAA/350XAA/550XAA                | 58        | 1.03%   |
| Dell Inspiron 3583                          | 51        | 0.9%    |
| Acer Nitro AN517-51                         | 50        | 0.88%   |
| Acer Aspire A315-34                         | 50        | 0.88%   |
| Acer Nitro AN515-44                         | 49        | 0.87%   |
| Dell Inspiron 5566                          | 48        | 0.85%   |
| Lenovo IdeaPad S145-15API 81V7              | 47        | 0.83%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 47        | 0.83%   |
| Acer Nitro AN515-43                         | 44        | 0.78%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 43        | 0.76%   |
| Dell Inspiron 15-3567                       | 42        | 0.74%   |
| Acer Aspire A515-51                         | 42        | 0.74%   |
| HP G42                                      | 38        | 0.67%   |
| Acer Nitro AN515-52                         | 35        | 0.62%   |
| Dell Inspiron 3421                          | 34        | 0.6%    |
| Lenovo IdeaPad 320-15IKB 80YH               | 32        | 0.57%   |
| Positivo S14CT01                            | 30        | 0.53%   |
| Itautec Infoway                             | 30        | 0.53%   |
| Dell Inspiron N4050                         | 30        | 0.53%   |
| Dell Inspiron 3442                          | 30        | 0.53%   |
| HP Pavilion g4                              | 29        | 0.51%   |
| Dell Inspiron 7520                          | 29        | 0.51%   |
| Samsung 300E5M/300E5L                       | 28        | 0.5%    |
| Dell Inspiron 1545                          | 28        | 0.5%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 27        | 0.48%   |
| Acer Aspire E1-571                          | 27        | 0.48%   |
| Dell Inspiron 5437                          | 26        | 0.46%   |
| Digibras NH4CU53                            | 25        | 0.44%   |
| Digibras NH4CU03                            | 25        | 0.44%   |
| Acer Aspire E5-571                          | 25        | 0.44%   |
| Dell Inspiron 5458                          | 24        | 0.42%   |
| Dell Inspiron 1525                          | 24        | 0.42%   |
| Dell G3 3590                                | 24        | 0.42%   |
| Acer Aspire A515-54G                        | 24        | 0.42%   |
| Dell Inspiron 5423                          | 23        | 0.41%   |
| Dell Inspiron 15 7000 Gaming                | 23        | 0.41%   |
| Acer Nitro AN515-51                         | 23        | 0.41%   |
| Acer Aspire A515-51G                        | 23        | 0.41%   |
| Dell Inspiron 5557                          | 22        | 0.39%   |
| Dell Inspiron 7560                          | 21        | 0.37%   |
| Dell Inspiron 5537                          | 21        | 0.37%   |
| Samsung 370E4K                              | 20        | 0.35%   |
| Samsung 270E5J/2570EJ                       | 20        | 0.35%   |
| Positivo H14BT58                            | 20        | 0.35%   |
| Samsung 300E4C/300E5C/300E7C                | 19        | 0.34%   |
| Positivo Q232A                              | 19        | 0.34%   |
| Dell Vostro 5490                            | 19        | 0.34%   |
| Dell Vostro 5470                            | 19        | 0.34%   |
| Positivo CHT14B                             | 18        | 0.32%   |
| HP Pavilion dv4                             | 18        | 0.32%   |
| Dell Inspiron 5548                          | 18        | 0.32%   |
| Dell Inspiron 5448                          | 18        | 0.32%   |
| Acer Aspire ES1-572                         | 18        | 0.32%   |
| Acer Aspire E1-572                          | 18        | 0.32%   |
| Acer Aspire A315-54                         | 18        | 0.32%   |
| Samsung 550XBE/350XBE                       | 17        | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Dell Inspiron               | 889       | 15.72%  |
| Acer Aspire                 | 754       | 13.33%  |
| Lenovo IdeaPad              | 359       | 6.35%   |
| Acer Nitro                  | 334       | 5.91%   |
| HP Pavilion                 | 172       | 3.04%   |
| Dell Vostro                 | 165       | 2.92%   |
| Lenovo ThinkPad             | 164       | 2.9%    |
| Dell Latitude               | 132       | 2.33%   |
| Positivo Mobile             | 113       | 2%      |
| Unknown                     | 84        | 1.49%   |
| Itautec Infoway             | 60        | 1.06%   |
| Samsung 340XAA              | 58        | 1.03%   |
| ASUS VivoBook               | 54        | 0.95%   |
| Dell G3                     | 44        | 0.78%   |
| HP ProBook                  | 38        | 0.67%   |
| HP G42                      | 38        | 0.67%   |
| Samsung RV411               | 37        | 0.65%   |
| Dell XPS                    | 32        | 0.57%   |
| HP EliteBook                | 31        | 0.55%   |
| Positivo S14CT01            | 30        | 0.53%   |
| Samsung 300E5M              | 28        | 0.5%    |
| Toshiba Satellite           | 27        | 0.48%   |
| Semp Toshiba IS             | 27        | 0.48%   |
| Acer Predator               | 26        | 0.46%   |
| Digibras NH4CU53            | 25        | 0.44%   |
| Digibras NH4CU03            | 25        | 0.44%   |
| Compaq Presario             | 23        | 0.41%   |
| Samsung RV415               | 22        | 0.39%   |
| Samsung 370E4K              | 20        | 0.35%   |
| Samsung 300E5EV             | 20        | 0.35%   |
| Samsung 270E5J              | 20        | 0.35%   |
| Positivo H14BT58            | 20        | 0.35%   |
| Samsung 300E4C              | 19        | 0.34%   |
| Positivo Q232A              | 19        | 0.34%   |
| Positivo CHT14B             | 18        | 0.32%   |
| Lenovo G400s                | 18        | 0.32%   |
| HP Compaq                   | 18        | 0.32%   |
| Samsung 550XBE              | 17        | 0.3%    |
| HP ENVY                     | 17        | 0.3%    |
| Positivo S14SL01            | 16        | 0.28%   |
| Samsung 270E5G              | 15        | 0.27%   |
| Positivo C14CR21            | 15        | 0.27%   |
| Apple MacBookPro8           | 15        | 0.27%   |
| Samsung 550XDA              | 14        | 0.25%   |
| Samsung 550XCJ              | 14        | 0.25%   |
| Lenovo G40-80               | 14        | 0.25%   |
| Samsung RF511               | 13        | 0.23%   |
| Samsung 300E5K              | 13        | 0.23%   |
| Philco 14I                  | 13        | 0.23%   |
| Lenovo G40-70               | 13        | 0.23%   |
| Samsung 550P5C              | 12        | 0.21%   |
| Positivo S14BW01            | 12        | 0.21%   |
| Lenovo Legion               | 12        | 0.21%   |
| HP 14                       | 12        | 0.21%   |
| Avell High Performance B.ON | 12        | 0.21%   |
| Positivo C14CU51            | 11        | 0.19%   |
| Intel Infoway               | 11        | 0.19%   |
| Intel HuronRiver            | 11        | 0.19%   |
| HP Presario                 | 11        | 0.19%   |
| Apple MacBookPro9           | 11        | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 796       | 14.08%  |
| 2012    | 611       | 10.8%   |
| 2011    | 552       | 9.76%   |
| 2018    | 522       | 9.23%   |
| 2013    | 457       | 8.08%   |
| 2017    | 425       | 7.52%   |
| 2016    | 421       | 7.44%   |
| 2010    | 368       | 6.51%   |
| 2014    | 304       | 5.38%   |
| 2015    | 285       | 5.04%   |
| 2020    | 248       | 4.39%   |
| 2008    | 221       | 3.91%   |
| 2009    | 193       | 3.41%   |
| 2021    | 107       | 1.89%   |
| 2007    | 78        | 1.38%   |
| 2006    | 31        | 0.55%   |
| Unknown | 22        | 0.39%   |
| 2005    | 9         | 0.16%   |
| 2004    | 4         | 0.07%   |
| 2022    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5655      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4785      | 84.05%  |
| Enabled  | 908       | 15.95%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5640      | 99.73%  |
| Yes  | 15        | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1850      | 32.31%  |
| 3.01-4.0    | 1634      | 28.54%  |
| 8.01-16.0   | 792       | 13.83%  |
| 16.01-24.0  | 702       | 12.26%  |
| 1.01-2.0    | 461       | 8.05%   |
| 2.01-3.0    | 152       | 2.66%   |
| 32.01-64.0  | 70        | 1.22%   |
| 0.51-1.0    | 28        | 0.49%   |
| 24.01-32.0  | 19        | 0.33%   |
| 64.01-256.0 | 16        | 0.28%   |
| 0.01-0.5    | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2335      | 37.61%  |
| 2.01-3.0   | 1759      | 28.33%  |
| 3.01-4.0   | 799       | 12.87%  |
| 4.01-8.0   | 681       | 10.97%  |
| 0.51-1.0   | 470       | 7.57%   |
| 8.01-16.0  | 117       | 1.88%   |
| 0.01-0.5   | 39        | 0.63%   |
| 16.01-24.0 | 4         | 0.06%   |
| Unknown    | 3         | 0.05%   |
| 32.01-64.0 | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4019      | 70.03%  |
| 2      | 1563      | 27.23%  |
| 3      | 108       | 1.88%   |
| 0      | 42        | 0.73%   |
| 4      | 7         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3338      | 58.78%  |
| Yes       | 2341      | 41.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5130      | 90.57%  |
| No        | 534       | 9.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5481      | 96.77%  |
| No        | 183       | 3.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3984      | 69.87%  |
| No        | 1718      | 30.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 5655      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 617       | 10.34%  |
| Rio de Janeiro            | 314       | 5.26%   |
| Curitiba                  | 181       | 3.03%   |
| Belo Horizonte            | 171       | 2.87%   |
| BrasГ­lia               | 143       | 2.4%    |
| Fortaleza                 | 126       | 2.11%   |
| Porto Alegre              | 123       | 2.06%   |
| Salvador                  | 89        | 1.49%   |
| Campinas                  | 85        | 1.42%   |
| Recife                    | 82        | 1.37%   |
| Osasco                    | 57        | 0.96%   |
| Natal                     | 56        | 0.94%   |
| GoiГўnia                | 56        | 0.94%   |
| BrasÃ­lia               | 50        | 0.84%   |
| Guarulhos                 | 47        | 0.79%   |
| Manaus                    | 45        | 0.75%   |
| Santo AndrГ©            | 44        | 0.74%   |
| Campo Grande              | 43        | 0.72%   |
| FlorianГіpolis          | 42        | 0.7%    |
| Teresina                  | 41        | 0.69%   |
| Sorocaba                  | 39        | 0.65%   |
| Joinville                 | 38        | 0.64%   |
| Aracaju                   | 36        | 0.6%    |
| SГЈo JosГ© dos Campos | 33        | 0.55%   |
| VitГіria                | 32        | 0.54%   |
| SГЈo LuГ­s            | 31        | 0.52%   |
| BelГ©m                  | 30        | 0.5%    |
| Juiz de Fora              | 29        | 0.49%   |
| NiterГіi                | 28        | 0.47%   |
| JoГЈo Pessoa            | 28        | 0.47%   |
| Londrina                  | 27        | 0.45%   |
| UberlГўndia             | 26        | 0.44%   |
| Sao Jose                  | 26        | 0.44%   |
| FlorianÃ³polis          | 26        | 0.44%   |
| Santo AndrÃ©            | 24        | 0.4%    |
| Canoas                    | 24        | 0.4%    |
| Blumenau                  | 24        | 0.4%    |
| SГЈo Carlos             | 22        | 0.37%   |
| Porto Velho               | 22        | 0.37%   |
| MaringГЎ                | 22        | 0.37%   |
| Santos                    | 21        | 0.35%   |
| JundiaГ­                | 20        | 0.34%   |
| GoiÃ¢nia                | 20        | 0.34%   |
| Duque de Caxias           | 20        | 0.34%   |
| BelÃ©m                  | 20        | 0.34%   |
| SГЈo Bernardo do Campo  | 19        | 0.32%   |
| Sao Vicente               | 19        | 0.32%   |
| SÃ£o JosÃ© dos Campos | 18        | 0.3%    |
| RibeirГЈo Preto         | 18        | 0.3%    |
| Campina Grande            | 18        | 0.3%    |
| UberlÃ¢ndia             | 17        | 0.28%   |
| Taubate                   | 17        | 0.28%   |
| Sao Goncalo               | 17        | 0.28%   |
| Presidente Prudente       | 17        | 0.28%   |
| Piracicaba                | 17        | 0.28%   |
| Petrolina                 | 17        | 0.28%   |
| MaceiГі                 | 17        | 0.28%   |
| Americana                 | 17        | 0.28%   |
| Volta Redonda             | 16        | 0.27%   |
| Palmas                    | 16        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 1658      | 2017   | 23.86%  |
| Seagate                        | 1141      | 1368   | 16.42%  |
| Kingston                       | 647       | 785    | 9.31%   |
| Toshiba                        | 524       | 602    | 7.54%   |
| Samsung Electronics            | 518       | 655    | 7.45%   |
| SanDisk                        | 393       | 513    | 5.66%   |
| Unknown                        | 310       | 417    | 4.46%   |
| Intel                          | 248       | 292    | 3.57%   |
| A-DATA Technology              | 243       | 303    | 3.5%    |
| Hitachi                        | 171       | 214    | 2.46%   |
| Crucial                        | 117       | 158    | 1.68%   |
| China                          | 90        | 108    | 1.3%    |
| ADATA Technology               | 89        | 110    | 1.28%   |
| LITEON                         | 87        | 100    | 1.25%   |
| HGST                           | 85        | 101    | 1.22%   |
| SK Hynix                       | 75        | 102    | 1.08%   |
| Silicon Motion                 | 44        | 49     | 0.63%   |
| Fujitsu                        | 37        | 46     | 0.53%   |
| KingSpec                       | 36        | 40     | 0.52%   |
| Apple                          | 28        | 35     | 0.4%    |
| JMicron                        | 25        | 30     | 0.36%   |
| Lexar                          | 24        | 31     | 0.35%   |
| Corsair                        | 23        | 23     | 0.33%   |
| Solid State Storage Technology | 19        | 24     | 0.27%   |
| Phison                         | 18        | 20     | 0.26%   |
| SSSTC                          | 17        | 17     | 0.24%   |
| SMART                          | 17        | 18     | 0.24%   |
| Realtek Semiconductor          | 14        | 18     | 0.2%    |
| PNY                            | 14        | 20     | 0.2%    |
| KIOXIA                         | 13        | 16     | 0.19%   |
| Hewlett-Packard                | 13        | 16     | 0.19%   |
| Netac                          | 12        | 13     | 0.17%   |
| LITEONIT                       | 12        | 17     | 0.17%   |
| KingDian                       | 12        | 18     | 0.17%   |
| XPG                            | 11        | 14     | 0.16%   |
| Patriot                        | 11        | 11     | 0.16%   |
| Solid State Storage            | 10        | 10     | 0.14%   |
| Micron Technology              | 10        | 11     | 0.14%   |
| Gigabyte Technology            | 10        | 13     | 0.14%   |
| Unknown                        | 10        | 10     | 0.14%   |
| Micron/Crucial Technology      | 8         | 9      | 0.12%   |
| XrayDisk                       | 7         | 9      | 0.1%    |
| Lite-On                        | 7         | 8      | 0.1%    |
| BHT                            | 5         | 5      | 0.07%   |
| MAXTOR                         | 4         | 4      | 0.06%   |
| HS-SSD-C100                    | 4         | 8      | 0.06%   |
| Vaseky                         | 3         | 3      | 0.04%   |
| Union Memory                   | 3         | 3      | 0.04%   |
| Transcend                      | 3         | 3      | 0.04%   |
| PLEXTOR                        | 3         | 3      | 0.04%   |
| OCZ                            | 3         | 3      | 0.04%   |
| JASTER                         | 3         | 4      | 0.04%   |
| Dell                           | 3         | 3      | 0.04%   |
| TSA                            | 2         | 2      | 0.03%   |
| TO Exter                       | 2         | 3      | 0.03%   |
| SPCC                           | 2         | 2      | 0.03%   |
| Ramsta                         | 2         | 2      | 0.03%   |
| Pichau                         | 2         | 2      | 0.03%   |
| KingFast                       | 2         | 6      | 0.03%   |
| KINGBANK                       | 2         | 2      | 0.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 434       | 6.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 230       | 3.23%   |
| Kingston SA400S37240G 240GB SSD     | 227       | 3.18%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 189       | 2.65%   |
| Toshiba MQ01ABD100 1TB              | 112       | 1.57%   |
| Kingston SA400S37480G 480GB SSD     | 112       | 1.57%   |
| Kingston SA400S37120G 120GB SSD     | 106       | 1.49%   |
| WDC WD10SPZX-24Z10 1TB              | 103       | 1.44%   |
| Intel NVMe SSD Drive 512GB          | 96        | 1.35%   |
| Unknown MMC Card  32GB              | 93        | 1.3%    |
| A-DATA IM2S3338-128GD2 128GB SSD    | 86        | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB      | 82        | 1.15%   |
| WDC WD10JPVX-22JC3T0 1TB            | 77        | 1.08%   |
| Samsung HM321HI 320GB               | 70        | 0.98%   |
| WDC WD10SPZX-75Z10T2 1TB            | 69        | 0.97%   |
| Intel NVMe SSD Drive 128GB          | 67        | 0.94%   |
| Seagate ST9500325AS 500GB           | 63        | 0.88%   |
| Toshiba MQ04ABF100 1TB              | 56        | 0.79%   |
| SanDisk SSD PLUS 240GB              | 56        | 0.79%   |
| Sandisk NVMe SSD Drive 512GB        | 55        | 0.77%   |
| WDC WD10JPVX-75JC3T0 1TB            | 51        | 0.72%   |
| Kingston SV300S37A120G 120GB SSD    | 51        | 0.72%   |
| SanDisk SSD PLUS 120GB              | 50        | 0.7%    |
| Toshiba MQ01ABF050 500GB            | 47        | 0.66%   |
| Seagate Expansion+ 2TB              | 47        | 0.66%   |
| Seagate ST2000LM007-1R8174 2TB      | 46        | 0.65%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 44        | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 43        | 0.6%    |
| Seagate ST500LT012-9WS142 500GB     | 43        | 0.6%    |
| ADATA NVMe SSD Drive 256GB          | 43        | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 42        | 0.59%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 40        | 0.56%   |
| Intel SSDPEKKW256G7 256GB           | 40        | 0.56%   |
| WDC WD10JPCX-24UE4T0 1TB            | 38        | 0.53%   |
| WDC WD10SPZX-75Z10T1 1TB            | 36        | 0.5%    |
| Seagate ST1000LM014-1EJ164 1TB      | 36        | 0.5%    |
| Toshiba MQ01ABD050 500GB            | 35        | 0.49%   |
| SanDisk SDSSDA240G 240GB            | 35        | 0.49%   |
| Unknown NVMe SSD Drive 256GB        | 34        | 0.48%   |
| Seagate ST500LT012-1DG142 500GB     | 32        | 0.45%   |
| Crucial CT240BX500SSD1 240GB        | 31        | 0.43%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 29        | 0.41%   |
| SK Hynix NVMe SSD Drive 256GB       | 29        | 0.41%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 28        | 0.39%   |
| Seagate ST1000LM048-2E7172 1TB      | 28        | 0.39%   |
| Samsung MZMPC032HBCD-000D1 32GB SSD | 28        | 0.39%   |
| WDC WD10SPZX-24Z10T0 1TB            | 27        | 0.38%   |
| SanDisk SSD PLUS 480GB              | 27        | 0.38%   |
| Samsung HM160HI 160GB               | 27        | 0.38%   |
| Hitachi HTS547550A9E384 500GB       | 26        | 0.36%   |
| Unknown MMC Card  16GB              | 25        | 0.35%   |
| Toshiba MQ02ABD100H 1TB             | 25        | 0.35%   |
| Samsung HM500JI 500GB               | 25        | 0.35%   |
| ADATA NVMe SSD Drive 128GB          | 25        | 0.35%   |
| Seagate ST9500420AS 500GB           | 24        | 0.34%   |
| Seagate ST9320325AS 320GB           | 23        | 0.32%   |
| Kingston SV300S37A240G 240GB SSD    | 23        | 0.32%   |
| Crucial CT480BX500SSD1 480GB        | 23        | 0.32%   |
| Unknown MMC Card  64GB              | 22        | 0.31%   |
| Samsung HN-M500MBB 500GB            | 22        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1498      | 1754   | 40.43%  |
| Seagate             | 1136      | 1361   | 30.66%  |
| Toshiba             | 494       | 571    | 13.33%  |
| Samsung Electronics | 255       | 294    | 6.88%   |
| Hitachi             | 171       | 214    | 4.62%   |
| HGST                | 85        | 101    | 2.29%   |
| Fujitsu             | 36        | 44     | 0.97%   |
| Unknown             | 12        | 14     | 0.32%   |
| Apple               | 10        | 13     | 0.27%   |
| JMicron             | 2         | 2      | 0.05%   |
| sage                | 1         | 1      | 0.03%   |
| Maxtor 6            | 1         | 1      | 0.03%   |
| MAXTOR              | 1         | 1      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 2      | 0.03%   |
| CLOVER              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 624       | 752    | 30.42%  |
| SanDisk             | 279       | 386    | 13.6%   |
| Samsung Electronics | 189       | 259    | 9.22%   |
| A-DATA Technology   | 166       | 202    | 8.09%   |
| WDC                 | 165       | 204    | 8.04%   |
| Crucial             | 112       | 150    | 5.46%   |
| China               | 90        | 108    | 4.39%   |
| LITEON              | 79        | 92     | 3.85%   |
| KingSpec            | 35        | 39     | 1.71%   |
| Lexar               | 24        | 31     | 1.17%   |
| Intel               | 21        | 25     | 1.02%   |
| JMicron             | 19        | 24     | 0.93%   |
| Corsair             | 19        | 19     | 0.93%   |
| SMART               | 17        | 18     | 0.83%   |
| Apple               | 17        | 20     | 0.83%   |
| Unknown             | 14        | 16     | 0.68%   |
| PNY                 | 14        | 20     | 0.68%   |
| SK Hynix            | 12        | 15     | 0.59%   |
| Netac               | 12        | 13     | 0.59%   |
| LITEONIT            | 12        | 17     | 0.59%   |
| KingDian            | 11        | 17     | 0.54%   |
| Patriot             | 10        | 10     | 0.49%   |
| Gigabyte Technology | 10        | 13     | 0.49%   |
| Hewlett-Packard     | 9         | 11     | 0.44%   |
| Toshiba             | 8         | 9      | 0.39%   |
| Micron Technology   | 7         | 8      | 0.34%   |
| Unknown             | 7         | 7      | 0.34%   |
| Seagate             | 6         | 6      | 0.29%   |
| BHT                 | 5         | 5      | 0.24%   |
| XrayDisk            | 3         | 4      | 0.15%   |
| Transcend           | 3         | 3      | 0.15%   |
| PLEXTOR             | 3         | 3      | 0.15%   |
| OCZ                 | 3         | 3      | 0.15%   |
| MAXTOR              | 3         | 3      | 0.15%   |
| Vaseky              | 2         | 2      | 0.1%    |
| TSA                 | 2         | 2      | 0.1%    |
| TO Exter            | 2         | 3      | 0.1%    |
| Ramsta              | 2         | 2      | 0.1%    |
| Pichau              | 2         | 2      | 0.1%    |
| KINGBANK            | 2         | 2      | 0.1%    |
| HS-SSD-C100         | 2         | 2      | 0.1%    |
| Dell                | 2         | 2      | 0.1%    |
| Zheino              | 1         | 1      | 0.05%   |
| WANGCHU             | 1         | 1      | 0.05%   |
| Team                | 1         | 1      | 0.05%   |
| SuperSSpeed         | 1         | 1      | 0.05%   |
| Super Talent        | 1         | 1      | 0.05%   |
| SPCC                | 1         | 1      | 0.05%   |
| S3+                 | 1         | 1      | 0.05%   |
| RZX                 | 1         | 1      | 0.05%   |
| Mushkin             | 1         | 1      | 0.05%   |
| Kross Elegance      | 1         | 1      | 0.05%   |
| JASTER              | 1         | 1      | 0.05%   |
| Intenso             | 1         | 1      | 0.05%   |
| INTEL SS            | 1         | 1      | 0.05%   |
| imation             | 1         | 1      | 0.05%   |
| HUSKY               | 1         | 1      | 0.05%   |
| HEORIADY            | 1         | 1      | 0.05%   |
| GLOWAY              | 1         | 1      | 0.05%   |
| Fujitsu             | 1         | 2      | 0.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3648      | 4375   | 53.88%  |
| SSD     | 1915      | 2559   | 28.28%  |
| NVMe    | 926       | 1164   | 13.68%  |
| MMC     | 241       | 346    | 3.56%   |
| Unknown | 41        | 52     | 0.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4933      | 6829   | 79.28%  |
| NVMe | 926       | 1164   | 14.88%  |
| MMC  | 241       | 346    | 3.87%   |
| SAS  | 122       | 157    | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3441      | 4539   | 63.36%  |
| 0.51-1.0   | 1845      | 2206   | 33.97%  |
| 1.01-2.0   | 138       | 181    | 2.54%   |
| 3.01-4.0   | 4         | 4      | 0.07%   |
| 2.01-3.0   | 3         | 4      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1735      | 29.39%  |
| 251-500        | 1561      | 26.44%  |
| 501-1000       | 1106      | 18.74%  |
| 51-100         | 375       | 6.35%   |
| 1-20           | 371       | 6.28%   |
| 21-50          | 299       | 5.07%   |
| 1001-2000      | 289       | 4.9%    |
| Unknown        | 78        | 1.32%   |
| 2001-3000      | 51        | 0.86%   |
| More than 3000 | 38        | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2347      | 38.45%  |
| 21-50          | 1465      | 24%     |
| 51-100         | 800       | 13.11%  |
| 101-250        | 785       | 12.86%  |
| 251-500        | 378       | 6.19%   |
| 501-1000       | 177       | 2.9%    |
| Unknown        | 78        | 1.28%   |
| 1001-2000      | 60        | 0.98%   |
| 2001-3000      | 9         | 0.15%   |
| More than 3000 | 5         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB   | 24        | 25     | 7.16%   |
| Seagate ST9500325AS 500GB            | 17        | 19     | 5.07%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 14        | 15     | 4.18%   |
| Seagate ST1000LM035-1RK172 1TB       | 10        | 10     | 2.99%   |
| Toshiba MQ01ABD100 1TB               | 8         | 8      | 2.39%   |
| Toshiba MQ02ABD100H 1TB              | 6         | 10     | 1.79%   |
| Toshiba MQ01ABF050 500GB             | 6         | 6      | 1.79%   |
| Seagate ST9320325AS 320GB            | 6         | 6      | 1.79%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 5         | 6      | 1.49%   |
| Seagate ST500LT012-9WS142 500GB      | 5         | 7      | 1.49%   |
| Samsung Electronics HM321HI 320GB    | 5         | 5      | 1.49%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 5      | 1.49%   |
| Hitachi HTS547550A9E384 500GB        | 5         | 5      | 1.49%   |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 4      | 1.19%   |
| Toshiba MQ01ABD050 500GB             | 4         | 4      | 1.19%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 4      | 1.19%   |
| Samsung Electronics HM160HI 160GB    | 4         | 4      | 1.19%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 3         | 3      | 0.9%    |
| WDC WD3200BPVT-00JJ5T0 320GB         | 3         | 4      | 0.9%    |
| Toshiba MQ01ACF050 500GB             | 3         | 3      | 0.9%    |
| Toshiba MQ01ABD032 320GB             | 3         | 3      | 0.9%    |
| Toshiba MK3259GSXP 320GB             | 3         | 3      | 0.9%    |
| Seagate ST9500423AS 500GB            | 3         | 3      | 0.9%    |
| Seagate ST9320423AS 320GB            | 3         | 3      | 0.9%    |
| Seagate ST9250410AS 250GB            | 3         | 3      | 0.9%    |
| Seagate ST9160314AS 160GB            | 3         | 4      | 0.9%    |
| Seagate ST500LT012-1DG142 500GB      | 3         | 4      | 0.9%    |
| Seagate ST500LM030-2E717D 500GB      | 3         | 3      | 0.9%    |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.9%    |
| Seagate ST1000LM014-1EJ164 1TB       | 3         | 3      | 0.9%    |
| SanDisk SSD PLUS 240GB               | 3         | 3      | 0.9%    |
| Samsung Electronics HM250HI 250GB    | 3         | 3      | 0.9%    |
| Kingston SA400S37240G 240GB SSD      | 3         | 3      | 0.9%    |
| Hitachi HTS545050A7E380 500GB        | 3         | 4      | 0.9%    |
| Hitachi HTS545025B9A300 250GB        | 3         | 3      | 0.9%    |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 2      | 0.6%    |
| WDC WD3200BPVT-24JJ5T0 320GB         | 2         | 2      | 0.6%    |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 2      | 0.6%    |
| WDC WD3200BEKT-60V5T1 320GB          | 2         | 5      | 0.6%    |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 3      | 0.6%    |
| WDC WD10SPZX-24Z10 1TB               | 2         | 2      | 0.6%    |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 2      | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 2      | 0.6%    |
| Toshiba MK7575GSX 752GB              | 2         | 3      | 0.6%    |
| Toshiba MK6465GSX 640GB              | 2         | 2      | 0.6%    |
| Toshiba MK5065GSXF 500GB             | 2         | 2      | 0.6%    |
| Toshiba MK5061GSYN 500GB             | 2         | 2      | 0.6%    |
| Toshiba MK5059GSXP 500GB             | 2         | 2      | 0.6%    |
| Toshiba MK2555GSX 250GB              | 2         | 2      | 0.6%    |
| Seagate ST9250315AS 250GB            | 2         | 2      | 0.6%    |
| SanDisk SSD PLUS 480GB               | 2         | 2      | 0.6%    |
| Samsung Electronics HN-M500MBB 500GB | 2         | 2      | 0.6%    |
| Samsung Electronics HM500JI 500GB    | 2         | 2      | 0.6%    |
| Samsung Electronics HM320JI 320GB    | 2         | 3      | 0.6%    |
| LITEON CV8-8E256-HP 256GB SSD        | 2         | 2      | 0.6%    |
| Kingston SUV400S37240G 240GB SSD     | 2         | 4      | 0.6%    |
| Kingston SA400S37480G 480GB SSD      | 2         | 2      | 0.6%    |
| Hitachi HTS547575A9E384 752GB        | 2         | 2      | 0.6%    |
| Hitachi HTS545050B9A300 500GB        | 2         | 2      | 0.6%    |
| XPG GAMMIX S11 Pro 512GB             | 1         | 1      | 0.3%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 120       | 130    | 36.14%  |
| WDC                 | 59        | 66     | 17.77%  |
| Toshiba             | 57        | 64     | 17.17%  |
| Hitachi             | 24        | 25     | 7.23%   |
| Samsung Electronics | 22        | 28     | 6.63%   |
| Kingston            | 14        | 18     | 4.22%   |
| SanDisk             | 8         | 8      | 2.41%   |
| Fujitsu             | 4         | 5      | 1.2%    |
| A-DATA Technology   | 4         | 4      | 1.2%    |
| Intel               | 3         | 3      | 0.9%    |
| China               | 3         | 3      | 0.9%    |
| PNY                 | 2         | 2      | 0.6%    |
| LITEON              | 2         | 2      | 0.6%    |
| HGST                | 2         | 2      | 0.6%    |
| Crucial             | 2         | 2      | 0.6%    |
| Apple               | 2         | 2      | 0.6%    |
| XPG                 | 1         | 1      | 0.3%    |
| OCZ                 | 1         | 1      | 0.3%    |
| Micron Technology   | 1         | 1      | 0.3%    |
| LITEONIT            | 1         | 2      | 0.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 120       | 130    | 42.4%   |
| WDC                 | 56        | 63     | 19.79%  |
| Toshiba             | 56        | 63     | 19.79%  |
| Hitachi             | 24        | 25     | 8.48%   |
| Samsung Electronics | 20        | 26     | 7.07%   |
| Fujitsu             | 4         | 5      | 1.41%   |
| HGST                | 2         | 2      | 0.71%   |
| Apple               | 1         | 1      | 0.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 283       | 315    | 85.24%  |
| SSD  | 43        | 48     | 12.95%  |
| NVMe | 6         | 6      | 1.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 11.11%  |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 11.11%  |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 11.11%  |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 11.11%  |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 11.11%  |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 11.11%  |
| Samsung Electronics HM321HI 320GB                | 1         | 1      | 11.11%  |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 11.11%  |
| MAXTOR STM380215AS 80GB                          | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 33.33%  |
| WDC                 | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| MAXTOR              | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4236      | 6340   | 72.3%   |
| Works    | 1286      | 1778   | 21.95%  |
| Malfunc  | 328       | 369    | 5.6%    |
| Failed   | 9         | 9      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4768      | 77.69%  |
| AMD                              | 497       | 8.1%    |
| ADATA Technology                 | 182       | 2.97%   |
| Sandisk                          | 136       | 2.22%   |
| Samsung Electronics              | 94        | 1.53%   |
| Silicon Integrated Systems [SiS] | 88        | 1.43%   |
| Solid State Storage Technology   | 61        | 0.99%   |
| SK Hynix                         | 59        | 0.96%   |
| Silicon Motion                   | 48        | 0.78%   |
| Nvidia                           | 28        | 0.46%   |
| Kingston Technology Company      | 25        | 0.41%   |
| VIA Technologies                 | 23        | 0.37%   |
| Realtek Semiconductor            | 23        | 0.37%   |
| Phison Electronics               | 23        | 0.37%   |
| Toshiba America Info Systems     | 21        | 0.34%   |
| Lite-On Technology               | 15        | 0.24%   |
| Micron/Crucial Technology        | 14        | 0.23%   |
| KIOXIA                           | 13        | 0.21%   |
| Union Memory (Shenzhen)          | 5         | 0.08%   |
| Marvell Technology Group         | 4         | 0.07%   |
| Micron Technology                | 3         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.03%   |
| Apple                            | 2         | 0.03%   |
| Seagate Technology               | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| Beijing Starblaze Technology     | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 800       | 11.75%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 661       | 9.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 545       | 8.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 383       | 5.63%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 335       | 4.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 310       | 4.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 258       | 3.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 252       | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 203       | 2.98%   |
| Intel PROSet/Wireless WiFi Software extension                                          | 197       | 2.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 165       | 2.42%   |
| ADATA Non-Volatile memory controller                                                   | 163       | 2.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 124       | 1.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 123       | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 120       | 1.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 107       | 1.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 103       | 1.51%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 99        | 1.45%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 87        | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 85        | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 78        | 1.15%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 73        | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 63        | 0.93%   |
| Solid State Storage Non-Volatile memory controller                                     | 61        | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 59        | 0.87%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 57        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 57        | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 53        | 0.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 53        | 0.78%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 51        | 0.75%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 51        | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 46        | 0.68%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 45        | 0.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 38        | 0.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 37        | 0.54%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 35        | 0.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 30        | 0.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 30        | 0.44%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 29        | 0.43%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 29        | 0.43%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 28        | 0.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 24        | 0.35%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 23        | 0.34%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 23        | 0.34%   |
| Sandisk PC SN520 NVMe SSD                                                              | 23        | 0.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 23        | 0.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 20        | 0.29%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 19        | 0.28%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 19        | 0.28%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 18        | 0.26%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 18        | 0.26%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 16        | 0.24%   |
| SK Hynix BC511                                                                         | 15        | 0.22%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 14        | 0.21%   |
| Samsung NVMe SSD Controller 980                                                        | 14        | 0.21%   |
| Intel SSD 660P Series                                                                  | 14        | 0.21%   |
| Realtek Realtek Non-Volatile memory controller                                         | 13        | 0.19%   |
| Phison E12 NVMe Controller                                                             | 13        | 0.19%   |
| KIOXIA Non-Volatile memory controller                                                  | 13        | 0.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 13        | 0.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4598      | 70.27%  |
| NVMe | 932       | 14.24%  |
| RAID | 524       | 8.01%   |
| IDE  | 489       | 7.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 5125      | 90.63%  |
| AMD    | 527       | 9.32%   |
| ARM    | 3         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 198       | 3.5%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 153       | 2.71%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 121       | 2.14%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 112       | 1.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 108       | 1.91%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 105       | 1.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 105       | 1.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 105       | 1.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 101       | 1.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 96        | 1.7%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 81        | 1.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 75        | 1.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 74        | 1.31%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 74        | 1.31%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 74        | 1.31%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 72        | 1.27%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 71        | 1.26%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 69        | 1.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 68        | 1.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 65        | 1.15%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 65        | 1.15%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 63        | 1.11%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 62        | 1.1%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 60        | 1.06%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 59        | 1.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 57        | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 57        | 1.01%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 56        | 0.99%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 53        | 0.94%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 52        | 0.92%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 51        | 0.9%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 49        | 0.87%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 48        | 0.85%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 48        | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 44        | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 44        | 0.78%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 42        | 0.74%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 41        | 0.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 39        | 0.69%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 39        | 0.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 39        | 0.69%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 38        | 0.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 37        | 0.65%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 37        | 0.65%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 36        | 0.64%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 36        | 0.64%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 35        | 0.62%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 35        | 0.62%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 34        | 0.6%    |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 34        | 0.6%    |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 33        | 0.58%   |
| AMD C-60 APU with Radeon HD Graphics          | 33        | 0.58%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 32        | 0.57%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 31        | 0.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 31        | 0.55%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 30        | 0.53%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 29        | 0.51%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 29        | 0.51%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 29        | 0.51%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 29        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 1727      | 30.53%  |
| Intel Core i7                        | 1202      | 21.25%  |
| Intel Core i3                        | 892       | 15.77%  |
| Intel Celeron                        | 412       | 7.28%   |
| Intel Core 2 Duo                     | 225       | 3.98%   |
| Intel Atom                           | 195       | 3.45%   |
| Intel Pentium Dual-Core              | 125       | 2.21%   |
| AMD Ryzen 5                          | 118       | 2.09%   |
| Intel Pentium                        | 108       | 1.91%   |
| Other                                | 100       | 1.77%   |
| AMD Ryzen 7                          | 94        | 1.66%   |
| Intel Pentium Dual                   | 63        | 1.11%   |
| AMD E                                | 45        | 0.8%    |
| AMD C-60                             | 35        | 0.62%   |
| AMD E1                               | 28        | 0.5%    |
| AMD A4                               | 26        | 0.46%   |
| Intel Genuine                        | 24        | 0.42%   |
| AMD A6                               | 23        | 0.41%   |
| AMD C-70                             | 21        | 0.37%   |
| AMD A10                              | 19        | 0.34%   |
| Intel Core 2                         | 17        | 0.3%    |
| Intel Celeron Dual-Core              | 14        | 0.25%   |
| AMD C-50                             | 14        | 0.25%   |
| AMD Mobile Sempron                   | 12        | 0.21%   |
| Intel Celeron M                      | 11        | 0.19%   |
| AMD Ryzen 3                          | 11        | 0.19%   |
| AMD Athlon II                        | 9         | 0.16%   |
| AMD A12                              | 9         | 0.16%   |
| AMD Turion X2 Dual-Core Mobile       | 5         | 0.09%   |
| AMD Turion II                        | 5         | 0.09%   |
| AMD Turion 64 Mobile                 | 5         | 0.09%   |
| Intel Pentium M                      | 4         | 0.07%   |
| AMD Turion 64 X2 Mobile              | 4         | 0.07%   |
| AMD Phenom II                        | 4         | 0.07%   |
| AMD Athlon 64 X2                     | 4         | 0.07%   |
| AMD A8                               | 4         | 0.07%   |
| ARM ARMv7                            | 3         | 0.05%   |
| AMD V120                             | 3         | 0.05%   |
| AMD Ryzen 7 PRO                      | 3         | 0.05%   |
| Intel Pentium Gold                   | 2         | 0.04%   |
| Intel Core i9                        | 2         | 0.04%   |
| Intel Core 2 Solo                    | 2         | 0.04%   |
| AMD Turion Neo X2                    | 2         | 0.04%   |
| AMD Turion 64 X2                     | 2         | 0.04%   |
| AMD E2                               | 2         | 0.04%   |
| AMD Athlon X2                        | 2         | 0.04%   |
| AMD Athlon II Dual-Core              | 2         | 0.04%   |
| AMD Athlon                           | 2         | 0.04%   |
| Intel Pentium 4                      | 1         | 0.02%   |
| Intel Core m7                        | 1         | 0.02%   |
| Intel Core m3                        | 1         | 0.02%   |
| Intel Core Duo                       | 1         | 0.02%   |
| AMD Turion II Ultra Dual-Core Mobile | 1         | 0.02%   |
| AMD Turion Dual-Core                 | 1         | 0.02%   |
| AMD Turion                           | 1         | 0.02%   |
| AMD Sempron                          | 1         | 0.02%   |
| AMD Ryzen 9                          | 1         | 0.02%   |
| AMD Ryzen 5 PRO                      | 1         | 0.02%   |
| AMD Quad-Core                        | 1         | 0.02%   |
| AMD Athlon XP                        | 1         | 0.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 3699      | 65.39%  |
| 4       | 1556      | 27.51%  |
| 6       | 212       | 3.75%   |
| 1       | 130       | 2.3%    |
| 8       | 53        | 0.94%   |
| 3       | 3         | 0.05%   |
| Unknown | 3         | 0.05%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5655      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4222      | 74.62%  |
| 1       | 1433      | 25.33%  |
| Unknown | 3         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5340      | 93.85%  |
| Unknown        | 293       | 5.15%   |
| 32-bit         | 42        | 0.74%   |
| 64-bit         | 15        | 0.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 919       | 15.79%  |
| 0x306a9    | 516       | 8.86%   |
| 0x206a7    | 503       | 8.64%   |
| 0x806e9    | 326       | 5.6%    |
| 0x40651    | 287       | 4.93%   |
| 0x906ea    | 276       | 4.74%   |
| 0x806ec    | 275       | 4.72%   |
| 0x20655    | 252       | 4.33%   |
| 0x406e3    | 240       | 4.12%   |
| 0x306d4    | 238       | 4.09%   |
| 0x1067a    | 227       | 3.9%    |
| 0x806ea    | 223       | 3.83%   |
| 0x6fd      | 125       | 2.15%   |
| 0x406c4    | 120       | 2.06%   |
| 0x05000119 | 80        | 1.37%   |
| 0x906e9    | 75        | 1.29%   |
| 0x806c1    | 75        | 1.29%   |
| 0x30678    | 72        | 1.24%   |
| 0x08108109 | 56        | 0.96%   |
| 0x906ed    | 54        | 0.93%   |
| 0x08108102 | 54        | 0.93%   |
| 0x706a1    | 52        | 0.89%   |
| 0x08600103 | 50        | 0.86%   |
| 0x306c3    | 47        | 0.81%   |
| 0x20652    | 44        | 0.76%   |
| 0x806eb    | 40        | 0.69%   |
| 0x106ca    | 39        | 0.67%   |
| 0x706e5    | 38        | 0.65%   |
| 0x406c3    | 37        | 0.64%   |
| 0x10676    | 31        | 0.53%   |
| 0x706a8    | 29        | 0.5%    |
| 0xa0652    | 28        | 0.48%   |
| 0x05000029 | 26        | 0.45%   |
| 0x03000027 | 26        | 0.45%   |
| 0x30661    | 25        | 0.43%   |
| 0x506e3    | 23        | 0.4%    |
| 0x506c9    | 23        | 0.4%    |
| 0x10661    | 23        | 0.4%    |
| 0x0810100b | 20        | 0.34%   |
| 0x0700010f | 20        | 0.34%   |
| 0x010000c8 | 17        | 0.29%   |
| 0x0600611a | 16        | 0.27%   |
| 0xa0660    | 11        | 0.19%   |
| 0x6ec      | 11        | 0.19%   |
| 0x106e5    | 11        | 0.19%   |
| 0x106c2    | 10        | 0.17%   |
| 0x0500010d | 10        | 0.17%   |
| 0x6fb      | 9         | 0.15%   |
| 0x6f6      | 9         | 0.15%   |
| 0x30673    | 9         | 0.15%   |
| 0x6e8      | 8         | 0.14%   |
| 0x6fa      | 7         | 0.12%   |
| 0x806d1    | 5         | 0.09%   |
| 0x6f2      | 5         | 0.09%   |
| 0x08608103 | 5         | 0.09%   |
| 0x06001119 | 5         | 0.09%   |
| 0x02000057 | 5         | 0.09%   |
| 0x6d8      | 4         | 0.07%   |
| 0x0a50000c | 3         | 0.05%   |
| 0x08600106 | 3         | 0.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 1468      | 25.96%  |
| IvyBridge       | 601       | 10.63%  |
| SandyBridge     | 578       | 10.22%  |
| Haswell         | 386       | 6.83%   |
| Westmere        | 339       | 5.99%   |
| Penryn          | 299       | 5.29%   |
| Skylake         | 296       | 5.23%   |
| Silvermont      | 275       | 4.86%   |
| Broadwell       | 265       | 4.69%   |
| Core            | 196       | 3.47%   |
| Zen+            | 134       | 2.37%   |
| Bobcat          | 132       | 2.33%   |
| TigerLake       | 92        | 1.63%   |
| Goldmont plus   | 86        | 1.52%   |
| Bonnell         | 79        | 1.4%    |
| Zen 2           | 55        | 0.97%   |
| CometLake       | 50        | 0.88%   |
| IceLake         | 49        | 0.87%   |
| K8 Hammer       | 35        | 0.62%   |
| Excavator       | 32        | 0.57%   |
| K10 Llano       | 30        | 0.53%   |
| Zen             | 28        | 0.5%    |
| K10             | 26        | 0.46%   |
| Goldmont        | 24        | 0.42%   |
| P6              | 23        | 0.41%   |
| Jaguar          | 22        | 0.39%   |
| Unknown         | 16        | 0.28%   |
| Nehalem         | 12        | 0.21%   |
| K8 & K10 hybrid | 9         | 0.16%   |
| Piledriver      | 7         | 0.12%   |
| Zen 3           | 4         | 0.07%   |
| Puma            | 4         | 0.07%   |
| Steamroller     | 2         | 0.04%   |
| NetBurst        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4897      | 66.49%  |
| Nvidia                           | 1487      | 20.19%  |
| AMD                              | 870       | 11.81%  |
| Silicon Integrated Systems [SiS] | 88        | 1.19%   |
| VIA Technologies                 | 23        | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 593       | 7.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 566       | 7.47%   |
| Intel HD Graphics 620                                                                    | 368       | 4.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 345       | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 325       | 4.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 318       | 4.2%    |
| Intel HD Graphics 5500                                                                   | 252       | 3.33%   |
| Intel UHD Graphics 620                                                                   | 245       | 3.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 244       | 3.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 243       | 3.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 227       | 3%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 216       | 2.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 188       | 2.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 136       | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 133       | 1.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 124       | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 119       | 1.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 119       | 1.57%   |
| Intel HD Graphics 630                                                                    | 88        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 87        | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 86        | 1.13%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 85        | 1.12%   |
| Nvidia GP108M [GeForce MX150]                                                            | 83        | 1.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 82        | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 81        | 1.07%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 74        | 0.98%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 69        | 0.91%   |
| Nvidia GM108M [GeForce MX110]                                                            | 66        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 63        | 0.83%   |
| Nvidia TU117M                                                                            | 59        | 0.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 59        | 0.78%   |
| AMD Renoir                                                                               | 54        | 0.71%   |
| Nvidia GP108M [GeForce MX250]                                                            | 45        | 0.59%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 42        | 0.55%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 41        | 0.54%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 39        | 0.51%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 37        | 0.49%   |
| Nvidia GP108M [GeForce MX230]                                                            | 36        | 0.48%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 35        | 0.46%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 35        | 0.46%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 34        | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 33        | 0.44%   |
| Nvidia GM108M [GeForce MX130]                                                            | 33        | 0.44%   |
| Nvidia GM108M [GeForce 930M]                                                             | 33        | 0.44%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 33        | 0.44%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 33        | 0.44%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 33        | 0.44%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 30        | 0.4%    |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 30        | 0.4%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 29        | 0.38%   |
| AMD Chelsea LP [Radeon HD 7730M]                                                         | 27        | 0.36%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 26        | 0.34%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 26        | 0.34%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 26        | 0.34%   |
| Intel HD Graphics 520                                                                    | 25        | 0.33%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 25        | 0.33%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 25        | 0.33%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 24        | 0.32%   |
| Intel HD Graphics 530                                                                    | 24        | 0.32%   |
| Intel HD Graphics 500                                                                    | 24        | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 3291      | 58.11%  |
| Intel + Nvidia | 1284      | 22.67%  |
| 1 x AMD        | 380       | 6.71%   |
| Intel + AMD    | 327       | 5.77%   |
| 1 x Nvidia     | 103       | 1.82%   |
| AMD + Nvidia   | 99        | 1.75%   |
| 1 x SiS        | 88        | 1.55%   |
| 2 x AMD        | 63        | 1.11%   |
| 1 x VIA        | 23        | 0.41%   |
| Other          | 5         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4579      | 80.32%  |
| Proprietary | 946       | 16.59%  |
| Unknown     | 176       | 3.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3902      | 67.72%  |
| 1.01-2.0   | 882       | 15.31%  |
| 0.01-0.5   | 423       | 7.34%   |
| 3.01-4.0   | 325       | 5.64%   |
| 0.51-1.0   | 155       | 2.69%   |
| 5.01-6.0   | 54        | 0.94%   |
| 2.01-3.0   | 14        | 0.24%   |
| 7.01-8.0   | 6         | 0.1%    |
| 8.01-16.0  | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1263      | 19.65%  |
| BOE                     | 1142      | 17.77%  |
| LG Display              | 933       | 14.51%  |
| Chimei Innolux          | 907       | 14.11%  |
| Samsung Electronics     | 689       | 10.72%  |
| Goldstar                | 332       | 5.16%   |
| AOC                     | 126       | 1.96%   |
| Chi Mei Optoelectronics | 123       | 1.91%   |
| Dell                    | 116       | 1.8%    |
| InfoVision              | 95        | 1.48%   |
| PANDA                   | 77        | 1.2%    |
| Philips                 | 68        | 1.06%   |
| Apple                   | 65        | 1.01%   |
| Lenovo                  | 52        | 0.81%   |
| CPT                     | 42        | 0.65%   |
| HannStar                | 41        | 0.64%   |
| Acer                    | 36        | 0.56%   |
| LG Philips              | 32        | 0.5%    |
| Sony                    | 28        | 0.44%   |
| InnoLux Display         | 25        | 0.39%   |
| Hewlett-Packard         | 21        | 0.33%   |
| Sharp                   | 16        | 0.25%   |
| MTD                     | 16        | 0.25%   |
| SLD                     | 14        | 0.22%   |
| Panasonic               | 13        | 0.2%    |
| KDC                     | 10        | 0.16%   |
| BenQ                    | 10        | 0.16%   |
| Toshiba                 | 9         | 0.14%   |
| Unknown                 | 7         | 0.11%   |
| SKY                     | 7         | 0.11%   |
| GDH                     | 7         | 0.11%   |
| ASUSTek Computer        | 7         | 0.11%   |
| RTK                     | 6         | 0.09%   |
| NCS                     | 6         | 0.09%   |
| STA                     | 5         | 0.08%   |
| Quanta Display          | 5         | 0.08%   |
| MStar                   | 5         | 0.08%   |
| LGD                     | 5         | 0.08%   |
| HB@                     | 5         | 0.08%   |
| AGO                     | 5         | 0.08%   |
| Unknown (XXX)           | 4         | 0.06%   |
| Seiko/Epson             | 4         | 0.06%   |
| ITE                     | 4         | 0.06%   |
| VIE                     | 3         | 0.05%   |
| Positivo                | 3         | 0.05%   |
| LG Electronics          | 3         | 0.05%   |
| Envision                | 3         | 0.05%   |
| Ancor Communications    | 3         | 0.05%   |
| ___                     | 2         | 0.03%   |
| PZG                     | 2         | 0.03%   |
| HBTV-29D07HD            | 2         | 0.03%   |
| DTV                     | 2         | 0.03%   |
| BOE Technology Group    | 2         | 0.03%   |
| XKX                     | 1         | 0.02%   |
| Westinghouse            | 1         | 0.02%   |
| WAN                     | 1         | 0.02%   |
| Wacom                   | 1         | 0.02%   |
| UGD                     | 1         | 0.02%   |
| TBD                     | 1         | 0.02%   |
| Sun                     | 1         | 0.02%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 105       | 1.62%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 99        | 1.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 92        | 1.42%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 89        | 1.38%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 88        | 1.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 86        | 1.33%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 82        | 1.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 79        | 1.22%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 73        | 1.13%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 71        | 1.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 64        | 0.99%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch          | 59        | 0.91%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 59        | 0.91%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 56        | 0.87%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 52        | 0.8%    |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 49        | 0.76%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 49        | 0.76%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 48        | 0.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 47        | 0.73%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 47        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 45        | 0.7%    |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 42        | 0.65%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch          | 41        | 0.63%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 41        | 0.63%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 41        | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 40        | 0.62%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 38        | 0.59%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 37        | 0.57%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 36        | 0.56%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 32        | 0.49%   |
| BOE LCD Monitor BOE0839 1920x1080 382x215mm 17.3-inch                | 32        | 0.49%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 32        | 0.49%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch        | 32        | 0.49%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch        | 32        | 0.49%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 31        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 31        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 31        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 31        | 0.48%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 31        | 0.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 31        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 30        | 0.46%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch          | 29        | 0.45%   |
| BOE LCD Monitor BOE05F0 1366x768 309x173mm 13.9-inch                 | 29        | 0.45%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch        | 29        | 0.45%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 28        | 0.43%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 28        | 0.43%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch        | 28        | 0.43%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch          | 27        | 0.42%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch       | 27        | 0.42%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                 | 26        | 0.4%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 26        | 0.4%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 25        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 24        | 0.37%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch | 23        | 0.36%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 23        | 0.36%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch | 22        | 0.34%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 22        | 0.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 22        | 0.34%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                | 22        | 0.34%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                 | 22        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 3476      | 56.51%  |
| 1920x1080 (FHD)    | 1733      | 28.17%  |
| 1280x800 (WXGA)    | 251       | 4.08%   |
| 1600x900 (HD+)     | 142       | 2.31%   |
| 2560x1080          | 114       | 1.85%   |
| 3840x2160 (4K)     | 79        | 1.28%   |
| 1440x900 (WXGA+)   | 73        | 1.19%   |
| 1360x768           | 59        | 0.96%   |
| 1024x600           | 36        | 0.59%   |
| 1920x1200 (WUXGA)  | 31        | 0.5%    |
| 1680x1050 (WSXGA+) | 26        | 0.42%   |
| 2560x1440 (QHD)    | 25        | 0.41%   |
| 1280x1024 (SXGA)   | 23        | 0.37%   |
| 1024x768 (XGA)     | 21        | 0.34%   |
| 1920x540           | 12        | 0.2%    |
| 1280x720 (HD)      | 9         | 0.15%   |
| 2288x1287          | 7         | 0.11%   |
| Unknown            | 6         | 0.1%    |
| 2560x1600          | 4         | 0.07%   |
| 3200x1800 (QHD+)   | 3         | 0.05%   |
| 3840x2400          | 2         | 0.03%   |
| 3840x1080          | 2         | 0.03%   |
| 2880x1800          | 2         | 0.03%   |
| 1280x960           | 2         | 0.03%   |
| 3600x1080          | 1         | 0.02%   |
| 3286x1080          | 1         | 0.02%   |
| 2880x900           | 1         | 0.02%   |
| 2646x800           | 1         | 0.02%   |
| 2640x800           | 1         | 0.02%   |
| 2304x1440          | 1         | 0.02%   |
| 2256x1504          | 1         | 0.02%   |
| 2160x1440          | 1         | 0.02%   |
| 1792x768           | 1         | 0.02%   |
| 1680x945           | 1         | 0.02%   |
| 1600x1200          | 1         | 0.02%   |
| 1280x768           | 1         | 0.02%   |
| 1024x576           | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2765      | 43.1%   |
| 14      | 1238      | 19.3%   |
| 13      | 1054      | 16.43%  |
| 21      | 182       | 2.84%   |
| 23      | 167       | 2.6%    |
| 17      | 148       | 2.31%   |
| 18      | 125       | 1.95%   |
| 34      | 105       | 1.64%   |
| 11      | 94        | 1.47%   |
| 24      | 77        | 1.2%    |
| 27      | 65        | 1.01%   |
| 31      | 44        | 0.69%   |
| 12      | 43        | 0.67%   |
| 10      | 41        | 0.64%   |
| 20      | 39        | 0.61%   |
| Unknown | 38        | 0.59%   |
| 19      | 33        | 0.51%   |
| 40      | 26        | 0.41%   |
| 32      | 24        | 0.37%   |
| 22      | 16        | 0.25%   |
| 72      | 15        | 0.23%   |
| 84      | 12        | 0.19%   |
| 28      | 12        | 0.19%   |
| 16      | 11        | 0.17%   |
| 54      | 10        | 0.16%   |
| 47      | 8         | 0.12%   |
| 52      | 6         | 0.09%   |
| 37      | 3         | 0.05%   |
| 48      | 2         | 0.03%   |
| 46      | 2         | 0.03%   |
| 26      | 2         | 0.03%   |
| 142     | 1         | 0.02%   |
| 74      | 1         | 0.02%   |
| 65      | 1         | 0.02%   |
| 60      | 1         | 0.02%   |
| 57      | 1         | 0.02%   |
| 55      | 1         | 0.02%   |
| 49      | 1         | 0.02%   |
| 42      | 1         | 0.02%   |
| 41      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 4789      | 75.23%  |
| 401-500        | 393       | 6.17%   |
| 201-300        | 333       | 5.23%   |
| 501-600        | 298       | 4.68%   |
| 351-400        | 232       | 3.64%   |
| 701-800        | 129       | 2.03%   |
| 601-700        | 61        | 0.96%   |
| Unknown        | 38        | 0.6%    |
| 1001-1500      | 33        | 0.52%   |
| 801-900        | 29        | 0.46%   |
| 1501-2000      | 28        | 0.44%   |
| 901-1000       | 2         | 0.03%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 5053      | 89.18%  |
| 16/10   | 408       | 7.2%    |
| 21/9    | 114       | 2.01%   |
| 4/3     | 35        | 0.62%   |
| 5/4     | 25        | 0.44%   |
| Unknown | 19        | 0.34%   |
| 3/2     | 10        | 0.18%   |
| 32/9    | 1         | 0.02%   |
| 1.00    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2750      | 42.93%  |
| 81-90          | 2168      | 33.84%  |
| 201-250        | 378       | 5.9%    |
| 351-500        | 176       | 2.75%   |
| 151-200        | 133       | 2.08%   |
| 141-150        | 130       | 2.03%   |
| 71-80          | 119       | 1.86%   |
| 121-130        | 107       | 1.67%   |
| 51-60          | 94        | 1.47%   |
| 301-350        | 65        | 1.01%   |
| More than 1000 | 51        | 0.8%    |
| 501-1000       | 42        | 0.66%   |
| 41-50          | 41        | 0.64%   |
| Unknown        | 38        | 0.59%   |
| 61-70          | 32        | 0.5%    |
| 91-100         | 27        | 0.42%   |
| 251-300        | 24        | 0.37%   |
| 131-140        | 22        | 0.34%   |
| 111-120        | 9         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 3568      | 57%     |
| 121-160       | 1541      | 24.62%  |
| 51-100        | 934       | 14.92%  |
| 1-50          | 86        | 1.37%   |
| 161-240       | 77        | 1.23%   |
| Unknown       | 38        | 0.61%   |
| More than 240 | 16        | 0.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4585      | 79.22%  |
| 2     | 988       | 17.07%  |
| 0     | 172       | 2.97%   |
| 3     | 43        | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 4127      | 41.37%  |
| Qualcomm Atheros                      | 2616      | 26.22%  |
| Intel                                 | 1681      | 16.85%  |
| Broadcom                              | 573       | 5.74%   |
| Marvell Technology Group              | 156       | 1.56%   |
| JMicron Technology                    | 154       | 1.54%   |
| Broadcom Limited                      | 127       | 1.27%   |
| Ralink                                | 114       | 1.14%   |
| Silicon Integrated Systems [SiS]      | 88        | 0.88%   |
| Ralink Technology                     | 72        | 0.72%   |
| TP-Link                               | 42        | 0.42%   |
| Samsung Electronics                   | 31        | 0.31%   |
| VIA Technologies                      | 23        | 0.23%   |
| Motorola PCS                          | 23        | 0.23%   |
| Qualcomm Atheros Communications       | 20        | 0.2%    |
| Nvidia                                | 19        | 0.19%   |
| ASIX Electronics                      | 18        | 0.18%   |
| Xiaomi                                | 15        | 0.15%   |
| D-Link                                | 13        | 0.13%   |
| ICS Advent                            | 8         | 0.08%   |
| DisplayLink                           | 5         | 0.05%   |
| D-Link System                         | 5         | 0.05%   |
| MEDIATEK                              | 4         | 0.04%   |
| Lenovo                                | 4         | 0.04%   |
| Attansic Technology                   | 4         | 0.04%   |
| LG Electronics                        | 3         | 0.03%   |
| Ericsson Business Mobile Networks     | 3         | 0.03%   |
| Dell                                  | 3         | 0.03%   |
| AMD                                   | 3         | 0.03%   |
| Huawei Technologies                   | 2         | 0.02%   |
| ASUSTek Computer                      | 2         | 0.02%   |
| Arduino SA                            | 2         | 0.02%   |
| Sierra Wireless                       | 1         | 0.01%   |
| Qualcomm                              | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| OPPO Electronics                      | 1         | 0.01%   |
| OnePlus Technology (Shenzhen)         | 1         | 0.01%   |
| NetGear                               | 1         | 0.01%   |
| Microsoft                             | 1         | 0.01%   |
| Micro Star International              | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Manta                                 | 1         | 0.01%   |
| Linksys                               | 1         | 0.01%   |
| Hewlett-Packard                       | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |
| Edimax Technology                     | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2482      | 22.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1159      | 10.6%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 701       | 6.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 601       | 5.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 490       | 4.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 257       | 2.35%   |
| Intel Wi-Fi 6 AX200                                                     | 254       | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 250       | 2.29%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 241       | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 185       | 1.69%   |
| Intel Wireless 7265                                                     | 131       | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 128       | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 115       | 1.05%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 113       | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 92        | 0.84%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 90        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 89        | 0.81%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 85        | 0.78%   |
| Intel Wi-Fi 6 AX201                                                     | 85        | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 80        | 0.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 74        | 0.68%   |
| Intel Wireless 3165                                                     | 70        | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 67        | 0.61%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 67        | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 66        | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 66        | 0.6%    |
| Intel Wireless 7260                                                     | 64        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 63        | 0.58%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 55        | 0.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 54        | 0.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 53        | 0.48%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 53        | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 52        | 0.48%   |
| Intel Wireless 3160                                                     | 52        | 0.48%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 51        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 51        | 0.47%   |
| Intel Centrino Advanced-N 6235                                          | 50        | 0.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 47        | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 46        | 0.42%   |
| Ralink MT7601U Wireless Adapter                                         | 44        | 0.4%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 44        | 0.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 43        | 0.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 0.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 42        | 0.38%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 42        | 0.38%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                     | 41        | 0.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 39        | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 39        | 0.36%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 37        | 0.34%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 37        | 0.34%   |
| Intel Wireless 8265 / 8275                                              | 35        | 0.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 35        | 0.32%   |
| Intel WiFi Link 5100                                                    | 34        | 0.31%   |
| Broadcom BCM43142 802.11b/g/n                                           | 34        | 0.31%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 30        | 0.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 0.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 29        | 0.27%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 28        | 0.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 27        | 0.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 27        | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 2458      | 43.4%   |
| Intel                                 | 1641      | 28.98%  |
| Realtek Semiconductor                 | 795       | 14.04%  |
| Broadcom                              | 415       | 7.33%   |
| Ralink                                | 114       | 2.01%   |
| Broadcom Limited                      | 81        | 1.43%   |
| Ralink Technology                     | 72        | 1.27%   |
| TP-Link                               | 34        | 0.6%    |
| Qualcomm Atheros Communications       | 20        | 0.35%   |
| D-Link                                | 13        | 0.23%   |
| D-Link System                         | 5         | 0.09%   |
| MEDIATEK                              | 2         | 0.04%   |
| Dell                                  | 2         | 0.04%   |
| Sierra Wireless                       | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Pegatron                              | 1         | 0.02%   |
| NetGear                               | 1         | 0.02%   |
| Microsoft                             | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Mercucys                              | 1         | 0.02%   |
| Linksys                               | 1         | 0.02%   |
| Guillemot                             | 1         | 0.02%   |
| Edimax Technology                     | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 701       | 12.32%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 601       | 10.56%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 490       | 8.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 257       | 4.52%   |
| Intel Wi-Fi 6 AX200                                                     | 254       | 4.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 250       | 4.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 241       | 4.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 185       | 3.25%   |
| Intel Wireless 7265                                                     | 131       | 2.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 128       | 2.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 115       | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 92        | 1.62%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 90        | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 89        | 1.56%   |
| Intel Wi-Fi 6 AX201                                                     | 85        | 1.49%   |
| Intel Wireless 3165                                                     | 70        | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 67        | 1.18%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 67        | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 66        | 1.16%   |
| Intel Wireless 7260                                                     | 64        | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 54        | 0.95%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 53        | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 53        | 0.93%   |
| Intel Wireless 3160                                                     | 52        | 0.91%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 51        | 0.9%    |
| Intel Centrino Advanced-N 6235                                          | 50        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 47        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                         | 44        | 0.77%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 44        | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 43        | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 42        | 0.74%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 42        | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 37        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 37        | 0.65%   |
| Intel Wireless 8265 / 8275                                              | 35        | 0.61%   |
| Intel WiFi Link 5100                                                    | 34        | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 34        | 0.6%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 30        | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 29        | 0.51%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 28        | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 27        | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 27        | 0.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 26        | 0.46%   |
| Intel Centrino Advanced-N 6200                                          | 26        | 0.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 26        | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 24        | 0.42%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 24        | 0.42%   |
| Intel Wireless 8260                                                     | 21        | 0.37%   |
| Broadcom BCM43225 802.11b/g/n                                           | 21        | 0.37%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 20        | 0.35%   |
| Intel Centrino Wireless-N 2230                                          | 19        | 0.33%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 18        | 0.32%   |
| Qualcomm Atheros AR9271 802.11n                                         | 18        | 0.32%   |
| Intel Wireless-AC 9260                                                  | 17        | 0.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 17        | 0.3%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 17        | 0.3%    |
| Realtek 802.11ac NIC                                                    | 16        | 0.28%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 14        | 0.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3763      | 72.41%  |
| Qualcomm Atheros                 | 353       | 6.79%   |
| Intel                            | 255       | 4.91%   |
| Broadcom                         | 216       | 4.16%   |
| Marvell Technology Group         | 156       | 3%      |
| JMicron Technology               | 154       | 2.96%   |
| Silicon Integrated Systems [SiS] | 88        | 1.69%   |
| Broadcom Limited                 | 52        | 1%      |
| Samsung Electronics              | 31        | 0.6%    |
| VIA Technologies                 | 23        | 0.44%   |
| Motorola PCS                     | 19        | 0.37%   |
| Nvidia                           | 18        | 0.35%   |
| ASIX Electronics                 | 18        | 0.35%   |
| Xiaomi                           | 15        | 0.29%   |
| TP-Link                          | 8         | 0.15%   |
| ICS Advent                       | 8         | 0.15%   |
| DisplayLink                      | 5         | 0.1%    |
| Lenovo                           | 4         | 0.08%   |
| Attansic Technology              | 4         | 0.08%   |
| ASUSTek Computer                 | 2         | 0.04%   |
| Qualcomm                         | 1         | 0.02%   |
| OPPO Electronics                 | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.02%   |
| MediaTek                         | 1         | 0.02%   |
| LG Electronics                   | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2482      | 47.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1159      | 22.22%  |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 113       | 2.17%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 85        | 1.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 80        | 1.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 74        | 1.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 66        | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 63        | 1.21%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 55        | 1.05%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 52        | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 51        | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 46        | 0.88%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 41        | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 39        | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 39        | 0.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 35        | 0.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 27        | 0.52%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 27        | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 26        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 25        | 0.48%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 23        | 0.44%   |
| Intel Ethernet Connection (4) I219-LM                                          | 23        | 0.44%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 21        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 20        | 0.38%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 20        | 0.38%   |
| Intel Ethernet Connection I219-LM                                              | 20        | 0.38%   |
| Intel 82577LM Gigabit Network Connection                                       | 20        | 0.38%   |
| Motorola PCS moto g(30)                                                        | 19        | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 18        | 0.35%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 0.33%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 16        | 0.31%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 15        | 0.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 15        | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 15        | 0.29%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 14        | 0.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 13        | 0.25%   |
| Intel Ethernet Connection I217-LM                                              | 13        | 0.25%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 13        | 0.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 11        | 0.21%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 0.21%   |
| Intel 82567LM Gigabit Network Connection                                       | 10        | 0.19%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 10        | 0.19%   |
| Realtek RTL8125 2.5GbE Controller                                              | 9         | 0.17%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 9         | 0.17%   |
| Intel Ethernet Connection (6) I219-LM                                          | 9         | 0.17%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 9         | 0.17%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 8         | 0.15%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 8         | 0.15%   |
| Nvidia MCP79 Ethernet                                                          | 8         | 0.15%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 8         | 0.15%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 7         | 0.13%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 7         | 0.13%   |
| Intel Ethernet Connection (10) I219-LM                                         | 7         | 0.13%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 7         | 0.13%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 7         | 0.13%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 7         | 0.13%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 7         | 0.13%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 0.12%   |
| Intel Ethernet Connection I217-V                                               | 6         | 0.12%   |
| Intel Ethernet Connection (13) I219-LM                                         | 6         | 0.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5480      | 51.53%  |
| Ethernet | 5124      | 48.19%  |
| Modem    | 23        | 0.22%   |
| Unknown  | 7         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5038      | 62.13%  |
| Ethernet | 3070      | 37.86%  |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4839      | 85.45%  |
| 1     | 658       | 11.62%  |
| 0     | 161       | 2.84%   |
| 3     | 5         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4824      | 83.53%  |
| Yes  | 951       | 16.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1350      | 33.69%  |
| Qualcomm Atheros Communications | 1210      | 30.2%   |
| Lite-On Technology              | 559       | 13.95%  |
| Broadcom                        | 176       | 4.39%   |
| Realtek Semiconductor           | 117       | 2.92%   |
| Foxconn / Hon Hai               | 102       | 2.55%   |
| IMC Networks                    | 86        | 2.15%   |
| Cambridge Silicon Radio         | 73        | 1.82%   |
| Apple                           | 67        | 1.67%   |
| Dell                            | 66        | 1.65%   |
| Ralink                          | 43        | 1.07%   |
| Hewlett-Packard                 | 42        | 1.05%   |
| Unknown                         | 36        | 0.9%    |
| Qcom                            | 22        | 0.55%   |
| Ralink Technology               | 16        | 0.4%    |
| Alps Electric                   | 12        | 0.3%    |
| Foxconn International           | 11        | 0.27%   |
| Askey Computer                  | 7         | 0.17%   |
| Toshiba                         | 4         | 0.1%    |
| Micro Star International        | 3         | 0.07%   |
| ASUSTek Computer                | 3         | 0.07%   |
| Syntek                          | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 680       | 16.97%  |
| Intel Bluetooth wireless interface                                                  | 480       | 11.98%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 354       | 8.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 332       | 8.29%   |
| Intel AX200 Bluetooth                                                               | 252       | 6.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 195       | 4.87%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 114       | 2.85%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 112       | 2.8%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 97        | 2.42%   |
| Realtek Bluetooth Radio                                                             | 88        | 2.2%    |
| Intel AX201 Bluetooth                                                               | 88        | 2.2%    |
| Lite-On Bluetooth Device                                                            | 80        | 2%      |
| Lite-On Atheros AR3012 Bluetooth                                                    | 73        | 1.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 73        | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 70        | 1.75%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 52        | 1.3%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 51        | 1.27%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 51        | 1.27%   |
| Intel Bluetooth Device                                                              | 49        | 1.22%   |
| Ralink RT3290 Bluetooth                                                             | 43        | 1.07%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 41        | 1.02%   |
| Unknown Bluetooth Device                                                            | 36        | 0.9%    |
| Dell Wireless 365 Bluetooth                                                         | 29        | 0.72%   |
| Apple Bluetooth Host Controller                                                     | 29        | 0.72%   |
| IMC Networks Bluetooth Radio                                                        | 28        | 0.7%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 27        | 0.67%   |
| IMC Networks Bluetooth Device                                                       | 26        | 0.65%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 25        | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 24        | 0.6%    |
| Apple Bluetooth USB Host Controller                                                 | 22        | 0.55%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 20        | 0.5%    |
| Lite-On Atheros Bluetooth                                                           | 19        | 0.47%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 15        | 0.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 15        | 0.37%   |
| Realtek RTL8723A Bluetooth                                                          | 14        | 0.35%   |
| Qcom Broadcom Bluetooth USB                                                         | 14        | 0.35%   |
| Dell DW375 Bluetooth Module                                                         | 14        | 0.35%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 14        | 0.35%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 13        | 0.32%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 13        | 0.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 13        | 0.32%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 12        | 0.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 11        | 0.27%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 11        | 0.27%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 11        | 0.27%   |
| IMC Networks Bluetooth                                                              | 10        | 0.25%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 9         | 0.22%   |
| Qcom Bluetooth USB                                                                  | 8         | 0.2%    |
| Dell Wireless 355 Bluetooth                                                         | 8         | 0.2%    |
| Broadcom BCM20702A0                                                                 | 8         | 0.2%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 8         | 0.2%    |
| Apple Bluetooth HCI                                                                 | 8         | 0.2%    |
| Alps Electric BCM2046 Bluetooth Device                                              | 8         | 0.2%    |
| Broadcom BCM2045 Bluetooth                                                          | 7         | 0.17%   |
| Askey Bluetooth Device                                                              | 7         | 0.17%   |
| Broadcom HP Portable SoftSailing                                                    | 6         | 0.15%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 0.12%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 5         | 0.12%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 5         | 0.12%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 0.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 4884      | 75.2%   |
| Nvidia                                          | 696       | 10.72%  |
| AMD                                             | 556       | 8.56%   |
| Silicon Integrated Systems [SiS]                | 88        | 1.35%   |
| C-Media Electronics                             | 49        | 0.75%   |
| Generalplus Technology                          | 32        | 0.49%   |
| Logitech                                        | 28        | 0.43%   |
| VIA Technologies                                | 23        | 0.35%   |
| JMTek                                           | 16        | 0.25%   |
| Kingston Technology                             | 15        | 0.23%   |
| Plantronics                                     | 9         | 0.14%   |
| Corsair                                         | 8         | 0.12%   |
| Realtek Semiconductor                           | 7         | 0.11%   |
| Microsoft                                       | 7         | 0.11%   |
| Texas Instruments                               | 6         | 0.09%   |
| Licensed by Sony Computer Entertainment America | 6         | 0.09%   |
| GN Netcom                                       | 6         | 0.09%   |
| Sony                                            | 5         | 0.08%   |
| Samsung Electronics                             | 4         | 0.06%   |
| SteelSeries ApS                                 | 3         | 0.05%   |
| Razer USA                                       | 3         | 0.05%   |
| Lenovo                                          | 3         | 0.05%   |
| JBL                                             | 3         | 0.05%   |
| Turtle Beach                                    | 2         | 0.03%   |
| Tdlasunnic                                      | 2         | 0.03%   |
| Meizu                                           | 2         | 0.03%   |
| M-Audio                                         | 2         | 0.03%   |
| Goldvish                                        | 2         | 0.03%   |
| Focusrite-Novation                              | 2         | 0.03%   |
| Dell                                            | 2         | 0.03%   |
| BY EDIFIER                                      | 2         | 0.03%   |
| BEHRINGER International                         | 2         | 0.03%   |
| Astro Gaming                                    | 2         | 0.03%   |
| Winbond Electronics                             | 1         | 0.02%   |
| Tenx Technology                                 | 1         | 0.02%   |
| Syntek                                          | 1         | 0.02%   |
| SOMIC Industrial                                | 1         | 0.02%   |
| Sennheiser Communications                       | 1         | 0.02%   |
| Samson Technologies                             | 1         | 0.02%   |
| QinHeng Electronics                             | 1         | 0.02%   |
| Philips (or NXP)                                | 1         | 0.02%   |
| Micronas                                        | 1         | 0.02%   |
| FIFINE Microphones                              | 1         | 0.02%   |
| eMPIA Technology                                | 1         | 0.02%   |
| Elite Silicon                                   | 1         | 0.02%   |
| EDIFIER Technology                              | 1         | 0.02%   |
| EDFIER                                          | 1         | 0.02%   |
| Creative Technology                             | 1         | 0.02%   |
| Casio Computer                                  | 1         | 0.02%   |
| BR25                                            | 1         | 0.02%   |
| Barco Display Systems                           | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 911       | 12.02%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 773       | 10.2%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 406       | 5.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 360       | 4.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 350       | 4.62%   |
| Intel 8 Series HD Audio Controller                                                                | 325       | 4.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 321       | 4.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 264       | 3.48%   |
| Intel Broadwell-U Audio Controller                                                                | 264       | 3.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 261       | 3.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 242       | 3.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 231       | 3.05%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 224       | 2.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 157       | 2.07%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 149       | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 139       | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 135       | 1.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 129       | 1.7%    |
| AMD Wrestler HDMI Audio                                                                           | 125       | 1.65%   |
| AMD FCH Azalia Controller                                                                         | 108       | 1.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 100       | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 91        | 1.2%    |
| Intel CM238 HD Audio Controller                                                                   | 88        | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 86        | 1.13%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 85        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 80        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 80        | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 69        | 0.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 62        | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 58        | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                                          | 51        | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 44        | 0.58%   |
| Intel Comet Lake PCH cAVS                                                                         | 37        | 0.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 35        | 0.46%   |
| Generalplus Technology Usb Audio Device                                                           | 32        | 0.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 32        | 0.42%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 30        | 0.4%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 30        | 0.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 26        | 0.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 24        | 0.32%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 23        | 0.3%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 23        | 0.3%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 23        | 0.3%    |
| Nvidia High Definition Audio Controller                                                           | 22        | 0.29%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 22        | 0.29%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 18        | 0.24%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 17        | 0.22%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 15        | 0.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 0.18%   |
| Intel USB PnP Sound Device                                                                        | 13        | 0.17%   |
| C-Media Electronics CM108 Audio Controller                                                        | 13        | 0.17%   |
| Logitech USB Headset                                                                              | 12        | 0.16%   |
| Nvidia MCP79 High Definition Audio                                                                | 10        | 0.13%   |
| Nvidia Audio device                                                                               | 10        | 0.13%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 10        | 0.13%   |
| JMTek USB PnP Audio Device(EEPROM)                                                                | 9         | 0.12%   |
| C-Media Electronics Redragon Gaming Headset                                                       | 9         | 0.12%   |
| Nvidia MCP89 High Definition Audio                                                                | 8         | 0.11%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 8         | 0.11%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 8         | 0.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Smart                        | 367       | 18.44%  |
| Samsung Electronics          | 287       | 14.42%  |
| Unknown                      | 196       | 9.85%   |
| Kingston                     | 196       | 9.85%   |
| SK Hynix                     | 188       | 9.45%   |
| A-DATA Technology            | 138       | 6.93%   |
| Teikon                       | 111       | 5.58%   |
| Micron Technology            | 87        | 4.37%   |
| Smart Brazil                 | 84        | 4.22%   |
| High Bridge                  | 48        | 2.41%   |
| Crucial                      | 48        | 2.41%   |
| Corsair                      | 46        | 2.31%   |
| Elpida                       | 35        | 1.76%   |
| Multilaser                   | 18        | 0.9%    |
| Apacer                       | 15        | 0.75%   |
| Nanya Technology             | 14        | 0.7%    |
| Unknown (ABCD)               | 11        | 0.55%   |
| Ramaxel Technology           | 9         | 0.45%   |
| HT Micron                    | 9         | 0.45%   |
| Patriot                      | 8         | 0.4%    |
| Kllisre                      | 6         | 0.3%    |
| Smart Modular                | 5         | 0.25%   |
| Avant                        | 5         | 0.25%   |
| RZX                          | 4         | 0.2%    |
| Carry                        | 4         | 0.2%    |
| Unknown                      | 4         | 0.2%    |
| PUSKILL                      | 3         | 0.15%   |
| Kingmax                      | 3         | 0.15%   |
| HBS                          | 3         | 0.15%   |
| Unknown (898F)               | 2         | 0.1%    |
| Team                         | 2         | 0.1%    |
| Positivo                     | 2         | 0.1%    |
| Lexar                        | 2         | 0.1%    |
| G.Skill                      | 2         | 0.1%    |
| CSX                          | 2         | 0.1%    |
| Catalyst                     | 2         | 0.1%    |
| Apogee                       | 2         | 0.1%    |
| ZIFEI                        | 1         | 0.05%   |
| Walton Chaintech             | 1         | 0.05%   |
| Unknown (8A02)               | 1         | 0.05%   |
| Unknown (0xC209)             | 1         | 0.05%   |
| Unknown (0x0194)             | 1         | 0.05%   |
| Unknown (0x0043415455000000) | 1         | 0.05%   |
| Unknown (08AE)               | 1         | 0.05%   |
| Unifosa                      | 1         | 0.05%   |
| Transcend                    | 1         | 0.05%   |
| Super Talent                 | 1         | 0.05%   |
| Qumo                         | 1         | 0.05%   |
| Kreton                       | 1         | 0.05%   |
| KANMEIQi                     | 1         | 0.05%   |
| Intel                        | 1         | 0.05%   |
| Hewlett-Packard              | 1         | 0.05%   |
| Goldkey                      | 1         | 0.05%   |
| Golden Empire                | 1         | 0.05%   |
| DigiBoard                    | 1         | 0.05%   |
| Atermiter                    | 1         | 0.05%   |
| Apotop                       | 1         | 0.05%   |
| 89F700000000                 | 1         | 0.05%   |
| 48spaces                     | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 66        | 3.05%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 37        | 1.71%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 37        | 1.71%   |
| Smart RAM SH564568FH8NZPHSCR 2048MB SODIMM DDR3 1333MT/s            | 36        | 1.66%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s            | 31        | 1.43%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s               | 30        | 1.38%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s               | 28        | 1.29%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 26        | 1.2%    |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s               | 24        | 1.11%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 23        | 1.06%   |
| Smart RAM SH564128FJ8NWRNSQR 4096MB SODIMM DDR3 1600MT/s            | 21        | 0.97%   |
| Smart RAM SH564128FJ8NZRNSDG 4096MB SODIMM DDR3 1600MT/s            | 20        | 0.92%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s              | 19        | 0.88%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s            | 18        | 0.83%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 18        | 0.83%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8192MB SODIMM DDR4 2400MT/s           | 17        | 0.78%   |
| Smart RAM SH564568FH8NZPHSCG 2048MB SODIMM DDR3 1333MT/s            | 15        | 0.69%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s               | 15        | 0.69%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s                | 14        | 0.65%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 14        | 0.65%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s               | 13        | 0.6%    |
| Smart RAM SH564568FH8NWPHSFG 2048MB SODIMM DDR3 1333MT/s            | 13        | 0.6%    |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s                | 13        | 0.6%    |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s               | 12        | 0.55%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                | 12        | 0.55%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s             | 12        | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 11        | 0.51%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 11        | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 11        | 0.51%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s         | 11        | 0.51%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 11        | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 10        | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 10        | 0.46%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 10        | 0.46%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 10        | 0.46%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s            | 10        | 0.46%   |
| A-DATA RAM AM1P26KC4U1-BACS 4GB SODIMM DDR4 2667MT/s                | 10        | 0.46%   |
| A-DATA RAM 11111111 4GB SODIMM DDR4 2400MT/s                        | 10        | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 9         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3                               | 9         | 0.42%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1600MT/s              | 9         | 0.42%   |
| Teikon RAM TMT251S6CFR8C-PBHC 4096MB SODIMM DDR3 1600MT/s           | 9         | 0.42%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s               | 9         | 0.42%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 9         | 0.42%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8192MB SODIMM DDR4 2667MT/s             | 9         | 0.42%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s              | 8         | 0.37%   |
| Teikon RAM TMA81GS6CJR8N-VKSC 8192MB SODIMM DDR4 2667MT/s           | 8         | 0.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 8         | 0.37%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s               | 8         | 0.37%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s               | 8         | 0.37%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s          | 8         | 0.37%   |
| HT Micron RAM HTH5AN8G6NAFR-UHD 4GB SODIMM DDR4 2400MT/s            | 8         | 0.37%   |
| High Bridge RAM HB3SU004GFM8MMD33 4GB SODIMM DDR3 1333MT/s          | 8         | 0.37%   |
| High Bridge RAM HB3SU002GFM8MMD33 2GB SODIMM DDR3 1333MT/s          | 8         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DRAM                               | 7         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 7         | 0.32%   |
| Teikon RAM TMT41GS6BFR8A-PBHC 8GB SODIMM DDR3 1600MT/s              | 7         | 0.32%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s            | 7         | 0.32%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1334MT/s               | 7         | 0.32%   |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s           | 7         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 797       | 48.1%   |
| DDR4    | 615       | 37.12%  |
| DDR2    | 109       | 6.58%   |
| SDRAM   | 50        | 3.02%   |
| LPDDR4  | 32        | 1.93%   |
| LPDDR3  | 22        | 1.33%   |
| DRAM    | 14        | 0.84%   |
| DDR     | 11        | 0.66%   |
| Unknown | 6         | 0.36%   |
| RAM     | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1579      | 96.4%   |
| Row Of Chips | 46        | 2.81%   |
| Unknown      | 8         | 0.49%   |
| DIMM         | 3         | 0.18%   |
| Chip         | 2         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 789       | 41.79%  |
| 8192  | 451       | 23.89%  |
| 2048  | 420       | 22.25%  |
| 16384 | 136       | 7.2%    |
| 1024  | 71        | 3.76%   |
| 32768 | 17        | 0.9%    |
| 512   | 4         | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 476       | 25.43%  |
| 2667    | 373       | 19.93%  |
| 2400    | 224       | 11.97%  |
| 1334    | 165       | 8.81%   |
| 1333    | 164       | 8.76%   |
| Unknown | 73        | 3.9%    |
| 2133    | 66        | 3.53%   |
| 3200    | 52        | 2.78%   |
| 800     | 47        | 2.51%   |
| 667     | 41        | 2.19%   |
| 1067    | 33        | 1.76%   |
| 4199    | 30        | 1.6%    |
| 1066    | 25        | 1.34%   |
| 533     | 18        | 0.96%   |
| 4267    | 16        | 0.85%   |
| 2048    | 16        | 0.85%   |
| 975     | 16        | 0.85%   |
| 3266    | 8         | 0.43%   |
| 1867    | 8         | 0.43%   |
| 2933    | 7         | 0.37%   |
| 1200    | 4         | 0.21%   |
| 3733    | 1         | 0.05%   |
| 2666    | 1         | 0.05%   |
| 2267    | 1         | 0.05%   |
| 1866    | 1         | 0.05%   |
| 1776    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 1400    | 1         | 0.05%   |
| 666     | 1         | 0.05%   |
| 2       | 1         | 0.05%   |
| 1       | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 18        | 39.13%  |
| Seiko Epson         | 17        | 36.96%  |
| Samsung Electronics | 4         | 8.7%    |
| Canon               | 3         | 6.52%   |
| Brother Industries  | 2         | 4.35%   |
| Xerox               | 1         | 2.17%   |
| MIIIW               | 1         | 2.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                   | 7         | 15.22%  |
| Seiko Epson L395 Series                      | 2         | 4.35%   |
| Seiko Epson ET-3750 Series                   | 2         | 4.35%   |
| HP LaserJet Professional P1102w              | 2         | 4.35%   |
| HP LaserJet 1020                             | 2         | 4.35%   |
| HP Deskjet 3050 J610 series                  | 2         | 4.35%   |
| HP Deskjet 2540 series                       | 2         | 4.35%   |
| Xerox Phaser 3040                            | 1         | 2.17%   |
| Seiko Epson XP-235 Series                    | 1         | 2.17%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 2.17%   |
| Seiko Epson L805 Series                      | 1         | 2.17%   |
| Seiko Epson L4150 Series                     | 1         | 2.17%   |
| Seiko Epson L380 Series                      | 1         | 2.17%   |
| Seiko Epson L222 Series                      | 1         | 2.17%   |
| Samsung SCX-4623 Series                      | 1         | 2.17%   |
| Samsung SCX-4200 series                      | 1         | 2.17%   |
| Samsung M332x 382x 402x Series               | 1         | 2.17%   |
| Samsung M2020 Series                         | 1         | 2.17%   |
| MIIIW MW Keyboard Air Mini                   | 1         | 2.17%   |
| HP LaserJet 1018                             | 1         | 2.17%   |
| HP Ink Tank Wireless 410 series              | 1         | 2.17%   |
| HP DeskJet F4200 series                      | 1         | 2.17%   |
| HP DeskJet F4100 Printer series              | 1         | 2.17%   |
| HP DeskJet D1360                             | 1         | 2.17%   |
| HP DeskJet 3630 series                       | 1         | 2.17%   |
| HP DeskJet 2700 series                       | 1         | 2.17%   |
| HP DeskJet 2300 series                       | 1         | 2.17%   |
| HP DeskJet 2130 series                       | 1         | 2.17%   |
| HP Deskjet 1510                              | 1         | 2.17%   |
| Canon G4010 series                           | 1         | 2.17%   |
| Canon G4000 series                           | 1         | 2.17%   |
| Canon G3000 series                           | 1         | 2.17%   |
| Brother HL-5250DN Printer                    | 1         | 2.17%   |
| Brother DCP-7040                             | 1         | 2.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 60%     |
| Hewlett-Packard | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HP ScanJet 2400c                   | 1         | 20%     |
| HP Scanjet 200                     | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 20%     |
| Canon CanoScan LiDE 110            | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1135      | 22.05%  |
| Microdia                               | 606       | 11.77%  |
| Realtek Semiconductor                  | 522       | 10.14%  |
| Quanta                                 | 494       | 9.6%    |
| Silicon Motion                         | 422       | 8.2%    |
| Sunplus Innovation Technology          | 399       | 7.75%   |
| Acer                                   | 366       | 7.11%   |
| Suyin                                  | 235       | 4.56%   |
| IMC Networks                           | 209       | 4.06%   |
| Syntek                                 | 164       | 3.19%   |
| Alcor Micro                            | 97        | 1.88%   |
| Cheng Uei Precision Industry (Foxlink) | 67        | 1.3%    |
| Apple                                  | 66        | 1.28%   |
| Samsung Electronics                    | 43        | 0.84%   |
| Ricoh                                  | 42        | 0.82%   |
| ALi                                    | 38        | 0.74%   |
| Logitech                               | 37        | 0.72%   |
| Importek                               | 22        | 0.43%   |
| Lite-On Technology                     | 20        | 0.39%   |
| Unknown                                | 19        | 0.37%   |
| OmniVision Technologies                | 18        | 0.35%   |
| Z-Star Microelectronics                | 15        | 0.29%   |
| Lenovo                                 | 10        | 0.19%   |
| LG Electronics                         | 9         | 0.17%   |
| Intel                                  | 9         | 0.17%   |
| Generalplus Technology                 | 8         | 0.16%   |
| Pixart Imaging                         | 6         | 0.12%   |
| Sunplus Technology                     | 5         | 0.1%    |
| Microsoft                              | 5         | 0.1%    |
| Image Processor                        | 5         | 0.1%    |
| DigiTech                               | 5         | 0.1%    |
| Camera                                 | 5         | 0.1%    |
| USB Camera                             | 4         | 0.08%   |
| JMicron Technology                     | 4         | 0.08%   |
| Foxconn / Hon Hai                      | 4         | 0.08%   |
| SunplusIT                              | 3         | 0.06%   |
| Primax Electronics                     | 3         | 0.06%   |
| Jieli Technology                       | 3         | 0.06%   |
| GEMBIRD                                | 3         | 0.06%   |
| Fitipower Integrated Technology        | 3         | 0.06%   |
| YGTek                                  | 2         | 0.04%   |
| Y Media                                | 2         | 0.04%   |
| GenesysLogic Technology                | 2         | 0.04%   |
| Denron                                 | 2         | 0.04%   |
| Xiaomi                                 | 1         | 0.02%   |
| WCM_USB                                | 1         | 0.02%   |
| MacroSilicon                           | 1         | 0.02%   |
| Luxvisions Innotech Limited            | 1         | 0.02%   |
| KYE Systems (Mouse Systems)            | 1         | 0.02%   |
| globaloptics                           | 1         | 0.02%   |
| Genesys Logic                          | 1         | 0.02%   |
| Cubeternet                             | 1         | 0.02%   |
| Arkmicro Technologies                  | 1         | 0.02%   |
| 8SSC20F27145V1SR19P0BEK                | 1         | 0.02%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD              | 214       | 4.15%   |
| Chicony HD WebCam                         | 208       | 4.04%   |
| Microdia Integrated_Webcam_HD             | 206       | 4%      |
| Quanta HD User Facing                     | 198       | 3.84%   |
| Chicony HD User Facing                    | 180       | 3.49%   |
| Sunplus Integrated_Webcam_HD              | 164       | 3.18%   |
| Quanta VGA WebCam                         | 161       | 3.12%   |
| Silicon Motion Web Camera                 | 152       | 2.95%   |
| Chicony VGA WebCam                        | 120       | 2.33%   |
| Chicony Integrated Camera                 | 107       | 2.08%   |
| Realtek Integrated Webcam                 | 91        | 1.77%   |
| Quanta HD Webcam                          | 88        | 1.71%   |
| Sunplus HD WebCam                         | 85        | 1.65%   |
| Syntek Integrated Camera                  | 83        | 1.61%   |
| Microdia Laptop_Integrated_Webcam_HD      | 75        | 1.46%   |
| Chicony USB 2.0 Camera                    | 70        | 1.36%   |
| Alcor Micro USB 2.0 Camera                | 59        | 1.14%   |
| Acer BisonCam, NB Pro                     | 59        | 1.14%   |
| Acer EasyCamera                           | 56        | 1.09%   |
| Acer Lenovo EasyCamera                    | 55        | 1.07%   |
| Realtek USB Camera                        | 51        | 0.99%   |
| Microdia Dell Laptop Integrated Webcam HD | 49        | 0.95%   |
| Samsung Galaxy A5 (MTP)                   | 43        | 0.83%   |
| Silicon Motion WebCam SC-10HDD12636N      | 42        | 0.82%   |
| Microdia Integrated Webcam HD             | 40        | 0.78%   |
| Acer VGA WebCam                           | 38        | 0.74%   |
| Silicon Motion WebCam SCB-1100N           | 37        | 0.72%   |
| Realtek HD WebCam                         | 36        | 0.7%    |
| Silicon Motion WebCam SC-13HDL11939N      | 33        | 0.64%   |
| Syntek EasyCamera                         | 32        | 0.62%   |
| IMC Networks Integrated Camera            | 32        | 0.62%   |
| Chicony EasyCamera                        | 31        | 0.6%    |
| Acer HD Webcam                            | 31        | 0.6%    |
| Suyin Integrated_Webcam_HD                | 30        | 0.58%   |
| Silicon Motion WebCam SCB-0385N           | 30        | 0.58%   |
| Chicony Lenovo EasyCamera                 | 30        | 0.58%   |
| Silicon Motion WebCam SC-0311139N         | 28        | 0.54%   |
| Microdia Integrated Webcam                | 28        | 0.54%   |
| IMC Networks USB2.0 HD UVC WebCam         | 28        | 0.54%   |
| Realtek EasyCamera                        | 27        | 0.52%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 27        | 0.52%   |
| Chicony USB2.0 VGA UVC WebCam             | 26        | 0.5%    |
| Chicony USB2.0 HD UVC WebCam              | 26        | 0.5%    |
| Chicony HP TrueVision HD                  | 26        | 0.5%    |
| Chicony HD WebCam (Acer)                  | 26        | 0.5%    |
| Suyin HP Webcam-101                       | 25        | 0.49%   |
| Apple FaceTime HD Camera                  | 25        | 0.49%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 23        | 0.45%   |
| Silicon Motion ATIV VGA Camera            | 23        | 0.45%   |
| Microdia Sonix USB 2.0 Camera             | 23        | 0.45%   |
| Chicony USB2.0 Camera                     | 23        | 0.45%   |
| Chicony Integrated Camera (1280x720@30)   | 23        | 0.45%   |
| Acer Integrated Camera                    | 22        | 0.43%   |
| Sunplus Integrated Webcam                 | 21        | 0.41%   |
| Microdia Webcam SC-10HDD12636P            | 20        | 0.39%   |
| Microdia Integrated_Webcam_1.3M           | 20        | 0.39%   |
| IMC Networks EasyCamera                   | 20        | 0.39%   |
| Apple iPhone 5/5C/5S/6/SE                 | 20        | 0.39%   |
| Syntek Lenovo EasyCamera                  | 19        | 0.37%   |
| OmniVision OV2640 Webcam                  | 18        | 0.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 235       | 50.76%  |
| Upek                       | 49        | 10.58%  |
| Synaptics                  | 48        | 10.37%  |
| AuthenTec                  | 45        | 9.72%   |
| Shenzhen Goodix Technology | 32        | 6.91%   |
| LighTuning Technology      | 26        | 5.62%   |
| Samsung Electronics        | 15        | 3.24%   |
| Elan Microelectronics      | 7         | 1.51%   |
| STMicroelectronics         | 3         | 0.65%   |
| Focal-systems.Corp         | 1         | 0.22%   |
| DigitalPersona             | 1         | 0.22%   |
| Dell                       | 1         | 0.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 83        | 17.93%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 41        | 8.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 25        | 5.4%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 4.97%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 4.54%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 21        | 4.54%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 20        | 4.32%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 4.32%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 4.1%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 17        | 3.67%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 15        | 3.24%   |
| Samsung Fingerprint Device                                                 | 15        | 3.24%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 2.59%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.59%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 2.16%   |
| Validity Sensors VFS491                                                    | 9         | 1.94%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 1.73%   |
| AuthenTec AES2810                                                          | 8         | 1.73%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 7         | 1.51%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 1.51%   |
| Synaptics  WBDI                                                            | 7         | 1.51%   |
| Elan ELAN:Fingerprint                                                      | 7         | 1.51%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.51%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.3%    |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 0.86%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.65%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.43%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.43%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.22%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.22%   |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.22%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.22%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.22%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.22%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.22%   |
| AuthenTec AES1600                                                          | 1         | 0.22%   |
| Unknown                                                                    | 1         | 0.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 65        | 52.85%  |
| Alcor Micro               | 20        | 16.26%  |
| Lenovo                    | 11        | 8.94%   |
| Upek                      | 8         | 6.5%    |
| Giesecke & Devrient       | 7         | 5.69%   |
| Aladdin Knowledge Systems | 4         | 3.25%   |
| Watchdata                 | 3         | 2.44%   |
| O2 Micro                  | 2         | 1.63%   |
| SCM Microsystems          | 1         | 0.81%   |
| Gemalto (was Gemplus)     | 1         | 0.81%   |
| Advanced Card Systems     | 1         | 0.81%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 16.26%  |
| Broadcom BCM5880 Secure Applications Processor                               | 19        | 15.45%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 13.01%  |
| Broadcom 5880                                                                | 16        | 13.01%  |
| Broadcom 58200                                                               | 14        | 11.38%  |
| Lenovo Integrated Smart Card Reader                                          | 11        | 8.94%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 6.5%    |
| Giesecke & Devrient StarSign CUT                                             | 5         | 4.07%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 3.25%   |
| Watchdata USB Key                                                            | 3         | 2.44%   |
| Giesecke & Devrient StarSign CUT S                                           | 2         | 1.63%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.81%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.81%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 0.81%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.81%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.81%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4454      | 77.69%  |
| 1     | 1123      | 19.59%  |
| 2     | 133       | 2.32%   |
| 3     | 14        | 0.24%   |
| 4     | 5         | 0.09%   |
| 7     | 2         | 0.03%   |
| 8     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 461       | 32.15%  |
| Graphics card            | 392       | 27.34%  |
| Multimedia controller    | 121       | 8.44%   |
| Chipcard                 | 113       | 7.88%   |
| Net/wireless             | 108       | 7.53%   |
| Bluetooth                | 63        | 4.39%   |
| Camera                   | 40        | 2.79%   |
| Storage                  | 32        | 2.23%   |
| Communication controller | 28        | 1.95%   |
| Sound                    | 20        | 1.39%   |
| Flash memory             | 19        | 1.32%   |
| Net/ethernet             | 16        | 1.12%   |
| Modem                    | 7         | 0.49%   |
| Card reader              | 7         | 0.49%   |
| Firewire controller      | 4         | 0.28%   |
| Unassigned class         | 1         | 0.07%   |
| Storage/ata              | 1         | 0.07%   |
| Network                  | 1         | 0.07%   |

