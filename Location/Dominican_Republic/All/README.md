Linux in Dominican Republic - Tested Hardware & Statistics
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Dominican Republic.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Dominican_Republic/Desktop/README.md) and [notebooks](/Location/Dominican_Republic/Notebook/README.md).

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

Total: 265

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [4434600249](https://linux-hardware.org/?probe=4434600249) | Jan 01, 2024 |
| HP            | ProBook 11 G2               | Notebook    | [6cf8228f10](https://linux-hardware.org/?probe=6cf8228f10) | Dec 31, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [3ad144c68e](https://linux-hardware.org/?probe=3ad144c68e) | Dec 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [03b1209523](https://linux-hardware.org/?probe=03b1209523) | Dec 24, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b7f3ca9ba4](https://linux-hardware.org/?probe=b7f3ca9ba4) | Dec 23, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [972b407abc](https://linux-hardware.org/?probe=972b407abc) | Dec 22, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [e13dae2abd](https://linux-hardware.org/?probe=e13dae2abd) | Dec 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [176fc09667](https://linux-hardware.org/?probe=176fc09667) | Dec 08, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f26cee0fe0](https://linux-hardware.org/?probe=f26cee0fe0) | Dec 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbabf31d17](https://linux-hardware.org/?probe=cbabf31d17) | Dec 07, 2023 |
| HP            | 18E5                        | Desktop     | [7b54dc44b4](https://linux-hardware.org/?probe=7b54dc44b4) | Dec 06, 2023 |
| Dell          | Latitude E6420              | Notebook    | [dab1a90459](https://linux-hardware.org/?probe=dab1a90459) | Nov 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [5e4b279442](https://linux-hardware.org/?probe=5e4b279442) | Nov 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [2db8bb3ceb](https://linux-hardware.org/?probe=2db8bb3ceb) | Nov 14, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [547c61e762](https://linux-hardware.org/?probe=547c61e762) | Nov 06, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f23e44229f](https://linux-hardware.org/?probe=f23e44229f) | Nov 03, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [346fad17ff](https://linux-hardware.org/?probe=346fad17ff) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [481d6c83fb](https://linux-hardware.org/?probe=481d6c83fb) | Oct 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 5th Ge... | Convertible | [f1b1a4603c](https://linux-hardware.org/?probe=f1b1a4603c) | Oct 25, 2023 |
| LG Electro... | 17ZT90P-G.AX33U1            | Notebook    | [0d53262cff](https://linux-hardware.org/?probe=0d53262cff) | Oct 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [6fdc093168](https://linux-hardware.org/?probe=6fdc093168) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d14e5830b2](https://linux-hardware.org/?probe=d14e5830b2) | Oct 16, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [02958738fb](https://linux-hardware.org/?probe=02958738fb) | Oct 14, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [305679af22](https://linux-hardware.org/?probe=305679af22) | Sep 14, 2023 |
| Dell          | Latitude E7440              | Notebook    | [7813372525](https://linux-hardware.org/?probe=7813372525) | Sep 11, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [74e5f6b8a5](https://linux-hardware.org/?probe=74e5f6b8a5) | Sep 08, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [d4df00af33](https://linux-hardware.org/?probe=d4df00af33) | Sep 08, 2023 |
| Dell          | XPS M1330                   | Notebook    | [ce3d41b222](https://linux-hardware.org/?probe=ce3d41b222) | Aug 27, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [945643bffa](https://linux-hardware.org/?probe=945643bffa) | Aug 16, 2023 |
| Dell          | Latitude E7250              | Notebook    | [7418a0dc06](https://linux-hardware.org/?probe=7418a0dc06) | Aug 12, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [522acc7a8e](https://linux-hardware.org/?probe=522acc7a8e) | Aug 02, 2023 |
| Dell          | Latitude 5590               | Notebook    | [466fdce7aa](https://linux-hardware.org/?probe=466fdce7aa) | Aug 01, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [e50470a456](https://linux-hardware.org/?probe=e50470a456) | Jul 22, 2023 |
| Acer          | AN515-44                    | Notebook    | [171bd20f26](https://linux-hardware.org/?probe=171bd20f26) | Jul 19, 2023 |
| Acer          | AN515-44                    | Notebook    | [c40876ce5f](https://linux-hardware.org/?probe=c40876ce5f) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ebed32abef](https://linux-hardware.org/?probe=ebed32abef) | Jul 19, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [25f8458274](https://linux-hardware.org/?probe=25f8458274) | Jul 17, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [f687b7efe2](https://linux-hardware.org/?probe=f687b7efe2) | Jul 16, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [287b00885d](https://linux-hardware.org/?probe=287b00885d) | Jul 02, 2023 |
| HP            | 21EF                        | Desktop     | [6022eb31ff](https://linux-hardware.org/?probe=6022eb31ff) | Jun 21, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [93e28671fa](https://linux-hardware.org/?probe=93e28671fa) | Jun 18, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [da1f33a87b](https://linux-hardware.org/?probe=da1f33a87b) | Jun 11, 2023 |
| Dell          | Latitude E6540              | Notebook    | [85520c9a0b](https://linux-hardware.org/?probe=85520c9a0b) | Jun 08, 2023 |
| Dell          | Latitude E6540              | Notebook    | [30f20f78ac](https://linux-hardware.org/?probe=30f20f78ac) | Jun 08, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [f9103674dc](https://linux-hardware.org/?probe=f9103674dc) | May 22, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [19416d3973](https://linux-hardware.org/?probe=19416d3973) | May 21, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [378acd7874](https://linux-hardware.org/?probe=378acd7874) | May 09, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [534af3636c](https://linux-hardware.org/?probe=534af3636c) | May 09, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [dd238f7e60](https://linux-hardware.org/?probe=dd238f7e60) | May 04, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [ea7f9b7eef](https://linux-hardware.org/?probe=ea7f9b7eef) | Apr 20, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [d3526466e8](https://linux-hardware.org/?probe=d3526466e8) | Apr 20, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [b7e04c4c41](https://linux-hardware.org/?probe=b7e04c4c41) | Apr 12, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [904fc9e194](https://linux-hardware.org/?probe=904fc9e194) | Apr 07, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [4b7801e829](https://linux-hardware.org/?probe=4b7801e829) | Mar 22, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [258c8aa62c](https://linux-hardware.org/?probe=258c8aa62c) | Mar 20, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [dca0487261](https://linux-hardware.org/?probe=dca0487261) | Mar 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [7a44108d05](https://linux-hardware.org/?probe=7a44108d05) | Mar 16, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [0b91c54846](https://linux-hardware.org/?probe=0b91c54846) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [4687219ca3](https://linux-hardware.org/?probe=4687219ca3) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [687328ccb0](https://linux-hardware.org/?probe=687328ccb0) | Mar 06, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [b12a53ec1e](https://linux-hardware.org/?probe=b12a53ec1e) | Mar 06, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [0620aa7f6f](https://linux-hardware.org/?probe=0620aa7f6f) | Feb 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [df734c276f](https://linux-hardware.org/?probe=df734c276f) | Feb 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [00e573a880](https://linux-hardware.org/?probe=00e573a880) | Feb 23, 2023 |
| HP            | ProBook 4520s               | Notebook    | [8192287499](https://linux-hardware.org/?probe=8192287499) | Feb 19, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [6de5bc549f](https://linux-hardware.org/?probe=6de5bc549f) | Jan 29, 2023 |
| Google        | Kip                         | Notebook    | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | Notebook    | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| Lenovo        | ThinkPad T420s 41732BU      | Notebook    | [fb42067a32](https://linux-hardware.org/?probe=fb42067a32) | Jan 20, 2023 |
| Google        | Kip                         | Notebook    | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4d2e9f3ee4](https://linux-hardware.org/?probe=4d2e9f3ee4) | Jan 16, 2023 |
| HP            | 18E5                        | Desktop     | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| Dell          | XPS M1330                   | Notebook    | [e3d66114f6](https://linux-hardware.org/?probe=e3d66114f6) | Jan 10, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9fd9875465](https://linux-hardware.org/?probe=9fd9875465) | Dec 23, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Dell          | OptiPlex 3020               | Desktop     | [2adcd09348](https://linux-hardware.org/?probe=2adcd09348) | Nov 25, 2022 |
| Lenovo        | ThinkPad T420s 41732BU      | Notebook    | [ac7791c167](https://linux-hardware.org/?probe=ac7791c167) | Nov 24, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [1a1f5f8d90](https://linux-hardware.org/?probe=1a1f5f8d90) | Nov 22, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [b2772ed1b3](https://linux-hardware.org/?probe=b2772ed1b3) | Nov 22, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | Notebook    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| Dell          | Latitude 5590               | Notebook    | [bbb332cf90](https://linux-hardware.org/?probe=bbb332cf90) | Nov 11, 2022 |
| Dell          | 0VNP2H A00                  | Desktop     | [dff6013531](https://linux-hardware.org/?probe=dff6013531) | Nov 09, 2022 |
| Eluktronic... | P670RE3                     | Notebook    | [d96ecdf7ab](https://linux-hardware.org/?probe=d96ecdf7ab) | Nov 08, 2022 |
| MSI           | GE62 6QC                    | Notebook    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [ff4216edcd](https://linux-hardware.org/?probe=ff4216edcd) | Oct 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [240d883d49](https://linux-hardware.org/?probe=240d883d49) | Oct 12, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Dell          | Latitude 2110               | Notebook    | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| Dell          | Latitude E6540              | Notebook    | [08bd609dbe](https://linux-hardware.org/?probe=08bd609dbe) | Sep 20, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [55cf772a79](https://linux-hardware.org/?probe=55cf772a79) | Sep 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [9e48793165](https://linux-hardware.org/?probe=9e48793165) | Aug 18, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [2b09076619](https://linux-hardware.org/?probe=2b09076619) | Jul 30, 2022 |
| Dell          | OptiPlex 780                | Desktop     | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| Dell          | Latitude E5440              | Notebook    | [c8e68471c1](https://linux-hardware.org/?probe=c8e68471c1) | Jul 16, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [9cd0caeff2](https://linux-hardware.org/?probe=9cd0caeff2) | Jul 14, 2022 |
| ECS           | ClassMate                   | Notebook    | [c86fa72fe1](https://linux-hardware.org/?probe=c86fa72fe1) | Jun 13, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [fb6db84371](https://linux-hardware.org/?probe=fb6db84371) | Jun 11, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [578aee86ed](https://linux-hardware.org/?probe=578aee86ed) | May 27, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e1e9853d49](https://linux-hardware.org/?probe=e1e9853d49) | May 26, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [62c1081de8](https://linux-hardware.org/?probe=62c1081de8) | May 23, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3e9f067939](https://linux-hardware.org/?probe=3e9f067939) | May 13, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [c72447a3ea](https://linux-hardware.org/?probe=c72447a3ea) | May 03, 2022 |
| TODOS INDU... | Easytouch_2022_V1           | Notebook    | [efc26220c4](https://linux-hardware.org/?probe=efc26220c4) | May 01, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [454226474b](https://linux-hardware.org/?probe=454226474b) | Apr 29, 2022 |
| Gigabyte      | Z87X-UD5 TH-CF              | Desktop     | [5dc83ea64b](https://linux-hardware.org/?probe=5dc83ea64b) | Apr 24, 2022 |
| Unknown       | K8M800-8237                 | Desktop     | [791e4eeaae](https://linux-hardware.org/?probe=791e4eeaae) | Apr 07, 2022 |
| Unknown       | K8M800-8237                 | Desktop     | [3447b4c67a](https://linux-hardware.org/?probe=3447b4c67a) | Apr 07, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [9d5011b41d](https://linux-hardware.org/?probe=9d5011b41d) | Mar 23, 2022 |
| ASUSTek       | K53E                        | Notebook    | [3a0af085ae](https://linux-hardware.org/?probe=3a0af085ae) | Mar 17, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [726633bbcc](https://linux-hardware.org/?probe=726633bbcc) | Feb 18, 2022 |
| Samsung       | 930QCG                      | Convertible | [fb417d6589](https://linux-hardware.org/?probe=fb417d6589) | Feb 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [2322337991](https://linux-hardware.org/?probe=2322337991) | Feb 15, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [507f27294e](https://linux-hardware.org/?probe=507f27294e) | Feb 15, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b32bc24608](https://linux-hardware.org/?probe=b32bc24608) | Jan 26, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [53e23140c0](https://linux-hardware.org/?probe=53e23140c0) | Jan 23, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [563f0e150e](https://linux-hardware.org/?probe=563f0e150e) | Dec 31, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [ea7511ce8d](https://linux-hardware.org/?probe=ea7511ce8d) | Dec 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9b89720cb4](https://linux-hardware.org/?probe=9b89720cb4) | Dec 14, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [b32fd5f07f](https://linux-hardware.org/?probe=b32fd5f07f) | Dec 07, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [d1843d03ba](https://linux-hardware.org/?probe=d1843d03ba) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | Notebook    | [a77255409f](https://linux-hardware.org/?probe=a77255409f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | Notebook    | [ef02c2fb6c](https://linux-hardware.org/?probe=ef02c2fb6c) | Dec 02, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [9164883468](https://linux-hardware.org/?probe=9164883468) | Nov 27, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [b137bf3459](https://linux-hardware.org/?probe=b137bf3459) | Nov 27, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8d3228452b](https://linux-hardware.org/?probe=8d3228452b) | Nov 20, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | Notebook    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [fb31c8d088](https://linux-hardware.org/?probe=fb31c8d088) | Oct 23, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| Dell          | Latitude E6410              | Notebook    | [bd65cdda08](https://linux-hardware.org/?probe=bd65cdda08) | Oct 08, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [7b2dcf44d9](https://linux-hardware.org/?probe=7b2dcf44d9) | Sep 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5038083b91](https://linux-hardware.org/?probe=5038083b91) | Sep 07, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [e402a0b407](https://linux-hardware.org/?probe=e402a0b407) | Aug 31, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [24bfc2b04a](https://linux-hardware.org/?probe=24bfc2b04a) | Aug 26, 2021 |
| HP            | 8265                        | Desktop     | [9a7e706a6b](https://linux-hardware.org/?probe=9a7e706a6b) | Aug 07, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [8242b46551](https://linux-hardware.org/?probe=8242b46551) | Jul 29, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [7fc508d633](https://linux-hardware.org/?probe=7fc508d633) | Jul 19, 2021 |
| Google        | Winky                       | Notebook    | [696230b066](https://linux-hardware.org/?probe=696230b066) | Jul 14, 2021 |
| Google        | Winky                       | Notebook    | [6048ac2ff9](https://linux-hardware.org/?probe=6048ac2ff9) | Jul 14, 2021 |
| Acer          | Aspire 1810TZ               | Notebook    | [3ed828bab0](https://linux-hardware.org/?probe=3ed828bab0) | Jul 11, 2021 |
| Acer          | Aspire 1810TZ               | Notebook    | [9b650cfab3](https://linux-hardware.org/?probe=9b650cfab3) | Jul 11, 2021 |
| Dell          | Latitude E6420              | Notebook    | [fe42f53d85](https://linux-hardware.org/?probe=fe42f53d85) | Jul 11, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [772842d291](https://linux-hardware.org/?probe=772842d291) | Jul 06, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [891b06178e](https://linux-hardware.org/?probe=891b06178e) | Jun 29, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [cc6035ae99](https://linux-hardware.org/?probe=cc6035ae99) | Jun 28, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [25dc027ef1](https://linux-hardware.org/?probe=25dc027ef1) | Jun 26, 2021 |
| Dell          | Latitude E6530              | Notebook    | [fda4879b12](https://linux-hardware.org/?probe=fda4879b12) | Jun 19, 2021 |
| Dell          | Latitude E6530              | Notebook    | [40566262f5](https://linux-hardware.org/?probe=40566262f5) | Jun 11, 2021 |
| Dell          | Latitude E6430              | Notebook    | [9ec2685f9d](https://linux-hardware.org/?probe=9ec2685f9d) | Jun 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [6098210314](https://linux-hardware.org/?probe=6098210314) | Jun 04, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5343885c32](https://linux-hardware.org/?probe=5343885c32) | May 17, 2021 |
| Dell          | Inspiron 3541               | Notebook    | [2170036527](https://linux-hardware.org/?probe=2170036527) | May 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d310246b09](https://linux-hardware.org/?probe=d310246b09) | Apr 30, 2021 |
| Dell          | Latitude D830               | Notebook    | [f6f0884fca](https://linux-hardware.org/?probe=f6f0884fca) | Apr 28, 2021 |
| Dell          | Latitude E6540              | Notebook    | [522d36a07e](https://linux-hardware.org/?probe=522d36a07e) | Apr 21, 2021 |
| Dell          | Latitude E6540              | Notebook    | [3c76496221](https://linux-hardware.org/?probe=3c76496221) | Apr 21, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [dc8b47f73d](https://linux-hardware.org/?probe=dc8b47f73d) | Feb 14, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [4adcccb57c](https://linux-hardware.org/?probe=4adcccb57c) | Feb 14, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [96d33743db](https://linux-hardware.org/?probe=96d33743db) | Jan 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [2cf1c789ec](https://linux-hardware.org/?probe=2cf1c789ec) | Dec 29, 2020 |
| Lenovo        | ThinkPad E470 20H1006DUS    | Notebook    | [3c51b58a24](https://linux-hardware.org/?probe=3c51b58a24) | Dec 14, 2020 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [f18b7b439b](https://linux-hardware.org/?probe=f18b7b439b) | Dec 05, 2020 |
| Fujitsu       | LIFEBOOK AH562              | Notebook    | [68c670f9e0](https://linux-hardware.org/?probe=68c670f9e0) | Dec 01, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [012580c2a7](https://linux-hardware.org/?probe=012580c2a7) | Nov 10, 2020 |
| HP            | Notebook                    | Notebook    | [5176e73c5a](https://linux-hardware.org/?probe=5176e73c5a) | Oct 27, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [d6729d6c6a](https://linux-hardware.org/?probe=d6729d6c6a) | Oct 17, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [907bc464e9](https://linux-hardware.org/?probe=907bc464e9) | Oct 13, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [03c52e4d49](https://linux-hardware.org/?probe=03c52e4d49) | Oct 10, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | Notebook    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| HP            | 3647h                       | Desktop     | [5788758b90](https://linux-hardware.org/?probe=5788758b90) | Oct 08, 2020 |
| Dell          | 0MM599                      | Desktop     | [fce90bd449](https://linux-hardware.org/?probe=fce90bd449) | Oct 06, 2020 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fd73b699f6](https://linux-hardware.org/?probe=fd73b699f6) | Oct 05, 2020 |
| Dell          | Latitude D620               | Notebook    | [3832d0c33e](https://linux-hardware.org/?probe=3832d0c33e) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [80611690cf](https://linux-hardware.org/?probe=80611690cf) | Sep 13, 2020 |
| Dell          | Latitude D620               | Notebook    | [d14cb277b7](https://linux-hardware.org/?probe=d14cb277b7) | Sep 12, 2020 |
| HP            | ProBook 6470b               | Notebook    | [c622e7298d](https://linux-hardware.org/?probe=c622e7298d) | Sep 07, 2020 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [9b34b0a6c3](https://linux-hardware.org/?probe=9b34b0a6c3) | Sep 03, 2020 |
| Dell          | Vostro 5471                 | Notebook    | [6d24c75bcf](https://linux-hardware.org/?probe=6d24c75bcf) | Sep 03, 2020 |
| MSI           | H81M-E33                    | Desktop     | [d24cd3858d](https://linux-hardware.org/?probe=d24cd3858d) | Aug 29, 2020 |
| Nuvision      | L1W6_I1101_G Reserved       | Notebook    | [b3e73aa9ba](https://linux-hardware.org/?probe=b3e73aa9ba) | Aug 29, 2020 |
| MSI           | H81M-E33                    | Desktop     | [9eda45f755](https://linux-hardware.org/?probe=9eda45f755) | Aug 20, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [d7d672869f](https://linux-hardware.org/?probe=d7d672869f) | Aug 16, 2020 |
| MSI           | H81M-E33                    | Desktop     | [ba3577fb00](https://linux-hardware.org/?probe=ba3577fb00) | Aug 14, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [081a2c3e4c](https://linux-hardware.org/?probe=081a2c3e4c) | Aug 03, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8eb28a49c4](https://linux-hardware.org/?probe=8eb28a49c4) | Aug 03, 2020 |
| MSI           | H81M-E33                    | Desktop     | [6bedf88c28](https://linux-hardware.org/?probe=6bedf88c28) | Jul 30, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [fcbd102a50](https://linux-hardware.org/?probe=fcbd102a50) | Jul 30, 2020 |
| MSI           | B350 GAMING PLUS            | Desktop     | [ca22d3b169](https://linux-hardware.org/?probe=ca22d3b169) | Jul 24, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [4877877772](https://linux-hardware.org/?probe=4877877772) | Jul 04, 2020 |
| Dell          | Vostro A860                 | Notebook    | [16ded4e283](https://linux-hardware.org/?probe=16ded4e283) | Jun 28, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [093c4d226c](https://linux-hardware.org/?probe=093c4d226c) | Jun 28, 2020 |
| MSI           | H81M-E33                    | Desktop     | [2d531766ab](https://linux-hardware.org/?probe=2d531766ab) | Jun 26, 2020 |
| HP            | 250 G3                      | Notebook    | [1862b881c0](https://linux-hardware.org/?probe=1862b881c0) | Jun 23, 2020 |
| Acer          | Aspire one 1-431            | Notebook    | [80f65d1ab4](https://linux-hardware.org/?probe=80f65d1ab4) | Jun 23, 2020 |
| Biostar       | G41D3C                      | Desktop     | [15959c0828](https://linux-hardware.org/?probe=15959c0828) | Jun 15, 2020 |
| Acer          | Aspire one 1-431            | Notebook    | [5994ea3a38](https://linux-hardware.org/?probe=5994ea3a38) | Jun 09, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [4003a55819](https://linux-hardware.org/?probe=4003a55819) | Jun 03, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [131d3a17f3](https://linux-hardware.org/?probe=131d3a17f3) | May 30, 2020 |
| Dell          | Vostro A860                 | Notebook    | [35d08abb65](https://linux-hardware.org/?probe=35d08abb65) | May 20, 2020 |
| Dell          | Latitude E6410              | Notebook    | [4e98eb67c5](https://linux-hardware.org/?probe=4e98eb67c5) | May 19, 2020 |
| Dell          | Latitude 3340               | Notebook    | [a8795064a1](https://linux-hardware.org/?probe=a8795064a1) | May 18, 2020 |
| Dell          | Latitude 3340               | Notebook    | [a07d882043](https://linux-hardware.org/?probe=a07d882043) | May 18, 2020 |
| Dell          | Latitude E6430              | Notebook    | [4316261d97](https://linux-hardware.org/?probe=4316261d97) | May 15, 2020 |
| Dell          | Latitude E6430              | Notebook    | [eef205a77d](https://linux-hardware.org/?probe=eef205a77d) | May 14, 2020 |
| HP            | G60                         | Notebook    | [90ec25f151](https://linux-hardware.org/?probe=90ec25f151) | May 13, 2020 |
| HP            | G60                         | Notebook    | [0b84216baf](https://linux-hardware.org/?probe=0b84216baf) | May 13, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [1b33a3d155](https://linux-hardware.org/?probe=1b33a3d155) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [5a74b9f950](https://linux-hardware.org/?probe=5a74b9f950) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [31e36437f4](https://linux-hardware.org/?probe=31e36437f4) | May 03, 2020 |
| Dell          | Latitude E6410              | Notebook    | [125cc5d7fd](https://linux-hardware.org/?probe=125cc5d7fd) | Apr 26, 2020 |
| HP            | 3031h                       | Desktop     | [0278ac4043](https://linux-hardware.org/?probe=0278ac4043) | Apr 07, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [87496c419f](https://linux-hardware.org/?probe=87496c419f) | Apr 07, 2020 |
| Dell          | 0WG864                      | Desktop     | [b7c74749f8](https://linux-hardware.org/?probe=b7c74749f8) | Mar 30, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [860893085c](https://linux-hardware.org/?probe=860893085c) | Mar 29, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [48e8186c4f](https://linux-hardware.org/?probe=48e8186c4f) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [080f6bbb80](https://linux-hardware.org/?probe=080f6bbb80) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [740334eed7](https://linux-hardware.org/?probe=740334eed7) | Mar 28, 2020 |
| Dell          | Latitude 3330               | Notebook    | [4033fca5eb](https://linux-hardware.org/?probe=4033fca5eb) | Mar 22, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [44fe9bdc7d](https://linux-hardware.org/?probe=44fe9bdc7d) | Mar 20, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [970faeadaf](https://linux-hardware.org/?probe=970faeadaf) | Mar 19, 2020 |
| HP            | 3031h                       | Desktop     | [3b10a92ee2](https://linux-hardware.org/?probe=3b10a92ee2) | Mar 19, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [4f152e3015](https://linux-hardware.org/?probe=4f152e3015) | Mar 06, 2020 |
| Dell          | 06D7TR A00                  | Desktop     | [4775efe228](https://linux-hardware.org/?probe=4775efe228) | Feb 27, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [185bf79f49](https://linux-hardware.org/?probe=185bf79f49) | Feb 08, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [cb7950841c](https://linux-hardware.org/?probe=cb7950841c) | Feb 07, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [3212549df1](https://linux-hardware.org/?probe=3212549df1) | Feb 05, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [661a8243a3](https://linux-hardware.org/?probe=661a8243a3) | Feb 01, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [ee353d9346](https://linux-hardware.org/?probe=ee353d9346) | Feb 01, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [51c3c0bb31](https://linux-hardware.org/?probe=51c3c0bb31) | Jan 07, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [4df330ed80](https://linux-hardware.org/?probe=4df330ed80) | Jan 07, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [a61df97ccd](https://linux-hardware.org/?probe=a61df97ccd) | Dec 19, 2019 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [4437a2deed](https://linux-hardware.org/?probe=4437a2deed) | Dec 18, 2019 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [edddb5eb5b](https://linux-hardware.org/?probe=edddb5eb5b) | Dec 18, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [e4a03527b5](https://linux-hardware.org/?probe=e4a03527b5) | Dec 11, 2019 |
| Toshiba       | Satellite C55-A             | Notebook    | [a760ea9cb2](https://linux-hardware.org/?probe=a760ea9cb2) | Nov 14, 2019 |
| Toshiba       | Satellite C55-A             | Notebook    | [b2477d7154](https://linux-hardware.org/?probe=b2477d7154) | Nov 07, 2019 |
| Gigabyte      | B450 AORUS M                | Desktop     | [628a2983df](https://linux-hardware.org/?probe=628a2983df) | Nov 05, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [cb7b5a4d2e](https://linux-hardware.org/?probe=cb7b5a4d2e) | Oct 13, 2019 |
| Dell          | Latitude E6430              | Notebook    | [49d71b26e7](https://linux-hardware.org/?probe=49d71b26e7) | Oct 08, 2019 |
| Dell          | Latitude E6430              | Notebook    | [b3ef7b4357](https://linux-hardware.org/?probe=b3ef7b4357) | Oct 06, 2019 |
| Dell          | 0M132G A00                  | Desktop     | [b79e419f05](https://linux-hardware.org/?probe=b79e419f05) | Aug 24, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [9a7d44bf28](https://linux-hardware.org/?probe=9a7d44bf28) | Aug 15, 2019 |
| HP            | Pavilion ze2000 (EC201UA... | Notebook    | [572baa05f4](https://linux-hardware.org/?probe=572baa05f4) | Jun 15, 2019 |
| HP            | 3397                        | Desktop     | [24770f4baf](https://linux-hardware.org/?probe=24770f4baf) | Jun 06, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [412e4da0ce](https://linux-hardware.org/?probe=412e4da0ce) | May 21, 2019 |
| HP            | 3396                        | Desktop     | [46d189dc80](https://linux-hardware.org/?probe=46d189dc80) | May 20, 2019 |
| Lenovo        | G40-70 20369                | Notebook    | [1f456620db](https://linux-hardware.org/?probe=1f456620db) | May 05, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0b9c00412b](https://linux-hardware.org/?probe=0b9c00412b) | Dec 14, 2018 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [e30bc2b8f2](https://linux-hardware.org/?probe=e30bc2b8f2) | Nov 02, 2018 |
| Dell          | 0PU052                      | Desktop     | [a5f063bc44](https://linux-hardware.org/?probe=a5f063bc44) | Apr 19, 2018 |
| Dell          | 0PU052                      | Desktop     | [e8fb115c06](https://linux-hardware.org/?probe=e8fb115c06) | Jan 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 21        | 11.54%  |
| Ubuntu 18.04                 | 17        | 9.34%   |
| Ubuntu 22.04                 | 11        | 6.04%   |
| Arch Rolling                 | 10        | 5.49%   |
| OpenMandriva 4.3             | 7         | 3.85%   |
| Fedora 38                    | 6         | 3.3%    |
| OpenMandriva 4.2             | 5         | 2.75%   |
| OpenMandriva 23.03           | 4         | 2.2%    |
| Fedora 37                    | 4         | 2.2%    |
| Fedora 36                    | 4         | 2.2%    |
| Zorin 16                     | 3         | 1.65%   |
| Manjaro                      | 3         | 1.65%   |
| Linux Mint 20.3              | 3         | 1.65%   |
| Kali 2023.3                  | 3         | 1.65%   |
| Fedora 34                    | 3         | 1.65%   |
| Debian 11                    | 3         | 1.65%   |
| Arch                         | 3         | 1.65%   |
| Ubuntu 22.10                 | 2         | 1.1%    |
| Ubuntu 21.10                 | 2         | 1.1%    |
| Pop!_OS 20.10                | 2         | 1.1%    |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.1%    |
| OpenMandriva 23.08           | 2         | 1.1%    |
| Linux Mint 21                | 2         | 1.1%    |
| Linux Mint 20.1              | 2         | 1.1%    |
| Linux Mint 19.3              | 2         | 1.1%    |
| KDE neon 22.04               | 2         | 1.1%    |
| Fedora 39                    | 2         | 1.1%    |
| Fedora 33                    | 2         | 1.1%    |
| ArcoLinux Rolling            | 2         | 1.1%    |
| Xubuntu 19.10                | 1         | 0.55%   |
| Xubuntu 18.04                | 1         | 0.55%   |
| Void Linux Rolling           | 1         | 0.55%   |
| Ubuntu MATE 22.04            | 1         | 0.55%   |
| Ubuntu Budgie 22.04          | 1         | 0.55%   |
| Ubuntu Budgie 21.10          | 1         | 0.55%   |
| Ubuntu Budgie 20.04          | 1         | 0.55%   |
| Ubuntu 23.04                 | 1         | 0.55%   |
| Ubuntu 21.04                 | 1         | 0.55%   |
| Ubuntu 19.10                 | 1         | 0.55%   |
| Ubuntu 19.04                 | 1         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 54        | 30.86%  |
| Fedora        | 21        | 12%     |
| OpenMandriva  | 20        | 11.43%  |
| Linux Mint    | 13        | 7.43%   |
| Arch          | 13        | 7.43%   |
| Manjaro       | 8         | 4.57%   |
| Pop!_OS       | 5         | 2.86%   |
| Kali          | 5         | 2.86%   |
| Debian        | 5         | 2.86%   |
| Zorin         | 3         | 1.71%   |
| Ubuntu Budgie | 3         | 1.71%   |
| KDE neon      | 3         | 1.71%   |
| Clear Linux   | 3         | 1.71%   |
| Xubuntu       | 2         | 1.14%   |
| openSUSE      | 2         | 1.14%   |
| ArcoLinux     | 2         | 1.14%   |
| Void Linux    | 1         | 0.57%   |
| Ubuntu MATE   | 1         | 0.57%   |
| Solus         | 1         | 0.57%   |
| ROSA          | 1         | 0.57%   |
| MX            | 1         | 0.57%   |
| Lubuntu       | 1         | 0.57%   |
| LMDE          | 1         | 0.57%   |
| Kubuntu       | 1         | 0.57%   |
| Endless       | 1         | 0.57%   |
| Elementary    | 1         | 0.57%   |
| CentOS        | 1         | 0.57%   |
| BlackPanther  | 1         | 0.57%   |
| Archcraft     | 1         | 0.57%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 7         | 3.48%   |
| 5.4.0-48-generic         | 4         | 1.99%   |
| 5.4.0-42-generic         | 4         | 1.99%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.99%   |
| 6.2.6-desktop-1omv2390   | 3         | 1.49%   |
| 5.19.0-46-generic        | 3         | 1.49%   |
| 5.15.0-53-generic        | 3         | 1.49%   |
| 5.13.0-22-generic        | 3         | 1.49%   |
| 6.5.0-kali3-amd64        | 2         | 1%      |
| 6.5.0-kali2-amd64        | 2         | 1%      |
| 6.4.8-desktop-2omv2390   | 2         | 1%      |
| 6.1.1-desktop-1omv2290   | 2         | 1%      |
| 5.4.0-77-generic         | 2         | 1%      |
| 5.4.0-52-generic         | 2         | 1%      |
| 5.4.0-33-generic         | 2         | 1%      |
| 5.3.0-51-generic         | 2         | 1%      |
| 5.3.0-46-generic         | 2         | 1%      |
| 5.3.0-42-generic         | 2         | 1%      |
| 5.19.0-32-generic        | 2         | 1%      |
| 5.15.0-76-generic        | 2         | 1%      |
| 5.15.0-58-generic        | 2         | 1%      |
| 5.15.0-50-generic        | 2         | 1%      |
| 5.15.0-41-generic        | 2         | 1%      |
| 5.11.0-40-generic        | 2         | 1%      |
| 5.11.0-25-generic        | 2         | 1%      |
| 5.0.0-32-generic         | 2         | 1%      |
| 6.6.8-200.fc39.x86_64    | 1         | 0.5%    |
| 6.6.8-2-MANJARO          | 1         | 0.5%    |
| 6.6.6-200.fc39.x86_64    | 1         | 0.5%    |
| 6.6.2-desktop-1omv2390   | 1         | 0.5%    |
| 6.6.1-arch1-1            | 1         | 0.5%    |
| 6.5.9-zen2-1-zen         | 1         | 0.5%    |
| 6.5.8-200.fc38.x86_64    | 1         | 0.5%    |
| 6.5.7-zen1-1-zen         | 1         | 0.5%    |
| 6.5.7-200.fc38.x86_64    | 1         | 0.5%    |
| 6.5.6-200.fc38.x86_64    | 1         | 0.5%    |
| 6.4.6-arch1-1            | 1         | 0.5%    |
| 6.4.15-200.fc38.x86_64   | 1         | 0.5%    |
| 6.4.14-200.fc38.x86_64   | 1         | 0.5%    |
| 6.3.7-x64v2-xanmod1-1    | 1         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 13.23%  |
| 5.15.0  | 17        | 8.99%   |
| 5.13.0  | 10        | 5.29%   |
| 5.3.0   | 9         | 4.76%   |
| 5.19.0  | 8         | 4.23%   |
| 5.11.0  | 8         | 4.23%   |
| 5.16.7  | 7         | 3.7%    |
| 4.15.0  | 6         | 3.17%   |
| 5.0.0   | 5         | 2.65%   |
| 6.5.0   | 4         | 2.12%   |
| 5.10.14 | 4         | 2.12%   |
| 5.10.0  | 4         | 2.12%   |
| 6.2.6   | 3         | 1.59%   |
| 6.6.8   | 2         | 1.06%   |
| 6.5.7   | 2         | 1.06%   |
| 6.4.8   | 2         | 1.06%   |
| 6.3.7   | 2         | 1.06%   |
| 6.1.1   | 2         | 1.06%   |
| 5.7.7   | 2         | 1.06%   |
| 4.19.0  | 2         | 1.06%   |
| 4.18.0  | 2         | 1.06%   |
| 6.6.6   | 1         | 0.53%   |
| 6.6.2   | 1         | 0.53%   |
| 6.6.1   | 1         | 0.53%   |
| 6.5.9   | 1         | 0.53%   |
| 6.5.8   | 1         | 0.53%   |
| 6.5.6   | 1         | 0.53%   |
| 6.4.6   | 1         | 0.53%   |
| 6.4.15  | 1         | 0.53%   |
| 6.4.14  | 1         | 0.53%   |
| 6.2.7   | 1         | 0.53%   |
| 6.2.14  | 1         | 0.53%   |
| 6.2.12  | 1         | 0.53%   |
| 6.2.0   | 1         | 0.53%   |
| 6.1.5   | 1         | 0.53%   |
| 6.1.18  | 1         | 0.53%   |
| 6.0.6   | 1         | 0.53%   |
| 6.0.14  | 1         | 0.53%   |
| 5.9.16  | 1         | 0.53%   |
| 5.9.12  | 1         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 15.05%  |
| 5.15    | 20        | 10.75%  |
| 5.19    | 11        | 5.91%   |
| 5.13    | 11        | 5.91%   |
| 5.11    | 10        | 5.38%   |
| 5.10    | 10        | 5.38%   |
| 5.3     | 9         | 4.84%   |
| 6.5     | 8         | 4.3%    |
| 6.2     | 7         | 3.76%   |
| 5.16    | 7         | 3.76%   |
| 5.0     | 6         | 3.23%   |
| 4.15    | 6         | 3.23%   |
| 6.6     | 5         | 2.69%   |
| 6.4     | 5         | 2.69%   |
| 5.8     | 5         | 2.69%   |
| 6.1     | 4         | 2.15%   |
| 5.9     | 4         | 2.15%   |
| 5.18    | 4         | 2.15%   |
| 5.12    | 4         | 2.15%   |
| 4.18    | 4         | 2.15%   |
| 5.7     | 3         | 1.61%   |
| 4.19    | 3         | 1.61%   |
| 6.3     | 2         | 1.08%   |
| 6.0     | 2         | 1.08%   |
| 5.17    | 2         | 1.08%   |
| 5.1     | 2         | 1.08%   |
| 5.6     | 1         | 0.54%   |
| 5.5     | 1         | 0.54%   |
| 5.14    | 1         | 0.54%   |
| 4.9     | 1         | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 169       | 97.69%  |
| i686   | 4         | 2.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 81        | 45.76%  |
| KDE5       | 39        | 22.03%  |
| XFCE       | 16        | 9.04%   |
| Unknown    | 13        | 7.34%   |
| X-Cinnamon | 10        | 5.65%   |
| Budgie     | 5         | 2.82%   |
| KDE        | 4         | 2.26%   |
| MATE       | 3         | 1.69%   |
| LXQt       | 2         | 1.13%   |
| sway       | 1         | 0.56%   |
| LXDE       | 1         | 0.56%   |
| KDE4       | 1         | 0.56%   |
| DWM        | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 134       | 76.14%  |
| Wayland | 35        | 19.89%  |
| Unknown | 5         | 2.84%   |
| Tty     | 2         | 1.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 84        | 47.46%  |
| SDDM    | 34        | 19.21%  |
| GDM3    | 18        | 10.17%  |
| GDM     | 18        | 10.17%  |
| LightDM | 17        | 9.6%    |
| TDM     | 4         | 2.26%   |
| LY-DM   | 1         | 0.56%   |
| KDM     | 1         | 0.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 92        | 51.11%  |
| es_DO   | 52        | 28.89%  |
| Unknown | 14        | 7.78%   |
| es_ES   | 7         | 3.89%   |
| es_MX   | 5         | 2.78%   |
| C       | 5         | 2.78%   |
| en_CA   | 2         | 1.11%   |
| ru_RU   | 1         | 0.56%   |
| fr_FR   | 1         | 0.56%   |
| es_US   | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 94        | 54.02%  |
| EFI  | 80        | 45.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 120       | 67.8%   |
| Btrfs   | 25        | 14.12%  |
| Overlay | 20        | 11.3%   |
| Xfs     | 4         | 2.26%   |
| Tmpfs   | 3         | 1.69%   |
| Zfs     | 2         | 1.13%   |
| Unknown | 2         | 1.13%   |
| F2fs    | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 89        | 50%     |
| GPT     | 72        | 40.45%  |
| MBR     | 17        | 9.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 145       | 82.86%  |
| Yes       | 30        | 17.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 122       | 69.32%  |
| Yes       | 54        | 30.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 53        | 30.64%  |
| Hewlett-Packard     | 29        | 16.76%  |
| Lenovo              | 20        | 11.56%  |
| ASUSTek Computer    | 12        | 6.94%   |
| Gigabyte Technology | 11        | 6.36%   |
| Apple               | 6         | 3.47%   |
| Acer                | 6         | 3.47%   |
| Unknown             | 6         | 3.47%   |
| MSI                 | 4         | 2.31%   |
| Samsung Electronics | 3         | 1.73%   |
| ASRock              | 3         | 1.73%   |
| VTEX                | 2         | 1.16%   |
| Google              | 2         | 1.16%   |
| EVOO                | 2         | 1.16%   |
| Toshiba             | 1         | 0.58%   |
| TODOS INDUSTRIAL    | 1         | 0.58%   |
| SAELITE             | 1         | 0.58%   |
| Nuvision            | 1         | 0.58%   |
| Microsoft           | 1         | 0.58%   |
| LG Electronics      | 1         | 0.58%   |
| Fujitsu             | 1         | 0.58%   |
| Foxconn             | 1         | 0.58%   |
| Eluktronics         | 1         | 0.58%   |
| ECS                 | 1         | 0.58%   |
| Chuwi               | 1         | 0.58%   |
| Biostar             | 1         | 0.58%   |
| AZW                 | 1         | 0.58%   |
| AMI                 | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 6         | 3.47%   |
| Gigabyte GA-78LMT-USB3 6.0                        | 3         | 1.73%   |
| VTEX NOTEBOOK                                     | 2         | 1.16%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 2         | 1.16%   |
| HP Pavilion Notebook                              | 2         | 1.16%   |
| HP Laptop 15-dy1xxx                               | 2         | 1.16%   |
| HP EliteBook 8460p                                | 2         | 1.16%   |
| EVOO EV-C-116-7                                   | 2         | 1.16%   |
| Dell OptiPlex 990                                 | 2         | 1.16%   |
| Dell OptiPlex 9020                                | 2         | 1.16%   |
| Dell OptiPlex 390                                 | 2         | 1.16%   |
| Dell OptiPlex 3010                                | 2         | 1.16%   |
| Dell Latitude E6540                               | 2         | 1.16%   |
| Dell Latitude E6430                               | 2         | 1.16%   |
| Dell Latitude E6420                               | 2         | 1.16%   |
| Dell Latitude E6410                               | 2         | 1.16%   |
| Dell Latitude 5590                                | 2         | 1.16%   |
| Dell Inspiron 5570                                | 2         | 1.16%   |
| Dell Inspiron 5555                                | 2         | 1.16%   |
| Apple MacBookPro8,1                               | 2         | 1.16%   |
| Toshiba Satellite C55-A                           | 1         | 0.58%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 0.58%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 0.58%   |
| Samsung 930QCG                                    | 1         | 0.58%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 0.58%   |
| SAELITE ES1AU11                                   | 1         | 0.58%   |
| Nuvision NES11                                    | 1         | 0.58%   |
| MSI MS-7A34                                       | 1         | 0.58%   |
| MSI MS-7817                                       | 1         | 0.58%   |
| MSI GE62 6QC                                      | 1         | 0.58%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 0.58%   |
| Microsoft Surface Go                              | 1         | 0.58%   |
| LG 17ZT90P-G.AX33U1                               | 1         | 0.58%   |
| Lenovo Z50-75 80EC                                | 1         | 0.58%   |
| Lenovo Yoga 520-14IKB 80X8                        | 1         | 0.58%   |
| Lenovo ThinkPad Yoga 11e 5th Gen 20LNS1MV00       | 1         | 0.58%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 0.58%   |
| Lenovo ThinkPad T490 20N3S7BC02                   | 1         | 0.58%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 0.58%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 21        | 12.14%  |
| Dell OptiPlex              | 15        | 8.67%   |
| Dell Inspiron              | 11        | 6.36%   |
| Lenovo ThinkPad            | 9         | 5.2%    |
| Unknown                    | 6         | 3.47%   |
| Lenovo IdeaPad             | 5         | 2.89%   |
| HP Pavilion                | 5         | 2.89%   |
| Acer Aspire                | 5         | 2.89%   |
| HP Laptop                  | 4         | 2.31%   |
| HP Compaq                  | 4         | 2.31%   |
| Gigabyte GA-78LMT-USB3     | 4         | 2.31%   |
| HP ProBook                 | 3         | 1.73%   |
| HP EliteBook               | 3         | 1.73%   |
| ASUS VivoBook              | 3         | 1.73%   |
| VTEX NOTEBOOK              | 2         | 1.16%   |
| HP EliteDesk               | 2         | 1.16%   |
| Gigabyte B450M             | 2         | 1.16%   |
| EVOO EV-C-116-7            | 2         | 1.16%   |
| Dell Vostro                | 2         | 1.16%   |
| Apple MacBookPro8          | 2         | 1.16%   |
| Toshiba Satellite          | 1         | 0.58%   |
| TODOS INDUSTRIAL Easytouch | 1         | 0.58%   |
| Samsung RV420              | 1         | 0.58%   |
| Samsung 930QCG             | 1         | 0.58%   |
| Samsung 905S3G             | 1         | 0.58%   |
| SAELITE ES1AU11            | 1         | 0.58%   |
| Nuvision NES11             | 1         | 0.58%   |
| MSI MS-7A34                | 1         | 0.58%   |
| MSI MS-7817                | 1         | 0.58%   |
| MSI GE62                   | 1         | 0.58%   |
| MSI CR70                   | 1         | 0.58%   |
| Microsoft Surface          | 1         | 0.58%   |
| LG 17ZT90P-G.AX33U1        | 1         | 0.58%   |
| Lenovo Z50-75              | 1         | 0.58%   |
| Lenovo Yoga                | 1         | 0.58%   |
| Lenovo ThinkBook           | 1         | 0.58%   |
| Lenovo Legion              | 1         | 0.58%   |
| Lenovo G505s               | 1         | 0.58%   |
| Lenovo G40-70              | 1         | 0.58%   |
| HP t520                    | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2014 | 18        | 10.4%   |
| 2011 | 17        | 9.83%   |
| 2013 | 16        | 9.25%   |
| 2017 | 15        | 8.67%   |
| 2021 | 14        | 8.09%   |
| 2019 | 14        | 8.09%   |
| 2012 | 11        | 6.36%   |
| 2018 | 10        | 5.78%   |
| 2016 | 10        | 5.78%   |
| 2020 | 8         | 4.62%   |
| 2015 | 8         | 4.62%   |
| 2008 | 8         | 4.62%   |
| 2010 | 7         | 4.05%   |
| 2009 | 5         | 2.89%   |
| 2007 | 5         | 2.89%   |
| 2022 | 4         | 2.31%   |
| 2006 | 2         | 1.16%   |
| 2005 | 1         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 118       | 68.21%  |
| Desktop     | 47        | 27.17%  |
| Convertible | 3         | 1.73%   |
| Tablet      | 2         | 1.16%   |
| Mini pc     | 2         | 1.16%   |
| All in one  | 1         | 0.58%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 168       | 97.11%  |
| Enabled  | 5         | 2.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 171       | 98.84%  |
| Yes  | 2         | 1.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 51        | 29.31%  |
| 4.01-8.0    | 45        | 25.86%  |
| 8.01-16.0   | 33        | 18.97%  |
| 16.01-24.0  | 23        | 13.22%  |
| 24.01-32.0  | 5         | 2.87%   |
| 2.01-3.0    | 5         | 2.87%   |
| 1.01-2.0    | 5         | 2.87%   |
| 32.01-64.0  | 4         | 2.3%    |
| 0.51-1.0    | 2         | 1.15%   |
| 64.01-256.0 | 1         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 71        | 37.97%  |
| 2.01-3.0  | 50        | 26.74%  |
| 3.01-4.0  | 34        | 18.18%  |
| 4.01-8.0  | 20        | 10.7%   |
| 0.51-1.0  | 10        | 5.35%   |
| 8.01-16.0 | 2         | 1.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 120       | 68.18%  |
| 2      | 45        | 25.57%  |
| 3      | 7         | 3.98%   |
| 4      | 4         | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 58.62%  |
| Yes       | 72        | 41.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 140       | 80.46%  |
| No        | 34        | 19.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 83.91%  |
| No        | 28        | 16.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 60.34%  |
| No        | 69        | 39.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 173       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 96        | 51.89%  |
| Santiago de los Caballeros | 22        | 11.89%  |
| Santo Domingo              | 16        | 8.65%   |
| La Romana                  | 6         | 3.24%   |
| Concepción de la Vega     | 5         | 2.7%    |
| Alejandro Bass             | 4         | 2.16%   |
| Santa Cruz de Barahona     | 3         | 1.62%   |
| San Pedro de Macorís      | 3         | 1.62%   |
| San Juan                   | 3         | 1.62%   |
| San Cristobal              | 3         | 1.62%   |
| Constanza                  | 3         | 1.62%   |
| Cabarete                   | 3         | 1.62%   |
| Sosua, Cabarete            | 2         | 1.08%   |
| Nacional                   | 2         | 1.08%   |
| Bajos de Haina             | 2         | 1.08%   |
| Santo Domingo Oeste        | 1         | 0.54%   |
| San Francisco de Macorís  | 1         | 0.54%   |
| Salcedo                    | 1         | 0.54%   |
| Sabaneta                   | 1         | 0.54%   |
| Punta Cana                 | 1         | 0.54%   |
| Nagua                      | 1         | 0.54%   |
| Moca                       | 1         | 0.54%   |
| Los Hidalgos               | 1         | 0.54%   |
| Guaymate                   | 1         | 0.54%   |
| Cancino                    | 1         | 0.54%   |
| Boca Chica                 | 1         | 0.54%   |
| Baní                      | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 48        | 63     | 21.15%  |
| Samsung Electronics         | 28        | 34     | 12.33%  |
| WDC                         | 21        | 29     | 9.25%   |
| Toshiba                     | 21        | 27     | 9.25%   |
| Kingston                    | 15        | 16     | 6.61%   |
| Hitachi                     | 15        | 18     | 6.61%   |
| SanDisk                     | 12        | 16     | 5.29%   |
| Unknown                     | 10        | 12     | 4.41%   |
| SK hynix                    | 6         | 7      | 2.64%   |
| Intel                       | 6         | 8      | 2.64%   |
| China                       | 4         | 5      | 1.76%   |
| AirDisk                     | 4         | 4      | 1.76%   |
| SPCC                        | 3         | 3      | 1.32%   |
| Micron/Crucial Technology   | 3         | 3      | 1.32%   |
| Unknown                     | 3         | 3      | 1.32%   |
| Transcend                   | 2         | 2      | 0.88%   |
| Micron Technology           | 2         | 2      | 0.88%   |
| Indilinx                    | 2         | 2      | 0.88%   |
| FORESEE                     | 2         | 2      | 0.88%   |
| Crucial                     | 2         | 3      | 0.88%   |
| Apple                       | 2         | 5      | 0.88%   |
| A-DATA Technology           | 2         | 2      | 0.88%   |
| UMIS                        | 1         | 1      | 0.44%   |
| Supersonic                  | 1         | 1      | 0.44%   |
| SABRENT                     | 1         | 1      | 0.44%   |
| PNY                         | 1         | 1      | 0.44%   |
| Phison Electronics          | 1         | 1      | 0.44%   |
| Patriot                     | 1         | 1      | 0.44%   |
| OCZ                         | 1         | 1      | 0.44%   |
| Maxtor                      | 1         | 1      | 0.44%   |
| LITEONIT                    | 1         | 2      | 0.44%   |
| Kingston Technology Company | 1         | 1      | 0.44%   |
| HGST                        | 1         | 1      | 0.44%   |
| Hewlett-Packard             | 1         | 1      | 0.44%   |
| Eluktro                     | 1         | 1      | 0.44%   |
| ELOTEC                      | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 4         | 1.63%   |
| Seagate ST500LM000-1EJ162 500GB                     | 4         | 1.63%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 1.63%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 1.63%   |
| AirDisk 128GB SSD                                   | 4         | 1.63%   |
| Toshiba MQ01ACF050 500GB                            | 3         | 1.22%   |
| Toshiba MK3275GSX 320GB                             | 3         | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 1.22%   |
| Samsung SSD 860 EVO 500GB                           | 3         | 1.22%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3         | 1.22%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 1.22%   |
| Unknown                                             | 3         | 1.22%   |
| Unknown MMC Card  64GB                              | 2         | 0.82%   |
| Unknown MMC Card  16GB                              | 2         | 0.82%   |
| Unknown MMC Card  128GB                             | 2         | 0.82%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.82%   |
| Toshiba MK2556GSY 250GB                             | 2         | 0.82%   |
| Toshiba DT01ACA050 500GB                            | 2         | 0.82%   |
| Seagate ST9250315AS 250GB                           | 2         | 0.82%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 0.82%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 0.82%   |
| Seagate ST380815AS 80GB                             | 2         | 0.82%   |
| Seagate ST3500418AS 500GB                           | 2         | 0.82%   |
| Seagate ST3160815AS 160GB                           | 2         | 0.82%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 0.82%   |
| SanDisk NVMe SSD Drive 256GB                        | 2         | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 2         | 0.82%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.82%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.82%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 0.82%   |
| Intel HBRPEKNX0101AHO 16GB                          | 2         | 0.82%   |
| Intel HBRPEKNX0101AH 256GB                          | 2         | 0.82%   |
| Indilinx IND-S3N80P/128G 128GB                      | 2         | 0.82%   |
| FORESEE 128GB SSD                                   | 2         | 0.82%   |
| WDC WDS120G1G0A-00SS50 120GB SSD                    | 1         | 0.41%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                      | 1         | 0.41%   |
| WDC WD6400AAKS-22A7B2 640GB                         | 1         | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 0.41%   |
| WDC WD5000LPLX-08ZNTT0 500GB                        | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 61     | 43.93%  |
| WDC                 | 19        | 25     | 17.76%  |
| Toshiba             | 19        | 24     | 17.76%  |
| Hitachi             | 15        | 18     | 14.02%  |
| Samsung Electronics | 4         | 6      | 3.74%   |
| SABRENT             | 1         | 1      | 0.93%   |
| Maxtor              | 1         | 1      | 0.93%   |
| HGST                | 1         | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 18     | 22.97%  |
| Kingston            | 14        | 15     | 18.92%  |
| SanDisk             | 7         | 11     | 9.46%   |
| China               | 4         | 5      | 5.41%   |
| AirDisk             | 4         | 4      | 5.41%   |
| WDC                 | 3         | 4      | 4.05%   |
| SPCC                | 3         | 3      | 4.05%   |
| Transcend           | 2         | 2      | 2.7%    |
| SK hynix            | 2         | 2      | 2.7%    |
| Intel               | 2         | 2      | 2.7%    |
| FORESEE             | 2         | 2      | 2.7%    |
| Crucial             | 2         | 3      | 2.7%    |
| A-DATA Technology   | 2         | 2      | 2.7%    |
| Supersonic          | 1         | 1      | 1.35%   |
| Seagate             | 1         | 2      | 1.35%   |
| PNY                 | 1         | 1      | 1.35%   |
| Patriot             | 1         | 1      | 1.35%   |
| OCZ                 | 1         | 1      | 1.35%   |
| LITEONIT            | 1         | 2      | 1.35%   |
| Hewlett-Packard     | 1         | 1      | 1.35%   |
| Eluktro             | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |
| Unknown             | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 93        | 137    | 44.93%  |
| SSD     | 67        | 85     | 32.37%  |
| NVMe    | 31        | 41     | 14.98%  |
| MMC     | 12        | 14     | 5.8%    |
| Unknown | 4         | 4      | 1.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 143       | 219    | 74.48%  |
| NVMe | 31        | 41     | 16.15%  |
| MMC  | 12        | 14     | 6.25%   |
| SAS  | 6         | 7      | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 114       | 167    | 71.25%  |
| 0.51-1.0   | 33        | 40     | 20.63%  |
| 1.01-2.0   | 8         | 9      | 5%      |
| 3.01-4.0   | 3         | 4      | 1.88%   |
| 4.01-10.0  | 2         | 2      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 57        | 30.98%  |
| 501-1000       | 31        | 16.85%  |
| 251-500        | 30        | 16.3%   |
| 1-20           | 20        | 10.87%  |
| 51-100         | 18        | 9.78%   |
| 21-50          | 8         | 4.35%   |
| 1001-2000      | 7         | 3.8%    |
| More than 3000 | 5         | 2.72%   |
| 2001-3000      | 4         | 2.17%   |
| Unknown        | 4         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 77        | 39.69%  |
| 21-50          | 36        | 18.56%  |
| 51-100         | 29        | 14.95%  |
| 101-250        | 17        | 8.76%   |
| 251-500        | 12        | 6.19%   |
| 501-1000       | 9         | 4.64%   |
| 1001-2000      | 5         | 2.58%   |
| 2001-3000      | 4         | 2.06%   |
| Unknown        | 4         | 2.06%   |
| More than 3000 | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba MK3275GSX 320GB           | 2         | 2      | 6.45%   |
| Seagate ST500LM021-1KJ152 500GB   | 2         | 2      | 6.45%   |
| Seagate ST500LM000-1EJ162 500GB   | 2         | 2      | 6.45%   |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 6.45%   |
| WDC WD6400AAKS-22A7B2 640GB       | 1         | 1      | 3.23%   |
| WDC WD5000BPVT-00HXZT1 500GB      | 1         | 1      | 3.23%   |
| WDC WD5000AZLX-60K2TA0 500GB      | 1         | 1      | 3.23%   |
| WDC WD2500BEKT-60A25T1 250GB      | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD050V 500GB         | 1         | 1      | 3.23%   |
| Toshiba MK6465GSXN 640GB          | 1         | 1      | 3.23%   |
| Toshiba MK3276GSX 320GB           | 1         | 1      | 3.23%   |
| Toshiba MK2556GSY 250GB           | 1         | 1      | 3.23%   |
| Toshiba MK1655GSX 160GB           | 1         | 1      | 3.23%   |
| Seagate ST9750420AS 752GB         | 1         | 1      | 3.23%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 3.23%   |
| Seagate ST3250318AS 250GB         | 1         | 1      | 3.23%   |
| Seagate ST2000LM007-1R8174 2TB    | 1         | 1      | 3.23%   |
| Samsung Electronics HM500LI 500GB | 1         | 1      | 3.23%   |
| Samsung Electronics HD154UI 1TB   | 1         | 1      | 3.23%   |
| Hitachi HTS727550A9E364 500GB     | 1         | 1      | 3.23%   |
| Hitachi HTS725032A9A364 320GB     | 1         | 1      | 3.23%   |
| Hitachi HTS722020K9SA00 200GB     | 1         | 1      | 3.23%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 3.23%   |
| Hitachi HTS547564A9E384 640GB     | 1         | 1      | 3.23%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 3.23%   |
| Hitachi HDT721025SLA380 250GB     | 1         | 1      | 3.23%   |
| Crucial CT240BX500SSD1 240GB      | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 32.26%  |
| Toshiba             | 7         | 7      | 22.58%  |
| Hitachi             | 7         | 7      | 22.58%  |
| WDC                 | 4         | 4      | 12.9%   |
| Samsung Electronics | 2         | 2      | 6.45%   |
| Crucial             | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 33.33%  |
| Toshiba             | 7         | 7      | 23.33%  |
| Hitachi             | 7         | 7      | 23.33%  |
| WDC                 | 4         | 4      | 13.33%  |
| Samsung Electronics | 2         | 2      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 30     | 96.3%   |
| SSD  | 1         | 1      | 3.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545050B9SA00 500GB | 1         | 1      | 50%     |
| Hitachi HDS721025CLA382 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 106       | 174    | 56.38%  |
| Works    | 54        | 74     | 28.72%  |
| Malfunc  | 26        | 31     | 13.83%  |
| Failed   | 2         | 2      | 1.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 120       | 64.17%  |
| AMD                              | 33        | 17.65%  |
| Samsung Electronics              | 9         | 4.81%   |
| SanDisk                          | 5         | 2.67%   |
| SK hynix                         | 3         | 1.6%    |
| Micron/Crucial Technology        | 3         | 1.6%    |
| Toshiba America Info Systems     | 2         | 1.07%   |
| Micron Technology                | 2         | 1.07%   |
| Kingston Technology Company      | 2         | 1.07%   |
| VIA Technologies                 | 1         | 0.53%   |
| Union Memory (Shenzhen)          | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |
| Phison Electronics               | 1         | 0.53%   |
| Nvidia                           | 1         | 0.53%   |
| Marvell Technology Group         | 1         | 0.53%   |
| ASMedia Technology               | 1         | 0.53%   |
| Apple                            | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24        | 11.06%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 15        | 6.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 12        | 5.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 5.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 3.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 3.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 2.76%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 2.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 2.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 1.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 1.84%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 1.84%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3         | 1.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.38%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 1.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.38%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 1.38%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                                   | 2         | 0.92%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2         | 0.92%   |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 2         | 0.92%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]                      | 2         | 0.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 0.92%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 0.92%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1         | 0.46%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1         | 0.46%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                                   | 1         | 0.46%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 59.8%   |
| NVMe | 31        | 15.58%  |
| IDE  | 27        | 13.57%  |
| RAID | 22        | 11.06%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 137       | 79.19%  |
| AMD    | 36        | 20.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron N4120 CPU @ 1.10GHz           | 8         | 4.62%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 4         | 2.31%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 2.31%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 2.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.73%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 1.73%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 1.73%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.16%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.16%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.16%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2         | 1.16%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.16%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.16%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 1.16%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 2         | 1.16%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 2         | 1.16%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.16%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 2         | 1.16%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.16%   |
| AMD FX-8320 Eight-Core Processor            | 2         | 1.16%   |
| AMD FX-4100 Quad-Core Processor             | 2         | 1.16%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.16%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics | 2         | 1.16%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1         | 0.58%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.58%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.58%   |
| Intel Pentium D CPU 3.00GHz                 | 1         | 0.58%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1         | 0.58%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.58%   |
| Intel Pentium CPU 4415Y @ 1.60GHz           | 1         | 0.58%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.58%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 0.58%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 49        | 28.32%  |
| Intel Core i7           | 24        | 13.87%  |
| Intel Celeron           | 22        | 12.72%  |
| Intel Core i3           | 14        | 8.09%   |
| AMD Ryzen 5             | 9         | 5.2%    |
| Intel Core 2 Duo        | 7         | 4.05%   |
| AMD FX                  | 5         | 2.89%   |
| Intel Atom              | 4         | 2.31%   |
| AMD Ryzen 7             | 4         | 2.31%   |
| Intel Pentium           | 3         | 1.73%   |
| AMD A10                 | 3         | 1.73%   |
| Other                   | 2         | 1.16%   |
| Intel Xeon              | 2         | 1.16%   |
| Intel Pentium Dual-Core | 2         | 1.16%   |
| Intel Core 2            | 2         | 1.16%   |
| AMD Ryzen 3             | 2         | 1.16%   |
| AMD A8                  | 2         | 1.16%   |
| AMD A6                  | 2         | 1.16%   |
| AMD A4                  | 2         | 1.16%   |
| Intel Pentium Dual      | 1         | 0.58%   |
| Intel Pentium D         | 1         | 0.58%   |
| Intel Pentium 4         | 1         | 0.58%   |
| Intel Genuine           | 1         | 0.58%   |
| Intel Core i9           | 1         | 0.58%   |
| Intel Core 2 Quad       | 1         | 0.58%   |
| AMD Sempron             | 1         | 0.58%   |
| AMD Quad-Core           | 1         | 0.58%   |
| AMD PRO A10             | 1         | 0.58%   |
| AMD Phenom II X4        | 1         | 0.58%   |
| AMD Mobile Sempron      | 1         | 0.58%   |
| AMD GX                  | 1         | 0.58%   |
| AMD A12                 | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 91        | 52.6%   |
| 4      | 63        | 36.42%  |
| 6      | 8         | 4.62%   |
| 1      | 5         | 2.89%   |
| 8      | 4         | 2.31%   |
| 12     | 1         | 0.58%   |
| 3      | 1         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 172       | 99.42%  |
| 2      | 1         | 0.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 101       | 58.38%  |
| 1      | 72        | 41.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 171       | 98.28%  |
| 64-bit         | 1         | 0.57%   |
| 32-bit         | 1         | 0.57%   |
| Unknown        | 1         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 31.07%  |
| 0x206a7    | 14        | 7.91%   |
| 0x306a9    | 11        | 6.21%   |
| 0x306c3    | 8         | 4.52%   |
| 0x1067a    | 7         | 3.95%   |
| 0x806e9    | 6         | 3.39%   |
| 0x506e3    | 6         | 3.39%   |
| 0x40651    | 5         | 2.82%   |
| 0x806ea    | 4         | 2.26%   |
| 0x706a1    | 4         | 2.26%   |
| 0x706a8    | 3         | 1.69%   |
| 0x30678    | 3         | 1.69%   |
| 0x0800820d | 3         | 1.69%   |
| 0x07030105 | 3         | 1.69%   |
| 0x06000852 | 3         | 1.69%   |
| 0x806ec    | 2         | 1.13%   |
| 0x6fb      | 2         | 1.13%   |
| 0x6f6      | 2         | 1.13%   |
| 0x20655    | 2         | 1.13%   |
| 0x20652    | 2         | 1.13%   |
| 0x10676    | 2         | 1.13%   |
| 0x08600103 | 2         | 1.13%   |
| 0x08108109 | 2         | 1.13%   |
| 0x0600611a | 2         | 1.13%   |
| 0xf65      | 1         | 0.56%   |
| 0xf49      | 1         | 0.56%   |
| 0x906ea    | 1         | 0.56%   |
| 0x906e9    | 1         | 0.56%   |
| 0x806c1    | 1         | 0.56%   |
| 0x706e5    | 1         | 0.56%   |
| 0x6fd      | 1         | 0.56%   |
| 0x506c9    | 1         | 0.56%   |
| 0x406c3    | 1         | 0.56%   |
| 0x30679    | 1         | 0.56%   |
| 0x106ca    | 1         | 0.56%   |
| 0x106c2    | 1         | 0.56%   |
| 0x10661    | 1         | 0.56%   |
| 0x08608103 | 1         | 0.56%   |
| 0x08608102 | 1         | 0.56%   |
| 0x08108102 | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 13.29%  |
| Haswell       | 18        | 10.4%   |
| SandyBridge   | 16        | 9.25%   |
| IvyBridge     | 14        | 8.09%   |
| Goldmont plus | 12        | 6.94%   |
| Silvermont    | 9         | 5.2%    |
| Penryn        | 9         | 5.2%    |
| Skylake       | 8         | 4.62%   |
| Zen+          | 7         | 4.05%   |
| Westmere      | 7         | 4.05%   |
| Core          | 6         | 3.47%   |
| Puma          | 5         | 2.89%   |
| Piledriver    | 4         | 2.31%   |
| IceLake       | 4         | 2.31%   |
| Excavator     | 4         | 2.31%   |
| Zen 3         | 3         | 1.73%   |
| Broadwell     | 3         | 1.73%   |
| Zen 2         | 2         | 1.16%   |
| TigerLake     | 2         | 1.16%   |
| NetBurst      | 2         | 1.16%   |
| K8 Hammer     | 2         | 1.16%   |
| Bulldozer     | 2         | 1.16%   |
| Bonnell       | 2         | 1.16%   |
| Unknown       | 2         | 1.16%   |
| Zen           | 1         | 0.58%   |
| Steamroller   | 1         | 0.58%   |
| K10 Llano     | 1         | 0.58%   |
| K10           | 1         | 0.58%   |
| Jaguar        | 1         | 0.58%   |
| Goldmont      | 1         | 0.58%   |
| CometLake     | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 123       | 63.73%  |
| AMD                              | 40        | 20.73%  |
| Nvidia                           | 28        | 14.51%  |
| VIA Technologies                 | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] | 1         | 0.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 7.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 6.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 3.54%   |
| Intel UHD Graphics 620                                                                   | 7         | 3.54%   |
| Intel HD Graphics 620                                                                    | 7         | 3.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 3.03%   |
| Intel HD Graphics 530                                                                    | 5         | 2.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.53%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.52%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.52%   |
| AMD RS780L [Radeon 3000]                                                                 | 3         | 1.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.01%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.01%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.01%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.01%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 1.01%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.01%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 2         | 1.01%   |
| AMD Lucienne                                                                             | 2         | 1.01%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.01%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                                | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.51%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.51%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.51%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 107       | 61.85%  |
| 1 x AMD        | 30        | 17.34%  |
| 1 x Nvidia     | 14        | 8.09%   |
| Intel + Nvidia | 10        | 5.78%   |
| Intel + AMD    | 4         | 2.31%   |
| AMD + Nvidia   | 4         | 2.31%   |
| 2 x AMD        | 2         | 1.16%   |
| 1 x VIA        | 1         | 0.58%   |
| 1 x SiS        | 1         | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 155       | 88.57%  |
| Proprietary | 15        | 8.57%   |
| Unknown     | 5         | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 71.59%  |
| 1.01-2.0   | 14        | 7.95%   |
| 0.01-0.5   | 14        | 7.95%   |
| 0.51-1.0   | 11        | 6.25%   |
| 3.01-4.0   | 6         | 3.41%   |
| 7.01-8.0   | 3         | 1.7%    |
| 2.01-3.0   | 2         | 1.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 16.38%  |
| BOE                     | 22        | 12.43%  |
| LG Display              | 18        | 10.17%  |
| Dell                    | 18        | 10.17%  |
| Chimei Innolux          | 16        | 9.04%   |
| Samsung Electronics     | 15        | 8.47%   |
| Hewlett-Packard         | 8         | 4.52%   |
| AOC                     | 7         | 3.95%   |
| Chi Mei Optoelectronics | 5         | 2.82%   |
| Apple                   | 5         | 2.82%   |
| InfoVision              | 4         | 2.26%   |
| Sony                    | 3         | 1.69%   |
| Acer                    | 3         | 1.69%   |
| Unknown (XXX)           | 2         | 1.13%   |
| Goldstar                | 2         | 1.13%   |
| ZTR                     | 1         | 0.56%   |
| Westinghouse            | 1         | 0.56%   |
| Vizio                   | 1         | 0.56%   |
| ViewSonic               | 1         | 0.56%   |
| STA                     | 1         | 0.56%   |
| Sharp                   | 1         | 0.56%   |
| Philips                 | 1         | 0.56%   |
| PANDA                   | 1         | 0.56%   |
| Panasonic               | 1         | 0.56%   |
| NEC Computers           | 1         | 0.56%   |
| MSI                     | 1         | 0.56%   |
| LG Philips              | 1         | 0.56%   |
| LG Electronics          | 1         | 0.56%   |
| Lenovo                  | 1         | 0.56%   |
| KTC                     | 1         | 0.56%   |
| KDC                     | 1         | 0.56%   |
| InnoLux Display         | 1         | 0.56%   |
| CHR                     | 1         | 0.56%   |
| BenQ                    | 1         | 0.56%   |
| Ancor Communications    | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision M116NWR1 R0 IVO0489 1366x768 256x144mm 11.6-inch           | 4         | 2.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 1.68%   |
| Sony TV SNYDD02 1920x1080 708x398mm 32.0-inch                         | 2         | 1.12%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 1.12%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.12%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                       | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch         | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 1.12%   |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                      | 2         | 1.12%   |
| ZTR LCD Monitor ZTR0001 1366x768 309x173mm 13.9-inch                  | 1         | 0.56%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch          | 1         | 0.56%   |
| Vizio E24-C1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.56%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                | 1         | 0.56%   |
| Unknown (XXX) MS82P XXX001A 1360x768 330x210mm 15.4-inch              | 1         | 0.56%   |
| Unknown (XXX) DTV XXX0030 1600x1200 708x398mm 32.0-inch               | 1         | 0.56%   |
| STA LCD Monitor STA0001 1366x768 256x144mm 11.6-inch                  | 1         | 0.56%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                         | 1         | 0.56%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch               | 1         | 0.56%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4642 1366x768 309x174mm 14.0-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0664 1360x768 410x256mm 19.0-inch  | 1         | 0.56%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch              | 1         | 0.56%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch               | 1         | 0.56%   |
| Panasonic TV MEI0206 1920x1080                                        | 1         | 0.56%   |
| NEC Computers EA274WMi NEC695F 2560x1440 597x336mm 27.0-inch          | 1         | 0.56%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 1         | 0.56%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 63        | 37.06%  |
| 1920x1080 (FHD)    | 54        | 31.76%  |
| 1680x1050 (WSXGA+) | 8         | 4.71%   |
| 1600x900 (HD+)     | 8         | 4.71%   |
| 1280x800 (WXGA)    | 7         | 4.12%   |
| 1280x1024 (SXGA)   | 7         | 4.12%   |
| 1440x900 (WXGA+)   | 4         | 2.35%   |
| 1360x768           | 4         | 2.35%   |
| 3840x2160 (4K)     | 3         | 1.76%   |
| 2560x1440 (QHD)    | 2         | 1.18%   |
| 1024x768 (XGA)     | 2         | 1.18%   |
| 3840x1100          | 1         | 0.59%   |
| 3440x1440          | 1         | 0.59%   |
| 2560x1600          | 1         | 0.59%   |
| 1984x768           | 1         | 0.59%   |
| 1800x1200          | 1         | 0.59%   |
| 1280x768           | 1         | 0.59%   |
| 1024x600           | 1         | 0.59%   |
| Unknown            | 1         | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 62        | 35.03%  |
| 13      | 22        | 12.43%  |
| 14      | 15        | 8.47%   |
| 11      | 11        | 6.21%   |
| 17      | 10        | 5.65%   |
| 22      | 9         | 5.08%   |
| 19      | 8         | 4.52%   |
| 24      | 6         | 3.39%   |
| 21      | 6         | 3.39%   |
| 27      | 5         | 2.82%   |
| Unknown | 4         | 2.26%   |
| 18      | 3         | 1.69%   |
| 50      | 2         | 1.13%   |
| 34      | 2         | 1.13%   |
| 32      | 2         | 1.13%   |
| 10      | 2         | 1.13%   |
| 84      | 1         | 0.56%   |
| 72      | 1         | 0.56%   |
| 41      | 1         | 0.56%   |
| 40      | 1         | 0.56%   |
| 31      | 1         | 0.56%   |
| 23      | 1         | 0.56%   |
| 20      | 1         | 0.56%   |
| 12      | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 89        | 51.15%  |
| 401-500     | 24        | 13.79%  |
| 201-300     | 24        | 13.79%  |
| 501-600     | 12        | 6.9%    |
| 351-400     | 10        | 5.75%   |
| 701-800     | 4         | 2.3%    |
| Unknown     | 4         | 2.3%    |
| 1501-2000   | 2         | 1.15%   |
| 1001-1500   | 2         | 1.15%   |
| 801-900     | 1         | 0.57%   |
| 601-700     | 1         | 0.57%   |
| 901-1000    | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 125       | 77.16%  |
| 16/10   | 23        | 14.2%   |
| 5/4     | 7         | 4.32%   |
| Unknown | 3         | 1.85%   |
| 4/3     | 1         | 0.62%   |
| 3/2     | 1         | 0.62%   |
| 3.40    | 1         | 0.62%   |
| 21/9    | 1         | 0.62%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 61        | 34.46%  |
| 81-90          | 30        | 16.95%  |
| 201-250        | 17        | 9.6%    |
| 151-200        | 13        | 7.34%   |
| 51-60          | 12        | 6.78%   |
| 141-150        | 8         | 4.52%   |
| 71-80          | 6         | 3.39%   |
| 301-350        | 5         | 2.82%   |
| 121-130        | 5         | 2.82%   |
| More than 1000 | 4         | 2.26%   |
| 351-500        | 4         | 2.26%   |
| Unknown        | 4         | 2.26%   |
| 501-1000       | 3         | 1.69%   |
| 41-50          | 2         | 1.13%   |
| 61-70          | 1         | 0.56%   |
| 251-300        | 1         | 0.56%   |
| 91-100         | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 63        | 36.63%  |
| 121-160       | 47        | 27.33%  |
| 51-100        | 46        | 26.74%  |
| 1-50          | 6         | 3.49%   |
| 161-240       | 5         | 2.91%   |
| Unknown       | 4         | 2.33%   |
| More than 240 | 1         | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 145       | 82.86%  |
| 2     | 22        | 12.57%  |
| 0     | 7         | 4%      |
| 3     | 1         | 0.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 87        | 33.21%  |
| Intel                           | 83        | 31.68%  |
| Qualcomm Atheros                | 34        | 12.98%  |
| Broadcom                        | 23        | 8.78%   |
| Ralink Technology               | 11        | 4.2%    |
| Qualcomm Atheros Communications | 4         | 1.53%   |
| Broadcom Limited                | 4         | 1.53%   |
| Marvell Technology Group        | 2         | 0.76%   |
| Linksys                         | 2         | 0.76%   |
| Lenovo                          | 2         | 0.76%   |
| Dell                            | 2         | 0.76%   |
| VIA Technologies                | 1         | 0.38%   |
| Tul Corporation / PowerColor    | 1         | 0.38%   |
| TP-Link                         | 1         | 0.38%   |
| Nvidia                          | 1         | 0.38%   |
| MediaTek                        | 1         | 0.38%   |
| JCM                             | 1         | 0.38%   |
| HTC (High Tech Computer)        | 1         | 0.38%   |
| AMD                             | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 15.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 5.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 4.55%   |
| Ralink MT7601U Wireless Adapter                                   | 9         | 2.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 2.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.95%   |
| Intel Wireless 7260                                               | 6         | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.62%   |
| Intel Wireless 3165                                               | 5         | 1.62%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.3%    |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.3%    |
| Intel Wireless 7265                                               | 4         | 1.3%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.3%    |
| Intel Wireless 8265 / 8275                                        | 3         | 0.97%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.97%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.97%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.65%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.65%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.65%   |
| Lenovo Thinkpad LAN                                               | 2         | 0.65%   |
| Intel Wireless 8260                                               | 2         | 0.65%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 38.99%  |
| Realtek Semiconductor           | 31        | 19.5%   |
| Qualcomm Atheros                | 27        | 16.98%  |
| Broadcom                        | 16        | 10.06%  |
| Ralink Technology               | 11        | 6.92%   |
| Qualcomm Atheros Communications | 4         | 2.52%   |
| Linksys                         | 2         | 1.26%   |
| Dell                            | 2         | 1.26%   |
| Broadcom Limited                | 2         | 1.26%   |
| TP-Link                         | 1         | 0.63%   |
| MediaTek                        | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Ralink MT7601U Wireless Adapter                                | 9         | 5.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 4.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 3.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 3.75%   |
| Intel Wireless 7260                                            | 6         | 3.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.13%   |
| Intel Wireless 3165                                            | 5         | 3.13%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 2.5%    |
| Qualcomm Atheros AR9271 802.11n                                | 4         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.5%    |
| Intel Wireless 7265                                            | 4         | 2.5%    |
| Intel Wireless 8265 / 8275                                     | 3         | 1.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.88%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.25%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.25%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.25%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 1.25%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.25%   |
| Intel Wireless 8260                                            | 2         | 1.25%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 1.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.25%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.25%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 1.25%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.25%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.25%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 2         | 1.25%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.63%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.63%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 71        | 48.97%  |
| Intel                    | 46        | 31.72%  |
| Broadcom                 | 10        | 6.9%    |
| Qualcomm Atheros         | 9         | 6.21%   |
| Marvell Technology Group | 2         | 1.38%   |
| Lenovo                   | 2         | 1.38%   |
| Broadcom Limited         | 2         | 1.38%   |
| VIA Technologies         | 1         | 0.69%   |
| Nvidia                   | 1         | 0.69%   |
| HTC (High Tech Computer) | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 33.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 12.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 9.66%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 4.14%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.76%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.07%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 2.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.38%   |
| Lenovo Thinkpad LAN                                               | 2         | 1.38%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.38%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.69%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.69%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.69%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.69%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.69%   |
| Intel 82562V 10/100 Network Connection                            | 1         | 0.69%   |
| HTC (High Tech Computer) UMI HAMMER                               | 1         | 0.69%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 146       | 50.69%  |
| Ethernet | 139       | 48.26%  |
| Modem    | 2         | 0.69%   |
| Unknown  | 1         | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 66.1%   |
| Ethernet | 60        | 33.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 99        | 57.23%  |
| 1     | 68        | 39.31%  |
| 0     | 6         | 3.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 158       | 88.76%  |
| Yes  | 20        | 11.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 41.9%   |
| Qualcomm Atheros Communications | 15        | 14.29%  |
| IMC Networks                    | 11        | 10.48%  |
| Cambridge Silicon Radio         | 8         | 7.62%   |
| Realtek Semiconductor           | 7         | 6.67%   |
| Dell                            | 6         | 5.71%   |
| Apple                           | 5         | 4.76%   |
| Broadcom                        | 4         | 3.81%   |
| Lite-On Technology              | 2         | 1.9%    |
| Hewlett-Packard                 | 1         | 0.95%   |
| Dynex                           | 1         | 0.95%   |
| ASUSTek Computer                | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 21        | 20%     |
| Qualcomm Atheros  Bluetooth Device                       | 10        | 9.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 8         | 7.62%   |
| IMC Networks Bluetooth Radio                             | 6         | 5.71%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 5         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 5         | 4.76%   |
| Intel AX200 Bluetooth                                    | 5         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                           | 4         | 3.81%   |
| Intel Bluetooth Device                                   | 4         | 3.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 3         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                         | 3         | 2.86%   |
| Dell BCM20702A0 Bluetooth Module                         | 3         | 2.86%   |
| Apple Bluetooth Host Controller                          | 3         | 2.86%   |
| Realtek Bluetooth Radio                                  | 2         | 1.9%    |
| IMC Networks BCM20702A0                                  | 2         | 1.9%    |
| Broadcom BCM43142 Bluetooth 4.0                          | 2         | 1.9%    |
| Realtek RTL8723B Bluetooth                               | 1         | 0.95%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1         | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 1         | 0.95%   |
| Lite-On Wireless_Device                                  | 1         | 0.95%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 0.95%   |
| IMC Networks Bluetooth Device                            | 1         | 0.95%   |
| IMC Networks Bluetooth                                   | 1         | 0.95%   |
| IMC Networks 802.11ac WLAN Adapter                       | 1         | 0.95%   |
| HP Broadcom 2070 Bluetooth Combo                         | 1         | 0.95%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1         | 0.95%   |
| Dell Wireless 360 Bluetooth                              | 1         | 0.95%   |
| Dell Wireless 355 Bluetooth                              | 1         | 0.95%   |
| Dell Wireless 350 Bluetooth                              | 1         | 0.95%   |
| Broadcom HP Portable SoftSailing                         | 1         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 0.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1         | 0.95%   |
| Apple Bluetooth USB Host Controller                      | 1         | 0.95%   |
| Apple Bluetooth HCI                                      | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 131       | 64.22%  |
| AMD                              | 39        | 19.12%  |
| Nvidia                           | 21        | 10.29%  |
| Logitech                         | 4         | 1.96%   |
| C-Media Electronics              | 2         | 0.98%   |
| VIA Technologies                 | 1         | 0.49%   |
| Sony                             | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| JMTek                            | 1         | 0.49%   |
| Creative Labs                    | 1         | 0.49%   |
| Blue Microphones                 | 1         | 0.49%   |
| BigBen Interactive               | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 7.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 6.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 5.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 4.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 4.78%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 4.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 4.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 3.59%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.39%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 2.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 2.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.2%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.2%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.8%    |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.8%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.8%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2         | 0.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.8%    |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 0.4%    |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 31        | 27.19%  |
| Samsung Electronics | 25        | 21.93%  |
| Micron Technology   | 13        | 11.4%   |
| Unknown             | 7         | 6.14%   |
| Unknown (ABCD)      | 6         | 5.26%   |
| Kingston            | 6         | 5.26%   |
| Crucial             | 5         | 4.39%   |
| Nanya Technology    | 4         | 3.51%   |
| Ramaxel Technology  | 3         | 2.63%   |
| Corsair             | 3         | 2.63%   |
| A-DATA Technology   | 2         | 1.75%   |
| V-Color             | 1         | 0.88%   |
| Timetec             | 1         | 0.88%   |
| Sesame              | 1         | 0.88%   |
| Qimonda             | 1         | 0.88%   |
| Patriot             | 1         | 0.88%   |
| G.Skill             | 1         | 0.88%   |
| Elpida              | 1         | 0.88%   |
| Avant               | 1         | 0.88%   |
| Unknown             | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 5%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.5%    |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 3         | 2.5%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2         | 1.67%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 2         | 1.67%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 1.67%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s             | 2         | 1.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.67%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.67%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.67%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                | 2         | 1.67%   |
| V-Color RAM TL48G32S8KGRGB16 8192MB DIMM DDR4 3200MT/s           | 1         | 0.83%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 0.83%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.83%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.83%   |
| Timetec RAM U8G-1333 8192MB DIMM DDR3 1333MT/s                   | 1         | 0.83%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.83%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s                    | 1         | 0.83%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 0.83%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR2 1331MT/s             | 1         | 0.83%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.83%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.83%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.83%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.83%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.83%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.83%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 1         | 0.83%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 35        | 39.77%  |
| DDR4    | 28        | 31.82%  |
| LPDDR4  | 10        | 11.36%  |
| SDRAM   | 7         | 7.95%   |
| DDR2    | 3         | 3.41%   |
| Unknown | 3         | 3.41%   |
| LPDDR3  | 1         | 1.14%   |
| DDR     | 1         | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 65.88%  |
| DIMM         | 25        | 29.41%  |
| Row Of Chips | 4         | 4.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 37        | 38.54%  |
| 8192  | 30        | 31.25%  |
| 2048  | 18        | 18.75%  |
| 16384 | 8         | 8.33%   |
| 1024  | 2         | 2.08%   |
| 512   | 1         | 1.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 26        | 25.49%  |
| 1333    | 14        | 13.73%  |
| 2400    | 13        | 12.75%  |
| 2667    | 11        | 10.78%  |
| 2133    | 7         | 6.86%   |
| 3200    | 5         | 4.9%    |
| 1334    | 3         | 2.94%   |
| 4267    | 2         | 1.96%   |
| 4199    | 2         | 1.96%   |
| 3266    | 2         | 1.96%   |
| 2933    | 2         | 1.96%   |
| 1867    | 2         | 1.96%   |
| 1067    | 2         | 1.96%   |
| 667     | 2         | 1.96%   |
| 49926   | 1         | 0.98%   |
| 3600    | 1         | 0.98%   |
| 2934    | 1         | 0.98%   |
| 2048    | 1         | 0.98%   |
| 1648    | 1         | 0.98%   |
| 1331    | 1         | 0.98%   |
| 975     | 1         | 0.98%   |
| 533     | 1         | 0.98%   |
| Unknown | 1         | 0.98%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 17.09%  |
| Microdia                               | 19        | 16.24%  |
| IMC Networks                           | 11        | 9.4%    |
| Sunplus Innovation Technology          | 10        | 8.55%   |
| Realtek Semiconductor                  | 8         | 6.84%   |
| Suyin                                  | 7         | 5.98%   |
| Apple                                  | 6         | 5.13%   |
| Syntek                                 | 4         | 3.42%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.42%   |
| Silicon Motion                         | 3         | 2.56%   |
| Ricoh                                  | 3         | 2.56%   |
| OmniVision Technologies                | 3         | 2.56%   |
| Microsoft                              | 3         | 2.56%   |
| Quanta                                 | 2         | 1.71%   |
| Primax Electronics                     | 2         | 1.71%   |
| Logitech                               | 2         | 1.71%   |
| Bison Electronics                      | 2         | 1.71%   |
| Sonix Technology                       | 1         | 0.85%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.85%   |
| Samsung Electronics                    | 1         | 0.85%   |
| MacroSilicon                           | 1         | 0.85%   |
| Lite-On Technology                     | 1         | 0.85%   |
| Jieli Technology                       | 1         | 0.85%   |
| globaloptics                           | 1         | 0.85%   |
| Alcor Micro                            | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 6         | 5.13%   |
| Microdia HP Integrated Webcam                                  | 6         | 5.13%   |
| Chicony Integrated Camera                                      | 5         | 4.27%   |
| IMC Networks Integrated Camera                                 | 4         | 3.42%   |
| Microdia Integrated_Webcam_HD                                  | 3         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 3         | 2.56%   |
| Chicony USB2.0 HD UVC WebCam                                   | 3         | 2.56%   |
| Chicony HP TrueVision HD                                       | 3         | 2.56%   |
| Syntek Lenovo EasyCamera                                       | 2         | 1.71%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.71%   |
| Microsoft MicrosoftÂ LifeCam HD-5001                          | 2         | 1.71%   |
| Microdia Sonix USB 2.0 Camera                                  | 2         | 1.71%   |
| Microdia Integrated Webcam                                     | 2         | 1.71%   |
| Microdia Dell Integrated HD Webcam                             | 2         | 1.71%   |
| IMC Networks HP TrueVision HD Camera                           | 2         | 1.71%   |
| Chicony Integrated HP HD Webcam                                | 2         | 1.71%   |
| Chicony HD User Facing                                         | 2         | 1.71%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.71%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 2         | 1.71%   |
| Apple FaceTime HD Camera                                       | 2         | 1.71%   |
| Syntek Integrated Camera                                       | 1         | 0.85%   |
| Syntek EasyCamera                                              | 1         | 0.85%   |
| Suyin VGA Webcam                                               | 1         | 0.85%   |
| Suyin TOSHIBA Web Camera - HD                                  | 1         | 0.85%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 1         | 0.85%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.85%   |
| Suyin HP TrueVision HD                                         | 1         | 0.85%   |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 1         | 0.85%   |
| Suyin 1.3M HD WebCam                                           | 1         | 0.85%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 1         | 0.85%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 0.85%   |
| Sunplus Integrated_Webcam_FHD                                  | 1         | 0.85%   |
| Sunplus HP Wide Vision HD                                      | 1         | 0.85%   |
| Sonix HP Webcam-101                                            | 1         | 0.85%   |
| Silicon Motion WebCam SCB-0385N                                | 1         | 0.85%   |
| Silicon Motion WebCam SC-10HDD13335N                           | 1         | 0.85%   |
| Silicon Motion Real HD WebCam                                  | 1         | 0.85%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                | 1         | 0.85%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 0.85%   |
| Ricoh Laptop_Integrated_Webcam_FHD                             | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 41.18%  |
| Synaptics                  | 4         | 23.53%  |
| Elan Microelectronics      | 2         | 11.76%  |
| STMicroelectronics         | 1         | 5.88%   |
| Shenzhen Goodix Technology | 1         | 5.88%   |
| Samsung Electronics        | 1         | 5.88%   |
| LighTuning Technology      | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader        | 2         | 11.76%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 11.76%  |
| Elan ELAN:ARM-M4                                  | 2         | 11.76%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 5.88%   |
| Validity Sensors VFS491                           | 1         | 5.88%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 5.88%   |
| Validity Sensors Synaptics WBDI                   | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner              | 1         | 5.88%   |
| Synaptics  WBDI                                   | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5.88%   |
| STMicroelectronics Fingerprint Reader             | 1         | 5.88%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 5.88%   |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 5.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 66.67%  |
| O2 Micro    | 2         | 16.67%  |
| Alcor Micro | 2         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 16.67%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 129       | 72.88%  |
| 1     | 40        | 22.6%   |
| 2     | 8         | 4.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 17        | 30.36%  |
| Graphics card         | 14        | 25%     |
| Chipcard              | 10        | 17.86%  |
| Net/wireless          | 4         | 7.14%   |
| Multimedia controller | 4         | 7.14%   |
| Storage               | 2         | 3.57%   |
| Camera                | 2         | 3.57%   |
| Network               | 1         | 1.79%   |
| Card reader           | 1         | 1.79%   |
| Bluetooth             | 1         | 1.79%   |

