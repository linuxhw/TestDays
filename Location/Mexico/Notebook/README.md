Linux in Mexico - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Mexico.

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

Total: 1606

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 4520s               | [8e03860e5f](https://linux-hardware.org/?probe=8e03860e5f) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| Alienware     | 17 R4                       | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [057703210a](https://linux-hardware.org/?probe=057703210a) | Jul 28, 2022 |
| Sony          | VPCS110FL                   | [8576955f3c](https://linux-hardware.org/?probe=8576955f3c) | Jul 28, 2022 |
| HP            | ProBook 4520s               | [80024f9b67](https://linux-hardware.org/?probe=80024f9b67) | Jul 26, 2022 |
| HP            | 245 G7 Notebook PC          | [07c70033f5](https://linux-hardware.org/?probe=07c70033f5) | Jul 25, 2022 |
| Alienware     | M11xR3                      | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| Dell          | Inspiron 3505               | [5bec1168d0](https://linux-hardware.org/?probe=5bec1168d0) | Jul 22, 2022 |
| HP            | 240 G4                      | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| Unknown       | W1415A                      | [3a2f4f9848](https://linux-hardware.org/?probe=3a2f4f9848) | Jul 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [8bf06ee1c1](https://linux-hardware.org/?probe=8bf06ee1c1) | Jul 21, 2022 |
| Dell          | Latitude E7250              | [5fdb8cad05](https://linux-hardware.org/?probe=5fdb8cad05) | Jul 21, 2022 |
| GHIA          | Notebook                    | [2193ab1cd3](https://linux-hardware.org/?probe=2193ab1cd3) | Jul 20, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [5859932a73](https://linux-hardware.org/?probe=5859932a73) | Jul 20, 2022 |
| HP            | EliteBook 8570w             | [6b8bf59f68](https://linux-hardware.org/?probe=6b8bf59f68) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Dell          | Inspiron 3421               | [d4c15eb5fd](https://linux-hardware.org/?probe=d4c15eb5fd) | Jul 18, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [27f6399025](https://linux-hardware.org/?probe=27f6399025) | Jul 16, 2022 |
| Dell          | Precision M4600             | [96f8364d87](https://linux-hardware.org/?probe=96f8364d87) | Jul 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [1cf6844d33](https://linux-hardware.org/?probe=1cf6844d33) | Jul 14, 2022 |
| Toshiba       | Satellite L55-B             | [0e0ba8274b](https://linux-hardware.org/?probe=0e0ba8274b) | Jul 13, 2022 |
| Toshiba       | Satellite L55-B             | [a7bebd622f](https://linux-hardware.org/?probe=a7bebd622f) | Jul 13, 2022 |
| Dell          | Inspiron 7460               | [316285fb12](https://linux-hardware.org/?probe=316285fb12) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Dell          | Latitude E5530 non-vPro     | [0ab6a30f98](https://linux-hardware.org/?probe=0ab6a30f98) | Jul 12, 2022 |
| Sony          | VPCYB20AL                   | [c9645d6952](https://linux-hardware.org/?probe=c9645d6952) | Jul 10, 2022 |
| Lenovo        | IdeaPad Y430 2781           | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Dell          | Inspiron 3558               | [14cacca8ad](https://linux-hardware.org/?probe=14cacca8ad) | Jul 09, 2022 |
| MSI           | GF63 Thin 11UC              | [ecfb5f39c5](https://linux-hardware.org/?probe=ecfb5f39c5) | Jul 09, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [a64c483143](https://linux-hardware.org/?probe=a64c483143) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [39e56d90b1](https://linux-hardware.org/?probe=39e56d90b1) | Jul 07, 2022 |
| Acer          | Nitro AN515-51              | [0b57ab5b5b](https://linux-hardware.org/?probe=0b57ab5b5b) | Jul 07, 2022 |
| ASUSTek       | X555DG                      | [b7a2c97bf2](https://linux-hardware.org/?probe=b7a2c97bf2) | Jul 07, 2022 |
| Acer          | Aspire E3-112M              | [6de763aad6](https://linux-hardware.org/?probe=6de763aad6) | Jul 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7e53f712c5](https://linux-hardware.org/?probe=7e53f712c5) | Jul 06, 2022 |
| Acer          | Aspire F5-573               | [1ada0ad162](https://linux-hardware.org/?probe=1ada0ad162) | Jul 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a673b1557d](https://linux-hardware.org/?probe=a673b1557d) | Jul 05, 2022 |
| HP            | Pavilion dv4                | [d40a5bd13e](https://linux-hardware.org/?probe=d40a5bd13e) | Jul 04, 2022 |
| Lenovo        | G40-45 80E1                 | [bce4ceea50](https://linux-hardware.org/?probe=bce4ceea50) | Jul 03, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [a5ad48eeb5](https://linux-hardware.org/?probe=a5ad48eeb5) | Jul 03, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [c364b347a5](https://linux-hardware.org/?probe=c364b347a5) | Jul 02, 2022 |
| Dell          | Precision M4600             | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| HUAWEI        | NBM-WXX9                    | [6ed674f77e](https://linux-hardware.org/?probe=6ed674f77e) | Jul 01, 2022 |
| Acer          | Aspire E5-573               | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6095915fb5](https://linux-hardware.org/?probe=6095915fb5) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [e7f3ea5cf5](https://linux-hardware.org/?probe=e7f3ea5cf5) | Jun 30, 2022 |
| HP            | Compaq CQ45                 | [74948790d0](https://linux-hardware.org/?probe=74948790d0) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Dell          | Latitude E6400              | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| Dell          | Latitude 7420               | [3730ffb739](https://linux-hardware.org/?probe=3730ffb739) | Jun 27, 2022 |
| HP            | OMEN Notebook PC 15         | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Sony          | VPCF236FM                   | [b2af243689](https://linux-hardware.org/?probe=b2af243689) | Jun 25, 2022 |
| Google        | Kip                         | [d21adde488](https://linux-hardware.org/?probe=d21adde488) | Jun 24, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| Dell          | Latitude E6400              | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| Alienware     | 17 R4                       | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [68ca5e600d](https://linux-hardware.org/?probe=68ca5e600d) | Jun 18, 2022 |
| Apple         | MacBookAir6,1               | [665cfa446b](https://linux-hardware.org/?probe=665cfa446b) | Jun 18, 2022 |
| HP            | Laptop 15-bs0xx             | [aa89682b09](https://linux-hardware.org/?probe=aa89682b09) | Jun 18, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Lenovo        | ThinkPad T540p 20BE003NU... | [e05c2e42c2](https://linux-hardware.org/?probe=e05c2e42c2) | Jun 17, 2022 |
| Gateway       | NE513                       | [c33ad72253](https://linux-hardware.org/?probe=c33ad72253) | Jun 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e4d5856a72](https://linux-hardware.org/?probe=e4d5856a72) | Jun 16, 2022 |
| Lenovo        | IdeaPad Z480                | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| Dell          | Latitude E6410              | [6194911b41](https://linux-hardware.org/?probe=6194911b41) | Jun 15, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| Lenovo        | Y50-70 20378                | [6153f90073](https://linux-hardware.org/?probe=6153f90073) | Jun 13, 2022 |
| Apple         | MacBookPro14,1              | [537b26aaf0](https://linux-hardware.org/?probe=537b26aaf0) | Jun 12, 2022 |
| Dell          | Latitude E6410              | [005799b9bf](https://linux-hardware.org/?probe=005799b9bf) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [ca2c0e822c](https://linux-hardware.org/?probe=ca2c0e822c) | Jun 11, 2022 |
| Dell          | Studio XPS 1340             | [36f61b29b5](https://linux-hardware.org/?probe=36f61b29b5) | Jun 11, 2022 |
| HP            | Pavilion dv6                | [c8e7eea8fc](https://linux-hardware.org/?probe=c8e7eea8fc) | Jun 11, 2022 |
| Corporativ... | Neuron LT                   | [84ed262694](https://linux-hardware.org/?probe=84ed262694) | Jun 10, 2022 |
| Corporativ... | Neuron LT                   | [ad265d5197](https://linux-hardware.org/?probe=ad265d5197) | Jun 10, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [479a01b8d8](https://linux-hardware.org/?probe=479a01b8d8) | Jun 10, 2022 |
| ASUSTek       | K43E                        | [cd9e7dab5e](https://linux-hardware.org/?probe=cd9e7dab5e) | Jun 09, 2022 |
| Acer          | Aspire E5-573               | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 2767AL9       | [8084a9ed95](https://linux-hardware.org/?probe=8084a9ed95) | Jun 08, 2022 |
| Toshiba       | Satellite L55-B             | [38c0d1cebc](https://linux-hardware.org/?probe=38c0d1cebc) | Jun 07, 2022 |
| HP            | Laptop 15-dy0xxx            | [e2a9ba60e2](https://linux-hardware.org/?probe=e2a9ba60e2) | Jun 07, 2022 |
| HP            | Laptop 15-dy2xxx            | [ecc580e75f](https://linux-hardware.org/?probe=ecc580e75f) | Jun 06, 2022 |
| HP            | Laptop 15-dy2xxx            | [e737d522f2](https://linux-hardware.org/?probe=e737d522f2) | Jun 06, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [84d72b2b06](https://linux-hardware.org/?probe=84d72b2b06) | Jun 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [058bd1f6b9](https://linux-hardware.org/?probe=058bd1f6b9) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| EVOO          | EV-C-116-7                  | [1955955afc](https://linux-hardware.org/?probe=1955955afc) | Jun 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [978a80c358](https://linux-hardware.org/?probe=978a80c358) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a3e63f04e7](https://linux-hardware.org/?probe=a3e63f04e7) | May 31, 2022 |
| Dell          | G7 7588                     | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| Dell          | Inspiron 5547               | [066f6369b2](https://linux-hardware.org/?probe=066f6369b2) | May 31, 2022 |
| Lenovo        | IdeaPad S300 20197          | [fcb07ac9aa](https://linux-hardware.org/?probe=fcb07ac9aa) | May 31, 2022 |
| Lenovo        | IdeaPad Z480                | [b1cf8ca505](https://linux-hardware.org/?probe=b1cf8ca505) | May 30, 2022 |
| Lenovo        | G50-30 80G0                 | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [55dfdf01c6](https://linux-hardware.org/?probe=55dfdf01c6) | May 29, 2022 |
| HP            | Presario CQ62               | [fe3cac8868](https://linux-hardware.org/?probe=fe3cac8868) | May 27, 2022 |
| Dell          | Inspiron 5570               | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| Acer          | Swift SF113-31              | [2bdba73cfa](https://linux-hardware.org/?probe=2bdba73cfa) | May 26, 2022 |
| Acer          | Aspire E3-112M              | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ad9da27671](https://linux-hardware.org/?probe=ad9da27671) | May 26, 2022 |
| HP            | Pavilion g4                 | [0c943e458a](https://linux-hardware.org/?probe=0c943e458a) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| ASUSTek       | X402CA                      | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| HUAWEI        | HVY-WXX9                    | [93bb32d1b2](https://linux-hardware.org/?probe=93bb32d1b2) | May 21, 2022 |
| Acer          | Aspire 5332                 | [f48da95c17](https://linux-hardware.org/?probe=f48da95c17) | May 21, 2022 |
| System76      | Oryx Pro                    | [b68edfe15c](https://linux-hardware.org/?probe=b68edfe15c) | May 17, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [f0fef230c2](https://linux-hardware.org/?probe=f0fef230c2) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [2f0e46cc27](https://linux-hardware.org/?probe=2f0e46cc27) | May 15, 2022 |
| Lenovo        | S10-3                       | [b2eb29a65e](https://linux-hardware.org/?probe=b2eb29a65e) | May 14, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4316b121b1](https://linux-hardware.org/?probe=4316b121b1) | May 14, 2022 |
| Dell          | Studio 1558                 | [ccffb59f97](https://linux-hardware.org/?probe=ccffb59f97) | May 13, 2022 |
| Toshiba       | Satellite C55-C             | [2695dd828d](https://linux-hardware.org/?probe=2695dd828d) | May 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [2bd7babedc](https://linux-hardware.org/?probe=2bd7babedc) | May 13, 2022 |
| Toshiba       | TECRA Z50-A                 | [985d5869bf](https://linux-hardware.org/?probe=985d5869bf) | May 12, 2022 |
| Dell          | XPS 15 9550                 | [de90425a28](https://linux-hardware.org/?probe=de90425a28) | May 09, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | [9b6892ebed](https://linux-hardware.org/?probe=9b6892ebed) | May 09, 2022 |
| Google        | Blooglet                    | [64b4f18c1c](https://linux-hardware.org/?probe=64b4f18c1c) | May 09, 2022 |
| Google        | Blooglet                    | [f3dc91bf66](https://linux-hardware.org/?probe=f3dc91bf66) | May 09, 2022 |
| HP            | Laptop 17z-ca300            | [c43f2b0e29](https://linux-hardware.org/?probe=c43f2b0e29) | May 08, 2022 |
| Acer          | Aspire ES1-531              | [a7927b8b27](https://linux-hardware.org/?probe=a7927b8b27) | May 08, 2022 |
| Acer          | Aspire F5-573               | [d6961632c4](https://linux-hardware.org/?probe=d6961632c4) | May 07, 2022 |
| HP            | Notebook                    | [04f5e602de](https://linux-hardware.org/?probe=04f5e602de) | May 07, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [46d0c349d6](https://linux-hardware.org/?probe=46d0c349d6) | May 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [38f5d37dcc](https://linux-hardware.org/?probe=38f5d37dcc) | May 07, 2022 |
| HP            | Pavilion 14                 | [2bd48eeb41](https://linux-hardware.org/?probe=2bd48eeb41) | May 06, 2022 |
| Apple         | MacBookAir6,2               | [d04d5e927d](https://linux-hardware.org/?probe=d04d5e927d) | May 05, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [4208da52ad](https://linux-hardware.org/?probe=4208da52ad) | May 04, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | [a3eb29c75d](https://linux-hardware.org/?probe=a3eb29c75d) | May 04, 2022 |
| Dell          | Latitude 7420               | [a0bd1ee0f4](https://linux-hardware.org/?probe=a0bd1ee0f4) | May 03, 2022 |
| Sony          | VPCF236FM                   | [ec0af02205](https://linux-hardware.org/?probe=ec0af02205) | May 02, 2022 |
| Acer          | Aspire V5-561               | [e9dfda82d4](https://linux-hardware.org/?probe=e9dfda82d4) | May 02, 2022 |
| Dell          | Latitude E5550              | [42a576bd39](https://linux-hardware.org/?probe=42a576bd39) | May 01, 2022 |
| HP            | Pavilion 13 x2 PC           | [fbb6d3b97e](https://linux-hardware.org/?probe=fbb6d3b97e) | May 01, 2022 |
| HP            | Pavilion 13 x2 PC           | [d594f3335c](https://linux-hardware.org/?probe=d594f3335c) | May 01, 2022 |
| ASUSTek       | X202E                       | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f5d70fb9d3](https://linux-hardware.org/?probe=f5d70fb9d3) | Apr 30, 2022 |
| Lenovo        | S10-3                       | [712c2dced9](https://linux-hardware.org/?probe=712c2dced9) | Apr 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [824ccc1317](https://linux-hardware.org/?probe=824ccc1317) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [35e8d13a74](https://linux-hardware.org/?probe=35e8d13a74) | Apr 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| Toshiba       | Satellite L735D             | [4bd23809e6](https://linux-hardware.org/?probe=4bd23809e6) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [d48006a0b2](https://linux-hardware.org/?probe=d48006a0b2) | Apr 26, 2022 |
| Toshiba       | Satellite C55-C             | [e9bc1aaf05](https://linux-hardware.org/?probe=e9bc1aaf05) | Apr 26, 2022 |
| Dell          | Inspiron 5577               | [0925d92173](https://linux-hardware.org/?probe=0925d92173) | Apr 25, 2022 |
| Lenovo        | ThinkPad E460 20ET000YLM    | [c82beac367](https://linux-hardware.org/?probe=c82beac367) | Apr 23, 2022 |
| HUAWEI        | HVY-WXX9                    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| ASUSTek       | K46CA                       | [e762eba391](https://linux-hardware.org/?probe=e762eba391) | Apr 23, 2022 |
| HP            | EliteBook 8570w             | [0a4b339d0f](https://linux-hardware.org/?probe=0a4b339d0f) | Apr 23, 2022 |
| Chuwi         | Unknown                     | [96105ecbb2](https://linux-hardware.org/?probe=96105ecbb2) | Apr 23, 2022 |
| Lenovo        | ThinkPad W530 2463A49       | [202b5d34a1](https://linux-hardware.org/?probe=202b5d34a1) | Apr 18, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [55186a3c2e](https://linux-hardware.org/?probe=55186a3c2e) | Apr 18, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | [726f69890c](https://linux-hardware.org/?probe=726f69890c) | Apr 17, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [382836d952](https://linux-hardware.org/?probe=382836d952) | Apr 16, 2022 |
| Acer          | Aspire R3-131T              | [776575ecdb](https://linux-hardware.org/?probe=776575ecdb) | Apr 16, 2022 |
| Lenovo        | G40-45 80E1                 | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Sony          | VPCEE23FX                   | [4c7634a096](https://linux-hardware.org/?probe=4c7634a096) | Apr 15, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [25c2200e11](https://linux-hardware.org/?probe=25c2200e11) | Apr 14, 2022 |
| HP            | Laptop 14-cm0xxx            | [d6463e4014](https://linux-hardware.org/?probe=d6463e4014) | Apr 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | [8888d86504](https://linux-hardware.org/?probe=8888d86504) | Apr 13, 2022 |
| Acer          | Nitro AN515-41              | [b938e715f4](https://linux-hardware.org/?probe=b938e715f4) | Apr 13, 2022 |
| HP            | ProBook 650 G1              | [5d153a1030](https://linux-hardware.org/?probe=5d153a1030) | Apr 12, 2022 |
| HP            | ZBook 15                    | [c8c2248854](https://linux-hardware.org/?probe=c8c2248854) | Apr 11, 2022 |
| Toshiba       | Satellite L735D             | [47f0119635](https://linux-hardware.org/?probe=47f0119635) | Apr 10, 2022 |
| HP            | EliteBook 8570w             | [9d7c1a88d6](https://linux-hardware.org/?probe=9d7c1a88d6) | Apr 10, 2022 |
| HP            | Laptop 15-da1xxx            | [8d9c212045](https://linux-hardware.org/?probe=8d9c212045) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Dell          | Inspiron 5570               | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| HP            | ZBook 15                    | [ee70932ef2](https://linux-hardware.org/?probe=ee70932ef2) | Apr 09, 2022 |
| HP            | Pavilion dv6                | [9d37acefa0](https://linux-hardware.org/?probe=9d37acefa0) | Apr 09, 2022 |
| Sony          | VPCF236FM                   | [ea109b146b](https://linux-hardware.org/?probe=ea109b146b) | Apr 08, 2022 |
| Toshiba       | NB505                       | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| Toshiba       | Satellite P775              | [3acd0b8861](https://linux-hardware.org/?probe=3acd0b8861) | Apr 08, 2022 |
| Dell          | Inspiron 5570               | [801e4fdab1](https://linux-hardware.org/?probe=801e4fdab1) | Apr 07, 2022 |
| Dell          | Latitude E5440              | [18a9d37c02](https://linux-hardware.org/?probe=18a9d37c02) | Apr 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | [e168714dee](https://linux-hardware.org/?probe=e168714dee) | Apr 06, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| HP            | 245 G7 Notebook PC          | [9d26a79ca6](https://linux-hardware.org/?probe=9d26a79ca6) | Apr 05, 2022 |
| HP            | 245 G7 Notebook PC          | [54db9ac27f](https://linux-hardware.org/?probe=54db9ac27f) | Apr 05, 2022 |
| HP            | Pavilion 14                 | [136105017c](https://linux-hardware.org/?probe=136105017c) | Apr 04, 2022 |
| HP            | Presario CQ56               | [7233c29381](https://linux-hardware.org/?probe=7233c29381) | Apr 03, 2022 |
| Toshiba       | Satellite S855D             | [45b97d03ed](https://linux-hardware.org/?probe=45b97d03ed) | Apr 03, 2022 |
| Apple         | MacBookPro9,2               | [f646cb03d2](https://linux-hardware.org/?probe=f646cb03d2) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [b87a95ae1a](https://linux-hardware.org/?probe=b87a95ae1a) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [fecf079b63](https://linux-hardware.org/?probe=fecf079b63) | Mar 31, 2022 |
| Dell          | Venue 8 Pro 5855            | [35a463a0fb](https://linux-hardware.org/?probe=35a463a0fb) | Mar 31, 2022 |
| HUAWEI        | HVY-WXX9                    | [5af7df2c2a](https://linux-hardware.org/?probe=5af7df2c2a) | Mar 30, 2022 |
| Acer          | Aspire one                  | [2b0b231b1a](https://linux-hardware.org/?probe=2b0b231b1a) | Mar 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [d346f2a1b1](https://linux-hardware.org/?probe=d346f2a1b1) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [67475db5e9](https://linux-hardware.org/?probe=67475db5e9) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [2c7227662f](https://linux-hardware.org/?probe=2c7227662f) | Mar 29, 2022 |
| Toshiba       | NB505                       | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Dell          | Latitude E6510              | [4feee8c983](https://linux-hardware.org/?probe=4feee8c983) | Mar 26, 2022 |
| HP            | Pavilion 11 x360 PC         | [975bcd1031](https://linux-hardware.org/?probe=975bcd1031) | Mar 25, 2022 |
| HP            | Laptop 15-bw0xx             | [eb140d5b4d](https://linux-hardware.org/?probe=eb140d5b4d) | Mar 25, 2022 |
| Sony          | SVT13125CLS                 | [5332da89c8](https://linux-hardware.org/?probe=5332da89c8) | Mar 25, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [4b955479cc](https://linux-hardware.org/?probe=4b955479cc) | Mar 24, 2022 |
| System76      | Gazelle                     | [5a83198dd6](https://linux-hardware.org/?probe=5a83198dd6) | Mar 24, 2022 |
| Acer          | Nitro AN515-54              | [4bb7650e38](https://linux-hardware.org/?probe=4bb7650e38) | Mar 23, 2022 |
| Lenovo        | Unknown                     | [661ddbd0df](https://linux-hardware.org/?probe=661ddbd0df) | Mar 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [e1f3c645b5](https://linux-hardware.org/?probe=e1f3c645b5) | Mar 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1PD0M    | [ed01dc4465](https://linux-hardware.org/?probe=ed01dc4465) | Mar 17, 2022 |
| HP            | EliteBook 8460p             | [6c0caa0de4](https://linux-hardware.org/?probe=6c0caa0de4) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1PD0M    | [dbed1562e8](https://linux-hardware.org/?probe=dbed1562e8) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| HP            | Pavilion 15                 | [29ac5f13cd](https://linux-hardware.org/?probe=29ac5f13cd) | Mar 16, 2022 |
| Apple         | MacBookPro15,2              | [a77a1ff925](https://linux-hardware.org/?probe=a77a1ff925) | Mar 16, 2022 |
| Dell          | Latitude E6220              | [0dbd85da47](https://linux-hardware.org/?probe=0dbd85da47) | Mar 13, 2022 |
| Dell          | G5 5505                     | [286d140bd5](https://linux-hardware.org/?probe=286d140bd5) | Mar 10, 2022 |
| HP            | ProBook 650 G1              | [046572a251](https://linux-hardware.org/?probe=046572a251) | Mar 09, 2022 |
| Dell          | XPS 15 9570                 | [dd0ebc18ce](https://linux-hardware.org/?probe=dd0ebc18ce) | Mar 07, 2022 |
| Acer          | Aspire E5-575               | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Chuwi         | GemiBook                    | [60146fd918](https://linux-hardware.org/?probe=60146fd918) | Mar 07, 2022 |
| Acer          | Aspire VN7-572              | [952fd83515](https://linux-hardware.org/?probe=952fd83515) | Mar 06, 2022 |
| Unknown       | KN12A                       | [3ba6165509](https://linux-hardware.org/?probe=3ba6165509) | Mar 05, 2022 |
| Panasonic     | CF-30KTPA9NP                | [fffe3abd97](https://linux-hardware.org/?probe=fffe3abd97) | Mar 05, 2022 |
| Lenovo        | G40-70 20369                | [fd797ac0c1](https://linux-hardware.org/?probe=fd797ac0c1) | Mar 03, 2022 |
| Chuwi         | GemiBook                    | [af28b0f0d8](https://linux-hardware.org/?probe=af28b0f0d8) | Mar 02, 2022 |
| Timi          | TM1612                      | [dc1c26b3a9](https://linux-hardware.org/?probe=dc1c26b3a9) | Mar 01, 2022 |
| Sony          | VGN-Z690N                   | [d3465abe44](https://linux-hardware.org/?probe=d3465abe44) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | [0a0e3feff6](https://linux-hardware.org/?probe=0a0e3feff6) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | [2b791434ce](https://linux-hardware.org/?probe=2b791434ce) | Feb 28, 2022 |
| Toshiba       | Satellite C655D             | [10f38d005e](https://linux-hardware.org/?probe=10f38d005e) | Feb 28, 2022 |
| ASUSTek       | X401A                       | [e97f529634](https://linux-hardware.org/?probe=e97f529634) | Feb 28, 2022 |
| Lenovo        | Z40-70 20366                | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Apple         | MacBookAir5,2               | [fb0403c8b8](https://linux-hardware.org/?probe=fb0403c8b8) | Feb 26, 2022 |
| Timi          | RedmiBook 13 R              | [a74bea030c](https://linux-hardware.org/?probe=a74bea030c) | Feb 25, 2022 |
| Timi          | RedmiBook 13 R              | [318a4d1d35](https://linux-hardware.org/?probe=318a4d1d35) | Feb 25, 2022 |
| MSI           | GL75 Leopard 10SDK          | [6a14728490](https://linux-hardware.org/?probe=6a14728490) | Feb 24, 2022 |
| Apple         | MacBookPro15,2              | [aebbda3f2d](https://linux-hardware.org/?probe=aebbda3f2d) | Feb 23, 2022 |
| Apple         | MacBookPro15,2              | [302836f9d3](https://linux-hardware.org/?probe=302836f9d3) | Feb 23, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [fe042017e6](https://linux-hardware.org/?probe=fe042017e6) | Feb 23, 2022 |
| ASUSTek       | X45U                        | [41f11e9487](https://linux-hardware.org/?probe=41f11e9487) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [229a11c203](https://linux-hardware.org/?probe=229a11c203) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [2a934577d6](https://linux-hardware.org/?probe=2a934577d6) | Feb 20, 2022 |
| Acer          | Aspire A315-56              | [26d9aa49e7](https://linux-hardware.org/?probe=26d9aa49e7) | Feb 19, 2022 |
| HP            | ProBook 4530s               | [26a60b46d2](https://linux-hardware.org/?probe=26a60b46d2) | Feb 18, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [91540e8aa6](https://linux-hardware.org/?probe=91540e8aa6) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3e5d5d5afe](https://linux-hardware.org/?probe=3e5d5d5afe) | Feb 18, 2022 |
| Hyundai Te... | Thinnote 13                 | [16d5bcb194](https://linux-hardware.org/?probe=16d5bcb194) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [eb1d4cf9d8](https://linux-hardware.org/?probe=eb1d4cf9d8) | Feb 17, 2022 |
| Acer          | Aspire A315-56              | [38fe80e2a8](https://linux-hardware.org/?probe=38fe80e2a8) | Feb 17, 2022 |
| Acer          | Aspire A315-56              | [cf4c296719](https://linux-hardware.org/?probe=cf4c296719) | Feb 17, 2022 |
| Apple         | MacBookPro14,1              | [f7c7bd4baf](https://linux-hardware.org/?probe=f7c7bd4baf) | Feb 17, 2022 |
| Acer          | TravelMate P214-53          | [4d1c34fef7](https://linux-hardware.org/?probe=4d1c34fef7) | Feb 17, 2022 |
| Lenovo        | G40-45 80E1                 | [f181193143](https://linux-hardware.org/?probe=f181193143) | Feb 16, 2022 |
| Lenovo        | G40-45 80E1                 | [88c9f0db96](https://linux-hardware.org/?probe=88c9f0db96) | Feb 16, 2022 |
| Dell          | Latitude E7440              | [1efc982c71](https://linux-hardware.org/?probe=1efc982c71) | Feb 16, 2022 |
| HP            | Laptop 15-da0xxx            | [84171dc3cd](https://linux-hardware.org/?probe=84171dc3cd) | Feb 16, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [34fff5bf39](https://linux-hardware.org/?probe=34fff5bf39) | Feb 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [85d4a8278e](https://linux-hardware.org/?probe=85d4a8278e) | Feb 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [a533f0d469](https://linux-hardware.org/?probe=a533f0d469) | Feb 14, 2022 |
| HP            | 655                         | [b0189b16b1](https://linux-hardware.org/?probe=b0189b16b1) | Feb 14, 2022 |
| HP            | Laptop 15-da2xxx            | [51dfcad0d4](https://linux-hardware.org/?probe=51dfcad0d4) | Feb 14, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [429d06ed33](https://linux-hardware.org/?probe=429d06ed33) | Feb 13, 2022 |
| HP            | 245 G1                      | [30c3eb937a](https://linux-hardware.org/?probe=30c3eb937a) | Feb 13, 2022 |
| Dell          | Inspiron 5537               | [3ef228db80](https://linux-hardware.org/?probe=3ef228db80) | Feb 11, 2022 |
| Dell          | Latitude 7420               | [2547d7836e](https://linux-hardware.org/?probe=2547d7836e) | Feb 11, 2022 |
| HP            | Laptop 15-dw0xxx            | [16157beba6](https://linux-hardware.org/?probe=16157beba6) | Feb 11, 2022 |
| Sony          | VGN-Z575FN                  | [4998f7ae6d](https://linux-hardware.org/?probe=4998f7ae6d) | Feb 11, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [cc5c3cd3d0](https://linux-hardware.org/?probe=cc5c3cd3d0) | Feb 11, 2022 |
| Lenovo        | ThinkPad T430 2349L38       | [85d1c3705e](https://linux-hardware.org/?probe=85d1c3705e) | Feb 09, 2022 |
| Dell          | Inspiron 5567               | [eec17e2cdc](https://linux-hardware.org/?probe=eec17e2cdc) | Feb 09, 2022 |
| HP            | ProBook 645 G1              | [98bdb87a7c](https://linux-hardware.org/?probe=98bdb87a7c) | Feb 08, 2022 |
| Lanix         | A V16                       | [2cbb463004](https://linux-hardware.org/?probe=2cbb463004) | Feb 08, 2022 |
| Lenovo        | ThinkPad Edge 13IAL# 019... | [78011da841](https://linux-hardware.org/?probe=78011da841) | Feb 07, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | [7196de2b08](https://linux-hardware.org/?probe=7196de2b08) | Feb 06, 2022 |
| HP            | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Sony          | VPCF236FM                   | [784b1b0c3b](https://linux-hardware.org/?probe=784b1b0c3b) | Feb 06, 2022 |
| Lanix         | NEURON_FLEX                 | [566f9282eb](https://linux-hardware.org/?probe=566f9282eb) | Feb 05, 2022 |
| HP            | Laptop 17-cn0xxx            | [cfdee7d88e](https://linux-hardware.org/?probe=cfdee7d88e) | Feb 05, 2022 |
| Lanix         | NEURON_FLEX                 | [90d39053df](https://linux-hardware.org/?probe=90d39053df) | Feb 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5a11c55e55](https://linux-hardware.org/?probe=5a11c55e55) | Feb 05, 2022 |
| HP            | 240 G4                      | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| Samsung       | 305V4A/305V5A               | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| Dell          | Latitude 3420               | [98d388a60d](https://linux-hardware.org/?probe=98d388a60d) | Feb 03, 2022 |
| Lenovo        | V14-ARE 82DQ                | [b3cfaa23eb](https://linux-hardware.org/?probe=b3cfaa23eb) | Feb 01, 2022 |
| Lenovo        | Rev B 20YM                  | [83c63da100](https://linux-hardware.org/?probe=83c63da100) | Feb 01, 2022 |
| Dell          | Latitude 3330               | [c3b39f74b4](https://linux-hardware.org/?probe=c3b39f74b4) | Jan 31, 2022 |
| Dell          | Latitude 3330               | [61a24473d4](https://linux-hardware.org/?probe=61a24473d4) | Jan 31, 2022 |
| Corporativ... | MB40II5                     | [ba6bc223c3](https://linux-hardware.org/?probe=ba6bc223c3) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [2248ba47d2](https://linux-hardware.org/?probe=2248ba47d2) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [74eb47cb2f](https://linux-hardware.org/?probe=74eb47cb2f) | Jan 30, 2022 |
| Corporativ... | MB40II5                     | [3c62692a0f](https://linux-hardware.org/?probe=3c62692a0f) | Jan 30, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e06431af49](https://linux-hardware.org/?probe=e06431af49) | Jan 29, 2022 |
| HP            | Laptop 14-cm0xxx            | [36fa473b25](https://linux-hardware.org/?probe=36fa473b25) | Jan 29, 2022 |
| Apple         | MacBookAir6,2               | [f25c578f5a](https://linux-hardware.org/?probe=f25c578f5a) | Jan 28, 2022 |
| Timi          | TM1701                      | [c4387537b3](https://linux-hardware.org/?probe=c4387537b3) | Jan 28, 2022 |
| Dell          | Latitude E6410              | [8f9cad1934](https://linux-hardware.org/?probe=8f9cad1934) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWA15L0... | [6e1153bb21](https://linux-hardware.org/?probe=6e1153bb21) | Jan 28, 2022 |
| Timi          | TM1701                      | [90877c2a8a](https://linux-hardware.org/?probe=90877c2a8a) | Jan 28, 2022 |
| HP            | EliteBook 8460p             | [49ab3da4e2](https://linux-hardware.org/?probe=49ab3da4e2) | Jan 28, 2022 |
| System76      | Gazelle                     | [4066e8f06a](https://linux-hardware.org/?probe=4066e8f06a) | Jan 24, 2022 |
| ASUSTek       | B551LG                      | [4df03afb9f](https://linux-hardware.org/?probe=4df03afb9f) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f9deb1d329](https://linux-hardware.org/?probe=f9deb1d329) | Jan 20, 2022 |
| Alienware     | x15 R1                      | [5f9dce49b3](https://linux-hardware.org/?probe=5f9dce49b3) | Jan 20, 2022 |
| Acer          | Predator G9-591             | [187b246949](https://linux-hardware.org/?probe=187b246949) | Jan 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [efdc064669](https://linux-hardware.org/?probe=efdc064669) | Jan 19, 2022 |
| Dell          | Latitude E6400              | [05d5d5de96](https://linux-hardware.org/?probe=05d5d5de96) | Jan 17, 2022 |
| Google        | Ultima                      | [d942b9081b](https://linux-hardware.org/?probe=d942b9081b) | Jan 16, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | [750744f996](https://linux-hardware.org/?probe=750744f996) | Jan 16, 2022 |
| Dell          | XPS 15 9570                 | [eb68d3d4dd](https://linux-hardware.org/?probe=eb68d3d4dd) | Jan 15, 2022 |
| Dell          | Inspiron 1525               | [286a7e58fd](https://linux-hardware.org/?probe=286a7e58fd) | Jan 14, 2022 |
| Dell          | Inspiron 1525               | [981a9aff50](https://linux-hardware.org/?probe=981a9aff50) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2d83a27067](https://linux-hardware.org/?probe=2d83a27067) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [ee8a872afd](https://linux-hardware.org/?probe=ee8a872afd) | Jan 13, 2022 |
| Dell          | Inspiron 3505               | [85c2838614](https://linux-hardware.org/?probe=85c2838614) | Jan 11, 2022 |
| Acer          | Aspire F5-573               | [2bf3f44e95](https://linux-hardware.org/?probe=2bf3f44e95) | Jan 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [99a245965c](https://linux-hardware.org/?probe=99a245965c) | Jan 09, 2022 |
| HUAWEI        | MACHD-WXX9                  | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Apple         | MacBook3,1                  | [b384dcb200](https://linux-hardware.org/?probe=b384dcb200) | Jan 06, 2022 |
| Dell          | Inspiron M5030              | [1715a3e584](https://linux-hardware.org/?probe=1715a3e584) | Jan 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [1660421dd9](https://linux-hardware.org/?probe=1660421dd9) | Jan 05, 2022 |
| MSI           | Bravo 15 A4DDR              | [d9aa580e5f](https://linux-hardware.org/?probe=d9aa580e5f) | Jan 05, 2022 |
| HP            | Compaq Mini CQ10-400        | [643f4e101f](https://linux-hardware.org/?probe=643f4e101f) | Jan 05, 2022 |
| HP            | Compaq Mini CQ10-400        | [ca3df238bc](https://linux-hardware.org/?probe=ca3df238bc) | Jan 05, 2022 |
| HP            | Pavilion 14                 | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| Acer          | Aspire E3-112M              | [466004173b](https://linux-hardware.org/?probe=466004173b) | Jan 04, 2022 |
| Lenovo        | ThinkPad W530 24382HU       | [5a4cc794e4](https://linux-hardware.org/?probe=5a4cc794e4) | Jan 02, 2022 |
| Lanix         | NeuronALV5                  | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| ASUSTek       | G75VW                       | [ffda51867b](https://linux-hardware.org/?probe=ffda51867b) | Jan 01, 2022 |
| eMachines     | E525                        | [192bbb8b30](https://linux-hardware.org/?probe=192bbb8b30) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Alienware     | 17 R3                       | [d5f4157f56](https://linux-hardware.org/?probe=d5f4157f56) | Dec 30, 2021 |
| Alienware     | 17 R3                       | [6c4813d3fd](https://linux-hardware.org/?probe=6c4813d3fd) | Dec 30, 2021 |
| Sony          | SVF14215CLW                 | [de9115a89c](https://linux-hardware.org/?probe=de9115a89c) | Dec 30, 2021 |
| Sony          | SVF14215CLW                 | [bf4fd6e13c](https://linux-hardware.org/?probe=bf4fd6e13c) | Dec 30, 2021 |
| HP            | ZBook 15u G3                | [e220b55c78](https://linux-hardware.org/?probe=e220b55c78) | Dec 30, 2021 |
| ASUSTek       | K43E                        | [38e1c3f86f](https://linux-hardware.org/?probe=38e1c3f86f) | Dec 30, 2021 |
| HUAWEI        | WRTD-WXX9                   | [0184868fb6](https://linux-hardware.org/?probe=0184868fb6) | Dec 29, 2021 |
| HP            | EliteBook 8460p             | [e9cf5c0353](https://linux-hardware.org/?probe=e9cf5c0353) | Dec 29, 2021 |
| Sony          | VPCEA35FL                   | [6c2b68633d](https://linux-hardware.org/?probe=6c2b68633d) | Dec 27, 2021 |
| HP            | ZBook 15u G3                | [f770dacb13](https://linux-hardware.org/?probe=f770dacb13) | Dec 25, 2021 |
| Acer          | Aspire 4752                 | [bb08100c63](https://linux-hardware.org/?probe=bb08100c63) | Dec 24, 2021 |
| MSI           | GF65 Thin 9SEXR             | [2be4e41c8e](https://linux-hardware.org/?probe=2be4e41c8e) | Dec 22, 2021 |
| Samsung       | RC410/RC510/RC710           | [123bdbfa71](https://linux-hardware.org/?probe=123bdbfa71) | Dec 22, 2021 |
| HP            | Pavilion dv4                | [7152c2fcd9](https://linux-hardware.org/?probe=7152c2fcd9) | Dec 22, 2021 |
| Apple         | MacBookPro14,1              | [e82554da93](https://linux-hardware.org/?probe=e82554da93) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [022cabd3f2](https://linux-hardware.org/?probe=022cabd3f2) | Dec 21, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | [d14536043e](https://linux-hardware.org/?probe=d14536043e) | Dec 20, 2021 |
| HUAWEI        | MACH-WX9                    | [033e872459](https://linux-hardware.org/?probe=033e872459) | Dec 19, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [ffd979b53f](https://linux-hardware.org/?probe=ffd979b53f) | Dec 19, 2021 |
| HP            | 14                          | [921783a9be](https://linux-hardware.org/?probe=921783a9be) | Dec 17, 2021 |
| ASUSTek       | X541NA                      | [70801591a7](https://linux-hardware.org/?probe=70801591a7) | Dec 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [66c985876e](https://linux-hardware.org/?probe=66c985876e) | Dec 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [ca0c96e24b](https://linux-hardware.org/?probe=ca0c96e24b) | Dec 15, 2021 |
| ASUSTek       | N53SV                       | [c17076e55c](https://linux-hardware.org/?probe=c17076e55c) | Dec 15, 2021 |
| Toshiba       | TECRA Z50-A                 | [0119ac4373](https://linux-hardware.org/?probe=0119ac4373) | Dec 15, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | [191acd1645](https://linux-hardware.org/?probe=191acd1645) | Dec 14, 2021 |
| Acer          | Aspire 4352                 | [f87ff266d6](https://linux-hardware.org/?probe=f87ff266d6) | Dec 13, 2021 |
| Acer          | Aspire 4352                 | [38f2bc6cc7](https://linux-hardware.org/?probe=38f2bc6cc7) | Dec 13, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [2e8509fb8b](https://linux-hardware.org/?probe=2e8509fb8b) | Dec 12, 2021 |
| Dell          | Inspiron 5570               | [1bed203660](https://linux-hardware.org/?probe=1bed203660) | Dec 12, 2021 |
| Timi          | TM1612                      | [1179aed154](https://linux-hardware.org/?probe=1179aed154) | Dec 12, 2021 |
| Dell          | Latitude E5400              | [3ce40a821b](https://linux-hardware.org/?probe=3ce40a821b) | Dec 09, 2021 |
| Gateway       | NE511                       | [ca37375600](https://linux-hardware.org/?probe=ca37375600) | Dec 09, 2021 |
| Lenovo        | ThinkPad E550 20DF002YUS    | [1533118145](https://linux-hardware.org/?probe=1533118145) | Dec 09, 2021 |
| HONOR         | NBR-WAX9                    | [e4edda2131](https://linux-hardware.org/?probe=e4edda2131) | Dec 08, 2021 |
| Lenovo        | ThinkPad W520 4284D47       | [a48239fba8](https://linux-hardware.org/?probe=a48239fba8) | Dec 08, 2021 |
| HUAWEI        | HVY-WXX9                    | [89330570db](https://linux-hardware.org/?probe=89330570db) | Dec 07, 2021 |
| HUAWEI        | HVY-WXX9                    | [7ff7601d59](https://linux-hardware.org/?probe=7ff7601d59) | Dec 07, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | [3f2487b1a6](https://linux-hardware.org/?probe=3f2487b1a6) | Dec 07, 2021 |
| Dell          | Vostro 3405                 | [b2dc2ac6b8](https://linux-hardware.org/?probe=b2dc2ac6b8) | Dec 05, 2021 |
| Lenovo        | G50-45 80E3                 | [cf43f05660](https://linux-hardware.org/?probe=cf43f05660) | Dec 03, 2021 |
| HP            | Laptop 15-db0xxx            | [4993feea8f](https://linux-hardware.org/?probe=4993feea8f) | Dec 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4855fe75cb](https://linux-hardware.org/?probe=4855fe75cb) | Dec 01, 2021 |
| HP            | Pavilion dv5                | [71ea9a6485](https://linux-hardware.org/?probe=71ea9a6485) | Nov 30, 2021 |
| HUAWEI        | HVY-WXX9                    | [c6289480ca](https://linux-hardware.org/?probe=c6289480ca) | Nov 27, 2021 |
| HUAWEI        | HVY-WXX9                    | [7569ef6338](https://linux-hardware.org/?probe=7569ef6338) | Nov 26, 2021 |
| Dell          | Latitude 3520               | [dfb19a422e](https://linux-hardware.org/?probe=dfb19a422e) | Nov 25, 2021 |
| Dell          | Latitude 3520               | [a0271563a5](https://linux-hardware.org/?probe=a0271563a5) | Nov 25, 2021 |
| Dell          | Inspiron 3505               | [9d28cad38c](https://linux-hardware.org/?probe=9d28cad38c) | Nov 24, 2021 |
| Alienware     | m15 R6                      | [7a71325757](https://linux-hardware.org/?probe=7a71325757) | Nov 24, 2021 |
| HP            | Laptop 15-da2xxx            | [eade5e3428](https://linux-hardware.org/?probe=eade5e3428) | Nov 24, 2021 |
| HP            | EliteBook 8460p             | [8278dcbd86](https://linux-hardware.org/?probe=8278dcbd86) | Nov 23, 2021 |
| MSI           | Prestige 14Evo A11M         | [ecc3ddf24a](https://linux-hardware.org/?probe=ecc3ddf24a) | Nov 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [af11f87974](https://linux-hardware.org/?probe=af11f87974) | Nov 22, 2021 |
| HP            | Laptop 14-cm0xxx            | [55e4412774](https://linux-hardware.org/?probe=55e4412774) | Nov 20, 2021 |
| Lenovo        | G475 20080                  | [98bc985284](https://linux-hardware.org/?probe=98bc985284) | Nov 18, 2021 |
| Dell          | System XPS L502X            | [8d247d71f2](https://linux-hardware.org/?probe=8d247d71f2) | Nov 17, 2021 |
| HP            | ENVY m7 Notebook            | [4b101cc132](https://linux-hardware.org/?probe=4b101cc132) | Nov 17, 2021 |
| Sony          | VPCF236FM                   | [70cffc5595](https://linux-hardware.org/?probe=70cffc5595) | Nov 16, 2021 |
| Dell          | Latitude E6400              | [e86a11de03](https://linux-hardware.org/?probe=e86a11de03) | Nov 15, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [5df470b888](https://linux-hardware.org/?probe=5df470b888) | Nov 15, 2021 |
| HP            | Pavilion g4                 | [e82daa0aba](https://linux-hardware.org/?probe=e82daa0aba) | Nov 13, 2021 |
| HP            | Pavilion g4                 | [ec71ab6f0c](https://linux-hardware.org/?probe=ec71ab6f0c) | Nov 12, 2021 |
| Dell          | Inspiron 1501               | [94ca9e7f47](https://linux-hardware.org/?probe=94ca9e7f47) | Nov 12, 2021 |
| Sony          | SVF14211CLB                 | [7c0dacdd54](https://linux-hardware.org/?probe=7c0dacdd54) | Nov 10, 2021 |
| Sony          | SVF14211CLB                 | [fdfd650fcc](https://linux-hardware.org/?probe=fdfd650fcc) | Nov 10, 2021 |
| HP            | ProBook 645 G2              | [beada5c26b](https://linux-hardware.org/?probe=beada5c26b) | Nov 09, 2021 |
| HP            | ProBook 645 G2              | [64b38adff8](https://linux-hardware.org/?probe=64b38adff8) | Nov 09, 2021 |
| HP            | Laptop 15-dy1xxx            | [e019dfb216](https://linux-hardware.org/?probe=e019dfb216) | Nov 09, 2021 |
| Dell          | XPS 15 9570                 | [a990ce7acd](https://linux-hardware.org/?probe=a990ce7acd) | Nov 08, 2021 |
| Sony          | VPCF236FM                   | [dda9f712f8](https://linux-hardware.org/?probe=dda9f712f8) | Nov 07, 2021 |
| Unknown       | Unknown                     | [38d3058206](https://linux-hardware.org/?probe=38d3058206) | Nov 05, 2021 |
| Unknown       | Unknown                     | [c78a5c81b2](https://linux-hardware.org/?probe=c78a5c81b2) | Nov 05, 2021 |
| Sony          | VPCEG23EL                   | [cc967c03fb](https://linux-hardware.org/?probe=cc967c03fb) | Nov 05, 2021 |
| ASUSTek       | T100TA                      | [7ac20ab25f](https://linux-hardware.org/?probe=7ac20ab25f) | Nov 03, 2021 |
| ASUSTek       | T100TA                      | [fa6b87b50d](https://linux-hardware.org/?probe=fa6b87b50d) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [d7c67d8ce7](https://linux-hardware.org/?probe=d7c67d8ce7) | Nov 02, 2021 |
| System76      | Gazelle                     | [09a256c5ae](https://linux-hardware.org/?probe=09a256c5ae) | Nov 02, 2021 |
| System76      | Gazelle                     | [09da0264ca](https://linux-hardware.org/?probe=09da0264ca) | Nov 01, 2021 |
| Gateway       | NV42                        | [8f46bc202f](https://linux-hardware.org/?probe=8f46bc202f) | Nov 01, 2021 |
| Toshiba       | Satellite P105              | [1b17b5c927](https://linux-hardware.org/?probe=1b17b5c927) | Oct 31, 2021 |
| Toshiba       | Satellite P105              | [8f6268031e](https://linux-hardware.org/?probe=8f6268031e) | Oct 31, 2021 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [2fca11cf26](https://linux-hardware.org/?probe=2fca11cf26) | Oct 31, 2021 |
| Dell          | Inspiron 3537               | [0812a6b105](https://linux-hardware.org/?probe=0812a6b105) | Oct 29, 2021 |
| Dell          | Inspiron 3537               | [0e2d73ad29](https://linux-hardware.org/?probe=0e2d73ad29) | Oct 29, 2021 |
| HP            | Laptop 17z-ca300            | [0071faabac](https://linux-hardware.org/?probe=0071faabac) | Oct 29, 2021 |
| HP            | Notebook                    | [0ba26ccc72](https://linux-hardware.org/?probe=0ba26ccc72) | Oct 28, 2021 |
| Dell          | Studio 1535                 | [69dc8fefa7](https://linux-hardware.org/?probe=69dc8fefa7) | Oct 27, 2021 |
| Dell          | Studio 1535                 | [3779b20704](https://linux-hardware.org/?probe=3779b20704) | Oct 27, 2021 |
| HP            | ENVY m7 Notebook            | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| HP            | Laptop 15-db0xxx            | [57be86b920](https://linux-hardware.org/?probe=57be86b920) | Oct 24, 2021 |
| Dell          | Inspiron 1545               | [e8e9a85406](https://linux-hardware.org/?probe=e8e9a85406) | Oct 23, 2021 |
| HP            | 240 G4 Notebook PC          | [b4cd0bde35](https://linux-hardware.org/?probe=b4cd0bde35) | Oct 23, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [20123f6b2f](https://linux-hardware.org/?probe=20123f6b2f) | Oct 23, 2021 |
| Dell          | Inspiron 1545               | [172b30ebe0](https://linux-hardware.org/?probe=172b30ebe0) | Oct 23, 2021 |
| Dell          | Latitude 5400               | [6a14ed2d5e](https://linux-hardware.org/?probe=6a14ed2d5e) | Oct 21, 2021 |
| HP            | Pavilion dv5                | [74cee5b7a8](https://linux-hardware.org/?probe=74cee5b7a8) | Oct 20, 2021 |
| Acer          | Aspire V5-122P              | [14086a6760](https://linux-hardware.org/?probe=14086a6760) | Oct 19, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [90aa462368](https://linux-hardware.org/?probe=90aa462368) | Oct 18, 2021 |
| Acer          | Aspire E5-523               | [fb8d7a6a25](https://linux-hardware.org/?probe=fb8d7a6a25) | Oct 18, 2021 |
| HP            | Compaq Presario CQ50        | [bb34275819](https://linux-hardware.org/?probe=bb34275819) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [b4c6139d09](https://linux-hardware.org/?probe=b4c6139d09) | Oct 17, 2021 |
| Sony          | SVE14A15FLB                 | [22a4b460cc](https://linux-hardware.org/?probe=22a4b460cc) | Oct 14, 2021 |
| Acer          | Aspire A514-53              | [ef16468238](https://linux-hardware.org/?probe=ef16468238) | Oct 13, 2021 |
| Sony          | SVE14A15FLB                 | [51170d9250](https://linux-hardware.org/?probe=51170d9250) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Apple         | MacBookPro8,1               | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [bdc66de1e6](https://linux-hardware.org/?probe=bdc66de1e6) | Oct 11, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [90dd918da6](https://linux-hardware.org/?probe=90dd918da6) | Oct 11, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [0562199997](https://linux-hardware.org/?probe=0562199997) | Oct 11, 2021 |
| HP            | EliteBook 820 G2            | [96da43b986](https://linux-hardware.org/?probe=96da43b986) | Oct 11, 2021 |
| Toshiba       | Satellite A215              | [06c3b56836](https://linux-hardware.org/?probe=06c3b56836) | Oct 11, 2021 |
| ASUSTek       | N61Jq                       | [2307cb57c4](https://linux-hardware.org/?probe=2307cb57c4) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [55ec005acb](https://linux-hardware.org/?probe=55ec005acb) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Alienware     | 17 R4                       | [564dd05308](https://linux-hardware.org/?probe=564dd05308) | Oct 04, 2021 |
| Alienware     | 17 R4                       | [01f8341213](https://linux-hardware.org/?probe=01f8341213) | Oct 04, 2021 |
| Lenovo        | ThinkPad X220 4291T5Q       | [d31646221c](https://linux-hardware.org/?probe=d31646221c) | Oct 04, 2021 |
| ASUSTek       | X455LD                      | [70b6961d1d](https://linux-hardware.org/?probe=70b6961d1d) | Oct 03, 2021 |
| ASUSTek       | X455LD                      | [7587f9b825](https://linux-hardware.org/?probe=7587f9b825) | Oct 03, 2021 |
| ASUSTek       | T102HA                      | [0a301456dc](https://linux-hardware.org/?probe=0a301456dc) | Oct 03, 2021 |
| ASUSTek       | T102HA                      | [16e83f5564](https://linux-hardware.org/?probe=16e83f5564) | Oct 03, 2021 |
| MSI           | GE72 6QD                    | [a8713aca99](https://linux-hardware.org/?probe=a8713aca99) | Oct 01, 2021 |
| Eluktronic... | RP-15                       | [c147de5b16](https://linux-hardware.org/?probe=c147de5b16) | Sep 30, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [2692ea7a93](https://linux-hardware.org/?probe=2692ea7a93) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| Dell          | Latitude 5491               | [197b1a5c35](https://linux-hardware.org/?probe=197b1a5c35) | Sep 29, 2021 |
| Sony          | VGN-NR330FE                 | [9222a5b0bf](https://linux-hardware.org/?probe=9222a5b0bf) | Sep 26, 2021 |
| Sony          | VGN-NR330FE                 | [4e7013363c](https://linux-hardware.org/?probe=4e7013363c) | Sep 26, 2021 |
| Lenovo        | G50-45 80E3                 | [72bee59f14](https://linux-hardware.org/?probe=72bee59f14) | Sep 26, 2021 |
| Dell          | Latitude E6440              | [940e015781](https://linux-hardware.org/?probe=940e015781) | Sep 24, 2021 |
| Dell          | Latitude E6440              | [3b8c430d4d](https://linux-hardware.org/?probe=3b8c430d4d) | Sep 24, 2021 |
| Google        | Ekko                        | [8760e0b36c](https://linux-hardware.org/?probe=8760e0b36c) | Sep 24, 2021 |
| Google        | Ekko                        | [0d6d5cc44a](https://linux-hardware.org/?probe=0d6d5cc44a) | Sep 23, 2021 |
| EVOO          | EG-LP10                     | [e6ab927226](https://linux-hardware.org/?probe=e6ab927226) | Sep 22, 2021 |
| Dell          | Latitude E6440              | [45f88af089](https://linux-hardware.org/?probe=45f88af089) | Sep 22, 2021 |
| Dell          | Latitude E6440              | [28a8dacd93](https://linux-hardware.org/?probe=28a8dacd93) | Sep 22, 2021 |
| Sony          | VGN-CR360FE                 | [db32680a97](https://linux-hardware.org/?probe=db32680a97) | Sep 22, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [2d0d73c751](https://linux-hardware.org/?probe=2d0d73c751) | Sep 19, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [a2bbae72c0](https://linux-hardware.org/?probe=a2bbae72c0) | Sep 18, 2021 |
| Toshiba       | Satellite L15W-B            | [3871a3c4fc](https://linux-hardware.org/?probe=3871a3c4fc) | Sep 18, 2021 |
| Acer          | AO751h                      | [d217a1c6b7](https://linux-hardware.org/?probe=d217a1c6b7) | Sep 18, 2021 |
| Dell          | Inspiron 5577               | [3c89bcae88](https://linux-hardware.org/?probe=3c89bcae88) | Sep 18, 2021 |
| Acer          | Aspire E5-551               | [223b8d9942](https://linux-hardware.org/?probe=223b8d9942) | Sep 18, 2021 |
| Dell          | Precision 5540              | [5f6d259dce](https://linux-hardware.org/?probe=5f6d259dce) | Sep 18, 2021 |
| Dell          | XPS 15 9570                 | [cc48078a68](https://linux-hardware.org/?probe=cc48078a68) | Sep 16, 2021 |
| Sony          | VGN-CS140F                  | [a7e19c8a44](https://linux-hardware.org/?probe=a7e19c8a44) | Sep 16, 2021 |
| Lenovo        | B40-45 20394                | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP            | Notebook                    | [c3bcf38e50](https://linux-hardware.org/?probe=c3bcf38e50) | Sep 15, 2021 |
| Acer          | Aspire 5733Z                | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Mini 110-3500               | [a4dd2b26bf](https://linux-hardware.org/?probe=a4dd2b26bf) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [69338ada32](https://linux-hardware.org/?probe=69338ada32) | Sep 12, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [57f772fc9f](https://linux-hardware.org/?probe=57f772fc9f) | Sep 12, 2021 |
| Sony          | VPCCW25FL                   | [5dcd7a6c93](https://linux-hardware.org/?probe=5dcd7a6c93) | Sep 12, 2021 |
| ASUSTek       | U56E                        | [99bd7dbfdf](https://linux-hardware.org/?probe=99bd7dbfdf) | Sep 09, 2021 |
| HP            | G60                         | [065e03350f](https://linux-hardware.org/?probe=065e03350f) | Sep 09, 2021 |
| HP            | G60                         | [4d35031cdf](https://linux-hardware.org/?probe=4d35031cdf) | Sep 09, 2021 |
| Acer          | Aspire 4752                 | [f11003a698](https://linux-hardware.org/?probe=f11003a698) | Sep 08, 2021 |
| Acer          | Aspire 4752                 | [cb8ee015c6](https://linux-hardware.org/?probe=cb8ee015c6) | Sep 08, 2021 |
| Samsung       | 550P5C/550P7C               | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Gateway       | NV55C                       | [1515d7dfbf](https://linux-hardware.org/?probe=1515d7dfbf) | Sep 06, 2021 |
| Apple         | MacBookPro9,1               | [78f1531e54](https://linux-hardware.org/?probe=78f1531e54) | Sep 05, 2021 |
| Apple         | MacBookPro9,1               | [d306a73462](https://linux-hardware.org/?probe=d306a73462) | Sep 05, 2021 |
| Apple         | MacBookPro12,1              | [b3c5e46b4d](https://linux-hardware.org/?probe=b3c5e46b4d) | Sep 04, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | [4115bc0195](https://linux-hardware.org/?probe=4115bc0195) | Sep 03, 2021 |
| Acer          | Aspire E1-522               | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Sony          | SVE14A15FLB                 | [b49abbf4c8](https://linux-hardware.org/?probe=b49abbf4c8) | Sep 01, 2021 |
| HP            | Laptop 15-bs0xx             | [fc0f8f406b](https://linux-hardware.org/?probe=fc0f8f406b) | Aug 31, 2021 |
| Toshiba       | Satellite A215              | [2d0d778e8e](https://linux-hardware.org/?probe=2d0d778e8e) | Aug 31, 2021 |
| Toshiba       | Satellite A215              | [3140742cd5](https://linux-hardware.org/?probe=3140742cd5) | Aug 31, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e134361dc2](https://linux-hardware.org/?probe=e134361dc2) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [cf69bd4423](https://linux-hardware.org/?probe=cf69bd4423) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [b409334e94](https://linux-hardware.org/?probe=b409334e94) | Aug 30, 2021 |
| HP            | ProBook 440 G3              | [c4b5fdc75f](https://linux-hardware.org/?probe=c4b5fdc75f) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| HP            | 2000                        | [c1d490dc62](https://linux-hardware.org/?probe=c1d490dc62) | Aug 29, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [d8daca96d1](https://linux-hardware.org/?probe=d8daca96d1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire E5-521               | [5716a5328f](https://linux-hardware.org/?probe=5716a5328f) | Aug 28, 2021 |
| HUAWEI        | WRT-WX9                     | [e1e5a14c77](https://linux-hardware.org/?probe=e1e5a14c77) | Aug 25, 2021 |
| Toshiba       | Satellite A215              | [5899e10002](https://linux-hardware.org/?probe=5899e10002) | Aug 25, 2021 |
| Dell          | Inspiron 5577               | [27ba1b6422](https://linux-hardware.org/?probe=27ba1b6422) | Aug 25, 2021 |
| Dell          | Inspiron 5577               | [cfc2b9442c](https://linux-hardware.org/?probe=cfc2b9442c) | Aug 25, 2021 |
| Lenovo        | B40-45 20394                | [3d74a16440](https://linux-hardware.org/?probe=3d74a16440) | Aug 25, 2021 |
| Lenovo        | B40-45 20394                | [551749a1af](https://linux-hardware.org/?probe=551749a1af) | Aug 25, 2021 |
| HP            | Laptop 14-cm0xxx            | [df0fa8e968](https://linux-hardware.org/?probe=df0fa8e968) | Aug 24, 2021 |
| HP            | 245 G7 Notebook PC          | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP            | 245 G7 Notebook PC          | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [01fadd29fd](https://linux-hardware.org/?probe=01fadd29fd) | Aug 23, 2021 |
| ASUSTek       | X455LA                      | [d40617b08b](https://linux-hardware.org/?probe=d40617b08b) | Aug 22, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [0d33aed04c](https://linux-hardware.org/?probe=0d33aed04c) | Aug 19, 2021 |
| Dell          | Inspiron 5559               | [004298137f](https://linux-hardware.org/?probe=004298137f) | Aug 17, 2021 |
| HP            | Notebook                    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP            | Notebook                    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [41e2825c3d](https://linux-hardware.org/?probe=41e2825c3d) | Aug 15, 2021 |
| Dell          | XPS 15 9570                 | [3a677218c5](https://linux-hardware.org/?probe=3a677218c5) | Aug 14, 2021 |
| HP            | ProBook 440 G3              | [e93a65b9cf](https://linux-hardware.org/?probe=e93a65b9cf) | Aug 14, 2021 |
| HP            | Notebook                    | [53235618da](https://linux-hardware.org/?probe=53235618da) | Aug 13, 2021 |
| Lenovo        | ThinkPad R61/R61i 7733AY... | [b074276477](https://linux-hardware.org/?probe=b074276477) | Aug 13, 2021 |
| HP            | ProBook 645 G1              | [38105c93e2](https://linux-hardware.org/?probe=38105c93e2) | Aug 13, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [c6acb13b5c](https://linux-hardware.org/?probe=c6acb13b5c) | Aug 12, 2021 |
| Apple         | MacBookPro9,2               | [10a9ce514b](https://linux-hardware.org/?probe=10a9ce514b) | Aug 11, 2021 |
| Apple         | MacBookPro9,2               | [4a08b4bc9c](https://linux-hardware.org/?probe=4a08b4bc9c) | Aug 11, 2021 |
| Samsung       | R530/R730                   | [3c4eb18a66](https://linux-hardware.org/?probe=3c4eb18a66) | Aug 11, 2021 |
| Acer          | Aspire 5742Z                | [dd55e4423e](https://linux-hardware.org/?probe=dd55e4423e) | Aug 11, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [538a15f3cc](https://linux-hardware.org/?probe=538a15f3cc) | Aug 09, 2021 |
| Dell          | Precision M6600             | [58b77bf05d](https://linux-hardware.org/?probe=58b77bf05d) | Aug 09, 2021 |
| HP            | 240 G6 Notebook PC          | [1344db8d42](https://linux-hardware.org/?probe=1344db8d42) | Aug 08, 2021 |
| HP            | 240 G6 Notebook PC          | [261f5fbbe7](https://linux-hardware.org/?probe=261f5fbbe7) | Aug 08, 2021 |
| Sony          | VPCS110FL                   | [2227fd7ae7](https://linux-hardware.org/?probe=2227fd7ae7) | Aug 07, 2021 |
| Sony          | VPCS110FL                   | [1741c7d3db](https://linux-hardware.org/?probe=1741c7d3db) | Aug 07, 2021 |
| Apple         | MacBookPro9,2               | [f4e31f03fb](https://linux-hardware.org/?probe=f4e31f03fb) | Aug 07, 2021 |
| ASUSTek       | X550CA                      | [a1e7efd7c1](https://linux-hardware.org/?probe=a1e7efd7c1) | Aug 07, 2021 |
| ASUSTek       | GL502VS                     | [921dd6e763](https://linux-hardware.org/?probe=921dd6e763) | Aug 07, 2021 |
| Sony          | VPCF236FM                   | [01a2971d58](https://linux-hardware.org/?probe=01a2971d58) | Aug 06, 2021 |
| Lenovo        | Z40-70 20366                | [506d99ad35](https://linux-hardware.org/?probe=506d99ad35) | Aug 05, 2021 |
| ASUSTek       | G750JZ                      | [f35df8640b](https://linux-hardware.org/?probe=f35df8640b) | Aug 02, 2021 |
| ASUSTek       | X556URK                     | [39508e15e9](https://linux-hardware.org/?probe=39508e15e9) | Aug 02, 2021 |
| Toshiba       | Satellite L855              | [8a2a8de791](https://linux-hardware.org/?probe=8a2a8de791) | Aug 01, 2021 |
| Dell          | Latitude 7400               | [f726a607ca](https://linux-hardware.org/?probe=f726a607ca) | Aug 01, 2021 |
| Acer          | Aspire V3-572P              | [b2fb71990b](https://linux-hardware.org/?probe=b2fb71990b) | Jul 31, 2021 |
| Lenovo        | G50-30 80G0                 | [79adcd22d0](https://linux-hardware.org/?probe=79adcd22d0) | Jul 31, 2021 |
| Toshiba       | Satellite S40Dt-A           | [25911158d3](https://linux-hardware.org/?probe=25911158d3) | Jul 31, 2021 |
| Dell          | Inspiron 5558               | [c7392e540f](https://linux-hardware.org/?probe=c7392e540f) | Jul 31, 2021 |
| Dell          | Inspiron 5558               | [f9ab524654](https://linux-hardware.org/?probe=f9ab524654) | Jul 31, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [07d66d0963](https://linux-hardware.org/?probe=07d66d0963) | Jul 30, 2021 |
| Toshiba       | Satellite L855              | [354b3bf7c6](https://linux-hardware.org/?probe=354b3bf7c6) | Jul 30, 2021 |
| Lenovo        | ThinkPad P50 20ENA00PLM     | [3b6f4346e5](https://linux-hardware.org/?probe=3b6f4346e5) | Jul 29, 2021 |
| ASUSTek       | UX31E                       | [af97b2b4d4](https://linux-hardware.org/?probe=af97b2b4d4) | Jul 29, 2021 |
| Lenovo        | G450 2949                   | [fcdd9d6dd7](https://linux-hardware.org/?probe=fcdd9d6dd7) | Jul 29, 2021 |
| Dell          | Inspiron 14-3467            | [a5b40bdc89](https://linux-hardware.org/?probe=a5b40bdc89) | Jul 28, 2021 |
| Dell          | Vostro 3400                 | [a95b01dfee](https://linux-hardware.org/?probe=a95b01dfee) | Jul 27, 2021 |
| Dell          | Precision M6600             | [67a1d8b2e4](https://linux-hardware.org/?probe=67a1d8b2e4) | Jul 27, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Acer          | Aspire A514-53              | [ce59a5d66a](https://linux-hardware.org/?probe=ce59a5d66a) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [6d6a97729d](https://linux-hardware.org/?probe=6d6a97729d) | Jul 21, 2021 |
| Toshiba       | Satellite S855              | [fd91905dbd](https://linux-hardware.org/?probe=fd91905dbd) | Jul 20, 2021 |
| Google        | Gnawty                      | [146da98e30](https://linux-hardware.org/?probe=146da98e30) | Jul 19, 2021 |
| Dell          | Inspiron 1520               | [b842c5ba03](https://linux-hardware.org/?probe=b842c5ba03) | Jul 19, 2021 |
| Dell          | Vostro 3400                 | [350080b7d5](https://linux-hardware.org/?probe=350080b7d5) | Jul 17, 2021 |
| Dell          | Latitude E6430              | [a0d9dec751](https://linux-hardware.org/?probe=a0d9dec751) | Jul 17, 2021 |
| Dell          | XPS 15 9550                 | [1183f6f39b](https://linux-hardware.org/?probe=1183f6f39b) | Jul 16, 2021 |
| Acer          | Aspire A514-53              | [035d8c290f](https://linux-hardware.org/?probe=035d8c290f) | Jul 15, 2021 |
| Acer          | Aspire A514-53              | [d41390ad39](https://linux-hardware.org/?probe=d41390ad39) | Jul 15, 2021 |
| Lenovo        | Y50-70 20378                | [4544d706e3](https://linux-hardware.org/?probe=4544d706e3) | Jul 14, 2021 |
| Lenovo        | Y50-70 20378                | [fa38a3ca0b](https://linux-hardware.org/?probe=fa38a3ca0b) | Jul 14, 2021 |
| Lenovo        | ThinkPad T490 20N3S5DV14    | [85acf9a5a3](https://linux-hardware.org/?probe=85acf9a5a3) | Jul 13, 2021 |
| Dell          | Latitude E6430              | [089735a3b4](https://linux-hardware.org/?probe=089735a3b4) | Jul 11, 2021 |
| Samsung       | N145P/N250P/N260P           | [e60ff3401a](https://linux-hardware.org/?probe=e60ff3401a) | Jul 11, 2021 |
| Lenovo        | G475 20080                  | [df7fc44231](https://linux-hardware.org/?probe=df7fc44231) | Jul 10, 2021 |
| Samsung       | 520U4C/520U4X               | [356e4d7151](https://linux-hardware.org/?probe=356e4d7151) | Jul 09, 2021 |
| Lenovo        | G475 20080                  | [3c28da8576](https://linux-hardware.org/?probe=3c28da8576) | Jul 09, 2021 |
| HP            | Pavilion dv2000 (RX563LA... | [ad42c0a861](https://linux-hardware.org/?probe=ad42c0a861) | Jul 08, 2021 |
| Dell          | Latitude E6430              | [516ee82d3c](https://linux-hardware.org/?probe=516ee82d3c) | Jul 07, 2021 |
| Dell          | Latitude E6430              | [b7854a10bf](https://linux-hardware.org/?probe=b7854a10bf) | Jul 07, 2021 |
| HP            | EliteBook Folio 1040 G3     | [8c12c26efd](https://linux-hardware.org/?probe=8c12c26efd) | Jul 06, 2021 |
| Dell          | Inspiron 5521               | [f2ab6f6a6f](https://linux-hardware.org/?probe=f2ab6f6a6f) | Jul 05, 2021 |
| Dell          | Inspiron 5521               | [260f6cb321](https://linux-hardware.org/?probe=260f6cb321) | Jul 05, 2021 |
| Lanix         | A V16                       | [98fb8de3e2](https://linux-hardware.org/?probe=98fb8de3e2) | Jul 05, 2021 |
| Dell          | Latitude 5480               | [9d6aca71eb](https://linux-hardware.org/?probe=9d6aca71eb) | Jul 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [e39ebb5e0f](https://linux-hardware.org/?probe=e39ebb5e0f) | Jul 04, 2021 |
| HP            | Pavilion dv2000 (RX563LA... | [7288eb9051](https://linux-hardware.org/?probe=7288eb9051) | Jul 04, 2021 |
| Acer          | Aspire 5250                 | [fd1b061559](https://linux-hardware.org/?probe=fd1b061559) | Jul 04, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [4d4b243c17](https://linux-hardware.org/?probe=4d4b243c17) | Jul 04, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [41837d1bed](https://linux-hardware.org/?probe=41837d1bed) | Jul 04, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [aea8fb485e](https://linux-hardware.org/?probe=aea8fb485e) | Jul 04, 2021 |
| HP            | Pavilion 11                 | [02856a7ef0](https://linux-hardware.org/?probe=02856a7ef0) | Jul 03, 2021 |
| HP            | Mini 110-3500               | [f7b35a9834](https://linux-hardware.org/?probe=f7b35a9834) | Jun 30, 2021 |
| Lanix         | A V16                       | [221857ee7e](https://linux-hardware.org/?probe=221857ee7e) | Jun 30, 2021 |
| Dell          | G7 7588                     | [c053b00ac1](https://linux-hardware.org/?probe=c053b00ac1) | Jun 29, 2021 |
| HP            | EliteBook 8460p             | [463c88f144](https://linux-hardware.org/?probe=463c88f144) | Jun 23, 2021 |
| Lenovo        | ThinkPad T420 42363S6       | [9689bef600](https://linux-hardware.org/?probe=9689bef600) | Jun 21, 2021 |
| Dell          | Inspiron 7348               | [52a2e0d342](https://linux-hardware.org/?probe=52a2e0d342) | Jun 18, 2021 |
| HP            | EliteBook 8460p             | [890fd61ee1](https://linux-hardware.org/?probe=890fd61ee1) | Jun 15, 2021 |
| HP            | Pavilion Notebook           | [752fc58f56](https://linux-hardware.org/?probe=752fc58f56) | Jun 14, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [11f773ff99](https://linux-hardware.org/?probe=11f773ff99) | Jun 14, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [0ba47d5ae1](https://linux-hardware.org/?probe=0ba47d5ae1) | Jun 14, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [b86630050e](https://linux-hardware.org/?probe=b86630050e) | Jun 14, 2021 |
| HP            | 14                          | [f6f78edde4](https://linux-hardware.org/?probe=f6f78edde4) | Jun 14, 2021 |
| HP            | EliteBook 8460p             | [e034952cce](https://linux-hardware.org/?probe=e034952cce) | Jun 13, 2021 |
| MSI           | GT70 2OC/2OD                | [fab3d5dbf8](https://linux-hardware.org/?probe=fab3d5dbf8) | Jun 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [0dde07f321](https://linux-hardware.org/?probe=0dde07f321) | Jun 11, 2021 |
| HP            | EliteBook 8460p             | [7fdea263ce](https://linux-hardware.org/?probe=7fdea263ce) | Jun 11, 2021 |
| HP            | EliteBook 8460p             | [52f443990e](https://linux-hardware.org/?probe=52f443990e) | Jun 11, 2021 |
| Lenovo        | ThinkPad T460 20FMA0GALM    | [1499d1854d](https://linux-hardware.org/?probe=1499d1854d) | Jun 10, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [abd01e8eac](https://linux-hardware.org/?probe=abd01e8eac) | Jun 09, 2021 |
| Sony          | VPCF236FM                   | [91ec4b799a](https://linux-hardware.org/?probe=91ec4b799a) | Jun 07, 2021 |
| HP            | Compaq 6735b                | [0188c881d6](https://linux-hardware.org/?probe=0188c881d6) | Jun 06, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0A01... | [818682d156](https://linux-hardware.org/?probe=818682d156) | Jun 06, 2021 |
| HP            | Mini 110-1100               | [dcaac9d2ce](https://linux-hardware.org/?probe=dcaac9d2ce) | Jun 04, 2021 |
| HP            | Mini 110-1100               | [d919b139c6](https://linux-hardware.org/?probe=d919b139c6) | Jun 04, 2021 |
| Dell          | Inspiron 3505               | [fe512b6857](https://linux-hardware.org/?probe=fe512b6857) | Jun 04, 2021 |
| Dell          | Vostro 3400                 | [6e49963b0f](https://linux-hardware.org/?probe=6e49963b0f) | Jun 03, 2021 |
| HP            | 240 G4 Notebook PC          | [e47851b0ed](https://linux-hardware.org/?probe=e47851b0ed) | Jun 01, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [51b5746d72](https://linux-hardware.org/?probe=51b5746d72) | Jun 01, 2021 |
| HP            | 240 G4 Notebook PC          | [0a9b2c114f](https://linux-hardware.org/?probe=0a9b2c114f) | Jun 01, 2021 |
| Alienware     | 17 R4                       | [cc69851e7f](https://linux-hardware.org/?probe=cc69851e7f) | May 31, 2021 |
| Dell          | Inspiron 5558               | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| ASUSTek       | TP501UAM                    | [b0c32b29bb](https://linux-hardware.org/?probe=b0c32b29bb) | May 30, 2021 |
| Lenovo        | ThinkPad T420 42366Y0       | [74547808d3](https://linux-hardware.org/?probe=74547808d3) | May 30, 2021 |
| Dell          | Inspiron 11 - 3147          | [8efeef8292](https://linux-hardware.org/?probe=8efeef8292) | May 30, 2021 |
| Lenovo        | ThinkPad T420 42366Y0       | [d36582d3d6](https://linux-hardware.org/?probe=d36582d3d6) | May 29, 2021 |
| HP            | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| Lenovo        | G50-30 80G0                 | [4c8e456405](https://linux-hardware.org/?probe=4c8e456405) | May 29, 2021 |
| HP            | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [bac9935f0b](https://linux-hardware.org/?probe=bac9935f0b) | May 28, 2021 |
| HP            | ProBook 4530s               | [f583d8f959](https://linux-hardware.org/?probe=f583d8f959) | May 27, 2021 |
| HP            | ProBook 4530s               | [f40e368515](https://linux-hardware.org/?probe=f40e368515) | May 27, 2021 |
| Acer          | Aspire E5-573               | [2427d069a8](https://linux-hardware.org/?probe=2427d069a8) | May 27, 2021 |
| Apple         | MacBookPro7,1               | [85073cea15](https://linux-hardware.org/?probe=85073cea15) | May 25, 2021 |
| Apple         | MacBookPro7,1               | [e1730dafc1](https://linux-hardware.org/?probe=e1730dafc1) | May 25, 2021 |
| ASUSTek       | TP501UAM                    | [0573e97043](https://linux-hardware.org/?probe=0573e97043) | May 25, 2021 |
| ASUSTek       | TP501UAM                    | [7acd82dc46](https://linux-hardware.org/?probe=7acd82dc46) | May 25, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [8b7eea5d26](https://linux-hardware.org/?probe=8b7eea5d26) | May 25, 2021 |
| MSI           | GF63 Thin 10SCSR            | [f5d60039e2](https://linux-hardware.org/?probe=f5d60039e2) | May 24, 2021 |
| HP            | Compaq 6735b                | [9a0f49c584](https://linux-hardware.org/?probe=9a0f49c584) | May 24, 2021 |
| HP            | Compaq 6735b                | [2e64a7319a](https://linux-hardware.org/?probe=2e64a7319a) | May 24, 2021 |
| Google        | Candy                       | [f6b5b1fd81](https://linux-hardware.org/?probe=f6b5b1fd81) | May 23, 2021 |
| Alienware     | M14xR2                      | [bf1baf508f](https://linux-hardware.org/?probe=bf1baf508f) | May 22, 2021 |
| Alienware     | M14xR2                      | [8fc65dd34f](https://linux-hardware.org/?probe=8fc65dd34f) | May 22, 2021 |
| Dell          | Inspiron 3505               | [c973055db8](https://linux-hardware.org/?probe=c973055db8) | May 20, 2021 |
| Sony          | VPCF236FM                   | [5e0b431cb8](https://linux-hardware.org/?probe=5e0b431cb8) | May 19, 2021 |
| Sony          | VPCF236FM                   | [22921fb0b7](https://linux-hardware.org/?probe=22921fb0b7) | May 16, 2021 |
| Dell          | Inspiron 5570               | [2fd333bc52](https://linux-hardware.org/?probe=2fd333bc52) | May 14, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | [0d44d30be1](https://linux-hardware.org/?probe=0d44d30be1) | May 13, 2021 |
| Apple         | MacBookPro9,2               | [1a045980ab](https://linux-hardware.org/?probe=1a045980ab) | May 13, 2021 |
| HP            | 14                          | [f1239691b2](https://linux-hardware.org/?probe=f1239691b2) | May 07, 2021 |
| Lenovo        | ThinkPad P50 20EQA0GSLM     | [c9837ef0c1](https://linux-hardware.org/?probe=c9837ef0c1) | May 07, 2021 |
| Lenovo        | ThinkPad P50 20EQA0GSLM     | [9546178741](https://linux-hardware.org/?probe=9546178741) | May 07, 2021 |
| HP            | Laptop 15-bs2xx             | [de6dfe1d67](https://linux-hardware.org/?probe=de6dfe1d67) | May 05, 2021 |
| HP            | Pavilion g4                 | [92f327db54](https://linux-hardware.org/?probe=92f327db54) | May 02, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [5fb16a0af0](https://linux-hardware.org/?probe=5fb16a0af0) | May 02, 2021 |
| Acer          | Aspire V3-574               | [3696026fc9](https://linux-hardware.org/?probe=3696026fc9) | May 01, 2021 |
| Alienware     | 17 R4                       | [b054aca191](https://linux-hardware.org/?probe=b054aca191) | May 01, 2021 |
| Dell          | Inspiron 5567               | [b6590f348d](https://linux-hardware.org/?probe=b6590f348d) | Apr 30, 2021 |
| HP            | Mini 110-3500               | [2f0cbfc23f](https://linux-hardware.org/?probe=2f0cbfc23f) | Apr 28, 2021 |
| HP            | ZBook 15 G3                 | [d9d1ea9712](https://linux-hardware.org/?probe=d9d1ea9712) | Apr 28, 2021 |
| Acer          | Aspire A315-31              | [051b60637b](https://linux-hardware.org/?probe=051b60637b) | Apr 28, 2021 |
| Lenovo        | G40-45 80E1                 | [3aa335d3bb](https://linux-hardware.org/?probe=3aa335d3bb) | Apr 28, 2021 |
| Lenovo        | G40-45 80E1                 | [489e368d37](https://linux-hardware.org/?probe=489e368d37) | Apr 27, 2021 |
| HP            | Pavilion dv4                | [40f26c8648](https://linux-hardware.org/?probe=40f26c8648) | Apr 27, 2021 |
| MSI           | GT70 2OC/2OD                | [f20d184a9c](https://linux-hardware.org/?probe=f20d184a9c) | Apr 25, 2021 |
| Acer          | Aspire V5-572               | [b1e4ebb53f](https://linux-hardware.org/?probe=b1e4ebb53f) | Apr 24, 2021 |
| Dell          | Inspiron 3421               | [8917f27d77](https://linux-hardware.org/?probe=8917f27d77) | Apr 22, 2021 |
| HP            | Pavilion Notebook           | [6f3d83062c](https://linux-hardware.org/?probe=6f3d83062c) | Apr 22, 2021 |
| Toshiba       | Satellite L305              | [c355f731bb](https://linux-hardware.org/?probe=c355f731bb) | Apr 21, 2021 |
| Toshiba       | Satellite L305              | [3e072f5d47](https://linux-hardware.org/?probe=3e072f5d47) | Apr 21, 2021 |
| Toshiba       | Satellite C55-B             | [38361bab55](https://linux-hardware.org/?probe=38361bab55) | Apr 21, 2021 |
| Acer          | AOD270                      | [e0bbdeb849](https://linux-hardware.org/?probe=e0bbdeb849) | Apr 20, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Apple         | MacBook4,1                  | [c81b5705ce](https://linux-hardware.org/?probe=c81b5705ce) | Apr 17, 2021 |
| Sony          | VPCM120AL                   | [e15b3dcfa3](https://linux-hardware.org/?probe=e15b3dcfa3) | Apr 16, 2021 |
| Acer          | Aspire V5-572               | [0e3054df28](https://linux-hardware.org/?probe=0e3054df28) | Apr 16, 2021 |
| Dell          | XPS 13 9310                 | [b722afa311](https://linux-hardware.org/?probe=b722afa311) | Apr 14, 2021 |
| Dell          | Inspiron 3505               | [50763a8b5f](https://linux-hardware.org/?probe=50763a8b5f) | Apr 14, 2021 |
| Acer          | Swift SF315-52              | [fadc8d5548](https://linux-hardware.org/?probe=fadc8d5548) | Apr 13, 2021 |
| Acer          | Swift SF315-52              | [78eb961ecd](https://linux-hardware.org/?probe=78eb961ecd) | Apr 13, 2021 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [666c09f493](https://linux-hardware.org/?probe=666c09f493) | Apr 13, 2021 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [e5008f2ec8](https://linux-hardware.org/?probe=e5008f2ec8) | Apr 13, 2021 |
| Lenovo        | ThinkPad T440p 20AWA20LL... | [c7fb55258d](https://linux-hardware.org/?probe=c7fb55258d) | Apr 12, 2021 |
| HP            | Pavilion dv4                | [e15fd6726e](https://linux-hardware.org/?probe=e15fd6726e) | Apr 12, 2021 |
| HP            | Pavilion dv5                | [2df1512442](https://linux-hardware.org/?probe=2df1512442) | Apr 12, 2021 |
| HP            | Pavilion dv5                | [963a9c98df](https://linux-hardware.org/?probe=963a9c98df) | Apr 12, 2021 |
| Dell          | Inspiron 5391               | [80bf268441](https://linux-hardware.org/?probe=80bf268441) | Apr 08, 2021 |
| Toshiba       | Satellite M505D             | [2711ae5eca](https://linux-hardware.org/?probe=2711ae5eca) | Apr 07, 2021 |
| Sony          | VGN-N350FE                  | [6900bee5ac](https://linux-hardware.org/?probe=6900bee5ac) | Apr 06, 2021 |
| Sony          | VGN-N350FE                  | [f8de549a62](https://linux-hardware.org/?probe=f8de549a62) | Apr 06, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [d4b7cef21b](https://linux-hardware.org/?probe=d4b7cef21b) | Apr 06, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [c55d72e928](https://linux-hardware.org/?probe=c55d72e928) | Apr 06, 2021 |
| ASUSTek       | N53SN                       | [94ddcfa2ea](https://linux-hardware.org/?probe=94ddcfa2ea) | Apr 05, 2021 |
| Sony          | VPCF236FM                   | [c7f9905fe5](https://linux-hardware.org/?probe=c7f9905fe5) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [4b9332ae3a](https://linux-hardware.org/?probe=4b9332ae3a) | Apr 05, 2021 |
| HP            | Pavilion 14                 | [917ffdcb82](https://linux-hardware.org/?probe=917ffdcb82) | Apr 04, 2021 |
| HP            | Pavilion 14                 | [a08fdec4d3](https://linux-hardware.org/?probe=a08fdec4d3) | Apr 04, 2021 |
| Sony          | VPCF236FM                   | [cb5204d13b](https://linux-hardware.org/?probe=cb5204d13b) | Apr 04, 2021 |
| LG Electro... | X300-L.CR31B1               | [728ce1cec3](https://linux-hardware.org/?probe=728ce1cec3) | Apr 02, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [d4a7fbec30](https://linux-hardware.org/?probe=d4a7fbec30) | Apr 01, 2021 |
| LG Electro... | X300-L.CR31B1               | [2dee5439bd](https://linux-hardware.org/?probe=2dee5439bd) | Apr 01, 2021 |
| Dell          | Vostro 3460                 | [22e8a09fcc](https://linux-hardware.org/?probe=22e8a09fcc) | Mar 31, 2021 |
| Toshiba       | Satellite L855              | [72af831ab1](https://linux-hardware.org/?probe=72af831ab1) | Mar 31, 2021 |
| Apple         | MacBook4,1                  | [74bbc27867](https://linux-hardware.org/?probe=74bbc27867) | Mar 31, 2021 |
| Lenovo        | ThinkPad Edge E431 62772... | [284e6c79de](https://linux-hardware.org/?probe=284e6c79de) | Mar 31, 2021 |
| Lenovo        | ThinkPad Edge E431 62772... | [ee8d0c801c](https://linux-hardware.org/?probe=ee8d0c801c) | Mar 30, 2021 |
| HP            | Stream Laptop 11-ah0XX      | [a2b11b405a](https://linux-hardware.org/?probe=a2b11b405a) | Mar 30, 2021 |
| Dell          | XPS 15 9550                 | [dbea4f6b5f](https://linux-hardware.org/?probe=dbea4f6b5f) | Mar 30, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [52cc42c292](https://linux-hardware.org/?probe=52cc42c292) | Mar 26, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [a54ea64f8d](https://linux-hardware.org/?probe=a54ea64f8d) | Mar 26, 2021 |
| HP            | Pavilion Notebook           | [c9b5e75a90](https://linux-hardware.org/?probe=c9b5e75a90) | Mar 26, 2021 |
| Dell          | Latitude E6430              | [a14da1e028](https://linux-hardware.org/?probe=a14da1e028) | Mar 25, 2021 |
| HP            | Pavilion 15                 | [dc6f0c2474](https://linux-hardware.org/?probe=dc6f0c2474) | Mar 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X532... | [1a538b0e45](https://linux-hardware.org/?probe=1a538b0e45) | Mar 24, 2021 |
| Dell          | Inspiron 3421               | [b977195eb4](https://linux-hardware.org/?probe=b977195eb4) | Mar 21, 2021 |
| Sony          | VPCCW25FL                   | [b0f9776d13](https://linux-hardware.org/?probe=b0f9776d13) | Mar 21, 2021 |
| Sony          | VPCCW25FL                   | [6ac0416576](https://linux-hardware.org/?probe=6ac0416576) | Mar 21, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [e8158529b3](https://linux-hardware.org/?probe=e8158529b3) | Mar 18, 2021 |
| Toshiba       | Satellite S855              | [eb315acbe4](https://linux-hardware.org/?probe=eb315acbe4) | Mar 17, 2021 |
| Dell          | Inspiron 11-3168            | [df9cba1f5c](https://linux-hardware.org/?probe=df9cba1f5c) | Mar 15, 2021 |
| Acer          | Aspire E3-112M              | [7f7af56989](https://linux-hardware.org/?probe=7f7af56989) | Mar 15, 2021 |
| Apple         | MacBookPro8,1               | [694960a902](https://linux-hardware.org/?probe=694960a902) | Mar 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [53d619550a](https://linux-hardware.org/?probe=53d619550a) | Mar 15, 2021 |
| Acer          | Aspire V5-572               | [ab7a951eb5](https://linux-hardware.org/?probe=ab7a951eb5) | Mar 15, 2021 |
| Toshiba       | Satellite L855              | [946a3afec1](https://linux-hardware.org/?probe=946a3afec1) | Mar 14, 2021 |
| Lenovo        | ThinkPad L420 7829BH2       | [db0c1fe4c4](https://linux-hardware.org/?probe=db0c1fe4c4) | Mar 13, 2021 |
| Dell          | Vostro 3700                 | [d1ece8006f](https://linux-hardware.org/?probe=d1ece8006f) | Mar 13, 2021 |
| HUAWEI        | MACHR-WX9                   | [32ddd24929](https://linux-hardware.org/?probe=32ddd24929) | Mar 13, 2021 |
| Dell          | Inspiron N5110              | [b06fd43a6e](https://linux-hardware.org/?probe=b06fd43a6e) | Mar 13, 2021 |
| Toshiba       | Satellite L855              | [3d8c77f6fc](https://linux-hardware.org/?probe=3d8c77f6fc) | Mar 12, 2021 |
| Dell          | Inspiron 3505               | [3870b0a8b0](https://linux-hardware.org/?probe=3870b0a8b0) | Mar 11, 2021 |
| Toshiba       | Satellite L855              | [59b708132a](https://linux-hardware.org/?probe=59b708132a) | Mar 11, 2021 |
| Dell          | Latitude E6430              | [df0fd6efc1](https://linux-hardware.org/?probe=df0fd6efc1) | Mar 11, 2021 |
| Dell          | Inspiron 3505               | [0a52f61c0b](https://linux-hardware.org/?probe=0a52f61c0b) | Mar 10, 2021 |
| Lenovo        | G475 20080                  | [bc23f1203d](https://linux-hardware.org/?probe=bc23f1203d) | Mar 10, 2021 |
| Lenovo        | ThinkPad T460 20FMA05ELM    | [6df088eed7](https://linux-hardware.org/?probe=6df088eed7) | Mar 09, 2021 |
| HP            | ProBook 440 G5              | [22f1c0cdf5](https://linux-hardware.org/?probe=22f1c0cdf5) | Mar 08, 2021 |
| Dell          | Inspiron N5010              | [0cc19de212](https://linux-hardware.org/?probe=0cc19de212) | Mar 07, 2021 |
| Sony          | VGN-NR130FE                 | [beff5e7b84](https://linux-hardware.org/?probe=beff5e7b84) | Mar 02, 2021 |
| HP            | ProBook 440 G5              | [65aaf4d956](https://linux-hardware.org/?probe=65aaf4d956) | Mar 02, 2021 |
| Sony          | VPCYB35AL                   | [b2276da50d](https://linux-hardware.org/?probe=b2276da50d) | Feb 28, 2021 |
| MSI           | GF63 Thin 10SCSR            | [6e2ec81f33](https://linux-hardware.org/?probe=6e2ec81f33) | Feb 27, 2021 |
| Dell          | Vostro 3460                 | [3127b67fa3](https://linux-hardware.org/?probe=3127b67fa3) | Feb 27, 2021 |
| Dell          | Vostro 3460                 | [452f5e2dc5](https://linux-hardware.org/?probe=452f5e2dc5) | Feb 27, 2021 |
| HP            | 435                         | [47d8f21d1d](https://linux-hardware.org/?probe=47d8f21d1d) | Feb 27, 2021 |
| Toshiba       | QOSMIO X875                 | [8c031f25b1](https://linux-hardware.org/?probe=8c031f25b1) | Feb 27, 2021 |
| Acer          | Aspire E5-511               | [8de4c7bbdb](https://linux-hardware.org/?probe=8de4c7bbdb) | Feb 26, 2021 |
| Dell          | Latitude E5450              | [a1ff35f981](https://linux-hardware.org/?probe=a1ff35f981) | Feb 26, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [2a89244123](https://linux-hardware.org/?probe=2a89244123) | Feb 25, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [1d0e4cc00f](https://linux-hardware.org/?probe=1d0e4cc00f) | Feb 25, 2021 |
| Apple         | MacBookPro9,2               | [c92086c4ca](https://linux-hardware.org/?probe=c92086c4ca) | Feb 25, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [eec33f21eb](https://linux-hardware.org/?probe=eec33f21eb) | Feb 24, 2021 |
| Dell          | XPS 15 9550                 | [7d1c10bc9a](https://linux-hardware.org/?probe=7d1c10bc9a) | Feb 23, 2021 |
| Toshiba       | Satellite L855              | [e507a57307](https://linux-hardware.org/?probe=e507a57307) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [c8fa1fd6d2](https://linux-hardware.org/?probe=c8fa1fd6d2) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [bda750c182](https://linux-hardware.org/?probe=bda750c182) | Feb 23, 2021 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | [4a94a7377c](https://linux-hardware.org/?probe=4a94a7377c) | Feb 23, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b845d0167a](https://linux-hardware.org/?probe=b845d0167a) | Feb 23, 2021 |
| Sony          | SVE11125CLB                 | [32f7cd36f3](https://linux-hardware.org/?probe=32f7cd36f3) | Feb 21, 2021 |
| MSI           | GV62 8RE                    | [e79d3bdfe8](https://linux-hardware.org/?probe=e79d3bdfe8) | Feb 20, 2021 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | [676acf093a](https://linux-hardware.org/?probe=676acf093a) | Feb 20, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [4d90e248e9](https://linux-hardware.org/?probe=4d90e248e9) | Feb 20, 2021 |
| Sony          | SVF15325CLB                 | [80b33d70fa](https://linux-hardware.org/?probe=80b33d70fa) | Feb 19, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [aa73d76a73](https://linux-hardware.org/?probe=aa73d76a73) | Feb 19, 2021 |
| HUAWEI        | MACH-WX9                    | [a5408b1b90](https://linux-hardware.org/?probe=a5408b1b90) | Feb 19, 2021 |
| Samsung       | 900X3N                      | [c2fafa6c24](https://linux-hardware.org/?probe=c2fafa6c24) | Feb 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [030df8a064](https://linux-hardware.org/?probe=030df8a064) | Feb 18, 2021 |
| HP            | Notebook                    | [b5c62a3151](https://linux-hardware.org/?probe=b5c62a3151) | Feb 18, 2021 |
| Acer          | Aspire 5720Z                | [aa5a168ee1](https://linux-hardware.org/?probe=aa5a168ee1) | Feb 18, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [0777f9cf28](https://linux-hardware.org/?probe=0777f9cf28) | Feb 17, 2021 |
| Acer          | Aspire 4736                 | [dcfe6a6021](https://linux-hardware.org/?probe=dcfe6a6021) | Feb 17, 2021 |
| Acer          | Swift SF314-42              | [401fbc4e6c](https://linux-hardware.org/?probe=401fbc4e6c) | Feb 17, 2021 |
| Acer          | Swift SF314-42              | [3911c9802c](https://linux-hardware.org/?probe=3911c9802c) | Feb 17, 2021 |
| HP            | ProBook 4430s               | [039d3e4962](https://linux-hardware.org/?probe=039d3e4962) | Feb 17, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [8fd2d8bfcc](https://linux-hardware.org/?probe=8fd2d8bfcc) | Feb 17, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [f9891df090](https://linux-hardware.org/?probe=f9891df090) | Feb 17, 2021 |
| Lenovo        | ThinkPad A285 20MWCTO1WW    | [8e663db748](https://linux-hardware.org/?probe=8e663db748) | Feb 17, 2021 |
| Lenovo        | ThinkPad T430 23421W9       | [85b751b7e9](https://linux-hardware.org/?probe=85b751b7e9) | Feb 17, 2021 |
| Sony          | SVF15325CLB                 | [4a6e4f85e1](https://linux-hardware.org/?probe=4a6e4f85e1) | Feb 16, 2021 |
| Unknown       | Unknown                     | [3c68044d9b](https://linux-hardware.org/?probe=3c68044d9b) | Feb 16, 2021 |
| Dell          | Inspiron 1420               | [0c5957927b](https://linux-hardware.org/?probe=0c5957927b) | Feb 15, 2021 |
| Acer          | V5-131                      | [fb508c9cd9](https://linux-hardware.org/?probe=fb508c9cd9) | Feb 14, 2021 |
| Toshiba       | Satellite L855              | [941b946e5e](https://linux-hardware.org/?probe=941b946e5e) | Feb 14, 2021 |
| Toshiba       | Satellite L855              | [4cfe29288e](https://linux-hardware.org/?probe=4cfe29288e) | Feb 14, 2021 |
| Dell          | Inspiron 3505               | [553d901926](https://linux-hardware.org/?probe=553d901926) | Feb 14, 2021 |
| HP            | ZBook 15 G3                 | [62c6b7586e](https://linux-hardware.org/?probe=62c6b7586e) | Feb 14, 2021 |
| HP            | Notebook                    | [56a5c8c252](https://linux-hardware.org/?probe=56a5c8c252) | Feb 14, 2021 |
| Gateway       | ID59C                       | [b19abd45ba](https://linux-hardware.org/?probe=b19abd45ba) | Feb 13, 2021 |
| Gateway       | ID59C                       | [ad762a3729](https://linux-hardware.org/?probe=ad762a3729) | Feb 13, 2021 |
| Acer          | Aspire V5-572               | [5d8e9893af](https://linux-hardware.org/?probe=5d8e9893af) | Feb 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [a0d2a03bed](https://linux-hardware.org/?probe=a0d2a03bed) | Feb 12, 2021 |
| Lenovo        | G50-30 80G0                 | [c12f388512](https://linux-hardware.org/?probe=c12f388512) | Feb 10, 2021 |
| Lenovo        | G50-30 80G0                 | [652e5a1352](https://linux-hardware.org/?probe=652e5a1352) | Feb 10, 2021 |
| HP            | Pavilion dv5                | [a1d8a0b99b](https://linux-hardware.org/?probe=a1d8a0b99b) | Feb 10, 2021 |
| HP            | Pavilion dv5                | [fe4b5ef832](https://linux-hardware.org/?probe=fe4b5ef832) | Feb 10, 2021 |
| Sony          | VGN-NR130FE                 | [02d525c94c](https://linux-hardware.org/?probe=02d525c94c) | Feb 10, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [6f095f70ea](https://linux-hardware.org/?probe=6f095f70ea) | Feb 08, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [4573978fce](https://linux-hardware.org/?probe=4573978fce) | Feb 08, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [cfc0721a89](https://linux-hardware.org/?probe=cfc0721a89) | Feb 08, 2021 |
| Acer          | Aspire V5-572               | [845ac62ec7](https://linux-hardware.org/?probe=845ac62ec7) | Feb 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ea7df9c5e5](https://linux-hardware.org/?probe=ea7df9c5e5) | Feb 07, 2021 |
| Acer          | Aspire R3-431T              | [f19b7db6c0](https://linux-hardware.org/?probe=f19b7db6c0) | Feb 07, 2021 |
| HP            | G62                         | [ea05144ac6](https://linux-hardware.org/?probe=ea05144ac6) | Feb 06, 2021 |
| Toshiba       | Satellite P755              | [5fd0a5a782](https://linux-hardware.org/?probe=5fd0a5a782) | Feb 05, 2021 |
| HP            | G62                         | [5d141c74aa](https://linux-hardware.org/?probe=5d141c74aa) | Feb 04, 2021 |
| Toshiba       | Satellite L855              | [7a2993f67a](https://linux-hardware.org/?probe=7a2993f67a) | Feb 03, 2021 |
| ASUSTek       | X541NA                      | [42e8ac7e57](https://linux-hardware.org/?probe=42e8ac7e57) | Feb 03, 2021 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [b877012ac5](https://linux-hardware.org/?probe=b877012ac5) | Feb 02, 2021 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [a147d69ec6](https://linux-hardware.org/?probe=a147d69ec6) | Feb 02, 2021 |
| Dell          | Latitude 3450               | [e581e8fe39](https://linux-hardware.org/?probe=e581e8fe39) | Feb 01, 2021 |
| Dell          | Latitude 3450               | [d1c4ad0cdf](https://linux-hardware.org/?probe=d1c4ad0cdf) | Feb 01, 2021 |
| Acer          | AOD257                      | [6516a78368](https://linux-hardware.org/?probe=6516a78368) | Feb 01, 2021 |
| Acer          | AOD257                      | [f435e31f67](https://linux-hardware.org/?probe=f435e31f67) | Feb 01, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [4398b5184f](https://linux-hardware.org/?probe=4398b5184f) | Jan 29, 2021 |
| Acer          | Aspire E3-112M              | [2dcea34103](https://linux-hardware.org/?probe=2dcea34103) | Jan 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X532... | [669b3a7aeb](https://linux-hardware.org/?probe=669b3a7aeb) | Jan 28, 2021 |
| Lenovo        | IdeaPad Y910-17ISK 80V1     | [9a9e567ab4](https://linux-hardware.org/?probe=9a9e567ab4) | Jan 27, 2021 |
| HP            | Pavilion 13 x360 PC         | [06b271f142](https://linux-hardware.org/?probe=06b271f142) | Jan 27, 2021 |
| HUAWEI        | HN-WX9X                     | [eb28878f00](https://linux-hardware.org/?probe=eb28878f00) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | [d0f16970b3](https://linux-hardware.org/?probe=d0f16970b3) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [cb06da42f6](https://linux-hardware.org/?probe=cb06da42f6) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [236fc1c1ea](https://linux-hardware.org/?probe=236fc1c1ea) | Jan 26, 2021 |
| Dell          | XPS 13 9350                 | [b9fe4c55c7](https://linux-hardware.org/?probe=b9fe4c55c7) | Jan 24, 2021 |
| Toshiba       | Satellite P305              | [c510c015c5](https://linux-hardware.org/?probe=c510c015c5) | Jan 23, 2021 |
| HP            | Pavilion g4                 | [f3b07013c2](https://linux-hardware.org/?probe=f3b07013c2) | Jan 22, 2021 |
| Toshiba       | Satellite P305              | [92c11ef7c0](https://linux-hardware.org/?probe=92c11ef7c0) | Jan 20, 2021 |
| HP            | Notebook                    | [5724cfe110](https://linux-hardware.org/?probe=5724cfe110) | Jan 19, 2021 |
| Acer          | Aspire R3-431T              | [1748407050](https://linux-hardware.org/?probe=1748407050) | Jan 18, 2021 |
| HP            | Pavilion 13 x360 PC         | [360a410808](https://linux-hardware.org/?probe=360a410808) | Jan 18, 2021 |
| HP            | Pavilion dv5                | [82242f6396](https://linux-hardware.org/?probe=82242f6396) | Jan 17, 2021 |
| Unknown       | Unknown                     | [43e80c011f](https://linux-hardware.org/?probe=43e80c011f) | Jan 16, 2021 |
| Dell          | Latitude 5580               | [eba5e925b8](https://linux-hardware.org/?probe=eba5e925b8) | Jan 14, 2021 |
| HP            | Pavilion dv5                | [c2024b4670](https://linux-hardware.org/?probe=c2024b4670) | Jan 12, 2021 |
| Samsung       | RC410/RC510/RC710           | [3ddef39d9e](https://linux-hardware.org/?probe=3ddef39d9e) | Jan 12, 2021 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [88b12593bc](https://linux-hardware.org/?probe=88b12593bc) | Jan 11, 2021 |
| HP            | Pavilion Laptop 15-cd0xx    | [af18fa04c3](https://linux-hardware.org/?probe=af18fa04c3) | Jan 11, 2021 |
| HP            | Pavilion Laptop 15-cd0xx    | [d163fb38d9](https://linux-hardware.org/?probe=d163fb38d9) | Jan 11, 2021 |
| Acer          | Aspire E3-112M              | [f438408755](https://linux-hardware.org/?probe=f438408755) | Jan 11, 2021 |
| Acer          | Aspire E3-112M              | [78d2276d7d](https://linux-hardware.org/?probe=78d2276d7d) | Jan 11, 2021 |
| Dell          | Inspiron 3505               | [b1981ecfff](https://linux-hardware.org/?probe=b1981ecfff) | Jan 10, 2021 |
| Acer          | Aspire V5-572               | [074b13aec5](https://linux-hardware.org/?probe=074b13aec5) | Jan 10, 2021 |
| ASUSTek       | X541NA                      | [a583bd4996](https://linux-hardware.org/?probe=a583bd4996) | Jan 10, 2021 |
| Acer          | Aspire V5-572               | [d58a15213d](https://linux-hardware.org/?probe=d58a15213d) | Jan 10, 2021 |
| Dell          | Inspiron 1545               | [17d1b27e3f](https://linux-hardware.org/?probe=17d1b27e3f) | Jan 10, 2021 |
| ASUSTek       | K46CA                       | [5c1da54689](https://linux-hardware.org/?probe=5c1da54689) | Jan 07, 2021 |
| Acer          | AOD257                      | [0f4e766947](https://linux-hardware.org/?probe=0f4e766947) | Jan 07, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [2ad9f6368e](https://linux-hardware.org/?probe=2ad9f6368e) | Jan 07, 2021 |
| Dell          | Latitude E6540              | [a224945d15](https://linux-hardware.org/?probe=a224945d15) | Jan 07, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [92c9f3e6c5](https://linux-hardware.org/?probe=92c9f3e6c5) | Jan 07, 2021 |
| ASUSTek       | G501VW                      | [32db9dc08a](https://linux-hardware.org/?probe=32db9dc08a) | Jan 07, 2021 |
| Lenovo        | G560e 20107                 | [aa92d6896e](https://linux-hardware.org/?probe=aa92d6896e) | Jan 07, 2021 |
| HP            | Mini 110-3700               | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| HP            | Pavilion dv5                | [cd2ef33093](https://linux-hardware.org/?probe=cd2ef33093) | Jan 05, 2021 |
| Apple         | MacBookPro8,1               | [86e79059c1](https://linux-hardware.org/?probe=86e79059c1) | Jan 04, 2021 |
| HP            | ProBook 4440s               | [8e6c01f203](https://linux-hardware.org/?probe=8e6c01f203) | Jan 04, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [efc897224f](https://linux-hardware.org/?probe=efc897224f) | Jan 03, 2021 |
| Acer          | AOD257                      | [bf6b850869](https://linux-hardware.org/?probe=bf6b850869) | Jan 03, 2021 |
| Gateway       | MX3631m                     | [15d8283384](https://linux-hardware.org/?probe=15d8283384) | Jan 03, 2021 |
| Acer          | Aspire E5-523               | [99c0e6fe8e](https://linux-hardware.org/?probe=99c0e6fe8e) | Jan 03, 2021 |
| ASUSTek       | GL553VD                     | [5f06cd3dc3](https://linux-hardware.org/?probe=5f06cd3dc3) | Jan 02, 2021 |
| ASUSTek       | GL553VD                     | [20fa405313](https://linux-hardware.org/?probe=20fa405313) | Jan 02, 2021 |
| Dell          | Precision 5520              | [e6ab46466b](https://linux-hardware.org/?probe=e6ab46466b) | Jan 02, 2021 |
| Dell          | Inspiron 3421               | [4d1abcba42](https://linux-hardware.org/?probe=4d1abcba42) | Jan 01, 2021 |
| Lenovo        | G50-45 80E3                 | [b26d930390](https://linux-hardware.org/?probe=b26d930390) | Jan 01, 2021 |
| HP            | Notebook                    | [f35ecfc673](https://linux-hardware.org/?probe=f35ecfc673) | Dec 31, 2020 |
| HP            | Pavilion g4                 | [704323b941](https://linux-hardware.org/?probe=704323b941) | Dec 31, 2020 |
| Acer          | Extensa 5630                | [eed68dd316](https://linux-hardware.org/?probe=eed68dd316) | Dec 30, 2020 |
| HP            | Compaq Presario CQ40        | [13ff1292c7](https://linux-hardware.org/?probe=13ff1292c7) | Dec 30, 2020 |
| MSI           | GL65 9SC                    | [e5fa3eefd0](https://linux-hardware.org/?probe=e5fa3eefd0) | Dec 30, 2020 |
| HP            | Notebook                    | [638aeddfe5](https://linux-hardware.org/?probe=638aeddfe5) | Dec 29, 2020 |
| HP            | Compaq Presario CQ40        | [f2648edd87](https://linux-hardware.org/?probe=f2648edd87) | Dec 29, 2020 |
| MSI           | GF63 Thin 10SCSR            | [f886aa9044](https://linux-hardware.org/?probe=f886aa9044) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA32VLM    | [cfa92bb7f3](https://linux-hardware.org/?probe=cfa92bb7f3) | Dec 28, 2020 |
| HP            | Pavilion g4                 | [753e9881d6](https://linux-hardware.org/?probe=753e9881d6) | Dec 27, 2020 |
| MSI           | GT70 2OC/2OD                | [b0ee02d1de](https://linux-hardware.org/?probe=b0ee02d1de) | Dec 27, 2020 |
| MSI           | GT70 2OC/2OD                | [909dfca881](https://linux-hardware.org/?probe=909dfca881) | Dec 26, 2020 |
| HP            | Pavilion dv5                | [e645ea7d89](https://linux-hardware.org/?probe=e645ea7d89) | Dec 26, 2020 |
| ASUSTek       | K46CA                       | [65b5ddbda5](https://linux-hardware.org/?probe=65b5ddbda5) | Dec 25, 2020 |
| HP            | G42                         | [c2046377dc](https://linux-hardware.org/?probe=c2046377dc) | Dec 25, 2020 |
| Lenovo        | ThinkPad X250 20CLA32VLM    | [08c1e530c1](https://linux-hardware.org/?probe=08c1e530c1) | Dec 24, 2020 |
| Acer          | Aspire E1-522               | [f6e709b997](https://linux-hardware.org/?probe=f6e709b997) | Dec 24, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [5537ea447d](https://linux-hardware.org/?probe=5537ea447d) | Dec 24, 2020 |
| MSI           | GL75 Leopard 10SDK          | [8b792fe096](https://linux-hardware.org/?probe=8b792fe096) | Dec 23, 2020 |
| Toshiba       | Satellite T215D             | [084f254e1f](https://linux-hardware.org/?probe=084f254e1f) | Dec 23, 2020 |
| Toshiba       | Satellite T215D             | [bdb8fe4e55](https://linux-hardware.org/?probe=bdb8fe4e55) | Dec 23, 2020 |
| Toshiba       | Satellite L855              | [0173204c7f](https://linux-hardware.org/?probe=0173204c7f) | Dec 23, 2020 |
| ASUSTek       | X541NA                      | [b17ba4582e](https://linux-hardware.org/?probe=b17ba4582e) | Dec 22, 2020 |
| ASUSTek       | X541NA                      | [1feb258908](https://linux-hardware.org/?probe=1feb258908) | Dec 20, 2020 |
| Dell          | Studio 1749                 | [3aae3f0b4b](https://linux-hardware.org/?probe=3aae3f0b4b) | Dec 19, 2020 |
| Acer          | Aspire M5-481T              | [30ef9f3c40](https://linux-hardware.org/?probe=30ef9f3c40) | Dec 19, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [d87cdee8cb](https://linux-hardware.org/?probe=d87cdee8cb) | Dec 19, 2020 |
| Dell          | Studio 1749                 | [13c11d7a5e](https://linux-hardware.org/?probe=13c11d7a5e) | Dec 19, 2020 |
| HP            | Compaq Presario A900        | [7190813d9f](https://linux-hardware.org/?probe=7190813d9f) | Dec 17, 2020 |
| HP            | Compaq Presario A900        | [3fd24577d3](https://linux-hardware.org/?probe=3fd24577d3) | Dec 17, 2020 |
| Acer          | Aspire E5-523               | [ff03816a1e](https://linux-hardware.org/?probe=ff03816a1e) | Dec 16, 2020 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b7fa9e38a1](https://linux-hardware.org/?probe=b7fa9e38a1) | Dec 14, 2020 |
| HP            | Pavilion dv5                | [d85d993bd8](https://linux-hardware.org/?probe=d85d993bd8) | Dec 14, 2020 |
| HP            | Pavilion dv5                | [82b27081ba](https://linux-hardware.org/?probe=82b27081ba) | Dec 14, 2020 |
| HP            | ProBook 4430s               | [dd137b1bad](https://linux-hardware.org/?probe=dd137b1bad) | Dec 13, 2020 |
| Toshiba       | Satellite L855              | [3d3a517e96](https://linux-hardware.org/?probe=3d3a517e96) | Dec 11, 2020 |
| HP            | ZBook 17 G5                 | [ca21d7e31d](https://linux-hardware.org/?probe=ca21d7e31d) | Dec 11, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [9d12f4f222](https://linux-hardware.org/?probe=9d12f4f222) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [c26814bfc2](https://linux-hardware.org/?probe=c26814bfc2) | Dec 10, 2020 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [2e6f19a420](https://linux-hardware.org/?probe=2e6f19a420) | Dec 09, 2020 |
| HP            | Pavilion dv1000 (EW999LA... | [6675bde630](https://linux-hardware.org/?probe=6675bde630) | Dec 07, 2020 |
| HP            | Pavilion Laptop 15-cd0xx    | [b70448e7c3](https://linux-hardware.org/?probe=b70448e7c3) | Dec 07, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [cf0d9c6a89](https://linux-hardware.org/?probe=cf0d9c6a89) | Dec 06, 2020 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [f60732b8e7](https://linux-hardware.org/?probe=f60732b8e7) | Dec 06, 2020 |
| Toshiba       | Satellite C655              | [2f3994d3e2](https://linux-hardware.org/?probe=2f3994d3e2) | Dec 05, 2020 |
| Toshiba       | Satellite C655              | [0410607acd](https://linux-hardware.org/?probe=0410607acd) | Dec 05, 2020 |
| Lenovo        | G400s 20244                 | [baefa771ef](https://linux-hardware.org/?probe=baefa771ef) | Dec 05, 2020 |
| Lenovo        | G400s 20244                 | [ab6a7a6eb5](https://linux-hardware.org/?probe=ab6a7a6eb5) | Dec 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4c880dbbf7](https://linux-hardware.org/?probe=4c880dbbf7) | Dec 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [19f15f5bf8](https://linux-hardware.org/?probe=19f15f5bf8) | Dec 03, 2020 |
| Acer          | Aspire E5-411               | [2513d28117](https://linux-hardware.org/?probe=2513d28117) | Dec 02, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f9f0d6845f](https://linux-hardware.org/?probe=f9f0d6845f) | Dec 02, 2020 |
| Lenovo        | Legion Y740-17ICHg 81HH     | [c9aa8ab3f3](https://linux-hardware.org/?probe=c9aa8ab3f3) | Nov 30, 2020 |
| ASUSTek       | X541NA                      | [14b61c8d9f](https://linux-hardware.org/?probe=14b61c8d9f) | Nov 30, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [69cb387fe7](https://linux-hardware.org/?probe=69cb387fe7) | Nov 30, 2020 |
| HP            | Pavilion dv2700             | [19cda851d2](https://linux-hardware.org/?probe=19cda851d2) | Nov 30, 2020 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [0e719d2807](https://linux-hardware.org/?probe=0e719d2807) | Nov 29, 2020 |
| Lenovo        | ThinkPad T420 4236S3C       | [7a61b58c47](https://linux-hardware.org/?probe=7a61b58c47) | Nov 29, 2020 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [d6559e4ce6](https://linux-hardware.org/?probe=d6559e4ce6) | Nov 29, 2020 |
| Dell          | Inspiron 15-3552            | [762c5e70ba](https://linux-hardware.org/?probe=762c5e70ba) | Nov 28, 2020 |
| Dell          | Inspiron 15-3552            | [fc13827e05](https://linux-hardware.org/?probe=fc13827e05) | Nov 28, 2020 |
| ASUSTek       | X541NA                      | [481c3fdef2](https://linux-hardware.org/?probe=481c3fdef2) | Nov 28, 2020 |
| HP            | Pavilion dv5                | [2a5735c275](https://linux-hardware.org/?probe=2a5735c275) | Nov 27, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [dbb90b2e1c](https://linux-hardware.org/?probe=dbb90b2e1c) | Nov 27, 2020 |
| Dell          | Latitude E6520              | [5fda977607](https://linux-hardware.org/?probe=5fda977607) | Nov 27, 2020 |
| ASUSTek       | G501VW                      | [4827515019](https://linux-hardware.org/?probe=4827515019) | Nov 27, 2020 |
| ASUSTek       | X541NA                      | [290b120d94](https://linux-hardware.org/?probe=290b120d94) | Nov 25, 2020 |
| System76      | Gazelle                     | [04cbce95b0](https://linux-hardware.org/?probe=04cbce95b0) | Nov 22, 2020 |
| Dell          | Precision 5520              | [1b927d9748](https://linux-hardware.org/?probe=1b927d9748) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [18d99f9e4f](https://linux-hardware.org/?probe=18d99f9e4f) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [c17dc0982c](https://linux-hardware.org/?probe=c17dc0982c) | Nov 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [84a70ed914](https://linux-hardware.org/?probe=84a70ed914) | Nov 21, 2020 |
| Apple         | MacBookAir5,2               | [5fb845c549](https://linux-hardware.org/?probe=5fb845c549) | Nov 21, 2020 |
| Acer          | Aspire A515-44G             | [e51d8b6e95](https://linux-hardware.org/?probe=e51d8b6e95) | Nov 21, 2020 |
| Acer          | Aspire A515-44G             | [88a96faacb](https://linux-hardware.org/?probe=88a96faacb) | Nov 21, 2020 |
| HP            | ProBook 640 G5              | [fc9abd07f4](https://linux-hardware.org/?probe=fc9abd07f4) | Nov 20, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [fdf88803ba](https://linux-hardware.org/?probe=fdf88803ba) | Nov 20, 2020 |
| HP            | Pavilion TS 14              | [131e26b57a](https://linux-hardware.org/?probe=131e26b57a) | Nov 18, 2020 |
| HP            | Pavilion TS 14              | [5bb89a3e53](https://linux-hardware.org/?probe=5bb89a3e53) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [da52f55c07](https://linux-hardware.org/?probe=da52f55c07) | Nov 18, 2020 |
| Lenovo        | IdeaPad S145-14API 81UV     | [7558b24484](https://linux-hardware.org/?probe=7558b24484) | Nov 16, 2020 |
| Lenovo        | ThinkPad T420 4236S3C       | [19f2fc978a](https://linux-hardware.org/?probe=19f2fc978a) | Nov 15, 2020 |
| Dell          | Latitude 3460               | [ca434a1d16](https://linux-hardware.org/?probe=ca434a1d16) | Nov 14, 2020 |
| Dell          | Latitude 3460               | [acb05d0cf6](https://linux-hardware.org/?probe=acb05d0cf6) | Nov 14, 2020 |
| Acer          | Aspire E5-523               | [316dc021cb](https://linux-hardware.org/?probe=316dc021cb) | Nov 14, 2020 |
| Dell          | XPS 13 9380                 | [f06c553056](https://linux-hardware.org/?probe=f06c553056) | Nov 12, 2020 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [6fbc070dc3](https://linux-hardware.org/?probe=6fbc070dc3) | Nov 11, 2020 |
| Sony          | SVE14A25CLB                 | [36b2478eee](https://linux-hardware.org/?probe=36b2478eee) | Nov 11, 2020 |
| Dell          | Inspiron 3520               | [4193ceaa32](https://linux-hardware.org/?probe=4193ceaa32) | Nov 09, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [e3850715a2](https://linux-hardware.org/?probe=e3850715a2) | Nov 07, 2020 |
| HP            | Compaq Presario CQ40        | [7ef796213b](https://linux-hardware.org/?probe=7ef796213b) | Nov 05, 2020 |
| Toshiba       | Satellite T115D             | [0ecef5c6a4](https://linux-hardware.org/?probe=0ecef5c6a4) | Nov 05, 2020 |
| Dell          | Inspiron 3442               | [3e1ef3d0d5](https://linux-hardware.org/?probe=3e1ef3d0d5) | Nov 05, 2020 |
| Dell          | Inspiron 3442               | [91e0e72594](https://linux-hardware.org/?probe=91e0e72594) | Nov 05, 2020 |
| Sony          | VGN-CS370T                  | [0747cec367](https://linux-hardware.org/?probe=0747cec367) | Nov 05, 2020 |
| ASUSTek       | X555QG                      | [e3453cf4bb](https://linux-hardware.org/?probe=e3453cf4bb) | Nov 04, 2020 |
| HUAWEI        | MACHC-WAX9                  | [c4cf6564b8](https://linux-hardware.org/?probe=c4cf6564b8) | Nov 04, 2020 |
| ASUSTek       | X555QG                      | [b19afd7ea9](https://linux-hardware.org/?probe=b19afd7ea9) | Nov 04, 2020 |
| Toshiba       | Satellite L655              | [0d09980c96](https://linux-hardware.org/?probe=0d09980c96) | Nov 02, 2020 |
| HP            | ProBook 640 G1              | [8d9ca2df40](https://linux-hardware.org/?probe=8d9ca2df40) | Nov 02, 2020 |
| HP            | ProBook 640 G1              | [2d30d43daa](https://linux-hardware.org/?probe=2d30d43daa) | Nov 02, 2020 |
| Toshiba       | Satellite L855              | [57b4629ea3](https://linux-hardware.org/?probe=57b4629ea3) | Nov 02, 2020 |
| Dell          | Latitude E4300              | [2cd7ae1a0e](https://linux-hardware.org/?probe=2cd7ae1a0e) | Oct 30, 2020 |
| ASUSTek       | X556UQK                     | [c05de50902](https://linux-hardware.org/?probe=c05de50902) | Oct 30, 2020 |
| Dell          | Studio XPS 1640             | [f9295825d1](https://linux-hardware.org/?probe=f9295825d1) | Oct 30, 2020 |
| Dell          | Latitude 5480               | [356ef986cc](https://linux-hardware.org/?probe=356ef986cc) | Oct 29, 2020 |
| Dell          | Latitude 5480               | [ecc79d59e4](https://linux-hardware.org/?probe=ecc79d59e4) | Oct 29, 2020 |
| Lenovo        | ThinkPad T430 23501K0       | [cbaf077bd3](https://linux-hardware.org/?probe=cbaf077bd3) | Oct 29, 2020 |
| Lenovo        | ThinkPad T430 23501K0       | [604548bcb1](https://linux-hardware.org/?probe=604548bcb1) | Oct 29, 2020 |
| Lenovo        | ThinkPad T430 23501K0       | [ab43860392](https://linux-hardware.org/?probe=ab43860392) | Oct 29, 2020 |
| Dell          | Inspiron 7559               | [9ce06bcd74](https://linux-hardware.org/?probe=9ce06bcd74) | Oct 29, 2020 |
| MSI           | GF63 Thin 9RCX              | [4bce2cf204](https://linux-hardware.org/?probe=4bce2cf204) | Oct 28, 2020 |
| Lenovo        | ThinkPad T420 42366Y0       | [ebcf2c46e9](https://linux-hardware.org/?probe=ebcf2c46e9) | Oct 26, 2020 |
| Lenovo        | ThinkPad T420 42366Y0       | [1b2fb4f3ac](https://linux-hardware.org/?probe=1b2fb4f3ac) | Oct 26, 2020 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [375eed9e37](https://linux-hardware.org/?probe=375eed9e37) | Oct 26, 2020 |
| Lenovo        | ThinkPad T520 4242BC5       | [3e986def5b](https://linux-hardware.org/?probe=3e986def5b) | Oct 25, 2020 |
| HP            | Pavilion g4                 | [3452219005](https://linux-hardware.org/?probe=3452219005) | Oct 24, 2020 |
| Apple         | MacBookPro9,2               | [4bd53283df](https://linux-hardware.org/?probe=4bd53283df) | Oct 24, 2020 |
| Apple         | MacBookPro9,2               | [3d2d1ef257](https://linux-hardware.org/?probe=3d2d1ef257) | Oct 24, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [47cb21f832](https://linux-hardware.org/?probe=47cb21f832) | Oct 23, 2020 |
| Lenovo        | ThinkPad L490 20Q6S80S00    | [399e928328](https://linux-hardware.org/?probe=399e928328) | Oct 22, 2020 |
| Lenovo        | IdeaPad U310                | [3a7e7833d7](https://linux-hardware.org/?probe=3a7e7833d7) | Oct 21, 2020 |
| Dell          | Inspiron 3421               | [33e944eab2](https://linux-hardware.org/?probe=33e944eab2) | Oct 20, 2020 |
| HP            | Compaq Presario CQ60        | [0fdfd91ef2](https://linux-hardware.org/?probe=0fdfd91ef2) | Oct 19, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [9e02d94bf0](https://linux-hardware.org/?probe=9e02d94bf0) | Oct 17, 2020 |
| Acer          | Aspire E5-522               | [1b817099d9](https://linux-hardware.org/?probe=1b817099d9) | Oct 17, 2020 |
| Dell          | Inspiron 5558               | [8b369f4f83](https://linux-hardware.org/?probe=8b369f4f83) | Oct 15, 2020 |
| HP            | EliteBook 820 G1            | [69db8e6f19](https://linux-hardware.org/?probe=69db8e6f19) | Oct 14, 2020 |
| HP            | Pavilion Notebook           | [6cfa593625](https://linux-hardware.org/?probe=6cfa593625) | Oct 11, 2020 |
| Acer          | Aspire E5-522               | [fd5a778809](https://linux-hardware.org/?probe=fd5a778809) | Oct 11, 2020 |
| Lenovo        | ThinkPad L490 20Q6S80S00    | [1d9d75467f](https://linux-hardware.org/?probe=1d9d75467f) | Oct 09, 2020 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [4c31e8d0bc](https://linux-hardware.org/?probe=4c31e8d0bc) | Oct 09, 2020 |
| Dell          | Latitude E7240              | [f0eed491f0](https://linux-hardware.org/?probe=f0eed491f0) | Oct 07, 2020 |
| HP            | Notebook                    | [5152b94329](https://linux-hardware.org/?probe=5152b94329) | Oct 07, 2020 |
| HP            | Pavilion dm4                | [1411241070](https://linux-hardware.org/?probe=1411241070) | Oct 06, 2020 |
| Toshiba       | Satellite S40Dt-A           | [1e7683c83e](https://linux-hardware.org/?probe=1e7683c83e) | Oct 06, 2020 |
| Toshiba       | Satellite A135              | [872e375f7d](https://linux-hardware.org/?probe=872e375f7d) | Oct 06, 2020 |
| Toshiba       | Satellite A135              | [51279c1662](https://linux-hardware.org/?probe=51279c1662) | Oct 06, 2020 |
| Acer          | Aspire V5-572               | [94442f9f9a](https://linux-hardware.org/?probe=94442f9f9a) | Oct 06, 2020 |
| Lenovo        | Unknown                     | [9985f4ca1a](https://linux-hardware.org/?probe=9985f4ca1a) | Oct 02, 2020 |
| Dell          | G3 3579                     | [07c2e25a8c](https://linux-hardware.org/?probe=07c2e25a8c) | Oct 02, 2020 |
| HP            | Pavilion 15                 | [b7c4b5f8e6](https://linux-hardware.org/?probe=b7c4b5f8e6) | Sep 30, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [dad6085603](https://linux-hardware.org/?probe=dad6085603) | Sep 29, 2020 |
| Acer          | Aspire E5-575               | [2b44e3ac0d](https://linux-hardware.org/?probe=2b44e3ac0d) | Sep 28, 2020 |
| Acer          | Aspire E5-575               | [4645186a02](https://linux-hardware.org/?probe=4645186a02) | Sep 28, 2020 |
| Acer          | Aspire E5-475               | [adb40d2eb4](https://linux-hardware.org/?probe=adb40d2eb4) | Sep 26, 2020 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | [7cf2dda814](https://linux-hardware.org/?probe=7cf2dda814) | Sep 25, 2020 |
| Dell          | Inspiron 1440               | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Google        | Kefka                       | [8b10654673](https://linux-hardware.org/?probe=8b10654673) | Sep 25, 2020 |
| Lenovo        | 3000 N200 0769AWS           | [1ae21f5419](https://linux-hardware.org/?probe=1ae21f5419) | Sep 24, 2020 |
| Lenovo        | 3000 N200 0769AWS           | [d0178cb242](https://linux-hardware.org/?probe=d0178cb242) | Sep 24, 2020 |
| Google        | Kefka                       | [35ba340c7c](https://linux-hardware.org/?probe=35ba340c7c) | Sep 24, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4b03ee65ce](https://linux-hardware.org/?probe=4b03ee65ce) | Sep 23, 2020 |
| Acer          | Aspire ES1-111M             | [b5a412b4ae](https://linux-hardware.org/?probe=b5a412b4ae) | Sep 22, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [7a07706a75](https://linux-hardware.org/?probe=7a07706a75) | Sep 21, 2020 |
| HP            | G42                         | [c3c240b5fe](https://linux-hardware.org/?probe=c3c240b5fe) | Sep 20, 2020 |
| Dell          | Inspiron 3421               | [4eb88f63fd](https://linux-hardware.org/?probe=4eb88f63fd) | Sep 19, 2020 |
| Clevo         | M1110M                      | [c545781337](https://linux-hardware.org/?probe=c545781337) | Sep 15, 2020 |
| Google        | Kefka                       | [9a6994eccc](https://linux-hardware.org/?probe=9a6994eccc) | Sep 15, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [06a2be071c](https://linux-hardware.org/?probe=06a2be071c) | Sep 14, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [1134efa13a](https://linux-hardware.org/?probe=1134efa13a) | Sep 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [614f49754a](https://linux-hardware.org/?probe=614f49754a) | Sep 13, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | [462b1c7b2f](https://linux-hardware.org/?probe=462b1c7b2f) | Sep 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [a606c2599e](https://linux-hardware.org/?probe=a606c2599e) | Sep 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [ff590d3a5e](https://linux-hardware.org/?probe=ff590d3a5e) | Sep 11, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | [065df82a87](https://linux-hardware.org/?probe=065df82a87) | Sep 11, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [bc05c6b8f2](https://linux-hardware.org/?probe=bc05c6b8f2) | Sep 11, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c4f748ee40](https://linux-hardware.org/?probe=c4f748ee40) | Sep 08, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [b090124c20](https://linux-hardware.org/?probe=b090124c20) | Sep 08, 2020 |
| HP            | 2000                        | [9b9d1846bb](https://linux-hardware.org/?probe=9b9d1846bb) | Sep 07, 2020 |
| Sony          | VPCCW25FL                   | [f239a287e7](https://linux-hardware.org/?probe=f239a287e7) | Sep 07, 2020 |
| Dell          | Vostro 1520                 | [f92bb1d4a7](https://linux-hardware.org/?probe=f92bb1d4a7) | Sep 07, 2020 |
| Apple         | MacBookPro9,2               | [9eaa287137](https://linux-hardware.org/?probe=9eaa287137) | Sep 07, 2020 |
| Apple         | MacBookPro14,1              | [e8b5085a16](https://linux-hardware.org/?probe=e8b5085a16) | Sep 06, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [f0f7bbc20d](https://linux-hardware.org/?probe=f0f7bbc20d) | Sep 06, 2020 |
| Dell          | Inspiron 3421               | [9d0e36cc9b](https://linux-hardware.org/?probe=9d0e36cc9b) | Sep 06, 2020 |
| Lenovo        | Flex 2-14 20404             | [74cf2869d7](https://linux-hardware.org/?probe=74cf2869d7) | Sep 05, 2020 |
| HP            | Notebook                    | [232fad8804](https://linux-hardware.org/?probe=232fad8804) | Sep 05, 2020 |
| Toshiba       | Satellite L855              | [3da5c16a94](https://linux-hardware.org/?probe=3da5c16a94) | Sep 04, 2020 |
| Dell          | Inspiron 3421               | [117835012a](https://linux-hardware.org/?probe=117835012a) | Sep 04, 2020 |
| Lenovo        | ThinkPad T440p 20AWA0UJL... | [bd739bcc4b](https://linux-hardware.org/?probe=bd739bcc4b) | Sep 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [51aa00a8f0](https://linux-hardware.org/?probe=51aa00a8f0) | Sep 03, 2020 |
| Acer          | Aspire V5-473P              | [53b5caab70](https://linux-hardware.org/?probe=53b5caab70) | Sep 02, 2020 |
| Insyde        | B14                         | [17f56fffc9](https://linux-hardware.org/?probe=17f56fffc9) | Sep 02, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [88dde753df](https://linux-hardware.org/?probe=88dde753df) | Aug 30, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [ed09cfb011](https://linux-hardware.org/?probe=ed09cfb011) | Aug 30, 2020 |
| Apple         | MacBookPro7,1               | [6c3518c3f2](https://linux-hardware.org/?probe=6c3518c3f2) | Aug 29, 2020 |
| Lenovo        | G40-45 80E1                 | [7479bd1e8e](https://linux-hardware.org/?probe=7479bd1e8e) | Aug 29, 2020 |
| Lenovo        | G40-45 80E1                 | [70df828288](https://linux-hardware.org/?probe=70df828288) | Aug 29, 2020 |
| Apple         | MacBookPro7,1               | [03f1147cb9](https://linux-hardware.org/?probe=03f1147cb9) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| HP            | Notebook                    | [2aa4b68203](https://linux-hardware.org/?probe=2aa4b68203) | Aug 26, 2020 |
| HP            | G42                         | [a5b6e6f033](https://linux-hardware.org/?probe=a5b6e6f033) | Aug 26, 2020 |
| HP            | Pavilion dv7                | [7bc6c01fdf](https://linux-hardware.org/?probe=7bc6c01fdf) | Aug 25, 2020 |
| Dell          | Latitude E6430s             | [34b7dc2f1c](https://linux-hardware.org/?probe=34b7dc2f1c) | Aug 25, 2020 |
| Dell          | Latitude E6430s             | [2b6bc59942](https://linux-hardware.org/?probe=2b6bc59942) | Aug 25, 2020 |
| Dell          | Studio 1535                 | [cc6fde20e2](https://linux-hardware.org/?probe=cc6fde20e2) | Aug 25, 2020 |
| HP            | Notebook                    | [16874b02c3](https://linux-hardware.org/?probe=16874b02c3) | Aug 24, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [52667a817a](https://linux-hardware.org/?probe=52667a817a) | Aug 24, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d6ecec7769](https://linux-hardware.org/?probe=d6ecec7769) | Aug 24, 2020 |
| Toshiba       | Satellite L855D             | [c43432c162](https://linux-hardware.org/?probe=c43432c162) | Aug 23, 2020 |
| HP            | Pavilion dv4                | [580a586842](https://linux-hardware.org/?probe=580a586842) | Aug 23, 2020 |
| Lenovo        | QIQY5                       | [d527778919](https://linux-hardware.org/?probe=d527778919) | Aug 22, 2020 |
| HP            | Pavilion dv6                | [0ed6b0a0bf](https://linux-hardware.org/?probe=0ed6b0a0bf) | Aug 22, 2020 |
| Toshiba       | Satellite C55-B             | [a30f907fcc](https://linux-hardware.org/?probe=a30f907fcc) | Aug 21, 2020 |
| Dell          | Studio 1535                 | [c549336288](https://linux-hardware.org/?probe=c549336288) | Aug 21, 2020 |
| Toshiba       | Satellite L855D             | [e24b9e7fdb](https://linux-hardware.org/?probe=e24b9e7fdb) | Aug 21, 2020 |
| Toshiba       | Satellite C55-B             | [9738b3a41e](https://linux-hardware.org/?probe=9738b3a41e) | Aug 21, 2020 |
| Dell          | G7 7588                     | [45f986f03d](https://linux-hardware.org/?probe=45f986f03d) | Aug 20, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [2090ed80ba](https://linux-hardware.org/?probe=2090ed80ba) | Aug 19, 2020 |
| HUAWEI        | HN-WX9X                     | [8b773f01d7](https://linux-hardware.org/?probe=8b773f01d7) | Aug 17, 2020 |
| HP            | Laptop 14-ck0xxx            | [2df9042677](https://linux-hardware.org/?probe=2df9042677) | Aug 17, 2020 |
| Dell          | Inspiron 7577               | [0829131f58](https://linux-hardware.org/?probe=0829131f58) | Aug 17, 2020 |
| ASUSTek       | X555DG                      | [eb45939783](https://linux-hardware.org/?probe=eb45939783) | Aug 17, 2020 |
| ASUSTek       | X55CR                       | [6d4b5b2778](https://linux-hardware.org/?probe=6d4b5b2778) | Aug 17, 2020 |
| Unknown       | KN12A                       | [56648f0d99](https://linux-hardware.org/?probe=56648f0d99) | Aug 16, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [93f97456c9](https://linux-hardware.org/?probe=93f97456c9) | Aug 16, 2020 |
| Sony          | VPCEK20AL                   | [2147eeff89](https://linux-hardware.org/?probe=2147eeff89) | Aug 16, 2020 |
| ASUSTek       | X541NA                      | [b9b89d3949](https://linux-hardware.org/?probe=b9b89d3949) | Aug 16, 2020 |
| Toshiba       | Satellite L855D             | [10da28f142](https://linux-hardware.org/?probe=10da28f142) | Aug 13, 2020 |
| Toshiba       | Satellite L855D             | [78b4307a24](https://linux-hardware.org/?probe=78b4307a24) | Aug 13, 2020 |
| ASUSTek       | X541NA                      | [38626e48c4](https://linux-hardware.org/?probe=38626e48c4) | Aug 13, 2020 |
| Toshiba       | Satellite L755D             | [8b95e230b3](https://linux-hardware.org/?probe=8b95e230b3) | Aug 13, 2020 |
| Acer          | Aspire A315-42              | [6b2998527f](https://linux-hardware.org/?probe=6b2998527f) | Aug 11, 2020 |
| HP            | ENVY 15                     | [50351c4fc3](https://linux-hardware.org/?probe=50351c4fc3) | Aug 06, 2020 |
| Lenovo        | ThinkPad Helix 37024V8      | [12ef944776](https://linux-hardware.org/?probe=12ef944776) | Aug 05, 2020 |
| Lenovo        | ThinkPad Helix 37024V8      | [8e8e86364e](https://linux-hardware.org/?probe=8e8e86364e) | Aug 05, 2020 |
| ASUSTek       | X541NA                      | [573c4745e3](https://linux-hardware.org/?probe=573c4745e3) | Aug 05, 2020 |
| Toshiba       | Satellite L855              | [5d7abe55d1](https://linux-hardware.org/?probe=5d7abe55d1) | Aug 05, 2020 |
| ASUSTek       | G750JW                      | [4199c37a8b](https://linux-hardware.org/?probe=4199c37a8b) | Aug 04, 2020 |
| ASUSTek       | X541NA                      | [920f977317](https://linux-hardware.org/?probe=920f977317) | Aug 04, 2020 |
| ASUSTek       | G750JW                      | [458aee2b71](https://linux-hardware.org/?probe=458aee2b71) | Aug 04, 2020 |
| Toshiba       | Satellite C55-B             | [7e10814d65](https://linux-hardware.org/?probe=7e10814d65) | Aug 03, 2020 |
| HP            | Pavilion dv6                | [d16b017e7b](https://linux-hardware.org/?probe=d16b017e7b) | Aug 01, 2020 |
| HP            | Pavilion dv6                | [1294d68d02](https://linux-hardware.org/?probe=1294d68d02) | Aug 01, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [6542295059](https://linux-hardware.org/?probe=6542295059) | Aug 01, 2020 |
| Dell          | Latitude 5580               | [f2260d4787](https://linux-hardware.org/?probe=f2260d4787) | Jul 30, 2020 |
| HP            | 240 G4                      | [259b0c0b6c](https://linux-hardware.org/?probe=259b0c0b6c) | Jul 29, 2020 |
| HP            | Pavilion dv2                | [8b119b3b2e](https://linux-hardware.org/?probe=8b119b3b2e) | Jul 29, 2020 |
| HP            | Pavilion dv2                | [872f8d83ab](https://linux-hardware.org/?probe=872f8d83ab) | Jul 29, 2020 |
| Samsung       | RC410/RC510/RC710           | [ff0e1e29b9](https://linux-hardware.org/?probe=ff0e1e29b9) | Jul 28, 2020 |
| Acer          | Aspire one                  | [cb5f7734ad](https://linux-hardware.org/?probe=cb5f7734ad) | Jul 27, 2020 |
| Sony          | VPCEA36FM                   | [f2855a01a1](https://linux-hardware.org/?probe=f2855a01a1) | Jul 27, 2020 |
| ASUSTek       | G50VT                       | [919044caec](https://linux-hardware.org/?probe=919044caec) | Jul 25, 2020 |
| Acer          | Aspire XXXX                 | [947f2f3fe1](https://linux-hardware.org/?probe=947f2f3fe1) | Jul 25, 2020 |
| ASUSTek       | X541NA                      | [96205d339f](https://linux-hardware.org/?probe=96205d339f) | Jul 24, 2020 |
| Gateway       | NV59                        | [072f41bee2](https://linux-hardware.org/?probe=072f41bee2) | Jul 23, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [4f9801f50a](https://linux-hardware.org/?probe=4f9801f50a) | Jul 23, 2020 |
| Dell          | Inspiron 3421               | [aed55dd96d](https://linux-hardware.org/?probe=aed55dd96d) | Jul 23, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [f9d6bbd72e](https://linux-hardware.org/?probe=f9d6bbd72e) | Jul 22, 2020 |
| HP            | G42                         | [a610e20c2e](https://linux-hardware.org/?probe=a610e20c2e) | Jul 19, 2020 |
| Apple         | MacBook5,1                  | [36bf6eee91](https://linux-hardware.org/?probe=36bf6eee91) | Jul 18, 2020 |
| Apple         | MacBook5,1                  | [a7e0cecd46](https://linux-hardware.org/?probe=a7e0cecd46) | Jul 18, 2020 |
| HP            | Laptop 14-bs0xx             | [9c797ef0a4](https://linux-hardware.org/?probe=9c797ef0a4) | Jul 17, 2020 |
| Apple         | MacBookPro11,4              | [e1a10e043b](https://linux-hardware.org/?probe=e1a10e043b) | Jul 17, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [b444564e32](https://linux-hardware.org/?probe=b444564e32) | Jul 17, 2020 |
| ASUSTek       | X541NA                      | [133839845c](https://linux-hardware.org/?probe=133839845c) | Jul 16, 2020 |
| Toshiba       | Satellite U305              | [a08a02467a](https://linux-hardware.org/?probe=a08a02467a) | Jul 16, 2020 |
| Insyde        | i101c                       | [0165ffabd2](https://linux-hardware.org/?probe=0165ffabd2) | Jul 13, 2020 |
| ASUSTek       | X541NA                      | [3ad86e6a72](https://linux-hardware.org/?probe=3ad86e6a72) | Jul 09, 2020 |
| HP            | Pavilion Notebook           | [367a2ebf06](https://linux-hardware.org/?probe=367a2ebf06) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Gateway       | MX6939M                     | [bcf6858e7d](https://linux-hardware.org/?probe=bcf6858e7d) | Jul 05, 2020 |
| Toshiba       | Satellite P305              | [375e5e169c](https://linux-hardware.org/?probe=375e5e169c) | Jul 04, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [86cdd553b2](https://linux-hardware.org/?probe=86cdd553b2) | Jul 04, 2020 |
| Acer          | Lugano M                    | [c3722a65f4](https://linux-hardware.org/?probe=c3722a65f4) | Jul 04, 2020 |
| Acer          | Lugano M                    | [d91f2c3af1](https://linux-hardware.org/?probe=d91f2c3af1) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| HP            | Pavilion g4                 | [21261aa7d1](https://linux-hardware.org/?probe=21261aa7d1) | Jul 01, 2020 |
| HP            | Laptop 14-bs0xx             | [cc1e0b07da](https://linux-hardware.org/?probe=cc1e0b07da) | Jun 30, 2020 |
| HP            | Pavilion Notebook           | [cd427a58b1](https://linux-hardware.org/?probe=cd427a58b1) | Jun 29, 2020 |
| HP            | Pavilion Notebook           | [64fcc4cd00](https://linux-hardware.org/?probe=64fcc4cd00) | Jun 29, 2020 |
| Toshiba       | Satellite S55t-B            | [01aa2bca69](https://linux-hardware.org/?probe=01aa2bca69) | Jun 28, 2020 |
| Toshiba       | Satellite S55t-B            | [71ae60ebc0](https://linux-hardware.org/?probe=71ae60ebc0) | Jun 27, 2020 |
| Dell          | Inspiron 5481               | [1075dca72a](https://linux-hardware.org/?probe=1075dca72a) | Jun 24, 2020 |
| eMachines     | eM350                       | [a7ce4015ef](https://linux-hardware.org/?probe=a7ce4015ef) | Jun 23, 2020 |
| Toshiba       | Satellite L755              | [a2168405a7](https://linux-hardware.org/?probe=a2168405a7) | Jun 23, 2020 |
| HP            | OMEN by Laptop              | [9b052aee3a](https://linux-hardware.org/?probe=9b052aee3a) | Jun 22, 2020 |
| Acer          | Swift SF514-52T             | [339f46cb2f](https://linux-hardware.org/?probe=339f46cb2f) | Jun 21, 2020 |
| Apple         | MacBookAir3,2               | [57590b568e](https://linux-hardware.org/?probe=57590b568e) | Jun 20, 2020 |
| Acer          | AOD255E                     | [1ff694ea71](https://linux-hardware.org/?probe=1ff694ea71) | Jun 20, 2020 |
| Lenovo        | ThinkPad S2 20GKA02100      | [a87fce4cf2](https://linux-hardware.org/?probe=a87fce4cf2) | Jun 19, 2020 |
| Dell          | Latitude E5470              | [eb93b4150a](https://linux-hardware.org/?probe=eb93b4150a) | Jun 18, 2020 |
| Dell          | Inspiron 5565               | [a077b3089f](https://linux-hardware.org/?probe=a077b3089f) | Jun 18, 2020 |
| Dell          | Inspiron 5584               | [03f0b77896](https://linux-hardware.org/?probe=03f0b77896) | Jun 18, 2020 |
| eMachines     | eM350                       | [37dd12d435](https://linux-hardware.org/?probe=37dd12d435) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bcbc0e3494](https://linux-hardware.org/?probe=bcbc0e3494) | Jun 16, 2020 |
| Lenovo        | ThinkPad L530 24792M8       | [ebbd146327](https://linux-hardware.org/?probe=ebbd146327) | Jun 15, 2020 |
| Dell          | Latitude E6430              | [97304444b6](https://linux-hardware.org/?probe=97304444b6) | Jun 14, 2020 |
| Sony          | VPCCW25FL                   | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| Lenovo        | ThinkPad L530 24792M8       | [d175fcfe4d](https://linux-hardware.org/?probe=d175fcfe4d) | Jun 14, 2020 |
| Dell          | Inspiron 5558               | [fe3aff4df8](https://linux-hardware.org/?probe=fe3aff4df8) | Jun 12, 2020 |
| Dell          | Inspiron 5558               | [a54b1c951c](https://linux-hardware.org/?probe=a54b1c951c) | Jun 12, 2020 |
| HP            | Laptop 14-bs0xx             | [3fbfb7068e](https://linux-hardware.org/?probe=3fbfb7068e) | Jun 12, 2020 |
| Acer          | Aspire S3                   | [1f5e93da5d](https://linux-hardware.org/?probe=1f5e93da5d) | Jun 11, 2020 |
| HP            | EliteBook 840 G1            | [abf4039e5c](https://linux-hardware.org/?probe=abf4039e5c) | Jun 11, 2020 |
| HP            | Laptop 14-bs0xx             | [b91a8274aa](https://linux-hardware.org/?probe=b91a8274aa) | Jun 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [48144c145b](https://linux-hardware.org/?probe=48144c145b) | Jun 11, 2020 |
| Dell          | Latitude E5470              | [31a6197816](https://linux-hardware.org/?probe=31a6197816) | Jun 11, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [0b76db5cd2](https://linux-hardware.org/?probe=0b76db5cd2) | Jun 10, 2020 |
| Dell          | Latitude 7490               | [6bf81ba8f3](https://linux-hardware.org/?probe=6bf81ba8f3) | Jun 10, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [b93dafce99](https://linux-hardware.org/?probe=b93dafce99) | Jun 09, 2020 |
| Dell          | Latitude 5480               | [10fc20ceee](https://linux-hardware.org/?probe=10fc20ceee) | Jun 09, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [27b21d21f9](https://linux-hardware.org/?probe=27b21d21f9) | Jun 09, 2020 |
| HP            | Laptop 14-bs0xx             | [88c7defa55](https://linux-hardware.org/?probe=88c7defa55) | Jun 08, 2020 |
| ASUSTek       | X541NA                      | [b8d172d989](https://linux-hardware.org/?probe=b8d172d989) | Jun 08, 2020 |
| ASUSTek       | X541NA                      | [c304a8f6f8](https://linux-hardware.org/?probe=c304a8f6f8) | Jun 08, 2020 |
| HP            | Pavilion g4                 | [cc7f94e1cd](https://linux-hardware.org/?probe=cc7f94e1cd) | Jun 08, 2020 |
| HP            | Pavilion g4                 | [a8d3be0148](https://linux-hardware.org/?probe=a8d3be0148) | Jun 08, 2020 |
| HP            | Laptop 14-bs0xx             | [32b21e20fa](https://linux-hardware.org/?probe=32b21e20fa) | Jun 08, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [35995e9a53](https://linux-hardware.org/?probe=35995e9a53) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [d6bcbe862e](https://linux-hardware.org/?probe=d6bcbe862e) | Jun 05, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [f6ce69be74](https://linux-hardware.org/?probe=f6ce69be74) | Jun 05, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [835562a983](https://linux-hardware.org/?probe=835562a983) | Jun 05, 2020 |
| AMI           | Cherry Trail CR             | [0ba222ad65](https://linux-hardware.org/?probe=0ba222ad65) | Jun 05, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [c074d83c99](https://linux-hardware.org/?probe=c074d83c99) | Jun 04, 2020 |
| HP            | EliteBook 745 G2            | [d1d202e7d3](https://linux-hardware.org/?probe=d1d202e7d3) | Jun 03, 2020 |
| Apple         | MacBookPro9,2               | [0e37132392](https://linux-hardware.org/?probe=0e37132392) | Jun 03, 2020 |
| ASUSTek       | X541NA                      | [51258219c2](https://linux-hardware.org/?probe=51258219c2) | Jun 03, 2020 |
| ASUSTek       | X541NA                      | [52d3f1eccd](https://linux-hardware.org/?probe=52d3f1eccd) | Jun 03, 2020 |
| MSI           | MS-N014                     | [f9d927e8e8](https://linux-hardware.org/?probe=f9d927e8e8) | Jun 03, 2020 |
| Lenovo        | IdeaPad U310                | [df9eae6346](https://linux-hardware.org/?probe=df9eae6346) | Jun 03, 2020 |
| HUAWEI        | KPL-W0X                     | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| Sony          | VPCEG3WFX                   | [eb209bcdb1](https://linux-hardware.org/?probe=eb209bcdb1) | Jun 01, 2020 |
| ASUSTek       | X541NA                      | [3b6f1169ca](https://linux-hardware.org/?probe=3b6f1169ca) | May 29, 2020 |
| Dell          | Inspiron N5050              | [50d2e1431b](https://linux-hardware.org/?probe=50d2e1431b) | May 29, 2020 |
| Dell          | Inspiron N5050              | [a0ad1f624b](https://linux-hardware.org/?probe=a0ad1f624b) | May 29, 2020 |
| HP            | EliteBook 8540w             | [4fb041418f](https://linux-hardware.org/?probe=4fb041418f) | May 29, 2020 |
| HP            | EliteBook 8540w             | [b36f5a9ddf](https://linux-hardware.org/?probe=b36f5a9ddf) | May 28, 2020 |
| Dell          | Inspiron 5584               | [5e0d7c2ec1](https://linux-hardware.org/?probe=5e0d7c2ec1) | May 27, 2020 |
| HP            | ProBook 440 G6              | [2871cd2944](https://linux-hardware.org/?probe=2871cd2944) | May 27, 2020 |
| HP            | Notebook                    | [06a311a209](https://linux-hardware.org/?probe=06a311a209) | May 27, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [add4c19bf6](https://linux-hardware.org/?probe=add4c19bf6) | May 26, 2020 |
| Acer          | Aspire E5-551               | [9cb02e8061](https://linux-hardware.org/?probe=9cb02e8061) | May 25, 2020 |
| ASUSTek       | X540SA                      | [b68266e0e6](https://linux-hardware.org/?probe=b68266e0e6) | May 24, 2020 |
| Lenovo        | ThinkPad L440 20ASA0STLM    | [85d33d9127](https://linux-hardware.org/?probe=85d33d9127) | May 23, 2020 |
| ASUSTek       | X540SA                      | [6da96852bd](https://linux-hardware.org/?probe=6da96852bd) | May 23, 2020 |
| ASUSTek       | X541NA                      | [4fb4f4b3c3](https://linux-hardware.org/?probe=4fb4f4b3c3) | May 21, 2020 |
| HP            | EliteBook 840 G2            | [2deaa8db50](https://linux-hardware.org/?probe=2deaa8db50) | May 21, 2020 |
| ASUSTek       | X541NA                      | [3da0141f0b](https://linux-hardware.org/?probe=3da0141f0b) | May 20, 2020 |
| Dell          | Latitude E6440              | [cb23d3096c](https://linux-hardware.org/?probe=cb23d3096c) | May 19, 2020 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [25ed02b04a](https://linux-hardware.org/?probe=25ed02b04a) | May 19, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c2d5094a2d](https://linux-hardware.org/?probe=c2d5094a2d) | May 18, 2020 |
| HP            | Laptop 15-bw0xx             | [522b796b7f](https://linux-hardware.org/?probe=522b796b7f) | May 16, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [52ab731a04](https://linux-hardware.org/?probe=52ab731a04) | May 16, 2020 |
| Dell          | Inspiron 5520               | [42f13839fc](https://linux-hardware.org/?probe=42f13839fc) | May 15, 2020 |
| HP            | ProBook 655 G1              | [e7efd28e25](https://linux-hardware.org/?probe=e7efd28e25) | May 14, 2020 |
| Sony          | VPCEG3WFX                   | [3e571fdf8f](https://linux-hardware.org/?probe=3e571fdf8f) | May 14, 2020 |
| Dell          | Inspiron 3421               | [6d3b8c8280](https://linux-hardware.org/?probe=6d3b8c8280) | May 14, 2020 |
| Acer          | Aspire 4752                 | [7f2daf70f2](https://linux-hardware.org/?probe=7f2daf70f2) | May 13, 2020 |
| HP            | Notebook                    | [dbed542e5a](https://linux-hardware.org/?probe=dbed542e5a) | May 12, 2020 |
| ASUSTek       | X541NA                      | [e5966e4342](https://linux-hardware.org/?probe=e5966e4342) | May 12, 2020 |
| HP            | Laptop 15-da0xxx            | [3897071746](https://linux-hardware.org/?probe=3897071746) | May 12, 2020 |
| Acer          | Aspire E5-522               | [b4a770be27](https://linux-hardware.org/?probe=b4a770be27) | May 12, 2020 |
| HP            | Notebook                    | [ae11af2244](https://linux-hardware.org/?probe=ae11af2244) | May 10, 2020 |
| HP            | Laptop 15-bw0xx             | [34129109b5](https://linux-hardware.org/?probe=34129109b5) | May 09, 2020 |
| HP            | Notebook                    | [915c735cd9](https://linux-hardware.org/?probe=915c735cd9) | May 08, 2020 |
| HP            | Notebook                    | [c2839b0dbe](https://linux-hardware.org/?probe=c2839b0dbe) | May 08, 2020 |
| ASUSTek       | X541NA                      | [0297320c60](https://linux-hardware.org/?probe=0297320c60) | May 06, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c3b02984d5](https://linux-hardware.org/?probe=c3b02984d5) | May 05, 2020 |
| ASUSTek       | X541NA                      | [4b9f8bab81](https://linux-hardware.org/?probe=4b9f8bab81) | May 05, 2020 |
| ASUSTek       | X541NA                      | [58254b6315](https://linux-hardware.org/?probe=58254b6315) | May 05, 2020 |
| ASUSTek       | X541NA                      | [902e3ec116](https://linux-hardware.org/?probe=902e3ec116) | May 05, 2020 |
| Dell          | Latitude 5480               | [786e8f0318](https://linux-hardware.org/?probe=786e8f0318) | May 05, 2020 |
| HP            | EliteBook 840 G2            | [778f60cd53](https://linux-hardware.org/?probe=778f60cd53) | May 05, 2020 |
| Dell          | Inspiron 3421               | [24b77103fe](https://linux-hardware.org/?probe=24b77103fe) | May 04, 2020 |
| Dell          | Latitude 5480               | [655485ab03](https://linux-hardware.org/?probe=655485ab03) | May 04, 2020 |
| HP            | Pavilion dv5                | [5608c5d048](https://linux-hardware.org/?probe=5608c5d048) | May 02, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [59a0c19077](https://linux-hardware.org/?probe=59a0c19077) | May 02, 2020 |
| Lenovo        | ThinkPad P52s 20LBCTO1WW    | [77b5e42351](https://linux-hardware.org/?probe=77b5e42351) | May 01, 2020 |
| HP            | Pavilion dv5                | [45a5298619](https://linux-hardware.org/?probe=45a5298619) | Apr 30, 2020 |
| Acer          | Aspire E3-112M              | [48bb5c33ea](https://linux-hardware.org/?probe=48bb5c33ea) | Apr 30, 2020 |
| Acer          | Aspire 5252                 | [06d9316dc7](https://linux-hardware.org/?probe=06d9316dc7) | Apr 30, 2020 |
| HP            | Pavilion Notebook           | [3b016a1599](https://linux-hardware.org/?probe=3b016a1599) | Apr 29, 2020 |
| HP            | Laptop 14-dq1xxx            | [16dbe6c7cf](https://linux-hardware.org/?probe=16dbe6c7cf) | Apr 28, 2020 |
| HP            | EliteBook 840 G6            | [3da001fdb1](https://linux-hardware.org/?probe=3da001fdb1) | Apr 25, 2020 |
| ASUSTek       | X441NA                      | [65fec6e1d7](https://linux-hardware.org/?probe=65fec6e1d7) | Apr 23, 2020 |
| ASUSTek       | X441NA                      | [9545894606](https://linux-hardware.org/?probe=9545894606) | Apr 23, 2020 |
| Sony          | VPCEE43EL                   | [2483b8e6b6](https://linux-hardware.org/?probe=2483b8e6b6) | Apr 22, 2020 |
| Sony          | VPCEE43EL                   | [96bf91786c](https://linux-hardware.org/?probe=96bf91786c) | Apr 22, 2020 |
| Samsung       | R580/R590                   | [d7a6640f85](https://linux-hardware.org/?probe=d7a6640f85) | Apr 21, 2020 |
| HP            | Presario V3700              | [0eac5f43d5](https://linux-hardware.org/?probe=0eac5f43d5) | Apr 21, 2020 |
| Sony          | VPCEE43EL                   | [022873c4bf](https://linux-hardware.org/?probe=022873c4bf) | Apr 21, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [adee231cee](https://linux-hardware.org/?probe=adee231cee) | Apr 19, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [d881ea8ef3](https://linux-hardware.org/?probe=d881ea8ef3) | Apr 19, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [a29cfa915c](https://linux-hardware.org/?probe=a29cfa915c) | Apr 19, 2020 |
| Sony          | VPCYB35AL                   | [a96bfb28b5](https://linux-hardware.org/?probe=a96bfb28b5) | Apr 18, 2020 |
| HP            | EliteBook 8460p             | [41c3cb6523](https://linux-hardware.org/?probe=41c3cb6523) | Apr 17, 2020 |
| HP            | EliteBook 8460p             | [e5283d7a27](https://linux-hardware.org/?probe=e5283d7a27) | Apr 17, 2020 |
| Lenovo        | VILG1                       | [a64ec0748d](https://linux-hardware.org/?probe=a64ec0748d) | Apr 16, 2020 |
| ASUSTek       | X505BA                      | [b636e2a22b](https://linux-hardware.org/?probe=b636e2a22b) | Apr 16, 2020 |
| ASUSTek       | X505BA                      | [3c10caf07e](https://linux-hardware.org/?probe=3c10caf07e) | Apr 16, 2020 |
| Dell          | Latitude E7240              | [ff2a028a63](https://linux-hardware.org/?probe=ff2a028a63) | Apr 16, 2020 |
| Toshiba       | Satellite M105              | [060f929e11](https://linux-hardware.org/?probe=060f929e11) | Apr 15, 2020 |
| Toshiba       | Satellite C50D-A            | [73d855f513](https://linux-hardware.org/?probe=73d855f513) | Apr 14, 2020 |
| Apple         | MacBookPro12,1              | [2498026e1d](https://linux-hardware.org/?probe=2498026e1d) | Apr 14, 2020 |
| Gateway       | NV53A                       | [1d3b62bc99](https://linux-hardware.org/?probe=1d3b62bc99) | Apr 13, 2020 |
| Dell          | Latitude E5450              | [7991e0a25d](https://linux-hardware.org/?probe=7991e0a25d) | Apr 12, 2020 |
| HP            | Notebook                    | [ed42a4cdaa](https://linux-hardware.org/?probe=ed42a4cdaa) | Apr 11, 2020 |
| Gateway       | NV53A                       | [4b736beb15](https://linux-hardware.org/?probe=4b736beb15) | Apr 11, 2020 |
| Dell          | Inspiron MXC061             | [e3bb4fc11f](https://linux-hardware.org/?probe=e3bb4fc11f) | Apr 10, 2020 |
| ASUSTek       | X510UAR                     | [f9d15dfa3b](https://linux-hardware.org/?probe=f9d15dfa3b) | Apr 08, 2020 |
| Dell          | G3 3590                     | [357f2b4feb](https://linux-hardware.org/?probe=357f2b4feb) | Apr 08, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [bc59639878](https://linux-hardware.org/?probe=bc59639878) | Apr 07, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [6943c28c65](https://linux-hardware.org/?probe=6943c28c65) | Apr 07, 2020 |
| Dell          | Vostro 3550                 | [b2247bf39b](https://linux-hardware.org/?probe=b2247bf39b) | Apr 07, 2020 |
| Toshiba       | Satellite L55-C             | [c6f3bbf3dd](https://linux-hardware.org/?probe=c6f3bbf3dd) | Apr 06, 2020 |
| Lenovo        | ThinkPad T420 42366Y0       | [b317d53b55](https://linux-hardware.org/?probe=b317d53b55) | Apr 05, 2020 |
| HP            | Notebook                    | [b9fbf34eee](https://linux-hardware.org/?probe=b9fbf34eee) | Apr 04, 2020 |
| Dell          | Studio 1558                 | [36307f44b0](https://linux-hardware.org/?probe=36307f44b0) | Apr 03, 2020 |
| HP            | ProBook 440 G6              | [8d48457b81](https://linux-hardware.org/?probe=8d48457b81) | Apr 02, 2020 |
| Lenovo        | ThinkPad T420 42366Y0       | [ea2e1cbba0](https://linux-hardware.org/?probe=ea2e1cbba0) | Apr 02, 2020 |
| HP            | Pavilion g4                 | [f7cd111c17](https://linux-hardware.org/?probe=f7cd111c17) | Apr 02, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [b7fe03109a](https://linux-hardware.org/?probe=b7fe03109a) | Apr 02, 2020 |
| Gateway       | NE56R                       | [307d646a70](https://linux-hardware.org/?probe=307d646a70) | Apr 01, 2020 |
| HP            | Pavilion g4                 | [685a9ddee6](https://linux-hardware.org/?probe=685a9ddee6) | Apr 01, 2020 |
| ASUSTek       | X510UAR                     | [69161f3f6f](https://linux-hardware.org/?probe=69161f3f6f) | Apr 01, 2020 |
| ASUSTek       | X510UAR                     | [08cc217b36](https://linux-hardware.org/?probe=08cc217b36) | Apr 01, 2020 |
| HP            | OMEN by Laptop 15-dh0xxx    | [6bc5982c0f](https://linux-hardware.org/?probe=6bc5982c0f) | Mar 31, 2020 |
| Dell          | Inspiron 5559               | [7663b99e7a](https://linux-hardware.org/?probe=7663b99e7a) | Mar 31, 2020 |
| HP            | Pavilion g4                 | [686fc6ddb4](https://linux-hardware.org/?probe=686fc6ddb4) | Mar 31, 2020 |
| Gateway       | NE56R                       | [782170d178](https://linux-hardware.org/?probe=782170d178) | Mar 31, 2020 |
| TECH PAD      | XtabFlex 14                 | [6db942d3f0](https://linux-hardware.org/?probe=6db942d3f0) | Mar 30, 2020 |
| TECH PAD      | XtabFlex 14                 | [9b15666730](https://linux-hardware.org/?probe=9b15666730) | Mar 30, 2020 |
| Gateway       | NE56R                       | [830f8cde80](https://linux-hardware.org/?probe=830f8cde80) | Mar 30, 2020 |
| Gateway       | NE56R                       | [4994ba8851](https://linux-hardware.org/?probe=4994ba8851) | Mar 30, 2020 |
| HP            | Notebook                    | [a0236c9d0f](https://linux-hardware.org/?probe=a0236c9d0f) | Mar 28, 2020 |
| HP            | Notebook                    | [e995b4baa0](https://linux-hardware.org/?probe=e995b4baa0) | Mar 28, 2020 |
| HP            | Notebook                    | [6eb7efa78f](https://linux-hardware.org/?probe=6eb7efa78f) | Mar 27, 2020 |
| HP            | Laptop 14-bw0xx             | [c69f89dd0e](https://linux-hardware.org/?probe=c69f89dd0e) | Mar 27, 2020 |
| Apple         | MacBookPro12,1              | [af43ef7ac8](https://linux-hardware.org/?probe=af43ef7ac8) | Mar 25, 2020 |
| Lenovo        | G480 20156                  | [436ab23001](https://linux-hardware.org/?probe=436ab23001) | Mar 25, 2020 |
| ASUSTek       | X455LAB                     | [4a5174a726](https://linux-hardware.org/?probe=4a5174a726) | Mar 24, 2020 |
| Dell          | Inspiron 13-5378            | [242a7e4fdc](https://linux-hardware.org/?probe=242a7e4fdc) | Mar 24, 2020 |
| HP            | Notebook                    | [2a36d04018](https://linux-hardware.org/?probe=2a36d04018) | Mar 23, 2020 |
| Acer          | Aspire 4352                 | [f0db411e92](https://linux-hardware.org/?probe=f0db411e92) | Mar 22, 2020 |
| HP            | EliteBook 840 G6            | [e34f0cec2d](https://linux-hardware.org/?probe=e34f0cec2d) | Mar 21, 2020 |
| HP            | EliteBook 840 G6            | [57e0abd00f](https://linux-hardware.org/?probe=57e0abd00f) | Mar 21, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | [e3e1789744](https://linux-hardware.org/?probe=e3e1789744) | Mar 20, 2020 |
| ASUSTek       | X541NA                      | [3c432560a7](https://linux-hardware.org/?probe=3c432560a7) | Mar 19, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [7bb8688560](https://linux-hardware.org/?probe=7bb8688560) | Mar 19, 2020 |
| HP            | Pavilion tx1000             | [5f8a15817c](https://linux-hardware.org/?probe=5f8a15817c) | Mar 18, 2020 |
| HP            | Pavilion tx1000             | [76f5c62167](https://linux-hardware.org/?probe=76f5c62167) | Mar 18, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [8f55278584](https://linux-hardware.org/?probe=8f55278584) | Mar 18, 2020 |
| HP            | Pavilion Notebook           | [17999c07a4](https://linux-hardware.org/?probe=17999c07a4) | Mar 16, 2020 |
| HP            | EliteBook 840 G6            | [f7db97fb08](https://linux-hardware.org/?probe=f7db97fb08) | Mar 15, 2020 |
| HP            | EliteBook 840 G6            | [e5998f9663](https://linux-hardware.org/?probe=e5998f9663) | Mar 14, 2020 |
| HP            | EliteBook 840 G6            | [c47a892b8d](https://linux-hardware.org/?probe=c47a892b8d) | Mar 14, 2020 |
| HP            | ProBook 6470b               | [b4f56c045b](https://linux-hardware.org/?probe=b4f56c045b) | Mar 14, 2020 |
| Lenovo        | ThinkPad P52 20MAS33F00     | [231f2c2d7c](https://linux-hardware.org/?probe=231f2c2d7c) | Mar 12, 2020 |
| Apple         | MacBookAir4,1               | [801de88bbc](https://linux-hardware.org/?probe=801de88bbc) | Mar 09, 2020 |
| HP            | Notebook                    | [aca3734fcd](https://linux-hardware.org/?probe=aca3734fcd) | Mar 09, 2020 |
| Dell          | Latitude E6430              | [7d66d4dfdb](https://linux-hardware.org/?probe=7d66d4dfdb) | Mar 07, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [c4b9b4ab26](https://linux-hardware.org/?probe=c4b9b4ab26) | Mar 07, 2020 |
| Acer          | Aspire V5-573P              | [6e29e040ea](https://linux-hardware.org/?probe=6e29e040ea) | Mar 06, 2020 |
| Lenovo        | ThinkPad Edge E430 62715... | [a3731b85e7](https://linux-hardware.org/?probe=a3731b85e7) | Mar 05, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [935c7208e3](https://linux-hardware.org/?probe=935c7208e3) | Mar 04, 2020 |
| ASUSTek       | X555DG                      | [f9862b1f7c](https://linux-hardware.org/?probe=f9862b1f7c) | Mar 04, 2020 |
| HP            | OMEN by Laptop 15-dh0xxx    | [bcc7be3d46](https://linux-hardware.org/?probe=bcc7be3d46) | Mar 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [cfdc1dbcf2](https://linux-hardware.org/?probe=cfdc1dbcf2) | Feb 28, 2020 |
| Lenovo        | ThinkPad W520 42844YS       | [9e345a31d7](https://linux-hardware.org/?probe=9e345a31d7) | Feb 27, 2020 |
| ASUSTek       | S301LP                      | [24ed245680](https://linux-hardware.org/?probe=24ed245680) | Feb 26, 2020 |
| ASUSTek       | S301LP                      | [717886fea2](https://linux-hardware.org/?probe=717886fea2) | Feb 26, 2020 |
| Dell          | Latitude 5491               | [053bb4e97a](https://linux-hardware.org/?probe=053bb4e97a) | Feb 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [c38bfbc6d3](https://linux-hardware.org/?probe=c38bfbc6d3) | Feb 25, 2020 |
| Dell          | Latitude 5400               | [c3c4d89f41](https://linux-hardware.org/?probe=c3c4d89f41) | Feb 24, 2020 |
| Lenovo        | ThinkPad T440s 20ARS3CQ0... | [b84fa900ee](https://linux-hardware.org/?probe=b84fa900ee) | Feb 23, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [910129b12f](https://linux-hardware.org/?probe=910129b12f) | Feb 20, 2020 |
| Lenovo        | G485 20136                  | [83eac14ffc](https://linux-hardware.org/?probe=83eac14ffc) | Feb 20, 2020 |
| Razer         | Blade                       | [98b6b5f40d](https://linux-hardware.org/?probe=98b6b5f40d) | Feb 20, 2020 |
| Lenovo        | ThinkPad Edge E430 62715... | [78bb7008d6](https://linux-hardware.org/?probe=78bb7008d6) | Feb 19, 2020 |
| Dell          | Latitude E6410              | [d4c32e834e](https://linux-hardware.org/?probe=d4c32e834e) | Feb 19, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [9bf1701a79](https://linux-hardware.org/?probe=9bf1701a79) | Feb 18, 2020 |
| Acer          | AOD257                      | [42c2447bcf](https://linux-hardware.org/?probe=42c2447bcf) | Feb 18, 2020 |
| HP            | Laptop 15-bs0xx             | [88c7aae3fe](https://linux-hardware.org/?probe=88c7aae3fe) | Feb 18, 2020 |
| HP            | Laptop 15-bs0xx             | [f922d1ec4a](https://linux-hardware.org/?probe=f922d1ec4a) | Feb 18, 2020 |
| ASUSTek       | X441NA                      | [7f2704244a](https://linux-hardware.org/?probe=7f2704244a) | Feb 17, 2020 |
| Acer          | Aspire V5-431               | [a7095637f4](https://linux-hardware.org/?probe=a7095637f4) | Feb 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [000ba4c307](https://linux-hardware.org/?probe=000ba4c307) | Feb 12, 2020 |
| Toshiba       | Satellite L55-C             | [acebd8101e](https://linux-hardware.org/?probe=acebd8101e) | Feb 11, 2020 |
| HP            | Laptop 15-bw0xx             | [68477ff275](https://linux-hardware.org/?probe=68477ff275) | Feb 11, 2020 |
| Dell          | Inspiron 5565               | [236b7d9514](https://linux-hardware.org/?probe=236b7d9514) | Feb 10, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [1dfb87d7bd](https://linux-hardware.org/?probe=1dfb87d7bd) | Feb 10, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [52269a6154](https://linux-hardware.org/?probe=52269a6154) | Feb 09, 2020 |
| ASUSTek       | X441NA                      | [7db3f40611](https://linux-hardware.org/?probe=7db3f40611) | Feb 08, 2020 |
| ASUSTek       | X441NA                      | [0448db985e](https://linux-hardware.org/?probe=0448db985e) | Feb 07, 2020 |
| Dell          | Latitude 7490               | [84de010704](https://linux-hardware.org/?probe=84de010704) | Feb 07, 2020 |
| Acer          | AOD255                      | [b427b5dc95](https://linux-hardware.org/?probe=b427b5dc95) | Feb 06, 2020 |
| ASUSTek       | X541NA                      | [e0fd3ff0fc](https://linux-hardware.org/?probe=e0fd3ff0fc) | Feb 06, 2020 |
| HP            | Compaq Presario CQ40        | [a8c476cd53](https://linux-hardware.org/?probe=a8c476cd53) | Feb 06, 2020 |
| ASUSTek       | X541NA                      | [d1ce0f74bd](https://linux-hardware.org/?probe=d1ce0f74bd) | Feb 05, 2020 |
| Lenovo        | ThinkPad X61s 874824U       | [241e0014cc](https://linux-hardware.org/?probe=241e0014cc) | Feb 04, 2020 |
| Lenovo        | ThinkPad X61s 874824U       | [376bcc78a9](https://linux-hardware.org/?probe=376bcc78a9) | Feb 04, 2020 |
| Apple         | MacBook5,1                  | [e8545416cb](https://linux-hardware.org/?probe=e8545416cb) | Feb 03, 2020 |
| Apple         | MacBook5,1                  | [392e6ba3a8](https://linux-hardware.org/?probe=392e6ba3a8) | Feb 03, 2020 |
| Dell          | Inspiron 1564               | [b80e556643](https://linux-hardware.org/?probe=b80e556643) | Feb 02, 2020 |
| ASUSTek       | X541NA                      | [f0c58cc811](https://linux-hardware.org/?probe=f0c58cc811) | Jan 31, 2020 |
| Dell          | Latitude E5470              | [65eddceddf](https://linux-hardware.org/?probe=65eddceddf) | Jan 29, 2020 |
| Lenovo        | ThinkPad X201 Tablet 309... | [8672dde937](https://linux-hardware.org/?probe=8672dde937) | Jan 28, 2020 |
| Dell          | Latitude E5470              | [f0a1120a51](https://linux-hardware.org/?probe=f0a1120a51) | Jan 27, 2020 |
| Lenovo        | Y50-70 20378                | [39a9917502](https://linux-hardware.org/?probe=39a9917502) | Jan 24, 2020 |
| Lenovo        | Y50-70 20378                | [c34eecb4fb](https://linux-hardware.org/?probe=c34eecb4fb) | Jan 24, 2020 |
| Dell          | Latitude E5530 non-vPro     | [013dfebe2f](https://linux-hardware.org/?probe=013dfebe2f) | Jan 23, 2020 |
| HP            | ZBook 14                    | [c1363da9be](https://linux-hardware.org/?probe=c1363da9be) | Jan 22, 2020 |
| HP            | Notebook                    | [ed91686a18](https://linux-hardware.org/?probe=ed91686a18) | Jan 19, 2020 |
| Dell          | G3 3579                     | [9dad78d944](https://linux-hardware.org/?probe=9dad78d944) | Jan 18, 2020 |
| Dell          | G3 3579                     | [b8a3b38138](https://linux-hardware.org/?probe=b8a3b38138) | Jan 16, 2020 |
| Dell          | G3 3579                     | [7b8dc1b4e7](https://linux-hardware.org/?probe=7b8dc1b4e7) | Jan 16, 2020 |
| ASUSTek       | X541NA                      | [ea69e810d9](https://linux-hardware.org/?probe=ea69e810d9) | Jan 15, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [0ed327df04](https://linux-hardware.org/?probe=0ed327df04) | Jan 14, 2020 |
| Insyde        | B14                         | [f6361c3a7e](https://linux-hardware.org/?probe=f6361c3a7e) | Jan 12, 2020 |
| Dell          | XPS M1330                   | [2e4e1cfdb8](https://linux-hardware.org/?probe=2e4e1cfdb8) | Jan 09, 2020 |
| Dell          | Latitude E6410              | [1840866ecd](https://linux-hardware.org/?probe=1840866ecd) | Jan 09, 2020 |
| Dell          | Latitude E6410              | [2fb00b811c](https://linux-hardware.org/?probe=2fb00b811c) | Jan 09, 2020 |
| Acer          | Aspire E5-573               | [cdb9a90494](https://linux-hardware.org/?probe=cdb9a90494) | Jan 07, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [a64cade811](https://linux-hardware.org/?probe=a64cade811) | Jan 06, 2020 |
| HP            | Pavilion dv4                | [265cdc3301](https://linux-hardware.org/?probe=265cdc3301) | Jan 03, 2020 |
| Lenovo        | Z40-70 20366                | [9f83597911](https://linux-hardware.org/?probe=9f83597911) | Jan 03, 2020 |
| HP            | Laptop 15-bw0xx             | [13a57cad2e](https://linux-hardware.org/?probe=13a57cad2e) | Jan 03, 2020 |
| Toshiba       | Satellite A215              | [47dcd6e7bf](https://linux-hardware.org/?probe=47dcd6e7bf) | Jan 02, 2020 |
| Toshiba       | Satellite A215              | [746c66b8c6](https://linux-hardware.org/?probe=746c66b8c6) | Jan 02, 2020 |
| HP            | Pavilion Notebook           | [aa000969db](https://linux-hardware.org/?probe=aa000969db) | Jan 01, 2020 |
| HP            | Pavilion Notebook           | [261fe45e48](https://linux-hardware.org/?probe=261fe45e48) | Dec 31, 2019 |
| Dell          | Inspiron 5565               | [3c27b4a785](https://linux-hardware.org/?probe=3c27b4a785) | Dec 30, 2019 |
| HP            | Compaq Mini CQ10-400        | [83b74358f7](https://linux-hardware.org/?probe=83b74358f7) | Dec 27, 2019 |
| Toshiba       | Satellite P755              | [c1acd923e1](https://linux-hardware.org/?probe=c1acd923e1) | Dec 26, 2019 |
| HP            | 240 G3                      | [f432e62120](https://linux-hardware.org/?probe=f432e62120) | Dec 24, 2019 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [9285519de9](https://linux-hardware.org/?probe=9285519de9) | Dec 22, 2019 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [2ba3d0ae75](https://linux-hardware.org/?probe=2ba3d0ae75) | Dec 19, 2019 |
| Apple         | MacBookPro8,1               | [2b202b204b](https://linux-hardware.org/?probe=2b202b204b) | Dec 18, 2019 |
| HP            | ProBook 640 G2              | [d937f7c7a3](https://linux-hardware.org/?probe=d937f7c7a3) | Dec 16, 2019 |
| Lenovo        | Y720-15IKB 80VR             | [43ac1a35d7](https://linux-hardware.org/?probe=43ac1a35d7) | Dec 14, 2019 |
| Lenovo        | ThinkPad T460p 20FXS1AQ0... | [ce47638461](https://linux-hardware.org/?probe=ce47638461) | Dec 14, 2019 |
| Dell          | Latitude E7450              | [aedb41cc44](https://linux-hardware.org/?probe=aedb41cc44) | Dec 13, 2019 |
| Dell          | Latitude E7450              | [a48df80cea](https://linux-hardware.org/?probe=a48df80cea) | Dec 13, 2019 |
| Lenovo        | ThinkPad X201 Tablet 298... | [9c774dc87f](https://linux-hardware.org/?probe=9c774dc87f) | Dec 09, 2019 |
| Dell          | Latitude 14 Rugged (5404... | [3ecd36e2dd](https://linux-hardware.org/?probe=3ecd36e2dd) | Dec 08, 2019 |
| Toshiba       | Satellite P755              | [2fae738892](https://linux-hardware.org/?probe=2fae738892) | Dec 05, 2019 |
| HP            | EliteBook 840 G6            | [f32bb8da9a](https://linux-hardware.org/?probe=f32bb8da9a) | Dec 04, 2019 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [8222676bfb](https://linux-hardware.org/?probe=8222676bfb) | Nov 23, 2019 |
| Sony          | VPCEA36FM                   | [44b359d5b3](https://linux-hardware.org/?probe=44b359d5b3) | Nov 23, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [9552ec26f0](https://linux-hardware.org/?probe=9552ec26f0) | Nov 22, 2019 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [d721d41ec7](https://linux-hardware.org/?probe=d721d41ec7) | Nov 21, 2019 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [83fc80837f](https://linux-hardware.org/?probe=83fc80837f) | Nov 21, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [53b65e6ffd](https://linux-hardware.org/?probe=53b65e6ffd) | Nov 17, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [b9830822fd](https://linux-hardware.org/?probe=b9830822fd) | Nov 17, 2019 |
| Acer          | Aspire E5-573               | [5861b2e713](https://linux-hardware.org/?probe=5861b2e713) | Nov 16, 2019 |
| Acer          | Aspire E5-573               | [600ec4fc40](https://linux-hardware.org/?probe=600ec4fc40) | Nov 16, 2019 |
| Lenovo        | ThinkPad W530 2436CTO       | [7d167c3d79](https://linux-hardware.org/?probe=7d167c3d79) | Nov 14, 2019 |
| Toshiba       | NB505                       | [7012b3df03](https://linux-hardware.org/?probe=7012b3df03) | Nov 12, 2019 |
| HP            | Unknown                     | [30076c1eea](https://linux-hardware.org/?probe=30076c1eea) | Nov 02, 2019 |
| HP            | Unknown                     | [6ae280e378](https://linux-hardware.org/?probe=6ae280e378) | Nov 02, 2019 |
| HP            | Laptop 15-bw0xx             | [86077c7759](https://linux-hardware.org/?probe=86077c7759) | Oct 26, 2019 |
| HP            | Laptop 15-bw0xx             | [9ced23c64f](https://linux-hardware.org/?probe=9ced23c64f) | Oct 26, 2019 |
| Apple         | MacBook4,1                  | [3a850564bc](https://linux-hardware.org/?probe=3a850564bc) | Oct 23, 2019 |
| Gateway       | NV47H                       | [38ee8c70cc](https://linux-hardware.org/?probe=38ee8c70cc) | Oct 21, 2019 |
| Gateway       | NV47H                       | [943b8827cb](https://linux-hardware.org/?probe=943b8827cb) | Oct 21, 2019 |
| Gateway       | NV47H                       | [063d956190](https://linux-hardware.org/?probe=063d956190) | Oct 21, 2019 |
| HP            | 455                         | [53782ccce3](https://linux-hardware.org/?probe=53782ccce3) | Oct 20, 2019 |
| HP            | Laptop 14-ck0xxx            | [6834f4bc15](https://linux-hardware.org/?probe=6834f4bc15) | Oct 17, 2019 |
| HP            | Notebook                    | [280cc65530](https://linux-hardware.org/?probe=280cc65530) | Oct 16, 2019 |
| HP            | Notebook                    | [528ac3c680](https://linux-hardware.org/?probe=528ac3c680) | Oct 16, 2019 |
| HP            | Laptop 14-ck0xxx            | [969fea5d03](https://linux-hardware.org/?probe=969fea5d03) | Oct 15, 2019 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [6e5919edb5](https://linux-hardware.org/?probe=6e5919edb5) | Oct 14, 2019 |
| ASUSTek       | X441NA                      | [89cca94cdf](https://linux-hardware.org/?probe=89cca94cdf) | Oct 14, 2019 |
| ASUSTek       | X441NA                      | [9ce590427c](https://linux-hardware.org/?probe=9ce590427c) | Oct 13, 2019 |
| Dell          | Latitude E6410              | [1d58a5316e](https://linux-hardware.org/?probe=1d58a5316e) | Oct 11, 2019 |
| Dell          | Latitude E6410              | [ca058f7365](https://linux-hardware.org/?probe=ca058f7365) | Oct 11, 2019 |
| Dell          | Latitude E6410              | [d70ba21dda](https://linux-hardware.org/?probe=d70ba21dda) | Oct 11, 2019 |
| Toshiba       | Satellite L845              | [f39187603d](https://linux-hardware.org/?probe=f39187603d) | Oct 09, 2019 |
| Dell          | Latitude E6220              | [e0e18094ad](https://linux-hardware.org/?probe=e0e18094ad) | Oct 06, 2019 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [eb20dc01d8](https://linux-hardware.org/?probe=eb20dc01d8) | Oct 06, 2019 |
| BenQ          | KTV00                       | [b8ce5070c7](https://linux-hardware.org/?probe=b8ce5070c7) | Oct 05, 2019 |
| BenQ          | KTV00                       | [2eecadf154](https://linux-hardware.org/?probe=2eecadf154) | Oct 05, 2019 |
| HP            | ENVY Laptop 13-ah0xxx       | [b1e0f41323](https://linux-hardware.org/?probe=b1e0f41323) | Oct 04, 2019 |
| Acer          | AO725                       | [47615b437f](https://linux-hardware.org/?probe=47615b437f) | Oct 03, 2019 |
| Sony          | VPCEH2JFX                   | [5bc6ebd718](https://linux-hardware.org/?probe=5bc6ebd718) | Oct 01, 2019 |
| Acer          | Nitro AN515-51              | [9afa037539](https://linux-hardware.org/?probe=9afa037539) | Sep 28, 2019 |
| Dell          | Latitude E5450              | [001f6a7015](https://linux-hardware.org/?probe=001f6a7015) | Sep 26, 2019 |
| Dell          | Latitude D505               | [4ebb330bf9](https://linux-hardware.org/?probe=4ebb330bf9) | Sep 26, 2019 |
| Dell          | Latitude D505               | [67f24d0ec2](https://linux-hardware.org/?probe=67f24d0ec2) | Sep 26, 2019 |
| Dell          | Latitude E5450              | [116078fd22](https://linux-hardware.org/?probe=116078fd22) | Sep 26, 2019 |
| Dell          | Latitude E5450              | [6fef8c47b3](https://linux-hardware.org/?probe=6fef8c47b3) | Sep 26, 2019 |
| HP            | Notebook                    | [ace4010918](https://linux-hardware.org/?probe=ace4010918) | Sep 24, 2019 |
| HP            | Unknown                     | [8e27aa5946](https://linux-hardware.org/?probe=8e27aa5946) | Sep 23, 2019 |
| HP            | Unknown                     | [d15c887163](https://linux-hardware.org/?probe=d15c887163) | Sep 23, 2019 |
| HP            | Unknown                     | [f4a59f9a78](https://linux-hardware.org/?probe=f4a59f9a78) | Sep 23, 2019 |
| Toshiba       | Satellite U305              | [a2bce6c4a7](https://linux-hardware.org/?probe=a2bce6c4a7) | Sep 22, 2019 |
| HP            | Notebook                    | [50df3b1711](https://linux-hardware.org/?probe=50df3b1711) | Sep 19, 2019 |
| HP            | Pavilion 17                 | [19543857cc](https://linux-hardware.org/?probe=19543857cc) | Sep 17, 2019 |
| HP            | Unknown                     | [bdb1268aa5](https://linux-hardware.org/?probe=bdb1268aa5) | Sep 12, 2019 |
| HP            | Unknown                     | [9f595190df](https://linux-hardware.org/?probe=9f595190df) | Sep 12, 2019 |
| HP            | Unknown                     | [eff1f02e0f](https://linux-hardware.org/?probe=eff1f02e0f) | Sep 11, 2019 |
| Lenovo        | ThinkPad T480 20L50011US    | [4c19881af9](https://linux-hardware.org/?probe=4c19881af9) | Sep 06, 2019 |
| HP            | ENVY Laptop 13-ah0xxx       | [0fb9118d8e](https://linux-hardware.org/?probe=0fb9118d8e) | Sep 05, 2019 |
| HP            | 240 G4 Notebook PC          | [f017e25c1b](https://linux-hardware.org/?probe=f017e25c1b) | Sep 04, 2019 |
| Acer          | Aspire ES1-571              | [d24a1a7f29](https://linux-hardware.org/?probe=d24a1a7f29) | Sep 04, 2019 |
| Acer          | AOD255E                     | [80b480a2a6](https://linux-hardware.org/?probe=80b480a2a6) | Sep 03, 2019 |
| HP            | Unknown                     | [47e15bceb4](https://linux-hardware.org/?probe=47e15bceb4) | Aug 30, 2019 |
| Alienware     | m15x                        | [7e166afa9d](https://linux-hardware.org/?probe=7e166afa9d) | Aug 30, 2019 |
| Alienware     | m15x                        | [621b6c19b0](https://linux-hardware.org/?probe=621b6c19b0) | Aug 30, 2019 |
| Alienware     | m15x                        | [369f343406](https://linux-hardware.org/?probe=369f343406) | Aug 30, 2019 |
| HP            | Laptop 15-bw0xx             | [f05db4fe05](https://linux-hardware.org/?probe=f05db4fe05) | Aug 22, 2019 |
| ASUSTek       | X555QA                      | [2bc3de5c8c](https://linux-hardware.org/?probe=2bc3de5c8c) | Aug 15, 2019 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [e9fba15cd9](https://linux-hardware.org/?probe=e9fba15cd9) | Aug 15, 2019 |
| HP            | Notebook                    | [f10fd89f8a](https://linux-hardware.org/?probe=f10fd89f8a) | Aug 10, 2019 |
| Dell          | Inspiron 1545               | [1a34250605](https://linux-hardware.org/?probe=1a34250605) | Aug 06, 2019 |
| Acer          | Nitro AN515-51              | [c80caabfc9](https://linux-hardware.org/?probe=c80caabfc9) | Jul 26, 2019 |
| Acer          | Nitro AN515-51              | [c633a79bd3](https://linux-hardware.org/?probe=c633a79bd3) | Jul 26, 2019 |
| HP            | ENVY Laptop 13-ah0xxx       | [24a04ca275](https://linux-hardware.org/?probe=24a04ca275) | Jul 25, 2019 |
| Dell          | Latitude E7240              | [ca9c198099](https://linux-hardware.org/?probe=ca9c198099) | Jul 24, 2019 |
| Dell          | Latitude E7240              | [dfc4c9b154](https://linux-hardware.org/?probe=dfc4c9b154) | Jul 24, 2019 |
| Gateway       | NE46R                       | [11b9c937c9](https://linux-hardware.org/?probe=11b9c937c9) | Jul 24, 2019 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [4df42728b2](https://linux-hardware.org/?probe=4df42728b2) | Jul 24, 2019 |
| HP            | 240 G5 Notebook PC          | [315b95ad61](https://linux-hardware.org/?probe=315b95ad61) | Jul 22, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | [788cb4019c](https://linux-hardware.org/?probe=788cb4019c) | Jul 21, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | [cd8307531c](https://linux-hardware.org/?probe=cd8307531c) | Jul 21, 2019 |
| Google        | Candy                       | [32438812a5](https://linux-hardware.org/?probe=32438812a5) | Jul 18, 2019 |
| HP            | Laptop 15-bs0xx             | [ed8af41b6e](https://linux-hardware.org/?probe=ed8af41b6e) | Jul 17, 2019 |
| Sony          | VPCYB35AL                   | [569b9b8b32](https://linux-hardware.org/?probe=569b9b8b32) | Jul 17, 2019 |
| Acer          | AOA150                      | [5da90f3771](https://linux-hardware.org/?probe=5da90f3771) | Jul 15, 2019 |
| HP            | Laptop 15-da0xxx            | [d6c8e34b95](https://linux-hardware.org/?probe=d6c8e34b95) | Jul 14, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7f7856d313](https://linux-hardware.org/?probe=7f7856d313) | Jul 13, 2019 |
| HP            | Notebook                    | [8c487be380](https://linux-hardware.org/?probe=8c487be380) | Jul 09, 2019 |
| HP            | Notebook                    | [12257f307f](https://linux-hardware.org/?probe=12257f307f) | Jul 05, 2019 |
| HUAWEI        | VLT-WX0                     | [67efa34926](https://linux-hardware.org/?probe=67efa34926) | Jul 03, 2019 |
| HP            | Unknown                     | [1184f5572b](https://linux-hardware.org/?probe=1184f5572b) | Jul 02, 2019 |
| HP            | Unknown                     | [a2a49e8ef7](https://linux-hardware.org/?probe=a2a49e8ef7) | Jul 02, 2019 |
| HP            | Laptop 14-bs0xx             | [402fa5458c](https://linux-hardware.org/?probe=402fa5458c) | Jun 28, 2019 |
| Acer          | AOA150                      | [75927be93c](https://linux-hardware.org/?probe=75927be93c) | Jun 24, 2019 |
| Lenovo        | ThinkPad L480 20LTS55300    | [2e8e0a1cd1](https://linux-hardware.org/?probe=2e8e0a1cd1) | Jun 23, 2019 |
| Acer          | Aspire V5-473P              | [44dc7d96c7](https://linux-hardware.org/?probe=44dc7d96c7) | Jun 22, 2019 |
| Acer          | Aspire V5-473P              | [b774e9e530](https://linux-hardware.org/?probe=b774e9e530) | Jun 22, 2019 |
| Toshiba       | Satellite Pro L750          | [3c40eeb687](https://linux-hardware.org/?probe=3c40eeb687) | Jun 21, 2019 |
| Toshiba       | Satellite Pro L750          | [ad23ab1660](https://linux-hardware.org/?probe=ad23ab1660) | Jun 21, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [6bcfb65563](https://linux-hardware.org/?probe=6bcfb65563) | Jun 18, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [6073bf9b88](https://linux-hardware.org/?probe=6073bf9b88) | Jun 18, 2019 |
| Toshiba       | Satellite P755              | [d9fc00d39e](https://linux-hardware.org/?probe=d9fc00d39e) | Jun 17, 2019 |
| HP            | Laptop 15-da0xxx            | [262f7958e6](https://linux-hardware.org/?probe=262f7958e6) | Jun 17, 2019 |
| Dell          | Studio 1558                 | [a3f3eb5872](https://linux-hardware.org/?probe=a3f3eb5872) | Jun 16, 2019 |
| Lenovo        | ThinkPad L480 20LTS55300    | [f217bc45ca](https://linux-hardware.org/?probe=f217bc45ca) | Jun 16, 2019 |
| Dell          | Inspiron 5423               | [2ef2a4013d](https://linux-hardware.org/?probe=2ef2a4013d) | Jun 14, 2019 |
| Dell          | Latitude E6220              | [79b2a2d980](https://linux-hardware.org/?probe=79b2a2d980) | Jun 11, 2019 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [e1cd9fd6c1](https://linux-hardware.org/?probe=e1cd9fd6c1) | Jun 10, 2019 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [cc5cadc107](https://linux-hardware.org/?probe=cc5cadc107) | Jun 10, 2019 |
| Panasonic     | CF-52PFNBX2M                | [400317e66e](https://linux-hardware.org/?probe=400317e66e) | May 31, 2019 |
| Lenovo        | ThinkPad L440 20ASA0STLM    | [7bb11c44a8](https://linux-hardware.org/?probe=7bb11c44a8) | May 31, 2019 |
| Acer          | Aspire E1-421               | [966134dd8f](https://linux-hardware.org/?probe=966134dd8f) | May 27, 2019 |
| Sony          | VPCEB25FL                   | [c88a9f6269](https://linux-hardware.org/?probe=c88a9f6269) | May 23, 2019 |
| Acer          | Aspire E5-573               | [ca27efc86b](https://linux-hardware.org/?probe=ca27efc86b) | May 22, 2019 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [3ef3ee8b41](https://linux-hardware.org/?probe=3ef3ee8b41) | May 22, 2019 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [b83a3e25e7](https://linux-hardware.org/?probe=b83a3e25e7) | May 22, 2019 |
| HP            | Laptop 15-da0xxx            | [369c8f2a12](https://linux-hardware.org/?probe=369c8f2a12) | May 19, 2019 |
| HP            | Laptop 14-cf0xxx            | [7b60495aed](https://linux-hardware.org/?probe=7b60495aed) | May 17, 2019 |
| Acer          | Aspire E5-411               | [60681259fd](https://linux-hardware.org/?probe=60681259fd) | May 16, 2019 |
| HP            | Laptop 15-da0xxx            | [defe0773a6](https://linux-hardware.org/?probe=defe0773a6) | May 13, 2019 |
| Gateway       | MX6940M                     | [668db92873](https://linux-hardware.org/?probe=668db92873) | May 09, 2019 |
| ASUSTek       | E402NA                      | [e0cf330ee2](https://linux-hardware.org/?probe=e0cf330ee2) | May 08, 2019 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | [2a19bf5724](https://linux-hardware.org/?probe=2a19bf5724) | May 07, 2019 |
| Dell          | Inspiron MP061              | [8557ccf8d1](https://linux-hardware.org/?probe=8557ccf8d1) | May 06, 2019 |
| Lenovo        | Z40-70 20366                | [5872e2bad1](https://linux-hardware.org/?probe=5872e2bad1) | May 06, 2019 |
| Dell          | Inspiron 5559               | [27a6ab8a2e](https://linux-hardware.org/?probe=27a6ab8a2e) | May 04, 2019 |
| Hannspree     | SN12E200                    | [927279dc7f](https://linux-hardware.org/?probe=927279dc7f) | May 01, 2019 |
| Lenovo        | Z40-70 20366                | [abbc791872](https://linux-hardware.org/?probe=abbc791872) | Apr 28, 2019 |
| HP            | Laptop 15-da0xxx            | [221ba50e67](https://linux-hardware.org/?probe=221ba50e67) | Apr 28, 2019 |
| Toshiba       | Satellite L455D             | [bafd1696ab](https://linux-hardware.org/?probe=bafd1696ab) | Apr 26, 2019 |
| HP            | ENVY 14                     | [15ab3c7abf](https://linux-hardware.org/?probe=15ab3c7abf) | Apr 26, 2019 |
| Dell          | Latitude E7240              | [24d1c1fabd](https://linux-hardware.org/?probe=24d1c1fabd) | Apr 25, 2019 |
| Toshiba       | Satellite T215D             | [3bf39d603e](https://linux-hardware.org/?probe=3bf39d603e) | Apr 18, 2019 |
| Toshiba       | Satellite T215D             | [8ebb39776a](https://linux-hardware.org/?probe=8ebb39776a) | Apr 18, 2019 |
| Apple         | MacBookAir6,1               | [c7366c6491](https://linux-hardware.org/?probe=c7366c6491) | Apr 13, 2019 |
| Apple         | MacBookAir6,1               | [256b1b59ee](https://linux-hardware.org/?probe=256b1b59ee) | Apr 13, 2019 |
| Dell          | Vostro 5470                 | [e106741644](https://linux-hardware.org/?probe=e106741644) | Apr 10, 2019 |
| HP            | Laptop 14-ck0xxx            | [d430ed846e](https://linux-hardware.org/?probe=d430ed846e) | Apr 06, 2019 |
| Dell          | Latitude E6430              | [c41045e39b](https://linux-hardware.org/?probe=c41045e39b) | Apr 04, 2019 |
| HP            | Laptop 15-da0xxx            | [00eebe5ef9](https://linux-hardware.org/?probe=00eebe5ef9) | Apr 04, 2019 |
| Dell          | Latitude E6430              | [baa0bc08fe](https://linux-hardware.org/?probe=baa0bc08fe) | Apr 04, 2019 |
| Dell          | Latitude E6430              | [7a1779c1fa](https://linux-hardware.org/?probe=7a1779c1fa) | Apr 03, 2019 |
| HP            | EliteBook 8460p             | [86301cabac](https://linux-hardware.org/?probe=86301cabac) | Mar 26, 2019 |
| Toshiba       | Satellite L655D             | [1b336889a7](https://linux-hardware.org/?probe=1b336889a7) | Mar 24, 2019 |
| Acer          | Aspire 1410                 | [00a29f0866](https://linux-hardware.org/?probe=00a29f0866) | Mar 23, 2019 |
| HP            | Laptop 15-da0xxx            | [4affbdeb95](https://linux-hardware.org/?probe=4affbdeb95) | Mar 23, 2019 |
| HP            | ProBook 6560b               | [8f832ad1b8](https://linux-hardware.org/?probe=8f832ad1b8) | Mar 22, 2019 |
| Lenovo        | ThinkPad E490s 20NGCTO1W... | [3cfd2cd856](https://linux-hardware.org/?probe=3cfd2cd856) | Mar 21, 2019 |
| Lenovo        | Y720-15IKB 80VR             | [5912bca027](https://linux-hardware.org/?probe=5912bca027) | Mar 12, 2019 |
| ASUSTek       | K54HR                       | [811bd2044b](https://linux-hardware.org/?probe=811bd2044b) | Mar 11, 2019 |
| Apple         | MacBookPro11,1              | [c84275fd05](https://linux-hardware.org/?probe=c84275fd05) | Feb 28, 2019 |
| HP            | 15                          | [c0412b10c3](https://linux-hardware.org/?probe=c0412b10c3) | Feb 27, 2019 |
| HP            | Pavilion g4                 | [0c9e0f4767](https://linux-hardware.org/?probe=0c9e0f4767) | Feb 02, 2019 |
| HP            | Pavilion g4                 | [429216ae74](https://linux-hardware.org/?probe=429216ae74) | Feb 02, 2019 |
| HP            | EliteBook 8460p             | [75f7ec794f](https://linux-hardware.org/?probe=75f7ec794f) | Jan 26, 2019 |
| HP            | Pavilion g7                 | [b9085e4b0a](https://linux-hardware.org/?probe=b9085e4b0a) | Jan 20, 2019 |
| HP            | Notebook                    | [2495b19c7e](https://linux-hardware.org/?probe=2495b19c7e) | Jan 14, 2019 |
| HP            | Notebook                    | [36169cf6a3](https://linux-hardware.org/?probe=36169cf6a3) | Jan 14, 2019 |
| Lenovo        | IdeaPad Y550 20017          | [20eec08e14](https://linux-hardware.org/?probe=20eec08e14) | Jan 13, 2019 |
| ASUSTek       | X555DG                      | [70a046ff8d](https://linux-hardware.org/?probe=70a046ff8d) | Jan 10, 2019 |
| Acer          | AO532h                      | [9cbd769d05](https://linux-hardware.org/?probe=9cbd769d05) | Jan 06, 2019 |
| HP            | Compaq Presario CQ50        | [dbce37e351](https://linux-hardware.org/?probe=dbce37e351) | Dec 17, 2018 |
| Lenovo        | IdeaPad Y550 20017          | [16c2fdf222](https://linux-hardware.org/?probe=16c2fdf222) | Nov 27, 2018 |
| Lenovo        | ThinkPad L560 20F2A0GWLM    | [87ac0729e6](https://linux-hardware.org/?probe=87ac0729e6) | Nov 21, 2018 |
| Lenovo        | ThinkPad L560 20F2A0GWLM    | [de287d73dc](https://linux-hardware.org/?probe=de287d73dc) | Nov 18, 2018 |
| Lenovo        | ThinkPad L560 20F2A0GWLM    | [8f8807630a](https://linux-hardware.org/?probe=8f8807630a) | Nov 18, 2018 |
| Alienware     | 17 R5                       | [3996651d78](https://linux-hardware.org/?probe=3996651d78) | Nov 18, 2018 |
| Alienware     | 17 R5                       | [e53cebefbb](https://linux-hardware.org/?probe=e53cebefbb) | Nov 18, 2018 |
| Alienware     | 17 R5                       | [ff499350ac](https://linux-hardware.org/?probe=ff499350ac) | Nov 18, 2018 |
| Alienware     | 17 R5                       | [aca7993158](https://linux-hardware.org/?probe=aca7993158) | Nov 17, 2018 |
| Alienware     | 17 R5                       | [39a0032bfe](https://linux-hardware.org/?probe=39a0032bfe) | Nov 17, 2018 |
| Alienware     | 17 R5                       | [4fad45b9cd](https://linux-hardware.org/?probe=4fad45b9cd) | Nov 17, 2018 |
| Alienware     | 17 R5                       | [3fbdbb7e9c](https://linux-hardware.org/?probe=3fbdbb7e9c) | Nov 17, 2018 |
| Alienware     | 17 R5                       | [94e9aa6095](https://linux-hardware.org/?probe=94e9aa6095) | Nov 17, 2018 |
| Lenovo        | ThinkPad X201 36809T7       | [935c012353](https://linux-hardware.org/?probe=935c012353) | Sep 10, 2018 |
| HP            | ENVY m4                     | [6996375996](https://linux-hardware.org/?probe=6996375996) | Feb 28, 2018 |
| Lenovo        | ThinkPad T420 4180C99       | [4f95c28e80](https://linux-hardware.org/?probe=4f95c28e80) | Feb 26, 2018 |
| Lenovo        | ThinkPad T530 23945ZS       | [4638250924](https://linux-hardware.org/?probe=4638250924) | Dec 31, 2017 |
| HP            | Pavilion g4                 | [2ae6ba2cd2](https://linux-hardware.org/?probe=2ae6ba2cd2) | Aug 25, 2017 |
| Toshiba       | Satellite S40Dt-A           | [0f518acfc3](https://linux-hardware.org/?probe=0f518acfc3) | Jul 11, 2017 |
| Dell          | Latitude E6400              | [27413a0bd2](https://linux-hardware.org/?probe=27413a0bd2) | Jun 15, 2017 |
| HP            | Pavilion dv2700             | [03fdc915f0](https://linux-hardware.org/?probe=03fdc915f0) | Oct 03, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Mexico/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 159       | 14.38%  |
| Ubuntu 18.04                 | 113       | 10.22%  |
| OpenMandriva 4.2             | 43        | 3.89%   |
| KDE neon 20.04               | 30        | 2.71%   |
| Manjaro                      | 29        | 2.62%   |
| OpenMandriva 4.3             | 27        | 2.44%   |
| Zorin 16                     | 25        | 2.26%   |
| Debian 11                    | 24        | 2.17%   |
| Pop!_OS 20.04                | 23        | 2.08%   |
| Arch                         | 20        | 1.81%   |
| Zorin 15                     | 19        | 1.72%   |
| Linux Mint 20                | 19        | 1.72%   |
| Ubuntu 19.10                 | 18        | 1.63%   |
| Ubuntu 19.04                 | 18        | 1.63%   |
| Linux Mint 20.3              | 18        | 1.63%   |
| Linux Mint 19.3              | 17        | 1.54%   |
| Ubuntu 22.04                 | 16        | 1.45%   |
| Fedora 36                    | 16        | 1.45%   |
| Debian 10                    | 16        | 1.45%   |
| Ubuntu 21.10                 | 15        | 1.36%   |
| Pop!_OS 21.04                | 15        | 1.36%   |
| Kubuntu 20.04                | 15        | 1.36%   |
| Xubuntu 18.04                | 14        | 1.27%   |
| Ubuntu 20.10                 | 14        | 1.27%   |
| Fedora 35                    | 14        | 1.27%   |
| Fedora 34                    | 14        | 1.27%   |
| Linux Mint 20.1              | 13        | 1.18%   |
| Ubuntu 16.04                 | 12        | 1.08%   |
| Fedora 32                    | 12        | 1.08%   |
| Xubuntu 20.04                | 10        | 0.9%    |
| Ubuntu 21.04                 | 9         | 0.81%   |
| Pop!_OS 20.10                | 8         | 0.72%   |
| Fedora 33                    | 8         | 0.72%   |
| Fedora 31                    | 8         | 0.72%   |
| Ubuntu 18.10                 | 7         | 0.63%   |
| Pop!_OS 22.04                | 7         | 0.63%   |
| Elementary 6.1               | 7         | 0.63%   |
| LMDE 4                       | 6         | 0.54%   |
| Linux Mint 20.2              | 6         | 0.54%   |
| Linux Mint 19.2              | 6         | 0.54%   |
| Elementary 5.1.7             | 6         | 0.54%   |
| Arch Rolling                 | 6         | 0.54%   |
| Pop!_OS 21.10                | 5         | 0.45%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 0.45%   |
| Manjaro 20.2.1               | 5         | 0.45%   |
| Zorin 12                     | 4         | 0.36%   |
| ROSA R9                      | 4         | 0.36%   |
| ROSA R11.1                   | 4         | 0.36%   |
| ROSA R10                     | 4         | 0.36%   |
| Lubuntu 20.04                | 4         | 0.36%   |
| KDE neon 18.04               | 4         | 0.36%   |
| Garuda Linux Soaring         | 4         | 0.36%   |
| Fedora 30                    | 4         | 0.36%   |
| CentOS 8                     | 4         | 0.36%   |
| ArcoLinux Rolling            | 4         | 0.36%   |
| Ubuntu Budgie 20.04          | 3         | 0.27%   |
| RHEL 8                       | 3         | 0.27%   |
| openSUSE Leap-15.2           | 3         | 0.27%   |
| OpenMandriva 4.50            | 3         | 0.27%   |
| LMDE 5                       | 3         | 0.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 371       | 34.61%  |
| Linux Mint       | 80        | 7.46%   |
| OpenMandriva     | 74        | 6.9%    |
| Fedora           | 71        | 6.62%   |
| Pop!_OS          | 57        | 5.32%   |
| Manjaro          | 50        | 4.66%   |
| Zorin            | 48        | 4.48%   |
| Debian           | 46        | 4.29%   |
| KDE neon         | 34        | 3.17%   |
| Xubuntu          | 28        | 2.61%   |
| Kubuntu          | 27        | 2.52%   |
| Arch             | 26        | 2.43%   |
| Elementary       | 18        | 1.68%   |
| ROSA             | 14        | 1.31%   |
| Kali             | 13        | 1.21%   |
| openSUSE         | 12        | 1.12%   |
| Endless          | 11        | 1.03%   |
| LMDE             | 9         | 0.84%   |
| Clear Linux      | 9         | 0.84%   |
| Ubuntu Budgie    | 8         | 0.75%   |
| Lubuntu          | 7         | 0.65%   |
| Garuda Linux     | 5         | 0.47%   |
| CentOS           | 5         | 0.47%   |
| Ubuntu MATE      | 4         | 0.37%   |
| MX               | 4         | 0.37%   |
| Gentoo           | 4         | 0.37%   |
| EndeavourOS      | 4         | 0.37%   |
| ArcoLinux        | 4         | 0.37%   |
| RHEL             | 3         | 0.28%   |
| Peppermint       | 3         | 0.28%   |
| Parrot           | 3         | 0.28%   |
| Reborn OS        | 2         | 0.19%   |
| LinuxFX          | 2         | 0.19%   |
| BlackPanther     | 2         | 0.19%   |
| UbuntuDDE        | 1         | 0.09%   |
| Ubuntu Studio    | 1         | 0.09%   |
| Trisquel         | 1         | 0.09%   |
| Solus            | 1         | 0.09%   |
| Slackware        | 1         | 0.09%   |
| org.kde.Platform | 1         | 0.09%   |
| Mageia           | 1         | 0.09%   |
| Linux Lite       | 1         | 0.09%   |
| KaOS             | 1         | 0.09%   |
| Devuan           | 1         | 0.09%   |
| Deepin           | 1         | 0.09%   |
| Archcraft        | 1         | 0.09%   |
| antiX            | 1         | 0.09%   |
| Alpine           | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 43        | 3.56%   |
| 5.4.0-42-generic         | 27        | 2.24%   |
| 5.16.7-desktop-1omv4003  | 27        | 2.24%   |
| 5.4.0-58-generic         | 17        | 1.41%   |
| 5.4.0-52-generic         | 14        | 1.16%   |
| 5.3.0-46-generic         | 14        | 1.16%   |
| 5.4.0-48-generic         | 12        | 0.99%   |
| 5.11.0-27-generic        | 12        | 0.99%   |
| 5.0.0-37-generic         | 12        | 0.99%   |
| 5.3.0-40-generic         | 11        | 0.91%   |
| 5.4.0-91-generic         | 10        | 0.83%   |
| 5.3.0-42-generic         | 10        | 0.83%   |
| 5.13.0-39-generic        | 10        | 0.83%   |
| 5.13.0-28-generic        | 10        | 0.83%   |
| 5.11.0-43-generic        | 10        | 0.83%   |
| 5.4.0-7642-generic       | 9         | 0.75%   |
| 5.4.0-74-generic         | 9         | 0.75%   |
| 5.4.0-65-generic         | 9         | 0.75%   |
| 5.4.0-45-generic         | 9         | 0.75%   |
| 5.3.0-28-generic         | 9         | 0.75%   |
| 5.13.0-40-generic        | 9         | 0.75%   |
| 5.11.0-7620-generic      | 9         | 0.75%   |
| 5.11.0-37-generic        | 9         | 0.75%   |
| 5.8.0-43-generic         | 8         | 0.66%   |
| 5.4.0-37-generic         | 8         | 0.66%   |
| 4.18.0-25-generic        | 8         | 0.66%   |
| 4.18.0-15-generic        | 8         | 0.66%   |
| 5.4.0-7634-generic       | 7         | 0.58%   |
| 5.4.0-40-generic         | 7         | 0.58%   |
| 5.4.0-33-generic         | 7         | 0.58%   |
| 5.13.0-44-generic        | 7         | 0.58%   |
| 5.0.0-32-generic         | 7         | 0.58%   |
| 4.15.0-54-generic        | 7         | 0.58%   |
| 5.4.0-72-generic         | 6         | 0.5%    |
| 5.4.0-56-generic         | 6         | 0.5%    |
| 5.4.0-54-generic         | 6         | 0.5%    |
| 5.4.0-29-generic         | 6         | 0.5%    |
| 5.4.0-26-generic         | 6         | 0.5%    |
| 5.15.0-41-generic        | 6         | 0.5%    |
| 5.13.0-7614-generic      | 6         | 0.5%    |
| 5.11.0-34-generic        | 6         | 0.5%    |
| 5.11.0-25-generic        | 6         | 0.5%    |
| 5.10.0-9-amd64           | 6         | 0.5%    |
| 5.10.0-8-amd64           | 6         | 0.5%    |
| 5.0.0-29-generic         | 6         | 0.5%    |
| 5.8.0-7630-generic       | 5         | 0.41%   |
| 5.8.0-53-generic         | 5         | 0.41%   |
| 5.8.0-41-generic         | 5         | 0.41%   |
| 5.8.0-14-generic         | 5         | 0.41%   |
| 5.4.0-80-generic         | 5         | 0.41%   |
| 5.4.0-77-generic         | 5         | 0.41%   |
| 5.3.0-51-generic         | 5         | 0.41%   |
| 5.3.0-26-generic         | 5         | 0.41%   |
| 5.11.0-41-generic        | 5         | 0.41%   |
| 5.11.0-40-generic        | 5         | 0.41%   |
| 5.11.0-38-generic        | 5         | 0.41%   |
| 5.0.0-27-generic         | 5         | 0.41%   |
| 4.18.0-20-generic        | 5         | 0.41%   |
| 5.9.1-arch1-1            | 4         | 0.33%   |
| 5.8.0-63-generic         | 4         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 222       | 19.65%  |
| 5.11.0  | 85        | 7.52%   |
| 5.3.0   | 72        | 6.37%   |
| 5.8.0   | 71        | 6.28%   |
| 5.13.0  | 71        | 6.28%   |
| 4.15.0  | 64        | 5.66%   |
| 5.0.0   | 54        | 4.78%   |
| 4.18.0  | 47        | 4.16%   |
| 5.10.14 | 43        | 3.81%   |
| 5.10.0  | 32        | 2.83%   |
| 5.16.7  | 28        | 2.48%   |
| 4.19.0  | 26        | 2.3%    |
| 5.15.0  | 24        | 2.12%   |
| 5.17.5  | 7         | 0.62%   |
| 5.9.1   | 5         | 0.44%   |
| 5.15.8  | 5         | 0.44%   |
| 5.14.0  | 5         | 0.44%   |
| 5.3.18  | 4         | 0.35%   |
| 5.16.0  | 4         | 0.35%   |
| 5.15.13 | 4         | 0.35%   |
| 4.9.20  | 4         | 0.35%   |
| 4.4.0   | 4         | 0.35%   |
| 5.9.14  | 3         | 0.27%   |
| 5.7.15  | 3         | 0.27%   |
| 5.18.9  | 3         | 0.27%   |
| 5.18.6  | 3         | 0.27%   |
| 5.17.4  | 3         | 0.27%   |
| 5.17.15 | 3         | 0.27%   |
| 5.17.0  | 3         | 0.27%   |
| 5.16.11 | 3         | 0.27%   |
| 5.15.4  | 3         | 0.27%   |
| 5.15.32 | 3         | 0.27%   |
| 5.15.25 | 3         | 0.27%   |
| 5.15.21 | 3         | 0.27%   |
| 5.15.16 | 3         | 0.27%   |
| 5.14.15 | 3         | 0.27%   |
| 5.13.5  | 3         | 0.27%   |
| 5.12.4  | 3         | 0.27%   |
| 5.11.12 | 3         | 0.27%   |
| 5.11.11 | 3         | 0.27%   |
| 5.10.7  | 3         | 0.27%   |
| 5.10.13 | 3         | 0.27%   |
| 4.9.60  | 3         | 0.27%   |
| 4.9.0   | 3         | 0.27%   |
| 4.13.0  | 3         | 0.27%   |
| 5.9.8   | 2         | 0.18%   |
| 5.9.16  | 2         | 0.18%   |
| 5.9.0   | 2         | 0.18%   |
| 5.8.13  | 2         | 0.18%   |
| 5.7.0   | 2         | 0.18%   |
| 5.6.6   | 2         | 0.18%   |
| 5.6.19  | 2         | 0.18%   |
| 5.6.16  | 2         | 0.18%   |
| 5.6.13  | 2         | 0.18%   |
| 5.6.11  | 2         | 0.18%   |
| 5.5.15  | 2         | 0.18%   |
| 5.4.38  | 2         | 0.18%   |
| 5.4.32  | 2         | 0.18%   |
| 5.4.28  | 2         | 0.18%   |
| 5.3.7   | 2         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 239       | 21.4%   |
| 5.10    | 100       | 8.95%   |
| 5.11    | 94        | 8.42%   |
| 5.3     | 83        | 7.43%   |
| 5.13    | 83        | 7.43%   |
| 5.8     | 78        | 6.98%   |
| 4.15    | 64        | 5.73%   |
| 5.15    | 61        | 5.46%   |
| 5.0     | 54        | 4.83%   |
| 5.16    | 49        | 4.39%   |
| 4.18    | 48        | 4.3%    |
| 4.19    | 28        | 2.51%   |
| 5.17    | 23        | 2.06%   |
| 5.9     | 16        | 1.43%   |
| 5.14    | 16        | 1.43%   |
| 5.18    | 14        | 1.25%   |
| 5.6     | 12        | 1.07%   |
| 4.9     | 12        | 1.07%   |
| 5.12    | 11        | 0.98%   |
| 5.7     | 10        | 0.9%    |
| 5.5     | 7         | 0.63%   |
| 4.4     | 4         | 0.36%   |
| 4.13    | 3         | 0.27%   |
| 5.2     | 2         | 0.18%   |
| 4.12    | 2         | 0.18%   |
| 5.1     | 1         | 0.09%   |
| 4.10    | 1         | 0.09%   |
| 3.2     | 1         | 0.09%   |
| 3.10    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 992       | 95.75%  |
| i686   | 44        | 4.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 494       | 45.83%  |
| KDE5              | 149       | 13.82%  |
| Unknown           | 133       | 12.34%  |
| XFCE              | 80        | 7.42%   |
| X-Cinnamon        | 59        | 5.47%   |
| KDE               | 50        | 4.64%   |
| MATE              | 31        | 2.88%   |
| Pantheon          | 18        | 1.67%   |
| Cinnamon          | 14        | 1.3%    |
| Budgie            | 9         | 0.83%   |
| LXQt              | 8         | 0.74%   |
| Unity             | 6         | 0.56%   |
| LXDE              | 6         | 0.56%   |
| KDE4              | 5         | 0.46%   |
| Deepin            | 4         | 0.37%   |
| i3                | 2         | 0.19%   |
| GNOME Classic     | 2         | 0.19%   |
| Enlightenment     | 2         | 0.19%   |
| Yaru:ubuntu:GNOME | 1         | 0.09%   |
| xmonad            | 1         | 0.09%   |
| trinity           | 1         | 0.09%   |
| openbox           | 1         | 0.09%   |
| lightdm-xsession  | 1         | 0.09%   |
| GNOME Flashback   | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 846       | 79.81%  |
| Wayland | 129       | 12.17%  |
| Unknown | 80        | 7.55%   |
| Tty     | 5         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 610       | 57.12%  |
| GDM     | 150       | 14.04%  |
| SDDM    | 134       | 12.55%  |
| LightDM | 74        | 6.93%   |
| GDM3    | 53        | 4.96%   |
| TDM     | 34        | 3.18%   |
| KDM     | 5         | 0.47%   |
| XDM     | 3         | 0.28%   |
| SLiM    | 3         | 0.28%   |
| MDM     | 1         | 0.09%   |
| LXDM    | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_MX      | 508       | 48.29%  |
| en_US      | 302       | 28.71%  |
| Unknown    | 129       | 12.26%  |
| es_ES      | 73        | 6.94%   |
| C          | 19        | 1.81%   |
| en_GB      | 6         | 0.57%   |
| es_US      | 3         | 0.29%   |
| en_CA      | 3         | 0.29%   |
| es_MX.UTF8 | 2         | 0.19%   |
| es_AR      | 2         | 0.19%   |
| en_MX      | 2         | 0.19%   |
| uk_UA      | 1         | 0.1%    |
| POSIX      | 1         | 0.1%    |
| it_IT      | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 540       | 51.23%  |
| EFI  | 514       | 48.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 828       | 79.16%  |
| Overlay | 95        | 9.08%   |
| Btrfs   | 57        | 5.45%   |
| Unknown | 36        | 3.44%   |
| Xfs     | 19        | 1.82%   |
| Zfs     | 4         | 0.38%   |
| Ext2    | 4         | 0.38%   |
| Ext3    | 2         | 0.19%   |
| Aufs    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 674       | 63.89%  |
| GPT     | 273       | 25.88%  |
| MBR     | 108       | 10.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 937       | 89.41%  |
| Yes       | 111       | 10.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 712       | 67.68%  |
| Yes       | 340       | 32.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 266       | 25.7%   |
| Lenovo              | 205       | 19.81%  |
| Dell                | 152       | 14.69%  |
| Acer                | 89        | 8.6%    |
| ASUSTek Computer    | 70        | 6.76%   |
| Toshiba             | 54        | 5.22%   |
| Sony                | 36        | 3.48%   |
| Apple               | 33        | 3.19%   |
| HUAWEI              | 28        | 2.71%   |
| Samsung Electronics | 16        | 1.55%   |
| MSI                 | 14        | 1.35%   |
| Gateway             | 13        | 1.26%   |
| Google              | 9         | 0.87%   |
| Alienware           | 9         | 0.87%   |
| Unknown             | 6         | 0.58%   |
| Lanix               | 4         | 0.39%   |
| Timi                | 3         | 0.29%   |
| System76            | 3         | 0.29%   |
| Panasonic           | 2         | 0.19%   |
| Insyde              | 2         | 0.19%   |
| EVOO                | 2         | 0.19%   |
| eMachines           | 2         | 0.19%   |
| Corporativo Lanix   | 2         | 0.19%   |
| Chuwi               | 2         | 0.19%   |
| TECH PAD            | 1         | 0.1%    |
| SK hynix            | 1         | 0.1%    |
| Razer               | 1         | 0.1%    |
| Notebook            | 1         | 0.1%    |
| LG Electronics      | 1         | 0.1%    |
| Hyundai Technology  | 1         | 0.1%    |
| HONOR               | 1         | 0.1%    |
| Hannspree           | 1         | 0.1%    |
| GHIA                | 1         | 0.1%    |
| Eluktronics         | 1         | 0.1%    |
| Clevo               | 1         | 0.1%    |
| BenQ                | 1         | 0.1%    |
| AMI                 | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Notebook                                | 25        | 2.42%   |
| HP Pavilion Laptop 15-cw0xxx               | 16        | 1.55%   |
| Unknown                                    | 16        | 1.55%   |
| HP Pavilion g4                             | 11        | 1.06%   |
| HP Laptop 15-da0xxx                        | 9         | 0.87%   |
| Lenovo IdeaPad 330-14AST 81D5              | 8         | 0.77%   |
| HUAWEI HVY-WXX9                            | 8         | 0.77%   |
| HP Pavilion Notebook                       | 8         | 0.77%   |
| HP EliteBook 8460p                         | 7         | 0.68%   |
| Dell Latitude E6430                        | 7         | 0.68%   |
| HP Pavilion Laptop 15-cw1xxx               | 6         | 0.58%   |
| HP Pavilion dv4                            | 6         | 0.58%   |
| HP Laptop 15-bw0xx                         | 6         | 0.58%   |
| Dell Inspiron 3421                         | 6         | 0.58%   |
| HP Pavilion dv5                            | 5         | 0.48%   |
| Apple MacBookPro9,2                        | 5         | 0.48%   |
| Acer Aspire E5-573                         | 5         | 0.48%   |
| Acer Aspire E3-112M                        | 5         | 0.48%   |
| Toshiba Satellite L855                     | 4         | 0.39%   |
| Lenovo G50-30 80G0                         | 4         | 0.39%   |
| Lenovo G40-45 80E1                         | 4         | 0.39%   |
| HP Pavilion 14                             | 4         | 0.39%   |
| HP Laptop 15-bs0xx                         | 4         | 0.39%   |
| HP Laptop 14-cm0xxx                        | 4         | 0.39%   |
| HP G42                                     | 4         | 0.39%   |
| HP 14                                      | 4         | 0.39%   |
| Dell Latitude E6410                        | 4         | 0.39%   |
| Dell Inspiron 5570                         | 4         | 0.39%   |
| Apple MacBookPro14,1                       | 4         | 0.39%   |
| Toshiba Satellite S40Dt-A                  | 3         | 0.29%   |
| Toshiba Satellite P755                     | 3         | 0.29%   |
| Toshiba Satellite C55-B                    | 3         | 0.29%   |
| Sony VPCYB35AL                             | 3         | 0.29%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 3         | 0.29%   |
| MSI GF63 Thin 10SCSR                       | 3         | 0.29%   |
| Lenovo Y50-70 20378                        | 3         | 0.29%   |
| Lenovo IdeaPad Y700-15ACZ 80NY             | 3         | 0.29%   |
| Lenovo IdeaPad Y700 Touch-15ISK 80NW       | 3         | 0.29%   |
| Lenovo IdeaPad S145-14IIL 81W6             | 3         | 0.29%   |
| Lenovo IdeaPad 330-15AST 81D6              | 3         | 0.29%   |
| Lenovo IdeaPad 330-14IGM 81D0              | 3         | 0.29%   |
| Lenovo IdeaPad 110-14IBR 80T6              | 3         | 0.29%   |
| Lenovo G475 20080                          | 3         | 0.29%   |
| HP Pavilion dv6                            | 3         | 0.29%   |
| HP Pavilion 15                             | 3         | 0.29%   |
| HP Laptop 15-db0xxx                        | 3         | 0.29%   |
| HP Laptop 14-ck0xxx                        | 3         | 0.29%   |
| HP Compaq Presario CQ40                    | 3         | 0.29%   |
| HP 245 G7 Notebook PC                      | 3         | 0.29%   |
| HP 240 G4                                  | 3         | 0.29%   |
| Dell XPS 15 9550                           | 3         | 0.29%   |
| Dell Studio 1558                           | 3         | 0.29%   |
| Dell Latitude E7240                        | 3         | 0.29%   |
| Dell Latitude E6400                        | 3         | 0.29%   |
| Dell Latitude 5480                         | 3         | 0.29%   |
| Dell Inspiron 5559                         | 3         | 0.29%   |
| Dell Inspiron 5558                         | 3         | 0.29%   |
| Dell Inspiron 3505                         | 3         | 0.29%   |
| Dell Inspiron 1545                         | 3         | 0.29%   |
| Dell G7 7588                               | 3         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 87        | 8.41%   |
| HP Pavilion        | 84        | 8.12%   |
| Lenovo IdeaPad     | 72        | 6.96%   |
| Acer Aspire        | 65        | 6.28%   |
| Dell Inspiron      | 59        | 5.7%    |
| Dell Latitude      | 56        | 5.41%   |
| Toshiba Satellite  | 50        | 4.83%   |
| HP Laptop          | 44        | 4.25%   |
| HP Notebook        | 25        | 2.42%   |
| HP ProBook         | 20        | 1.93%   |
| HP EliteBook       | 19        | 1.84%   |
| Unknown            | 16        | 1.55%   |
| ASUS VivoBook      | 14        | 1.35%   |
| HP Compaq          | 12        | 1.16%   |
| Dell XPS           | 9         | 0.87%   |
| HUAWEI HVY-WXX9    | 8         | 0.77%   |
| HP ENVY            | 8         | 0.77%   |
| HP 240             | 8         | 0.77%   |
| Dell Studio        | 8         | 0.77%   |
| Dell Vostro        | 7         | 0.68%   |
| Lenovo Legion      | 6         | 0.58%   |
| HP ZBook           | 6         | 0.58%   |
| Apple MacBookPro9  | 6         | 0.58%   |
| MSI GF63           | 5         | 0.48%   |
| HP OMEN            | 5         | 0.48%   |
| Lenovo G50-30      | 4         | 0.39%   |
| Lenovo G40-45      | 4         | 0.39%   |
| HP G42             | 4         | 0.39%   |
| HP 245             | 4         | 0.39%   |
| HP 14              | 4         | 0.39%   |
| Dell Precision     | 4         | 0.39%   |
| ASUS ZenBook       | 4         | 0.39%   |
| Apple MacBookPro14 | 4         | 0.39%   |
| Apple MacBookAir6  | 4         | 0.39%   |
| Alienware 17       | 4         | 0.39%   |
| Acer Swift         | 4         | 0.39%   |
| Acer Nitro         | 4         | 0.39%   |
| Sony VPCYB35AL     | 3         | 0.29%   |
| Samsung 300V3A     | 3         | 0.29%   |
| Samsung 300E5EV    | 3         | 0.29%   |
| Lenovo Y50-70      | 3         | 0.29%   |
| Lenovo G475        | 3         | 0.29%   |
| HP Presario        | 3         | 0.29%   |
| HP Mini            | 3         | 0.29%   |
| Dell G7            | 3         | 0.29%   |
| Dell G3            | 3         | 0.29%   |
| ASUS X555DG        | 3         | 0.29%   |
| ASUS X441NA        | 3         | 0.29%   |
| Apple MacBookPro8  | 3         | 0.29%   |
| Acer AOD257        | 3         | 0.29%   |
| Toshiba NB505      | 2         | 0.19%   |
| System76 Gazelle   | 2         | 0.19%   |
| Sony VPCYB20AL     | 2         | 0.19%   |
| Sony VPCS110FL     | 2         | 0.19%   |
| Sony VPCEA36FM     | 2         | 0.19%   |
| Lenovo Z40-70      | 2         | 0.19%   |
| Lenovo Yoga        | 2         | 0.19%   |
| Lenovo Y720-15IKB  | 2         | 0.19%   |
| Lenovo G50-45      | 2         | 0.19%   |
| Lanix A            | 2         | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 105       | 10.14%  |
| 2011    | 99        | 9.57%   |
| 2019    | 85        | 8.21%   |
| 2017    | 82        | 7.92%   |
| 2012    | 82        | 7.92%   |
| 2015    | 77        | 7.44%   |
| 2014    | 77        | 7.44%   |
| 2010    | 73        | 7.05%   |
| 2013    | 72        | 6.96%   |
| 2020    | 71        | 6.86%   |
| 2008    | 58        | 5.6%    |
| 2016    | 55        | 5.31%   |
| 2021    | 34        | 3.29%   |
| 2009    | 29        | 2.8%    |
| 2007    | 19        | 1.84%   |
| 2006    | 6         | 0.58%   |
| 2022    | 3         | 0.29%   |
| 2005    | 3         | 0.29%   |
| Unknown | 3         | 0.29%   |
| 2004    | 2         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1035      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 922       | 88.15%  |
| Enabled  | 124       | 11.85%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1025      | 99.03%  |
| Yes  | 10        | 0.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 296       | 28.35%  |
| 3.01-4.0    | 275       | 26.34%  |
| 8.01-16.0   | 193       | 18.49%  |
| 16.01-24.0  | 113       | 10.82%  |
| 1.01-2.0    | 79        | 7.57%   |
| 32.01-64.0  | 30        | 2.87%   |
| 2.01-3.0    | 26        | 2.49%   |
| 0.51-1.0    | 17        | 1.63%   |
| 24.01-32.0  | 11        | 1.05%   |
| 64.01-256.0 | 4         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 451       | 39.91%  |
| 2.01-3.0   | 315       | 27.88%  |
| 3.01-4.0   | 128       | 11.33%  |
| 4.01-8.0   | 101       | 8.94%   |
| 0.51-1.0   | 88        | 7.79%   |
| 8.01-16.0  | 30        | 2.65%   |
| 0.01-0.5   | 10        | 0.88%   |
| 16.01-24.0 | 5         | 0.44%   |
| 32.01-64.0 | 1         | 0.09%   |
| Unknown    | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 805       | 76.38%  |
| 2      | 211       | 20.02%  |
| 3      | 19        | 1.8%    |
| 0      | 15        | 1.42%   |
| 4      | 3         | 0.28%   |
| 6      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 633       | 60.87%  |
| Yes       | 407       | 39.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 873       | 84.35%  |
| No        | 162       | 15.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1021      | 98.65%  |
| No        | 14        | 1.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 765       | 72.58%  |
| No        | 289       | 27.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Mexico  | 1035      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Mexico City               | 232       | 21.36%  |
| Guadalajara               | 50        | 4.6%    |
| Monterrey                 | 33        | 3.04%   |
| Zapopan                   | 30        | 2.76%   |
| Queretaro                 | 27        | 2.49%   |
| Tijuana                   | 24        | 2.21%   |
| Puebla City               | 23        | 2.12%   |
| Toluca                    | 20        | 1.84%   |
| Cancún                   | 20        | 1.84%   |
| Mérida                   | 16        | 1.47%   |
| Ciudad Lopez Mateos       | 15        | 1.38%   |
| León                     | 14        | 1.29%   |
| Hermosillo                | 14        | 1.29%   |
| Ecatepec                  | 14        | 1.29%   |
| Naucalpan                 | 13        | 1.2%    |
| Apodaca                   | 13        | 1.2%    |
| Morelia                   | 12        | 1.1%    |
| Celaya                    | 12        | 1.1%    |
| Villahermosa              | 11        | 1.01%   |
| Veracruz                  | 11        | 1.01%   |
| Tlalnepantla              | 11        | 1.01%   |
| Mexico                    | 11        | 1.01%   |
| Ciudad Nezahualcoyotl     | 11        | 1.01%   |
| Ciudad Juárez            | 11        | 1.01%   |
| Xalapa                    | 10        | 0.92%   |
| Culiacán                 | 10        | 0.92%   |
| Mexicali                  | 9         | 0.83%   |
| Ensenada                  | 9         | 0.83%   |
| Cuernavaca                | 9         | 0.83%   |
| Azcapotzalco              | 9         | 0.83%   |
| San Luis Potosí City     | 8         | 0.74%   |
| Puerto Vallarta           | 8         | 0.74%   |
| Oaxaca City               | 8         | 0.74%   |
| Iztapalapa                | 8         | 0.74%   |
| Durango                   | 8         | 0.74%   |
| Saltillo                  | 7         | 0.64%   |
| Puebla                    | 7         | 0.64%   |
| Guadalupe                 | 7         | 0.64%   |
| Cuautitlán Izcalli       | 7         | 0.64%   |
| Chihuahua City            | 7         | 0.64%   |
| Zacatecas City            | 6         | 0.55%   |
| Playa del Carmen          | 6         | 0.55%   |
| Pachuca                   | 6         | 0.55%   |
| Torreón                  | 5         | 0.46%   |
| Tizayuca                  | 5         | 0.46%   |
| Gustavo Adolfo Madero     | 5         | 0.46%   |
| Guanajuato City           | 5         | 0.46%   |
| Colima                    | 5         | 0.46%   |
| Ciudad del Carmen         | 5         | 0.46%   |
| Acapulco de Juárez       | 5         | 0.46%   |
| Zumpango                  | 4         | 0.37%   |
| Tlaxcala City             | 4         | 0.37%   |
| Texcoco                   | 4         | 0.37%   |
| Tepic                     | 4         | 0.37%   |
| Santa Maria Chimalhuacan  | 4         | 0.37%   |
| San Nicolás de los Garza | 4         | 0.37%   |
| San José del Cabo        | 4         | 0.37%   |
| Metepec                   | 4         | 0.37%   |
| Ixtapaluca                | 4         | 0.37%   |
| Cuautla                   | 4         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 201       | 253    | 16.09%  |
| WDC                       | 184       | 223    | 14.73%  |
| Toshiba                   | 146       | 175    | 11.69%  |
| Kingston                  | 118       | 145    | 9.45%   |
| Samsung Electronics       | 89        | 105    | 7.13%   |
| A-DATA Technology         | 72        | 90     | 5.76%   |
| Unknown                   | 63        | 71     | 5.04%   |
| Hitachi                   | 60        | 64     | 4.8%    |
| HGST                      | 60        | 63     | 4.8%    |
| SanDisk                   | 47        | 59     | 3.76%   |
| SK hynix                  | 23        | 30     | 1.84%   |
| Apple                     | 21        | 27     | 1.68%   |
| Intel                     | 19        | 27     | 1.52%   |
| Crucial                   | 15        | 17     | 1.2%    |
| Fujitsu                   | 12        | 13     | 0.96%   |
| Micron Technology         | 11        | 11     | 0.88%   |
| LITEON                    | 9         | 14     | 0.72%   |
| XPG                       | 7         | 13     | 0.56%   |
| Realtek Semiconductor     | 7         | 8      | 0.56%   |
| YMTC                      | 6         | 7      | 0.48%   |
| KIOXIA                    | 6         | 8      | 0.48%   |
| PNY                       | 5         | 7      | 0.4%    |
| Phison                    | 5         | 5      | 0.4%    |
| Silicon Motion            | 4         | 4      | 0.32%   |
| JMicron Technology        | 4         | 4      | 0.32%   |
| China                     | 4         | 4      | 0.32%   |
| SABRENT                   | 3         | 3      | 0.24%   |
| Unknown                   | 3         | 3      | 0.24%   |
| Union Memory (Shenzhen)   | 2         | 2      | 0.16%   |
| Pioneer                   | 2         | 3      | 0.16%   |
| Patriot                   | 2         | 4      | 0.16%   |
| OCZ                       | 2         | 4      | 0.16%   |
| Netac                     | 2         | 2      | 0.16%   |
| LITEONIT                  | 2         | 2      | 0.16%   |
| Hewlett-Packard           | 2         | 2      | 0.16%   |
| Gigabyte Technology       | 2         | 2      | 0.16%   |
| ZTC                       | 1         | 1      | 0.08%   |
| Yeyian                    | 1         | 2      | 0.08%   |
| UMIS                      | 1         | 1      | 0.08%   |
| Transcend                 | 1         | 1      | 0.08%   |
| Team                      | 1         | 1      | 0.08%   |
| StoreJet                  | 1         | 1      | 0.08%   |
| StarTech                  | 1         | 2      | 0.08%   |
| SPCC                      | 1         | 1      | 0.08%   |
| sobetter                  | 1         | 1      | 0.08%   |
| ShanDianZhe               | 1         | 2      | 0.08%   |
| SAGE                      | 1         | 1      | 0.08%   |
| Phison Electronics        | 1         | 1      | 0.08%   |
| Micron/Crucial Technology | 1         | 1      | 0.08%   |
| Mass                      | 1         | 1      | 0.08%   |
| Lite-On                   | 1         | 1      | 0.08%   |
| Lenovo                    | 1         | 1      | 0.08%   |
| LaCie                     | 1         | 2      | 0.08%   |
| KingSpec                  | 1         | 2      | 0.08%   |
| IBM/Hitachi               | 1         | 1      | 0.08%   |
| Hikvision                 | 1         | 1      | 0.08%   |
| Dogfish                   | 1         | 1      | 0.08%   |
| CSD                       | 1         | 1      | 0.08%   |
| Blackpcs                  | 1         | 1      | 0.08%   |
| BHT                       | 1         | 1      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 44        | 3.43%   |
| Toshiba MQ04ABF100 1TB             | 32        | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 29        | 2.26%   |
| Kingston SA400S37240G 240GB SSD    | 27        | 2.11%   |
| Toshiba MQ01ABD100 1TB             | 26        | 2.03%   |
| Kingston SA400S37480G 480GB SSD    | 22        | 1.72%   |
| Seagate ST500LT012-1DG142 500GB    | 20        | 1.56%   |
| Toshiba MQ01ABF050 500GB           | 18        | 1.4%    |
| A-DATA SU650 120GB SSD             | 15        | 1.17%   |
| HGST HTS725050A7E630 500GB         | 12        | 0.94%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 11        | 0.86%   |
| Samsung NVMe SSD Drive 512GB       | 10        | 0.78%   |
| HGST HTS541010A9E680 1TB           | 10        | 0.78%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 9         | 0.7%    |
| Unknown MMC Card  64GB             | 9         | 0.7%    |
| Unknown MMC Card  32GB             | 9         | 0.7%    |
| Seagate ST500LM021-1KJ152 500GB    | 9         | 0.7%    |
| HGST HTS721010A9E630 1TB           | 9         | 0.7%    |
| HGST HTS541075A9E680 752GB         | 9         | 0.7%    |
| WDC WD10JPVX-60JC3T1 1TB           | 8         | 0.62%   |
| Kingston SA400S37120G 120GB SSD    | 8         | 0.62%   |
| HGST HTS545050A7E680 500GB         | 8         | 0.62%   |
| A-DATA SU630 240GB SSD             | 8         | 0.62%   |
| WDC WD10SPZX-08Z10 1TB             | 7         | 0.55%   |
| WDC WD10JPCX-24UE4T0 1TB           | 7         | 0.55%   |
| Seagate ST9500325AS 500GB          | 7         | 0.55%   |
| Seagate ST2000LM007-1R8174 2TB     | 7         | 0.55%   |
| Seagate Expansion 1TB              | 7         | 0.55%   |
| Kingston SUV400S37480G 480GB SSD   | 7         | 0.55%   |
| Kingston SA400S37960G 960GB SSD    | 7         | 0.55%   |
| WDC WD10SPZX-60Z10T0 1TB           | 6         | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB           | 6         | 0.47%   |
| Seagate ST500LT012-9WS142 500GB    | 6         | 0.47%   |
| SanDisk NVMe SSD Drive 256GB       | 6         | 0.47%   |
| Hitachi HTS545050B9A300 500GB      | 6         | 0.47%   |
| A-DATA SU650 240GB SSD             | 6         | 0.47%   |
| YMTC PC005 512GB                   | 5         | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 5         | 0.39%   |
| WDC WD10SPZX-24Z10 1TB             | 5         | 0.39%   |
| Unknown MMC Card  16GB             | 5         | 0.39%   |
| Seagate ST9250410AS 250GB          | 5         | 0.39%   |
| Seagate ST9250315AS 250GB          | 5         | 0.39%   |
| Seagate ST1000LM049-2GH172 1TB     | 5         | 0.39%   |
| SanDisk NVMe SSD Drive 512GB       | 5         | 0.39%   |
| Samsung NVMe SSD Drive 256GB       | 5         | 0.39%   |
| LITEON CV8-8E128-HP 128GB SSD      | 5         | 0.39%   |
| Kingston SV300S37A120G 120GB SSD   | 5         | 0.39%   |
| Hitachi HTS547550A9E384 500GB      | 5         | 0.39%   |
| A-DATA SU800 512GB SSD             | 5         | 0.39%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 4         | 0.31%   |
| WDC WD2500BEVS-60UST0 250GB        | 4         | 0.31%   |
| WDC WD10SPCX-24HWST1 1TB           | 4         | 0.31%   |
| WDC WD10JPVX-60JC3T0 1TB           | 4         | 0.31%   |
| Unknown SD/MMC/MS PRO 64GB         | 4         | 0.31%   |
| Unknown MMC Card  7GB              | 4         | 0.31%   |
| Toshiba NVMe SSD Drive 512GB       | 4         | 0.31%   |
| Toshiba MQ01ACF050 500GB           | 4         | 0.31%   |
| Toshiba MQ01ABD075 752GB           | 4         | 0.31%   |
| Toshiba MQ01ABD050 500GB           | 4         | 0.31%   |
| Toshiba HDWL110 1TB                | 4         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 200       | 250    | 30.91%  |
| WDC                 | 157       | 187    | 24.27%  |
| Toshiba             | 130       | 157    | 20.09%  |
| Hitachi             | 60        | 64     | 9.27%   |
| HGST                | 60        | 63     | 9.27%   |
| Samsung Electronics | 12        | 13     | 1.85%   |
| Fujitsu             | 12        | 13     | 1.85%   |
| Unknown             | 4         | 4      | 0.62%   |
| Apple               | 4         | 5      | 0.62%   |
| Hewlett-Packard     | 2         | 2      | 0.31%   |
| SAGE                | 1         | 1      | 0.15%   |
| SABRENT             | 1         | 1      | 0.15%   |
| LaCie               | 1         | 2      | 0.15%   |
| IBM/Hitachi         | 1         | 1      | 0.15%   |
| ASMT                | 1         | 1      | 0.15%   |
| ASMedia             | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 109       | 133    | 32.63%  |
| A-DATA Technology   | 70        | 88     | 20.96%  |
| Samsung Electronics | 30        | 32     | 8.98%   |
| SanDisk             | 23        | 27     | 6.89%   |
| Crucial             | 13        | 13     | 3.89%   |
| Apple               | 13        | 14     | 3.89%   |
| WDC                 | 12        | 18     | 3.59%   |
| LITEON              | 9         | 14     | 2.69%   |
| Micron Technology   | 6         | 6      | 1.8%    |
| Intel               | 6         | 7      | 1.8%    |
| SK hynix            | 5         | 6      | 1.5%    |
| PNY                 | 5         | 7      | 1.5%    |
| China               | 4         | 4      | 1.2%    |
| Unknown             | 2         | 2      | 0.6%    |
| Toshiba             | 2         | 2      | 0.6%    |
| Pioneer             | 2         | 3      | 0.6%    |
| Patriot             | 2         | 4      | 0.6%    |
| OCZ                 | 2         | 4      | 0.6%    |
| Netac               | 2         | 2      | 0.6%    |
| LITEONIT            | 2         | 2      | 0.6%    |
| Gigabyte Technology | 2         | 2      | 0.6%    |
| ZTC                 | 1         | 1      | 0.3%    |
| Yeyian              | 1         | 2      | 0.3%    |
| Transcend           | 1         | 1      | 0.3%    |
| Team                | 1         | 1      | 0.3%    |
| StoreJet            | 1         | 1      | 0.3%    |
| SPCC                | 1         | 1      | 0.3%    |
| ShanDianZhe         | 1         | 2      | 0.3%    |
| KingSpec            | 1         | 2      | 0.3%    |
| Hikvision           | 1         | 1      | 0.3%    |
| Dogfish             | 1         | 1      | 0.3%    |
| Blackpcs            | 1         | 1      | 0.3%    |
| BHT                 | 1         | 1      | 0.3%    |
| AS201               | 1         | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 636       | 765    | 52.52%  |
| SSD     | 313       | 406    | 25.85%  |
| NVMe    | 188       | 253    | 15.52%  |
| MMC     | 61        | 70     | 5.04%   |
| Unknown | 13        | 14     | 1.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 865       | 1136   | 74.96%  |
| NVMe | 186       | 251    | 16.12%  |
| MMC  | 61        | 70     | 5.29%   |
| SAS  | 42        | 51     | 3.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 597       | 745    | 63.04%  |
| 0.51-1.0   | 324       | 392    | 34.21%  |
| 1.01-2.0   | 23        | 30     | 2.43%   |
| 3.01-4.0   | 3         | 4      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 299       | 27.89%  |
| 251-500        | 264       | 24.63%  |
| 501-1000       | 174       | 16.23%  |
| 1-20           | 100       | 9.33%   |
| 51-100         | 86        | 8.02%   |
| 21-50          | 57        | 5.32%   |
| 1001-2000      | 55        | 5.13%   |
| More than 3000 | 15        | 1.4%    |
| Unknown        | 12        | 1.12%   |
| 2001-3000      | 10        | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 508       | 45.64%  |
| 21-50          | 208       | 18.69%  |
| 101-250        | 135       | 12.13%  |
| 51-100         | 123       | 11.05%  |
| 251-500        | 68        | 6.11%   |
| 501-1000       | 38        | 3.41%   |
| 1001-2000      | 13        | 1.17%   |
| Unknown        | 12        | 1.08%   |
| More than 3000 | 5         | 0.45%   |
| 2001-3000      | 3         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                       | 4         | 5      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB              | 4         | 4      | 4.17%   |
| Hitachi HTS545050B9A300 500GB                | 4         | 4      | 4.17%   |
| HGST HTS541075A9E680 752GB                   | 4         | 4      | 4.17%   |
| HGST HTS541010A9E680 1TB                     | 4         | 4      | 4.17%   |
| Toshiba MQ01ABF050 500GB                     | 3         | 3      | 3.13%   |
| WDC WD2500BEVS-60UST0 250GB                  | 2         | 2      | 2.08%   |
| Seagate ST9500420AS 500GB                    | 2         | 2      | 2.08%   |
| Seagate ST500LM021-1KJ152 500GB              | 2         | 2      | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 2.08%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 2         | 2      | 2.08%   |
| LITEON CV8-8E128-HP 128GB SSD                | 2         | 2      | 2.08%   |
| Hitachi HTS545016B9A300 160GB                | 2         | 2      | 2.08%   |
| HGST HTS541010A7E630 1TB                     | 2         | 2      | 2.08%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 1.04%   |
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1      | 1.04%   |
| WDC WD5000BPVT-22HXZT1 500GB                 | 1         | 2      | 1.04%   |
| WDC WD50 00BEVT-11ZAT0 500GB                 | 1         | 1      | 1.04%   |
| WDC WD3200BEVT-22A23T0 320GB                 | 1         | 1      | 1.04%   |
| WDC WD2500LPVX-22V0TT0 250GB                 | 1         | 1      | 1.04%   |
| WDC WD2500BEVT-80A23T0 250GB                 | 1         | 2      | 1.04%   |
| WDC WD10SPCX-60KHST0 1TB                     | 1         | 1      | 1.04%   |
| WDC WD10JPVX-60JC3T1 1TB                     | 1         | 1      | 1.04%   |
| WDC WD10JPVX-55JC3T3 1TB                     | 1         | 1      | 1.04%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 1      | 1.04%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 1.04%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 1.04%   |
| Toshiba MQ01ABD032 320GB                     | 1         | 1      | 1.04%   |
| Toshiba MK7559GSXP 752GB                     | 1         | 5      | 1.04%   |
| Toshiba MK2561GSY 250GB                      | 1         | 1      | 1.04%   |
| Toshiba MK2559GSXP 250GB                     | 1         | 1      | 1.04%   |
| Toshiba MK2555GSX 250GB                      | 1         | 1      | 1.04%   |
| Toshiba MK1655GSX 160GB                      | 1         | 1      | 1.04%   |
| Toshiba MK1652GSX 160GB                      | 1         | 1      | 1.04%   |
| Toshiba MK1237GSX 120GB                      | 1         | 1      | 1.04%   |
| Seagate ST9500423AS 500GB                    | 1         | 1      | 1.04%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.04%   |
| Seagate ST9250410AS 250GB                    | 1         | 1      | 1.04%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 1.04%   |
| Seagate ST500LM000-SSHD-8GB                  | 1         | 1      | 1.04%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 1.04%   |
| Seagate ST320LM001 HN-M320MBB 320GB          | 1         | 1      | 1.04%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 1.04%   |
| SanDisk SSD U100 256GB                       | 1         | 1      | 1.04%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD          | 1         | 1      | 1.04%   |
| Samsung Electronics SSD 970 EVO 500GB        | 1         | 1      | 1.04%   |
| Samsung Electronics HN-M500MBB 500GB         | 1         | 1      | 1.04%   |
| Micron Technology MTFDDAT064MAM-1J2 64GB SSD | 1         | 1      | 1.04%   |
| Kingston SUV500MS120G 120GB SSD              | 1         | 1      | 1.04%   |
| Kingston SUV400S37480G 480GB SSD             | 1         | 1      | 1.04%   |
| Kingston SHFS37A120G 120GB SSD               | 1         | 1      | 1.04%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 1      | 1.04%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD      | 1         | 1      | 1.04%   |
| Hitachi HTS725050A9A364 500GB                | 1         | 1      | 1.04%   |
| Hitachi HTS725032A9A364 320GB                | 1         | 1      | 1.04%   |
| Hitachi HTS723232L9SA60 320GB                | 1         | 1      | 1.04%   |
| Hitachi HTS723232A7A364 320GB                | 1         | 1      | 1.04%   |
| Hitachi HTS547564A9E384 640GB                | 1         | 1      | 1.04%   |
| Hitachi HTS547550A9E384 500GB                | 1         | 1      | 1.04%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 1.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 18.75%  |
| Toshiba             | 17        | 22     | 17.71%  |
| Hitachi             | 17        | 17     | 17.71%  |
| WDC                 | 13        | 15     | 13.54%  |
| HGST                | 12        | 12     | 12.5%   |
| Kingston            | 5         | 5      | 5.21%   |
| SanDisk             | 4         | 4      | 4.17%   |
| Fujitsu             | 3         | 3      | 3.13%   |
| Samsung Electronics | 2         | 2      | 2.08%   |
| LITEON              | 2         | 2      | 2.08%   |
| Micron Technology   | 1         | 1      | 1.04%   |
| Crucial             | 1         | 1      | 1.04%   |
| China               | 1         | 1      | 1.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 22.22%  |
| Toshiba             | 17        | 22     | 20.99%  |
| Hitachi             | 17        | 17     | 20.99%  |
| WDC                 | 13        | 15     | 16.05%  |
| HGST                | 12        | 12     | 14.81%  |
| Fujitsu             | 3         | 3      | 3.7%    |
| Samsung Electronics | 1         | 1      | 1.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 81        | 88     | 84.38%  |
| SSD  | 13        | 13     | 13.54%  |
| NVMe | 2         | 2      | 2.08%   |

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
| Detected | 693       | 1012   | 64.41%  |
| Works    | 289       | 393    | 26.86%  |
| Malfunc  | 94        | 103    | 8.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 714       | 63.19%  |
| AMD                              | 206       | 18.23%  |
| Samsung Electronics              | 52        | 4.6%    |
| SanDisk                          | 35        | 3.1%    |
| SK hynix                         | 18        | 1.59%   |
| Nvidia                           | 16        | 1.42%   |
| Toshiba America Info Systems     | 14        | 1.24%   |
| Realtek Semiconductor            | 10        | 0.88%   |
| Kingston Technology Company      | 9         | 0.8%    |
| KIOXIA                           | 8         | 0.71%   |
| ADATA Technology                 | 7         | 0.62%   |
| Yangtze Memory Technologies      | 6         | 0.53%   |
| Phison Electronics               | 6         | 0.53%   |
| Union Memory (Shenzhen)          | 5         | 0.44%   |
| Micron Technology                | 5         | 0.44%   |
| Marvell Technology Group         | 5         | 0.44%   |
| Silicon Motion                   | 4         | 0.35%   |
| Apple                            | 4         | 0.35%   |
| Micron/Crucial Technology        | 3         | 0.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| Lite-On Technology               | 1         | 0.09%   |
| Lenovo                           | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 162       | 13.38%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 82        | 6.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 73        | 6.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 65        | 5.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 57        | 4.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 41        | 3.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 37        | 3.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 34        | 2.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 32        | 2.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 32        | 2.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 28        | 2.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 26        | 2.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 25        | 2.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 23        | 1.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 21        | 1.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 19        | 1.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 18        | 1.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 17        | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 16        | 1.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 16        | 1.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 16        | 1.32%   |
| Samsung NVMe SSD Controller 980                                                        | 15        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 13        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 13        | 1.07%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 11        | 0.91%   |
| Realtek Realtek Non-Volatile memory controller                                         | 10        | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 10        | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 10        | 0.83%   |
| SanDisk Non-Volatile memory controller                                                 | 9         | 0.74%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 9         | 0.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 8         | 0.66%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 8         | 0.66%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 8         | 0.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 8         | 0.66%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 8         | 0.66%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 8         | 0.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 7         | 0.58%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 7         | 0.58%   |
| Nvidia MCP67 IDE Controller                                                            | 7         | 0.58%   |
| Nvidia MCP67 AHCI Controller                                                           | 7         | 0.58%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 7         | 0.58%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 7         | 0.58%   |
| Yangtze Memory Non-Volatile memory controller                                          | 6         | 0.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 6         | 0.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 6         | 0.5%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 6         | 0.5%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 5         | 0.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 5         | 0.41%   |
| Micron Non-Volatile memory controller                                                  | 5         | 0.41%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 5         | 0.41%   |
| SK hynix Non-Volatile memory controller                                                | 4         | 0.33%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 4         | 0.33%   |
| Silicon Motion Non-Volatile memory controller                                          | 4         | 0.33%   |
| Phison PS5013 E13 NVMe Controller                                                      | 4         | 0.33%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 4         | 0.33%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 4         | 0.33%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 4         | 0.33%   |
| AMD SB600 IDE                                                                          | 4         | 0.33%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 3         | 0.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 816       | 69.39%  |
| NVMe | 188       | 15.99%  |
| IDE  | 87        | 7.4%    |
| RAID | 85        | 7.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 791       | 76.43%  |
| AMD    | 244       | 23.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 19        | 1.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 1.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 14        | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 1.35%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 14        | 1.35%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 14        | 1.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 13        | 1.25%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.16%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 12        | 1.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 1.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 1.06%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 11        | 1.06%   |
| AMD Ryzen 3 2300U with Radeon Vega Mobile Gfx | 11        | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 0.97%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 10        | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.87%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 9         | 0.87%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 9         | 0.87%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 9         | 0.87%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 9         | 0.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 0.77%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 8         | 0.77%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 8         | 0.77%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 8         | 0.77%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 8         | 0.77%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 8         | 0.77%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 8         | 0.77%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 0.68%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 7         | 0.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.68%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 7         | 0.68%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 0.68%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 7         | 0.68%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 7         | 0.68%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 7         | 0.68%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 7         | 0.68%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 7         | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 0.58%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.58%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 6         | 0.58%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 0.58%   |
| AMD Turion 64 X2 Mobile Technology TL-58      | 6         | 0.58%   |
| AMD E-450 APU with Radeon HD Graphics         | 6         | 0.58%   |
| AMD A6-4400M APU with Radeon HD Graphics      | 6         | 0.58%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 5         | 0.48%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 5         | 0.48%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 5         | 0.48%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.48%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.48%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 5         | 0.48%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 5         | 0.48%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 0.48%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.48%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 5         | 0.48%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 5         | 0.48%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 5         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 213       | 20.58%  |
| Intel Core i7                  | 201       | 19.42%  |
| Intel Celeron                  | 117       | 11.3%   |
| Intel Core i3                  | 97        | 9.37%   |
| AMD Ryzen 5                    | 47        | 4.54%   |
| Intel Core 2 Duo               | 42        | 4.06%   |
| Intel Atom                     | 38        | 3.67%   |
| Other                          | 35        | 3.38%   |
| AMD A6                         | 25        | 2.42%   |
| Intel Pentium                  | 21        | 2.03%   |
| AMD A8                         | 20        | 1.93%   |
| AMD E                          | 16        | 1.55%   |
| AMD A4                         | 16        | 1.55%   |
| AMD Ryzen 3                    | 15        | 1.45%   |
| AMD Ryzen 7                    | 14        | 1.35%   |
| AMD A10                        | 14        | 1.35%   |
| Intel Pentium Dual             | 11        | 1.06%   |
| Intel Genuine                  | 8         | 0.77%   |
| AMD Turion 64 X2 Mobile        | 8         | 0.77%   |
| AMD Athlon II                  | 8         | 0.77%   |
| Intel Pentium Dual-Core        | 7         | 0.68%   |
| AMD E1                         | 5         | 0.48%   |
| Intel Core 2                   | 4         | 0.39%   |
| AMD FX                         | 4         | 0.39%   |
| AMD Athlon 64 X2               | 4         | 0.39%   |
| AMD A12                        | 4         | 0.39%   |
| AMD Sempron                    | 3         | 0.29%   |
| AMD E2                         | 3         | 0.29%   |
| AMD Athlon                     | 3         | 0.29%   |
| Intel Pentium Silver           | 2         | 0.19%   |
| Intel Celeron M                | 2         | 0.19%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.19%   |
| AMD Ryzen 5 PRO                | 2         | 0.19%   |
| AMD C-60                       | 2         | 0.19%   |
| AMD Athlon X2                  | 2         | 0.19%   |
| AMD Athlon II Neo              | 2         | 0.19%   |
| Intel Xeon                     | 1         | 0.1%    |
| Intel Pentium M                | 1         | 0.1%    |
| Intel Core m3                  | 1         | 0.1%    |
| Intel Core Duo                 | 1         | 0.1%    |
| Intel Core 2 Quad              | 1         | 0.1%    |
| Intel Celeron Dual-Core        | 1         | 0.1%    |
| AMD V140                       | 1         | 0.1%    |
| AMD Turion II Dual-Core        | 1         | 0.1%    |
| AMD Turion II                  | 1         | 0.1%    |
| AMD Turion 64 Mobile           | 1         | 0.1%    |
| AMD Turion                     | 1         | 0.1%    |
| AMD Ryzen 9                    | 1         | 0.1%    |
| AMD PRO A8                     | 1         | 0.1%    |
| AMD PRO A10                    | 1         | 0.1%    |
| AMD Phenom II                  | 1         | 0.1%    |
| AMD Mobile Sempron             | 1         | 0.1%    |
| AMD C-70                       | 1         | 0.1%    |
| AMD Athlon Neo                 | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 637       | 61.55%  |
| 4      | 271       | 26.18%  |
| 6      | 56        | 5.41%   |
| 1      | 56        | 5.41%   |
| 8      | 14        | 1.35%   |
| 3      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1035      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 653       | 63.09%  |
| 1      | 382       | 36.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1000      | 96.62%  |
| 32-bit         | 16        | 1.55%   |
| Unknown        | 14        | 1.35%   |
| 64-bit         | 5         | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 196       | 18.37%  |
| 0x206a7    | 76        | 7.12%   |
| 0x306a9    | 61        | 5.72%   |
| 0x40651    | 45        | 4.22%   |
| 0x806ec    | 31        | 2.91%   |
| 0x306d4    | 30        | 2.81%   |
| 0x806e9    | 29        | 2.72%   |
| 0x30678    | 29        | 2.72%   |
| 0x1067a    | 27        | 2.53%   |
| 0x806ea    | 24        | 2.25%   |
| 0x20655    | 24        | 2.25%   |
| 0x906ea    | 22        | 2.06%   |
| 0x06006705 | 22        | 2.06%   |
| 0x406e3    | 20        | 1.87%   |
| 0x106ca    | 20        | 1.87%   |
| 0x406c4    | 19        | 1.78%   |
| 0x406c3    | 18        | 1.69%   |
| 0x506e3    | 17        | 1.59%   |
| 0x0810100b | 17        | 1.59%   |
| 0x306c3    | 16        | 1.5%    |
| 0x08108109 | 16        | 1.5%    |
| 0x6fd      | 15        | 1.41%   |
| 0x806c1    | 14        | 1.31%   |
| 0x20652    | 14        | 1.31%   |
| 0x10676    | 14        | 1.31%   |
| 0x07030105 | 14        | 1.31%   |
| 0x506c9    | 13        | 1.22%   |
| 0x05000119 | 13        | 1.22%   |
| 0x906e9    | 12        | 1.12%   |
| 0x706a1    | 12        | 1.12%   |
| 0x08600106 | 12        | 1.12%   |
| 0x08108102 | 12        | 1.12%   |
| 0x06001119 | 12        | 1.12%   |
| 0x706e5    | 11        | 1.03%   |
| 0x010000c8 | 11        | 1.03%   |
| 0x106c2    | 9         | 0.84%   |
| 0x06006704 | 9         | 0.84%   |
| 0xa0652    | 8         | 0.75%   |
| 0x02000057 | 7         | 0.66%   |
| 0x806eb    | 6         | 0.56%   |
| 0x06006110 | 6         | 0.56%   |
| 0x06006118 | 5         | 0.47%   |
| 0x03000027 | 5         | 0.47%   |
| 0x6e8      | 4         | 0.37%   |
| 0x08608103 | 4         | 0.37%   |
| 0x0700010f | 4         | 0.37%   |
| 0x706a8    | 3         | 0.28%   |
| 0x6fb      | 3         | 0.28%   |
| 0x30673    | 3         | 0.28%   |
| 0x10661    | 3         | 0.28%   |
| 0x06003106 | 3         | 0.28%   |
| 0x0600111f | 3         | 0.28%   |
| 0x0500010d | 3         | 0.28%   |
| 0x906ed    | 2         | 0.19%   |
| 0x6f6      | 2         | 0.19%   |
| 0x6f2      | 2         | 0.19%   |
| 0x106e5    | 2         | 0.19%   |
| 0x0a50000c | 2         | 0.19%   |
| 0x08600104 | 2         | 0.19%   |
| 0x08600103 | 2         | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 153       | 14.78%  |
| SandyBridge     | 93        | 8.99%   |
| Silvermont      | 73        | 7.05%   |
| IvyBridge       | 72        | 6.96%   |
| Haswell         | 72        | 6.96%   |
| Penryn          | 48        | 4.64%   |
| Excavator       | 48        | 4.64%   |
| Skylake         | 47        | 4.54%   |
| Westmere        | 40        | 3.86%   |
| Broadwell       | 39        | 3.77%   |
| Zen+            | 30        | 2.9%    |
| Core            | 30        | 2.9%    |
| Bonnell         | 30        | 2.9%    |
| Bobcat          | 23        | 2.22%   |
| Zen 2           | 21        | 2.03%   |
| Zen             | 21        | 2.03%   |
| Puma            | 19        | 1.84%   |
| Goldmont plus   | 19        | 1.84%   |
| TigerLake       | 18        | 1.74%   |
| Piledriver      | 18        | 1.74%   |
| Goldmont        | 16        | 1.55%   |
| K8 Hammer       | 15        | 1.45%   |
| IceLake         | 15        | 1.45%   |
| K10             | 14        | 1.35%   |
| CometLake       | 14        | 1.35%   |
| K8 & K10 hybrid | 9         | 0.87%   |
| P6              | 8         | 0.77%   |
| Jaguar          | 8         | 0.77%   |
| Unknown         | 8         | 0.77%   |
| K10 Llano       | 5         | 0.48%   |
| Zen 3           | 4         | 0.39%   |
| Steamroller     | 3         | 0.29%   |
| Nehalem         | 2         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 747       | 62.56%  |
| AMD                              | 272       | 22.78%  |
| Nvidia                           | 174       | 14.57%  |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 87        | 6.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 66        | 5.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 52        | 4.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 38        | 3.04%   |
| Intel HD Graphics 5500                                                                   | 36        | 2.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 35        | 2.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 35        | 2.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 35        | 2.8%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 32        | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 31        | 2.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 29        | 2.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 28        | 2.24%   |
| Intel UHD Graphics 620                                                                   | 28        | 2.24%   |
| Intel HD Graphics 620                                                                    | 28        | 2.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 23        | 1.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 21        | 1.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 21        | 1.68%   |
| Intel HD Graphics 530                                                                    | 20        | 1.6%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 20        | 1.6%    |
| AMD Renoir                                                                               | 20        | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 20        | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 18        | 1.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 1.36%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 16        | 1.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 1.2%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 1.2%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 15        | 1.2%    |
| Intel HD Graphics 630                                                                    | 14        | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.12%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 14        | 1.12%   |
| Intel HD Graphics 500                                                                    | 13        | 1.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 1.04%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 11        | 0.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 0.88%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 10        | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 8         | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 7         | 0.56%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 7         | 0.56%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 7         | 0.56%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 7         | 0.56%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.48%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.48%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 6         | 0.48%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 6         | 0.48%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 6         | 0.48%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 6         | 0.48%   |
| AMD Lucienne                                                                             | 6         | 0.48%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.4%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.32%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.32%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 4         | 0.32%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 4         | 0.32%   |
| Intel Iris Plus Graphics 640                                                             | 4         | 0.32%   |
| AMD Cezanne                                                                              | 4         | 0.32%   |
| Nvidia TU117M                                                                            | 3         | 0.24%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.24%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 598       | 57.67%  |
| 1 x AMD        | 216       | 20.83%  |
| Intel + Nvidia | 120       | 11.57%  |
| 1 x Nvidia     | 44        | 4.24%   |
| Intel + AMD    | 26        | 2.51%   |
| 2 x AMD        | 21        | 2.03%   |
| AMD + Nvidia   | 9         | 0.87%   |
| Other          | 2         | 0.19%   |
| 1 x SiS        | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 938       | 89.85%  |
| Proprietary | 86        | 8.24%   |
| Unknown     | 20        | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 674       | 64.07%  |
| 0.01-0.5   | 156       | 14.83%  |
| 1.01-2.0   | 85        | 8.08%   |
| 0.51-1.0   | 75        | 7.13%   |
| 3.01-4.0   | 38        | 3.61%   |
| 7.01-8.0   | 10        | 0.95%   |
| 5.01-6.0   | 10        | 0.95%   |
| 2.01-3.0   | 4         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 215       | 18.47%  |
| LG Display              | 172       | 14.78%  |
| BOE                     | 172       | 14.78%  |
| Chimei Innolux          | 167       | 14.35%  |
| Samsung Electronics     | 136       | 11.68%  |
| Apple                   | 36        | 3.09%   |
| Chi Mei Optoelectronics | 34        | 2.92%   |
| Lenovo                  | 24        | 2.06%   |
| Hewlett-Packard         | 22        | 1.89%   |
| Goldstar                | 22        | 1.89%   |
| Dell                    | 17        | 1.46%   |
| LG Philips              | 16        | 1.37%   |
| Sharp                   | 13        | 1.12%   |
| BenQ                    | 13        | 1.12%   |
| Acer                    | 10        | 0.86%   |
| HannStar                | 9         | 0.77%   |
| Unknown                 | 8         | 0.69%   |
| PANDA                   | 7         | 0.6%    |
| Sony                    | 6         | 0.52%   |
| InnoLux Display         | 5         | 0.43%   |
| InfoVision              | 5         | 0.43%   |
| AOC                     | 5         | 0.43%   |
| JDI                     | 4         | 0.34%   |
| Gateway                 | 4         | 0.34%   |
| CPT                     | 4         | 0.34%   |
| Toshiba                 | 3         | 0.26%   |
| FOX                     | 3         | 0.26%   |
| ASUSTek Computer        | 3         | 0.26%   |
| ___                     | 2         | 0.17%   |
| ViewSonic               | 2         | 0.17%   |
| Unknown (AAA)           | 2         | 0.17%   |
| SLD                     | 2         | 0.17%   |
| CSO                     | 2         | 0.17%   |
| Westinghouse            | 1         | 0.09%   |
| VOR                     | 1         | 0.09%   |
| Vizio                   | 1         | 0.09%   |
| VIE                     | 1         | 0.09%   |
| VHT                     | 1         | 0.09%   |
| Seiko/Epson             | 1         | 0.09%   |
| SAC                     | 1         | 0.09%   |
| Plain Tree Systems      | 1         | 0.09%   |
| Panasonic               | 1         | 0.09%   |
| MSI                     | 1         | 0.09%   |
| LGD                     | 1         | 0.09%   |
| LG Electronics          | 1         | 0.09%   |
| Insignia                | 1         | 0.09%   |
| Hisense                 | 1         | 0.09%   |
| eMachines               | 1         | 0.09%   |
| DTV                     | 1         | 0.09%   |
| DMT                     | 1         | 0.09%   |
| AGT                     | 1         | 0.09%   |
| Unknown                 | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 15        | 1.28%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                     | 13        | 1.11%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 11        | 0.94%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 10        | 0.85%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 10        | 0.85%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 10        | 0.85%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 10        | 0.85%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 10        | 0.85%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 9         | 0.77%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 9         | 0.77%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 9         | 0.77%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 8         | 0.68%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 8         | 0.68%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 8         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 8         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 8         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 8         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 8         | 0.68%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 8         | 0.68%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 7         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch          | 7         | 0.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 7         | 0.6%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 6         | 0.51%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 6         | 0.51%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 6         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch          | 6         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 6         | 0.51%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                     | 6         | 0.51%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.51%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 6         | 0.51%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 5         | 0.43%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 5         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 5         | 0.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 5         | 0.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 5         | 0.43%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 5         | 0.43%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 4         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch     | 4         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 310x170mm 13.9-inch     | 4         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 4         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 4         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 4         | 0.34%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 4         | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.34%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                    | 4         | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 4         | 0.34%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 4         | 0.34%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 4         | 0.34%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch            | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch            | 4         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 584       | 52.47%  |
| 1920x1080 (FHD)    | 279       | 25.07%  |
| 1280x800 (WXGA)    | 63        | 5.66%   |
| 1600x900 (HD+)     | 39        | 3.5%    |
| 1024x600           | 25        | 2.25%   |
| 1440x900 (WXGA+)   | 21        | 1.89%   |
| 3840x2160 (4K)     | 18        | 1.62%   |
| 1360x768           | 8         | 0.72%   |
| 2560x1440 (QHD)    | 7         | 0.63%   |
| 1680x1050 (WSXGA+) | 7         | 0.63%   |
| 2160x1440          | 6         | 0.54%   |
| 1280x1024 (SXGA)   | 6         | 0.54%   |
| 3000x2000          | 5         | 0.45%   |
| 2880x1800          | 5         | 0.45%   |
| 2560x1600          | 5         | 0.45%   |
| 1024x768 (XGA)     | 5         | 0.45%   |
| 3440x1440          | 4         | 0.36%   |
| 2560x1080          | 4         | 0.36%   |
| 3200x1800 (QHD+)   | 3         | 0.27%   |
| Unknown            | 3         | 0.27%   |
| 2288x1287          | 2         | 0.18%   |
| 1920x1200 (WUXGA)  | 2         | 0.18%   |
| 1600x1200          | 2         | 0.18%   |
| 1280x768           | 2         | 0.18%   |
| 3840x2400          | 1         | 0.09%   |
| 3840x1080          | 1         | 0.09%   |
| 3280x1080          | 1         | 0.09%   |
| 2520x1680          | 1         | 0.09%   |
| 1920x540           | 1         | 0.09%   |
| 1400x1050          | 1         | 0.09%   |
| 1366x912           | 1         | 0.09%   |
| 1152x864           | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 424       | 36.52%  |
| 13      | 235       | 20.24%  |
| 14      | 187       | 16.11%  |
| 11      | 44        | 3.79%   |
| 17      | 33        | 2.84%   |
| 21      | 28        | 2.41%   |
| 10      | 23        | 1.98%   |
| 12      | 22        | 1.89%   |
| 23      | 19        | 1.64%   |
| 24      | 18        | 1.55%   |
| 18      | 15        | 1.29%   |
| 27      | 14        | 1.21%   |
| 20      | 13        | 1.12%   |
| Unknown | 13        | 1.12%   |
| 16      | 11        | 0.95%   |
| 31      | 10        | 0.86%   |
| 19      | 9         | 0.78%   |
| 34      | 7         | 0.6%    |
| 22      | 5         | 0.43%   |
| 84      | 4         | 0.34%   |
| 54      | 4         | 0.34%   |
| 72      | 3         | 0.26%   |
| 32      | 3         | 0.26%   |
| 142     | 2         | 0.17%   |
| 40      | 2         | 0.17%   |
| 39      | 2         | 0.17%   |
| 8       | 2         | 0.17%   |
| 74      | 1         | 0.09%   |
| 55      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 46      | 1         | 0.09%   |
| 42      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 35      | 1         | 0.09%   |
| 29      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 761       | 66.12%  |
| 201-300        | 161       | 13.99%  |
| 401-500        | 69        | 5.99%   |
| 501-600        | 50        | 4.34%   |
| 351-400        | 50        | 4.34%   |
| Unknown        | 13        | 1.13%   |
| 601-700        | 11        | 0.96%   |
| 701-800        | 10        | 0.87%   |
| 1501-2000      | 8         | 0.7%    |
| 1001-1500      | 7         | 0.61%   |
| 801-900        | 6         | 0.52%   |
| More than 2000 | 2         | 0.17%   |
| 101-200        | 2         | 0.17%   |
| 901-1000       | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 887       | 85.37%  |
| 16/10   | 104       | 10.01%  |
| 3/2     | 16        | 1.54%   |
| 4/3     | 9         | 0.87%   |
| Unknown | 9         | 0.87%   |
| 21/9    | 8         | 0.77%   |
| 5/4     | 4         | 0.38%   |
| 1.00    | 2         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 430       | 37.07%  |
| 81-90          | 374       | 32.24%  |
| 201-250        | 58        | 5%      |
| 71-80          | 48        | 4.14%   |
| 51-60          | 44        | 3.79%   |
| 151-200        | 28        | 2.41%   |
| 41-50          | 23        | 1.98%   |
| 121-130        | 23        | 1.98%   |
| 351-500        | 22        | 1.9%    |
| 61-70          | 21        | 1.81%   |
| 141-150        | 18        | 1.55%   |
| More than 1000 | 16        | 1.38%   |
| 301-350        | 15        | 1.29%   |
| Unknown        | 13        | 1.12%   |
| 131-140        | 7         | 0.6%    |
| 501-1000       | 7         | 0.6%    |
| 111-120        | 4         | 0.34%   |
| 91-100         | 4         | 0.34%   |
| 251-300        | 3         | 0.26%   |
| 1-40           | 2         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 600       | 52.72%  |
| 121-160       | 287       | 25.22%  |
| 51-100        | 161       | 14.15%  |
| 161-240       | 34        | 2.99%   |
| 1-50          | 24        | 2.11%   |
| More than 240 | 19        | 1.67%   |
| Unknown       | 13        | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 866       | 81.62%  |
| 2     | 159       | 14.99%  |
| 0     | 20        | 1.89%   |
| 3     | 16        | 1.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 591       | 36.8%   |
| Intel                                  | 394       | 24.53%  |
| Qualcomm Atheros                       | 274       | 17.06%  |
| Broadcom                               | 149       | 9.28%   |
| Broadcom Limited                       | 36        | 2.24%   |
| Ralink                                 | 34        | 2.12%   |
| Marvell Technology Group               | 26        | 1.62%   |
| TP-Link                                | 14        | 0.87%   |
| Ralink Technology                      | 13        | 0.81%   |
| Nvidia                                 | 13        | 0.81%   |
| MediaTek                               | 7         | 0.44%   |
| Huawei Technologies                    | 6         | 0.37%   |
| Qualcomm Atheros Communications        | 5         | 0.31%   |
| DisplayLink                            | 5         | 0.31%   |
| Xiaomi                                 | 4         | 0.25%   |
| Motorola PCS                           | 4         | 0.25%   |
| ASIX Electronics                       | 4         | 0.25%   |
| ICS Advent                             | 3         | 0.19%   |
| Spreadtrum Communications              | 2         | 0.12%   |
| Samsung Electronics                    | 2         | 0.12%   |
| Lenovo                                 | 2         | 0.12%   |
| JMicron Technology                     | 2         | 0.12%   |
| Dell                                   | 2         | 0.12%   |
| D-Link                                 | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.06%   |
| T & A Mobile Phones                    | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.06%   |
| Qualcomm                               | 1         | 0.06%   |
| NetGear                                | 1         | 0.06%   |
| LG Electronics                         | 1         | 0.06%   |
| Lab126                                 | 1         | 0.06%   |
| Hewlett-Packard                        | 1         | 0.06%   |
| Foxconn / Hon Hai                      | 1         | 0.06%   |
| D-Link System                          | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 299       | 14.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 211       | 10.53%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 56        | 2.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 2.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 48        | 2.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 40        | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 39        | 1.95%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 38        | 1.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 37        | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 32        | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 31        | 1.55%   |
| Intel Wi-Fi 6 AX200                                                     | 31        | 1.55%   |
| Intel Wireless 7265                                                     | 27        | 1.35%   |
| Intel Wireless 8265 / 8275                                              | 25        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 25        | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 24        | 1.2%    |
| Intel Wireless 7260                                                     | 21        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 21        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 17        | 0.85%   |
| Intel Wireless 8260                                                     | 17        | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 0.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 15        | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 14        | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 0.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 14        | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 14        | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 0.7%    |
| Intel Wi-Fi 6 AX201                                                     | 13        | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 12        | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.6%    |
| Intel Wireless 3165                                                     | 12        | 0.6%    |
| Intel Wireless 3160                                                     | 12        | 0.6%    |
| Intel Ethernet Connection I218-LM                                       | 12        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 0.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 12        | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 11        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                                | 11        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 10        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 10        | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                                   | 10        | 0.5%    |
| Intel Centrino Ultimate-N 6300                                          | 10        | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 9         | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 9         | 0.45%   |
| Intel WiFi Link 5100                                                    | 9         | 0.45%   |
| Intel Centrino Advanced-N 6200                                          | 9         | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 9         | 0.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 9         | 0.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 8         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 8         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 8         | 0.4%    |
| Intel Ethernet Connection I217-LM                                       | 8         | 0.4%    |
| Intel Ethernet Connection (4) I219-LM                                   | 8         | 0.4%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 8         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 367       | 34.36%  |
| Realtek Semiconductor                 | 241       | 22.57%  |
| Qualcomm Atheros                      | 232       | 21.72%  |
| Broadcom                              | 125       | 11.7%   |
| Ralink                                | 34        | 3.18%   |
| Broadcom Limited                      | 28        | 2.62%   |
| Ralink Technology                     | 13        | 1.22%   |
| TP-Link                               | 12        | 1.12%   |
| Qualcomm Atheros Communications       | 5         | 0.47%   |
| MediaTek                              | 4         | 0.37%   |
| D-Link                                | 2         | 0.19%   |
| Qualcomm                              | 1         | 0.09%   |
| NetGear                               | 1         | 0.09%   |
| Dell                                  | 1         | 0.09%   |
| D-Link System                         | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 56        | 5.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 4.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 48        | 4.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 40        | 3.68%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 38        | 3.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 37        | 3.41%   |
| Broadcom BCM43142 802.11b/g/n                                           | 32        | 2.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 31        | 2.85%   |
| Intel Wi-Fi 6 AX200                                                     | 31        | 2.85%   |
| Intel Wireless 7265                                                     | 27        | 2.49%   |
| Intel Wireless 8265 / 8275                                              | 25        | 2.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 25        | 2.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 24        | 2.21%   |
| Intel Wireless 7260                                                     | 21        | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 21        | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.75%   |
| Intel Wireless 8260                                                     | 17        | 1.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.38%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 15        | 1.38%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 14        | 1.29%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 1.29%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 14        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 1.29%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 1.2%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 12        | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.1%    |
| Intel Wireless 3165                                                     | 12        | 1.1%    |
| Intel Wireless 3160                                                     | 12        | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 1.1%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 12        | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 11        | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 0.92%   |
| Intel Centrino Ultimate-N 6300                                          | 10        | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 9         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 9         | 0.83%   |
| Intel WiFi Link 5100                                                    | 9         | 0.83%   |
| Intel Centrino Advanced-N 6200                                          | 9         | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 9         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 8         | 0.74%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 8         | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 8         | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.64%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 7         | 0.64%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.55%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 0.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.55%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.55%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.55%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.55%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 0.55%   |
| Broadcom BCM4311 802.11a/b/g                                            | 6         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 5         | 0.46%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.46%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 5         | 0.46%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 5         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 526       | 58.31%  |
| Intel                                  | 157       | 17.41%  |
| Qualcomm Atheros                       | 87        | 9.65%   |
| Broadcom                               | 43        | 4.77%   |
| Marvell Technology Group               | 26        | 2.88%   |
| Nvidia                                 | 13        | 1.44%   |
| Broadcom Limited                       | 8         | 0.89%   |
| Huawei Technologies                    | 5         | 0.55%   |
| DisplayLink                            | 5         | 0.55%   |
| Xiaomi                                 | 4         | 0.44%   |
| ASIX Electronics                       | 4         | 0.44%   |
| MediaTek                               | 3         | 0.33%   |
| ICS Advent                             | 3         | 0.33%   |
| TP-Link                                | 2         | 0.22%   |
| Spreadtrum Communications              | 2         | 0.22%   |
| Samsung Electronics                    | 2         | 0.22%   |
| Lenovo                                 | 2         | 0.22%   |
| JMicron Technology                     | 2         | 0.22%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.11%   |
| T & A Mobile Phones                    | 1         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.11%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.11%   |
| Motorola PCS                           | 1         | 0.11%   |
| LG Electronics                         | 1         | 0.11%   |
| Lab126                                 | 1         | 0.11%   |
| Foxconn / Hon Hai                      | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 299       | 32.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 211       | 23.26%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 39        | 4.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 17        | 1.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 14        | 1.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 12        | 1.32%   |
| Intel Ethernet Connection I218-LM                                              | 12        | 1.32%   |
| Intel 82577LM Gigabit Network Connection                                       | 11        | 1.21%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 10        | 1.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 10        | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                                          | 10        | 1.1%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 9         | 0.99%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 8         | 0.88%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 8         | 0.88%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                       | 8         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 8         | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 7         | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.77%   |
| Nvidia MCP67 Ethernet                                                          | 7         | 0.77%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 0.77%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 6         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 5         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 5         | 0.55%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.55%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                           | 5         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.55%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 5         | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.44%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 4         | 0.44%   |
| Intel Ethernet Connection I219-V                                               | 4         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                                          | 4         | 0.44%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 0.44%   |
| Huawei LYA-L09                                                                 | 4         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.33%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.33%   |
| MediaTek moto e(6) plus                                                        | 3         | 0.33%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 3         | 0.33%   |
| Intel WiMAX Connection 2400m                                                   | 3         | 0.33%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 0.33%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.33%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 3         | 0.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.33%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 0.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 3         | 0.33%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 3         | 0.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 0.22%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 0.22%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 2         | 0.22%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.22%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 2         | 0.22%   |
| Intel PRO/100 VE Network Connection                                            | 2         | 0.22%   |
| Intel Ethernet Connection I218-V                                               | 2         | 0.22%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.22%   |
| DisplayLink USB3.0 Dual Video Dock                                             | 2         | 0.22%   |
| DisplayLink Dell Universal Dock D6000                                          | 2         | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1021      | 53.65%  |
| Ethernet | 872       | 45.82%  |
| Modem    | 6         | 0.32%   |
| Unknown  | 4         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 833       | 75.59%  |
| Ethernet | 268       | 24.32%  |
| Unknown  | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 824       | 79.61%  |
| 1     | 199       | 19.23%  |
| 0     | 10        | 0.97%   |
| 3     | 2         | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 811       | 76.65%  |
| Yes  | 247       | 23.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 255       | 33.25%  |
| Realtek Semiconductor           | 157       | 20.47%  |
| Qualcomm Atheros Communications | 83        | 10.82%  |
| Broadcom                        | 64        | 8.34%   |
| Lite-On Technology              | 37        | 4.82%   |
| Foxconn / Hon Hai               | 31        | 4.04%   |
| Apple                           | 28        | 3.65%   |
| Dell                            | 21        | 2.74%   |
| IMC Networks                    | 18        | 2.35%   |
| Toshiba                         | 15        | 1.96%   |
| Ralink                          | 14        | 1.83%   |
| Hewlett-Packard                 | 14        | 1.83%   |
| Realtek                         | 8         | 1.04%   |
| Cambridge Silicon Radio         | 7         | 0.91%   |
| Ralink Technology               | 5         | 0.65%   |
| Alps Electric                   | 4         | 0.52%   |
| Foxconn International           | 3         | 0.39%   |
| Integrated System Solution      | 1         | 0.13%   |
| Chicony Electronics             | 1         | 0.13%   |
| ASUSTek Computer                | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 115       | 14.97%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 67        | 8.72%   |
| Realtek Bluetooth Radio                                                             | 65        | 8.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 50        | 6.51%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 48        | 6.25%   |
| Intel AX200 Bluetooth                                                               | 31        | 4.04%   |
| Intel AX201 Bluetooth                                                               | 30        | 3.91%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 18        | 2.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 15        | 1.95%   |
| Intel Bluetooth Device                                                              | 15        | 1.95%   |
| Ralink RT3290 Bluetooth                                                             | 14        | 1.82%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 14        | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 1.69%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 12        | 1.56%   |
| Realtek RTL8723B Bluetooth                                                          | 11        | 1.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.43%   |
| Apple Bluetooth USB Host Controller                                                 | 11        | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 10        | 1.3%    |
| Lite-On Bluetooth Device                                                            | 10        | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 1.3%    |
| Apple Bluetooth Host Controller                                                     | 10        | 1.3%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 9         | 1.17%   |
| Realtek Bluetooth Radio                                                             | 8         | 1.04%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 8         | 1.04%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 8         | 1.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 1.04%   |
| Realtek RTL8821A Bluetooth                                                          | 7         | 0.91%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 7         | 0.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 0.91%   |
| IMC Networks Bluetooth Radio                                                        | 6         | 0.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 0.65%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 5         | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 5         | 0.65%   |
| Toshiba RT Bluetooth Radio                                                          | 4         | 0.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.52%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 4         | 0.52%   |
| IMC Networks Bluetooth Device                                                       | 4         | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 0.52%   |
| Dell Wireless 355 Bluetooth                                                         | 4         | 0.52%   |
| Broadcom HP Portable Bumble Bee                                                     | 4         | 0.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 0.52%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.39%   |
| Toshiba BCM43142A0                                                                  | 3         | 0.39%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 0.39%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 0.39%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.39%   |
| Broadcom BCM20702A0                                                                 | 3         | 0.39%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.39%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 3         | 0.39%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.26%   |
| Toshiba Askey Bluetooth Module                                                      | 2         | 0.26%   |
| Realtek CSR BS8510                                                                  | 2         | 0.26%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.26%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.26%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 2         | 0.26%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.26%   |
| Broadcom HP Portable Valentine                                                      | 2         | 0.26%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.26%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.26%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 777       | 66.41%  |
| AMD                                             | 244       | 20.85%  |
| Nvidia                                          | 100       | 8.55%   |
| Texas Instruments                               | 7         | 0.6%    |
| C-Media Electronics                             | 6         | 0.51%   |
| Logitech                                        | 5         | 0.43%   |
| Tenx Technology                                 | 3         | 0.26%   |
| Realtek Semiconductor                           | 3         | 0.26%   |
| Plantronics                                     | 3         | 0.26%   |
| Lenovo                                          | 3         | 0.26%   |
| GN Netcom                                       | 3         | 0.26%   |
| Creative Technology                             | 3         | 0.26%   |
| Syntek                                          | 2         | 0.17%   |
| Samson Technologies                             | 2         | 0.17%   |
| Generalplus Technology                          | 2         | 0.17%   |
| Synaptics                                       | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.09%   |
| Sennheiser Communications                       | 1         | 0.09%   |
| Razer USA                                       | 1         | 0.09%   |
| M-Audio                                         | 1         | 0.09%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.09%   |
| Apple                                           | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 94        | 6.35%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 87        | 5.87%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 72        | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 71        | 4.79%   |
| AMD FCH Azalia Controller                                                                         | 61        | 4.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 52        | 3.51%   |
| Intel 8 Series HD Audio Controller                                                                | 52        | 3.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 49        | 3.31%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 48        | 3.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 43        | 2.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 42        | 2.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 42        | 2.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 42        | 2.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 39        | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 39        | 2.63%   |
| Intel Broadwell-U Audio Controller                                                                | 39        | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 34        | 2.3%    |
| Intel Cannon Lake PCH cAVS                                                                        | 32        | 2.16%   |
| AMD High Definition Audio Controller                                                              | 32        | 2.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 31        | 2.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 29        | 1.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 25        | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 24        | 1.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 1.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 20        | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 19        | 1.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 18        | 1.22%   |
| AMD Trinity HDMI Audio Controller                                                                 | 18        | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 17        | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 1.08%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 14        | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 0.95%   |
| AMD Wrestler HDMI Audio                                                                           | 14        | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 13        | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 12        | 0.81%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 12        | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 0.54%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 0.47%   |
| Nvidia MCP67 High Definition Audio                                                                | 7         | 0.47%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 6         | 0.41%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.41%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 0.41%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.41%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 5         | 0.34%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 5         | 0.34%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 5         | 0.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.27%   |
| Tenx Technology USB AUDIO                                                                         | 3         | 0.2%    |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.2%    |
| Nvidia MCP89 High Definition Audio                                                                | 3         | 0.2%    |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.2%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.2%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.2%    |
| Lenovo ThinkVision T24v Wide Monitor for USB-Audio                                                | 3         | 0.2%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.2%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.2%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.2%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 163       | 28.1%   |
| SK hynix            | 126       | 21.72%  |
| Kingston            | 80        | 13.79%  |
| Micron Technology   | 75        | 12.93%  |
| Unknown             | 42        | 7.24%   |
| A-DATA Technology   | 25        | 4.31%   |
| Ramaxel Technology  | 19        | 3.28%   |
| Elpida              | 9         | 1.55%   |
| Nanya Technology    | 8         | 1.38%   |
| Unknown (ABCD)      | 6         | 1.03%   |
| Crucial             | 5         | 0.86%   |
| Corsair             | 5         | 0.86%   |
| Transcend           | 2         | 0.34%   |
| Qimonda             | 2         | 0.34%   |
| PNY                 | 2         | 0.34%   |
| Patriot             | 2         | 0.34%   |
| Timetec             | 1         | 0.17%   |
| Team                | 1         | 0.17%   |
| SHARETRONIC         | 1         | 0.17%   |
| Goldkey             | 1         | 0.17%   |
| ChangXin Memory     | 1         | 0.17%   |
| Avant               | 1         | 0.17%   |
| 3235CB0010E4        | 1         | 0.17%   |
| 0161000080AD        | 1         | 0.17%   |
| Unknown             | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 21        | 3.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 2.06%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 9         | 1.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.27%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 1.27%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 1.27%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 1.11%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 7         | 1.11%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 6         | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.95%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.95%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.95%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.95%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 6         | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.79%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 5         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 4         | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.63%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 4         | 0.63%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.63%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 4         | 0.63%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.63%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 0.63%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.63%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.63%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 4         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.48%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.48%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 3         | 0.48%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.48%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s        | 3         | 0.48%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 3         | 0.48%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.48%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.48%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s   | 3         | 0.48%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 3         | 0.48%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.48%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 3         | 0.48%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s        | 3         | 0.48%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 3         | 0.48%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 3         | 0.48%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 3         | 0.48%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 3         | 0.48%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.48%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 3         | 0.48%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 3         | 0.48%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s          | 3         | 0.48%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 3         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 218       | 46.28%  |
| DDR4    | 180       | 38.22%  |
| DDR2    | 26        | 5.52%   |
| LPDDR3  | 17        | 3.61%   |
| LPDDR4  | 14        | 2.97%   |
| SDRAM   | 7         | 1.49%   |
| Unknown | 5         | 1.06%   |
| DDR     | 3         | 0.64%   |
| RAM     | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 430       | 90.53%  |
| Row Of Chips | 40        | 8.42%   |
| Chip         | 4         | 0.84%   |
| Unknown      | 1         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 223       | 39.75%  |
| 8192  | 195       | 34.76%  |
| 2048  | 87        | 15.51%  |
| 16384 | 27        | 4.81%   |
| 1024  | 22        | 3.92%   |
| 32768 | 4         | 0.71%   |
| 512   | 2         | 0.36%   |
| 256   | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 166       | 31.44%  |
| 2667    | 99        | 18.75%  |
| 3200    | 38        | 7.2%    |
| 2400    | 34        | 6.44%   |
| 2133    | 33        | 6.25%   |
| 1334    | 33        | 6.25%   |
| 1333    | 28        | 5.3%    |
| 3266    | 21        | 3.98%   |
| 667     | 15        | 2.84%   |
| Unknown | 15        | 2.84%   |
| 800     | 8         | 1.52%   |
| 4267    | 6         | 1.14%   |
| 1067    | 5         | 0.95%   |
| 1066    | 5         | 0.95%   |
| 2048    | 4         | 0.76%   |
| 1867    | 4         | 0.76%   |
| 4199    | 3         | 0.57%   |
| 975     | 3         | 0.57%   |
| 533     | 3         | 0.57%   |
| 8400    | 2         | 0.38%   |
| 3733    | 1         | 0.19%   |
| 2933    | 1         | 0.19%   |
| 400     | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Seiko Epson            | 3         | 37.5%   |
| Brother Industries     | 2         | 25%     |
| TSC Auto ID Technology | 1         | 12.5%   |
| Samsung Electronics    | 1         | 12.5%   |
| BIXOLON                | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| TSC Auto ID Printer     | 1         | 12.5%   |
| Seiko Epson L555 Series | 1         | 12.5%   |
| Seiko Epson L210 Series | 1         | 12.5%   |
| Seiko Epson L120 Series | 1         | 12.5%   |
| Samsung ML-1660 Series  | 1         | 12.5%   |
| Brother MFC-J470DW      | 1         | 12.5%   |
| Brother DCP-1510        | 1         | 12.5%   |
| BIXOLON SRP-350plusIII  | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| HP ScanJet 5590 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 241       | 25.37%  |
| Microdia                               | 89        | 9.37%   |
| IMC Networks                           | 89        | 9.37%   |
| Realtek Semiconductor                  | 73        | 7.68%   |
| Cheng Uei Precision Industry (Foxlink) | 57        | 6%      |
| Acer                                   | 55        | 5.79%   |
| Suyin                                  | 54        | 5.68%   |
| Sunplus Innovation Technology          | 49        | 5.16%   |
| Quanta                                 | 35        | 3.68%   |
| Syntek                                 | 33        | 3.47%   |
| Lite-On Technology                     | 27        | 2.84%   |
| Apple                                  | 22        | 2.32%   |
| Ricoh                                  | 19        | 2%      |
| Silicon Motion                         | 15        | 1.58%   |
| Importek                               | 14        | 1.47%   |
| Alcor Micro                            | 11        | 1.16%   |
| Logitech                               | 9         | 0.95%   |
| ALi                                    | 7         | 0.74%   |
| OmniVision Technologies                | 5         | 0.53%   |
| Primax Electronics                     | 4         | 0.42%   |
| Genesys Logic                          | 4         | 0.42%   |
| MacroSilicon                           | 3         | 0.32%   |
| Lenovo                                 | 3         | 0.32%   |
| Generalplus Technology                 | 3         | 0.32%   |
| Y Media                                | 2         | 0.21%   |
| Tobii Technology AB                    | 2         | 0.21%   |
| Samsung Electronics                    | 2         | 0.21%   |
| Microsoft                              | 2         | 0.21%   |
| Jieli Technology                       | 2         | 0.21%   |
| DigiTech                               | 2         | 0.21%   |
| Z-Star Microelectronics                | 1         | 0.11%   |
| YGTek                                  | 1         | 0.11%   |
| Sunplus Technology                     | 1         | 0.11%   |
| Sonix Technology                       | 1         | 0.11%   |
| Novatek Microelectronics               | 1         | 0.11%   |
| Nebraska Furniture Mart                | 1         | 0.11%   |
| Luxvisions Innotech Limited            | 1         | 0.11%   |
| LG Electronics                         | 1         | 0.11%   |
| kingcome                               | 1         | 0.11%   |
| JMicron Technology                     | 1         | 0.11%   |
| Goodong Industry                       | 1         | 0.11%   |
| GEMBIRD                                | 1         | 0.11%   |
| Foxconn / Hon Hai                      | 1         | 0.11%   |
| Fitipower Integrated Technology        | 1         | 0.11%   |
| Creative Technology                    | 1         | 0.11%   |
| Blackmagic Design                      | 1         | 0.11%   |
| ARC International                      | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 37        | 3.87%   |
| Microdia Integrated_Webcam_HD                                              | 28        | 2.93%   |
| Chicony HD WebCam                                                          | 24        | 2.51%   |
| Chicony HP Webcam                                                          | 19        | 1.99%   |
| Acer Integrated Camera                                                     | 19        | 1.99%   |
| Realtek Integrated_Webcam_HD                                               | 18        | 1.88%   |
| IMC Networks Integrated Camera                                             | 18        | 1.88%   |
| Sunplus Integrated_Webcam_HD                                               | 14        | 1.46%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 14        | 1.46%   |
| IMC Networks HD Camera                                                     | 13        | 1.36%   |
| Chicony HP TrueVision HD                                                   | 13        | 1.36%   |
| Syntek Lenovo EasyCamera                                                   | 11        | 1.15%   |
| Quanta HP Webcam                                                           | 11        | 1.15%   |
| IMC Networks EasyCamera                                                    | 11        | 1.15%   |
| Chicony HP TrueVision HD Camera                                            | 11        | 1.15%   |
| Sunplus HD WebCam                                                          | 10        | 1.05%   |
| Chicony HP Wide Vision HD Camera                                           | 10        | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 10        | 1.05%   |
| Chicony USB 2.0 Camera                                                     | 9         | 0.94%   |
| Apple FaceTime HD Camera                                                   | 9         | 0.94%   |
| Acer EasyCamera                                                            | 9         | 0.94%   |
| Syntek Integrated Camera                                                   | 8         | 0.84%   |
| Suyin HP Truevision HD                                                     | 8         | 0.84%   |
| Microdia Integrated Webcam                                                 | 8         | 0.84%   |
| Lite-On HP Wide Vision HD Camera                                           | 8         | 0.84%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 8         | 0.84%   |
| Chicony HP HD Camera                                                       | 8         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 8         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 8         | 0.84%   |
| Realtek HP Truevision HD                                                   | 7         | 0.73%   |
| Microdia Sonix USB 2.0 Camera                                              | 7         | 0.73%   |
| Microdia Lenovo EasyCamera                                                 | 7         | 0.73%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 7         | 0.73%   |
| Chicony Lenovo EasyCamera                                                  | 7         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 7         | 0.73%   |
| Acer Lenovo EasyCamera                                                     | 7         | 0.73%   |
| Syntek EasyCamera                                                          | 6         | 0.63%   |
| Sunplus Laptop Integrated Webcam HD                                        | 6         | 0.63%   |
| Ricoh Integrated Webcam                                                    | 6         | 0.63%   |
| Realtek HD WebCam                                                          | 6         | 0.63%   |
| Quanta HP TrueVision HD Camera                                             | 6         | 0.63%   |
| Importek TOSHIBA Web Camera - HD                                           | 6         | 0.63%   |
| Chicony VGA 24fps UVC Webcam                                               | 6         | 0.63%   |
| Chicony Integrated HP HD Webcam                                            | 6         | 0.63%   |
| Chicony HP HD Webcam                                                       | 6         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 6         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 6         | 0.63%   |
| ALi Gateway Webcam                                                         | 6         | 0.63%   |
| Realtek USB Camera                                                         | 5         | 0.52%   |
| Realtek Lenovo EasyCamera                                                  | 5         | 0.52%   |
| Microdia Dell Integrated HD Webcam                                         | 5         | 0.52%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 5         | 0.52%   |
| Chicony TOSHIBA Web Camera - HD                                            | 5         | 0.52%   |
| Chicony Sony Visual Communication Camera                                   | 5         | 0.52%   |
| Chicony Integrated Camera (1280x720@30)                                    | 5         | 0.52%   |
| Chicony HD User Facing                                                     | 5         | 0.52%   |
| Suyin WebCam                                                               | 4         | 0.42%   |
| Suyin USB 2.0 Camera                                                       | 4         | 0.42%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 4         | 0.42%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 4         | 0.42%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 68        | 41.72%  |
| Shenzhen Goodix Technology | 27        | 16.56%  |
| Synaptics                  | 25        | 15.34%  |
| Upek                       | 14        | 8.59%   |
| AuthenTec                  | 14        | 8.59%   |
| STMicroelectronics         | 5         | 3.07%   |
| Elan Microelectronics      | 5         | 3.07%   |
| LighTuning Technology      | 3         | 1.84%   |
| Suprema                    | 1         | 0.61%   |
| Samsung Electronics        | 1         | 0.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 22        | 13.5%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 9.82%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 7.36%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 7.36%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 5.52%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 4.91%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 4.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 4.91%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 4.29%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 3.07%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 3.07%   |
| AuthenTec AES2810                                                          | 5         | 3.07%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 2.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.45%   |
| Validity Sensors VFS491                                                    | 3         | 1.84%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.84%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.84%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.23%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.23%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 1.23%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.23%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.23%   |
| Unknown                                                                    | 2         | 1.23%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.61%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.61%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.61%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.61%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader                           | 1         | 0.61%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.61%   |
| Samsung Fingerprint Device                                                 | 1         | 0.61%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.61%   |
| AuthenTec AES1600                                                          | 1         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 27        | 54%     |
| Alcor Micro           | 10        | 20%     |
| Upek                  | 7         | 14%     |
| Lenovo                | 5         | 10%     |
| Gemalto (was Gemplus) | 1         | 2%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 24%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 20%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 14%     |
| Lenovo Integrated Smart Card Reader                                          | 5         | 10%     |
| Broadcom 58200                                                               | 3         | 6%      |
| Broadcom 5880                                                                | 2         | 4%      |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 688       | 65.09%  |
| 1     | 307       | 29.04%  |
| 2     | 54        | 5.11%   |
| 3     | 6         | 0.57%   |
| 7     | 1         | 0.09%   |
| 6     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 161       | 36.93%  |
| Net/wireless             | 72        | 16.51%  |
| Graphics card            | 59        | 13.53%  |
| Chipcard                 | 50        | 11.47%  |
| Multimedia controller    | 24        | 5.5%    |
| Bluetooth                | 19        | 4.36%   |
| Camera                   | 11        | 2.52%   |
| Storage                  | 8         | 1.83%   |
| Communication controller | 8         | 1.83%   |
| Net/ethernet             | 7         | 1.61%   |
| Sound                    | 5         | 1.15%   |
| Card reader              | 5         | 1.15%   |
| Modem                    | 4         | 0.92%   |
| Storage/ide              | 1         | 0.23%   |
| Network                  | 1         | 0.23%   |
| Dvb card                 | 1         | 0.23%   |

