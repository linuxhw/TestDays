Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

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

Total: 4895

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | GE60 0NC\0ND                | [423eca6c8c](https://linux-hardware.org/?probe=423eca6c8c) | Jan 05, 2025 |
| Dell          | Latitude E6410              | [b51666dd6f](https://linux-hardware.org/?probe=b51666dd6f) | Dec 19, 2024 |
| Acer          | Aspire 5733                 | [edc4741bd8](https://linux-hardware.org/?probe=edc4741bd8) | Dec 15, 2024 |
| Acer          | Aspire 5733                 | [b7af1c256d](https://linux-hardware.org/?probe=b7af1c256d) | Dec 15, 2024 |
| Clevo         | W35_37ET                    | [8c4d3d1caa](https://linux-hardware.org/?probe=8c4d3d1caa) | Nov 30, 2024 |
| Clevo         | W35_37ET                    | [4b7ce97c36](https://linux-hardware.org/?probe=4b7ce97c36) | Nov 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [45fd5080cc](https://linux-hardware.org/?probe=45fd5080cc) | Nov 26, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [a13d39cf07](https://linux-hardware.org/?probe=a13d39cf07) | Nov 20, 2024 |
| HP            | Notebook                    | [9ec4cde8a4](https://linux-hardware.org/?probe=9ec4cde8a4) | Nov 18, 2024 |
| Dell          | Inspiron 5720               | [5c8bf7fb22](https://linux-hardware.org/?probe=5c8bf7fb22) | Nov 09, 2024 |
| MSI           | Thin GF63 12UCX             | [20bee02e0a](https://linux-hardware.org/?probe=20bee02e0a) | Nov 07, 2024 |
| PC Special... | 14 Fusion IV                | [1ef6e14285](https://linux-hardware.org/?probe=1ef6e14285) | Nov 04, 2024 |
| Insyde        | GeminiLake                  | [df7e9af6a4](https://linux-hardware.org/?probe=df7e9af6a4) | Nov 02, 2024 |
| Dell          | XPS 15 7590                 | [597318b1e3](https://linux-hardware.org/?probe=597318b1e3) | Nov 01, 2024 |
| Acer          | Nitro AN515-52              | [009c07413d](https://linux-hardware.org/?probe=009c07413d) | Oct 29, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5Q1E    | [b36104396e](https://linux-hardware.org/?probe=b36104396e) | Oct 26, 2024 |
| Sony          | VGN-NW26M                   | [b7d8f997e5](https://linux-hardware.org/?probe=b7d8f997e5) | Oct 25, 2024 |
| HP            | 250 G8 Notebook PC          | [338df85e2c](https://linux-hardware.org/?probe=338df85e2c) | Oct 23, 2024 |
| HP            | ProBook 440 14 inch G9 N... | [8f4ed9b69e](https://linux-hardware.org/?probe=8f4ed9b69e) | Oct 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d01b3d0dd1](https://linux-hardware.org/?probe=d01b3d0dd1) | Oct 18, 2024 |
| Dell          | Latitude E6520              | [aff7fc0640](https://linux-hardware.org/?probe=aff7fc0640) | Oct 16, 2024 |
| SLIMBOOK      | Unknown                     | [a45b75d9ec](https://linux-hardware.org/?probe=a45b75d9ec) | Oct 14, 2024 |
| Acer          | Aspire A515-56              | [a61df1d187](https://linux-hardware.org/?probe=a61df1d187) | Oct 11, 2024 |
| HP            | G60                         | [c4e7fe598d](https://linux-hardware.org/?probe=c4e7fe598d) | Sep 30, 2024 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [91c64d17ea](https://linux-hardware.org/?probe=91c64d17ea) | Sep 22, 2024 |
| Acer          | Aspire ES1-533              | [238267b887](https://linux-hardware.org/?probe=238267b887) | Sep 20, 2024 |
| ASUSTek       | 1000                        | [4ba77b632f](https://linux-hardware.org/?probe=4ba77b632f) | Sep 20, 2024 |
| HP            | G60                         | [918e4c12c2](https://linux-hardware.org/?probe=918e4c12c2) | Sep 20, 2024 |
| Lenovo        | ThinkPad T430 2347FF9       | [0e9f60231f](https://linux-hardware.org/?probe=0e9f60231f) | Sep 11, 2024 |
| HP            | Laptop 15s-eq2xxx           | [dc90d7b0f6](https://linux-hardware.org/?probe=dc90d7b0f6) | Sep 09, 2024 |
| HP            | EliteBook 8760w             | [78169bfe9b](https://linux-hardware.org/?probe=78169bfe9b) | Sep 08, 2024 |
| Positivo      | C8240AI-15                  | [cf5df4af8e](https://linux-hardware.org/?probe=cf5df4af8e) | Sep 02, 2024 |
| HP            | G60                         | [b27d94e4b9](https://linux-hardware.org/?probe=b27d94e4b9) | Aug 21, 2024 |
| HP            | G60                         | [98fc212513](https://linux-hardware.org/?probe=98fc212513) | Aug 21, 2024 |
| Lenovo        | 3000 G530 4151/200          | [1d9b0a4f71](https://linux-hardware.org/?probe=1d9b0a4f71) | Aug 19, 2024 |
| Lenovo        | 3000 G530 4151/200          | [c12d510377](https://linux-hardware.org/?probe=c12d510377) | Aug 19, 2024 |
| Acer          | Aspire AG14-31P             | [0e32b18772](https://linux-hardware.org/?probe=0e32b18772) | Aug 12, 2024 |
| Acer          | Aspire AG14-31P             | [12d18c1ee6](https://linux-hardware.org/?probe=12d18c1ee6) | Aug 12, 2024 |
| Lenovo        | ThinkPad E490 20N8S0WH00    | [4df92c7741](https://linux-hardware.org/?probe=4df92c7741) | Aug 12, 2024 |
| Lenovo        | ThinkPad E595 20NF001HRT    | [ed43fa321d](https://linux-hardware.org/?probe=ed43fa321d) | Aug 11, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [32a29957a4](https://linux-hardware.org/?probe=32a29957a4) | Aug 10, 2024 |
| HP            | Mini China Mobile Editio... | [573e118166](https://linux-hardware.org/?probe=573e118166) | Aug 09, 2024 |
| HP            | Mini China Mobile Editio... | [f1700dec96](https://linux-hardware.org/?probe=f1700dec96) | Aug 09, 2024 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [7f7717743d](https://linux-hardware.org/?probe=7f7717743d) | Aug 08, 2024 |
| Acer          | Aspire E5-523G              | [dcae9fea91](https://linux-hardware.org/?probe=dcae9fea91) | Aug 01, 2024 |
| Acer          | AOD270                      | [086d69b5dc](https://linux-hardware.org/?probe=086d69b5dc) | Jul 31, 2024 |
| Acer          | AOD270                      | [5a2f98fbf0](https://linux-hardware.org/?probe=5a2f98fbf0) | Jul 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [b83c73ebb9](https://linux-hardware.org/?probe=b83c73ebb9) | Jul 27, 2024 |
| Dell          | Latitude E6420              | [062d91bd4e](https://linux-hardware.org/?probe=062d91bd4e) | Jul 26, 2024 |
| NOBLEX        | NT1010E                     | [c27368454d](https://linux-hardware.org/?probe=c27368454d) | Jul 25, 2024 |
| Lenovo        | 3000 N100 0768FPG           | [1f529ec188](https://linux-hardware.org/?probe=1f529ec188) | Jul 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [af38eddfb9](https://linux-hardware.org/?probe=af38eddfb9) | Jul 23, 2024 |
| AMI           | Cherry Trail CR             | [bef52595c6](https://linux-hardware.org/?probe=bef52595c6) | Jul 21, 2024 |
| ASUSTek       | K53SJ                       | [ac4dbbb061](https://linux-hardware.org/?probe=ac4dbbb061) | Jul 12, 2024 |
| HP            | 250 G7 Notebook PC          | [4625edbfa8](https://linux-hardware.org/?probe=4625edbfa8) | Jul 05, 2024 |
| HP            | ZBook 15u G5                | [026a2f799a](https://linux-hardware.org/?probe=026a2f799a) | Jun 30, 2024 |
| Tablet        | 8                           | [05e319ff90](https://linux-hardware.org/?probe=05e319ff90) | Jun 28, 2024 |
| Positivo B... | VJFE59F11X-B1011H           | [b3a0915574](https://linux-hardware.org/?probe=b3a0915574) | Jun 24, 2024 |
| MSI           | PE70 7RD                    | [26556b06ad](https://linux-hardware.org/?probe=26556b06ad) | Jun 24, 2024 |
| Acer          | TravelMate P449-G2-M        | [715fa28bb7](https://linux-hardware.org/?probe=715fa28bb7) | Jun 23, 2024 |
| Acer          | TravelMate P449-G2-M        | [7abc3101ea](https://linux-hardware.org/?probe=7abc3101ea) | Jun 22, 2024 |
| Toshiba       | Satellite L650D             | [09f8b8509c](https://linux-hardware.org/?probe=09f8b8509c) | Jun 22, 2024 |
| Dell          | Latitude E6420              | [07364acb42](https://linux-hardware.org/?probe=07364acb42) | Jun 19, 2024 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [abf647d335](https://linux-hardware.org/?probe=abf647d335) | Jun 10, 2024 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [4fc663cdab](https://linux-hardware.org/?probe=4fc663cdab) | Jun 10, 2024 |
| Lenovo        | B490 37722QP                | [d8afa9ab6e](https://linux-hardware.org/?probe=d8afa9ab6e) | Jun 07, 2024 |
| Lenovo        | B490 37722QP                | [981e272711](https://linux-hardware.org/?probe=981e272711) | Jun 06, 2024 |
| HP            | EliteBook 725 G4            | [5a8af90597](https://linux-hardware.org/?probe=5a8af90597) | Jun 04, 2024 |
| HP            | EliteBook 725 G4            | [ddcee8dc11](https://linux-hardware.org/?probe=ddcee8dc11) | Jun 04, 2024 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [4ac8e343f3](https://linux-hardware.org/?probe=4ac8e343f3) | May 30, 2024 |
| Dell          | Inspiron N4050              | [c4f21338da](https://linux-hardware.org/?probe=c4f21338da) | May 27, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [548c48e57a](https://linux-hardware.org/?probe=548c48e57a) | May 21, 2024 |
| Dell          | Precision M4700             | [3025a7f21e](https://linux-hardware.org/?probe=3025a7f21e) | May 13, 2024 |
| Lenovo        | ThinkPad T430 2349BG6       | [590a71a235](https://linux-hardware.org/?probe=590a71a235) | May 13, 2024 |
| Dell          | Precision 5510              | [dfe5317b14](https://linux-hardware.org/?probe=dfe5317b14) | May 12, 2024 |
| Dell          | Precision 5510              | [f16ec110d5](https://linux-hardware.org/?probe=f16ec110d5) | May 11, 2024 |
| HP            | Pavilion dv6700             | [f160688603](https://linux-hardware.org/?probe=f160688603) | May 10, 2024 |
| Lenovo        | G50-45 80E3                 | [801eeb31ef](https://linux-hardware.org/?probe=801eeb31ef) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7c01de63e1](https://linux-hardware.org/?probe=7c01de63e1) | May 08, 2024 |
| Acer          | Aspire E1-531               | [27d57e495a](https://linux-hardware.org/?probe=27d57e495a) | May 04, 2024 |
| Dell          | Precision 5510              | [a010faffda](https://linux-hardware.org/?probe=a010faffda) | May 01, 2024 |
| HP            | Laptop 15s-eq2xxx           | [90d5348bf5](https://linux-hardware.org/?probe=90d5348bf5) | Apr 28, 2024 |
| Acer          | Aspire E1-532               | [b50154d060](https://linux-hardware.org/?probe=b50154d060) | Apr 28, 2024 |
| Dell          | Precision M6800             | [1d41e8bb92](https://linux-hardware.org/?probe=1d41e8bb92) | Apr 25, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [e61e4963d5](https://linux-hardware.org/?probe=e61e4963d5) | Apr 23, 2024 |
| Acer          | Aspire S3                   | [e43ba2d3ae](https://linux-hardware.org/?probe=e43ba2d3ae) | Apr 21, 2024 |
| Dell          | Precision M6800             | [c44a2aee51](https://linux-hardware.org/?probe=c44a2aee51) | Apr 20, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [01121cc898](https://linux-hardware.org/?probe=01121cc898) | Apr 18, 2024 |
| HP            | 245 G6                      | [17b7e55361](https://linux-hardware.org/?probe=17b7e55361) | Apr 17, 2024 |
| HP            | 245 G6                      | [7c3534813c](https://linux-hardware.org/?probe=7c3534813c) | Apr 17, 2024 |
| Lenovo        | IdeaPadFlex 14 20308        | [7ccf67d720](https://linux-hardware.org/?probe=7ccf67d720) | Apr 16, 2024 |
| HP            | Laptop 14s-dq2xxx           | [d6865e9438](https://linux-hardware.org/?probe=d6865e9438) | Apr 14, 2024 |
| Fujitsu       | LIFEBOOK E752               | [57b8f56426](https://linux-hardware.org/?probe=57b8f56426) | Apr 12, 2024 |
| HP            | Presario V6000 (GH918EA#... | [19c9124453](https://linux-hardware.org/?probe=19c9124453) | Apr 10, 2024 |
| Apple         | MacBookPro5,3               | [4661f5b412](https://linux-hardware.org/?probe=4661f5b412) | Apr 08, 2024 |
| Dell          | Inspiron 5537               | [304df5369f](https://linux-hardware.org/?probe=304df5369f) | Apr 06, 2024 |
| Acer          | Aspire 3690                 | [a3091a1ceb](https://linux-hardware.org/?probe=a3091a1ceb) | Apr 06, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [e759ee33bf](https://linux-hardware.org/?probe=e759ee33bf) | Apr 04, 2024 |
| Fujitsu       | LIFEBOOK A557               | [0c26980268](https://linux-hardware.org/?probe=0c26980268) | Apr 03, 2024 |
| Juana Mans... | SF20GM7                     | [8571d52a38](https://linux-hardware.org/?probe=8571d52a38) | Apr 02, 2024 |
| ASUSTek       | N55SF                       | [69918bf880](https://linux-hardware.org/?probe=69918bf880) | Apr 01, 2024 |
| HP            | ENVY Laptop 13-ah0xxx       | [38d1d0b6b6](https://linux-hardware.org/?probe=38d1d0b6b6) | Mar 31, 2024 |
| ASUSTek       | K53SJ                       | [7542f194a2](https://linux-hardware.org/?probe=7542f194a2) | Mar 28, 2024 |
| ASUSTek       | K53SJ                       | [34d7c41e80](https://linux-hardware.org/?probe=34d7c41e80) | Mar 28, 2024 |
| ASUSTek       | F52Q                        | [edb335c489](https://linux-hardware.org/?probe=edb335c489) | Mar 27, 2024 |
| Digma         | EVE 15 C419 ES5065EW        | [83810dcd33](https://linux-hardware.org/?probe=83810dcd33) | Mar 26, 2024 |
| HP            | Presario V2000 (EH459UA#... | [af3a09ea38](https://linux-hardware.org/?probe=af3a09ea38) | Mar 26, 2024 |
| Primux Tec... | Primux ioxbook 1402FX       | [53e6d67001](https://linux-hardware.org/?probe=53e6d67001) | Mar 23, 2024 |
| Fujitsu       | LIFEBOOK E754               | [4558c9a4f4](https://linux-hardware.org/?probe=4558c9a4f4) | Mar 22, 2024 |
| Lenovo        | V310-14IKB 80T2             | [0018e3e74d](https://linux-hardware.org/?probe=0018e3e74d) | Mar 16, 2024 |
| Lenovo        | IdeaPad C340-14API 81N6     | [08ca6f8423](https://linux-hardware.org/?probe=08ca6f8423) | Mar 14, 2024 |
| Dell          | Latitude 5401               | [651b3a2f09](https://linux-hardware.org/?probe=651b3a2f09) | Mar 14, 2024 |
| Dell          | System XPS L702X            | [09313dcc56](https://linux-hardware.org/?probe=09313dcc56) | Mar 11, 2024 |
| Lenovo        | ThinkPad X230 2325AEG       | [8e4dbd3b9a](https://linux-hardware.org/?probe=8e4dbd3b9a) | Mar 10, 2024 |
| HP            | Compaq Presario CQ50        | [a690fc2f4c](https://linux-hardware.org/?probe=a690fc2f4c) | Mar 06, 2024 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [dede36b712](https://linux-hardware.org/?probe=dede36b712) | Mar 04, 2024 |
| Lenovo        | ThinkPad A275 20KDS01S00    | [21f2a28872](https://linux-hardware.org/?probe=21f2a28872) | Mar 04, 2024 |
| MSI           | Modern 14 B11MOU            | [66a88413c4](https://linux-hardware.org/?probe=66a88413c4) | Feb 28, 2024 |
| VANT          | MOOVE2-14                   | [9d5df13f40](https://linux-hardware.org/?probe=9d5df13f40) | Feb 27, 2024 |
| Packard Be... | H17HV                       | [aa7bdcf198](https://linux-hardware.org/?probe=aa7bdcf198) | Feb 27, 2024 |
| HP            | ProBook 4540s               | [da8c81f864](https://linux-hardware.org/?probe=da8c81f864) | Feb 27, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [ad9632b089](https://linux-hardware.org/?probe=ad9632b089) | Feb 27, 2024 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [d44ed1a56f](https://linux-hardware.org/?probe=d44ed1a56f) | Feb 26, 2024 |
| HP            | Pavilion dv7                | [4712b3d187](https://linux-hardware.org/?probe=4712b3d187) | Feb 25, 2024 |
| Dell          | Inspiron 15 3511            | [cf8780be93](https://linux-hardware.org/?probe=cf8780be93) | Feb 24, 2024 |
| HP            | Compaq Presario CQ50        | [dc0f4d581f](https://linux-hardware.org/?probe=dc0f4d581f) | Feb 23, 2024 |
| Acer          | Nitro AN515-43              | [033fe9a8a6](https://linux-hardware.org/?probe=033fe9a8a6) | Feb 22, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [b6fb308e13](https://linux-hardware.org/?probe=b6fb308e13) | Feb 19, 2024 |
| Toshiba       | Satellite C670D-121         | [e72d5daf72](https://linux-hardware.org/?probe=e72d5daf72) | Feb 17, 2024 |
| Toshiba       | Satellite C670D-121         | [31876b1946](https://linux-hardware.org/?probe=31876b1946) | Feb 15, 2024 |
| HP            | EliteBook 840 G6            | [b3ffbe3673](https://linux-hardware.org/?probe=b3ffbe3673) | Feb 14, 2024 |
| ASUSTek       | X751LB                      | [e2b955fef7](https://linux-hardware.org/?probe=e2b955fef7) | Feb 12, 2024 |
| Dell          | Latitude E6440              | [af1136c398](https://linux-hardware.org/?probe=af1136c398) | Feb 11, 2024 |
| Dell          | Latitude E6440              | [3d82406435](https://linux-hardware.org/?probe=3d82406435) | Feb 11, 2024 |
| Positivo B... | VJFE59F11X-B0821H           | [749f5aacff](https://linux-hardware.org/?probe=749f5aacff) | Feb 10, 2024 |
| Toshiba       | Satellite L755              | [51db691206](https://linux-hardware.org/?probe=51db691206) | Feb 09, 2024 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [10a9284561](https://linux-hardware.org/?probe=10a9284561) | Feb 07, 2024 |
| HP            | Compaq 15                   | [beb2ca6a98](https://linux-hardware.org/?probe=beb2ca6a98) | Feb 06, 2024 |
| Acer          | Aspire 7741                 | [65e4664bc8](https://linux-hardware.org/?probe=65e4664bc8) | Feb 03, 2024 |
| HP            | Pavilion g4                 | [c918dcf201](https://linux-hardware.org/?probe=c918dcf201) | Feb 03, 2024 |
| MSI           | Modern 14 B11MOU            | [f7d0fcd205](https://linux-hardware.org/?probe=f7d0fcd205) | Feb 02, 2024 |
| Lenovo        | ThinkPad T410 2537AF8       | [88794835fb](https://linux-hardware.org/?probe=88794835fb) | Feb 02, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a3932a77fb](https://linux-hardware.org/?probe=a3932a77fb) | Feb 01, 2024 |
| HP            | 15                          | [5abc868cce](https://linux-hardware.org/?probe=5abc868cce) | Jan 31, 2024 |
| ASUSTek       | N550JK                      | [097f96652f](https://linux-hardware.org/?probe=097f96652f) | Jan 29, 2024 |
| HP            | Compaq nc6320 (EN371UA#A... | [24bcfc0005](https://linux-hardware.org/?probe=24bcfc0005) | Jan 28, 2024 |
| MSI           | GL62M 7RDX                  | [bd42ee7dc8](https://linux-hardware.org/?probe=bd42ee7dc8) | Jan 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [58f6bacae6](https://linux-hardware.org/?probe=58f6bacae6) | Jan 21, 2024 |
| Dell          | Latitude D630               | [bf9ce8c208](https://linux-hardware.org/?probe=bf9ce8c208) | Jan 21, 2024 |
| Dell          | Latitude D630               | [b2a68014db](https://linux-hardware.org/?probe=b2a68014db) | Jan 21, 2024 |
| Lenovo        | ThinkPad T490 20N2000RRT    | [b48f14a503](https://linux-hardware.org/?probe=b48f14a503) | Jan 20, 2024 |
| HP            | ProBook 640 G2              | [b09c608815](https://linux-hardware.org/?probe=b09c608815) | Jan 19, 2024 |
| Multilaser    | MLGW08                      | [abfe537d6f](https://linux-hardware.org/?probe=abfe537d6f) | Jan 15, 2024 |
| HP            | Compaq 6720s                | [4b6c283ab3](https://linux-hardware.org/?probe=4b6c283ab3) | Jan 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [a485e19625](https://linux-hardware.org/?probe=a485e19625) | Jan 12, 2024 |
| HP            | 348 G5                      | [a7c6a60aaf](https://linux-hardware.org/?probe=a7c6a60aaf) | Jan 12, 2024 |
| HP            | 530 Notebook PC(GH634AA#... | [a17c4145f4](https://linux-hardware.org/?probe=a17c4145f4) | Jan 11, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [5479dc0213](https://linux-hardware.org/?probe=5479dc0213) | Jan 11, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [48bddf33da](https://linux-hardware.org/?probe=48bddf33da) | Jan 11, 2024 |
| Unknown       | Unknown                     | [0f2d55f419](https://linux-hardware.org/?probe=0f2d55f419) | Jan 11, 2024 |
| Unknown       | Unknown                     | [f5d4b22b3c](https://linux-hardware.org/?probe=f5d4b22b3c) | Jan 11, 2024 |
| HP            | ProBook 650 G1              | [90b63b0d8a](https://linux-hardware.org/?probe=90b63b0d8a) | Jan 10, 2024 |
| HP            | EliteBook 2530p             | [0de99e6532](https://linux-hardware.org/?probe=0de99e6532) | Jan 09, 2024 |
| HP            | ProBook 6545b               | [278d4aea3c](https://linux-hardware.org/?probe=278d4aea3c) | Jan 09, 2024 |
| Acer          | TMP455-M                    | [559512a222](https://linux-hardware.org/?probe=559512a222) | Jan 09, 2024 |
| Dell          | Precision 5570              | [acc6213478](https://linux-hardware.org/?probe=acc6213478) | Jan 08, 2024 |
| HP            | 350 G2                      | [75e4063ce8](https://linux-hardware.org/?probe=75e4063ce8) | Jan 07, 2024 |
| Toshiba       | PORTEGE R500                | [315837012b](https://linux-hardware.org/?probe=315837012b) | Jan 07, 2024 |
| Lenovo        | V15-ADA 82C7                | [80604ec459](https://linux-hardware.org/?probe=80604ec459) | Dec 30, 2023 |
| HP            | Laptop 17-cp0xxx            | [4118aee355](https://linux-hardware.org/?probe=4118aee355) | Dec 28, 2023 |
| HP            | Laptop 17-cp0xxx            | [7b5e390f00](https://linux-hardware.org/?probe=7b5e390f00) | Dec 27, 2023 |
| Clevo         | W240BU                      | [a0d883bb3d](https://linux-hardware.org/?probe=a0d883bb3d) | Dec 20, 2023 |
| ASUSTek       | K52Jc                       | [dfa5dc9cd9](https://linux-hardware.org/?probe=dfa5dc9cd9) | Dec 14, 2023 |
| Sony          | VPCEG18FG                   | [3cf20aa9ea](https://linux-hardware.org/?probe=3cf20aa9ea) | Dec 14, 2023 |
| HP            | ProBook 4540s               | [24875256cd](https://linux-hardware.org/?probe=24875256cd) | Dec 14, 2023 |
| HP            | Pavilion g6                 | [920939b6c0](https://linux-hardware.org/?probe=920939b6c0) | Dec 13, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [21b8166e02](https://linux-hardware.org/?probe=21b8166e02) | Dec 06, 2023 |
| Apple         | MacBookPro5,5               | [82dedf4be4](https://linux-hardware.org/?probe=82dedf4be4) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | [01485bc011](https://linux-hardware.org/?probe=01485bc011) | Dec 04, 2023 |
| HP            | 255 G8 Notebook PC          | [2afc97f78a](https://linux-hardware.org/?probe=2afc97f78a) | Dec 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [0869816e7a](https://linux-hardware.org/?probe=0869816e7a) | Dec 02, 2023 |
| Sony          | VPCEB46FX                   | [b331dc017f](https://linux-hardware.org/?probe=b331dc017f) | Dec 02, 2023 |
| HP            | Pavilion dv6                | [ddce26dd72](https://linux-hardware.org/?probe=ddce26dd72) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [1b7f8a15dd](https://linux-hardware.org/?probe=1b7f8a15dd) | Nov 29, 2023 |
| Daten Tecn... | DCM3A-4                     | [66b8d06d48](https://linux-hardware.org/?probe=66b8d06d48) | Nov 27, 2023 |
| HP            | Laptop 15s-fq2xxx           | [f0b4d1d85c](https://linux-hardware.org/?probe=f0b4d1d85c) | Nov 26, 2023 |
| Lenovo        | G580 2189                   | [3ec9fbcdea](https://linux-hardware.org/?probe=3ec9fbcdea) | Nov 20, 2023 |
| HP            | Laptop 15-da0xxx            | [fa116d20dc](https://linux-hardware.org/?probe=fa116d20dc) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [a566513a93](https://linux-hardware.org/?probe=a566513a93) | Nov 19, 2023 |
| Lenovo        | G580 2189                   | [9a96aff4c7](https://linux-hardware.org/?probe=9a96aff4c7) | Nov 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [204303d116](https://linux-hardware.org/?probe=204303d116) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [026b13382d](https://linux-hardware.org/?probe=026b13382d) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [893762777e](https://linux-hardware.org/?probe=893762777e) | Nov 17, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [e7e00bb090](https://linux-hardware.org/?probe=e7e00bb090) | Nov 16, 2023 |
| Acer          | Extensa 215-32              | [477b965e66](https://linux-hardware.org/?probe=477b965e66) | Nov 15, 2023 |
| Phoenix/Si... | M730SR                      | [59e9d07293](https://linux-hardware.org/?probe=59e9d07293) | Nov 14, 2023 |
| TUXEDO        | Unknown                     | [e90f4e1799](https://linux-hardware.org/?probe=e90f4e1799) | Nov 14, 2023 |
| Packard Be... | EasyNote TK81               | [a44fd2dc7a](https://linux-hardware.org/?probe=a44fd2dc7a) | Nov 14, 2023 |
| Apple         | MacBookPro5,5               | [57e4a13fab](https://linux-hardware.org/?probe=57e4a13fab) | Nov 13, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [2bc7d7c816](https://linux-hardware.org/?probe=2bc7d7c816) | Nov 13, 2023 |
| HP            | EliteBook 2530p             | [4a9666ef8a](https://linux-hardware.org/?probe=4a9666ef8a) | Nov 12, 2023 |
| Acer          | Aspire A315-54              | [a83ac39876](https://linux-hardware.org/?probe=a83ac39876) | Nov 10, 2023 |
| Acer          | Aspire F5-573G              | [afeda2ac5e](https://linux-hardware.org/?probe=afeda2ac5e) | Nov 08, 2023 |
| HP            | Stream Notebook PC 13       | [25387a2c6f](https://linux-hardware.org/?probe=25387a2c6f) | Nov 08, 2023 |
| Lenovo        | ThinkPad X121e 30515YG      | [4008ec0eb0](https://linux-hardware.org/?probe=4008ec0eb0) | Nov 08, 2023 |
| Lenovo        | ThinkPad T470 20HES3JR02    | [4cdded6623](https://linux-hardware.org/?probe=4cdded6623) | Nov 07, 2023 |
| Acer          | AO532h                      | [0b3d66b04a](https://linux-hardware.org/?probe=0b3d66b04a) | Nov 04, 2023 |
| Packard Be... | EasyNote TK87               | [3ff2e66179](https://linux-hardware.org/?probe=3ff2e66179) | Nov 03, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [212105774f](https://linux-hardware.org/?probe=212105774f) | Nov 02, 2023 |
| HP            | Pavilion g6                 | [8c9de8be4f](https://linux-hardware.org/?probe=8c9de8be4f) | Nov 02, 2023 |
| HP            | Pavilion g6                 | [c35f9a55aa](https://linux-hardware.org/?probe=c35f9a55aa) | Nov 02, 2023 |
| Acer          | TravelMate P215-52          | [b9c3643e62](https://linux-hardware.org/?probe=b9c3643e62) | Nov 01, 2023 |
| HP            | 255 G8 Notebook PC          | [b9d1b13098](https://linux-hardware.org/?probe=b9d1b13098) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [8b1fe7cf44](https://linux-hardware.org/?probe=8b1fe7cf44) | Oct 30, 2023 |
| HP            | Pavilion g6                 | [57441db309](https://linux-hardware.org/?probe=57441db309) | Oct 29, 2023 |
| Toshiba       | TECRA R950                  | [afa984b0d3](https://linux-hardware.org/?probe=afa984b0d3) | Oct 28, 2023 |
| Acer          | Aspire A115-31              | [137821ca25](https://linux-hardware.org/?probe=137821ca25) | Oct 28, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B4I... | [afce107e0d](https://linux-hardware.org/?probe=afce107e0d) | Oct 26, 2023 |
| Matsushita... | CF-30CTWAZBM                | [4211783dac](https://linux-hardware.org/?probe=4211783dac) | Oct 25, 2023 |
| MSI           | GT62VR 6RD                  | [0d10c5251c](https://linux-hardware.org/?probe=0d10c5251c) | Oct 23, 2023 |
| Packard Be... | EasyNote TE11HC             | [dc33bae348](https://linux-hardware.org/?probe=dc33bae348) | Oct 21, 2023 |
| Acer          | Aspire A315-34              | [1ec00092e6](https://linux-hardware.org/?probe=1ec00092e6) | Oct 19, 2023 |
| Juana Mans... | SF20GM7                     | [ea7e37eb5d](https://linux-hardware.org/?probe=ea7e37eb5d) | Oct 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | [9d77b16e0b](https://linux-hardware.org/?probe=9d77b16e0b) | Oct 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00F0GE    | [61c5a7e37a](https://linux-hardware.org/?probe=61c5a7e37a) | Oct 13, 2023 |
| Dell          | Latitude E6520              | [30a511af92](https://linux-hardware.org/?probe=30a511af92) | Oct 13, 2023 |
| Toshiba       | Satellite L755              | [679e27a869](https://linux-hardware.org/?probe=679e27a869) | Oct 12, 2023 |
| Apple         | MacBookPro9,2               | [f53b6f5e53](https://linux-hardware.org/?probe=f53b6f5e53) | Oct 11, 2023 |
| ASUSTek       | N751JK                      | [855d2e95a7](https://linux-hardware.org/?probe=855d2e95a7) | Oct 09, 2023 |
| Toshiba       | Satellite L755              | [74a043fcf5](https://linux-hardware.org/?probe=74a043fcf5) | Oct 09, 2023 |
| Lenovo        | Legion Y920-17IKB Laptop... | [881454bd02](https://linux-hardware.org/?probe=881454bd02) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | [cae6954f11](https://linux-hardware.org/?probe=cae6954f11) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | [ca68af85fb](https://linux-hardware.org/?probe=ca68af85fb) | Oct 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [71bc4e1d3f](https://linux-hardware.org/?probe=71bc4e1d3f) | Oct 07, 2023 |
| Dell          | Latitude E6520              | [fea9ed801a](https://linux-hardware.org/?probe=fea9ed801a) | Oct 07, 2023 |
| Toshiba       | Satellite L755              | [63ad812f2f](https://linux-hardware.org/?probe=63ad812f2f) | Oct 06, 2023 |
| Exo           | Smart Serie L               | [812041d985](https://linux-hardware.org/?probe=812041d985) | Oct 05, 2023 |
| Philco Inf... | EC10IS2                     | [f85315b46a](https://linux-hardware.org/?probe=f85315b46a) | Oct 04, 2023 |
| Unknown       | Unknown                     | [a6849f7516](https://linux-hardware.org/?probe=a6849f7516) | Oct 03, 2023 |
| Teclast       | F15Plus 2                   | [3779ac7003](https://linux-hardware.org/?probe=3779ac7003) | Oct 01, 2023 |
| HP            | Laptop 15-dw3xxx            | [6443df8957](https://linux-hardware.org/?probe=6443df8957) | Oct 01, 2023 |
| Packard Be... | EasyNote LM98               | [8fdf8eee6c](https://linux-hardware.org/?probe=8fdf8eee6c) | Oct 01, 2023 |
| HP            | Laptop 14s-fq1xxx           | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| Juana Mans... | SF20GM7                     | [b2b359c659](https://linux-hardware.org/?probe=b2b359c659) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | [ccb9b4e795](https://linux-hardware.org/?probe=ccb9b4e795) | Sep 30, 2023 |
| Dell          | Latitude 5410               | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| Dell          | Latitude 5410               | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| HP            | 250 G4                      | [c9dac1b4d5](https://linux-hardware.org/?probe=c9dac1b4d5) | Sep 23, 2023 |
| HP            | Compaq Presario CQ60        | [ae8071638f](https://linux-hardware.org/?probe=ae8071638f) | Sep 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1e9774c53c](https://linux-hardware.org/?probe=1e9774c53c) | Sep 22, 2023 |
| ASUSTek       | X555LJ                      | [2edb781d68](https://linux-hardware.org/?probe=2edb781d68) | Sep 22, 2023 |
| Dell          | Precision 5560              | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| Dell          | Precision 7550              | [75394df91f](https://linux-hardware.org/?probe=75394df91f) | Sep 19, 2023 |
| Lenovo        | Z50-75 80EC                 | [410df263b8](https://linux-hardware.org/?probe=410df263b8) | Sep 18, 2023 |
| Acer          | Extensa 215-32              | [6879449933](https://linux-hardware.org/?probe=6879449933) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | [e14140ad96](https://linux-hardware.org/?probe=e14140ad96) | Sep 18, 2023 |
| Acer          | TravelMate P446-MG          | [08d9d6868b](https://linux-hardware.org/?probe=08d9d6868b) | Sep 17, 2023 |
| Google        | Droid                       | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [3eb787f2ec](https://linux-hardware.org/?probe=3eb787f2ec) | Sep 15, 2023 |
| SLIMBOOK      | Essential15L                | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| Panasonic     | CF-19RHR3DPM                | [11484f2d00](https://linux-hardware.org/?probe=11484f2d00) | Sep 10, 2023 |
| Dell          | Precision 5530              | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| Acer          | Extensa 5220                | [c4ea757260](https://linux-hardware.org/?probe=c4ea757260) | Sep 10, 2023 |
| Acer          | Aspire E1-531               | [91decda3c9](https://linux-hardware.org/?probe=91decda3c9) | Sep 09, 2023 |
| HP            | Compaq Presario CQ40        | [4695b758c9](https://linux-hardware.org/?probe=4695b758c9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [e8a4fb3aea](https://linux-hardware.org/?probe=e8a4fb3aea) | Sep 08, 2023 |
| Dell          | Latitude E5550              | [90fc999e4a](https://linux-hardware.org/?probe=90fc999e4a) | Sep 08, 2023 |
| ASUSTek       | N751JX                      | [8ece217753](https://linux-hardware.org/?probe=8ece217753) | Sep 06, 2023 |
| Acer          | Aspire ES1-533              | [9c788645a1](https://linux-hardware.org/?probe=9c788645a1) | Sep 03, 2023 |
| HP            | EliteBook 2740p             | [c6d9dc5a3b](https://linux-hardware.org/?probe=c6d9dc5a3b) | Sep 03, 2023 |
| Dell          | Latitude E6520              | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| HP            | ProBook 6460b               | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| HP            | Pavilion dv5                | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| Acer          | Aspire VN7-793G             | [5d748b1e22](https://linux-hardware.org/?probe=5d748b1e22) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | [113a5418ca](https://linux-hardware.org/?probe=113a5418ca) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | [b2579f594d](https://linux-hardware.org/?probe=b2579f594d) | Aug 25, 2023 |
| Lenovo        | IdeaPad Z485 20151          | [599346f806](https://linux-hardware.org/?probe=599346f806) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | [0a000435ae](https://linux-hardware.org/?probe=0a000435ae) | Aug 23, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| HP            | 250 G7 Notebook PC          | [cb4da51551](https://linux-hardware.org/?probe=cb4da51551) | Aug 21, 2023 |
| Apple         | MacBookAir7,2               | [fb3c8c793c](https://linux-hardware.org/?probe=fb3c8c793c) | Aug 19, 2023 |
| Acer          | Aspire VN7-793G             | [b88e1a5605](https://linux-hardware.org/?probe=b88e1a5605) | Aug 18, 2023 |
| Acer          | Aspire one                  | [47131c09b2](https://linux-hardware.org/?probe=47131c09b2) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [66c997fdec](https://linux-hardware.org/?probe=66c997fdec) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [e57e76260c](https://linux-hardware.org/?probe=e57e76260c) | Aug 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [4c24f10db4](https://linux-hardware.org/?probe=4c24f10db4) | Aug 15, 2023 |
| Lenovo        | ThinkPad W530 24477V0       | [2e09955f2f](https://linux-hardware.org/?probe=2e09955f2f) | Aug 13, 2023 |
| Apple         | MacBookPro8,1               | [c7bc7c3f16](https://linux-hardware.org/?probe=c7bc7c3f16) | Aug 13, 2023 |
| Unknown       | Unknown                     | [2e76349d2c](https://linux-hardware.org/?probe=2e76349d2c) | Aug 12, 2023 |
| ASUSTek       | 1005PE                      | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| Dell          | Inspiron 15 3511            | [217bd70a25](https://linux-hardware.org/?probe=217bd70a25) | Aug 06, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| HP            | Lantis                      | [2c917365b3](https://linux-hardware.org/?probe=2c917365b3) | Aug 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| Packard Be... | H17HV                       | [de2003d390](https://linux-hardware.org/?probe=de2003d390) | Jul 31, 2023 |
| NEC Comput... | PC-VY22GXZCA                | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| Apple         | MacBookPro5,5               | [f201460a34](https://linux-hardware.org/?probe=f201460a34) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Lenovo        | ThinkPad X220 42914XG       | [053a30cc87](https://linux-hardware.org/?probe=053a30cc87) | Jul 30, 2023 |
| Sony          | SVS13A1Z9RN                 | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Dell          | Latitude 5520               | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| Acer          | Extensa 215-32              | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [b2dd23136f](https://linux-hardware.org/?probe=b2dd23136f) | Jul 26, 2023 |
| Apple         | MacBookPro5,5               | [9cf2abf318](https://linux-hardware.org/?probe=9cf2abf318) | Jul 25, 2023 |
| Dell          | Inspiron 15 3511            | [980ed56abe](https://linux-hardware.org/?probe=980ed56abe) | Jul 24, 2023 |
| Dell          | Latitude E7250              | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Dell          | Latitude 7480               | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| ASUSTek       | K72Jr                       | [cdb9b29f94](https://linux-hardware.org/?probe=cdb9b29f94) | Jul 21, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [fc45e9b064](https://linux-hardware.org/?probe=fc45e9b064) | Jul 21, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [820630ba9e](https://linux-hardware.org/?probe=820630ba9e) | Jul 20, 2023 |
| HP            | EliteBook 8570p             | [8e456f1108](https://linux-hardware.org/?probe=8e456f1108) | Jul 18, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [f789cd31fa](https://linux-hardware.org/?probe=f789cd31fa) | Jul 18, 2023 |
| Toshiba       | Satellite L755              | [da4d6e8a5c](https://linux-hardware.org/?probe=da4d6e8a5c) | Jul 18, 2023 |
| ASUSTek       | X505BA                      | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| Dell          | Inspiron 16 7610            | [6d77ef17a0](https://linux-hardware.org/?probe=6d77ef17a0) | Jul 17, 2023 |
| Dell          | Latitude E6440              | [c1de0cf4d1](https://linux-hardware.org/?probe=c1de0cf4d1) | Jul 16, 2023 |
| Dell          | Latitude E6320              | [0087a8e5cf](https://linux-hardware.org/?probe=0087a8e5cf) | Jul 16, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [65e4fb1356](https://linux-hardware.org/?probe=65e4fb1356) | Jul 16, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [8d3168b6c4](https://linux-hardware.org/?probe=8d3168b6c4) | Jul 15, 2023 |
| Acer          | Aspire R7-371T              | [c4f6270bdb](https://linux-hardware.org/?probe=c4f6270bdb) | Jul 15, 2023 |
| Dell          | Inspiron 15 3511            | [e6d47a005f](https://linux-hardware.org/?probe=e6d47a005f) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [ae8ecf10e7](https://linux-hardware.org/?probe=ae8ecf10e7) | Jul 13, 2023 |
| Lenovo        | V14-IIL 82C4                | [42aba63af0](https://linux-hardware.org/?probe=42aba63af0) | Jul 13, 2023 |
| Dell          | Latitude E6330              | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| Positivo      | Mobile                      | [463636c0a2](https://linux-hardware.org/?probe=463636c0a2) | Jul 12, 2023 |
| Lenovo        | G570 4334                   | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK E780               | [ab432dcb0e](https://linux-hardware.org/?probe=ab432dcb0e) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [33aa3fcdbc](https://linux-hardware.org/?probe=33aa3fcdbc) | Jul 10, 2023 |
| Toshiba       | PORTEGE Z30-C               | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| HP            | EliteBook 1040 G4           | [cbc100e6b1](https://linux-hardware.org/?probe=cbc100e6b1) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | [3177785c7f](https://linux-hardware.org/?probe=3177785c7f) | Jul 07, 2023 |
| Lenovo        | ThinkPad T450s 20BWS0PJ0... | [2345d00757](https://linux-hardware.org/?probe=2345d00757) | Jul 07, 2023 |
| Dell          | Inspiron 15-3565            | [69d01e9a98](https://linux-hardware.org/?probe=69d01e9a98) | Jul 05, 2023 |
| NEC Comput... | PC-VK27MBZCG                | [5db0d02025](https://linux-hardware.org/?probe=5db0d02025) | Jul 04, 2023 |
| HP            | EliteBook 6930p             | [b7328dc212](https://linux-hardware.org/?probe=b7328dc212) | Jul 04, 2023 |
| HP            | EliteBook 840 G3            | [ed37dd6278](https://linux-hardware.org/?probe=ed37dd6278) | Jul 03, 2023 |
| Fujitsu       | LIFEBOOK E780               | [2eb6c4356c](https://linux-hardware.org/?probe=2eb6c4356c) | Jul 02, 2023 |
| HUAWEI        | BOM-WXX9                    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| Apple         | MacBookAir7,2               | [cb1bcce659](https://linux-hardware.org/?probe=cb1bcce659) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | TravelMate P449-G2-M        | [b9291d6951](https://linux-hardware.org/?probe=b9291d6951) | Jun 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Dell          | Latitude 7370               | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| ASUSTek       | K53SJ                       | [fe211e4239](https://linux-hardware.org/?probe=fe211e4239) | Jun 26, 2023 |
| HP            | Laptop 14-dq0xxx            | [695dd94347](https://linux-hardware.org/?probe=695dd94347) | Jun 25, 2023 |
| Acer          | Aspire VN7-591G             | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| Google        | Kip                         | [4e1bfd359e](https://linux-hardware.org/?probe=4e1bfd359e) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| Lenovo        | Edge 15 80H1                | [aff25effc2](https://linux-hardware.org/?probe=aff25effc2) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [6d8c00ff02](https://linux-hardware.org/?probe=6d8c00ff02) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [1c1a2724f4](https://linux-hardware.org/?probe=1c1a2724f4) | Jun 23, 2023 |
| VIT           | P2423                       | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| Dell          | Inspiron 1525               | [1cdf3502e8](https://linux-hardware.org/?probe=1cdf3502e8) | Jun 21, 2023 |
| Dell          | Inspiron 1525               | [7bbc89ec0f](https://linux-hardware.org/?probe=7bbc89ec0f) | Jun 21, 2023 |
| Dell          | Latitude E5550              | [72f4d53246](https://linux-hardware.org/?probe=72f4d53246) | Jun 21, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [76fbd356a0](https://linux-hardware.org/?probe=76fbd356a0) | Jun 21, 2023 |
| Dell          | Latitude E5550              | [e1fdcf84b3](https://linux-hardware.org/?probe=e1fdcf84b3) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| Packard Be... | EasyNote TE11HC             | [6bbc56b36c](https://linux-hardware.org/?probe=6bbc56b36c) | Jun 20, 2023 |
| Apple         | MacBookPro5,5               | [16c4045c3b](https://linux-hardware.org/?probe=16c4045c3b) | Jun 20, 2023 |
| Acer          | TravelMate P449-G2-M        | [98626bde6c](https://linux-hardware.org/?probe=98626bde6c) | Jun 20, 2023 |
| Dell          | Latitude 3410               | [1e0348842a](https://linux-hardware.org/?probe=1e0348842a) | Jun 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Packard Be... | EasyNote TE11HC             | [33785e2493](https://linux-hardware.org/?probe=33785e2493) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| Dell          | Precision M2800             | [e9f259595a](https://linux-hardware.org/?probe=e9f259595a) | Jun 17, 2023 |
| Acer          | Aspire E1-571               | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| Dell          | Latitude D620               | [8dc25931d7](https://linux-hardware.org/?probe=8dc25931d7) | Jun 16, 2023 |
| Dell          | Latitude D620               | [819f346812](https://linux-hardware.org/?probe=819f346812) | Jun 16, 2023 |
| Dell          | Latitude E6400              | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| HP            | Laptop 14-cm0xxx            | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| Medion        | E6214                       | [71b2e69534](https://linux-hardware.org/?probe=71b2e69534) | Jun 15, 2023 |
| Toshiba       | Satellite L45-B             | [4cc6199522](https://linux-hardware.org/?probe=4cc6199522) | Jun 15, 2023 |
| Dell          | Latitude 5480               | [677cb87f98](https://linux-hardware.org/?probe=677cb87f98) | Jun 14, 2023 |
| Apple         | MacBookPro5,5               | [b639a64b45](https://linux-hardware.org/?probe=b639a64b45) | Jun 14, 2023 |
| Fujitsu       | LIFEBOOK E780               | [b8631b65c4](https://linux-hardware.org/?probe=b8631b65c4) | Jun 13, 2023 |
| HP            | Pavilion dv7                | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Acer          | TravelMate P449-G2-M        | [97b6ba8bd6](https://linux-hardware.org/?probe=97b6ba8bd6) | Jun 13, 2023 |
| Apple         | MacBookAir7,2               | [b4a1eae7be](https://linux-hardware.org/?probe=b4a1eae7be) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [675f082570](https://linux-hardware.org/?probe=675f082570) | Jun 12, 2023 |
| Hampoo        | Cherry Trail CR V200        | [d2ee0bc234](https://linux-hardware.org/?probe=d2ee0bc234) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | [45b16c1cdf](https://linux-hardware.org/?probe=45b16c1cdf) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | [1da963b3f4](https://linux-hardware.org/?probe=1da963b3f4) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Dell          | Latitude 7440               | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| Acidanther... | MacBookPro15,2              | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| Intel         | powered classmate PC        | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| HP            | G42                         | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Acer          | TravelMate P449-G2-M        | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [d992393271](https://linux-hardware.org/?probe=d992393271) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [dd385507aa](https://linux-hardware.org/?probe=dd385507aa) | Jun 08, 2023 |
| HP            | Pavilion 17                 | [da809f90cc](https://linux-hardware.org/?probe=da809f90cc) | Jun 07, 2023 |
| Dell          | Latitude 5530               | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| HP            | ProBook 4530s               | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Intel         | HURONRIVER                  | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| MSI           | Pulse GL66 12UDK            | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| HP            | Pavilion g7                 | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| Dell          | Latitude 3410               | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Dell          | Latitude 3410               | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| ASUSTek       | Q502LA                      | [679a477085](https://linux-hardware.org/?probe=679a477085) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| AVITA         | NS14A8                      | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| Apple         | MacBookPro7,1               | [b1513dc005](https://linux-hardware.org/?probe=b1513dc005) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| Dell          | Latitude E6430              | [b129765265](https://linux-hardware.org/?probe=b129765265) | Jun 02, 2023 |
| HP            | EliteBook 840 G6            | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| Dell          | System Inspiron N4110       | [ea09e45a4f](https://linux-hardware.org/?probe=ea09e45a4f) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Positivo      | C500                        | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| ASUSTek       | 1225B                       | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| Dell          | Latitude 5411               | [8583aa2091](https://linux-hardware.org/?probe=8583aa2091) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| Dell          | Latitude E5510              | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| HP            | Laptop 17-ca0xxx            | [3222c41173](https://linux-hardware.org/?probe=3222c41173) | May 30, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| Fujitsu       | LIFEBOOK E780               | [aac95cf765](https://linux-hardware.org/?probe=aac95cf765) | May 29, 2023 |
| Dell          | Latitude E5470              | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [deaa4b357c](https://linux-hardware.org/?probe=deaa4b357c) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [af312b5e91](https://linux-hardware.org/?probe=af312b5e91) | May 29, 2023 |
| Dell          | Latitude E6530              | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| Lenovo        | ThinkPad W530 2447GH2       | [f902d43115](https://linux-hardware.org/?probe=f902d43115) | May 29, 2023 |
| Dell          | Latitude E6530              | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| HP            | Laptop 17-ca0xxx            | [4b53ed4ede](https://linux-hardware.org/?probe=4b53ed4ede) | May 29, 2023 |
| Lenovo        | Edge 15 80H1                | [75fdd71ca1](https://linux-hardware.org/?probe=75fdd71ca1) | May 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d5a3141562](https://linux-hardware.org/?probe=d5a3141562) | May 28, 2023 |
| HP            | EliteBook 840 G1            | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| HP            | Mini 110-3700               | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| HP            | G42                         | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| ASUSTek       | X550CA                      | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| ASUSTek       | K53SV                       | [357c1fd091](https://linux-hardware.org/?probe=357c1fd091) | May 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c3aa6334b](https://linux-hardware.org/?probe=4c3aa6334b) | May 26, 2023 |
| Acer          | Aspire A315-42              | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| Acer          | Aspire V3-551               | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| Dell          | Latitude 7220 Rugged Ext... | [442b7239c8](https://linux-hardware.org/?probe=442b7239c8) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| Notebook      | W54_55SU1,SUW               | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| HP            | 530                         | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [44b6477648](https://linux-hardware.org/?probe=44b6477648) | May 22, 2023 |
| ASUSTek       | N56VB                       | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| Unknown       | Unknown                     | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| HP            | Laptop 15-da0xxx            | [82f235bfbb](https://linux-hardware.org/?probe=82f235bfbb) | May 22, 2023 |
| HP            | Laptop 14-dq0xxx            | [4438fdd9b2](https://linux-hardware.org/?probe=4438fdd9b2) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0ab3a9817b](https://linux-hardware.org/?probe=0ab3a9817b) | May 21, 2023 |
| Dell          | Inspiron 5570               | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Dell          | Inspiron 3451               | [e69cefc8da](https://linux-hardware.org/?probe=e69cefc8da) | May 21, 2023 |
| Lenovo        | ThinkPad W510 4391DK3       | [ac8db768ce](https://linux-hardware.org/?probe=ac8db768ce) | May 20, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [e6e79ac2ca](https://linux-hardware.org/?probe=e6e79ac2ca) | May 20, 2023 |
| Dell          | Latitude 5411               | [8929285bca](https://linux-hardware.org/?probe=8929285bca) | May 19, 2023 |
| Dell          | Vostro 15 3515              | [6b5bc55aeb](https://linux-hardware.org/?probe=6b5bc55aeb) | May 18, 2023 |
| Dell          | Vostro 15 3515              | [e26f4ecf2f](https://linux-hardware.org/?probe=e26f4ecf2f) | May 18, 2023 |
| Lenovo        | ThinkPad X200s 7470WUB      | [e5ad235f60](https://linux-hardware.org/?probe=e5ad235f60) | May 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [5d69cc1112](https://linux-hardware.org/?probe=5d69cc1112) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| Acer          | Aspire A514-54              | [26dc842484](https://linux-hardware.org/?probe=26dc842484) | May 18, 2023 |
| Dell          | Latitude E7450              | [3000905b05](https://linux-hardware.org/?probe=3000905b05) | May 18, 2023 |
| Dell          | Latitude E7450              | [10f138711f](https://linux-hardware.org/?probe=10f138711f) | May 18, 2023 |
| Apple         | MacBookPro12,1              | [4aadc89f41](https://linux-hardware.org/?probe=4aadc89f41) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [8aef05613d](https://linux-hardware.org/?probe=8aef05613d) | May 17, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Dell          | Latitude 5521               | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| Acer          | AO532h                      | [6cfe2a58cc](https://linux-hardware.org/?probe=6cfe2a58cc) | May 15, 2023 |
| Acer          | Aspire 7745G                | [c1bcc07617](https://linux-hardware.org/?probe=c1bcc07617) | May 15, 2023 |
| Acer          | Aspire 7745G                | [7b0f6f3dc2](https://linux-hardware.org/?probe=7b0f6f3dc2) | May 15, 2023 |
| Dell          | G15 5510                    | [5624d414be](https://linux-hardware.org/?probe=5624d414be) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cd0a78ce39](https://linux-hardware.org/?probe=cd0a78ce39) | May 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| ASUSTek       | N56VB                       | [87d2f8b907](https://linux-hardware.org/?probe=87d2f8b907) | May 14, 2023 |
| ASUSTek       | N56VB                       | [7e2caae7ea](https://linux-hardware.org/?probe=7e2caae7ea) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Dell          | Latitude 7410               | [542e1d7f7b](https://linux-hardware.org/?probe=542e1d7f7b) | May 14, 2023 |
| AMI           | Intel                       | [958f5ffc92](https://linux-hardware.org/?probe=958f5ffc92) | May 14, 2023 |
| AMI           | Intel                       | [0c9a68a20c](https://linux-hardware.org/?probe=0c9a68a20c) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E5410              | [c62a002948](https://linux-hardware.org/?probe=c62a002948) | May 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [bf54c69e0c](https://linux-hardware.org/?probe=bf54c69e0c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| Toshiba       | Satellite Pro C660          | [848eedb681](https://linux-hardware.org/?probe=848eedb681) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| Apple         | MacBook10,1                 | [d26983a399](https://linux-hardware.org/?probe=d26983a399) | May 12, 2023 |
| HP            | ProBook 450 G7              | [ba542c09f2](https://linux-hardware.org/?probe=ba542c09f2) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| HP            | 250 G6 Notebook PC          | [f612c54f9c](https://linux-hardware.org/?probe=f612c54f9c) | May 09, 2023 |
| HP            | 250 G6 Notebook PC          | [9c14434a99](https://linux-hardware.org/?probe=9c14434a99) | May 09, 2023 |
| Unknown       | Unknown                     | [4a0ccb88d2](https://linux-hardware.org/?probe=4a0ccb88d2) | May 09, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [967e39a2d3](https://linux-hardware.org/?probe=967e39a2d3) | May 08, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYFR    | [f945ec106e](https://linux-hardware.org/?probe=f945ec106e) | May 07, 2023 |
| HP            | 255 G3                      | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| ASUSTek       | K73SJ                       | [13b8c8be10](https://linux-hardware.org/?probe=13b8c8be10) | May 07, 2023 |
| Dell          | Vostro 15-3568              | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| Acer          | Aspire AV15-51              | [9d7736a816](https://linux-hardware.org/?probe=9d7736a816) | May 06, 2023 |
| Lenovo        | IdeaPad Y480 20131          | [d625664bee](https://linux-hardware.org/?probe=d625664bee) | May 06, 2023 |
| Unknown       | Unknown                     | [dd406112de](https://linux-hardware.org/?probe=dd406112de) | May 06, 2023 |
| HP            | Laptop 15s-fq2xxx           | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| Acer          | Aspire 7741                 | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Lenovo        | ThinkPad T410 2537CC5       | [10de9f17e1](https://linux-hardware.org/?probe=10de9f17e1) | May 06, 2023 |
| Acer          | TravelMate P215-53          | [f7c7c572e4](https://linux-hardware.org/?probe=f7c7c572e4) | May 05, 2023 |
| Dell          | Inspiron 5770               | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 2i 21A... | [064df1260c](https://linux-hardware.org/?probe=064df1260c) | May 05, 2023 |
| Dell          | Latitude D630               | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Acer          | Aspire A515-52G             | [4f2fbcc26f](https://linux-hardware.org/?probe=4f2fbcc26f) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2660b0df6d](https://linux-hardware.org/?probe=2660b0df6d) | May 04, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [b68f20e323](https://linux-hardware.org/?probe=b68f20e323) | May 04, 2023 |
| Notebook      | W54_55SU1,SUW               | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f636b7c230](https://linux-hardware.org/?probe=f636b7c230) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [fc1bd7fffc](https://linux-hardware.org/?probe=fc1bd7fffc) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [c8373114ef](https://linux-hardware.org/?probe=c8373114ef) | May 03, 2023 |
| Lenovo        | ThinkPad T470 20HES63400    | [6628ac6681](https://linux-hardware.org/?probe=6628ac6681) | May 03, 2023 |
| HP            | Notebook                    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Dell          | Precision 7510              | [1e73564cf9](https://linux-hardware.org/?probe=1e73564cf9) | May 03, 2023 |
| Dell          | Latitude 5414               | [6922f7db46](https://linux-hardware.org/?probe=6922f7db46) | May 03, 2023 |
| Dell          | Latitude D630               | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Dell          | Latitude 7370               | [c984360af7](https://linux-hardware.org/?probe=c984360af7) | May 02, 2023 |
| Dell          | Latitude 7370               | [295b50d5b2](https://linux-hardware.org/?probe=295b50d5b2) | May 02, 2023 |
| MSI           | Katana GF76 12UEK           | [5af5d6aec3](https://linux-hardware.org/?probe=5af5d6aec3) | May 01, 2023 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3174c98e9c](https://linux-hardware.org/?probe=3174c98e9c) | May 01, 2023 |
| Acer          | Aspire E1-571               | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [07e2cc77f8](https://linux-hardware.org/?probe=07e2cc77f8) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [638e747fb1](https://linux-hardware.org/?probe=638e747fb1) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Positivo      | Q464C                       | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| COPELION I... | QX-250 Series               | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| Dell          | Latitude E7450              | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [e61f528ba5](https://linux-hardware.org/?probe=e61f528ba5) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [cec3a72c8a](https://linux-hardware.org/?probe=cec3a72c8a) | Apr 26, 2023 |
| Google        | Terra                       | [b22deb9f09](https://linux-hardware.org/?probe=b22deb9f09) | Apr 26, 2023 |
| Dell          | Latitude E6440              | [f5cdf825fa](https://linux-hardware.org/?probe=f5cdf825fa) | Apr 26, 2023 |
| HP            | ENVY 15                     | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| HP            | 250 G6 Notebook PC          | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| Lenovo        | ThinkPad T530 23594ZC       | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [aa1b58a2a2](https://linux-hardware.org/?probe=aa1b58a2a2) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [32546113c8](https://linux-hardware.org/?probe=32546113c8) | Apr 24, 2023 |
| HP            | 15                          | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [adee59c351](https://linux-hardware.org/?probe=adee59c351) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [c5c43186bc](https://linux-hardware.org/?probe=c5c43186bc) | Apr 23, 2023 |
| Dell          | G15 5520                    | [07751c950a](https://linux-hardware.org/?probe=07751c950a) | Apr 22, 2023 |
| HP            | Laptop 15s-du3xxx           | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [8c8d2eb3b5](https://linux-hardware.org/?probe=8c8d2eb3b5) | Apr 21, 2023 |
| Dell          | Precision 3550              | [7434822402](https://linux-hardware.org/?probe=7434822402) | Apr 21, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| HP            | Laptop 15-db0xxx            | [9ab965fcb8](https://linux-hardware.org/?probe=9ab965fcb8) | Apr 19, 2023 |
| Lenovo        | ThinkPad T500 2055WAB       | [4e293261bb](https://linux-hardware.org/?probe=4e293261bb) | Apr 19, 2023 |
| HP            | ProBook 450 G2              | [3b8c115c1a](https://linux-hardware.org/?probe=3b8c115c1a) | Apr 19, 2023 |
| Toshiba       | Satellite Pro A100          | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| HP            | 255 G8 Notebook PC          | [699e2a2a80](https://linux-hardware.org/?probe=699e2a2a80) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| LG Electro... | P530-KE6BK                  | [b1f0863c79](https://linux-hardware.org/?probe=b1f0863c79) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| Dell          | Latitude 5420               | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [d532f6fdbd](https://linux-hardware.org/?probe=d532f6fdbd) | Apr 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c622c73721](https://linux-hardware.org/?probe=c622c73721) | Apr 16, 2023 |
| HP            | Notebook                    | [7614984f1d](https://linux-hardware.org/?probe=7614984f1d) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| HP            | EliteBook 850 G4            | [984cf8fd47](https://linux-hardware.org/?probe=984cf8fd47) | Apr 14, 2023 |
| Acer          | Aspire E5-575G              | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [6fdb6931f0](https://linux-hardware.org/?probe=6fdb6931f0) | Apr 14, 2023 |
| Acer          | Extensa 5635Z               | [b3c99bf352](https://linux-hardware.org/?probe=b3c99bf352) | Apr 14, 2023 |
| Notebook      | N7x0WU                      | [5d37070bf0](https://linux-hardware.org/?probe=5d37070bf0) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Acer          | AO756                       | [58efd2f87f](https://linux-hardware.org/?probe=58efd2f87f) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| Apple         | MacBookPro5,5               | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [abedf2741f](https://linux-hardware.org/?probe=abedf2741f) | Apr 12, 2023 |
| HP            | ZBook 15 G3                 | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| HP            | Pavilion dv6                | [09b80dd551](https://linux-hardware.org/?probe=09b80dd551) | Apr 12, 2023 |
| HP            | Pavilion dv7                | [4363479bf0](https://linux-hardware.org/?probe=4363479bf0) | Apr 12, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | [ea2aa5245d](https://linux-hardware.org/?probe=ea2aa5245d) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [c074d665d9](https://linux-hardware.org/?probe=c074d665d9) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [845a04c326](https://linux-hardware.org/?probe=845a04c326) | Apr 11, 2023 |
| Packard Be... | EasyNote_MX45               | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire 5738                 | [c039220e20](https://linux-hardware.org/?probe=c039220e20) | Apr 11, 2023 |
| Dell          | Inspiron 15 5510            | [5d84a5a711](https://linux-hardware.org/?probe=5d84a5a711) | Apr 10, 2023 |
| Apple         | MacBookAir7,2               | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE1M    | [eb794b0dc7](https://linux-hardware.org/?probe=eb794b0dc7) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [fec574fe0d](https://linux-hardware.org/?probe=fec574fe0d) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [f97c4e6d47](https://linux-hardware.org/?probe=f97c4e6d47) | Apr 10, 2023 |
| Samsung       | RF511/RF411/RF711           | [ea4fdd80e6](https://linux-hardware.org/?probe=ea4fdd80e6) | Apr 09, 2023 |
| ASUSTek       | X756UQ                      | [bff5545041](https://linux-hardware.org/?probe=bff5545041) | Apr 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [fc28f6d3f0](https://linux-hardware.org/?probe=fc28f6d3f0) | Apr 08, 2023 |
| HP            | ENVY dv6                    | [0d89a1797e](https://linux-hardware.org/?probe=0d89a1797e) | Apr 08, 2023 |
| MSI           | GL65 Leopard 10SCSR         | [3063414a8c](https://linux-hardware.org/?probe=3063414a8c) | Apr 08, 2023 |
| Lenovo        | ThinkPad T450 20BUA05900    | [e771177cca](https://linux-hardware.org/?probe=e771177cca) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [6d50e55675](https://linux-hardware.org/?probe=6d50e55675) | Apr 07, 2023 |
| HP            | Pavilion dv7                | [3ec1e98abd](https://linux-hardware.org/?probe=3ec1e98abd) | Apr 07, 2023 |
| Google        | Reks                        | [25341f2040](https://linux-hardware.org/?probe=25341f2040) | Apr 07, 2023 |
| Google        | Reks                        | [21c7e0c282](https://linux-hardware.org/?probe=21c7e0c282) | Apr 07, 2023 |
| Google        | Terra                       | [09a6a1ca8f](https://linux-hardware.org/?probe=09a6a1ca8f) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [a74c66fc15](https://linux-hardware.org/?probe=a74c66fc15) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [46990342e8](https://linux-hardware.org/?probe=46990342e8) | Apr 06, 2023 |
| Acer          | TravelMate 5735Z            | [6d0065dea2](https://linux-hardware.org/?probe=6d0065dea2) | Apr 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [d5c75a0967](https://linux-hardware.org/?probe=d5c75a0967) | Apr 06, 2023 |
| Dell          | Latitude E7250              | [e5fe0c7962](https://linux-hardware.org/?probe=e5fe0c7962) | Apr 06, 2023 |
| Toshiba       | Satellite C855D-12J         | [cb3dedf5e8](https://linux-hardware.org/?probe=cb3dedf5e8) | Apr 05, 2023 |
| Acer          | Aspire E1-532               | [ba90a2c123](https://linux-hardware.org/?probe=ba90a2c123) | Apr 05, 2023 |
| Dell          | Precision M4700             | [1e2be52d80](https://linux-hardware.org/?probe=1e2be52d80) | Apr 05, 2023 |
| Acer          | TravelMate P215-53          | [0808bd0d17](https://linux-hardware.org/?probe=0808bd0d17) | Apr 04, 2023 |
| Apple         | MacBookPro10,2              | [ad5d8f611a](https://linux-hardware.org/?probe=ad5d8f611a) | Apr 04, 2023 |
| Dell          | Latitude 5430               | [6494113c9b](https://linux-hardware.org/?probe=6494113c9b) | Apr 04, 2023 |
| HP            | EliteBook 840 G3            | [36f4574fd4](https://linux-hardware.org/?probe=36f4574fd4) | Apr 03, 2023 |
| Lenovo        | ThinkPad T530 242962G       | [58d0ea734d](https://linux-hardware.org/?probe=58d0ea734d) | Apr 03, 2023 |
| Toshiba       | Satellite Pro C850-1K0      | [893534249a](https://linux-hardware.org/?probe=893534249a) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [0f4881cccf](https://linux-hardware.org/?probe=0f4881cccf) | Apr 03, 2023 |
| HP            | EliteBook 850 G6            | [1af731cc92](https://linux-hardware.org/?probe=1af731cc92) | Apr 03, 2023 |
| Clevo         | P170HMx                     | [c963b350fc](https://linux-hardware.org/?probe=c963b350fc) | Apr 03, 2023 |
| Apple         | MacBookAir6,1               | [423c5d2481](https://linux-hardware.org/?probe=423c5d2481) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3034a3d11a](https://linux-hardware.org/?probe=3034a3d11a) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [89d4ef9333](https://linux-hardware.org/?probe=89d4ef9333) | Apr 02, 2023 |
| Acer          | Aspire A515-45              | [8fa60907d5](https://linux-hardware.org/?probe=8fa60907d5) | Apr 02, 2023 |
| Dell          | Precision M4700             | [aea1cc51a5](https://linux-hardware.org/?probe=aea1cc51a5) | Apr 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | [9e25dfd6bb](https://linux-hardware.org/?probe=9e25dfd6bb) | Apr 02, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [e42bc1dd05](https://linux-hardware.org/?probe=e42bc1dd05) | Apr 02, 2023 |
| Acer          | TravelMate P215-53          | [bd1d2b4102](https://linux-hardware.org/?probe=bd1d2b4102) | Apr 02, 2023 |
| Google        | Snappy                      | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| Dell          | Precision 5540              | [f25b25b590](https://linux-hardware.org/?probe=f25b25b590) | Apr 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2f2326e574](https://linux-hardware.org/?probe=2f2326e574) | Apr 02, 2023 |
| HP            | Notebook                    | [348d80772f](https://linux-hardware.org/?probe=348d80772f) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| HP            | Pavilion dv7                | [00bbec023a](https://linux-hardware.org/?probe=00bbec023a) | Apr 01, 2023 |
| ASUSTek       | X202E                       | [cdcccb09e7](https://linux-hardware.org/?probe=cdcccb09e7) | Mar 31, 2023 |
| ASUSTek       | X202E                       | [ac12ec53a3](https://linux-hardware.org/?probe=ac12ec53a3) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Dell          | Latitude E6330              | [ae7a7254b8](https://linux-hardware.org/?probe=ae7a7254b8) | Mar 31, 2023 |
| Dell          | Latitude E6330              | [2239e12384](https://linux-hardware.org/?probe=2239e12384) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Dell          | Precision M4700             | [7c93bc178e](https://linux-hardware.org/?probe=7c93bc178e) | Mar 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [2ca1607b80](https://linux-hardware.org/?probe=2ca1607b80) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | [990f324256](https://linux-hardware.org/?probe=990f324256) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | [b6226ae481](https://linux-hardware.org/?probe=b6226ae481) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | [bf3d484605](https://linux-hardware.org/?probe=bf3d484605) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | [3e4d9fac89](https://linux-hardware.org/?probe=3e4d9fac89) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e85544a3d7](https://linux-hardware.org/?probe=e85544a3d7) | Mar 30, 2023 |
| Dell          | Precision M4800             | [ebd0442adc](https://linux-hardware.org/?probe=ebd0442adc) | Mar 30, 2023 |
| Lenovo        | ThinkPad T60 195143U        | [4de196550b](https://linux-hardware.org/?probe=4de196550b) | Mar 30, 2023 |
| OEGStone      | W54_55SU1,SUW               | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| Unknown       | Unknown                     | [7d3374d52b](https://linux-hardware.org/?probe=7d3374d52b) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| Lenovo        | G50-45 80E3                 | [7bfed0aedd](https://linux-hardware.org/?probe=7bfed0aedd) | Mar 29, 2023 |
| Acer          | Aspire A315-23G             | [5c6734f5e6](https://linux-hardware.org/?probe=5c6734f5e6) | Mar 29, 2023 |
| Medion        | P7641 MD99856               | [7347a28d53](https://linux-hardware.org/?probe=7347a28d53) | Mar 28, 2023 |
| HP            | Pavilion dv5000 (EW771EA... | [db28f35ce0](https://linux-hardware.org/?probe=db28f35ce0) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| HP            | EliteBook 840 G3            | [58d5e99cd1](https://linux-hardware.org/?probe=58d5e99cd1) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [dd84425bc7](https://linux-hardware.org/?probe=dd84425bc7) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [d1f406ffe7](https://linux-hardware.org/?probe=d1f406ffe7) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | [d2f95decbe](https://linux-hardware.org/?probe=d2f95decbe) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | [1377a2ea15](https://linux-hardware.org/?probe=1377a2ea15) | Mar 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0C40... | [39b2a59543](https://linux-hardware.org/?probe=39b2a59543) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Packard Be... | H17HV                       | [c4bddccbd8](https://linux-hardware.org/?probe=c4bddccbd8) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | Inspiron 7348               | [4011322039](https://linux-hardware.org/?probe=4011322039) | Mar 24, 2023 |
| HP            | EliteBook 850 G5            | [cde421908c](https://linux-hardware.org/?probe=cde421908c) | Mar 24, 2023 |
| ASUSTek       | N56VJ                       | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| Dell          | Inspiron 15 3511            | [7aa41dd248](https://linux-hardware.org/?probe=7aa41dd248) | Mar 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [32a4fc1880](https://linux-hardware.org/?probe=32a4fc1880) | Mar 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Dell          | G3 3579                     | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Apple         | MacBookPro5,5               | [849f9d23c7](https://linux-hardware.org/?probe=849f9d23c7) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230s 20AHS0070... | [9d86eaf558](https://linux-hardware.org/?probe=9d86eaf558) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| HP            | EliteBook 850 G5            | [5ca3a1b044](https://linux-hardware.org/?probe=5ca3a1b044) | Mar 21, 2023 |
| Lenovo        | G570 20079                  | [8657b8d645](https://linux-hardware.org/?probe=8657b8d645) | Mar 21, 2023 |
| ASUSTek       | S551LB                      | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| Dell          | Latitude E6420              | [e564f25125](https://linux-hardware.org/?probe=e564f25125) | Mar 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7bc035af43](https://linux-hardware.org/?probe=7bc035af43) | Mar 20, 2023 |
| Fujitsu       | LIFEBOOK E734               | [0c4119f8b3](https://linux-hardware.org/?probe=0c4119f8b3) | Mar 20, 2023 |
| Samsung       | RF511/RF411/RF711           | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Dell          | Latitude 7480               | [00d8228ec6](https://linux-hardware.org/?probe=00d8228ec6) | Mar 20, 2023 |
| TUXEDO        | N13xWU                      | [e9614af654](https://linux-hardware.org/?probe=e9614af654) | Mar 19, 2023 |
| Dell          | Latitude 7480               | [bbdb75bdce](https://linux-hardware.org/?probe=bbdb75bdce) | Mar 19, 2023 |
| HP            | Pavilion g7                 | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B8M... | [4cb81db618](https://linux-hardware.org/?probe=4cb81db618) | Mar 19, 2023 |
| Acer          | Aspire V5-552PG             | [d895f0f391](https://linux-hardware.org/?probe=d895f0f391) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | [229dcc2cb0](https://linux-hardware.org/?probe=229dcc2cb0) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | [5037090da8](https://linux-hardware.org/?probe=5037090da8) | Mar 19, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [eea214ee38](https://linux-hardware.org/?probe=eea214ee38) | Mar 18, 2023 |
| HP            | Laptop 14-cm0xxx            | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| HP            | ProBook 470 G3              | [3cdb0bbdf6](https://linux-hardware.org/?probe=3cdb0bbdf6) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [2020cf3584](https://linux-hardware.org/?probe=2020cf3584) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [e7ebc0ec0e](https://linux-hardware.org/?probe=e7ebc0ec0e) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [c343e79a84](https://linux-hardware.org/?probe=c343e79a84) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [5391c84cf4](https://linux-hardware.org/?probe=5391c84cf4) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [8fcb466fab](https://linux-hardware.org/?probe=8fcb466fab) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [7aa3efb2fd](https://linux-hardware.org/?probe=7aa3efb2fd) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [8319fcb9da](https://linux-hardware.org/?probe=8319fcb9da) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [6bf9694348](https://linux-hardware.org/?probe=6bf9694348) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [c3c0ef4a31](https://linux-hardware.org/?probe=c3c0ef4a31) | Mar 17, 2023 |
| HP            | 255 G3                      | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Dell          | Latitude 7480               | [ee6015f962](https://linux-hardware.org/?probe=ee6015f962) | Mar 17, 2023 |
| MSI           | GF72 8RE                    | [4610dffdcc](https://linux-hardware.org/?probe=4610dffdcc) | Mar 17, 2023 |
| HP            | Notebook                    | [e901631805](https://linux-hardware.org/?probe=e901631805) | Mar 17, 2023 |
| Dell          | Precision M6800             | [db62a370ed](https://linux-hardware.org/?probe=db62a370ed) | Mar 16, 2023 |
| HP            | EliteBook 8460p             | [e8d00684ac](https://linux-hardware.org/?probe=e8d00684ac) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [57f2de5da4](https://linux-hardware.org/?probe=57f2de5da4) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [2a316e6d03](https://linux-hardware.org/?probe=2a316e6d03) | Mar 16, 2023 |
| Dell          | Latitude 7480               | [72069037ca](https://linux-hardware.org/?probe=72069037ca) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | [3f7d27d637](https://linux-hardware.org/?probe=3f7d27d637) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | [e670ea3583](https://linux-hardware.org/?probe=e670ea3583) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [b78130eae1](https://linux-hardware.org/?probe=b78130eae1) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [8ea6223dc5](https://linux-hardware.org/?probe=8ea6223dc5) | Mar 16, 2023 |
| Acer          | AO756                       | [21ba8b2996](https://linux-hardware.org/?probe=21ba8b2996) | Mar 15, 2023 |
| Apple         | MacBook5,2                  | [c8c6ab5fce](https://linux-hardware.org/?probe=c8c6ab5fce) | Mar 15, 2023 |
| Acer          | Aspire 7720                 | [0f040d8292](https://linux-hardware.org/?probe=0f040d8292) | Mar 15, 2023 |
| HP            | Mini 210-1000               | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| Apple         | MacBook5,2                  | [634ae1ae2b](https://linux-hardware.org/?probe=634ae1ae2b) | Mar 14, 2023 |
| ASUSTek       | ZenBook UX534FAC_UX533FA... | [83351958e6](https://linux-hardware.org/?probe=83351958e6) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [a897cf713a](https://linux-hardware.org/?probe=a897cf713a) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [63cbbd1f57](https://linux-hardware.org/?probe=63cbbd1f57) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [f5cbc232d7](https://linux-hardware.org/?probe=f5cbc232d7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [aeb56fbebc](https://linux-hardware.org/?probe=aeb56fbebc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [ee034131c0](https://linux-hardware.org/?probe=ee034131c0) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [438caf3588](https://linux-hardware.org/?probe=438caf3588) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [57d173995a](https://linux-hardware.org/?probe=57d173995a) | Mar 14, 2023 |
| Acer          | Aspire 7739G                | [aeff2df11c](https://linux-hardware.org/?probe=aeff2df11c) | Mar 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [812104dae3](https://linux-hardware.org/?probe=812104dae3) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [27c3c24dfc](https://linux-hardware.org/?probe=27c3c24dfc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [714f8e1321](https://linux-hardware.org/?probe=714f8e1321) | Mar 14, 2023 |
| Acer          | Aspire 7720                 | [b80fa5f7ff](https://linux-hardware.org/?probe=b80fa5f7ff) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [500bee4bb7](https://linux-hardware.org/?probe=500bee4bb7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [189b1a8ec7](https://linux-hardware.org/?probe=189b1a8ec7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [9be2c9ee2b](https://linux-hardware.org/?probe=9be2c9ee2b) | Mar 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [054bb62a67](https://linux-hardware.org/?probe=054bb62a67) | Mar 14, 2023 |
| Lenovo        | Z710 20250                  | [3a99fb6400](https://linux-hardware.org/?probe=3a99fb6400) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [5c4b7a9754](https://linux-hardware.org/?probe=5c4b7a9754) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [481073d13f](https://linux-hardware.org/?probe=481073d13f) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [497a7bdef5](https://linux-hardware.org/?probe=497a7bdef5) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [07ceb1e102](https://linux-hardware.org/?probe=07ceb1e102) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [79fdcb1951](https://linux-hardware.org/?probe=79fdcb1951) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [73e4261a63](https://linux-hardware.org/?probe=73e4261a63) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [44784531d4](https://linux-hardware.org/?probe=44784531d4) | Mar 13, 2023 |
| Acer          | Aspire E5-511               | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [e58e88f5fd](https://linux-hardware.org/?probe=e58e88f5fd) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [267c6693a0](https://linux-hardware.org/?probe=267c6693a0) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [bdb4c28449](https://linux-hardware.org/?probe=bdb4c28449) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [d9226f0ad6](https://linux-hardware.org/?probe=d9226f0ad6) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [906f70a5e9](https://linux-hardware.org/?probe=906f70a5e9) | Mar 13, 2023 |
| Acer          | Aspire 5738                 | [bd231fbff6](https://linux-hardware.org/?probe=bd231fbff6) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| HP            | ZBook 17 G3                 | [f69ef4ff89](https://linux-hardware.org/?probe=f69ef4ff89) | Mar 12, 2023 |
| Lenovo        | ThinkPad X131e 3367AG9      | [0ff86711d1](https://linux-hardware.org/?probe=0ff86711d1) | Mar 12, 2023 |
| Dell          | Latitude 3510               | [13ed29770d](https://linux-hardware.org/?probe=13ed29770d) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| HP            | ProBook 4415s               | [8b974a2717](https://linux-hardware.org/?probe=8b974a2717) | Mar 12, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [f066472937](https://linux-hardware.org/?probe=f066472937) | Mar 11, 2023 |
| Dell          | Latitude E6430              | [080ad6aa2a](https://linux-hardware.org/?probe=080ad6aa2a) | Mar 11, 2023 |
| Acer          | Swift SF314-43              | [dc1a94966b](https://linux-hardware.org/?probe=dc1a94966b) | Mar 11, 2023 |
| Apple         | MacBook5,2                  | [ffb66872c2](https://linux-hardware.org/?probe=ffb66872c2) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [9736a383d7](https://linux-hardware.org/?probe=9736a383d7) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [f9bd57cf06](https://linux-hardware.org/?probe=f9bd57cf06) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [a71d5d0d96](https://linux-hardware.org/?probe=a71d5d0d96) | Mar 10, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [87aa621d6a](https://linux-hardware.org/?probe=87aa621d6a) | Mar 10, 2023 |
| Dell          | Latitude 7285               | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [91985ffa00](https://linux-hardware.org/?probe=91985ffa00) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [40499e56d1](https://linux-hardware.org/?probe=40499e56d1) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [3abbf961d5](https://linux-hardware.org/?probe=3abbf961d5) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [734afe2673](https://linux-hardware.org/?probe=734afe2673) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [364b9159c4](https://linux-hardware.org/?probe=364b9159c4) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7f3075e65e](https://linux-hardware.org/?probe=7f3075e65e) | Mar 08, 2023 |
| Medion        | E122X                       | [dad02f1ac7](https://linux-hardware.org/?probe=dad02f1ac7) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [07f425d57f](https://linux-hardware.org/?probe=07f425d57f) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f62ef69dcc](https://linux-hardware.org/?probe=f62ef69dcc) | Mar 08, 2023 |
| HP            | ZBook Studio G3             | [d059dad473](https://linux-hardware.org/?probe=d059dad473) | Mar 08, 2023 |
| Apple         | MacBook5,2                  | [e6cbad4861](https://linux-hardware.org/?probe=e6cbad4861) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [6fa1bc8547](https://linux-hardware.org/?probe=6fa1bc8547) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [ce9ba5580b](https://linux-hardware.org/?probe=ce9ba5580b) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [9a8f396913](https://linux-hardware.org/?probe=9a8f396913) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [07709f5f79](https://linux-hardware.org/?probe=07709f5f79) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [8bbc04cb55](https://linux-hardware.org/?probe=8bbc04cb55) | Mar 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [a3682a5cb6](https://linux-hardware.org/?probe=a3682a5cb6) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [7b1918ab47](https://linux-hardware.org/?probe=7b1918ab47) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [0d996d4041](https://linux-hardware.org/?probe=0d996d4041) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [eb4c28b498](https://linux-hardware.org/?probe=eb4c28b498) | Mar 07, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [124045e654](https://linux-hardware.org/?probe=124045e654) | Mar 07, 2023 |
| HP            | ZBook 15 G3                 | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [119a07048d](https://linux-hardware.org/?probe=119a07048d) | Mar 06, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [91db409270](https://linux-hardware.org/?probe=91db409270) | Mar 06, 2023 |
| Acer          | Aspire E1-571               | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| Apple         | MacBookPro6,2               | [308b516329](https://linux-hardware.org/?probe=308b516329) | Mar 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ca566e314e](https://linux-hardware.org/?probe=ca566e314e) | Mar 05, 2023 |
| Acer          | Aspire A315-54              | [cadbbe841e](https://linux-hardware.org/?probe=cadbbe841e) | Mar 05, 2023 |
| Dell          | G5 5500                     | [7da5494dea](https://linux-hardware.org/?probe=7da5494dea) | Mar 05, 2023 |
| HP            | G42                         | [7dee433139](https://linux-hardware.org/?probe=7dee433139) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| Dell          | Latitude E5450              | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| Intel         | powered classmate PC        | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| SANTECH       | NHx0DB,DE                   | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| HP            | Laptop 14s-dq1xxx           | [29fa7c0b23](https://linux-hardware.org/?probe=29fa7c0b23) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | [cdaf43afa8](https://linux-hardware.org/?probe=cdaf43afa8) | Mar 03, 2023 |
| Acer          | Aspire E1-522               | [f102669f1f](https://linux-hardware.org/?probe=f102669f1f) | Mar 03, 2023 |
| Unknown       | Unknown                     | [7afe06d070](https://linux-hardware.org/?probe=7afe06d070) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [54a92cd736](https://linux-hardware.org/?probe=54a92cd736) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [916405bd1c](https://linux-hardware.org/?probe=916405bd1c) | Mar 03, 2023 |
| HP            | 635                         | [108b9443ea](https://linux-hardware.org/?probe=108b9443ea) | Mar 03, 2023 |
| Dell          | Latitude E7440              | [36439d1a64](https://linux-hardware.org/?probe=36439d1a64) | Mar 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [180f5c9379](https://linux-hardware.org/?probe=180f5c9379) | Mar 03, 2023 |
| Dell          | Vostro1710                  | [c24eab7e3d](https://linux-hardware.org/?probe=c24eab7e3d) | Mar 02, 2023 |
| Acer          | Aspire 1640Z                | [915a8900d0](https://linux-hardware.org/?probe=915a8900d0) | Mar 02, 2023 |
| Dell          | Latitude E7440              | [b84f760e8e](https://linux-hardware.org/?probe=b84f760e8e) | Mar 02, 2023 |
| ASUSTek       | X556UR                      | [70c4807d21](https://linux-hardware.org/?probe=70c4807d21) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Dell          | Latitude 3510               | [0bad8d504d](https://linux-hardware.org/?probe=0bad8d504d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Dell          | XPS 15 9520                 | [2894a5929b](https://linux-hardware.org/?probe=2894a5929b) | Mar 02, 2023 |
| HUAWEI        | NBD-WXX9                    | [9036fa2ef1](https://linux-hardware.org/?probe=9036fa2ef1) | Mar 02, 2023 |
| GMKtec        | NucBox5                     | [fc11280fe6](https://linux-hardware.org/?probe=fc11280fe6) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [da2fc6826a](https://linux-hardware.org/?probe=da2fc6826a) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| HP            | ProBook 4415s               | [4e909ec0ad](https://linux-hardware.org/?probe=4e909ec0ad) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| TUXEDO        | Aura 15 Gen2                | [26a7db2ed8](https://linux-hardware.org/?probe=26a7db2ed8) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Dell          | Latitude 5400               | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| HP            | Pavilion g6                 | [41e4ef16e4](https://linux-hardware.org/?probe=41e4ef16e4) | Feb 26, 2023 |
| Panasonic     | CF-31WEUEEBE                | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430 2349GUU       | [95cc420bd5](https://linux-hardware.org/?probe=95cc420bd5) | Feb 26, 2023 |
| Medion        | BEAST X25                   | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BX... | [633fb08804](https://linux-hardware.org/?probe=633fb08804) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [3b2a19c835](https://linux-hardware.org/?probe=3b2a19c835) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| Unknown       | T3 MRD                      | [ae88920ea5](https://linux-hardware.org/?probe=ae88920ea5) | Feb 25, 2023 |
| Acer          | Nitro AN517-55              | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| HUAWEI        | WRT-WX9                     | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| Unknown       | Unknown                     | [2c5d6ab621](https://linux-hardware.org/?probe=2c5d6ab621) | Feb 25, 2023 |
| HP            | Pavilion g6                 | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Acer          | AO756                       | [ca83ee78ec](https://linux-hardware.org/?probe=ca83ee78ec) | Feb 24, 2023 |
| Lenovo        | KaiTian N70z G1d            | [cbc8e4e008](https://linux-hardware.org/?probe=cbc8e4e008) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| HP            | Presario CQ57               | [b41de6d094](https://linux-hardware.org/?probe=b41de6d094) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| Dell          | Latitude D620               | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [5da2f709bb](https://linux-hardware.org/?probe=5da2f709bb) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [bf32299a30](https://linux-hardware.org/?probe=bf32299a30) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [54279e4e30](https://linux-hardware.org/?probe=54279e4e30) | Feb 24, 2023 |
| HP            | EliteBook Folio 9480m       | [788e0929de](https://linux-hardware.org/?probe=788e0929de) | Feb 24, 2023 |
| Samsung       | N150P                       | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [885478dd47](https://linux-hardware.org/?probe=885478dd47) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [53eb80a44b](https://linux-hardware.org/?probe=53eb80a44b) | Feb 23, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| LincPlus      | P2                          | [5d4e528621](https://linux-hardware.org/?probe=5d4e528621) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| Dell          | Inspiron 5566               | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8227fec538](https://linux-hardware.org/?probe=8227fec538) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| Acer          | AO756                       | [58f52941c7](https://linux-hardware.org/?probe=58f52941c7) | Feb 22, 2023 |
| ASUSTek       | X556UQ                      | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 581       | 14.84%  |
| 5.10.0-10-amd64        | 491       | 12.54%  |
| 5.10.0-20-amd64        | 248       | 6.34%   |
| 5.10.0-21-amd64        | 236       | 6.03%   |
| 5.10.0-18-amd64        | 180       | 4.6%    |
| 5.10.0-9-amd64         | 173       | 4.42%   |
| 5.10.0-7-amd64         | 171       | 4.37%   |
| 5.10.0-16-amd64        | 168       | 4.29%   |
| 5.10.0-19-amd64        | 162       | 4.14%   |
| 5.10.0-13-amd64        | 151       | 3.86%   |
| 5.10.0-23-amd64        | 111       | 2.84%   |
| 5.10.0-11-amd64        | 103       | 2.63%   |
| 5.10.0-14-amd64        | 79        | 2.02%   |
| 5.10.0-17-amd64        | 73        | 1.87%   |
| 5.10.0-15-amd64        | 61        | 1.56%   |
| 5.10.0-22-amd64        | 44        | 1.12%   |
| 5.10.0-2-amd64         | 43        | 1.1%    |
| 5.10.0-12-amd64        | 39        | 1%      |
| 5.10.0-26-amd64        | 35        | 0.89%   |
| 5.10.0-6-amd64         | 28        | 0.72%   |
| 5.10.0-28-amd64        | 28        | 0.72%   |
| 5.18.0-0.deb11.4-amd64 | 27        | 0.69%   |
| 5.10.0-13-686-pae      | 26        | 0.66%   |
| 6.0.0-0.deb11.6-amd64  | 23        | 0.59%   |
| 5.10.0-25-amd64        | 22        | 0.56%   |
| 6.0.0-0.deb11.2-amd64  | 19        | 0.49%   |
| 5.14.0-0.bpo.2-amd64   | 17        | 0.43%   |
| 5.10.0-27-amd64        | 16        | 0.41%   |
| 6.1.0-0.deb11.5-amd64  | 15        | 0.38%   |
| 5.16.0-0.bpo.4-amd64   | 15        | 0.38%   |
| 5.19.0-0.deb11.2-amd64 | 14        | 0.36%   |
| 5.15.0-2-amd64         | 14        | 0.36%   |
| 5.10.0-3-amd64         | 13        | 0.33%   |
| 6.0.0-6mx-amd64        | 10        | 0.26%   |
| 5.18.0-0.bpo.1-amd64   | 9         | 0.23%   |
| 5.10.0-9-686-pae       | 9         | 0.23%   |
| 5.10.0-8-686-pae       | 9         | 0.23%   |
| 5.10.0-33-amd64        | 9         | 0.23%   |
| 5.10.0-21-686-pae      | 9         | 0.23%   |
| 5.10.0-13-686          | 9         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 3180      | 87.92%  |
| 6.0.0    | 58        | 1.6%    |
| 5.18.0   | 46        | 1.27%   |
| 6.1.0    | 43        | 1.19%   |
| 5.16.0   | 38        | 1.05%   |
| 5.15.0   | 37        | 1.02%   |
| 5.19.0   | 33        | 0.91%   |
| 5.14.0   | 24        | 0.66%   |
| 5.17.0   | 14        | 0.39%   |
| 4.19.0   | 7         | 0.19%   |
| 5.10.60  | 4         | 0.11%   |
| 6.3.5    | 3         | 0.08%   |
| 6.1.15   | 3         | 0.08%   |
| 5.15.107 | 3         | 0.08%   |
| 5.13.19  | 3         | 0.08%   |
| 5.12.0   | 3         | 0.08%   |
| 6.7.0    | 2         | 0.06%   |
| 6.2.8    | 2         | 0.06%   |
| 6.0.2    | 2         | 0.06%   |
| 5.17.5   | 2         | 0.06%   |
| 5.17.11  | 2         | 0.06%   |
| 5.15.90  | 2         | 0.06%   |
| 5.15.35  | 2         | 0.06%   |
| 5.15.11  | 2         | 0.06%   |
| 5.13.8   | 2         | 0.06%   |
| 5.11.0   | 2         | 0.06%   |
| 5.10.92  | 2         | 0.06%   |
| 5.10.109 | 2         | 0.06%   |
| 4.9.0    | 2         | 0.06%   |
| 6.7.4    | 1         | 0.03%   |
| 6.7      | 1         | 0.03%   |
| 6.5.13   | 1         | 0.03%   |
| 6.5.11   | 1         | 0.03%   |
| 6.5.0    | 1         | 0.03%   |
| 6.4.3    | 1         | 0.03%   |
| 6.4.2    | 1         | 0.03%   |
| 6.4.13   | 1         | 0.03%   |
| 6.4.12   | 1         | 0.03%   |
| 6.4.11   | 1         | 0.03%   |
| 6.3.4    | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 3199      | 88.57%  |
| 5.15    | 65        | 1.8%    |
| 6.0     | 63        | 1.74%   |
| 6.1     | 48        | 1.33%   |
| 5.18    | 48        | 1.33%   |
| 5.16    | 40        | 1.11%   |
| 5.19    | 37        | 1.02%   |
| 5.14    | 29        | 0.8%    |
| 5.17    | 20        | 0.55%   |
| 5.13    | 10        | 0.28%   |
| 4.19    | 9         | 0.25%   |
| 6.2     | 6         | 0.17%   |
| 5.12    | 6         | 0.17%   |
| 5.11    | 6         | 0.17%   |
| 6.4     | 5         | 0.14%   |
| 6.3     | 4         | 0.11%   |
| 6.7     | 3         | 0.08%   |
| 6.5     | 3         | 0.08%   |
| 5.4     | 2         | 0.06%   |
| 5.1     | 2         | 0.06%   |
| 4.9     | 2         | 0.06%   |
| 6       | 1         | 0.03%   |
| 5.15.6  | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |
| 3.8     | 1         | 0.03%   |
| 3.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3386      | 95.65%  |
| i686    | 150       | 4.24%   |
| armv7l  | 3         | 0.08%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 1047      | 29.06%  |
| GNOME             | 923       | 25.62%  |
| XFCE              | 465       | 12.91%  |
| KDE5              | 451       | 12.52%  |
| MATE              | 144       | 4%      |
| LXDE              | 117       | 3.25%   |
| X-Cinnamon        | 114       | 3.16%   |
| Cinnamon          | 99        | 2.75%   |
| LXQt              | 52        | 1.44%   |
| i3                | 44        | 1.22%   |
| KDE               | 37        | 1.03%   |
| GNOME Flashback   | 28        | 0.78%   |
| Openbox           | 16        | 0.44%   |
| lightdm-xsession  | 15        | 0.42%   |
| GNOME Classic     | 9         | 0.25%   |
| trinity           | 8         | 0.22%   |
| Budgie            | 5         | 0.14%   |
| Dwm               | 3         | 0.08%   |
| Cutefish          | 3         | 0.08%   |
| BunsenLabs        | 3         | 0.08%   |
| x-session-manager | 2         | 0.06%   |
| sway              | 2         | 0.06%   |
| ICEWM             | 2         | 0.06%   |
| Enlightenment     | 2         | 0.06%   |
| awesome           | 2         | 0.06%   |
| xmonad            | 1         | 0.03%   |
| wmaker-common     | 1         | 0.03%   |
| TOS:GNOME         | 1         | 0.03%   |
| mwm               | 1         | 0.03%   |
| matchbox          | 1         | 0.03%   |
| jwm               | 1         | 0.03%   |
| GNUstep           | 1         | 0.03%   |
| fluxbox           | 1         | 0.03%   |
| default           | 1         | 0.03%   |
| Deepin            | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 1829      | 50.89%  |
| Unknown     | 955       | 26.57%  |
| Wayland     | 672       | 18.7%   |
| Tty         | 133       | 3.7%    |
| Unspecified | 4         | 0.11%   |
| Web         | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1453      | 40.46%  |
| GDM     | 793       | 22.08%  |
| LightDM | 770       | 21.44%  |
| SDDM    | 404       | 11.25%  |
| GDM3    | 76        | 2.12%   |
| TDM     | 70        | 1.95%   |
| XDM     | 9         | 0.25%   |
| LXDM    | 7         | 0.19%   |
| SLiM    | 4         | 0.11%   |
| Ly      | 2         | 0.06%   |
| SU      | 1         | 0.03%   |
| NODM    | 1         | 0.03%   |
| KDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1084      | 30.33%  |
| Unknown | 759       | 21.24%  |
| ru_RU   | 266       | 7.44%   |
| de_DE   | 224       | 6.27%   |
| fr_FR   | 191       | 5.34%   |
| en_GB   | 156       | 4.36%   |
| es_ES   | 110       | 3.08%   |
| pt_BR   | 99        | 2.77%   |
| it_IT   | 96        | 2.69%   |
| pl_PL   | 80        | 2.24%   |
| en_CA   | 38        | 1.06%   |
| es_MX   | 35        | 0.98%   |
| es_AR   | 33        | 0.92%   |
| en_AU   | 32        | 0.9%    |
| zh_CN   | 25        | 0.7%    |
| en_IN   | 22        | 0.62%   |
| C       | 20        | 0.56%   |
| hu_HU   | 16        | 0.45%   |
| en_IE   | 14        | 0.39%   |
| fi_FI   | 13        | 0.36%   |
| es_VE   | 13        | 0.36%   |
| es_CL   | 12        | 0.34%   |
| de_CH   | 12        | 0.34%   |
| de_AT   | 12        | 0.34%   |
| sv_SE   | 11        | 0.31%   |
| es_CO   | 11        | 0.31%   |
| nl_NL   | 10        | 0.28%   |
| ja_JP   | 10        | 0.28%   |
| pt_PT   | 9         | 0.25%   |
| tr_TR   | 8         | 0.22%   |
| nb_NO   | 8         | 0.22%   |
| fr_BE   | 8         | 0.22%   |
| cs_CZ   | 8         | 0.22%   |
| zh_TW   | 7         | 0.2%    |
| ko_KR   | 7         | 0.2%    |
| en_SG   | 7         | 0.2%    |
| ca_ES   | 6         | 0.17%   |
| sk_SK   | 5         | 0.14%   |
| en_ZA   | 5         | 0.14%   |
| en_NZ   | 5         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2371      | 66.45%  |
| BIOS | 1197      | 33.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2316      | 65.18%  |
| Overlay | 1070      | 30.12%  |
| Btrfs   | 94        | 2.65%   |
| Xfs     | 29        | 0.82%   |
| Tmpfs   | 16        | 0.45%   |
| Zfs     | 15        | 0.42%   |
| Ext2    | 5         | 0.14%   |
| Ext3    | 3         | 0.08%   |
| Unknown | 3         | 0.08%   |
| Rootfs  | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2394      | 66.98%  |
| MBR     | 696       | 19.47%  |
| Unknown | 484       | 13.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2865      | 80.16%  |
| Yes       | 709       | 19.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2653      | 74.31%  |
| Yes       | 917       | 25.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 720       | 20.34%  |
| Apple                          | 634       | 17.91%  |
| Hewlett-Packard                | 530       | 14.98%  |
| Dell                           | 440       | 12.43%  |
| ASUSTek Computer               | 292       | 8.25%   |
| Acer                           | 233       | 6.58%   |
| Google                         | 135       | 3.81%   |
| Toshiba                        | 57        | 1.61%   |
| MSI                            | 57        | 1.61%   |
| Aquarius                       | 44        | 1.24%   |
| Samsung Electronics            | 41        | 1.16%   |
| Unknown                        | 30        | 0.85%   |
| HUAWEI                         | 27        | 0.76%   |
| Fujitsu                        | 23        | 0.65%   |
| Sony                           | 21        | 0.59%   |
| Notebook                       | 19        | 0.54%   |
| Packard Bell                   | 16        | 0.45%   |
| Clevo                          | 11        | 0.31%   |
| Panasonic                      | 10        | 0.28%   |
| TUXEDO                         | 8         | 0.23%   |
| Positivo                       | 8         | 0.23%   |
| Medion                         | 8         | 0.23%   |
| Intel                          | 7         | 0.2%    |
| Timi                           | 6         | 0.17%   |
| SLIMBOOK                       | 6         | 0.17%   |
| IBM                            | 6         | 0.17%   |
| GPU Company                    | 6         | 0.17%   |
| LG Electronics                 | 5         | 0.14%   |
| Gigabyte Technology            | 5         | 0.14%   |
| Pegatron                       | 4         | 0.11%   |
| HONOR                          | 4         | 0.11%   |
| Fujitsu Siemens                | 4         | 0.11%   |
| AMI                            | 4         | 0.11%   |
| Alienware                      | 4         | 0.11%   |
| System76                       | 3         | 0.08%   |
| SmbiosType1_SystemManufacturer | 3         | 0.08%   |
| Positivo Bahia - VAIO          | 3         | 0.08%   |
| PC Specialist                  | 3         | 0.08%   |
| Juana Manso                    | 3         | 0.08%   |
| Insyde                         | 3         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 353       | 9.97%   |
| Apple MacBookAir7,2                   | 77        | 2.18%   |
| Apple MacBookAir7,1                   | 77        | 2.18%   |
| Google Enguarde                       | 74        | 2.09%   |
| Apple MacBook2,1                      | 55        | 1.55%   |
| Aquarius NS585                        | 44        | 1.24%   |
| Unknown                               | 37        | 1.05%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.68%   |
| Google Terra                          | 23        | 0.65%   |
| Apple MacBook4,1                      | 21        | 0.59%   |
| HP Notebook                           | 19        | 0.54%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.45%   |
| Acer Aspire A315-23                   | 15        | 0.42%   |
| ASUS 1005HA                           | 14        | 0.4%    |
| HP Pavilion g6                        | 13        | 0.37%   |
| Google Reks                           | 13        | 0.37%   |
| HP Laptop 15-db0xxx                   | 10        | 0.28%   |
| HP EliteBook 8460p                    | 9         | 0.25%   |
| Dell Latitude E7440                   | 9         | 0.25%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 8         | 0.23%   |
| HP EliteBook 840 G3                   | 8         | 0.23%   |
| HP 255 G8 Notebook PC                 | 8         | 0.23%   |
| HP 250 G7 Notebook PC                 | 8         | 0.23%   |
| Dell Latitude 7480                    | 8         | 0.23%   |
| Samsung 300E4C/300E5C/300E7C          | 7         | 0.2%    |
| HP Laptop 15-db1xxx                   | 7         | 0.2%    |
| HP Laptop 15-bw0xx                    | 7         | 0.2%    |
| HP EliteBook 840 G8 Notebook PC       | 7         | 0.2%    |
| Dell Latitude E6330                   | 7         | 0.2%    |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 6         | 0.17%   |
| Dell XPS 13 9310                      | 6         | 0.17%   |
| Dell Latitude E6520                   | 6         | 0.17%   |
| Dell Latitude E6420                   | 6         | 0.17%   |
| Dell Latitude E5430 non-vPro          | 6         | 0.17%   |
| Dell Latitude D630                    | 6         | 0.17%   |
| Dell Latitude 5420                    | 6         | 0.17%   |
| Dell Inspiron 5100                    | 6         | 0.17%   |
| Apple MacBookPro5,5                   | 6         | 0.17%   |
| Apple MacBook7,1                      | 6         | 0.17%   |
| Acer Aspire A515-56                   | 6         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 476       | 13.45%  |
| Apple MacBook5        | 353       | 9.97%   |
| Dell Latitude         | 187       | 5.28%   |
| Acer Aspire           | 155       | 4.38%   |
| Apple MacBookAir7     | 154       | 4.35%   |
| Dell Inspiron         | 124       | 3.5%    |
| Lenovo IdeaPad        | 120       | 3.39%   |
| HP EliteBook          | 106       | 3%      |
| HP Pavilion           | 80        | 2.26%   |
| HP Laptop             | 76        | 2.15%   |
| Google Enguarde       | 74        | 2.09%   |
| HP ProBook            | 63        | 1.78%   |
| Apple MacBook2        | 55        | 1.55%   |
| Toshiba Satellite     | 45        | 1.27%   |
| ASUS VivoBook         | 44        | 1.24%   |
| Aquarius NS585        | 44        | 1.24%   |
| Dell XPS              | 42        | 1.19%   |
| Dell Precision        | 38        | 1.07%   |
| Unknown               | 37        | 1.05%   |
| HP Compaq             | 36        | 1.02%   |
| Dell Vostro           | 30        | 0.85%   |
| HP ZBook              | 25        | 0.71%   |
| ASUS ASUS             | 25        | 0.71%   |
| HP 250                | 24        | 0.68%   |
| Google Terra          | 23        | 0.65%   |
| ASUS ZenBook          | 22        | 0.62%   |
| Acer TravelMate       | 22        | 0.62%   |
| Fujitsu LIFEBOOK      | 21        | 0.59%   |
| Apple MacBook4        | 21        | 0.59%   |
| HP Notebook           | 19        | 0.54%   |
| Lenovo Legion         | 17        | 0.48%   |
| Acer Nitro            | 17        | 0.48%   |
| Lenovo ThinkBook      | 16        | 0.45%   |
| HP ENVY               | 15        | 0.42%   |
| HP 255                | 15        | 0.42%   |
| Acer Swift            | 15        | 0.42%   |
| ASUS ROG              | 14        | 0.4%    |
| ASUS 1005HA           | 14        | 0.4%    |
| Packard Bell EasyNote | 13        | 0.37%   |
| Google Reks           | 13        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 440       | 12.43%  |
| 2021    | 349       | 9.86%   |
| 2020    | 325       | 9.18%   |
| 2019    | 322       | 9.1%    |
| 2012    | 218       | 6.16%   |
| 2015    | 204       | 5.76%   |
| 2018    | 195       | 5.51%   |
| 2017    | 188       | 5.31%   |
| 2011    | 188       | 5.31%   |
| 2007    | 186       | 5.26%   |
| 2013    | 172       | 4.86%   |
| 2014    | 156       | 4.41%   |
| 2022    | 148       | 4.18%   |
| 2016    | 137       | 3.87%   |
| 2008    | 119       | 3.36%   |
| 2010    | 113       | 3.19%   |
| 2006    | 30        | 0.85%   |
| 2005    | 19        | 0.54%   |
| 2023    | 11        | 0.31%   |
| 2003    | 9         | 0.25%   |
| 2004    | 6         | 0.17%   |
| Unknown | 3         | 0.08%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3539      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3263      | 91.84%  |
| Enabled  | 290       | 8.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3398      | 95.99%  |
| Yes  | 142       | 4.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 968       | 27.18%  |
| 3.01-4.0    | 722       | 20.27%  |
| 16.01-24.0  | 529       | 14.85%  |
| 1.01-2.0    | 496       | 13.92%  |
| 8.01-16.0   | 438       | 12.3%   |
| 32.01-64.0  | 185       | 5.19%   |
| 2.01-3.0    | 81        | 2.27%   |
| 0.51-1.0    | 59        | 1.66%   |
| 64.01-256.0 | 37        | 1.04%   |
| 24.01-32.0  | 35        | 0.98%   |
| 0.01-0.5    | 11        | 0.31%   |
| Unknown     | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1620      | 43.34%  |
| 2.01-3.0   | 726       | 19.42%  |
| 0.51-1.0   | 408       | 10.91%  |
| 4.01-8.0   | 402       | 10.75%  |
| 3.01-4.0   | 346       | 9.26%   |
| 8.01-16.0  | 116       | 3.1%    |
| 0.01-0.5   | 102       | 2.73%   |
| 16.01-24.0 | 11        | 0.29%   |
| 24.01-32.0 | 3         | 0.08%   |
| 32.01-64.0 | 2         | 0.05%   |
| Unknown    | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2881      | 80.34%  |
| 2      | 593       | 16.54%  |
| 3      | 67        | 1.87%   |
| 0      | 26        | 0.73%   |
| 4      | 14        | 0.39%   |
| 5      | 3         | 0.08%   |
| 7      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2257      | 63.63%  |
| Yes       | 1290      | 36.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2874      | 81.05%  |
| No        | 672       | 18.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3469      | 97.97%  |
| No        | 72        | 2.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2879      | 80.94%  |
| No        | 678       | 19.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1117      | 31.46%  |
| Germany     | 313       | 8.82%   |
| Russia      | 292       | 8.23%   |
| France      | 233       | 6.56%   |
| Spain       | 146       | 4.11%   |
| Brazil      | 131       | 3.69%   |
| Italy       | 122       | 3.44%   |
| Poland      | 103       | 2.9%    |
| UK          | 79        | 2.23%   |
| Netherlands | 57        | 1.61%   |
| Canada      | 57        | 1.61%   |
| Mexico      | 48        | 1.35%   |
| Argentina   | 45        | 1.27%   |
| Switzerland | 39        | 1.1%    |
| Australia   | 38        | 1.07%   |
| China       | 37        | 1.04%   |
| India       | 34        | 0.96%   |
| Sweden      | 32        | 0.9%    |
| Turkey      | 28        | 0.79%   |
| Hungary     | 27        | 0.76%   |
| Ukraine     | 26        | 0.73%   |
| Belgium     | 26        | 0.73%   |
| Finland     | 25        | 0.7%    |
| Austria     | 24        | 0.68%   |
| Norway      | 22        | 0.62%   |
| Portugal    | 21        | 0.59%   |
| Czechia     | 20        | 0.56%   |
| Romania     | 19        | 0.54%   |
| Greece      | 19        | 0.54%   |
| Colombia    | 17        | 0.48%   |
| Venezuela   | 16        | 0.45%   |
| Japan       | 15        | 0.42%   |
| Ireland     | 15        | 0.42%   |
| Chile       | 14        | 0.39%   |
| Bulgaria    | 14        | 0.39%   |
| Indonesia   | 13        | 0.37%   |
| Croatia     | 12        | 0.34%   |
| Thailand    | 11        | 0.31%   |
| Taiwan      | 11        | 0.31%   |
| Denmark     | 10        | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 621       | 16.68%  |
| Dover-Foxcroft    | 229       | 6.15%   |
| Voronezh          | 144       | 3.87%   |
| Paris             | 39        | 1.05%   |
| Seville           | 36        | 0.97%   |
| Moscow            | 31        | 0.83%   |
| Berlin            | 31        | 0.83%   |
| St Petersburg     | 30        | 0.81%   |
| Madrid            | 27        | 0.73%   |
| Warsaw            | 25        | 0.67%   |
| Munich            | 21        | 0.56%   |
| Barcelona         | 19        | 0.51%   |
| Milan             | 17        | 0.46%   |
| Amsterdam         | 17        | 0.46%   |
| Vienna            | 16        | 0.43%   |
| Sao Paulo         | 15        | 0.4%    |
| Hamburg           | 14        | 0.38%   |
| London            | 13        | 0.35%   |
| Istanbul          | 12        | 0.32%   |
| Frankfurt am Main | 12        | 0.32%   |
| Rome              | 11        | 0.3%    |
| Prague            | 11        | 0.3%    |
| Dublin            | 11        | 0.3%    |
| Blizniew          | 11        | 0.3%    |
| Toronto           | 10        | 0.27%   |
| Perm              | 10        | 0.27%   |
| Helsinki          | 10        | 0.27%   |
| Athens            | 10        | 0.27%   |
| Zagreb            | 9         | 0.24%   |
| Sydney            | 9         | 0.24%   |
| Oslo              | 9         | 0.24%   |
| Mexico City       | 9         | 0.24%   |
| Lyon              | 9         | 0.24%   |
| Iasi              | 9         | 0.24%   |
| Chorzele          | 9         | 0.24%   |
| Budapest          | 9         | 0.24%   |
| Brisbane          | 9         | 0.24%   |
| Brasília         | 9         | 0.24%   |
| San Jose          | 8         | 0.21%   |
| Natal             | 8         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 567       | 695    | 13.59%  |
| WDC                       | 423       | 517    | 10.14%  |
| Seagate                   | 335       | 397    | 8.03%   |
| Toshiba                   | 331       | 355    | 7.94%   |
| Unknown                   | 283       | 351    | 6.78%   |
| Fujitsu                   | 279       | 285    | 6.69%   |
| Kingston                  | 219       | 270    | 5.25%   |
| SanDisk                   | 191       | 228    | 4.58%   |
| Apple                     | 177       | 211    | 4.24%   |
| Crucial                   | 160       | 185    | 3.84%   |
| SK hynix                  | 150       | 167    | 3.6%    |
| Hitachi                   | 118       | 135    | 2.83%   |
| A-DATA Technology         | 101       | 188    | 2.42%   |
| Intel                     | 98        | 122    | 2.35%   |
| Micron Technology         | 92        | 97     | 2.21%   |
| HGST                      | 73        | 89     | 1.75%   |
| KIOXIA                    | 53        | 58     | 1.27%   |
| China                     | 34        | 35     | 0.82%   |
| Unknown                   | 31        | 35     | 0.74%   |
| LITEON                    | 26        | 30     | 0.62%   |
| Transcend                 | 19        | 25     | 0.46%   |
| PNY                       | 18        | 24     | 0.43%   |
| SABRENT                   | 17        | 18     | 0.41%   |
| Phison                    | 17        | 21     | 0.41%   |
| SPCC                      | 16        | 17     | 0.38%   |
| Intenso                   | 16        | 20     | 0.38%   |
| Silicon Motion            | 15        | 18     | 0.36%   |
| LITEONIT                  | 15        | 18     | 0.36%   |
| Team                      | 12        | 12     | 0.29%   |
| Patriot                   | 12        | 12     | 0.29%   |
| JMicron Technology        | 12        | 12     | 0.29%   |
| GOODRAM                   | 12        | 13     | 0.29%   |
| SSSTC                     | 9         | 9      | 0.22%   |
| Lenovo                    | 9         | 11     | 0.22%   |
| Apacer                    | 9         | 9      | 0.22%   |
| Netac                     | 8         | 9      | 0.19%   |
| UMIS                      | 7         | 12     | 0.17%   |
| Micron/Crucial Technology | 7         | 7      | 0.17%   |
| Corsair                   | 7         | 7      | 0.17%   |
| ASMT                      | 7         | 11     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 237       | 5.57%   |
| Apple SSD AP0128H 121GB            | 77        | 1.81%   |
| Apple SSD SM0128G 121GB            | 71        | 1.67%   |
| Toshiba MK1655GSXF 160GB           | 52        | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB     | 45        | 1.06%   |
| A-DATA SU800 512GB SSD             | 44        | 1.03%   |
| Toshiba MK1653GSX 160GB            | 43        | 1.01%   |
| Kingston SA400S37240G 240GB SSD    | 42        | 0.99%   |
| Unknown AGND3R  16GB               | 39        | 0.92%   |
| Kingston SA400S37120G 120GB SSD    | 39        | 0.92%   |
| Toshiba MQ04ABF100 1TB             | 31        | 0.73%   |
| Unknown                            | 31        | 0.73%   |
| Unknown HAG2e  16GB                | 30        | 0.7%    |
| Toshiba MQ01ABF050 500GB           | 29        | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 29        | 0.68%   |
| Unknown SDW16G  16GB               | 25        | 0.59%   |
| Crucial CT500MX500SSD1 500GB       | 25        | 0.59%   |
| Crucial CT1000MX500SSD1 1TB        | 25        | 0.59%   |
| Toshiba MQ01ABD100 1TB             | 24        | 0.56%   |
| HGST HTS721010A9E630 1TB           | 24        | 0.56%   |
| Unknown MMC Card  32GB             | 23        | 0.54%   |
| Samsung SSD 860 EVO 500GB          | 23        | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB       | 21        | 0.49%   |
| Seagate ST500LT012-1DG142 500GB    | 19        | 0.45%   |
| Samsung SSD 850 EVO 500GB          | 19        | 0.45%   |
| SABRENT Disk 2TB                   | 17        | 0.4%    |
| Kingston SV300S37A120G 120GB SSD   | 17        | 0.4%    |
| WDC WD1600BUDT-63DPZY0 160GB       | 16        | 0.38%   |
| Samsung SSD 850 EVO 250GB          | 16        | 0.38%   |
| Kingston SA400S37480G 480GB SSD    | 16        | 0.38%   |
| HGST HTS541010A9E680 1TB           | 15        | 0.35%   |
| SanDisk SD8SBAT128G1122 128GB SSD  | 14        | 0.33%   |
| Samsung SSD 870 EVO 500GB          | 14        | 0.33%   |
| HGST HTS725050A7E630 500GB         | 14        | 0.33%   |
| Seagate ST9500325AS 500GB          | 13        | 0.31%   |
| Samsung SSD 860 EVO 250GB          | 13        | 0.31%   |
| Samsung SSD 980 1TB                | 12        | 0.28%   |
| Intel SSDPEKNW512G8 512GB          | 12        | 0.28%   |
| Hitachi HTS543216L9SA02 160GB      | 12        | 0.28%   |
| Crucial CT240BX500SSD1 240GB       | 12        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 322       | 382    | 23.44%  |
| Fujitsu             | 279       | 285    | 20.31%  |
| Toshiba             | 270       | 288    | 19.65%  |
| WDC                 | 237       | 274    | 17.25%  |
| Hitachi             | 118       | 135    | 8.59%   |
| HGST                | 73        | 89     | 5.31%   |
| SABRENT             | 17        | 18     | 1.24%   |
| Samsung Electronics | 16        | 17     | 1.16%   |
| Unknown             | 12        | 15     | 0.87%   |
| JMicron Technology  | 9         | 9      | 0.66%   |
| ASMT                | 7         | 11     | 0.51%   |
| TO Exter            | 2         | 2      | 0.15%   |
| Intenso             | 2         | 2      | 0.15%   |
| Unknown             | 2         | 2      | 0.15%   |
| Unknown (CF)        | 1         | 1      | 0.07%   |
| Space ke            | 1         | 1      | 0.07%   |
| SILICONMOTION       | 1         | 1      | 0.07%   |
| Maxone              | 1         | 1      | 0.07%   |
| LaCie               | 1         | 1      | 0.07%   |
| IBM/Hitachi         | 1         | 1      | 0.07%   |
| External            | 1         | 1      | 0.07%   |
| Apple               | 1         | 2      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 256       | 306    | 19.51%  |
| Kingston            | 173       | 221    | 13.19%  |
| Crucial             | 137       | 159    | 10.44%  |
| SanDisk             | 128       | 157    | 9.76%   |
| Apple               | 93        | 103    | 7.09%   |
| A-DATA Technology   | 74        | 148    | 5.64%   |
| WDC                 | 45        | 62     | 3.43%   |
| China               | 34        | 35     | 2.59%   |
| Micron Technology   | 31        | 34     | 2.36%   |
| Intel               | 27        | 29     | 2.06%   |
| SK hynix            | 26        | 31     | 1.98%   |
| LITEON              | 21        | 23     | 1.6%    |
| Transcend           | 17        | 23     | 1.3%    |
| Toshiba             | 17        | 18     | 1.3%    |
| PNY                 | 16        | 22     | 1.22%   |
| LITEONIT            | 15        | 18     | 1.14%   |
| Intenso             | 13        | 17     | 0.99%   |
| SPCC                | 12        | 13     | 0.91%   |
| Patriot             | 12        | 12     | 0.91%   |
| Team                | 11        | 11     | 0.84%   |
| Netac               | 8         | 9      | 0.61%   |
| GOODRAM             | 8         | 9      | 0.61%   |
| Apacer              | 8         | 8      | 0.61%   |
| Unknown             | 7         | 7      | 0.53%   |
| Lexar               | 6         | 7      | 0.46%   |
| Seagate             | 5         | 5      | 0.38%   |
| Plextor             | 4         | 4      | 0.3%    |
| KIOXIA-EXCERIA      | 4         | 5      | 0.3%    |
| KingDian            | 4         | 4      | 0.3%    |
| Dogfish             | 4         | 6      | 0.3%    |
| Corsair             | 4         | 4      | 0.3%    |
| ZTC                 | 3         | 4      | 0.23%   |
| Teclast             | 3         | 4      | 0.23%   |
| OCZ                 | 3         | 3      | 0.23%   |
| Lenovo              | 3         | 4      | 0.23%   |
| Hewlett-Packard     | 3         | 5      | 0.23%   |
| FORESEE             | 3         | 3      | 0.23%   |
| Fanxiang            | 3         | 3      | 0.23%   |
| Emtec               | 3         | 3      | 0.23%   |
| ASUS-PHISON         | 3         | 4      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1330      | 1538   | 33.18%  |
| SSD     | 1240      | 1618   | 30.93%  |
| NVMe    | 1100      | 1376   | 27.44%  |
| MMC     | 304       | 373    | 7.58%   |
| Unknown | 35        | 39     | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2338      | 3024   | 60.35%  |
| NVMe | 1099      | 1372   | 28.37%  |
| MMC  | 304       | 373    | 7.85%   |
| SAS  | 133       | 175    | 3.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1879      | 2284   | 73.89%  |
| 0.51-1.0   | 568       | 756    | 22.34%  |
| 1.01-2.0   | 74        | 90     | 2.91%   |
| 4.01-10.0  | 12        | 15     | 0.47%   |
| 3.01-4.0   | 8         | 9      | 0.31%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |
| 0          | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1013      | 27.8%   |
| Unknown        | 747       | 20.5%   |
| 251-500        | 675       | 18.52%  |
| 501-1000       | 409       | 11.22%  |
| 1-20           | 216       | 5.93%   |
| 51-100         | 213       | 5.85%   |
| 1001-2000      | 163       | 4.47%   |
| 21-50          | 129       | 3.54%   |
| 2001-3000      | 42        | 1.15%   |
| More than 3000 | 37        | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1398      | 37.46%  |
| Unknown        | 747       | 20.02%  |
| 21-50          | 426       | 11.41%  |
| 101-250        | 377       | 10.1%   |
| 51-100         | 344       | 9.22%   |
| 251-500        | 228       | 6.11%   |
| 501-1000       | 130       | 3.48%   |
| 1001-2000      | 49        | 1.31%   |
| More than 3000 | 13        | 0.35%   |
| 2001-3000      | 10        | 0.27%   |
| 0              | 10        | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB        | 25        | 25     | 6.67%   |
| Hitachi HTS543216L9SA02 160GB         | 11        | 11     | 2.93%   |
| Toshiba MK1653GSX 160GB               | 9         | 9      | 2.4%    |
| Seagate ST9500325AS 500GB             | 9         | 9      | 2.4%    |
| Toshiba MK1655GSXF 160GB              | 8         | 8      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 7         | 8      | 1.87%   |
| HGST HTS541010A9E680 1TB              | 7         | 7      | 1.87%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 6         | 7      | 1.6%    |
| Seagate ST9500420AS 500GB             | 6         | 7      | 1.6%    |
| Seagate ST500LM021-1KJ152 500GB       | 5         | 5      | 1.33%   |
| Hitachi HTS542512K9SA00 120GB         | 5         | 6      | 1.33%   |
| WDC WD1600BUDT-63DPZY0 160GB          | 4         | 4      | 1.07%   |
| Toshiba MQ01ABF050 500GB              | 4         | 4      | 1.07%   |
| Toshiba MQ01ABD100 1TB                | 4         | 5      | 1.07%   |
| Seagate ST9320325AS 320GB             | 4         | 4      | 1.07%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 1.07%   |
| Hitachi HTS545050B9A300 500GB         | 4         | 4      | 1.07%   |
| HGST HTS725050A7E630 500GB            | 4         | 5      | 1.07%   |
| Toshiba MQ04ABF100 1TB                | 3         | 3      | 0.8%    |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 0.8%    |
| Seagate ST500LM000-SSHD-8GB           | 3         | 3      | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 0.8%    |
| Kingston SV300S37A120G 120GB SSD      | 3         | 3      | 0.8%    |
| Hitachi HTS547575A9E384 752GB         | 3         | 3      | 0.8%    |
| Crucial CT275MX300SSD1 275GB          | 3         | 3      | 0.8%    |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 2      | 0.53%   |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 4      | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 0.53%   |
| WDC WD10JPVT-75A1YT0 1TB              | 2         | 2      | 0.53%   |
| Toshiba MQ01ABD050V 500GB             | 2         | 2      | 0.53%   |
| Toshiba MK2552GSX 250GB               | 2         | 2      | 0.53%   |
| SK hynix SH920 mSATA 128GB SSD        | 2         | 2      | 0.53%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 2         | 2      | 0.53%   |
| SK hynix HFS256G39MND-2300A 256GB SSD | 2         | 2      | 0.53%   |
| SK hynix BC711 HFM256GD3JX013N 256GB  | 2         | 2      | 0.53%   |
| Seagate ST980811AS 80GB               | 2         | 2      | 0.53%   |
| Seagate ST94811A 40GB                 | 2         | 2      | 0.53%   |
| Seagate ST9320423AS 320GB             | 2         | 2      | 0.53%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 0.53%   |
| Seagate ST2000LX001-1RG174 2TB        | 2         | 2      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 84     | 20.86%  |
| Hitachi             | 59        | 66     | 15.78%  |
| Toshiba             | 49        | 51     | 13.1%   |
| Fujitsu             | 34        | 36     | 9.09%   |
| WDC                 | 28        | 33     | 7.49%   |
| HGST                | 20        | 23     | 5.35%   |
| SK hynix            | 18        | 19     | 4.81%   |
| Samsung Electronics | 16        | 17     | 4.28%   |
| Kingston            | 13        | 13     | 3.48%   |
| SanDisk             | 10        | 11     | 2.67%   |
| Micron Technology   | 10        | 10     | 2.67%   |
| Intel               | 9         | 10     | 2.41%   |
| Crucial             | 6         | 6      | 1.6%    |
| LITEON              | 4         | 4      | 1.07%   |
| A-DATA Technology   | 4         | 4      | 1.07%   |
| LITEONIT            | 3         | 4      | 0.8%    |
| Unknown             | 2         | 2      | 0.53%   |
| SSSTC               | 1         | 1      | 0.27%   |
| ShiJi               | 1         | 1      | 0.27%   |
| Plextor             | 1         | 1      | 0.27%   |
| Lenovo              | 1         | 1      | 0.27%   |
| KingSpec            | 1         | 1      | 0.27%   |
| IBM/Hitachi         | 1         | 1      | 0.27%   |
| GOODRAM             | 1         | 1      | 0.27%   |
| GLOWAY              | 1         | 1      | 0.27%   |
| Dogfish             | 1         | 1      | 0.27%   |
| DGM                 | 1         | 1      | 0.27%   |
| Apple               | 1         | 2      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 84     | 28.16%  |
| Hitachi             | 59        | 66     | 21.3%   |
| Toshiba             | 49        | 51     | 17.69%  |
| Fujitsu             | 34        | 36     | 12.27%  |
| WDC                 | 28        | 33     | 10.11%  |
| HGST                | 20        | 23     | 7.22%   |
| Samsung Electronics | 7         | 7      | 2.53%   |
| IBM/Hitachi         | 1         | 1      | 0.36%   |
| Apple               | 1         | 2      | 0.36%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 276       | 303    | 73.99%  |
| SSD  | 78        | 82     | 20.91%  |
| NVMe | 19        | 20     | 5.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 11.11%  |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 11.11%  |
| Toshiba MK3276GSXN 320GB                        | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 11.11%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 11.11%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 11.11%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 11.11%  |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 2      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2539      | 3276   | 67.53%  |
| Detected | 840       | 1252   | 22.34%  |
| Malfunc  | 371       | 405    | 9.87%   |
| Failed   | 9         | 10     | 0.24%   |
| Limited  | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2019      | 51.54%  |
| Samsung Electronics              | 383       | 9.78%   |
| Nvidia                           | 374       | 9.55%   |
| AMD                              | 342       | 8.73%   |
| SanDisk                          | 195       | 4.98%   |
| SK hynix                         | 119       | 3.04%   |
| Apple                            | 83        | 2.12%   |
| Micron Technology                | 61        | 1.56%   |
| Toshiba America Info Systems     | 53        | 1.35%   |
| Kingston Technology Company      | 50        | 1.28%   |
| KIOXIA                           | 48        | 1.23%   |
| ADATA Technology                 | 31        | 0.79%   |
| Phison Electronics               | 30        | 0.77%   |
| Micron/Crucial Technology        | 28        | 0.71%   |
| Silicon Motion                   | 25        | 0.64%   |
| Solid State Storage Technology   | 17        | 0.43%   |
| Union Memory (Shenzhen)          | 10        | 0.26%   |
| Realtek Semiconductor            | 7         | 0.18%   |
| Silicon Integrated Systems [SiS] | 5         | 0.13%   |
| Shenzhen Longsys Electronics     | 5         | 0.13%   |
| Lite-On Technology               | 5         | 0.13%   |
| Lenovo                           | 5         | 0.13%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.1%    |
| ULi Electronics                  | 3         | 0.08%   |
| Marvell Technology Group         | 3         | 0.08%   |
| VIA Technologies                 | 2         | 0.05%   |
| Jiangsu Huacun Elec.             | 2         | 0.05%   |
| ASMedia Technology               | 2         | 0.05%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Transcend                        | 1         | 0.03%   |
| Silicon Image                    | 1         | 0.03%   |
| JMicron Technology               | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 AHCI Controller                                                   | 362       | 8.61%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 299       | 7.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 232       | 5.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 223       | 5.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 152       | 3.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 146       | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 130       | 3.09%   |
| Intel Volume Management Device NVMe RAID Controller                            | 121       | 2.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 95        | 2.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 95        | 2.26%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 90        | 2.14%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 80        | 1.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 79        | 1.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 78        | 1.85%   |
| Apple S1X NVMe Controller                                                      | 78        | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 72        | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 65        | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 61        | 1.45%   |
| Intel Tiger Lake-LP SATA Controller                                            | 60        | 1.43%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 59        | 1.4%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 56        | 1.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 56        | 1.33%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 53        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 51        | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 49        | 1.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 49        | 1.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 48        | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 44        | 1.05%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 40        | 0.95%   |
| Intel SSD 660P Series                                                          | 36        | 0.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 35        | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 34        | 0.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 34        | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 33        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 31        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 30        | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 29        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 27        | 0.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 26        | 0.62%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 23        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2425      | 59.2%   |
| NVMe | 1098      | 26.81%  |
| IDE  | 292       | 7.13%   |
| RAID | 281       | 6.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3034      | 85.71%  |
| AMD          | 499       | 14.1%   |
| ARM          | 4         | 0.11%   |
| CentaurHauls | 3         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 355       | 10.02%  |
| Intel Core i5-5250U CPU @ 1.60GHz             | 147       | 4.15%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 91        | 2.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 76        | 2.15%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 61        | 1.72%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 59        | 1.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 58        | 1.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 46        | 1.3%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 45        | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 44        | 1.24%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 1.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 39        | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 37        | 1.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 34        | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 32        | 0.9%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 31        | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 28        | 0.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 28        | 0.79%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 28        | 0.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 27        | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 0.73%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 26        | 0.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 24        | 0.68%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.68%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 21        | 0.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 20        | 0.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 20        | 0.56%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 19        | 0.54%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 19        | 0.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 18        | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 0.51%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 18        | 0.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.51%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 18        | 0.51%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 0.48%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 17        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 839       | 23.7%   |
| Intel Core i7           | 557       | 15.73%  |
| Intel Core 2 Duo        | 481       | 13.59%  |
| Other                   | 306       | 8.64%   |
| Intel Celeron           | 306       | 8.64%   |
| Intel Core i3           | 232       | 6.55%   |
| AMD Ryzen 5             | 150       | 4.24%   |
| Intel Atom              | 94        | 2.66%   |
| AMD Ryzen 7             | 76        | 2.15%   |
| Intel Core 2            | 67        | 1.89%   |
| Intel Pentium           | 61        | 1.72%   |
| AMD A6                  | 35        | 0.99%   |
| AMD Ryzen 7 PRO         | 31        | 0.88%   |
| Intel Pentium M         | 22        | 0.62%   |
| Intel Genuine           | 20        | 0.56%   |
| Intel Pentium Dual-Core | 19        | 0.54%   |
| AMD A4                  | 17        | 0.48%   |
| AMD Ryzen 9             | 15        | 0.42%   |
| AMD Ryzen 3             | 15        | 0.42%   |
| AMD Ryzen 5 PRO         | 13        | 0.37%   |
| AMD A8                  | 13        | 0.37%   |
| Intel Celeron M         | 12        | 0.34%   |
| Intel Pentium Dual      | 11        | 0.31%   |
| AMD A10                 | 11        | 0.31%   |
| AMD E1                  | 9         | 0.25%   |
| AMD E2                  | 8         | 0.23%   |
| AMD E                   | 8         | 0.23%   |
| Intel Pentium Silver    | 7         | 0.2%    |
| Intel Pentium 4         | 7         | 0.2%    |
| Intel Core i9           | 6         | 0.17%   |
| AMD A12                 | 6         | 0.17%   |
| Intel Xeon              | 5         | 0.14%   |
| Intel Core Duo          | 5         | 0.14%   |
| AMD PRO A10             | 5         | 0.14%   |
| AMD C-50                | 5         | 0.14%   |
| Intel Pentium Gold      | 4         | 0.11%   |
| Intel Core m7           | 4         | 0.11%   |
| Intel Core m3           | 4         | 0.11%   |
| AMD Turion 64 X2 Mobile | 4         | 0.11%   |
| AMD Turion 64 Mobile    | 4         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2039      | 57.58%  |
| 4      | 974       | 27.51%  |
| 6      | 180       | 5.08%   |
| 8      | 152       | 4.29%   |
| 1      | 148       | 4.18%   |
| 10     | 24        | 0.68%   |
| 14     | 15        | 0.42%   |
| 12     | 8         | 0.23%   |
| 16     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3538      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2205      | 62.27%  |
| 1      | 1335      | 37.7%   |
| 4      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3439      | 97.17%  |
| 32-bit         | 95        | 2.68%   |
| Unknown        | 5         | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 601       | 16.72%  |
| 0x1067a    | 418       | 11.63%  |
| 0x306d4    | 226       | 6.29%   |
| 0x306a9    | 166       | 4.62%   |
| 0x806c1    | 147       | 4.09%   |
| 0x206a7    | 146       | 4.06%   |
| 0x806ec    | 118       | 3.28%   |
| 0x30678    | 103       | 2.87%   |
| 0x806e9    | 97        | 2.7%    |
| 0x406e3    | 85        | 2.37%   |
| 0x40651    | 85        | 2.37%   |
| 0x806ea    | 82        | 2.28%   |
| 0x6f6      | 64        | 1.78%   |
| 0x406c4    | 63        | 1.75%   |
| 0x306c3    | 63        | 1.75%   |
| 0xa0652    | 56        | 1.56%   |
| 0x20655    | 51        | 1.42%   |
| 0x08108109 | 48        | 1.34%   |
| 0x906ea    | 45        | 1.25%   |
| 0x906eb    | 44        | 1.22%   |
| 0x08608103 | 43        | 1.2%    |
| 0x08600106 | 43        | 1.2%    |
| 0x0a50000c | 42        | 1.17%   |
| 0x706e5    | 36        | 1%      |
| 0x706a8    | 36        | 1%      |
| 0x10676    | 36        | 1%      |
| 0x0600611a | 33        | 0.92%   |
| 0x06006705 | 31        | 0.86%   |
| 0x106c2    | 29        | 0.81%   |
| 0x6fd      | 28        | 0.78%   |
| 0x506c9    | 26        | 0.72%   |
| 0x806eb    | 25        | 0.7%    |
| 0x506e3    | 25        | 0.7%    |
| 0x106ca    | 24        | 0.67%   |
| 0x08108102 | 23        | 0.64%   |
| 0x906e9    | 21        | 0.58%   |
| 0x906a4    | 20        | 0.56%   |
| 0x906a3    | 20        | 0.56%   |
| 0x806d1    | 20        | 0.56%   |
| 0x6d8      | 20        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 554       | 15.63%  |
| Penryn           | 470       | 13.26%  |
| Broadwell        | 246       | 6.94%   |
| IvyBridge        | 216       | 6.09%   |
| Silvermont       | 202       | 5.7%    |
| Haswell          | 194       | 5.47%   |
| SandyBridge      | 190       | 5.36%   |
| TigerLake        | 188       | 5.3%    |
| Skylake          | 143       | 4.03%   |
| Core             | 123       | 3.47%   |
| Unknown          | 106       | 2.99%   |
| Zen+             | 93        | 2.62%   |
| Westmere         | 87        | 2.45%   |
| Excavator        | 82        | 2.31%   |
| Zen 2            | 77        | 2.17%   |
| CometLake        | 71        | 2%      |
| Bonnell          | 62        | 1.75%   |
| Zen 3            | 61        | 1.72%   |
| Icelake          | 60        | 1.69%   |
| Goldmont plus    | 59        | 1.66%   |
| P6               | 54        | 1.52%   |
| Goldmont         | 31        | 0.87%   |
| Bobcat           | 25        | 0.71%   |
| Alderlake Hybrid | 22        | 0.62%   |
| Puma             | 21        | 0.59%   |
| Zen              | 18        | 0.51%   |
| Jaguar           | 14        | 0.4%    |
| Tremont          | 13        | 0.37%   |
| Piledriver       | 10        | 0.28%   |
| NetBurst         | 10        | 0.28%   |
| K8 Hammer        | 10        | 0.28%   |
| K10 Llano        | 10        | 0.28%   |
| K10              | 9         | 0.25%   |
| K8 & K10 hybrid  | 7         | 0.2%    |
| Nehalem          | 4         | 0.11%   |
| Steamroller      | 2         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2509      | 59.87%  |
| Nvidia                           | 1021      | 24.36%  |
| AMD                              | 652       | 15.56%  |
| Silicon Integrated Systems [SiS] | 4         | 0.1%    |
| Zhaoxin                          | 3         | 0.07%   |
| VIA Technologies                 | 1         | 0.02%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 353       | 8.01%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 198       | 4.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 172       | 3.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 166       | 3.77%   |
| Intel HD Graphics 6000                                                                   | 154       | 3.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 120       | 2.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 113       | 2.56%   |
| Intel UHD Graphics 620                                                                   | 107       | 2.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 105       | 2.38%   |
| Intel HD Graphics 620                                                                    | 100       | 2.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 98        | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 95        | 2.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 88        | 2%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 85        | 1.93%   |
| Intel HD Graphics 5500                                                                   | 83        | 1.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 82        | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 81        | 1.84%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 77        | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 74        | 1.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 69        | 1.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 61        | 1.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 58        | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 58        | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 57        | 1.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 56        | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 54        | 1.23%   |
| AMD Lucienne                                                                             | 54        | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 53        | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 48        | 1.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 1%      |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 44        | 1%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 38        | 0.86%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 31        | 0.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 29        | 0.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 28        | 0.64%   |
| Intel HD Graphics 630                                                                    | 28        | 0.64%   |
| Intel HD Graphics 530                                                                    | 27        | 0.61%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 25        | 0.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 24        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1908      | 53.85%  |
| Intel + Nvidia  | 503       | 14.2%   |
| 1 x AMD         | 463       | 13.07%  |
| 1 x Nvidia      | 455       | 12.84%  |
| Intel + AMD     | 88        | 2.48%   |
| AMD + Nvidia    | 63        | 1.78%   |
| 2 x AMD         | 38        | 1.07%   |
| Other           | 14        | 0.4%    |
| 1 x SiS         | 4         | 0.11%   |
| 1 x Zhaoxin     | 3         | 0.08%   |
| 2 x Nvidia      | 1         | 0.03%   |
| 2 x Intel       | 1         | 0.03%   |
| 1 x VIA         | 1         | 0.03%   |
| 1 x S3 Graphics | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3079      | 86.39%  |
| Unknown     | 282       | 7.91%   |
| Proprietary | 203       | 5.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 2549      | 71.36%  |
| 0.01-0.5       | 626       | 17.53%  |
| 1.01-2.0       | 157       | 4.4%    |
| 3.01-4.0       | 99        | 2.77%   |
| 0.51-1.0       | 97        | 2.72%   |
| 5.01-6.0       | 23        | 0.64%   |
| 7.01-8.0       | 12        | 0.34%   |
| 2.01-3.0       | 6         | 0.17%   |
| 8.01-16.0      | 2         | 0.06%   |
| More than 64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 632       | 17.06%  |
| AU Optronics            | 598       | 16.14%  |
| BOE                     | 483       | 13.04%  |
| LG Display              | 420       | 11.34%  |
| Chimei Innolux          | 405       | 10.93%  |
| Samsung Electronics     | 269       | 7.26%   |
| Lenovo                  | 89        | 2.4%    |
| Dell                    | 74        | 2%      |
| Sharp                   | 68        | 1.84%   |
| Chi Mei Optoelectronics | 64        | 1.73%   |
| InfoVision              | 55        | 1.48%   |
| Goldstar                | 55        | 1.48%   |
| BenQ                    | 39        | 1.05%   |
| PANDA                   | 37        | 1%      |
| Hewlett-Packard         | 37        | 1%      |
| Philips                 | 32        | 0.86%   |
| HannStar                | 29        | 0.78%   |
| Unknown                 | 26        | 0.7%    |
| LG Philips              | 26        | 0.7%    |
| AOC                     | 25        | 0.67%   |
| Ancor Communications    | 21        | 0.57%   |
| Acer                    | 21        | 0.57%   |
| Iiyama                  | 19        | 0.51%   |
| ViewSonic               | 18        | 0.49%   |
| CSO                     | 17        | 0.46%   |
| CPT                     | 8         | 0.22%   |
| Sony                    | 7         | 0.19%   |
| Quanta Display          | 7         | 0.19%   |
| Eizo                    | 7         | 0.19%   |
| Panasonic               | 6         | 0.16%   |
| NEC Computers           | 6         | 0.16%   |
| MSI                     | 6         | 0.16%   |
| Pixio                   | 5         | 0.13%   |
| TMX                     | 4         | 0.11%   |
| ___                     | 3         | 0.08%   |
| Vestel Elektronik       | 3         | 0.08%   |
| Toshiba                 | 3         | 0.08%   |
| SLD                     | 3         | 0.08%   |
| LGD                     | 3         | 0.08%   |
| AGO                     | 3         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                  | 209       | 5.59%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 187       | 5%      |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                  | 54        | 1.45%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 42        | 1.12%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 41        | 1.1%    |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 41        | 1.1%    |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 38        | 1.02%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 28        | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 26        | 0.7%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 26        | 0.7%    |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 25        | 0.67%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 22        | 0.59%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 22        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 22        | 0.59%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 22        | 0.59%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                  | 22        | 0.59%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 20        | 0.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 18        | 0.48%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 18        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 16        | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 14        | 0.37%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                  | 13        | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 12        | 0.32%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 12        | 0.32%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 11        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 11        | 0.29%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                  | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 11        | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 10        | 0.27%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 10        | 0.27%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 10        | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 10        | 0.27%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                     | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 10        | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 9         | 0.24%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch           | 9         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1255      | 35.77%  |
| 1366x768 (WXGA)    | 954       | 27.19%  |
| 1280x800 (WXGA)    | 539       | 15.36%  |
| 1600x900 (HD+)     | 135       | 3.85%   |
| 1440x900 (WXGA+)   | 127       | 3.62%   |
| 3840x2160 (4K)     | 95        | 2.71%   |
| 1920x1200 (WUXGA)  | 70        | 1.99%   |
| 2560x1440 (QHD)    | 65        | 1.85%   |
| 1024x600           | 52        | 1.48%   |
| 1280x1024 (SXGA)   | 26        | 0.74%   |
| 2288x1287          | 22        | 0.63%   |
| 2560x1600          | 21        | 0.6%    |
| 1680x1050 (WSXGA+) | 17        | 0.48%   |
| 1024x768 (XGA)     | 16        | 0.46%   |
| 3840x2400          | 13        | 0.37%   |
| 1360x768           | 13        | 0.37%   |
| 2560x1080          | 12        | 0.34%   |
| 3440x1440          | 11        | 0.31%   |
| 2880x1800          | 10        | 0.28%   |
| 2160x1440          | 7         | 0.2%    |
| 1400x1050          | 5         | 0.14%   |
| Unknown            | 5         | 0.14%   |
| 3840x1080          | 4         | 0.11%   |
| 3200x1800 (QHD+)   | 3         | 0.09%   |
| 1600x1200          | 3         | 0.09%   |
| 1024x576           | 3         | 0.09%   |
| 3840x1200          | 2         | 0.06%   |
| 3840x1100          | 2         | 0.06%   |
| 3072x1920          | 2         | 0.06%   |
| 2880x1920          | 2         | 0.06%   |
| 2304x1440          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 1920x540           | 2         | 0.06%   |
| 1920x1280          | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 5760x2160          | 1         | 0.03%   |
| 3840x1600          | 1         | 0.03%   |
| 3520x1080          | 1         | 0.03%   |
| 2520x1680          | 1         | 0.03%   |
| 2048x1152          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1079      | 29.13%  |
| 13      | 956       | 25.81%  |
| 14      | 426       | 11.5%   |
| 11      | 261       | 7.05%   |
| 17      | 190       | 5.13%   |
| 24      | 125       | 3.37%   |
| 12      | 121       | 3.27%   |
| 27      | 86        | 2.32%   |
| 23      | 72        | 1.94%   |
| 21      | 59        | 1.59%   |
| 10      | 53        | 1.43%   |
| 31      | 38        | 1.03%   |
| 18      | 32        | 0.86%   |
| 19      | 25        | 0.67%   |
| Unknown | 25        | 0.67%   |
| 16      | 24        | 0.65%   |
| 142     | 22        | 0.59%   |
| 34      | 18        | 0.49%   |
| 25      | 10        | 0.27%   |
| 32      | 9         | 0.24%   |
| 22      | 9         | 0.24%   |
| 20      | 8         | 0.22%   |
| 84      | 7         | 0.19%   |
| 72      | 6         | 0.16%   |
| 54      | 6         | 0.16%   |
| 40      | 6         | 0.16%   |
| 29      | 5         | 0.13%   |
| 49      | 3         | 0.08%   |
| 46      | 3         | 0.08%   |
| 28      | 3         | 0.08%   |
| 8       | 3         | 0.08%   |
| 52      | 2         | 0.05%   |
| 43      | 2         | 0.05%   |
| 42      | 2         | 0.05%   |
| 26      | 2         | 0.05%   |
| 65      | 1         | 0.03%   |
| 64      | 1         | 0.03%   |
| 55      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 37      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1774      | 48.25%  |
| 201-300        | 1121      | 30.49%  |
| 501-600        | 265       | 7.21%   |
| 351-400        | 216       | 5.87%   |
| 401-500        | 122       | 3.32%   |
| 601-700        | 59        | 1.6%    |
| 701-800        | 28        | 0.76%   |
| Unknown        | 25        | 0.68%   |
| More than 2000 | 22        | 0.6%    |
| 1001-1500      | 20        | 0.54%   |
| 1501-2000      | 13        | 0.35%   |
| 801-900        | 7         | 0.19%   |
| 101-200        | 3         | 0.08%   |
| 901-1000       | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2399      | 71.76%  |
| 16/10   | 801       | 23.96%  |
| 5/4     | 26        | 0.78%   |
| 4/3     | 26        | 0.78%   |
| 1.00    | 22        | 0.66%   |
| 3/2     | 21        | 0.63%   |
| 21/9    | 21        | 0.63%   |
| Unknown | 15        | 0.45%   |
| 2.65    | 4         | 0.12%   |
| 32/9    | 2         | 0.06%   |
| 3.40    | 2         | 0.06%   |
| 3.20    | 2         | 0.06%   |
| 3.73    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 1173      | 31.72%  |
| 101-110        | 1079      | 29.18%  |
| 51-60          | 263       | 7.11%   |
| 201-250        | 205       | 5.54%   |
| 71-80          | 203       | 5.49%   |
| 121-130        | 152       | 4.11%   |
| 61-70          | 117       | 3.16%   |
| 301-350        | 87        | 2.35%   |
| 351-500        | 70        | 1.89%   |
| 251-300        | 59        | 1.6%    |
| 41-50          | 53        | 1.43%   |
| 151-200        | 48        | 1.3%    |
| More than 1000 | 47        | 1.27%   |
| 141-150        | 43        | 1.16%   |
| 131-140        | 26        | 0.7%    |
| Unknown        | 25        | 0.68%   |
| 111-120        | 18        | 0.49%   |
| 501-1000       | 16        | 0.43%   |
| 91-100         | 11        | 0.3%    |
| 1-40           | 3         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1529      | 42.1%   |
| 101-120       | 1298      | 35.74%  |
| 51-100        | 494       | 13.6%   |
| 161-240       | 184       | 5.07%   |
| More than 240 | 52        | 1.43%   |
| 1-50          | 50        | 1.38%   |
| Unknown       | 25        | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2799      | 77.9%   |
| 2     | 455       | 12.66%  |
| 0     | 285       | 7.93%   |
| 3     | 53        | 1.48%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1672      | 29.12%  |
| Realtek Semiconductor             | 1521      | 26.49%  |
| Qualcomm Atheros                  | 671       | 11.69%  |
| Broadcom                          | 645       | 11.23%  |
| Nvidia                            | 371       | 6.46%   |
| Broadcom Limited                  | 232       | 4.04%   |
| Marvell Technology Group          | 114       | 1.99%   |
| MediaTek                          | 64        | 1.11%   |
| ASIX Electronics                  | 42        | 0.73%   |
| Ralink                            | 39        | 0.68%   |
| Sierra Wireless                   | 28        | 0.49%   |
| Dell                              | 28        | 0.49%   |
| Samsung Electronics               | 27        | 0.47%   |
| TP-Link                           | 26        | 0.45%   |
| Xiaomi                            | 23        | 0.4%    |
| Ralink Technology                 | 21        | 0.37%   |
| Qualcomm                          | 19        | 0.33%   |
| DisplayLink                       | 18        | 0.31%   |
| JMicron Technology                | 15        | 0.26%   |
| Ericsson Business Mobile Networks | 15        | 0.26%   |
| Lenovo                            | 13        | 0.23%   |
| Hewlett-Packard                   | 13        | 0.23%   |
| Huawei Technologies               | 8         | 0.14%   |
| OPPO Electronics                  | 7         | 0.12%   |
| Fibocom                           | 7         | 0.12%   |
| Qualcomm Atheros Communications   | 6         | 0.1%    |
| NetGear                           | 6         | 0.1%    |
| Cypress Semiconductor             | 6         | 0.1%    |
| AMD                               | 6         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 5         | 0.09%   |
| ICS Advent                        | 5         | 0.09%   |
| ASUSTek Computer                  | 5         | 0.09%   |
| Microchip Technology              | 4         | 0.07%   |
| Attansic Technology               | 4         | 0.07%   |
| ULi Electronics                   | 3         | 0.05%   |
| Motorola PCS                      | 3         | 0.05%   |
| Edimax Technology                 | 3         | 0.05%   |
| Dresden Elektronik                | 3         | 0.05%   |
| D-Link                            | 3         | 0.05%   |
| Apple                             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 921       | 13.58%  |
| Nvidia MCP79 Ethernet                                                                 | 362       | 5.34%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 362       | 5.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 238       | 3.51%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 160       | 2.36%   |
| Intel Wireless 7260                                                                   | 157       | 2.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 155       | 2.29%   |
| Intel Wireless 8265 / 8275                                                            | 141       | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 134       | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 131       | 1.93%   |
| Intel Wi-Fi 6 AX201                                                                   | 129       | 1.9%    |
| Intel Wireless 7265                                                                   | 128       | 1.89%   |
| Intel Wi-Fi 6 AX200                                                                   | 108       | 1.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 92        | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 92        | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 82        | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 82        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 80        | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 79        | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 78        | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 77        | 1.14%   |
| Intel Wireless 8260                                                                   | 72        | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 57        | 0.84%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 0.83%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 56        | 0.83%   |
| Intel Ethernet Connection (4) I219-V                                                  | 51        | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 50        | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 48        | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 48        | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 48        | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 46        | 0.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 44        | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 41        | 0.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 41        | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 39        | 0.58%   |
| Intel Wireless 3165                                                                   | 38        | 0.56%   |
| Intel Ethernet Connection I219-LM                                                     | 38        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 38        | 0.56%   |
| Intel Ethernet Connection I218-LM                                                     | 37        | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 36        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1579      | 43.63%  |
| Qualcomm Atheros                      | 600       | 16.58%  |
| Broadcom                              | 554       | 15.31%  |
| Realtek Semiconductor                 | 461       | 12.74%  |
| Broadcom Limited                      | 201       | 5.55%   |
| MediaTek                              | 57        | 1.58%   |
| Ralink                                | 39        | 1.08%   |
| Sierra Wireless                       | 28        | 0.77%   |
| Ralink Technology                     | 21        | 0.58%   |
| Dell                                  | 18        | 0.5%    |
| TP-Link                               | 13        | 0.36%   |
| Qualcomm                              | 9         | 0.25%   |
| Fibocom                               | 7         | 0.19%   |
| Qualcomm Atheros Communications       | 6         | 0.17%   |
| NetGear                               | 6         | 0.17%   |
| ASUSTek Computer                      | 5         | 0.14%   |
| Edimax Technology                     | 3         | 0.08%   |
| Hewlett-Packard                       | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| Z-Com                                 | 1         | 0.03%   |
| Winbond Electronics                   | 1         | 0.03%   |
| Wilocity                              | 1         | 0.03%   |
| Ovislink                              | 1         | 0.03%   |
| D-Link System                         | 1         | 0.03%   |
| D-Link                                | 1         | 0.03%   |
| Belkin Components                     | 1         | 0.03%   |
| 3Com                                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 362       | 9.96%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 160       | 4.4%    |
| Intel Wireless 7260                                                                   | 157       | 4.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 155       | 4.26%   |
| Intel Wireless 8265 / 8275                                                            | 141       | 3.88%   |
| Intel Wi-Fi 6 AX201                                                                   | 129       | 3.55%   |
| Intel Wireless 7265                                                                   | 128       | 3.52%   |
| Intel Wi-Fi 6 AX200                                                                   | 108       | 2.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 92        | 2.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 92        | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 82        | 2.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 82        | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 80        | 2.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 79        | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 78        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 77        | 2.12%   |
| Intel Wireless 8260                                                                   | 72        | 1.98%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 57        | 1.57%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 50        | 1.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 48        | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 48        | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 46        | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 44        | 1.21%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 41        | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 41        | 1.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 39        | 1.07%   |
| Intel Wireless 3165                                                                   | 38        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 36        | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 35        | 0.96%   |
| Intel Centrino Ultimate-N 6300                                                        | 30        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 30        | 0.83%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 27        | 0.74%   |
| Intel Wireless 3160                                                                   | 26        | 0.72%   |
| Intel Centrino Advanced-N 6200                                                        | 25        | 0.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 23        | 0.63%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 23        | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 22        | 0.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 22        | 0.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 21        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1337      | 44.3%   |
| Intel                            | 676       | 22.4%   |
| Nvidia                           | 371       | 12.29%  |
| Qualcomm Atheros                 | 144       | 4.77%   |
| Broadcom                         | 119       | 3.94%   |
| Marvell Technology Group         | 114       | 3.78%   |
| ASIX Electronics                 | 42        | 1.39%   |
| Broadcom Limited                 | 34        | 1.13%   |
| Xiaomi                           | 23        | 0.76%   |
| DisplayLink                      | 18        | 0.6%    |
| Samsung Electronics              | 15        | 0.5%    |
| JMicron Technology               | 15        | 0.5%    |
| TP-Link                          | 13        | 0.43%   |
| Lenovo                           | 13        | 0.43%   |
| Qualcomm                         | 10        | 0.33%   |
| OPPO Electronics                 | 7         | 0.23%   |
| MediaTek                         | 7         | 0.23%   |
| Cypress Semiconductor            | 6         | 0.2%    |
| Silicon Integrated Systems [SiS] | 5         | 0.17%   |
| ICS Advent                       | 5         | 0.17%   |
| Huawei Technologies              | 5         | 0.17%   |
| Microchip Technology             | 4         | 0.13%   |
| Attansic Technology              | 4         | 0.13%   |
| Motorola PCS                     | 3         | 0.1%    |
| Hewlett-Packard                  | 3         | 0.1%    |
| Apple                            | 3         | 0.1%    |
| VIA Technologies                 | 2         | 0.07%   |
| Spreadtrum Communications        | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.07%   |
| National Semiconductor           | 2         | 0.07%   |
| Davicom Semiconductor            | 2         | 0.07%   |
| D-Link                           | 2         | 0.07%   |
| ULi Electronics                  | 1         | 0.03%   |
| TP-Link Corporation Limited.     | 1         | 0.03%   |
| MosChip Semiconductor            | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| LG Electronics                   | 1         | 0.03%   |
| LeEco                            | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Google                           | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 921       | 30.19%  |
| Nvidia MCP79 Ethernet                                                  | 362       | 11.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 238       | 7.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 134       | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 131       | 4.29%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 56        | 1.84%   |
| Intel Ethernet Connection (4) I219-V                                   | 51        | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                                  | 48        | 1.57%   |
| Intel Ethernet Connection I219-LM                                      | 38        | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                                  | 38        | 1.25%   |
| Intel Ethernet Connection I218-LM                                      | 37        | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                          | 35        | 1.15%   |
| Intel 82577LM Gigabit Network Connection                               | 30        | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 29        | 0.95%   |
| Intel Ethernet Connection I217-LM                                      | 25        | 0.82%   |
| Intel Ethernet Connection (6) I219-V                                   | 24        | 0.79%   |
| Intel Ethernet Connection (13) I219-V                                  | 23        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 22        | 0.72%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 22        | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 21        | 0.69%   |
| Intel 82567LM Gigabit Network Connection                               | 21        | 0.69%   |
| Intel Ethernet Connection I219-V                                       | 20        | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 19        | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 18        | 0.59%   |
| Intel Ethernet Connection (10) I219-V                                  | 18        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 17        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13        | 0.43%   |
| Realtek Killer E2600 GbE Controller                                    | 13        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 13        | 0.43%   |
| Intel 82579V Gigabit Network Connection                                | 13        | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 12        | 0.39%   |
| Intel Ethernet Connection (13) I219-LM                                 | 12        | 0.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 12        | 0.39%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 11        | 0.36%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 11        | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 11        | 0.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 11        | 0.36%   |
| Intel Ethernet Connection (2) I219-LM                                  | 11        | 0.36%   |
| Intel Ethernet Connection (11) I219-LM                                 | 10        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3473      | 53.94%  |
| Ethernet | 2870      | 44.57%  |
| Modem    | 93        | 1.44%   |
| Unknown  | 3         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2615      | 70.47%  |
| Ethernet | 1094      | 29.48%  |
| Modem    | 2         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2591      | 73.15%  |
| 1     | 866       | 24.45%  |
| 0     | 48        | 1.36%   |
| 3     | 36        | 1.02%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2868      | 80.43%  |
| Yes  | 698       | 19.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1188      | 40.97%  |
| Apple                           | 620       | 21.38%  |
| Realtek Semiconductor           | 265       | 9.14%   |
| Qualcomm Atheros Communications | 217       | 7.48%   |
| Broadcom                        | 123       | 4.24%   |
| Lite-On Technology              | 111       | 3.83%   |
| IMC Networks                    | 107       | 3.69%   |
| Foxconn / Hon Hai               | 67        | 2.31%   |
| Dell                            | 43        | 1.48%   |
| Cambridge Silicon Radio         | 35        | 1.21%   |
| Hewlett-Packard                 | 32        | 1.1%    |
| Toshiba                         | 18        | 0.62%   |
| Realtek                         | 15        | 0.52%   |
| ASUSTek Computer                | 13        | 0.45%   |
| Ralink                          | 12        | 0.41%   |
| Ralink Technology               | 6         | 0.21%   |
| Alps Electric                   | 5         | 0.17%   |
| Taiyo Yuden                     | 4         | 0.14%   |
| Foxconn International           | 4         | 0.14%   |
| MediaTek                        | 3         | 0.1%    |
| Fujitsu                         | 3         | 0.1%    |
| USI                             | 2         | 0.07%   |
| Qcom                            | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 524       | 18.06%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 349       | 12.03%  |
| Intel AX201 Bluetooth                               | 245       | 8.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 180       | 6.2%    |
| Apple Bluetooth USB Host Controller                 | 159       | 5.48%   |
| Realtek Bluetooth Radio                             | 150       | 5.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 134       | 4.62%   |
| Intel AX200 Bluetooth                               | 105       | 3.62%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 59        | 2.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 44        | 1.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 35        | 1.21%   |
| Apple Bluetooth Host Controller                     | 33        | 1.14%   |
| IMC Networks Bluetooth Radio                        | 31        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 30        | 1.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 29        | 1%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 28        | 0.97%   |
| Intel AX211 Bluetooth                               | 27        | 0.93%   |
| Lite-On Bluetooth Device                            | 25        | 0.86%   |
| IMC Networks Bluetooth Device                       | 24        | 0.83%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 0.79%   |
| Realtek 802.11ac WLAN Adapter                       | 22        | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.72%   |
| IMC Networks Wireless_Device                        | 21        | 0.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 20        | 0.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 20        | 0.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 0.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 0.65%   |
| Intel AX210 Bluetooth                               | 19        | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 0.62%   |
| Realtek RTL8723B Bluetooth                          | 17        | 0.59%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 17        | 0.59%   |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.55%   |
| Realtek Bluetooth Radio                             | 15        | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 0.52%   |
| Ralink RT3290 Bluetooth                             | 12        | 0.41%   |
| Lite-On Wireless_Device                             | 12        | 0.41%   |
| Dell DW375 Bluetooth Module                         | 12        | 0.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 11        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2617      | 64.57%  |
| Nvidia                                       | 698       | 17.22%  |
| AMD                                          | 535       | 13.2%   |
| C-Media Electronics                          | 30        | 0.74%   |
| Realtek Semiconductor                        | 18        | 0.44%   |
| Logitech                                     | 16        | 0.39%   |
| Lenovo                                       | 14        | 0.35%   |
| Texas Instruments                            | 10        | 0.25%   |
| Plantronics                                  | 10        | 0.25%   |
| GN Netcom                                    | 10        | 0.25%   |
| Generalplus Technology                       | 10        | 0.25%   |
| Hewlett-Packard                              | 8         | 0.2%    |
| Zoran Co. Personal Media Division (Nogatech) | 6         | 0.15%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.12%   |
| Creative Technology                          | 5         | 0.12%   |
| ASUSTek Computer                             | 5         | 0.12%   |
| JMTek                                        | 4         | 0.1%    |
| Zhaoxin                                      | 3         | 0.07%   |
| ULi Electronics                              | 3         | 0.07%   |
| Kingston Technology                          | 3         | 0.07%   |
| VIA Technologies                             | 2         | 0.05%   |
| SAVITECH                                     | 2         | 0.05%   |
| RODE Microphones                             | 2         | 0.05%   |
| Razer USA                                    | 2         | 0.05%   |
| Microsoft                                    | 2         | 0.05%   |
| DSEA A/S                                     | 2         | 0.05%   |
| Dell                                         | 2         | 0.05%   |
| CMX Systems                                  | 2         | 0.05%   |
| XMOS                                         | 1         | 0.02%   |
| Toshiba                                      | 1         | 0.02%   |
| Thomann                                      | 1         | 0.02%   |
| Tenx Technology                              | 1         | 0.02%   |
| Syntek                                       | 1         | 0.02%   |
| SteelSeries ApS                              | 1         | 0.02%   |
| Sony                                         | 1         | 0.02%   |
| Sennheiser Communications                    | 1         | 0.02%   |
| Samsung Electronics                          | 1         | 0.02%   |
| Pixart Imaging                               | 1         | 0.02%   |
| Phoenix Audio Technologies                   | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 High Definition Audio                                                                | 364       | 7.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 343       | 6.94%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 305       | 6.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 259       | 5.24%   |
| Intel Broadwell-U Audio Controller                                                                | 246       | 4.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 243       | 4.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 187       | 3.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 157       | 3.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 152       | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 147       | 2.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 111       | 2.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 109       | 2.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 109       | 2.21%   |
| Intel 8 Series HD Audio Controller                                                                | 109       | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 109       | 2.21%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 95        | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 90        | 1.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 88        | 1.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 84        | 1.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 79        | 1.6%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 79        | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 77        | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 74        | 1.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 74        | 1.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 66        | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 66        | 1.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 63        | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 59        | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 55        | 1.11%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 45        | 0.91%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 40        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 39        | 0.79%   |
| AMD High Definition Audio Controller                                                              | 38        | 0.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 32        | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 31        | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 31        | 0.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 31        | 0.63%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 29        | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 27        | 0.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 22        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1035      | 29.11%  |
| Samsung Electronics | 919       | 25.85%  |
| Micron Technology   | 394       | 11.08%  |
| Kingston            | 249       | 7%      |
| Unknown             | 232       | 6.53%   |
| Crucial             | 183       | 5.15%   |
| Elpida              | 103       | 2.9%    |
| Ramaxel Technology  | 66        | 1.86%   |
| A-DATA Technology   | 64        | 1.8%    |
| Nanya Technology    | 40        | 1.13%   |
| Corsair             | 36        | 1.01%   |
| Unknown (ABCD)      | 28        | 0.79%   |
| Smart               | 24        | 0.68%   |
| GOODRAM             | 24        | 0.68%   |
| Unknown             | 16        | 0.45%   |
| Transcend           | 13        | 0.37%   |
| Team                | 13        | 0.37%   |
| G.Skill             | 11        | 0.31%   |
| Silicon Power       | 7         | 0.2%    |
| Patriot             | 6         | 0.17%   |
| ASint Technology    | 6         | 0.17%   |
| Apacer              | 6         | 0.17%   |
| Timetec             | 4         | 0.11%   |
| AMD                 | 4         | 0.11%   |
| Wilk                | 3         | 0.08%   |
| Teikon              | 3         | 0.08%   |
| Smart Brazil        | 3         | 0.08%   |
| Qimonda             | 3         | 0.08%   |
| PNY                 | 3         | 0.08%   |
| Infineon            | 3         | 0.08%   |
| Goldkey             | 3         | 0.08%   |
| fef5                | 3         | 0.08%   |
| 48spaces            | 3         | 0.08%   |
| Unknown (89F7)      | 2         | 0.06%   |
| Unifosa             | 2         | 0.06%   |
| Shenzhen WODPOSIT   | 2         | 0.06%   |
| SHARETRONIC         | 2         | 0.06%   |
| Neo Forza           | 2         | 0.06%   |
| Kllisre             | 2         | 0.06%   |
| ff                  | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 264       | 7.11%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.83%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.7%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 60        | 1.62%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 1.19%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 40        | 1.08%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 32        | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 32        | 0.86%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 31        | 0.84%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 0.84%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 29        | 0.78%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 28        | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 28        | 0.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 28        | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 28        | 0.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 28        | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 27        | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 26        | 0.7%    |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 26        | 0.7%    |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.67%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 25        | 0.67%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 24        | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 22        | 0.59%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 21        | 0.57%   |
| Micron RAM EDF8132A3MA-GD-F 2GB LPDDR3 1600MT/s                  | 21        | 0.57%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 19        | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 18        | 0.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.46%   |
| Micron RAM Module 2GB SODIMM DDR2 800MT/s                        | 17        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 16        | 0.43%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s             | 16        | 0.43%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 16        | 0.43%   |
| Unknown                                                          | 16        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.4%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 15        | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 15        | 0.4%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 15        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1171      | 37.65%  |
| DDR3    | 1037      | 33.34%  |
| DDR2    | 557       | 17.91%  |
| LPDDR4  | 102       | 3.28%   |
| LPDDR3  | 97        | 3.12%   |
| SDRAM   | 66        | 2.12%   |
| DDR     | 34        | 1.09%   |
| Unknown | 19        | 0.61%   |
| DDR5    | 11        | 0.35%   |
| LPDDR5  | 8         | 0.26%   |
| DRAM    | 8         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2858      | 91.81%  |
| Row Of Chips | 165       | 5.3%    |
| Unknown      | 53        | 1.7%    |
| Chip         | 23        | 0.74%   |
| DIMM         | 14        | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 998       | 29.73%  |
| 4096  | 813       | 24.22%  |
| 2048  | 540       | 16.09%  |
| 1024  | 511       | 15.22%  |
| 16384 | 368       | 10.96%  |
| 32768 | 76        | 2.26%   |
| 512   | 38        | 1.13%   |
| 256   | 11        | 0.33%   |
| 8072  | 1         | 0.03%   |
| 384   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 733       | 22.18%  |
| 3200    | 579       | 17.52%  |
| 2667    | 513       | 15.52%  |
| 800     | 377       | 11.41%  |
| 2400    | 202       | 6.11%   |
| 667     | 154       | 4.66%   |
| 1334    | 127       | 3.84%   |
| 2133    | 115       | 3.48%   |
| 1333    | 99        | 3%      |
| Unknown | 77        | 2.33%   |
| 1067    | 45        | 1.36%   |
| 1867    | 40        | 1.21%   |
| 4267    | 34        | 1.03%   |
| 3266    | 32        | 0.97%   |
| 4199    | 22        | 0.67%   |
| 1066    | 22        | 0.67%   |
| 533     | 19        | 0.57%   |
| 4800    | 14        | 0.42%   |
| 2048    | 14        | 0.42%   |
| 8400    | 10        | 0.3%    |
| 975     | 10        | 0.3%    |
| 6400    | 9         | 0.27%   |
| 4266    | 8         | 0.24%   |
| 333     | 8         | 0.24%   |
| 3733    | 7         | 0.21%   |
| 266     | 7         | 0.21%   |
| 1866    | 5         | 0.15%   |
| 400     | 5         | 0.15%   |
| 2933    | 3         | 0.09%   |
| 2666    | 3         | 0.09%   |
| 1639    | 3         | 0.09%   |
| 933     | 2         | 0.06%   |
| 5600    | 1         | 0.03%   |
| 3000    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 200     | 1         | 0.03%   |
| 166     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |
| 100     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 33.33%  |
| Canon               | 5         | 20.83%  |
| Xerox               | 4         | 16.67%  |
| Brother Industries  | 4         | 16.67%  |
| Samsung Electronics | 2         | 8.33%   |
| Seiko Epson         | 1         | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Xerox B205                          | 4         | 16.67%  |
| Seiko Epson L120 Series             | 1         | 4.17%   |
| Samsung SCX-472x Series             | 1         | 4.17%   |
| Samsung ML-2010P Mono Laser Printer | 1         | 4.17%   |
| HP Printing Support                 | 1         | 4.17%   |
| HP LaserJet P1005                   | 1         | 4.17%   |
| HP LaserJet 1160 series             | 1         | 4.17%   |
| HP LaserJet 1150                    | 1         | 4.17%   |
| HP LaserJet 1022                    | 1         | 4.17%   |
| HP Ink Tank 110 series              | 1         | 4.17%   |
| HP DeskJet 2620 All-in-One Printer  | 1         | 4.17%   |
| HP DeskJet 2130 series              | 1         | 4.17%   |
| Canon PIXMA MX920 Series            | 1         | 4.17%   |
| Canon LBP3010/LBP3018/LBP3050       | 1         | 4.17%   |
| Canon LBP2900                       | 1         | 4.17%   |
| Canon G3010 series                  | 1         | 4.17%   |
| Canon CanoScan LiDE 300             | 1         | 4.17%   |
| Brother PT-9500PC                   | 1         | 4.17%   |
| Brother MFC-L2707DW                 | 1         | 4.17%   |
| Brother MFC-J460DW                  | 1         | 4.17%   |
| Brother HL-L2340D series            | 1         | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Canon          | 7         | 70%     |
| Seiko Epson    | 2         | 20%     |
| Mustek Systems | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                       | 3         | 30%     |
| Canon CanoScan LiDE 120                       | 2         | 20%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 10%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 10%     |
| Mustek Systems BearPaw 2400 CU Plus           | 1         | 10%     |
| Canon CanoScan LIDE 25                        | 1         | 10%     |
| Canon CanoScan LiDE 210                       | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 639       | 24.55%  |
| IMC Networks                           | 282       | 10.83%  |
| Quanta                                 | 238       | 9.14%   |
| Bison Electronics                      | 225       | 8.64%   |
| Microdia                               | 193       | 7.41%   |
| Realtek Semiconductor                  | 185       | 7.11%   |
| Sunplus Innovation Technology          | 122       | 4.69%   |
| Cheng Uei Precision Industry (Foxlink) | 90        | 3.46%   |
| Suyin                                  | 78        | 3%      |
| Lite-On Technology                     | 68        | 2.61%   |
| Luxvisions Innotech Limited            | 59        | 2.27%   |
| Syntek                                 | 57        | 2.19%   |
| Acer                                   | 54        | 2.07%   |
| Apple                                  | 50        | 1.92%   |
| Logitech                               | 33        | 1.27%   |
| Silicon Motion                         | 28        | 1.08%   |
| Alcor Micro                            | 24        | 0.92%   |
| Lenovo                                 | 22        | 0.85%   |
| Sonix Technology                       | 14        | 0.54%   |
| Ricoh                                  | 13        | 0.5%    |
| Z-Star Microelectronics                | 11        | 0.42%   |
| Primax Electronics                     | 11        | 0.42%   |
| Importek                               | 9         | 0.35%   |
| SunplusIT                              | 8         | 0.31%   |
| icSpring                               | 6         | 0.23%   |
| ALi                                    | 6         | 0.23%   |
| Y Media                                | 5         | 0.19%   |
| Samsung Electronics                    | 5         | 0.19%   |
| Intel                                  | 5         | 0.19%   |
| Genesys Logic                          | 5         | 0.19%   |
| Generalplus Technology                 | 5         | 0.19%   |
| OmniVision Technologies                | 4         | 0.15%   |
| Unknown                                | 4         | 0.15%   |
| MacroSilicon                           | 3         | 0.12%   |
| Sunplus Technology                     | 2         | 0.08%   |
| Shine-optics                           | 2         | 0.08%   |
| Pixart Imaging                         | 2         | 0.08%   |
| Mimaki Engineering                     | 2         | 0.08%   |
| Microsoft                              | 2         | 0.08%   |
| Huawei Technologies                    | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 176       | 6.74%   |
| Microdia Integrated_Webcam_HD                       | 102       | 3.9%    |
| IMC Networks Integrated Camera                      | 89        | 3.41%   |
| Quanta Chromebook HD Camera                         | 69        | 2.64%   |
| Realtek Integrated_Webcam_HD                        | 65        | 2.49%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 64        | 2.45%   |
| Bison Integrated Camera                             | 63        | 2.41%   |
| Chicony HD Webcam                                   | 53        | 2.03%   |
| Bison BisonCam, NB Pro                              | 50        | 1.91%   |
| Sunplus Integrated_Webcam_HD                        | 37        | 1.42%   |
| Chicony HP HD Camera                                | 37        | 1.42%   |
| Chicony USB2.0 HD UVC WebCam                        | 36        | 1.38%   |
| Quanta HD User Facing                               | 33        | 1.26%   |
| Quanta HP TrueVision HD Camera                      | 31        | 1.19%   |
| Syntek Integrated Camera                            | 29        | 1.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 27        | 1.03%   |
| Quanta VGA WebCam                                   | 26        | 1%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 23        | 0.88%   |
| Lite-On Integrated Camera                           | 23        | 0.88%   |
| Bison SunplusIT Integrated Camera                   | 23        | 0.88%   |
| Microdia Integrated Webcam                          | 22        | 0.84%   |
| Lite-On HP HD Camera                                | 22        | 0.84%   |
| Chicony HP TrueVision HD Camera                     | 21        | 0.8%    |
| Sunplus HD WebCam                                   | 19        | 0.73%   |
| Quanta HP HD Camera                                 | 19        | 0.73%   |
| Realtek USB Camera                                  | 18        | 0.69%   |
| Chicony Integrated Camera (1280x720@30)             | 18        | 0.69%   |
| Bison Lenovo Integrated Webcam                      | 18        | 0.69%   |
| Chicony HD User Facing                              | 17        | 0.65%   |
| Apple Built-in iSight                               | 17        | 0.65%   |
| Luxvisions Innotech Limited HP HD Camera            | 16        | 0.61%   |
| IMC Networks HD Camera                              | 16        | 0.61%   |
| Chicony Lenovo EasyCamera                           | 16        | 0.61%   |
| Chicony HP Webcam                                   | 16        | 0.61%   |
| Bison HD Webcam                                     | 16        | 0.61%   |
| Chicony Chromebook HD Camera                        | 15        | 0.57%   |
| Realtek Integrated Webcam                           | 14        | 0.54%   |
| Quanta HP Webcam                                    | 14        | 0.54%   |
| IMC Networks USB 2.0 Camera                         | 14        | 0.54%   |
| Chicony HP Truevision HD                            | 14        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 184       | 34.46%  |
| Synaptics                          | 166       | 31.09%  |
| Shenzhen Goodix Technology         | 68        | 12.73%  |
| AuthenTec                          | 32        | 5.99%   |
| Upek                               | 31        | 5.81%   |
| Elan Microelectronics              | 23        | 4.31%   |
| LighTuning Technology              | 19        | 3.56%   |
| STMicroelectronics                 | 9         | 1.69%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.19%   |
| Focal-systems.Corp                 | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 67        | 12.55%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 42        | 7.87%   |
| Shenzhen Goodix  Fingerprint Device                                        | 40        | 7.49%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 6.18%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 6.18%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 5.24%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 5.24%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 18        | 3.37%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 3.18%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 2.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 2.43%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 2.43%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 2.06%   |
| Validity Sensors VFS491                                                    | 10        | 1.87%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 1.87%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 1.87%   |
| Elan ELAN:ARM-M4                                                           | 10        | 1.87%   |
| Elan ELAN:Fingerprint                                                      | 9         | 1.69%   |
| Synaptics Prometheus Fingerprint Reader                                    | 8         | 1.5%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.5%    |
| AuthenTec AES2810                                                          | 8         | 1.5%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 1.31%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.31%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.31%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.31%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.31%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.31%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.12%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.94%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.75%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.75%   |
| Elan WBF Fingerprint Sensor                                                | 4         | 0.75%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.56%   |
| Synaptics WBDI                                                             | 3         | 0.56%   |
| Synaptics  WBDI                                                            | 3         | 0.56%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.56%   |
| AuthenTec AES1600                                                          | 3         | 0.56%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.37%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 112       | 37.97%  |
| Alcor Micro               | 99        | 33.56%  |
| Upek                      | 26        | 8.81%   |
| O2 Micro                  | 25        | 8.47%   |
| Lenovo                    | 17        | 5.76%   |
| Gemalto (was Gemplus)     | 4         | 1.36%   |
| Yubico.com                | 2         | 0.68%   |
| SCM Microsystems          | 2         | 0.68%   |
| C3PO                      | 2         | 0.68%   |
| Aladdin Knowledge Systems | 2         | 0.68%   |
| OmniKey                   | 1         | 0.34%   |
| Clay Logic                | 1         | 0.34%   |
| CHERRY                    | 1         | 0.34%   |
| Advanced Card Systems     | 1         | 0.34%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 98        | 33.22%  |
| Broadcom 58200                                                               | 34        | 11.53%  |
| Broadcom BCM5880 Secure Applications Processor                               | 32        | 10.85%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 8.81%   |
| Broadcom 5880                                                                | 23        | 7.8%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 7.12%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 7.12%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 5.76%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.36%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.68%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.68%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.68%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.68%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.68%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.34%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.34%   |
| OmniKey CardMan 4321                                                         | 1         | 0.34%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.34%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.34%   |
| C3PO LTC31v2                                                                 | 1         | 0.34%   |
| C3PO KBR36                                                                   | 1         | 0.34%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.34%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.34%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2017      | 56.29%  |
| 1     | 1183      | 33.02%  |
| 2     | 301       | 8.4%    |
| 3     | 73        | 2.04%   |
| 4     | 5         | 0.14%   |
| 5     | 3         | 0.08%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 606       | 30.78%  |
| Fingerprint reader       | 532       | 27.02%  |
| Chipcard                 | 275       | 13.97%  |
| Multimedia controller    | 204       | 10.36%  |
| Net/wireless             | 181       | 9.19%   |
| Bluetooth                | 35        | 1.78%   |
| Communication controller | 29        | 1.47%   |
| Storage                  | 23        | 1.17%   |
| Card reader              | 22        | 1.12%   |
| Camera                   | 20        | 1.02%   |
| Sound                    | 13        | 0.66%   |
| Net/ethernet             | 10        | 0.51%   |
| Flash memory             | 6         | 0.3%    |
| Network                  | 5         | 0.25%   |
| Modem                    | 4         | 0.2%    |
| Unassigned class         | 2         | 0.1%    |
| Tv card                  | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |

