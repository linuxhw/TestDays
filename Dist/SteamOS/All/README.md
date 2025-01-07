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

Total: 2764

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Valve         | Galileo                     | Notebook    | [dff6a36e92](https://linux-hardware.org/?probe=dff6a36e92) | Jan 06, 2025 |
| Valve         | Jupiter                     | Notebook    | [586cabc574](https://linux-hardware.org/?probe=586cabc574) | Jan 06, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [271c85b332](https://linux-hardware.org/?probe=271c85b332) | Jan 05, 2025 |
| Valve         | Jupiter                     | Notebook    | [6773d7420e](https://linux-hardware.org/?probe=6773d7420e) | Jan 05, 2025 |
| Valve         | Jupiter                     | Notebook    | [7b2eb9a0e9](https://linux-hardware.org/?probe=7b2eb9a0e9) | Jan 05, 2025 |
| Valve         | Jupiter                     | Notebook    | [5786386be1](https://linux-hardware.org/?probe=5786386be1) | Jan 04, 2025 |
| Valve         | Jupiter                     | Notebook    | [5f851271c3](https://linux-hardware.org/?probe=5f851271c3) | Jan 03, 2025 |
| Valve         | Jupiter                     | Notebook    | [4588bcf961](https://linux-hardware.org/?probe=4588bcf961) | Jan 03, 2025 |
| Valve         | Jupiter                     | Notebook    | [7d460209df](https://linux-hardware.org/?probe=7d460209df) | Jan 03, 2025 |
| Valve         | Jupiter                     | Notebook    | [d8901f7e5b](https://linux-hardware.org/?probe=d8901f7e5b) | Jan 02, 2025 |
| Valve         | Jupiter                     | Notebook    | [699dafa117](https://linux-hardware.org/?probe=699dafa117) | Jan 02, 2025 |
| Valve         | Jupiter                     | Notebook    | [c55e30f87f](https://linux-hardware.org/?probe=c55e30f87f) | Jan 01, 2025 |
| Valve         | Galileo                     | Notebook    | [e1cfe6798d](https://linux-hardware.org/?probe=e1cfe6798d) | Dec 31, 2024 |
| Valve         | Galileo                     | Notebook    | [d2e95667cf](https://linux-hardware.org/?probe=d2e95667cf) | Dec 30, 2024 |
| Valve         | Galileo                     | Notebook    | [d942a63123](https://linux-hardware.org/?probe=d942a63123) | Dec 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [4eb06472bd](https://linux-hardware.org/?probe=4eb06472bd) | Dec 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [0f665464e0](https://linux-hardware.org/?probe=0f665464e0) | Dec 29, 2024 |
| Lenovo        | K14 Gen 1 21CUS0DF00        | Notebook    | [48ba2722d7](https://linux-hardware.org/?probe=48ba2722d7) | Dec 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [9361016877](https://linux-hardware.org/?probe=9361016877) | Dec 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [7ae5afa5ea](https://linux-hardware.org/?probe=7ae5afa5ea) | Dec 28, 2024 |
| Valve         | Galileo                     | Notebook    | [b45df4045a](https://linux-hardware.org/?probe=b45df4045a) | Dec 28, 2024 |
| MSI           | Katana A15 AI B8VE          | Notebook    | [2dc1c3f9ae](https://linux-hardware.org/?probe=2dc1c3f9ae) | Dec 27, 2024 |
| MSI           | Katana A15 AI B8VE          | Notebook    | [ae92e3f945](https://linux-hardware.org/?probe=ae92e3f945) | Dec 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [f13430f9ec](https://linux-hardware.org/?probe=f13430f9ec) | Dec 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [9c8684e346](https://linux-hardware.org/?probe=9c8684e346) | Dec 27, 2024 |
| AYANEO        | 2                           | Tablet      | [811af91e75](https://linux-hardware.org/?probe=811af91e75) | Dec 27, 2024 |
| Valve         | Galileo                     | Notebook    | [c1ae30e981](https://linux-hardware.org/?probe=c1ae30e981) | Dec 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [ccfb809cc8](https://linux-hardware.org/?probe=ccfb809cc8) | Dec 26, 2024 |
| Valve         | Galileo                     | Notebook    | [80b78f46d2](https://linux-hardware.org/?probe=80b78f46d2) | Dec 26, 2024 |
| Valve         | Galileo                     | Notebook    | [9f19e784e4](https://linux-hardware.org/?probe=9f19e784e4) | Dec 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [adf8b11851](https://linux-hardware.org/?probe=adf8b11851) | Dec 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [b2a0e79409](https://linux-hardware.org/?probe=b2a0e79409) | Dec 25, 2024 |
| Valve         | Galileo                     | Notebook    | [c74d7133c4](https://linux-hardware.org/?probe=c74d7133c4) | Dec 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [b795ac1fcd](https://linux-hardware.org/?probe=b795ac1fcd) | Dec 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [fb4323604f](https://linux-hardware.org/?probe=fb4323604f) | Dec 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [7f72a25dab](https://linux-hardware.org/?probe=7f72a25dab) | Dec 24, 2024 |
| Valve         | Galileo                     | Notebook    | [b70e46f7f0](https://linux-hardware.org/?probe=b70e46f7f0) | Dec 22, 2024 |
| Valve         | Galileo                     | Notebook    | [ec69f4be51](https://linux-hardware.org/?probe=ec69f4be51) | Dec 21, 2024 |
| Valve         | Galileo                     | Notebook    | [324e8e320b](https://linux-hardware.org/?probe=324e8e320b) | Dec 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [fbe2a34804](https://linux-hardware.org/?probe=fbe2a34804) | Dec 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [96ec07b5d4](https://linux-hardware.org/?probe=96ec07b5d4) | Dec 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [9b99dd7185](https://linux-hardware.org/?probe=9b99dd7185) | Dec 19, 2024 |
| Valve         | Galileo                     | Notebook    | [45a67a7577](https://linux-hardware.org/?probe=45a67a7577) | Dec 19, 2024 |
| Valve         | Galileo                     | Notebook    | [edfdc80209](https://linux-hardware.org/?probe=edfdc80209) | Dec 18, 2024 |
| Valve         | Galileo                     | Notebook    | [92b2090648](https://linux-hardware.org/?probe=92b2090648) | Dec 17, 2024 |
| Valve         | Galileo                     | Notebook    | [860b42a1d3](https://linux-hardware.org/?probe=860b42a1d3) | Dec 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [23d9275334](https://linux-hardware.org/?probe=23d9275334) | Dec 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [507ba3c279](https://linux-hardware.org/?probe=507ba3c279) | Dec 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [cb6ebf4600](https://linux-hardware.org/?probe=cb6ebf4600) | Dec 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [246668e9eb](https://linux-hardware.org/?probe=246668e9eb) | Dec 16, 2024 |
| Valve         | Galileo                     | Notebook    | [b74863c36c](https://linux-hardware.org/?probe=b74863c36c) | Dec 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [120418f0e3](https://linux-hardware.org/?probe=120418f0e3) | Dec 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [3b34c56811](https://linux-hardware.org/?probe=3b34c56811) | Dec 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [f0f29070ae](https://linux-hardware.org/?probe=f0f29070ae) | Dec 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [7f3601393d](https://linux-hardware.org/?probe=7f3601393d) | Dec 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [2f36d7df07](https://linux-hardware.org/?probe=2f36d7df07) | Dec 13, 2024 |
| Valve         | Galileo                     | Notebook    | [79f765f659](https://linux-hardware.org/?probe=79f765f659) | Dec 13, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [0942a5a5e2](https://linux-hardware.org/?probe=0942a5a5e2) | Dec 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [24bbbbae23](https://linux-hardware.org/?probe=24bbbbae23) | Dec 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [63ff703069](https://linux-hardware.org/?probe=63ff703069) | Dec 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [62a914e297](https://linux-hardware.org/?probe=62a914e297) | Dec 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [a9e67f8e9c](https://linux-hardware.org/?probe=a9e67f8e9c) | Dec 11, 2024 |
| Valve         | Galileo                     | Notebook    | [b2cbfb3cf8](https://linux-hardware.org/?probe=b2cbfb3cf8) | Dec 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [676c01342e](https://linux-hardware.org/?probe=676c01342e) | Dec 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [483676eaaa](https://linux-hardware.org/?probe=483676eaaa) | Dec 10, 2024 |
| Valve         | Galileo                     | Notebook    | [43f1ef2e9b](https://linux-hardware.org/?probe=43f1ef2e9b) | Dec 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [b81aceb033](https://linux-hardware.org/?probe=b81aceb033) | Dec 09, 2024 |
| Valve         | Galileo                     | Notebook    | [3ca96a14e6](https://linux-hardware.org/?probe=3ca96a14e6) | Dec 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [adf22162c5](https://linux-hardware.org/?probe=adf22162c5) | Dec 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [ef940ccf9e](https://linux-hardware.org/?probe=ef940ccf9e) | Dec 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [b1d1e201ac](https://linux-hardware.org/?probe=b1d1e201ac) | Dec 08, 2024 |
| Valve         | Galileo                     | Notebook    | [cff59fadd6](https://linux-hardware.org/?probe=cff59fadd6) | Dec 07, 2024 |
| Valve         | Galileo                     | Notebook    | [b2e558b6d3](https://linux-hardware.org/?probe=b2e558b6d3) | Dec 07, 2024 |
| Valve         | Galileo                     | Notebook    | [cabb8134bf](https://linux-hardware.org/?probe=cabb8134bf) | Dec 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [71db1ec209](https://linux-hardware.org/?probe=71db1ec209) | Dec 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [2fbfef599f](https://linux-hardware.org/?probe=2fbfef599f) | Dec 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [ed49188fcb](https://linux-hardware.org/?probe=ed49188fcb) | Dec 04, 2024 |
| Valve         | Galileo                     | Notebook    | [79c8763d17](https://linux-hardware.org/?probe=79c8763d17) | Dec 02, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [cb38e7215b](https://linux-hardware.org/?probe=cb38e7215b) | Dec 01, 2024 |
| Valve         | Galileo                     | Notebook    | [93e70f8f51](https://linux-hardware.org/?probe=93e70f8f51) | Dec 01, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [14584a3f16](https://linux-hardware.org/?probe=14584a3f16) | Dec 01, 2024 |
| Valve         | Galileo                     | Notebook    | [d08c4aac64](https://linux-hardware.org/?probe=d08c4aac64) | Nov 29, 2024 |
| Valve         | Galileo                     | Notebook    | [13c5cb5602](https://linux-hardware.org/?probe=13c5cb5602) | Nov 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [82f1b41d19](https://linux-hardware.org/?probe=82f1b41d19) | Nov 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [41901475f6](https://linux-hardware.org/?probe=41901475f6) | Nov 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [6597b78dae](https://linux-hardware.org/?probe=6597b78dae) | Nov 27, 2024 |
| Valve         | Galileo                     | Notebook    | [1d7f88265d](https://linux-hardware.org/?probe=1d7f88265d) | Nov 26, 2024 |
| Valve         | Galileo                     | Notebook    | [d91eb8bcf7](https://linux-hardware.org/?probe=d91eb8bcf7) | Nov 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [211b17a37a](https://linux-hardware.org/?probe=211b17a37a) | Nov 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [202fad7ad9](https://linux-hardware.org/?probe=202fad7ad9) | Nov 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [99d0e12698](https://linux-hardware.org/?probe=99d0e12698) | Nov 24, 2024 |
| Valve         | Galileo                     | Notebook    | [df851043c9](https://linux-hardware.org/?probe=df851043c9) | Nov 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [4bf52db455](https://linux-hardware.org/?probe=4bf52db455) | Nov 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [af03db7c27](https://linux-hardware.org/?probe=af03db7c27) | Nov 23, 2024 |
| Dell          | Latitude 5430               | Notebook    | [cbb4970afb](https://linux-hardware.org/?probe=cbb4970afb) | Nov 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [e0e7192eba](https://linux-hardware.org/?probe=e0e7192eba) | Nov 22, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e67448179d](https://linux-hardware.org/?probe=e67448179d) | Nov 22, 2024 |
| Dell          | Latitude 5430               | Notebook    | [7123ed49f7](https://linux-hardware.org/?probe=7123ed49f7) | Nov 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [01d5857ef9](https://linux-hardware.org/?probe=01d5857ef9) | Nov 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [c182c36dba](https://linux-hardware.org/?probe=c182c36dba) | Nov 22, 2024 |
| Valve         | Galileo                     | Notebook    | [675c70d8dd](https://linux-hardware.org/?probe=675c70d8dd) | Nov 22, 2024 |
| Valve         | Galileo                     | Notebook    | [6e6122bf10](https://linux-hardware.org/?probe=6e6122bf10) | Nov 22, 2024 |
| Valve         | Galileo                     | Notebook    | [918ab68150](https://linux-hardware.org/?probe=918ab68150) | Nov 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [228a34d78e](https://linux-hardware.org/?probe=228a34d78e) | Nov 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [ac34137963](https://linux-hardware.org/?probe=ac34137963) | Nov 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [3011f248cc](https://linux-hardware.org/?probe=3011f248cc) | Nov 21, 2024 |
| Valve         | Galileo                     | Notebook    | [c7d8b70b76](https://linux-hardware.org/?probe=c7d8b70b76) | Nov 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [76f910e120](https://linux-hardware.org/?probe=76f910e120) | Nov 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [fc95853dd8](https://linux-hardware.org/?probe=fc95853dd8) | Nov 19, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [b1fc0f41f0](https://linux-hardware.org/?probe=b1fc0f41f0) | Nov 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [c07ea0753c](https://linux-hardware.org/?probe=c07ea0753c) | Nov 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [5e6f8b0b19](https://linux-hardware.org/?probe=5e6f8b0b19) | Nov 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [1caa8b41f8](https://linux-hardware.org/?probe=1caa8b41f8) | Nov 14, 2024 |
| Valve         | Galileo                     | Notebook    | [fd4e0a6266](https://linux-hardware.org/?probe=fd4e0a6266) | Nov 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [158bfeec61](https://linux-hardware.org/?probe=158bfeec61) | Nov 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [77c6929edc](https://linux-hardware.org/?probe=77c6929edc) | Nov 13, 2024 |
| Valve         | Galileo                     | Notebook    | [59e09fa093](https://linux-hardware.org/?probe=59e09fa093) | Nov 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [7e2bf5246b](https://linux-hardware.org/?probe=7e2bf5246b) | Nov 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [14aba31e19](https://linux-hardware.org/?probe=14aba31e19) | Nov 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [d837e0a19f](https://linux-hardware.org/?probe=d837e0a19f) | Nov 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [d99256d583](https://linux-hardware.org/?probe=d99256d583) | Nov 11, 2024 |
| MSI           | GF63 Thin 11SC              | Notebook    | [ae90933824](https://linux-hardware.org/?probe=ae90933824) | Nov 11, 2024 |
| MSI           | GF63 Thin 11SC              | Notebook    | [8ee9854eca](https://linux-hardware.org/?probe=8ee9854eca) | Nov 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [bc6dab074b](https://linux-hardware.org/?probe=bc6dab074b) | Nov 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [58bc3fd29d](https://linux-hardware.org/?probe=58bc3fd29d) | Nov 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [f811772f91](https://linux-hardware.org/?probe=f811772f91) | Nov 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [709ca74058](https://linux-hardware.org/?probe=709ca74058) | Nov 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [fd09d3aa1f](https://linux-hardware.org/?probe=fd09d3aa1f) | Nov 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [e121f7e4c8](https://linux-hardware.org/?probe=e121f7e4c8) | Nov 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [0959d23059](https://linux-hardware.org/?probe=0959d23059) | Nov 08, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [db873cebfd](https://linux-hardware.org/?probe=db873cebfd) | Nov 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [03f86ae260](https://linux-hardware.org/?probe=03f86ae260) | Nov 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [1f8e59f5f3](https://linux-hardware.org/?probe=1f8e59f5f3) | Nov 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [f53913cff8](https://linux-hardware.org/?probe=f53913cff8) | Nov 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [44366fc1ea](https://linux-hardware.org/?probe=44366fc1ea) | Nov 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [3303b99e5b](https://linux-hardware.org/?probe=3303b99e5b) | Nov 06, 2024 |
| Valve         | Galileo                     | Notebook    | [9a91afe08a](https://linux-hardware.org/?probe=9a91afe08a) | Nov 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [fd2f3ef339](https://linux-hardware.org/?probe=fd2f3ef339) | Nov 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [d4a4913c3f](https://linux-hardware.org/?probe=d4a4913c3f) | Nov 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [b2b7dd85c2](https://linux-hardware.org/?probe=b2b7dd85c2) | Nov 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [6c907b73a0](https://linux-hardware.org/?probe=6c907b73a0) | Nov 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [841e474828](https://linux-hardware.org/?probe=841e474828) | Nov 02, 2024 |
| Valve         | Galileo                     | Notebook    | [1903569037](https://linux-hardware.org/?probe=1903569037) | Nov 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [21f659115d](https://linux-hardware.org/?probe=21f659115d) | Nov 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [8a5b502e6a](https://linux-hardware.org/?probe=8a5b502e6a) | Oct 31, 2024 |
| Valve         | Jupiter                     | Notebook    | [a3d6710722](https://linux-hardware.org/?probe=a3d6710722) | Oct 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [b0b7fe3be6](https://linux-hardware.org/?probe=b0b7fe3be6) | Oct 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [60613a7f13](https://linux-hardware.org/?probe=60613a7f13) | Oct 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [9975d4d5b2](https://linux-hardware.org/?probe=9975d4d5b2) | Oct 30, 2024 |
| Valve         | Galileo                     | Notebook    | [68c748ec7b](https://linux-hardware.org/?probe=68c748ec7b) | Oct 29, 2024 |
| Valve         | Galileo                     | Notebook    | [eb2265793c](https://linux-hardware.org/?probe=eb2265793c) | Oct 29, 2024 |
| Valve         | Galileo                     | Notebook    | [c601d4f6cf](https://linux-hardware.org/?probe=c601d4f6cf) | Oct 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [225bf78915](https://linux-hardware.org/?probe=225bf78915) | Oct 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [9da334fd4b](https://linux-hardware.org/?probe=9da334fd4b) | Oct 27, 2024 |
| Valve         | Galileo                     | Notebook    | [e93312d73e](https://linux-hardware.org/?probe=e93312d73e) | Oct 27, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [7d770e159c](https://linux-hardware.org/?probe=7d770e159c) | Oct 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [d174ca7015](https://linux-hardware.org/?probe=d174ca7015) | Oct 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [e0047b5e92](https://linux-hardware.org/?probe=e0047b5e92) | Oct 23, 2024 |
| Valve         | Galileo                     | Notebook    | [3c5b93427d](https://linux-hardware.org/?probe=3c5b93427d) | Oct 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [b40269dd83](https://linux-hardware.org/?probe=b40269dd83) | Oct 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [5ad2363702](https://linux-hardware.org/?probe=5ad2363702) | Oct 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [4c527e81c9](https://linux-hardware.org/?probe=4c527e81c9) | Oct 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [b6f3c1b874](https://linux-hardware.org/?probe=b6f3c1b874) | Oct 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [d445573740](https://linux-hardware.org/?probe=d445573740) | Oct 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [63401adb43](https://linux-hardware.org/?probe=63401adb43) | Oct 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [e5d63f0a37](https://linux-hardware.org/?probe=e5d63f0a37) | Oct 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [63da83d9d0](https://linux-hardware.org/?probe=63da83d9d0) | Oct 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [45ee9ed099](https://linux-hardware.org/?probe=45ee9ed099) | Oct 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [33929e23ed](https://linux-hardware.org/?probe=33929e23ed) | Oct 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [920099bf75](https://linux-hardware.org/?probe=920099bf75) | Oct 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [2ec35611ed](https://linux-hardware.org/?probe=2ec35611ed) | Oct 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [8eacd0551d](https://linux-hardware.org/?probe=8eacd0551d) | Oct 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [5e6e73d7d0](https://linux-hardware.org/?probe=5e6e73d7d0) | Oct 19, 2024 |
| Valve         | Galileo                     | Notebook    | [04566e19f7](https://linux-hardware.org/?probe=04566e19f7) | Oct 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [c857c25534](https://linux-hardware.org/?probe=c857c25534) | Oct 18, 2024 |
| Valve         | Galileo                     | Notebook    | [6fcae86bfc](https://linux-hardware.org/?probe=6fcae86bfc) | Oct 16, 2024 |
| Valve         | Galileo                     | Notebook    | [63a52c61c4](https://linux-hardware.org/?probe=63a52c61c4) | Oct 14, 2024 |
| Valve         | Galileo                     | Notebook    | [f1ddf3e7f6](https://linux-hardware.org/?probe=f1ddf3e7f6) | Oct 14, 2024 |
| Valve         | Galileo                     | Notebook    | [23e2beaac2](https://linux-hardware.org/?probe=23e2beaac2) | Oct 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [5a883c2366](https://linux-hardware.org/?probe=5a883c2366) | Oct 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [2e2320aaa0](https://linux-hardware.org/?probe=2e2320aaa0) | Oct 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [d69953f1a7](https://linux-hardware.org/?probe=d69953f1a7) | Oct 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [dd814ebab8](https://linux-hardware.org/?probe=dd814ebab8) | Oct 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [2cc13c14ff](https://linux-hardware.org/?probe=2cc13c14ff) | Oct 11, 2024 |
| MSI           | Claw A1M                    | Tablet      | [2ebde0820d](https://linux-hardware.org/?probe=2ebde0820d) | Oct 11, 2024 |
| MSI           | Claw A1M                    | Tablet      | [1f688c697a](https://linux-hardware.org/?probe=1f688c697a) | Oct 11, 2024 |
| Valve         | Galileo                     | Notebook    | [772619a68f](https://linux-hardware.org/?probe=772619a68f) | Oct 11, 2024 |
| Valve         | Galileo                     | Notebook    | [df3b9380db](https://linux-hardware.org/?probe=df3b9380db) | Oct 11, 2024 |
| Valve         | Galileo                     | Notebook    | [36d203ab8a](https://linux-hardware.org/?probe=36d203ab8a) | Oct 10, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6481acc825](https://linux-hardware.org/?probe=6481acc825) | Oct 10, 2024 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [204b016d66](https://linux-hardware.org/?probe=204b016d66) | Oct 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [ea91cd0b04](https://linux-hardware.org/?probe=ea91cd0b04) | Oct 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [d9e32fbd56](https://linux-hardware.org/?probe=d9e32fbd56) | Oct 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [e40215b793](https://linux-hardware.org/?probe=e40215b793) | Oct 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [a805cc579d](https://linux-hardware.org/?probe=a805cc579d) | Oct 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [3ea99e78e1](https://linux-hardware.org/?probe=3ea99e78e1) | Oct 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [ca1c672297](https://linux-hardware.org/?probe=ca1c672297) | Oct 07, 2024 |
| Valve         | Galileo                     | Notebook    | [db5a96a4c7](https://linux-hardware.org/?probe=db5a96a4c7) | Oct 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [0bf769af9a](https://linux-hardware.org/?probe=0bf769af9a) | Oct 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [99f6a817e8](https://linux-hardware.org/?probe=99f6a817e8) | Oct 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [370c6c0007](https://linux-hardware.org/?probe=370c6c0007) | Oct 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [979b04a3ab](https://linux-hardware.org/?probe=979b04a3ab) | Oct 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [1989d5320d](https://linux-hardware.org/?probe=1989d5320d) | Oct 05, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [86664c2cf3](https://linux-hardware.org/?probe=86664c2cf3) | Oct 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [bad1281ef5](https://linux-hardware.org/?probe=bad1281ef5) | Oct 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [65e207a462](https://linux-hardware.org/?probe=65e207a462) | Oct 04, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ccee521d6](https://linux-hardware.org/?probe=0ccee521d6) | Oct 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [35bec4da6c](https://linux-hardware.org/?probe=35bec4da6c) | Oct 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [98801dba2b](https://linux-hardware.org/?probe=98801dba2b) | Oct 04, 2024 |
| Valve         | Galileo                     | Notebook    | [a8bc5582e6](https://linux-hardware.org/?probe=a8bc5582e6) | Oct 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [5900be6c19](https://linux-hardware.org/?probe=5900be6c19) | Oct 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [f98b374914](https://linux-hardware.org/?probe=f98b374914) | Oct 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [f72decd0b9](https://linux-hardware.org/?probe=f72decd0b9) | Oct 02, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c23e41e809](https://linux-hardware.org/?probe=c23e41e809) | Oct 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [1779729d2b](https://linux-hardware.org/?probe=1779729d2b) | Oct 02, 2024 |
| Dell          | 0FDY5C A00                  | Desktop     | [2975c3986e](https://linux-hardware.org/?probe=2975c3986e) | Oct 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [2940d61004](https://linux-hardware.org/?probe=2940d61004) | Oct 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [27563b6975](https://linux-hardware.org/?probe=27563b6975) | Oct 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [3c3d65b534](https://linux-hardware.org/?probe=3c3d65b534) | Oct 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [93ca7d99ed](https://linux-hardware.org/?probe=93ca7d99ed) | Sep 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [8da5ea058b](https://linux-hardware.org/?probe=8da5ea058b) | Sep 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [3b4228b0a8](https://linux-hardware.org/?probe=3b4228b0a8) | Sep 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [8648722c09](https://linux-hardware.org/?probe=8648722c09) | Sep 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [768ea67256](https://linux-hardware.org/?probe=768ea67256) | Sep 29, 2024 |
| Valve         | Galileo                     | Notebook    | [477b1133ae](https://linux-hardware.org/?probe=477b1133ae) | Sep 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [aeeb11bdf0](https://linux-hardware.org/?probe=aeeb11bdf0) | Sep 28, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [9e6105fdd5](https://linux-hardware.org/?probe=9e6105fdd5) | Sep 27, 2024 |
| Valve         | Galileo                     | Notebook    | [c82a27eaec](https://linux-hardware.org/?probe=c82a27eaec) | Sep 27, 2024 |
| Valve         | Galileo                     | Notebook    | [b277c3ef80](https://linux-hardware.org/?probe=b277c3ef80) | Sep 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [6601d8e1d4](https://linux-hardware.org/?probe=6601d8e1d4) | Sep 26, 2024 |
| Lenovo        | SDK0E50510 WIN 262507025... | Desktop     | [26d5a61655](https://linux-hardware.org/?probe=26d5a61655) | Sep 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [d9d44448bb](https://linux-hardware.org/?probe=d9d44448bb) | Sep 25, 2024 |
| Dell          | Latitude 7420               | Convertible | [00de068c6e](https://linux-hardware.org/?probe=00de068c6e) | Sep 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [79fd38469f](https://linux-hardware.org/?probe=79fd38469f) | Sep 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [53f14c8959](https://linux-hardware.org/?probe=53f14c8959) | Sep 24, 2024 |
| Valve         | Galileo                     | Notebook    | [5dbf0a6bc5](https://linux-hardware.org/?probe=5dbf0a6bc5) | Sep 24, 2024 |
| Valve         | Galileo                     | Notebook    | [8ab5e110e2](https://linux-hardware.org/?probe=8ab5e110e2) | Sep 24, 2024 |
| Valve         | Galileo                     | Notebook    | [c863bb9916](https://linux-hardware.org/?probe=c863bb9916) | Sep 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [9a260645fb](https://linux-hardware.org/?probe=9a260645fb) | Sep 23, 2024 |
| Valve         | Galileo                     | Notebook    | [8a2afaa250](https://linux-hardware.org/?probe=8a2afaa250) | Sep 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [973335ffcd](https://linux-hardware.org/?probe=973335ffcd) | Sep 21, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [07dc4c9a19](https://linux-hardware.org/?probe=07dc4c9a19) | Sep 20, 2024 |
| Valve         | Galileo                     | Notebook    | [992862f220](https://linux-hardware.org/?probe=992862f220) | Sep 20, 2024 |
| QIYIDA        | ED4 V1.1                    | Desktop     | [57a88e488a](https://linux-hardware.org/?probe=57a88e488a) | Sep 19, 2024 |
| Valve         | Galileo                     | Notebook    | [abb70c0daa](https://linux-hardware.org/?probe=abb70c0daa) | Sep 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [2936fd354a](https://linux-hardware.org/?probe=2936fd354a) | Sep 18, 2024 |
| ASUSTek       | GR8 II-K                    | Desktop     | [d7a4d66200](https://linux-hardware.org/?probe=d7a4d66200) | Sep 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [86fdf5655d](https://linux-hardware.org/?probe=86fdf5655d) | Sep 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [858c073c1e](https://linux-hardware.org/?probe=858c073c1e) | Sep 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [eedc2c681f](https://linux-hardware.org/?probe=eedc2c681f) | Sep 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [2997a5ca44](https://linux-hardware.org/?probe=2997a5ca44) | Sep 14, 2024 |
| Valve         | Galileo                     | Notebook    | [22dbd35551](https://linux-hardware.org/?probe=22dbd35551) | Sep 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [1d1a8ff915](https://linux-hardware.org/?probe=1d1a8ff915) | Sep 14, 2024 |
| Valve         | Galileo                     | Notebook    | [5416889c08](https://linux-hardware.org/?probe=5416889c08) | Sep 14, 2024 |
| Valve         | Galileo                     | Notebook    | [eeb76e5318](https://linux-hardware.org/?probe=eeb76e5318) | Sep 13, 2024 |
| Valve         | Galileo                     | Notebook    | [2bde8a5931](https://linux-hardware.org/?probe=2bde8a5931) | Sep 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [de8469ded0](https://linux-hardware.org/?probe=de8469ded0) | Sep 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [f1e5915a56](https://linux-hardware.org/?probe=f1e5915a56) | Sep 13, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [72fe68b845](https://linux-hardware.org/?probe=72fe68b845) | Sep 12, 2024 |
| Valve         | Galileo                     | Notebook    | [0bd0a69491](https://linux-hardware.org/?probe=0bd0a69491) | Sep 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [46870d6ecc](https://linux-hardware.org/?probe=46870d6ecc) | Sep 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [e07df1fb70](https://linux-hardware.org/?probe=e07df1fb70) | Sep 11, 2024 |
| Valve         | Galileo                     | Notebook    | [eeed33b4c4](https://linux-hardware.org/?probe=eeed33b4c4) | Sep 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [0e77bc77fb](https://linux-hardware.org/?probe=0e77bc77fb) | Sep 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [6ea3fd02fa](https://linux-hardware.org/?probe=6ea3fd02fa) | Sep 09, 2024 |
| Valve         | Galileo                     | Notebook    | [972b28cbc9](https://linux-hardware.org/?probe=972b28cbc9) | Sep 08, 2024 |
| Valve         | Galileo                     | Notebook    | [7f727c54c9](https://linux-hardware.org/?probe=7f727c54c9) | Sep 08, 2024 |
| Valve         | Galileo                     | Notebook    | [c5b1328aa0](https://linux-hardware.org/?probe=c5b1328aa0) | Sep 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [8c37e0ced7](https://linux-hardware.org/?probe=8c37e0ced7) | Sep 08, 2024 |
| Apple         | MacBookPro15,1              | Notebook    | [70759ce2d6](https://linux-hardware.org/?probe=70759ce2d6) | Sep 08, 2024 |
| Apple         | MacBookPro15,1              | Notebook    | [719e065b1a](https://linux-hardware.org/?probe=719e065b1a) | Sep 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [749c1a9107](https://linux-hardware.org/?probe=749c1a9107) | Sep 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [708c2f4588](https://linux-hardware.org/?probe=708c2f4588) | Sep 07, 2024 |
| Valve         | Galileo                     | Notebook    | [405c8c012c](https://linux-hardware.org/?probe=405c8c012c) | Sep 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [14b176dee2](https://linux-hardware.org/?probe=14b176dee2) | Sep 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [bcb696a01c](https://linux-hardware.org/?probe=bcb696a01c) | Sep 07, 2024 |
| Valve         | Galileo                     | Notebook    | [947f9c3752](https://linux-hardware.org/?probe=947f9c3752) | Sep 06, 2024 |
| Valve         | Galileo                     | Notebook    | [cd1ff09df0](https://linux-hardware.org/?probe=cd1ff09df0) | Sep 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [96d9e41b2c](https://linux-hardware.org/?probe=96d9e41b2c) | Sep 06, 2024 |
| Dell          | 0KWVT8 A03                  | Desktop     | [737215a158](https://linux-hardware.org/?probe=737215a158) | Sep 06, 2024 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [9d4c7f50f3](https://linux-hardware.org/?probe=9d4c7f50f3) | Sep 05, 2024 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [a57db85eec](https://linux-hardware.org/?probe=a57db85eec) | Sep 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [6c3cc50159](https://linux-hardware.org/?probe=6c3cc50159) | Sep 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [6701bd7646](https://linux-hardware.org/?probe=6701bd7646) | Sep 05, 2024 |
| Intel         | X99                         | Desktop     | [cb1938142e](https://linux-hardware.org/?probe=cb1938142e) | Sep 04, 2024 |
| Valve         | Galileo                     | Notebook    | [e046c21d5d](https://linux-hardware.org/?probe=e046c21d5d) | Sep 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [eec8034fe9](https://linux-hardware.org/?probe=eec8034fe9) | Sep 04, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [709c1de688](https://linux-hardware.org/?probe=709c1de688) | Sep 03, 2024 |
| Valve         | Galileo                     | Notebook    | [2e9ee3c9c4](https://linux-hardware.org/?probe=2e9ee3c9c4) | Sep 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [ef47bd111b](https://linux-hardware.org/?probe=ef47bd111b) | Sep 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [c8cb9ebca0](https://linux-hardware.org/?probe=c8cb9ebca0) | Sep 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [60fa984831](https://linux-hardware.org/?probe=60fa984831) | Sep 01, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [07e82620c8](https://linux-hardware.org/?probe=07e82620c8) | Sep 01, 2024 |
| Valve         | Galileo                     | Notebook    | [a5f332f085](https://linux-hardware.org/?probe=a5f332f085) | Sep 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [a5c6081620](https://linux-hardware.org/?probe=a5c6081620) | Sep 01, 2024 |
| ASRock        | AB350M Pro4                 | Desktop     | [cb21643ddb](https://linux-hardware.org/?probe=cb21643ddb) | Sep 01, 2024 |
| ASRock        | AB350M Pro4                 | Desktop     | [07d5926eb0](https://linux-hardware.org/?probe=07d5926eb0) | Aug 31, 2024 |
| Valve         | Jupiter                     | Notebook    | [909ac8e9f1](https://linux-hardware.org/?probe=909ac8e9f1) | Aug 31, 2024 |
| Valve         | Jupiter                     | Notebook    | [2037b82683](https://linux-hardware.org/?probe=2037b82683) | Aug 30, 2024 |
| Valve         | Galileo                     | Notebook    | [a77fcccef5](https://linux-hardware.org/?probe=a77fcccef5) | Aug 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [38523d49eb](https://linux-hardware.org/?probe=38523d49eb) | Aug 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [a5dc4542d4](https://linux-hardware.org/?probe=a5dc4542d4) | Aug 29, 2024 |
| Valve         | Galileo                     | Notebook    | [b8d77aa175](https://linux-hardware.org/?probe=b8d77aa175) | Aug 29, 2024 |
| Valve         | Galileo                     | Notebook    | [72ef15cff5](https://linux-hardware.org/?probe=72ef15cff5) | Aug 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [79b44d89aa](https://linux-hardware.org/?probe=79b44d89aa) | Aug 29, 2024 |
| MSI           | MPG Z790I EDGE WIFI         | Desktop     | [befece1a07](https://linux-hardware.org/?probe=befece1a07) | Aug 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [72a6ce8827](https://linux-hardware.org/?probe=72a6ce8827) | Aug 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [cdfa0ca346](https://linux-hardware.org/?probe=cdfa0ca346) | Aug 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [2ea4673f0e](https://linux-hardware.org/?probe=2ea4673f0e) | Aug 28, 2024 |
| Valve         | Galileo                     | Notebook    | [71ce12da6b](https://linux-hardware.org/?probe=71ce12da6b) | Aug 27, 2024 |
| Valve         | Galileo                     | Notebook    | [8f13ce096b](https://linux-hardware.org/?probe=8f13ce096b) | Aug 27, 2024 |
| Valve         | Galileo                     | Notebook    | [135e9f012e](https://linux-hardware.org/?probe=135e9f012e) | Aug 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [e301eba8d6](https://linux-hardware.org/?probe=e301eba8d6) | Aug 26, 2024 |
| Valve         | Galileo                     | Notebook    | [f835c659b4](https://linux-hardware.org/?probe=f835c659b4) | Aug 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [f8ceed077b](https://linux-hardware.org/?probe=f8ceed077b) | Aug 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [8327c9d2da](https://linux-hardware.org/?probe=8327c9d2da) | Aug 25, 2024 |
| Valve         | Galileo                     | Notebook    | [b876dad1ae](https://linux-hardware.org/?probe=b876dad1ae) | Aug 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [f586184770](https://linux-hardware.org/?probe=f586184770) | Aug 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [eec8a2799b](https://linux-hardware.org/?probe=eec8a2799b) | Aug 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [ce5ec75cd3](https://linux-hardware.org/?probe=ce5ec75cd3) | Aug 23, 2024 |
| Valve         | Galileo                     | Notebook    | [8f9e373748](https://linux-hardware.org/?probe=8f9e373748) | Aug 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [124cf78dc4](https://linux-hardware.org/?probe=124cf78dc4) | Aug 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [d9cd6bebc7](https://linux-hardware.org/?probe=d9cd6bebc7) | Aug 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [804c8de645](https://linux-hardware.org/?probe=804c8de645) | Aug 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [e7cf12d289](https://linux-hardware.org/?probe=e7cf12d289) | Aug 21, 2024 |
| Valve         | Galileo                     | Notebook    | [e308116ec5](https://linux-hardware.org/?probe=e308116ec5) | Aug 21, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [ff71054b4c](https://linux-hardware.org/?probe=ff71054b4c) | Aug 20, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [1cceda0c67](https://linux-hardware.org/?probe=1cceda0c67) | Aug 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [018a72ea27](https://linux-hardware.org/?probe=018a72ea27) | Aug 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [2d0a0de254](https://linux-hardware.org/?probe=2d0a0de254) | Aug 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [aeb49efec1](https://linux-hardware.org/?probe=aeb49efec1) | Aug 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [e89225da18](https://linux-hardware.org/?probe=e89225da18) | Aug 20, 2024 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b573981587](https://linux-hardware.org/?probe=b573981587) | Aug 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [b230861d43](https://linux-hardware.org/?probe=b230861d43) | Aug 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [9682fb547b](https://linux-hardware.org/?probe=9682fb547b) | Aug 19, 2024 |
| Valve         | Galileo                     | Notebook    | [9ab8a63f8e](https://linux-hardware.org/?probe=9ab8a63f8e) | Aug 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [1ac487a1f3](https://linux-hardware.org/?probe=1ac487a1f3) | Aug 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [5086032317](https://linux-hardware.org/?probe=5086032317) | Aug 18, 2024 |
| Valve         | Galileo                     | Notebook    | [7f06be1644](https://linux-hardware.org/?probe=7f06be1644) | Aug 18, 2024 |
| Valve         | Galileo                     | Notebook    | [07009ffd33](https://linux-hardware.org/?probe=07009ffd33) | Aug 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [27a29cca1a](https://linux-hardware.org/?probe=27a29cca1a) | Aug 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [d888a53e4e](https://linux-hardware.org/?probe=d888a53e4e) | Aug 18, 2024 |
| Gigabyte      | X670E AORUS PRO X           | Desktop     | [0182b82b41](https://linux-hardware.org/?probe=0182b82b41) | Aug 17, 2024 |
| Valve         | Galileo                     | Notebook    | [2ee8cf64bf](https://linux-hardware.org/?probe=2ee8cf64bf) | Aug 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [7cf94a8418](https://linux-hardware.org/?probe=7cf94a8418) | Aug 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [c2c96a7641](https://linux-hardware.org/?probe=c2c96a7641) | Aug 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [10f3e1bca7](https://linux-hardware.org/?probe=10f3e1bca7) | Aug 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [27dfedf4e0](https://linux-hardware.org/?probe=27dfedf4e0) | Aug 15, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6866176fe2](https://linux-hardware.org/?probe=6866176fe2) | Aug 14, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [bdd81784d4](https://linux-hardware.org/?probe=bdd81784d4) | Aug 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [4a329e739e](https://linux-hardware.org/?probe=4a329e739e) | Aug 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [10ab7a64bc](https://linux-hardware.org/?probe=10ab7a64bc) | Aug 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [256d85532a](https://linux-hardware.org/?probe=256d85532a) | Aug 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [17b52afc47](https://linux-hardware.org/?probe=17b52afc47) | Aug 13, 2024 |
| AYANEO        | AB05-AMD                    | Notebook    | [02faa3b46c](https://linux-hardware.org/?probe=02faa3b46c) | Aug 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [9de056a428](https://linux-hardware.org/?probe=9de056a428) | Aug 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [6149439ea6](https://linux-hardware.org/?probe=6149439ea6) | Aug 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [77dfc77c5f](https://linux-hardware.org/?probe=77dfc77c5f) | Aug 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [492a7be38c](https://linux-hardware.org/?probe=492a7be38c) | Aug 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [970eaf56d1](https://linux-hardware.org/?probe=970eaf56d1) | Aug 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [02c0bbefd7](https://linux-hardware.org/?probe=02c0bbefd7) | Aug 10, 2024 |
| Valve         | Galileo                     | Notebook    | [207810999c](https://linux-hardware.org/?probe=207810999c) | Aug 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [e1a39d93fc](https://linux-hardware.org/?probe=e1a39d93fc) | Aug 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [12921125a4](https://linux-hardware.org/?probe=12921125a4) | Aug 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [548d0048d4](https://linux-hardware.org/?probe=548d0048d4) | Aug 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [9a05cb0410](https://linux-hardware.org/?probe=9a05cb0410) | Aug 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [2345802b02](https://linux-hardware.org/?probe=2345802b02) | Aug 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [ec60ec441b](https://linux-hardware.org/?probe=ec60ec441b) | Aug 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [c7b59219b7](https://linux-hardware.org/?probe=c7b59219b7) | Aug 08, 2024 |
| Valve         | Galileo                     | Notebook    | [1b2c7d183d](https://linux-hardware.org/?probe=1b2c7d183d) | Aug 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [f3be9e3a4d](https://linux-hardware.org/?probe=f3be9e3a4d) | Aug 08, 2024 |
| Valve         | Galileo                     | Notebook    | [255bf14975](https://linux-hardware.org/?probe=255bf14975) | Aug 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [644bccbed5](https://linux-hardware.org/?probe=644bccbed5) | Aug 07, 2024 |
| Valve         | Galileo                     | Notebook    | [120ecc4cd1](https://linux-hardware.org/?probe=120ecc4cd1) | Aug 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [10557734f4](https://linux-hardware.org/?probe=10557734f4) | Aug 07, 2024 |
| GPD           | WIN2                        | Notebook    | [1fe989fad1](https://linux-hardware.org/?probe=1fe989fad1) | Aug 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [351c25c227](https://linux-hardware.org/?probe=351c25c227) | Aug 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [b9e860d80b](https://linux-hardware.org/?probe=b9e860d80b) | Aug 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [990f43a660](https://linux-hardware.org/?probe=990f43a660) | Aug 06, 2024 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [24119bdb5e](https://linux-hardware.org/?probe=24119bdb5e) | Aug 05, 2024 |
| Valve         | Galileo                     | Notebook    | [fbde556732](https://linux-hardware.org/?probe=fbde556732) | Aug 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [8908b97b57](https://linux-hardware.org/?probe=8908b97b57) | Aug 05, 2024 |
| Valve         | Galileo                     | Notebook    | [e184b99807](https://linux-hardware.org/?probe=e184b99807) | Aug 05, 2024 |
| JGINYUE       | B450I-GAMING Ver:1.1        | Desktop     | [a51ecd44f8](https://linux-hardware.org/?probe=a51ecd44f8) | Aug 05, 2024 |
| Shenzhen M... | F7BAA                       | Desktop     | [f997d4444d](https://linux-hardware.org/?probe=f997d4444d) | Aug 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [185cee5333](https://linux-hardware.org/?probe=185cee5333) | Aug 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [f12b84e716](https://linux-hardware.org/?probe=f12b84e716) | Aug 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [6afe9c392f](https://linux-hardware.org/?probe=6afe9c392f) | Aug 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [856ad22873](https://linux-hardware.org/?probe=856ad22873) | Aug 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [a6aed47a91](https://linux-hardware.org/?probe=a6aed47a91) | Aug 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [d8d1ff3d09](https://linux-hardware.org/?probe=d8d1ff3d09) | Aug 03, 2024 |
| ASRock        | B550M-C                     | Desktop     | [ff06ba744d](https://linux-hardware.org/?probe=ff06ba744d) | Aug 02, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [b84f2e45ff](https://linux-hardware.org/?probe=b84f2e45ff) | Aug 02, 2024 |
| Valve         | Galileo                     | Notebook    | [de27ed2ec2](https://linux-hardware.org/?probe=de27ed2ec2) | Aug 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [dd6f3a47ef](https://linux-hardware.org/?probe=dd6f3a47ef) | Aug 01, 2024 |
| Valve         | Galileo                     | Notebook    | [aeffe451a6](https://linux-hardware.org/?probe=aeffe451a6) | Aug 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [02d553659b](https://linux-hardware.org/?probe=02d553659b) | Jul 31, 2024 |
| Valve         | Galileo                     | Notebook    | [e0ce22958f](https://linux-hardware.org/?probe=e0ce22958f) | Jul 31, 2024 |
| Valve         | Galileo                     | Notebook    | [688d586fb6](https://linux-hardware.org/?probe=688d586fb6) | Jul 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [d816b9a92e](https://linux-hardware.org/?probe=d816b9a92e) | Jul 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [a994738f0f](https://linux-hardware.org/?probe=a994738f0f) | Jul 30, 2024 |
| Valve         | Galileo                     | Notebook    | [f19dfd6066](https://linux-hardware.org/?probe=f19dfd6066) | Jul 29, 2024 |
| Valve         | Galileo                     | Notebook    | [c62dd4aca9](https://linux-hardware.org/?probe=c62dd4aca9) | Jul 29, 2024 |
| Valve         | Galileo                     | Notebook    | [f4a8db2e5f](https://linux-hardware.org/?probe=f4a8db2e5f) | Jul 29, 2024 |
| ASUSTek       | PN53                        | Mini pc     | [6cb0faffca](https://linux-hardware.org/?probe=6cb0faffca) | Jul 29, 2024 |
| Lenovo        | 364A                        | Desktop     | [133e44eaa4](https://linux-hardware.org/?probe=133e44eaa4) | Jul 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [dda27ff4b2](https://linux-hardware.org/?probe=dda27ff4b2) | Jul 29, 2024 |
| Valve         | Galileo                     | Notebook    | [7486fe2e2d](https://linux-hardware.org/?probe=7486fe2e2d) | Jul 28, 2024 |
| Valve         | Galileo                     | Notebook    | [82a9ab9d05](https://linux-hardware.org/?probe=82a9ab9d05) | Jul 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [da6fe0b872](https://linux-hardware.org/?probe=da6fe0b872) | Jul 27, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [780f8aa87f](https://linux-hardware.org/?probe=780f8aa87f) | Jul 27, 2024 |
| Valve         | Galileo                     | Notebook    | [60cad61bb9](https://linux-hardware.org/?probe=60cad61bb9) | Jul 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [0ea5661d08](https://linux-hardware.org/?probe=0ea5661d08) | Jul 27, 2024 |
| Valve         | Galileo                     | Notebook    | [f2e7281501](https://linux-hardware.org/?probe=f2e7281501) | Jul 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [d08c520219](https://linux-hardware.org/?probe=d08c520219) | Jul 26, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [6649de3bc7](https://linux-hardware.org/?probe=6649de3bc7) | Jul 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [d0bfc7d5a0](https://linux-hardware.org/?probe=d0bfc7d5a0) | Jul 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [58e34d4736](https://linux-hardware.org/?probe=58e34d4736) | Jul 25, 2024 |
| Valve         | Galileo                     | Notebook    | [43c9ef5682](https://linux-hardware.org/?probe=43c9ef5682) | Jul 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [79e199cee3](https://linux-hardware.org/?probe=79e199cee3) | Jul 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [29e717369c](https://linux-hardware.org/?probe=29e717369c) | Jul 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [2581b68fdf](https://linux-hardware.org/?probe=2581b68fdf) | Jul 24, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [a3a0bfc94d](https://linux-hardware.org/?probe=a3a0bfc94d) | Jul 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [b2f955f6c2](https://linux-hardware.org/?probe=b2f955f6c2) | Jul 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [aba58db410](https://linux-hardware.org/?probe=aba58db410) | Jul 21, 2024 |
| Valve         | Galileo                     | Notebook    | [4ca73c7dbf](https://linux-hardware.org/?probe=4ca73c7dbf) | Jul 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [23181349eb](https://linux-hardware.org/?probe=23181349eb) | Jul 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [d3da433858](https://linux-hardware.org/?probe=d3da433858) | Jul 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [267ae5ae8a](https://linux-hardware.org/?probe=267ae5ae8a) | Jul 20, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [fc4b11232b](https://linux-hardware.org/?probe=fc4b11232b) | Jul 20, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [361baaba70](https://linux-hardware.org/?probe=361baaba70) | Jul 20, 2024 |
| Valve         | Galileo                     | Notebook    | [84094f6c95](https://linux-hardware.org/?probe=84094f6c95) | Jul 19, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [1b64f2a6c6](https://linux-hardware.org/?probe=1b64f2a6c6) | Jul 19, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [e53dd4acab](https://linux-hardware.org/?probe=e53dd4acab) | Jul 19, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [6f8fcf391e](https://linux-hardware.org/?probe=6f8fcf391e) | Jul 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [a8baa7b80b](https://linux-hardware.org/?probe=a8baa7b80b) | Jul 19, 2024 |
| Valve         | Galileo                     | Notebook    | [e881789efd](https://linux-hardware.org/?probe=e881789efd) | Jul 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [0af4c8e33d](https://linux-hardware.org/?probe=0af4c8e33d) | Jul 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [7cc0040262](https://linux-hardware.org/?probe=7cc0040262) | Jul 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [d40f3907f4](https://linux-hardware.org/?probe=d40f3907f4) | Jul 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [5a49a17e87](https://linux-hardware.org/?probe=5a49a17e87) | Jul 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [dd85ac2d89](https://linux-hardware.org/?probe=dd85ac2d89) | Jul 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [6cb4efdd20](https://linux-hardware.org/?probe=6cb4efdd20) | Jul 15, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [2050081e07](https://linux-hardware.org/?probe=2050081e07) | Jul 15, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [78db81d92d](https://linux-hardware.org/?probe=78db81d92d) | Jul 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [97d9904f80](https://linux-hardware.org/?probe=97d9904f80) | Jul 14, 2024 |
| Valve         | Galileo                     | Notebook    | [3a21bcbb8c](https://linux-hardware.org/?probe=3a21bcbb8c) | Jul 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [b7c421b2b6](https://linux-hardware.org/?probe=b7c421b2b6) | Jul 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [1af6c9569b](https://linux-hardware.org/?probe=1af6c9569b) | Jul 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [20aeaa8455](https://linux-hardware.org/?probe=20aeaa8455) | Jul 13, 2024 |
| Shenzhen M... | F7BAA                       | Desktop     | [47f43bfb0b](https://linux-hardware.org/?probe=47f43bfb0b) | Jul 12, 2024 |
| Valve         | Galileo                     | Notebook    | [b515ad6719](https://linux-hardware.org/?probe=b515ad6719) | Jul 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [6659109c2c](https://linux-hardware.org/?probe=6659109c2c) | Jul 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [be4d4121bd](https://linux-hardware.org/?probe=be4d4121bd) | Jul 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [81d661f85e](https://linux-hardware.org/?probe=81d661f85e) | Jul 10, 2024 |
| ASRock        | B360M Xtreme                | Desktop     | [77c855ffba](https://linux-hardware.org/?probe=77c855ffba) | Jul 10, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [18ea2c08bb](https://linux-hardware.org/?probe=18ea2c08bb) | Jul 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [eed14819ad](https://linux-hardware.org/?probe=eed14819ad) | Jul 08, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2938398b92](https://linux-hardware.org/?probe=2938398b92) | Jul 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [e840ba5076](https://linux-hardware.org/?probe=e840ba5076) | Jul 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [4d58b03e0d](https://linux-hardware.org/?probe=4d58b03e0d) | Jul 07, 2024 |
| Valve         | Galileo                     | Notebook    | [243f001450](https://linux-hardware.org/?probe=243f001450) | Jul 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [71881f2726](https://linux-hardware.org/?probe=71881f2726) | Jul 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [13b3507e44](https://linux-hardware.org/?probe=13b3507e44) | Jul 06, 2024 |
| Valve         | Galileo                     | Notebook    | [faad9ed361](https://linux-hardware.org/?probe=faad9ed361) | Jul 06, 2024 |
| Valve         | Galileo                     | Notebook    | [187ecb8c3e](https://linux-hardware.org/?probe=187ecb8c3e) | Jul 06, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [dcb993f549](https://linux-hardware.org/?probe=dcb993f549) | Jul 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [4cd27dceef](https://linux-hardware.org/?probe=4cd27dceef) | Jul 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [eb90d739f5](https://linux-hardware.org/?probe=eb90d739f5) | Jul 05, 2024 |
| Valve         | Galileo                     | Notebook    | [a726f50e50](https://linux-hardware.org/?probe=a726f50e50) | Jul 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [7fb4affa2d](https://linux-hardware.org/?probe=7fb4affa2d) | Jul 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [041da22739](https://linux-hardware.org/?probe=041da22739) | Jul 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [d7c3a3e7a5](https://linux-hardware.org/?probe=d7c3a3e7a5) | Jul 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [3767477a96](https://linux-hardware.org/?probe=3767477a96) | Jul 04, 2024 |
| Valve         | Galileo                     | Notebook    | [f856d038b7](https://linux-hardware.org/?probe=f856d038b7) | Jul 03, 2024 |
| Valve         | Galileo                     | Notebook    | [f5bd2681fd](https://linux-hardware.org/?probe=f5bd2681fd) | Jul 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [1ccb426afe](https://linux-hardware.org/?probe=1ccb426afe) | Jul 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [53d7faf568](https://linux-hardware.org/?probe=53d7faf568) | Jul 02, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [70a230bac1](https://linux-hardware.org/?probe=70a230bac1) | Jul 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [30ac050b8c](https://linux-hardware.org/?probe=30ac050b8c) | Jul 02, 2024 |
| Valve         | Galileo                     | Notebook    | [16323ec624](https://linux-hardware.org/?probe=16323ec624) | Jul 02, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8b7d65a86c](https://linux-hardware.org/?probe=8b7d65a86c) | Jul 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [e5b0fecc14](https://linux-hardware.org/?probe=e5b0fecc14) | Jul 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [622fb82f08](https://linux-hardware.org/?probe=622fb82f08) | Jul 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [b664521485](https://linux-hardware.org/?probe=b664521485) | Jul 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [cc1f6b21fd](https://linux-hardware.org/?probe=cc1f6b21fd) | Jul 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [7f92ab53ad](https://linux-hardware.org/?probe=7f92ab53ad) | Jul 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [162c4ed949](https://linux-hardware.org/?probe=162c4ed949) | Jun 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [d3bd81f97d](https://linux-hardware.org/?probe=d3bd81f97d) | Jun 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [2997938de8](https://linux-hardware.org/?probe=2997938de8) | Jun 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [f8b7ac5efe](https://linux-hardware.org/?probe=f8b7ac5efe) | Jun 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [6c57d46723](https://linux-hardware.org/?probe=6c57d46723) | Jun 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [03f1dde349](https://linux-hardware.org/?probe=03f1dde349) | Jun 27, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5f9980bb04](https://linux-hardware.org/?probe=5f9980bb04) | Jun 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [6c9bd171e9](https://linux-hardware.org/?probe=6c9bd171e9) | Jun 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [cca5086065](https://linux-hardware.org/?probe=cca5086065) | Jun 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [49ade9d97b](https://linux-hardware.org/?probe=49ade9d97b) | Jun 24, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1758fea944](https://linux-hardware.org/?probe=1758fea944) | Jun 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [fed4c964d0](https://linux-hardware.org/?probe=fed4c964d0) | Jun 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [6f6d21c0a6](https://linux-hardware.org/?probe=6f6d21c0a6) | Jun 23, 2024 |
| Valve         | Galileo                     | Notebook    | [d7697545d4](https://linux-hardware.org/?probe=d7697545d4) | Jun 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [39adbfce1d](https://linux-hardware.org/?probe=39adbfce1d) | Jun 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [ae5ea1127e](https://linux-hardware.org/?probe=ae5ea1127e) | Jun 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [cfb741b75a](https://linux-hardware.org/?probe=cfb741b75a) | Jun 22, 2024 |
| Valve         | Galileo                     | Notebook    | [e60f736bad](https://linux-hardware.org/?probe=e60f736bad) | Jun 21, 2024 |
| Intel         | X79v2.72 KD V2.0            | Desktop     | [3e1bbdccc8](https://linux-hardware.org/?probe=3e1bbdccc8) | Jun 20, 2024 |
| Valve         | Galileo                     | Notebook    | [ddfbd408a0](https://linux-hardware.org/?probe=ddfbd408a0) | Jun 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [f547ae57cb](https://linux-hardware.org/?probe=f547ae57cb) | Jun 20, 2024 |
| Valve         | Galileo                     | Notebook    | [af0962fcf0](https://linux-hardware.org/?probe=af0962fcf0) | Jun 20, 2024 |
| Valve         | Galileo                     | Notebook    | [b0adc5fb82](https://linux-hardware.org/?probe=b0adc5fb82) | Jun 19, 2024 |
| Valve         | Galileo                     | Notebook    | [8c250eb26f](https://linux-hardware.org/?probe=8c250eb26f) | Jun 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [dd17653792](https://linux-hardware.org/?probe=dd17653792) | Jun 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [cc34802c81](https://linux-hardware.org/?probe=cc34802c81) | Jun 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [49d9ce63bf](https://linux-hardware.org/?probe=49d9ce63bf) | Jun 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [87dfe9ba14](https://linux-hardware.org/?probe=87dfe9ba14) | Jun 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [0fa52f5fa6](https://linux-hardware.org/?probe=0fa52f5fa6) | Jun 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [3efb253506](https://linux-hardware.org/?probe=3efb253506) | Jun 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [42e411679d](https://linux-hardware.org/?probe=42e411679d) | Jun 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [1c05546f6c](https://linux-hardware.org/?probe=1c05546f6c) | Jun 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [a2c47b5a90](https://linux-hardware.org/?probe=a2c47b5a90) | Jun 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [f2f1d90b24](https://linux-hardware.org/?probe=f2f1d90b24) | Jun 16, 2024 |
| Valve         | Galileo                     | Notebook    | [fe78f4bfd1](https://linux-hardware.org/?probe=fe78f4bfd1) | Jun 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [907d762be9](https://linux-hardware.org/?probe=907d762be9) | Jun 16, 2024 |
| Valve         | Galileo                     | Notebook    | [0dcc255711](https://linux-hardware.org/?probe=0dcc255711) | Jun 14, 2024 |
| Valve         | Galileo                     | Notebook    | [adf863c3a8](https://linux-hardware.org/?probe=adf863c3a8) | Jun 14, 2024 |
| Dell          | Inspiron 3180               | Notebook    | [0cc66cd822](https://linux-hardware.org/?probe=0cc66cd822) | Jun 13, 2024 |
| Dell          | Inspiron 3180               | Notebook    | [d51459ccc3](https://linux-hardware.org/?probe=d51459ccc3) | Jun 13, 2024 |
| Valve         | Galileo                     | Notebook    | [620d5dea49](https://linux-hardware.org/?probe=620d5dea49) | Jun 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [0cb758c7b4](https://linux-hardware.org/?probe=0cb758c7b4) | Jun 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [b98f157084](https://linux-hardware.org/?probe=b98f157084) | Jun 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [abd2069262](https://linux-hardware.org/?probe=abd2069262) | Jun 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [924b735a6d](https://linux-hardware.org/?probe=924b735a6d) | Jun 10, 2024 |
| Valve         | Galileo                     | Notebook    | [3ee31a0659](https://linux-hardware.org/?probe=3ee31a0659) | Jun 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [ec19627536](https://linux-hardware.org/?probe=ec19627536) | Jun 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [7b33fffe4b](https://linux-hardware.org/?probe=7b33fffe4b) | Jun 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [3e9a82f12b](https://linux-hardware.org/?probe=3e9a82f12b) | Jun 08, 2024 |
| MSI           | Katana 15 B13VFK            | Notebook    | [b4ee376d73](https://linux-hardware.org/?probe=b4ee376d73) | Jun 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [93c31a60b8](https://linux-hardware.org/?probe=93c31a60b8) | Jun 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [9ded2c684c](https://linux-hardware.org/?probe=9ded2c684c) | Jun 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [f5acb21b8a](https://linux-hardware.org/?probe=f5acb21b8a) | Jun 07, 2024 |
| Valve         | Galileo                     | Notebook    | [fa868c6988](https://linux-hardware.org/?probe=fa868c6988) | Jun 06, 2024 |
| Valve         | Galileo                     | Notebook    | [c1cd10e2c9](https://linux-hardware.org/?probe=c1cd10e2c9) | Jun 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [f05a7b1ffd](https://linux-hardware.org/?probe=f05a7b1ffd) | Jun 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [151aa4e844](https://linux-hardware.org/?probe=151aa4e844) | Jun 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [c80349bff9](https://linux-hardware.org/?probe=c80349bff9) | Jun 03, 2024 |
| Valve         | Galileo                     | Notebook    | [6637bae1b1](https://linux-hardware.org/?probe=6637bae1b1) | Jun 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [025c412f84](https://linux-hardware.org/?probe=025c412f84) | Jun 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [34cb62e145](https://linux-hardware.org/?probe=34cb62e145) | Jun 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [c611821678](https://linux-hardware.org/?probe=c611821678) | Jun 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [47287ea332](https://linux-hardware.org/?probe=47287ea332) | Jun 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [27f5ec8379](https://linux-hardware.org/?probe=27f5ec8379) | Jun 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [0158910bc1](https://linux-hardware.org/?probe=0158910bc1) | May 31, 2024 |
| Valve         | Jupiter                     | Notebook    | [a5fb0c22da](https://linux-hardware.org/?probe=a5fb0c22da) | May 31, 2024 |
| Valve         | Galileo                     | Notebook    | [86653d2909](https://linux-hardware.org/?probe=86653d2909) | May 30, 2024 |
| Valve         | Galileo                     | Notebook    | [b964e07797](https://linux-hardware.org/?probe=b964e07797) | May 30, 2024 |
| Valve         | Galileo                     | Notebook    | [b569820c9e](https://linux-hardware.org/?probe=b569820c9e) | May 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [7358b6d0aa](https://linux-hardware.org/?probe=7358b6d0aa) | May 30, 2024 |
| Valve         | Galileo                     | Notebook    | [34c9edbb55](https://linux-hardware.org/?probe=34c9edbb55) | May 30, 2024 |
| Valve         | Galileo                     | Notebook    | [4502f2febd](https://linux-hardware.org/?probe=4502f2febd) | May 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [44a1aa1433](https://linux-hardware.org/?probe=44a1aa1433) | May 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [1ddb224c47](https://linux-hardware.org/?probe=1ddb224c47) | May 27, 2024 |
| Valve         | Galileo                     | Notebook    | [66613e5eb2](https://linux-hardware.org/?probe=66613e5eb2) | May 27, 2024 |
| Valve         | Galileo                     | Notebook    | [917f59b1a1](https://linux-hardware.org/?probe=917f59b1a1) | May 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [d6527daec7](https://linux-hardware.org/?probe=d6527daec7) | May 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [ba4e5166ce](https://linux-hardware.org/?probe=ba4e5166ce) | May 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [f3cac40a5a](https://linux-hardware.org/?probe=f3cac40a5a) | May 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [e03f67a310](https://linux-hardware.org/?probe=e03f67a310) | May 22, 2024 |
| ASRock        | B660M PG Riptide            | Desktop     | [0eb75d61c6](https://linux-hardware.org/?probe=0eb75d61c6) | May 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [4080a2a217](https://linux-hardware.org/?probe=4080a2a217) | May 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [19a4c0ceba](https://linux-hardware.org/?probe=19a4c0ceba) | May 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [cff66de9ee](https://linux-hardware.org/?probe=cff66de9ee) | May 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [68e9550bca](https://linux-hardware.org/?probe=68e9550bca) | May 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [db74964be4](https://linux-hardware.org/?probe=db74964be4) | May 21, 2024 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [c12ef32789](https://linux-hardware.org/?probe=c12ef32789) | May 20, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [810351e380](https://linux-hardware.org/?probe=810351e380) | May 19, 2024 |
| Valve         | Galileo                     | Notebook    | [1c500922b5](https://linux-hardware.org/?probe=1c500922b5) | May 19, 2024 |
| Valve         | Galileo                     | Notebook    | [9549cb7d85](https://linux-hardware.org/?probe=9549cb7d85) | May 19, 2024 |
| Valve         | Galileo                     | Notebook    | [a85c23cf18](https://linux-hardware.org/?probe=a85c23cf18) | May 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [599aec1e4e](https://linux-hardware.org/?probe=599aec1e4e) | May 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [5e15e8c17b](https://linux-hardware.org/?probe=5e15e8c17b) | May 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [d84cfa7d7f](https://linux-hardware.org/?probe=d84cfa7d7f) | May 18, 2024 |
| Valve         | Galileo                     | Notebook    | [ed4a40c18a](https://linux-hardware.org/?probe=ed4a40c18a) | May 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [5de837e78c](https://linux-hardware.org/?probe=5de837e78c) | May 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [29fae4b082](https://linux-hardware.org/?probe=29fae4b082) | May 18, 2024 |
| Valve         | Galileo                     | Notebook    | [058f6d665d](https://linux-hardware.org/?probe=058f6d665d) | May 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [e3272728de](https://linux-hardware.org/?probe=e3272728de) | May 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [cab7d8548c](https://linux-hardware.org/?probe=cab7d8548c) | May 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [90c4df117d](https://linux-hardware.org/?probe=90c4df117d) | May 18, 2024 |
| Valve         | Galileo                     | Notebook    | [9b5fd55552](https://linux-hardware.org/?probe=9b5fd55552) | May 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [617b6ab231](https://linux-hardware.org/?probe=617b6ab231) | May 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [edfda63f37](https://linux-hardware.org/?probe=edfda63f37) | May 17, 2024 |
| Valve         | Galileo                     | Notebook    | [7b44b5dc29](https://linux-hardware.org/?probe=7b44b5dc29) | May 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [ea34e4adf2](https://linux-hardware.org/?probe=ea34e4adf2) | May 15, 2024 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | Desktop     | [e10a369f92](https://linux-hardware.org/?probe=e10a369f92) | May 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [ba91321fa0](https://linux-hardware.org/?probe=ba91321fa0) | May 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [08f916fd15](https://linux-hardware.org/?probe=08f916fd15) | May 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [073c85e73d](https://linux-hardware.org/?probe=073c85e73d) | May 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [be3c00adec](https://linux-hardware.org/?probe=be3c00adec) | May 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [e3c466308b](https://linux-hardware.org/?probe=e3c466308b) | May 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [23799f6a79](https://linux-hardware.org/?probe=23799f6a79) | May 13, 2024 |
| Valve         | Galileo                     | Notebook    | [3b501f9708](https://linux-hardware.org/?probe=3b501f9708) | May 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [dde2589857](https://linux-hardware.org/?probe=dde2589857) | May 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [9523a351f6](https://linux-hardware.org/?probe=9523a351f6) | May 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [ac6ebe5faa](https://linux-hardware.org/?probe=ac6ebe5faa) | May 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [f10720d561](https://linux-hardware.org/?probe=f10720d561) | May 11, 2024 |
| Valve         | Galileo                     | Notebook    | [974b158130](https://linux-hardware.org/?probe=974b158130) | May 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [18a1991ac9](https://linux-hardware.org/?probe=18a1991ac9) | May 10, 2024 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [40478abcae](https://linux-hardware.org/?probe=40478abcae) | May 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [7fd798adce](https://linux-hardware.org/?probe=7fd798adce) | May 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [358d9efd2f](https://linux-hardware.org/?probe=358d9efd2f) | May 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [a7a182f08f](https://linux-hardware.org/?probe=a7a182f08f) | May 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [99879342f6](https://linux-hardware.org/?probe=99879342f6) | May 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [18c9c24ecb](https://linux-hardware.org/?probe=18c9c24ecb) | May 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [fadecff7cd](https://linux-hardware.org/?probe=fadecff7cd) | May 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [c0eded1dbf](https://linux-hardware.org/?probe=c0eded1dbf) | May 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [cdb467c650](https://linux-hardware.org/?probe=cdb467c650) | May 08, 2024 |
| Valve         | Galileo                     | Notebook    | [9b9caa6850](https://linux-hardware.org/?probe=9b9caa6850) | May 07, 2024 |
| Valve         | Galileo                     | Notebook    | [af20242820](https://linux-hardware.org/?probe=af20242820) | May 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [9a90343d3e](https://linux-hardware.org/?probe=9a90343d3e) | May 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [829ef0c2ba](https://linux-hardware.org/?probe=829ef0c2ba) | May 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [728da6c7b1](https://linux-hardware.org/?probe=728da6c7b1) | May 05, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [dc7364667b](https://linux-hardware.org/?probe=dc7364667b) | May 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [5f8e391778](https://linux-hardware.org/?probe=5f8e391778) | May 04, 2024 |
| ASRock        | B760M PG Lightning/D4       | Desktop     | [50c91b7d78](https://linux-hardware.org/?probe=50c91b7d78) | May 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [9a03d01cbc](https://linux-hardware.org/?probe=9a03d01cbc) | May 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [912546851a](https://linux-hardware.org/?probe=912546851a) | May 01, 2024 |
| Valve         | Galileo                     | Notebook    | [fc102d1c7f](https://linux-hardware.org/?probe=fc102d1c7f) | May 01, 2024 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [68cb77a084](https://linux-hardware.org/?probe=68cb77a084) | May 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [5266501940](https://linux-hardware.org/?probe=5266501940) | Apr 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [20eca8966f](https://linux-hardware.org/?probe=20eca8966f) | Apr 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [4360127fcb](https://linux-hardware.org/?probe=4360127fcb) | Apr 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [42fe2e9ed4](https://linux-hardware.org/?probe=42fe2e9ed4) | Apr 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [db12022c45](https://linux-hardware.org/?probe=db12022c45) | Apr 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [2b383bd91e](https://linux-hardware.org/?probe=2b383bd91e) | Apr 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [7a58749308](https://linux-hardware.org/?probe=7a58749308) | Apr 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [bca2851ff6](https://linux-hardware.org/?probe=bca2851ff6) | Apr 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [93f380bf3e](https://linux-hardware.org/?probe=93f380bf3e) | Apr 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [2c0ec8539f](https://linux-hardware.org/?probe=2c0ec8539f) | Apr 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [49fd8e0c8f](https://linux-hardware.org/?probe=49fd8e0c8f) | Apr 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [3b3674f61e](https://linux-hardware.org/?probe=3b3674f61e) | Apr 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [5430bf31d1](https://linux-hardware.org/?probe=5430bf31d1) | Apr 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [81ec451d66](https://linux-hardware.org/?probe=81ec451d66) | Apr 26, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [4ffacbaeac](https://linux-hardware.org/?probe=4ffacbaeac) | Apr 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [4cad19c61a](https://linux-hardware.org/?probe=4cad19c61a) | Apr 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [61762f3b53](https://linux-hardware.org/?probe=61762f3b53) | Apr 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [8b69a30a9d](https://linux-hardware.org/?probe=8b69a30a9d) | Apr 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [7c8a53ecb1](https://linux-hardware.org/?probe=7c8a53ecb1) | Apr 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [53f25f4dba](https://linux-hardware.org/?probe=53f25f4dba) | Apr 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [665861dbf9](https://linux-hardware.org/?probe=665861dbf9) | Apr 22, 2024 |
| Valve         | Galileo                     | Notebook    | [3baa035f72](https://linux-hardware.org/?probe=3baa035f72) | Apr 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [bc9b5cbcc5](https://linux-hardware.org/?probe=bc9b5cbcc5) | Apr 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [3d82c7c0ee](https://linux-hardware.org/?probe=3d82c7c0ee) | Apr 20, 2024 |
| ONE-NETBOO... | ONEXPLAYER Mini Pro         | Tablet      | [2b95c1e3b2](https://linux-hardware.org/?probe=2b95c1e3b2) | Apr 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [8cbd37a2d2](https://linux-hardware.org/?probe=8cbd37a2d2) | Apr 19, 2024 |
| Valve         | Galileo                     | Notebook    | [c3c28433cd](https://linux-hardware.org/?probe=c3c28433cd) | Apr 19, 2024 |
| ONE-NETBOO... | ONEXPLAYER Mini Pro         | Tablet      | [4c54b3eac4](https://linux-hardware.org/?probe=4c54b3eac4) | Apr 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [38ab9d1cca](https://linux-hardware.org/?probe=38ab9d1cca) | Apr 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [46fe84935f](https://linux-hardware.org/?probe=46fe84935f) | Apr 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [85092eabaa](https://linux-hardware.org/?probe=85092eabaa) | Apr 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [541aacb1a1](https://linux-hardware.org/?probe=541aacb1a1) | Apr 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [37f71f57a0](https://linux-hardware.org/?probe=37f71f57a0) | Apr 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [04d302c0e5](https://linux-hardware.org/?probe=04d302c0e5) | Apr 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [d5c75e66f1](https://linux-hardware.org/?probe=d5c75e66f1) | Apr 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [7de67bf8c5](https://linux-hardware.org/?probe=7de67bf8c5) | Apr 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [211106f4c1](https://linux-hardware.org/?probe=211106f4c1) | Apr 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [0043fe12b0](https://linux-hardware.org/?probe=0043fe12b0) | Apr 13, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [97e9e0c7a1](https://linux-hardware.org/?probe=97e9e0c7a1) | Apr 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [8b4172f55b](https://linux-hardware.org/?probe=8b4172f55b) | Apr 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [64cab9101d](https://linux-hardware.org/?probe=64cab9101d) | Apr 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [c5c95abb79](https://linux-hardware.org/?probe=c5c95abb79) | Apr 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [5f44467298](https://linux-hardware.org/?probe=5f44467298) | Apr 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [a75cf3dc0f](https://linux-hardware.org/?probe=a75cf3dc0f) | Apr 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [6f2b093298](https://linux-hardware.org/?probe=6f2b093298) | Apr 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [a80d8086f4](https://linux-hardware.org/?probe=a80d8086f4) | Apr 09, 2024 |
| Valve         | Galileo                     | Notebook    | [942bd1a16a](https://linux-hardware.org/?probe=942bd1a16a) | Apr 08, 2024 |
| Valve         | Galileo                     | Notebook    | [9ce0365088](https://linux-hardware.org/?probe=9ce0365088) | Apr 08, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [d0241d517a](https://linux-hardware.org/?probe=d0241d517a) | Apr 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [36089b579d](https://linux-hardware.org/?probe=36089b579d) | Apr 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [8cd7c7653a](https://linux-hardware.org/?probe=8cd7c7653a) | Apr 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [6fb589032f](https://linux-hardware.org/?probe=6fb589032f) | Apr 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [ca414b0905](https://linux-hardware.org/?probe=ca414b0905) | Apr 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [80b0985ecd](https://linux-hardware.org/?probe=80b0985ecd) | Apr 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [1cd9cc4807](https://linux-hardware.org/?probe=1cd9cc4807) | Apr 07, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [d0447bf92e](https://linux-hardware.org/?probe=d0447bf92e) | Apr 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [70c2145a5e](https://linux-hardware.org/?probe=70c2145a5e) | Apr 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [2e89c99bcd](https://linux-hardware.org/?probe=2e89c99bcd) | Apr 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [bf17940c69](https://linux-hardware.org/?probe=bf17940c69) | Apr 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [04c5de9351](https://linux-hardware.org/?probe=04c5de9351) | Apr 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [a981f41f5c](https://linux-hardware.org/?probe=a981f41f5c) | Apr 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [806dd327bf](https://linux-hardware.org/?probe=806dd327bf) | Apr 05, 2024 |
| ASRock        | B450M Pro4-F                | Desktop     | [c70e4f20eb](https://linux-hardware.org/?probe=c70e4f20eb) | Apr 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [e7ac70b5b9](https://linux-hardware.org/?probe=e7ac70b5b9) | Apr 04, 2024 |
| Valve         | Galileo                     | Notebook    | [968d4e6589](https://linux-hardware.org/?probe=968d4e6589) | Apr 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [450a01c984](https://linux-hardware.org/?probe=450a01c984) | Apr 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [a9bb9ace67](https://linux-hardware.org/?probe=a9bb9ace67) | Apr 03, 2024 |
| Valve         | Galileo                     | Notebook    | [0e73d5c7db](https://linux-hardware.org/?probe=0e73d5c7db) | Apr 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [3f58323ccb](https://linux-hardware.org/?probe=3f58323ccb) | Apr 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [780ff142f3](https://linux-hardware.org/?probe=780ff142f3) | Apr 01, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [3fe2ef5687](https://linux-hardware.org/?probe=3fe2ef5687) | Apr 01, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [24108983ab](https://linux-hardware.org/?probe=24108983ab) | Apr 01, 2024 |
| ONE-NETBOO... | ONEXPLAYER Mini Pro         | Tablet      | [4dd7031fb5](https://linux-hardware.org/?probe=4dd7031fb5) | Mar 31, 2024 |
| Valve         | Jupiter                     | Notebook    | [83291b94be](https://linux-hardware.org/?probe=83291b94be) | Mar 31, 2024 |
| Valve         | Jupiter                     | Notebook    | [16cef49100](https://linux-hardware.org/?probe=16cef49100) | Mar 31, 2024 |
| Valve         | Galileo                     | Notebook    | [f1d07303d3](https://linux-hardware.org/?probe=f1d07303d3) | Mar 30, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [1fb1798295](https://linux-hardware.org/?probe=1fb1798295) | Mar 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [65e56cbf7d](https://linux-hardware.org/?probe=65e56cbf7d) | Mar 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [1a14e1128b](https://linux-hardware.org/?probe=1a14e1128b) | Mar 29, 2024 |
| Valve         | Galileo                     | Notebook    | [cf3139b931](https://linux-hardware.org/?probe=cf3139b931) | Mar 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [b2242c7939](https://linux-hardware.org/?probe=b2242c7939) | Mar 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [735b182e71](https://linux-hardware.org/?probe=735b182e71) | Mar 27, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1cda914d9f](https://linux-hardware.org/?probe=1cda914d9f) | Mar 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [767300c112](https://linux-hardware.org/?probe=767300c112) | Mar 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [6ded41cc7e](https://linux-hardware.org/?probe=6ded41cc7e) | Mar 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [99fec85b50](https://linux-hardware.org/?probe=99fec85b50) | Mar 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [28b02c08d8](https://linux-hardware.org/?probe=28b02c08d8) | Mar 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [8c039323e6](https://linux-hardware.org/?probe=8c039323e6) | Mar 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [4342049244](https://linux-hardware.org/?probe=4342049244) | Mar 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [b61c5a739b](https://linux-hardware.org/?probe=b61c5a739b) | Mar 24, 2024 |
| Valve         | Galileo                     | Notebook    | [edb753ac8d](https://linux-hardware.org/?probe=edb753ac8d) | Mar 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [d2155ef727](https://linux-hardware.org/?probe=d2155ef727) | Mar 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [a4d5199429](https://linux-hardware.org/?probe=a4d5199429) | Mar 23, 2024 |
| Valve         | Galileo                     | Notebook    | [5e7e2c39df](https://linux-hardware.org/?probe=5e7e2c39df) | Mar 22, 2024 |
| Valve         | Galileo                     | Notebook    | [14e646cf21](https://linux-hardware.org/?probe=14e646cf21) | Mar 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [4de44d6cdd](https://linux-hardware.org/?probe=4de44d6cdd) | Mar 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [3984f68c68](https://linux-hardware.org/?probe=3984f68c68) | Mar 22, 2024 |
| Valve         | Galileo                     | Notebook    | [cd0fb4513f](https://linux-hardware.org/?probe=cd0fb4513f) | Mar 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [799336fb6f](https://linux-hardware.org/?probe=799336fb6f) | Mar 21, 2024 |
| Valve         | Galileo                     | Notebook    | [21dd2b032b](https://linux-hardware.org/?probe=21dd2b032b) | Mar 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [00d8e6290f](https://linux-hardware.org/?probe=00d8e6290f) | Mar 20, 2024 |
| Valve         | Galileo                     | Notebook    | [f27bde39ca](https://linux-hardware.org/?probe=f27bde39ca) | Mar 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [fdd201eb62](https://linux-hardware.org/?probe=fdd201eb62) | Mar 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [5c3d9869b4](https://linux-hardware.org/?probe=5c3d9869b4) | Mar 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [ff5812e646](https://linux-hardware.org/?probe=ff5812e646) | Mar 20, 2024 |
| Valve         | Galileo                     | Notebook    | [0bbc97ddea](https://linux-hardware.org/?probe=0bbc97ddea) | Mar 19, 2024 |
| Valve         | Galileo                     | Notebook    | [085b9b9244](https://linux-hardware.org/?probe=085b9b9244) | Mar 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [869100ba40](https://linux-hardware.org/?probe=869100ba40) | Mar 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [0f1ba4ef31](https://linux-hardware.org/?probe=0f1ba4ef31) | Mar 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [4d0b384f4d](https://linux-hardware.org/?probe=4d0b384f4d) | Mar 17, 2024 |
| Gigabyte      | A620M GAMING X AX           | Desktop     | [95dabe0b93](https://linux-hardware.org/?probe=95dabe0b93) | Mar 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [ebb293f4f2](https://linux-hardware.org/?probe=ebb293f4f2) | Mar 16, 2024 |
| Valve         | Galileo                     | Notebook    | [1b0c67a809](https://linux-hardware.org/?probe=1b0c67a809) | Mar 16, 2024 |
| Gigabyte      | A620M GAMING X AX           | Desktop     | [ac8a1cf30d](https://linux-hardware.org/?probe=ac8a1cf30d) | Mar 16, 2024 |
| Valve         | Galileo                     | Notebook    | [94545cd73f](https://linux-hardware.org/?probe=94545cd73f) | Mar 16, 2024 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [853a2babec](https://linux-hardware.org/?probe=853a2babec) | Mar 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [5592371b6d](https://linux-hardware.org/?probe=5592371b6d) | Mar 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [ed1ff78792](https://linux-hardware.org/?probe=ed1ff78792) | Mar 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [930838ef76](https://linux-hardware.org/?probe=930838ef76) | Mar 14, 2024 |
| Valve         | Galileo                     | Notebook    | [ce3a2505b6](https://linux-hardware.org/?probe=ce3a2505b6) | Mar 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [c3514740e2](https://linux-hardware.org/?probe=c3514740e2) | Mar 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [14ec218ad2](https://linux-hardware.org/?probe=14ec218ad2) | Mar 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [850f86c442](https://linux-hardware.org/?probe=850f86c442) | Mar 13, 2024 |
| Valve         | Galileo                     | Notebook    | [a55314d630](https://linux-hardware.org/?probe=a55314d630) | Mar 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [14ed8497d8](https://linux-hardware.org/?probe=14ed8497d8) | Mar 12, 2024 |
| Valve         | Galileo                     | Notebook    | [fd1ccf71a2](https://linux-hardware.org/?probe=fd1ccf71a2) | Mar 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [19c2d88d48](https://linux-hardware.org/?probe=19c2d88d48) | Mar 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [ee85c6e7e9](https://linux-hardware.org/?probe=ee85c6e7e9) | Mar 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [0a31a36586](https://linux-hardware.org/?probe=0a31a36586) | Mar 10, 2024 |
| Valve         | Galileo                     | Notebook    | [d816b83ec2](https://linux-hardware.org/?probe=d816b83ec2) | Mar 10, 2024 |
| Gigabyte      | B650 GAMING X AX            | Notebook    | [3ee6829e26](https://linux-hardware.org/?probe=3ee6829e26) | Mar 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [af7786fb34](https://linux-hardware.org/?probe=af7786fb34) | Mar 10, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [541d122eed](https://linux-hardware.org/?probe=541d122eed) | Mar 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [d38b45b5d5](https://linux-hardware.org/?probe=d38b45b5d5) | Mar 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [f8cd449a7b](https://linux-hardware.org/?probe=f8cd449a7b) | Mar 09, 2024 |
| Valve         | Galileo                     | Notebook    | [1b9852cbf9](https://linux-hardware.org/?probe=1b9852cbf9) | Mar 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [b69d18360e](https://linux-hardware.org/?probe=b69d18360e) | Mar 08, 2024 |
| Valve         | Galileo                     | Notebook    | [b2d15e9047](https://linux-hardware.org/?probe=b2d15e9047) | Mar 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [035ae9a246](https://linux-hardware.org/?probe=035ae9a246) | Mar 08, 2024 |
| Valve         | Galileo                     | Notebook    | [7ae1784e3b](https://linux-hardware.org/?probe=7ae1784e3b) | Mar 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [677470b88d](https://linux-hardware.org/?probe=677470b88d) | Mar 06, 2024 |
| QIYIDA        | ED4 V1.1                    | Desktop     | [cbfcb37d83](https://linux-hardware.org/?probe=cbfcb37d83) | Mar 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [1af9e94fb7](https://linux-hardware.org/?probe=1af9e94fb7) | Mar 05, 2024 |
| Valve         | Galileo                     | Notebook    | [88afcecdbe](https://linux-hardware.org/?probe=88afcecdbe) | Mar 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [f1068af6ca](https://linux-hardware.org/?probe=f1068af6ca) | Mar 03, 2024 |
| ASRock        | B550M Steel Legend          | Desktop     | [ff01bc4e69](https://linux-hardware.org/?probe=ff01bc4e69) | Mar 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [3937ff45d4](https://linux-hardware.org/?probe=3937ff45d4) | Mar 03, 2024 |
| ASUSTek       | Z170-A                      | Desktop     | [5c7cfb2969](https://linux-hardware.org/?probe=5c7cfb2969) | Mar 02, 2024 |
| Valve         | Galileo                     | Notebook    | [fd78eb29e4](https://linux-hardware.org/?probe=fd78eb29e4) | Mar 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [eecf1f7620](https://linux-hardware.org/?probe=eecf1f7620) | Mar 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [8a19c9b077](https://linux-hardware.org/?probe=8a19c9b077) | Mar 02, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [721c874400](https://linux-hardware.org/?probe=721c874400) | Mar 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [b455b30583](https://linux-hardware.org/?probe=b455b30583) | Mar 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [8b06ba52f8](https://linux-hardware.org/?probe=8b06ba52f8) | Mar 02, 2024 |
| Gigabyte      | H170M-DS3H-CF               | Desktop     | [e9d405fea6](https://linux-hardware.org/?probe=e9d405fea6) | Mar 02, 2024 |
| Gigabyte      | H170M-DS3H-CF               | Desktop     | [c95130db9f](https://linux-hardware.org/?probe=c95130db9f) | Mar 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [b2228e6857](https://linux-hardware.org/?probe=b2228e6857) | Mar 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [febb7c9dec](https://linux-hardware.org/?probe=febb7c9dec) | Mar 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [610fa788bb](https://linux-hardware.org/?probe=610fa788bb) | Mar 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [a3062daa4e](https://linux-hardware.org/?probe=a3062daa4e) | Mar 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [25aac8bc03](https://linux-hardware.org/?probe=25aac8bc03) | Mar 01, 2024 |
| Valve         | Galileo                     | Notebook    | [63cd4fe821](https://linux-hardware.org/?probe=63cd4fe821) | Feb 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [30c94fd159](https://linux-hardware.org/?probe=30c94fd159) | Feb 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [2f381a7a43](https://linux-hardware.org/?probe=2f381a7a43) | Feb 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [ecfc325c0f](https://linux-hardware.org/?probe=ecfc325c0f) | Feb 29, 2024 |
| Valve         | Galileo                     | Notebook    | [341298d11f](https://linux-hardware.org/?probe=341298d11f) | Feb 28, 2024 |
| Valve         | Galileo                     | Notebook    | [d8f5007f65](https://linux-hardware.org/?probe=d8f5007f65) | Feb 27, 2024 |
| Valve         | Galileo                     | Notebook    | [10c68c0f8b](https://linux-hardware.org/?probe=10c68c0f8b) | Feb 27, 2024 |
| Valve         | Galileo                     | Notebook    | [1eecc5bac8](https://linux-hardware.org/?probe=1eecc5bac8) | Feb 27, 2024 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [14d015f400](https://linux-hardware.org/?probe=14d015f400) | Feb 26, 2024 |
| Valve         | Galileo                     | Notebook    | [de70e171dc](https://linux-hardware.org/?probe=de70e171dc) | Feb 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [a559534ad7](https://linux-hardware.org/?probe=a559534ad7) | Feb 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [ac52b6fbea](https://linux-hardware.org/?probe=ac52b6fbea) | Feb 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [4da56c1b32](https://linux-hardware.org/?probe=4da56c1b32) | Feb 24, 2024 |
| Valve         | Galileo                     | Notebook    | [222802e961](https://linux-hardware.org/?probe=222802e961) | Feb 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [c54b01f190](https://linux-hardware.org/?probe=c54b01f190) | Feb 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [723e90e0ad](https://linux-hardware.org/?probe=723e90e0ad) | Feb 23, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [b8d705b208](https://linux-hardware.org/?probe=b8d705b208) | Feb 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [17b0edd6f8](https://linux-hardware.org/?probe=17b0edd6f8) | Feb 23, 2024 |
| Valve         | Galileo                     | Notebook    | [f4c12237df](https://linux-hardware.org/?probe=f4c12237df) | Feb 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [4a80cf0f13](https://linux-hardware.org/?probe=4a80cf0f13) | Feb 22, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [04b45ee685](https://linux-hardware.org/?probe=04b45ee685) | Feb 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [fa56f61268](https://linux-hardware.org/?probe=fa56f61268) | Feb 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [e0565441ff](https://linux-hardware.org/?probe=e0565441ff) | Feb 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [cdcf85f04c](https://linux-hardware.org/?probe=cdcf85f04c) | Feb 21, 2024 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [f9d1325a38](https://linux-hardware.org/?probe=f9d1325a38) | Feb 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [e493063cc7](https://linux-hardware.org/?probe=e493063cc7) | Feb 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [61c3ec125c](https://linux-hardware.org/?probe=61c3ec125c) | Feb 20, 2024 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [852d20d6f7](https://linux-hardware.org/?probe=852d20d6f7) | Feb 20, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [63c3d36c4b](https://linux-hardware.org/?probe=63c3d36c4b) | Feb 19, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [e0d169ccee](https://linux-hardware.org/?probe=e0d169ccee) | Feb 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [1e4fe945b9](https://linux-hardware.org/?probe=1e4fe945b9) | Feb 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [259bfa3fd6](https://linux-hardware.org/?probe=259bfa3fd6) | Feb 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [fc900c86f1](https://linux-hardware.org/?probe=fc900c86f1) | Feb 18, 2024 |
| Valve         | Galileo                     | Notebook    | [aabc3c448c](https://linux-hardware.org/?probe=aabc3c448c) | Feb 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [1fea584115](https://linux-hardware.org/?probe=1fea584115) | Feb 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [d575568ecc](https://linux-hardware.org/?probe=d575568ecc) | Feb 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [51257484fe](https://linux-hardware.org/?probe=51257484fe) | Feb 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [51f10c1fc1](https://linux-hardware.org/?probe=51f10c1fc1) | Feb 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [db182bfb66](https://linux-hardware.org/?probe=db182bfb66) | Feb 16, 2024 |
| Valve         | Galileo                     | Notebook    | [e8ff67fb4c](https://linux-hardware.org/?probe=e8ff67fb4c) | Feb 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [4014dc3070](https://linux-hardware.org/?probe=4014dc3070) | Feb 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [3cc9a72587](https://linux-hardware.org/?probe=3cc9a72587) | Feb 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [71c7cf074b](https://linux-hardware.org/?probe=71c7cf074b) | Feb 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [4bfb818f2f](https://linux-hardware.org/?probe=4bfb818f2f) | Feb 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [ffaf97c4b5](https://linux-hardware.org/?probe=ffaf97c4b5) | Feb 12, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2c5e1e36f8](https://linux-hardware.org/?probe=2c5e1e36f8) | Feb 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [b87bcc0c74](https://linux-hardware.org/?probe=b87bcc0c74) | Feb 12, 2024 |
| Valve         | Galileo                     | Notebook    | [19586b27b1](https://linux-hardware.org/?probe=19586b27b1) | Feb 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [715d0ca807](https://linux-hardware.org/?probe=715d0ca807) | Feb 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [43e2aaa664](https://linux-hardware.org/?probe=43e2aaa664) | Feb 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [fe45dc1492](https://linux-hardware.org/?probe=fe45dc1492) | Feb 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [7753a449fe](https://linux-hardware.org/?probe=7753a449fe) | Feb 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [b2758be2c2](https://linux-hardware.org/?probe=b2758be2c2) | Feb 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [e2f2d83b90](https://linux-hardware.org/?probe=e2f2d83b90) | Feb 08, 2024 |
| Valve         | Galileo                     | Notebook    | [11d7631320](https://linux-hardware.org/?probe=11d7631320) | Feb 08, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [63ed84550f](https://linux-hardware.org/?probe=63ed84550f) | Feb 08, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [1e4f204b76](https://linux-hardware.org/?probe=1e4f204b76) | Feb 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [85375b8312](https://linux-hardware.org/?probe=85375b8312) | Feb 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [da9c1d2875](https://linux-hardware.org/?probe=da9c1d2875) | Feb 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [624ed1cc79](https://linux-hardware.org/?probe=624ed1cc79) | Feb 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [f01021ead3](https://linux-hardware.org/?probe=f01021ead3) | Feb 07, 2024 |
| Valve         | Galileo                     | Notebook    | [2ec00ae541](https://linux-hardware.org/?probe=2ec00ae541) | Feb 06, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9b1ea3c33b](https://linux-hardware.org/?probe=9b1ea3c33b) | Feb 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [aed70e45ab](https://linux-hardware.org/?probe=aed70e45ab) | Feb 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [aa0a520e23](https://linux-hardware.org/?probe=aa0a520e23) | Feb 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [1564fac4f6](https://linux-hardware.org/?probe=1564fac4f6) | Feb 04, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [a3b4d9b128](https://linux-hardware.org/?probe=a3b4d9b128) | Feb 04, 2024 |
| Dell          | Precision M6700             | Notebook    | [c35af6db34](https://linux-hardware.org/?probe=c35af6db34) | Feb 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [ae2cb6e513](https://linux-hardware.org/?probe=ae2cb6e513) | Feb 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [a9f76ff5b1](https://linux-hardware.org/?probe=a9f76ff5b1) | Feb 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [6c300e05f5](https://linux-hardware.org/?probe=6c300e05f5) | Feb 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [5823a5e361](https://linux-hardware.org/?probe=5823a5e361) | Feb 03, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f0f4ead532](https://linux-hardware.org/?probe=f0f4ead532) | Feb 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [658987799e](https://linux-hardware.org/?probe=658987799e) | Feb 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [ff59f7877a](https://linux-hardware.org/?probe=ff59f7877a) | Feb 02, 2024 |
| Valve         | Galileo                     | Notebook    | [3b44d4da2f](https://linux-hardware.org/?probe=3b44d4da2f) | Feb 02, 2024 |
| Valve         | Galileo                     | Notebook    | [aebc4c73ad](https://linux-hardware.org/?probe=aebc4c73ad) | Feb 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [ab5f4937c1](https://linux-hardware.org/?probe=ab5f4937c1) | Feb 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [238b20b912](https://linux-hardware.org/?probe=238b20b912) | Feb 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [f7647969b5](https://linux-hardware.org/?probe=f7647969b5) | Feb 01, 2024 |
| Valve         | Galileo                     | Notebook    | [c286128e50](https://linux-hardware.org/?probe=c286128e50) | Feb 01, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ae820ef040](https://linux-hardware.org/?probe=ae820ef040) | Feb 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [282271ee83](https://linux-hardware.org/?probe=282271ee83) | Jan 31, 2024 |
| Valve         | Jupiter                     | Notebook    | [574ab05eb4](https://linux-hardware.org/?probe=574ab05eb4) | Jan 31, 2024 |
| Valve         | Jupiter                     | Notebook    | [1cdbb473c3](https://linux-hardware.org/?probe=1cdbb473c3) | Jan 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [0db5dcce8b](https://linux-hardware.org/?probe=0db5dcce8b) | Jan 30, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [27229e7136](https://linux-hardware.org/?probe=27229e7136) | Jan 30, 2024 |
| QIYIDA        | ED4 V1.1                    | Desktop     | [3583de3c82](https://linux-hardware.org/?probe=3583de3c82) | Jan 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [e9a7ccf69a](https://linux-hardware.org/?probe=e9a7ccf69a) | Jan 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [f3af706ee0](https://linux-hardware.org/?probe=f3af706ee0) | Jan 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [71066ddcbf](https://linux-hardware.org/?probe=71066ddcbf) | Jan 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [72f7a8c4e7](https://linux-hardware.org/?probe=72f7a8c4e7) | Jan 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [d12b2f3bf3](https://linux-hardware.org/?probe=d12b2f3bf3) | Jan 28, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b4510875e8](https://linux-hardware.org/?probe=b4510875e8) | Jan 28, 2024 |
| Valve         | Jupiter                     | Notebook    | [7c87eec092](https://linux-hardware.org/?probe=7c87eec092) | Jan 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [7ff59e8f3a](https://linux-hardware.org/?probe=7ff59e8f3a) | Jan 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [8ae43fed66](https://linux-hardware.org/?probe=8ae43fed66) | Jan 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [3e0bcfc51d](https://linux-hardware.org/?probe=3e0bcfc51d) | Jan 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [b69df41d1b](https://linux-hardware.org/?probe=b69df41d1b) | Jan 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [ad91e418c3](https://linux-hardware.org/?probe=ad91e418c3) | Jan 25, 2024 |
| Valve         | Galileo                     | Notebook    | [b9012d8d8c](https://linux-hardware.org/?probe=b9012d8d8c) | Jan 25, 2024 |
| Valve         | Galileo                     | Notebook    | [4d738e6ad2](https://linux-hardware.org/?probe=4d738e6ad2) | Jan 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [56666176ea](https://linux-hardware.org/?probe=56666176ea) | Jan 23, 2024 |
| Valve         | Galileo                     | Notebook    | [55087a9f6f](https://linux-hardware.org/?probe=55087a9f6f) | Jan 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [83f771db1c](https://linux-hardware.org/?probe=83f771db1c) | Jan 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [9ac816140b](https://linux-hardware.org/?probe=9ac816140b) | Jan 23, 2024 |
| Valve         | Galileo                     | Notebook    | [f819a94a66](https://linux-hardware.org/?probe=f819a94a66) | Jan 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [d2a4f1790a](https://linux-hardware.org/?probe=d2a4f1790a) | Jan 22, 2024 |
| Medion        | Deputy P50                  | Notebook    | [57081b7e90](https://linux-hardware.org/?probe=57081b7e90) | Jan 22, 2024 |
| AMI           | Cherry Trail CR             | Notebook    | [873a9b67e1](https://linux-hardware.org/?probe=873a9b67e1) | Jan 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [03734c93e6](https://linux-hardware.org/?probe=03734c93e6) | Jan 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [9e62126d95](https://linux-hardware.org/?probe=9e62126d95) | Jan 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [4d7a6b2c71](https://linux-hardware.org/?probe=4d7a6b2c71) | Jan 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [890477dbac](https://linux-hardware.org/?probe=890477dbac) | Jan 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [f0e5f47e6b](https://linux-hardware.org/?probe=f0e5f47e6b) | Jan 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [e65dcac4a9](https://linux-hardware.org/?probe=e65dcac4a9) | Jan 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [4dd4fc3a4c](https://linux-hardware.org/?probe=4dd4fc3a4c) | Jan 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [a64bc13a23](https://linux-hardware.org/?probe=a64bc13a23) | Jan 19, 2024 |
| ASUSTek       | SABERTOOTH Z170 S           | Desktop     | [953ea23870](https://linux-hardware.org/?probe=953ea23870) | Jan 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [3fac9b5786](https://linux-hardware.org/?probe=3fac9b5786) | Jan 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [d9666cbb26](https://linux-hardware.org/?probe=d9666cbb26) | Jan 18, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [3cdbce90e0](https://linux-hardware.org/?probe=3cdbce90e0) | Jan 17, 2024 |
| Valve         | Galileo                     | Notebook    | [e11c272188](https://linux-hardware.org/?probe=e11c272188) | Jan 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [1ebf344a00](https://linux-hardware.org/?probe=1ebf344a00) | Jan 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [df98e57037](https://linux-hardware.org/?probe=df98e57037) | Jan 15, 2024 |
| Valve         | Galileo                     | Notebook    | [c9db96cd08](https://linux-hardware.org/?probe=c9db96cd08) | Jan 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [ff4dff4d2f](https://linux-hardware.org/?probe=ff4dff4d2f) | Jan 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [5a872c599e](https://linux-hardware.org/?probe=5a872c599e) | Jan 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [354c998efb](https://linux-hardware.org/?probe=354c998efb) | Jan 15, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ffe6ae701f](https://linux-hardware.org/?probe=ffe6ae701f) | Jan 15, 2024 |
| Valve         | Galileo                     | Notebook    | [5d92a542e4](https://linux-hardware.org/?probe=5d92a542e4) | Jan 14, 2024 |
| Valve         | Galileo                     | Notebook    | [48d337c0f3](https://linux-hardware.org/?probe=48d337c0f3) | Jan 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [51d79bc7e2](https://linux-hardware.org/?probe=51d79bc7e2) | Jan 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [4b71896940](https://linux-hardware.org/?probe=4b71896940) | Jan 13, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [52aaf67030](https://linux-hardware.org/?probe=52aaf67030) | Jan 13, 2024 |
| Valve         | Galileo                     | Notebook    | [48f9b2ac8a](https://linux-hardware.org/?probe=48f9b2ac8a) | Jan 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [07ee2b0014](https://linux-hardware.org/?probe=07ee2b0014) | Jan 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [32a7347cc6](https://linux-hardware.org/?probe=32a7347cc6) | Jan 12, 2024 |
| Valve         | Galileo                     | Notebook    | [8e6568f88e](https://linux-hardware.org/?probe=8e6568f88e) | Jan 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [168d28210d](https://linux-hardware.org/?probe=168d28210d) | Jan 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [96faa10437](https://linux-hardware.org/?probe=96faa10437) | Jan 11, 2024 |
| Valve         | Jupiter                     | Notebook    | [ab13227de0](https://linux-hardware.org/?probe=ab13227de0) | Jan 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [bc2f7eea4c](https://linux-hardware.org/?probe=bc2f7eea4c) | Jan 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [941126dfcc](https://linux-hardware.org/?probe=941126dfcc) | Jan 10, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [79504ec34b](https://linux-hardware.org/?probe=79504ec34b) | Jan 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [62bf989a58](https://linux-hardware.org/?probe=62bf989a58) | Jan 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [3462a5ad9f](https://linux-hardware.org/?probe=3462a5ad9f) | Jan 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [400f14241d](https://linux-hardware.org/?probe=400f14241d) | Jan 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [eac99b5d0a](https://linux-hardware.org/?probe=eac99b5d0a) | Jan 09, 2024 |
| Valve         | Galileo                     | Notebook    | [4032bdfc39](https://linux-hardware.org/?probe=4032bdfc39) | Jan 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [bddd9671c1](https://linux-hardware.org/?probe=bddd9671c1) | Jan 08, 2024 |
| Valve         | Galileo                     | Notebook    | [ef6307532c](https://linux-hardware.org/?probe=ef6307532c) | Jan 08, 2024 |
| Valve         | Galileo                     | Notebook    | [e71ef9c36d](https://linux-hardware.org/?probe=e71ef9c36d) | Jan 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [4ee3e89964](https://linux-hardware.org/?probe=4ee3e89964) | Jan 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [67ec614b0e](https://linux-hardware.org/?probe=67ec614b0e) | Jan 07, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9c61eb5bab](https://linux-hardware.org/?probe=9c61eb5bab) | Jan 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [1d07e80599](https://linux-hardware.org/?probe=1d07e80599) | Jan 07, 2024 |
| Valve         | Galileo                     | Notebook    | [7365f742df](https://linux-hardware.org/?probe=7365f742df) | Jan 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [da56767d30](https://linux-hardware.org/?probe=da56767d30) | Jan 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [561c912554](https://linux-hardware.org/?probe=561c912554) | Jan 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [3d47c0ba48](https://linux-hardware.org/?probe=3d47c0ba48) | Jan 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [2ccc42584e](https://linux-hardware.org/?probe=2ccc42584e) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [c23d61cde7](https://linux-hardware.org/?probe=c23d61cde7) | Jan 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [2942273257](https://linux-hardware.org/?probe=2942273257) | Jan 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [348b004789](https://linux-hardware.org/?probe=348b004789) | Jan 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [9d4ea07ea6](https://linux-hardware.org/?probe=9d4ea07ea6) | Jan 03, 2024 |
| Valve         | Galileo                     | Notebook    | [1e16b6eb69](https://linux-hardware.org/?probe=1e16b6eb69) | Jan 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [b3ada6c407](https://linux-hardware.org/?probe=b3ada6c407) | Jan 02, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [9eb25ba0bf](https://linux-hardware.org/?probe=9eb25ba0bf) | Jan 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [e381b764b0](https://linux-hardware.org/?probe=e381b764b0) | Jan 02, 2024 |
| Valve         | Jupiter                     | Notebook    | [95183ba54e](https://linux-hardware.org/?probe=95183ba54e) | Jan 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [c9de553faa](https://linux-hardware.org/?probe=c9de553faa) | Jan 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [b16497fbfc](https://linux-hardware.org/?probe=b16497fbfc) | Jan 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [e714aab1f3](https://linux-hardware.org/?probe=e714aab1f3) | Jan 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [ca7a54408f](https://linux-hardware.org/?probe=ca7a54408f) | Dec 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [5be404c400](https://linux-hardware.org/?probe=5be404c400) | Dec 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [e80d5f8a2b](https://linux-hardware.org/?probe=e80d5f8a2b) | Dec 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [c459051f01](https://linux-hardware.org/?probe=c459051f01) | Dec 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [2f8ea60a38](https://linux-hardware.org/?probe=2f8ea60a38) | Dec 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [0254493ea3](https://linux-hardware.org/?probe=0254493ea3) | Dec 29, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [c6cd1c43ba](https://linux-hardware.org/?probe=c6cd1c43ba) | Dec 29, 2023 |
| Valve         | Galileo                     | Notebook    | [83bfa965fb](https://linux-hardware.org/?probe=83bfa965fb) | Dec 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [73a4d3fcfd](https://linux-hardware.org/?probe=73a4d3fcfd) | Dec 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [bee71f6f73](https://linux-hardware.org/?probe=bee71f6f73) | Dec 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [eeac675274](https://linux-hardware.org/?probe=eeac675274) | Dec 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [c2f08b6c04](https://linux-hardware.org/?probe=c2f08b6c04) | Dec 26, 2023 |
| HP            | ProBook 455 G3              | Notebook    | [9e47611108](https://linux-hardware.org/?probe=9e47611108) | Dec 26, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [b5b5857360](https://linux-hardware.org/?probe=b5b5857360) | Dec 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [6117a0c576](https://linux-hardware.org/?probe=6117a0c576) | Dec 25, 2023 |
| Valve         | Galileo                     | Notebook    | [e21296767e](https://linux-hardware.org/?probe=e21296767e) | Dec 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [4ab75ea56b](https://linux-hardware.org/?probe=4ab75ea56b) | Dec 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [509364a4ac](https://linux-hardware.org/?probe=509364a4ac) | Dec 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [94cf6bda69](https://linux-hardware.org/?probe=94cf6bda69) | Dec 25, 2023 |
| Valve         | Galileo                     | Notebook    | [99c3c24140](https://linux-hardware.org/?probe=99c3c24140) | Dec 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [6ec124a0c4](https://linux-hardware.org/?probe=6ec124a0c4) | Dec 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [3f9fc8839c](https://linux-hardware.org/?probe=3f9fc8839c) | Dec 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [f57d2e51fe](https://linux-hardware.org/?probe=f57d2e51fe) | Dec 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [4c98f6b6f3](https://linux-hardware.org/?probe=4c98f6b6f3) | Dec 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [c0b15b216d](https://linux-hardware.org/?probe=c0b15b216d) | Dec 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [19f8d4f0b4](https://linux-hardware.org/?probe=19f8d4f0b4) | Dec 24, 2023 |
| Anbernic      | Win600                      | Notebook    | [3b5255f14b](https://linux-hardware.org/?probe=3b5255f14b) | Dec 24, 2023 |
| Valve         | Galileo                     | Notebook    | [aa141b8ea2](https://linux-hardware.org/?probe=aa141b8ea2) | Dec 24, 2023 |
| Anbernic      | Win600                      | Notebook    | [02e1d7adeb](https://linux-hardware.org/?probe=02e1d7adeb) | Dec 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [6fd8f41741](https://linux-hardware.org/?probe=6fd8f41741) | Dec 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [482500f7b0](https://linux-hardware.org/?probe=482500f7b0) | Dec 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [03491495da](https://linux-hardware.org/?probe=03491495da) | Dec 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [4899962b6a](https://linux-hardware.org/?probe=4899962b6a) | Dec 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [f30a4a2d8a](https://linux-hardware.org/?probe=f30a4a2d8a) | Dec 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [6003cb709f](https://linux-hardware.org/?probe=6003cb709f) | Dec 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [186428f160](https://linux-hardware.org/?probe=186428f160) | Dec 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [091511a6c2](https://linux-hardware.org/?probe=091511a6c2) | Dec 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [ceba2299c2](https://linux-hardware.org/?probe=ceba2299c2) | Dec 20, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/SteamOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| SteamOS 3.5.19                | 266       | 11.66%  |
| SteamOS 3.5.7                 | 227       | 9.95%   |
| SteamOS 3.4.4                 | 179       | 7.85%   |
| SteamOS 3.4.6                 | 157       | 6.88%   |
| SteamOS 3.4.8                 | 146       | 6.4%    |
| SteamOS 3.3.2                 | 117       | 5.13%   |
| SteamOS 3.5.17                | 110       | 4.82%   |
| SteamOS 3.4                   | 108       | 4.73%   |
| SteamOS 3.3.1                 | 107       | 4.69%   |
| SteamOS 3.6.20                | 87        | 3.81%   |
| SteamOS 3.3                   | 87        | 3.81%   |
| SteamOS 3.4.10                | 64        | 2.81%   |
| SteamOS 3.2                   | 59        | 2.59%   |
| SteamOS 3.4.11                | 57        | 2.5%    |
| SteamOS 4                     | 56        | 2.46%   |
| SteamOS 3.5                   | 30        | 1.32%   |
| SteamOS Rolling               | 28        | 1.23%   |
| SteamOS 3.6                   | 27        | 1.18%   |
| SteamOS Snapshot              | 26        | 1.14%   |
| SteamOS 3.5.5                 | 26        | 1.14%   |
| SteamOS 3.4.2                 | 23        | 1.01%   |
| SteamOS                       | 23        | 1.01%   |
| SteamOS 3.7                   | 21        | 0.92%   |
| SteamOS 1.3-mesa-fixes        | 19        | 0.83%   |
| SteamOS 3.1                   | 17        | 0.75%   |
| SteamOS 3.6.9                 | 16        | 0.7%    |
| SteamOS 3.3.3                 | 15        | 0.66%   |
| SteamOS 3.6.19                | 14        | 0.61%   |
| SteamOS 3.5.1                 | 14        | 0.61%   |
| SteamOS 3.2 (steamdeck-main)  | 14        | 0.61%   |
| SteamOS 3.6.8                 | 12        | 0.53%   |
| SteamOS 3.5.13                | 9         | 0.39%   |
| SteamOS 3.6.21                | 8         | 0.35%   |
| SteamOS 3.6.17                | 8         | 0.35%   |
| SteamOS 3.4.5                 | 8         | 0.35%   |
| SteamOS 1.5-next-fixes        | 8         | 0.35%   |
| SteamOS 3.4.3                 | 7         | 0.31%   |
| SteamOS 1.1.2                 | 7         | 0.31%   |
| SteamOS 3.6.3                 | 5         | 0.22%   |
| SteamOS 1.1.6-prefinal_fixups | 5         | 0.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SteamOS | 2038      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| 5.13.0-valve36-1-neptune                           | 503       | 22.31%  |
| 6.1.52-valve16-1-neptune-61                        | 375       | 16.63%  |
| 6.1.52-valve9-1-neptune-61                         | 224       | 9.93%   |
| 5.13.0-valve21.3-1-neptune                         | 191       | 8.47%   |
| 5.13.0-valve37-1-neptune                           | 127       | 5.63%   |
| 5.13.0-valve21.1-1-neptune-02211-gc54cda5a36f3     | 110       | 4.88%   |
| 6.5.0-valve22-1-neptune-65-g9a338ed8a75e           | 100       | 4.43%   |
| 5.13.0-valve15-1-neptune-02197-gf6ec7ad3762a       | 54        | 2.39%   |
| 6.3.7-zen1-1-zen                                   | 46        | 2.04%   |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 36        | 1.6%    |
| 6.8.5-1-lljy-CFS-gcd11c870c00c                     | 31        | 1.37%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 31        | 1.37%   |
| 6.1.52-valve7-1-neptune-61                         | 29        | 1.29%   |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 24        | 1.06%   |
| 6.1.52-valve2-1-neptune-61                         | 19        | 0.84%   |
| 5.13.0-valve10.3-1-neptune-02176-g5fe416c4acd8     | 19        | 0.84%   |
| 6.4.12-zen1-1-zen                                  | 17        | 0.75%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 16        | 0.71%   |
| 5.13.0-valve10.1-1-neptune-02144-g7fffaf925dfb     | 16        | 0.71%   |
| 6.5.0-valve16-2-neptune-65-gc9ad4106624e           | 15        | 0.67%   |
| 6.1.52-valve3-1-neptune-61                         | 14        | 0.62%   |
| 6.5.0-valve12-1-neptune-65-g1889664e19fc           | 13        | 0.58%   |
| 6.5.0-valve21-1-neptune-65-g33487bf05ed3           | 12        | 0.53%   |
| 6.1.52-valve14-1-neptune-61                        | 12        | 0.53%   |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 12        | 0.53%   |
| 5.13.0-valve31-1-neptune                           | 11        | 0.49%   |
| 6.5.0-valve23-1-neptune-65-g385b5e207ae2           | 9         | 0.4%    |
| 6.5.0-valve19-1-neptune-65-g8e4b171a9b33           | 9         | 0.4%    |
| 6.7.4-holoiso-beta_lljy-kernel-lljy-g76a2d2abfbba  | 8         | 0.35%   |
| 6.1.52-valve10-1-neptune-61                        | 8         | 0.35%   |
| 6.1.21-valve1-3-neptune-61                         | 8         | 0.35%   |
| 6.1.21-valve1-1-neptune-61                         | 8         | 0.35%   |
| 5.13.0-valve35-1-neptune                           | 8         | 0.35%   |
| 6.5.0-valve5-1-neptune-65-g6efe817cc486            | 7         | 0.31%   |
| 6.1.43-valve1-1-neptune-61                         | 7         | 0.31%   |
| 5.13.0-valve24-1-neptune                           | 7         | 0.31%   |
| 6.5.0-valve13-1-neptune-65-gd5e176bdacb0           | 6         | 0.27%   |
| 5.13.0-valve21.2-1-neptune                         | 6         | 0.27%   |
| 5.13.0-valve21-1-steamos-02209-g2a5bdc1102a0       | 6         | 0.27%   |
| 6.10.7-1-lljy-g2fd7b345494a                        | 5         | 0.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 1114      | 51.79%  |
| 6.1.52  | 667       | 31.01%  |
| 6.5.0   | 172       | 8%      |
| 6.3.7   | 46        | 2.14%   |
| 6.8.5   | 31        | 1.44%   |
| 6.1.21  | 18        | 0.84%   |
| 6.4.12  | 17        | 0.79%   |
| 5.18.1  | 16        | 0.74%   |
| 6.8.12  | 9         | 0.42%   |
| 6.7.4   | 8         | 0.37%   |
| 6.1.43  | 7         | 0.33%   |
| 6.10.7  | 5         | 0.23%   |
| 6.1.12  | 5         | 0.23%   |
| 5.15.93 | 5         | 0.23%   |
| 6.8.8   | 3         | 0.14%   |
| 6.0.9   | 3         | 0.14%   |
| 5.15.79 | 3         | 0.14%   |
| 6.1.9   | 2         | 0.09%   |
| 6.1.29  | 2         | 0.09%   |
| 5.15.60 | 2         | 0.09%   |
| 5.15.54 | 2         | 0.09%   |
| 6.4.3   | 1         | 0.05%   |
| 6.4.0   | 1         | 0.05%   |
| 6.3.9   | 1         | 0.05%   |
| 6.12.6  | 1         | 0.05%   |
| 6.11.6  | 1         | 0.05%   |
| 6.11.1  | 1         | 0.05%   |
| 6.10.4  | 1         | 0.05%   |
| 6.10.10 | 1         | 0.05%   |
| 6.1.5   | 1         | 0.05%   |
| 6.1.39  | 1         | 0.05%   |
| 6.1.3   | 1         | 0.05%   |
| 6.1.1   | 1         | 0.05%   |
| 6.0.7   | 1         | 0.05%   |
| 5.16.2  | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 1114      | 51.91%  |
| 6.1     | 701       | 32.67%  |
| 6.5     | 172       | 8.01%   |
| 6.3     | 47        | 2.19%   |
| 6.8     | 43        | 2%      |
| 6.4     | 18        | 0.84%   |
| 5.18    | 16        | 0.75%   |
| 5.15    | 12        | 0.56%   |
| 6.7     | 8         | 0.37%   |
| 6.10    | 7         | 0.33%   |
| 6.0     | 4         | 0.19%   |
| 6.11    | 2         | 0.09%   |
| 6.12    | 1         | 0.05%   |
| 5.16    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2038      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| KDE5      | 2025      | 98.93%  |
| gamescope | 9         | 0.44%   |
| Unknown   | 6         | 0.29%   |
| KDE6      | 3         | 0.15%   |
| KDE       | 3         | 0.15%   |
| GNOME     | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2027      | 99.27%  |
| Tty     | 8         | 0.39%   |
| Wayland | 5         | 0.24%   |
| Unknown | 2         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2012      | 98.68%  |
| SDDM    | 27        | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| en_US        | 1693      | 82.14%  |
| C            | 55        | 2.67%   |
| ru_RU        | 54        | 2.62%   |
| de_DE        | 52        | 2.52%   |
| fr_FR        | 28        | 1.36%   |
| en_GB        | 28        | 1.36%   |
| es_ES        | 26        | 1.26%   |
| zh_CN        | 19        | 0.92%   |
| pt_BR        | 17        | 0.82%   |
| pl_PL        | 15        | 0.73%   |
| en_DE        | 12        | 0.58%   |
| it_IT        | 7         | 0.34%   |
| an_ES        | 7         | 0.34%   |
| ko_KR        | 5         | 0.24%   |
| cs_CZ        | 4         | 0.19%   |
| zh_TW        | 3         | 0.15%   |
| ru_UA        | 2         | 0.1%    |
| pt_PT        | 2         | 0.1%    |
| hu_HU        | 2         | 0.1%    |
| es_MX        | 2         | 0.1%    |
| en_NL        | 2         | 0.1%    |
| en_IE        | 2         | 0.1%    |
| en_CA        | 2         | 0.1%    |
| ba_RU        | 2         | 0.1%    |
| tr_TR        | 1         | 0.05%   |
| sk_SK        | 1         | 0.05%   |
| pl           | 1         | 0.05%   |
| n_US         | 1         | 0.05%   |
| nl_NL        | 1         | 0.05%   |
| nl_BE        | 1         | 0.05%   |
| ksh_DE       | 1         | 0.05%   |
| ja_JP        | 1         | 0.05%   |
| hr_HR        | 1         | 0.05%   |
| fr_BE        | 1         | 0.05%   |
| et_EE        | 1         | 0.05%   |
| es_UY        | 1         | 0.05%   |
| en_SE        | 1         | 0.05%   |
| en_IN        | 1         | 0.05%   |
| en_HK        | 1         | 0.05%   |
| en_GB.UTF-12 | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2006      | 98.24%  |
| EFI  | 36        | 1.76%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 2024      | 99.31%  |
| Tmpfs | 12        | 0.59%   |
| Ext4  | 2         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2005      | 98.14%  |
| GPT     | 38        | 1.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2017      | 98.82%  |
| Yes       | 24        | 1.18%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2031      | 99.66%  |
| Yes       | 7         | 0.34%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Valve                                | 1696      | 83.22%  |
| ASUSTek Computer                     | 71        | 3.48%   |
| Gigabyte Technology                  | 43        | 2.11%   |
| Hewlett-Packard                      | 35        | 1.72%   |
| MSI                                  | 29        | 1.42%   |
| Dell                                 | 28        | 1.37%   |
| ASRock                               | 27        | 1.32%   |
| Lenovo                               | 23        | 1.13%   |
| Apple                                | 12        | 0.59%   |
| GPD                                  | 9         | 0.44%   |
| Acer                                 | 8         | 0.39%   |
| AZW                                  | 6         | 0.29%   |
| ONE-NETBOOK                          | 5         | 0.25%   |
| ONE-NETBOOK TECHNOLOGY               | 4         | 0.2%    |
| AOKZOE                               | 4         | 0.2%    |
| Shenzhen Meigao Electronic Equipment | 3         | 0.15%   |
| Intel                                | 3         | 0.15%   |
| AYANEO                               | 3         | 0.15%   |
| Anbernic                             | 3         | 0.15%   |
| Unknown                              | 3         | 0.15%   |
| Samsung Electronics                  | 2         | 0.1%    |
| Microsoft                            | 2         | 0.1%    |
| Biostar                              | 2         | 0.1%    |
| AMI                                  | 2         | 0.1%    |
| Alienware                            | 2         | 0.1%    |
| Teclast                              | 1         | 0.05%   |
| Supermicro                           | 1         | 0.05%   |
| Sony                                 | 1         | 0.05%   |
| QIYIDA                               | 1         | 0.05%   |
| Monster                              | 1         | 0.05%   |
| MeLE                                 | 1         | 0.05%   |
| Medion                               | 1         | 0.05%   |
| MAXSUN                               | 1         | 0.05%   |
| MACHINIST                            | 1         | 0.05%   |
| HUAWEI                               | 1         | 0.05%   |
| GPU Company                          | 1         | 0.05%   |
| Google                               | 1         | 0.05%   |
| ADVANCE                              | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Valve Jupiter                                       | 1508      | 73.99%  |
| Valve Galileo                                       | 188       | 9.22%   |
| ASUS All Series                                     | 6         | 0.29%   |
| GPD G1619-04                                        | 5         | 0.25%   |
| AZW SER                                             | 5         | 0.25%   |
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER                  | 4         | 0.2%    |
| Gigabyte B450 AORUS M                               | 4         | 0.2%    |
| ASUS PRIME A320M-K                                  | 4         | 0.2%    |
| AOKZOE A1 AR07                                      | 4         | 0.2%    |
| Unknown                                             | 4         | 0.2%    |
| MSI MS-7C02                                         | 3         | 0.15%   |
| Gigabyte B450M GAMING                               | 3         | 0.15%   |
| ASUS ROG STRIX B550-F GAMING                        | 3         | 0.15%   |
| ASUS ROG Ally RC71L_RC71L                           | 3         | 0.15%   |
| ASRock B450 Gaming-ITX/ac                           | 3         | 0.15%   |
| Anbernic Win600                                     | 3         | 0.15%   |
| ONE-NETBOOK ONEXPLAYER Mini Pro                     | 2         | 0.1%    |
| ONE-NETBOOK ONEXPLAYER 2 ARP23                      | 2         | 0.1%    |
| MSI MS-7C95                                         | 2         | 0.1%    |
| MSI MS-7C37                                         | 2         | 0.1%    |
| Lenovo IdeaPadFlex 5 14ALC05 82HU                   | 2         | 0.1%    |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2                 | 2         | 0.1%    |
| HP Victus by 15L Gaming Desktop TG02-0xxx           | 2         | 0.1%    |
| HP Pavilion 17                                      | 2         | 0.1%    |
| HP Laptop 15s-eq2xxx                                | 2         | 0.1%    |
| HP Laptop 15-bs0xx                                  | 2         | 0.1%    |
| Gigabyte B550M DS3H                                 | 2         | 0.1%    |
| Gigabyte B550 GAMING X V2                           | 2         | 0.1%    |
| Dell OptiPlex 9010                                  | 2         | 0.1%    |
| ASUS ROG STRIX B550-I GAMING                        | 2         | 0.1%    |
| ASUS PRIME B450M-A II                               | 2         | 0.1%    |
| ASRock B550M Steel Legend                           | 2         | 0.1%    |
| Apple Macmini7,1                                    | 2         | 0.1%    |
| Apple MacBookPro8,1                                 | 2         | 0.1%    |
| Apple MacBookPro15,1                                | 2         | 0.1%    |
| Teclast TbooK 16 Power                              | 1         | 0.05%   |
| Supermicro C7H170-M                                 | 1         | 0.05%   |
| Sony VGN-Z520N                                      | 1         | 0.05%   |
| Shenzhen Meigao Electronic Equipment UM690          | 1         | 0.05%   |
| Shenzhen Meigao Electronic Equipment Mercury series | 1         | 0.05%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Valve Jupiter              | 1508      | 73.99%  |
| Valve Galileo              | 188       | 9.22%   |
| ASUS ROG                   | 17        | 0.83%   |
| ASUS PRIME                 | 16        | 0.79%   |
| HP Pavilion                | 10        | 0.49%   |
| ASUS TUF                   | 10        | 0.49%   |
| Lenovo IdeaPad             | 7         | 0.34%   |
| HP Laptop                  | 7         | 0.34%   |
| Dell Precision             | 7         | 0.34%   |
| Dell OptiPlex              | 7         | 0.34%   |
| Gigabyte B450M             | 6         | 0.29%   |
| Gigabyte B450              | 6         | 0.29%   |
| ASUS All                   | 6         | 0.29%   |
| ONE-NETBOOK ONEXPLAYER     | 5         | 0.25%   |
| GPD G1619-04               | 5         | 0.25%   |
| Dell Inspiron              | 5         | 0.25%   |
| AZW SER                    | 5         | 0.25%   |
| ONE-NETBOOK TECHNOLOGY ONE | 4         | 0.2%    |
| HP Victus                  | 4         | 0.2%    |
| ASRock B450                | 4         | 0.2%    |
| AOKZOE A1                  | 4         | 0.2%    |
| Acer Nitro                 | 4         | 0.2%    |
| Unknown                    | 4         | 0.2%    |
| MSI MS-7C02                | 3         | 0.15%   |
| Lenovo ThinkCentre         | 3         | 0.15%   |
| Lenovo Legion              | 3         | 0.15%   |
| HP EliteDesk               | 3         | 0.15%   |
| Gigabyte X570              | 3         | 0.15%   |
| Gigabyte B550M             | 3         | 0.15%   |
| Dell XPS                   | 3         | 0.15%   |
| ASRock X570                | 3         | 0.15%   |
| ASRock B550M               | 3         | 0.15%   |
| Anbernic Win600            | 3         | 0.15%   |
| Acer Aspire                | 3         | 0.15%   |
| MSI MS-7C95                | 2         | 0.1%    |
| MSI MS-7C37                | 2         | 0.1%    |
| MSI Katana                 | 2         | 0.1%    |
| Microsoft Surface          | 2         | 0.1%    |
| Lenovo Yoga                | 2         | 0.1%    |
| Lenovo ThinkStation        | 2         | 0.1%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 923       | 45.29%  |
| 2023    | 650       | 31.89%  |
| 2024    | 183       | 8.98%   |
| 2021    | 56        | 2.75%   |
| 2020    | 44        | 2.16%   |
| 2018    | 40        | 1.96%   |
| 2017    | 30        | 1.47%   |
| 2019    | 28        | 1.37%   |
| 2016    | 15        | 0.74%   |
| Unknown | 15        | 0.74%   |
| 2013    | 14        | 0.69%   |
| 2012    | 13        | 0.64%   |
| 2015    | 11        | 0.54%   |
| 2014    | 10        | 0.49%   |
| 2011    | 4         | 0.2%    |
| 2009    | 1         | 0.05%   |
| 2008    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1808      | 88.71%  |
| Desktop     | 175       | 8.59%   |
| Tablet      | 21        | 1.03%   |
| Mini pc     | 18        | 0.88%   |
| Convertible | 11        | 0.54%   |
| All in one  | 4         | 0.2%    |
| Server      | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2038      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2037      | 99.95%  |
| Yes  | 1         | 0.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 1771      | 86.81%  |
| 16.01-24.0  | 96        | 4.71%   |
| 32.01-64.0  | 67        | 3.28%   |
| 4.01-8.0    | 50        | 2.45%   |
| 24.01-32.0  | 32        | 1.57%   |
| 3.01-4.0    | 13        | 0.64%   |
| 64.01-256.0 | 10        | 0.49%   |
| 2.01-3.0    | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 734       | 33.11%  |
| 4.01-8.0  | 707       | 31.89%  |
| 2.01-3.0  | 610       | 27.51%  |
| 1.01-2.0  | 104       | 4.69%   |
| 8.01-16.0 | 61        | 2.75%   |
| 0.51-1.0  | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 1185      | 56.35%  |
| 1      | 775       | 36.85%  |
| 3      | 91        | 4.33%   |
| 4      | 31        | 1.47%   |
| 5      | 14        | 0.67%   |
| 6      | 2         | 0.1%    |
| 0      | 2         | 0.1%    |
| 11     | 1         | 0.05%   |
| 8      | 1         | 0.05%   |
| 7      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1983      | 97.21%  |
| Yes       | 57        | 2.79%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1220      | 58.18%  |
| Yes       | 877       | 41.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1963      | 96.32%  |
| No        | 75        | 3.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1740      | 85.25%  |
| No        | 301       | 14.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 801       | 39.19%  |
| Germany      | 171       | 8.37%   |
| UK           | 165       | 8.07%   |
| Russia       | 105       | 5.14%   |
| Canada       | 86        | 4.21%   |
| France       | 59        | 2.89%   |
| Poland       | 54        | 2.64%   |
| Spain        | 51        | 2.5%    |
| Brazil       | 48        | 2.35%   |
| Netherlands  | 36        | 1.76%   |
| Australia    | 30        | 1.47%   |
| Italy        | 26        | 1.27%   |
| China        | 24        | 1.17%   |
| Mexico       | 21        | 1.03%   |
| Austria      | 18        | 0.88%   |
| Philippines  | 17        | 0.83%   |
| Sweden       | 16        | 0.78%   |
| Hungary      | 16        | 0.78%   |
| Israel       | 13        | 0.64%   |
| Czechia      | 13        | 0.64%   |
| Romania      | 11        | 0.54%   |
| Ireland      | 11        | 0.54%   |
| Chile        | 11        | 0.54%   |
| Ukraine      | 10        | 0.49%   |
| UAE          | 10        | 0.49%   |
| Saudi Arabia | 10        | 0.49%   |
| Japan        | 10        | 0.49%   |
| Indonesia    | 10        | 0.49%   |
| Belgium      | 10        | 0.49%   |
| South Korea  | 9         | 0.44%   |
| Slovakia     | 9         | 0.44%   |
| Hong Kong    | 9         | 0.44%   |
| Denmark      | 9         | 0.44%   |
| Switzerland  | 8         | 0.39%   |
| Portugal     | 8         | 0.39%   |
| Taiwan       | 7         | 0.34%   |
| Turkey       | 6         | 0.29%   |
| Malaysia     | 6         | 0.29%   |
| India        | 6         | 0.29%   |
| Finland      | 6         | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Moscow              | 38        | 1.77%   |
| Berlin              | 17        | 0.79%   |
| Madrid              | 14        | 0.65%   |
| St Petersburg       | 13        | 0.61%   |
| Seattle             | 13        | 0.61%   |
| Dallas              | 13        | 0.61%   |
| Warsaw              | 12        | 0.56%   |
| Portland            | 11        | 0.51%   |
| Los Angeles         | 11        | 0.51%   |
| Austin              | 11        | 0.51%   |
| Sydney              | 10        | 0.47%   |
| Toronto             | 9         | 0.42%   |
| Melbourne           | 9         | 0.42%   |
| Chicago             | 9         | 0.42%   |
| Santiago            | 8         | 0.37%   |
| London              | 8         | 0.37%   |
| Flushing            | 8         | 0.37%   |
| Dubai               | 8         | 0.37%   |
| Denver              | 8         | 0.37%   |
| Atlanta             | 8         | 0.37%   |
| Prague              | 7         | 0.33%   |
| Indianapolis        | 7         | 0.33%   |
| Hamburg             | 7         | 0.33%   |
| Budapest            | 7         | 0.33%   |
| Brooklyn            | 7         | 0.33%   |
| Amsterdam           | 7         | 0.33%   |
| Sao Paulo           | 6         | 0.28%   |
| New York            | 6         | 0.28%   |
| Munich              | 6         | 0.28%   |
| Miami               | 6         | 0.28%   |
| Vienna              | 5         | 0.23%   |
| Valencia            | 5         | 0.23%   |
| The Bronx           | 5         | 0.23%   |
| Tel Aviv            | 5         | 0.23%   |
| Tacoma              | 5         | 0.23%   |
| Poznan              | 5         | 0.23%   |
| Paris               | 5         | 0.23%   |
| Oklahoma City       | 5         | 0.23%   |
| Nuremberg           | 5         | 0.23%   |
| Newcastle upon Tyne | 5         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Unknown                        | 896       | 1060   | 25.35%  |
| Phison Electronics             | 429       | 517    | 12.14%  |
| Samsung Electronics            | 382       | 473    | 10.81%  |
| Kingston Technology Company    | 340       | 403    | 9.62%   |
| Unknown                        | 256       | 304    | 7.24%   |
| O2 Micro                       | 226       | 252    | 6.39%   |
| SanDisk                        | 160       | 191    | 4.53%   |
| Kingston                       | 119       | 132    | 3.37%   |
| Phison                         | 85        | 88     | 2.4%    |
| Seagate                        | 79        | 103    | 2.23%   |
| Silicon Motion                 | 72        | 82     | 2.04%   |
| Micron Technology              | 65        | 74     | 1.84%   |
| WDC                            | 53        | 67     | 1.5%    |
| SK hynix                       | 43        | 59     | 1.22%   |
| KIOXIA                         | 32        | 36     | 0.91%   |
| Toshiba                        | 27        | 31     | 0.76%   |
| Crucial                        | 26        | 34     | 0.74%   |
| MAXIO Technology (Hangzhou)    | 22        | 28     | 0.62%   |
| Micron/Crucial Technology      | 18        | 18     | 0.51%   |
| Realtek                        | 15        | 19     | 0.42%   |
| Intel                          | 14        | 16     | 0.4%    |
| A-DATA Technology              | 14        | 14     | 0.4%    |
| JMicron Technology             | 13        | 13     | 0.37%   |
| Biwin Storage Technology       | 12        | 13     | 0.34%   |
| PNY                            | 10        | 11     | 0.28%   |
| China                          | 8         | 11     | 0.23%   |
| Apple                          | 8         | 12     | 0.23%   |
| Realtek Semiconductor          | 7         | 7      | 0.2%    |
| Solid State Storage Technology | 6         | 7      | 0.17%   |
| Hitachi                        | 6         | 6      | 0.17%   |
| SPCC                           | 5         | 7      | 0.14%   |
| SABRENT                        | 5         | 5      | 0.14%   |
| Patriot                        | 5         | 5      | 0.14%   |
| ASMT                           | 4         | 5      | 0.11%   |
| ADATA Technology               | 4         | 5      | 0.11%   |
| T-FORCE                        | 3         | 3      | 0.08%   |
| Solid State Storage            | 3         | 3      | 0.08%   |
| Mushkin                        | 3         | 3      | 0.08%   |
| Timetec                        | 2         | 2      | 0.06%   |
| Shenzhen Longsys Electronics   | 2         | 2      | 0.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown MMC Card  512GB                               | 392       | 10.79%  |
| Kingston Company OM3PDP3 NVMe SSD 512GB               | 333       | 9.17%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 301       | 8.29%   |
| Unknown                                               | 256       | 7.05%   |
| O2 Micro E2M2 64GB                                    | 212       | 5.84%   |
| Unknown MMC Card  256GB                               | 195       | 5.37%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                      | 145       | 3.99%   |
| Unknown MMC Card  128GB                               | 110       | 3.03%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                      | 87        | 2.4%    |
| Phison NVMe SSD Drive 512GB                           | 55        | 1.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 52        | 1.43%   |
| Unknown MMC Card  64GB                                | 43        | 1.18%   |
| Kingston NVMe SSD Drive 512GB                         | 42        | 1.16%   |
| Sandisk WD PC SN740 SDDPTQD-1T00 1024GB               | 39        | 1.07%   |
| Unknown MMC Card  32GB                                | 34        | 0.94%   |
| Phison Sabrent SB-2130-1TB                            | 32        | 0.88%   |
| Kingston NVMe SSD Drive 256GB                         | 32        | 0.88%   |
| Sandisk WD PC SN740 SDDPTQE-2T00 2TB                  | 31        | 0.85%   |
| Phison ESMP001TKB5C3-E19TS 1024GB                     | 30        | 0.83%   |
| Micron 2400_MTFDKBK1T0QFM 1024GB                      | 28        | 0.77%   |
| Unknown MMC Card  393GB                               | 26        | 0.72%   |
| Samsung MZ9L41T0HBLB-00AVL 1024GB                     | 23        | 0.63%   |
| Phison NVMe SSD Drive 256GB                           | 18        | 0.5%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB    | 17        | 0.47%   |
| Unknown MMC Card  1TB                                 | 15        | 0.41%   |
| O2 Micro NVMe SSD Drive 64GB                          | 15        | 0.41%   |
| Micron 2400_MTFDKBK512QFM 512GB                       | 14        | 0.39%   |
| Unknown MMC Card  250GB                               | 13        | 0.36%   |
| Unknown MMC Card  16GB                                | 13        | 0.36%   |
| Sandisk WDC PC SN530 SDBPTPZ-1T00 1024GB              | 13        | 0.36%   |
| SK hynix BC711 NVMe 256GB                             | 11        | 0.3%    |
| Realtek RTL9210B-CG 500GB                             | 11        | 0.3%    |
| Phison Corsair MP600 MINI 1TB                         | 11        | 0.3%    |
| Unknown MMC Card  249GB                               | 10        | 0.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 10        | 0.28%   |
| Unknown MMC Card  500GB                               | 9         | 0.25%   |
| SK hynix BC511 512GB                                  | 9         | 0.25%   |
| Samsung MZ9LQ1T0HBLB-00B00 1024GB                     | 9         | 0.25%   |
| Micron 2400_MTFDKBK2T0QFM 2TB                         | 9         | 0.25%   |
| Unknown MMC Card  196GB                               | 8         | 0.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 95     | 44.51%  |
| WDC                 | 35        | 44     | 21.34%  |
| Toshiba             | 22        | 25     | 13.41%  |
| JMicron Technology  | 6         | 6      | 3.66%   |
| Hitachi             | 6         | 6      | 3.66%   |
| Samsung Electronics | 5         | 5      | 3.05%   |
| SABRENT             | 3         | 3      | 1.83%   |
| Apple               | 3         | 7      | 1.83%   |
| HGST                | 2         | 2      | 1.22%   |
| ASMT                | 2         | 2      | 1.22%   |
| Unknown             | 1         | 1      | 0.61%   |
| TO Exter            | 1         | 1      | 0.61%   |
| StoreJet            | 1         | 1      | 0.61%   |
| Maxtor              | 1         | 1      | 0.61%   |
| Maxone              | 1         | 1      | 0.61%   |
| LaCie               | 1         | 1      | 0.61%   |
| External            | 1         | 2      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 58     | 19.73%  |
| Kingston            | 31        | 35     | 13.9%   |
| Crucial             | 26        | 34     | 11.66%  |
| WDC                 | 21        | 22     | 9.42%   |
| SanDisk             | 19        | 20     | 8.52%   |
| A-DATA Technology   | 11        | 11     | 4.93%   |
| PNY                 | 10        | 11     | 4.48%   |
| China               | 8         | 11     | 3.59%   |
| SPCC                | 5         | 7      | 2.24%   |
| Patriot             | 5         | 5      | 2.24%   |
| Micron Technology   | 4         | 5      | 1.79%   |
| Mushkin             | 3         | 3      | 1.35%   |
| SK hynix            | 2         | 2      | 0.9%    |
| KingSpec            | 2         | 2      | 0.9%    |
| GLOWAY              | 2         | 2      | 0.9%    |
| ASMT                | 2         | 3      | 0.9%    |
| Apple               | 2         | 2      | 0.9%    |
| Unknown             | 2         | 2      | 0.9%    |
| WDC WDB             | 1         | 1      | 0.45%   |
| Verbatim            | 1         | 2      | 0.45%   |
| Union Memory        | 1         | 1      | 0.45%   |
| TrekStor            | 1         | 1      | 0.45%   |
| Transcend           | 1         | 1      | 0.45%   |
| Team                | 1         | 1      | 0.45%   |
| SABRENT             | 1         | 1      | 0.45%   |
| Ramsta              | 1         | 1      | 0.45%   |
| NGFF                | 1         | 1      | 0.45%   |
| Netac               | 1         | 1      | 0.45%   |
| Lexar 25            | 1         | 1      | 0.45%   |
| Kingchuxing         | 1         | 1      | 0.45%   |
| KEEPDATA            | 1         | 1      | 0.45%   |
| Intenso             | 1         | 1      | 0.45%   |
| INTEL SS            | 1         | 1      | 0.45%   |
| Intel               | 1         | 1      | 0.45%   |
| HUSKY               | 1         | 1      | 0.45%   |
| HP Phison           | 1         | 1      | 0.45%   |
| Gigastone           | 1         | 1      | 0.45%   |
| Dell                | 1         | 1      | 0.45%   |
| Corsair             | 1         | 1      | 0.45%   |
| BIWIN               | 1         | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1917      | 2333   | 56.32%  |
| MMC     | 1131      | 1346   | 33.23%  |
| SSD     | 186       | 260    | 5.46%   |
| HDD     | 134       | 203    | 3.94%   |
| Unknown | 36        | 39     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1917      | 2303   | 57.09%  |
| MMC  | 1131      | 1346   | 33.68%  |
| SATA | 204       | 391    | 6.08%   |
| SAS  | 106       | 141    | 3.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 157       | 218    | 45.51%  |
| 0.51-1.0   | 104       | 140    | 30.14%  |
| 1.01-2.0   | 44        | 58     | 12.75%  |
| 3.01-4.0   | 16        | 20     | 4.64%   |
| 4.01-10.0  | 14        | 14     | 4.06%   |
| 2.01-3.0   | 6         | 8      | 1.74%   |
| 10.01-20.0 | 4         | 5      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 741       | 34.47%  |
| 501-1000       | 511       | 23.77%  |
| 101-250        | 385       | 17.91%  |
| 1001-2000      | 249       | 11.58%  |
| 51-100         | 156       | 7.26%   |
| 2001-3000      | 48        | 2.23%   |
| More than 3000 | 43        | 2%      |
| Unknown        | 8         | 0.37%   |
| 21-50          | 7         | 0.33%   |
| 1-20           | 2         | 0.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 545       | 24.87%  |
| 251-500        | 540       | 24.65%  |
| 501-1000       | 291       | 13.28%  |
| 21-50          | 270       | 12.32%  |
| 1-20           | 223       | 10.18%  |
| 51-100         | 180       | 8.22%   |
| 1001-2000      | 105       | 4.79%   |
| 2001-3000      | 19        | 0.87%   |
| More than 3000 | 10        | 0.46%   |
| Unknown        | 8         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 2022      | 4128   | 97.97%  |
| Works    | 41        | 52     | 1.99%   |
| Malfunc  | 1         | 1      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Phison Electronics             | 506       | 22.7%   |
| Kingston Technology Company    | 419       | 18.8%   |
| Samsung Electronics            | 345       | 15.48%  |
| O2 Micro                       | 226       | 10.14%  |
| Sandisk                        | 145       | 6.51%   |
| Intel                          | 136       | 6.1%    |
| AMD                            | 133       | 5.97%   |
| Silicon Motion                 | 72        | 3.23%   |
| Micron Technology              | 61        | 2.74%   |
| SK hynix                       | 42        | 1.88%   |
| KIOXIA                         | 32        | 1.44%   |
| MAXIO Technology (Hangzhou)    | 22        | 0.99%   |
| Micron/Crucial Technology      | 18        | 0.81%   |
| Biwin Storage Technology       | 13        | 0.58%   |
| Solid State Storage Technology | 9         | 0.4%    |
| Realtek Semiconductor          | 7         | 0.31%   |
| INNOGRIT                       | 7         | 0.31%   |
| ASMedia Technology             | 7         | 0.31%   |
| ADATA Technology               | 7         | 0.31%   |
| Toshiba America Info Systems   | 6         | 0.27%   |
| Marvell Technology Group       | 4         | 0.18%   |
| Apple                          | 3         | 0.13%   |
| Shenzhen Longsys Electronics   | 2         | 0.09%   |
| Seagate Technology             | 2         | 0.09%   |
| Yangtze Memory Technologies    | 1         | 0.04%   |
| Union Memory (Shenzhen)        | 1         | 0.04%   |
| Transcend                      | 1         | 0.04%   |
| Solidigm                       | 1         | 0.04%   |
| Netac Technology               | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                                              | 400       | 17.37%  |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 368       | 15.98%  |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 291       | 12.64%  |
| O2 Micro FORESEE E2M2 NVMe SSD                                                 | 226       | 9.81%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 86        | 3.73%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 86        | 3.73%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                          | 78        | 3.39%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 64        | 2.78%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 55        | 2.39%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                            | 35        | 1.52%   |
| AMD 400 Series Chipset SATA Controller                                         | 32        | 1.39%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 26        | 1.13%   |
| AMD 500 Series Chipset SATA Controller                                         | 25        | 1.09%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 24        | 1.04%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 20        | 0.87%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 18        | 0.78%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 17        | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 0.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 15        | 0.65%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 14        | 0.61%   |
| SK hynix BC511 NVMe SSD                                                        | 11        | 0.48%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 0.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 0.48%   |
| Biwin Storage KingSpec NX series NVMe SSD (DRAM-less)                          | 11        | 0.48%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 10        | 0.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10        | 0.43%   |
| Phison E12 NVMe Controller                                                     | 9         | 0.39%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 9         | 0.39%   |
| AMD 600 Series Chipset SATA Controller                                         | 9         | 0.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 0.35%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8         | 0.35%   |
| AMD 300 Series Chipset SATA Controller                                         | 8         | 0.35%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 7         | 0.3%    |
| Intel SSD 660P Series                                                          | 7         | 0.3%    |
| Intel SATA Controller [RAID mode]                                              | 7         | 0.3%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 7         | 0.3%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 6         | 0.26%   |
| Sandisk WD Black SN770M NVMe SSD (DRAM-less)                                   | 6         | 0.26%   |
| Solid State Storage XA1-311024 NVMe SSD M.2                                    | 5         | 0.22%   |
| Silicon Motion SM2269XT (DRAM-less) NVMe SSD Controller                        | 5         | 0.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 1918      | 87.38%  |
| SATA | 245       | 11.16%  |
| RAID | 27        | 1.23%   |
| IDE  | 4         | 0.18%   |
| SAS  | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 1886      | 92.54%  |
| Intel  | 152       | 7.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Custom APU 0405                     | 1561      | 76.44%  |
| AMD Custom APU 0932                     | 139       | 6.81%   |
| AMD Ryzen 7 6800U with Radeon Graphics  | 17        | 0.83%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 12        | 0.59%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 8         | 0.39%   |
| AMD Ryzen 5 3600 6-Core Processor       | 7         | 0.34%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 6         | 0.29%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 6         | 0.29%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 6         | 0.29%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 5         | 0.24%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 5         | 0.24%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 5         | 0.24%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 4         | 0.2%    |
| AMD Ryzen Z1 Extreme                    | 4         | 0.2%    |
| AMD Ryzen 7 5800X 8-Core Processor      | 4         | 0.2%    |
| AMD Ryzen 7 4800U with Radeon Graphics  | 4         | 0.2%    |
| AMD Ryzen 5 4500U with Radeon Graphics  | 4         | 0.2%    |
| AMD Ryzen 5 2600 Six-Core Processor     | 4         | 0.2%    |
| Intel Core i7-4790K CPU @ 4.00GHz       | 3         | 0.15%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 3         | 0.15%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 0.15%   |
| AMD Ryzen 5 7600X 6-Core Processor      | 3         | 0.15%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 3         | 0.15%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 3         | 0.15%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 3         | 0.15%   |
| AMD Ryzen 5 2600X Six-Core Processor    | 3         | 0.15%   |
| Intel Core i9-9880H CPU @ 2.30GHz       | 2         | 0.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.1%    |
| Intel Core i7-8700 CPU @ 3.20GHz        | 2         | 0.1%    |
| Intel Core i7-6700 CPU @ 3.40GHz        | 2         | 0.1%    |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 0.1%    |
| Intel Core i5-9400F CPU @ 2.90GHz       | 2         | 0.1%    |
| Intel Core i5-7400 CPU @ 3.00GHz        | 2         | 0.1%    |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 0.1%    |
| Intel Core i5-4260U CPU @ 1.40GHz       | 2         | 0.1%    |
| Intel Core i5-2435M CPU @ 2.40GHz       | 2         | 0.1%    |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 0.1%    |
| Intel Core i5-10400F CPU @ 2.90GHz      | 2         | 0.1%    |
| Intel Core i3-9100F CPU @ 3.60GHz       | 2         | 0.1%    |
| Intel Celeron CPU N3060 @ 1.60GHz       | 2         | 0.1%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 1736      | 85.18%  |
| AMD Ryzen 5            | 74        | 3.63%   |
| AMD Ryzen 7            | 61        | 2.99%   |
| Intel Core i7          | 41        | 2.01%   |
| Intel Core i5          | 40        | 1.96%   |
| AMD Ryzen 9            | 19        | 0.93%   |
| Intel Xeon             | 12        | 0.59%   |
| Intel Core i3          | 9         | 0.44%   |
| AMD Ryzen 5 PRO        | 6         | 0.29%   |
| Intel Celeron          | 5         | 0.25%   |
| AMD Ryzen 3            | 5         | 0.25%   |
| Intel Atom             | 4         | 0.2%    |
| AMD FX                 | 3         | 0.15%   |
| AMD Athlon             | 3         | 0.15%   |
| AMD A10                | 3         | 0.15%   |
| Intel Pentium Silver   | 2         | 0.1%    |
| Intel Core i9          | 2         | 0.1%    |
| Intel Core 2 Duo       | 2         | 0.1%    |
| AMD Ryzen Threadripper | 2         | 0.1%    |
| AMD A6                 | 2         | 0.1%    |
| Intel Core m3          | 1         | 0.05%   |
| Intel Core             | 1         | 0.05%   |
| AMD Ryzen 7 PRO        | 1         | 0.05%   |
| AMD Embedded           | 1         | 0.05%   |
| AMD E1                 | 1         | 0.05%   |
| AMD Athlon X4          | 1         | 0.05%   |
| AMD A8                 | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 1786      | 87.59%  |
| 6      | 94        | 4.61%   |
| 8      | 80        | 3.92%   |
| 2      | 46        | 2.26%   |
| 12     | 18        | 0.88%   |
| 16     | 5         | 0.25%   |
| 3      | 3         | 0.15%   |
| 10     | 2         | 0.1%    |
| 32     | 1         | 0.05%   |
| 28     | 1         | 0.05%   |
| 24     | 1         | 0.05%   |
| 14     | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2034      | 99.8%   |
| 2      | 4         | 0.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1975      | 96.81%  |
| 1      | 65        | 3.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2038      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2010      | 98.43%  |
| 0x08900201 | 17        | 0.83%   |
| 0x08900203 | 3         | 0.15%   |
| 0x0a704103 | 2         | 0.1%    |
| 0x0a404102 | 2         | 0.1%    |
| 0x906e9    | 1         | 0.05%   |
| 0x40651    | 1         | 0.05%   |
| 0x1067a    | 1         | 0.05%   |
| 0x0a704104 | 1         | 0.05%   |
| 0x0a50000c | 1         | 0.05%   |
| 0x08901001 | 1         | 0.05%   |
| 0x08701021 | 1         | 0.05%   |
| 0x08600106 | 1         | 0.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 1769      | 86.8%   |
| Zen 3             | 47        | 2.31%   |
| KabyLake          | 39        | 1.91%   |
| Zen 2             | 35        | 1.72%   |
| Zen+              | 28        | 1.37%   |
| Haswell           | 24        | 1.18%   |
| Skylake           | 16        | 0.79%   |
| Zen               | 14        | 0.69%   |
| TigerLake         | 12        | 0.59%   |
| IvyBridge         | 10        | 0.49%   |
| SandyBridge       | 7         | 0.34%   |
| Silvermont        | 6         | 0.29%   |
| Piledriver        | 6         | 0.29%   |
| Excavator         | 6         | 0.29%   |
| CometLake         | 5         | 0.25%   |
| Goldmont plus     | 3         | 0.15%   |
| Broadwell         | 3         | 0.15%   |
| Penryn            | 2         | 0.1%    |
| IceLake           | 2         | 0.1%    |
| Westmere          | 1         | 0.05%   |
| Steamroller       | 1         | 0.05%   |
| Meteorlake Hybrid | 1         | 0.05%   |
| Jaguar            | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 1921      | 91.69%  |
| Intel  | 90        | 4.3%    |
| Nvidia | 84        | 4.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 1508      | 71.47%  |
| AMD Sephiroth [AMD Custom GPU 0405]                                                      | 188       | 8.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 31        | 1.47%   |
| AMD Rembrandt [Radeon 680M]                                                              | 22        | 1.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 1%      |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 17        | 0.81%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 12        | 0.57%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 12        | 0.57%   |
| AMD Lucienne                                                                             | 12        | 0.57%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 11        | 0.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 0.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 0.43%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8         | 0.38%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 8         | 0.38%   |
| AMD Raphael                                                                              | 7         | 0.33%   |
| AMD Phoenix1                                                                             | 7         | 0.33%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 7         | 0.33%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 7         | 0.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 0.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 0.28%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                               | 6         | 0.28%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 5         | 0.24%   |
| Intel HD Graphics 530                                                                    | 5         | 0.24%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 0.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 0.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 0.19%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 4         | 0.19%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.19%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]                    | 4         | 0.19%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                                  | 4         | 0.19%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 0.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3         | 0.14%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.14%   |
| Intel HD Graphics 630                                                                    | 3         | 0.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.14%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                                | 3         | 0.14%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                                          | 3         | 0.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 1886      | 92.41%  |
| 1 x Intel      | 48        | 2.35%   |
| 1 x Nvidia     | 42        | 2.06%   |
| Intel + Nvidia | 27        | 1.32%   |
| AMD + Nvidia   | 16        | 0.78%   |
| 2 x AMD        | 15        | 0.73%   |
| Intel + AMD    | 6         | 0.29%   |
| Other          | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1999      | 98.04%  |
| Proprietary | 39        | 1.91%   |
| Unknown     | 1         | 0.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1978      | 96.82%  |
| 3.01-4.0   | 17        | 0.83%   |
| 0.51-1.0   | 16        | 0.78%   |
| 7.01-8.0   | 13        | 0.64%   |
| 5.01-6.0   | 5         | 0.24%   |
| 2.01-3.0   | 4         | 0.2%    |
| 1.01-2.0   | 3         | 0.15%   |
| 0.01-0.5   | 3         | 0.15%   |
| 16.01-24.0 | 2         | 0.1%    |
| 8.01-16.0  | 2         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Valve                | 1353      | 56.28%  |
| Analogix             | 167       | 6.95%   |
| Samsung Electronics  | 124       | 5.16%   |
| Goldstar             | 84        | 3.49%   |
| Dell                 | 47        | 1.96%   |
| Acer                 | 40        | 1.66%   |
| Hewlett-Packard      | 37        | 1.54%   |
| AOC                  | 35        | 1.46%   |
| BOE                  | 31        | 1.29%   |
| Ancor Communications | 28        | 1.16%   |
| ASUSTek Computer     | 26        | 1.08%   |
| Philips              | 22        | 0.92%   |
| Sony                 | 21        | 0.87%   |
| MSI                  | 18        | 0.75%   |
| Chimei Innolux       | 18        | 0.75%   |
| BenQ                 | 17        | 0.71%   |
| AU Optronics         | 17        | 0.71%   |
| Vizio                | 16        | 0.67%   |
| LG Display           | 14        | 0.58%   |
| Lenovo               | 14        | 0.58%   |
| RTK                  | 13        | 0.54%   |
| Sceptre Tech         | 12        | 0.5%    |
| ViewSonic            | 11        | 0.46%   |
| Apple                | 10        | 0.42%   |
| Hitachi              | 9         | 0.37%   |
| Toshiba              | 8         | 0.33%   |
| Pixio                | 8         | 0.33%   |
| Unknown (XXX)        | 7         | 0.29%   |
| Panasonic            | 7         | 0.29%   |
| Gigabyte Technology  | 7         | 0.29%   |
| Sharp                | 6         | 0.25%   |
| Huion                | 6         | 0.25%   |
| PANDA                | 5         | 0.21%   |
| ONN                  | 5         | 0.21%   |
| MSF                  | 5         | 0.21%   |
| JDI                  | 5         | 0.21%   |
| Insignia             | 5         | 0.21%   |
| GreenWood            | 5         | 0.21%   |
| SGT                  | 4         | 0.17%   |
| MStar                | 4         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 1163      | 47.92%  |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                     | 173       | 7.13%   |
| Analogix ANX7530 U ANX7539 800x1280                                     | 167       | 6.88%   |
| Valve ANX7530 U VLV3004 800x1280 100x160mm 7.4-inch                     | 15        | 0.62%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                  | 11        | 0.45%   |
| RTK FHD RTK2A3B 1920x1080 531x299mm 24.0-inch                           | 8         | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 6         | 0.25%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1210x680mm 54.6-inch          | 5         | 0.21%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 5         | 0.21%   |
| Pixio HDMI WAM2700 2560x1440 597x336mm 27.0-inch                        | 5         | 0.21%   |
| MSF TV080WUM-NL0 MSF1003 1600x2560 113x181mm 8.4-inch                   | 5         | 0.21%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                      | 5         | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 4         | 0.16%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 4         | 0.16%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 4         | 0.16%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                        | 4         | 0.16%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                 | 4         | 0.16%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                      | 4         | 0.16%   |
| Vizio V435-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                     | 3         | 0.12%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                      | 3         | 0.12%   |
| TMX TL070FVXS01-0 TMX0002 1920x1080 160x100mm 7.4-inch                  | 3         | 0.12%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 526x296mm 23.8-inch          | 3         | 0.12%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 3         | 0.12%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch       | 3         | 0.12%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch       | 3         | 0.12%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                      | 3         | 0.12%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 3         | 0.12%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                      | 3         | 0.12%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                     | 3         | 0.12%   |
| Huion Kamvas Pro 13 HAT1330 1920x1080 345x195mm 15.6-inch               | 3         | 0.12%   |
| Goldstar ULTRAGEAR GSM5BB2 1920x1080 527x296mm 23.8-inch                | 3         | 0.12%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 3         | 0.12%   |
| Goldstar 27GN7 GSM5B8D 1920x1080 600x303mm 26.5-inch                    | 3         | 0.12%   |
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                   | 3         | 0.12%   |
| AOC Q32E2WG5B AOC3202 2560x1440 698x393mm 31.5-inch                     | 3         | 0.12%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch        | 3         | 0.12%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 3         | 0.12%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 3         | 0.12%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                       | 3         | 0.12%   |
| Vizio D48-D0 VIZ1004 1920x1080 1070x610mm 48.5-inch                     | 2         | 0.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 800x1280           | 1492      | 63.49%  |
| 1920x1080 (FHD)    | 431       | 18.34%  |
| 3840x2160 (4K)     | 172       | 7.32%   |
| 2560x1440 (QHD)    | 79        | 3.36%   |
| 1366x768 (WXGA)    | 38        | 1.62%   |
| 3440x1440          | 29        | 1.23%   |
| 2560x1080          | 17        | 0.72%   |
| 2560x1600          | 10        | 0.43%   |
| 1600x2560          | 9         | 0.38%   |
| 1360x768           | 7         | 0.3%    |
| 3840x1080          | 6         | 0.26%   |
| 1920x1200 (WUXGA)  | 6         | 0.26%   |
| 1200x1920          | 6         | 0.26%   |
| 1680x1050 (WSXGA+) | 5         | 0.21%   |
| 1600x900 (HD+)     | 5         | 0.21%   |
| 1440x900 (WXGA+)   | 5         | 0.21%   |
| 1280x800 (WXGA)    | 4         | 0.17%   |
| 1280x1024 (SXGA)   | 4         | 0.17%   |
| 2880x1800          | 3         | 0.13%   |
| 1920x540           | 3         | 0.13%   |
| 1024x768 (XGA)     | 3         | 0.13%   |
| Unknown            | 3         | 0.13%   |
| 3840x1600          | 2         | 0.09%   |
| 1920x800           | 2         | 0.09%   |
| 504x315            | 1         | 0.04%   |
| 480x1920           | 1         | 0.04%   |
| 3840x2400          | 1         | 0.04%   |
| 3200x1800 (QHD+)   | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2160x3840          | 1         | 0.04%   |
| 1600x1200          | 1         | 0.04%   |
| 1400x1050          | 1         | 0.04%   |
| 1080x1920          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 7       | 1358      | 56.51%  |
| 3       | 167       | 6.95%   |
| 27      | 138       | 5.74%   |
| 24      | 91        | 3.79%   |
| 23      | 73        | 3.04%   |
| 15      | 73        | 3.04%   |
| 31      | 71        | 2.95%   |
| 21      | 48        | 2%      |
| 84      | 38        | 1.58%   |
| 34      | 37        | 1.54%   |
| 54      | 26        | 1.08%   |
| 72      | 22        | 0.92%   |
| Unknown | 22        | 0.92%   |
| 32      | 20        | 0.83%   |
| 14      | 19        | 0.79%   |
| 13      | 19        | 0.79%   |
| 40      | 18        | 0.75%   |
| 16      | 12        | 0.5%    |
| 65      | 10        | 0.42%   |
| 57      | 10        | 0.42%   |
| 17      | 10        | 0.42%   |
| 8       | 10        | 0.42%   |
| 18      | 8         | 0.33%   |
| 19      | 7         | 0.29%   |
| 11      | 7         | 0.29%   |
| 52      | 6         | 0.25%   |
| 86      | 5         | 0.21%   |
| 48      | 5         | 0.21%   |
| 36      | 5         | 0.21%   |
| 69      | 4         | 0.17%   |
| 55      | 4         | 0.17%   |
| 49      | 4         | 0.17%   |
| 35      | 4         | 0.17%   |
| 22      | 4         | 0.17%   |
| 75      | 3         | 0.12%   |
| 74      | 3         | 0.12%   |
| 64      | 3         | 0.12%   |
| 47      | 3         | 0.12%   |
| 46      | 3         | 0.12%   |
| 43      | 3         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 1-100       | 1495      | 63.37%  |
| 501-600     | 278       | 11.78%  |
| 301-350     | 99        | 4.2%    |
| 601-700     | 91        | 3.86%   |
| 1501-2000   | 75        | 3.18%   |
| 701-800     | 71        | 3.01%   |
| 1001-1500   | 69        | 2.92%   |
| 401-500     | 63        | 2.67%   |
| 801-900     | 27        | 1.14%   |
| 201-300     | 26        | 1.1%    |
| Unknown     | 22        | 0.93%   |
| 351-400     | 21        | 0.89%   |
| 101-200     | 15        | 0.64%   |
| 901-1000    | 7         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 0.67    | 1166      | 49.6%   |
| 16/9    | 688       | 29.26%  |
| 0.62    | 195       | 8.29%   |
| 6/5     | 167       | 7.1%    |
| 21/9    | 45        | 1.91%   |
| 16/10   | 45        | 1.91%   |
| 0.56    | 11        | 0.47%   |
| 32/9    | 8         | 0.34%   |
| 5/4     | 5         | 0.21%   |
| 4/3     | 5         | 0.21%   |
| 0.58    | 5         | 0.21%   |
| 3/2     | 3         | 0.13%   |
| Unknown | 3         | 0.13%   |
| 2.64    | 1         | 0.04%   |
| 2.12    | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |
| 0.63    | 1         | 0.04%   |
| 0.25    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 1-40           | 1509      | 63.7%   |
| 201-250        | 167       | 7.05%   |
| 301-350        | 141       | 5.95%   |
| More than 1000 | 137       | 5.78%   |
| 351-500        | 135       | 5.7%    |
| 101-110        | 79        | 3.33%   |
| 501-1000       | 47        | 1.98%   |
| 251-300        | 36        | 1.52%   |
| 81-90          | 25        | 1.06%   |
| 151-200        | 25        | 1.06%   |
| Unknown        | 22        | 0.93%   |
| 71-80          | 13        | 0.55%   |
| 141-150        | 9         | 0.38%   |
| 121-130        | 8         | 0.34%   |
| 51-60          | 7         | 0.3%    |
| 111-120        | 6         | 0.25%   |
| 41-50          | 1         | 0.04%   |
| 131-140        | 1         | 0.04%   |
| 91-100         | 1         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 161-240       | 1371      | 58.59%  |
| 51-100        | 414       | 17.69%  |
| More than 240 | 183       | 7.82%   |
| 101-120       | 156       | 6.67%   |
| 121-160       | 111       | 4.74%   |
| 1-50          | 83        | 3.55%   |
| Unknown       | 22        | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1550      | 74.3%   |
| 2     | 508       | 24.35%  |
| 3     | 26        | 1.25%   |
| 4     | 2         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1743      | 68.09%  |
| ASIX Electronics                      | 268       | 10.47%  |
| Qualcomm                              | 188       | 7.34%   |
| Intel                                 | 169       | 6.6%    |
| MediaTek                              | 37        | 1.45%   |
| Qualcomm Atheros                      | 22        | 0.86%   |
| Broadcom                              | 20        | 0.78%   |
| Microsoft                             | 18        | 0.7%    |
| TP-Link                               | 16        | 0.63%   |
| DisplayLink                           | 16        | 0.63%   |
| Samsung Electronics                   | 7         | 0.27%   |
| Broadcom Limited                      | 7         | 0.27%   |
| Ralink Technology                     | 6         | 0.23%   |
| ASUSTek Computer                      | 6         | 0.23%   |
| Lenovo                                | 5         | 0.2%    |
| Google                                | 4         | 0.16%   |
| Xiaomi                                | 2         | 0.08%   |
| OPPO Electronics                      | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)         | 2         | 0.08%   |
| Marvell Technology Group              | 2         | 0.08%   |
| Edimax Technology                     | 2         | 0.08%   |
| Dell                                  | 2         | 0.08%   |
| D-Link                                | 2         | 0.08%   |
| Aquantia                              | 2         | 0.08%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.04%   |
| STMicroelectronics                    | 1         | 0.04%   |
| Raspberry Pi                          | 1         | 0.04%   |
| Motorola PCS                          | 1         | 0.04%   |
| Linksys                               | 1         | 0.04%   |
| Huawei Technologies                   | 1         | 0.04%   |
| Davicom Semiconductor                 | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| ArteryTek                             | 1         | 0.04%   |
| Apple                                 | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1509      | 51.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 300       | 10.2%   |
| ASIX AX88179 Gigabit Ethernet                                          | 267       | 9.08%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 188       | 6.39%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 140       | 4.76%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 33        | 1.12%   |
| Intel Wi-Fi 6 AX200                                                    | 32        | 1.09%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 24        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                      | 21        | 0.71%   |
| Intel I211 Gigabit Network Connection                                  | 17        | 0.58%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 16        | 0.54%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 15        | 0.51%   |
| Intel Ethernet Connection (2) I219-V                                   | 14        | 0.48%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 13        | 0.44%   |
| Realtek 802.11ac NIC                                                   | 12        | 0.41%   |
| Intel Ethernet Controller I225-V                                       | 12        | 0.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 11        | 0.37%   |
| Intel Wi-Fi 6 AX201                                                    | 10        | 0.34%   |
| Intel Wireless 7265                                                    | 9         | 0.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 0.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 0.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 7         | 0.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 0.24%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 7         | 0.24%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 0.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 0.2%    |
| Intel Wireless 8260                                                    | 6         | 0.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 5         | 0.17%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 5         | 0.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 5         | 0.17%   |
| Intel Wireless 3165                                                    | 4         | 0.14%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 4         | 0.14%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.14%   |
| Intel Ethernet Connection (2) I218-V                                   | 4         | 0.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 4         | 0.14%   |
| DisplayLink Dell Universal Dock D6000                                  | 4         | 0.14%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 4         | 0.14%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 3         | 0.1%    |
| TP-Link 802.11ac NIC                                                   | 3         | 0.1%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1555      | 77.56%  |
| Qualcomm                              | 188       | 9.38%   |
| Intel                                 | 128       | 6.38%   |
| MediaTek                              | 33        | 1.65%   |
| Qualcomm Atheros                      | 19        | 0.95%   |
| Microsoft                             | 18        | 0.9%    |
| Broadcom                              | 18        | 0.9%    |
| TP-Link                               | 16        | 0.8%    |
| Broadcom Limited                      | 7         | 0.35%   |
| Ralink Technology                     | 6         | 0.3%    |
| ASUSTek Computer                      | 6         | 0.3%    |
| Edimax Technology                     | 2         | 0.1%    |
| Dell                                  | 2         | 0.1%    |
| D-Link                                | 2         | 0.1%    |
| ZyXEL Communications                  | 1         | 0.05%   |
| Marvell Technology Group              | 1         | 0.05%   |
| Linksys                               | 1         | 0.05%   |
| AVM                                   | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1509      | 75%     |
| Qualcomm QCNFA765 Wireless Network Adapter                                                    | 188       | 9.34%   |
| Intel Wi-Fi 6 AX200                                                                           | 32        | 1.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 24        | 1.19%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 16        | 0.8%    |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 15        | 0.75%   |
| Realtek 802.11ac NIC                                                                          | 12        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 11        | 0.55%   |
| Intel Wi-Fi 6 AX201                                                                           | 10        | 0.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 9         | 0.45%   |
| Intel Wireless 7265                                                                           | 9         | 0.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 7         | 0.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 7         | 0.35%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 7         | 0.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 6         | 0.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 6         | 0.3%    |
| Intel Wireless 8260                                                                           | 6         | 0.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 5         | 0.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 5         | 0.25%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 4         | 0.2%    |
| Intel Wireless 3165                                                                           | 4         | 0.2%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                                             | 4         | 0.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 0.2%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 4         | 0.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 3         | 0.15%   |
| TP-Link 802.11ac NIC                                                                          | 3         | 0.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3         | 0.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 0.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3         | 0.15%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 3         | 0.15%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 3         | 0.15%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                            | 3         | 0.15%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 3         | 0.15%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 2         | 0.1%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 2         | 0.1%    |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                                   | 2         | 0.1%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 2         | 0.1%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 2         | 0.1%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.1%    |
| Ralink RT5370 Wireless Adapter                                                                | 2         | 0.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 505       | 55.25%  |
| ASIX Electronics              | 268       | 29.32%  |
| Intel                         | 80        | 8.75%   |
| DisplayLink                   | 16        | 1.75%   |
| Qualcomm Atheros              | 8         | 0.88%   |
| Samsung Electronics           | 6         | 0.66%   |
| Broadcom                      | 6         | 0.66%   |
| MediaTek                      | 5         | 0.55%   |
| Lenovo                        | 5         | 0.55%   |
| Google                        | 3         | 0.33%   |
| Xiaomi                        | 2         | 0.22%   |
| OPPO Electronics              | 2         | 0.22%   |
| OnePlus Technology (Shenzhen) | 2         | 0.22%   |
| Aquantia                      | 2         | 0.22%   |
| Motorola PCS                  | 1         | 0.11%   |
| Marvell Technology Group      | 1         | 0.11%   |
| Huawei Technologies           | 1         | 0.11%   |
| Davicom Semiconductor         | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 300       | 32.57%  |
| ASIX AX88179 Gigabit Ethernet                                                  | 267       | 28.99%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 140       | 15.2%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 33        | 3.58%   |
| Realtek RTL8125 2.5GbE Controller                                              | 21        | 2.28%   |
| Intel I211 Gigabit Network Connection                                          | 17        | 1.85%   |
| Intel Ethernet Connection (2) I219-V                                           | 14        | 1.52%   |
| Intel Ethernet Controller I225-V                                               | 12        | 1.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 0.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 6         | 0.65%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 4         | 0.43%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 0.43%   |
| Intel Ethernet Connection (2) I218-V                                           | 4         | 0.43%   |
| DisplayLink Dell Universal Dock D6000                                          | 4         | 0.43%   |
| Realtek Killer E2600 GbE Controller                                            | 3         | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3         | 0.33%   |
| Lenovo USB-C Dock Ethernet                                                     | 3         | 0.33%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 0.33%   |
| Intel Ethernet Controller I226-V                                               | 3         | 0.33%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.33%   |
| DisplayLink USB 4K Graphic Docking                                             | 3         | 0.33%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 3         | 0.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.22%   |
| OnePlus (Shenzhen) OnePlus                                                     | 2         | 0.22%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.22%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.22%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.22%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.22%   |
| DisplayLink Plugable UD-3900C                                                  | 2         | 0.22%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2         | 0.22%   |
| Realtek USB 10/100/1G/2.5G LAN                                                 | 1         | 0.11%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                    | 1         | 0.11%   |
| Realtek PCIe GbE Family Controller                                             | 1         | 0.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.11%   |
| OPPO OnePlus Nord 4                                                            | 1         | 0.11%   |
| OPPO CPH2477                                                                   | 1         | 0.11%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1963      | 68.95%  |
| Ethernet | 877       | 30.8%   |
| Modem    | 7         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1803      | 83.32%  |
| Ethernet | 359       | 16.59%  |
| Modem    | 2         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1863      | 91.41%  |
| 2     | 158       | 7.75%   |
| 3     | 10        | 0.49%   |
| 0     | 7         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1268      | 60.93%  |
| Yes  | 813       | 39.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 1501      | 85.53%  |
| Intel                           | 121       | 6.89%   |
| Realtek Semiconductor           | 28        | 1.6%    |
| Cambridge Silicon Radio         | 21        | 1.2%    |
| MediaTek                        | 19        | 1.08%   |
| Qualcomm Atheros Communications | 13        | 0.74%   |
| Foxconn / Hon Hai               | 12        | 0.68%   |
| Apple                           | 11        | 0.63%   |
| ASUSTek Computer                | 6         | 0.34%   |
| Broadcom                        | 5         | 0.28%   |
| TP-Link                         | 4         | 0.23%   |
| SINO WEALTH                     | 3         | 0.17%   |
| Realtek                         | 3         | 0.17%   |
| Lite-On Technology              | 2         | 0.11%   |
| Dell                            | 2         | 0.11%   |
| Marvell Semiconductor           | 1         | 0.06%   |
| Integrated System Solution      | 1         | 0.06%   |
| HTC (High Tech Computer)        | 1         | 0.06%   |
| Alps Electric                   | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                                         | 1498      | 85.36%  |
| Intel AX200 Bluetooth                                                | 31        | 1.77%   |
| Realtek Bluetooth Radio                                              | 25        | 1.42%   |
| Intel Bluetooth wireless interface                                   | 24        | 1.37%   |
| Intel AX210 Bluetooth                                                | 22        | 1.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 21        | 1.2%    |
| MediaTek Wireless_Device                                             | 19        | 1.08%   |
| Intel AX201 Bluetooth                                                | 18        | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 11        | 0.63%   |
| Foxconn / Hon Hai Wireless_Device                                    | 8         | 0.46%   |
| Qualcomm Atheros  Bluetooth Device                                   | 6         | 0.34%   |
| Apple Bluetooth Host Controller                                      | 6         | 0.34%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 5         | 0.28%   |
| Intel AX211 Bluetooth                                                | 5         | 0.28%   |
| TP-Link TP-Link Bluetooth USB Adapter                                | 4         | 0.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 4         | 0.23%   |
| Apple Bluetooth USB Host Controller                                  | 4         | 0.23%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 3         | 0.17%   |
| Realtek Bluetooth Radio                                              | 3         | 0.17%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3         | 0.17%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 3         | 0.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3         | 0.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 3         | 0.17%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 2         | 0.11%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 2         | 0.11%   |
| IMC Networks Wireless_Device                                         | 2         | 0.11%   |
| ASUS ASUS USB-BT500                                                  | 2         | 0.11%   |
| SINO WEALTH RK Bluetooth Keyboard                                    | 1         | 0.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.06%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 1         | 0.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 0.06%   |
| Lite-On Bluetooth Radio                                              | 1         | 0.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1         | 0.06%   |
| Intel Bluetooth Device                                               | 1         | 0.06%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1         | 0.06%   |
| IMC Networks Bluetooth Device                                        | 1         | 0.06%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.06%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                      | 1         | 0.06%   |
| Dell Broadcom BCM20702A0 Bluetooth                                   | 1         | 0.06%   |
| Dell BCM20702A0 Bluetooth Module                                     | 1         | 0.06%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| AMD                                          | 1936      | 80.77%  |
| Intel                                        | 147       | 6.13%   |
| Nvidia                                       | 73        | 3.05%   |
| Logitech                                     | 28        | 1.17%   |
| Sony                                         | 18        | 0.75%   |
| C-Media Electronics                          | 18        | 0.75%   |
| Razer USA                                    | 14        | 0.58%   |
| Realtek Semiconductor                        | 13        | 0.54%   |
| Kingston Technology                          | 11        | 0.46%   |
| Generalplus Technology                       | 11        | 0.46%   |
| SteelSeries ApS                              | 8         | 0.33%   |
| Hewlett-Packard                              | 8         | 0.33%   |
| Corsair                                      | 8         | 0.33%   |
| Lenovo                                       | 7         | 0.29%   |
| JMTek                                        | 7         | 0.29%   |
| Nreal                                        | 6         | 0.25%   |
| Focusrite-Novation                           | 6         | 0.25%   |
| Apple                                        | 6         | 0.25%   |
| Plantronics                                  | 5         | 0.21%   |
| Medeli Electronics                           | 4         | 0.17%   |
| GN Netcom                                    | 4         | 0.17%   |
| Valve Software                               | 3         | 0.13%   |
| KTMicro                                      | 3         | 0.13%   |
| Blue Microphones                             | 3         | 0.13%   |
| BEHRINGER International                      | 3         | 0.13%   |
| Texas Instruments                            | 2         | 0.08%   |
| Tenx Technology                              | 2         | 0.08%   |
| Silicon Motion                               | 2         | 0.08%   |
| Micro Star International                     | 2         | 0.08%   |
| Jieli Technology                             | 2         | 0.08%   |
| FiiO Electronics Technology                  | 2         | 0.08%   |
| ASUSTek Computer                             | 2         | 0.08%   |
| Antlion Audio                                | 2         | 0.08%   |
| Unknown                                      | 2         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| Yamaha                                       | 1         | 0.04%   |
| Walmart                                      | 1         | 0.04%   |
| Universal Audio                              | 1         | 0.04%   |
| Teenage Engineering                          | 1         | 0.04%   |
| SHI GANTECH                                  | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1733      | 66.65%  |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 108       | 4.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 53        | 2.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 45        | 1.73%   |
| AMD Starship/Matisse HD Audio Controller                                   | 38        | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 33        | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 25        | 0.96%   |
| AMD Navi 10 HDMI Audio                                                     | 19        | 0.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15        | 0.58%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 0.5%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13        | 0.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 0.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 0.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 0.46%   |
| Realtek Semiconductor USB Audio                                            | 11        | 0.42%   |
| Intel 200 Series PCH HD Audio                                              | 11        | 0.42%   |
| Generalplus Technology USB Audio Device                                    | 11        | 0.42%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 11        | 0.42%   |
| Sony DualSense wireless controller (PS5)                                   | 9         | 0.35%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 0.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 0.35%   |
| Nvidia GP104 High Definition Audio Controller                              | 8         | 0.31%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 0.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 0.27%   |
| JMTek USB PnP Audio Device                                                 | 7         | 0.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 0.27%   |
| Nreal Air                                                                  | 6         | 0.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 0.23%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 0.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 0.23%   |
| C-Media Electronics USB Audio Device                                       | 6         | 0.23%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.23%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.19%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.19%   |
| Logitech G733 Gaming Headset                                               | 5         | 0.19%   |
| Kingston Technology HyperX 7.1 Audio                                       | 5         | 0.19%   |
| Intel Raptor Lake High Definition Audio Controller                         | 5         | 0.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 0.19%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.19%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5         | 0.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 47.5%   |
| Micron Technology   | 12        | 30%     |
| SK hynix            | 4         | 10%     |
| G.Skill             | 2         | 5%      |
| Nanya Technology    | 1         | 2.5%    |
| Kingston            | 1         | 2.5%    |
| Crucial             | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM K3LK7K70BM-BGCP000 4096MB SODIMM 4266MT/s        | 14        | 35%     |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s   | 6         | 15%     |
| Samsung RAM K3LKBKB0BM-MGCP 4GB SODIMM LPDDR5 6400MT/s       | 2         | 5%      |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 2.5%    |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB DIMM LPDDR5 6400MT/s     | 1         | 2.5%    |
| SK hynix RAM H9JCNNNCP3MLCR-N6E 4GB DIMM LPDDR5 6400MT/s     | 1         | 2.5%    |
| SK hynix RAM H58G56AK6BX069 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 2.5%    |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s       | 1         | 2.5%    |
| Samsung RAM K3KL3L30CM-BGCT 4GB Row Of Chips LPDDR5 7500MT/s | 1         | 2.5%    |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR 800MT/s           | 1         | 2.5%    |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s   | 1         | 2.5%    |
| Micron RAM MT62F1G64D4AH-023 WT 4GB SODIMM LPDDR5 4266MT/s   | 1         | 2.5%    |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1         | 2.5%    |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s       | 1         | 2.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 1         | 2.5%    |
| Micron RAM 16ATS2G64HZ-2G6B1 16GB SODIMM DDR4 2400MT/s       | 1         | 2.5%    |
| Kingston RAM 9905417-054.A00G 4GB SODIMM DDR3 1600MT/s       | 1         | 2.5%    |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 1         | 2.5%    |
| G.Skill RAM F4-2666C19-16GRS 16GB SODIMM DDR4 2667MT/s       | 1         | 2.5%    |
| Crucial RAM CT8G4SFS832A.C8FR 8GB SODIMM DDR4 3200MT/s       | 1         | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR5 | 28        | 75.68%  |
| DDR4   | 6         | 16.22%  |
| DDR3   | 2         | 5.41%   |
| SDRAM  | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 86.49%  |
| DIMM         | 3         | 8.11%   |
| Row Of Chips | 2         | 5.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 27        | 72.97%  |
| 8192  | 6         | 16.22%  |
| 16384 | 2         | 5.41%   |
| 2048  | 2         | 5.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 4266  | 15        | 40.54%  |
| 6400  | 11        | 29.73%  |
| 3200  | 4         | 10.81%  |
| 7500  | 2         | 5.41%   |
| 1600  | 2         | 5.41%   |
| 2667  | 1         | 2.7%    |
| 2400  | 1         | 2.7%    |
| 2048  | 1         | 2.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 3         | 30%     |
| Canon                 | 3         | 30%     |
| Samsung Electronics   | 1         | 10%     |
| Lexmark International | 1         | 10%     |
| KODAK                 | 1         | 10%     |
| Dymo-CoStar           | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Samsung M2020 Series              | 1         | 10%     |
| Lexmark International 2600 Series | 1         | 10%     |
| KODAK ESP 5 AiO                   | 1         | 10%     |
| HP LaserJet P1102                 | 1         | 10%     |
| HP LaserJet CP1525nw/x            | 1         | 10%     |
| HP DeskJet 2700 series            | 1         | 10%     |
| Dymo-CoStar LabelWriter 400       | 1         | 10%     |
| Canon PIXMA MG3600 Series         | 1         | 10%     |
| Canon PIXMA MG2500 Series         | 1         | 10%     |
| Canon LiDE 400                    | 1         | 10%     |

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
| Logitech                               | 26        | 15.48%  |
| Microdia                               | 18        | 10.71%  |
| Chicony Electronics                    | 17        | 10.12%  |
| Realtek Semiconductor                  | 12        | 7.14%   |
| IMC Networks                           | 10        | 5.95%   |
| Apple                                  | 10        | 5.95%   |
| Sunplus Innovation Technology          | 7         | 4.17%   |
| Quanta                                 | 7         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.57%   |
| Tripath Technology                     | 5         | 2.98%   |
| Samsung Electronics                    | 5         | 2.98%   |
| Luxvisions Innotech Limited            | 5         | 2.98%   |
| Bison Electronics                      | 4         | 2.38%   |
| Valve Software                         | 3         | 1.79%   |
| Syntek                                 | 3         | 1.79%   |
| Razer USA                              | 3         | 1.79%   |
| Microsoft                              | 3         | 1.79%   |
| Acer                                   | 3         | 1.79%   |
| Tobii Technology AB                    | 2         | 1.19%   |
| SunplusIT                              | 2         | 1.19%   |
| Generalplus Technology                 | 2         | 1.19%   |
| Alpha Imaging Technology               | 2         | 1.19%   |
| Suyin                                  | 1         | 0.6%    |
| Silicon Motion                         | 1         | 0.6%    |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.6%    |
| Ricoh                                  | 1         | 0.6%    |
| Remo Tech                              | 1         | 0.6%    |
| Magic Control Technology               | 1         | 0.6%    |
| MacroSilicon                           | 1         | 0.6%    |
| Lite-On Technology                     | 1         | 0.6%    |
| Jieli Technology                       | 1         | 0.6%    |
| IPEVO                                  | 1         | 0.6%    |
| HTC (High Tech Computer)               | 1         | 0.6%    |
| Google                                 | 1         | 0.6%    |
| AVerMedia Technologies                 | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Logitech HD Pro Webcam C920                                     | 7         | 4.14%   |
| Microdia Webcam Vitade AF                                       | 6         | 3.55%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 6         | 3.55%   |
| Tripath USB Camera                                              | 5         | 2.96%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 5         | 2.96%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 5         | 2.96%   |
| Microdia Integrated_Webcam_HD                                   | 4         | 2.37%   |
| Logitech Webcam C270                                            | 4         | 2.37%   |
| Valve Software 3D Camera                                        | 3         | 1.78%   |
| Syntek Integrated Camera                                        | 3         | 1.78%   |
| Realtek Integrated_Webcam_HD                                    | 3         | 1.78%   |
| Logitech HD Webcam C615                                         | 3         | 1.78%   |
| Chicony Integrated Camera                                       | 3         | 1.78%   |
| Chicony HP TrueVision HD Camera                                 | 3         | 1.78%   |
| Chicony HD User Facing                                          | 3         | 1.78%   |
| Apple FaceTime HD Camera                                        | 3         | 1.78%   |
| Tobii AB EyeChip                                                | 2         | 1.18%   |
| Sunplus Integrated_Webcam_FHD                                   | 2         | 1.18%   |
| Sunplus Asus Webcam                                             | 2         | 1.18%   |
| Realtek NexiGo N660P FHD Webcam                                 | 2         | 1.18%   |
| Microsoft LifeCam HD-3000                                       | 2         | 1.18%   |
| Microdia USB 2.0 Camera                                         | 2         | 1.18%   |
| Microdia Integrated Webcam                                      | 2         | 1.18%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 2         | 1.18%   |
| Logitech HD Webcam C525                                         | 2         | 1.18%   |
| IMC Networks Integrated Camera                                  | 2         | 1.18%   |
| Generalplus GENERAL WEBCAM                                      | 2         | 1.18%   |
| Chicony USB2.0 HD UVC WebCam                                    | 2         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.18%   |
| Bison HD Webcam                                                 | 2         | 1.18%   |
| Apple iSight in LED Cinema Display                              | 2         | 1.18%   |
| Alpha Imaging Integrated_Webcam_8M                              | 2         | 1.18%   |
| Acer Integrated Camera                                          | 2         | 1.18%   |
| Suyin HP Truevision HD                                          | 1         | 0.59%   |
| SunplusIT Depstech webcam                                       | 1         | 0.59%   |
| SunplusIT CODi A05020 Webcam                                    | 1         | 0.59%   |
| Sunplus USB 2.0 Camera                                          | 1         | 0.59%   |
| Sunplus NexiGo N950P 4K Webcam                                  | 1         | 0.59%   |
| Sunplus Dell E5570 integrated webcam                            | 1         | 0.59%   |
| Silicon Motion WebCam SC-13HDL11939N                            | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 33.33%  |
| Synaptics                  | 3         | 25%     |
| Focal-systems.Corp         | 2         | 16.67%  |
| Elan Microelectronics      | 2         | 16.67%  |
| Upek                       | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 3         | 25%     |
| Synaptics UWP WBDI                                     | 2         | 16.67%  |
| Focal-systems.Corp FT9201Fingerprint.Ì              | 2         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 8.33%   |
| Synaptics WBDI                                         | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 8.33%   |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1         | 8.33%   |
| Elan ELAN:Fingerprint                                  | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 55.56%  |
| SCM Microsystems      | 1         | 11.11%  |
| Realtek Semiconductor | 1         | 11.11%  |
| Lenovo                | 1         | 11.11%  |
| Advanced Card Systems | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 2         | 22.22%  |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 11.11%  |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 11.11%  |
| Lenovo Smartcard Keyboard                                                    | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |
| Broadcom 5880                                                                | 1         | 11.11%  |
| Advanced Card Systems ACR39U                                                 | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1907      | 93.43%  |
| 1     | 104       | 5.1%    |
| 2     | 28        | 1.37%   |
| 4     | 1         | 0.05%   |
| 3     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 59        | 35.54%  |
| Multimedia controller    | 35        | 21.08%  |
| Graphics card            | 23        | 13.86%  |
| Fingerprint reader       | 12        | 7.23%   |
| Chipcard                 | 7         | 4.22%   |
| Camera                   | 7         | 4.22%   |
| Unassigned class         | 6         | 3.61%   |
| Sound                    | 4         | 2.41%   |
| Storage/nvme             | 3         | 1.81%   |
| Net/ethernet             | 3         | 1.81%   |
| Card reader              | 2         | 1.2%    |
| Storage/raid             | 1         | 0.6%    |
| Network                  | 1         | 0.6%    |
| Modem                    | 1         | 0.6%    |
| Communication controller | 1         | 0.6%    |
| Bluetooth                | 1         | 0.6%    |

