Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI      | Modern 15 A11M              | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP       | Stream Notebook             | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Lenovo   | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Dell     | Inspiron 5402               | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| Lenovo   | ThinkPad T14 Gen 2i 20W0... | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo   | ThinkPad T14 Gen 2i 20W0... | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo   | ThinkPad X260 20F5S46R00    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| Gigabyte | AERO 15 KB                  | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| HP       | ProBook 640 G2              | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Dell     | XPS 13 9370                 | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo   | ThinkPad T420 4236WC3       | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo   | ThinkPad E14 20RB000UBR     | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP       | Laptop 15-ef1xxx            | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Lenovo   | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP       | EliteBook 820 G2            | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| Lenovo   | ThinkPad T430 2347FF9       | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP       | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer     | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Dell     | XPS 13 7390                 | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| Lenovo   | IdeaPad S145-14AST 81ST     | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| Apple    | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Lenovo   | IdeaPad 700-15ISK 80RU      | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo   | ThinkPad E595 20NF0005IX    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte | AERO 17-SA                  | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer     | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo   | IdeaPad S145-15IWL 81S9     | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| HP       | Laptop 15s-fq1xxx           | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| HP       | EliteBook 830 G7 Noteboo... | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo   | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell     | Precision 3540              | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec  | Infoway                     | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| Acer     | Aspire 7741                 | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer     | Aspire 7741                 | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X513... | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek  | ROG Strix G533QS_G533QS     | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo   | ThinkPad T430 2349V4B       | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP       | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Acer     | Aspire A315-23G             | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| Dell     | XPS 13 9380                 | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| Dell     | Latitude E6330              | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP       | Compaq 6830s                | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| HP       | Compaq 6830s                | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell     | Inspiron 5570               | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer     | Aspire A515-51              | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP       | ZBook Fury 17 G7 Mobile ... | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell     | Inspiron 5570               | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer     | Aspire A315-23G             | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer     | Aspire A315-23G             | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo   | ThinkPad X1 Extreme Gen ... | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Dell     | XPS 13 9310                 | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP       | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| HP       | ZBook 17 G5                 | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo   | IdeaPad Z580                | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell     | Inspiron 5570               | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell     | Inspiron 5570               | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer     | Aspire A315-23G             | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI   | BOHK-WAX9X                  | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI   | BOHK-WAX9X                  | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| HP       | ZBook Fury 17 G7 Mobile ... | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| Acer     | Nitro AN515-51              | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Dell     | Inspiron 3501               | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| MSI      | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo   | ThinkPad T495 20NKS0PG00    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| Dell     | Precision 3560              | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu  | LIFEBOOK A357               | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Lenovo   | IdeaPad 700-15ISK 80RU      | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo   | IdeaPad 700-15ISK 80RU      | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer     | Aspire A315-23G             | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell     | Latitude E7470              | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer     | Aspire 5750G                | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek  | ZenBook UX431DA_UM431DA     | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer     | Aspire A315-23G             | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| Lenovo   | ThinkPad X270 W10DG 20K5... | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer     | Aspire A315-23G             | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo   | ThinkPad X230 2325AZ8       | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo   | Yoga 300-11IBR 80M1         | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Acer     | Aspire ES1-132              | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| Acer     | Aspire A315-23G             | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Acer     | Aspire V3-331               | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY   | Y13G002S4EI                 | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek  | X550LD                      | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer     | Aspire V3-331               | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo   | ThinkPad X270 W10DG 20K5... | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X512... | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI   | BOHK-WAX9X                  | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Dell     | Latitude E7470              | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| Acer     | Aspire A315-23G             | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell     | Latitude E6330              | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo   | ThinkPad T430s 2356A89      | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| Acer     | Aspire ES1-132              | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| Acer     | Aspire A315-23G             | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell     | Inspiron 3793               | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek  | M3N                         | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek  | M3N                         | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| Lenovo   | IdeaPad 320-15IKB 80XL      | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI   | BOHK-WAX9X                  | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer     | Aspire A315-23G             | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP       | ProBook 640 G8 Notebook ... | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo   | ThinkPad T495 20NJCTO1WW    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Monster  | ABRA A5 V15.2               | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron | A15                         | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| HUAWEI   | BOHK-WAX9X                  | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| Acer     | Aspire A315-23G             | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP       | Compaq tc4400 (GE179UP#A... | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| Toshiba  | Satellite U800W             | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI      | U90/U100                    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI      | U90/U100                    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Lenovo   | ThinkPad X1 Carbon 6th 2... | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| MSI      | CX700                       | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Dell     | XPS 13 9310                 | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo   | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung  | 370E4K                      | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI      | CX700                       | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| Acer     | Aspire A315-23G             | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer     | Aspire A315-23G             | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20UDC... | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| HP       | EliteBook 840 G1            | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Acer     | Aspire A315-23G             | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell     | Latitude 7480               | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo   | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HUAWEI   | BOHK-WAX9X                  | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI   | BOHK-WAX9X                  | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Acer     | Aspire A315-23G             | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| HP       | Compaq Presario C700        | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer     | Aspire A315-23G             | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| HP       | Split 13 x2 PC              | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek  | ZenBook UX425IA_UM425IA     | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo   | IdeaPad Z500 20202          | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| ASUSTek  | ZenBook UX333FN_UX333FN     | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell     | Inspiron 3793               | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| HP       | EliteBook 8460p             | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo   | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell     | Inspiron 5468               | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Lenovo   | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo   | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-7-amd64             | 40        | 39.6%   |
| 5.10.0-8-amd64             | 22        | 21.78%  |
| 5.10.0-6-amd64             | 21        | 20.79%  |
| 5.12.10                    | 1         | 0.99%   |
| 5.12.1                     | 1         | 0.99%   |
| 5.12.0-9.2-liquorix-amd64  | 1         | 0.99%   |
| 5.12.0-14.2-liquorix-amd64 | 1         | 0.99%   |
| 5.11.9+                    | 1         | 0.99%   |
| 5.11.22-1-pve              | 1         | 0.99%   |
| 5.11.15-051115-generic     | 1         | 0.99%   |
| 5.11.14                    | 1         | 0.99%   |
| 5.11.0-rc6                 | 1         | 0.99%   |
| 5.10.40-ismynik            | 1         | 0.99%   |
| 5.10.0-io7-amd64           | 1         | 0.99%   |
| 5.10.0-6-rt-amd64          | 1         | 0.99%   |
| 5.10.0-6-686               | 1         | 0.99%   |
| 5.10.0-5-amd64             | 1         | 0.99%   |
| 4.19.181-z580322           | 1         | 0.99%   |
| 4.19.0-16-amd64            | 1         | 0.99%   |
| 4.19.0-16-686-pae          | 1         | 0.99%   |
| 4.19.0-14-amd64            | 1         | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 84        | 86.6%   |
| 4.19.0   | 3         | 3.09%   |
| 5.12.10  | 1         | 1.03%   |
| 5.12.1   | 1         | 1.03%   |
| 5.12.0   | 1         | 1.03%   |
| 5.11.9   | 1         | 1.03%   |
| 5.11.22  | 1         | 1.03%   |
| 5.11.15  | 1         | 1.03%   |
| 5.11.14  | 1         | 1.03%   |
| 5.11.0   | 1         | 1.03%   |
| 5.10.40  | 1         | 1.03%   |
| 4.19.181 | 1         | 1.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 85        | 87.63%  |
| 5.11    | 5         | 5.15%   |
| 4.19    | 4         | 4.12%   |
| 5.12    | 3         | 3.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 95        | 97.94%  |
| i686   | 2         | 2.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 26        | 26.8%   |
| KDE5             | 24        | 24.74%  |
| XFCE             | 9         | 9.28%   |
| MATE             | 7         | 7.22%   |
| Unknown          | 5         | 5.15%   |
| LXQt             | 4         | 4.12%   |
| i3               | 4         | 4.12%   |
| KDE              | 3         | 3.09%   |
| Cinnamon         | 3         | 3.09%   |
| X-Cinnamon       | 2         | 2.06%   |
| openbox          | 2         | 2.06%   |
| lightdm-xsession | 2         | 2.06%   |
| GNOME Flashback  | 2         | 2.06%   |
| sway             | 1         | 1.03%   |
| LXDE             | 1         | 1.03%   |
| default          | 1         | 1.03%   |
| awesome          | 1         | 1.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 69        | 69.7%   |
| Wayland | 22        | 22.22%  |
| Tty     | 6         | 6.06%   |
| Unknown | 2         | 2.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 27        | 27.84%  |
| SDDM    | 26        | 26.8%   |
| GDM     | 26        | 26.8%   |
| Unknown | 16        | 16.49%  |
| XDM     | 1         | 1.03%   |
| LightDM | 1         | 1.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 32        | 32.99%  |
| fr_FR   | 8         | 8.25%   |
| de_DE   | 7         | 7.22%   |
| ru_RU   | 6         | 6.19%   |
| pt_BR   | 5         | 5.15%   |
| es_ES   | 5         | 5.15%   |
| tr_TR   | 3         | 3.09%   |
| pl_PL   | 3         | 3.09%   |
| it_IT   | 3         | 3.09%   |
| en_IN   | 3         | 3.09%   |
| en_GB   | 3         | 3.09%   |
| pt_PT   | 2         | 2.06%   |
| de_CH   | 2         | 2.06%   |
| ru_UA   | 1         | 1.03%   |
| ro_RO   | 1         | 1.03%   |
| nl_BE   | 1         | 1.03%   |
| ja_JP   | 1         | 1.03%   |
| hu_HU   | 1         | 1.03%   |
| hr_HR   | 1         | 1.03%   |
| fi_FI   | 1         | 1.03%   |
| es_CO   | 1         | 1.03%   |
| en_HK   | 1         | 1.03%   |
| en_CA   | 1         | 1.03%   |
| en_AU   | 1         | 1.03%   |
| cs_CZ   | 1         | 1.03%   |
| ca_ES   | 1         | 1.03%   |
| C       | 1         | 1.03%   |
| Unknown | 1         | 1.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 69        | 71.13%  |
| BIOS | 28        | 28.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 86        | 88.66%  |
| Btrfs   | 5         | 5.15%   |
| Overlay | 3         | 3.09%   |
| Zfs     | 1         | 1.03%   |
| Xfs     | 1         | 1.03%   |
| Unknown | 1         | 1.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 71        | 73.2%   |
| MBR     | 15        | 15.46%  |
| Unknown | 11        | 11.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 82.47%  |
| Yes       | 17        | 17.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 69.07%  |
| Yes       | 30        | 30.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 30        | 30.93%  |
| Hewlett-Packard     | 18        | 18.56%  |
| Dell                | 16        | 16.49%  |
| ASUSTek Computer    | 9         | 9.28%   |
| Acer                | 9         | 9.28%   |
| MSI                 | 4         | 4.12%   |
| Gigabyte Technology | 2         | 2.06%   |
| UNOWHY              | 1         | 1.03%   |
| Toshiba             | 1         | 1.03%   |
| Samsung Electronics | 1         | 1.03%   |
| Pegatron            | 1         | 1.03%   |
| Monster             | 1         | 1.03%   |
| Itautec             | 1         | 1.03%   |
| HUAWEI              | 1         | 1.03%   |
| Fujitsu             | 1         | 1.03%   |
| Apple               | 1         | 1.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell XPS 13 9310                            | 2         | 2.06%   |
| Dell Inspiron 3793                          | 2         | 2.06%   |
| UNOWHY Y13G002S4EI                          | 1         | 1.03%   |
| Toshiba Satellite U800W                     | 1         | 1.03%   |
| Samsung 370E4K                              | 1         | 1.03%   |
| Pegatron A15                                | 1         | 1.03%   |
| MSI U90/U100                                | 1         | 1.03%   |
| MSI Modern 15 A11M                          | 1         | 1.03%   |
| MSI GF65 Thin 10UE                          | 1         | 1.03%   |
| MSI CX700                                   | 1         | 1.03%   |
| Monster ABRA A5 V15.2                       | 1         | 1.03%   |
| Lenovo Yoga 300-11IBR 80M1                  | 1         | 1.03%   |
| Lenovo ThinkPad X270 W10DG 20K5S41E00       | 1         | 1.03%   |
| Lenovo ThinkPad X260 20F5S46R00             | 1         | 1.03%   |
| Lenovo ThinkPad X260 20F5S0JF00             | 1         | 1.03%   |
| Lenovo ThinkPad X230 2325AZ8                | 1         | 1.03%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS | 1         | 1.03%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JRT    | 1         | 1.03%   |
| Lenovo ThinkPad T530 24296HG                | 1         | 1.03%   |
| Lenovo ThinkPad T495 20NKS0PG00             | 1         | 1.03%   |
| Lenovo ThinkPad T495 20NJCTO1WW             | 1         | 1.03%   |
| Lenovo ThinkPad T440p 20AWS4PN00            | 1         | 1.03%   |
| Lenovo ThinkPad T430s 2356A89               | 1         | 1.03%   |
| Lenovo ThinkPad T430s 23533KJ               | 1         | 1.03%   |
| Lenovo ThinkPad T430 2349V4B                | 1         | 1.03%   |
| Lenovo ThinkPad T430 2347FF9                | 1         | 1.03%   |
| Lenovo ThinkPad T420 4236WC3                | 1         | 1.03%   |
| Lenovo ThinkPad T14 Gen 2i 20W0CTO1WW       | 1         | 1.03%   |
| Lenovo ThinkPad T14 Gen 1 20UDCTO1WW        | 1         | 1.03%   |
| Lenovo ThinkPad Edge E540 20C600KCJP        | 1         | 1.03%   |
| Lenovo ThinkPad E595 20NF0005IX             | 1         | 1.03%   |
| Lenovo ThinkPad E15 Gen 2 20TD003MRT        | 1         | 1.03%   |
| Lenovo ThinkPad E14 20RB000UBR              | 1         | 1.03%   |
| Lenovo IdeaPad Z580                         | 1         | 1.03%   |
| Lenovo IdeaPad Z500 20202                   | 1         | 1.03%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 1.03%   |
| Lenovo IdeaPad S145-14AST 81ST              | 1         | 1.03%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.03%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 1         | 1.03%   |
| Lenovo IdeaPad 320-15IKB 80XL               | 1         | 1.03%   |
| Lenovo G50-80 80E5                          | 1         | 1.03%   |
| Itautec Infoway                             | 1         | 1.03%   |
| HUAWEI BOHK-WAX9X                           | 1         | 1.03%   |
| HP ZBook Fury 17 G7 Mobile Workstation      | 1         | 1.03%   |
| HP ZBook 17 G5                              | 1         | 1.03%   |
| HP Stream Notebook                          | 1         | 1.03%   |
| HP Split 13 x2 PC                           | 1         | 1.03%   |
| HP ProBook 640 G8 Notebook PC               | 1         | 1.03%   |
| HP ProBook 640 G3                           | 1         | 1.03%   |
| HP ProBook 640 G2                           | 1         | 1.03%   |
| HP Laptop 15s-fq1xxx                        | 1         | 1.03%   |
| HP Laptop 15-ef1xxx                         | 1         | 1.03%   |
| HP EliteBook 855 G7 Notebook PC             | 1         | 1.03%   |
| HP EliteBook 8460p                          | 1         | 1.03%   |
| HP EliteBook 840 G1                         | 1         | 1.03%   |
| HP EliteBook 830 G7 Notebook PC             | 1         | 1.03%   |
| HP EliteBook 820 G2                         | 1         | 1.03%   |
| HP Compaq tc4400 (GE179UP#ABA)              | 1         | 1.03%   |
| HP Compaq Presario C700                     | 1         | 1.03%   |
| HP Compaq 6830s                             | 1         | 1.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 21        | 21.65%  |
| Acer Aspire        | 8         | 8.25%   |
| Lenovo IdeaPad     | 7         | 7.22%   |
| Dell Inspiron      | 6         | 6.19%   |
| HP EliteBook       | 5         | 5.15%   |
| Dell XPS           | 5         | 5.15%   |
| HP ProBook         | 3         | 3.09%   |
| HP Compaq          | 3         | 3.09%   |
| Dell Latitude      | 3         | 3.09%   |
| ASUS ZenBook       | 3         | 3.09%   |
| ASUS VivoBook      | 3         | 3.09%   |
| HP ZBook           | 2         | 2.06%   |
| HP Laptop          | 2         | 2.06%   |
| Gigabyte AERO      | 2         | 2.06%   |
| Dell Precision     | 2         | 2.06%   |
| UNOWHY Y13G002S4EI | 1         | 1.03%   |
| Toshiba Satellite  | 1         | 1.03%   |
| Samsung 370E4K     | 1         | 1.03%   |
| Pegatron A15       | 1         | 1.03%   |
| MSI U90            | 1         | 1.03%   |
| MSI Modern         | 1         | 1.03%   |
| MSI GF65           | 1         | 1.03%   |
| MSI CX700          | 1         | 1.03%   |
| Monster ABRA       | 1         | 1.03%   |
| Lenovo Yoga        | 1         | 1.03%   |
| Lenovo G50-80      | 1         | 1.03%   |
| Itautec Infoway    | 1         | 1.03%   |
| HUAWEI BOHK-WAX9X  | 1         | 1.03%   |
| HP Stream          | 1         | 1.03%   |
| HP Split           | 1         | 1.03%   |
| HP 2000            | 1         | 1.03%   |
| Fujitsu LIFEBOOK   | 1         | 1.03%   |
| ASUS X550LD        | 1         | 1.03%   |
| ASUS ROG           | 1         | 1.03%   |
| ASUS M3N           | 1         | 1.03%   |
| Apple MacBookPro8  | 1         | 1.03%   |
| Acer Nitro         | 1         | 1.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 25        | 25.77%  |
| 2021 | 18        | 18.56%  |
| 2019 | 16        | 16.49%  |
| 2018 | 8         | 8.25%   |
| 2012 | 6         | 6.19%   |
| 2016 | 5         | 5.15%   |
| 2015 | 3         | 3.09%   |
| 2014 | 3         | 3.09%   |
| 2011 | 3         | 3.09%   |
| 2017 | 2         | 2.06%   |
| 2013 | 2         | 2.06%   |
| 2009 | 2         | 2.06%   |
| 2008 | 2         | 2.06%   |
| 2007 | 1         | 1.03%   |
| 2004 | 1         | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 97        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 79        | 80.61%  |
| Enabled  | 19        | 19.39%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 97        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 29        | 29.9%   |
| 4.01-8.0    | 24        | 24.74%  |
| 8.01-16.0   | 20        | 20.62%  |
| 32.01-64.0  | 6         | 6.19%   |
| 3.01-4.0    | 6         | 6.19%   |
| 1.01-2.0    | 6         | 6.19%   |
| 64.01-256.0 | 3         | 3.09%   |
| 2.01-3.0    | 2         | 2.06%   |
| 24.01-32.0  | 1         | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 26        | 25.74%  |
| 4.01-8.0   | 21        | 20.79%  |
| 1.01-2.0   | 21        | 20.79%  |
| 3.01-4.0   | 15        | 14.85%  |
| 0.51-1.0   | 8         | 7.92%   |
| 8.01-16.0  | 7         | 6.93%   |
| 0.01-0.5   | 2         | 1.98%   |
| 32.01-64.0 | 1         | 0.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 64.95%  |
| 2      | 29        | 29.9%   |
| 3      | 2         | 2.06%   |
| 0      | 2         | 2.06%   |
| 4      | 1         | 1.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 77        | 79.38%  |
| Yes       | 20        | 20.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 76.29%  |
| No        | 23        | 23.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 98.97%  |
| No        | 1         | 1.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 78.35%  |
| No        | 21        | 21.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| France      | 11        | 11.34%  |
| Russia      | 10        | 10.31%  |
| USA         | 9         | 9.28%   |
| Germany     | 9         | 9.28%   |
| Brazil      | 7         | 7.22%   |
| Spain       | 5         | 5.15%   |
| Poland      | 5         | 5.15%   |
| Ukraine     | 3         | 3.09%   |
| Turkey      | 3         | 3.09%   |
| Portugal    | 3         | 3.09%   |
| Italy       | 3         | 3.09%   |
| India       | 3         | 3.09%   |
| Canada      | 3         | 3.09%   |
| Switzerland | 2         | 2.06%   |
| Croatia     | 2         | 2.06%   |
| Thailand    | 1         | 1.03%   |
| Romania     | 1         | 1.03%   |
| Philippines | 1         | 1.03%   |
| Netherlands | 1         | 1.03%   |
| Mexico      | 1         | 1.03%   |
| Kazakhstan  | 1         | 1.03%   |
| Japan       | 1         | 1.03%   |
| Hungary     | 1         | 1.03%   |
| Greece      | 1         | 1.03%   |
| Finland     | 1         | 1.03%   |
| Denmark     | 1         | 1.03%   |
| Czechia     | 1         | 1.03%   |
| Colombia    | 1         | 1.03%   |
| China       | 1         | 1.03%   |
| Bulgaria    | 1         | 1.03%   |
| Belgium     | 1         | 1.03%   |
| Belarus     | 1         | 1.03%   |
| Australia   | 1         | 1.03%   |
| Argentina   | 1         | 1.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| St Petersburg        | 5         | 5.1%    |
| Paris                | 4         | 4.08%   |
| Bengaluru            | 3         | 3.06%   |
| Rio de Janeiro       | 2         | 2.04%   |
| Mesa                 | 2         | 2.04%   |
| Kyiv                 | 2         | 2.04%   |
| Ankara               | 2         | 2.04%   |
| Zaragoza             | 1         | 1.02%   |
| Zagreb               | 1         | 1.02%   |
| Waterloo             | 1         | 1.02%   |
| Warsaw               | 1         | 1.02%   |
| Waregem              | 1         | 1.02%   |
| Vitória             | 1         | 1.02%   |
| Utrecht              | 1         | 1.02%   |
| Turin                | 1         | 1.02%   |
| Toul                 | 1         | 1.02%   |
| Toronto              | 1         | 1.02%   |
| Sunnyvale            | 1         | 1.02%   |
| Srednyaya Akhtuba    | 1         | 1.02%   |
| Sofia                | 1         | 1.02%   |
| Shizuoka             | 1         | 1.02%   |
| Schleswig            | 1         | 1.02%   |
| Sarand               | 1         | 1.02%   |
| San Justo            | 1         | 1.02%   |
| Sagunto              | 1         | 1.02%   |
| Rottenburg           | 1         | 1.02%   |
| Reliquias            | 1         | 1.02%   |
| Regen                | 1         | 1.02%   |
| Ratiskovice          | 1         | 1.02%   |
| Pula                 | 1         | 1.02%   |
| Piracicaba           | 1         | 1.02%   |
| Perm                 | 1         | 1.02%   |
| Paderno Franciacorta | 1         | 1.02%   |
| Odessa               | 1         | 1.02%   |
| Nur-Sultan           | 1         | 1.02%   |
| Novo Hamburgo        | 1         | 1.02%   |
| Nova Porteirinha     | 1         | 1.02%   |
| Noblesville          | 1         | 1.02%   |
| New Westminster      | 1         | 1.02%   |
| Navalcarnero         | 1         | 1.02%   |
| Munich               | 1         | 1.02%   |
| Moscow               | 1         | 1.02%   |
| Montauban            | 1         | 1.02%   |
| Minneapolis          | 1         | 1.02%   |
| Meitingen            | 1         | 1.02%   |
| Mataró              | 1         | 1.02%   |
| Manchester           | 1         | 1.02%   |
| Madrid               | 1         | 1.02%   |
| Lucon                | 1         | 1.02%   |
| Loziska              | 1         | 1.02%   |
| Lodz                 | 1         | 1.02%   |
| Lisbon               | 1         | 1.02%   |
| Les Mees             | 1         | 1.02%   |
| Krakow               | 1         | 1.02%   |
| Katowice             | 1         | 1.02%   |
| Kassel               | 1         | 1.02%   |
| Ivanteyevka          | 1         | 1.02%   |
| Istanbul             | 1         | 1.02%   |
| Hrodna               | 1         | 1.02%   |
| Hombrechtikon        | 1         | 1.02%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 23     | 16.13%  |
| WDC                 | 16        | 21     | 12.9%   |
| Toshiba             | 11        | 11     | 8.87%   |
| Seagate             | 11        | 13     | 8.87%   |
| Kingston            | 8         | 10     | 6.45%   |
| Unknown             | 6         | 6      | 4.84%   |
| SK Hynix            | 6         | 6      | 4.84%   |
| Intel               | 5         | 5      | 4.03%   |
| Crucial             | 5         | 5      | 4.03%   |
| A-DATA Technology   | 5         | 7      | 4.03%   |
| Transcend           | 2         | 2      | 1.61%   |
| Micron Technology   | 2         | 2      | 1.61%   |
| LITEONIT            | 2         | 2      | 1.61%   |
| LITEON              | 2         | 2      | 1.61%   |
| JMicron             | 2         | 2      | 1.61%   |
| Intenso             | 2         | 2      | 1.61%   |
| Hitachi             | 2         | 2      | 1.61%   |
| HGST                | 2         | 2      | 1.61%   |
| China               | 2         | 2      | 1.61%   |
| ZTC                 | 1         | 1      | 0.81%   |
| XPG                 | 1         | 1      | 0.81%   |
| Union Memory        | 1         | 1      | 0.81%   |
| Silicon Motion      | 1         | 1      | 0.81%   |
| SanDisk             | 1         | 1      | 0.81%   |
| Phison              | 1         | 2      | 0.81%   |
| Patriot             | 1         | 1      | 0.81%   |
| Maxtor              | 1         | 1      | 0.81%   |
| LDLC                | 1         | 1      | 0.81%   |
| KIOXIA              | 1         | 1      | 0.81%   |
| Fujitsu             | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |
| AMD                 | 1         | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 2.33%   |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 2.33%   |
| Seagate ST2000LX001-1RG174 2TB          | 2         | 1.55%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 1.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 1.55%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.55%   |
| Kingston OM8PCP3512F-AI1 512GB          | 2         | 1.55%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 1.55%   |
| ZTC SM201-512G SSD                      | 1         | 0.78%   |
| XPG NVMe SSD Drive 1024GB               | 1         | 0.78%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.78%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.78%   |
| WDC WD5000BPVT-00HXZT3 500GB            | 1         | 0.78%   |
| WDC WD50 00LPCX-24VHA 500GB             | 1         | 0.78%   |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 0.78%   |
| WDC WD10SPZX-80Z10T2 1TB                | 1         | 0.78%   |
| WDC WD10SPZX-22Z10T0 1TB                | 1         | 0.78%   |
| WDC WD-WD3200BVVT-62A26Y080 320GB       | 1         | 0.78%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB    | 1         | 0.78%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 1         | 0.78%   |
| WDC PC SN530 SDBPNPZ-1T00-1006 1TB      | 1         | 0.78%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB    | 1         | 0.78%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB    | 1         | 0.78%   |
| Unknown SDW32G  32GB                    | 1         | 0.78%   |
| Unknown SD/MMC/MS PRO 32GB              | 1         | 0.78%   |
| Unknown SC32G  32GB                     | 1         | 0.78%   |
| Unknown DA4064  64GB                    | 1         | 0.78%   |
| Unknown BGND3R  32GB                    | 1         | 0.78%   |
| Unknown APPSD  272GB                    | 1         | 0.78%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD  | 1         | 0.78%   |
| Transcend TS128GMSA370 128GB SSD        | 1         | 0.78%   |
| Transcend TS120GSSD220S 120GB           | 1         | 0.78%   |
| Toshiba THNSFJ256GCSU 256GB SSD         | 1         | 0.78%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.78%   |
| Toshiba MQ04ABD200 2TB                  | 1         | 0.78%   |
| Toshiba MQ01ACF032 320GB                | 1         | 0.78%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.78%   |
| Toshiba MQ01ABD100V 1TB                 | 1         | 0.78%   |
| Toshiba KXG6AZNV1T02 1TB                | 1         | 0.78%   |
| Toshiba KXG60ZNV512G NVMe KIOXIA 512GB  | 1         | 0.78%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB | 1         | 0.78%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 0.78%   |
| Toshiba KBG30ZMT256G 256GB              | 1         | 0.78%   |
| SK Hynix PC711 NVMe 1TB                 | 1         | 0.78%   |
| SK Hynix PC401 NVMe 256GB               | 1         | 0.78%   |
| SK Hynix HFM512GDJTNG-8310A 512GB       | 1         | 0.78%   |
| SK Hynix HFM512GDHTNG-8710B 512GB       | 1         | 0.78%   |
| SK Hynix HFM256GDJTNG-8310A 256GB       | 1         | 0.78%   |
| SK Hynix HFM001TD3JX013N 1TB            | 1         | 0.78%   |
| Silicon Motion NVMe SSD Drive 512GB     | 1         | 0.78%   |
| Seagate USB 250GB                       | 1         | 0.78%   |
| Seagate ST9320325AS 320GB               | 1         | 0.78%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 0.78%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.78%   |
| Seagate BUP Portable 4TB                | 1         | 0.78%   |
| Seagate BarraCuda SSD ZA1000CM10002 1TB | 1         | 0.78%   |
| SanDisk SSD PLUS 240GB                  | 1         | 0.78%   |
| Samsung SSD SM841 2.5 7mm 128GB         | 1         | 0.78%   |
| Samsung SSD 970 EVO Plus 500GB          | 1         | 0.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 9         | 10     | 32.14%  |
| Seagate | 9         | 11     | 32.14%  |
| Toshiba | 5         | 5      | 17.86%  |
| Hitachi | 2         | 2      | 7.14%   |
| HGST    | 2         | 2      | 7.14%   |
| Fujitsu | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 11     | 18.18%  |
| Kingston            | 4         | 6      | 9.09%   |
| Crucial             | 4         | 4      | 9.09%   |
| Intel               | 3         | 3      | 6.82%   |
| WDC                 | 2         | 4      | 4.55%   |
| Transcend           | 2         | 2      | 4.55%   |
| LITEONIT            | 2         | 2      | 4.55%   |
| Intenso             | 2         | 2      | 4.55%   |
| China               | 2         | 2      | 4.55%   |
| A-DATA Technology   | 2         | 2      | 4.55%   |
| ZTC                 | 1         | 1      | 2.27%   |
| Union Memory        | 1         | 1      | 2.27%   |
| Toshiba             | 1         | 1      | 2.27%   |
| Seagate             | 1         | 1      | 2.27%   |
| SanDisk             | 1         | 1      | 2.27%   |
| Patriot             | 1         | 1      | 2.27%   |
| Micron Technology   | 1         | 1      | 2.27%   |
| Maxtor              | 1         | 1      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| LDLC                | 1         | 1      | 2.27%   |
| JMicron             | 1         | 1      | 2.27%   |
| Apple               | 1         | 1      | 2.27%   |
| AMD                 | 1         | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 40        | 49     | 34.78%  |
| SSD     | 39        | 51     | 33.91%  |
| HDD     | 28        | 31     | 24.35%  |
| MMC     | 5         | 5      | 4.35%   |
| Unknown | 3         | 3      | 2.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 77     | 51.85%  |
| NVMe | 40        | 49     | 37.04%  |
| SAS  | 7         | 8      | 6.48%   |
| MMC  | 5         | 5      | 4.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 56     | 62.5%   |
| 0.51-1.0   | 20        | 22     | 31.25%  |
| 1.01-2.0   | 3         | 3      | 4.69%   |
| 3.01-4.0   | 1         | 1      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 25        | 25.51%  |
| 101-250        | 22        | 22.45%  |
| 501-1000       | 17        | 17.35%  |
| 1001-2000      | 13        | 13.27%  |
| 51-100         | 7         | 7.14%   |
| 1-20           | 6         | 6.12%   |
| 21-50          | 5         | 5.1%    |
| Unknown        | 2         | 2.04%   |
| More than 3000 | 1         | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 26        | 26.26%  |
| 21-50     | 17        | 17.17%  |
| 101-250   | 16        | 16.16%  |
| 51-100    | 14        | 14.14%  |
| 251-500   | 12        | 12.12%  |
| 501-1000  | 8         | 8.08%   |
| 1001-2000 | 2         | 2.02%   |
| 0         | 2         | 2.02%   |
| Unknown   | 2         | 2.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                    | 1         | 1      | 9.09%   |
| Seagate ST2000LX001-1RG174 2TB               | 1         | 1      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 9.09%   |
| LITEONIT LMT-64M6M-HP 64GB SSD               | 1         | 1      | 9.09%   |
| Intel SSDSC2KW120H6 120GB                    | 1         | 1      | 9.09%   |
| Intel SSDSC2BF180A4H 180GB                   | 1         | 1      | 9.09%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 9.09%   |
| Hitachi HTS543212L9A300 120GB                | 1         | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 9.09%   |
| A-DATA Technology SU630 480GB SSD            | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 27.27%  |
| Intel               | 2         | 2      | 18.18%  |
| Hitachi             | 2         | 2      | 18.18%  |
| Samsung Electronics | 1         | 2      | 9.09%   |
| LITEONIT            | 1         | 1      | 9.09%   |
| HGST                | 1         | 1      | 9.09%   |
| A-DATA Technology   | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 50%     |
| Hitachi | 2         | 2      | 33.33%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 54.55%  |
| SSD  | 5         | 6      | 45.45%  |

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
| Works    | 74        | 100    | 71.84%  |
| Detected | 18        | 27     | 17.48%  |
| Malfunc  | 11        | 12     | 10.68%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 62        | 55.36%  |
| Samsung Electronics          | 12        | 10.71%  |
| AMD                          | 7         | 6.25%   |
| SK Hynix                     | 6         | 5.36%   |
| Sandisk                      | 6         | 5.36%   |
| Toshiba America Info Systems | 5         | 4.46%   |
| Kingston Technology Company  | 4         | 3.57%   |
| ADATA Technology             | 4         | 3.57%   |
| Silicon Motion               | 1         | 0.89%   |
| Phison Electronics           | 1         | 0.89%   |
| Micron/Crucial Technology    | 1         | 0.89%   |
| Micron Technology            | 1         | 0.89%   |
| Lite-On Technology           | 1         | 0.89%   |
| KIOXIA                       | 1         | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 8.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 7.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 7.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 6.78%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 5.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 4.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 3.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 2.54%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 2.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 2.54%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 2.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.54%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.54%   |
| SK Hynix NVMe SSD Controller                                                     | 2         | 1.69%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 1.69%   |
| Samsung NVMe Controller                                                          | 2         | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.69%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 1.69%   |
| ADATA Non-Volatile memory controller                                             | 2         | 1.69%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.85%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.85%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.85%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.85%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.85%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.85%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.85%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.85%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 0.85%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 0.85%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.85%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.85%   |
| Intel SSD 660P Series                                                            | 1         | 0.85%   |
| Intel SSD 600P Series                                                            | 1         | 0.85%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.85%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 57        | 50.89%  |
| NVMe | 40        | 35.71%  |
| RAID | 11        | 9.82%   |
| IDE  | 4         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 83        | 85.57%  |
| AMD    | 14        | 14.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz               | 5         | 5.15%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 4         | 4.12%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 4         | 4.12%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 3         | 3.09%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 3         | 3.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 3         | 3.09%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 3.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 2.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 2.06%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 2.06%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 2         | 2.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 2         | 2.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 2.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 2.06%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 2         | 2.06%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 2.06%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 2.06%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                | 1         | 1.03%   |
| Intel Pentium M processor 1600MHz               | 1         | 1.03%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 1         | 1.03%   |
| Intel Pentium CPU 4415U @ 2.30GHz               | 1         | 1.03%   |
| Intel Pentium 3556U @ 1.70GHz                   | 1         | 1.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.03%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 1.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 1.03%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 1.03%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 1.03%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 1.03%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 1         | 1.03%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 1.03%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 1         | 1.03%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 1.03%   |
| Intel Core i7-3612QM CPU @ 2.10GHz              | 1         | 1.03%   |
| Intel Core i7-3610QM CPU @ 2.30GHz              | 1         | 1.03%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 1         | 1.03%   |
| Intel Core i7-10875H CPU @ 2.30GHz              | 1         | 1.03%   |
| Intel Core i7-10850H CPU @ 2.70GHz              | 1         | 1.03%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 1         | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 1.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 1.03%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 1.03%   |
| Intel Core i5-4200Y CPU @ 1.40GHz               | 1         | 1.03%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 1.03%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 1         | 1.03%   |
| Intel Core i5-2540M CPU @ 2.60GHz               | 1         | 1.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 1.03%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 1         | 1.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 1         | 1.03%   |
| Intel Core i5 CPU M 460 @ 2.53GHz               | 1         | 1.03%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 1.03%   |
| Intel Core i3-2370M CPU @ 2.40GHz               | 1         | 1.03%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 1         | 1.03%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz            | 1         | 1.03%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz            | 1         | 1.03%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 1         | 1.03%   |
| Intel Celeron CPU N3450 @ 1.10GHz               | 1         | 1.03%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 1.03%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 1         | 1.03%   |
| Intel Celeron CPU B800 @ 1.50GHz                | 1         | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 29        | 29.9%   |
| Intel Core i7    | 28        | 28.87%  |
| Other            | 10        | 10.31%  |
| Intel Celeron    | 5         | 5.15%   |
| AMD Ryzen 5      | 5         | 5.15%   |
| AMD Ryzen 7 PRO  | 4         | 4.12%   |
| Intel Pentium    | 3         | 3.09%   |
| Intel Core i3    | 3         | 3.09%   |
| Intel Core 2 Duo | 2         | 2.06%   |
| AMD Ryzen 7      | 2         | 2.06%   |
| Intel Xeon       | 1         | 1.03%   |
| Intel Pentium M  | 1         | 1.03%   |
| Intel Core 2     | 1         | 1.03%   |
| Intel Atom       | 1         | 1.03%   |
| AMD Ryzen 9      | 1         | 1.03%   |
| AMD A12          | 1         | 1.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 41        | 42.27%  |
| 4      | 40        | 41.24%  |
| 6      | 7         | 7.22%   |
| 8      | 6         | 6.19%   |
| 1      | 3         | 3.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 97        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 81        | 83.51%  |
| 1      | 16        | 16.49%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 95        | 97.94%  |
| 32-bit         | 2         | 2.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 18.37%  |
| 0x806c1    | 9         | 9.18%   |
| 0x306a9    | 8         | 8.16%   |
| 0x206a7    | 6         | 6.12%   |
| 0x806e9    | 5         | 5.1%    |
| 0x906ea    | 4         | 4.08%   |
| 0x806ec    | 4         | 4.08%   |
| 0x806ea    | 4         | 4.08%   |
| 0x706e5    | 4         | 4.08%   |
| 0xa0652    | 3         | 3.06%   |
| 0x406e3    | 3         | 3.06%   |
| 0x40651    | 3         | 3.06%   |
| 0x306d4    | 3         | 3.06%   |
| 0x08600106 | 3         | 3.06%   |
| 0x08108109 | 3         | 3.06%   |
| 0x806eb    | 2         | 2.04%   |
| 0x506c9    | 2         | 2.04%   |
| 0x906e9    | 1         | 1.02%   |
| 0x6f6      | 1         | 1.02%   |
| 0x695      | 1         | 1.02%   |
| 0x406c4    | 1         | 1.02%   |
| 0x406c3    | 1         | 1.02%   |
| 0x306c3    | 1         | 1.02%   |
| 0x20655    | 1         | 1.02%   |
| 0x106c2    | 1         | 1.02%   |
| 0x1067a    | 1         | 1.02%   |
| 0x10661    | 1         | 1.02%   |
| 0x0a50000b | 1         | 1.02%   |
| 0x08108102 | 1         | 1.02%   |
| 0x06006705 | 1         | 1.02%   |
| 0x0600611a | 1         | 1.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 23        | 23.71%  |
| IvyBridge   | 11        | 11.34%  |
| TigerLake   | 9         | 9.28%   |
| Zen+        | 6         | 6.19%   |
| Skylake     | 6         | 6.19%   |
| SandyBridge | 6         | 6.19%   |
| Haswell     | 6         | 6.19%   |
| Zen 2       | 5         | 5.15%   |
| IceLake     | 4         | 4.12%   |
| CometLake   | 4         | 4.12%   |
| Core        | 3         | 3.09%   |
| Broadwell   | 3         | 3.09%   |
| Silvermont  | 2         | 2.06%   |
| Goldmont    | 2         | 2.06%   |
| Excavator   | 2         | 2.06%   |
| Zen 3       | 1         | 1.03%   |
| Westmere    | 1         | 1.03%   |
| Penryn      | 1         | 1.03%   |
| P6          | 1         | 1.03%   |
| Bonnell     | 1         | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 81        | 65.32%  |
| Nvidia | 23        | 18.55%  |
| AMD    | 20        | 16.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 8.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 6.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.62%   |
| AMD Picasso                                                                              | 6         | 4.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.85%   |
| Intel HD Graphics 620                                                                    | 5         | 3.85%   |
| AMD Renoir                                                                               | 5         | 3.85%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 3.08%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.31%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 2.31%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.54%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 2         | 1.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.54%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.54%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.54%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.77%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.77%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.77%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.77%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.77%   |
| Nvidia GP104GLM [Quadro P3200 Mobile]                                                    | 1         | 0.77%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.77%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.77%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.77%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 0.77%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.77%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 0.77%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.77%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.77%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 0.77%   |
| Intel HD Graphics 630                                                                    | 1         | 0.77%   |
| Intel HD Graphics 530                                                                    | 1         | 0.77%   |
| Intel HD Graphics 500                                                                    | 1         | 0.77%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 0.77%   |
| Intel Coffee Lake UHD Graphics P630                                                      | 1         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 0.77%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 0.77%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.77%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.77%   |
| AMD RV620/M82 [Mobility Radeon HD 3410/3430]                                             | 1         | 0.77%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 0.77%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                                         | 1         | 0.77%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 55.56%  |
| Intel + Nvidia | 22        | 22.22%  |
| 1 x AMD        | 13        | 13.13%  |
| Intel + AMD    | 4         | 4.04%   |
| 2 x AMD        | 2         | 2.02%   |
| Other          | 1         | 1.01%   |
| 1 x Nvidia     | 1         | 1.01%   |
| AMD + Nvidia   | 1         | 1.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 96        | 97.96%  |
| Unknown | 2         | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 84.69%  |
| 0.01-0.5   | 6         | 6.12%   |
| 1.01-2.0   | 4         | 4.08%   |
| 0.51-1.0   | 3         | 3.06%   |
| 5.01-6.0   | 1         | 1.02%   |
| 3.01-4.0   | 1         | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 29        | 26.13%  |
| BOE                 | 18        | 16.22%  |
| Chimei Innolux      | 15        | 13.51%  |
| LG Display          | 14        | 12.61%  |
| Samsung Electronics | 10        | 9.01%   |
| Sharp               | 6         | 5.41%   |
| Dell                | 3         | 2.7%    |
| Philips             | 2         | 1.8%    |
| Lenovo              | 2         | 1.8%    |
| Hewlett-Packard     | 2         | 1.8%    |
| CPT                 | 2         | 1.8%    |
| ___                 | 1         | 0.9%    |
| Unknown             | 1         | 0.9%    |
| PANDA               | 1         | 0.9%    |
| NCS                 | 1         | 0.9%    |
| JXG                 | 1         | 0.9%    |
| CSO                 | 1         | 0.9%    |
| Apple               | 1         | 0.9%    |
| AOC                 | 1         | 0.9%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 3         | 2.68%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                | 2         | 1.79%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch            | 2         | 1.79%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch           | 2         | 1.79%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                  | 2         | 1.79%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                   | 2         | 1.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 1.79%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch         | 2         | 1.79%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 1.79%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 2         | 1.79%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                     | 1         | 0.89%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                    | 1         | 0.89%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 0.89%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch                | 1         | 0.89%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                | 1         | 0.89%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch   | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x257mm 19.1-inch    | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch | 1         | 0.89%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch     | 1         | 0.89%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch    | 1         | 0.89%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1         | 0.89%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                     | 1         | 0.89%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 1         | 0.89%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                  | 1         | 0.89%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD0543 2560x1440 310x174mm 14.0-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD040B 1366x768 293x165mm 13.2-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD03C4 1366x768 345x194mm 15.6-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 1         | 0.89%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.89%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch               | 1         | 0.89%   |
| JXG NV156 JXG3840 3840x2160 880x510mm 40.0-inch                        | 1         | 0.89%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                      | 1         | 0.89%   |
| Dell P2419HC DELA11C 1920x1080 527x296mm 23.8-inch                     | 1         | 0.89%   |
| Dell 1909W DELA03D 1440x900 408x255mm 18.9-inch                        | 1         | 0.89%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                  | 1         | 0.89%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                   | 1         | 0.89%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                   | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch       | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch        | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch       | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch       | 1         | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 48        | 44.44%  |
| 1366x768 (WXGA)    | 28        | 25.93%  |
| 1600x900 (HD+)     | 8         | 7.41%   |
| 3840x2160 (4K)     | 5         | 4.63%   |
| 2560x1440 (QHD)    | 4         | 3.7%    |
| 1920x1200 (WUXGA)  | 4         | 3.7%    |
| 1280x800 (WXGA)    | 3         | 2.78%   |
| 1680x1050 (WSXGA+) | 2         | 1.85%   |
| 1440x900 (WXGA+)   | 2         | 1.85%   |
| 1792x768           | 1         | 0.93%   |
| 1280x1024 (SXGA)   | 1         | 0.93%   |
| 1024x768 (XGA)     | 1         | 0.93%   |
| 1024x600           | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 41        | 36.61%  |
| 13     | 21        | 18.75%  |
| 14     | 16        | 14.29%  |
| 12     | 7         | 6.25%   |
| 17     | 6         | 5.36%   |
| 24     | 4         | 3.57%   |
| 23     | 3         | 2.68%   |
| 11     | 3         | 2.68%   |
| 21     | 2         | 1.79%   |
| 19     | 2         | 1.79%   |
| 72     | 1         | 0.89%   |
| 47     | 1         | 0.89%   |
| 40     | 1         | 0.89%   |
| 33     | 1         | 0.89%   |
| 31     | 1         | 0.89%   |
| 25     | 1         | 0.89%   |
| 10     | 1         | 0.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 66        | 59.46%  |
| 201-300     | 23        | 20.72%  |
| 501-600     | 7         | 6.31%   |
| 401-500     | 5         | 4.5%    |
| 351-400     | 5         | 4.5%    |
| 801-900     | 1         | 0.9%    |
| 701-800     | 1         | 0.9%    |
| 601-700     | 1         | 0.9%    |
| 1501-2000   | 1         | 0.9%    |
| 1001-1500   | 1         | 0.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 87        | 85.29%  |
| 16/10 | 9         | 8.82%   |
| 4/3   | 2         | 1.96%   |
| 3/2   | 2         | 1.96%   |
| 5/4   | 1         | 0.98%   |
| 21/9  | 1         | 0.98%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 36.61%  |
| 81-90          | 25        | 22.32%  |
| 71-80          | 13        | 11.61%  |
| 201-250        | 7         | 6.25%   |
| 61-70          | 6         | 5.36%   |
| 121-130        | 5         | 4.46%   |
| 51-60          | 3         | 2.68%   |
| 251-300        | 3         | 2.68%   |
| 351-500        | 2         | 1.79%   |
| 151-200        | 2         | 1.79%   |
| 501-1000       | 2         | 1.79%   |
| More than 1000 | 1         | 0.89%   |
| 41-50          | 1         | 0.89%   |
| 141-150        | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 50.45%  |
| 101-120       | 24        | 21.62%  |
| 51-100        | 16        | 14.41%  |
| 161-240       | 9         | 8.11%   |
| More than 240 | 4         | 3.6%    |
| 1-50          | 2         | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 78        | 79.59%  |
| 2     | 17        | 17.35%  |
| 0     | 2         | 2.04%   |
| 3     | 1         | 1.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 61        | 41.22%  |
| Realtek Semiconductor             | 45        | 30.41%  |
| Qualcomm Atheros                  | 22        | 14.86%  |
| Broadcom                          | 4         | 2.7%    |
| Ralink                            | 2         | 1.35%   |
| Marvell Technology Group          | 2         | 1.35%   |
| Cypress Semiconductor             | 2         | 1.35%   |
| Broadcom Limited                  | 2         | 1.35%   |
| Xiaomi                            | 1         | 0.68%   |
| Qualcomm                          | 1         | 0.68%   |
| Microchip Technology              | 1         | 0.68%   |
| Huawei Technologies               | 1         | 0.68%   |
| Ericsson Business Mobile Networks | 1         | 0.68%   |
| Edimax Technology                 | 1         | 0.68%   |
| DisplayLink                       | 1         | 0.68%   |
| Dell                              | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 27        | 14.52%  |
| Intel Wi-Fi 6 AX200                                                     | 9         | 4.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 4.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 3.76%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 3.76%   |
| Intel Wireless 8260                                                     | 5         | 2.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 2.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.15%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.61%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.61%   |
| Intel Wireless 7265                                                     | 3         | 1.61%   |
| Intel Wireless 7260                                                     | 3         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 2         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.08%   |
| Intel Wireless 3160                                                     | 2         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                                    | 2         | 1.08%   |
| Intel Ethernet Connection (13) I219-V                                   | 2         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.08%   |
| Cypress K38231_03                                                       | 2         | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.54%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.54%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.54%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.54%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.54%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]             | 1         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.54%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)               | 1         | 0.54%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                 | 1         | 0.54%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 0.54%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.54%   |
| Intel Wireless Gigabit 17265                                            | 1         | 0.54%   |
| Intel Wireless 3165                                                     | 1         | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.54%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                         | 1         | 0.54%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.54%   |
| Intel Ethernet Connection I219-V                                        | 1         | 0.54%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 0.54%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                                   | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 60%     |
| Qualcomm Atheros      | 21        | 21%     |
| Realtek Semiconductor | 11        | 11%     |
| Broadcom              | 3         | 3%      |
| Ralink                | 2         | 2%      |
| Qualcomm              | 1         | 1%      |
| Edimax Technology     | 1         | 1%      |
| Broadcom Limited      | 1         | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 9         | 8.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 7.92%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 6.93%   |
| Intel Wireless 8260                                                     | 5         | 4.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 4.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 3.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.97%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.97%   |
| Intel Wireless 7265                                                     | 3         | 2.97%   |
| Intel Wireless 7260                                                     | 3         | 2.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 2.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.98%   |
| Intel Wireless 3160                                                     | 2         | 1.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.98%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.99%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.99%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.99%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.99%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.99%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]             | 1         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.99%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.99%   |
| Intel Wireless Gigabit 17265                                            | 1         | 0.99%   |
| Intel Wireless 3165                                                     | 1         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.99%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                         | 1         | 0.99%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.99%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.99%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 0.99%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 0.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 0.99%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.99%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 40        | 49.38%  |
| Intel                    | 27        | 33.33%  |
| Broadcom                 | 3         | 3.7%    |
| Qualcomm Atheros         | 2         | 2.47%   |
| Marvell Technology Group | 2         | 2.47%   |
| Cypress Semiconductor    | 2         | 2.47%   |
| Xiaomi                   | 1         | 1.23%   |
| Microchip Technology     | 1         | 1.23%   |
| Huawei Technologies      | 1         | 1.23%   |
| DisplayLink              | 1         | 1.23%   |
| Broadcom Limited         | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 32.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 10.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 8.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 4.88%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 4.88%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 2.44%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.44%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 2.44%   |
| Cypress K38231_03                                                 | 2         | 2.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.22%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 1.22%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.22%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.22%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.22%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.22%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.22%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.22%   |
| Intel 82801DB PRO/100 VM (MOB) Ethernet Controller                | 1         | 1.22%   |
| Huawei E353/E3131                                                 | 1         | 1.22%   |
| DisplayLink LAPDOCK                                               | 1         | 1.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.22%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express  | 1         | 1.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 96        | 55.49%  |
| Ethernet | 74        | 42.77%  |
| Modem    | 3         | 1.73%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 65.94%  |
| Ethernet | 47        | 34.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 64        | 65.98%  |
| 1     | 29        | 29.9%   |
| 3     | 4         | 4.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 74.49%  |
| Yes  | 25        | 25.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 54.55%  |
| Qualcomm Atheros Communications | 8         | 10.39%  |
| Realtek Semiconductor           | 6         | 7.79%   |
| Lite-On Technology              | 6         | 7.79%   |
| Broadcom                        | 4         | 5.19%   |
| Foxconn / Hon Hai               | 3         | 3.9%    |
| Cambridge Silicon Radio         | 2         | 2.6%    |
| Realtek                         | 1         | 1.3%    |
| Ralink                          | 1         | 1.3%    |
| IMC Networks                    | 1         | 1.3%    |
| Hewlett-Packard                 | 1         | 1.3%    |
| Dell                            | 1         | 1.3%    |
| Apple                           | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 19.48%  |
| Intel Bluetooth Device                              | 10        | 12.99%  |
| Intel AX200 Bluetooth                               | 9         | 11.69%  |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 7.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 7.79%   |
| Realtek Bluetooth Radio                             | 5         | 6.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 3.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 2.6%    |
| Lite-On Bluetooth Device                            | 2         | 2.6%    |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 2.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.6%    |
| Realtek RTL8723B Bluetooth                          | 1         | 1.3%    |
| Realtek Bluetooth Radio                             | 1         | 1.3%    |
| Ralink RT3290 Bluetooth                             | 1         | 1.3%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.3%    |
| IMC Networks Bluetooth Device                       | 1         | 1.3%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.3%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.3%    |
| Dell BCM20702A0                                     | 1         | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.3%    |
| Apple Bluetooth Host Controller                     | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 83        | 70.34%  |
| AMD                    | 15        | 12.71%  |
| Nvidia                 | 12        | 10.17%  |
| Texas Instruments      | 2         | 1.69%   |
| C-Media Electronics    | 2         | 1.69%   |
| Razer USA              | 1         | 0.85%   |
| Logitech               | 1         | 0.85%   |
| Generalplus Technology | 1         | 0.85%   |
| Creative Technology    | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 10.64%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 8.51%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 12        | 8.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 6.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 4.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 4.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 3.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 2.84%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 2.84%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.84%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 2.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.13%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.13%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.42%   |
| Razer USA Razer Thresher 7.1                                                                      | 1         | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.71%   |
| Nvidia Audio device                                                                               | 1         | 0.71%   |
| Logitech USB Headset                                                                              | 1         | 0.71%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.71%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.71%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.71%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.71%   |
| Creative Technology Sound Blaster Play! 3                                                         | 1         | 0.71%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 0.71%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.71%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.71%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 26        | 24.53%  |
| Samsung Electronics | 24        | 22.64%  |
| Micron Technology   | 11        | 10.38%  |
| Crucial             | 9         | 8.49%   |
| Kingston            | 8         | 7.55%   |
| A-DATA Technology   | 8         | 7.55%   |
| Unknown             | 5         | 4.72%   |
| Elpida              | 3         | 2.83%   |
| Ramaxel Technology  | 2         | 1.89%   |
| Nanya Technology    | 2         | 1.89%   |
| Unknown (ABCD)      | 1         | 0.94%   |
| Team                | 1         | 0.94%   |
| SMART Brazil        | 1         | 0.94%   |
| Smart               | 1         | 0.94%   |
| PNY                 | 1         | 0.94%   |
| Kllisre             | 1         | 0.94%   |
| GOODRAM             | 1         | 0.94%   |
| Corsair             | 1         | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 2.68%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 1.79%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.79%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.79%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 1.79%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 1.79%   |
| Crucial RAM CT8G4SFRA32A.C8FE 8GB SODIMM DDR4 3200MT/s           | 2         | 1.79%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.79%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.89%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                           | 1         | 0.89%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.89%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.89%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.89%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.89%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s   | 1         | 0.89%   |
| Team RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 0.89%   |
| Smart RAM SH5641G8FJ8NWRNSQR 8GB SODIMM DDR3 1600MT/s            | 1         | 0.89%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.89%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.89%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.89%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.89%   |
| SK Hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 0.89%   |
| SK Hynix RAM Module 2GB Row Of Chips DDR3 1600MT/s               | 1         | 0.89%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.89%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.89%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.89%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.89%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.89%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.89%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.89%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.89%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.89%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.89%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 0.89%   |
| SK Hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.89%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.89%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.89%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.89%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 1         | 0.89%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                     | 1         | 0.89%   |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.89%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.89%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.89%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.89%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.89%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.89%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 0.89%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.89%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 0.89%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.89%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 0.89%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB SODIMM LPDDR4 4266MT/s           | 1         | 0.89%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 0.89%   |
| PNY RAM Module 8GB SODIMM DDR3 1600MT/s                          | 1         | 0.89%   |
| Nanya RAM NT1GT64U8HB0BN-3C 1GB SODIMM DDR2 667MT/s              | 1         | 0.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 47        | 54.02%  |
| DDR3   | 25        | 28.74%  |
| LPDDR4 | 5         | 5.75%   |
| LPDDR3 | 5         | 5.75%   |
| DDR2   | 4         | 4.6%    |
| SDRAM  | 1         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 89.53%  |
| Row Of Chips | 9         | 10.47%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 36        | 38.3%   |
| 4096  | 28        | 29.79%  |
| 16384 | 12        | 12.77%  |
| 2048  | 9         | 9.57%   |
| 1024  | 5         | 5.32%   |
| 32768 | 4         | 4.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 23        | 24.73%  |
| 1600    | 18        | 19.35%  |
| 3200    | 15        | 16.13%  |
| 2133    | 11        | 11.83%  |
| 2400    | 8         | 8.6%    |
| 1334    | 6         | 6.45%   |
| 1333    | 4         | 4.3%    |
| 4267    | 2         | 2.15%   |
| 533     | 2         | 2.15%   |
| Unknown | 2         | 2.15%   |
| 4266    | 1         | 1.08%   |
| 667     | 1         | 1.08%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 25%     |
| IMC Networks                           | 14        | 16.67%  |
| Acer                                   | 9         | 10.71%  |
| Realtek Semiconductor                  | 8         | 9.52%   |
| Microdia                               | 8         | 9.52%   |
| Quanta                                 | 5         | 5.95%   |
| Sunplus Innovation Technology          | 3         | 3.57%   |
| Logitech                               | 3         | 3.57%   |
| Lite-On Technology                     | 3         | 3.57%   |
| Syntek                                 | 2         | 2.38%   |
| Suyin                                  | 2         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.38%   |
| DJKCVA19IE3NE8                         | 1         | 1.19%   |
| Apple                                  | 1         | 1.19%   |
| ALi                                    | 1         | 1.19%   |
| Alcor Micro                            | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                 | 7         | 8.33%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 6         | 7.14%   |
| Chicony Integrated Camera                                     | 6         | 7.14%   |
| IMC Networks Integrated Camera                                | 5         | 5.95%   |
| Acer Integrated Camera                                        | 5         | 5.95%   |
| Chicony HP HD Camera                                          | 4         | 4.76%   |
| Realtek Integrated_Webcam_HD                                  | 3         | 3.57%   |
| Chicony HD WebCam                                             | 3         | 3.57%   |
| Quanta HD Webcam                                              | 2         | 2.38%   |
| Logitech C505 HD Webcam                                       | 2         | 2.38%   |
| Lite-On Integrated Camera                                     | 2         | 2.38%   |
| Chicony Lenovo EasyCamera                                     | 2         | 2.38%   |
| Chicony HP HD Webcam                                          | 2         | 2.38%   |
| Syntek USB 2.0 UVC PC Camera                                  | 1         | 1.19%   |
| Syntek Lenovo EasyCamera                                      | 1         | 1.19%   |
| Suyin HP TrueVision HD Integrated Webcam                      | 1         | 1.19%   |
| Suyin HP TrueVision Full HD                                   | 1         | 1.19%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 1.19%   |
| Sunplus Dell E5570 integrated webcam                          | 1         | 1.19%   |
| Sunplus 1.3M HD WebCam                                        | 1         | 1.19%   |
| Realtek Lenovo EasyCamera                                     | 1         | 1.19%   |
| Realtek Integrated Webcam                                     | 1         | 1.19%   |
| Realtek HD WebCam                                             | 1         | 1.19%   |
| Realtek EasyCamera                                            | 1         | 1.19%   |
| Realtek Acer 640 x 480 laptop camera                          | 1         | 1.19%   |
| Quanta VGA WebCam                                             | 1         | 1.19%   |
| Quanta HP TrueVision HD Camera                                | 1         | 1.19%   |
| Quanta HP HD Camera                                           | 1         | 1.19%   |
| Microdia Laptop_Integrated_Webcam_E4HD                        | 1         | 1.19%   |
| Logitech Webcam C930e                                         | 1         | 1.19%   |
| Lite-On HP HD Camera                                          | 1         | 1.19%   |
| IMC Networks USB2.0 VGA UVC WebCam                            | 1         | 1.19%   |
| IMC Networks USB2.0 HD IR UVC WebCam                          | 1         | 1.19%   |
| IMC Networks ov9734_azurewave_camera                          | 1         | 1.19%   |
| DJKCVA19IE3NE8 HP TrueVision HD Camera                        | 1         | 1.19%   |
| Chicony USB2.0 HD UVC WebCam                                  | 1         | 1.19%   |
| Chicony ThinkPad T490 Webcam                                  | 1         | 1.19%   |
| Chicony Thinkpad T430 camera                                  | 1         | 1.19%   |
| Chicony FJ Camera                                             | 1         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 1         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD       | 1         | 1.19%   |
| Apple FaceTime HD Camera                                      | 1         | 1.19%   |
| ALi Gateway Webcam                                            | 1         | 1.19%   |
| Alcor Micro USB 2.0 Camera                                    | 1         | 1.19%   |
| Acer ThinkPad Integrated Camera                               | 1         | 1.19%   |
| Acer Lenovo EasyCamera                                        | 1         | 1.19%   |
| Acer HD Webcam                                                | 1         | 1.19%   |
| Acer EasyCamera                                               | 1         | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 31.58%  |
| Shenzhen Goodix Technology | 5         | 26.32%  |
| Validity Sensors           | 4         | 21.05%  |
| Elan Microelectronics      | 3         | 15.79%  |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 15.79%  |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 15.79%  |
| Elan ELAN:Fingerprint                                                      | 3         | 15.79%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 10.53%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 10.53%  |
| Shenzhen Goodix FingerPrint                                                | 2         | 10.53%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 5.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 36.36%  |
| Alcor Micro | 3         | 27.27%  |
| Upek        | 2         | 18.18%  |
| Lenovo      | 2         | 18.18%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 27.27%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 18.18%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 18.18%  |
| Broadcom 58200                                                               | 2         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 5880                                                                | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 63        | 63.64%  |
| 1     | 24        | 24.24%  |
| 2     | 11        | 11.11%  |
| 4     | 1         | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 39.58%  |
| Graphics card            | 10        | 20.83%  |
| Chipcard                 | 8         | 16.67%  |
| Net/wireless             | 4         | 8.33%   |
| Multimedia controller    | 3         | 6.25%   |
| Communication controller | 2         | 4.17%   |
| Card reader              | 1         | 2.08%   |
| Bluetooth                | 1         | 2.08%   |

