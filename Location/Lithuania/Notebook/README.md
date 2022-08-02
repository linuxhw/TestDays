Linux in Lithuania - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Lithuania.

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

Total: 256

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Compaq Presario CQ60        | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| eMachines     | eME443                      | [9197e8ef17](https://linux-hardware.org/?probe=9197e8ef17) | Jul 11, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [f23b75e3ca](https://linux-hardware.org/?probe=f23b75e3ca) | Jun 19, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [8f2740e70e](https://linux-hardware.org/?probe=8f2740e70e) | Jun 18, 2022 |
| Panasonic     | CF-52VDA131M                | [aa40370193](https://linux-hardware.org/?probe=aa40370193) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| Dell          | Latitude E5570              | [310aadd79a](https://linux-hardware.org/?probe=310aadd79a) | May 24, 2022 |
| Alienware     | 17                          | [b30786ba0e](https://linux-hardware.org/?probe=b30786ba0e) | May 10, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [3e171a4858](https://linux-hardware.org/?probe=3e171a4858) | May 09, 2022 |
| Lenovo        | G500 20236                  | [8439c948ec](https://linux-hardware.org/?probe=8439c948ec) | May 06, 2022 |
| Dell          | Inspiron 7720               | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| Dell          | XPS 15 9510                 | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [96fc510369](https://linux-hardware.org/?probe=96fc510369) | Apr 29, 2022 |
| Dell          | Latitude 5401               | [d115db916d](https://linux-hardware.org/?probe=d115db916d) | Apr 23, 2022 |
| Dell          | Latitude 5401               | [c9f380ea26](https://linux-hardware.org/?probe=c9f380ea26) | Apr 23, 2022 |
| ASUSTek       | X55A                        | [9188b40f88](https://linux-hardware.org/?probe=9188b40f88) | Apr 23, 2022 |
| Dell          | Vostro 3580                 | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| ASUSTek       | X55A                        | [9b02d587bf](https://linux-hardware.org/?probe=9b02d587bf) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [c3ffdf7791](https://linux-hardware.org/?probe=c3ffdf7791) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77b0be92c8](https://linux-hardware.org/?probe=77b0be92c8) | Mar 17, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5d0113f42d](https://linux-hardware.org/?probe=5d0113f42d) | Mar 16, 2022 |
| HP            | ProBook 455 G1              | [c6ad6edf70](https://linux-hardware.org/?probe=c6ad6edf70) | Mar 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4b0c952d9b](https://linux-hardware.org/?probe=4b0c952d9b) | Mar 09, 2022 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [12a1b54a3a](https://linux-hardware.org/?probe=12a1b54a3a) | Feb 16, 2022 |
| ASUSTek       | X55A                        | [dbbb7b1213](https://linux-hardware.org/?probe=dbbb7b1213) | Feb 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a7d1f29451](https://linux-hardware.org/?probe=a7d1f29451) | Jan 31, 2022 |
| Jumper        | EZbook                      | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| HP            | ProBook 450 G1              | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Lenovo        | Flex 2-15 20405             | [8f6a587ed3](https://linux-hardware.org/?probe=8f6a587ed3) | Jan 20, 2022 |
| ASUSTek       | N53SV                       | [a5b43fd8b4](https://linux-hardware.org/?probe=a5b43fd8b4) | Jan 05, 2022 |
| HP            | Laptop 14s-fq1xxx           | [8e0b4fec6c](https://linux-hardware.org/?probe=8e0b4fec6c) | Dec 26, 2021 |
| Acer          | Aspire A515-56              | [113924cdba](https://linux-hardware.org/?probe=113924cdba) | Dec 12, 2021 |
| ASUSTek       | N53SV                       | [557bb216fc](https://linux-hardware.org/?probe=557bb216fc) | Nov 20, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad L440 20ASA10P00    | [3119a05196](https://linux-hardware.org/?probe=3119a05196) | Nov 15, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [b455b4457c](https://linux-hardware.org/?probe=b455b4457c) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| ASUSTek       | X55A                        | [a55961748f](https://linux-hardware.org/?probe=a55961748f) | Nov 10, 2021 |
| ASUSTek       | X55A                        | [8c59513ced](https://linux-hardware.org/?probe=8c59513ced) | Nov 10, 2021 |
| ASUSTek       | K52F                        | [f90cbb4d26](https://linux-hardware.org/?probe=f90cbb4d26) | Nov 04, 2021 |
| ASUSTek       | N73SV                       | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| HUAWEI        | MACHD-WXX9                  | [1876547e8e](https://linux-hardware.org/?probe=1876547e8e) | Oct 25, 2021 |
| HUAWEI        | MACHD-WXX9                  | [078863a9b7](https://linux-hardware.org/?probe=078863a9b7) | Oct 25, 2021 |
| Toshiba       | Satellite C50D-A-13G        | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| Dell          | Inspiron 15-3567            | [5db12e2534](https://linux-hardware.org/?probe=5db12e2534) | Oct 02, 2021 |
| Alienware     | 17                          | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Dell          | XPS 15 9500                 | [239dced9a1](https://linux-hardware.org/?probe=239dced9a1) | Sep 19, 2021 |
| HUAWEI        | MACHD-WXX9                  | [4db5d51b06](https://linux-hardware.org/?probe=4db5d51b06) | Sep 17, 2021 |
| HP            | 250 G4                      | [6c66581e62](https://linux-hardware.org/?probe=6c66581e62) | Sep 06, 2021 |
| HP            | 250 G4                      | [619fff9116](https://linux-hardware.org/?probe=619fff9116) | Sep 04, 2021 |
| ASUSTek       | X551CAP                     | [626023b280](https://linux-hardware.org/?probe=626023b280) | Aug 24, 2021 |
| ASUSTek       | X551CAP                     | [9e64453373](https://linux-hardware.org/?probe=9e64453373) | Aug 23, 2021 |
| Acer          | Aspire 5750G                | [c358dfd2e6](https://linux-hardware.org/?probe=c358dfd2e6) | Aug 18, 2021 |
| HP            | Pavilion dv7                | [640a5fb2b3](https://linux-hardware.org/?probe=640a5fb2b3) | Aug 13, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5d33b12497](https://linux-hardware.org/?probe=5d33b12497) | Aug 13, 2021 |
| HP            | EliteBook 8440p             | [80cb2748cf](https://linux-hardware.org/?probe=80cb2748cf) | Aug 02, 2021 |
| HP            | 250 G4                      | [bd80a8cdf0](https://linux-hardware.org/?probe=bd80a8cdf0) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4752d9cb90](https://linux-hardware.org/?probe=4752d9cb90) | Aug 01, 2021 |
| Alienware     | 17                          | [9d281e3351](https://linux-hardware.org/?probe=9d281e3351) | Jun 16, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [45b678cc45](https://linux-hardware.org/?probe=45b678cc45) | Jun 07, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [dab115ff9f](https://linux-hardware.org/?probe=dab115ff9f) | Jun 07, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [63b5d9a81a](https://linux-hardware.org/?probe=63b5d9a81a) | Jun 05, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [56308999d2](https://linux-hardware.org/?probe=56308999d2) | Jun 05, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [20b885e70c](https://linux-hardware.org/?probe=20b885e70c) | Jun 01, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [74979cf76a](https://linux-hardware.org/?probe=74979cf76a) | Jun 01, 2021 |
| ASUSTek       | K52F                        | [92db46133f](https://linux-hardware.org/?probe=92db46133f) | May 24, 2021 |
| Dell          | Precision M4700             | [1d14e22fbd](https://linux-hardware.org/?probe=1d14e22fbd) | May 22, 2021 |
| Dell          | Inspiron 5579               | [83c30b9084](https://linux-hardware.org/?probe=83c30b9084) | May 15, 2021 |
| ASUSTek       | UX430UAR                    | [84b8a6331d](https://linux-hardware.org/?probe=84b8a6331d) | May 08, 2021 |
| Unknown       | Unknown                     | [50d2466e84](https://linux-hardware.org/?probe=50d2466e84) | May 06, 2021 |
| Unknown       | Unknown                     | [410d40ca5f](https://linux-hardware.org/?probe=410d40ca5f) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [49aad4b320](https://linux-hardware.org/?probe=49aad4b320) | May 04, 2021 |
| Lenovo        | ThinkPad P53 20QN0034MH     | [bcb2272cf0](https://linux-hardware.org/?probe=bcb2272cf0) | Apr 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [26133ce35a](https://linux-hardware.org/?probe=26133ce35a) | Apr 24, 2021 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [1e30c2850c](https://linux-hardware.org/?probe=1e30c2850c) | Apr 09, 2021 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [faca4e4038](https://linux-hardware.org/?probe=faca4e4038) | Apr 08, 2021 |
| Acer          | Aspire A515-56              | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| ASUSTek       | K50C                        | [4ccd0463c4](https://linux-hardware.org/?probe=4ccd0463c4) | Mar 17, 2021 |
| Lenovo        | ThinkPad T480 20L50002MH    | [554173e0d7](https://linux-hardware.org/?probe=554173e0d7) | Mar 17, 2021 |
| ASUSTek       | K50C                        | [65941d7354](https://linux-hardware.org/?probe=65941d7354) | Mar 17, 2021 |
| Dell          | Latitude E5530 non-vPro     | [530ac66726](https://linux-hardware.org/?probe=530ac66726) | Mar 17, 2021 |
| Dell          | Latitude 7380               | [43510cebc1](https://linux-hardware.org/?probe=43510cebc1) | Mar 13, 2021 |
| Lenovo        | ThinkPad W530 243852U       | [15c953bc70](https://linux-hardware.org/?probe=15c953bc70) | Mar 09, 2021 |
| Dell          | Inspiron 5758               | [f371afba83](https://linux-hardware.org/?probe=f371afba83) | Feb 27, 2021 |
| Dell          | Inspiron 5570               | [d36796da44](https://linux-hardware.org/?probe=d36796da44) | Feb 27, 2021 |
| Lenovo        | ThinkPad T430 2347EV8       | [3bf5967320](https://linux-hardware.org/?probe=3bf5967320) | Feb 19, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a398ccbc3d](https://linux-hardware.org/?probe=a398ccbc3d) | Jan 31, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XN0... | [f25ec6b2f3](https://linux-hardware.org/?probe=f25ec6b2f3) | Jan 31, 2021 |
| Acer          | Extensa 5220                | [20ea0cd55c](https://linux-hardware.org/?probe=20ea0cd55c) | Jan 23, 2021 |
| Acer          | Extensa 5220                | [9fe95abf63](https://linux-hardware.org/?probe=9fe95abf63) | Jan 23, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [b7b3175352](https://linux-hardware.org/?probe=b7b3175352) | Jan 14, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [ed7d9bff15](https://linux-hardware.org/?probe=ed7d9bff15) | Jan 13, 2021 |
| Acer          | Aspire 5750G                | [91885a7829](https://linux-hardware.org/?probe=91885a7829) | Jan 05, 2021 |
| Acer          | Aspire 5750G                | [34198a369d](https://linux-hardware.org/?probe=34198a369d) | Dec 26, 2020 |
| HP            | EliteBook 855 G7 Noteboo... | [f4ab3e4295](https://linux-hardware.org/?probe=f4ab3e4295) | Dec 26, 2020 |
| Acer          | Aspire 1410                 | [3ff80e7b33](https://linux-hardware.org/?probe=3ff80e7b33) | Dec 26, 2020 |
| ASUSTek       | X510UNR                     | [44990d7fc0](https://linux-hardware.org/?probe=44990d7fc0) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | [e6e91c5ea2](https://linux-hardware.org/?probe=e6e91c5ea2) | Dec 16, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [5b56323f14](https://linux-hardware.org/?probe=5b56323f14) | Dec 15, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [2c7c774492](https://linux-hardware.org/?probe=2c7c774492) | Dec 15, 2020 |
| Toshiba       | Satellite L855              | [48d0f1a04c](https://linux-hardware.org/?probe=48d0f1a04c) | Dec 08, 2020 |
| Dell          | Latitude E7470              | [3c76403f27](https://linux-hardware.org/?probe=3c76403f27) | Dec 01, 2020 |
| Packard Be... | EasyNote TE11HC             | [a58e43a971](https://linux-hardware.org/?probe=a58e43a971) | Nov 20, 2020 |
| Packard Be... | EasyNote TE11HC             | [374504e0bd](https://linux-hardware.org/?probe=374504e0bd) | Nov 20, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [1310e54c33](https://linux-hardware.org/?probe=1310e54c33) | Nov 20, 2020 |
| ASUSTek       | X510UNR                     | [fb41abdfb1](https://linux-hardware.org/?probe=fb41abdfb1) | Nov 13, 2020 |
| Alienware     | 17                          | [59fdbdd4d7](https://linux-hardware.org/?probe=59fdbdd4d7) | Nov 11, 2020 |
| ASUSTek       | GL553VD                     | [86837daf1c](https://linux-hardware.org/?probe=86837daf1c) | Nov 10, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cf2cbcbe72](https://linux-hardware.org/?probe=cf2cbcbe72) | Nov 05, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [39dcf2485b](https://linux-hardware.org/?probe=39dcf2485b) | Nov 03, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [f507c9b3e5](https://linux-hardware.org/?probe=f507c9b3e5) | Oct 25, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1b2dd49d08](https://linux-hardware.org/?probe=1b2dd49d08) | Oct 20, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [b3e5017b13](https://linux-hardware.org/?probe=b3e5017b13) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | [09fbf70f49](https://linux-hardware.org/?probe=09fbf70f49) | Oct 16, 2020 |
| HP            | ProBook 450 G1              | [c69e6488fd](https://linux-hardware.org/?probe=c69e6488fd) | Oct 14, 2020 |
| Dell          | G5 5587                     | [ba6fbeb10c](https://linux-hardware.org/?probe=ba6fbeb10c) | Oct 09, 2020 |
| Dell          | G5 5587                     | [8b28232f32](https://linux-hardware.org/?probe=8b28232f32) | Oct 09, 2020 |
| HP            | ProBook 4720s               | [a882fdd653](https://linux-hardware.org/?probe=a882fdd653) | Oct 02, 2020 |
| ASUSTek       | N56VZ                       | [d4d74a6e34](https://linux-hardware.org/?probe=d4d74a6e34) | Sep 29, 2020 |
| ASUSTek       | K52JT                       | [2acb54cb0d](https://linux-hardware.org/?probe=2acb54cb0d) | Sep 28, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [87092c4768](https://linux-hardware.org/?probe=87092c4768) | Sep 21, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [48825acdce](https://linux-hardware.org/?probe=48825acdce) | Sep 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [aef0cb23ec](https://linux-hardware.org/?probe=aef0cb23ec) | Sep 16, 2020 |
| HP            | ProBook 450 G6              | [6fffc9928f](https://linux-hardware.org/?probe=6fffc9928f) | Sep 10, 2020 |
| HP            | ProBook 450 G6              | [7465caa486](https://linux-hardware.org/?probe=7465caa486) | Sep 10, 2020 |
| Lenovo        | ThinkPad T460s 20F90058M... | [352f3932b4](https://linux-hardware.org/?probe=352f3932b4) | Sep 09, 2020 |
| Dell          | Latitude 5491               | [06d4120fc1](https://linux-hardware.org/?probe=06d4120fc1) | Sep 08, 2020 |
| Lenovo        | ThinkPad L440 20ASS10F00    | [cb6b544787](https://linux-hardware.org/?probe=cb6b544787) | Sep 04, 2020 |
| Timi          | TM1701                      | [4c01fca357](https://linux-hardware.org/?probe=4c01fca357) | Aug 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [d053bf3f76](https://linux-hardware.org/?probe=d053bf3f76) | Aug 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [2551496802](https://linux-hardware.org/?probe=2551496802) | Aug 18, 2020 |
| Dell          | XPS M1330                   | [4a907eebb9](https://linux-hardware.org/?probe=4a907eebb9) | Aug 02, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [a52cd7499e](https://linux-hardware.org/?probe=a52cd7499e) | Jul 28, 2020 |
| Acer          | Swift SF314-54G             | [a4948f0d33](https://linux-hardware.org/?probe=a4948f0d33) | Jul 24, 2020 |
| Acer          | Swift SF314-54G             | [cd250d0e7b](https://linux-hardware.org/?probe=cd250d0e7b) | Jul 24, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [810f713a78](https://linux-hardware.org/?probe=810f713a78) | Jul 24, 2020 |
| HP            | Pavilion dv6                | [4c09684767](https://linux-hardware.org/?probe=4c09684767) | Jul 23, 2020 |
| ASUSTek       | N71Ja                       | [db78759a1a](https://linux-hardware.org/?probe=db78759a1a) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [0fb6ac937d](https://linux-hardware.org/?probe=0fb6ac937d) | Jul 06, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [fc16d36603](https://linux-hardware.org/?probe=fc16d36603) | Jul 03, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [9c1c6b6919](https://linux-hardware.org/?probe=9c1c6b6919) | Jun 30, 2020 |
| Dell          | XPS 15 7590                 | [78351d2937](https://linux-hardware.org/?probe=78351d2937) | Jun 22, 2020 |
| Lenovo        | ThinkPad L460 20FU0007MH    | [27a87ca264](https://linux-hardware.org/?probe=27a87ca264) | Jun 18, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [9c0419884f](https://linux-hardware.org/?probe=9c0419884f) | Jun 17, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | [ed27c7aa81](https://linux-hardware.org/?probe=ed27c7aa81) | Jun 10, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | [574368a188](https://linux-hardware.org/?probe=574368a188) | Jun 09, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [ebac9eaefe](https://linux-hardware.org/?probe=ebac9eaefe) | Jun 02, 2020 |
| HP            | EliteBook 8440p             | [cc3e01ff0f](https://linux-hardware.org/?probe=cc3e01ff0f) | May 29, 2020 |
| Lenovo        | Y50-70 20378                | [85443edb8d](https://linux-hardware.org/?probe=85443edb8d) | May 22, 2020 |
| Dell          | Inspiron 1520               | [368e9f53e5](https://linux-hardware.org/?probe=368e9f53e5) | May 22, 2020 |
| Samsung       | RC530/RC730                 | [7e180f5fd2](https://linux-hardware.org/?probe=7e180f5fd2) | May 21, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [04ed3686b1](https://linux-hardware.org/?probe=04ed3686b1) | May 19, 2020 |
| ASUSTek       | X51RL                       | [afee28a69b](https://linux-hardware.org/?probe=afee28a69b) | May 16, 2020 |
| HP            | EliteBook 8440p             | [5856d8fd4a](https://linux-hardware.org/?probe=5856d8fd4a) | Apr 30, 2020 |
| Lenovo        | ThinkPad Edge E320 12985... | [e4a1ece1ec](https://linux-hardware.org/?probe=e4a1ece1ec) | Apr 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [70daf3ad77](https://linux-hardware.org/?probe=70daf3ad77) | Apr 20, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [c4b061e0f5](https://linux-hardware.org/?probe=c4b061e0f5) | Apr 19, 2020 |
| Lenovo        | V130-15IGM 81HL             | [11251407bd](https://linux-hardware.org/?probe=11251407bd) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | [37f223475f](https://linux-hardware.org/?probe=37f223475f) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | [21a5c2580f](https://linux-hardware.org/?probe=21a5c2580f) | Apr 10, 2020 |
| ASUSTek       | M50SA                       | [a7381b478e](https://linux-hardware.org/?probe=a7381b478e) | Apr 10, 2020 |
| Dell          | Inspiron 3542               | [38086a42be](https://linux-hardware.org/?probe=38086a42be) | Apr 01, 2020 |
| Dell          | Inspiron 3542               | [2246b94acb](https://linux-hardware.org/?probe=2246b94acb) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | [0552ab024f](https://linux-hardware.org/?probe=0552ab024f) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | [0fd03337ad](https://linux-hardware.org/?probe=0fd03337ad) | Mar 29, 2020 |
| Acer          | Aspire 5733                 | [055f9887c3](https://linux-hardware.org/?probe=055f9887c3) | Mar 29, 2020 |
| Lenovo        | G550 20023                  | [0e9b1fb324](https://linux-hardware.org/?probe=0e9b1fb324) | Mar 29, 2020 |
| HP            | 630                         | [fc76abe01b](https://linux-hardware.org/?probe=fc76abe01b) | Mar 29, 2020 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [23a0bdb230](https://linux-hardware.org/?probe=23a0bdb230) | Mar 19, 2020 |
| ASUSTek       | K43E                        | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |
| ASUSTek       | K53E                        | [8729f56cdc](https://linux-hardware.org/?probe=8729f56cdc) | Mar 07, 2020 |
| ASUSTek       | K53SV                       | [3b537b4a10](https://linux-hardware.org/?probe=3b537b4a10) | Mar 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f08088a64d](https://linux-hardware.org/?probe=f08088a64d) | Feb 20, 2020 |
| HP            | ProBook 4740s               | [4d4d26ef02](https://linux-hardware.org/?probe=4d4d26ef02) | Feb 03, 2020 |
| Lenovo        | ThinkPad E590 20NB0065MH    | [e895371f73](https://linux-hardware.org/?probe=e895371f73) | Feb 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [226b976601](https://linux-hardware.org/?probe=226b976601) | Jan 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6973864306](https://linux-hardware.org/?probe=6973864306) | Jan 25, 2020 |
| Acer          | Aspire V3-772               | [17005306cd](https://linux-hardware.org/?probe=17005306cd) | Jan 24, 2020 |
| ASUSTek       | K52JT                       | [4335a97dd6](https://linux-hardware.org/?probe=4335a97dd6) | Jan 24, 2020 |
| Dell          | G3 3579                     | [56f84db06b](https://linux-hardware.org/?probe=56f84db06b) | Jan 22, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [f22d44d39f](https://linux-hardware.org/?probe=f22d44d39f) | Jan 22, 2020 |
| Panasonic     | CF-52WEBBYDE                | [0d21ee7063](https://linux-hardware.org/?probe=0d21ee7063) | Jan 17, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [cf8ada0ad0](https://linux-hardware.org/?probe=cf8ada0ad0) | Jan 16, 2020 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | [f57bc0120b](https://linux-hardware.org/?probe=f57bc0120b) | Jan 15, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | [4ea8d503ae](https://linux-hardware.org/?probe=4ea8d503ae) | Dec 13, 2019 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | [a298251c28](https://linux-hardware.org/?probe=a298251c28) | Dec 13, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [5b4aff6fe8](https://linux-hardware.org/?probe=5b4aff6fe8) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [abeaa01348](https://linux-hardware.org/?probe=abeaa01348) | Dec 03, 2019 |
| HP            | EliteBook 856               | [80cf2af707](https://linux-hardware.org/?probe=80cf2af707) | Nov 22, 2019 |
| HP            | Pavilion dv6                | [6f6270eb8e](https://linux-hardware.org/?probe=6f6270eb8e) | Nov 16, 2019 |
| HP            | Pavilion dv6                | [c08e4bac64](https://linux-hardware.org/?probe=c08e4bac64) | Nov 16, 2019 |
| HP            | EliteBook 8460p             | [56a12d5f20](https://linux-hardware.org/?probe=56a12d5f20) | Nov 09, 2019 |
| Acer          | AOD260                      | [a911172500](https://linux-hardware.org/?probe=a911172500) | Nov 09, 2019 |
| Sony          | VGN-C260E                   | [c623de88ee](https://linux-hardware.org/?probe=c623de88ee) | Oct 24, 2019 |
| Lenovo        | G505s 20255                 | [36deb3b32d](https://linux-hardware.org/?probe=36deb3b32d) | Oct 13, 2019 |
| HP            | Pavilion dv6                | [c2264e7abd](https://linux-hardware.org/?probe=c2264e7abd) | Oct 11, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | [77b1afae40](https://linux-hardware.org/?probe=77b1afae40) | Oct 09, 2019 |
| ASUSTek       | K53SV                       | [61f7ec13d8](https://linux-hardware.org/?probe=61f7ec13d8) | Sep 19, 2019 |
| ASUSTek       | K53E                        | [71fd2610fe](https://linux-hardware.org/?probe=71fd2610fe) | Sep 15, 2019 |
| ASUSTek       | K53E                        | [e435064ad7](https://linux-hardware.org/?probe=e435064ad7) | Sep 15, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [3baafefb84](https://linux-hardware.org/?probe=3baafefb84) | Aug 27, 2019 |
| Prestigio     | PSB141C02                   | [3e96d56c17](https://linux-hardware.org/?probe=3e96d56c17) | Aug 25, 2019 |
| ASUSTek       | K53E                        | [c1811b7ec3](https://linux-hardware.org/?probe=c1811b7ec3) | Aug 23, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | [15419d9561](https://linux-hardware.org/?probe=15419d9561) | Aug 20, 2019 |
| HP            | Laptop 15-bw0xx             | [7653d7fa4d](https://linux-hardware.org/?probe=7653d7fa4d) | Jul 29, 2019 |
| Lenovo        | G550 20023                  | [601d53f9eb](https://linux-hardware.org/?probe=601d53f9eb) | Jul 23, 2019 |
| Lenovo        | ThinkPad R500 27327KG       | [c8b31c9d99](https://linux-hardware.org/?probe=c8b31c9d99) | Jun 04, 2019 |
| Dell          | Inspiron N5010              | [23d8e1dd30](https://linux-hardware.org/?probe=23d8e1dd30) | May 31, 2019 |
| Acer          | TravelMate 5740G            | [0d4611c952](https://linux-hardware.org/?probe=0d4611c952) | May 25, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [be887070fe](https://linux-hardware.org/?probe=be887070fe) | May 17, 2019 |
| Toshiba       | Satellite C50D-A-13G        | [c39268dff8](https://linux-hardware.org/?probe=c39268dff8) | May 13, 2019 |
| Toshiba       | Satellite C50D-A-13G        | [e0d133befc](https://linux-hardware.org/?probe=e0d133befc) | May 13, 2019 |
| HP            | ProBook 6555b               | [598fc6c1ca](https://linux-hardware.org/?probe=598fc6c1ca) | May 13, 2019 |
| HP            | ProBook 4540s               | [2e61bfe1be](https://linux-hardware.org/?probe=2e61bfe1be) | Apr 28, 2019 |
| HP            | ProBook 4540s               | [8d460232a9](https://linux-hardware.org/?probe=8d460232a9) | Apr 28, 2019 |
| Dell          | Inspiron 5737               | [2c7d308e3a](https://linux-hardware.org/?probe=2c7d308e3a) | Apr 26, 2019 |
| Dell          | Inspiron 5737               | [dcf03f780e](https://linux-hardware.org/?probe=dcf03f780e) | Apr 26, 2019 |
| Acer          | TravelMate 5740G            | [6b69828c13](https://linux-hardware.org/?probe=6b69828c13) | Apr 07, 2019 |
| Sony          | VPCZ1390S                   | [eb4e58c4d9](https://linux-hardware.org/?probe=eb4e58c4d9) | Mar 05, 2019 |
| Sony          | VPCZ1390S                   | [8995c67e48](https://linux-hardware.org/?probe=8995c67e48) | Mar 05, 2019 |
| Lenovo        | ThinkPad X230 2325AEG       | [2b8bcfe576](https://linux-hardware.org/?probe=2b8bcfe576) | Feb 19, 2019 |
| ASUSTek       | X550LB                      | [992697103b](https://linux-hardware.org/?probe=992697103b) | Jan 18, 2019 |
| ASUSTek       | X550LB                      | [5228ac3dbc](https://linux-hardware.org/?probe=5228ac3dbc) | Jan 18, 2019 |
| Lenovo        | ThinkPad L440 20ASA10P00    | [dffa2ed3ef](https://linux-hardware.org/?probe=dffa2ed3ef) | Dec 20, 2018 |
| Lenovo        | ThinkPad L440 20ASA10P00    | [e192353344](https://linux-hardware.org/?probe=e192353344) | Dec 20, 2018 |
| Lenovo        | G550 20023                  | [54fd0e13d2](https://linux-hardware.org/?probe=54fd0e13d2) | Oct 29, 2018 |
| Lenovo        | G550 20023                  | [3011864d4b](https://linux-hardware.org/?probe=3011864d4b) | Oct 25, 2018 |
| ASUSTek       | K53E                        | [0e63193763](https://linux-hardware.org/?probe=0e63193763) | Oct 21, 2018 |
| ASUSTek       | K53E                        | [8a053e30bf](https://linux-hardware.org/?probe=8a053e30bf) | Sep 30, 2018 |
| ASUSTek       | K53E                        | [8e1eab57d7](https://linux-hardware.org/?probe=8e1eab57d7) | Sep 03, 2018 |
| ASUSTek       | 1225B                       | [fb333d2cde](https://linux-hardware.org/?probe=fb333d2cde) | Aug 23, 2018 |
| ASUSTek       | K53E                        | [8ebafe3965](https://linux-hardware.org/?probe=8ebafe3965) | Aug 04, 2018 |
| ASUSTek       | K53E                        | [58b632622d](https://linux-hardware.org/?probe=58b632622d) | Apr 15, 2018 |
| ASUSTek       | X555LN                      | [9760e114b0](https://linux-hardware.org/?probe=9760e114b0) | Apr 07, 2018 |
| ASUSTek       | X555LN                      | [c3f232766b](https://linux-hardware.org/?probe=c3f232766b) | Apr 07, 2018 |
| ASUSTek       | K53SV                       | [e3e865dedf](https://linux-hardware.org/?probe=e3e865dedf) | Apr 06, 2018 |
| ASUSTek       | K53SV                       | [041cd61823](https://linux-hardware.org/?probe=041cd61823) | Dec 14, 2017 |
| Acer          | Aspire 5610Z                | [c79786fae0](https://linux-hardware.org/?probe=c79786fae0) | Dec 12, 2017 |
| Dell          | Inspiron 3537               | [0cb8d57f73](https://linux-hardware.org/?probe=0cb8d57f73) | Sep 25, 2017 |
| ASUSTek       | M50Vc                       | [9224093b58](https://linux-hardware.org/?probe=9224093b58) | Aug 22, 2017 |
| ASUSTek       | K53SV                       | [366e5e884c](https://linux-hardware.org/?probe=366e5e884c) | Jun 23, 2017 |
| Lenovo        | B50-10 80QR                 | [0ba3b01a3b](https://linux-hardware.org/?probe=0ba3b01a3b) | May 17, 2017 |
| Lenovo        | B50-10 80QR                 | [0a9d97b358](https://linux-hardware.org/?probe=0a9d97b358) | Apr 11, 2017 |
| Dell          | Precision M4600             | [2a09c39637](https://linux-hardware.org/?probe=2a09c39637) | Mar 15, 2017 |
| Dell          | Precision M4600             | [c9a115e18c](https://linux-hardware.org/?probe=c9a115e18c) | Mar 15, 2017 |
| Acer          | Aspire ES1-711              | [0f7625ddc4](https://linux-hardware.org/?probe=0f7625ddc4) | Mar 10, 2017 |
| Acer          | Aspire ES1-711              | [64cea7b4eb](https://linux-hardware.org/?probe=64cea7b4eb) | Mar 10, 2017 |
| Dell          | Precision M4600             | [e851921cd7](https://linux-hardware.org/?probe=e851921cd7) | Oct 24, 2016 |
| Dell          | Latitude E6440              | [ea1b5da2e7](https://linux-hardware.org/?probe=ea1b5da2e7) | Dec 07, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 23        | 12.57%  |
| Ubuntu 18.04      | 19        | 10.38%  |
| Arch Rolling      | 8         | 4.37%   |
| Ubuntu 19.04      | 5         | 2.73%   |
| ROSA R11          | 5         | 2.73%   |
| Pop!_OS 21.04     | 5         | 2.73%   |
| Zorin 16          | 4         | 2.19%   |
| Xubuntu 20.04     | 4         | 2.19%   |
| ROSA R9           | 4         | 2.19%   |
| ROSA R8.1         | 4         | 2.19%   |
| ROSA R10          | 4         | 2.19%   |
| Pop!_OS 20.04     | 4         | 2.19%   |
| OpenMandriva 4.2  | 4         | 2.19%   |
| Linux Mint 20     | 4         | 2.19%   |
| Xubuntu 19.10     | 3         | 1.64%   |
| ROSA R11.1        | 3         | 1.64%   |
| Linux Mint 20.1   | 3         | 1.64%   |
| KDE neon 20.04    | 3         | 1.64%   |
| Debian 10         | 3         | 1.64%   |
| ArcoLinux Rolling | 3         | 1.64%   |
| Arch              | 3         | 1.64%   |
| Zorin 15          | 2         | 1.09%   |
| Ubuntu 22.04      | 2         | 1.09%   |
| Ubuntu 21.04      | 2         | 1.09%   |
| Ubuntu 20.10      | 2         | 1.09%   |
| Ubuntu 19.10      | 2         | 1.09%   |
| Ubuntu 16.04      | 2         | 1.09%   |
| RED X3            | 2         | 1.09%   |
| Pop!_OS 21.10     | 2         | 1.09%   |
| OpenMandriva 4.3  | 2         | 1.09%   |
| Manjaro 20.2.1    | 2         | 1.09%   |
| Manjaro 20.2      | 2         | 1.09%   |
| Linux Mint 19.2   | 2         | 1.09%   |
| Fedora 34         | 2         | 1.09%   |
| Xubuntu 18.04     | 1         | 0.55%   |
| Ubuntu MATE 18.04 | 1         | 0.55%   |
| Ubuntu 21.10      | 1         | 0.55%   |
| Ubuntu 18.10      | 1         | 0.55%   |
| ROSA R8           | 1         | 0.55%   |
| RHEL 8            | 1         | 0.55%   |
| Pop!_OS 20.10     | 1         | 0.55%   |
| Peppermint 10     | 1         | 0.55%   |
| openSUSE 13.2     | 1         | 0.55%   |
| Manjaro 21.2.4    | 1         | 0.55%   |
| Manjaro 20.1.1    | 1         | 0.55%   |
| Manjaro 20.1      | 1         | 0.55%   |
| Manjaro 20.0      | 1         | 0.55%   |
| Manjaro 18.1.5    | 1         | 0.55%   |
| Manjaro 18.0.4    | 1         | 0.55%   |
| Manjaro 18.0.0    | 1         | 0.55%   |
| Manjaro           | 1         | 0.55%   |
| Lubuntu 21.04     | 1         | 0.55%   |
| Lubuntu 20.04     | 1         | 0.55%   |
| Lubuntu 18.10     | 1         | 0.55%   |
| LMDE 5            | 1         | 0.55%   |
| Linux Mint 20.3   | 1         | 0.55%   |
| Linux Mint 19.3   | 1         | 0.55%   |
| Kubuntu 20.04     | 1         | 0.55%   |
| KDE neon 18.04    | 1         | 0.55%   |
| Gentoo 2.7        | 1         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 56        | 33.33%  |
| ROSA         | 15        | 8.93%   |
| Pop!_OS      | 12        | 7.14%   |
| Linux Mint   | 11        | 6.55%   |
| Manjaro      | 10        | 5.95%   |
| Arch         | 10        | 5.95%   |
| Zorin        | 6         | 3.57%   |
| Xubuntu      | 6         | 3.57%   |
| OpenMandriva | 6         | 3.57%   |
| Fedora       | 6         | 3.57%   |
| KDE neon     | 4         | 2.38%   |
| Debian       | 4         | 2.38%   |
| Lubuntu      | 3         | 1.79%   |
| Endless      | 3         | 1.79%   |
| ArcoLinux    | 3         | 1.79%   |
| RED          | 2         | 1.19%   |
| Ubuntu MATE  | 1         | 0.6%    |
| RHEL         | 1         | 0.6%    |
| Peppermint   | 1         | 0.6%    |
| openSUSE     | 1         | 0.6%    |
| LMDE         | 1         | 0.6%    |
| Kubuntu      | 1         | 0.6%    |
| Gentoo       | 1         | 0.6%    |
| Elementary   | 1         | 0.6%    |
| Drauger OS   | 1         | 0.6%    |
| CentOS       | 1         | 0.6%    |
| Artix        | 1         | 0.6%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 5         | 2.54%   |
| 5.13.0-40-generic               | 5         | 2.54%   |
| 5.10.14-desktop-1omv4002        | 4         | 2.03%   |
| 5.4.0-48-generic                | 3         | 1.52%   |
| 5.4.0-47-generic                | 3         | 1.52%   |
| 5.3.0-26-generic                | 3         | 1.52%   |
| 4.9.41-nrj-desktop-1rosa-x86_64 | 3         | 1.52%   |
| 4.15.0-91-generic               | 3         | 1.52%   |
| 5.8.0-44-generic                | 2         | 1.02%   |
| 5.4.0-7634-generic              | 2         | 1.02%   |
| 5.4.0-73-generic                | 2         | 1.02%   |
| 5.4.0-66-generic                | 2         | 1.02%   |
| 5.4.0-52-generic                | 2         | 1.02%   |
| 5.4.0-31-generic                | 2         | 1.02%   |
| 5.3.0-28-generic                | 2         | 1.02%   |
| 5.13.0-35-generic               | 2         | 1.02%   |
| 5.11.0-7633-generic             | 2         | 1.02%   |
| 5.0.0-37-generic                | 2         | 1.02%   |
| 5.0.0-25-generic                | 2         | 1.02%   |
| 4.4.16-nrj-desktop-1rosa-x86_64 | 2         | 1.02%   |
| 4.15.0-desktop-60.7rosa-i586    | 2         | 1.02%   |
| 4.15.0-29-generic               | 2         | 1.02%   |
| 5.9.3-1-MANJARO                 | 1         | 0.51%   |
| 5.9.16-1-MANJARO                | 1         | 0.51%   |
| 5.9.14-zen1-1-zen               | 1         | 0.51%   |
| 5.9.13-200.fc33.x86_64          | 1         | 0.51%   |
| 5.8.3-zen1-1-zen                | 1         | 0.51%   |
| 5.8.18-300.fc33.x86_64          | 1         | 0.51%   |
| 5.8.18-1-MANJARO                | 1         | 0.51%   |
| 5.8.11-arch1-1                  | 1         | 0.51%   |
| 5.8.11-1-MANJARO                | 1         | 0.51%   |
| 5.8.0-7630-generic              | 1         | 0.51%   |
| 5.8.0-7625-generic              | 1         | 0.51%   |
| 5.8.0-63-generic                | 1         | 0.51%   |
| 5.8.0-55-generic                | 1         | 0.51%   |
| 5.8.0-48-generic                | 1         | 0.51%   |
| 5.8.0-41-generic                | 1         | 0.51%   |
| 5.8.0-14-generic                | 1         | 0.51%   |
| 5.7.17-2-MANJARO                | 1         | 0.51%   |
| 5.6.5-1-MANJARO                 | 1         | 0.51%   |
| 5.6.13-arch1-1                  | 1         | 0.51%   |
| 5.4.83-generic-2rosa-x86_64     | 1         | 0.51%   |
| 5.4.70-1-lts                    | 1         | 0.51%   |
| 5.4.54-1-lts                    | 1         | 0.51%   |
| 5.4.32-generic-2rosa-x86_64     | 1         | 0.51%   |
| 5.4.19-200.fc31.x86_64          | 1         | 0.51%   |
| 5.4.13-arch1-1                  | 1         | 0.51%   |
| 5.4.13-3-MANJARO                | 1         | 0.51%   |
| 5.4.1-050401-generic            | 1         | 0.51%   |
| 5.4.0-88-generic                | 1         | 0.51%   |
| 5.4.0-7642-generic              | 1         | 0.51%   |
| 5.4.0-70-generic                | 1         | 0.51%   |
| 5.4.0-67-generic                | 1         | 0.51%   |
| 5.4.0-64-generic                | 1         | 0.51%   |
| 5.4.0-58-generic                | 1         | 0.51%   |
| 5.4.0-56-generic                | 1         | 0.51%   |
| 5.4.0-54-generic                | 1         | 0.51%   |
| 5.4.0-47-lowlatency             | 1         | 0.51%   |
| 5.4.0-42-lowlatency             | 1         | 0.51%   |
| 5.4.0-40-lowlatency             | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 18.48%  |
| 4.15.0  | 19        | 10.33%  |
| 5.3.0   | 13        | 7.07%   |
| 5.13.0  | 10        | 5.43%   |
| 5.0.0   | 10        | 5.43%   |
| 5.8.0   | 9         | 4.89%   |
| 5.11.0  | 6         | 3.26%   |
| 5.10.14 | 4         | 2.17%   |
| 4.18.0  | 4         | 2.17%   |
| 5.15.0  | 3         | 1.63%   |
| 4.9.41  | 3         | 1.63%   |
| 5.8.18  | 2         | 1.09%   |
| 5.8.11  | 2         | 1.09%   |
| 5.4.13  | 2         | 1.09%   |
| 5.10.16 | 2         | 1.09%   |
| 5.10.0  | 2         | 1.09%   |
| 4.9.9   | 2         | 1.09%   |
| 4.9.60  | 2         | 1.09%   |
| 4.9.20  | 2         | 1.09%   |
| 4.4.16  | 2         | 1.09%   |
| 4.19.0  | 2         | 1.09%   |
| 5.9.3   | 1         | 0.54%   |
| 5.9.16  | 1         | 0.54%   |
| 5.9.14  | 1         | 0.54%   |
| 5.9.13  | 1         | 0.54%   |
| 5.8.3   | 1         | 0.54%   |
| 5.7.17  | 1         | 0.54%   |
| 5.6.5   | 1         | 0.54%   |
| 5.6.13  | 1         | 0.54%   |
| 5.4.83  | 1         | 0.54%   |
| 5.4.70  | 1         | 0.54%   |
| 5.4.54  | 1         | 0.54%   |
| 5.4.32  | 1         | 0.54%   |
| 5.4.19  | 1         | 0.54%   |
| 5.4.1   | 1         | 0.54%   |
| 5.17.5  | 1         | 0.54%   |
| 5.17.12 | 1         | 0.54%   |
| 5.17.1  | 1         | 0.54%   |
| 5.16.7  | 1         | 0.54%   |
| 5.16.16 | 1         | 0.54%   |
| 5.16.11 | 1         | 0.54%   |
| 5.15.7  | 1         | 0.54%   |
| 5.15.25 | 1         | 0.54%   |
| 5.15.16 | 1         | 0.54%   |
| 5.15.15 | 1         | 0.54%   |
| 5.15.13 | 1         | 0.54%   |
| 5.15.11 | 1         | 0.54%   |
| 5.15.10 | 1         | 0.54%   |
| 5.14.8  | 1         | 0.54%   |
| 5.13.9  | 1         | 0.54%   |
| 5.13.19 | 1         | 0.54%   |
| 5.12.9  | 1         | 0.54%   |
| 5.12.5  | 1         | 0.54%   |
| 5.12.10 | 1         | 0.54%   |
| 5.12.0  | 1         | 0.54%   |
| 5.11.17 | 1         | 0.54%   |
| 5.11.16 | 1         | 0.54%   |
| 5.10.76 | 1         | 0.54%   |
| 5.10.7  | 1         | 0.54%   |
| 5.10.6  | 1         | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 22.65%  |
| 4.15    | 19        | 10.5%   |
| 5.8     | 14        | 7.73%   |
| 5.3     | 13        | 7.18%   |
| 5.10    | 13        | 7.18%   |
| 5.13    | 12        | 6.63%   |
| 5.0     | 11        | 6.08%   |
| 4.9     | 11        | 6.08%   |
| 5.15    | 10        | 5.52%   |
| 5.11    | 8         | 4.42%   |
| 5.12    | 4         | 2.21%   |
| 4.18    | 4         | 2.21%   |
| 5.9     | 3         | 1.66%   |
| 5.17    | 3         | 1.66%   |
| 5.16    | 3         | 1.66%   |
| 4.4     | 3         | 1.66%   |
| 5.6     | 2         | 1.1%    |
| 4.19    | 2         | 1.1%    |
| 5.7     | 1         | 0.55%   |
| 5.14    | 1         | 0.55%   |
| 4.14    | 1         | 0.55%   |
| 4.1     | 1         | 0.55%   |
| 3.16    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 147       | 93.04%  |
| i686   | 11        | 6.96%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 67        | 39.41%  |
| Unknown         | 23        | 13.53%  |
| KDE5            | 20        | 11.76%  |
| XFCE            | 15        | 8.82%   |
| KDE4            | 13        | 7.65%   |
| X-Cinnamon      | 10        | 5.88%   |
| KDE             | 5         | 2.94%   |
| LXQt            | 4         | 2.35%   |
| Unity           | 2         | 1.18%   |
| MATE            | 2         | 1.18%   |
| awesome         | 2         | 1.18%   |
| Pantheon        | 1         | 0.59%   |
| LXDE            | 1         | 0.59%   |
| GNOME Flashback | 1         | 0.59%   |
| Enlightenment   | 1         | 0.59%   |
| Deepin          | 1         | 0.59%   |
| Cinnamon        | 1         | 0.59%   |
| Budgie          | 1         | 0.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 134       | 81.21%  |
| Wayland | 16        | 9.7%    |
| Unknown | 10        | 6.06%   |
| Tty     | 5         | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 50.3%   |
| GDM     | 23        | 13.94%  |
| SDDM    | 21        | 12.73%  |
| KDM     | 12        | 7.27%   |
| LightDM | 10        | 6.06%   |
| TDM     | 8         | 4.85%   |
| GDM3    | 7         | 4.24%   |
| XDM     | 1         | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 92        | 56.1%   |
| Unknown | 37        | 22.56%  |
| lt_LT   | 25        | 15.24%  |
| ru_RU   | 5         | 3.05%   |
| en_GB   | 2         | 1.22%   |
| C       | 2         | 1.22%   |
| en_AU   | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 81        | 50.31%  |
| BIOS | 80        | 49.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 124       | 77.02%  |
| Unknown | 16        | 9.94%   |
| Btrfs   | 8         | 4.97%   |
| Overlay | 7         | 4.35%   |
| Xfs     | 4         | 2.48%   |
| Zfs     | 1         | 0.62%   |
| ExX4    | 1         | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 93        | 57.76%  |
| GPT     | 50        | 31.06%  |
| MBR     | 18        | 11.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 142       | 88.75%  |
| Yes       | 18        | 11.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 127       | 79.38%  |
| Yes       | 33        | 20.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 49        | 31.41%  |
| ASUSTek Computer    | 32        | 20.51%  |
| Dell                | 27        | 17.31%  |
| Hewlett-Packard     | 20        | 12.82%  |
| Acer                | 11        | 7.05%   |
| Samsung Electronics | 3         | 1.92%   |
| Toshiba             | 2         | 1.28%   |
| Sony                | 2         | 1.28%   |
| Panasonic           | 2         | 1.28%   |
| Timi                | 1         | 0.64%   |
| Prestigio           | 1         | 0.64%   |
| Packard Bell        | 1         | 0.64%   |
| Jumper              | 1         | 0.64%   |
| HUAWEI              | 1         | 0.64%   |
| eMachines           | 1         | 0.64%   |
| Alienware           | 1         | 0.64%   |
| Unknown             | 1         | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo ThinkPad T490 20N3000KMH                       | 2         | 1.28%   |
| Lenovo IdeaPad Y700-15ISK 80NV                        | 2         | 1.28%   |
| Lenovo G550 20023                                     | 2         | 1.28%   |
| HP EliteBook 8460p                                    | 2         | 1.28%   |
| ASUS K53E                                             | 2         | 1.28%   |
| Toshiba Satellite L855                                | 1         | 0.64%   |
| Toshiba Satellite C50D-A-13G                          | 1         | 0.64%   |
| Timi TM1701                                           | 1         | 0.64%   |
| Sony VPCZ1390S                                        | 1         | 0.64%   |
| Sony VGN-C260E                                        | 1         | 0.64%   |
| Samsung RC530/RC730                                   | 1         | 0.64%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.64%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.64%   |
| Prestigio PSB141C02                                   | 1         | 0.64%   |
| Panasonic CF-52WEBBYDE                                | 1         | 0.64%   |
| Panasonic CF-52VDA131M                                | 1         | 0.64%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.64%   |
| Lenovo Yoga Creator 7 15IMH05 82DS                    | 1         | 0.64%   |
| Lenovo Y50-70 20378                                   | 1         | 0.64%   |
| Lenovo V130-15IGM 81HL                                | 1         | 0.64%   |
| Lenovo ThinkPad X230 2325AEG                          | 1         | 0.64%   |
| Lenovo ThinkPad X1 Nano Gen 1 20UN0060MH              | 1         | 0.64%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006KPB              | 1         | 0.64%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS03800              | 1         | 0.64%   |
| Lenovo ThinkPad W530 243852U                          | 1         | 0.64%   |
| Lenovo ThinkPad T60 1951FDG                           | 1         | 0.64%   |
| Lenovo ThinkPad T500 2241W8Q                          | 1         | 0.64%   |
| Lenovo ThinkPad T480 20L50002MH                       | 1         | 0.64%   |
| Lenovo ThinkPad T460s 20F90058MH                      | 1         | 0.64%   |
| Lenovo ThinkPad T440p 20AWS4XN00                      | 1         | 0.64%   |
| Lenovo ThinkPad T430 2347EV8                          | 1         | 0.64%   |
| Lenovo ThinkPad T15 Gen 1 20S6005HMH                  | 1         | 0.64%   |
| Lenovo ThinkPad S1 Yoga 12 20DK002EMH                 | 1         | 0.64%   |
| Lenovo ThinkPad R500 27327KG                          | 1         | 0.64%   |
| Lenovo ThinkPad P53 20QN0034MH                        | 1         | 0.64%   |
| Lenovo ThinkPad P15 Gen 1 20STS19600                  | 1         | 0.64%   |
| Lenovo ThinkPad P14s Gen 2a 21A0000CMH                | 1         | 0.64%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH                   | 1         | 0.64%   |
| Lenovo ThinkPad L580 20LW0010GE                       | 1         | 0.64%   |
| Lenovo ThinkPad L460 20FU0007MH                       | 1         | 0.64%   |
| Lenovo ThinkPad L440 20ASS10F00                       | 1         | 0.64%   |
| Lenovo ThinkPad L440 20ASA10P00                       | 1         | 0.64%   |
| Lenovo ThinkPad L14 Gen 1 20U50003GE                  | 1         | 0.64%   |
| Lenovo ThinkPad Edge E540 20C6CTO1WW                  | 1         | 0.64%   |
| Lenovo ThinkPad Edge E320 12985PG                     | 1         | 0.64%   |
| Lenovo ThinkPad E590 20NB0065MH                       | 1         | 0.64%   |
| Lenovo ThinkPad E490 20N8CTO1WW                       | 1         | 0.64%   |
| Lenovo ThinkPad E15 Gen 2 20TD004NMH                  | 1         | 0.64%   |
| Lenovo ThinkPad E15 Gen 2 20T8000RMX                  | 1         | 0.64%   |
| Lenovo Legion Y530-15ICH 81FV                         | 1         | 0.64%   |
| Lenovo Legion 5 15ARH05H 82B1                         | 1         | 0.64%   |
| Lenovo IdeaPad MIIX 700-12ISK 80QL                    | 1         | 0.64%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                 | 1         | 0.64%   |
| Lenovo IdeaPad 710S-13ISK 80SW                        | 1         | 0.64%   |
| Lenovo IdeaPad 330-15IGM 81D1                         | 1         | 0.64%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 1         | 0.64%   |
| Lenovo G505s 20255                                    | 1         | 0.64%   |
| Lenovo G500 20236                                     | 1         | 0.64%   |
| Lenovo Flex 2-15 20405                                | 1         | 0.64%   |
| Lenovo B50-10 80QR                                    | 1         | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 31        | 19.87%  |
| Dell Inspiron          | 11        | 7.05%   |
| HP ProBook             | 8         | 5.13%   |
| Lenovo IdeaPad         | 7         | 4.49%   |
| Dell Latitude          | 7         | 4.49%   |
| Acer Aspire            | 7         | 4.49%   |
| HP EliteBook           | 5         | 3.21%   |
| Dell XPS               | 4         | 2.56%   |
| ASUS VivoBook          | 4         | 2.56%   |
| Toshiba Satellite      | 2         | 1.28%   |
| Lenovo Legion          | 2         | 1.28%   |
| Lenovo G550            | 2         | 1.28%   |
| HP Pavilion            | 2         | 1.28%   |
| HP Laptop              | 2         | 1.28%   |
| Dell Precision         | 2         | 1.28%   |
| ASUS ZenBook           | 2         | 1.28%   |
| ASUS TUF               | 2         | 1.28%   |
| ASUS K53E              | 2         | 1.28%   |
| Timi TM1701            | 1         | 0.64%   |
| Sony VPCZ1390S         | 1         | 0.64%   |
| Sony VGN-C260E         | 1         | 0.64%   |
| Samsung RC530          | 1         | 0.64%   |
| Samsung 530U3C         | 1         | 0.64%   |
| Samsung 300E5EV        | 1         | 0.64%   |
| Prestigio PSB141C02    | 1         | 0.64%   |
| Panasonic CF-52WEBBYDE | 1         | 0.64%   |
| Panasonic CF-52VDA131M | 1         | 0.64%   |
| Packard Bell EasyNote  | 1         | 0.64%   |
| Lenovo Yoga            | 1         | 0.64%   |
| Lenovo Y50-70          | 1         | 0.64%   |
| Lenovo V130-15IGM      | 1         | 0.64%   |
| Lenovo G505s           | 1         | 0.64%   |
| Lenovo G500            | 1         | 0.64%   |
| Lenovo Flex            | 1         | 0.64%   |
| Lenovo B50-10          | 1         | 0.64%   |
| Jumper EZbook          | 1         | 0.64%   |
| HUAWEI MACHD-WXX9      | 1         | 0.64%   |
| HP Compaq              | 1         | 0.64%   |
| HP 630                 | 1         | 0.64%   |
| HP 250                 | 1         | 0.64%   |
| eMachines eME443       | 1         | 0.64%   |
| Dell Vostro            | 1         | 0.64%   |
| Dell G5                | 1         | 0.64%   |
| Dell G3                | 1         | 0.64%   |
| ASUS X55A              | 1         | 0.64%   |
| ASUS X555LN            | 1         | 0.64%   |
| ASUS X551CAP           | 1         | 0.64%   |
| ASUS X550LB            | 1         | 0.64%   |
| ASUS X51RL             | 1         | 0.64%   |
| ASUS X510UNR           | 1         | 0.64%   |
| ASUS UX430UAR          | 1         | 0.64%   |
| ASUS ROG               | 1         | 0.64%   |
| ASUS N73SV             | 1         | 0.64%   |
| ASUS N71Ja             | 1         | 0.64%   |
| ASUS N56VZ             | 1         | 0.64%   |
| ASUS N53SV             | 1         | 0.64%   |
| ASUS M50Vc             | 1         | 0.64%   |
| ASUS M50SA             | 1         | 0.64%   |
| ASUS K53SV             | 1         | 0.64%   |
| ASUS K52JT             | 1         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 17        | 10.9%   |
| 2018 | 15        | 9.62%   |
| 2020 | 14        | 8.97%   |
| 2019 | 14        | 8.97%   |
| 2013 | 14        | 8.97%   |
| 2012 | 13        | 8.33%   |
| 2017 | 11        | 7.05%   |
| 2014 | 11        | 7.05%   |
| 2015 | 8         | 5.13%   |
| 2010 | 8         | 5.13%   |
| 2008 | 8         | 5.13%   |
| 2021 | 6         | 3.85%   |
| 2016 | 5         | 3.21%   |
| 2009 | 4         | 2.56%   |
| 2007 | 3         | 1.92%   |
| 2006 | 3         | 1.92%   |
| 2022 | 1         | 0.64%   |
| 2004 | 1         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 156       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 142       | 89.87%  |
| Enabled  | 16        | 10.13%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 40        | 25.16%  |
| 4.01-8.0   | 37        | 23.27%  |
| 3.01-4.0   | 37        | 23.27%  |
| 8.01-16.0  | 21        | 13.21%  |
| 32.01-64.0 | 9         | 5.66%   |
| 1.01-2.0   | 8         | 5.03%   |
| 2.01-3.0   | 3         | 1.89%   |
| 24.01-32.0 | 2         | 1.26%   |
| 0.51-1.0   | 2         | 1.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 60        | 33.33%  |
| 2.01-3.0  | 49        | 27.22%  |
| 4.01-8.0  | 27        | 15%     |
| 3.01-4.0  | 17        | 9.44%   |
| 0.51-1.0  | 16        | 8.89%   |
| 8.01-16.0 | 9         | 5%      |
| 0.01-0.5  | 2         | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 115       | 71.43%  |
| 2      | 42        | 26.09%  |
| 3      | 4         | 2.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 57.23%  |
| Yes       | 68        | 42.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 85.35%  |
| No        | 23        | 14.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 99.36%  |
| No        | 1         | 0.64%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 74.69%  |
| No        | 41        | 25.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Lithuania | 156       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Vilnius      | 84        | 50.91%  |
| Kaunas       | 25        | 15.15%  |
| Šiauliai    | 10        | 6.06%   |
| Klaipėda    | 9         | 5.45%   |
| Mažeikiai   | 4         | 2.42%   |
| Alytus       | 4         | 2.42%   |
| Panevezys    | 3         | 1.82%   |
| Jonava       | 3         | 1.82%   |
| Palanga      | 2         | 1.21%   |
| Kėdainiai   | 2         | 1.21%   |
| Želva       | 1         | 0.61%   |
| Visaginas    | 1         | 0.61%   |
| Vėžaičiai | 1         | 0.61%   |
| Ukmerge      | 1         | 0.61%   |
| Trakai       | 1         | 0.61%   |
| Tauragė     | 1         | 0.61%   |
| Šilalė     | 1         | 0.61%   |
| Serdokai     | 1         | 0.61%   |
| Šeduva      | 1         | 0.61%   |
| Rokiškis    | 1         | 0.61%   |
| Plungė      | 1         | 0.61%   |
| Pasvalys     | 1         | 0.61%   |
| Molėtai     | 1         | 0.61%   |
| Mauruciai    | 1         | 0.61%   |
| Marijampolė | 1         | 0.61%   |
| Maneikiai    | 1         | 0.61%   |
| Karkliniai   | 1         | 0.61%   |
| Gargždai    | 1         | 0.61%   |
| Anykščiai  | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 44     | 16%     |
| Seagate             | 26        | 35     | 13%     |
| WDC                 | 19        | 28     | 9.5%    |
| Toshiba             | 18        | 24     | 9%      |
| Kingston            | 18        | 22     | 9%      |
| SanDisk             | 13        | 14     | 6.5%    |
| Intel               | 12        | 14     | 6%      |
| Hitachi             | 9         | 16     | 4.5%    |
| A-DATA Technology   | 8         | 8      | 4%      |
| SK hynix            | 6         | 6      | 3%      |
| Patriot             | 5         | 6      | 2.5%    |
| Crucial             | 5         | 6      | 2.5%    |
| Unknown             | 4         | 14     | 2%      |
| Micron Technology   | 3         | 3      | 1.5%    |
| HGST                | 3         | 4      | 1.5%    |
| China               | 3         | 5      | 1.5%    |
| KingSpec            | 2         | 2      | 1%      |
| ASMT                | 2         | 2      | 1%      |
| Apacer              | 2         | 2      | 1%      |
| Union Memory        | 1         | 1      | 0.5%    |
| Team                | 1         | 1      | 0.5%    |
| Phison Electronics  | 1         | 2      | 0.5%    |
| OCZ                 | 1         | 1      | 0.5%    |
| LITEONIT            | 1         | 1      | 0.5%    |
| LITEON              | 1         | 2      | 0.5%    |
| GOODRAM             | 1         | 1      | 0.5%    |
| Fujitsu             | 1         | 1      | 0.5%    |
| FORESEE             | 1         | 1      | 0.5%    |
| Corsair             | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 256GB            | 5         | 2.42%   |
| Kingston SV300S37A120G 120GB SSD        | 5         | 2.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 1.93%   |
| Intel NVMe SSD Drive 512GB              | 4         | 1.93%   |
| Seagate ST9500325AS 500GB               | 3         | 1.45%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 1.45%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 1.45%   |
| Samsung SSD 850 EVO 250GB               | 3         | 1.45%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 1.45%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 1.45%   |
| Toshiba NVMe SSD Drive 512GB            | 2         | 0.97%   |
| Toshiba NVMe SSD Drive 256GB            | 2         | 0.97%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.97%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.97%   |
| Toshiba HDWL110 1TB                     | 2         | 0.97%   |
| SK hynix HFS256G39TND-N210A 256GB SSD   | 2         | 0.97%   |
| Seagate ST9160821AS 160GB               | 2         | 0.97%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 2         | 0.97%   |
| SanDisk X400 M.2 2280 256GB SSD         | 2         | 0.97%   |
| Samsung MZVLB1T0HBLR-000L7 1TB          | 2         | 0.97%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 0.97%   |
| Intel NVMe SSD Drive 32GB               | 2         | 0.97%   |
| Intel NVMe SSD Drive 256GB              | 2         | 0.97%   |
| Hitachi HTS545025B9A300 250GB           | 2         | 0.97%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 0.97%   |
| China SATA SSD 120GB                    | 2         | 0.97%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.48%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.48%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.48%   |
| WDC WD7500BPVX-60JC3T0 752GB            | 1         | 0.48%   |
| WDC WD7500BPKT-75PK4T0 752GB            | 1         | 0.48%   |
| WDC WD6400BPVT-22HXZT1 640GB            | 1         | 0.48%   |
| WDC WD5000BPVT-80HXZT3 500GB            | 1         | 0.48%   |
| WDC WD5000BEVT-24A0RT0 500GB            | 1         | 0.48%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 0.48%   |
| WDC WD2500BEVS-60UST0 250GB             | 1         | 0.48%   |
| WDC WD1600BEVS-60RST0 160GB             | 1         | 0.48%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 0.48%   |
| WDC WD1600BEVS-08VAT2 160GB             | 1         | 0.48%   |
| WDC WD10SPCX-24HWST1 1TB                | 1         | 0.48%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 0.48%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB    | 1         | 0.48%   |
| WDC PC SN730 NVMe 1024GB                | 1         | 0.48%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB    | 1         | 0.48%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB    | 1         | 0.48%   |
| Unknown SD128  128GB                    | 1         | 0.48%   |
| Unknown SD/MMC/MS PRO 64GB              | 1         | 0.48%   |
| Unknown MMC Card  536GB                 | 1         | 0.48%   |
| Unknown MMC Card  32GB                  | 1         | 0.48%   |
| Unknown MMC Card  128GB                 | 1         | 0.48%   |
| Unknown BC4MW  64GB                     | 1         | 0.48%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB | 1         | 0.48%   |
| Toshiba TR200 240GB SSD                 | 1         | 0.48%   |
| Toshiba THNSNK128GVN8 128GB SSD         | 1         | 0.48%   |
| Toshiba THNSNC128GMMJ 128GB SSD         | 1         | 0.48%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.48%   |
| Toshiba MQ01ABD050 500GB                | 1         | 0.48%   |
| Toshiba MK1652GSX 160GB                 | 1         | 0.48%   |
| Toshiba KXG6AZNV512G 512GB              | 1         | 0.48%   |
| Toshiba KBG30ZMV512G KIOXIA 512GB       | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 35     | 41.27%  |
| WDC                 | 12        | 18     | 19.05%  |
| Hitachi             | 9         | 16     | 14.29%  |
| Toshiba             | 8         | 10     | 12.7%   |
| HGST                | 3         | 4      | 4.76%   |
| Samsung Electronics | 2         | 3      | 3.17%   |
| Unknown             | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |
| ASMT                | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 17        | 21     | 20.73%  |
| Samsung Electronics | 16        | 25     | 19.51%  |
| A-DATA Technology   | 7         | 7      | 8.54%   |
| SanDisk             | 6         | 7      | 7.32%   |
| Patriot             | 5         | 6      | 6.1%    |
| Toshiba             | 4         | 6      | 4.88%   |
| Crucial             | 4         | 4      | 4.88%   |
| SK hynix            | 3         | 3      | 3.66%   |
| Intel               | 3         | 3      | 3.66%   |
| China               | 3         | 5      | 3.66%   |
| WDC                 | 2         | 5      | 2.44%   |
| KingSpec            | 2         | 2      | 2.44%   |
| Apacer              | 2         | 2      | 2.44%   |
| Team                | 1         | 1      | 1.22%   |
| OCZ                 | 1         | 1      | 1.22%   |
| LITEONIT            | 1         | 1      | 1.22%   |
| LITEON              | 1         | 2      | 1.22%   |
| GOODRAM             | 1         | 1      | 1.22%   |
| FORESEE             | 1         | 1      | 1.22%   |
| Corsair             | 1         | 1      | 1.22%   |
| ASMT                | 1         | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 74        | 105    | 39.78%  |
| HDD  | 61        | 89     | 32.8%   |
| NVMe | 47        | 58     | 25.27%  |
| MMC  | 4         | 15     | 2.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 113       | 186    | 66.08%  |
| NVMe | 47        | 58     | 27.49%  |
| SAS  | 7         | 8      | 4.09%   |
| MMC  | 4         | 15     | 2.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 98        | 151    | 74.24%  |
| 0.51-1.0   | 33        | 42     | 25%     |
| 4.01-10.0  | 1         | 1      | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 59        | 34.3%   |
| 251-500    | 46        | 26.74%  |
| 501-1000   | 23        | 13.37%  |
| 21-50      | 13        | 7.56%   |
| 51-100     | 11        | 6.4%    |
| 1-20       | 10        | 5.81%   |
| 1001-2000  | 5         | 2.91%   |
| Unknown    | 4         | 2.33%   |
| 2001-3000  | 1         | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 76        | 42.46%  |
| 21-50     | 27        | 15.08%  |
| 101-250   | 27        | 15.08%  |
| 51-100    | 25        | 13.97%  |
| 251-500   | 16        | 8.94%   |
| Unknown   | 4         | 2.23%   |
| 501-1000  | 3         | 1.68%   |
| 1001-2000 | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVX-60JC3T0 752GB             | 1         | 1      | 7.69%   |
| WDC WD6400BPVT-22HXZT1 640GB             | 1         | 1      | 7.69%   |
| Toshiba MK1652GSX 160GB                  | 1         | 1      | 7.69%   |
| SK hynix HFS256G39TND-N210A 256GB SSD    | 1         | 1      | 7.69%   |
| Seagate ST9640320AS 640GB                | 1         | 2      | 7.69%   |
| Samsung Electronics SSD 850 EVO 250GB    | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 840 Series 500GB | 1         | 2      | 7.69%   |
| Samsung Electronics HM641JI 640GB        | 1         | 1      | 7.69%   |
| Hitachi HTS545050KTA300 500GB            | 1         | 1      | 7.69%   |
| Hitachi HTS545032B9A300 320GB            | 1         | 1      | 7.69%   |
| Hitachi HTS545025B9A300 250GB            | 1         | 1      | 7.69%   |
| HGST HTS541010A9E680 1TB                 | 1         | 2      | 7.69%   |
| A-DATA Technology SX900 128GB SSD        | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 23.08%  |
| Hitachi             | 3         | 3      | 23.08%  |
| WDC                 | 2         | 2      | 15.38%  |
| Toshiba             | 1         | 1      | 7.69%   |
| SK hynix            | 1         | 1      | 7.69%   |
| Seagate             | 1         | 2      | 7.69%   |
| HGST                | 1         | 2      | 7.69%   |
| A-DATA Technology   | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 3         | 3      | 33.33%  |
| WDC                 | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Seagate             | 1         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| HGST                | 1         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 11     | 69.23%  |
| SSD  | 4         | 5      | 30.77%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Hitachi HTS541010A9E680 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 97        | 156    | 57.74%  |
| Works    | 57        | 94     | 33.93%  |
| Malfunc  | 13        | 16     | 7.74%   |
| Failed   | 1         | 1      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 122       | 68.54%  |
| Samsung Electronics              | 14        | 7.87%   |
| AMD                              | 12        | 6.74%   |
| SanDisk                          | 9         | 5.06%   |
| Toshiba America Info Systems     | 7         | 3.93%   |
| SK hynix                         | 3         | 1.69%   |
| Micron Technology                | 3         | 1.69%   |
| Union Memory (Shenzhen)          | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Phison Electronics               | 1         | 0.56%   |
| Nvidia                           | 1         | 0.56%   |
| Micron/Crucial Technology        | 1         | 0.56%   |
| Kingston Technology Company      | 1         | 0.56%   |
| JMicron Technology               | 1         | 0.56%   |
| ADATA Technology                 | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 9.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 7.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 4.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 4.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 3.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 3.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 3.66%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 3.66%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 3.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 3.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 2.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 2.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 2.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 2.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 2.09%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.57%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 1.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.57%   |
| Micron Non-Volatile memory controller                                          | 3         | 1.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.57%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.57%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.57%   |
| Intel SSD 660P Series                                                          | 3         | 1.57%   |
| Intel Non-Volatile memory controller                                           | 3         | 1.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 3         | 1.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 1.57%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.05%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.52%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 0.52%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.52%   |
| SK hynix Gold P31 SSD                                                          | 1         | 0.52%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.52%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.52%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.52%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.52%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.52%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.52%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                   | 1         | 0.52%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 1         | 0.52%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.52%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.52%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 0.52%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 0.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 0.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 0.52%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile     | 1         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 0.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 0.52%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 108       | 60.34%  |
| NVMe | 47        | 26.26%  |
| RAID | 12        | 6.7%    |
| IDE  | 12        | 6.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 137       | 87.82%  |
| AMD    | 19        | 12.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 3.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 2.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 2.55%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 3         | 1.91%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 3         | 1.91%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 3         | 1.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 1.91%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 3         | 1.91%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 1.91%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 3         | 1.91%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.27%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 2         | 1.27%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 2         | 1.27%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 1.27%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 2         | 1.27%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 1.27%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.27%   |
| Intel Core i7 CPU M 640 @ 2.80GHz           | 2         | 1.27%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 2         | 1.27%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.27%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.27%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 1.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.27%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 1.27%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.27%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.27%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 2         | 1.27%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz        | 2         | 1.27%   |
| Intel Celeron CPU B830 @ 1.80GHz            | 2         | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.27%   |
| AMD A8-4500M APU with Radeon HD Graphics    | 2         | 1.27%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.64%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.64%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.64%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.64%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 0.64%   |
| Intel Genuine CPU U2300 @ 1.20GHz           | 1         | 0.64%   |
| Intel Genuine CPU T2080 @ 1.73GHz           | 1         | 0.64%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 0.64%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.64%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.64%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 0.64%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.64%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.64%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.64%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.64%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.64%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.64%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.64%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.64%   |
| Intel Core i7-2920XM CPU @ 2.50GHz          | 1         | 0.64%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.64%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.64%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 0.64%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.64%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 0.64%   |
| Intel Core i5-6260U CPU @ 1.80GHz           | 1         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 41        | 26.28%  |
| Intel Core i5           | 38        | 24.36%  |
| Intel Core i3           | 20        | 12.82%  |
| Intel Celeron           | 9         | 5.77%   |
| Intel Core 2 Duo        | 7         | 4.49%   |
| Other                   | 6         | 3.85%   |
| AMD Ryzen 7             | 4         | 2.56%   |
| AMD Ryzen 5             | 4         | 2.56%   |
| Intel Pentium Dual-Core | 3         | 1.92%   |
| Intel Pentium           | 3         | 1.92%   |
| Intel Core i9           | 3         | 1.92%   |
| Intel Genuine           | 2         | 1.28%   |
| Intel Core 2            | 2         | 1.28%   |
| AMD Ryzen 7 PRO         | 2         | 1.28%   |
| AMD Phenom II           | 2         | 1.28%   |
| AMD A8                  | 2         | 1.28%   |
| Intel Pentium Silver    | 1         | 0.64%   |
| Intel Core m7           | 1         | 0.64%   |
| Intel Atom              | 1         | 0.64%   |
| AMD Sempron             | 1         | 0.64%   |
| AMD E                   | 1         | 0.64%   |
| AMD C-60                | 1         | 0.64%   |
| AMD A6                  | 1         | 0.64%   |
| AMD A10                 | 1         | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 78        | 49.37%  |
| 4       | 56        | 35.44%  |
| 6       | 10        | 6.33%   |
| 8       | 9         | 5.7%    |
| 1       | 3         | 1.9%    |
| Unknown | 2         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 156       | 99.36%  |
| Unknown | 1         | 0.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 116       | 73.89%  |
| 1       | 39        | 24.84%  |
| Unknown | 2         | 1.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 154       | 98.72%  |
| 32-bit         | 1         | 0.64%   |
| Unknown        | 1         | 0.64%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 17.28%  |
| 0x306a9    | 16        | 9.88%   |
| 0x206a7    | 15        | 9.26%   |
| 0x806ea    | 9         | 5.56%   |
| 0x306c3    | 8         | 4.94%   |
| 0x40651    | 6         | 3.7%    |
| 0x1067a    | 6         | 3.7%    |
| 0x806ec    | 5         | 3.09%   |
| 0x406e3    | 5         | 3.09%   |
| 0x20655    | 5         | 3.09%   |
| 0x906ea    | 4         | 2.47%   |
| 0x806c1    | 4         | 2.47%   |
| 0x806eb    | 3         | 1.85%   |
| 0x506e3    | 3         | 1.85%   |
| 0x306d4    | 3         | 1.85%   |
| 0xa0652    | 2         | 1.23%   |
| 0x906ed    | 2         | 1.23%   |
| 0x906e9    | 2         | 1.23%   |
| 0x706a1    | 2         | 1.23%   |
| 0x6fd      | 2         | 1.23%   |
| 0x30678    | 2         | 1.23%   |
| 0x20652    | 2         | 1.23%   |
| 0x10676    | 2         | 1.23%   |
| 0x08608103 | 2         | 1.23%   |
| 0x08108102 | 2         | 1.23%   |
| 0x05000119 | 2         | 1.23%   |
| 0x010000c8 | 2         | 1.23%   |
| 0x806e9    | 1         | 0.62%   |
| 0x706e5    | 1         | 0.62%   |
| 0x6fa      | 1         | 0.62%   |
| 0x6f6      | 1         | 0.62%   |
| 0x6f2      | 1         | 0.62%   |
| 0x6ec      | 1         | 0.62%   |
| 0x506c9    | 1         | 0.62%   |
| 0x106e5    | 1         | 0.62%   |
| 0x106ca    | 1         | 0.62%   |
| 0x10661    | 1         | 0.62%   |
| 0x0a404101 | 1         | 0.62%   |
| 0x08600106 | 1         | 0.62%   |
| 0x08600104 | 1         | 0.62%   |
| 0x0700010f | 1         | 0.62%   |
| 0x0600611a | 1         | 0.62%   |
| 0x0600111f | 1         | 0.62%   |
| 0x06001119 | 1         | 0.62%   |
| 0x02000032 | 1         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 31        | 19.87%  |
| SandyBridge     | 17        | 10.9%   |
| IvyBridge       | 16        | 10.26%  |
| Haswell         | 16        | 10.26%  |
| Skylake         | 9         | 5.77%   |
| Westmere        | 8         | 5.13%   |
| Penryn          | 8         | 5.13%   |
| Core            | 6         | 3.85%   |
| TigerLake       | 5         | 3.21%   |
| CometLake       | 5         | 3.21%   |
| Unknown         | 5         | 3.21%   |
| Zen 2           | 4         | 2.56%   |
| Goldmont plus   | 4         | 2.56%   |
| Broadwell       | 3         | 1.92%   |
| Zen+            | 2         | 1.28%   |
| Silvermont      | 2         | 1.28%   |
| Piledriver      | 2         | 1.28%   |
| K10             | 2         | 1.28%   |
| Goldmont        | 2         | 1.28%   |
| Bobcat          | 2         | 1.28%   |
| Zen 3           | 1         | 0.64%   |
| Nehalem         | 1         | 0.64%   |
| K8 & K10 hybrid | 1         | 0.64%   |
| Jaguar          | 1         | 0.64%   |
| IceLake         | 1         | 0.64%   |
| Excavator       | 1         | 0.64%   |
| Bonnell         | 1         | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 122       | 59.8%   |
| Nvidia                           | 44        | 21.57%  |
| AMD                              | 37        | 18.14%  |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 14        | 6.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 14        | 6.54%   |
| Intel UHD Graphics 620                                                        | 10        | 4.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 9         | 4.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 9         | 4.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 7         | 3.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 3.27%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 5         | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                           | 5         | 2.34%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 5         | 2.34%   |
| Nvidia GP108M [GeForce MX150]                                                 | 4         | 1.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 1.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 3         | 1.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 1.4%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 1.4%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 3         | 1.4%    |
| Intel HD Graphics 5500                                                        | 3         | 1.4%    |
| Intel HD Graphics 530                                                         | 3         | 1.4%    |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.4%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 3         | 1.4%    |
| AMD Renoir                                                                    | 3         | 1.4%    |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                              | 3         | 1.4%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.93%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 0.93%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 0.93%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 2         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 0.93%   |
| Intel HD Graphics 630                                                         | 2         | 0.93%   |
| Intel HD Graphics 500                                                         | 2         | 0.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 0.93%   |
| AMD Trinity [Radeon HD 7640G]                                                 | 2         | 0.93%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                           | 2         | 0.93%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 2         | 0.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 0.93%   |
| AMD Lucienne                                                                  | 2         | 0.93%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 2         | 0.93%   |
| AMD Chelsea LP [Radeon HD 7730M]                                              | 2         | 0.93%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 0.47%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.47%   |
| Nvidia TU117M                                                                 | 1         | 0.47%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 1         | 0.47%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                              | 1         | 0.47%   |
| Nvidia GT216M [GeForce GT 330M]                                               | 1         | 0.47%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.47%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.47%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 0.47%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 1         | 0.47%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.47%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.47%   |
| Nvidia GK107GLM [Quadro K2000M]                                               | 1         | 0.47%   |
| Nvidia GK107GLM [Quadro K1000M]                                               | 1         | 0.47%   |
| Nvidia GK106M [GeForce GTX 770M]                                              | 1         | 0.47%   |
| Nvidia GK106M [GeForce GTX 760M]                                              | 1         | 0.47%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.47%   |
| Nvidia GF106GLM [Quadro 2000M]                                                | 1         | 0.47%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 74        | 47.13%  |
| Intel + Nvidia | 39        | 24.84%  |
| 1 x AMD        | 23        | 14.65%  |
| Intel + AMD    | 9         | 5.73%   |
| 1 x Nvidia     | 6         | 3.82%   |
| 2 x AMD        | 5         | 3.18%   |
| 1 x SiS        | 1         | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 136       | 85%     |
| Proprietary | 21        | 13.13%  |
| Unknown     | 3         | 1.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 51.23%  |
| 1.01-2.0   | 34        | 20.99%  |
| 0.01-0.5   | 20        | 12.35%  |
| 0.51-1.0   | 10        | 6.17%   |
| 3.01-4.0   | 9         | 5.56%   |
| 5.01-6.0   | 4         | 2.47%   |
| 7.01-8.0   | 1         | 0.62%   |
| 2.01-3.0   | 1         | 0.62%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 39        | 21.08%  |
| AU Optronics            | 33        | 17.84%  |
| BOE                     | 18        | 9.73%   |
| Samsung Electronics     | 17        | 9.19%   |
| Chimei Innolux          | 17        | 9.19%   |
| Lenovo                  | 11        | 5.95%   |
| Dell                    | 11        | 5.95%   |
| Chi Mei Optoelectronics | 9         | 4.86%   |
| Goldstar                | 4         | 2.16%   |
| Sony                    | 3         | 1.62%   |
| Philips                 | 3         | 1.62%   |
| PANDA                   | 3         | 1.62%   |
| Sharp                   | 2         | 1.08%   |
| Unknown (AAA)           | 1         | 0.54%   |
| Toshiba                 | 1         | 0.54%   |
| MStar                   | 1         | 0.54%   |
| LGD                     | 1         | 0.54%   |
| LG Philips              | 1         | 0.54%   |
| KDC                     | 1         | 0.54%   |
| JDI                     | 1         | 0.54%   |
| InfoVision              | 1         | 0.54%   |
| Iiyama                  | 1         | 0.54%   |
| IBM                     | 1         | 0.54%   |
| Hewlett-Packard         | 1         | 0.54%   |
| HannStar                | 1         | 0.54%   |
| CSO                     | 1         | 0.54%   |
| ASUSTek Computer        | 1         | 0.54%   |
| AOC                     | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 2.16%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 2.16%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                     | 3         | 1.62%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 1.62%   |
| Sony LCD Monitor MS_9005 1920x1200 331x207mm 15.4-inch                   | 2         | 1.08%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 1.08%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 1.08%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 2         | 1.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 1.08%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 2         | 1.08%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                        | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 2         | 1.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 1.08%   |
| Unknown (AAA) smart tv AAA0001 1920x1080 1600x900mm 72.3-inch            | 1         | 0.54%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch                 | 1         | 0.54%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 0.54%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                  | 1         | 0.54%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.54%   |
| Samsung Electronics S24D391 SAM0B87 1920x1080 521x293mm 23.5-inch        | 1         | 0.54%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 531x299mm 24.0-inch        | 1         | 0.54%   |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch        | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 340x190mm 15.3-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4258 1024x768 286x214mm 14.1-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3641 1280x800 331x207mm 15.4-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4144 2160x1440 254x169mm 12.0-inch    | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch    | 1         | 0.54%   |
| Philips PHL 328B6Q PHL0920 2560x1440 700x390mm 31.5-inch                 | 1         | 0.54%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 1         | 0.54%   |
| Philips PHL 272P7V PHL0902 3840x2160 597x336mm 27.0-inch                 | 1         | 0.54%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 0.54%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 0.54%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 0.54%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 1         | 0.54%   |
| LGD LCD Monitor 1920x1080                                                | 1         | 0.54%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 1         | 0.54%   |
| LG Display LP156WH1-TLA1 LGD6301 1366x768 344x194mm 15.5-inch            | 1         | 0.54%   |
| LG Display LCD Monitor LGD069B 1920x1080 344x194mm 15.5-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD05AB 1920x1080 309x174mm 14.0-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD058B 2560x1440 309x174mm 14.0-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD04F2 1366x768 309x174mm 14.0-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD04A0 2560x1440 310x174mm 14.0-inch             | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 77        | 45.83%  |
| 1366x768 (WXGA)    | 45        | 26.79%  |
| 1600x900 (HD+)     | 13        | 7.74%   |
| 3840x2160 (4K)     | 8         | 4.76%   |
| 2560x1440 (QHD)    | 5         | 2.98%   |
| 1280x800 (WXGA)    | 5         | 2.98%   |
| 1920x1200 (WUXGA)  | 4         | 2.38%   |
| 3440x1440          | 2         | 1.19%   |
| 3840x2400          | 1         | 0.6%    |
| 3000x2000          | 1         | 0.6%    |
| 2560x1600          | 1         | 0.6%    |
| 2560x1080          | 1         | 0.6%    |
| 2160x1440          | 1         | 0.6%    |
| 1680x1050 (WSXGA+) | 1         | 0.6%    |
| 1440x900 (WXGA+)   | 1         | 0.6%    |
| 1024x768 (XGA)     | 1         | 0.6%    |
| 1024x600           | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 91        | 49.73%  |
| 14      | 19        | 10.38%  |
| 13      | 19        | 10.38%  |
| 17      | 12        | 6.56%   |
| 24      | 9         | 4.92%   |
| 27      | 8         | 4.37%   |
| 23      | 6         | 3.28%   |
| 12      | 4         | 2.19%   |
| 21      | 3         | 1.64%   |
| 34      | 2         | 1.09%   |
| 11      | 2         | 1.09%   |
| 72      | 1         | 0.55%   |
| 52      | 1         | 0.55%   |
| 40      | 1         | 0.55%   |
| 31      | 1         | 0.55%   |
| 29      | 1         | 0.55%   |
| 25      | 1         | 0.55%   |
| 10      | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 118       | 64.84%  |
| 501-600     | 22        | 12.09%  |
| 351-400     | 15        | 8.24%   |
| 201-300     | 15        | 8.24%   |
| 601-700     | 3         | 1.65%   |
| 401-500     | 3         | 1.65%   |
| 701-800     | 2         | 1.1%    |
| 801-900     | 1         | 0.55%   |
| 1501-2000   | 1         | 0.55%   |
| 1001-1500   | 1         | 0.55%   |
| Unknown     | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 134       | 87.01%  |
| 16/10   | 14        | 9.09%   |
| 3/2     | 2         | 1.3%    |
| 21/9    | 2         | 1.3%    |
| 4/3     | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 90        | 49.18%  |
| 81-90          | 32        | 17.49%  |
| 201-250        | 17        | 9.29%   |
| 121-130        | 11        | 6.01%   |
| 301-350        | 8         | 4.37%   |
| 71-80          | 5         | 2.73%   |
| 61-70          | 4         | 2.19%   |
| 351-500        | 4         | 2.19%   |
| More than 1000 | 2         | 1.09%   |
| 51-60          | 2         | 1.09%   |
| 251-300        | 2         | 1.09%   |
| 91-100         | 2         | 1.09%   |
| 41-50          | 1         | 0.55%   |
| 131-140        | 1         | 0.55%   |
| 501-1000       | 1         | 0.55%   |
| Unknown        | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 78        | 43.33%  |
| 101-120       | 49        | 27.22%  |
| 51-100        | 36        | 20%     |
| 161-240       | 10        | 5.56%   |
| More than 240 | 4         | 2.22%   |
| 1-50          | 2         | 1.11%   |
| Unknown       | 1         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 123       | 77.85%  |
| 2     | 29        | 18.35%  |
| 0     | 4         | 2.53%   |
| 3     | 2         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 85        | 34%     |
| Realtek Semiconductor             | 69        | 27.6%   |
| Qualcomm Atheros                  | 46        | 18.4%   |
| Broadcom                          | 21        | 8.4%    |
| Lenovo                            | 4         | 1.6%    |
| Ralink                            | 3         | 1.2%    |
| Marvell Technology Group          | 3         | 1.2%    |
| Broadcom Limited                  | 3         | 1.2%    |
| JMicron Technology                | 2         | 0.8%    |
| Fibocom                           | 2         | 0.8%    |
| Dell                              | 2         | 0.8%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.4%    |
| TP-Link                           | 1         | 0.4%    |
| Sierra Wireless                   | 1         | 0.4%    |
| Ralink Technology                 | 1         | 0.4%    |
| Qualcomm Atheros Communications   | 1         | 0.4%    |
| Nvidia                            | 1         | 0.4%    |
| MediaTek                          | 1         | 0.4%    |
| Ericsson Business Mobile Networks | 1         | 0.4%    |
| D-Link                            | 1         | 0.4%    |
| ASIX Electronics                  | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 43        | 14.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 4.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 4.23%   |
| Intel Wireless 8265 / 8275                                              | 10        | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 10        | 3.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 2.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.28%   |
| Intel Wireless 8260                                                     | 6         | 1.95%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 1.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 1.63%   |
| Intel Wireless 7260                                                     | 5         | 1.63%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.63%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.3%    |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.98%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 3         | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.98%   |
| Intel Wireless 7265                                                     | 3         | 0.98%   |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 0.98%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 0.65%   |
| Lenovo USB-C Dock Ethernet                                              | 2         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 0.65%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.65%   |
| Intel Wireless 3165                                                     | 2         | 0.65%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.65%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.65%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.65%   |
| Intel Ethernet Connection I217-V                                        | 2         | 0.65%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.65%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.65%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.65%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 2         | 0.65%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 2         | 0.65%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 2         | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 2         | 0.65%   |
| Broadcom BCM4401-B0 100Base-TX                                          | 2         | 0.65%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.65%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 0.65%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.65%   |
| ZTE WCDMA MSM ZTE MSM                                                   | 1         | 0.33%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.33%   |
| Sierra Wireless EM7455                                                  | 1         | 0.33%   |
| Realtek USB 10/100 LAN                                                  | 1         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 84        | 50.91%  |
| Qualcomm Atheros                | 40        | 24.24%  |
| Broadcom                        | 16        | 9.7%    |
| Realtek Semiconductor           | 11        | 6.67%   |
| Ralink                          | 3         | 1.82%   |
| Fibocom                         | 2         | 1.21%   |
| Dell                            | 2         | 1.21%   |
| TP-Link                         | 1         | 0.61%   |
| Sierra Wireless                 | 1         | 0.61%   |
| Ralink Technology               | 1         | 0.61%   |
| Qualcomm Atheros Communications | 1         | 0.61%   |
| MediaTek                        | 1         | 0.61%   |
| D-Link                          | 1         | 0.61%   |
| Broadcom Limited                | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 7.88%   |
| Intel Wireless 8265 / 8275                                              | 10        | 6.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 5.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 4.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 4.24%   |
| Intel Wireless 8260                                                     | 6         | 3.64%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 3.64%   |
| Intel Wireless 7260                                                     | 5         | 3.03%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.82%   |
| Intel Wireless 7265                                                     | 3         | 1.82%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.82%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.21%   |
| Intel Wireless 3165                                                     | 2         | 1.21%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.21%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.21%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.21%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.21%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.21%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.21%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 2         | 1.21%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 2         | 1.21%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.21%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.21%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.21%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.21%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.61%   |
| Sierra Wireless EM7455                                                  | 1         | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.61%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.61%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.61%   |
| MediaTek WLAN controller                                                | 1         | 0.61%   |
| Intel Wireless 3160                                                     | 1         | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.61%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.61%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.61%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.61%   |
| D-Link 802.11 n WLAN                                                    | 1         | 0.61%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 1         | 0.61%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 65        | 46.76%  |
| Intel                      | 33        | 23.74%  |
| Qualcomm Atheros           | 17        | 12.23%  |
| Broadcom                   | 10        | 7.19%   |
| Lenovo                     | 4         | 2.88%   |
| Marvell Technology Group   | 3         | 2.16%   |
| JMicron Technology         | 2         | 1.44%   |
| Broadcom Limited           | 2         | 1.44%   |
| ZTE WCDMA Technologies MSM | 1         | 0.72%   |
| Nvidia                     | 1         | 0.72%   |
| ASIX Electronics           | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 43        | 30.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 15        | 10.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 7.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 3.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 3.55%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 2.84%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 2.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 2.13%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 2.13%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 1.42%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 1.42%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.42%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.42%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.42%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.42%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.42%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 2         | 1.42%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 1.42%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 1.42%   |
| ZTE WCDMA MSM ZTE MSM                                                          | 1         | 0.71%   |
| Realtek USB 10/100 LAN                                                         | 1         | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.71%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.71%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.71%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.71%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.71%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.71%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]                    | 1         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.71%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.71%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.71%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.71%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.71%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.71%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.71%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 0.71%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 0.71%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.71%   |
| ASIX AX88772                                                                   | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 155       | 53.45%  |
| Ethernet | 134       | 46.21%  |
| Modem    | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 130       | 74.29%  |
| Ethernet | 45        | 25.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 125       | 80.13%  |
| 1     | 28        | 17.95%  |
| 0     | 2         | 1.28%   |
| 3     | 1         | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 46.77%  |
| Qualcomm Atheros Communications | 19        | 15.32%  |
| Broadcom                        | 11        | 8.87%   |
| IMC Networks                    | 10        | 8.06%   |
| Realtek Semiconductor           | 5         | 4.03%   |
| Cambridge Silicon Radio         | 4         | 3.23%   |
| Ralink                          | 3         | 2.42%   |
| Foxconn / Hon Hai               | 3         | 2.42%   |
| Dell                            | 3         | 2.42%   |
| ASUSTek Computer                | 3         | 2.42%   |
| Toshiba                         | 2         | 1.61%   |
| Hewlett-Packard                 | 2         | 1.61%   |
| Lite-On Technology              | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 25        | 20.16%  |
| Intel AX201 Bluetooth                                                               | 14        | 11.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 7.26%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 7         | 5.65%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 4.84%   |
| Intel AX200 Bluetooth                                                               | 5         | 4.03%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 3.23%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.42%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.42%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 2.42%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 2.42%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.61%   |
| Intel Bluetooth Device                                                              | 2         | 1.61%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.61%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 1.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.61%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.61%   |
| Broadcom BCM2046 Bluetooth Device                                                   | 2         | 1.61%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.61%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.81%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.81%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.81%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.81%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.81%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.81%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.81%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]                              | 1         | 0.81%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.81%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.81%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.81%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.81%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.81%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.81%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 0.81%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.81%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 135       | 69.23%  |
| AMD                              | 28        | 14.36%  |
| Nvidia                           | 22        | 11.28%  |
| Lenovo                           | 4         | 2.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.51%   |
| Sennheiser Communications        | 1         | 0.51%   |
| Realtek Semiconductor            | 1         | 0.51%   |
| Microsoft                        | 1         | 0.51%   |
| GN Netcom                        | 1         | 0.51%   |
| Creative Technology              | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 18        | 7.79%   |
| Intel Sunrise Point-LP HD Audio                                                   | 17        | 7.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15        | 6.49%   |
| AMD Family 17h/19h HD Audio Controller                                            | 10        | 4.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9         | 3.9%    |
| Intel Cannon Lake PCH cAVS                                                        | 9         | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9         | 3.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 9         | 3.9%    |
| Intel Haswell-ULT HD Audio Controller                                             | 7         | 3.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 7         | 3.03%   |
| Intel 8 Series HD Audio Controller                                                | 7         | 3.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6         | 2.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 6         | 2.6%    |
| Nvidia GF108 High Definition Audio Controller                                     | 5         | 2.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 5         | 2.16%   |
| Intel Comet Lake PCH cAVS                                                         | 5         | 2.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5         | 2.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4         | 1.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 4         | 1.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4         | 1.73%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 1.3%    |
| Nvidia GK107 HDMI Audio Controller                                                | 3         | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 1.3%    |
| Intel Broadwell-U Audio Controller                                                | 3         | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3         | 1.3%    |
| AMD FCH Azalia Controller                                                         | 3         | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2         | 0.87%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 2         | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 0.87%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2         | 0.87%   |
| AMD Trinity HDMI Audio Controller                                                 | 2         | 0.87%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 2         | 0.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                          | 2         | 0.87%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2         | 0.87%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.87%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                          | 1         | 0.43%   |
| Sennheiser Communications Sennheiser USB headset                                  | 1         | 0.43%   |
| Realtek Semiconductor USB Audio                                                   | 1         | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1         | 0.43%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1         | 0.43%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 0.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 0.43%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.43%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1         | 0.43%   |
| Microsoft LifeChat LX-3000 Headset                                                | 1         | 0.43%   |
| Lenovo ThinkPad OneLink Pro Dock Audio                                            | 1         | 0.43%   |
| Lenovo ThinkPad Dock Audio                                                        | 1         | 0.43%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 0.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1         | 0.43%   |
| GN Netcom Jabra EVOLVE 20 MS                                                      | 1         | 0.43%   |
| Creative Technology Sound Blaster Play! 2                                         | 1         | 0.43%   |
| AMD Wrestler HDMI Audio                                                           | 1         | 0.43%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1         | 0.43%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                   | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 32.71%  |
| SK hynix            | 20        | 18.69%  |
| Kingston            | 15        | 14.02%  |
| Micron Technology   | 10        | 9.35%   |
| Ramaxel Technology  | 5         | 4.67%   |
| Crucial             | 5         | 4.67%   |
| Unknown             | 3         | 2.8%    |
| Nanya Technology    | 3         | 2.8%    |
| Elpida              | 3         | 2.8%    |
| Patriot             | 2         | 1.87%   |
| Unknown (ABCD)      | 1         | 0.93%   |
| Lexar               | 1         | 0.93%   |
| G.Skill             | 1         | 0.93%   |
| Corsair             | 1         | 0.93%   |
| A-DATA Technology   | 1         | 0.93%   |
| Unknown             | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                  | 3         | 2.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                   | 2         | 1.8%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                   | 2         | 1.8%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                   | 2         | 1.8%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                    | 2         | 1.8%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                    | 2         | 1.8%    |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                    | 2         | 1.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                    | 2         | 1.8%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 1.8%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.8%    |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s                    | 2         | 1.8%    |
| Elpida RAM EBJ41UF8BDU0-GN-F 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.8%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                           | 1         | 0.9%    |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                            | 1         | 0.9%    |
| Unknown RAM Module 1024MB SODIMM DDR2                                    | 1         | 0.9%    |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s         | 1         | 0.9%    |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                        | 1         | 0.9%    |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                         | 1         | 0.9%    |
| SK hynix RAM HYMP512S64BP8-Y5 1GB SODIMM DDR 667MT/s                     | 1         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.9%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                   | 1         | 0.9%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                   | 1         | 0.9%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s                  | 1         | 0.9%    |
| SK hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s               | 1         | 0.9%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s                | 1         | 0.9%    |
| Samsung RAM Module 2048MB Row Of Chips LPDDR4 4267MT/s                   | 1         | 0.9%    |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                          | 1         | 0.9%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                    | 1         | 0.9%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                    | 1         | 0.9%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.9%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                    | 1         | 0.9%    |
| Samsung RAM M471B5174BM0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.9%    |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.9%    |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                    | 1         | 0.9%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                   | 1         | 0.9%    |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.9%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.9%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.9%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.9%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s                       | 1         | 0.9%    |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM 4800MT/s                       | 1         | 0.9%    |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s                   | 1         | 0.9%    |
| Samsung RAM K4E6E304EB-EGCG 4096MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.9%    |
| Samsung RAM K4AAG165WA-BCWE 8GB Row Of Chips DDR4 3200MT/s               | 1         | 0.9%    |
| Samsung RAM 4D3420373054353636334548332D43463720 2GB SODIMM DDR2 667MT/s | 1         | 0.9%    |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.9%    |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s               | 1         | 0.9%    |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s                | 1         | 0.9%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 0.9%    |
| Ramaxel RAM RMSA3260MD78HAF-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 0.9%    |
| Patriot RAM PSD34G160081S 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.9%    |
| Patriot RAM PSD34G13332S 4GB SODIMM DDR3 1334MT/s                        | 1         | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 42        | 48.28%  |
| DDR4    | 29        | 33.33%  |
| LPDDR3  | 6         | 6.9%    |
| LPDDR4  | 4         | 4.6%    |
| DDR2    | 4         | 4.6%    |
| DRAM    | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 81        | 93.1%   |
| Row Of Chips | 6         | 6.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 37        | 39.78%  |
| 8192  | 28        | 30.11%  |
| 16384 | 15        | 16.13%  |
| 2048  | 9         | 9.68%   |
| 1024  | 3         | 3.23%   |
| 32768 | 1         | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 30        | 31.58%  |
| 2667    | 23        | 24.21%  |
| 3200    | 12        | 12.63%  |
| 1334    | 8         | 8.42%   |
| 1333    | 5         | 5.26%   |
| 2133    | 4         | 4.21%   |
| 1867    | 3         | 3.16%   |
| 667     | 3         | 3.16%   |
| 2400    | 2         | 2.11%   |
| 4800    | 1         | 1.05%   |
| 4267    | 1         | 1.05%   |
| 1067    | 1         | 1.05%   |
| 800     | 1         | 1.05%   |
| Unknown | 1         | 1.05%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 29        | 20.28%  |
| Chicony Electronics                    | 28        | 19.58%  |
| Microdia                               | 13        | 9.09%   |
| Sunplus Innovation Technology          | 12        | 8.39%   |
| Acer                                   | 11        | 7.69%   |
| Realtek Semiconductor                  | 10        | 6.99%   |
| Suyin                                  | 8         | 5.59%   |
| Syntek                                 | 5         | 3.5%    |
| Alcor Micro                            | 5         | 3.5%    |
| Silicon Motion                         | 3         | 2.1%    |
| Quanta                                 | 2         | 1.4%    |
| OmniVision Technologies                | 2         | 1.4%    |
| Luxvisions Innotech Limited            | 2         | 1.4%    |
| Lite-On Technology                     | 2         | 1.4%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.4%    |
| Sonix Technology                       | 1         | 0.7%    |
| Ricoh                                  | 1         | 0.7%    |
| Primax Electronics                     | 1         | 0.7%    |
| Lenovo                                 | 1         | 0.7%    |
| Intel                                  | 1         | 0.7%    |
| Importek                               | 1         | 0.7%    |
| DJJHNA29IE70D3                         | 1         | 0.7%    |
| DigiTech                               | 1         | 0.7%    |
| ALi                                    | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 8         | 5.59%   |
| IMC Networks Integrated Camera                      | 8         | 5.59%   |
| Chicony Integrated Camera                           | 8         | 5.59%   |
| Microdia Integrated_Webcam_HD                       | 6         | 4.2%    |
| Syntek Lenovo EasyCamera                            | 3         | 2.1%    |
| Sunplus Integrated_Webcam_HD                        | 3         | 2.1%    |
| Sunplus HP HD Webcam [Fixed]                        | 3         | 2.1%    |
| Realtek Integrated_Webcam_HD                        | 3         | 2.1%    |
| IMC Networks UVC VGA Webcam                         | 3         | 2.1%    |
| Chicony ThinkPad T490 Webcam                        | 3         | 2.1%    |
| Acer Integrated Camera                              | 3         | 2.1%    |
| Suyin HP Webcam                                     | 2         | 1.4%    |
| Sunplus HD Webcam                                   | 2         | 1.4%    |
| Sunplus ASUS USB2.0 Webcam                          | 2         | 1.4%    |
| Silicon Motion Lenovo EasyCamera                    | 2         | 1.4%    |
| Microdia Integrated Webcam                          | 2         | 1.4%    |
| IMC Networks VGA UVC WebCam                         | 2         | 1.4%    |
| IMC Networks 2M Integrated Webcam                   | 2         | 1.4%    |
| Chicony Webcam                                      | 2         | 1.4%    |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 1.4%    |
| Chicony USB2.0 0.3M UVC WebCam                      | 2         | 1.4%    |
| Chicony HP Laptop Integrated Webcam [2 MP Fixed]    | 2         | 1.4%    |
| Chicony HP HD Webcam                                | 2         | 1.4%    |
| Alcor Micro USB 2.0 PC cam                          | 2         | 1.4%    |
| Alcor Micro Asus Integrated Webcam                  | 2         | 1.4%    |
| Acer SunplusIT Integrated Camera                    | 2         | 1.4%    |
| Syntek Sonix USB 2.0 Camera                         | 1         | 0.7%    |
| Syntek Integrated Camera                            | 1         | 0.7%    |
| Suyin WebCam                                        | 1         | 0.7%    |
| Suyin Laptop_Integrated_Webcam_HD                   | 1         | 0.7%    |
| Suyin Integrated Camera                             | 1         | 0.7%    |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.7%    |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 0.7%    |
| Suyin 1.3M HD WebCam                                | 1         | 0.7%    |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.7%    |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.7%    |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.7%    |
| Silicon Motion WebCam SC-13HDL12131N                | 1         | 0.7%    |
| Ricoh Sony Visual Communication Camera              | 1         | 0.7%    |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.7%    |
| Realtek USB Camera                                  | 1         | 0.7%    |
| Realtek Laptop_Integrated_Webcam_HD                 | 1         | 0.7%    |
| Realtek Integrated Webcam_HD                        | 1         | 0.7%    |
| Realtek Integrated Webcam                           | 1         | 0.7%    |
| Realtek Integrated Camera                           | 1         | 0.7%    |
| Realtek FULL HD 1080P Webcam                        | 1         | 0.7%    |
| Quanta HP HD Camera                                 | 1         | 0.7%    |
| Quanta HD User Facing                               | 1         | 0.7%    |
| Primax HP HD Webcam [Fixed]                         | 1         | 0.7%    |
| OmniVision OV7670 Webcam                            | 1         | 0.7%    |
| OmniVision OV2640 Webcam                            | 1         | 0.7%    |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 0.7%    |
| Microdia Laptop_Integrated_Webcam_FHD               | 1         | 0.7%    |
| Microdia Laptop_Integrated_Webcam_E4HD              | 1         | 0.7%    |
| Microdia Integrated Webcam HD                       | 1         | 0.7%    |
| Microdia Dell Laptop Integrated Webcam HD           | 1         | 0.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.7%    |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 0.7%    |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 0.7%    |
| Lite-On Integrated Camera                           | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 15        | 40.54%  |
| Validity Sensors           | 8         | 21.62%  |
| Elan Microelectronics      | 4         | 10.81%  |
| AuthenTec                  | 4         | 10.81%  |
| Shenzhen Goodix Technology | 3         | 8.11%   |
| STMicroelectronics         | 2         | 5.41%   |
| LighTuning Technology      | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 8         | 21.62%  |
| Validity Sensors VFS471 Fingerprint Reader                 | 3         | 8.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 8.11%   |
| Elan ELAN:Fingerprint                                      | 3         | 8.11%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 5.41%   |
| STMicroelectronics Fingerprint Reader                      | 2         | 5.41%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 5.41%   |
| AuthenTec AES2810                                          | 2         | 5.41%   |
| AuthenTec AES1600                                          | 2         | 5.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2.7%    |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2.7%    |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.7%    |
| Validity Sensors Fingerprint scanner                       | 1         | 2.7%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.7%    |
| Shenzhen Goodix FingerPrint                                | 1         | 2.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 2.7%    |
| Elan ELAN:ARM-M4                                           | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 10        | 58.82%  |
| Broadcom              | 5         | 29.41%  |
| Gemalto (was Gemplus) | 2         | 11.76%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 58.82%  |
| Broadcom 5880                                                                | 2         | 11.76%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 5.88%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.88%   |
| Broadcom 58200                                                               | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 98        | 61.25%  |
| 1     | 44        | 27.5%   |
| 2     | 14        | 8.75%   |
| 3     | 3         | 1.88%   |
| 4     | 1         | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 35        | 41.67%  |
| Chipcard                 | 16        | 19.05%  |
| Graphics card            | 12        | 14.29%  |
| Net/wireless             | 8         | 9.52%   |
| Multimedia controller    | 3         | 3.57%   |
| Camera                   | 2         | 2.38%   |
| Bluetooth                | 2         | 2.38%   |
| Storage                  | 1         | 1.19%   |
| Sound                    | 1         | 1.19%   |
| Net/ethernet             | 1         | 1.19%   |
| Flash memory             | 1         | 1.19%   |
| Communication controller | 1         | 1.19%   |
| Card reader              | 1         | 1.19%   |

