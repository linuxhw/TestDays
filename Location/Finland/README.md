Linux in Finland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Finland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Finland/Desktop/README.md) and [notebooks](/Location/Finland/Notebook/README.md).

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

Total: 2076

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ProBook 650 G1              | Notebook    | [593959e6f3](https://linux-hardware.org/?probe=593959e6f3) | Jun 30, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [a64b48a5a2](https://linux-hardware.org/?probe=a64b48a5a2) | Jun 29, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [42624c8bb1](https://linux-hardware.org/?probe=42624c8bb1) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| HP            | 250 G3                      | Notebook    | [90647a4b33](https://linux-hardware.org/?probe=90647a4b33) | Jun 28, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [3e5baaaa01](https://linux-hardware.org/?probe=3e5baaaa01) | Jun 27, 2023 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | Notebook    | [0defa5c92d](https://linux-hardware.org/?probe=0defa5c92d) | Jun 27, 2023 |
| Cisco         | WAVE-694-K9 A0              | Desktop     | [26b9c3adb7](https://linux-hardware.org/?probe=26b9c3adb7) | Jun 27, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [55179e2249](https://linux-hardware.org/?probe=55179e2249) | Jun 25, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2153f80362](https://linux-hardware.org/?probe=2153f80362) | Jun 25, 2023 |
| HP            | 872E                        | Mini pc     | [d59093e79e](https://linux-hardware.org/?probe=d59093e79e) | Jun 24, 2023 |
| Lenovo        | 00YJ434 SVT                 | Server      | [ba92d2c25b](https://linux-hardware.org/?probe=ba92d2c25b) | Jun 23, 2023 |
| Oracle        | ASM,MOTHERBOARD,1U          | Server      | [cb71d1574c](https://linux-hardware.org/?probe=cb71d1574c) | Jun 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4429a0f659](https://linux-hardware.org/?probe=4429a0f659) | Jun 23, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [7b33fc2cb8](https://linux-hardware.org/?probe=7b33fc2cb8) | Jun 23, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [017f0476b0](https://linux-hardware.org/?probe=017f0476b0) | Jun 21, 2023 |
| HP            | 1495                        | Desktop     | [9bdf95d92b](https://linux-hardware.org/?probe=9bdf95d92b) | Jun 21, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [4af402b7c9](https://linux-hardware.org/?probe=4af402b7c9) | Jun 21, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [4dca77df51](https://linux-hardware.org/?probe=4dca77df51) | Jun 21, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [ba4e83abed](https://linux-hardware.org/?probe=ba4e83abed) | Jun 20, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| Toshiba       | Satellite C850-1DV          | Notebook    | [eb574aab3b](https://linux-hardware.org/?probe=eb574aab3b) | Jun 19, 2023 |
| ASUSTek       | UX530UQ                     | Notebook    | [c952ec8390](https://linux-hardware.org/?probe=c952ec8390) | Jun 13, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [285303d1a0](https://linux-hardware.org/?probe=285303d1a0) | Jun 13, 2023 |
| Fujitsu       | LIFEBOOK A514               | Notebook    | [45b16c1cdf](https://linux-hardware.org/?probe=45b16c1cdf) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | Notebook    | [1da963b3f4](https://linux-hardware.org/?probe=1da963b3f4) | Jun 12, 2023 |
| HP            | 3398                        | Desktop     | [7523eb041f](https://linux-hardware.org/?probe=7523eb041f) | Jun 11, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [eab5787d6a](https://linux-hardware.org/?probe=eab5787d6a) | Jun 11, 2023 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [5affc12294](https://linux-hardware.org/?probe=5affc12294) | Jun 10, 2023 |
| ASUSTek       | UX530UQ                     | Notebook    | [71d0ddd2f0](https://linux-hardware.org/?probe=71d0ddd2f0) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| Gigabyte      | P2542                       | Notebook    | [12a2415432](https://linux-hardware.org/?probe=12a2415432) | Jun 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [281be42f34](https://linux-hardware.org/?probe=281be42f34) | Jun 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [f9b3588ff3](https://linux-hardware.org/?probe=f9b3588ff3) | Jun 07, 2023 |
| Lenovo        | ThinkPad T495 20NKS10K00    | Notebook    | [f205c52b8f](https://linux-hardware.org/?probe=f205c52b8f) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [16aa33fdfe](https://linux-hardware.org/?probe=16aa33fdfe) | Jun 06, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [a0430d6f0c](https://linux-hardware.org/?probe=a0430d6f0c) | Jun 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [9a1c9022af](https://linux-hardware.org/?probe=9a1c9022af) | Jun 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [4840dda2e3](https://linux-hardware.org/?probe=4840dda2e3) | Jun 04, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [7f95f275b3](https://linux-hardware.org/?probe=7f95f275b3) | Jun 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| Gigabyte      | P2542                       | Notebook    | [b1064cae7a](https://linux-hardware.org/?probe=b1064cae7a) | May 30, 2023 |
| Gigabyte      | P2542                       | Notebook    | [7cded000f2](https://linux-hardware.org/?probe=7cded000f2) | May 30, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [b1213efe40](https://linux-hardware.org/?probe=b1213efe40) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [88c6b12404](https://linux-hardware.org/?probe=88c6b12404) | May 27, 2023 |
| Acer          | Predator G3-605             | Desktop     | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [cb238efd5e](https://linux-hardware.org/?probe=cb238efd5e) | May 27, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [8472aba19b](https://linux-hardware.org/?probe=8472aba19b) | May 25, 2023 |
| ASRock        | 890GX Extreme3              | Desktop     | [016f2a8ada](https://linux-hardware.org/?probe=016f2a8ada) | May 24, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [a2a31dbbee](https://linux-hardware.org/?probe=a2a31dbbee) | May 24, 2023 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [a81e627367](https://linux-hardware.org/?probe=a81e627367) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [0197aaf79a](https://linux-hardware.org/?probe=0197aaf79a) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [bb39617225](https://linux-hardware.org/?probe=bb39617225) | May 23, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a4528c4521](https://linux-hardware.org/?probe=a4528c4521) | May 20, 2023 |
| MSI           | 2AE0                        | Desktop     | [5f47fbb9cb](https://linux-hardware.org/?probe=5f47fbb9cb) | May 19, 2023 |
| MSI           | 2AE0                        | Desktop     | [c14f84a498](https://linux-hardware.org/?probe=c14f84a498) | May 19, 2023 |
| ASRock        | X299 Taichi XE              | Desktop     | [deae8ee190](https://linux-hardware.org/?probe=deae8ee190) | May 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [f811501691](https://linux-hardware.org/?probe=f811501691) | May 18, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [7c6154717b](https://linux-hardware.org/?probe=7c6154717b) | May 18, 2023 |
| ASRock        | 890FX Deluxe4               | Desktop     | [c00eb20149](https://linux-hardware.org/?probe=c00eb20149) | May 18, 2023 |
| HP            | Stream Notebook PC 14       | Notebook    | [835c46e8e2](https://linux-hardware.org/?probe=835c46e8e2) | May 18, 2023 |
| Unknown       | Unknown                     | Soc         | [56541743e1](https://linux-hardware.org/?probe=56541743e1) | May 18, 2023 |
| Unknown       | Unknown                     | Soc         | [a7b33c758f](https://linux-hardware.org/?probe=a7b33c758f) | May 18, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [d1d5700b2c](https://linux-hardware.org/?probe=d1d5700b2c) | May 18, 2023 |
| Lenovo        | ThinkPad T400 276522G       | Notebook    | [dc8b38dd37](https://linux-hardware.org/?probe=dc8b38dd37) | May 17, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [2a93ec6ed8](https://linux-hardware.org/?probe=2a93ec6ed8) | May 17, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [de0485927b](https://linux-hardware.org/?probe=de0485927b) | May 17, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f5ef3c16c5](https://linux-hardware.org/?probe=f5ef3c16c5) | May 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b788039ba1](https://linux-hardware.org/?probe=b788039ba1) | May 15, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [2a50b288f8](https://linux-hardware.org/?probe=2a50b288f8) | May 15, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [dede8cf401](https://linux-hardware.org/?probe=dede8cf401) | May 14, 2023 |
| HP            | 1495                        | Desktop     | [6332ac9d68](https://linux-hardware.org/?probe=6332ac9d68) | May 14, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [9fd366eba6](https://linux-hardware.org/?probe=9fd366eba6) | May 14, 2023 |
| ASRock        | X299 Taichi                 | Desktop     | [59e43db209](https://linux-hardware.org/?probe=59e43db209) | May 14, 2023 |
| Acer          | Predator G3-605             | Desktop     | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Acer          | Predator G3-605             | Desktop     | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [713564ccd4](https://linux-hardware.org/?probe=713564ccd4) | May 12, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [33f3e64e8f](https://linux-hardware.org/?probe=33f3e64e8f) | May 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| HP            | 655                         | Notebook    | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Lenovo        | ThinkPad Edge E320 12988... | Notebook    | [5d3d3fb42e](https://linux-hardware.org/?probe=5d3d3fb42e) | May 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [66d8e4a703](https://linux-hardware.org/?probe=66d8e4a703) | May 02, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [a17449f761](https://linux-hardware.org/?probe=a17449f761) | May 02, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [3e42d222a0](https://linux-hardware.org/?probe=3e42d222a0) | May 02, 2023 |
| Dell          | Latitude 7370               | Notebook    | [c984360af7](https://linux-hardware.org/?probe=c984360af7) | May 02, 2023 |
| Dell          | Latitude 7370               | Notebook    | [295b50d5b2](https://linux-hardware.org/?probe=295b50d5b2) | May 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| ASRock        | 890FX Deluxe4               | Desktop     | [327a1a2b37](https://linux-hardware.org/?probe=327a1a2b37) | Apr 29, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e4718d8b12](https://linux-hardware.org/?probe=e4718d8b12) | Apr 29, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [0295ab04a7](https://linux-hardware.org/?probe=0295ab04a7) | Apr 28, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [1e7a947d41](https://linux-hardware.org/?probe=1e7a947d41) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | Notebook    | [9a7a15dae3](https://linux-hardware.org/?probe=9a7a15dae3) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | Notebook    | [754fc44526](https://linux-hardware.org/?probe=754fc44526) | Apr 27, 2023 |
| HP            | 3029h                       | Desktop     | [35be4d25c4](https://linux-hardware.org/?probe=35be4d25c4) | Apr 25, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | Notebook    | [379a1710e5](https://linux-hardware.org/?probe=379a1710e5) | Apr 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [962bffed9f](https://linux-hardware.org/?probe=962bffed9f) | Apr 25, 2023 |
| Dell          | Latitude 5420               | Notebook    | [8c1a7992c0](https://linux-hardware.org/?probe=8c1a7992c0) | Apr 25, 2023 |
| Lenovo        | ThinkPad A285 20MXS0NJ00    | Notebook    | [f155ad2bf4](https://linux-hardware.org/?probe=f155ad2bf4) | Apr 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [bc1dca3c78](https://linux-hardware.org/?probe=bc1dca3c78) | Apr 24, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7560923404](https://linux-hardware.org/?probe=7560923404) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4fad4d4a09](https://linux-hardware.org/?probe=4fad4d4a09) | Apr 21, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [6090be709d](https://linux-hardware.org/?probe=6090be709d) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | Notebook    | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | Notebook    | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [0ff08e0727](https://linux-hardware.org/?probe=0ff08e0727) | Apr 19, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [17eb54bee6](https://linux-hardware.org/?probe=17eb54bee6) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3ea28c33c9](https://linux-hardware.org/?probe=3ea28c33c9) | Apr 16, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | Desktop     | [e8b30a69f9](https://linux-hardware.org/?probe=e8b30a69f9) | Apr 16, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [e85b3e34b0](https://linux-hardware.org/?probe=e85b3e34b0) | Apr 16, 2023 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [6c711c5197](https://linux-hardware.org/?probe=6c711c5197) | Apr 15, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [984cf8fd47](https://linux-hardware.org/?probe=984cf8fd47) | Apr 14, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [5d37070bf0](https://linux-hardware.org/?probe=5d37070bf0) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [87acc1eb9d](https://linux-hardware.org/?probe=87acc1eb9d) | Apr 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9ce743560b](https://linux-hardware.org/?probe=9ce743560b) | Apr 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [91da873411](https://linux-hardware.org/?probe=91da873411) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c3eb775c80](https://linux-hardware.org/?probe=c3eb775c80) | Apr 13, 2023 |
| HP            | 1791                        | Desktop     | [c87bf6d0e1](https://linux-hardware.org/?probe=c87bf6d0e1) | Apr 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [654728e9fe](https://linux-hardware.org/?probe=654728e9fe) | Apr 13, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [33a7fad816](https://linux-hardware.org/?probe=33a7fad816) | Apr 13, 2023 |
| Dell          | Latitude E7440              | Notebook    | [4cfe81f687](https://linux-hardware.org/?probe=4cfe81f687) | Apr 12, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [408e2e47c1](https://linux-hardware.org/?probe=408e2e47c1) | Apr 12, 2023 |
| Lenovo        | ThinkPad L580 20LW000VMX    | Notebook    | [7b2e3794c9](https://linux-hardware.org/?probe=7b2e3794c9) | Apr 11, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [df2f924a6e](https://linux-hardware.org/?probe=df2f924a6e) | Apr 11, 2023 |
| Google        | Lindar rev3                 | Notebook    | [e6dd3f6805](https://linux-hardware.org/?probe=e6dd3f6805) | Apr 09, 2023 |
| Acer          | Enduro EUN314-51WG          | Notebook    | [7f73117dba](https://linux-hardware.org/?probe=7f73117dba) | Apr 09, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [375bb1794b](https://linux-hardware.org/?probe=375bb1794b) | Apr 08, 2023 |
| Lenovo        | ThinkPad T470s 20HF0001M... | Notebook    | [8c6105e5be](https://linux-hardware.org/?probe=8c6105e5be) | Apr 06, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a2a4936e2c](https://linux-hardware.org/?probe=a2a4936e2c) | Apr 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6ea31cc2ed](https://linux-hardware.org/?probe=6ea31cc2ed) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3569575b7c](https://linux-hardware.org/?probe=3569575b7c) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5881a47fd0](https://linux-hardware.org/?probe=5881a47fd0) | Apr 05, 2023 |
| HP            | 18E5                        | Desktop     | [71c68a2c6a](https://linux-hardware.org/?probe=71c68a2c6a) | Apr 05, 2023 |
| Lenovo        | ThinkPad T410 2537WB7       | Notebook    | [d68ffd9d0f](https://linux-hardware.org/?probe=d68ffd9d0f) | Apr 04, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [8c90ec7da1](https://linux-hardware.org/?probe=8c90ec7da1) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [cd18ce0a96](https://linux-hardware.org/?probe=cd18ce0a96) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0662f665d7](https://linux-hardware.org/?probe=0662f665d7) | Apr 03, 2023 |
| MSI           | GS66 Stealth 11UH           | Notebook    | [43a7d8f578](https://linux-hardware.org/?probe=43a7d8f578) | Apr 03, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [c9245a7032](https://linux-hardware.org/?probe=c9245a7032) | Apr 03, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [20e885eb0b](https://linux-hardware.org/?probe=20e885eb0b) | Apr 02, 2023 |
| HP            | 2AF3                        | Desktop     | [fe33aa7257](https://linux-hardware.org/?probe=fe33aa7257) | Apr 02, 2023 |
| HP            | 0A64h                       | Desktop     | [f4fd3904f0](https://linux-hardware.org/?probe=f4fd3904f0) | Mar 31, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [a025953f4c](https://linux-hardware.org/?probe=a025953f4c) | Mar 31, 2023 |
| Motion Com... | J3600                       | Notebook    | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| HP            | 0A64h                       | Desktop     | [9f50595e87](https://linux-hardware.org/?probe=9f50595e87) | Mar 30, 2023 |
| HP            | 18E7                        | Desktop     | [6b64a1639b](https://linux-hardware.org/?probe=6b64a1639b) | Mar 30, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [cec51b833f](https://linux-hardware.org/?probe=cec51b833f) | Mar 30, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [d237bcc0a2](https://linux-hardware.org/?probe=d237bcc0a2) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a1d2ac5e6e](https://linux-hardware.org/?probe=a1d2ac5e6e) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d74490158e](https://linux-hardware.org/?probe=d74490158e) | Mar 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7483952d78](https://linux-hardware.org/?probe=7483952d78) | Mar 29, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [042e72aea5](https://linux-hardware.org/?probe=042e72aea5) | Mar 28, 2023 |
| Lenovo        | IdeaPad S145-14IWL          | Notebook    | [91f36f67a4](https://linux-hardware.org/?probe=91f36f67a4) | Mar 28, 2023 |
| Dell          | Latitude E5250              | Notebook    | [7d9e678484](https://linux-hardware.org/?probe=7d9e678484) | Mar 27, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [3b9e638ecb](https://linux-hardware.org/?probe=3b9e638ecb) | Mar 26, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [f32cce4c6f](https://linux-hardware.org/?probe=f32cce4c6f) | Mar 26, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [95b0768bfc](https://linux-hardware.org/?probe=95b0768bfc) | Mar 25, 2023 |
| Acer          | Aspire C27-962              | All in one  | [d801e40f8c](https://linux-hardware.org/?probe=d801e40f8c) | Mar 25, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [9ab6fd4ae0](https://linux-hardware.org/?probe=9ab6fd4ae0) | Mar 25, 2023 |
| HP            | 8433 11                     | Desktop     | [1f76e1dc62](https://linux-hardware.org/?probe=1f76e1dc62) | Mar 25, 2023 |
| HP            | 0A64h                       | Desktop     | [c53db667a1](https://linux-hardware.org/?probe=c53db667a1) | Mar 24, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [d77c81e9e3](https://linux-hardware.org/?probe=d77c81e9e3) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0c824a1f88](https://linux-hardware.org/?probe=0c824a1f88) | Mar 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [f2fed76f66](https://linux-hardware.org/?probe=f2fed76f66) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6a57dfd8fc](https://linux-hardware.org/?probe=6a57dfd8fc) | Mar 23, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [8cf7b9cc76](https://linux-hardware.org/?probe=8cf7b9cc76) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aad036448d](https://linux-hardware.org/?probe=aad036448d) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7b899e790a](https://linux-hardware.org/?probe=7b899e790a) | Mar 22, 2023 |
| Dell          | Latitude E6430              | Notebook    | [7eafa653dc](https://linux-hardware.org/?probe=7eafa653dc) | Mar 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3fe3c818f7](https://linux-hardware.org/?probe=3fe3c818f7) | Mar 20, 2023 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [a76d46bf92](https://linux-hardware.org/?probe=a76d46bf92) | Mar 18, 2023 |
| HP            | 829E                        | Mini pc     | [b9e2d55bc9](https://linux-hardware.org/?probe=b9e2d55bc9) | Mar 18, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [8a2a9a9e75](https://linux-hardware.org/?probe=8a2a9a9e75) | Mar 18, 2023 |
| Dell          | Latitude E5470              | Notebook    | [6565aa43e3](https://linux-hardware.org/?probe=6565aa43e3) | Mar 18, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [c9ba614358](https://linux-hardware.org/?probe=c9ba614358) | Mar 18, 2023 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [93fd9dded3](https://linux-hardware.org/?probe=93fd9dded3) | Mar 17, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [f2b9853f35](https://linux-hardware.org/?probe=f2b9853f35) | Mar 16, 2023 |
| HP            | 805A                        | Desktop     | [fd97efb317](https://linux-hardware.org/?probe=fd97efb317) | Mar 16, 2023 |
| HP            | 8299                        | Desktop     | [59417ae66d](https://linux-hardware.org/?probe=59417ae66d) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [57f2de5da4](https://linux-hardware.org/?probe=57f2de5da4) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [2a316e6d03](https://linux-hardware.org/?probe=2a316e6d03) | Mar 16, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [c6aa050dd1](https://linux-hardware.org/?probe=c6aa050dd1) | Mar 16, 2023 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [976729abe2](https://linux-hardware.org/?probe=976729abe2) | Mar 16, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [ae9acbc4ef](https://linux-hardware.org/?probe=ae9acbc4ef) | Mar 15, 2023 |
| Lenovo        | Annapurna CRB 0B98401 WI... | Desktop     | [c4603a155e](https://linux-hardware.org/?probe=c4603a155e) | Mar 14, 2023 |
| ASUSTek       | P5KR                        | Desktop     | [613bbd6934](https://linux-hardware.org/?probe=613bbd6934) | Mar 14, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [e111e27012](https://linux-hardware.org/?probe=e111e27012) | Mar 13, 2023 |
| Dell          | Precision M4500             | Notebook    | [b61053a0de](https://linux-hardware.org/?probe=b61053a0de) | Mar 13, 2023 |
| MSI           | MPG Z490 GAMING CARBON W... | Desktop     | [a6c5296f86](https://linux-hardware.org/?probe=a6c5296f86) | Mar 12, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [a2b1839fd1](https://linux-hardware.org/?probe=a2b1839fd1) | Mar 11, 2023 |
| HP            | ZBook 17                    | Notebook    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| HP            | 8433 11                     | Desktop     | [51a4dbf83e](https://linux-hardware.org/?probe=51a4dbf83e) | Mar 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [c5950249eb](https://linux-hardware.org/?probe=c5950249eb) | Mar 11, 2023 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [7d5df3a3d7](https://linux-hardware.org/?probe=7d5df3a3d7) | Mar 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [ca937e17a7](https://linux-hardware.org/?probe=ca937e17a7) | Mar 10, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [5e2c4e9a1c](https://linux-hardware.org/?probe=5e2c4e9a1c) | Mar 09, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [fcb5d30135](https://linux-hardware.org/?probe=fcb5d30135) | Mar 09, 2023 |
| HP            | ZBook 17                    | Notebook    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [5a9c11da8a](https://linux-hardware.org/?probe=5a9c11da8a) | Mar 07, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [e24f683971](https://linux-hardware.org/?probe=e24f683971) | Mar 06, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [168b8db115](https://linux-hardware.org/?probe=168b8db115) | Mar 06, 2023 |
| MSI           | MS-6702E                    | Desktop     | [e17662e6c0](https://linux-hardware.org/?probe=e17662e6c0) | Mar 05, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [65aa79b0a3](https://linux-hardware.org/?probe=65aa79b0a3) | Mar 05, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [ab7448d0bf](https://linux-hardware.org/?probe=ab7448d0bf) | Mar 05, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [cadbbe841e](https://linux-hardware.org/?probe=cadbbe841e) | Mar 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b531e1a7a8](https://linux-hardware.org/?probe=b531e1a7a8) | Mar 04, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [1c2701a81c](https://linux-hardware.org/?probe=1c2701a81c) | Mar 04, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [c3d6a142c0](https://linux-hardware.org/?probe=c3d6a142c0) | Mar 04, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [d49f7315d3](https://linux-hardware.org/?probe=d49f7315d3) | Mar 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a04a4550d5](https://linux-hardware.org/?probe=a04a4550d5) | Mar 04, 2023 |
| Lenovo        | ThinkPad X240 20AMS2EH00    | Notebook    | [11d225cddb](https://linux-hardware.org/?probe=11d225cddb) | Mar 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [5ad0c4c383](https://linux-hardware.org/?probe=5ad0c4c383) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [62c37af17b](https://linux-hardware.org/?probe=62c37af17b) | Mar 03, 2023 |
| HP            | 8053                        | Desktop     | [c48153fe6d](https://linux-hardware.org/?probe=c48153fe6d) | Mar 02, 2023 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [cd58d8a863](https://linux-hardware.org/?probe=cd58d8a863) | Feb 28, 2023 |
| HP            | 18E7                        | Desktop     | [a4fb4affcf](https://linux-hardware.org/?probe=a4fb4affcf) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [4018e453c4](https://linux-hardware.org/?probe=4018e453c4) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [48725cdc4d](https://linux-hardware.org/?probe=48725cdc4d) | Feb 28, 2023 |
| ASUSTek       | B150M-C                     | Desktop     | [e675a40455](https://linux-hardware.org/?probe=e675a40455) | Feb 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | Notebook    | [db0d3b74bd](https://linux-hardware.org/?probe=db0d3b74bd) | Feb 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a758475e11](https://linux-hardware.org/?probe=a758475e11) | Feb 26, 2023 |
| HP            | ProBook 470 G1              | Notebook    | [8044704386](https://linux-hardware.org/?probe=8044704386) | Feb 26, 2023 |
| Lenovo        | ThinkPad L412 0585A38       | Notebook    | [da6493ef82](https://linux-hardware.org/?probe=da6493ef82) | Feb 25, 2023 |
| Alienware     | 15 R3                       | Notebook    | [72543030d5](https://linux-hardware.org/?probe=72543030d5) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| HP            | 8433 11                     | Desktop     | [881b062090](https://linux-hardware.org/?probe=881b062090) | Feb 24, 2023 |
| HP            | ProBook 4530s               | Notebook    | [305f79455e](https://linux-hardware.org/?probe=305f79455e) | Feb 24, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [9035e056b4](https://linux-hardware.org/?probe=9035e056b4) | Feb 24, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [cfff7e8c96](https://linux-hardware.org/?probe=cfff7e8c96) | Feb 24, 2023 |
| Dell          | Latitude D620               | Notebook    | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c34909b191](https://linux-hardware.org/?probe=c34909b191) | Feb 24, 2023 |
| ASUSTek       | X550LB                      | Notebook    | [736bb83bb8](https://linux-hardware.org/?probe=736bb83bb8) | Feb 23, 2023 |
| Dell          | Latitude E5470              | Notebook    | [12a8a55fca](https://linux-hardware.org/?probe=12a8a55fca) | Feb 23, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [fd4b8d6419](https://linux-hardware.org/?probe=fd4b8d6419) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ec6ab709e5](https://linux-hardware.org/?probe=ec6ab709e5) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1fd091bff9](https://linux-hardware.org/?probe=1fd091bff9) | Feb 21, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [50261acb6b](https://linux-hardware.org/?probe=50261acb6b) | Feb 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | Notebook    | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [32ed66a6f9](https://linux-hardware.org/?probe=32ed66a6f9) | Feb 20, 2023 |
| Acer          | Aspire 6530G                | Notebook    | [c1d73e8ceb](https://linux-hardware.org/?probe=c1d73e8ceb) | Feb 20, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [06c110e6f1](https://linux-hardware.org/?probe=06c110e6f1) | Feb 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [47e6250a37](https://linux-hardware.org/?probe=47e6250a37) | Feb 19, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d94b8cf0e0](https://linux-hardware.org/?probe=d94b8cf0e0) | Feb 18, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8fb0aec13d](https://linux-hardware.org/?probe=8fb0aec13d) | Feb 18, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [c67a2ae3c5](https://linux-hardware.org/?probe=c67a2ae3c5) | Feb 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| AOpen         | iBDWMt-WBOP R1.00H 55WB3... | Desktop     | [c524d923e6](https://linux-hardware.org/?probe=c524d923e6) | Feb 17, 2023 |
| ASUSTek       | K54C                        | Notebook    | [ea944628df](https://linux-hardware.org/?probe=ea944628df) | Feb 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [9f63fbafbe](https://linux-hardware.org/?probe=9f63fbafbe) | Feb 16, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [5065063fa1](https://linux-hardware.org/?probe=5065063fa1) | Feb 16, 2023 |
| HP            | 8433 11                     | Desktop     | [3f4ea738b6](https://linux-hardware.org/?probe=3f4ea738b6) | Feb 15, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [b5744eb259](https://linux-hardware.org/?probe=b5744eb259) | Feb 13, 2023 |
| Acer          | Predator G9-793             | Notebook    | [8c11736bf0](https://linux-hardware.org/?probe=8c11736bf0) | Feb 11, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [2a189f2497](https://linux-hardware.org/?probe=2a189f2497) | Feb 11, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [79204339d0](https://linux-hardware.org/?probe=79204339d0) | Feb 11, 2023 |
| HP            | 212B                        | Desktop     | [d3ac338cb9](https://linux-hardware.org/?probe=d3ac338cb9) | Feb 11, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [04929299d7](https://linux-hardware.org/?probe=04929299d7) | Feb 10, 2023 |
| HP            | 212B                        | Desktop     | [cc32aa2d27](https://linux-hardware.org/?probe=cc32aa2d27) | Feb 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8d2e488f38](https://linux-hardware.org/?probe=8d2e488f38) | Feb 09, 2023 |
| Dell          | Latitude E7440              | Notebook    | [ac0e96d86c](https://linux-hardware.org/?probe=ac0e96d86c) | Feb 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3af865ffdf](https://linux-hardware.org/?probe=3af865ffdf) | Feb 07, 2023 |
| Acer          | F690GVM                     | Desktop     | [8110fd6f99](https://linux-hardware.org/?probe=8110fd6f99) | Feb 07, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d9401dac6d](https://linux-hardware.org/?probe=d9401dac6d) | Feb 05, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [1445c60562](https://linux-hardware.org/?probe=1445c60562) | Feb 05, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [95ff55d958](https://linux-hardware.org/?probe=95ff55d958) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [a8fea59f32](https://linux-hardware.org/?probe=a8fea59f32) | Feb 04, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [c66fb39891](https://linux-hardware.org/?probe=c66fb39891) | Feb 04, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [67c2139481](https://linux-hardware.org/?probe=67c2139481) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [da7b0aca1f](https://linux-hardware.org/?probe=da7b0aca1f) | Feb 03, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [b6f1c93413](https://linux-hardware.org/?probe=b6f1c93413) | Feb 02, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| HP            | 872E                        | Mini pc     | [c73d160043](https://linux-hardware.org/?probe=c73d160043) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |
| MSI           | D2415 S26361-D2415-A21      | Desktop     | [3acfaaf14c](https://linux-hardware.org/?probe=3acfaaf14c) | Feb 01, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [3fc59532b8](https://linux-hardware.org/?probe=3fc59532b8) | Feb 01, 2023 |
| Dell          | Precision 5560              | Notebook    | [c994bfa3a7](https://linux-hardware.org/?probe=c994bfa3a7) | Jan 30, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a4ded61661](https://linux-hardware.org/?probe=a4ded61661) | Jan 27, 2023 |
| HP            | 805A                        | Desktop     | [b33510966e](https://linux-hardware.org/?probe=b33510966e) | Jan 27, 2023 |
| Lenovo        | ThinkPad R500 2718WA3       | Notebook    | [2bb86279a8](https://linux-hardware.org/?probe=2bb86279a8) | Jan 27, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [0065b33518](https://linux-hardware.org/?probe=0065b33518) | Jan 26, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [4dded574d3](https://linux-hardware.org/?probe=4dded574d3) | Jan 25, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [da185120e5](https://linux-hardware.org/?probe=da185120e5) | Jan 25, 2023 |
| Dell          | 0KRC95 A01                  | Desktop     | [9580da1eb5](https://linux-hardware.org/?probe=9580da1eb5) | Jan 25, 2023 |
| Fujitsu Si... | AMILO Notebook Xa 3530      | Notebook    | [e8384494a3](https://linux-hardware.org/?probe=e8384494a3) | Jan 25, 2023 |
| Lenovo        | ThinkPad T430s 2356GRG      | Notebook    | [cd81d567a2](https://linux-hardware.org/?probe=cd81d567a2) | Jan 24, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [08d8bb84c4](https://linux-hardware.org/?probe=08d8bb84c4) | Jan 24, 2023 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| HP            | Pavilion 17                 | Notebook    | [0ba46e91d2](https://linux-hardware.org/?probe=0ba46e91d2) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Acer          | Predator G9-591             | Notebook    | [0544a1b07c](https://linux-hardware.org/?probe=0544a1b07c) | Jan 21, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [287c632c93](https://linux-hardware.org/?probe=287c632c93) | Jan 21, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [83529ed276](https://linux-hardware.org/?probe=83529ed276) | Jan 20, 2023 |
| Lenovo        | ThinkPad E470 20H1004SMX    | Notebook    | [0d8528f0d2](https://linux-hardware.org/?probe=0d8528f0d2) | Jan 19, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [bd55cae677](https://linux-hardware.org/?probe=bd55cae677) | Jan 17, 2023 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [e24691c830](https://linux-hardware.org/?probe=e24691c830) | Jan 15, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a551d228f4](https://linux-hardware.org/?probe=a551d228f4) | Jan 14, 2023 |
| Dell          | Precision M4700             | Notebook    | [64bd9a7627](https://linux-hardware.org/?probe=64bd9a7627) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [fdf56c0639](https://linux-hardware.org/?probe=fdf56c0639) | Jan 13, 2023 |
| Acer          | Aspire 7730G                | Notebook    | [ba1e942da3](https://linux-hardware.org/?probe=ba1e942da3) | Jan 12, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [ae60044fa6](https://linux-hardware.org/?probe=ae60044fa6) | Jan 12, 2023 |
| HP            | 87D6 SMVB                   | Desktop     | [cf2b65f039](https://linux-hardware.org/?probe=cf2b65f039) | Jan 12, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [cc5b67471e](https://linux-hardware.org/?probe=cc5b67471e) | Jan 12, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | Notebook    | [7a2cdcb0ab](https://linux-hardware.org/?probe=7a2cdcb0ab) | Jan 12, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [791cd47247](https://linux-hardware.org/?probe=791cd47247) | Jan 12, 2023 |
| HP            | 3397                        | Desktop     | [0057e1b40e](https://linux-hardware.org/?probe=0057e1b40e) | Jan 11, 2023 |
| HP            | Unknown                     | Notebook    | [604bea5ac6](https://linux-hardware.org/?probe=604bea5ac6) | Jan 11, 2023 |
| Acer          | Predator G9-591             | Notebook    | [aa9794813e](https://linux-hardware.org/?probe=aa9794813e) | Jan 11, 2023 |
| ASRock        | Z87 Extreme6                | Desktop     | [49e3d87de4](https://linux-hardware.org/?probe=49e3d87de4) | Jan 11, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [333595c9de](https://linux-hardware.org/?probe=333595c9de) | Jan 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [ce911686b3](https://linux-hardware.org/?probe=ce911686b3) | Jan 10, 2023 |
| HP            | 255 G4                      | Notebook    | [1893637142](https://linux-hardware.org/?probe=1893637142) | Jan 10, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [19658b1d4e](https://linux-hardware.org/?probe=19658b1d4e) | Jan 10, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8f9cd3c097](https://linux-hardware.org/?probe=8f9cd3c097) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6e756926b8](https://linux-hardware.org/?probe=6e756926b8) | Jan 09, 2023 |
| HP            | 3646h                       | Desktop     | [9baf70c121](https://linux-hardware.org/?probe=9baf70c121) | Jan 08, 2023 |
| Foxconn       | ETON                        | Desktop     | [f30a00babb](https://linux-hardware.org/?probe=f30a00babb) | Jan 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [79551dad5b](https://linux-hardware.org/?probe=79551dad5b) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7142941d7c](https://linux-hardware.org/?probe=7142941d7c) | Jan 07, 2023 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [fa5bdcfc4c](https://linux-hardware.org/?probe=fa5bdcfc4c) | Jan 06, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [7a89ea18a0](https://linux-hardware.org/?probe=7a89ea18a0) | Jan 06, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [06ff3bed63](https://linux-hardware.org/?probe=06ff3bed63) | Jan 06, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [1396e4d561](https://linux-hardware.org/?probe=1396e4d561) | Jan 05, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [f88e88d88d](https://linux-hardware.org/?probe=f88e88d88d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [d89c5688d2](https://linux-hardware.org/?probe=d89c5688d2) | Jan 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [729d97d43a](https://linux-hardware.org/?probe=729d97d43a) | Jan 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [4b951f8c2a](https://linux-hardware.org/?probe=4b951f8c2a) | Jan 02, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [86b79bce9e](https://linux-hardware.org/?probe=86b79bce9e) | Jan 01, 2023 |
| Intel         | X79-SERVER V1.1             | Desktop     | [322b016537](https://linux-hardware.org/?probe=322b016537) | Jan 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [347dc56d43](https://linux-hardware.org/?probe=347dc56d43) | Dec 30, 2022 |
| HP            | 339A                        | Desktop     | [8e0b785427](https://linux-hardware.org/?probe=8e0b785427) | Dec 29, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [33fd3ed258](https://linux-hardware.org/?probe=33fd3ed258) | Dec 29, 2022 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [c1c0ab5824](https://linux-hardware.org/?probe=c1c0ab5824) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| MouseCompu... | BC-MB1485UD11A-191          | Convertible | [b24a434561](https://linux-hardware.org/?probe=b24a434561) | Dec 27, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [bef58a2317](https://linux-hardware.org/?probe=bef58a2317) | Dec 26, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [7a7d8227ee](https://linux-hardware.org/?probe=7a7d8227ee) | Dec 25, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | Notebook    | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [ad4be7f0fa](https://linux-hardware.org/?probe=ad4be7f0fa) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a70ba97a7a](https://linux-hardware.org/?probe=a70ba97a7a) | Dec 22, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [3d63d2fe51](https://linux-hardware.org/?probe=3d63d2fe51) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [3cfcfad4ba](https://linux-hardware.org/?probe=3cfcfad4ba) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7714ba77eb](https://linux-hardware.org/?probe=7714ba77eb) | Dec 21, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | Notebook    | [9e860431a0](https://linux-hardware.org/?probe=9e860431a0) | Dec 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8c140bbafc](https://linux-hardware.org/?probe=8c140bbafc) | Dec 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5981154034](https://linux-hardware.org/?probe=5981154034) | Dec 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0361b1083f](https://linux-hardware.org/?probe=0361b1083f) | Dec 20, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [262a879a99](https://linux-hardware.org/?probe=262a879a99) | Dec 19, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | Notebook    | [8e689417f3](https://linux-hardware.org/?probe=8e689417f3) | Dec 16, 2022 |
| HP            | 829E                        | Mini pc     | [dccdfac601](https://linux-hardware.org/?probe=dccdfac601) | Dec 15, 2022 |
| HP            | 829E                        | Mini pc     | [10b9e184e1](https://linux-hardware.org/?probe=10b9e184e1) | Dec 15, 2022 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | Notebook    | [bed7f6d44e](https://linux-hardware.org/?probe=bed7f6d44e) | Dec 14, 2022 |
| Lenovo        | ThinkPad Helix 2nd 20CG0... | Tablet      | [e32ae95f08](https://linux-hardware.org/?probe=e32ae95f08) | Dec 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [66b2e8e737](https://linux-hardware.org/?probe=66b2e8e737) | Dec 14, 2022 |
| Acer          | Predator G9-591             | Notebook    | [838b0e0f8c](https://linux-hardware.org/?probe=838b0e0f8c) | Dec 13, 2022 |
| Acer          | Aspire A315-43              | Notebook    | [6d77f1e173](https://linux-hardware.org/?probe=6d77f1e173) | Dec 13, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9787630f1c](https://linux-hardware.org/?probe=9787630f1c) | Dec 12, 2022 |
| ASUSTek       | H170-PRO                    | Desktop     | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [fa85be7b33](https://linux-hardware.org/?probe=fa85be7b33) | Dec 12, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [ab1dd22124](https://linux-hardware.org/?probe=ab1dd22124) | Dec 10, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c8890a2f74](https://linux-hardware.org/?probe=c8890a2f74) | Dec 09, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f1ac9526c5](https://linux-hardware.org/?probe=f1ac9526c5) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [fb93b5bdfa](https://linux-hardware.org/?probe=fb93b5bdfa) | Dec 06, 2022 |
| Acer          | Predator G9-591             | Notebook    | [6e8fe2e030](https://linux-hardware.org/?probe=6e8fe2e030) | Dec 06, 2022 |
| Dell          | Latitude E6440              | Notebook    | [425331326b](https://linux-hardware.org/?probe=425331326b) | Dec 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [19f5d58b52](https://linux-hardware.org/?probe=19f5d58b52) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [504a0286fb](https://linux-hardware.org/?probe=504a0286fb) | Dec 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [4a2e796be8](https://linux-hardware.org/?probe=4a2e796be8) | Dec 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [8de79673ea](https://linux-hardware.org/?probe=8de79673ea) | Dec 01, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [b840a0d02e](https://linux-hardware.org/?probe=b840a0d02e) | Dec 01, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e2f97abdea](https://linux-hardware.org/?probe=e2f97abdea) | Nov 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a42a4d6080](https://linux-hardware.org/?probe=a42a4d6080) | Nov 29, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [89e97c7099](https://linux-hardware.org/?probe=89e97c7099) | Nov 29, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [95b1694080](https://linux-hardware.org/?probe=95b1694080) | Nov 28, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [ae85dba67e](https://linux-hardware.org/?probe=ae85dba67e) | Nov 28, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [1e84d5c704](https://linux-hardware.org/?probe=1e84d5c704) | Nov 28, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [ccc431ef2e](https://linux-hardware.org/?probe=ccc431ef2e) | Nov 28, 2022 |
| HP            | 872E                        | Mini pc     | [9d8a2595d7](https://linux-hardware.org/?probe=9d8a2595d7) | Nov 27, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [028c06fcdc](https://linux-hardware.org/?probe=028c06fcdc) | Nov 27, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [05983f8566](https://linux-hardware.org/?probe=05983f8566) | Nov 26, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [1e016dcb9b](https://linux-hardware.org/?probe=1e016dcb9b) | Nov 26, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2813bdf250](https://linux-hardware.org/?probe=2813bdf250) | Nov 26, 2022 |
| HP            | 872E                        | Mini pc     | [c7ff015966](https://linux-hardware.org/?probe=c7ff015966) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ab6ce548bc](https://linux-hardware.org/?probe=ab6ce548bc) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| Dell          | Latitude 5410               | Notebook    | [1eeb98c3b0](https://linux-hardware.org/?probe=1eeb98c3b0) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| Dell          | Latitude 5410               | Notebook    | [a9b8b4208d](https://linux-hardware.org/?probe=a9b8b4208d) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [db9c9330b7](https://linux-hardware.org/?probe=db9c9330b7) | Nov 23, 2022 |
| ASUSTek       | PRIME Z690-P                | Notebook    | [436bd74a38](https://linux-hardware.org/?probe=436bd74a38) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [07d9dc965a](https://linux-hardware.org/?probe=07d9dc965a) | Nov 20, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [9484c00cb6](https://linux-hardware.org/?probe=9484c00cb6) | Nov 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [dd13c1df3f](https://linux-hardware.org/?probe=dd13c1df3f) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Intel         | D53427RKE G87971-406        | Desktop     | [e3bc504c6e](https://linux-hardware.org/?probe=e3bc504c6e) | Nov 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1472f0a14e](https://linux-hardware.org/?probe=1472f0a14e) | Nov 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [6a4c697203](https://linux-hardware.org/?probe=6a4c697203) | Nov 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [074c3a8b43](https://linux-hardware.org/?probe=074c3a8b43) | Nov 14, 2022 |
| HP            | Notebook                    | Notebook    | [b0d1cd283f](https://linux-hardware.org/?probe=b0d1cd283f) | Nov 14, 2022 |
| HP            | Notebook                    | Notebook    | [95ecccf4c7](https://linux-hardware.org/?probe=95ecccf4c7) | Nov 14, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [00db55919b](https://linux-hardware.org/?probe=00db55919b) | Nov 14, 2022 |
| HP            | 1998                        | Desktop     | [ddcba37929](https://linux-hardware.org/?probe=ddcba37929) | Nov 14, 2022 |
| HP            | 1998                        | Desktop     | [5249f1cdd7](https://linux-hardware.org/?probe=5249f1cdd7) | Nov 14, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2a6473f450](https://linux-hardware.org/?probe=2a6473f450) | Nov 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a0d94329a6](https://linux-hardware.org/?probe=a0d94329a6) | Nov 13, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [0d8609e1ed](https://linux-hardware.org/?probe=0d8609e1ed) | Nov 13, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [cee6d10d17](https://linux-hardware.org/?probe=cee6d10d17) | Nov 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9f0e94860c](https://linux-hardware.org/?probe=9f0e94860c) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [81f59ba6f5](https://linux-hardware.org/?probe=81f59ba6f5) | Nov 11, 2022 |
| HP            | 8054                        | Desktop     | [08a9a98d04](https://linux-hardware.org/?probe=08a9a98d04) | Nov 10, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3fe8b5fef3](https://linux-hardware.org/?probe=3fe8b5fef3) | Nov 10, 2022 |
| HP            | 8054                        | Desktop     | [4ce3ccc26d](https://linux-hardware.org/?probe=4ce3ccc26d) | Nov 09, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [dc9837cefc](https://linux-hardware.org/?probe=dc9837cefc) | Nov 09, 2022 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [9746d693c3](https://linux-hardware.org/?probe=9746d693c3) | Nov 08, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [6921f657bf](https://linux-hardware.org/?probe=6921f657bf) | Nov 07, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | Notebook    | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [0dab96ade2](https://linux-hardware.org/?probe=0dab96ade2) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [012705552d](https://linux-hardware.org/?probe=012705552d) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9af713ef6e](https://linux-hardware.org/?probe=9af713ef6e) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [dae32fcba7](https://linux-hardware.org/?probe=dae32fcba7) | Nov 04, 2022 |
| Acer          | Predator G9-591             | Notebook    | [ca65bba88a](https://linux-hardware.org/?probe=ca65bba88a) | Nov 03, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [4b9071c932](https://linux-hardware.org/?probe=4b9071c932) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| Dell          | Latitude E6330              | Notebook    | [51ded2feb1](https://linux-hardware.org/?probe=51ded2feb1) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [cbdfd56f05](https://linux-hardware.org/?probe=cbdfd56f05) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [031a5998a5](https://linux-hardware.org/?probe=031a5998a5) | Oct 30, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [e737f3b4bd](https://linux-hardware.org/?probe=e737f3b4bd) | Oct 29, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [34061efe0c](https://linux-hardware.org/?probe=34061efe0c) | Oct 25, 2022 |
| HP            | ZBook 15                    | Notebook    | [b2d2352668](https://linux-hardware.org/?probe=b2d2352668) | Oct 25, 2022 |
| HP            | 805A                        | Desktop     | [dbe3ff75e8](https://linux-hardware.org/?probe=dbe3ff75e8) | Oct 24, 2022 |
| Lenovo        | ThinkPad T470 20HES21434    | Notebook    | [39ff1846e3](https://linux-hardware.org/?probe=39ff1846e3) | Oct 23, 2022 |
| Fujitsu       | D2759 S26361-D2759-A13 W... | Server      | [c4c0b53877](https://linux-hardware.org/?probe=c4c0b53877) | Oct 23, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [9380dfc8b7](https://linux-hardware.org/?probe=9380dfc8b7) | Oct 23, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [59f7d0820f](https://linux-hardware.org/?probe=59f7d0820f) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [f81a40a71c](https://linux-hardware.org/?probe=f81a40a71c) | Oct 20, 2022 |
| Acer          | Aspire A315-33              | Notebook    | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [48d48d4c8e](https://linux-hardware.org/?probe=48d48d4c8e) | Oct 19, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7207f549c7](https://linux-hardware.org/?probe=7207f549c7) | Oct 18, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2495f40df9](https://linux-hardware.org/?probe=2495f40df9) | Oct 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ba8acdb280](https://linux-hardware.org/?probe=ba8acdb280) | Oct 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d18c649cb6](https://linux-hardware.org/?probe=d18c649cb6) | Oct 15, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [14891d8a26](https://linux-hardware.org/?probe=14891d8a26) | Oct 13, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [682dcf0b87](https://linux-hardware.org/?probe=682dcf0b87) | Oct 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f9dc4fff88](https://linux-hardware.org/?probe=f9dc4fff88) | Oct 12, 2022 |
| Alienware     | 15 R3                       | Notebook    | [bfdbf12cbb](https://linux-hardware.org/?probe=bfdbf12cbb) | Oct 11, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [60b02deb7f](https://linux-hardware.org/?probe=60b02deb7f) | Oct 11, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [703ab6caa2](https://linux-hardware.org/?probe=703ab6caa2) | Oct 10, 2022 |
| Acer          | Aspire A315-33              | Notebook    | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [29f7444a6e](https://linux-hardware.org/?probe=29f7444a6e) | Oct 10, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [49fff6123f](https://linux-hardware.org/?probe=49fff6123f) | Oct 10, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [0272592d8e](https://linux-hardware.org/?probe=0272592d8e) | Oct 08, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [05e6a5cb26](https://linux-hardware.org/?probe=05e6a5cb26) | Oct 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d2f6a610d9](https://linux-hardware.org/?probe=d2f6a610d9) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| Google        | Banon                       | Notebook    | [269a819905](https://linux-hardware.org/?probe=269a819905) | Oct 03, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [08a298f14e](https://linux-hardware.org/?probe=08a298f14e) | Oct 03, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [33cb2c0dce](https://linux-hardware.org/?probe=33cb2c0dce) | Oct 03, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [12486e4114](https://linux-hardware.org/?probe=12486e4114) | Oct 03, 2022 |
| Alienware     | 15 R3                       | Notebook    | [28e4e84fb1](https://linux-hardware.org/?probe=28e4e84fb1) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0c25e7e0a0](https://linux-hardware.org/?probe=0c25e7e0a0) | Oct 02, 2022 |
| Dell          | Latitude 5480               | Notebook    | [ec9593f051](https://linux-hardware.org/?probe=ec9593f051) | Oct 01, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [a64f339e70](https://linux-hardware.org/?probe=a64f339e70) | Sep 28, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [03ac8c5daa](https://linux-hardware.org/?probe=03ac8c5daa) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0f4b7501b3](https://linux-hardware.org/?probe=0f4b7501b3) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [d603e07087](https://linux-hardware.org/?probe=d603e07087) | Sep 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a2ebf20cd0](https://linux-hardware.org/?probe=a2ebf20cd0) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| HP            | 0AA0h                       | Desktop     | [5757039d29](https://linux-hardware.org/?probe=5757039d29) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e46ce42e90](https://linux-hardware.org/?probe=e46ce42e90) | Sep 20, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [b2a1aea8e2](https://linux-hardware.org/?probe=b2a1aea8e2) | Sep 17, 2022 |
| ZMY           | D1500 Ver.A                 | Server      | [a99d672930](https://linux-hardware.org/?probe=a99d672930) | Sep 15, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [337ccff161](https://linux-hardware.org/?probe=337ccff161) | Sep 15, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [e620df9580](https://linux-hardware.org/?probe=e620df9580) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6168b7089f](https://linux-hardware.org/?probe=6168b7089f) | Sep 11, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [4a00a1ca0b](https://linux-hardware.org/?probe=4a00a1ca0b) | Sep 10, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [bb1af3736f](https://linux-hardware.org/?probe=bb1af3736f) | Sep 10, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [40ad505314](https://linux-hardware.org/?probe=40ad505314) | Sep 10, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| Dell          | Latitude E6220              | Notebook    | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [3a599be2f2](https://linux-hardware.org/?probe=3a599be2f2) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| HP            | 805A                        | Desktop     | [477936d851](https://linux-hardware.org/?probe=477936d851) | Aug 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2fd4ef02b3](https://linux-hardware.org/?probe=2fd4ef02b3) | Aug 30, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [4b37519faf](https://linux-hardware.org/?probe=4b37519faf) | Aug 29, 2022 |
| HP            | 339A                        | Desktop     | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | Notebook    | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [a180ab604a](https://linux-hardware.org/?probe=a180ab604a) | Aug 26, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [6bcc6b550f](https://linux-hardware.org/?probe=6bcc6b550f) | Aug 24, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| Acer          | Predator G3620              | Desktop     | [b79ed7b47b](https://linux-hardware.org/?probe=b79ed7b47b) | Aug 23, 2022 |
| HP            | Compaq 6735s                | Notebook    | [4e52bb6ecb](https://linux-hardware.org/?probe=4e52bb6ecb) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1d0c242f30](https://linux-hardware.org/?probe=1d0c242f30) | Aug 23, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [1231c2fabe](https://linux-hardware.org/?probe=1231c2fabe) | Aug 23, 2022 |
| Acer          | Enduro EUN314-51WG          | Notebook    | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| ASRock        | Z75 Pro3                    | Desktop     | [4fbe3d2710](https://linux-hardware.org/?probe=4fbe3d2710) | Aug 22, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| Alienware     | 15 R3                       | Notebook    | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| Raspberry ... | Raspberry Pi Model B Plu... | Soc         | [7deff7707e](https://linux-hardware.org/?probe=7deff7707e) | Aug 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [8834646a81](https://linux-hardware.org/?probe=8834646a81) | Aug 19, 2022 |
| Acer          | Predator PO5-600s V:1.0     | Desktop     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [eaea01215e](https://linux-hardware.org/?probe=eaea01215e) | Aug 17, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [9d82dca288](https://linux-hardware.org/?probe=9d82dca288) | Aug 17, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | X501A1                      | Notebook    | [d021969767](https://linux-hardware.org/?probe=d021969767) | Aug 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [04f75d45cb](https://linux-hardware.org/?probe=04f75d45cb) | Aug 15, 2022 |
| Acer          | Aspire VN7-571G             | Notebook    | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a5ef05aaff](https://linux-hardware.org/?probe=a5ef05aaff) | Aug 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [bd608fb7bc](https://linux-hardware.org/?probe=bd608fb7bc) | Aug 13, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| HP            | 805A                        | Desktop     | [c7671a704a](https://linux-hardware.org/?probe=c7671a704a) | Aug 11, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ea9b6a4757](https://linux-hardware.org/?probe=ea9b6a4757) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [4e9256cf7f](https://linux-hardware.org/?probe=4e9256cf7f) | Aug 10, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [2539e9f908](https://linux-hardware.org/?probe=2539e9f908) | Aug 08, 2022 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| HP            | 1497                        | Desktop     | [2fe6cb5b2c](https://linux-hardware.org/?probe=2fe6cb5b2c) | Aug 07, 2022 |
| HP            | 1497                        | Desktop     | [24959f2c80](https://linux-hardware.org/?probe=24959f2c80) | Aug 07, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [0f1a9e4af2](https://linux-hardware.org/?probe=0f1a9e4af2) | Aug 06, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fa0a089121](https://linux-hardware.org/?probe=fa0a089121) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [a284074100](https://linux-hardware.org/?probe=a284074100) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [f14436327b](https://linux-hardware.org/?probe=f14436327b) | Aug 04, 2022 |
| HP            | Laptop 14-dg0xxx            | Notebook    | [365fe3e266](https://linux-hardware.org/?probe=365fe3e266) | Aug 03, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [da1731c1d2](https://linux-hardware.org/?probe=da1731c1d2) | Aug 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [d5e820b393](https://linux-hardware.org/?probe=d5e820b393) | Aug 03, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [2cea7378e8](https://linux-hardware.org/?probe=2cea7378e8) | Aug 03, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [09cd376e43](https://linux-hardware.org/?probe=09cd376e43) | Aug 02, 2022 |
| HP            | Compaq 2510p                | Notebook    | [b61ccedd14](https://linux-hardware.org/?probe=b61ccedd14) | Jul 31, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [8693dca4f6](https://linux-hardware.org/?probe=8693dca4f6) | Jul 30, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [dca4c898f8](https://linux-hardware.org/?probe=dca4c898f8) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ca37936b6f](https://linux-hardware.org/?probe=ca37936b6f) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| HP            | Laptop 14-dg0xxx            | Notebook    | [fa46d23eda](https://linux-hardware.org/?probe=fa46d23eda) | Jul 27, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [70ddacf43f](https://linux-hardware.org/?probe=70ddacf43f) | Jul 25, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1578510bc0](https://linux-hardware.org/?probe=1578510bc0) | Jul 25, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | Desktop     | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [b35dabeb45](https://linux-hardware.org/?probe=b35dabeb45) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [2625b243eb](https://linux-hardware.org/?probe=2625b243eb) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [25728e964b](https://linux-hardware.org/?probe=25728e964b) | Jul 20, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [9558ff01e9](https://linux-hardware.org/?probe=9558ff01e9) | Jul 20, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [e93d3eae0d](https://linux-hardware.org/?probe=e93d3eae0d) | Jul 20, 2022 |
| HP            | G62                         | Notebook    | [bc85466c3f](https://linux-hardware.org/?probe=bc85466c3f) | Jul 19, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [96c65556bb](https://linux-hardware.org/?probe=96c65556bb) | Jul 18, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [e540c6e30d](https://linux-hardware.org/?probe=e540c6e30d) | Jul 18, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [34ff1068ca](https://linux-hardware.org/?probe=34ff1068ca) | Jul 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [f4f2c80cdd](https://linux-hardware.org/?probe=f4f2c80cdd) | Jul 09, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [57517e2dc2](https://linux-hardware.org/?probe=57517e2dc2) | Jul 09, 2022 |
| Dell          | Precision 7560              | Notebook    | [3a5fc098c4](https://linux-hardware.org/?probe=3a5fc098c4) | Jul 08, 2022 |
| Dell          | 0GM819                      | Desktop     | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [a93792aef3](https://linux-hardware.org/?probe=a93792aef3) | Jul 07, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [9467db0d89](https://linux-hardware.org/?probe=9467db0d89) | Jul 06, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f525b5f3b0](https://linux-hardware.org/?probe=f525b5f3b0) | Jul 04, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | Notebook    | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [6904140540](https://linux-hardware.org/?probe=6904140540) | Jul 02, 2022 |
| HP            | 829E                        | Mini pc     | [91fee1441e](https://linux-hardware.org/?probe=91fee1441e) | Jul 01, 2022 |
| HP            | 3647h                       | Desktop     | [f59774eab5](https://linux-hardware.org/?probe=f59774eab5) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [abebd5c659](https://linux-hardware.org/?probe=abebd5c659) | Jun 30, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [8ecea7fce7](https://linux-hardware.org/?probe=8ecea7fce7) | Jun 28, 2022 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [c62062eac9](https://linux-hardware.org/?probe=c62062eac9) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| Medion        | AXA                         | All in one  | [0cbda6d693](https://linux-hardware.org/?probe=0cbda6d693) | Jun 23, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f0d321b741](https://linux-hardware.org/?probe=f0d321b741) | Jun 22, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | Notebook    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a69564b477](https://linux-hardware.org/?probe=a69564b477) | Jun 17, 2022 |
| Dell          | Latitude E7440              | Notebook    | [41acc5e2ba](https://linux-hardware.org/?probe=41acc5e2ba) | Jun 17, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [139ffc0039](https://linux-hardware.org/?probe=139ffc0039) | Jun 16, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f339cce523](https://linux-hardware.org/?probe=f339cce523) | Jun 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [36bf4dc378](https://linux-hardware.org/?probe=36bf4dc378) | Jun 13, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [d4bfcc2d6d](https://linux-hardware.org/?probe=d4bfcc2d6d) | Jun 12, 2022 |
| Dell          | 0RW203                      | Desktop     | [d53558bc85](https://linux-hardware.org/?probe=d53558bc85) | Jun 12, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d2861687ff](https://linux-hardware.org/?probe=d2861687ff) | Jun 12, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [f2351bb361](https://linux-hardware.org/?probe=f2351bb361) | Jun 11, 2022 |
| HP            | G62                         | Notebook    | [de2464c378](https://linux-hardware.org/?probe=de2464c378) | Jun 08, 2022 |
| HP            | Elite Dragonfly Max Note... | Convertible | [3b16bdeb2c](https://linux-hardware.org/?probe=3b16bdeb2c) | Jun 06, 2022 |
| Supermicro    | X10SBA-LA                   | Desktop     | [4b46c69e08](https://linux-hardware.org/?probe=4b46c69e08) | Jun 03, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [dff99aa7e6](https://linux-hardware.org/?probe=dff99aa7e6) | May 30, 2022 |
| HP            | 1998                        | Desktop     | [48be2e4a99](https://linux-hardware.org/?probe=48be2e4a99) | May 30, 2022 |
| HP            | 1998                        | Desktop     | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [6e41ef26bf](https://linux-hardware.org/?probe=6e41ef26bf) | May 29, 2022 |
| Unknown       | Unknown                     | Phone       | [63d3c9a3b6](https://linux-hardware.org/?probe=63d3c9a3b6) | May 28, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | Notebook    | [3a472b96d3](https://linux-hardware.org/?probe=3a472b96d3) | May 27, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | Notebook    | [7f3e3aada0](https://linux-hardware.org/?probe=7f3e3aada0) | May 27, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [9430147fab](https://linux-hardware.org/?probe=9430147fab) | May 27, 2022 |
| Dell          | Latitude 3520               | Notebook    | [6c5618416d](https://linux-hardware.org/?probe=6c5618416d) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | Notebook    | [018e2a8bff](https://linux-hardware.org/?probe=018e2a8bff) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | Notebook    | [6d4ab67cb8](https://linux-hardware.org/?probe=6d4ab67cb8) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 81X2          | Convertible | [df65cb7a9e](https://linux-hardware.org/?probe=df65cb7a9e) | May 26, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [1ca9184b98](https://linux-hardware.org/?probe=1ca9184b98) | May 22, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [ee04d8165a](https://linux-hardware.org/?probe=ee04d8165a) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [d52e9e2938](https://linux-hardware.org/?probe=d52e9e2938) | May 17, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [f06eee580b](https://linux-hardware.org/?probe=f06eee580b) | May 16, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [d2e3603431](https://linux-hardware.org/?probe=d2e3603431) | May 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [244be4f232](https://linux-hardware.org/?probe=244be4f232) | May 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [587c1deb4c](https://linux-hardware.org/?probe=587c1deb4c) | May 15, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [7cbd29cc48](https://linux-hardware.org/?probe=7cbd29cc48) | May 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2f3b6548d0](https://linux-hardware.org/?probe=2f3b6548d0) | May 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [826dfbee64](https://linux-hardware.org/?probe=826dfbee64) | May 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3fe223176c](https://linux-hardware.org/?probe=3fe223176c) | May 13, 2022 |
| Dell          | Latitude E6330              | Notebook    | [0065ab0681](https://linux-hardware.org/?probe=0065ab0681) | May 12, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [d94b81d9d3](https://linux-hardware.org/?probe=d94b81d9d3) | May 12, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0069680215](https://linux-hardware.org/?probe=0069680215) | May 10, 2022 |
| HP            | 805F                        | Desktop     | [466bb8cc36](https://linux-hardware.org/?probe=466bb8cc36) | May 10, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [65d7984ad4](https://linux-hardware.org/?probe=65d7984ad4) | May 09, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [b4ecefaba5](https://linux-hardware.org/?probe=b4ecefaba5) | May 09, 2022 |
| Acer          | RS780HVF                    | Desktop     | [431353b969](https://linux-hardware.org/?probe=431353b969) | May 09, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [df57c0ad60](https://linux-hardware.org/?probe=df57c0ad60) | May 09, 2022 |
| MSI           | Z87M GAMING                 | Desktop     | [7e95657ad7](https://linux-hardware.org/?probe=7e95657ad7) | May 08, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [abccbed349](https://linux-hardware.org/?probe=abccbed349) | May 08, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [537def711a](https://linux-hardware.org/?probe=537def711a) | May 08, 2022 |
| Acer          | RS780HVF                    | Desktop     | [1f30630929](https://linux-hardware.org/?probe=1f30630929) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [3cab505f0a](https://linux-hardware.org/?probe=3cab505f0a) | May 05, 2022 |
| Acer          | H57M01                      | Desktop     | [180132b3e1](https://linux-hardware.org/?probe=180132b3e1) | May 03, 2022 |
| Acer          | FX58M                       | Desktop     | [0a6673afb9](https://linux-hardware.org/?probe=0a6673afb9) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| HP            | 1589                        | Desktop     | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [39c9900546](https://linux-hardware.org/?probe=39c9900546) | May 01, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a90e6b2be7](https://linux-hardware.org/?probe=a90e6b2be7) | Apr 30, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0b23621ed1](https://linux-hardware.org/?probe=0b23621ed1) | Apr 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [c78066bc19](https://linux-hardware.org/?probe=c78066bc19) | Apr 29, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [2e84d98937](https://linux-hardware.org/?probe=2e84d98937) | Apr 29, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | Notebook    | [31bc958302](https://linux-hardware.org/?probe=31bc958302) | Apr 26, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | Notebook    | [8446691cb3](https://linux-hardware.org/?probe=8446691cb3) | Apr 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| Lenovo        | ThinkPad X230 2324GA7       | Notebook    | [a5138b511d](https://linux-hardware.org/?probe=a5138b511d) | Apr 25, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [f656f0d16f](https://linux-hardware.org/?probe=f656f0d16f) | Apr 24, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [1612f46137](https://linux-hardware.org/?probe=1612f46137) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e83ffcb04f](https://linux-hardware.org/?probe=e83ffcb04f) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [25e6181500](https://linux-hardware.org/?probe=25e6181500) | Apr 24, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [cd1bc2095f](https://linux-hardware.org/?probe=cd1bc2095f) | Apr 22, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [33afc70a54](https://linux-hardware.org/?probe=33afc70a54) | Apr 22, 2022 |
| Acer          | Aspire 7530G                | Notebook    | [710b429d94](https://linux-hardware.org/?probe=710b429d94) | Apr 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| ASRock        | Z87 Extreme6                | Desktop     | [d7e24821ee](https://linux-hardware.org/?probe=d7e24821ee) | Apr 18, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [5a93c8e68c](https://linux-hardware.org/?probe=5a93c8e68c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T480 20L6S93F00    | Notebook    | [b8c57e6b8a](https://linux-hardware.org/?probe=b8c57e6b8a) | Apr 14, 2022 |
| MSI           | Indio                       | Desktop     | [ca3a24d84d](https://linux-hardware.org/?probe=ca3a24d84d) | Apr 13, 2022 |
| HP            | Notebook                    | Notebook    | [24faf4835d](https://linux-hardware.org/?probe=24faf4835d) | Apr 10, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [1a910e93c5](https://linux-hardware.org/?probe=1a910e93c5) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [2d350f40d2](https://linux-hardware.org/?probe=2d350f40d2) | Apr 09, 2022 |
| Acer          | Batman A01                  | Desktop     | [a102f85d9d](https://linux-hardware.org/?probe=a102f85d9d) | Apr 08, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [1a1c86083e](https://linux-hardware.org/?probe=1a1c86083e) | Apr 07, 2022 |
| HP            | 18E7                        | Desktop     | [35dbcc5737](https://linux-hardware.org/?probe=35dbcc5737) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | B150M-K                     | Desktop     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASRock        | B85M-ITX                    | Desktop     | [1a2849588f](https://linux-hardware.org/?probe=1a2849588f) | Apr 01, 2022 |
| HP            | 3047h                       | Desktop     | [356fac6a3a](https://linux-hardware.org/?probe=356fac6a3a) | Apr 01, 2022 |
| HP            | 3047h                       | Desktop     | [d4c9852b3c](https://linux-hardware.org/?probe=d4c9852b3c) | Apr 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [07efb6a561](https://linux-hardware.org/?probe=07efb6a561) | Apr 01, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Dell          | Latitude 5480               | Notebook    | [2d431aae25](https://linux-hardware.org/?probe=2d431aae25) | Mar 29, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [79c9d66395](https://linux-hardware.org/?probe=79c9d66395) | Mar 26, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| Lenovo        | ThinkPad X230 2325BN8       | Notebook    | [3ad2d0f3ee](https://linux-hardware.org/?probe=3ad2d0f3ee) | Mar 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | Notebook    | [d5b5eeffc8](https://linux-hardware.org/?probe=d5b5eeffc8) | Mar 25, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [7b835e9a57](https://linux-hardware.org/?probe=7b835e9a57) | Mar 23, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [069ce018ad](https://linux-hardware.org/?probe=069ce018ad) | Mar 22, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | Notebook    | [bf87e829d7](https://linux-hardware.org/?probe=bf87e829d7) | Mar 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [78ae0419a3](https://linux-hardware.org/?probe=78ae0419a3) | Mar 14, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ba2686174e](https://linux-hardware.org/?probe=ba2686174e) | Mar 13, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6b32e0c788](https://linux-hardware.org/?probe=6b32e0c788) | Mar 10, 2022 |
| Acer          | AO725                       | Notebook    | [70febdd28f](https://linux-hardware.org/?probe=70febdd28f) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | Notebook    | [0f20b300ec](https://linux-hardware.org/?probe=0f20b300ec) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| HP            | G62                         | Notebook    | [67bc301ee6](https://linux-hardware.org/?probe=67bc301ee6) | Mar 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f351d9839b](https://linux-hardware.org/?probe=f351d9839b) | Mar 09, 2022 |
| Acer          | FX58M                       | Desktop     | [7404e9534e](https://linux-hardware.org/?probe=7404e9534e) | Mar 09, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [2142681934](https://linux-hardware.org/?probe=2142681934) | Mar 06, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [456b0dd391](https://linux-hardware.org/?probe=456b0dd391) | Mar 06, 2022 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [2e19b36624](https://linux-hardware.org/?probe=2e19b36624) | Mar 03, 2022 |
| Lenovo        | ThinkPad 13 20GJ0048MS      | Notebook    | [6590a539cf](https://linux-hardware.org/?probe=6590a539cf) | Mar 02, 2022 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [ea68b8ed21](https://linux-hardware.org/?probe=ea68b8ed21) | Mar 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0278765ef8](https://linux-hardware.org/?probe=0278765ef8) | Feb 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c08be74242](https://linux-hardware.org/?probe=c08be74242) | Feb 27, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [0dd55e5b26](https://linux-hardware.org/?probe=0dd55e5b26) | Feb 26, 2022 |
| ABIT          | IP35                        | Desktop     | [278dd592cc](https://linux-hardware.org/?probe=278dd592cc) | Feb 26, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [cfdffcf6ab](https://linux-hardware.org/?probe=cfdffcf6ab) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [02ac351573](https://linux-hardware.org/?probe=02ac351573) | Feb 25, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [f12d1e47df](https://linux-hardware.org/?probe=f12d1e47df) | Feb 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [fa5d4846df](https://linux-hardware.org/?probe=fa5d4846df) | Feb 23, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [5fe85bba2e](https://linux-hardware.org/?probe=5fe85bba2e) | Feb 22, 2022 |
| HP            | G62                         | Notebook    | [337afde8c1](https://linux-hardware.org/?probe=337afde8c1) | Feb 21, 2022 |
| HP            | G62                         | Notebook    | [a175af3dd6](https://linux-hardware.org/?probe=a175af3dd6) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [811ec775f8](https://linux-hardware.org/?probe=811ec775f8) | Feb 19, 2022 |
| powerinter... | Cepter N510-03              | Notebook    | [cd6804144d](https://linux-hardware.org/?probe=cd6804144d) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | Notebook    | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Lenovo        | ThinkPad E14 20RA001LMX     | Notebook    | [19edff5659](https://linux-hardware.org/?probe=19edff5659) | Feb 17, 2022 |
| HP            | Compaq 6910p (GB951EA#AK... | Notebook    | [b136dd5def](https://linux-hardware.org/?probe=b136dd5def) | Feb 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [deb108070d](https://linux-hardware.org/?probe=deb108070d) | Feb 15, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [87db259935](https://linux-hardware.org/?probe=87db259935) | Feb 15, 2022 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [8b588bf90b](https://linux-hardware.org/?probe=8b588bf90b) | Feb 15, 2022 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [a5179b9681](https://linux-hardware.org/?probe=a5179b9681) | Feb 15, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [7cdffcccb7](https://linux-hardware.org/?probe=7cdffcccb7) | Feb 13, 2022 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [0ba38c6605](https://linux-hardware.org/?probe=0ba38c6605) | Feb 13, 2022 |
| Dell          | Latitude E5420              | Notebook    | [f016e9f3ad](https://linux-hardware.org/?probe=f016e9f3ad) | Feb 12, 2022 |
| Dell          | Latitude E5420              | Notebook    | [8843a735a0](https://linux-hardware.org/?probe=8843a735a0) | Feb 12, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [61e1bce7ae](https://linux-hardware.org/?probe=61e1bce7ae) | Feb 12, 2022 |
| ASRock        | 890FX Deluxe4               | Desktop     | [33a47b3c4b](https://linux-hardware.org/?probe=33a47b3c4b) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [040550cdaa](https://linux-hardware.org/?probe=040550cdaa) | Feb 11, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [766e937263](https://linux-hardware.org/?probe=766e937263) | Feb 10, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [ba2262bba5](https://linux-hardware.org/?probe=ba2262bba5) | Feb 10, 2022 |
| Lenovo        | ThinkPad E590 20NB0012MX    | Notebook    | [92a33a8f31](https://linux-hardware.org/?probe=92a33a8f31) | Feb 10, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [3d76f83751](https://linux-hardware.org/?probe=3d76f83751) | Feb 10, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [75b31509a3](https://linux-hardware.org/?probe=75b31509a3) | Feb 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [72b880911a](https://linux-hardware.org/?probe=72b880911a) | Feb 08, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [88fdd17fc6](https://linux-hardware.org/?probe=88fdd17fc6) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [22be2d64a2](https://linux-hardware.org/?probe=22be2d64a2) | Feb 06, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [e0765c9f5a](https://linux-hardware.org/?probe=e0765c9f5a) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [6160f71e77](https://linux-hardware.org/?probe=6160f71e77) | Feb 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [035ccaeec8](https://linux-hardware.org/?probe=035ccaeec8) | Feb 04, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [cba6a6b5a6](https://linux-hardware.org/?probe=cba6a6b5a6) | Feb 02, 2022 |
| Dell          | 051FJ8 A00                  | Desktop     | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [e83deb15fd](https://linux-hardware.org/?probe=e83deb15fd) | Jan 31, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [5f6a8cf57f](https://linux-hardware.org/?probe=5f6a8cf57f) | Jan 29, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [9ff78b6d13](https://linux-hardware.org/?probe=9ff78b6d13) | Jan 29, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f76e2b6c0f](https://linux-hardware.org/?probe=f76e2b6c0f) | Jan 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| Lenovo        | ThinkPad X390 20Q00057MX    | Notebook    | [326cb714f0](https://linux-hardware.org/?probe=326cb714f0) | Jan 27, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [a31ae712c0](https://linux-hardware.org/?probe=a31ae712c0) | Jan 26, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [82a45a6067](https://linux-hardware.org/?probe=82a45a6067) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [f82216de53](https://linux-hardware.org/?probe=f82216de53) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [fe7ef8a290](https://linux-hardware.org/?probe=fe7ef8a290) | Jan 26, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [ef779f5d49](https://linux-hardware.org/?probe=ef779f5d49) | Jan 26, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [cf5823e07b](https://linux-hardware.org/?probe=cf5823e07b) | Jan 26, 2022 |
| Packard Be... | IMEDIA S3840                | Desktop     | [eff4bf09ec](https://linux-hardware.org/?probe=eff4bf09ec) | Jan 26, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [63d4ce1086](https://linux-hardware.org/?probe=63d4ce1086) | Jan 23, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [b9d8fc0e46](https://linux-hardware.org/?probe=b9d8fc0e46) | Jan 23, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [88049a6cee](https://linux-hardware.org/?probe=88049a6cee) | Jan 22, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | Notebook    | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [8f7c57b03f](https://linux-hardware.org/?probe=8f7c57b03f) | Jan 18, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [5f904131f5](https://linux-hardware.org/?probe=5f904131f5) | Jan 18, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [f6beec1048](https://linux-hardware.org/?probe=f6beec1048) | Jan 18, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [06c4be96aa](https://linux-hardware.org/?probe=06c4be96aa) | Jan 17, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [39b90ab9c3](https://linux-hardware.org/?probe=39b90ab9c3) | Jan 17, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | Notebook    | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| HP            | 18E5                        | Desktop     | [a06f3d3373](https://linux-hardware.org/?probe=a06f3d3373) | Jan 16, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [3417abe371](https://linux-hardware.org/?probe=3417abe371) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [3d2a67265f](https://linux-hardware.org/?probe=3d2a67265f) | Jan 15, 2022 |
| HP            | 1495                        | Desktop     | [ea7df45832](https://linux-hardware.org/?probe=ea7df45832) | Jan 14, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c2406eee73](https://linux-hardware.org/?probe=c2406eee73) | Jan 13, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [4bbc688f9d](https://linux-hardware.org/?probe=4bbc688f9d) | Jan 13, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [e82feb71d2](https://linux-hardware.org/?probe=e82feb71d2) | Jan 12, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0529614510](https://linux-hardware.org/?probe=0529614510) | Jan 12, 2022 |
| Toshiba       | Satellite P870              | Notebook    | [e046040d73](https://linux-hardware.org/?probe=e046040d73) | Jan 11, 2022 |
| HP            | Notebook                    | Notebook    | [0667124a5f](https://linux-hardware.org/?probe=0667124a5f) | Jan 10, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [1da9aea182](https://linux-hardware.org/?probe=1da9aea182) | Jan 10, 2022 |
| Sony          | VGN-FZ21Z                   | Notebook    | [6291085e58](https://linux-hardware.org/?probe=6291085e58) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| HP            | 3646h                       | Desktop     | [85edd0c1bf](https://linux-hardware.org/?probe=85edd0c1bf) | Jan 08, 2022 |
| HP            | 3646h                       | Desktop     | [616a0acd31](https://linux-hardware.org/?probe=616a0acd31) | Jan 08, 2022 |
| Sony          | VGN-FZ21Z                   | Notebook    | [c4ac286105](https://linux-hardware.org/?probe=c4ac286105) | Jan 08, 2022 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [72fa18d5dd](https://linux-hardware.org/?probe=72fa18d5dd) | Jan 08, 2022 |
| MSI           | H110M ECO                   | Desktop     | [c056a2eafa](https://linux-hardware.org/?probe=c056a2eafa) | Jan 07, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [1644301279](https://linux-hardware.org/?probe=1644301279) | Jan 07, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [6f8a6d74e4](https://linux-hardware.org/?probe=6f8a6d74e4) | Jan 07, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [b2682cb5fe](https://linux-hardware.org/?probe=b2682cb5fe) | Jan 06, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | Notebook    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Acer          | WMCP78M                     | Desktop     | [250fa57c5d](https://linux-hardware.org/?probe=250fa57c5d) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 20RA001BMX     | Notebook    | [b34ccf2c06](https://linux-hardware.org/?probe=b34ccf2c06) | Jan 05, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [c28c0f7f40](https://linux-hardware.org/?probe=c28c0f7f40) | Jan 04, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [0731f1a6d9](https://linux-hardware.org/?probe=0731f1a6d9) | Jan 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [5dd20e2872](https://linux-hardware.org/?probe=5dd20e2872) | Jan 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [4ed85a0f7a](https://linux-hardware.org/?probe=4ed85a0f7a) | Dec 30, 2021 |
| HP            | 3397                        | Desktop     | [188bb8c669](https://linux-hardware.org/?probe=188bb8c669) | Dec 28, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a3f574b521](https://linux-hardware.org/?probe=a3f574b521) | Dec 26, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | Notebook    | [25a59e69c1](https://linux-hardware.org/?probe=25a59e69c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | Notebook    | [a5b0d0a06a](https://linux-hardware.org/?probe=a5b0d0a06a) | Dec 25, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7b2a363709](https://linux-hardware.org/?probe=7b2a363709) | Dec 21, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [4384deed19](https://linux-hardware.org/?probe=4384deed19) | Dec 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [82a9ed12b5](https://linux-hardware.org/?probe=82a9ed12b5) | Dec 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Dell          | Latitude 5490               | Notebook    | [a9261b4529](https://linux-hardware.org/?probe=a9261b4529) | Dec 16, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [4365a457d8](https://linux-hardware.org/?probe=4365a457d8) | Dec 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a1c07a7e6a](https://linux-hardware.org/?probe=a1c07a7e6a) | Dec 15, 2021 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0ca333f8b0](https://linux-hardware.org/?probe=0ca333f8b0) | Dec 15, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [002a05b1c7](https://linux-hardware.org/?probe=002a05b1c7) | Dec 14, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [81873c2912](https://linux-hardware.org/?probe=81873c2912) | Dec 14, 2021 |
| Dell          | Precision 7510              | Notebook    | [59a0d1a314](https://linux-hardware.org/?probe=59a0d1a314) | Dec 13, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| HP            | Pavilion 15                 | Notebook    | [9b61f8e080](https://linux-hardware.org/?probe=9b61f8e080) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Samsung       | 750XDA                      | Notebook    | [30d61197a1](https://linux-hardware.org/?probe=30d61197a1) | Dec 09, 2021 |
| HP            | 340 G5                      | Notebook    | [8ed2eec9b4](https://linux-hardware.org/?probe=8ed2eec9b4) | Dec 07, 2021 |
| Dell          | Latitude E6400              | Notebook    | [b8e56749b8](https://linux-hardware.org/?probe=b8e56749b8) | Dec 03, 2021 |
| Lenovo        | ThinkPad W540 20BH002NMS    | Notebook    | [52d66e95f4](https://linux-hardware.org/?probe=52d66e95f4) | Dec 01, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [3284718afd](https://linux-hardware.org/?probe=3284718afd) | Dec 01, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [493153bf7c](https://linux-hardware.org/?probe=493153bf7c) | Nov 30, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [b98f644a91](https://linux-hardware.org/?probe=b98f644a91) | Nov 30, 2021 |
| HP            | 3646h                       | Desktop     | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | Desktop     | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [71d6a80bd1](https://linux-hardware.org/?probe=71d6a80bd1) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6591fce926](https://linux-hardware.org/?probe=6591fce926) | Nov 27, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [9ae82b251b](https://linux-hardware.org/?probe=9ae82b251b) | Nov 26, 2021 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [65d49ae483](https://linux-hardware.org/?probe=65d49ae483) | Nov 26, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3355d6fd50](https://linux-hardware.org/?probe=3355d6fd50) | Nov 24, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [9b0bfd9c19](https://linux-hardware.org/?probe=9b0bfd9c19) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f62619c698](https://linux-hardware.org/?probe=f62619c698) | Nov 24, 2021 |
| Acer          | WMCP78M                     | Desktop     | [5930f530bb](https://linux-hardware.org/?probe=5930f530bb) | Nov 24, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [9476bb5e05](https://linux-hardware.org/?probe=9476bb5e05) | Nov 24, 2021 |
| HP            | 3647h                       | Desktop     | [e3d0601f0b](https://linux-hardware.org/?probe=e3d0601f0b) | Nov 23, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [613686da3f](https://linux-hardware.org/?probe=613686da3f) | Nov 22, 2021 |
| HP            | 8433 11                     | Desktop     | [e88c3d4a94](https://linux-hardware.org/?probe=e88c3d4a94) | Nov 22, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | Notebook    | [cdf3297bef](https://linux-hardware.org/?probe=cdf3297bef) | Nov 21, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| Google        | Relm                        | Notebook    | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [11710ca51d](https://linux-hardware.org/?probe=11710ca51d) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| Lenovo        | ThinkStation S20 4157FY2    | Desktop     | [b05be2384d](https://linux-hardware.org/?probe=b05be2384d) | Nov 20, 2021 |
| Dell          | Latitude E6420              | Notebook    | [2e2b68b190](https://linux-hardware.org/?probe=2e2b68b190) | Nov 20, 2021 |
| HP            | Pavilion 17                 | Notebook    | [a633bbd978](https://linux-hardware.org/?probe=a633bbd978) | Nov 20, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d0581432da](https://linux-hardware.org/?probe=d0581432da) | Nov 20, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [646919d578](https://linux-hardware.org/?probe=646919d578) | Nov 20, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [972f96ba1d](https://linux-hardware.org/?probe=972f96ba1d) | Nov 17, 2021 |
| Lenovo        | ThinkPad T530 24341G0       | Notebook    | [0dcfa8bdc7](https://linux-hardware.org/?probe=0dcfa8bdc7) | Nov 17, 2021 |
| Dell          | Latitude 7420               | Notebook    | [52bd94ce90](https://linux-hardware.org/?probe=52bd94ce90) | Nov 17, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [5bed28d52e](https://linux-hardware.org/?probe=5bed28d52e) | Nov 15, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [da8846a5fd](https://linux-hardware.org/?probe=da8846a5fd) | Nov 14, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [d004277425](https://linux-hardware.org/?probe=d004277425) | Nov 14, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [1d72b572ac](https://linux-hardware.org/?probe=1d72b572ac) | Nov 14, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | Notebook    | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [438a1236fb](https://linux-hardware.org/?probe=438a1236fb) | Nov 11, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | Notebook    | [7a1824b26a](https://linux-hardware.org/?probe=7a1824b26a) | Nov 11, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| HP            | 1495                        | Desktop     | [d66a2a8cf5](https://linux-hardware.org/?probe=d66a2a8cf5) | Nov 10, 2021 |
| Lenovo        | Kabini CRB 31900003 STD     | Desktop     | [4d94fd8ba6](https://linux-hardware.org/?probe=4d94fd8ba6) | Nov 10, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [b98565dc8e](https://linux-hardware.org/?probe=b98565dc8e) | Nov 09, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [224597688f](https://linux-hardware.org/?probe=224597688f) | Nov 09, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [0aeea3a3c9](https://linux-hardware.org/?probe=0aeea3a3c9) | Nov 09, 2021 |
| HP            | 1495                        | Desktop     | [22bbd228cb](https://linux-hardware.org/?probe=22bbd228cb) | Nov 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [536b4200f8](https://linux-hardware.org/?probe=536b4200f8) | Nov 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [33a5ffbf9a](https://linux-hardware.org/?probe=33a5ffbf9a) | Nov 07, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [748d879ed2](https://linux-hardware.org/?probe=748d879ed2) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8cf09365a4](https://linux-hardware.org/?probe=8cf09365a4) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [10faa36c81](https://linux-hardware.org/?probe=10faa36c81) | Nov 06, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [a40335233e](https://linux-hardware.org/?probe=a40335233e) | Nov 04, 2021 |
| ASRock        | Z87 Extreme6                | Desktop     | [32b0b7b787](https://linux-hardware.org/?probe=32b0b7b787) | Nov 04, 2021 |
| ABIT          | AI7                         | Desktop     | [75f77dabe1](https://linux-hardware.org/?probe=75f77dabe1) | Nov 03, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [ae1af68eae](https://linux-hardware.org/?probe=ae1af68eae) | Nov 03, 2021 |
| Samsung       | R530/R730                   | Notebook    | [a62fb59972](https://linux-hardware.org/?probe=a62fb59972) | Nov 03, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [798cf3cc96](https://linux-hardware.org/?probe=798cf3cc96) | Nov 02, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [dfa80f4b9f](https://linux-hardware.org/?probe=dfa80f4b9f) | Oct 31, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [1217a94f61](https://linux-hardware.org/?probe=1217a94f61) | Oct 26, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [e10152abc8](https://linux-hardware.org/?probe=e10152abc8) | Oct 25, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [0f6daccd63](https://linux-hardware.org/?probe=0f6daccd63) | Oct 25, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [e74dc83f0a](https://linux-hardware.org/?probe=e74dc83f0a) | Oct 24, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [5b429fd560](https://linux-hardware.org/?probe=5b429fd560) | Oct 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [477512ba5c](https://linux-hardware.org/?probe=477512ba5c) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [c487ba6138](https://linux-hardware.org/?probe=c487ba6138) | Oct 22, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| HP            | Compaq 6735s                | Notebook    | [25c73d7c4d](https://linux-hardware.org/?probe=25c73d7c4d) | Oct 20, 2021 |
| HP            | 158B                        | Desktop     | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [d89008ef64](https://linux-hardware.org/?probe=d89008ef64) | Oct 16, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [8961245abb](https://linux-hardware.org/?probe=8961245abb) | Oct 15, 2021 |
| Acer          | Aspire 7530G                | Notebook    | [09694e2816](https://linux-hardware.org/?probe=09694e2816) | Oct 15, 2021 |
| HP            | ProBook 655 G1              | Notebook    | [5a67ea75fe](https://linux-hardware.org/?probe=5a67ea75fe) | Oct 14, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [072dab3e8c](https://linux-hardware.org/?probe=072dab3e8c) | Oct 14, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [cf747bee4e](https://linux-hardware.org/?probe=cf747bee4e) | Oct 13, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [e8ad89cb87](https://linux-hardware.org/?probe=e8ad89cb87) | Oct 12, 2021 |
| HP            | 21D0                        | Desktop     | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [818fe93a6d](https://linux-hardware.org/?probe=818fe93a6d) | Oct 10, 2021 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [319f2002de](https://linux-hardware.org/?probe=319f2002de) | Oct 09, 2021 |
| Dell          | 0YC523                      | Desktop     | [cf8d063deb](https://linux-hardware.org/?probe=cf8d063deb) | Oct 09, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [a9d87f6d4e](https://linux-hardware.org/?probe=a9d87f6d4e) | Oct 08, 2021 |
| Lenovo        | ThinkPad T490 20N2000KGE    | Notebook    | [cb7f37874e](https://linux-hardware.org/?probe=cb7f37874e) | Oct 07, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [2fe4152b53](https://linux-hardware.org/?probe=2fe4152b53) | Oct 07, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [26501031e8](https://linux-hardware.org/?probe=26501031e8) | Oct 07, 2021 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [28eb3733ca](https://linux-hardware.org/?probe=28eb3733ca) | Oct 06, 2021 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [8028a9757c](https://linux-hardware.org/?probe=8028a9757c) | Oct 06, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | Desktop     | [0c5e4a2345](https://linux-hardware.org/?probe=0c5e4a2345) | Oct 02, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [31df81c76d](https://linux-hardware.org/?probe=31df81c76d) | Sep 30, 2021 |
| HP            | 0AACh                       | Desktop     | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [ba4f1bda7d](https://linux-hardware.org/?probe=ba4f1bda7d) | Sep 30, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [8fa77435f7](https://linux-hardware.org/?probe=8fa77435f7) | Sep 29, 2021 |
| Medion        | B460H6-EM                   | Desktop     | [b461764429](https://linux-hardware.org/?probe=b461764429) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [171fc1cb46](https://linux-hardware.org/?probe=171fc1cb46) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [f9373d8ba5](https://linux-hardware.org/?probe=f9373d8ba5) | Sep 27, 2021 |
| MSI           | MS-7211                     | Desktop     | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [0914aeed54](https://linux-hardware.org/?probe=0914aeed54) | Sep 25, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [89783ad217](https://linux-hardware.org/?probe=89783ad217) | Sep 24, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [867138c338](https://linux-hardware.org/?probe=867138c338) | Sep 22, 2021 |
| Lenovo        | ThinkPad X230 204016Z1ZS    | Notebook    | [eb1d7abffc](https://linux-hardware.org/?probe=eb1d7abffc) | Sep 21, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | Desktop     | [7ded59f42f](https://linux-hardware.org/?probe=7ded59f42f) | Sep 21, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [a4488fd2fe](https://linux-hardware.org/?probe=a4488fd2fe) | Sep 19, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [f9509414bc](https://linux-hardware.org/?probe=f9509414bc) | Sep 18, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Finland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 187       | 12.17%  |
| Ubuntu 18.04                 | 103       | 6.7%    |
| Ubuntu 22.04                 | 74        | 4.81%   |
| OpenMandriva 23.01           | 60        | 3.9%    |
| Debian 11                    | 43        | 2.8%    |
| Arch Rolling                 | 42        | 2.73%   |
| Pop!_OS 22.04                | 34        | 2.21%   |
| OpenMandriva 4.2             | 33        | 2.15%   |
| Arch                         | 27        | 1.76%   |
| Manjaro                      | 26        | 1.69%   |
| OpenMandriva 4.3             | 25        | 1.63%   |
| Linux Mint 20                | 24        | 1.56%   |
| Ubuntu 21.04                 | 23        | 1.5%    |
| Linux Mint 21.1              | 23        | 1.5%    |
| OpenMandriva 23.03           | 22        | 1.43%   |
| Linux Mint 20.1              | 22        | 1.43%   |
| Pop!_OS 21.04                | 20        | 1.3%    |
| Ubuntu 20.10                 | 19        | 1.24%   |
| Fedora 36                    | 19        | 1.24%   |
| Xubuntu 20.04                | 18        | 1.17%   |
| EndeavourOS Rolling          | 18        | 1.17%   |
| Zorin 16                     | 17        | 1.11%   |
| Linux Mint 19.3              | 17        | 1.11%   |
| Fedora 33                    | 17        | 1.11%   |
| Ubuntu 21.10                 | 16        | 1.04%   |
| Pop!_OS 20.04                | 16        | 1.04%   |
| Gentoo 2.7                   | 15        | 0.98%   |
| Fedora 32                    | 15        | 0.98%   |
| Debian 10                    | 15        | 0.98%   |
| ArcoLinux Rolling            | 15        | 0.98%   |
| openSUSE Tumbleweed-XXXXXXXX | 14        | 0.91%   |
| Linux Mint 20.2              | 14        | 0.91%   |
| Fedora 37                    | 14        | 0.91%   |
| Fedora 34                    | 14        | 0.91%   |
| Fedora 31                    | 14        | 0.91%   |
| Ubuntu 19.10                 | 13        | 0.85%   |
| Linux Mint 20.3              | 13        | 0.85%   |
| Fedora 38                    | 12        | 0.78%   |
| Xubuntu 18.04                | 11        | 0.72%   |
| Pop!_OS 21.10                | 11        | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 446       | 30.78%  |
| OpenMandriva     | 142       | 9.8%    |
| Linux Mint       | 114       | 7.87%   |
| Fedora           | 102       | 7.04%   |
| Pop!_OS          | 85        | 5.87%   |
| Debian           | 75        | 5.18%   |
| Arch             | 69        | 4.76%   |
| Manjaro          | 61        | 4.21%   |
| Xubuntu          | 39        | 2.69%   |
| Gentoo           | 27        | 1.86%   |
| ROSA             | 26        | 1.79%   |
| Kubuntu          | 23        | 1.59%   |
| Zorin            | 21        | 1.45%   |
| openSUSE         | 20        | 1.38%   |
| EndeavourOS      | 20        | 1.38%   |
| ArcoLinux        | 17        | 1.17%   |
| Lubuntu          | 15        | 1.04%   |
| Ubuntu MATE      | 13        | 0.9%    |
| KDE neon         | 13        | 0.9%    |
| CentOS           | 11        | 0.76%   |
| MX               | 9         | 0.62%   |
| Elementary       | 8         | 0.55%   |
| Kali             | 7         | 0.48%   |
| Clear Linux      | 6         | 0.41%   |
| BlackPanther     | 6         | 0.41%   |
| Ubuntu Unity     | 5         | 0.35%   |
| Peppermint       | 5         | 0.35%   |
| Ubuntu Budgie    | 4         | 0.28%   |
| RHEL             | 4         | 0.28%   |
| Nobara           | 4         | 0.28%   |
| LMDE             | 4         | 0.28%   |
| Garuda Linux     | 4         | 0.28%   |
| Endless          | 4         | 0.28%   |
| Parrot           | 3         | 0.21%   |
| Oracle Linux     | 3         | 0.21%   |
| Artix            | 3         | 0.21%   |
| SteamOS          | 2         | 0.14%   |
| Solus            | 2         | 0.14%   |
| Raspbian         | 2         | 0.14%   |
| org.kde.Platform | 2         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.1.1-desktop-1omv2290   | 58        | 3.46%   |
| 5.4.0-42-generic         | 37        | 2.21%   |
| 5.10.14-desktop-1omv4002 | 32        | 1.91%   |
| 5.16.7-desktop-1omv4003  | 22        | 1.31%   |
| 6.2.6-desktop-1omv2390   | 20        | 1.19%   |
| 5.4.0-58-generic         | 18        | 1.07%   |
| 5.4.0-48-generic         | 16        | 0.96%   |
| 5.4.0-47-generic         | 16        | 0.96%   |
| 5.4.0-52-generic         | 12        | 0.72%   |
| 5.3.0-40-generic         | 12        | 0.72%   |
| 5.15.0-58-generic        | 12        | 0.72%   |
| 5.11.0-7620-generic      | 12        | 0.72%   |
| 5.8.0-44-generic         | 10        | 0.6%    |
| 5.15.0-52-generic        | 10        | 0.6%    |
| 5.8.0-41-generic         | 9         | 0.54%   |
| 5.4.0-65-generic         | 9         | 0.54%   |
| 5.4.0-56-generic         | 9         | 0.54%   |
| 5.4.0-53-generic         | 9         | 0.54%   |
| 5.15.0-48-generic        | 9         | 0.54%   |
| 5.15.0-46-generic        | 9         | 0.54%   |
| 5.4.0-45-generic         | 8         | 0.48%   |
| 5.13.0-7620-generic      | 8         | 0.48%   |
| 6.2.0-20-generic         | 7         | 0.42%   |
| 6.0.12-76060006-generic  | 7         | 0.42%   |
| 5.8.0-43-generic         | 7         | 0.42%   |
| 5.4.0-92-generic         | 7         | 0.42%   |
| 5.4.0-66-generic         | 7         | 0.42%   |
| 5.4.0-54-generic         | 7         | 0.42%   |
| 5.3.0-46-generic         | 7         | 0.42%   |
| 5.3.0-42-generic         | 7         | 0.42%   |
| 5.19.0-76051900-generic  | 7         | 0.42%   |
| 5.15.0-56-generic        | 7         | 0.42%   |
| 5.15.0-43-generic        | 7         | 0.42%   |
| 5.15.0-41-generic        | 7         | 0.42%   |
| 5.15.0-27-generic        | 7         | 0.42%   |
| 5.11.0-25-generic        | 7         | 0.42%   |
| 5.8.0-7630-generic       | 6         | 0.36%   |
| 5.4.0-7634-generic       | 6         | 0.36%   |
| 5.4.0-51-generic         | 6         | 0.36%   |
| 5.19.0-43-generic        | 6         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 255       | 15.99%  |
| 5.15.0  | 128       | 8.03%   |
| 5.8.0   | 81        | 5.08%   |
| 4.15.0  | 78        | 4.89%   |
| 5.11.0  | 73        | 4.58%   |
| 6.1.1   | 60        | 3.76%   |
| 5.13.0  | 50        | 3.13%   |
| 5.3.0   | 49        | 3.07%   |
| 5.10.0  | 40        | 2.51%   |
| 5.19.0  | 37        | 2.32%   |
| 5.10.14 | 33        | 2.07%   |
| 5.0.0   | 26        | 1.63%   |
| 6.2.6   | 25        | 1.57%   |
| 4.18.0  | 23        | 1.44%   |
| 5.16.7  | 22        | 1.38%   |
| 4.19.0  | 20        | 1.25%   |
| 6.2.0   | 10        | 0.63%   |
| 6.0.12  | 10        | 0.63%   |
| 5.17.5  | 9         | 0.56%   |
| 5.14.0  | 9         | 0.56%   |
| 6.1.0   | 8         | 0.5%    |
| 4.18.16 | 7         | 0.44%   |
| 6.1.4   | 6         | 0.38%   |
| 6.0.5   | 6         | 0.38%   |
| 6.0.0   | 6         | 0.38%   |
| 5.16.13 | 6         | 0.38%   |
| 5.10.74 | 6         | 0.38%   |
| 4.9.60  | 6         | 0.38%   |
| 3.10.0  | 6         | 0.38%   |
| 6.3.1   | 5         | 0.31%   |
| 6.2.9   | 5         | 0.31%   |
| 6.0.6   | 5         | 0.31%   |
| 5.15.15 | 5         | 0.31%   |
| 5.14.14 | 5         | 0.31%   |
| 5.12.4  | 5         | 0.31%   |
| 5.11.14 | 5         | 0.31%   |
| 6.0.8   | 4         | 0.25%   |
| 6.0.7   | 4         | 0.25%   |
| 6.0.11  | 4         | 0.25%   |
| 5.9.0   | 4         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 280       | 17.86%  |
| 5.15    | 189       | 12.05%  |
| 5.10    | 110       | 7.02%   |
| 5.8     | 106       | 6.76%   |
| 5.11    | 95        | 6.06%   |
| 6.1     | 94        | 5.99%   |
| 4.15    | 79        | 5.04%   |
| 5.13    | 66        | 4.21%   |
| 5.3     | 62        | 3.95%   |
| 6.2     | 59        | 3.76%   |
| 5.19    | 53        | 3.38%   |
| 5.16    | 47        | 3%      |
| 6.0     | 45        | 2.87%   |
| 4.18    | 31        | 1.98%   |
| 5.17    | 30        | 1.91%   |
| 5.0     | 27        | 1.72%   |
| 4.19    | 25        | 1.59%   |
| 5.14    | 22        | 1.4%    |
| 5.9     | 18        | 1.15%   |
| 5.7     | 17        | 1.08%   |
| 5.18    | 17        | 1.08%   |
| 5.12    | 17        | 1.08%   |
| 5.6     | 14        | 0.89%   |
| 4.9     | 14        | 0.89%   |
| 5.5     | 13        | 0.83%   |
| 6.3     | 12        | 0.77%   |
| 3.10    | 6         | 0.38%   |
| 4.1     | 4         | 0.26%   |
| 5.2     | 3         | 0.19%   |
| 4.4     | 3         | 0.19%   |
| 5.1     | 2         | 0.13%   |
| 4.13    | 2         | 0.13%   |
| 4.20    | 1         | 0.06%   |
| 4.17    | 1         | 0.06%   |
| 4.14    | 1         | 0.06%   |
| 4.12    | 1         | 0.06%   |
| 4.10    | 1         | 0.06%   |
| 4       | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1361      | 97.01%  |
| i686    | 30        | 2.14%   |
| aarch64 | 10        | 0.71%   |
| armv7l  | 1         | 0.07%   |
| armv6l  | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 607       | 41.69%  |
| KDE5             | 292       | 20.05%  |
| Unknown          | 184       | 12.64%  |
| XFCE             | 109       | 7.49%   |
| X-Cinnamon       | 78        | 5.36%   |
| MATE             | 42        | 2.88%   |
| KDE              | 23        | 1.58%   |
| LXQt             | 17        | 1.17%   |
| Cinnamon         | 15        | 1.03%   |
| KDE4             | 13        | 0.89%   |
| GNOME Flashback  | 11        | 0.76%   |
| LXDE             | 9         | 0.62%   |
| i3               | 9         | 0.62%   |
| Pantheon         | 7         | 0.48%   |
| Budgie           | 7         | 0.48%   |
| lightdm-xsession | 6         | 0.41%   |
| Unity            | 5         | 0.34%   |
| DWM              | 3         | 0.21%   |
| Deepin           | 3         | 0.21%   |
| bspwm            | 3         | 0.21%   |
| sway             | 2         | 0.14%   |
| LeftWM           | 2         | 0.14%   |
| Hyprland         | 2         | 0.14%   |
| xubuntu          | 1         | 0.07%   |
| xmonad           | 1         | 0.07%   |
| sway:Unity       | 1         | 0.07%   |
| Openbox          | 1         | 0.07%   |
| onyx:GNOME       | 1         | 0.07%   |
| GNOME Classic    | 1         | 0.07%   |
| BunsenLabs       | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1067      | 74.05%  |
| Wayland | 236       | 16.38%  |
| Unknown | 81        | 5.62%   |
| Tty     | 55        | 3.82%   |
| Web     | 2         | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 671       | 45.83%  |
| SDDM    | 266       | 18.17%  |
| GDM     | 194       | 13.25%  |
| GDM3    | 128       | 8.74%   |
| LightDM | 125       | 8.54%   |
| TDM     | 61        | 4.17%   |
| KDM     | 14        | 0.96%   |
| XDM     | 2         | 0.14%   |
| SLiM    | 1         | 0.07%   |
| Ly      | 1         | 0.07%   |
| LXDM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 639       | 44.47%  |
| fi_FI       | 450       | 31.32%  |
| Unknown     | 141       | 9.81%   |
| en_GB       | 95        | 6.61%   |
| C           | 26        | 1.81%   |
| ru_RU       | 23        | 1.6%    |
| en_FI       | 7         | 0.49%   |
| sv_FI       | 5         | 0.35%   |
| en_DK       | 5         | 0.35%   |
| sv_SE       | 4         | 0.28%   |
| fr_FR       | 4         | 0.28%   |
| C.UTF8      | 4         | 0.28%   |
| pl_PL       | 3         | 0.21%   |
| et_EE       | 3         | 0.21%   |
| en_US.UTf-8 | 3         | 0.21%   |
| en_AG       | 3         | 0.21%   |
| it_IT       | 2         | 0.14%   |
| en_SE       | 2         | 0.14%   |
| en_IE       | 2         | 0.14%   |
| en_CA       | 2         | 0.14%   |
| de_DE       | 2         | 0.14%   |
| zh_CN       | 1         | 0.07%   |
| UTF-8       | 1         | 0.07%   |
| POSIX       | 1         | 0.07%   |
| ja_JP       | 1         | 0.07%   |
| is_IS       | 1         | 0.07%   |
| ia_FR       | 1         | 0.07%   |
| hu_HU       | 1         | 0.07%   |
| fr_CA       | 1         | 0.07%   |
| es_ES       | 1         | 0.07%   |
| en_US.UTF8  | 1         | 0.07%   |
| en_NG       | 1         | 0.07%   |
| af_ZA       | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 738       | 51.5%   |
| EFI  | 695       | 48.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1045      | 72.62%  |
| Btrfs   | 155       | 10.77%  |
| Overlay | 135       | 9.38%   |
| Unknown | 42        | 2.92%   |
| Xfs     | 28        | 1.95%   |
| Zfs     | 14        | 0.97%   |
| Tmpfs   | 11        | 0.76%   |
| Ext2    | 4         | 0.28%   |
| Ext3    | 3         | 0.21%   |
| F2fs    | 2         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 654       | 45.45%  |
| GPT     | 599       | 41.63%  |
| MBR     | 186       | 12.93%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1193      | 83.54%  |
| Yes       | 235       | 16.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1046      | 73.46%  |
| Yes       | 378       | 26.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 308       | 21.97%  |
| Lenovo                  | 258       | 18.4%   |
| Hewlett-Packard         | 241       | 17.19%  |
| Dell                    | 105       | 7.49%   |
| Acer                    | 75        | 5.35%   |
| MSI                     | 74        | 5.28%   |
| Gigabyte Technology     | 63        | 4.49%   |
| ASRock                  | 54        | 3.85%   |
| Fujitsu                 | 39        | 2.78%   |
| Apple                   | 27        | 1.93%   |
| Intel                   | 22        | 1.57%   |
| Samsung Electronics     | 20        | 1.43%   |
| Fujitsu Siemens         | 11        | 0.78%   |
| Foxconn                 | 10        | 0.71%   |
| Pegatron                | 9         | 0.64%   |
| Toshiba                 | 7         | 0.5%    |
| Raspberry Pi Foundation | 7         | 0.5%    |
| Packard Bell            | 7         | 0.5%    |
| HUAWEI                  | 5         | 0.36%   |
| Unknown                 | 5         | 0.36%   |
| Supermicro              | 4         | 0.29%   |
| Sony                    | 4         | 0.29%   |
| Google                  | 3         | 0.21%   |
| AOpen                   | 3         | 0.21%   |
| AMI                     | 3         | 0.21%   |
| Valve                   | 2         | 0.14%   |
| Timi                    | 2         | 0.14%   |
| Notebook                | 2         | 0.14%   |
| Medion                  | 2         | 0.14%   |
| ASRockRack              | 2         | 0.14%   |
| ABIT                    | 2         | 0.14%   |
| ZOTAC                   | 1         | 0.07%   |
| ZMY                     | 1         | 0.07%   |
| Xunlong                 | 1         | 0.07%   |
| WeiBu                   | 1         | 0.07%   |
| TUXEDO                  | 1         | 0.07%   |
| TrekStor                | 1         | 0.07%   |
| Shuttle                 | 1         | 0.07%   |
| Seco                    | 1         | 0.07%   |
| powerinternational      | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS All Series                      | 24        | 1.71%   |
| HP EliteDesk 800 G1 SFF              | 9         | 0.64%   |
| Unknown                              | 8         | 0.57%   |
| MSI MS-7C37                          | 6         | 0.43%   |
| ASUS TUF Gaming X570-PLUS            | 6         | 0.43%   |
| ASUS ROG STRIX B550-F GAMING         | 6         | 0.43%   |
| ASUS M5A97 R2.0                      | 5         | 0.36%   |
| MSI MS-7A38                          | 4         | 0.29%   |
| Lenovo MIIX 310-10ICR 80SG           | 4         | 0.29%   |
| HP ProDesk 600 G3 DM                 | 4         | 0.29%   |
| HP EliteBook 840 G3                  | 4         | 0.29%   |
| HP EliteBook 2560p                   | 4         | 0.29%   |
| HP Compaq 8200 Elite SFF PC          | 4         | 0.29%   |
| Gigabyte X570 AORUS ELITE            | 4         | 0.29%   |
| Fujitsu LIFEBOOK A530                | 4         | 0.29%   |
| ASUS TUF Gaming FX505DT_FX505DT      | 4         | 0.29%   |
| ASUS TUF B450-PLUS GAMING            | 4         | 0.29%   |
| ASUS Pro WS 565-ACE                  | 4         | 0.29%   |
| ASUS PRIME X370-PRO                  | 4         | 0.29%   |
| ASUS PRIME B350-PLUS                 | 4         | 0.29%   |
| Samsung R530/R730                    | 3         | 0.21%   |
| Samsung 300E4A/300E5A/300E7A         | 3         | 0.21%   |
| MSI MS-7B89                          | 3         | 0.21%   |
| MSI MS-7B49                          | 3         | 0.21%   |
| MSI MS-7B48                          | 3         | 0.21%   |
| Lenovo Yoga Slim 7 14ARE05 82A2      | 3         | 0.21%   |
| Lenovo V145-15AST 81MT               | 3         | 0.21%   |
| Lenovo ThinkPad T420 4180PBG         | 3         | 0.21%   |
| HP ZBook 15 G4                       | 3         | 0.21%   |
| HP ProBook 650 G1                    | 3         | 0.21%   |
| HP Pavilion dv6                      | 3         | 0.21%   |
| HP Pavilion 17                       | 3         | 0.21%   |
| HP EliteBook 8460p                   | 3         | 0.21%   |
| HP EliteBook 840 G7 Notebook PC      | 3         | 0.21%   |
| HP EliteBook 840 G6                  | 3         | 0.21%   |
| HP EliteBook 840 G1                  | 3         | 0.21%   |
| HP EliteBook 820 G1                  | 3         | 0.21%   |
| Fujitsu Siemens ESPRIMO Mobile D9500 | 3         | 0.21%   |
| Fujitsu ESPRIMO E910                 | 3         | 0.21%   |
| Dell XPS 13 9380                     | 3         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 159       | 11.34%  |
| HP EliteBook            | 53        | 3.78%   |
| Acer Aspire             | 50        | 3.57%   |
| Dell Latitude           | 45        | 3.21%   |
| HP Compaq               | 41        | 2.92%   |
| ASUS PRIME              | 41        | 2.92%   |
| ASUS ROG                | 35        | 2.5%    |
| HP Pavilion             | 32        | 2.28%   |
| Lenovo IdeaPad          | 24        | 1.71%   |
| ASUS All                | 24        | 1.71%   |
| ASUS TUF                | 23        | 1.64%   |
| Fujitsu LIFEBOOK        | 19        | 1.36%   |
| Dell OptiPlex           | 17        | 1.21%   |
| Lenovo Yoga             | 16        | 1.14%   |
| HP EliteDesk            | 16        | 1.14%   |
| Dell XPS                | 16        | 1.14%   |
| Dell Precision          | 16        | 1.14%   |
| HP ProBook              | 15        | 1.07%   |
| Lenovo ThinkCentre      | 13        | 0.93%   |
| HP ProDesk              | 13        | 0.93%   |
| ASUS VivoBook           | 12        | 0.86%   |
| Fujitsu ESPRIMO         | 11        | 0.78%   |
| ASUS M5A97              | 11        | 0.78%   |
| HP ZBook                | 9         | 0.64%   |
| HP Laptop               | 9         | 0.64%   |
| Unknown                 | 8         | 0.57%   |
| Toshiba Satellite       | 7         | 0.5%    |
| RPi Raspberry           | 7         | 0.5%    |
| Gigabyte X570           | 7         | 0.5%    |
| Fujitsu Siemens ESPRIMO | 7         | 0.5%    |
| Acer Predator           | 7         | 0.5%    |
| MSI MS-7C37             | 6         | 0.43%   |
| Dell Inspiron           | 6         | 0.43%   |
| Lenovo Legion           | 5         | 0.36%   |
| HP ENVY                 | 5         | 0.36%   |
| ASUS Pro                | 5         | 0.36%   |
| Acer Swift              | 5         | 0.36%   |
| Samsung 300E4A          | 4         | 0.29%   |
| Packard Bell EasyNote   | 4         | 0.29%   |
| MSI MS-7A38             | 4         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 134       | 9.56%   |
| 2019    | 129       | 9.2%    |
| 2018    | 125       | 8.92%   |
| 2020    | 115       | 8.2%    |
| 2017    | 112       | 7.99%   |
| 2013    | 112       | 7.99%   |
| 2011    | 106       | 7.56%   |
| 2014    | 79        | 5.63%   |
| 2015    | 75        | 5.35%   |
| 2008    | 71        | 5.06%   |
| 2016    | 68        | 4.85%   |
| 2009    | 64        | 4.56%   |
| 2010    | 62        | 4.42%   |
| 2021    | 57        | 4.07%   |
| 2007    | 34        | 2.43%   |
| 2022    | 25        | 1.78%   |
| 2006    | 15        | 1.07%   |
| Unknown | 9         | 0.64%   |
| 2005    | 5         | 0.36%   |
| 2023    | 3         | 0.21%   |
| 2004    | 2         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 713       | 50.86%  |
| Desktop        | 596       | 42.51%  |
| Convertible    | 25        | 1.78%   |
| Mini pc        | 21        | 1.5%    |
| All in one     | 14        | 1%      |
| Server         | 14        | 1%      |
| System on chip | 9         | 0.64%   |
| Tablet         | 8         | 0.57%   |
| Phone          | 2         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1302      | 92.41%  |
| Enabled  | 107       | 7.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1398      | 99.71%  |
| Yes  | 4         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 317       | 22.28%  |
| 16.01-24.0      | 301       | 21.15%  |
| 3.01-4.0        | 273       | 19.18%  |
| 8.01-16.0       | 226       | 15.88%  |
| 32.01-64.0      | 153       | 10.75%  |
| 1.01-2.0        | 47        | 3.3%    |
| 64.01-256.0     | 44        | 3.09%   |
| 24.01-32.0      | 29        | 2.04%   |
| 2.01-3.0        | 19        | 1.34%   |
| 0.51-1.0        | 8         | 0.56%   |
| More than 256.0 | 4         | 0.28%   |
| 0.01-0.5        | 2         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 566       | 36.71%  |
| 2.01-3.0    | 351       | 22.76%  |
| 4.01-8.0    | 213       | 13.81%  |
| 3.01-4.0    | 178       | 11.54%  |
| 0.51-1.0    | 115       | 7.46%   |
| 8.01-16.0   | 72        | 4.67%   |
| 0.01-0.5    | 22        | 1.43%   |
| 16.01-24.0  | 11        | 0.71%   |
| 32.01-64.0  | 5         | 0.32%   |
| 24.01-32.0  | 5         | 0.32%   |
| 64.01-256.0 | 2         | 0.13%   |
| 0           | 2         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 857       | 59.43%  |
| 2      | 296       | 20.53%  |
| 3      | 130       | 9.02%   |
| 4      | 58        | 4.02%   |
| 5      | 36        | 2.5%    |
| 0      | 24        | 1.66%   |
| 6      | 16        | 1.11%   |
| 7      | 8         | 0.55%   |
| 9      | 6         | 0.42%   |
| 8      | 5         | 0.35%   |
| 10     | 4         | 0.28%   |
| 23     | 1         | 0.07%   |
| 11     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 842       | 59.38%  |
| Yes       | 576       | 40.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1253      | 89.18%  |
| No        | 152       | 10.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1002      | 71.01%  |
| No        | 409       | 28.99%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 798       | 56.32%  |
| No        | 619       | 43.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Finland | 1402      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Helsinki     | 641       | 42.7%   |
| Tampere      | 135       | 8.99%   |
| Turku        | 109       | 7.26%   |
| Espoo        | 74        | 4.93%   |
| Oulu         | 72        | 4.8%    |
| Vantaa       | 42        | 2.8%    |
| Kuopio       | 38        | 2.53%   |
| Jyväskylä  | 37        | 2.47%   |
| Lahti        | 30        | 2%      |
| Vaasa        | 17        | 1.13%   |
| Tuusula      | 15        | 1%      |
| Raisio       | 15        | 1%      |
| Hyvinkaeae   | 14        | 0.93%   |
| Joensuu      | 12        | 0.8%    |
| Lappeenranta | 10        | 0.67%   |
| Raahe        | 9         | 0.6%    |
| Pori         | 9         | 0.6%    |
| Kotka        | 8         | 0.53%   |
| Seinäjoki   | 7         | 0.47%   |
| Lohja        | 7         | 0.47%   |
| Kouvola      | 7         | 0.47%   |
| Salo         | 6         | 0.4%    |
| Rovaniemi    | 5         | 0.33%   |
| Kokkola      | 5         | 0.33%   |
| Järvenpää | 5         | 0.33%   |
| Hämeenlinna | 5         | 0.33%   |
| Forssa       | 5         | 0.33%   |
| Tenala       | 4         | 0.27%   |
| Solv         | 4         | 0.27%   |
| Riihimäki   | 4         | 0.27%   |
| Rauma        | 4         | 0.27%   |
| Klaukkala    | 4         | 0.27%   |
| Kerava       | 4         | 0.27%   |
| Uusikaupunki | 3         | 0.2%    |
| Rusko        | 3         | 0.2%    |
| Porvoo       | 3         | 0.2%    |
| Porlammi     | 3         | 0.2%    |
| Nokia        | 3         | 0.2%    |
| Mikkeli      | 3         | 0.2%    |
| Mäntsälä  | 3         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 421       | 670    | 20.47%  |
| WDC                         | 290       | 494    | 14.1%   |
| Seagate                     | 257       | 402    | 12.49%  |
| Kingston                    | 242       | 336    | 11.76%  |
| Toshiba                     | 98        | 150    | 4.76%   |
| Intel                       | 76        | 96     | 3.69%   |
| Hitachi                     | 72        | 99     | 3.5%    |
| Unknown                     | 71        | 102    | 3.45%   |
| SanDisk                     | 70        | 85     | 3.4%    |
| SK hynix                    | 61        | 79     | 2.97%   |
| Crucial                     | 56        | 66     | 2.72%   |
| Micron Technology           | 38        | 72     | 1.85%   |
| A-DATA Technology           | 32        | 40     | 1.56%   |
| HGST                        | 29        | 55     | 1.41%   |
| Transcend                   | 18        | 19     | 0.88%   |
| Corsair                     | 14        | 16     | 0.68%   |
| PNY                         | 13        | 14     | 0.63%   |
| OCZ                         | 13        | 18     | 0.63%   |
| Maxtor                      | 13        | 20     | 0.63%   |
| Phison                      | 12        | 13     | 0.58%   |
| KIOXIA                      | 12        | 12     | 0.58%   |
| Fujitsu                     | 12        | 15     | 0.58%   |
| Apple                       | 12        | 16     | 0.58%   |
| Verbatim                    | 11        | 17     | 0.53%   |
| LITEONIT                    | 8         | 11     | 0.39%   |
| LITEON                      | 8         | 12     | 0.39%   |
| Kingston Technology Company | 7         | 9      | 0.34%   |
| Intenso                     | 7         | 10     | 0.34%   |
| China                       | 5         | 5      | 0.24%   |
| XPG                         | 4         | 6      | 0.19%   |
| Patriot                     | 4         | 7      | 0.19%   |
| UMIS                        | 3         | 4      | 0.15%   |
| Lenovo                      | 3         | 3      | 0.15%   |
| HUAWEI                      | 3         | 3      | 0.15%   |
| Hewlett-Packard             | 3         | 4      | 0.15%   |
| Gigabyte Technology         | 3         | 4      | 0.15%   |
| BHT                         | 3         | 5      | 0.15%   |
| ASMT                        | 3         | 3      | 0.15%   |
| Unknown                     | 3         | 3      | 0.15%   |
| Plextor                     | 2         | 2      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 45        | 1.95%   |
| Samsung SSD 850 EVO 250GB                           | 33        | 1.43%   |
| Kingston SA400S37120G 120GB SSD                     | 28        | 1.21%   |
| Samsung SSD 850 EVO 500GB                           | 26        | 1.12%   |
| Kingston SA400S37480G 480GB SSD                     | 25        | 1.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 18        | 0.78%   |
| Samsung NVMe SSD Drive 500GB                        | 17        | 0.74%   |
| Kingston SV300S37A120G 120GB SSD                    | 17        | 0.74%   |
| Unknown MMC Card  64GB                              | 16        | 0.69%   |
| Samsung SSD 860 EVO 500GB                           | 15        | 0.65%   |
| Kingston SV300S37A240G 240GB SSD                    | 15        | 0.65%   |
| Unknown MMC Card  32GB                              | 14        | 0.61%   |
| Seagate ST9500325AS 500GB                           | 13        | 0.56%   |
| Seagate ST500DM002-1BD142 500GB                     | 13        | 0.56%   |
| Kingston SHFS37A120G 120GB SSD                      | 13        | 0.56%   |
| HGST HTS721010A9E630 1TB                            | 12        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                         | 12        | 0.52%   |
| Samsung NVMe SSD Drive 256GB                        | 11        | 0.48%   |
| Toshiba DT01ACA300 3TB                              | 10        | 0.43%   |
| Samsung SSD 860 EVO 1TB                             | 10        | 0.43%   |
| Samsung NVMe SSD Drive 512GB                        | 10        | 0.43%   |
| Samsung NVMe SSD Drive 1TB                          | 10        | 0.43%   |
| Samsung HD103SJ 1TB                                 | 10        | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 9         | 0.39%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 9         | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 9         | 0.39%   |
| Samsung SSD 840 EVO 120GB                           | 9         | 0.39%   |
| WDC WD40EFRX-68WT0N0 4TB                            | 8         | 0.35%   |
| Seagate ST500LT012-1DG142 500GB                     | 8         | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB                      | 8         | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB                      | 8         | 0.35%   |
| Samsung SSD 960 EVO 500GB                           | 8         | 0.35%   |
| Samsung HD501LJ 500GB                               | 8         | 0.35%   |
| PNY CS900 120GB SSD                                 | 8         | 0.35%   |
| Kingston SA400S37960G 960GB SSD                     | 8         | 0.35%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 0.3%    |
| Toshiba DT01ACA100 1TB                              | 7         | 0.3%    |
| SK hynix NVMe SSD Drive 256GB                       | 7         | 0.3%    |
| Seagate ST31000528AS 1TB                            | 7         | 0.3%    |
| Seagate ST1000DM010-2EP102 1TB                      | 7         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 249       | 389    | 34.02%  |
| WDC                 | 234       | 399    | 31.97%  |
| Hitachi             | 72        | 99     | 9.84%   |
| Toshiba             | 63        | 97     | 8.61%   |
| Samsung Electronics | 47        | 71     | 6.42%   |
| HGST                | 29        | 55     | 3.96%   |
| Maxtor              | 13        | 20     | 1.78%   |
| Fujitsu             | 12        | 15     | 1.64%   |
| Unknown             | 3         | 3      | 0.41%   |
| Intenso             | 2         | 2      | 0.27%   |
| ASMedia             | 2         | 2      | 0.27%   |
| Apple               | 2         | 2      | 0.27%   |
| USB3.0              | 1         | 1      | 0.14%   |
| RSH-339             | 1         | 1      | 0.14%   |
| JMicron Technology  | 1         | 4      | 0.14%   |
| Hewlett-Packard     | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 244       | 356    | 29.68%  |
| Kingston            | 215       | 299    | 26.16%  |
| Crucial             | 52        | 61     | 6.33%   |
| WDC                 | 44        | 62     | 5.35%   |
| SanDisk             | 35        | 43     | 4.26%   |
| Intel               | 34        | 50     | 4.14%   |
| Micron Technology   | 25        | 54     | 3.04%   |
| A-DATA Technology   | 20        | 25     | 2.43%   |
| Transcend           | 18        | 19     | 2.19%   |
| SK hynix            | 13        | 22     | 1.58%   |
| OCZ                 | 13        | 18     | 1.58%   |
| Toshiba             | 12        | 20     | 1.46%   |
| Verbatim            | 11        | 17     | 1.34%   |
| PNY                 | 11        | 12     | 1.34%   |
| LITEONIT            | 8         | 11     | 0.97%   |
| LITEON              | 8         | 12     | 0.97%   |
| Corsair             | 7         | 8      | 0.85%   |
| Apple               | 7         | 8      | 0.85%   |
| Intenso             | 5         | 8      | 0.61%   |
| China               | 5         | 5      | 0.61%   |
| Patriot             | 4         | 7      | 0.49%   |
| BHT                 | 3         | 5      | 0.36%   |
| ASMT                | 3         | 3      | 0.36%   |
| Plextor             | 2         | 2      | 0.24%   |
| OCZ-VERTEX3         | 2         | 2      | 0.24%   |
| OCZ-VERTEX          | 2         | 2      | 0.24%   |
| Hewlett-Packard     | 2         | 3      | 0.24%   |
| WDC WDS2            | 1         | 1      | 0.12%   |
| Vaseky              | 1         | 1      | 0.12%   |
| Unknown             | 1         | 1      | 0.12%   |
| TSA                 | 1         | 1      | 0.12%   |
| TO Exter            | 1         | 1      | 0.12%   |
| SPCC                | 1         | 1      | 0.12%   |
| Seagate             | 1         | 1      | 0.12%   |
| Ramsta              | 1         | 1      | 0.12%   |
| Netac               | 1         | 1      | 0.12%   |
| Kolink              | 1         | 1      | 0.12%   |
| GOODRAM             | 1         | 1      | 0.12%   |
| FORESEE             | 1         | 1      | 0.12%   |
| External            | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 700       | 1151   | 38.25%  |
| HDD     | 606       | 1161   | 33.11%  |
| NVMe    | 434       | 611    | 23.72%  |
| MMC     | 69        | 95     | 3.77%   |
| Unknown | 21        | 33     | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1066      | 2245   | 65.36%  |
| NVMe | 434       | 609    | 26.61%  |
| MMC  | 69        | 95     | 4.23%   |
| SAS  | 62        | 102    | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 869       | 1438   | 62.65%  |
| 0.51-1.0   | 332       | 479    | 23.94%  |
| 1.01-2.0   | 85        | 152    | 6.13%   |
| 3.01-4.0   | 35        | 97     | 2.52%   |
| 4.01-10.0  | 33        | 77     | 2.38%   |
| 2.01-3.0   | 32        | 68     | 2.31%   |
| 10.01-20.0 | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 430       | 29.25%  |
| 251-500        | 278       | 18.91%  |
| 501-1000       | 191       | 12.99%  |
| 1-20           | 124       | 8.44%   |
| 51-100         | 100       | 6.8%    |
| 1001-2000      | 88        | 5.99%   |
| More than 3000 | 86        | 5.85%   |
| Unknown        | 71        | 4.83%   |
| 21-50          | 54        | 3.67%   |
| 2001-3000      | 48        | 3.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 606       | 39.79%  |
| 21-50          | 255       | 16.74%  |
| 101-250        | 153       | 10.05%  |
| 51-100         | 151       | 9.91%   |
| 251-500        | 96        | 6.3%    |
| 501-1000       | 83        | 5.45%   |
| Unknown        | 71        | 4.66%   |
| 1001-2000      | 46        | 3.02%   |
| More than 3000 | 35        | 2.3%    |
| 2001-3000      | 26        | 1.71%   |
| 0              | 1         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD40EFRX-68WT0N0 4TB                       | 4         | 6      | 2.8%    |
| Seagate ST9500325AS 500GB                      | 4         | 5      | 2.8%    |
| Samsung Electronics HD103SJ 1TB                | 3         | 4      | 2.1%    |
| Kingston SHFS37A120G 120GB SSD                 | 3         | 4      | 2.1%    |
| Toshiba DT01ACA100 1TB                         | 2         | 2      | 1.4%    |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 1.4%    |
| Seagate ST3250318AS 250GB                      | 2         | 2      | 1.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 3      | 1.4%    |
| Samsung Electronics SSD 980 1TB                | 2         | 3      | 1.4%    |
| Samsung Electronics SSD 850 EVO 1TB            | 2         | 2      | 1.4%    |
| Micron Technology MTFDDAK512MAM-1K1 512GB SSD  | 2         | 4      | 1.4%    |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD | 2         | 4      | 1.4%    |
| Maxtor 7Y250M0 250GB                           | 2         | 2      | 1.4%    |
| Kingston SA400S37120G 120GB SSD                | 2         | 2      | 1.4%    |
| Intel SSDSA2M080G2GC 80GB                      | 2         | 2      | 1.4%    |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 1.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 0.7%    |
| WDC WDS120G2G0A-00JH30 128GB SSD               | 1         | 1      | 0.7%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                 | 1         | 2      | 0.7%    |
| WDC WD6400AAKS-07A7B0 640GB                    | 1         | 1      | 0.7%    |
| WDC WD50EZRZ-32RWYB1 5TB                       | 1         | 1      | 0.7%    |
| WDC WD5000ABPS-01ZZB0 500GB                    | 1         | 1      | 0.7%    |
| WDC WD5000AAKX-00ERMA0 500GB                   | 1         | 1      | 0.7%    |
| WDC WD5000AAKS-22A7B0 500GB                    | 1         | 1      | 0.7%    |
| WDC WD3200YS-01PGB0 320GB                      | 1         | 1      | 0.7%    |
| WDC WD3200BEVT-22ZCT0 320GB                    | 1         | 1      | 0.7%    |
| WDC WD3200AAKS-00L9A0 320GB                    | 1         | 1      | 0.7%    |
| WDC WD3200AAJS-60Z0A0 320GB                    | 1         | 1      | 0.7%    |
| WDC WD3200AAJS-00RYA0 320GB                    | 1         | 1      | 0.7%    |
| WDC WD30EFRX-68EUZN0 3TB                       | 1         | 1      | 0.7%    |
| WDC WD2500AAJS-00V4A0 250GB                    | 1         | 1      | 0.7%    |
| WDC WD2002FAEX-007BA0 2TB                      | 1         | 1      | 0.7%    |
| WDC WD1600BJKT-75F4T0 160GB                    | 1         | 1      | 0.7%    |
| WDC WD10JUCT-63CYNY0 1TB                       | 1         | 1      | 0.7%    |
| WDC WD10EZEX-60ZF5A0 1TB                       | 1         | 1      | 0.7%    |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 1      | 0.7%    |
| WDC WD10EARS-22Y5B1 1TB                        | 1         | 1      | 0.7%    |
| WDC WD10EADX-22TDHB0 1TB                       | 1         | 1      | 0.7%    |
| WDC WD10EADS-22M2B0 1TB                        | 1         | 1      | 0.7%    |
| Vaseky V800/60G 64GB                           | 1         | 1      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 34     | 22.14%  |
| WDC                 | 26        | 30     | 18.57%  |
| Kingston            | 14        | 15     | 10%     |
| Samsung Electronics | 13        | 16     | 9.29%   |
| Toshiba             | 10        | 10     | 7.14%   |
| Hitachi             | 10        | 18     | 7.14%   |
| Intel               | 6         | 6      | 4.29%   |
| HGST                | 6         | 6      | 4.29%   |
| Micron Technology   | 5         | 9      | 3.57%   |
| Maxtor              | 4         | 4      | 2.86%   |
| SK hynix            | 3         | 3      | 2.14%   |
| Fujitsu             | 2         | 3      | 1.43%   |
| Vaseky              | 1         | 1      | 0.71%   |
| USB3.0              | 1         | 1      | 0.71%   |
| SanDisk             | 1         | 1      | 0.71%   |
| PNY                 | 1         | 1      | 0.71%   |
| OCZ                 | 1         | 1      | 0.71%   |
| LITEONIT            | 1         | 1      | 0.71%   |
| Corsair             | 1         | 1      | 0.71%   |
| ATP                 | 1         | 1      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |
| A-DATA Technology   | 1         | 1      | 0.71%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 34     | 34.07%  |
| WDC                 | 23        | 26     | 25.27%  |
| Hitachi             | 10        | 18     | 10.99%  |
| Toshiba             | 9         | 9      | 9.89%   |
| HGST                | 6         | 6      | 6.59%   |
| Samsung Electronics | 5         | 6      | 5.49%   |
| Maxtor              | 4         | 4      | 4.4%    |
| Fujitsu             | 2         | 3      | 2.2%    |
| USB3.0              | 1         | 1      | 1.1%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 89        | 107    | 64.03%  |
| SSD  | 43        | 49     | 30.94%  |
| NVMe | 7         | 8      | 5.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB         | 1         | 1      | 50%     |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 753       | 1613   | 49.47%  |
| Works    | 631       | 1272   | 41.46%  |
| Malfunc  | 136       | 164    | 8.94%   |
| Failed   | 2         | 2      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 890       | 50.11%  |
| AMD                              | 309       | 17.4%   |
| Samsung Electronics              | 175       | 9.85%   |
| SanDisk                          | 53        | 2.98%   |
| SK hynix                         | 46        | 2.59%   |
| ASMedia Technology               | 38        | 2.14%   |
| Kingston Technology Company      | 35        | 1.97%   |
| Nvidia                           | 34        | 1.91%   |
| JMicron Technology               | 30        | 1.69%   |
| Phison Electronics               | 26        | 1.46%   |
| Toshiba America Info Systems     | 25        | 1.41%   |
| ADATA Technology                 | 18        | 1.01%   |
| Marvell Technology Group         | 17        | 0.96%   |
| Micron Technology                | 13        | 0.73%   |
| KIOXIA                           | 12        | 0.68%   |
| VIA Technologies                 | 8         | 0.45%   |
| Micron/Crucial Technology        | 7         | 0.39%   |
| LSI Logic / Symbios Logic        | 6         | 0.34%   |
| Broadcom / LSI                   | 5         | 0.28%   |
| Union Memory (Shenzhen)          | 4         | 0.23%   |
| Seagate Technology               | 4         | 0.23%   |
| Silicon Integrated Systems [SiS] | 3         | 0.17%   |
| Realtek Semiconductor            | 3         | 0.17%   |
| Lenovo                           | 3         | 0.17%   |
| Apple                            | 3         | 0.17%   |
| Solid State Storage Technology   | 2         | 0.11%   |
| Yangtze Memory Technologies      | 1         | 0.06%   |
| Silicon Motion                   | 1         | 0.06%   |
| Promise Technology               | 1         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.06%   |
| Lite-On Technology               | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Adaptec                          | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 198       | 9.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 99        | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 70        | 3.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 59        | 2.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 58        | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 52        | 2.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 47        | 2.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 46        | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 44        | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 42        | 2.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 40        | 1.92%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 36        | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 36        | 1.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 35        | 1.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 32        | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 30        | 1.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 30        | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 30        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 28        | 1.35%   |
| AMD 500 Series Chipset SATA Controller                                         | 28        | 1.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 24        | 1.15%   |
| Intel SSD 660P Series                                                          | 23        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 22        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 21        | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 21        | 1.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 20        | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 20        | 0.96%   |
| AMD 300 Series Chipset SATA Controller                                         | 20        | 0.96%   |
| Intel SATA Controller [RAID mode]                                              | 19        | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 19        | 0.91%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 18        | 0.87%   |
| Kingston Company A2000 NVMe SSD                                                | 18        | 0.87%   |
| Samsung NVMe SSD Controller 980                                                | 17        | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 0.77%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 16        | 0.77%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 15        | 0.72%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 15        | 0.72%   |
| Phison E12 NVMe Controller                                                     | 15        | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 15        | 0.72%   |
| JMicron JMB363 SATA/IDE Controller                                             | 14        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1059      | 58.93%  |
| NVMe | 439       | 24.43%  |
| IDE  | 209       | 11.63%  |
| RAID | 79        | 4.4%    |
| SAS  | 7         | 0.39%   |
| SCSI | 4         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1008      | 71.9%   |
| AMD          | 381       | 27.18%  |
| ARM          | 11        | 0.78%   |
| QUALCOMM     | 1         | 0.07%   |
| CentaurHauls | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 18        | 1.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 17        | 1.21%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 17        | 1.21%   |
| AMD Ryzen 5 3600 6-Core Processor       | 17        | 1.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 14        | 1%      |
| AMD Ryzen 7 3700X 8-Core Processor      | 14        | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz       | 12        | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 12        | 0.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 0.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 12        | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 11        | 0.78%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 11        | 0.78%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 10        | 0.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 9         | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 9         | 0.64%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 9         | 0.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 9         | 0.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 9         | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 9         | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 9         | 0.64%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 9         | 0.64%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 9         | 0.64%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 9         | 0.64%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 8         | 0.57%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 8         | 0.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 8         | 0.57%   |
| AMD FX-8350 Eight-Core Processor        | 8         | 0.57%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 7         | 0.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz       | 7         | 0.5%    |
| Intel Core i7-6700 CPU @ 3.40GHz        | 7         | 0.5%    |
| Intel Core i5-6600K CPU @ 3.50GHz       | 7         | 0.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz        | 7         | 0.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 7         | 0.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz       | 7         | 0.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 0.5%    |
| Intel Celeron CPU N3060 @ 1.60GHz       | 7         | 0.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz       | 7         | 0.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 0.5%    |
| ARM Processor                           | 7         | 0.5%    |
| AMD Ryzen 9 5900X 12-Core Processor     | 7         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 356       | 25.37%  |
| Intel Core i7                  | 247       | 17.61%  |
| AMD Ryzen 5                    | 88        | 6.27%   |
| Intel Core i3                  | 80        | 5.7%    |
| AMD Ryzen 7                    | 69        | 4.92%   |
| Intel Celeron                  | 65        | 4.63%   |
| Intel Core 2 Duo               | 64        | 4.56%   |
| Other                          | 52        | 3.71%   |
| Intel Xeon                     | 36        | 2.57%   |
| Intel Pentium                  | 34        | 2.42%   |
| AMD Ryzen 9                    | 31        | 2.21%   |
| AMD FX                         | 25        | 1.78%   |
| Intel Atom                     | 20        | 1.43%   |
| Intel Pentium Dual-Core        | 18        | 1.28%   |
| AMD Ryzen 3                    | 14        | 1%      |
| AMD Athlon II X2               | 13        | 0.93%   |
| AMD E1                         | 12        | 0.86%   |
| AMD Athlon 64 X2               | 11        | 0.78%   |
| Intel Core 2 Quad              | 10        | 0.71%   |
| AMD Ryzen 7 PRO                | 10        | 0.71%   |
| AMD Phenom II X4               | 10        | 0.71%   |
| AMD A4                         | 9         | 0.64%   |
| Intel Core 2                   | 8         | 0.57%   |
| AMD A10                        | 8         | 0.57%   |
| Intel Genuine                  | 7         | 0.5%    |
| Intel Core i9                  | 7         | 0.5%    |
| AMD A8                         | 7         | 0.5%    |
| AMD Phenom                     | 5         | 0.36%   |
| AMD Athlon                     | 5         | 0.36%   |
| Intel Pentium Dual             | 4         | 0.29%   |
| AMD Ryzen 5 PRO                | 4         | 0.29%   |
| AMD Phenom II X6               | 4         | 0.29%   |
| AMD E2                         | 4         | 0.29%   |
| AMD A6                         | 4         | 0.29%   |
| Intel Pentium 4                | 3         | 0.21%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.21%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.21%   |
| AMD Ryzen 3 PRO                | 3         | 0.21%   |
| AMD EPYC                       | 3         | 0.21%   |
| AMD Athlon II X4               | 3         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 561       | 39.96%  |
| 4       | 521       | 37.11%  |
| 6       | 123       | 8.76%   |
| 8       | 105       | 7.48%   |
| 1       | 28        | 1.99%   |
| 12      | 21        | 1.5%    |
| 16      | 15        | 1.07%   |
| 3       | 12        | 0.85%   |
| 10      | 4         | 0.28%   |
| 14      | 3         | 0.21%   |
| 24      | 2         | 0.14%   |
| 20      | 2         | 0.14%   |
| Unknown | 2         | 0.14%   |
| 80      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 32      | 1         | 0.07%   |
| 18      | 1         | 0.07%   |
| 5       | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1391      | 99.22%  |
| 2       | 8         | 0.57%   |
| Unknown | 2         | 0.14%   |
| 0       | 1         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 892       | 63.53%  |
| 1       | 510       | 36.32%  |
| Unknown | 2         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1373      | 97.65%  |
| Unknown        | 21        | 1.49%   |
| 32-bit         | 11        | 0.78%   |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 381       | 26.29%  |
| 0x206a7    | 78        | 5.38%   |
| 0x306a9    | 77        | 5.31%   |
| 0x306c3    | 59        | 4.07%   |
| 0x1067a    | 48        | 3.31%   |
| 0x506e3    | 45        | 3.11%   |
| 0x806ec    | 38        | 2.62%   |
| 0x40651    | 33        | 2.28%   |
| 0x806ea    | 28        | 1.93%   |
| 0x406e3    | 28        | 1.93%   |
| 0x906e9    | 25        | 1.73%   |
| 0x08701021 | 23        | 1.59%   |
| 0x906ea    | 22        | 1.52%   |
| 0x20655    | 20        | 1.38%   |
| 0x306d4    | 19        | 1.31%   |
| 0x0800820d | 18        | 1.24%   |
| 0x806e9    | 17        | 1.17%   |
| 0x406c4    | 17        | 1.17%   |
| 0x30678    | 17        | 1.17%   |
| 0x10676    | 17        | 1.17%   |
| 0x806c1    | 16        | 1.1%    |
| 0x20652    | 15        | 1.04%   |
| 0x0a201016 | 15        | 1.04%   |
| 0x08701013 | 14        | 0.97%   |
| 0x06000852 | 14        | 0.97%   |
| 0x6fd      | 13        | 0.9%    |
| 0x010000c8 | 13        | 0.9%    |
| 0x6fb      | 12        | 0.83%   |
| 0x506c9    | 10        | 0.69%   |
| 0x08600106 | 10        | 0.69%   |
| 0x08108102 | 10        | 0.69%   |
| 0xa0652    | 9         | 0.62%   |
| 0x806eb    | 9         | 0.62%   |
| 0x106e5    | 9         | 0.62%   |
| 0x06001119 | 9         | 0.62%   |
| 0x906eb    | 8         | 0.55%   |
| 0x706e5    | 8         | 0.55%   |
| 0x0810100b | 8         | 0.55%   |
| 0x05000119 | 7         | 0.48%   |
| 0x906ed    | 6         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 208       | 14.8%   |
| Haswell          | 139       | 9.89%   |
| SandyBridge      | 108       | 7.69%   |
| IvyBridge        | 99        | 7.05%   |
| Skylake          | 95        | 6.76%   |
| Zen 2            | 76        | 5.41%   |
| Penryn           | 74        | 5.27%   |
| Zen 3            | 52        | 3.7%    |
| Silvermont       | 45        | 3.2%    |
| Core             | 44        | 3.13%   |
| Zen+             | 43        | 3.06%   |
| Zen              | 42        | 2.99%   |
| Westmere         | 42        | 2.99%   |
| K10              | 40        | 2.85%   |
| Unknown          | 40        | 2.85%   |
| Piledriver       | 34        | 2.42%   |
| Broadwell        | 27        | 1.92%   |
| TigerLake        | 22        | 1.57%   |
| K8 Hammer        | 22        | 1.57%   |
| CometLake        | 21        | 1.49%   |
| Nehalem          | 19        | 1.35%   |
| IceLake          | 15        | 1.07%   |
| Goldmont         | 12        | 0.85%   |
| Excavator        | 12        | 0.85%   |
| Bobcat           | 10        | 0.71%   |
| Puma             | 9         | 0.64%   |
| Goldmont plus    | 9         | 0.64%   |
| K8 & K10 hybrid  | 7         | 0.5%    |
| Jaguar           | 7         | 0.5%    |
| P6               | 6         | 0.43%   |
| Bonnell          | 6         | 0.43%   |
| Steamroller      | 5         | 0.36%   |
| NetBurst         | 5         | 0.36%   |
| Bulldozer        | 4         | 0.28%   |
| Alderlake Hybrid | 4         | 0.28%   |
| K10 Llano        | 2         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 737       | 46.26%  |
| Nvidia                                       | 468       | 29.38%  |
| AMD                                          | 359       | 22.54%  |
| ASPEED Technology                            | 13        | 0.82%   |
| Matrox Electronics Systems                   | 8         | 0.5%    |
| Silicon Motion                               | 3         | 0.19%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.19%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.06%   |
| VIA Technologies                             | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 80        | 4.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 52        | 3.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 43        | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 35        | 2.12%   |
| Intel UHD Graphics 620                                                                   | 33        | 2%      |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 2%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 31        | 1.87%   |
| Intel HD Graphics 530                                                                    | 29        | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 1.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 25        | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 1.51%   |
| AMD Renoir                                                                               | 24        | 1.45%   |
| Intel HD Graphics 620                                                                    | 22        | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 22        | 1.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 20        | 1.21%   |
| Intel HD Graphics 5500                                                                   | 20        | 1.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 1.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 17        | 1.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 0.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 14        | 0.85%   |
| Intel HD Graphics 630                                                                    | 14        | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 13        | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13        | 0.79%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 13        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 0.73%   |
| Nvidia GT218 [GeForce 210]                                                               | 11        | 0.67%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 11        | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10        | 0.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.6%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 10        | 0.6%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 9         | 0.54%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 9         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 570       | 40.25%  |
| 1 x Nvidia         | 317       | 22.39%  |
| 1 x AMD            | 290       | 20.48%  |
| Intel + Nvidia     | 120       | 8.47%   |
| Intel + AMD        | 23        | 1.62%   |
| 2 x AMD            | 22        | 1.55%   |
| AMD + Nvidia       | 21        | 1.48%   |
| 1 x ASPEED         | 13        | 0.92%   |
| Other              | 12        | 0.85%   |
| 2 x Nvidia         | 7         | 0.49%   |
| 1 x Matrox         | 6         | 0.42%   |
| 2 x Intel          | 5         | 0.35%   |
| 1 x SiS            | 3         | 0.21%   |
| 1 x Silicon Motion | 3         | 0.21%   |
| Nvidia + Matrox    | 2         | 0.14%   |
| 1 x XGI            | 1         | 0.07%   |
| 1 x VIA            | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1088      | 76.3%   |
| Proprietary | 265       | 18.58%  |
| Unknown     | 73        | 5.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 788       | 54.65%  |
| 0.01-0.5   | 161       | 11.17%  |
| 1.01-2.0   | 157       | 10.89%  |
| 0.51-1.0   | 103       | 7.14%   |
| 3.01-4.0   | 91        | 6.31%   |
| 7.01-8.0   | 76        | 5.27%   |
| 5.01-6.0   | 34        | 2.36%   |
| 2.01-3.0   | 13        | 0.9%    |
| 8.01-16.0  | 13        | 0.9%    |
| 16.01-24.0 | 6         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 243       | 15.75%  |
| AU Optronics            | 157       | 10.17%  |
| LG Display              | 144       | 9.33%   |
| Chimei Innolux          | 100       | 6.48%   |
| BenQ                    | 77        | 4.99%   |
| Hewlett-Packard         | 74        | 4.8%    |
| Dell                    | 74        | 4.8%    |
| Acer                    | 74        | 4.8%    |
| BOE                     | 68        | 4.41%   |
| Ancor Communications    | 65        | 4.21%   |
| Lenovo                  | 60        | 3.89%   |
| Goldstar                | 51        | 3.31%   |
| Fujitsu Siemens         | 25        | 1.62%   |
| ASUSTek Computer        | 25        | 1.62%   |
| Apple                   | 25        | 1.62%   |
| AOC                     | 25        | 1.62%   |
| Sharp                   | 21        | 1.36%   |
| Philips                 | 21        | 1.36%   |
| Sony                    | 20        | 1.3%    |
| InfoVision              | 18        | 1.17%   |
| ViewSonic               | 16        | 1.04%   |
| Eizo                    | 13        | 0.84%   |
| Chi Mei Optoelectronics | 10        | 0.65%   |
| Vestel Elektronik       | 9         | 0.58%   |
| LG Philips              | 9         | 0.58%   |
| CSO                     | 8         | 0.52%   |
| Unknown                 | 7         | 0.45%   |
| LG Electronics          | 7         | 0.45%   |
| Toshiba                 | 6         | 0.39%   |
| PANDA                   | 6         | 0.39%   |
| Panasonic               | 6         | 0.39%   |
| IBM                     | 4         | 0.26%   |
| FUS                     | 4         | 0.26%   |
| CPT                     | 4         | 0.26%   |
| Valve                   | 3         | 0.19%   |
| Packard Bell            | 3         | 0.19%   |
| Onkyo                   | 3         | 0.19%   |
| NEC Computers           | 3         | 0.19%   |
| LGD                     | 3         | 0.19%   |
| Lenovo Group Limited    | 3         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 9         | 0.57%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6         | 0.38%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 6         | 0.38%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch  | 5         | 0.31%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 5         | 0.31%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 5         | 0.31%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 5         | 0.31%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 5         | 0.31%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 4         | 0.25%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 4         | 0.25%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.25%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 4         | 0.25%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.25%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch           | 4         | 0.25%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                 | 4         | 0.25%   |
| Hewlett-Packard Z23i HWP3090 1920x1080 509x286mm 23.0-inch            | 4         | 0.25%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 4         | 0.25%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 4         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 4         | 0.25%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 4         | 0.25%   |
| BenQ XL2411Z BNQ7F32 1920x1080 531x298mm 24.0-inch                    | 4         | 0.25%   |
| BenQ G2420HDB BNQ7842 1920x1080 477x268mm 21.5-inch                   | 4         | 0.25%   |
| BenQ G2400W BNQ780A 1920x1200 519x324mm 24.1-inch                     | 4         | 0.25%   |
| BenQ EW3270U BNQ7950 3840x2160 700x390mm 31.5-inch                    | 4         | 0.25%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 4         | 0.25%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 4         | 0.25%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 4         | 0.25%   |
| Acer X34A ACR0450 3440x1440 800x340mm 34.2-inch                       | 4         | 0.25%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 3         | 0.19%   |
| Samsung Electronics T24D390 SAM0B6C 1920x1080 521x293mm 23.5-inch     | 3         | 0.19%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 3         | 0.19%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 3         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 634       | 42.55%  |
| 1366x768 (WXGA)    | 188       | 12.62%  |
| 3840x2160 (4K)     | 100       | 6.71%   |
| 2560x1440 (QHD)    | 92        | 6.17%   |
| 1920x1200 (WUXGA)  | 65        | 4.36%   |
| 1680x1050 (WSXGA+) | 65        | 4.36%   |
| 1600x900 (HD+)     | 64        | 4.3%    |
| 1280x1024 (SXGA)   | 51        | 3.42%   |
| 1440x900 (WXGA+)   | 42        | 2.82%   |
| Unknown            | 30        | 2.01%   |
| 1280x800 (WXGA)    | 29        | 1.95%   |
| 3440x1440          | 21        | 1.41%   |
| 1360x768           | 14        | 0.94%   |
| 3840x1080          | 12        | 0.81%   |
| 2560x1600          | 7         | 0.47%   |
| 3840x2400          | 6         | 0.4%    |
| 2880x1800          | 6         | 0.4%    |
| 1280x720 (HD)      | 6         | 0.4%    |
| 1920x540           | 5         | 0.34%   |
| 1600x1200          | 5         | 0.34%   |
| 4480x1440          | 4         | 0.27%   |
| 1024x600           | 4         | 0.27%   |
| 3840x1200          | 3         | 0.2%    |
| 3200x1800 (QHD+)   | 3         | 0.2%    |
| 2560x1080          | 3         | 0.2%    |
| 800x1280           | 2         | 0.13%   |
| 5760x2160          | 2         | 0.13%   |
| 5120x1440          | 2         | 0.13%   |
| 3360x1050          | 2         | 0.13%   |
| 1400x1050          | 2         | 0.13%   |
| 5760x1440          | 1         | 0.07%   |
| 5280x1080          | 1         | 0.07%   |
| 4480x1600          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 3520x1200          | 1         | 0.07%   |
| 3360x1080          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2800x1752          | 1         | 0.07%   |
| 2736x1824          | 1         | 0.07%   |
| 2560x2880          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 281       | 18.44%  |
| 24      | 152       | 9.97%   |
| 13      | 142       | 9.32%   |
| 14      | 135       | 8.86%   |
| 27      | 131       | 8.6%    |
| 23      | 114       | 7.48%   |
| Unknown | 99        | 6.5%    |
| 17      | 73        | 4.79%   |
| 22      | 46        | 3.02%   |
| 19      | 44        | 2.89%   |
| 21      | 43        | 2.82%   |
| 12      | 38        | 2.49%   |
| 31      | 34        | 2.23%   |
| 84      | 24        | 1.57%   |
| 18      | 21        | 1.38%   |
| 34      | 19        | 1.25%   |
| 11      | 17        | 1.12%   |
| 20      | 14        | 0.92%   |
| 32      | 13        | 0.85%   |
| 25      | 11        | 0.72%   |
| 72      | 9         | 0.59%   |
| 40      | 7         | 0.46%   |
| 28      | 7         | 0.46%   |
| 55      | 5         | 0.33%   |
| 26      | 5         | 0.33%   |
| 16      | 4         | 0.26%   |
| 10      | 4         | 0.26%   |
| 75      | 3         | 0.2%    |
| 65      | 3         | 0.2%    |
| 54      | 3         | 0.2%    |
| 48      | 3         | 0.2%    |
| 43      | 2         | 0.13%   |
| 39      | 2         | 0.13%   |
| 36      | 2         | 0.13%   |
| 33      | 2         | 0.13%   |
| 29      | 2         | 0.13%   |
| 7       | 2         | 0.13%   |
| 142     | 1         | 0.07%   |
| 66      | 1         | 0.07%   |
| 58      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 490       | 33.11%  |
| 501-600        | 357       | 24.12%  |
| 201-300        | 131       | 8.85%   |
| 401-500        | 126       | 8.51%   |
| 351-400        | 111       | 7.5%    |
| Unknown        | 99        | 6.69%   |
| 601-700        | 61        | 4.12%   |
| 701-800        | 36        | 2.43%   |
| 1501-2000      | 36        | 2.43%   |
| 1001-1500      | 18        | 1.22%   |
| 801-900        | 11        | 0.74%   |
| 1-100          | 2         | 0.14%   |
| More than 2000 | 1         | 0.07%   |
| 901-1000       | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 966       | 70.1%   |
| 16/10   | 226       | 16.4%   |
| Unknown | 82        | 5.95%   |
| 5/4     | 50        | 3.63%   |
| 21/9    | 23        | 1.67%   |
| 3/2     | 10        | 0.73%   |
| 4/3     | 8         | 0.58%   |
| 32/9    | 5         | 0.36%   |
| 6/5     | 2         | 0.15%   |
| 0.67    | 2         | 0.15%   |
| 3.20    | 1         | 0.07%   |
| 1.00    | 1         | 0.07%   |
| 0.89    | 1         | 0.07%   |
| 0.45    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 279       | 18.59%  |
| 201-250        | 265       | 17.65%  |
| 81-90          | 219       | 14.59%  |
| 301-350        | 136       | 9.06%   |
| Unknown        | 99        | 6.6%    |
| 151-200        | 76        | 5.06%   |
| 351-500        | 75        | 5%      |
| 251-300        | 74        | 4.93%   |
| 71-80          | 57        | 3.8%    |
| 121-130        | 51        | 3.4%    |
| More than 1000 | 50        | 3.33%   |
| 61-70          | 38        | 2.53%   |
| 141-150        | 24        | 1.6%    |
| 501-1000       | 19        | 1.27%   |
| 51-60          | 17        | 1.13%   |
| 131-140        | 9         | 0.6%    |
| 111-120        | 7         | 0.47%   |
| 41-50          | 4         | 0.27%   |
| 1-40           | 2         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 518       | 35.48%  |
| 121-160       | 400       | 27.4%   |
| 101-120       | 310       | 21.23%  |
| Unknown       | 99        | 6.78%   |
| 161-240       | 71        | 4.86%   |
| 1-50          | 35        | 2.4%    |
| More than 240 | 27        | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1098      | 76.57%  |
| 2     | 229       | 15.97%  |
| 0     | 77        | 5.37%   |
| 3     | 27        | 1.88%   |
| 4     | 3         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 754       | 35.9%   |
| Realtek Semiconductor                  | 630       | 30%     |
| Qualcomm Atheros                       | 189       | 9%      |
| Broadcom                               | 108       | 5.14%   |
| Ralink                                 | 29        | 1.38%   |
| Huawei Technologies                    | 27        | 1.29%   |
| Nvidia                                 | 26        | 1.24%   |
| Marvell Technology Group               | 26        | 1.24%   |
| MediaTek                               | 25        | 1.19%   |
| TP-Link                                | 23        | 1.1%    |
| Broadcom Limited                       | 22        | 1.05%   |
| Ericsson Business Mobile Networks      | 21        | 1%      |
| ASUSTek Computer                       | 19        | 0.9%    |
| Hewlett-Packard                        | 18        | 0.86%   |
| Samsung Electronics                    | 16        | 0.76%   |
| Ralink Technology                      | 15        | 0.71%   |
| Sierra Wireless                        | 11        | 0.52%   |
| Dell                                   | 11        | 0.52%   |
| Lenovo                                 | 9         | 0.43%   |
| Xiaomi                                 | 8         | 0.38%   |
| ZyXEL Communications                   | 7         | 0.33%   |
| Microsoft                              | 7         | 0.33%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.29%   |
| ASIX Electronics                       | 6         | 0.29%   |
| Microchip Technology                   | 5         | 0.24%   |
| Fibocom                                | 5         | 0.24%   |
| D-Link System                          | 5         | 0.24%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.19%   |
| Motorola PCS                           | 4         | 0.19%   |
| HMD Global                             | 4         | 0.19%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.14%   |
| Qualcomm                               | 3         | 0.14%   |
| NetGear                                | 3         | 0.14%   |
| Linksys                                | 3         | 0.14%   |
| Gemtek                                 | 3         | 0.14%   |
| DisplayLink                            | 3         | 0.14%   |
| D-Link                                 | 3         | 0.14%   |
| BUFFALO                                | 3         | 0.14%   |
| Aquantia                               | 3         | 0.14%   |
| 3Com                                   | 3         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 464       | 18.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 88        | 3.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 51        | 2.01%   |
| Intel Wi-Fi 6 AX200                                               | 48        | 1.89%   |
| Intel I211 Gigabit Network Connection                             | 47        | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 41        | 1.62%   |
| Intel Wireless 8265 / 8275                                        | 40        | 1.58%   |
| Intel Wireless 7260                                               | 37        | 1.46%   |
| Intel Wireless 8260                                               | 33        | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 32        | 1.26%   |
| Intel Wireless 7265                                               | 32        | 1.26%   |
| Intel Ethernet Connection (2) I219-V                              | 29        | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28        | 1.1%    |
| Intel Ethernet Connection I217-LM                                 | 27        | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 25        | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 25        | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 23        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 21        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 0.79%   |
| Intel Wi-Fi 6 AX201                                               | 20        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 20        | 0.79%   |
| Intel Ethernet Connection (6) I219-V                              | 19        | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 18        | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 18        | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 17        | 0.67%   |
| Intel Ethernet Controller I225-V                                  | 16        | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 15        | 0.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 15        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 15        | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 15        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 0.59%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 15        | 0.59%   |
| Intel Wireless-AC 9260                                            | 14        | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 512       | 48.26%  |
| Qualcomm Atheros                | 153       | 14.42%  |
| Realtek Semiconductor           | 146       | 13.76%  |
| Broadcom                        | 69        | 6.5%    |
| Ralink                          | 29        | 2.73%   |
| TP-Link                         | 22        | 2.07%   |
| MediaTek                        | 21        | 1.98%   |
| ASUSTek Computer                | 19        | 1.79%   |
| Ralink Technology               | 15        | 1.41%   |
| Sierra Wireless                 | 11        | 1.04%   |
| Broadcom Limited                | 10        | 0.94%   |
| ZyXEL Communications            | 7         | 0.66%   |
| Microsoft                       | 7         | 0.66%   |
| Hewlett-Packard                 | 6         | 0.57%   |
| Dell                            | 6         | 0.57%   |
| Fibocom                         | 5         | 0.47%   |
| D-Link System                   | 4         | 0.38%   |
| NetGear                         | 3         | 0.28%   |
| Gemtek                          | 3         | 0.28%   |
| BUFFALO                         | 3         | 0.28%   |
| Linksys                         | 2         | 0.19%   |
| Edimax Technology               | 2         | 0.19%   |
| D-Link                          | 2         | 0.19%   |
| ZyDAS                           | 1         | 0.09%   |
| Qualcomm Atheros Communications | 1         | 0.09%   |
| Marvell Technology Group        | 1         | 0.09%   |
| LG Electronics                  | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 48        | 4.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 41        | 3.85%   |
| Intel Wireless 8265 / 8275                                              | 40        | 3.76%   |
| Intel Wireless 7260                                                     | 37        | 3.48%   |
| Intel Wireless 8260                                                     | 33        | 3.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 32        | 3.01%   |
| Intel Wireless 7265                                                     | 32        | 3.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 2.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 25        | 2.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 23        | 2.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.88%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 20        | 1.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 18        | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 15        | 1.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 15        | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.41%   |
| Intel Wireless-AC 9260                                                  | 14        | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.22%   |
| Intel Centrino Advanced-N 6235                                          | 13        | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 1.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 1.13%   |
| Intel Wireless 3165                                                     | 12        | 1.13%   |
| Intel Centrino Ultimate-N 6300                                          | 12        | 1.13%   |
| Intel Centrino Advanced-N 6200                                          | 11        | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 0.94%   |
| Intel Wireless 3160                                                     | 10        | 0.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 10        | 0.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 9         | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 9         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 0.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 9         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 0.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 585       | 42.67%  |
| Intel                                  | 512       | 37.35%  |
| Qualcomm Atheros                       | 51        | 3.72%   |
| Broadcom                               | 51        | 3.72%   |
| Nvidia                                 | 26        | 1.9%    |
| Marvell Technology Group               | 25        | 1.82%   |
| Huawei Technologies                    | 20        | 1.46%   |
| Samsung Electronics                    | 12        | 0.88%   |
| Broadcom Limited                       | 12        | 0.88%   |
| Lenovo                                 | 9         | 0.66%   |
| Xiaomi                                 | 8         | 0.58%   |
| ASIX Electronics                       | 6         | 0.44%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.36%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.29%   |
| MediaTek                               | 4         | 0.29%   |
| HMD Global                             | 4         | 0.29%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.22%   |
| Qualcomm                               | 3         | 0.22%   |
| DisplayLink                            | 3         | 0.22%   |
| Aquantia                               | 3         | 0.22%   |
| 3Com                                   | 3         | 0.22%   |
| TP-Link                                | 2         | 0.15%   |
| Motorola PCS                           | 2         | 0.15%   |
| Hewlett-Packard                        | 2         | 0.15%   |
| VIA Technologies                       | 1         | 0.07%   |
| Standard Microsystems                  | 1         | 0.07%   |
| OPPO Electronics                       | 1         | 0.07%   |
| Microchip Technology                   | 1         | 0.07%   |
| Linksys                                | 1         | 0.07%   |
| ICS Advent                             | 1         | 0.07%   |
| IBM                                    | 1         | 0.07%   |
| Google                                 | 1         | 0.07%   |
| Foxconn / Hon Hai                      | 1         | 0.07%   |
| D-Link System                          | 1         | 0.07%   |
| D-Link                                 | 1         | 0.07%   |
| Attansic Technology                    | 1         | 0.07%   |
| Apple                                  | 1         | 0.07%   |
| American Megatrends                    | 1         | 0.07%   |
| AMD                                    | 1         | 0.07%   |
| ADMtek                                 | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 464       | 33.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 88        | 6.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 51        | 3.64%   |
| Intel I211 Gigabit Network Connection                             | 47        | 3.35%   |
| Intel Ethernet Connection (2) I219-V                              | 29        | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28        | 2%      |
| Intel Ethernet Connection I217-LM                                 | 27        | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 1.85%   |
| Intel Ethernet Connection (6) I219-V                              | 19        | 1.35%   |
| Intel I210 Gigabit Network Connection                             | 18        | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 1.28%   |
| Intel Ethernet Controller I225-V                                  | 16        | 1.14%   |
| Intel Ethernet Connection I218-LM                                 | 15        | 1.07%   |
| Intel Ethernet Connection I217-V                                  | 15        | 1.07%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 1.07%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 1.07%   |
| Intel 82577LM Gigabit Network Connection                          | 15        | 1.07%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 1%      |
| Intel Ethernet Connection (3) I218-LM                             | 13        | 0.93%   |
| Huawei LLD-L21                                                    | 12        | 0.86%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.78%   |
| Nvidia MCP61 Ethernet                                             | 11        | 0.78%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.71%   |
| Intel Ethernet Connection (2) I218-V                              | 10        | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 10        | 0.71%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                          | 9         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.57%   |
| Intel I350 Gigabit Network Connection                             | 8         | 0.57%   |
| Intel 82574L Gigabit Network Connection                           | 8         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                             | 7         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                             | 6         | 0.43%   |
| Huawei E353/E3131                                                 | 6         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1252      | 54.01%  |
| WiFi     | 999       | 43.1%   |
| Modem    | 63        | 2.72%   |
| Unknown  | 4         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 729       | 51.41%  |
| Ethernet | 686       | 48.38%  |
| Modem    | 2         | 0.14%   |
| Unknown  | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 770       | 54.57%  |
| 1     | 563       | 39.9%   |
| 3     | 35        | 2.48%   |
| 0     | 29        | 2.06%   |
| 4     | 9         | 0.64%   |
| 5     | 5         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1161      | 80.68%  |
| Yes  | 278       | 19.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 379       | 46.56%  |
| Realtek Semiconductor           | 63        | 7.74%   |
| Broadcom                        | 63        | 7.74%   |
| Cambridge Silicon Radio         | 56        | 6.88%   |
| Qualcomm Atheros Communications | 49        | 6.02%   |
| ASUSTek Computer                | 38        | 4.67%   |
| IMC Networks                    | 34        | 4.18%   |
| Apple                           | 27        | 3.32%   |
| Foxconn / Hon Hai               | 23        | 2.83%   |
| Lite-On Technology              | 18        | 2.21%   |
| Hewlett-Packard                 | 15        | 1.84%   |
| Dell                            | 11        | 1.35%   |
| Askey Computer                  | 8         | 0.98%   |
| Ralink                          | 7         | 0.86%   |
| MediaTek                        | 4         | 0.49%   |
| HTC (High Tech Computer)        | 4         | 0.49%   |
| Foxconn International           | 4         | 0.49%   |
| Toshiba                         | 2         | 0.25%   |
| Edimax Technology               | 2         | 0.25%   |
| Taiyo Yuden                     | 1         | 0.12%   |
| Realtek                         | 1         | 0.12%   |
| Marvell Semiconductor           | 1         | 0.12%   |
| Fujitsu                         | 1         | 0.12%   |
| Chicony Electronics             | 1         | 0.12%   |
| Belkin Components               | 1         | 0.12%   |
| Alps Electric                   | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 157       | 19.24%  |
| Intel AX201 Bluetooth                               | 60        | 7.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 56        | 6.86%   |
| Intel AX200 Bluetooth                               | 53        | 6.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 43        | 5.27%   |
| Realtek Bluetooth Radio                             | 32        | 3.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 22        | 2.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 2.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 19        | 2.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 2.08%   |
| IMC Networks Bluetooth Radio                        | 14        | 1.72%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 1.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 1.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 1.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 1.35%   |
| IMC Networks Bluetooth Device                       | 9         | 1.1%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 9         | 1.1%    |
| Intel AX210 Bluetooth                               | 8         | 0.98%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.98%   |
| Askey Bluetooth Device                              | 8         | 0.98%   |
| Apple Bluetooth USB Host Controller                 | 8         | 0.98%   |
| Realtek RTL8723B Bluetooth                          | 7         | 0.86%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.86%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 0.86%   |
| Broadcom HP Portable Bumble Bee                     | 7         | 0.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.74%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.74%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 0.74%   |
| ASUS ASUS USB-BT500                                 | 6         | 0.74%   |
| Apple Bluetooth Host Controller                     | 6         | 0.74%   |
| Lite-On Bluetooth Device                            | 5         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 5         | 0.61%   |
| MediaTek Wireless_Device                            | 4         | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.49%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.49%   |
| IMC Networks Wireless_Device                        | 4         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 944       | 47.46%  |
| AMD                                  | 414       | 20.81%  |
| Nvidia                               | 386       | 19.41%  |
| C-Media Electronics                  | 27        | 1.36%   |
| Logitech                             | 19        | 0.96%   |
| Creative Labs                        | 15        | 0.75%   |
| Kingston Technology                  | 10        | 0.5%    |
| ASUSTek Computer                     | 10        | 0.5%    |
| Texas Instruments                    | 9         | 0.45%   |
| GN Netcom                            | 9         | 0.45%   |
| Creative Technology                  | 9         | 0.45%   |
| SteelSeries ApS                      | 8         | 0.4%    |
| Realtek Semiconductor                | 8         | 0.4%    |
| Razer USA                            | 7         | 0.35%   |
| VIA Technologies                     | 6         | 0.3%    |
| Lenovo                               | 6         | 0.3%    |
| RODE Microphones                     | 5         | 0.25%   |
| Plantronics                          | 5         | 0.25%   |
| Focusrite-Novation                   | 5         | 0.25%   |
| M-Audio                              | 4         | 0.2%    |
| GYROCOM C&C                          | 4         | 0.2%    |
| Generalplus Technology               | 4         | 0.2%    |
| Corsair                              | 4         | 0.2%    |
| Blue Microphones                     | 4         | 0.2%    |
| Thesycon Systemsoftware & Consulting | 3         | 0.15%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.15%   |
| Sennheiser Communications            | 3         | 0.15%   |
| Microsoft                            | 3         | 0.15%   |
| Hewlett-Packard                      | 3         | 0.15%   |
| Cambridge Audio                      | 3         | 0.15%   |
| Turtle Beach                         | 2         | 0.1%    |
| Scarlett                             | 2         | 0.1%    |
| SAVITECH                             | 2         | 0.1%    |
| JBL                                  | 2         | 0.1%    |
| FiiO Electronics Technology          | 2         | 0.1%    |
| DSEA A/S                             | 2         | 0.1%    |
| DigiTech                             | 2         | 0.1%    |
| AudioQuest                           | 2         | 0.1%    |
| ZOOM                                 | 1         | 0.05%   |
| Yamaha                               | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 106       | 4.5%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 97        | 4.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 93        | 3.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 91        | 3.87%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 76        | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 71        | 3.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 67        | 2.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 55        | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 49        | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 48        | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 46        | 1.95%   |
| Intel 8 Series HD Audio Controller                                                                | 43        | 1.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 42        | 1.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 42        | 1.78%   |
| AMD FCH Azalia Controller                                                                         | 42        | 1.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 40        | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 40        | 1.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 40        | 1.7%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 35        | 1.49%   |
| Intel 200 Series PCH HD Audio                                                                     | 34        | 1.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 30        | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 30        | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 29        | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 28        | 1.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 26        | 1.1%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 23        | 0.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 22        | 0.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 22        | 0.93%   |
| Intel Broadwell-U Audio Controller                                                                | 22        | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 21        | 0.89%   |
| Nvidia High Definition Audio Controller                                                           | 20        | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 20        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 18        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 17        | 0.72%   |
| Intel CM238 HD Audio Controller                                                                   | 17        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 16        | 0.68%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 15        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 238       | 24.92%  |
| Kingston            | 180       | 18.85%  |
| SK hynix            | 167       | 17.49%  |
| Micron Technology   | 90        | 9.42%   |
| Unknown             | 88        | 9.21%   |
| Corsair             | 47        | 4.92%   |
| G.Skill             | 37        | 3.87%   |
| Crucial             | 32        | 3.35%   |
| Elpida              | 17        | 1.78%   |
| Ramaxel Technology  | 14        | 1.47%   |
| A-DATA Technology   | 13        | 1.36%   |
| Nanya Technology    | 8         | 0.84%   |
| Qimonda             | 3         | 0.31%   |
| Unknown (ABCD)      | 2         | 0.21%   |
| Team                | 2         | 0.21%   |
| ASint Technology    | 2         | 0.21%   |
| Apacer              | 2         | 0.21%   |
| Unknown (AB)        | 1         | 0.1%    |
| Unigen              | 1         | 0.1%    |
| Toshiba             | 1         | 0.1%    |
| PUSKILL             | 1         | 0.1%    |
| pqi                 | 1         | 0.1%    |
| Patriot             | 1         | 0.1%    |
| Hitachi             | 1         | 0.1%    |
| Hewlett-Packard     | 1         | 0.1%    |
| GOODRAM             | 1         | 0.1%    |
| GIGA-BYTE           | 1         | 0.1%    |
| ChangXin Memory     | 1         | 0.1%    |
| 48spaces            | 1         | 0.1%    |
| Unknown             | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 14        | 1.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 12        | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 11        | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 10        | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s    | 10        | 0.97%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 10        | 0.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 9         | 0.87%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 9         | 0.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 9         | 0.87%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 8         | 0.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 7         | 0.68%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 7         | 0.68%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s              | 7         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s    | 7         | 0.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 7         | 0.68%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 7         | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 6         | 0.58%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 5         | 0.48%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s | 5         | 0.48%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s     | 5         | 0.48%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 5         | 0.48%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s    | 5         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 4         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 4         | 0.39%   |
| Unknown RAM Module 1024MB SODIMM DDR2                    | 4         | 0.39%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s             | 4         | 0.39%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s             | 4         | 0.39%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 4         | 0.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s   | 4         | 0.39%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s    | 4         | 0.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 4         | 0.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s    | 4         | 0.39%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM 2200MT/s           | 4         | 0.39%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 4         | 0.39%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s   | 4         | 0.39%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 4         | 0.39%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s      | 4         | 0.39%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s     | 4         | 0.39%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s      | 4         | 0.39%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 4         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 377       | 44.51%  |
| DDR3    | 305       | 36.01%  |
| DDR2    | 65        | 7.67%   |
| SDRAM   | 24        | 2.83%   |
| LPDDR4  | 22        | 2.6%    |
| LPDDR3  | 22        | 2.6%    |
| Unknown | 19        | 2.24%   |
| DDR     | 7         | 0.83%   |
| DDR5    | 4         | 0.47%   |
| DRAM    | 2         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 445       | 53.1%   |
| DIMM         | 344       | 41.05%  |
| Row Of Chips | 39        | 4.65%   |
| Chip         | 5         | 0.6%    |
| RIMM         | 2         | 0.24%   |
| Unknown      | 2         | 0.24%   |
| FB-DIMM      | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 324       | 35.92%  |
| 4096  | 249       | 27.61%  |
| 2048  | 131       | 14.52%  |
| 16384 | 120       | 13.3%   |
| 1024  | 40        | 4.43%   |
| 32768 | 33        | 3.66%   |
| 512   | 5         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 179       | 19.54%  |
| 2667    | 107       | 11.68%  |
| 3200    | 98        | 10.7%   |
| 1333    | 62        | 6.77%   |
| 2133    | 61        | 6.66%   |
| 2400    | 57        | 6.22%   |
| 667     | 40        | 4.37%   |
| 3600    | 36        | 3.93%   |
| 1334    | 35        | 3.82%   |
| 800     | 29        | 3.17%   |
| 1867    | 25        | 2.73%   |
| Unknown | 15        | 1.64%   |
| 3466    | 13        | 1.42%   |
| 1067    | 13        | 1.42%   |
| 3266    | 11        | 1.2%    |
| 1066    | 11        | 1.2%    |
| 4267    | 10        | 1.09%   |
| 3000    | 8         | 0.87%   |
| 4199    | 7         | 0.76%   |
| 3800    | 7         | 0.76%   |
| 3733    | 7         | 0.76%   |
| 2933    | 7         | 0.76%   |
| 3533    | 6         | 0.66%   |
| 2048    | 6         | 0.66%   |
| 1866    | 5         | 0.55%   |
| 533     | 5         | 0.55%   |
| 3866    | 4         | 0.44%   |
| 2800    | 4         | 0.44%   |
| 2200    | 4         | 0.44%   |
| 3400    | 3         | 0.33%   |
| 2666    | 3         | 0.33%   |
| 1800    | 3         | 0.33%   |
| 975     | 3         | 0.33%   |
| 49926   | 2         | 0.22%   |
| 4800    | 2         | 0.22%   |
| 4266    | 2         | 0.22%   |
| 3333    | 2         | 0.22%   |
| 3151    | 2         | 0.22%   |
| 3100    | 2         | 0.22%   |
| 1639    | 2         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 36.36%  |
| Samsung Electronics   | 5         | 15.15%  |
| Seiko Epson           | 4         | 12.12%  |
| Canon                 | 4         | 12.12%  |
| Brother Industries    | 3         | 9.09%   |
| Xerox                 | 1         | 3.03%   |
| Prolific Technology   | 1         | 3.03%   |
| Pantum                | 1         | 3.03%   |
| Lexmark International | 1         | 3.03%   |
| Dell                  | 1         | 3.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-1660 Series              | 2         | 6.06%   |
| Xerox Phaser 6500DN                 | 1         | 3.03%   |
| Seiko Epson XP-510 Series           | 1         | 3.03%   |
| Seiko Epson WF-3520 Series          | 1         | 3.03%   |
| Seiko Epson Printer                 | 1         | 3.03%   |
| Seiko Epson L555 Series             | 1         | 3.03%   |
| Samsung M2020 Series                | 1         | 3.03%   |
| Samsung CLP-325 Color Laser Printer | 1         | 3.03%   |
| Samsung C43x Series                 | 1         | 3.03%   |
| Prolific PL2305 Parallel Port       | 1         | 3.03%   |
| Pantum P2500W series                | 1         | 3.03%   |
| Lexmark International 2400 series   | 1         | 3.03%   |
| HP PSC 1100 series                  | 1         | 3.03%   |
| HP OfficeJet Pro 69                 | 1         | 3.03%   |
| HP OfficeJet 5200 series            | 1         | 3.03%   |
| HP LaserJet Professional P 1102w    | 1         | 3.03%   |
| HP LaserJet Pro M148-M149           | 1         | 3.03%   |
| HP LaserJet P2055 series            | 1         | 3.03%   |
| HP LaserJet P2015 series            | 1         | 3.03%   |
| HP LaserJet 1200                    | 1         | 3.03%   |
| HP DeskJet F300 series              | 1         | 3.03%   |
| HP DeskJet 960c                     | 1         | 3.03%   |
| HP DeskJet 6940 series              | 1         | 3.03%   |
| HP DeskJet 2130 series              | 1         | 3.03%   |
| Dell Laser Printer 1720             | 1         | 3.03%   |
| Canon TS3300 series                 | 1         | 3.03%   |
| Canon TS3100 series                 | 1         | 3.03%   |
| Canon PIXMA MG3100 Series           | 1         | 3.03%   |
| Canon LBP6000                       | 1         | 3.03%   |
| Brother MFC-7460DN                  | 1         | 3.03%   |
| Brother DCP-L2530DW series          | 1         | 3.03%   |
| Brother DCP-7055 scanner/printer    | 1         | 3.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 5         | 83.33%  |
| Seiko Epson | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan N650U/N656U            | 2         | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 16.67%  |
| Canon CanoScan LiDE 200               | 1         | 16.67%  |
| Canon CanoScan LiDE 110               | 1         | 16.67%  |
| Canon CanoScan LiDE 100               | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 218       | 29.74%  |
| IMC Networks                           | 67        | 9.14%   |
| Microdia                               | 54        | 7.37%   |
| Realtek Semiconductor                  | 48        | 6.55%   |
| Logitech                               | 48        | 6.55%   |
| Bison Electronics                      | 34        | 4.64%   |
| Cheng Uei Precision Industry (Foxlink) | 30        | 4.09%   |
| Sunplus Innovation Technology          | 29        | 3.96%   |
| Quanta                                 | 28        | 3.82%   |
| Suyin                                  | 25        | 3.41%   |
| Apple                                  | 23        | 3.14%   |
| Lite-On Technology                     | 18        | 2.46%   |
| Acer                                   | 17        | 2.32%   |
| Syntek                                 | 13        | 1.77%   |
| Silicon Motion                         | 12        | 1.64%   |
| Lenovo                                 | 10        | 1.36%   |
| Microsoft                              | 9         | 1.23%   |
| Samsung Electronics                    | 7         | 0.95%   |
| Primax Electronics                     | 5         | 0.68%   |
| Z-Star Microelectronics                | 4         | 0.55%   |
| Alcor Micro                            | 4         | 0.55%   |
| Ricoh                                  | 3         | 0.41%   |
| Luxvisions Innotech Limited            | 3         | 0.41%   |
| ALi                                    | 3         | 0.41%   |
| Trust                                  | 2         | 0.27%   |
| Sonix Technology                       | 2         | 0.27%   |
| MacroSilicon                           | 2         | 0.27%   |
| Importek                               | 2         | 0.27%   |
| DigiTech                               | 2         | 0.27%   |
| Creative Technology                    | 2         | 0.27%   |
| Valve Software                         | 1         | 0.14%   |
| SunplusIT                              | 1         | 0.14%   |
| STEREOLABS                             | 1         | 0.14%   |
| OnePlus                                | 1         | 0.14%   |
| Omnivision                             | 1         | 0.14%   |
| LG Electronics                         | 1         | 0.14%   |
| Hewlett-Packard                        | 1         | 0.14%   |
| Google                                 | 1         | 0.14%   |
| Generalplus Technology                 | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 55        | 7.49%   |
| IMC Networks Integrated Camera                      | 22        | 3%      |
| Microdia Integrated_Webcam_HD                       | 21        | 2.86%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 16        | 2.18%   |
| Bison Integrated Camera                             | 13        | 1.77%   |
| Realtek Integrated_Webcam_HD                        | 12        | 1.63%   |
| Chicony HP HD Camera                                | 12        | 1.63%   |
| Chicony HP HD Webcam                                | 11        | 1.5%    |
| Chicony HD WebCam                                   | 11        | 1.5%    |
| Chicony FJ Camera                                   | 11        | 1.5%    |
| Logitech Webcam C270                                | 10        | 1.36%   |
| Logitech HD Pro Webcam C920                         | 9         | 1.23%   |
| Syntek Integrated Camera                            | 8         | 1.09%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 8         | 1.09%   |
| Samsung Galaxy A5 (MTP)                             | 7         | 0.95%   |
| Lite-On Integrated Camera                           | 7         | 0.95%   |
| Chicony Integrated Camera (1280x720@30)             | 7         | 0.95%   |
| Apple FaceTime HD Camera (Built-in)                 | 7         | 0.95%   |
| Acer Integrated Camera                              | 7         | 0.95%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 6         | 0.82%   |
| Sunplus Integrated_Webcam_HD                        | 6         | 0.82%   |
| Sunplus HD WebCam                                   | 6         | 0.82%   |
| Realtek USB Camera                                  | 6         | 0.82%   |
| Microsoft LifeCam HD-3000                           | 6         | 0.82%   |
| Lite-On HP HD Camera                                | 6         | 0.82%   |
| Chicony USB2.0 HD UVC WebCam                        | 6         | 0.82%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 6         | 0.82%   |
| Chicony Lenovo EasyCamera                           | 6         | 0.82%   |
| Chicony Integrated Camera [ThinkPad]                | 6         | 0.82%   |
| Chicony EasyCamera                                  | 6         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 6         | 0.82%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.68%   |
| Realtek Lenovo EasyCamera                           | 5         | 0.68%   |
| Quanta USB Webcam                                   | 5         | 0.68%   |
| Quanta HP Webcam                                    | 5         | 0.68%   |
| Primax HP HD Webcam [Fixed]                         | 5         | 0.68%   |
| Microdia Integrated Webcam                          | 5         | 0.68%   |
| Logitech StreamCam                                  | 5         | 0.68%   |
| Lenovo Integrated Webcam [R5U877]                   | 5         | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam                       | 5         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 76        | 41.3%   |
| Synaptics                  | 43        | 23.37%  |
| AuthenTec                  | 17        | 9.24%   |
| Shenzhen Goodix Technology | 15        | 8.15%   |
| Upek                       | 13        | 7.07%   |
| STMicroelectronics         | 9         | 4.89%   |
| LighTuning Technology      | 6         | 3.26%   |
| Elan Microelectronics      | 4         | 2.17%   |
| Microsoft                  | 1         | 0.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 13.04%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 22        | 11.96%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 7.07%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 5.98%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 4.89%   |
| AuthenTec AES2810                                                          | 9         | 4.89%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 4.35%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 4.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 3.8%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 3.8%    |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 3.8%    |
| Shenzhen Goodix FingerPrint                                                | 5         | 2.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 2.72%   |
| Validity Sensors VFS491                                                    | 4         | 2.17%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.63%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.63%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.63%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.09%   |
| Synaptics  WBDI                                                            | 2         | 1.09%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.09%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.09%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.54%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.54%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.54%   |
| Synaptics WBDI                                                             | 1         | 0.54%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.54%   |
| Synaptics UWP WBDI                                                         | 1         | 0.54%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.54%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.54%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.54%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.54%   |
| AuthenTec AES1600                                                          | 1         | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 56        | 43.41%  |
| Broadcom                  | 36        | 27.91%  |
| Lenovo                    | 10        | 7.75%   |
| Upek                      | 7         | 5.43%   |
| O2 Micro                  | 7         | 5.43%   |
| SCM Microsystems          | 6         | 4.65%   |
| Fujitsu Siemens Computers | 3         | 2.33%   |
| OmniKey                   | 2         | 1.55%   |
| Advanced Card Systems     | 2         | 1.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 56        | 43.41%  |
| Broadcom 5880                                                                | 12        | 9.3%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 8.53%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 7.75%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 5.43%   |
| Broadcom 58200                                                               | 7         | 5.43%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 4.65%   |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 3.88%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 2.33%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 3         | 2.33%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 1.55%   |
| OmniKey CardMan 1021                                                         | 2         | 1.55%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 1.55%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.78%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.78%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 955       | 66.83%  |
| 1     | 359       | 25.12%  |
| 2     | 89        | 6.23%   |
| 3     | 17        | 1.19%   |
| 5     | 4         | 0.28%   |
| 4     | 3         | 0.21%   |
| 6     | 2         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 183       | 30.15%  |
| Chipcard                 | 114       | 18.78%  |
| Graphics card            | 106       | 17.46%  |
| Net/wireless             | 65        | 10.71%  |
| Communication controller | 23        | 3.79%   |
| Multimedia controller    | 22        | 3.62%   |
| Camera                   | 15        | 2.47%   |
| Bluetooth                | 15        | 2.47%   |
| Unassigned class         | 14        | 2.31%   |
| Storage                  | 9         | 1.48%   |
| Net/ethernet             | 9         | 1.48%   |
| Sound                    | 8         | 1.32%   |
| Card reader              | 8         | 1.32%   |
| Storage/raid             | 5         | 0.82%   |
| Modem                    | 3         | 0.49%   |
| Firewire controller      | 3         | 0.49%   |
| Storage/nvme             | 2         | 0.33%   |
| Network                  | 1         | 0.16%   |
| Flash memory             | 1         | 0.16%   |
| Dvb card                 | 1         | 0.16%   |

