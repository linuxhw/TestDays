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

Total: 283

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Graviton      | DMB-H510-MCA01              | [4dbcbc3b7a](https://linux-hardware.org/?probe=4dbcbc3b7a) | Nov 30, 2022 |
| MSI           | J1800I                      | [156269ae8c](https://linux-hardware.org/?probe=156269ae8c) | Nov 26, 2022 |
| Graviton      | DMB-A520-MCA01              | [1a09a9bb5c](https://linux-hardware.org/?probe=1a09a9bb5c) | Nov 14, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [b5965fce49](https://linux-hardware.org/?probe=b5965fce49) | Nov 11, 2022 |
| ASUSTek       | P7H55-M/USB3                | [d3d30c473e](https://linux-hardware.org/?probe=d3d30c473e) | Nov 10, 2022 |
| Gigabyte      | 8I915GMF                    | [76f5cb17ad](https://linux-hardware.org/?probe=76f5cb17ad) | Nov 10, 2022 |
| ASUSTek       | P7H55-M/USB3                | [8983159779](https://linux-hardware.org/?probe=8983159779) | Oct 30, 2022 |
| ASRock        | Z77 Pro4-M                  | [b388ac6776](https://linux-hardware.org/?probe=b388ac6776) | Oct 27, 2022 |
| Biostar       | TB250-BTC                   | [89e7931244](https://linux-hardware.org/?probe=89e7931244) | Oct 27, 2022 |
| Intel         | D34010WYK H14771-301        | [cea24a780a](https://linux-hardware.org/?probe=cea24a780a) | Oct 26, 2022 |
| Gigabyte      | H61M-S2PV                   | [a876af89ec](https://linux-hardware.org/?probe=a876af89ec) | Oct 24, 2022 |
| MSI           | PRO H610M-B DDR4            | [25db5739b7](https://linux-hardware.org/?probe=25db5739b7) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-301        | [18d8d35afa](https://linux-hardware.org/?probe=18d8d35afa) | Oct 24, 2022 |
| Huanan        | H97-ZD3 V2.0                | [d0d194fbdc](https://linux-hardware.org/?probe=d0d194fbdc) | Oct 15, 2022 |
| Graviton      | DMB-H510-MCA01              | [355974871d](https://linux-hardware.org/?probe=355974871d) | Oct 12, 2022 |
| Graviton      | DMB-H510-MCA01              | [02395d2c6f](https://linux-hardware.org/?probe=02395d2c6f) | Oct 07, 2022 |
| Gigabyte      | H110M-S2-CF                 | [79b160283f](https://linux-hardware.org/?probe=79b160283f) | Oct 05, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [8e3ee86b79](https://linux-hardware.org/?probe=8e3ee86b79) | Oct 05, 2022 |
| ASUSTek       | D300TA                      | [7c175e4db4](https://linux-hardware.org/?probe=7c175e4db4) | Oct 03, 2022 |
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
| Graviton      | DMB-A520-MCA01              | [edd6464f18](https://linux-hardware.org/?probe=edd6464f18) | Jan 19, 2022 |
| Graviton      | DMB-A520-MCA01              | [93fef2e073](https://linux-hardware.org/?probe=93fef2e073) | Jan 19, 2022 |
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
| Kometa P10         | 81       | 40.5%   |
| ALT Linux 9.1      | 33       | 16.5%   |
| ALT Linux 10.0     | 20       | 10%     |
| ALT Linux 10.1     | 17       | 8.5%    |
| ALT Linux 9.0      | 15       | 7.5%    |
| ALT Linux 9.2      | 7        | 3.5%    |
| MOS 10             | 5        | 2.5%    |
| ALT Linux P10      | 3        | 1.5%    |
| ALT Linux 8.4      | 3        | 1.5%    |
| ALT Linux P9       | 2        | 1%      |
| ALT Linux P8       | 2        | 1%      |
| ALT Linux 8.2      | 2        | 1%      |
| ALT Linux 7.0.5    | 2        | 1%      |
| ALT Linux 10.0.900 | 2        | 1%      |
| Kometa 1           | 1        | 0.5%    |
| ALT Linux 8.2.0    | 1        | 0.5%    |
| ALT Linux 20220110 | 1        | 0.5%    |
| ALT Linux 20201124 | 1        | 0.5%    |
| ALT Linux 20190303 | 1        | 0.5%    |
| ALT Linux 10.0.910 | 1        | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ALT Linux | 191      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.109-std-def-alt1       | 51       | 24.76%  |
| 5.10.102-std-def-alt1       | 27       | 13.11%  |
| 5.15.34-un-def-alt1         | 8        | 3.88%   |
| 5.10.82-std-def-alt1        | 8        | 3.88%   |
| 5.4.68-std-def-alt1.1       | 7        | 3.4%    |
| 5.4.51-std-def-alt1         | 5        | 2.43%   |
| 5.15.32-un-def-alt1         | 5        | 2.43%   |
| 5.4.41-std-def-alt1         | 3        | 1.46%   |
| 5.10.93-std-def-alt1        | 3        | 1.46%   |
| 5.10.35-un-def-alt1         | 3        | 1.46%   |
| 5.10.32-un-def-alt1         | 3        | 1.46%   |
| 5.10.145-std-def-alt1       | 3        | 1.46%   |
| 4.19.79-std-def-alt1        | 3        | 1.46%   |
| 5.7.19-un-def-alt1          | 2        | 0.97%   |
| 5.4.85-std-def-alt1         | 2        | 0.97%   |
| 5.4.62-std-def-alt1         | 2        | 0.97%   |
| 5.4.28-std-def-alt1         | 2        | 0.97%   |
| 5.4.181-std-def-alt1        | 2        | 0.97%   |
| 5.4.127-std-def-alt1        | 2        | 0.97%   |
| 5.2.10-un-def-alt1          | 2        | 0.97%   |
| 5.15.70-un-def-alt1         | 2        | 0.97%   |
| 5.15.15-un-def-alt1         | 2        | 0.97%   |
| 5.15.14-un-def-alt1         | 2        | 0.97%   |
| 5.10.88-std-def-alt1        | 2        | 0.97%   |
| 5.10.83-std-def-alt0.c9f.2  | 2        | 0.97%   |
| 5.10.72-std-def-alt1        | 2        | 0.97%   |
| 5.10.17-un-def-alt1         | 2        | 0.97%   |
| 5.10.123-std-def-alt1       | 2        | 0.97%   |
| 5.9.8-un-def-alt1           | 1        | 0.49%   |
| 5.7.14-un-def-alt1          | 1        | 0.49%   |
| 5.4.94-std-def-alt1         | 1        | 0.49%   |
| 5.4.92-std-def-alt1         | 1        | 0.49%   |
| 5.4.91-elbrus-def-alt2.12.1 | 1        | 0.49%   |
| 5.4.81-std-def-alt1         | 1        | 0.49%   |
| 5.4.58-elbrus-def-alt1.7.0  | 1        | 0.49%   |
| 5.4.35-std-def-alt1         | 1        | 0.49%   |
| 5.4.134-std-def-alt1        | 1        | 0.49%   |
| 5.4.123-std-def-alt1        | 1        | 0.49%   |
| 5.4.104-std-def-alt1        | 1        | 0.49%   |
| 5.2.11-un-def-alt1          | 1        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.109 | 51       | 24.76%  |
| 5.10.102 | 27       | 13.11%  |
| 5.15.34  | 8        | 3.88%   |
| 5.10.82  | 8        | 3.88%   |
| 5.4.68   | 7        | 3.4%    |
| 5.4.51   | 5        | 2.43%   |
| 5.15.32  | 5        | 2.43%   |
| 5.4.41   | 3        | 1.46%   |
| 5.10.93  | 3        | 1.46%   |
| 5.10.35  | 3        | 1.46%   |
| 5.10.32  | 3        | 1.46%   |
| 5.10.145 | 3        | 1.46%   |
| 4.19.79  | 3        | 1.46%   |
| 5.7.19   | 2        | 0.97%   |
| 5.4.85   | 2        | 0.97%   |
| 5.4.62   | 2        | 0.97%   |
| 5.4.28   | 2        | 0.97%   |
| 5.4.181  | 2        | 0.97%   |
| 5.4.127  | 2        | 0.97%   |
| 5.2.10   | 2        | 0.97%   |
| 5.15.70  | 2        | 0.97%   |
| 5.15.15  | 2        | 0.97%   |
| 5.15.14  | 2        | 0.97%   |
| 5.14.21  | 2        | 0.97%   |
| 5.10.88  | 2        | 0.97%   |
| 5.10.83  | 2        | 0.97%   |
| 5.10.72  | 2        | 0.97%   |
| 5.10.54  | 2        | 0.97%   |
| 5.10.17  | 2        | 0.97%   |
| 5.10.123 | 2        | 0.97%   |
| 5.9.8    | 1        | 0.49%   |
| 5.7.14   | 1        | 0.49%   |
| 5.4.94   | 1        | 0.49%   |
| 5.4.92   | 1        | 0.49%   |
| 5.4.91   | 1        | 0.49%   |
| 5.4.81   | 1        | 0.49%   |
| 5.4.58   | 1        | 0.49%   |
| 5.4.35   | 1        | 0.49%   |
| 5.4.134  | 1        | 0.49%   |
| 5.4.123  | 1        | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 117      | 58.79%  |
| 5.4     | 34       | 17.09%  |
| 5.15    | 23       | 11.56%  |
| 4.19    | 7        | 3.52%   |
| 5.7     | 3        | 1.51%   |
| 5.2     | 3        | 1.51%   |
| 4.9     | 3        | 1.51%   |
| 5.14    | 2        | 1.01%   |
| 4.14    | 2        | 1.01%   |
| 5.9     | 1        | 0.5%    |
| 5.18    | 1        | 0.5%    |
| 5.13    | 1        | 0.5%    |
| 5.12    | 1        | 0.5%    |
| 4.20    | 1        | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 185      | 96.86%  |
| i686   | 4        | 2.09%   |
| e2k    | 2        | 1.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 135      | 69.59%  |
| XFCE     | 28       | 14.43%  |
| Unknown  | 26       | 13.4%   |
| MATE     | 2        | 1.03%   |
| KDE      | 2        | 1.03%   |
| Cinnamon | 1        | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 186      | 97.38%  |
| Unknown | 5        | 2.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 116      | 59.79%  |
| TDM     | 28       | 14.43%  |
| LightDM | 28       | 14.43%  |
| Unknown | 22       | 11.34%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 160      | 81.63%  |
| Unknown | 34       | 17.35%  |
| en_US   | 1        | 0.51%   |
| el_GR   | 1        | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 117      | 60.94%  |
| BIOS | 75       | 39.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 179      | 93.23%  |
| Overlay | 9        | 4.69%   |
| Btrfs   | 4        | 2.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 131      | 68.23%  |
| MBR     | 40       | 20.83%  |
| Unknown | 21       | 10.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 168      | 87.96%  |
| Yes       | 23       | 12.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 142      | 73.2%   |
| Yes       | 52       | 26.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 45       | 23.56%  |
| ASUSTek Computer    | 35       | 18.32%  |
| Gigabyte Technology | 30       | 15.71%  |
| ASRock              | 18       | 9.42%   |
| Acer                | 13       | 6.81%   |
| MSI                 | 11       | 5.76%   |
| Unknown             | 9        | 4.71%   |
| MAINBRD             | 3        | 1.57%   |
| iRU                 | 3        | 1.57%   |
| 3Logic Group        | 3        | 1.57%   |
| Hewlett-Packard     | 2        | 1.05%   |
| Graviton            | 2        | 1.05%   |
| DEPO Computers      | 2        | 1.05%   |
| Dell                | 2        | 1.05%   |
| Biostar             | 2        | 1.05%   |
| VIA Technologies    | 1        | 0.52%   |
| SYS                 | 1        | 0.52%   |
| Supermicro          | 1        | 0.52%   |
| OEM                 | 1        | 0.52%   |
| Lenovo              | 1        | 0.52%   |
| Kraftway            | 1        | 0.52%   |
| Huanan              | 1        | 0.52%   |
| Foxconn             | 1        | 0.52%   |
| EPoX Computer       | 1        | 0.52%   |
| ECS                 | 1        | 0.52%   |
| Aquarius            | 1        | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel SKYBAY                           | 43       | 22.51%  |
| ASUS PRIME B450-PLUS                   | 12       | 6.28%   |
| Acer Veriton X2640G                    | 10       | 5.24%   |
| Unknown                                | 9        | 4.71%   |
| Gigabyte H110M-S2H                     | 4        | 2.09%   |
| MAINBRD OPS62A-SHA                     | 3        | 1.57%   |
| 3Logic Group Graviton                  | 3        | 1.57%   |
| MSI MS-7D46                            | 2        | 1.05%   |
| MSI MPG B560 Trident A (MS-B926)       | 2        | 1.05%   |
| iRU 515                                | 2        | 1.05%   |
| Gigabyte H77M-D3H                      | 2        | 1.05%   |
| ASUS H110M-R                           | 2        | 1.05%   |
| Acer Veriton ES2710G                   | 2        | 1.05%   |
| VIA P4M266A-8235                       | 1        | 0.52%   |
| SYS RAY B101                           | 1        | 0.52%   |
| Supermicro SYS-1019D-14CN-FHN13TP      | 1        | 0.52%   |
| OEM ZXE CRB                            | 1        | 0.52%   |
| MSI MS-7D18                            | 1        | 0.52%   |
| MSI MS-7A38                            | 1        | 0.52%   |
| MSI MS-7996                            | 1        | 0.52%   |
| MSI MS-7895                            | 1        | 0.52%   |
| MSI MS-7877                            | 1        | 0.52%   |
| MSI MS-7758                            | 1        | 0.52%   |
| MSI MS-7721                            | 1        | 0.52%   |
| Lenovo ThinkCentre M73 10B1S15000      | 1        | 0.52%   |
| Kraftway KWH310                        | 1        | 0.52%   |
| iRU IRUB365M                           | 1        | 0.52%   |
| Intel D34010WYK                        | 1        | 0.52%   |
| Intel B75                              | 1        | 0.52%   |
| Huanan H97-ZD3 V2.0                    | 1        | 0.52%   |
| HP Compaq dc7600 Convertible Minitower | 1        | 0.52%   |
| HP 290 G4 Microtower PC                | 1        | 0.52%   |
| Graviton DMB-H510-MCA01                | 1        | 0.52%   |
| Graviton DMB-A520-MCA01                | 1        | 0.52%   |
| Gigabyte Z77MX-D3H                     | 1        | 0.52%   |
| Gigabyte X79-UD3                       | 1        | 0.52%   |
| Gigabyte P35-S3G                       | 1        | 0.52%   |
| Gigabyte M57SLI-S4                     | 1        | 0.52%   |
| Gigabyte J1800N-D2H                    | 1        | 0.52%   |
| Gigabyte H61M-S2PV                     | 1        | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel SKYBAY                      | 43       | 22.51%  |
| ASUS PRIME                        | 17       | 8.9%    |
| Acer Veriton                      | 12       | 6.28%   |
| Unknown                           | 9        | 4.71%   |
| Gigabyte H110M-S2H                | 4        | 2.09%   |
| MAINBRD OPS62A-SHA                | 3        | 1.57%   |
| 3Logic Group Graviton             | 3        | 1.57%   |
| MSI MS-7D46                       | 2        | 1.05%   |
| MSI MPG                           | 2        | 1.05%   |
| iRU 515                           | 2        | 1.05%   |
| Gigabyte H77M-D3H                 | 2        | 1.05%   |
| Gigabyte B550                     | 2        | 1.05%   |
| Gigabyte B450                     | 2        | 1.05%   |
| Dell OptiPlex                     | 2        | 1.05%   |
| ASUS H110M-R                      | 2        | 1.05%   |
| ASRock Z77                        | 2        | 1.05%   |
| VIA P4M266A-8235                  | 1        | 0.52%   |
| SYS RAY                           | 1        | 0.52%   |
| Supermicro SYS-1019D-14CN-FHN13TP | 1        | 0.52%   |
| OEM ZXE                           | 1        | 0.52%   |
| MSI MS-7D18                       | 1        | 0.52%   |
| MSI MS-7A38                       | 1        | 0.52%   |
| MSI MS-7996                       | 1        | 0.52%   |
| MSI MS-7895                       | 1        | 0.52%   |
| MSI MS-7877                       | 1        | 0.52%   |
| MSI MS-7758                       | 1        | 0.52%   |
| MSI MS-7721                       | 1        | 0.52%   |
| Lenovo ThinkCentre                | 1        | 0.52%   |
| Kraftway KWH310                   | 1        | 0.52%   |
| iRU IRUB365M                      | 1        | 0.52%   |
| Intel D34010WYK                   | 1        | 0.52%   |
| Intel B75                         | 1        | 0.52%   |
| Huanan H97-ZD3                    | 1        | 0.52%   |
| HP Compaq                         | 1        | 0.52%   |
| HP 290                            | 1        | 0.52%   |
| Graviton DMB-H510-MCA01           | 1        | 0.52%   |
| Graviton DMB-A520-MCA01           | 1        | 0.52%   |
| Gigabyte Z77MX-D3H                | 1        | 0.52%   |
| Gigabyte X79-UD3                  | 1        | 0.52%   |
| Gigabyte P35-S3G                  | 1        | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 43       | 22.51%  |
| 2017    | 34       | 17.8%   |
| 2016    | 21       | 10.99%  |
| 2020    | 13       | 6.81%   |
| 2021    | 11       | 5.76%   |
| 2012    | 11       | 5.76%   |
| 2022    | 9        | 4.71%   |
| 2019    | 6        | 3.14%   |
| 2015    | 6        | 3.14%   |
| 2014    | 5        | 2.62%   |
| 2008    | 5        | 2.62%   |
| 2011    | 4        | 2.09%   |
| 2010    | 4        | 2.09%   |
| 2009    | 4        | 2.09%   |
| 2007    | 3        | 1.57%   |
| 2006    | 3        | 1.57%   |
| 2005    | 3        | 1.57%   |
| 2013    | 2        | 1.05%   |
| Unknown | 2        | 1.05%   |
| 2004    | 1        | 0.52%   |
| 2003    | 1        | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 191      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 182      | 95.29%  |
| Enabled  | 9        | 4.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 191      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 79       | 41.36%  |
| 4.01-8.0    | 46       | 24.08%  |
| 3.01-4.0    | 28       | 14.66%  |
| 16.01-24.0  | 18       | 9.42%   |
| 32.01-64.0  | 5        | 2.62%   |
| 1.01-2.0    | 5        | 2.62%   |
| 2.01-3.0    | 4        | 2.09%   |
| 64.01-256.0 | 3        | 1.57%   |
| 0.51-1.0    | 2        | 1.05%   |
| 24.01-32.0  | 1        | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 99       | 49.75%  |
| 2.01-3.0  | 31       | 15.58%  |
| 0.51-1.0  | 31       | 15.58%  |
| 4.01-8.0  | 17       | 8.54%   |
| 3.01-4.0  | 15       | 7.54%   |
| 8.01-16.0 | 3        | 1.51%   |
| 0.01-0.5  | 3        | 1.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 129      | 66.49%  |
| 2      | 40       | 20.62%  |
| 3      | 16       | 8.25%   |
| 4      | 4        | 2.06%   |
| 5      | 3        | 1.55%   |
| 8      | 1        | 0.52%   |
| 0      | 1        | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 64.92%  |
| Yes       | 67       | 35.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 190      | 99.48%  |
| No        | 1        | 0.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 155      | 81.15%  |
| Yes       | 36       | 18.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 165      | 85.94%  |
| Yes       | 27       | 14.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Russia     | 184      | 96.34%  |
| Ukraine    | 2        | 1.05%   |
| Greece     | 2        | 1.05%   |
| Kazakhstan | 1        | 0.52%   |
| China      | 1        | 0.52%   |
| Belarus    | 1        | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Moscow                   | 121      | 61.73%  |
| St Petersburg            | 9        | 4.59%   |
| Samara                   | 5        | 2.55%   |
| Irkutsk                  | 3        | 1.53%   |
| Barnaul                  | 3        | 1.53%   |
| Yekaterinburg            | 2        | 1.02%   |
| Sevastopol               | 2        | 1.02%   |
| Saratov                  | 2        | 1.02%   |
| Rostov-on-Don            | 2        | 1.02%   |
| Perm                     | 2        | 1.02%   |
| Obninsk                  | 2        | 1.02%   |
| Kaliningrad              | 2        | 1.02%   |
| Chelyabinsk              | 2        | 1.02%   |
| Zelenodolsk              | 1        | 0.51%   |
| Yessentuki               | 1        | 0.51%   |
| Vologda                  | 1        | 0.51%   |
| Vladivostok              | 1        | 0.51%   |
| Verkhnyaya Pyshma        | 1        | 0.51%   |
| Vergina                  | 1        | 0.51%   |
| Valuyki                  | 1        | 0.51%   |
| Ulyanovsk                | 1        | 0.51%   |
| Tula                     | 1        | 0.51%   |
| Tolyatti                 | 1        | 0.51%   |
| Thessaloniki             | 1        | 0.51%   |
| Taraz                    | 1        | 0.51%   |
| Tambov                   | 1        | 0.51%   |
| Surgut                   | 1        | 0.51%   |
| Stavropol                | 1        | 0.51%   |
| Shenzhen                 | 1        | 0.51%   |
| Pushchino                | 1        | 0.51%   |
| Protvino                 | 1        | 0.51%   |
| Polyarnyy                | 1        | 0.51%   |
| Petropavlovsk-Kamchatsky | 1        | 0.51%   |
| Nizhny Tagil             | 1        | 0.51%   |
| Nizhniy Novgorod         | 1        | 0.51%   |
| Murmansk                 | 1        | 0.51%   |
| Monchegorsk              | 1        | 0.51%   |
| Mogilev                  | 1        | 0.51%   |
| Lipetsk                  | 1        | 0.51%   |
| Kyzyl                    | 1        | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 53       | 78     | 20.62%  |
| Seagate                   | 35       | 59     | 13.62%  |
| Samsung Electronics       | 30       | 35     | 11.67%  |
| Toshiba                   | 27       | 43     | 10.51%  |
| AXIOMTEK                  | 26       | 26     | 10.12%  |
| Kingston                  | 21       | 23     | 8.17%   |
| China                     | 8        | 8      | 3.11%   |
| Apacer                    | 7        | 10     | 2.72%   |
| Hitachi                   | 6        | 7      | 2.33%   |
| A-DATA Technology         | 6        | 6      | 2.33%   |
| XPG                       | 3        | 3      | 1.17%   |
| Patriot                   | 3        | 3      | 1.17%   |
| Intel                     | 3        | 7      | 1.17%   |
| SPCC                      | 2        | 2      | 0.78%   |
| Smartbuy                  | 2        | 2      | 0.78%   |
| Plextor                   | 2        | 2      | 0.78%   |
| Phison                    | 2        | 2      | 0.78%   |
| Gigabyte Technology       | 2        | 2      | 0.78%   |
| DEPO                      | 2        | 2      | 0.78%   |
| Crucial                   | 2        | 2      | 0.78%   |
| TMI                       | 1        | 1      | 0.39%   |
| Team                      | 1        | 1      | 0.39%   |
| SP-8                      | 1        | 1      | 0.39%   |
| SINTECHI                  | 1        | 1      | 0.39%   |
| SanDisk                   | 1        | 1      | 0.39%   |
| OCZ                       | 1        | 1      | 0.39%   |
| Micron/Crucial Technology | 1        | 1      | 0.39%   |
| Micron Technology         | 1        | 1      | 0.39%   |
| LITEON                    | 1        | 1      | 0.39%   |
| KingSpec                  | 1        | 1      | 0.39%   |
| JMicron Technology        | 1        | 1      | 0.39%   |
| HEORIADY                  | 1        | 1      | 0.39%   |
| Foxline                   | 1        | 1      | 0.39%   |
| Corsair                   | 1        | 1      | 0.39%   |
| AMD                       | 1        | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD   | 26       | 9.45%   |
| Samsung MZVLW128HEGR-00000 128GB       | 17       | 6.18%   |
| Toshiba HDWD120 2TB                    | 13       | 4.73%   |
| WDC WD5000AZLX-21K2TA0 500GB           | 10       | 3.64%   |
| Toshiba HDWD110 1TB                    | 5        | 1.82%   |
| Kingston SV300S37A120G 120GB SSD       | 4        | 1.45%   |
| Kingston RBUSC180S37256GJ 256GB SSD    | 4        | 1.45%   |
| Apacer AS350 256GB SSD                 | 4        | 1.45%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 3        | 1.09%   |
| Toshiba DT01ACA100 1TB                 | 3        | 1.09%   |
| Seagate ST1000DM010-2EP102 1TB         | 3        | 1.09%   |
| Samsung SSD 860 EVO 250GB              | 3        | 1.09%   |
| Kingston SA400S37120G 120GB SSD        | 3        | 1.09%   |
| XPG GAMMIX S5 512GB                    | 2        | 0.73%   |
| WDC WD3200AAKS-00G3A0 320GB            | 2        | 0.73%   |
| WDC WD2000FYYZ-01UL1B1 2TB             | 2        | 0.73%   |
| WDC WD10PURZ-85U8XY0 1TB               | 2        | 0.73%   |
| WDC WD10JPVX-00JC3T0 1TB               | 2        | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2        | 0.73%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB     | 2        | 0.73%   |
| Seagate ST500LM030-2E717D 500GB        | 2        | 0.73%   |
| Seagate ST500DM002-1BC142 500GB        | 2        | 0.73%   |
| Seagate ST380815AS 80GB                | 2        | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB         | 2        | 0.73%   |
| Seagate ST1000LM049-2GH172 1TB         | 2        | 0.73%   |
| Samsung SSD 860 EVO 500GB              | 2        | 0.73%   |
| Phison M.2 128GB SSO128GTLCG-SBC-2 SSD | 2        | 0.73%   |
| Kingston SA400S37240G 240GB SSD        | 2        | 0.73%   |
| Hitachi HDS723020BLA642 2TB            | 2        | 0.73%   |
| Hitachi HDS721025CLA382 250GB          | 2        | 0.73%   |
| DEPO SM3DT-120 120GB SSD               | 2        | 0.73%   |
| China SSD 128GB                        | 2        | 0.73%   |
| Apacer AS350 240GB SSD                 | 2        | 0.73%   |
| XPG SPECTRIX S40G 512GB                | 1        | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1        | 0.36%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1        | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 1        | 0.36%   |
| WDC WD800AAJS-00WAA0 80GB              | 1        | 0.36%   |
| WDC WD7501AALS-00E3A0 752GB            | 1        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 45       | 69     | 39.13%  |
| Seagate             | 33       | 54     | 28.7%   |
| Toshiba             | 27       | 42     | 23.48%  |
| Hitachi             | 6        | 7      | 5.22%   |
| Samsung Electronics | 3        | 3      | 2.61%   |
| SINTECHI            | 1        | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| AXIOMTEK            | 26       | 26     | 23.85%  |
| Kingston            | 19       | 20     | 17.43%  |
| China               | 8        | 8      | 7.34%   |
| WDC                 | 7        | 7      | 6.42%   |
| Samsung Electronics | 7        | 9      | 6.42%   |
| Apacer              | 7        | 10     | 6.42%   |
| A-DATA Technology   | 5        | 5      | 4.59%   |
| Patriot             | 3        | 3      | 2.75%   |
| Smartbuy            | 2        | 2      | 1.83%   |
| Seagate             | 2        | 5      | 1.83%   |
| Plextor             | 2        | 2      | 1.83%   |
| Phison              | 2        | 2      | 1.83%   |
| Intel               | 2        | 5      | 1.83%   |
| DEPO                | 2        | 2      | 1.83%   |
| Crucial             | 2        | 2      | 1.83%   |
| TMI                 | 1        | 1      | 0.92%   |
| Team                | 1        | 1      | 0.92%   |
| SP-8                | 1        | 1      | 0.92%   |
| SanDisk             | 1        | 1      | 0.92%   |
| OCZ                 | 1        | 1      | 0.92%   |
| LITEON              | 1        | 1      | 0.92%   |
| KingSpec            | 1        | 1      | 0.92%   |
| JMicron Technology  | 1        | 1      | 0.92%   |
| HEORIADY            | 1        | 1      | 0.92%   |
| Gigabyte Technology | 1        | 1      | 0.92%   |
| Foxline             | 1        | 1      | 0.92%   |
| Corsair             | 1        | 1      | 0.92%   |
| AMD                 | 1        | 1      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 100      | 176    | 42.92%  |
| SSD  | 98       | 121    | 42.06%  |
| NVMe | 35       | 40     | 15.02%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 167      | 295    | 81.86%  |
| NVMe | 35       | 40     | 17.16%  |
| SAS  | 2        | 2      | 0.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 133      | 172    | 64.88%  |
| 0.51-1.0   | 41       | 62     | 20%     |
| 1.01-2.0   | 27       | 58     | 13.17%  |
| 2.01-3.0   | 3        | 4      | 1.46%   |
| 4.01-10.0  | 1        | 1      | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 93       | 47.45%  |
| 251-500        | 30       | 15.31%  |
| 1001-2000      | 28       | 14.29%  |
| 501-1000       | 13       | 6.63%   |
| 21-50          | 8        | 4.08%   |
| More than 3000 | 7        | 3.57%   |
| 51-100         | 7        | 3.57%   |
| 1-20           | 5        | 2.55%   |
| 2001-3000      | 4        | 2.04%   |
| Unknown        | 1        | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 111      | 56.35%  |
| 21-50          | 29       | 14.72%  |
| 101-250        | 15       | 7.61%   |
| 51-100         | 15       | 7.61%   |
| 501-1000       | 11       | 5.58%   |
| 251-500        | 7        | 3.55%   |
| More than 3000 | 3        | 1.52%   |
| 1001-2000      | 3        | 1.52%   |
| 2001-3000      | 2        | 1.02%   |
| Unknown        | 1        | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD7501AALS-00E3A0 752GB           | 1        | 1      | 4.55%   |
| WDC WD7500AAKS-00RBA0 752GB           | 1        | 2      | 4.55%   |
| WDC WD3200AAKS-00V1A0 320GB           | 1        | 1      | 4.55%   |
| WDC WD2500KS-00MJB0 250GB             | 1        | 1      | 4.55%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1        | 3      | 4.55%   |
| WDC WD20EARX-008FB0 2TB               | 1        | 1      | 4.55%   |
| WDC WD1003FBYX-01Y7B0 1TB             | 1        | 1      | 4.55%   |
| Seagate ST9250315AS 250GB             | 1        | 1      | 4.55%   |
| Seagate ST380815AS 80GB               | 1        | 1      | 4.55%   |
| Seagate ST380811AS 80GB               | 1        | 1      | 4.55%   |
| Seagate ST3320418AS 320GB             | 1        | 1      | 4.55%   |
| Seagate ST32000641AS 2TB              | 1        | 2      | 4.55%   |
| Seagate ST3000DM001-1CH166 3TB        | 1        | 1      | 4.55%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 2      | 4.55%   |
| Seagate ST1000DL004 HD105SI 1TB       | 1        | 1      | 4.55%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 4.55%   |
| Hitachi HUA722010CLA330 1TB           | 1        | 1      | 4.55%   |
| Hitachi HTS545050KTA300 500GB         | 1        | 2      | 4.55%   |
| Hitachi HDS723020BLA642 2TB           | 1        | 1      | 4.55%   |
| Hitachi HDS721025CLA382 250GB         | 1        | 1      | 4.55%   |
| DEPO SM3DT-120 120GB SSD              | 1        | 1      | 4.55%   |
| Corsair Force LS SSD 240GB            | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 10     | 36.36%  |
| WDC                 | 7        | 10     | 31.82%  |
| Hitachi             | 4        | 5      | 18.18%  |
| Samsung Electronics | 1        | 1      | 4.55%   |
| DEPO                | 1        | 1      | 4.55%   |
| Corsair             | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 8        | 10     | 42.11%  |
| WDC     | 7        | 10     | 36.84%  |
| Hitachi | 4        | 5      | 21.05%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 25     | 85%     |
| SSD  | 3        | 3      | 15%     |

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
| Works    | 157      | 252    | 75.12%  |
| Detected | 31       | 56     | 14.83%  |
| Malfunc  | 20       | 28     | 9.57%   |
| Failed   | 1        | 1      | 0.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 140      | 58.58%  |
| AMD                          | 39       | 16.32%  |
| Samsung Electronics          | 20       | 8.37%   |
| Nvidia                       | 8        | 3.35%   |
| JMicron Technology           | 5        | 2.09%   |
| Realtek Semiconductor        | 4        | 1.67%   |
| ASMedia Technology           | 4        | 1.67%   |
| Marvell Technology Group     | 3        | 1.26%   |
| Kingston Technology Company  | 3        | 1.26%   |
| SanDisk                      | 2        | 0.84%   |
| Phison Electronics           | 2        | 0.84%   |
| MCST                         | 2        | 0.84%   |
| Zhaoxin                      | 1        | 0.42%   |
| VIA Technologies             | 1        | 0.42%   |
| Toshiba America Info Systems | 1        | 0.42%   |
| Silicon Motion               | 1        | 0.42%   |
| Micron/Crucial Technology    | 1        | 0.42%   |
| Micron Technology            | 1        | 0.42%   |
| LSI Logic / Symbios Logic    | 1        | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 65       | 22.57%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 30       | 10.42%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 17       | 5.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 17       | 5.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 3.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 2.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4        | 1.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.39%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.39%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3        | 1.04%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 1.04%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 1.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.69%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2        | 0.69%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 0.69%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.69%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 0.69%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 2        | 0.69%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 2        | 0.69%   |
| Nvidia MCP51 IDE                                                                        | 2        | 0.69%   |
| MCST SATA                                                                               | 2        | 0.69%   |
| MCST IDE controller                                                                     | 2        | 0.69%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.69%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.69%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 0.69%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.69%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 165      | 69.33%  |
| NVMe | 35       | 14.71%  |
| IDE  | 35       | 14.71%  |
| RAID | 3        | 1.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 142      | 74.35%  |
| AMD          | 46       | 24.08%  |
| E8C/EATX     | 1        | 0.52%   |
| E8C-SWTX     | 1        | 0.52%   |
| CentaurHauls | 1        | 0.52%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-6100TE CPU @ 2.70GHz          | 43       | 22.28%  |
| AMD Ryzen 5 1600 Six-Core Processor         | 13       | 6.74%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 10       | 5.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4        | 2.07%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 4        | 2.07%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 2.07%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.55%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3        | 1.55%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 3        | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3        | 1.55%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 2        | 1.04%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 1.04%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 2        | 1.04%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 1.04%   |
| Intel Genuine CPU 0000 @ 2.40GHz            | 2        | 1.04%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.04%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.04%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 1.04%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.04%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 1.04%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.04%   |
| Intel 11th Gen Core i5-11500 @ 2.70GHz      | 2        | 1.04%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.04%   |
| AMD Athlon 64 X2 Dual Core Processor 4800+  | 2        | 1.04%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.04%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 2        | 1.04%   |
| Intel Xeon D-2177NT CPU @ 1.90GHz           | 1        | 0.52%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.52%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.52%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.52%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.52%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.52%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.52%   |
| Intel Pentium CPU G4500 @ 3.50GHz           | 1        | 0.52%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.52%   |
| Intel Genuine CPU 0000 @ 3.40GHz            | 1        | 0.52%   |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1        | 0.52%   |
| Intel Core i9-10980XE CPU @ 3.00GHz         | 1        | 0.52%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 62       | 32.29%  |
| Intel Core i5           | 18       | 9.38%   |
| AMD Ryzen 5             | 18       | 9.38%   |
| Intel Pentium           | 13       | 6.77%   |
| Other                   | 12       | 6.25%   |
| Intel Celeron           | 11       | 5.73%   |
| Intel Pentium Dual-Core | 5        | 2.6%    |
| AMD Ryzen 7             | 5        | 2.6%    |
| Intel Core i7           | 4        | 2.08%   |
| Intel Core 2 Duo        | 4        | 2.08%   |
| AMD Athlon 64 X2        | 4        | 2.08%   |
| Intel Xeon              | 3        | 1.56%   |
| Intel Pentium Gold      | 3        | 1.56%   |
| Intel Genuine           | 3        | 1.56%   |
| AMD A8                  | 3        | 1.56%   |
| AMD A10                 | 3        | 1.56%   |
| Intel Core i9           | 2        | 1.04%   |
| Intel Core 2 Quad       | 2        | 1.04%   |
| AMD Ryzen 3             | 2        | 1.04%   |
| AMD Phenom II X4        | 2        | 1.04%   |
| AMD FX                  | 2        | 1.04%   |
| AMD Athlon              | 2        | 1.04%   |
| Intel Pentium D         | 1        | 0.52%   |
| Intel Pentium 4         | 1        | 0.52%   |
| Intel Celeron D         | 1        | 0.52%   |
| AMD Sempron             | 1        | 0.52%   |
| AMD Ryzen 7 PRO         | 1        | 0.52%   |
| AMD Ryzen 5 PRO         | 1        | 0.52%   |
| AMD Athlon II X4        | 1        | 0.52%   |
| AMD Athlon 64           | 1        | 0.52%   |
| AMD A6                  | 1        | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 100      | 52.08%  |
| 4      | 44       | 22.92%  |
| 6      | 26       | 13.54%  |
| 8      | 11       | 5.73%   |
| 1      | 5        | 2.6%    |
| 3      | 2        | 1.04%   |
| 32     | 1        | 0.52%   |
| 18     | 1        | 0.52%   |
| 16     | 1        | 0.52%   |
| 14     | 1        | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 188      | 98.43%  |
| 2      | 2        | 1.05%   |
| 4      | 1        | 0.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 131      | 68.59%  |
| 1      | 60       | 31.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 188      | 98.43%  |
| Unknown        | 2        | 1.05%   |
| 32-bit         | 1        | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 49       | 25.39%  |
| Unknown    | 35       | 18.13%  |
| 0x906e9    | 13       | 6.74%   |
| 0x08001138 | 13       | 6.74%   |
| 0x1067a    | 9        | 4.66%   |
| 0xa0653    | 7        | 3.63%   |
| 0xa0671    | 5        | 2.59%   |
| 0x906eb    | 5        | 2.59%   |
| 0x906ea    | 5        | 2.59%   |
| 0x08108109 | 5        | 2.59%   |
| 0x306a9    | 4        | 2.07%   |
| 0x806e9    | 3        | 1.55%   |
| 0x806c1    | 3        | 1.55%   |
| 0x206a7    | 3        | 1.55%   |
| 0x06001119 | 3        | 1.55%   |
| 0x906ed    | 2        | 1.04%   |
| 0x306c3    | 2        | 1.04%   |
| 0x30679    | 2        | 1.04%   |
| 0x0a50000c | 2        | 1.04%   |
| 0x08701021 | 2        | 1.04%   |
| 0x010000db | 2        | 1.04%   |
| 0xf47      | 1        | 0.52%   |
| 0xf29      | 1        | 0.52%   |
| 0x806ec    | 1        | 0.52%   |
| 0x6fb      | 1        | 0.52%   |
| 0x506e8    | 1        | 0.52%   |
| 0x506c9    | 1        | 0.52%   |
| 0x50657    | 1        | 0.52%   |
| 0x50654    | 1        | 0.52%   |
| 0x306e4    | 1        | 0.52%   |
| 0x206c2    | 1        | 0.52%   |
| 0x20655    | 1        | 0.52%   |
| 0x10661    | 1        | 0.52%   |
| 0x08108102 | 1        | 0.52%   |
| 0x0810100b | 1        | 0.52%   |
| 0x0800820d | 1        | 0.52%   |
| 0x08001129 | 1        | 0.52%   |
| 0x06000852 | 1        | 0.52%   |
| 0x010000c8 | 1        | 0.52%   |
| 0x00000000 | 1        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Skylake     | 55       | 28.65%  |
| KabyLake    | 31       | 16.15%  |
| Zen         | 15       | 7.81%   |
| Penryn      | 10       | 5.21%   |
| Unknown     | 9        | 4.69%   |
| Zen+        | 8        | 4.17%   |
| CometLake   | 8        | 4.17%   |
| IvyBridge   | 7        | 3.65%   |
| Piledriver  | 6        | 3.13%   |
| K8 Hammer   | 6        | 3.13%   |
| SandyBridge | 5        | 2.6%    |
| Silvermont  | 4        | 2.08%   |
| Haswell     | 4        | 2.08%   |
| Zen 2       | 3        | 1.56%   |
| TigerLake   | 3        | 1.56%   |
| NetBurst    | 3        | 1.56%   |
| K10         | 3        | 1.56%   |
| Zen 3       | 2        | 1.04%   |
| Westmere    | 2        | 1.04%   |
| Steamroller | 2        | 1.04%   |
| Icelake     | 2        | 1.04%   |
| Core        | 2        | 1.04%   |
| K10 Llano   | 1        | 0.52%   |
| Goldmont    | 1        | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 112      | 56.57%  |
| Nvidia            | 52       | 26.26%  |
| AMD               | 29       | 14.65%  |
| Silicon Motion    | 2        | 1.01%   |
| ASPEED Technology | 2        | 1.01%   |
| Zhaoxin           | 1        | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                     | 47       | 23.15%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 18       | 8.87%   |
| Intel HD Graphics 610                                                     | 10       | 4.93%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 9        | 4.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 7        | 3.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 6        | 2.96%   |
| Intel HD Graphics 510                                                     | 5        | 2.46%   |
| Nvidia GK208B [GeForce GT 710]                                            | 4        | 1.97%   |
| Intel HD Graphics 620                                                     | 4        | 1.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4        | 1.97%   |
| Nvidia GF108 [GeForce GT 630]                                             | 3        | 1.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3        | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3        | 1.48%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                         | 3        | 1.48%   |
| Silicon Motion SM718 LynxSE+                                              | 2        | 0.99%   |
| Nvidia GF119 [GeForce GT 610]                                             | 2        | 0.99%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                 | 2        | 0.99%   |
| Intel HD Graphics 630                                                     | 2        | 0.99%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                 | 2        | 0.99%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 2        | 0.99%   |
| ASPEED Technology ASPEED Graphics Family                                  | 2        | 0.99%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series] (Secondary)                     | 2        | 0.99%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series]                                 | 2        | 0.99%   |
| AMD Kaveri [Radeon R7 Graphics]                                           | 2        | 0.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 2        | 0.99%   |
| Zhaoxin ZX-E C-960 GPU                                                    | 1        | 0.49%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1        | 0.49%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                     | 1        | 0.49%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                      | 1        | 0.49%   |
| Nvidia GT218 [GeForce 210]                                                | 1        | 0.49%   |
| Nvidia GP107GL [Quadro P400]                                              | 1        | 0.49%   |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1        | 0.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1        | 0.49%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                       | 1        | 0.49%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                        | 1        | 0.49%   |
| Nvidia GM204 [GeForce GTX 980]                                            | 1        | 0.49%   |
| Nvidia GM107 [GeForce GTX 750]                                            | 1        | 0.49%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 0.49%   |
| Nvidia GK106 [GeForce GTX 660]                                            | 1        | 0.49%   |
| Nvidia GK106 [GeForce GTX 650 Ti Boost]                                   | 1        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 107      | 56.02%  |
| 1 x Nvidia         | 50       | 26.18%  |
| 1 x AMD            | 23       | 12.04%  |
| 2 x AMD            | 4        | 2.09%   |
| 1 x Silicon Motion | 2        | 1.05%   |
| 1 x ASPEED         | 2        | 1.05%   |
| Nvidia + Zhaoxin   | 1        | 0.52%   |
| Intel + Nvidia     | 1        | 0.52%   |
| Intel + AMD        | 1        | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 147      | 76.56%  |
| Proprietary | 40       | 20.83%  |
| Unknown     | 5        | 2.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 122      | 63.54%  |
| 3.01-4.0   | 23       | 11.98%  |
| 1.01-2.0   | 15       | 7.81%   |
| 0.51-1.0   | 13       | 6.77%   |
| 0.01-0.5   | 13       | 6.77%   |
| 7.01-8.0   | 2        | 1.04%   |
| 8.01-16.0  | 2        | 1.04%   |
| 5.01-6.0   | 1        | 0.52%   |
| 2.01-3.0   | 1        | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| HHT                  | 43       | 22.05%  |
| Acer                 | 24       | 12.31%  |
| Samsung Electronics  | 21       | 10.77%  |
| AOC                  | 21       | 10.77%  |
| BenQ                 | 20       | 10.26%  |
| Goldstar             | 11       | 5.64%   |
| ViewSonic            | 8        | 4.1%    |
| Dell                 | 7        | 3.59%   |
| Philips              | 6        | 3.08%   |
| Ancor Communications | 5        | 2.56%   |
| PRW                  | 4        | 2.05%   |
| WBT                  | 3        | 1.54%   |
| LG Electronics       | 3        | 1.54%   |
| STD                  | 2        | 1.03%   |
| Iiyama               | 2        | 1.03%   |
| Hewlett-Packard      | 2        | 1.03%   |
| VIE                  | 1        | 0.51%   |
| Toshiba              | 1        | 0.51%   |
| SKG                  | 1        | 0.51%   |
| Plain Tree Systems   | 1        | 0.51%   |
| MSI                  | 1        | 0.51%   |
| Lenovo               | 1        | 0.51%   |
| JRY                  | 1        | 0.51%   |
| HIB                  | 1        | 0.51%   |
| HannStar             | 1        | 0.51%   |
| DZW                  | 1        | 0.51%   |
| ASUSTek Computer     | 1        | 0.51%   |
| Apple                | 1        | 0.51%   |
| Unknown              | 1        | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HHT ActviPanel V5 HHT0030 3840x2160 944x398mm 40.3-inch               | 43       | 21.39%  |
| AOC LCD Monitor 2778X 2560x1440                                       | 11       | 5.47%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                     | 10       | 4.98%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 7        | 3.48%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 5        | 2.49%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 4        | 1.99%   |
| PRW AP7_Titanium PRW4200 3840x2160                                    | 4        | 1.99%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                      | 3        | 1.49%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2        | 1%      |
| STD LCD Monitor STD0001 1920x1080                                     | 2        | 1%      |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 2        | 1%      |
| Samsung Electronics S22E391 SAM0C0E 1920x1080 477x268mm 21.5-inch     | 2        | 1%      |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                | 2        | 1%      |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2        | 1%      |
| BenQ EW3270U BNQ7950 3840x2160 700x390mm 31.5-inch                    | 2        | 1%      |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                      | 2        | 1%      |
| AOC 22P1W AOC2201 1920x1080 477x268mm 21.5-inch                       | 2        | 1%      |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                       | 2        | 1%      |
| ViewSonic VA1916w-6 VSCF91F 1440x900 410x256mm 19.0-inch              | 1        | 0.5%    |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch           | 1        | 0.5%    |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 0.5%    |
| Toshiba LCD Monitor TV 1920x1080                                      | 1        | 0.5%    |
| SKG 86 Monitor SKG8600 3840x2160 1650x928mm 74.5-inch                 | 1        | 0.5%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM0611 1920x1080 604x342mm 27.3-inch  | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM01CF 1600x1200 432x324mm 21.3-inch  | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1        | 0.5%    |
| Samsung Electronics SMS22A450 SAM0836 1680x1050 459x296mm 21.5-inch   | 1        | 0.5%    |
| Samsung Electronics S27E370D SAM0CF3 1920x1080 598x336mm 27.0-inch    | 1        | 0.5%    |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 1        | 0.5%    |
| Samsung Electronics S24B370 SAM08DE 1920x1080 531x299mm 24.0-inch     | 1        | 0.5%    |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1        | 0.5%    |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 0.5%    |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1        | 0.5%    |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1        | 0.5%    |
| Samsung Electronics EPSON PJ SECA60D 1920x1080                        | 1        | 0.5%    |
| Samsung Electronics C27JG5x SAM0F58 2560x1440 597x336mm 27.0-inch     | 1        | 0.5%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 77       | 40.31%  |
| 3840x2160 (4K)     | 55       | 28.8%   |
| 2560x1440 (QHD)    | 23       | 12.04%  |
| 1280x1024 (SXGA)   | 16       | 8.38%   |
| 1680x1050 (WSXGA+) | 4        | 2.09%   |
| 1600x900 (HD+)     | 3        | 1.57%   |
| 1440x900 (WXGA+)   | 3        | 1.57%   |
| 1366x768 (WXGA)    | 2        | 1.05%   |
| Unknown            | 2        | 1.05%   |
| 4480x1440          | 1        | 0.52%   |
| 3840x1600          | 1        | 0.52%   |
| 1920x1200 (WUXGA)  | 1        | 0.52%   |
| 1600x1200          | 1        | 0.52%   |
| 1360x768           | 1        | 0.52%   |
| 1280x720 (HD)      | 1        | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 40      | 43       | 22.4%   |
| 24      | 31       | 16.15%  |
| Unknown | 25       | 13.02%  |
| 21      | 21       | 10.94%  |
| 23      | 20       | 10.42%  |
| 27      | 13       | 6.77%   |
| 19      | 11       | 5.73%   |
| 17      | 9        | 4.69%   |
| 31      | 5        | 2.6%    |
| 26      | 3        | 1.56%   |
| 22      | 2        | 1.04%   |
| 74      | 1        | 0.52%   |
| 72      | 1        | 0.52%   |
| 46      | 1        | 0.52%   |
| 37      | 1        | 0.52%   |
| 33      | 1        | 0.52%   |
| 32      | 1        | 0.52%   |
| 28      | 1        | 0.52%   |
| 20      | 1        | 0.52%   |
| 18      | 1        | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 63       | 33.33%  |
| 901-1000    | 43       | 22.75%  |
| 401-500     | 28       | 14.81%  |
| Unknown     | 25       | 13.23%  |
| 601-700     | 9        | 4.76%   |
| 301-350     | 9        | 4.76%   |
| 351-400     | 6        | 3.17%   |
| 701-800     | 2        | 1.06%   |
| 1501-2000   | 2        | 1.06%   |
| 801-900     | 1        | 0.53%   |
| 1001-1500   | 1        | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 94       | 51.09%  |
| 21/9    | 44       | 23.91%  |
| Unknown | 21       | 11.41%  |
| 5/4     | 15       | 8.15%   |
| 16/10   | 8        | 4.35%   |
| 4/3     | 1        | 0.54%   |
| 3/2     | 1        | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 64       | 33.86%  |
| 501-1000       | 45       | 23.81%  |
| Unknown        | 25       | 13.23%  |
| 151-200        | 17       | 8.99%   |
| 301-350        | 16       | 8.47%   |
| 141-150        | 10       | 5.29%   |
| 351-500        | 8        | 4.23%   |
| More than 1000 | 2        | 1.06%   |
| 251-300        | 2        | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 80       | 42.11%  |
| 101-120 | 67       | 35.26%  |
| Unknown | 25       | 13.16%  |
| 121-160 | 13       | 6.84%   |
| 1-50    | 4        | 2.11%   |
| 161-240 | 1        | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 169      | 87.56%  |
| 2     | 14       | 7.25%   |
| 0     | 9        | 4.66%   |
| 3     | 1        | 0.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 155      | 58.49%  |
| Intel                      | 72       | 27.17%  |
| Qualcomm Atheros           | 12       | 4.53%   |
| Nvidia                     | 7        | 2.64%   |
| TP-Link                    | 3        | 1.13%   |
| Microchip Technology       | 3        | 1.13%   |
| Ralink Technology          | 2        | 0.75%   |
| Ralink                     | 2        | 0.75%   |
| MCST                       | 2        | 0.75%   |
| ZTE WCDMA Technologies MSM | 1        | 0.38%   |
| Xiaomi                     | 1        | 0.38%   |
| Vimtron Electronics        | 1        | 0.38%   |
| VIA Technologies           | 1        | 0.38%   |
| U-Blox                     | 1        | 0.38%   |
| D-Link                     | 1        | 0.38%   |
| Broadcom Limited           | 1        | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94       | 32.3%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 43       | 14.78%  |
| Intel Ethernet Connection I219-LM                                 | 31       | 10.65%  |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 5.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.06%   |
| Intel Wireless 3165                                               | 6        | 2.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 1.37%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 1.37%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3        | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.03%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.03%   |
| Microchip MCP2221 USB-I2C/UART Combo                              | 3        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.03%   |
| Intel Ethernet Connection (13) I219-V                             | 3        | 1.03%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2        | 0.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.69%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.69%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.69%   |
| Intel Wireless-AC 9260                                            | 2        | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 0.69%   |
| Intel I211 Gigabit Network Connection                             | 2        | 0.69%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2        | 0.69%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1        | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.34%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.34%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.34%   |
| U-Blox [u-blox 7]                                                 | 1        | 0.34%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.34%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.34%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.34%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.34%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.34%   |
| Realtek 802.11ac NIC                                              | 1        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 38.89%  |
| Realtek Semiconductor | 12       | 33.33%  |
| TP-Link               | 3        | 8.33%   |
| Qualcomm Atheros      | 3        | 8.33%   |
| Ralink Technology     | 2        | 5.56%   |
| Ralink                | 2        | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                        | 6        | 16.67%  |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 3        | 8.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 3        | 8.33%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 2        | 5.56%   |
| Intel Wireless-AC 9260                                     | 2        | 5.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 2        | 5.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 2        | 5.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 2.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1        | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 2.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1        | 2.78%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 2.78%   |
| Realtek 802.11ac NIC                                       | 1        | 2.78%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 2.78%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 2.78%   |
| Ralink RT5392 PCIe Wireless Network Adapter                | 1        | 2.78%   |
| Ralink RT2561/RT61 rev B 802.11g                           | 1        | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 2.78%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 2.78%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 2.78%   |
| Intel Centrino Wireless-N 2230                             | 1        | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 153      | 62.2%   |
| Intel                      | 68       | 27.64%  |
| Qualcomm Atheros           | 9        | 3.66%   |
| Nvidia                     | 7        | 2.85%   |
| MCST                       | 2        | 0.81%   |
| ZTE WCDMA Technologies MSM | 1        | 0.41%   |
| Xiaomi                     | 1        | 0.41%   |
| Vimtron Electronics        | 1        | 0.41%   |
| VIA Technologies           | 1        | 0.41%   |
| TP-Link                    | 1        | 0.41%   |
| D-Link                     | 1        | 0.41%   |
| Broadcom Limited           | 1        | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94       | 37.45%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 43       | 17.13%  |
| Intel Ethernet Connection I219-LM                                 | 31       | 12.35%  |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 6.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 1.59%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.2%    |
| Intel Ethernet Connection (13) I219-V                             | 3        | 1.2%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.8%    |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.8%    |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.8%    |
| Intel I211 Gigabit Network Connection                             | 2        | 0.8%    |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.8%    |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.4%    |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.4%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.4%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.4%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.4%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.4%    |
| Nvidia MCP77 Ethernet                                             | 1        | 0.4%    |
| Nvidia MCP73 Ethernet                                             | 1        | 0.4%    |
| Nvidia MCP61 Ethernet                                             | 1        | 0.4%    |
| Nvidia MCP55 Ethernet                                             | 1        | 0.4%    |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.4%    |
| Intel I350 Gigabit Network Connection                             | 1        | 0.4%    |
| Intel I210 Gigabit Network Connection                             | 1        | 0.4%    |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1        | 0.4%    |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1        | 0.4%    |
| Intel Ethernet Connection I218-V                                  | 1        | 0.4%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.4%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 190      | 82.61%  |
| WiFi     | 36       | 15.65%  |
| Modem    | 4        | 1.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 176      | 91.19%  |
| WiFi     | 17       | 8.81%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 159      | 83.25%  |
| 2     | 28       | 14.66%  |
| 13    | 1        | 0.52%   |
| 8     | 1        | 0.52%   |
| 3     | 1        | 0.52%   |
| 0     | 1        | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 186      | 97.38%  |
| Yes  | 5        | 2.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 14       | 50%     |
| Cambridge Silicon Radio | 6        | 21.43%  |
| Realtek Semiconductor   | 3        | 10.71%  |
| IMC Networks            | 2        | 7.14%   |
| Broadcom                | 2        | 7.14%   |
| Logitech                | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 8        | 28.57%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 21.43%  |
| Realtek Bluetooth Radio                             | 2        | 7.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 7.14%   |
| Intel AX210 Bluetooth                               | 2        | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 3.57%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 3.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 3.57%   |
| Intel AX200 Bluetooth                               | 1        | 3.57%   |
| IMC Networks Bluetooth Radio                        | 1        | 3.57%   |
| IMC Networks Bluetooth Device                       | 1        | 3.57%   |
| Broadcom Bluetooth dongle                           | 1        | 3.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 137      | 55.02%  |
| Nvidia              | 50       | 20.08%  |
| AMD                 | 46       | 18.47%  |
| C-Media Electronics | 4        | 1.61%   |
| MCST                | 2        | 0.8%    |
| JMTek               | 2        | 0.8%    |
| Creative Technology | 2        | 0.8%    |
| Zhaoxin             | 1        | 0.4%    |
| VIA Technologies    | 1        | 0.4%    |
| EasyPass Industrial | 1        | 0.4%    |
| Creative Labs       | 1        | 0.4%    |
| Apple               | 1        | 0.4%    |
| A4Tech              | 1        | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 65       | 23.9%   |
| Nvidia GP107GL High Definition Audio Controller                            | 20       | 7.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 5.51%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 4.04%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 3.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 2.94%   |
| AMD FCH Azalia Controller                                                  | 7        | 2.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 2.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.84%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 1.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.84%   |
| Intel Sunrise Point-LP HD Audio                                            | 4        | 1.47%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 1.47%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3        | 1.1%    |
| Intel Audio device                                                         | 3        | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 1.1%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.1%    |
| AMD Trinity HDMI Audio Controller                                          | 3        | 1.1%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.1%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 2        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.74%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.74%   |
| MCST HD Audio                                                              | 2        | 0.74%   |
| JMTek USB PnP Audio Device                                                 | 2        | 0.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 0.74%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 0.74%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 0.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 0.74%   |
| Zhaoxin ZX-E High Definition Audio Controller                              | 1        | 0.37%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                  | 1        | 0.37%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 29       | 21.17%  |
| Unknown             | 22       | 16.06%  |
| Kingston            | 22       | 16.06%  |
| Samsung Electronics | 14       | 10.22%  |
| Micron Technology   | 14       | 10.22%  |
| SK hynix            | 7        | 5.11%   |
| Foxline             | 4        | 2.92%   |
| Apacer              | 3        | 2.19%   |
| Patriot             | 2        | 1.46%   |
| Goodram             | 2        | 1.46%   |
| Goldkey             | 2        | 1.46%   |
| AMD                 | 2        | 1.46%   |
| A-DATA Technology   | 2        | 1.46%   |
| Wilk                | 1        | 0.73%   |
| Unknown (0x0B7A)    | 1        | 0.73%   |
| tigo                | 1        | 0.73%   |
| Shenzhen Longsys    | 1        | 0.73%   |
| Ramaxel Technology  | 1        | 0.73%   |
| Qumo                | 1        | 0.73%   |
| Juhor               | 1        | 0.73%   |
| Golden Empire       | 1        | 0.73%   |
| G.Skill             | 1        | 0.73%   |
| Elpida              | 1        | 0.73%   |
| Corsair             | 1        | 0.73%   |
| Unknown             | 1        | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Crucial RAM CT4G4DFS824A.M8FF 4096MB DIMM DDR4 2400MT/s          | 13       | 8.61%   |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                         | 10       | 6.62%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s           | 4        | 2.65%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 3        | 1.99%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s           | 3        | 1.99%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2        | 1.32%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2        | 1.32%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2        | 1.32%   |
| Unknown RAM Module 1024MB DIMM                                   | 2        | 1.32%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2        | 1.32%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s              | 2        | 1.32%   |
| Samsung RAM M378A1K43EB2-CVF 8GB DIMM DDR4 2933MT/s              | 2        | 1.32%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s          | 2        | 1.32%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s            | 2        | 1.32%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 2        | 1.32%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s           | 2        | 1.32%   |
| Wilk RAM IRX3000D464L16S/8G 8GB DIMM DDR4 3200MT/s               | 1        | 0.66%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                        | 1        | 0.66%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1        | 0.66%   |
| Unknown RAM Module 4096MB DIMM 333MT/s                           | 1        | 0.66%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1        | 0.66%   |
| Unknown RAM Module 2048MB DIMM SDRAM 533MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1        | 0.66%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                      | 1        | 0.66%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1        | 0.66%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1        | 0.66%   |
| Unknown RAM Module 1024MB DIMM SDRAM 533MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1        | 0.66%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1        | 0.66%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                       | 1        | 0.66%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 1        | 0.66%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1        | 0.66%   |
| Unknown RAM Module 1024MB DIMM 400MT/s                           | 1        | 0.66%   |
| Unknown RAM Module 1024MB DIMM 32MT/s                            | 1        | 0.66%   |
| Unknown (0x0B7A) RAM UDIMM PC4-2666 8G 1R 8GB DIMM DDR4 2667MT/s | 1        | 0.66%   |
| tigo RAM 4GB-2400MHZ 4GB SODIMM DDR4 2400MT/s                    | 1        | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 1        | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 85       | 66.41%  |
| DDR3    | 23       | 17.97%  |
| Unknown | 11       | 8.59%   |
| DDR2    | 4        | 3.13%   |
| SDRAM   | 3        | 2.34%   |
| DDR     | 2        | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 113      | 88.28%  |
| SODIMM | 15       | 11.72%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 55       | 41.04%  |
| 8192  | 50       | 37.31%  |
| 2048  | 10       | 7.46%   |
| 1024  | 10       | 7.46%   |
| 16384 | 5        | 3.73%   |
| 512   | 3        | 2.24%   |
| 32768 | 1        | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 40       | 29.41%  |
| 1600    | 13       | 9.56%   |
| 3200    | 12       | 8.82%   |
| 2667    | 12       | 8.82%   |
| 2133    | 9        | 6.62%   |
| 1333    | 8        | 5.88%   |
| 2933    | 6        | 4.41%   |
| 800     | 4        | 2.94%   |
| 667     | 4        | 2.94%   |
| Unknown | 4        | 2.94%   |
| 400     | 3        | 2.21%   |
| 3600    | 2        | 1.47%   |
| 3066    | 2        | 1.47%   |
| 533     | 2        | 1.47%   |
| 333     | 2        | 1.47%   |
| 4333    | 1        | 0.74%   |
| 3534    | 1        | 0.74%   |
| 3466    | 1        | 0.74%   |
| 3333    | 1        | 0.74%   |
| 3266    | 1        | 0.74%   |
| 3151    | 1        | 0.74%   |
| 2866    | 1        | 0.74%   |
| 2666    | 1        | 0.74%   |
| 1867    | 1        | 0.74%   |
| 1866    | 1        | 0.74%   |
| 1648    | 1        | 0.74%   |
| 1066    | 1        | 0.74%   |
| 32      | 1        | 0.74%   |

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
| Logitech                | 16       | 53.33%  |
| Alcor Micro             | 7        | 23.33%  |
| Z-Star Microelectronics | 1        | 3.33%   |
| Unknown                 | 1        | 3.33%   |
| Microsoft               | 1        | 3.33%   |
| Microdia                | 1        | 3.33%   |
| Hewlett-Packard         | 1        | 3.33%   |
| GEMBIRD                 | 1        | 3.33%   |
| Apple                   | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 10       | 33.33%  |
| Alcor Micro USB 2.0 PC Camera                     | 5        | 16.67%  |
| Logitech C505 HD Webcam                           | 2        | 6.67%   |
| Alcor Micro USB 2.0 Camera                        | 2        | 6.67%   |
| Z-Star Venus USB2.0 Camera                        | 1        | 3.33%   |
| Unknown HD camera                                 | 1        | 3.33%   |
| Microsoft LifeCam VX-700                          | 1        | 3.33%   |
| Microdia Camera                                   | 1        | 3.33%   |
| Logitech Webcam C930e                             | 1        | 3.33%   |
| Logitech HD Webcam C525                           | 1        | 3.33%   |
| Logitech HD Pro Webcam C920                       | 1        | 3.33%   |
| Logitech B525 HD Webcam                           | 1        | 3.33%   |
| HP Webcam HD 2300                                 | 1        | 3.33%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 3.33%   |
| Apple iSight in LED Cinema Display                | 1        | 3.33%   |

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
| 0     | 177      | 91.24%  |
| 1     | 14       | 7.22%   |
| 2     | 2        | 1.03%   |
| 5     | 1        | 0.52%   |

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

