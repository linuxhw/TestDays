Clear Linux - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Clear Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [0e61f69494](https://linux-hardware.org/?probe=0e61f69494) | Jan 05, 2022 |
| Google        | Auron_Paine                 | [141027ba98](https://linux-hardware.org/?probe=141027ba98) | Jan 05, 2022 |
| Dell          | Inspiron 3583               | [4b12ee93be](https://linux-hardware.org/?probe=4b12ee93be) | Jan 02, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | [82cef16846](https://linux-hardware.org/?probe=82cef16846) | Dec 29, 2021 |
| Gigabyte      | GB-BSi3-6100                | [a74c0d09dd](https://linux-hardware.org/?probe=a74c0d09dd) | Dec 24, 2021 |
| Apple         | MacBookPro8,1               | [44b1bbbb9c](https://linux-hardware.org/?probe=44b1bbbb9c) | Dec 18, 2021 |
| MSI           | GP63 Leopard 8RD            | [332c4bba00](https://linux-hardware.org/?probe=332c4bba00) | Dec 18, 2021 |
| Dell          | XPS 15 9570                 | [448cdcb300](https://linux-hardware.org/?probe=448cdcb300) | Dec 17, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| Apple         | MacBookPro11,5              | [9a09876c14](https://linux-hardware.org/?probe=9a09876c14) | Nov 22, 2021 |
| HP            | Laptop 14-df0xxx            | [767039524f](https://linux-hardware.org/?probe=767039524f) | Nov 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [564ef15a99](https://linux-hardware.org/?probe=564ef15a99) | Nov 16, 2021 |
| Dell          | Inspiron 13-7378            | [e1384fb15b](https://linux-hardware.org/?probe=e1384fb15b) | Nov 12, 2021 |
| Apple         | MacBookPro11,5              | [401da402d8](https://linux-hardware.org/?probe=401da402d8) | Nov 12, 2021 |
| Apple         | MacBookPro11,5              | [7daf6ea0a5](https://linux-hardware.org/?probe=7daf6ea0a5) | Nov 12, 2021 |
| Maibenben     | E5100                       | [26a4ff554a](https://linux-hardware.org/?probe=26a4ff554a) | Nov 11, 2021 |
| Dell          | Inspiron 5558               | [45992e5117](https://linux-hardware.org/?probe=45992e5117) | Nov 11, 2021 |
| Apple         | MacBookPro11,4              | [3ba991c901](https://linux-hardware.org/?probe=3ba991c901) | Nov 10, 2021 |
| Google        | Auron_Paine                 | [1227213ee7](https://linux-hardware.org/?probe=1227213ee7) | Nov 07, 2021 |
| HP            | ProBook 450 G5              | [ecae91dfa5](https://linux-hardware.org/?probe=ecae91dfa5) | Nov 07, 2021 |
| HP            | ProBook 450 G5              | [cc4231496b](https://linux-hardware.org/?probe=cc4231496b) | Nov 07, 2021 |
| Apple         | MacBookPro11,4              | [7cdc55e110](https://linux-hardware.org/?probe=7cdc55e110) | Nov 06, 2021 |
| Dell          | Latitude 7370               | [6bf3c3796e](https://linux-hardware.org/?probe=6bf3c3796e) | Oct 30, 2021 |
| Dell          | Inspiron 3537               | [0812a6b105](https://linux-hardware.org/?probe=0812a6b105) | Oct 29, 2021 |
| Dell          | Inspiron 3537               | [0e2d73ad29](https://linux-hardware.org/?probe=0e2d73ad29) | Oct 29, 2021 |
| Lenovo        | G500 20236                  | [1587d2dbaf](https://linux-hardware.org/?probe=1587d2dbaf) | Oct 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f55ca527be](https://linux-hardware.org/?probe=f55ca527be) | Oct 21, 2021 |
| Lenovo        | V110-15IAP 80TG             | [ec77ed1da7](https://linux-hardware.org/?probe=ec77ed1da7) | Oct 16, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [89840aac65](https://linux-hardware.org/?probe=89840aac65) | Oct 13, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [fcc9eab970](https://linux-hardware.org/?probe=fcc9eab970) | Oct 12, 2021 |
| Dell          | Latitude E5470              | [08d4c126fa](https://linux-hardware.org/?probe=08d4c126fa) | Oct 11, 2021 |
| MSI           | Modern 14 B10MW             | [3f23aa5dc4](https://linux-hardware.org/?probe=3f23aa5dc4) | Oct 07, 2021 |
| MSI           | Modern 14 B10MW             | [cef5dd6d30](https://linux-hardware.org/?probe=cef5dd6d30) | Oct 07, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [77a6cb9eba](https://linux-hardware.org/?probe=77a6cb9eba) | Oct 07, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [99c08de77b](https://linux-hardware.org/?probe=99c08de77b) | Oct 07, 2021 |
| HP            | Stream Laptop 11-ak0xxx     | [64a01bd96e](https://linux-hardware.org/?probe=64a01bd96e) | Oct 06, 2021 |
| HP            | EliteBook 8460p             | [09f20340ed](https://linux-hardware.org/?probe=09f20340ed) | Oct 05, 2021 |
| HP            | EliteBook 8460p             | [34ce7d14dc](https://linux-hardware.org/?probe=34ce7d14dc) | Oct 04, 2021 |
| Acer          | Aspire E5-571P              | [8fa08d58ef](https://linux-hardware.org/?probe=8fa08d58ef) | Oct 03, 2021 |
| Acer          | Aspire E5-571P              | [6b4706ee1a](https://linux-hardware.org/?probe=6b4706ee1a) | Oct 03, 2021 |
| Dell          | Latitude 5480               | [bd21f22540](https://linux-hardware.org/?probe=bd21f22540) | Sep 28, 2021 |
| Apple         | MacBookPro8,1               | [a08d8ecd94](https://linux-hardware.org/?probe=a08d8ecd94) | Sep 21, 2021 |
| Acer          | Aspire E5-571P              | [3af02e9c48](https://linux-hardware.org/?probe=3af02e9c48) | Sep 19, 2021 |
| Acer          | Aspire E5-571P              | [790a43aecb](https://linux-hardware.org/?probe=790a43aecb) | Sep 16, 2021 |
| Acer          | Aspire E5-571P              | [f5e45f9ef5](https://linux-hardware.org/?probe=f5e45f9ef5) | Sep 16, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [05f3bfe1fe](https://linux-hardware.org/?probe=05f3bfe1fe) | Sep 14, 2021 |
| Acer          | Aspire E5-571P              | [dfe0340402](https://linux-hardware.org/?probe=dfe0340402) | Sep 04, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [3758bf5026](https://linux-hardware.org/?probe=3758bf5026) | Sep 01, 2021 |
| Acer          | Aspire V5-571G              | [575b7af6a0](https://linux-hardware.org/?probe=575b7af6a0) | Aug 30, 2021 |
| Acer          | Aspire E5-571P              | [9505862c5e](https://linux-hardware.org/?probe=9505862c5e) | Aug 29, 2021 |
| Dell          | Precision 7550              | [42721343a3](https://linux-hardware.org/?probe=42721343a3) | Aug 16, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [698b26501e](https://linux-hardware.org/?probe=698b26501e) | Aug 15, 2021 |
| Acer          | Aspire F5-573               | [8a33fea383](https://linux-hardware.org/?probe=8a33fea383) | Aug 14, 2021 |
| Acer          | Aspire F5-573               | [cada2d25da](https://linux-hardware.org/?probe=cada2d25da) | Aug 14, 2021 |
| ASUSTek       | X550LD                      | [e879ad305a](https://linux-hardware.org/?probe=e879ad305a) | Aug 12, 2021 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | [e81b578a28](https://linux-hardware.org/?probe=e81b578a28) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [2553632d5d](https://linux-hardware.org/?probe=2553632d5d) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [c77c7b6360](https://linux-hardware.org/?probe=c77c7b6360) | Aug 09, 2021 |
| Dell          | XPS 13 9310                 | [b5ab852570](https://linux-hardware.org/?probe=b5ab852570) | Aug 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [18469458d9](https://linux-hardware.org/?probe=18469458d9) | Aug 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [157f15a6de](https://linux-hardware.org/?probe=157f15a6de) | Aug 08, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [a98e8d0283](https://linux-hardware.org/?probe=a98e8d0283) | Aug 02, 2021 |
| Gigabyte      | P57                         | [7a9fa5b7d1](https://linux-hardware.org/?probe=7a9fa5b7d1) | Jul 31, 2021 |
| HP            | ENVY Laptop 17m-cg0xxx      | [c4b65848bf](https://linux-hardware.org/?probe=c4b65848bf) | Jul 28, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [bcdd6f776b](https://linux-hardware.org/?probe=bcdd6f776b) | Jul 28, 2021 |
| HP            | ENVY Laptop 17m-cg0xxx      | [e999c3f146](https://linux-hardware.org/?probe=e999c3f146) | Jul 28, 2021 |
| Lenovo        | ThinkPad X220 4291CF7       | [259e7f5b9c](https://linux-hardware.org/?probe=259e7f5b9c) | Jul 24, 2021 |
| ASUSTek       | TP550LA                     | [2a5843180d](https://linux-hardware.org/?probe=2a5843180d) | Jul 23, 2021 |
| Dell          | Inspiron 3505               | [092ad1b8e7](https://linux-hardware.org/?probe=092ad1b8e7) | Jul 22, 2021 |
| Dell          | Inspiron 5570               | [b07887acc1](https://linux-hardware.org/?probe=b07887acc1) | Jul 18, 2021 |
| Acer          | Aspire A315-23              | [f608273dd1](https://linux-hardware.org/?probe=f608273dd1) | Jul 16, 2021 |
| HP            | EliteBook 8540p             | [720242bd55](https://linux-hardware.org/?probe=720242bd55) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | [0005eb3569](https://linux-hardware.org/?probe=0005eb3569) | Jul 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [5a442d1b82](https://linux-hardware.org/?probe=5a442d1b82) | Jul 09, 2021 |
| MSI           | GS43VR 7RE                  | [93e4c242e8](https://linux-hardware.org/?probe=93e4c242e8) | Jul 09, 2021 |
| Acer          | Aspire ES1-111M             | [40450f88e3](https://linux-hardware.org/?probe=40450f88e3) | Jul 07, 2021 |
| Dell          | XPS 15 9560                 | [9bae1ef315](https://linux-hardware.org/?probe=9bae1ef315) | Jul 07, 2021 |
| Acer          | Aspire ES1-111M             | [7eb7b4a001](https://linux-hardware.org/?probe=7eb7b4a001) | Jul 07, 2021 |
| Dell          | XPS 15 9560                 | [08fad9a114](https://linux-hardware.org/?probe=08fad9a114) | Jul 03, 2021 |
| Dell          | Latitude 3330               | [f6a5d02ff8](https://linux-hardware.org/?probe=f6a5d02ff8) | Jul 02, 2021 |
| Dell          | Inspiron 7773               | [0f2d634052](https://linux-hardware.org/?probe=0f2d634052) | Jul 01, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [4c4e08cbed](https://linux-hardware.org/?probe=4c4e08cbed) | Jul 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [2279bef5dc](https://linux-hardware.org/?probe=2279bef5dc) | Jun 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [6bf8a2ed63](https://linux-hardware.org/?probe=6bf8a2ed63) | Jun 27, 2021 |
| HP            | ZBook 17 G3                 | [bb110af1eb](https://linux-hardware.org/?probe=bb110af1eb) | Jun 24, 2021 |
| HP            | ZBook 17 G3                 | [e118524a10](https://linux-hardware.org/?probe=e118524a10) | Jun 24, 2021 |
| Lenovo        | B590 62743PG                | [83bdc57e22](https://linux-hardware.org/?probe=83bdc57e22) | Jun 24, 2021 |
| HP            | Laptop 17-by2xxx            | [e414cae554](https://linux-hardware.org/?probe=e414cae554) | Jun 18, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [6ea7ce0821](https://linux-hardware.org/?probe=6ea7ce0821) | Jun 17, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [2cc70c86d4](https://linux-hardware.org/?probe=2cc70c86d4) | Jun 17, 2021 |
| EVOO          | EVC156-1                    | [a1d5d4829c](https://linux-hardware.org/?probe=a1d5d4829c) | Jun 15, 2021 |
| EVOO          | EVC156-1                    | [3823b50f55](https://linux-hardware.org/?probe=3823b50f55) | Jun 15, 2021 |
| Acer          | Aspire ES1-111M             | [e21a83e794](https://linux-hardware.org/?probe=e21a83e794) | Jun 12, 2021 |
| Google        | Coral                       | [f6cf3ed923](https://linux-hardware.org/?probe=f6cf3ed923) | Jun 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5d0ad3d400](https://linux-hardware.org/?probe=5d0ad3d400) | Jun 08, 2021 |
| Dell          | Inspiron 3558               | [c4cbc7b811](https://linux-hardware.org/?probe=c4cbc7b811) | Jun 08, 2021 |
| MOTILE        | M141                        | [533abc5ae4](https://linux-hardware.org/?probe=533abc5ae4) | Jun 06, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [fc5e5fb4f1](https://linux-hardware.org/?probe=fc5e5fb4f1) | Jun 05, 2021 |
| Dell          | Latitude 3330               | [0374f02ff3](https://linux-hardware.org/?probe=0374f02ff3) | Jun 03, 2021 |
| Dell          | Inspiron 3501               | [db4f728d1e](https://linux-hardware.org/?probe=db4f728d1e) | May 29, 2021 |
| HP            | Laptop 17-by2xxx            | [47d3f247b0](https://linux-hardware.org/?probe=47d3f247b0) | May 29, 2021 |
| HP            | Laptop 17-by2xxx            | [8477c386b6](https://linux-hardware.org/?probe=8477c386b6) | May 29, 2021 |
| HP            | Laptop 14-dq0xxx            | [bbe9417568](https://linux-hardware.org/?probe=bbe9417568) | May 28, 2021 |
| HP            | Laptop 14-dq0xxx            | [f750a7b519](https://linux-hardware.org/?probe=f750a7b519) | May 28, 2021 |
| ASUSTek       | X550LB                      | [435091e995](https://linux-hardware.org/?probe=435091e995) | May 24, 2021 |
| ASUSTek       | X550LB                      | [fb64646c9b](https://linux-hardware.org/?probe=fb64646c9b) | May 24, 2021 |
| Toshiba       | Satellite C50-A545          | [8a9dc6ab53](https://linux-hardware.org/?probe=8a9dc6ab53) | May 24, 2021 |
| Toshiba       | Satellite L850              | [6beced18da](https://linux-hardware.org/?probe=6beced18da) | May 23, 2021 |
| Acer          | TMP453-MG                   | [07291bacfe](https://linux-hardware.org/?probe=07291bacfe) | May 22, 2021 |
| Dell          | Latitude 3330               | [363f4f7708](https://linux-hardware.org/?probe=363f4f7708) | May 20, 2021 |
| Apple         | MacBookPro11,4              | [12903a99bf](https://linux-hardware.org/?probe=12903a99bf) | May 20, 2021 |
| Toshiba       | Satellite C50-A545          | [34c12e6041](https://linux-hardware.org/?probe=34c12e6041) | May 18, 2021 |
| Acer          | Aspire 7750                 | [ecf8d0fa55](https://linux-hardware.org/?probe=ecf8d0fa55) | May 18, 2021 |
| HP            | Laptop 17-by2xxx            | [6673a828e8](https://linux-hardware.org/?probe=6673a828e8) | May 18, 2021 |
| HP            | Laptop 17-by2xxx            | [3db3d9cb4a](https://linux-hardware.org/?probe=3db3d9cb4a) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | [d91a5890c9](https://linux-hardware.org/?probe=d91a5890c9) | May 18, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [5343885c32](https://linux-hardware.org/?probe=5343885c32) | May 17, 2021 |
| Samsung       | 760XBE                      | [641aa732da](https://linux-hardware.org/?probe=641aa732da) | May 17, 2021 |
| Toshiba       | Satellite C50-A545          | [d12a52a705](https://linux-hardware.org/?probe=d12a52a705) | May 14, 2021 |
| Dell          | Inspiron 5570               | [2fd333bc52](https://linux-hardware.org/?probe=2fd333bc52) | May 14, 2021 |
| Samsung       | 760XBE                      | [8065c7647a](https://linux-hardware.org/?probe=8065c7647a) | May 14, 2021 |
| Apple         | MacBookPro11,4              | [a100d4cd8a](https://linux-hardware.org/?probe=a100d4cd8a) | May 12, 2021 |
| HP            | 255 G7 Notebook PC          | [e57ab59850](https://linux-hardware.org/?probe=e57ab59850) | May 12, 2021 |
| Dell          | XPS 13 9350                 | [36d2d6ef64](https://linux-hardware.org/?probe=36d2d6ef64) | May 12, 2021 |
| Apple         | MacBookPro11,4              | [23d951aa64](https://linux-hardware.org/?probe=23d951aa64) | May 02, 2021 |
| Dell          | Latitude E5570              | [bba0c4ade9](https://linux-hardware.org/?probe=bba0c4ade9) | May 01, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [806898fe25](https://linux-hardware.org/?probe=806898fe25) | Apr 29, 2021 |
| Acer          | Aspire ES1-111M             | [aa9bfbf347](https://linux-hardware.org/?probe=aa9bfbf347) | Apr 29, 2021 |
| Acer          | Aspire ES1-111M             | [298d859193](https://linux-hardware.org/?probe=298d859193) | Apr 27, 2021 |
| Dell          | Latitude 5310               | [c308a5a20b](https://linux-hardware.org/?probe=c308a5a20b) | Apr 17, 2021 |
| Dell          | Latitude 5310               | [2eab1c1ad2](https://linux-hardware.org/?probe=2eab1c1ad2) | Apr 16, 2021 |
| Lenovo        | G50-70 20351                | [e8e1b223c6](https://linux-hardware.org/?probe=e8e1b223c6) | Apr 15, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [5ff30ea7db](https://linux-hardware.org/?probe=5ff30ea7db) | Apr 11, 2021 |
| Dell          | Latitude 7280               | [1c4da429ac](https://linux-hardware.org/?probe=1c4da429ac) | Apr 09, 2021 |
| Dell          | Latitude E7450              | [8d1df1806c](https://linux-hardware.org/?probe=8d1df1806c) | Apr 08, 2021 |
| Dell          | Latitude E7450              | [24492fbd03](https://linux-hardware.org/?probe=24492fbd03) | Apr 07, 2021 |
| HP            | Notebook                    | [e8e5c7f100](https://linux-hardware.org/?probe=e8e5c7f100) | Apr 04, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [7ffd62b3fa](https://linux-hardware.org/?probe=7ffd62b3fa) | Mar 31, 2021 |
| Lenovo        | ThinkPad T430 2347AY1       | [74bcb6eabd](https://linux-hardware.org/?probe=74bcb6eabd) | Mar 29, 2021 |
| Lenovo        | ThinkPad T430 2347AY1       | [453cb24e69](https://linux-hardware.org/?probe=453cb24e69) | Mar 29, 2021 |
| Samsung       | SF311/SF411/SF511           | [fb1261d331](https://linux-hardware.org/?probe=fb1261d331) | Mar 25, 2021 |
| Notebook      | W65_W67RN,RC1,RCY           | [c3d75ecf4f](https://linux-hardware.org/?probe=c3d75ecf4f) | Mar 25, 2021 |
| Apple         | MacBookPro12,1              | [ac590318bb](https://linux-hardware.org/?probe=ac590318bb) | Mar 22, 2021 |
| Mediacom      | Unknown                     | [5dbde592d4](https://linux-hardware.org/?probe=5dbde592d4) | Mar 18, 2021 |
| ASUSTek       | P55VA                       | [b4b0177e41](https://linux-hardware.org/?probe=b4b0177e41) | Mar 18, 2021 |
| ASUSTek       | P55VA                       | [b06371c249](https://linux-hardware.org/?probe=b06371c249) | Mar 18, 2021 |
| Dell          | Latitude E6420              | [b006880df4](https://linux-hardware.org/?probe=b006880df4) | Mar 17, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ff15d5b8ad](https://linux-hardware.org/?probe=ff15d5b8ad) | Mar 12, 2021 |
| Apple         | MacBookPro12,1              | [e3774fdabc](https://linux-hardware.org/?probe=e3774fdabc) | Mar 09, 2021 |
| Apple         | MacBookPro12,1              | [06bec9c32d](https://linux-hardware.org/?probe=06bec9c32d) | Mar 09, 2021 |
| Dell          | Latitude E6420              | [027c467458](https://linux-hardware.org/?probe=027c467458) | Mar 09, 2021 |
| HP            | Notebook                    | [2a28d46c73](https://linux-hardware.org/?probe=2a28d46c73) | Mar 09, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [77a787d158](https://linux-hardware.org/?probe=77a787d158) | Mar 08, 2021 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [21eb2bd6e0](https://linux-hardware.org/?probe=21eb2bd6e0) | Mar 07, 2021 |
| HP            | ZBook 17                    | [065ff8443f](https://linux-hardware.org/?probe=065ff8443f) | Mar 06, 2021 |
| HP            | Laptop 15q-bu1xx            | [008868f177](https://linux-hardware.org/?probe=008868f177) | Feb 28, 2021 |
| Fujitsu       | LIFEBOOK P771               | [2414020b54](https://linux-hardware.org/?probe=2414020b54) | Feb 26, 2021 |
| Fujitsu       | LIFEBOOK P771               | [ae61a5e1fa](https://linux-hardware.org/?probe=ae61a5e1fa) | Feb 26, 2021 |
| Lenovo        | ThinkPad T410 2537VQ4       | [576fa34b0c](https://linux-hardware.org/?probe=576fa34b0c) | Feb 25, 2021 |
| Acer          | Aspire V5-572P              | [61834c786c](https://linux-hardware.org/?probe=61834c786c) | Feb 24, 2021 |
| Dell          | Inspiron 5570               | [4fd5f831b6](https://linux-hardware.org/?probe=4fd5f831b6) | Feb 22, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [93e1220042](https://linux-hardware.org/?probe=93e1220042) | Feb 22, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [78ec6d58ba](https://linux-hardware.org/?probe=78ec6d58ba) | Feb 22, 2021 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [ea79d1d8e0](https://linux-hardware.org/?probe=ea79d1d8e0) | Feb 21, 2021 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [79b6fc3c82](https://linux-hardware.org/?probe=79b6fc3c82) | Feb 19, 2021 |
| Lenovo        | Zhaoyang E49L 20178         | [bf121d7dcf](https://linux-hardware.org/?probe=bf121d7dcf) | Feb 12, 2021 |
| HP            | ENVY Notebook               | [c951e2abbd](https://linux-hardware.org/?probe=c951e2abbd) | Feb 07, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0040... | [21dd1bcda6](https://linux-hardware.org/?probe=21dd1bcda6) | Feb 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2a1e54967b](https://linux-hardware.org/?probe=2a1e54967b) | Feb 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [656d39b38c](https://linux-hardware.org/?probe=656d39b38c) | Feb 05, 2021 |
| HP            | Pavilion dv6                | [a775a17be3](https://linux-hardware.org/?probe=a775a17be3) | Feb 01, 2021 |
| Acer          | Predator G9-791             | [e498f5aa1d](https://linux-hardware.org/?probe=e498f5aa1d) | Jan 30, 2021 |
| Sony          | SVF14N25CXB                 | [1db1e6aec9](https://linux-hardware.org/?probe=1db1e6aec9) | Jan 28, 2021 |
| MOTILE        | M141                        | [f26f420164](https://linux-hardware.org/?probe=f26f420164) | Jan 28, 2021 |
| MOTILE        | M141                        | [2931763d11](https://linux-hardware.org/?probe=2931763d11) | Jan 28, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [a85ceac13e](https://linux-hardware.org/?probe=a85ceac13e) | Jan 26, 2021 |
| AMI           | Intel                       | [c290895be0](https://linux-hardware.org/?probe=c290895be0) | Jan 23, 2021 |
| Dell          | Latitude E6510              | [bc65564608](https://linux-hardware.org/?probe=bc65564608) | Jan 22, 2021 |
| Dell          | Latitude E6510              | [19035e3a57](https://linux-hardware.org/?probe=19035e3a57) | Jan 22, 2021 |
| Dell          | Vostro 3350                 | [06fb5d662a](https://linux-hardware.org/?probe=06fb5d662a) | Jan 21, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [3918f52127](https://linux-hardware.org/?probe=3918f52127) | Jan 20, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [3d7ce778c6](https://linux-hardware.org/?probe=3d7ce778c6) | Jan 20, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [1883634f7b](https://linux-hardware.org/?probe=1883634f7b) | Jan 18, 2021 |
| Dell          | XPS 13 9380                 | [041ad86a38](https://linux-hardware.org/?probe=041ad86a38) | Jan 12, 2021 |
| Dell          | Latitude E7240              | [17308a75c0](https://linux-hardware.org/?probe=17308a75c0) | Dec 27, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [5b174411b3](https://linux-hardware.org/?probe=5b174411b3) | Dec 26, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [f1ae9f4de0](https://linux-hardware.org/?probe=f1ae9f4de0) | Dec 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [0c7cdd9f71](https://linux-hardware.org/?probe=0c7cdd9f71) | Dec 23, 2020 |
| Samsung       | 530XBB                      | [7b63094c3e](https://linux-hardware.org/?probe=7b63094c3e) | Dec 18, 2020 |
| Unknown       | Unknown                     | [df193070a4](https://linux-hardware.org/?probe=df193070a4) | Dec 13, 2020 |
| Unknown       | Unknown                     | [7b57f91f5d](https://linux-hardware.org/?probe=7b57f91f5d) | Dec 13, 2020 |
| Unknown       | Unknown                     | [ef997b1269](https://linux-hardware.org/?probe=ef997b1269) | Dec 12, 2020 |
| Unknown       | Unknown                     | [a49b1a585c](https://linux-hardware.org/?probe=a49b1a585c) | Dec 12, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [246bca0206](https://linux-hardware.org/?probe=246bca0206) | Dec 02, 2020 |
| HP            | EliteBook 8460p             | [e33b92bbf1](https://linux-hardware.org/?probe=e33b92bbf1) | Dec 01, 2020 |
| HP            | EliteBook 8460p             | [dfd9578421](https://linux-hardware.org/?probe=dfd9578421) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | [4a9f777280](https://linux-hardware.org/?probe=4a9f777280) | Nov 30, 2020 |
| HUAWEI        | KLVL-WXX9                   | [e6a375087e](https://linux-hardware.org/?probe=e6a375087e) | Nov 28, 2020 |
| HUAWEI        | KLVL-WXX9                   | [91806f966b](https://linux-hardware.org/?probe=91806f966b) | Nov 28, 2020 |
| HP            | Laptop 14-dk0xxx            | [410ff74e69](https://linux-hardware.org/?probe=410ff74e69) | Nov 28, 2020 |
| Avell High... | A62 LIV                     | [765753e831](https://linux-hardware.org/?probe=765753e831) | Nov 26, 2020 |
| Chuwi         | GemiBook                    | [4b86f47f1e](https://linux-hardware.org/?probe=4b86f47f1e) | Nov 24, 2020 |
| Razer         | Blade 15 Studio Edition ... | [10d20f60df](https://linux-hardware.org/?probe=10d20f60df) | Nov 21, 2020 |
| HP            | EliteBook 840 G1            | [66a2004080](https://linux-hardware.org/?probe=66a2004080) | Nov 12, 2020 |
| ASUSTek       | G551JM                      | [5bf5531f2d](https://linux-hardware.org/?probe=5bf5531f2d) | Nov 08, 2020 |
| HP            | EliteBook 8460p             | [6b3b488150](https://linux-hardware.org/?probe=6b3b488150) | Nov 05, 2020 |
| Dell          | XPS 15 9550                 | [f08f791eaf](https://linux-hardware.org/?probe=f08f791eaf) | Oct 28, 2020 |
| Lenovo        | B50-70 20384                | [cca8e03499](https://linux-hardware.org/?probe=cca8e03499) | Oct 24, 2020 |
| Panasonic     | CF-C2CKFZFCM                | [a6a2539a17](https://linux-hardware.org/?probe=a6a2539a17) | Oct 23, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [d1194ef869](https://linux-hardware.org/?probe=d1194ef869) | Oct 18, 2020 |
| HP            | 250 G3                      | [100536aea2](https://linux-hardware.org/?probe=100536aea2) | Oct 17, 2020 |
| Dell          | XPS 13 9360                 | [94f16e9c34](https://linux-hardware.org/?probe=94f16e9c34) | Oct 16, 2020 |
| Dell          | XPS 13 9360                 | [c495aa4352](https://linux-hardware.org/?probe=c495aa4352) | Oct 16, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [5d60295214](https://linux-hardware.org/?probe=5d60295214) | Oct 15, 2020 |
| HP            | Laptop 15q-bu1xx            | [bb0de25ace](https://linux-hardware.org/?probe=bb0de25ace) | Oct 15, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4b18f0db05](https://linux-hardware.org/?probe=4b18f0db05) | Oct 14, 2020 |
| Dell          | XPS 15 9560                 | [45a21ef843](https://linux-hardware.org/?probe=45a21ef843) | Oct 14, 2020 |
| Panasonic     | CF-19ADUAEDM                | [67c288d5cc](https://linux-hardware.org/?probe=67c288d5cc) | Oct 08, 2020 |
| Panasonic     | CF-19ADUAEDM                | [a730dd736c](https://linux-hardware.org/?probe=a730dd736c) | Oct 07, 2020 |
| HP            | EliteBook 8460p             | [f4c1b393b4](https://linux-hardware.org/?probe=f4c1b393b4) | Oct 05, 2020 |
| Panasonic     | CF-19ADUAEDM                | [6312d92efd](https://linux-hardware.org/?probe=6312d92efd) | Oct 05, 2020 |
| HP            | EliteBook 8460p             | [e03efe3ba7](https://linux-hardware.org/?probe=e03efe3ba7) | Oct 05, 2020 |
| HP            | EliteBook 8460p             | [8d84313282](https://linux-hardware.org/?probe=8d84313282) | Oct 04, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [57e753215c](https://linux-hardware.org/?probe=57e753215c) | Oct 04, 2020 |
| Lenovo        | ThinkPad E580 20KS002BCD    | [e89a66365d](https://linux-hardware.org/?probe=e89a66365d) | Sep 29, 2020 |
| Lenovo        | B50-70 20384                | [b2dfec8760](https://linux-hardware.org/?probe=b2dfec8760) | Sep 29, 2020 |
| HP            | Laptop 15q-bu1xx            | [8a2c7d0a65](https://linux-hardware.org/?probe=8a2c7d0a65) | Sep 25, 2020 |
| HP            | Laptop 15q-bu1xx            | [b0f3a8c5f0](https://linux-hardware.org/?probe=b0f3a8c5f0) | Sep 24, 2020 |
| HP            | 250 G3                      | [c0207d3878](https://linux-hardware.org/?probe=c0207d3878) | Sep 24, 2020 |
| Lenovo        | Yoga 300-11IBY 80M0         | [00c43e6a62](https://linux-hardware.org/?probe=00c43e6a62) | Sep 20, 2020 |
| Dell          | XPS 15 9560                 | [0b12ffde57](https://linux-hardware.org/?probe=0b12ffde57) | Sep 17, 2020 |
| Dell          | XPS 15 9560                 | [78aebc9965](https://linux-hardware.org/?probe=78aebc9965) | Sep 14, 2020 |
| Dell          | XPS 13 9343                 | [7414554e2d](https://linux-hardware.org/?probe=7414554e2d) | Sep 10, 2020 |
| MASSCOM VI... | L133                        | [b356f018b2](https://linux-hardware.org/?probe=b356f018b2) | Sep 09, 2020 |
| Dell          | Latitude E7240              | [4834754ce2](https://linux-hardware.org/?probe=4834754ce2) | Sep 09, 2020 |
| Lenovo        | Yoga 300-11IBY 80M0         | [bd721e65ce](https://linux-hardware.org/?probe=bd721e65ce) | Sep 05, 2020 |
| Dell          | XPS 13 9370                 | [783ffb159a](https://linux-hardware.org/?probe=783ffb159a) | Sep 02, 2020 |
| Apple         | MacBookPro9,2               | [a00607ac5f](https://linux-hardware.org/?probe=a00607ac5f) | Sep 01, 2020 |
| Apple         | MacBookPro9,2               | [e76eecbdaa](https://linux-hardware.org/?probe=e76eecbdaa) | Sep 01, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [988ca31973](https://linux-hardware.org/?probe=988ca31973) | Aug 31, 2020 |
| PC Special... | Fusion IV                   | [55da1618ab](https://linux-hardware.org/?probe=55da1618ab) | Aug 30, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4cd583b4b7](https://linux-hardware.org/?probe=4cd583b4b7) | Aug 30, 2020 |
| Acer          | Aspire 7750G                | [91041cbcfb](https://linux-hardware.org/?probe=91041cbcfb) | Aug 28, 2020 |
| Acer          | Aspire 7750G                | [072119fece](https://linux-hardware.org/?probe=072119fece) | Aug 28, 2020 |
| Lenovo        | G50-45 80E3                 | [44e4d217af](https://linux-hardware.org/?probe=44e4d217af) | Aug 28, 2020 |
| HP            | Laptop 14-dq1xxx            | [f880ed8f66](https://linux-hardware.org/?probe=f880ed8f66) | Aug 20, 2020 |
| Positivo      | C500                        | [71530651bb](https://linux-hardware.org/?probe=71530651bb) | Aug 18, 2020 |
| HP            | Laptop 15s-eq0xxx           | [db484283e2](https://linux-hardware.org/?probe=db484283e2) | Aug 12, 2020 |
| HP            | Laptop 15q-bu1xx            | [bc222c5b5c](https://linux-hardware.org/?probe=bc222c5b5c) | Aug 10, 2020 |
| Sony          | VPCF236FM                   | [44a563d6db](https://linux-hardware.org/?probe=44a563d6db) | Aug 06, 2020 |
| Lenovo        | ThinkPad Helix 37024V8      | [12ef944776](https://linux-hardware.org/?probe=12ef944776) | Aug 05, 2020 |
| Lenovo        | ThinkPad Helix 37024V8      | [8e8e86364e](https://linux-hardware.org/?probe=8e8e86364e) | Aug 05, 2020 |
| Dell          | Latitude E7450              | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [38442a922b](https://linux-hardware.org/?probe=38442a922b) | Aug 01, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ef4f365d92](https://linux-hardware.org/?probe=ef4f365d92) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6126a00ffc](https://linux-hardware.org/?probe=6126a00ffc) | Jul 24, 2020 |
| Samsung       | 760XBE                      | [1daa9fb781](https://linux-hardware.org/?probe=1daa9fb781) | Jul 23, 2020 |
| Samsung       | 760XBE                      | [fdc5b78be7](https://linux-hardware.org/?probe=fdc5b78be7) | Jul 23, 2020 |
| Sony          | VPCEB18FD                   | [bbd63881ce](https://linux-hardware.org/?probe=bbd63881ce) | Jul 19, 2020 |
| Sony          | VPCEB18FD                   | [2970161a20](https://linux-hardware.org/?probe=2970161a20) | Jul 19, 2020 |
| Lenovo        | ThinkPad E460 20ET0014US    | [92026f05a8](https://linux-hardware.org/?probe=92026f05a8) | Jul 07, 2020 |
| HP            | ProBook 450 G4              | [844578109a](https://linux-hardware.org/?probe=844578109a) | Jul 06, 2020 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [ef35af0360](https://linux-hardware.org/?probe=ef35af0360) | Jul 05, 2020 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [a77123da13](https://linux-hardware.org/?probe=a77123da13) | Jul 05, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [f8b39e4272](https://linux-hardware.org/?probe=f8b39e4272) | Jul 01, 2020 |
| Unknown       | MEDION                      | [994978528e](https://linux-hardware.org/?probe=994978528e) | Jun 30, 2020 |
| HP            | ENVY Sleekbook 6 PC         | [aa9335e337](https://linux-hardware.org/?probe=aa9335e337) | Jun 28, 2020 |
| Razer         | Blade 15 Base Model (Ear... | [c7c8369ab1](https://linux-hardware.org/?probe=c7c8369ab1) | Jun 28, 2020 |
| HP            | ENVY Sleekbook 6 PC         | [8502e65ee5](https://linux-hardware.org/?probe=8502e65ee5) | Jun 28, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [aba4b6462f](https://linux-hardware.org/?probe=aba4b6462f) | Jun 27, 2020 |
| Google        | Coral                       | [96a7dea193](https://linux-hardware.org/?probe=96a7dea193) | Jun 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [326b11f044](https://linux-hardware.org/?probe=326b11f044) | Jun 22, 2020 |
| Dell          | Vostro 7590                 | [9cbd8b38c1](https://linux-hardware.org/?probe=9cbd8b38c1) | Jun 16, 2020 |
| Acer          | Aspire S7-391               | [3bd6e82237](https://linux-hardware.org/?probe=3bd6e82237) | Jun 15, 2020 |
| Dell          | Inspiron 3443               | [a6c281883a](https://linux-hardware.org/?probe=a6c281883a) | Jun 14, 2020 |
| Lenovo        | G500 20236                  | [4eba6cb14f](https://linux-hardware.org/?probe=4eba6cb14f) | Jun 12, 2020 |
| Lenovo        | G500 20236                  | [de91036bf6](https://linux-hardware.org/?probe=de91036bf6) | Jun 12, 2020 |
| HP            | 340S G7                     | [c433639026](https://linux-hardware.org/?probe=c433639026) | Jun 09, 2020 |
| ASUSTek       | X541NA                      | [b8d172d989](https://linux-hardware.org/?probe=b8d172d989) | Jun 08, 2020 |
| ASUSTek       | X541NA                      | [c304a8f6f8](https://linux-hardware.org/?probe=c304a8f6f8) | Jun 08, 2020 |
| Lenovo        | ThinkPad W520 4284V21       | [6c0368dfeb](https://linux-hardware.org/?probe=6c0368dfeb) | Jun 03, 2020 |
| Lenovo        | ThinkPad W520 4284V21       | [3c335f539d](https://linux-hardware.org/?probe=3c335f539d) | Jun 03, 2020 |
| ASUSTek       | X541NA                      | [51258219c2](https://linux-hardware.org/?probe=51258219c2) | Jun 03, 2020 |
| ASUSTek       | X541NA                      | [52d3f1eccd](https://linux-hardware.org/?probe=52d3f1eccd) | Jun 03, 2020 |
| ASUSTek       | X550VX                      | [a651714cc1](https://linux-hardware.org/?probe=a651714cc1) | Jun 03, 2020 |
| Sony          | SVF14N25CXB                 | [2fdd1fc4d3](https://linux-hardware.org/?probe=2fdd1fc4d3) | Jun 02, 2020 |
| Acer          | Aspire A315-51              | [5d042bc26a](https://linux-hardware.org/?probe=5d042bc26a) | May 31, 2020 |
| Acer          | Aspire A315-51              | [5c70b2f02d](https://linux-hardware.org/?probe=5c70b2f02d) | May 31, 2020 |
| HP            | 250 G6 Notebook PC          | [99de8c34ef](https://linux-hardware.org/?probe=99de8c34ef) | May 29, 2020 |
| ASUSTek       | X541NA                      | [3b6f1169ca](https://linux-hardware.org/?probe=3b6f1169ca) | May 29, 2020 |
| Apple         | MacBookPro10,1              | [fcb77c0b07](https://linux-hardware.org/?probe=fcb77c0b07) | May 29, 2020 |
| HP            | 250 G6 Notebook PC          | [e814c4f10a](https://linux-hardware.org/?probe=e814c4f10a) | May 28, 2020 |
| HP            | 250 G6 Notebook PC          | [2c62f7166b](https://linux-hardware.org/?probe=2c62f7166b) | May 28, 2020 |
| HP            | 250 G6 Notebook PC          | [3a6891795b](https://linux-hardware.org/?probe=3a6891795b) | May 28, 2020 |
| Lenovo        | ThinkPad W550s 20E1S0L50... | [f4657ce6c7](https://linux-hardware.org/?probe=f4657ce6c7) | May 27, 2020 |
| ASUSTek       | UX390UAK                    | [0857b4df77](https://linux-hardware.org/?probe=0857b4df77) | May 27, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [429d0e0895](https://linux-hardware.org/?probe=429d0e0895) | May 25, 2020 |
| ASUSTek       | X541NA                      | [4fb4f4b3c3](https://linux-hardware.org/?probe=4fb4f4b3c3) | May 21, 2020 |
| ASUSTek       | X541NA                      | [3da0141f0b](https://linux-hardware.org/?probe=3da0141f0b) | May 20, 2020 |
| ASUSTek       | X541NA                      | [e5966e4342](https://linux-hardware.org/?probe=e5966e4342) | May 12, 2020 |
| HP            | EliteBook 840 G1            | [f6bc1aa4bf](https://linux-hardware.org/?probe=f6bc1aa4bf) | May 11, 2020 |
| Apple         | MacBookPro10,1              | [11c9e11a07](https://linux-hardware.org/?probe=11c9e11a07) | May 09, 2020 |
| HP            | EliteBook 840 G1            | [ee2382dc05](https://linux-hardware.org/?probe=ee2382dc05) | May 07, 2020 |
| HP            | EliteBook 840 G1            | [10d3d30341](https://linux-hardware.org/?probe=10d3d30341) | May 07, 2020 |
| Toshiba       | Satellite P50-C             | [c8bdff05b8](https://linux-hardware.org/?probe=c8bdff05b8) | May 07, 2020 |
| Toshiba       | Satellite P50-C             | [477e156d9b](https://linux-hardware.org/?probe=477e156d9b) | May 07, 2020 |
| Toshiba       | Satellite P50-C             | [84d5d6098e](https://linux-hardware.org/?probe=84d5d6098e) | May 07, 2020 |
| ASUSTek       | X541NA                      | [0297320c60](https://linux-hardware.org/?probe=0297320c60) | May 06, 2020 |
| ASUSTek       | X541NA                      | [4b9f8bab81](https://linux-hardware.org/?probe=4b9f8bab81) | May 05, 2020 |
| ASUSTek       | X541NA                      | [58254b6315](https://linux-hardware.org/?probe=58254b6315) | May 05, 2020 |
| ASUSTek       | X541NA                      | [ca3817dcd7](https://linux-hardware.org/?probe=ca3817dcd7) | May 05, 2020 |
| ASUSTek       | X541NA                      | [902e3ec116](https://linux-hardware.org/?probe=902e3ec116) | May 05, 2020 |
| Alienware     | M14xR2                      | [737a2771cd](https://linux-hardware.org/?probe=737a2771cd) | May 04, 2020 |
| HP            | 15 Notebook PC              | [a3a2e124bf](https://linux-hardware.org/?probe=a3a2e124bf) | May 04, 2020 |
| HP            | EliteBook 2540p             | [48e17c097d](https://linux-hardware.org/?probe=48e17c097d) | May 03, 2020 |
| HP            | EliteBook 2540p             | [8758004d49](https://linux-hardware.org/?probe=8758004d49) | May 03, 2020 |
| Dell          | Inspiron 15-3567            | [37cb5d2749](https://linux-hardware.org/?probe=37cb5d2749) | May 01, 2020 |
| Dell          | Inspiron 15-3567            | [6e28889527](https://linux-hardware.org/?probe=6e28889527) | May 01, 2020 |
| Dell          | Inspiron 15-3567            | [6939bb943e](https://linux-hardware.org/?probe=6939bb943e) | May 01, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [d11ba9afbf](https://linux-hardware.org/?probe=d11ba9afbf) | Apr 30, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [20f69deb0d](https://linux-hardware.org/?probe=20f69deb0d) | Apr 30, 2020 |
| Sony          | SVP132190X                  | [7bfb045386](https://linux-hardware.org/?probe=7bfb045386) | Apr 30, 2020 |
| Sony          | SVP132190X                  | [ea803349ac](https://linux-hardware.org/?probe=ea803349ac) | Apr 30, 2020 |
| Samsung       | 270E5G/270E5U               | [845ed80d48](https://linux-hardware.org/?probe=845ed80d48) | Apr 26, 2020 |
| Apple         | MacBookPro8,1               | [42636a47b1](https://linux-hardware.org/?probe=42636a47b1) | Apr 26, 2020 |
| Apple         | MacBookPro10,1              | [2d4ce1513b](https://linux-hardware.org/?probe=2d4ce1513b) | Apr 25, 2020 |
| Apple         | MacBookPro10,1              | [45dfee483e](https://linux-hardware.org/?probe=45dfee483e) | Apr 22, 2020 |
| Apple         | MacBookPro10,1              | [685d0ad4e2](https://linux-hardware.org/?probe=685d0ad4e2) | Apr 22, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [ad2959d25b](https://linux-hardware.org/?probe=ad2959d25b) | Apr 20, 2020 |
| HP            | EliteBook 8570p             | [261bb9de80](https://linux-hardware.org/?probe=261bb9de80) | Apr 16, 2020 |
| HP            | 15 Notebook PC              | [3a8175d360](https://linux-hardware.org/?probe=3a8175d360) | Apr 16, 2020 |
| HP            | 15 Notebook PC              | [0712cec075](https://linux-hardware.org/?probe=0712cec075) | Apr 16, 2020 |
| HP            | ENVY Laptop 17-ce1xxx       | [cf98b2c860](https://linux-hardware.org/?probe=cf98b2c860) | Apr 13, 2020 |
| Dell          | Precision M4500             | [919212e67c](https://linux-hardware.org/?probe=919212e67c) | Apr 13, 2020 |
| Acer          | Aspire A314-31              | [3f2fcfaa0f](https://linux-hardware.org/?probe=3f2fcfaa0f) | Apr 09, 2020 |
| HP            | Pavilion Notebook           | [cb3baf1d22](https://linux-hardware.org/?probe=cb3baf1d22) | Apr 08, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [bc59639878](https://linux-hardware.org/?probe=bc59639878) | Apr 07, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [6943c28c65](https://linux-hardware.org/?probe=6943c28c65) | Apr 07, 2020 |
| KANJI         | KJ-HANA                     | [a9135d6bb0](https://linux-hardware.org/?probe=a9135d6bb0) | Apr 07, 2020 |
| KANJI         | KJ-HANA                     | [a207a4c9bc](https://linux-hardware.org/?probe=a207a4c9bc) | Apr 07, 2020 |
| KANJI         | KJ-HANA                     | [e400ea0d44](https://linux-hardware.org/?probe=e400ea0d44) | Apr 07, 2020 |
| Toshiba       | Satellite L55-C             | [c6f3bbf3dd](https://linux-hardware.org/?probe=c6f3bbf3dd) | Apr 06, 2020 |
| HP            | Notebook                    | [a104da67d3](https://linux-hardware.org/?probe=a104da67d3) | Apr 05, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [1986440abc](https://linux-hardware.org/?probe=1986440abc) | Apr 03, 2020 |
| Acer          | Aspire E5-575G              | [b10c1bd149](https://linux-hardware.org/?probe=b10c1bd149) | Apr 03, 2020 |
| Apple         | MacBookPro8,1               | [429fde3ebd](https://linux-hardware.org/?probe=429fde3ebd) | Apr 02, 2020 |
| Packard Be... | EasyNote TE11HC             | [e7703e79d9](https://linux-hardware.org/?probe=e7703e79d9) | Mar 31, 2020 |
| Toshiba       | PORTEGE R930                | [0dbe97d54b](https://linux-hardware.org/?probe=0dbe97d54b) | Mar 30, 2020 |
| AXIOO         | Mybook Lite                 | [0ec3e1d33f](https://linux-hardware.org/?probe=0ec3e1d33f) | Mar 28, 2020 |
| AXIOO         | Mybook Lite                 | [539bf6ca99](https://linux-hardware.org/?probe=539bf6ca99) | Mar 28, 2020 |
| Dell          | Inspiron 3421               | [982599d139](https://linux-hardware.org/?probe=982599d139) | Mar 27, 2020 |
| Acer          | Aspire S7-391               | [6456153797](https://linux-hardware.org/?probe=6456153797) | Mar 27, 2020 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [a0dc23c790](https://linux-hardware.org/?probe=a0dc23c790) | Mar 26, 2020 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [7dbae378fe](https://linux-hardware.org/?probe=7dbae378fe) | Mar 26, 2020 |
| Lenovo        | ThinkPad X250 20CM0048US    | [62c976c563](https://linux-hardware.org/?probe=62c976c563) | Mar 25, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [f08c6424b7](https://linux-hardware.org/?probe=f08c6424b7) | Mar 22, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [9fe1bc84d4](https://linux-hardware.org/?probe=9fe1bc84d4) | Mar 22, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [069d575f4a](https://linux-hardware.org/?probe=069d575f4a) | Mar 21, 2020 |
| HP            | OMEN by HP Laptop           | [b5cbaaf3b1](https://linux-hardware.org/?probe=b5cbaaf3b1) | Mar 20, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [92148d6858](https://linux-hardware.org/?probe=92148d6858) | Mar 19, 2020 |
| Sony          | SVS151190X                  | [f8fc1f8146](https://linux-hardware.org/?probe=f8fc1f8146) | Mar 18, 2020 |
| Acer          | Aspire E5-575               | [0e0a45f908](https://linux-hardware.org/?probe=0e0a45f908) | Mar 18, 2020 |
| Acer          | Aspire E5-575               | [738e0603e3](https://linux-hardware.org/?probe=738e0603e3) | Mar 18, 2020 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [1635141ccd](https://linux-hardware.org/?probe=1635141ccd) | Mar 17, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [ccc20cb679](https://linux-hardware.org/?probe=ccc20cb679) | Mar 16, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [7b2e2dc41d](https://linux-hardware.org/?probe=7b2e2dc41d) | Mar 15, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [252c5a9ab3](https://linux-hardware.org/?probe=252c5a9ab3) | Mar 15, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [13a2b3c1cc](https://linux-hardware.org/?probe=13a2b3c1cc) | Mar 14, 2020 |
| Dell          | XPS 15 9570                 | [af9cb6cfaa](https://linux-hardware.org/?probe=af9cb6cfaa) | Mar 14, 2020 |
| MSI           | GL62 7QF                    | [7bec561443](https://linux-hardware.org/?probe=7bec561443) | Mar 13, 2020 |
| MSI           | GL62 7QF                    | [9d475bed43](https://linux-hardware.org/?probe=9d475bed43) | Mar 13, 2020 |
| Lenovo        | ThinkPad Twist 33472HU      | [3dc6c8ab7f](https://linux-hardware.org/?probe=3dc6c8ab7f) | Mar 13, 2020 |
| Lenovo        | ThinkPad Twist 33472HU      | [319e776f86](https://linux-hardware.org/?probe=319e776f86) | Mar 13, 2020 |
| Lenovo        | ThinkPad Twist 33472HU      | [0ee09fe8ae](https://linux-hardware.org/?probe=0ee09fe8ae) | Mar 13, 2020 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [6ca6dcbc34](https://linux-hardware.org/?probe=6ca6dcbc34) | Mar 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d2adad34df](https://linux-hardware.org/?probe=d2adad34df) | Mar 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [33bb47db4b](https://linux-hardware.org/?probe=33bb47db4b) | Mar 08, 2020 |
| Lenovo        | ThinkPad T440p 20AWA0850... | [8be67d92a1](https://linux-hardware.org/?probe=8be67d92a1) | Mar 08, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [1bbf1190fe](https://linux-hardware.org/?probe=1bbf1190fe) | Mar 07, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [ad3e9a51c8](https://linux-hardware.org/?probe=ad3e9a51c8) | Mar 07, 2020 |
| ASUSTek       | ZenBook UX431FA_UX431FA     | [cf0ac2c22c](https://linux-hardware.org/?probe=cf0ac2c22c) | Mar 06, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [0af19b1569](https://linux-hardware.org/?probe=0af19b1569) | Mar 04, 2020 |
| Apple         | MacBookAir5,1               | [156f5d46d9](https://linux-hardware.org/?probe=156f5d46d9) | Mar 03, 2020 |
| Acer          | Aspire S7-391               | [9d9274e346](https://linux-hardware.org/?probe=9d9274e346) | Mar 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [6eac6e2f82](https://linux-hardware.org/?probe=6eac6e2f82) | Mar 02, 2020 |
| ASUSTek       | X510UAR                     | [34798af88e](https://linux-hardware.org/?probe=34798af88e) | Mar 02, 2020 |
| ASUSTek       | X510UAR                     | [b73c34ce17](https://linux-hardware.org/?probe=b73c34ce17) | Mar 02, 2020 |
| HUAWEI        | KPL-W0X                     | [703c788767](https://linux-hardware.org/?probe=703c788767) | Mar 02, 2020 |
| HUAWEI        | KPL-W0X                     | [1159e7a361](https://linux-hardware.org/?probe=1159e7a361) | Mar 02, 2020 |
| MSI           | GS43VR 7RE                  | [3c9524e8eb](https://linux-hardware.org/?probe=3c9524e8eb) | Mar 01, 2020 |
| Lenovo        | ThinkPad X250 20CM0048US    | [62a070c8e8](https://linux-hardware.org/?probe=62a070c8e8) | Feb 29, 2020 |
| Dell          | Latitude E7240              | [2f48128844](https://linux-hardware.org/?probe=2f48128844) | Feb 29, 2020 |
| Apple         | MacBookPro15,2              | [3e260beb60](https://linux-hardware.org/?probe=3e260beb60) | Feb 29, 2020 |
| Apple         | MacBookPro15,2              | [b2936932cf](https://linux-hardware.org/?probe=b2936932cf) | Feb 29, 2020 |
| Apple         | MacBookPro15,2              | [5c56805de1](https://linux-hardware.org/?probe=5c56805de1) | Feb 29, 2020 |
| Lenovo        | ThinkPad E580 20KS001JGE    | [a1279a130c](https://linux-hardware.org/?probe=a1279a130c) | Feb 29, 2020 |
| Dell          | Inspiron 5370               | [dba6ba3410](https://linux-hardware.org/?probe=dba6ba3410) | Feb 29, 2020 |
| Dell          | Inspiron 5370               | [32cbdf058a](https://linux-hardware.org/?probe=32cbdf058a) | Feb 29, 2020 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [5843481e1f](https://linux-hardware.org/?probe=5843481e1f) | Feb 28, 2020 |
| Acer          | Aspire A517-51              | [2e94416a6c](https://linux-hardware.org/?probe=2e94416a6c) | Feb 28, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [08877a0ba8](https://linux-hardware.org/?probe=08877a0ba8) | Feb 28, 2020 |
| HP            | ProBook 450 G1              | [62ecf7a2ec](https://linux-hardware.org/?probe=62ecf7a2ec) | Feb 27, 2020 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [061ac0eac4](https://linux-hardware.org/?probe=061ac0eac4) | Feb 26, 2020 |
| Acer          | Swift SF114-32              | [7990186d76](https://linux-hardware.org/?probe=7990186d76) | Feb 26, 2020 |
| Acer          | Swift SF114-32              | [846827952c](https://linux-hardware.org/?probe=846827952c) | Feb 26, 2020 |
| Acer          | Swift SF114-32              | [93865efe48](https://linux-hardware.org/?probe=93865efe48) | Feb 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [532f40ca67](https://linux-hardware.org/?probe=532f40ca67) | Feb 26, 2020 |
| Samsung       | 300E5K/300E5Q               | [67c70768ec](https://linux-hardware.org/?probe=67c70768ec) | Feb 25, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [120e4beab4](https://linux-hardware.org/?probe=120e4beab4) | Feb 25, 2020 |
| ASUSTek       | X553MA                      | [bcfd516883](https://linux-hardware.org/?probe=bcfd516883) | Feb 25, 2020 |
| ASUSTek       | X553MA                      | [cdb4fe5f65](https://linux-hardware.org/?probe=cdb4fe5f65) | Feb 25, 2020 |
| Lenovo        | IdeaPad U310                | [cb1d9fde08](https://linux-hardware.org/?probe=cb1d9fde08) | Feb 24, 2020 |
| Acer          | Aspire V3-551               | [f0c1e637ba](https://linux-hardware.org/?probe=f0c1e637ba) | Feb 24, 2020 |
| Acer          | Aspire V3-551               | [8f0758b541](https://linux-hardware.org/?probe=8f0758b541) | Feb 24, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [9fcac55f4b](https://linux-hardware.org/?probe=9fcac55f4b) | Feb 23, 2020 |
| Apple         | MacBookPro8,2               | [9a958b3260](https://linux-hardware.org/?probe=9a958b3260) | Feb 23, 2020 |
| Dell          | Inspiron 13-5378            | [eaafafb8fc](https://linux-hardware.org/?probe=eaafafb8fc) | Feb 23, 2020 |
| HP            | EliteBook 840 G6            | [0d60789987](https://linux-hardware.org/?probe=0d60789987) | Feb 22, 2020 |
| Alienware     | M14xR2                      | [5a4277e575](https://linux-hardware.org/?probe=5a4277e575) | Feb 22, 2020 |
| Complet       | MY8312                      | [327dd7f3f6](https://linux-hardware.org/?probe=327dd7f3f6) | Feb 22, 2020 |
| Lenovo        | IdeaPad Y500 20193          | [1eaec7e819](https://linux-hardware.org/?probe=1eaec7e819) | Feb 22, 2020 |
| Lenovo        | IdeaPad Y500 20193          | [001a0cca1a](https://linux-hardware.org/?probe=001a0cca1a) | Feb 22, 2020 |
| Acer          | Aspire E5-575               | [f92a4b5c41](https://linux-hardware.org/?probe=f92a4b5c41) | Feb 21, 2020 |
| CyberPower... | TRACER III                  | [1dd6123f5e](https://linux-hardware.org/?probe=1dd6123f5e) | Feb 21, 2020 |
| Bak USA Te... | Atlas                       | [0ad59c321c](https://linux-hardware.org/?probe=0ad59c321c) | Feb 21, 2020 |
| HP            | 250 G6 Notebook PC          | [89dce04e92](https://linux-hardware.org/?probe=89dce04e92) | Feb 20, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [31d470af54](https://linux-hardware.org/?probe=31d470af54) | Feb 20, 2020 |
| Acer          | Aspire F5-573G              | [ddbd784a4c](https://linux-hardware.org/?probe=ddbd784a4c) | Feb 19, 2020 |
| Acer          | Aspire F5-573G              | [b209844e9b](https://linux-hardware.org/?probe=b209844e9b) | Feb 19, 2020 |
| Complet       | MY8312                      | [ad8b933693](https://linux-hardware.org/?probe=ad8b933693) | Feb 18, 2020 |
| Complet       | MY8312                      | [d5d53a2c14](https://linux-hardware.org/?probe=d5d53a2c14) | Feb 18, 2020 |
| Dell          | Precision 5510              | [0e30ff12b4](https://linux-hardware.org/?probe=0e30ff12b4) | Feb 18, 2020 |
| MSI           | GL63 9SDK                   | [f7631364d8](https://linux-hardware.org/?probe=f7631364d8) | Feb 18, 2020 |
| HP            | Laptop 15-da0xxx            | [b32816d9c9](https://linux-hardware.org/?probe=b32816d9c9) | Feb 17, 2020 |
| HP            | Laptop 15-da0xxx            | [a050475a4c](https://linux-hardware.org/?probe=a050475a4c) | Feb 17, 2020 |
| HP            | Laptop 15-da0xxx            | [301f08057c](https://linux-hardware.org/?probe=301f08057c) | Feb 17, 2020 |
| HP            | Laptop 15-da0xxx            | [42c2cda85b](https://linux-hardware.org/?probe=42c2cda85b) | Feb 17, 2020 |
| HP            | Laptop 15-da0xxx            | [1f1f176fed](https://linux-hardware.org/?probe=1f1f176fed) | Feb 17, 2020 |
| HP            | Laptop 15-da0xxx            | [e5d73e4be4](https://linux-hardware.org/?probe=e5d73e4be4) | Feb 17, 2020 |
| HP            | Pavilion Notebook           | [623dd83832](https://linux-hardware.org/?probe=623dd83832) | Feb 17, 2020 |
| Dell          | XPS 15 9560                 | [b6593ee087](https://linux-hardware.org/?probe=b6593ee087) | Feb 17, 2020 |
| HP            | Pavilion Notebook           | [18539e8a76](https://linux-hardware.org/?probe=18539e8a76) | Feb 16, 2020 |
| HP            | OMEN by HP Laptop           | [18e1f94ed1](https://linux-hardware.org/?probe=18e1f94ed1) | Feb 16, 2020 |
| Acer          | Aspire VX5-591G             | [3713e69080](https://linux-hardware.org/?probe=3713e69080) | Feb 16, 2020 |
| Complet       | MY8312                      | [64883dadb8](https://linux-hardware.org/?probe=64883dadb8) | Feb 16, 2020 |
| HP            | Stream Laptop 14-cb0XX      | [e8bed3c6b4](https://linux-hardware.org/?probe=e8bed3c6b4) | Feb 15, 2020 |
| HP            | Pavilion Sleekbook 14       | [b90c9066b8](https://linux-hardware.org/?probe=b90c9066b8) | Feb 15, 2020 |
| HP            | Laptop 15-da0xxx            | [2ee5466e30](https://linux-hardware.org/?probe=2ee5466e30) | Feb 15, 2020 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [ea9968943f](https://linux-hardware.org/?probe=ea9968943f) | Feb 15, 2020 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [41effd34c7](https://linux-hardware.org/?probe=41effd34c7) | Feb 15, 2020 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [f6edae1b56](https://linux-hardware.org/?probe=f6edae1b56) | Feb 14, 2020 |
| Google        | Squawks                     | [7595228ca0](https://linux-hardware.org/?probe=7595228ca0) | Feb 14, 2020 |
| HP            | EliteBook Folio 1040 G3     | [e74af3fb1a](https://linux-hardware.org/?probe=e74af3fb1a) | Feb 12, 2020 |
| HP            | Stream Laptop 14-cb0XX      | [e06df1c5e6](https://linux-hardware.org/?probe=e06df1c5e6) | Feb 11, 2020 |
| HP            | Pavilion g6                 | [e00c19c57e](https://linux-hardware.org/?probe=e00c19c57e) | Feb 11, 2020 |
| Lenovo        | ThinkPad T420 4236FJ1       | [8bdbed7f50](https://linux-hardware.org/?probe=8bdbed7f50) | Feb 11, 2020 |
| Lenovo        | ThinkPad T420 4236FJ1       | [21f76eed02](https://linux-hardware.org/?probe=21f76eed02) | Feb 11, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [17a111f812](https://linux-hardware.org/?probe=17a111f812) | Feb 11, 2020 |
| Dell          | Latitude E7240              | [ec789785f8](https://linux-hardware.org/?probe=ec789785f8) | Feb 11, 2020 |
| Fujitsu       | LIFEBOOK A514               | [699088f30e](https://linux-hardware.org/?probe=699088f30e) | Feb 10, 2020 |
| Acer          | Aspire ES1-411              | [b16a33ccf9](https://linux-hardware.org/?probe=b16a33ccf9) | Feb 10, 2020 |
| Acer          | Aspire ES1-411              | [fb63d11536](https://linux-hardware.org/?probe=fb63d11536) | Feb 10, 2020 |
| Lenovo        | G500 20236                  | [0e27af1b21](https://linux-hardware.org/?probe=0e27af1b21) | Feb 10, 2020 |
| Dell          | Precision 5540              | [3198845d50](https://linux-hardware.org/?probe=3198845d50) | Feb 10, 2020 |
| Dell          | XPS 15 9560                 | [b86c44684a](https://linux-hardware.org/?probe=b86c44684a) | Feb 10, 2020 |
| ASUSTek       | X406UAR                     | [63c393ada5](https://linux-hardware.org/?probe=63c393ada5) | Feb 09, 2020 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [1b16fc0109](https://linux-hardware.org/?probe=1b16fc0109) | Feb 09, 2020 |
| HP            | Notebook                    | [6d3168c352](https://linux-hardware.org/?probe=6d3168c352) | Feb 09, 2020 |
| HP            | OMEN by HP Laptop           | [b8591238fc](https://linux-hardware.org/?probe=b8591238fc) | Feb 02, 2020 |
| Dell          | Inspiron 5570               | [d218bf5858](https://linux-hardware.org/?probe=d218bf5858) | Feb 01, 2020 |
| HP            | OMEN by HP Laptop           | [947da231ce](https://linux-hardware.org/?probe=947da231ce) | Jan 31, 2020 |
| Acer          | Aspire V5-561G              | [a646ea611f](https://linux-hardware.org/?probe=a646ea611f) | Jan 29, 2020 |
| Apple         | MacBookPro11,5              | [1954691023](https://linux-hardware.org/?probe=1954691023) | Jan 27, 2020 |
| Acer          | Aspire V5-572PG             | [266cfb5e0b](https://linux-hardware.org/?probe=266cfb5e0b) | Jan 24, 2020 |
| Acer          | Aspire V5-572PG             | [b93df1da27](https://linux-hardware.org/?probe=b93df1da27) | Jan 23, 2020 |
| Acer          | Aspire V3-772G              | [fd1b29510e](https://linux-hardware.org/?probe=fd1b29510e) | Jan 23, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [9eb64d7269](https://linux-hardware.org/?probe=9eb64d7269) | Jan 17, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [8211b13acf](https://linux-hardware.org/?probe=8211b13acf) | Jan 17, 2020 |
| HP            | EliteBook 840 G2            | [3f1a13b63f](https://linux-hardware.org/?probe=3f1a13b63f) | Jan 09, 2020 |
| Compaq        | Presario CQ-21              | [9e818de51b](https://linux-hardware.org/?probe=9e818de51b) | Jan 07, 2020 |
| Acer          | Aspire A315-22              | [9f6abb0023](https://linux-hardware.org/?probe=9f6abb0023) | Jan 06, 2020 |
| Dell          | Inspiron 5520               | [601d03392f](https://linux-hardware.org/?probe=601d03392f) | Jan 05, 2020 |
| Acer          | Predator PH315-51           | [f7fdeaf683](https://linux-hardware.org/?probe=f7fdeaf683) | Dec 28, 2019 |
| HP            | EliteBook 840 G2            | [8279148d8f](https://linux-hardware.org/?probe=8279148d8f) | Dec 26, 2019 |
| Acer          | Aspire V3-574G              | [0bf21968fb](https://linux-hardware.org/?probe=0bf21968fb) | Dec 20, 2019 |
| Acer          | Aspire V3-574G              | [e7b2385fde](https://linux-hardware.org/?probe=e7b2385fde) | Dec 20, 2019 |
| Dell          | Inspiron 3537               | [1795b01ed8](https://linux-hardware.org/?probe=1795b01ed8) | Dec 18, 2019 |
| Acer          | Aspire V5-572PG             | [426c628480](https://linux-hardware.org/?probe=426c628480) | Dec 11, 2019 |
| ASUSTek       | X551CAP                     | [e2d8066257](https://linux-hardware.org/?probe=e2d8066257) | Dec 08, 2019 |
| Acer          | Aspire V5-572PG             | [1169693aca](https://linux-hardware.org/?probe=1169693aca) | Dec 03, 2019 |
| Dell          | Inspiron 3542               | [38da710325](https://linux-hardware.org/?probe=38da710325) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| HP            | ZBook Studio x360 G5        | [5bced05c28](https://linux-hardware.org/?probe=5bced05c28) | Nov 28, 2019 |
| HP            | ZBook Studio x360 G5        | [fb84a8579b](https://linux-hardware.org/?probe=fb84a8579b) | Nov 27, 2019 |
| Dell          | Latitude E7470              | [3c44de609a](https://linux-hardware.org/?probe=3c44de609a) | Nov 23, 2019 |
| Acer          | Aspire V3-574G              | [a6acdd8e0c](https://linux-hardware.org/?probe=a6acdd8e0c) | Nov 15, 2019 |
| Dell          | Inspiron 3537               | [8861a5ed03](https://linux-hardware.org/?probe=8861a5ed03) | Nov 15, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [d315164f73](https://linux-hardware.org/?probe=d315164f73) | Nov 15, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f1f961ebf3](https://linux-hardware.org/?probe=f1f961ebf3) | Nov 14, 2019 |
| Dell          | Inspiron 3537               | [f7721d5e6e](https://linux-hardware.org/?probe=f7721d5e6e) | Nov 13, 2019 |
| HP            | Stream Laptop 14-cb1xxx     | [4f9bcf585c](https://linux-hardware.org/?probe=4f9bcf585c) | Nov 12, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b6fdd30851](https://linux-hardware.org/?probe=b6fdd30851) | Nov 10, 2019 |
| HP            | OMEN by HP Laptop 15-dc0... | [68e18ae90f](https://linux-hardware.org/?probe=68e18ae90f) | Nov 07, 2019 |
| Dell          | Inspiron 5547               | [3e6e53b421](https://linux-hardware.org/?probe=3e6e53b421) | Nov 06, 2019 |
| ASUSTek       | X555LAB                     | [ff3c39c429](https://linux-hardware.org/?probe=ff3c39c429) | Nov 04, 2019 |
| ASUSTek       | X555LAB                     | [f932476400](https://linux-hardware.org/?probe=f932476400) | Oct 31, 2019 |
| Dell          | XPS 13 9343                 | [eaa6ab03b1](https://linux-hardware.org/?probe=eaa6ab03b1) | Oct 31, 2019 |
| Dell          | XPS 13 9343                 | [193781dfb9](https://linux-hardware.org/?probe=193781dfb9) | Oct 31, 2019 |
| Dell          | G7 7588                     | [2479b39b58](https://linux-hardware.org/?probe=2479b39b58) | Oct 27, 2019 |
| Dell          | XPS 13 9360                 | [3b65e519fc](https://linux-hardware.org/?probe=3b65e519fc) | Oct 23, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9d9a396447](https://linux-hardware.org/?probe=9d9a396447) | Oct 23, 2019 |
| Acer          | Nitro AN515-53              | [bf41b34238](https://linux-hardware.org/?probe=bf41b34238) | Oct 19, 2019 |
| Acer          | Nitro AN515-53              | [4ab07de556](https://linux-hardware.org/?probe=4ab07de556) | Oct 19, 2019 |
| Toshiba       | Satellite S55-A             | [38b27f2e0f](https://linux-hardware.org/?probe=38b27f2e0f) | Oct 18, 2019 |
| Acer          | Nitro AN515-53              | [86befe6f42](https://linux-hardware.org/?probe=86befe6f42) | Oct 16, 2019 |
| Acer          | Nitro AN515-53              | [66a6a177c7](https://linux-hardware.org/?probe=66a6a177c7) | Oct 16, 2019 |
| Acer          | Nitro AN515-53              | [51d60ee2a9](https://linux-hardware.org/?probe=51d60ee2a9) | Oct 16, 2019 |
| Acer          | Aspire V3-574G              | [632726f3fc](https://linux-hardware.org/?probe=632726f3fc) | Oct 16, 2019 |
| Acer          | Aspire V3-574G              | [933dfaebec](https://linux-hardware.org/?probe=933dfaebec) | Oct 16, 2019 |
| ASUSTek       | X453MA                      | [2838e72214](https://linux-hardware.org/?probe=2838e72214) | Oct 16, 2019 |
| ASUSTek       | X453MA                      | [6e3d93cb63](https://linux-hardware.org/?probe=6e3d93cb63) | Oct 16, 2019 |
| Acer          | Nitro AN515-53              | [32176223a3](https://linux-hardware.org/?probe=32176223a3) | Oct 15, 2019 |
| ASUSTek       | X453MA                      | [657a6e8e5c](https://linux-hardware.org/?probe=657a6e8e5c) | Oct 15, 2019 |
| Toshiba       | Satellite S55-A             | [07d9125457](https://linux-hardware.org/?probe=07d9125457) | Oct 14, 2019 |
| Dell          | Inspiron 5559               | [f51bffc1ec](https://linux-hardware.org/?probe=f51bffc1ec) | Oct 14, 2019 |
| Dell          | Inspiron 5559               | [65a5673553](https://linux-hardware.org/?probe=65a5673553) | Oct 14, 2019 |
| Gigabyte      | GB-BSi3-6100                | [dd56498fbf](https://linux-hardware.org/?probe=dd56498fbf) | Oct 14, 2019 |
| Gigabyte      | GB-BSi3-6100                | [bf5ab9b927](https://linux-hardware.org/?probe=bf5ab9b927) | Oct 14, 2019 |
| Toshiba       | Satellite S55-A             | [444cd46637](https://linux-hardware.org/?probe=444cd46637) | Oct 08, 2019 |
| Toshiba       | Satellite S55-A             | [84eb00f196](https://linux-hardware.org/?probe=84eb00f196) | Oct 08, 2019 |
| Toshiba       | Satellite S55-A             | [cef009a622](https://linux-hardware.org/?probe=cef009a622) | Oct 08, 2019 |
| Dell          | XPS 13 9360                 | [11cf128e4b](https://linux-hardware.org/?probe=11cf128e4b) | Sep 17, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | [45ff155f8e](https://linux-hardware.org/?probe=45ff155f8e) | Sep 15, 2019 |
| Hampoo        | B3W6_NA123C Reserved        | [8129327b0d](https://linux-hardware.org/?probe=8129327b0d) | Sep 14, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8dbe2671e7](https://linux-hardware.org/?probe=8dbe2671e7) | Sep 14, 2019 |
| Toshiba       | Satellite L855              | [f5d2dffc84](https://linux-hardware.org/?probe=f5d2dffc84) | Sep 13, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1fb8a35227](https://linux-hardware.org/?probe=1fb8a35227) | Sep 13, 2019 |
| ASUSTek       | X540NA                      | [0091150282](https://linux-hardware.org/?probe=0091150282) | Sep 11, 2019 |
| Apple         | MacBookPro9,2               | [1bd87674b0](https://linux-hardware.org/?probe=1bd87674b0) | Sep 08, 2019 |
| Gigabyte      | X5V6                        | [42d74d3387](https://linux-hardware.org/?probe=42d74d3387) | Sep 07, 2019 |
| ASUSTek       | Strix 17 GL703GE            | [c34161a66d](https://linux-hardware.org/?probe=c34161a66d) | Sep 02, 2019 |
| Dell          | Latitude E6430              | [32e71a014c](https://linux-hardware.org/?probe=32e71a014c) | Aug 25, 2019 |
| Dell          | Latitude E6430              | [c25ea97bb1](https://linux-hardware.org/?probe=c25ea97bb1) | Aug 25, 2019 |
| Dell          | Latitude E6430              | [ba8379b425](https://linux-hardware.org/?probe=ba8379b425) | Aug 25, 2019 |
| Complet       | MY8312                      | [fe23b19e30](https://linux-hardware.org/?probe=fe23b19e30) | Aug 18, 2019 |
| HP            | Stream Laptop 14-cb0XX      | [cd4612107c](https://linux-hardware.org/?probe=cd4612107c) | Aug 14, 2019 |
| Dell          | Latitude E6540              | [c9564bf81b](https://linux-hardware.org/?probe=c9564bf81b) | Aug 10, 2019 |
| Dell          | Latitude E6540              | [8165f7312c](https://linux-hardware.org/?probe=8165f7312c) | Aug 10, 2019 |
| Google        | Celes                       | [fb211eb782](https://linux-hardware.org/?probe=fb211eb782) | Aug 08, 2019 |
| MECHREVO      | X6Ti Series GH5KN51         | [15434c10dd](https://linux-hardware.org/?probe=15434c10dd) | Jul 29, 2019 |
| Lenovo        | G580 2189                   | [f3d7e4e13d](https://linux-hardware.org/?probe=f3d7e4e13d) | Jul 19, 2019 |
| Lenovo        | G580 2189                   | [a75a2e9dae](https://linux-hardware.org/?probe=a75a2e9dae) | Jul 19, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1613715663](https://linux-hardware.org/?probe=1613715663) | Jul 15, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [aed8974317](https://linux-hardware.org/?probe=aed8974317) | Jul 15, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62ebee4d1f](https://linux-hardware.org/?probe=62ebee4d1f) | Jul 15, 2019 |
| Lenovo        | B50-80 80LT                 | [8bb3d800bf](https://linux-hardware.org/?probe=8bb3d800bf) | Jul 04, 2019 |
| Lenovo        | B50-80 80LT                 | [86895d0347](https://linux-hardware.org/?probe=86895d0347) | Jul 04, 2019 |
| Lenovo        | B50-80 80LT                 | [c9470fc4c0](https://linux-hardware.org/?probe=c9470fc4c0) | Jul 04, 2019 |
| MSI           | GT80 2QE                    | [e23b8672e1](https://linux-hardware.org/?probe=e23b8672e1) | Jul 03, 2019 |
| Dell          | Latitude E7240              | [c0c75ef0df](https://linux-hardware.org/?probe=c0c75ef0df) | Jul 03, 2019 |
| Alienware     | 13                          | [3ffc07f627](https://linux-hardware.org/?probe=3ffc07f627) | Jun 22, 2019 |
| MSI           | GT80 2QE                    | [5f8e5c052d](https://linux-hardware.org/?probe=5f8e5c052d) | Jun 17, 2019 |
| MSI           | GT80 2QE                    | [8fd27a6b05](https://linux-hardware.org/?probe=8fd27a6b05) | Jun 12, 2019 |
| ASUSTek       | X302LJ                      | [ca06e39372](https://linux-hardware.org/?probe=ca06e39372) | Jun 11, 2019 |
| ASUSTek       | X302LJ                      | [38ba3bc487](https://linux-hardware.org/?probe=38ba3bc487) | Jun 11, 2019 |
| MSI           | GT80 2QE                    | [65f0553c7c](https://linux-hardware.org/?probe=65f0553c7c) | Jun 08, 2019 |
| MSI           | GT80 2QE                    | [248546b55e](https://linux-hardware.org/?probe=248546b55e) | Jun 06, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [70fecd4e42](https://linux-hardware.org/?probe=70fecd4e42) | Jun 04, 2019 |
| ASUSTek       | UX31A                       | [377e8b594a](https://linux-hardware.org/?probe=377e8b594a) | Jun 03, 2019 |
| Dell          | Inspiron 5720               | [9292730fa3](https://linux-hardware.org/?probe=9292730fa3) | Jun 02, 2019 |
| MSI           | GT80 2QE                    | [c46dfa6bb2](https://linux-hardware.org/?probe=c46dfa6bb2) | May 30, 2019 |
| Lenovo        | Unknown                     | [bb521ffe81](https://linux-hardware.org/?probe=bb521ffe81) | May 29, 2019 |
| Lenovo        | Unknown                     | [ded7e33a30](https://linux-hardware.org/?probe=ded7e33a30) | May 29, 2019 |
| MSI           | GT80 2QE                    | [d767391353](https://linux-hardware.org/?probe=d767391353) | May 29, 2019 |
| Lenovo        | ThinkPad T450 20BUS1DH00    | [3686a559e0](https://linux-hardware.org/?probe=3686a559e0) | May 28, 2019 |
| MSI           | GT80 2QE                    | [fd03c73bc7](https://linux-hardware.org/?probe=fd03c73bc7) | May 27, 2019 |
| Acer          | Aspire V3-772G              | [08537101e8](https://linux-hardware.org/?probe=08537101e8) | May 26, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [217dc98a9f](https://linux-hardware.org/?probe=217dc98a9f) | May 26, 2019 |
| Acer          | Aspire V3-772G              | [6f12f62179](https://linux-hardware.org/?probe=6f12f62179) | May 26, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [c94d8180a7](https://linux-hardware.org/?probe=c94d8180a7) | May 26, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [11c13da62b](https://linux-hardware.org/?probe=11c13da62b) | May 23, 2019 |
| Lenovo        | Y520-15IKBM 80YY            | [d814f4eab3](https://linux-hardware.org/?probe=d814f4eab3) | May 21, 2019 |
| HP            | EliteBook 840 G1            | [e038d3c88d](https://linux-hardware.org/?probe=e038d3c88d) | May 21, 2019 |
| Lenovo        | G50-70 20351                | [84c3544bb2](https://linux-hardware.org/?probe=84c3544bb2) | May 20, 2019 |
| MSI           | GT80 2QE                    | [2b30bc8319](https://linux-hardware.org/?probe=2b30bc8319) | May 19, 2019 |
| Acer          | Aspire E5-576G              | [97183f5186](https://linux-hardware.org/?probe=97183f5186) | May 18, 2019 |
| HP            | Pavilion Notebook           | [5048eb8853](https://linux-hardware.org/?probe=5048eb8853) | May 17, 2019 |
| HP            | Laptop 15-bs2xx             | [db976f7ed5](https://linux-hardware.org/?probe=db976f7ed5) | May 15, 2019 |
| ASUSTek       | Strix 17 GL703GE            | [328975f3a5](https://linux-hardware.org/?probe=328975f3a5) | May 15, 2019 |
| MSI           | GT80 2QE                    | [2ccf0b5196](https://linux-hardware.org/?probe=2ccf0b5196) | May 14, 2019 |
| MSI           | GT80 2QE                    | [3856eb3405](https://linux-hardware.org/?probe=3856eb3405) | May 14, 2019 |
| Gigabyte      | M1M3XAP-00                  | [fa543553ec](https://linux-hardware.org/?probe=fa543553ec) | Apr 19, 2019 |
| Acer          | Aspire A515-52G             | [6c5781b14b](https://linux-hardware.org/?probe=6c5781b14b) | Apr 09, 2019 |
| Acer          | Aspire A515-52G             | [3fb9d9f561](https://linux-hardware.org/?probe=3fb9d9f561) | Apr 09, 2019 |
| Acer          | Aspire A515-52G             | [83a517d4ed](https://linux-hardware.org/?probe=83a517d4ed) | Apr 09, 2019 |
| Timi          | TM1701                      | [fa7e44951e](https://linux-hardware.org/?probe=fa7e44951e) | Mar 29, 2019 |
| Dell          | Inspiron 15 7000 Gaming     | [882d11658b](https://linux-hardware.org/?probe=882d11658b) | Mar 26, 2019 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1e7adbe67a](https://linux-hardware.org/?probe=1e7adbe67a) | Dec 26, 2018 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [a684d1aeea](https://linux-hardware.org/?probe=a684d1aeea) | Dec 26, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.5.6-914.native    | 19        | 4.99%   |
| 5.4.18-902.native   | 15        | 3.94%   |
| 5.13.13-1070.native | 13        | 3.41%   |
| 5.10.19-1032.native | 13        | 3.41%   |
| 5.12.14-1051.native | 10        | 2.62%   |
| 5.5.5-911.native    | 9         | 2.36%   |
| 5.7.13-975.native   | 8         | 2.1%    |
| 5.5.15-930.native   | 7         | 1.84%   |
| 5.5.4-909.native    | 6         | 1.57%   |
| 5.5.3-908.native    | 6         | 1.57%   |
| 5.13.8-1065.native  | 6         | 1.57%   |
| 5.12.8-1045.native  | 6         | 1.57%   |
| 5.9.8-1000.native   | 5         | 1.31%   |
| 5.7.6-966.native    | 5         | 1.31%   |
| 5.6.8-945.native    | 5         | 1.31%   |
| 5.5.8-917.native    | 5         | 1.31%   |
| 5.12.5-1041.native  | 5         | 1.31%   |
| 5.10.10-1017.native | 5         | 1.31%   |
| 5.9.12-1004.native  | 4         | 1.05%   |
| 5.7.7-967.native    | 4         | 1.05%   |
| 5.6.6-942.native    | 4         | 1.05%   |
| 5.5.3-905.native    | 4         | 1.05%   |
| 5.4.6-883.native    | 4         | 1.05%   |
| 5.3.8-854.native    | 4         | 1.05%   |
| 5.14.9-1079.native  | 4         | 1.05%   |
| 5.10.17-1026.native | 4         | 1.05%   |
| 5.1.5-770.native    | 4         | 1.05%   |
| 5.0.18-767.native   | 4         | 1.05%   |
| 5.9.1-992.native    | 3         | 0.79%   |
| 5.8.14-991.native   | 3         | 0.79%   |
| 5.8.12-989.native   | 3         | 0.79%   |
| 5.7.2-962.native    | 3         | 0.79%   |
| 5.7.11-973.native   | 3         | 0.79%   |
| 5.6.16-958.native   | 3         | 0.79%   |
| 5.6.15-957.native   | 3         | 0.79%   |
| 5.5.9-918.native    | 3         | 0.79%   |
| 5.5.13-924.native   | 3         | 0.79%   |
| 5.5.10-921.native   | 3         | 0.79%   |
| 5.3.5-847.native    | 3         | 0.79%   |
| 5.2.13-832.native   | 3         | 0.79%   |
| 5.14.15-1086.native | 3         | 0.79%   |
| 5.10.18-1027.native | 3         | 0.79%   |
| 5.9.10-1002.native  | 2         | 0.52%   |
| 5.8.10-987.native   | 2         | 0.52%   |
| 5.7.18-980.native   | 2         | 0.52%   |
| 5.6.4-937.native    | 2         | 0.52%   |
| 5.6.3-935.native    | 2         | 0.52%   |
| 5.6.14-955.native   | 2         | 0.52%   |
| 5.6.11-948.native   | 2         | 0.52%   |
| 5.5.11-922.native   | 2         | 0.52%   |
| 5.4.16-900.native   | 2         | 0.52%   |
| 5.4.12-893.native   | 2         | 0.52%   |
| 5.4.101-103.lts2019 | 2         | 0.52%   |
| 5.3.7-853.native    | 2         | 0.52%   |
| 5.3.6-849.native    | 2         | 0.52%   |
| 5.3.2-844.native    | 2         | 0.52%   |
| 5.3.12-871.native   | 2         | 0.52%   |
| 5.2.8-818.native    | 2         | 0.52%   |
| 5.2.11-830.native   | 2         | 0.52%   |
| 5.15.7-1106.native  | 2         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.5.6   | 19        | 4.99%   |
| 5.4.18  | 15        | 3.94%   |
| 5.13.13 | 13        | 3.41%   |
| 5.10.19 | 13        | 3.41%   |
| 5.5.3   | 10        | 2.62%   |
| 5.12.14 | 10        | 2.62%   |
| 5.5.5   | 9         | 2.36%   |
| 5.7.13  | 8         | 2.1%    |
| 5.5.15  | 7         | 1.84%   |
| 5.6.8   | 6         | 1.57%   |
| 5.5.4   | 6         | 1.57%   |
| 5.13.8  | 6         | 1.57%   |
| 5.12.8  | 6         | 1.57%   |
| 5.9.8   | 5         | 1.31%   |
| 5.7.6   | 5         | 1.31%   |
| 5.5.8   | 5         | 1.31%   |
| 5.12.5  | 5         | 1.31%   |
| 5.10.10 | 5         | 1.31%   |
| 5.9.12  | 4         | 1.05%   |
| 5.7.7   | 4         | 1.05%   |
| 5.6.6   | 4         | 1.05%   |
| 5.6.15  | 4         | 1.05%   |
| 5.5.9   | 4         | 1.05%   |
| 5.4.6   | 4         | 1.05%   |
| 5.3.8   | 4         | 1.05%   |
| 5.14.9  | 4         | 1.05%   |
| 5.10.17 | 4         | 1.05%   |
| 5.1.5   | 4         | 1.05%   |
| 5.0.18  | 4         | 1.05%   |
| 5.9.1   | 3         | 0.79%   |
| 5.8.14  | 3         | 0.79%   |
| 5.8.12  | 3         | 0.79%   |
| 5.7.2   | 3         | 0.79%   |
| 5.7.11  | 3         | 0.79%   |
| 5.6.4   | 3         | 0.79%   |
| 5.6.3   | 3         | 0.79%   |
| 5.6.16  | 3         | 0.79%   |
| 5.5.13  | 3         | 0.79%   |
| 5.5.10  | 3         | 0.79%   |
| 5.3.5   | 3         | 0.79%   |
| 5.2.8   | 3         | 0.79%   |
| 5.2.13  | 3         | 0.79%   |
| 5.2.11  | 3         | 0.79%   |
| 5.14.15 | 3         | 0.79%   |
| 5.10.18 | 3         | 0.79%   |
| 5.1.15  | 3         | 0.79%   |
| 5.0.17  | 3         | 0.79%   |
| 5.9.10  | 2         | 0.52%   |
| 5.8.10  | 2         | 0.52%   |
| 5.7.18  | 2         | 0.52%   |
| 5.6.14  | 2         | 0.52%   |
| 5.6.11  | 2         | 0.52%   |
| 5.5.11  | 2         | 0.52%   |
| 5.4.16  | 2         | 0.52%   |
| 5.4.12  | 2         | 0.52%   |
| 5.4.101 | 2         | 0.52%   |
| 5.3.7   | 2         | 0.52%   |
| 5.3.6   | 2         | 0.52%   |
| 5.3.2   | 2         | 0.52%   |
| 5.3.12  | 2         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.5     | 67        | 18.41%  |
| 5.10    | 37        | 10.16%  |
| 5.4     | 34        | 9.34%   |
| 5.12    | 32        | 8.79%   |
| 5.7     | 29        | 7.97%   |
| 5.6     | 29        | 7.97%   |
| 5.13    | 22        | 6.04%   |
| 5.3     | 19        | 5.22%   |
| 5.9     | 18        | 4.95%   |
| 5.0     | 15        | 4.12%   |
| 5.2     | 13        | 3.57%   |
| 5.8     | 11        | 3.02%   |
| 5.14    | 11        | 3.02%   |
| 5.1     | 11        | 3.02%   |
| 5.15    | 8         | 2.2%    |
| 4.19    | 8         | 2.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 334       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 264       | 76.08%  |
| Unknown         | 54        | 15.56%  |
| KDE             | 13        | 3.75%   |
| GNOME Flashback | 11        | 3.17%   |
| XFCE            | 3         | 0.86%   |
| KDE5            | 1         | 0.29%   |
| awesome         | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 317       | 94.63%  |
| Wayland | 17        | 5.07%   |
| Tty     | 1         | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 330       | 98.8%   |
| GDM     | 3         | 0.9%    |
| SDDM    | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 212       | 62.54%  |
| Unknown | 52        | 15.34%  |
| ru_RU   | 16        | 4.72%   |
| de_DE   | 10        | 2.95%   |
| es_MX   | 6         | 1.77%   |
| en_GB   | 6         | 1.77%   |
| es_ES   | 5         | 1.47%   |
| pl_PL   | 4         | 1.18%   |
| it_IT   | 4         | 1.18%   |
| fr_FR   | 4         | 1.18%   |
| pt_BR   | 3         | 0.88%   |
| en_AU   | 3         | 0.88%   |
| zh_CN   | 2         | 0.59%   |
| tr_TR   | 2         | 0.59%   |
| bg_BG   | 2         | 0.59%   |
| pt_PT   | 1         | 0.29%   |
| nl_NL   | 1         | 0.29%   |
| nl_BE   | 1         | 0.29%   |
| ka_GE   | 1         | 0.29%   |
| hu_HU   | 1         | 0.29%   |
| fi_FI   | 1         | 0.29%   |
| en_ZA   | 1         | 0.29%   |
| ar_SA   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 334       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 276       | 81.42%  |
| Unknown | 57        | 16.81%  |
| Xfs     | 3         | 0.88%   |
| Btrfs   | 3         | 0.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 328       | 97.91%  |
| GPT     | 7         | 2.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 333       | 99.7%   |
| Yes       | 1         | 0.3%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 330       | 98.8%   |
| Yes       | 4         | 1.2%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 62        | 18.56%  |
| Dell                   | 61        | 18.26%  |
| Hewlett-Packard        | 53        | 15.87%  |
| ASUSTek Computer       | 38        | 11.38%  |
| Acer                   | 31        | 9.28%   |
| Apple                  | 16        | 4.79%   |
| Samsung Electronics    | 9         | 2.69%   |
| Toshiba                | 7         | 2.1%    |
| MSI                    | 7         | 2.1%    |
| Sony                   | 5         | 1.5%    |
| Google                 | 5         | 1.5%    |
| Gigabyte Technology    | 4         | 1.2%    |
| Complet                | 3         | 0.9%    |
| Unknown                | 3         | 0.9%    |
| Panasonic              | 2         | 0.6%    |
| MOTILE                 | 2         | 0.6%    |
| HUAWEI                 | 2         | 0.6%    |
| Fujitsu                | 2         | 0.6%    |
| Alienware              | 2         | 0.6%    |
| Timi                   | 1         | 0.3%    |
| Razer                  | 1         | 0.3%    |
| Positivo               | 1         | 0.3%    |
| PC Specialist          | 1         | 0.3%    |
| Packard Bell           | 1         | 0.3%    |
| Notebook               | 1         | 0.3%    |
| Mediacom               | 1         | 0.3%    |
| MECHREVO               | 1         | 0.3%    |
| MASSCOM VIETNAM        | 1         | 0.3%    |
| Maibenben              | 1         | 0.3%    |
| KANJI                  | 1         | 0.3%    |
| Hampoo                 | 1         | 0.3%    |
| EVOO                   | 1         | 0.3%    |
| CyberPowerPC           | 1         | 0.3%    |
| Compaq                 | 1         | 0.3%    |
| Chuwi                  | 1         | 0.3%    |
| Bak USA Technologies   | 1         | 0.3%    |
| AXIOO                  | 1         | 0.3%    |
| Avell High Performance | 1         | 0.3%    |
| AMI                    | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Dell XPS 15 9560                                   | 5         | 1.5%    |
| Unknown                                            | 5         | 1.5%    |
| HP Notebook                                        | 4         | 1.2%    |
| Lenovo G500 20236                                  | 3         | 0.9%    |
| HP Pavilion Notebook                               | 3         | 0.9%    |
| HP EliteBook 8460p                                 | 3         | 0.9%    |
| HP EliteBook 840 G1                                | 3         | 0.9%    |
| Dell XPS 13 9360                                   | 3         | 0.9%    |
| Dell Inspiron 5570                                 | 3         | 0.9%    |
| Complet MY8312                                     | 3         | 0.9%    |
| Apple MacBookPro8,1                                | 3         | 0.9%    |
| Apple MacBookPro11,5                               | 3         | 0.9%    |
| Apple MacBookPro10,1                               | 3         | 0.9%    |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D         | 2         | 0.6%    |
| MSI GS43VR 7RE                                     | 2         | 0.6%    |
| MOTILE M141                                        | 2         | 0.6%    |
| Lenovo IdeaPad 110-15ACL 80TJ                      | 2         | 0.6%    |
| Lenovo G50-70 20351                                | 2         | 0.6%    |
| HP Stream Laptop 14-cb0XX                          | 2         | 0.6%    |
| HP 250 G6 Notebook PC                              | 2         | 0.6%    |
| Google Auron_Paine                                 | 2         | 0.6%    |
| Dell XPS 15 9570                                   | 2         | 0.6%    |
| Dell XPS 13 9343                                   | 2         | 0.6%    |
| Dell Latitude E7450                                | 2         | 0.6%    |
| Dell Inspiron 5370                                 | 2         | 0.6%    |
| Dell Inspiron 3537                                 | 2         | 0.6%    |
| ASUS X553MA                                        | 2         | 0.6%    |
| Apple MacBookPro9,2                                | 2         | 0.6%    |
| Acer Aspire V3-772G                                | 2         | 0.6%    |
| Acer Aspire ES1-111M                               | 2         | 0.6%    |
| Acer Aspire E5-575                                 | 2         | 0.6%    |
| Toshiba Satellite S55-A                            | 1         | 0.3%    |
| Toshiba Satellite P50-C                            | 1         | 0.3%    |
| Toshiba Satellite L855                             | 1         | 0.3%    |
| Toshiba Satellite L850                             | 1         | 0.3%    |
| Toshiba Satellite L55-C                            | 1         | 0.3%    |
| Toshiba Satellite C50-A545                         | 1         | 0.3%    |
| Toshiba PORTEGE R930                               | 1         | 0.3%    |
| Timi TM1701                                        | 1         | 0.3%    |
| Sony VPCF236FM                                     | 1         | 0.3%    |
| Sony VPCEB18FD                                     | 1         | 0.3%    |
| Sony SVS151190X                                    | 1         | 0.3%    |
| Sony SVP132190X                                    | 1         | 0.3%    |
| Sony SVF14N25CXB                                   | 1         | 0.3%    |
| Samsung SF311/SF411/SF511                          | 1         | 0.3%    |
| Samsung 760XBE                                     | 1         | 0.3%    |
| Samsung 530XBB                                     | 1         | 0.3%    |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B         | 1         | 0.3%    |
| Samsung 300E5K/300E5Q                              | 1         | 0.3%    |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA         | 1         | 0.3%    |
| Samsung 270E5G/270E5U                              | 1         | 0.3%    |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.3%    |
| Positivo C500                                      | 1         | 0.3%    |
| PC Specialist Fusion IV                            | 1         | 0.3%    |
| Panasonic CF-C2CKFZFCM                             | 1         | 0.3%    |
| Panasonic CF-19ADUAEDM                             | 1         | 0.3%    |
| Packard Bell EasyNote TE11HC                       | 1         | 0.3%    |
| Notebook W65_W67RN,RC1,RCY                         | 1         | 0.3%    |
| MSI Modern 14 B10MW                                | 1         | 0.3%    |
| MSI GT80 2QE                                       | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 27        | 8.08%   |
| Lenovo ThinkPad        | 22        | 6.59%   |
| Dell Inspiron          | 22        | 6.59%   |
| Lenovo IdeaPad         | 18        | 5.39%   |
| Dell XPS               | 17        | 5.09%   |
| Dell Latitude          | 15        | 4.49%   |
| HP EliteBook           | 12        | 3.59%   |
| ASUS VivoBook          | 11        | 3.29%   |
| HP Pavilion            | 10        | 2.99%   |
| HP Laptop              | 7         | 2.1%    |
| Toshiba Satellite      | 6         | 1.8%    |
| HP Stream              | 5         | 1.5%    |
| Unknown                | 5         | 1.5%    |
| HP Notebook            | 4         | 1.2%    |
| Dell Precision         | 4         | 1.2%    |
| ASUS ZenBook           | 4         | 1.2%    |
| Apple MacBookPro8      | 4         | 1.2%    |
| Apple MacBookPro11     | 4         | 1.2%    |
| Lenovo Yoga            | 3         | 0.9%    |
| Lenovo G500            | 3         | 0.9%    |
| HP ZBook               | 3         | 0.9%    |
| HP ENVY                | 3         | 0.9%    |
| HP 250                 | 3         | 0.9%    |
| Complet MY8312         | 3         | 0.9%    |
| ASUS ROG               | 3         | 0.9%    |
| Apple MacBookPro10     | 3         | 0.9%    |
| Samsung 900X3C         | 2         | 0.6%    |
| MSI GS43VR             | 2         | 0.6%    |
| MOTILE M141            | 2         | 0.6%    |
| Lenovo Legion          | 2         | 0.6%    |
| Lenovo G50-70          | 2         | 0.6%    |
| HP ProBook             | 2         | 0.6%    |
| Google Auron           | 2         | 0.6%    |
| Fujitsu LIFEBOOK       | 2         | 0.6%    |
| Dell Vostro            | 2         | 0.6%    |
| ASUS X553MA            | 2         | 0.6%    |
| ASUS Strix             | 2         | 0.6%    |
| Apple MacBookPro9      | 2         | 0.6%    |
| Acer Predator          | 2         | 0.6%    |
| Toshiba PORTEGE        | 1         | 0.3%    |
| Timi TM1701            | 1         | 0.3%    |
| Sony VPCF236FM         | 1         | 0.3%    |
| Sony VPCEB18FD         | 1         | 0.3%    |
| Sony SVS151190X        | 1         | 0.3%    |
| Sony SVP132190X        | 1         | 0.3%    |
| Sony SVF14N25CXB       | 1         | 0.3%    |
| Samsung SF311          | 1         | 0.3%    |
| Samsung 760XBE         | 1         | 0.3%    |
| Samsung 530XBB         | 1         | 0.3%    |
| Samsung 300V3A         | 1         | 0.3%    |
| Samsung 300E5K         | 1         | 0.3%    |
| Samsung 300E4A         | 1         | 0.3%    |
| Samsung 270E5G         | 1         | 0.3%    |
| Razer Blade            | 1         | 0.3%    |
| Positivo C500          | 1         | 0.3%    |
| PC Specialist Fusion   | 1         | 0.3%    |
| Panasonic CF-C2CKFZFCM | 1         | 0.3%    |
| Panasonic CF-19ADUAEDM | 1         | 0.3%    |
| Packard Bell EasyNote  | 1         | 0.3%    |
| Notebook W65           | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 87        | 26.05%  |
| 2018 | 53        | 15.87%  |
| 2020 | 45        | 13.47%  |
| 2014 | 26        | 7.78%   |
| 2013 | 25        | 7.49%   |
| 2016 | 22        | 6.59%   |
| 2015 | 21        | 6.29%   |
| 2021 | 19        | 5.69%   |
| 2017 | 18        | 5.39%   |
| 2012 | 12        | 3.59%   |
| 2011 | 5         | 1.5%    |
| 2010 | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 334       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 334       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 329       | 98.5%   |
| Yes  | 5         | 1.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 81        | 24.11%  |
| 8.01-16.0  | 78        | 23.21%  |
| 16.01-24.0 | 75        | 22.32%  |
| 3.01-4.0   | 72        | 21.43%  |
| 32.01-64.0 | 16        | 4.76%   |
| 1.01-2.0   | 9         | 2.68%   |
| 24.01-32.0 | 4         | 1.19%   |
| 2.01-3.0   | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 165       | 45.96%  |
| 2.01-3.0  | 115       | 32.03%  |
| 3.01-4.0  | 40        | 11.14%  |
| 4.01-8.0  | 24        | 6.69%   |
| 0.51-1.0  | 9         | 2.51%   |
| 8.01-16.0 | 6         | 1.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 247       | 72.65%  |
| 2      | 76        | 22.35%  |
| 3      | 13        | 3.82%   |
| 0      | 2         | 0.59%   |
| 6      | 1         | 0.29%   |
| 5      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 235       | 70.36%  |
| Yes       | 99        | 29.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 248       | 74.25%  |
| No        | 86        | 25.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 331       | 98.81%  |
| No        | 4         | 1.19%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 273       | 81.01%  |
| No        | 64        | 18.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 80        | 23.74%  |
| Russia             | 25        | 7.42%   |
| Germany            | 18        | 5.34%   |
| Brazil             | 16        | 4.75%   |
| UK                 | 15        | 4.45%   |
| Canada             | 14        | 4.15%   |
| Poland             | 11        | 3.26%   |
| Italy              | 10        | 2.97%   |
| Australia          | 10        | 2.97%   |
| India              | 9         | 2.67%   |
| Bulgaria           | 9         | 2.67%   |
| Ukraine            | 8         | 2.37%   |
| Romania            | 8         | 2.37%   |
| Netherlands        | 8         | 2.37%   |
| Mexico             | 6         | 1.78%   |
| Spain              | 5         | 1.48%   |
| Turkey             | 4         | 1.19%   |
| South Africa       | 4         | 1.19%   |
| Portugal           | 4         | 1.19%   |
| Thailand           | 3         | 0.89%   |
| Norway             | 3         | 0.89%   |
| Hungary            | 3         | 0.89%   |
| Hong Kong          | 3         | 0.89%   |
| France             | 3         | 0.89%   |
| Belgium            | 3         | 0.89%   |
| Argentina          | 3         | 0.89%   |
| Vietnam            | 2         | 0.59%   |
| Uzbekistan         | 2         | 0.59%   |
| Switzerland        | 2         | 0.59%   |
| Saudi Arabia       | 2         | 0.59%   |
| Ireland            | 2         | 0.59%   |
| Indonesia          | 2         | 0.59%   |
| Estonia            | 2         | 0.59%   |
| Egypt              | 2         | 0.59%   |
| Denmark            | 2         | 0.59%   |
| Colombia           | 2         | 0.59%   |
| China              | 2         | 0.59%   |
| Chile              | 2         | 0.59%   |
| Bolivia            | 2         | 0.59%   |
| Sweden             | 1         | 0.3%    |
| Sri Lanka          | 1         | 0.3%    |
| Slovenia           | 1         | 0.3%    |
| Slovakia           | 1         | 0.3%    |
| Singapore          | 1         | 0.3%    |
| Serbia             | 1         | 0.3%    |
| Réunion           | 1         | 0.3%    |
| Philippines        | 1         | 0.3%    |
| Pakistan           | 1         | 0.3%    |
| Luxembourg         | 1         | 0.3%    |
| Lebanon            | 1         | 0.3%    |
| Kazakhstan         | 1         | 0.3%    |
| Israel             | 1         | 0.3%    |
| Iran               | 1         | 0.3%    |
| Georgia            | 1         | 0.3%    |
| French Polynesia   | 1         | 0.3%    |
| Finland            | 1         | 0.3%    |
| Eswatini           | 1         | 0.3%    |
| Dominican Republic | 1         | 0.3%    |
| Czechia            | 1         | 0.3%    |
| Cyprus             | 1         | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 8         | 2.27%   |
| Johannesburg      | 4         | 1.14%   |
| Berlin            | 4         | 1.14%   |
| Sydney            | 3         | 0.85%   |
| Sofia             | 3         | 0.85%   |
| Lisbon            | 3         | 0.85%   |
| Kyiv              | 3         | 0.85%   |
| Houston           | 3         | 0.85%   |
| Frankfurt am Main | 3         | 0.85%   |
| Warsaw            | 2         | 0.57%   |
| Varna             | 2         | 0.57%   |
| Torrance          | 2         | 0.57%   |
| Thunder Bay       | 2         | 0.57%   |
| Tashkent          | 2         | 0.57%   |
| Salvador          | 2         | 0.57%   |
| Rome              | 2         | 0.57%   |
| New Westminster   | 2         | 0.57%   |
| Nanjing           | 2         | 0.57%   |
| Mexico City       | 2         | 0.57%   |
| Madison           | 2         | 0.57%   |
| Kolkata           | 2         | 0.57%   |
| Hawthorn          | 2         | 0.57%   |
| Dublin            | 2         | 0.57%   |
| Denver            | 2         | 0.57%   |
| Curitiba          | 2         | 0.57%   |
| Cologne           | 2         | 0.57%   |
| Chennai           | 2         | 0.57%   |
| Cairo             | 2         | 0.57%   |
| Budapest          | 2         | 0.57%   |
| Bucharest         | 2         | 0.57%   |
| Brooklyn          | 2         | 0.57%   |
| Bangkok           | 2         | 0.57%   |
| Austin            | 2         | 0.57%   |
| Asenovgrad        | 2         | 0.57%   |
| Amsterdam         | 2         | 0.57%   |
| Zárate           | 1         | 0.28%   |
| Zurich            | 1         | 0.28%   |
| Zgorzelec         | 1         | 0.28%   |
| Zapopan           | 1         | 0.28%   |
| Zagaydarovka      | 1         | 0.28%   |
| Xieqiao           | 1         | 0.28%   |
| Xenia             | 1         | 0.28%   |
| Wroclaw           | 1         | 0.28%   |
| Woolloomooloo     | 1         | 0.28%   |
| Wilmington        | 1         | 0.28%   |
| Wigan             | 1         | 0.28%   |
| White Plains      | 1         | 0.28%   |
| Weston            | 1         | 0.28%   |
| West Covina       | 1         | 0.28%   |
| Voorburg          | 1         | 0.28%   |
| Vladivostok       | 1         | 0.28%   |
| Viljandi          | 1         | 0.28%   |
| Victoria          | 1         | 0.28%   |
| Valbrembo         | 1         | 0.28%   |
| Uster             | 1         | 0.28%   |
| Tychy             | 1         | 0.28%   |
| Turobin           | 1         | 0.28%   |
| Tulsa             | 1         | 0.28%   |
| Tula              | 1         | 0.28%   |
| Tuen Mun          | 1         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 70        | 100    | 16.79%  |
| Toshiba                   | 43        | 44     | 10.31%  |
| Seagate                   | 39        | 52     | 9.35%   |
| Unknown                   | 35        | 47     | 8.39%   |
| WDC                       | 31        | 36     | 7.43%   |
| Sandisk                   | 25        | 26     | 6%      |
| Kingston                  | 25        | 27     | 6%      |
| SK Hynix                  | 21        | 21     | 5.04%   |
| HGST                      | 15        | 19     | 3.6%    |
| Intel                     | 12        | 15     | 2.88%   |
| Hitachi                   | 12        | 15     | 2.88%   |
| Apple                     | 11        | 12     | 2.64%   |
| Crucial                   | 8         | 9      | 1.92%   |
| A-DATA Technology         | 7         | 9      | 1.68%   |
| Micron Technology         | 6         | 7      | 1.44%   |
| JMicron                   | 5         | 5      | 1.2%    |
| KingSpec                  | 4         | 4      | 0.96%   |
| FORESEE                   | 4         | 4      | 0.96%   |
| Transcend                 | 3         | 3      | 0.72%   |
| SPCC                      | 3         | 3      | 0.72%   |
| Silicon Motion            | 3         | 3      | 0.72%   |
| LITEONIT                  | 2         | 7      | 0.48%   |
| LITEON                    | 2         | 3      | 0.48%   |
| KIOXIA                    | 2         | 5      | 0.48%   |
| Hewlett-Packard           | 2         | 2      | 0.48%   |
| Fujitsu                   | 2         | 3      | 0.48%   |
| XrayDisk                  | 1         | 1      | 0.24%   |
| WDC WDS1                  | 1         | 1      | 0.24%   |
| W800S                     | 1         | 1      | 0.24%   |
| Team                      | 1         | 1      | 0.24%   |
| SSK                       | 1         | 1      | 0.24%   |
| SABRENT                   | 1         | 1      | 0.24%   |
| PNY                       | 1         | 1      | 0.24%   |
| PLEXTOR                   | 1         | 1      | 0.24%   |
| Phison                    | 1         | 1      | 0.24%   |
| Patriot                   | 1         | 1      | 0.24%   |
| OWC                       | 1         | 2      | 0.24%   |
| OCZ                       | 1         | 1      | 0.24%   |
| Netac                     | 1         | 1      | 0.24%   |
| MyDigitalSSD              | 1         | 2      | 0.24%   |
| Micron/Crucial Technology | 1         | 1      | 0.24%   |
| Leven                     | 1         | 1      | 0.24%   |
| KingDian                  | 1         | 1      | 0.24%   |
| Integral                  | 1         | 1      | 0.24%   |
| HUAWEI                    | 1         | 1      | 0.24%   |
| Hikvision                 | 1         | 1      | 0.24%   |
| Corsair                   | 1         | 1      | 0.24%   |
| China                     | 1         | 1      | 0.24%   |
| BIWIN                     | 1         | 1      | 0.24%   |
| Apacer                    | 1         | 1      | 0.24%   |
| ADATA Technology          | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 16        | 3.72%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 11        | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB         | 9         | 2.09%   |
| Toshiba MQ01ABF050 500GB               | 7         | 1.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 7         | 1.63%   |
| HGST HTS721010A9E630 1TB               | 7         | 1.63%   |
| Unknown MMC Card  64GB                 | 6         | 1.4%    |
| Toshiba NVMe SSD Drive 512GB           | 6         | 1.4%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 6         | 1.4%    |
| Samsung NVMe SSD Drive 1024GB          | 6         | 1.4%    |
| Intel NVMe SSD Drive 512GB             | 6         | 1.4%    |
| Toshiba MQ01ABD100 1TB                 | 5         | 1.16%   |
| Sandisk NVMe SSD Drive 512GB           | 5         | 1.16%   |
| Samsung SSD 850 EVO 250GB              | 5         | 1.16%   |
| Kingston SA400S37240G 240GB SSD        | 5         | 1.16%   |
| Unknown MMC Card  128GB                | 4         | 0.93%   |
| SK Hynix NVMe SSD Drive 512GB          | 4         | 0.93%   |
| SK Hynix NVMe SSD Drive 256GB          | 4         | 0.93%   |
| Seagate ST500LT012-1DG142 500GB        | 4         | 0.93%   |
| Sandisk NVMe SSD Drive 256GB           | 4         | 0.93%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 0.93%   |
| Samsung NVMe SSD Drive 500GB           | 4         | 0.93%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD    | 4         | 0.93%   |
| JMicron Tech 250GB                     | 4         | 0.93%   |
| Toshiba MQ04ABF100 1TB                 | 3         | 0.7%    |
| SK Hynix SC311 SATA 256GB SSD          | 3         | 0.7%    |
| Samsung SSD 860 EVO 500GB              | 3         | 0.7%    |
| Hitachi HTS545050B9A300 500GB          | 3         | 0.7%    |
| HGST HTS725050A7E630 500GB             | 3         | 0.7%    |
| FORESEE 256GB SSD                      | 3         | 0.7%    |
| Apple SSD SM512E 500GB                 | 3         | 0.7%    |
| Apple SSD SM0512G 500GB                | 3         | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 0.47%   |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 0.47%   |
| WDC WD10SPZX-17Z10T1 1TB               | 2         | 0.47%   |
| WDC WD10JPVX-60JC3T0 1TB               | 2         | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.47%   |
| Unknown SD/MMC/MS PRO 4GB              | 2         | 0.47%   |
| Unknown MMC Card  16GB                 | 2         | 0.47%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD  | 2         | 0.47%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD  | 2         | 0.47%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 2         | 0.47%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 0.47%   |
| Seagate ST1000LM014-1EJ164 1TB         | 2         | 0.47%   |
| SanDisk SSD PLUS 240GB                 | 2         | 0.47%   |
| Samsung SSD 860 EVO 250GB              | 2         | 0.47%   |
| Samsung SSD 850 PRO 512GB              | 2         | 0.47%   |
| Samsung SSD 850 PRO 256GB              | 2         | 0.47%   |
| Samsung SSD 850 EVO M.2 500GB          | 2         | 0.47%   |
| Samsung SSD 850 EVO 500GB              | 2         | 0.47%   |
| Samsung MZNLN256HCHP-00000 256GB SSD   | 2         | 0.47%   |
| Kingston SV300S37A120G 120GB SSD       | 2         | 0.47%   |
| Kingston SA400S37480G 480GB SSD        | 2         | 0.47%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 0.47%   |
| Kingston NVMe SSD Drive 256GB          | 2         | 0.47%   |
| Kingston NVMe SSD Drive 128GB          | 2         | 0.47%   |
| KingSpec NT-128 128GB                  | 2         | 0.47%   |
| Intel NVMe SSD Drive 1024GB            | 2         | 0.47%   |
| Hitachi HTS545025B9A300 250GB          | 2         | 0.47%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 51     | 32.48%  |
| WDC                 | 23        | 25     | 19.66%  |
| Toshiba             | 22        | 22     | 18.8%   |
| HGST                | 15        | 19     | 12.82%  |
| Hitachi             | 12        | 15     | 10.26%  |
| Unknown             | 2         | 2      | 1.71%   |
| Fujitsu             | 2         | 3      | 1.71%   |
| Samsung Electronics | 1         | 1      | 0.85%   |
| SABRENT             | 1         | 1      | 0.85%   |
| Apple               | 1         | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 67     | 26.14%  |
| Kingston            | 19        | 19     | 10.8%   |
| SanDisk             | 14        | 15     | 7.95%   |
| SK Hynix            | 12        | 12     | 6.82%   |
| WDC                 | 9         | 11     | 5.11%   |
| Apple               | 9         | 10     | 5.11%   |
| Crucial             | 8         | 9      | 4.55%   |
| A-DATA Technology   | 7         | 9      | 3.98%   |
| Toshiba             | 6         | 7      | 3.41%   |
| Micron Technology   | 5         | 6      | 2.84%   |
| KingSpec            | 4         | 4      | 2.27%   |
| FORESEE             | 4         | 4      | 2.27%   |
| Transcend           | 3         | 3      | 1.7%    |
| SPCC                | 3         | 3      | 1.7%    |
| Intel               | 3         | 3      | 1.7%    |
| LITEONIT            | 2         | 7      | 1.14%   |
| LITEON              | 2         | 3      | 1.14%   |
| Hewlett-Packard     | 2         | 2      | 1.14%   |
| WDC WDS1            | 1         | 1      | 0.57%   |
| W800S               | 1         | 1      | 0.57%   |
| Team                | 1         | 1      | 0.57%   |
| PNY                 | 1         | 1      | 0.57%   |
| PLEXTOR             | 1         | 1      | 0.57%   |
| Patriot             | 1         | 1      | 0.57%   |
| OCZ                 | 1         | 1      | 0.57%   |
| Netac               | 1         | 1      | 0.57%   |
| MyDigitalSSD        | 1         | 2      | 0.57%   |
| Leven               | 1         | 1      | 0.57%   |
| KingDian            | 1         | 1      | 0.57%   |
| JMicron             | 1         | 1      | 0.57%   |
| Integral            | 1         | 1      | 0.57%   |
| Hikvision           | 1         | 1      | 0.57%   |
| Corsair             | 1         | 1      | 0.57%   |
| China               | 1         | 1      | 0.57%   |
| BIWIN               | 1         | 1      | 0.57%   |
| Apacer              | 1         | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 165       | 213    | 40.44%  |
| HDD     | 115       | 140    | 28.19%  |
| NVMe    | 86        | 101    | 21.08%  |
| MMC     | 32        | 43     | 7.84%   |
| Unknown | 10        | 11     | 2.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 253       | 349    | 65.71%  |
| NVMe | 86        | 101    | 22.34%  |
| MMC  | 32        | 43     | 8.31%   |
| SAS  | 14        | 15     | 3.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 195       | 242    | 70.4%   |
| 0.51-1.0   | 72        | 100    | 25.99%  |
| 1.01-2.0   | 10        | 11     | 3.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 138       | 40.12%  |
| 251-500        | 69        | 20.06%  |
| 501-1000       | 39        | 11.34%  |
| 21-50          | 30        | 8.72%   |
| 51-100         | 29        | 8.43%   |
| Unknown        | 24        | 6.98%   |
| 1001-2000      | 11        | 3.2%    |
| 1-20           | 3         | 0.87%   |
| More than 3000 | 1         | 0.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 192       | 54.08%  |
| 21-50     | 77        | 21.69%  |
| 51-100    | 27        | 7.61%   |
| Unknown   | 24        | 6.76%   |
| 101-250   | 22        | 6.2%    |
| 251-500   | 8         | 2.25%   |
| 501-1000  | 4         | 1.13%   |
| 1001-2000 | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Fujitsu MHZ2250BH G1 250GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Fujitsu | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Fujitsu | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 328       | 500    | 98.2%   |
| Works    | 5         | 7      | 1.5%    |
| Malfunc  | 1         | 1      | 0.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 264       | 70.59%  |
| Samsung Electronics          | 35        | 9.36%   |
| AMD                          | 22        | 5.88%   |
| Toshiba America Info Systems | 15        | 4.01%   |
| Sandisk                      | 11        | 2.94%   |
| SK Hynix                     | 9         | 2.41%   |
| Kingston Technology Company  | 6         | 1.6%    |
| Silicon Motion               | 3         | 0.8%    |
| KIOXIA                       | 2         | 0.53%   |
| ASMedia Technology           | 2         | 0.53%   |
| Shenzhen Longsys Electronics | 1         | 0.27%   |
| Micron/Crucial Technology    | 1         | 0.27%   |
| Micron Technology            | 1         | 0.27%   |
| Apple                        | 1         | 0.27%   |
| ADATA Technology             | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 39        | 10.08%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 34        | 8.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 26        | 6.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 22        | 5.68%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 22        | 5.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 20        | 5.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 19        | 4.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 18        | 4.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 17        | 4.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 17        | 4.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 11        | 2.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 2.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 10        | 2.58%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 8         | 2.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 7         | 1.81%   |
| Intel SSD 660P Series                                                                  | 6         | 1.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 5         | 1.29%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 5         | 1.29%   |
| Samsung Electronics SATA controller                                                    | 5         | 1.29%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.29%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 4         | 1.03%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                            | 4         | 1.03%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 4         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 1.03%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 0.78%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 3         | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 3         | 0.78%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 2         | 0.52%   |
| SK Hynix Non-Volatile memory controller                                                | 2         | 0.52%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 2         | 0.52%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 0.52%   |
| Sandisk PC SN520 NVMe SSD                                                              | 2         | 0.52%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 0.52%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.52%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 2         | 0.52%   |
| Intel SATA Controller [RAID mode]                                                      | 2         | 0.52%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.52%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.52%   |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 0.26%   |
| SK Hynix PC300 NVMe Solid State Drive 256GB                                            | 1         | 0.26%   |
| SK Hynix PC300 NVMe Solid State Drive 1TB                                              | 1         | 0.26%   |
| SK Hynix Gold P31 SSD                                                                  | 1         | 0.26%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.26%   |
| Shenzhen Longsys Non-Volatile memory controller                                        | 1         | 0.26%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 1         | 0.26%   |
| Sandisk Non-Volatile memory controller                                                 | 1         | 0.26%   |
| Samsung XP941 PCIe SSD                                                                 | 1         | 0.26%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 0.26%   |
| Micron Non-Volatile memory controller                                                  | 1         | 0.26%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.26%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 0.26%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 0.26%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 0.26%   |
| Intel Non-Volatile memory controller                                                   | 1         | 0.26%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 0.26%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.26%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                  | 1         | 0.26%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.26%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.26%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 258       | 67.54%  |
| NVMe | 88        | 23.04%  |
| RAID | 29        | 7.59%   |
| IDE  | 7         | 1.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 307       | 91.92%  |
| AMD    | 27        | 8.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 4.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 2.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 2.99%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 2.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 2.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 2.1%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 2.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 1.8%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 1.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 1.8%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 1.8%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 5         | 1.5%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 1.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 1.5%    |
| Intel Core i5-3317U CPU @ 1.70GHz             | 5         | 1.5%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 1.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.2%    |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 4         | 1.2%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 1.2%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 4         | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.2%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.9%    |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 3         | 0.9%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.9%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.9%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.9%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.9%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 3         | 0.9%    |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 0.9%    |
| Intel Celeron CPU 3215U @ 1.70GHz             | 3         | 0.9%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.9%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 0.9%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.6%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.6%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 2         | 0.6%    |
| Intel Core i7-3667U CPU @ 2.00GHz             | 2         | 0.6%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.6%    |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 2         | 0.6%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.6%    |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 0.6%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.6%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.6%    |
| Intel Core i5-2435M CPU @ 2.40GHz             | 2         | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.6%    |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.6%    |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.6%    |
| Intel Core i3-6100U CPU @ 2.30GHz             | 2         | 0.6%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 112       | 33.53%  |
| Intel Core i7        | 105       | 31.44%  |
| Intel Celeron        | 34        | 10.18%  |
| Intel Core i3        | 25        | 7.49%   |
| Intel Pentium        | 13        | 3.89%   |
| AMD Ryzen 5          | 9         | 2.69%   |
| Other                | 5         | 1.5%    |
| Intel Pentium Silver | 5         | 1.5%    |
| AMD Ryzen 3          | 5         | 1.5%    |
| AMD A8               | 5         | 1.5%    |
| Intel Atom           | 4         | 1.2%    |
| Intel Core i9        | 2         | 0.6%    |
| AMD Ryzen 7          | 2         | 0.6%    |
| AMD A6               | 2         | 0.6%    |
| Intel Xeon           | 1         | 0.3%    |
| Intel Core m5        | 1         | 0.3%    |
| AMD E1               | 1         | 0.3%    |
| AMD A4               | 1         | 0.3%    |
| AMD A12              | 1         | 0.3%    |
| AMD A10              | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 170       | 50.9%   |
| 4      | 140       | 41.92%  |
| 6      | 21        | 6.29%   |
| 8      | 3         | 0.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 334       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 260       | 77.84%  |
| 1      | 74        | 22.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 289       | 85.5%   |
| Unknown        | 49        | 14.5%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 306       | 91.34%  |
| 0x40651 | 5         | 1.49%   |
| 0x806ea | 4         | 1.19%   |
| 0x306a9 | 4         | 1.19%   |
| 0x906ea | 3         | 0.9%    |
| 0x706a1 | 3         | 0.9%    |
| 0x306d4 | 2         | 0.6%    |
| 0x906e9 | 1         | 0.3%    |
| 0x806eb | 1         | 0.3%    |
| 0x806e9 | 1         | 0.3%    |
| 0x506e3 | 1         | 0.3%    |
| 0x506c9 | 1         | 0.3%    |
| 0x406c3 | 1         | 0.3%    |
| 0x40671 | 1         | 0.3%    |
| 0x306c3 | 1         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 92        | 27.54%  |
| IvyBridge     | 38        | 11.38%  |
| Haswell       | 38        | 11.38%  |
| Skylake       | 27        | 8.08%   |
| SandyBridge   | 27        | 8.08%   |
| Broadwell     | 23        | 6.89%   |
| Silvermont    | 18        | 5.39%   |
| Goldmont plus | 14        | 4.19%   |
| Goldmont      | 12        | 3.59%   |
| Zen+          | 11        | 3.29%   |
| Westmere      | 6         | 1.8%    |
| TigerLake     | 4         | 1.2%    |
| Puma          | 4         | 1.2%    |
| IceLake       | 4         | 1.2%    |
| Excavator     | 4         | 1.2%    |
| Zen           | 3         | 0.9%    |
| CometLake     | 3         | 0.9%    |
| Zen 2         | 2         | 0.6%    |
| Piledriver    | 2         | 0.6%    |
| Jaguar        | 1         | 0.3%    |
| Unknown       | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 294       | 63.91%  |
| Nvidia | 111       | 24.13%  |
| AMD    | 55        | 11.96%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 35        | 7.54%   |
| Intel UHD Graphics 620                                                                   | 24        | 5.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 5.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 4.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 22        | 4.74%   |
| Intel HD Graphics 5500                                                                   | 17        | 3.66%   |
| Intel HD Graphics 630                                                                    | 15        | 3.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 2.37%   |
| Intel HD Graphics 530                                                                    | 11        | 2.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 2.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 2.37%   |
| Intel HD Graphics 620                                                                    | 10        | 2.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 2.16%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 1.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 7         | 1.51%   |
| Intel HD Graphics 500                                                                    | 7         | 1.51%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 1.51%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.29%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 1.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 5         | 1.08%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.86%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 0.86%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.86%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.86%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.86%   |
| Intel HD Graphics                                                                        | 4         | 0.86%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 3         | 0.65%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 3         | 0.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.65%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 3         | 0.65%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.65%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.43%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.43%   |
| Nvidia GM204M [GeForce GTX 980M]                                                         | 2         | 0.43%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.43%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.43%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.43%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 2         | 0.43%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.43%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.43%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.43%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.43%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.43%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 0.43%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.43%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.43%   |
| AMD Renoir                                                                               | 2         | 0.43%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 2         | 0.43%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 171       | 50.89%  |
| Intel + Nvidia | 101       | 30.06%  |
| 1 x AMD        | 27        | 8.04%   |
| Intel + AMD    | 22        | 6.55%   |
| 1 x Nvidia     | 8         | 2.38%   |
| 2 x AMD        | 4         | 1.19%   |
| AMD + Nvidia   | 2         | 0.6%    |
| Other          | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 328       | 98.2%   |
| Proprietary | 6         | 1.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 324       | 96.72%  |
| 3.01-4.0   | 3         | 0.9%    |
| 0.51-1.0   | 3         | 0.9%    |
| 5.01-6.0   | 2         | 0.6%    |
| 7.01-8.0   | 1         | 0.3%    |
| 2.01-3.0   | 1         | 0.3%    |
| 1.01-2.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 74        | 20.16%  |
| LG Display              | 57        | 15.53%  |
| BOE                     | 55        | 14.99%  |
| Chimei Innolux          | 51        | 13.9%   |
| Samsung Electronics     | 30        | 8.17%   |
| Sharp                   | 19        | 5.18%   |
| Apple                   | 16        | 4.36%   |
| PANDA                   | 14        | 3.81%   |
| Dell                    | 9         | 2.45%   |
| Chi Mei Optoelectronics | 7         | 1.91%   |
| Goldstar                | 5         | 1.36%   |
| Lenovo                  | 4         | 1.09%   |
| InfoVision              | 3         | 0.82%   |
| Acer                    | 3         | 0.82%   |
| Panasonic               | 2         | 0.54%   |
| BenQ                    | 2         | 0.54%   |
| AOC                     | 2         | 0.54%   |
| Vizio                   | 1         | 0.27%   |
| Toshiba                 | 1         | 0.27%   |
| SDC                     | 1         | 0.27%   |
| Philips                 | 1         | 0.27%   |
| MSI                     | 1         | 0.27%   |
| MiTAC                   | 1         | 0.27%   |
| JXC                     | 1         | 0.27%   |
| JRY                     | 1         | 0.27%   |
| ITE                     | 1         | 0.27%   |
| Iiyama                  | 1         | 0.27%   |
| Hewlett-Packard         | 1         | 0.27%   |
| CYX                     | 1         | 0.27%   |
| CSO                     | 1         | 0.27%   |
| Ancor Communications    | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 1.63%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 5         | 1.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 1.09%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 4         | 1.09%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.09%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                    | 4         | 1.09%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 3         | 0.82%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch    | 3         | 0.82%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 3         | 0.82%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.82%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 3         | 0.82%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 3         | 0.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 3         | 0.82%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 3         | 0.82%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 0.82%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 310x170mm 13.9-inch            | 3         | 0.82%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch            | 3         | 0.82%   |
| Apple Color LCD APPA00E 2880x1800 331x207mm 15.4-inch                    | 3         | 0.82%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.54%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 2         | 0.54%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 2         | 0.54%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.54%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                  | 2         | 0.54%   |
| Sharp LCD Monitor SHP1420 1920x1080 290x170mm 13.2-inch                  | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch     | 2         | 0.54%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 2         | 0.54%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 2         | 0.54%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 2         | 0.54%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.54%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.54%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 0.54%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.54%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 2         | 0.54%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x164mm 13.2-inch              | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 340x190mm 15.3-inch         | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 340x190mm 15.3-inch          | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1375 1920x1080 293x165mm 13.2-inch         | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 2         | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.54%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                    | 2         | 0.54%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 2         | 0.54%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 2         | 0.54%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 2         | 0.54%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 0.54%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.54%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 0.54%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.54%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 2         | 0.54%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch            | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO439D 1920x1080 382x215mm 17.3-inch           | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO31EC 1366x768 344x193mm 15.5-inch            | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 2         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 165       | 46.48%  |
| 1366x768 (WXGA)    | 116       | 32.68%  |
| 3840x2160 (4K)     | 19        | 5.35%   |
| 1600x900 (HD+)     | 17        | 4.79%   |
| 2880x1800          | 7         | 1.97%   |
| 1280x800 (WXGA)    | 6         | 1.69%   |
| 3200x1800 (QHD+)   | 4         | 1.13%   |
| 2560x1600          | 4         | 1.13%   |
| 3840x1080          | 2         | 0.56%   |
| 2560x1440 (QHD)    | 2         | 0.56%   |
| 2160x1440          | 2         | 0.56%   |
| 1680x1050 (WSXGA+) | 2         | 0.56%   |
| 1440x900 (WXGA+)   | 2         | 0.56%   |
| 1280x1024 (SXGA)   | 2         | 0.56%   |
| 3840x1100          | 1         | 0.28%   |
| 3440x1440          | 1         | 0.28%   |
| 2736x1824          | 1         | 0.28%   |
| 2560x1080          | 1         | 0.28%   |
| 1920x1200 (WUXGA)  | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 172       | 46.87%  |
| 13      | 63        | 17.17%  |
| 14      | 36        | 9.81%   |
| 17      | 23        | 6.27%   |
| 11      | 16        | 4.36%   |
| 12      | 10        | 2.72%   |
| 27      | 9         | 2.45%   |
| 24      | 6         | 1.63%   |
| 23      | 5         | 1.36%   |
| 21      | 5         | 1.36%   |
| 18      | 5         | 1.36%   |
| 31      | 3         | 0.82%   |
| 34      | 2         | 0.54%   |
| 16      | 2         | 0.54%   |
| 84      | 1         | 0.27%   |
| 52      | 1         | 0.27%   |
| 49      | 1         | 0.27%   |
| 48      | 1         | 0.27%   |
| 40      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 22      | 1         | 0.27%   |
| 20      | 1         | 0.27%   |
| 10      | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 232       | 63.56%  |
| 201-300     | 66        | 18.08%  |
| 351-400     | 23        | 6.3%    |
| 501-600     | 20        | 5.48%   |
| 401-500     | 12        | 3.29%   |
| 601-700     | 4         | 1.1%    |
| 1001-1500   | 3         | 0.82%   |
| 701-800     | 2         | 0.55%   |
| 801-900     | 1         | 0.27%   |
| 1501-2000   | 1         | 0.27%   |
| Unknown     | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 306       | 90.53%  |
| 16/10   | 21        | 6.21%   |
| 3/2     | 3         | 0.89%   |
| 32/9    | 2         | 0.59%   |
| 21/9    | 2         | 0.59%   |
| 5/4     | 1         | 0.3%    |
| 4/3     | 1         | 0.3%    |
| 3.40    | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 172       | 46.99%  |
| 81-90          | 64        | 17.49%  |
| 71-80          | 34        | 9.29%   |
| 121-130        | 22        | 6.01%   |
| 51-60          | 17        | 4.64%   |
| 201-250        | 15        | 4.1%    |
| 61-70          | 10        | 2.73%   |
| 301-350        | 10        | 2.73%   |
| 141-150        | 6         | 1.64%   |
| 351-500        | 5         | 1.37%   |
| 501-1000       | 3         | 0.82%   |
| More than 1000 | 2         | 0.55%   |
| 151-200        | 2         | 0.55%   |
| 111-120        | 2         | 0.55%   |
| 41-50          | 1         | 0.27%   |
| Unknown        | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 155       | 42.7%   |
| 101-120       | 113       | 31.13%  |
| 161-240       | 38        | 10.47%  |
| 51-100        | 36        | 9.92%   |
| More than 240 | 19        | 5.23%   |
| 1-50          | 1         | 0.28%   |
| Unknown       | 1         | 0.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 299       | 88.99%  |
| 2     | 36        | 10.71%  |
| 3     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 174       | 33.66%  |
| Intel                             | 168       | 32.5%   |
| Qualcomm Atheros                  | 97        | 18.76%  |
| Broadcom                          | 31        | 6%      |
| Broadcom Limited                  | 13        | 2.51%   |
| Ralink Technology                 | 5         | 0.97%   |
| ASUSTek Computer                  | 4         | 0.77%   |
| TP-Link                           | 3         | 0.58%   |
| Ralink                            | 3         | 0.58%   |
| Motorola PCS                      | 3         | 0.58%   |
| Dell                              | 3         | 0.58%   |
| Hewlett-Packard                   | 2         | 0.39%   |
| ASIX Electronics                  | 2         | 0.39%   |
| QinHeng Electronics               | 1         | 0.19%   |
| Marvell Technology Group          | 1         | 0.19%   |
| JMicron Technology                | 1         | 0.19%   |
| ICS Advent                        | 1         | 0.19%   |
| Huawei Technologies               | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |
| DisplayLink                       | 1         | 0.19%   |
| AVM                               | 1         | 0.19%   |
| Apple                             | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 104       | 16.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 6.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 3.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 21        | 3.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.45%   |
| Intel Wireless 7260                                               | 14        | 2.29%   |
| Intel Wireless 3165                                               | 13        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 1.96%   |
| Intel Wireless 7265                                               | 12        | 1.96%   |
| Intel Wireless 8260                                               | 11        | 1.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 1.63%   |
| Intel Wireless 8265 / 8275                                        | 10        | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 1.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 9         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 1.31%   |
| Intel Wireless 3160                                               | 8         | 1.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.31%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 0.98%   |
| Intel Centrino Advanced-N 6235                                    | 6         | 0.98%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.98%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.82%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 5         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.65%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 0.65%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 4         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.49%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.49%   |
| Motorola PCS motorola razr                                        | 3         | 0.49%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.49%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.49%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.49%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.49%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 3         | 0.49%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 3         | 0.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2         | 0.33%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.33%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 159       | 45.56%  |
| Qualcomm Atheros      | 84        | 24.07%  |
| Realtek Semiconductor | 50        | 14.33%  |
| Broadcom              | 26        | 7.45%   |
| Broadcom Limited      | 11        | 3.15%   |
| Ralink Technology     | 5         | 1.43%   |
| ASUSTek Computer      | 4         | 1.15%   |
| TP-Link               | 3         | 0.86%   |
| Ralink                | 3         | 0.86%   |
| Dell                  | 3         | 0.86%   |
| AVM                   | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 23        | 6.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 21        | 5.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 17        | 4.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 15        | 4.25%   |
| Intel Wireless 7260                                              | 14        | 3.97%   |
| Intel Wireless 3165                                              | 13        | 3.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 12        | 3.4%    |
| Intel Wireless 7265                                              | 12        | 3.4%    |
| Intel Wireless 8260                                              | 11        | 3.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 10        | 2.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 10        | 2.83%   |
| Intel Wireless 8265 / 8275                                       | 10        | 2.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 10        | 2.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                 | 9         | 2.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 8         | 2.27%   |
| Intel Wireless 3160                                              | 8         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                | 8         | 2.27%   |
| Intel Wi-Fi 6 AX200                                              | 7         | 1.98%   |
| Broadcom BCM43142 802.11b/g/n                                    | 7         | 1.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                  | 6         | 1.7%    |
| Intel Centrino Advanced-N 6235                                   | 6         | 1.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                   | 6         | 1.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 5         | 1.42%   |
| Intel Gemini Lake PCH CNVi WiFi                                  | 5         | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 5         | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                         | 5         | 1.42%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 5         | 1.42%   |
| Broadcom BCM43224 802.11a/b/g/n                                  | 4         | 1.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter         | 3         | 0.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                       | 3         | 0.85%   |
| Intel Wi-Fi 6 AX201                                              | 3         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 3         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 3         | 0.85%   |
| Intel Centrino Wireless-N 2230                                   | 3         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 0.85%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                           | 3         | 0.85%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                          | 3         | 0.85%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                  | 2         | 0.57%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                       | 2         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 2         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 0.57%   |
| Realtek 802.11n WLAN Adapter                                     | 2         | 0.57%   |
| Ralink RT5372 Wireless Adapter                                   | 2         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)   | 2         | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 2         | 0.57%   |
| Intel Wireless-AC 9260                                           | 2         | 0.57%   |
| Intel Centrino Wireless-N 130                                    | 2         | 0.57%   |
| Broadcom Limited BCM43142 802.11b/g/n                            | 2         | 0.57%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter      | 2         | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter              | 2         | 0.57%   |
| ASUS 802.11ac NIC                                                | 2         | 0.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                     | 1         | 0.28%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                              | 1         | 0.28%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]       | 1         | 0.28%   |
| Realtek RTL8723DE Wireless Network Adapter                       | 1         | 0.28%   |
| Ralink RT5572 Wireless Adapter                                   | 1         | 0.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                            | 1         | 0.28%   |
| Ralink MT7601U Wireless Adapter                                  | 1         | 0.28%   |
| Ralink RT5392 PCIe Wireless Network Adapter                      | 1         | 0.28%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 0.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 153       | 61.2%   |
| Intel                    | 50        | 20%     |
| Qualcomm Atheros         | 24        | 9.6%    |
| Broadcom                 | 13        | 5.2%    |
| Broadcom Limited         | 2         | 0.8%    |
| ASIX Electronics         | 2         | 0.8%    |
| QinHeng Electronics      | 1         | 0.4%    |
| Marvell Technology Group | 1         | 0.4%    |
| JMicron Technology       | 1         | 0.4%    |
| ICS Advent               | 1         | 0.4%    |
| DisplayLink              | 1         | 0.4%    |
| Apple                    | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 104       | 41.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 40        | 15.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 5.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 3.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.98%   |
| Intel Ethernet Connection I218-LM                                              | 5         | 1.98%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.98%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.98%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 4         | 1.59%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 4         | 1.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 1.19%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 1.19%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.19%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 3         | 1.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.79%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.79%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.79%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.79%   |
| QinHeng CH9200 USB Ethernet Adapter                                            | 1         | 0.4%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.4%    |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.4%    |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.4%    |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.4%    |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.4%    |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.4%    |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.4%    |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 0.4%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.4%    |
| DisplayLink USB-C Triple-4K Dock                                               | 1         | 0.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.4%    |
| ASIX AX88772B Fast Ethernet Controller                                         | 1         | 0.4%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.4%    |
| Apple Ethernet Adapter [A1277]                                                 | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 331       | 56.58%  |
| Ethernet | 247       | 42.22%  |
| Modem    | 4         | 0.68%   |
| Unknown  | 3         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 316       | 56.63%  |
| Ethernet | 242       | 43.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 232       | 69.25%  |
| 1     | 94        | 28.06%  |
| 0     | 7         | 2.09%   |
| 3     | 2         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 308       | 91.67%  |
| Yes  | 28        | 8.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 132       | 47.83%  |
| Qualcomm Atheros Communications | 44        | 15.94%  |
| Realtek Semiconductor           | 30        | 10.87%  |
| Apple                           | 15        | 5.43%   |
| Lite-On Technology              | 12        | 4.35%   |
| Foxconn / Hon Hai               | 10        | 3.62%   |
| Broadcom                        | 10        | 3.62%   |
| IMC Networks                    | 9         | 3.26%   |
| Realtek                         | 3         | 1.09%   |
| Cambridge Silicon Radio         | 3         | 1.09%   |
| Hewlett-Packard                 | 2         | 0.72%   |
| Foxconn International           | 2         | 0.72%   |
| Toshiba                         | 1         | 0.36%   |
| Ralink                          | 1         | 0.36%   |
| Dell                            | 1         | 0.36%   |
| Alps Electric                   | 1         | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 68        | 24.64%  |
| Intel Bluetooth Device                                                              | 46        | 16.67%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 32        | 11.59%  |
| Realtek Bluetooth Radio                                                             | 12        | 4.35%   |
| Apple Bluetooth Host Controller                                                     | 12        | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 9         | 3.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 2.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 7         | 2.54%   |
| Intel AX200 Bluetooth                                                               | 7         | 2.54%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 2.17%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.81%   |
| Realtek 802.11ac WLAN Adapter                                                       | 4         | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.45%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.45%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.45%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.09%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 1.09%   |
| Broadcom BCM20702A0                                                                 | 3         | 1.09%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.09%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.72%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.72%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.72%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.72%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.72%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.72%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.72%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 0.72%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.36%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.36%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.36%   |
| Realtek 802.11n WLAN Adapter                                                        | 1         | 0.36%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.36%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.36%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.36%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.36%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.36%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.36%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                                     | 1         | 0.36%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.36%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.36%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.36%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.36%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 302       | 78.24%  |
| Nvidia                | 41        | 10.62%  |
| AMD                   | 35        | 9.07%   |
| Logitech              | 2         | 0.52%   |
| SteelSeries ApS       | 1         | 0.26%   |
| Realtek Semiconductor | 1         | 0.26%   |
| Plantronics           | 1         | 0.26%   |
| C-Media Electronics   | 1         | 0.26%   |
| Barco Display Systems | 1         | 0.26%   |
| Apple                 | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 48        | 10.28%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 43        | 9.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 23        | 4.93%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 4.93%   |
| Intel 8 Series HD Audio Controller                                                                | 23        | 4.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 22        | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 4.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 4.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 3.43%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 16        | 3.43%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 3.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 3%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 13        | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 2.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 12        | 2.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 2.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 2.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.5%    |
| AMD FCH Azalia Controller                                                                         | 7         | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.07%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 1.07%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 1.07%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.64%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.43%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.43%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.43%   |
| SteelSeries ApS SteelSeries Arctis 5                                                              | 1         | 0.21%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.21%   |
| Plantronics BT600                                                                                 | 1         | 0.21%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.21%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.21%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.21%   |
| Nvidia Audio device                                                                               | 1         | 0.21%   |
| Logitech Headset H390                                                                             | 1         | 0.21%   |
| Logitech G430 Surround Sound Gaming Headset                                                       | 1         | 0.21%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.21%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.21%   |
| C-Media Electronics TONOR TC-777 Audio Device                                                     | 1         | 0.21%   |
| Barco Display Systems USB02                                                                       | 1         | 0.21%   |
| Apple Audio Device                                                                                | 1         | 0.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 0.21%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.21%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 5         | 55.56%  |
| Samsung Electronics | 2         | 22.22%  |
| Unknown             | 1         | 11.11%  |
| Crucial             | 1         | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                  | 1         | 11.11%  |
| SK Hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 11.11%  |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s       | 1         | 11.11%  |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s      | 1         | 11.11%  |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s       | 1         | 11.11%  |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s       | 1         | 11.11%  |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s           | 1         | 11.11%  |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 11.11%  |
| Crucial RAM BLS16G4S26BFSD.16FD 16GB SODIMM DDR4 2667MT/s       | 1         | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 5         | 62.5%   |
| DDR3   | 2         | 25%     |
| LPDDR3 | 1         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 7         | 87.5%   |
| Row Of Chips | 1         | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 4         | 50%     |
| 16384 | 2         | 25%     |
| 4096  | 2         | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 4         | 44.44%  |
| 2400  | 2         | 22.22%  |
| 1600  | 2         | 22.22%  |
| 2133  | 1         | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 3         | 60%     |
| Kyocera     | 1         | 20%     |
| Canon       | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Seiko Epson L222 Series   | 2         | 40%     |
| Seiko Epson L355 Series   | 1         | 20%     |
| Kyocera FS-1030D printer  | 1         | 20%     |
| Canon PIXMA MG2500 Series | 1         | 20%     |

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
| Chicony Electronics                    | 72        | 23.76%  |
| Microdia                               | 32        | 10.56%  |
| IMC Networks                           | 29        | 9.57%   |
| Acer                                   | 29        | 9.57%   |
| Realtek Semiconductor                  | 28        | 9.24%   |
| Sunplus Innovation Technology          | 19        | 6.27%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.62%   |
| Quanta                                 | 12        | 3.96%   |
| Apple                                  | 12        | 3.96%   |
| Suyin                                  | 10        | 3.3%    |
| Silicon Motion                         | 10        | 3.3%    |
| Alcor Micro                            | 8         | 2.64%   |
| Syntek                                 | 6         | 1.98%   |
| Lite-On Technology                     | 5         | 1.65%   |
| Samsung Electronics                    | 2         | 0.66%   |
| Ricoh                                  | 2         | 0.66%   |
| Luxvisions Innotech Limited            | 2         | 0.66%   |
| Z-Star Microelectronics                | 1         | 0.33%   |
| YGTek                                  | 1         | 0.33%   |
| Unknown                                | 1         | 0.33%   |
| Spreadtrum Communications              | 1         | 0.33%   |
| Logitech                               | 1         | 0.33%   |
| Importek                               | 1         | 0.33%   |
| Genesys Logic                          | 1         | 0.33%   |
| Foxconn / Hon Hai                      | 1         | 0.33%   |
| DJJHNA29IE9J88                         | 1         | 0.33%   |
| Denron                                 | 1         | 0.33%   |
| ARC International                      | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 19        | 6.23%   |
| Chicony HD WebCam                                       | 13        | 4.26%   |
| Realtek Integrated_Webcam_HD                            | 11        | 3.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 10        | 3.28%   |
| Chicony Integrated Camera                               | 10        | 3.28%   |
| Sunplus HD WebCam                                       | 7         | 2.3%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 7         | 2.3%    |
| Acer HD Webcam                                          | 7         | 2.3%    |
| Acer EasyCamera                                         | 7         | 2.3%    |
| Apple FaceTime HD Camera                                | 6         | 1.97%   |
| Acer Integrated Camera                                  | 6         | 1.97%   |
| Realtek Lenovo EasyCamera                               | 5         | 1.64%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 5         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 5         | 1.64%   |
| Suyin HP TrueVision HD                                  | 4         | 1.31%   |
| Chicony USB2.0 VGA UVC WebCam                           | 4         | 1.31%   |
| Chicony USB 2.0 Camera                                  | 4         | 1.31%   |
| Chicony Lenovo EasyCamera                               | 4         | 1.31%   |
| Apple FaceTime HD Camera (Built-in)                     | 4         | 1.31%   |
| Alcor Micro USB 2.0 Camera                              | 4         | 1.31%   |
| Acer Lenovo EasyCamera                                  | 4         | 1.31%   |
| Syntek EasyCamera                                       | 3         | 0.98%   |
| Suyin HD WebCam                                         | 3         | 0.98%   |
| Sunplus Integrated_Webcam_HD                            | 3         | 0.98%   |
| Quanta HD Webcam                                        | 3         | 0.98%   |
| Microdia Integrated Webcam HD                           | 3         | 0.98%   |
| Lite-On Integrated Camera                               | 3         | 0.98%   |
| IMC Networks Integrated Camera                          | 3         | 0.98%   |
| Chicony VGA WebCam                                      | 3         | 0.98%   |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 0.98%   |
| Chicony TOSHIBA Web Camera - HD                         | 3         | 0.98%   |
| Alcor Micro USB 2.0 PC Camera                           | 3         | 0.98%   |
| Sunplus Laptop Integrated WebCam HD                     | 2         | 0.66%   |
| Sunplus Integrated_Webcam_FHD                           | 2         | 0.66%   |
| Silicon Motion WebCam SCB-1100N                         | 2         | 0.66%   |
| Silicon Motion WebCam SC-13HDL11624N                    | 2         | 0.66%   |
| Silicon Motion Web Camera                               | 2         | 0.66%   |
| Silicon Motion 300k Pixel Camera                        | 2         | 0.66%   |
| Samsung Galaxy A5 (MTP)                                 | 2         | 0.66%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.66%   |
| Realtek HP Webcam                                       | 2         | 0.66%   |
| Realtek HD WebCam                                       | 2         | 0.66%   |
| Quanta HP TrueVision HD Camera                          | 2         | 0.66%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 0.66%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 2         | 0.66%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 2         | 0.66%   |
| Chicony USB 2.0 Webcam Device                           | 2         | 0.66%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 2         | 0.66%   |
| Chicony Integrated HP HD Webcam                         | 2         | 0.66%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 0.66%   |
| Chicony HP Wide Vision HD                               | 2         | 0.66%   |
| Chicony HP Webcam [2 MP Macro]                          | 2         | 0.66%   |
| Chicony HP Webcam                                       | 2         | 0.66%   |
| Chicony HP TrueVision HD                                | 2         | 0.66%   |
| Chicony HP HD Webcam                                    | 2         | 0.66%   |
| Chicony HP HD Camera                                    | 2         | 0.66%   |
| Chicony FJ Camera                                       | 2         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 0.66%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 42.42%  |
| Synaptics                  | 6         | 18.18%  |
| Shenzhen Goodix Technology | 3         | 9.09%   |
| Elan Microelectronics      | 3         | 9.09%   |
| Upek                       | 2         | 6.06%   |
| Samsung Electronics        | 2         | 6.06%   |
| AuthenTec                  | 2         | 6.06%   |
| LighTuning Technology      | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 15.15%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 9.09%   |
| Elan ELAN:Fingerprint                                                      | 3         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 6.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 6.06%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 6.06%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 6.06%   |
| Samsung Fingerprint Device                                                 | 2         | 6.06%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 6.06%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.03%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 3.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.03%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.03%   |
| Synaptics  WBDI                                                            | 1         | 3.03%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 3.03%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.03%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.03%   |
| Unknown                                                                    | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 7         | 53.85%  |
| Alcor Micro                | 2         | 15.38%  |
| Upek                       | 1         | 7.69%   |
| Lenovo                     | 1         | 7.69%   |
| Athena Smartcard Solutions | 1         | 7.69%   |
| Aladdin Knowledge Systems  | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 23.08%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 15.38%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 15.38%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 7.69%   |
| Broadcom 5880                                                                | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 7.69%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 201       | 58.77%  |
| 1     | 121       | 35.38%  |
| 2     | 19        | 5.56%   |
| 3     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 45        | 26.95%  |
| Fingerprint reader       | 33        | 19.76%  |
| Net/wireless             | 24        | 14.37%  |
| Firewire controller      | 19        | 11.38%  |
| Multimedia controller    | 17        | 10.18%  |
| Chipcard                 | 13        | 7.78%   |
| Camera                   | 4         | 2.4%    |
| Net/ethernet             | 3         | 1.8%    |
| Sound                    | 2         | 1.2%    |
| Bluetooth                | 2         | 1.2%    |
| Storage/nvme             | 1         | 0.6%    |
| Storage/ide              | 1         | 0.6%    |
| Storage                  | 1         | 0.6%    |
| Modem                    | 1         | 0.6%    |
| Communication controller | 1         | 0.6%    |

