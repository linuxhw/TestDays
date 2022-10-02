ALT Linux - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for ALT Linux.

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

Total: 265

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | B560M PRO-VDH               | [34db101d55](https://linux-hardware.org/?probe=34db101d55) | Sep 22, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [b8609443fe](https://linux-hardware.org/?probe=b8609443fe) | Sep 17, 2022 |
| Gigabyte      | M57SLI-S4                   | [0384b171c7](https://linux-hardware.org/?probe=0384b171c7) | Sep 03, 2022 |
| ASUSTek       | F2A85-V                     | [a6a798ce96](https://linux-hardware.org/?probe=a6a798ce96) | Aug 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [315c1df30c](https://linux-hardware.org/?probe=315c1df30c) | Aug 16, 2022 |
| Dell          | 0W0CHX A00                  | [7d9b8e0f96](https://linux-hardware.org/?probe=7d9b8e0f96) | Aug 01, 2022 |
| OEM           | KX-18 V1.0                  | [a68e653aa9](https://linux-hardware.org/?probe=a68e653aa9) | Jul 14, 2022 |
| Gigabyte      | Z77MX-D3H                   | [c8051cd18e](https://linux-hardware.org/?probe=c8051cd18e) | Jul 13, 2022 |
| MSI           | PRO H610M-G DDR4            | [7a95d588c4](https://linux-hardware.org/?probe=7a95d588c4) | Jul 05, 2022 |
| Gigabyte      | GA-A75M-D2H                 | [7411d7a561](https://linux-hardware.org/?probe=7411d7a561) | Jun 23, 2022 |
| MSI           | Z77A-G43                    | [2724c1558a](https://linux-hardware.org/?probe=2724c1558a) | Jun 20, 2022 |
| MAINBRD       | OPS62A-SHA                  | [8fe4a74fa3](https://linux-hardware.org/?probe=8fe4a74fa3) | Jun 10, 2022 |
| MAINBRD       | OPS62A-SHA                  | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [31ab5150ea](https://linux-hardware.org/?probe=31ab5150ea) | Jun 06, 2022 |
| ASUSTek       | PRIME Z390-A                | [4fa81ba66a](https://linux-hardware.org/?probe=4fa81ba66a) | Jun 06, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [fb935ea1d0](https://linux-hardware.org/?probe=fb935ea1d0) | Jun 03, 2022 |
| ASUSTek       | M4A78-EM                    | [7bfddcecee](https://linux-hardware.org/?probe=7bfddcecee) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [acc0a6ae9c](https://linux-hardware.org/?probe=acc0a6ae9c) | May 31, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [4ad9ca01bd](https://linux-hardware.org/?probe=4ad9ca01bd) | May 31, 2022 |
| ASUSTek       | PRO H410T                   | [7d7a4c7536](https://linux-hardware.org/?probe=7d7a4c7536) | May 25, 2022 |
| ASUSTek       | M4A78-EM                    | [37a8e41d00](https://linux-hardware.org/?probe=37a8e41d00) | May 25, 2022 |
| Gigabyte      | EP45-UD3LR                  | [ea7f269697](https://linux-hardware.org/?probe=ea7f269697) | May 24, 2022 |
| MAINBRD       | OPS62A-SHA                  | [9450237ae3](https://linux-hardware.org/?probe=9450237ae3) | May 23, 2022 |
| MAINBRD       | OPS62A-SHA                  | [ad85836549](https://linux-hardware.org/?probe=ad85836549) | May 20, 2022 |
| iRU           | LPGR.469559.012             | [9163b267bc](https://linux-hardware.org/?probe=9163b267bc) | May 19, 2022 |
| ASUSTek       | M4A78-EM                    | [ac65146c38](https://linux-hardware.org/?probe=ac65146c38) | May 17, 2022 |
| ASUSTek       | PRO H410T                   | [8ededa12ef](https://linux-hardware.org/?probe=8ededa12ef) | May 16, 2022 |
| ASUSTek       | M4A78-EM                    | [bedc08df5b](https://linux-hardware.org/?probe=bedc08df5b) | May 15, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | [cfb12880a5](https://linux-hardware.org/?probe=cfb12880a5) | May 11, 2022 |
| ASRock        | H61M-GE                     | [fefe67c0d4](https://linux-hardware.org/?probe=fefe67c0d4) | May 05, 2022 |
| Intel         | SKYBAY                      | [4891bdbd5c](https://linux-hardware.org/?probe=4891bdbd5c) | May 04, 2022 |
| ASRock        | A300M-STX                   | [48af028244](https://linux-hardware.org/?probe=48af028244) | Apr 29, 2022 |
| Lenovo        | NOK                         | [4ea735896c](https://linux-hardware.org/?probe=4ea735896c) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | [c75ef7f42d](https://linux-hardware.org/?probe=c75ef7f42d) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | [af1b36d1f6](https://linux-hardware.org/?probe=af1b36d1f6) | Apr 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | [e612a2bab1](https://linux-hardware.org/?probe=e612a2bab1) | Apr 27, 2022 |
| Lenovo        | NOK                         | [6d17068770](https://linux-hardware.org/?probe=6d17068770) | Apr 27, 2022 |
| Acer          | Veriton X2640G V:1.0        | [f1e5d5715f](https://linux-hardware.org/?probe=f1e5d5715f) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [a0e3085b4c](https://linux-hardware.org/?probe=a0e3085b4c) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [9819b3fc78](https://linux-hardware.org/?probe=9819b3fc78) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [d27d03b7e4](https://linux-hardware.org/?probe=d27d03b7e4) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [a8784c861a](https://linux-hardware.org/?probe=a8784c861a) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [b970feef75](https://linux-hardware.org/?probe=b970feef75) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [6bfffcf96a](https://linux-hardware.org/?probe=6bfffcf96a) | Apr 25, 2022 |
| Unknown       | Unknown                     | [c7c9ed4c0e](https://linux-hardware.org/?probe=c7c9ed4c0e) | Apr 21, 2022 |
| Intel         | SKYBAY                      | [ec99a4a73b](https://linux-hardware.org/?probe=ec99a4a73b) | Apr 19, 2022 |
| Intel         | SKYBAY                      | [807bf178aa](https://linux-hardware.org/?probe=807bf178aa) | Apr 19, 2022 |
| Intel         | SKYBAY                      | [5ce5f89e30](https://linux-hardware.org/?probe=5ce5f89e30) | Apr 18, 2022 |
| Intel         | SKYBAY                      | [016707b662](https://linux-hardware.org/?probe=016707b662) | Apr 18, 2022 |
| Acer          | Veriton X2640G V:1.0        | [472e946f77](https://linux-hardware.org/?probe=472e946f77) | Apr 18, 2022 |
| Intel         | SKYBAY                      | [f227fe1fc7](https://linux-hardware.org/?probe=f227fe1fc7) | Apr 18, 2022 |
| Intel         | SKYBAY                      | [49039d6324](https://linux-hardware.org/?probe=49039d6324) | Apr 18, 2022 |
| Intel         | SKYBAY                      | [39553516dd](https://linux-hardware.org/?probe=39553516dd) | Apr 18, 2022 |
| Intel         | SKYBAY                      | [9f87ee8978](https://linux-hardware.org/?probe=9f87ee8978) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [bf274bc0f4](https://linux-hardware.org/?probe=bf274bc0f4) | Apr 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [53137ae702](https://linux-hardware.org/?probe=53137ae702) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | [a98b8b4304](https://linux-hardware.org/?probe=a98b8b4304) | Apr 14, 2022 |
| Intel         | SKYBAY                      | [0d3978670a](https://linux-hardware.org/?probe=0d3978670a) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | [3829d7dfca](https://linux-hardware.org/?probe=3829d7dfca) | Apr 14, 2022 |
| Intel         | SKYBAY                      | [13122b16be](https://linux-hardware.org/?probe=13122b16be) | Apr 14, 2022 |
| Intel         | SKYBAY                      | [82df5d5154](https://linux-hardware.org/?probe=82df5d5154) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [c55e8d0780](https://linux-hardware.org/?probe=c55e8d0780) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [46344da31f](https://linux-hardware.org/?probe=46344da31f) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [906a9f0a46](https://linux-hardware.org/?probe=906a9f0a46) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [482922befd](https://linux-hardware.org/?probe=482922befd) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [2cb7352d17](https://linux-hardware.org/?probe=2cb7352d17) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [54f3bbf0af](https://linux-hardware.org/?probe=54f3bbf0af) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [f7d3604a6b](https://linux-hardware.org/?probe=f7d3604a6b) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [40083e1990](https://linux-hardware.org/?probe=40083e1990) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [ecf34aa4f0](https://linux-hardware.org/?probe=ecf34aa4f0) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [baf8cdeb1a](https://linux-hardware.org/?probe=baf8cdeb1a) | Apr 13, 2022 |
| Gigabyte      | G31M-ES2L                   | [1eacb6915d](https://linux-hardware.org/?probe=1eacb6915d) | Apr 12, 2022 |
| MSI           | A68HM-E33 V2                | [0fecbe6cdc](https://linux-hardware.org/?probe=0fecbe6cdc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [97d94278ea](https://linux-hardware.org/?probe=97d94278ea) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [5ebaca158a](https://linux-hardware.org/?probe=5ebaca158a) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [7e40f60767](https://linux-hardware.org/?probe=7e40f60767) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [ce83b095fe](https://linux-hardware.org/?probe=ce83b095fe) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | [105088d6de](https://linux-hardware.org/?probe=105088d6de) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | [126b987221](https://linux-hardware.org/?probe=126b987221) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [5d59afae00](https://linux-hardware.org/?probe=5d59afae00) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [442de26b34](https://linux-hardware.org/?probe=442de26b34) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [9d7fc26276](https://linux-hardware.org/?probe=9d7fc26276) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [e07ab03ffb](https://linux-hardware.org/?probe=e07ab03ffb) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [b4b977309d](https://linux-hardware.org/?probe=b4b977309d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [bff39744bc](https://linux-hardware.org/?probe=bff39744bc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [01cd534e80](https://linux-hardware.org/?probe=01cd534e80) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [669e6289c0](https://linux-hardware.org/?probe=669e6289c0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [d49df4c170](https://linux-hardware.org/?probe=d49df4c170) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [01aa1a4299](https://linux-hardware.org/?probe=01aa1a4299) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [a85817bb6d](https://linux-hardware.org/?probe=a85817bb6d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [25955c9bb1](https://linux-hardware.org/?probe=25955c9bb1) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [0c81aeca67](https://linux-hardware.org/?probe=0c81aeca67) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [e72fe0a0a9](https://linux-hardware.org/?probe=e72fe0a0a9) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [33b61b457e](https://linux-hardware.org/?probe=33b61b457e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [d6c6259cc0](https://linux-hardware.org/?probe=d6c6259cc0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [f2444b315d](https://linux-hardware.org/?probe=f2444b315d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [aa745aba70](https://linux-hardware.org/?probe=aa745aba70) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [3b73c79a3c](https://linux-hardware.org/?probe=3b73c79a3c) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [d1a4cd1698](https://linux-hardware.org/?probe=d1a4cd1698) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [54713393ec](https://linux-hardware.org/?probe=54713393ec) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [56d2022832](https://linux-hardware.org/?probe=56d2022832) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [efbe0a9eca](https://linux-hardware.org/?probe=efbe0a9eca) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [60fbf7929d](https://linux-hardware.org/?probe=60fbf7929d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [e9a0bae6e6](https://linux-hardware.org/?probe=e9a0bae6e6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [4fb63d6dfe](https://linux-hardware.org/?probe=4fb63d6dfe) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [8ee5753b25](https://linux-hardware.org/?probe=8ee5753b25) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [6fb5a857e1](https://linux-hardware.org/?probe=6fb5a857e1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [613ea0ab6b](https://linux-hardware.org/?probe=613ea0ab6b) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [2aeec4566f](https://linux-hardware.org/?probe=2aeec4566f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [5751abaf6c](https://linux-hardware.org/?probe=5751abaf6c) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [31b40a1aa0](https://linux-hardware.org/?probe=31b40a1aa0) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [d3bbe595ba](https://linux-hardware.org/?probe=d3bbe595ba) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [24d5b7f6c6](https://linux-hardware.org/?probe=24d5b7f6c6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [f94dbbfc1f](https://linux-hardware.org/?probe=f94dbbfc1f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [960168908f](https://linux-hardware.org/?probe=960168908f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [71610e6e10](https://linux-hardware.org/?probe=71610e6e10) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [d2407bd778](https://linux-hardware.org/?probe=d2407bd778) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [88fc4d57ec](https://linux-hardware.org/?probe=88fc4d57ec) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [a1cbc192aa](https://linux-hardware.org/?probe=a1cbc192aa) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [66d94b1220](https://linux-hardware.org/?probe=66d94b1220) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [e8c2f02ba1](https://linux-hardware.org/?probe=e8c2f02ba1) | Apr 11, 2022 |
| Unknown       | Unknown                     | [7ef15ed6c9](https://linux-hardware.org/?probe=7ef15ed6c9) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [8bcad9c229](https://linux-hardware.org/?probe=8bcad9c229) | Apr 11, 2022 |
| ASRock        | FM2A55M-HD+                 | [a03ff53e01](https://linux-hardware.org/?probe=a03ff53e01) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [5486388fa0](https://linux-hardware.org/?probe=5486388fa0) | Apr 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [237634ce8d](https://linux-hardware.org/?probe=237634ce8d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [83b01e222e](https://linux-hardware.org/?probe=83b01e222e) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [c6f290816a](https://linux-hardware.org/?probe=c6f290816a) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [60c4fc315b](https://linux-hardware.org/?probe=60c4fc315b) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [faad64ac67](https://linux-hardware.org/?probe=faad64ac67) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f3fe662dcb](https://linux-hardware.org/?probe=f3fe662dcb) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [5293db1b11](https://linux-hardware.org/?probe=5293db1b11) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [7d3b364ff0](https://linux-hardware.org/?probe=7d3b364ff0) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [d8307a4138](https://linux-hardware.org/?probe=d8307a4138) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [bffde28b59](https://linux-hardware.org/?probe=bffde28b59) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [7d31dd74d7](https://linux-hardware.org/?probe=7d31dd74d7) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [7d03a291a2](https://linux-hardware.org/?probe=7d03a291a2) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [91f33b247d](https://linux-hardware.org/?probe=91f33b247d) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [2628069096](https://linux-hardware.org/?probe=2628069096) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [7c2a257e92](https://linux-hardware.org/?probe=7c2a257e92) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [868b030342](https://linux-hardware.org/?probe=868b030342) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [4088112a18](https://linux-hardware.org/?probe=4088112a18) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [68820282cb](https://linux-hardware.org/?probe=68820282cb) | Apr 11, 2022 |
| Unknown       | Unknown                     | [5a5a1a7ae6](https://linux-hardware.org/?probe=5a5a1a7ae6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [936252dfca](https://linux-hardware.org/?probe=936252dfca) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [67ed2ddd29](https://linux-hardware.org/?probe=67ed2ddd29) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [fde95ea3ed](https://linux-hardware.org/?probe=fde95ea3ed) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [de01821ecf](https://linux-hardware.org/?probe=de01821ecf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [67f41bf764](https://linux-hardware.org/?probe=67f41bf764) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [77aadf6511](https://linux-hardware.org/?probe=77aadf6511) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [cb9ae4e880](https://linux-hardware.org/?probe=cb9ae4e880) | Apr 11, 2022 |
| ASUSTek       | A68HM-K                     | [0199b0b388](https://linux-hardware.org/?probe=0199b0b388) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [d2a24f0327](https://linux-hardware.org/?probe=d2a24f0327) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [498dd8c409](https://linux-hardware.org/?probe=498dd8c409) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [fa2978c8db](https://linux-hardware.org/?probe=fa2978c8db) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [150ce1c4dd](https://linux-hardware.org/?probe=150ce1c4dd) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [76e9ddaa30](https://linux-hardware.org/?probe=76e9ddaa30) | Apr 11, 2022 |
| Unknown       | Unknown                     | [43c08af7bf](https://linux-hardware.org/?probe=43c08af7bf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [093a6488c3](https://linux-hardware.org/?probe=093a6488c3) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [730280aef1](https://linux-hardware.org/?probe=730280aef1) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [679df55359](https://linux-hardware.org/?probe=679df55359) | Apr 06, 2022 |
| Unknown       | S074VI5R8                   | [3fd567de05](https://linux-hardware.org/?probe=3fd567de05) | Apr 06, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [7e10ceda79](https://linux-hardware.org/?probe=7e10ceda79) | Apr 06, 2022 |
| ASRock        | M3N78D FX                   | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Unknown       | Unknown                     | [95628eab40](https://linux-hardware.org/?probe=95628eab40) | Mar 24, 2022 |
| ASRock        | A300M-STX                   | [1fb2262bcc](https://linux-hardware.org/?probe=1fb2262bcc) | Mar 17, 2022 |
| Gigabyte      | G41MT-D3                    | [92fc99440a](https://linux-hardware.org/?probe=92fc99440a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | [f7f470651e](https://linux-hardware.org/?probe=f7f470651e) | Feb 17, 2022 |
| Gigabyte      | X79-UD3                     | [452ebf6a67](https://linux-hardware.org/?probe=452ebf6a67) | Feb 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [921e224ec5](https://linux-hardware.org/?probe=921e224ec5) | Feb 12, 2022 |
| Aquarius      | AQH410T                     | [351b2e5344](https://linux-hardware.org/?probe=351b2e5344) | Jan 31, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [481e745592](https://linux-hardware.org/?probe=481e745592) | Jan 30, 2022 |
| ASRock        | B450 Gaming K4              | [8c31667834](https://linux-hardware.org/?probe=8c31667834) | Jan 20, 2022 |
| ASRock        | A520M-HDVP/DASH             | [edd6464f18](https://linux-hardware.org/?probe=edd6464f18) | Jan 19, 2022 |
| ASRock        | A520M-HDVP/DASH             | [93fef2e073](https://linux-hardware.org/?probe=93fef2e073) | Jan 19, 2022 |
| MSI           | A68HM-P33 V2                | [98e05db690](https://linux-hardware.org/?probe=98e05db690) | Jan 17, 2022 |
| ASRock        | B450 Gaming K4              | [0c802de596](https://linux-hardware.org/?probe=0c802de596) | Jan 14, 2022 |
| Gigabyte      | H77M-D3H                    | [c8ff16f0ed](https://linux-hardware.org/?probe=c8ff16f0ed) | Dec 24, 2021 |
| Supermicro    | X11SDW-14CNT-TP13F          | [4d8499f8ba](https://linux-hardware.org/?probe=4d8499f8ba) | Dec 23, 2021 |
| ASRock        | A320M-HDV R4.0              | [9180a824d8](https://linux-hardware.org/?probe=9180a824d8) | Dec 23, 2021 |
| ASRock        | B450 Gaming K4              | [7ef05a32a9](https://linux-hardware.org/?probe=7ef05a32a9) | Dec 17, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | [2aff2121af](https://linux-hardware.org/?probe=2aff2121af) | Dec 16, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | [30eab5f54f](https://linux-hardware.org/?probe=30eab5f54f) | Dec 15, 2021 |
| Gigabyte      | B550 GAMING X               | [c853f62ddd](https://linux-hardware.org/?probe=c853f62ddd) | Dec 06, 2021 |
| Unknown       | Unknown                     | [0f5c69902a](https://linux-hardware.org/?probe=0f5c69902a) | Dec 01, 2021 |
| ASRock        | B450M Pro4                  | [68a1f83b4f](https://linux-hardware.org/?probe=68a1f83b4f) | Nov 28, 2021 |
| Gigabyte      | B550 GAMING X               | [058d8a0404](https://linux-hardware.org/?probe=058d8a0404) | Nov 19, 2021 |
| ASUSTek       | P5Q                         | [70ee05a53e](https://linux-hardware.org/?probe=70ee05a53e) | Oct 28, 2021 |
| Gigabyte      | B450 AORUS M                | [d9dd1b763b](https://linux-hardware.org/?probe=d9dd1b763b) | Oct 08, 2021 |
| Dell          | 0U649C                      | [80e138d949](https://linux-hardware.org/?probe=80e138d949) | Sep 24, 2021 |
| ASRock        | X300M-STX                   | [da7d22c384](https://linux-hardware.org/?probe=da7d22c384) | Sep 16, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [132286ab64](https://linux-hardware.org/?probe=132286ab64) | Aug 17, 2021 |
| Gigabyte      | H77M-D3H                    | [85ce2f74c4](https://linux-hardware.org/?probe=85ce2f74c4) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [624e92e15e](https://linux-hardware.org/?probe=624e92e15e) | Aug 11, 2021 |
| Gigabyte      | H510M S2H                   | [db68dde16d](https://linux-hardware.org/?probe=db68dde16d) | Aug 04, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [b01641d467](https://linux-hardware.org/?probe=b01641d467) | Jul 25, 2021 |
| Gigabyte      | H110M-S2V-CF                | [8687a8809b](https://linux-hardware.org/?probe=8687a8809b) | Jul 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [05be9fcdec](https://linux-hardware.org/?probe=05be9fcdec) | Jul 03, 2021 |
| Gigabyte      | H110M-S2V-CF                | [24bd5ac93f](https://linux-hardware.org/?probe=24bd5ac93f) | Jun 27, 2021 |
| Kraftway      | KWH310                      | [f470a86a1c](https://linux-hardware.org/?probe=f470a86a1c) | Jun 26, 2021 |
| ASRock        | H110M-DGS R3.0              | [87ab7018c4](https://linux-hardware.org/?probe=87ab7018c4) | Jun 24, 2021 |
| MSI           | H110M PRO-VD                | [21a019dcb3](https://linux-hardware.org/?probe=21a019dcb3) | Jun 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [8325754280](https://linux-hardware.org/?probe=8325754280) | Jun 13, 2021 |
| MSI           | H110M PRO-VD                | [96cc5b470f](https://linux-hardware.org/?probe=96cc5b470f) | Jun 12, 2021 |
| MSI           | H110M PRO-VD                | [cfeb0493d3](https://linux-hardware.org/?probe=cfeb0493d3) | Jun 11, 2021 |
| ASRock        | J3455B-ITX                  | [13396a7347](https://linux-hardware.org/?probe=13396a7347) | May 19, 2021 |
| DEPO Compu... | DPH410S                     | [0d1000e904](https://linux-hardware.org/?probe=0d1000e904) | May 14, 2021 |
| DEPO Compu... | DPA320S G10g                | [5ecc011c34](https://linux-hardware.org/?probe=5ecc011c34) | May 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [97b70c1bac](https://linux-hardware.org/?probe=97b70c1bac) | Apr 17, 2021 |
| Acer          | H11H4-AI V:1.0              | [34997240d5](https://linux-hardware.org/?probe=34997240d5) | Mar 30, 2021 |
| ECS           | BAT-I2                      | [037e6e58e6](https://linux-hardware.org/?probe=037e6e58e6) | Mar 30, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [f0c7659cf9](https://linux-hardware.org/?probe=f0c7659cf9) | Mar 29, 2021 |
| Gigabyte      | P35-S3G                     | [8e53d68603](https://linux-hardware.org/?probe=8e53d68603) | Mar 20, 2021 |
| ASUSTek       | N3150M-E                    | [7467b59c82](https://linux-hardware.org/?probe=7467b59c82) | Mar 17, 2021 |
| ASUSTek       | PRIME B250-PRO              | [c62af0239b](https://linux-hardware.org/?probe=c62af0239b) | Mar 17, 2021 |
| iRU           | IRUB365M                    | [b7d5dda036](https://linux-hardware.org/?probe=b7d5dda036) | Mar 11, 2021 |
| Gigabyte      | GA-MA69VM-S2                | [6651c76da3](https://linux-hardware.org/?probe=6651c76da3) | Feb 07, 2021 |
| Gigabyte      | GA-MA69VM-S2                | [d63a1e9eef](https://linux-hardware.org/?probe=d63a1e9eef) | Feb 02, 2021 |
| ASUSTek       | P5B                         | [e0fc318a34](https://linux-hardware.org/?probe=e0fc318a34) | Jan 28, 2021 |
| EPoX Compu... | GeForce6100 + nForce410 ... | [99f734d52e](https://linux-hardware.org/?probe=99f734d52e) | Jan 18, 2021 |
| Gigabyte      | H110M-S2H-CF                | [38ae5dd532](https://linux-hardware.org/?probe=38ae5dd532) | Jan 14, 2021 |
| Intel         | B75                         | [34d29fb066](https://linux-hardware.org/?probe=34d29fb066) | Jan 12, 2021 |
| Gigabyte      | H110M-S2H-CF                | [2c49129777](https://linux-hardware.org/?probe=2c49129777) | Jan 09, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [31d84f6485](https://linux-hardware.org/?probe=31d84f6485) | Dec 31, 2020 |
| SYS           | H310SB                      | [ba93a151f2](https://linux-hardware.org/?probe=ba93a151f2) | Dec 24, 2020 |
| HP            | 877E A                      | [4456ec4081](https://linux-hardware.org/?probe=4456ec4081) | Dec 23, 2020 |
| HP            | 877E A                      | [145b54d631](https://linux-hardware.org/?probe=145b54d631) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | [c560d2aa9b](https://linux-hardware.org/?probe=c560d2aa9b) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | [8286c6ca5c](https://linux-hardware.org/?probe=8286c6ca5c) | Dec 23, 2020 |
| Foxconn       | 2ABF                        | [dbc40fef9d](https://linux-hardware.org/?probe=dbc40fef9d) | Dec 18, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [bb4bd8f82f](https://linux-hardware.org/?probe=bb4bd8f82f) | Dec 09, 2020 |
| ASRock        | X299 Steel Legend           | [fdfcfb17c6](https://linux-hardware.org/?probe=fdfcfb17c6) | Dec 03, 2020 |
| ASRock        | X299 Steel Legend           | [98800b881c](https://linux-hardware.org/?probe=98800b881c) | Dec 03, 2020 |
| Gigabyte      | H310N x.x                   | [b0ca19ee36](https://linux-hardware.org/?probe=b0ca19ee36) | Dec 02, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [4ec24e5c24](https://linux-hardware.org/?probe=4ec24e5c24) | Nov 27, 2020 |
| ASUSTek       | Z8NR-D12                    | [2758f1ff94](https://linux-hardware.org/?probe=2758f1ff94) | Nov 21, 2020 |
| iRU           | IRUB365M                    | [ab7e110c9a](https://linux-hardware.org/?probe=ab7e110c9a) | Nov 17, 2020 |
| iRU           | IRUB365M                    | [ed5fee32dd](https://linux-hardware.org/?probe=ed5fee32dd) | Nov 13, 2020 |
| Gigabyte      | H77M-D3H                    | [c878b046bc](https://linux-hardware.org/?probe=c878b046bc) | Nov 13, 2020 |
| Acer          | H11H4-AI V:1.0              | [5ad12e4b3b](https://linux-hardware.org/?probe=5ad12e4b3b) | Nov 12, 2020 |
| Gigabyte      | J1800N-D2H                  | [e25041fb04](https://linux-hardware.org/?probe=e25041fb04) | Nov 09, 2020 |
| ASUSTek       | A8N-E                       | [f716673893](https://linux-hardware.org/?probe=f716673893) | Oct 24, 2020 |
| ASUSTek       | P5B-MX                      | [0779d0f18c](https://linux-hardware.org/?probe=0779d0f18c) | Oct 24, 2020 |
| Acer          | Aspire XC-885 V:1.1         | [f587011ab7](https://linux-hardware.org/?probe=f587011ab7) | Sep 10, 2020 |
| ASRock        | G31M-VS                     | [fb4e557598](https://linux-hardware.org/?probe=fb4e557598) | Aug 16, 2020 |
| ASRock        | 4CoreN73PV-HD720p           | [ac70970005](https://linux-hardware.org/?probe=ac70970005) | Aug 16, 2020 |
| Gigabyte      | EP35C-DS3R                  | [4c98d77a2f](https://linux-hardware.org/?probe=4c98d77a2f) | Aug 07, 2020 |
| ASRock        | G31M-VS                     | [c4c8bad6ca](https://linux-hardware.org/?probe=c4c8bad6ca) | May 31, 2020 |
| Gigabyte      | A320M-S2H-CF                | [74899486ac](https://linux-hardware.org/?probe=74899486ac) | May 26, 2020 |
| ASUSTek       | PRIME B250-PRO              | [8dddac7046](https://linux-hardware.org/?probe=8dddac7046) | Mar 25, 2020 |
| Gigabyte      | H77M-D3H                    | [a644a3a3ad](https://linux-hardware.org/?probe=a644a3a3ad) | Nov 24, 2019 |
| HP            | 09F0h                       | [7f6c26af5d](https://linux-hardware.org/?probe=7f6c26af5d) | Oct 25, 2019 |
| MSI           | B350M PRO-VDH               | [525f09653e](https://linux-hardware.org/?probe=525f09653e) | Oct 08, 2019 |
| Gigabyte      | GA-890XA-UD3                | [1536999c3e](https://linux-hardware.org/?probe=1536999c3e) | Sep 13, 2019 |
| ASRock        | Z77 Pro3                    | [a1db2eb143](https://linux-hardware.org/?probe=a1db2eb143) | Sep 13, 2019 |
| ASRock        | B85M                        | [5a36ce2620](https://linux-hardware.org/?probe=5a36ce2620) | Sep 13, 2019 |
| ASUSTek       | Z97-A                       | [68dbf33470](https://linux-hardware.org/?probe=68dbf33470) | Aug 03, 2019 |
| ASUSTek       | A8N-VM CSM                  | [5814b6a2af](https://linux-hardware.org/?probe=5814b6a2af) | Mar 28, 2019 |
| ASUSTek       | H110M-R                     | [34b40d93fc](https://linux-hardware.org/?probe=34b40d93fc) | Oct 30, 2018 |
| ASRock        | FM2A68M-HD+                 | [d55532d7a9](https://linux-hardware.org/?probe=d55532d7a9) | Oct 29, 2018 |
| Biostar       | NF720D A2G+                 | [ef09cb18cc](https://linux-hardware.org/?probe=ef09cb18cc) | Oct 29, 2018 |
| ASUSTek       | H110M-R                     | [572c918e8a](https://linux-hardware.org/?probe=572c918e8a) | Oct 27, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Kometa P10         | 81       | 43.78%  |
| ALT Linux 9.1      | 33       | 17.84%  |
| ALT Linux 10.0     | 20       | 10.81%  |
| ALT Linux 9.0      | 15       | 8.11%   |
| ALT Linux 9.2      | 7        | 3.78%   |
| ALT Linux 10.1     | 5        | 2.7%    |
| MOS 10             | 4        | 2.16%   |
| ALT Linux P9       | 2        | 1.08%   |
| ALT Linux P8       | 2        | 1.08%   |
| ALT Linux P10      | 2        | 1.08%   |
| ALT Linux 8.4      | 2        | 1.08%   |
| ALT Linux 8.2      | 2        | 1.08%   |
| ALT Linux 7.0.5    | 2        | 1.08%   |
| ALT Linux 10.0.900 | 2        | 1.08%   |
| Kometa 1           | 1        | 0.54%   |
| ALT Linux 8.2.0    | 1        | 0.54%   |
| ALT Linux 20220110 | 1        | 0.54%   |
| ALT Linux 20201124 | 1        | 0.54%   |
| ALT Linux 20190303 | 1        | 0.54%   |
| ALT Linux 10.0.910 | 1        | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ALT Linux | 177      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.109-std-def-alt1       | 51       | 26.84%  |
| 5.10.102-std-def-alt1       | 27       | 14.21%  |
| 5.4.68-std-def-alt1.1       | 7        | 3.68%   |
| 5.10.82-std-def-alt1        | 6        | 3.16%   |
| 5.4.51-std-def-alt1         | 5        | 2.63%   |
| 5.15.34-un-def-alt1         | 5        | 2.63%   |
| 5.15.32-un-def-alt1         | 5        | 2.63%   |
| 5.4.41-std-def-alt1         | 3        | 1.58%   |
| 5.10.93-std-def-alt1        | 3        | 1.58%   |
| 5.10.35-un-def-alt1         | 3        | 1.58%   |
| 5.10.32-un-def-alt1         | 3        | 1.58%   |
| 4.19.79-std-def-alt1        | 3        | 1.58%   |
| 5.7.19-un-def-alt1          | 2        | 1.05%   |
| 5.4.85-std-def-alt1         | 2        | 1.05%   |
| 5.4.62-std-def-alt1         | 2        | 1.05%   |
| 5.4.28-std-def-alt1         | 2        | 1.05%   |
| 5.4.181-std-def-alt1        | 2        | 1.05%   |
| 5.4.127-std-def-alt1        | 2        | 1.05%   |
| 5.2.10-un-def-alt1          | 2        | 1.05%   |
| 5.15.15-un-def-alt1         | 2        | 1.05%   |
| 5.15.14-un-def-alt1         | 2        | 1.05%   |
| 5.10.88-std-def-alt1        | 2        | 1.05%   |
| 5.10.83-std-def-alt0.c9f.2  | 2        | 1.05%   |
| 5.10.72-std-def-alt1        | 2        | 1.05%   |
| 5.10.17-un-def-alt1         | 2        | 1.05%   |
| 5.9.8-un-def-alt1           | 1        | 0.53%   |
| 5.7.14-un-def-alt1          | 1        | 0.53%   |
| 5.4.94-std-def-alt1         | 1        | 0.53%   |
| 5.4.92-std-def-alt1         | 1        | 0.53%   |
| 5.4.91-elbrus-def-alt2.12.1 | 1        | 0.53%   |
| 5.4.81-std-def-alt1         | 1        | 0.53%   |
| 5.4.58-elbrus-def-alt1.7.0  | 1        | 0.53%   |
| 5.4.35-std-def-alt1         | 1        | 0.53%   |
| 5.4.134-std-def-alt1        | 1        | 0.53%   |
| 5.4.123-std-def-alt1        | 1        | 0.53%   |
| 5.4.104-std-def-alt1        | 1        | 0.53%   |
| 5.2.11-un-def-alt1          | 1        | 0.53%   |
| 5.18.16-un-def-alt1         | 1        | 0.53%   |
| 5.15.63-un-def-alt1         | 1        | 0.53%   |
| 5.15.53-un-def-alt1         | 1        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.109 | 51       | 26.84%  |
| 5.10.102 | 27       | 14.21%  |
| 5.4.68   | 7        | 3.68%   |
| 5.10.82  | 6        | 3.16%   |
| 5.4.51   | 5        | 2.63%   |
| 5.15.34  | 5        | 2.63%   |
| 5.15.32  | 5        | 2.63%   |
| 5.4.41   | 3        | 1.58%   |
| 5.10.93  | 3        | 1.58%   |
| 5.10.35  | 3        | 1.58%   |
| 5.10.32  | 3        | 1.58%   |
| 4.19.79  | 3        | 1.58%   |
| 5.7.19   | 2        | 1.05%   |
| 5.4.85   | 2        | 1.05%   |
| 5.4.62   | 2        | 1.05%   |
| 5.4.28   | 2        | 1.05%   |
| 5.4.181  | 2        | 1.05%   |
| 5.4.127  | 2        | 1.05%   |
| 5.2.10   | 2        | 1.05%   |
| 5.15.15  | 2        | 1.05%   |
| 5.15.14  | 2        | 1.05%   |
| 5.14.21  | 2        | 1.05%   |
| 5.10.88  | 2        | 1.05%   |
| 5.10.83  | 2        | 1.05%   |
| 5.10.72  | 2        | 1.05%   |
| 5.10.54  | 2        | 1.05%   |
| 5.10.17  | 2        | 1.05%   |
| 5.9.8    | 1        | 0.53%   |
| 5.7.14   | 1        | 0.53%   |
| 5.4.94   | 1        | 0.53%   |
| 5.4.92   | 1        | 0.53%   |
| 5.4.91   | 1        | 0.53%   |
| 5.4.81   | 1        | 0.53%   |
| 5.4.58   | 1        | 0.53%   |
| 5.4.35   | 1        | 0.53%   |
| 5.4.134  | 1        | 0.53%   |
| 5.4.123  | 1        | 0.53%   |
| 5.4.104  | 1        | 0.53%   |
| 5.2.11   | 1        | 0.53%   |
| 5.18.16  | 1        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 110      | 59.78%  |
| 5.4     | 34       | 18.48%  |
| 5.15    | 15       | 8.15%   |
| 4.19    | 7        | 3.8%    |
| 5.7     | 3        | 1.63%   |
| 5.2     | 3        | 1.63%   |
| 4.9     | 3        | 1.63%   |
| 5.14    | 2        | 1.09%   |
| 4.14    | 2        | 1.09%   |
| 5.9     | 1        | 0.54%   |
| 5.18    | 1        | 0.54%   |
| 5.13    | 1        | 0.54%   |
| 5.12    | 1        | 0.54%   |
| 4.20    | 1        | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 171      | 96.61%  |
| i686   | 4        | 2.26%   |
| e2k    | 2        | 1.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 128      | 71.51%  |
| Unknown  | 24       | 13.41%  |
| XFCE     | 22       | 12.29%  |
| MATE     | 2        | 1.12%   |
| KDE      | 2        | 1.12%   |
| Cinnamon | 1        | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 172      | 97.18%  |
| Unknown | 5        | 2.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 113      | 63.13%  |
| TDM     | 28       | 15.64%  |
| LightDM | 23       | 12.85%  |
| Unknown | 15       | 8.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 146      | 80.66%  |
| Unknown | 33       | 18.23%  |
| en_US   | 1        | 0.55%   |
| el_GR   | 1        | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 110      | 61.8%   |
| BIOS | 68       | 38.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 167      | 93.82%  |
| Overlay | 9        | 5.06%   |
| Btrfs   | 2        | 1.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 124      | 69.66%  |
| MBR     | 40       | 22.47%  |
| Unknown | 14       | 7.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 156      | 88.14%  |
| Yes       | 21       | 11.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 72.78%  |
| Yes       | 49       | 27.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 44       | 24.86%  |
| ASUSTek Computer    | 33       | 18.64%  |
| Gigabyte Technology | 26       | 14.69%  |
| ASRock              | 18       | 10.17%  |
| Acer                | 13       | 7.34%   |
| Unknown             | 9        | 5.08%   |
| MSI                 | 8        | 4.52%   |
| MAINBRD             | 3        | 1.69%   |
| iRU                 | 3        | 1.69%   |
| 3Logic Group        | 3        | 1.69%   |
| Hewlett-Packard     | 2        | 1.13%   |
| DEPO Computers      | 2        | 1.13%   |
| Dell                | 2        | 1.13%   |
| VIA Technologies    | 1        | 0.56%   |
| SYS                 | 1        | 0.56%   |
| Supermicro          | 1        | 0.56%   |
| OEM                 | 1        | 0.56%   |
| Lenovo              | 1        | 0.56%   |
| Kraftway            | 1        | 0.56%   |
| Foxconn             | 1        | 0.56%   |
| EPoX Computer       | 1        | 0.56%   |
| ECS                 | 1        | 0.56%   |
| Biostar             | 1        | 0.56%   |
| Aquarius            | 1        | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel SKYBAY                           | 43       | 24.29%  |
| ASUS PRIME B450-PLUS                   | 12       | 6.78%   |
| Acer Veriton X2640G                    | 10       | 5.65%   |
| Unknown                                | 9        | 5.08%   |
| Gigabyte H110M-S2H                     | 4        | 2.26%   |
| MAINBRD OPS62A-SHA                     | 3        | 1.69%   |
| 3Logic Group Graviton                  | 3        | 1.69%   |
| iRU 515                                | 2        | 1.13%   |
| Gigabyte H77M-D3H                      | 2        | 1.13%   |
| ASUS H110M-R                           | 2        | 1.13%   |
| Acer Veriton ES2710G                   | 2        | 1.13%   |
| VIA P4M266A-8235                       | 1        | 0.56%   |
| SYS RAY B101                           | 1        | 0.56%   |
| Supermicro SYS-1019D-14CN-FHN13TP      | 1        | 0.56%   |
| OEM ZXE CRB                            | 1        | 0.56%   |
| MSI MS-7D46                            | 1        | 0.56%   |
| MSI MS-7D18                            | 1        | 0.56%   |
| MSI MS-7A38                            | 1        | 0.56%   |
| MSI MS-7996                            | 1        | 0.56%   |
| MSI MS-7895                            | 1        | 0.56%   |
| MSI MS-7758                            | 1        | 0.56%   |
| MSI MS-7721                            | 1        | 0.56%   |
| MSI MPG B560 Trident A (MS-B926)       | 1        | 0.56%   |
| Lenovo ThinkCentre M73 10B1S15000      | 1        | 0.56%   |
| Kraftway KWH310                        | 1        | 0.56%   |
| iRU IRUB365M                           | 1        | 0.56%   |
| Intel B75                              | 1        | 0.56%   |
| HP Compaq dc7600 Convertible Minitower | 1        | 0.56%   |
| HP 290 G4 Microtower PC                | 1        | 0.56%   |
| Gigabyte Z77MX-D3H                     | 1        | 0.56%   |
| Gigabyte X79-UD3                       | 1        | 0.56%   |
| Gigabyte P35-S3G                       | 1        | 0.56%   |
| Gigabyte M57SLI-S4                     | 1        | 0.56%   |
| Gigabyte J1800N-D2H                    | 1        | 0.56%   |
| Gigabyte H510M S2H                     | 1        | 0.56%   |
| Gigabyte H310N 2.0                     | 1        | 0.56%   |
| Gigabyte H110M-S2V                     | 1        | 0.56%   |
| Gigabyte GA-MA69VM-S2                  | 1        | 0.56%   |
| Gigabyte GA-A75M-D2H                   | 1        | 0.56%   |
| Gigabyte GA-890XA-UD3                  | 1        | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel SKYBAY                      | 43       | 24.29%  |
| ASUS PRIME                        | 17       | 9.6%    |
| Acer Veriton                      | 12       | 6.78%   |
| Unknown                           | 9        | 5.08%   |
| Gigabyte H110M-S2H                | 4        | 2.26%   |
| MAINBRD OPS62A-SHA                | 3        | 1.69%   |
| 3Logic Group Graviton             | 3        | 1.69%   |
| iRU 515                           | 2        | 1.13%   |
| Gigabyte H77M-D3H                 | 2        | 1.13%   |
| Gigabyte B450                     | 2        | 1.13%   |
| Dell OptiPlex                     | 2        | 1.13%   |
| ASUS H110M-R                      | 2        | 1.13%   |
| VIA P4M266A-8235                  | 1        | 0.56%   |
| SYS RAY                           | 1        | 0.56%   |
| Supermicro SYS-1019D-14CN-FHN13TP | 1        | 0.56%   |
| OEM ZXE                           | 1        | 0.56%   |
| MSI MS-7D46                       | 1        | 0.56%   |
| MSI MS-7D18                       | 1        | 0.56%   |
| MSI MS-7A38                       | 1        | 0.56%   |
| MSI MS-7996                       | 1        | 0.56%   |
| MSI MS-7895                       | 1        | 0.56%   |
| MSI MS-7758                       | 1        | 0.56%   |
| MSI MS-7721                       | 1        | 0.56%   |
| MSI MPG                           | 1        | 0.56%   |
| Lenovo ThinkCentre                | 1        | 0.56%   |
| Kraftway KWH310                   | 1        | 0.56%   |
| iRU IRUB365M                      | 1        | 0.56%   |
| Intel B75                         | 1        | 0.56%   |
| HP Compaq                         | 1        | 0.56%   |
| HP 290                            | 1        | 0.56%   |
| Gigabyte Z77MX-D3H                | 1        | 0.56%   |
| Gigabyte X79-UD3                  | 1        | 0.56%   |
| Gigabyte P35-S3G                  | 1        | 0.56%   |
| Gigabyte M57SLI-S4                | 1        | 0.56%   |
| Gigabyte J1800N-D2H               | 1        | 0.56%   |
| Gigabyte H510M                    | 1        | 0.56%   |
| Gigabyte H310N                    | 1        | 0.56%   |
| Gigabyte H110M-S2V                | 1        | 0.56%   |
| Gigabyte GA-MA69VM-S2             | 1        | 0.56%   |
| Gigabyte GA-A75M-D2H              | 1        | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 43       | 24.29%  |
| 2017    | 33       | 18.64%  |
| 2016    | 20       | 11.3%   |
| 2020    | 12       | 6.78%   |
| 2021    | 9        | 5.08%   |
| 2012    | 9        | 5.08%   |
| 2022    | 7        | 3.95%   |
| 2015    | 6        | 3.39%   |
| 2008    | 5        | 2.82%   |
| 2019    | 4        | 2.26%   |
| 2014    | 4        | 2.26%   |
| 2011    | 4        | 2.26%   |
| 2009    | 4        | 2.26%   |
| 2010    | 3        | 1.69%   |
| 2007    | 3        | 1.69%   |
| 2006    | 3        | 1.69%   |
| 2005    | 3        | 1.69%   |
| 2013    | 2        | 1.13%   |
| Unknown | 2        | 1.13%   |
| 2003    | 1        | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 177      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 169      | 95.48%  |
| Enabled  | 8        | 4.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 177      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 78       | 44.07%  |
| 4.01-8.0    | 42       | 23.73%  |
| 3.01-4.0    | 27       | 15.25%  |
| 16.01-24.0  | 12       | 6.78%   |
| 1.01-2.0    | 5        | 2.82%   |
| 32.01-64.0  | 4        | 2.26%   |
| 2.01-3.0    | 3        | 1.69%   |
| 64.01-256.0 | 3        | 1.69%   |
| 0.51-1.0    | 2        | 1.13%   |
| 24.01-32.0  | 1        | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 93       | 50.54%  |
| 0.51-1.0  | 29       | 15.76%  |
| 2.01-3.0  | 27       | 14.67%  |
| 4.01-8.0  | 16       | 8.7%    |
| 3.01-4.0  | 13       | 7.07%   |
| 8.01-16.0 | 3        | 1.63%   |
| 0.01-0.5  | 3        | 1.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 124      | 68.89%  |
| 2      | 37       | 20.56%  |
| 3      | 13       | 7.22%   |
| 4      | 3        | 1.67%   |
| 5      | 2        | 1.11%   |
| 0      | 1        | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 63.84%  |
| Yes       | 64       | 36.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 176      | 99.44%  |
| No        | 1        | 0.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 145      | 81.92%  |
| Yes       | 32       | 18.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 154      | 86.52%  |
| Yes       | 24       | 13.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Russia     | 170      | 96.05%  |
| Ukraine    | 2        | 1.13%   |
| Greece     | 2        | 1.13%   |
| Kazakhstan | 1        | 0.56%   |
| China      | 1        | 0.56%   |
| Belarus    | 1        | 0.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Moscow                   | 117      | 64.29%  |
| St Petersburg            | 7        | 3.85%   |
| Samara                   | 5        | 2.75%   |
| Irkutsk                  | 3        | 1.65%   |
| Barnaul                  | 3        | 1.65%   |
| Yekaterinburg            | 2        | 1.1%    |
| Sevastopol               | 2        | 1.1%    |
| Saratov                  | 2        | 1.1%    |
| Perm                     | 2        | 1.1%    |
| Kaliningrad              | 2        | 1.1%    |
| Zelenodolsk              | 1        | 0.55%   |
| Vologda                  | 1        | 0.55%   |
| Vladivostok              | 1        | 0.55%   |
| Verkhnyaya Pyshma        | 1        | 0.55%   |
| Vergina                  | 1        | 0.55%   |
| Valuyki                  | 1        | 0.55%   |
| Tula                     | 1        | 0.55%   |
| Thessaloniki             | 1        | 0.55%   |
| Taraz                    | 1        | 0.55%   |
| Tambov                   | 1        | 0.55%   |
| Surgut                   | 1        | 0.55%   |
| Shenzhen                 | 1        | 0.55%   |
| Rostov-on-Don            | 1        | 0.55%   |
| Pushchino                | 1        | 0.55%   |
| Protvino                 | 1        | 0.55%   |
| Polyarnyy                | 1        | 0.55%   |
| Petropavlovsk-Kamchatsky | 1        | 0.55%   |
| Obninsk                  | 1        | 0.55%   |
| Nizhniy Novgorod         | 1        | 0.55%   |
| Murmansk                 | 1        | 0.55%   |
| Monchegorsk              | 1        | 0.55%   |
| Mogilev                  | 1        | 0.55%   |
| Lipetsk                  | 1        | 0.55%   |
| Kyzyl                    | 1        | 0.55%   |
| Krasnoyarsk              | 1        | 0.55%   |
| Krasnokamensk            | 1        | 0.55%   |
| Krasnogorsk              | 1        | 0.55%   |
| Krasnodar                | 1        | 0.55%   |
| Kostroma                 | 1        | 0.55%   |
| Korolyov                 | 1        | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 46       | 66     | 20.54%  |
| Seagate             | 30       | 46     | 13.39%  |
| Samsung Electronics | 27       | 32     | 12.05%  |
| AXIOMTEK            | 26       | 26     | 11.61%  |
| Toshiba             | 25       | 41     | 11.16%  |
| Kingston            | 17       | 19     | 7.59%   |
| China               | 8        | 8      | 3.57%   |
| Hitachi             | 6        | 7      | 2.68%   |
| A-DATA Technology   | 5        | 5      | 2.23%   |
| Apacer              | 4        | 6      | 1.79%   |
| SPCC                | 2        | 2      | 0.89%   |
| Smartbuy            | 2        | 2      | 0.89%   |
| Phison              | 2        | 2      | 0.89%   |
| Patriot             | 2        | 2      | 0.89%   |
| Intel               | 2        | 6      | 0.89%   |
| Gigabyte Technology | 2        | 2      | 0.89%   |
| DEPO                | 2        | 2      | 0.89%   |
| Crucial             | 2        | 2      | 0.89%   |
| XPG                 | 1        | 1      | 0.45%   |
| TMI                 | 1        | 1      | 0.45%   |
| SP-8                | 1        | 1      | 0.45%   |
| SINTECHI            | 1        | 1      | 0.45%   |
| SanDisk             | 1        | 1      | 0.45%   |
| Plextor             | 1        | 1      | 0.45%   |
| OCZ                 | 1        | 1      | 0.45%   |
| Micron Technology   | 1        | 1      | 0.45%   |
| LITEON              | 1        | 1      | 0.45%   |
| KingSpec            | 1        | 1      | 0.45%   |
| JMicron Technology  | 1        | 1      | 0.45%   |
| HEORIADY            | 1        | 1      | 0.45%   |
| Foxline             | 1        | 1      | 0.45%   |
| AMD                 | 1        | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD   | 26       | 10.88%  |
| Samsung MZVLW128HEGR-00000 128GB       | 17       | 7.11%   |
| Toshiba HDWD120 2TB                    | 13       | 5.44%   |
| WDC WD5000AZLX-21K2TA0 500GB           | 10       | 4.18%   |
| Toshiba HDWD110 1TB                    | 5        | 2.09%   |
| Kingston SV300S37A120G 120GB SSD       | 4        | 1.67%   |
| Kingston RBUSC180S37256GJ 256GB SSD    | 4        | 1.67%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 3        | 1.26%   |
| Samsung SSD 860 EVO 250GB              | 3        | 1.26%   |
| Kingston SA400S37120G 120GB SSD        | 3        | 1.26%   |
| WDC WD3200AAKS-00G3A0 320GB            | 2        | 0.84%   |
| WDC WD10PURZ-85U8XY0 1TB               | 2        | 0.84%   |
| Toshiba DT01ACA100 1TB                 | 2        | 0.84%   |
| Seagate ST500LM030-2E717D 500GB        | 2        | 0.84%   |
| Seagate ST500DM002-1BC142 500GB        | 2        | 0.84%   |
| Seagate ST380815AS 80GB                | 2        | 0.84%   |
| Seagate ST1000DM010-2EP102 1TB         | 2        | 0.84%   |
| Samsung SSD 860 EVO 500GB              | 2        | 0.84%   |
| Phison M.2 128GB SSO128GTLCG-SBC-2 SSD | 2        | 0.84%   |
| Kingston SA400S37240G 240GB SSD        | 2        | 0.84%   |
| Hitachi HDS723020BLA642 2TB            | 2        | 0.84%   |
| Hitachi HDS721025CLA382 165GB          | 2        | 0.84%   |
| DEPO SM3DT-120 120GB SSD               | 2        | 0.84%   |
| China SSD 128GB                        | 2        | 0.84%   |
| Apacer AS350 256GB SSD                 | 2        | 0.84%   |
| XPG GAMMIX S5 512GB                    | 1        | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1        | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1        | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1        | 0.42%   |
| WDC WD800AAJS-00WAA0 80GB              | 1        | 0.42%   |
| WDC WD7501AALS-00E3A0 752GB            | 1        | 0.42%   |
| WDC WD60EZRZ-22GZ5B1 6TB               | 1        | 0.42%   |
| WDC WD5003ABYZ-011FA0 500GB            | 1        | 0.42%   |
| WDC WD5001ABYS-01YNA0 500GB            | 1        | 0.42%   |
| WDC WD5001AALS-00E3A0 500GB            | 1        | 0.42%   |
| WDC WD5000HHTZ-04N21V0 500GB           | 1        | 0.42%   |
| WDC WD5000AZRZ-00HTKB0 500GB           | 1        | 0.42%   |
| WDC WD5000AZLX-00JKKA0 500GB           | 1        | 0.42%   |
| WDC WD3200BPVT-00HXZT3 320GB           | 1        | 0.42%   |
| WDC WD3200BEVT-80A0RT0 320GB           | 1        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 40       | 59     | 39.6%   |
| Seagate             | 28       | 41     | 27.72%  |
| Toshiba             | 25       | 40     | 24.75%  |
| Hitachi             | 6        | 7      | 5.94%   |
| SINTECHI            | 1        | 1      | 0.99%   |
| Samsung Electronics | 1        | 1      | 0.99%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| AXIOMTEK            | 26       | 26     | 27.37%  |
| Kingston            | 16       | 17     | 16.84%  |
| China               | 8        | 8      | 8.42%   |
| Samsung Electronics | 7        | 9      | 7.37%   |
| WDC                 | 6        | 6      | 6.32%   |
| Apacer              | 4        | 6      | 4.21%   |
| A-DATA Technology   | 4        | 4      | 4.21%   |
| Smartbuy            | 2        | 2      | 2.11%   |
| Seagate             | 2        | 5      | 2.11%   |
| Phison              | 2        | 2      | 2.11%   |
| Patriot             | 2        | 2      | 2.11%   |
| DEPO                | 2        | 2      | 2.11%   |
| Crucial             | 2        | 2      | 2.11%   |
| TMI                 | 1        | 1      | 1.05%   |
| SP-8                | 1        | 1      | 1.05%   |
| SanDisk             | 1        | 1      | 1.05%   |
| Plextor             | 1        | 1      | 1.05%   |
| OCZ                 | 1        | 1      | 1.05%   |
| LITEON              | 1        | 1      | 1.05%   |
| KingSpec            | 1        | 1      | 1.05%   |
| Intel               | 1        | 4      | 1.05%   |
| HEORIADY            | 1        | 1      | 1.05%   |
| Gigabyte Technology | 1        | 1      | 1.05%   |
| Foxline             | 1        | 1      | 1.05%   |
| AMD                 | 1        | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 90       | 106    | 42.86%  |
| HDD  | 89       | 149    | 42.38%  |
| NVMe | 31       | 35     | 14.76%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 153      | 254    | 82.7%   |
| NVMe | 30       | 34     | 16.22%  |
| SAS  | 2        | 2      | 1.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 123      | 157    | 66.85%  |
| 0.51-1.0   | 32       | 48     | 17.39%  |
| 1.01-2.0   | 25       | 45     | 13.59%  |
| 2.01-3.0   | 3        | 4      | 1.63%   |
| 4.01-10.0  | 1        | 1      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 87       | 48.33%  |
| 251-500        | 28       | 15.56%  |
| 1001-2000      | 23       | 12.78%  |
| 501-1000       | 11       | 6.11%   |
| 21-50          | 8        | 4.44%   |
| More than 3000 | 7        | 3.89%   |
| 51-100         | 7        | 3.89%   |
| 1-20           | 5        | 2.78%   |
| 2001-3000      | 3        | 1.67%   |
| Unknown        | 1        | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 108      | 59.02%  |
| 21-50          | 24       | 13.11%  |
| 101-250        | 15       | 8.2%    |
| 51-100         | 14       | 7.65%   |
| 501-1000       | 8        | 4.37%   |
| 251-500        | 5        | 2.73%   |
| More than 3000 | 3        | 1.64%   |
| 1001-2000      | 3        | 1.64%   |
| 2001-3000      | 2        | 1.09%   |
| Unknown        | 1        | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD7501AALS-00E3A0 752GB           | 1        | 1      | 5.56%   |
| WDC WD3200AAKS-00V1A0 320GB           | 1        | 1      | 5.56%   |
| WDC WD2500KS-00MJB0 250GB             | 1        | 1      | 5.56%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1        | 3      | 5.56%   |
| WDC WD20EARX-008FB0 2TB               | 1        | 1      | 5.56%   |
| Seagate ST9250315AS 250GB             | 1        | 1      | 5.56%   |
| Seagate ST380815AS 80GB               | 1        | 1      | 5.56%   |
| Seagate ST380811AS 80GB               | 1        | 1      | 5.56%   |
| Seagate ST3320418AS 320GB             | 1        | 1      | 5.56%   |
| Seagate ST3000DM001-1CH166 3TB        | 1        | 1      | 5.56%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 2      | 5.56%   |
| Seagate ST1000DL004 HD105SI 1TB       | 1        | 1      | 5.56%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 5.56%   |
| Hitachi HUA722010CLA330 1TB           | 1        | 1      | 5.56%   |
| Hitachi HTS545050KTA300 500GB         | 1        | 2      | 5.56%   |
| Hitachi HDS723020BLA642 2TB           | 1        | 1      | 5.56%   |
| Hitachi HDS721025CLA382 165GB         | 1        | 1      | 5.56%   |
| DEPO SM3DT-120 120GB SSD              | 1        | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 8      | 38.89%  |
| WDC                 | 5        | 7      | 27.78%  |
| Hitachi             | 4        | 5      | 22.22%  |
| Samsung Electronics | 1        | 1      | 5.56%   |
| DEPO                | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 7        | 8      | 43.75%  |
| WDC     | 5        | 7      | 31.25%  |
| Hitachi | 4        | 5      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 20     | 88.24%  |
| SSD  | 2        | 2      | 11.76%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5001AALS-00E3A0 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 150      | 223    | 78.13%  |
| Detected | 24       | 44     | 12.5%   |
| Malfunc  | 17       | 22     | 8.85%   |
| Failed   | 1        | 1      | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 127      | 58.53%  |
| AMD                          | 38       | 17.51%  |
| Samsung Electronics          | 19       | 8.76%   |
| Nvidia                       | 8        | 3.69%   |
| JMicron Technology           | 5        | 2.3%    |
| ASMedia Technology           | 3        | 1.38%   |
| Realtek Semiconductor        | 2        | 0.92%   |
| Phison Electronics           | 2        | 0.92%   |
| MCST                         | 2        | 0.92%   |
| Marvell Technology Group     | 2        | 0.92%   |
| Kingston Technology Company  | 2        | 0.92%   |
| Zhaoxin                      | 1        | 0.46%   |
| VIA Technologies             | 1        | 0.46%   |
| Toshiba America Info Systems | 1        | 0.46%   |
| Silicon Motion               | 1        | 0.46%   |
| SanDisk                      | 1        | 0.46%   |
| Micron Technology            | 1        | 0.46%   |
| LSI Logic / Symbios Logic    | 1        | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 64       | 24.24%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 30       | 11.36%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 17       | 6.44%   |
| AMD 400 Series Chipset SATA Controller                                         | 17       | 6.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9        | 3.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6        | 2.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6        | 2.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 1.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5        | 1.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4        | 1.52%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 1.52%   |
| AMD FCH SATA Controller D                                                      | 4        | 1.52%   |
| JMicron JMB363 SATA/IDE Controller                                             | 3        | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3        | 1.14%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 3        | 1.14%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 3        | 1.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3        | 1.14%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 1.14%   |
| Realtek Realtek Non-Volatile memory controller                                 | 2        | 0.76%   |
| Phison PS5013 E13 NVMe Controller                                              | 2        | 0.76%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2        | 0.76%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2        | 0.76%   |
| Nvidia MCP51 Serial ATA Controller                                             | 2        | 0.76%   |
| Nvidia MCP51 IDE                                                               | 2        | 0.76%   |
| MCST SATA                                                                      | 2        | 0.76%   |
| MCST IDE controller                                                            | 2        | 0.76%   |
| JMicron JMB368 IDE controller                                                  | 2        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 0.76%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2        | 0.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 2        | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 2        | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 0.76%   |
| Zhaoxin ZX-100/ZX-200/ZX-E StorX AHCI Controller                               | 1        | 0.38%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 0.38%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1        | 0.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 154      | 70.97%  |
| IDE  | 31       | 14.29%  |
| NVMe | 30       | 13.82%  |
| RAID | 2        | 0.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 129      | 72.88%  |
| AMD          | 45       | 25.42%  |
| E8C/EATX     | 1        | 0.56%   |
| E8C-SWTX     | 1        | 0.56%   |
| CentaurHauls | 1        | 0.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-6100TE CPU @ 2.70GHz          | 43       | 24.02%  |
| AMD Ryzen 5 1600 Six-Core Processor         | 13       | 7.26%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 10       | 5.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4        | 2.23%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 2.23%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3        | 1.68%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 3        | 1.68%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 3        | 1.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3        | 1.68%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 2        | 1.12%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 1.12%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 2        | 1.12%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 1.12%   |
| Intel Genuine CPU 0000 @ 2.40GHz            | 2        | 1.12%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.12%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.12%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.12%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.12%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 1.12%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.12%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.12%   |
| AMD Athlon 64 X2 Dual Core Processor 4800+  | 2        | 1.12%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.12%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 2        | 1.12%   |
| Intel Xeon D-2177NT CPU @ 1.90GHz           | 1        | 0.56%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.56%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.56%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.56%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.56%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.56%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.56%   |
| Intel Pentium CPU G4500 @ 3.50GHz           | 1        | 0.56%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.56%   |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1        | 0.56%   |
| Intel Core i9-10980XE CPU @ 3.00GHz         | 1        | 0.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.56%   |
| Intel Core i7-4960X CPU @ 3.60GHz           | 1        | 0.56%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.56%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 58       | 32.58%  |
| AMD Ryzen 5             | 18       | 10.11%  |
| Intel Core i5           | 17       | 9.55%   |
| Intel Pentium           | 13       | 7.3%    |
| Intel Celeron           | 10       | 5.62%   |
| Other                   | 9        | 5.06%   |
| Intel Pentium Dual-Core | 5        | 2.81%   |
| Intel Core 2 Duo        | 4        | 2.25%   |
| AMD Ryzen 7             | 4        | 2.25%   |
| AMD Athlon 64 X2        | 4        | 2.25%   |
| Intel Xeon              | 3        | 1.69%   |
| Intel Pentium Gold      | 3        | 1.69%   |
| AMD A8                  | 3        | 1.69%   |
| AMD A10                 | 3        | 1.69%   |
| Intel Genuine           | 2        | 1.12%   |
| Intel Core i9           | 2        | 1.12%   |
| Intel Core i7           | 2        | 1.12%   |
| Intel Core 2 Quad       | 2        | 1.12%   |
| AMD Ryzen 3             | 2        | 1.12%   |
| AMD Phenom II X4        | 2        | 1.12%   |
| AMD FX                  | 2        | 1.12%   |
| AMD Athlon              | 2        | 1.12%   |
| Intel Pentium D         | 1        | 0.56%   |
| Intel Pentium 4         | 1        | 0.56%   |
| AMD Sempron             | 1        | 0.56%   |
| AMD Ryzen 7 PRO         | 1        | 0.56%   |
| AMD Ryzen 5 PRO         | 1        | 0.56%   |
| AMD Athlon II X4        | 1        | 0.56%   |
| AMD Athlon 64           | 1        | 0.56%   |
| AMD A6                  | 1        | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 96       | 53.93%  |
| 4      | 40       | 22.47%  |
| 6      | 23       | 12.92%  |
| 8      | 9        | 5.06%   |
| 1      | 4        | 2.25%   |
| 3      | 2        | 1.12%   |
| 32     | 1        | 0.56%   |
| 18     | 1        | 0.56%   |
| 16     | 1        | 0.56%   |
| 14     | 1        | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 174      | 98.31%  |
| 2      | 2        | 1.13%   |
| 4      | 1        | 0.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 120      | 67.8%   |
| 1      | 57       | 32.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 174      | 98.31%  |
| Unknown        | 2        | 1.13%   |
| 32-bit         | 1        | 0.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 49       | 27.37%  |
| Unknown    | 29       | 16.2%   |
| 0x906e9    | 13       | 7.26%   |
| 0x08001138 | 13       | 7.26%   |
| 0x1067a    | 9        | 5.03%   |
| 0xa0653    | 6        | 3.35%   |
| 0x906eb    | 5        | 2.79%   |
| 0x08108109 | 5        | 2.79%   |
| 0x906ea    | 4        | 2.23%   |
| 0x306a9    | 4        | 2.23%   |
| 0xa0671    | 3        | 1.68%   |
| 0x806e9    | 3        | 1.68%   |
| 0x806c1    | 3        | 1.68%   |
| 0x06001119 | 3        | 1.68%   |
| 0x906ed    | 2        | 1.12%   |
| 0x30679    | 2        | 1.12%   |
| 0x206a7    | 2        | 1.12%   |
| 0x08701021 | 2        | 1.12%   |
| 0x010000db | 2        | 1.12%   |
| 0xf47      | 1        | 0.56%   |
| 0xf29      | 1        | 0.56%   |
| 0x806ec    | 1        | 0.56%   |
| 0x6fb      | 1        | 0.56%   |
| 0x506e8    | 1        | 0.56%   |
| 0x506c9    | 1        | 0.56%   |
| 0x50657    | 1        | 0.56%   |
| 0x50654    | 1        | 0.56%   |
| 0x306e4    | 1        | 0.56%   |
| 0x306c3    | 1        | 0.56%   |
| 0x206c2    | 1        | 0.56%   |
| 0x10661    | 1        | 0.56%   |
| 0x0a50000c | 1        | 0.56%   |
| 0x08108102 | 1        | 0.56%   |
| 0x0810100b | 1        | 0.56%   |
| 0x0800820d | 1        | 0.56%   |
| 0x08001129 | 1        | 0.56%   |
| 0x06000852 | 1        | 0.56%   |
| 0x010000c8 | 1        | 0.56%   |
| 0x00000000 | 1        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Skylake     | 54       | 30.51%  |
| KabyLake    | 30       | 16.95%  |
| Zen         | 15       | 8.47%   |
| Penryn      | 10       | 5.65%   |
| Zen+        | 8        | 4.52%   |
| CometLake   | 7        | 3.95%   |
| Unknown     | 7        | 3.95%   |
| Piledriver  | 6        | 3.39%   |
| K8 Hammer   | 6        | 3.39%   |
| IvyBridge   | 6        | 3.39%   |
| SandyBridge | 4        | 2.26%   |
| Zen 2       | 3        | 1.69%   |
| TigerLake   | 3        | 1.69%   |
| Silvermont  | 3        | 1.69%   |
| K10         | 3        | 1.69%   |
| Steamroller | 2        | 1.13%   |
| NetBurst    | 2        | 1.13%   |
| Haswell     | 2        | 1.13%   |
| Core        | 2        | 1.13%   |
| Zen 3       | 1        | 0.56%   |
| Westmere    | 1        | 0.56%   |
| K10 Llano   | 1        | 0.56%   |
| Goldmont    | 1        | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 104      | 57.14%  |
| Nvidia            | 49       | 26.92%  |
| AMD               | 24       | 13.19%  |
| Silicon Motion    | 2        | 1.1%    |
| ASPEED Technology | 2        | 1.1%    |
| Zhaoxin           | 1        | 0.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                     | 46       | 24.73%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 17       | 9.14%   |
| Intel HD Graphics 610                                                     | 10       | 5.38%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 9        | 4.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 7        | 3.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 6        | 3.23%   |
| Intel HD Graphics 510                                                     | 5        | 2.69%   |
| Intel HD Graphics 620                                                     | 4        | 2.15%   |
| Nvidia GK208B [GeForce GT 710]                                            | 3        | 1.61%   |
| Nvidia GF108 [GeForce GT 630]                                             | 3        | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3        | 1.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3        | 1.61%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                         | 3        | 1.61%   |
| Silicon Motion SM718 LynxSE+                                              | 2        | 1.08%   |
| Nvidia GF119 [GeForce GT 610]                                             | 2        | 1.08%   |
| Intel HD Graphics 630                                                     | 2        | 1.08%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                 | 2        | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2        | 1.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 2        | 1.08%   |
| ASPEED Technology ASPEED Graphics Family                                  | 2        | 1.08%   |
| AMD Kaveri [Radeon R7 Graphics]                                           | 2        | 1.08%   |
| Zhaoxin ZX-E C-960 GPU                                                    | 1        | 0.54%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1        | 0.54%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                     | 1        | 0.54%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                      | 1        | 0.54%   |
| Nvidia GT218 [GeForce 210]                                                | 1        | 0.54%   |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1        | 0.54%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1        | 0.54%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                       | 1        | 0.54%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                        | 1        | 0.54%   |
| Nvidia GM204 [GeForce GTX 980]                                            | 1        | 0.54%   |
| Nvidia GM107 [GeForce GTX 750]                                            | 1        | 0.54%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 0.54%   |
| Nvidia GK106 [GeForce GTX 660]                                            | 1        | 0.54%   |
| Nvidia GK106 [GeForce GTX 650 Ti Boost]                                   | 1        | 0.54%   |
| Nvidia GF119 [GeForce GT 520]                                             | 1        | 0.54%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                     | 1        | 0.54%   |
| Nvidia GF106 [GeForce GTS 450]                                            | 1        | 0.54%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                            | 1        | 0.54%   |
| Nvidia G94 [GeForce 9600 GT]                                              | 1        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 101      | 57.06%  |
| 1 x Nvidia         | 47       | 26.55%  |
| 1 x AMD            | 20       | 11.3%   |
| 2 x AMD            | 3        | 1.69%   |
| 1 x Silicon Motion | 2        | 1.13%   |
| 1 x ASPEED         | 2        | 1.13%   |
| Nvidia + Zhaoxin   | 1        | 0.56%   |
| Intel + Nvidia     | 1        | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 136      | 76.4%   |
| Proprietary | 37       | 20.79%  |
| Unknown     | 5        | 2.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 114      | 64.04%  |
| 3.01-4.0   | 21       | 11.8%   |
| 1.01-2.0   | 13       | 7.3%    |
| 0.51-1.0   | 13       | 7.3%    |
| 0.01-0.5   | 13       | 7.3%    |
| 7.01-8.0   | 1        | 0.56%   |
| 5.01-6.0   | 1        | 0.56%   |
| 2.01-3.0   | 1        | 0.56%   |
| 8.01-16.0  | 1        | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| HHT                  | 43       | 23.89%  |
| Acer                 | 23       | 12.78%  |
| BenQ                 | 20       | 11.11%  |
| AOC                  | 19       | 10.56%  |
| Samsung Electronics  | 18       | 10%     |
| Goldstar             | 9        | 5%      |
| ViewSonic            | 8        | 4.44%   |
| Dell                 | 6        | 3.33%   |
| Philips              | 5        | 2.78%   |
| PRW                  | 4        | 2.22%   |
| Ancor Communications | 4        | 2.22%   |
| WBT                  | 3        | 1.67%   |
| LG Electronics       | 3        | 1.67%   |
| STD                  | 2        | 1.11%   |
| Hewlett-Packard      | 2        | 1.11%   |
| VIE                  | 1        | 0.56%   |
| Toshiba              | 1        | 0.56%   |
| SKG                  | 1        | 0.56%   |
| Lenovo               | 1        | 0.56%   |
| JRY                  | 1        | 0.56%   |
| HIB                  | 1        | 0.56%   |
| HannStar             | 1        | 0.56%   |
| DZW                  | 1        | 0.56%   |
| ASUSTek Computer     | 1        | 0.56%   |
| Apple                | 1        | 0.56%   |
| Unknown              | 1        | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HHT ActviPanel V5 HHT0030 3840x2160 944x398mm 40.3-inch               | 43       | 23.12%  |
| AOC LCD Monitor 2778X 2560x1440                                       | 11       | 5.91%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                     | 10       | 5.38%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 7        | 3.76%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 5        | 2.69%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch         | 4        | 2.15%   |
| PRW AP7_Titanium PRW4200 3840x2160                                    | 4        | 2.15%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                      | 3        | 1.61%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2        | 1.08%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                         | 2        | 1.08%   |
| Samsung Electronics S22E391 SAM0C0E 1920x1080 477x268mm 21.5-inch     | 2        | 1.08%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                | 2        | 1.08%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2        | 1.08%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 2        | 1.08%   |
| AOC G2490W1G4 AOC2490 1920x1080 527x296mm 23.8-inch                   | 2        | 1.08%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                       | 2        | 1.08%   |
| ViewSonic VA1916w-6 VSCF91F 1440x900 410x256mm 19.0-inch              | 1        | 0.54%   |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch           | 1        | 0.54%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 0.54%   |
| Toshiba LCD Monitor TV 1920x1080                                      | 1        | 0.54%   |
| SKG 86 Monitor SKG8600 3840x2160 1650x928mm 74.5-inch                 | 1        | 0.54%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1        | 0.54%   |
| Samsung Electronics SMS22A450 SAM0836 1680x1050 459x296mm 21.5-inch   | 1        | 0.54%   |
| Samsung Electronics S27E370D SAM0CF3 1920x1080 598x336mm 27.0-inch    | 1        | 0.54%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 520x290mm 23.4-inch     | 1        | 0.54%   |
| Samsung Electronics S24B370 SAM08DE 1920x1080 531x299mm 24.0-inch     | 1        | 0.54%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1        | 0.54%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 0.54%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1        | 0.54%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 1        | 0.54%   |
| Samsung Electronics EPSON PJ SECA60D 1920x1080                        | 1        | 0.54%   |
| Samsung Electronics C27JG5x SAM0F58 2560x1440 597x336mm 27.0-inch     | 1        | 0.54%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1        | 0.54%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch               | 1        | 0.54%   |
| Philips PHI32PFL3605 PHLD06B 1680x1050 699x393mm 31.6-inch            | 1        | 0.54%   |
| Philips PHI32PFL3404 PHLD067 1360x768 700x390mm 31.5-inch             | 1        | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 71       | 39.89%  |
| 3840x2160 (4K)     | 53       | 29.78%  |
| 2560x1440 (QHD)    | 23       | 12.92%  |
| 1280x1024 (SXGA)   | 14       | 7.87%   |
| 1680x1050 (WSXGA+) | 4        | 2.25%   |
| 1600x900 (HD+)     | 3        | 1.69%   |
| 1440x900 (WXGA+)   | 3        | 1.69%   |
| 1366x768 (WXGA)    | 2        | 1.12%   |
| Unknown            | 2        | 1.12%   |
| 4480x1440          | 1        | 0.56%   |
| 1920x1200 (WUXGA)  | 1        | 0.56%   |
| 1360x768           | 1        | 0.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 40      | 43       | 24.16%  |
| 24      | 30       | 16.85%  |
| Unknown | 25       | 14.04%  |
| 23      | 20       | 11.24%  |
| 21      | 17       | 9.55%   |
| 19      | 10       | 5.62%   |
| 27      | 8        | 4.49%   |
| 17      | 7        | 3.93%   |
| 31      | 5        | 2.81%   |
| 26      | 3        | 1.69%   |
| 22      | 2        | 1.12%   |
| 74      | 1        | 0.56%   |
| 72      | 1        | 0.56%   |
| 46      | 1        | 0.56%   |
| 33      | 1        | 0.56%   |
| 32      | 1        | 0.56%   |
| 28      | 1        | 0.56%   |
| 20      | 1        | 0.56%   |
| 18      | 1        | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 59       | 33.71%  |
| 901-1000    | 43       | 24.57%  |
| Unknown     | 25       | 14.29%  |
| 401-500     | 24       | 13.71%  |
| 601-700     | 7        | 4%      |
| 301-350     | 7        | 4%      |
| 351-400     | 5        | 2.86%   |
| 701-800     | 2        | 1.14%   |
| 1501-2000   | 2        | 1.14%   |
| 1001-1500   | 1        | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 86       | 50.29%  |
| 21/9    | 43       | 25.15%  |
| Unknown | 21       | 12.28%  |
| 5/4     | 12       | 7.02%   |
| 16/10   | 8        | 4.68%   |
| 3/2     | 1        | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 61       | 34.86%  |
| 501-1000       | 44       | 25.14%  |
| Unknown        | 25       | 14.29%  |
| 151-200        | 14       | 8%      |
| 301-350        | 11       | 6.29%   |
| 351-500        | 8        | 4.57%   |
| 141-150        | 8        | 4.57%   |
| More than 1000 | 2        | 1.14%   |
| 251-300        | 2        | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 72       | 40.91%  |
| 101-120 | 63       | 35.8%   |
| Unknown | 25       | 14.2%   |
| 121-160 | 12       | 6.82%   |
| 1-50    | 4        | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 156      | 87.15%  |
| 2     | 13       | 7.26%   |
| 0     | 9        | 5.03%   |
| 3     | 1        | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 145      | 58%     |
| Intel                      | 68       | 27.2%   |
| Qualcomm Atheros           | 12       | 4.8%    |
| Nvidia                     | 7        | 2.8%    |
| Microchip Technology       | 3        | 1.2%    |
| TP-Link                    | 2        | 0.8%    |
| Ralink Technology          | 2        | 0.8%    |
| Ralink                     | 2        | 0.8%    |
| MCST                       | 2        | 0.8%    |
| ZTE WCDMA Technologies MSM | 1        | 0.4%    |
| Xiaomi                     | 1        | 0.4%    |
| Vimtron Electronics        | 1        | 0.4%    |
| VIA Technologies           | 1        | 0.4%    |
| U-Blox                     | 1        | 0.4%    |
| D-Link                     | 1        | 0.4%    |
| Broadcom Limited           | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 87       | 31.87%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 43       | 15.75%  |
| Intel Ethernet Connection I219-LM                                 | 31       | 11.36%  |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 6.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.2%    |
| Intel Wireless 3165                                               | 6        | 2.2%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3        | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.1%    |
| Microchip MCP2221 USB-I2C/UART Combo                              | 3        | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.1%    |
| Intel Ethernet Connection (14) I219-V                             | 3        | 1.1%    |
| Intel Ethernet Connection (13) I219-V                             | 3        | 1.1%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2        | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 0.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.73%   |
| Realtek 802.11ac NIC                                              | 2        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.73%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.73%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.73%   |
| Intel Wireless-AC 9260                                            | 2        | 0.73%   |
| Intel I211 Gigabit Network Connection                             | 2        | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2        | 0.73%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1        | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.37%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.37%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.37%   |
| U-Blox [u-blox 7]                                                 | 1        | 0.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.37%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.37%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.37%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.37%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 0.37%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1        | 0.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 37.5%   |
| Realtek Semiconductor | 11       | 34.38%  |
| Qualcomm Atheros      | 3        | 9.38%   |
| TP-Link               | 2        | 6.25%   |
| Ralink Technology     | 2        | 6.25%   |
| Ralink                | 2        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                        | 6        | 18.75%  |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 3        | 9.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 3        | 9.38%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 2        | 6.25%   |
| Realtek 802.11ac NIC                                       | 2        | 6.25%   |
| Intel Wireless-AC 9260                                     | 2        | 6.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 2        | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 3.13%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1        | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 3.13%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 3.13%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 3.13%   |
| Ralink RT5392 PCIe Wireless Network Adapter                | 1        | 3.13%   |
| Ralink RT2561/RT61 rev B 802.11g                           | 1        | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 3.13%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 3.13%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 143      | 61.64%  |
| Intel                      | 65       | 28.02%  |
| Qualcomm Atheros           | 9        | 3.88%   |
| Nvidia                     | 7        | 3.02%   |
| MCST                       | 2        | 0.86%   |
| ZTE WCDMA Technologies MSM | 1        | 0.43%   |
| Xiaomi                     | 1        | 0.43%   |
| Vimtron Electronics        | 1        | 0.43%   |
| VIA Technologies           | 1        | 0.43%   |
| D-Link                     | 1        | 0.43%   |
| Broadcom Limited           | 1        | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 87       | 36.71%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 43       | 18.14%  |
| Intel Ethernet Connection I219-LM                                 | 31       | 13.08%  |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 7.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.27%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 1.27%   |
| Intel Ethernet Connection (13) I219-V                             | 3        | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 0.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.84%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.84%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 2        | 0.84%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.42%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.42%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.42%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.42%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.42%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.42%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.42%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.42%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.42%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.42%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.42%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1        | 0.42%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1        | 0.42%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.42%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.42%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.42%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.42%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 176      | 83.02%  |
| WiFi     | 32       | 15.09%  |
| Modem    | 4        | 1.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 162      | 90.5%   |
| WiFi     | 17       | 9.5%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 149      | 84.18%  |
| 2     | 25       | 14.12%  |
| 13    | 1        | 0.56%   |
| 8     | 1        | 0.56%   |
| 3     | 1        | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 172      | 97.18%  |
| Yes  | 5        | 2.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 12       | 48%     |
| Cambridge Silicon Radio | 6        | 24%     |
| Realtek Semiconductor   | 3        | 12%     |
| Broadcom                | 2        | 8%      |
| Logitech                | 1        | 4%      |
| IMC Networks            | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 8        | 32%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 24%     |
| Realtek Bluetooth Radio                             | 2        | 8%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 8%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4%      |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 4%      |
| Intel AX210 Bluetooth                               | 1        | 4%      |
| Intel AX200 Bluetooth                               | 1        | 4%      |
| IMC Networks Bluetooth Device                       | 1        | 4%      |
| Broadcom Bluetooth dongle                           | 1        | 4%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 125      | 54.35%  |
| Nvidia              | 47       | 20.43%  |
| AMD                 | 42       | 18.26%  |
| C-Media Electronics | 4        | 1.74%   |
| MCST                | 2        | 0.87%   |
| JMTek               | 2        | 0.87%   |
| Creative Technology | 2        | 0.87%   |
| Zhaoxin             | 1        | 0.43%   |
| VIA Technologies    | 1        | 0.43%   |
| EasyPass Industrial | 1        | 0.43%   |
| Creative Labs       | 1        | 0.43%   |
| Apple               | 1        | 0.43%   |
| A4Tech              | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 64       | 25.6%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18       | 7.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 6%      |
| AMD Family 17h/19h HD Audio Controller                                     | 10       | 4%      |
| Intel 200 Series PCH HD Audio                                              | 9        | 3.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 3.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 2.8%    |
| AMD FCH Azalia Controller                                                  | 7        | 2.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 2.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.6%    |
| Intel Sunrise Point-LP HD Audio                                            | 4        | 1.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 1.6%    |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3        | 1.2%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.2%    |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.2%    |
| Intel Audio device                                                         | 3        | 1.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.2%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.2%    |
| AMD Trinity HDMI Audio Controller                                          | 3        | 1.2%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.2%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 2        | 0.8%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.8%    |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.8%    |
| MCST HD Audio                                                              | 2        | 0.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 0.8%    |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 0.8%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 0.8%    |
| Zhaoxin ZX-E High Definition Audio Controller                              | 1        | 0.4%    |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                  | 1        | 0.4%    |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 0.4%    |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.4%    |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.4%    |
| Nvidia MCP73 High Definition Audio                                         | 1        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 28       | 21.54%  |
| Unknown             | 21       | 16.15%  |
| Kingston            | 21       | 16.15%  |
| Samsung Electronics | 14       | 10.77%  |
| Micron Technology   | 14       | 10.77%  |
| SK hynix            | 5        | 3.85%   |
| Foxline             | 4        | 3.08%   |
| Apacer              | 3        | 2.31%   |
| Patriot             | 2        | 1.54%   |
| Goodram             | 2        | 1.54%   |
| Goldkey             | 2        | 1.54%   |
| A-DATA Technology   | 2        | 1.54%   |
| Wilk                | 1        | 0.77%   |
| Unknown (0x0B7A)    | 1        | 0.77%   |
| tigo                | 1        | 0.77%   |
| Shenzhen Longsys    | 1        | 0.77%   |
| Ramaxel Technology  | 1        | 0.77%   |
| Qumo                | 1        | 0.77%   |
| Juhor               | 1        | 0.77%   |
| G.Skill             | 1        | 0.77%   |
| Elpida              | 1        | 0.77%   |
| Corsair             | 1        | 0.77%   |
| AMD                 | 1        | 0.77%   |
| Unknown             | 1        | 0.77%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s             | 13       | 9.15%   |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                         | 10       | 7.04%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s           | 4        | 2.82%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s           | 3        | 2.11%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2        | 1.41%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2        | 1.41%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2        | 1.41%   |
| Unknown RAM Module 1024MB DIMM                                   | 2        | 1.41%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2        | 1.41%   |
| Samsung RAM M378A1K43EB2-CVF 8GB DIMM DDR4 2933MT/s              | 2        | 1.41%   |
| Kingston RAM 99U5471-012.A00LF 4096MB DIMM DDR3 1600MT/s         | 2        | 1.41%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 2        | 1.41%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s           | 2        | 1.41%   |
| Wilk RAM IRX3000D464L16S/8G 8GB DIMM DDR4 3200MT/s               | 1        | 0.7%    |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1        | 0.7%    |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                        | 1        | 0.7%    |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1        | 0.7%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1        | 0.7%    |
| Unknown RAM Module 4096MB DIMM 333MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1        | 0.7%    |
| Unknown RAM Module 2048MB DIMM SDRAM 533MT/s                     | 1        | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1        | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                      | 1        | 0.7%    |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1        | 0.7%    |
| Unknown RAM Module 1024MB DIMM SDRAM 533MT/s                     | 1        | 0.7%    |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1        | 0.7%    |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1        | 0.7%    |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                       | 1        | 0.7%    |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 1024MB DIMM 400MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 1024MB DIMM 32MT/s                            | 1        | 0.7%    |
| Unknown (0x0B7A) RAM UDIMM PC4-2666 8G 1R 8GB DIMM DDR4 2667MT/s | 1        | 0.7%    |
| tigo RAM 4GB-2400MHZ 4GB SODIMM DDR4 2400MT/s                    | 1        | 0.7%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 1        | 0.7%    |
| SK hynix RAM HMT151R7TFR4C-H9 4096MB DIMM DDR3 1333MT/s          | 1        | 0.7%    |
| SK hynix RAM HMT151R7BFR4C-H9 4096MB DIMM DDR3 1333MT/s          | 1        | 0.7%    |
| SK hynix RAM HMA82GU6CJR8N-XN 16GB DIMM DDR4 3333MT/s            | 1        | 0.7%    |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1        | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 80       | 66.12%  |
| DDR3    | 22       | 18.18%  |
| Unknown | 11       | 9.09%   |
| DDR2    | 4        | 3.31%   |
| SDRAM   | 3        | 2.48%   |
| DDR     | 1        | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 106      | 87.6%   |
| SODIMM | 15       | 12.4%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 53       | 42.06%  |
| 8192  | 45       | 35.71%  |
| 1024  | 10       | 7.94%   |
| 2048  | 9        | 7.14%   |
| 16384 | 5        | 3.97%   |
| 512   | 3        | 2.38%   |
| 32768 | 1        | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 40       | 31.25%  |
| 1600    | 13       | 10.16%  |
| 2667    | 11       | 8.59%   |
| 3200    | 10       | 7.81%   |
| 2133    | 9        | 7.03%   |
| 1333    | 7        | 5.47%   |
| 2933    | 5        | 3.91%   |
| 800     | 4        | 3.13%   |
| 667     | 4        | 3.13%   |
| Unknown | 4        | 3.13%   |
| 400     | 3        | 2.34%   |
| 533     | 2        | 1.56%   |
| 333     | 2        | 1.56%   |
| 4333    | 1        | 0.78%   |
| 3600    | 1        | 0.78%   |
| 3534    | 1        | 0.78%   |
| 3466    | 1        | 0.78%   |
| 3333    | 1        | 0.78%   |
| 3266    | 1        | 0.78%   |
| 3151    | 1        | 0.78%   |
| 3066    | 1        | 0.78%   |
| 2866    | 1        | 0.78%   |
| 2666    | 1        | 0.78%   |
| 1867    | 1        | 0.78%   |
| 1866    | 1        | 0.78%   |
| 1066    | 1        | 0.78%   |
| 32      | 1        | 0.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 40%     |
| Hewlett-Packard     | 3        | 30%     |
| Canon               | 2        | 20%     |
| QinHeng Electronics | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Samsung SCX-4200 series        | 1        | 10%     |
| Samsung SCX-3400 Series        | 1        | 10%     |
| Samsung SCX-3200 Series        | 1        | 10%     |
| Samsung M332x 382x 402x Series | 1        | 10%     |
| QinHeng CH340S                 | 1        | 10%     |
| HP LaserJet P1102              | 1        | 10%     |
| HP LaserJet M402dn             | 1        | 10%     |
| HP LaserJet 1010               | 1        | 10%     |
| Canon MF4410                   | 1        | 10%     |
| Canon G1010 series             | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LIDE 25  | 1        | 50%     |
| Canon CanoScan LiDE 110 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 15       | 53.57%  |
| Alcor Micro             | 7        | 25%     |
| Z-Star Microelectronics | 1        | 3.57%   |
| Unknown                 | 1        | 3.57%   |
| Microsoft               | 1        | 3.57%   |
| Microdia                | 1        | 3.57%   |
| Hewlett-Packard         | 1        | 3.57%   |
| Apple                   | 1        | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Logitech Webcam C270               | 9        | 32.14%  |
| Alcor Micro USB 2.0 PC Camera      | 4        | 14.29%  |
| Logitech C505 HD Webcam            | 2        | 7.14%   |
| Alcor Micro SHUNCCM2MP             | 2        | 7.14%   |
| Z-Star Venus USB2.0 Camera         | 1        | 3.57%   |
| Unknown HD camera                  | 1        | 3.57%   |
| Microsoft LifeCam VX-700           | 1        | 3.57%   |
| Microdia Camera                    | 1        | 3.57%   |
| Logitech Webcam C930e              | 1        | 3.57%   |
| Logitech HD Webcam C525            | 1        | 3.57%   |
| Logitech HD Pro Webcam C920        | 1        | 3.57%   |
| Logitech B525 HD Webcam            | 1        | 3.57%   |
| HP Webcam HD 2300                  | 1        | 3.57%   |
| Apple iSight in LED Cinema Display | 1        | 3.57%   |
| Alcor Micro USB2.0 Camera          | 1        | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Aktiv  | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Aktiv Rutoken lite | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 164      | 91.11%  |
| 1     | 13       | 7.22%   |
| 2     | 2        | 1.11%   |
| 5     | 1        | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 8        | 38.1%   |
| Graphics card            | 5        | 23.81%  |
| Multimedia controller    | 2        | 9.52%   |
| Unassigned class         | 1        | 4.76%   |
| Sound                    | 1        | 4.76%   |
| Net/wireless             | 1        | 4.76%   |
| Net/ethernet             | 1        | 4.76%   |
| Chipcard                 | 1        | 4.76%   |
| Bluetooth                | 1        | 4.76%   |

