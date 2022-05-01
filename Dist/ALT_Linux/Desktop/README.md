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

Total: 243

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Intel         | SKYBAY                      | [9f0b004c95](https://linux-hardware.org/?probe=9f0b004c95) | Apr 12, 2022 |
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
| AQUARIUS      | AQH410T                     | [351b2e5344](https://linux-hardware.org/?probe=351b2e5344) | Jan 31, 2022 |
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
| ASUSTek       | M5A99X EVO R2.0             | [615b6f5a78](https://linux-hardware.org/?probe=615b6f5a78) | Aug 13, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [624e92e15e](https://linux-hardware.org/?probe=624e92e15e) | Aug 11, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [49e1a59dfe](https://linux-hardware.org/?probe=49e1a59dfe) | Aug 11, 2021 |
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
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [0fa9201a34](https://linux-hardware.org/?probe=0fa9201a34) | Jun 03, 2021 |
| ASRock        | J3455B-ITX                  | [13396a7347](https://linux-hardware.org/?probe=13396a7347) | May 19, 2021 |
| DEPO Compu... | DPH410S                     | [0d1000e904](https://linux-hardware.org/?probe=0d1000e904) | May 14, 2021 |
| DEPO Compu... | DPA320S G10g                | [5ecc011c34](https://linux-hardware.org/?probe=5ecc011c34) | May 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [5fab5adc6b](https://linux-hardware.org/?probe=5fab5adc6b) | Apr 18, 2021 |
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
| ASUSTek       | M5A99X EVO R2.0             | [bf536f43c6](https://linux-hardware.org/?probe=bf536f43c6) | Jan 07, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [ee8a8fec79](https://linux-hardware.org/?probe=ee8a8fec79) | Jan 05, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [16e976d9e5](https://linux-hardware.org/?probe=16e976d9e5) | Jan 02, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [3296ffa017](https://linux-hardware.org/?probe=3296ffa017) | Jan 02, 2021 |
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
| ASRock        | G31M-VS                     | [de62d84a9c](https://linux-hardware.org/?probe=de62d84a9c) | Aug 12, 2020 |
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
| Kometa P10         | 79       | 49.07%  |
| ALT Linux 9.1      | 31       | 19.25%  |
| ALT Linux 9.0      | 15       | 9.32%   |
| ALT Linux 10.0     | 13       | 8.07%   |
| ALT Linux 9.2      | 7        | 4.35%   |
| ALT Linux 5.0.0    | 3        | 1.86%   |
| ALT Linux P8       | 2        | 1.24%   |
| ALT Linux 8.2      | 2        | 1.24%   |
| MOS 10             | 1        | 0.62%   |
| ALT Linux P9       | 1        | 0.62%   |
| ALT Linux P10      | 1        | 0.62%   |
| ALT Linux 8.2.0    | 1        | 0.62%   |
| ALT Linux 8        | 1        | 0.62%   |
| ALT Linux 7.0.5    | 1        | 0.62%   |
| ALT Linux 20201124 | 1        | 0.62%   |
| ALT Linux 20190303 | 1        | 0.62%   |
| ALT Linux 10.0.900 | 1        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ALT Linux | 154      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.109-std-def-alt1       | 49       | 29.52%  |
| 5.10.102-std-def-alt1       | 26       | 15.66%  |
| 5.4.68-std-def-alt1.1       | 7        | 4.22%   |
| 5.15.32-un-def-alt1         | 6        | 3.61%   |
| 5.4.51-std-def-alt1         | 5        | 3.01%   |
| 5.10.82-std-def-alt1        | 4        | 2.41%   |
| 5.4.41-std-def-alt1         | 3        | 1.81%   |
| 5.10.93-std-def-alt1        | 3        | 1.81%   |
| 5.10.35-un-def-alt1         | 3        | 1.81%   |
| 5.10.32-un-def-alt1         | 3        | 1.81%   |
| 4.19.79-std-def-alt1        | 3        | 1.81%   |
| 5.7.19-un-def-alt1          | 2        | 1.2%    |
| 5.4.85-std-def-alt1         | 2        | 1.2%    |
| 5.4.62-std-def-alt1         | 2        | 1.2%    |
| 5.4.28-std-def-alt1         | 2        | 1.2%    |
| 5.4.127-std-def-alt1        | 2        | 1.2%    |
| 5.2.10-un-def-alt1          | 2        | 1.2%    |
| 5.15.15-un-def-alt1         | 2        | 1.2%    |
| 5.15.14-un-def-alt1         | 2        | 1.2%    |
| 5.10.72-std-def-alt1        | 2        | 1.2%    |
| 5.10.17-un-def-alt1         | 2        | 1.2%    |
| 5.9.8-un-def-alt1           | 1        | 0.6%    |
| 5.7.14-un-def-alt1          | 1        | 0.6%    |
| 5.4.94-std-def-alt1         | 1        | 0.6%    |
| 5.4.92-std-def-alt1         | 1        | 0.6%    |
| 5.4.91-elbrus-def-alt2.12.1 | 1        | 0.6%    |
| 5.4.81-std-def-alt1         | 1        | 0.6%    |
| 5.4.58-elbrus-def-alt1.7.0  | 1        | 0.6%    |
| 5.4.35-std-def-alt1         | 1        | 0.6%    |
| 5.4.181-std-def-alt1        | 1        | 0.6%    |
| 5.4.134-std-def-alt1        | 1        | 0.6%    |
| 5.4.123-std-def-alt1        | 1        | 0.6%    |
| 5.4.104-std-def-alt1        | 1        | 0.6%    |
| 5.2.11-un-def-alt1          | 1        | 0.6%    |
| 5.14.21-un-def-alt3         | 1        | 0.6%    |
| 5.14.21-un-def-alt1         | 1        | 0.6%    |
| 5.13.13-un-def-alt1         | 1        | 0.6%    |
| 5.12.19-un-def-alt2         | 1        | 0.6%    |
| 5.10.88-std-def-alt1        | 1        | 0.6%    |
| 5.10.83-std-def-alt0.c9f.2  | 1        | 0.6%    |
| 5.10.54-un-def-alt1.1       | 1        | 0.6%    |
| 5.10.54-std-def-alt2        | 1        | 0.6%    |
| 5.10.52-un-def-alt1         | 1        | 0.6%    |
| 5.10.45-un-def-alt1         | 1        | 0.6%    |
| 5.10.42-un-def-alt1         | 1        | 0.6%    |
| 5.10.110-std-def-alt1       | 1        | 0.6%    |
| 4.9.188-std-def-alt0.M80P.1 | 1        | 0.6%    |
| 4.9.133-std-def-alt0.M80P.1 | 1        | 0.6%    |
| 4.9.128-std-def-alt0.M80P.1 | 1        | 0.6%    |
| 4.20.14-un-def-alt1         | 1        | 0.6%    |
| 4.19.67-std-def-alt1        | 1        | 0.6%    |
| 4.19.182-old-def-alt1       | 1        | 0.6%    |
| 4.19.128-old-def-alt2       | 1        | 0.6%    |
| 4.14.78-un-def-alt0.M80P.1  | 1        | 0.6%    |
| 4.14.71-un-def-alt0.M80P.1  | 1        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.109 | 49       | 29.52%  |
| 5.10.102 | 26       | 15.66%  |
| 5.4.68   | 7        | 4.22%   |
| 5.15.32  | 6        | 3.61%   |
| 5.4.51   | 5        | 3.01%   |
| 5.10.82  | 4        | 2.41%   |
| 5.4.41   | 3        | 1.81%   |
| 5.10.93  | 3        | 1.81%   |
| 5.10.35  | 3        | 1.81%   |
| 5.10.32  | 3        | 1.81%   |
| 4.19.79  | 3        | 1.81%   |
| 5.7.19   | 2        | 1.2%    |
| 5.4.85   | 2        | 1.2%    |
| 5.4.62   | 2        | 1.2%    |
| 5.4.28   | 2        | 1.2%    |
| 5.4.127  | 2        | 1.2%    |
| 5.2.10   | 2        | 1.2%    |
| 5.15.15  | 2        | 1.2%    |
| 5.15.14  | 2        | 1.2%    |
| 5.14.21  | 2        | 1.2%    |
| 5.10.72  | 2        | 1.2%    |
| 5.10.54  | 2        | 1.2%    |
| 5.10.17  | 2        | 1.2%    |
| 5.9.8    | 1        | 0.6%    |
| 5.7.14   | 1        | 0.6%    |
| 5.4.94   | 1        | 0.6%    |
| 5.4.92   | 1        | 0.6%    |
| 5.4.91   | 1        | 0.6%    |
| 5.4.81   | 1        | 0.6%    |
| 5.4.58   | 1        | 0.6%    |
| 5.4.35   | 1        | 0.6%    |
| 5.4.181  | 1        | 0.6%    |
| 5.4.134  | 1        | 0.6%    |
| 5.4.123  | 1        | 0.6%    |
| 5.4.104  | 1        | 0.6%    |
| 5.2.11   | 1        | 0.6%    |
| 5.13.13  | 1        | 0.6%    |
| 5.12.19  | 1        | 0.6%    |
| 5.10.88  | 1        | 0.6%    |
| 5.10.83  | 1        | 0.6%    |
| 5.10.52  | 1        | 0.6%    |
| 5.10.45  | 1        | 0.6%    |
| 5.10.42  | 1        | 0.6%    |
| 5.10.110 | 1        | 0.6%    |
| 4.9.188  | 1        | 0.6%    |
| 4.9.133  | 1        | 0.6%    |
| 4.9.128  | 1        | 0.6%    |
| 4.20.14  | 1        | 0.6%    |
| 4.19.67  | 1        | 0.6%    |
| 4.19.182 | 1        | 0.6%    |
| 4.19.128 | 1        | 0.6%    |
| 4.14.78  | 1        | 0.6%    |
| 4.14.71  | 1        | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 97       | 60.25%  |
| 5.4     | 33       | 20.5%   |
| 5.15    | 8        | 4.97%   |
| 4.19    | 6        | 3.73%   |
| 5.7     | 3        | 1.86%   |
| 5.2     | 3        | 1.86%   |
| 4.9     | 3        | 1.86%   |
| 5.14    | 2        | 1.24%   |
| 4.14    | 2        | 1.24%   |
| 5.9     | 1        | 0.62%   |
| 5.13    | 1        | 0.62%   |
| 5.12    | 1        | 0.62%   |
| 4.20    | 1        | 0.62%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 148      | 96.1%   |
| i686   | 4        | 2.6%    |
| e2k    | 2        | 1.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 112      | 72.26%  |
| Unknown  | 20       | 12.9%   |
| XFCE     | 18       | 11.61%  |
| MATE     | 2        | 1.29%   |
| KDE      | 2        | 1.29%   |
| Cinnamon | 1        | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 149      | 96.75%  |
| Unknown | 5        | 3.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 105      | 67.31%  |
| TDM     | 28       | 17.95%  |
| LightDM | 14       | 8.97%   |
| Unknown | 9        | 5.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 124      | 78.48%  |
| Unknown | 32       | 20.25%  |
| en_US   | 1        | 0.63%   |
| el_GR   | 1        | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 101      | 65.16%  |
| BIOS | 54       | 34.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 145      | 93.55%  |
| Overlay | 8        | 5.16%   |
| Btrfs   | 2        | 1.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 113      | 72.9%   |
| MBR     | 36       | 23.23%  |
| Unknown | 6        | 3.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 88.96%  |
| Yes       | 17       | 11.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 71.97%  |
| Yes       | 44       | 28.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 43       | 27.92%  |
| ASUSTek Computer    | 28       | 18.18%  |
| Gigabyte Technology | 21       | 13.64%  |
| ASRock              | 17       | 11.04%  |
| Acer                | 13       | 8.44%   |
| Unknown             | 9        | 5.84%   |
| MSI                 | 5        | 3.25%   |
| iRU                 | 2        | 1.3%    |
| Hewlett-Packard     | 2        | 1.3%    |
| DEPO Computers      | 2        | 1.3%    |
| VIA Technologies    | 1        | 0.65%   |
| SYS                 | 1        | 0.65%   |
| Supermicro          | 1        | 0.65%   |
| Lenovo              | 1        | 0.65%   |
| Kraftway            | 1        | 0.65%   |
| Foxconn             | 1        | 0.65%   |
| EPoX Computer       | 1        | 0.65%   |
| ECS                 | 1        | 0.65%   |
| Dell                | 1        | 0.65%   |
| Biostar             | 1        | 0.65%   |
| AQUARIUS            | 1        | 0.65%   |
| 3Logic Group        | 1        | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Intel SKYBAY                                       | 42       | 27.27%  |
| ASUS PRIME B450-PLUS                               | 12       | 7.79%   |
| Acer Veriton X2640G                                | 10       | 6.49%   |
| Unknown                                            | 9        | 5.84%   |
| Gigabyte H110M-S2H                                 | 4        | 2.6%    |
| Gigabyte H77M-D3H                                  | 2        | 1.3%    |
| ASUS H110M-R                                       | 2        | 1.3%    |
| Acer Veriton ES2710G                               | 2        | 1.3%    |
| VIA P4M266A-8235                                   | 1        | 0.65%   |
| SYS RAY B101                                       | 1        | 0.65%   |
| Supermicro SYS-1019D-14CN-FHN13TP                  | 1        | 0.65%   |
| MSI MS-7A38                                        | 1        | 0.65%   |
| MSI MS-7996                                        | 1        | 0.65%   |
| MSI MS-7895                                        | 1        | 0.65%   |
| MSI MS-7721                                        | 1        | 0.65%   |
| MSI MPG B560 Trident A (MS-B926)                   | 1        | 0.65%   |
| Lenovo ThinkCentre M73 10B1S15000                  | 1        | 0.65%   |
| Kraftway KWH310                                    | 1        | 0.65%   |
| iRU IRUB365M                                       | 1        | 0.65%   |
| iRU 515                                            | 1        | 0.65%   |
| Intel B75                                          | 1        | 0.65%   |
| HP Compaq dc7600 Convertible Minitower             | 1        | 0.65%   |
| HP 290 G4 Microtower PC                            | 1        | 0.65%   |
| Gigabyte X79-UD3                                   | 1        | 0.65%   |
| Gigabyte P35-S3G                                   | 1        | 0.65%   |
| Gigabyte J1800N-D2H                                | 1        | 0.65%   |
| Gigabyte H510M S2H                                 | 1        | 0.65%   |
| Gigabyte H310N 2.0                                 | 1        | 0.65%   |
| Gigabyte H110M-S2V                                 | 1        | 0.65%   |
| Gigabyte GA-MA69VM-S2                              | 1        | 0.65%   |
| Gigabyte GA-890XA-UD3                              | 1        | 0.65%   |
| Gigabyte G41MT-D3                                  | 1        | 0.65%   |
| Gigabyte G31M-ES2L                                 | 1        | 0.65%   |
| Gigabyte EP35C-DS3R                                | 1        | 0.65%   |
| Gigabyte B550 GAMING X                             | 1        | 0.65%   |
| Gigabyte B450M S2H                                 | 1        | 0.65%   |
| Gigabyte B450 AORUS M                              | 1        | 0.65%   |
| Gigabyte A320M-S2H                                 | 1        | 0.65%   |
| Foxconn Pro 3400 Series MT                         | 1        | 0.65%   |
| EPoX GeForce6100 + nForce410 DDR: 8GF6100-M Series | 1        | 0.65%   |
| ECS T420                                           | 1        | 0.65%   |
| DEPO Computers DPH410S                             | 1        | 0.65%   |
| DEPO Computers DPA320S                             | 1        | 0.65%   |
| Dell OptiPlex 755                                  | 1        | 0.65%   |
| Biostar NF720D A2G+                                | 1        | 0.65%   |
| ASUS Z8NR-D12                                      | 1        | 0.65%   |
| ASUS PRIME H310M-R R2.0                            | 1        | 0.65%   |
| ASUS PRIME B550-PLUS                               | 1        | 0.65%   |
| ASUS PRIME B250-PRO                                | 1        | 0.65%   |
| ASUS PRIME A320M-K                                 | 1        | 0.65%   |
| ASUS P5Q                                           | 1        | 0.65%   |
| ASUS P5G41T-M LX2/GB/LPT                           | 1        | 0.65%   |
| ASUS P5B-MX                                        | 1        | 0.65%   |
| ASUS P5B                                           | 1        | 0.65%   |
| ASUS M5A99X EVO R2.0                               | 1        | 0.65%   |
| ASUS All Series                                    | 1        | 0.65%   |
| ASUS A8N-VM CSM                                    | 1        | 0.65%   |
| ASUS A8N-E                                         | 1        | 0.65%   |
| ASUS A68HM-K                                       | 1        | 0.65%   |
| ASRock Z77 Pro3                                    | 1        | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel SKYBAY                      | 42       | 27.27%  |
| ASUS PRIME                        | 16       | 10.39%  |
| Acer Veriton                      | 12       | 7.79%   |
| Unknown                           | 9        | 5.84%   |
| Gigabyte H110M-S2H                | 4        | 2.6%    |
| Gigabyte H77M-D3H                 | 2        | 1.3%    |
| ASUS H110M-R                      | 2        | 1.3%    |
| VIA P4M266A-8235                  | 1        | 0.65%   |
| SYS RAY                           | 1        | 0.65%   |
| Supermicro SYS-1019D-14CN-FHN13TP | 1        | 0.65%   |
| MSI MS-7A38                       | 1        | 0.65%   |
| MSI MS-7996                       | 1        | 0.65%   |
| MSI MS-7895                       | 1        | 0.65%   |
| MSI MS-7721                       | 1        | 0.65%   |
| MSI MPG                           | 1        | 0.65%   |
| Lenovo ThinkCentre                | 1        | 0.65%   |
| Kraftway KWH310                   | 1        | 0.65%   |
| iRU IRUB365M                      | 1        | 0.65%   |
| iRU 515                           | 1        | 0.65%   |
| Intel B75                         | 1        | 0.65%   |
| HP Compaq                         | 1        | 0.65%   |
| HP 290                            | 1        | 0.65%   |
| Gigabyte X79-UD3                  | 1        | 0.65%   |
| Gigabyte P35-S3G                  | 1        | 0.65%   |
| Gigabyte J1800N-D2H               | 1        | 0.65%   |
| Gigabyte H510M                    | 1        | 0.65%   |
| Gigabyte H310N                    | 1        | 0.65%   |
| Gigabyte H110M-S2V                | 1        | 0.65%   |
| Gigabyte GA-MA69VM-S2             | 1        | 0.65%   |
| Gigabyte GA-890XA-UD3             | 1        | 0.65%   |
| Gigabyte G41MT-D3                 | 1        | 0.65%   |
| Gigabyte G31M-ES2L                | 1        | 0.65%   |
| Gigabyte EP35C-DS3R               | 1        | 0.65%   |
| Gigabyte B550                     | 1        | 0.65%   |
| Gigabyte B450M                    | 1        | 0.65%   |
| Gigabyte B450                     | 1        | 0.65%   |
| Gigabyte A320M-S2H                | 1        | 0.65%   |
| Foxconn Pro                       | 1        | 0.65%   |
| EPoX GeForce6100                  | 1        | 0.65%   |
| ECS T420                          | 1        | 0.65%   |
| DEPO Computers DPH410S            | 1        | 0.65%   |
| DEPO Computers DPA320S            | 1        | 0.65%   |
| Dell OptiPlex                     | 1        | 0.65%   |
| Biostar NF720D                    | 1        | 0.65%   |
| ASUS Z8NR-D12                     | 1        | 0.65%   |
| ASUS P5Q                          | 1        | 0.65%   |
| ASUS P5G41T-M                     | 1        | 0.65%   |
| ASUS P5B-MX                       | 1        | 0.65%   |
| ASUS P5B                          | 1        | 0.65%   |
| ASUS M5A99X                       | 1        | 0.65%   |
| ASUS All                          | 1        | 0.65%   |
| ASUS A8N-VM                       | 1        | 0.65%   |
| ASUS A8N-E                        | 1        | 0.65%   |
| ASUS A68HM-K                      | 1        | 0.65%   |
| ASRock Z77                        | 1        | 0.65%   |
| ASRock X300M-STX                  | 1        | 0.65%   |
| ASRock X299                       | 1        | 0.65%   |
| ASRock N68-GS4                    | 1        | 0.65%   |
| ASRock M3N78D                     | 1        | 0.65%   |
| ASRock J3455B-ITX                 | 1        | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 41       | 26.62%  |
| 2017    | 31       | 20.13%  |
| 2016    | 20       | 12.99%  |
| 2020    | 11       | 7.14%   |
| 2021    | 6        | 3.9%    |
| 2015    | 6        | 3.9%    |
| 2012    | 5        | 3.25%   |
| 2008    | 5        | 3.25%   |
| 2019    | 4        | 2.6%    |
| 2014    | 4        | 2.6%    |
| 2010    | 3        | 1.95%   |
| 2007    | 3        | 1.95%   |
| 2005    | 3        | 1.95%   |
| 2013    | 2        | 1.3%    |
| 2011    | 2        | 1.3%    |
| 2009    | 2        | 1.3%    |
| 2006    | 2        | 1.3%    |
| Unknown | 2        | 1.3%    |
| 2022    | 1        | 0.65%   |
| 2003    | 1        | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 154      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 147      | 95.45%  |
| Enabled  | 7        | 4.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 154      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 73       | 47.4%   |
| 4.01-8.0    | 34       | 22.08%  |
| 3.01-4.0    | 23       | 14.94%  |
| 16.01-24.0  | 10       | 6.49%   |
| 1.01-2.0    | 5        | 3.25%   |
| 64.01-256.0 | 3        | 1.95%   |
| 32.01-64.0  | 2        | 1.3%    |
| 2.01-3.0    | 2        | 1.3%    |
| 0.51-1.0    | 2        | 1.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 82       | 51.57%  |
| 0.51-1.0  | 27       | 16.98%  |
| 2.01-3.0  | 21       | 13.21%  |
| 4.01-8.0  | 12       | 7.55%   |
| 3.01-4.0  | 11       | 6.92%   |
| 8.01-16.0 | 3        | 1.89%   |
| 0.01-0.5  | 3        | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 109      | 69.87%  |
| 2      | 33       | 21.15%  |
| 3      | 9        | 5.77%   |
| 4      | 3        | 1.92%   |
| 5      | 1        | 0.64%   |
| 0      | 1        | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 62.99%  |
| Yes       | 57       | 37.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 153      | 99.35%  |
| No        | 1        | 0.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 84.42%  |
| Yes       | 24       | 15.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 138      | 89.61%  |
| Yes       | 16       | 10.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Russia     | 149      | 96.75%  |
| Greece     | 2        | 1.3%    |
| Ukraine    | 1        | 0.65%   |
| Kazakhstan | 1        | 0.65%   |
| Belarus    | 1        | 0.65%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Moscow             | 109      | 68.55%  |
| St Petersburg      | 5        | 3.14%   |
| Samara             | 3        | 1.89%   |
| Barnaul            | 3        | 1.89%   |
| Usol'ye-Sibirskoye | 2        | 1.26%   |
| Murmansk           | 2        | 1.26%   |
| Irkutsk            | 2        | 1.26%   |
| Zelenodolsk        | 1        | 0.63%   |
| Yelizovo           | 1        | 0.63%   |
| Vologda            | 1        | 0.63%   |
| Vergina            | 1        | 0.63%   |
| Valuyki            | 1        | 0.63%   |
| Tula               | 1        | 0.63%   |
| Tolyatti           | 1        | 0.63%   |
| Thessaloniki       | 1        | 0.63%   |
| Tambov             | 1        | 0.63%   |
| Srednyaya Akhtuba  | 1        | 0.63%   |
| Sredneuralsk       | 1        | 0.63%   |
| Shymkent           | 1        | 0.63%   |
| Sevastopol         | 1        | 0.63%   |
| Saratov            | 1        | 0.63%   |
| Rostov-on-Don      | 1        | 0.63%   |
| Perm               | 1        | 0.63%   |
| Obninsk            | 1        | 0.63%   |
| Novyy Oskol        | 1        | 0.63%   |
| Monchegorsk        | 1        | 0.63%   |
| Krasnoyarsk        | 1        | 0.63%   |
| Krasnogorsk        | 1        | 0.63%   |
| Krasnodar          | 1        | 0.63%   |
| Kostroma           | 1        | 0.63%   |
| Korolyov           | 1        | 0.63%   |
| Kirovsk            | 1        | 0.63%   |
| Kirov              | 1        | 0.63%   |
| Kazanâ€™      | 1        | 0.63%   |
| Kaliningrad        | 1        | 0.63%   |
| Ivanovo            | 1        | 0.63%   |
| Chita              | 1        | 0.63%   |
| Belgorod           | 1        | 0.63%   |
| Babruysk           | 1        | 0.63%   |
| Almaty             | 1        | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 42       | 61     | 22.22%  |
| AXIOMTEK            | 25       | 25     | 13.23%  |
| Seagate             | 23       | 36     | 12.17%  |
| Samsung Electronics | 23       | 28     | 12.17%  |
| Toshiba             | 22       | 37     | 11.64%  |
| Kingston            | 15       | 18     | 7.94%   |
| China               | 7        | 7      | 3.7%    |
| Hitachi             | 5        | 6      | 2.65%   |
| A-DATA Technology   | 4        | 4      | 2.12%   |
| Intel               | 2        | 6      | 1.06%   |
| DEPO                | 2        | 2      | 1.06%   |
| Apacer              | 2        | 3      | 1.06%   |
| SPCC                | 1        | 1      | 0.53%   |
| SP-8                | 1        | 1      | 0.53%   |
| Smartbuy            | 1        | 1      | 0.53%   |
| SINTECHI            | 1        | 1      | 0.53%   |
| SanDisk             | 1        | 1      | 0.53%   |
| PLEXTOR             | 1        | 1      | 0.53%   |
| Patriot             | 1        | 1      | 0.53%   |
| OCZ                 | 1        | 1      | 0.53%   |
| Micron Technology   | 1        | 1      | 0.53%   |
| LITEON              | 1        | 1      | 0.53%   |
| KingSpec            | 1        | 1      | 0.53%   |
| JMicron             | 1        | 1      | 0.53%   |
| HEORIADY            | 1        | 1      | 0.53%   |
| Gigabyte Technology | 1        | 1      | 0.53%   |
| FOXLINE             | 1        | 1      | 0.53%   |
| Crucial             | 1        | 1      | 0.53%   |
| AMD                 | 1        | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD     | 25       | 12.44%  |
| Samsung MZVLW128HEGR-00000 128GB         | 17       | 8.46%   |
| Toshiba HDWD120 2TB                      | 13       | 6.47%   |
| WDC WD5000AZLX-21K2TA0 500GB             | 10       | 4.98%   |
| Toshiba HDWD110 1TB                      | 4        | 1.99%   |
| Kingston RBUSC180S37256GJ 256GB SSD      | 4        | 1.99%   |
| WDC WDS240G1G0A-00SS50 240GB SSD         | 3        | 1.49%   |
| Kingston SV300S37A120G 120GB SSD         | 3        | 1.49%   |
| Kingston SA400S37120G 120GB SSD          | 3        | 1.49%   |
| WDC WD10PURZ-85U8XY0 1TB                 | 2        | 1%      |
| Toshiba DT01ACA100 1TB                   | 2        | 1%      |
| Seagate ST500LM030-2E717D 500GB          | 2        | 1%      |
| Seagate ST380815AS 80GB                  | 2        | 1%      |
| Seagate ST1000DM010-2EP102 1TB           | 2        | 1%      |
| Samsung SSD 860 EVO 500GB                | 2        | 1%      |
| Samsung SSD 860 EVO 250GB                | 2        | 1%      |
| Hitachi HDS721025CLA382 250GB            | 2        | 1%      |
| DEPO SM3DT-120 120GB SSD                 | 2        | 1%      |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1        | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 1        | 0.5%    |
| WDC WD800AAJS-00WAA0 80GB                | 1        | 0.5%    |
| WDC WD7501AALS-00E3A0 752GB              | 1        | 0.5%    |
| WDC WD5003ABYZ-011FA0 500GB              | 1        | 0.5%    |
| WDC WD5001ABYS-01YNA0 500GB              | 1        | 0.5%    |
| WDC WD5001AALS-00E3A0 500GB              | 1        | 0.5%    |
| WDC WD5000HHTZ-04N21V0 500GB             | 1        | 0.5%    |
| WDC WD5000AZRZ-00HTKB0 500GB             | 1        | 0.5%    |
| WDC WD5000AZLX-00JKKA0 500GB             | 1        | 0.5%    |
| WDC WD3200BPVT-00HXZT3 320GB             | 1        | 0.5%    |
| WDC WD3200BEVT-80A0RT0 320GB             | 1        | 0.5%    |
| WDC WD3200AAKS-00V1A0 320GB              | 1        | 0.5%    |
| WDC WD3200AAKS-00UU3A0 320GB             | 1        | 0.5%    |
| WDC WD30EZRX-00DC0B0 3TB                 | 1        | 0.5%    |
| WDC WD2500KS-00MJB0 250GB                | 1        | 0.5%    |
| WDC WD2500BEVT-60ZCT1 250GB              | 1        | 0.5%    |
| WDC WD20EZBX-00AYRA0 2TB                 | 1        | 0.5%    |
| WDC WD20EURX-63T0FY0 2TB                 | 1        | 0.5%    |
| WDC WD20EARX-008FB0 2TB                  | 1        | 0.5%    |
| WDC WD2005FBYZ-01YCBB3 2TB               | 1        | 0.5%    |
| WDC WD2000FYYZ-01UL1B1 2TB               | 1        | 0.5%    |
| WDC WD1600AAJS-61M0A0 160GB              | 1        | 0.5%    |
| WDC WD10SPSX-00A6WT0 1TB                 | 1        | 0.5%    |
| WDC WD10EZRZ-00HTKB0 1TB                 | 1        | 0.5%    |
| WDC WD10EZEX-60ZF5A0 1TB                 | 1        | 0.5%    |
| WDC WD10EZEX-21WN4A0 1TB                 | 1        | 0.5%    |
| WDC WD10EZEX-08M2NA0 1TB                 | 1        | 0.5%    |
| WDC WD1004FBYZ-01YCBB1 1TB               | 1        | 0.5%    |
| WDC WD1003FZEX-00MK2A0 1TB               | 1        | 0.5%    |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB       | 1        | 0.5%    |
| Toshiba DT01ACA300 3TB                   | 1        | 0.5%    |
| Toshiba DT01ACA200 2TB                   | 1        | 0.5%    |
| Toshiba DT01ACA050 500GB                 | 1        | 0.5%    |
| SPCC M.2 PCIe SSD 1TB                    | 1        | 0.5%    |
| SP-8 PRO 1TB SSD                         | 1        | 0.5%    |
| Smartbuy SSD 512GB                       | 1        | 0.5%    |
| SINTECHI HighSpeed SD to CF Adapter V1.0 | 1        | 0.5%    |
| Seagate STM3320418AS 320GB               | 1        | 0.5%    |
| Seagate ST96812AS 64GB                   | 1        | 0.5%    |
| Seagate ST9250315AS 250GB                | 1        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 36       | 54     | 42.35%  |
| Toshiba  | 22       | 37     | 25.88%  |
| Seagate  | 21       | 31     | 24.71%  |
| Hitachi  | 5        | 6      | 5.88%   |
| SINTECHI | 1        | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| AXIOMTEK            | 25       | 25     | 30.86%  |
| Kingston            | 14       | 16     | 17.28%  |
| China               | 7        | 7      | 8.64%   |
| WDC                 | 6        | 6      | 7.41%   |
| Samsung Electronics | 5        | 7      | 6.17%   |
| A-DATA Technology   | 3        | 3      | 3.7%    |
| Seagate             | 2        | 5      | 2.47%   |
| DEPO                | 2        | 2      | 2.47%   |
| Apacer              | 2        | 3      | 2.47%   |
| SP-8                | 1        | 1      | 1.23%   |
| Smartbuy            | 1        | 1      | 1.23%   |
| SanDisk             | 1        | 1      | 1.23%   |
| PLEXTOR             | 1        | 1      | 1.23%   |
| Patriot             | 1        | 1      | 1.23%   |
| OCZ                 | 1        | 1      | 1.23%   |
| LITEON              | 1        | 1      | 1.23%   |
| KingSpec            | 1        | 1      | 1.23%   |
| JMicron             | 1        | 1      | 1.23%   |
| Intel               | 1        | 4      | 1.23%   |
| HEORIADY            | 1        | 1      | 1.23%   |
| Gigabyte Technology | 1        | 1      | 1.23%   |
| FOXLINE             | 1        | 1      | 1.23%   |
| Crucial             | 1        | 1      | 1.23%   |
| AMD                 | 1        | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 76       | 92     | 43.18%  |
| HDD  | 75       | 129    | 42.61%  |
| NVMe | 25       | 29     | 14.2%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 133      | 220    | 83.65%  |
| NVMe | 25       | 29     | 15.72%  |
| SAS  | 1        | 1      | 0.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 105      | 137    | 68.18%  |
| 0.51-1.0   | 25       | 40     | 16.23%  |
| 1.01-2.0   | 22       | 41     | 14.29%  |
| 2.01-3.0   | 2        | 3      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 76       | 48.41%  |
| 251-500        | 24       | 15.29%  |
| 1001-2000      | 21       | 13.38%  |
| 501-1000       | 11       | 7.01%   |
| 21-50          | 7        | 4.46%   |
| 51-100         | 6        | 3.82%   |
| 1-20           | 5        | 3.18%   |
| More than 3000 | 4        | 2.55%   |
| 2001-3000      | 2        | 1.27%   |
| Unknown        | 1        | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 99       | 61.49%  |
| 21-50          | 21       | 13.04%  |
| 101-250        | 12       | 7.45%   |
| 51-100         | 11       | 6.83%   |
| 501-1000       | 8        | 4.97%   |
| 251-500        | 5        | 3.11%   |
| 1001-2000      | 2        | 1.24%   |
| More than 3000 | 1        | 0.62%   |
| 2001-3000      | 1        | 0.62%   |
| Unknown        | 1        | 0.62%   |

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
| Hitachi HDS721025CLA382 250GB         | 1        | 1      | 5.88%   |
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
| Works    | 134      | 199    | 80.24%  |
| Detected | 16       | 29     | 9.58%   |
| Malfunc  | 16       | 21     | 9.58%   |
| Failed   | 1        | 1      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 110      | 58.82%  |
| AMD                         | 34       | 18.18%  |
| Samsung Electronics         | 18       | 9.63%   |
| Nvidia                      | 7        | 3.74%   |
| JMicron Technology          | 4        | 2.14%   |
| MCST                        | 2        | 1.07%   |
| Marvell Technology Group    | 2        | 1.07%   |
| Kingston Technology Company | 2        | 1.07%   |
| ASMedia Technology          | 2        | 1.07%   |
| VIA Technologies            | 1        | 0.53%   |
| Silicon Motion              | 1        | 0.53%   |
| Sandisk                     | 1        | 0.53%   |
| Realtek Semiconductor       | 1        | 0.53%   |
| Micron Technology           | 1        | 0.53%   |
| LSI Logic / Symbios Logic   | 1        | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 63       | 27.39%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 28       | 12.17%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 17       | 7.39%   |
| AMD 400 Series Chipset SATA Controller                                           | 16       | 6.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 7        | 3.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6        | 2.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5        | 2.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4        | 1.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4        | 1.74%   |
| AMD FCH SATA Controller D                                                        | 4        | 1.74%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3        | 1.3%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3        | 1.3%    |
| AMD 500 Series Chipset SATA Controller                                           | 3        | 1.3%    |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2        | 0.87%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                     | 2        | 0.87%   |
| Nvidia MCP51 Serial ATA Controller                                               | 2        | 0.87%   |
| Nvidia MCP51 IDE                                                                 | 2        | 0.87%   |
| MCST SATA                                                                        | 2        | 0.87%   |
| MCST IDE controller                                                              | 2        | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2        | 0.87%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2        | 0.87%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2        | 0.87%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2        | 0.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 2        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 2        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2        | 0.87%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 0.87%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1        | 0.43%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.43%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1        | 0.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1        | 0.43%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1        | 0.43%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 1        | 0.43%   |
| Nvidia MCP73 IDE Controller                                                      | 1        | 0.43%   |
| Nvidia MCP61 SATA Controller                                                     | 1        | 0.43%   |
| Nvidia CK804 Serial ATA Controller                                               | 1        | 0.43%   |
| Nvidia CK804 IDE                                                                 | 1        | 0.43%   |
| Micron Non-Volatile memory controller                                            | 1        | 0.43%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1        | 0.43%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 1        | 0.43%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                          | 1        | 0.43%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1        | 0.43%   |
| Kingston Company A2000 NVMe SSD                                                  | 1        | 0.43%   |
| JMicron JMB368 IDE controller                                                    | 1        | 0.43%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1        | 0.43%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 0.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 0.43%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1        | 0.43%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1        | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 0.43%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1        | 0.43%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 0.43%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 1        | 0.43%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1        | 0.43%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                          | 1        | 0.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1        | 0.43%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 134      | 71.28%  |
| IDE  | 27       | 14.36%  |
| NVMe | 25       | 13.3%   |
| RAID | 2        | 1.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 112      | 72.73%  |
| AMD      | 40       | 25.97%  |
| E8C/EATX | 1        | 0.65%   |
| E8C-SWTX | 1        | 0.65%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-6100TE CPU @ 2.70GHz          | 42       | 26.92%  |
| AMD Ryzen 5 1600 Six-Core Processor         | 13       | 8.33%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 10       | 6.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4        | 2.56%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3        | 1.92%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 3        | 1.92%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 3        | 1.92%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.92%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 1.28%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 2        | 1.28%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 1.28%   |
| Intel Genuine CPU 0000 @ 2.40GHz            | 2        | 1.28%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.28%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.28%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.28%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.28%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.28%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 2        | 1.28%   |
| Intel Xeon D-2177NT CPU @ 1.90GHz           | 1        | 0.64%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.64%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.64%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.64%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 0.64%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.64%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.64%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.64%   |
| Intel Pentium CPU G4500 @ 3.50GHz           | 1        | 0.64%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.64%   |
| Intel Core i9-10980XE CPU @ 3.00GHz         | 1        | 0.64%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.64%   |
| Intel Core i7-4960X CPU @ 3.60GHz           | 1        | 0.64%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.64%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.64%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.64%   |
| Intel Core i5-8265UC CPU @ 1.60GHz          | 1        | 0.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.64%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 0.64%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 0.64%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 0.64%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 0.64%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 0.64%   |
| Intel Core i3-10100T CPU @ 3.00GHz          | 1        | 0.64%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 0.64%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 0.64%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 1        | 0.64%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 1        | 0.64%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1        | 0.64%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 0.64%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 1        | 0.64%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 1        | 0.64%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 1        | 0.64%   |
| E8C/EATX E8C                                | 1        | 0.64%   |
| E8C-SWTX E8C                                | 1        | 0.64%   |
| AMD Sempron Processor 3000+                 | 1        | 0.64%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics  | 1        | 0.64%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 0.64%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 1        | 0.64%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 1        | 0.64%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 1        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 55       | 35.48%  |
| AMD Ryzen 5             | 17       | 10.97%  |
| Intel Pentium           | 13       | 8.39%   |
| Intel Core i5           | 13       | 8.39%   |
| Intel Celeron           | 8        | 5.16%   |
| Intel Pentium Dual-Core | 5        | 3.23%   |
| Intel Core 2 Duo        | 4        | 2.58%   |
| AMD Ryzen 7             | 4        | 2.58%   |
| Other                   | 3        | 1.94%   |
| Intel Xeon              | 3        | 1.94%   |
| AMD Athlon 64 X2        | 3        | 1.94%   |
| AMD A8                  | 3        | 1.94%   |
| Intel Pentium Gold      | 2        | 1.29%   |
| Intel Genuine           | 2        | 1.29%   |
| Intel Core i7           | 2        | 1.29%   |
| AMD Ryzen 3             | 2        | 1.29%   |
| AMD Phenom II X4        | 2        | 1.29%   |
| AMD FX                  | 2        | 1.29%   |
| AMD Athlon              | 2        | 1.29%   |
| AMD A10                 | 2        | 1.29%   |
| Intel Pentium D         | 1        | 0.65%   |
| Intel Pentium 4         | 1        | 0.65%   |
| Intel Core i9           | 1        | 0.65%   |
| Intel Core 2 Quad       | 1        | 0.65%   |
| AMD Sempron             | 1        | 0.65%   |
| AMD Ryzen 7 PRO         | 1        | 0.65%   |
| AMD Ryzen 5 PRO         | 1        | 0.65%   |
| AMD Athlon II X4        | 1        | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 89       | 57.42%  |
| 4      | 31       | 20%     |
| 6      | 20       | 12.9%   |
| 8      | 7        | 4.52%   |
| 1      | 3        | 1.94%   |
| 32     | 1        | 0.65%   |
| 18     | 1        | 0.65%   |
| 16     | 1        | 0.65%   |
| 14     | 1        | 0.65%   |
| 3      | 1        | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 151      | 98.05%  |
| 2      | 2        | 1.3%    |
| 4      | 1        | 0.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 107      | 69.48%  |
| 1      | 47       | 30.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 151      | 98.05%  |
| Unknown        | 2        | 1.3%    |
| 32-bit         | 1        | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 47       | 30.13%  |
| Unknown    | 23       | 14.74%  |
| 0x906e9    | 13       | 8.33%   |
| 0x08001138 | 13       | 8.33%   |
| 0x1067a    | 8        | 5.13%   |
| 0xa0653    | 5        | 3.21%   |
| 0x906eb    | 5        | 3.21%   |
| 0x906ea    | 3        | 1.92%   |
| 0x306a9    | 3        | 1.92%   |
| 0x08108109 | 3        | 1.92%   |
| 0x806e9    | 2        | 1.28%   |
| 0x30679    | 2        | 1.28%   |
| 0x08701021 | 2        | 1.28%   |
| 0x06001119 | 2        | 1.28%   |
| 0x010000db | 2        | 1.28%   |
| 0xf47      | 1        | 0.64%   |
| 0xf29      | 1        | 0.64%   |
| 0xa0671    | 1        | 0.64%   |
| 0x906ed    | 1        | 0.64%   |
| 0x806ec    | 1        | 0.64%   |
| 0x6fb      | 1        | 0.64%   |
| 0x506e8    | 1        | 0.64%   |
| 0x506c9    | 1        | 0.64%   |
| 0x50657    | 1        | 0.64%   |
| 0x50654    | 1        | 0.64%   |
| 0x306e4    | 1        | 0.64%   |
| 0x306c3    | 1        | 0.64%   |
| 0x206c2    | 1        | 0.64%   |
| 0x206a7    | 1        | 0.64%   |
| 0x10661    | 1        | 0.64%   |
| 0x0a50000c | 1        | 0.64%   |
| 0x08108102 | 1        | 0.64%   |
| 0x0810100b | 1        | 0.64%   |
| 0x0800820d | 1        | 0.64%   |
| 0x08001129 | 1        | 0.64%   |
| 0x06000852 | 1        | 0.64%   |
| 0x010000c8 | 1        | 0.64%   |
| 0x00000000 | 1        | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Skylake     | 52       | 33.77%  |
| KabyLake    | 28       | 18.18%  |
| Zen         | 15       | 9.74%   |
| Penryn      | 9        | 5.84%   |
| Zen+        | 7        | 4.55%   |
| Piledriver  | 5        | 3.25%   |
| CometLake   | 5        | 3.25%   |
| K8 Hammer   | 4        | 2.6%    |
| IvyBridge   | 4        | 2.6%    |
| Zen 2       | 3        | 1.95%   |
| Silvermont  | 3        | 1.95%   |
| K10         | 3        | 1.95%   |
| Unknown     | 3        | 1.95%   |
| Steamroller | 2        | 1.3%    |
| SandyBridge | 2        | 1.3%    |
| NetBurst    | 2        | 1.3%    |
| Haswell     | 2        | 1.3%    |
| Core        | 2        | 1.3%    |
| Zen 3       | 1        | 0.65%   |
| Westmere    | 1        | 0.65%   |
| Goldmont    | 1        | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 91       | 57.59%  |
| Nvidia            | 42       | 26.58%  |
| AMD               | 21       | 13.29%  |
| Silicon Motion    | 2        | 1.27%   |
| ASPEED Technology | 2        | 1.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                                    | 44       | 27.33%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 15       | 9.32%   |
| Intel HD Graphics 610                                                                    | 10       | 6.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8        | 4.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6        | 3.73%   |
| Intel HD Graphics 510                                                                    | 5        | 3.11%   |
| Intel HD Graphics 620                                                                    | 4        | 2.48%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 2.48%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 1.86%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3        | 1.86%   |
| Silicon Motion SM718 LynxSE+                                                             | 2        | 1.24%   |
| Intel HD Graphics 630                                                                    | 2        | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.24%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.24%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 1.24%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.24%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 2        | 1.24%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.62%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.62%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.62%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.62%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.62%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1        | 0.62%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.62%   |
| Nvidia GK106 [GeForce GTX 650 Ti Boost]                                                  | 1        | 0.62%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 0.62%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 1        | 0.62%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 0.62%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1        | 0.62%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 0.62%   |
| Nvidia G92 [GeForce 8800 GT]                                                             | 1        | 0.62%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 0.62%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 0.62%   |
| Nvidia C51PV [GeForce 6150]                                                              | 1        | 0.62%   |
| Nvidia C51G [GeForce 6100]                                                               | 1        | 0.62%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 0.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1        | 0.62%   |
| Intel HD Graphics 500                                                                    | 1        | 0.62%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                                 | 1        | 0.62%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1        | 0.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1        | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 0.62%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 0.62%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 0.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 0.62%   |
| AMD Trinity [Radeon HD 7660D]                                                            | 1        | 0.62%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 1        | 0.62%   |
| AMD RV530LE [Radeon X1600/X1650 PRO]                                                     | 1        | 0.62%   |
| AMD RV530 [Radeon X1650] (Secondary)                                                     | 1        | 0.62%   |
| AMD RV530 [Radeon X1600] (Secondary)                                                     | 1        | 0.62%   |
| AMD RV530 [Radeon X1600 PRO]                                                             | 1        | 0.62%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series] (Secondary)                                    | 1        | 0.62%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series]                                                | 1        | 0.62%   |
| AMD Richland [Radeon HD 8670D]                                                           | 1        | 0.62%   |
| AMD Richland [Radeon HD 8570D]                                                           | 1        | 0.62%   |
| AMD Renoir                                                                               | 1        | 0.62%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                                 | 1        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 88       | 57.14%  |
| 1 x Nvidia         | 41       | 26.62%  |
| 1 x AMD            | 18       | 11.69%  |
| 2 x AMD            | 2        | 1.3%    |
| 1 x Silicon Motion | 2        | 1.3%    |
| 1 x ASPEED         | 2        | 1.3%    |
| Intel + Nvidia     | 1        | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 120      | 77.42%  |
| Proprietary | 30       | 19.35%  |
| Unknown     | 5        | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 100      | 64.52%  |
| 3.01-4.0   | 18       | 11.61%  |
| 0.01-0.5   | 12       | 7.74%   |
| 0.51-1.0   | 11       | 7.1%    |
| 1.01-2.0   | 10       | 6.45%   |
| 7.01-8.0   | 1        | 0.65%   |
| 5.01-6.0   | 1        | 0.65%   |
| 2.01-3.0   | 1        | 0.65%   |
| 8.01-16.0  | 1        | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| HHT                  | 42       | 26.42%  |
| Acer                 | 21       | 13.21%  |
| BenQ                 | 18       | 11.32%  |
| AOC                  | 18       | 11.32%  |
| Samsung Electronics  | 13       | 8.18%   |
| Goldstar             | 8        | 5.03%   |
| Dell                 | 6        | 3.77%   |
| ViewSonic            | 5        | 3.14%   |
| PRW                  | 4        | 2.52%   |
| WBT                  | 3        | 1.89%   |
| Philips              | 3        | 1.89%   |
| STD                  | 2        | 1.26%   |
| LG Electronics       | 2        | 1.26%   |
| Hewlett-Packard      | 2        | 1.26%   |
| Ancor Communications | 2        | 1.26%   |
| VIE                  | 1        | 0.63%   |
| Toshiba              | 1        | 0.63%   |
| SKG                  | 1        | 0.63%   |
| Lenovo               | 1        | 0.63%   |
| JRY                  | 1        | 0.63%   |
| HIB                  | 1        | 0.63%   |
| HannStar             | 1        | 0.63%   |
| DZW                  | 1        | 0.63%   |
| Apple                | 1        | 0.63%   |
| Unknown              | 1        | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch               | 42       | 25.61%  |
| AOC LCD Monitor 2778X 2560x1440                                       | 11       | 6.71%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                     | 10       | 6.1%    |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 7        | 4.27%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 5        | 3.05%   |
| PRW AP7_Titanium PRW4200 3840x2160                                    | 4        | 2.44%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                      | 3        | 1.83%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2        | 1.22%   |
| STD Monitor STD0001 1920x1080                                         | 2        | 1.22%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                | 2        | 1.22%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2        | 1.22%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch         | 1        | 0.61%   |
| ViewSonic VA1916wSERIES VSCF91F 1440x900 410x256mm 19.0-inch          | 1        | 0.61%   |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch           | 1        | 0.61%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 0.61%   |
| Toshiba LCD Monitor TV 1920x1080                                      | 1        | 0.61%   |
| SKG 86 Monitor SKG8600 3840x2160 1650x928mm 74.5-inch                 | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 0.61%   |
| Samsung Electronics SMS22A450 SAM0836 1680x1050 459x296mm 21.5-inch   | 1        | 0.61%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 1        | 0.61%   |
| Samsung Electronics S24B370 SAM08DE 1920x1080 531x299mm 24.0-inch     | 1        | 0.61%   |
| Samsung Electronics S22E391 SAM0C0E 1920x1080 477x268mm 21.5-inch     | 1        | 0.61%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1        | 0.61%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1        | 0.61%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 1        | 0.61%   |
| Samsung Electronics EPSON PJ SECA60D 1920x1080                        | 1        | 0.61%   |
| Samsung Electronics C27JG5x SAM0F58 2560x1440 600x340mm 27.2-inch     | 1        | 0.61%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 0.61%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch               | 1        | 0.61%   |
| Philips PHI32PFL3404 PHLD067 1360x768 700x390mm 31.5-inch             | 1        | 0.61%   |
| Philips 19S PHL0878 1280x1024 376x301mm 19.0-inch                     | 1        | 0.61%   |
| LG Electronics LCD Monitor W2243 1920x1080                            | 1        | 0.61%   |
| LG Electronics LCD Monitor L1752S 1280x1024                           | 1        | 0.61%   |
| LG Electronics LCD Monitor 2D FHD LG TV 1920x1080                     | 1        | 0.61%   |
| Lenovo LEN E2323swA LEN60B0 1920x1080 477x268mm 21.5-inch             | 1        | 0.61%   |
| JRY HDMI JRY2380 1920x1080 527x296mm 23.8-inch                        | 1        | 0.61%   |
| HIB AIO HIB0001 1920x1200 476x268mm 21.5-inch                         | 1        | 0.61%   |
| Hewlett-Packard L1730 HWP260E 1280x1024 338x270mm 17.0-inch           | 1        | 0.61%   |
| Hewlett-Packard E241i HWP3124 1920x1200 518x324mm 24.1-inch           | 1        | 0.61%   |
| HannStar JC171D HSD04B2 1280x1024 338x270mm 17.0-inch                 | 1        | 0.61%   |
| Goldstar W2261 GSM56CF 1920x1080 477x268mm 21.5-inch                  | 1        | 0.61%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 1        | 0.61%   |
| Goldstar L1953S GSM4B3E 1280x1024 376x301mm 19.0-inch                 | 1        | 0.61%   |
| Goldstar L1752S GSM4432 1280x1024 338x270mm 17.0-inch                 | 1        | 0.61%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 1        | 0.61%   |
| Goldstar 22M35 GSM5A31 1920x1080 480x270mm 21.7-inch                  | 1        | 0.61%   |
| DZW SMART TV UHD DZW0030 3840x2160 708x398mm 32.0-inch                | 1        | 0.61%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1        | 0.61%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                    | 1        | 0.61%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 1        | 0.61%   |
| Dell S2318H/HX DELD0BC 1920x1080 510x290mm 23.1-inch                  | 1        | 0.61%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 1        | 0.61%   |
| Dell E2216H DELF069 1920x1080 476x268mm 21.5-inch                     | 1        | 0.61%   |
| BenQ V2220H BNQ7B0E 1920x1080 477x268mm 21.5-inch                     | 1        | 0.61%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 1        | 0.61%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 1        | 0.61%   |
| BenQ G900 BNQ7803 1280x1024 376x301mm 19.0-inch                       | 1        | 0.61%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 1        | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 60       | 38.46%  |
| 3840x2160 (4K)     | 50       | 32.05%  |
| 2560x1440 (QHD)    | 21       | 13.46%  |
| 1280x1024 (SXGA)   | 12       | 7.69%   |
| 1600x900 (HD+)     | 3        | 1.92%   |
| 1440x900 (WXGA+)   | 2        | 1.28%   |
| 1366x768 (WXGA)    | 2        | 1.28%   |
| Unknown            | 2        | 1.28%   |
| 4480x1440          | 1        | 0.64%   |
| 1920x1200 (WUXGA)  | 1        | 0.64%   |
| 1680x1050 (WSXGA+) | 1        | 0.64%   |
| 1360x768           | 1        | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 40      | 43       | 27.56%  |
| 24      | 30       | 19.23%  |
| Unknown | 21       | 13.46%  |
| 21      | 14       | 8.97%   |
| 23      | 13       | 8.33%   |
| 19      | 9        | 5.77%   |
| 17      | 6        | 3.85%   |
| 27      | 5        | 3.21%   |
| 31      | 3        | 1.92%   |
| 26      | 3        | 1.92%   |
| 22      | 2        | 1.28%   |
| 74      | 1        | 0.64%   |
| 72      | 1        | 0.64%   |
| 33      | 1        | 0.64%   |
| 32      | 1        | 0.64%   |
| 28      | 1        | 0.64%   |
| 20      | 1        | 0.64%   |
| 18      | 1        | 0.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 50       | 32.68%  |
| 901-1000    | 42       | 27.45%  |
| Unknown     | 21       | 13.73%  |
| 401-500     | 20       | 13.07%  |
| 301-350     | 6        | 3.92%   |
| 351-400     | 5        | 3.27%   |
| 601-700     | 4        | 2.61%   |
| 701-800     | 2        | 1.31%   |
| 1501-2000   | 2        | 1.31%   |
| 801-900     | 1        | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 73       | 48.34%  |
| 21/9    | 42       | 27.81%  |
| Unknown | 17       | 11.26%  |
| 5/4     | 11       | 7.28%   |
| 16/10   | 7        | 4.64%   |
| 3/2     | 1        | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 52       | 33.99%  |
| 501-1000       | 43       | 28.1%   |
| Unknown        | 21       | 13.73%  |
| 151-200        | 12       | 7.84%   |
| 301-350        | 8        | 5.23%   |
| 141-150        | 7        | 4.58%   |
| 351-500        | 6        | 3.92%   |
| More than 1000 | 2        | 1.31%   |
| 251-300        | 2        | 1.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 60       | 39.22%  |
| 101-120 | 59       | 38.56%  |
| Unknown | 21       | 13.73%  |
| 121-160 | 10       | 6.54%   |
| 1-50    | 3        | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 133      | 85.81%  |
| 2     | 12       | 7.74%   |
| 0     | 9        | 5.81%   |
| 3     | 1        | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 133      | 60.45%  |
| Intel                      | 58       | 26.36%  |
| Qualcomm Atheros           | 9        | 4.09%   |
| Nvidia                     | 6        | 2.73%   |
| Microchip Technology       | 3        | 1.36%   |
| Ralink Technology          | 2        | 0.91%   |
| MCST                       | 2        | 0.91%   |
| ZTE WCDMA Technologies MSM | 1        | 0.45%   |
| Vimtron Electronics        | 1        | 0.45%   |
| VIA Technologies           | 1        | 0.45%   |
| TP-Link                    | 1        | 0.45%   |
| Ralink                     | 1        | 0.45%   |
| D-Link                     | 1        | 0.45%   |
| Broadcom Limited           | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78       | 32.64%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 42       | 17.57%  |
| Intel Ethernet Connection I219-LM                                 | 30       | 12.55%  |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 7.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.51%   |
| Intel Wireless 3165                                               | 4        | 1.67%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3        | 1.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.26%   |
| Microchip MCP2221 USB-I2C/UART Combo                              | 3        | 1.26%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.84%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.84%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.84%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1        | 0.42%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.42%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.42%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.42%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.42%   |
| Realtek 802.11ac NIC                                              | 1        | 0.42%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.42%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.42%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1        | 0.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.42%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.42%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.42%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.42%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.42%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.42%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.42%   |
| Intel Wireless-AC 9260                                            | 1        | 0.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.42%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 0.42%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.42%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.42%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.42%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1        | 0.42%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1        | 0.42%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.42%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.42%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.42%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.42%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.42%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 1        | 0.42%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 41.67%  |
| Intel                 | 7        | 29.17%  |
| Qualcomm Atheros      | 3        | 12.5%   |
| Ralink Technology     | 2        | 8.33%   |
| TP-Link               | 1        | 4.17%   |
| Ralink                | 1        | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                        | 4        | 16.67%  |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 3        | 12.5%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 3        | 12.5%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 4.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 4.17%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 4.17%   |
| Realtek 802.11ac NIC                                       | 1        | 4.17%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 4.17%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 4.17%   |
| Ralink RT2561/RT61 rev B 802.11g                           | 1        | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 4.17%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 4.17%   |
| Intel Wireless-AC 9260                                     | 1        | 4.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 4.17%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 132      | 63.77%  |
| Intel                      | 56       | 27.05%  |
| Qualcomm Atheros           | 6        | 2.9%    |
| Nvidia                     | 6        | 2.9%    |
| MCST                       | 2        | 0.97%   |
| ZTE WCDMA Technologies MSM | 1        | 0.48%   |
| Vimtron Electronics        | 1        | 0.48%   |
| VIA Technologies           | 1        | 0.48%   |
| D-Link                     | 1        | 0.48%   |
| Broadcom Limited           | 1        | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78       | 36.79%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 42       | 19.81%  |
| Intel Ethernet Connection I219-LM                                 | 30       | 14.15%  |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 8.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.83%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.94%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.94%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.94%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1        | 0.47%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.47%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.47%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.47%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.47%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.47%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.47%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.47%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.47%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.47%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.47%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1        | 0.47%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1        | 0.47%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.47%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.47%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.47%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.47%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 1        | 0.47%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 153      | 85%     |
| WiFi     | 24       | 13.33%  |
| Modem    | 3        | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 143      | 91.08%  |
| WiFi     | 14       | 8.92%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 133      | 86.36%  |
| 2     | 18       | 11.69%  |
| 13    | 1        | 0.65%   |
| 8     | 1        | 0.65%   |
| 3     | 1        | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 150      | 97.4%   |
| Yes  | 4        | 2.6%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 7        | 41.18%  |
| Cambridge Silicon Radio | 4        | 23.53%  |
| Realtek Semiconductor   | 2        | 11.76%  |
| Broadcom                | 2        | 11.76%  |
| Logitech                | 1        | 5.88%   |
| IMC Networks            | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 4        | 23.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 23.53%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 5.88%   |
| Realtek Bluetooth Radio                             | 1        | 5.88%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 5.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 5.88%   |
| Intel AX210 Bluetooth                               | 1        | 5.88%   |
| Intel AX200 Bluetooth                               | 1        | 5.88%   |
| IMC Networks Bluetooth Device                       | 1        | 5.88%   |
| Broadcom Bluetooth dongle                           | 1        | 5.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 108      | 55.38%  |
| Nvidia              | 40       | 20.51%  |
| AMD                 | 37       | 18.97%  |
| MCST                | 2        | 1.03%   |
| VIA Technologies    | 1        | 0.51%   |
| JMTek               | 1        | 0.51%   |
| EasyPass Industrial | 1        | 0.51%   |
| Creative Technology | 1        | 0.51%   |
| Creative Labs       | 1        | 0.51%   |
| C-Media Electronics | 1        | 0.51%   |
| Apple               | 1        | 0.51%   |
| A4Tech              | 1        | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 63       | 29.58%  |
| Nvidia GP107GL High Definition Audio Controller                                                   | 16       | 7.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15       | 7.04%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9        | 4.23%   |
| Intel 200 Series PCH HD Audio                                                                     | 7        | 3.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7        | 3.29%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 2.82%   |
| AMD FCH Azalia Controller                                                                         | 5        | 2.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 1.88%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 1.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4        | 1.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 1.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3        | 1.41%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3        | 1.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3        | 1.41%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 0.94%   |
| MCST HD Audio                                                                                     | 2        | 0.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2        | 0.94%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2        | 0.94%   |
| Intel Audio device                                                                                | 2        | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2        | 0.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2        | 0.94%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2        | 0.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 0.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 0.94%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1        | 0.47%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.47%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 0.47%   |
| Nvidia MCP73 High Definition Audio                                                                | 1        | 0.47%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 0.47%   |
| Nvidia MCP51 High Definition Audio                                                                | 1        | 0.47%   |
| Nvidia MCP51 AC97 Audio Controller                                                                | 1        | 0.47%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.47%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.47%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 0.47%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.47%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1        | 0.47%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1        | 0.47%   |
| Nvidia CK804 AC'97 Audio Controller                                                               | 1        | 0.47%   |
| Nvidia Audio device                                                                               | 1        | 0.47%   |
| JMTek USB PnP Audio Device                                                                        | 1        | 0.47%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 0.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 0.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1        | 0.47%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 0.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 0.47%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 0.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1        | 0.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 0.47%   |
| EasyPass Industrial Audioengine D1                                                                | 1        | 0.47%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                                                      | 1        | 0.47%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 1        | 0.47%   |
| C-Media Electronics CM103+ Audio Controller                                                       | 1        | 0.47%   |
| Apple Audio in LED Cinema Display                                                                 | 1        | 0.47%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1        | 0.47%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 28       | 25%     |
| Kingston            | 19       | 16.96%  |
| Unknown             | 18       | 16.07%  |
| Micron Technology   | 13       | 11.61%  |
| Samsung Electronics | 9        | 8.04%   |
| SK Hynix            | 5        | 4.46%   |
| Foxline             | 3        | 2.68%   |
| Patriot             | 2        | 1.79%   |
| GOODRAM             | 2        | 1.79%   |
| Goldkey             | 2        | 1.79%   |
| Apacer              | 2        | 1.79%   |
| TIGO                | 1        | 0.89%   |
| Ramaxel Technology  | 1        | 0.89%   |
| Qumo                | 1        | 0.89%   |
| Juhor               | 1        | 0.89%   |
| G.Skill             | 1        | 0.89%   |
| Elpida              | 1        | 0.89%   |
| Corsair             | 1        | 0.89%   |
| A-DATA Technology   | 1        | 0.89%   |
| Unknown             | 1        | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s     | 13       | 10.57%  |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                 | 10       | 8.13%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s   | 4        | 3.25%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s   | 3        | 2.44%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 2        | 1.63%   |
| Unknown RAM Module 1024MB DIMM                           | 2        | 1.63%   |
| Samsung RAM M378A1K43EB2-CVF 8GB DIMM DDR4 2933MT/s      | 2        | 1.63%   |
| Kingston RAM 99U5471-012.A00LF 4096MB DIMM DDR3 1600MT/s | 2        | 1.63%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s   | 2        | 1.63%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 0.81%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                | 1        | 0.81%   |
| Unknown RAM Module 512MB DIMM 400MT/s                    | 1        | 0.81%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.81%   |
| Unknown RAM Module 4096MB DIMM 333MT/s                   | 1        | 0.81%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM SDRAM 533MT/s             | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s              | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM SDRAM 533MT/s             | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s              | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s               | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                   | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM 400MT/s                   | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM 32MT/s                    | 1        | 0.81%   |
| TIGO RAM 4GB-2400MHZ 4GB SODIMM DDR4 2400MT/s            | 1        | 0.81%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s     | 1        | 0.81%   |
| SK Hynix RAM HMT151R7TFR4C-H9 4096MB DIMM DDR3 1333MT/s  | 1        | 0.81%   |
| SK Hynix RAM HMT151R7BFR4C-H9 4096MB DIMM DDR3 1333MT/s  | 1        | 0.81%   |
| SK Hynix RAM HMA82GU6CJR8N-XN 16GB DIMM DDR4 3333MT/s    | 1        | 0.81%   |
| SK Hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s     | 1        | 0.81%   |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s     | 1        | 0.81%   |
| Samsung RAM Module 4096MB DIMM DDR4 2667MT/s             | 1        | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s | 1        | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s | 1        | 0.81%   |
| Samsung RAM M471A1K43BB1-CWE 8GB SODIMM DDR4 3534MT/s    | 1        | 0.81%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 0.81%   |
| Samsung RAM M378A5143DB0-CPB 4GB DIMM DDR4 2400MT/s      | 1        | 0.81%   |
| Samsung RAM M378A1K43DB2-CTD 8192MB DIMM DDR4 4333MT/s   | 1        | 0.81%   |
| Ramaxel RAM RML1040EG38D6W-533 512MB DIMM DDR2 533MT/s   | 1        | 0.81%   |
| Qumo RAM QUM4U-8G2666P19 8192MB DIMM DDR4 2667MT/s       | 1        | 0.81%   |
| Patriot RAM PSD44G240081 4096MB DIMM DDR4 2400MT/s       | 1        | 0.81%   |
| Patriot RAM PSD38G16002 8192MB DIMM DDR3 1600MT/s        | 1        | 0.81%   |
| Micron RAM Module 8192MB DIMM DDR4 2400MT/s              | 1        | 0.81%   |
| Micron RAM Module 4096MB DIMM DDR4 2400MT/s              | 1        | 0.81%   |
| Micron RAM 8ATF1G64HZ-2G3B2 8GB SODIMM DDR4 2133MT/s     | 1        | 0.81%   |
| Kingston RAM Module 32GB DIMM DDR4 3200MT/s              | 1        | 0.81%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s     | 1        | 0.81%   |
| Kingston RAM KHX2933C17D4/8G 8GB DIMM DDR4 3200MT/s      | 1        | 0.81%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s      | 1        | 0.81%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 1        | 0.81%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1866MT/s   | 1        | 0.81%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s     | 1        | 0.81%   |
| Kingston RAM 99U5584-017.A 4GB DIMM DDR3 1600MT/s        | 1        | 0.81%   |
| Kingston RAM 99U5584-005.A 4GB DIMM DDR3 1600MT/s        | 1        | 0.81%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 0.81%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 68       | 64.76%  |
| DDR3    | 19       | 18.1%   |
| Unknown | 10       | 9.52%   |
| DDR2    | 4        | 3.81%   |
| SDRAM   | 3        | 2.86%   |
| DDR     | 1        | 0.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 94       | 89.52%  |
| SODIMM | 11       | 10.48%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 49       | 44.95%  |
| 8192  | 37       | 33.94%  |
| 1024  | 9        | 8.26%   |
| 2048  | 7        | 6.42%   |
| 16384 | 3        | 2.75%   |
| 512   | 3        | 2.75%   |
| 32768 | 1        | 0.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 36       | 32.43%  |
| 1600    | 13       | 11.71%  |
| 2667    | 10       | 9.01%   |
| 2133    | 10       | 9.01%   |
| 3200    | 5        | 4.5%    |
| 1333    | 5        | 4.5%    |
| 2933    | 4        | 3.6%    |
| Unknown | 4        | 3.6%    |
| 800     | 3        | 2.7%    |
| 667     | 3        | 2.7%    |
| 400     | 3        | 2.7%    |
| 533     | 2        | 1.8%    |
| 333     | 2        | 1.8%    |
| 4333    | 1        | 0.9%    |
| 3534    | 1        | 0.9%    |
| 3533    | 1        | 0.9%    |
| 3333    | 1        | 0.9%    |
| 3266    | 1        | 0.9%    |
| 3151    | 1        | 0.9%    |
| 2666    | 1        | 0.9%    |
| 1867    | 1        | 0.9%    |
| 1866    | 1        | 0.9%    |
| 1066    | 1        | 0.9%    |
| 32      | 1        | 0.9%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 50%     |
| QinHeng Electronics | 1        | 16.67%  |
| Hewlett-Packard     | 1        | 16.67%  |
| Canon               | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Samsung SCX-4200 series        | 1        | 16.67%  |
| Samsung SCX-3200 Series        | 1        | 16.67%  |
| Samsung M332x 382x 402x Series | 1        | 16.67%  |
| QinHeng CH340S                 | 1        | 16.67%  |
| HP LaserJet M402dn             | 1        | 16.67%  |
| Canon MF4410                   | 1        | 16.67%  |

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
| Logitech                | 13       | 56.52%  |
| Alcor Micro             | 6        | 26.09%  |
| Z-Star Microelectronics | 1        | 4.35%   |
| Microsoft               | 1        | 4.35%   |
| Hewlett-Packard         | 1        | 4.35%   |
| Apple                   | 1        | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Logitech Webcam C270               | 8        | 34.78%  |
| Alcor Micro USB 2.0 PC Camera      | 4        | 17.39%  |
| Alcor Micro USB 2.0 Web Camera     | 2        | 8.7%    |
| Z-Star Venus USB2.0 Camera         | 1        | 4.35%   |
| Microsoft LifeCam VX-700           | 1        | 4.35%   |
| Logitech Webcam C930e              | 1        | 4.35%   |
| Logitech HD Webcam C525            | 1        | 4.35%   |
| Logitech HD Pro Webcam C920        | 1        | 4.35%   |
| Logitech C505 HD Webcam            | 1        | 4.35%   |
| Logitech B525 HD Webcam            | 1        | 4.35%   |
| HP Webcam HD 2300                  | 1        | 4.35%   |
| Apple iSight in LED Cinema Display | 1        | 4.35%   |

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
| 0     | 144      | 91.72%  |
| 1     | 11       | 7.01%   |
| 5     | 1        | 0.64%   |
| 2     | 1        | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 7        | 41.18%  |
| Graphics card            | 4        | 23.53%  |
| Multimedia controller    | 2        | 11.76%  |
| Unassigned class         | 1        | 5.88%   |
| Net/wireless             | 1        | 5.88%   |
| Chipcard                 | 1        | 5.88%   |
| Bluetooth                | 1        | 5.88%   |

