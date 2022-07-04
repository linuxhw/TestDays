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

Total: 256

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Kometa P10         | 81       | 46.02%  |
| ALT Linux 9.1      | 33       | 18.75%  |
| ALT Linux 10.0     | 17       | 9.66%   |
| ALT Linux 9.0      | 15       | 8.52%   |
| ALT Linux 9.2      | 7        | 3.98%   |
| MOS 10             | 4        | 2.27%   |
| ALT Linux 10.1     | 3        | 1.7%    |
| ALT Linux P9       | 2        | 1.14%   |
| ALT Linux P8       | 2        | 1.14%   |
| ALT Linux 8.4      | 2        | 1.14%   |
| ALT Linux 8.2      | 2        | 1.14%   |
| ALT Linux 7.0.5    | 2        | 1.14%   |
| ALT Linux P10      | 1        | 0.57%   |
| ALT Linux 8.2.0    | 1        | 0.57%   |
| ALT Linux 20201124 | 1        | 0.57%   |
| ALT Linux 20190303 | 1        | 0.57%   |
| ALT Linux 10.0.910 | 1        | 0.57%   |
| ALT Linux 10.0.900 | 1        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ALT Linux | 168      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.109-std-def-alt1       | 51       | 28.18%  |
| 5.10.102-std-def-alt1       | 27       | 14.92%  |
| 5.4.68-std-def-alt1.1       | 7        | 3.87%   |
| 5.10.82-std-def-alt1        | 6        | 3.31%   |
| 5.4.51-std-def-alt1         | 5        | 2.76%   |
| 5.15.32-un-def-alt1         | 5        | 2.76%   |
| 5.4.41-std-def-alt1         | 3        | 1.66%   |
| 5.15.34-un-def-alt1         | 3        | 1.66%   |
| 5.10.93-std-def-alt1        | 3        | 1.66%   |
| 5.10.35-un-def-alt1         | 3        | 1.66%   |
| 5.10.32-un-def-alt1         | 3        | 1.66%   |
| 4.19.79-std-def-alt1        | 3        | 1.66%   |
| 5.7.19-un-def-alt1          | 2        | 1.1%    |
| 5.4.85-std-def-alt1         | 2        | 1.1%    |
| 5.4.62-std-def-alt1         | 2        | 1.1%    |
| 5.4.28-std-def-alt1         | 2        | 1.1%    |
| 5.4.181-std-def-alt1        | 2        | 1.1%    |
| 5.4.127-std-def-alt1        | 2        | 1.1%    |
| 5.2.10-un-def-alt1          | 2        | 1.1%    |
| 5.15.15-un-def-alt1         | 2        | 1.1%    |
| 5.15.14-un-def-alt1         | 2        | 1.1%    |
| 5.10.88-std-def-alt1        | 2        | 1.1%    |
| 5.10.83-std-def-alt0.c9f.2  | 2        | 1.1%    |
| 5.10.72-std-def-alt1        | 2        | 1.1%    |
| 5.10.17-un-def-alt1         | 2        | 1.1%    |
| 5.9.8-un-def-alt1           | 1        | 0.55%   |
| 5.7.14-un-def-alt1          | 1        | 0.55%   |
| 5.4.94-std-def-alt1         | 1        | 0.55%   |
| 5.4.92-std-def-alt1         | 1        | 0.55%   |
| 5.4.91-elbrus-def-alt2.12.1 | 1        | 0.55%   |
| 5.4.81-std-def-alt1         | 1        | 0.55%   |
| 5.4.58-elbrus-def-alt1.7.0  | 1        | 0.55%   |
| 5.4.35-std-def-alt1         | 1        | 0.55%   |
| 5.4.134-std-def-alt1        | 1        | 0.55%   |
| 5.4.123-std-def-alt1        | 1        | 0.55%   |
| 5.4.104-std-def-alt1        | 1        | 0.55%   |
| 5.2.11-un-def-alt1          | 1        | 0.55%   |
| 5.15.41-un-def-alt1         | 1        | 0.55%   |
| 5.15.37-un-def-alt1         | 1        | 0.55%   |
| 5.14.21-un-def-alt3         | 1        | 0.55%   |
| 5.14.21-un-def-alt1         | 1        | 0.55%   |
| 5.13.13-un-def-alt1         | 1        | 0.55%   |
| 5.12.19-un-def-alt2         | 1        | 0.55%   |
| 5.10.54-un-def-alt1.1       | 1        | 0.55%   |
| 5.10.54-std-def-alt2        | 1        | 0.55%   |
| 5.10.52-un-def-alt1         | 1        | 0.55%   |
| 5.10.45-un-def-alt1         | 1        | 0.55%   |
| 5.10.42-un-def-alt1         | 1        | 0.55%   |
| 5.10.117-std-def-alt1       | 1        | 0.55%   |
| 5.10.113-std-def-alt1       | 1        | 0.55%   |
| 5.10.111-std-def-alt1       | 1        | 0.55%   |
| 5.10.110-std-def-alt1       | 1        | 0.55%   |
| 4.9.188-std-def-alt0.M80P.1 | 1        | 0.55%   |
| 4.9.133-std-def-alt0.M80P.1 | 1        | 0.55%   |
| 4.9.128-std-def-alt0.M80P.1 | 1        | 0.55%   |
| 4.20.14-un-def-alt1         | 1        | 0.55%   |
| 4.19.67-std-def-alt1        | 1        | 0.55%   |
| 4.19.182-old-def-alt1       | 1        | 0.55%   |
| 4.19.128-old-def-alt2       | 1        | 0.55%   |
| 4.14.78-un-def-alt0.M80P.1  | 1        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.109 | 51       | 28.18%  |
| 5.10.102 | 27       | 14.92%  |
| 5.4.68   | 7        | 3.87%   |
| 5.10.82  | 6        | 3.31%   |
| 5.4.51   | 5        | 2.76%   |
| 5.15.32  | 5        | 2.76%   |
| 5.4.41   | 3        | 1.66%   |
| 5.15.34  | 3        | 1.66%   |
| 5.10.93  | 3        | 1.66%   |
| 5.10.35  | 3        | 1.66%   |
| 5.10.32  | 3        | 1.66%   |
| 4.19.79  | 3        | 1.66%   |
| 5.7.19   | 2        | 1.1%    |
| 5.4.85   | 2        | 1.1%    |
| 5.4.62   | 2        | 1.1%    |
| 5.4.28   | 2        | 1.1%    |
| 5.4.181  | 2        | 1.1%    |
| 5.4.127  | 2        | 1.1%    |
| 5.2.10   | 2        | 1.1%    |
| 5.15.15  | 2        | 1.1%    |
| 5.15.14  | 2        | 1.1%    |
| 5.14.21  | 2        | 1.1%    |
| 5.10.88  | 2        | 1.1%    |
| 5.10.83  | 2        | 1.1%    |
| 5.10.72  | 2        | 1.1%    |
| 5.10.54  | 2        | 1.1%    |
| 5.10.17  | 2        | 1.1%    |
| 5.9.8    | 1        | 0.55%   |
| 5.7.14   | 1        | 0.55%   |
| 5.4.94   | 1        | 0.55%   |
| 5.4.92   | 1        | 0.55%   |
| 5.4.91   | 1        | 0.55%   |
| 5.4.81   | 1        | 0.55%   |
| 5.4.58   | 1        | 0.55%   |
| 5.4.35   | 1        | 0.55%   |
| 5.4.134  | 1        | 0.55%   |
| 5.4.123  | 1        | 0.55%   |
| 5.4.104  | 1        | 0.55%   |
| 5.2.11   | 1        | 0.55%   |
| 5.15.41  | 1        | 0.55%   |
| 5.15.37  | 1        | 0.55%   |
| 5.13.13  | 1        | 0.55%   |
| 5.12.19  | 1        | 0.55%   |
| 5.10.52  | 1        | 0.55%   |
| 5.10.45  | 1        | 0.55%   |
| 5.10.42  | 1        | 0.55%   |
| 5.10.117 | 1        | 0.55%   |
| 5.10.113 | 1        | 0.55%   |
| 5.10.111 | 1        | 0.55%   |
| 5.10.110 | 1        | 0.55%   |
| 4.9.188  | 1        | 0.55%   |
| 4.9.133  | 1        | 0.55%   |
| 4.9.128  | 1        | 0.55%   |
| 4.20.14  | 1        | 0.55%   |
| 4.19.67  | 1        | 0.55%   |
| 4.19.182 | 1        | 0.55%   |
| 4.19.128 | 1        | 0.55%   |
| 4.14.78  | 1        | 0.55%   |
| 4.14.71  | 1        | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 107      | 61.14%  |
| 5.4     | 34       | 19.43%  |
| 5.15    | 11       | 6.29%   |
| 4.19    | 6        | 3.43%   |
| 5.7     | 3        | 1.71%   |
| 5.2     | 3        | 1.71%   |
| 4.9     | 3        | 1.71%   |
| 5.14    | 2        | 1.14%   |
| 4.14    | 2        | 1.14%   |
| 5.9     | 1        | 0.57%   |
| 5.13    | 1        | 0.57%   |
| 5.12    | 1        | 0.57%   |
| 4.20    | 1        | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 162      | 96.43%  |
| i686   | 4        | 2.38%   |
| e2k    | 2        | 1.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 122      | 71.76%  |
| Unknown  | 22       | 12.94%  |
| XFCE     | 21       | 12.35%  |
| MATE     | 2        | 1.18%   |
| KDE      | 2        | 1.18%   |
| Cinnamon | 1        | 0.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 163      | 97.02%  |
| Unknown | 5        | 2.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 111      | 65.29%  |
| TDM     | 28       | 16.47%  |
| LightDM | 19       | 11.18%  |
| Unknown | 12       | 7.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 137      | 79.65%  |
| Unknown | 33       | 19.19%  |
| en_US   | 1        | 0.58%   |
| el_GR   | 1        | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 108      | 63.91%  |
| BIOS | 61       | 36.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 158      | 93.49%  |
| Overlay | 9        | 5.33%   |
| Btrfs   | 2        | 1.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 119      | 70.41%  |
| MBR     | 39       | 23.08%  |
| Unknown | 11       | 6.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 148      | 88.1%   |
| Yes       | 20       | 11.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 125      | 73.1%   |
| Yes       | 46       | 26.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 44       | 26.19%  |
| ASUSTek Computer    | 31       | 18.45%  |
| Gigabyte Technology | 23       | 13.69%  |
| ASRock              | 18       | 10.71%  |
| Acer                | 13       | 7.74%   |
| Unknown             | 9        | 5.36%   |
| MSI                 | 6        | 3.57%   |
| MAINBRD             | 3        | 1.79%   |
| iRU                 | 3        | 1.79%   |
| 3Logic Group        | 3        | 1.79%   |
| Hewlett-Packard     | 2        | 1.19%   |
| DEPO Computers      | 2        | 1.19%   |
| VIA Technologies    | 1        | 0.6%    |
| SYS                 | 1        | 0.6%    |
| Supermicro          | 1        | 0.6%    |
| Lenovo              | 1        | 0.6%    |
| Kraftway            | 1        | 0.6%    |
| Foxconn             | 1        | 0.6%    |
| EPoX Computer       | 1        | 0.6%    |
| ECS                 | 1        | 0.6%    |
| Dell                | 1        | 0.6%    |
| Biostar             | 1        | 0.6%    |
| Aquarius            | 1        | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Intel SKYBAY                                       | 43       | 25.6%   |
| ASUS PRIME B450-PLUS                               | 12       | 7.14%   |
| Acer Veriton X2640G                                | 10       | 5.95%   |
| Unknown                                            | 9        | 5.36%   |
| Gigabyte H110M-S2H                                 | 4        | 2.38%   |
| MAINBRD OPS62A-SHA                                 | 3        | 1.79%   |
| 3Logic Group Graviton                              | 3        | 1.79%   |
| iRU 515                                            | 2        | 1.19%   |
| Gigabyte H77M-D3H                                  | 2        | 1.19%   |
| ASUS H110M-R                                       | 2        | 1.19%   |
| Acer Veriton ES2710G                               | 2        | 1.19%   |
| VIA P4M266A-8235                                   | 1        | 0.6%    |
| SYS RAY B101                                       | 1        | 0.6%    |
| Supermicro SYS-1019D-14CN-FHN13TP                  | 1        | 0.6%    |
| MSI MS-7A38                                        | 1        | 0.6%    |
| MSI MS-7996                                        | 1        | 0.6%    |
| MSI MS-7895                                        | 1        | 0.6%    |
| MSI MS-7758                                        | 1        | 0.6%    |
| MSI MS-7721                                        | 1        | 0.6%    |
| MSI MPG B560 Trident A (MS-B926)                   | 1        | 0.6%    |
| Lenovo ThinkCentre M73 10B1S15000                  | 1        | 0.6%    |
| Kraftway KWH310                                    | 1        | 0.6%    |
| iRU IRUB365M                                       | 1        | 0.6%    |
| Intel B75                                          | 1        | 0.6%    |
| HP Compaq dc7600 Convertible Minitower             | 1        | 0.6%    |
| HP 290 G4 Microtower PC                            | 1        | 0.6%    |
| Gigabyte X79-UD3                                   | 1        | 0.6%    |
| Gigabyte P35-S3G                                   | 1        | 0.6%    |
| Gigabyte J1800N-D2H                                | 1        | 0.6%    |
| Gigabyte H510M S2H                                 | 1        | 0.6%    |
| Gigabyte H310N 2.0                                 | 1        | 0.6%    |
| Gigabyte H110M-S2V                                 | 1        | 0.6%    |
| Gigabyte GA-MA69VM-S2                              | 1        | 0.6%    |
| Gigabyte GA-A75M-D2H                               | 1        | 0.6%    |
| Gigabyte GA-890XA-UD3                              | 1        | 0.6%    |
| Gigabyte G41MT-D3                                  | 1        | 0.6%    |
| Gigabyte G31M-ES2L                                 | 1        | 0.6%    |
| Gigabyte EP45-UD3LR                                | 1        | 0.6%    |
| Gigabyte EP35C-DS3R                                | 1        | 0.6%    |
| Gigabyte B550 GAMING X                             | 1        | 0.6%    |
| Gigabyte B450M S2H                                 | 1        | 0.6%    |
| Gigabyte B450 AORUS M                              | 1        | 0.6%    |
| Gigabyte A320M-S2H                                 | 1        | 0.6%    |
| Foxconn Pro 3400 Series MT                         | 1        | 0.6%    |
| EPoX GeForce6100 + nForce410 DDR: 8GF6100-M Series | 1        | 0.6%    |
| ECS T420                                           | 1        | 0.6%    |
| DEPO Computers DPH410S                             | 1        | 0.6%    |
| DEPO Computers DPA320S                             | 1        | 0.6%    |
| Dell OptiPlex 755                                  | 1        | 0.6%    |
| Biostar NF720D A2G+                                | 1        | 0.6%    |
| ASUS Z8NR-D12                                      | 1        | 0.6%    |
| ASUS PRO H410T                                     | 1        | 0.6%    |
| ASUS PRIME Z390-A                                  | 1        | 0.6%    |
| ASUS PRIME H310M-R R2.0                            | 1        | 0.6%    |
| ASUS PRIME B550-PLUS                               | 1        | 0.6%    |
| ASUS PRIME B250-PRO                                | 1        | 0.6%    |
| ASUS PRIME A320M-K                                 | 1        | 0.6%    |
| ASUS P5Q                                           | 1        | 0.6%    |
| ASUS P5G41T-M LX2/GB/LPT                           | 1        | 0.6%    |
| ASUS P5B-MX                                        | 1        | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel SKYBAY                      | 43       | 25.6%   |
| ASUS PRIME                        | 17       | 10.12%  |
| Acer Veriton                      | 12       | 7.14%   |
| Unknown                           | 9        | 5.36%   |
| Gigabyte H110M-S2H                | 4        | 2.38%   |
| MAINBRD OPS62A-SHA                | 3        | 1.79%   |
| 3Logic Group Graviton             | 3        | 1.79%   |
| iRU 515                           | 2        | 1.19%   |
| Gigabyte H77M-D3H                 | 2        | 1.19%   |
| ASUS H110M-R                      | 2        | 1.19%   |
| VIA P4M266A-8235                  | 1        | 0.6%    |
| SYS RAY                           | 1        | 0.6%    |
| Supermicro SYS-1019D-14CN-FHN13TP | 1        | 0.6%    |
| MSI MS-7A38                       | 1        | 0.6%    |
| MSI MS-7996                       | 1        | 0.6%    |
| MSI MS-7895                       | 1        | 0.6%    |
| MSI MS-7758                       | 1        | 0.6%    |
| MSI MS-7721                       | 1        | 0.6%    |
| MSI MPG                           | 1        | 0.6%    |
| Lenovo ThinkCentre                | 1        | 0.6%    |
| Kraftway KWH310                   | 1        | 0.6%    |
| iRU IRUB365M                      | 1        | 0.6%    |
| Intel B75                         | 1        | 0.6%    |
| HP Compaq                         | 1        | 0.6%    |
| HP 290                            | 1        | 0.6%    |
| Gigabyte X79-UD3                  | 1        | 0.6%    |
| Gigabyte P35-S3G                  | 1        | 0.6%    |
| Gigabyte J1800N-D2H               | 1        | 0.6%    |
| Gigabyte H510M                    | 1        | 0.6%    |
| Gigabyte H310N                    | 1        | 0.6%    |
| Gigabyte H110M-S2V                | 1        | 0.6%    |
| Gigabyte GA-MA69VM-S2             | 1        | 0.6%    |
| Gigabyte GA-A75M-D2H              | 1        | 0.6%    |
| Gigabyte GA-890XA-UD3             | 1        | 0.6%    |
| Gigabyte G41MT-D3                 | 1        | 0.6%    |
| Gigabyte G31M-ES2L                | 1        | 0.6%    |
| Gigabyte EP45-UD3LR               | 1        | 0.6%    |
| Gigabyte EP35C-DS3R               | 1        | 0.6%    |
| Gigabyte B550                     | 1        | 0.6%    |
| Gigabyte B450M                    | 1        | 0.6%    |
| Gigabyte B450                     | 1        | 0.6%    |
| Gigabyte A320M-S2H                | 1        | 0.6%    |
| Foxconn Pro                       | 1        | 0.6%    |
| EPoX GeForce6100                  | 1        | 0.6%    |
| ECS T420                          | 1        | 0.6%    |
| DEPO Computers DPH410S            | 1        | 0.6%    |
| DEPO Computers DPA320S            | 1        | 0.6%    |
| Dell OptiPlex                     | 1        | 0.6%    |
| Biostar NF720D                    | 1        | 0.6%    |
| ASUS Z8NR-D12                     | 1        | 0.6%    |
| ASUS PRO                          | 1        | 0.6%    |
| ASUS P5Q                          | 1        | 0.6%    |
| ASUS P5G41T-M                     | 1        | 0.6%    |
| ASUS P5B-MX                       | 1        | 0.6%    |
| ASUS P5B                          | 1        | 0.6%    |
| ASUS M5A99X                       | 1        | 0.6%    |
| ASUS M4A78-EM                     | 1        | 0.6%    |
| ASUS All                          | 1        | 0.6%    |
| ASUS A8N-VM                       | 1        | 0.6%    |
| ASUS A8N-E                        | 1        | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 42       | 25%     |
| 2017    | 32       | 19.05%  |
| 2016    | 20       | 11.9%   |
| 2020    | 12       | 7.14%   |
| 2021    | 8        | 4.76%   |
| 2015    | 6        | 3.57%   |
| 2012    | 6        | 3.57%   |
| 2022    | 5        | 2.98%   |
| 2008    | 5        | 2.98%   |
| 2019    | 4        | 2.38%   |
| 2014    | 4        | 2.38%   |
| 2011    | 4        | 2.38%   |
| 2009    | 4        | 2.38%   |
| 2010    | 3        | 1.79%   |
| 2007    | 3        | 1.79%   |
| 2005    | 3        | 1.79%   |
| 2013    | 2        | 1.19%   |
| 2006    | 2        | 1.19%   |
| Unknown | 2        | 1.19%   |
| 2003    | 1        | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 168      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 160      | 95.24%  |
| Enabled  | 8        | 4.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 168      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 76       | 45.24%  |
| 4.01-8.0    | 40       | 23.81%  |
| 3.01-4.0    | 25       | 14.88%  |
| 16.01-24.0  | 12       | 7.14%   |
| 1.01-2.0    | 5        | 2.98%   |
| 32.01-64.0  | 3        | 1.79%   |
| 64.01-256.0 | 3        | 1.79%   |
| 2.01-3.0    | 2        | 1.19%   |
| 0.51-1.0    | 2        | 1.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 89       | 50.86%  |
| 0.51-1.0  | 29       | 16.57%  |
| 2.01-3.0  | 24       | 13.71%  |
| 4.01-8.0  | 15       | 8.57%   |
| 3.01-4.0  | 12       | 6.86%   |
| 8.01-16.0 | 3        | 1.71%   |
| 0.01-0.5  | 3        | 1.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 119      | 69.59%  |
| 2      | 37       | 21.64%  |
| 3      | 10       | 5.85%   |
| 4      | 3        | 1.75%   |
| 5      | 1        | 0.58%   |
| 0      | 1        | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 63.69%  |
| Yes       | 61       | 36.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 167      | 99.4%   |
| No        | 1        | 0.6%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 140      | 83.33%  |
| Yes       | 28       | 16.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 148      | 87.57%  |
| Yes       | 21       | 12.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Russia     | 162      | 96.43%  |
| Greece     | 2        | 1.19%   |
| Ukraine    | 1        | 0.6%    |
| Kazakhstan | 1        | 0.6%    |
| China      | 1        | 0.6%    |
| Belarus    | 1        | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Moscow                   | 114      | 65.9%   |
| St Petersburg            | 7        | 4.05%   |
| Samara                   | 5        | 2.89%   |
| Irkutsk                  | 3        | 1.73%   |
| Barnaul                  | 3        | 1.73%   |
| Saratov                  | 2        | 1.16%   |
| Kaliningrad              | 2        | 1.16%   |
| Zelenodolsk              | 1        | 0.58%   |
| Yekaterinburg            | 1        | 0.58%   |
| Vologda                  | 1        | 0.58%   |
| Vladivostok              | 1        | 0.58%   |
| Verkhnyaya Pyshma        | 1        | 0.58%   |
| Vergina                  | 1        | 0.58%   |
| Valuyki                  | 1        | 0.58%   |
| Tula                     | 1        | 0.58%   |
| Thessaloniki             | 1        | 0.58%   |
| Taraz                    | 1        | 0.58%   |
| Tambov                   | 1        | 0.58%   |
| Shenzhen                 | 1        | 0.58%   |
| Sevastopol               | 1        | 0.58%   |
| Rostov-on-Don            | 1        | 0.58%   |
| Pushchino                | 1        | 0.58%   |
| Polyarnyy                | 1        | 0.58%   |
| Petropavlovsk-Kamchatsky | 1        | 0.58%   |
| Perm                     | 1        | 0.58%   |
| Obninsk                  | 1        | 0.58%   |
| Nizhniy Novgorod         | 1        | 0.58%   |
| Murmansk                 | 1        | 0.58%   |
| Monchegorsk              | 1        | 0.58%   |
| Mogilev                  | 1        | 0.58%   |
| Lipetsk                  | 1        | 0.58%   |
| Kyzyl                    | 1        | 0.58%   |
| Krasnoyarsk              | 1        | 0.58%   |
| Krasnokamensk            | 1        | 0.58%   |
| Krasnogorsk              | 1        | 0.58%   |
| Krasnodar                | 1        | 0.58%   |
| Kostroma                 | 1        | 0.58%   |
| Korolyov                 | 1        | 0.58%   |
| Kirovsk                  | 1        | 0.58%   |
| Kirov                    | 1        | 0.58%   |
| Ivanovo                  | 1        | 0.58%   |
| Belgorod                 | 1        | 0.58%   |
| Balashikha               | 1        | 0.58%   |
| Almaty                   | 1        | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 44       | 63     | 21.15%  |
| Seagate             | 26       | 41     | 12.5%   |
| AXIOMTEK            | 26       | 26     | 12.5%   |
| Samsung Electronics | 25       | 30     | 12.02%  |
| Toshiba             | 24       | 39     | 11.54%  |
| Kingston            | 16       | 18     | 7.69%   |
| China               | 8        | 8      | 3.85%   |
| Hitachi             | 5        | 6      | 2.4%    |
| A-DATA Technology   | 5        | 5      | 2.4%    |
| Apacer              | 3        | 5      | 1.44%   |
| Phison              | 2        | 2      | 0.96%   |
| Intel               | 2        | 6      | 0.96%   |
| DEPO                | 2        | 2      | 0.96%   |
| Crucial             | 2        | 2      | 0.96%   |
| XPG                 | 1        | 1      | 0.48%   |
| TMI                 | 1        | 1      | 0.48%   |
| SPCC                | 1        | 1      | 0.48%   |
| SP-8                | 1        | 1      | 0.48%   |
| Smartbuy            | 1        | 1      | 0.48%   |
| SINTECHI            | 1        | 1      | 0.48%   |
| SanDisk             | 1        | 1      | 0.48%   |
| Plextor             | 1        | 1      | 0.48%   |
| Patriot             | 1        | 1      | 0.48%   |
| OCZ                 | 1        | 1      | 0.48%   |
| Micron Technology   | 1        | 1      | 0.48%   |
| LITEON              | 1        | 1      | 0.48%   |
| KingSpec            | 1        | 1      | 0.48%   |
| JMicron Technology  | 1        | 1      | 0.48%   |
| HEORIADY            | 1        | 1      | 0.48%   |
| Gigabyte Technology | 1        | 1      | 0.48%   |
| Foxline             | 1        | 1      | 0.48%   |
| AMD                 | 1        | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD   | 26       | 11.82%  |
| Samsung MZVLW128HEGR-00000 128GB       | 17       | 7.73%   |
| Toshiba HDWD120 2TB                    | 13       | 5.91%   |
| WDC WD5000AZLX-21K2TA0 500GB           | 10       | 4.55%   |
| Toshiba HDWD110 1TB                    | 5        | 2.27%   |
| Kingston RBUSC180S37256GJ 256GB SSD    | 4        | 1.82%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 3        | 1.36%   |
| Kingston SV300S37A120G 120GB SSD       | 3        | 1.36%   |
| Kingston SA400S37120G 120GB SSD        | 3        | 1.36%   |
| WDC WD10PURZ-85U8XY0 1TB               | 2        | 0.91%   |
| Toshiba DT01ACA100 1TB                 | 2        | 0.91%   |
| Seagate ST500LM030-2E717D 500GB        | 2        | 0.91%   |
| Seagate ST500DM002-1BC142 500GB        | 2        | 0.91%   |
| Seagate ST380815AS 80GB                | 2        | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB         | 2        | 0.91%   |
| Samsung SSD 860 EVO 500GB              | 2        | 0.91%   |
| Samsung SSD 860 EVO 250GB              | 2        | 0.91%   |
| Phison M.2 128GB SSO128GTLCG-SBC-2 SSD | 2        | 0.91%   |
| Kingston SA400S37240G 240GB SSD        | 2        | 0.91%   |
| Hitachi HDS721025CLA382 165GB          | 2        | 0.91%   |
| DEPO SM3DT-120 120GB SSD               | 2        | 0.91%   |
| China SSD 128GB                        | 2        | 0.91%   |
| XPG GAMMIX S5 1TB                      | 1        | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1        | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1        | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1        | 0.45%   |
| WDC WD800AAJS-00WAA0 80GB              | 1        | 0.45%   |
| WDC WD7501AALS-00E3A0 752GB            | 1        | 0.45%   |
| WDC WD5003ABYZ-011FA0 500GB            | 1        | 0.45%   |
| WDC WD5001ABYS-01YNA0 500GB            | 1        | 0.45%   |
| WDC WD5001AALS-00E3A0 500GB            | 1        | 0.45%   |
| WDC WD5000HHTZ-04N21V0 500GB           | 1        | 0.45%   |
| WDC WD5000AZRZ-00HTKB0 500GB           | 1        | 0.45%   |
| WDC WD5000AZLX-00JKKA0 500GB           | 1        | 0.45%   |
| WDC WD3200BPVT-00HXZT3 320GB           | 1        | 0.45%   |
| WDC WD3200BEVT-80A0RT0 320GB           | 1        | 0.45%   |
| WDC WD3200AAKS-00V1A0 320GB            | 1        | 0.45%   |
| WDC WD3200AAKS-00UU3A0 320GB           | 1        | 0.45%   |
| WDC WD3200AAKS-00G3A0 320GB            | 1        | 0.45%   |
| WDC WD30EZRX-00DC0B0 3TB               | 1        | 0.45%   |
| WDC WD2500KS-00MJB0 250GB              | 1        | 0.45%   |
| WDC WD2500BEVT-60ZCT1 250GB            | 1        | 0.45%   |
| WDC WD20EZBX-00AYRA0 2TB               | 1        | 0.45%   |
| WDC WD20EURX-63T0FY0 2TB               | 1        | 0.45%   |
| WDC WD20EARX-008FB0 2TB                | 1        | 0.45%   |
| WDC WD2005FBYZ-01YCBB3 2TB             | 1        | 0.45%   |
| WDC WD2000FYYZ-01UL1B1 2TB             | 1        | 0.45%   |
| WDC WD1600AAJS-61M0A0 160GB            | 1        | 0.45%   |
| WDC WD10SPSX-00A6WT0 1TB               | 1        | 0.45%   |
| WDC WD10EZRZ-00HTKB0 1TB               | 1        | 0.45%   |
| WDC WD10EZEX-60ZF5A0 1TB               | 1        | 0.45%   |
| WDC WD10EZEX-21WN4A0 1TB               | 1        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB               | 1        | 0.45%   |
| WDC WD10EZEX-08M2NA0 1TB               | 1        | 0.45%   |
| WDC WD1004FBYZ-01YCBB1 1TB             | 1        | 0.45%   |
| WDC WD1003FZEX-00MK2A0 1TB             | 1        | 0.45%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB     | 1        | 0.45%   |
| Toshiba HDWK105 500GB                  | 1        | 0.45%   |
| Toshiba DT01ACA300 3TB                 | 1        | 0.45%   |
| Toshiba DT01ACA200 2TB                 | 1        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| WDC                | 38       | 56     | 40.86%  |
| Toshiba            | 24       | 39     | 25.81%  |
| Seagate            | 24       | 36     | 25.81%  |
| Hitachi            | 5        | 6      | 5.38%   |
| SINTECHI           | 1        | 1      | 1.08%   |
| JMicron Technology | 1        | 1      | 1.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| AXIOMTEK            | 26       | 26     | 28.89%  |
| Kingston            | 15       | 16     | 16.67%  |
| China               | 8        | 8      | 8.89%   |
| WDC                 | 6        | 6      | 6.67%   |
| Samsung Electronics | 6        | 8      | 6.67%   |
| A-DATA Technology   | 4        | 4      | 4.44%   |
| Apacer              | 3        | 5      | 3.33%   |
| Seagate             | 2        | 5      | 2.22%   |
| Phison              | 2        | 2      | 2.22%   |
| DEPO                | 2        | 2      | 2.22%   |
| Crucial             | 2        | 2      | 2.22%   |
| TMI                 | 1        | 1      | 1.11%   |
| SP-8                | 1        | 1      | 1.11%   |
| Smartbuy            | 1        | 1      | 1.11%   |
| SanDisk             | 1        | 1      | 1.11%   |
| Plextor             | 1        | 1      | 1.11%   |
| Patriot             | 1        | 1      | 1.11%   |
| OCZ                 | 1        | 1      | 1.11%   |
| LITEON              | 1        | 1      | 1.11%   |
| KingSpec            | 1        | 1      | 1.11%   |
| Intel               | 1        | 4      | 1.11%   |
| HEORIADY            | 1        | 1      | 1.11%   |
| Gigabyte Technology | 1        | 1      | 1.11%   |
| Foxline             | 1        | 1      | 1.11%   |
| AMD                 | 1        | 1      | 1.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 86       | 101    | 44.1%   |
| HDD  | 82       | 139    | 42.05%  |
| NVMe | 27       | 31     | 13.85%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 146      | 239    | 83.91%  |
| NVMe | 27       | 31     | 15.52%  |
| SAS  | 1        | 1      | 0.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 117      | 149    | 68.02%  |
| 0.51-1.0   | 30       | 46     | 17.44%  |
| 1.01-2.0   | 23       | 42     | 13.37%  |
| 2.01-3.0   | 2        | 3      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 84       | 49.12%  |
| 251-500        | 26       | 15.2%   |
| 1001-2000      | 23       | 13.45%  |
| 501-1000       | 11       | 6.43%   |
| 21-50          | 8        | 4.68%   |
| 51-100         | 7        | 4.09%   |
| 1-20           | 5        | 2.92%   |
| More than 3000 | 4        | 2.34%   |
| 2001-3000      | 2        | 1.17%   |
| Unknown        | 1        | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 107      | 61.49%  |
| 21-50          | 22       | 12.64%  |
| 101-250        | 14       | 8.05%   |
| 51-100         | 13       | 7.47%   |
| 501-1000       | 8        | 4.6%    |
| 251-500        | 5        | 2.87%   |
| 1001-2000      | 2        | 1.15%   |
| More than 3000 | 1        | 0.57%   |
| 2001-3000      | 1        | 0.57%   |
| Unknown        | 1        | 0.57%   |

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
| Works    | 144      | 211    | 79.56%  |
| Detected | 20       | 38     | 11.05%  |
| Malfunc  | 16       | 21     | 8.84%   |
| Failed   | 1        | 1      | 0.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 122      | 59.8%   |
| AMD                         | 36       | 17.65%  |
| Samsung Electronics         | 19       | 9.31%   |
| Nvidia                      | 7        | 3.43%   |
| JMicron Technology          | 5        | 2.45%   |
| Realtek Semiconductor       | 2        | 0.98%   |
| MCST                        | 2        | 0.98%   |
| Marvell Technology Group    | 2        | 0.98%   |
| Kingston Technology Company | 2        | 0.98%   |
| ASMedia Technology          | 2        | 0.98%   |
| VIA Technologies            | 1        | 0.49%   |
| Silicon Motion              | 1        | 0.49%   |
| SanDisk                     | 1        | 0.49%   |
| Micron Technology           | 1        | 0.49%   |
| LSI Logic / Symbios Logic   | 1        | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 64       | 25.6%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 29       | 11.6%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 17       | 6.8%    |
| AMD 400 Series Chipset SATA Controller                                           | 16       | 6.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 8        | 3.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6        | 2.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 5        | 2%      |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5        | 2%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 5        | 2%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4        | 1.6%    |
| AMD FCH SATA Controller D                                                        | 4        | 1.6%    |
| JMicron JMB363 SATA/IDE Controller                                               | 3        | 1.2%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 3        | 1.2%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 3        | 1.2%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 3        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3        | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                           | 3        | 1.2%    |
| Realtek Realtek Non-Volatile memory controller                                   | 2        | 0.8%    |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2        | 0.8%    |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                     | 2        | 0.8%    |
| Nvidia MCP51 Serial ATA Controller                                               | 2        | 0.8%    |
| Nvidia MCP51 IDE                                                                 | 2        | 0.8%    |
| MCST SATA                                                                        | 2        | 0.8%    |
| MCST IDE controller                                                              | 2        | 0.8%    |
| JMicron JMB368 IDE controller                                                    | 2        | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2        | 0.8%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2        | 0.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2        | 0.8%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 2        | 0.8%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 2        | 0.8%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 2        | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 0.8%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1        | 0.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.4%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1        | 0.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1        | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1        | 0.4%    |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 1        | 0.4%    |
| Nvidia MCP73 IDE Controller                                                      | 1        | 0.4%    |
| Nvidia MCP61 SATA Controller                                                     | 1        | 0.4%    |
| Nvidia CK804 Serial ATA Controller                                               | 1        | 0.4%    |
| Nvidia CK804 IDE                                                                 | 1        | 0.4%    |
| Micron Non-Volatile memory controller                                            | 1        | 0.4%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1        | 0.4%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 1        | 0.4%    |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                          | 1        | 0.4%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1        | 0.4%    |
| Kingston Company A2000 NVMe SSD                                                  | 1        | 0.4%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1        | 0.4%    |
| Intel SATA Controller [RAID mode]                                                | 1        | 0.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 0.4%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1        | 0.4%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1        | 0.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 0.4%    |
| Intel 82Q35 Express PT IDER Controller                                           | 1        | 0.4%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 0.4%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 1        | 0.4%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1        | 0.4%    |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                          | 1        | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 146      | 71.22%  |
| IDE  | 30       | 14.63%  |
| NVMe | 27       | 13.17%  |
| RAID | 2        | 0.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 124      | 73.81%  |
| AMD      | 42       | 25%     |
| E8C/EATX | 1        | 0.6%    |
| E8C-SWTX | 1        | 0.6%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-6100TE CPU @ 2.70GHz          | 43       | 25.29%  |
| AMD Ryzen 5 1600 Six-Core Processor         | 13       | 7.65%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 10       | 5.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4        | 2.35%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3        | 1.76%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 3        | 1.76%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 3        | 1.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3        | 1.76%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.76%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 2        | 1.18%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 1.18%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 2        | 1.18%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 1.18%   |
| Intel Genuine CPU 0000 @ 2.40GHz            | 2        | 1.18%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.18%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.18%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.18%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.18%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.18%   |
| AMD Athlon 64 X2 Dual Core Processor 4800+  | 2        | 1.18%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.18%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 2        | 1.18%   |
| Intel Xeon D-2177NT CPU @ 1.90GHz           | 1        | 0.59%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.59%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.59%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.59%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.59%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.59%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.59%   |
| Intel Pentium CPU G4500 @ 3.50GHz           | 1        | 0.59%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.59%   |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1        | 0.59%   |
| Intel Core i9-10980XE CPU @ 3.00GHz         | 1        | 0.59%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.59%   |
| Intel Core i7-4960X CPU @ 3.60GHz           | 1        | 0.59%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.59%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.59%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.59%   |
| Intel Core i5-8265UC CPU @ 1.60GHz          | 1        | 0.59%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 0.59%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 0.59%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 0.59%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 0.59%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 0.59%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 0.59%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 0.59%   |
| Intel Core i3-10100T CPU @ 3.00GHz          | 1        | 0.59%   |
| Intel Core 2 Quad CPU Q9500 @ 2.83GHz       | 1        | 0.59%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 0.59%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 0.59%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 1        | 0.59%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 1        | 0.59%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1        | 0.59%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 0.59%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 1        | 0.59%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 1        | 0.59%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 1        | 0.59%   |
| Intel 11th Gen Core i5-11500 @ 2.70GHz      | 1        | 0.59%   |
| E8C/EATX E8C                                | 1        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 57       | 33.73%  |
| AMD Ryzen 5             | 17       | 10.06%  |
| Intel Core i5           | 16       | 9.47%   |
| Intel Pentium           | 13       | 7.69%   |
| Intel Celeron           | 8        | 4.73%   |
| Other                   | 7        | 4.14%   |
| Intel Pentium Dual-Core | 5        | 2.96%   |
| Intel Core 2 Duo        | 4        | 2.37%   |
| AMD Ryzen 7             | 4        | 2.37%   |
| AMD Athlon 64 X2        | 4        | 2.37%   |
| Intel Xeon              | 3        | 1.78%   |
| Intel Pentium Gold      | 3        | 1.78%   |
| AMD A8                  | 3        | 1.78%   |
| Intel Genuine           | 2        | 1.18%   |
| Intel Core i9           | 2        | 1.18%   |
| Intel Core i7           | 2        | 1.18%   |
| Intel Core 2 Quad       | 2        | 1.18%   |
| AMD Ryzen 3             | 2        | 1.18%   |
| AMD Phenom II X4        | 2        | 1.18%   |
| AMD FX                  | 2        | 1.18%   |
| AMD Athlon              | 2        | 1.18%   |
| AMD A10                 | 2        | 1.18%   |
| Intel Pentium D         | 1        | 0.59%   |
| Intel Pentium 4         | 1        | 0.59%   |
| AMD Sempron             | 1        | 0.59%   |
| AMD Ryzen 7 PRO         | 1        | 0.59%   |
| AMD Ryzen 5 PRO         | 1        | 0.59%   |
| AMD Athlon II X4        | 1        | 0.59%   |
| AMD A6                  | 1        | 0.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 92       | 54.44%  |
| 4      | 38       | 22.49%  |
| 6      | 22       | 13.02%  |
| 8      | 8        | 4.73%   |
| 1      | 3        | 1.78%   |
| 3      | 2        | 1.18%   |
| 32     | 1        | 0.59%   |
| 18     | 1        | 0.59%   |
| 16     | 1        | 0.59%   |
| 14     | 1        | 0.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 165      | 98.21%  |
| 2      | 2        | 1.19%   |
| 4      | 1        | 0.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 116      | 69.05%  |
| 1      | 52       | 30.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 165      | 98.21%  |
| Unknown        | 2        | 1.19%   |
| 32-bit         | 1        | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 48       | 28.24%  |
| Unknown    | 25       | 14.71%  |
| 0x906e9    | 13       | 7.65%   |
| 0x08001138 | 13       | 7.65%   |
| 0x1067a    | 9        | 5.29%   |
| 0xa0653    | 6        | 3.53%   |
| 0x906eb    | 5        | 2.94%   |
| 0x906ea    | 4        | 2.35%   |
| 0x08108109 | 4        | 2.35%   |
| 0x806e9    | 3        | 1.76%   |
| 0x806c1    | 3        | 1.76%   |
| 0x306a9    | 3        | 1.76%   |
| 0xa0671    | 2        | 1.18%   |
| 0x906ed    | 2        | 1.18%   |
| 0x30679    | 2        | 1.18%   |
| 0x206a7    | 2        | 1.18%   |
| 0x08701021 | 2        | 1.18%   |
| 0x06001119 | 2        | 1.18%   |
| 0x010000db | 2        | 1.18%   |
| 0xf47      | 1        | 0.59%   |
| 0xf29      | 1        | 0.59%   |
| 0x806ec    | 1        | 0.59%   |
| 0x6fb      | 1        | 0.59%   |
| 0x506e8    | 1        | 0.59%   |
| 0x506c9    | 1        | 0.59%   |
| 0x50657    | 1        | 0.59%   |
| 0x50654    | 1        | 0.59%   |
| 0x306e4    | 1        | 0.59%   |
| 0x306c3    | 1        | 0.59%   |
| 0x206c2    | 1        | 0.59%   |
| 0x10661    | 1        | 0.59%   |
| 0x0a50000c | 1        | 0.59%   |
| 0x08108102 | 1        | 0.59%   |
| 0x0810100b | 1        | 0.59%   |
| 0x0800820d | 1        | 0.59%   |
| 0x08001129 | 1        | 0.59%   |
| 0x06000852 | 1        | 0.59%   |
| 0x010000c8 | 1        | 0.59%   |
| 0x00000000 | 1        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Skylake     | 53       | 31.55%  |
| KabyLake    | 30       | 17.86%  |
| Zen         | 15       | 8.93%   |
| Penryn      | 10       | 5.95%   |
| Zen+        | 7        | 4.17%   |
| CometLake   | 7        | 4.17%   |
| Piledriver  | 5        | 2.98%   |
| K8 Hammer   | 5        | 2.98%   |
| IvyBridge   | 5        | 2.98%   |
| Unknown     | 4        | 2.38%   |
| Zen 2       | 3        | 1.79%   |
| TigerLake   | 3        | 1.79%   |
| Silvermont  | 3        | 1.79%   |
| SandyBridge | 3        | 1.79%   |
| K10         | 3        | 1.79%   |
| Steamroller | 2        | 1.19%   |
| NetBurst    | 2        | 1.19%   |
| Haswell     | 2        | 1.19%   |
| Core        | 2        | 1.19%   |
| Zen 3       | 1        | 0.6%    |
| Westmere    | 1        | 0.6%    |
| K10 Llano   | 1        | 0.6%    |
| Goldmont    | 1        | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 101      | 58.72%  |
| Nvidia            | 45       | 26.16%  |
| AMD               | 22       | 12.79%  |
| Silicon Motion    | 2        | 1.16%   |
| ASPEED Technology | 2        | 1.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                                    | 45       | 25.71%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 16       | 9.14%   |
| Intel HD Graphics 610                                                                    | 10       | 5.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9        | 5.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6        | 3.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6        | 3.43%   |
| Intel HD Graphics 510                                                                    | 5        | 2.86%   |
| Intel HD Graphics 620                                                                    | 4        | 2.29%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 1.71%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3        | 1.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3        | 1.71%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 3        | 1.71%   |
| Silicon Motion SM718 LynxSE+                                                             | 2        | 1.14%   |
| Intel HD Graphics 630                                                                    | 2        | 1.14%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.14%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.14%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 1.14%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.14%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.57%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.57%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.57%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.57%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.57%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.57%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.57%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.57%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1        | 0.57%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.57%   |
| Nvidia GK106 [GeForce GTX 650 Ti Boost]                                                  | 1        | 0.57%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.57%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 0.57%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 1        | 0.57%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 0.57%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1        | 0.57%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 0.57%   |
| Nvidia G92 [GeForce 8800 GT]                                                             | 1        | 0.57%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 0.57%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 0.57%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 0.57%   |
| Nvidia C51PV [GeForce 6150]                                                              | 1        | 0.57%   |
| Nvidia C51G [GeForce 6100]                                                               | 1        | 0.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 0.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1        | 0.57%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.57%   |
| Intel HD Graphics 500                                                                    | 1        | 0.57%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                                 | 1        | 0.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1        | 0.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 0.57%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 0.57%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 0.57%   |
| AMD Trinity [Radeon HD 7660D]                                                            | 1        | 0.57%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 1        | 0.57%   |
| AMD RV530LE [Radeon X1600/X1650 PRO]                                                     | 1        | 0.57%   |
| AMD RV530 [Radeon X1650] (Secondary)                                                     | 1        | 0.57%   |
| AMD RV530 [Radeon X1600] (Secondary)                                                     | 1        | 0.57%   |
| AMD RV530 [Radeon X1600 PRO]                                                             | 1        | 0.57%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series] (Secondary)                                    | 1        | 0.57%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series]                                                | 1        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 98       | 58.33%  |
| 1 x Nvidia         | 44       | 26.19%  |
| 1 x AMD            | 19       | 11.31%  |
| 2 x AMD            | 2        | 1.19%   |
| 1 x Silicon Motion | 2        | 1.19%   |
| 1 x ASPEED         | 2        | 1.19%   |
| Intel + Nvidia     | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 131      | 77.51%  |
| Proprietary | 33       | 19.53%  |
| Unknown     | 5        | 2.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 110      | 65.09%  |
| 3.01-4.0   | 19       | 11.24%  |
| 0.51-1.0   | 13       | 7.69%   |
| 0.01-0.5   | 13       | 7.69%   |
| 1.01-2.0   | 10       | 5.92%   |
| 7.01-8.0   | 1        | 0.59%   |
| 5.01-6.0   | 1        | 0.59%   |
| 2.01-3.0   | 1        | 0.59%   |
| 8.01-16.0  | 1        | 0.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| HHT                  | 43       | 25.15%  |
| Acer                 | 22       | 12.87%  |
| BenQ                 | 19       | 11.11%  |
| AOC                  | 19       | 11.11%  |
| Samsung Electronics  | 15       | 8.77%   |
| Goldstar             | 8        | 4.68%   |
| ViewSonic            | 7        | 4.09%   |
| Dell                 | 6        | 3.51%   |
| PRW                  | 4        | 2.34%   |
| Philips              | 4        | 2.34%   |
| WBT                  | 3        | 1.75%   |
| LG Electronics       | 3        | 1.75%   |
| Ancor Communications | 3        | 1.75%   |
| STD                  | 2        | 1.17%   |
| Hewlett-Packard      | 2        | 1.17%   |
| VIE                  | 1        | 0.58%   |
| Toshiba              | 1        | 0.58%   |
| SKG                  | 1        | 0.58%   |
| Lenovo               | 1        | 0.58%   |
| JRY                  | 1        | 0.58%   |
| HIB                  | 1        | 0.58%   |
| HannStar             | 1        | 0.58%   |
| DZW                  | 1        | 0.58%   |
| ASUSTek Computer     | 1        | 0.58%   |
| Apple                | 1        | 0.58%   |
| Unknown              | 1        | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HHT ActviPanel V5 HHT0030 3840x2160 944x398mm 40.3-inch               | 43       | 24.29%  |
| AOC LCD Monitor 2778X 2560x1440                                       | 11       | 6.21%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                     | 10       | 5.65%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 7        | 3.95%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 5        | 2.82%   |
| PRW AP7_Titanium PRW4200 3840x2160                                    | 4        | 2.26%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                      | 3        | 1.69%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch         | 3        | 1.69%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2        | 1.13%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                         | 2        | 1.13%   |
| Samsung Electronics S22E391 SAM0C0E 1920x1080 477x268mm 21.5-inch     | 2        | 1.13%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                | 2        | 1.13%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                     | 2        | 1.13%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 2        | 1.13%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                      | 2        | 1.13%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                       | 2        | 1.13%   |
| ViewSonic VA1916wSERIES VSCF91F 1440x900 410x256mm 19.0-inch          | 1        | 0.56%   |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch           | 1        | 0.56%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 0.56%   |
| Toshiba LCD Monitor TV 1920x1080                                      | 1        | 0.56%   |
| SKG 86 Monitor SKG8600 3840x2160 1650x928mm 74.5-inch                 | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 0.56%   |
| Samsung Electronics SMS22A450 SAM0836 1680x1050 459x296mm 21.5-inch   | 1        | 0.56%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 1        | 0.56%   |
| Samsung Electronics S24B370 SAM08DE 1920x1080 531x299mm 24.0-inch     | 1        | 0.56%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1        | 0.56%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 0.56%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1        | 0.56%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1        | 0.56%   |
| Samsung Electronics EPSON PJ SECA60D 1920x1080                        | 1        | 0.56%   |
| Samsung Electronics C27JG5x SAM0F58 2560x1440 597x336mm 27.0-inch     | 1        | 0.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 0.56%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch               | 1        | 0.56%   |
| Philips PHI32PFL3404 PHLD067 1360x768 700x390mm 31.5-inch             | 1        | 0.56%   |
| Philips LCD Monitor 19SL 1280x1024                                    | 1        | 0.56%   |
| Philips 19S PHL0878 1280x1024 376x301mm 19.0-inch                     | 1        | 0.56%   |
| LG Electronics LCD Monitor W2243 1920x1080                            | 1        | 0.56%   |
| LG Electronics LCD Monitor L1752S 1280x1024                           | 1        | 0.56%   |
| LG Electronics LCD Monitor E2250 1920x1080                            | 1        | 0.56%   |
| LG Electronics LCD Monitor 2D FHD LG TV 1920x1080                     | 1        | 0.56%   |
| Lenovo LEN E2323swA LEN60B0 1920x1080 477x268mm 21.5-inch             | 1        | 0.56%   |
| JRY HDMI JRY2380 1920x1080 527x296mm 23.8-inch                        | 1        | 0.56%   |
| HIB AIO HIB0001 1920x1200 476x268mm 21.5-inch                         | 1        | 0.56%   |
| Hewlett-Packard L1730 HWP260E 1280x1024 338x270mm 17.0-inch           | 1        | 0.56%   |
| Hewlett-Packard E241i HWP3124 1920x1200 518x324mm 24.1-inch           | 1        | 0.56%   |
| HannStar JC171D HSD04B2 1280x1024 338x270mm 17.0-inch                 | 1        | 0.56%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                  | 1        | 0.56%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 1        | 0.56%   |
| Goldstar L1953S GSM4B3E 1280x1024 376x301mm 19.0-inch                 | 1        | 0.56%   |
| Goldstar L1752S GSM4432 1280x1024 338x270mm 17.0-inch                 | 1        | 0.56%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 1        | 0.56%   |
| Goldstar 22M35 GSM5A31 1920x1080 480x270mm 21.7-inch                  | 1        | 0.56%   |
| DZW SMART TV UHD DZW0030 3840x2160 708x398mm 32.0-inch                | 1        | 0.56%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1        | 0.56%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                    | 1        | 0.56%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 1        | 0.56%   |
| Dell S2318H/HX DELD0BC 1920x1080 510x290mm 23.1-inch                  | 1        | 0.56%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 1        | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 66       | 39.05%  |
| 3840x2160 (4K)     | 52       | 30.77%  |
| 2560x1440 (QHD)    | 23       | 13.61%  |
| 1280x1024 (SXGA)   | 13       | 7.69%   |
| 1600x900 (HD+)     | 3        | 1.78%   |
| 1440x900 (WXGA+)   | 3        | 1.78%   |
| 1680x1050 (WSXGA+) | 2        | 1.18%   |
| 1366x768 (WXGA)    | 2        | 1.18%   |
| Unknown            | 2        | 1.18%   |
| 4480x1440          | 1        | 0.59%   |
| 1920x1200 (WUXGA)  | 1        | 0.59%   |
| 1360x768           | 1        | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 40      | 43       | 25.44%  |
| 24      | 30       | 17.75%  |
| Unknown | 24       | 14.2%   |
| 23      | 17       | 10.06%  |
| 21      | 16       | 9.47%   |
| 19      | 10       | 5.92%   |
| 27      | 6        | 3.55%   |
| 17      | 6        | 3.55%   |
| 31      | 4        | 2.37%   |
| 26      | 3        | 1.78%   |
| 22      | 2        | 1.18%   |
| 74      | 1        | 0.59%   |
| 72      | 1        | 0.59%   |
| 46      | 1        | 0.59%   |
| 33      | 1        | 0.59%   |
| 32      | 1        | 0.59%   |
| 28      | 1        | 0.59%   |
| 20      | 1        | 0.59%   |
| 18      | 1        | 0.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 55       | 33.13%  |
| 901-1000    | 43       | 25.9%   |
| Unknown     | 24       | 14.46%  |
| 401-500     | 23       | 13.86%  |
| 301-350     | 6        | 3.61%   |
| 601-700     | 5        | 3.01%   |
| 351-400     | 5        | 3.01%   |
| 701-800     | 2        | 1.2%    |
| 1501-2000   | 2        | 1.2%    |
| 1001-1500   | 1        | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 79       | 48.77%  |
| 21/9    | 43       | 26.54%  |
| Unknown | 20       | 12.35%  |
| 5/4     | 11       | 6.79%   |
| 16/10   | 8        | 4.94%   |
| 3/2     | 1        | 0.62%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 57       | 34.34%  |
| 501-1000       | 44       | 26.51%  |
| Unknown        | 24       | 14.46%  |
| 151-200        | 14       | 8.43%   |
| 301-350        | 9        | 5.42%   |
| 351-500        | 7        | 4.22%   |
| 141-150        | 7        | 4.22%   |
| More than 1000 | 2        | 1.2%    |
| 251-300        | 2        | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 66       | 39.52%  |
| 101-120 | 62       | 37.13%  |
| Unknown | 24       | 14.37%  |
| 121-160 | 11       | 6.59%   |
| 1-50    | 4        | 2.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 147      | 86.47%  |
| 2     | 13       | 7.65%   |
| 0     | 9        | 5.29%   |
| 3     | 1        | 0.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 140      | 59.32%  |
| Intel                      | 65       | 27.54%  |
| Qualcomm Atheros           | 10       | 4.24%   |
| Nvidia                     | 6        | 2.54%   |
| Microchip Technology       | 3        | 1.27%   |
| Ralink Technology          | 2        | 0.85%   |
| Ralink                     | 2        | 0.85%   |
| MCST                       | 2        | 0.85%   |
| ZTE WCDMA Technologies MSM | 1        | 0.42%   |
| Vimtron Electronics        | 1        | 0.42%   |
| VIA Technologies           | 1        | 0.42%   |
| TP-Link                    | 1        | 0.42%   |
| D-Link                     | 1        | 0.42%   |
| Broadcom Limited           | 1        | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 84       | 32.56%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 43       | 16.67%  |
| Intel Ethernet Connection I219-LM                                 | 31       | 12.02%  |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 6.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.33%   |
| Intel Wireless 3165                                               | 5        | 1.94%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3        | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.16%   |
| Microchip MCP2221 USB-I2C/UART Combo                              | 3        | 1.16%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.16%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 1.16%   |
| Intel Ethernet Connection (13) I219-V                             | 3        | 1.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.78%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.78%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2        | 0.78%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1        | 0.39%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.39%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.39%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.39%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.39%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.39%   |
| Realtek 802.11ac NIC                                              | 1        | 0.39%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.39%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.39%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 0.39%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1        | 0.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.39%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.39%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.39%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.39%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.39%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.39%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.39%   |
| Intel Wireless-AC 9260                                            | 1        | 0.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.39%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 0.39%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.39%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.39%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1        | 0.39%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1        | 0.39%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.39%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.39%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.39%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.39%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.39%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 1        | 0.39%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 35.71%  |
| Intel                 | 10       | 35.71%  |
| Qualcomm Atheros      | 3        | 10.71%  |
| Ralink Technology     | 2        | 7.14%   |
| Ralink                | 2        | 7.14%   |
| TP-Link               | 1        | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                        | 5        | 17.86%  |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 3        | 10.71%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 3        | 10.71%  |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 2        | 7.14%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 3.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 3.57%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 3.57%   |
| Realtek 802.11ac NIC                                       | 1        | 3.57%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 3.57%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 3.57%   |
| Ralink RT5392 PCIe Wireless Network Adapter                | 1        | 3.57%   |
| Ralink RT2561/RT61 rev B 802.11g                           | 1        | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 3.57%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 3.57%   |
| Intel Wireless-AC 9260                                     | 1        | 3.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 3.57%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 139      | 62.61%  |
| Intel                      | 63       | 28.38%  |
| Qualcomm Atheros           | 7        | 3.15%   |
| Nvidia                     | 6        | 2.7%    |
| MCST                       | 2        | 0.9%    |
| ZTE WCDMA Technologies MSM | 1        | 0.45%   |
| Vimtron Electronics        | 1        | 0.45%   |
| VIA Technologies           | 1        | 0.45%   |
| D-Link                     | 1        | 0.45%   |
| Broadcom Limited           | 1        | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 84       | 37%     |
| Realtek RTL8152 Fast Ethernet Adapter                             | 43       | 18.94%  |
| Intel Ethernet Connection I219-LM                                 | 31       | 13.66%  |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 7.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.64%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.32%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 1.32%   |
| Intel Ethernet Connection (13) I219-V                             | 3        | 1.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.88%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.88%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.88%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1        | 0.44%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.44%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.44%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.44%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.44%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.44%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.44%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.44%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.44%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1        | 0.44%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1        | 0.44%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.44%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.44%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.44%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 1        | 0.44%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 167      | 84.34%  |
| WiFi     | 28       | 14.14%  |
| Modem    | 3        | 1.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 154      | 90.59%  |
| WiFi     | 16       | 9.41%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 143      | 85.12%  |
| 2     | 22       | 13.1%   |
| 13    | 1        | 0.6%    |
| 8     | 1        | 0.6%    |
| 3     | 1        | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 163      | 97.02%  |
| Yes  | 5        | 2.98%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 45.45%  |
| Cambridge Silicon Radio | 5        | 22.73%  |
| Realtek Semiconductor   | 3        | 13.64%  |
| Broadcom                | 2        | 9.09%   |
| Logitech                | 1        | 4.55%   |
| IMC Networks            | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 7        | 31.82%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 22.73%  |
| Realtek Bluetooth Radio                             | 2        | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4.55%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.55%   |
| Intel AX210 Bluetooth                               | 1        | 4.55%   |
| Intel AX200 Bluetooth                               | 1        | 4.55%   |
| IMC Networks Bluetooth Device                       | 1        | 4.55%   |
| Broadcom Bluetooth dongle                           | 1        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 120      | 55.81%  |
| Nvidia              | 42       | 19.53%  |
| AMD                 | 40       | 18.6%   |
| C-Media Electronics | 4        | 1.86%   |
| MCST                | 2        | 0.93%   |
| VIA Technologies    | 1        | 0.47%   |
| JMTek               | 1        | 0.47%   |
| EasyPass Industrial | 1        | 0.47%   |
| Creative Technology | 1        | 0.47%   |
| Creative Labs       | 1        | 0.47%   |
| Apple               | 1        | 0.47%   |
| A4Tech              | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 64       | 27.47%  |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17       | 7.3%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15       | 6.44%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9        | 3.86%   |
| Intel 200 Series PCH HD Audio                                                                     | 8        | 3.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7        | 3%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 2.58%   |
| AMD FCH Azalia Controller                                                                         | 6        | 2.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 2.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5        | 2.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 1.72%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 1.72%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 1.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3        | 1.29%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.29%   |
| Intel Audio device                                                                                | 3        | 1.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3        | 1.29%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3        | 1.29%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3        | 1.29%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3        | 1.29%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2        | 0.86%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 0.86%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2        | 0.86%   |
| MCST HD Audio                                                                                     | 2        | 0.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2        | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2        | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2        | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 0.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 0.86%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2        | 0.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 0.86%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1        | 0.43%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.43%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 0.43%   |
| Nvidia MCP73 High Definition Audio                                                                | 1        | 0.43%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 0.43%   |
| Nvidia MCP51 High Definition Audio                                                                | 1        | 0.43%   |
| Nvidia MCP51 AC97 Audio Controller                                                                | 1        | 0.43%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.43%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.43%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 0.43%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 0.43%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1        | 0.43%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1        | 0.43%   |
| Nvidia CK804 AC'97 Audio Controller                                                               | 1        | 0.43%   |
| Nvidia Audio device                                                                               | 1        | 0.43%   |
| JMTek USB PnP Audio Device                                                                        | 1        | 0.43%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 0.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1        | 0.43%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 0.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1        | 0.43%   |
| EasyPass Industrial Audioengine D1                                                                | 1        | 0.43%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                                                      | 1        | 0.43%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 1        | 0.43%   |
| C-Media Electronics CM103+ Audio Controller                                                       | 1        | 0.43%   |
| Apple Audio in LED Cinema Display                                                                 | 1        | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 28       | 22.95%  |
| Unknown             | 19       | 15.57%  |
| Kingston            | 19       | 15.57%  |
| Micron Technology   | 14       | 11.48%  |
| Samsung Electronics | 12       | 9.84%   |
| SK hynix            | 5        | 4.1%    |
| Foxline             | 4        | 3.28%   |
| Apacer              | 3        | 2.46%   |
| Patriot             | 2        | 1.64%   |
| Goodram             | 2        | 1.64%   |
| Goldkey             | 2        | 1.64%   |
| A-DATA Technology   | 2        | 1.64%   |
| Unknown (0x0B7A)    | 1        | 0.82%   |
| tigo                | 1        | 0.82%   |
| Shenzhen Longsys    | 1        | 0.82%   |
| Ramaxel Technology  | 1        | 0.82%   |
| Qumo                | 1        | 0.82%   |
| Juhor               | 1        | 0.82%   |
| G.Skill             | 1        | 0.82%   |
| Elpida              | 1        | 0.82%   |
| Corsair             | 1        | 0.82%   |
| Unknown             | 1        | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s             | 13       | 9.7%    |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                         | 10       | 7.46%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s           | 4        | 2.99%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s           | 3        | 2.24%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2        | 1.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2        | 1.49%   |
| Unknown RAM Module 1024MB DIMM                                   | 2        | 1.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2        | 1.49%   |
| Samsung RAM M378A1K43EB2-CVF 8GB DIMM DDR4 2933MT/s              | 2        | 1.49%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s            | 2        | 1.49%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 2        | 1.49%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s           | 2        | 1.49%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                        | 1        | 0.75%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM 333MT/s                           | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM 533MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                      | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1        | 0.75%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM SDRAM 533MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                       | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM 400MT/s                           | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM 32MT/s                            | 1        | 0.75%   |
| Unknown (0x0B7A) RAM UDIMM PC4-2666 8G 1R 8GB DIMM DDR4 2667MT/s | 1        | 0.75%   |
| tigo RAM 4GB-2400MHZ 4GB SODIMM DDR4 2400MT/s                    | 1        | 0.75%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 1        | 0.75%   |
| SK hynix RAM HMT151R7TFR4C-H9 4096MB DIMM DDR3 1333MT/s          | 1        | 0.75%   |
| SK hynix RAM HMT151R7BFR4C-H9 4096MB DIMM DDR3 1333MT/s          | 1        | 0.75%   |
| SK hynix RAM HMA82GU6CJR8N-XN 16GB DIMM DDR4 3333MT/s            | 1        | 0.75%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1        | 0.75%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8192MB DIMM DDR4 2667MT/s          | 1        | 0.75%   |
| Shenzhen Longsys RAM FD4AS3200C8GSE 8GB SODIMM DDR4 3200MT/s     | 1        | 0.75%   |
| Samsung RAM Module 4096MB DIMM DDR4 2667MT/s                     | 1        | 0.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1        | 0.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1        | 0.75%   |
| Samsung RAM M471A1K43BB1-CWE 8GB SODIMM DDR4 3534MT/s            | 1        | 0.75%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s              | 1        | 0.75%   |
| Samsung RAM M378A5143DB0-CPB 4GB DIMM DDR4 2400MT/s              | 1        | 0.75%   |
| Samsung RAM M378A2G43MX3-CTD 16384MB DIMM DDR4 3466MT/s          | 1        | 0.75%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s              | 1        | 0.75%   |
| Ramaxel RAM RML1040EG38D6W-533 512MB DIMM DDR2 533MT/s           | 1        | 0.75%   |
| Qumo RAM QUM4U-8G2666P19 8192MB DIMM DDR4 2667MT/s               | 1        | 0.75%   |
| Patriot RAM PSD44G240081 4GB DIMM DDR4 2400MT/s                  | 1        | 0.75%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                   | 1        | 0.75%   |
| Micron RAM Module 8192MB DIMM DDR4 2400MT/s                      | 1        | 0.75%   |
| Micron RAM Module 4096MB DIMM DDR4 2400MT/s                      | 1        | 0.75%   |
| Micron RAM 8JTF25664AZ-1G4H1 2GB DIMM DDR3 1333MT/s              | 1        | 0.75%   |
| Micron RAM 8ATF1G64HZ-2G3B2 8GB SODIMM DDR4 2400MT/s             | 1        | 0.75%   |
| Kingston RAM Module 32GB DIMM DDR4 3200MT/s                      | 1        | 0.75%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s          | 1        | 0.75%   |
| Kingston RAM KHX2933C17D4/8G 8GB DIMM DDR4 3200MT/s              | 1        | 0.75%   |
| Kingston RAM KHX2400C15D4/4G 4096MB DIMM DDR4 3151MT/s           | 1        | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 76       | 66.09%  |
| DDR3    | 20       | 17.39%  |
| Unknown | 11       | 9.57%   |
| DDR2    | 4        | 3.48%   |
| SDRAM   | 3        | 2.61%   |
| DDR     | 1        | 0.87%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 100      | 86.96%  |
| SODIMM | 15       | 13.04%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 49       | 40.83%  |
| 8192  | 44       | 36.67%  |
| 1024  | 10       | 8.33%   |
| 2048  | 9        | 7.5%    |
| 16384 | 4        | 3.33%   |
| 512   | 3        | 2.5%    |
| 32768 | 1        | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 38       | 31.15%  |
| 1600    | 13       | 10.66%  |
| 2667    | 11       | 9.02%   |
| 2133    | 9        | 7.38%   |
| 3200    | 8        | 6.56%   |
| 1333    | 6        | 4.92%   |
| 2933    | 5        | 4.1%    |
| 800     | 4        | 3.28%   |
| 667     | 4        | 3.28%   |
| Unknown | 4        | 3.28%   |
| 400     | 3        | 2.46%   |
| 533     | 2        | 1.64%   |
| 333     | 2        | 1.64%   |
| 4333    | 1        | 0.82%   |
| 3534    | 1        | 0.82%   |
| 3533    | 1        | 0.82%   |
| 3466    | 1        | 0.82%   |
| 3333    | 1        | 0.82%   |
| 3266    | 1        | 0.82%   |
| 3151    | 1        | 0.82%   |
| 2866    | 1        | 0.82%   |
| 2666    | 1        | 0.82%   |
| 1867    | 1        | 0.82%   |
| 1866    | 1        | 0.82%   |
| 1066    | 1        | 0.82%   |
| 32      | 1        | 0.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 50%     |
| Hewlett-Packard     | 2        | 25%     |
| QinHeng Electronics | 1        | 12.5%   |
| Canon               | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Samsung SCX-4200 series        | 1        | 12.5%   |
| Samsung SCX-3400 Series        | 1        | 12.5%   |
| Samsung SCX-3200 Series        | 1        | 12.5%   |
| Samsung M332x 382x 402x Series | 1        | 12.5%   |
| QinHeng CH340S                 | 1        | 12.5%   |
| HP LaserJet P1102              | 1        | 12.5%   |
| HP LaserJet M402dn             | 1        | 12.5%   |
| Canon MF4410                   | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 14       | 56%     |
| Alcor Micro             | 7        | 28%     |
| Z-Star Microelectronics | 1        | 4%      |
| Microsoft               | 1        | 4%      |
| Hewlett-Packard         | 1        | 4%      |
| Apple                   | 1        | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Logitech Webcam C270               | 9        | 36%     |
| Alcor Micro USB 2.0 PC Camera      | 5        | 20%     |
| Alcor Micro USB 2.0 Camera         | 2        | 8%      |
| Z-Star Venus USB2.0 Camera         | 1        | 4%      |
| Microsoft LifeCam VX-700           | 1        | 4%      |
| Logitech Webcam C930e              | 1        | 4%      |
| Logitech HD Webcam C525            | 1        | 4%      |
| Logitech HD Pro Webcam C920        | 1        | 4%      |
| Logitech C505 HD Webcam            | 1        | 4%      |
| Logitech B525 HD Webcam            | 1        | 4%      |
| HP Webcam HD 2300                  | 1        | 4%      |
| Apple iSight in LED Cinema Display | 1        | 4%      |

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
| 0     | 157      | 91.81%  |
| 1     | 12       | 7.02%   |
| 5     | 1        | 0.58%   |
| 2     | 1        | 0.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 7        | 38.89%  |
| Graphics card            | 4        | 22.22%  |
| Multimedia controller    | 2        | 11.11%  |
| Unassigned class         | 1        | 5.56%   |
| Net/wireless             | 1        | 5.56%   |
| Net/ethernet             | 1        | 5.56%   |
| Chipcard                 | 1        | 5.56%   |
| Bluetooth                | 1        | 5.56%   |

