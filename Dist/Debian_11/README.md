Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linux-bsd)
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

* [ Printers & scanners ](#printers-scanners)
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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Modern 15 A11M              | Notebook    | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | Notebook    | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Compulab      | fitlet2                     | Mini pc     | [9d1571afa4](https://linux-hardware.org/?probe=9d1571afa4) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | Desktop     | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | Notebook    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Protectli     | FW6                         | Desktop     | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Lenovo        | Yoga 710-11ISK 80TX         | Convertible | [c34bcc095c](https://linux-hardware.org/?probe=c34bcc095c) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | Desktop     | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [0c49a20e7c](https://linux-hardware.org/?probe=0c49a20e7c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | Desktop     | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | Notebook    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | Notebook    | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| Supermicro    | X11DDW-L                    | Server      | [6fab4e3135](https://linux-hardware.org/?probe=6fab4e3135) | Jul 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| Dell          | 0H5J4J A01                  | Server      | [fbdf83f7ff](https://linux-hardware.org/?probe=fbdf83f7ff) | Jul 17, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | Notebook    | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | Notebook    | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Dell          | Latitude E6330              | Notebook    | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | Notebook    | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| MSI           | MS-6712                     | Desktop     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| HP            | Compaq 6830s                | Notebook    | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [457f309f39](https://linux-hardware.org/?probe=457f309f39) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [945a4600c4](https://linux-hardware.org/?probe=945a4600c4) | Jul 02, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| MSI           | B85M-G43                    | Desktop     | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2) (... | Phone       | [6805b89f3d](https://linux-hardware.org/?probe=6805b89f3d) | Jun 25, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | Desktop     | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| Dell          | 04WYPY A04                  | Server      | [20fa770830](https://linux-hardware.org/?probe=20fa770830) | Jun 22, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Dell          | Precision 3560              | Notebook    | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | Notebook    | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | Desktop     | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Unknown       | Helios64                    | Soc         | [33c6248333](https://linux-hardware.org/?probe=33c6248333) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| Dell          | Latitude E7470              | Notebook    | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | Notebook    | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | Notebook    | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | Notebook    | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f77e2ebb10](https://linux-hardware.org/?probe=f77e2ebb10) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [eb3d04e089](https://linux-hardware.org/?probe=eb3d04e089) | May 29, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [92aa2017b9](https://linux-hardware.org/?probe=92aa2017b9) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | CX700                       | Notebook    | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [7ca350189c](https://linux-hardware.org/?probe=7ca350189c) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | Notebook    | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | Notebook    | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Dell          | Latitude 7410               | Convertible | [bc7c58f248](https://linux-hardware.org/?probe=bc7c58f248) | May 21, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [1c271464f4](https://linux-hardware.org/?probe=1c271464f4) | May 21, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7410               | Convertible | [cbd8832f44](https://linux-hardware.org/?probe=cbd8832f44) | May 19, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| sunxi         | Unknown                     | Soc         | [d54c3a2a33](https://linux-hardware.org/?probe=d54c3a2a33) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| HP            | Compaq Presario C700        | Notebook    | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| Biostar       | B450MH                      | Desktop     | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [446238dd0c](https://linux-hardware.org/?probe=446238dd0c) | Apr 25, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [bb76391a12](https://linux-hardware.org/?probe=bb76391a12) | Apr 25, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [c0536c5433](https://linux-hardware.org/?probe=c0536c5433) | Apr 13, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [935ccffcd5](https://linux-hardware.org/?probe=935ccffcd5) | Feb 01, 2021 |
| Unknown       | Shenzhen Amediatech Tech... | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| sunxi         | Unknown                     | Soc         | [604dd9d393](https://linux-hardware.org/?probe=604dd9d393) | Feb 25, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.0-7-amd64                 | 72        | 38.3%   |
| 5.10.0-8-amd64                 | 43        | 22.87%  |
| 5.10.0-6-amd64                 | 35        | 18.62%  |
| 5.11.22-2-pve                  | 2         | 1.06%   |
| 5.11.22-1-pve                  | 2         | 1.06%   |
| 5.10-sunxi64                   | 2         | 1.06%   |
| 5.9.0-arm-64                   | 1         | 0.53%   |
| 5.8.0-3-amd64                  | 1         | 0.53%   |
| 5.4.18-sunxi64                 | 1         | 0.53%   |
| 5.4.0-73-generic               | 1         | 0.53%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1         | 0.53%   |
| 5.12.4                         | 1         | 0.53%   |
| 5.12.10                        | 1         | 0.53%   |
| 5.12.1                         | 1         | 0.53%   |
| 5.12.0-9.2-liquorix-amd64      | 1         | 0.53%   |
| 5.12.0-14.2-liquorix-amd64     | 1         | 0.53%   |
| 5.11.9+                        | 1         | 0.53%   |
| 5.11.15-terranz                | 1         | 0.53%   |
| 5.11.15-051115-generic         | 1         | 0.53%   |
| 5.11.14                        | 1         | 0.53%   |
| 5.11.0-rc6                     | 1         | 0.53%   |
| 5.11.0-21.1-liquorix-amd64     | 1         | 0.53%   |
| 5.11.0-16.1-liquorix-amd64     | 1         | 0.53%   |
| 5.10.40-ismynik                | 1         | 0.53%   |
| 5.10.35-rockchip64             | 1         | 0.53%   |
| 5.10.21-sunxi                  | 1         | 0.53%   |
| 5.10.12-sunxi                  | 1         | 0.53%   |
| 5.10.0-io7-amd64               | 1         | 0.53%   |
| 5.10.0-7-686-pae               | 1         | 0.53%   |
| 5.10.0-6-rt-amd64              | 1         | 0.53%   |
| 5.10.0-6-686                   | 1         | 0.53%   |
| 5.10.0-5-amd64                 | 1         | 0.53%   |
| 5.10.0-3-amd64                 | 1         | 0.53%   |
| 5.10.0-2-amd64                 | 1         | 0.53%   |
| 4.19.181-z580322               | 1         | 0.53%   |
| 4.19.0-16-amd64                | 1         | 0.53%   |
| 4.19.0-16-686-pae              | 1         | 0.53%   |
| 4.19.0-14-amd64                | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 153       | 83.61%  |
| 5.11.22  | 4         | 2.19%   |
| 5.11.0   | 3         | 1.64%   |
| 4.19.0   | 3         | 1.64%   |
| 5.11.15  | 2         | 1.09%   |
| 5.10     | 2         | 1.09%   |
| 5.9.0    | 1         | 0.55%   |
| 5.8.0    | 1         | 0.55%   |
| 5.4.18   | 1         | 0.55%   |
| 5.4.0    | 1         | 0.55%   |
| 5.13.0   | 1         | 0.55%   |
| 5.12.4   | 1         | 0.55%   |
| 5.12.10  | 1         | 0.55%   |
| 5.12.1   | 1         | 0.55%   |
| 5.12.0   | 1         | 0.55%   |
| 5.11.9   | 1         | 0.55%   |
| 5.11.14  | 1         | 0.55%   |
| 5.10.40  | 1         | 0.55%   |
| 5.10.35  | 1         | 0.55%   |
| 5.10.21  | 1         | 0.55%   |
| 5.10.12  | 1         | 0.55%   |
| 4.19.181 | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 156       | 85.71%  |
| 5.11    | 11        | 6.04%   |
| 5.12    | 4         | 2.2%    |
| 4.19    | 4         | 2.2%    |
| 5.4     | 2         | 1.1%    |
| 5       | 2         | 1.1%    |
| 5.9     | 1         | 0.55%   |
| 5.8     | 1         | 0.55%   |
| 5.13    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 173       | 95.05%  |
| aarch64 | 5         | 2.75%   |
| i686    | 3         | 1.65%   |
| armv7l  | 1         | 0.55%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 46        | 25.27%  |
| KDE5             | 40        | 21.98%  |
| XFCE             | 19        | 10.44%  |
| MATE             | 17        | 9.34%   |
| Unknown          | 15        | 8.24%   |
| KDE              | 9         | 4.95%   |
| i3               | 7         | 3.85%   |
| Cinnamon         | 6         | 3.3%    |
| LXQt             | 5         | 2.75%   |
| X-Cinnamon       | 4         | 2.2%    |
| GNOME Flashback  | 3         | 1.65%   |
| sway             | 2         | 1.1%    |
| openbox          | 2         | 1.1%    |
| lightdm-xsession | 2         | 1.1%    |
| LXDE             | 1         | 0.55%   |
| GNUstep          | 1         | 0.55%   |
| default          | 1         | 0.55%   |
| Budgie           | 1         | 0.55%   |
| awesome          | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 126       | 68.48%  |
| Wayland | 37        | 20.11%  |
| Tty     | 15        | 8.15%   |
| Unknown | 6         | 3.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 52        | 28.57%  |
| GDM     | 42        | 23.08%  |
| Unknown | 40        | 21.98%  |
| SDDM    | 39        | 21.43%  |
| LightDM | 6         | 3.3%    |
| XDM     | 2         | 1.1%    |
| SLiM    | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 68        | 37.16%  |
| fr_FR   | 16        | 8.74%   |
| de_DE   | 13        | 7.1%    |
| ru_RU   | 8         | 4.37%   |
| pt_BR   | 8         | 4.37%   |
| es_ES   | 7         | 3.83%   |
| pl_PL   | 6         | 3.28%   |
| en_GB   | 6         | 3.28%   |
| C       | 5         | 2.73%   |
| Unknown | 5         | 2.73%   |
| en_IN   | 4         | 2.19%   |
| en_CA   | 4         | 2.19%   |
| tr_TR   | 3         | 1.64%   |
| it_IT   | 3         | 1.64%   |
| en_AU   | 3         | 1.64%   |
| de_CH   | 3         | 1.64%   |
| ru_UA   | 2         | 1.09%   |
| ro_RO   | 2         | 1.09%   |
| pt_PT   | 2         | 1.09%   |
| nl_BE   | 2         | 1.09%   |
| ja_JP   | 2         | 1.09%   |
| hu_HU   | 2         | 1.09%   |
| sr_RS   | 1         | 0.55%   |
| hr_HR   | 1         | 0.55%   |
| fi_FI   | 1         | 0.55%   |
| es_CO   | 1         | 0.55%   |
| es_AR   | 1         | 0.55%   |
| en_PH   | 1         | 0.55%   |
| en_HK   | 1         | 0.55%   |
| cs_CZ   | 1         | 0.55%   |
| ca_ES   | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 114       | 62.64%  |
| BIOS | 68        | 37.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 156       | 85.71%  |
| Btrfs   | 9         | 4.95%   |
| Zfs     | 6         | 3.3%    |
| Overlay | 5         | 2.75%   |
| Ext3    | 3         | 1.65%   |
| Unknown | 2         | 1.1%    |
| Xfs     | 1         | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 122       | 67.03%  |
| MBR     | 31        | 17.03%  |
| Unknown | 29        | 15.93%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 148       | 81.32%  |
| Yes       | 34        | 18.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 133       | 73.08%  |
| Yes       | 49        | 26.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 34        | 18.68%  |
| ASUSTek Computer    | 26        | 14.29%  |
| Dell                | 25        | 13.74%  |
| Hewlett-Packard     | 22        | 12.09%  |
| Gigabyte Technology | 19        | 10.44%  |
| MSI                 | 13        | 7.14%   |
| Acer                | 9         | 4.95%   |
| ASRock              | 7         | 3.85%   |
| sunxi               | 3         | 1.65%   |
| Intel               | 3         | 1.65%   |
| Huanan              | 2         | 1.1%    |
| Apple               | 2         | 1.1%    |
| Unknown             | 2         | 1.1%    |
| UNOWHY              | 1         | 0.55%   |
| Toshiba             | 1         | 0.55%   |
| Supermicro          | 1         | 0.55%   |
| Samsung Electronics | 1         | 0.55%   |
| Protectli           | 1         | 0.55%   |
| Pine Microsystems   | 1         | 0.55%   |
| Pegatron            | 1         | 0.55%   |
| Monster             | 1         | 0.55%   |
| Itautec             | 1         | 0.55%   |
| HUAWEI              | 1         | 0.55%   |
| HARDKERNEL          | 1         | 0.55%   |
| Fujitsu             | 1         | 0.55%   |
| Compulab            | 1         | 0.55%   |
| Chuwi               | 1         | 0.55%   |
| Biostar             | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                          | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Unknown                                       | 4         | 2.2%    |
| ASUS All Series                               | 3         | 1.65%   |
| Gigabyte Z77-D3H                              | 2         | 1.1%    |
| Gigabyte Z370 AORUS Gaming 5                  | 2         | 1.1%    |
| Dell XPS 13 9310                              | 2         | 1.1%    |
| Dell Inspiron 3793                            | 2         | 1.1%    |
| ASRock B450M Pro4                             | 2         | 1.1%    |
| UNOWHY Y13G002S4EI                            | 1         | 0.55%   |
| Toshiba Satellite U800W                       | 1         | 0.55%   |
| Supermicro SYS-6019P-WT                       | 1         | 0.55%   |
| sunxi Banana Pi BPI-M2-Ultra                  | 1         | 0.55%   |
| Samsung 370E4K                                | 1         | 0.55%   |
| Protectli FW6                                 | 1         | 0.55%   |
| Pine Microsystems Pine64 PinePhone (1.2) (DT) | 1         | 0.55%   |
| Pegatron A15                                  | 1         | 0.55%   |
| MSI U90/U100                                  | 1         | 0.55%   |
| MSI MS-7C56                                   | 1         | 0.55%   |
| MSI MS-7B89                                   | 1         | 0.55%   |
| MSI MS-7A70                                   | 1         | 0.55%   |
| MSI MS-7A40                                   | 1         | 0.55%   |
| MSI MS-7995                                   | 1         | 0.55%   |
| MSI MS-7823                                   | 1         | 0.55%   |
| MSI MS-7759                                   | 1         | 0.55%   |
| MSI MS-7721                                   | 1         | 0.55%   |
| MSI MS-6712                                   | 1         | 0.55%   |
| MSI Modern 15 A11M                            | 1         | 0.55%   |
| MSI GF65 Thin 10UE                            | 1         | 0.55%   |
| MSI CX700                                     | 1         | 0.55%   |
| Monster ABRA A5 V15.2                         | 1         | 0.55%   |
| Lenovo Yoga 710-11ISK 80TX                    | 1         | 0.55%   |
| Lenovo Yoga 300-11IBR 80M1                    | 1         | 0.55%   |
| Lenovo ThinkPad Yoga 260 20FEA02WJP           | 1         | 0.55%   |
| Lenovo ThinkPad X270 W10DG 20K5S41E00         | 1         | 0.55%   |
| Lenovo ThinkPad X260 20F5S46R00               | 1         | 0.55%   |
| Lenovo ThinkPad X260 20F5S0JF00               | 1         | 0.55%   |
| Lenovo ThinkPad X230 2325AZ8                  | 1         | 0.55%   |
| Lenovo ThinkPad X1 Tablet 20GGS02600          | 1         | 0.55%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS   | 1         | 0.55%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JRT      | 1         | 0.55%   |
| Lenovo ThinkPad T530 24296HG                  | 1         | 0.55%   |
| Lenovo ThinkPad T495 20NKS0PG00               | 1         | 0.55%   |
| Lenovo ThinkPad T495 20NJCTO1WW               | 1         | 0.55%   |
| Lenovo ThinkPad T440p 20AWS4PN00              | 1         | 0.55%   |
| Lenovo ThinkPad T430s 2356A89                 | 1         | 0.55%   |
| Lenovo ThinkPad T430s 23533KJ                 | 1         | 0.55%   |
| Lenovo ThinkPad T430 2349V4B                  | 1         | 0.55%   |
| Lenovo ThinkPad T430 2347FF9                  | 1         | 0.55%   |
| Lenovo ThinkPad T420 4236WC3                  | 1         | 0.55%   |
| Lenovo ThinkPad T14 Gen 2i 20W0CTO1WW         | 1         | 0.55%   |
| Lenovo ThinkPad T14 Gen 1 20UDCTO1WW          | 1         | 0.55%   |
| Lenovo ThinkPad Edge E540 20C600KCJP          | 1         | 0.55%   |
| Lenovo ThinkPad E595 20NF0005IX               | 1         | 0.55%   |
| Lenovo ThinkPad E15 Gen 2 20TD003MRT          | 1         | 0.55%   |
| Lenovo ThinkPad E14 20RB000UBR                | 1         | 0.55%   |
| Lenovo ThinkCentre M92p 3209EK4               | 1         | 0.55%   |
| Lenovo IdeaPad Z580                           | 1         | 0.55%   |
| Lenovo IdeaPad Z500 20202                     | 1         | 0.55%   |
| Lenovo IdeaPad S145-15IWL 81S9                | 1         | 0.55%   |
| Lenovo IdeaPad S145-14AST 81ST                | 1         | 0.55%   |
| Lenovo IdeaPad 700-15ISK 80RU                 | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 23        | 12.64%  |
| Acer Aspire              | 8         | 4.4%    |
| Lenovo IdeaPad           | 7         | 3.85%   |
| HP EliteBook             | 6         | 3.3%    |
| Dell Inspiron            | 6         | 3.3%    |
| Dell XPS                 | 5         | 2.75%   |
| ASUS ROG                 | 5         | 2.75%   |
| ASUS PRIME               | 5         | 2.75%   |
| Dell Precision           | 4         | 2.2%    |
| Dell OptiPlex            | 4         | 2.2%    |
| Dell Latitude            | 4         | 2.2%    |
| Unknown                  | 4         | 2.2%    |
| HP ProBook               | 3         | 1.65%   |
| HP Compaq                | 3         | 1.65%   |
| ASUS ZenBook             | 3         | 1.65%   |
| ASUS VivoBook            | 3         | 1.65%   |
| ASUS All                 | 3         | 1.65%   |
| Lenovo Yoga              | 2         | 1.1%    |
| HP ZBook                 | 2         | 1.1%    |
| HP Laptop                | 2         | 1.1%    |
| Gigabyte Z77-D3H         | 2         | 1.1%    |
| Gigabyte Z370            | 2         | 1.1%    |
| Gigabyte AERO            | 2         | 1.1%    |
| Dell PowerEdge           | 2         | 1.1%    |
| ASRock B450M             | 2         | 1.1%    |
| UNOWHY Y13G002S4EI       | 1         | 0.55%   |
| Toshiba Satellite        | 1         | 0.55%   |
| Supermicro SYS-6019P-WT  | 1         | 0.55%   |
| sunxi Banana             | 1         | 0.55%   |
| Samsung 370E4K           | 1         | 0.55%   |
| Protectli FW6            | 1         | 0.55%   |
| Pine Microsystems Pine64 | 1         | 0.55%   |
| Pegatron A15             | 1         | 0.55%   |
| MSI U90                  | 1         | 0.55%   |
| MSI MS-7C56              | 1         | 0.55%   |
| MSI MS-7B89              | 1         | 0.55%   |
| MSI MS-7A70              | 1         | 0.55%   |
| MSI MS-7A40              | 1         | 0.55%   |
| MSI MS-7995              | 1         | 0.55%   |
| MSI MS-7823              | 1         | 0.55%   |
| MSI MS-7759              | 1         | 0.55%   |
| MSI MS-7721              | 1         | 0.55%   |
| MSI MS-6712              | 1         | 0.55%   |
| MSI Modern               | 1         | 0.55%   |
| MSI GF65                 | 1         | 0.55%   |
| MSI CX700                | 1         | 0.55%   |
| Monster ABRA             | 1         | 0.55%   |
| Lenovo ThinkCentre       | 1         | 0.55%   |
| Lenovo G50-80            | 1         | 0.55%   |
| Itautec Infoway          | 1         | 0.55%   |
| Intel NUC8i5BEH          | 1         | 0.55%   |
| Intel NUC10i7FNH         | 1         | 0.55%   |
| Intel DP55WB             | 1         | 0.55%   |
| HUAWEI BOHK-WAX9X        | 1         | 0.55%   |
| Huanan X99-F8            | 1         | 0.55%   |
| Huanan X99-8M-F          | 1         | 0.55%   |
| HP Stream                | 1         | 0.55%   |
| HP Split                 | 1         | 0.55%   |
| HP ProLiant              | 1         | 0.55%   |
| HP ENVY                  | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 44        | 24.18%  |
| 2021    | 30        | 16.48%  |
| 2019    | 27        | 14.84%  |
| 2018    | 17        | 9.34%   |
| 2012    | 11        | 6.04%   |
| 2016    | 9         | 4.95%   |
| 2014    | 9         | 4.95%   |
| Unknown | 6         | 3.3%    |
| 2015    | 5         | 2.75%   |
| 2013    | 5         | 2.75%   |
| 2011    | 4         | 2.2%    |
| 2017    | 3         | 1.65%   |
| 2010    | 3         | 1.65%   |
| 2009    | 3         | 1.65%   |
| 2008    | 2         | 1.1%    |
| 2007    | 2         | 1.1%    |
| 2004    | 1         | 0.55%   |
| 2001    | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 97        | 53.3%   |
| Desktop        | 65        | 35.71%  |
| System on chip | 5         | 2.75%   |
| Convertible    | 5         | 2.75%   |
| Mini pc        | 3         | 1.65%   |
| Server         | 3         | 1.65%   |
| Tablet         | 2         | 1.1%    |
| Phone          | 1         | 0.55%   |
| All in one     | 1         | 0.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 160       | 87.43%  |
| Enabled  | 23        | 12.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 181       | 99.45%  |
| Yes  | 1         | 0.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 53        | 29.12%  |
| 8.01-16.0       | 34        | 18.68%  |
| 4.01-8.0        | 33        | 18.13%  |
| 32.01-64.0      | 17        | 9.34%   |
| 64.01-256.0     | 15        | 8.24%   |
| 3.01-4.0        | 14        | 7.69%   |
| 1.01-2.0        | 8         | 4.4%    |
| 2.01-3.0        | 6         | 3.3%    |
| More than 256.0 | 1         | 0.55%   |
| 24.01-32.0      | 1         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 44        | 23.66%  |
| 4.01-8.0    | 37        | 19.89%  |
| 3.01-4.0    | 31        | 16.67%  |
| 1.01-2.0    | 30        | 16.13%  |
| 8.01-16.0   | 15        | 8.06%   |
| 0.51-1.0    | 15        | 8.06%   |
| 16.01-24.0  | 4         | 2.15%   |
| 32.01-64.0  | 3         | 1.61%   |
| 24.01-32.0  | 3         | 1.61%   |
| 0.01-0.5    | 3         | 1.61%   |
| 64.01-256.0 | 1         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 85        | 46.7%   |
| 2      | 60        | 32.97%  |
| 3      | 17        | 9.34%   |
| 4      | 6         | 3.3%    |
| 8      | 5         | 2.75%   |
| 5      | 5         | 2.75%   |
| 0      | 2         | 1.1%    |
| 9      | 1         | 0.55%   |
| 6      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 126       | 69.23%  |
| Yes       | 56        | 30.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 81.32%  |
| No        | 34        | 18.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 73.08%  |
| No        | 49        | 26.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 57.14%  |
| No        | 78        | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country       | Computers | Percent |
|---------------|-----------|---------|
| USA           | 30        | 16.48%  |
| France        | 20        | 10.99%  |
| Germany       | 17        | 9.34%   |
| Russia        | 13        | 7.14%   |
| Poland        | 10        | 5.49%   |
| Brazil        | 10        | 5.49%   |
| Spain         | 9         | 4.95%   |
| Canada        | 6         | 3.3%    |
| Italy         | 5         | 2.75%   |
| Ukraine       | 4         | 2.2%    |
| India         | 4         | 2.2%    |
| Hungary       | 4         | 2.2%    |
| Australia     | 4         | 2.2%    |
| Turkey        | 3         | 1.65%   |
| Switzerland   | 3         | 1.65%   |
| Portugal      | 3         | 1.65%   |
| Netherlands   | 3         | 1.65%   |
| Bulgaria      | 3         | 1.65%   |
| Argentina     | 3         | 1.65%   |
| UK            | 2         | 1.1%    |
| Norway        | 2         | 1.1%    |
| Japan         | 2         | 1.1%    |
| Croatia       | 2         | 1.1%    |
| Belgium       | 2         | 1.1%    |
| Vietnam       | 1         | 0.55%   |
| Thailand      | 1         | 0.55%   |
| Syria         | 1         | 0.55%   |
| Singapore     | 1         | 0.55%   |
| Serbia        | 1         | 0.55%   |
| Romania       | 1         | 0.55%   |
| Philippines   | 1         | 0.55%   |
| New Caledonia | 1         | 0.55%   |
| Mexico        | 1         | 0.55%   |
| Madagascar    | 1         | 0.55%   |
| Kazakhstan    | 1         | 0.55%   |
| Greece        | 1         | 0.55%   |
| Finland       | 1         | 0.55%   |
| Denmark       | 1         | 0.55%   |
| Czechia       | 1         | 0.55%   |
| Colombia      | 1         | 0.55%   |
| China         | 1         | 0.55%   |
| Belarus       | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| St Petersburg               | 5         | 2.73%   |
| Paris                       | 4         | 2.19%   |
| Warsaw                      | 3         | 1.64%   |
| Sofia                       | 3         | 1.64%   |
| Mesa                        | 3         | 1.64%   |
| Lyon                        | 3         | 1.64%   |
| Bengaluru                   | 3         | 1.64%   |
| Waregem                     | 2         | 1.09%   |
| Shizuoka                    | 2         | 1.09%   |
| Rio de Janeiro              | 2         | 1.09%   |
| Noblesville                 | 2         | 1.09%   |
| New York                    | 2         | 1.09%   |
| Madrid                      | 2         | 1.09%   |
| Las Vegas                   | 2         | 1.09%   |
| Kyiv                        | 2         | 1.09%   |
| Ankara                      | 2         | 1.09%   |
| Érd                        | 1         | 0.55%   |
| Zaragoza                    | 1         | 0.55%   |
| Zagreb                      | 1         | 0.55%   |
| Woolloongabba               | 1         | 0.55%   |
| Woodstock                   | 1         | 0.55%   |
| Waterloo                    | 1         | 0.55%   |
| Vladivostok                 | 1         | 0.55%   |
| Vitória                    | 1         | 0.55%   |
| Vancouver                   | 1         | 0.55%   |
| Utrecht                     | 1         | 0.55%   |
| Turin                       | 1         | 0.55%   |
| Toulouse                    | 1         | 0.55%   |
| Toul                        | 1         | 0.55%   |
| Toronto                     | 1         | 0.55%   |
| Thionville                  | 1         | 0.55%   |
| Sunnyvale                   | 1         | 0.55%   |
| Stavanger                   | 1         | 0.55%   |
| Srednyaya Akhtuba           | 1         | 0.55%   |
| Sosnowiec                   | 1         | 0.55%   |
| Singapore                   | 1         | 0.55%   |
| Schleswig                   | 1         | 0.55%   |
| Sarand                      | 1         | 0.55%   |
| San Justo                   | 1         | 0.55%   |
| San Francisco               | 1         | 0.55%   |
| San Cristóbal de La Laguna | 1         | 0.55%   |
| Saint-Denis                 | 1         | 0.55%   |
| Sagunto                     | 1         | 0.55%   |
| Rottenburg                  | 1         | 0.55%   |
| Rochester                   | 1         | 0.55%   |
| Ribeirao Pires              | 1         | 0.55%   |
| Reliquias                   | 1         | 0.55%   |
| Regen                       | 1         | 0.55%   |
| Ratiskovice                 | 1         | 0.55%   |
| Pula                        | 1         | 0.55%   |
| Providence                  | 1         | 0.55%   |
| Piracicaba                  | 1         | 0.55%   |
| Perth                       | 1         | 0.55%   |
| Perm                        | 1         | 0.55%   |
| Paderno Franciacorta        | 1         | 0.55%   |
| Odessa                      | 1         | 0.55%   |
| Oberhausen                  | 1         | 0.55%   |
| Nur-Sultan                  | 1         | 0.55%   |
| Novo Hamburgo               | 1         | 0.55%   |
| Nova Porteirinha            | 1         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 43        | 66     | 15.58%  |
| Seagate             | 43        | 67     | 15.58%  |
| Samsung Electronics | 43        | 61     | 15.58%  |
| Toshiba             | 20        | 25     | 7.25%   |
| Unknown             | 16        | 24     | 5.8%    |
| Kingston            | 15        | 19     | 5.43%   |
| Crucial             | 13        | 14     | 4.71%   |
| Intel               | 11        | 18     | 3.99%   |
| SK Hynix            | 8         | 9      | 2.9%    |
| A-DATA Technology   | 8         | 10     | 2.9%    |
| Sandisk             | 7         | 7      | 2.54%   |
| Hitachi             | 4         | 4      | 1.45%   |
| Intenso             | 3         | 3      | 1.09%   |
| China               | 3         | 3      | 1.09%   |
| Transcend           | 2         | 2      | 0.72%   |
| PNY                 | 2         | 2      | 0.72%   |
| Phison Electronics  | 2         | 2      | 0.72%   |
| Phison              | 2         | 3      | 0.72%   |
| Patriot             | 2         | 2      | 0.72%   |
| Micron Technology   | 2         | 2      | 0.72%   |
| LITEONIT            | 2         | 2      | 0.72%   |
| LITEON              | 2         | 2      | 0.72%   |
| KIOXIA              | 2         | 2      | 0.72%   |
| JMicron             | 2         | 2      | 0.72%   |
| HGST                | 2         | 2      | 0.72%   |
| Gigabyte Technology | 2         | 2      | 0.72%   |
| Apple               | 2         | 2      | 0.72%   |
| ZTC                 | 1         | 1      | 0.36%   |
| XPG                 | 1         | 1      | 0.36%   |
| Union Memory        | 1         | 1      | 0.36%   |
| Team                | 1         | 1      | 0.36%   |
| SPCC                | 1         | 1      | 0.36%   |
| Silicon Motion      | 1         | 1      | 0.36%   |
| SABRENT             | 1         | 1      | 0.36%   |
| Maxtor              | 1         | 1      | 0.36%   |
| Maximus             | 1         | 1      | 0.36%   |
| LDLC                | 1         | 1      | 0.36%   |
| Fujitsu             | 1         | 1      | 0.36%   |
| Corsair             | 1         | 1      | 0.36%   |
| AMD                 | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 970 EVO Plus 1TB       | 5         | 1.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 3         | 0.95%   |
| WDC WD10SPZX-21Z10T0 1TB           | 3         | 0.95%   |
| Toshiba HDWD110 1TB                | 3         | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.95%   |
| Samsung SSD 860 EVO 250GB          | 3         | 0.95%   |
| Samsung SSD 860 EVO 1TB            | 3         | 0.95%   |
| Samsung SSD 850 EVO 250GB          | 3         | 0.95%   |
| Samsung SSD 840 PRO Series 256GB   | 3         | 0.95%   |
| Kingston SV300S37A240G 240GB SSD   | 3         | 0.95%   |
| Kingston SA400S37240G 240GB SSD    | 3         | 0.95%   |
| Crucial CT1000MX500SSD1 1TB        | 3         | 0.95%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 2         | 0.63%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 0.63%   |
| WDC WD20EARX-00PASB0 2TB           | 2         | 0.63%   |
| Unknown MMC Card  64GB             | 2         | 0.63%   |
| Unknown MMC Card  32GB             | 2         | 0.63%   |
| Toshiba MQ01ACF032 320GB           | 2         | 0.63%   |
| Toshiba DT01ACA300 3TB             | 2         | 0.63%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB     | 2         | 0.63%   |
| Seagate ST3000DM001-1CH166 3TB     | 2         | 0.63%   |
| Seagate ST2000LX001-1RG174 2TB     | 2         | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB     | 2         | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB     | 2         | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 0.63%   |
| Seagate BUP Slim BL 2TB            | 2         | 0.63%   |
| Sandisk NVMe SSD Drive 1TB         | 2         | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB     | 2         | 0.63%   |
| Samsung SSD 860 EVO 500GB          | 2         | 0.63%   |
| Samsung SSD 860 EVO 2TB            | 2         | 0.63%   |
| Samsung SSD 850 EVO 500GB          | 2         | 0.63%   |
| Samsung HD103SJ 1TB                | 2         | 0.63%   |
| Phison PCIe SSD 512GB              | 2         | 0.63%   |
| KIOXIA KBG40ZNV1T02 1TB            | 2         | 0.63%   |
| Kingston SV300S37A120G 120GB SSD   | 2         | 0.63%   |
| Kingston OM8PCP3512F-AI1 512GB     | 2         | 0.63%   |
| Intel NVMe SSD Drive 1024GB        | 2         | 0.63%   |
| Intel MEMPEK1J016GAL 16GB          | 2         | 0.63%   |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.63%   |
| ZTC SM201-512G SSD                 | 1         | 0.32%   |
| XPG NVMe SSD Drive 1024GB          | 1         | 0.32%   |
| WDC WUH721414ALE6L4 14TB           | 1         | 0.32%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.32%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.32%   |
| WDC WDS100T3X0C-00SJG0 1TB         | 1         | 0.32%   |
| WDC WDBRPG5000ANC-WRSN 500GB       | 1         | 0.32%   |
| WDC WD5003ABYX-18WERA0 500GB       | 1         | 0.32%   |
| WDC WD5000BPVT-00HXZT3 500GB       | 1         | 0.32%   |
| WDC WD5000AZRX-00A8LB0 500GB       | 1         | 0.32%   |
| WDC WD5000AVCS-632DY1 500GB        | 1         | 0.32%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 0.32%   |
| WDC WD5000AAKS-22V1A0 500GB        | 1         | 0.32%   |
| WDC WD5000A 500GB                  | 1         | 0.32%   |
| WDC WD50 00LPCX-24VHA 500GB        | 1         | 0.32%   |
| WDC WD400BB-00DEA0 40GB            | 1         | 0.32%   |
| WDC WD30EZRX-22D8PB0 3TB           | 1         | 0.32%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 56     | 42.55%  |
| WDC                 | 31        | 46     | 32.98%  |
| Toshiba             | 12        | 17     | 12.77%  |
| Samsung Electronics | 4         | 5      | 4.26%   |
| Hitachi             | 4         | 4      | 4.26%   |
| HGST                | 2         | 2      | 2.13%   |
| Fujitsu             | 1         | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 35     | 24.44%  |
| Kingston            | 11        | 15     | 12.22%  |
| Crucial             | 11        | 11     | 12.22%  |
| WDC                 | 6         | 9      | 6.67%   |
| A-DATA Technology   | 5         | 5      | 5.56%   |
| Toshiba             | 3         | 3      | 3.33%   |
| SanDisk             | 3         | 3      | 3.33%   |
| Intel               | 3         | 3      | 3.33%   |
| China               | 3         | 3      | 3.33%   |
| Transcend           | 2         | 2      | 2.22%   |
| Patriot             | 2         | 2      | 2.22%   |
| LITEONIT            | 2         | 2      | 2.22%   |
| Intenso             | 2         | 2      | 2.22%   |
| ZTC                 | 1         | 1      | 1.11%   |
| Unknown             | 1         | 1      | 1.11%   |
| Union Memory        | 1         | 1      | 1.11%   |
| Team                | 1         | 1      | 1.11%   |
| SK Hynix            | 1         | 1      | 1.11%   |
| Seagate             | 1         | 1      | 1.11%   |
| PNY                 | 1         | 1      | 1.11%   |
| Micron Technology   | 1         | 1      | 1.11%   |
| Maxtor              | 1         | 1      | 1.11%   |
| Maximus             | 1         | 1      | 1.11%   |
| LITEON              | 1         | 1      | 1.11%   |
| LDLC                | 1         | 1      | 1.11%   |
| JMicron             | 1         | 1      | 1.11%   |
| Apple               | 1         | 1      | 1.11%   |
| AMD                 | 1         | 1      | 1.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 82        | 110    | 32.28%  |
| HDD     | 79        | 131    | 31.1%   |
| NVMe    | 72        | 92     | 28.35%  |
| MMC     | 14        | 23     | 5.51%   |
| Unknown | 7         | 14     | 2.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 120       | 231    | 54.3%   |
| NVMe | 71        | 91     | 32.13%  |
| SAS  | 16        | 25     | 7.24%   |
| MMC  | 14        | 23     | 6.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 82        | 121    | 49.1%   |
| 0.51-1.0   | 49        | 63     | 29.34%  |
| 1.01-2.0   | 21        | 25     | 12.57%  |
| 3.01-4.0   | 5         | 5      | 2.99%   |
| 2.01-3.0   | 5         | 9      | 2.99%   |
| 4.01-10.0  | 3         | 12     | 1.8%    |
| 10.01-20.0 | 2         | 6      | 1.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 41        | 22.4%   |
| 101-250        | 33        | 18.03%  |
| 501-1000       | 28        | 15.3%   |
| 1001-2000      | 22        | 12.02%  |
| More than 3000 | 16        | 8.74%   |
| 51-100         | 11        | 6.01%   |
| Unknown        | 9         | 4.92%   |
| 21-50          | 8         | 4.37%   |
| 1-20           | 8         | 4.37%   |
| 2001-3000      | 7         | 3.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 42        | 22.83%  |
| 101-250        | 31        | 16.85%  |
| 21-50          | 25        | 13.59%  |
| 51-100         | 21        | 11.41%  |
| 251-500        | 20        | 10.87%  |
| 501-1000       | 14        | 7.61%   |
| 1001-2000      | 10        | 5.43%   |
| Unknown        | 9         | 4.89%   |
| 2001-3000      | 6         | 3.26%   |
| More than 3000 | 4         | 2.17%   |
| 0              | 2         | 1.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5003ABYX-18WERA0 500GB                 | 1         | 2      | 3.33%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 3.33%   |
| WDC WD5000AAKS-22V1A0 500GB                  | 1         | 1      | 3.33%   |
| WDC WD400BB-00DEA0 40GB                      | 1         | 1      | 3.33%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 3.33%   |
| WDC WD1600AAJS-00L7A0 160GB                  | 1         | 1      | 3.33%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 1         | 1      | 3.33%   |
| WDC WD1001FALS-75J7B0 1TB                    | 1         | 1      | 3.33%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 3.33%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 3.33%   |
| Seagate ST32000542AS 2TB                     | 1         | 1      | 3.33%   |
| Seagate ST31500341AS 1TB                     | 1         | 1      | 3.33%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 3.33%   |
| Seagate ST2000LX001-1RG174 2TB               | 1         | 1      | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 3.33%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 3.33%   |
| LITEONIT LMT-64M6M-HP 64GB SSD               | 1         | 1      | 3.33%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 3.33%   |
| Intel SSDSC2KW120H6 120GB                    | 1         | 1      | 3.33%   |
| Intel SSDSC2BF180A4H 180GB                   | 1         | 1      | 3.33%   |
| Intel SSDPEKKW010T7 1TB                      | 1         | 2      | 3.33%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 3.33%   |
| Hitachi HTS543212L9A300 120GB                | 1         | 1      | 3.33%   |
| Hitachi HDS722525VLAT80 250GB                | 1         | 1      | 3.33%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 3.33%   |
| A-DATA Technology SU630 480GB SSD            | 1         | 1      | 3.33%   |
| A-DATA Technology SSD DP900 128GB-DL3        | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 30%     |
| WDC                 | 8         | 9      | 26.67%  |
| Intel               | 3         | 4      | 10%     |
| Hitachi             | 3         | 3      | 10%     |
| A-DATA Technology   | 2         | 2      | 6.67%   |
| Toshiba             | 1         | 1      | 3.33%   |
| Samsung Electronics | 1         | 2      | 3.33%   |
| LITEONIT            | 1         | 1      | 3.33%   |
| Kingston            | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 9      | 40.91%  |
| WDC     | 8         | 9      | 36.36%  |
| Hitachi | 3         | 3      | 13.64%  |
| Toshiba | 1         | 1      | 4.55%   |
| HGST    | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 23     | 72.41%  |
| SSD  | 7         | 8      | 24.14%  |
| NVMe | 1         | 2      | 3.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500830AS 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 136       | 246    | 64.45%  |
| Detected | 46        | 90     | 21.8%   |
| Malfunc  | 28        | 33     | 13.27%  |
| Failed   | 1         | 1      | 0.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 110       | 48.89%  |
| AMD                          | 34        | 15.11%  |
| Samsung Electronics          | 22        | 9.78%   |
| Sandisk                      | 12        | 5.33%   |
| Phison Electronics           | 8         | 3.56%   |
| SK Hynix                     | 7         | 3.11%   |
| Toshiba America Info Systems | 5         | 2.22%   |
| Kingston Technology Company  | 4         | 1.78%   |
| ASMedia Technology           | 4         | 1.78%   |
| ADATA Technology             | 4         | 1.78%   |
| Micron/Crucial Technology    | 3         | 1.33%   |
| KIOXIA                       | 2         | 0.89%   |
| JMicron Technology           | 2         | 0.89%   |
| Broadcom / LSI               | 2         | 0.89%   |
| VIA Technologies             | 1         | 0.44%   |
| Silicon Motion               | 1         | 0.44%   |
| Micron Technology            | 1         | 0.44%   |
| Marvell Technology Group     | 1         | 0.44%   |
| Lite-On Technology           | 1         | 0.44%   |
| Adaptec                      | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 26        | 10.08%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 5.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 4.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 3.88%   |
| AMD 400 Series Chipset SATA Controller                                           | 9         | 3.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 3.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 3.1%    |
| Phison E12 NVMe Controller                                                       | 6         | 2.33%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 1.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 1.94%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 4         | 1.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.55%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 1.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4         | 1.55%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 4         | 1.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 1.16%   |
| SK Hynix NVMe SSD Controller                                                     | 3         | 1.16%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 1.16%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.16%   |
| Intel SSD 600P Series                                                            | 3         | 1.16%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.16%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.16%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.16%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.78%   |
| Samsung NVMe Controller                                                          | 2         | 0.78%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 2         | 0.78%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 0.78%   |
| Intel SSD 660P Series                                                            | 2         | 0.78%   |
| Intel NVMe Optane Memory Series                                                  | 2         | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 0.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.78%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.78%   |
| AMD FCH SATA Controller D                                                        | 2         | 0.78%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 0.78%   |
| ADATA Non-Volatile memory controller                                             | 2         | 0.78%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.39%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.39%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.39%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.39%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.39%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.39%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.39%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.39%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.39%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 124       | 54.63%  |
| NVMe | 71        | 31.28%  |
| RAID | 16        | 7.05%   |
| IDE  | 14        | 6.17%   |
| SAS  | 2         | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 133       | 73.08%  |
| AMD    | 43        | 23.63%  |
| ARM    | 6         | 3.3%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz               | 5         | 2.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 5         | 2.75%   |
| ARM Processor                                   | 4         | 2.2%    |
| AMD Ryzen 5 3600 6-Core Processor               | 4         | 2.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 4         | 2.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 3         | 1.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 3         | 1.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 3         | 1.65%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 1.65%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 3         | 1.65%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 3         | 1.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.1%    |
| Intel Core i7-8700K CPU @ 3.70GHz               | 2         | 1.1%    |
| Intel Core i7-8700 CPU @ 3.20GHz                | 2         | 1.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 1.1%    |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 1.1%    |
| Intel Core i7-10710U CPU @ 1.10GHz              | 2         | 1.1%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 2         | 1.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz              | 2         | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 1.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 1.1%    |
| Intel Core i5-4460 CPU @ 3.20GHz                | 2         | 1.1%    |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.1%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 2         | 1.1%    |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 1.1%    |
| AMD Ryzen 5 5600X 6-Core Processor              | 2         | 1.1%    |
| Intel Xeon Silver 4215R CPU @ 3.20GHz           | 1         | 0.55%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                | 1         | 0.55%   |
| Intel Xeon CPU W3503 @ 2.40GHz                  | 1         | 0.55%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz             | 1         | 0.55%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz             | 1         | 0.55%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz             | 1         | 0.55%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz              | 1         | 0.55%   |
| Intel Pentium M processor 1600MHz               | 1         | 0.55%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 1         | 0.55%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1         | 0.55%   |
| Intel Pentium CPU 4415U @ 2.30GHz               | 1         | 0.55%   |
| Intel Pentium CPU 4405Y @ 1.50GHz               | 1         | 0.55%   |
| Intel Pentium 3556U @ 1.70GHz                   | 1         | 0.55%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz                | 1         | 0.55%   |
| Intel Core i9-9900K CPU @ 3.60GHz               | 1         | 0.55%   |
| Intel Core i7-8086K CPU @ 4.00GHz               | 1         | 0.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.55%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 0.55%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 0.55%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 0.55%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 0.55%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 0.55%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.55%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 0.55%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 1         | 0.55%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1         | 0.55%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 0.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 0.55%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 1         | 0.55%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 0.55%   |
| Intel Core i7-3612QM CPU @ 2.10GHz              | 1         | 0.55%   |
| Intel Core i7-3610QM CPU @ 2.30GHz              | 1         | 0.55%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 46        | 25.27%  |
| Intel Core i7          | 41        | 22.53%  |
| Other                  | 15        | 8.24%   |
| AMD Ryzen 5            | 15        | 8.24%   |
| AMD Ryzen 7            | 8         | 4.4%    |
| Intel Celeron          | 7         | 3.85%   |
| Intel Xeon             | 6         | 3.3%    |
| Intel Core i3          | 6         | 3.3%    |
| Intel Pentium          | 5         | 2.75%   |
| Intel Core 2 Duo       | 4         | 2.2%    |
| AMD Ryzen 7 PRO        | 4         | 2.2%    |
| AMD Ryzen 9            | 3         | 1.65%   |
| Intel Atom             | 2         | 1.1%    |
| AMD Ryzen 3            | 2         | 1.1%    |
| Intel Xeon Silver      | 1         | 0.55%   |
| Intel Pentium M        | 1         | 0.55%   |
| Intel Core m7          | 1         | 0.55%   |
| Intel Core i9          | 1         | 0.55%   |
| Intel Core 2 Quad      | 1         | 0.55%   |
| Intel Core 2           | 1         | 0.55%   |
| ARM Allwinner          | 1         | 0.55%   |
| ARM AArch64            | 1         | 0.55%   |
| AMD Ryzen Threadripper | 1         | 0.55%   |
| AMD Phenom II X4       | 1         | 0.55%   |
| AMD FX                 | 1         | 0.55%   |
| AMD Athlon XP          | 1         | 0.55%   |
| AMD Athlon X4          | 1         | 0.55%   |
| AMD Athlon II Neo      | 1         | 0.55%   |
| AMD A8                 | 1         | 0.55%   |
| AMD A6                 | 1         | 0.55%   |
| AMD A12                | 1         | 0.55%   |
| AMD A10                | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 73        | 40.11%  |
| 2      | 57        | 31.32%  |
| 6      | 26        | 14.29%  |
| 8      | 14        | 7.69%   |
| 1      | 5         | 2.75%   |
| 12     | 4         | 2.2%    |
| 44     | 1         | 0.55%   |
| 32     | 1         | 0.55%   |
| 16     | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 178       | 97.8%   |
| 2      | 4         | 2.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 132       | 72.53%  |
| 1      | 50        | 27.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 176       | 96.7%   |
| 32-bit         | 3         | 1.65%   |
| 64-bit         | 2         | 1.1%    |
| Unknown        | 1         | 0.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 26.23%  |
| 0x306a9    | 13        | 7.1%    |
| 0x806c1    | 9         | 4.92%   |
| 0x206a7    | 8         | 4.37%   |
| 0x906ea    | 6         | 3.28%   |
| 0x806e9    | 6         | 3.28%   |
| 0x406e3    | 6         | 3.28%   |
| 0x306c3    | 6         | 3.28%   |
| 0x806ec    | 5         | 2.73%   |
| 0x08701021 | 5         | 2.73%   |
| 0x806ea    | 4         | 2.19%   |
| 0x706e5    | 4         | 2.19%   |
| 0xa0652    | 3         | 1.64%   |
| 0x506e3    | 3         | 1.64%   |
| 0x506c9    | 3         | 1.64%   |
| 0x40651    | 3         | 1.64%   |
| 0x306d4    | 3         | 1.64%   |
| 0x08600106 | 3         | 1.64%   |
| 0x08108109 | 3         | 1.64%   |
| 0x06003106 | 3         | 1.64%   |
| 0xa0660    | 2         | 1.09%   |
| 0x906e9    | 2         | 1.09%   |
| 0x806eb    | 2         | 1.09%   |
| 0x406c4    | 2         | 1.09%   |
| 0x306f2    | 2         | 1.09%   |
| 0x0800820d | 2         | 1.09%   |
| 0x08001138 | 2         | 1.09%   |
| 0xa0671    | 1         | 0.55%   |
| 0x906ec    | 1         | 0.55%   |
| 0x706a1    | 1         | 0.55%   |
| 0x6fb      | 1         | 0.55%   |
| 0x6f6      | 1         | 0.55%   |
| 0x695      | 1         | 0.55%   |
| 0x50657    | 1         | 0.55%   |
| 0x406f1    | 1         | 0.55%   |
| 0x406c3    | 1         | 0.55%   |
| 0x206d7    | 1         | 0.55%   |
| 0x20655    | 1         | 0.55%   |
| 0x106e5    | 1         | 0.55%   |
| 0x106c2    | 1         | 0.55%   |
| 0x106a5    | 1         | 0.55%   |
| 0x1067a    | 1         | 0.55%   |
| 0x10661    | 1         | 0.55%   |
| 0x0a50000b | 1         | 0.55%   |
| 0x0a201009 | 1         | 0.55%   |
| 0x08701013 | 1         | 0.55%   |
| 0x08600104 | 1         | 0.55%   |
| 0x08108102 | 1         | 0.55%   |
| 0x0800820b | 1         | 0.55%   |
| 0x06006705 | 1         | 0.55%   |
| 0x0600611a | 1         | 0.55%   |
| 0x010000c8 | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 34        | 18.68%  |
| IvyBridge     | 18        | 9.89%   |
| Zen 2         | 17        | 9.34%   |
| Skylake       | 14        | 7.69%   |
| Haswell       | 14        | 7.69%   |
| Zen+          | 11        | 6.04%   |
| TigerLake     | 9         | 4.95%   |
| SandyBridge   | 9         | 4.95%   |
| Unknown       | 7         | 3.85%   |
| CometLake     | 6         | 3.3%    |
| Core          | 5         | 2.75%   |
| Steamroller   | 4         | 2.2%    |
| IceLake       | 4         | 2.2%    |
| Broadwell     | 4         | 2.2%    |
| Zen 3         | 3         | 1.65%   |
| Silvermont    | 3         | 1.65%   |
| Goldmont      | 3         | 1.65%   |
| Zen           | 2         | 1.1%    |
| Westmere      | 2         | 1.1%    |
| Penryn        | 2         | 1.1%    |
| Nehalem       | 2         | 1.1%    |
| K10           | 2         | 1.1%    |
| Excavator     | 2         | 1.1%    |
| Piledriver    | 1         | 0.55%   |
| P6            | 1         | 0.55%   |
| K6            | 1         | 0.55%   |
| Goldmont plus | 1         | 0.55%   |
| Bonnell       | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 109       | 53.17%  |
| Nvidia                     | 52        | 25.37%  |
| AMD                        | 42        | 20.49%  |
| Matrox Electronics Systems | 1         | 0.49%   |
| ASPEED Technology          | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 5.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 3.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.83%   |
| Intel HD Graphics 620                                                                    | 6         | 2.83%   |
| AMD Renoir                                                                               | 6         | 2.83%   |
| AMD Picasso                                                                              | 6         | 2.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 2.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.36%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.36%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.89%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 1.89%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.42%   |
| Intel HD Graphics 530                                                                    | 3         | 1.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.42%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.42%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.42%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.94%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 2         | 0.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.94%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.94%   |
| Intel HD Graphics 515                                                                    | 2         | 0.94%   |
| Intel HD Graphics 500                                                                    | 2         | 0.94%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.94%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.94%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.47%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.47%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.47%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.47%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.47%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.47%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.47%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.47%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1         | 0.47%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.47%   |
| Nvidia GV100GL [Quadro GV100]                                                            | 1         | 0.47%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.47%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.47%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.47%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.47%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.47%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.47%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.47%   |
| Nvidia GP104GLM [Quadro P3200 Mobile]                                                    | 1         | 0.47%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.47%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 82        | 44.57%  |
| 1 x AMD         | 34        | 18.48%  |
| 1 x Nvidia      | 28        | 15.22%  |
| Intel + Nvidia  | 23        | 12.5%   |
| Other           | 7         | 3.8%    |
| Intel + AMD     | 4         | 2.17%   |
| 2 x AMD         | 3         | 1.63%   |
| Nvidia + Matrox | 1         | 0.54%   |
| 1 x ASPEED      | 1         | 0.54%   |
| AMD + Nvidia    | 1         | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 154       | 84.15%  |
| Proprietary | 20        | 10.93%  |
| Unknown     | 9         | 4.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 70.49%  |
| 1.01-2.0   | 11        | 6.01%   |
| 0.01-0.5   | 11        | 6.01%   |
| 7.01-8.0   | 9         | 4.92%   |
| 3.01-4.0   | 8         | 4.37%   |
| 0.51-1.0   | 8         | 4.37%   |
| 5.01-6.0   | 5         | 2.73%   |
| 24.01-32.0 | 1         | 0.55%   |
| 2.01-3.0   | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 30        | 14.35%  |
| Samsung Electronics  | 27        | 12.92%  |
| BOE                  | 18        | 8.61%   |
| Chimei Innolux       | 16        | 7.66%   |
| LG Display           | 15        | 7.18%   |
| Goldstar             | 12        | 5.74%   |
| Dell                 | 11        | 5.26%   |
| Acer                 | 11        | 5.26%   |
| Hewlett-Packard      | 9         | 4.31%   |
| Ancor Communications | 9         | 4.31%   |
| Sharp                | 7         | 3.35%   |
| BenQ                 | 5         | 2.39%   |
| AOC                  | 5         | 2.39%   |
| Philips              | 4         | 1.91%   |
| Unknown              | 2         | 0.96%   |
| LG Electronics       | 2         | 0.96%   |
| Lenovo               | 2         | 0.96%   |
| Iiyama               | 2         | 0.96%   |
| CPT                  | 2         | 0.96%   |
| Apple                | 2         | 0.96%   |
| ___                  | 1         | 0.48%   |
| ViewSonic            | 1         | 0.48%   |
| Vestel Elektronik    | 1         | 0.48%   |
| TEO                  | 1         | 0.48%   |
| Sony                 | 1         | 0.48%   |
| PANDA                | 1         | 0.48%   |
| ODH                  | 1         | 0.48%   |
| NCS                  | 1         | 0.48%   |
| Medion               | 1         | 0.48%   |
| JXG                  | 1         | 0.48%   |
| JVC                  | 1         | 0.48%   |
| InfoVision           | 1         | 0.48%   |
| INFOTRONIC           | 1         | 0.48%   |
| Idek Iiyama          | 1         | 0.48%   |
| Hitachi              | 1         | 0.48%   |
| Eizo                 | 1         | 0.48%   |
| CSO                  | 1         | 0.48%   |
| Belinea              | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 3         | 1.39%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                | 2         | 0.93%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 2         | 0.93%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch | 2         | 0.93%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch            | 2         | 0.93%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2         | 0.93%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch           | 2         | 0.93%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2         | 0.93%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                  | 2         | 0.93%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                   | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch         | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 2         | 0.93%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 2         | 0.93%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2         | 0.93%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                     | 1         | 0.46%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 1         | 0.46%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 0.46%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                    | 1         | 0.46%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1         | 0.46%   |
| TEO TL565 TEO5550 1024x768 304x228mm 15.0-inch                         | 1         | 0.46%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1         | 0.46%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 0.46%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch                | 1         | 0.46%   |
| Sharp LCD Monitor SHP14E2 1920x1080 309x174mm 14.0-inch                | 1         | 0.46%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                | 1         | 0.46%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch   | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x257mm 19.1-inch    | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 1         | 0.46%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 1         | 0.46%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 1         | 0.46%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1         | 0.46%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1         | 0.46%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1         | 0.46%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch      | 1         | 0.46%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch       | 1         | 0.46%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster 5760x1080                   | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SMB2430L                               | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch   | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch   | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch   | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4244 2160x1440 254x169mm 12.0-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SAM0D42 1920x540                       | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1         | 0.46%   |
| Samsung Electronics LCD Monitor C24F390 3360x1080                      | 1         | 0.46%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch     | 1         | 0.46%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch    | 1         | 0.46%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch      | 1         | 0.46%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1         | 0.46%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1         | 0.46%   |
| Philips LCD Monitor PHLD074 1920x1080 640x360mm 28.9-inch              | 1         | 0.46%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                     | 1         | 0.46%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 1         | 0.46%   |
| ODH LM24 ODH2492 1920x1080 345x259mm 17.0-inch                         | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 83        | 41.09%  |
| 1366x768 (WXGA)    | 33        | 16.34%  |
| 3840x2160 (4K)     | 17        | 8.42%   |
| 2560x1440 (QHD)    | 12        | 5.94%   |
| 1600x900 (HD+)     | 11        | 5.45%   |
| 1920x1200 (WUXGA)  | 7         | 3.47%   |
| 1280x1024 (SXGA)   | 6         | 2.97%   |
| 1680x1050 (WSXGA+) | 5         | 2.48%   |
| 1440x900 (WXGA+)   | 5         | 2.48%   |
| Unknown            | 4         | 1.98%   |
| 1280x800 (WXGA)    | 3         | 1.49%   |
| 2560x1600          | 2         | 0.99%   |
| 1600x1200          | 2         | 0.99%   |
| 1024x768 (XGA)     | 2         | 0.99%   |
| 7680x4320          | 1         | 0.5%    |
| 5760x1080          | 1         | 0.5%    |
| 4480x1440          | 1         | 0.5%    |
| 3360x1080          | 1         | 0.5%    |
| 2560x1080          | 1         | 0.5%    |
| 2288x1287          | 1         | 0.5%    |
| 2160x1440          | 1         | 0.5%    |
| 1920x540           | 1         | 0.5%    |
| 1792x768           | 1         | 0.5%    |
| 1024x600           | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 42        | 20.39%  |
| 13      | 23        | 11.17%  |
| 24      | 18        | 8.74%   |
| 14      | 17        | 8.25%   |
| 23      | 16        | 7.77%   |
| 27      | 10        | 4.85%   |
| Unknown | 10        | 4.85%   |
| 17      | 9         | 4.37%   |
| 12      | 9         | 4.37%   |
| 21      | 8         | 3.88%   |
| 31      | 7         | 3.4%    |
| 19      | 6         | 2.91%   |
| 18      | 6         | 2.91%   |
| 11      | 4         | 1.94%   |
| 20      | 3         | 1.46%   |
| 84      | 2         | 0.97%   |
| 47      | 2         | 0.97%   |
| 29      | 2         | 0.97%   |
| 28      | 2         | 0.97%   |
| 142     | 1         | 0.49%   |
| 72      | 1         | 0.49%   |
| 55      | 1         | 0.49%   |
| 48      | 1         | 0.49%   |
| 40      | 1         | 0.49%   |
| 34      | 1         | 0.49%   |
| 33      | 1         | 0.49%   |
| 25      | 1         | 0.49%   |
| 16      | 1         | 0.49%   |
| 10      | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 72        | 35.82%  |
| 501-600        | 39        | 19.4%   |
| 201-300        | 28        | 13.93%  |
| 401-500        | 22        | 10.95%  |
| 601-700        | 12        | 5.97%   |
| Unknown        | 10        | 4.98%   |
| 351-400        | 7         | 3.48%   |
| 1001-1500      | 4         | 1.99%   |
| 1501-2000      | 3         | 1.49%   |
| 701-800        | 2         | 1%      |
| More than 2000 | 1         | 0.5%    |
| 801-900        | 1         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 141       | 75.4%   |
| 16/10   | 17        | 9.09%   |
| Unknown | 9         | 4.81%   |
| 4/3     | 6         | 3.21%   |
| 5/4     | 5         | 2.67%   |
| 3/2     | 4         | 2.14%   |
| 21/9    | 2         | 1.07%   |
| 6/5     | 1         | 0.53%   |
| 1.96    | 1         | 0.53%   |
| 1.00    | 1         | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 42        | 20.79%  |
| 201-250        | 30        | 14.85%  |
| 81-90          | 26        | 12.87%  |
| 71-80          | 15        | 7.43%   |
| 351-500        | 13        | 6.44%   |
| 151-200        | 13        | 6.44%   |
| 301-350        | 10        | 4.95%   |
| Unknown        | 10        | 4.95%   |
| 61-70          | 8         | 3.96%   |
| 251-300        | 7         | 3.47%   |
| 141-150        | 7         | 3.47%   |
| More than 1000 | 5         | 2.48%   |
| 121-130        | 5         | 2.48%   |
| 51-60          | 4         | 1.98%   |
| 501-1000       | 4         | 1.98%   |
| 131-140        | 2         | 0.99%   |
| 41-50          | 1         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 65        | 32.99%  |
| 121-160       | 63        | 31.98%  |
| 101-120       | 32        | 16.24%  |
| 161-240       | 18        | 9.14%   |
| Unknown       | 10        | 5.08%   |
| 1-50          | 5         | 2.54%   |
| More than 240 | 4         | 2.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 133       | 72.28%  |
| 2     | 36        | 19.57%  |
| 0     | 9         | 4.89%   |
| 3     | 5         | 2.72%   |
| 4     | 1         | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 99        | 39.76%  |
| Realtek Semiconductor             | 86        | 34.54%  |
| Qualcomm Atheros                  | 29        | 11.65%  |
| Broadcom                          | 10        | 4.02%   |
| Marvell Technology Group          | 3         | 1.2%    |
| Broadcom Limited                  | 3         | 1.2%    |
| Ralink Technology                 | 2         | 0.8%    |
| Ralink                            | 2         | 0.8%    |
| Cypress Semiconductor             | 2         | 0.8%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.4%    |
| Xiaomi                            | 1         | 0.4%    |
| TP-Link                           | 1         | 0.4%    |
| Sierra Wireless                   | 1         | 0.4%    |
| Qualcomm                          | 1         | 0.4%    |
| Microsoft                         | 1         | 0.4%    |
| Microchip Technology              | 1         | 0.4%    |
| Huawei Technologies               | 1         | 0.4%    |
| Ericsson Business Mobile Networks | 1         | 0.4%    |
| Edimax Technology                 | 1         | 0.4%    |
| DisplayLink                       | 1         | 0.4%    |
| Dell                              | 1         | 0.4%    |
| D-Link                            | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 19.28%  |
| Intel Wi-Fi 6 AX200                                               | 11        | 3.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 3.59%   |
| Intel Wireless 8260                                               | 10        | 3.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 8         | 2.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 2.29%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 2.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.63%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.31%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.31%   |
| Intel Wireless 7260                                               | 4         | 1.31%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.98%   |
| Intel Wireless 7265                                               | 3         | 0.98%   |
| Intel Wireless 3165                                               | 3         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.65%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.65%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.65%   |
| Intel Wireless-AC 9260                                            | 2         | 0.65%   |
| Intel Wireless 3160                                               | 2         | 0.65%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.65%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.65%   |
| Cypress K38231_03                                                 | 2         | 0.65%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1         | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.33%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.33%   |
| Sierra Wireless EM7455                                            | 1         | 0.33%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.33%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.33%   |
| Realtek 802.11ac NIC                                              | 1         | 0.33%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 0.33%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 79        | 57.66%  |
| Qualcomm Atheros      | 25        | 18.25%  |
| Realtek Semiconductor | 17        | 12.41%  |
| Broadcom              | 5         | 3.65%   |
| Ralink Technology     | 2         | 1.46%   |
| Ralink                | 2         | 1.46%   |
| TP-Link               | 1         | 0.73%   |
| Sierra Wireless       | 1         | 0.73%   |
| Qualcomm              | 1         | 0.73%   |
| Microsoft             | 1         | 0.73%   |
| Edimax Technology     | 1         | 0.73%   |
| D-Link                | 1         | 0.73%   |
| Broadcom Limited      | 1         | 0.73%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 11        | 7.97%   |
| Intel Wireless 8260                                                     | 10        | 7.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 6.52%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 5.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 3.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 3.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 3.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.9%    |
| Intel Wireless 8265 / 8275                                              | 4         | 2.9%    |
| Intel Wireless 7260                                                     | 4         | 2.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.17%   |
| Intel Wireless 7265                                                     | 3         | 2.17%   |
| Intel Wireless 3165                                                     | 3         | 2.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 2.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.45%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.45%   |
| Intel Wireless 3160                                                     | 2         | 1.45%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.45%   |
| TP-Link Archer T4U ver.3                                                | 1         | 0.72%   |
| Sierra Wireless EM7455                                                  | 1         | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.72%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.72%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.72%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.72%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.72%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]             | 1         | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.72%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.72%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 0.72%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.72%   |
| Intel Wireless Gigabit 17265                                            | 1         | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.72%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                         | 1         | 0.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.72%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.72%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 0.72%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1         | 0.72%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 0.72%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 1         | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 0.72%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.72%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 78        | 48.75%  |
| Intel                    | 57        | 35.63%  |
| Broadcom                 | 8         | 5%      |
| Qualcomm Atheros         | 6         | 3.75%   |
| Marvell Technology Group | 3         | 1.88%   |
| Cypress Semiconductor    | 2         | 1.25%   |
| Broadcom Limited         | 2         | 1.25%   |
| Xiaomi                   | 1         | 0.63%   |
| Microchip Technology     | 1         | 0.63%   |
| Huawei Technologies      | 1         | 0.63%   |
| DisplayLink              | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 35.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 6.71%   |
| Intel I211 Gigabit Network Connection                             | 8         | 4.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 4.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.66%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 3.05%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.44%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.22%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.22%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.22%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.22%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.22%   |
| Cypress K38231_03                                                 | 2         | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.61%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.61%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.61%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.61%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.61%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.61%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.61%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.61%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.61%   |
| Intel Ethernet Connection X722 for 1GbE                           | 1         | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.61%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.61%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.61%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.61%   |
| Intel 82801DB PRO/100 VM (MOB) Ethernet Controller                | 1         | 0.61%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.61%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.61%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.61%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.61%   |
| Huawei E353/E3131                                                 | 1         | 0.61%   |
| DisplayLink LAPDOCK                                               | 1         | 0.61%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.61%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.61%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1         | 0.61%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.61%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express  | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 148       | 52.11%  |
| WiFi     | 132       | 46.48%  |
| Modem    | 4         | 1.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 116       | 51.79%  |
| Ethernet | 108       | 48.21%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 93        | 51.1%   |
| 1     | 70        | 38.46%  |
| 3     | 9         | 4.95%   |
| 0     | 8         | 4.4%    |
| 6     | 1         | 0.55%   |
| 4     | 1         | 0.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 138       | 75.41%  |
| Yes  | 45        | 24.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 55.66%  |
| Qualcomm Atheros Communications | 10        | 9.43%   |
| Realtek Semiconductor           | 8         | 7.55%   |
| Cambridge Silicon Radio         | 7         | 6.6%    |
| Lite-On Technology              | 6         | 5.66%   |
| Broadcom                        | 5         | 4.72%   |
| Foxconn / Hon Hai               | 3         | 2.83%   |
| ASUSTek Computer                | 2         | 1.89%   |
| Realtek                         | 1         | 0.94%   |
| Ralink                          | 1         | 0.94%   |
| IMC Networks                    | 1         | 0.94%   |
| Hewlett-Packard                 | 1         | 0.94%   |
| Dell                            | 1         | 0.94%   |
| Apple                           | 1         | 0.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 20.75%  |
| Intel Bluetooth Device                              | 12        | 11.32%  |
| Intel AX200 Bluetooth                               | 11        | 10.38%  |
| Realtek Bluetooth Radio                             | 7         | 6.6%    |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 6.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 6.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 6.6%    |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 4.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 2.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.89%   |
| Lite-On Bluetooth Device                            | 2         | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.89%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.89%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.94%   |
| Realtek Bluetooth Radio                             | 1         | 0.94%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.94%   |
| IMC Networks Bluetooth Device                       | 1         | 0.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.94%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.94%   |
| Dell BCM20702A0                                     | 1         | 0.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.94%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 0.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.94%   |
| ASUS Bluetooth Adapter                              | 1         | 0.94%   |
| Apple Bluetooth Host Controller                     | 1         | 0.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 128       | 52.24%  |
| AMD                        | 46        | 18.78%  |
| Nvidia                     | 39        | 15.92%  |
| C-Media Electronics        | 11        | 4.49%   |
| Generalplus Technology     | 3         | 1.22%   |
| Texas Instruments          | 2         | 0.82%   |
| Samson Technologies        | 2         | 0.82%   |
| Logitech                   | 2         | 0.82%   |
| GYROCOM C&C                | 2         | 0.82%   |
| VIA Technologies           | 1         | 0.41%   |
| ROCCAT                     | 1         | 0.41%   |
| Razer USA                  | 1         | 0.41%   |
| PreSonus Audio Electronics | 1         | 0.41%   |
| Hewlett-Packard            | 1         | 0.41%   |
| GN Netcom                  | 1         | 0.41%   |
| Creative Technology        | 1         | 0.41%   |
| Creative Labs              | 1         | 0.41%   |
| Blue Microphones           | 1         | 0.41%   |
| Alesis                     | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 6.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 6.29%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 4.55%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 13        | 4.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.45%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 2.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 2.1%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.75%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.75%   |
| AMD Navi 10 HDMI Audio                                                                            | 5         | 1.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.4%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 1.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.4%    |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.4%    |
| AMD FCH Azalia Controller                                                                         | 4         | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.05%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 1.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.05%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.05%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 1.05%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 1.05%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.7%    |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.7%    |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.7%    |
| GYROCOM C&C Fiio E10                                                                              | 2         | 0.7%    |
| C-Media Electronics USB Audio Device                                                              | 2         | 0.7%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.7%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.7%    |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 0.35%   |
| Samson Technologies Q1U dynamic microphone                                                        | 1         | 0.35%   |
| Samson Technologies Meteorite condenser microphone                                                | 1         | 0.35%   |
| ROCCAT Juke                                                                                       | 1         | 0.35%   |
| Razer USA Razer Thresher 7.1                                                                      | 1         | 0.35%   |
| PreSonus Audio Electronics PreSonus AudioBox iTwo                                                 | 1         | 0.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.35%   |
| Nvidia GV100 TITAN V High Definition Audio Controller                                             | 1         | 0.35%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 33        | 18.33%  |
| Samsung Electronics | 31        | 17.22%  |
| Kingston            | 22        | 12.22%  |
| Crucial             | 17        | 9.44%   |
| Unknown             | 15        | 8.33%   |
| Micron Technology   | 12        | 6.67%   |
| Corsair             | 11        | 6.11%   |
| A-DATA Technology   | 10        | 5.56%   |
| G.Skill             | 8         | 4.44%   |
| Elpida              | 4         | 2.22%   |
| Team                | 3         | 1.67%   |
| Unknown (ABCD)      | 2         | 1.11%   |
| Ramaxel Technology  | 2         | 1.11%   |
| Nanya Technology    | 2         | 1.11%   |
| Kllisre             | 2         | 1.11%   |
| V-Color             | 1         | 0.56%   |
| SMART Brazil        | 1         | 0.56%   |
| Smart               | 1         | 0.56%   |
| PNY                 | 1         | 0.56%   |
| GOODRAM             | 1         | 0.56%   |
| GeIL                | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.55%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 1.03%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 1.03%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.03%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.03%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 1.03%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 1.03%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s              | 2         | 1.03%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s           | 2         | 1.03%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 2         | 1.03%   |
| Crucial RAM CT8G4SFRA32A.C8FE 8GB SODIMM DDR4 3200MT/s           | 2         | 1.03%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.03%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s                 | 1         | 0.52%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.52%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                           | 1         | 0.52%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s       | 1         | 0.52%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.52%   |
| Unknown RAM Module 4GB DIMM 800MT/s                              | 1         | 0.52%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.52%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                       | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.52%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.52%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.52%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                       | 1         | 0.52%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                       | 1         | 0.52%   |
| Unknown RAM CMA5-4GA03BALA1B00 8GB SODIMM DDR3 1600MT/s          | 1         | 0.52%   |
| Unknown RAM 7EH64AA# 8GB DIMM DDR4 2667MT/s                      | 1         | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s   | 1         | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 1         | 0.52%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s               | 1         | 0.52%   |
| Team RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 0.52%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                       | 1         | 0.52%   |
| Smart RAM SH5641G8FJ8NWRNSQR 8GB SODIMM DDR3 1600MT/s            | 1         | 0.52%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.52%   |
| SK Hynix RAM S949A4UUH-ITR 16GB DIMM DDR4 2400MT/s               | 1         | 0.52%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.52%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.52%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.52%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s                       | 1         | 0.52%   |
| SK Hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 0.52%   |
| SK Hynix RAM Module 2GB Row Of Chips DDR3 1600MT/s               | 1         | 0.52%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.52%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT325U7CFR8A-H9 2GB DIMM DDR3 1333MT/s             | 1         | 0.52%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.52%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.52%   |
| SK Hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.52%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 0.52%   |
| SK Hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 83        | 54.97%  |
| DDR3    | 47        | 31.13%  |
| LPDDR3  | 7         | 4.64%   |
| LPDDR4  | 6         | 3.97%   |
| DDR2    | 4         | 2.65%   |
| Unknown | 3         | 1.99%   |
| SDRAM   | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 85        | 56.29%  |
| DIMM         | 52        | 34.44%  |
| Row Of Chips | 11        | 7.28%   |
| Chip         | 2         | 1.32%   |
| RIMM         | 1         | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 65        | 39.63%  |
| 4096  | 43        | 26.22%  |
| 16384 | 27        | 16.46%  |
| 2048  | 15        | 9.15%   |
| 32768 | 8         | 4.88%   |
| 1024  | 5         | 3.05%   |
| 65536 | 1         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 32        | 19.28%  |
| 2667    | 31        | 18.67%  |
| 3200    | 25        | 15.06%  |
| 2400    | 15        | 9.04%   |
| 2133    | 14        | 8.43%   |
| 1333    | 14        | 8.43%   |
| 1334    | 6         | 3.61%   |
| 3600    | 3         | 1.81%   |
| 1867    | 3         | 1.81%   |
| 4267    | 2         | 1.2%    |
| 3000    | 2         | 1.2%    |
| 2933    | 2         | 1.2%    |
| 1866    | 2         | 1.2%    |
| 800     | 2         | 1.2%    |
| 533     | 2         | 1.2%    |
| Unknown | 2         | 1.2%    |
| 4266    | 1         | 0.6%    |
| 3500    | 1         | 0.6%    |
| 3466    | 1         | 0.6%    |
| 3066    | 1         | 0.6%    |
| 2666    | 1         | 0.6%    |
| 2465    | 1         | 0.6%    |
| 1067    | 1         | 0.6%    |
| 1066    | 1         | 0.6%    |
| 667     | 1         | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 75%     |
| Samsung Electronics | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung ML-1660 Series | 1         | 25%     |
| HP LaserJet P1006      | 1         | 25%     |
| HP LaserJet M101-M106  | 1         | 25%     |
| HP LaserJet 1200       | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 18.92%  |
| IMC Networks                           | 15        | 13.51%  |
| Microdia                               | 14        | 12.61%  |
| Realtek Semiconductor                  | 9         | 8.11%   |
| Logitech                               | 9         | 8.11%   |
| Acer                                   | 9         | 8.11%   |
| Quanta                                 | 5         | 4.5%    |
| Lite-On Technology                     | 4         | 3.6%    |
| Sunplus Innovation Technology          | 3         | 2.7%    |
| Syntek                                 | 2         | 1.8%    |
| Suyin                                  | 2         | 1.8%    |
| Samsung Electronics                    | 2         | 1.8%    |
| Generalplus Technology                 | 2         | 1.8%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.8%    |
| Apple                                  | 2         | 1.8%    |
| Xiongmai                               | 1         | 0.9%    |
| Razer USA                              | 1         | 0.9%    |
| Huawei Technologies                    | 1         | 0.9%    |
| Hewlett-Packard                        | 1         | 0.9%    |
| eMPIA Technology                       | 1         | 0.9%    |
| DJKCVA19IE3NE8                         | 1         | 0.9%    |
| AVerMedia Technologies                 | 1         | 0.9%    |
| ARC International                      | 1         | 0.9%    |
| ALi                                    | 1         | 0.9%    |
| Alcor Micro                            | 1         | 0.9%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                 | 8         | 7.21%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 6         | 5.41%   |
| IMC Networks Integrated Camera                                | 6         | 5.41%   |
| Chicony Integrated Camera                                     | 6         | 5.41%   |
| Acer Integrated Camera                                        | 5         | 4.5%    |
| Chicony HP HD Camera                                          | 4         | 3.6%    |
| Realtek Integrated_Webcam_HD                                  | 3         | 2.7%    |
| Chicony HD WebCam                                             | 3         | 2.7%    |
| Samsung Galaxy series, misc. (MTP mode)                       | 2         | 1.8%    |
| Realtek EasyCamera                                            | 2         | 1.8%    |
| Quanta HD Webcam                                              | 2         | 1.8%    |
| Microdia USB Live camera                                      | 2         | 1.8%    |
| Microdia USB 2.0 Camera                                       | 2         | 1.8%    |
| Logitech HD Pro Webcam C920                                   | 2         | 1.8%    |
| Logitech C505 HD Webcam                                       | 2         | 1.8%    |
| Lite-On Integrated Camera                                     | 2         | 1.8%    |
| Chicony Lenovo EasyCamera                                     | 2         | 1.8%    |
| Chicony HP HD Webcam                                          | 2         | 1.8%    |
| Xiongmai web camera                                           | 1         | 0.9%    |
| Syntek USB 2.0 UVC PC Camera                                  | 1         | 0.9%    |
| Syntek Lenovo EasyCamera                                      | 1         | 0.9%    |
| Suyin HP TrueVision HD Integrated Webcam                      | 1         | 0.9%    |
| Suyin HP TrueVision Full HD                                   | 1         | 0.9%    |
| Sunplus Integrated_Webcam_HD                                  | 1         | 0.9%    |
| Sunplus Dell E5570 integrated webcam                          | 1         | 0.9%    |
| Sunplus 1.3M HD WebCam                                        | 1         | 0.9%    |
| Realtek Lenovo EasyCamera                                     | 1         | 0.9%    |
| Realtek Integrated Webcam                                     | 1         | 0.9%    |
| Realtek HD WebCam                                             | 1         | 0.9%    |
| Realtek Acer 640 x 480 laptop camera                          | 1         | 0.9%    |
| Razer USA Razer Kiyo                                          | 1         | 0.9%    |
| Quanta VGA WebCam                                             | 1         | 0.9%    |
| Quanta HP TrueVision HD Camera                                | 1         | 0.9%    |
| Quanta HP HD Camera                                           | 1         | 0.9%    |
| Microdia Laptop_Integrated_Webcam_E4HD                        | 1         | 0.9%    |
| Microdia Integrated Camera                                    | 1         | 0.9%    |
| Logitech Webcam C930e                                         | 1         | 0.9%    |
| Logitech Webcam C260                                          | 1         | 0.9%    |
| Logitech HD Webcam C615                                       | 1         | 0.9%    |
| Logitech CrystalCam                                           | 1         | 0.9%    |
| Logitech BRIO                                                 | 1         | 0.9%    |
| Lite-On HP HD Camera                                          | 1         | 0.9%    |
| Lite-On HP Full-HD Camera                                     | 1         | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                            | 1         | 0.9%    |
| IMC Networks USB2.0 HD IR UVC WebCam                          | 1         | 0.9%    |
| IMC Networks ov9734_azurewave_camera                          | 1         | 0.9%    |
| Huawei UVC Camera                                             | 1         | 0.9%    |
| HP Webcam 3110                                                | 1         | 0.9%    |
| Generalplus GENERAL WEBCAM                                    | 1         | 0.9%    |
| Generalplus 808 Camera #9 (web-cam mode)                      | 1         | 0.9%    |
| eMPIA M035 Compact Web Cam                                    | 1         | 0.9%    |
| DJKCVA19IE3NE8 HP TrueVision HD Camera                        | 1         | 0.9%    |
| Chicony USB2.0 HD UVC WebCam                                  | 1         | 0.9%    |
| Chicony ThinkPad T490 Webcam                                  | 1         | 0.9%    |
| Chicony Thinkpad T430 camera                                  | 1         | 0.9%    |
| Chicony FJ Camera                                             | 1         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 1         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD       | 1         | 0.9%    |
| AVerMedia Live Gamer Ultra-Video                              | 1         | 0.9%    |
| ARC International Camera                                      | 1         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 33.33%  |
| Validity Sensors           | 5         | 23.81%  |
| Shenzhen Goodix Technology | 5         | 23.81%  |
| Elan Microelectronics      | 3         | 14.29%  |
| AuthenTec                  | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 14.29%  |
| Elan ELAN:Fingerprint                                                      | 3         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 9.52%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 9.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 9.52%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 4.76%   |
| Unknown                                                                    | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 38.46%  |
| Alcor Micro           | 3         | 23.08%  |
| Upek                  | 2         | 15.38%  |
| Lenovo                | 2         | 15.38%  |
| Gemalto (was Gemplus) | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 3         | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 23.08%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 15.38%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 15.38%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom 5880                                                                | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 136       | 73.91%  |
| 1     | 33        | 17.93%  |
| 2     | 12        | 6.52%   |
| 5     | 2         | 1.09%   |
| 4     | 1         | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 33.87%  |
| Graphics card            | 12        | 19.35%  |
| Chipcard                 | 9         | 14.52%  |
| Multimedia controller    | 6         | 9.68%   |
| Net/wireless             | 5         | 8.06%   |
| Communication controller | 4         | 6.45%   |
| Unassigned class         | 3         | 4.84%   |
| Card reader              | 1         | 1.61%   |
| Bluetooth                | 1         | 1.61%   |

