SteamOS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for SteamOS.

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

Total: 283

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Valve     | Jupiter                     | [12f0d9358a](https://linux-hardware.org/?probe=12f0d9358a) | Oct 01, 2022 |
| Valve     | Jupiter                     | [9ea6c15d28](https://linux-hardware.org/?probe=9ea6c15d28) | Oct 01, 2022 |
| Valve     | Jupiter                     | [dab0a00c02](https://linux-hardware.org/?probe=dab0a00c02) | Sep 30, 2022 |
| Valve     | Jupiter                     | [4d1b722861](https://linux-hardware.org/?probe=4d1b722861) | Sep 30, 2022 |
| Valve     | Jupiter                     | [e9737fcadf](https://linux-hardware.org/?probe=e9737fcadf) | Sep 30, 2022 |
| Valve     | Jupiter                     | [5e7ec518d4](https://linux-hardware.org/?probe=5e7ec518d4) | Sep 30, 2022 |
| Valve     | Jupiter                     | [a031955ffb](https://linux-hardware.org/?probe=a031955ffb) | Sep 30, 2022 |
| Valve     | Jupiter                     | [66731152dd](https://linux-hardware.org/?probe=66731152dd) | Sep 29, 2022 |
| Valve     | Jupiter                     | [679b3600fa](https://linux-hardware.org/?probe=679b3600fa) | Sep 29, 2022 |
| Valve     | Jupiter                     | [92b774ed77](https://linux-hardware.org/?probe=92b774ed77) | Sep 29, 2022 |
| Valve     | Jupiter                     | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| Valve     | Jupiter                     | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| Valve     | Jupiter                     | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| GPD       | G1619-04                    | [9e99ae15fb](https://linux-hardware.org/?probe=9e99ae15fb) | Sep 27, 2022 |
| Valve     | Jupiter                     | [9a2af6352a](https://linux-hardware.org/?probe=9a2af6352a) | Sep 27, 2022 |
| Valve     | Jupiter                     | [0f1c8fad1c](https://linux-hardware.org/?probe=0f1c8fad1c) | Sep 26, 2022 |
| Valve     | Jupiter                     | [c3305d9bff](https://linux-hardware.org/?probe=c3305d9bff) | Sep 26, 2022 |
| Valve     | Jupiter                     | [8c94cd9bd3](https://linux-hardware.org/?probe=8c94cd9bd3) | Sep 26, 2022 |
| Valve     | Jupiter                     | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Valve     | Jupiter                     | [315719a312](https://linux-hardware.org/?probe=315719a312) | Sep 25, 2022 |
| Valve     | Jupiter                     | [f5183f3eed](https://linux-hardware.org/?probe=f5183f3eed) | Sep 24, 2022 |
| Valve     | Jupiter                     | [6ddd668003](https://linux-hardware.org/?probe=6ddd668003) | Sep 24, 2022 |
| Valve     | Jupiter                     | [b70be12594](https://linux-hardware.org/?probe=b70be12594) | Sep 24, 2022 |
| Valve     | Jupiter                     | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Valve     | Jupiter                     | [d03b845c90](https://linux-hardware.org/?probe=d03b845c90) | Sep 23, 2022 |
| Valve     | Jupiter                     | [ca6d2abcd9](https://linux-hardware.org/?probe=ca6d2abcd9) | Sep 23, 2022 |
| Valve     | Jupiter                     | [bea162d6e3](https://linux-hardware.org/?probe=bea162d6e3) | Sep 22, 2022 |
| Valve     | Jupiter                     | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Valve     | Jupiter                     | [ce15d6d4bb](https://linux-hardware.org/?probe=ce15d6d4bb) | Sep 22, 2022 |
| Valve     | Jupiter                     | [f9230d9e82](https://linux-hardware.org/?probe=f9230d9e82) | Sep 21, 2022 |
| Valve     | Jupiter                     | [a39be03b34](https://linux-hardware.org/?probe=a39be03b34) | Sep 21, 2022 |
| Valve     | Jupiter                     | [1c7bc3efcf](https://linux-hardware.org/?probe=1c7bc3efcf) | Sep 21, 2022 |
| Valve     | Jupiter                     | [7bc45b1077](https://linux-hardware.org/?probe=7bc45b1077) | Sep 21, 2022 |
| Valve     | Jupiter                     | [721ede2e11](https://linux-hardware.org/?probe=721ede2e11) | Sep 20, 2022 |
| Valve     | Jupiter                     | [83ed33f7e6](https://linux-hardware.org/?probe=83ed33f7e6) | Sep 20, 2022 |
| Valve     | Jupiter                     | [e60653a4c7](https://linux-hardware.org/?probe=e60653a4c7) | Sep 20, 2022 |
| Valve     | Jupiter                     | [090e33f643](https://linux-hardware.org/?probe=090e33f643) | Sep 20, 2022 |
| Valve     | Jupiter                     | [919ae4fe6c](https://linux-hardware.org/?probe=919ae4fe6c) | Sep 19, 2022 |
| Valve     | Jupiter                     | [5ed6e54010](https://linux-hardware.org/?probe=5ed6e54010) | Sep 19, 2022 |
| Valve     | Jupiter                     | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| Valve     | Jupiter                     | [84051314e8](https://linux-hardware.org/?probe=84051314e8) | Sep 19, 2022 |
| Valve     | Jupiter                     | [de74f87be5](https://linux-hardware.org/?probe=de74f87be5) | Sep 18, 2022 |
| Valve     | Jupiter                     | [8273135785](https://linux-hardware.org/?probe=8273135785) | Sep 18, 2022 |
| Valve     | Jupiter                     | [4b802a9fe9](https://linux-hardware.org/?probe=4b802a9fe9) | Sep 18, 2022 |
| Valve     | Jupiter                     | [e65c41605f](https://linux-hardware.org/?probe=e65c41605f) | Sep 18, 2022 |
| Valve     | Jupiter                     | [b2a1aea8e2](https://linux-hardware.org/?probe=b2a1aea8e2) | Sep 17, 2022 |
| Valve     | Jupiter                     | [b667f00856](https://linux-hardware.org/?probe=b667f00856) | Sep 17, 2022 |
| Valve     | Jupiter                     | [221fd3ae1c](https://linux-hardware.org/?probe=221fd3ae1c) | Sep 17, 2022 |
| Valve     | Jupiter                     | [c4dd2bf91f](https://linux-hardware.org/?probe=c4dd2bf91f) | Sep 17, 2022 |
| Valve     | Jupiter                     | [0db4b64dcd](https://linux-hardware.org/?probe=0db4b64dcd) | Sep 16, 2022 |
| Valve     | Jupiter                     | [4540c4e930](https://linux-hardware.org/?probe=4540c4e930) | Sep 16, 2022 |
| Valve     | Jupiter                     | [47ac328960](https://linux-hardware.org/?probe=47ac328960) | Sep 16, 2022 |
| Valve     | Jupiter                     | [28a40721a8](https://linux-hardware.org/?probe=28a40721a8) | Sep 16, 2022 |
| Valve     | Jupiter                     | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| Valve     | Jupiter                     | [9adc000021](https://linux-hardware.org/?probe=9adc000021) | Sep 15, 2022 |
| Valve     | Jupiter                     | [9493095ab1](https://linux-hardware.org/?probe=9493095ab1) | Sep 15, 2022 |
| Valve     | Jupiter                     | [9817414c4e](https://linux-hardware.org/?probe=9817414c4e) | Sep 14, 2022 |
| Valve     | Jupiter                     | [0925a55100](https://linux-hardware.org/?probe=0925a55100) | Sep 13, 2022 |
| Valve     | Jupiter                     | [b2b312e843](https://linux-hardware.org/?probe=b2b312e843) | Sep 12, 2022 |
| Valve     | Jupiter                     | [694e9a60ad](https://linux-hardware.org/?probe=694e9a60ad) | Sep 11, 2022 |
| Valve     | Jupiter                     | [438ec3fe41](https://linux-hardware.org/?probe=438ec3fe41) | Sep 11, 2022 |
| Valve     | Jupiter                     | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| Valve     | Jupiter                     | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| Valve     | Jupiter                     | [2c95ed7c92](https://linux-hardware.org/?probe=2c95ed7c92) | Sep 10, 2022 |
| Valve     | Jupiter                     | [17eea2b641](https://linux-hardware.org/?probe=17eea2b641) | Sep 09, 2022 |
| Valve     | Jupiter                     | [49694d92f6](https://linux-hardware.org/?probe=49694d92f6) | Sep 09, 2022 |
| Valve     | Jupiter                     | [48df4850fe](https://linux-hardware.org/?probe=48df4850fe) | Sep 09, 2022 |
| Valve     | Jupiter                     | [c63b3ff391](https://linux-hardware.org/?probe=c63b3ff391) | Sep 09, 2022 |
| Valve     | Jupiter                     | [cb5ede9c6f](https://linux-hardware.org/?probe=cb5ede9c6f) | Sep 09, 2022 |
| Valve     | Jupiter                     | [9fce9d23c8](https://linux-hardware.org/?probe=9fce9d23c8) | Sep 09, 2022 |
| Valve     | Jupiter                     | [7d45c49609](https://linux-hardware.org/?probe=7d45c49609) | Sep 08, 2022 |
| ASUSTek   | ROG Zephyrus S17 GX703HS... | [041c6dac05](https://linux-hardware.org/?probe=041c6dac05) | Sep 08, 2022 |
| Valve     | Jupiter                     | [3c4865fc8c](https://linux-hardware.org/?probe=3c4865fc8c) | Sep 08, 2022 |
| Valve     | Jupiter                     | [1669287cbb](https://linux-hardware.org/?probe=1669287cbb) | Sep 07, 2022 |
| Valve     | Jupiter                     | [47baad2eed](https://linux-hardware.org/?probe=47baad2eed) | Sep 07, 2022 |
| Valve     | Jupiter                     | [eb15307366](https://linux-hardware.org/?probe=eb15307366) | Sep 07, 2022 |
| Valve     | Jupiter                     | [8cd669599d](https://linux-hardware.org/?probe=8cd669599d) | Sep 07, 2022 |
| Valve     | Jupiter                     | [090d406ac3](https://linux-hardware.org/?probe=090d406ac3) | Sep 07, 2022 |
| Valve     | Jupiter                     | [3f0eb4cd71](https://linux-hardware.org/?probe=3f0eb4cd71) | Sep 06, 2022 |
| Valve     | Jupiter                     | [04c7e44198](https://linux-hardware.org/?probe=04c7e44198) | Sep 05, 2022 |
| Valve     | Jupiter                     | [584ea1ade0](https://linux-hardware.org/?probe=584ea1ade0) | Sep 05, 2022 |
| Valve     | Jupiter                     | [bf34e42b02](https://linux-hardware.org/?probe=bf34e42b02) | Sep 04, 2022 |
| Valve     | Jupiter                     | [f9942c8a6b](https://linux-hardware.org/?probe=f9942c8a6b) | Sep 04, 2022 |
| Valve     | Jupiter                     | [93771f5a6b](https://linux-hardware.org/?probe=93771f5a6b) | Sep 04, 2022 |
| Valve     | Jupiter                     | [08728d3dc1](https://linux-hardware.org/?probe=08728d3dc1) | Sep 04, 2022 |
| Valve     | Jupiter                     | [a8038907ed](https://linux-hardware.org/?probe=a8038907ed) | Sep 03, 2022 |
| Valve     | Jupiter                     | [f35ef3a2e1](https://linux-hardware.org/?probe=f35ef3a2e1) | Sep 03, 2022 |
| Valve     | Jupiter                     | [e12248df34](https://linux-hardware.org/?probe=e12248df34) | Sep 03, 2022 |
| Valve     | Jupiter                     | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| Valve     | Jupiter                     | [c0094f39c5](https://linux-hardware.org/?probe=c0094f39c5) | Sep 02, 2022 |
| Valve     | Jupiter                     | [b3b1ffd7ff](https://linux-hardware.org/?probe=b3b1ffd7ff) | Sep 02, 2022 |
| Valve     | Jupiter                     | [3fdc8df5b2](https://linux-hardware.org/?probe=3fdc8df5b2) | Sep 02, 2022 |
| Valve     | Jupiter                     | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| Valve     | Jupiter                     | [c89533e9a2](https://linux-hardware.org/?probe=c89533e9a2) | Sep 01, 2022 |
| Valve     | Jupiter                     | [c348c06118](https://linux-hardware.org/?probe=c348c06118) | Sep 01, 2022 |
| Valve     | Jupiter                     | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| Valve     | Jupiter                     | [5a2483051c](https://linux-hardware.org/?probe=5a2483051c) | Aug 31, 2022 |
| Valve     | Jupiter                     | [0b928ad313](https://linux-hardware.org/?probe=0b928ad313) | Aug 31, 2022 |
| Valve     | Jupiter                     | [dbc549504c](https://linux-hardware.org/?probe=dbc549504c) | Aug 31, 2022 |
| Valve     | Jupiter                     | [1b38f48059](https://linux-hardware.org/?probe=1b38f48059) | Aug 30, 2022 |
| Valve     | Jupiter                     | [40b9dd39a6](https://linux-hardware.org/?probe=40b9dd39a6) | Aug 30, 2022 |
| Valve     | Jupiter                     | [ea6506cc93](https://linux-hardware.org/?probe=ea6506cc93) | Aug 30, 2022 |
| Lenovo    | IdeaPad Gaming 3 15ACH6 ... | [844a0c00e2](https://linux-hardware.org/?probe=844a0c00e2) | Aug 29, 2022 |
| Valve     | Jupiter                     | [830c22afde](https://linux-hardware.org/?probe=830c22afde) | Aug 29, 2022 |
| Dell      | XPS 13 9360                 | [1763ee1dd0](https://linux-hardware.org/?probe=1763ee1dd0) | Aug 29, 2022 |
| Valve     | Jupiter                     | [43ec7fb445](https://linux-hardware.org/?probe=43ec7fb445) | Aug 29, 2022 |
| Valve     | Jupiter                     | [3848655fce](https://linux-hardware.org/?probe=3848655fce) | Aug 28, 2022 |
| Valve     | Jupiter                     | [cd6744821b](https://linux-hardware.org/?probe=cd6744821b) | Aug 27, 2022 |
| Lenovo    | Legion Y740-15IRHg 81UH     | [521dd85c98](https://linux-hardware.org/?probe=521dd85c98) | Aug 26, 2022 |
| Valve     | Jupiter                     | [8027445785](https://linux-hardware.org/?probe=8027445785) | Aug 26, 2022 |
| Dell      | Precision 7720              | [7fafc0e50b](https://linux-hardware.org/?probe=7fafc0e50b) | Aug 26, 2022 |
| Valve     | Jupiter                     | [447edaff49](https://linux-hardware.org/?probe=447edaff49) | Aug 25, 2022 |
| Valve     | Jupiter                     | [ebd183fc4b](https://linux-hardware.org/?probe=ebd183fc4b) | Aug 25, 2022 |
| Valve     | Jupiter                     | [b74760105e](https://linux-hardware.org/?probe=b74760105e) | Aug 25, 2022 |
| Valve     | Jupiter                     | [5064c9f57b](https://linux-hardware.org/?probe=5064c9f57b) | Aug 24, 2022 |
| Valve     | Jupiter                     | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| Valve     | Jupiter                     | [de49ccefa5](https://linux-hardware.org/?probe=de49ccefa5) | Aug 24, 2022 |
| Valve     | Jupiter                     | [4c88b729d3](https://linux-hardware.org/?probe=4c88b729d3) | Aug 23, 2022 |
| Valve     | Jupiter                     | [ba1940016e](https://linux-hardware.org/?probe=ba1940016e) | Aug 23, 2022 |
| Valve     | Jupiter                     | [161cc0c135](https://linux-hardware.org/?probe=161cc0c135) | Aug 23, 2022 |
| Valve     | Jupiter                     | [078b8e8ff1](https://linux-hardware.org/?probe=078b8e8ff1) | Aug 22, 2022 |
| Valve     | Jupiter                     | [04b0de9007](https://linux-hardware.org/?probe=04b0de9007) | Aug 22, 2022 |
| Valve     | Jupiter                     | [1c25a3bf8a](https://linux-hardware.org/?probe=1c25a3bf8a) | Aug 22, 2022 |
| Valve     | Jupiter                     | [bc83cf9f77](https://linux-hardware.org/?probe=bc83cf9f77) | Aug 21, 2022 |
| Valve     | Jupiter                     | [36124147ef](https://linux-hardware.org/?probe=36124147ef) | Aug 20, 2022 |
| Valve     | Jupiter                     | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| Valve     | Jupiter                     | [d6b92d1aa0](https://linux-hardware.org/?probe=d6b92d1aa0) | Aug 19, 2022 |
| Valve     | Jupiter                     | [bff4d1ca46](https://linux-hardware.org/?probe=bff4d1ca46) | Aug 19, 2022 |
| Valve     | Jupiter                     | [87f3603202](https://linux-hardware.org/?probe=87f3603202) | Aug 18, 2022 |
| Valve     | Jupiter                     | [f0dc30e9f8](https://linux-hardware.org/?probe=f0dc30e9f8) | Aug 17, 2022 |
| Valve     | Jupiter                     | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| Valve     | Jupiter                     | [af4a593873](https://linux-hardware.org/?probe=af4a593873) | Aug 16, 2022 |
| Valve     | Jupiter                     | [c395a0f9db](https://linux-hardware.org/?probe=c395a0f9db) | Aug 16, 2022 |
| Valve     | Jupiter                     | [90ac03e747](https://linux-hardware.org/?probe=90ac03e747) | Aug 15, 2022 |
| Valve     | Jupiter                     | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| Valve     | Jupiter                     | [9ab7a2b695](https://linux-hardware.org/?probe=9ab7a2b695) | Aug 15, 2022 |
| Valve     | Jupiter                     | [2adcfce1c0](https://linux-hardware.org/?probe=2adcfce1c0) | Aug 14, 2022 |
| Valve     | Jupiter                     | [e9f1f10a4c](https://linux-hardware.org/?probe=e9f1f10a4c) | Aug 14, 2022 |
| Valve     | Jupiter                     | [50596cb93b](https://linux-hardware.org/?probe=50596cb93b) | Aug 13, 2022 |
| Valve     | Jupiter                     | [3a1e95f5d5](https://linux-hardware.org/?probe=3a1e95f5d5) | Aug 12, 2022 |
| Valve     | Jupiter                     | [b63f9aedab](https://linux-hardware.org/?probe=b63f9aedab) | Aug 12, 2022 |
| Valve     | Jupiter                     | [822737452b](https://linux-hardware.org/?probe=822737452b) | Aug 12, 2022 |
| Valve     | Jupiter                     | [9839802d27](https://linux-hardware.org/?probe=9839802d27) | Aug 12, 2022 |
| Valve     | Jupiter                     | [6b9bfad898](https://linux-hardware.org/?probe=6b9bfad898) | Aug 12, 2022 |
| Valve     | Jupiter                     | [c6e02c54e7](https://linux-hardware.org/?probe=c6e02c54e7) | Aug 11, 2022 |
| HP        | Laptop 14z-fq0000           | [9c62f8d392](https://linux-hardware.org/?probe=9c62f8d392) | Aug 11, 2022 |
| Valve     | Jupiter                     | [90e751b5cf](https://linux-hardware.org/?probe=90e751b5cf) | Aug 10, 2022 |
| Valve     | Jupiter                     | [6223a43fe2](https://linux-hardware.org/?probe=6223a43fe2) | Aug 10, 2022 |
| Valve     | Jupiter                     | [2cec170e55](https://linux-hardware.org/?probe=2cec170e55) | Aug 10, 2022 |
| AMI       | Unknown                     | [5cee81ed21](https://linux-hardware.org/?probe=5cee81ed21) | Aug 10, 2022 |
| Valve     | Jupiter                     | [68214f1af2](https://linux-hardware.org/?probe=68214f1af2) | Aug 10, 2022 |
| AMI       | Unknown                     | [7752037bab](https://linux-hardware.org/?probe=7752037bab) | Aug 10, 2022 |
| Valve     | Jupiter                     | [e4914b879a](https://linux-hardware.org/?probe=e4914b879a) | Aug 09, 2022 |
| Valve     | Jupiter                     | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| Valve     | Jupiter                     | [a5b1208abc](https://linux-hardware.org/?probe=a5b1208abc) | Aug 08, 2022 |
| Valve     | Jupiter                     | [a50e78265a](https://linux-hardware.org/?probe=a50e78265a) | Aug 07, 2022 |
| Valve     | Jupiter                     | [d8ef9609a7](https://linux-hardware.org/?probe=d8ef9609a7) | Aug 07, 2022 |
| Valve     | Jupiter                     | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| Valve     | Jupiter                     | [64a0d92417](https://linux-hardware.org/?probe=64a0d92417) | Aug 07, 2022 |
| Valve     | Jupiter                     | [b6c7ee76fa](https://linux-hardware.org/?probe=b6c7ee76fa) | Aug 06, 2022 |
| Valve     | Jupiter                     | [6bbc4f3d0a](https://linux-hardware.org/?probe=6bbc4f3d0a) | Aug 05, 2022 |
| Valve     | Jupiter                     | [d15c62e29a](https://linux-hardware.org/?probe=d15c62e29a) | Aug 05, 2022 |
| Valve     | Jupiter                     | [6f76f9d91a](https://linux-hardware.org/?probe=6f76f9d91a) | Aug 05, 2022 |
| Valve     | Jupiter                     | [4403a80bdc](https://linux-hardware.org/?probe=4403a80bdc) | Aug 03, 2022 |
| Valve     | Jupiter                     | [8689254ee7](https://linux-hardware.org/?probe=8689254ee7) | Aug 03, 2022 |
| Valve     | Jupiter                     | [bfddbf1d22](https://linux-hardware.org/?probe=bfddbf1d22) | Aug 02, 2022 |
| Valve     | Jupiter                     | [fdb514a999](https://linux-hardware.org/?probe=fdb514a999) | Aug 01, 2022 |
| Valve     | Jupiter                     | [e4c6300b68](https://linux-hardware.org/?probe=e4c6300b68) | Aug 01, 2022 |
| GPD       | G1619-02                    | [c61c4280c8](https://linux-hardware.org/?probe=c61c4280c8) | Jul 31, 2022 |
| Valve     | Jupiter                     | [ee3b662083](https://linux-hardware.org/?probe=ee3b662083) | Jul 30, 2022 |
| Acer      | Aspire A514-54              | [9a18d7476f](https://linux-hardware.org/?probe=9a18d7476f) | Jul 29, 2022 |
| Valve     | Jupiter                     | [225e2c825e](https://linux-hardware.org/?probe=225e2c825e) | Jul 29, 2022 |
| Acer      | Aspire A514-54              | [4a6c9ef157](https://linux-hardware.org/?probe=4a6c9ef157) | Jul 28, 2022 |
| Valve     | Jupiter                     | [dffaa71aed](https://linux-hardware.org/?probe=dffaa71aed) | Jul 28, 2022 |
| Valve     | Jupiter                     | [35608b206c](https://linux-hardware.org/?probe=35608b206c) | Jul 27, 2022 |
| Valve     | Jupiter                     | [e35fa6e699](https://linux-hardware.org/?probe=e35fa6e699) | Jul 27, 2022 |
| Valve     | Jupiter                     | [f43cbe28e9](https://linux-hardware.org/?probe=f43cbe28e9) | Jul 27, 2022 |
| Valve     | Jupiter                     | [d4e4413f9b](https://linux-hardware.org/?probe=d4e4413f9b) | Jul 26, 2022 |
| Valve     | Jupiter                     | [9c34e91c79](https://linux-hardware.org/?probe=9c34e91c79) | Jul 26, 2022 |
| Valve     | Jupiter                     | [b605f923c6](https://linux-hardware.org/?probe=b605f923c6) | Jul 25, 2022 |
| Valve     | Jupiter                     | [3e7b7cb8cd](https://linux-hardware.org/?probe=3e7b7cb8cd) | Jul 23, 2022 |
| Alienware | m17                         | [e14db26b9b](https://linux-hardware.org/?probe=e14db26b9b) | Jul 23, 2022 |
| Valve     | Jupiter                     | [ca07489d53](https://linux-hardware.org/?probe=ca07489d53) | Jul 23, 2022 |
| Valve     | Jupiter                     | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Valve     | Jupiter                     | [2d0db23de3](https://linux-hardware.org/?probe=2d0db23de3) | Jul 23, 2022 |
| Valve     | Jupiter                     | [4aece18875](https://linux-hardware.org/?probe=4aece18875) | Jul 23, 2022 |
| Valve     | Jupiter                     | [44dca72cbb](https://linux-hardware.org/?probe=44dca72cbb) | Jul 22, 2022 |
| Unknown   | Unknown                     | [96af389676](https://linux-hardware.org/?probe=96af389676) | Jul 22, 2022 |
| ASRock    | X570 Extreme4 WiFi ax       | [bc52038c74](https://linux-hardware.org/?probe=bc52038c74) | Jul 21, 2022 |
| Valve     | Jupiter                     | [0cd166bdb1](https://linux-hardware.org/?probe=0cd166bdb1) | Jul 21, 2022 |
| Valve     | Jupiter                     | [2c1ad04467](https://linux-hardware.org/?probe=2c1ad04467) | Jul 18, 2022 |
| Valve     | Jupiter                     | [7f27efe00e](https://linux-hardware.org/?probe=7f27efe00e) | Jul 17, 2022 |
| HP        | Pavilion 17                 | [722f4eb4a9](https://linux-hardware.org/?probe=722f4eb4a9) | Jul 17, 2022 |
| Valve     | Jupiter                     | [b639365efd](https://linux-hardware.org/?probe=b639365efd) | Jul 16, 2022 |
| Valve     | Jupiter                     | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| Valve     | Jupiter                     | [eec9897935](https://linux-hardware.org/?probe=eec9897935) | Jul 15, 2022 |
| Valve     | Jupiter                     | [d4be0d94b4](https://linux-hardware.org/?probe=d4be0d94b4) | Jul 14, 2022 |
| Valve     | Jupiter                     | [d2f117e7f3](https://linux-hardware.org/?probe=d2f117e7f3) | Jul 14, 2022 |
| Dell      | XPS 15 9570                 | [e157e6d524](https://linux-hardware.org/?probe=e157e6d524) | Jul 14, 2022 |
| Valve     | Jupiter                     | [f7d66c8d35](https://linux-hardware.org/?probe=f7d66c8d35) | Jul 10, 2022 |
| Valve     | Jupiter                     | [0c2ea27c49](https://linux-hardware.org/?probe=0c2ea27c49) | Jul 09, 2022 |
| Valve     | Jupiter                     | [98711d54c1](https://linux-hardware.org/?probe=98711d54c1) | Jul 08, 2022 |
| Lenovo    | ThinkBook 13s G3 ACN 20Y... | [c3c73948f5](https://linux-hardware.org/?probe=c3c73948f5) | Jul 08, 2022 |
| Valve     | Jupiter                     | [3ede093138](https://linux-hardware.org/?probe=3ede093138) | Jul 07, 2022 |
| Valve     | Jupiter                     | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Valve     | Jupiter                     | [663562cc6b](https://linux-hardware.org/?probe=663562cc6b) | Jul 06, 2022 |
| Valve     | Jupiter                     | [e640bab55c](https://linux-hardware.org/?probe=e640bab55c) | Jul 05, 2022 |
| Valve     | Jupiter                     | [0bd46afcda](https://linux-hardware.org/?probe=0bd46afcda) | Jul 04, 2022 |
| Valve     | Jupiter                     | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Valve     | Jupiter                     | [ac0c161f66](https://linux-hardware.org/?probe=ac0c161f66) | Jul 02, 2022 |
| Valve     | Jupiter                     | [c591d23b4d](https://linux-hardware.org/?probe=c591d23b4d) | Jul 01, 2022 |
| Valve     | Jupiter                     | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Valve     | Jupiter                     | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Valve     | Jupiter                     | [261590e542](https://linux-hardware.org/?probe=261590e542) | Jun 29, 2022 |
| Valve     | Jupiter                     | [7c233f0a07](https://linux-hardware.org/?probe=7c233f0a07) | Jun 29, 2022 |
| Valve     | Jupiter                     | [e80815c8d4](https://linux-hardware.org/?probe=e80815c8d4) | Jun 27, 2022 |
| Valve     | Jupiter                     | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| Valve     | Jupiter                     | [e51f5d8645](https://linux-hardware.org/?probe=e51f5d8645) | Jun 26, 2022 |
| Valve     | Jupiter                     | [b4dd19f939](https://linux-hardware.org/?probe=b4dd19f939) | Jun 25, 2022 |
| Valve     | Jupiter                     | [c9ed3cf311](https://linux-hardware.org/?probe=c9ed3cf311) | Jun 23, 2022 |
| Dell      | G15 5510                    | [9c5777f505](https://linux-hardware.org/?probe=9c5777f505) | Jun 23, 2022 |
| Valve     | Jupiter                     | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Valve     | Jupiter                     | [262a7f0cd4](https://linux-hardware.org/?probe=262a7f0cd4) | Jun 22, 2022 |
| Valve     | Jupiter                     | [f8722866b2](https://linux-hardware.org/?probe=f8722866b2) | Jun 22, 2022 |
| Valve     | Jupiter                     | [aa18022bce](https://linux-hardware.org/?probe=aa18022bce) | Jun 22, 2022 |
| Valve     | Jupiter                     | [000682313d](https://linux-hardware.org/?probe=000682313d) | Jun 20, 2022 |
| Valve     | Jupiter                     | [363ab9e4ea](https://linux-hardware.org/?probe=363ab9e4ea) | Jun 20, 2022 |
| Valve     | Jupiter                     | [dd5765a418](https://linux-hardware.org/?probe=dd5765a418) | Jun 18, 2022 |
| Valve     | Jupiter                     | [8e293bb4b1](https://linux-hardware.org/?probe=8e293bb4b1) | Jun 17, 2022 |
| Valve     | Jupiter                     | [ff0ce08944](https://linux-hardware.org/?probe=ff0ce08944) | Jun 16, 2022 |
| Valve     | Jupiter                     | [68a581ae0b](https://linux-hardware.org/?probe=68a581ae0b) | Jun 12, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [df3f1b5d8f](https://linux-hardware.org/?probe=df3f1b5d8f) | Jun 11, 2022 |
| Valve     | Jupiter                     | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Valve     | Jupiter                     | [17406c8741](https://linux-hardware.org/?probe=17406c8741) | Jun 11, 2022 |
| Valve     | Jupiter                     | [715e914cba](https://linux-hardware.org/?probe=715e914cba) | Jun 10, 2022 |
| Valve     | Jupiter                     | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Valve     | Jupiter                     | [2fb1bfad12](https://linux-hardware.org/?probe=2fb1bfad12) | Jun 04, 2022 |
| Valve     | Jupiter                     | [322bdc2ce3](https://linux-hardware.org/?probe=322bdc2ce3) | Jun 03, 2022 |
| Valve     | Jupiter                     | [780d6b923a](https://linux-hardware.org/?probe=780d6b923a) | Jun 02, 2022 |
| Valve     | Jupiter                     | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| Valve     | Jupiter                     | [e415de106f](https://linux-hardware.org/?probe=e415de106f) | May 29, 2022 |
| Valve     | Jupiter                     | [0af4b9c805](https://linux-hardware.org/?probe=0af4b9c805) | May 29, 2022 |
| Valve     | Jupiter                     | [06b56d54d4](https://linux-hardware.org/?probe=06b56d54d4) | May 28, 2022 |
| Valve     | Jupiter                     | [1e966da4f8](https://linux-hardware.org/?probe=1e966da4f8) | May 27, 2022 |
| Valve     | Jupiter                     | [c716690aa2](https://linux-hardware.org/?probe=c716690aa2) | May 27, 2022 |
| Valve     | Jupiter                     | [43f315aa0c](https://linux-hardware.org/?probe=43f315aa0c) | May 27, 2022 |
| Valve     | Jupiter                     | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [b672eefb50](https://linux-hardware.org/?probe=b672eefb50) | May 25, 2022 |
| Valve     | Jupiter                     | [dee0bbedd1](https://linux-hardware.org/?probe=dee0bbedd1) | May 25, 2022 |
| Valve     | Jupiter                     | [c34173715a](https://linux-hardware.org/?probe=c34173715a) | May 24, 2022 |
| Valve     | Jupiter                     | [6ca95b630c](https://linux-hardware.org/?probe=6ca95b630c) | May 23, 2022 |
| Valve     | Jupiter                     | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| Acer      | Aspire A315-23              | [b5d37bf4f2](https://linux-hardware.org/?probe=b5d37bf4f2) | May 22, 2022 |
| Samsung   | 950XDB/951XDB/950XDY        | [fc970670a8](https://linux-hardware.org/?probe=fc970670a8) | May 22, 2022 |
| Valve     | Jupiter                     | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Valve     | Jupiter                     | [d706d00651](https://linux-hardware.org/?probe=d706d00651) | May 21, 2022 |
| Valve     | Jupiter                     | [317e492fa3](https://linux-hardware.org/?probe=317e492fa3) | May 21, 2022 |
| Valve     | Jupiter                     | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| Valve     | Jupiter                     | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Valve     | Jupiter                     | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| Valve     | Jupiter                     | [79f6db1d69](https://linux-hardware.org/?probe=79f6db1d69) | May 08, 2022 |
| Valve     | Jupiter                     | [771539d18d](https://linux-hardware.org/?probe=771539d18d) | May 03, 2022 |
| Valve     | Jupiter                     | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Valve     | Jupiter                     | [1c826aed5e](https://linux-hardware.org/?probe=1c826aed5e) | Apr 30, 2022 |
| Valve     | Jupiter                     | [4c43342014](https://linux-hardware.org/?probe=4c43342014) | Apr 24, 2022 |
| Valve     | Jupiter                     | [8564bded7f](https://linux-hardware.org/?probe=8564bded7f) | Apr 21, 2022 |
| Valve     | Jupiter                     | [d761657c3a](https://linux-hardware.org/?probe=d761657c3a) | Apr 21, 2022 |
| Valve     | Jupiter                     | [f2e59fcb97](https://linux-hardware.org/?probe=f2e59fcb97) | Apr 20, 2022 |
| Valve     | Jupiter                     | [4f23fab4fd](https://linux-hardware.org/?probe=4f23fab4fd) | Apr 17, 2022 |
| Valve     | Jupiter                     | [ed07e93435](https://linux-hardware.org/?probe=ed07e93435) | Apr 16, 2022 |
| Valve     | Jupiter                     | [48aacdeee8](https://linux-hardware.org/?probe=48aacdeee8) | Apr 15, 2022 |
| Valve     | Jupiter                     | [6a042646dd](https://linux-hardware.org/?probe=6a042646dd) | Apr 14, 2022 |
| Valve     | Jupiter                     | [d4c9dba2a1](https://linux-hardware.org/?probe=d4c9dba2a1) | Apr 14, 2022 |
| Valve     | Jupiter                     | [852b6fb53a](https://linux-hardware.org/?probe=852b6fb53a) | Apr 08, 2022 |
| Valve     | Jupiter                     | [6129b15fb5](https://linux-hardware.org/?probe=6129b15fb5) | Apr 05, 2022 |
| Valve     | Jupiter                     | [ec05067a1d](https://linux-hardware.org/?probe=ec05067a1d) | Apr 03, 2022 |
| Valve     | Jupiter                     | [180c84c856](https://linux-hardware.org/?probe=180c84c856) | Apr 02, 2022 |
| Valve     | Jupiter                     | [d8625616de](https://linux-hardware.org/?probe=d8625616de) | Mar 30, 2022 |
| Valve     | Jupiter                     | [d181a912af](https://linux-hardware.org/?probe=d181a912af) | Mar 23, 2022 |
| Valve     | Jupiter                     | [0b6a21cf35](https://linux-hardware.org/?probe=0b6a21cf35) | Mar 18, 2022 |
| Valve     | Jupiter                     | [85328e8f3d](https://linux-hardware.org/?probe=85328e8f3d) | Mar 17, 2022 |
| Valve     | Jupiter                     | [023aea75e1](https://linux-hardware.org/?probe=023aea75e1) | Mar 14, 2022 |
| Valve     | Jupiter                     | [c7f6388908](https://linux-hardware.org/?probe=c7f6388908) | Mar 11, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| SteamOS 3.3.1                | 89        | 36.33%  |
| SteamOS 3.2                  | 57        | 23.27%  |
| SteamOS 3.3                  | 46        | 18.78%  |
| SteamOS Snapshot             | 21        | 8.57%   |
| SteamOS 3.1                  | 10        | 4.08%   |
| SteamOS 3.4                  | 6         | 2.45%   |
| SteamOS 3.3.2                | 6         | 2.45%   |
| SteamOS Rolling              | 4         | 1.63%   |
| SteamOS 3.2 (steamdeck-main) | 3         | 1.22%   |
| SteamOS                      | 3         | 1.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SteamOS | 236       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| 5.13.0-valve21.1-1-neptune-02211-gc54cda5a36f3     | 92        | 37.25%  |
| 5.13.0-valve15-1-neptune-02197-gf6ec7ad3762a       | 53        | 21.46%  |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 35        | 14.17%  |
| 5.13.0-valve10.1-1-neptune-02144-g7fffaf925dfb     | 16        | 6.48%   |
| 5.13.0-valve10.3-1-neptune-02176-g5fe416c4acd8     | 12        | 4.86%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 11        | 4.45%   |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 7         | 2.83%   |
| 5.13.0-valve21.2-1-neptune                         | 6         | 2.43%   |
| 5.13.0-valve14-1-neptune-02195-g5b0f749d00fa       | 5         | 2.02%   |
| 5.13.0-valve20-1-neptune-02207-gbd986a7e1c7f       | 4         | 1.62%   |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 3         | 1.21%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 1         | 0.4%    |
| 5.15.54-1-lts                                      | 1         | 0.4%    |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 234       | 99.15%  |
| 5.18.1  | 1         | 0.42%   |
| 5.15.54 | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 234       | 99.15%  |
| 5.18    | 1         | 0.42%   |
| 5.15    | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 236       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 233       | 98.31%  |
| gamescope | 2         | 0.84%   |
| Unknown   | 2         | 0.84%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 234       | 98.73%  |
| Wayland | 2         | 0.84%   |
| Unknown | 1         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 232       | 98.31%  |
| SDDM    | 4         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 204       | 86.08%  |
| de_DE | 6         | 2.53%   |
| en_GB | 5         | 2.11%   |
| an_ES | 4         | 1.69%   |
| fr_FR | 3         | 1.27%   |
| en_DE | 3         | 1.27%   |
| zh_CN | 2         | 0.84%   |
| sk_SK | 1         | 0.42%   |
| pt_BR | 1         | 0.42%   |
| pl_PL | 1         | 0.42%   |
| nl_NL | 1         | 0.42%   |
| it_IT | 1         | 0.42%   |
| et_EE | 1         | 0.42%   |
| es_ES | 1         | 0.42%   |
| en_NL | 1         | 0.42%   |
| en_CA | 1         | 0.42%   |
| ba_RU | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 230       | 97.46%  |
| EFI  | 6         | 2.54%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 235       | 99.58%  |
| Ext4  | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 230       | 97.46%  |
| GPT     | 6         | 2.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 230       | 97.46%  |
| Yes       | 6         | 2.54%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 236       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Valve               | 215       | 91.1%   |
| Hewlett-Packard     | 4         | 1.69%   |
| Dell                | 4         | 1.69%   |
| Lenovo              | 3         | 1.27%   |
| GPD                 | 2         | 0.85%   |
| Acer                | 2         | 0.85%   |
| Samsung Electronics | 1         | 0.42%   |
| ASUSTek Computer    | 1         | 0.42%   |
| ASRock              | 1         | 0.42%   |
| AMI                 | 1         | 0.42%   |
| Alienware           | 1         | 0.42%   |
| Unknown             | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Valve Jupiter                          | 215       | 91.1%   |
| Unknown                                | 2         | 0.85%   |
| Samsung 950XDB/951XDB/950XDY           | 1         | 0.42%   |
| Lenovo ThinkBook 13s G3 ACN 20YA       | 1         | 0.42%   |
| Lenovo Legion Y740-15IRHg 81UH         | 1         | 0.42%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 0.42%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 1         | 0.42%   |
| HP Pavilion Gaming Laptop 15-dk0xxx    | 1         | 0.42%   |
| HP Pavilion 17                         | 1         | 0.42%   |
| HP Laptop 14z-fq0000                   | 1         | 0.42%   |
| GPD G1619-04                           | 1         | 0.42%   |
| GPD G1619-02                           | 1         | 0.42%   |
| Dell XPS 15 9570                       | 1         | 0.42%   |
| Dell XPS 13 9360                       | 1         | 0.42%   |
| Dell Precision 7720                    | 1         | 0.42%   |
| Dell G15 5510                          | 1         | 0.42%   |
| ASUS ROG Zephyrus S17 GX703HSD_GX703HS | 1         | 0.42%   |
| ASRock X570 Extreme4 WiFi ax           | 1         | 0.42%   |
| Alienware m17                          | 1         | 0.42%   |
| Acer Aspire A514-54                    | 1         | 0.42%   |
| Acer Aspire A315-23                    | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Valve Jupiter    | 215       | 91.1%   |
| HP Pavilion      | 3         | 1.27%   |
| Dell XPS         | 2         | 0.85%   |
| Acer Aspire      | 2         | 0.85%   |
| Unknown          | 2         | 0.85%   |
| Samsung 950XDB   | 1         | 0.42%   |
| Lenovo ThinkBook | 1         | 0.42%   |
| Lenovo Legion    | 1         | 0.42%   |
| Lenovo IdeaPad   | 1         | 0.42%   |
| HP Laptop        | 1         | 0.42%   |
| GPD G1619-04     | 1         | 0.42%   |
| GPD G1619-02     | 1         | 0.42%   |
| Dell Precision   | 1         | 0.42%   |
| Dell G15         | 1         | 0.42%   |
| ASUS ROG         | 1         | 0.42%   |
| ASRock X570      | 1         | 0.42%   |
| Alienware m17    | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2022    | 204       | 86.44%  |
| Unknown | 12        | 5.08%   |
| 2021    | 9         | 3.81%   |
| 2020    | 3         | 1.27%   |
| 2019    | 3         | 1.27%   |
| 2017    | 2         | 0.85%   |
| 2018    | 1         | 0.42%   |
| 2016    | 1         | 0.42%   |
| 2013    | 1         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 236       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 236       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 236       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 220       | 93.22%  |
| 16.01-24.0  | 6         | 2.54%   |
| 4.01-8.0    | 5         | 2.12%   |
| 24.01-32.0  | 2         | 0.85%   |
| 32.01-64.0  | 1         | 0.42%   |
| 3.01-4.0    | 1         | 0.42%   |
| 64.01-256.0 | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 121       | 49.19%  |
| 3.01-4.0 | 59        | 23.98%  |
| 4.01-8.0 | 35        | 14.23%  |
| 1.01-2.0 | 31        | 12.6%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 139       | 57.92%  |
| 1      | 91        | 37.92%  |
| 3      | 8         | 3.33%   |
| 4      | 1         | 0.42%   |
| 0      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 232       | 98.31%  |
| Yes       | 4         | 1.69%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 176       | 73.33%  |
| Yes       | 64        | 26.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 236       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 234       | 99.15%  |
| No        | 2         | 0.85%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 117       | 49.58%  |
| Germany     | 26        | 11.02%  |
| UK          | 24        | 10.17%  |
| Canada      | 17        | 7.2%    |
| Spain       | 7         | 2.97%   |
| France      | 6         | 2.54%   |
| Poland      | 5         | 2.12%   |
| Netherlands | 5         | 2.12%   |
| Italy       | 4         | 1.69%   |
| Czechia     | 3         | 1.27%   |
| Slovakia    | 2         | 0.85%   |
| Brazil      | 2         | 0.85%   |
| Austria     | 2         | 0.85%   |
| Sweden      | 1         | 0.42%   |
| Russia      | 1         | 0.42%   |
| Romania     | 1         | 0.42%   |
| Oman        | 1         | 0.42%   |
| Malaysia    | 1         | 0.42%   |
| Latvia      | 1         | 0.42%   |
| Japan       | 1         | 0.42%   |
| Hungary     | 1         | 0.42%   |
| Guatemala   | 1         | 0.42%   |
| Greece      | 1         | 0.42%   |
| Finland     | 1         | 0.42%   |
| Estonia     | 1         | 0.42%   |
| Denmark     | 1         | 0.42%   |
| Cyprus      | 1         | 0.42%   |
| China       | 1         | 0.42%   |
| Belgium     | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Austin            | 4         | 1.67%   |
| Brooklyn          | 3         | 1.26%   |
| Washington        | 2         | 0.84%   |
| Sunnyvale         | 2         | 0.84%   |
| Seattle           | 2         | 0.84%   |
| Prague            | 2         | 0.84%   |
| Portland          | 2         | 0.84%   |
| Phoenix           | 2         | 0.84%   |
| Mississauga       | 2         | 0.84%   |
| Manchester        | 2         | 0.84%   |
| Los Angeles       | 2         | 0.84%   |
| Dresden           | 2         | 0.84%   |
| Colorado Springs  | 2         | 0.84%   |
| Calgary           | 2         | 0.84%   |
| Bristol           | 2         | 0.84%   |
| Bamberg           | 2         | 0.84%   |
| York              | 1         | 0.42%   |
| Yekaterinburg     | 1         | 0.42%   |
| Wokingham         | 1         | 0.42%   |
| Whitley Bay       | 1         | 0.42%   |
| Weaverville       | 1         | 0.42%   |
| Wausau            | 1         | 0.42%   |
| Wasungen          | 1         | 0.42%   |
| Warsaw            | 1         | 0.42%   |
| Warren            | 1         | 0.42%   |
| Waalre            | 1         | 0.42%   |
| Victoria          | 1         | 0.42%   |
| Vechelde          | 1         | 0.42%   |
| Ulm               | 1         | 0.42%   |
| Tulsa             | 1         | 0.42%   |
| Treviso           | 1         | 0.42%   |
| Torre del Mar     | 1         | 0.42%   |
| Toronto           | 1         | 0.42%   |
| Thief River Falls | 1         | 0.42%   |
| Thessaloniki      | 1         | 0.42%   |
| Temecula          | 1         | 0.42%   |
| Sylmar            | 1         | 0.42%   |
| Stuttgart         | 1         | 0.42%   |
| Stouffville       | 1         | 0.42%   |
| Stockholm         | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Unknown                        | 115       | 123    | 28.97%  |
| Kingston                       | 76        | 83     | 19.14%  |
| Phison                         | 75        | 77     | 18.89%  |
| Unknown                        | 27        | 28     | 6.8%    |
| O2 Micro                       | 18        | 19     | 4.53%   |
| Samsung Electronics            | 17        | 19     | 4.28%   |
| Silicon Motion                 | 15        | 16     | 3.78%   |
| Kingston Technology Company    | 11        | 11     | 2.77%   |
| Phison Electronics             | 10        | 10     | 2.52%   |
| SK hynix                       | 4         | 6      | 1.01%   |
| SanDisk                        | 4         | 4      | 1.01%   |
| WDC                            | 2         | 2      | 0.5%    |
| Toshiba                        | 2         | 2      | 0.5%    |
| Solid State Storage Technology | 2         | 2      | 0.5%    |
| KIOXIA                         | 2         | 2      | 0.5%    |
| JMicron Technology             | 2         | 2      | 0.5%    |
| ADATA Technology               | 2         | 2      | 0.5%    |
| Yangtze Memory Technologies    | 1         | 1      | 0.25%   |
| TrekStor                       | 1         | 1      | 0.25%   |
| SSK                            | 1         | 1      | 0.25%   |
| Seagate                        | 1         | 1      | 0.25%   |
| Realtek                        | 1         | 1      | 0.25%   |
| Micron/Crucial Technology      | 1         | 1      | 0.25%   |
| Micron Technology              | 1         | 1      | 0.25%   |
| Lexar 25                       | 1         | 1      | 0.25%   |
| Inateck                        | 1         | 1      | 0.25%   |
| External                       | 1         | 2      | 0.25%   |
| Crucial                        | 1         | 1      | 0.25%   |
| Biwin Storage Technology       | 1         | 1      | 0.25%   |
| ASMT                           | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Phison NVMe SSD Drive 512GB                            | 54        | 13.43%  |
| Unknown MMC Card  512GB                                | 47        | 11.69%  |
| Kingston NVMe SSD Drive 512GB                          | 42        | 10.45%  |
| Kingston NVMe SSD Drive 256GB                          | 32        | 7.96%   |
| Unknown                                                | 27        | 6.72%   |
| Unknown MMC Card  128GB                                | 19        | 4.73%   |
| Phison NVMe SSD Drive 256GB                            | 18        | 4.48%   |
| Unknown MMC Card  256GB                                | 17        | 4.23%   |
| O2 Micro NVMe SSD Drive 64GB                           | 15        | 3.73%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB                | 11        | 2.74%   |
| Phison PS5013 E13 NVMe Controller 512GB                | 10        | 2.49%   |
| Silicon Motion NVMe SSD Drive 512GB                    | 8         | 1.99%   |
| Unknown MMC Card  393GB                                | 7         | 1.74%   |
| Unknown MMC Card  64GB                                 | 5         | 1.24%   |
| Unknown MMC Card  32GB                                 | 5         | 1.24%   |
| Silicon Motion NVMe SSD Drive 256GB                    | 5         | 1.24%   |
| O2 Micro E2M2 64GB                                     | 4         | 1%      |
| Unknown MMC Card  498GB                                | 3         | 0.75%   |
| Samsung NVMe SSD Drive 512GB                           | 3         | 0.75%   |
| Samsung NVMe SSD Drive 1024GB                          | 3         | 0.75%   |
| Unknown MMC Card  196GB                                | 2         | 0.5%    |
| Unknown MMC Card  16GB                                 | 2         | 0.5%    |
| SK hynix NVMe SSD Drive 1024GB                         | 2         | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 2         | 0.5%    |
| SanDisk NVMe SSD Drive 512GB                           | 2         | 0.5%    |
| Samsung MZ9LQ512HBLU-00BVL 512GB                       | 2         | 0.5%    |
| Samsung MZ9LQ256HBJD-00BVL 256GB                       | 2         | 0.5%    |
| Phison ESMP512GKB4C3-E13TS 512GB                       | 2         | 0.5%    |
| Kingston OM3PDP3512B-A01 512GB                         | 2         | 0.5%    |
| JMicron Generic 120GB                                  | 2         | 0.5%    |
| Yangtze Memory NVMe SSD Drive 1024GB                   | 1         | 0.25%   |
| WDC WD10SPZX-75Z10T2 1TB                               | 1         | 0.25%   |
| WDC CH SN530 SDBPTPZ-1T00-1024 930GB                   | 1         | 0.25%   |
| Unknown SK256  256GB                                   | 1         | 0.25%   |
| Unknown MMC Card  500GB                                | 1         | 0.25%   |
| Unknown MMC Card  250GB                                | 1         | 0.25%   |
| Unknown MMC Card  248GB                                | 1         | 0.25%   |
| Unknown MMC Card  1TB                                  | 1         | 0.25%   |
| Unknown MMC Card  1073GB                               | 1         | 0.25%   |
| Unknown MMC Card  1048GB                               | 1         | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| ASMT    | 1         | 1      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 50%     |
| TrekStor            | 1         | 1      | 16.67%  |
| Lexar 25            | 1         | 1      | 16.67%  |
| Crucial             | 1         | 1      | 16.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 232       | 261    | 60.57%  |
| MMC     | 141       | 151    | 36.81%  |
| SSD     | 6         | 6      | 1.57%   |
| HDD     | 3         | 3      | 0.78%   |
| Unknown | 1         | 1      | 0.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 232       | 255    | 59.95%  |
| MMC  | 141       | 151    | 36.43%  |
| SAS  | 10        | 11     | 2.58%   |
| SATA | 4         | 5      | 1.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5         | 5      | 55.56%  |
| 0.51-1.0   | 4         | 4      | 44.44%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 126       | 52.72%  |
| 101-250        | 68        | 28.45%  |
| 501-1000       | 24        | 10.04%  |
| 51-100         | 17        | 7.11%   |
| 1001-2000      | 3         | 1.26%   |
| More than 3000 | 1         | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 99        | 40.57%  |
| 251-500   | 71        | 29.1%   |
| 21-50     | 33        | 13.52%  |
| 1-20      | 19        | 7.79%   |
| 51-100    | 17        | 6.97%   |
| 501-1000  | 4         | 1.64%   |
| 1001-2000 | 1         | 0.41%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 234       | 416    | 97.5%   |
| Works    | 6         | 6      | 2.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Kingston Technology Company    | 86        | 34.68%  |
| Phison Electronics             | 83        | 33.47%  |
| O2 Micro                       | 18        | 7.26%   |
| Silicon Motion                 | 15        | 6.05%   |
| Samsung Electronics            | 14        | 5.65%   |
| Intel                          | 7         | 2.82%   |
| SanDisk                        | 5         | 2.02%   |
| SK hynix                       | 4         | 1.61%   |
| AMD                            | 4         | 1.61%   |
| Toshiba America Info Systems   | 2         | 0.81%   |
| Solid State Storage Technology | 2         | 0.81%   |
| KIOXIA                         | 2         | 0.81%   |
| ADATA Technology               | 2         | 0.81%   |
| Yangtze Memory Technologies    | 1         | 0.4%    |
| Micron/Crucial Technology      | 1         | 0.4%    |
| Micron Technology              | 1         | 0.4%    |
| Biwin Storage Technology       | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                                             | 85        | 34%     |
| Phison PS5013 E13 NVMe Controller                                             | 81        | 32.4%   |
| O2 Micro Non-Volatile memory controller                                       | 18        | 7.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 15        | 6%      |
| Samsung NVMe SSD Controller 980                                               | 10        | 4%      |
| SK hynix Gold P31 SSD                                                         | 4         | 1.6%    |
| AMD FCH SATA Controller [AHCI mode]                                           | 4         | 1.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 1.2%    |
| Solid State Storage Non-Volatile memory controller                            | 2         | 0.8%    |
| SanDisk PC SN530 NVMe SSD                                                     | 2         | 0.8%    |
| SanDisk Non-Volatile memory controller                                        | 2         | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 2         | 0.8%    |
| Phison E12 NVMe Controller                                                    | 2         | 0.8%    |
| KIOXIA NVMe SSD Controller BG4                                                | 2         | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 0.8%    |
| ADATA Non-Volatile memory controller                                          | 2         | 0.8%    |
| Yangtze Memory Non-Volatile memory controller                                 | 1         | 0.4%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.4%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 0.4%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 0.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 0.4%    |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1         | 0.4%    |
| Micron Non-Volatile memory controller                                         | 1         | 0.4%    |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 0.4%    |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 0.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 0.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 0.4%    |
| Biwin Storage Non-Volatile memory controller                                  | 1         | 0.4%    |
| AMD FCH IDE Controller                                                        | 1         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 232       | 94.69%  |
| SATA | 7         | 2.86%   |
| RAID | 5         | 2.04%   |
| IDE  | 1         | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| AMD    | 224       | 94.92%  |
| Intel  | 12        | 5.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 215       | 91.1%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.85%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.85%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.42%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.42%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.42%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.42%   |
| Intel Atom x7-Z8750 CPU @ 1.60GHz             | 1         | 0.42%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 0.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 0.42%   |
| Intel 11th Gen Core i7-1160G7 @ 1.20GHz       | 1         | 0.42%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 0.42%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 0.42%   |
| AMD Ryzen 7 6800U with Radeon Graphics        | 1         | 0.42%   |
| AMD Ryzen 7 4800U with Radeon Graphics        | 1         | 0.42%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 0.42%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 0.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 0.42%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 1         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Other         | 219       | 92.8%   |
| Intel Core i7 | 5         | 2.12%   |
| AMD Ryzen 5   | 5         | 2.12%   |
| AMD Ryzen 7   | 2         | 0.85%   |
| Intel Xeon    | 1         | 0.42%   |
| Intel Core i5 | 1         | 0.42%   |
| Intel Atom    | 1         | 0.42%   |
| AMD Ryzen 9   | 1         | 0.42%   |
| AMD A8        | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 221       | 93.64%  |
| 6      | 6         | 2.54%   |
| 8      | 4         | 1.69%   |
| 2      | 4         | 1.69%   |
| 12     | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 236       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 234       | 98.73%  |
| 1      | 3         | 1.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 236       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 230       | 97.46%  |
| 0x08900201 | 6         | 2.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 217       | 91.95%  |
| KabyLake   | 5         | 2.12%   |
| Zen 3      | 3         | 1.27%   |
| Zen 2      | 3         | 1.27%   |
| TigerLake  | 3         | 1.27%   |
| Zen+       | 1         | 0.42%   |
| Skylake    | 1         | 0.42%   |
| Silvermont | 1         | 0.42%   |
| Piledriver | 1         | 0.42%   |
| CometLake  | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| AMD    | 224       | 92.18%  |
| Intel  | 10        | 4.12%   |
| Nvidia | 9         | 3.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 215       | 88.48%  |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.23%   |
| AMD Cezanne                                                                              | 3         | 1.23%   |
| AMD Renoir                                                                               | 2         | 0.82%   |
| Nvidia TU117M                                                                            | 1         | 0.41%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.41%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.41%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.41%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.41%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 0.41%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.41%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.41%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 0.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.41%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.41%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.41%   |
| Intel Tiger Lake Iris Xe Graphics                                                        | 1         | 0.41%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 0.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.41%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 1         | 0.41%   |
| AMD Rembrandt [Radeon 680M]                                                              | 1         | 0.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 0.41%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 222       | 94.07%  |
| Intel + Nvidia | 5         | 2.12%   |
| 1 x Intel      | 5         | 2.12%   |
| 1 x Nvidia     | 2         | 0.85%   |
| AMD + Nvidia   | 2         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 230       | 97.46%  |
| Proprietary | 6         | 2.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 228       | 96.61%  |
| 0.51-1.0   | 5         | 2.12%   |
| 7.01-8.0   | 1         | 0.42%   |
| 5.01-6.0   | 1         | 0.42%   |
| 1.01-2.0   | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| ANX                  | 189       | 65.85%  |
| Analogix             | 18        | 6.27%   |
| Goldstar             | 10        | 3.48%   |
| Valve                | 9         | 3.14%   |
| Samsung Electronics  | 7         | 2.44%   |
| BOE                  | 5         | 1.74%   |
| Vizio                | 4         | 1.39%   |
| Chimei Innolux       | 4         | 1.39%   |
| AOC                  | 4         | 1.39%   |
| Ancor Communications | 4         | 1.39%   |
| AU Optronics         | 3         | 1.05%   |
| Sony                 | 2         | 0.7%    |
| Sharp                | 2         | 0.7%    |
| Philips              | 2         | 0.7%    |
| Microsoft            | 2         | 0.7%    |
| Hewlett-Packard      | 2         | 0.7%    |
| Dell                 | 2         | 0.7%    |
| ASUSTek Computer     | 2         | 0.7%    |
| ZSC                  | 1         | 0.35%   |
| YTH                  | 1         | 0.35%   |
| TCL                  | 1         | 0.35%   |
| Sun                  | 1         | 0.35%   |
| RTK                  | 1         | 0.35%   |
| Pixio                | 1         | 0.35%   |
| MSI                  | 1         | 0.35%   |
| LTM                  | 1         | 0.35%   |
| LG Display           | 1         | 0.35%   |
| JDI                  | 1         | 0.35%   |
| Huion                | 1         | 0.35%   |
| GreenWood            | 1         | 0.35%   |
| GBR                  | 1         | 0.35%   |
| EXP                  | 1         | 0.35%   |
| CMS                  | 1         | 0.35%   |
| Acer                 | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ANX ANX7530 U ANX7539 800x1280                                         | 189       | 65.85%  |
| Analogix ANX7530 U ANX7539 800x1280                                    | 18        | 6.27%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 9         | 3.14%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 3         | 1.05%   |
| Microsoft Xbox One MSH0001 1920x1080 520x290mm 23.4-inch               | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch       | 2         | 0.7%    |
| Ancor Communications ASUS VH242H ACI24F3 1920x1080 521x293mm 23.5-inch | 2         | 0.7%    |
| ZSC FHD HDR ZSCBC32 1920x1080 344x195mm 15.6-inch                      | 1         | 0.35%   |
| YTH HS133PC YTH1330 1920x1080 255x220mm 13.3-inch                      | 1         | 0.35%   |
| Vizio M58Q7-J01 VIZ1039 3840x2160 1212x682mm 54.8-inch                 | 1         | 0.35%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 0.35%   |
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                  | 1         | 0.35%   |
| Vizio D24f4-J01 VIZ1044 1920x1080 527x296mm 23.8-inch                  | 1         | 0.35%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                    | 1         | 0.35%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                 | 1         | 0.35%   |
| Sony TV *00 SNY7A04 3840x2160 1218x685mm 55.0-inch                     | 1         | 0.35%   |
| Sony BW8 MS_9001 2560x1600                                             | 1         | 0.35%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.35%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.35%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch      | 1         | 0.35%   |
| Samsung Electronics S27HG5x SAM0E10 2560x1440 598x336mm 27.0-inch      | 1         | 0.35%   |
| Samsung Electronics S27A750D SAM0798 1920x1080 598x336mm 27.0-inch     | 1         | 0.35%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch  | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SAM0A7E 1920x1080 1060x626mm 48.5-inch | 1         | 0.35%   |
| Samsung Electronics C49HG9x SAM0E5D 1920x1080 1196x336mm 48.9-inch     | 1         | 0.35%   |
| RTK UHD HDR RTK1B1A 3840x2160 609x355mm 27.8-inch                      | 1         | 0.35%   |
| Pixio PX277P PNS0277 2560x1440 620x370mm 28.4-inch                     | 1         | 0.35%   |
| Philips PHL 345B1C PHL093D 3440x1440 797x334mm 34.0-inch               | 1         | 0.35%   |
| Philips PHL 326M6V PHLC193 3840x2160 698x398mm 31.6-inch               | 1         | 0.35%   |
| MSI MPG341CQR MSI3DA0 3440x1440 797x334mm 34.0-inch                    | 1         | 0.35%   |
| LTM LT7911D LTM08E1 1024x768 140x140mm 7.8-inch                        | 1         | 0.35%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch            | 1         | 0.35%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                     | 1         | 0.35%   |
| Huion GT221 HAT2150 1920x1080 476x267mm 21.5-inch                      | 1         | 0.35%   |
| Hewlett-Packard S230tm HWP3115 1920x1080 509x286mm 23.0-inch           | 1         | 0.35%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch              | 1         | 0.35%   |
| GreenWood ARZOPA GWD1581 1920x1080 350x200mm 15.9-inch                 | 1         | 0.35%   |
| Goldstar ULTRAWIDE GSM76F6 1920x1080 800x335mm 34.1-inch               | 1         | 0.35%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 800x1280          | 211       | 75.09%  |
| 1920x1080 (FHD)   | 33        | 11.74%  |
| 3840x2160 (4K)    | 12        | 4.27%   |
| 3440x1440         | 7         | 2.49%   |
| 2560x1440 (QHD)   | 4         | 1.42%   |
| 2560x1600         | 3         | 1.07%   |
| 2560x1080         | 3         | 1.07%   |
| 1366x768 (WXGA)   | 3         | 1.07%   |
| 3840x1080         | 1         | 0.36%   |
| 3200x1800 (QHD+)  | 1         | 0.36%   |
| 1920x1200 (WUXGA) | 1         | 0.36%   |
| 1600x900 (HD+)    | 1         | 0.36%   |
| 1024x768 (XGA)    | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 205       | 71.93%  |
| 15      | 12        | 4.21%   |
| 7       | 10        | 3.51%   |
| 34      | 8         | 2.81%   |
| 27      | 8         | 2.81%   |
| 23      | 6         | 2.11%   |
| 17      | 4         | 1.4%    |
| 13      | 4         | 1.4%    |
| 72      | 3         | 1.05%   |
| 31      | 3         | 1.05%   |
| 64      | 2         | 0.7%    |
| 54      | 2         | 0.7%    |
| 49      | 2         | 0.7%    |
| 40      | 2         | 0.7%    |
| 24      | 2         | 0.7%    |
| 21      | 2         | 0.7%    |
| 69      | 1         | 0.35%   |
| 57      | 1         | 0.35%   |
| 55      | 1         | 0.35%   |
| 52      | 1         | 0.35%   |
| 42      | 1         | 0.35%   |
| 36      | 1         | 0.35%   |
| 35      | 1         | 0.35%   |
| 28      | 1         | 0.35%   |
| 14      | 1         | 0.35%   |
| 8       | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 205       | 72.18%  |
| 501-600     | 15        | 5.28%   |
| 301-350     | 14        | 4.93%   |
| 701-800     | 9         | 3.17%   |
| 1-100       | 9         | 3.17%   |
| 1001-1500   | 8         | 2.82%   |
| 601-700     | 5         | 1.76%   |
| 351-400     | 4         | 1.41%   |
| 1501-2000   | 4         | 1.41%   |
| 801-900     | 3         | 1.06%   |
| 201-300     | 3         | 1.06%   |
| 401-500     | 2         | 0.7%    |
| 101-200     | 2         | 0.7%    |
| 901-1000    | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 0.62  | 206       | 73.31%  |
| 16/9  | 53        | 18.86%  |
| 21/9  | 9         | 3.2%    |
| 0.67  | 9         | 3.2%    |
| 16/10 | 2         | 0.71%   |
| 32/9  | 1         | 0.36%   |
| 1.00  | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 205       | 72.18%  |
| 351-500        | 13        | 4.58%   |
| More than 1000 | 11        | 3.87%   |
| 1-40           | 11        | 3.87%   |
| 101-110        | 11        | 3.87%   |
| 301-350        | 8         | 2.82%   |
| 201-250        | 7         | 2.46%   |
| 501-1000       | 5         | 1.76%   |
| 121-130        | 4         | 1.41%   |
| 71-80          | 3         | 1.06%   |
| 81-90          | 2         | 0.7%    |
| 251-300        | 2         | 0.7%    |
| 151-200        | 1         | 0.35%   |
| 91-100         | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 205       | 72.18%  |
| 51-100        | 25        | 8.8%    |
| 121-160       | 16        | 5.63%   |
| 101-120       | 16        | 5.63%   |
| 161-240       | 14        | 4.93%   |
| 1-50          | 6         | 2.11%   |
| More than 240 | 2         | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 196       | 82.01%  |
| 2     | 41        | 17.15%  |
| 3     | 2         | 0.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 227       | 81.07%  |
| ASIX Electronics      | 25        | 8.93%   |
| Intel                 | 12        | 4.29%   |
| Qualcomm Atheros      | 4         | 1.43%   |
| DisplayLink           | 3         | 1.07%   |
| TP-Link               | 2         | 0.71%   |
| MediaTek              | 2         | 0.71%   |
| Lenovo                | 1         | 0.36%   |
| Google                | 1         | 0.36%   |
| Dell                  | 1         | 0.36%   |
| Broadcom              | 1         | 0.36%   |
| AVM                   | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 215       | 70.03%  |
| ASIX AX88179 Gigabit Ethernet                                     | 25        | 8.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 7.49%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 2.28%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.65%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.65%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.33%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.33%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.33%   |
| Intel Wireless 7265                                               | 1         | 0.33%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.33%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.33%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 0.33%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 0.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.33%   |
| Google Pixel 6                                                    | 1         | 0.33%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 0.33%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                              | 1         | 0.33%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                | 1         | 0.33%   |
| AVM FRITZ!WLAN AC 860                                             | 1         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 217       | 90.42%  |
| Intel                 | 12        | 5%      |
| Qualcomm Atheros      | 4         | 1.67%   |
| TP-Link               | 2         | 0.83%   |
| MediaTek              | 2         | 0.83%   |
| Dell                  | 1         | 0.42%   |
| Broadcom              | 1         | 0.42%   |
| AVM                   | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 215       | 89.58%  |
| Intel Wi-Fi 6 AX200                                           | 4         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 0.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 0.83%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 0.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.42%   |
| TP-Link Archer T4U ver.3                                      | 1         | 0.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 0.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 0.42%   |
| Intel Wireless 7265                                           | 1         | 0.42%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 0.42%   |
| Intel Centrino Advanced-N 6235                                | 1         | 0.42%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 0.42%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                          | 1         | 0.42%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter            | 1         | 0.42%   |
| AVM FRITZ!WLAN AC 860                                         | 1         | 0.42%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 32        | 48.48%  |
| ASIX Electronics      | 25        | 37.88%  |
| Intel                 | 3         | 4.55%   |
| DisplayLink           | 3         | 4.55%   |
| Qualcomm Atheros      | 1         | 1.52%   |
| Lenovo                | 1         | 1.52%   |
| Google                | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| ASIX AX88179 Gigabit Ethernet                                     | 25        | 37.31%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 34.33%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 10.45%  |
| DisplayLink Dell Universal Dock D6000                             | 2         | 2.99%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.49%   |
| Lenovo ThinkPad Lan                                               | 1         | 1.49%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.49%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.49%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.49%   |
| Google Pixel 6                                                    | 1         | 1.49%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 236       | 78.67%  |
| Ethernet | 64        | 21.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 225       | 89.29%  |
| Ethernet | 27        | 10.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 223       | 94.49%  |
| 2     | 13        | 5.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 152       | 64.14%  |
| Yes  | 85        | 35.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 215       | 91.88%  |
| Intel                           | 12        | 5.13%   |
| Qualcomm Atheros Communications | 3         | 1.28%   |
| Realtek Semiconductor           | 2         | 0.85%   |
| Lite-On Technology              | 1         | 0.43%   |
| Foxconn / Hon Hai               | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| IMC Networks 802.11ac WLAN Adapter             | 215       | 91.88%  |
| Intel AX200 Bluetooth                          | 4         | 1.71%   |
| Intel AX201 Bluetooth                          | 3         | 1.28%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 0.85%   |
| Intel AX210 Bluetooth                          | 2         | 0.85%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 0.43%   |
| Realtek Bluetooth Radio                        | 1         | 0.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 0.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 0.43%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 0.43%   |
| Intel Bluetooth wireless interface             | 1         | 0.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 0.43%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| AMD                   | 224       | 87.84%  |
| Intel                 | 11        | 4.31%   |
| Nvidia                | 7         | 2.75%   |
| C-Media Electronics   | 2         | 0.78%   |
| Blue Microphones      | 2         | 0.78%   |
| Sony                  | 1         | 0.39%   |
| Realtek Semiconductor | 1         | 0.39%   |
| Razer USA             | 1         | 0.39%   |
| MosArt Semiconductor  | 1         | 0.39%   |
| Logitech              | 1         | 0.39%   |
| Lenovo                | 1         | 0.39%   |
| Kingston Technology   | 1         | 0.39%   |
| JMTek                 | 1         | 0.39%   |
| GN Netcom             | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller          | 216       | 82.13%  |
| AMD Family 17h/19h HD Audio Controller                         | 7         | 2.66%   |
| Intel Cannon Lake PCH cAVS                                     | 4         | 1.52%   |
| AMD Renoir Radeon High Definition Audio Controller             | 4         | 1.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller    | 3         | 1.14%   |
| Nvidia TU106 High Definition Audio Controller                  | 2         | 0.76%   |
| Sony DualSense wireless controller (PS5)                       | 1         | 0.38%   |
| Realtek Semiconductor USB Audio                                | 1         | 0.38%   |
| Razer USA Razer Barracuda Pro 2.4                              | 1         | 0.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller | 1         | 0.38%   |
| Nvidia GP107GL High Definition Audio Controller                | 1         | 0.38%   |
| Nvidia GP104 High Definition Audio Controller                  | 1         | 0.38%   |
| Nvidia GA106 High Definition Audio Controller                  | 1         | 0.38%   |
| Nvidia GA104 High Definition Audio Controller                  | 1         | 0.38%   |
| MosArt Semiconductor MosArt USB Audio Device                   | 1         | 0.38%   |
| Logitech G432 Gaming Headset                                   | 1         | 0.38%   |
| Lenovo ThinkPad USB-C Dock Audio                               | 1         | 0.38%   |
| Kingston Technology HyperX QuadCast                            | 1         | 0.38%   |
| JMTek USB PnP Audio Device(EEPROM)                             | 1         | 0.38%   |
| Intel Tiger Lake-H HD Audio Controller                         | 1         | 0.38%   |
| Intel Sunrise Point-LP HD Audio                                | 1         | 0.38%   |
| Intel Comet Lake PCH cAVS                                      | 1         | 0.38%   |
| Intel CM238 HD Audio Controller                                | 1         | 0.38%   |
| GN Netcom Jabra Link 370                                       | 1         | 0.38%   |
| C-Media Electronics USB MICROPHONE                             | 1         | 0.38%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)              | 1         | 0.38%   |
| Blue Microphones Yeti Stereo Microphone                        | 1         | 0.38%   |
| Blue Microphones Yeti Nano                                     | 1         | 0.38%   |
| AMD Trinity HDMI Audio Controller                              | 1         | 0.38%   |
| AMD Starship/Matisse HD Audio Controller                       | 1         | 0.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller            | 1         | 0.38%   |
| AMD Navi 10 HDMI Audio                                         | 1         | 0.38%   |
| AMD FCH Azalia Controller                                      | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 6         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 6         | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| LPDDR5 | 6         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 6         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 6         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 4266  | 6         | 100%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| HP Laserjet CP1525nw | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 3         | 13.64%  |
| Realtek Semiconductor         | 2         | 9.09%   |
| Quanta                        | 2         | 9.09%   |
| Microdia                      | 2         | 9.09%   |
| Logitech                      | 2         | 9.09%   |
| Unknown                       | 1         | 4.55%   |
| Tripath Technology            | 1         | 4.55%   |
| Syntek                        | 1         | 4.55%   |
| Suyin                         | 1         | 4.55%   |
| SunplusIT                     | 1         | 4.55%   |
| Sunplus Innovation Technology | 1         | 4.55%   |
| Samsung Electronics           | 1         | 4.55%   |
| Luxvisions Innotech Limited   | 1         | 4.55%   |
| IMC Networks                  | 1         | 4.55%   |
| AVerMedia Technologies        | 1         | 4.55%   |
| Acer                          | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown 720p HD Camera                              | 1         | 4.55%   |
| Tripath USB Camera                                  | 1         | 4.55%   |
| Syntek Integrated Camera                            | 1         | 4.55%   |
| Suyin HP Truevision HD                              | 1         | 4.55%   |
| SunplusIT CODi A05020 Webcam                        | 1         | 4.55%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 4.55%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 4.55%   |
| Realtek NexiGo N660P FHD Webcam                     | 1         | 4.55%   |
| Realtek Integrated_Webcam_HD                        | 1         | 4.55%   |
| Quanta VGA WebCam                                   | 1         | 4.55%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 4.55%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.55%   |
| Microdia Integrated Webcam HD                       | 1         | 4.55%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.55%   |
| Logitech HD Pro Webcam C920                         | 1         | 4.55%   |
| Logitech CrystalCam                                 | 1         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 4.55%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 4.55%   |
| Chicony HP TrueVision HD Camera                     | 1         | 4.55%   |
| Chicony HD User Facing                              | 1         | 4.55%   |
| AVerMedia Live Streamer CAM 313                     | 1         | 4.55%   |
| Acer Integrated Camera                              | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| SCM Microsystems | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| SCM Microsystems SCR3500 A Contact Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 225       | 95.34%  |
| 1     | 8         | 3.39%   |
| 2     | 3         | 1.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 4         | 28.57%  |
| Multimedia controller | 4         | 28.57%  |
| Graphics card         | 3         | 21.43%  |
| Modem                 | 1         | 7.14%   |
| Fingerprint reader    | 1         | 7.14%   |
| Chipcard              | 1         | 7.14%   |

