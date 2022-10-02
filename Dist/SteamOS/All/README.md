SteamOS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for SteamOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/SteamOS/Desktop/README.md) and [notebooks](/Dist/SteamOS/Notebook/README.md).

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

Total: 343

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [3e25da0356](https://linux-hardware.org/?probe=3e25da0356) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [12f0d9358a](https://linux-hardware.org/?probe=12f0d9358a) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [9ea6c15d28](https://linux-hardware.org/?probe=9ea6c15d28) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [dab0a00c02](https://linux-hardware.org/?probe=dab0a00c02) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [4d1b722861](https://linux-hardware.org/?probe=4d1b722861) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9737fcadf](https://linux-hardware.org/?probe=e9737fcadf) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [5e7ec518d4](https://linux-hardware.org/?probe=5e7ec518d4) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [a031955ffb](https://linux-hardware.org/?probe=a031955ffb) | Sep 30, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [5746aa7609](https://linux-hardware.org/?probe=5746aa7609) | Sep 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [66731152dd](https://linux-hardware.org/?probe=66731152dd) | Sep 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [679b3600fa](https://linux-hardware.org/?probe=679b3600fa) | Sep 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [92b774ed77](https://linux-hardware.org/?probe=92b774ed77) | Sep 29, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [46e48bc4c1](https://linux-hardware.org/?probe=46e48bc4c1) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| GPD           | G1619-04                    | Notebook    | [9e99ae15fb](https://linux-hardware.org/?probe=9e99ae15fb) | Sep 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [9a2af6352a](https://linux-hardware.org/?probe=9a2af6352a) | Sep 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [0f1c8fad1c](https://linux-hardware.org/?probe=0f1c8fad1c) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [c3305d9bff](https://linux-hardware.org/?probe=c3305d9bff) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [8c94cd9bd3](https://linux-hardware.org/?probe=8c94cd9bd3) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [315719a312](https://linux-hardware.org/?probe=315719a312) | Sep 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [f5183f3eed](https://linux-hardware.org/?probe=f5183f3eed) | Sep 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [6ddd668003](https://linux-hardware.org/?probe=6ddd668003) | Sep 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7a00d659bd](https://linux-hardware.org/?probe=7a00d659bd) | Sep 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [b70be12594](https://linux-hardware.org/?probe=b70be12594) | Sep 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5d02471757](https://linux-hardware.org/?probe=5d02471757) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [d03b845c90](https://linux-hardware.org/?probe=d03b845c90) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ca6d2abcd9](https://linux-hardware.org/?probe=ca6d2abcd9) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [bea162d6e3](https://linux-hardware.org/?probe=bea162d6e3) | Sep 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [ce15d6d4bb](https://linux-hardware.org/?probe=ce15d6d4bb) | Sep 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [f9230d9e82](https://linux-hardware.org/?probe=f9230d9e82) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [a39be03b34](https://linux-hardware.org/?probe=a39be03b34) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c7bc3efcf](https://linux-hardware.org/?probe=1c7bc3efcf) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [7bc45b1077](https://linux-hardware.org/?probe=7bc45b1077) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [721ede2e11](https://linux-hardware.org/?probe=721ede2e11) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [83ed33f7e6](https://linux-hardware.org/?probe=83ed33f7e6) | Sep 20, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [696b4e525e](https://linux-hardware.org/?probe=696b4e525e) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [e60653a4c7](https://linux-hardware.org/?probe=e60653a4c7) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [090e33f643](https://linux-hardware.org/?probe=090e33f643) | Sep 20, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [8d8440548e](https://linux-hardware.org/?probe=8d8440548e) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [919ae4fe6c](https://linux-hardware.org/?probe=919ae4fe6c) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [5ed6e54010](https://linux-hardware.org/?probe=5ed6e54010) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [84051314e8](https://linux-hardware.org/?probe=84051314e8) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [de74f87be5](https://linux-hardware.org/?probe=de74f87be5) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [8273135785](https://linux-hardware.org/?probe=8273135785) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [4b802a9fe9](https://linux-hardware.org/?probe=4b802a9fe9) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [e65c41605f](https://linux-hardware.org/?probe=e65c41605f) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [b2a1aea8e2](https://linux-hardware.org/?probe=b2a1aea8e2) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [b667f00856](https://linux-hardware.org/?probe=b667f00856) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [221fd3ae1c](https://linux-hardware.org/?probe=221fd3ae1c) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [c4dd2bf91f](https://linux-hardware.org/?probe=c4dd2bf91f) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [0db4b64dcd](https://linux-hardware.org/?probe=0db4b64dcd) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [4540c4e930](https://linux-hardware.org/?probe=4540c4e930) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [47ac328960](https://linux-hardware.org/?probe=47ac328960) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [28a40721a8](https://linux-hardware.org/?probe=28a40721a8) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [f686754b27](https://linux-hardware.org/?probe=f686754b27) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [9adc000021](https://linux-hardware.org/?probe=9adc000021) | Sep 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9493095ab1](https://linux-hardware.org/?probe=9493095ab1) | Sep 15, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [9919cebdfe](https://linux-hardware.org/?probe=9919cebdfe) | Sep 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9817414c4e](https://linux-hardware.org/?probe=9817414c4e) | Sep 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [0925a55100](https://linux-hardware.org/?probe=0925a55100) | Sep 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [b2b312e843](https://linux-hardware.org/?probe=b2b312e843) | Sep 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [694e9a60ad](https://linux-hardware.org/?probe=694e9a60ad) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [438ec3fe41](https://linux-hardware.org/?probe=438ec3fe41) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| MSI           | 970A-G46                    | Desktop     | [5f7482fe88](https://linux-hardware.org/?probe=5f7482fe88) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [2c95ed7c92](https://linux-hardware.org/?probe=2c95ed7c92) | Sep 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [17eea2b641](https://linux-hardware.org/?probe=17eea2b641) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [49694d92f6](https://linux-hardware.org/?probe=49694d92f6) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [48df4850fe](https://linux-hardware.org/?probe=48df4850fe) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [c63b3ff391](https://linux-hardware.org/?probe=c63b3ff391) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [cb5ede9c6f](https://linux-hardware.org/?probe=cb5ede9c6f) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [9fce9d23c8](https://linux-hardware.org/?probe=9fce9d23c8) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [7d45c49609](https://linux-hardware.org/?probe=7d45c49609) | Sep 08, 2022 |
| Microsoft     | Surface Pro 8               | Tablet      | [e450ddeea6](https://linux-hardware.org/?probe=e450ddeea6) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus S17 GX703HS... | Notebook    | [041c6dac05](https://linux-hardware.org/?probe=041c6dac05) | Sep 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3c4865fc8c](https://linux-hardware.org/?probe=3c4865fc8c) | Sep 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [1669287cbb](https://linux-hardware.org/?probe=1669287cbb) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [47baad2eed](https://linux-hardware.org/?probe=47baad2eed) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb15307366](https://linux-hardware.org/?probe=eb15307366) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [8cd669599d](https://linux-hardware.org/?probe=8cd669599d) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [090d406ac3](https://linux-hardware.org/?probe=090d406ac3) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [3f0eb4cd71](https://linux-hardware.org/?probe=3f0eb4cd71) | Sep 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [04c7e44198](https://linux-hardware.org/?probe=04c7e44198) | Sep 05, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [fc14fdd03a](https://linux-hardware.org/?probe=fc14fdd03a) | Sep 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [584ea1ade0](https://linux-hardware.org/?probe=584ea1ade0) | Sep 05, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [2d99107aa6](https://linux-hardware.org/?probe=2d99107aa6) | Sep 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [bf34e42b02](https://linux-hardware.org/?probe=bf34e42b02) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [f9942c8a6b](https://linux-hardware.org/?probe=f9942c8a6b) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [93771f5a6b](https://linux-hardware.org/?probe=93771f5a6b) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [08728d3dc1](https://linux-hardware.org/?probe=08728d3dc1) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [a8038907ed](https://linux-hardware.org/?probe=a8038907ed) | Sep 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [f35ef3a2e1](https://linux-hardware.org/?probe=f35ef3a2e1) | Sep 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [e12248df34](https://linux-hardware.org/?probe=e12248df34) | Sep 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [f4142b2ff8](https://linux-hardware.org/?probe=f4142b2ff8) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [c0094f39c5](https://linux-hardware.org/?probe=c0094f39c5) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [b3b1ffd7ff](https://linux-hardware.org/?probe=b3b1ffd7ff) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [3fdc8df5b2](https://linux-hardware.org/?probe=3fdc8df5b2) | Sep 02, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bdae2c60cd](https://linux-hardware.org/?probe=bdae2c60cd) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [c89533e9a2](https://linux-hardware.org/?probe=c89533e9a2) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [c348c06118](https://linux-hardware.org/?probe=c348c06118) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [5a2483051c](https://linux-hardware.org/?probe=5a2483051c) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b928ad313](https://linux-hardware.org/?probe=0b928ad313) | Aug 31, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1f4a6a9ec3](https://linux-hardware.org/?probe=1f4a6a9ec3) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [dbc549504c](https://linux-hardware.org/?probe=dbc549504c) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [1b38f48059](https://linux-hardware.org/?probe=1b38f48059) | Aug 30, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [6d2717b230](https://linux-hardware.org/?probe=6d2717b230) | Aug 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [40b9dd39a6](https://linux-hardware.org/?probe=40b9dd39a6) | Aug 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [ea6506cc93](https://linux-hardware.org/?probe=ea6506cc93) | Aug 30, 2022 |
| MSI           | MS-B9201                    | Desktop     | [b5c80c8c2c](https://linux-hardware.org/?probe=b5c80c8c2c) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [844a0c00e2](https://linux-hardware.org/?probe=844a0c00e2) | Aug 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [830c22afde](https://linux-hardware.org/?probe=830c22afde) | Aug 29, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [1763ee1dd0](https://linux-hardware.org/?probe=1763ee1dd0) | Aug 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [43ec7fb445](https://linux-hardware.org/?probe=43ec7fb445) | Aug 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [3848655fce](https://linux-hardware.org/?probe=3848655fce) | Aug 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [9e3df56c3b](https://linux-hardware.org/?probe=9e3df56c3b) | Aug 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [cd6744821b](https://linux-hardware.org/?probe=cd6744821b) | Aug 27, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [521dd85c98](https://linux-hardware.org/?probe=521dd85c98) | Aug 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [8027445785](https://linux-hardware.org/?probe=8027445785) | Aug 26, 2022 |
| Dell          | Precision 7720              | Notebook    | [7fafc0e50b](https://linux-hardware.org/?probe=7fafc0e50b) | Aug 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [447edaff49](https://linux-hardware.org/?probe=447edaff49) | Aug 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [67b791eb17](https://linux-hardware.org/?probe=67b791eb17) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [ebd183fc4b](https://linux-hardware.org/?probe=ebd183fc4b) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [b74760105e](https://linux-hardware.org/?probe=b74760105e) | Aug 25, 2022 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [663bc0a517](https://linux-hardware.org/?probe=663bc0a517) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [5064c9f57b](https://linux-hardware.org/?probe=5064c9f57b) | Aug 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [de49ccefa5](https://linux-hardware.org/?probe=de49ccefa5) | Aug 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c88b729d3](https://linux-hardware.org/?probe=4c88b729d3) | Aug 23, 2022 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e934af2a60](https://linux-hardware.org/?probe=e934af2a60) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ba1940016e](https://linux-hardware.org/?probe=ba1940016e) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [161cc0c135](https://linux-hardware.org/?probe=161cc0c135) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [078b8e8ff1](https://linux-hardware.org/?probe=078b8e8ff1) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [04b0de9007](https://linux-hardware.org/?probe=04b0de9007) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c25a3bf8a](https://linux-hardware.org/?probe=1c25a3bf8a) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [bc83cf9f77](https://linux-hardware.org/?probe=bc83cf9f77) | Aug 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [36124147ef](https://linux-hardware.org/?probe=36124147ef) | Aug 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [d6b92d1aa0](https://linux-hardware.org/?probe=d6b92d1aa0) | Aug 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [bff4d1ca46](https://linux-hardware.org/?probe=bff4d1ca46) | Aug 19, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9661c799c9](https://linux-hardware.org/?probe=9661c799c9) | Aug 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [87f3603202](https://linux-hardware.org/?probe=87f3603202) | Aug 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [f0dc30e9f8](https://linux-hardware.org/?probe=f0dc30e9f8) | Aug 17, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [af4a593873](https://linux-hardware.org/?probe=af4a593873) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [c395a0f9db](https://linux-hardware.org/?probe=c395a0f9db) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [90ac03e747](https://linux-hardware.org/?probe=90ac03e747) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [53429d945b](https://linux-hardware.org/?probe=53429d945b) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9ab7a2b695](https://linux-hardware.org/?probe=9ab7a2b695) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [2adcfce1c0](https://linux-hardware.org/?probe=2adcfce1c0) | Aug 14, 2022 |
| MSI           | MS-B9351                    | Desktop     | [a5b1950761](https://linux-hardware.org/?probe=a5b1950761) | Aug 14, 2022 |
| MSI           | MS-B9351                    | Desktop     | [fbf08d2d76](https://linux-hardware.org/?probe=fbf08d2d76) | Aug 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9f1f10a4c](https://linux-hardware.org/?probe=e9f1f10a4c) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [50596cb93b](https://linux-hardware.org/?probe=50596cb93b) | Aug 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [54ea6926a0](https://linux-hardware.org/?probe=54ea6926a0) | Aug 13, 2022 |
| HP            | 2B3E                        | All in one  | [1ba4759f2c](https://linux-hardware.org/?probe=1ba4759f2c) | Aug 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [3a1e95f5d5](https://linux-hardware.org/?probe=3a1e95f5d5) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [b63f9aedab](https://linux-hardware.org/?probe=b63f9aedab) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [822737452b](https://linux-hardware.org/?probe=822737452b) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [9839802d27](https://linux-hardware.org/?probe=9839802d27) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [6b9bfad898](https://linux-hardware.org/?probe=6b9bfad898) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c6e02c54e7](https://linux-hardware.org/?probe=c6e02c54e7) | Aug 11, 2022 |
| HP            | Laptop 14z-fq0000           | Notebook    | [9c62f8d392](https://linux-hardware.org/?probe=9c62f8d392) | Aug 11, 2022 |
| Microsoft     | Surface Pro 8               | Tablet      | [a5f743f641](https://linux-hardware.org/?probe=a5f743f641) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [90e751b5cf](https://linux-hardware.org/?probe=90e751b5cf) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [6223a43fe2](https://linux-hardware.org/?probe=6223a43fe2) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [2cec170e55](https://linux-hardware.org/?probe=2cec170e55) | Aug 10, 2022 |
| AMI           | Unknown                     | Notebook    | [5cee81ed21](https://linux-hardware.org/?probe=5cee81ed21) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [68214f1af2](https://linux-hardware.org/?probe=68214f1af2) | Aug 10, 2022 |
| AMI           | Unknown                     | Notebook    | [7752037bab](https://linux-hardware.org/?probe=7752037bab) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [e4914b879a](https://linux-hardware.org/?probe=e4914b879a) | Aug 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [a5b1208abc](https://linux-hardware.org/?probe=a5b1208abc) | Aug 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [a50e78265a](https://linux-hardware.org/?probe=a50e78265a) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8ef9609a7](https://linux-hardware.org/?probe=d8ef9609a7) | Aug 07, 2022 |
| Dell          | 00F82W A00                  | Desktop     | [8e74c57731](https://linux-hardware.org/?probe=8e74c57731) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [64a0d92417](https://linux-hardware.org/?probe=64a0d92417) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [b6c7ee76fa](https://linux-hardware.org/?probe=b6c7ee76fa) | Aug 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [6bbc4f3d0a](https://linux-hardware.org/?probe=6bbc4f3d0a) | Aug 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [d15c62e29a](https://linux-hardware.org/?probe=d15c62e29a) | Aug 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [6f76f9d91a](https://linux-hardware.org/?probe=6f76f9d91a) | Aug 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [4403a80bdc](https://linux-hardware.org/?probe=4403a80bdc) | Aug 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [8689254ee7](https://linux-hardware.org/?probe=8689254ee7) | Aug 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [bfddbf1d22](https://linux-hardware.org/?probe=bfddbf1d22) | Aug 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [fdb514a999](https://linux-hardware.org/?probe=fdb514a999) | Aug 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [e4c6300b68](https://linux-hardware.org/?probe=e4c6300b68) | Aug 01, 2022 |
| Gigabyte      | H310M S2V                   | Desktop     | [329d2071a9](https://linux-hardware.org/?probe=329d2071a9) | Aug 01, 2022 |
| GPD           | G1619-02                    | Notebook    | [c61c4280c8](https://linux-hardware.org/?probe=c61c4280c8) | Jul 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [ee3b662083](https://linux-hardware.org/?probe=ee3b662083) | Jul 30, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [9a18d7476f](https://linux-hardware.org/?probe=9a18d7476f) | Jul 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [225e2c825e](https://linux-hardware.org/?probe=225e2c825e) | Jul 29, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [4a6c9ef157](https://linux-hardware.org/?probe=4a6c9ef157) | Jul 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [dffaa71aed](https://linux-hardware.org/?probe=dffaa71aed) | Jul 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [35608b206c](https://linux-hardware.org/?probe=35608b206c) | Jul 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [e35fa6e699](https://linux-hardware.org/?probe=e35fa6e699) | Jul 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [f43cbe28e9](https://linux-hardware.org/?probe=f43cbe28e9) | Jul 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4e4413f9b](https://linux-hardware.org/?probe=d4e4413f9b) | Jul 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [9c34e91c79](https://linux-hardware.org/?probe=9c34e91c79) | Jul 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [b605f923c6](https://linux-hardware.org/?probe=b605f923c6) | Jul 25, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [6b300beb70](https://linux-hardware.org/?probe=6b300beb70) | Jul 25, 2022 |
| ASRock        | A520M-ITX/ac                | Desktop     | [876c779461](https://linux-hardware.org/?probe=876c779461) | Jul 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [ce14e41b96](https://linux-hardware.org/?probe=ce14e41b96) | Jul 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e7b7cb8cd](https://linux-hardware.org/?probe=3e7b7cb8cd) | Jul 23, 2022 |
| Alienware     | m17                         | Notebook    | [e14db26b9b](https://linux-hardware.org/?probe=e14db26b9b) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ca07489d53](https://linux-hardware.org/?probe=ca07489d53) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d0db23de3](https://linux-hardware.org/?probe=2d0db23de3) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [4aece18875](https://linux-hardware.org/?probe=4aece18875) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [44dca72cbb](https://linux-hardware.org/?probe=44dca72cbb) | Jul 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [96af389676](https://linux-hardware.org/?probe=96af389676) | Jul 22, 2022 |
| ASRock        | X570 Extreme4 WiFi ax       | Notebook    | [bc52038c74](https://linux-hardware.org/?probe=bc52038c74) | Jul 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [0cd166bdb1](https://linux-hardware.org/?probe=0cd166bdb1) | Jul 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [02c47a57e5](https://linux-hardware.org/?probe=02c47a57e5) | Jul 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [2c1ad04467](https://linux-hardware.org/?probe=2c1ad04467) | Jul 18, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [7f27efe00e](https://linux-hardware.org/?probe=7f27efe00e) | Jul 17, 2022 |
| HP            | Pavilion 17                 | Notebook    | [722f4eb4a9](https://linux-hardware.org/?probe=722f4eb4a9) | Jul 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [b639365efd](https://linux-hardware.org/?probe=b639365efd) | Jul 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [eec9897935](https://linux-hardware.org/?probe=eec9897935) | Jul 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4be0d94b4](https://linux-hardware.org/?probe=d4be0d94b4) | Jul 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [d2f117e7f3](https://linux-hardware.org/?probe=d2f117e7f3) | Jul 14, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [e157e6d524](https://linux-hardware.org/?probe=e157e6d524) | Jul 14, 2022 |
| AYANEO        | NEXT Pro                    | Tablet      | [12b2ede47c](https://linux-hardware.org/?probe=12b2ede47c) | Jul 12, 2022 |
| AYANEO        | NEXT Pro                    | Tablet      | [4dc9fd4b9e](https://linux-hardware.org/?probe=4dc9fd4b9e) | Jul 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [f7d66c8d35](https://linux-hardware.org/?probe=f7d66c8d35) | Jul 10, 2022 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [2f3e59dc30](https://linux-hardware.org/?probe=2f3e59dc30) | Jul 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [0c2ea27c49](https://linux-hardware.org/?probe=0c2ea27c49) | Jul 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [98711d54c1](https://linux-hardware.org/?probe=98711d54c1) | Jul 08, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [c3c73948f5](https://linux-hardware.org/?probe=c3c73948f5) | Jul 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3ede093138](https://linux-hardware.org/?probe=3ede093138) | Jul 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [663562cc6b](https://linux-hardware.org/?probe=663562cc6b) | Jul 06, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [61eaf99aca](https://linux-hardware.org/?probe=61eaf99aca) | Jul 05, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [812733dd89](https://linux-hardware.org/?probe=812733dd89) | Jul 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [e640bab55c](https://linux-hardware.org/?probe=e640bab55c) | Jul 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [0bd46afcda](https://linux-hardware.org/?probe=0bd46afcda) | Jul 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [ac0c161f66](https://linux-hardware.org/?probe=ac0c161f66) | Jul 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [c591d23b4d](https://linux-hardware.org/?probe=c591d23b4d) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [261590e542](https://linux-hardware.org/?probe=261590e542) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [7c233f0a07](https://linux-hardware.org/?probe=7c233f0a07) | Jun 29, 2022 |
| HP            | x2 210 G2                   | Tablet      | [812530aed8](https://linux-hardware.org/?probe=812530aed8) | Jun 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [e80815c8d4](https://linux-hardware.org/?probe=e80815c8d4) | Jun 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [e51f5d8645](https://linux-hardware.org/?probe=e51f5d8645) | Jun 26, 2022 |
| Alienware     | 02XRCM A01                  | Desktop     | [c70647bab0](https://linux-hardware.org/?probe=c70647bab0) | Jun 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [b4dd19f939](https://linux-hardware.org/?probe=b4dd19f939) | Jun 25, 2022 |
| AZW           | SER V01                     | Mini pc     | [295a32d26e](https://linux-hardware.org/?probe=295a32d26e) | Jun 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [c9ed3cf311](https://linux-hardware.org/?probe=c9ed3cf311) | Jun 23, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [1a568c2e5f](https://linux-hardware.org/?probe=1a568c2e5f) | Jun 23, 2022 |
| ASUSTek       | Q524UQK                     | Convertible | [fd5f128747](https://linux-hardware.org/?probe=fd5f128747) | Jun 23, 2022 |
| Dell          | G15 5510                    | Notebook    | [9c5777f505](https://linux-hardware.org/?probe=9c5777f505) | Jun 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [262a7f0cd4](https://linux-hardware.org/?probe=262a7f0cd4) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [f8722866b2](https://linux-hardware.org/?probe=f8722866b2) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [aa18022bce](https://linux-hardware.org/?probe=aa18022bce) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [000682313d](https://linux-hardware.org/?probe=000682313d) | Jun 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [363ab9e4ea](https://linux-hardware.org/?probe=363ab9e4ea) | Jun 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [dd5765a418](https://linux-hardware.org/?probe=dd5765a418) | Jun 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [8e293bb4b1](https://linux-hardware.org/?probe=8e293bb4b1) | Jun 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [ff0ce08944](https://linux-hardware.org/?probe=ff0ce08944) | Jun 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [68a581ae0b](https://linux-hardware.org/?probe=68a581ae0b) | Jun 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [df3f1b5d8f](https://linux-hardware.org/?probe=df3f1b5d8f) | Jun 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [17406c8741](https://linux-hardware.org/?probe=17406c8741) | Jun 11, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [7ccfe2d3a7](https://linux-hardware.org/?probe=7ccfe2d3a7) | Jun 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [715e914cba](https://linux-hardware.org/?probe=715e914cba) | Jun 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [2fb1bfad12](https://linux-hardware.org/?probe=2fb1bfad12) | Jun 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [322bdc2ce3](https://linux-hardware.org/?probe=322bdc2ce3) | Jun 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [780d6b923a](https://linux-hardware.org/?probe=780d6b923a) | Jun 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b3a08001ed](https://linux-hardware.org/?probe=b3a08001ed) | Jun 01, 2022 |
| ASRock        | B550 PG Velocita            | Desktop     | [0d7f71a24d](https://linux-hardware.org/?probe=0d7f71a24d) | May 30, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [e415de106f](https://linux-hardware.org/?probe=e415de106f) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [0af4b9c805](https://linux-hardware.org/?probe=0af4b9c805) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [06b56d54d4](https://linux-hardware.org/?probe=06b56d54d4) | May 28, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e966da4f8](https://linux-hardware.org/?probe=1e966da4f8) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [c716690aa2](https://linux-hardware.org/?probe=c716690aa2) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [43f315aa0c](https://linux-hardware.org/?probe=43f315aa0c) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [d4bef1e450](https://linux-hardware.org/?probe=d4bef1e450) | May 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b672eefb50](https://linux-hardware.org/?probe=b672eefb50) | May 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [dee0bbedd1](https://linux-hardware.org/?probe=dee0bbedd1) | May 25, 2022 |
| HP            | 8158 A01                    | Mini pc     | [0d32a2b2e3](https://linux-hardware.org/?probe=0d32a2b2e3) | May 24, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [da9b5c2be2](https://linux-hardware.org/?probe=da9b5c2be2) | May 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [c34173715a](https://linux-hardware.org/?probe=c34173715a) | May 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [6ca95b630c](https://linux-hardware.org/?probe=6ca95b630c) | May 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [b5d37bf4f2](https://linux-hardware.org/?probe=b5d37bf4f2) | May 22, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [fc970670a8](https://linux-hardware.org/?probe=fc970670a8) | May 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [d706d00651](https://linux-hardware.org/?probe=d706d00651) | May 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [317e492fa3](https://linux-hardware.org/?probe=317e492fa3) | May 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [79f6db1d69](https://linux-hardware.org/?probe=79f6db1d69) | May 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [771539d18d](https://linux-hardware.org/?probe=771539d18d) | May 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c826aed5e](https://linux-hardware.org/?probe=1c826aed5e) | Apr 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c43342014](https://linux-hardware.org/?probe=4c43342014) | Apr 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [8564bded7f](https://linux-hardware.org/?probe=8564bded7f) | Apr 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [d761657c3a](https://linux-hardware.org/?probe=d761657c3a) | Apr 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [f2e59fcb97](https://linux-hardware.org/?probe=f2e59fcb97) | Apr 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [4f23fab4fd](https://linux-hardware.org/?probe=4f23fab4fd) | Apr 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [ed07e93435](https://linux-hardware.org/?probe=ed07e93435) | Apr 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [48aacdeee8](https://linux-hardware.org/?probe=48aacdeee8) | Apr 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [6a042646dd](https://linux-hardware.org/?probe=6a042646dd) | Apr 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4c9dba2a1](https://linux-hardware.org/?probe=d4c9dba2a1) | Apr 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [852b6fb53a](https://linux-hardware.org/?probe=852b6fb53a) | Apr 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [6129b15fb5](https://linux-hardware.org/?probe=6129b15fb5) | Apr 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [ec05067a1d](https://linux-hardware.org/?probe=ec05067a1d) | Apr 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [180c84c856](https://linux-hardware.org/?probe=180c84c856) | Apr 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8625616de](https://linux-hardware.org/?probe=d8625616de) | Mar 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [d181a912af](https://linux-hardware.org/?probe=d181a912af) | Mar 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b6a21cf35](https://linux-hardware.org/?probe=0b6a21cf35) | Mar 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [85328e8f3d](https://linux-hardware.org/?probe=85328e8f3d) | Mar 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [023aea75e1](https://linux-hardware.org/?probe=023aea75e1) | Mar 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [c7f6388908](https://linux-hardware.org/?probe=c7f6388908) | Mar 11, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| SteamOS 3.3.1                | 89        | 30.27%  |
| SteamOS 3.3                  | 75        | 25.51%  |
| SteamOS 3.2                  | 58        | 19.73%  |
| SteamOS Snapshot             | 26        | 8.84%   |
| SteamOS 3.2 (steamdeck-main) | 14        | 4.76%   |
| SteamOS 3.1                  | 10        | 3.4%    |
| SteamOS 3.4                  | 6         | 2.04%   |
| SteamOS 3.3.2                | 6         | 2.04%   |
| SteamOS Rolling              | 5         | 1.7%    |
| SteamOS                      | 5         | 1.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SteamOS | 284       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| 5.13.0-valve21.1-1-neptune-02211-gc54cda5a36f3     | 92        | 31.08%  |
| 5.13.0-valve15-1-neptune-02197-gf6ec7ad3762a       | 53        | 17.91%  |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 36        | 12.16%  |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 24        | 8.11%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 23        | 7.77%   |
| 5.13.0-valve10.1-1-neptune-02144-g7fffaf925dfb     | 16        | 5.41%   |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 12        | 4.05%   |
| 5.13.0-valve10.3-1-neptune-02176-g5fe416c4acd8     | 12        | 4.05%   |
| 5.13.0-valve21.2-1-neptune                         | 6         | 2.03%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 5         | 1.69%   |
| 5.13.0-valve14-1-neptune-02195-g5b0f749d00fa       | 5         | 1.69%   |
| 5.13.0-valve20-1-neptune-02207-gbd986a7e1c7f       | 4         | 1.35%   |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 3         | 1.01%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2         | 0.68%   |
| 5.16.2-arch1-1                                     | 1         | 0.34%   |
| 5.15.60-1-lts                                      | 1         | 0.34%   |
| 5.15.54-1-lts                                      | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 277       | 97.19%  |
| 5.18.1  | 5         | 1.75%   |
| 5.16.2  | 1         | 0.35%   |
| 5.15.60 | 1         | 0.35%   |
| 5.15.54 | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 277       | 97.19%  |
| 5.18    | 5         | 1.75%   |
| 5.15    | 2         | 0.7%    |
| 5.16    | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 284       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| KDE5      | 281       | 98.6%   |
| gamescope | 2         | 0.7%    |
| Unknown   | 2         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 282       | 98.95%  |
| Wayland | 2         | 0.7%    |
| Unknown | 1         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 279       | 98.24%  |
| SDDM    | 5         | 1.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 246       | 86.32%  |
| en_GB | 6         | 2.11%   |
| de_DE | 6         | 2.11%   |
| fr_FR | 4         | 1.4%    |
| an_ES | 4         | 1.4%    |
| en_DE | 3         | 1.05%   |
| zh_CN | 2         | 0.7%    |
| pt_PT | 2         | 0.7%    |
| sk_SK | 1         | 0.35%   |
| pt_BR | 1         | 0.35%   |
| pl_PL | 1         | 0.35%   |
| nl_NL | 1         | 0.35%   |
| it_IT | 1         | 0.35%   |
| et_EE | 1         | 0.35%   |
| es_ES | 1         | 0.35%   |
| en_NL | 1         | 0.35%   |
| en_IE | 1         | 0.35%   |
| en_CA | 1         | 0.35%   |
| C     | 1         | 0.35%   |
| ba_RU | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 277       | 97.54%  |
| EFI  | 7         | 2.46%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 283       | 99.65%  |
| Ext4  | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 277       | 97.54%  |
| GPT     | 7         | 2.46%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 278       | 97.89%  |
| Yes       | 6         | 2.11%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 283       | 99.65%  |
| Yes       | 1         | 0.35%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Valve                  | 215       | 75.7%   |
| ASUSTek Computer       | 13        | 4.58%   |
| Gigabyte Technology    | 9         | 3.17%   |
| Hewlett-Packard        | 8         | 2.82%   |
| MSI                    | 6         | 2.11%   |
| Dell                   | 6         | 2.11%   |
| ASRock                 | 6         | 2.11%   |
| Lenovo                 | 5         | 1.76%   |
| Apple                  | 3         | 1.06%   |
| GPD                    | 2         | 0.7%    |
| Alienware              | 2         | 0.7%    |
| Acer                   | 2         | 0.7%    |
| Samsung Electronics    | 1         | 0.35%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.35%   |
| Microsoft              | 1         | 0.35%   |
| AZW                    | 1         | 0.35%   |
| AYANEO                 | 1         | 0.35%   |
| AMI                    | 1         | 0.35%   |
| Unknown                | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Valve Jupiter                          | 215       | 75.7%   |
| ASUS All Series                        | 3         | 1.06%   |
| Unknown                                | 2         | 0.7%    |
| Samsung 950XDB/951XDB/950XDY           | 1         | 0.35%   |
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER     | 1         | 0.35%   |
| MSI MS-7C02                            | 1         | 0.35%   |
| MSI MS-7B79                            | 1         | 0.35%   |
| MSI MS-7B09                            | 1         | 0.35%   |
| MSI MS-7693                            | 1         | 0.35%   |
| MSI MPG H510 Trident 3 (MS-B935)       | 1         | 0.35%   |
| MSI H310 Gaming Trident3 (MS-B920)     | 1         | 0.35%   |
| Microsoft Surface Pro 8                | 1         | 0.35%   |
| Lenovo ThinkCentre M720q 10T7002CUS    | 1         | 0.35%   |
| Lenovo ThinkBook 13s G3 ACN 20YA       | 1         | 0.35%   |
| Lenovo Legion Y740-15IRHg 81UH         | 1         | 0.35%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 0.35%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 0.35%   |
| HP x2 210 G2                           | 1         | 0.35%   |
| HP t630 Thin Client                    | 1         | 0.35%   |
| HP Pavilion x360 Convertible 14-dy0xxx | 1         | 0.35%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 1         | 0.35%   |
| HP Pavilion Gaming Laptop 15-dk0xxx    | 1         | 0.35%   |
| HP Pavilion 17                         | 1         | 0.35%   |
| HP Laptop 14z-fq0000                   | 1         | 0.35%   |
| HP 27-p055na                           | 1         | 0.35%   |
| GPD G1619-04                           | 1         | 0.35%   |
| GPD G1619-02                           | 1         | 0.35%   |
| Gigabyte X570 I AORUS PRO WIFI         | 1         | 0.35%   |
| Gigabyte X570 GAMING X                 | 1         | 0.35%   |
| Gigabyte MBB-670016                    | 1         | 0.35%   |
| Gigabyte H310M S2V 2.0                 | 1         | 0.35%   |
| Gigabyte H170N-WIFI                    | 1         | 0.35%   |
| Gigabyte B560M AORUS PRO               | 1         | 0.35%   |
| Gigabyte B550 GAMING X V2              | 1         | 0.35%   |
| Gigabyte B450 AORUS M                  | 1         | 0.35%   |
| Gigabyte AB350-Gaming 3                | 1         | 0.35%   |
| Dell XPS 15 9570                       | 1         | 0.35%   |
| Dell XPS 13 9360                       | 1         | 0.35%   |
| Dell Precision Tower 5810              | 1         | 0.35%   |
| Dell Precision 7720                    | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Valve Jupiter              | 215       | 75.7%   |
| HP Pavilion                | 4         | 1.41%   |
| ASUS All                   | 3         | 1.06%   |
| Gigabyte X570              | 2         | 0.7%    |
| Dell XPS                   | 2         | 0.7%    |
| Dell Precision             | 2         | 0.7%    |
| ASUS ROG                   | 2         | 0.7%    |
| ASUS PRIME                 | 2         | 0.7%    |
| ASRock X570                | 2         | 0.7%    |
| Acer Aspire                | 2         | 0.7%    |
| Unknown                    | 2         | 0.7%    |
| Samsung 950XDB             | 1         | 0.35%   |
| ONE-NETBOOK TECHNOLOGY ONE | 1         | 0.35%   |
| MSI MS-7C02                | 1         | 0.35%   |
| MSI MS-7B79                | 1         | 0.35%   |
| MSI MS-7B09                | 1         | 0.35%   |
| MSI MS-7693                | 1         | 0.35%   |
| MSI MPG                    | 1         | 0.35%   |
| MSI H310                   | 1         | 0.35%   |
| Microsoft Surface          | 1         | 0.35%   |
| Lenovo ThinkCentre         | 1         | 0.35%   |
| Lenovo ThinkBook           | 1         | 0.35%   |
| Lenovo Legion              | 1         | 0.35%   |
| Lenovo IdeaPadFlex         | 1         | 0.35%   |
| Lenovo IdeaPad             | 1         | 0.35%   |
| HP x2                      | 1         | 0.35%   |
| HP t630                    | 1         | 0.35%   |
| HP Laptop                  | 1         | 0.35%   |
| HP 27-p055na               | 1         | 0.35%   |
| GPD G1619-04               | 1         | 0.35%   |
| GPD G1619-02               | 1         | 0.35%   |
| Gigabyte MBB-670016        | 1         | 0.35%   |
| Gigabyte H310M             | 1         | 0.35%   |
| Gigabyte H170N-WIFI        | 1         | 0.35%   |
| Gigabyte B560M             | 1         | 0.35%   |
| Gigabyte B550              | 1         | 0.35%   |
| Gigabyte B450              | 1         | 0.35%   |
| Gigabyte AB350-Gaming      | 1         | 0.35%   |
| Dell OptiPlex              | 1         | 0.35%   |
| Dell G15                   | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 208       | 73.24%  |
| 2021    | 16        | 5.63%   |
| Unknown | 12        | 4.23%   |
| 2020    | 11        | 3.87%   |
| 2019    | 10        | 3.52%   |
| 2018    | 7         | 2.46%   |
| 2017    | 6         | 2.11%   |
| 2016    | 6         | 2.11%   |
| 2013    | 4         | 1.41%   |
| 2012    | 2         | 0.7%    |
| 2015    | 1         | 0.35%   |
| 2014    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 236       | 83.1%   |
| Desktop     | 34        | 11.97%  |
| Mini pc     | 5         | 1.76%   |
| Tablet      | 4         | 1.41%   |
| Convertible | 3         | 1.06%   |
| All in one  | 2         | 0.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 284       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 284       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 226       | 79.58%  |
| 16.01-24.0  | 27        | 9.51%   |
| 4.01-8.0    | 10        | 3.52%   |
| 32.01-64.0  | 10        | 3.52%   |
| 24.01-32.0  | 5         | 1.76%   |
| 64.01-256.0 | 4         | 1.41%   |
| 3.01-4.0    | 2         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 146       | 49.66%  |
| 3.01-4.0 | 70        | 23.81%  |
| 4.01-8.0 | 41        | 13.95%  |
| 1.01-2.0 | 37        | 12.59%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 154       | 53.47%  |
| 1      | 107       | 37.15%  |
| 3      | 17        | 5.9%    |
| 4      | 5         | 1.74%   |
| 5      | 2         | 0.69%   |
| 7      | 1         | 0.35%   |
| 6      | 1         | 0.35%   |
| 0      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 277       | 97.54%  |
| Yes       | 7         | 2.46%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 181       | 62.85%  |
| Yes       | 107       | 37.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 269       | 94.72%  |
| No        | 15        | 5.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 260       | 91.55%  |
| No        | 24        | 8.45%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 135       | 47.54%  |
| UK          | 31        | 10.92%  |
| Germany     | 26        | 9.15%   |
| Canada      | 18        | 6.34%   |
| Spain       | 10        | 3.52%   |
| France      | 9         | 3.17%   |
| Poland      | 6         | 2.11%   |
| Netherlands | 6         | 2.11%   |
| Italy       | 4         | 1.41%   |
| Czechia     | 3         | 1.06%   |
| Australia   | 3         | 1.06%   |
| Slovakia    | 2         | 0.7%    |
| Romania     | 2         | 0.7%    |
| Portugal    | 2         | 0.7%    |
| Oman        | 2         | 0.7%    |
| Latvia      | 2         | 0.7%    |
| Brazil      | 2         | 0.7%    |
| Austria     | 2         | 0.7%    |
| Turkey      | 1         | 0.35%   |
| Sweden      | 1         | 0.35%   |
| Russia      | 1         | 0.35%   |
| Malaysia    | 1         | 0.35%   |
| Kuwait      | 1         | 0.35%   |
| Japan       | 1         | 0.35%   |
| Ireland     | 1         | 0.35%   |
| Hungary     | 1         | 0.35%   |
| Hong Kong   | 1         | 0.35%   |
| Honduras    | 1         | 0.35%   |
| Guatemala   | 1         | 0.35%   |
| Greece      | 1         | 0.35%   |
| Finland     | 1         | 0.35%   |
| Estonia     | 1         | 0.35%   |
| Denmark     | 1         | 0.35%   |
| Cyprus      | 1         | 0.35%   |
| China       | 1         | 0.35%   |
| Cambodia    | 1         | 0.35%   |
| Belgium     | 1         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Austin           | 4         | 1.39%   |
| Portland         | 3         | 1.04%   |
| Brooklyn         | 3         | 1.04%   |
| Washington       | 2         | 0.69%   |
| Sunnyvale        | 2         | 0.69%   |
| South Holland    | 2         | 0.69%   |
| Seattle          | 2         | 0.69%   |
| Riga             | 2         | 0.69%   |
| Prague           | 2         | 0.69%   |
| Phoenix          | 2         | 0.69%   |
| Muscat           | 2         | 0.69%   |
| Mississauga      | 2         | 0.69%   |
| Miami            | 2         | 0.69%   |
| Manchester       | 2         | 0.69%   |
| Madrid           | 2         | 0.69%   |
| Los Angeles      | 2         | 0.69%   |
| Henderson        | 2         | 0.69%   |
| Dresden          | 2         | 0.69%   |
| Colorado Springs | 2         | 0.69%   |
| Calgary          | 2         | 0.69%   |
| Bristol          | 2         | 0.69%   |
| Bamberg          | 2         | 0.69%   |
| York             | 1         | 0.35%   |
| Yekaterinburg    | 1         | 0.35%   |
| Wokingham        | 1         | 0.35%   |
| Wise             | 1         | 0.35%   |
| Whitley Bay      | 1         | 0.35%   |
| Weaverville      | 1         | 0.35%   |
| Wausau           | 1         | 0.35%   |
| Wasungen         | 1         | 0.35%   |
| Warsaw           | 1         | 0.35%   |
| Warren           | 1         | 0.35%   |
| Walsall          | 1         | 0.35%   |
| Waalre           | 1         | 0.35%   |
| Vilas            | 1         | 0.35%   |
| Victoria         | 1         | 0.35%   |
| Vechelde         | 1         | 0.35%   |
| Ulm              | 1         | 0.35%   |
| Tulsa            | 1         | 0.35%   |
| Tuam             | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Unknown                        | 118       | 127    | 23.84%  |
| Kingston                       | 83        | 90     | 16.77%  |
| Phison                         | 80        | 82     | 16.16%  |
| Samsung Electronics            | 36        | 46     | 7.27%   |
| Unknown                        | 28        | 29     | 5.66%   |
| O2 Micro                       | 18        | 19     | 3.64%   |
| Silicon Motion                 | 16        | 17     | 3.23%   |
| Seagate                        | 13        | 15     | 2.63%   |
| Phison Electronics             | 11        | 11     | 2.22%   |
| Kingston Technology Company    | 11        | 11     | 2.22%   |
| SanDisk                        | 10        | 12     | 2.02%   |
| WDC                            | 8         | 9      | 1.62%   |
| Toshiba                        | 5         | 7      | 1.01%   |
| SK hynix                       | 5         | 7      | 1.01%   |
| Crucial                        | 5         | 5      | 1.01%   |
| A-DATA Technology              | 5         | 5      | 1.01%   |
| PNY                            | 4         | 4      | 0.81%   |
| Micron/Crucial Technology      | 3         | 3      | 0.61%   |
| KIOXIA                         | 3         | 4      | 0.61%   |
| Intel                          | 3         | 3      | 0.61%   |
| Apple                          | 3         | 3      | 0.61%   |
| Solid State Storage Technology | 2         | 2      | 0.4%    |
| Realtek Semiconductor          | 2         | 2      | 0.4%    |
| JMicron Technology             | 2         | 2      | 0.4%    |
| China                          | 2         | 3      | 0.4%    |
| ASMT                           | 2         | 2      | 0.4%    |
| ADATA Technology               | 2         | 2      | 0.4%    |
| Yangtze Memory Technologies    | 1         | 1      | 0.2%    |
| Union Memory (Shenzhen)        | 1         | 1      | 0.2%    |
| TrekStor                       | 1         | 1      | 0.2%    |
| SSK                            | 1         | 1      | 0.2%    |
| SPCC                           | 1         | 1      | 0.2%    |
| Realtek                        | 1         | 1      | 0.2%    |
| Mushkin                        | 1         | 1      | 0.2%    |
| Micron Technology              | 1         | 1      | 0.2%    |
| Lexar 25                       | 1         | 1      | 0.2%    |
| Inateck                        | 1         | 1      | 0.2%    |
| HS-SSD-C100                    | 1         | 1      | 0.2%    |
| HP Phison                      | 1         | 1      | 0.2%    |
| GALAX                          | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Phison NVMe SSD Drive 512GB                            | 55        | 10.7%   |
| Unknown MMC Card  512GB                                | 47        | 9.14%   |
| Kingston NVMe SSD Drive 512GB                          | 42        | 8.17%   |
| Kingston NVMe SSD Drive 256GB                          | 32        | 6.23%   |
| Unknown                                                | 28        | 5.45%   |
| Unknown MMC Card  128GB                                | 20        | 3.89%   |
| Phison NVMe SSD Drive 256GB                            | 18        | 3.5%    |
| Unknown MMC Card  256GB                                | 17        | 3.31%   |
| O2 Micro NVMe SSD Drive 64GB                           | 15        | 2.92%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB                | 11        | 2.14%   |
| Phison PS5013 E13 NVMe Controller 512GB                | 10        | 1.95%   |
| Silicon Motion NVMe SSD Drive 512GB                    | 8         | 1.56%   |
| Unknown MMC Card  393GB                                | 7         | 1.36%   |
| Unknown MMC Card  64GB                                 | 6         | 1.17%   |
| Unknown MMC Card  32GB                                 | 5         | 0.97%   |
| Silicon Motion NVMe SSD Drive 256GB                    | 5         | 0.97%   |
| Samsung NVMe SSD Drive 512GB                           | 5         | 0.97%   |
| Samsung NVMe SSD Drive 1TB                             | 5         | 0.97%   |
| O2 Micro E2M2 64GB                                     | 4         | 0.78%   |
| Unknown MMC Card  498GB                                | 3         | 0.58%   |
| Samsung NVMe SSD Drive 1024GB                          | 3         | 0.58%   |
| Unknown MMC Card  196GB                                | 2         | 0.39%   |
| Unknown MMC Card  16GB                                 | 2         | 0.39%   |
| SK hynix NVMe SSD Drive 256GB                          | 2         | 0.39%   |
| SK hynix NVMe SSD Drive 1024GB                         | 2         | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 2         | 0.39%   |
| SanDisk NVMe SSD Drive 512GB                           | 2         | 0.39%   |
| SanDisk NVMe SSD Drive 500GB                           | 2         | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB                           | 2         | 0.39%   |
| Samsung SSD 870 QVO 2TB                                | 2         | 0.39%   |
| Samsung SSD 860 EVO 250GB                              | 2         | 0.39%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                       | 2         | 0.39%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                       | 2         | 0.39%   |
| Realtek NVMe SSD Drive 256GB                           | 2         | 0.39%   |
| Phison ESMP512GKB4C3-E13TS 512GB                       | 2         | 0.39%   |
| KIOXIA NVMe SSD Drive 512GB                            | 2         | 0.39%   |
| Kingston OM3PDP3512B-A01 512GB                         | 2         | 0.39%   |
| JMicron Generic 120GB                                  | 2         | 0.39%   |
| Crucial CT1000BX500SSD1 1TB                            | 2         | 0.39%   |
| A-DATA SU650 240GB SSD                                 | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 14     | 52.17%  |
| WDC     | 4         | 5      | 17.39%  |
| Toshiba | 3         | 5      | 13.04%  |
| ASMT    | 2         | 2      | 8.7%    |
| Apple   | 2         | 2      | 8.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 18     | 33.33%  |
| Kingston            | 6         | 6      | 12.5%   |
| Crucial             | 5         | 5      | 10.42%  |
| A-DATA Technology   | 5         | 5      | 10.42%  |
| PNY                 | 4         | 4      | 8.33%   |
| WDC                 | 3         | 3      | 6.25%   |
| SanDisk             | 2         | 3      | 4.17%   |
| China               | 2         | 3      | 4.17%   |
| TrekStor            | 1         | 1      | 2.08%   |
| SPCC                | 1         | 1      | 2.08%   |
| Mushkin             | 1         | 1      | 2.08%   |
| Lexar 25            | 1         | 1      | 2.08%   |
| HP Phison           | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 266       | 300    | 56.48%  |
| MMC     | 143       | 154    | 30.36%  |
| SSD     | 37        | 52     | 7.86%   |
| HDD     | 21        | 28     | 4.46%   |
| Unknown | 4         | 4      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 266       | 294    | 57.45%  |
| MMC  | 143       | 154    | 30.89%  |
| SATA | 41        | 76     | 8.86%   |
| SAS  | 13        | 14     | 2.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 46     | 51.67%  |
| 0.51-1.0   | 19        | 22     | 31.67%  |
| 1.01-2.0   | 5         | 6      | 8.33%   |
| 3.01-4.0   | 2         | 2      | 3.33%   |
| 2.01-3.0   | 2         | 3      | 3.33%   |
| 4.01-10.0  | 1         | 1      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 136       | 47.22%  |
| 101-250        | 85        | 29.51%  |
| 501-1000       | 31        | 10.76%  |
| 51-100         | 18        | 6.25%   |
| 1001-2000      | 11        | 3.82%   |
| More than 3000 | 4         | 1.39%   |
| 2001-3000      | 2         | 0.69%   |
| 21-50          | 1         | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 103       | 35.15%  |
| 251-500        | 72        | 24.57%  |
| 1-20           | 42        | 14.33%  |
| 21-50          | 37        | 12.63%  |
| 51-100         | 30        | 10.24%  |
| 501-1000       | 6         | 2.05%   |
| More than 3000 | 1         | 0.34%   |
| 2001-3000      | 1         | 0.34%   |
| 1001-2000      | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 281       | 527    | 97.23%  |
| Works    | 8         | 11     | 2.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Phison Electronics             | 89        | 27.47%  |
| Kingston Technology Company    | 87        | 26.85%  |
| Intel                          | 29        | 8.95%   |
| AMD                            | 26        | 8.02%   |
| Samsung Electronics            | 23        | 7.1%    |
| O2 Micro                       | 18        | 5.56%   |
| Silicon Motion                 | 16        | 4.94%   |
| SanDisk                        | 10        | 3.09%   |
| SK hynix                       | 5         | 1.54%   |
| Micron/Crucial Technology      | 3         | 0.93%   |
| KIOXIA                         | 3         | 0.93%   |
| Toshiba America Info Systems   | 2         | 0.62%   |
| Solid State Storage Technology | 2         | 0.62%   |
| Realtek Semiconductor          | 2         | 0.62%   |
| ADATA Technology               | 2         | 0.62%   |
| Yangtze Memory Technologies    | 1         | 0.31%   |
| Unknown                        | 1         | 0.31%   |
| Union Memory (Shenzhen)        | 1         | 0.31%   |
| Seagate Technology             | 1         | 0.31%   |
| Micron Technology              | 1         | 0.31%   |
| Biwin Storage Technology       | 1         | 0.31%   |
| Apple                          | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                                             | 85        | 25.22%  |
| Phison PS5013 E13 NVMe Controller                                             | 82        | 24.33%  |
| AMD FCH SATA Controller [AHCI mode]                                           | 20        | 5.93%   |
| O2 Micro Non-Volatile memory controller                                       | 18        | 5.34%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 15        | 4.45%   |
| Samsung NVMe SSD Controller 980                                               | 12        | 3.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 6         | 1.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 5         | 1.48%   |
| AMD 500 Series Chipset SATA Controller                                        | 5         | 1.48%   |
| SK hynix Gold P31 SSD                                                         | 4         | 1.19%   |
| SanDisk Non-Volatile memory controller                                        | 4         | 1.19%   |
| Phison E12 NVMe Controller                                                    | 4         | 1.19%   |
| AMD 400 Series Chipset SATA Controller                                        | 4         | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 0.89%   |
| KIOXIA NVMe SSD Controller BG4                                                | 3         | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 0.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 0.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 3         | 0.89%   |
| Solid State Storage Non-Volatile memory controller                            | 2         | 0.59%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 0.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 2         | 0.59%   |
| SanDisk PC SN530 NVMe SSD                                                     | 2         | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 0.59%   |
| Phison Electronics Non-Volatile memory controller                             | 2         | 0.59%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 2         | 0.59%   |
| Kingston Company Company Non-Volatile memory controller                       | 2         | 0.59%   |
| Intel SSD 660P Series                                                         | 2         | 0.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2         | 0.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 0.59%   |
| AMD FCH SATA Controller D                                                     | 2         | 0.59%   |
| ADATA Non-Volatile memory controller                                          | 2         | 0.59%   |
| Yangtze Memory Non-Volatile memory controller                                 | 1         | 0.3%    |
| Unknown Non-Volatile memory controller                                        | 1         | 0.3%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 1         | 0.3%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.3%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 0.3%    |
| SK hynix Non-Volatile memory controller                                       | 1         | 0.3%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.3%    |
| Seagate FireCuda 510 SSD                                                      | 1         | 0.3%    |
| Samsung NVMe SSD Controller SM951/PM951                                       | 1         | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 265       | 82.81%  |
| SATA | 47        | 14.69%  |
| RAID | 7         | 2.19%   |
| IDE  | 1         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 249       | 87.68%  |
| Intel  | 35        | 12.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| AMD Custom APU 0405                            | 215       | 75.7%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 4         | 1.41%   |
| AMD Ryzen 7 4800U with Radeon Graphics         | 3         | 1.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 2         | 0.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 0.7%    |
| AMD Ryzen 5 5600H with Radeon Graphics         | 2         | 0.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics         | 2         | 0.7%    |
| AMD Ryzen 5 3600X 6-Core Processor             | 2         | 0.7%    |
| Intel Xeon W-3223 CPU @ 3.50GHz                | 1         | 0.35%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1         | 0.35%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1         | 0.35%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz           | 1         | 0.35%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 1         | 0.35%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1         | 0.35%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1         | 0.35%   |
| Intel Core i7-7560U CPU @ 2.40GHz              | 1         | 0.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 1         | 0.35%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1         | 0.35%   |
| Intel Core i7-4578U CPU @ 3.00GHz              | 1         | 0.35%   |
| Intel Core i7-10870H CPU @ 2.20GHz             | 1         | 0.35%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1         | 0.35%   |
| Intel Core i5-9300H CPU @ 2.40GHz              | 1         | 0.35%   |
| Intel Core i5-8500T CPU @ 2.10GHz              | 1         | 0.35%   |
| Intel Core i5-8400T CPU @ 1.70GHz              | 1         | 0.35%   |
| Intel Core i5-6600 CPU @ 3.30GHz               | 1         | 0.35%   |
| Intel Core i5-6400T CPU @ 2.20GHz              | 1         | 0.35%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 1         | 0.35%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1         | 0.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 0.35%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1         | 0.35%   |
| Intel Core i3-9100F CPU @ 3.60GHz              | 1         | 0.35%   |
| Intel Atom x7-Z8750 CPU @ 1.60GHz              | 1         | 0.35%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 1         | 0.35%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz        | 1         | 0.35%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz        | 1         | 0.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 0.35%   |
| Intel 11th Gen Core i7-1160G7 @ 1.20GHz        | 1         | 0.35%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz        | 1         | 0.35%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz        | 1         | 0.35%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 223       | 78.52%  |
| AMD Ryzen 5            | 14        | 4.93%   |
| Intel Core i7          | 10        | 3.52%   |
| Intel Core i5          | 10        | 3.52%   |
| AMD Ryzen 7            | 10        | 3.52%   |
| AMD Ryzen 9            | 5         | 1.76%   |
| Intel Xeon             | 4         | 1.41%   |
| Intel Atom             | 2         | 0.7%    |
| Intel Core i3          | 1         | 0.35%   |
| AMD Ryzen Threadripper | 1         | 0.35%   |
| AMD FX                 | 1         | 0.35%   |
| AMD Embedded           | 1         | 0.35%   |
| AMD Athlon             | 1         | 0.35%   |
| AMD A8                 | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 235       | 82.75%  |
| 6      | 20        | 7.04%   |
| 8      | 16        | 5.63%   |
| 2      | 8         | 2.82%   |
| 12     | 5         | 1.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 284       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 270       | 94.74%  |
| 1      | 15        | 5.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 284       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 277       | 97.54%  |
| 0x08900201 | 6         | 2.11%   |
| 0x08600106 | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 220       | 77.46%  |
| Zen 2       | 12        | 4.23%   |
| KabyLake    | 12        | 4.23%   |
| Zen 3       | 9         | 3.17%   |
| Zen+        | 6         | 2.11%   |
| TigerLake   | 5         | 1.76%   |
| Skylake     | 5         | 1.76%   |
| Haswell     | 5         | 1.76%   |
| Zen         | 2         | 0.7%    |
| Silvermont  | 2         | 0.7%    |
| Piledriver  | 2         | 0.7%    |
| SandyBridge | 1         | 0.35%   |
| IvyBridge   | 1         | 0.35%   |
| Excavator   | 1         | 0.35%   |
| CometLake   | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 256       | 86.2%   |
| Intel  | 21        | 7.07%   |
| Nvidia | 20        | 6.73%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 215       | 72.39%  |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 2.36%   |
| AMD Renoir                                                                               | 5         | 1.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.35%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 4         | 1.35%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 1.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.01%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 3         | 1.01%   |
| AMD Cezanne                                                                              | 3         | 1.01%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.67%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.67%   |
| Intel HD Graphics 530                                                                    | 2         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.67%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 0.67%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 0.67%   |
| Nvidia TU117M                                                                            | 1         | 0.34%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.34%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.34%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.34%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.34%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.34%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.34%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.34%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 0.34%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.34%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.34%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.34%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.34%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 0.34%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1         | 0.34%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 0.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.34%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.34%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.34%   |
| Intel Tiger Lake Iris Xe Graphics                                                        | 1         | 0.34%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 0.34%   |
| Intel HD Graphics 620                                                                    | 1         | 0.34%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 253       | 89.08%  |
| 1 x Nvidia     | 12        | 4.23%   |
| 1 x Intel      | 10        | 3.52%   |
| Intel + Nvidia | 6         | 2.11%   |
| AMD + Nvidia   | 2         | 0.7%    |
| Intel + AMD    | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 267       | 94.01%  |
| Proprietary | 17        | 5.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 265       | 93.31%  |
| 3.01-4.0   | 5         | 1.76%   |
| 0.51-1.0   | 5         | 1.76%   |
| 7.01-8.0   | 3         | 1.06%   |
| 5.01-6.0   | 3         | 1.06%   |
| 16.01-24.0 | 1         | 0.35%   |
| 1.01-2.0   | 1         | 0.35%   |
| 0.01-0.5   | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| ANX                  | 189       | 56.08%  |
| Analogix             | 18        | 5.34%   |
| Goldstar             | 14        | 4.15%   |
| Samsung Electronics  | 13        | 3.86%   |
| Valve                | 9         | 2.67%   |
| BOE                  | 7         | 2.08%   |
| Ancor Communications | 7         | 2.08%   |
| Sony                 | 5         | 1.48%   |
| Philips              | 5         | 1.48%   |
| Dell                 | 5         | 1.48%   |
| Vizio                | 4         | 1.19%   |
| Hewlett-Packard      | 4         | 1.19%   |
| Chimei Innolux       | 4         | 1.19%   |
| AU Optronics         | 4         | 1.19%   |
| ASUSTek Computer     | 4         | 1.19%   |
| AOC                  | 4         | 1.19%   |
| Acer                 | 4         | 1.19%   |
| MSI                  | 3         | 0.89%   |
| LG Display           | 3         | 0.89%   |
| Sharp                | 2         | 0.59%   |
| Pixio                | 2         | 0.59%   |
| MSF                  | 2         | 0.59%   |
| Microsoft            | 2         | 0.59%   |
| ___                  | 1         | 0.3%    |
| ZSC                  | 1         | 0.3%    |
| YTH                  | 1         | 0.3%    |
| Wacom                | 1         | 0.3%    |
| ViewSonic            | 1         | 0.3%    |
| Unknown              | 1         | 0.3%    |
| Toshiba              | 1         | 0.3%    |
| TCL                  | 1         | 0.3%    |
| Sun                  | 1         | 0.3%    |
| Sceptre Tech         | 1         | 0.3%    |
| RTK                  | 1         | 0.3%    |
| LTM                  | 1         | 0.3%    |
| JDI                  | 1         | 0.3%    |
| Huion                | 1         | 0.3%    |
| HannStar             | 1         | 0.3%    |
| GreenWood            | 1         | 0.3%    |
| GBR                  | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ANX ANX7530 U ANX7539 800x1280                                         | 189       | 55.75%  |
| Analogix ANX7530 U ANX7539 800x1280                                    | 18        | 5.31%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 9         | 2.65%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 4         | 1.18%   |
| Sony TV *00 SNY7A04 3840x2160 1218x685mm 55.0-inch                     | 2         | 0.59%   |
| MSF TV080WUM-NL0 MSF1003 1600x2560 113x181mm 8.4-inch                  | 2         | 0.59%   |
| Microsoft Xbox One MSH0001 1920x1080 520x290mm 23.4-inch               | 2         | 0.59%   |
| Goldstar ULTRAWIDE GSM5AFB 2560x1080 798x334mm 34.1-inch               | 2         | 0.59%   |
| Goldstar 27GN7 GSM5B8D 1920x1080 600x303mm 26.5-inch                   | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch       | 2         | 0.59%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch       | 2         | 0.59%   |
| Ancor Communications ASUS VH242H ACI24F3 1920x1080 521x293mm 23.5-inch | 2         | 0.59%   |
| ___ TV ___9000 1360x768                                                | 1         | 0.29%   |
| ZSC FHD HDR ZSCBC32 1920x1080 344x195mm 15.6-inch                      | 1         | 0.29%   |
| YTH HS133PC YTH1330 1920x1080 255x220mm 13.3-inch                      | 1         | 0.29%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch               | 1         | 0.29%   |
| Vizio M58Q7-J01 VIZ1039 3840x2160 1212x682mm 54.8-inch                 | 1         | 0.29%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 0.29%   |
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                  | 1         | 0.29%   |
| Vizio D24f4-J01 VIZ1044 1920x1080 527x296mm 23.8-inch                  | 1         | 0.29%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1         | 0.29%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                     | 1         | 0.29%   |
| Toshiba TV TSB010E 1920x1080 1014x573mm 45.9-inch                      | 1         | 0.29%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                    | 1         | 0.29%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                 | 1         | 0.29%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 0.29%   |
| Sony TV *00 SNY8204 3840x2160 1218x685mm 55.0-inch                     | 1         | 0.29%   |
| Sony BW8 MS_9001 2560x1600                                             | 1         | 0.29%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.29%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.29%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                 | 1         | 0.29%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch      | 1         | 0.29%   |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch      | 1         | 0.29%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch      | 1         | 0.29%   |
| Samsung Electronics S27HG5x SAM0E10 2560x1440 598x336mm 27.0-inch      | 1         | 0.29%   |
| Samsung Electronics S27A750D SAM0798 1920x1080 598x336mm 27.0-inch     | 1         | 0.29%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch  | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1020x570mm 46.0-inch | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SAM0A7E 1920x1080 1060x626mm 48.5-inch | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 800x1280          | 211       | 63.75%  |
| 1920x1080 (FHD)   | 58        | 17.52%  |
| 3840x2160 (4K)    | 20        | 6.04%   |
| 2560x1440 (QHD)   | 10        | 3.02%   |
| 3440x1440         | 7         | 2.11%   |
| 2560x1080         | 5         | 1.51%   |
| 1366x768 (WXGA)   | 4         | 1.21%   |
| 2560x1600         | 3         | 0.91%   |
| 3840x1080         | 2         | 0.6%    |
| 1920x1200 (WUXGA) | 2         | 0.6%    |
| 1600x2560         | 2         | 0.6%    |
| 3200x1800 (QHD+)  | 1         | 0.3%    |
| 2880x1920         | 1         | 0.3%    |
| 1600x900 (HD+)    | 1         | 0.3%    |
| 1440x900 (WXGA+)  | 1         | 0.3%    |
| 1360x768          | 1         | 0.3%    |
| 1280x800 (WXGA)   | 1         | 0.3%    |
| 1024x768 (XGA)    | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 206       | 61.49%  |
| 27      | 19        | 5.67%   |
| 15      | 14        | 4.18%   |
| 23      | 13        | 3.88%   |
| 34      | 10        | 2.99%   |
| 7       | 10        | 2.99%   |
| 24      | 8         | 2.39%   |
| 72      | 6         | 1.79%   |
| 31      | 5         | 1.49%   |
| 13      | 5         | 1.49%   |
| 21      | 4         | 1.19%   |
| 17      | 4         | 1.19%   |
| 14      | 3         | 0.9%    |
| 8       | 3         | 0.9%    |
| 64      | 2         | 0.6%    |
| 55      | 2         | 0.6%    |
| 54      | 2         | 0.6%    |
| 49      | 2         | 0.6%    |
| 48      | 2         | 0.6%    |
| 40      | 2         | 0.6%    |
| 84      | 1         | 0.3%    |
| 69      | 1         | 0.3%    |
| 65      | 1         | 0.3%    |
| 57      | 1         | 0.3%    |
| 52      | 1         | 0.3%    |
| 46      | 1         | 0.3%    |
| 42      | 1         | 0.3%    |
| 36      | 1         | 0.3%    |
| 35      | 1         | 0.3%    |
| 32      | 1         | 0.3%    |
| 28      | 1         | 0.3%    |
| 18      | 1         | 0.3%    |
| 10      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 206       | 61.86%  |
| 501-600     | 35        | 10.51%  |
| 301-350     | 18        | 5.41%   |
| 1001-1500   | 13        | 3.9%    |
| 701-800     | 12        | 3.6%    |
| 601-700     | 10        | 3%      |
| 1-100       | 9         | 2.7%    |
| 1501-2000   | 8         | 2.4%    |
| 401-500     | 5         | 1.5%    |
| 201-300     | 5         | 1.5%    |
| 351-400     | 4         | 1.2%    |
| 101-200     | 4         | 1.2%    |
| 801-900     | 3         | 0.9%    |
| 901-1000    | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 0.62  | 206       | 62.8%   |
| 16/9  | 93        | 28.35%  |
| 21/9  | 11        | 3.35%   |
| 0.67  | 9         | 2.74%   |
| 16/10 | 3         | 0.91%   |
| 32/9  | 2         | 0.61%   |
| 0.58  | 2         | 0.61%   |
| 3/2   | 1         | 0.3%    |
| 1.00  | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 206       | 61.68%  |
| 201-250        | 22        | 6.59%   |
| 301-350        | 19        | 5.69%   |
| More than 1000 | 18        | 5.39%   |
| 351-500        | 18        | 5.39%   |
| 1-40           | 13        | 3.89%   |
| 101-110        | 13        | 3.89%   |
| 501-1000       | 7         | 2.1%    |
| 81-90          | 4         | 1.2%    |
| 71-80          | 4         | 1.2%    |
| 121-130        | 4         | 1.2%    |
| 251-300        | 2         | 0.6%    |
| 41-50          | 1         | 0.3%    |
| 151-200        | 1         | 0.3%    |
| 141-150        | 1         | 0.3%    |
| 91-100         | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 206       | 62.05%  |
| 51-100        | 51        | 15.36%  |
| 121-160       | 22        | 6.63%   |
| 101-120       | 22        | 6.63%   |
| 161-240       | 18        | 5.42%   |
| 1-50          | 10        | 3.01%   |
| More than 240 | 3         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 237       | 82.58%  |
| 2     | 48        | 16.72%  |
| 3     | 2         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 253       | 71.47%  |
| Intel                         | 35        | 9.89%   |
| ASIX Electronics              | 26        | 7.34%   |
| Broadcom                      | 7         | 1.98%   |
| Qualcomm Atheros              | 6         | 1.69%   |
| MediaTek                      | 5         | 1.41%   |
| Microsoft                     | 4         | 1.13%   |
| TP-Link                       | 3         | 0.85%   |
| Google                        | 3         | 0.85%   |
| DisplayLink                   | 3         | 0.85%   |
| Samsung Electronics           | 1         | 0.28%   |
| OnePlus Technology (Shenzhen) | 1         | 0.28%   |
| Lenovo                        | 1         | 0.28%   |
| Huawei Technologies           | 1         | 0.28%   |
| Dell                          | 1         | 0.28%   |
| Broadcom Limited              | 1         | 0.28%   |
| AVM                           | 1         | 0.28%   |
| Aquantia                      | 1         | 0.28%   |
| Apple                         | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 215       | 54.43%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 6.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 6.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 6.33%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 2.78%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.01%   |
| Microsoft XBOX ACC                                                | 3         | 0.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.76%   |
| Intel Wireless 7265                                               | 3         | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.76%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.51%   |
| Realtek 802.11ac NIC                                              | 2         | 0.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.51%   |
| Intel Wireless 8260                                               | 2         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.51%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.51%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 0.51%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.25%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.25%   |
| Realtek Realtek Network controller                                | 1         | 0.25%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.25%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.25%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 0.25%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.25%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.25%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.25%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 220       | 80%     |
| Intel                 | 28        | 10.18%  |
| Qualcomm Atheros      | 6         | 2.18%   |
| Broadcom              | 6         | 2.18%   |
| MediaTek              | 5         | 1.82%   |
| Microsoft             | 4         | 1.45%   |
| TP-Link               | 3         | 1.09%   |
| Dell                  | 1         | 0.36%   |
| Broadcom Limited      | 1         | 0.36%   |
| AVM                   | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 215       | 78.18%  |
| Intel Wi-Fi 6 AX200                                           | 11        | 4%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 4         | 1.45%   |
| Microsoft XBOX ACC                                            | 3         | 1.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 3         | 1.09%   |
| Intel Wireless 7265                                           | 3         | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 1.09%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 1.09%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2         | 0.73%   |
| Realtek 802.11ac NIC                                          | 2         | 0.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 0.73%   |
| Intel Wireless 8260                                           | 2         | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 0.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 2         | 0.73%   |
| TP-Link Archer T4U ver.3                                      | 1         | 0.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 0.36%   |
| Realtek Realtek Network controller                            | 1         | 0.36%   |
| Microsoft Xbox 360 Wireless Adapter                           | 1         | 0.36%   |
| Intel Wireless 8265 / 8275                                    | 1         | 0.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1         | 0.36%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 0.36%   |
| Intel Centrino Advanced-N 6235                                | 1         | 0.36%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                          | 1         | 0.36%   |
| Broadcom Network controller                                   | 1         | 0.36%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 1         | 0.36%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 1         | 0.36%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 1         | 0.36%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter            | 1         | 0.36%   |
| AVM FRITZ!WLAN AC 860                                         | 1         | 0.36%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 57        | 48.72%  |
| ASIX Electronics              | 26        | 22.22%  |
| Intel                         | 19        | 16.24%  |
| Google                        | 3         | 2.56%   |
| DisplayLink                   | 3         | 2.56%   |
| Qualcomm Atheros              | 2         | 1.71%   |
| Broadcom                      | 2         | 1.71%   |
| Samsung Electronics           | 1         | 0.85%   |
| OnePlus Technology (Shenzhen) | 1         | 0.85%   |
| Lenovo                        | 1         | 0.85%   |
| Huawei Technologies           | 1         | 0.85%   |
| Aquantia                      | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 22.69%  |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 21.85%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 21.01%  |
| Intel I211 Gigabit Network Connection                             | 6         | 5.04%   |
| Intel Ethernet Controller I225-V                                  | 4         | 3.36%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 3.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.68%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.68%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 1.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.84%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.84%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.84%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.84%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.84%   |
| Huawei YAL-L21                                                    | 1         | 0.84%   |
| Google Pixel 6                                                    | 1         | 0.84%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1         | 0.84%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.84%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 0.84%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.84%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 269       | 71.35%  |
| Ethernet | 107       | 28.38%  |
| Modem    | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 241       | 79.8%   |
| Ethernet | 61        | 20.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 249       | 87.68%  |
| 2     | 33        | 11.62%  |
| 3     | 2         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 186       | 65.26%  |
| Yes  | 99        | 34.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 215       | 82.69%  |
| Intel                           | 26        | 10%     |
| Qualcomm Atheros Communications | 5         | 1.92%   |
| Realtek Semiconductor           | 3         | 1.15%   |
| MediaTek                        | 2         | 0.77%   |
| Apple                           | 2         | 0.77%   |
| TP-Link                         | 1         | 0.38%   |
| Lite-On Technology              | 1         | 0.38%   |
| Integrated System Solution      | 1         | 0.38%   |
| Foxconn / Hon Hai               | 1         | 0.38%   |
| Cambridge Silicon Radio         | 1         | 0.38%   |
| Broadcom                        | 1         | 0.38%   |
| ASUSTek Computer                | 1         | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| IMC Networks 802.11ac WLAN Adapter                    | 215       | 82.69%  |
| Intel AX200 Bluetooth                                 | 9         | 3.46%   |
| Intel Bluetooth wireless interface                    | 6         | 2.31%   |
| Intel AX201 Bluetooth                                 | 4         | 1.54%   |
| Qualcomm Atheros  Bluetooth Device                    | 3         | 1.15%   |
| Intel AX210 Bluetooth                                 | 3         | 1.15%   |
| Realtek Bluetooth Radio                               | 2         | 0.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 0.77%   |
| MediaTek Wireless_Device                              | 2         | 0.77%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 0.77%   |
| TP-Link UB500 Adapter                                 | 1         | 0.38%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1         | 0.38%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1         | 0.38%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 0.38%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.38%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 0.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 1         | 0.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 0.38%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1         | 0.38%   |
| Apple Bluetooth USB Host Controller                   | 1         | 0.38%   |
| Apple Bluetooth Host Controller                       | 1         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| AMD                         | 261       | 76.99%  |
| Intel                       | 32        | 9.44%   |
| Nvidia                      | 18        | 5.31%   |
| Logitech                    | 5         | 1.47%   |
| C-Media Electronics         | 3         | 0.88%   |
| Realtek Semiconductor       | 2         | 0.59%   |
| Kingston Technology         | 2         | 0.59%   |
| Blue Microphones            | 2         | 0.59%   |
| Apple                       | 2         | 0.59%   |
| Tenx Technology             | 1         | 0.29%   |
| SteelSeries ApS             | 1         | 0.29%   |
| Sony                        | 1         | 0.29%   |
| Razer USA                   | 1         | 0.29%   |
| Quanta                      | 1         | 0.29%   |
| MosArt Semiconductor        | 1         | 0.29%   |
| Lenovo                      | 1         | 0.29%   |
| JMTek                       | 1         | 0.29%   |
| GN Netcom                   | 1         | 0.29%   |
| FiiO Electronics Technology | 1         | 0.29%   |
| Creative Labs               | 1         | 0.29%   |
| Corsair                     | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller           | 216       | 58.54%  |
| AMD Family 17h/19h HD Audio Controller                          | 15        | 4.07%   |
| AMD Renoir Radeon High Definition Audio Controller              | 11        | 2.98%   |
| AMD Starship/Matisse HD Audio Controller                        | 10        | 2.71%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                         | 10        | 2.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]      | 7         | 1.9%    |
| Intel Cannon Lake PCH cAVS                                      | 6         | 1.63%   |
| AMD Navi 10 HDMI Audio                                          | 6         | 1.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller             | 6         | 1.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller     | 5         | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller | 4         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                 | 3         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                          | 3         | 0.81%   |
| Intel 200 Series PCH HD Audio                                   | 3         | 0.81%   |
| Realtek Semiconductor USB Audio                                 | 2         | 0.54%   |
| Nvidia TU116 High Definition Audio Controller                   | 2         | 0.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller  | 2         | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                   | 2         | 0.54%   |
| Nvidia GP104 High Definition Audio Controller                   | 2         | 0.54%   |
| Nvidia GM204 High Definition Audio Controller                   | 2         | 0.54%   |
| Nvidia GA104 High Definition Audio Controller                   | 2         | 0.54%   |
| Intel Sunrise Point-LP HD Audio                                 | 2         | 0.54%   |
| Intel C610/X99 series chipset HD Audio Controller               | 2         | 0.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller             | 2         | 0.54%   |
| Tenx Technology USB AUDIO                                       | 1         | 0.27%   |
| SteelSeries ApS SteelSeries Arctis Pro                          | 1         | 0.27%   |
| Sony DualSense wireless controller (PS5)                        | 1         | 0.27%   |
| Razer USA Razer Barracuda Pro 2.4                               | 1         | 0.27%   |
| Quanta USB Audio                                                | 1         | 0.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]   | 1         | 0.27%   |
| Nvidia GA106 High Definition Audio Controller                   | 1         | 0.27%   |
| Nvidia GA102 High Definition Audio Controller                   | 1         | 0.27%   |
| MosArt Semiconductor MosArt USB Audio Device                    | 1         | 0.27%   |
| Logitech Logitech G PRO X Gaming Headset                        | 1         | 0.27%   |
| Logitech G733 Gaming Headset                                    | 1         | 0.27%   |
| Logitech G432 Gaming Headset                                    | 1         | 0.27%   |
| Logitech G430 Surround Sound Gaming Headset                     | 1         | 0.27%   |
| Logitech Blue Microphones                                       | 1         | 0.27%   |
| Lenovo ThinkPad USB-C Dock Audio                                | 1         | 0.27%   |
| Kingston Technology HyperX QuadCast                             | 1         | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6         | 75%     |
| G.Skill | 1         | 12.5%   |
| Crucial | 1         | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 6         | 75%     |
| G.Skill RAM F4-2666C19-16GRS 16GB SODIMM DDR4 2667MT/s    | 1         | 12.5%   |
| Crucial RAM CT8G4SFS832A.C8FR 8192MB SODIMM DDR4 3200MT/s | 1         | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR5 | 6         | 75%     |
| DDR4   | 2         | 25%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 8         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 6         | 75%     |
| 16384 | 1         | 12.5%   |
| 8192  | 1         | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 4266  | 6         | 75%     |
| 3200  | 1         | 12.5%   |
| 2667  | 1         | 12.5%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| HP Laserjet CP1525nw | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 6         | 18.75%  |
| Quanta                                 | 3         | 9.38%   |
| Logitech                               | 3         | 9.38%   |
| Sunplus Innovation Technology          | 2         | 6.25%   |
| Realtek Semiconductor                  | 2         | 6.25%   |
| Microdia                               | 2         | 6.25%   |
| Apple                                  | 2         | 6.25%   |
| Unknown                                | 1         | 3.13%   |
| Tripath Technology                     | 1         | 3.13%   |
| Syntek                                 | 1         | 3.13%   |
| Suyin                                  | 1         | 3.13%   |
| SunplusIT                              | 1         | 3.13%   |
| Samsung Electronics                    | 1         | 3.13%   |
| Magic Control Technology               | 1         | 3.13%   |
| Luxvisions Innotech Limited            | 1         | 3.13%   |
| IMC Networks                           | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |
| AVerMedia Technologies                 | 1         | 3.13%   |
| Acer                                   | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown 720p HD Camera                                  | 1         | 3.13%   |
| Tripath USB Camera                                      | 1         | 3.13%   |
| Syntek Integrated Camera                                | 1         | 3.13%   |
| Suyin HP Truevision HD                                  | 1         | 3.13%   |
| SunplusIT CODi A05020 Webcam                            | 1         | 3.13%   |
| Sunplus USB 2.0 Camera                                  | 1         | 3.13%   |
| Sunplus Integrated_Webcam_FHD                           | 1         | 3.13%   |
| Samsung Galaxy A5 (MTP)                                 | 1         | 3.13%   |
| Realtek NexiGo N660P FHD Webcam                         | 1         | 3.13%   |
| Realtek Integrated_Webcam_HD                            | 1         | 3.13%   |
| Quanta VGA WebCam                                       | 1         | 3.13%   |
| Quanta HP Wide Vision HD Camera                         | 1         | 3.13%   |
| Quanta HD Camera                                        | 1         | 3.13%   |
| Microdia Integrated_Webcam_HD                           | 1         | 3.13%   |
| Microdia Integrated Webcam HD                           | 1         | 3.13%   |
| Magic Control j5 WebCam JVCU100                         | 1         | 3.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 1         | 3.13%   |
| Logitech HD Webcam C525                                 | 1         | 3.13%   |
| Logitech HD Pro Webcam C920                             | 1         | 3.13%   |
| Logitech CrystalCam                                     | 1         | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 1         | 3.13%   |
| Chicony USB2.0 HD UVC WebCam                            | 1         | 3.13%   |
| Chicony Integrated Camera (1280x720@30)                 | 1         | 3.13%   |
| Chicony HP Wide Vision HD Camera                        | 1         | 3.13%   |
| Chicony HP TrueVision HD Camera                         | 1         | 3.13%   |
| Chicony HP High Definition 1MP Webcam                   | 1         | 3.13%   |
| Chicony HD User Facing                                  | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 1         | 3.13%   |
| AVerMedia Live Streamer CAM 313                         | 1         | 3.13%   |
| Apple iPhone5/5C/5S/6                                   | 1         | 3.13%   |
| Apple FaceTime HD Camera (Built-in)                     | 1         | 3.13%   |
| Acer Integrated Camera                                  | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 1         | 50%     |
| Shenzhen Goodix Technology | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device | 1         | 50%     |
| Unknown                             | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| SCM Microsystems | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| SCM Microsystems SCR3500 A Contact Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 260       | 91.55%  |
| 1     | 18        | 6.34%   |
| 2     | 5         | 1.76%   |
| 4     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 10        | 31.25%  |
| Multimedia controller | 10        | 31.25%  |
| Unassigned class      | 3         | 9.38%   |
| Graphics card         | 3         | 9.38%   |
| Fingerprint reader    | 2         | 6.25%   |
| Sound                 | 1         | 3.13%   |
| Net/ethernet          | 1         | 3.13%   |
| Modem                 | 1         | 3.13%   |
| Chipcard              | 1         | 3.13%   |

