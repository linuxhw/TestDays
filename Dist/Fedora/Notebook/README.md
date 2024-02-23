Fedora - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 13146

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Nitro AN515-54              | [051e477b5f](https://linux-hardware.org/?probe=051e477b5f) | Feb 02, 2024 |
| HP            | EliteBook 8560w             | [6ff665aaf5](https://linux-hardware.org/?probe=6ff665aaf5) | Feb 02, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | [2b3f583bc7](https://linux-hardware.org/?probe=2b3f583bc7) | Feb 02, 2024 |
| Dell          | XPS 15 7590                 | [214b9d35cb](https://linux-hardware.org/?probe=214b9d35cb) | Feb 02, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | [a569cab490](https://linux-hardware.org/?probe=a569cab490) | Feb 02, 2024 |
| HP            | EliteBook 840 G2            | [4a3954a4c1](https://linux-hardware.org/?probe=4a3954a4c1) | Feb 02, 2024 |
| Acer          | Aspire VN7-591G             | [c0f024d3e0](https://linux-hardware.org/?probe=c0f024d3e0) | Feb 02, 2024 |
| Dell          | Latitude 3420               | [15de060676](https://linux-hardware.org/?probe=15de060676) | Feb 02, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [d9a0906eac](https://linux-hardware.org/?probe=d9a0906eac) | Feb 02, 2024 |
| Lenovo        | Z50-70 20354                | [d6023b78a2](https://linux-hardware.org/?probe=d6023b78a2) | Feb 02, 2024 |
| Acer          | Swift SF314-43              | [e87efb031b](https://linux-hardware.org/?probe=e87efb031b) | Feb 02, 2024 |
| HP            | EliteBook Revolve 810 G2    | [788fb13f23](https://linux-hardware.org/?probe=788fb13f23) | Feb 02, 2024 |
| Dell          | Inspiron N5110              | [e7338ad21d](https://linux-hardware.org/?probe=e7338ad21d) | Feb 01, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [f2003839e0](https://linux-hardware.org/?probe=f2003839e0) | Feb 01, 2024 |
| HONOR         | BRN-HXX                     | [9e92d94ecb](https://linux-hardware.org/?probe=9e92d94ecb) | Feb 01, 2024 |
| Dell          | Precision 5520              | [60d35bb7a2](https://linux-hardware.org/?probe=60d35bb7a2) | Feb 01, 2024 |
| realme        | CloudProXXXX                | [1299621a5e](https://linux-hardware.org/?probe=1299621a5e) | Feb 01, 2024 |
| Apple         | MacBookPro11,3              | [9b4ae891b7](https://linux-hardware.org/?probe=9b4ae891b7) | Feb 01, 2024 |
| Dell          | XPS 15 9530                 | [3aa974d8a0](https://linux-hardware.org/?probe=3aa974d8a0) | Feb 01, 2024 |
| Dell          | Inspiron 5748               | [1eaa79e492](https://linux-hardware.org/?probe=1eaa79e492) | Feb 01, 2024 |
| Dell          | Vostro 3500                 | [1d57e2e0b1](https://linux-hardware.org/?probe=1d57e2e0b1) | Feb 01, 2024 |
| Apple         | MacBookPro11,3              | [3a809ef1d0](https://linux-hardware.org/?probe=3a809ef1d0) | Jan 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [0414c66c77](https://linux-hardware.org/?probe=0414c66c77) | Jan 31, 2024 |
| Dell          | Inspiron 5748               | [7a50d780ce](https://linux-hardware.org/?probe=7a50d780ce) | Jan 31, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | [e91ff8608c](https://linux-hardware.org/?probe=e91ff8608c) | Jan 31, 2024 |
| HP            | EliteBook 8560w             | [6d3b73b144](https://linux-hardware.org/?probe=6d3b73b144) | Jan 31, 2024 |
| Acer          | Swift SF514-56T             | [320f3db548](https://linux-hardware.org/?probe=320f3db548) | Jan 31, 2024 |
| Lenovo        | G50-30 80G0                 | [16e8c28b87](https://linux-hardware.org/?probe=16e8c28b87) | Jan 31, 2024 |
| Dell          | Latitude 7280               | [0a79c87afb](https://linux-hardware.org/?probe=0a79c87afb) | Jan 31, 2024 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [4838799f43](https://linux-hardware.org/?probe=4838799f43) | Jan 31, 2024 |
| HP            | Laptop 14-cf2xxx            | [7984b3ffda](https://linux-hardware.org/?probe=7984b3ffda) | Jan 31, 2024 |
| HP            | EliteBook 840 G7 Noteboo... | [e79be04d28](https://linux-hardware.org/?probe=e79be04d28) | Jan 31, 2024 |
| Avell         | B.ON                        | [45a01901e9](https://linux-hardware.org/?probe=45a01901e9) | Jan 31, 2024 |
| Dell          | Inspiron 5537               | [7c7904f383](https://linux-hardware.org/?probe=7c7904f383) | Jan 31, 2024 |
| Dell          | Inspiron 5537               | [7a4e4ac7ba](https://linux-hardware.org/?probe=7a4e4ac7ba) | Jan 31, 2024 |
| HP            | Laptop 15-dy1xxx            | [5a506021d1](https://linux-hardware.org/?probe=5a506021d1) | Jan 31, 2024 |
| HP            | Laptop 15-dy1xxx            | [999c7694d0](https://linux-hardware.org/?probe=999c7694d0) | Jan 31, 2024 |
| Google        | Cyan                        | [15ee2dfc2f](https://linux-hardware.org/?probe=15ee2dfc2f) | Jan 30, 2024 |
| Dell          | Latitude 5590               | [d10e7cf975](https://linux-hardware.org/?probe=d10e7cf975) | Jan 30, 2024 |
| Dell          | XPS 9315                    | [dd96b44e05](https://linux-hardware.org/?probe=dd96b44e05) | Jan 30, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [76cc91cd14](https://linux-hardware.org/?probe=76cc91cd14) | Jan 30, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [5e58868dbf](https://linux-hardware.org/?probe=5e58868dbf) | Jan 30, 2024 |
| Dell          | G15 5510                    | [9f3691e991](https://linux-hardware.org/?probe=9f3691e991) | Jan 30, 2024 |
| HUAWEI        | BOM-WXX9                    | [93b76b804d](https://linux-hardware.org/?probe=93b76b804d) | Jan 30, 2024 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [b0ebb1ac3b](https://linux-hardware.org/?probe=b0ebb1ac3b) | Jan 30, 2024 |
| Samsung       | 940XFG                      | [5dea9b20b4](https://linux-hardware.org/?probe=5dea9b20b4) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK E5512A             | [e4d7a0ca3a](https://linux-hardware.org/?probe=e4d7a0ca3a) | Jan 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bd5392e681](https://linux-hardware.org/?probe=bd5392e681) | Jan 30, 2024 |
| HP            | EliteBook Folio 9480m       | [648e9e296d](https://linux-hardware.org/?probe=648e9e296d) | Jan 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [69f602b6c5](https://linux-hardware.org/?probe=69f602b6c5) | Jan 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [89f648ad66](https://linux-hardware.org/?probe=89f648ad66) | Jan 30, 2024 |
| Apple         | MacBookPro14,2              | [c2b9f915d1](https://linux-hardware.org/?probe=c2b9f915d1) | Jan 29, 2024 |
| Dell          | Latitude 5590               | [9ab8c26d03](https://linux-hardware.org/?probe=9ab8c26d03) | Jan 29, 2024 |
| HP            | ENVY Laptop 17-cr0xxx       | [3aa33cea08](https://linux-hardware.org/?probe=3aa33cea08) | Jan 29, 2024 |
| MSI           | Modern 14 C12M              | [39450e20cc](https://linux-hardware.org/?probe=39450e20cc) | Jan 29, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [dd92e4a676](https://linux-hardware.org/?probe=dd92e4a676) | Jan 29, 2024 |
| Acer          | TravelMate B113             | [7f86bed0b1](https://linux-hardware.org/?probe=7f86bed0b1) | Jan 29, 2024 |
| HP            | Laptop 15-ef2xxx            | [db29833c5b](https://linux-hardware.org/?probe=db29833c5b) | Jan 29, 2024 |
| Lenovo        | V370 HuronRiver Platform    | [9d6e253461](https://linux-hardware.org/?probe=9d6e253461) | Jan 29, 2024 |
| Lenovo        | ThinkPad P52 20M9001MMX     | [0270f75e12](https://linux-hardware.org/?probe=0270f75e12) | Jan 29, 2024 |
| Lenovo        | V370 HuronRiver Platform    | [77ec188a66](https://linux-hardware.org/?probe=77ec188a66) | Jan 29, 2024 |
| Dell          | Precision M4800             | [54bea54d08](https://linux-hardware.org/?probe=54bea54d08) | Jan 29, 2024 |
| HUAWEI        | NbDE-WXX9                   | [39f2e4dc9e](https://linux-hardware.org/?probe=39f2e4dc9e) | Jan 29, 2024 |
| HUAWEI        | NbDE-WXX9                   | [bf90b37fe4](https://linux-hardware.org/?probe=bf90b37fe4) | Jan 29, 2024 |
| Dell          | Vostro 3558                 | [f2c958ad91](https://linux-hardware.org/?probe=f2c958ad91) | Jan 29, 2024 |
| General Dy... | Tadpole TOPAZ               | [2d773d0793](https://linux-hardware.org/?probe=2d773d0793) | Jan 29, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [454031382d](https://linux-hardware.org/?probe=454031382d) | Jan 29, 2024 |
| Acer          | Swift SF314-56G             | [a6aac17123](https://linux-hardware.org/?probe=a6aac17123) | Jan 29, 2024 |
| Acer          | Swift SF314-56G             | [b259912831](https://linux-hardware.org/?probe=b259912831) | Jan 29, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [f46d220d2e](https://linux-hardware.org/?probe=f46d220d2e) | Jan 28, 2024 |
| Dell          | Latitude 5490               | [02270e4c1f](https://linux-hardware.org/?probe=02270e4c1f) | Jan 28, 2024 |
| Acer          | TravelMate P259-MG          | [0192eb7c53](https://linux-hardware.org/?probe=0192eb7c53) | Jan 28, 2024 |
| Dell          | Latitude 5490               | [6e91f2be02](https://linux-hardware.org/?probe=6e91f2be02) | Jan 28, 2024 |
| Dell          | Latitude 5420               | [459fbb3448](https://linux-hardware.org/?probe=459fbb3448) | Jan 28, 2024 |
| Apple         | MacBookPro10,1              | [35238c08e4](https://linux-hardware.org/?probe=35238c08e4) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [e78406b431](https://linux-hardware.org/?probe=e78406b431) | Jan 28, 2024 |
| Lenovo        | ThinkPad T410 2522PT3       | [5116ee6ad3](https://linux-hardware.org/?probe=5116ee6ad3) | Jan 28, 2024 |
| Dell          | Inspiron 5415               | [c7bd6068fa](https://linux-hardware.org/?probe=c7bd6068fa) | Jan 28, 2024 |
| HP            | Laptop 14-dq2xxx            | [54cf5ffabf](https://linux-hardware.org/?probe=54cf5ffabf) | Jan 27, 2024 |
| Acer          | Aspire A315-41G             | [e0d994ac23](https://linux-hardware.org/?probe=e0d994ac23) | Jan 27, 2024 |
| Acer          | Aspire A315-41G             | [1b15d869d4](https://linux-hardware.org/?probe=1b15d869d4) | Jan 27, 2024 |
| MSI           | Modern 15 H B13M            | [53eae9905c](https://linux-hardware.org/?probe=53eae9905c) | Jan 27, 2024 |
| Lenovo        | ThinkPad T490s 20NYS1AM0... | [eb0027485d](https://linux-hardware.org/?probe=eb0027485d) | Jan 27, 2024 |
| Apple         | MacBookPro11,3              | [efdf2169af](https://linux-hardware.org/?probe=efdf2169af) | Jan 27, 2024 |
| Dell          | Latitude 5310               | [334e579e92](https://linux-hardware.org/?probe=334e579e92) | Jan 27, 2024 |
| Timi          | Xiaomi Book Pro 16 2022     | [60e1022aef](https://linux-hardware.org/?probe=60e1022aef) | Jan 27, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [1f1d3ff8f9](https://linux-hardware.org/?probe=1f1d3ff8f9) | Jan 27, 2024 |
| HP            | ProBook 650 G1              | [26cf710a63](https://linux-hardware.org/?probe=26cf710a63) | Jan 27, 2024 |
| Lenovo        | B590 20206                  | [31fa6a22ea](https://linux-hardware.org/?probe=31fa6a22ea) | Jan 27, 2024 |
| Lenovo        | ThinkPad T490s 20NYS1AM0... | [48a5f801fc](https://linux-hardware.org/?probe=48a5f801fc) | Jan 27, 2024 |
| Unknown       | Unknown                     | [5c676b44c6](https://linux-hardware.org/?probe=5c676b44c6) | Jan 27, 2024 |
| Unknown       | Unknown                     | [52522836b8](https://linux-hardware.org/?probe=52522836b8) | Jan 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [32f526010e](https://linux-hardware.org/?probe=32f526010e) | Jan 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2d82723a5a](https://linux-hardware.org/?probe=2d82723a5a) | Jan 27, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | [8c4e929f6f](https://linux-hardware.org/?probe=8c4e929f6f) | Jan 27, 2024 |
| ASUSTek       | N551JX                      | [6a0be842aa](https://linux-hardware.org/?probe=6a0be842aa) | Jan 27, 2024 |
| HUAWEI        | WRT-WX9                     | [4fe4c818d5](https://linux-hardware.org/?probe=4fe4c818d5) | Jan 26, 2024 |
| Apple         | MacBookAir7,2               | [0aeced0805](https://linux-hardware.org/?probe=0aeced0805) | Jan 26, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [275a598957](https://linux-hardware.org/?probe=275a598957) | Jan 26, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8cafa419c5](https://linux-hardware.org/?probe=8cafa419c5) | Jan 26, 2024 |
| mPTech        | Techbite ZIN 3              | [57234bbbc3](https://linux-hardware.org/?probe=57234bbbc3) | Jan 26, 2024 |
| HUAWEI        | MACHC-WAX9                  | [4cfadd11cf](https://linux-hardware.org/?probe=4cfadd11cf) | Jan 26, 2024 |
| HP            | EliteBook 845 14 inch G1... | [c890800eff](https://linux-hardware.org/?probe=c890800eff) | Jan 26, 2024 |
| Notebook      | NS5x_NS7xAU                 | [25b199fd9d](https://linux-hardware.org/?probe=25b199fd9d) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3932a6e2cf](https://linux-hardware.org/?probe=3932a6e2cf) | Jan 26, 2024 |
| LG Electro... | 16Z90Q-G.AA54C2             | [34806d0240](https://linux-hardware.org/?probe=34806d0240) | Jan 26, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDA... | [6456dc0020](https://linux-hardware.org/?probe=6456dc0020) | Jan 26, 2024 |
| Lenovo        | ThinkPad E420 114155F       | [cdee2fb160](https://linux-hardware.org/?probe=cdee2fb160) | Jan 26, 2024 |
| Framework     | Laptop                      | [002ca05701](https://linux-hardware.org/?probe=002ca05701) | Jan 26, 2024 |
| Dell          | Inspiron 5521               | [e9f2d87f0f](https://linux-hardware.org/?probe=e9f2d87f0f) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [660c45b7e5](https://linux-hardware.org/?probe=660c45b7e5) | Jan 26, 2024 |
| Dell          | Inspiron 5521               | [1c9b6b485d](https://linux-hardware.org/?probe=1c9b6b485d) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [182e75dbe2](https://linux-hardware.org/?probe=182e75dbe2) | Jan 26, 2024 |
| MACHENIKE     | S15C                        | [7429416572](https://linux-hardware.org/?probe=7429416572) | Jan 25, 2024 |
| Lenovo        | V15-ADA 82C7                | [a72a3bb0e5](https://linux-hardware.org/?probe=a72a3bb0e5) | Jan 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [e7a39e7734](https://linux-hardware.org/?probe=e7a39e7734) | Jan 25, 2024 |
| Apple         | MacBookAir6,2               | [07460c8e19](https://linux-hardware.org/?probe=07460c8e19) | Jan 25, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [3ed9ff642f](https://linux-hardware.org/?probe=3ed9ff642f) | Jan 25, 2024 |
| Lenovo        | ThinkPad X201 36805B8       | [cf0a1641da](https://linux-hardware.org/?probe=cf0a1641da) | Jan 25, 2024 |
| HP            | EliteBook 865 16 inch G1... | [72f849d40c](https://linux-hardware.org/?probe=72f849d40c) | Jan 25, 2024 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [49a536ed05](https://linux-hardware.org/?probe=49a536ed05) | Jan 25, 2024 |
| Fujitsu       | LIFEBOOK A555               | [4d1f942627](https://linux-hardware.org/?probe=4d1f942627) | Jan 25, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | [0e4d078f49](https://linux-hardware.org/?probe=0e4d078f49) | Jan 25, 2024 |
| Lenovo        | Unknown                     | [ae59a4d618](https://linux-hardware.org/?probe=ae59a4d618) | Jan 25, 2024 |
| Dell          | Precision M4800             | [a945621369](https://linux-hardware.org/?probe=a945621369) | Jan 25, 2024 |
| HP            | Pavilion dv6                | [073fe44f35](https://linux-hardware.org/?probe=073fe44f35) | Jan 24, 2024 |
| Dell          | Precision 5510              | [e1e543eaa4](https://linux-hardware.org/?probe=e1e543eaa4) | Jan 24, 2024 |
| Apple         | MacBookPro14,1              | [77704a62ca](https://linux-hardware.org/?probe=77704a62ca) | Jan 24, 2024 |
| Lenovo        | ThinkPad X270 20HN0012MX    | [ac867529fa](https://linux-hardware.org/?probe=ac867529fa) | Jan 24, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [4b9301ae7f](https://linux-hardware.org/?probe=4b9301ae7f) | Jan 24, 2024 |
| ASUSTek       | X507UA                      | [ebf2dc120a](https://linux-hardware.org/?probe=ebf2dc120a) | Jan 24, 2024 |
| Apple         | MacBookPro14,1              | [01d5416f71](https://linux-hardware.org/?probe=01d5416f71) | Jan 24, 2024 |
| LG Electro... | 14Z990-V.AR52A2             | [346844d302](https://linux-hardware.org/?probe=346844d302) | Jan 24, 2024 |
| HP            | Notebook                    | [e862ba4d2b](https://linux-hardware.org/?probe=e862ba4d2b) | Jan 24, 2024 |
| Lenovo        | U41-70 80JV                 | [48ea1ff4a5](https://linux-hardware.org/?probe=48ea1ff4a5) | Jan 24, 2024 |
| Dell          | Inspiron N5040              | [79bca2224b](https://linux-hardware.org/?probe=79bca2224b) | Jan 24, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [789bbeb50a](https://linux-hardware.org/?probe=789bbeb50a) | Jan 24, 2024 |
| Acer          | Aspire A315-24P             | [ab51a416c0](https://linux-hardware.org/?probe=ab51a416c0) | Jan 23, 2024 |
| Dell          | Inspiron 13-7378            | [f1abc906bc](https://linux-hardware.org/?probe=f1abc906bc) | Jan 23, 2024 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | [27804a7892](https://linux-hardware.org/?probe=27804a7892) | Jan 23, 2024 |
| Dell          | XPS 15 9500                 | [909b4a8f7c](https://linux-hardware.org/?probe=909b4a8f7c) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [48f8a71c93](https://linux-hardware.org/?probe=48f8a71c93) | Jan 23, 2024 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [a80c29ee33](https://linux-hardware.org/?probe=a80c29ee33) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [59eb577232](https://linux-hardware.org/?probe=59eb577232) | Jan 23, 2024 |
| Dell          | System Inspiron N7110       | [e764df92ee](https://linux-hardware.org/?probe=e764df92ee) | Jan 23, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [d0cd433ae4](https://linux-hardware.org/?probe=d0cd433ae4) | Jan 23, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [23edfb46f4](https://linux-hardware.org/?probe=23edfb46f4) | Jan 23, 2024 |
| Lenovo        | ThinkPad L480 20LTS8CY00    | [a18fc04450](https://linux-hardware.org/?probe=a18fc04450) | Jan 23, 2024 |
| Dell          | Precision 5530              | [585fb7de16](https://linux-hardware.org/?probe=585fb7de16) | Jan 22, 2024 |
| Unknown       | Unknown                     | [dd7b17439f](https://linux-hardware.org/?probe=dd7b17439f) | Jan 22, 2024 |
| Acer          | Predator PH315-53           | [74ca3f63e2](https://linux-hardware.org/?probe=74ca3f63e2) | Jan 22, 2024 |
| HP            | Laptop 14-cf2xxx            | [72068173b9](https://linux-hardware.org/?probe=72068173b9) | Jan 22, 2024 |
| Toshiba       | Satellite C850-C5K          | [11b9b2c55a](https://linux-hardware.org/?probe=11b9b2c55a) | Jan 22, 2024 |
| Dell          | Latitude E7440              | [4e05575433](https://linux-hardware.org/?probe=4e05575433) | Jan 22, 2024 |
| Dell          | Inspiron 5770               | [8d01c56fca](https://linux-hardware.org/?probe=8d01c56fca) | Jan 22, 2024 |
| HP            | 240 G7 Notebook PC          | [5225ed2250](https://linux-hardware.org/?probe=5225ed2250) | Jan 22, 2024 |
| Apple         | MacBook5,1                  | [0833d2c5c5](https://linux-hardware.org/?probe=0833d2c5c5) | Jan 22, 2024 |
| Lenovo        | ThinkPad T480 20L6S1AL00    | [f5c1f6e080](https://linux-hardware.org/?probe=f5c1f6e080) | Jan 22, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [2ab9e19a09](https://linux-hardware.org/?probe=2ab9e19a09) | Jan 22, 2024 |
| Apple         | MacBookPro14,1              | [2be86e592f](https://linux-hardware.org/?probe=2be86e592f) | Jan 22, 2024 |
| Apple         | MacBookPro16,1              | [62447a80b3](https://linux-hardware.org/?probe=62447a80b3) | Jan 22, 2024 |
| Apple         | MacBookPro16,1              | [f9faae4b87](https://linux-hardware.org/?probe=f9faae4b87) | Jan 22, 2024 |
| Apple         | MacBookPro9,2               | [835a20ab23](https://linux-hardware.org/?probe=835a20ab23) | Jan 21, 2024 |
| ASUSTek       | X550LA                      | [3010861da1](https://linux-hardware.org/?probe=3010861da1) | Jan 21, 2024 |
| HP            | Laptop 15s-gr0xxx           | [320f2c215a](https://linux-hardware.org/?probe=320f2c215a) | Jan 21, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [ddb59f8c7e](https://linux-hardware.org/?probe=ddb59f8c7e) | Jan 21, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [97e1f1353f](https://linux-hardware.org/?probe=97e1f1353f) | Jan 21, 2024 |
| Lenovo        | ThinkPad X220 429044U       | [d5fd867450](https://linux-hardware.org/?probe=d5fd867450) | Jan 21, 2024 |
| Acer          | Aspire R3-471T              | [5cf2f2b404](https://linux-hardware.org/?probe=5cf2f2b404) | Jan 21, 2024 |
| Acer          | Aspire R3-471T              | [3e062ccf04](https://linux-hardware.org/?probe=3e062ccf04) | Jan 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [4bc0f00e37](https://linux-hardware.org/?probe=4bc0f00e37) | Jan 21, 2024 |
| HP            | EliteBook 830 G6            | [7f5c817c53](https://linux-hardware.org/?probe=7f5c817c53) | Jan 21, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [ef2b018f0e](https://linux-hardware.org/?probe=ef2b018f0e) | Jan 21, 2024 |
| Toshiba       | Satellite C70-B             | [452f1d82f7](https://linux-hardware.org/?probe=452f1d82f7) | Jan 21, 2024 |
| Apple         | MacBookPro11,5              | [f3fe3777b0](https://linux-hardware.org/?probe=f3fe3777b0) | Jan 21, 2024 |
| Dell          | Inspiron 14 5410            | [018d9742c7](https://linux-hardware.org/?probe=018d9742c7) | Jan 21, 2024 |
| Lenovo        | ThinkPad T480 20L6S3C100    | [ef29c6e451](https://linux-hardware.org/?probe=ef29c6e451) | Jan 20, 2024 |
| Dell          | Precision 5480              | [2ebc089368](https://linux-hardware.org/?probe=2ebc089368) | Jan 20, 2024 |
| Sony          | SVF1521A1EW                 | [034a736927](https://linux-hardware.org/?probe=034a736927) | Jan 20, 2024 |
| Acer          | Aspire A315-35              | [baff1b7c03](https://linux-hardware.org/?probe=baff1b7c03) | Jan 20, 2024 |
| LG Electro... | 16Z90Q-G.AA54C2             | [d847e907f7](https://linux-hardware.org/?probe=d847e907f7) | Jan 20, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [a6f32a12ea](https://linux-hardware.org/?probe=a6f32a12ea) | Jan 20, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | [9f7b8c991a](https://linux-hardware.org/?probe=9f7b8c991a) | Jan 20, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | [4ec76f803c](https://linux-hardware.org/?probe=4ec76f803c) | Jan 20, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | [fbcde01158](https://linux-hardware.org/?probe=fbcde01158) | Jan 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8a52bc7ddc](https://linux-hardware.org/?probe=8a52bc7ddc) | Jan 20, 2024 |
| Infinix       | ZERO BOOK 13                | [5f3718642b](https://linux-hardware.org/?probe=5f3718642b) | Jan 20, 2024 |
| Dell          | Inspiron N5040              | [80702016eb](https://linux-hardware.org/?probe=80702016eb) | Jan 20, 2024 |
| Dell          | Latitude 3490               | [367100a9ad](https://linux-hardware.org/?probe=367100a9ad) | Jan 20, 2024 |
| Lenovo        | G580 2189                   | [a46c26bc93](https://linux-hardware.org/?probe=a46c26bc93) | Jan 20, 2024 |
| Samsung       | 960XFH                      | [fa6946bc7b](https://linux-hardware.org/?probe=fa6946bc7b) | Jan 19, 2024 |
| HONOR         | BMH-WCX9                    | [45113bdfbb](https://linux-hardware.org/?probe=45113bdfbb) | Jan 19, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [aca7a5c7c5](https://linux-hardware.org/?probe=aca7a5c7c5) | Jan 19, 2024 |
| Dell          | Inspiron 3501               | [dcd7920f8c](https://linux-hardware.org/?probe=dcd7920f8c) | Jan 19, 2024 |
| Nuvision      | L1W6_I1101_G Hampoo Rese... | [fb82a79de2](https://linux-hardware.org/?probe=fb82a79de2) | Jan 19, 2024 |
| Lenovo        | ThinkPad T450s 20BWS12V0... | [237a06ae54](https://linux-hardware.org/?probe=237a06ae54) | Jan 19, 2024 |
| HP            | Pavilion Laptop 15-cs3xx... | [0ce8f49628](https://linux-hardware.org/?probe=0ce8f49628) | Jan 19, 2024 |
| GPD           | P2 MAX                      | [ec59cadd15](https://linux-hardware.org/?probe=ec59cadd15) | Jan 19, 2024 |
| Apple         | MacBookPro10,1              | [f866974a0b](https://linux-hardware.org/?probe=f866974a0b) | Jan 18, 2024 |
| Dell          | Inspiron 3480               | [0c15974fbb](https://linux-hardware.org/?probe=0c15974fbb) | Jan 18, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [c765a21a05](https://linux-hardware.org/?probe=c765a21a05) | Jan 18, 2024 |
| ASUSTek       | X550VQ                      | [f20c1955ef](https://linux-hardware.org/?probe=f20c1955ef) | Jan 18, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [3b679561c7](https://linux-hardware.org/?probe=3b679561c7) | Jan 18, 2024 |
| MSI           | GE72 6QD                    | [17fb69aaa6](https://linux-hardware.org/?probe=17fb69aaa6) | Jan 18, 2024 |
| Lenovo        | ThinkPad X260 20F5S3J301    | [90905d3416](https://linux-hardware.org/?probe=90905d3416) | Jan 17, 2024 |
| Acer          | Aspire A315-57G             | [8c8ccb9324](https://linux-hardware.org/?probe=8c8ccb9324) | Jan 17, 2024 |
| Acer          | Aspire A315-57G             | [f7eb7dc2e9](https://linux-hardware.org/?probe=f7eb7dc2e9) | Jan 17, 2024 |
| Lenovo        | IdeaPad Slim 3 16IRU8 82... | [7c0ccbc993](https://linux-hardware.org/?probe=7c0ccbc993) | Jan 17, 2024 |
| Acer          | Swift SF314-43              | [a60906f053](https://linux-hardware.org/?probe=a60906f053) | Jan 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [39d3f0ad0b](https://linux-hardware.org/?probe=39d3f0ad0b) | Jan 17, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [385ae61d79](https://linux-hardware.org/?probe=385ae61d79) | Jan 17, 2024 |
| Panasonic     | CF-52PFN61PM                | [971bbaea1a](https://linux-hardware.org/?probe=971bbaea1a) | Jan 17, 2024 |
| HUAWEI        | MRGFG-XX                    | [826b284720](https://linux-hardware.org/?probe=826b284720) | Jan 17, 2024 |
| HP            | ENVY Notebook               | [f1289ece27](https://linux-hardware.org/?probe=f1289ece27) | Jan 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [02bc66202e](https://linux-hardware.org/?probe=02bc66202e) | Jan 17, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [09c8624b31](https://linux-hardware.org/?probe=09c8624b31) | Jan 16, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [83ccef18c2](https://linux-hardware.org/?probe=83ccef18c2) | Jan 16, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [78896edb96](https://linux-hardware.org/?probe=78896edb96) | Jan 16, 2024 |
| Unknown       | Unknown                     | [40de727301](https://linux-hardware.org/?probe=40de727301) | Jan 16, 2024 |
| Dell          | Vostro 5502                 | [a134c0eb16](https://linux-hardware.org/?probe=a134c0eb16) | Jan 16, 2024 |
| LG Electro... | P300-U.ABRAG                | [1336576fec](https://linux-hardware.org/?probe=1336576fec) | Jan 16, 2024 |
| Apple         | MacBookAir7,2               | [240262c43c](https://linux-hardware.org/?probe=240262c43c) | Jan 16, 2024 |
| Apple         | MacBookAir7,2               | [43f1d0cbe1](https://linux-hardware.org/?probe=43f1d0cbe1) | Jan 16, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [a28b135223](https://linux-hardware.org/?probe=a28b135223) | Jan 16, 2024 |
| Lenovo        | ThinkPad E490 20N90000BR    | [94ef2c20ba](https://linux-hardware.org/?probe=94ef2c20ba) | Jan 16, 2024 |
| Apple         | MacBookAir7,2               | [11c9a4f149](https://linux-hardware.org/?probe=11c9a4f149) | Jan 15, 2024 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [c2a719d955](https://linux-hardware.org/?probe=c2a719d955) | Jan 15, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [09e866e5e9](https://linux-hardware.org/?probe=09e866e5e9) | Jan 15, 2024 |
| Casper        | EXCALIBUR G900              | [8531ff6e44](https://linux-hardware.org/?probe=8531ff6e44) | Jan 15, 2024 |
| Casper        | EXCALIBUR G900              | [efb49fa361](https://linux-hardware.org/?probe=efb49fa361) | Jan 15, 2024 |
| ASUSTek       | N56VB                       | [3542693793](https://linux-hardware.org/?probe=3542693793) | Jan 15, 2024 |
| HP            | 630                         | [15cea68071](https://linux-hardware.org/?probe=15cea68071) | Jan 15, 2024 |
| Dell          | Inspiron 3501               | [fecc6a63eb](https://linux-hardware.org/?probe=fecc6a63eb) | Jan 15, 2024 |
| HP            | Laptop 15s-fq4xxx           | [4b0eb86898](https://linux-hardware.org/?probe=4b0eb86898) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [4a57c65ec3](https://linux-hardware.org/?probe=4a57c65ec3) | Jan 15, 2024 |
| Unknown       | Unknown                     | [cc6ea90bc9](https://linux-hardware.org/?probe=cc6ea90bc9) | Jan 15, 2024 |
| SPA CONDOR    | WM15-CCLPRO                 | [ad4f96e106](https://linux-hardware.org/?probe=ad4f96e106) | Jan 15, 2024 |
| Apple         | MacBookPro10,1              | [29522391fa](https://linux-hardware.org/?probe=29522391fa) | Jan 15, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [c699d403f6](https://linux-hardware.org/?probe=c699d403f6) | Jan 14, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [46074255e9](https://linux-hardware.org/?probe=46074255e9) | Jan 14, 2024 |
| Toshiba       | Satellite C75D-B            | [8716ceb6bd](https://linux-hardware.org/?probe=8716ceb6bd) | Jan 14, 2024 |
| ASUSTek       | G750JS                      | [ce24ff4784](https://linux-hardware.org/?probe=ce24ff4784) | Jan 14, 2024 |
| Dell          | Inspiron 15-3567            | [fe568bbc5d](https://linux-hardware.org/?probe=fe568bbc5d) | Jan 14, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [95569b47c5](https://linux-hardware.org/?probe=95569b47c5) | Jan 14, 2024 |
| Lenovo        | ThinkPad X250 20CM004XIX    | [5834e700db](https://linux-hardware.org/?probe=5834e700db) | Jan 14, 2024 |
| Lenovo        | Yoga Slim 6 14IAP8 83C7     | [4e4c095efb](https://linux-hardware.org/?probe=4e4c095efb) | Jan 14, 2024 |
| Gigabyte      | G5 KD                       | [1f4984ff1a](https://linux-hardware.org/?probe=1f4984ff1a) | Jan 14, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [3b89bdc1d9](https://linux-hardware.org/?probe=3b89bdc1d9) | Jan 14, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [ea56655c50](https://linux-hardware.org/?probe=ea56655c50) | Jan 14, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | [60e35c48cf](https://linux-hardware.org/?probe=60e35c48cf) | Jan 14, 2024 |
| Lenovo        | ThinkPad A285 20MXS0GT00    | [6fe7454ae4](https://linux-hardware.org/?probe=6fe7454ae4) | Jan 14, 2024 |
| MSI           | GE70 2PE                    | [5f5076a207](https://linux-hardware.org/?probe=5f5076a207) | Jan 14, 2024 |
| Acer          | Predator PH16-71            | [e2d230f52c](https://linux-hardware.org/?probe=e2d230f52c) | Jan 14, 2024 |
| MSI           | GT62VR 7RE                  | [11a6fc29dd](https://linux-hardware.org/?probe=11a6fc29dd) | Jan 14, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [9ede09f25a](https://linux-hardware.org/?probe=9ede09f25a) | Jan 14, 2024 |
| Dell          | Precision M6500             | [a295e6f19f](https://linux-hardware.org/?probe=a295e6f19f) | Jan 14, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [c7e3069d99](https://linux-hardware.org/?probe=c7e3069d99) | Jan 14, 2024 |
| Dell          | Latitude 5491               | [47908d47c4](https://linux-hardware.org/?probe=47908d47c4) | Jan 14, 2024 |
| Google        | Barla                       | [a2dc4bce8c](https://linux-hardware.org/?probe=a2dc4bce8c) | Jan 14, 2024 |
| Positivo B... | VJFE53F11X-XXXXXX           | [ebd0135392](https://linux-hardware.org/?probe=ebd0135392) | Jan 14, 2024 |
| Dell          | Precision M6500             | [8768db9ec2](https://linux-hardware.org/?probe=8768db9ec2) | Jan 13, 2024 |
| Apple         | MacBookPro11,2              | [c9f084fd2a](https://linux-hardware.org/?probe=c9f084fd2a) | Jan 13, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6f915e2f99](https://linux-hardware.org/?probe=6f915e2f99) | Jan 13, 2024 |
| Apple         | MacBookPro11,3              | [e47ef53e7f](https://linux-hardware.org/?probe=e47ef53e7f) | Jan 13, 2024 |
| HP            | EliteBook 745 G5            | [64314a5149](https://linux-hardware.org/?probe=64314a5149) | Jan 13, 2024 |
| ASUSTek       | G750JS                      | [a8eb3fc6f4](https://linux-hardware.org/?probe=a8eb3fc6f4) | Jan 13, 2024 |
| Dell          | Latitude E5450              | [a9275ec728](https://linux-hardware.org/?probe=a9275ec728) | Jan 13, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [f68b62b601](https://linux-hardware.org/?probe=f68b62b601) | Jan 13, 2024 |
| Dell          | Inspiron 15 3520            | [cec67d41f8](https://linux-hardware.org/?probe=cec67d41f8) | Jan 13, 2024 |
| Apple         | MacBookPro10,1              | [dc905da8e7](https://linux-hardware.org/?probe=dc905da8e7) | Jan 12, 2024 |
| Dell          | Latitude 3440               | [b8145337d1](https://linux-hardware.org/?probe=b8145337d1) | Jan 12, 2024 |
| HUAWEI        | BOM-WXX9                    | [77d4403dbe](https://linux-hardware.org/?probe=77d4403dbe) | Jan 12, 2024 |
| TUXEDO        | Pulse 14 Gen3               | [661a86f920](https://linux-hardware.org/?probe=661a86f920) | Jan 12, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [df073dcede](https://linux-hardware.org/?probe=df073dcede) | Jan 12, 2024 |
| Acer          | Predator PH315-53           | [bb3670e4b7](https://linux-hardware.org/?probe=bb3670e4b7) | Jan 12, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [27a04d94e5](https://linux-hardware.org/?probe=27a04d94e5) | Jan 12, 2024 |
| Dell          | Latitude 7300               | [0ad6fa9f50](https://linux-hardware.org/?probe=0ad6fa9f50) | Jan 12, 2024 |
| HP            | ProBook 450 G1              | [aada05f6c2](https://linux-hardware.org/?probe=aada05f6c2) | Jan 12, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [c9788a2dac](https://linux-hardware.org/?probe=c9788a2dac) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ee354e10c1](https://linux-hardware.org/?probe=ee354e10c1) | Jan 12, 2024 |
| ASUSTek       | X580VD                      | [25e38b0f43](https://linux-hardware.org/?probe=25e38b0f43) | Jan 12, 2024 |
| Dell          | Precision 3581              | [2bf1e4d7f0](https://linux-hardware.org/?probe=2bf1e4d7f0) | Jan 12, 2024 |
| Dell          | Latitude E6430              | [d09873629d](https://linux-hardware.org/?probe=d09873629d) | Jan 12, 2024 |
| Dell          | Latitude E7470              | [c4cb105efd](https://linux-hardware.org/?probe=c4cb105efd) | Jan 12, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582HS_... | [23667dd048](https://linux-hardware.org/?probe=23667dd048) | Jan 12, 2024 |
| Lenovo        | B50-30 20382                | [0ca9774d55](https://linux-hardware.org/?probe=0ca9774d55) | Jan 11, 2024 |
| Lenovo        | B50-30 20382                | [a2ee63de30](https://linux-hardware.org/?probe=a2ee63de30) | Jan 11, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [70593d8eb2](https://linux-hardware.org/?probe=70593d8eb2) | Jan 11, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [7378080744](https://linux-hardware.org/?probe=7378080744) | Jan 11, 2024 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [4d02212cbc](https://linux-hardware.org/?probe=4d02212cbc) | Jan 11, 2024 |
| ASUSTek       | G53SX                       | [01ccd618c5](https://linux-hardware.org/?probe=01ccd618c5) | Jan 11, 2024 |
| Dell          | XPS 13 9305                 | [382558433d](https://linux-hardware.org/?probe=382558433d) | Jan 11, 2024 |
| Unknown       | Unknown                     | [f6ae9e1e1d](https://linux-hardware.org/?probe=f6ae9e1e1d) | Jan 11, 2024 |
| Acer          | Predator PH16-71            | [a2cae97378](https://linux-hardware.org/?probe=a2cae97378) | Jan 11, 2024 |
| ASUSTek       | X542UQ                      | [80e9791b86](https://linux-hardware.org/?probe=80e9791b86) | Jan 11, 2024 |
| Acer          | Swift SFG14-42              | [15da646623](https://linux-hardware.org/?probe=15da646623) | Jan 11, 2024 |
| Dell          | Inspiron 16 5620            | [6ee5c8e435](https://linux-hardware.org/?probe=6ee5c8e435) | Jan 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [be9bd3885e](https://linux-hardware.org/?probe=be9bd3885e) | Jan 11, 2024 |
| General Dy... | Tadpole TOPAZ               | [2fb322cd2e](https://linux-hardware.org/?probe=2fb322cd2e) | Jan 11, 2024 |
| HUAWEI        | MRGFG-XX                    | [93269856b2](https://linux-hardware.org/?probe=93269856b2) | Jan 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [68a601314f](https://linux-hardware.org/?probe=68a601314f) | Jan 10, 2024 |
| Dell          | Latitude 5580               | [d97f97cf29](https://linux-hardware.org/?probe=d97f97cf29) | Jan 10, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [d205c03e58](https://linux-hardware.org/?probe=d205c03e58) | Jan 10, 2024 |
| HP            | Victus by Gaming Laptop ... | [fb2aecbc70](https://linux-hardware.org/?probe=fb2aecbc70) | Jan 10, 2024 |
| MSI           | Bravo 15 C7VE               | [6c44184013](https://linux-hardware.org/?probe=6c44184013) | Jan 10, 2024 |
| HP            | Laptop 17-cp0xxx            | [49486d60b3](https://linux-hardware.org/?probe=49486d60b3) | Jan 10, 2024 |
| Lenovo        | ThinkPad T430 2349RN6       | [787844bb19](https://linux-hardware.org/?probe=787844bb19) | Jan 10, 2024 |
| Acer          | Aspire 5733                 | [21d89e2212](https://linux-hardware.org/?probe=21d89e2212) | Jan 10, 2024 |
| Dell          | XPS 9320                    | [86cf8ad410](https://linux-hardware.org/?probe=86cf8ad410) | Jan 10, 2024 |
| Lenovo        | ThinkPad T480 20L6S3C100    | [c54acdce25](https://linux-hardware.org/?probe=c54acdce25) | Jan 10, 2024 |
| HP            | EliteBook 865 16 inch G9... | [ba001a1e95](https://linux-hardware.org/?probe=ba001a1e95) | Jan 10, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [8d20d6aac5](https://linux-hardware.org/?probe=8d20d6aac5) | Jan 10, 2024 |
| Lenovo        | ThinkPad W530 24474LG       | [7c1349e97d](https://linux-hardware.org/?probe=7c1349e97d) | Jan 10, 2024 |
| Dell          | Latitude 5521               | [8058baf2cb](https://linux-hardware.org/?probe=8058baf2cb) | Jan 10, 2024 |
| MSI           | Stealth GS66 12UGS          | [302723b72f](https://linux-hardware.org/?probe=302723b72f) | Jan 10, 2024 |
| Dell          | Inspiron 16 7610            | [2605684e23](https://linux-hardware.org/?probe=2605684e23) | Jan 09, 2024 |
| HP            | Laptop 15s-eq2xxx           | [376c519812](https://linux-hardware.org/?probe=376c519812) | Jan 09, 2024 |
| HP            | EliteBook 860 16 inch G1... | [efb5e0a5f7](https://linux-hardware.org/?probe=efb5e0a5f7) | Jan 09, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [6c8905667e](https://linux-hardware.org/?probe=6c8905667e) | Jan 09, 2024 |
| Dell          | Latitude 5290 2-in-1        | [b6d519e34c](https://linux-hardware.org/?probe=b6d519e34c) | Jan 09, 2024 |
| MSI           | GS66 Stealth 10SE           | [4af36bad9f](https://linux-hardware.org/?probe=4af36bad9f) | Jan 09, 2024 |
| Dell          | Latitude 7420               | [03a0ad44ae](https://linux-hardware.org/?probe=03a0ad44ae) | Jan 09, 2024 |
| HP            | ZBook 17 G4                 | [5dc1550956](https://linux-hardware.org/?probe=5dc1550956) | Jan 09, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [65ec7304a9](https://linux-hardware.org/?probe=65ec7304a9) | Jan 09, 2024 |
| HP            | Laptop 14s-dy5xxx           | [f64c72ed00](https://linux-hardware.org/?probe=f64c72ed00) | Jan 09, 2024 |
| Apple         | MacBookPro14,2              | [0d3413c236](https://linux-hardware.org/?probe=0d3413c236) | Jan 09, 2024 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [9a12d1146d](https://linux-hardware.org/?probe=9a12d1146d) | Jan 09, 2024 |
| Razer         | Blade 15 Base Model (Ear... | [a7c594cca5](https://linux-hardware.org/?probe=a7c594cca5) | Jan 08, 2024 |
| Dell          | Latitude 5511               | [6c6f30a5dd](https://linux-hardware.org/?probe=6c6f30a5dd) | Jan 08, 2024 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [825a5ed72b](https://linux-hardware.org/?probe=825a5ed72b) | Jan 08, 2024 |
| Apple         | MacBookAir6,2               | [45ab810378](https://linux-hardware.org/?probe=45ab810378) | Jan 08, 2024 |
| Dell          | Latitude 5511               | [9b5387e81f](https://linux-hardware.org/?probe=9b5387e81f) | Jan 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [c16e85c0b1](https://linux-hardware.org/?probe=c16e85c0b1) | Jan 08, 2024 |
| Lenovo        | ThinkPad X230 2325Y3G       | [f2c9141668](https://linux-hardware.org/?probe=f2c9141668) | Jan 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81d7f1e405](https://linux-hardware.org/?probe=81d7f1e405) | Jan 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1673e31468](https://linux-hardware.org/?probe=1673e31468) | Jan 08, 2024 |
| MSI           | Modern 15 A5M               | [1032489aa7](https://linux-hardware.org/?probe=1032489aa7) | Jan 08, 2024 |
| Acer          | Aspire A315-24P             | [716c2f37dd](https://linux-hardware.org/?probe=716c2f37dd) | Jan 08, 2024 |
| Dell          | Precision 5510              | [521a57df4a](https://linux-hardware.org/?probe=521a57df4a) | Jan 08, 2024 |
| HP            | Stream Laptop 11-ah1XX      | [bb9623d23f](https://linux-hardware.org/?probe=bb9623d23f) | Jan 08, 2024 |
| HP            | Laptop 15-ef1xxx            | [ab9812dca2](https://linux-hardware.org/?probe=ab9812dca2) | Jan 08, 2024 |
| Notebook      | NL5xRU                      | [8e36b92a02](https://linux-hardware.org/?probe=8e36b92a02) | Jan 08, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [9ee22790e4](https://linux-hardware.org/?probe=9ee22790e4) | Jan 08, 2024 |
| Acer          | Aspire A315-24P             | [ba75fc0540](https://linux-hardware.org/?probe=ba75fc0540) | Jan 08, 2024 |
| HP            | Laptop                      | [0fce2e2603](https://linux-hardware.org/?probe=0fce2e2603) | Jan 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [86ebfc719f](https://linux-hardware.org/?probe=86ebfc719f) | Jan 08, 2024 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [26b15c1102](https://linux-hardware.org/?probe=26b15c1102) | Jan 08, 2024 |
| MSI           | Bravo 15 C7VE               | [0235f555a0](https://linux-hardware.org/?probe=0235f555a0) | Jan 07, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [be56ab0378](https://linux-hardware.org/?probe=be56ab0378) | Jan 07, 2024 |
| HP            | ProBook 6360b               | [e47b503ba6](https://linux-hardware.org/?probe=e47b503ba6) | Jan 07, 2024 |
| Lenovo        | ThinkPad T480s 20L8S0R30... | [9cfe296019](https://linux-hardware.org/?probe=9cfe296019) | Jan 07, 2024 |
| ENTITY        | ENTYG11Q1                   | [b2ca051044](https://linux-hardware.org/?probe=b2ca051044) | Jan 07, 2024 |
| Apple         | MacBookPro13,2              | [c7e8eb2475](https://linux-hardware.org/?probe=c7e8eb2475) | Jan 07, 2024 |
| ENTITY        | ENTYG11Q1                   | [f9b0c03994](https://linux-hardware.org/?probe=f9b0c03994) | Jan 07, 2024 |
| HUAWEI        | WRT-WX9                     | [33092c4e45](https://linux-hardware.org/?probe=33092c4e45) | Jan 07, 2024 |
| Samsung       | 900X3L                      | [d77974be8d](https://linux-hardware.org/?probe=d77974be8d) | Jan 07, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [31daef8900](https://linux-hardware.org/?probe=31daef8900) | Jan 07, 2024 |
| MSI           | Modern 15 B5M               | [edf62d9f68](https://linux-hardware.org/?probe=edf62d9f68) | Jan 07, 2024 |
| Dell          | Inspiron 15 3520            | [c540776adb](https://linux-hardware.org/?probe=c540776adb) | Jan 07, 2024 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [5854a4d3e2](https://linux-hardware.org/?probe=5854a4d3e2) | Jan 07, 2024 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [a402710280](https://linux-hardware.org/?probe=a402710280) | Jan 07, 2024 |
| Apple         | MacBookAir8,2               | [d9ddd91356](https://linux-hardware.org/?probe=d9ddd91356) | Jan 07, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7 82S0    | [94a6c6bf63](https://linux-hardware.org/?probe=94a6c6bf63) | Jan 07, 2024 |
| Samsung       | RV415/RV515                 | [5451d552aa](https://linux-hardware.org/?probe=5451d552aa) | Jan 07, 2024 |
| Lenovo        | G710 20252                  | [0ee32cd03b](https://linux-hardware.org/?probe=0ee32cd03b) | Jan 07, 2024 |
| Gigabyte      | B660M DS3H DDR4             | [3e8e2de847](https://linux-hardware.org/?probe=3e8e2de847) | Jan 06, 2024 |
| Acer          | Aspire E5-574               | [4c6e591812](https://linux-hardware.org/?probe=4c6e591812) | Jan 06, 2024 |
| GPD           | G1621-02                    | [ea062fdae3](https://linux-hardware.org/?probe=ea062fdae3) | Jan 06, 2024 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [c6b6b98947](https://linux-hardware.org/?probe=c6b6b98947) | Jan 06, 2024 |
| Dell          | Latitude E6530              | [a813f516b9](https://linux-hardware.org/?probe=a813f516b9) | Jan 06, 2024 |
| Dell          | Inspiron N5110              | [0f0d661119](https://linux-hardware.org/?probe=0f0d661119) | Jan 06, 2024 |
| Acer          | Aspire E1-522               | [bc948a749d](https://linux-hardware.org/?probe=bc948a749d) | Jan 06, 2024 |
| Apple         | MacBookPro16,2              | [4a4cf1f56b](https://linux-hardware.org/?probe=4a4cf1f56b) | Jan 06, 2024 |
| Acer          | Aspire E5-722               | [f037171af4](https://linux-hardware.org/?probe=f037171af4) | Jan 06, 2024 |
| Fujitsu       | LIFEBOOK U747               | [4e93444c15](https://linux-hardware.org/?probe=4e93444c15) | Jan 06, 2024 |
| MSI           | GL62M 7REX                  | [d3f10df70f](https://linux-hardware.org/?probe=d3f10df70f) | Jan 06, 2024 |
| Fujitsu       | LIFEBOOK U747               | [7bee789f15](https://linux-hardware.org/?probe=7bee789f15) | Jan 06, 2024 |
| Acer          | Aspire A515-51G             | [6b47dd8ec2](https://linux-hardware.org/?probe=6b47dd8ec2) | Jan 06, 2024 |
| MSI           | GF63 Thin 10SC              | [001230dba0](https://linux-hardware.org/?probe=001230dba0) | Jan 06, 2024 |
| Lenovo        | ThinkPad X270 20HMS22H00    | [302c8659c3](https://linux-hardware.org/?probe=302c8659c3) | Jan 06, 2024 |
| ASUSTek       | Unknown                     | [d79d018083](https://linux-hardware.org/?probe=d79d018083) | Jan 06, 2024 |
| Acer          | Aspire A315-53              | [5828fad4a5](https://linux-hardware.org/?probe=5828fad4a5) | Jan 06, 2024 |
| OEM           | Unknown                     | [de6b4bdba5](https://linux-hardware.org/?probe=de6b4bdba5) | Jan 06, 2024 |
| Dell          | Inspiron 5480               | [fb0ac8ac2b](https://linux-hardware.org/?probe=fb0ac8ac2b) | Jan 06, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [cc89127000](https://linux-hardware.org/?probe=cc89127000) | Jan 05, 2024 |
| Toshiba       | Satellite C850-C5K          | [55c4519a60](https://linux-hardware.org/?probe=55c4519a60) | Jan 05, 2024 |
| Toshiba       | Satellite C855-2J5          | [3a219077df](https://linux-hardware.org/?probe=3a219077df) | Jan 05, 2024 |
| Acer          | Nitro AN515-44              | [4116ba8fb4](https://linux-hardware.org/?probe=4116ba8fb4) | Jan 05, 2024 |
| Dell          | Inspiron 3593               | [94cefd3624](https://linux-hardware.org/?probe=94cefd3624) | Jan 05, 2024 |
| Sony          | VPCS12AFJ                   | [b46e630517](https://linux-hardware.org/?probe=b46e630517) | Jan 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [05eebccb0b](https://linux-hardware.org/?probe=05eebccb0b) | Jan 05, 2024 |
| HP            | ProBook 445 G7              | [758fdda6d6](https://linux-hardware.org/?probe=758fdda6d6) | Jan 05, 2024 |
| MSI           | GE63VR 7RF                  | [9dc00ce09b](https://linux-hardware.org/?probe=9dc00ce09b) | Jan 05, 2024 |
| Lenovo        | V15 G3 IAP CTO 83C4         | [050c0c3ac6](https://linux-hardware.org/?probe=050c0c3ac6) | Jan 04, 2024 |
| MSI           | Prestige 15 A11SCS          | [c96226d4ac](https://linux-hardware.org/?probe=c96226d4ac) | Jan 04, 2024 |
| Toshiba       | Satellite C855-2J5          | [1e44b5beda](https://linux-hardware.org/?probe=1e44b5beda) | Jan 04, 2024 |
| Fujitsu       | UH-X                        | [fae98e772d](https://linux-hardware.org/?probe=fae98e772d) | Jan 04, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [5d5a6bbf4e](https://linux-hardware.org/?probe=5d5a6bbf4e) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [514f7e46c3](https://linux-hardware.org/?probe=514f7e46c3) | Jan 04, 2024 |
| Dell          | Inspiron 5583               | [1c3475390d](https://linux-hardware.org/?probe=1c3475390d) | Jan 04, 2024 |
| HUAWEI        | WRT-WX9                     | [1c7bfceeec](https://linux-hardware.org/?probe=1c7bfceeec) | Jan 04, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [183851c797](https://linux-hardware.org/?probe=183851c797) | Jan 04, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [6fae764b45](https://linux-hardware.org/?probe=6fae764b45) | Jan 04, 2024 |
| Acer          | Aspire A315-21              | [7d4f4c0cbc](https://linux-hardware.org/?probe=7d4f4c0cbc) | Jan 04, 2024 |
| Apple         | MacBookPro11,2              | [65c5154739](https://linux-hardware.org/?probe=65c5154739) | Jan 04, 2024 |
| ASUSTek       | K53SV                       | [c5f4f5d73b](https://linux-hardware.org/?probe=c5f4f5d73b) | Jan 04, 2024 |
| ASUSTek       | K53SV                       | [0dd63031cf](https://linux-hardware.org/?probe=0dd63031cf) | Jan 04, 2024 |
| HP            | EliteBook 840 G6            | [7fc5a1c4d0](https://linux-hardware.org/?probe=7fc5a1c4d0) | Jan 04, 2024 |
| HP            | ZBook Studio G3             | [21b560e443](https://linux-hardware.org/?probe=21b560e443) | Jan 04, 2024 |
| HP            | Notebook                    | [34b0db7948](https://linux-hardware.org/?probe=34b0db7948) | Jan 04, 2024 |
| Lenovo        | ThinkPad T410 2518FMG       | [d2e50fca98](https://linux-hardware.org/?probe=d2e50fca98) | Jan 03, 2024 |
| Lenovo        | ThinkPad T410 2518FMG       | [e1d4b75f1c](https://linux-hardware.org/?probe=e1d4b75f1c) | Jan 03, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [88f364d196](https://linux-hardware.org/?probe=88f364d196) | Jan 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1b25631ac9](https://linux-hardware.org/?probe=1b25631ac9) | Jan 03, 2024 |
| Dell          | Inspiron 3543               | [d4e58353b1](https://linux-hardware.org/?probe=d4e58353b1) | Jan 03, 2024 |
| Dell          | Latitude E7250              | [0c6c42e76e](https://linux-hardware.org/?probe=0c6c42e76e) | Jan 03, 2024 |
| Dell          | Latitude E6410              | [88d0787a66](https://linux-hardware.org/?probe=88d0787a66) | Jan 03, 2024 |
| HUAWEI        | NBM-WXX9                    | [f1a366a5a9](https://linux-hardware.org/?probe=f1a366a5a9) | Jan 03, 2024 |
| Unknown       | Unknown                     | [ec1ee65b65](https://linux-hardware.org/?probe=ec1ee65b65) | Jan 03, 2024 |
| Dell          | XPS 15 9570                 | [08ce6196e7](https://linux-hardware.org/?probe=08ce6196e7) | Jan 03, 2024 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [cdec50a425](https://linux-hardware.org/?probe=cdec50a425) | Jan 03, 2024 |
| Acer          | Aspire 5733Z                | [3a3502aceb](https://linux-hardware.org/?probe=3a3502aceb) | Jan 03, 2024 |
| Alienware     | M17x                        | [c699c086bb](https://linux-hardware.org/?probe=c699c086bb) | Jan 03, 2024 |
| Dell          | XPS 13 9360                 | [f115f9696c](https://linux-hardware.org/?probe=f115f9696c) | Jan 02, 2024 |
| Lenovo        | ThinkPad L540 20AUS2J000    | [a39424a752](https://linux-hardware.org/?probe=a39424a752) | Jan 02, 2024 |
| Dell          | Precision M3800             | [5867b0c6eb](https://linux-hardware.org/?probe=5867b0c6eb) | Jan 02, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | [2903680651](https://linux-hardware.org/?probe=2903680651) | Jan 02, 2024 |
| Google        | Blooglet                    | [e9a02f38b1](https://linux-hardware.org/?probe=e9a02f38b1) | Jan 02, 2024 |
| HP            | ProBook 6570b               | [113503a0a8](https://linux-hardware.org/?probe=113503a0a8) | Jan 02, 2024 |
| Dell          | Latitude 5290 2-in-1        | [30ccf5163b](https://linux-hardware.org/?probe=30ccf5163b) | Jan 02, 2024 |
| HP            | ProBook 6570b               | [98ccfce078](https://linux-hardware.org/?probe=98ccfce078) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [00e99b0067](https://linux-hardware.org/?probe=00e99b0067) | Jan 02, 2024 |
| Lenovo        | G50-70 20351                | [cb1029f101](https://linux-hardware.org/?probe=cb1029f101) | Jan 02, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | [389ae3afc8](https://linux-hardware.org/?probe=389ae3afc8) | Jan 02, 2024 |
| Lenovo        | ThinkPad T410 2522PT3       | [db100cd948](https://linux-hardware.org/?probe=db100cd948) | Jan 02, 2024 |
| Apple         | MacBookPro9,2               | [133a9d6ebc](https://linux-hardware.org/?probe=133a9d6ebc) | Jan 02, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [8701a130d2](https://linux-hardware.org/?probe=8701a130d2) | Jan 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [689f8869db](https://linux-hardware.org/?probe=689f8869db) | Jan 01, 2024 |
| Dell          | Inspiron 15 3530            | [ee21ee0e37](https://linux-hardware.org/?probe=ee21ee0e37) | Jan 01, 2024 |
| Dell          | Inspiron N5110              | [bf974230c7](https://linux-hardware.org/?probe=bf974230c7) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d4335b1132](https://linux-hardware.org/?probe=d4335b1132) | Jan 01, 2024 |
| Apple         | MacBookPro11,2              | [4a37a9b35c](https://linux-hardware.org/?probe=4a37a9b35c) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [20f988146c](https://linux-hardware.org/?probe=20f988146c) | Jan 01, 2024 |
| Lenovo        | ThinkPad T460 20FMS2291P    | [1a86f2a3d4](https://linux-hardware.org/?probe=1a86f2a3d4) | Jan 01, 2024 |
| Dell          | Latitude 5310               | [87c543db6f](https://linux-hardware.org/?probe=87c543db6f) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [de7126bf06](https://linux-hardware.org/?probe=de7126bf06) | Jan 01, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [4eb26f2685](https://linux-hardware.org/?probe=4eb26f2685) | Jan 01, 2024 |
| Dell          | XPS 15 9530                 | [22ba5950e3](https://linux-hardware.org/?probe=22ba5950e3) | Jan 01, 2024 |
| Dell          | XPS 15 9530                 | [dddd9b59bf](https://linux-hardware.org/?probe=dddd9b59bf) | Jan 01, 2024 |
| Dell          | Inspiron N5110              | [439d746143](https://linux-hardware.org/?probe=439d746143) | Dec 31, 2023 |
| Apple         | MacBookAir7,2               | [b25bae6ded](https://linux-hardware.org/?probe=b25bae6ded) | Dec 31, 2023 |
| HUAWEI        | KLVL-WXX9                   | [28ad8513b4](https://linux-hardware.org/?probe=28ad8513b4) | Dec 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [c0587a6f3f](https://linux-hardware.org/?probe=c0587a6f3f) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [cd2840bccc](https://linux-hardware.org/?probe=cd2840bccc) | Dec 31, 2023 |
| HP            | Laptop 14s-dq1xxx           | [f5f0fa82e5](https://linux-hardware.org/?probe=f5f0fa82e5) | Dec 31, 2023 |
| Apple         | MacBookPro6,2               | [1a25482d3d](https://linux-hardware.org/?probe=1a25482d3d) | Dec 31, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [47e1e3c766](https://linux-hardware.org/?probe=47e1e3c766) | Dec 31, 2023 |
| Thirdwave     | Prime Series                | [dc3d167b01](https://linux-hardware.org/?probe=dc3d167b01) | Dec 31, 2023 |
| HP            | ProBook 11 G2               | [6cf8228f10](https://linux-hardware.org/?probe=6cf8228f10) | Dec 31, 2023 |
| Acer          | Predator PH16-71            | [deae7730f2](https://linux-hardware.org/?probe=deae7730f2) | Dec 31, 2023 |
| Dell          | Inspiron 3505               | [bbcd14000a](https://linux-hardware.org/?probe=bbcd14000a) | Dec 30, 2023 |
| Dell          | Latitude 5540               | [604aab0481](https://linux-hardware.org/?probe=604aab0481) | Dec 30, 2023 |
| Packard Be... | EasyNote TS44HR             | [a06265dd1e](https://linux-hardware.org/?probe=a06265dd1e) | Dec 30, 2023 |
| Dell          | Inspiron 5748               | [20017233b9](https://linux-hardware.org/?probe=20017233b9) | Dec 30, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [aa1bee686a](https://linux-hardware.org/?probe=aa1bee686a) | Dec 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [adf7c97dab](https://linux-hardware.org/?probe=adf7c97dab) | Dec 30, 2023 |
| HP            | EliteBook 840 G3            | [d3bb35f033](https://linux-hardware.org/?probe=d3bb35f033) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f391231013](https://linux-hardware.org/?probe=f391231013) | Dec 30, 2023 |
| HP            | EliteBook 840 G3            | [52ed3f7e82](https://linux-hardware.org/?probe=52ed3f7e82) | Dec 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [33556742c3](https://linux-hardware.org/?probe=33556742c3) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [60da2c756f](https://linux-hardware.org/?probe=60da2c756f) | Dec 30, 2023 |
| ASUSTek       | U52F                        | [acf3ac6f23](https://linux-hardware.org/?probe=acf3ac6f23) | Dec 30, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | [017090bd57](https://linux-hardware.org/?probe=017090bd57) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f805c2c9fc](https://linux-hardware.org/?probe=f805c2c9fc) | Dec 30, 2023 |
| ASUSTek       | N551JW                      | [12339778af](https://linux-hardware.org/?probe=12339778af) | Dec 30, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [76f94ce16a](https://linux-hardware.org/?probe=76f94ce16a) | Dec 29, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [63af20b791](https://linux-hardware.org/?probe=63af20b791) | Dec 29, 2023 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [402a1c70b8](https://linux-hardware.org/?probe=402a1c70b8) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0fa90555a](https://linux-hardware.org/?probe=e0fa90555a) | Dec 29, 2023 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [13e876e5cf](https://linux-hardware.org/?probe=13e876e5cf) | Dec 29, 2023 |
| Lenovo        | ThinkPad T410 2537BY8       | [0117a0ab48](https://linux-hardware.org/?probe=0117a0ab48) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03199adbd4](https://linux-hardware.org/?probe=03199adbd4) | Dec 29, 2023 |
| Apple         | MacBookPro5,2               | [b6269d662d](https://linux-hardware.org/?probe=b6269d662d) | Dec 29, 2023 |
| Razer         | Blade                       | [87f8a27b0a](https://linux-hardware.org/?probe=87f8a27b0a) | Dec 29, 2023 |
| Dell          | Vostro 3405                 | [e527034e74](https://linux-hardware.org/?probe=e527034e74) | Dec 29, 2023 |
| Dell          | Vostro 3405                 | [aee31d728f](https://linux-hardware.org/?probe=aee31d728f) | Dec 29, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [99561c9ed3](https://linux-hardware.org/?probe=99561c9ed3) | Dec 29, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [13e6674db0](https://linux-hardware.org/?probe=13e6674db0) | Dec 29, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [53fc03e451](https://linux-hardware.org/?probe=53fc03e451) | Dec 29, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [fb4b958ae6](https://linux-hardware.org/?probe=fb4b958ae6) | Dec 29, 2023 |
| Apple         | MacBookAir4,2               | [ab4628dffe](https://linux-hardware.org/?probe=ab4628dffe) | Dec 29, 2023 |
| HONOR         | NMH-WDX9                    | [a632604865](https://linux-hardware.org/?probe=a632604865) | Dec 29, 2023 |
| Star Labs     | StarBook                    | [930fb359dd](https://linux-hardware.org/?probe=930fb359dd) | Dec 29, 2023 |
| HP            | Laptop 15-da0xxx            | [03ad95c394](https://linux-hardware.org/?probe=03ad95c394) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [6c5599855c](https://linux-hardware.org/?probe=6c5599855c) | Dec 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c0a8fdcf6f](https://linux-hardware.org/?probe=c0a8fdcf6f) | Dec 29, 2023 |
| Apple         | MacBookAir4,2               | [9a7ee6f89e](https://linux-hardware.org/?probe=9a7ee6f89e) | Dec 29, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [09f37233e4](https://linux-hardware.org/?probe=09f37233e4) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [0be6e9ce52](https://linux-hardware.org/?probe=0be6e9ce52) | Dec 29, 2023 |
| HP            | EliteBook 2570p             | [935d08358c](https://linux-hardware.org/?probe=935d08358c) | Dec 29, 2023 |
| Dell          | Inspiron 3542               | [06e3a35d05](https://linux-hardware.org/?probe=06e3a35d05) | Dec 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [92c8c4f42c](https://linux-hardware.org/?probe=92c8c4f42c) | Dec 28, 2023 |
| Lenovo        | G700 20251                  | [3426bbc85d](https://linux-hardware.org/?probe=3426bbc85d) | Dec 28, 2023 |
| Lenovo        | G700 20251                  | [78b29bb9e8](https://linux-hardware.org/?probe=78b29bb9e8) | Dec 28, 2023 |
| Dell          | Vostro 15 5510              | [02df63af48](https://linux-hardware.org/?probe=02df63af48) | Dec 28, 2023 |
| MSI           | GS70 2OD                    | [13dab050a1](https://linux-hardware.org/?probe=13dab050a1) | Dec 28, 2023 |
| MSI           | GS70 2OD                    | [7092678d3b](https://linux-hardware.org/?probe=7092678d3b) | Dec 28, 2023 |
| Acer          | Nitro AN515-54              | [b310676172](https://linux-hardware.org/?probe=b310676172) | Dec 28, 2023 |
| Apple         | MacBookPro15,4              | [b3691ac681](https://linux-hardware.org/?probe=b3691ac681) | Dec 28, 2023 |
| BAKED         | P65xRP                      | [4bd66fa9db](https://linux-hardware.org/?probe=4bd66fa9db) | Dec 28, 2023 |
| Unknown       | Unknown                     | [7c86c2f5dc](https://linux-hardware.org/?probe=7c86c2f5dc) | Dec 28, 2023 |
| HP            | EliteBook 840 G2            | [bbce6fb229](https://linux-hardware.org/?probe=bbce6fb229) | Dec 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [a135119148](https://linux-hardware.org/?probe=a135119148) | Dec 28, 2023 |
| HP            | ENVY Laptop 13-aq1xxx       | [44df1c7cc6](https://linux-hardware.org/?probe=44df1c7cc6) | Dec 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cc024fb567](https://linux-hardware.org/?probe=cc024fb567) | Dec 28, 2023 |
| HP            | EliteBook 840 G2            | [6ba5504a6f](https://linux-hardware.org/?probe=6ba5504a6f) | Dec 28, 2023 |
| Lenovo        | ThinkPad T510 43492RU       | [87b76140e0](https://linux-hardware.org/?probe=87b76140e0) | Dec 28, 2023 |
| Apple         | MacBookPro15,4              | [1d368b7c25](https://linux-hardware.org/?probe=1d368b7c25) | Dec 28, 2023 |
| HP            | Notebook                    | [5b3e4ada9c](https://linux-hardware.org/?probe=5b3e4ada9c) | Dec 28, 2023 |
| HP            | ProBook 11 G2               | [3ad144c68e](https://linux-hardware.org/?probe=3ad144c68e) | Dec 28, 2023 |
| Lenovo        | ThinkPad T560 20FH002GUS    | [76926807cc](https://linux-hardware.org/?probe=76926807cc) | Dec 28, 2023 |
| Lenovo        | ThinkPad T560 20FH002GUS    | [cf5b823135](https://linux-hardware.org/?probe=cf5b823135) | Dec 28, 2023 |
| ASUSTek       | ROG Strix G614JZ_G614JZ     | [3ec4d2a40d](https://linux-hardware.org/?probe=3ec4d2a40d) | Dec 27, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [151f072ac9](https://linux-hardware.org/?probe=151f072ac9) | Dec 27, 2023 |
| Lenovo        | Mullins-LarneML             | [e545ddc079](https://linux-hardware.org/?probe=e545ddc079) | Dec 27, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [eaa68fe0f5](https://linux-hardware.org/?probe=eaa68fe0f5) | Dec 27, 2023 |
| Apple         | MacBookPro11,1              | [344f1c919a](https://linux-hardware.org/?probe=344f1c919a) | Dec 27, 2023 |
| MSI           | Modern 15 B7M               | [2c7f48c9ad](https://linux-hardware.org/?probe=2c7f48c9ad) | Dec 27, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [7378a1bdb4](https://linux-hardware.org/?probe=7378a1bdb4) | Dec 27, 2023 |
| ASUSTek       | GL753VD                     | [73bbd42b1f](https://linux-hardware.org/?probe=73bbd42b1f) | Dec 27, 2023 |
| Chuwi         | MiniBook X                  | [6249e8f644](https://linux-hardware.org/?probe=6249e8f644) | Dec 27, 2023 |
| Dell          | XPS 15 9570                 | [25466d5d3b](https://linux-hardware.org/?probe=25466d5d3b) | Dec 27, 2023 |
| LG Electro... | 17Z90N-R.AAC8U1             | [b9fd2cf453](https://linux-hardware.org/?probe=b9fd2cf453) | Dec 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [10918ac964](https://linux-hardware.org/?probe=10918ac964) | Dec 27, 2023 |
| HP            | Laptop 14s-dy5xxx           | [de602b4dc6](https://linux-hardware.org/?probe=de602b4dc6) | Dec 27, 2023 |
| Dell          | XPS 17 9720                 | [ff40dc8bad](https://linux-hardware.org/?probe=ff40dc8bad) | Dec 27, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [d304e99c16](https://linux-hardware.org/?probe=d304e99c16) | Dec 27, 2023 |
| Acer          | TravelMate P256-M           | [c4f9e9de5e](https://linux-hardware.org/?probe=c4f9e9de5e) | Dec 27, 2023 |
| Acer          | TravelMate P256-M           | [c129debcae](https://linux-hardware.org/?probe=c129debcae) | Dec 27, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [df9f1cce5b](https://linux-hardware.org/?probe=df9f1cce5b) | Dec 27, 2023 |
| Acer          | Aspire E5-571G              | [a143ecb3c3](https://linux-hardware.org/?probe=a143ecb3c3) | Dec 27, 2023 |
| Lenovo        | ThinkPad T510 43492RU       | [d3f51b650d](https://linux-hardware.org/?probe=d3f51b650d) | Dec 27, 2023 |
| Dell          | Latitude E6530              | [bd56df50f6](https://linux-hardware.org/?probe=bd56df50f6) | Dec 26, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e832f6b336](https://linux-hardware.org/?probe=e832f6b336) | Dec 26, 2023 |
| HUAWEI        | MRGFG-XX                    | [8ac7316911](https://linux-hardware.org/?probe=8ac7316911) | Dec 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [a32866554a](https://linux-hardware.org/?probe=a32866554a) | Dec 26, 2023 |
| Lenovo        | ThinkPad W530 24474LG       | [180b4817c4](https://linux-hardware.org/?probe=180b4817c4) | Dec 26, 2023 |
| Apple         | MacBookPro13,1              | [63344458c9](https://linux-hardware.org/?probe=63344458c9) | Dec 26, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [3fd8513ee7](https://linux-hardware.org/?probe=3fd8513ee7) | Dec 26, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [c436ff8cab](https://linux-hardware.org/?probe=c436ff8cab) | Dec 26, 2023 |
| Dell          | XPS 13 9343                 | [8ba85bdc8c](https://linux-hardware.org/?probe=8ba85bdc8c) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [ef91ce6df3](https://linux-hardware.org/?probe=ef91ce6df3) | Dec 26, 2023 |
| Acer          | Nitro AN16-41               | [ae0d837def](https://linux-hardware.org/?probe=ae0d837def) | Dec 26, 2023 |
| Chuwi         | GemiBook Pro                | [0fceb23d42](https://linux-hardware.org/?probe=0fceb23d42) | Dec 25, 2023 |
| Apple         | MacBookPro13,1              | [555e444fe5](https://linux-hardware.org/?probe=555e444fe5) | Dec 25, 2023 |
| Dell          | Latitude E5470              | [71121b89c8](https://linux-hardware.org/?probe=71121b89c8) | Dec 25, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [c38f5ee95e](https://linux-hardware.org/?probe=c38f5ee95e) | Dec 25, 2023 |
| Dell          | Latitude 6430U              | [4c20fee408](https://linux-hardware.org/?probe=4c20fee408) | Dec 25, 2023 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [00e7af074b](https://linux-hardware.org/?probe=00e7af074b) | Dec 25, 2023 |
| Dell          | Latitude E6230              | [618343f74c](https://linux-hardware.org/?probe=618343f74c) | Dec 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | [41f592a596](https://linux-hardware.org/?probe=41f592a596) | Dec 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [69ec584b3a](https://linux-hardware.org/?probe=69ec584b3a) | Dec 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5b4d3b8b68](https://linux-hardware.org/?probe=5b4d3b8b68) | Dec 25, 2023 |
| Gigabyte      | AORUS 15 XE4                | [4fa06b2483](https://linux-hardware.org/?probe=4fa06b2483) | Dec 25, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [66915e859e](https://linux-hardware.org/?probe=66915e859e) | Dec 25, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [d775a90c0e](https://linux-hardware.org/?probe=d775a90c0e) | Dec 25, 2023 |
| Dell          | Inspiron 5520               | [27f944d802](https://linux-hardware.org/?probe=27f944d802) | Dec 25, 2023 |
| Dell          | Inspiron 5520               | [7cc405c94d](https://linux-hardware.org/?probe=7cc405c94d) | Dec 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | [eb3b2bf56b](https://linux-hardware.org/?probe=eb3b2bf56b) | Dec 24, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [3dcd1787be](https://linux-hardware.org/?probe=3dcd1787be) | Dec 24, 2023 |
| HP            | Pavilion g7                 | [f6a852d547](https://linux-hardware.org/?probe=f6a852d547) | Dec 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [23f36cddd3](https://linux-hardware.org/?probe=23f36cddd3) | Dec 24, 2023 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | [65afff0074](https://linux-hardware.org/?probe=65afff0074) | Dec 24, 2023 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | [496c9bc11f](https://linux-hardware.org/?probe=496c9bc11f) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [3bd91ab067](https://linux-hardware.org/?probe=3bd91ab067) | Dec 24, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [a5d5ac012b](https://linux-hardware.org/?probe=a5d5ac012b) | Dec 24, 2023 |
| Dell          | Latitude 7390               | [6b0dcd03de](https://linux-hardware.org/?probe=6b0dcd03de) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | [5206fdfe7e](https://linux-hardware.org/?probe=5206fdfe7e) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | [976944381c](https://linux-hardware.org/?probe=976944381c) | Dec 24, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [9822ecf249](https://linux-hardware.org/?probe=9822ecf249) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [720ff4cf67](https://linux-hardware.org/?probe=720ff4cf67) | Dec 24, 2023 |
| Lenovo        | ThinkPad E460 20ET0016US    | [96959ec0a3](https://linux-hardware.org/?probe=96959ec0a3) | Dec 24, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [de6b5ead5b](https://linux-hardware.org/?probe=de6b5ead5b) | Dec 24, 2023 |
| Acer          | Aspire 5742Z                | [ddf1553f4b](https://linux-hardware.org/?probe=ddf1553f4b) | Dec 24, 2023 |
| Samsung       | RV415/RV515                 | [da980644b4](https://linux-hardware.org/?probe=da980644b4) | Dec 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [29b4b5a349](https://linux-hardware.org/?probe=29b4b5a349) | Dec 24, 2023 |
| Dell          | G16 7630                    | [71f36f8ed0](https://linux-hardware.org/?probe=71f36f8ed0) | Dec 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [c0ff23eba6](https://linux-hardware.org/?probe=c0ff23eba6) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [d49a8fe4d4](https://linux-hardware.org/?probe=d49a8fe4d4) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [f1c9eab3f4](https://linux-hardware.org/?probe=f1c9eab3f4) | Dec 24, 2023 |
| Acer          | Aspire A515-43              | [922518c025](https://linux-hardware.org/?probe=922518c025) | Dec 23, 2023 |
| Dell          | Inspiron 15 3530            | [0688896e27](https://linux-hardware.org/?probe=0688896e27) | Dec 23, 2023 |
| HP            | Elite x2 1012 G1            | [b093087b3c](https://linux-hardware.org/?probe=b093087b3c) | Dec 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [a79885417a](https://linux-hardware.org/?probe=a79885417a) | Dec 23, 2023 |
| HP            | Elite x2 1012 G1            | [c93fffc388](https://linux-hardware.org/?probe=c93fffc388) | Dec 23, 2023 |
| Dell          | Latitude E6420              | [82c13c188b](https://linux-hardware.org/?probe=82c13c188b) | Dec 23, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b3e3c041d7](https://linux-hardware.org/?probe=b3e3c041d7) | Dec 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [40ba77bcb8](https://linux-hardware.org/?probe=40ba77bcb8) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5c4d1c7d64](https://linux-hardware.org/?probe=5c4d1c7d64) | Dec 23, 2023 |
| Dell          | XPS 13 9310                 | [78b73643ff](https://linux-hardware.org/?probe=78b73643ff) | Dec 23, 2023 |
| ASUSTek       | T100TA                      | [9ad17d2d3c](https://linux-hardware.org/?probe=9ad17d2d3c) | Dec 23, 2023 |
| Toshiba       | Satellite P850              | [e16f04d074](https://linux-hardware.org/?probe=e16f04d074) | Dec 23, 2023 |
| Danew         | Dbook 131                   | [a3880bd02c](https://linux-hardware.org/?probe=a3880bd02c) | Dec 23, 2023 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | [1ace47e8fd](https://linux-hardware.org/?probe=1ace47e8fd) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S69B00    | [16b6aaa173](https://linux-hardware.org/?probe=16b6aaa173) | Dec 23, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [9a5d0ca94a](https://linux-hardware.org/?probe=9a5d0ca94a) | Dec 23, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [2ca58f3eb8](https://linux-hardware.org/?probe=2ca58f3eb8) | Dec 23, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K6... | [d53640436b](https://linux-hardware.org/?probe=d53640436b) | Dec 22, 2023 |
| Dell          | Latitude 5420               | [9858586a84](https://linux-hardware.org/?probe=9858586a84) | Dec 22, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [dbfd9ef700](https://linux-hardware.org/?probe=dbfd9ef700) | Dec 22, 2023 |
| Dell          | Precision M4800             | [ce7a9239f4](https://linux-hardware.org/?probe=ce7a9239f4) | Dec 22, 2023 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [d65cca0578](https://linux-hardware.org/?probe=d65cca0578) | Dec 22, 2023 |
| Dell          | Latitude 7300               | [8792895835](https://linux-hardware.org/?probe=8792895835) | Dec 22, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [d36af9d69e](https://linux-hardware.org/?probe=d36af9d69e) | Dec 22, 2023 |
| Acer          | Nitro AN515-58              | [c7a31a4dab](https://linux-hardware.org/?probe=c7a31a4dab) | Dec 22, 2023 |
| ASUSTek       | Unknown                     | [60e10649cc](https://linux-hardware.org/?probe=60e10649cc) | Dec 22, 2023 |
| Dell          | Latitude 14 Rugged (5404... | [084f663c15](https://linux-hardware.org/?probe=084f663c15) | Dec 22, 2023 |
| Danew         | Dbook 131                   | [0568c9bdbf](https://linux-hardware.org/?probe=0568c9bdbf) | Dec 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [283320e72d](https://linux-hardware.org/?probe=283320e72d) | Dec 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [6f60c08653](https://linux-hardware.org/?probe=6f60c08653) | Dec 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [cf835775a4](https://linux-hardware.org/?probe=cf835775a4) | Dec 21, 2023 |
| Gigabyte      | AORUS 15 XE4                | [5dd281e2dd](https://linux-hardware.org/?probe=5dd281e2dd) | Dec 21, 2023 |
| MSI           | Modern 15 B7M               | [77760018a7](https://linux-hardware.org/?probe=77760018a7) | Dec 21, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [e864a3cd22](https://linux-hardware.org/?probe=e864a3cd22) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [cb7f868a54](https://linux-hardware.org/?probe=cb7f868a54) | Dec 21, 2023 |
| ASUSTek       | X411UA                      | [a4a14550e8](https://linux-hardware.org/?probe=a4a14550e8) | Dec 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ef2e756e7b](https://linux-hardware.org/?probe=ef2e756e7b) | Dec 21, 2023 |
| HUAWEI        | MRGFG-XX                    | [747de8fa3c](https://linux-hardware.org/?probe=747de8fa3c) | Dec 21, 2023 |
| Acer          | Aspire M5-581T              | [c99da67d31](https://linux-hardware.org/?probe=c99da67d31) | Dec 21, 2023 |
| HP            | ProBook 445 G7              | [4153ae7cc6](https://linux-hardware.org/?probe=4153ae7cc6) | Dec 21, 2023 |
| Acer          | Predator PH16-71            | [403fcc076f](https://linux-hardware.org/?probe=403fcc076f) | Dec 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [03b86f8fd8](https://linux-hardware.org/?probe=03b86f8fd8) | Dec 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [faabc05597](https://linux-hardware.org/?probe=faabc05597) | Dec 21, 2023 |
| Dell          | Latitude 3410               | [3de48ebce1](https://linux-hardware.org/?probe=3de48ebce1) | Dec 20, 2023 |
| Dell          | XPS 15 9510                 | [107d6edb72](https://linux-hardware.org/?probe=107d6edb72) | Dec 20, 2023 |
| ASUSTek       | X580VD                      | [18f5888ad5](https://linux-hardware.org/?probe=18f5888ad5) | Dec 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [398a10f8ce](https://linux-hardware.org/?probe=398a10f8ce) | Dec 20, 2023 |
| MSI           | Prestige 14Evo A12M         | [23e7499358](https://linux-hardware.org/?probe=23e7499358) | Dec 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eef5dcab57](https://linux-hardware.org/?probe=eef5dcab57) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c2eacfced7](https://linux-hardware.org/?probe=c2eacfced7) | Dec 20, 2023 |
| Dell          | Latitude E5450              | [6d4e378f53](https://linux-hardware.org/?probe=6d4e378f53) | Dec 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [44a01e07bb](https://linux-hardware.org/?probe=44a01e07bb) | Dec 20, 2023 |
| Apple         | MacBookPro14,2              | [e13dae2abd](https://linux-hardware.org/?probe=e13dae2abd) | Dec 20, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7b4cd22d8d](https://linux-hardware.org/?probe=7b4cd22d8d) | Dec 20, 2023 |
| ASUSTek       | X556URK                     | [b4f01c5bd5](https://linux-hardware.org/?probe=b4f01c5bd5) | Dec 19, 2023 |
| Dell          | Latitude 3460               | [c3b4a00583](https://linux-hardware.org/?probe=c3b4a00583) | Dec 19, 2023 |
| Dell          | Latitude 3460               | [3b425238a6](https://linux-hardware.org/?probe=3b425238a6) | Dec 19, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [4acd70fc9f](https://linux-hardware.org/?probe=4acd70fc9f) | Dec 19, 2023 |
| Acer          | Aspire A515-57              | [f6f623f0d8](https://linux-hardware.org/?probe=f6f623f0d8) | Dec 19, 2023 |
| HUAWEI        | MRGFG-XX                    | [6a10eb945c](https://linux-hardware.org/?probe=6a10eb945c) | Dec 19, 2023 |
| Dell          | Latitude E5450              | [627a81b211](https://linux-hardware.org/?probe=627a81b211) | Dec 19, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [a074081eb1](https://linux-hardware.org/?probe=a074081eb1) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [85531f6788](https://linux-hardware.org/?probe=85531f6788) | Dec 19, 2023 |
| Dell          | Inspiron N5110              | [761103087e](https://linux-hardware.org/?probe=761103087e) | Dec 19, 2023 |
| Acer          | Swift SF314-54              | [4d8fbbd6d0](https://linux-hardware.org/?probe=4d8fbbd6d0) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [4715b83a8c](https://linux-hardware.org/?probe=4715b83a8c) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [e37edfc830](https://linux-hardware.org/?probe=e37edfc830) | Dec 19, 2023 |
| Dell          | Inspiron 3542               | [7d3f7e97ce](https://linux-hardware.org/?probe=7d3f7e97ce) | Dec 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2d2f0f8de2](https://linux-hardware.org/?probe=2d2f0f8de2) | Dec 19, 2023 |
| Dell          | Inspiron 5520               | [df5cca640e](https://linux-hardware.org/?probe=df5cca640e) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9afec278e2](https://linux-hardware.org/?probe=9afec278e2) | Dec 18, 2023 |
| Dell          | Inspiron 5520               | [0d5fb0418b](https://linux-hardware.org/?probe=0d5fb0418b) | Dec 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1d8ddbcb75](https://linux-hardware.org/?probe=1d8ddbcb75) | Dec 18, 2023 |
| Dell          | Latitude 3420               | [59784d2788](https://linux-hardware.org/?probe=59784d2788) | Dec 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [147873adce](https://linux-hardware.org/?probe=147873adce) | Dec 18, 2023 |
| Dell          | Latitude E5470              | [9aa1f53217](https://linux-hardware.org/?probe=9aa1f53217) | Dec 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1c015093b2](https://linux-hardware.org/?probe=1c015093b2) | Dec 18, 2023 |
| Dell          | Latitude E5550              | [671595a2e5](https://linux-hardware.org/?probe=671595a2e5) | Dec 18, 2023 |
| GPD           | G1619-04                    | [63b517665b](https://linux-hardware.org/?probe=63b517665b) | Dec 18, 2023 |
| Lenovo        | ThinkPad T450s 20BX001LU... | [b3a6780db5](https://linux-hardware.org/?probe=b3a6780db5) | Dec 18, 2023 |
| Dell          | Latitude E7440              | [c2dce135e4](https://linux-hardware.org/?probe=c2dce135e4) | Dec 18, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4e18aeb53f](https://linux-hardware.org/?probe=4e18aeb53f) | Dec 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7d1b99f3a7](https://linux-hardware.org/?probe=7d1b99f3a7) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [1a1a04845b](https://linux-hardware.org/?probe=1a1a04845b) | Dec 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19fe61d807](https://linux-hardware.org/?probe=19fe61d807) | Dec 18, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [b0526a42f4](https://linux-hardware.org/?probe=b0526a42f4) | Dec 18, 2023 |
| Samsung       | 550P5C/550P7C               | [b06e8fbef4](https://linux-hardware.org/?probe=b06e8fbef4) | Dec 18, 2023 |
| ASUSTek       | K53SD                       | [4b43240ccd](https://linux-hardware.org/?probe=4b43240ccd) | Dec 18, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [612482d238](https://linux-hardware.org/?probe=612482d238) | Dec 18, 2023 |
| Compal        | PBL1011                     | [8983f2e331](https://linux-hardware.org/?probe=8983f2e331) | Dec 18, 2023 |
| Acer          | Nitro AN515-55              | [bdecd800b4](https://linux-hardware.org/?probe=bdecd800b4) | Dec 18, 2023 |
| Lenovo        | ThinkPad X270 20HMS0B60H    | [059545a4ad](https://linux-hardware.org/?probe=059545a4ad) | Dec 17, 2023 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [6ac6a904be](https://linux-hardware.org/?probe=6ac6a904be) | Dec 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [7b289201bc](https://linux-hardware.org/?probe=7b289201bc) | Dec 17, 2023 |
| Acer          | Nitro AN517-54              | [80aeddc1b2](https://linux-hardware.org/?probe=80aeddc1b2) | Dec 17, 2023 |
| HP            | ZBook 17 G5                 | [288e976604](https://linux-hardware.org/?probe=288e976604) | Dec 17, 2023 |
| Acer          | Nitro AN517-54              | [2f2bcf0c97](https://linux-hardware.org/?probe=2f2bcf0c97) | Dec 17, 2023 |
| Dell          | G5 5587                     | [0200ad8ea9](https://linux-hardware.org/?probe=0200ad8ea9) | Dec 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [26503ce57e](https://linux-hardware.org/?probe=26503ce57e) | Dec 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [16902836db](https://linux-hardware.org/?probe=16902836db) | Dec 17, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [845e586dba](https://linux-hardware.org/?probe=845e586dba) | Dec 17, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [b8d81eb2c9](https://linux-hardware.org/?probe=b8d81eb2c9) | Dec 17, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [c93d5be9d6](https://linux-hardware.org/?probe=c93d5be9d6) | Dec 17, 2023 |
| VIT           | P3400                       | [0564cdc52e](https://linux-hardware.org/?probe=0564cdc52e) | Dec 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [299d6ae362](https://linux-hardware.org/?probe=299d6ae362) | Dec 17, 2023 |
| Fujitsu       | LIFEBOOK U749               | [4ede8e182e](https://linux-hardware.org/?probe=4ede8e182e) | Dec 17, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [3a2290dbe0](https://linux-hardware.org/?probe=3a2290dbe0) | Dec 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [f4c923a84a](https://linux-hardware.org/?probe=f4c923a84a) | Dec 16, 2023 |
| Dell          | Inspiron 15-3567            | [570a822273](https://linux-hardware.org/?probe=570a822273) | Dec 16, 2023 |
| Fujitsu       | LIFEBOOK U728               | [381f2ea08d](https://linux-hardware.org/?probe=381f2ea08d) | Dec 16, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [a2a4eb520c](https://linux-hardware.org/?probe=a2a4eb520c) | Dec 16, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [9e217a08be](https://linux-hardware.org/?probe=9e217a08be) | Dec 16, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [f7ffef008a](https://linux-hardware.org/?probe=f7ffef008a) | Dec 16, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [fc9b36317a](https://linux-hardware.org/?probe=fc9b36317a) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [984c55c6a2](https://linux-hardware.org/?probe=984c55c6a2) | Dec 16, 2023 |
| Lenovo        | B50-80 80LT                 | [ea695bd9c5](https://linux-hardware.org/?probe=ea695bd9c5) | Dec 16, 2023 |
| Lenovo        | B50-80 80LT                 | [40d547e3f5](https://linux-hardware.org/?probe=40d547e3f5) | Dec 16, 2023 |
| HP            | Compaq CQ58                 | [7567b51bda](https://linux-hardware.org/?probe=7567b51bda) | Dec 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [56e95fc392](https://linux-hardware.org/?probe=56e95fc392) | Dec 16, 2023 |
| Apple         | MacBookPro10,1              | [adc736fc8d](https://linux-hardware.org/?probe=adc736fc8d) | Dec 16, 2023 |
| MSI           | GP62MVR 7RFX                | [fcb56f79d6](https://linux-hardware.org/?probe=fcb56f79d6) | Dec 16, 2023 |
| ASUSTek       | Q524UQ                      | [8466629595](https://linux-hardware.org/?probe=8466629595) | Dec 16, 2023 |
| Dell          | Inspiron 5447               | [0e868b4cba](https://linux-hardware.org/?probe=0e868b4cba) | Dec 15, 2023 |
| Dell          | Inspiron 5447               | [60320e4007](https://linux-hardware.org/?probe=60320e4007) | Dec 15, 2023 |
| Dell          | Inspiron 13-5378            | [d63cdec5eb](https://linux-hardware.org/?probe=d63cdec5eb) | Dec 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [cde85f7526](https://linux-hardware.org/?probe=cde85f7526) | Dec 15, 2023 |
| ASUSTek       | X540LJ                      | [281c56510a](https://linux-hardware.org/?probe=281c56510a) | Dec 15, 2023 |
| Apple         | MacBookPro5,3               | [f882c29faa](https://linux-hardware.org/?probe=f882c29faa) | Dec 15, 2023 |
| Dell          | Latitude E5550              | [dc16864fb6](https://linux-hardware.org/?probe=dc16864fb6) | Dec 15, 2023 |
| Apple         | MacBookPro11,3              | [106c5c6ec4](https://linux-hardware.org/?probe=106c5c6ec4) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e5916c58ec](https://linux-hardware.org/?probe=e5916c58ec) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [37495b67c9](https://linux-hardware.org/?probe=37495b67c9) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G531GU_GL531GU    | [b3b3853325](https://linux-hardware.org/?probe=b3b3853325) | Dec 15, 2023 |
| HP            | ZBook 15u G6                | [4467debb1c](https://linux-hardware.org/?probe=4467debb1c) | Dec 15, 2023 |
| Sony          | SVF1521G6EW                 | [55b5387ed5](https://linux-hardware.org/?probe=55b5387ed5) | Dec 15, 2023 |
| Apple         | MacBookPro5,3               | [066c7e2b1a](https://linux-hardware.org/?probe=066c7e2b1a) | Dec 15, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [b342bc9627](https://linux-hardware.org/?probe=b342bc9627) | Dec 14, 2023 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | [c2186c6471](https://linux-hardware.org/?probe=c2186c6471) | Dec 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [a043c13550](https://linux-hardware.org/?probe=a043c13550) | Dec 14, 2023 |
| Dell          | Inspiron 3793               | [90804693a6](https://linux-hardware.org/?probe=90804693a6) | Dec 14, 2023 |
| Dell          | Precision M3800             | [9e8d36821a](https://linux-hardware.org/?probe=9e8d36821a) | Dec 14, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | [91fd392ea3](https://linux-hardware.org/?probe=91fd392ea3) | Dec 14, 2023 |
| Apple         | MacBookAir9,1               | [6cadf8d04e](https://linux-hardware.org/?probe=6cadf8d04e) | Dec 14, 2023 |
| Dell          | Precision 5510              | [ddc02a6165](https://linux-hardware.org/?probe=ddc02a6165) | Dec 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [0728e617a0](https://linux-hardware.org/?probe=0728e617a0) | Dec 14, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [6a493a834d](https://linux-hardware.org/?probe=6a493a834d) | Dec 14, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [9d34609e0d](https://linux-hardware.org/?probe=9d34609e0d) | Dec 14, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [2b65b49ba3](https://linux-hardware.org/?probe=2b65b49ba3) | Dec 14, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [309aea6480](https://linux-hardware.org/?probe=309aea6480) | Dec 14, 2023 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [cda15a71e9](https://linux-hardware.org/?probe=cda15a71e9) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [0ece599b11](https://linux-hardware.org/?probe=0ece599b11) | Dec 14, 2023 |
| ASRock        | B560M Pro4/ac               | [0dd2927c25](https://linux-hardware.org/?probe=0dd2927c25) | Dec 14, 2023 |
| Dell          | G15 5520                    | [12b6fa0914](https://linux-hardware.org/?probe=12b6fa0914) | Dec 14, 2023 |
| A-DATA Tec... | XENIA 14                    | [ebbefc4570](https://linux-hardware.org/?probe=ebbefc4570) | Dec 14, 2023 |
| Dell          | G15 5520                    | [d212fe82aa](https://linux-hardware.org/?probe=d212fe82aa) | Dec 14, 2023 |
| Acer          | Nitro AN515-45              | [1ff0d683f4](https://linux-hardware.org/?probe=1ff0d683f4) | Dec 13, 2023 |
| Dell          | XPS 15 9530                 | [33d1f683ba](https://linux-hardware.org/?probe=33d1f683ba) | Dec 13, 2023 |
| Lenovo        | ThinkPad E560 20EV000SMZ    | [13b8795a4e](https://linux-hardware.org/?probe=13b8795a4e) | Dec 13, 2023 |
| Lenovo        | Z710 20250                  | [0ffc45c096](https://linux-hardware.org/?probe=0ffc45c096) | Dec 13, 2023 |
| HUAWEI        | HKD-WXX                     | [c6a0ea6b45](https://linux-hardware.org/?probe=c6a0ea6b45) | Dec 13, 2023 |
| Dell          | Precision 5510              | [0ce634decf](https://linux-hardware.org/?probe=0ce634decf) | Dec 13, 2023 |
| HP            | Laptop 17-cp0xxx            | [7d584c6a4d](https://linux-hardware.org/?probe=7d584c6a4d) | Dec 13, 2023 |
| HUAWEI        | HKD-WXX                     | [b0c03a26ce](https://linux-hardware.org/?probe=b0c03a26ce) | Dec 13, 2023 |
| Dell          | XPS 13 9350                 | [149a7f254a](https://linux-hardware.org/?probe=149a7f254a) | Dec 13, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [625439b5a5](https://linux-hardware.org/?probe=625439b5a5) | Dec 13, 2023 |
| Dell          | Precision 7510              | [863d50a5a5](https://linux-hardware.org/?probe=863d50a5a5) | Dec 13, 2023 |
| Dell          | Precision 7510              | [dddb88520a](https://linux-hardware.org/?probe=dddb88520a) | Dec 13, 2023 |
| HP            | EliteBook 840 G4            | [6440dbccd4](https://linux-hardware.org/?probe=6440dbccd4) | Dec 13, 2023 |
| Dell          | Inspiron 5584               | [525d98e3f0](https://linux-hardware.org/?probe=525d98e3f0) | Dec 13, 2023 |
| Lenovo        | ThinkPad E560 20EV000SMZ    | [1bb8694fda](https://linux-hardware.org/?probe=1bb8694fda) | Dec 12, 2023 |
| Acer          | Aspire A515-45              | [74dc572dd7](https://linux-hardware.org/?probe=74dc572dd7) | Dec 12, 2023 |
| Lenovo        | ThinkPad P1 20MD0001GE      | [e4c9202751](https://linux-hardware.org/?probe=e4c9202751) | Dec 12, 2023 |
| Lenovo        | ThinkPad P1 20MD0001GE      | [5662ef46db](https://linux-hardware.org/?probe=5662ef46db) | Dec 12, 2023 |
| Acer          | Aspire A515-45              | [089a40a6f2](https://linux-hardware.org/?probe=089a40a6f2) | Dec 12, 2023 |
| HP            | 15                          | [9c4fb8f41d](https://linux-hardware.org/?probe=9c4fb8f41d) | Dec 12, 2023 |
| HP            | OMEN by Laptop              | [12c97adbac](https://linux-hardware.org/?probe=12c97adbac) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | [9200b90a95](https://linux-hardware.org/?probe=9200b90a95) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | [917471b136](https://linux-hardware.org/?probe=917471b136) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | [6c3498a025](https://linux-hardware.org/?probe=6c3498a025) | Dec 12, 2023 |
| Apple         | MacBookPro14,1              | [16e9faf4e6](https://linux-hardware.org/?probe=16e9faf4e6) | Dec 12, 2023 |
| Apple         | MacBookPro14,1              | [05ceb8703b](https://linux-hardware.org/?probe=05ceb8703b) | Dec 12, 2023 |
| Timi          | A35R                        | [6133c765d4](https://linux-hardware.org/?probe=6133c765d4) | Dec 12, 2023 |
| Acer          | Extensa 215-55              | [40eaa33887](https://linux-hardware.org/?probe=40eaa33887) | Dec 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [293fe3fb8e](https://linux-hardware.org/?probe=293fe3fb8e) | Dec 12, 2023 |
| Alienware     | M17x                        | [da64c97fa8](https://linux-hardware.org/?probe=da64c97fa8) | Dec 12, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [dfe75293a5](https://linux-hardware.org/?probe=dfe75293a5) | Dec 12, 2023 |
| Acer          | Aspire A315-510P            | [e2bdedca29](https://linux-hardware.org/?probe=e2bdedca29) | Dec 12, 2023 |
| HUAWEI        | BOD-WXX9                    | [c12ada5b78](https://linux-hardware.org/?probe=c12ada5b78) | Dec 12, 2023 |
| Acer          | V5-171                      | [79abc82869](https://linux-hardware.org/?probe=79abc82869) | Dec 11, 2023 |
| MSI           | Modern 15 B7M               | [d4c74075be](https://linux-hardware.org/?probe=d4c74075be) | Dec 11, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9a6a483608](https://linux-hardware.org/?probe=9a6a483608) | Dec 11, 2023 |
| Lenovo        | G50-70 20351                | [d22fb3a791](https://linux-hardware.org/?probe=d22fb3a791) | Dec 11, 2023 |
| ASUSTek       | U52F                        | [5bdf8ec184](https://linux-hardware.org/?probe=5bdf8ec184) | Dec 11, 2023 |
| Dell          | Precision M6500             | [5b287ea21f](https://linux-hardware.org/?probe=5b287ea21f) | Dec 11, 2023 |
| Dell          | XPS 15 9510                 | [b88a7e6159](https://linux-hardware.org/?probe=b88a7e6159) | Dec 10, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | [2dc1349392](https://linux-hardware.org/?probe=2dc1349392) | Dec 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [ee7a9f7ba7](https://linux-hardware.org/?probe=ee7a9f7ba7) | Dec 10, 2023 |
| HP            | Laptop 17-cn3xxx            | [7a93c4b54c](https://linux-hardware.org/?probe=7a93c4b54c) | Dec 10, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [070ba5c3c1](https://linux-hardware.org/?probe=070ba5c3c1) | Dec 10, 2023 |
| Dell          | Inspiron 1525               | [9eb3de84e4](https://linux-hardware.org/?probe=9eb3de84e4) | Dec 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [2aef9deafb](https://linux-hardware.org/?probe=2aef9deafb) | Dec 10, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [3cfc2b72b4](https://linux-hardware.org/?probe=3cfc2b72b4) | Dec 10, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [c0797a823b](https://linux-hardware.org/?probe=c0797a823b) | Dec 10, 2023 |
| HP            | Laptop 15-da0xxx            | [2722000dd3](https://linux-hardware.org/?probe=2722000dd3) | Dec 10, 2023 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [d6ec80c299](https://linux-hardware.org/?probe=d6ec80c299) | Dec 10, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [d31e9bc5eb](https://linux-hardware.org/?probe=d31e9bc5eb) | Dec 10, 2023 |
| Dell          | Latitude 7440               | [2aef8e5157](https://linux-hardware.org/?probe=2aef8e5157) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [96a56fd534](https://linux-hardware.org/?probe=96a56fd534) | Dec 09, 2023 |
| ASUSTek       | P552LA                      | [cbe77e84b7](https://linux-hardware.org/?probe=cbe77e84b7) | Dec 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [a0670e0719](https://linux-hardware.org/?probe=a0670e0719) | Dec 09, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [baa82e571f](https://linux-hardware.org/?probe=baa82e571f) | Dec 09, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [140789380e](https://linux-hardware.org/?probe=140789380e) | Dec 09, 2023 |
| Dell          | Inspiron N5110              | [c7a949f9e8](https://linux-hardware.org/?probe=c7a949f9e8) | Dec 09, 2023 |
| Dell          | Latitude 3480               | [ee6070cfbe](https://linux-hardware.org/?probe=ee6070cfbe) | Dec 09, 2023 |
| Acer          | Predator PH16-71            | [234562596d](https://linux-hardware.org/?probe=234562596d) | Dec 09, 2023 |
| Gigabyte      | AORUS 15 9KF                | [d6386ee775](https://linux-hardware.org/?probe=d6386ee775) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [587ff35c26](https://linux-hardware.org/?probe=587ff35c26) | Dec 08, 2023 |
| Acer          | Aspire A515-47              | [363153833d](https://linux-hardware.org/?probe=363153833d) | Dec 08, 2023 |
| Dell          | Latitude 5511               | [9f006edcd8](https://linux-hardware.org/?probe=9f006edcd8) | Dec 08, 2023 |
| HP            | 630                         | [b6c4bc59c1](https://linux-hardware.org/?probe=b6c4bc59c1) | Dec 08, 2023 |
| Dell          | Latitude E6430              | [dee39185ec](https://linux-hardware.org/?probe=dee39185ec) | Dec 08, 2023 |
| MSI           | Katana GF76 11UD            | [a489e0db56](https://linux-hardware.org/?probe=a489e0db56) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2cc6eaff05](https://linux-hardware.org/?probe=2cc6eaff05) | Dec 08, 2023 |
| MSI           | Katana GF76 11UD            | [0f09b2440c](https://linux-hardware.org/?probe=0f09b2440c) | Dec 08, 2023 |
| HUAWEI        | MRGF-XX                     | [ec03f0452e](https://linux-hardware.org/?probe=ec03f0452e) | Dec 08, 2023 |
| HUAWEI        | MRGF-XX                     | [88fc932f99](https://linux-hardware.org/?probe=88fc932f99) | Dec 08, 2023 |
| Dell          | Precision M4700             | [54abe2ce35](https://linux-hardware.org/?probe=54abe2ce35) | Dec 08, 2023 |
| HP            | 15 Notebook PC              | [35b7f5d288](https://linux-hardware.org/?probe=35b7f5d288) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7f76b4716d](https://linux-hardware.org/?probe=7f76b4716d) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0a3a227554](https://linux-hardware.org/?probe=0a3a227554) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cf832dba27](https://linux-hardware.org/?probe=cf832dba27) | Dec 08, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [01f7b97e5d](https://linux-hardware.org/?probe=01f7b97e5d) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [2eb0717bf1](https://linux-hardware.org/?probe=2eb0717bf1) | Dec 07, 2023 |
| Sony          | VPCEB25FX                   | [f2d99590ca](https://linux-hardware.org/?probe=f2d99590ca) | Dec 07, 2023 |
| HUAWEI        | KLVC-WXX9                   | [cd7c131bf1](https://linux-hardware.org/?probe=cd7c131bf1) | Dec 07, 2023 |
| HP            | EliteBook 840 14 inch G1... | [b2fcb75892](https://linux-hardware.org/?probe=b2fcb75892) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [eea00eb64c](https://linux-hardware.org/?probe=eea00eb64c) | Dec 07, 2023 |
| Toshiba       | Satellite C70-B             | [6493c4fcf8](https://linux-hardware.org/?probe=6493c4fcf8) | Dec 07, 2023 |
| Acer          | Aspire A515-45              | [ccc3f6589d](https://linux-hardware.org/?probe=ccc3f6589d) | Dec 07, 2023 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [96ab8b0be8](https://linux-hardware.org/?probe=96ab8b0be8) | Dec 07, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [8ec5586df3](https://linux-hardware.org/?probe=8ec5586df3) | Dec 07, 2023 |
| HONOR         | HGF-WX6                     | [0ba74f97d0](https://linux-hardware.org/?probe=0ba74f97d0) | Dec 07, 2023 |
| Dell          | System Inspiron N4110       | [72874bcc85](https://linux-hardware.org/?probe=72874bcc85) | Dec 07, 2023 |
| HP            | EliteBook 845 14 inch G1... | [aa4dc92984](https://linux-hardware.org/?probe=aa4dc92984) | Dec 07, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [3ffedf98eb](https://linux-hardware.org/?probe=3ffedf98eb) | Dec 07, 2023 |
| Dell          | XPS 13 9310                 | [1b786f8834](https://linux-hardware.org/?probe=1b786f8834) | Dec 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2d483d736b](https://linux-hardware.org/?probe=2d483d736b) | Dec 06, 2023 |
| Dell          | XPS 13 9310                 | [2e32594a3f](https://linux-hardware.org/?probe=2e32594a3f) | Dec 06, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | [65ec6660cc](https://linux-hardware.org/?probe=65ec6660cc) | Dec 06, 2023 |
| Packard Be... | EasyNote TSX66HR            | [8ca6149044](https://linux-hardware.org/?probe=8ca6149044) | Dec 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [7376c1f4cf](https://linux-hardware.org/?probe=7376c1f4cf) | Dec 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [0c0833952d](https://linux-hardware.org/?probe=0c0833952d) | Dec 06, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [f87c61387d](https://linux-hardware.org/?probe=f87c61387d) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5940ba1d2c](https://linux-hardware.org/?probe=5940ba1d2c) | Dec 06, 2023 |
| Toshiba       | Satellite C70-B             | [ea76b3e92c](https://linux-hardware.org/?probe=ea76b3e92c) | Dec 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [fc51759095](https://linux-hardware.org/?probe=fc51759095) | Dec 06, 2023 |
| HUAWEI        | RLEF-XX                     | [519c5e78fc](https://linux-hardware.org/?probe=519c5e78fc) | Dec 06, 2023 |
| HUAWEI        | KLVL-WXXW                   | [3c655a8eed](https://linux-hardware.org/?probe=3c655a8eed) | Dec 05, 2023 |
| Dell          | Precision 7720              | [da0616987d](https://linux-hardware.org/?probe=da0616987d) | Dec 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [de12499622](https://linux-hardware.org/?probe=de12499622) | Dec 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [ad7bb46855](https://linux-hardware.org/?probe=ad7bb46855) | Dec 05, 2023 |
| Dell          | Inspiron 3593               | [3a07569e5f](https://linux-hardware.org/?probe=3a07569e5f) | Dec 05, 2023 |
| Acer          | TravelMate P414-51          | [bc31600bfa](https://linux-hardware.org/?probe=bc31600bfa) | Dec 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [997c250e85](https://linux-hardware.org/?probe=997c250e85) | Dec 05, 2023 |
| ASUSTek       | GL553VD                     | [578cbbda94](https://linux-hardware.org/?probe=578cbbda94) | Dec 05, 2023 |
| Dell          | Latitude E7440              | [48aff5ace0](https://linux-hardware.org/?probe=48aff5ace0) | Dec 05, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1cfd81f715](https://linux-hardware.org/?probe=1cfd81f715) | Dec 05, 2023 |
| Apple         | MacBookPro11,5              | [749492541f](https://linux-hardware.org/?probe=749492541f) | Dec 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [6e9230f8ab](https://linux-hardware.org/?probe=6e9230f8ab) | Dec 05, 2023 |
| Dell          | G7 7588                     | [8564f8e395](https://linux-hardware.org/?probe=8564f8e395) | Dec 05, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [ac97a3fe1c](https://linux-hardware.org/?probe=ac97a3fe1c) | Dec 05, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [fe13325e26](https://linux-hardware.org/?probe=fe13325e26) | Dec 05, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [b8a831d450](https://linux-hardware.org/?probe=b8a831d450) | Dec 04, 2023 |
| HP            | 630                         | [7d372bb7da](https://linux-hardware.org/?probe=7d372bb7da) | Dec 04, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | [a8c094f376](https://linux-hardware.org/?probe=a8c094f376) | Dec 04, 2023 |
| Acer          | Swift SF314-58G             | [14862c0964](https://linux-hardware.org/?probe=14862c0964) | Dec 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [3965451e6d](https://linux-hardware.org/?probe=3965451e6d) | Dec 04, 2023 |
| Acer          | Swift SFE16-42              | [f61134a2d0](https://linux-hardware.org/?probe=f61134a2d0) | Dec 04, 2023 |
| Dell          | Latitude 5420               | [b3ebc9b0fc](https://linux-hardware.org/?probe=b3ebc9b0fc) | Dec 04, 2023 |
| MSI           | Prestige 15 A12UD           | [b19937fb48](https://linux-hardware.org/?probe=b19937fb48) | Dec 04, 2023 |
| MSI           | Prestige 15 A12UD           | [0c9a3a5cae](https://linux-hardware.org/?probe=0c9a3a5cae) | Dec 04, 2023 |
| Dell          | XPS 15 9530                 | [e6d446fcd3](https://linux-hardware.org/?probe=e6d446fcd3) | Dec 04, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [ff7bf1a3cc](https://linux-hardware.org/?probe=ff7bf1a3cc) | Dec 04, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [1e1ea2cc1d](https://linux-hardware.org/?probe=1e1ea2cc1d) | Dec 04, 2023 |
| Valve         | Jupiter                     | [0caac1007d](https://linux-hardware.org/?probe=0caac1007d) | Dec 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [ccf7855510](https://linux-hardware.org/?probe=ccf7855510) | Dec 03, 2023 |
| Alienware     | M17x                        | [f1c871bbd9](https://linux-hardware.org/?probe=f1c871bbd9) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [7b5f2ca2f9](https://linux-hardware.org/?probe=7b5f2ca2f9) | Dec 03, 2023 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | [151a3ceaf0](https://linux-hardware.org/?probe=151a3ceaf0) | Dec 03, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [2ffb70a1ca](https://linux-hardware.org/?probe=2ffb70a1ca) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [f8a528e1d6](https://linux-hardware.org/?probe=f8a528e1d6) | Dec 03, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [20e77986a2](https://linux-hardware.org/?probe=20e77986a2) | Dec 03, 2023 |
| MSI           | Thin GF63 12HW              | [0612c99f8a](https://linux-hardware.org/?probe=0612c99f8a) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a7c5eb788c](https://linux-hardware.org/?probe=a7c5eb788c) | Dec 03, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [20a5a6a137](https://linux-hardware.org/?probe=20a5a6a137) | Dec 03, 2023 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | [5f96e00c00](https://linux-hardware.org/?probe=5f96e00c00) | Dec 03, 2023 |
| Acer          | Swift SF314-58G             | [d2a73d55eb](https://linux-hardware.org/?probe=d2a73d55eb) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [e3255e030f](https://linux-hardware.org/?probe=e3255e030f) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [da6b435afa](https://linux-hardware.org/?probe=da6b435afa) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [fe6c19062f](https://linux-hardware.org/?probe=fe6c19062f) | Dec 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [b85f62262a](https://linux-hardware.org/?probe=b85f62262a) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6189dc268f](https://linux-hardware.org/?probe=6189dc268f) | Dec 02, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [983698f613](https://linux-hardware.org/?probe=983698f613) | Dec 02, 2023 |
| Lenovo        | ThinkPad T480s 20L7001SM... | [da99e083aa](https://linux-hardware.org/?probe=da99e083aa) | Dec 02, 2023 |
| Lenovo        | ThinkPad E15 20RD0019IX     | [5d53fe03da](https://linux-hardware.org/?probe=5d53fe03da) | Dec 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7b5d061328](https://linux-hardware.org/?probe=7b5d061328) | Dec 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1729d2c4c1](https://linux-hardware.org/?probe=1729d2c4c1) | Dec 02, 2023 |
| Dell          | Inspiron 15-3565            | [6e0eb386a4](https://linux-hardware.org/?probe=6e0eb386a4) | Dec 02, 2023 |
| Dell          | Latitude 3540               | [64067574ad](https://linux-hardware.org/?probe=64067574ad) | Dec 02, 2023 |
| Lenovo        | ThinkPad T460s 20FAS09H0... | [94274c6313](https://linux-hardware.org/?probe=94274c6313) | Dec 02, 2023 |
| Acer          | Aspire A515-45              | [9875097d6a](https://linux-hardware.org/?probe=9875097d6a) | Dec 01, 2023 |
| Dell          | Inspiron 7720               | [974a2661e2](https://linux-hardware.org/?probe=974a2661e2) | Dec 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [997f545600](https://linux-hardware.org/?probe=997f545600) | Dec 01, 2023 |
| Dynabook      | PORTEGE X50-G               | [65a2f2f3d5](https://linux-hardware.org/?probe=65a2f2f3d5) | Dec 01, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [bf9f891fe4](https://linux-hardware.org/?probe=bf9f891fe4) | Dec 01, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [b5086b8a65](https://linux-hardware.org/?probe=b5086b8a65) | Dec 01, 2023 |
| HP            | Pavilion Notebook           | [06fdc9d8e6](https://linux-hardware.org/?probe=06fdc9d8e6) | Dec 01, 2023 |
| ASUSTek       | X555LAB                     | [b60a0a3ed7](https://linux-hardware.org/?probe=b60a0a3ed7) | Dec 01, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [100228341f](https://linux-hardware.org/?probe=100228341f) | Dec 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [deba3c2073](https://linux-hardware.org/?probe=deba3c2073) | Nov 30, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [c7a78a1510](https://linux-hardware.org/?probe=c7a78a1510) | Nov 30, 2023 |
| Apple         | MacBook4,1                  | [72fc73581b](https://linux-hardware.org/?probe=72fc73581b) | Nov 30, 2023 |
| HP            | ProBook 4540s               | [e1e15771c1](https://linux-hardware.org/?probe=e1e15771c1) | Nov 30, 2023 |
| Timi          | A35S                        | [3c967bd86d](https://linux-hardware.org/?probe=3c967bd86d) | Nov 30, 2023 |
| Lenovo        | Z51-70 80K6                 | [e7fab4df3b](https://linux-hardware.org/?probe=e7fab4df3b) | Nov 30, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [f2dc650bdf](https://linux-hardware.org/?probe=f2dc650bdf) | Nov 30, 2023 |
| Dell          | G15 5515                    | [25c732d6aa](https://linux-hardware.org/?probe=25c732d6aa) | Nov 30, 2023 |
| Dell          | G15 5511                    | [f77d3ad016](https://linux-hardware.org/?probe=f77d3ad016) | Nov 30, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [13d2cf2679](https://linux-hardware.org/?probe=13d2cf2679) | Nov 30, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [cbe557a601](https://linux-hardware.org/?probe=cbe557a601) | Nov 30, 2023 |
| Dell          | XPS 9320                    | [e4ca1d9f5f](https://linux-hardware.org/?probe=e4ca1d9f5f) | Nov 30, 2023 |
| Dell          | Latitude 3480               | [f83ad2bb01](https://linux-hardware.org/?probe=f83ad2bb01) | Nov 30, 2023 |
| Avell High... | B.ON                        | [22a1430347](https://linux-hardware.org/?probe=22a1430347) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d9b203868f](https://linux-hardware.org/?probe=d9b203868f) | Nov 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [6596326097](https://linux-hardware.org/?probe=6596326097) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7db0c2781b](https://linux-hardware.org/?probe=7db0c2781b) | Nov 29, 2023 |
| Apple         | MacBook4,1                  | [ea63175ae6](https://linux-hardware.org/?probe=ea63175ae6) | Nov 29, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BE09    | [33b3b8ed10](https://linux-hardware.org/?probe=33b3b8ed10) | Nov 29, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [4fb92d7fe0](https://linux-hardware.org/?probe=4fb92d7fe0) | Nov 29, 2023 |
| Samsung       | RF511/RF411/RF711           | [4446f12e33](https://linux-hardware.org/?probe=4446f12e33) | Nov 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [fa60a82ab5](https://linux-hardware.org/?probe=fa60a82ab5) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [50fb1dbbfb](https://linux-hardware.org/?probe=50fb1dbbfb) | Nov 29, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [a5caeab77f](https://linux-hardware.org/?probe=a5caeab77f) | Nov 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5e08371b05](https://linux-hardware.org/?probe=5e08371b05) | Nov 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c4bd54d16b](https://linux-hardware.org/?probe=c4bd54d16b) | Nov 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [61876cd7a5](https://linux-hardware.org/?probe=61876cd7a5) | Nov 29, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [248ac55d99](https://linux-hardware.org/?probe=248ac55d99) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [31b8894b55](https://linux-hardware.org/?probe=31b8894b55) | Nov 29, 2023 |
| Dell          | Inspiron 15 3530            | [410e2cc867](https://linux-hardware.org/?probe=410e2cc867) | Nov 29, 2023 |
| HP            | Elite x2 1012 G1            | [1fda4e1f6d](https://linux-hardware.org/?probe=1fda4e1f6d) | Nov 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [97719198b9](https://linux-hardware.org/?probe=97719198b9) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9d88b4ad0b](https://linux-hardware.org/?probe=9d88b4ad0b) | Nov 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [184a3ca616](https://linux-hardware.org/?probe=184a3ca616) | Nov 28, 2023 |
| MSI           | Summit E14Evo A12M          | [32b533e055](https://linux-hardware.org/?probe=32b533e055) | Nov 28, 2023 |
| Apple         | MacBookPro11,1              | [e8fadc04f4](https://linux-hardware.org/?probe=e8fadc04f4) | Nov 28, 2023 |
| HP            | ProBook 445 G7              | [979fcdaea6](https://linux-hardware.org/?probe=979fcdaea6) | Nov 28, 2023 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [7be81f9e9c](https://linux-hardware.org/?probe=7be81f9e9c) | Nov 28, 2023 |
| HP            | ZBook 14 G2                 | [124f1ff011](https://linux-hardware.org/?probe=124f1ff011) | Nov 28, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [62b0e92532](https://linux-hardware.org/?probe=62b0e92532) | Nov 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0390B    | [9b37545fa9](https://linux-hardware.org/?probe=9b37545fa9) | Nov 28, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [f813230b08](https://linux-hardware.org/?probe=f813230b08) | Nov 27, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [f8cdbfddcd](https://linux-hardware.org/?probe=f8cdbfddcd) | Nov 27, 2023 |
| HP            | Laptop 15s-eq1xxx           | [0769357573](https://linux-hardware.org/?probe=0769357573) | Nov 27, 2023 |
| HONOR         | BMH-WCX9                    | [62d142db95](https://linux-hardware.org/?probe=62d142db95) | Nov 27, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [6418e60f5a](https://linux-hardware.org/?probe=6418e60f5a) | Nov 27, 2023 |
| HP            | EliteBook 850 G6            | [597c5faf3a](https://linux-hardware.org/?probe=597c5faf3a) | Nov 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5fabcb33c4](https://linux-hardware.org/?probe=5fabcb33c4) | Nov 27, 2023 |
| Dell          | G15 5515                    | [b33a8c3a2e](https://linux-hardware.org/?probe=b33a8c3a2e) | Nov 27, 2023 |
| Dell          | Latitude 7490               | [70a7c438a1](https://linux-hardware.org/?probe=70a7c438a1) | Nov 27, 2023 |
| Lenovo        | 15ARE05 81W4                | [4fa9ab8a76](https://linux-hardware.org/?probe=4fa9ab8a76) | Nov 27, 2023 |
| Dell          | Inspiron 5566               | [df3eed7cc0](https://linux-hardware.org/?probe=df3eed7cc0) | Nov 27, 2023 |
| Teclast       | F6S                         | [d8c3190c92](https://linux-hardware.org/?probe=d8c3190c92) | Nov 27, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [23d18fc15e](https://linux-hardware.org/?probe=23d18fc15e) | Nov 27, 2023 |
| HP            | Notebook                    | [be0de1221c](https://linux-hardware.org/?probe=be0de1221c) | Nov 26, 2023 |
| Apple         | MacBook10,1                 | [78c3cc842b](https://linux-hardware.org/?probe=78c3cc842b) | Nov 26, 2023 |
| HP            | Laptop 15-bw0xx             | [542c0ce906](https://linux-hardware.org/?probe=542c0ce906) | Nov 26, 2023 |
| HUAWEI        | HVY-WXX9                    | [e083bf134c](https://linux-hardware.org/?probe=e083bf134c) | Nov 26, 2023 |
| HP            | Laptop 15-dy2xxx            | [858c641fcf](https://linux-hardware.org/?probe=858c641fcf) | Nov 26, 2023 |
| Dell          | Precision M3800             | [a01e02361f](https://linux-hardware.org/?probe=a01e02361f) | Nov 26, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [68ead98f75](https://linux-hardware.org/?probe=68ead98f75) | Nov 26, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [ce1806eec5](https://linux-hardware.org/?probe=ce1806eec5) | Nov 26, 2023 |
| Lenovo        | G510 20238                  | [3f9a7e29e7](https://linux-hardware.org/?probe=3f9a7e29e7) | Nov 26, 2023 |
| HP            | 250 G1                      | [ac68122660](https://linux-hardware.org/?probe=ac68122660) | Nov 26, 2023 |
| HUAWEI        | RLEF-XX                     | [626b08dbe0](https://linux-hardware.org/?probe=626b08dbe0) | Nov 26, 2023 |
| Lenovo        | Unknown                     | [504a4bd033](https://linux-hardware.org/?probe=504a4bd033) | Nov 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [ce68d047a6](https://linux-hardware.org/?probe=ce68d047a6) | Nov 26, 2023 |
| Unknown       | Unknown                     | [9bebf014dd](https://linux-hardware.org/?probe=9bebf014dd) | Nov 26, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [78b8e2f560](https://linux-hardware.org/?probe=78b8e2f560) | Nov 26, 2023 |
| MSI           | PS63 Modern 8RC             | [d647ccba36](https://linux-hardware.org/?probe=d647ccba36) | Nov 26, 2023 |
| Dell          | XPS 15 9570                 | [8e243668e7](https://linux-hardware.org/?probe=8e243668e7) | Nov 26, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [1e704edcd6](https://linux-hardware.org/?probe=1e704edcd6) | Nov 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e18bd022e8](https://linux-hardware.org/?probe=e18bd022e8) | Nov 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [c887e86fe4](https://linux-hardware.org/?probe=c887e86fe4) | Nov 25, 2023 |
| Apple         | MacBookPro9,2               | [ab9cf7394e](https://linux-hardware.org/?probe=ab9cf7394e) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [36e2df7f72](https://linux-hardware.org/?probe=36e2df7f72) | Nov 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [2188d0c4b8](https://linux-hardware.org/?probe=2188d0c4b8) | Nov 25, 2023 |
| MSI           | Thin GF63 12HW              | [82a4c6642b](https://linux-hardware.org/?probe=82a4c6642b) | Nov 25, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [9e623760a1](https://linux-hardware.org/?probe=9e623760a1) | Nov 25, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [8f6ce26933](https://linux-hardware.org/?probe=8f6ce26933) | Nov 25, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [6d1874da45](https://linux-hardware.org/?probe=6d1874da45) | Nov 25, 2023 |
| Acer          | Swift SFE16-42              | [6b2a075d5a](https://linux-hardware.org/?probe=6b2a075d5a) | Nov 25, 2023 |
| Matsushita... | CF-30FCDALAM                | [94d60b91d5](https://linux-hardware.org/?probe=94d60b91d5) | Nov 25, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [6c397edda9](https://linux-hardware.org/?probe=6c397edda9) | Nov 25, 2023 |
| Apple         | MacBookPro14,1              | [390152e044](https://linux-hardware.org/?probe=390152e044) | Nov 25, 2023 |
| HP            | Compaq CQ58                 | [51198853ca](https://linux-hardware.org/?probe=51198853ca) | Nov 25, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [cc4ce2ca20](https://linux-hardware.org/?probe=cc4ce2ca20) | Nov 25, 2023 |
| Lenovo        | G510 20238                  | [75a5b58cb8](https://linux-hardware.org/?probe=75a5b58cb8) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [082c36ab01](https://linux-hardware.org/?probe=082c36ab01) | Nov 25, 2023 |
| Acer          | Aspire A315-24P             | [30586cdeb5](https://linux-hardware.org/?probe=30586cdeb5) | Nov 24, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [2b2ac91a50](https://linux-hardware.org/?probe=2b2ac91a50) | Nov 24, 2023 |
| Lenovo        | Legion 9 16IRX8 83AG        | [f511dac11e](https://linux-hardware.org/?probe=f511dac11e) | Nov 24, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Fedora 38 | 1772      | 18.66%  |
| Fedora 36 | 1243      | 13.09%  |
| Fedora 37 | 1240      | 13.06%  |
| Fedora 35 | 976       | 10.28%  |
| Fedora 34 | 941       | 9.91%   |
| Fedora 39 | 919       | 9.68%   |
| Fedora 33 | 857       | 9.02%   |
| Fedora 32 | 746       | 7.86%   |
| Fedora 31 | 503       | 5.3%    |
| Fedora 30 | 163       | 1.72%   |
| Fedora 29 | 90        | 0.95%   |
| Fedora 28 | 22        | 0.23%   |
| Fedora 27 | 8         | 0.08%   |
| Fedora 40 | 6         | 0.06%   |
| Fedora 24 | 4         | 0.04%   |
| Fedora 21 | 4         | 0.04%   |
| Fedora 25 | 2         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Fedora | 8487      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.9-300.fc38.x86_64   | 223       | 2.12%   |
| 6.2.15-300.fc38.x86_64  | 142       | 1.35%   |
| 6.5.11-300.fc39.x86_64  | 138       | 1.31%   |
| 5.17.5-300.fc36.x86_64  | 116       | 1.1%    |
| 6.3.8-200.fc38.x86_64   | 114       | 1.08%   |
| 6.5.6-300.fc39.x86_64   | 111       | 1.05%   |
| 6.6.9-200.fc39.x86_64   | 108       | 1.03%   |
| 6.6.8-200.fc39.x86_64   | 102       | 0.97%   |
| 6.4.15-200.fc38.x86_64  | 102       | 0.97%   |
| 6.0.7-301.fc37.x86_64   | 93        | 0.88%   |
| 5.16.18-200.fc35.x86_64 | 92        | 0.87%   |
| 6.5.5-200.fc38.x86_64   | 90        | 0.86%   |
| 6.2.14-300.fc38.x86_64  | 90        | 0.86%   |
| 5.9.16-200.fc33.x86_64  | 90        | 0.86%   |
| 6.2.11-300.fc38.x86_64  | 87        | 0.83%   |
| 5.11.12-300.fc34.x86_64 | 77        | 0.73%   |
| 6.0.15-300.fc37.x86_64  | 76        | 0.72%   |
| 5.14.10-300.fc35.x86_64 | 71        | 0.67%   |
| 6.0.5-200.fc36.x86_64   | 69        | 0.66%   |
| 6.5.8-200.fc38.x86_64   | 67        | 0.64%   |
| 6.3.12-200.fc38.x86_64  | 66        | 0.63%   |
| 5.8.16-300.fc33.x86_64  | 64        | 0.61%   |
| 6.6.13-200.fc39.x86_64  | 61        | 0.58%   |
| 6.1.14-200.fc37.x86_64  | 61        | 0.58%   |
| 5.8.15-301.fc33.x86_64  | 61        | 0.58%   |
| 5.18.13-200.fc36.x86_64 | 61        | 0.58%   |
| 6.5.12-300.fc39.x86_64  | 59        | 0.56%   |
| 6.0.8-300.fc37.x86_64   | 57        | 0.54%   |
| 5.8.4-200.fc32.x86_64   | 57        | 0.54%   |
| 6.4.6-200.fc38.x86_64   | 56        | 0.53%   |
| 6.1.7-200.fc37.x86_64   | 56        | 0.53%   |
| 6.6.4-200.fc39.x86_64   | 55        | 0.52%   |
| 6.6.6-200.fc39.x86_64   | 54        | 0.51%   |
| 5.13.12-200.fc34.x86_64 | 54        | 0.51%   |
| 6.5.6-200.fc38.x86_64   | 53        | 0.5%    |
| 6.3.11-200.fc38.x86_64  | 52        | 0.49%   |
| 6.0.9-300.fc37.x86_64   | 52        | 0.49%   |
| 6.4.14-200.fc38.x86_64  | 51        | 0.48%   |
| 6.1.18-200.fc37.x86_64  | 51        | 0.48%   |
| 6.0.12-300.fc37.x86_64  | 51        | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.9   | 263       | 2.5%    |
| 6.2.15  | 183       | 1.74%   |
| 6.5.6   | 166       | 1.58%   |
| 5.17.5  | 150       | 1.43%   |
| 6.5.11  | 140       | 1.33%   |
| 6.3.8   | 125       | 1.19%   |
| 6.6.8   | 113       | 1.07%   |
| 6.6.9   | 111       | 1.06%   |
| 6.5.5   | 107       | 1.02%   |
| 6.4.15  | 104       | 0.99%   |
| 6.2.14  | 104       | 0.99%   |
| 6.0.7   | 103       | 0.98%   |
| 6.2.11  | 99        | 0.94%   |
| 5.9.16  | 96        | 0.91%   |
| 5.16.18 | 95        | 0.9%    |
| 5.8.15  | 88        | 0.84%   |
| 6.0.15  | 86        | 0.82%   |
| 5.11.12 | 84        | 0.8%    |
| 5.8.16  | 81        | 0.77%   |
| 5.14.10 | 80        | 0.76%   |
| 6.0.5   | 75        | 0.71%   |
| 5.19.16 | 75        | 0.71%   |
| 6.5.8   | 71        | 0.67%   |
| 6.0.12  | 71        | 0.67%   |
| 6.3.12  | 70        | 0.67%   |
| 6.5.12  | 69        | 0.66%   |
| 6.0.8   | 69        | 0.66%   |
| 6.0.9   | 67        | 0.64%   |
| 5.11.11 | 66        | 0.63%   |
| 5.18.13 | 65        | 0.62%   |
| 6.1.14  | 64        | 0.61%   |
| 5.8.18  | 64        | 0.61%   |
| 6.6.6   | 63        | 0.6%    |
| 6.6.13  | 63        | 0.6%    |
| 6.6.4   | 62        | 0.59%   |
| 6.1.7   | 61        | 0.58%   |
| 6.4.6   | 57        | 0.54%   |
| 6.2.8   | 57        | 0.54%   |
| 5.8.4   | 57        | 0.54%   |
| 5.13.12 | 57        | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 849       | 8.42%   |
| 6.5     | 690       | 6.85%   |
| 6.0     | 661       | 6.56%   |
| 6.6     | 608       | 6.03%   |
| 5.17    | 522       | 5.18%   |
| 6.4     | 505       | 5.01%   |
| 6.1     | 481       | 4.77%   |
| 5.8     | 465       | 4.61%   |
| 5.19    | 450       | 4.46%   |
| 5.11    | 449       | 4.45%   |
| 5.18    | 410       | 4.07%   |
| 6.3     | 404       | 4.01%   |
| 5.14    | 395       | 3.92%   |
| 5.16    | 384       | 3.81%   |
| 5.15    | 310       | 3.08%   |
| 5.9     | 304       | 3.02%   |
| 5.13    | 303       | 3.01%   |
| 5.10    | 294       | 2.92%   |
| 5.6     | 286       | 2.84%   |
| 5.12    | 282       | 2.8%    |
| 5.7     | 221       | 2.19%   |
| 5.3     | 194       | 1.92%   |
| 5.5     | 183       | 1.82%   |
| 5.4     | 169       | 1.68%   |
| 5.0     | 62        | 0.62%   |
| 5.2     | 47        | 0.47%   |
| 5.1     | 43        | 0.43%   |
| 4.19    | 30        | 0.3%    |
| 4.18    | 27        | 0.27%   |
| 4.20    | 18        | 0.18%   |
| 6.7     | 12        | 0.12%   |
| 4.16    | 3         | 0.03%   |
| 4.15    | 3         | 0.03%   |
| 4.11    | 3         | 0.03%   |
| 4.1     | 3         | 0.03%   |
| 4.8     | 2         | 0.02%   |
| 4.17    | 2         | 0.02%   |
| 4.5     | 1         | 0.01%   |
| 4.14    | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 8477      | 99.87%  |
| i686    | 5         | 0.06%   |
| aarch64 | 5         | 0.06%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 6510      | 74.7%   |
| KDE5            | 1043      | 11.97%  |
| Unknown         | 345       | 3.96%   |
| XFCE            | 172       | 1.97%   |
| KDE             | 137       | 1.57%   |
| X-Cinnamon      | 114       | 1.31%   |
| MATE            | 101       | 1.16%   |
| Cinnamon        | 81        | 0.93%   |
| i3              | 37        | 0.42%   |
| GNOME Classic   | 31        | 0.36%   |
| sway            | 26        | 0.3%    |
| LXQt            | 25        | 0.29%   |
| LXDE            | 20        | 0.23%   |
| Deepin          | 15        | 0.17%   |
| Budgie          | 15        | 0.17%   |
| Pantheon        | 5         | 0.06%   |
| Hyprland        | 5         | 0.06%   |
| KDE4            | 4         | 0.05%   |
| fluxbox         | 4         | 0.05%   |
| awesome         | 4         | 0.05%   |
| openbox         | 3         | 0.03%   |
| GNOME-Classic   | 3         | 0.03%   |
| GNOME Flashback | 3         | 0.03%   |
| xinit-compat    | 2         | 0.02%   |
| dwm             | 2         | 0.02%   |
| bspwm           | 2         | 0.02%   |
| xmonad          | 1         | 0.01%   |
| Unity           | 1         | 0.01%   |
| qtile           | 1         | 0.01%   |
| KDE:old         | 1         | 0.01%   |
| i3-with-shmlog  | 1         | 0.01%   |
| custom          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 6115      | 69.58%  |
| X11     | 2387      | 27.16%  |
| Unknown | 221       | 2.51%   |
| Tty     | 65        | 0.74%   |
| Xcb     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4625      | 53.04%  |
| GDM     | 3010      | 34.52%  |
| SDDM    | 621       | 7.12%   |
| LightDM | 347       | 3.98%   |
| TDM     | 87        | 1%      |
| XDM     | 10        | 0.11%   |
| LXDM    | 9         | 0.1%    |
| KDM     | 8         | 0.09%   |
| SLiM    | 1         | 0.01%   |
| Ly      | 1         | 0.01%   |
| GREETD  | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 4412      | 51.09%  |
| en_GB   | 619       | 7.17%   |
| ru_RU   | 421       | 4.87%   |
| pt_BR   | 394       | 4.56%   |
| Unknown | 376       | 4.35%   |
| de_DE   | 318       | 3.68%   |
| fr_FR   | 253       | 2.93%   |
| it_IT   | 233       | 2.7%    |
| pl_PL   | 137       | 1.59%   |
| es_ES   | 132       | 1.53%   |
| en_CA   | 128       | 1.48%   |
| en_IN   | 117       | 1.35%   |
| en_AU   | 113       | 1.31%   |
| es_MX   | 89        | 1.03%   |
| es_CL   | 60        | 0.69%   |
| cs_CZ   | 51        | 0.59%   |
| zh_CN   | 46        | 0.53%   |
| tr_TR   | 45        | 0.52%   |
| es_AR   | 40        | 0.46%   |
| es_CO   | 38        | 0.44%   |
| pt_PT   | 36        | 0.42%   |
| en_DK   | 33        | 0.38%   |
| de_AT   | 29        | 0.34%   |
| nl_NL   | 28        | 0.32%   |
| hu_HU   | 28        | 0.32%   |
| sv_SE   | 25        | 0.29%   |
| en_NZ   | 24        | 0.28%   |
| en_ZA   | 22        | 0.25%   |
| en_IE   | 21        | 0.24%   |
| C       | 21        | 0.24%   |
| ru_UA   | 20        | 0.23%   |
| fr_CA   | 18        | 0.21%   |
| de_CH   | 16        | 0.19%   |
| es_PE   | 15        | 0.17%   |
| nb_NO   | 14        | 0.16%   |
| fi_FI   | 14        | 0.16%   |
| sk_SK   | 13        | 0.15%   |
| fr_BE   | 13        | 0.15%   |
| en_SG   | 13        | 0.15%   |
| uk_UA   | 11        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 6979      | 81.09%  |
| BIOS | 1628      | 18.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 5712      | 65.91%  |
| Ext4                | 2541      | 29.32%  |
| Unknown             | 196       | 2.26%   |
| Xfs                 | 192       | 2.22%   |
| Overlay             | 13        | 0.15%   |
| Zfs                 | 3         | 0.03%   |
| F2fs                | 3         | 0.03%   |
| Ext3                | 3         | 0.03%   |
| Fuse.fuse-overlayfs | 2         | 0.02%   |
| Tmpfs               | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4577      | 52.72%  |
| GPT     | 3673      | 42.31%  |
| MBR     | 431       | 4.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7821      | 91.13%  |
| Yes       | 761       | 8.87%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7051      | 82.15%  |
| Yes       | 1532      | 17.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 2463      | 29.02%  |
| Dell                   | 1485      | 17.5%   |
| Hewlett-Packard        | 1254      | 14.78%  |
| ASUSTek Computer       | 913       | 10.76%  |
| Acer                   | 549       | 6.47%   |
| Apple                  | 269       | 3.17%   |
| MSI                    | 202       | 2.38%   |
| HUAWEI                 | 193       | 2.27%   |
| Samsung Electronics    | 115       | 1.36%   |
| Toshiba                | 107       | 1.26%   |
| Sony                   | 65        | 0.77%   |
| Timi                   | 63        | 0.74%   |
| Notebook               | 61        | 0.72%   |
| Framework              | 50        | 0.59%   |
| Google                 | 48        | 0.57%   |
| Unknown                | 42        | 0.49%   |
| Fujitsu                | 39        | 0.46%   |
| Alienware              | 31        | 0.37%   |
| Positivo               | 25        | 0.29%   |
| TUXEDO                 | 23        | 0.27%   |
| System76               | 23        | 0.27%   |
| Gigabyte Technology    | 23        | 0.27%   |
| Razer                  | 21        | 0.25%   |
| LG Electronics         | 20        | 0.24%   |
| HONOR                  | 19        | 0.22%   |
| Chuwi                  | 17        | 0.2%    |
| Avell High Performance | 13        | 0.15%   |
| Schenker               | 12        | 0.14%   |
| PC Specialist          | 11        | 0.13%   |
| Packard Bell           | 11        | 0.13%   |
| GPU Company            | 10        | 0.12%   |
| GPD                    | 10        | 0.12%   |
| Panasonic              | 9         | 0.11%   |
| SLIMBOOK               | 8         | 0.09%   |
| Fujitsu Siemens        | 8         | 0.09%   |
| Intel Client Systems   | 7         | 0.08%   |
| Positivo Bahia - VAIO  | 6         | 0.07%   |
| Insyde                 | 6         | 0.07%   |
| Hampoo                 | 6         | 0.07%   |
| Clevo                  | 6         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 69        | 0.81%   |
| HP Notebook                                | 43        | 0.51%   |
| Framework Laptop                           | 31        | 0.37%   |
| Dell Latitude 7490                         | 29        | 0.34%   |
| Dell XPS 15 9570                           | 27        | 0.32%   |
| Apple MacBookPro9,2                        | 27        | 0.32%   |
| Dell XPS 13 9370                           | 26        | 0.31%   |
| Dell XPS 15 7590                           | 25        | 0.29%   |
| Dell XPS 15 9560                           | 24        | 0.28%   |
| Dell XPS 13 9310                           | 23        | 0.27%   |
| HP EliteBook 840 G6                        | 22        | 0.26%   |
| Dell XPS 15 9500                           | 21        | 0.25%   |
| Dell XPS 13 9360                           | 21        | 0.25%   |
| HP Pavilion dv6                            | 19        | 0.22%   |
| Dell XPS 13 7390                           | 19        | 0.22%   |
| Dell Latitude E7450                        | 19        | 0.22%   |
| Apple MacBookPro12,1                       | 19        | 0.22%   |
| HP Pavilion Notebook                       | 18        | 0.21%   |
| HP Pavilion 15                             | 17        | 0.2%    |
| HP Laptop 15-da0xxx                        | 17        | 0.2%    |
| Dell XPS 15 9550                           | 17        | 0.2%    |
| Apple MacBookPro8,1                        | 17        | 0.2%    |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 16        | 0.19%   |
| HUAWEI KLVL-WXX9                           | 16        | 0.19%   |
| Dell XPS 13 9300                           | 16        | 0.19%   |
| Dell Latitude E6420                        | 16        | 0.19%   |
| Apple MacBookPro11,3                       | 16        | 0.19%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 15        | 0.18%   |
| HP EliteBook 840 G3                        | 15        | 0.18%   |
| Dell Latitude E7440                        | 15        | 0.18%   |
| Apple MacBookPro14,1                       | 15        | 0.18%   |
| Apple MacBookPro11,1                       | 15        | 0.18%   |
| Acer Nitro AN515-54                        | 15        | 0.18%   |
| HUAWEI NBLK-WAX9X                          | 14        | 0.16%   |
| Dell XPS 13 9380                           | 14        | 0.16%   |
| Dell Latitude 5480                         | 14        | 0.16%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 13        | 0.15%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 13        | 0.15%   |
| HUAWEI HVY-WXX9                            | 13        | 0.15%   |
| Dell XPS 15 9510                           | 13        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1455      | 17.14%  |
| Lenovo IdeaPad     | 499       | 5.88%   |
| Dell Latitude      | 466       | 5.49%   |
| Dell Inspiron      | 407       | 4.8%    |
| Acer Aspire        | 343       | 4.04%   |
| Dell XPS           | 321       | 3.78%   |
| HP Pavilion        | 255       | 3%      |
| HP EliteBook       | 248       | 2.92%   |
| ASUS VivoBook      | 214       | 2.52%   |
| HP Laptop          | 188       | 2.22%   |
| HP ProBook         | 185       | 2.18%   |
| ASUS ROG           | 151       | 1.78%   |
| Dell Precision     | 127       | 1.5%    |
| Lenovo Legion      | 114       | 1.34%   |
| Lenovo ThinkBook   | 92        | 1.08%   |
| Toshiba Satellite  | 88        | 1.04%   |
| ASUS ASUS          | 88        | 1.04%   |
| Acer Nitro         | 80        | 0.94%   |
| Lenovo Yoga        | 79        | 0.93%   |
| ASUS ZenBook       | 79        | 0.93%   |
| Dell Vostro        | 73        | 0.86%   |
| Unknown            | 69        | 0.81%   |
| HP ZBook           | 63        | 0.74%   |
| HP ENVY            | 53        | 0.62%   |
| Acer Swift         | 52        | 0.61%   |
| Framework Laptop   | 50        | 0.59%   |
| Apple MacBookPro11 | 49        | 0.58%   |
| HP OMEN            | 46        | 0.54%   |
| HP Notebook        | 43        | 0.51%   |
| MSI Modern         | 35        | 0.41%   |
| ASUS TUF           | 35        | 0.41%   |
| Fujitsu LIFEBOOK   | 33        | 0.39%   |
| Apple MacBookPro9  | 31        | 0.37%   |
| Acer Predator      | 27        | 0.32%   |
| Dell G5            | 24        | 0.28%   |
| Apple MacBookPro8  | 23        | 0.27%   |
| HP 250             | 22        | 0.26%   |
| Acer TravelMate    | 21        | 0.25%   |
| Razer Blade        | 20        | 0.24%   |
| MSI Prestige       | 19        | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 1106      | 13.03%  |
| 2021    | 1043      | 12.29%  |
| 2019    | 967       | 11.39%  |
| 2018    | 843       | 9.93%   |
| 2017    | 609       | 7.18%   |
| 2022    | 588       | 6.93%   |
| 2012    | 465       | 5.48%   |
| 2015    | 459       | 5.41%   |
| 2013    | 457       | 5.38%   |
| 2016    | 453       | 5.34%   |
| 2014    | 436       | 5.14%   |
| 2011    | 351       | 4.14%   |
| 2023    | 240       | 2.83%   |
| 2010    | 183       | 2.16%   |
| 2008    | 142       | 1.67%   |
| 2009    | 90        | 1.06%   |
| 2007    | 42        | 0.49%   |
| 2006    | 6         | 0.07%   |
| Unknown | 5         | 0.06%   |
| 2024    | 1         | 0.01%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 8487      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 6724      | 77.74%  |
| Enabled  | 1925      | 22.26%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 8415      | 99.15%  |
| Yes  | 72        | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2499      | 29%     |
| 16.01-24.0  | 2021      | 23.45%  |
| 8.01-16.0   | 1722      | 19.98%  |
| 32.01-64.0  | 1015      | 11.78%  |
| 3.01-4.0    | 823       | 9.55%   |
| 24.01-32.0  | 189       | 2.19%   |
| 64.01-256.0 | 152       | 1.76%   |
| 1.01-2.0    | 145       | 1.68%   |
| 2.01-3.0    | 39        | 0.45%   |
| 0.51-1.0    | 11        | 0.13%   |
| Unknown     | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 2687      | 28.2%   |
| 2.01-3.0   | 2612      | 27.42%  |
| 3.01-4.0   | 2178      | 22.86%  |
| 1.01-2.0   | 1170      | 12.28%  |
| 8.01-16.0  | 692       | 7.26%   |
| 0.51-1.0   | 85        | 0.89%   |
| 16.01-24.0 | 72        | 0.76%   |
| 24.01-32.0 | 17        | 0.18%   |
| 32.01-64.0 | 8         | 0.08%   |
| 0.01-0.5   | 4         | 0.04%   |
| Unknown    | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 6320      | 73.22%  |
| 2      | 1986      | 23.01%  |
| 3      | 230       | 2.66%   |
| 4      | 39        | 0.45%   |
| 0      | 39        | 0.45%   |
| 5      | 9         | 0.1%    |
| 6      | 6         | 0.07%   |
| 8      | 1         | 0.01%   |
| 7      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6821      | 80.05%  |
| Yes       | 1700      | 19.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6227      | 72.86%  |
| No        | 2320      | 27.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8336      | 98.15%  |
| No        | 157       | 1.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7210      | 84.01%  |
| No        | 1372      | 15.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1397      | 16.28%  |
| Germany     | 604       | 7.04%   |
| Brazil      | 594       | 6.92%   |
| Russia      | 560       | 6.53%   |
| Italy       | 414       | 4.82%   |
| France      | 342       | 3.99%   |
| India       | 334       | 3.89%   |
| UK          | 313       | 3.65%   |
| Poland      | 258       | 3.01%   |
| Canada      | 246       | 2.87%   |
| Netherlands | 240       | 2.8%    |
| Spain       | 218       | 2.54%   |
| Mexico      | 168       | 1.96%   |
| Turkey      | 139       | 1.62%   |
| Czechia     | 136       | 1.58%   |
| Australia   | 135       | 1.57%   |
| Austria     | 102       | 1.19%   |
| Sweden      | 100       | 1.17%   |
| Switzerland | 96        | 1.12%   |
| Portugal    | 88        | 1.03%   |
| Romania     | 83        | 0.97%   |
| Chile       | 78        | 0.91%   |
| Belgium     | 78        | 0.91%   |
| Argentina   | 77        | 0.9%    |
| Indonesia   | 74        | 0.86%   |
| Hungary     | 72        | 0.84%   |
| Ukraine     | 67        | 0.78%   |
| Norway      | 67        | 0.78%   |
| Finland     | 67        | 0.78%   |
| Colombia    | 64        | 0.75%   |
| Denmark     | 61        | 0.71%   |
| China       | 54        | 0.63%   |
| Bulgaria    | 49        | 0.57%   |
| Iran        | 46        | 0.54%   |
| Belarus     | 45        | 0.52%   |
| Greece      | 42        | 0.49%   |
| Israel      | 41        | 0.48%   |
| Slovakia    | 40        | 0.47%   |
| Japan       | 38        | 0.44%   |
| Philippines | 37        | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 173       | 1.89%   |
| St Petersburg     | 79        | 0.86%   |
| Sao Paulo         | 79        | 0.86%   |
| Berlin            | 74        | 0.81%   |
| Vienna            | 68        | 0.74%   |
| Paris             | 67        | 0.73%   |
| Warsaw            | 60        | 0.66%   |
| Milan             | 59        | 0.64%   |
| Istanbul          | 56        | 0.61%   |
| Amsterdam         | 56        | 0.61%   |
| Prague            | 53        | 0.58%   |
| Madrid            | 49        | 0.54%   |
| Mexico City       | 43        | 0.47%   |
| Helsinki          | 43        | 0.47%   |
| Bengaluru         | 43        | 0.47%   |
| Munich            | 42        | 0.46%   |
| Santiago          | 39        | 0.43%   |
| Sydney            | 38        | 0.42%   |
| Melbourne         | 37        | 0.4%    |
| Budapest          | 36        | 0.39%   |
| Oslo              | 35        | 0.38%   |
| Zurich            | 33        | 0.36%   |
| Hamburg           | 33        | 0.36%   |
| Frankfurt am Main | 33        | 0.36%   |
| Bucharest         | 33        | 0.36%   |
| Lisbon            | 32        | 0.35%   |
| Sofia             | 31        | 0.34%   |
| Jakarta           | 29        | 0.32%   |
| Barcelona         | 29        | 0.32%   |
| Rio de Janeiro    | 28        | 0.31%   |
| Montreal          | 28        | 0.31%   |
| Minsk             | 28        | 0.31%   |
| Delft             | 28        | 0.31%   |
| Brisbane          | 28        | 0.31%   |
| Brasília         | 27        | 0.3%    |
| Tehran            | 26        | 0.28%   |
| Singapore         | 26        | 0.28%   |
| Toronto           | 25        | 0.27%   |
| Rome              | 25        | 0.27%   |
| Los Angeles       | 25        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2225      | 3190   | 20.8%   |
| WDC                         | 958       | 1207   | 8.95%   |
| SanDisk                     | 872       | 1109   | 8.15%   |
| Seagate                     | 730       | 951    | 6.82%   |
| Toshiba                     | 664       | 844    | 6.21%   |
| SK hynix                    | 645       | 791    | 6.03%   |
| Unknown                     | 546       | 712    | 5.1%    |
| Kingston                    | 513       | 625    | 4.79%   |
| Intel                       | 457       | 638    | 4.27%   |
| Micron Technology           | 411       | 523    | 3.84%   |
| Crucial                     | 301       | 394    | 2.81%   |
| HGST                        | 200       | 269    | 1.87%   |
| KIOXIA                      | 178       | 239    | 1.66%   |
| Apple                       | 155       | 216    | 1.45%   |
| A-DATA Technology           | 149       | 173    | 1.39%   |
| Hitachi                     | 96        | 113    | 0.9%    |
| LITEON                      | 84        | 90     | 0.79%   |
| Phison Electronics          | 81        | 90     | 0.76%   |
| China                       | 75        | 90     | 0.7%    |
| Silicon Motion              | 74        | 94     | 0.69%   |
| Micron/Crucial Technology   | 74        | 84     | 0.69%   |
| Phison                      | 66        | 76     | 0.62%   |
| ADATA Technology            | 50        | 56     | 0.47%   |
| Kingston Technology Company | 49        | 57     | 0.46%   |
| PNY                         | 47        | 62     | 0.44%   |
| SPCC                        | 43        | 54     | 0.4%    |
| Transcend                   | 40        | 58     | 0.37%   |
| LITEONIT                    | 38        | 45     | 0.36%   |
| JMicron Technology          | 31        | 39     | 0.29%   |
| Lenovo                      | 28        | 34     | 0.26%   |
| Unknown                     | 28        | 34     | 0.26%   |
| Realtek Semiconductor       | 24        | 29     | 0.22%   |
| Netac                       | 24        | 31     | 0.22%   |
| Corsair                     | 23        | 28     | 0.21%   |
| Patriot                     | 21        | 27     | 0.2%    |
| Union Memory (Shenzhen)     | 20        | 34     | 0.19%   |
| Lexar                       | 20        | 31     | 0.19%   |
| Intenso                     | 20        | 23     | 0.19%   |
| Hewlett-Packard             | 20        | 20     | 0.19%   |
| Gigabyte Technology         | 20        | 28     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 217       | 1.93%   |
| Seagate ST1000LM035-1RK172 1TB                      | 155       | 1.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 152       | 1.36%   |
| Samsung NVMe SSD Drive 512GB                        | 113       | 1.01%   |
| Kingston SA400S37240G 240GB SSD                     | 104       | 0.93%   |
| Unknown MMC Card  32GB                              | 93        | 0.83%   |
| HGST HTS721010A9E630 1TB                            | 87        | 0.78%   |
| Unknown MMC Card  64GB                              | 85        | 0.76%   |
| Toshiba MQ04ABF100 1TB                              | 83        | 0.74%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 83        | 0.74%   |
| SanDisk NVMe SSD Drive 512GB                        | 81        | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 80        | 0.71%   |
| Kingston SA400S37480G 480GB SSD                     | 74        | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 70        | 0.62%   |
| Unknown MMC Card  128GB                             | 66        | 0.59%   |
| Samsung SSD 860 EVO 500GB                           | 66        | 0.59%   |
| Toshiba MQ01ABD100 1TB                              | 63        | 0.56%   |
| Intel SSDPEKNU512GZ 512GB                           | 63        | 0.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 57        | 0.51%   |
| SK hynix NVMe SSD Drive 512GB                       | 51        | 0.45%   |
| Samsung NVMe SSD Drive 1024GB                       | 51        | 0.45%   |
| SanDisk NVMe SSD Drive 256GB                        | 48        | 0.43%   |
| Samsung SSD 850 EVO 250GB                           | 48        | 0.43%   |
| Samsung SSD 850 EVO 500GB                           | 47        | 0.42%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 47        | 0.42%   |
| Intel NVMe SSD Drive 512GB                          | 46        | 0.41%   |
| Seagate ST500LT012-1DG142 500GB                     | 45        | 0.4%    |
| Samsung NVMe SSD Drive 1TB                          | 43        | 0.38%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 41        | 0.37%   |
| Intel SSD 660P Series 1024GB                        | 41        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                         | 41        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                        | 40        | 0.36%   |
| Seagate Expansion 1TB                               | 39        | 0.35%   |
| Samsung SSD 980 1TB                                 | 39        | 0.35%   |
| Toshiba NVMe SSD Drive 512GB                        | 38        | 0.34%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 37        | 0.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 37        | 0.33%   |
| Crucial CT500MX500SSD1 500GB                        | 36        | 0.32%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 35        | 0.31%   |
| Samsung SSD 860 EVO 250GB                           | 34        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 697       | 901    | 35.6%   |
| WDC                 | 516       | 652    | 26.35%  |
| Toshiba             | 324       | 406    | 16.55%  |
| HGST                | 200       | 269    | 10.21%  |
| Hitachi             | 96        | 113    | 4.9%    |
| Unknown             | 25        | 36     | 1.28%   |
| JMicron Technology  | 23        | 30     | 1.17%   |
| Samsung Electronics | 17        | 20     | 0.87%   |
| Fujitsu             | 14        | 14     | 0.72%   |
| Apple               | 14        | 16     | 0.72%   |
| External            | 6         | 9      | 0.31%   |
| TO Exter            | 5         | 5      | 0.26%   |
| HGST HTS            | 3         | 3      | 0.15%   |
| LIO-ORG             | 2         | 12     | 0.1%    |
| LaCie               | 2         | 3      | 0.1%    |
| ASMT                | 2         | 3      | 0.1%    |
| XrayDisk            | 1         | 1      | 0.05%   |
| StoreJet            | 1         | 1      | 0.05%   |
| SSK                 | 1         | 1      | 0.05%   |
| SAGE                | 1         | 1      | 0.05%   |
| QNAP                | 1         | 4      | 0.05%   |
| Phison              | 1         | 2      | 0.05%   |
| Intenso             | 1         | 1      | 0.05%   |
| Inateck             | 1         | 1      | 0.05%   |
| IB-AC703            | 1         | 1      | 0.05%   |
| IB                  | 1         | 2      | 0.05%   |
| Asm                 | 1         | 1      | 0.05%   |
| ACASIS              | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 756       | 1070   | 23.93%  |
| Kingston            | 367       | 441    | 11.62%  |
| SanDisk             | 317       | 425    | 10.03%  |
| Crucial             | 273       | 363    | 8.64%   |
| WDC                 | 167       | 214    | 5.29%   |
| Intel               | 107       | 166    | 3.39%   |
| Micron Technology   | 104       | 125    | 3.29%   |
| Apple               | 102       | 117    | 3.23%   |
| A-DATA Technology   | 98        | 113    | 3.1%    |
| SK hynix            | 84        | 101    | 2.66%   |
| China               | 74        | 89     | 2.34%   |
| LITEON              | 69        | 75     | 2.18%   |
| Toshiba             | 68        | 85     | 2.15%   |
| PNY                 | 45        | 59     | 1.42%   |
| LITEONIT            | 38        | 45     | 1.2%    |
| SPCC                | 36        | 47     | 1.14%   |
| Transcend           | 34        | 48     | 1.08%   |
| Patriot             | 19        | 24     | 0.6%    |
| Netac               | 18        | 23     | 0.57%   |
| OCZ                 | 17        | 20     | 0.54%   |
| KingSpec            | 17        | 20     | 0.54%   |
| Gigabyte Technology | 17        | 24     | 0.54%   |
| Lexar               | 16        | 26     | 0.51%   |
| Intenso             | 16        | 18     | 0.51%   |
| GOODRAM             | 16        | 25     | 0.51%   |
| SABRENT             | 15        | 15     | 0.47%   |
| Corsair             | 15        | 17     | 0.47%   |
| Team                | 13        | 16     | 0.41%   |
| Hewlett-Packard     | 12        | 12     | 0.38%   |
| Apacer              | 12        | 15     | 0.38%   |
| Seagate             | 11        | 12     | 0.35%   |
| Plextor             | 8         | 15     | 0.25%   |
| Unknown             | 6         | 6      | 0.19%   |
| Unknown             | 6         | 7      | 0.19%   |
| Teclast             | 5         | 6      | 0.16%   |
| Ramsta              | 5         | 6      | 0.16%   |
| Mushkin             | 5         | 14     | 0.16%   |
| KingDian            | 5         | 5      | 0.16%   |
| FORESEE             | 5         | 7      | 0.16%   |
| MidasForce          | 4         | 4      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 4609      | 6503   | 45.74%  |
| SSD     | 2933      | 4105   | 29.11%  |
| HDD     | 1884      | 2509   | 18.7%   |
| MMC     | 508       | 670    | 5.04%   |
| Unknown | 142       | 162    | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 4607      | 6487   | 47.54%  |
| SATA | 4210      | 6308   | 43.44%  |
| MMC  | 508       | 670    | 5.24%   |
| SAS  | 366       | 484    | 3.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3010      | 4206   | 62.89%  |
| 0.51-1.0   | 1592      | 2142   | 33.26%  |
| 1.01-2.0   | 153       | 231    | 3.2%    |
| 4.01-10.0  | 16        | 17     | 0.33%   |
| 3.01-4.0   | 13        | 15     | 0.27%   |
| 2.01-3.0   | 1         | 1      | 0.02%   |
| 0          | 1         | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 1948      | 21.86%  |
| 251-500        | 1940      | 21.77%  |
| 101-250        | 1501      | 16.84%  |
| 1001-2000      | 1032      | 11.58%  |
| 1-20           | 933       | 10.47%  |
| Unknown        | 674       | 7.56%   |
| 51-100         | 340       | 3.82%   |
| More than 3000 | 191       | 2.14%   |
| 21-50          | 180       | 2.02%   |
| 2001-3000      | 172       | 1.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2879      | 30.83%  |
| 21-50          | 1629      | 17.44%  |
| 101-250        | 1408      | 15.08%  |
| 51-100         | 1173      | 12.56%  |
| 251-500        | 862       | 9.23%   |
| Unknown        | 674       | 7.22%   |
| 501-1000       | 490       | 5.25%   |
| 1001-2000      | 170       | 1.82%   |
| More than 3000 | 28        | 0.3%    |
| 2001-3000      | 25        | 0.27%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                | 13        | 13     | 3.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 19     | 2.6%    |
| HGST HTS721010A9E630 1TB                       | 9         | 11     | 2.6%    |
| Seagate ST9500325AS 500GB                      | 7         | 9      | 2.02%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 2.02%   |
| HGST HTS541010A9E680 1TB                       | 7         | 7      | 2.02%   |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 1.73%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 6         | 6      | 1.73%   |
| HGST HTS545050A7E680 500GB                     | 6         | 6      | 1.73%   |
| Hitachi HTS547575A9E384 752GB                  | 5         | 7      | 1.45%   |
| Toshiba MQ01ABF050 500GB                       | 4         | 5      | 1.16%   |
| Toshiba MQ01ABD075 752GB                       | 4         | 4      | 1.16%   |
| Hitachi HTS545050B9A300 500GB                  | 4         | 4      | 1.16%   |
| HGST HTS725050A7E630 500GB                     | 4         | 4      | 1.16%   |
| SK hynix SC308 SATA 128GB SSD                  | 3         | 3      | 0.87%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 3         | 3      | 0.87%   |
| Seagate ST9500420AS 500GB                      | 3         | 4      | 0.87%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 0.87%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 4      | 0.87%   |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 3         | 3      | 0.87%   |
| Seagate ST1000LM049-2GH172 1TB                 | 3         | 4      | 0.87%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 3         | 3      | 0.87%   |
| Samsung Electronics SSD 980 1TB                | 3         | 3      | 0.87%   |
| Samsung Electronics SSD 870 EVO 500GB          | 3         | 6      | 0.87%   |
| Crucial CT1000P1SSD8 1TB                       | 3         | 3      | 0.87%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 2         | 2      | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 2         | 2      | 0.58%   |
| WDC WD3200BPVT-75ZEST0 320GB                   | 2         | 2      | 0.58%   |
| WDC WD10SPZX-24Z10 1TB                         | 2         | 2      | 0.58%   |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 0.58%   |
| Toshiba MQ01ABD050V 500GB                      | 2         | 2      | 0.58%   |
| Toshiba MK5061GSY 500GB                        | 2         | 2      | 0.58%   |
| Toshiba MK3275GSX 320GB                        | 2         | 3      | 0.58%   |
| SPCC Solid State Disk 256GB                    | 2         | 2      | 0.58%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.58%   |
| Seagate ST9750420AS 752GB                      | 2         | 2      | 0.58%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 0.58%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.58%   |
| Seagate ST500LM000-SSHD-8GB                    | 2         | 3      | 0.58%   |
| Seagate ST500LM000-1EJ162 500GB                | 2         | 2      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 90     | 21.16%  |
| WDC                 | 36        | 39     | 10.43%  |
| Toshiba             | 36        | 38     | 10.43%  |
| HGST                | 30        | 32     | 8.7%    |
| Samsung Electronics | 27        | 32     | 7.83%   |
| Hitachi             | 22        | 26     | 6.38%   |
| Micron Technology   | 17        | 20     | 4.93%   |
| SK hynix            | 15        | 16     | 4.35%   |
| Intel               | 15        | 26     | 4.35%   |
| Crucial             | 15        | 23     | 4.35%   |
| SanDisk             | 14        | 16     | 4.06%   |
| Kingston            | 9         | 11     | 2.61%   |
| A-DATA Technology   | 5         | 5      | 1.45%   |
| LITEONIT            | 4         | 5      | 1.16%   |
| LITEON              | 4         | 4      | 1.16%   |
| Fujitsu             | 3         | 3      | 0.87%   |
| SPCC                | 2         | 2      | 0.58%   |
| China               | 2         | 2      | 0.58%   |
| YS                  | 1         | 1      | 0.29%   |
| Wibtek              | 1         | 1      | 0.29%   |
| walram              | 1         | 1      | 0.29%   |
| Union Memory        | 1         | 1      | 0.29%   |
| Teclast             | 1         | 1      | 0.29%   |
| SSSTC               | 1         | 1      | 0.29%   |
| SSD                 | 1         | 1      | 0.29%   |
| PNY                 | 1         | 1      | 0.29%   |
| Plextor             | 1         | 1      | 0.29%   |
| Origin              | 1         | 1      | 0.29%   |
| OCZ-VERTEX3         | 1         | 1      | 0.29%   |
| Netac               | 1         | 1      | 0.29%   |
| Lenovo              | 1         | 2      | 0.29%   |
| HGST HTS            | 1         | 1      | 0.29%   |
| Apple               | 1         | 1      | 0.29%   |
| Unknown             | 1         | 1      | 0.29%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 90     | 36.68%  |
| Toshiba             | 35        | 37     | 17.59%  |
| WDC                 | 30        | 33     | 15.08%  |
| HGST                | 30        | 32     | 15.08%  |
| Hitachi             | 22        | 26     | 11.06%  |
| Samsung Electronics | 4         | 4      | 2.01%   |
| Fujitsu             | 3         | 3      | 1.51%   |
| HGST HTS            | 1         | 1      | 0.5%    |
| Apple               | 1         | 1      | 0.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 197       | 227    | 57.6%   |
| SSD  | 119       | 151    | 34.8%   |
| NVMe | 26        | 29     | 7.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 14.29%  |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1         | 1      | 14.29%  |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 14.29%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 42.86%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5047      | 8252   | 55.68%  |
| Works    | 3678      | 5283   | 40.57%  |
| Malfunc  | 333       | 407    | 3.67%   |
| Failed   | 7         | 7      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 5067      | 47.61%  |
| Samsung Electronics                     | 1571      | 14.76%  |
| AMD                                     | 864       | 8.12%   |
| SanDisk                                 | 807       | 7.58%   |
| SK hynix                                | 547       | 5.14%   |
| Micron Technology                       | 309       | 2.9%    |
| Toshiba America Info Systems            | 278       | 2.61%   |
| Kingston Technology Company             | 195       | 1.83%   |
| KIOXIA                                  | 179       | 1.68%   |
| Phison Electronics                      | 157       | 1.48%   |
| ADATA Technology                        | 109       | 1.02%   |
| Micron/Crucial Technology               | 98        | 0.92%   |
| Silicon Motion                          | 92        | 0.86%   |
| Union Memory (Shenzhen)                 | 48        | 0.45%   |
| Solid State Storage Technology          | 40        | 0.38%   |
| Nvidia                                  | 36        | 0.34%   |
| Apple                                   | 36        | 0.34%   |
| Realtek Semiconductor                   | 31        | 0.29%   |
| Lite-On Technology                      | 29        | 0.27%   |
| Lenovo                                  | 26        | 0.24%   |
| MAXIO Technology (Hangzhou)             | 21        | 0.2%    |
| Marvell Technology Group                | 15        | 0.14%   |
| Yangtze Memory Technologies             | 13        | 0.12%   |
| Shenzhen Longsys Electronics            | 13        | 0.12%   |
| Seagate Technology                      | 13        | 0.12%   |
| Solidigm                                | 10        | 0.09%   |
| Netac Technology                        | 6         | 0.06%   |
| Biwin Storage Technology                | 6         | 0.06%   |
| JMicron Technology                      | 5         | 0.05%   |
| Shenzhen Unionmemory Information System | 4         | 0.04%   |
| INNOGRIT                                | 4         | 0.04%   |
| ASMedia Technology                      | 3         | 0.03%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.02%   |
| ULi Electronics                         | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| Lite-On IT Corp. / Plextor              | 1         | 0.01%   |
| Hosin Global Electronics                | 1         | 0.01%   |
| Enmotus                                 | 1         | 0.01%   |
| Beijing Starblaze Technology            | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 822       | 7.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 774       | 6.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 707       | 6.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 493       | 4.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 473       | 4.24%   |
| Intel Volume Management Device NVMe RAID Controller                            | 415       | 3.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 363       | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 293       | 2.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 283       | 2.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 258       | 2.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 249       | 2.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 239       | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 215       | 1.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 211       | 1.89%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 197       | 1.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 187       | 1.68%   |
| Intel Tiger Lake-LP SATA Controller                                            | 161       | 1.44%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 159       | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                          | 139       | 1.25%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 133       | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 128       | 1.15%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 124       | 1.11%   |
| Intel SSD 660P Series                                                          | 116       | 1.04%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 113       | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 109       | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 94        | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 93        | 0.83%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 90        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 84        | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 84        | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 79        | 0.71%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 78        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 76        | 0.68%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 75        | 0.67%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 72        | 0.65%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 71        | 0.64%   |
| SK hynix BC511 NVMe SSD                                                        | 67        | 0.6%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 59        | 0.53%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 59        | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 58        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4981      | 46.54%  |
| NVMe | 4608      | 43.05%  |
| RAID | 963       | 9%      |
| IDE  | 151       | 1.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 6753      | 79.57%  |
| AMD          | 1727      | 20.35%  |
| ARM          | 4         | 0.05%   |
| Unknown      | 2         | 0.02%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 210       | 2.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 174       | 2.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 170       | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 165       | 1.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 133       | 1.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 129       | 1.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 126       | 1.48%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 126       | 1.48%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 123       | 1.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 123       | 1.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 113       | 1.33%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 110       | 1.3%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 108       | 1.27%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 108       | 1.27%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 107       | 1.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 107       | 1.26%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 94        | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 91        | 1.07%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 85        | 1%      |
| Intel Core i5-5200U CPU @ 2.20GHz             | 83        | 0.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 81        | 0.95%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 79        | 0.93%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 78        | 0.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 75        | 0.88%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 70        | 0.82%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 66        | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 64        | 0.75%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 60        | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 59        | 0.69%   |
| Intel 12th Gen Core i7-12700H                 | 57        | 0.67%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 55        | 0.65%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 55        | 0.65%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 54        | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 54        | 0.64%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 54        | 0.64%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 53        | 0.62%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 52        | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 49        | 0.58%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 49        | 0.58%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 49        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 2282      | 26.88%  |
| Intel Core i5                  | 2058      | 24.24%  |
| Other                          | 1190      | 14.02%  |
| AMD Ryzen 7                    | 543       | 6.4%    |
| AMD Ryzen 5                    | 531       | 6.25%   |
| Intel Core i3                  | 485       | 5.71%   |
| Intel Celeron                  | 216       | 2.54%   |
| Intel Core 2 Duo               | 143       | 1.68%   |
| AMD Ryzen 7 PRO                | 127       | 1.5%    |
| AMD Ryzen 9                    | 124       | 1.46%   |
| Intel Atom                     | 119       | 1.4%    |
| Intel Pentium                  | 94        | 1.11%   |
| AMD Ryzen 3                    | 79        | 0.93%   |
| Intel Core i9                  | 65        | 0.77%   |
| AMD Ryzen 5 PRO                | 58        | 0.68%   |
| AMD A6                         | 48        | 0.57%   |
| AMD A10                        | 39        | 0.46%   |
| AMD A8                         | 35        | 0.41%   |
| Intel Pentium Silver           | 31        | 0.37%   |
| AMD A4                         | 25        | 0.29%   |
| Intel Xeon                     | 19        | 0.22%   |
| Intel Pentium Dual-Core        | 17        | 0.2%    |
| AMD E1                         | 15        | 0.18%   |
| AMD Athlon                     | 13        | 0.15%   |
| Intel Pentium Dual             | 12        | 0.14%   |
| Intel Core m3                  | 12        | 0.14%   |
| AMD A12                        | 12        | 0.14%   |
| Intel Core m5                  | 11        | 0.13%   |
| AMD E                          | 9         | 0.11%   |
| Intel Genuine                  | 8         | 0.09%   |
| AMD E2                         | 8         | 0.09%   |
| Intel Core M                   | 7         | 0.08%   |
| Intel Core m7                  | 5         | 0.06%   |
| AMD Athlon II                  | 5         | 0.06%   |
| Intel Core 2                   | 4         | 0.05%   |
| Intel Celeron Dual-Core        | 4         | 0.05%   |
| AMD PRO A10                    | 4         | 0.05%   |
| AMD Phenom II                  | 4         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.04%   |
| AMD Ryzen 3 PRO                | 3         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 3264      | 38.45%  |
| 2       | 3011      | 35.47%  |
| 8       | 913       | 10.75%  |
| 6       | 835       | 9.84%   |
| 12      | 145       | 1.71%   |
| 14      | 140       | 1.65%   |
| 10      | 129       | 1.52%   |
| 1       | 26        | 0.31%   |
| 24      | 11        | 0.13%   |
| 16      | 10        | 0.12%   |
| 20      | 2         | 0.02%   |
| 3       | 2         | 0.02%   |
| 5       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 8486      | 99.98%  |
| 2       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 7469      | 87.87%  |
| 1       | 1030      | 12.12%  |
| Unknown | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8349      | 98.13%  |
| Unknown        | 151       | 1.77%   |
| 64-bit         | 4         | 0.05%   |
| 32-bit         | 4         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2522      | 28.71%  |
| 0x806ec    | 399       | 4.54%   |
| 0x806ea    | 383       | 4.36%   |
| 0x306a9    | 357       | 4.06%   |
| 0x806c1    | 350       | 3.98%   |
| 0x206a7    | 279       | 3.18%   |
| 0x906ea    | 273       | 3.11%   |
| 0x406e3    | 272       | 3.1%    |
| 0x806e9    | 269       | 3.06%   |
| 0x0a50000c | 244       | 2.78%   |
| 0x40651    | 221       | 2.52%   |
| 0x306d4    | 216       | 2.46%   |
| 0x306c3    | 169       | 1.92%   |
| 0x08600106 | 167       | 1.9%    |
| 0xa0652    | 166       | 1.89%   |
| 0x08108109 | 144       | 1.64%   |
| 0x08608103 | 129       | 1.47%   |
| 0x08108102 | 127       | 1.45%   |
| 0x906e9    | 119       | 1.35%   |
| 0x506e3    | 112       | 1.27%   |
| 0x706e5    | 104       | 1.18%   |
| 0x0a404102 | 93        | 1.06%   |
| 0x906a3    | 88        | 1%      |
| 0x08600104 | 88        | 1%      |
| 0x20655    | 81        | 0.92%   |
| 0x806eb    | 75        | 0.85%   |
| 0x30678    | 75        | 0.85%   |
| 0x0a50000d | 75        | 0.85%   |
| 0x1067a    | 70        | 0.8%    |
| 0x806d1    | 61        | 0.69%   |
| 0x906ed    | 56        | 0.64%   |
| 0x08600103 | 56        | 0.64%   |
| 0x0810100b | 44        | 0.5%    |
| 0x406c4    | 42        | 0.48%   |
| 0x08608102 | 42        | 0.48%   |
| 0x0a404101 | 41        | 0.47%   |
| 0x06006705 | 37        | 0.42%   |
| 0x706a8    | 34        | 0.39%   |
| 0x406c3    | 31        | 0.35%   |
| 0x906a4    | 29        | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 2130      | 25.06%  |
| TigerLake         | 595       | 7%      |
| Haswell           | 574       | 6.75%   |
| Skylake           | 535       | 6.29%   |
| IvyBridge         | 490       | 5.76%   |
| Alderlake Hybrid  | 440       | 5.18%   |
| Unknown           | 440       | 5.18%   |
| SandyBridge       | 388       | 4.56%   |
| Zen 2             | 365       | 4.29%   |
| Zen 3             | 355       | 4.18%   |
| Broadwell         | 298       | 3.51%   |
| Zen+              | 279       | 3.28%   |
| CometLake         | 260       | 3.06%   |
| IceLake           | 257       | 3.02%   |
| Silvermont        | 215       | 2.53%   |
| Westmere          | 166       | 1.95%   |
| Penryn            | 141       | 1.66%   |
| Goldmont plus     | 98        | 1.15%   |
| Zen               | 88        | 1.04%   |
| Excavator         | 82        | 0.96%   |
| Core              | 46        | 0.54%   |
| Goldmont          | 44        | 0.52%   |
| Puma              | 38        | 0.45%   |
| Piledriver        | 37        | 0.44%   |
| Jaguar            | 25        | 0.29%   |
| Nehalem           | 23        | 0.27%   |
| Bobcat            | 17        | 0.2%    |
| Tremont           | 16        | 0.19%   |
| K10               | 14        | 0.16%   |
| K10 Llano         | 10        | 0.12%   |
| Steamroller       | 9         | 0.11%   |
| K8 & K10 hybrid   | 6         | 0.07%   |
| Bonnell           | 6         | 0.07%   |
| K8 Hammer         | 5         | 0.06%   |
| P6                | 3         | 0.04%   |
| Gracemont         | 3         | 0.04%   |
| Meteorlake Hybrid | 2         | 0.02%   |
| NetBurst          | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6378      | 57.35%  |
| Nvidia                           | 2640      | 23.74%  |
| AMD                              | 2101      | 18.89%  |
| Zhaoxin                          | 1         | 0.01%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 544       | 4.8%    |
| Intel UHD Graphics 620                                                                   | 503       | 4.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 456       | 4.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 365       | 3.22%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 356       | 3.14%   |
| Intel HD Graphics 620                                                                    | 351       | 3.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 347       | 3.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 346       | 3.05%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 332       | 2.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 299       | 2.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 288       | 2.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 282       | 2.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 266       | 2.35%   |
| Intel HD Graphics 5500                                                                   | 251       | 2.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 220       | 1.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 216       | 1.91%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 194       | 1.71%   |
| AMD Lucienne                                                                             | 187       | 1.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 184       | 1.62%   |
| Intel HD Graphics 630                                                                    | 142       | 1.25%   |
| AMD Rembrandt [Radeon 680M]                                                              | 140       | 1.24%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 133       | 1.17%   |
| Intel HD Graphics 530                                                                    | 126       | 1.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 126       | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 120       | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 105       | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 102       | 0.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 99        | 0.87%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 97        | 0.86%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 97        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 95        | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 84        | 0.74%   |
| Nvidia GP108M [GeForce MX150]                                                            | 81        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 79        | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 78        | 0.69%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 74        | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 74        | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 71        | 0.63%   |
| AMD Barcelo                                                                              | 70        | 0.62%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 67        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 4048      | 47.48%  |
| Intel + Nvidia     | 2007      | 23.54%  |
| 1 x AMD            | 1343      | 15.75%  |
| 1 x Nvidia         | 326       | 3.82%   |
| AMD + Nvidia       | 312       | 3.66%   |
| Intel + AMD        | 304       | 3.57%   |
| 2 x AMD            | 146       | 1.71%   |
| 2 x Intel          | 19        | 0.22%   |
| Other              | 12        | 0.14%   |
| 2 x Nvidia         | 4         | 0.05%   |
| Intel + 2 x Nvidia | 2         | 0.02%   |
| 1 x Zhaoxin        | 1         | 0.01%   |
| 1 x SiS            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 7296      | 84.89%  |
| Proprietary | 1160      | 13.5%   |
| Unknown     | 139       | 1.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5281      | 60.93%  |
| 1.01-2.0   | 1067      | 12.31%  |
| 0.01-0.5   | 961       | 11.09%  |
| 3.01-4.0   | 581       | 6.7%    |
| 0.51-1.0   | 471       | 5.43%   |
| 5.01-6.0   | 129       | 1.49%   |
| 7.01-8.0   | 115       | 1.33%   |
| 8.01-16.0  | 34        | 0.39%   |
| 2.01-3.0   | 28        | 0.32%   |
| 16.01-24.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1762      | 16.98%  |
| BOE                     | 1619      | 15.6%   |
| Chimei Innolux          | 1417      | 13.66%  |
| LG Display              | 1270      | 12.24%  |
| Samsung Electronics     | 846       | 8.15%   |
| Dell                    | 460       | 4.43%   |
| Sharp                   | 409       | 3.94%   |
| Goldstar                | 314       | 3.03%   |
| Apple                   | 265       | 2.55%   |
| Lenovo                  | 209       | 2.01%   |
| PANDA                   | 188       | 1.81%   |
| Hewlett-Packard         | 168       | 1.62%   |
| CSO                     | 135       | 1.3%    |
| Chi Mei Optoelectronics | 111       | 1.07%   |
| AOC                     | 107       | 1.03%   |
| Philips                 | 103       | 0.99%   |
| Acer                    | 101       | 0.97%   |
| InfoVision              | 98        | 0.94%   |
| BenQ                    | 97        | 0.93%   |
| Ancor Communications    | 69        | 0.66%   |
| Iiyama                  | 49        | 0.47%   |
| TMX                     | 48        | 0.46%   |
| ASUSTek Computer        | 45        | 0.43%   |
| ViewSonic               | 40        | 0.39%   |
| Sony                    | 29        | 0.28%   |
| Panasonic               | 25        | 0.24%   |
| MSI                     | 21        | 0.2%    |
| JDI                     | 21        | 0.2%    |
| Toshiba                 | 20        | 0.19%   |
| LG Philips              | 20        | 0.19%   |
| Gigabyte Technology     | 16        | 0.15%   |
| Sceptre Tech            | 12        | 0.12%   |
| NEC Computers           | 11        | 0.11%   |
| HKC                     | 11        | 0.11%   |
| Eizo                    | 11        | 0.11%   |
| CPT                     | 11        | 0.11%   |
| Vizio                   | 9         | 0.09%   |
| HannStar                | 9         | 0.09%   |
| Fujitsu Siemens         | 9         | 0.09%   |
| CTO                     | 8         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 83        | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 69        | 0.65%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 66        | 0.63%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 63        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 62        | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 55        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 50        | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 48        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 47        | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 47        | 0.45%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 45        | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 42        | 0.4%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 41        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 40        | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 38        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 35        | 0.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 34        | 0.32%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 34        | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 32        | 0.3%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 31        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 30        | 0.28%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 30        | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 29        | 0.28%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 29        | 0.28%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 29        | 0.28%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 28        | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 27        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 27        | 0.26%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 26        | 0.25%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 26        | 0.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 26        | 0.25%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 26        | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 26        | 0.25%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 26        | 0.25%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 25        | 0.24%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 25        | 0.24%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 25        | 0.24%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 25        | 0.24%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 24        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 24        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4751      | 49.72%  |
| 1366x768 (WXGA)    | 1808      | 18.92%  |
| 3840x2160 (4K)     | 549       | 5.75%   |
| 2560x1440 (QHD)    | 410       | 4.29%   |
| 1920x1200 (WUXGA)  | 330       | 3.45%   |
| 1600x900 (HD+)     | 309       | 3.23%   |
| 2560x1600          | 233       | 2.44%   |
| 2880x1800          | 156       | 1.63%   |
| 1280x800 (WXGA)    | 153       | 1.6%    |
| 1440x900 (WXGA+)   | 99        | 1.04%   |
| 2560x1080          | 92        | 0.96%   |
| 3440x1440          | 84        | 0.88%   |
| 3840x2400          | 74        | 0.77%   |
| 2160x1440          | 62        | 0.65%   |
| 2256x1504          | 55        | 0.58%   |
| 1680x1050 (WSXGA+) | 52        | 0.54%   |
| 1280x1024 (SXGA)   | 42        | 0.44%   |
| 3200x1800 (QHD+)   | 40        | 0.42%   |
| 3200x2000          | 24        | 0.25%   |
| 3000x2000          | 21        | 0.22%   |
| 1360x768           | 21        | 0.22%   |
| 2520x1680          | 17        | 0.18%   |
| 3456x2160          | 16        | 0.17%   |
| 3072x1920          | 15        | 0.16%   |
| 2240x1400          | 15        | 0.16%   |
| 1920x1280          | 14        | 0.15%   |
| 2880x1620          | 13        | 0.14%   |
| 3840x1600          | 11        | 0.12%   |
| 2160x1350          | 10        | 0.1%    |
| 3840x1080          | 9         | 0.09%   |
| 1920x540           | 7         | 0.07%   |
| 1024x768 (XGA)     | 7         | 0.07%   |
| 3840x1100          | 6         | 0.06%   |
| 1024x600           | 5         | 0.05%   |
| 3120x2080          | 4         | 0.04%   |
| 2304x1440          | 4         | 0.04%   |
| Unknown            | 4         | 0.04%   |
| 800x1280           | 3         | 0.03%   |
| 2288x1287          | 3         | 0.03%   |
| 1680x945           | 3         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3813      | 36.74%  |
| 13      | 1665      | 16.04%  |
| 14      | 1501      | 14.46%  |
| 17      | 491       | 4.73%   |
| 27      | 483       | 4.65%   |
| 24      | 448       | 4.32%   |
| 23      | 306       | 2.95%   |
| 12      | 259       | 2.5%    |
| 16      | 247       | 2.38%   |
| 21      | 242       | 2.33%   |
| 34      | 152       | 1.46%   |
| 31      | 117       | 1.13%   |
| 11      | 92        | 0.89%   |
| 18      | 82        | 0.79%   |
| 19      | 52        | 0.5%    |
| 20      | 44        | 0.42%   |
| 22      | 34        | 0.33%   |
| 40      | 30        | 0.29%   |
| Unknown | 30        | 0.29%   |
| 25      | 28        | 0.27%   |
| 84      | 27        | 0.26%   |
| 32      | 22        | 0.21%   |
| 26      | 20        | 0.19%   |
| 28      | 19        | 0.18%   |
| 54      | 17        | 0.16%   |
| 72      | 16        | 0.15%   |
| 10      | 16        | 0.15%   |
| 29      | 15        | 0.14%   |
| 35      | 14        | 0.13%   |
| 37      | 11        | 0.11%   |
| 48      | 8         | 0.08%   |
| 86      | 6         | 0.06%   |
| 39      | 6         | 0.06%   |
| 52      | 5         | 0.05%   |
| 42      | 5         | 0.05%   |
| 33      | 5         | 0.05%   |
| 74      | 4         | 0.04%   |
| 57      | 4         | 0.04%   |
| 49      | 4         | 0.04%   |
| 46      | 4         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 6275      | 61.15%  |
| 201-300        | 1194      | 11.64%  |
| 501-600        | 1148      | 11.19%  |
| 351-400        | 612       | 5.96%   |
| 401-500        | 426       | 4.15%   |
| 601-700        | 202       | 1.97%   |
| 701-800        | 183       | 1.78%   |
| 801-900        | 64        | 0.62%   |
| 1001-1500      | 60        | 0.58%   |
| 1501-2000      | 51        | 0.5%    |
| Unknown        | 30        | 0.29%   |
| 901-1000       | 9         | 0.09%   |
| 101-200        | 3         | 0.03%   |
| 1-100          | 3         | 0.03%   |
| More than 2000 | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 7126      | 80.76%  |
| 16/10   | 1203      | 13.63%  |
| 3/2     | 191       | 2.16%   |
| 21/9    | 187       | 2.12%   |
| 5/4     | 44        | 0.5%    |
| 4/3     | 20        | 0.23%   |
| 32/9    | 14        | 0.16%   |
| Unknown | 13        | 0.15%   |
| 0.56    | 7         | 0.08%   |
| 3.40    | 6         | 0.07%   |
| 0.67    | 3         | 0.03%   |
| 6/5     | 2         | 0.02%   |
| 1.00    | 2         | 0.02%   |
| 0.62    | 2         | 0.02%   |
| 3.88    | 1         | 0.01%   |
| 3.73    | 1         | 0.01%   |
| 3.33    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3820      | 36.9%   |
| 81-90          | 2536      | 24.5%   |
| 201-250        | 814       | 7.86%   |
| 71-80          | 598       | 5.78%   |
| 301-350        | 502       | 4.85%   |
| 121-130        | 445       | 4.3%    |
| 351-500        | 330       | 3.19%   |
| 61-70          | 246       | 2.38%   |
| 111-120        | 229       | 2.21%   |
| 251-300        | 176       | 1.7%    |
| 151-200        | 155       | 1.5%    |
| 51-60          | 98        | 0.95%   |
| More than 1000 | 97        | 0.94%   |
| 141-150        | 89        | 0.86%   |
| 501-1000       | 79        | 0.76%   |
| 131-140        | 42        | 0.41%   |
| 91-100         | 42        | 0.41%   |
| Unknown        | 30        | 0.29%   |
| 41-50          | 16        | 0.15%   |
| 1-40           | 7         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 4534      | 44.82%  |
| 101-120       | 2206      | 21.81%  |
| 51-100        | 1529      | 15.12%  |
| 161-240       | 1188      | 11.74%  |
| More than 240 | 552       | 5.46%   |
| 1-50          | 76        | 0.75%   |
| Unknown       | 30        | 0.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6483      | 73.75%  |
| 2     | 1841      | 20.94%  |
| 3     | 242       | 2.75%   |
| 0     | 205       | 2.33%   |
| 4     | 17        | 0.19%   |
| 5     | 3         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 5072      | 39.39%  |
| Realtek Semiconductor             | 4233      | 32.88%  |
| Qualcomm Atheros                  | 1312      | 10.19%  |
| Broadcom                          | 612       | 4.75%   |
| MediaTek                          | 379       | 2.94%   |
| Broadcom Limited                  | 141       | 1.1%    |
| Lenovo                            | 112       | 0.87%   |
| ASIX Electronics                  | 104       | 0.81%   |
| TP-Link                           | 83        | 0.64%   |
| Qualcomm                          | 81        | 0.63%   |
| Sierra Wireless                   | 74        | 0.57%   |
| Dell                              | 56        | 0.43%   |
| DisplayLink                       | 52        | 0.4%    |
| Ralink                            | 49        | 0.38%   |
| Samsung Electronics               | 48        | 0.37%   |
| Ralink Technology                 | 46        | 0.36%   |
| Marvell Technology Group          | 45        | 0.35%   |
| Xiaomi                            | 38        | 0.3%    |
| Hewlett-Packard                   | 33        | 0.26%   |
| Ericsson Business Mobile Networks | 32        | 0.25%   |
| Nvidia                            | 27        | 0.21%   |
| Huawei Technologies               | 22        | 0.17%   |
| Google                            | 22        | 0.17%   |
| ASUSTek Computer                  | 18        | 0.14%   |
| Apple                             | 16        | 0.12%   |
| Fibocom                           | 14        | 0.11%   |
| OPPO Electronics                  | 12        | 0.09%   |
| JMicron Technology                | 12        | 0.09%   |
| NetGear                           | 11        | 0.09%   |
| D-Link                            | 10        | 0.08%   |
| Qualcomm Atheros Communications   | 9         | 0.07%   |
| Edimax Technology                 | 7         | 0.05%   |
| D-Link System                     | 7         | 0.05%   |
| T & A Mobile Phones               | 6         | 0.05%   |
| Motorola PCS                      | 6         | 0.05%   |
| Microsoft                         | 6         | 0.05%   |
| Linksys                           | 6         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.04%   |
| Cypress Semiconductor             | 4         | 0.03%   |
| Belkin Components                 | 4         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2596      | 16.62%  |
| Intel Wi-Fi 6 AX200                                                    | 560       | 3.58%   |
| Intel Wireless 8265 / 8275                                             | 523       | 3.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 518       | 3.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 489       | 3.13%   |
| Intel Wi-Fi 6 AX201                                                    | 453       | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 316       | 2.02%   |
| Intel Wireless 8260                                                    | 282       | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 281       | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 280       | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 276       | 1.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 271       | 1.73%   |
| Intel Wireless 7260                                                    | 264       | 1.69%   |
| Intel Wireless 7265                                                    | 260       | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 242       | 1.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 225       | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 223       | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 216       | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 207       | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 203       | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                                  | 201       | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 196       | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 167       | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 155       | 0.99%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 151       | 0.97%   |
| Intel Wireless 3165                                                    | 136       | 0.87%   |
| Intel Ethernet Connection I219-LM                                      | 127       | 0.81%   |
| Intel Ethernet Connection (4) I219-V                                   | 117       | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 105       | 0.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 105       | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 102       | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 102       | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                          | 102       | 0.65%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 101       | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                          | 95        | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 92        | 0.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 91        | 0.58%   |
| Intel Ethernet Connection I218-LM                                      | 91        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                                  | 90        | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 86        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4936      | 56.44%  |
| Realtek Semiconductor                 | 1212      | 13.86%  |
| Qualcomm Atheros                      | 1144      | 13.08%  |
| Broadcom                              | 514       | 5.88%   |
| MediaTek                              | 371       | 4.24%   |
| Broadcom Limited                      | 114       | 1.3%    |
| Sierra Wireless                       | 74        | 0.85%   |
| Qualcomm                              | 66        | 0.75%   |
| TP-Link                               | 63        | 0.72%   |
| Ralink                                | 49        | 0.56%   |
| Ralink Technology                     | 46        | 0.53%   |
| Dell                                  | 42        | 0.48%   |
| ASUSTek Computer                      | 17        | 0.19%   |
| Fibocom                               | 14        | 0.16%   |
| NetGear                               | 10        | 0.11%   |
| Hewlett-Packard                       | 10        | 0.11%   |
| Qualcomm Atheros Communications       | 9         | 0.1%    |
| Ericsson Business Mobile Networks     | 9         | 0.1%    |
| Edimax Technology                     | 7         | 0.08%   |
| D-Link System                         | 7         | 0.08%   |
| D-Link                                | 7         | 0.08%   |
| Linksys                               | 5         | 0.06%   |
| Microsoft                             | 4         | 0.05%   |
| Belkin Components                     | 4         | 0.05%   |
| Quectel Wireless Solutions            | 2         | 0.02%   |
| Unknown                               | 2         | 0.02%   |
| ZyDAS                                 | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Qualcomm Technologies                 | 1         | 0.01%   |
| IMC Networks                          | 1         | 0.01%   |
| AVM                                   | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 560       | 6.37%   |
| Intel Wireless 8265 / 8275                                     | 523       | 5.95%   |
| Intel Wi-Fi 6 AX201                                            | 453       | 5.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 316       | 3.59%   |
| Intel Wireless 8260                                            | 282       | 3.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 281       | 3.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 276       | 3.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 271       | 3.08%   |
| Intel Wireless 7260                                            | 264       | 3%      |
| Intel Wireless 7265                                            | 260       | 2.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 242       | 2.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 225       | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 223       | 2.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 216       | 2.46%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 207       | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 203       | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 196       | 2.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 167       | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 155       | 1.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 151       | 1.72%   |
| Intel Wireless 3165                                            | 136       | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 105       | 1.19%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 105       | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 102       | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 102       | 1.16%   |
| Broadcom BCM43142 802.11b/g/n                                  | 102       | 1.16%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 101       | 1.15%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 92        | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 91        | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 86        | 0.98%   |
| Intel Wireless 3160                                            | 85        | 0.97%   |
| Intel Centrino Ultimate-N 6300                                 | 82        | 0.93%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 80        | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 77        | 0.88%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 73        | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 71        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 57        | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 57        | 0.65%   |
| Intel Centrino Advanced-N 6235                                 | 54        | 0.61%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 49        | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3706      | 56.02%  |
| Intel                                  | 1825      | 27.58%  |
| Qualcomm Atheros                       | 276       | 4.17%   |
| Broadcom                               | 192       | 2.9%    |
| Lenovo                                 | 109       | 1.65%   |
| ASIX Electronics                       | 104       | 1.57%   |
| DisplayLink                            | 52        | 0.79%   |
| Samsung Electronics                    | 48        | 0.73%   |
| Marvell Technology Group               | 45        | 0.68%   |
| Xiaomi                                 | 38        | 0.57%   |
| Nvidia                                 | 27        | 0.41%   |
| Broadcom Limited                       | 27        | 0.41%   |
| TP-Link                                | 22        | 0.33%   |
| Google                                 | 22        | 0.33%   |
| Apple                                  | 16        | 0.24%   |
| Qualcomm                               | 15        | 0.23%   |
| Huawei Technologies                    | 14        | 0.21%   |
| OPPO Electronics                       | 12        | 0.18%   |
| JMicron Technology                     | 12        | 0.18%   |
| MediaTek                               | 8         | 0.12%   |
| Hewlett-Packard                        | 8         | 0.12%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.06%   |
| Cypress Semiconductor                  | 4         | 0.06%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| Motorola PCS                           | 3         | 0.05%   |
| D-Link                                 | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.03%   |
| Microsoft                              | 2         | 0.03%   |
| ICS Advent                             | 2         | 0.03%   |
| vivo                                   | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Linksys                                | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |
| Foxconn / Hon Hai                      | 1         | 0.02%   |
| ASUSTek Computer                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2596      | 38.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 518       | 7.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 489       | 7.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 280       | 4.16%   |
| Intel Ethernet Connection (4) I219-LM                                  | 201       | 2.99%   |
| Intel Ethernet Connection I219-LM                                      | 127       | 1.89%   |
| Intel Ethernet Connection (4) I219-V                                   | 117       | 1.74%   |
| ASIX AX88179 Gigabit Ethernet                                          | 95        | 1.41%   |
| Intel Ethernet Connection I218-LM                                      | 91        | 1.35%   |
| Intel Ethernet Connection (3) I218-LM                                  | 90        | 1.34%   |
| Intel Ethernet Connection I217-LM                                      | 83        | 1.23%   |
| Intel Ethernet Connection (6) I219-V                                   | 80        | 1.19%   |
| Intel Ethernet Connection (6) I219-LM                                  | 68        | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                      | 64        | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                                  | 64        | 0.95%   |
| Intel Ethernet Connection (10) I219-V                                  | 63        | 0.94%   |
| Intel 82577LM Gigabit Network Connection                               | 55        | 0.82%   |
| Realtek Killer E2600 GbE Controller                                    | 54        | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 54        | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                  | 50        | 0.74%   |
| Intel Ethernet Connection I219-V                                       | 47        | 0.7%    |
| Lenovo ThinkPad TBT 3 Dock                                             | 44        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                                  | 43        | 0.64%   |
| Intel Ethernet Connection (16) I219-V                                  | 39        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 38        | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 38        | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 38        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 38        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 33        | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 32        | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                   | 32        | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 31        | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 28        | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 28        | 0.42%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 28        | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 26        | 0.39%   |
| Intel 82567LM Gigabit Network Connection                               | 25        | 0.37%   |
| Nvidia MCP79 Ethernet                                                  | 24        | 0.36%   |
| Intel Ethernet Connection I217-V                                       | 23        | 0.34%   |
| Intel Ethernet Connection (10) I219-LM                                 | 23        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 8337      | 56.91%  |
| Ethernet | 6214      | 42.42%  |
| Modem    | 83        | 0.57%   |
| Unknown  | 15        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7191      | 79.84%  |
| Ethernet | 1814      | 20.14%  |
| Modem    | 2         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5506      | 64.82%  |
| 1     | 2741      | 32.27%  |
| 0     | 157       | 1.85%   |
| 3     | 89        | 1.05%   |
| 4     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 6759      | 77.99%  |
| Yes     | 1905      | 21.98%  |
| Unknown | 3         | 0.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 4144      | 57%     |
| Realtek Semiconductor           | 737       | 10.14%  |
| Qualcomm Atheros Communications | 579       | 7.96%   |
| IMC Networks                    | 331       | 4.55%   |
| Foxconn / Hon Hai               | 297       | 4.09%   |
| Broadcom                        | 285       | 3.92%   |
| Lite-On Technology              | 257       | 3.54%   |
| Apple                           | 219       | 3.01%   |
| Realtek                         | 89        | 1.22%   |
| Dell                            | 49        | 0.67%   |
| Cambridge Silicon Radio         | 48        | 0.66%   |
| Hewlett-Packard                 | 37        | 0.51%   |
| Ralink                          | 33        | 0.45%   |
| Toshiba                         | 30        | 0.41%   |
| USI                             | 26        | 0.36%   |
| MediaTek                        | 26        | 0.36%   |
| ASUSTek Computer                | 20        | 0.28%   |
| Foxconn International           | 19        | 0.26%   |
| Opticis                         | 12        | 0.17%   |
| Ralink Technology               | 5         | 0.07%   |
| Alps Electric                   | 5         | 0.07%   |
| Smart Modular Technologies      | 4         | 0.06%   |
| Askey Computer                  | 4         | 0.06%   |
| Chicony Electronics             | 3         | 0.04%   |
| Taiyo Yuden                     | 2         | 0.03%   |
| Qcom                            | 2         | 0.03%   |
| Fujitsu                         | 2         | 0.03%   |
| TP-Link                         | 1         | 0.01%   |
| Syntek                          | 1         | 0.01%   |
| Micro Star International        | 1         | 0.01%   |
| Dynex                           | 1         | 0.01%   |
| Corsair                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1418      | 19.49%  |
| Intel AX201 Bluetooth                               | 911       | 12.52%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 612       | 8.41%   |
| Intel AX200 Bluetooth                               | 546       | 7.5%    |
| Realtek Bluetooth Radio                             | 505       | 6.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 332       | 4.56%   |
| Intel Bluetooth Device                              | 289       | 3.97%   |
| Realtek  Bluetooth 4.2 Adapter                      | 158       | 2.17%   |
| IMC Networks Wireless_Device                        | 150       | 2.06%   |
| Intel AX210 Bluetooth                               | 146       | 2.01%   |
| Apple Bluetooth Host Controller                     | 140       | 1.92%   |
| Foxconn / Hon Hai Wireless_Device                   | 137       | 1.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 97        | 1.33%   |
| IMC Networks Bluetooth Radio                        | 95        | 1.31%   |
| Realtek Bluetooth Radio                             | 89        | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 88        | 1.21%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 88        | 1.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 86        | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 83        | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 62        | 0.85%   |
| Lite-On Bluetooth Device                            | 58        | 0.8%    |
| Apple Bluetooth USB Host Controller                 | 58        | 0.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 55        | 0.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 53        | 0.73%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 48        | 0.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 48        | 0.66%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 46        | 0.63%   |
| Broadcom BCM2045B (BDC-2.1)                         | 44        | 0.6%    |
| IMC Networks Bluetooth Device                       | 42        | 0.58%   |
| Lite-On Wireless_Device                             | 41        | 0.56%   |
| Ralink RT3290 Bluetooth                             | 33        | 0.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 30        | 0.41%   |
| HP Broadcom 2070 Bluetooth Combo                    | 28        | 0.38%   |
| USI Bluetooth Device                                | 26        | 0.36%   |
| Realtek RTL8723B Bluetooth                          | 26        | 0.36%   |
| MediaTek Wireless_Device                            | 26        | 0.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 24        | 0.33%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 23        | 0.32%   |
| Dell BCM20702A0 Bluetooth Module                    | 22        | 0.3%    |
| Dell DW375 Bluetooth Module                         | 21        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 6594      | 60.28%  |
| AMD                                  | 1831      | 16.74%  |
| Nvidia                               | 1465      | 13.39%  |
| Lenovo                               | 134       | 1.22%   |
| C-Media Electronics                  | 110       | 1.01%   |
| Realtek Semiconductor                | 95        | 0.87%   |
| Logitech                             | 79        | 0.72%   |
| GN Netcom                            | 77        | 0.7%    |
| Plantronics                          | 42        | 0.38%   |
| Hewlett-Packard                      | 38        | 0.35%   |
| JMTek                                | 37        | 0.34%   |
| Kingston Technology                  | 24        | 0.22%   |
| Texas Instruments                    | 22        | 0.2%    |
| Sony                                 | 21        | 0.19%   |
| Apple                                | 21        | 0.19%   |
| Creative Technology                  | 20        | 0.18%   |
| ASUSTek Computer                     | 17        | 0.16%   |
| SteelSeries ApS                      | 16        | 0.15%   |
| Razer USA                            | 15        | 0.14%   |
| Generalplus Technology               | 14        | 0.13%   |
| Focusrite-Novation                   | 13        | 0.12%   |
| Dell                                 | 13        | 0.12%   |
| Corsair                              | 13        | 0.12%   |
| Sennheiser Communications            | 11        | 0.1%    |
| Samson Technologies                  | 10        | 0.09%   |
| RODE Microphones                     | 10        | 0.09%   |
| Blue Microphones                     | 10        | 0.09%   |
| Microsoft                            | 9         | 0.08%   |
| Conexant Systems                     | 8         | 0.07%   |
| XMOS                                 | 7         | 0.06%   |
| Samsung Electronics                  | 7         | 0.06%   |
| No brand                             | 7         | 0.06%   |
| Tenx Technology                      | 6         | 0.05%   |
| FiiO Electronics Technology          | 6         | 0.05%   |
| CMX Systems                          | 6         | 0.05%   |
| SAVITECH                             | 5         | 0.05%   |
| GYROCOM C&C                          | 5         | 0.05%   |
| DSEA A/S                             | 5         | 0.05%   |
| Yamaha                               | 4         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1416      | 10.6%   |
| Intel Sunrise Point-LP HD Audio                                            | 1274      | 9.54%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 777       | 5.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 594       | 4.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 543       | 4.07%   |
| Intel Cannon Lake PCH cAVS                                                 | 414       | 3.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 359       | 2.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 344       | 2.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 339       | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 335       | 2.51%   |
| Intel Comet Lake PCH-LP cAVS                                               | 309       | 2.31%   |
| Intel Haswell-ULT HD Audio Controller                                      | 303       | 2.27%   |
| Intel 8 Series HD Audio Controller                                         | 302       | 2.26%   |
| Intel Broadwell-U Audio Controller                                         | 298       | 2.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 295       | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 270       | 2.02%   |
| Intel Comet Lake PCH cAVS                                                  | 238       | 1.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 213       | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 210       | 1.57%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 194       | 1.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 188       | 1.41%   |
| Intel CM238 HD Audio Controller                                            | 168       | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                            | 160       | 1.2%    |
| Nvidia Audio device                                                        | 154       | 1.15%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 152       | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 150       | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                              | 134       | 1%      |
| AMD FCH Azalia Controller                                                  | 128       | 0.96%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 103       | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                   | 101       | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 100       | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 98        | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 95        | 0.71%   |
| Realtek Semiconductor USB Audio                                            | 94        | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 93        | 0.7%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 85        | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 81        | 0.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 78        | 0.58%   |
| Nvidia GA104 High Definition Audio Controller                              | 74        | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                              | 69        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1525      | 30.03%  |
| SK hynix            | 1140      | 22.45%  |
| Micron Technology   | 754       | 14.85%  |
| Kingston            | 410       | 8.07%   |
| Crucial             | 291       | 5.73%   |
| Unknown             | 247       | 4.86%   |
| Ramaxel Technology  | 115       | 2.26%   |
| A-DATA Technology   | 106       | 2.09%   |
| Corsair             | 65        | 1.28%   |
| Elpida              | 45        | 0.89%   |
| Smart               | 34        | 0.67%   |
| Unknown             | 33        | 0.65%   |
| G.Skill             | 32        | 0.63%   |
| Unknown (ABCD)      | 29        | 0.57%   |
| Team                | 28        | 0.55%   |
| Nanya Technology    | 26        | 0.51%   |
| Patriot             | 21        | 0.41%   |
| Teikon              | 17        | 0.33%   |
| Smart Brazil        | 13        | 0.26%   |
| Transcend           | 12        | 0.24%   |
| GOODRAM             | 11        | 0.22%   |
| Avant               | 10        | 0.2%    |
| Apacer              | 6         | 0.12%   |
| Timetec             | 5         | 0.1%    |
| Silicon Power       | 5         | 0.1%    |
| Goldkey             | 5         | 0.1%    |
| ChangXin Memory     | 5         | 0.1%    |
| V-GeN               | 4         | 0.08%   |
| PUSKILL             | 4         | 0.08%   |
| PNY                 | 4         | 0.08%   |
| Lexar               | 4         | 0.08%   |
| Kllisre             | 4         | 0.08%   |
| CSX                 | 4         | 0.08%   |
| 4ea5                | 4         | 0.08%   |
| OnBoard             | 3         | 0.06%   |
| ASint Technology    | 3         | 0.06%   |
| Unknown (0x0B5E)    | 2         | 0.04%   |
| SHARETRONIC         | 2         | 0.04%   |
| Sesame              | 2         | 0.04%   |
| RZX                 | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 88        | 1.65%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 77        | 1.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 69        | 1.29%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 62        | 1.16%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 54        | 1.01%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 47        | 0.88%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 45        | 0.84%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 44        | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 43        | 0.81%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 38        | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 36        | 0.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 36        | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 36        | 0.67%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 36        | 0.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 34        | 0.64%   |
| Unknown                                                             | 33        | 0.62%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 32        | 0.6%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 32        | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 32        | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 31        | 0.58%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 31        | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 30        | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 30        | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 30        | 0.56%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 30        | 0.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 29        | 0.54%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 29        | 0.54%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 28        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 28        | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 28        | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 27        | 0.51%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 27        | 0.51%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 26        | 0.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 26        | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 26        | 0.49%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 26        | 0.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 25        | 0.47%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 25        | 0.47%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 25        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 24        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 2418      | 57%     |
| DDR3    | 1015      | 23.93%  |
| LPDDR4  | 230       | 5.42%   |
| LPDDR3  | 223       | 5.26%   |
| LPDDR5  | 150       | 3.54%   |
| DDR5    | 115       | 2.71%   |
| DDR2    | 50        | 1.18%   |
| SDRAM   | 23        | 0.54%   |
| Unknown | 14        | 0.33%   |
| DDR     | 3         | 0.07%   |
| DRAM    | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3576      | 82.74%  |
| Row Of Chips | 646       | 14.95%  |
| Chip         | 53        | 1.23%   |
| Unknown      | 26        | 0.6%    |
| DIMM         | 21        | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 2020      | 43.58%  |
| 4096  | 1135      | 24.49%  |
| 16384 | 907       | 19.57%  |
| 2048  | 331       | 7.14%   |
| 32768 | 185       | 3.99%   |
| 1024  | 51        | 1.1%    |
| 3072  | 3         | 0.06%   |
| 12288 | 1         | 0.02%   |
| 512   | 1         | 0.02%   |
| 64    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 1138      | 24.97%  |
| 2667    | 1031      | 22.62%  |
| 1600    | 732       | 16.06%  |
| 2400    | 310       | 6.8%    |
| 2133    | 297       | 6.52%   |
| 6400    | 141       | 3.09%   |
| 1333    | 123       | 2.7%    |
| 1334    | 121       | 2.65%   |
| 4267    | 110       | 2.41%   |
| 4800    | 99        | 2.17%   |
| 1867    | 90        | 1.97%   |
| 3266    | 62        | 1.36%   |
| 1067    | 44        | 0.97%   |
| 4266    | 35        | 0.77%   |
| Unknown | 35        | 0.77%   |
| 8400    | 30        | 0.66%   |
| 667     | 30        | 0.66%   |
| 5600    | 21        | 0.46%   |
| 3733    | 19        | 0.42%   |
| 1066    | 18        | 0.39%   |
| 4199    | 17        | 0.37%   |
| 800     | 15        | 0.33%   |
| 2933    | 5         | 0.11%   |
| 975     | 5         | 0.11%   |
| 7500    | 4         | 0.09%   |
| 7467    | 4         | 0.09%   |
| 2048    | 4         | 0.09%   |
| 5500    | 3         | 0.07%   |
| 533     | 3         | 0.07%   |
| 1866    | 2         | 0.04%   |
| 5200    | 1         | 0.02%   |
| 3800    | 1         | 0.02%   |
| 3600    | 1         | 0.02%   |
| 2800    | 1         | 0.02%   |
| 1776    | 1         | 0.02%   |
| 1639    | 1         | 0.02%   |
| 1200    | 1         | 0.02%   |
| 933     | 1         | 0.02%   |
| 333     | 1         | 0.02%   |
| 133     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Hewlett-Packard               | 15        | 29.41%  |
| Canon                         | 8         | 15.69%  |
| Brother Industries            | 7         | 13.73%  |
| Samsung Electronics           | 6         | 11.76%  |
| Seiko Epson                   | 5         | 9.8%    |
| Prolific Technology           | 2         | 3.92%   |
| STMicroelectronics            | 1         | 1.96%   |
| Samsung Info. Systems America | 1         | 1.96%   |
| Ricoh                         | 1         | 1.96%   |
| Pantum                        | 1         | 1.96%   |
| NXP Semiconductors            | 1         | 1.96%   |
| Minolta                       | 1         | 1.96%   |
| MiiiW                         | 1         | 1.96%   |
| Dymo-CoStar                   | 1         | 1.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 2         | 3.92%   |
| Prolific PL2305 Parallel Port                                         | 2         | 3.92%   |
| HP LaserJet P1102                                                     | 2         | 3.92%   |
| Brother DCP-1600                                                      | 2         | 3.92%   |
| STMicroelectronics USB Printing Support                               | 1         | 1.96%   |
| Seiko Epson WF-2830 Series                                            | 1         | 1.96%   |
| Seiko Epson L3150 Series                                              | 1         | 1.96%   |
| Seiko Epson L200 Series                                               | 1         | 1.96%   |
| Samsung Info. Systems America SAMSUNG SRP-270                         | 1         | 1.96%   |
| Samsung SCX-4200 series                                               | 1         | 1.96%   |
| Samsung SCX-3200 Series                                               | 1         | 1.96%   |
| Samsung ML-331x Series Laser Printer                                  | 1         | 1.96%   |
| Samsung M2070 Series                                                  | 1         | 1.96%   |
| Samsung CLX-6260 Series                                               | 1         | 1.96%   |
| Samsung C43x Series                                                   | 1         | 1.96%   |
| Ricoh SP 211SU                                                        | 1         | 1.96%   |
| Pantum P2500W series                                                  | 1         | 1.96%   |
| NXP Semiconductors Printer-80                                         | 1         | 1.96%   |
| Minolta PagePro 1300W                                                 | 1         | 1.96%   |
| MiiiW MW USB Receiver                                                 | 1         | 1.96%   |
| HP Smart Tank 510 series                                              | 1         | 1.96%   |
| HP Photosmart B010 series                                             | 1         | 1.96%   |
| HP Officejet 2620 series                                              | 1         | 1.96%   |
| HP LaserJet 400 colorMFP M475dw                                       | 1         | 1.96%   |
| HP LaserJet 1010                                                      | 1         | 1.96%   |
| HP Ink Tank 310 series                                                | 1         | 1.96%   |
| HP ENVY Pro 6400 series                                               | 1         | 1.96%   |
| HP ENVY 4500 series                                                   | 1         | 1.96%   |
| HP Deskjet 3510 series                                                | 1         | 1.96%   |
| HP Deskjet 3050A                                                      | 1         | 1.96%   |
| HP DeskJet 2600 series                                                | 1         | 1.96%   |
| HP DeskJet 2300 series                                                | 1         | 1.96%   |
| HP DeskJet 2130 series                                                | 1         | 1.96%   |
| Dymo-CoStar LabelWriter 450                                           | 1         | 1.96%   |
| Canon TR8500 series                                                   | 1         | 1.96%   |
| Canon TR150 series                                                    | 1         | 1.96%   |
| Canon PIXMA MG3600 Series                                             | 1         | 1.96%   |
| Canon PIXMA MG3500 Series                                             | 1         | 1.96%   |
| Canon PIXMA MG3000 series                                             | 1         | 1.96%   |
| Canon MF3110                                                          | 1         | 1.96%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 60%     |
| Seiko Epson     | 3         | 30%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20          | 2         | 20%     |
| Canon CanoScan LiDE 220                     | 2         | 20%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 10%     |
| Seiko Epson GT-X770 [Perfection V500]       | 1         | 10%     |
| Seiko Epson ES-D400 [GT-S80]                | 1         | 10%     |
| HP Scanjet 300                              | 1         | 10%     |
| Canon CanoScan N650U/N656U                  | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1818      | 23.03%  |
| IMC Networks                           | 983       | 12.45%  |
| Microdia                               | 700       | 8.87%   |
| Realtek Semiconductor                  | 640       | 8.11%   |
| Bison Electronics                      | 516       | 6.54%   |
| Quanta                                 | 497       | 6.3%    |
| Sunplus Innovation Technology          | 413       | 5.23%   |
| Cheng Uei Precision Industry (Foxlink) | 307       | 3.89%   |
| Acer                                   | 249       | 3.15%   |
| Syntek                                 | 222       | 2.81%   |
| Lite-On Technology                     | 209       | 2.65%   |
| Apple                                  | 191       | 2.42%   |
| Logitech                               | 175       | 2.22%   |
| Luxvisions Innotech Limited            | 172       | 2.18%   |
| Suyin                                  | 118       | 1.49%   |
| Sonix Technology                       | 95        | 1.2%    |
| Silicon Motion                         | 93        | 1.18%   |
| Alcor Micro                            | 55        | 0.7%    |
| Samsung Electronics                    | 49        | 0.62%   |
| Ricoh                                  | 42        | 0.53%   |
| Lenovo                                 | 26        | 0.33%   |
| SunplusIT                              | 25        | 0.32%   |
| Primax Electronics                     | 24        | 0.3%    |
| Microsoft                              | 20        | 0.25%   |
| Importek                               | 18        | 0.23%   |
| ShineTech                              | 15        | 0.19%   |
| Z-Star Microelectronics                | 12        | 0.15%   |
| USB Camera                             | 12        | 0.15%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 0.11%   |
| Generalplus Technology                 | 9         | 0.11%   |
| ALi                                    | 9         | 0.11%   |
| ARC International                      | 8         | 0.1%    |
| 8SSC21D67422V1SR3AV5KW1                | 8         | 0.1%    |
| MacroSilicon                           | 7         | 0.09%   |
| Intel                                  | 7         | 0.09%   |
| Creative Technology                    | 7         | 0.09%   |
| Razer USA                              | 6         | 0.08%   |
| KYE Systems (Mouse Systems)            | 6         | 0.08%   |
| WaveRider Communications               | 5         | 0.06%   |
| Tobii Technology AB                    | 5         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 628       | 7.9%    |
| Microdia Integrated_Webcam_HD                       | 401       | 5.04%   |
| IMC Networks Integrated Camera                      | 377       | 4.74%   |
| Realtek Integrated_Webcam_HD                        | 310       | 3.9%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 271       | 3.41%   |
| Chicony HD WebCam                                   | 181       | 2.28%   |
| Sunplus Integrated_Webcam_HD                        | 171       | 2.15%   |
| Bison Integrated Camera                             | 170       | 2.14%   |
| Syntek Integrated Camera                            | 156       | 1.96%   |
| Quanta HD User Facing                               | 101       | 1.27%   |
| Lite-On Integrated Camera                           | 99        | 1.25%   |
| Chicony Integrated Camera (1280x720@30)             | 97        | 1.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 79        | 0.99%   |
| Chicony HP HD Camera                                | 77        | 0.97%   |
| Acer SunplusIT Integrated Camera                    | 76        | 0.96%   |
| Acer Integrated Camera                              | 68        | 0.86%   |
| Quanta HP TrueVision HD Camera                      | 62        | 0.78%   |
| Bison Lenovo EasyCamera                             | 62        | 0.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 59        | 0.74%   |
| Chicony HP TrueVision HD Camera                     | 58        | 0.73%   |
| IMC Networks HD Camera                              | 55        | 0.69%   |
| Quanta HP HD Camera                                 | 54        | 0.68%   |
| Apple FaceTime HD Camera                            | 54        | 0.68%   |
| Sonix USB2.0 HD UVC WebCam                          | 53        | 0.67%   |
| Chicony USB2.0 Camera                               | 52        | 0.65%   |
| Realtek USB Camera                                  | 51        | 0.64%   |
| Microdia Integrated Webcam                          | 50        | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 50        | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)             | 49        | 0.62%   |
| Quanta HD Webcam                                    | 48        | 0.6%    |
| Lite-On HP HD Camera                                | 47        | 0.59%   |
| Quanta HP Wide Vision HD Camera                     | 46        | 0.58%   |
| Chicony HD User Facing                              | 45        | 0.57%   |
| Chicony HP Wide Vision HD Camera                    | 43        | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 43        | 0.54%   |
| Realtek Integrated Webcam                           | 42        | 0.53%   |
| IMC Networks ov9734_azurewave_camera                | 42        | 0.53%   |
| Logitech HD Pro Webcam C920                         | 40        | 0.5%    |
| Chicony HP TrueVision HD                            | 40        | 0.5%    |
| Apple Built-in iSight                               | 40        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 686       | 35.05%  |
| Validity Sensors                   | 570       | 29.13%  |
| Shenzhen Goodix Technology         | 356       | 18.19%  |
| Elan Microelectronics              | 122       | 6.23%   |
| Upek                               | 70        | 3.58%   |
| LighTuning Technology              | 63        | 3.22%   |
| AuthenTec                          | 43        | 2.2%    |
| Realtek USB2.0 Finger Print Bridge | 24        | 1.23%   |
| Samsung Electronics                | 11        | 0.56%   |
| STMicroelectronics                 | 5         | 0.26%   |
| Focal-systems.Corp                 | 5         | 0.26%   |
| FocalTech                          | 1         | 0.05%   |
| Dell                               | 1         | 0.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 308       | 15.73%  |
| Shenzhen Goodix  Fingerprint Device                                        | 230       | 11.75%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 132       | 6.74%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 124       | 6.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 107       | 5.46%   |
| Validity Sensors Synaptics WBDI                                            | 67        | 3.42%   |
| Shenzhen Goodix FingerPrint                                                | 67        | 3.42%   |
| Elan ELAN:Fingerprint                                                      | 67        | 3.42%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 65        | 3.32%   |
| Shenzhen Goodix Fingerprint Reader                                         | 59        | 3.01%   |
| Elan ELAN:ARM-M4                                                           | 53        | 2.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 51        | 2.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 47        | 2.4%    |
| Synaptics Fingerprint reader [HP G6]                                       | 44        | 2.25%   |
| Validity Sensors VFS491                                                    | 32        | 1.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 32        | 1.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 30        | 1.53%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 30        | 1.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 30        | 1.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 29        | 1.48%   |
| Synaptics UWP WBDI Device                                                  | 28        | 1.43%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 26        | 1.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 26        | 1.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 24        | 1.23%   |
| Synaptics  WBDI                                                            | 22        | 1.12%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 20        | 1.02%   |
| Validity Sensors Fingerprint scanner                                       | 19        | 0.97%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 17        | 0.87%   |
| Synaptics WBDI                                                             | 15        | 0.77%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 0.72%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 0.61%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 9         | 0.46%   |
| Synaptics UWP WBDI                                                         | 9         | 0.46%   |
| AuthenTec AES2810                                                          | 9         | 0.46%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 0.46%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.36%   |
| Synaptics TouchPad                                                         | 7         | 0.36%   |
| Unknown                                                                    | 7         | 0.36%   |
| Synaptics WBDI Device                                                      | 6         | 0.31%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 322       | 42.59%  |
| Alcor Micro                | 302       | 39.95%  |
| Upek                       | 43        | 5.69%   |
| Lenovo                     | 36        | 4.76%   |
| O2 Micro                   | 15        | 1.98%   |
| Gemalto (was Gemplus)      | 9         | 1.19%   |
| OmniKey                    | 5         | 0.66%   |
| Yubico.com                 | 4         | 0.53%   |
| Aladdin Knowledge Systems  | 4         | 0.53%   |
| SCM Microsystems           | 3         | 0.4%    |
| Realtek Semiconductor      | 3         | 0.4%    |
| Reiner SCT Kartensysteme   | 2         | 0.26%   |
| Advanced Card Systems      | 2         | 0.26%   |
| Purism, SPC                | 1         | 0.13%   |
| Hewlett-Packard            | 1         | 0.13%   |
| Chicony Electronics        | 1         | 0.13%   |
| Bit4id                     | 1         | 0.13%   |
| Athena Smartcard Solutions | 1         | 0.13%   |
| Aktiv                      | 1         | 0.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 301       | 39.81%  |
| Broadcom 5880                                                                | 105       | 13.89%  |
| Broadcom 58200                                                               | 95        | 12.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 71        | 9.39%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 49        | 6.48%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 43        | 5.69%   |
| Lenovo Integrated Smart Card Reader                                          | 35        | 4.63%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 12        | 1.59%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 6         | 0.79%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 4         | 0.53%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 0.53%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.4%    |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.4%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.4%    |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.26%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.26%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.13%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.13%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.13%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.13%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.13%   |
| Purism, SPC Librem Key                                                       | 1         | 0.13%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.13%   |
| OmniKey CardMan 4321                                                         | 1         | 0.13%   |
| OmniKey CardMan 1021                                                         | 1         | 0.13%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.13%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.13%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.13%   |
| Bit4id miniLector EVO                                                        | 1         | 0.13%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.13%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.13%   |
| Aktiv Rutoken lite                                                           | 1         | 0.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5068      | 57.93%  |
| 1     | 3031      | 34.65%  |
| 2     | 551       | 6.3%    |
| 3     | 67        | 0.77%   |
| 4     | 11        | 0.13%   |
| 5     | 8         | 0.09%   |
| 6     | 6         | 0.07%   |
| 7     | 4         | 0.05%   |
| 8     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1935      | 44.89%  |
| Graphics card            | 893       | 20.71%  |
| Multimedia controller    | 470       | 10.9%   |
| Net/wireless             | 319       | 7.4%    |
| Chipcard                 | 226       | 5.24%   |
| Camera                   | 152       | 3.53%   |
| Bluetooth                | 83        | 1.93%   |
| Storage                  | 57        | 1.32%   |
| Card reader              | 55        | 1.28%   |
| Sound                    | 41        | 0.95%   |
| Net/ethernet             | 25        | 0.58%   |
| Communication controller | 21        | 0.49%   |
| Network                  | 18        | 0.42%   |
| Modem                    | 11        | 0.26%   |
| Flash memory             | 2         | 0.05%   |
| Video                    | 1         | 0.02%   |
| Firewire controller      | 1         | 0.02%   |
| Dvb card                 | 1         | 0.02%   |

