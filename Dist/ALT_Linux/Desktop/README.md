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

Total: 260

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Kometa P10         | 81       | 45%     |
| ALT Linux 9.1      | 33       | 18.33%  |
| ALT Linux 10.0     | 19       | 10.56%  |
| ALT Linux 9.0      | 15       | 8.33%   |
| ALT Linux 9.2      | 7        | 3.89%   |
| MOS 10             | 4        | 2.22%   |
| ALT Linux 10.1     | 3        | 1.67%   |
| ALT Linux P9       | 2        | 1.11%   |
| ALT Linux P8       | 2        | 1.11%   |
| ALT Linux P10      | 2        | 1.11%   |
| ALT Linux 8.4      | 2        | 1.11%   |
| ALT Linux 8.2      | 2        | 1.11%   |
| ALT Linux 7.0.5    | 2        | 1.11%   |
| Kometa 1           | 1        | 0.56%   |
| ALT Linux 8.2.0    | 1        | 0.56%   |
| ALT Linux 20201124 | 1        | 0.56%   |
| ALT Linux 20190303 | 1        | 0.56%   |
| ALT Linux 10.0.910 | 1        | 0.56%   |
| ALT Linux 10.0.900 | 1        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ALT Linux | 172      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.109-std-def-alt1       | 51       | 27.57%  |
| 5.10.102-std-def-alt1       | 27       | 14.59%  |
| 5.4.68-std-def-alt1.1       | 7        | 3.78%   |
| 5.10.82-std-def-alt1        | 6        | 3.24%   |
| 5.4.51-std-def-alt1         | 5        | 2.7%    |
| 5.15.32-un-def-alt1         | 5        | 2.7%    |
| 5.15.34-un-def-alt1         | 4        | 2.16%   |
| 5.4.41-std-def-alt1         | 3        | 1.62%   |
| 5.10.93-std-def-alt1        | 3        | 1.62%   |
| 5.10.35-un-def-alt1         | 3        | 1.62%   |
| 5.10.32-un-def-alt1         | 3        | 1.62%   |
| 4.19.79-std-def-alt1        | 3        | 1.62%   |
| 5.7.19-un-def-alt1          | 2        | 1.08%   |
| 5.4.85-std-def-alt1         | 2        | 1.08%   |
| 5.4.62-std-def-alt1         | 2        | 1.08%   |
| 5.4.28-std-def-alt1         | 2        | 1.08%   |
| 5.4.181-std-def-alt1        | 2        | 1.08%   |
| 5.4.127-std-def-alt1        | 2        | 1.08%   |
| 5.2.10-un-def-alt1          | 2        | 1.08%   |
| 5.15.15-un-def-alt1         | 2        | 1.08%   |
| 5.15.14-un-def-alt1         | 2        | 1.08%   |
| 5.10.88-std-def-alt1        | 2        | 1.08%   |
| 5.10.83-std-def-alt0.c9f.2  | 2        | 1.08%   |
| 5.10.72-std-def-alt1        | 2        | 1.08%   |
| 5.10.17-un-def-alt1         | 2        | 1.08%   |
| 5.9.8-un-def-alt1           | 1        | 0.54%   |
| 5.7.14-un-def-alt1          | 1        | 0.54%   |
| 5.4.94-std-def-alt1         | 1        | 0.54%   |
| 5.4.92-std-def-alt1         | 1        | 0.54%   |
| 5.4.91-elbrus-def-alt2.12.1 | 1        | 0.54%   |
| 5.4.81-std-def-alt1         | 1        | 0.54%   |
| 5.4.58-elbrus-def-alt1.7.0  | 1        | 0.54%   |
| 5.4.35-std-def-alt1         | 1        | 0.54%   |
| 5.4.134-std-def-alt1        | 1        | 0.54%   |
| 5.4.123-std-def-alt1        | 1        | 0.54%   |
| 5.4.104-std-def-alt1        | 1        | 0.54%   |
| 5.2.11-un-def-alt1          | 1        | 0.54%   |
| 5.15.53-un-def-alt1         | 1        | 0.54%   |
| 5.15.41-un-def-alt1         | 1        | 0.54%   |
| 5.15.37-un-def-alt1         | 1        | 0.54%   |
| 5.14.21-un-def-alt3         | 1        | 0.54%   |
| 5.14.21-un-def-alt1         | 1        | 0.54%   |
| 5.13.13-un-def-alt1         | 1        | 0.54%   |
| 5.12.19-un-def-alt2         | 1        | 0.54%   |
| 5.10.54-un-def-alt1.1       | 1        | 0.54%   |
| 5.10.54-std-def-alt2        | 1        | 0.54%   |
| 5.10.52-un-def-alt1         | 1        | 0.54%   |
| 5.10.45-un-def-alt1         | 1        | 0.54%   |
| 5.10.42-un-def-alt1         | 1        | 0.54%   |
| 5.10.128-std-def-alt1       | 1        | 0.54%   |
| 5.10.117-std-def-alt1       | 1        | 0.54%   |
| 5.10.113-std-def-alt1       | 1        | 0.54%   |
| 5.10.111-std-def-alt1       | 1        | 0.54%   |
| 5.10.110-std-def-alt1       | 1        | 0.54%   |
| 4.9.188-std-def-alt0.M80P.1 | 1        | 0.54%   |
| 4.9.133-std-def-alt0.M80P.1 | 1        | 0.54%   |
| 4.9.128-std-def-alt0.M80P.1 | 1        | 0.54%   |
| 4.20.14-un-def-alt1         | 1        | 0.54%   |
| 4.19.67-std-def-alt1        | 1        | 0.54%   |
| 4.19.182-old-def-alt1       | 1        | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.109 | 51       | 27.57%  |
| 5.10.102 | 27       | 14.59%  |
| 5.4.68   | 7        | 3.78%   |
| 5.10.82  | 6        | 3.24%   |
| 5.4.51   | 5        | 2.7%    |
| 5.15.32  | 5        | 2.7%    |
| 5.15.34  | 4        | 2.16%   |
| 5.4.41   | 3        | 1.62%   |
| 5.10.93  | 3        | 1.62%   |
| 5.10.35  | 3        | 1.62%   |
| 5.10.32  | 3        | 1.62%   |
| 4.19.79  | 3        | 1.62%   |
| 5.7.19   | 2        | 1.08%   |
| 5.4.85   | 2        | 1.08%   |
| 5.4.62   | 2        | 1.08%   |
| 5.4.28   | 2        | 1.08%   |
| 5.4.181  | 2        | 1.08%   |
| 5.4.127  | 2        | 1.08%   |
| 5.2.10   | 2        | 1.08%   |
| 5.15.15  | 2        | 1.08%   |
| 5.15.14  | 2        | 1.08%   |
| 5.14.21  | 2        | 1.08%   |
| 5.10.88  | 2        | 1.08%   |
| 5.10.83  | 2        | 1.08%   |
| 5.10.72  | 2        | 1.08%   |
| 5.10.54  | 2        | 1.08%   |
| 5.10.17  | 2        | 1.08%   |
| 5.9.8    | 1        | 0.54%   |
| 5.7.14   | 1        | 0.54%   |
| 5.4.94   | 1        | 0.54%   |
| 5.4.92   | 1        | 0.54%   |
| 5.4.91   | 1        | 0.54%   |
| 5.4.81   | 1        | 0.54%   |
| 5.4.58   | 1        | 0.54%   |
| 5.4.35   | 1        | 0.54%   |
| 5.4.134  | 1        | 0.54%   |
| 5.4.123  | 1        | 0.54%   |
| 5.4.104  | 1        | 0.54%   |
| 5.2.11   | 1        | 0.54%   |
| 5.15.53  | 1        | 0.54%   |
| 5.15.41  | 1        | 0.54%   |
| 5.15.37  | 1        | 0.54%   |
| 5.13.13  | 1        | 0.54%   |
| 5.12.19  | 1        | 0.54%   |
| 5.10.52  | 1        | 0.54%   |
| 5.10.45  | 1        | 0.54%   |
| 5.10.42  | 1        | 0.54%   |
| 5.10.128 | 1        | 0.54%   |
| 5.10.117 | 1        | 0.54%   |
| 5.10.113 | 1        | 0.54%   |
| 5.10.111 | 1        | 0.54%   |
| 5.10.110 | 1        | 0.54%   |
| 4.9.188  | 1        | 0.54%   |
| 4.9.133  | 1        | 0.54%   |
| 4.9.128  | 1        | 0.54%   |
| 4.20.14  | 1        | 0.54%   |
| 4.19.67  | 1        | 0.54%   |
| 4.19.182 | 1        | 0.54%   |
| 4.19.128 | 1        | 0.54%   |
| 4.19.102 | 1        | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 108      | 60.34%  |
| 5.4     | 34       | 18.99%  |
| 5.15    | 13       | 7.26%   |
| 4.19    | 7        | 3.91%   |
| 5.7     | 3        | 1.68%   |
| 5.2     | 3        | 1.68%   |
| 4.9     | 3        | 1.68%   |
| 5.14    | 2        | 1.12%   |
| 4.14    | 2        | 1.12%   |
| 5.9     | 1        | 0.56%   |
| 5.13    | 1        | 0.56%   |
| 5.12    | 1        | 0.56%   |
| 4.20    | 1        | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 166      | 96.51%  |
| i686   | 4        | 2.33%   |
| e2k    | 2        | 1.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 125      | 71.84%  |
| Unknown  | 23       | 13.22%  |
| XFCE     | 21       | 12.07%  |
| MATE     | 2        | 1.15%   |
| KDE      | 2        | 1.15%   |
| Cinnamon | 1        | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 167      | 97.09%  |
| Unknown | 5        | 2.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 112      | 64.37%  |
| TDM     | 28       | 16.09%  |
| LightDM | 21       | 12.07%  |
| Unknown | 13       | 7.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 141      | 80.11%  |
| Unknown | 33       | 18.75%  |
| en_US   | 1        | 0.57%   |
| el_GR   | 1        | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 109      | 63.01%  |
| BIOS | 64       | 36.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 162      | 93.64%  |
| Overlay | 9        | 5.2%    |
| Btrfs   | 2        | 1.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 121      | 69.94%  |
| MBR     | 40       | 23.12%  |
| Unknown | 12       | 6.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 152      | 88.37%  |
| Yes       | 20       | 11.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 128      | 73.14%  |
| Yes       | 47       | 26.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 44       | 25.58%  |
| ASUSTek Computer    | 31       | 18.02%  |
| Gigabyte Technology | 24       | 13.95%  |
| ASRock              | 18       | 10.47%  |
| Acer                | 13       | 7.56%   |
| Unknown             | 9        | 5.23%   |
| MSI                 | 7        | 4.07%   |
| MAINBRD             | 3        | 1.74%   |
| iRU                 | 3        | 1.74%   |
| 3Logic Group        | 3        | 1.74%   |
| Hewlett-Packard     | 2        | 1.16%   |
| DEPO Computers      | 2        | 1.16%   |
| Dell                | 2        | 1.16%   |
| VIA Technologies    | 1        | 0.58%   |
| SYS                 | 1        | 0.58%   |
| Supermicro          | 1        | 0.58%   |
| OEM                 | 1        | 0.58%   |
| Lenovo              | 1        | 0.58%   |
| Kraftway            | 1        | 0.58%   |
| Foxconn             | 1        | 0.58%   |
| EPoX Computer       | 1        | 0.58%   |
| ECS                 | 1        | 0.58%   |
| Biostar             | 1        | 0.58%   |
| Aquarius            | 1        | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Intel SKYBAY                                       | 43       | 25%     |
| ASUS PRIME B450-PLUS                               | 12       | 6.98%   |
| Acer Veriton X2640G                                | 10       | 5.81%   |
| Unknown                                            | 9        | 5.23%   |
| Gigabyte H110M-S2H                                 | 4        | 2.33%   |
| MAINBRD OPS62A-SHA                                 | 3        | 1.74%   |
| 3Logic Group Graviton                              | 3        | 1.74%   |
| iRU 515                                            | 2        | 1.16%   |
| Gigabyte H77M-D3H                                  | 2        | 1.16%   |
| ASUS H110M-R                                       | 2        | 1.16%   |
| Acer Veriton ES2710G                               | 2        | 1.16%   |
| VIA P4M266A-8235                                   | 1        | 0.58%   |
| SYS RAY B101                                       | 1        | 0.58%   |
| Supermicro SYS-1019D-14CN-FHN13TP                  | 1        | 0.58%   |
| OEM ZXE CRB                                        | 1        | 0.58%   |
| MSI MS-7D46                                        | 1        | 0.58%   |
| MSI MS-7A38                                        | 1        | 0.58%   |
| MSI MS-7996                                        | 1        | 0.58%   |
| MSI MS-7895                                        | 1        | 0.58%   |
| MSI MS-7758                                        | 1        | 0.58%   |
| MSI MS-7721                                        | 1        | 0.58%   |
| MSI MPG B560 Trident A (MS-B926)                   | 1        | 0.58%   |
| Lenovo ThinkCentre M73 10B1S15000                  | 1        | 0.58%   |
| Kraftway KWH310                                    | 1        | 0.58%   |
| iRU IRUB365M                                       | 1        | 0.58%   |
| Intel B75                                          | 1        | 0.58%   |
| HP Compaq dc7600 Convertible Minitower             | 1        | 0.58%   |
| HP 290 G4 Microtower PC                            | 1        | 0.58%   |
| Gigabyte Z77MX-D3H                                 | 1        | 0.58%   |
| Gigabyte X79-UD3                                   | 1        | 0.58%   |
| Gigabyte P35-S3G                                   | 1        | 0.58%   |
| Gigabyte J1800N-D2H                                | 1        | 0.58%   |
| Gigabyte H510M S2H                                 | 1        | 0.58%   |
| Gigabyte H310N 2.0                                 | 1        | 0.58%   |
| Gigabyte H110M-S2V                                 | 1        | 0.58%   |
| Gigabyte GA-MA69VM-S2                              | 1        | 0.58%   |
| Gigabyte GA-A75M-D2H                               | 1        | 0.58%   |
| Gigabyte GA-890XA-UD3                              | 1        | 0.58%   |
| Gigabyte G41MT-D3                                  | 1        | 0.58%   |
| Gigabyte G31M-ES2L                                 | 1        | 0.58%   |
| Gigabyte EP45-UD3LR                                | 1        | 0.58%   |
| Gigabyte EP35C-DS3R                                | 1        | 0.58%   |
| Gigabyte B550 GAMING X                             | 1        | 0.58%   |
| Gigabyte B450M S2H                                 | 1        | 0.58%   |
| Gigabyte B450 AORUS M                              | 1        | 0.58%   |
| Gigabyte A320M-S2H                                 | 1        | 0.58%   |
| Foxconn Pro 3400 Series MT                         | 1        | 0.58%   |
| EPoX GeForce6100 + nForce410 DDR: 8GF6100-M Series | 1        | 0.58%   |
| ECS T420                                           | 1        | 0.58%   |
| DEPO Computers DPH410S                             | 1        | 0.58%   |
| DEPO Computers DPA320S                             | 1        | 0.58%   |
| Dell OptiPlex 755                                  | 1        | 0.58%   |
| Dell OptiPlex 3050                                 | 1        | 0.58%   |
| Biostar NF720D A2G+                                | 1        | 0.58%   |
| ASUS Z8NR-D12                                      | 1        | 0.58%   |
| ASUS PRO H410T                                     | 1        | 0.58%   |
| ASUS PRIME Z390-A                                  | 1        | 0.58%   |
| ASUS PRIME H310M-R R2.0                            | 1        | 0.58%   |
| ASUS PRIME B550-PLUS                               | 1        | 0.58%   |
| ASUS PRIME B250-PRO                                | 1        | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel SKYBAY                      | 43       | 25%     |
| ASUS PRIME                        | 17       | 9.88%   |
| Acer Veriton                      | 12       | 6.98%   |
| Unknown                           | 9        | 5.23%   |
| Gigabyte H110M-S2H                | 4        | 2.33%   |
| MAINBRD OPS62A-SHA                | 3        | 1.74%   |
| 3Logic Group Graviton             | 3        | 1.74%   |
| iRU 515                           | 2        | 1.16%   |
| Gigabyte H77M-D3H                 | 2        | 1.16%   |
| Dell OptiPlex                     | 2        | 1.16%   |
| ASUS H110M-R                      | 2        | 1.16%   |
| VIA P4M266A-8235                  | 1        | 0.58%   |
| SYS RAY                           | 1        | 0.58%   |
| Supermicro SYS-1019D-14CN-FHN13TP | 1        | 0.58%   |
| OEM ZXE                           | 1        | 0.58%   |
| MSI MS-7D46                       | 1        | 0.58%   |
| MSI MS-7A38                       | 1        | 0.58%   |
| MSI MS-7996                       | 1        | 0.58%   |
| MSI MS-7895                       | 1        | 0.58%   |
| MSI MS-7758                       | 1        | 0.58%   |
| MSI MS-7721                       | 1        | 0.58%   |
| MSI MPG                           | 1        | 0.58%   |
| Lenovo ThinkCentre                | 1        | 0.58%   |
| Kraftway KWH310                   | 1        | 0.58%   |
| iRU IRUB365M                      | 1        | 0.58%   |
| Intel B75                         | 1        | 0.58%   |
| HP Compaq                         | 1        | 0.58%   |
| HP 290                            | 1        | 0.58%   |
| Gigabyte Z77MX-D3H                | 1        | 0.58%   |
| Gigabyte X79-UD3                  | 1        | 0.58%   |
| Gigabyte P35-S3G                  | 1        | 0.58%   |
| Gigabyte J1800N-D2H               | 1        | 0.58%   |
| Gigabyte H510M                    | 1        | 0.58%   |
| Gigabyte H310N                    | 1        | 0.58%   |
| Gigabyte H110M-S2V                | 1        | 0.58%   |
| Gigabyte GA-MA69VM-S2             | 1        | 0.58%   |
| Gigabyte GA-A75M-D2H              | 1        | 0.58%   |
| Gigabyte GA-890XA-UD3             | 1        | 0.58%   |
| Gigabyte G41MT-D3                 | 1        | 0.58%   |
| Gigabyte G31M-ES2L                | 1        | 0.58%   |
| Gigabyte EP45-UD3LR               | 1        | 0.58%   |
| Gigabyte EP35C-DS3R               | 1        | 0.58%   |
| Gigabyte B550                     | 1        | 0.58%   |
| Gigabyte B450M                    | 1        | 0.58%   |
| Gigabyte B450                     | 1        | 0.58%   |
| Gigabyte A320M-S2H                | 1        | 0.58%   |
| Foxconn Pro                       | 1        | 0.58%   |
| EPoX GeForce6100                  | 1        | 0.58%   |
| ECS T420                          | 1        | 0.58%   |
| DEPO Computers DPH410S            | 1        | 0.58%   |
| DEPO Computers DPA320S            | 1        | 0.58%   |
| Biostar NF720D                    | 1        | 0.58%   |
| ASUS Z8NR-D12                     | 1        | 0.58%   |
| ASUS PRO                          | 1        | 0.58%   |
| ASUS P5Q                          | 1        | 0.58%   |
| ASUS P5G41T-M                     | 1        | 0.58%   |
| ASUS P5B-MX                       | 1        | 0.58%   |
| ASUS P5B                          | 1        | 0.58%   |
| ASUS M5A99X                       | 1        | 0.58%   |
| ASUS M4A78-EM                     | 1        | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 42       | 24.42%  |
| 2017    | 33       | 19.19%  |
| 2016    | 20       | 11.63%  |
| 2020    | 12       | 6.98%   |
| 2021    | 8        | 4.65%   |
| 2022    | 7        | 4.07%   |
| 2012    | 7        | 4.07%   |
| 2015    | 6        | 3.49%   |
| 2008    | 5        | 2.91%   |
| 2019    | 4        | 2.33%   |
| 2014    | 4        | 2.33%   |
| 2011    | 4        | 2.33%   |
| 2009    | 4        | 2.33%   |
| 2010    | 3        | 1.74%   |
| 2007    | 3        | 1.74%   |
| 2005    | 3        | 1.74%   |
| 2013    | 2        | 1.16%   |
| 2006    | 2        | 1.16%   |
| Unknown | 2        | 1.16%   |
| 2003    | 1        | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 172      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 164      | 95.35%  |
| Enabled  | 8        | 4.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 172      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 77       | 44.77%  |
| 4.01-8.0    | 42       | 24.42%  |
| 3.01-4.0    | 26       | 15.12%  |
| 16.01-24.0  | 12       | 6.98%   |
| 1.01-2.0    | 5        | 2.91%   |
| 32.01-64.0  | 3        | 1.74%   |
| 64.01-256.0 | 3        | 1.74%   |
| 2.01-3.0    | 2        | 1.16%   |
| 0.51-1.0    | 2        | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 91       | 50.84%  |
| 0.51-1.0  | 29       | 16.2%   |
| 2.01-3.0  | 25       | 13.97%  |
| 4.01-8.0  | 16       | 8.94%   |
| 3.01-4.0  | 12       | 6.7%    |
| 8.01-16.0 | 3        | 1.68%   |
| 0.01-0.5  | 3        | 1.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 121      | 69.14%  |
| 2      | 37       | 21.14%  |
| 3      | 12       | 6.86%   |
| 4      | 3        | 1.71%   |
| 5      | 1        | 0.57%   |
| 0      | 1        | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 63.95%  |
| Yes       | 62       | 36.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 171      | 99.42%  |
| No        | 1        | 0.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 143      | 83.14%  |
| Yes       | 29       | 16.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 151      | 87.28%  |
| Yes       | 22       | 12.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Russia     | 166      | 96.51%  |
| Greece     | 2        | 1.16%   |
| Ukraine    | 1        | 0.58%   |
| Kazakhstan | 1        | 0.58%   |
| China      | 1        | 0.58%   |
| Belarus    | 1        | 0.58%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Moscow                   | 116      | 65.54%  |
| St Petersburg            | 7        | 3.95%   |
| Samara                   | 5        | 2.82%   |
| Irkutsk                  | 3        | 1.69%   |
| Barnaul                  | 3        | 1.69%   |
| Saratov                  | 2        | 1.13%   |
| Kaliningrad              | 2        | 1.13%   |
| Zelenodolsk              | 1        | 0.56%   |
| Yekaterinburg            | 1        | 0.56%   |
| Vologda                  | 1        | 0.56%   |
| Vladivostok              | 1        | 0.56%   |
| Verkhnyaya Pyshma        | 1        | 0.56%   |
| Vergina                  | 1        | 0.56%   |
| Valuyki                  | 1        | 0.56%   |
| Tula                     | 1        | 0.56%   |
| Thessaloniki             | 1        | 0.56%   |
| Taraz                    | 1        | 0.56%   |
| Tambov                   | 1        | 0.56%   |
| Surgut                   | 1        | 0.56%   |
| Shenzhen                 | 1        | 0.56%   |
| Sevastopol               | 1        | 0.56%   |
| Rostov-on-Don            | 1        | 0.56%   |
| Pushchino                | 1        | 0.56%   |
| Protvino                 | 1        | 0.56%   |
| Polyarnyy                | 1        | 0.56%   |
| Petropavlovsk-Kamchatsky | 1        | 0.56%   |
| Perm                     | 1        | 0.56%   |
| Obninsk                  | 1        | 0.56%   |
| Nizhniy Novgorod         | 1        | 0.56%   |
| Murmansk                 | 1        | 0.56%   |
| Monchegorsk              | 1        | 0.56%   |
| Mogilev                  | 1        | 0.56%   |
| Lipetsk                  | 1        | 0.56%   |
| Kyzyl                    | 1        | 0.56%   |
| Krasnoyarsk              | 1        | 0.56%   |
| Krasnokamensk            | 1        | 0.56%   |
| Krasnogorsk              | 1        | 0.56%   |
| Krasnodar                | 1        | 0.56%   |
| Kostroma                 | 1        | 0.56%   |
| Korolyov                 | 1        | 0.56%   |
| Kirovsk                  | 1        | 0.56%   |
| Kirov                    | 1        | 0.56%   |
| Ivanovo                  | 1        | 0.56%   |
| Belgorod                 | 1        | 0.56%   |
| Balashikha               | 1        | 0.56%   |
| Almaty                   | 1        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 45       | 65     | 20.93%  |
| Seagate             | 28       | 43     | 13.02%  |
| Samsung Electronics | 26       | 31     | 12.09%  |
| AXIOMTEK            | 26       | 26     | 12.09%  |
| Toshiba             | 24       | 39     | 11.16%  |
| Kingston            | 17       | 19     | 7.91%   |
| China               | 8        | 8      | 3.72%   |
| Hitachi             | 5        | 6      | 2.33%   |
| A-DATA Technology   | 5        | 5      | 2.33%   |
| Apacer              | 4        | 6      | 1.86%   |
| Phison              | 2        | 2      | 0.93%   |
| Intel               | 2        | 6      | 0.93%   |
| Gigabyte Technology | 2        | 2      | 0.93%   |
| DEPO                | 2        | 2      | 0.93%   |
| Crucial             | 2        | 2      | 0.93%   |
| XPG                 | 1        | 1      | 0.47%   |
| TMI                 | 1        | 1      | 0.47%   |
| SPCC                | 1        | 1      | 0.47%   |
| SP-8                | 1        | 1      | 0.47%   |
| Smartbuy            | 1        | 1      | 0.47%   |
| SINTECHI            | 1        | 1      | 0.47%   |
| SanDisk             | 1        | 1      | 0.47%   |
| Plextor             | 1        | 1      | 0.47%   |
| Patriot             | 1        | 1      | 0.47%   |
| OCZ                 | 1        | 1      | 0.47%   |
| Micron Technology   | 1        | 1      | 0.47%   |
| LITEON              | 1        | 1      | 0.47%   |
| KingSpec            | 1        | 1      | 0.47%   |
| JMicron Technology  | 1        | 1      | 0.47%   |
| HEORIADY            | 1        | 1      | 0.47%   |
| Foxline             | 1        | 1      | 0.47%   |
| AMD                 | 1        | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD   | 26       | 11.4%   |
| Samsung MZVLW128HEGR-00000 128GB       | 17       | 7.46%   |
| Toshiba HDWD120 2TB                    | 13       | 5.7%    |
| WDC WD5000AZLX-21K2TA0 500GB           | 10       | 4.39%   |
| Toshiba HDWD110 1TB                    | 5        | 2.19%   |
| Kingston SV300S37A120G 120GB SSD       | 4        | 1.75%   |
| Kingston RBUSC180S37256GJ 256GB SSD    | 4        | 1.75%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 3        | 1.32%   |
| Samsung SSD 860 EVO 250GB              | 3        | 1.32%   |
| Kingston SA400S37120G 120GB SSD        | 3        | 1.32%   |
| WDC WD3200AAKS-00G3A0 320GB            | 2        | 0.88%   |
| WDC WD10PURZ-85U8XY0 1TB               | 2        | 0.88%   |
| Toshiba DT01ACA100 1TB                 | 2        | 0.88%   |
| Seagate ST500LM030-2E717D 500GB        | 2        | 0.88%   |
| Seagate ST500DM002-1BC142 500GB        | 2        | 0.88%   |
| Seagate ST380815AS 80GB                | 2        | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB         | 2        | 0.88%   |
| Samsung SSD 860 EVO 500GB              | 2        | 0.88%   |
| Phison M.2 128GB SSO128GTLCG-SBC-2 SSD | 2        | 0.88%   |
| Kingston SA400S37240G 240GB SSD        | 2        | 0.88%   |
| Hitachi HDS721025CLA382 165GB          | 2        | 0.88%   |
| DEPO SM3DT-120 120GB SSD               | 2        | 0.88%   |
| China SSD 128GB                        | 2        | 0.88%   |
| Apacer AS350 256GB SSD                 | 2        | 0.88%   |
| XPG GAMMIX S5 256GB                    | 1        | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1        | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1        | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1        | 0.44%   |
| WDC WD800AAJS-00WAA0 80GB              | 1        | 0.44%   |
| WDC WD7501AALS-00E3A0 752GB            | 1        | 0.44%   |
| WDC WD5003ABYZ-011FA0 500GB            | 1        | 0.44%   |
| WDC WD5001ABYS-01YNA0 500GB            | 1        | 0.44%   |
| WDC WD5001AALS-00E3A0 500GB            | 1        | 0.44%   |
| WDC WD5000HHTZ-04N21V0 500GB           | 1        | 0.44%   |
| WDC WD5000AZRZ-00HTKB0 500GB           | 1        | 0.44%   |
| WDC WD5000AZLX-00JKKA0 500GB           | 1        | 0.44%   |
| WDC WD3200BPVT-00HXZT3 320GB           | 1        | 0.44%   |
| WDC WD3200BEVT-80A0RT0 320GB           | 1        | 0.44%   |
| WDC WD3200AAKS-00V1A0 320GB            | 1        | 0.44%   |
| WDC WD3200AAKS-00UU3A0 320GB           | 1        | 0.44%   |
| WDC WD30EZRX-00DC0B0 3TB               | 1        | 0.44%   |
| WDC WD2500KS-00MJB0 250GB              | 1        | 0.44%   |
| WDC WD2500BEVT-60ZCT1 250GB            | 1        | 0.44%   |
| WDC WD20EZBX-00AYRA0 2TB               | 1        | 0.44%   |
| WDC WD20EURX-63T0FY0 2TB               | 1        | 0.44%   |
| WDC WD20EARX-008FB0 2TB                | 1        | 0.44%   |
| WDC WD2005FBYZ-01YCBB3 2TB             | 1        | 0.44%   |
| WDC WD2000FYYZ-01UL1B1 2TB             | 1        | 0.44%   |
| WDC WD1600AAJS-61M0A0 160GB            | 1        | 0.44%   |
| WDC WD10SPSX-00A6WT0 1TB               | 1        | 0.44%   |
| WDC WD10JPVX-00JC3T0 1TB               | 1        | 0.44%   |
| WDC WD10EZRZ-00HTKB0 1TB               | 1        | 0.44%   |
| WDC WD10EZEX-60ZF5A0 1TB               | 1        | 0.44%   |
| WDC WD10EZEX-21WN4A0 1TB               | 1        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB               | 1        | 0.44%   |
| WDC WD10EZEX-08M2NA0 1TB               | 1        | 0.44%   |
| WDC WD1004FBYZ-01YCBB1 1TB             | 1        | 0.44%   |
| WDC WD1003FZEX-00MK2A0 1TB             | 1        | 0.44%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB     | 1        | 0.44%   |
| Toshiba HDWK105 500GB                  | 1        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 39       | 58     | 41.05%  |
| Seagate  | 26       | 38     | 27.37%  |
| Toshiba  | 24       | 39     | 25.26%  |
| Hitachi  | 5        | 6      | 5.26%   |
| SINTECHI | 1        | 1      | 1.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| AXIOMTEK            | 26       | 26     | 27.96%  |
| Kingston            | 16       | 17     | 17.2%   |
| China               | 8        | 8      | 8.6%    |
| Samsung Electronics | 7        | 9      | 7.53%   |
| WDC                 | 6        | 6      | 6.45%   |
| Apacer              | 4        | 6      | 4.3%    |
| A-DATA Technology   | 4        | 4      | 4.3%    |
| Seagate             | 2        | 5      | 2.15%   |
| Phison              | 2        | 2      | 2.15%   |
| DEPO                | 2        | 2      | 2.15%   |
| Crucial             | 2        | 2      | 2.15%   |
| TMI                 | 1        | 1      | 1.08%   |
| SP-8                | 1        | 1      | 1.08%   |
| Smartbuy            | 1        | 1      | 1.08%   |
| SanDisk             | 1        | 1      | 1.08%   |
| Plextor             | 1        | 1      | 1.08%   |
| Patriot             | 1        | 1      | 1.08%   |
| OCZ                 | 1        | 1      | 1.08%   |
| LITEON              | 1        | 1      | 1.08%   |
| KingSpec            | 1        | 1      | 1.08%   |
| Intel               | 1        | 4      | 1.08%   |
| HEORIADY            | 1        | 1      | 1.08%   |
| Gigabyte Technology | 1        | 1      | 1.08%   |
| Foxline             | 1        | 1      | 1.08%   |
| AMD                 | 1        | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 88       | 104    | 43.56%  |
| HDD  | 85       | 142    | 42.08%  |
| NVMe | 29       | 33     | 14.36%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 149      | 246    | 83.71%  |
| NVMe | 28       | 32     | 15.73%  |
| SAS  | 1        | 1      | 0.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 120      | 154    | 68.18%  |
| 0.51-1.0   | 30       | 45     | 17.05%  |
| 1.01-2.0   | 24       | 44     | 13.64%  |
| 2.01-3.0   | 2        | 3      | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 85       | 48.57%  |
| 251-500        | 27       | 15.43%  |
| 1001-2000      | 23       | 13.14%  |
| 501-1000       | 11       | 6.29%   |
| 21-50          | 8        | 4.57%   |
| 51-100         | 7        | 4%      |
| More than 3000 | 5        | 2.86%   |
| 1-20           | 5        | 2.86%   |
| 2001-3000      | 3        | 1.71%   |
| Unknown        | 1        | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 108      | 60.67%  |
| 21-50          | 22       | 12.36%  |
| 101-250        | 14       | 7.87%   |
| 51-100         | 14       | 7.87%   |
| 501-1000       | 8        | 4.49%   |
| 251-500        | 5        | 2.81%   |
| 1001-2000      | 3        | 1.69%   |
| More than 3000 | 2        | 1.12%   |
| 2001-3000      | 1        | 0.56%   |
| Unknown        | 1        | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD7501AALS-00E3A0 752GB           | 1        | 1      | 5.88%   |
| WDC WD3200AAKS-00V1A0 320GB           | 1        | 1      | 5.88%   |
| WDC WD2500KS-00MJB0 250GB             | 1        | 1      | 5.88%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1        | 3      | 5.88%   |
| WDC WD20EARX-008FB0 2TB               | 1        | 1      | 5.88%   |
| Seagate ST9250315AS 250GB             | 1        | 1      | 5.88%   |
| Seagate ST380815AS 80GB               | 1        | 1      | 5.88%   |
| Seagate ST380811AS 80GB               | 1        | 1      | 5.88%   |
| Seagate ST3320418AS 320GB             | 1        | 1      | 5.88%   |
| Seagate ST3000DM001-1CH166 3TB        | 1        | 1      | 5.88%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 2      | 5.88%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 5.88%   |
| Hitachi HUA722010CLA330 1TB           | 1        | 1      | 5.88%   |
| Hitachi HTS545050KTA300 500GB         | 1        | 2      | 5.88%   |
| Hitachi HDS723020BLA642 2TB           | 1        | 1      | 5.88%   |
| Hitachi HDS721025CLA382 165GB         | 1        | 1      | 5.88%   |
| DEPO SM3DT-120 120GB SSD              | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 35.29%  |
| WDC                 | 5        | 7      | 29.41%  |
| Hitachi             | 4        | 5      | 23.53%  |
| Samsung Electronics | 1        | 1      | 5.88%   |
| DEPO                | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 6        | 7      | 40%     |
| WDC     | 5        | 7      | 33.33%  |
| Hitachi | 4        | 5      | 26.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 19     | 87.5%   |
| SSD  | 2        | 2      | 12.5%   |

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
| Works    | 147      | 216    | 79.46%  |
| Detected | 21       | 41     | 11.35%  |
| Malfunc  | 16       | 21     | 8.65%   |
| Failed   | 1        | 1      | 0.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 125      | 59.52%  |
| AMD                         | 36       | 17.14%  |
| Samsung Electronics         | 19       | 9.05%   |
| Nvidia                      | 7        | 3.33%   |
| JMicron Technology          | 5        | 2.38%   |
| ASMedia Technology          | 3        | 1.43%   |
| Realtek Semiconductor       | 2        | 0.95%   |
| MCST                        | 2        | 0.95%   |
| Marvell Technology Group    | 2        | 0.95%   |
| Kingston Technology Company | 2        | 0.95%   |
| Zhaoxin                     | 1        | 0.48%   |
| VIA Technologies            | 1        | 0.48%   |
| Silicon Motion              | 1        | 0.48%   |
| SanDisk                     | 1        | 0.48%   |
| Phison Electronics          | 1        | 0.48%   |
| Micron Technology           | 1        | 0.48%   |
| LSI Logic / Symbios Logic   | 1        | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 64       | 25%     |
| AMD FCH SATA Controller [AHCI mode]                                              | 29       | 11.33%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 17       | 6.64%   |
| AMD 400 Series Chipset SATA Controller                                           | 16       | 6.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 9        | 3.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6        | 2.34%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 5        | 1.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5        | 1.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 5        | 1.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4        | 1.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4        | 1.56%   |
| AMD FCH SATA Controller D                                                        | 4        | 1.56%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3        | 1.17%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3        | 1.17%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 3        | 1.17%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 3        | 1.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3        | 1.17%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3        | 1.17%   |
| AMD 500 Series Chipset SATA Controller                                           | 3        | 1.17%   |
| Realtek Realtek Non-Volatile memory controller                                   | 2        | 0.78%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2        | 0.78%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                     | 2        | 0.78%   |
| Nvidia MCP51 Serial ATA Controller                                               | 2        | 0.78%   |
| Nvidia MCP51 IDE                                                                 | 2        | 0.78%   |
| MCST SATA                                                                        | 2        | 0.78%   |
| MCST IDE controller                                                              | 2        | 0.78%   |
| JMicron JMB368 IDE controller                                                    | 2        | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2        | 0.78%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2        | 0.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2        | 0.78%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 2        | 0.78%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 2        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 0.78%   |
| Zhaoxin ZX-100/ZX-200/ZX-E StorX AHCI Controller                                 | 1        | 0.39%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1        | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1        | 0.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1        | 0.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1        | 0.39%   |
| Phison PS5013 E13 NVMe Controller                                                | 1        | 0.39%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 1        | 0.39%   |
| Nvidia MCP73 IDE Controller                                                      | 1        | 0.39%   |
| Nvidia MCP61 SATA Controller                                                     | 1        | 0.39%   |
| Nvidia CK804 Serial ATA Controller                                               | 1        | 0.39%   |
| Nvidia CK804 IDE                                                                 | 1        | 0.39%   |
| Micron Non-Volatile memory controller                                            | 1        | 0.39%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1        | 0.39%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 1        | 0.39%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                          | 1        | 0.39%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1        | 0.39%   |
| Kingston Company A2000 NVMe SSD                                                  | 1        | 0.39%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1        | 0.39%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 0.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 0.39%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1        | 0.39%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1        | 0.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 0.39%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1        | 0.39%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1        | 0.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 150      | 71.43%  |
| IDE  | 30       | 14.29%  |
| NVMe | 28       | 13.33%  |
| RAID | 2        | 0.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 127      | 73.84%  |
| AMD          | 42       | 24.42%  |
| E8C/EATX     | 1        | 0.58%   |
| E8C-SWTX     | 1        | 0.58%   |
| CentaurHauls | 1        | 0.58%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-6100TE CPU @ 2.70GHz          | 43       | 24.71%  |
| AMD Ryzen 5 1600 Six-Core Processor         | 13       | 7.47%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 10       | 5.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4        | 2.3%    |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3        | 1.72%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 3        | 1.72%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 3        | 1.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3        | 1.72%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.72%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 2        | 1.15%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 1.15%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 2        | 1.15%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 1.15%   |
| Intel Genuine CPU 0000 @ 2.40GHz            | 2        | 1.15%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.15%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.15%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.15%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 1.15%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.15%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.15%   |
| AMD Athlon 64 X2 Dual Core Processor 4800+  | 2        | 1.15%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.15%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 2        | 1.15%   |
| Intel Xeon D-2177NT CPU @ 1.90GHz           | 1        | 0.57%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.57%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.57%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.57%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.57%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.57%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.57%   |
| Intel Pentium CPU G4500 @ 3.50GHz           | 1        | 0.57%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.57%   |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1        | 0.57%   |
| Intel Core i9-10980XE CPU @ 3.00GHz         | 1        | 0.57%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.57%   |
| Intel Core i7-4960X CPU @ 3.60GHz           | 1        | 0.57%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.57%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.57%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.57%   |
| Intel Core i5-8265UC CPU @ 1.60GHz          | 1        | 0.57%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 0.57%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 0.57%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 0.57%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 0.57%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 0.57%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 0.57%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 0.57%   |
| Intel Core i3-10100T CPU @ 3.00GHz          | 1        | 0.57%   |
| Intel Core 2 Quad CPU Q9500 @ 2.83GHz       | 1        | 0.57%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 0.57%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 0.57%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 1        | 0.57%   |
| Intel Celeron G6900                         | 1        | 0.57%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 1        | 0.57%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1        | 0.57%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 0.57%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 1        | 0.57%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 1        | 0.57%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 1        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 58       | 33.53%  |
| Intel Core i5           | 17       | 9.83%   |
| AMD Ryzen 5             | 17       | 9.83%   |
| Intel Pentium           | 13       | 7.51%   |
| Intel Celeron           | 9        | 5.2%    |
| Other                   | 8        | 4.62%   |
| Intel Pentium Dual-Core | 5        | 2.89%   |
| Intel Core 2 Duo        | 4        | 2.31%   |
| AMD Ryzen 7             | 4        | 2.31%   |
| AMD Athlon 64 X2        | 4        | 2.31%   |
| Intel Xeon              | 3        | 1.73%   |
| Intel Pentium Gold      | 3        | 1.73%   |
| AMD A8                  | 3        | 1.73%   |
| Intel Genuine           | 2        | 1.16%   |
| Intel Core i9           | 2        | 1.16%   |
| Intel Core i7           | 2        | 1.16%   |
| Intel Core 2 Quad       | 2        | 1.16%   |
| AMD Ryzen 3             | 2        | 1.16%   |
| AMD Phenom II X4        | 2        | 1.16%   |
| AMD FX                  | 2        | 1.16%   |
| AMD Athlon              | 2        | 1.16%   |
| AMD A10                 | 2        | 1.16%   |
| Intel Pentium D         | 1        | 0.58%   |
| Intel Pentium 4         | 1        | 0.58%   |
| AMD Sempron             | 1        | 0.58%   |
| AMD Ryzen 7 PRO         | 1        | 0.58%   |
| AMD Ryzen 5 PRO         | 1        | 0.58%   |
| AMD Athlon II X4        | 1        | 0.58%   |
| AMD A6                  | 1        | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 94       | 54.34%  |
| 4      | 39       | 22.54%  |
| 6      | 22       | 12.72%  |
| 8      | 9        | 5.2%    |
| 1      | 3        | 1.73%   |
| 3      | 2        | 1.16%   |
| 32     | 1        | 0.58%   |
| 18     | 1        | 0.58%   |
| 16     | 1        | 0.58%   |
| 14     | 1        | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 169      | 98.26%  |
| 2      | 2        | 1.16%   |
| 4      | 1        | 0.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 117      | 68.02%  |
| 1      | 55       | 31.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 169      | 98.26%  |
| Unknown        | 2        | 1.16%   |
| 32-bit         | 1        | 0.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 49       | 28.16%  |
| Unknown    | 27       | 15.52%  |
| 0x906e9    | 13       | 7.47%   |
| 0x08001138 | 13       | 7.47%   |
| 0x1067a    | 9        | 5.17%   |
| 0xa0653    | 6        | 3.45%   |
| 0x906eb    | 5        | 2.87%   |
| 0x906ea    | 4        | 2.3%    |
| 0x306a9    | 4        | 2.3%    |
| 0x08108109 | 4        | 2.3%    |
| 0x806e9    | 3        | 1.72%   |
| 0x806c1    | 3        | 1.72%   |
| 0xa0671    | 2        | 1.15%   |
| 0x906ed    | 2        | 1.15%   |
| 0x30679    | 2        | 1.15%   |
| 0x206a7    | 2        | 1.15%   |
| 0x08701021 | 2        | 1.15%   |
| 0x06001119 | 2        | 1.15%   |
| 0x010000db | 2        | 1.15%   |
| 0xf47      | 1        | 0.57%   |
| 0xf29      | 1        | 0.57%   |
| 0x806ec    | 1        | 0.57%   |
| 0x6fb      | 1        | 0.57%   |
| 0x506e8    | 1        | 0.57%   |
| 0x506c9    | 1        | 0.57%   |
| 0x50657    | 1        | 0.57%   |
| 0x50654    | 1        | 0.57%   |
| 0x306e4    | 1        | 0.57%   |
| 0x306c3    | 1        | 0.57%   |
| 0x206c2    | 1        | 0.57%   |
| 0x10661    | 1        | 0.57%   |
| 0x0a50000c | 1        | 0.57%   |
| 0x08108102 | 1        | 0.57%   |
| 0x0810100b | 1        | 0.57%   |
| 0x0800820d | 1        | 0.57%   |
| 0x08001129 | 1        | 0.57%   |
| 0x06000852 | 1        | 0.57%   |
| 0x010000c8 | 1        | 0.57%   |
| 0x00000000 | 1        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Skylake     | 54       | 31.4%   |
| KabyLake    | 30       | 17.44%  |
| Zen         | 15       | 8.72%   |
| Penryn      | 10       | 5.81%   |
| Zen+        | 7        | 4.07%   |
| CometLake   | 7        | 4.07%   |
| IvyBridge   | 6        | 3.49%   |
| Unknown     | 6        | 3.49%   |
| Piledriver  | 5        | 2.91%   |
| K8 Hammer   | 5        | 2.91%   |
| Zen 2       | 3        | 1.74%   |
| TigerLake   | 3        | 1.74%   |
| Silvermont  | 3        | 1.74%   |
| SandyBridge | 3        | 1.74%   |
| K10         | 3        | 1.74%   |
| Steamroller | 2        | 1.16%   |
| NetBurst    | 2        | 1.16%   |
| Haswell     | 2        | 1.16%   |
| Core        | 2        | 1.16%   |
| Zen 3       | 1        | 0.58%   |
| Westmere    | 1        | 0.58%   |
| K10 Llano   | 1        | 0.58%   |
| Goldmont    | 1        | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 102      | 57.63%  |
| Nvidia            | 48       | 27.12%  |
| AMD               | 22       | 12.43%  |
| Silicon Motion    | 2        | 1.13%   |
| ASPEED Technology | 2        | 1.13%   |
| Zhaoxin           | 1        | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                                    | 46       | 25.56%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 17       | 9.44%   |
| Intel HD Graphics 610                                                                    | 10       | 5.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9        | 5%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6        | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6        | 3.33%   |
| Intel HD Graphics 510                                                                    | 5        | 2.78%   |
| Intel HD Graphics 620                                                                    | 4        | 2.22%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 1.67%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3        | 1.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3        | 1.67%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 3        | 1.67%   |
| Silicon Motion SM718 LynxSE+                                                             | 2        | 1.11%   |
| Intel HD Graphics 630                                                                    | 2        | 1.11%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.11%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.11%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 1.11%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.11%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.56%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.56%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.56%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.56%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.56%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.56%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1        | 0.56%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1        | 0.56%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.56%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.56%   |
| Nvidia GK106 [GeForce GTX 650 Ti Boost]                                                  | 1        | 0.56%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.56%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 0.56%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 1        | 0.56%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 0.56%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1        | 0.56%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 0.56%   |
| Nvidia G92 [GeForce 8800 GT]                                                             | 1        | 0.56%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 0.56%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 0.56%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 0.56%   |
| Nvidia C51PV [GeForce 6150]                                                              | 1        | 0.56%   |
| Nvidia C51G [GeForce 6100]                                                               | 1        | 0.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 0.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1        | 0.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.56%   |
| Intel HD Graphics 500                                                                    | 1        | 0.56%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                                 | 1        | 0.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1        | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 0.56%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 0.56%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 0.56%   |
| AMD Trinity [Radeon HD 7660D]                                                            | 1        | 0.56%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 1        | 0.56%   |
| AMD RV530LE [Radeon X1600/X1650 PRO]                                                     | 1        | 0.56%   |
| AMD RV530 [Radeon X1650] (Secondary)                                                     | 1        | 0.56%   |
| AMD RV530 [Radeon X1600] (Secondary)                                                     | 1        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 99       | 57.56%  |
| 1 x Nvidia         | 46       | 26.74%  |
| 1 x AMD            | 19       | 11.05%  |
| 2 x AMD            | 2        | 1.16%   |
| 1 x Silicon Motion | 2        | 1.16%   |
| 1 x ASPEED         | 2        | 1.16%   |
| Nvidia + Zhaoxin   | 1        | 0.58%   |
| Intel + Nvidia     | 1        | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 132      | 76.3%   |
| Proprietary | 36       | 20.81%  |
| Unknown     | 5        | 2.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 111      | 64.16%  |
| 3.01-4.0   | 21       | 12.14%  |
| 0.51-1.0   | 13       | 7.51%   |
| 0.01-0.5   | 13       | 7.51%   |
| 1.01-2.0   | 11       | 6.36%   |
| 7.01-8.0   | 1        | 0.58%   |
| 5.01-6.0   | 1        | 0.58%   |
| 2.01-3.0   | 1        | 0.58%   |
| 8.01-16.0  | 1        | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| HHT                  | 43       | 24.57%  |
| Acer                 | 23       | 13.14%  |
| BenQ                 | 20       | 11.43%  |
| AOC                  | 19       | 10.86%  |
| Samsung Electronics  | 16       | 9.14%   |
| ViewSonic            | 8        | 4.57%   |
| Goldstar             | 8        | 4.57%   |
| Dell                 | 6        | 3.43%   |
| PRW                  | 4        | 2.29%   |
| Philips              | 4        | 2.29%   |
| WBT                  | 3        | 1.71%   |
| LG Electronics       | 3        | 1.71%   |
| Ancor Communications | 3        | 1.71%   |
| STD                  | 2        | 1.14%   |
| Hewlett-Packard      | 2        | 1.14%   |
| VIE                  | 1        | 0.57%   |
| Toshiba              | 1        | 0.57%   |
| SKG                  | 1        | 0.57%   |
| Lenovo               | 1        | 0.57%   |
| JRY                  | 1        | 0.57%   |
| HIB                  | 1        | 0.57%   |
| HannStar             | 1        | 0.57%   |
| DZW                  | 1        | 0.57%   |
| ASUSTek Computer     | 1        | 0.57%   |
| Apple                | 1        | 0.57%   |
| Unknown              | 1        | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HHT ActviPanel V5 HHT0030 3840x2160 944x398mm 40.3-inch               | 43       | 23.76%  |
| AOC LCD Monitor 2778X 2560x1440                                       | 11       | 6.08%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                     | 10       | 5.52%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 7        | 3.87%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 5        | 2.76%   |
| ViewSonic LCD Monitor VSC8C31 1920x1080 520x290mm 23.4-inch           | 4        | 2.21%   |
| PRW AP7_Titanium PRW4200 3840x2160                                    | 4        | 2.21%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                      | 3        | 1.66%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2        | 1.1%    |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                         | 2        | 1.1%    |
| Samsung Electronics S22E391 SAM0C0E 1920x1080 477x268mm 21.5-inch     | 2        | 1.1%    |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                | 2        | 1.1%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2        | 1.1%    |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 2        | 1.1%    |
| AOC G2490W1G4 AOC2490 1920x1080 527x296mm 23.8-inch                   | 2        | 1.1%    |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                      | 2        | 1.1%    |
| ViewSonic VA1916w-6 VSCF91F 1440x900 410x256mm 19.0-inch              | 1        | 0.55%   |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch           | 1        | 0.55%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 0.55%   |
| Toshiba LCD Monitor TV 1920x1080                                      | 1        | 0.55%   |
| SKG 86 Monitor SKG8600 3840x2160 1650x928mm 74.5-inch                 | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 0.55%   |
| Samsung Electronics SMS22A450 SAM0836 1680x1050 459x296mm 21.5-inch   | 1        | 0.55%   |
| Samsung Electronics S27E370D SAM0CF3 1920x1080 598x336mm 27.0-inch    | 1        | 0.55%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 520x290mm 23.4-inch     | 1        | 0.55%   |
| Samsung Electronics S24B370 SAM08DE 1920x1080 531x299mm 24.0-inch     | 1        | 0.55%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1        | 0.55%   |
| Samsung Electronics EPSON PJ SECA60D 1920x1080                        | 1        | 0.55%   |
| Samsung Electronics C27JG5x SAM0F58 2560x1440 597x336mm 27.0-inch     | 1        | 0.55%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 0.55%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch               | 1        | 0.55%   |
| Philips PHI32PFL3404 PHLD067 1360x768 700x390mm 31.5-inch             | 1        | 0.55%   |
| Philips LCD Monitor 19SL 1280x1024                                    | 1        | 0.55%   |
| Philips 19S PHL0878 1280x1024 376x301mm 19.0-inch                     | 1        | 0.55%   |
| LG Electronics LCD Monitor W2243 1920x1080                            | 1        | 0.55%   |
| LG Electronics LCD Monitor L1752S 1280x1024                           | 1        | 0.55%   |
| LG Electronics LCD Monitor E2250 1920x1080                            | 1        | 0.55%   |
| LG Electronics LCD Monitor 2D FHD LG TV 1920x1080                     | 1        | 0.55%   |
| Lenovo LEN E2323swA LEN60B0 1920x1080 477x268mm 21.5-inch             | 1        | 0.55%   |
| JRY HDMI JRY2380 1920x1080 527x296mm 23.8-inch                        | 1        | 0.55%   |
| HIB AIO HIB0001 1920x1200 476x268mm 21.5-inch                         | 1        | 0.55%   |
| Hewlett-Packard L1730 HWP260E 1280x1024 338x270mm 17.0-inch           | 1        | 0.55%   |
| Hewlett-Packard E241i HWP3124 1920x1200 518x324mm 24.1-inch           | 1        | 0.55%   |
| HannStar JC171D HSD04B2 1280x1024 338x270mm 17.0-inch                 | 1        | 0.55%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                  | 1        | 0.55%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 1        | 0.55%   |
| Goldstar L1953S GSM4B3E 1280x1024 376x301mm 19.0-inch                 | 1        | 0.55%   |
| Goldstar L1752S GSM4432 1280x1024 338x270mm 17.0-inch                 | 1        | 0.55%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 1        | 0.55%   |
| Goldstar 22M35 GSM5A31 1920x1080 480x270mm 21.7-inch                  | 1        | 0.55%   |
| DZW SMART TV UHD DZW0030 3840x2160 708x398mm 32.0-inch                | 1        | 0.55%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1        | 0.55%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                    | 1        | 0.55%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 1        | 0.55%   |
| Dell S2318H/HX DELD0BC 1920x1080 510x290mm 23.1-inch                  | 1        | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 69       | 39.88%  |
| 3840x2160 (4K)     | 52       | 30.06%  |
| 2560x1440 (QHD)    | 23       | 13.29%  |
| 1280x1024 (SXGA)   | 13       | 7.51%   |
| 1680x1050 (WSXGA+) | 3        | 1.73%   |
| 1600x900 (HD+)     | 3        | 1.73%   |
| 1440x900 (WXGA+)   | 3        | 1.73%   |
| 1366x768 (WXGA)    | 2        | 1.16%   |
| Unknown            | 2        | 1.16%   |
| 4480x1440          | 1        | 0.58%   |
| 1920x1200 (WUXGA)  | 1        | 0.58%   |
| 1360x768           | 1        | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 40      | 43       | 24.86%  |
| 24      | 30       | 17.34%  |
| Unknown | 25       | 14.45%  |
| 23      | 19       | 10.98%  |
| 21      | 16       | 9.25%   |
| 19      | 10       | 5.78%   |
| 27      | 7        | 4.05%   |
| 17      | 6        | 3.47%   |
| 31      | 4        | 2.31%   |
| 26      | 3        | 1.73%   |
| 22      | 2        | 1.16%   |
| 74      | 1        | 0.58%   |
| 72      | 1        | 0.58%   |
| 46      | 1        | 0.58%   |
| 33      | 1        | 0.58%   |
| 32      | 1        | 0.58%   |
| 28      | 1        | 0.58%   |
| 20      | 1        | 0.58%   |
| 18      | 1        | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 58       | 34.12%  |
| 901-1000    | 43       | 25.29%  |
| Unknown     | 25       | 14.71%  |
| 401-500     | 23       | 13.53%  |
| 301-350     | 6        | 3.53%   |
| 601-700     | 5        | 2.94%   |
| 351-400     | 5        | 2.94%   |
| 701-800     | 2        | 1.18%   |
| 1501-2000   | 2        | 1.18%   |
| 1001-1500   | 1        | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 82       | 49.4%   |
| 21/9    | 43       | 25.9%   |
| Unknown | 21       | 12.65%  |
| 5/4     | 11       | 6.63%   |
| 16/10   | 8        | 4.82%   |
| 3/2     | 1        | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 59       | 34.71%  |
| 501-1000       | 44       | 25.88%  |
| Unknown        | 25       | 14.71%  |
| 151-200        | 14       | 8.24%   |
| 301-350        | 10       | 5.88%   |
| 351-500        | 7        | 4.12%   |
| 141-150        | 7        | 4.12%   |
| More than 1000 | 2        | 1.18%   |
| 251-300        | 2        | 1.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 69       | 40.35%  |
| 101-120 | 62       | 36.26%  |
| Unknown | 25       | 14.62%  |
| 121-160 | 11       | 6.43%   |
| 1-50    | 4        | 2.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 151      | 86.78%  |
| 2     | 13       | 7.47%   |
| 0     | 9        | 5.17%   |
| 3     | 1        | 0.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 142      | 58.92%  |
| Intel                      | 67       | 27.8%   |
| Qualcomm Atheros           | 11       | 4.56%   |
| Nvidia                     | 6        | 2.49%   |
| Microchip Technology       | 3        | 1.24%   |
| Ralink Technology          | 2        | 0.83%   |
| Ralink                     | 2        | 0.83%   |
| MCST                       | 2        | 0.83%   |
| ZTE WCDMA Technologies MSM | 1        | 0.41%   |
| Vimtron Electronics        | 1        | 0.41%   |
| VIA Technologies           | 1        | 0.41%   |
| TP-Link                    | 1        | 0.41%   |
| D-Link                     | 1        | 0.41%   |
| Broadcom Limited           | 1        | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86       | 32.7%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 43       | 16.35%  |
| Intel Ethernet Connection I219-LM                                 | 31       | 11.79%  |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 6.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.28%   |
| Intel Wireless 3165                                               | 6        | 2.28%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3        | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.14%   |
| Microchip MCP2221 USB-I2C/UART Combo                              | 3        | 1.14%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.14%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 1.14%   |
| Intel Ethernet Connection (13) I219-V                             | 3        | 1.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.76%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.76%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2        | 0.76%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1        | 0.38%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.38%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.38%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.38%   |
| Realtek 802.11ac NIC                                              | 1        | 0.38%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.38%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.38%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 0.38%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1        | 0.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.38%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.38%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.38%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.38%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.38%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.38%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.38%   |
| Intel Wireless-AC 9260                                            | 1        | 0.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.38%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 0.38%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.38%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.38%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.38%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1        | 0.38%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1        | 0.38%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.38%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.38%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.38%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.38%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.38%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 1        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 37.93%  |
| Realtek Semiconductor | 10       | 34.48%  |
| Qualcomm Atheros      | 3        | 10.34%  |
| Ralink Technology     | 2        | 6.9%    |
| Ralink                | 2        | 6.9%    |
| TP-Link               | 1        | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                        | 6        | 20.69%  |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 3        | 10.34%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 3        | 10.34%  |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 2        | 6.9%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 3.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 3.45%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 3.45%   |
| Realtek 802.11ac NIC                                       | 1        | 3.45%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 3.45%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 3.45%   |
| Ralink RT5392 PCIe Wireless Network Adapter                | 1        | 3.45%   |
| Ralink RT2561/RT61 rev B 802.11g                           | 1        | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 3.45%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 3.45%   |
| Intel Wireless-AC 9260                                     | 1        | 3.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 3.45%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 141      | 62.39%  |
| Intel                      | 64       | 28.32%  |
| Qualcomm Atheros           | 8        | 3.54%   |
| Nvidia                     | 6        | 2.65%   |
| MCST                       | 2        | 0.88%   |
| ZTE WCDMA Technologies MSM | 1        | 0.44%   |
| Vimtron Electronics        | 1        | 0.44%   |
| VIA Technologies           | 1        | 0.44%   |
| D-Link                     | 1        | 0.44%   |
| Broadcom Limited           | 1        | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86       | 37.23%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 43       | 18.61%  |
| Intel Ethernet Connection I219-LM                                 | 31       | 13.42%  |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 7.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.6%    |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.3%    |
| Intel Ethernet Connection (14) I219-V                             | 3        | 1.3%    |
| Intel Ethernet Connection (13) I219-V                             | 3        | 1.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.87%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.87%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.87%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1        | 0.43%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.43%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.43%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.43%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.43%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.43%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.43%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.43%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.43%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.43%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.43%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1        | 0.43%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1        | 0.43%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.43%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.43%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.43%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.43%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 1        | 0.43%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 171      | 84.24%  |
| WiFi     | 29       | 14.29%  |
| Modem    | 3        | 1.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 158      | 90.8%   |
| WiFi     | 16       | 9.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 146      | 84.88%  |
| 2     | 23       | 13.37%  |
| 13    | 1        | 0.58%   |
| 8     | 1        | 0.58%   |
| 3     | 1        | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 167      | 97.09%  |
| Yes  | 5        | 2.91%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 47.83%  |
| Cambridge Silicon Radio | 5        | 21.74%  |
| Realtek Semiconductor   | 3        | 13.04%  |
| Broadcom                | 2        | 8.7%    |
| Logitech                | 1        | 4.35%   |
| IMC Networks            | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 8        | 34.78%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 21.74%  |
| Realtek Bluetooth Radio                             | 2        | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4.35%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 4.35%   |
| Intel Bluetooth Device                              | 1        | 4.35%   |
| Intel AX210 Bluetooth                               | 1        | 4.35%   |
| Intel AX200 Bluetooth                               | 1        | 4.35%   |
| IMC Networks Bluetooth Device                       | 1        | 4.35%   |
| Broadcom Bluetooth dongle                           | 1        | 4.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 123      | 55.41%  |
| Nvidia              | 45       | 20.27%  |
| AMD                 | 40       | 18.02%  |
| C-Media Electronics | 4        | 1.8%    |
| MCST                | 2        | 0.9%    |
| Zhaoxin             | 1        | 0.45%   |
| VIA Technologies    | 1        | 0.45%   |
| JMTek               | 1        | 0.45%   |
| EasyPass Industrial | 1        | 0.45%   |
| Creative Technology | 1        | 0.45%   |
| Creative Labs       | 1        | 0.45%   |
| Apple               | 1        | 0.45%   |
| A4Tech              | 1        | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 64       | 26.56%  |
| Nvidia GP107GL High Definition Audio Controller                                                   | 18       | 7.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15       | 6.22%   |
| Intel 200 Series PCH HD Audio                                                                     | 9        | 3.73%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9        | 3.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7        | 2.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 2.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6        | 2.49%   |
| AMD FCH Azalia Controller                                                                         | 6        | 2.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 2.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 1.66%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 1.66%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 1.66%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 1.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3        | 1.24%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.24%   |
| Intel Audio device                                                                                | 3        | 1.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3        | 1.24%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3        | 1.24%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3        | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3        | 1.24%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 0.83%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2        | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2        | 0.83%   |
| MCST HD Audio                                                                                     | 2        | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2        | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 0.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 0.83%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2        | 0.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 0.83%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1        | 0.41%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                                         | 1        | 0.41%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1        | 0.41%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.41%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 0.41%   |
| Nvidia MCP73 High Definition Audio                                                                | 1        | 0.41%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 0.41%   |
| Nvidia MCP51 High Definition Audio                                                                | 1        | 0.41%   |
| Nvidia MCP51 AC97 Audio Controller                                                                | 1        | 0.41%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.41%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.41%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 0.41%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 0.41%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1        | 0.41%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1        | 0.41%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1        | 0.41%   |
| Nvidia CK804 AC'97 Audio Controller                                                               | 1        | 0.41%   |
| JMTek USB PnP Audio Device                                                                        | 1        | 0.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 0.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1        | 0.41%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 0.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 0.41%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1        | 0.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1        | 0.41%   |
| EasyPass Industrial Audioengine D1                                                                | 1        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 28       | 22.22%  |
| Unknown             | 20       | 15.87%  |
| Kingston            | 20       | 15.87%  |
| Samsung Electronics | 14       | 11.11%  |
| Micron Technology   | 14       | 11.11%  |
| SK hynix            | 5        | 3.97%   |
| Foxline             | 4        | 3.17%   |
| Apacer              | 3        | 2.38%   |
| Patriot             | 2        | 1.59%   |
| Goodram             | 2        | 1.59%   |
| Goldkey             | 2        | 1.59%   |
| A-DATA Technology   | 2        | 1.59%   |
| Unknown (0x0B7A)    | 1        | 0.79%   |
| tigo                | 1        | 0.79%   |
| Shenzhen Longsys    | 1        | 0.79%   |
| Ramaxel Technology  | 1        | 0.79%   |
| Qumo                | 1        | 0.79%   |
| Juhor               | 1        | 0.79%   |
| G.Skill             | 1        | 0.79%   |
| Elpida              | 1        | 0.79%   |
| Corsair             | 1        | 0.79%   |
| Unknown             | 1        | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s             | 13       | 9.42%   |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                         | 10       | 7.25%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s           | 4        | 2.9%    |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s           | 3        | 2.17%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2        | 1.45%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2        | 1.45%   |
| Unknown RAM Module 1024MB DIMM                                   | 2        | 1.45%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2        | 1.45%   |
| Samsung RAM M378A1K43EB2-CVF 8GB DIMM DDR4 2933MT/s              | 2        | 1.45%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s            | 2        | 1.45%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 2        | 1.45%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s           | 2        | 1.45%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1        | 0.72%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                        | 1        | 0.72%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1        | 0.72%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1        | 0.72%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 0.72%   |
| Unknown RAM Module 4096MB DIMM 333MT/s                           | 1        | 0.72%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM 533MT/s                     | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                      | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1        | 0.72%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM SDRAM 533MT/s                     | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                       | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM 400MT/s                           | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM 32MT/s                            | 1        | 0.72%   |
| Unknown (0x0B7A) RAM UDIMM PC4-2666 8G 1R 8GB DIMM DDR4 2667MT/s | 1        | 0.72%   |
| tigo RAM 4GB-2400MHZ 4GB SODIMM DDR4 2400MT/s                    | 1        | 0.72%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 1        | 0.72%   |
| SK hynix RAM HMT151R7TFR4C-H9 4096MB DIMM DDR3 1333MT/s          | 1        | 0.72%   |
| SK hynix RAM HMT151R7BFR4C-H9 4096MB DIMM DDR3 1333MT/s          | 1        | 0.72%   |
| SK hynix RAM HMA82GU6CJR8N-XN 16GB DIMM DDR4 3333MT/s            | 1        | 0.72%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1        | 0.72%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8192MB DIMM DDR4 2667MT/s          | 1        | 0.72%   |
| Shenzhen Longsys RAM FD4AS3200C8GSE 8GB SODIMM DDR4 3200MT/s     | 1        | 0.72%   |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s                        | 1        | 0.72%   |
| Samsung RAM Module 4096MB DIMM DDR4 2667MT/s                     | 1        | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1        | 0.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1        | 0.72%   |
| Samsung RAM M471A1K43BB1-CWE 8GB SODIMM DDR4 3534MT/s            | 1        | 0.72%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s              | 1        | 0.72%   |
| Samsung RAM M378A5244CB0-CRC 4096MB DIMM DDR4 3066MT/s           | 1        | 0.72%   |
| Samsung RAM M378A5143DB0-CPB 4GB DIMM DDR4 2400MT/s              | 1        | 0.72%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s             | 1        | 0.72%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s              | 1        | 0.72%   |
| Ramaxel RAM RML1040EG38D6W-533 512MB DIMM DDR2 533MT/s           | 1        | 0.72%   |
| Qumo RAM QUM4U-8G2666P19 8192MB DIMM DDR4 2667MT/s               | 1        | 0.72%   |
| Patriot RAM PSD44G240081 4GB DIMM DDR4 2400MT/s                  | 1        | 0.72%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                   | 1        | 0.72%   |
| Micron RAM Module 8192MB DIMM DDR4 2400MT/s                      | 1        | 0.72%   |
| Micron RAM Module 4096MB DIMM DDR4 2400MT/s                      | 1        | 0.72%   |
| Micron RAM 8JTF25664AZ-1G4H1 2GB DIMM DDR3 1333MT/s              | 1        | 0.72%   |
| Micron RAM 8ATF1G64HZ-2G3B2 8GB SODIMM DDR4 2400MT/s             | 1        | 0.72%   |
| Kingston RAM Module 32GB DIMM DDR4 3200MT/s                      | 1        | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 78       | 66.1%   |
| DDR3    | 21       | 17.8%   |
| Unknown | 11       | 9.32%   |
| DDR2    | 4        | 3.39%   |
| SDRAM   | 3        | 2.54%   |
| DDR     | 1        | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 103      | 87.29%  |
| SODIMM | 15       | 12.71%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 52       | 42.28%  |
| 8192  | 44       | 35.77%  |
| 1024  | 10       | 8.13%   |
| 2048  | 9        | 7.32%   |
| 16384 | 4        | 3.25%   |
| 512   | 3        | 2.44%   |
| 32768 | 1        | 0.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 39       | 31.2%   |
| 1600    | 13       | 10.4%   |
| 2667    | 11       | 8.8%    |
| 2133    | 9        | 7.2%    |
| 3200    | 8        | 6.4%    |
| 1333    | 7        | 5.6%    |
| 2933    | 5        | 4%      |
| 800     | 4        | 3.2%    |
| 667     | 4        | 3.2%    |
| Unknown | 4        | 3.2%    |
| 400     | 3        | 2.4%    |
| 533     | 2        | 1.6%    |
| 333     | 2        | 1.6%    |
| 4333    | 1        | 0.8%    |
| 3600    | 1        | 0.8%    |
| 3534    | 1        | 0.8%    |
| 3466    | 1        | 0.8%    |
| 3333    | 1        | 0.8%    |
| 3266    | 1        | 0.8%    |
| 3151    | 1        | 0.8%    |
| 3066    | 1        | 0.8%    |
| 2866    | 1        | 0.8%    |
| 2666    | 1        | 0.8%    |
| 1867    | 1        | 0.8%    |
| 1866    | 1        | 0.8%    |
| 1066    | 1        | 0.8%    |
| 32      | 1        | 0.8%    |

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
| Logitech                | 15       | 57.69%  |
| Alcor Micro             | 7        | 26.92%  |
| Z-Star Microelectronics | 1        | 3.85%   |
| Microsoft               | 1        | 3.85%   |
| Hewlett-Packard         | 1        | 3.85%   |
| Apple                   | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Logitech Webcam C270               | 9        | 34.62%  |
| Alcor Micro USB 2.0 PC Camera      | 5        | 19.23%  |
| Logitech C505 HD Webcam            | 2        | 7.69%   |
| Alcor Micro USB 2.0 PC cam         | 2        | 7.69%   |
| Z-Star Venus USB2.0 Camera         | 1        | 3.85%   |
| Microsoft LifeCam VX-700           | 1        | 3.85%   |
| Logitech Webcam C930e              | 1        | 3.85%   |
| Logitech HD Webcam C525            | 1        | 3.85%   |
| Logitech HD Pro Webcam C920        | 1        | 3.85%   |
| Logitech B525 HD Webcam            | 1        | 3.85%   |
| HP Webcam HD 2300                  | 1        | 3.85%   |
| Apple iSight in LED Cinema Display | 1        | 3.85%   |

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
| 0     | 159      | 90.86%  |
| 1     | 13       | 7.43%   |
| 2     | 2        | 1.14%   |
| 5     | 1        | 0.57%   |

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

