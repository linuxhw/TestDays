Linux in Israel - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Israel.

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

Total: 455

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 5820                 | [3e0e45bc17](https://linux-hardware.org/?probe=3e0e45bc17) | Mar 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [5667e8416e](https://linux-hardware.org/?probe=5667e8416e) | Mar 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [2c2920d462](https://linux-hardware.org/?probe=2c2920d462) | Mar 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [28769bd85b](https://linux-hardware.org/?probe=28769bd85b) | Mar 12, 2023 |
| Gigabyte      | AORUS 17G XC                | [fb998b9957](https://linux-hardware.org/?probe=fb998b9957) | Mar 12, 2023 |
| Acer          | Aspire A715-72G             | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [ac772ea51f](https://linux-hardware.org/?probe=ac772ea51f) | Mar 08, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [4e05d0a0e9](https://linux-hardware.org/?probe=4e05d0a0e9) | Mar 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [aa0e36b22e](https://linux-hardware.org/?probe=aa0e36b22e) | Mar 02, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [3db8300147](https://linux-hardware.org/?probe=3db8300147) | Mar 01, 2023 |
| Timi          | RedmiBook 16                | [2d713931d2](https://linux-hardware.org/?probe=2d713931d2) | Feb 28, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| HP            | Pavilion TS 14              | [37296c42c3](https://linux-hardware.org/?probe=37296c42c3) | Feb 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [323b6463a9](https://linux-hardware.org/?probe=323b6463a9) | Feb 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Alienware     | 15 R2                       | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| HP            | Laptop 15-ef2xxx            | [6f8fadfe19](https://linux-hardware.org/?probe=6f8fadfe19) | Feb 15, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [26ea96167c](https://linux-hardware.org/?probe=26ea96167c) | Feb 12, 2023 |
| Dell          | Vostro 3558                 | [bb53ff2532](https://linux-hardware.org/?probe=bb53ff2532) | Feb 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [a1133b56be](https://linux-hardware.org/?probe=a1133b56be) | Feb 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [ab928273ba](https://linux-hardware.org/?probe=ab928273ba) | Feb 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [5995e0b36b](https://linux-hardware.org/?probe=5995e0b36b) | Feb 11, 2023 |
| Heptagon S... | HQ-BOX2 Server              | [476197a287](https://linux-hardware.org/?probe=476197a287) | Feb 09, 2023 |
| Lenovo        | V14-IIL 82C4                | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| ASUSTek       | X556UV                      | [ae90dba4ca](https://linux-hardware.org/?probe=ae90dba4ca) | Feb 04, 2023 |
| HUAWEI        | HN-WX9X                     | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK U554               | [22bf4111de](https://linux-hardware.org/?probe=22bf4111de) | Jan 23, 2023 |
| Acer          | TravelMate P257-M           | [1345fa56c4](https://linux-hardware.org/?probe=1345fa56c4) | Jan 22, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| Dell          | Vostro 14 5401              | [b56e81d82d](https://linux-hardware.org/?probe=b56e81d82d) | Jan 11, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [3965f2f9f4](https://linux-hardware.org/?probe=3965f2f9f4) | Jan 11, 2023 |
| Dell          | XPS 15 9550                 | [abe344877a](https://linux-hardware.org/?probe=abe344877a) | Jan 09, 2023 |
| Dell          | XPS 15 9550                 | [6a5da8e502](https://linux-hardware.org/?probe=6a5da8e502) | Jan 08, 2023 |
| Apple         | MacBookPro10,1              | [874b25fc88](https://linux-hardware.org/?probe=874b25fc88) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Apple         | MacBookPro8,1               | [4641833cab](https://linux-hardware.org/?probe=4641833cab) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Lenovo        | V14-IIL 82C4                | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| GPD           | G1621-02                    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Dell          | Vostro 15 5510              | [10f4ac5e13](https://linux-hardware.org/?probe=10f4ac5e13) | Dec 24, 2022 |
| Dell          | XPS 15 9520                 | [b9b1f8140b](https://linux-hardware.org/?probe=b9b1f8140b) | Dec 18, 2022 |
| MSI           | Summit E16FlipEvo A12MT     | [426289da4e](https://linux-hardware.org/?probe=426289da4e) | Dec 11, 2022 |
| Dell          | Latitude E6420              | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [dc13dde66a](https://linux-hardware.org/?probe=dc13dde66a) | Nov 29, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [ade5f58f0e](https://linux-hardware.org/?probe=ade5f58f0e) | Nov 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [58c63522a4](https://linux-hardware.org/?probe=58c63522a4) | Nov 20, 2022 |
| Dell          | Inspiron 1545               | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| Dell          | Inspiron 1545               | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| Dell          | Vostro 3300                 | [ae100dd7e2](https://linux-hardware.org/?probe=ae100dd7e2) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| ASUSTek       | UX430UNR                    | [f04bf95806](https://linux-hardware.org/?probe=f04bf95806) | Nov 08, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| HP            | Laptop 15-dw2xxx            | [66b04ff6f8](https://linux-hardware.org/?probe=66b04ff6f8) | Oct 20, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [989fe39fa7](https://linux-hardware.org/?probe=989fe39fa7) | Oct 10, 2022 |
| Dell          | Inspiron 5559               | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| HP            | ProBook 430 G6              | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [bc43cff31b](https://linux-hardware.org/?probe=bc43cff31b) | Sep 23, 2022 |
| Dell          | Inspiron 1545               | [cc3af3e194](https://linux-hardware.org/?probe=cc3af3e194) | Sep 16, 2022 |
| Dell          | Inspiron 1545               | [598341495c](https://linux-hardware.org/?probe=598341495c) | Sep 16, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Acer          | Aspire 5820                 | [1820ffa037](https://linux-hardware.org/?probe=1820ffa037) | Sep 09, 2022 |
| Acer          | Aspire 5820                 | [3f0d8d8ff5](https://linux-hardware.org/?probe=3f0d8d8ff5) | Sep 09, 2022 |
| Dell          | Latitude E4300              | [4589ef4489](https://linux-hardware.org/?probe=4589ef4489) | Sep 06, 2022 |
| Apple         | MacBookPro8,1               | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| ASUSTek       | G75VX                       | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Dell          | XPS 15 7590                 | [9158baf2c0](https://linux-hardware.org/?probe=9158baf2c0) | Aug 28, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [4f711bf806](https://linux-hardware.org/?probe=4f711bf806) | Aug 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [eb37729065](https://linux-hardware.org/?probe=eb37729065) | Aug 16, 2022 |
| Lenovo        | G50-80 80L0                 | [eb58813044](https://linux-hardware.org/?probe=eb58813044) | Aug 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS3UW00    | [ddefadf8f1](https://linux-hardware.org/?probe=ddefadf8f1) | Aug 06, 2022 |
| Lenovo        | 3000 G530 4151/200          | [8e9bf5b1f9](https://linux-hardware.org/?probe=8e9bf5b1f9) | Aug 03, 2022 |
| Dell          | G7 7500                     | [f5e6475121](https://linux-hardware.org/?probe=f5e6475121) | Jul 22, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [8f556b89fc](https://linux-hardware.org/?probe=8f556b89fc) | Jul 16, 2022 |
| ASUSTek       | G53JW                       | [2090800f5c](https://linux-hardware.org/?probe=2090800f5c) | Jul 06, 2022 |
| HP            | ProBook 430 G6              | [4281fab7fd](https://linux-hardware.org/?probe=4281fab7fd) | Jul 05, 2022 |
| HP            | Mini 210-1100               | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| Dell          | Latitude 7300               | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [755c2fc534](https://linux-hardware.org/?probe=755c2fc534) | Jun 20, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [2e98922741](https://linux-hardware.org/?probe=2e98922741) | Jun 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [51042aca4a](https://linux-hardware.org/?probe=51042aca4a) | Jun 15, 2022 |
| Purism        | Librem 14                   | [89d920a7d2](https://linux-hardware.org/?probe=89d920a7d2) | Jun 11, 2022 |
| Dell          | XPS 15 9570                 | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| Lenovo        | Unknown                     | [2921bcaa1c](https://linux-hardware.org/?probe=2921bcaa1c) | Jun 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1c8e5b49d3](https://linux-hardware.org/?probe=1c8e5b49d3) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [00d3a71a00](https://linux-hardware.org/?probe=00d3a71a00) | Jun 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| ASUSTek       | N550JV                      | [37af34e2e7](https://linux-hardware.org/?probe=37af34e2e7) | May 31, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| ASUSTek       | N550JV                      | [7b3acdb5ac](https://linux-hardware.org/?probe=7b3acdb5ac) | May 23, 2022 |
| ASUSTek       | N550JV                      | [286611f4de](https://linux-hardware.org/?probe=286611f4de) | May 20, 2022 |
| Dell          | Inspiron 5577               | [d14ee897f2](https://linux-hardware.org/?probe=d14ee897f2) | May 17, 2022 |
| Lenovo        | V14-IIL 82C4                | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| Dell          | Latitude 5421               | [3b2e352ea9](https://linux-hardware.org/?probe=3b2e352ea9) | May 11, 2022 |
| Dell          | Latitude 5421               | [105382c79b](https://linux-hardware.org/?probe=105382c79b) | May 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [f48ef1adaf](https://linux-hardware.org/?probe=f48ef1adaf) | May 09, 2022 |
| Dell          | Vostro 5402                 | [ff11e148fd](https://linux-hardware.org/?probe=ff11e148fd) | May 04, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a7fe3cb0f6](https://linux-hardware.org/?probe=a7fe3cb0f6) | Apr 30, 2022 |
| Dell          | Latitude 7400               | [7f20623ac0](https://linux-hardware.org/?probe=7f20623ac0) | Apr 28, 2022 |
| ASUSTek       | UX32VD                      | [6f956cd55c](https://linux-hardware.org/?probe=6f956cd55c) | Apr 23, 2022 |
| Acer          | Aspire V7-482PG             | [40eb526de9](https://linux-hardware.org/?probe=40eb526de9) | Apr 18, 2022 |
| Acer          | Aspire 5755G                | [e13fc569ce](https://linux-hardware.org/?probe=e13fc569ce) | Apr 13, 2022 |
| Lenovo        | Legion Y730-15ICH 81HD      | [9ad8e2f080](https://linux-hardware.org/?probe=9ad8e2f080) | Apr 13, 2022 |
| HP            | 250 G4 Notebook PC          | [7f35e9e656](https://linux-hardware.org/?probe=7f35e9e656) | Apr 09, 2022 |
| Dell          | XPS 15 9570                 | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| Acer          | Aspire 5820                 | [5288ae7fc8](https://linux-hardware.org/?probe=5288ae7fc8) | Mar 17, 2022 |
| ASUSTek       | N550JV                      | [0d64cbab8e](https://linux-hardware.org/?probe=0d64cbab8e) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| Dell          | Latitude 5411               | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [376b49560d](https://linux-hardware.org/?probe=376b49560d) | Feb 28, 2022 |
| Dell          | Studio 1555                 | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| ASUSTek       | S400CA                      | [56c75c35b6](https://linux-hardware.org/?probe=56c75c35b6) | Feb 19, 2022 |
| Dell          | Latitude E6330              | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [331b62c0e9](https://linux-hardware.org/?probe=331b62c0e9) | Feb 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [310e0596c7](https://linux-hardware.org/?probe=310e0596c7) | Feb 05, 2022 |
| Dell          | Inspiron 3542               | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Dell          | Latitude 3350               | [682af42b93](https://linux-hardware.org/?probe=682af42b93) | Jan 18, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [8ab84f13d3](https://linux-hardware.org/?probe=8ab84f13d3) | Jan 14, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [50669a06d2](https://linux-hardware.org/?probe=50669a06d2) | Jan 14, 2022 |
| Lenovo        | V14-IIL 82C4                | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| Lenovo        | V14-IIL 82C4                | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Dell          | Vostro 3560                 | [ffc754462f](https://linux-hardware.org/?probe=ffc754462f) | Dec 30, 2021 |
| Dell          | Vostro 3560                 | [cd630222d7](https://linux-hardware.org/?probe=cd630222d7) | Dec 30, 2021 |
| Acer          | Aspire 5755G                | [14f60e1eef](https://linux-hardware.org/?probe=14f60e1eef) | Dec 28, 2021 |
| Lenovo        | V14-IIL 82C4                | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| HP            | 240 G6 Notebook PC          | [0eee85762e](https://linux-hardware.org/?probe=0eee85762e) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | [f986757d36](https://linux-hardware.org/?probe=f986757d36) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | [8462457866](https://linux-hardware.org/?probe=8462457866) | Dec 14, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [df4d55c39b](https://linux-hardware.org/?probe=df4d55c39b) | Nov 26, 2021 |
| ASUSTek       | UX331UA                     | [7aee71ceed](https://linux-hardware.org/?probe=7aee71ceed) | Nov 24, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [540612a510](https://linux-hardware.org/?probe=540612a510) | Nov 23, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [ba96dd251c](https://linux-hardware.org/?probe=ba96dd251c) | Nov 17, 2021 |
| Dell          | Inspiron 3581               | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| ASUSTek       | BU403UAV                    | [cb7fcf5c15](https://linux-hardware.org/?probe=cb7fcf5c15) | Nov 15, 2021 |
| ASUSTek       | GL502VMK                    | [78bc4b00c0](https://linux-hardware.org/?probe=78bc4b00c0) | Nov 12, 2021 |
| Dell          | XPS 15 9510                 | [b95625ab23](https://linux-hardware.org/?probe=b95625ab23) | Nov 10, 2021 |
| Dell          | Latitude 5410               | [35fd3a8949](https://linux-hardware.org/?probe=35fd3a8949) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [c5e111be13](https://linux-hardware.org/?probe=c5e111be13) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [6cc81555db](https://linux-hardware.org/?probe=6cc81555db) | Nov 04, 2021 |
| Dell          | System Inspiron N7110       | [3f5d6aaab8](https://linux-hardware.org/?probe=3f5d6aaab8) | Oct 26, 2021 |
| Lenovo        | G40-70 20369                | [c8606a3a2a](https://linux-hardware.org/?probe=c8606a3a2a) | Oct 20, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [b8d00b123f](https://linux-hardware.org/?probe=b8d00b123f) | Oct 16, 2021 |
| Dell          | Inspiron 3593               | [28136dcca0](https://linux-hardware.org/?probe=28136dcca0) | Oct 13, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [267712392b](https://linux-hardware.org/?probe=267712392b) | Oct 11, 2021 |
| Notebook      | N2x0WU                      | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Dell          | Inspiron 3521               | [3e85c5d96f](https://linux-hardware.org/?probe=3e85c5d96f) | Sep 27, 2021 |
| Dell          | Latitude 5420               | [a31b3507c4](https://linux-hardware.org/?probe=a31b3507c4) | Sep 26, 2021 |
| Dell          | Latitude 5420               | [a077664ed2](https://linux-hardware.org/?probe=a077664ed2) | Sep 26, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [ab36263477](https://linux-hardware.org/?probe=ab36263477) | Sep 25, 2021 |
| Lenovo        | G40-70 20369                | [e79a9eb09d](https://linux-hardware.org/?probe=e79a9eb09d) | Sep 22, 2021 |
| Lenovo        | G50-80 80L0                 | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [229830926d](https://linux-hardware.org/?probe=229830926d) | Sep 13, 2021 |
| Dell          | Vostro 7590                 | [8f4e694845](https://linux-hardware.org/?probe=8f4e694845) | Sep 10, 2021 |
| Lenovo        | G50-80 80L0                 | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Dell          | Vostro 3580                 | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T410 2522WZN       | [b6c19325a4](https://linux-hardware.org/?probe=b6c19325a4) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ProBook 4520s               | [4f947f1b22](https://linux-hardware.org/?probe=4f947f1b22) | Sep 06, 2021 |
| HP            | ProBook 4520s               | [fac0dbdf09](https://linux-hardware.org/?probe=fac0dbdf09) | Sep 06, 2021 |
| HP            | Spectre Notebook            | [6a3406a77f](https://linux-hardware.org/?probe=6a3406a77f) | Sep 02, 2021 |
| HP            | Spectre Notebook            | [9966ff0b8f](https://linux-hardware.org/?probe=9966ff0b8f) | Sep 02, 2021 |
| Apple         | MacBookPro12,1              | [79010f7e30](https://linux-hardware.org/?probe=79010f7e30) | Aug 31, 2021 |
| HP            | Compaq Presario CQ61        | [c7c1d06954](https://linux-hardware.org/?probe=c7c1d06954) | Aug 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [17afc04962](https://linux-hardware.org/?probe=17afc04962) | Aug 16, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [0ca5c5faa2](https://linux-hardware.org/?probe=0ca5c5faa2) | Aug 11, 2021 |
| IP3 Tech      | AP1                         | [b27a94c64c](https://linux-hardware.org/?probe=b27a94c64c) | Aug 08, 2021 |
| Dell          | Latitude 5410               | [4f2e0ccb9f](https://linux-hardware.org/?probe=4f2e0ccb9f) | Aug 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [eaa9723b34](https://linux-hardware.org/?probe=eaa9723b34) | Aug 03, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [37cbdcae11](https://linux-hardware.org/?probe=37cbdcae11) | Aug 03, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [6c6c327314](https://linux-hardware.org/?probe=6c6c327314) | Aug 02, 2021 |
| Dell          | Latitude 5410               | [73c46f7a65](https://linux-hardware.org/?probe=73c46f7a65) | Aug 01, 2021 |
| Dell          | Latitude 5410               | [8357a0ce64](https://linux-hardware.org/?probe=8357a0ce64) | Aug 01, 2021 |
| HP            | Unknown                     | [f048334d4b](https://linux-hardware.org/?probe=f048334d4b) | Jul 21, 2021 |
| Dell          | Latitude E4300              | [3310bfe342](https://linux-hardware.org/?probe=3310bfe342) | Jul 20, 2021 |
| Apple         | MacBookAir4,2               | [d479a6fd61](https://linux-hardware.org/?probe=d479a6fd61) | Jun 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [d96ffce12a](https://linux-hardware.org/?probe=d96ffce12a) | Jun 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [13ed380099](https://linux-hardware.org/?probe=13ed380099) | Jun 24, 2021 |
| HP            | Notebook                    | [c3f23110da](https://linux-hardware.org/?probe=c3f23110da) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [79f64eaadf](https://linux-hardware.org/?probe=79f64eaadf) | Jun 19, 2021 |
| HP            | Notebook                    | [daae35477b](https://linux-hardware.org/?probe=daae35477b) | Jun 19, 2021 |
| Dell          | Vostro 5590                 | [debb5f4ac5](https://linux-hardware.org/?probe=debb5f4ac5) | Jun 07, 2021 |
| Acer          | Aspire 4333                 | [9f3738469d](https://linux-hardware.org/?probe=9f3738469d) | May 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c2267f8dd1](https://linux-hardware.org/?probe=c2267f8dd1) | May 19, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [6fe368312c](https://linux-hardware.org/?probe=6fe368312c) | May 15, 2021 |
| Lenovo        | G510 20238                  | [9497cc9d85](https://linux-hardware.org/?probe=9497cc9d85) | May 15, 2021 |
| Dell          | Latitude E4300              | [7ed9015fd5](https://linux-hardware.org/?probe=7ed9015fd5) | May 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [ab559fd00d](https://linux-hardware.org/?probe=ab559fd00d) | May 09, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [8bf60ca353](https://linux-hardware.org/?probe=8bf60ca353) | May 08, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [c72aec456a](https://linux-hardware.org/?probe=c72aec456a) | May 06, 2021 |
| LG Electro... | 15Z980-A.AAS8U1             | [2a68dcd848](https://linux-hardware.org/?probe=2a68dcd848) | May 03, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [ca15c642d7](https://linux-hardware.org/?probe=ca15c642d7) | Apr 08, 2021 |
| Dell          | Inspiron 5755               | [fefe0c7d71](https://linux-hardware.org/?probe=fefe0c7d71) | Apr 01, 2021 |
| Dell          | Inspiron 3593               | [4cc755d1c2](https://linux-hardware.org/?probe=4cc755d1c2) | Mar 25, 2021 |
| HP            | Compaq Presario CQ61        | [58db0eef1f](https://linux-hardware.org/?probe=58db0eef1f) | Mar 25, 2021 |
| Dell          | XPS 13 9370                 | [f71120521c](https://linux-hardware.org/?probe=f71120521c) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [edf6ab636e](https://linux-hardware.org/?probe=edf6ab636e) | Mar 19, 2021 |
| HP            | ZBook 15 G3                 | [fa7b8613f2](https://linux-hardware.org/?probe=fa7b8613f2) | Mar 16, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ff15d5b8ad](https://linux-hardware.org/?probe=ff15d5b8ad) | Mar 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a50f9abd26](https://linux-hardware.org/?probe=a50f9abd26) | Mar 11, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [77a787d158](https://linux-hardware.org/?probe=77a787d158) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a55964d5d9](https://linux-hardware.org/?probe=a55964d5d9) | Mar 06, 2021 |
| Lenovo        | G50-80 80E5                 | [4336742334](https://linux-hardware.org/?probe=4336742334) | Mar 04, 2021 |
| HUAWEI        | HN-WX9X                     | [fb3d2fc3e9](https://linux-hardware.org/?probe=fb3d2fc3e9) | Mar 03, 2021 |
| HP            | ZBook 15 G6                 | [061392ad81](https://linux-hardware.org/?probe=061392ad81) | Mar 01, 2021 |
| ASUSTek       | GL503VD                     | [d03b00803b](https://linux-hardware.org/?probe=d03b00803b) | Feb 27, 2021 |
| Apple         | MacBookPro9,2               | [618d47c042](https://linux-hardware.org/?probe=618d47c042) | Feb 27, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [2fff8b3674](https://linux-hardware.org/?probe=2fff8b3674) | Feb 24, 2021 |
| HUAWEI        | HN-WX9X                     | [2b4a74a520](https://linux-hardware.org/?probe=2b4a74a520) | Feb 16, 2021 |
| HUAWEI        | HN-WX9X                     | [f4c77fc7dc](https://linux-hardware.org/?probe=f4c77fc7dc) | Feb 16, 2021 |
| HP            | Compaq Presario CQ61        | [e72ebb6663](https://linux-hardware.org/?probe=e72ebb6663) | Feb 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [a2ab510560](https://linux-hardware.org/?probe=a2ab510560) | Feb 14, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8711f89b6b](https://linux-hardware.org/?probe=8711f89b6b) | Feb 13, 2021 |
| HP            | Compaq Presario CQ61        | [bcf179fa51](https://linux-hardware.org/?probe=bcf179fa51) | Feb 12, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [655d6c5817](https://linux-hardware.org/?probe=655d6c5817) | Feb 06, 2021 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [799c676c40](https://linux-hardware.org/?probe=799c676c40) | Feb 04, 2021 |
| Lenovo        | ThinkPad E550 20DF004RIV    | [23140cf3f9](https://linux-hardware.org/?probe=23140cf3f9) | Jan 29, 2021 |
| Lenovo        | G40-70 20369                | [1763668816](https://linux-hardware.org/?probe=1763668816) | Jan 29, 2021 |
| Dell          | Latitude E6420              | [9aa53da922](https://linux-hardware.org/?probe=9aa53da922) | Jan 19, 2021 |
| Dell          | Latitude E6420              | [20a4b3769d](https://linux-hardware.org/?probe=20a4b3769d) | Jan 19, 2021 |
| Dell          | XPS 13 9370                 | [4df2203870](https://linux-hardware.org/?probe=4df2203870) | Jan 19, 2021 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [65724a4aa6](https://linux-hardware.org/?probe=65724a4aa6) | Jan 18, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [1883634f7b](https://linux-hardware.org/?probe=1883634f7b) | Jan 18, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [23a9e9c5f6](https://linux-hardware.org/?probe=23a9e9c5f6) | Jan 17, 2021 |
| HP            | Pavilion Notebook           | [750413cc61](https://linux-hardware.org/?probe=750413cc61) | Jan 16, 2021 |
| HP            | EliteBook 840 G5            | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Dell          | Inspiron 13-5378            | [94b70d7578](https://linux-hardware.org/?probe=94b70d7578) | Jan 12, 2021 |
| HP            | Pavilion Notebook           | [c1eeffc9d8](https://linux-hardware.org/?probe=c1eeffc9d8) | Jan 08, 2021 |
| Dell          | Inspiron 5567               | [0d62d918c5](https://linux-hardware.org/?probe=0d62d918c5) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | [5a3a67e5c3](https://linux-hardware.org/?probe=5a3a67e5c3) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | [f37800ed52](https://linux-hardware.org/?probe=f37800ed52) | Jan 07, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [b8bab31c57](https://linux-hardware.org/?probe=b8bab31c57) | Jan 06, 2021 |
| Dell          | Inspiron 13-5378            | [d55bf78096](https://linux-hardware.org/?probe=d55bf78096) | Jan 06, 2021 |
| Unknown       | Unknown                     | [b364724e53](https://linux-hardware.org/?probe=b364724e53) | Jan 02, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [8d338ea73c](https://linux-hardware.org/?probe=8d338ea73c) | Dec 31, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [ef84edb346](https://linux-hardware.org/?probe=ef84edb346) | Dec 31, 2020 |
| HP            | EliteBook 2570p             | [2ed921327b](https://linux-hardware.org/?probe=2ed921327b) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [9448ec4439](https://linux-hardware.org/?probe=9448ec4439) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [7cd92f4564](https://linux-hardware.org/?probe=7cd92f4564) | Dec 30, 2020 |
| Unknown       | Unknown                     | [749c45e229](https://linux-hardware.org/?probe=749c45e229) | Dec 29, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [01024cf86e](https://linux-hardware.org/?probe=01024cf86e) | Dec 27, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [66fd37cef4](https://linux-hardware.org/?probe=66fd37cef4) | Dec 27, 2020 |
| Dell          | Inspiron 3542               | [c79668f190](https://linux-hardware.org/?probe=c79668f190) | Dec 24, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [56b69fe95e](https://linux-hardware.org/?probe=56b69fe95e) | Dec 23, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [ddc1a4457d](https://linux-hardware.org/?probe=ddc1a4457d) | Dec 22, 2020 |
| HP            | Pavilion g6                 | [8d41f37972](https://linux-hardware.org/?probe=8d41f37972) | Dec 18, 2020 |
| Unknown       | Unknown                     | [e42b0f86e0](https://linux-hardware.org/?probe=e42b0f86e0) | Dec 14, 2020 |
| HUAWEI        | HN-WX9X                     | [5c1982b26c](https://linux-hardware.org/?probe=5c1982b26c) | Dec 08, 2020 |
| HUAWEI        | HN-WX9X                     | [5b58c4ff46](https://linux-hardware.org/?probe=5b58c4ff46) | Dec 08, 2020 |
| HP            | Laptop 15-da1xxx            | [df5f3d5a4d](https://linux-hardware.org/?probe=df5f3d5a4d) | Dec 07, 2020 |
| Dell          | XPS 13 9370                 | [4cbbe5b21a](https://linux-hardware.org/?probe=4cbbe5b21a) | Nov 26, 2020 |
| Lenovo        | Unknown                     | [40c892a262](https://linux-hardware.org/?probe=40c892a262) | Nov 26, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [46d30ce200](https://linux-hardware.org/?probe=46d30ce200) | Nov 20, 2020 |
| Toshiba       | Satellite L755              | [a6e2af6e5b](https://linux-hardware.org/?probe=a6e2af6e5b) | Nov 18, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2f9457bf32](https://linux-hardware.org/?probe=2f9457bf32) | Nov 17, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f2e24821f4](https://linux-hardware.org/?probe=f2e24821f4) | Nov 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [e13999e22a](https://linux-hardware.org/?probe=e13999e22a) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | [e04b97eabe](https://linux-hardware.org/?probe=e04b97eabe) | Nov 11, 2020 |
| Acer          | Aspire A715-72G             | [90ef23a01c](https://linux-hardware.org/?probe=90ef23a01c) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | [4572167747](https://linux-hardware.org/?probe=4572167747) | Nov 10, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [21105809e4](https://linux-hardware.org/?probe=21105809e4) | Nov 08, 2020 |
| Lenovo        | Yoga 3 11 80J8              | [b4f083536f](https://linux-hardware.org/?probe=b4f083536f) | Nov 04, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [b94cef8d24](https://linux-hardware.org/?probe=b94cef8d24) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [c872f1d76f](https://linux-hardware.org/?probe=c872f1d76f) | Nov 03, 2020 |
| Dell          | Latitude E6330              | [f7e530a8c2](https://linux-hardware.org/?probe=f7e530a8c2) | Nov 02, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [e8426a064f](https://linux-hardware.org/?probe=e8426a064f) | Nov 01, 2020 |
| Lenovo        | ThinkPad E480 20KN0062IV    | [fba2fb0e45](https://linux-hardware.org/?probe=fba2fb0e45) | Oct 30, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [1a691f72dc](https://linux-hardware.org/?probe=1a691f72dc) | Oct 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [990f9bb22f](https://linux-hardware.org/?probe=990f9bb22f) | Oct 29, 2020 |
| Dell          | Latitude 7490               | [2d61d426d5](https://linux-hardware.org/?probe=2d61d426d5) | Oct 28, 2020 |
| Dell          | Latitude 7300               | [ebf99bafc8](https://linux-hardware.org/?probe=ebf99bafc8) | Oct 27, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [36d289ce92](https://linux-hardware.org/?probe=36d289ce92) | Oct 20, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [e360fd1fa2](https://linux-hardware.org/?probe=e360fd1fa2) | Oct 18, 2020 |
| Dell          | Vostro 14 5401              | [89826d13da](https://linux-hardware.org/?probe=89826d13da) | Oct 13, 2020 |
| ASUSTek       | UX430UNR                    | [03dd6f184c](https://linux-hardware.org/?probe=03dd6f184c) | Oct 12, 2020 |
| Dell          | Vostro 14 5401              | [d3f66acd1b](https://linux-hardware.org/?probe=d3f66acd1b) | Oct 12, 2020 |
| HP            | Laptop 15-bs1xx             | [cab83dd9ff](https://linux-hardware.org/?probe=cab83dd9ff) | Oct 12, 2020 |
| Dell          | Vostro 5490                 | [b998e489c5](https://linux-hardware.org/?probe=b998e489c5) | Oct 07, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [a9d940dd83](https://linux-hardware.org/?probe=a9d940dd83) | Oct 04, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [c7e2a6001a](https://linux-hardware.org/?probe=c7e2a6001a) | Oct 04, 2020 |
| Dell          | Latitude 7400               | [6eac6cfa15](https://linux-hardware.org/?probe=6eac6cfa15) | Oct 04, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c4d11b04b5](https://linux-hardware.org/?probe=c4d11b04b5) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [b8c1686e69](https://linux-hardware.org/?probe=b8c1686e69) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [33801ffba1](https://linux-hardware.org/?probe=33801ffba1) | Sep 28, 2020 |
| Lenovo        | ThinkPad E14 20RA0036IV     | [d53e57ac10](https://linux-hardware.org/?probe=d53e57ac10) | Sep 25, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [9b2604c2e1](https://linux-hardware.org/?probe=9b2604c2e1) | Sep 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f8631e5f4a](https://linux-hardware.org/?probe=f8631e5f4a) | Sep 03, 2020 |
| Dell          | Latitude E5270              | [745e05ba12](https://linux-hardware.org/?probe=745e05ba12) | Aug 31, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [eee9972fdf](https://linux-hardware.org/?probe=eee9972fdf) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [cb7fda5c3f](https://linux-hardware.org/?probe=cb7fda5c3f) | Aug 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [99c5924655](https://linux-hardware.org/?probe=99c5924655) | Aug 23, 2020 |
| Lenovo        | ThinkPad L390 20NR001LIV    | [9fef5634b2](https://linux-hardware.org/?probe=9fef5634b2) | Aug 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ee5213ce49](https://linux-hardware.org/?probe=ee5213ce49) | Aug 19, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | [5f1ce912be](https://linux-hardware.org/?probe=5f1ce912be) | Aug 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [635a148f20](https://linux-hardware.org/?probe=635a148f20) | Aug 19, 2020 |
| Toshiba       | Satellite P50t-B-10T        | [0f41a5b6ec](https://linux-hardware.org/?probe=0f41a5b6ec) | Aug 13, 2020 |
| Lenovo        | ThinkPad T490 20N20073IV    | [3878e27014](https://linux-hardware.org/?probe=3878e27014) | Aug 10, 2020 |
| Dell          | Latitude 7390 2-in-1        | [fb785080a3](https://linux-hardware.org/?probe=fb785080a3) | Aug 02, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [38442a922b](https://linux-hardware.org/?probe=38442a922b) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | [e934fab850](https://linux-hardware.org/?probe=e934fab850) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | [38feef34d4](https://linux-hardware.org/?probe=38feef34d4) | Aug 01, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ef4f365d92](https://linux-hardware.org/?probe=ef4f365d92) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6126a00ffc](https://linux-hardware.org/?probe=6126a00ffc) | Jul 24, 2020 |
| Dell          | Latitude E6530              | [6e1b2fb388](https://linux-hardware.org/?probe=6e1b2fb388) | Jul 24, 2020 |
| Lenovo        | V510-15IKB 80WQ             | [3944aa1028](https://linux-hardware.org/?probe=3944aa1028) | Jul 20, 2020 |
| HP            | ProBook 640 G2              | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [6e6f80378d](https://linux-hardware.org/?probe=6e6f80378d) | Jul 11, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | [d0aacf7693](https://linux-hardware.org/?probe=d0aacf7693) | Jul 09, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | [868953dc99](https://linux-hardware.org/?probe=868953dc99) | Jul 09, 2020 |
| Dell          | Latitude 5400               | [ae1c2d9825](https://linux-hardware.org/?probe=ae1c2d9825) | Jul 08, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [52fad4367c](https://linux-hardware.org/?probe=52fad4367c) | Jul 01, 2020 |
| HP            | Pavilion dv6                | [39df31f4c6](https://linux-hardware.org/?probe=39df31f4c6) | Jun 27, 2020 |
| Lenovo        | ThinkPad E14 20RA0016IV     | [2878e88064](https://linux-hardware.org/?probe=2878e88064) | Jun 24, 2020 |
| HP            | Pavilion Notebook           | [866c72927a](https://linux-hardware.org/?probe=866c72927a) | Jun 22, 2020 |
| Dell          | Inspiron 5379               | [f7fe8744d9](https://linux-hardware.org/?probe=f7fe8744d9) | Jun 21, 2020 |
| ASUSTek       | UX331UA                     | [064e95c086](https://linux-hardware.org/?probe=064e95c086) | Jun 10, 2020 |
| HP            | EliteBook 840 G5            | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| ASUSTek       | UX331UA                     | [8ca766622f](https://linux-hardware.org/?probe=8ca766622f) | Jun 02, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [1ce6e06069](https://linux-hardware.org/?probe=1ce6e06069) | May 30, 2020 |
| Dell          | Latitude 5490               | [2afe6adf1b](https://linux-hardware.org/?probe=2afe6adf1b) | May 18, 2020 |
| Dell          | Latitude 5490               | [c2b1c12105](https://linux-hardware.org/?probe=c2b1c12105) | May 17, 2020 |
| ASUSTek       | UX331UA                     | [0a0319493d](https://linux-hardware.org/?probe=0a0319493d) | May 15, 2020 |
| HP            | EliteBook 840 G5            | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| HP            | G42                         | [6d45062a76](https://linux-hardware.org/?probe=6d45062a76) | May 14, 2020 |
| Lenovo        | ThinkPad X200 74587DU       | [ba354beaa9](https://linux-hardware.org/?probe=ba354beaa9) | May 10, 2020 |
| ASUSTek       | K54C                        | [c2656ceae6](https://linux-hardware.org/?probe=c2656ceae6) | May 07, 2020 |
| HP            | Pavilion Laptop 14-bf1xx    | [6f86c55589](https://linux-hardware.org/?probe=6f86c55589) | May 04, 2020 |
| Acer          | Swift SF314-54G             | [e93143c6fd](https://linux-hardware.org/?probe=e93143c6fd) | Apr 27, 2020 |
| Acer          | Swift SF314-54G             | [4cc7a86795](https://linux-hardware.org/?probe=4cc7a86795) | Apr 26, 2020 |
| Toshiba       | Satellite A200              | [d9a55aeca2](https://linux-hardware.org/?probe=d9a55aeca2) | Apr 25, 2020 |
| Toshiba       | Satellite A200              | [1e6ea00cd0](https://linux-hardware.org/?probe=1e6ea00cd0) | Apr 25, 2020 |
| ASUSTek       | UX331UA                     | [634f000249](https://linux-hardware.org/?probe=634f000249) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | [94be2c2ea7](https://linux-hardware.org/?probe=94be2c2ea7) | Apr 24, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [2516b70573](https://linux-hardware.org/?probe=2516b70573) | Apr 23, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [cdcce3c09c](https://linux-hardware.org/?probe=cdcce3c09c) | Apr 23, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [434a4a46f9](https://linux-hardware.org/?probe=434a4a46f9) | Apr 19, 2020 |
| Dell          | XPS 13 9350                 | [d718b985ec](https://linux-hardware.org/?probe=d718b985ec) | Apr 18, 2020 |
| HP            | Pavilion Notebook           | [cd641ec5c7](https://linux-hardware.org/?probe=cd641ec5c7) | Apr 17, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [28e6c33fec](https://linux-hardware.org/?probe=28e6c33fec) | Apr 17, 2020 |
| HP            | Pavilion Notebook           | [7e17ce97e9](https://linux-hardware.org/?probe=7e17ce97e9) | Apr 17, 2020 |
| ASUSTek       | X550CA                      | [d23cc368bb](https://linux-hardware.org/?probe=d23cc368bb) | Apr 10, 2020 |
| Dell          | Latitude 5490               | [6759b030d2](https://linux-hardware.org/?probe=6759b030d2) | Apr 10, 2020 |
| Dell          | Latitude 7300               | [4c263fc2d0](https://linux-hardware.org/?probe=4c263fc2d0) | Apr 01, 2020 |
| HP            | ZBook 15 G3                 | [254c1f48da](https://linux-hardware.org/?probe=254c1f48da) | Mar 31, 2020 |
| Dell          | Latitude 5490               | [03873fa787](https://linux-hardware.org/?probe=03873fa787) | Mar 30, 2020 |
| Dell          | Latitude 5490               | [d71d69d129](https://linux-hardware.org/?probe=d71d69d129) | Mar 30, 2020 |
| HP            | EliteBook 840 G5            | [2aab729aee](https://linux-hardware.org/?probe=2aab729aee) | Mar 30, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [9c1238b041](https://linux-hardware.org/?probe=9c1238b041) | Mar 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b5765e1a9f](https://linux-hardware.org/?probe=b5765e1a9f) | Mar 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3c36d4bdc9](https://linux-hardware.org/?probe=3c36d4bdc9) | Mar 21, 2020 |
| Lenovo        | ThinkPad T480 20L5A063CD    | [ccd24104da](https://linux-hardware.org/?probe=ccd24104da) | Mar 08, 2020 |
| Dell          | Inspiron N5110              | [d13a02aacb](https://linux-hardware.org/?probe=d13a02aacb) | Mar 08, 2020 |
| Dell          | Inspiron 7548               | [ebce14c87e](https://linux-hardware.org/?probe=ebce14c87e) | Feb 22, 2020 |
| Dell          | Inspiron 7548               | [d4b3df5729](https://linux-hardware.org/?probe=d4b3df5729) | Feb 22, 2020 |
| ASUSTek       | X201EP                      | [75d7523e83](https://linux-hardware.org/?probe=75d7523e83) | Feb 13, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [239b2eba6d](https://linux-hardware.org/?probe=239b2eba6d) | Feb 08, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [a3e9ca6d37](https://linux-hardware.org/?probe=a3e9ca6d37) | Feb 08, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [60ba0e3d0f](https://linux-hardware.org/?probe=60ba0e3d0f) | Feb 08, 2020 |
| Dell          | Inspiron 13-5378            | [30e38a1812](https://linux-hardware.org/?probe=30e38a1812) | Feb 03, 2020 |
| HP            | Laptop 15-da1xxx            | [b4ef2a52c5](https://linux-hardware.org/?probe=b4ef2a52c5) | Jan 21, 2020 |
| HP            | Laptop 15-da1xxx            | [33d23400b4](https://linux-hardware.org/?probe=33d23400b4) | Jan 20, 2020 |
| LG Electro... | 15Z990-A.AAS7U1             | [afd7d4caf9](https://linux-hardware.org/?probe=afd7d4caf9) | Jan 15, 2020 |
| Lenovo        | G570 4334                   | [7bf153f618](https://linux-hardware.org/?probe=7bf153f618) | Jan 13, 2020 |
| Lenovo        | ThinkPad E595 20NF0018US    | [00d8e5ba33](https://linux-hardware.org/?probe=00d8e5ba33) | Jan 13, 2020 |
| Lenovo        | G570 4334                   | [a423e910c6](https://linux-hardware.org/?probe=a423e910c6) | Jan 13, 2020 |
| Lenovo        | G570 4334                   | [84fcfb4be2](https://linux-hardware.org/?probe=84fcfb4be2) | Jan 07, 2020 |
| Lenovo        | G570 4334                   | [903ab151c8](https://linux-hardware.org/?probe=903ab151c8) | Jan 07, 2020 |
| Lenovo        | G570 4334                   | [495c89d842](https://linux-hardware.org/?probe=495c89d842) | Jan 07, 2020 |
| Dell          | Latitude E7270              | [83f77407ab](https://linux-hardware.org/?probe=83f77407ab) | Jan 06, 2020 |
| Dell          | Latitude E7270              | [dc87d2cdee](https://linux-hardware.org/?probe=dc87d2cdee) | Jan 06, 2020 |
| Dell          | Inspiron MM061              | [3da92e4cab](https://linux-hardware.org/?probe=3da92e4cab) | Jan 02, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [992e2074ff](https://linux-hardware.org/?probe=992e2074ff) | Dec 25, 2019 |
| ASUSTek       | UL30A                       | [b7f84b8da0](https://linux-hardware.org/?probe=b7f84b8da0) | Dec 20, 2019 |
| ASUSTek       | X501A                       | [ce99670ceb](https://linux-hardware.org/?probe=ce99670ceb) | Dec 20, 2019 |
| ASUSTek       | X501A                       | [f7a367e32c](https://linux-hardware.org/?probe=f7a367e32c) | Dec 20, 2019 |
| LG Electro... | A310                        | [d2599d1470](https://linux-hardware.org/?probe=d2599d1470) | Nov 26, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [52db21c094](https://linux-hardware.org/?probe=52db21c094) | Nov 24, 2019 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [831c001466](https://linux-hardware.org/?probe=831c001466) | Nov 23, 2019 |
| HP            | G7000                       | [cb550f69f7](https://linux-hardware.org/?probe=cb550f69f7) | Nov 12, 2019 |
| HP            | G7000                       | [97ada3d9cf](https://linux-hardware.org/?probe=97ada3d9cf) | Nov 12, 2019 |
| HP            | G7000                       | [ca985e708a](https://linux-hardware.org/?probe=ca985e708a) | Nov 12, 2019 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [39c33a8d85](https://linux-hardware.org/?probe=39c33a8d85) | Oct 21, 2019 |
| Samsung       | 3570R/370R/470R/450R/510... | [a5e61f3a1a](https://linux-hardware.org/?probe=a5e61f3a1a) | Oct 18, 2019 |
| Dell          | Latitude E6320              | [276041713d](https://linux-hardware.org/?probe=276041713d) | Oct 18, 2019 |
| Dell          | Latitude E6320              | [a2002798ac](https://linux-hardware.org/?probe=a2002798ac) | Oct 18, 2019 |
| Lenovo        | E31-80 80MX                 | [4f5d1ae105](https://linux-hardware.org/?probe=4f5d1ae105) | Oct 17, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6bc1a600ee](https://linux-hardware.org/?probe=6bc1a600ee) | Oct 06, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [32944602dd](https://linux-hardware.org/?probe=32944602dd) | Oct 06, 2019 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [60e8599708](https://linux-hardware.org/?probe=60e8599708) | Sep 30, 2019 |
| Lenovo        | G560 0679                   | [403cb2c831](https://linux-hardware.org/?probe=403cb2c831) | Sep 19, 2019 |
| Lenovo        | G560 0679                   | [0552d32d91](https://linux-hardware.org/?probe=0552d32d91) | Sep 18, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [77a3bc0e11](https://linux-hardware.org/?probe=77a3bc0e11) | Sep 17, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eeaadaa0a3](https://linux-hardware.org/?probe=eeaadaa0a3) | Sep 17, 2019 |
| HP            | EliteBook 840 G6            | [4ada1a54ef](https://linux-hardware.org/?probe=4ada1a54ef) | Sep 13, 2019 |
| Lenovo        | Yoga 500-14ISK 80R5         | [b4f1b9249a](https://linux-hardware.org/?probe=b4f1b9249a) | Sep 10, 2019 |
| Dell          | Latitude E7450              | [cb374fcaff](https://linux-hardware.org/?probe=cb374fcaff) | Sep 05, 2019 |
| Dell          | XPS 13 9343                 | [ecb0cffd7b](https://linux-hardware.org/?probe=ecb0cffd7b) | Sep 04, 2019 |
| ASUSTek       | X302UJ                      | [d467007887](https://linux-hardware.org/?probe=d467007887) | Aug 24, 2019 |
| Acer          | Aspire 5730                 | [6e8c846d9b](https://linux-hardware.org/?probe=6e8c846d9b) | Aug 24, 2019 |
| Dell          | Latitude E5470              | [d01c149d9c](https://linux-hardware.org/?probe=d01c149d9c) | Aug 17, 2019 |
| Dell          | Latitude E5470              | [b0b32067b9](https://linux-hardware.org/?probe=b0b32067b9) | Aug 17, 2019 |
| Dell          | Inspiron 13-5378            | [afa245a5c3](https://linux-hardware.org/?probe=afa245a5c3) | Aug 13, 2019 |
| HP            | 255 G5 Notebook PC          | [2043a9b3c9](https://linux-hardware.org/?probe=2043a9b3c9) | Jul 18, 2019 |
| ASUSTek       | K54C                        | [4a89c5d895](https://linux-hardware.org/?probe=4a89c5d895) | Jul 06, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [93c1102eae](https://linux-hardware.org/?probe=93c1102eae) | May 30, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [89e100d874](https://linux-hardware.org/?probe=89e100d874) | May 17, 2019 |
| HP            | Pavilion dv6500             | [b185023357](https://linux-hardware.org/?probe=b185023357) | May 13, 2019 |
| ASUSTek       | K54C                        | [653d157e1a](https://linux-hardware.org/?probe=653d157e1a) | May 04, 2019 |
| Lenovo        | ThinkPad T440p 20AN00E3I... | [a803a8593b](https://linux-hardware.org/?probe=a803a8593b) | Apr 11, 2019 |
| Lenovo        | ThinkPad T440p 20AN00E3I... | [6be3c466e0](https://linux-hardware.org/?probe=6be3c466e0) | Apr 10, 2019 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [f49f4bf7e3](https://linux-hardware.org/?probe=f49f4bf7e3) | Mar 30, 2019 |
| Fujitsu Si... | AMILO Li 2727               | [606743f06e](https://linux-hardware.org/?probe=606743f06e) | Mar 22, 2019 |
| System76      | Gazelle                     | [03387dc427](https://linux-hardware.org/?probe=03387dc427) | Mar 12, 2019 |
| HP            | G70                         | [d4f5ef99c5](https://linux-hardware.org/?probe=d4f5ef99c5) | Feb 14, 2019 |
| ASUSTek       | S551LN                      | [572227fb77](https://linux-hardware.org/?probe=572227fb77) | Jan 19, 2019 |
| ASUSTek       | S551LN                      | [f624b3c2eb](https://linux-hardware.org/?probe=f624b3c2eb) | Jan 18, 2019 |
| ASUSTek       | S551LN                      | [084947886f](https://linux-hardware.org/?probe=084947886f) | Jan 03, 2019 |
| Timi          | TM1701                      | [19f0b77769](https://linux-hardware.org/?probe=19f0b77769) | Dec 21, 2018 |
| Timi          | TM1701                      | [e0c4ee1fcb](https://linux-hardware.org/?probe=e0c4ee1fcb) | Dec 21, 2018 |
| ASUSTek       | S551LN                      | [4fef5b511a](https://linux-hardware.org/?probe=4fef5b511a) | Dec 15, 2018 |
| ASUSTek       | S551LN                      | [735db3cd91](https://linux-hardware.org/?probe=735db3cd91) | Dec 14, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [120d843ed3](https://linux-hardware.org/?probe=120d843ed3) | Nov 07, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d21daddd24](https://linux-hardware.org/?probe=d21daddd24) | Nov 07, 2018 |
| ASUSTek       | 1001PXD                     | [00e7c9c5fc](https://linux-hardware.org/?probe=00e7c9c5fc) | Aug 18, 2018 |
| ASUSTek       | 1001PXD                     | [80227a12a8](https://linux-hardware.org/?probe=80227a12a8) | Aug 18, 2018 |
| Lenovo        | ThinkPad T60 2613CTO        | [35edbff8b9](https://linux-hardware.org/?probe=35edbff8b9) | Feb 25, 2018 |
| Samsung       | N248P                       | [2b7782d6cb](https://linux-hardware.org/?probe=2b7782d6cb) | Aug 10, 2017 |
| HP            | Unknown                     | [551457fd6d](https://linux-hardware.org/?probe=551457fd6d) | Jul 10, 2017 |
| Acer          | Aspire 7520                 | [9132eeefdd](https://linux-hardware.org/?probe=9132eeefdd) | Nov 21, 2016 |
| ASUSTek       | 1001PXD                     | [6de0cbb74c](https://linux-hardware.org/?probe=6de0cbb74c) | Oct 29, 2016 |
| ASUSTek       | 1001PXD                     | [439684c718](https://linux-hardware.org/?probe=439684c718) | Oct 29, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu 20.04     | 74        | 22.7%   |
| Ubuntu 18.04     | 30        | 9.2%    |
| Ubuntu 22.04     | 14        | 4.29%   |
| Fedora 37        | 8         | 2.45%   |
| Fedora 35        | 8         | 2.45%   |
| Ubuntu 21.04     | 7         | 2.15%   |
| Fedora 36        | 6         | 1.84%   |
| Arch             | 6         | 1.84%   |
| Zorin 15         | 5         | 1.53%   |
| ROSA R11         | 5         | 1.53%   |
| Pop!_OS 21.04    | 5         | 1.53%   |
| Manjaro          | 5         | 1.53%   |
| Linux Mint 20.1  | 5         | 1.53%   |
| Ubuntu 19.10     | 4         | 1.23%   |
| ROSA R10         | 4         | 1.23%   |
| Pop!_OS 22.04    | 4         | 1.23%   |
| OpenMandriva 4.3 | 4         | 1.23%   |
| Linux Mint 21    | 4         | 1.23%   |
| Linux Mint 20.3  | 4         | 1.23%   |
| Fedora 34        | 4         | 1.23%   |
| Fedora 33        | 4         | 1.23%   |
| Zorin 16         | 3         | 0.92%   |
| Ubuntu 20.10     | 3         | 0.92%   |
| Ubuntu 19.04     | 3         | 0.92%   |
| Pop!_OS 21.10    | 3         | 0.92%   |
| Pop!_OS 20.10    | 3         | 0.92%   |
| Manjaro 20.2     | 3         | 0.92%   |
| Linux Mint 20    | 3         | 0.92%   |
| Fedora 32        | 3         | 0.92%   |
| Arch Rolling     | 3         | 0.92%   |
| Xubuntu 22.04    | 2         | 0.61%   |
| Xubuntu 18.04    | 2         | 0.61%   |
| Ubuntu 22.10     | 2         | 0.61%   |
| ROSA R9          | 2         | 0.61%   |
| ROSA R8          | 2         | 0.61%   |
| ROSA R11.1       | 2         | 0.61%   |
| Pop!_OS 20.04    | 2         | 0.61%   |
| OpenMandriva 4.2 | 2         | 0.61%   |
| Linux Mint 21.1  | 2         | 0.61%   |
| Linux Mint 20.2  | 2         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 135       | 44.85%  |
| Fedora       | 30        | 9.97%   |
| Linux Mint   | 25        | 8.31%   |
| Pop!_OS      | 17        | 5.65%   |
| ROSA         | 14        | 4.65%   |
| Manjaro      | 12        | 3.99%   |
| Zorin        | 9         | 2.99%   |
| Arch         | 9         | 2.99%   |
| Xubuntu      | 7         | 2.33%   |
| OpenMandriva | 7         | 2.33%   |
| Endless      | 7         | 2.33%   |
| Debian       | 4         | 1.33%   |
| Kubuntu      | 3         | 1%      |
| Kali         | 3         | 1%      |
| KDE neon     | 2         | 0.66%   |
| Elementary   | 2         | 0.66%   |
| CentOS       | 2         | 0.66%   |
| BlackPanther | 2         | 0.66%   |
| ArcoLinux    | 2         | 0.66%   |
| Ubuntu MATE  | 1         | 0.33%   |
| RHEL         | 1         | 0.33%   |
| PureOS       | 1         | 0.33%   |
| openSUSE     | 1         | 0.33%   |
| Lubuntu      | 1         | 0.33%   |
| EndeavourOS  | 1         | 0.33%   |
| Devuan       | 1         | 0.33%   |
| Clear Linux  | 1         | 0.33%   |
| Artix        | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 10        | 2.86%   |
| 5.4.0-48-generic        | 8         | 2.29%   |
| 5.4.0-52-generic        | 5         | 1.43%   |
| 5.15.0-56-generic       | 5         | 1.43%   |
| 5.0.0-23-generic        | 5         | 1.43%   |
| 5.4.0-26-generic        | 4         | 1.14%   |
| 5.16.7-desktop-1omv4003 | 4         | 1.14%   |
| 5.8.0-59-generic        | 3         | 0.86%   |
| 5.8.0-44-generic        | 3         | 0.86%   |
| 5.4.0-72-generic        | 3         | 0.86%   |
| 5.4.0-65-generic        | 3         | 0.86%   |
| 5.4.0-58-generic        | 3         | 0.86%   |
| 5.3.0-46-generic        | 3         | 0.86%   |
| 5.3.0-42-generic        | 3         | 0.86%   |
| 5.3.0-26-generic        | 3         | 0.86%   |
| 5.15.0-57-generic       | 3         | 0.86%   |
| 5.15.0-50-generic       | 3         | 0.86%   |
| 5.15.0-41-generic       | 3         | 0.86%   |
| 5.11.0-34-generic       | 3         | 0.86%   |
| 6.1.18-200.fc37.x86_64  | 2         | 0.57%   |
| 6.1.14-200.fc37.x86_64  | 2         | 0.57%   |
| 6.1.10-200.fc37.x86_64  | 2         | 0.57%   |
| 6.0.8-300.fc37.x86_64   | 2         | 0.57%   |
| 6.0.0-kali3-amd64       | 2         | 0.57%   |
| 5.9.16-200.fc33.x86_64  | 2         | 0.57%   |
| 5.8.16-300.fc33.x86_64  | 2         | 0.57%   |
| 5.8.0-7642-generic      | 2         | 0.57%   |
| 5.8.0-63-generic        | 2         | 0.57%   |
| 5.8.0-53-generic        | 2         | 0.57%   |
| 5.8.0-41-generic        | 2         | 0.57%   |
| 5.4.2-1-MANJARO         | 2         | 0.57%   |
| 5.4.0-91-generic        | 2         | 0.57%   |
| 5.4.0-70-generic        | 2         | 0.57%   |
| 5.4.0-62-generic        | 2         | 0.57%   |
| 5.4.0-53-generic        | 2         | 0.57%   |
| 5.4.0-47-generic        | 2         | 0.57%   |
| 5.4.0-40-generic        | 2         | 0.57%   |
| 5.4.0-37-generic        | 2         | 0.57%   |
| 5.4.0-29-generic        | 2         | 0.57%   |
| 5.4.0-122-generic       | 2         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 69        | 20.47%  |
| 5.15.0  | 24        | 7.12%   |
| 5.8.0   | 23        | 6.82%   |
| 5.11.0  | 21        | 6.23%   |
| 4.15.0  | 20        | 5.93%   |
| 5.3.0   | 18        | 5.34%   |
| 5.13.0  | 12        | 3.56%   |
| 5.0.0   | 12        | 3.56%   |
| 5.19.0  | 6         | 1.78%   |
| 4.18.0  | 6         | 1.78%   |
| 5.16.7  | 4         | 1.19%   |
| 5.10.0  | 4         | 1.19%   |
| 6.1.14  | 3         | 0.89%   |
| 4.9.60  | 3         | 0.89%   |
| 6.1.7   | 2         | 0.59%   |
| 6.1.18  | 2         | 0.59%   |
| 6.1.12  | 2         | 0.59%   |
| 6.1.10  | 2         | 0.59%   |
| 6.0.8   | 2         | 0.59%   |
| 6.0.7   | 2         | 0.59%   |
| 6.0.2   | 2         | 0.59%   |
| 6.0.0   | 2         | 0.59%   |
| 5.9.16  | 2         | 0.59%   |
| 5.8.16  | 2         | 0.59%   |
| 5.7.10  | 2         | 0.59%   |
| 5.6.0   | 2         | 0.59%   |
| 5.4.2   | 2         | 0.59%   |
| 5.19.1  | 2         | 0.59%   |
| 5.16.18 | 2         | 0.59%   |
| 5.16.15 | 2         | 0.59%   |
| 5.15.2  | 2         | 0.59%   |
| 5.13.12 | 2         | 0.59%   |
| 4.9.20  | 2         | 0.59%   |
| 4.19.0  | 2         | 0.59%   |
| 4.18.16 | 2         | 0.59%   |
| 4.1.34  | 2         | 0.59%   |
| 6.2.6   | 1         | 0.3%    |
| 6.1.11  | 1         | 0.3%    |
| 6.1.0   | 1         | 0.3%    |
| 6.0.18  | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 72        | 22.09%  |
| 5.15    | 32        | 9.82%   |
| 5.8     | 27        | 8.28%   |
| 5.11    | 26        | 7.98%   |
| 5.3     | 20        | 6.13%   |
| 4.15    | 20        | 6.13%   |
| 5.13    | 15        | 4.6%    |
| 5.16    | 13        | 3.99%   |
| 5.0     | 12        | 3.68%   |
| 5.10    | 11        | 3.37%   |
| 6.1     | 10        | 3.07%   |
| 6.0     | 9         | 2.76%   |
| 5.19    | 9         | 2.76%   |
| 5.18    | 8         | 2.45%   |
| 4.18    | 8         | 2.45%   |
| 4.9     | 6         | 1.84%   |
| 5.9     | 5         | 1.53%   |
| 5.7     | 4         | 1.23%   |
| 5.14    | 4         | 1.23%   |
| 5.6     | 3         | 0.92%   |
| 5.17    | 3         | 0.92%   |
| 4.19    | 3         | 0.92%   |
| 4.1     | 2         | 0.61%   |
| 6.2     | 1         | 0.31%   |
| 5.5     | 1         | 0.31%   |
| 5.12    | 1         | 0.31%   |
| 4.4     | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 287       | 96.63%  |
| i686   | 10        | 3.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 166       | 54.61%  |
| KDE5       | 35        | 11.51%  |
| Unknown    | 35        | 11.51%  |
| X-Cinnamon | 22        | 7.24%   |
| XFCE       | 18        | 5.92%   |
| KDE4       | 11        | 3.62%   |
| KDE        | 4         | 1.32%   |
| Cinnamon   | 4         | 1.32%   |
| Pantheon   | 2         | 0.66%   |
| MATE       | 2         | 0.66%   |
| LXQt       | 2         | 0.66%   |
| Trinity    | 1         | 0.33%   |
| LXDE       | 1         | 0.33%   |
| i3         | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 239       | 78.62%  |
| Wayland | 42        | 13.82%  |
| Unknown | 21        | 6.91%   |
| Tty     | 2         | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 155       | 51.16%  |
| GDM     | 58        | 19.14%  |
| GDM3    | 27        | 8.91%   |
| SDDM    | 25        | 8.25%   |
| LightDM | 17        | 5.61%   |
| KDM     | 11        | 3.63%   |
| TDM     | 10        | 3.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IL   | 119       | 38.89%  |
| en_US   | 96        | 31.37%  |
| Unknown | 44        | 14.38%  |
| ru_RU   | 21        | 6.86%   |
| he_IL   | 12        | 3.92%   |
| en_GB   | 3         | 0.98%   |
| C       | 3         | 0.98%   |
| fr_FR   | 2         | 0.65%   |
| en_AG   | 2         | 0.65%   |
| es_ES   | 1         | 0.33%   |
| en_NZ   | 1         | 0.33%   |
| en_CA   | 1         | 0.33%   |
| en_AU   | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 179       | 58.31%  |
| BIOS | 128       | 41.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 241       | 80.6%   |
| Btrfs   | 21        | 7.02%   |
| Unknown | 14        | 4.68%   |
| Overlay | 13        | 4.35%   |
| Xfs     | 7         | 2.34%   |
| Ext3    | 2         | 0.67%   |
| Ext2    | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 161       | 52.61%  |
| GPT     | 122       | 39.87%  |
| MBR     | 23        | 7.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 277       | 92.95%  |
| Yes       | 21        | 7.05%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 220       | 73.83%  |
| Yes       | 78        | 26.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 88        | 29.63%  |
| Dell                | 66        | 22.22%  |
| ASUSTek Computer    | 50        | 16.84%  |
| Hewlett-Packard     | 47        | 15.82%  |
| Acer                | 10        | 3.37%   |
| Samsung Electronics | 5         | 1.68%   |
| Apple               | 5         | 1.68%   |
| Toshiba             | 4         | 1.35%   |
| Fujitsu             | 4         | 1.35%   |
| LG Electronics      | 3         | 1.01%   |
| Timi                | 2         | 0.67%   |
| Fujitsu Siemens     | 2         | 0.67%   |
| System76            | 1         | 0.34%   |
| Purism              | 1         | 0.34%   |
| Notebook            | 1         | 0.34%   |
| MSI                 | 1         | 0.34%   |
| IP3 Tech            | 1         | 0.34%   |
| HUAWEI              | 1         | 0.34%   |
| Heptagon Systems    | 1         | 0.34%   |
| GPD                 | 1         | 0.34%   |
| Gigabyte Technology | 1         | 0.34%   |
| Alienware           | 1         | 0.34%   |
| Unknown             | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 5         | 1.68%   |
| Lenovo IdeaPad 5 14ITL05 82FE                                                            | 3         | 1.01%   |
| HP Pavilion Notebook                                                                     | 3         | 1.01%   |
| HP Compaq Presario CQ61                                                                  | 3         | 1.01%   |
| ASUS UX331UA                                                                             | 3         | 1.01%   |
| Lenovo V14-IIL 82C4                                                                      | 2         | 0.67%   |
| Lenovo IdeaPad Y700-15ISK 80NV                                                           | 2         | 0.67%   |
| Lenovo IdeaPad L340-15IWL 81LG                                                           | 2         | 0.67%   |
| Lenovo G50-80 80L0                                                                       | 2         | 0.67%   |
| HP ZBook 15 G3                                                                           | 2         | 0.67%   |
| HP ProBook 430 G6                                                                        | 2         | 0.67%   |
| HP EliteBook 840 G5                                                                      | 2         | 0.67%   |
| Fujitsu LIFEBOOK AH530                                                                   | 2         | 0.67%   |
| Dell XPS 15 9570                                                                         | 2         | 0.67%   |
| Dell Latitude E6420                                                                      | 2         | 0.67%   |
| Dell Latitude E6330                                                                      | 2         | 0.67%   |
| Dell Latitude E4300                                                                      | 2         | 0.67%   |
| Dell Latitude 7400                                                                       | 2         | 0.67%   |
| Dell Latitude 5410                                                                       | 2         | 0.67%   |
| Dell Inspiron 3593                                                                       | 2         | 0.67%   |
| Dell Inspiron 3542                                                                       | 2         | 0.67%   |
| Dell Inspiron 13-5378                                                                    | 2         | 0.67%   |
| ASUS ZenBook UX425EA_UX425EA                                                             | 2         | 0.67%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR                                                     | 2         | 0.67%   |
| ASUS UX430UNR                                                                            | 2         | 0.67%   |
| ASUS N550JV                                                                              | 2         | 0.67%   |
| Acer Aspire A715-72G                                                                     | 2         | 0.67%   |
| Toshiba Satellite P50t-B-10T                                                             | 1         | 0.34%   |
| Toshiba Satellite L755                                                                   | 1         | 0.34%   |
| Toshiba Satellite A200                                                                   | 1         | 0.34%   |
| Toshiba PORTEGE R700                                                                     | 1         | 0.34%   |
| Timi TM1701                                                                              | 1         | 0.34%   |
| Timi RedmiBook 16                                                                        | 1         | 0.34%   |
| System76 Gazelle                                                                         | 1         | 0.34%   |
| Samsung N248P                                                                            | 1         | 0.34%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV                                                 | 1         | 0.34%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.34%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                                                      | 1         | 0.34%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B                                               | 1         | 0.34%   |
| Purism Librem 14                                                                         | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 44        | 14.81%  |
| Dell Latitude     | 25        | 8.42%   |
| Lenovo IdeaPad    | 21        | 7.07%   |
| Dell Inspiron     | 19        | 6.4%    |
| ASUS VivoBook     | 11        | 3.7%    |
| HP Pavilion       | 10        | 3.37%   |
| Dell Vostro       | 10        | 3.37%   |
| Dell XPS          | 9         | 3.03%   |
| Acer Aspire       | 8         | 2.69%   |
| ASUS ROG          | 7         | 2.36%   |
| Lenovo Legion     | 6         | 2.02%   |
| HP ZBook          | 6         | 2.02%   |
| HP ProBook        | 6         | 2.02%   |
| HP EliteBook      | 5         | 1.68%   |
| ASUS ZenBook      | 5         | 1.68%   |
| Unknown           | 5         | 1.68%   |
| HP Laptop         | 4         | 1.35%   |
| Fujitsu LIFEBOOK  | 4         | 1.35%   |
| Toshiba Satellite | 3         | 1.01%   |
| Lenovo G50-80     | 3         | 1.01%   |
| HP Compaq         | 3         | 1.01%   |
| ASUS UX331UA      | 3         | 1.01%   |
| ASUS ASUS         | 3         | 1.01%   |
| Lenovo Yoga       | 2         | 0.67%   |
| Lenovo V14-IIL    | 2         | 0.67%   |
| HP ENVY           | 2         | 0.67%   |
| ASUS UX430UNR     | 2         | 0.67%   |
| ASUS N550JV       | 2         | 0.67%   |
| Toshiba PORTEGE   | 1         | 0.34%   |
| Timi TM1701       | 1         | 0.34%   |
| Timi RedmiBook    | 1         | 0.34%   |
| System76 Gazelle  | 1         | 0.34%   |
| Samsung N248P     | 1         | 0.34%   |
| Samsung 3570R     | 1         | 0.34%   |
| Samsung 355V4C    | 1         | 0.34%   |
| Samsung 350V5C    | 1         | 0.34%   |
| Samsung 300V3A    | 1         | 0.34%   |
| Purism Librem     | 1         | 0.34%   |
| Notebook N2x0WU   | 1         | 0.34%   |
| MSI Summit        | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 43        | 14.48%  |
| 2020 | 37        | 12.46%  |
| 2018 | 32        | 10.77%  |
| 2016 | 22        | 7.41%   |
| 2015 | 22        | 7.41%   |
| 2021 | 21        | 7.07%   |
| 2017 | 21        | 7.07%   |
| 2012 | 17        | 5.72%   |
| 2011 | 16        | 5.39%   |
| 2010 | 12        | 4.04%   |
| 2014 | 11        | 3.7%    |
| 2008 | 11        | 3.7%    |
| 2013 | 9         | 3.03%   |
| 2022 | 7         | 2.36%   |
| 2009 | 7         | 2.36%   |
| 2007 | 6         | 2.02%   |
| 2006 | 2         | 0.67%   |
| 2023 | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 297       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 261       | 87.29%  |
| Enabled  | 38        | 12.71%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 296       | 99.66%  |
| Yes  | 1         | 0.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 75        | 25.25%  |
| 16.01-24.0  | 68        | 22.9%   |
| 32.01-64.0  | 45        | 15.15%  |
| 8.01-16.0   | 40        | 13.47%  |
| 3.01-4.0    | 37        | 12.46%  |
| 1.01-2.0    | 15        | 5.05%   |
| 64.01-256.0 | 7         | 2.36%   |
| 24.01-32.0  | 4         | 1.35%   |
| 2.01-3.0    | 4         | 1.35%   |
| 0.51-1.0    | 2         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 83        | 25.46%  |
| 2.01-3.0   | 80        | 24.54%  |
| 4.01-8.0   | 55        | 16.87%  |
| 3.01-4.0   | 55        | 16.87%  |
| 8.01-16.0  | 32        | 9.82%   |
| 0.51-1.0   | 14        | 4.29%   |
| 16.01-24.0 | 4         | 1.23%   |
| 0.01-0.5   | 3         | 0.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 244       | 81.61%  |
| 2      | 50        | 16.72%  |
| 3      | 2         | 0.67%   |
| 0      | 2         | 0.67%   |
| 4      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 204       | 68.69%  |
| Yes       | 93        | 31.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 241       | 80.6%   |
| No        | 58        | 19.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 291       | 97.98%  |
| No        | 6         | 2.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 243       | 80.73%  |
| No        | 58        | 19.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Israel  | 297       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Tel Aviv              | 141       | 43.38%  |
| Ramat Gan             | 29        | 8.92%   |
| Jerusalem             | 12        | 3.69%   |
| Petaẖ Tiqwa         | 11        | 3.38%   |
| Herzliya              | 10        | 3.08%   |
| Rishon LeZiyyon       | 9         | 2.77%   |
| Haifa                 | 9         | 2.77%   |
| Netanya               | 8         | 2.46%   |
| Givatayim             | 8         | 2.46%   |
| Rehovot               | 6         | 1.85%   |
| Rishon LeTsiyyon      | 5         | 1.54%   |
| Ramat HaSharon        | 5         | 1.54%   |
| Nahariya              | 5         | 1.54%   |
| Holon                 | 5         | 1.54%   |
| Kiryat Ono            | 4         | 1.23%   |
| Givat Shmuel          | 4         | 1.23%   |
| Ashquelon             | 4         | 1.23%   |
| Raanana               | 3         | 0.92%   |
| Kfar Saba             | 3         | 0.92%   |
| Hadera                | 3         | 0.92%   |
| Bet Shemesh           | 3         | 0.92%   |
| Yavne                 | 2         | 0.62%   |
| Yaqum                 | 2         | 0.62%   |
| Ramla                 | 2         | 0.62%   |
| Hod HaSharon          | 2         | 0.62%   |
| Beersheba             | 2         | 0.62%   |
| Yehud                 | 1         | 0.31%   |
| Tiberias              | 1         | 0.31%   |
| Tel Mond              | 1         | 0.31%   |
| Shelomi               | 1         | 0.31%   |
| Sha`ar Ha`Amaqim      | 1         | 0.31%   |
| Sde Nehemya           | 1         | 0.31%   |
| Qiryat Moẕqin       | 1         | 0.31%   |
| Qiryat Bialik         | 1         | 0.31%   |
| Qiryat Ata            | 1         | 0.31%   |
| Pardes Hanna Karkur   | 1         | 0.31%   |
| Ofakim                | 1         | 0.31%   |
| Ness Ziona            | 1         | 0.31%   |
| Modiin Makkabbim Reut | 1         | 0.31%   |
| Mazkeret Batya        | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 60        | 84     | 17.7%   |
| WDC                 | 39        | 41     | 11.5%   |
| Seagate             | 31        | 38     | 9.14%   |
| SK hynix            | 29        | 41     | 8.55%   |
| Toshiba             | 27        | 29     | 7.96%   |
| SanDisk             | 27        | 33     | 7.96%   |
| Intel               | 19        | 25     | 5.6%    |
| Micron Technology   | 15        | 18     | 4.42%   |
| Kingston            | 15        | 18     | 4.42%   |
| HGST                | 14        | 15     | 4.13%   |
| Hitachi             | 9         | 9      | 2.65%   |
| Crucial             | 8         | 16     | 2.36%   |
| Unknown             | 7         | 7      | 2.06%   |
| KIOXIA              | 7         | 7      | 2.06%   |
| StoreJet            | 4         | 4      | 1.18%   |
| JMicron Technology  | 4         | 4      | 1.18%   |
| Transcend           | 3         | 4      | 0.88%   |
| Fujitsu             | 3         | 3      | 0.88%   |
| Apple               | 3         | 3      | 0.88%   |
| A-DATA Technology   | 3         | 4      | 0.88%   |
| LITEON              | 2         | 2      | 0.59%   |
| faspeed             | 2         | 3      | 0.59%   |
| China               | 2         | 3      | 0.59%   |
| Apacer              | 2         | 2      | 0.59%   |
| SPCC                | 1         | 1      | 0.29%   |
| LITEONIT            | 1         | 1      | 0.29%   |
| Lexar               | 1         | 1      | 0.29%   |
| ADATA Technology    | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                        | 9         | 2.56%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 1.99%   |
| SK hynix NVMe SSD Drive 256GB                       | 5         | 1.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 1.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 1.42%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 1.14%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 1.14%   |
| Intel NVMe SSD Drive 512GB                          | 4         | 1.14%   |
| HGST HTS721010A9E630 1TB                            | 4         | 1.14%   |
| Crucial CT500MX500SSD1 500GB                        | 4         | 1.14%   |
| Toshiba NVMe SSD Drive 512GB                        | 3         | 0.85%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.85%   |
| SK hynix PC401 NVMe 512GB                           | 3         | 0.85%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 0.85%   |
| SanDisk SSD PLUS 240GB                              | 3         | 0.85%   |
| SanDisk NVMe SSD Drive 256GB                        | 3         | 0.85%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 0.85%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 3         | 0.85%   |
| Intel NVMe SSD Drive 256GB                          | 3         | 0.85%   |
| HGST HTS541010A9E680 1TB                            | 3         | 0.85%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 2         | 0.57%   |
| WDC WD5000BPKT-75PK4T0 500GB                        | 2         | 0.57%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 2         | 0.57%   |
| WDC PC SN730 NVMe 512GB                             | 2         | 0.57%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                  | 2         | 0.57%   |
| WDC PC SN530 NVMe 256GB                             | 2         | 0.57%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.57%   |
| Toshiba KXG6AZNV1T02 1TB                            | 2         | 0.57%   |
| StoreJet Transcend 256GB SSD                        | 2         | 0.57%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB             | 2         | 0.57%   |
| SK hynix SC311 SATA 256GB SSD                       | 2         | 0.57%   |
| SanDisk SD8SN8U512G1002 512GB SSD                   | 2         | 0.57%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.57%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.57%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 0.57%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                      | 2         | 0.57%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                      | 2         | 0.57%   |
| Micron MTFDKBA1T0TFH 1024GB                         | 2         | 0.57%   |
| Micron MTFDHBA256TCK-1AS1AABHA 256GB                | 2         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 38     | 32.98%  |
| WDC                 | 19        | 19     | 20.21%  |
| Toshiba             | 16        | 16     | 17.02%  |
| HGST                | 14        | 15     | 14.89%  |
| Hitachi             | 9         | 9      | 9.57%   |
| Fujitsu             | 3         | 3      | 3.19%   |
| Unknown             | 1         | 1      | 1.06%   |
| Samsung Electronics | 1         | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 20     | 19.61%  |
| SanDisk             | 16        | 20     | 15.69%  |
| Kingston            | 12        | 15     | 11.76%  |
| SK hynix            | 9         | 19     | 8.82%   |
| Crucial             | 8         | 16     | 7.84%   |
| Micron Technology   | 7         | 7      | 6.86%   |
| WDC                 | 4         | 4      | 3.92%   |
| Transcend           | 3         | 4      | 2.94%   |
| Toshiba             | 3         | 3      | 2.94%   |
| Apple               | 3         | 3      | 2.94%   |
| A-DATA Technology   | 3         | 4      | 2.94%   |
| StoreJet            | 2         | 2      | 1.96%   |
| LITEON              | 2         | 2      | 1.96%   |
| JMicron Technology  | 2         | 2      | 1.96%   |
| Intel               | 2         | 2      | 1.96%   |
| China               | 2         | 3      | 1.96%   |
| Apacer              | 2         | 2      | 1.96%   |
| LITEONIT            | 1         | 1      | 0.98%   |
| faspeed             | 1         | 1      | 0.98%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 132       | 174    | 40%     |
| SSD     | 98        | 130    | 29.7%   |
| HDD     | 90        | 102    | 27.27%  |
| MMC     | 5         | 5      | 1.52%   |
| Unknown | 5         | 6      | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 173       | 223    | 53.23%  |
| NVMe | 132       | 174    | 40.62%  |
| SAS  | 15        | 15     | 4.62%   |
| MMC  | 5         | 5      | 1.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 128       | 160    | 68.45%  |
| 0.51-1.0   | 55        | 68     | 29.41%  |
| 1.01-2.0   | 4         | 4      | 2.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 96        | 31.37%  |
| 251-500        | 89        | 29.08%  |
| 501-1000       | 47        | 15.36%  |
| 51-100         | 19        | 6.21%   |
| 1-20           | 16        | 5.23%   |
| 1001-2000      | 13        | 4.25%   |
| Unknown        | 10        | 3.27%   |
| 21-50          | 9         | 2.94%   |
| 2001-3000      | 5         | 1.63%   |
| More than 3000 | 2         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 110       | 34.92%  |
| 21-50     | 65        | 20.63%  |
| 101-250   | 54        | 17.14%  |
| 51-100    | 44        | 13.97%  |
| 251-500   | 23        | 7.3%    |
| Unknown   | 10        | 3.17%   |
| 501-1000  | 6         | 1.9%    |
| 1001-2000 | 3         | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E380 500GB            | 2         | 2      | 8.7%    |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 1      | 4.35%   |
| WDC WD2500BEVT-24A23T0 250GB          | 1         | 1      | 4.35%   |
| WDC WD1600BJKT-75F4T0 160GB           | 1         | 1      | 4.35%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 4.35%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 4.35%   |
| Toshiba MK5075GSX 500GB               | 1         | 1      | 4.35%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 4.35%   |
| Toshiba MK1646GSX 160GB               | 1         | 1      | 4.35%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD | 1         | 5      | 4.35%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 4.35%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 4.35%   |
| Seagate ST9120817AS 120GB             | 1         | 1      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 4.35%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 2      | 4.35%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 4.35%   |
| Intel SSDSCKKF256H6 SATA 256GB        | 1         | 1      | 4.35%   |
| Hitachi HTS545025B9A300 250GB         | 1         | 1      | 4.35%   |
| Hitachi HTS542516K9SA00 160GB         | 1         | 1      | 4.35%   |
| HGST HCC545050A7E380 500GB            | 1         | 1      | 4.35%   |
| Fujitsu MHY2160BH 160GB               | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 5         | 5      | 22.73%  |
| Seagate  | 4         | 6      | 18.18%  |
| WDC      | 3         | 3      | 13.64%  |
| HGST     | 3         | 3      | 13.64%  |
| SK hynix | 2         | 6      | 9.09%   |
| Hitachi  | 2         | 2      | 9.09%   |
| SanDisk  | 1         | 1      | 4.55%   |
| Intel    | 1         | 1      | 4.55%   |
| Fujitsu  | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 27.78%  |
| Seagate | 4         | 6      | 22.22%  |
| WDC     | 3         | 3      | 16.67%  |
| HGST    | 3         | 3      | 16.67%  |
| Hitachi | 2         | 2      | 11.11%  |
| Fujitsu | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 20     | 78.95%  |
| SSD  | 4         | 8      | 21.05%  |

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
| Detected | 168       | 225    | 53.85%  |
| Works    | 125       | 164    | 40.06%  |
| Malfunc  | 19        | 28     | 6.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 226       | 63.48%  |
| Samsung Electronics          | 42        | 11.8%   |
| SanDisk                      | 26        | 7.3%    |
| SK hynix                     | 20        | 5.62%   |
| Toshiba America Info Systems | 9         | 2.53%   |
| AMD                          | 9         | 2.53%   |
| Micron Technology            | 8         | 2.25%   |
| KIOXIA                       | 6         | 1.69%   |
| Kingston Technology Company  | 3         | 0.84%   |
| Nvidia                       | 2         | 0.56%   |
| VIA Technologies             | 1         | 0.28%   |
| Union Memory (Shenzhen)      | 1         | 0.28%   |
| Shenzhen Longsys Electronics | 1         | 0.28%   |
| Realtek Semiconductor        | 1         | 0.28%   |
| ADATA Technology             | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 42        | 11.05%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 21        | 5.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 21        | 5.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 15        | 3.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 3.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 3.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 12        | 3.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 2.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 2.37%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 9         | 2.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 2.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 2.37%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 2.37%   |
| Micron NVMe Storage Controller                                                 | 8         | 2.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 8         | 2.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 2.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.84%   |
| SK hynix Non-Volatile memory controller                                        | 6         | 1.58%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 1.58%   |
| Intel SSD 660P Series                                                          | 6         | 1.58%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.58%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 1.32%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 5         | 1.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 1.32%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.32%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 1.05%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 1.05%   |
| Intel Non-Volatile memory controller                                           | 4         | 1.05%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 3         | 0.79%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 0.79%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 0.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.79%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 196       | 52.55%  |
| NVMe | 132       | 35.39%  |
| RAID | 32        | 8.58%   |
| IDE  | 13        | 3.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 279       | 93.94%  |
| AMD          | 17        | 5.72%   |
| CentaurHauls | 1         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 17        | 5.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 10        | 3.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 8         | 2.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 8         | 2.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 7         | 2.36%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 7         | 2.36%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 7         | 2.36%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 2.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 6         | 2.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 2.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 5         | 1.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 5         | 1.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 5         | 1.68%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 4         | 1.35%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 4         | 1.35%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 4         | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 1.35%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 4         | 1.35%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 3         | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 1.01%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 1.01%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 1.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.01%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 3         | 1.01%   |
| Intel Atom CPU N455 @ 1.66GHz               | 3         | 1.01%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 1.01%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 2         | 0.67%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 2         | 0.67%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 2         | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.67%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 0.67%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 2         | 0.67%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 0.67%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 2         | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.67%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 2         | 0.67%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 101       | 34.01%  |
| Intel Core i5           | 75        | 25.25%  |
| Other                   | 34        | 11.45%  |
| Intel Core i3           | 26        | 8.75%   |
| Intel Core 2 Duo        | 9         | 3.03%   |
| Intel Core i9           | 6         | 2.02%   |
| Intel Celeron           | 6         | 2.02%   |
| Intel Pentium Dual-Core | 5         | 1.68%   |
| Intel Atom              | 4         | 1.35%   |
| AMD Ryzen 5             | 4         | 1.35%   |
| Intel Pentium Dual      | 3         | 1.01%   |
| Intel Pentium           | 3         | 1.01%   |
| AMD Ryzen 9             | 3         | 1.01%   |
| AMD Ryzen 7             | 3         | 1.01%   |
| Intel Xeon              | 2         | 0.67%   |
| Intel Genuine           | 2         | 0.67%   |
| AMD Ryzen 7 PRO         | 2         | 0.67%   |
| AMD A6                  | 2         | 0.67%   |
| Intel Core M            | 1         | 0.34%   |
| Intel Core 2            | 1         | 0.34%   |
| Intel Celeron Dual-Core | 1         | 0.34%   |
| CentaurHauls VIA C7     | 1         | 0.34%   |
| AMD Turion 64 X2 Mobile | 1         | 0.34%   |
| AMD A8                  | 1         | 0.34%   |
| AMD A10                 | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 123       | 41.41%  |
| 2       | 121       | 40.74%  |
| 6       | 20        | 6.73%   |
| 8       | 19        | 6.4%    |
| 1       | 7         | 2.36%   |
| 14      | 3         | 1.01%   |
| 16      | 1         | 0.34%   |
| 12      | 1         | 0.34%   |
| 10      | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 296       | 99.66%  |
| Unknown | 1         | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 259       | 86.91%  |
| 1       | 38        | 12.75%  |
| Unknown | 1         | 0.34%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 289       | 97.31%  |
| Unknown        | 6         | 2.02%   |
| 32-bit         | 2         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 24.12%  |
| 0x806ea    | 22        | 7.07%   |
| 0x806c1    | 18        | 5.79%   |
| 0x806ec    | 17        | 5.47%   |
| 0x406e3    | 16        | 5.14%   |
| 0x206a7    | 14        | 4.5%    |
| 0x306d4    | 11        | 3.54%   |
| 0x306a9    | 11        | 3.54%   |
| 0x706e5    | 10        | 3.22%   |
| 0xa0652    | 9         | 2.89%   |
| 0x806e9    | 9         | 2.89%   |
| 0x506e3    | 9         | 2.89%   |
| 0x20655    | 8         | 2.57%   |
| 0x906ea    | 7         | 2.25%   |
| 0x40651    | 7         | 2.25%   |
| 0x1067a    | 7         | 2.25%   |
| 0x806eb    | 6         | 1.93%   |
| 0x906ed    | 5         | 1.61%   |
| 0x6fd      | 5         | 1.61%   |
| 0x306c3    | 5         | 1.61%   |
| 0x906a3    | 4         | 1.29%   |
| 0x806d1    | 3         | 0.96%   |
| 0x106ca    | 3         | 0.96%   |
| 0x906e9    | 2         | 0.64%   |
| 0x706a1    | 2         | 0.64%   |
| 0x6fa      | 2         | 0.64%   |
| 0x10676    | 2         | 0.64%   |
| 0x0a50000c | 2         | 0.64%   |
| 0x08600104 | 2         | 0.64%   |
| 0x08108109 | 2         | 0.64%   |
| 0x08108102 | 2         | 0.64%   |
| 0xa0660    | 1         | 0.32%   |
| 0x90672    | 1         | 0.32%   |
| 0x806c2    | 1         | 0.32%   |
| 0x6f6      | 1         | 0.32%   |
| 0x6f4      | 1         | 0.32%   |
| 0x506c9    | 1         | 0.32%   |
| 0x106e5    | 1         | 0.32%   |
| 0x106c2    | 1         | 0.32%   |
| 0x0a404102 | 1         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 89        | 29.97%  |
| Skylake          | 28        | 9.43%   |
| TigerLake        | 24        | 8.08%   |
| SandyBridge      | 16        | 5.39%   |
| IvyBridge        | 16        | 5.39%   |
| Haswell          | 16        | 5.39%   |
| Icelake          | 15        | 5.05%   |
| Broadwell        | 14        | 4.71%   |
| Penryn           | 13        | 4.38%   |
| CometLake        | 12        | 4.04%   |
| Westmere         | 10        | 3.37%   |
| Core             | 9         | 3.03%   |
| Unknown          | 8         | 2.69%   |
| Alderlake Hybrid | 5         | 1.68%   |
| Zen+             | 4         | 1.35%   |
| Zen 2            | 3         | 1.01%   |
| Bonnell          | 3         | 1.01%   |
| Zen 3            | 2         | 0.67%   |
| Puma             | 2         | 0.67%   |
| Piledriver       | 2         | 0.67%   |
| Goldmont plus    | 2         | 0.67%   |
| Silvermont       | 1         | 0.34%   |
| Nehalem          | 1         | 0.34%   |
| K8 Hammer        | 1         | 0.34%   |
| Goldmont         | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 268       | 68.19%  |
| Nvidia            | 97        | 24.68%  |
| AMD               | 26        | 6.62%   |
| VIA Technologies  | 1         | 0.25%   |
| ASPEED Technology | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 30        | 7.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 21        | 5.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 19        | 4.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 15        | 3.75%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 15        | 3.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 14        | 3.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 14        | 3.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 14        | 3.5%    |
| Intel HD Graphics 5500                                                    | 12        | 3%      |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 11        | 2.75%   |
| Intel HD Graphics 620                                                     | 10        | 2.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 10        | 2.5%    |
| Intel Core Processor Integrated Graphics Controller                       | 10        | 2.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 10        | 2.5%    |
| Intel HD Graphics 530                                                     | 9         | 2.25%   |
| Nvidia GP108M [GeForce MX150]                                             | 7         | 1.75%   |
| Intel Iris Plus Graphics G7                                               | 7         | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 6         | 1.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 5         | 1.25%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 5         | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 5         | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 5         | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 4         | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 1%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 1%      |
| Intel Alder Lake-P Integrated Graphics Controller                         | 4         | 1%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 1%      |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 3         | 0.75%   |
| Nvidia GP108M [GeForce MX230]                                             | 3         | 0.75%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 3         | 0.75%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 3         | 0.75%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 0.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 3         | 0.75%   |
| AMD Renoir                                                                | 3         | 0.75%   |
| Nvidia TU117M [GeForce MX450]                                             | 2         | 0.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 0.5%    |
| Nvidia TU117GLM [Quadro T500 Mobile]                                      | 2         | 0.5%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 2         | 0.5%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 0.5%    |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                          | 2         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 177       | 59.6%   |
| Intel + Nvidia | 82        | 27.61%  |
| 1 x AMD        | 12        | 4.04%   |
| 1 x Nvidia     | 9         | 3.03%   |
| Intel + AMD    | 8         | 2.69%   |
| AMD + Nvidia   | 5         | 1.68%   |
| 2 x Intel      | 1         | 0.34%   |
| 2 x AMD        | 1         | 0.34%   |
| 1 x VIA        | 1         | 0.34%   |
| 1 x ASPEED     | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 243       | 81%     |
| Proprietary | 50        | 16.67%  |
| Unknown     | 7         | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 218       | 72.43%  |
| 3.01-4.0   | 26        | 8.64%   |
| 1.01-2.0   | 24        | 7.97%   |
| 0.01-0.5   | 15        | 4.98%   |
| 5.01-6.0   | 6         | 1.99%   |
| 0.51-1.0   | 6         | 1.99%   |
| 7.01-8.0   | 5         | 1.66%   |
| 2.01-3.0   | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 68        | 18.68%  |
| Chimei Innolux          | 51        | 14.01%  |
| LG Display              | 48        | 13.19%  |
| BOE                     | 46        | 12.64%  |
| Dell                    | 32        | 8.79%   |
| Samsung Electronics     | 29        | 7.97%   |
| Lenovo                  | 17        | 4.67%   |
| Sharp                   | 12        | 3.3%    |
| Goldstar                | 9         | 2.47%   |
| InfoVision              | 7         | 1.92%   |
| Chi Mei Optoelectronics | 7         | 1.92%   |
| Hewlett-Packard         | 6         | 1.65%   |
| LG Philips              | 5         | 1.37%   |
| Philips                 | 4         | 1.1%    |
| Apple                   | 4         | 1.1%    |
| CSO                     | 3         | 0.82%   |
| Toshiba                 | 2         | 0.55%   |
| ASUSTek Computer        | 2         | 0.55%   |
| VOR                     | 1         | 0.27%   |
| STD                     | 1         | 0.27%   |
| Seiko/Epson             | 1         | 0.27%   |
| RIS                     | 1         | 0.27%   |
| PANDA                   | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| LGD                     | 1         | 0.27%   |
| CPT                     | 1         | 0.27%   |
| BOE Technology Group    | 1         | 0.27%   |
| AOC                     | 1         | 0.27%   |
| Ancor Communications    | 1         | 0.27%   |
| Acer                    | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 1.61%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 6         | 1.61%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 4         | 1.08%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 4         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 1.08%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 3         | 0.81%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 3         | 0.81%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 293x165mm 13.2-inch           | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO102D 1920x1080 293x165mm 13.2-inch           | 3         | 0.81%   |
| Toshiba LCD Monitor LCD2207 1280x800 287x180mm 13.3-inch                 | 2         | 0.54%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.54%   |
| Samsung Electronics LC34G55T SAM7119 3440x1440 798x334mm 34.1-inch       | 2         | 0.54%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 2         | 0.54%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 2         | 0.54%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch             | 2         | 0.54%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 2         | 0.54%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch             | 2         | 0.54%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.54%   |
| Lenovo E27q-20 LEN62D0 2560x1440 597x336mm 27.0-inch                     | 2         | 0.54%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 2         | 0.54%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch              | 2         | 0.54%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                     | 2         | 0.54%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                        | 2         | 0.54%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                       | 2         | 0.54%   |
| Dell P2719H DEL4184 1920x1080 600x340mm 27.2-inch                        | 2         | 0.54%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                        | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch         | 2         | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.54%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.54%   |
| BOE LCD Monitor BOE0846 1920x1080 294x165mm 13.3-inch                    | 2         | 0.54%   |
| BOE LCD Monitor BOE07BC 1920x1080 309x173mm 13.9-inch                    | 2         | 0.54%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 2         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 165       | 50.77%  |
| 1366x768 (WXGA)    | 72        | 22.15%  |
| 3840x2160 (4K)     | 22        | 6.77%   |
| 2560x1440 (QHD)    | 16        | 4.92%   |
| 1280x800 (WXGA)    | 13        | 4%      |
| 1920x1200 (WUXGA)  | 7         | 2.15%   |
| 1600x900 (HD+)     | 5         | 1.54%   |
| 3440x1440          | 3         | 0.92%   |
| 2560x1600          | 3         | 0.92%   |
| 1440x900 (WXGA+)   | 3         | 0.92%   |
| 3200x1800 (QHD+)   | 2         | 0.62%   |
| 2560x1080          | 2         | 0.62%   |
| 1680x1050 (WSXGA+) | 2         | 0.62%   |
| 1024x768 (XGA)     | 2         | 0.62%   |
| 3840x1080          | 1         | 0.31%   |
| 3456x2160          | 1         | 0.31%   |
| 2880x1800          | 1         | 0.31%   |
| 2160x1440          | 1         | 0.31%   |
| 1280x768           | 1         | 0.31%   |
| 1280x1024 (SXGA)   | 1         | 0.31%   |
| 1024x600           | 1         | 0.31%   |
| Unknown            | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 139       | 38.29%  |
| 13      | 68        | 18.73%  |
| 14      | 45        | 12.4%   |
| 24      | 25        | 6.89%   |
| 27      | 20        | 5.51%   |
| 23      | 13        | 3.58%   |
| 17      | 10        | 2.75%   |
| 21      | 8         | 2.2%    |
| 12      | 8         | 2.2%    |
| 34      | 4         | 1.1%    |
| 16      | 4         | 1.1%    |
| 40      | 3         | 0.83%   |
| 11      | 3         | 0.83%   |
| Unknown | 3         | 0.83%   |
| 31      | 2         | 0.55%   |
| 22      | 2         | 0.55%   |
| 19      | 2         | 0.55%   |
| 84      | 1         | 0.28%   |
| 25      | 1         | 0.28%   |
| 10      | 1         | 0.28%   |
| 8       | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 217       | 60.45%  |
| 501-600     | 53        | 14.76%  |
| 201-300     | 48        | 13.37%  |
| 351-400     | 15        | 4.18%   |
| 401-500     | 10        | 2.79%   |
| 701-800     | 4         | 1.11%   |
| 601-700     | 4         | 1.11%   |
| 801-900     | 3         | 0.84%   |
| Unknown     | 3         | 0.84%   |
| 1501-2000   | 1         | 0.28%   |
| 101-200     | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 257       | 85.38%  |
| 16/10   | 30        | 9.97%   |
| 21/9    | 4         | 1.33%   |
| 3/2     | 3         | 1%      |
| Unknown | 3         | 1%      |
| 5/4     | 2         | 0.66%   |
| 4/3     | 2         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 139       | 38.5%   |
| 81-90          | 80        | 22.16%  |
| 201-250        | 42        | 11.63%  |
| 71-80          | 32        | 8.86%   |
| 301-350        | 20        | 5.54%   |
| 61-70          | 8         | 2.22%   |
| 121-130        | 8         | 2.22%   |
| 351-500        | 6         | 1.66%   |
| 251-300        | 4         | 1.11%   |
| 111-120        | 4         | 1.11%   |
| 51-60          | 3         | 0.83%   |
| 151-200        | 3         | 0.83%   |
| 501-1000       | 3         | 0.83%   |
| Unknown        | 3         | 0.83%   |
| 131-140        | 2         | 0.55%   |
| More than 1000 | 1         | 0.28%   |
| 41-50          | 1         | 0.28%   |
| 1-40           | 1         | 0.28%   |
| 91-100         | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 147       | 41.41%  |
| 101-120       | 91        | 25.63%  |
| 51-100        | 66        | 18.59%  |
| 161-240       | 27        | 7.61%   |
| More than 240 | 21        | 5.92%   |
| Unknown       | 3         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 220       | 72.85%  |
| 2     | 64        | 21.19%  |
| 3     | 11        | 3.64%   |
| 0     | 6         | 1.99%   |
| 4     | 1         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 181       | 37.79%  |
| Realtek Semiconductor           | 151       | 31.52%  |
| Qualcomm Atheros                | 58        | 12.11%  |
| Broadcom                        | 22        | 4.59%   |
| Lenovo                          | 12        | 2.51%   |
| Broadcom Limited                | 11        | 2.3%    |
| MediaTek                        | 5         | 1.04%   |
| DisplayLink                     | 4         | 0.84%   |
| Xiaomi                          | 3         | 0.63%   |
| Marvell Technology Group        | 3         | 0.63%   |
| ASIX Electronics                | 3         | 0.63%   |
| Samsung Electronics             | 2         | 0.42%   |
| Ralink Technology               | 2         | 0.42%   |
| Qualcomm Atheros Communications | 2         | 0.42%   |
| Huawei Technologies             | 2         | 0.42%   |
| Edimax Technology               | 2         | 0.42%   |
| U-Blox                          | 1         | 0.21%   |
| Toshiba                         | 1         | 0.21%   |
| Qualcomm                        | 1         | 0.21%   |
| PEAK-System Technik             | 1         | 0.21%   |
| Nvidia                          | 1         | 0.21%   |
| Nokia Mobile Phones             | 1         | 0.21%   |
| Linksys                         | 1         | 0.21%   |
| LG Electronics                  | 1         | 0.21%   |
| ICS Advent                      | 1         | 0.21%   |
| HMD Global                      | 1         | 0.21%   |
| Hewlett-Packard                 | 1         | 0.21%   |
| Google                          | 1         | 0.21%   |
| Dell                            | 1         | 0.21%   |
| Comneon                         | 1         | 0.21%   |
| Attansic Technology             | 1         | 0.21%   |
| ASUSTek Computer                | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 90        | 15.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 32        | 5.5%    |
| Intel Wireless 8265 / 8275                                              | 20        | 3.44%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 3.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.89%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 1.89%   |
| Intel Wireless 8260                                                     | 10        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 1.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.37%   |
| Intel Wireless 3165                                                     | 8         | 1.37%   |
| Intel Wireless 3160                                                     | 8         | 1.37%   |
| Intel Wireless 7265                                                     | 7         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.03%   |
| Lenovo ThinkPad TBT 3 Dock                                              | 6         | 1.03%   |
| Intel Ethernet Connection (13) I219-V                                   | 6         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.86%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                                   | 5         | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                       | 4         | 0.69%   |
| Lenovo USB-C Dock Ethernet                                              | 4         | 0.69%   |
| Intel Wireless 7260                                                     | 4         | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.69%   |
| Intel Ethernet Connection (10) I219-V                                   | 4         | 0.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 171       | 56.81%  |
| Qualcomm Atheros                | 54        | 17.94%  |
| Realtek Semiconductor           | 33        | 10.96%  |
| Broadcom                        | 21        | 6.98%   |
| Broadcom Limited                | 8         | 2.66%   |
| MediaTek                        | 5         | 1.66%   |
| Ralink Technology               | 2         | 0.66%   |
| Qualcomm Atheros Communications | 2         | 0.66%   |
| Edimax Technology               | 2         | 0.66%   |
| Qualcomm                        | 1         | 0.33%   |
| Dell                            | 1         | 0.33%   |
| ASUSTek Computer                | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 20        | 6.6%    |
| Intel Wi-Fi 6 AX201                                                     | 19        | 6.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 3.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 3.63%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 3.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 3.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 3.63%   |
| Intel Wireless 8260                                                     | 10        | 3.3%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 3.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 2.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.64%   |
| Intel Wireless 3165                                                     | 8         | 2.64%   |
| Intel Wireless 3160                                                     | 8         | 2.64%   |
| Intel Wireless 7265                                                     | 7         | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.32%   |
| Intel Wireless 7260                                                     | 4         | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.32%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 1.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.66%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.66%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.66%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 2         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 141       | 52.81%  |
| Intel                    | 71        | 26.59%  |
| Lenovo                   | 12        | 4.49%   |
| Qualcomm Atheros         | 11        | 4.12%   |
| Broadcom                 | 6         | 2.25%   |
| DisplayLink              | 4         | 1.5%    |
| Broadcom Limited         | 4         | 1.5%    |
| Xiaomi                   | 3         | 1.12%   |
| Marvell Technology Group | 3         | 1.12%   |
| ASIX Electronics         | 3         | 1.12%   |
| Samsung Electronics      | 2         | 0.75%   |
| Nvidia                   | 1         | 0.37%   |
| Linksys                  | 1         | 0.37%   |
| ICS Advent               | 1         | 0.37%   |
| Huawei Technologies      | 1         | 0.37%   |
| HMD Global               | 1         | 0.37%   |
| Google                   | 1         | 0.37%   |
| Attansic Technology      | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 90        | 33.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 11.81%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 4.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 3.32%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 6         | 2.21%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 2.21%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.48%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 1.48%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.48%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.48%   |
| Intel I210 Gigabit Network Connection                             | 3         | 1.11%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.11%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.11%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.11%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.11%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.74%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.74%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.74%   |
| Intel Ethernet Connection (14) I219-LM                            | 2         | 0.74%   |
| DisplayLink USB 3.0 Dual Video Dock                               | 2         | 0.74%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.37%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 291       | 53.89%  |
| Ethernet | 241       | 44.63%  |
| Modem    | 7         | 1.3%    |
| Unknown  | 1         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 232       | 73.42%  |
| Ethernet | 83        | 26.27%  |
| Modem    | 1         | 0.32%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 215       | 72.15%  |
| 1     | 79        | 26.51%  |
| 3     | 3         | 1.01%   |
| 7     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 254       | 84.67%  |
| Yes  | 46        | 15.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 148       | 60.41%  |
| Qualcomm Atheros Communications | 21        | 8.57%   |
| Realtek Semiconductor           | 20        | 8.16%   |
| IMC Networks                    | 14        | 5.71%   |
| Broadcom                        | 10        | 4.08%   |
| Lite-On Technology              | 6         | 2.45%   |
| Foxconn / Hon Hai               | 6         | 2.45%   |
| Apple                           | 5         | 2.04%   |
| Dell                            | 4         | 1.63%   |
| Hewlett-Packard                 | 2         | 0.82%   |
| Cambridge Silicon Radio         | 2         | 0.82%   |
| Askey Computer                  | 2         | 0.82%   |
| Toshiba                         | 1         | 0.41%   |
| Realtek                         | 1         | 0.41%   |
| MediaTek                        | 1         | 0.41%   |
| ASUSTek Computer                | 1         | 0.41%   |
| Actions                         | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 58        | 23.67%  |
| Intel AX201 Bluetooth                               | 43        | 17.55%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 7.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 4.49%   |
| Intel AX200 Bluetooth                               | 10        | 4.08%   |
| Realtek Bluetooth Radio                             | 9         | 3.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 2.86%   |
| Lite-On Bluetooth Device                            | 5         | 2.04%   |
| Intel Bluetooth Device                              | 5         | 2.04%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 1.63%   |
| Intel AX210 Bluetooth                               | 4         | 1.63%   |
| IMC Networks Bluetooth Device                       | 4         | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.22%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 1.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.22%   |
| IMC Networks Wireless_Device                        | 3         | 1.22%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.22%   |
| Apple Bluetooth Host Controller                     | 3         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.82%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.82%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.82%   |
| Foxconn / Hon Hai BT                                | 2         | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.82%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.82%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.82%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.82%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.82%   |
| Askey Bluetooth Device                              | 2         | 0.82%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.41%   |
| Realtek Bluetooth Radio                             | 1         | 0.41%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.41%   |
| MediaTek BT                                         | 1         | 0.41%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.41%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.41%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 277       | 74.26%  |
| Nvidia                     | 44        | 11.8%   |
| AMD                        | 17        | 4.56%   |
| Lenovo                     | 13        | 3.49%   |
| Realtek Semiconductor      | 4         | 1.07%   |
| Microsoft                  | 2         | 0.54%   |
| Logitech                   | 2         | 0.54%   |
| GN Netcom                  | 2         | 0.54%   |
| XMOS                       | 1         | 0.27%   |
| VIA Technologies           | 1         | 0.27%   |
| Texas Instruments          | 1         | 0.27%   |
| Sennheiser Communications  | 1         | 0.27%   |
| Razer USA                  | 1         | 0.27%   |
| PreSonus Audio Electronics | 1         | 0.27%   |
| Plantronics                | 1         | 0.27%   |
| FIFINE Microphones         | 1         | 0.27%   |
| Dell                       | 1         | 0.27%   |
| Creative Technology        | 1         | 0.27%   |
| C-Media Electronics        | 1         | 0.27%   |
| ASUSTek Computer           | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 58        | 13.88%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 24        | 5.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 4.31%   |
| Intel Cannon Lake PCH cAVS                                                 | 16        | 3.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 15        | 3.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 14        | 3.35%   |
| Intel Broadwell-U Audio Controller                                         | 14        | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 3.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 12        | 2.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 2.87%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 2.87%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 2.63%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 2.39%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 2.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 2.39%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.44%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 1.44%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 6         | 1.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.2%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 1.2%    |
| Realtek Semiconductor USB Audio                                            | 4         | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.96%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 4         | 0.96%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 0.96%   |
| AMD FCH Azalia Controller                                                  | 4         | 0.96%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.72%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.72%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.48%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.48%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.48%   |
| Nvidia Audio device                                                        | 2         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 28.57%  |
| SK hynix            | 50        | 23.81%  |
| Micron Technology   | 36        | 17.14%  |
| Kingston            | 15        | 7.14%   |
| Unknown             | 13        | 6.19%   |
| Crucial             | 11        | 5.24%   |
| Ramaxel Technology  | 7         | 3.33%   |
| G.Skill             | 4         | 1.9%    |
| Nanya Technology    | 3         | 1.43%   |
| Elpida              | 3         | 1.43%   |
| Transcend           | 2         | 0.95%   |
| V-Color             | 1         | 0.48%   |
| Corsair             | 1         | 0.48%   |
| Avant               | 1         | 0.48%   |
| ASint Technology    | 1         | 0.48%   |
| A-DATA Technology   | 1         | 0.48%   |
| 48spaces            | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 1.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 4         | 1.85%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 4         | 1.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 4         | 1.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 1.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 1.39%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 1.39%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 3         | 1.39%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 3         | 1.39%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s           | 3         | 1.39%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 3         | 1.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 2         | 0.93%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 2         | 0.93%   |
| Unknown RAM Module 1024MB SODIMM DDR2                        | 2         | 0.93%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s             | 2         | 0.93%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.93%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 2         | 0.93%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s   | 2         | 0.93%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 0.93%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 2         | 0.93%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 2         | 0.93%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                  | 2         | 0.93%   |
| Samsung RAM M471B5673DZ1-CF8 2048MB SODIMM 1067MT/s          | 2         | 0.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.93%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 2         | 0.93%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.93%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s        | 2         | 0.93%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s     | 2         | 0.93%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.93%   |
| Ramaxel RAM RMSA3320ME88HBF-3200 16GB SODIMM DDR4 3200MT/s   | 2         | 0.93%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 2         | 0.93%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 2         | 0.93%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s         | 2         | 0.93%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 2         | 0.93%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s  | 2         | 0.93%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 0.93%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s       | 2         | 0.93%   |
| Kingston RAM 9905711-035.A00G 8GB SODIMM DDR4 3200MT/s       | 2         | 0.93%   |
| Elpida RAM SNY1333D3S9ELC/4G 4GB SODIMM DDR 1333MT/s         | 2         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 97        | 56.73%  |
| DDR3    | 40        | 23.39%  |
| LPDDR3  | 10        | 5.85%   |
| DDR2    | 10        | 5.85%   |
| DDR5    | 5         | 2.92%   |
| DDR     | 3         | 1.75%   |
| LPDDR5  | 2         | 1.17%   |
| LPDDR4  | 2         | 1.17%   |
| Unknown | 2         | 1.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 153       | 89.47%  |
| Row Of Chips | 16        | 9.36%   |
| DIMM         | 1         | 0.58%   |
| Chip         | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 62        | 33.33%  |
| 16384 | 43        | 23.12%  |
| 4096  | 43        | 23.12%  |
| 2048  | 19        | 10.22%  |
| 32768 | 10        | 5.38%   |
| 1024  | 9         | 4.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 47        | 25.27%  |
| 3200    | 35        | 18.82%  |
| 1600    | 29        | 15.59%  |
| 2133    | 16        | 8.6%    |
| 2400    | 14        | 7.53%   |
| 667     | 7         | 3.76%   |
| 4800    | 6         | 3.23%   |
| 1334    | 5         | 2.69%   |
| 1067    | 5         | 2.69%   |
| 3266    | 4         | 2.15%   |
| 1333    | 3         | 1.61%   |
| Unknown | 3         | 1.61%   |
| 6400    | 2         | 1.08%   |
| 4267    | 2         | 1.08%   |
| 1867    | 2         | 1.08%   |
| 800     | 2         | 1.08%   |
| 533     | 2         | 1.08%   |
| 8400    | 1         | 0.54%   |
| 1066    | 1         | 0.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 66.67%  |
| BIXOLON             | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 33.33%  |
| Samsung M288x Series               | 1         | 33.33%  |
| BIXOLON BIXOLON_SLP-T400           | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 50        | 17.86%  |
| Chicony Electronics                    | 50        | 17.86%  |
| Realtek Semiconductor                  | 42        | 15%     |
| Sunplus Innovation Technology          | 21        | 7.5%    |
| Microdia                               | 21        | 7.5%    |
| Acer                                   | 20        | 7.14%   |
| Lite-On Technology                     | 8         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.86%   |
| Apple                                  | 8         | 2.86%   |
| Suyin                                  | 7         | 2.5%    |
| Quanta                                 | 6         | 2.14%   |
| Logitech                               | 6         | 2.14%   |
| Luxvisions Innotech Limited            | 5         | 1.79%   |
| Syntek                                 | 4         | 1.43%   |
| Silicon Motion                         | 4         | 1.43%   |
| Microsoft                              | 4         | 1.43%   |
| Lenovo                                 | 2         | 0.71%   |
| Cubeternet                             | 2         | 0.71%   |
| Bison Electronics                      | 2         | 0.71%   |
| ALi                                    | 2         | 0.71%   |
| Alcor Micro                            | 2         | 0.71%   |
| Z-Star Microelectronics                | 1         | 0.36%   |
| Samsung Electronics                    | 1         | 0.36%   |
| Primax Electronics                     | 1         | 0.36%   |
| Jieli Technology                       | 1         | 0.36%   |
| Generalplus Technology                 | 1         | 0.36%   |
| eMPIA Technology                       | 1         | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                  | 21        | 7.47%   |
| Chicony Integrated Camera                     | 20        | 7.12%   |
| IMC Networks USB2.0 HD UVC WebCam             | 14        | 4.98%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 13        | 4.63%   |
| IMC Networks Integrated Camera                | 13        | 4.63%   |
| Microdia Integrated_Webcam_HD                 | 10        | 3.56%   |
| Acer Integrated Camera                        | 5         | 1.78%   |
| Sunplus Integrated_Webcam_HD                  | 4         | 1.42%   |
| Lite-On HP HD Camera                          | 4         | 1.42%   |
| Chicony HP HD Camera                          | 4         | 1.42%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 4         | 1.42%   |
| Acer SunplusIT Integrated Camera              | 4         | 1.42%   |
| Syntek Integrated Camera                      | 3         | 1.07%   |
| Sunplus WEMISS CM-A1                          | 3         | 1.07%   |
| Realtek Lenovo EasyCamera                     | 3         | 1.07%   |
| IMC Networks USB2.0 UVC HD Webcam             | 3         | 1.07%   |
| Chicony Lenovo EasyCamera                     | 3         | 1.07%   |
| Chicony Integrated Camera (1280x720@30)       | 3         | 1.07%   |
| Acer Lenovo EasyCamera                        | 3         | 1.07%   |
| Acer BisonCam, NB Pro                         | 3         | 1.07%   |
| Suyin Integrated_Webcam_HD                    | 2         | 0.71%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 2         | 0.71%   |
| Sunplus ASUS Webcam                           | 2         | 0.71%   |
| Realtek USB2.0 HD UVC WebCam                  | 2         | 0.71%   |
| Realtek USB Camera                            | 2         | 0.71%   |
| Realtek Integrated Webcam HD                  | 2         | 0.71%   |
| Realtek HP Wide Vision HD Camera              | 2         | 0.71%   |
| Quanta USB Webcam                             | 2         | 0.71%   |
| Quanta HP TrueVision HD Camera                | 2         | 0.71%   |
| Microsoft LifeCam NX-6000                     | 2         | 0.71%   |
| Microdia Integrated Webcam                    | 2         | 0.71%   |
| Microdia Dell Integrated HD Webcam            | 2         | 0.71%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 0.71%   |
| Luxvisions Innotech Limited HP HD Camera      | 2         | 0.71%   |
| Logitech HD Pro Webcam C920                   | 2         | 0.71%   |
| Lite-On Integrated Camera                     | 2         | 0.71%   |
| IMC Networks USB2.0 HD IR UVC WebCam          | 2         | 0.71%   |
| IMC Networks Lenovo EasyCamera                | 2         | 0.71%   |
| Cubeternet USB2.0 Camera                      | 2         | 0.71%   |
| Chicony HP Webcam                             | 2         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 29        | 46.03%  |
| Validity Sensors           | 17        | 26.98%  |
| Shenzhen Goodix Technology | 7         | 11.11%  |
| Elan Microelectronics      | 4         | 6.35%   |
| STMicroelectronics         | 2         | 3.17%   |
| AuthenTec                  | 2         | 3.17%   |
| Upek                       | 1         | 1.59%   |
| LighTuning Technology      | 1         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 25.4%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 6.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 6.35%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 6.35%   |
| Elan ELAN:Fingerprint                                                      | 4         | 6.35%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 3.17%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 3.17%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.59%   |
| Validity Sensors VFS491                                                    | 1         | 1.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.59%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.59%   |
| Synaptics WBDI                                                             | 1         | 1.59%   |
| Synaptics UWP WBDI                                                         | 1         | 1.59%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 1.59%   |
| Synaptics  WBDI                                                            | 1         | 1.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.59%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.59%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 23        | 62.16%  |
| Alcor Micro | 14        | 37.84%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 37.84%  |
| Broadcom 58200                                                               | 8         | 21.62%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 18.92%  |
| Broadcom 5880                                                                | 6         | 16.22%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 5.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 170       | 55.37%  |
| 1     | 99        | 32.25%  |
| 2     | 30        | 9.77%   |
| 3     | 6         | 1.95%   |
| 7     | 1         | 0.33%   |
| 4     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 62        | 34.44%  |
| Graphics card            | 39        | 21.67%  |
| Chipcard                 | 33        | 18.33%  |
| Net/wireless             | 17        | 9.44%   |
| Camera                   | 8         | 4.44%   |
| Multimedia controller    | 5         | 2.78%   |
| Card reader              | 3         | 1.67%   |
| Unassigned class         | 2         | 1.11%   |
| Storage                  | 2         | 1.11%   |
| Sound                    | 2         | 1.11%   |
| Net/ethernet             | 2         | 1.11%   |
| Communication controller | 2         | 1.11%   |
| Bluetooth                | 2         | 1.11%   |
| Network                  | 1         | 0.56%   |

