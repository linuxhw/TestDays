Zorin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 4522

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Dell          | Inspiron 5559               | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Framework     | Laptop                      | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| Toshiba       | Satellite C70D-A            | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Dell          | G15 5511                    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| Gigabyte      | G5 KF                       | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Dell          | Latitude 5400               | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| HP            | 15                          | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| Dell          | Venue 11 Pro 5130           | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| HP            | Laptop 14-dq1xxx            | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [b1efa66e79](https://linux-hardware.org/?probe=b1efa66e79) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [7726b35ef6](https://linux-hardware.org/?probe=7726b35ef6) | Aug 25, 2023 |
| Google        | Rammus                      | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| TERRA         | TERRAPC                     | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| ASUSTek       | X756UQ                      | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | Precision M4700             | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| HP            | Notebook                    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| Dell          | Latitude E5470              | [ca95c6f5bc](https://linux-hardware.org/?probe=ca95c6f5bc) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Google        | Coral                       | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Lenovo        | G40-30 80FY                 | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | 15                          | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| AMI           | Unknown                     | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| HP            | 350 G2                      | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Unknown       | Unknown                     | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| HP            | Presario CQ56               | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Dell          | Latitude 7490               | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| HP            | 530                         | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| HP            | Pavilion dv4                | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| HP            | Pavilion g7                 | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| HP            | EliteBook 8560p             | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Dell          | Vostro 1500                 | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| Acer          | TravelMate B113             | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| OEM           | Unknown                     | [a45e07b803](https://linux-hardware.org/?probe=a45e07b803) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| Dell          | Latitude E6400              | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Acer          | AO756                       | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| HP            | Compaq Presario CQ50        | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| Dell          | Latitude E6440              | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Dell          | Vostro 1500                 | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Dell          | Latitude 3520               | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| Positivo      | Mobile                      | [1a6243fc5d](https://linux-hardware.org/?probe=1a6243fc5d) | Jul 18, 2023 |
| Positivo      | Mobile                      | [0c194a9d1d](https://linux-hardware.org/?probe=0c194a9d1d) | Jul 18, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Alienware     | M11xR3                      | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HP            | 15                          | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [9cab0f6446](https://linux-hardware.org/?probe=9cab0f6446) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [c1a6aea2fc](https://linux-hardware.org/?probe=c1a6aea2fc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Compaq 2510p                | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| HP            | Compaq 2510p                | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| HP            | Notebook                    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| OTVOC         | N1                          | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| Dell          | Precision M4700             | [3680e0f79f](https://linux-hardware.org/?probe=3680e0f79f) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| Acer          | Nitro AN515-44              | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| OTVOC         | N1                          | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| HP            | Compaq 6830s                | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| Dell          | Latitude E6400              | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| Dell          | Latitude 3189               | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Dell          | Latitude E6400              | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| Acer          | AOD270                      | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | EliteBook 8560p             | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Google        | Kefka                       | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Sony          | VPCCA15FX                   | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| HP            | EliteBook 840 G3            | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Haier         | Y11B                        | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| eMachines     | eMD728                      | [85dd880b0d](https://linux-hardware.org/?probe=85dd880b0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| Dell          | Venue 11 Pro 5130           | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| HP            | Pavilion g7                 | [c599527484](https://linux-hardware.org/?probe=c599527484) | Jun 11, 2023 |
| Samsung       | N150/N210/N220              | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| Google        | Pirika                      | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| HP            | Pavilion Notebook           | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| Apple         | MacBookPro8,1               | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| HP            | ProBook 450 G2              | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| IPASON        | P3                          | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Toshiba       | Satellite L650              | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Sony          | SVF14214CXW                 | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| ASUSTek       | U43Jc                       | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | Pavilion dv6                | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| Acer          | Aspire ES1-523              | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| Toshiba       | TECRA M10                   | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| HP            | ProBook 4740s               | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| ASUSTek       | G50VT                       | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Google        | Lars                        | [25cc6549c3](https://linux-hardware.org/?probe=25cc6549c3) | May 25, 2023 |
| HP            | ProBook 6440b               | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| Apple         | MacBookAir4,1               | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| HP            | Pavilion g6                 | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Stream Notebook             | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8c7d3913b8](https://linux-hardware.org/?probe=8c7d3913b8) | May 24, 2023 |
| Apple         | MacBookPro7,1               | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [08746538f6](https://linux-hardware.org/?probe=08746538f6) | May 23, 2023 |
| Dell          | Latitude E5450              | [642802d511](https://linux-hardware.org/?probe=642802d511) | May 23, 2023 |
| Dell          | Inspiron 1501               | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| HP            | Pavilion g6                 | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| Packard Be... | EasyNote MH35               | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| Acer          | Aspire A515-56              | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| Dell          | Latitude E7450              | [b76cb7567c](https://linux-hardware.org/?probe=b76cb7567c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aae519e65d](https://linux-hardware.org/?probe=aae519e65d) | May 19, 2023 |
| Tactus        | GeoBook 140                 | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Philco        | PHN14C                      | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Acer          | Aspire A514-55              | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| Apple         | MacBookAir7,2               | [cadb0eb363](https://linux-hardware.org/?probe=cadb0eb363) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [cd3c24c6a2](https://linux-hardware.org/?probe=cd3c24c6a2) | May 17, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e18deba45b](https://linux-hardware.org/?probe=e18deba45b) | May 17, 2023 |
| Framework     | Laptop                      | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [d825262368](https://linux-hardware.org/?probe=d825262368) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [18ca79ef29](https://linux-hardware.org/?probe=18ca79ef29) | May 16, 2023 |
| Dell          | XPS 17 9700                 | [7b95691784](https://linux-hardware.org/?probe=7b95691784) | May 15, 2023 |
| Samsung       | N150/N210/N220              | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [03c67bbed5](https://linux-hardware.org/?probe=03c67bbed5) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Apple         | MacBookPro10,1              | [d27a3510ed](https://linux-hardware.org/?probe=d27a3510ed) | May 14, 2023 |
| HP            | Presario CQ61               | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Google        | Bluebird                    | [c10880ed1b](https://linux-hardware.org/?probe=c10880ed1b) | May 14, 2023 |
| Acer          | Aspire E5-574               | [89fbcb7903](https://linux-hardware.org/?probe=89fbcb7903) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [83e208da09](https://linux-hardware.org/?probe=83e208da09) | May 14, 2023 |
| Lenovo        | IdeaPad Z470                | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| Dell          | Latitude 3340               | [59d83d9cef](https://linux-hardware.org/?probe=59d83d9cef) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| Chuwi         | GemiBook XPro               | [53b6692944](https://linux-hardware.org/?probe=53b6692944) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | [297921aabf](https://linux-hardware.org/?probe=297921aabf) | May 13, 2023 |
| Acer          | Aspire E1-570               | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Google        | Kled                        | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| Dell          | Precision M2800             | [571407d9a3](https://linux-hardware.org/?probe=571407d9a3) | May 12, 2023 |
| Chuwi         | GemiBook XPro               | [e13fe43842](https://linux-hardware.org/?probe=e13fe43842) | May 12, 2023 |
| HP            | ProBook 4535s               | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | EliteBook 820 G4            | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | OMEN by Laptop              | [5a1484127d](https://linux-hardware.org/?probe=5a1484127d) | May 12, 2023 |
| eMachines     | E620                        | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| Apple         | MacBookPro10,1              | [381ca3ca78](https://linux-hardware.org/?probe=381ca3ca78) | May 11, 2023 |
| HP            | OMEN by Laptop              | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| HP            | EliteBook 820 G4            | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | EliteBook 745 G3            | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Acer          | Aspire A315-23              | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Toshiba       | TECRA M10                   | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| HP            | Pavilion dv7                | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| Toshiba       | Satellite M60               | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| ASUSTek       | GL702VI                     | [3598875ef3](https://linux-hardware.org/?probe=3598875ef3) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [372fa59e86](https://linux-hardware.org/?probe=372fa59e86) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [9ac068efc7](https://linux-hardware.org/?probe=9ac068efc7) | May 09, 2023 |
| Dell          | Latitude E6520              | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | Laptop 15                   | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Acer          | Aspire E5-574               | [d48affb6b2](https://linux-hardware.org/?probe=d48affb6b2) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| HP            | 655                         | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Positivo      | S14CT01                     | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Dell          | Latitude 5520               | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | [a6da9a31d7](https://linux-hardware.org/?probe=a6da9a31d7) | May 06, 2023 |
| Dell          | Inspiron 3501               | [b7bf9f8683](https://linux-hardware.org/?probe=b7bf9f8683) | May 06, 2023 |
| HP            | ProBook 6570b               | [480e352bf8](https://linux-hardware.org/?probe=480e352bf8) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [d8582f94de](https://linux-hardware.org/?probe=d8582f94de) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [4ac4356e10](https://linux-hardware.org/?probe=4ac4356e10) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [37fd24fab6](https://linux-hardware.org/?probe=37fd24fab6) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Unknown       | X133                        | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [cf49833602](https://linux-hardware.org/?probe=cf49833602) | May 04, 2023 |
| HP            | EliteBook 8470p             | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Acer          | Aspire 5732Z                | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| Unknown       | E450                        | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Dell          | XPS 15 9560                 | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| KUU           | Andes II                    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Acer          | Aspire E1-570               | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| Acer          | Aspire V5-531               | [d8c61ad691](https://linux-hardware.org/?probe=d8c61ad691) | May 02, 2023 |
| Dell          | Latitude E6540              | [e6f334c91c](https://linux-hardware.org/?probe=e6f334c91c) | May 01, 2023 |
| Acer          | Aspire A315-21              | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| ASUSTek       | K53U                        | [0745a61353](https://linux-hardware.org/?probe=0745a61353) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Acer          | Aspire E5-574               | [bcd38374a3](https://linux-hardware.org/?probe=bcd38374a3) | May 01, 2023 |
| HP            | Pavilion dv7                | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Positivo      | S14CT01                     | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Positivo      | S14CT01                     | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| Dell          | Vostro 1510                 | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| Acer          | AOHAPPY                     | [6f32fad8f0](https://linux-hardware.org/?probe=6f32fad8f0) | Apr 24, 2023 |
| Toshiba       | Satellite C45-A             | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [60d1d4aec8](https://linux-hardware.org/?probe=60d1d4aec8) | Apr 24, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [c087d6cbae](https://linux-hardware.org/?probe=c087d6cbae) | Apr 24, 2023 |
| Dell          | XPS 15 9530                 | [d9429d7e06](https://linux-hardware.org/?probe=d9429d7e06) | Apr 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BH0... | [b76462c15b](https://linux-hardware.org/?probe=b76462c15b) | Apr 23, 2023 |
| MSI           | GP62 7RD                    | [277bb2d2e3](https://linux-hardware.org/?probe=277bb2d2e3) | Apr 23, 2023 |
| Acer          | AOD270                      | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| HP            | Laptop 14-em0xxx            | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [ca0be4b423](https://linux-hardware.org/?probe=ca0be4b423) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [74e38a8db9](https://linux-hardware.org/?probe=74e38a8db9) | Apr 22, 2023 |
| Acer          | AOHAPPY                     | [57a7ebf03f](https://linux-hardware.org/?probe=57a7ebf03f) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | [e472034313](https://linux-hardware.org/?probe=e472034313) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | [e500ddd5d9](https://linux-hardware.org/?probe=e500ddd5d9) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7d380bf016](https://linux-hardware.org/?probe=7d380bf016) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7029b5ee48](https://linux-hardware.org/?probe=7029b5ee48) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Dell          | XPS 15 9530                 | [bb0be3d9e3](https://linux-hardware.org/?probe=bb0be3d9e3) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| Acer          | Aspire E5-574               | [2f60207985](https://linux-hardware.org/?probe=2f60207985) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| Dell          | Vostro 3580                 | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| Apple         | MacBookPro5,3               | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1DU01    | [3fc78b3451](https://linux-hardware.org/?probe=3fc78b3451) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| AZW           | SEi                         | [a382976bf2](https://linux-hardware.org/?probe=a382976bf2) | Apr 15, 2023 |
| AZW           | SEi                         | [980b83cf5e](https://linux-hardware.org/?probe=980b83cf5e) | Apr 15, 2023 |
| Acer          | Aspire V3-772               | [2b6f0394d7](https://linux-hardware.org/?probe=2b6f0394d7) | Apr 15, 2023 |
| Acer          | Aspire ES1-731G             | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [ba3d9dd7e7](https://linux-hardware.org/?probe=ba3d9dd7e7) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| Apple         | MacBookPro14,1              | [2ca7c3fccc](https://linux-hardware.org/?probe=2ca7c3fccc) | Apr 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [a4c5130b84](https://linux-hardware.org/?probe=a4c5130b84) | Apr 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e122e8dab8](https://linux-hardware.org/?probe=e122e8dab8) | Apr 15, 2023 |
| Positivo      | Q4128C-S                    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [9e6cfba525](https://linux-hardware.org/?probe=9e6cfba525) | Apr 13, 2023 |
| Acer          | Aspire E5-771G              | [504d600530](https://linux-hardware.org/?probe=504d600530) | Apr 13, 2023 |
| HP            | Compaq Presario F700        | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Dell          | Inspiron 1545               | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [b504683b39](https://linux-hardware.org/?probe=b504683b39) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [8b8d053221](https://linux-hardware.org/?probe=8b8d053221) | Apr 12, 2023 |
| Toshiba       | Satellite C650D             | [fb8b24d111](https://linux-hardware.org/?probe=fb8b24d111) | Apr 12, 2023 |
| Apple         | MacBookPro14,2              | [1bc09aed8a](https://linux-hardware.org/?probe=1bc09aed8a) | Apr 10, 2023 |
| Dell          | XPS 13 9343                 | [f847287142](https://linux-hardware.org/?probe=f847287142) | Apr 09, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [8b461d224b](https://linux-hardware.org/?probe=8b461d224b) | Apr 06, 2023 |
| HP            | ProBook 4540s               | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| HP            | Notebook                    | [4ac4839ccd](https://linux-hardware.org/?probe=4ac4839ccd) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | [5a864191a9](https://linux-hardware.org/?probe=5a864191a9) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | [bb24498044](https://linux-hardware.org/?probe=bb24498044) | Apr 05, 2023 |
| Google        | Cyan                        | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| Toshiba       | Satellite C650              | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| Dell          | Latitude E6430              | [5c205ea646](https://linux-hardware.org/?probe=5c205ea646) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK T935               | [1cc4178b9a](https://linux-hardware.org/?probe=1cc4178b9a) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [45086032e1](https://linux-hardware.org/?probe=45086032e1) | Apr 02, 2023 |
| Notebook      | NJ50GU                      | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| Lenovo        | V570 1066EDG                | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| Dell          | Vostro 1520                 | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | [22d22e0742](https://linux-hardware.org/?probe=22d22e0742) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | [2994622700](https://linux-hardware.org/?probe=2994622700) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Positivo      | S14SL01                     | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| HP            | kip                         | [fe84eac39e](https://linux-hardware.org/?probe=fe84eac39e) | Mar 30, 2023 |
| Positivo      | Q232A                       | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Positivo      | Q232A                       | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| Dell          | Precision M4500             | [cf7e033a17](https://linux-hardware.org/?probe=cf7e033a17) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| Dell          | Latitude 3590               | [9b5971401c](https://linux-hardware.org/?probe=9b5971401c) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Apple         | MacBookPro11,2              | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [90fa9585c9](https://linux-hardware.org/?probe=90fa9585c9) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| WEIPAI        | S15                         | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| HP            | Stream Notebook             | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Dell          | Latitude E5510              | [8a9a1eec2c](https://linux-hardware.org/?probe=8a9a1eec2c) | Mar 24, 2023 |
| Framework     | Laptop                      | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| Acer          | Aspire A315-59              | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| Dell          | Inspiron 5555               | [efab305a00](https://linux-hardware.org/?probe=efab305a00) | Mar 24, 2023 |
| HP            | 255 G5                      | [99e2d83974](https://linux-hardware.org/?probe=99e2d83974) | Mar 24, 2023 |
| Dell          | Inspiron 3721               | [e992b8f3a0](https://linux-hardware.org/?probe=e992b8f3a0) | Mar 23, 2023 |
| HP            | Pavilion 15                 | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| HP            | Pavilion dv6                | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| Dell          | Latitude E7240              | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| Dell          | Inspiron 5405               | [bb59d0b5e9](https://linux-hardware.org/?probe=bb59d0b5e9) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| Acer          | TravelMate 2490             | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| Dell          | Inspiron 5423               | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| Google        | Kip                         | [84b79bf446](https://linux-hardware.org/?probe=84b79bf446) | Mar 19, 2023 |
| Google        | Kip                         | [4e63ea7ac8](https://linux-hardware.org/?probe=4e63ea7ac8) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| Microtech     | CoreBook                    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| Dell          | Inspiron 3721               | [c7b5ea67bb](https://linux-hardware.org/?probe=c7b5ea67bb) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| ASUSTek       | G53SX                       | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| HP            | Pavilion dm1                | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Alienware     | 15 R3                       | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| Lenovo        | Yoga 2 13 20344             | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| Google        | Babymega                    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| Acer          | Aspire 5736Z                | [d9e1bb3da7](https://linux-hardware.org/?probe=d9e1bb3da7) | Mar 16, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [f6a3a68640](https://linux-hardware.org/?probe=f6a3a68640) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| Google        | Celes                       | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| HP            | Pavilion dv6                | [9d5d0051ea](https://linux-hardware.org/?probe=9d5d0051ea) | Mar 13, 2023 |
| HP            | Pavilion 15                 | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| Toshiba       | PORTEGE X30-D               | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Dell          | Latitude E5470              | [86adaddcae](https://linux-hardware.org/?probe=86adaddcae) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| HP            | Pavilion dv6                | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Dell          | Latitude E5470              | [e7e23885b7](https://linux-hardware.org/?probe=e7e23885b7) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Medion        | Akoya E1318T                | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | [6648af3696](https://linux-hardware.org/?probe=6648af3696) | Mar 10, 2023 |
| Lenovo        | G50-45 80E3                 | [807d1626b4](https://linux-hardware.org/?probe=807d1626b4) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | [3b0a7cfbf0](https://linux-hardware.org/?probe=3b0a7cfbf0) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | [08bfa4188e](https://linux-hardware.org/?probe=08bfa4188e) | Mar 10, 2023 |
| HP            | ProBook 4530s               | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Precision M6700             | [7a02d78344](https://linux-hardware.org/?probe=7a02d78344) | Mar 10, 2023 |
| HP            | ZBook 17 G2                 | [565c8963d4](https://linux-hardware.org/?probe=565c8963d4) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| Acer          | Aspire M3-581G              | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Dell          | Latitude 3180               | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| Multilaser    | PC130                       | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0T500     | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d01b6ad50c](https://linux-hardware.org/?probe=d01b6ad50c) | Mar 08, 2023 |
| ASUSTek       | K50IJ                       | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| Dell          | Latitude E4310              | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| Google        | Candy                       | [e74102ff2c](https://linux-hardware.org/?probe=e74102ff2c) | Mar 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [3f1ebc8271](https://linux-hardware.org/?probe=3f1ebc8271) | Mar 07, 2023 |
| Google        | Lillipup                    | [33350c987b](https://linux-hardware.org/?probe=33350c987b) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| YJKC          | vBOOK Plus RVP7             | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Google        | Lillipup                    | [214481f959](https://linux-hardware.org/?probe=214481f959) | Mar 06, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [657175938b](https://linux-hardware.org/?probe=657175938b) | Mar 05, 2023 |
| Timi          | TM1701                      | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [3e60e33df2](https://linux-hardware.org/?probe=3e60e33df2) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1237954f03](https://linux-hardware.org/?probe=1237954f03) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | [a3b6a280c1](https://linux-hardware.org/?probe=a3b6a280c1) | Mar 02, 2023 |
| HP            | Notebook                    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| ASUSTek       | UX331UA                     | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | [7b17e49d0f](https://linux-hardware.org/?probe=7b17e49d0f) | Mar 02, 2023 |
| ASUSTek       | X200MA                      | [95b0a4d944](https://linux-hardware.org/?probe=95b0a4d944) | Mar 02, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e9b7ee04ec](https://linux-hardware.org/?probe=e9b7ee04ec) | Mar 01, 2023 |
| Toshiba       | Satellite S55t-B            | [69734289ba](https://linux-hardware.org/?probe=69734289ba) | Mar 01, 2023 |
| MSI           | Raider GE66 12UHS           | [3fcfdd9fba](https://linux-hardware.org/?probe=3fcfdd9fba) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| Dell          | Inspiron N5010              | [480ff87a20](https://linux-hardware.org/?probe=480ff87a20) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| HP            | ENVY 17                     | [61d1252ef3](https://linux-hardware.org/?probe=61d1252ef3) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
| Dell          | Inspiron 3793               | [d7b51f6048](https://linux-hardware.org/?probe=d7b51f6048) | Feb 27, 2023 |
| HP            | Pavilion dv7                | [d5da5f62b8](https://linux-hardware.org/?probe=d5da5f62b8) | Feb 27, 2023 |
| Acer          | TravelMate B113             | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [42acb38635](https://linux-hardware.org/?probe=42acb38635) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e8c76a33fe](https://linux-hardware.org/?probe=e8c76a33fe) | Feb 27, 2023 |
| Dell          | Vostro 1540                 | [8f09ea4351](https://linux-hardware.org/?probe=8f09ea4351) | Feb 27, 2023 |
| HP            | ENVY m7 Notebook            | [14374fbcc8](https://linux-hardware.org/?probe=14374fbcc8) | Feb 27, 2023 |
| Lenovo        | V570 1066EDG                | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| HP            | 620                         | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Dell          | Latitude E6440              | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| HP            | Laptop 15-dy2xxx            | [7f88a11698](https://linux-hardware.org/?probe=7f88a11698) | Feb 25, 2023 |
| Digibras      | NH4CU03                     | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| HP            | Laptop 14-ck0xxx            | [bafb67390c](https://linux-hardware.org/?probe=bafb67390c) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Apple         | MacBookPro12,1              | [3b27d3609f](https://linux-hardware.org/?probe=3b27d3609f) | Feb 24, 2023 |
| HP            | ProBook 4545s               | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| ASUSTek       | T100TAF                     | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| Dell          | Latitude 7480               | [fd80b301db](https://linux-hardware.org/?probe=fd80b301db) | Feb 23, 2023 |
| Lenovo        | G500 20236                  | [294c5c45e6](https://linux-hardware.org/?probe=294c5c45e6) | Feb 23, 2023 |
| DERE          | V14                         | [bb2d40e676](https://linux-hardware.org/?probe=bb2d40e676) | Feb 22, 2023 |
| HP            | ENVY 17                     | [ea0b2e63ef](https://linux-hardware.org/?probe=ea0b2e63ef) | Feb 21, 2023 |
| Teclast       | F7                          | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [5d32bc7f7c](https://linux-hardware.org/?probe=5d32bc7f7c) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [a00e724475](https://linux-hardware.org/?probe=a00e724475) | Feb 21, 2023 |
| Dell          | System XPS L502X            | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| HP            | 620                         | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Toshiba       | PORTEGE Z30-A               | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Dell          | Latitude E5440              | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Toshiba       | Satellite L50-B             | [3c53a60245](https://linux-hardware.org/?probe=3c53a60245) | Feb 19, 2023 |
| Toshiba       | Satellite L50D-B            | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [752cdf5b2b](https://linux-hardware.org/?probe=752cdf5b2b) | Feb 19, 2023 |
| Multilaser    | PC130                       | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| HP            | Unknown                     | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| HP            | ENVY 17                     | [de8af1b249](https://linux-hardware.org/?probe=de8af1b249) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Medion        | E7220                       | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Google        | Robo                        | [303c72db93](https://linux-hardware.org/?probe=303c72db93) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| Dell          | Inspiron 3793               | [b997f44969](https://linux-hardware.org/?probe=b997f44969) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c08ad0f295](https://linux-hardware.org/?probe=c08ad0f295) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| HP            | ENVY TS Sleekbook 4         | [1189701feb](https://linux-hardware.org/?probe=1189701feb) | Feb 15, 2023 |
| Acer          | Extensa 5230                | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Dell          | Latitude 3320               | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [6c1c0027b1](https://linux-hardware.org/?probe=6c1c0027b1) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Dell          | System XPS L502X            | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [03123ee601](https://linux-hardware.org/?probe=03123ee601) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | [a7aa67f64e](https://linux-hardware.org/?probe=a7aa67f64e) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | [eda645cefe](https://linux-hardware.org/?probe=eda645cefe) | Feb 14, 2023 |
| Samsung       | 700T1C                      | [66c15f037d](https://linux-hardware.org/?probe=66c15f037d) | Feb 14, 2023 |
| Samsung       | 700T1C                      | [9e154ea3a4](https://linux-hardware.org/?probe=9e154ea3a4) | Feb 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [d1edc30dac](https://linux-hardware.org/?probe=d1edc30dac) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | [baa5f72e80](https://linux-hardware.org/?probe=baa5f72e80) | Feb 12, 2023 |
| HP            | Notebook                    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6f7c0f381e](https://linux-hardware.org/?probe=6f7c0f381e) | Feb 12, 2023 |
| HP            | Laptop 15-dy2xxx            | [131d5052d1](https://linux-hardware.org/?probe=131d5052d1) | Feb 11, 2023 |
| Dell          | Inspiron 16 5625            | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [518f413d2f](https://linux-hardware.org/?probe=518f413d2f) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [a24d7423c4](https://linux-hardware.org/?probe=a24d7423c4) | Feb 11, 2023 |
| Dell          | Latitude E6400              | [8c489c529a](https://linux-hardware.org/?probe=8c489c529a) | Feb 11, 2023 |
| Acer          | TravelMate P253             | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| HONOR         | HLYL-WXX9                   | [9d916e8e03](https://linux-hardware.org/?probe=9d916e8e03) | Feb 10, 2023 |
| Acer          | Aspire 5720                 | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| Acer          | Predator G3-571             | [50fe192ea1](https://linux-hardware.org/?probe=50fe192ea1) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [8513e7eb92](https://linux-hardware.org/?probe=8513e7eb92) | Feb 09, 2023 |
| Positivo      | Smash2                      | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| Positivo      | Smash2                      | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [5c9ca6cd47](https://linux-hardware.org/?probe=5c9ca6cd47) | Feb 09, 2023 |
| HP            | Pavilion dv7                | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| Acer          | Aspire 5755G                | [0d0c6fe86c](https://linux-hardware.org/?probe=0d0c6fe86c) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [ae78404854](https://linux-hardware.org/?probe=ae78404854) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [b2c3e0fa85](https://linux-hardware.org/?probe=b2c3e0fa85) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Lenovo        | V570 1066EDG                | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| Acer          | Okinawa                     | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Sony          | VGN-Z31XN_B                 | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| TWC           | Unknown                     | [4ea2803396](https://linux-hardware.org/?probe=4ea2803396) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| MSI           | GF63 Thin 11UC              | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Intel         | Unknown                     | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Sony          | VPCEG36FX                   | [d760d9e79b](https://linux-hardware.org/?probe=d760d9e79b) | Feb 06, 2023 |
| Acer          | TravelMate P253             | [050d7b5d68](https://linux-hardware.org/?probe=050d7b5d68) | Feb 06, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f536be92d0](https://linux-hardware.org/?probe=f536be92d0) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Acer          | One S1002                   | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Insyde        | CherryTrail                 | [b3ad379bdc](https://linux-hardware.org/?probe=b3ad379bdc) | Feb 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| Dell          | Latitude D630               | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| Acer          | Aspire A517-51G             | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| Dell          | Inspiron 5537               | [5bfa4ad142](https://linux-hardware.org/?probe=5bfa4ad142) | Feb 02, 2023 |
| Intel         | Unknown                     | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| MSI           | GF63 Thin 11UC              | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| MSI           | Raider GE66 12UHS           | [75e83dae8b](https://linux-hardware.org/?probe=75e83dae8b) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | [d221bc6b8d](https://linux-hardware.org/?probe=d221bc6b8d) | Feb 01, 2023 |
| Dell          | Latitude E6540              | [156a047a82](https://linux-hardware.org/?probe=156a047a82) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | [a663152b7c](https://linux-hardware.org/?probe=a663152b7c) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | [ae3838cc5d](https://linux-hardware.org/?probe=ae3838cc5d) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | Pavilion Notebook           | [912213d849](https://linux-hardware.org/?probe=912213d849) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | [456415a23e](https://linux-hardware.org/?probe=456415a23e) | Jan 30, 2023 |
| Dell          | Latitude E6520              | [f042c5966b](https://linux-hardware.org/?probe=f042c5966b) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1F20... | [39b709296b](https://linux-hardware.org/?probe=39b709296b) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| Dell          | Precision 5530              | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | [62b104b3d2](https://linux-hardware.org/?probe=62b104b3d2) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | [b7cf9bee5c](https://linux-hardware.org/?probe=b7cf9bee5c) | Jan 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Dell          | Precision 5530              | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| Dell          | Vostro 1520                 | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| Dell          | Latitude E7470              | [4245585e75](https://linux-hardware.org/?probe=4245585e75) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| HP            | Notebook                    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [de7bee1cd6](https://linux-hardware.org/?probe=de7bee1cd6) | Jan 26, 2023 |
| Alienware     | M11xR3                      | [634b7f8eb0](https://linux-hardware.org/?probe=634b7f8eb0) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| HP            | 625                         | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Google        | Blorb                       | [adae28c837](https://linux-hardware.org/?probe=adae28c837) | Jan 25, 2023 |
| HP            | EliteBook Folio 9470m       | [5dfd026f77](https://linux-hardware.org/?probe=5dfd026f77) | Jan 25, 2023 |
| Lenovo        | Z51-70 80K6                 | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [61d7aa3ef9](https://linux-hardware.org/?probe=61d7aa3ef9) | Jan 25, 2023 |
| Google        | Kip                         | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| HP            | Laptop 15-dy2xxx            | [af9518a90a](https://linux-hardware.org/?probe=af9518a90a) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [db73b82761](https://linux-hardware.org/?probe=db73b82761) | Jan 24, 2023 |
| AXDIA Inte... | WINPAD V10                  | [dc93e9d9f0](https://linux-hardware.org/?probe=dc93e9d9f0) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [6fd520f670](https://linux-hardware.org/?probe=6fd520f670) | Jan 23, 2023 |
| Acer          | Aspire SW5-012              | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ProBook 440 G5              | [788d350490](https://linux-hardware.org/?probe=788d350490) | Jan 23, 2023 |
| Dell          | Latitude E7470              | [525bcdd915](https://linux-hardware.org/?probe=525bcdd915) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Acer          | Aspire A315-59              | [20b73bd156](https://linux-hardware.org/?probe=20b73bd156) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6d5ca0b2e3](https://linux-hardware.org/?probe=6d5ca0b2e3) | Jan 22, 2023 |
| Packard Be... | EasyNote TE69KB             | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| Dell          | Precision M6800             | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| HP            | 625                         | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| Lenovo        | V110-15IAP 80TG             | [1707a21fed](https://linux-hardware.org/?probe=1707a21fed) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| HP            | 625                         | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Dell          | Inspiron 1525               | [548d331968](https://linux-hardware.org/?probe=548d331968) | Jan 21, 2023 |
| ASUSTek       | X453MA                      | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| Timi          | Mi Notebook Pro             | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| ASUSTek       | G74Sx                       | [f3af245bf8](https://linux-hardware.org/?probe=f3af245bf8) | Jan 20, 2023 |
| Acer          | Aspire A317-33              | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| ASUSTek       | A6U                         | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| HP            | ProBook 4740s               | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Acer          | Aspire E5-774G              | [f3ab78c392](https://linux-hardware.org/?probe=f3ab78c392) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | [4908236396](https://linux-hardware.org/?probe=4908236396) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | [9e17ffeecc](https://linux-hardware.org/?probe=9e17ffeecc) | Jan 19, 2023 |
| Lenovo        | V110-15IAP 80TG             | [cfe9a9d924](https://linux-hardware.org/?probe=cfe9a9d924) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | 15                          | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| Google        | Kip                         | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | Pavilion dv7                | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [473ae331ec](https://linux-hardware.org/?probe=473ae331ec) | Jan 16, 2023 |
| Wortmann      | Mobile 1524                 | [17fc7e2f75](https://linux-hardware.org/?probe=17fc7e2f75) | Jan 16, 2023 |
| HP            | Pavilion 17                 | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| Lenovo        | G560 0679                   | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| Sony          | VGN-SR16GN_B                | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [331b5e3efa](https://linux-hardware.org/?probe=331b5e3efa) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [19531b68b1](https://linux-hardware.org/?probe=19531b68b1) | Jan 14, 2023 |
| HP            | EliteBook 745 G5            | [941c62872e](https://linux-hardware.org/?probe=941c62872e) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [ddf679df3a](https://linux-hardware.org/?probe=ddf679df3a) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| ASUSTek       | K93SV                       | [250b4a09a0](https://linux-hardware.org/?probe=250b4a09a0) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| HP            | Laptop 14-bw0xx             | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| Acer          | Aspire 2920                 | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Samsung       | R520/R522/R620              | [78eb96d148](https://linux-hardware.org/?probe=78eb96d148) | Jan 11, 2023 |
| Samsung       | R520/R522/R620              | [9dfcb68d9a](https://linux-hardware.org/?probe=9dfcb68d9a) | Jan 11, 2023 |
| HP            | Notebook                    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| Dell          | Inspiron 3583               | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Dell          | Inspiron 15-3567            | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| HP            | Pavilion dv6                | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| Dell          | Latitude E6510              | [28cceb82e3](https://linux-hardware.org/?probe=28cceb82e3) | Jan 09, 2023 |
| Acer          | Aspire A315-53              | [a8f14a8a8e](https://linux-hardware.org/?probe=a8f14a8a8e) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5bd32eb6f6](https://linux-hardware.org/?probe=5bd32eb6f6) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [88ba7d805e](https://linux-hardware.org/?probe=88ba7d805e) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [b5b4c3f6ef](https://linux-hardware.org/?probe=b5b4c3f6ef) | Jan 08, 2023 |
| MSI           | CR62 6M                     | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| Dell          | Inspiron 5559               | [4c680e9948](https://linux-hardware.org/?probe=4c680e9948) | Jan 07, 2023 |
| HP            | Laptop 17-cp1xxx            | [d699356fd1](https://linux-hardware.org/?probe=d699356fd1) | Jan 07, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [cc8d4f6e6d](https://linux-hardware.org/?probe=cc8d4f6e6d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [393397e25c](https://linux-hardware.org/?probe=393397e25c) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [76f452827f](https://linux-hardware.org/?probe=76f452827f) | Jan 06, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [6148bc3313](https://linux-hardware.org/?probe=6148bc3313) | Jan 06, 2023 |
| Multilaser    | PC024                       | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Multilaser    | PC024                       | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| Dell          | Precision M90               | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | ProBook 4540s               | [6e2638a12e](https://linux-hardware.org/?probe=6e2638a12e) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Acer          | Aspire V3-772G              | [4ec59dca55](https://linux-hardware.org/?probe=4ec59dca55) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| HP            | EliteBook Folio 9470m       | [309e449325](https://linux-hardware.org/?probe=309e449325) | Jan 03, 2023 |
| HP            | Pavilion dv7                | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Apple         | MacBookPro12,1              | [ce3dc1998f](https://linux-hardware.org/?probe=ce3dc1998f) | Jan 02, 2023 |
| HP            | EliteBook 2570p             | [fcf5d132a5](https://linux-hardware.org/?probe=fcf5d132a5) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| Dell          | Latitude E5440              | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| HP            | Pavilion dv6                | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0360bb01d0](https://linux-hardware.org/?probe=0360bb01d0) | Jan 01, 2023 |
| Dell          | Latitude E5500              | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| HP            | Pavilion dv6                | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
| Dell          | Latitude E6540              | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | Latitude 7490               | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Zorin 16 | 1864      | 62.3%   |
| Zorin 15 | 1014      | 33.89%  |
| Zorin 12 | 114       | 3.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Zorin | 2981      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 133       | 3.9%    |
| 5.11.0-38-generic | 101       | 2.96%   |
| 5.11.0-27-generic | 94        | 2.76%   |
| 5.15.0-52-generic | 93        | 2.73%   |
| 5.15.0-58-generic | 90        | 2.64%   |
| 5.15.0-46-generic | 89        | 2.61%   |
| 5.13.0-30-generic | 74        | 2.17%   |
| 5.3.0-40-generic  | 67        | 1.97%   |
| 5.11.0-37-generic | 67        | 1.97%   |
| 5.11.0-40-generic | 65        | 1.91%   |
| 5.15.0-69-generic | 63        | 1.85%   |
| 5.15.0-67-generic | 63        | 1.85%   |
| 5.11.0-41-generic | 63        | 1.85%   |
| 5.4.0-42-generic  | 61        | 1.79%   |
| 5.13.0-39-generic | 60        | 1.76%   |
| 5.11.0-34-generic | 57        | 1.67%   |
| 5.15.0-60-generic | 56        | 1.64%   |
| 5.11.0-43-generic | 56        | 1.64%   |
| 5.15.0-76-generic | 54        | 1.58%   |
| 5.3.0-46-generic  | 53        | 1.56%   |
| 5.15.0-78-generic | 52        | 1.53%   |
| 5.15.0-71-generic | 51        | 1.5%    |
| 5.15.0-48-generic | 51        | 1.5%    |
| 5.13.0-44-generic | 48        | 1.41%   |
| 5.3.0-51-generic  | 47        | 1.38%   |
| 5.0.0-37-generic  | 47        | 1.38%   |
| 5.13.0-40-generic | 46        | 1.35%   |
| 5.15.0-53-generic | 43        | 1.26%   |
| 5.13.0-35-generic | 40        | 1.17%   |
| 5.4.0-47-generic  | 38        | 1.12%   |
| 5.3.0-53-generic  | 37        | 1.09%   |
| 5.13.0-28-generic | 37        | 1.09%   |
| 5.3.0-42-generic  | 36        | 1.06%   |
| 5.4.0-45-generic  | 35        | 1.03%   |
| 5.15.0-41-generic | 35        | 1.03%   |
| 5.15.0-73-generic | 34        | 1%      |
| 5.15.0-79-generic | 33        | 0.97%   |
| 5.4.0-58-generic  | 32        | 0.94%   |
| 5.4.0-48-generic  | 31        | 0.91%   |
| 5.15.0-72-generic | 31        | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 937       | 30.14%  |
| 5.4.0   | 592       | 19.04%  |
| 5.11.0  | 550       | 17.69%  |
| 5.13.0  | 406       | 13.06%  |
| 5.3.0   | 312       | 10.04%  |
| 4.15.0  | 110       | 3.54%   |
| 5.0.0   | 89        | 2.86%   |
| 4.18.0  | 45        | 1.45%   |
| 5.8.0   | 23        | 0.74%   |
| 5.14.0  | 8         | 0.26%   |
| 4.4.0   | 4         | 0.13%   |
| 5.6.0   | 2         | 0.06%   |
| 5.18.15 | 2         | 0.06%   |
| 5.16.0  | 2         | 0.06%   |
| 5.10.0  | 2         | 0.06%   |
| 6.3.2   | 1         | 0.03%   |
| 6.3.1   | 1         | 0.03%   |
| 6.2.16  | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.0.9   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.9.12  | 1         | 0.03%   |
| 5.9.0   | 1         | 0.03%   |
| 5.7.1   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.4.1   | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.12 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.19.0  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.16.12 | 1         | 0.03%   |
| 5.15.49 | 1         | 0.03%   |
| 5.15.24 | 1         | 0.03%   |
| 5.13.18 | 1         | 0.03%   |
| 5.10.35 | 1         | 0.03%   |
| 5.10.16 | 1         | 0.03%   |
| 4.13.0  | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 939       | 30.2%   |
| 5.4     | 594       | 19.11%  |
| 5.11    | 550       | 17.69%  |
| 5.13    | 407       | 13.09%  |
| 5.3     | 312       | 10.04%  |
| 4.15    | 110       | 3.54%   |
| 5.0     | 89        | 2.86%   |
| 4.18    | 45        | 1.45%   |
| 5.8     | 23        | 0.74%   |
| 5.14    | 8         | 0.26%   |
| 5.19    | 5         | 0.16%   |
| 5.10    | 4         | 0.13%   |
| 4.4     | 4         | 0.13%   |
| 6.0     | 3         | 0.1%    |
| 5.18    | 3         | 0.1%    |
| 5.16    | 3         | 0.1%    |
| 6.3     | 2         | 0.06%   |
| 6.2     | 2         | 0.06%   |
| 5.9     | 2         | 0.06%   |
| 5.6     | 2         | 0.06%   |
| 5.7     | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2703      | 90.58%  |
| i686   | 281       | 9.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 2111      | 70.04%  |
| XFCE       | 709       | 23.52%  |
| Unknown    | 172       | 5.71%   |
| X-Cinnamon | 7         | 0.23%   |
| Unity      | 3         | 0.1%    |
| KDE5       | 3         | 0.1%    |
| KDE        | 3         | 0.1%    |
| i3         | 2         | 0.07%   |
| Budgie     | 2         | 0.07%   |
| LXDE       | 1         | 0.03%   |
| Cinnamon   | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2847      | 94.62%  |
| Unknown | 107       | 3.56%   |
| Wayland | 54        | 1.79%   |
| Tty     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2359      | 77.98%  |
| GDM3    | 237       | 7.83%   |
| GDM     | 229       | 7.57%   |
| LightDM | 191       | 6.31%   |
| TDM     | 6         | 0.2%    |
| SDDM    | 2         | 0.07%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1052      | 34.99%  |
| de_DE   | 220       | 7.32%   |
| pt_BR   | 192       | 6.39%   |
| en_GB   | 175       | 5.82%   |
| Unknown | 127       | 4.22%   |
| it_IT   | 117       | 3.89%   |
| es_ES   | 99        | 3.29%   |
| fr_FR   | 96        | 3.19%   |
| en_IN   | 95        | 3.16%   |
| en_CA   | 86        | 2.86%   |
| pl_PL   | 73        | 2.43%   |
| en_AU   | 47        | 1.56%   |
| es_MX   | 43        | 1.43%   |
| pt_PT   | 42        | 1.4%    |
| nl_NL   | 42        | 1.4%    |
| ru_RU   | 37        | 1.23%   |
| cs_CZ   | 36        | 1.2%    |
| en_ZA   | 31        | 1.03%   |
| es_AR   | 30        | 1%      |
| tr_TR   | 23        | 0.76%   |
| sv_SE   | 22        | 0.73%   |
| C       | 20        | 0.67%   |
| es_CL   | 19        | 0.63%   |
| en_NZ   | 18        | 0.6%    |
| de_AT   | 18        | 0.6%    |
| hu_HU   | 16        | 0.53%   |
| de_CH   | 15        | 0.5%    |
| ja_JP   | 13        | 0.43%   |
| fr_BE   | 13        | 0.43%   |
| nl_BE   | 12        | 0.4%    |
| fr_CA   | 12        | 0.4%    |
| el_GR   | 11        | 0.37%   |
| es_CO   | 10        | 0.33%   |
| en_PH   | 9         | 0.3%    |
| da_DK   | 9         | 0.3%    |
| ro_RO   | 8         | 0.27%   |
| ru_UA   | 7         | 0.23%   |
| hr_HR   | 7         | 0.23%   |
| es_PE   | 7         | 0.23%   |
| bg_BG   | 6         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1556      | 51.56%  |
| EFI  | 1462      | 48.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2780      | 92.67%  |
| Overlay | 65        | 2.17%   |
| Tmpfs   | 55        | 1.83%   |
| Zfs     | 30        | 1%      |
| Btrfs   | 25        | 0.83%   |
| Ext2    | 21        | 0.7%    |
| Unknown | 17        | 0.57%   |
| Xfs     | 4         | 0.13%   |
| Ext3    | 3         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2585      | 85.74%  |
| GPT     | 324       | 10.75%  |
| MBR     | 106       | 3.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2845      | 94.8%   |
| Yes       | 156       | 5.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2527      | 84.29%  |
| Yes       | 471       | 15.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 681       | 22.84%  |
| Lenovo              | 468       | 15.7%   |
| Dell                | 459       | 15.4%   |
| ASUSTek Computer    | 285       | 9.56%   |
| Acer                | 237       | 7.95%   |
| Toshiba             | 161       | 5.4%    |
| Apple               | 83        | 2.78%   |
| Samsung Electronics | 59        | 1.98%   |
| Sony                | 51        | 1.71%   |
| MSI                 | 44        | 1.48%   |
| Google              | 32        | 1.07%   |
| Unknown             | 30        | 1.01%   |
| Packard Bell        | 29        | 0.97%   |
| Positivo            | 23        | 0.77%   |
| Fujitsu Siemens     | 20        | 0.67%   |
| HUAWEI              | 19        | 0.64%   |
| Fujitsu             | 18        | 0.6%    |
| Medion              | 15        | 0.5%    |
| Notebook            | 12        | 0.4%    |
| Alienware           | 11        | 0.37%   |
| Chuwi               | 10        | 0.34%   |
| Panasonic           | 9         | 0.3%    |
| AMI                 | 9         | 0.3%    |
| Gateway             | 8         | 0.27%   |
| eMachines           | 8         | 0.27%   |
| Multilaser          | 7         | 0.23%   |
| LG Electronics      | 6         | 0.2%    |
| Itautec             | 6         | 0.2%    |
| Insyde              | 6         | 0.2%    |
| GPU Company         | 6         | 0.2%    |
| Digibras            | 6         | 0.2%    |
| Semp Toshiba        | 5         | 0.17%   |
| NEC Computers       | 5         | 0.17%   |
| Ematic              | 5         | 0.17%   |
| Clevo               | 5         | 0.17%   |
| Thomson             | 4         | 0.13%   |
| Razer               | 4         | 0.13%   |
| Quanta              | 4         | 0.13%   |
| Microtech           | 4         | 0.13%   |
| Jumper              | 4         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Unknown                   | 59        | 1.98%   |
| HP Notebook               | 30        | 1.01%   |
| HP Pavilion Notebook      | 17        | 0.57%   |
| HP Pavilion dv6           | 16        | 0.54%   |
| HP 15                     | 16        | 0.54%   |
| HP Pavilion dv7           | 14        | 0.47%   |
| HP Pavilion 15            | 12        | 0.4%    |
| Toshiba Satellite C660    | 10        | 0.34%   |
| Dell Latitude E6400       | 10        | 0.34%   |
| Dell Latitude D630        | 10        | 0.34%   |
| Dell Inspiron 1545        | 10        | 0.34%   |
| HP Pavilion g6            | 9         | 0.3%    |
| Apple MacBookPro8,1       | 9         | 0.3%    |
| HP Pavilion g7            | 8         | 0.27%   |
| HP Laptop 15-bw0xx        | 8         | 0.27%   |
| Dell Latitude E6540       | 8         | 0.27%   |
| Dell Inspiron 15-3567     | 8         | 0.27%   |
| HP Pavilion dv6700        | 7         | 0.23%   |
| HP EliteBook 8460p        | 7         | 0.23%   |
| HP EliteBook 840 G1       | 7         | 0.23%   |
| Dell Latitude E6410       | 7         | 0.23%   |
| Dell Inspiron 3521        | 7         | 0.23%   |
| Dell Inspiron 1525        | 7         | 0.23%   |
| Toshiba Satellite A100    | 6         | 0.2%    |
| HP ProBook 640 G1         | 6         | 0.2%    |
| HP ProBook 4540s          | 6         | 0.2%    |
| HP Pavilion 17            | 6         | 0.2%    |
| HP Laptop 15-db0xxx       | 6         | 0.2%    |
| Dell Latitude E6430       | 6         | 0.2%    |
| Dell Latitude E5470       | 6         | 0.2%    |
| Dell Inspiron 7520        | 6         | 0.2%    |
| Apple MacBookPro12,1      | 6         | 0.2%    |
| Positivo Mobile           | 5         | 0.17%   |
| HP Stream Notebook        | 5         | 0.17%   |
| HP Stream Laptop 14-ax0XX | 5         | 0.17%   |
| HP ProBook 4530s          | 5         | 0.17%   |
| HP Pavilion dv5           | 5         | 0.17%   |
| HP EliteBook 2570p        | 5         | 0.17%   |
| HP Compaq Presario CQ60   | 5         | 0.17%   |
| HP Compaq 6730s           | 5         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 192       | 6.44%   |
| HP Pavilion           | 174       | 5.84%   |
| Dell Latitude         | 172       | 5.77%   |
| Dell Inspiron         | 168       | 5.64%   |
| Acer Aspire           | 165       | 5.54%   |
| Lenovo IdeaPad        | 145       | 4.86%   |
| Toshiba Satellite     | 137       | 4.6%    |
| HP EliteBook          | 88        | 2.95%   |
| HP ProBook            | 74        | 2.48%   |
| HP Laptop             | 62        | 2.08%   |
| Unknown               | 59        | 1.98%   |
| HP Compaq             | 53        | 1.78%   |
| ASUS VivoBook         | 40        | 1.34%   |
| Dell Vostro           | 34        | 1.14%   |
| HP Notebook           | 30        | 1.01%   |
| Packard Bell EasyNote | 27        | 0.91%   |
| Dell XPS              | 24        | 0.81%   |
| HP Stream             | 23        | 0.77%   |
| HP ENVY               | 23        | 0.77%   |
| Dell Precision        | 21        | 0.7%    |
| HP 15                 | 18        | 0.6%    |
| ASUS ZenBook          | 17        | 0.57%   |
| HP Presario           | 16        | 0.54%   |
| ASUS ROG              | 16        | 0.54%   |
| Lenovo Yoga           | 14        | 0.47%   |
| HP 255                | 14        | 0.47%   |
| Apple MacBookPro8     | 13        | 0.44%   |
| HP OMEN               | 12        | 0.4%    |
| Fujitsu LIFEBOOK      | 12        | 0.4%    |
| Dell Studio           | 12        | 0.4%    |
| Lenovo Legion         | 11        | 0.37%   |
| HP ZBook              | 11        | 0.37%   |
| Fujitsu Siemens AMILO | 11        | 0.37%   |
| Acer TravelMate       | 11        | 0.37%   |
| Dell System           | 10        | 0.34%   |
| ASUS ASUS             | 10        | 0.34%   |
| Apple MacBookPro11    | 10        | 0.34%   |
| Toshiba PORTEGE       | 9         | 0.3%    |
| Acer Swift            | 9         | 0.3%    |
| HP Mini               | 8         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 272       | 9.12%   |
| 2012    | 256       | 8.59%   |
| 2013    | 239       | 8.02%   |
| 2010    | 214       | 7.18%   |
| 2008    | 202       | 6.78%   |
| 2018    | 187       | 6.27%   |
| 2014    | 186       | 6.24%   |
| 2019    | 178       | 5.97%   |
| 2017    | 173       | 5.8%    |
| 2021    | 163       | 5.47%   |
| 2015    | 163       | 5.47%   |
| 2016    | 152       | 5.1%    |
| 2020    | 148       | 4.96%   |
| 2007    | 147       | 4.93%   |
| 2009    | 141       | 4.73%   |
| 2006    | 55        | 1.85%   |
| 2022    | 45        | 1.51%   |
| 2005    | 37        | 1.24%   |
| 2023    | 14        | 0.47%   |
| Unknown | 6         | 0.2%    |
| 2003    | 2         | 0.07%   |
| 2004    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2981      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2635      | 87.83%  |
| Enabled  | 365       | 12.17%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2944      | 98.76%  |
| Yes  | 37        | 1.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 885       | 29.45%  |
| 4.01-8.0    | 852       | 28.35%  |
| 8.01-16.0   | 361       | 12.01%  |
| 1.01-2.0    | 325       | 10.82%  |
| 16.01-24.0  | 290       | 9.65%   |
| 2.01-3.0    | 111       | 3.69%   |
| 32.01-64.0  | 84        | 2.8%    |
| 0.51-1.0    | 71        | 2.36%   |
| 64.01-256.0 | 14        | 0.47%   |
| 24.01-32.0  | 12        | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1386      | 42.98%  |
| 2.01-3.0   | 900       | 27.91%  |
| 3.01-4.0   | 364       | 11.29%  |
| 0.51-1.0   | 277       | 8.59%   |
| 4.01-8.0   | 239       | 7.41%   |
| 8.01-16.0  | 30        | 0.93%   |
| 0.01-0.5   | 25        | 0.78%   |
| 24.01-32.0 | 2         | 0.06%   |
| 16.01-24.0 | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2322      | 76.68%  |
| 2      | 619       | 20.44%  |
| 3      | 62        | 2.05%   |
| 0      | 12        | 0.4%    |
| 4      | 8         | 0.26%   |
| 5      | 3         | 0.1%    |
| 8      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1540      | 51.44%  |
| Yes       | 1454      | 48.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2449      | 81.96%  |
| No        | 539       | 18.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2886      | 96.75%  |
| No        | 97        | 3.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1943      | 64.47%  |
| No        | 1071      | 35.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 609       | 20.35%  |
| Germany      | 258       | 8.62%   |
| Brazil       | 221       | 7.38%   |
| UK           | 170       | 5.68%   |
| Italy        | 123       | 4.11%   |
| Canada       | 112       | 3.74%   |
| Spain        | 104       | 3.47%   |
| India        | 102       | 3.41%   |
| France       | 95        | 3.17%   |
| Netherlands  | 77        | 2.57%   |
| Poland       | 71        | 2.37%   |
| Mexico       | 66        | 2.21%   |
| Australia    | 53        | 1.77%   |
| Portugal     | 48        | 1.6%    |
| Czechia      | 41        | 1.37%   |
| Sweden       | 40        | 1.34%   |
| Argentina    | 39        | 1.3%    |
| Russia       | 38        | 1.27%   |
| South Africa | 37        | 1.24%   |
| Belgium      | 36        | 1.2%    |
| Austria      | 34        | 1.14%   |
| Romania      | 33        | 1.1%    |
| Turkey       | 31        | 1.04%   |
| Switzerland  | 29        | 0.97%   |
| Indonesia    | 28        | 0.94%   |
| Greece       | 24        | 0.8%    |
| New Zealand  | 21        | 0.7%    |
| Japan        | 21        | 0.7%    |
| Norway       | 19        | 0.63%   |
| Chile        | 19        | 0.63%   |
| Hungary      | 18        | 0.6%    |
| Colombia     | 18        | 0.6%    |
| Egypt        | 16        | 0.53%   |
| Serbia       | 15        | 0.5%    |
| Bulgaria     | 14        | 0.47%   |
| Denmark      | 13        | 0.43%   |
| Ukraine      | 12        | 0.4%    |
| Philippines  | 12        | 0.4%    |
| Finland      | 11        | 0.37%   |
| Pakistan     | 10        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 24        | 0.77%   |
| Berlin         | 20        | 0.64%   |
| Vienna         | 19        | 0.61%   |
| Sydney         | 19        | 0.61%   |
| Madrid         | 18        | 0.57%   |
| Rome           | 16        | 0.51%   |
| Munich         | 16        | 0.51%   |
| Johannesburg   | 15        | 0.48%   |
| Athens         | 14        | 0.45%   |
| New York       | 13        | 0.42%   |
| Montreal       | 13        | 0.42%   |
| Milan          | 13        | 0.42%   |
| Istanbul       | 13        | 0.42%   |
| Rio de Janeiro | 12        | 0.38%   |
| Paris          | 12        | 0.38%   |
| Mexico City    | 12        | 0.38%   |
| Auckland       | 12        | 0.38%   |
| Prague         | 11        | 0.35%   |
| Moscow         | 11        | 0.35%   |
| Jakarta        | 11        | 0.35%   |
| Hamburg        | 11        | 0.35%   |
| Dallas         | 11        | 0.35%   |
| Cairo          | 11        | 0.35%   |
| Toronto        | 10        | 0.32%   |
| Stockholm      | 10        | 0.32%   |
| Bucharest      | 10        | 0.32%   |
| Bengaluru      | 10        | 0.32%   |
| Amsterdam      | 10        | 0.32%   |
| Warsaw         | 9         | 0.29%   |
| Stuttgart      | 9         | 0.29%   |
| Seattle        | 9         | 0.29%   |
| Nairobi        | 9         | 0.29%   |
| Krakow         | 9         | 0.29%   |
| Kolkata        | 9         | 0.29%   |
| Denver         | 9         | 0.29%   |
| Delhi          | 9         | 0.29%   |
| Buenos Aires   | 9         | 0.29%   |
| Belgrade       | 9         | 0.29%   |
| Barcelona      | 9         | 0.29%   |
| Valencia       | 8         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 446       | 547    | 12.81%  |
| WDC                       | 426       | 518    | 12.23%  |
| Samsung Electronics       | 393       | 532    | 11.29%  |
| Toshiba                   | 351       | 399    | 10.08%  |
| Unknown                   | 304       | 415    | 8.73%   |
| SanDisk                   | 198       | 234    | 5.69%   |
| Hitachi                   | 171       | 199    | 4.91%   |
| Kingston                  | 156       | 191    | 4.48%   |
| Crucial                   | 115       | 138    | 3.3%    |
| HGST                      | 105       | 126    | 3.02%   |
| Intel                     | 85        | 107    | 2.44%   |
| SK hynix                  | 75        | 88     | 2.15%   |
| Micron Technology         | 59        | 70     | 1.69%   |
| Fujitsu                   | 44        | 46     | 1.26%   |
| A-DATA Technology         | 43        | 48     | 1.23%   |
| China                     | 42        | 52     | 1.21%   |
| Apple                     | 36        | 42     | 1.03%   |
| Intenso                   | 25        | 26     | 0.72%   |
| KIOXIA                    | 24        | 29     | 0.69%   |
| PNY                       | 21        | 25     | 0.6%    |
| SPCC                      | 19        | 24     | 0.55%   |
| Netac                     | 16        | 16     | 0.46%   |
| LITEONIT                  | 16        | 19     | 0.46%   |
| LITEON                    | 16        | 20     | 0.46%   |
| Transcend                 | 15        | 20     | 0.43%   |
| Patriot                   | 15        | 19     | 0.43%   |
| Unknown                   | 15        | 17     | 0.43%   |
| Phison                    | 14        | 17     | 0.4%    |
| GOODRAM                   | 13        | 14     | 0.37%   |
| Team                      | 11        | 12     | 0.32%   |
| JMicron Technology        | 10        | 11     | 0.29%   |
| OCZ                       | 9         | 10     | 0.26%   |
| Silicon Motion            | 8         | 8      | 0.23%   |
| SABRENT                   | 8         | 9      | 0.23%   |
| Phison Electronics        | 6         | 6      | 0.17%   |
| Hewlett-Packard           | 6         | 6      | 0.17%   |
| ASMT                      | 6         | 6      | 0.17%   |
| Plextor                   | 5         | 5      | 0.14%   |
| Lite-On                   | 5         | 7      | 0.14%   |
| Micron/Crucial Technology | 4         | 6      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 113       | 3.13%   |
| Unknown MMC Card  64GB                              | 77        | 2.13%   |
| Seagate ST1000LM035-1RK172 1TB                      | 49        | 1.36%   |
| Toshiba MQ01ABF050 500GB                            | 48        | 1.33%   |
| Toshiba MQ01ABD100 1TB                              | 40        | 1.11%   |
| Kingston SA400S37240G 240GB SSD                     | 39        | 1.08%   |
| Seagate ST500LT012-1DG142 500GB                     | 38        | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 34        | 0.94%   |
| Unknown MMC Card  128GB                             | 32        | 0.89%   |
| Toshiba MQ04ABF100 1TB                              | 32        | 0.89%   |
| Unknown MMC Card  16GB                              | 27        | 0.75%   |
| Seagate ST9500325AS 500GB                           | 27        | 0.75%   |
| Kingston SA400S37480G 480GB SSD                     | 27        | 0.75%   |
| Samsung NVMe SSD Drive 512GB                        | 24        | 0.66%   |
| Kingston SA400S37120G 120GB SSD                     | 22        | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 21        | 0.58%   |
| Crucial CT240BX500SSD1 240GB                        | 21        | 0.58%   |
| SanDisk NVMe SSD Drive 256GB                        | 20        | 0.55%   |
| HGST HTS725050A7E630 500GB                          | 20        | 0.55%   |
| HGST HTS721010A9E630 1TB                            | 20        | 0.55%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 19        | 0.53%   |
| HGST HTS541010A9E680 1TB                            | 18        | 0.5%    |
| Intel NVMe SSD Drive 512GB                          | 17        | 0.47%   |
| Hitachi HTS545032B9A300 320GB                       | 17        | 0.47%   |
| Crucial CT500MX500SSD1 500GB                        | 17        | 0.47%   |
| Seagate Expansion 2TB                               | 16        | 0.44%   |
| Samsung SSD 850 EVO 500GB                           | 16        | 0.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 15        | 0.41%   |
| HGST HTS545050A7E680 500GB                          | 15        | 0.41%   |
| Unknown                                             | 15        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.39%   |
| Samsung SSD 860 EVO 500GB                           | 14        | 0.39%   |
| Unknown SD/MMC/MS PRO 1GB                           | 13        | 0.36%   |
| Samsung SSD 860 EVO 250GB                           | 13        | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 12        | 0.33%   |
| Samsung HM160HI 160GB                               | 12        | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 11        | 0.3%    |
| WDC WD10JPVX-60JC3T0 1TB                            | 11        | 0.3%    |
| Toshiba MQ01ABD075 752GB                            | 11        | 0.3%    |
| Seagate ST9320325AS 320GB                           | 11        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 441       | 538    | 29.26%  |
| WDC                 | 364       | 434    | 24.15%  |
| Toshiba             | 298       | 335    | 19.77%  |
| Hitachi             | 171       | 199    | 11.35%  |
| HGST                | 105       | 126    | 6.97%   |
| Samsung Electronics | 46        | 51     | 3.05%   |
| Fujitsu             | 44        | 46     | 2.92%   |
| Unknown             | 13        | 19     | 0.86%   |
| SABRENT             | 8         | 9      | 0.53%   |
| Apple               | 5         | 5      | 0.33%   |
| IBM/Hitachi         | 4         | 5      | 0.27%   |
| JMicron Technology  | 2         | 2      | 0.13%   |
| USB3.0              | 1         | 1      | 0.07%   |
| SSK                 | 1         | 1      | 0.07%   |
| Pioneer             | 1         | 1      | 0.07%   |
| LaCie               | 1         | 1      | 0.07%   |
| KESU                | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 214       | 297    | 18.95%  |
| Kingston            | 137       | 169    | 12.13%  |
| Crucial             | 113       | 134    | 10.01%  |
| SanDisk             | 112       | 132    | 9.92%   |
| WDC                 | 47        | 61     | 4.16%   |
| China               | 41        | 51     | 3.63%   |
| Intel               | 39        | 45     | 3.45%   |
| A-DATA Technology   | 38        | 43     | 3.37%   |
| Toshiba             | 32        | 36     | 2.83%   |
| SK hynix            | 27        | 31     | 2.39%   |
| Micron Technology   | 27        | 31     | 2.39%   |
| Apple               | 26        | 30     | 2.3%    |
| PNY                 | 21        | 25     | 1.86%   |
| SPCC                | 18        | 23     | 1.59%   |
| Intenso             | 17        | 17     | 1.51%   |
| Netac               | 16        | 16     | 1.42%   |
| LITEONIT            | 16        | 19     | 1.42%   |
| LITEON              | 16        | 20     | 1.42%   |
| Transcend           | 15        | 20     | 1.33%   |
| Patriot             | 15        | 19     | 1.33%   |
| GOODRAM             | 12        | 13     | 1.06%   |
| Team                | 11        | 12     | 0.97%   |
| OCZ                 | 9         | 10     | 0.8%    |
| JMicron Technology  | 6         | 7      | 0.53%   |
| ASMT                | 6         | 6      | 0.53%   |
| Plextor             | 5         | 5      | 0.44%   |
| Unknown             | 5         | 7      | 0.44%   |
| KingSpec            | 4         | 4      | 0.35%   |
| Hewlett-Packard     | 4         | 4      | 0.35%   |
| BHT                 | 4         | 5      | 0.35%   |
| Verbatim            | 3         | 3      | 0.27%   |
| Mushkin             | 3         | 3      | 0.27%   |
| Lexar               | 3         | 3      | 0.27%   |
| Apacer              | 3         | 3      | 0.27%   |
| Vaseky              | 2         | 3      | 0.18%   |
| TO Exter            | 2         | 3      | 0.18%   |
| Teclast             | 2         | 2      | 0.18%   |
| TCSUNBOW            | 2         | 2      | 0.18%   |
| Phison              | 2         | 3      | 0.18%   |
| Leven               | 2         | 2      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1472      | 1775   | 43.63%  |
| SSD     | 1072      | 1376   | 31.77%  |
| NVMe    | 476       | 624    | 14.11%  |
| MMC     | 304       | 411    | 9.01%   |
| Unknown | 50        | 55     | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2384      | 3066   | 73.08%  |
| NVMe | 476       | 624    | 14.59%  |
| MMC  | 304       | 411    | 9.32%   |
| SAS  | 98        | 140    | 3%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1880      | 2329   | 74.28%  |
| 0.51-1.0   | 582       | 722    | 22.99%  |
| 1.01-2.0   | 61        | 85     | 2.41%   |
| 4.01-10.0  | 5         | 9      | 0.2%    |
| 3.01-4.0   | 3         | 6      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1096      | 35.7%   |
| 251-500        | 785       | 25.57%  |
| 501-1000       | 378       | 12.31%  |
| 51-100         | 336       | 10.94%  |
| 21-50          | 207       | 6.74%   |
| 1001-2000      | 97        | 3.16%   |
| 1-20           | 94        | 3.06%   |
| Unknown        | 28        | 0.91%   |
| More than 3000 | 26        | 0.85%   |
| 2001-3000      | 23        | 0.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1589      | 49.83%  |
| 21-50          | 766       | 24.02%  |
| 51-100         | 324       | 10.16%  |
| 101-250        | 278       | 8.72%   |
| 251-500        | 122       | 3.83%   |
| 501-1000       | 51        | 1.6%    |
| Unknown        | 28        | 0.88%   |
| 1001-2000      | 16        | 0.5%    |
| More than 3000 | 11        | 0.34%   |
| 2001-3000      | 4         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                        | 3         | 3      | 4.35%   |
| Toshiba MQ02ABD100H 1TB                          | 2         | 2      | 2.9%    |
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 2.9%    |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 2      | 2.9%    |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 2.9%    |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 2.9%    |
| Seagate ST1000LM035-1RK172 1TB                   | 2         | 2      | 2.9%    |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 2.9%    |
| HGST HTS545050A7E380 500GB                       | 2         | 3      | 2.9%    |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 1.45%   |
| WDC WD5000LPVX-75V0TT0 500GB                     | 1         | 1      | 1.45%   |
| WDC WD5000BEVT-24A0RT0 500GB                     | 1         | 1      | 1.45%   |
| WDC WD3200BPVT-55ZEST0 320GB                     | 1         | 1      | 1.45%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.45%   |
| WDC WD10SPZX-75Z10T2 1TB                         | 1         | 1      | 1.45%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 1.45%   |
| WDC WD10JPVT-55A1YT0 1TB                         | 1         | 1      | 1.45%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 1         | 1      | 1.45%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD         | 1         | 1      | 1.45%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.45%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 1.45%   |
| Toshiba MK5061GSY 500GB                          | 1         | 1      | 1.45%   |
| Toshiba MK2046GSX 200GB                          | 1         | 1      | 1.45%   |
| Teclast 128GB NS550-2242 SSD                     | 1         | 1      | 1.45%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.45%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 1.45%   |
| Seagate ST9320310AS 320GB                        | 1         | 1      | 1.45%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 1.45%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 1.45%   |
| Seagate ST9160411ASG 160GB                       | 1         | 1      | 1.45%   |
| Seagate ST9160314AS 160GB                        | 1         | 1      | 1.45%   |
| Seagate ST9120822AS 120GB                        | 1         | 1      | 1.45%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 1.45%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.45%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 1.45%   |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 1.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 1.45%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 1.45%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD    | 1         | 1      | 1.45%   |
| Samsung Electronics HM160JI 160GB                | 1         | 1      | 1.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 22     | 31.88%  |
| Toshiba             | 10        | 10     | 14.49%  |
| WDC                 | 8         | 8      | 11.59%  |
| HGST                | 7         | 8      | 10.14%  |
| Hitachi             | 5         | 5      | 7.25%   |
| Samsung Electronics | 4         | 4      | 5.8%    |
| Kingston            | 3         | 3      | 4.35%   |
| SK hynix            | 2         | 2      | 2.9%    |
| Teclast             | 1         | 1      | 1.45%   |
| POLION              | 1         | 1      | 1.45%   |
| Micron Technology   | 1         | 1      | 1.45%   |
| LITEONIT            | 1         | 1      | 1.45%   |
| Intel               | 1         | 1      | 1.45%   |
| Hewlett-Packard     | 1         | 1      | 1.45%   |
| Drevo               | 1         | 1      | 1.45%   |
| Unknown             | 1         | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 22     | 42.31%  |
| WDC                 | 8         | 8      | 15.38%  |
| Toshiba             | 8         | 8      | 15.38%  |
| HGST                | 7         | 8      | 13.46%  |
| Hitachi             | 5         | 5      | 9.62%   |
| Samsung Electronics | 2         | 2      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 52        | 53     | 75.36%  |
| SSD  | 15        | 15     | 21.74%  |
| NVMe | 2         | 2      | 2.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2702      | 3854   | 89.15%  |
| Works    | 258       | 314    | 8.51%   |
| Malfunc  | 68        | 70     | 2.24%   |
| Failed   | 2         | 2      | 0.07%   |
| Fixed    | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2176      | 69.15%  |
| AMD                              | 386       | 12.27%  |
| Samsung Electronics              | 161       | 5.12%   |
| SanDisk                          | 91        | 2.89%   |
| Nvidia                           | 49        | 1.56%   |
| SK hynix                         | 46        | 1.46%   |
| Micron Technology                | 33        | 1.05%   |
| Silicon Integrated Systems [SiS] | 31        | 0.99%   |
| KIOXIA                           | 24        | 0.76%   |
| Toshiba America Info Systems     | 23        | 0.73%   |
| Kingston Technology Company      | 23        | 0.73%   |
| Phison Electronics               | 18        | 0.57%   |
| VIA Technologies                 | 12        | 0.38%   |
| Silicon Motion                   | 11        | 0.35%   |
| ADATA Technology                 | 8         | 0.25%   |
| Micron/Crucial Technology        | 7         | 0.22%   |
| Union Memory (Shenzhen)          | 5         | 0.16%   |
| Marvell Technology Group         | 5         | 0.16%   |
| Lite-On Technology               | 5         | 0.16%   |
| JMicron Technology               | 5         | 0.16%   |
| Realtek Semiconductor            | 4         | 0.13%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.13%   |
| ASMedia Technology               | 4         | 0.13%   |
| Apple                            | 4         | 0.13%   |
| Yangtze Memory Technologies      | 2         | 0.06%   |
| Solid State Storage Technology   | 2         | 0.06%   |
| Silicon Image                    | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 293       | 8.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 246       | 6.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 202       | 5.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 199       | 5.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 174       | 4.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 157       | 4.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 120       | 3.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 120       | 3.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 100       | 2.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 99        | 2.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 81        | 2.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 67        | 1.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 64        | 1.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 54        | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 54        | 1.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 52        | 1.48%   |
| Intel Volume Management Device NVMe RAID Controller                              | 50        | 1.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 50        | 1.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 47        | 1.33%   |
| Samsung NVMe SSD Controller 980                                                  | 46        | 1.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 45        | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 40        | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 38        | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 37        | 1.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 36        | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 32        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 31        | 0.88%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 30        | 0.85%   |
| Intel Tiger Lake-LP SATA Controller                                              | 28        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 27        | 0.77%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 24        | 0.68%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 24        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 24        | 0.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 24        | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 23        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 21        | 0.6%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 20        | 0.57%   |
| Intel Comet Lake SATA AHCI Controller                                            | 20        | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 19        | 0.54%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 19        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2169      | 65.02%  |
| NVMe | 478       | 14.33%  |
| IDE  | 456       | 13.67%  |
| RAID | 233       | 6.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2502      | 83.93%  |
| AMD          | 478       | 16.03%  |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 38        | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 37        | 1.24%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 35        | 1.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 32        | 1.07%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 29        | 0.97%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 29        | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 28        | 0.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 26        | 0.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 25        | 0.84%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.84%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 25        | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 25        | 0.84%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 23        | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 22        | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 22        | 0.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 22        | 0.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 22        | 0.74%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 22        | 0.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 21        | 0.7%    |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 20        | 0.67%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 20        | 0.67%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 19        | 0.64%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 19        | 0.64%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 19        | 0.64%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 19        | 0.64%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 19        | 0.64%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 19        | 0.64%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 0.64%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 18        | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 18        | 0.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.6%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 18        | 0.6%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 17        | 0.57%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 17        | 0.57%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 17        | 0.57%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 16        | 0.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 16        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 637       | 21.35%  |
| Intel Core i7           | 444       | 14.88%  |
| Intel Core i3           | 296       | 9.92%   |
| Intel Celeron           | 260       | 8.71%   |
| Intel Core 2 Duo        | 249       | 8.34%   |
| Intel Atom              | 164       | 5.5%    |
| Other                   | 116       | 3.89%   |
| Intel Pentium           | 100       | 3.35%   |
| AMD Ryzen 5             | 71        | 2.38%   |
| AMD Ryzen 7             | 51        | 1.71%   |
| AMD A6                  | 50        | 1.68%   |
| Intel Pentium Dual-Core | 43        | 1.44%   |
| Intel Genuine           | 42        | 1.41%   |
| AMD A4                  | 42        | 1.41%   |
| Intel Pentium Dual      | 31        | 1.04%   |
| Intel Pentium M         | 26        | 0.87%   |
| Intel Core 2            | 26        | 0.87%   |
| AMD A8                  | 25        | 0.84%   |
| AMD A10                 | 25        | 0.84%   |
| Intel Celeron M         | 24        | 0.8%    |
| AMD Ryzen 3             | 23        | 0.77%   |
| AMD E1                  | 21        | 0.7%    |
| AMD E                   | 20        | 0.67%   |
| AMD Turion 64 X2 Mobile | 17        | 0.57%   |
| Intel Core M            | 12        | 0.4%    |
| Intel Pentium Silver    | 10        | 0.34%   |
| Intel Celeron Dual-Core | 9         | 0.3%    |
| AMD Turion 64 Mobile    | 9         | 0.3%    |
| AMD Ryzen 9             | 9         | 0.3%    |
| AMD E2                  | 9         | 0.3%    |
| AMD Athlon II           | 9         | 0.3%    |
| AMD Athlon 64 X2        | 9         | 0.3%    |
| Intel Core Duo          | 8         | 0.27%   |
| AMD Sempron             | 7         | 0.23%   |
| AMD Mobile Sempron      | 7         | 0.23%   |
| AMD Athlon              | 7         | 0.23%   |
| AMD C-50                | 6         | 0.2%    |
| AMD Athlon X2           | 6         | 0.2%    |
| Intel Core m5           | 5         | 0.17%   |
| AMD C-60                | 5         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1893      | 63.44%  |
| 4      | 734       | 24.6%   |
| 1      | 186       | 6.23%   |
| 6      | 86        | 2.88%   |
| 8      | 69        | 2.31%   |
| 10     | 6         | 0.2%    |
| 14     | 5         | 0.17%   |
| 3      | 2         | 0.07%   |
| 24     | 1         | 0.03%   |
| 16     | 1         | 0.03%   |
| 12     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2981      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1750      | 58.71%  |
| 1      | 1231      | 41.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2861      | 95.94%  |
| 32-bit         | 119       | 3.99%   |
| Unknown        | 2         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 265       | 8.76%   |
| Unknown    | 249       | 8.23%   |
| 0x306a9    | 220       | 7.28%   |
| 0x1067a    | 161       | 5.32%   |
| 0x40651    | 133       | 4.4%    |
| 0x20655    | 108       | 3.57%   |
| 0x406e3    | 99        | 3.27%   |
| 0x306d4    | 99        | 3.27%   |
| 0x6fd      | 90        | 2.98%   |
| 0x30678    | 83        | 2.74%   |
| 0x306c3    | 81        | 2.68%   |
| 0x806e9    | 75        | 2.48%   |
| 0x806ea    | 69        | 2.28%   |
| 0x406c4    | 66        | 2.18%   |
| 0x806c1    | 65        | 2.15%   |
| 0x806ec    | 55        | 1.82%   |
| 0x10676    | 52        | 1.72%   |
| 0x906ea    | 43        | 1.42%   |
| 0x406c3    | 42        | 1.39%   |
| 0x506c9    | 41        | 1.36%   |
| 0x20652    | 39        | 1.29%   |
| 0x706e5    | 38        | 1.26%   |
| 0x706a8    | 38        | 1.26%   |
| 0x906e9    | 37        | 1.22%   |
| 0x106ca    | 35        | 1.16%   |
| 0x06006705 | 34        | 1.12%   |
| 0x6e8      | 30        | 0.99%   |
| 0x6d8      | 30        | 0.99%   |
| 0x08108109 | 30        | 0.99%   |
| 0x07030105 | 26        | 0.86%   |
| 0x05000119 | 26        | 0.86%   |
| 0x0700010f | 25        | 0.83%   |
| 0x106c2    | 24        | 0.79%   |
| 0x08108102 | 24        | 0.79%   |
| 0x6f6      | 23        | 0.76%   |
| 0x6fb      | 22        | 0.73%   |
| 0x06001119 | 22        | 0.73%   |
| 0x0a50000c | 21        | 0.69%   |
| 0xa0652    | 20        | 0.66%   |
| 0x706a1    | 20        | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 324       | 10.87%  |
| SandyBridge      | 271       | 9.09%   |
| Haswell          | 232       | 7.78%   |
| IvyBridge        | 231       | 7.75%   |
| Penryn           | 224       | 7.51%   |
| Silvermont       | 219       | 7.35%   |
| Core             | 180       | 6.04%   |
| Westmere         | 154       | 5.17%   |
| Skylake          | 120       | 4.03%   |
| Broadwell        | 99        | 3.32%   |
| P6               | 84        | 2.82%   |
| TigerLake        | 74        | 2.48%   |
| Bonnell          | 70        | 2.35%   |
| Excavator        | 62        | 2.08%   |
| Goldmont plus    | 61        | 2.05%   |
| Zen+             | 57        | 1.91%   |
| IceLake          | 51        | 1.71%   |
| K8 Hammer        | 48        | 1.61%   |
| Goldmont         | 43        | 1.44%   |
| Puma             | 42        | 1.41%   |
| Bobcat           | 39        | 1.31%   |
| Zen 2            | 35        | 1.17%   |
| Zen 3            | 33        | 1.11%   |
| Unknown          | 33        | 1.11%   |
| Jaguar           | 31        | 1.04%   |
| Piledriver       | 26        | 0.87%   |
| CometLake        | 25        | 0.84%   |
| K10              | 22        | 0.74%   |
| K10 Llano        | 20        | 0.67%   |
| K8 & K10 hybrid  | 17        | 0.57%   |
| Zen              | 14        | 0.47%   |
| Alderlake Hybrid | 12        | 0.4%    |
| Nehalem          | 11        | 0.37%   |
| Tremont          | 7         | 0.23%   |
| Steamroller      | 6         | 0.2%    |
| NetBurst         | 4         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2182      | 62.27%  |
| AMD                              | 667       | 19.04%  |
| Nvidia                           | 616       | 17.58%  |
| Silicon Integrated Systems [SiS] | 28        | 0.8%    |
| VIA Technologies                 | 11        | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 242       | 6.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 219       | 5.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 137       | 3.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 137       | 3.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 115       | 3.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 114       | 3.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 105       | 2.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 90        | 2.42%   |
| Intel HD Graphics 620                                                                    | 81        | 2.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 79        | 2.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 79        | 2.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 79        | 2.13%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 75        | 2.02%   |
| Intel HD Graphics 5500                                                                   | 70        | 1.89%   |
| Intel UHD Graphics 620                                                                   | 68        | 1.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 58        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 58        | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 54        | 1.45%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 50        | 1.35%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 49        | 1.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 42        | 1.13%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 36        | 0.97%   |
| Intel HD Graphics 500                                                                    | 35        | 0.94%   |
| AMD Renoir                                                                               | 35        | 0.94%   |
| Intel HD Graphics 630                                                                    | 34        | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 30        | 0.81%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 30        | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 29        | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 27        | 0.73%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 27        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 26        | 0.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 26        | 0.7%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 25        | 0.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 0.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 24        | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 21        | 0.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 0.57%   |
| AMD Lucienne                                                                             | 21        | 0.57%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 20        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1691      | 56.63%  |
| 1 x AMD        | 464       | 15.54%  |
| Intel + Nvidia | 365       | 12.22%  |
| 1 x Nvidia     | 209       | 7%      |
| Intel + AMD    | 120       | 4.02%   |
| 2 x AMD        | 47        | 1.57%   |
| AMD + Nvidia   | 37        | 1.24%   |
| 1 x SiS        | 28        | 0.94%   |
| 1 x VIA        | 11        | 0.37%   |
| Other          | 8         | 0.27%   |
| 2 x Nvidia     | 6         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2601      | 86.84%  |
| Proprietary | 297       | 9.92%   |
| Unknown     | 97        | 3.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1969      | 65.18%  |
| 0.01-0.5   | 481       | 15.92%  |
| 1.01-2.0   | 253       | 8.37%   |
| 0.51-1.0   | 185       | 6.12%   |
| 3.01-4.0   | 84        | 2.78%   |
| 5.01-6.0   | 20        | 0.66%   |
| 7.01-8.0   | 16        | 0.53%   |
| 2.01-3.0   | 12        | 0.4%    |
| 8.01-16.0  | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 586       | 19.37%  |
| LG Display              | 427       | 14.12%  |
| Samsung Electronics     | 409       | 13.52%  |
| Chimei Innolux          | 387       | 12.79%  |
| BOE                     | 360       | 11.9%   |
| Chi Mei Optoelectronics | 118       | 3.9%    |
| Apple                   | 84        | 2.78%   |
| LG Philips              | 77        | 2.55%   |
| Lenovo                  | 52        | 1.72%   |
| Sharp                   | 46        | 1.52%   |
| Goldstar                | 44        | 1.45%   |
| Dell                    | 43        | 1.42%   |
| InfoVision              | 35        | 1.16%   |
| PANDA                   | 30        | 0.99%   |
| CPT                     | 21        | 0.69%   |
| HannStar                | 18        | 0.6%    |
| Toshiba                 | 17        | 0.56%   |
| Hewlett-Packard         | 17        | 0.56%   |
| Acer                    | 15        | 0.5%    |
| Sony                    | 14        | 0.46%   |
| Philips                 | 12        | 0.4%    |
| Quanta Display          | 11        | 0.36%   |
| BenQ                    | 11        | 0.36%   |
| Vizio                   | 10        | 0.33%   |
| LGD                     | 10        | 0.33%   |
| InnoLux Display         | 10        | 0.33%   |
| AOC                     | 10        | 0.33%   |
| Seiko/Epson             | 9         | 0.3%    |
| Panasonic               | 8         | 0.26%   |
| Ancor Communications    | 8         | 0.26%   |
| Eizo                    | 6         | 0.2%    |
| Iiyama                  | 5         | 0.17%   |
| BOE Technology Group    | 5         | 0.17%   |
| ASUSTek Computer        | 5         | 0.17%   |
| Unknown                 | 5         | 0.17%   |
| Unknown                 | 4         | 0.13%   |
| SLD                     | 4         | 0.13%   |
| KDC                     | 4         | 0.13%   |
| IBM                     | 4         | 0.13%   |
| ViewSonic               | 3         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 34        | 1.11%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 24        | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 21        | 0.69%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 18        | 0.59%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 17        | 0.56%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.52%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 16        | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 15        | 0.49%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.46%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 14        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.43%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 13        | 0.43%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 13        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 12        | 0.39%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 12        | 0.39%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 11        | 0.36%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 11        | 0.36%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 10        | 0.33%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 10        | 0.33%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 9         | 0.29%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 9         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 9         | 0.29%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 9         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 8         | 0.26%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 8         | 0.26%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 8         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1244      | 42.18%  |
| 1920x1080 (FHD)    | 815       | 27.64%  |
| 1280x800 (WXGA)    | 239       | 8.1%    |
| 1600x900 (HD+)     | 192       | 6.51%   |
| 1440x900 (WXGA+)   | 82        | 2.78%   |
| 3840x2160 (4K)     | 59        | 2%      |
| 1024x600           | 47        | 1.59%   |
| 1920x1200 (WUXGA)  | 32        | 1.09%   |
| 1680x1050 (WSXGA+) | 31        | 1.05%   |
| 2560x1600          | 25        | 0.85%   |
| 2560x1440 (QHD)    | 22        | 0.75%   |
| 1360x768           | 14        | 0.47%   |
| 1280x1024 (SXGA)   | 14        | 0.47%   |
| 2880x1800          | 12        | 0.41%   |
| 3200x1800 (QHD+)   | 10        | 0.34%   |
| 2560x1080          | 10        | 0.34%   |
| 2160x1440          | 10        | 0.34%   |
| 1024x768 (XGA)     | 10        | 0.34%   |
| Unknown            | 9         | 0.31%   |
| 2256x1504          | 8         | 0.27%   |
| 1280x768           | 8         | 0.27%   |
| 1920x540           | 6         | 0.2%    |
| 3840x2400          | 5         | 0.17%   |
| 3440x1440          | 5         | 0.17%   |
| 3840x1080          | 4         | 0.14%   |
| 1680x945           | 4         | 0.14%   |
| 1920x515           | 3         | 0.1%    |
| 1400x1050          | 3         | 0.1%    |
| 1024x576           | 3         | 0.1%    |
| 5760x1080          | 2         | 0.07%   |
| 3600x1080          | 2         | 0.07%   |
| 2880x1920          | 2         | 0.07%   |
| 2304x1440          | 2         | 0.07%   |
| 2288x1287          | 2         | 0.07%   |
| 1280x720 (HD)      | 2         | 0.07%   |
| 5760x2160          | 1         | 0.03%   |
| 4480x1600          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |
| 3072x1920          | 1         | 0.03%   |
| 3000x2000          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1325      | 43.86%  |
| 13      | 409       | 13.54%  |
| 14      | 353       | 11.68%  |
| 17      | 250       | 8.28%   |
| 11      | 115       | 3.81%   |
| 12      | 84        | 2.78%   |
| Unknown | 71        | 2.35%   |
| 10      | 58        | 1.92%   |
| 24      | 48        | 1.59%   |
| 27      | 45        | 1.49%   |
| 23      | 32        | 1.06%   |
| 18      | 30        | 0.99%   |
| 21      | 29        | 0.96%   |
| 16      | 21        | 0.7%    |
| 31      | 20        | 0.66%   |
| 34      | 18        | 0.6%    |
| 19      | 13        | 0.43%   |
| 20      | 12        | 0.4%    |
| 22      | 11        | 0.36%   |
| 72      | 9         | 0.3%    |
| 54      | 9         | 0.3%    |
| 40      | 7         | 0.23%   |
| 84      | 6         | 0.2%    |
| 8       | 5         | 0.17%   |
| 32      | 4         | 0.13%   |
| 26      | 4         | 0.13%   |
| 25      | 4         | 0.13%   |
| 74      | 3         | 0.1%    |
| 52      | 3         | 0.1%    |
| 49      | 3         | 0.1%    |
| 58      | 2         | 0.07%   |
| 46      | 2         | 0.07%   |
| 37      | 2         | 0.07%   |
| 36      | 2         | 0.07%   |
| 29      | 2         | 0.07%   |
| 65      | 1         | 0.03%   |
| 64      | 1         | 0.03%   |
| 59      | 1         | 0.03%   |
| 55      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1874      | 62.24%  |
| 201-300     | 435       | 14.45%  |
| 351-400     | 302       | 10.03%  |
| 501-600     | 124       | 4.12%   |
| 401-500     | 93        | 3.09%   |
| Unknown     | 71        | 2.36%   |
| 601-700     | 27        | 0.9%    |
| 701-800     | 25        | 0.83%   |
| 1001-1500   | 24        | 0.8%    |
| 1501-2000   | 18        | 0.6%    |
| 801-900     | 10        | 0.33%   |
| 101-200     | 5         | 0.17%   |
| 901-1000    | 3         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2254      | 80.44%  |
| 16/10   | 413       | 14.74%  |
| Unknown | 54        | 1.93%   |
| 3/2     | 25        | 0.89%   |
| 4/3     | 19        | 0.68%   |
| 21/9    | 16        | 0.57%   |
| 5/4     | 13        | 0.46%   |
| 32/9    | 3         | 0.11%   |
| 3.73    | 3         | 0.11%   |
| 0.62    | 2         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1324      | 43.88%  |
| 81-90          | 636       | 21.08%  |
| 121-130        | 183       | 6.07%   |
| 71-80          | 120       | 3.98%   |
| 51-60          | 115       | 3.81%   |
| 201-250        | 99        | 3.28%   |
| 61-70          | 82        | 2.72%   |
| Unknown        | 71        | 2.35%   |
| 41-50          | 58        | 1.92%   |
| 131-140        | 57        | 1.89%   |
| 301-350        | 48        | 1.59%   |
| 351-500        | 43        | 1.43%   |
| More than 1000 | 39        | 1.29%   |
| 151-200        | 38        | 1.26%   |
| 141-150        | 38        | 1.26%   |
| 501-1000       | 20        | 0.66%   |
| 111-120        | 16        | 0.53%   |
| 251-300        | 13        | 0.43%   |
| 91-100         | 12        | 0.4%    |
| 1-40           | 5         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1304      | 43.88%  |
| 121-160       | 871       | 29.31%  |
| 51-100        | 507       | 17.06%  |
| 161-240       | 134       | 4.51%   |
| Unknown       | 71        | 2.39%   |
| 1-50          | 43        | 1.45%   |
| More than 240 | 42        | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2594      | 85.5%   |
| 2     | 315       | 10.38%  |
| 0     | 102       | 3.36%   |
| 3     | 20        | 0.66%   |
| 4     | 2         | 0.07%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1493      | 30.91%  |
| Intel                             | 1256      | 26%     |
| Qualcomm Atheros                  | 814       | 16.85%  |
| Broadcom                          | 488       | 10.1%   |
| Broadcom Limited                  | 154       | 3.19%   |
| Marvell Technology Group          | 88        | 1.82%   |
| Ralink                            | 61        | 1.26%   |
| Nvidia                            | 43        | 0.89%   |
| TP-Link                           | 33        | 0.68%   |
| MediaTek                          | 31        | 0.64%   |
| Silicon Integrated Systems [SiS]  | 29        | 0.6%    |
| Dell                              | 26        | 0.54%   |
| Ralink Technology                 | 25        | 0.52%   |
| ASIX Electronics                  | 25        | 0.52%   |
| JMicron Technology                | 24        | 0.5%    |
| Samsung Electronics               | 23        | 0.48%   |
| Xiaomi                            | 16        | 0.33%   |
| Sierra Wireless                   | 16        | 0.33%   |
| Hewlett-Packard                   | 15        | 0.31%   |
| DisplayLink                       | 12        | 0.25%   |
| Huawei Technologies               | 11        | 0.23%   |
| VIA Technologies                  | 10        | 0.21%   |
| Qualcomm Atheros Communications   | 9         | 0.19%   |
| NetGear                           | 9         | 0.19%   |
| Ericsson Business Mobile Networks | 9         | 0.19%   |
| ASUSTek Computer                  | 9         | 0.19%   |
| OPPO Electronics                  | 8         | 0.17%   |
| Edimax Technology                 | 8         | 0.17%   |
| AMD                               | 8         | 0.17%   |
| Qualcomm                          | 6         | 0.12%   |
| Motorola PCS                      | 6         | 0.12%   |
| Attansic Technology               | 6         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.08%   |
| Google                            | 4         | 0.08%   |
| D-Link System                     | 4         | 0.08%   |
| D-Link                            | 4         | 0.08%   |
| T & A Mobile Phones               | 3         | 0.06%   |
| Linksys                           | 3         | 0.06%   |
| Belkin Components                 | 3         | 0.06%   |
| ZyDAS                             | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 750       | 13.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 414       | 7.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 146       | 2.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 134       | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 122       | 2.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 113       | 1.97%   |
| Intel Wireless 7260                                                     | 111       | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 107       | 1.86%   |
| Intel Wireless 7265                                                     | 80        | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 80        | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 77        | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 75        | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                           | 69        | 1.2%    |
| Intel Wireless 8265 / 8275                                              | 68        | 1.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 66        | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 64        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 1.06%   |
| Intel Wireless 8260                                                     | 55        | 0.96%   |
| Intel Wi-Fi 6 AX200                                                     | 55        | 0.96%   |
| Intel Wireless 3165                                                     | 54        | 0.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 53        | 0.92%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 52        | 0.9%    |
| Intel WiFi Link 5100                                                    | 50        | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 47        | 0.82%   |
| Intel Wi-Fi 6 AX201                                                     | 47        | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 41        | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 38        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 37        | 0.64%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 0.63%   |
| Intel Wireless 3160                                                     | 35        | 0.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 0.61%   |
| Intel Ethernet Connection I218-LM                                       | 35        | 0.61%   |
| Intel Ethernet Connection I217-LM                                       | 35        | 0.61%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 35        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                                | 34        | 0.59%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 33        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 33        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                | 33        | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 31        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1173      | 37.97%  |
| Qualcomm Atheros                | 688       | 22.27%  |
| Realtek Semiconductor           | 513       | 16.61%  |
| Broadcom                        | 376       | 12.17%  |
| Broadcom Limited                | 107       | 3.46%   |
| Ralink                          | 61        | 1.97%   |
| MediaTek                        | 26        | 0.84%   |
| TP-Link                         | 25        | 0.81%   |
| Ralink Technology               | 25        | 0.81%   |
| Sierra Wireless                 | 16        | 0.52%   |
| Dell                            | 12        | 0.39%   |
| Qualcomm Atheros Communications | 9         | 0.29%   |
| NetGear                         | 9         | 0.29%   |
| Edimax Technology               | 8         | 0.26%   |
| ASUSTek Computer                | 8         | 0.26%   |
| D-Link System                   | 4         | 0.13%   |
| D-Link                          | 4         | 0.13%   |
| Linksys                         | 3         | 0.1%    |
| Hewlett-Packard                 | 3         | 0.1%    |
| Belkin Components               | 3         | 0.1%    |
| ZyDAS                           | 2         | 0.06%   |
| Micro Star International        | 2         | 0.06%   |
| ZyXEL Communications            | 1         | 0.03%   |
| Xiaomi                          | 1         | 0.03%   |
| TRENDnet                        | 1         | 0.03%   |
| Tenda                           | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Qualcomm                        | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Mercucys                        | 1         | 0.03%   |
| Lite-On Technology              | 1         | 0.03%   |
| IMC Networks                    | 1         | 0.03%   |
| Fibocom                         | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 146       | 4.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 134       | 4.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 113       | 3.63%   |
| Intel Wireless 7260                                                     | 111       | 3.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 107       | 3.43%   |
| Intel Wireless 7265                                                     | 80        | 2.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 80        | 2.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 77        | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 75        | 2.41%   |
| Broadcom BCM43142 802.11b/g/n                                           | 69        | 2.21%   |
| Intel Wireless 8265 / 8275                                              | 68        | 2.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 66        | 2.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 64        | 2.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 1.96%   |
| Intel Wireless 8260                                                     | 55        | 1.76%   |
| Intel Wi-Fi 6 AX200                                                     | 55        | 1.76%   |
| Intel Wireless 3165                                                     | 54        | 1.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 53        | 1.7%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 52        | 1.67%   |
| Intel WiFi Link 5100                                                    | 50        | 1.6%    |
| Intel Wi-Fi 6 AX201                                                     | 47        | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 41        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 38        | 1.22%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 1.15%   |
| Intel Wireless 3160                                                     | 35        | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 1.12%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 35        | 1.12%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 33        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 31        | 0.99%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 30        | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 28        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 27        | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 26        | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 25        | 0.8%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 24        | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 24        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 24        | 0.77%   |
| Intel Centrino Advanced-N 6235                                          | 24        | 0.77%   |
| Intel Centrino Advanced-N 6200                                          | 24        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1273      | 50.3%   |
| Intel                                  | 483       | 19.08%  |
| Qualcomm Atheros                       | 214       | 8.46%   |
| Broadcom                               | 172       | 6.8%    |
| Marvell Technology Group               | 88        | 3.48%   |
| Broadcom Limited                       | 52        | 2.05%   |
| Nvidia                                 | 43        | 1.7%    |
| Silicon Integrated Systems [SiS]       | 27        | 1.07%   |
| ASIX Electronics                       | 25        | 0.99%   |
| JMicron Technology                     | 24        | 0.95%   |
| Samsung Electronics                    | 23        | 0.91%   |
| Xiaomi                                 | 15        | 0.59%   |
| DisplayLink                            | 12        | 0.47%   |
| VIA Technologies                       | 10        | 0.4%    |
| TP-Link                                | 8         | 0.32%   |
| OPPO Electronics                       | 8         | 0.32%   |
| Huawei Technologies                    | 8         | 0.32%   |
| Attansic Technology                    | 6         | 0.24%   |
| Qualcomm                               | 5         | 0.2%    |
| Motorola PCS                           | 5         | 0.2%    |
| MediaTek                               | 5         | 0.2%    |
| Google                                 | 4         | 0.16%   |
| Hewlett-Packard                        | 3         | 0.12%   |
| T & A Mobile Phones                    | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.08%   |
| Lenovo                                 | 2         | 0.08%   |
| Davicom Semiconductor                  | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Novatel Wireless                       | 1         | 0.04%   |
| Motorola BCS                           | 1         | 0.04%   |
| LG Electronics                         | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |
| GoPro                                  | 1         | 0.04%   |
| ASUSTek Computer                       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 750       | 29.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 414       | 16.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 122       | 4.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 47        | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 37        | 1.46%   |
| Intel Ethernet Connection I218-LM                                 | 35        | 1.38%   |
| Intel Ethernet Connection I217-LM                                 | 35        | 1.38%   |
| Intel 82567LM Gigabit Network Connection                          | 34        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 1.3%    |
| Intel 82577LM Gigabit Network Connection                          | 33        | 1.3%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 28        | 1.1%    |
| Intel Ethernet Connection I219-LM                                 | 27        | 1.06%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 26        | 1.02%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 25        | 0.98%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 24        | 0.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 24        | 0.94%   |
| Intel 82566MM Gigabit Network Connection                          | 21        | 0.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.79%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 20        | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 19        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.67%   |
| Intel Ethernet Connection I219-V                                  | 17        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 17        | 0.67%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 17        | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.59%   |
| Nvidia MCP79 Ethernet                                             | 15        | 0.59%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 15        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.55%   |
| Nvidia MCP67 Ethernet                                             | 14        | 0.55%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.51%   |
| Intel PRO/100 VE Network Connection                               | 13        | 0.51%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 13        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.47%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 12        | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2886      | 53.25%  |
| Ethernet | 2442      | 45.06%  |
| Modem    | 86        | 1.59%   |
| Unknown  | 6         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2427      | 78.62%  |
| Ethernet | 659       | 21.35%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2258      | 75.64%  |
| 1     | 593       | 19.87%  |
| 0     | 120       | 4.02%   |
| 3     | 14        | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2351      | 77.69%  |
| Yes  | 675       | 22.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 727       | 37%     |
| Qualcomm Atheros Communications | 242       | 12.32%  |
| Realtek Semiconductor           | 221       | 11.25%  |
| Broadcom                        | 159       | 8.09%   |
| IMC Networks                    | 87        | 4.43%   |
| Apple                           | 74        | 3.77%   |
| Lite-On Technology              | 71        | 3.61%   |
| Foxconn / Hon Hai               | 70        | 3.56%   |
| Dell                            | 67        | 3.41%   |
| Hewlett-Packard                 | 66        | 3.36%   |
| Toshiba                         | 40        | 2.04%   |
| Cambridge Silicon Radio         | 30        | 1.53%   |
| Ralink                          | 25        | 1.27%   |
| ASUSTek Computer                | 17        | 0.87%   |
| Alps Electric                   | 14        | 0.71%   |
| Realtek                         | 13        | 0.66%   |
| Foxconn International           | 12        | 0.61%   |
| Askey Computer                  | 6         | 0.31%   |
| Ralink Technology               | 5         | 0.25%   |
| Taiyo Yuden                     | 4         | 0.2%    |
| Dynex                           | 3         | 0.15%   |
| Chicony Electronics             | 3         | 0.15%   |
| Qcom                            | 2         | 0.1%    |
| MediaTek                        | 2         | 0.1%    |
| Integrated System Solution      | 2         | 0.1%    |
| TP-Link                         | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 382       | 19.41%  |
| Realtek Bluetooth Radio                             | 145       | 7.37%   |
| Qualcomm Atheros  Bluetooth Device                  | 103       | 5.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 93        | 4.73%   |
| Intel AX201 Bluetooth                               | 86        | 4.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 67        | 3.4%    |
| Intel AX200 Bluetooth                               | 53        | 2.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 43        | 2.18%   |
| Apple Bluetooth Host Controller                     | 43        | 2.18%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 39        | 1.98%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 39        | 1.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 36        | 1.83%   |
| IMC Networks Bluetooth Device                       | 32        | 1.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 30        | 1.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 26        | 1.32%   |
| Lite-On Atheros AR3012 Bluetooth                    | 26        | 1.32%   |
| Ralink RT3290 Bluetooth                             | 25        | 1.27%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 24        | 1.22%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 23        | 1.17%   |
| Intel Bluetooth Device                              | 23        | 1.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 1.07%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 21        | 1.07%   |
| IMC Networks Bluetooth Radio                        | 21        | 1.07%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 1.07%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 1.02%   |
| Dell DW375 Bluetooth Module                         | 19        | 0.97%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 19        | 0.97%   |
| Foxconn / Hon Hai Bluetooth Device                  | 18        | 0.91%   |
| Intel AX210 Bluetooth                               | 17        | 0.86%   |
| Toshiba Bluetooth Device                            | 13        | 0.66%   |
| IMC Networks Wireless_Device                        | 13        | 0.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 0.66%   |
| Apple Bluetooth USB Host Controller                 | 13        | 0.66%   |
| Foxconn International BCM43142A0 Bluetooth module   | 12        | 0.61%   |
| Dell Wireless 365 Bluetooth                         | 12        | 0.61%   |
| Realtek 802.11ac WLAN Adapter                       | 11        | 0.56%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.56%   |
| Broadcom BCM2045 Bluetooth                          | 11        | 0.56%   |
| Lite-On Bluetooth Device                            | 10        | 0.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2349      | 70.04%  |
| AMD                                  | 532       | 15.86%  |
| Nvidia                               | 343       | 10.23%  |
| Silicon Integrated Systems [SiS]     | 31        | 0.92%   |
| VIA Technologies                     | 11        | 0.33%   |
| C-Media Electronics                  | 10        | 0.3%    |
| Generalplus Technology               | 7         | 0.21%   |
| Tenx Technology                      | 6         | 0.18%   |
| Realtek Semiconductor                | 5         | 0.15%   |
| Logitech                             | 4         | 0.12%   |
| Lenovo                               | 4         | 0.12%   |
| Creative Technology                  | 4         | 0.12%   |
| Texas Instruments                    | 3         | 0.09%   |
| SteelSeries ApS                      | 3         | 0.09%   |
| Plantronics                          | 3         | 0.09%   |
| JMTek                                | 3         | 0.09%   |
| GN Netcom                            | 3         | 0.09%   |
| Yamaha                               | 2         | 0.06%   |
| PreSonus Audio Electronics           | 2         | 0.06%   |
| Focusrite-Novation                   | 2         | 0.06%   |
| DCMT Technology                      | 2         | 0.06%   |
| Corsair                              | 2         | 0.06%   |
| ZOOM                                 | 1         | 0.03%   |
| XMOS                                 | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.03%   |
| Syntek                               | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| Sennheiser Communications            | 1         | 0.03%   |
| SAVITECH                             | 1         | 0.03%   |
| Roland                               | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |
| OPPO Electronics                     | 1         | 0.03%   |
| Kingston Technology                  | 1         | 0.03%   |
| Hewlett-Packard                      | 1         | 0.03%   |
| FiiO Electronics Technology          | 1         | 0.03%   |
| DSEA A/S                             | 1         | 0.03%   |
| Dell                                 | 1         | 0.03%   |
| Conexant Systems                     | 1         | 0.03%   |
| CMX Systems                          | 1         | 0.03%   |
| BEHRINGER International              | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 280       | 6.9%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 264       | 6.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 221       | 5.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 194       | 4.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 165       | 4.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 162       | 3.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 141       | 3.47%   |
| Intel 8 Series HD Audio Controller                                                                | 139       | 3.43%   |
| AMD FCH Azalia Controller                                                                         | 136       | 3.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 135       | 3.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 126       | 3.1%    |
| Intel Broadwell-U Audio Controller                                                                | 99        | 2.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 98        | 2.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 93        | 2.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 86        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 76        | 1.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 74        | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 73        | 1.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 73        | 1.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 72        | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 64        | 1.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 61        | 1.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 60        | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 52        | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 51        | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 49        | 1.21%   |
| AMD High Definition Audio Controller                                                              | 49        | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 46        | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 43        | 1.06%   |
| Intel CM238 HD Audio Controller                                                                   | 40        | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 39        | 0.96%   |
| AMD Wrestler HDMI Audio                                                                           | 32        | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 30        | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 30        | 0.74%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 26        | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 26        | 0.64%   |
| Nvidia High Definition Audio Controller                                                           | 24        | 0.59%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 24        | 0.59%   |
| Intel Comet Lake PCH cAVS                                                                         | 23        | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 22        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 179       | 24.79%  |
| SK hynix               | 171       | 23.68%  |
| Micron Technology      | 83        | 11.5%   |
| Unknown                | 69        | 9.56%   |
| Kingston               | 52        | 7.2%    |
| Unknown (ABCD)         | 20        | 2.77%   |
| Crucial                | 20        | 2.77%   |
| Elpida                 | 16        | 2.22%   |
| Ramaxel Technology     | 15        | 2.08%   |
| Nanya Technology       | 15        | 2.08%   |
| A-DATA Technology      | 13        | 1.8%    |
| Smart                  | 9         | 1.25%   |
| Qimonda                | 4         | 0.55%   |
| Corsair                | 4         | 0.55%   |
| Timetec                | 3         | 0.42%   |
| Unknown                | 3         | 0.42%   |
| Transcend              | 2         | 0.28%   |
| Teikon                 | 2         | 0.28%   |
| Team                   | 2         | 0.28%   |
| Smart Brazil           | 2         | 0.28%   |
| SHARETRONIC            | 2         | 0.28%   |
| Patriot                | 2         | 0.28%   |
| High Bridge            | 2         | 0.28%   |
| G.Skill                | 2         | 0.28%   |
| ff                     | 2         | 0.28%   |
| fef5                   | 2         | 0.28%   |
| 4ea5                   | 2         | 0.28%   |
| Walton Chaintech       | 1         | 0.14%   |
| Unknown (08B5)         | 1         | 0.14%   |
| Unknown (07F7)         | 1         | 0.14%   |
| Unknown (000080B30080) | 1         | 0.14%   |
| Toshiba                | 1         | 0.14%   |
| Strontium              | 1         | 0.14%   |
| Silicon Power          | 1         | 0.14%   |
| PUSKILL                | 1         | 0.14%   |
| ProMos/Mosel Vitelic   | 1         | 0.14%   |
| pqi                    | 1         | 0.14%   |
| PNY                    | 1         | 0.14%   |
| Netlist                | 1         | 0.14%   |
| Nayna                  | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 18        | 2.34%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.3%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 1.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.17%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 8         | 1.04%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.91%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.91%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 7         | 0.91%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.78%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 6         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.78%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.78%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.65%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.65%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.65%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.52%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.52%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.52%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.52%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.52%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.52%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 4         | 0.52%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 4         | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.39%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 3         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 242       | 39.54%  |
| DDR4    | 197       | 32.19%  |
| DDR2    | 70        | 11.44%  |
| LPDDR4  | 40        | 6.54%   |
| SDRAM   | 23        | 3.76%   |
| LPDDR3  | 20        | 3.27%   |
| DRAM    | 6         | 0.98%   |
| DDR     | 5         | 0.82%   |
| Unknown | 5         | 0.82%   |
| LPDDR5  | 2         | 0.33%   |
| DDR5    | 2         | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 533       | 88.25%  |
| Row Of Chips | 46        | 7.62%   |
| DIMM         | 12        | 1.99%   |
| Unknown      | 8         | 1.32%   |
| Chip         | 5         | 0.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 216       | 31.21%  |
| 4096  | 215       | 31.07%  |
| 2048  | 148       | 21.39%  |
| 1024  | 50        | 7.23%   |
| 16384 | 44        | 6.36%   |
| 512   | 12        | 1.73%   |
| 32768 | 5         | 0.72%   |
| 256   | 2         | 0.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 164       | 24.7%   |
| 2667    | 94        | 14.16%  |
| 3200    | 74        | 11.14%  |
| 2400    | 55        | 8.28%   |
| 1334    | 40        | 6.02%   |
| 667     | 38        | 5.72%   |
| Unknown | 27        | 4.07%   |
| 2133    | 26        | 3.92%   |
| 1333    | 25        | 3.77%   |
| 1066    | 15        | 2.26%   |
| 800     | 13        | 1.96%   |
| 4267    | 11        | 1.66%   |
| 975     | 11        | 1.66%   |
| 2048    | 10        | 1.51%   |
| 533     | 10        | 1.51%   |
| 4199    | 9         | 1.36%   |
| 3266    | 9         | 1.36%   |
| 1867    | 8         | 1.2%    |
| 1067    | 7         | 1.05%   |
| 8400    | 3         | 0.45%   |
| 6400    | 3         | 0.45%   |
| 400     | 3         | 0.45%   |
| 4800    | 2         | 0.3%    |
| 3733    | 2         | 0.3%    |
| 4266    | 1         | 0.15%   |
| 2933    | 1         | 0.15%   |
| 1866    | 1         | 0.15%   |
| 1639    | 1         | 0.15%   |
| 666     | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 40%     |
| Canon                 | 6         | 20%     |
| Seiko Epson           | 5         | 16.67%  |
| Samsung Electronics   | 2         | 6.67%   |
| Brother Industries    | 2         | 6.67%   |
| Zebra                 | 1         | 3.33%   |
| STMicroelectronics    | 1         | 3.33%   |
| Lexmark International | 1         | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP ENVY Photo 6200 series                                 | 2         | 6.67%   |
| HP DeskJet 1110 series                                    | 2         | 6.67%   |
| Zebra ZP 450 Printer                                      | 1         | 3.33%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.33%   |
| Seiko Epson WF-2010 Series                                | 1         | 3.33%   |
| Seiko Epson Printer                                       | 1         | 3.33%   |
| Seiko Epson L3110 Series                                  | 1         | 3.33%   |
| Seiko Epson ET-2810 Series                                | 1         | 3.33%   |
| Seiko Epson AcuLaser C1700                                | 1         | 3.33%   |
| Samsung M2020 Series                                      | 1         | 3.33%   |
| Samsung CLX-3300 Series                                   | 1         | 3.33%   |
| Lexmark International 2400 series                         | 1         | 3.33%   |
| HP Laserjet P1505                                         | 1         | 3.33%   |
| HP LaserJet P1102                                         | 1         | 3.33%   |
| HP LaserJet 1200                                          | 1         | 3.33%   |
| HP LaserJet 1020                                          | 1         | 3.33%   |
| HP LaserJet 1000                                          | 1         | 3.33%   |
| HP DeskJet 2700 series                                    | 1         | 3.33%   |
| HP DeskJet 2300 series                                    | 1         | 3.33%   |
| HP Deskjet 1510                                           | 1         | 3.33%   |
| Canon TS3100 series                                       | 1         | 3.33%   |
| Canon PIXMA MX490 Series                                  | 1         | 3.33%   |
| Canon PIXMA MX340                                         | 1         | 3.33%   |
| Canon PIXMA MG3600 Series                                 | 1         | 3.33%   |
| Canon PIXMA MG3000 series                                 | 1         | 3.33%   |
| Canon MG2100 series                                       | 1         | 3.33%   |
| Brother MFC-L2730DW series                                | 1         | 3.33%   |
| Brother DCP-T300                                          | 1         | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 60%     |
| Seiko Epson | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 40%     |
| Canon CanoScan LiDE 90                      | 1         | 20%     |
| Canon CanoScan LIDE 25                      | 1         | 20%     |
| Canon CanoScan LiDE 200                     | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 606       | 25.08%  |
| Microdia                               | 229       | 9.48%   |
| Realtek Semiconductor                  | 199       | 8.24%   |
| IMC Networks                           | 184       | 7.62%   |
| Sunplus Innovation Technology          | 136       | 5.63%   |
| Bison Electronics                      | 136       | 5.63%   |
| Suyin                                  | 124       | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 112       | 4.64%   |
| Quanta                                 | 99        | 4.1%    |
| Apple                                  | 69        | 2.86%   |
| Syntek                                 | 64        | 2.65%   |
| Silicon Motion                         | 56        | 2.32%   |
| Lite-On Technology                     | 46        | 1.9%    |
| Alcor Micro                            | 44        | 1.82%   |
| Acer                                   | 37        | 1.53%   |
| Ricoh                                  | 32        | 1.32%   |
| Luxvisions Innotech Limited            | 22        | 0.91%   |
| Logitech                               | 20        | 0.83%   |
| ALi                                    | 19        | 0.79%   |
| Importek                               | 17        | 0.7%    |
| Samsung Electronics                    | 16        | 0.66%   |
| Primax Electronics                     | 15        | 0.62%   |
| icSpring                               | 14        | 0.58%   |
| Z-Star Microelectronics                | 13        | 0.54%   |
| Sonix Technology                       | 11        | 0.46%   |
| Lenovo                                 | 11        | 0.46%   |
| OmniVision Technologies                | 10        | 0.41%   |
| GEMBIRD                                | 9         | 0.37%   |
| SunplusIT                              | 7         | 0.29%   |
| Genesys Logic                          | 6         | 0.25%   |
| Y Media                                | 4         | 0.17%   |
| Sunplus Technology                     | 4         | 0.17%   |
| Intel                                  | 4         | 0.17%   |
| Microsoft                              | 3         | 0.12%   |
| Generalplus Technology                 | 3         | 0.12%   |
| ARC International                      | 3         | 0.12%   |
| Tripath Technology                     | 2         | 0.08%   |
| LG Electronics                         | 2         | 0.08%   |
| Huawei Technologies                    | 2         | 0.08%   |
| Camera                                 | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 80        | 3.3%    |
| Microdia Integrated_Webcam_HD                    | 48        | 1.98%   |
| IMC Networks USB2.0 HD UVC WebCam                | 44        | 1.82%   |
| Chicony HD WebCam                                | 37        | 1.53%   |
| Realtek Integrated_Webcam_HD                     | 36        | 1.49%   |
| Microdia Integrated Webcam                       | 36        | 1.49%   |
| Chicony HP Truevision HD                         | 35        | 1.44%   |
| Bison Integrated Camera                          | 33        | 1.36%   |
| Syntek Integrated Camera                         | 30        | 1.24%   |
| Chicony TOSHIBA Web Camera - HD                  | 30        | 1.24%   |
| Sunplus Integrated_Webcam_HD                     | 26        | 1.07%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 26        | 1.07%   |
| IMC Networks Integrated Camera                   | 25        | 1.03%   |
| Chicony USB 2.0 Camera                           | 24        | 0.99%   |
| Chicony HP TrueVision HD Camera                  | 24        | 0.99%   |
| Sunplus HD WebCam                                | 23        | 0.95%   |
| Realtek Integrated Webcam                        | 22        | 0.91%   |
| Bison Lenovo EasyCamera                          | 22        | 0.91%   |
| Chicony Lenovo EasyCamera                        | 21        | 0.87%   |
| Chicony EasyCamera                               | 20        | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 20        | 0.83%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 20        | 0.83%   |
| Apple FaceTime HD Camera                         | 19        | 0.78%   |
| Chicony VGA WebCam                               | 18        | 0.74%   |
| Chicony HP HD Webcam                             | 18        | 0.74%   |
| Suyin HP Truevision HD                           | 17        | 0.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 17        | 0.7%    |
| Realtek USB Camera                               | 17        | 0.7%    |
| Lite-On HP HD Camera                             | 17        | 0.7%    |
| Alcor Micro USB 2.0 PC cam                       | 17        | 0.7%    |
| Samsung Galaxy series, misc. (MTP mode)          | 16        | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam                    | 16        | 0.66%   |
| Chicony HP Webcam                                | 16        | 0.66%   |
| Chicony CNF9055 Toshiba Webcam                   | 16        | 0.66%   |
| ALi Gateway Webcam                               | 16        | 0.66%   |
| Realtek HP Truevision HD                         | 15        | 0.62%   |
| Quanta HP Webcam                                 | 15        | 0.62%   |
| Quanta HP TrueVision HD Camera                   | 15        | 0.62%   |
| Chicony HP HD Camera                             | 15        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 15        | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 196       | 47.57%  |
| AuthenTec                          | 62        | 15.05%  |
| Shenzhen Goodix Technology         | 39        | 9.47%   |
| Upek                               | 34        | 8.25%   |
| Synaptics                          | 32        | 7.77%   |
| Elan Microelectronics              | 19        | 4.61%   |
| STMicroelectronics                 | 18        | 4.37%   |
| LighTuning Technology              | 8         | 1.94%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.49%   |
| Samsung Electronics                | 1         | 0.24%   |
| Focal-systems.Corp                 | 1         | 0.24%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 10.19%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 32        | 7.77%   |
| Shenzhen Goodix  FingerPrint Device                                        | 28        | 6.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 6.07%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 5.1%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 21        | 5.1%    |
| Validity Sensors VFS491                                                    | 19        | 4.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 4.37%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 4.37%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 4.37%   |
| AuthenTec AES2810                                                          | 18        | 4.37%   |
| Elan ELAN:ARM-M4                                                           | 11        | 2.67%   |
| AuthenTec AES1600                                                          | 10        | 2.43%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.18%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 2.18%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 1.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 1.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.46%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 1.46%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.46%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.46%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.21%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 1.21%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.21%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.97%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.97%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.97%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.73%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.73%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.73%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.49%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.49%   |
| Synaptics WBDI                                                             | 2         | 0.49%   |
| Synaptics  WBDI                                                            | 2         | 0.49%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.49%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.49%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.49%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 99        | 54.4%   |
| Alcor Micro                       | 31        | 17.03%  |
| O2 Micro                          | 27        | 14.84%  |
| Lenovo                            | 9         | 4.95%   |
| Upek                              | 7         | 3.85%   |
| Yubico.com                        | 2         | 1.1%    |
| SCM Microsystems                  | 2         | 1.1%    |
| Realtek Semiconductor             | 2         | 1.1%    |
| VASCO Data Security International | 1         | 0.55%   |
| OmniKey                           | 1         | 0.55%   |
| Fujitsu Siemens Computers         | 1         | 0.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 47        | 25.68%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 16.39%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 13.11%  |
| Broadcom 5880                                                                | 23        | 12.57%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 12.02%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 4.92%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 3.83%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 2.73%   |
| Broadcom 58200                                                               | 4         | 2.19%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.09%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.09%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.09%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.55%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.55%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.55%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1936      | 63.92%  |
| 1     | 852       | 28.13%  |
| 2     | 214       | 7.07%   |
| 3     | 24        | 0.79%   |
| 4     | 2         | 0.07%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 405       | 30.82%  |
| Graphics card            | 289       | 21.99%  |
| Chipcard                 | 173       | 13.17%  |
| Net/wireless             | 156       | 11.87%  |
| Multimedia controller    | 95        | 7.23%   |
| Storage                  | 44        | 3.35%   |
| Modem                    | 38        | 2.89%   |
| Bluetooth                | 33        | 2.51%   |
| Sound                    | 15        | 1.14%   |
| Communication controller | 14        | 1.07%   |
| Flash memory             | 13        | 0.99%   |
| Camera                   | 13        | 0.99%   |
| Net/ethernet             | 8         | 0.61%   |
| Card reader              | 6         | 0.46%   |
| Network                  | 4         | 0.3%    |
| Storage/nvme             | 2         | 0.15%   |
| Storage/ide              | 2         | 0.15%   |
| Dvb card                 | 2         | 0.15%   |
| Unclassified device      | 1         | 0.08%   |
| Storage/ata              | 1         | 0.08%   |

