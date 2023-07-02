Ubuntu MATE 20.04 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 20.04.

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

Total: 408

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Studio 1558                 | [66e76ea87d](https://linux-hardware.org/?probe=66e76ea87d) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| Lenovo        | IdeaPad S410p 20296         | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| Avell High... | A72 HYB                     | [c6f131b8b1](https://linux-hardware.org/?probe=c6f131b8b1) | May 24, 2023 |
| Avell High... | A72 HYB                     | [d54fb61d87](https://linux-hardware.org/?probe=d54fb61d87) | May 24, 2023 |
| HP            | Compaq Presario CQ60        | [5b51a121e2](https://linux-hardware.org/?probe=5b51a121e2) | May 18, 2023 |
| HP            | Laptop 15-ef2xxx            | [83f752ffd8](https://linux-hardware.org/?probe=83f752ffd8) | Apr 17, 2023 |
| ASUSTek       | U6Sg                        | [c97f807bb0](https://linux-hardware.org/?probe=c97f807bb0) | Apr 01, 2023 |
| Dell          | Latitude E6320              | [a6a0d01947](https://linux-hardware.org/?probe=a6a0d01947) | Mar 31, 2023 |
| Packard Be... | EasyNote TE11HC             | [ce6f515364](https://linux-hardware.org/?probe=ce6f515364) | Mar 19, 2023 |
| Packard Be... | EasyNote TE11HC             | [0bb94771bc](https://linux-hardware.org/?probe=0bb94771bc) | Mar 18, 2023 |
| Packard Be... | EasyNote TE11HC             | [4a54741fec](https://linux-hardware.org/?probe=4a54741fec) | Mar 12, 2023 |
| Packard Be... | EasyNote TE11HC             | [fb3c4afbaa](https://linux-hardware.org/?probe=fb3c4afbaa) | Feb 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| Lenovo        | G500 20236                  | [d92542c9e8](https://linux-hardware.org/?probe=d92542c9e8) | Jan 14, 2023 |
| Acer          | AO756                       | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| Dell          | G5 5590                     | [c0bba3f9fd](https://linux-hardware.org/?probe=c0bba3f9fd) | Jan 04, 2023 |
| Dell          | G5 5590                     | [cb89cf0f00](https://linux-hardware.org/?probe=cb89cf0f00) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-C            | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Dell          | Latitude E5430 non-vPro     | [cc88046606](https://linux-hardware.org/?probe=cc88046606) | Dec 22, 2022 |
| ASUSTek       | T100TA                      | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| Dell          | Studio 1558                 | [ef9a6b217c](https://linux-hardware.org/?probe=ef9a6b217c) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | [ea7c3c0cc4](https://linux-hardware.org/?probe=ea7c3c0cc4) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | [39ecfb673f](https://linux-hardware.org/?probe=39ecfb673f) | Nov 19, 2022 |
| Sony          | VGN-CR120E                  | [99def76c59](https://linux-hardware.org/?probe=99def76c59) | Nov 12, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Dell          | Studio 1558                 | [8b5cb100a8](https://linux-hardware.org/?probe=8b5cb100a8) | Nov 05, 2022 |
| HP            | Pavilion g6                 | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| HP            | Compaq Presario CQ71        | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Samsung       | 760XBE                      | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Samsung       | 760XBE                      | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| Lenovo        | B51-30 80LK                 | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| HP            | EliteBook 840 G3            | [2643af430d](https://linux-hardware.org/?probe=2643af430d) | Oct 08, 2022 |
| HP            | 15                          | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Dell          | Precision 7520              | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| ASUSTek       | T100TA                      | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| HP            | Pavilion dv5                | [dd2f0b859b](https://linux-hardware.org/?probe=dd2f0b859b) | Aug 24, 2022 |
| HP            | ProBook 455 G7              | [c563966e9c](https://linux-hardware.org/?probe=c563966e9c) | Aug 06, 2022 |
| Google        | Swanky                      | [f54bdd7887](https://linux-hardware.org/?probe=f54bdd7887) | Aug 04, 2022 |
| Google        | Swanky                      | [daac706167](https://linux-hardware.org/?probe=daac706167) | Aug 02, 2022 |
| HP            | Pavilion g6                 | [b48c146eff](https://linux-hardware.org/?probe=b48c146eff) | Aug 01, 2022 |
| Acer          | Aspire 5050                 | [59d8bb1e10](https://linux-hardware.org/?probe=59d8bb1e10) | Jul 26, 2022 |
| Acer          | Aspire 5050                 | [a8bcc56e78](https://linux-hardware.org/?probe=a8bcc56e78) | Jul 26, 2022 |
| HP            | EliteBook 8570p             | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| Dell          | Latitude XT                 | [9d9deeace5](https://linux-hardware.org/?probe=9d9deeace5) | Jul 10, 2022 |
| Dell          | Latitude XT                 | [b0a096fb7d](https://linux-hardware.org/?probe=b0a096fb7d) | Jul 10, 2022 |
| MicroByte     | ezbook                      | [0f08faf963](https://linux-hardware.org/?probe=0f08faf963) | Jul 08, 2022 |
| Dell          | XPS 17 9710                 | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| Dell          | XPS 13 9360                 | [73746e5672](https://linux-hardware.org/?probe=73746e5672) | Jun 03, 2022 |
| Fujitsu       | LIFEBOOK E5511              | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| HP            | Stream Laptop 11-ak1xxx     | [2d2044b499](https://linux-hardware.org/?probe=2d2044b499) | May 30, 2022 |
| HP            | Pavilion Power Laptop 15... | [4813c4e0b4](https://linux-hardware.org/?probe=4813c4e0b4) | May 28, 2022 |
| HP            | ProBook 650 G1              | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Medion        | Akoya E6415                 | [32545030d4](https://linux-hardware.org/?probe=32545030d4) | May 16, 2022 |
| Avell High... | A70 MOB                     | [c8900ed973](https://linux-hardware.org/?probe=c8900ed973) | May 15, 2022 |
| Avell High... | A62 LIV                     | [8b912c2c4f](https://linux-hardware.org/?probe=8b912c2c4f) | May 15, 2022 |
| HP            | Laptop 17-by3xxx            | [86c82d9ca0](https://linux-hardware.org/?probe=86c82d9ca0) | May 03, 2022 |
| HP            | Laptop 17-by3xxx            | [a55c5c5c9f](https://linux-hardware.org/?probe=a55c5c5c9f) | May 03, 2022 |
| Toshiba       | Satellite C660              | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| Dell          | Precision 3561              | [26fa0f202c](https://linux-hardware.org/?probe=26fa0f202c) | Apr 20, 2022 |
| Clevo         | W54xEU                      | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | [2f865445ce](https://linux-hardware.org/?probe=2f865445ce) | Apr 14, 2022 |
| Dell          | Latitude E5530 non-vPro     | [d32ffb065a](https://linux-hardware.org/?probe=d32ffb065a) | Apr 14, 2022 |
| Clevo         | W54xEU                      | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Dell          | XPS 15 9500                 | [d873b2d218](https://linux-hardware.org/?probe=d873b2d218) | Apr 14, 2022 |
| Dell          | XPS 13 9380                 | [0897999e8d](https://linux-hardware.org/?probe=0897999e8d) | Apr 13, 2022 |
| Samsung       | R505                        | [9ff46a8ca6](https://linux-hardware.org/?probe=9ff46a8ca6) | Apr 13, 2022 |
| Dell          | Latitude E5400              | [0ac76c891f](https://linux-hardware.org/?probe=0ac76c891f) | Apr 11, 2022 |
| Lenovo        | G700 20251                  | [790d42fec8](https://linux-hardware.org/?probe=790d42fec8) | Mar 30, 2022 |
| Lenovo        | G700 20251                  | [d8166d09e9](https://linux-hardware.org/?probe=d8166d09e9) | Mar 30, 2022 |
| HP            | Pavilion dv7                | [112a1842a0](https://linux-hardware.org/?probe=112a1842a0) | Mar 30, 2022 |
| Samsung       | R530/R730/R540              | [186f96a5a1](https://linux-hardware.org/?probe=186f96a5a1) | Mar 27, 2022 |
| Dell          | Studio 1558                 | [7004b83ddf](https://linux-hardware.org/?probe=7004b83ddf) | Mar 23, 2022 |
| Dell          | Vostro 3350                 | [721a0ea932](https://linux-hardware.org/?probe=721a0ea932) | Mar 21, 2022 |
| ASUSTek       | X541UV                      | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| HP            | Pavilion dv7                | [0eb8ef5cd3](https://linux-hardware.org/?probe=0eb8ef5cd3) | Mar 16, 2022 |
| Dell          | Vostro 3401                 | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| Toshiba       | Satellite P755              | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| ASUSTek       | 1011PX                      | [776d052837](https://linux-hardware.org/?probe=776d052837) | Mar 09, 2022 |
| ASUSTek       | UX305FA                     | [6618b00369](https://linux-hardware.org/?probe=6618b00369) | Feb 28, 2022 |
| Fujitsu       | LIFEBOOK S752               | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| Acer          | Aspire E1-571G              | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| Lenovo        | ThinkPad T460p 20FW000VU... | [9cbb915f78](https://linux-hardware.org/?probe=9cbb915f78) | Feb 18, 2022 |
| ASUSTek       | X553MA                      | [94ebaa5d9b](https://linux-hardware.org/?probe=94ebaa5d9b) | Feb 15, 2022 |
| Acer          | Aspire 7735                 | [38d97cd9da](https://linux-hardware.org/?probe=38d97cd9da) | Feb 06, 2022 |
| Dell          | XPS 15 9570                 | [d1f8ff2cb8](https://linux-hardware.org/?probe=d1f8ff2cb8) | Feb 02, 2022 |
| Dell          | Latitude 3410               | [8f2181125e](https://linux-hardware.org/?probe=8f2181125e) | Jan 27, 2022 |
| ASUSTek       | X553MA                      | [a748bb8955](https://linux-hardware.org/?probe=a748bb8955) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [08613587e8](https://linux-hardware.org/?probe=08613587e8) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [f5b0fd8e22](https://linux-hardware.org/?probe=f5b0fd8e22) | Jan 18, 2022 |
| Dell          | XPS 12 9Q23                 | [3c8e26636b](https://linux-hardware.org/?probe=3c8e26636b) | Jan 15, 2022 |
| Dell          | Latitude E5400              | [4f72d3dae0](https://linux-hardware.org/?probe=4f72d3dae0) | Jan 09, 2022 |
| ASUSTek       | X541SA                      | [4103077e59](https://linux-hardware.org/?probe=4103077e59) | Jan 08, 2022 |
| Lenovo        | Flex 2-14 20404             | [1ddb6e11fb](https://linux-hardware.org/?probe=1ddb6e11fb) | Jan 01, 2022 |
| Acer          | Aspire A515-43              | [82163f143b](https://linux-hardware.org/?probe=82163f143b) | Dec 29, 2021 |
| Lenovo        | ThinkPad X131e 33722VU      | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| Lenovo        | G580 2189                   | [843f8c04fe](https://linux-hardware.org/?probe=843f8c04fe) | Dec 21, 2021 |
| HP            | ENVY Notebook               | [69b60fabe0](https://linux-hardware.org/?probe=69b60fabe0) | Dec 15, 2021 |
| Acer          | Aspire ES1-523              | [66a8186276](https://linux-hardware.org/?probe=66a8186276) | Dec 15, 2021 |
| Unknown       | Unknown                     | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| HP            | EliteBook Folio 9480m       | [2cd39490da](https://linux-hardware.org/?probe=2cd39490da) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | [4f46a6c92a](https://linux-hardware.org/?probe=4f46a6c92a) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | [1521941a87](https://linux-hardware.org/?probe=1521941a87) | Dec 02, 2021 |
| Dell          | Latitude E6400              | [170f397883](https://linux-hardware.org/?probe=170f397883) | Dec 02, 2021 |
| HP            | EliteBook Folio 9480m       | [3b06bfa748](https://linux-hardware.org/?probe=3b06bfa748) | Dec 01, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| Polaroid      | MP1464PR001                 | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| HP            | EliteBook Folio 9480m       | [8b5c3b008f](https://linux-hardware.org/?probe=8b5c3b008f) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | [bf8ac4dc12](https://linux-hardware.org/?probe=bf8ac4dc12) | Nov 24, 2021 |
| Dell          | Precision 5560              | [aa3dbdc6bb](https://linux-hardware.org/?probe=aa3dbdc6bb) | Nov 22, 2021 |
| Acer          | TravelMate 5720             | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| HP            | ZBook Fury 17.3 inch G8 ... | [63f392ea8b](https://linux-hardware.org/?probe=63f392ea8b) | Nov 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [3ddad52d21](https://linux-hardware.org/?probe=3ddad52d21) | Nov 16, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [162531d482](https://linux-hardware.org/?probe=162531d482) | Nov 16, 2021 |
| Dell          | Vostro 5568                 | [403ef45f63](https://linux-hardware.org/?probe=403ef45f63) | Nov 15, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | [e881f41269](https://linux-hardware.org/?probe=e881f41269) | Nov 14, 2021 |
| AMI           | Unknown                     | [d1cd5b09e1](https://linux-hardware.org/?probe=d1cd5b09e1) | Nov 12, 2021 |
| Toshiba       | Satellite C665              | [a136cdd51d](https://linux-hardware.org/?probe=a136cdd51d) | Nov 11, 2021 |
| HP            | ZBook 15                    | [835fb0e921](https://linux-hardware.org/?probe=835fb0e921) | Nov 10, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c8b67f9143](https://linux-hardware.org/?probe=c8b67f9143) | Nov 08, 2021 |
| GPD           | P2 MAX                      | [9adb3fd2eb](https://linux-hardware.org/?probe=9adb3fd2eb) | Nov 02, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [10e9f4b604](https://linux-hardware.org/?probe=10e9f4b604) | Oct 27, 2021 |
| Dell          | Precision 7520              | [83df635945](https://linux-hardware.org/?probe=83df635945) | Oct 26, 2021 |
| HP            | Pavilion Notebook           | [cd2454732b](https://linux-hardware.org/?probe=cd2454732b) | Oct 25, 2021 |
| Lenovo        | ThinkPad L512 2598A59       | [0bc832bd49](https://linux-hardware.org/?probe=0bc832bd49) | Oct 19, 2021 |
| Lenovo        | B570e HuronRiver Platfor... | [2bc2b5c1d6](https://linux-hardware.org/?probe=2bc2b5c1d6) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [36f407c3aa](https://linux-hardware.org/?probe=36f407c3aa) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [1b3b80e104](https://linux-hardware.org/?probe=1b3b80e104) | Oct 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [8917a2fc6b](https://linux-hardware.org/?probe=8917a2fc6b) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [b566b7f862](https://linux-hardware.org/?probe=b566b7f862) | Oct 13, 2021 |
| ASUSTek       | U36SD                       | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [26453872b1](https://linux-hardware.org/?probe=26453872b1) | Oct 12, 2021 |
| ASUSTek       | N43SL                       | [c5adc8860e](https://linux-hardware.org/?probe=c5adc8860e) | Oct 09, 2021 |
| Lenovo        | Z51-70 80K6                 | [219e5cd0d5](https://linux-hardware.org/?probe=219e5cd0d5) | Oct 04, 2021 |
| HP            | ProBook 455 G7              | [491cab82de](https://linux-hardware.org/?probe=491cab82de) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | [04ff8f3c32](https://linux-hardware.org/?probe=04ff8f3c32) | Sep 29, 2021 |
| Dell          | Vostro 3350                 | [384af306e6](https://linux-hardware.org/?probe=384af306e6) | Sep 27, 2021 |
| Acer          | Aspire A515-43              | [523fe48a54](https://linux-hardware.org/?probe=523fe48a54) | Sep 19, 2021 |
| Teclast       | F15S                        | [b6fcd1a34d](https://linux-hardware.org/?probe=b6fcd1a34d) | Sep 13, 2021 |
| Teclast       | F15S                        | [93d4fafebd](https://linux-hardware.org/?probe=93d4fafebd) | Sep 13, 2021 |
| Dell          | Vostro 3350                 | [0fdc4bc08a](https://linux-hardware.org/?probe=0fdc4bc08a) | Sep 13, 2021 |
| Dell          | Latitude E7450              | [012bae3aa2](https://linux-hardware.org/?probe=012bae3aa2) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [5ee9ab86d7](https://linux-hardware.org/?probe=5ee9ab86d7) | Aug 31, 2021 |
| Packard Be... | EasyNote SL65               | [934368dd02](https://linux-hardware.org/?probe=934368dd02) | Aug 20, 2021 |
| Lenovo        | ThinkPad T420 4180PA9       | [17b9828f96](https://linux-hardware.org/?probe=17b9828f96) | Aug 19, 2021 |
| ASUSTek       | X556UAK                     | [70e369f2ba](https://linux-hardware.org/?probe=70e369f2ba) | Aug 19, 2021 |
| Acer          | Extensa 5630                | [f32dfbfe2a](https://linux-hardware.org/?probe=f32dfbfe2a) | Aug 15, 2021 |
| HP            | Notebook                    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| Chuwi         | GemiBook Pro                | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| ASUSTek       | X556UAK                     | [399d9ceec5](https://linux-hardware.org/?probe=399d9ceec5) | Aug 06, 2021 |
| Intel         | AMI                         | [c11ff5c3a9](https://linux-hardware.org/?probe=c11ff5c3a9) | Aug 06, 2021 |
| Intel         | AMI                         | [bfe9befd10](https://linux-hardware.org/?probe=bfe9befd10) | Aug 05, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Acer          | Aspire E1-571               | [561ec14e6b](https://linux-hardware.org/?probe=561ec14e6b) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | [068e66bfae](https://linux-hardware.org/?probe=068e66bfae) | Jul 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [49be4c6d59](https://linux-hardware.org/?probe=49be4c6d59) | Jul 23, 2021 |
| Toshiba       | Satellite C660              | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Dell          | Studio 1558                 | [d1fad8f698](https://linux-hardware.org/?probe=d1fad8f698) | Jul 16, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [90235ac63a](https://linux-hardware.org/?probe=90235ac63a) | Jun 30, 2021 |
| HP            | EliteBook 2170p             | [212819389c](https://linux-hardware.org/?probe=212819389c) | Jun 25, 2021 |
| HP            | Pavilion dv7                | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| Dell          | Latitude E6400              | [547126dd82](https://linux-hardware.org/?probe=547126dd82) | Jun 20, 2021 |
| Dell          | Latitude E6510              | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| ASUSTek       | K73SJ                       | [cb0f042995](https://linux-hardware.org/?probe=cb0f042995) | Jun 04, 2021 |
| Dell          | Latitude 7420               | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| HP            | Pavilion                    | [1fa0cb66b1](https://linux-hardware.org/?probe=1fa0cb66b1) | May 26, 2021 |
| Dell          | Precision M4800             | [a85ce8a041](https://linux-hardware.org/?probe=a85ce8a041) | May 24, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Unknown       | Unknown                     | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite C675              | [5225757c73](https://linux-hardware.org/?probe=5225757c73) | May 19, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Lenovo        | ThinkPad E520 11433KG       | [336659ac3a](https://linux-hardware.org/?probe=336659ac3a) | May 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Toshiba       | Satellite Pro C660          | [d4ed145cfd](https://linux-hardware.org/?probe=d4ed145cfd) | May 14, 2021 |
| Dell          | G7 7588                     | [8ae4bf0bf2](https://linux-hardware.org/?probe=8ae4bf0bf2) | May 10, 2021 |
| Cube          | i18-L                       | [77cd23575f](https://linux-hardware.org/?probe=77cd23575f) | May 07, 2021 |
| HP            | Pavilion                    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [90d1b76313](https://linux-hardware.org/?probe=90d1b76313) | May 04, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| ONE-NETBOO... | A1                          | [86c38b0aca](https://linux-hardware.org/?probe=86c38b0aca) | Apr 23, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3835eff7c6](https://linux-hardware.org/?probe=3835eff7c6) | Apr 21, 2021 |
| Dell          | Inspiron 3480               | [75f43079fb](https://linux-hardware.org/?probe=75f43079fb) | Apr 13, 2021 |
| Dell          | Inspiron 3480               | [dce5f8220a](https://linux-hardware.org/?probe=dce5f8220a) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [fb0db0afbd](https://linux-hardware.org/?probe=fb0db0afbd) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [236be7c7e7](https://linux-hardware.org/?probe=236be7c7e7) | Apr 12, 2021 |
| HP            | Pavilion dv6                | [bf634bb665](https://linux-hardware.org/?probe=bf634bb665) | Apr 09, 2021 |
| HP            | 15                          | [acc9ccddfa](https://linux-hardware.org/?probe=acc9ccddfa) | Apr 08, 2021 |
| HP            | ProBook 4530s               | [12a7784eb4](https://linux-hardware.org/?probe=12a7784eb4) | Apr 06, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fa8acecaa2](https://linux-hardware.org/?probe=fa8acecaa2) | Apr 01, 2021 |
| Dell          | Latitude E7250              | [d88e8eb416](https://linux-hardware.org/?probe=d88e8eb416) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| Dell          | Latitude 7310               | [9f4c2f64a5](https://linux-hardware.org/?probe=9f4c2f64a5) | Mar 30, 2021 |
| Dell          | Latitude E7250              | [d1716d96f2](https://linux-hardware.org/?probe=d1716d96f2) | Mar 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [dc5e67af5a](https://linux-hardware.org/?probe=dc5e67af5a) | Mar 27, 2021 |
| Acer          | Aspire 4740                 | [3551944dd9](https://linux-hardware.org/?probe=3551944dd9) | Mar 25, 2021 |
| Samsung       | 760XBE                      | [3cacabef7b](https://linux-hardware.org/?probe=3cacabef7b) | Mar 23, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | [92bcacad15](https://linux-hardware.org/?probe=92bcacad15) | Mar 22, 2021 |
| Samsung       | 760XBE                      | [26e28d0645](https://linux-hardware.org/?probe=26e28d0645) | Mar 21, 2021 |
| ASUSTek       | K50IE                       | [cc01498ee9](https://linux-hardware.org/?probe=cc01498ee9) | Mar 18, 2021 |
| MSI           | GF63 Thin 9SCSR             | [f58ddcc3f4](https://linux-hardware.org/?probe=f58ddcc3f4) | Mar 17, 2021 |
| Acer          | Aspire A515-56              | [1919b6a57f](https://linux-hardware.org/?probe=1919b6a57f) | Mar 17, 2021 |
| HP            | Pavilion g7                 | [cc361e0dbf](https://linux-hardware.org/?probe=cc361e0dbf) | Mar 04, 2021 |
| Toshiba       | Satellite L350D             | [0286dc8c95](https://linux-hardware.org/?probe=0286dc8c95) | Mar 02, 2021 |
| HP            | Pavilion g7                 | [41d55a3dd7](https://linux-hardware.org/?probe=41d55a3dd7) | Feb 26, 2021 |
| Dell          | Precision M4800             | [45c92f0ad1](https://linux-hardware.org/?probe=45c92f0ad1) | Feb 22, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [5bd6c548d2](https://linux-hardware.org/?probe=5bd6c548d2) | Feb 15, 2021 |
| Positivo      | N8X0EK1                     | [c6ac8d6eca](https://linux-hardware.org/?probe=c6ac8d6eca) | Feb 15, 2021 |
| Dell          | Latitude E6500              | [75d199bcfd](https://linux-hardware.org/?probe=75d199bcfd) | Feb 12, 2021 |
| Dell          | Studio 1747                 | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | [952ca96633](https://linux-hardware.org/?probe=952ca96633) | Feb 09, 2021 |
| Notebook      | W310CZ/CZ-T                 | [2b60fc9e91](https://linux-hardware.org/?probe=2b60fc9e91) | Feb 09, 2021 |
| Acer          | Aspire ES1-521              | [73b3295031](https://linux-hardware.org/?probe=73b3295031) | Jan 29, 2021 |
| Dell          | G7 7588                     | [ae6d47978a](https://linux-hardware.org/?probe=ae6d47978a) | Jan 28, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [4cae7dc78d](https://linux-hardware.org/?probe=4cae7dc78d) | Jan 18, 2021 |
| HP            | 250 G5 Notebook PC          | [f2e3b573f5](https://linux-hardware.org/?probe=f2e3b573f5) | Jan 16, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [e8b3cf2cbd](https://linux-hardware.org/?probe=e8b3cf2cbd) | Jan 14, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [8117aff9b0](https://linux-hardware.org/?probe=8117aff9b0) | Jan 14, 2021 |
| Medion        | X682X                       | [bf7dbceaa3](https://linux-hardware.org/?probe=bf7dbceaa3) | Jan 13, 2021 |
| Dell          | XPS 13 9370                 | [1b3b03be98](https://linux-hardware.org/?probe=1b3b03be98) | Jan 07, 2021 |
| HP            | 255 G7 Notebook PC          | [4f385a65db](https://linux-hardware.org/?probe=4f385a65db) | Jan 03, 2021 |
| Samsung       | SR58P                       | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [e253bc608d](https://linux-hardware.org/?probe=e253bc608d) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1483935c23](https://linux-hardware.org/?probe=1483935c23) | Jan 02, 2021 |
| Acer          | Aspire E1-532P              | [a1f1287741](https://linux-hardware.org/?probe=a1f1287741) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [30041ef295](https://linux-hardware.org/?probe=30041ef295) | Jan 01, 2021 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HP            | Notebook                    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA32VLM    | [cfa92bb7f3](https://linux-hardware.org/?probe=cfa92bb7f3) | Dec 28, 2020 |
| ASUSTek       | X302LA                      | [f5dde37fb9](https://linux-hardware.org/?probe=f5dde37fb9) | Dec 26, 2020 |
| ASUSTek       | X302LA                      | [a35e9f4b28](https://linux-hardware.org/?probe=a35e9f4b28) | Dec 25, 2020 |
| Star Labs     | LabTop                      | [b8c8467e92](https://linux-hardware.org/?probe=b8c8467e92) | Dec 20, 2020 |
| Toshiba       | Satellite Pro L500          | [d01d9e0d34](https://linux-hardware.org/?probe=d01d9e0d34) | Dec 08, 2020 |
| Dell          | Inspiron 3520               | [be6f5d9f85](https://linux-hardware.org/?probe=be6f5d9f85) | Dec 07, 2020 |
| Dell          | Latitude D630               | [475177f3da](https://linux-hardware.org/?probe=475177f3da) | Dec 07, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | [5862508036](https://linux-hardware.org/?probe=5862508036) | Dec 06, 2020 |
| HP            | Pavilion 17                 | [2f04deaf4e](https://linux-hardware.org/?probe=2f04deaf4e) | Dec 03, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [ee0aa7b52f](https://linux-hardware.org/?probe=ee0aa7b52f) | Dec 02, 2020 |
| Dell          | Precision 7710              | [f017e7a0d2](https://linux-hardware.org/?probe=f017e7a0d2) | Nov 30, 2020 |
| Acer          | Aspire E5-523               | [cfd9403111](https://linux-hardware.org/?probe=cfd9403111) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Dell          | Latitude E6400              | [a39e2e7fa3](https://linux-hardware.org/?probe=a39e2e7fa3) | Nov 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [833a22d4ee](https://linux-hardware.org/?probe=833a22d4ee) | Nov 20, 2020 |
| HP            | EliteBook 830 G6            | [c47a2f5f86](https://linux-hardware.org/?probe=c47a2f5f86) | Nov 18, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | [08c8440950](https://linux-hardware.org/?probe=08c8440950) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | [968f302807](https://linux-hardware.org/?probe=968f302807) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | [2a9231cde8](https://linux-hardware.org/?probe=2a9231cde8) | Nov 17, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [b8e7eedfed](https://linux-hardware.org/?probe=b8e7eedfed) | Nov 17, 2020 |
| Dell          | Latitude E6420              | [3452613a4c](https://linux-hardware.org/?probe=3452613a4c) | Nov 16, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d7abac1c02](https://linux-hardware.org/?probe=d7abac1c02) | Nov 07, 2020 |
| HP            | EliteBook Folio 9470m       | [659c1c8745](https://linux-hardware.org/?probe=659c1c8745) | Nov 06, 2020 |
| HP            | EliteBook Folio 9470m       | [248ce84271](https://linux-hardware.org/?probe=248ce84271) | Nov 05, 2020 |
| Dell          | Latitude E6420              | [6cdd815251](https://linux-hardware.org/?probe=6cdd815251) | Nov 04, 2020 |
| Dell          | Latitude E6420              | [10d44f2853](https://linux-hardware.org/?probe=10d44f2853) | Nov 04, 2020 |
| Acer          | Aspire A314-32              | [686d0b8c4f](https://linux-hardware.org/?probe=686d0b8c4f) | Nov 03, 2020 |
| Dell          | Latitude E6430              | [39ba29b6a3](https://linux-hardware.org/?probe=39ba29b6a3) | Nov 02, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | [d9a9dae79a](https://linux-hardware.org/?probe=d9a9dae79a) | Oct 31, 2020 |
| Lenovo        | ThinkPad E520 1143B5G       | [146fc730d7](https://linux-hardware.org/?probe=146fc730d7) | Oct 29, 2020 |
| MSI           | GE72 7RE                    | [f75b251f96](https://linux-hardware.org/?probe=f75b251f96) | Oct 29, 2020 |
| Acer          | Aspire 5715Z                | [a2fca6b9da](https://linux-hardware.org/?probe=a2fca6b9da) | Oct 26, 2020 |
| Lenovo        | V570 HuronRiver Platform    | [62082c183e](https://linux-hardware.org/?probe=62082c183e) | Oct 26, 2020 |
| ASUSTek       | X751LK                      | [0dad6a22c5](https://linux-hardware.org/?probe=0dad6a22c5) | Oct 26, 2020 |
| HP            | Pavilion dv7                | [59e2fce913](https://linux-hardware.org/?probe=59e2fce913) | Oct 26, 2020 |
| Dell          | Precision M4800             | [2f91204b5e](https://linux-hardware.org/?probe=2f91204b5e) | Oct 26, 2020 |
| HP            | 255 G7 Notebook PC          | [fd598f0888](https://linux-hardware.org/?probe=fd598f0888) | Oct 25, 2020 |
| Dell          | G3 3590                     | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| Lenovo        | ThinkPad E560 20EV0013MS    | [6a0824824b](https://linux-hardware.org/?probe=6a0824824b) | Oct 20, 2020 |
| Dell          | Latitude E6430              | [67b44ea2b4](https://linux-hardware.org/?probe=67b44ea2b4) | Oct 20, 2020 |
| HP            | Compaq 6730s                | [b8d5fd5eea](https://linux-hardware.org/?probe=b8d5fd5eea) | Oct 19, 2020 |
| HP            | Notebook                    | [669e2e8ce6](https://linux-hardware.org/?probe=669e2e8ce6) | Oct 19, 2020 |
| Lenovo        | G50-80 80R0                 | [51ec4152a2](https://linux-hardware.org/?probe=51ec4152a2) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c45c0eb7e4](https://linux-hardware.org/?probe=c45c0eb7e4) | Oct 16, 2020 |
| HP            | ProBook 4430s               | [c816b204bf](https://linux-hardware.org/?probe=c816b204bf) | Oct 15, 2020 |
| Lenovo        | ThinkPad X270 20HN0013MX    | [3dbb81e06d](https://linux-hardware.org/?probe=3dbb81e06d) | Oct 14, 2020 |
| Dell          | Latitude E6420              | [1e2a1974f2](https://linux-hardware.org/?probe=1e2a1974f2) | Oct 08, 2020 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [01948526e2](https://linux-hardware.org/?probe=01948526e2) | Oct 08, 2020 |
| Acer          | Aspire 5715Z                | [e112fe04f3](https://linux-hardware.org/?probe=e112fe04f3) | Oct 08, 2020 |
| Medion        | E15302                      | [957a41b1b5](https://linux-hardware.org/?probe=957a41b1b5) | Oct 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [28bab55cdf](https://linux-hardware.org/?probe=28bab55cdf) | Oct 02, 2020 |
| Lenovo        | ThinkPad X230 2325W5W       | [e2a36190d7](https://linux-hardware.org/?probe=e2a36190d7) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| System76      | Serval WS                   | [7add8e6511](https://linux-hardware.org/?probe=7add8e6511) | Sep 25, 2020 |
| Dell          | Precision M6700             | [1b20609aaa](https://linux-hardware.org/?probe=1b20609aaa) | Sep 25, 2020 |
| HP            | ProBook 440 G5              | [3140b90a75](https://linux-hardware.org/?probe=3140b90a75) | Sep 24, 2020 |
| Apple         | MacBook4,1                  | [91c2f7bfb9](https://linux-hardware.org/?probe=91c2f7bfb9) | Sep 20, 2020 |
| Dell          | Latitude E6410              | [6fa6138bb4](https://linux-hardware.org/?probe=6fa6138bb4) | Sep 18, 2020 |
| Dell          | Latitude E6410              | [8a3b88673f](https://linux-hardware.org/?probe=8a3b88673f) | Sep 17, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [a96ad52bc9](https://linux-hardware.org/?probe=a96ad52bc9) | Sep 16, 2020 |
| Dell          | Latitude E6410              | [8930b7e16f](https://linux-hardware.org/?probe=8930b7e16f) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [299b899172](https://linux-hardware.org/?probe=299b899172) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [b45cb0028d](https://linux-hardware.org/?probe=b45cb0028d) | Sep 16, 2020 |
| HP            | Compaq 8710w (GC124EA#AK... | [dc5006e254](https://linux-hardware.org/?probe=dc5006e254) | Sep 15, 2020 |
| Apple         | MacBook4,1                  | [092f9a6491](https://linux-hardware.org/?probe=092f9a6491) | Sep 15, 2020 |
| HP            | G42                         | [9cb42d6f5f](https://linux-hardware.org/?probe=9cb42d6f5f) | Sep 15, 2020 |
| HP            | G42                         | [72d647e1b9](https://linux-hardware.org/?probe=72d647e1b9) | Sep 15, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [956bfaaad9](https://linux-hardware.org/?probe=956bfaaad9) | Sep 11, 2020 |
| Acer          | Aspire A315-42G             | [ab24b14a42](https://linux-hardware.org/?probe=ab24b14a42) | Sep 09, 2020 |
| Samsung       | 530U4E/540U4E               | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| Dell          | Latitude E6420              | [e3bc793dc3](https://linux-hardware.org/?probe=e3bc793dc3) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [676828b4d4](https://linux-hardware.org/?probe=676828b4d4) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [6057658605](https://linux-hardware.org/?probe=6057658605) | Sep 01, 2020 |
| Dell          | Latitude E6420              | [9b1f1928c7](https://linux-hardware.org/?probe=9b1f1928c7) | Sep 01, 2020 |
| Positivo      | Mobile                      | [2249764f28](https://linux-hardware.org/?probe=2249764f28) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | [cae373d70b](https://linux-hardware.org/?probe=cae373d70b) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | [c77cf6f3fa](https://linux-hardware.org/?probe=c77cf6f3fa) | Aug 30, 2020 |
| Toshiba       | Satellite M500              | [42449081bb](https://linux-hardware.org/?probe=42449081bb) | Aug 29, 2020 |
| HP            | 250 G4 Notebook PC          | [97eeff2c12](https://linux-hardware.org/?probe=97eeff2c12) | Aug 22, 2020 |
| Lenovo        | ThinkPad W530 24478K0       | [74fda860f1](https://linux-hardware.org/?probe=74fda860f1) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | [ad30c07ac3](https://linux-hardware.org/?probe=ad30c07ac3) | Aug 17, 2020 |
| MSI           | GP72MVR 7RFX                | [39da2f58b5](https://linux-hardware.org/?probe=39da2f58b5) | Aug 16, 2020 |
| Dell          | Inspiron 7559               | [021ed0aac6](https://linux-hardware.org/?probe=021ed0aac6) | Aug 16, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0e5e076914](https://linux-hardware.org/?probe=0e5e076914) | Aug 15, 2020 |
| GPD           | MicroPC                     | [bb39ae1b31](https://linux-hardware.org/?probe=bb39ae1b31) | Aug 15, 2020 |
| Sony          | VPCEH1S1E                   | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3e086d75b0](https://linux-hardware.org/?probe=3e086d75b0) | Aug 12, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ab576b0cd8](https://linux-hardware.org/?probe=ab576b0cd8) | Aug 12, 2020 |
| ASUSTek       | X71SL                       | [f2da7fe3f0](https://linux-hardware.org/?probe=f2da7fe3f0) | Aug 12, 2020 |
| HP            | ZBook 14u G6                | [10911e8e46](https://linux-hardware.org/?probe=10911e8e46) | Aug 11, 2020 |
| HP            | Pavilion dm1                | [ccb974921b](https://linux-hardware.org/?probe=ccb974921b) | Aug 05, 2020 |
| ASUSTek       | X71SL                       | [7bfd99a9bd](https://linux-hardware.org/?probe=7bfd99a9bd) | Aug 05, 2020 |
| Dell          | System XPS L702X            | [86885b0835](https://linux-hardware.org/?probe=86885b0835) | Aug 04, 2020 |
| MSI           | GV62 8RD                    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| Dell          | Inspiron 3421               | [09aac7d871](https://linux-hardware.org/?probe=09aac7d871) | Aug 01, 2020 |
| Dell          | Precision M4800             | [defc3ac914](https://linux-hardware.org/?probe=defc3ac914) | Aug 01, 2020 |
| Lenovo        | Flex 2-14D 20376            | [efd445830e](https://linux-hardware.org/?probe=efd445830e) | Jul 27, 2020 |
| Dell          | Inspiron 7520               | [a1ea369f96](https://linux-hardware.org/?probe=a1ea369f96) | Jul 27, 2020 |
| Dell          | Inspiron 3421               | [12424c5a76](https://linux-hardware.org/?probe=12424c5a76) | Jul 25, 2020 |
| HP            | Pavilion g4                 | [a10cfaa6e2](https://linux-hardware.org/?probe=a10cfaa6e2) | Jul 24, 2020 |
| HP            | EliteBook 2570p             | [baa26535f9](https://linux-hardware.org/?probe=baa26535f9) | Jul 23, 2020 |
| Dell          | Vostro 3560                 | [c83b65951c](https://linux-hardware.org/?probe=c83b65951c) | Jul 20, 2020 |
| HP            | ZBook 17 G2                 | [61d82db95d](https://linux-hardware.org/?probe=61d82db95d) | Jul 20, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8e5e5de5c3](https://linux-hardware.org/?probe=8e5e5de5c3) | Jul 20, 2020 |
| HP            | 250 G5 Notebook PC          | [9577cafcf7](https://linux-hardware.org/?probe=9577cafcf7) | Jul 19, 2020 |
| Lenovo        | ThinkPad T490 20N3CTO1WW    | [b6f9682f0b](https://linux-hardware.org/?probe=b6f9682f0b) | Jul 15, 2020 |
| ASUSTek       | X555LJ                      | [5657a6a512](https://linux-hardware.org/?probe=5657a6a512) | Jul 14, 2020 |
| Dell          | G7 7588                     | [8c4a8875bd](https://linux-hardware.org/?probe=8c4a8875bd) | Jul 14, 2020 |
| Dell          | G7 7588                     | [aee8398552](https://linux-hardware.org/?probe=aee8398552) | Jul 12, 2020 |
| Sony          | VPCF1290X                   | [f7c7a3ca92](https://linux-hardware.org/?probe=f7c7a3ca92) | Jul 08, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [f4dd6bbdec](https://linux-hardware.org/?probe=f4dd6bbdec) | Jul 06, 2020 |
| Lenovo        | ThinkPad 11e 20D9CTO1WW     | [11c17aa062](https://linux-hardware.org/?probe=11c17aa062) | Jul 05, 2020 |
| Acer          | Aspire 7750G                | [f6a31e475d](https://linux-hardware.org/?probe=f6a31e475d) | Jul 05, 2020 |
| HP            | 250 G4                      | [ca40ef5473](https://linux-hardware.org/?probe=ca40ef5473) | Jul 02, 2020 |
| HP            | Pavilion g6                 | [0175164903](https://linux-hardware.org/?probe=0175164903) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| HP            | Pavilion g6                 | [efc97f097b](https://linux-hardware.org/?probe=efc97f097b) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [944b66e3ba](https://linux-hardware.org/?probe=944b66e3ba) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [3f58959650](https://linux-hardware.org/?probe=3f58959650) | Jun 24, 2020 |
| Lenovo        | ThinkPad T520 4243RS6       | [881175c7ec](https://linux-hardware.org/?probe=881175c7ec) | Jun 23, 2020 |
| HP            | ProBook 450 G5              | [143bbac73c](https://linux-hardware.org/?probe=143bbac73c) | Jun 23, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [c5a7e2708f](https://linux-hardware.org/?probe=c5a7e2708f) | Jun 22, 2020 |
| Lenovo        | ThinkPad X240 qqqq          | [04328e30ac](https://linux-hardware.org/?probe=04328e30ac) | Jun 15, 2020 |
| Sony          | VPCF1290X                   | [55652dadf6](https://linux-hardware.org/?probe=55652dadf6) | Jun 15, 2020 |
| Lenovo        | ThinkPad T430 2349H86       | [5ef2ab445e](https://linux-hardware.org/?probe=5ef2ab445e) | Jun 13, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [5467542c77](https://linux-hardware.org/?probe=5467542c77) | Jun 12, 2020 |
| HP            | Pavilion g6                 | [78f5ccb141](https://linux-hardware.org/?probe=78f5ccb141) | Jun 11, 2020 |
| Acer          | Nitro AN515-54              | [4c810c7859](https://linux-hardware.org/?probe=4c810c7859) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [35995e9a53](https://linux-hardware.org/?probe=35995e9a53) | Jun 06, 2020 |
| ASUSTek       | X541SA                      | [508fc56922](https://linux-hardware.org/?probe=508fc56922) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [d6bcbe862e](https://linux-hardware.org/?probe=d6bcbe862e) | Jun 05, 2020 |
| HP            | 250 G7 Notebook PC          | [56c24dddd4](https://linux-hardware.org/?probe=56c24dddd4) | May 31, 2020 |
| Packard Be... | EasyNote ME69BMP            | [7023dc94da](https://linux-hardware.org/?probe=7023dc94da) | May 28, 2020 |
| Dell          | Precision M6800             | [fac8dbf769](https://linux-hardware.org/?probe=fac8dbf769) | May 28, 2020 |
| Packard Be... | EasyNote ME69BMP            | [17cb4d2a9a](https://linux-hardware.org/?probe=17cb4d2a9a) | May 28, 2020 |
| Dell          | Precision M4800             | [4f404379b5](https://linux-hardware.org/?probe=4f404379b5) | May 27, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| Lenovo        | ThinkPad T480s 20L7001HM... | [8c6c9a5faa](https://linux-hardware.org/?probe=8c6c9a5faa) | May 25, 2020 |
| Toshiba       | Satellite M500              | [89bc529650](https://linux-hardware.org/?probe=89bc529650) | May 23, 2020 |
| Sony          | VPCF1290X                   | [6d41a82565](https://linux-hardware.org/?probe=6d41a82565) | May 22, 2020 |
| Sony          | VPCF1290X                   | [e260c25549](https://linux-hardware.org/?probe=e260c25549) | May 20, 2020 |
| ASUSTek       | X541SA                      | [af59d45f16](https://linux-hardware.org/?probe=af59d45f16) | May 19, 2020 |
| Dell          | Latitude E6400              | [5575a3dc87](https://linux-hardware.org/?probe=5575a3dc87) | May 17, 2020 |
| Dell          | Latitude E6400              | [4ad76f6e55](https://linux-hardware.org/?probe=4ad76f6e55) | May 16, 2020 |
| Dell          | Latitude E6400              | [9c8f7c7f2c](https://linux-hardware.org/?probe=9c8f7c7f2c) | May 16, 2020 |
| Dell          | Latitude E6400              | [0e2b5d699e](https://linux-hardware.org/?probe=0e2b5d699e) | May 16, 2020 |
| HP            | 250 G1                      | [bc48855d22](https://linux-hardware.org/?probe=bc48855d22) | May 16, 2020 |
| Lenovo        | ThinkPad X240 20AMS08816    | [5581eee295](https://linux-hardware.org/?probe=5581eee295) | May 10, 2020 |
| Dell          | System XPS L502X            | [f095fb06d8](https://linux-hardware.org/?probe=f095fb06d8) | May 09, 2020 |
| HP            | EliteBook 840 G2            | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Samsung       | 550P5C/550P7C               | [4262f676d3](https://linux-hardware.org/?probe=4262f676d3) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | [015ef81b51](https://linux-hardware.org/?probe=015ef81b51) | May 02, 2020 |
| ASUSTek       | G73Sw                       | [d4abec1a93](https://linux-hardware.org/?probe=d4abec1a93) | May 02, 2020 |
| HP            | 250 G5 Notebook PC          | [f986b480ad](https://linux-hardware.org/?probe=f986b480ad) | May 01, 2020 |
| Dell          | Inspiron 3576               | [4dc9474ba1](https://linux-hardware.org/?probe=4dc9474ba1) | Apr 29, 2020 |
| Sony          | VPCS12X9E                   | [3631a4d89d](https://linux-hardware.org/?probe=3631a4d89d) | Apr 24, 2020 |
| Lenovo        | ThinkPad T460s 20F9003WM... | [1b1c89732c](https://linux-hardware.org/?probe=1b1c89732c) | Apr 19, 2020 |
| HP            | EliteBook 755 G5            | [db0ea12ab8](https://linux-hardware.org/?probe=db0ea12ab8) | Apr 16, 2020 |
| Dell          | XPS 13 9360                 | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [154b970640](https://linux-hardware.org/?probe=154b970640) | Mar 25, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [ad9b0ebdf6](https://linux-hardware.org/?probe=ad9b0ebdf6) | Feb 25, 2020 |
| Acer          | Aspire V3-574G              | [471f9aa9b0](https://linux-hardware.org/?probe=471f9aa9b0) | Jan 02, 2020 |
| MSI           | GP72 6QF                    | [98dc37dc79](https://linux-hardware.org/?probe=98dc37dc79) | Oct 21, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 24        | 7.27%   |
| 5.4.0-52-generic  | 17        | 5.15%   |
| 5.4.0-47-generic  | 10        | 3.03%   |
| 5.4.0-40-generic  | 10        | 3.03%   |
| 5.4.0-58-generic  | 9         | 2.73%   |
| 5.8.0-50-generic  | 8         | 2.42%   |
| 5.4.0-48-generic  | 8         | 2.42%   |
| 5.4.0-31-generic  | 8         | 2.42%   |
| 5.4.0-26-generic  | 8         | 2.42%   |
| 5.4.0-65-generic  | 7         | 2.12%   |
| 5.11.0-40-generic | 7         | 2.12%   |
| 5.4.0-56-generic  | 6         | 1.82%   |
| 5.4.0-54-generic  | 6         | 1.82%   |
| 5.4.0-45-generic  | 6         | 1.82%   |
| 5.11.0-38-generic | 6         | 1.82%   |
| 5.8.0-59-generic  | 5         | 1.52%   |
| 5.8.0-48-generic  | 5         | 1.52%   |
| 5.8.0-43-generic  | 5         | 1.52%   |
| 5.4.0-81-generic  | 5         | 1.52%   |
| 5.4.0-37-generic  | 5         | 1.52%   |
| 5.4.0-29-generic  | 5         | 1.52%   |
| 5.13.0-41-generic | 5         | 1.52%   |
| 5.13.0-30-generic | 5         | 1.52%   |
| 5.11.0-37-generic | 5         | 1.52%   |
| 5.8.0-53-generic  | 4         | 1.21%   |
| 5.4.0-91-generic  | 4         | 1.21%   |
| 5.4.0-89-generic  | 4         | 1.21%   |
| 5.4.0-51-generic  | 4         | 1.21%   |
| 5.13.0-39-generic | 4         | 1.21%   |
| 5.4.0-90-generic  | 3         | 0.91%   |
| 5.4.0-74-generic  | 3         | 0.91%   |
| 5.4.0-73-generic  | 3         | 0.91%   |
| 5.4.0-39-generic  | 3         | 0.91%   |
| 5.4.0-33-generic  | 3         | 0.91%   |
| 5.4.0-28-generic  | 3         | 0.91%   |
| 5.15.0-41-generic | 3         | 0.91%   |
| 5.11.0-43-generic | 3         | 0.91%   |
| 5.11.0-41-generic | 3         | 0.91%   |
| 5.11.0-27-generic | 3         | 0.91%   |
| 5.8.0-63-generic  | 2         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 183       | 60.4%   |
| 5.8.0   | 33        | 10.89%  |
| 5.11.0  | 31        | 10.23%  |
| 5.13.0  | 27        | 8.91%   |
| 5.15.0  | 18        | 5.94%   |
| 5.14.0  | 4         | 1.32%   |
| 5.3.0   | 2         | 0.66%   |
| 5.9.3   | 1         | 0.33%   |
| 5.8.17  | 1         | 0.33%   |
| 5.15.6  | 1         | 0.33%   |
| 5.15.34 | 1         | 0.33%   |
| 5.15.27 | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 183       | 60.4%   |
| 5.8     | 34        | 11.22%  |
| 5.11    | 31        | 10.23%  |
| 5.13    | 27        | 8.91%   |
| 5.15    | 21        | 6.93%   |
| 5.14    | 4         | 1.32%   |
| 5.3     | 2         | 0.66%   |
| 5.9     | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 299       | 99.67%  |
| aarch64 | 1         | 0.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 292       | 97.33%  |
| Cinnamon   | 3         | 1%      |
| GNOME      | 2         | 0.67%   |
| X-Cinnamon | 1         | 0.33%   |
| KDE5       | 1         | 0.33%   |
| i3         | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 294       | 98%     |
| Wayland | 3         | 1%      |
| Tty     | 3         | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 112       | 36.6%   |
| TDM     | 99        | 32.35%  |
| Unknown | 76        | 24.84%  |
| GDM     | 15        | 4.9%    |
| GDM3    | 3         | 0.98%   |
| SDDM    | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 111       | 36.88%  |
| fr_FR   | 33        | 10.96%  |
| pt_BR   | 30        | 9.97%   |
| en_GB   | 18        | 5.98%   |
| de_DE   | 16        | 5.32%   |
| es_ES   | 14        | 4.65%   |
| it_IT   | 11        | 3.65%   |
| ru_RU   | 8         | 2.66%   |
| C       | 7         | 2.33%   |
| ru_UA   | 6         | 1.99%   |
| pl_PL   | 5         | 1.66%   |
| es_AR   | 4         | 1.33%   |
| en_PH   | 3         | 1%      |
| en_IN   | 3         | 1%      |
| de_CH   | 3         | 1%      |
| nl_NL   | 2         | 0.66%   |
| en_CA   | 2         | 0.66%   |
| en_AU   | 2         | 0.66%   |
| ca_ES   | 2         | 0.66%   |
| zh_TW   | 1         | 0.33%   |
| zh_CN   | 1         | 0.33%   |
| uk_UA   | 1         | 0.33%   |
| sv_SE   | 1         | 0.33%   |
| sk_SK   | 1         | 0.33%   |
| nl_BE   | 1         | 0.33%   |
| hu_HU   | 1         | 0.33%   |
| fr_CH   | 1         | 0.33%   |
| fr_CA   | 1         | 0.33%   |
| fr_BE   | 1         | 0.33%   |
| fi_FI   | 1         | 0.33%   |
| et_EE   | 1         | 0.33%   |
| es_UY   | 1         | 0.33%   |
| es_PR   | 1         | 0.33%   |
| es_PE   | 1         | 0.33%   |
| es_MX   | 1         | 0.33%   |
| en_NZ   | 1         | 0.33%   |
| en_IE   | 1         | 0.33%   |
| da_DK   | 1         | 0.33%   |
| cs_CZ   | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 155       | 51.67%  |
| BIOS | 145       | 48.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 281       | 93.05%  |
| Overlay | 11        | 3.64%   |
| Btrfs   | 3         | 0.99%   |
| Zfs     | 2         | 0.66%   |
| Xfs     | 2         | 0.66%   |
| Ext3    | 2         | 0.66%   |
| Tmpfs   | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 120       | 39.74%  |
| Unknown | 97        | 32.12%  |
| MBR     | 85        | 28.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 269       | 87.91%  |
| Yes       | 37        | 12.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 208       | 68.87%  |
| Yes       | 94        | 31.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 65        | 21.67%  |
| Hewlett-Packard        | 62        | 20.67%  |
| Dell                   | 61        | 20.33%  |
| ASUSTek Computer       | 26        | 8.67%   |
| Acer                   | 21        | 7%      |
| Toshiba                | 10        | 3.33%   |
| Samsung Electronics    | 8         | 2.67%   |
| MSI                    | 7         | 2.33%   |
| Sony                   | 4         | 1.33%   |
| Packard Bell           | 3         | 1%      |
| Medion                 | 3         | 1%      |
| Avell High Performance | 3         | 1%      |
| Positivo               | 2         | 0.67%   |
| Notebook               | 2         | 0.67%   |
| GPD                    | 2         | 0.67%   |
| Fujitsu                | 2         | 0.67%   |
| Apple                  | 2         | 0.67%   |
| Unknown                | 2         | 0.67%   |
| Wortmann AG            | 1         | 0.33%   |
| TUXEDO                 | 1         | 0.33%   |
| Teclast                | 1         | 0.33%   |
| System76               | 1         | 0.33%   |
| Star Labs              | 1         | 0.33%   |
| Polaroid               | 1         | 0.33%   |
| Pine Microsystems      | 1         | 0.33%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.33%   |
| MicroByte              | 1         | 0.33%   |
| Intel                  | 1         | 0.33%   |
| Google                 | 1         | 0.33%   |
| Cube                   | 1         | 0.33%   |
| Clevo                  | 1         | 0.33%   |
| Chuwi                  | 1         | 0.33%   |
| AMI                    | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Dell Latitude E6420             | 5         | 1.67%   |
| HP Pavilion dv7                 | 4         | 1.33%   |
| HP Pavilion g6                  | 3         | 1%      |
| HP Notebook                     | 3         | 1%      |
| Dell Precision M4800            | 3         | 1%      |
| Dell Latitude E6410             | 3         | 1%      |
| Unknown                         | 3         | 1%      |
| Toshiba Satellite C660          | 2         | 0.67%   |
| HP EliteBook 8470p              | 2         | 0.67%   |
| HP 15                           | 2         | 0.67%   |
| Dell XPS 13 9360                | 2         | 0.67%   |
| Dell Vostro 3350                | 2         | 0.67%   |
| Dell Precision 7520             | 2         | 0.67%   |
| Dell Latitude E6430             | 2         | 0.67%   |
| Dell Inspiron 3421              | 2         | 0.67%   |
| ASUS ZenBook UX431DA_UM431DA    | 2         | 0.67%   |
| ASUS X553MA                     | 2         | 0.67%   |
| ASUS X541SA                     | 2         | 0.67%   |
| Wortmann AG TERRA_MOBILE_1749   | 1         | 0.33%   |
| TUXEDO InfinityBook Pro 14 Gen6 | 1         | 0.33%   |
| Toshiba Satellite Pro L500      | 1         | 0.33%   |
| Toshiba Satellite Pro C660      | 1         | 0.33%   |
| Toshiba Satellite P755          | 1         | 0.33%   |
| Toshiba Satellite M500          | 1         | 0.33%   |
| Toshiba Satellite L350D         | 1         | 0.33%   |
| Toshiba Satellite C675          | 1         | 0.33%   |
| Toshiba Satellite C665          | 1         | 0.33%   |
| Toshiba Satellite C50D-C        | 1         | 0.33%   |
| Teclast F15S                    | 1         | 0.33%   |
| System76 Serval WS              | 1         | 0.33%   |
| Star Labs LabTop                | 1         | 0.33%   |
| Sony VPCS12X9E                  | 1         | 0.33%   |
| Sony VPCF1290X                  | 1         | 0.33%   |
| Sony VPCEH1S1E                  | 1         | 0.33%   |
| Sony VGN-CR120E                 | 1         | 0.33%   |
| Samsung SR58P                   | 1         | 0.33%   |
| Samsung R530/R730/R540          | 1         | 0.33%   |
| Samsung R505                    | 1         | 0.33%   |
| Samsung 760XBE                  | 1         | 0.33%   |
| Samsung 550P5C/550P7C           | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 40        | 13.33%  |
| Dell Latitude         | 23        | 7.67%   |
| HP Pavilion           | 20        | 6.67%   |
| Acer Aspire           | 16        | 5.33%   |
| HP EliteBook          | 11        | 3.67%   |
| Toshiba Satellite     | 10        | 3.33%   |
| Lenovo IdeaPad        | 10        | 3.33%   |
| Dell Precision        | 10        | 3.33%   |
| Dell Inspiron         | 8         | 2.67%   |
| Dell XPS              | 7         | 2.33%   |
| Dell Vostro           | 6         | 2%      |
| HP ProBook            | 5         | 1.67%   |
| HP 250                | 5         | 1.67%   |
| HP ZBook              | 4         | 1.33%   |
| HP Laptop             | 4         | 1.33%   |
| HP Compaq             | 4         | 1.33%   |
| ASUS VivoBook         | 4         | 1.33%   |
| Packard Bell EasyNote | 3         | 1%      |
| HP Notebook           | 3         | 1%      |
| Unknown               | 3         | 1%      |
| Lenovo ThinkBook      | 2         | 0.67%   |
| Lenovo Legion         | 2         | 0.67%   |
| Lenovo Flex           | 2         | 0.67%   |
| HP 15                 | 2         | 0.67%   |
| Fujitsu LIFEBOOK      | 2         | 0.67%   |
| Dell System           | 2         | 0.67%   |
| Dell Studio           | 2         | 0.67%   |
| ASUS ZenBook          | 2         | 0.67%   |
| ASUS X553MA           | 2         | 0.67%   |
| ASUS X541SA           | 2         | 0.67%   |
| Acer TravelMate       | 2         | 0.67%   |
| Wortmann AG TERRA     | 1         | 0.33%   |
| TUXEDO InfinityBook   | 1         | 0.33%   |
| Teclast F15S          | 1         | 0.33%   |
| System76 Serval       | 1         | 0.33%   |
| Star Labs LabTop      | 1         | 0.33%   |
| Sony VPCS12X9E        | 1         | 0.33%   |
| Sony VPCF1290X        | 1         | 0.33%   |
| Sony VPCEH1S1E        | 1         | 0.33%   |
| Sony VGN-CR120E       | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 37        | 12.33%  |
| 2012    | 31        | 10.33%  |
| 2019    | 30        | 10%     |
| 2013    | 25        | 8.33%   |
| 2020    | 23        | 7.67%   |
| 2018    | 21        | 7%      |
| 2015    | 20        | 6.67%   |
| 2014    | 19        | 6.33%   |
| 2016    | 18        | 6%      |
| 2008    | 18        | 6%      |
| 2010    | 17        | 5.67%   |
| 2017    | 15        | 5%      |
| 2021    | 12        | 4%      |
| 2009    | 7         | 2.33%   |
| 2007    | 4         | 1.33%   |
| 2022    | 1         | 0.33%   |
| 2006    | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 300       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 270       | 89.7%   |
| Enabled  | 31        | 10.3%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 299       | 99.67%  |
| Yes  | 1         | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 87        | 28.62%  |
| 4.01-8.0    | 81        | 26.64%  |
| 8.01-16.0   | 47        | 15.46%  |
| 16.01-24.0  | 42        | 13.82%  |
| 32.01-64.0  | 18        | 5.92%   |
| 64.01-256.0 | 9         | 2.96%   |
| 1.01-2.0    | 9         | 2.96%   |
| 2.01-3.0    | 7         | 2.3%    |
| 24.01-32.0  | 4         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 125       | 39.06%  |
| 2.01-3.0   | 83        | 25.94%  |
| 3.01-4.0   | 41        | 12.81%  |
| 4.01-8.0   | 40        | 12.5%   |
| 0.51-1.0   | 24        | 7.5%    |
| 8.01-16.0  | 6         | 1.88%   |
| 24.01-32.0 | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 223       | 72.4%   |
| 2      | 74        | 24.03%  |
| 3      | 9         | 2.92%   |
| 4      | 1         | 0.32%   |
| 0      | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 165       | 54.82%  |
| Yes       | 136       | 45.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 259       | 86.33%  |
| No        | 41        | 13.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 295       | 97.68%  |
| No        | 7         | 2.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 227       | 74.92%  |
| No        | 76        | 25.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Brazil      | 41        | 13.62%  |
| USA         | 36        | 11.96%  |
| France      | 35        | 11.63%  |
| Germany     | 28        | 9.3%    |
| Spain       | 17        | 5.65%   |
| UK          | 16        | 5.32%   |
| Italy       | 14        | 4.65%   |
| Russia      | 12        | 3.99%   |
| Ukraine     | 9         | 2.99%   |
| Switzerland | 7         | 2.33%   |
| Netherlands | 7         | 2.33%   |
| Indonesia   | 6         | 1.99%   |
| Argentina   | 6         | 1.99%   |
| Poland      | 4         | 1.33%   |
| Canada      | 4         | 1.33%   |
| Turkey      | 3         | 1%      |
| Sweden      | 3         | 1%      |
| Norway      | 3         | 1%      |
| India       | 3         | 1%      |
| Greece      | 3         | 1%      |
| Finland     | 3         | 1%      |
| Vietnam     | 2         | 0.66%   |
| Thailand    | 2         | 0.66%   |
| Portugal    | 2         | 0.66%   |
| Philippines | 2         | 0.66%   |
| Mexico      | 2         | 0.66%   |
| Ireland     | 2         | 0.66%   |
| Denmark     | 2         | 0.66%   |
| Chile       | 2         | 0.66%   |
| Belgium     | 2         | 0.66%   |
| Australia   | 2         | 0.66%   |
| Venezuela   | 1         | 0.33%   |
| Uruguay     | 1         | 0.33%   |
| Taiwan      | 1         | 0.33%   |
| Slovakia    | 1         | 0.33%   |
| Réunion    | 1         | 0.33%   |
| Puerto Rico | 1         | 0.33%   |
| Peru        | 1         | 0.33%   |
| New Zealand | 1         | 0.33%   |
| Morocco     | 1         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 21        | 6.73%   |
| Paris             | 7         | 2.24%   |
| Moscow            | 6         | 1.92%   |
| Kyiv              | 5         | 1.6%    |
| Barcelona         | 5         | 1.6%    |
| Rome              | 3         | 0.96%   |
| Rio de Janeiro    | 3         | 0.96%   |
| Berlin            | 3         | 0.96%   |
| Seville           | 2         | 0.64%   |
| Samara            | 2         | 0.64%   |
| Saint-Cloud       | 2         | 0.64%   |
| Porto Alegre      | 2         | 0.64%   |
| Oslo              | 2         | 0.64%   |
| Marseille         | 2         | 0.64%   |
| Manchester        | 2         | 0.64%   |
| Jakarta           | 2         | 0.64%   |
| Huissen           | 2         | 0.64%   |
| Ho Chi Minh City  | 2         | 0.64%   |
| Gigean            | 2         | 0.64%   |
| Genoa             | 2         | 0.64%   |
| Frankfurt am Main | 2         | 0.64%   |
| Evansville        | 2         | 0.64%   |
| Essen             | 2         | 0.64%   |
| Durham            | 2         | 0.64%   |
| Draper            | 2         | 0.64%   |
| Clichy-sous-Bois  | 2         | 0.64%   |
| Brooklyn          | 2         | 0.64%   |
| Bristol           | 2         | 0.64%   |
| Balikpapan        | 2         | 0.64%   |
| Athens            | 2         | 0.64%   |
| Ankara            | 2         | 0.64%   |
| Amsterdam         | 2         | 0.64%   |
| Albuquerque       | 2         | 0.64%   |
| Akron             | 2         | 0.64%   |
| Zurich            | 1         | 0.32%   |
| Zagreb            | 1         | 0.32%   |
| Yogyakarta        | 1         | 0.32%   |
| Xining            | 1         | 0.32%   |
| Wolfhagen         | 1         | 0.32%   |
| Willimantic       | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 51        | 58     | 13.46%  |
| Seagate               | 51        | 56     | 13.46%  |
| Samsung Electronics   | 47        | 54     | 12.4%   |
| Toshiba               | 37        | 42     | 9.76%   |
| Kingston              | 28        | 33     | 7.39%   |
| Unknown               | 23        | 26     | 6.07%   |
| SanDisk               | 21        | 26     | 5.54%   |
| Hitachi               | 15        | 17     | 3.96%   |
| SK hynix              | 14        | 19     | 3.69%   |
| Intel                 | 11        | 15     | 2.9%    |
| Crucial               | 11        | 16     | 2.9%    |
| A-DATA Technology     | 9         | 11     | 2.37%   |
| KIOXIA                | 5         | 6      | 1.32%   |
| HGST                  | 5         | 5      | 1.32%   |
| China                 | 5         | 6      | 1.32%   |
| Phison                | 4         | 4      | 1.06%   |
| Micron Technology     | 4         | 5      | 1.06%   |
| PNY                   | 3         | 3      | 0.79%   |
| Fujitsu               | 3         | 3      | 0.79%   |
| Transcend             | 2         | 3      | 0.53%   |
| Silicon Motion        | 2         | 2      | 0.53%   |
| SAGE                  | 2         | 2      | 0.53%   |
| Patriot               | 2         | 2      | 0.53%   |
| LITEONIT              | 2         | 3      | 0.53%   |
| LITEON                | 2         | 2      | 0.53%   |
| KingSpec              | 2         | 2      | 0.53%   |
| Intenso               | 2         | 2      | 0.53%   |
| Apacer                | 2         | 3      | 0.53%   |
| XPG                   | 1         | 1      | 0.26%   |
| Vaseky                | 1         | 1      | 0.26%   |
| Smart                 | 1         | 1      | 0.26%   |
| SABRENT               | 1         | 1      | 0.26%   |
| Realtek Semiconductor | 1         | 1      | 0.26%   |
| Ramos Technology      | 1         | 1      | 0.26%   |
| Plextor               | 1         | 1      | 0.26%   |
| OCZ                   | 1         | 1      | 0.26%   |
| Netac                 | 1         | 1      | 0.26%   |
| LaCie                 | 1         | 1      | 0.26%   |
| HS-SSD-E100           | 1         | 1      | 0.26%   |
| FORESEE               | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD         | 8         | 2.06%   |
| Toshiba MQ01ABF050 500GB                | 7         | 1.8%    |
| Kingston SA400S37120G 120GB SSD         | 7         | 1.8%    |
| Seagate ST320LT007-9ZV142 320GB         | 6         | 1.54%   |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 1.29%   |
| WDC WD10JPVX-22JC3T0 1TB                | 4         | 1.03%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 1.03%   |
| Seagate ST500LT012-1DG142 500GB         | 4         | 1.03%   |
| Hitachi HTS545050B9A300 500GB           | 4         | 1.03%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.77%   |
| Unknown MMC Card  16GB                  | 3         | 0.77%   |
| Seagate ST9500420AS 500GB               | 3         | 0.77%   |
| Seagate ST500LT012-9WS142 500GB         | 3         | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.77%   |
| Seagate ST1000LM014-1EJ164 1TB          | 3         | 0.77%   |
| Samsung SSD 860 EVO 500GB               | 3         | 0.77%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.77%   |
| Intel SSDPEKNW512G8 512GB               | 3         | 0.77%   |
| Hitachi HTS547564A9E384 640GB           | 3         | 0.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 2         | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 2         | 0.51%   |
| WDC WD5000BPKT-75PK4T0 500GB            | 2         | 0.51%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 2         | 0.51%   |
| WDC WD10SPZX-08Z10 1TB                  | 2         | 0.51%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB      | 2         | 0.51%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB    | 2         | 0.51%   |
| Unknown DA4064  64GB                    | 2         | 0.51%   |
| Transcend TS512GMTS430S 512GB SSD       | 2         | 0.51%   |
| Toshiba MQ01ACF032 320GB                | 2         | 0.51%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.51%   |
| Toshiba MQ01ABD050 500GB                | 2         | 0.51%   |
| Toshiba MK7559GSXP 752GB                | 2         | 0.51%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.51%   |
| Seagate ST9500325AS 500GB               | 2         | 0.51%   |
| Seagate ST9250410AS 250GB               | 2         | 0.51%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 0.51%   |
| Seagate ST500LM000-SSHD-8GB             | 2         | 0.51%   |
| Seagate ST2000LM015-2E8174 2TB          | 2         | 0.51%   |
| SanDisk SD6SB2M-512G-1006 512GB SSD     | 2         | 0.51%   |
| SanDisk NVMe SSD Drive 512GB            | 2         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 55     | 35.92%  |
| WDC                 | 34        | 39     | 23.94%  |
| Toshiba             | 29        | 34     | 20.42%  |
| Hitachi             | 15        | 17     | 10.56%  |
| HGST                | 5         | 5      | 3.52%   |
| Fujitsu             | 3         | 3      | 2.11%   |
| Samsung Electronics | 2         | 2      | 1.41%   |
| SAGE                | 2         | 2      | 1.41%   |
| LaCie               | 1         | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 37     | 23.7%   |
| Kingston            | 26        | 31     | 19.26%  |
| SanDisk             | 15        | 19     | 11.11%  |
| Crucial             | 9         | 14     | 6.67%   |
| WDC                 | 6         | 6      | 4.44%   |
| A-DATA Technology   | 6         | 8      | 4.44%   |
| China               | 5         | 6      | 3.7%    |
| Intel               | 4         | 7      | 2.96%   |
| Toshiba             | 3         | 3      | 2.22%   |
| PNY                 | 3         | 3      | 2.22%   |
| Transcend           | 2         | 3      | 1.48%   |
| SK hynix            | 2         | 4      | 1.48%   |
| Micron Technology   | 2         | 3      | 1.48%   |
| LITEONIT            | 2         | 3      | 1.48%   |
| KingSpec            | 2         | 2      | 1.48%   |
| Intenso             | 2         | 2      | 1.48%   |
| Apacer              | 2         | 3      | 1.48%   |
| Vaseky              | 1         | 1      | 0.74%   |
| Smart               | 1         | 1      | 0.74%   |
| Seagate             | 1         | 1      | 0.74%   |
| Ramos Technology    | 1         | 1      | 0.74%   |
| Plextor             | 1         | 1      | 0.74%   |
| Patriot             | 1         | 1      | 0.74%   |
| OCZ                 | 1         | 1      | 0.74%   |
| Netac               | 1         | 1      | 0.74%   |
| LITEON              | 1         | 1      | 0.74%   |
| HS-SSD-E100         | 1         | 1      | 0.74%   |
| FORESEE             | 1         | 1      | 0.74%   |
| Dogfish             | 1         | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 136       | 158    | 38.31%  |
| SSD     | 123       | 166    | 34.65%  |
| NVMe    | 74        | 87     | 20.85%  |
| MMC     | 21        | 28     | 5.92%   |
| Unknown | 1         | 1      | 0.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 234       | 315    | 69.03%  |
| NVMe | 73        | 86     | 21.53%  |
| MMC  | 21        | 28     | 6.19%   |
| SAS  | 11        | 11     | 3.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 180       | 229    | 68.44%  |
| 0.51-1.0   | 71        | 79     | 27%     |
| 1.01-2.0   | 10        | 14     | 3.8%    |
| 3.01-4.0   | 2         | 2      | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 94        | 30.42%  |
| 101-250        | 88        | 28.48%  |
| 501-1000       | 48        | 15.53%  |
| 1-20           | 19        | 6.15%   |
| 51-100         | 19        | 6.15%   |
| 1001-2000      | 17        | 5.5%    |
| 21-50          | 11        | 3.56%   |
| 2001-3000      | 7         | 2.27%   |
| More than 3000 | 6         | 1.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 109       | 34.28%  |
| 51-100         | 55        | 17.3%   |
| 101-250        | 52        | 16.35%  |
| 21-50          | 50        | 15.72%  |
| 251-500        | 30        | 9.43%   |
| 501-1000       | 15        | 4.72%   |
| 1001-2000      | 5         | 1.57%   |
| More than 3000 | 1         | 0.31%   |
| 2001-3000      | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT007-9ZV142 320GB   | 4         | 4      | 10.53%  |
| WDC WD3200BEVT-60ZCT1 320GB       | 2         | 2      | 5.26%   |
| Toshiba MK7559GSXP 752GB          | 2         | 2      | 5.26%   |
| WDC WD7500BPVT-75HXZT1 752GB      | 1         | 1      | 2.63%   |
| WDC WD7500BPKT-75PK4T0 752GB      | 1         | 1      | 2.63%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 2.63%   |
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 2      | 2.63%   |
| WDC WD3200BEKT-60V5T1 320GB       | 1         | 1      | 2.63%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 2.63%   |
| Vaseky V820/1TB 1024GB            | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 2.63%   |
| Toshiba MK5065GSX 500GB           | 1         | 1      | 2.63%   |
| Toshiba MK2565GSXN 250GB          | 1         | 1      | 2.63%   |
| Toshiba MK2555GSX 250GB           | 1         | 1      | 2.63%   |
| Seagate ST9500420AS 500GB         | 1         | 1      | 2.63%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 2.63%   |
| Seagate ST9250410AS 250GB         | 1         | 1      | 2.63%   |
| Seagate ST9160821AS 160GB         | 1         | 1      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 2.63%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 2.63%   |
| Seagate ST320LT012-9WS14C 320GB   | 1         | 1      | 2.63%   |
| SanDisk SD7SN3Q256G1002 256GB SSD | 1         | 1      | 2.63%   |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 2.63%   |
| OCZ VERTEX450 128GB SSD           | 1         | 1      | 2.63%   |
| Intel SSDSC2KF256H6L 256GB        | 1         | 1      | 2.63%   |
| Hitachi HTS722016K9A300 160GB     | 1         | 1      | 2.63%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 2.63%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 2.63%   |
| Hitachi HTS541616J9SA00 160GB     | 1         | 1      | 2.63%   |
| Fujitsu MHZ2320BH G1 320GB        | 1         | 1      | 2.63%   |
| China SSD 120GB                   | 1         | 1      | 2.63%   |
| A-DATA Technology SU650 120GB SSD | 1         | 3      | 2.63%   |
| A-DATA Technology SP900 64GB SSD  | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 28.95%  |
| WDC                 | 8         | 9      | 21.05%  |
| Toshiba             | 6         | 6      | 15.79%  |
| Hitachi             | 4         | 4      | 10.53%  |
| A-DATA Technology   | 2         | 4      | 5.26%   |
| Vaseky              | 1         | 1      | 2.63%   |
| SanDisk             | 1         | 1      | 2.63%   |
| Samsung Electronics | 1         | 1      | 2.63%   |
| OCZ                 | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| Fujitsu             | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 35.48%  |
| WDC                 | 8         | 9      | 25.81%  |
| Toshiba             | 6         | 6      | 19.35%  |
| Hitachi             | 4         | 4      | 12.9%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 32     | 81.58%  |
| SSD  | 7         | 9      | 18.42%  |

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
| Works    | 169       | 224    | 52.32%  |
| Detected | 117       | 175    | 36.22%  |
| Malfunc  | 37        | 41     | 11.46%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 227       | 68.17%  |
| AMD                              | 31        | 9.31%   |
| SanDisk                          | 16        | 4.8%    |
| Samsung Electronics              | 14        | 4.2%    |
| SK hynix                         | 11        | 3.3%    |
| Toshiba America Info Systems     | 7         | 2.1%    |
| Phison Electronics               | 4         | 1.2%    |
| KIOXIA                           | 4         | 1.2%    |
| ADATA Technology                 | 4         | 1.2%    |
| Silicon Motion                   | 3         | 0.9%    |
| Silicon Integrated Systems [SiS] | 2         | 0.6%    |
| Micron/Crucial Technology        | 2         | 0.6%    |
| Micron Technology                | 2         | 0.6%    |
| Kingston Technology Company      | 2         | 0.6%    |
| Solid State Storage Technology   | 1         | 0.3%    |
| Realtek Semiconductor            | 1         | 0.3%    |
| Nvidia                           | 1         | 0.3%    |
| Lite-On Technology               | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 35        | 9.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 30        | 8.36%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 6.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 19        | 5.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 5.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 15        | 4.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 3.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 3.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 2.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 2.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 2.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 2.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 2.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 1.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 1.39%   |
| Intel SSD 660P Series                                                            | 5         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.39%   |
| SK hynix BC511 NVMe SSD                                                          | 4         | 1.11%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1.11%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.11%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.84%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.84%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 0.84%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.84%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.84%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 3         | 0.84%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 3         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.84%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 0.56%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 226       | 66.47%  |
| NVMe | 72        | 21.18%  |
| RAID | 22        | 6.47%   |
| IDE  | 20        | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 262       | 87.33%  |
| AMD    | 37        | 12.33%  |
| ARM    | 1         | 0.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 2%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 2%      |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.67%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.67%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 5         | 1.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.33%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 1.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.33%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.33%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.33%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.33%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 3         | 1%      |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 1%      |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1%      |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1%      |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 1%      |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 1%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1%      |
| Intel Core i3-2330M CPU @ 2.20GHz             | 3         | 1%      |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1%      |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.67%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.67%   |
| Intel Genuine CPU T1600 @ 1.66GHz             | 2         | 0.67%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.67%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 2         | 0.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.67%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 2         | 0.67%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 2         | 0.67%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.67%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 0.67%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 2         | 0.67%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 84        | 28%     |
| Intel Core i7                  | 76        | 25.33%  |
| Intel Core i3                  | 26        | 8.67%   |
| Intel Core 2 Duo               | 15        | 5%      |
| Intel Celeron                  | 15        | 5%      |
| Intel Pentium                  | 13        | 4.33%   |
| Other                          | 12        | 4%      |
| AMD Ryzen 7                    | 6         | 2%      |
| AMD Ryzen 5                    | 6         | 2%      |
| Intel Atom                     | 5         | 1.67%   |
| Intel Pentium Dual-Core        | 4         | 1.33%   |
| AMD A6                         | 4         | 1.33%   |
| Intel Core m3                  | 3         | 1%      |
| AMD A4                         | 3         | 1%      |
| Intel Xeon                     | 2         | 0.67%   |
| Intel Genuine                  | 2         | 0.67%   |
| Intel Core M                   | 2         | 0.67%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.67%   |
| AMD Ryzen 9                    | 2         | 0.67%   |
| AMD Ryzen 3                    | 2         | 0.67%   |
| AMD A8                         | 2         | 0.67%   |
| Intel Pentium Silver           | 1         | 0.33%   |
| Intel Pentium Dual             | 1         | 0.33%   |
| Intel Core i9                  | 1         | 0.33%   |
| Intel Core 2 Extreme           | 1         | 0.33%   |
| Intel Celeron Dual-Core        | 1         | 0.33%   |
| AMD Turion 64 Mobile           | 1         | 0.33%   |
| AMD Ryzen 7 PRO                | 1         | 0.33%   |
| AMD Ryzen 5 PRO                | 1         | 0.33%   |
| AMD Phenom II                  | 1         | 0.33%   |
| AMD E2                         | 1         | 0.33%   |
| AMD E1                         | 1         | 0.33%   |
| AMD E                          | 1         | 0.33%   |
| AMD Athlon X2                  | 1         | 0.33%   |
| AMD Athlon                     | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 172       | 57.14%  |
| 4      | 102       | 33.89%  |
| 6      | 12        | 3.99%   |
| 8      | 10        | 3.32%   |
| 1      | 3         | 1%      |
| 14     | 1         | 0.33%   |
| 3      | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 299       | 99.67%  |
| 2      | 1         | 0.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 217       | 72.33%  |
| 1      | 83        | 27.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 300       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 12.17%  |
| 0x206a7    | 35        | 11.51%  |
| 0x306a9    | 31        | 10.2%   |
| 0x306d4    | 13        | 4.28%   |
| 0x1067a    | 12        | 3.95%   |
| 0x806e9    | 11        | 3.62%   |
| 0x806ec    | 10        | 3.29%   |
| 0x40651    | 10        | 3.29%   |
| 0x306c3    | 9         | 2.96%   |
| 0x6fd      | 8         | 2.63%   |
| 0x406e3    | 8         | 2.63%   |
| 0x806ea    | 7         | 2.3%    |
| 0x706e5    | 7         | 2.3%    |
| 0x20655    | 7         | 2.3%    |
| 0x906ea    | 6         | 1.97%   |
| 0x20652    | 6         | 1.97%   |
| 0x08108102 | 6         | 1.97%   |
| 0x906e9    | 5         | 1.64%   |
| 0x806c1    | 5         | 1.64%   |
| 0x406c4    | 5         | 1.64%   |
| 0x30678    | 5         | 1.64%   |
| 0x706a1    | 4         | 1.32%   |
| 0x506e3    | 4         | 1.32%   |
| 0x06006705 | 4         | 1.32%   |
| 0x806d1    | 3         | 0.99%   |
| 0x406c3    | 3         | 0.99%   |
| 0x30673    | 3         | 0.99%   |
| 0x08600106 | 3         | 0.99%   |
| 0x07030105 | 3         | 0.99%   |
| 0x02000032 | 3         | 0.99%   |
| 0xa0652    | 2         | 0.66%   |
| 0x906ed    | 2         | 0.66%   |
| 0x806eb    | 2         | 0.66%   |
| 0x6fa      | 2         | 0.66%   |
| 0x506c9    | 2         | 0.66%   |
| 0x106e5    | 2         | 0.66%   |
| 0x10676    | 2         | 0.66%   |
| 0x08108109 | 2         | 0.66%   |
| 0x08101016 | 2         | 0.66%   |
| 0xa0660    | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 51        | 17%     |
| SandyBridge      | 39        | 13%     |
| IvyBridge        | 34        | 11.33%  |
| Haswell          | 24        | 8%      |
| Silvermont       | 16        | 5.33%   |
| Broadwell        | 16        | 5.33%   |
| Skylake          | 15        | 5%      |
| Penryn           | 14        | 4.67%   |
| Westmere         | 13        | 4.33%   |
| Icelake          | 11        | 3.67%   |
| Core             | 10        | 3.33%   |
| Zen+             | 8         | 2.67%   |
| TigerLake        | 5         | 1.67%   |
| Puma             | 5         | 1.67%   |
| Excavator        | 5         | 1.67%   |
| Zen 2            | 4         | 1.33%   |
| Goldmont plus    | 4         | 1.33%   |
| Zen 3            | 3         | 1%      |
| Zen              | 3         | 1%      |
| K8 & K10 hybrid  | 3         | 1%      |
| Goldmont         | 3         | 1%      |
| CometLake        | 3         | 1%      |
| Nehalem          | 2         | 0.67%   |
| Bobcat           | 2         | 0.67%   |
| Unknown          | 2         | 0.67%   |
| Piledriver       | 1         | 0.33%   |
| K8 Hammer        | 1         | 0.33%   |
| K10              | 1         | 0.33%   |
| Bonnell          | 1         | 0.33%   |
| Alderlake Hybrid | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 240       | 64%     |
| Nvidia                           | 74        | 19.73%  |
| AMD                              | 60        | 16%     |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 8.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 8.59%   |
| Intel HD Graphics 5500                                                                   | 14        | 3.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 3.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 2.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.34%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.3%    |
| Intel HD Graphics 620                                                                    | 5         | 1.3%    |
| Intel HD Graphics 530                                                                    | 5         | 1.3%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.04%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.04%   |
| Intel HD Graphics 630                                                                    | 4         | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.04%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 1.04%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.78%   |
| Intel HD Graphics 500                                                                    | 3         | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.78%   |
| AMD Renoir                                                                               | 3         | 0.78%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.78%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.52%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 2         | 0.52%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 167       | 55.67%  |
| Intel + Nvidia | 57        | 19%     |
| 1 x AMD        | 37        | 12.33%  |
| Intel + AMD    | 16        | 5.33%   |
| 1 x Nvidia     | 15        | 5%      |
| 2 x AMD        | 4         | 1.33%   |
| AMD + Nvidia   | 2         | 0.67%   |
| Other          | 1         | 0.33%   |
| 1 x SiS        | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 249       | 82.45%  |
| Proprietary | 42        | 13.91%  |
| Unknown     | 11        | 3.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 211       | 69.87%  |
| 0.01-0.5   | 26        | 8.61%   |
| 1.01-2.0   | 25        | 8.28%   |
| 0.51-1.0   | 18        | 5.96%   |
| 3.01-4.0   | 14        | 4.64%   |
| 5.01-6.0   | 4         | 1.32%   |
| 2.01-3.0   | 3         | 0.99%   |
| 7.01-8.0   | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 66        | 19.82%  |
| LG Display              | 59        | 17.72%  |
| Samsung Electronics     | 45        | 13.51%  |
| Chimei Innolux          | 42        | 12.61%  |
| BOE                     | 30        | 9.01%   |
| Dell                    | 13        | 3.9%    |
| Chi Mei Optoelectronics | 13        | 3.9%    |
| PANDA                   | 8         | 2.4%    |
| Sharp                   | 6         | 1.8%    |
| Hewlett-Packard         | 5         | 1.5%    |
| Philips                 | 4         | 1.2%    |
| LG Philips              | 4         | 1.2%    |
| Lenovo                  | 4         | 1.2%    |
| Goldstar                | 4         | 1.2%    |
| InnoLux Display         | 3         | 0.9%    |
| Apple                   | 3         | 0.9%    |
| Sony                    | 2         | 0.6%    |
| Iiyama                  | 2         | 0.6%    |
| CSO                     | 2         | 0.6%    |
| AOC                     | 2         | 0.6%    |
| Ancor Communications    | 2         | 0.6%    |
| Acer                    | 2         | 0.6%    |
| ___                     | 1         | 0.3%    |
| Vizio                   | 1         | 0.3%    |
| Unknown                 | 1         | 0.3%    |
| Seiko/Epson             | 1         | 0.3%    |
| Optoma                  | 1         | 0.3%    |
| NEC Computers           | 1         | 0.3%    |
| MS_ Nvidia              | 1         | 0.3%    |
| Medion                  | 1         | 0.3%    |
| LGD                     | 1         | 0.3%    |
| InfoVision              | 1         | 0.3%    |
| HannStar                | 1         | 0.3%    |
| CPT                     | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 6         | 1.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 6         | 1.77%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 1.18%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 0.88%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch              | 3         | 0.88%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.88%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.88%   |
| AU Optronics LCD Monitor AUO193C 1366x768 310x170mm 13.9-inch            | 3         | 0.88%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 3         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 2         | 0.59%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.59%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 0.59%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.59%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.59%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.59%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 2         | 0.59%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.59%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 2         | 0.59%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch          | 2         | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 2         | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.59%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.59%   |
| ___ LCDTV16 ___9000 1360x768                                             | 1         | 0.29%   |
| Vizio D40f-G9 VIZ1027 1920x1080 930x520mm 41.9-inch                      | 1         | 0.29%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 0.29%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 116       | 36.94%  |
| 1920x1080 (FHD)    | 110       | 35.03%  |
| 1600x900 (HD+)     | 29        | 9.24%   |
| 1280x800 (WXGA)    | 14        | 4.46%   |
| 2560x1440 (QHD)    | 8         | 2.55%   |
| 1440x900 (WXGA+)   | 7         | 2.23%   |
| 1680x1050 (WSXGA+) | 6         | 1.91%   |
| 3840x2160 (4K)     | 5         | 1.59%   |
| 1920x1200 (WUXGA)  | 5         | 1.59%   |
| 3440x1440          | 2         | 0.64%   |
| 3200x1800 (QHD+)   | 2         | 0.64%   |
| 2560x1600          | 2         | 0.64%   |
| 1360x768           | 2         | 0.64%   |
| 2880x1800          | 1         | 0.32%   |
| 2160x1440          | 1         | 0.32%   |
| 1680x945           | 1         | 0.32%   |
| 1600x1200          | 1         | 0.32%   |
| 1400x1050          | 1         | 0.32%   |
| 1024x600           | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 135       | 40.42%  |
| 14      | 43        | 12.87%  |
| 13      | 43        | 12.87%  |
| 17      | 30        | 8.98%   |
| 12      | 13        | 3.89%   |
| 21      | 9         | 2.69%   |
| 24      | 8         | 2.4%    |
| 23      | 8         | 2.4%    |
| 11      | 8         | 2.4%    |
| 27      | 6         | 1.8%    |
| Unknown | 6         | 1.8%    |
| 18      | 5         | 1.5%    |
| 22      | 4         | 1.2%    |
| 34      | 2         | 0.6%    |
| 20      | 2         | 0.6%    |
| 19      | 2         | 0.6%    |
| 10      | 2         | 0.6%    |
| 72      | 1         | 0.3%    |
| 65      | 1         | 0.3%    |
| 49      | 1         | 0.3%    |
| 46      | 1         | 0.3%    |
| 31      | 1         | 0.3%    |
| 29      | 1         | 0.3%    |
| 16      | 1         | 0.3%    |
| 8       | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 196       | 58.86%  |
| 201-300     | 43        | 12.91%  |
| 351-400     | 36        | 10.81%  |
| 401-500     | 22        | 6.61%   |
| 501-600     | 21        | 6.31%   |
| Unknown     | 6         | 1.8%    |
| 1001-1500   | 3         | 0.9%    |
| 701-800     | 2         | 0.6%    |
| 601-700     | 2         | 0.6%    |
| 1501-2000   | 1         | 0.3%    |
| 101-200     | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 262       | 86.47%  |
| 16/10   | 30        | 9.9%    |
| 3/2     | 4         | 1.32%   |
| Unknown | 3         | 0.99%   |
| 21/9    | 2         | 0.66%   |
| 4/3     | 1         | 0.33%   |
| 0.62    | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 133       | 39.82%  |
| 81-90          | 67        | 20.06%  |
| 201-250        | 24        | 7.19%   |
| 121-130        | 23        | 6.89%   |
| 71-80          | 19        | 5.69%   |
| 61-70          | 13        | 3.89%   |
| 51-60          | 8         | 2.4%    |
| 131-140        | 7         | 2.1%    |
| 301-350        | 6         | 1.8%    |
| 151-200        | 6         | 1.8%    |
| Unknown        | 6         | 1.8%    |
| 351-500        | 4         | 1.2%    |
| 251-300        | 4         | 1.2%    |
| 141-150        | 4         | 1.2%    |
| More than 1000 | 3         | 0.9%    |
| 41-50          | 2         | 0.6%    |
| 111-120        | 2         | 0.6%    |
| 1-40           | 1         | 0.3%    |
| 501-1000       | 1         | 0.3%    |
| 91-100         | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 125       | 37.88%  |
| 121-160       | 110       | 33.33%  |
| 51-100        | 55        | 16.67%  |
| 161-240       | 22        | 6.67%   |
| More than 240 | 8         | 2.42%   |
| Unknown       | 6         | 1.82%   |
| 1-50          | 4         | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 248       | 81.85%  |
| 2     | 43        | 14.19%  |
| 3     | 6         | 1.98%   |
| 0     | 6         | 1.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 157       | 32.91%  |
| Realtek Semiconductor             | 151       | 31.66%  |
| Qualcomm Atheros                  | 80        | 16.77%  |
| Broadcom                          | 35        | 7.34%   |
| Broadcom Limited                  | 12        | 2.52%   |
| Ralink                            | 7         | 1.47%   |
| Marvell Technology Group          | 6         | 1.26%   |
| Ralink Technology                 | 5         | 1.05%   |
| Sierra Wireless                   | 4         | 0.84%   |
| Xiaomi                            | 2         | 0.42%   |
| TP-Link                           | 2         | 0.42%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.42%   |
| Ericsson Business Mobile Networks | 2         | 0.42%   |
| Samsung Electronics               | 1         | 0.21%   |
| Realtek                           | 1         | 0.21%   |
| Qualcomm Atheros Communications   | 1         | 0.21%   |
| Qualcomm                          | 1         | 0.21%   |
| NetGear                           | 1         | 0.21%   |
| Lenovo                            | 1         | 0.21%   |
| Hewlett-Packard                   | 1         | 0.21%   |
| Fibocom                           | 1         | 0.21%   |
| Dell                              | 1         | 0.21%   |
| Attansic Technology               | 1         | 0.21%   |
| ASUSTek Computer                  | 1         | 0.21%   |
| ASIX Electronics                  | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 90        | 15.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 39        | 6.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 23        | 3.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 2.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 2.57%   |
| Intel Wireless 7265                                                     | 14        | 2.4%    |
| Intel Wireless 7260                                                     | 14        | 2.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 2.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.54%   |
| Intel Wireless 8265 / 8275                                              | 9         | 1.54%   |
| Intel Wireless 3165                                                     | 9         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.37%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.37%   |
| Intel Ethernet Connection I217-LM                                       | 8         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.03%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.03%   |
| Intel Wireless 8260                                                     | 5         | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.86%   |
| Intel Ethernet Connection I218-LM                                       | 5         | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.86%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.86%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.68%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 0.68%   |
| Intel Ethernet Connection I219-V                                        | 4         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.68%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 148       | 46.98%  |
| Qualcomm Atheros                | 69        | 21.9%   |
| Realtek Semiconductor           | 37        | 11.75%  |
| Broadcom                        | 24        | 7.62%   |
| Broadcom Limited                | 11        | 3.49%   |
| Ralink                          | 7         | 2.22%   |
| Ralink Technology               | 5         | 1.59%   |
| Sierra Wireless                 | 4         | 1.27%   |
| TP-Link                         | 2         | 0.63%   |
| Realtek                         | 1         | 0.32%   |
| Qualcomm Atheros Communications | 1         | 0.32%   |
| Qualcomm                        | 1         | 0.32%   |
| NetGear                         | 1         | 0.32%   |
| Hewlett-Packard                 | 1         | 0.32%   |
| Fibocom                         | 1         | 0.32%   |
| Dell                            | 1         | 0.32%   |
| ASUSTek Computer                | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 5.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 4.76%   |
| Intel Wireless 7265                                                     | 14        | 4.44%   |
| Intel Wireless 7260                                                     | 14        | 4.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 4.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 4.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.86%   |
| Intel Wireless 8265 / 8275                                              | 9         | 2.86%   |
| Intel Wireless 3165                                                     | 9         | 2.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 2.54%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 2.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 2.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.9%    |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.9%    |
| Intel Wireless 8260                                                     | 5         | 1.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.59%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.27%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.27%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.95%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.95%   |
| Intel Wireless 3160                                                     | 3         | 0.95%   |
| Intel WiFi Link 5100                                                    | 3         | 0.95%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.95%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 3         | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.95%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.63%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.63%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 142       | 53.99%  |
| Intel                            | 73        | 27.76%  |
| Qualcomm Atheros                 | 18        | 6.84%   |
| Broadcom                         | 14        | 5.32%   |
| Marvell Technology Group         | 6         | 2.28%   |
| Xiaomi                           | 2         | 0.76%   |
| Silicon Integrated Systems [SiS] | 2         | 0.76%   |
| Broadcom Limited                 | 2         | 0.76%   |
| Samsung Electronics              | 1         | 0.38%   |
| Lenovo                           | 1         | 0.38%   |
| Attansic Technology              | 1         | 0.38%   |
| ASIX Electronics                 | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 90        | 33.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 14.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 8.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 4.12%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 3%      |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.87%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.87%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.5%    |
| Intel Ethernet Connection I219-V                                  | 4         | 1.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.12%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.12%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.12%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.75%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.75%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.75%   |
| Intel Ethernet Connection (14) I219-LM                            | 2         | 0.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.37%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 295       | 53.15%  |
| Ethernet | 258       | 46.49%  |
| Modem    | 2         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 242       | 76.58%  |
| Ethernet | 74        | 23.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 241       | 79.8%   |
| 1     | 57        | 18.87%  |
| 0     | 3         | 0.99%   |
| 3     | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 253       | 83.77%  |
| Yes  | 49        | 16.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 110       | 47.83%  |
| Qualcomm Atheros Communications | 28        | 12.17%  |
| Realtek Semiconductor           | 22        | 9.57%   |
| Broadcom                        | 20        | 8.7%    |
| Dell                            | 13        | 5.65%   |
| Lite-On Technology              | 9         | 3.91%   |
| IMC Networks                    | 9         | 3.91%   |
| Foxconn / Hon Hai               | 4         | 1.74%   |
| Cambridge Silicon Radio         | 4         | 1.74%   |
| Ralink                          | 3         | 1.3%    |
| ASUSTek Computer                | 3         | 1.3%    |
| Ralink Technology               | 2         | 0.87%   |
| Toshiba                         | 1         | 0.43%   |
| Foxconn International           | 1         | 0.43%   |
| Apple                           | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 57        | 24.78%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 7.83%   |
| Intel AX201 Bluetooth                               | 14        | 6.09%   |
| Realtek Bluetooth Radio                             | 11        | 4.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 3.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 3.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 3.04%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 3.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 3.04%   |
| Intel AX200 Bluetooth                               | 7         | 3.04%   |
| IMC Networks Bluetooth Device                       | 7         | 3.04%   |
| Dell DW375 Bluetooth Module                         | 7         | 3.04%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 1.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.74%   |
| Broadcom HP Portable SoftSailing                    | 4         | 1.74%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 1.74%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.3%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.3%    |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.3%    |
| Realtek RTL8723B Bluetooth                          | 2         | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.87%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.87%   |
| Lite-On Bluetooth Device                            | 2         | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.87%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 2         | 0.87%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.87%   |
| Toshiba Bluetooth Radio                             | 1         | 0.43%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.43%   |
| Ralink CSR BS8510                                   | 1         | 0.43%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.43%   |
| IMC Networks BCM20702A0                             | 1         | 0.43%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.43%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.43%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 254       | 68.65%  |
| Nvidia                                         | 46        | 12.43%  |
| AMD                                            | 46        | 12.43%  |
| Realtek Semiconductor                          | 4         | 1.08%   |
| Lenovo                                         | 3         | 0.81%   |
| Silicon Integrated Systems [SiS]               | 2         | 0.54%   |
| Sony                                           | 1         | 0.27%   |
| Siemens Information and Communication Products | 1         | 0.27%   |
| Plantronics                                    | 1         | 0.27%   |
| No brand                                       | 1         | 0.27%   |
| Meizu                                          | 1         | 0.27%   |
| Logitech                                       | 1         | 0.27%   |
| Kingston Technology                            | 1         | 0.27%   |
| Hewlett-Packard                                | 1         | 0.27%   |
| GN Netcom                                      | 1         | 0.27%   |
| Generalplus Technology                         | 1         | 0.27%   |
| FiiO Electronics Technology                    | 1         | 0.27%   |
| Elite Silicon                                  | 1         | 0.27%   |
| Corsair                                        | 1         | 0.27%   |
| Conexant Systems                               | 1         | 0.27%   |
| C-Media Electronics                            | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 8.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 34        | 7.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 6.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 18        | 4.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 3.61%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 3.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 3.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.71%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 2.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.58%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.58%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.58%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.35%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.13%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.13%   |
| Realtek Semiconductor USB Audio                                                                   | 4         | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.9%    |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.68%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 68        | 25.09%  |
| SK hynix                                         | 49        | 18.08%  |
| Micron Technology                                | 32        | 11.81%  |
| Kingston                                         | 24        | 8.86%   |
| Unknown                                          | 22        | 8.12%   |
| Crucial                                          | 15        | 5.54%   |
| Ramaxel Technology                               | 10        | 3.69%   |
| Nanya Technology                                 | 9         | 3.32%   |
| Elpida                                           | 8         | 2.95%   |
| A-DATA Technology                                | 7         | 2.58%   |
| Smart                                            | 6         | 2.21%   |
| Unknown (ABCD)                                   | 3         | 1.11%   |
| Teikon                                           | 2         | 0.74%   |
| Patriot                                          | 2         | 0.74%   |
| Netlist                                          | 2         | 0.74%   |
| Goodram                                          | 2         | 0.74%   |
| Corsair                                          | 2         | 0.74%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.37%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.37%   |
| Toshiba                                          | 1         | 0.37%   |
| Team                                             | 1         | 0.37%   |
| Qimonda                                          | 1         | 0.37%   |
| G.Skill                                          | 1         | 0.37%   |
| ASint Technology                                 | 1         | 0.37%   |
| Apacer                                           | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 2.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 2.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.74%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 5         | 1.74%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 1.39%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.39%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 1.05%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.05%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.05%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 1.05%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.05%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 1.05%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 1.05%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.7%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.7%    |
| Unknown RAM Module 2048MB SODIMM DRAM                            | 2         | 0.7%    |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s            | 2         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.7%    |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.7%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.7%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.7%    |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s           | 2         | 0.7%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.7%    |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 4199MT/s                 | 2         | 0.7%    |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 2         | 0.7%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.7%    |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 2         | 0.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.7%    |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 110       | 48.25%  |
| DDR4    | 72        | 31.58%  |
| DDR2    | 14        | 6.14%   |
| LPDDR3  | 11        | 4.82%   |
| SDRAM   | 8         | 3.51%   |
| LPDDR4  | 8         | 3.51%   |
| DRAM    | 2         | 0.88%   |
| DDR5    | 1         | 0.44%   |
| DDR     | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 206       | 91.15%  |
| Row Of Chips | 16        | 7.08%   |
| Chip         | 3         | 1.33%   |
| DIMM         | 1         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 96        | 38.4%   |
| 8192  | 71        | 28.4%   |
| 2048  | 43        | 17.2%   |
| 16384 | 24        | 9.6%    |
| 32768 | 8         | 3.2%    |
| 1024  | 7         | 2.8%    |
| 1536  | 1         | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 76        | 30.52%  |
| 2667    | 40        | 16.06%  |
| 1334    | 24        | 9.64%   |
| 3200    | 23        | 9.24%   |
| 2133    | 15        | 6.02%   |
| 2400    | 13        | 5.22%   |
| 1333    | 12        | 4.82%   |
| Unknown | 8         | 3.21%   |
| 4199    | 6         | 2.41%   |
| 3266    | 6         | 2.41%   |
| 667     | 6         | 2.41%   |
| 1066    | 5         | 2.01%   |
| 800     | 4         | 1.61%   |
| 1067    | 3         | 1.2%    |
| 2048    | 2         | 0.8%    |
| 975     | 2         | 0.8%    |
| 4800    | 1         | 0.4%    |
| 4267    | 1         | 0.4%    |
| 1867    | 1         | 0.4%    |
| 533     | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| QinHeng CH340S                   | 1         | 33.33%  |
| Canon PIXMA MG2500 Series        | 1         | 33.33%  |
| Brother DCP-7055 scanner/printer | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 50%     |
| Seiko Epson ES-D400 [GT-S80]                     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 85        | 31.37%  |
| Microdia                               | 29        | 10.7%   |
| Sunplus Innovation Technology          | 18        | 6.64%   |
| Bison Electronics                      | 16        | 5.9%    |
| IMC Networks                           | 14        | 5.17%   |
| Realtek Semiconductor                  | 13        | 4.8%    |
| Cheng Uei Precision Industry (Foxlink) | 11        | 4.06%   |
| Acer                                   | 11        | 4.06%   |
| Quanta                                 | 10        | 3.69%   |
| Ricoh                                  | 9         | 3.32%   |
| Suyin                                  | 7         | 2.58%   |
| Syntek                                 | 6         | 2.21%   |
| Silicon Motion                         | 6         | 2.21%   |
| Lite-On Technology                     | 5         | 1.85%   |
| Logitech                               | 4         | 1.48%   |
| Apple                                  | 4         | 1.48%   |
| Luxvisions Innotech Limited            | 3         | 1.11%   |
| Samsung Electronics                    | 2         | 0.74%   |
| LG Electronics                         | 2         | 0.74%   |
| Importek                               | 2         | 0.74%   |
| Alcor Micro                            | 2         | 0.74%   |
| Z-Star Microelectronics                | 1         | 0.37%   |
| Y Media                                | 1         | 0.37%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.37%   |
| Ruision                                | 1         | 0.37%   |
| Primax Electronics                     | 1         | 0.37%   |
| Microsoft                              | 1         | 0.37%   |
| Lenovo                                 | 1         | 0.37%   |
| Google                                 | 1         | 0.37%   |
| Generalplus Technology                 | 1         | 0.37%   |
| DigiTech                               | 1         | 0.37%   |
| Cubeternet                             | 1         | 0.37%   |
| Aveo Technology                        | 1         | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 19        | 6.99%   |
| Microdia Integrated_Webcam_HD                    | 9         | 3.31%   |
| Sunplus Integrated_Webcam_HD                     | 8         | 2.94%   |
| Chicony USB2.0 VGA UVC WebCam                    | 7         | 2.57%   |
| Chicony HD WebCam                                | 6         | 2.21%   |
| Bison Integrated Camera                          | 6         | 2.21%   |
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 1.84%   |
| Ricoh HD Webcam                                  | 4         | 1.47%   |
| Microdia Laptop_Integrated_Webcam_HD             | 4         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 4         | 1.47%   |
| Suyin HP TrueVision HD Integrated Webcam         | 3         | 1.1%    |
| Sunplus Laptop_Integrated_Webcam_FHD             | 3         | 1.1%    |
| Realtek Integrated_Webcam_HD                     | 3         | 1.1%    |
| Quanta HD User Facing                            | 3         | 1.1%    |
| Microdia Integrated Webcam                       | 3         | 1.1%    |
| Lite-On HP HD Camera                             | 3         | 1.1%    |
| Chicony Integrated IR Camera                     | 3         | 1.1%    |
| Chicony Integrated Camera (1280x720@30)          | 3         | 1.1%    |
| Chicony HP Wide Vision HD Camera                 | 3         | 1.1%    |
| Chicony HP HD Webcam                             | 3         | 1.1%    |
| Chicony CNF9055 Toshiba Webcam                   | 3         | 1.1%    |
| Bison BisonCam, NB Pro                           | 3         | 1.1%    |
| Acer BisonCam, NB Pro                            | 3         | 1.1%    |
| Syntek Lenovo EasyCamera                         | 2         | 0.74%   |
| Syntek EasyCamera                                | 2         | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 2         | 0.74%   |
| Sunplus Dell Integrated Webcam                   | 2         | 0.74%   |
| Silicon Motion WebCam SC-13HDL11939N             | 2         | 0.74%   |
| Silicon Motion 300k Pixel Camera                 | 2         | 0.74%   |
| Samsung Galaxy A5 (MTP)                          | 2         | 0.74%   |
| Ricoh Sony Visual Communication Camera           | 2         | 0.74%   |
| Ricoh Laptop_Integrated_Webcam_FHD               | 2         | 0.74%   |
| Realtek USB Camera                               | 2         | 0.74%   |
| Realtek Lenovo EasyCamera                        | 2         | 0.74%   |
| Quanta VGA WebCam                                | 2         | 0.74%   |
| Quanta Laptop_Integrated_Webcam_2HDM             | 2         | 0.74%   |
| Microdia Laptop_Integrated_Webcam_2M             | 2         | 0.74%   |
| Microdia Dell Integrated HD Webcam               | 2         | 0.74%   |
| LG G2/G3 Android Phone [MTP/PTP/Download mode]   | 2         | 0.74%   |
| IMC Networks UVC VGA Webcam                      | 2         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 49.02%  |
| Synaptics                  | 11        | 21.57%  |
| Shenzhen Goodix Technology | 4         | 7.84%   |
| Upek                       | 3         | 5.88%   |
| Elan Microelectronics      | 3         | 5.88%   |
| STMicroelectronics         | 1         | 1.96%   |
| Samsung Electronics        | 1         | 1.96%   |
| LighTuning Technology      | 1         | 1.96%   |
| Focal-systems.Corp         | 1         | 1.96%   |
| AuthenTec                  | 1         | 1.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 5         | 9.8%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 5         | 9.8%    |
| Validity Sensors VFS491                                    | 4         | 7.84%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 7.84%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 5.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 3.92%   |
| Validity Sensors Synaptics WBDI                            | 2         | 3.92%   |
| Validity Sensors Fingerprint scanner                       | 2         | 3.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 3.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.92%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 3.92%   |
| Elan ELAN:Fingerprint                                      | 2         | 3.92%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.96%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.96%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 1.96%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 1.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.96%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 1.96%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.96%   |
| Shenzhen Goodix FingerPrint                                | 1         | 1.96%   |
| Samsung Fingerprint Device                                 | 1         | 1.96%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 1.96%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.96%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.96%   |
| AuthenTec AES2810                                          | 1         | 1.96%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 23        | 58.97%  |
| Alcor Micro           | 8         | 20.51%  |
| Upek                  | 2         | 5.13%   |
| O2 Micro              | 2         | 5.13%   |
| Lenovo                | 2         | 5.13%   |
| Gemalto (was Gemplus) | 1         | 2.56%   |
| Advanced Card Systems | 1         | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 25.64%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 20.51%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 20.51%  |
| Broadcom 5880                                                                | 3         | 7.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5.13%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.13%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.13%   |
| Broadcom 58200                                                               | 2         | 5.13%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.56%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 183       | 60%     |
| 1     | 97        | 31.8%   |
| 2     | 20        | 6.56%   |
| 3     | 3         | 0.98%   |
| 8     | 2         | 0.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 32.08%  |
| Chipcard                 | 37        | 23.27%  |
| Graphics card            | 31        | 19.5%   |
| Net/wireless             | 11        | 6.92%   |
| Storage                  | 8         | 5.03%   |
| Bluetooth                | 5         | 3.14%   |
| Camera                   | 4         | 2.52%   |
| Multimedia controller    | 3         | 1.89%   |
| Sound                    | 2         | 1.26%   |
| Communication controller | 2         | 1.26%   |
| Card reader              | 2         | 1.26%   |
| Network                  | 1         | 0.63%   |
| Flash memory             | 1         | 0.63%   |
| Firewire controller      | 1         | 0.63%   |

