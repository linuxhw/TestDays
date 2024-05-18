Debian 12 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 12.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_12/Desktop/README.md) and [notebooks](/Dist/Debian_12/Notebook/README.md).

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

Total: 5274

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv6500             | Notebook    | [a9906a0a37](https://linux-hardware.org/?probe=a9906a0a37) | May 09, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [369a002b88](https://linux-hardware.org/?probe=369a002b88) | May 09, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [0a6d9b6f29](https://linux-hardware.org/?probe=0a6d9b6f29) | May 09, 2024 |
| Toshiba       | Satellite C650D             | Notebook    | [9e66892f4b](https://linux-hardware.org/?probe=9e66892f4b) | May 09, 2024 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [fc06be20c3](https://linux-hardware.org/?probe=fc06be20c3) | May 09, 2024 |
| HP            | 8711                        | Mini pc     | [dd252958ea](https://linux-hardware.org/?probe=dd252958ea) | May 09, 2024 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [8256dfc204](https://linux-hardware.org/?probe=8256dfc204) | May 08, 2024 |
| VALE          | Notebook Evolution i5-11... | Notebook    | [55764ee04d](https://linux-hardware.org/?probe=55764ee04d) | May 08, 2024 |
| HP            | EliteBook 735 G5            | Notebook    | [628e01fd2b](https://linux-hardware.org/?probe=628e01fd2b) | May 08, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [3c353c281f](https://linux-hardware.org/?probe=3c353c281f) | May 08, 2024 |
| Sony          | VGN-NS12M_W                 | Notebook    | [e364d75564](https://linux-hardware.org/?probe=e364d75564) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10c139f22b](https://linux-hardware.org/?probe=10c139f22b) | May 08, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [5de84bcb38](https://linux-hardware.org/?probe=5de84bcb38) | May 08, 2024 |
| HP            | 89EB 11                     | Desktop     | [f53a08bd5c](https://linux-hardware.org/?probe=f53a08bd5c) | May 08, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [fcc3b9cc19](https://linux-hardware.org/?probe=fcc3b9cc19) | May 08, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [43cb45f5c4](https://linux-hardware.org/?probe=43cb45f5c4) | May 08, 2024 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [eab2642002](https://linux-hardware.org/?probe=eab2642002) | May 08, 2024 |
| Digma         | Pro Magnus M DN16R9-ADXW... | Notebook    | [beee17622d](https://linux-hardware.org/?probe=beee17622d) | May 08, 2024 |
| Dell          | 0GN6JF A01                  | Desktop     | [b9877feccd](https://linux-hardware.org/?probe=b9877feccd) | May 08, 2024 |
| Dell          | Latitude D830               | Notebook    | [831a2196a3](https://linux-hardware.org/?probe=831a2196a3) | May 07, 2024 |
| OrangePi      | 4 LTS                       | Soc         | [8671fa709f](https://linux-hardware.org/?probe=8671fa709f) | May 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [857bd41fc3](https://linux-hardware.org/?probe=857bd41fc3) | May 07, 2024 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [e04c4654da](https://linux-hardware.org/?probe=e04c4654da) | May 07, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [7a48c1a73b](https://linux-hardware.org/?probe=7a48c1a73b) | May 07, 2024 |
| HP            | 250 G3                      | Notebook    | [5f00c46a92](https://linux-hardware.org/?probe=5f00c46a92) | May 07, 2024 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [94766b9a5d](https://linux-hardware.org/?probe=94766b9a5d) | May 07, 2024 |
| MSI           | B450-A PRO MAX              | Desktop     | [27adbf1266](https://linux-hardware.org/?probe=27adbf1266) | May 07, 2024 |
| GEDU          | YourLand                    | Soc         | [e400f0c9b6](https://linux-hardware.org/?probe=e400f0c9b6) | May 07, 2024 |
| MSI           | GF63 Thin 8SC               | Notebook    | [59abbac521](https://linux-hardware.org/?probe=59abbac521) | May 07, 2024 |
| HP            | G60                         | Notebook    | [c9e5d3832d](https://linux-hardware.org/?probe=c9e5d3832d) | May 07, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [cf6fc980de](https://linux-hardware.org/?probe=cf6fc980de) | May 07, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [9fd55d6b07](https://linux-hardware.org/?probe=9fd55d6b07) | May 07, 2024 |
| HP            | ProLiant DL20 Gen9          | Server      | [d270509755](https://linux-hardware.org/?probe=d270509755) | May 06, 2024 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | Desktop     | [5a5f459292](https://linux-hardware.org/?probe=5a5f459292) | May 06, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [602683adef](https://linux-hardware.org/?probe=602683adef) | May 06, 2024 |
| ASUSTek       | P9X79                       | Desktop     | [dd0d50c3bf](https://linux-hardware.org/?probe=dd0d50c3bf) | May 06, 2024 |
| Intel         | S1200BTL E98681-352         | Server      | [4927e2996f](https://linux-hardware.org/?probe=4927e2996f) | May 06, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [92d80bd754](https://linux-hardware.org/?probe=92d80bd754) | May 06, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cece4d3b5e](https://linux-hardware.org/?probe=cece4d3b5e) | May 06, 2024 |
| ASUSTek       | Z9PR-D12 Series             | Server      | [f922090bb9](https://linux-hardware.org/?probe=f922090bb9) | May 06, 2024 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [390ca96513](https://linux-hardware.org/?probe=390ca96513) | May 06, 2024 |
| ASRock        | H310CM-HDV                  | Desktop     | [1312cfac28](https://linux-hardware.org/?probe=1312cfac28) | May 06, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [98e922adae](https://linux-hardware.org/?probe=98e922adae) | May 06, 2024 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [c3072851e8](https://linux-hardware.org/?probe=c3072851e8) | May 06, 2024 |
| GEDU          | YourLand                    | Soc         | [5bfcf863da](https://linux-hardware.org/?probe=5bfcf863da) | May 06, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [0544131147](https://linux-hardware.org/?probe=0544131147) | May 06, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [cb063ef0b2](https://linux-hardware.org/?probe=cb063ef0b2) | May 06, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [bb7e4b6de6](https://linux-hardware.org/?probe=bb7e4b6de6) | May 06, 2024 |
| Foxconn       | PANGU-B 1A32N3500-600-G     | Desktop     | [e2c56e50f1](https://linux-hardware.org/?probe=e2c56e50f1) | May 05, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1d637d8802](https://linux-hardware.org/?probe=1d637d8802) | May 05, 2024 |
| SZMZ          | X99 DUAL Z8                 | Desktop     | [24f362dbe8](https://linux-hardware.org/?probe=24f362dbe8) | May 05, 2024 |
| Gigabyte      | H610M K DDR4                | Desktop     | [da4e59e69d](https://linux-hardware.org/?probe=da4e59e69d) | May 05, 2024 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [0c39b2e745](https://linux-hardware.org/?probe=0c39b2e745) | May 05, 2024 |
| Lenovo        | ThinkPad T470 20HES6VG00    | Notebook    | [f87983a9a9](https://linux-hardware.org/?probe=f87983a9a9) | May 05, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [63591686d7](https://linux-hardware.org/?probe=63591686d7) | May 05, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [6d828aab44](https://linux-hardware.org/?probe=6d828aab44) | May 05, 2024 |
| MSI           | H110M ECO                   | Desktop     | [2c97e6ca20](https://linux-hardware.org/?probe=2c97e6ca20) | May 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [ce0eb6aa57](https://linux-hardware.org/?probe=ce0eb6aa57) | May 05, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4a08259d5e](https://linux-hardware.org/?probe=4a08259d5e) | May 05, 2024 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [1ee81eb650](https://linux-hardware.org/?probe=1ee81eb650) | May 05, 2024 |
| Dell          | Latitude 7480               | Notebook    | [124ec816c7](https://linux-hardware.org/?probe=124ec816c7) | May 05, 2024 |
| Huanan        | X99-TF                      | Desktop     | [804eb7916a](https://linux-hardware.org/?probe=804eb7916a) | May 05, 2024 |
| Supermicro    | H12SSL-NT                   | Server      | [e156a869a2](https://linux-hardware.org/?probe=e156a869a2) | May 05, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [4afe74277e](https://linux-hardware.org/?probe=4afe74277e) | May 05, 2024 |
| BANGHO        | Suma 1025                   | Tablet      | [e7c37d670f](https://linux-hardware.org/?probe=e7c37d670f) | May 05, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [b3bbc669ec](https://linux-hardware.org/?probe=b3bbc669ec) | May 04, 2024 |
| Lenovo        | ThinkPad T480 20L6SADD00    | Notebook    | [ad52d07a71](https://linux-hardware.org/?probe=ad52d07a71) | May 04, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [616bda869b](https://linux-hardware.org/?probe=616bda869b) | May 04, 2024 |
| HP            | 83DD                        | Mini pc     | [c20e13567a](https://linux-hardware.org/?probe=c20e13567a) | May 04, 2024 |
| HP            | G62                         | Notebook    | [3e3af3a851](https://linux-hardware.org/?probe=3e3af3a851) | May 04, 2024 |
| ASUSTek       | X751MA                      | Notebook    | [ab76aeaddb](https://linux-hardware.org/?probe=ab76aeaddb) | May 04, 2024 |
| Chuwi         | MiniBook X                  | Notebook    | [64c7ac113f](https://linux-hardware.org/?probe=64c7ac113f) | May 04, 2024 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [4fa09a0b8e](https://linux-hardware.org/?probe=4fa09a0b8e) | May 04, 2024 |
| Digiboard     | G41M-S                      | Desktop     | [7b5f122417](https://linux-hardware.org/?probe=7b5f122417) | May 04, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [221d8e684d](https://linux-hardware.org/?probe=221d8e684d) | May 04, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [37ed88bcea](https://linux-hardware.org/?probe=37ed88bcea) | May 03, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [b8f0474451](https://linux-hardware.org/?probe=b8f0474451) | May 03, 2024 |
| Acer          | Veriton N4640G              | Desktop     | [ce50a47462](https://linux-hardware.org/?probe=ce50a47462) | May 03, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [4eb1ae6ad4](https://linux-hardware.org/?probe=4eb1ae6ad4) | May 03, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [a7dfd908c9](https://linux-hardware.org/?probe=a7dfd908c9) | May 03, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [3b15ff3048](https://linux-hardware.org/?probe=3b15ff3048) | May 03, 2024 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [67f5f847c9](https://linux-hardware.org/?probe=67f5f847c9) | May 03, 2024 |
| Dell          | 0H21J3 A10                  | Server      | [125e045945](https://linux-hardware.org/?probe=125e045945) | May 03, 2024 |
| Lenovo        | G500s 20245                 | Notebook    | [54adaed795](https://linux-hardware.org/?probe=54adaed795) | May 03, 2024 |
| Itautec       | Infoway w7730               | Notebook    | [65fba1a766](https://linux-hardware.org/?probe=65fba1a766) | May 03, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [3f7c3168f2](https://linux-hardware.org/?probe=3f7c3168f2) | May 02, 2024 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [1b1d2cd8c6](https://linux-hardware.org/?probe=1b1d2cd8c6) | May 02, 2024 |
| Intel         | powered classmate PC        | Notebook    | [2f4933a503](https://linux-hardware.org/?probe=2f4933a503) | May 02, 2024 |
| Acer          | Veriton N4640G              | Desktop     | [d18d5f8d9d](https://linux-hardware.org/?probe=d18d5f8d9d) | May 02, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [00a9e3fe9b](https://linux-hardware.org/?probe=00a9e3fe9b) | May 02, 2024 |
| Google        | Phaser                      | Notebook    | [feb45bf2a2](https://linux-hardware.org/?probe=feb45bf2a2) | May 02, 2024 |
| Dell          | 02C2CP A03                  | Server      | [533b90f443](https://linux-hardware.org/?probe=533b90f443) | May 02, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [d2c6cfb3bd](https://linux-hardware.org/?probe=d2c6cfb3bd) | May 02, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3380a14ae9](https://linux-hardware.org/?probe=3380a14ae9) | May 02, 2024 |
| Lenovo        | ThinkPad T480 20L6SADD00    | Notebook    | [b9fcd48ed1](https://linux-hardware.org/?probe=b9fcd48ed1) | May 02, 2024 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [a76ca4fae1](https://linux-hardware.org/?probe=a76ca4fae1) | May 02, 2024 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [73e7f9d576](https://linux-hardware.org/?probe=73e7f9d576) | May 02, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [1307008025](https://linux-hardware.org/?probe=1307008025) | May 01, 2024 |
| MSI           | MS-7204                     | Desktop     | [5d3f1b6a58](https://linux-hardware.org/?probe=5d3f1b6a58) | May 01, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [c3b30e066b](https://linux-hardware.org/?probe=c3b30e066b) | May 01, 2024 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [edceb0e782](https://linux-hardware.org/?probe=edceb0e782) | May 01, 2024 |
| IGEL Techn... | M350C                       | Notebook    | [c63a48250c](https://linux-hardware.org/?probe=c63a48250c) | May 01, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [f3d12216e7](https://linux-hardware.org/?probe=f3d12216e7) | May 01, 2024 |
| HUAWEI        | BC11HGSC0 V100R003          | Server      | [4ba7497e3e](https://linux-hardware.org/?probe=4ba7497e3e) | May 01, 2024 |
| Acer          | Extensa 4210                | Notebook    | [1b24527bdf](https://linux-hardware.org/?probe=1b24527bdf) | May 01, 2024 |
| HP            | 8906 SMVB                   | Desktop     | [6c9a72d2cb](https://linux-hardware.org/?probe=6c9a72d2cb) | May 01, 2024 |
| Pegatron      | 2A99                        | Desktop     | [fcd74433b3](https://linux-hardware.org/?probe=fcd74433b3) | Apr 30, 2024 |
| Biostar       | G41D3B                      | Desktop     | [748e0749c5](https://linux-hardware.org/?probe=748e0749c5) | Apr 30, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [164f516c10](https://linux-hardware.org/?probe=164f516c10) | Apr 30, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [446ba2ecc6](https://linux-hardware.org/?probe=446ba2ecc6) | Apr 30, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [38975e46ec](https://linux-hardware.org/?probe=38975e46ec) | Apr 30, 2024 |
| ASRock        | N68-S                       | Desktop     | [a099ad6775](https://linux-hardware.org/?probe=a099ad6775) | Apr 30, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [4c7535b1ac](https://linux-hardware.org/?probe=4c7535b1ac) | Apr 30, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [859396f855](https://linux-hardware.org/?probe=859396f855) | Apr 30, 2024 |
| Gigabyte      | H81M-S2V                    | Desktop     | [11f391fabc](https://linux-hardware.org/?probe=11f391fabc) | Apr 30, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [c0fa280156](https://linux-hardware.org/?probe=c0fa280156) | Apr 30, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1QU0... | Notebook    | [5429ec2fa3](https://linux-hardware.org/?probe=5429ec2fa3) | Apr 30, 2024 |
| Digma         | CITI E301 ES3008EW          | Notebook    | [91b8be60a0](https://linux-hardware.org/?probe=91b8be60a0) | Apr 30, 2024 |
| Digma         | CITI E301 ES3008EW          | Notebook    | [586069736d](https://linux-hardware.org/?probe=586069736d) | Apr 30, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1QU0... | Notebook    | [60d21b08c6](https://linux-hardware.org/?probe=60d21b08c6) | Apr 30, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8a21aa2463](https://linux-hardware.org/?probe=8a21aa2463) | Apr 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [56f9ef0976](https://linux-hardware.org/?probe=56f9ef0976) | Apr 30, 2024 |
| ASRock        | B560M Pro4                  | Desktop     | [510e90dcb8](https://linux-hardware.org/?probe=510e90dcb8) | Apr 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [57a68c0dec](https://linux-hardware.org/?probe=57a68c0dec) | Apr 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4939bdb260](https://linux-hardware.org/?probe=4939bdb260) | Apr 30, 2024 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [56e690c86e](https://linux-hardware.org/?probe=56e690c86e) | Apr 30, 2024 |
| PCWare        | IPMH310G PRO                | Desktop     | [f38e07cde2](https://linux-hardware.org/?probe=f38e07cde2) | Apr 30, 2024 |
| BCM Advanc... | MX87QD                      | Desktop     | [5f5deeae12](https://linux-hardware.org/?probe=5f5deeae12) | Apr 30, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [e0cb14de08](https://linux-hardware.org/?probe=e0cb14de08) | Apr 30, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [aedd483ccc](https://linux-hardware.org/?probe=aedd483ccc) | Apr 29, 2024 |
| Dell          | Inspiron 3442               | Notebook    | [05db1722f8](https://linux-hardware.org/?probe=05db1722f8) | Apr 29, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8d9161d10f](https://linux-hardware.org/?probe=8d9161d10f) | Apr 29, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [62b6fb2419](https://linux-hardware.org/?probe=62b6fb2419) | Apr 29, 2024 |
| BESSTAR Te... | HM80                        | Desktop     | [7e9ff18aba](https://linux-hardware.org/?probe=7e9ff18aba) | Apr 29, 2024 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [bf5c2a7930](https://linux-hardware.org/?probe=bf5c2a7930) | Apr 29, 2024 |
| ASUSTek       | E203NA                      | Notebook    | [2caea60de4](https://linux-hardware.org/?probe=2caea60de4) | Apr 29, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3f5beab74c](https://linux-hardware.org/?probe=3f5beab74c) | Apr 28, 2024 |
| HP            | ProBook 4535s               | Notebook    | [34910d04e7](https://linux-hardware.org/?probe=34910d04e7) | Apr 28, 2024 |
| HP            | Notebook                    | Notebook    | [b45aa2251b](https://linux-hardware.org/?probe=b45aa2251b) | Apr 28, 2024 |
| HP            | Notebook                    | Notebook    | [9f5ae93269](https://linux-hardware.org/?probe=9f5ae93269) | Apr 28, 2024 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [278dad8d5a](https://linux-hardware.org/?probe=278dad8d5a) | Apr 28, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a802b0c72d](https://linux-hardware.org/?probe=a802b0c72d) | Apr 28, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [c31443d648](https://linux-hardware.org/?probe=c31443d648) | Apr 28, 2024 |
| MSI           | GF63 Thin 8SC               | Notebook    | [b375d81404](https://linux-hardware.org/?probe=b375d81404) | Apr 28, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9f0eda367d](https://linux-hardware.org/?probe=9f0eda367d) | Apr 28, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [06b56e10dc](https://linux-hardware.org/?probe=06b56e10dc) | Apr 28, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [3e16c2d8c6](https://linux-hardware.org/?probe=3e16c2d8c6) | Apr 28, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c35533dfbf](https://linux-hardware.org/?probe=c35533dfbf) | Apr 28, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a0fcbd666f](https://linux-hardware.org/?probe=a0fcbd666f) | Apr 28, 2024 |
| Acer          | Aspire ES1-431              | Notebook    | [ff9ee70831](https://linux-hardware.org/?probe=ff9ee70831) | Apr 28, 2024 |
| HP            | 15                          | Notebook    | [0e0d6ab57a](https://linux-hardware.org/?probe=0e0d6ab57a) | Apr 28, 2024 |
| HP            | 15                          | Notebook    | [d329164137](https://linux-hardware.org/?probe=d329164137) | Apr 28, 2024 |
| ASRock        | B760M-HDV/M.2               | Desktop     | [01633e2e6d](https://linux-hardware.org/?probe=01633e2e6d) | Apr 28, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [31af2ca036](https://linux-hardware.org/?probe=31af2ca036) | Apr 28, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [7918dabd8f](https://linux-hardware.org/?probe=7918dabd8f) | Apr 28, 2024 |
| AZW           | U59                         | Desktop     | [d310713234](https://linux-hardware.org/?probe=d310713234) | Apr 28, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [0902f17c99](https://linux-hardware.org/?probe=0902f17c99) | Apr 27, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [91449c8a93](https://linux-hardware.org/?probe=91449c8a93) | Apr 27, 2024 |
| ASRock        | B760M-HDV/M.2               | Desktop     | [324ac4ff48](https://linux-hardware.org/?probe=324ac4ff48) | Apr 27, 2024 |
| Lenovo        | ThinkPad X390 20Q1S62G00    | Notebook    | [e7319a730f](https://linux-hardware.org/?probe=e7319a730f) | Apr 27, 2024 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [bbd6e87bc4](https://linux-hardware.org/?probe=bbd6e87bc4) | Apr 27, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [caf8879e78](https://linux-hardware.org/?probe=caf8879e78) | Apr 27, 2024 |
| Fujitsu       | D3167-A1 S26361-D3167-A1    | Desktop     | [5182ad8bd7](https://linux-hardware.org/?probe=5182ad8bd7) | Apr 27, 2024 |
| Dixonsxp      | Crestline & ICH8M Chipse... | Notebook    | [a9e235a9db](https://linux-hardware.org/?probe=a9e235a9db) | Apr 27, 2024 |
| HP            | ZBook 14                    | Notebook    | [42c92ec19d](https://linux-hardware.org/?probe=42c92ec19d) | Apr 27, 2024 |
| Acer          | TravelMate P215-53          | Notebook    | [00d58edb3b](https://linux-hardware.org/?probe=00d58edb3b) | Apr 27, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [7d60545173](https://linux-hardware.org/?probe=7d60545173) | Apr 27, 2024 |
| HP            | EliteBook 735 G5            | Notebook    | [9e1b0b4220](https://linux-hardware.org/?probe=9e1b0b4220) | Apr 27, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b4d4155591](https://linux-hardware.org/?probe=b4d4155591) | Apr 27, 2024 |
| Samsung       | 550XDA                      | Notebook    | [de2396f0a2](https://linux-hardware.org/?probe=de2396f0a2) | Apr 27, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [723af200e1](https://linux-hardware.org/?probe=723af200e1) | Apr 27, 2024 |
| Lenovo        | Flex 7 14IRU8 82Y2          | Convertible | [93ed75aa98](https://linux-hardware.org/?probe=93ed75aa98) | Apr 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [b52a110875](https://linux-hardware.org/?probe=b52a110875) | Apr 27, 2024 |
| Dell          | 02C2CP A06                  | Server      | [f852aff4f6](https://linux-hardware.org/?probe=f852aff4f6) | Apr 27, 2024 |
| Dell          | Latitude E6400              | Notebook    | [fe74dc08cd](https://linux-hardware.org/?probe=fe74dc08cd) | Apr 27, 2024 |
| Samsung       | 730QDA                      | Convertible | [43fdcef4be](https://linux-hardware.org/?probe=43fdcef4be) | Apr 27, 2024 |
| Lenovo        | ThinkPad T460s 20FAS21A0... | Notebook    | [f8c5a44d3d](https://linux-hardware.org/?probe=f8c5a44d3d) | Apr 27, 2024 |
| Lenovo        | ThinkPad P52 20MAS04M23     | Notebook    | [3cc3f4dcc1](https://linux-hardware.org/?probe=3cc3f4dcc1) | Apr 27, 2024 |
| DEXP          | ZRA6101                     | All in one  | [3b8874497a](https://linux-hardware.org/?probe=3b8874497a) | Apr 27, 2024 |
| HP            | ZBook 14                    | Notebook    | [d6e2400956](https://linux-hardware.org/?probe=d6e2400956) | Apr 26, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a5cb6f40d5](https://linux-hardware.org/?probe=a5cb6f40d5) | Apr 26, 2024 |
| ASUSTek       | UX32VD                      | Notebook    | [abf6c0658a](https://linux-hardware.org/?probe=abf6c0658a) | Apr 26, 2024 |
| HP            | Pavilion 15                 | Notebook    | [ef9f89946b](https://linux-hardware.org/?probe=ef9f89946b) | Apr 26, 2024 |
| ASUSTek       | P5QL-CM                     | Desktop     | [28a4852048](https://linux-hardware.org/?probe=28a4852048) | Apr 26, 2024 |
| ASUSTek       | P5QL-CM                     | Desktop     | [bf1873c20d](https://linux-hardware.org/?probe=bf1873c20d) | Apr 26, 2024 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [6caa28f904](https://linux-hardware.org/?probe=6caa28f904) | Apr 26, 2024 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [517a020485](https://linux-hardware.org/?probe=517a020485) | Apr 26, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [083c88fe82](https://linux-hardware.org/?probe=083c88fe82) | Apr 26, 2024 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [714f84cadb](https://linux-hardware.org/?probe=714f84cadb) | Apr 26, 2024 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [e21d70e37d](https://linux-hardware.org/?probe=e21d70e37d) | Apr 26, 2024 |
| Gigabyte      | P75-D3                      | Desktop     | [496e1605e9](https://linux-hardware.org/?probe=496e1605e9) | Apr 26, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d25ca314d4](https://linux-hardware.org/?probe=d25ca314d4) | Apr 26, 2024 |
| Lenovo        | ThinkPad T570 20HAS03W00    | Notebook    | [6d4f2cc6ca](https://linux-hardware.org/?probe=6d4f2cc6ca) | Apr 26, 2024 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [d378d3e2a8](https://linux-hardware.org/?probe=d378d3e2a8) | Apr 26, 2024 |
| ASRock        | G31M-GS                     | Desktop     | [5a76ec66ed](https://linux-hardware.org/?probe=5a76ec66ed) | Apr 26, 2024 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [ca351b002d](https://linux-hardware.org/?probe=ca351b002d) | Apr 26, 2024 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [8992ae65ab](https://linux-hardware.org/?probe=8992ae65ab) | Apr 26, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [b5d2df5a85](https://linux-hardware.org/?probe=b5d2df5a85) | Apr 26, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [bf18be8805](https://linux-hardware.org/?probe=bf18be8805) | Apr 26, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [773cffce7f](https://linux-hardware.org/?probe=773cffce7f) | Apr 26, 2024 |
| MobileDema... | Cherry Trail CR             | Notebook    | [45127b07b2](https://linux-hardware.org/?probe=45127b07b2) | Apr 26, 2024 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [3daa76cdd8](https://linux-hardware.org/?probe=3daa76cdd8) | Apr 26, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [a2f7e0ec28](https://linux-hardware.org/?probe=a2f7e0ec28) | Apr 26, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [79f0b7e272](https://linux-hardware.org/?probe=79f0b7e272) | Apr 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [10a878e186](https://linux-hardware.org/?probe=10a878e186) | Apr 25, 2024 |
| ForeScout ... | 04N3DF A09                  | Server      | [d86100a3af](https://linux-hardware.org/?probe=d86100a3af) | Apr 25, 2024 |
| Acer          | Aspire V3-551G              | Notebook    | [86b4773429](https://linux-hardware.org/?probe=86b4773429) | Apr 25, 2024 |
| Lenovo        | ThinkPad L420 7829A71       | Notebook    | [11c76a20a0](https://linux-hardware.org/?probe=11c76a20a0) | Apr 25, 2024 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [e6fa07d931](https://linux-hardware.org/?probe=e6fa07d931) | Apr 25, 2024 |
| ECS           | H61H2-M13                   | Desktop     | [677042f9b9](https://linux-hardware.org/?probe=677042f9b9) | Apr 25, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [353dfb074d](https://linux-hardware.org/?probe=353dfb074d) | Apr 25, 2024 |
| ASUSTek       | F2A85-M                     | Desktop     | [94e6f654e9](https://linux-hardware.org/?probe=94e6f654e9) | Apr 25, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7f54c26bc1](https://linux-hardware.org/?probe=7f54c26bc1) | Apr 25, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e7a56f20f9](https://linux-hardware.org/?probe=e7a56f20f9) | Apr 25, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [8ed8b87e84](https://linux-hardware.org/?probe=8ed8b87e84) | Apr 25, 2024 |
| Unknown       | 04N3DF A05                  | Server      | [e9a95e8e1a](https://linux-hardware.org/?probe=e9a95e8e1a) | Apr 25, 2024 |
| Inventec      | DQ Class A02                | Desktop     | [5edaa0ed95](https://linux-hardware.org/?probe=5edaa0ed95) | Apr 24, 2024 |
| ASUSTek       | P5N-MX                      | Desktop     | [8c9cb42e87](https://linux-hardware.org/?probe=8c9cb42e87) | Apr 24, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [45b756650e](https://linux-hardware.org/?probe=45b756650e) | Apr 24, 2024 |
| Dell          | Latitude 9440 2-in-1        | Convertible | [52e163ab73](https://linux-hardware.org/?probe=52e163ab73) | Apr 24, 2024 |
| Dell          | Latitude 5420               | Notebook    | [604846386f](https://linux-hardware.org/?probe=604846386f) | Apr 24, 2024 |
| Lenovo        | ThinkPad T470s 20HGS6Y80... | Notebook    | [96569e2ad7](https://linux-hardware.org/?probe=96569e2ad7) | Apr 24, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1086d184b6](https://linux-hardware.org/?probe=1086d184b6) | Apr 24, 2024 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [42a4906c7d](https://linux-hardware.org/?probe=42a4906c7d) | Apr 24, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [bc030e73d5](https://linux-hardware.org/?probe=bc030e73d5) | Apr 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fefcca9318](https://linux-hardware.org/?probe=fefcca9318) | Apr 24, 2024 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [d6c9b24678](https://linux-hardware.org/?probe=d6c9b24678) | Apr 24, 2024 |
| Lenovo        | G50-80 80L0                 | Notebook    | [882a343fea](https://linux-hardware.org/?probe=882a343fea) | Apr 23, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [f5d49e0d32](https://linux-hardware.org/?probe=f5d49e0d32) | Apr 23, 2024 |
| Acer          | Nitro AN16-41               | Notebook    | [4cfb726ac6](https://linux-hardware.org/?probe=4cfb726ac6) | Apr 23, 2024 |
| Shenzhen M... | RPBNB                       | Desktop     | [37eb2f2a94](https://linux-hardware.org/?probe=37eb2f2a94) | Apr 23, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [efcac49277](https://linux-hardware.org/?probe=efcac49277) | Apr 23, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [ae4c858581](https://linux-hardware.org/?probe=ae4c858581) | Apr 23, 2024 |
| Lenovo        | XiaoXinPro 16 AHP9 83D5     | Notebook    | [8ee1de3473](https://linux-hardware.org/?probe=8ee1de3473) | Apr 23, 2024 |
| Dell          | Latitude 7490               | Notebook    | [13f0f49982](https://linux-hardware.org/?probe=13f0f49982) | Apr 23, 2024 |
| Dell          | Latitude 7490               | Notebook    | [1f22d48915](https://linux-hardware.org/?probe=1f22d48915) | Apr 23, 2024 |
| HP            | 895C                        | Desktop     | [08b147d945](https://linux-hardware.org/?probe=08b147d945) | Apr 23, 2024 |
| Dell          | Latitude 5420               | Notebook    | [f3182ce0c2](https://linux-hardware.org/?probe=f3182ce0c2) | Apr 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [044858db54](https://linux-hardware.org/?probe=044858db54) | Apr 23, 2024 |
| ASUSTek       | P5N-MX                      | Desktop     | [8bb509b6d7](https://linux-hardware.org/?probe=8bb509b6d7) | Apr 23, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9db655d8b6](https://linux-hardware.org/?probe=9db655d8b6) | Apr 23, 2024 |
| ADLINK Tec... | LEC-EL A1                   | Desktop     | [72b115951b](https://linux-hardware.org/?probe=72b115951b) | Apr 22, 2024 |
| Gigabyte      | B650I AORUS ULTRA se2       | Desktop     | [0fcc20ba38](https://linux-hardware.org/?probe=0fcc20ba38) | Apr 22, 2024 |
| Acer          | Swift SF314-42              | Notebook    | [c5ab9f2681](https://linux-hardware.org/?probe=c5ab9f2681) | Apr 22, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [02420cbf38](https://linux-hardware.org/?probe=02420cbf38) | Apr 22, 2024 |
| MSI           | Prestige 13Evo A13M         | Notebook    | [9103acf647](https://linux-hardware.org/?probe=9103acf647) | Apr 22, 2024 |
| Xunlong       | Orange Pi Zero              | Soc         | [af1ac19040](https://linux-hardware.org/?probe=af1ac19040) | Apr 22, 2024 |
| HP            | ZBook Studio G3             | Notebook    | [c78e54109c](https://linux-hardware.org/?probe=c78e54109c) | Apr 22, 2024 |
| HP            | ProLiant DL385p Gen8        | Server      | [2f9535b576](https://linux-hardware.org/?probe=2f9535b576) | Apr 22, 2024 |
| HP            | ProLiant DL360e Gen8        | Server      | [aee06f5ae4](https://linux-hardware.org/?probe=aee06f5ae4) | Apr 22, 2024 |
| HP            | 8835                        | Desktop     | [63962138e6](https://linux-hardware.org/?probe=63962138e6) | Apr 22, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [55814d7e58](https://linux-hardware.org/?probe=55814d7e58) | Apr 22, 2024 |
| ASUSTek       | X441SA                      | Notebook    | [4ebc6f3907](https://linux-hardware.org/?probe=4ebc6f3907) | Apr 22, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2a4799164d](https://linux-hardware.org/?probe=2a4799164d) | Apr 22, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [0a9ede9e09](https://linux-hardware.org/?probe=0a9ede9e09) | Apr 22, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [4a46b6f322](https://linux-hardware.org/?probe=4a46b6f322) | Apr 22, 2024 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [546846d640](https://linux-hardware.org/?probe=546846d640) | Apr 22, 2024 |
| Itautec       | Infoway w7730               | Notebook    | [904234ad57](https://linux-hardware.org/?probe=904234ad57) | Apr 22, 2024 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [a290c311d1](https://linux-hardware.org/?probe=a290c311d1) | Apr 22, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [1c066ce5e2](https://linux-hardware.org/?probe=1c066ce5e2) | Apr 21, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [0b6a8b8487](https://linux-hardware.org/?probe=0b6a8b8487) | Apr 21, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6389731461](https://linux-hardware.org/?probe=6389731461) | Apr 21, 2024 |
| Lenovo        | ThinkPad T470 20HES6VG00    | Notebook    | [b122ffbcd4](https://linux-hardware.org/?probe=b122ffbcd4) | Apr 21, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [0231457347](https://linux-hardware.org/?probe=0231457347) | Apr 21, 2024 |
| MSI           | Thin GF63 12VE              | Notebook    | [797980dc42](https://linux-hardware.org/?probe=797980dc42) | Apr 21, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [482d5d1221](https://linux-hardware.org/?probe=482d5d1221) | Apr 21, 2024 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [a206f7f2d5](https://linux-hardware.org/?probe=a206f7f2d5) | Apr 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [a1cc621a2f](https://linux-hardware.org/?probe=a1cc621a2f) | Apr 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [5ff81fe9b8](https://linux-hardware.org/?probe=5ff81fe9b8) | Apr 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1fe127b27d](https://linux-hardware.org/?probe=1fe127b27d) | Apr 21, 2024 |
| Huanan        | X99-TF V3.0 JX              | Desktop     | [bb51640f19](https://linux-hardware.org/?probe=bb51640f19) | Apr 21, 2024 |
| LNV           | M14LC2-256                  | Notebook    | [582ccc43d4](https://linux-hardware.org/?probe=582ccc43d4) | Apr 21, 2024 |
| Lenovo        | G50-45 80E3                 | Notebook    | [61882ea818](https://linux-hardware.org/?probe=61882ea818) | Apr 21, 2024 |
| ASUSTek       | P9X79                       | Desktop     | [f5f0955b10](https://linux-hardware.org/?probe=f5f0955b10) | Apr 20, 2024 |
| Lenovo        | G50-45 80E3                 | Notebook    | [2ee14c9eff](https://linux-hardware.org/?probe=2ee14c9eff) | Apr 20, 2024 |
| Supermicro    | H12SSL-CT                   | Server      | [165f049bbe](https://linux-hardware.org/?probe=165f049bbe) | Apr 20, 2024 |
| HP            | 82A2                        | Desktop     | [1eeebb4829](https://linux-hardware.org/?probe=1eeebb4829) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS II    | Desktop     | [9666b7dd0c](https://linux-hardware.org/?probe=9666b7dd0c) | Apr 20, 2024 |
| MSI           | MS-7235                     | Desktop     | [67ea957848](https://linux-hardware.org/?probe=67ea957848) | Apr 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [82a3685099](https://linux-hardware.org/?probe=82a3685099) | Apr 20, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [e7c1f32086](https://linux-hardware.org/?probe=e7c1f32086) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [a1f1d3f4a0](https://linux-hardware.org/?probe=a1f1d3f4a0) | Apr 20, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [22ba7e810f](https://linux-hardware.org/?probe=22ba7e810f) | Apr 20, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [0df86cd712](https://linux-hardware.org/?probe=0df86cd712) | Apr 20, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [88986725e7](https://linux-hardware.org/?probe=88986725e7) | Apr 20, 2024 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [f0e2928850](https://linux-hardware.org/?probe=f0e2928850) | Apr 20, 2024 |
| Lenovo        | ThinkPad L570 20J80013US    | Notebook    | [0f79928572](https://linux-hardware.org/?probe=0f79928572) | Apr 20, 2024 |
| Toshiba       | Satellite C870-192          | Notebook    | [563eab96cf](https://linux-hardware.org/?probe=563eab96cf) | Apr 20, 2024 |
| Dell          | 0R790T A00                  | Desktop     | [82b384c367](https://linux-hardware.org/?probe=82b384c367) | Apr 20, 2024 |
| Lenovo        | ThinkPad T480s 20L8S6BW1... | Notebook    | [778bb54578](https://linux-hardware.org/?probe=778bb54578) | Apr 20, 2024 |
| Lenovo        | ThinkPad L420 7829A71       | Notebook    | [06f7d10927](https://linux-hardware.org/?probe=06f7d10927) | Apr 20, 2024 |
| Gigabyte      | Z390 UD                     | Desktop     | [2f4860118a](https://linux-hardware.org/?probe=2f4860118a) | Apr 19, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [3022280b20](https://linux-hardware.org/?probe=3022280b20) | Apr 19, 2024 |
| HP            | ZBook 15 G5                 | Notebook    | [e6dc5df04b](https://linux-hardware.org/?probe=e6dc5df04b) | Apr 19, 2024 |
| Dell          | Latitude E6420              | Notebook    | [88731c458f](https://linux-hardware.org/?probe=88731c458f) | Apr 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [018abcebe4](https://linux-hardware.org/?probe=018abcebe4) | Apr 19, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [b1b415511d](https://linux-hardware.org/?probe=b1b415511d) | Apr 19, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [40a4bdb47b](https://linux-hardware.org/?probe=40a4bdb47b) | Apr 19, 2024 |
| Dell          | Inspiron 910                | Notebook    | [150577a3da](https://linux-hardware.org/?probe=150577a3da) | Apr 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e65c84d822](https://linux-hardware.org/?probe=e65c84d822) | Apr 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [d1cf256cf2](https://linux-hardware.org/?probe=d1cf256cf2) | Apr 19, 2024 |
| Dell          | 0D9JG3 A00                  | Desktop     | [b5c9c5d6b0](https://linux-hardware.org/?probe=b5c9c5d6b0) | Apr 19, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [8d3a6c05f9](https://linux-hardware.org/?probe=8d3a6c05f9) | Apr 19, 2024 |
| AZW           | U59                         | Desktop     | [3923393266](https://linux-hardware.org/?probe=3923393266) | Apr 19, 2024 |
| ASUSTek       | H110M-D                     | Desktop     | [994b125f04](https://linux-hardware.org/?probe=994b125f04) | Apr 19, 2024 |
| Dell          | Precision 3560              | Notebook    | [2f847b171f](https://linux-hardware.org/?probe=2f847b171f) | Apr 18, 2024 |
| MSI           | B450-A PRO MAX              | Desktop     | [1babcb92fd](https://linux-hardware.org/?probe=1babcb92fd) | Apr 18, 2024 |
| Dell          | PowerEdge T420              | Server      | [3796c964b5](https://linux-hardware.org/?probe=3796c964b5) | Apr 18, 2024 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [68b9255929](https://linux-hardware.org/?probe=68b9255929) | Apr 18, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [91410dd38c](https://linux-hardware.org/?probe=91410dd38c) | Apr 18, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e1f8cb5a4d](https://linux-hardware.org/?probe=e1f8cb5a4d) | Apr 18, 2024 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [340a3e1a78](https://linux-hardware.org/?probe=340a3e1a78) | Apr 18, 2024 |
| Lenovo        | ThinkPad T460s 20FAS5NN0... | Notebook    | [156dedcc62](https://linux-hardware.org/?probe=156dedcc62) | Apr 18, 2024 |
| Intel         | DH67CL AAG10212-207         | Desktop     | [276f923b44](https://linux-hardware.org/?probe=276f923b44) | Apr 18, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [24acebde2b](https://linux-hardware.org/?probe=24acebde2b) | Apr 18, 2024 |
| Gigabyte      | B450M K-CF                  | Desktop     | [74fb485917](https://linux-hardware.org/?probe=74fb485917) | Apr 17, 2024 |
| Intel         | H55                         | Desktop     | [28e666728f](https://linux-hardware.org/?probe=28e666728f) | Apr 17, 2024 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [fd71b9d36c](https://linux-hardware.org/?probe=fd71b9d36c) | Apr 17, 2024 |
| Intel         | NUC9i7QNB K49245-403        | Mini pc     | [29bc0e84a8](https://linux-hardware.org/?probe=29bc0e84a8) | Apr 17, 2024 |
| HP            | ProLiant DL380 Gen9         | Server      | [c3a2cafa4c](https://linux-hardware.org/?probe=c3a2cafa4c) | Apr 17, 2024 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [f08c90bc44](https://linux-hardware.org/?probe=f08c90bc44) | Apr 17, 2024 |
| Intel         | H55                         | Desktop     | [27ee1cd49f](https://linux-hardware.org/?probe=27ee1cd49f) | Apr 17, 2024 |
| Lenovo        | ThinkPad T450s 20BWS00V0... | Notebook    | [c6cafaee9d](https://linux-hardware.org/?probe=c6cafaee9d) | Apr 17, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e5f340aec0](https://linux-hardware.org/?probe=e5f340aec0) | Apr 17, 2024 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [68691105b0](https://linux-hardware.org/?probe=68691105b0) | Apr 17, 2024 |
| HP            | ProLiant DL360p Gen8        | Server      | [4f8f62dd7c](https://linux-hardware.org/?probe=4f8f62dd7c) | Apr 17, 2024 |
| Intel         | S1200BTL E98681-352         | Server      | [848bdccedc](https://linux-hardware.org/?probe=848bdccedc) | Apr 17, 2024 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [b408b88671](https://linux-hardware.org/?probe=b408b88671) | Apr 17, 2024 |
| ASUSTek       | Z9PR-D12 Series             | Server      | [463e1228da](https://linux-hardware.org/?probe=463e1228da) | Apr 17, 2024 |
| Acer          | Aspire ES1-731              | Notebook    | [cd5f5f6530](https://linux-hardware.org/?probe=cd5f5f6530) | Apr 17, 2024 |
| Microsoft     | Surface Go 3                | Tablet      | [30cfc28189](https://linux-hardware.org/?probe=30cfc28189) | Apr 17, 2024 |
| MSI           | Modern 15 B12M              | Notebook    | [b1786f8a58](https://linux-hardware.org/?probe=b1786f8a58) | Apr 17, 2024 |
| Unknown       | Unknown                     | All in one  | [fadcc61645](https://linux-hardware.org/?probe=fadcc61645) | Apr 17, 2024 |
| Dell          | Latitude E6400              | Notebook    | [6a6279d4c0](https://linux-hardware.org/?probe=6a6279d4c0) | Apr 17, 2024 |
| HP            | Laptop 17-bs0xx             | Notebook    | [2de1af4835](https://linux-hardware.org/?probe=2de1af4835) | Apr 16, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [a3eb57bb17](https://linux-hardware.org/?probe=a3eb57bb17) | Apr 16, 2024 |
| Intel         | ADL-F10                     | Desktop     | [036f5e1450](https://linux-hardware.org/?probe=036f5e1450) | Apr 16, 2024 |
| MSI           | H61M-P20                    | Desktop     | [17a91ba1d0](https://linux-hardware.org/?probe=17a91ba1d0) | Apr 16, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [cfacf09dbe](https://linux-hardware.org/?probe=cfacf09dbe) | Apr 16, 2024 |
| Intel         | D201GLY AAD81205-301        | Desktop     | [1b2fcf83fa](https://linux-hardware.org/?probe=1b2fcf83fa) | Apr 16, 2024 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [c9be366373](https://linux-hardware.org/?probe=c9be366373) | Apr 16, 2024 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [9dd5160f8f](https://linux-hardware.org/?probe=9dd5160f8f) | Apr 16, 2024 |
| Sony          | SVF15A17CLB                 | Notebook    | [7b947c3636](https://linux-hardware.org/?probe=7b947c3636) | Apr 16, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7cd3cf42ef](https://linux-hardware.org/?probe=7cd3cf42ef) | Apr 16, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [fd99b7519e](https://linux-hardware.org/?probe=fd99b7519e) | Apr 16, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [80386e5109](https://linux-hardware.org/?probe=80386e5109) | Apr 15, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [a41037f2e9](https://linux-hardware.org/?probe=a41037f2e9) | Apr 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9c51df5a4a](https://linux-hardware.org/?probe=9c51df5a4a) | Apr 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4b84c41edf](https://linux-hardware.org/?probe=4b84c41edf) | Apr 15, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [d8294ede23](https://linux-hardware.org/?probe=d8294ede23) | Apr 15, 2024 |
| AMI           | Intel                       | Desktop     | [d620a9c686](https://linux-hardware.org/?probe=d620a9c686) | Apr 15, 2024 |
| Acer          | One S1003                   | Tablet      | [425ae260b2](https://linux-hardware.org/?probe=425ae260b2) | Apr 15, 2024 |
| ASUSTek       | X502CA                      | Notebook    | [80390054a8](https://linux-hardware.org/?probe=80390054a8) | Apr 15, 2024 |
| ASUSTek       | Vivobook Go E1504GA_E150... | Notebook    | [2f8ba18ab4](https://linux-hardware.org/?probe=2f8ba18ab4) | Apr 15, 2024 |
| Dell          | Latitude E6440              | Notebook    | [9a85d3d85f](https://linux-hardware.org/?probe=9a85d3d85f) | Apr 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9f29571aab](https://linux-hardware.org/?probe=9f29571aab) | Apr 14, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [00c4bda850](https://linux-hardware.org/?probe=00c4bda850) | Apr 14, 2024 |
| Lenovo        | ThinkPad T470s 20HGS6Y80... | Notebook    | [56bf2bd4d4](https://linux-hardware.org/?probe=56bf2bd4d4) | Apr 14, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7259447d3b](https://linux-hardware.org/?probe=7259447d3b) | Apr 14, 2024 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [ec1f49c1c8](https://linux-hardware.org/?probe=ec1f49c1c8) | Apr 14, 2024 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [2ee0e2ace7](https://linux-hardware.org/?probe=2ee0e2ace7) | Apr 14, 2024 |
| HP            | 83C3 A01                    | Mini pc     | [b877d49ea4](https://linux-hardware.org/?probe=b877d49ea4) | Apr 14, 2024 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [20e465155b](https://linux-hardware.org/?probe=20e465155b) | Apr 14, 2024 |
| Notebook      | NS5x_NS7xAU                 | Notebook    | [fef58e28df](https://linux-hardware.org/?probe=fef58e28df) | Apr 14, 2024 |
| Dell          | Inspiron 5515               | Notebook    | [5847899f83](https://linux-hardware.org/?probe=5847899f83) | Apr 14, 2024 |
| ASRock        | X670E PG Lightning          | Desktop     | [e3bd195788](https://linux-hardware.org/?probe=e3bd195788) | Apr 14, 2024 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d79972631a](https://linux-hardware.org/?probe=d79972631a) | Apr 14, 2024 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fa6b81bbbf](https://linux-hardware.org/?probe=fa6b81bbbf) | Apr 14, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [4e8dddab03](https://linux-hardware.org/?probe=4e8dddab03) | Apr 14, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f3d0eefe93](https://linux-hardware.org/?probe=f3d0eefe93) | Apr 14, 2024 |
| Dell          | 0GXM1W A02                  | Desktop     | [7acfaf7395](https://linux-hardware.org/?probe=7acfaf7395) | Apr 14, 2024 |
| Unknown       | Unknown                     | Notebook    | [da4225e583](https://linux-hardware.org/?probe=da4225e583) | Apr 14, 2024 |
| Dell          | 0GXM1W A02                  | Desktop     | [e10d403882](https://linux-hardware.org/?probe=e10d403882) | Apr 14, 2024 |
| Unknown       | Unknown                     | Notebook    | [7dbc8ebb37](https://linux-hardware.org/?probe=7dbc8ebb37) | Apr 13, 2024 |
| IP3 Tech      | GB3                         | Mini pc     | [50683f2a9f](https://linux-hardware.org/?probe=50683f2a9f) | Apr 13, 2024 |
| Intel         | NUC9i7QNB K49245-403        | Mini pc     | [15fee94530](https://linux-hardware.org/?probe=15fee94530) | Apr 13, 2024 |
| IP3 Tech      | GB3                         | Mini pc     | [c4404c9117](https://linux-hardware.org/?probe=c4404c9117) | Apr 13, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [64eef30697](https://linux-hardware.org/?probe=64eef30697) | Apr 13, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [14ff2613c4](https://linux-hardware.org/?probe=14ff2613c4) | Apr 13, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [4b92f0d2d3](https://linux-hardware.org/?probe=4b92f0d2d3) | Apr 13, 2024 |
| Gigabyte      | Z270X-UD3-CF                | Desktop     | [b3a5999470](https://linux-hardware.org/?probe=b3a5999470) | Apr 13, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [94adb9264d](https://linux-hardware.org/?probe=94adb9264d) | Apr 13, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [5ef202ce64](https://linux-hardware.org/?probe=5ef202ce64) | Apr 13, 2024 |
| Google        | Atlas                       | Notebook    | [9073524bfb](https://linux-hardware.org/?probe=9073524bfb) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [b40a1b3e44](https://linux-hardware.org/?probe=b40a1b3e44) | Apr 12, 2024 |
| ASUSTek       | Vivobook Go E1504GA_E150... | Notebook    | [6fbf514771](https://linux-hardware.org/?probe=6fbf514771) | Apr 12, 2024 |
| Intel         | S2600GZ G11481-354          | Server      | [d6ce3ea6e8](https://linux-hardware.org/?probe=d6ce3ea6e8) | Apr 12, 2024 |
| HP            | 8053                        | Desktop     | [7518745fe0](https://linux-hardware.org/?probe=7518745fe0) | Apr 12, 2024 |
| MSI           | GE62 2QC                    | Notebook    | [af7a9f75d6](https://linux-hardware.org/?probe=af7a9f75d6) | Apr 12, 2024 |
| MSI           | GE62 2QC                    | Notebook    | [2b18322513](https://linux-hardware.org/?probe=2b18322513) | Apr 12, 2024 |
| ASUSTek       | P8H77-V                     | Desktop     | [ff2fb02615](https://linux-hardware.org/?probe=ff2fb02615) | Apr 12, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [d9ab381361](https://linux-hardware.org/?probe=d9ab381361) | Apr 12, 2024 |
| ASUSTek       | UX32VD                      | Notebook    | [a063aa7aef](https://linux-hardware.org/?probe=a063aa7aef) | Apr 12, 2024 |
| Notebook      | NS5x_NS7xAU                 | Notebook    | [d2fa3daec7](https://linux-hardware.org/?probe=d2fa3daec7) | Apr 12, 2024 |
| HP            | ProLiant DL380 Gen9         | Server      | [a9cd6d9c71](https://linux-hardware.org/?probe=a9cd6d9c71) | Apr 12, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [861ffd6210](https://linux-hardware.org/?probe=861ffd6210) | Apr 12, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [bc8e13b93d](https://linux-hardware.org/?probe=bc8e13b93d) | Apr 12, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [8d3873a49f](https://linux-hardware.org/?probe=8d3873a49f) | Apr 12, 2024 |
| HP            | 3397                        | Desktop     | [878192f0bd](https://linux-hardware.org/?probe=878192f0bd) | Apr 11, 2024 |
| Dell          | Latitude 7310               | Convertible | [2156e0a9cf](https://linux-hardware.org/?probe=2156e0a9cf) | Apr 11, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [026c72df1c](https://linux-hardware.org/?probe=026c72df1c) | Apr 11, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [57ccbefc29](https://linux-hardware.org/?probe=57ccbefc29) | Apr 11, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [75b741a57b](https://linux-hardware.org/?probe=75b741a57b) | Apr 11, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [86056cf6ca](https://linux-hardware.org/?probe=86056cf6ca) | Apr 11, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [045700832b](https://linux-hardware.org/?probe=045700832b) | Apr 11, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [ab8331fb24](https://linux-hardware.org/?probe=ab8331fb24) | Apr 11, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [204eec6335](https://linux-hardware.org/?probe=204eec6335) | Apr 11, 2024 |
| Supermicro    | H12SSL-CT                   | Server      | [33e7aacb2c](https://linux-hardware.org/?probe=33e7aacb2c) | Apr 11, 2024 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [66253502ac](https://linux-hardware.org/?probe=66253502ac) | Apr 11, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H1C... | Notebook    | [4d834b6378](https://linux-hardware.org/?probe=4d834b6378) | Apr 11, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H1C... | Notebook    | [12ad1e078b](https://linux-hardware.org/?probe=12ad1e078b) | Apr 11, 2024 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [4c3351faf0](https://linux-hardware.org/?probe=4c3351faf0) | Apr 11, 2024 |
| Lenovo        | Bantry CRB NOK              | Desktop     | [451151dc37](https://linux-hardware.org/?probe=451151dc37) | Apr 11, 2024 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [e7a4618bc4](https://linux-hardware.org/?probe=e7a4618bc4) | Apr 11, 2024 |
| ASUSTek       | TUF Gaming FA706II_TUF76... | Notebook    | [ee6a729006](https://linux-hardware.org/?probe=ee6a729006) | Apr 11, 2024 |
| ASUSTek       | X450CC                      | Notebook    | [752a03f0de](https://linux-hardware.org/?probe=752a03f0de) | Apr 11, 2024 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [c473133c45](https://linux-hardware.org/?probe=c473133c45) | Apr 11, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [44d8afa05f](https://linux-hardware.org/?probe=44d8afa05f) | Apr 11, 2024 |
| Intel         | D845GRG AAA81583-300        | Desktop     | [678a3f7bf8](https://linux-hardware.org/?probe=678a3f7bf8) | Apr 10, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [bcb9300739](https://linux-hardware.org/?probe=bcb9300739) | Apr 10, 2024 |
| ASUSTek       | Q87T                        | Desktop     | [9b85fb5652](https://linux-hardware.org/?probe=9b85fb5652) | Apr 10, 2024 |
| Dell          | Latitude 5590               | Notebook    | [dd558c6b50](https://linux-hardware.org/?probe=dd558c6b50) | Apr 10, 2024 |
| Dell          | Latitude E7440              | Notebook    | [d7c3a0d9c9](https://linux-hardware.org/?probe=d7c3a0d9c9) | Apr 10, 2024 |
| Dell          | Latitude E7440              | Notebook    | [2ea80bdebb](https://linux-hardware.org/?probe=2ea80bdebb) | Apr 10, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [8d05f71f6b](https://linux-hardware.org/?probe=8d05f71f6b) | Apr 10, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4b2cfbf4b2](https://linux-hardware.org/?probe=4b2cfbf4b2) | Apr 10, 2024 |
| Dell          | Latitude E7440              | Notebook    | [9f0e547b50](https://linux-hardware.org/?probe=9f0e547b50) | Apr 10, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [0b230ea544](https://linux-hardware.org/?probe=0b230ea544) | Apr 10, 2024 |
| Dell          | 02C2CP A03                  | Server      | [60940cc2cd](https://linux-hardware.org/?probe=60940cc2cd) | Apr 10, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [bdcccf8c92](https://linux-hardware.org/?probe=bdcccf8c92) | Apr 10, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [2ca0777f6f](https://linux-hardware.org/?probe=2ca0777f6f) | Apr 10, 2024 |
| OrangePi      | Zero3                       | Soc         | [761d16b70f](https://linux-hardware.org/?probe=761d16b70f) | Apr 10, 2024 |
| GenMachine    | Ren12                       | Desktop     | [f5ec7252ac](https://linux-hardware.org/?probe=f5ec7252ac) | Apr 10, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [09d22d5711](https://linux-hardware.org/?probe=09d22d5711) | Apr 10, 2024 |
| Lenovo        | 36E9 SDK0R32862 WIN 3258... | Desktop     | [e494587893](https://linux-hardware.org/?probe=e494587893) | Apr 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [79a4ac6c52](https://linux-hardware.org/?probe=79a4ac6c52) | Apr 09, 2024 |
| Lenovo        | ThinkPad T420 4180DS7       | Notebook    | [e8ea27e460](https://linux-hardware.org/?probe=e8ea27e460) | Apr 09, 2024 |
| HP            | ProBook 4510s               | Notebook    | [9992995d43](https://linux-hardware.org/?probe=9992995d43) | Apr 09, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [cd38e8b3bd](https://linux-hardware.org/?probe=cd38e8b3bd) | Apr 09, 2024 |
| Lenovo        | G710 20252                  | Notebook    | [6859d6ad04](https://linux-hardware.org/?probe=6859d6ad04) | Apr 09, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [5c33da7024](https://linux-hardware.org/?probe=5c33da7024) | Apr 09, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [67c665fbe5](https://linux-hardware.org/?probe=67c665fbe5) | Apr 09, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [ffd26f8255](https://linux-hardware.org/?probe=ffd26f8255) | Apr 09, 2024 |
| HP            | 158B                        | Desktop     | [d7c58cf079](https://linux-hardware.org/?probe=d7c58cf079) | Apr 09, 2024 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [bf17502965](https://linux-hardware.org/?probe=bf17502965) | Apr 09, 2024 |
| HP            | Mini 210-1000               | Notebook    | [0afce35d6b](https://linux-hardware.org/?probe=0afce35d6b) | Apr 09, 2024 |
| HP            | Pavilion dv9500             | Notebook    | [19def7ab9a](https://linux-hardware.org/?probe=19def7ab9a) | Apr 09, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [fba34eaafb](https://linux-hardware.org/?probe=fba34eaafb) | Apr 09, 2024 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [2f2ae87a60](https://linux-hardware.org/?probe=2f2ae87a60) | Apr 08, 2024 |
| Samsung       | 750XED                      | Notebook    | [bfcfd0dab7](https://linux-hardware.org/?probe=bfcfd0dab7) | Apr 08, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [3b2982c04c](https://linux-hardware.org/?probe=3b2982c04c) | Apr 08, 2024 |
| Intel         | ADL-F10                     | Desktop     | [17a43967f2](https://linux-hardware.org/?probe=17a43967f2) | Apr 08, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [9ec4bf2a73](https://linux-hardware.org/?probe=9ec4bf2a73) | Apr 08, 2024 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [295a425d96](https://linux-hardware.org/?probe=295a425d96) | Apr 08, 2024 |
| ASRock        | B650M Pro RS                | Desktop     | [8a6331a3b2](https://linux-hardware.org/?probe=8a6331a3b2) | Apr 08, 2024 |
| ASRock        | B650M Pro RS                | Desktop     | [9c421a9dbb](https://linux-hardware.org/?probe=9c421a9dbb) | Apr 08, 2024 |
| Dell          | Latitude 9440 2-in-1        | Convertible | [8472484320](https://linux-hardware.org/?probe=8472484320) | Apr 08, 2024 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [e54693d43a](https://linux-hardware.org/?probe=e54693d43a) | Apr 08, 2024 |
| OrangePi      | Zero3                       | Soc         | [019ad99ba9](https://linux-hardware.org/?probe=019ad99ba9) | Apr 08, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [95b6780794](https://linux-hardware.org/?probe=95b6780794) | Apr 08, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [78fa4035a9](https://linux-hardware.org/?probe=78fa4035a9) | Apr 08, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [9cc14232f1](https://linux-hardware.org/?probe=9cc14232f1) | Apr 08, 2024 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [794f80b5a2](https://linux-hardware.org/?probe=794f80b5a2) | Apr 08, 2024 |
| ASUSTek       | TUF Gaming Z790-PRO WIFI    | Desktop     | [6c9980ed7d](https://linux-hardware.org/?probe=6c9980ed7d) | Apr 08, 2024 |
| ASUSTek       | TUF Gaming Z790-PRO WIFI    | Desktop     | [08f0877b81](https://linux-hardware.org/?probe=08f0877b81) | Apr 08, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [0079f0fad1](https://linux-hardware.org/?probe=0079f0fad1) | Apr 07, 2024 |
| HP            | ProLiant DL380 Gen9         | Server      | [28e6287aa0](https://linux-hardware.org/?probe=28e6287aa0) | Apr 07, 2024 |
| Lenovo        | ThinkPad L430 2465C32       | Notebook    | [788733ca44](https://linux-hardware.org/?probe=788733ca44) | Apr 07, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [fa70861321](https://linux-hardware.org/?probe=fa70861321) | Apr 07, 2024 |
| HP            | 240 G6 Notebook PC          | Notebook    | [00731ce19b](https://linux-hardware.org/?probe=00731ce19b) | Apr 07, 2024 |
| ASRock        | X570S PG Riptide            | Desktop     | [2ceec9259b](https://linux-hardware.org/?probe=2ceec9259b) | Apr 07, 2024 |
| Dell          | Latitude E6410              | Notebook    | [af5738b699](https://linux-hardware.org/?probe=af5738b699) | Apr 07, 2024 |
| Dell          | Inspiron 3443               | Notebook    | [0794f7cac6](https://linux-hardware.org/?probe=0794f7cac6) | Apr 07, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [ee31a1ab57](https://linux-hardware.org/?probe=ee31a1ab57) | Apr 07, 2024 |
| SolidRun      | CEX7 Platform               | Desktop     | [921a652a7e](https://linux-hardware.org/?probe=921a652a7e) | Apr 07, 2024 |
| Dell          | 06X1TJ A00                  | Desktop     | [9a4f23a1e2](https://linux-hardware.org/?probe=9a4f23a1e2) | Apr 07, 2024 |
| MSI           | Prestige 16 AI Studio B1... | Notebook    | [03e388324a](https://linux-hardware.org/?probe=03e388324a) | Apr 07, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [6c3aca8be2](https://linux-hardware.org/?probe=6c3aca8be2) | Apr 07, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ebc11c966d](https://linux-hardware.org/?probe=ebc11c966d) | Apr 07, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [c917535f70](https://linux-hardware.org/?probe=c917535f70) | Apr 06, 2024 |
| Gigabyte      | B760I AORUS PRO             | Desktop     | [3de78e9354](https://linux-hardware.org/?probe=3de78e9354) | Apr 06, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [95ea5b1c53](https://linux-hardware.org/?probe=95ea5b1c53) | Apr 06, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1760da04a2](https://linux-hardware.org/?probe=1760da04a2) | Apr 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | Notebook    | [327b8112a5](https://linux-hardware.org/?probe=327b8112a5) | Apr 06, 2024 |
| Lenovo        | ThinkPad T420 4180WA8       | Notebook    | [b8975f4296](https://linux-hardware.org/?probe=b8975f4296) | Apr 06, 2024 |
| SZMZ          | X99-S3                      | Desktop     | [a3be3fb7ae](https://linux-hardware.org/?probe=a3be3fb7ae) | Apr 06, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [edd04ef397](https://linux-hardware.org/?probe=edd04ef397) | Apr 06, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [cd19230af5](https://linux-hardware.org/?probe=cd19230af5) | Apr 06, 2024 |
| Dell          | Latitude 7480               | Notebook    | [60c813fedb](https://linux-hardware.org/?probe=60c813fedb) | Apr 06, 2024 |
| ASUSTek       | M4A785-M                    | Desktop     | [dae4d8f0c7](https://linux-hardware.org/?probe=dae4d8f0c7) | Apr 05, 2024 |
| Intel         | S5000PSL                    | Server      | [b6d52648e6](https://linux-hardware.org/?probe=b6d52648e6) | Apr 05, 2024 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1cb1d0f6bf](https://linux-hardware.org/?probe=1cb1d0f6bf) | Apr 05, 2024 |
| Dell          | 00NH4P A02                  | Server      | [00040f07d6](https://linux-hardware.org/?probe=00040f07d6) | Apr 05, 2024 |
| ASUSTek       | M4A785-M                    | Desktop     | [1a3e173e11](https://linux-hardware.org/?probe=1a3e173e11) | Apr 05, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [169c6755af](https://linux-hardware.org/?probe=169c6755af) | Apr 05, 2024 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [67a3c40ae1](https://linux-hardware.org/?probe=67a3c40ae1) | Apr 05, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [77ca8ba81c](https://linux-hardware.org/?probe=77ca8ba81c) | Apr 05, 2024 |
| Lenovo        | 330B NOK                    | Mini pc     | [452cd8332b](https://linux-hardware.org/?probe=452cd8332b) | Apr 05, 2024 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [929a473474](https://linux-hardware.org/?probe=929a473474) | Apr 05, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6718f93942](https://linux-hardware.org/?probe=6718f93942) | Apr 05, 2024 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [3c7ff2a204](https://linux-hardware.org/?probe=3c7ff2a204) | Apr 05, 2024 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [547acce656](https://linux-hardware.org/?probe=547acce656) | Apr 05, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [b2df81d7c6](https://linux-hardware.org/?probe=b2df81d7c6) | Apr 05, 2024 |
| ASRock        | Z97 Extreme4                | Desktop     | [b3391cd116](https://linux-hardware.org/?probe=b3391cd116) | Apr 05, 2024 |
| ASUSTek       | PRIME Z270-AR               | Desktop     | [d994e7a27c](https://linux-hardware.org/?probe=d994e7a27c) | Apr 05, 2024 |
| ASUSTek       | PRIME Z270-AR               | Desktop     | [f4fc63ac25](https://linux-hardware.org/?probe=f4fc63ac25) | Apr 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [45bd209357](https://linux-hardware.org/?probe=45bd209357) | Apr 05, 2024 |
| ASUSTek       | K53E                        | Notebook    | [4cde59e125](https://linux-hardware.org/?probe=4cde59e125) | Apr 05, 2024 |
| Google        | Peppy                       | Notebook    | [18d00034d7](https://linux-hardware.org/?probe=18d00034d7) | Apr 05, 2024 |
| HP            | Pavilion dv7                | Notebook    | [f7ecb14c8e](https://linux-hardware.org/?probe=f7ecb14c8e) | Apr 05, 2024 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [8fb4cdf244](https://linux-hardware.org/?probe=8fb4cdf244) | Apr 04, 2024 |
| Lenovo        | 312F SDK0J40697 WIN 3305... | Mini pc     | [58d2a59187](https://linux-hardware.org/?probe=58d2a59187) | Apr 04, 2024 |
| Digibras      | CL341                       | Notebook    | [7cc99d85ef](https://linux-hardware.org/?probe=7cc99d85ef) | Apr 04, 2024 |
| Lenovo        | ThinkPad T420 4180W1A       | Notebook    | [274454a883](https://linux-hardware.org/?probe=274454a883) | Apr 04, 2024 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | Desktop     | [09d25c6ea8](https://linux-hardware.org/?probe=09d25c6ea8) | Apr 04, 2024 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [b2d57c4c76](https://linux-hardware.org/?probe=b2d57c4c76) | Apr 04, 2024 |
| Dell          | 0XKH0D A02                  | Desktop     | [ee1a50dbca](https://linux-hardware.org/?probe=ee1a50dbca) | Apr 04, 2024 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [f4f685c50a](https://linux-hardware.org/?probe=f4f685c50a) | Apr 04, 2024 |
| Dell          | 0PU052                      | Desktop     | [6555bfeb7b](https://linux-hardware.org/?probe=6555bfeb7b) | Apr 04, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [faa2ccd815](https://linux-hardware.org/?probe=faa2ccd815) | Apr 04, 2024 |
| Digibras      | CL341                       | Notebook    | [da58ad0afb](https://linux-hardware.org/?probe=da58ad0afb) | Apr 04, 2024 |
| ASRock        | B450M/ac R2.0               | Desktop     | [454169b7c9](https://linux-hardware.org/?probe=454169b7c9) | Apr 04, 2024 |
| Gigabyte      | B360M H                     | Desktop     | [acb3dd01b9](https://linux-hardware.org/?probe=acb3dd01b9) | Apr 04, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [a12df57269](https://linux-hardware.org/?probe=a12df57269) | Apr 04, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f4641bc90c](https://linux-hardware.org/?probe=f4641bc90c) | Apr 04, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [648e1cbe49](https://linux-hardware.org/?probe=648e1cbe49) | Apr 04, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e41ebb7b08](https://linux-hardware.org/?probe=e41ebb7b08) | Apr 04, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [31a5f26be7](https://linux-hardware.org/?probe=31a5f26be7) | Apr 03, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [9ae8603096](https://linux-hardware.org/?probe=9ae8603096) | Apr 03, 2024 |
| ASUSTek       | G11CB                       | Desktop     | [372379f18a](https://linux-hardware.org/?probe=372379f18a) | Apr 03, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [4b5619e1d7](https://linux-hardware.org/?probe=4b5619e1d7) | Apr 03, 2024 |
| Lenovo        | ThinkPad E15 20RD001FPB     | Notebook    | [209962ecb2](https://linux-hardware.org/?probe=209962ecb2) | Apr 03, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [c2482a6360](https://linux-hardware.org/?probe=c2482a6360) | Apr 03, 2024 |
| MSI           | H110M PRO-VH                | Desktop     | [a135bec51e](https://linux-hardware.org/?probe=a135bec51e) | Apr 03, 2024 |
| Lenovo        | ThinkPad E15 20RD001FPB     | Notebook    | [ac7a313a3c](https://linux-hardware.org/?probe=ac7a313a3c) | Apr 03, 2024 |
| HUAWEI        | NBLBZ-WAX9N                 | Notebook    | [f0688bc1c1](https://linux-hardware.org/?probe=f0688bc1c1) | Apr 03, 2024 |
| Supermicro    | X8ST3                       | Desktop     | [45765546f5](https://linux-hardware.org/?probe=45765546f5) | Apr 03, 2024 |
| ASRock        | H55M-LE                     | Desktop     | [603c13de70](https://linux-hardware.org/?probe=603c13de70) | Apr 03, 2024 |
| HP            | ProLiant DL380 Gen9         | Server      | [a3c26f6451](https://linux-hardware.org/?probe=a3c26f6451) | Apr 03, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [83e03938be](https://linux-hardware.org/?probe=83e03938be) | Apr 03, 2024 |
| ASUSTek       | X456UQ                      | Notebook    | [e7ae74a0ed](https://linux-hardware.org/?probe=e7ae74a0ed) | Apr 03, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [34684cff67](https://linux-hardware.org/?probe=34684cff67) | Apr 03, 2024 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [29d954b3b6](https://linux-hardware.org/?probe=29d954b3b6) | Apr 03, 2024 |
| Dell          | Latitude 5440               | Notebook    | [19eee079f1](https://linux-hardware.org/?probe=19eee079f1) | Apr 03, 2024 |
| Google        | Fizz                        | Desktop     | [55cd95ea52](https://linux-hardware.org/?probe=55cd95ea52) | Apr 03, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [86bf1e5346](https://linux-hardware.org/?probe=86bf1e5346) | Apr 03, 2024 |
| Dell          | Vostro 5590                 | Notebook    | [9046f24617](https://linux-hardware.org/?probe=9046f24617) | Apr 03, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [2bb5c3d295](https://linux-hardware.org/?probe=2bb5c3d295) | Apr 03, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [224f00ec38](https://linux-hardware.org/?probe=224f00ec38) | Apr 03, 2024 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [1c9bd6a74d](https://linux-hardware.org/?probe=1c9bd6a74d) | Apr 03, 2024 |
| Panasonic     | CF-C1BTCREFF                | Notebook    | [6a749f6baf](https://linux-hardware.org/?probe=6a749f6baf) | Apr 03, 2024 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [ce53254be7](https://linux-hardware.org/?probe=ce53254be7) | Apr 02, 2024 |
| Gigabyte      | MC12-LE0-00 01000100        | Server      | [2d77943e65](https://linux-hardware.org/?probe=2d77943e65) | Apr 02, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [992cf5c5a6](https://linux-hardware.org/?probe=992cf5c5a6) | Apr 02, 2024 |
| Intel         | NUC7i5BNB J31144-312        | Mini pc     | [5fca055ea9](https://linux-hardware.org/?probe=5fca055ea9) | Apr 02, 2024 |
| Dell          | 0H603H A01                  | Server      | [129d04d79e](https://linux-hardware.org/?probe=129d04d79e) | Apr 02, 2024 |
| Intel         | DX58SO2 AAG10925-207        | Desktop     | [170582acfb](https://linux-hardware.org/?probe=170582acfb) | Apr 02, 2024 |
| Intel         | DX58SO2 AAG10925-207        | Desktop     | [a91ca2286f](https://linux-hardware.org/?probe=a91ca2286f) | Apr 02, 2024 |
| Fujitsu       | FARQ1801LZ                  | Tablet      | [ba34c56bb1](https://linux-hardware.org/?probe=ba34c56bb1) | Apr 02, 2024 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [054b7415b5](https://linux-hardware.org/?probe=054b7415b5) | Apr 01, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [42c853e695](https://linux-hardware.org/?probe=42c853e695) | Apr 01, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [6c8467a122](https://linux-hardware.org/?probe=6c8467a122) | Apr 01, 2024 |
| Dell          | Latitude E6520              | Notebook    | [d359664665](https://linux-hardware.org/?probe=d359664665) | Apr 01, 2024 |
| Dell          | Latitude 7400               | Notebook    | [5de339a7cc](https://linux-hardware.org/?probe=5de339a7cc) | Apr 01, 2024 |
| Dell          | 04MFRM A02                  | Desktop     | [588fc1d405](https://linux-hardware.org/?probe=588fc1d405) | Apr 01, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [d7142dfd4d](https://linux-hardware.org/?probe=d7142dfd4d) | Apr 01, 2024 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [9bda4cf2a7](https://linux-hardware.org/?probe=9bda4cf2a7) | Apr 01, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [bd6730e15d](https://linux-hardware.org/?probe=bd6730e15d) | Apr 01, 2024 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [bfc80c9d90](https://linux-hardware.org/?probe=bfc80c9d90) | Apr 01, 2024 |
| MSI           | X399 SLI PLUS               | Desktop     | [e519990ad6](https://linux-hardware.org/?probe=e519990ad6) | Apr 01, 2024 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [2a236e9fd5](https://linux-hardware.org/?probe=2a236e9fd5) | Apr 01, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [f8bc7da1fc](https://linux-hardware.org/?probe=f8bc7da1fc) | Apr 01, 2024 |
| Lenovo        | ThinkPad T430s 2355AR2      | Notebook    | [645e34f6c3](https://linux-hardware.org/?probe=645e34f6c3) | Apr 01, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [b4724cc6b0](https://linux-hardware.org/?probe=b4724cc6b0) | Mar 31, 2024 |
| Dell          | 0J2J3Y A00                  | Desktop     | [34c276b20a](https://linux-hardware.org/?probe=34c276b20a) | Mar 31, 2024 |
| Intel         | DP35DP AAD81073-207         | Desktop     | [8d783be6f7](https://linux-hardware.org/?probe=8d783be6f7) | Mar 31, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [9f092af8fc](https://linux-hardware.org/?probe=9f092af8fc) | Mar 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [1c48ba772e](https://linux-hardware.org/?probe=1c48ba772e) | Mar 31, 2024 |
| ASUSTek       | PRIME B660M-A AC D4         | Desktop     | [09927387b6](https://linux-hardware.org/?probe=09927387b6) | Mar 31, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [c03a952f7a](https://linux-hardware.org/?probe=c03a952f7a) | Mar 31, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [2af9e98058](https://linux-hardware.org/?probe=2af9e98058) | Mar 31, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [eeb5af4e4d](https://linux-hardware.org/?probe=eeb5af4e4d) | Mar 31, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [45c3f7f796](https://linux-hardware.org/?probe=45c3f7f796) | Mar 31, 2024 |
| ASUSTek       | GL553VD                     | Notebook    | [cdb08c255c](https://linux-hardware.org/?probe=cdb08c255c) | Mar 30, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [b6bb7745a9](https://linux-hardware.org/?probe=b6bb7745a9) | Mar 30, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [76c1ed5a7c](https://linux-hardware.org/?probe=76c1ed5a7c) | Mar 30, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0f799d574c](https://linux-hardware.org/?probe=0f799d574c) | Mar 30, 2024 |
| HP            | EliteBook 2740p             | Notebook    | [796c12edc5](https://linux-hardware.org/?probe=796c12edc5) | Mar 30, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b2c5315c94](https://linux-hardware.org/?probe=b2c5315c94) | Mar 30, 2024 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [dbc70004b3](https://linux-hardware.org/?probe=dbc70004b3) | Mar 30, 2024 |
| Lenovo        | ThinkPad P53 20QQS5WG00     | Notebook    | [15499f30af](https://linux-hardware.org/?probe=15499f30af) | Mar 30, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [e988ec8d61](https://linux-hardware.org/?probe=e988ec8d61) | Mar 30, 2024 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [0c67b02957](https://linux-hardware.org/?probe=0c67b02957) | Mar 30, 2024 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [b79b70e996](https://linux-hardware.org/?probe=b79b70e996) | Mar 30, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [feb0c64ad4](https://linux-hardware.org/?probe=feb0c64ad4) | Mar 30, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [bf5466e3a0](https://linux-hardware.org/?probe=bf5466e3a0) | Mar 30, 2024 |
| HP            | 8463                        | Desktop     | [dd77e7dc68](https://linux-hardware.org/?probe=dd77e7dc68) | Mar 30, 2024 |
| Dell          | Vostro 1015                 | Notebook    | [f9ca91d526](https://linux-hardware.org/?probe=f9ca91d526) | Mar 29, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e1a32810f8](https://linux-hardware.org/?probe=e1a32810f8) | Mar 29, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9be524311b](https://linux-hardware.org/?probe=9be524311b) | Mar 29, 2024 |
| Lenovo        | ThinkPad X220 4291W3B       | Notebook    | [c4fdbba9d2](https://linux-hardware.org/?probe=c4fdbba9d2) | Mar 29, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [fd1414dbcb](https://linux-hardware.org/?probe=fd1414dbcb) | Mar 29, 2024 |
| JGINYUE       | X99M-PLUS D4 V3.1           | Desktop     | [e44ab52f45](https://linux-hardware.org/?probe=e44ab52f45) | Mar 29, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [176e1c469e](https://linux-hardware.org/?probe=176e1c469e) | Mar 29, 2024 |
| Dell          | Latitude 5414               | Notebook    | [debd534bcb](https://linux-hardware.org/?probe=debd534bcb) | Mar 29, 2024 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [652f1eb271](https://linux-hardware.org/?probe=652f1eb271) | Mar 29, 2024 |
| Supermicro    | X8DTT                       | Server      | [0b94978c31](https://linux-hardware.org/?probe=0b94978c31) | Mar 29, 2024 |
| Supermicro    | X8DTT                       | Server      | [667d230c85](https://linux-hardware.org/?probe=667d230c85) | Mar 29, 2024 |
| MSI           | X470 GAMING PLUS            | Desktop     | [e312018423](https://linux-hardware.org/?probe=e312018423) | Mar 29, 2024 |
| Supermicro    | X12SAE-5                    | Server      | [9a4ba4f180](https://linux-hardware.org/?probe=9a4ba4f180) | Mar 28, 2024 |
| HP            | 829A                        | Mini pc     | [9419634289](https://linux-hardware.org/?probe=9419634289) | Mar 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4b1c2afd39](https://linux-hardware.org/?probe=4b1c2afd39) | Mar 28, 2024 |
| Supermicro    | X12SAE-5                    | Server      | [01d33257fe](https://linux-hardware.org/?probe=01d33257fe) | Mar 28, 2024 |
| Apple         | Mac-F2268CC8                | All in one  | [aa208bf7ed](https://linux-hardware.org/?probe=aa208bf7ed) | Mar 28, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [e963c8d60d](https://linux-hardware.org/?probe=e963c8d60d) | Mar 28, 2024 |
| HP            | EliteBook 835 13 inch G9... | Notebook    | [2b2e2a0296](https://linux-hardware.org/?probe=2b2e2a0296) | Mar 28, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [5d1d7ed87a](https://linux-hardware.org/?probe=5d1d7ed87a) | Mar 28, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [f14980865f](https://linux-hardware.org/?probe=f14980865f) | Mar 28, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [e80bef29a7](https://linux-hardware.org/?probe=e80bef29a7) | Mar 28, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [43c77170e4](https://linux-hardware.org/?probe=43c77170e4) | Mar 28, 2024 |
| Dell          | Latitude 5480               | Notebook    | [21dd5f9667](https://linux-hardware.org/?probe=21dd5f9667) | Mar 28, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b0999a9b6a](https://linux-hardware.org/?probe=b0999a9b6a) | Mar 27, 2024 |
| HP            | EliteBook 835 13 inch G9... | Notebook    | [430635ac56](https://linux-hardware.org/?probe=430635ac56) | Mar 27, 2024 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [05bab22d87](https://linux-hardware.org/?probe=05bab22d87) | Mar 27, 2024 |
| Lenovo        | 312F SDK0J40697 WIN 3305... | Mini pc     | [48e33b929c](https://linux-hardware.org/?probe=48e33b929c) | Mar 27, 2024 |
| Google        | Stout                       | Notebook    | [8b022ae66a](https://linux-hardware.org/?probe=8b022ae66a) | Mar 27, 2024 |
| Google        | Stout                       | Notebook    | [4e9784a9a7](https://linux-hardware.org/?probe=4e9784a9a7) | Mar 27, 2024 |
| Dell          | 0020HJ A01                  | Server      | [be50a442ab](https://linux-hardware.org/?probe=be50a442ab) | Mar 27, 2024 |
| Dell          | 0WR7PY A01                  | Desktop     | [aa3125e137](https://linux-hardware.org/?probe=aa3125e137) | Mar 27, 2024 |
| Google        | Stout                       | Notebook    | [7646bacc68](https://linux-hardware.org/?probe=7646bacc68) | Mar 27, 2024 |
| Google        | Stout                       | Notebook    | [352f4368da](https://linux-hardware.org/?probe=352f4368da) | Mar 27, 2024 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [024fd15280](https://linux-hardware.org/?probe=024fd15280) | Mar 27, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [31a385d0e9](https://linux-hardware.org/?probe=31a385d0e9) | Mar 27, 2024 |
| Lenovo        | B50-10 80QR                 | Notebook    | [cf333072f0](https://linux-hardware.org/?probe=cf333072f0) | Mar 27, 2024 |
| Gigabyte      | H81M-S2V                    | Desktop     | [af7633b712](https://linux-hardware.org/?probe=af7633b712) | Mar 27, 2024 |
| Supermicro    | X8DT6                       | Server      | [b8eeebfc78](https://linux-hardware.org/?probe=b8eeebfc78) | Mar 27, 2024 |
| Lenovo        | ThinkServer TS440           | Desktop     | [063d6aafdb](https://linux-hardware.org/?probe=063d6aafdb) | Mar 27, 2024 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f74c46802a](https://linux-hardware.org/?probe=f74c46802a) | Mar 27, 2024 |
| Dell          | 0D6H9T A00                  | Desktop     | [26269c60d1](https://linux-hardware.org/?probe=26269c60d1) | Mar 27, 2024 |
| Lenovo        | Unknown                     | Notebook    | [3bbef18998](https://linux-hardware.org/?probe=3bbef18998) | Mar 27, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ae5952b714](https://linux-hardware.org/?probe=ae5952b714) | Mar 27, 2024 |
| ASUSTek       | Q502LAB                     | Notebook    | [d9dc351db0](https://linux-hardware.org/?probe=d9dc351db0) | Mar 26, 2024 |
| Lenovo        | ThinkPad 13 20J10046US      | Notebook    | [160ac60377](https://linux-hardware.org/?probe=160ac60377) | Mar 26, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [5eb093e5c7](https://linux-hardware.org/?probe=5eb093e5c7) | Mar 26, 2024 |
| Google        | Stout                       | Notebook    | [ff192d759c](https://linux-hardware.org/?probe=ff192d759c) | Mar 26, 2024 |
| Google        | Stout                       | Notebook    | [a8643e01ca](https://linux-hardware.org/?probe=a8643e01ca) | Mar 26, 2024 |
| Samsung       | 550XED                      | Notebook    | [ab624683ca](https://linux-hardware.org/?probe=ab624683ca) | Mar 26, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [f78cc0f797](https://linux-hardware.org/?probe=f78cc0f797) | Mar 26, 2024 |
| Google        | Stout                       | Notebook    | [a554b971b4](https://linux-hardware.org/?probe=a554b971b4) | Mar 26, 2024 |
| HP            | 829A                        | Mini pc     | [5714e4e197](https://linux-hardware.org/?probe=5714e4e197) | Mar 26, 2024 |
| Google        | Stout                       | Notebook    | [042f9d9837](https://linux-hardware.org/?probe=042f9d9837) | Mar 26, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [f6f2e4d8d3](https://linux-hardware.org/?probe=f6f2e4d8d3) | Mar 26, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [bfe7baf9c6](https://linux-hardware.org/?probe=bfe7baf9c6) | Mar 26, 2024 |
| Dell          | Inspiron 5593               | Notebook    | [1630ab92c1](https://linux-hardware.org/?probe=1630ab92c1) | Mar 26, 2024 |
| Biostar       | B450MX-S                    | Desktop     | [dd90661bff](https://linux-hardware.org/?probe=dd90661bff) | Mar 26, 2024 |
| ASUSTek       | K53SC                       | Notebook    | [dadf168399](https://linux-hardware.org/?probe=dadf168399) | Mar 26, 2024 |
| Gigabyte      | B365M D2V                   | Desktop     | [bd13d968ce](https://linux-hardware.org/?probe=bd13d968ce) | Mar 26, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [9eb745f7d5](https://linux-hardware.org/?probe=9eb745f7d5) | Mar 26, 2024 |
| Acer          | Aspire 5820TG               | Notebook    | [9e3a75ab14](https://linux-hardware.org/?probe=9e3a75ab14) | Mar 26, 2024 |
| Toshiba       | Satellite A210              | Notebook    | [37734a1409](https://linux-hardware.org/?probe=37734a1409) | Mar 26, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [1652f0954c](https://linux-hardware.org/?probe=1652f0954c) | Mar 26, 2024 |
| ASUSTek       | X542UQ                      | Notebook    | [75455c4a87](https://linux-hardware.org/?probe=75455c4a87) | Mar 26, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e772c3db14](https://linux-hardware.org/?probe=e772c3db14) | Mar 26, 2024 |
| ASUSTek       | X540LA                      | Notebook    | [2c593ff829](https://linux-hardware.org/?probe=2c593ff829) | Mar 26, 2024 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [069f9b2bc9](https://linux-hardware.org/?probe=069f9b2bc9) | Mar 26, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c2dedfbe62](https://linux-hardware.org/?probe=c2dedfbe62) | Mar 25, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [f4276dd02c](https://linux-hardware.org/?probe=f4276dd02c) | Mar 25, 2024 |
| Congatec      | conga-B7XD C.3              | Mini pc     | [ff584585fe](https://linux-hardware.org/?probe=ff584585fe) | Mar 25, 2024 |
| Google        | Stout                       | Notebook    | [8ac4ec7cd8](https://linux-hardware.org/?probe=8ac4ec7cd8) | Mar 25, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [25184ad945](https://linux-hardware.org/?probe=25184ad945) | Mar 25, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [b48921d197](https://linux-hardware.org/?probe=b48921d197) | Mar 25, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [c906c9dc87](https://linux-hardware.org/?probe=c906c9dc87) | Mar 25, 2024 |
| HP            | Pavilion 17                 | Notebook    | [8bf3b9d8bd](https://linux-hardware.org/?probe=8bf3b9d8bd) | Mar 25, 2024 |
| HP            | ProBook 655 G2              | Notebook    | [49a85fae09](https://linux-hardware.org/?probe=49a85fae09) | Mar 25, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [43d5eddd6e](https://linux-hardware.org/?probe=43d5eddd6e) | Mar 25, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [756f5d9aca](https://linux-hardware.org/?probe=756f5d9aca) | Mar 25, 2024 |
| LG Electro... | 17Z90R-H.ADC8U1             | Notebook    | [d0bcf896cf](https://linux-hardware.org/?probe=d0bcf896cf) | Mar 25, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [954efe1d9b](https://linux-hardware.org/?probe=954efe1d9b) | Mar 25, 2024 |
| Dell          | 0DR845                      | Desktop     | [81bc347039](https://linux-hardware.org/?probe=81bc347039) | Mar 25, 2024 |
| Acer          | Swift SF514-56T             | Notebook    | [37cec8bd6a](https://linux-hardware.org/?probe=37cec8bd6a) | Mar 24, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [7cad0a2b84](https://linux-hardware.org/?probe=7cad0a2b84) | Mar 24, 2024 |
| Dell          | 06D7TR A02                  | Desktop     | [ae3cf563b4](https://linux-hardware.org/?probe=ae3cf563b4) | Mar 24, 2024 |
| Intel         | DX58SO AAE29331-503         | Desktop     | [7e3d9e89de](https://linux-hardware.org/?probe=7e3d9e89de) | Mar 24, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [773df1edad](https://linux-hardware.org/?probe=773df1edad) | Mar 24, 2024 |
| Packard Be... | WMCP78M                     | Desktop     | [854bfb4d53](https://linux-hardware.org/?probe=854bfb4d53) | Mar 24, 2024 |
| Medion        | MS-7616                     | Desktop     | [56b5e8ba1d](https://linux-hardware.org/?probe=56b5e8ba1d) | Mar 24, 2024 |
| Lenovo        | ThinkPad Edge 03014CG       | Notebook    | [2b57d89f5a](https://linux-hardware.org/?probe=2b57d89f5a) | Mar 24, 2024 |
| Unknown       | Home a2 lite                | Notebook    | [88544e3a1c](https://linux-hardware.org/?probe=88544e3a1c) | Mar 24, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [8a9482cb42](https://linux-hardware.org/?probe=8a9482cb42) | Mar 24, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [afa5872c09](https://linux-hardware.org/?probe=afa5872c09) | Mar 24, 2024 |
| Dell          | 06D7TR A02                  | Desktop     | [d66b1dcb1a](https://linux-hardware.org/?probe=d66b1dcb1a) | Mar 24, 2024 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [54ee23abb0](https://linux-hardware.org/?probe=54ee23abb0) | Mar 24, 2024 |
| HP            | EliteBook 8530w             | Notebook    | [68ee7621ae](https://linux-hardware.org/?probe=68ee7621ae) | Mar 24, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [793cd99221](https://linux-hardware.org/?probe=793cd99221) | Mar 23, 2024 |
| SYWZ          | S210HA Series               | Desktop     | [0adb0f4432](https://linux-hardware.org/?probe=0adb0f4432) | Mar 23, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [04f792e4fe](https://linux-hardware.org/?probe=04f792e4fe) | Mar 23, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [4629f81fff](https://linux-hardware.org/?probe=4629f81fff) | Mar 23, 2024 |
| HP            | 15                          | Notebook    | [d44f6d6211](https://linux-hardware.org/?probe=d44f6d6211) | Mar 23, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b0092a8e43](https://linux-hardware.org/?probe=b0092a8e43) | Mar 23, 2024 |
| Acer          | RS880M05                    | Desktop     | [d4f039d786](https://linux-hardware.org/?probe=d4f039d786) | Mar 23, 2024 |
| Biostar       | B450MX-S                    | Desktop     | [6afcf0e275](https://linux-hardware.org/?probe=6afcf0e275) | Mar 23, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [ea8c9e4fdb](https://linux-hardware.org/?probe=ea8c9e4fdb) | Mar 23, 2024 |
| SYWZ          | S210HA Series               | Desktop     | [0fbf298970](https://linux-hardware.org/?probe=0fbf298970) | Mar 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a20d8894bd](https://linux-hardware.org/?probe=a20d8894bd) | Mar 23, 2024 |
| HP            | Pavilion 17                 | Notebook    | [80b1ad1d8b](https://linux-hardware.org/?probe=80b1ad1d8b) | Mar 23, 2024 |
| HP            | 8266                        | Desktop     | [df49dd1099](https://linux-hardware.org/?probe=df49dd1099) | Mar 22, 2024 |
| HP            | Drawcia                     | Notebook    | [11b3cbe426](https://linux-hardware.org/?probe=11b3cbe426) | Mar 22, 2024 |
| Dell          | Precision 7560              | Notebook    | [2de886c9c9](https://linux-hardware.org/?probe=2de886c9c9) | Mar 22, 2024 |
| HP            | 82A2                        | Desktop     | [fcb3205539](https://linux-hardware.org/?probe=fcb3205539) | Mar 22, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [df5c12540c](https://linux-hardware.org/?probe=df5c12540c) | Mar 22, 2024 |
| ASUSTek       | PRIME X670-P                | Desktop     | [e3c04a457d](https://linux-hardware.org/?probe=e3c04a457d) | Mar 22, 2024 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [619de50d8d](https://linux-hardware.org/?probe=619de50d8d) | Mar 22, 2024 |
| Google        | Laser14                     | Notebook    | [3bbaadcb60](https://linux-hardware.org/?probe=3bbaadcb60) | Mar 22, 2024 |
| Acer          | Aspire 5315                 | Notebook    | [01f4e47340](https://linux-hardware.org/?probe=01f4e47340) | Mar 22, 2024 |
| Dell          | Inspiron 15 3515            | Notebook    | [b6096d2468](https://linux-hardware.org/?probe=b6096d2468) | Mar 22, 2024 |
| Google        | Stout                       | Notebook    | [0b8bfbcc32](https://linux-hardware.org/?probe=0b8bfbcc32) | Mar 21, 2024 |
| Intel         | D510MO AAE76523-403         | Desktop     | [4017a437d3](https://linux-hardware.org/?probe=4017a437d3) | Mar 21, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [99ff7d5b73](https://linux-hardware.org/?probe=99ff7d5b73) | Mar 21, 2024 |
| Google        | Stout                       | Notebook    | [f6e58b7398](https://linux-hardware.org/?probe=f6e58b7398) | Mar 21, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [ccbeaff8e3](https://linux-hardware.org/?probe=ccbeaff8e3) | Mar 21, 2024 |
| Google        | Stout                       | Notebook    | [e0156c0090](https://linux-hardware.org/?probe=e0156c0090) | Mar 21, 2024 |
| Google        | Stout                       | Notebook    | [c0b128f965](https://linux-hardware.org/?probe=c0b128f965) | Mar 21, 2024 |
| ASRock        | Z77 Pro3                    | Desktop     | [51c0a74384](https://linux-hardware.org/?probe=51c0a74384) | Mar 21, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3597d1a106](https://linux-hardware.org/?probe=3597d1a106) | Mar 21, 2024 |
| Google        | Astronaut                   | Notebook    | [b2e117a773](https://linux-hardware.org/?probe=b2e117a773) | Mar 21, 2024 |
| Google        | Reks                        | Notebook    | [5b8248765d](https://linux-hardware.org/?probe=5b8248765d) | Mar 21, 2024 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [5b4707338f](https://linux-hardware.org/?probe=5b4707338f) | Mar 21, 2024 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [0801a23a0f](https://linux-hardware.org/?probe=0801a23a0f) | Mar 21, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [fa35d836d3](https://linux-hardware.org/?probe=fa35d836d3) | Mar 21, 2024 |
| Lenovo        | ThinkPad T440p              | Notebook    | [39d16a18ec](https://linux-hardware.org/?probe=39d16a18ec) | Mar 21, 2024 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [bbd6d31a0c](https://linux-hardware.org/?probe=bbd6d31a0c) | Mar 21, 2024 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [131fa6deb3](https://linux-hardware.org/?probe=131fa6deb3) | Mar 21, 2024 |
| MSI           | G31TM-P21                   | Desktop     | [da55967c61](https://linux-hardware.org/?probe=da55967c61) | Mar 21, 2024 |
| Gigabyte      | H81ND2H                     | Desktop     | [9b5fecade5](https://linux-hardware.org/?probe=9b5fecade5) | Mar 21, 2024 |
| Dell          | Vostro 5568                 | Notebook    | [bafabe8708](https://linux-hardware.org/?probe=bafabe8708) | Mar 21, 2024 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [558856655f](https://linux-hardware.org/?probe=558856655f) | Mar 21, 2024 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [c92aa3d747](https://linux-hardware.org/?probe=c92aa3d747) | Mar 21, 2024 |
| Dell          | Vostro 5568                 | Notebook    | [e45d89ada7](https://linux-hardware.org/?probe=e45d89ada7) | Mar 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e5613c8592](https://linux-hardware.org/?probe=e5613c8592) | Mar 21, 2024 |
| HONOR         | FRI-FXX                     | Notebook    | [52c0d69000](https://linux-hardware.org/?probe=52c0d69000) | Mar 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e1da52705a](https://linux-hardware.org/?probe=e1da52705a) | Mar 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [99789095cd](https://linux-hardware.org/?probe=99789095cd) | Mar 21, 2024 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [42b75efcf6](https://linux-hardware.org/?probe=42b75efcf6) | Mar 21, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [164452e3b4](https://linux-hardware.org/?probe=164452e3b4) | Mar 21, 2024 |
| Google        | Stout                       | Notebook    | [51ca299022](https://linux-hardware.org/?probe=51ca299022) | Mar 21, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [83fb273295](https://linux-hardware.org/?probe=83fb273295) | Mar 20, 2024 |
| Google        | Stout                       | Notebook    | [930075bd96](https://linux-hardware.org/?probe=930075bd96) | Mar 20, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a8ead75f81](https://linux-hardware.org/?probe=a8ead75f81) | Mar 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [00f9ee02d9](https://linux-hardware.org/?probe=00f9ee02d9) | Mar 20, 2024 |
| ASUSTek       | X756UQ                      | Notebook    | [9557771f1d](https://linux-hardware.org/?probe=9557771f1d) | Mar 20, 2024 |
| Google        | Stout                       | Notebook    | [ed81fe0a4b](https://linux-hardware.org/?probe=ed81fe0a4b) | Mar 20, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [b3bd8d15bb](https://linux-hardware.org/?probe=b3bd8d15bb) | Mar 20, 2024 |
| Google        | Stout                       | Notebook    | [52a0fe0e8f](https://linux-hardware.org/?probe=52a0fe0e8f) | Mar 20, 2024 |
| Google        | Stout                       | Notebook    | [5e43bced95](https://linux-hardware.org/?probe=5e43bced95) | Mar 20, 2024 |
| OEM           | X79G                        | Desktop     | [3e4d82db74](https://linux-hardware.org/?probe=3e4d82db74) | Mar 20, 2024 |
| Acer          | Aspire ES1-111              | Notebook    | [429ee44acd](https://linux-hardware.org/?probe=429ee44acd) | Mar 20, 2024 |
| HP            | Pavilion g6                 | Notebook    | [4d90befad6](https://linux-hardware.org/?probe=4d90befad6) | Mar 20, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [0022401c37](https://linux-hardware.org/?probe=0022401c37) | Mar 20, 2024 |
| Intel         | H55                         | Desktop     | [bb1c373ea6](https://linux-hardware.org/?probe=bb1c373ea6) | Mar 20, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [1aab338075](https://linux-hardware.org/?probe=1aab338075) | Mar 20, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [d6dfd879ee](https://linux-hardware.org/?probe=d6dfd879ee) | Mar 20, 2024 |
| HP            | Pavilion Plus Laptop 14z... | Notebook    | [0b0ad40c3d](https://linux-hardware.org/?probe=0b0ad40c3d) | Mar 20, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [f1e5e55e2c](https://linux-hardware.org/?probe=f1e5e55e2c) | Mar 20, 2024 |
| Alienware     | 17 R4                       | Notebook    | [a89397f827](https://linux-hardware.org/?probe=a89397f827) | Mar 20, 2024 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [6d5c05f0a7](https://linux-hardware.org/?probe=6d5c05f0a7) | Mar 20, 2024 |
| HP            | ProBook 440 G6              | Notebook    | [15167e6cda](https://linux-hardware.org/?probe=15167e6cda) | Mar 19, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [9f6517d4ce](https://linux-hardware.org/?probe=9f6517d4ce) | Mar 19, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [2a287a57dd](https://linux-hardware.org/?probe=2a287a57dd) | Mar 19, 2024 |
| Dell          | Latitude E7440              | Notebook    | [c39e459211](https://linux-hardware.org/?probe=c39e459211) | Mar 19, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [febfdac13f](https://linux-hardware.org/?probe=febfdac13f) | Mar 19, 2024 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [5213638a3c](https://linux-hardware.org/?probe=5213638a3c) | Mar 19, 2024 |
| Dell          | Latitude E7440              | Notebook    | [e6fabe11b0](https://linux-hardware.org/?probe=e6fabe11b0) | Mar 19, 2024 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [d2b4d77618](https://linux-hardware.org/?probe=d2b4d77618) | Mar 19, 2024 |
| Lenovo        | Yoga 7 14IAL7 82QE          | Convertible | [b6cb7d7ec1](https://linux-hardware.org/?probe=b6cb7d7ec1) | Mar 19, 2024 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [56aa7a5265](https://linux-hardware.org/?probe=56aa7a5265) | Mar 19, 2024 |
| Acer          | Nitro AN515-43              | Notebook    | [85aae083ad](https://linux-hardware.org/?probe=85aae083ad) | Mar 19, 2024 |
| HP            | Notebook                    | Notebook    | [5790810149](https://linux-hardware.org/?probe=5790810149) | Mar 19, 2024 |
| Lenovo        | ThinkPad T480s 20L8S9DL0... | Notebook    | [0df7e53a5b](https://linux-hardware.org/?probe=0df7e53a5b) | Mar 19, 2024 |
| Microsoft     | Surface Pro 6               | Tablet      | [88197088cf](https://linux-hardware.org/?probe=88197088cf) | Mar 18, 2024 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [64e69c2ba1](https://linux-hardware.org/?probe=64e69c2ba1) | Mar 18, 2024 |
| HP            | EliteBook 745 G3            | Notebook    | [505719d41e](https://linux-hardware.org/?probe=505719d41e) | Mar 18, 2024 |
| HP            | EliteBook 745 G3            | Notebook    | [612e881108](https://linux-hardware.org/?probe=612e881108) | Mar 18, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [7d09ef62cc](https://linux-hardware.org/?probe=7d09ef62cc) | Mar 18, 2024 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6ebf6d5c87](https://linux-hardware.org/?probe=6ebf6d5c87) | Mar 18, 2024 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [a4f5cd90b3](https://linux-hardware.org/?probe=a4f5cd90b3) | Mar 18, 2024 |
| Dell          | Latitude E7440              | Notebook    | [274a06f022](https://linux-hardware.org/?probe=274a06f022) | Mar 18, 2024 |
| Intel         | H61 V1.1                    | Desktop     | [eb0d3daea7](https://linux-hardware.org/?probe=eb0d3daea7) | Mar 18, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [86302bbd71](https://linux-hardware.org/?probe=86302bbd71) | Mar 18, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [a13b1aaa4d](https://linux-hardware.org/?probe=a13b1aaa4d) | Mar 18, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [79eb548cbc](https://linux-hardware.org/?probe=79eb548cbc) | Mar 18, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [0a5c9e24b5](https://linux-hardware.org/?probe=0a5c9e24b5) | Mar 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [d6d2c95a7a](https://linux-hardware.org/?probe=d6d2c95a7a) | Mar 17, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [b187be84a4](https://linux-hardware.org/?probe=b187be84a4) | Mar 17, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [030fe7cb7a](https://linux-hardware.org/?probe=030fe7cb7a) | Mar 17, 2024 |
| HP            | ZBook 15 G3                 | Notebook    | [d565c68c67](https://linux-hardware.org/?probe=d565c68c67) | Mar 17, 2024 |
| ASUSTek       | ROG GU501GM                 | Notebook    | [6a2786c694](https://linux-hardware.org/?probe=6a2786c694) | Mar 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [d02fd3d860](https://linux-hardware.org/?probe=d02fd3d860) | Mar 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [3bd52dc634](https://linux-hardware.org/?probe=3bd52dc634) | Mar 17, 2024 |
| Unknown       | 1.0                         | Desktop     | [95713f1f4b](https://linux-hardware.org/?probe=95713f1f4b) | Mar 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [35209a450e](https://linux-hardware.org/?probe=35209a450e) | Mar 17, 2024 |
| HP            | 2B38                        | Desktop     | [b0457c0f4a](https://linux-hardware.org/?probe=b0457c0f4a) | Mar 17, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [3c3545a34f](https://linux-hardware.org/?probe=3c3545a34f) | Mar 17, 2024 |
| Intel         | DB43LD AAE60577-204         | Desktop     | [9b9fab3f17](https://linux-hardware.org/?probe=9b9fab3f17) | Mar 17, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [75309e4a5b](https://linux-hardware.org/?probe=75309e4a5b) | Mar 17, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [0f456e0a91](https://linux-hardware.org/?probe=0f456e0a91) | Mar 17, 2024 |
| ASUSTek       | Zenbook UP6502ZD_UP6502Z... | Convertible | [e27178a011](https://linux-hardware.org/?probe=e27178a011) | Mar 17, 2024 |
| Dell          | Latitude 7490               | Notebook    | [2d06821968](https://linux-hardware.org/?probe=2d06821968) | Mar 17, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e8e05c9b6f](https://linux-hardware.org/?probe=e8e05c9b6f) | Mar 17, 2024 |
| HP            | EliteBook 745 G3            | Notebook    | [b881a5b337](https://linux-hardware.org/?probe=b881a5b337) | Mar 17, 2024 |
| HP            | EliteBook 745 G3            | Notebook    | [988b3c3ebc](https://linux-hardware.org/?probe=988b3c3ebc) | Mar 17, 2024 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [f0c6f9e60c](https://linux-hardware.org/?probe=f0c6f9e60c) | Mar 17, 2024 |
| HP            | EliteBook 745 G3            | Notebook    | [ff007ff23e](https://linux-hardware.org/?probe=ff007ff23e) | Mar 16, 2024 |
| HP            | EliteBook 745 G3            | Notebook    | [18bed734d1](https://linux-hardware.org/?probe=18bed734d1) | Mar 16, 2024 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [a781e10290](https://linux-hardware.org/?probe=a781e10290) | Mar 16, 2024 |
| Acer          | Aspire A114-31              | Notebook    | [899c6f43f5](https://linux-hardware.org/?probe=899c6f43f5) | Mar 16, 2024 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [e4991581c4](https://linux-hardware.org/?probe=e4991581c4) | Mar 16, 2024 |
| Google        | Lick                        | Notebook    | [38f3dae4fc](https://linux-hardware.org/?probe=38f3dae4fc) | Mar 16, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [b51fd9bc2b](https://linux-hardware.org/?probe=b51fd9bc2b) | Mar 16, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [a3a01d0403](https://linux-hardware.org/?probe=a3a01d0403) | Mar 16, 2024 |
| Dell          | Latitude 5480               | Notebook    | [84cc86e4f5](https://linux-hardware.org/?probe=84cc86e4f5) | Mar 16, 2024 |
| AZW           | GK mini                     | Desktop     | [afe9ed8283](https://linux-hardware.org/?probe=afe9ed8283) | Mar 16, 2024 |
| Lenovo        | IdeaPadFlex 5 14IRU8 82Y... | Convertible | [3878433152](https://linux-hardware.org/?probe=3878433152) | Mar 16, 2024 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [291b222709](https://linux-hardware.org/?probe=291b222709) | Mar 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e05236c14d](https://linux-hardware.org/?probe=e05236c14d) | Mar 16, 2024 |
| Dell          | XPS 17 9730                 | Notebook    | [eee424c6c6](https://linux-hardware.org/?probe=eee424c6c6) | Mar 16, 2024 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [250f1255fd](https://linux-hardware.org/?probe=250f1255fd) | Mar 16, 2024 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b24d70c129](https://linux-hardware.org/?probe=b24d70c129) | Mar 16, 2024 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [5883806cc2](https://linux-hardware.org/?probe=5883806cc2) | Mar 16, 2024 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [d54d058ff4](https://linux-hardware.org/?probe=d54d058ff4) | Mar 16, 2024 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [048f588fac](https://linux-hardware.org/?probe=048f588fac) | Mar 16, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [17aa01dfc2](https://linux-hardware.org/?probe=17aa01dfc2) | Mar 16, 2024 |
| Dell          | Latitude E6320              | Notebook    | [3dfd6b80a4](https://linux-hardware.org/?probe=3dfd6b80a4) | Mar 15, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [12ebbdd41a](https://linux-hardware.org/?probe=12ebbdd41a) | Mar 15, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [d63edacb71](https://linux-hardware.org/?probe=d63edacb71) | Mar 15, 2024 |
| Microsoft     | Surface Laptop              | Tablet      | [f35f1a27c3](https://linux-hardware.org/?probe=f35f1a27c3) | Mar 15, 2024 |
| Microsoft     | Surface Laptop              | Tablet      | [9d6aaa7ef0](https://linux-hardware.org/?probe=9d6aaa7ef0) | Mar 15, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e88369fa4d](https://linux-hardware.org/?probe=e88369fa4d) | Mar 15, 2024 |
| GPD           | P3 MAX                      | Notebook    | [2e933fa77d](https://linux-hardware.org/?probe=2e933fa77d) | Mar 15, 2024 |
| Dell          | Latitude E7440              | Notebook    | [5d4aea2b82](https://linux-hardware.org/?probe=5d4aea2b82) | Mar 15, 2024 |
| Micro Comp... | Venus series                | Notebook    | [ffb53207eb](https://linux-hardware.org/?probe=ffb53207eb) | Mar 15, 2024 |
| Dell          | Latitude E7440              | Notebook    | [c9db9548cf](https://linux-hardware.org/?probe=c9db9548cf) | Mar 15, 2024 |
| Dell          | Latitude E7440              | Notebook    | [79365ef1b3](https://linux-hardware.org/?probe=79365ef1b3) | Mar 15, 2024 |
| Dell          | Latitude E7440              | Notebook    | [373307ea06](https://linux-hardware.org/?probe=373307ea06) | Mar 15, 2024 |
| Dell          | Latitude E7440              | Notebook    | [702daa8fd3](https://linux-hardware.org/?probe=702daa8fd3) | Mar 15, 2024 |
| Dell          | Latitude E7440              | Notebook    | [5e6e833281](https://linux-hardware.org/?probe=5e6e833281) | Mar 15, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3f302731ea](https://linux-hardware.org/?probe=3f302731ea) | Mar 15, 2024 |
| Dell          | Latitude E7440              | Notebook    | [db5d402e08](https://linux-hardware.org/?probe=db5d402e08) | Mar 15, 2024 |
| Dell          | Latitude E7440              | Notebook    | [796f48ebbb](https://linux-hardware.org/?probe=796f48ebbb) | Mar 15, 2024 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [ba8c04d50e](https://linux-hardware.org/?probe=ba8c04d50e) | Mar 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9170891a99](https://linux-hardware.org/?probe=9170891a99) | Mar 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [1da99640ba](https://linux-hardware.org/?probe=1da99640ba) | Mar 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [00e6d44f41](https://linux-hardware.org/?probe=00e6d44f41) | Mar 15, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [ae670d563a](https://linux-hardware.org/?probe=ae670d563a) | Mar 15, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1QU0... | Notebook    | [0aeadde0d2](https://linux-hardware.org/?probe=0aeadde0d2) | Mar 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [96f5ad9c2b](https://linux-hardware.org/?probe=96f5ad9c2b) | Mar 15, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f6947e3cb1](https://linux-hardware.org/?probe=f6947e3cb1) | Mar 15, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [103edd2219](https://linux-hardware.org/?probe=103edd2219) | Mar 15, 2024 |
| Dell          | Latitude E7440              | Notebook    | [d294aa428c](https://linux-hardware.org/?probe=d294aa428c) | Mar 14, 2024 |
| Dell          | Latitude E6320              | Notebook    | [b889e2e692](https://linux-hardware.org/?probe=b889e2e692) | Mar 14, 2024 |
| Lenovo        | G50-80 80L0                 | Notebook    | [995f47afbb](https://linux-hardware.org/?probe=995f47afbb) | Mar 14, 2024 |
| Dell          | Latitude E6420              | Notebook    | [bd0e21e6e8](https://linux-hardware.org/?probe=bd0e21e6e8) | Mar 14, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [af8cc61afe](https://linux-hardware.org/?probe=af8cc61afe) | Mar 14, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ba3ec85a8c](https://linux-hardware.org/?probe=ba3ec85a8c) | Mar 14, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d9dcb9a8f4](https://linux-hardware.org/?probe=d9dcb9a8f4) | Mar 14, 2024 |
| Dell          | Latitude E6420              | Notebook    | [b8474e8eaa](https://linux-hardware.org/?probe=b8474e8eaa) | Mar 14, 2024 |
| Dell          | Latitude E6420              | Notebook    | [94b6aa0ebf](https://linux-hardware.org/?probe=94b6aa0ebf) | Mar 14, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [91890298e9](https://linux-hardware.org/?probe=91890298e9) | Mar 14, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1c8ceb24a1](https://linux-hardware.org/?probe=1c8ceb24a1) | Mar 14, 2024 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [721d5ddfe6](https://linux-hardware.org/?probe=721d5ddfe6) | Mar 14, 2024 |
| Intel         | H81                         | Desktop     | [e7d551c959](https://linux-hardware.org/?probe=e7d551c959) | Mar 14, 2024 |
| Lenovo        | G565 20071                  | Notebook    | [53c4aa7525](https://linux-hardware.org/?probe=53c4aa7525) | Mar 14, 2024 |
| Lenovo        | Legion Pro 7 16ARX8H 82W... | Notebook    | [ec652b3d4e](https://linux-hardware.org/?probe=ec652b3d4e) | Mar 14, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [33164bcce1](https://linux-hardware.org/?probe=33164bcce1) | Mar 14, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [3598522f0a](https://linux-hardware.org/?probe=3598522f0a) | Mar 13, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [4137469fd5](https://linux-hardware.org/?probe=4137469fd5) | Mar 13, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [6cba9dc6dd](https://linux-hardware.org/?probe=6cba9dc6dd) | Mar 13, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [85dd7ddf92](https://linux-hardware.org/?probe=85dd7ddf92) | Mar 13, 2024 |
| HP            | ProBook 6450b               | Notebook    | [71e2ba1acd](https://linux-hardware.org/?probe=71e2ba1acd) | Mar 13, 2024 |
| Radxa         | ROCK 5B                     | Soc         | [196e6ef733](https://linux-hardware.org/?probe=196e6ef733) | Mar 13, 2024 |
| Google        | Reks                        | Notebook    | [8e0c35418b](https://linux-hardware.org/?probe=8e0c35418b) | Mar 13, 2024 |
| HP            | ProBook 6450b               | Notebook    | [758d6b94cf](https://linux-hardware.org/?probe=758d6b94cf) | Mar 13, 2024 |
| HP            | ProBook 6450b               | Notebook    | [79851a4f52](https://linux-hardware.org/?probe=79851a4f52) | Mar 13, 2024 |
| Gigabyte      | H81M-S2V                    | Desktop     | [951c32a197](https://linux-hardware.org/?probe=951c32a197) | Mar 13, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [d75eaeebc0](https://linux-hardware.org/?probe=d75eaeebc0) | Mar 13, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [d72491ebac](https://linux-hardware.org/?probe=d72491ebac) | Mar 12, 2024 |
| HP            | Pavilion dm3                | Notebook    | [0f22d77b49](https://linux-hardware.org/?probe=0f22d77b49) | Mar 12, 2024 |
| Intel         | X79G-A V2.0                 | Desktop     | [87e5ff547d](https://linux-hardware.org/?probe=87e5ff547d) | Mar 12, 2024 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [77f28d5d35](https://linux-hardware.org/?probe=77f28d5d35) | Mar 12, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [5391520be0](https://linux-hardware.org/?probe=5391520be0) | Mar 12, 2024 |
| Lenovo        | B590 62742BG                | Notebook    | [5e3e316020](https://linux-hardware.org/?probe=5e3e316020) | Mar 12, 2024 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [3bb66ce50a](https://linux-hardware.org/?probe=3bb66ce50a) | Mar 12, 2024 |
| Lenovo        | ThinkPad Edge E431 62774... | Notebook    | [4055861a67](https://linux-hardware.org/?probe=4055861a67) | Mar 12, 2024 |
| Lenovo        | ThinkPad L540 20AVA05CJP    | Notebook    | [ac69dd4e65](https://linux-hardware.org/?probe=ac69dd4e65) | Mar 12, 2024 |
| IP3 Tech      | GB3                         | Mini pc     | [b396284786](https://linux-hardware.org/?probe=b396284786) | Mar 12, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ff6c1aab7d](https://linux-hardware.org/?probe=ff6c1aab7d) | Mar 12, 2024 |
| ASRock        | ConRoe1333-DVI/H            | Desktop     | [568d966b3f](https://linux-hardware.org/?probe=568d966b3f) | Mar 12, 2024 |
| ASUSTek       | P8Z77-M                     | Desktop     | [9b5be8dd07](https://linux-hardware.org/?probe=9b5be8dd07) | Mar 12, 2024 |
| Dell          | Latitude 5401               | Notebook    | [b68db5aef2](https://linux-hardware.org/?probe=b68db5aef2) | Mar 12, 2024 |
| Dell          | 0RCPW3 A03                  | Desktop     | [4fcaa7c300](https://linux-hardware.org/?probe=4fcaa7c300) | Mar 12, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [d928c71a48](https://linux-hardware.org/?probe=d928c71a48) | Mar 12, 2024 |
| GEEKOM        | Mini IT13                   | Desktop     | [945ed05c48](https://linux-hardware.org/?probe=945ed05c48) | Mar 11, 2024 |
| Huanan        | X99-TF V3.0 JX              | Desktop     | [23c5dd18e5](https://linux-hardware.org/?probe=23c5dd18e5) | Mar 11, 2024 |
| Dell          | Latitude 3490               | Notebook    | [ac7317cebc](https://linux-hardware.org/?probe=ac7317cebc) | Mar 11, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [d0c902f508](https://linux-hardware.org/?probe=d0c902f508) | Mar 11, 2024 |
| Lenovo        | ThinkPad L540 20AVA05CJP    | Notebook    | [b38dfb0116](https://linux-hardware.org/?probe=b38dfb0116) | Mar 11, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [10c1897017](https://linux-hardware.org/?probe=10c1897017) | Mar 11, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [f18d080090](https://linux-hardware.org/?probe=f18d080090) | Mar 11, 2024 |
| Star Labs     | StarBook                    | Notebook    | [6dfcd28891](https://linux-hardware.org/?probe=6dfcd28891) | Mar 11, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f17a5b4720](https://linux-hardware.org/?probe=f17a5b4720) | Mar 11, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [2581c54872](https://linux-hardware.org/?probe=2581c54872) | Mar 11, 2024 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e350a0f21a](https://linux-hardware.org/?probe=e350a0f21a) | Mar 10, 2024 |
| Inventec      | DQ Class A02                | Desktop     | [37d048c93a](https://linux-hardware.org/?probe=37d048c93a) | Mar 10, 2024 |
| ASRockRack    | B550D4U-2T R1.00            | Desktop     | [79de662be3](https://linux-hardware.org/?probe=79de662be3) | Mar 10, 2024 |
| Acer          | TravelMate 5730             | Notebook    | [06d52ce1c4](https://linux-hardware.org/?probe=06d52ce1c4) | Mar 10, 2024 |
| Insyde        | Purley                      | Server      | [85f94eb166](https://linux-hardware.org/?probe=85f94eb166) | Mar 10, 2024 |
| Supermicro    | X9DR3-F                     | Desktop     | [4f5a5a1b7c](https://linux-hardware.org/?probe=4f5a5a1b7c) | Mar 10, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1eecb13729](https://linux-hardware.org/?probe=1eecb13729) | Mar 10, 2024 |
| Lenovo        | XiaoXinPro 14 APH8 83AM     | Notebook    | [c8304d2f20](https://linux-hardware.org/?probe=c8304d2f20) | Mar 09, 2024 |
| Acer          | Aspire A114-31              | Notebook    | [2af6274287](https://linux-hardware.org/?probe=2af6274287) | Mar 09, 2024 |
| Google        | Lillipup                    | Notebook    | [3e55a8fd00](https://linux-hardware.org/?probe=3e55a8fd00) | Mar 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [79ca53b90b](https://linux-hardware.org/?probe=79ca53b90b) | Mar 09, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [26a448f763](https://linux-hardware.org/?probe=26a448f763) | Mar 09, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [caa3411c2c](https://linux-hardware.org/?probe=caa3411c2c) | Mar 09, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [3890a0c9b5](https://linux-hardware.org/?probe=3890a0c9b5) | Mar 09, 2024 |
| MSI           | Stealth GS77 12UH           | Notebook    | [892a9a5e88](https://linux-hardware.org/?probe=892a9a5e88) | Mar 09, 2024 |
| System76      | Thelio thelio-r2            | Desktop     | [f991b0cab8](https://linux-hardware.org/?probe=f991b0cab8) | Mar 09, 2024 |
| Clevo         | W55xEU                      | Notebook    | [0ee8318d3f](https://linux-hardware.org/?probe=0ee8318d3f) | Mar 09, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | Notebook    | [d2bc937dc1](https://linux-hardware.org/?probe=d2bc937dc1) | Mar 09, 2024 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [0d827eec25](https://linux-hardware.org/?probe=0d827eec25) | Mar 09, 2024 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [abc44a83ff](https://linux-hardware.org/?probe=abc44a83ff) | Mar 09, 2024 |
| Intel         | BQM5                        | Desktop     | [36ca4efb8c](https://linux-hardware.org/?probe=36ca4efb8c) | Mar 09, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [3080527b19](https://linux-hardware.org/?probe=3080527b19) | Mar 09, 2024 |
| ASUSTek       | Q502LAB                     | Notebook    | [00512805b9](https://linux-hardware.org/?probe=00512805b9) | Mar 09, 2024 |
| MSI           | X99S SLI PLUS               | Desktop     | [310dce5320](https://linux-hardware.org/?probe=310dce5320) | Mar 09, 2024 |
| Dell          | Inspiron 11-3168            | Notebook    | [6f4fde28c7](https://linux-hardware.org/?probe=6f4fde28c7) | Mar 08, 2024 |
| Dell          | Inspiron 11-3168            | Notebook    | [fc26237c72](https://linux-hardware.org/?probe=fc26237c72) | Mar 08, 2024 |
| HP            | Notebook                    | Notebook    | [17c617ba03](https://linux-hardware.org/?probe=17c617ba03) | Mar 08, 2024 |
| HP            | Notebook                    | Notebook    | [73813f7d70](https://linux-hardware.org/?probe=73813f7d70) | Mar 08, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [b7ead3f3ea](https://linux-hardware.org/?probe=b7ead3f3ea) | Mar 08, 2024 |
| ASRock        | D1800M                      | Desktop     | [9098eafea6](https://linux-hardware.org/?probe=9098eafea6) | Mar 08, 2024 |
| Dell          | Inspiron 3593               | Notebook    | [e5931414ce](https://linux-hardware.org/?probe=e5931414ce) | Mar 08, 2024 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [c58d7ff7b8](https://linux-hardware.org/?probe=c58d7ff7b8) | Mar 08, 2024 |
| Dell          | 0M3918                      | Desktop     | [28a616adee](https://linux-hardware.org/?probe=28a616adee) | Mar 08, 2024 |
| Dell          | 0M3918                      | Desktop     | [4f73764337](https://linux-hardware.org/?probe=4f73764337) | Mar 08, 2024 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [343dc1071f](https://linux-hardware.org/?probe=343dc1071f) | Mar 08, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f5af865ffc](https://linux-hardware.org/?probe=f5af865ffc) | Mar 07, 2024 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [004da047e8](https://linux-hardware.org/?probe=004da047e8) | Mar 07, 2024 |
| Apple         | MacBook7,1                  | Notebook    | [942bc3410e](https://linux-hardware.org/?probe=942bc3410e) | Mar 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [f582976129](https://linux-hardware.org/?probe=f582976129) | Mar 07, 2024 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [f25ce70502](https://linux-hardware.org/?probe=f25ce70502) | Mar 07, 2024 |
| Acer          | One 14 Z8-415               | Notebook    | [369734aa1f](https://linux-hardware.org/?probe=369734aa1f) | Mar 07, 2024 |
| Acer          | One 14 Z8-415               | Notebook    | [6fce03c633](https://linux-hardware.org/?probe=6fce03c633) | Mar 07, 2024 |
| Dell          | Latitude 5440               | Notebook    | [555765316a](https://linux-hardware.org/?probe=555765316a) | Mar 07, 2024 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [d79cbc134e](https://linux-hardware.org/?probe=d79cbc134e) | Mar 07, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [644841f4df](https://linux-hardware.org/?probe=644841f4df) | Mar 07, 2024 |
| HP            | 1589                        | Desktop     | [624b940448](https://linux-hardware.org/?probe=624b940448) | Mar 07, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f9ed40afc2](https://linux-hardware.org/?probe=f9ed40afc2) | Mar 06, 2024 |
| Alienware     | 17 R4                       | Notebook    | [f3eab6ab63](https://linux-hardware.org/?probe=f3eab6ab63) | Mar 06, 2024 |
| Apple         | MacBook7,1                  | Notebook    | [e6500f99bb](https://linux-hardware.org/?probe=e6500f99bb) | Mar 06, 2024 |
| Unknown       | Unknown                     | Soc         | [52fda62c9f](https://linux-hardware.org/?probe=52fda62c9f) | Mar 06, 2024 |
| ASUSTek       | P8Z77-M                     | Desktop     | [031b9032f6](https://linux-hardware.org/?probe=031b9032f6) | Mar 06, 2024 |
| Hardkernel    | ODROID-H3                   | Desktop     | [175145ad7c](https://linux-hardware.org/?probe=175145ad7c) | Mar 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dadfd2990c](https://linux-hardware.org/?probe=dadfd2990c) | Mar 06, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9ac6447d8f](https://linux-hardware.org/?probe=9ac6447d8f) | Mar 06, 2024 |
| HP            | Pavilion dv6000 (GH906EA... | Notebook    | [be0ca4a00c](https://linux-hardware.org/?probe=be0ca4a00c) | Mar 06, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [34c6283f00](https://linux-hardware.org/?probe=34c6283f00) | Mar 05, 2024 |
| HP            | ENVY 15                     | Notebook    | [6f74377b0a](https://linux-hardware.org/?probe=6f74377b0a) | Mar 05, 2024 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [29b9dd14e6](https://linux-hardware.org/?probe=29b9dd14e6) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | Notebook    | [a8c23be08a](https://linux-hardware.org/?probe=a8c23be08a) | Mar 05, 2024 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [3b6afc68c7](https://linux-hardware.org/?probe=3b6afc68c7) | Mar 05, 2024 |
| BESSTAR Te... | HM80                        | Desktop     | [b0dd533b6a](https://linux-hardware.org/?probe=b0dd533b6a) | Mar 05, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [76317bf019](https://linux-hardware.org/?probe=76317bf019) | Mar 05, 2024 |
| Lenovo        | Flex 6-11IGM 81A7           | Convertible | [831e3cc4fd](https://linux-hardware.org/?probe=831e3cc4fd) | Mar 05, 2024 |
| Biostar       | M7MKB                       | Desktop     | [8d1cf151f7](https://linux-hardware.org/?probe=8d1cf151f7) | Mar 05, 2024 |
| Biostar       | M7MKB                       | Desktop     | [bd1260c783](https://linux-hardware.org/?probe=bd1260c783) | Mar 05, 2024 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [888ce42ec2](https://linux-hardware.org/?probe=888ce42ec2) | Mar 04, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [4b55061676](https://linux-hardware.org/?probe=4b55061676) | Mar 04, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [6cb53dc79e](https://linux-hardware.org/?probe=6cb53dc79e) | Mar 04, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7105302b8d](https://linux-hardware.org/?probe=7105302b8d) | Mar 04, 2024 |
| AZW           | Green G5                    | Desktop     | [0d917a5d84](https://linux-hardware.org/?probe=0d917a5d84) | Mar 04, 2024 |
| Acer          | Aspire X3960                | Desktop     | [ac6dc6f4ce](https://linux-hardware.org/?probe=ac6dc6f4ce) | Mar 04, 2024 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [b7775135ef](https://linux-hardware.org/?probe=b7775135ef) | Mar 04, 2024 |
| Lenovo        | ThinkPad P53 20QQS5WG00     | Notebook    | [c9b881db8b](https://linux-hardware.org/?probe=c9b881db8b) | Mar 04, 2024 |
| Lenovo        | 32E1 NOK                    | Desktop     | [f8482cdaa3](https://linux-hardware.org/?probe=f8482cdaa3) | Mar 04, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H50... | Notebook    | [6b1f0885d9](https://linux-hardware.org/?probe=6b1f0885d9) | Mar 04, 2024 |
| Dell          | Latitude 5420 Rugged        | Notebook    | [18acc91a94](https://linux-hardware.org/?probe=18acc91a94) | Mar 03, 2024 |
| Lenovo        | ThinkPad X260 20F5A21WJP    | Notebook    | [51eeb3af20](https://linux-hardware.org/?probe=51eeb3af20) | Mar 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [267b3b9397](https://linux-hardware.org/?probe=267b3b9397) | Mar 03, 2024 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [42a2042f1d](https://linux-hardware.org/?probe=42a2042f1d) | Mar 03, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [f91440705e](https://linux-hardware.org/?probe=f91440705e) | Mar 03, 2024 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [e693b43cc0](https://linux-hardware.org/?probe=e693b43cc0) | Mar 03, 2024 |
| HP            | EliteBook 850 G6            | Notebook    | [20d430b7b1](https://linux-hardware.org/?probe=20d430b7b1) | Mar 03, 2024 |
| Gigabyte      | GA-880GM-USB3L              | Desktop     | [61f2f3738a](https://linux-hardware.org/?probe=61f2f3738a) | Mar 03, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [16e5aeca08](https://linux-hardware.org/?probe=16e5aeca08) | Mar 03, 2024 |
| Gigabyte      | GA-880GM-USB3L              | Desktop     | [83e5cbff40](https://linux-hardware.org/?probe=83e5cbff40) | Mar 03, 2024 |
| Lenovo        | 3181 SDK0J40697 WIN 3305... | Mini pc     | [d7b1a6e8b1](https://linux-hardware.org/?probe=d7b1a6e8b1) | Mar 03, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2e07664ae3](https://linux-hardware.org/?probe=2e07664ae3) | Mar 02, 2024 |
| Lenovo        | ThinkCentre M81 0385A2G     | Desktop     | [f66c00d744](https://linux-hardware.org/?probe=f66c00d744) | Mar 02, 2024 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [eeb2d3dcd6](https://linux-hardware.org/?probe=eeb2d3dcd6) | Mar 02, 2024 |
| Lenovo        | ThinkCentre M81 0385A2G     | Desktop     | [81dc4aff97](https://linux-hardware.org/?probe=81dc4aff97) | Mar 02, 2024 |
| Dell          | Latitude E6330              | Notebook    | [6a84be56da](https://linux-hardware.org/?probe=6a84be56da) | Mar 02, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_12/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 6.1.0-13-amd64        | 555       | 13.34%  |
| 6.1.0-18-amd64        | 468       | 11.25%  |
| 6.1.0-4-amd64         | 348       | 8.37%   |
| 6.1.0-10-amd64        | 307       | 7.38%   |
| 6.1.0-9-amd64         | 299       | 7.19%   |
| 6.1.0-17-amd64        | 293       | 7.04%   |
| 6.1.0-11-amd64        | 293       | 7.04%   |
| 6.1.0-12-amd64        | 212       | 5.1%    |
| 6.1.0-16-amd64        | 187       | 4.5%    |
| 6.1.0-20-amd64        | 130       | 3.13%   |
| 6.1.0-7-amd64         | 92        | 2.21%   |
| 6.1.0-15-amd64        | 85        | 2.04%   |
| 6.1.0-6-amd64         | 44        | 1.06%   |
| 6.5.11-7-pve          | 41        | 0.99%   |
| 6.1.0-3-amd64         | 36        | 0.87%   |
| 6.5.0-0.deb12.4-amd64 | 35        | 0.84%   |
| 6.1.0-5-amd64         | 32        | 0.77%   |
| 6.2.16-3-pve          | 29        | 0.7%    |
| 6.5.11-8-pve          | 25        | 0.6%    |
| 6.4.0-0.deb12.2-amd64 | 24        | 0.58%   |
| 6.6.13+bpo-amd64      | 21        | 0.5%    |
| 6.5.13-3-pve          | 19        | 0.46%   |
| 6.5.11-4-pve          | 19        | 0.46%   |
| 6.2.16-19-pve         | 18        | 0.43%   |
| 6.1.0-8-amd64         | 16        | 0.38%   |
| 6.5.0-0.deb12.1-amd64 | 14        | 0.34%   |
| 6.1.0-14-amd64        | 13        | 0.31%   |
| 6.8.4-2-pve           | 12        | 0.29%   |
| 6.5.13-1-pve          | 11        | 0.26%   |
| 6.2.16-6-pve          | 10        | 0.24%   |
| 6.2.16-15-pve         | 10        | 0.24%   |
| 6.1.0-21-amd64        | 10        | 0.24%   |
| 6.2.16-12-pve         | 9         | 0.22%   |
| 6.1.0-rpi7-rpi-v8     | 8         | 0.19%   |
| 6.6.20+rpt-rpi-v8     | 7         | 0.17%   |
| 6.6.20+rpt-rpi-2712   | 7         | 0.17%   |
| 6.2.16-14-pve         | 7         | 0.17%   |
| 6.1.0-19-amd64        | 7         | 0.17%   |
| 6.1.0-10-686-pae      | 7         | 0.17%   |
| 6.0.0-6-amd64         | 7         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.0    | 3341      | 84.33%  |
| 6.2.16   | 100       | 2.52%   |
| 6.5.11   | 85        | 2.15%   |
| 6.5.0    | 60        | 1.51%   |
| 6.5.13   | 36        | 0.91%   |
| 6.4.0    | 34        | 0.86%   |
| 6.6.13   | 23        | 0.58%   |
| 6.8.4    | 18        | 0.45%   |
| 6.0.0    | 18        | 0.45%   |
| 5.10.0   | 17        | 0.43%   |
| 6.6.20   | 15        | 0.38%   |
| 6.6.28   | 8         | 0.2%    |
| 6.3.0    | 7         | 0.18%   |
| 6.1.63   | 7         | 0.18%   |
| 5.15.0   | 7         | 0.18%   |
| 6.7.9    | 6         | 0.15%   |
| 6.7.4    | 6         | 0.15%   |
| 6.6.0    | 6         | 0.15%   |
| 6.5.3    | 6         | 0.15%   |
| 6.1.21   | 6         | 0.15%   |
| 6.1.11   | 5         | 0.13%   |
| 5.10.160 | 5         | 0.13%   |
| 5.10.113 | 5         | 0.13%   |
| 6.6.10   | 4         | 0.1%    |
| 6.1.74   | 4         | 0.1%    |
| 6.1.38   | 4         | 0.1%    |
| 6.8.1    | 3         | 0.08%   |
| 6.7.0    | 3         | 0.08%   |
| 6.6.2    | 3         | 0.08%   |
| 6.6.11   | 3         | 0.08%   |
| 6.4.3    | 3         | 0.08%   |
| 6.4.2    | 3         | 0.08%   |
| 6.1.69   | 3         | 0.08%   |
| 6.1.52   | 3         | 0.08%   |
| 6.1.42   | 3         | 0.08%   |
| 5.10.110 | 3         | 0.08%   |
| 6.8.7    | 2         | 0.05%   |
| 6.7.7    | 2         | 0.05%   |
| 6.7.2    | 2         | 0.05%   |
| 6.7.10   | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 3392      | 85.96%  |
| 6.5     | 187       | 4.74%   |
| 6.2     | 105       | 2.66%   |
| 6.6     | 75        | 1.9%    |
| 6.4     | 45        | 1.14%   |
| 5.10    | 33        | 0.84%   |
| 6.8     | 28        | 0.71%   |
| 6.7     | 25        | 0.63%   |
| 6.0     | 18        | 0.46%   |
| 6.3     | 15        | 0.38%   |
| 5.15    | 11        | 0.28%   |
| 6       | 3         | 0.08%   |
| 5.19    | 2         | 0.05%   |
| 4.19    | 2         | 0.05%   |
| 4.1     | 2         | 0.05%   |
| 96.5    | 1         | 0.03%   |
| 5.16    | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 3730      | 95.69%  |
| aarch64     | 103       | 2.64%   |
| i686        | 39        | 1%      |
| riscv64     | 12        | 0.31%   |
| armv7l      | 11        | 0.28%   |
| ppc64       | 1         | 0.03%   |
| mips64      | 1         | 0.03%   |
| loongarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 1127      | 28.6%   |
| Unknown           | 1064      | 27.01%  |
| KDE5              | 760       | 19.29%  |
| XFCE              | 357       | 9.06%   |
| X-Cinnamon        | 180       | 4.57%   |
| MATE              | 146       | 3.71%   |
| LXDE              | 53        | 1.35%   |
| LXQt              | 50        | 1.27%   |
| Cinnamon          | 39        | 0.99%   |
| i3                | 31        | 0.79%   |
| GNOME Flashback   | 25        | 0.63%   |
| LXDE-pi-wayfire   | 19        | 0.48%   |
| Openbox           | 15        | 0.38%   |
| GNOME Classic     | 12        | 0.3%    |
| KDE               | 9         | 0.23%   |
| Budgie            | 9         | 0.23%   |
| ICEWM             | 5         | 0.13%   |
| Trinity           | 4         | 0.1%    |
| sway              | 3         | 0.08%   |
| lightdm-xsession  | 3         | 0.08%   |
| GNUstep           | 3         | 0.08%   |
| Enlightenment     | 3         | 0.08%   |
| dwm               | 3         | 0.08%   |
| BunsenLabs        | 3         | 0.08%   |
| awesome           | 3         | 0.08%   |
| x-session-manager | 2         | 0.05%   |
| Phosh:GNOME       | 2         | 0.05%   |
| bspwm             | 2         | 0.05%   |
| xmonad            | 1         | 0.03%   |
| Unity             | 1         | 0.03%   |
| sway:GNOME        | 1         | 0.03%   |
| qtile             | 1         | 0.03%   |
| Pantheon          | 1         | 0.03%   |
| fluxbox           | 1         | 0.03%   |
| Deepin            | 1         | 0.03%   |
| Cutefish          | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1515      | 38.28%  |
| Wayland | 1271      | 32.11%  |
| Unknown | 739       | 18.67%  |
| Tty     | 430       | 10.86%  |
| Web     | 3         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 1797      | 45.62%  |
| GDM3          | 927       | 23.53%  |
| LightDM       | 647       | 16.43%  |
| SDDM          | 526       | 13.35%  |
| LXDM          | 10        | 0.25%   |
| GDM           | 9         | 0.23%   |
| SLiM          | 5         | 0.13%   |
| GREETD        | 4         | 0.1%    |
| XDM           | 3         | 0.08%   |
| TDM           | 3         | 0.08%   |
| NODM          | 3         | 0.08%   |
| Ly            | 3         | 0.08%   |
| WDM           | 1         | 0.03%   |
| DARKDM_ON_TTY | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1530      | 38.96%  |
| ru_RU   | 479       | 12.2%   |
| Unknown | 320       | 8.15%   |
| de_DE   | 247       | 6.29%   |
| fr_FR   | 244       | 6.21%   |
| en_GB   | 208       | 5.3%    |
| pt_BR   | 89        | 2.27%   |
| it_IT   | 87        | 2.22%   |
| es_ES   | 85        | 2.16%   |
| en_CA   | 60        | 1.53%   |
| pl_PL   | 54        | 1.38%   |
| en_AU   | 43        | 1.09%   |
| C       | 39        | 0.99%   |
| en_IN   | 35        | 0.89%   |
| zh_CN   | 28        | 0.71%   |
| sv_SE   | 25        | 0.64%   |
| es_MX   | 21        | 0.53%   |
| nl_NL   | 20        | 0.51%   |
| en_IE   | 19        | 0.48%   |
| de_CH   | 18        | 0.46%   |
| es_AR   | 17        | 0.43%   |
| hu_HU   | 16        | 0.41%   |
| es_CL   | 16        | 0.41%   |
| en_ZA   | 15        | 0.38%   |
| tr_TR   | 11        | 0.28%   |
| de_AT   | 11        | 0.28%   |
| fr_BE   | 10        | 0.25%   |
| fi_FI   | 10        | 0.25%   |
| en_NZ   | 10        | 0.25%   |
| ca_ES   | 10        | 0.25%   |
| cs_CZ   | 9         | 0.23%   |
| es_CO   | 8         | 0.2%    |
| da_DK   | 8         | 0.2%    |
| zh_TW   | 7         | 0.18%   |
| pt_PT   | 7         | 0.18%   |
| es_VE   | 7         | 0.18%   |
| nl_BE   | 6         | 0.15%   |
| nb_NO   | 6         | 0.15%   |
| fr_CA   | 6         | 0.15%   |
| ko_KR   | 5         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2294      | 58.58%  |
| BIOS | 1622      | 41.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2762      | 70.39%  |
| Overlay | 768       | 19.57%  |
| Btrfs   | 181       | 4.61%   |
| Tmpfs   | 83        | 2.12%   |
| Zfs     | 75        | 1.91%   |
| Xfs     | 41        | 1.04%   |
| Ext3    | 7         | 0.18%   |
| Ext2    | 2         | 0.05%   |
| Unknown | 2         | 0.05%   |
| XXXXX   | 1         | 0.03%   |
| Jfs     | 1         | 0.03%   |
| F2fs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2422      | 61.72%  |
| MBR     | 762       | 19.42%  |
| Unknown | 740       | 18.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3432      | 87.15%  |
| Yes       | 506       | 12.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2804      | 71.35%  |
| Yes       | 1126      | 28.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 736       | 18.88%  |
| ASUSTek Computer                     | 571       | 14.65%  |
| Hewlett-Packard                      | 492       | 12.62%  |
| Dell                                 | 376       | 9.65%   |
| Gigabyte Technology                  | 242       | 6.21%   |
| MSI                                  | 179       | 4.59%   |
| Acer                                 | 161       | 4.13%   |
| ASRock                               | 119       | 3.05%   |
| Google                               | 103       | 2.64%   |
| Apple                                | 97        | 2.49%   |
| Unknown                              | 78        | 2%      |
| Intel                                | 76        | 1.95%   |
| Raspberry Pi Foundation              | 66        | 1.69%   |
| Aquarius                             | 37        | 0.95%   |
| Supermicro                           | 33        | 0.85%   |
| HUAWEI                               | 31        | 0.8%    |
| Fujitsu                              | 30        | 0.77%   |
| Samsung Electronics                  | 27        | 0.69%   |
| Toshiba                              | 26        | 0.67%   |
| AZW                                  | 20        | 0.51%   |
| ECS                                  | 17        | 0.44%   |
| Sony                                 | 14        | 0.36%   |
| Biostar                              | 14        | 0.36%   |
| Microsoft                            | 12        | 0.31%   |
| Shenzhen Meigao Electronic Equipment | 10        | 0.26%   |
| Medion                               | 10        | 0.26%   |
| Framework                            | 10        | 0.26%   |
| Foxconn                              | 10        | 0.26%   |
| HONOR                                | 9         | 0.23%   |
| AMI                                  | 9         | 0.23%   |
| Rockchip                             | 8         | 0.21%   |
| Huanan                               | 8         | 0.21%   |
| Alienware                            | 8         | 0.21%   |
| Notebook                             | 7         | 0.18%   |
| BESSTAR Tech                         | 7         | 0.18%   |
| TUXEDO                               | 6         | 0.15%   |
| Timi                                 | 6         | 0.15%   |
| Shuttle                              | 6         | 0.15%   |
| ASRockRack                           | 6         | 0.15%   |
| Panasonic                            | 5         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 108       | 2.77%   |
| Unknown                                   | 92        | 2.36%   |
| ASUS All Series                           | 46        | 1.18%   |
| Google Reks                               | 37        | 0.95%   |
| Aquarius NS585                            | 36        | 0.92%   |
| RPi Raspberry Pi 5 Model B Rev 1.0        | 28        | 0.72%   |
| Lenovo ThinkPad E475 20H40006US           | 22        | 0.56%   |
| HP ProDesk 400 G2.5 SFF                   | 20        | 0.51%   |
| ASRock H470M-HVS                          | 20        | 0.51%   |
| Google Stout                              | 17        | 0.44%   |
| Google Enguarde                           | 16        | 0.41%   |
| ASUS P5QL-CM                              | 15        | 0.38%   |
| Lenovo ThinkCentre M55p 8808D8U           | 14        | 0.36%   |
| Apple MacBookAir7,2                       | 13        | 0.33%   |
| MSI MS-7996                               | 12        | 0.31%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 12        | 0.31%   |
| ASUS PRIME B450M-K                        | 12        | 0.31%   |
| Gigabyte H81M-S2V                         | 11        | 0.28%   |
| Dell Latitude E7440                       | 11        | 0.28%   |
| ASUS S20 K29                              | 11        | 0.28%   |
| Supermicro Super Server                   | 10        | 0.26%   |
| RPi Raspberry Pi 4 Model B Rev 1.5        | 10        | 0.26%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 9         | 0.23%   |
| Lenovo ThinkCentre M79 10JAS05300         | 9         | 0.23%   |
| HP EliteBook 745 G3                       | 9         | 0.23%   |
| Lenovo ThinkPad X230 2325V2Y              | 8         | 0.21%   |
| HP Z440 Workstation                       | 8         | 0.21%   |
| Gigabyte A320M-S2H V2                     | 8         | 0.21%   |
| ECS G31T-M9                               | 8         | 0.21%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 7         | 0.18%   |
| HP ProLiant DL360 Gen9                    | 7         | 0.18%   |
| HP ProDesk 400 G3 SFF                     | 7         | 0.18%   |
| Dell Latitude E6420                       | 7         | 0.18%   |
| AZW SER                                   | 7         | 0.18%   |
| ASUS PRIME A320M-K                        | 7         | 0.18%   |
| ASUS H110M-R                              | 7         | 0.18%   |
| HP ProBook 650 G1                         | 6         | 0.15%   |
| HP ProBook 450 G3                         | 6         | 0.15%   |
| HP Notebook                               | 6         | 0.15%   |
| Gigabyte X570 GAMING X                    | 6         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 441       | 11.31%  |
| Dell Latitude      | 105       | 2.69%   |
| ASUS PRIME         | 93        | 2.39%   |
| Unknown            | 92        | 2.36%   |
| Acer Aspire        | 91        | 2.33%   |
| Lenovo ThinkCentre | 77        | 1.98%   |
| HP EliteBook       | 76        | 1.95%   |
| RPi Raspberry      | 66        | 1.69%   |
| Lenovo IdeaPad     | 66        | 1.69%   |
| HP Pavilion        | 61        | 1.56%   |
| ASUS ROG           | 58        | 1.49%   |
| ASUS Vivobook      | 57        | 1.46%   |
| Dell OptiPlex      | 56        | 1.44%   |
| HP ProBook         | 55        | 1.41%   |
| Dell Inspiron      | 54        | 1.39%   |
| ASUS All           | 46        | 1.18%   |
| Dell XPS           | 44        | 1.13%   |
| Dell PowerEdge     | 44        | 1.13%   |
| HP ProDesk         | 43        | 1.1%    |
| HP Laptop          | 39        | 1%      |
| ASUS TUF           | 39        | 1%      |
| Google Reks        | 37        | 0.95%   |
| Aquarius NS585     | 36        | 0.92%   |
| Lenovo Yoga        | 29        | 0.74%   |
| Dell Precision     | 29        | 0.74%   |
| HP ProLiant        | 27        | 0.69%   |
| Dell Vostro        | 26        | 0.67%   |
| HP EliteDesk       | 22        | 0.56%   |
| Toshiba Satellite  | 21        | 0.54%   |
| HP ENVY            | 20        | 0.51%   |
| ASRock H470M-HVS   | 20        | 0.51%   |
| Acer Veriton       | 19        | 0.49%   |
| Lenovo Legion      | 18        | 0.46%   |
| HP ZBook           | 18        | 0.46%   |
| Gigabyte X570      | 18        | 0.46%   |
| ASUS Zenbook       | 18        | 0.46%   |
| ASUS ASUS          | 18        | 0.46%   |
| HP Compaq          | 17        | 0.44%   |
| Google Stout       | 17        | 0.44%   |
| Gigabyte B450M     | 17        | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 424       | 10.88%  |
| 2022    | 370       | 9.49%   |
| 2021    | 365       | 9.36%   |
| 2019    | 320       | 8.21%   |
| 2023    | 304       | 7.8%    |
| 2018    | 270       | 6.93%   |
| 2012    | 210       | 5.39%   |
| 2014    | 186       | 4.77%   |
| 2017    | 185       | 4.75%   |
| 2013    | 183       | 4.69%   |
| 2016    | 180       | 4.62%   |
| 2015    | 174       | 4.46%   |
| 2011    | 160       | 4.1%    |
| Unknown | 121       | 3.1%    |
| 2008    | 109       | 2.8%    |
| 2010    | 107       | 2.74%   |
| 2009    | 98        | 2.51%   |
| 2007    | 81        | 2.08%   |
| 2024    | 25        | 0.64%   |
| 2005    | 9         | 0.23%   |
| 2006    | 8         | 0.21%   |
| 2004    | 6         | 0.15%   |
| 2002    | 2         | 0.05%   |
| 2000    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1838      | 47.15%  |
| Desktop        | 1454      | 37.3%   |
| Convertible    | 192       | 4.93%   |
| System on chip | 113       | 2.9%    |
| Server         | 112       | 2.87%   |
| Mini pc        | 108       | 2.77%   |
| All in one     | 43        | 1.1%    |
| Tablet         | 33        | 0.85%   |
| Other          | 2         | 0.05%   |
| Phone          | 1         | 0.03%   |
| Stick pc       | 1         | 0.03%   |
| Firewall       | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3608      | 92.3%   |
| Enabled  | 301       | 7.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3789      | 97.2%   |
| Yes  | 109       | 2.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 860       | 21.89%  |
| 16.01-24.0      | 694       | 17.67%  |
| 8.01-16.0       | 677       | 17.24%  |
| 3.01-4.0        | 613       | 15.61%  |
| 32.01-64.0      | 507       | 12.91%  |
| 64.01-256.0     | 261       | 6.64%   |
| 1.01-2.0        | 125       | 3.18%   |
| 24.01-32.0      | 90        | 2.29%   |
| 2.01-3.0        | 47        | 1.2%    |
| More than 256.0 | 25        | 0.64%   |
| 0.51-1.0        | 22        | 0.56%   |
| 0.01-0.5        | 5         | 0.13%   |
| Unknown         | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1051      | 25.75%  |
| 2.01-3.0    | 808       | 19.79%  |
| 4.01-8.0    | 757       | 18.54%  |
| 3.01-4.0    | 540       | 13.23%  |
| 0.51-1.0    | 472       | 11.56%  |
| 8.01-16.0   | 196       | 4.8%    |
| 0.01-0.5    | 125       | 3.06%   |
| 16.01-24.0  | 51        | 1.25%   |
| 24.01-32.0  | 36        | 0.88%   |
| 32.01-64.0  | 24        | 0.59%   |
| 64.01-256.0 | 20        | 0.49%   |
| Unknown     | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2501      | 63.22%  |
| 2      | 826       | 20.88%  |
| 3      | 266       | 6.72%   |
| 4      | 142       | 3.59%   |
| 5      | 55        | 1.39%   |
| 6      | 41        | 1.04%   |
| 0      | 34        | 0.86%   |
| 7      | 18        | 0.46%   |
| 8      | 13        | 0.33%   |
| 10     | 10        | 0.25%   |
| 11     | 7         | 0.18%   |
| 9      | 7         | 0.18%   |
| 14     | 5         | 0.13%   |
| 13     | 4         | 0.1%    |
| 12     | 4         | 0.1%    |
| 17     | 3         | 0.08%   |
| 16     | 3         | 0.08%   |
| 21     | 2         | 0.05%   |
| 19     | 2         | 0.05%   |
| 15     | 2         | 0.05%   |
| 70     | 1         | 0.03%   |
| 41     | 1         | 0.03%   |
| 38     | 1         | 0.03%   |
| 37     | 1         | 0.03%   |
| 33     | 1         | 0.03%   |
| 32     | 1         | 0.03%   |
| 29     | 1         | 0.03%   |
| 27     | 1         | 0.03%   |
| 26     | 1         | 0.03%   |
| 23     | 1         | 0.03%   |
| 18     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3009      | 76.88%  |
| Yes       | 905       | 23.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3298      | 84.43%  |
| No        | 608       | 15.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2715      | 69.49%  |
| No        | 1192      | 30.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2361      | 60.32%  |
| No        | 1553      | 39.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 816       | 20.87%  |
| Russia       | 582       | 14.89%  |
| Germany      | 380       | 9.72%   |
| France       | 277       | 7.09%   |
| Italy        | 142       | 3.63%   |
| Brazil       | 134       | 3.43%   |
| Spain        | 130       | 3.33%   |
| UK           | 122       | 3.12%   |
| Canada       | 112       | 2.87%   |
| Poland       | 95        | 2.43%   |
| Netherlands  | 64        | 1.64%   |
| Sweden       | 59        | 1.51%   |
| Australia    | 53        | 1.36%   |
| India        | 52        | 1.33%   |
| Switzerland  | 48        | 1.23%   |
| China        | 47        | 1.2%    |
| Mexico       | 45        | 1.15%   |
| Austria      | 37        | 0.95%   |
| Finland      | 34        | 0.87%   |
| Belgium      | 34        | 0.87%   |
| Turkey       | 31        | 0.79%   |
| Romania      | 30        | 0.77%   |
| Hungary      | 29        | 0.74%   |
| Czechia      | 29        | 0.74%   |
| Norway       | 28        | 0.72%   |
| Portugal     | 26        | 0.67%   |
| Argentina    | 26        | 0.67%   |
| Greece       | 22        | 0.56%   |
| Chile        | 20        | 0.51%   |
| Indonesia    | 19        | 0.49%   |
| Colombia     | 19        | 0.49%   |
| Denmark      | 18        | 0.46%   |
| South Africa | 16        | 0.41%   |
| Japan        | 15        | 0.38%   |
| Slovakia     | 14        | 0.36%   |
| New Zealand  | 13        | 0.33%   |
| Hong Kong    | 13        | 0.33%   |
| Philippines  | 12        | 0.31%   |
| Belarus      | 12        | 0.31%   |
| Vietnam      | 10        | 0.26%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 345       | 8.63%   |
| Bangor            | 292       | 7.31%   |
| Moscow            | 83        | 2.08%   |
| Roubaix           | 66        | 1.65%   |
| St Petersburg     | 42        | 1.05%   |
| Paris             | 33        | 0.83%   |
| Berlin            | 30        | 0.75%   |
| Toronto           | 24        | 0.6%    |
| Vienna            | 23        | 0.58%   |
| Milan             | 23        | 0.58%   |
| Madrid            | 22        | 0.55%   |
| Frankfurt am Main | 22        | 0.55%   |
| Amsterdam         | 21        | 0.53%   |
| Sydney            | 20        | 0.5%    |
| Bagneux           | 18        | 0.45%   |
| Hamburg           | 17        | 0.43%   |
| Warsaw            | 16        | 0.4%    |
| Saltsjoe-Boo      | 16        | 0.4%    |
| Helsinki          | 16        | 0.4%    |
| Sao Paulo         | 14        | 0.35%   |
| Stockholm         | 13        | 0.33%   |
| Prague            | 13        | 0.33%   |
| Budapest          | 13        | 0.33%   |
| Athens            | 13        | 0.33%   |
| Zurich            | 12        | 0.3%    |
| Perm              | 12        | 0.3%    |
| Istanbul          | 12        | 0.3%    |
| Bucharest         | 12        | 0.3%    |
| Bonn              | 12        | 0.3%    |
| Bogotá           | 12        | 0.3%    |
| Seville           | 11        | 0.28%   |
| Santiago          | 11        | 0.28%   |
| Rio de Janeiro    | 11        | 0.28%   |
| Montreal          | 11        | 0.28%   |
| Mesa              | 11        | 0.28%   |
| Melbourne         | 11        | 0.28%   |
| Dublin            | 11        | 0.28%   |
| Dresden           | 11        | 0.28%   |
| Bengaluru         | 11        | 0.28%   |
| Barcelona         | 11        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 968       | 1391   | 17.43%  |
| WDC                         | 705       | 1173   | 12.69%  |
| Seagate                     | 565       | 1012   | 10.17%  |
| SanDisk                     | 317       | 379    | 5.71%   |
| Kingston                    | 306       | 372    | 5.51%   |
| Toshiba                     | 293       | 427    | 5.27%   |
| Unknown                     | 278       | 342    | 5%      |
| Crucial                     | 267       | 369    | 4.81%   |
| SK hynix                    | 156       | 181    | 2.81%   |
| Intel                       | 122       | 157    | 2.2%    |
| Micron Technology           | 119       | 132    | 2.14%   |
| Hitachi                     | 119       | 165    | 2.14%   |
| A-DATA Technology           | 101       | 138    | 1.82%   |
| HGST                        | 83        | 403    | 1.49%   |
| Unknown                     | 72        | 83     | 1.3%    |
| China                       | 63        | 78     | 1.13%   |
| KIOXIA                      | 54        | 60     | 0.97%   |
| Apple                       | 54        | 67     | 0.97%   |
| Netac                       | 50        | 54     | 0.9%    |
| Kingston Technology Company | 40        | 53     | 0.72%   |
| SPCC                        | 37        | 46     | 0.67%   |
| Transcend                   | 31        | 42     | 0.56%   |
| Silicon Motion              | 28        | 31     | 0.5%    |
| Patriot                     | 28        | 32     | 0.5%    |
| Hewlett-Packard             | 25        | 43     | 0.45%   |
| Phison Electronics          | 24        | 33     | 0.43%   |
| Micron/Crucial Technology   | 23        | 31     | 0.41%   |
| JMicron Technology          | 23        | 24     | 0.41%   |
| Phison                      | 22        | 27     | 0.4%    |
| Intenso                     | 22        | 27     | 0.4%    |
| PNY                         | 21        | 28     | 0.38%   |
| GOODRAM                     | 20        | 41     | 0.36%   |
| LITEON                      | 19        | 21     | 0.34%   |
| SSSTC                       | 18        | 20     | 0.32%   |
| Corsair                     | 18        | 24     | 0.32%   |
| Team                        | 17        | 25     | 0.31%   |
| MAXIO Technology (Hangzhou) | 17        | 18     | 0.31%   |
| Lexar                       | 15        | 16     | 0.27%   |
| KIOXIA-EXCERIA              | 15        | 17     | 0.27%   |
| Apacer                      | 15        | 25     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung MZVLB512HBJQ-000L7 512GB                   | 112       | 1.81%   |
| Unknown                                            | 72        | 1.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 63        | 1.02%   |
| Kingston SA400S37240G 240GB SSD                    | 52        | 0.84%   |
| Kingston SA400S37120G 120GB SSD                    | 48        | 0.78%   |
| Seagate ST500DM002-1BD142 500GB                    | 47        | 0.76%   |
| Kingston SA400S37480G 480GB SSD                    | 44        | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB                     | 37        | 0.6%    |
| A-DATA SU800 512GB SSD                             | 37        | 0.6%    |
| SanDisk NVMe SSD Drive 1TB                         | 35        | 0.57%   |
| Crucial CT480BX500SSD1 480GB                       | 34        | 0.55%   |
| Crucial CT1000MX500SSD1 1TB                        | 32        | 0.52%   |
| Crucial CT500MX500SSD1 500GB                       | 31        | 0.5%    |
| Crucial CT240BX500SSD1 240GB                       | 29        | 0.47%   |
| Samsung SSD 860 EVO 500GB                          | 28        | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 28        | 0.45%   |
| Samsung SSD 980 PRO 1TB                            | 27        | 0.44%   |
| Unknown DF4016  16GB                               | 26        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                       | 26        | 0.42%   |
| Toshiba DT01ACA050 500GB                           | 25        | 0.41%   |
| Netac SSD 240GB                                    | 25        | 0.41%   |
| Unknown MMC Card  64GB                             | 24        | 0.39%   |
| Samsung SSD 850 EVO 250GB                          | 24        | 0.39%   |
| Samsung SSD 870 EVO 500GB                          | 23        | 0.37%   |
| Samsung SSD 860 EVO 250GB                          | 23        | 0.37%   |
| Toshiba DT01ACA100 1TB                             | 22        | 0.36%   |
| SanDisk NVMe SSD Drive 512GB                       | 22        | 0.36%   |
| Samsung SSD 980 1TB                                | 22        | 0.36%   |
| WDC WD5000AAKX-60U6AA0 500GB                       | 21        | 0.34%   |
| Toshiba MQ01ABD100 1TB                             | 21        | 0.34%   |
| Samsung SSD 870 EVO 1TB                            | 21        | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 20        | 0.32%   |
| Seagate ST2000DM008-2FR102 2TB                     | 20        | 0.32%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                | 20        | 0.32%   |
| Toshiba HDWD110 1TB                                | 19        | 0.31%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 19        | 0.31%   |
| Samsung SSD 850 EVO 500GB                          | 19        | 0.31%   |
| WDC WD3200AAJS-00L7A0 320GB                        | 18        | 0.29%   |
| Unknown MMC Card  128GB                            | 18        | 0.29%   |
| Seagate ST1000LM035-1RK172 1TB                     | 18        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 550       | 992    | 33.5%   |
| WDC                 | 531       | 929    | 32.34%  |
| Toshiba             | 218       | 341    | 13.28%  |
| Hitachi             | 119       | 165    | 7.25%   |
| HGST                | 83        | 400    | 5.05%   |
| Samsung Electronics | 36        | 46     | 2.19%   |
| Apple               | 17        | 18     | 1.04%   |
| Unknown             | 16        | 19     | 0.97%   |
| Fujitsu             | 12        | 25     | 0.73%   |
| SABRENT             | 9         | 9      | 0.55%   |
| JMicron Technology  | 9         | 9      | 0.55%   |
| Hewlett-Packard     | 9         | 24     | 0.55%   |
| Maxtor              | 8         | 8      | 0.49%   |
| ASMT                | 4         | 19     | 0.24%   |
| TO Exter            | 3         | 4      | 0.18%   |
| USB                 | 2         | 3      | 0.12%   |
| MARSHAL             | 2         | 2      | 0.12%   |
| Unknown             | 2         | 2      | 0.12%   |
| XrayDisk            | 1         | 1      | 0.06%   |
| WALRAM              | 1         | 1      | 0.06%   |
| Unknown (CF)        | 1         | 1      | 0.06%   |
| SYMTEC              | 1         | 1      | 0.06%   |
| STEC                | 1         | 1      | 0.06%   |
| MARVELL             | 1         | 2      | 0.06%   |
| LaCie               | 1         | 1      | 0.06%   |
| HPE                 | 1         | 1      | 0.06%   |
| HGST HTS            | 1         | 1      | 0.06%   |
| H/W                 | 1         | 7      | 0.06%   |
| Elite               | 1         | 1      | 0.06%   |
| DELLBOSS            | 1         | 2      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 344       | 518    | 19.56%  |
| Kingston            | 231       | 279    | 13.13%  |
| Crucial             | 197       | 266    | 11.2%   |
| SanDisk             | 140       | 165    | 7.96%   |
| WDC                 | 90        | 123    | 5.12%   |
| A-DATA Technology   | 75        | 106    | 4.26%   |
| China               | 62        | 77     | 3.52%   |
| Netac               | 43        | 46     | 2.44%   |
| Intel               | 43        | 59     | 2.44%   |
| Micron Technology   | 32        | 39     | 1.82%   |
| Apple               | 30        | 30     | 1.71%   |
| SK hynix            | 29        | 31     | 1.65%   |
| SPCC                | 28        | 34     | 1.59%   |
| Transcend           | 25        | 36     | 1.42%   |
| Toshiba             | 24        | 28     | 1.36%   |
| Patriot             | 24        | 28     | 1.36%   |
| Intenso             | 22        | 27     | 1.25%   |
| PNY                 | 20        | 27     | 1.14%   |
| GOODRAM             | 18        | 26     | 1.02%   |
| LITEON              | 17        | 19     | 0.97%   |
| OCZ                 | 14        | 15     | 0.8%    |
| Apacer              | 12        | 17     | 0.68%   |
| Unknown             | 11        | 14     | 0.63%   |
| Hewlett-Packard     | 10        | 11     | 0.57%   |
| Fanxiang            | 10        | 14     | 0.57%   |
| Team                | 9         | 15     | 0.51%   |
| Plextor             | 9         | 10     | 0.51%   |
| AMD                 | 8         | 8      | 0.45%   |
| Lexar               | 7         | 7      | 0.4%    |
| Gigabyte Technology | 7         | 8      | 0.4%    |
| XrayDisk            | 6         | 7      | 0.34%   |
| KIOXIA-EXCERIA      | 6         | 6      | 0.34%   |
| Corsair             | 6         | 6      | 0.34%   |
| LITEONIT            | 5         | 6      | 0.28%   |
| KingSpec            | 5         | 6      | 0.28%   |
| Dogfish             | 5         | 5      | 0.28%   |
| Wibtek              | 4         | 4      | 0.23%   |
| Seagate             | 4         | 5      | 0.23%   |
| Innodisk            | 4         | 4      | 0.23%   |
| FORESEE             | 4         | 4      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1695      | 2323   | 33.88%  |
| SSD     | 1550      | 2278   | 30.98%  |
| HDD     | 1390      | 3035   | 27.78%  |
| MMC     | 303       | 372    | 6.06%   |
| Unknown | 65        | 83     | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2431      | 5002   | 52.38%  |
| NVMe | 1689      | 2296   | 36.39%  |
| MMC  | 303       | 372    | 6.53%   |
| SAS  | 218       | 421    | 4.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1769      | 2417   | 56.36%  |
| 0.51-1.0   | 805       | 1269   | 25.65%  |
| 1.01-2.0   | 261       | 522    | 8.31%   |
| 3.01-4.0   | 122       | 302    | 3.89%   |
| 4.01-10.0  | 89        | 556    | 2.84%   |
| 2.01-3.0   | 61        | 101    | 1.94%   |
| 10.01-20.0 | 32        | 146    | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 916       | 23%     |
| 101-250        | 833       | 20.92%  |
| 501-1000       | 526       | 13.21%  |
| Unknown        | 506       | 12.71%  |
| 1001-2000      | 281       | 7.06%   |
| 1-20           | 248       | 6.23%   |
| 51-100         | 219       | 5.5%    |
| More than 3000 | 218       | 5.47%   |
| 21-50          | 139       | 3.49%   |
| 2001-3000      | 96        | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1614      | 39.92%  |
| 21-50          | 515       | 12.74%  |
| Unknown        | 506       | 12.52%  |
| 101-250        | 415       | 10.26%  |
| 51-100         | 346       | 8.56%   |
| 251-500        | 253       | 6.26%   |
| 501-1000       | 164       | 4.06%   |
| 1001-2000      | 119       | 2.94%   |
| More than 3000 | 82        | 2.03%   |
| 2001-3000      | 28        | 0.69%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB          | 14        | 14     | 2.93%   |
| WDC WD3200AAJS-00L7A0 320GB           | 13        | 13     | 2.72%   |
| Seagate ST500DM002-1BD142 500GB       | 10        | 11     | 2.09%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 5         | 5      | 1.05%   |
| Seagate ST3500418AS 500GB             | 5         | 5      | 1.05%   |
| Seagate ST3250410AS 250GB             | 5         | 5      | 1.05%   |
| Seagate ST3160811AS 160GB             | 5         | 5      | 1.05%   |
| Kingston SV300S37A120G 120GB SSD      | 5         | 5      | 1.05%   |
| Hitachi HDS721050CLA362 500GB         | 5         | 7      | 1.05%   |
| HGST HTS725050A7E630 500GB            | 5         | 5      | 1.05%   |
| WDC WD2500AAJS-00L7A0 250GB           | 4         | 4      | 0.84%   |
| Seagate ST9500325AS 500GB             | 4         | 4      | 0.84%   |
| Samsung Electronics SSD 870 EVO 1TB   | 4         | 4      | 0.84%   |
| WDC WD5000LPLX-60ZNTT1 500GB          | 3         | 3      | 0.63%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 3         | 3      | 0.63%   |
| WDC WD20EARS-00MVWB0 2TB              | 3         | 3      | 0.63%   |
| Toshiba MQ01ABF050 500GB              | 3         | 3      | 0.63%   |
| Toshiba MQ01ABD100 1TB                | 3         | 3      | 0.63%   |
| Toshiba DT01ACA200 2TB                | 3         | 8      | 0.63%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 3         | 3      | 0.63%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 3         | 3      | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB        | 3         | 3      | 0.63%   |
| Seagate ST2000DM001-1CH164 2TB        | 3         | 5      | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 0.63%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 5      | 0.63%   |
| SanDisk SSD PLUS 1000GB               | 3         | 3      | 0.63%   |
| Samsung Electronics SSD 870 EVO 500GB | 3         | 3      | 0.63%   |
| Maxtor STM3160815AS 160GB             | 3         | 3      | 0.63%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 3      | 0.63%   |
| Hitachi HTS545050B9A300 500GB         | 3         | 3      | 0.63%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 2         | 3      | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.42%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 2         | 2      | 0.42%   |
| WDC WD5000AAKX-001CA0 500GB           | 2         | 2      | 0.42%   |
| WDC WD40EFRX-68N32N0 4TB              | 2         | 4      | 0.42%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2         | 2      | 0.42%   |
| WDC WD2500AAKS-00VSA0 250GB           | 2         | 3      | 0.42%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 2      | 0.42%   |
| WDC WD20EARX-00PASB0 2TB              | 2         | 3      | 0.42%   |
| WDC WD2002FAEX-007BA0 2TB             | 2         | 2      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 128       | 170    | 27.77%  |
| Seagate             | 105       | 125    | 22.78%  |
| Samsung Electronics | 42        | 50     | 9.11%   |
| Hitachi             | 30        | 38     | 6.51%   |
| Toshiba             | 24        | 29     | 5.21%   |
| SK hynix            | 18        | 19     | 3.9%    |
| Intel               | 17        | 19     | 3.69%   |
| HGST                | 16        | 17     | 3.47%   |
| Kingston            | 12        | 12     | 2.6%    |
| SanDisk             | 10        | 10     | 2.17%   |
| Crucial             | 9         | 10     | 1.95%   |
| Micron Technology   | 7         | 8      | 1.52%   |
| Maxtor              | 5         | 5      | 1.08%   |
| Apple               | 4         | 4      | 0.87%   |
| A-DATA Technology   | 4         | 4      | 0.87%   |
| OCZ                 | 3         | 3      | 0.65%   |
| LITEON              | 3         | 3      | 0.65%   |
| SSSTC               | 2         | 2      | 0.43%   |
| Mushkin             | 2         | 2      | 0.43%   |
| Kimtigo             | 2         | 2      | 0.43%   |
| ASMT                | 2         | 2      | 0.43%   |
| ZHITAI              | 1         | 1      | 0.22%   |
| ShiJi               | 1         | 3      | 0.22%   |
| Netac               | 1         | 2      | 0.22%   |
| Lenovo              | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 1      | 0.22%   |
| JMicron Technology  | 1         | 1      | 0.22%   |
| Intenso             | 1         | 2      | 0.22%   |
| HS-SSD-C100         | 1         | 1      | 0.22%   |
| Hewlett-Packard     | 1         | 2      | 0.22%   |
| HECTRON             | 1         | 1      | 0.22%   |
| Fujitsu             | 1         | 1      | 0.22%   |
| Dogfish             | 1         | 1      | 0.22%   |
| Corsair             | 1         | 1      | 0.22%   |
| China               | 1         | 1      | 0.22%   |
| ADATA Technology    | 1         | 1      | 0.22%   |
| Unknown             | 1         | 1      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 120       | 161    | 38.1%   |
| Seagate             | 105       | 125    | 33.33%  |
| Hitachi             | 30        | 38     | 9.52%   |
| Toshiba             | 24        | 29     | 7.62%   |
| HGST                | 16        | 17     | 5.08%   |
| Samsung Electronics | 10        | 11     | 3.17%   |
| Maxtor              | 5         | 5      | 1.59%   |
| Apple               | 2         | 2      | 0.63%   |
| JMicron Technology  | 1         | 1      | 0.32%   |
| Hewlett-Packard     | 1         | 2      | 0.32%   |
| ASMT                | 1         | 1      | 0.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 287       | 392    | 66.28%  |
| SSD  | 110       | 119    | 25.4%   |
| NVMe | 36        | 44     | 8.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| SK hynix SC308 SATA 512GB SSD | 1         | 1      | 33.33%  |
| Seagate ST3500418ASQ 500GB    | 1         | 1      | 33.33%  |
| Seagate ST31000528AS 1TB      | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 66.67%  |
| SK hynix | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2580      | 5137   | 60.1%   |
| Detected | 1285      | 2395   | 29.93%  |
| Malfunc  | 424       | 555    | 9.88%   |
| Failed   | 3         | 3      | 0.07%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2230      | 44.25%  |
| AMD                              | 673       | 13.35%  |
| Samsung Electronics              | 651       | 12.92%  |
| SanDisk                          | 267       | 5.3%    |
| SK hynix                         | 125       | 2.48%   |
| Kingston Technology Company      | 114       | 2.26%   |
| Micron/Crucial Technology        | 97        | 1.92%   |
| Micron Technology                | 91        | 1.81%   |
| ASMedia Technology               | 85        | 1.69%   |
| Phison Electronics               | 78        | 1.55%   |
| Toshiba America Info Systems     | 61        | 1.21%   |
| KIOXIA                           | 55        | 1.09%   |
| JMicron Technology               | 53        | 1.05%   |
| Silicon Motion                   | 44        | 0.87%   |
| Marvell Technology Group         | 43        | 0.85%   |
| ADATA Technology                 | 43        | 0.85%   |
| Nvidia                           | 42        | 0.83%   |
| Broadcom / LSI                   | 38        | 0.75%   |
| MAXIO Technology (Hangzhou)      | 31        | 0.62%   |
| LSI Logic / Symbios Logic        | 27        | 0.54%   |
| Hewlett-Packard                  | 20        | 0.4%    |
| Solid State Storage Technology   | 18        | 0.36%   |
| Realtek Semiconductor            | 17        | 0.34%   |
| Union Memory (Shenzhen)          | 14        | 0.28%   |
| Adaptec                          | 13        | 0.26%   |
| Shenzhen Longsys Electronics     | 11        | 0.22%   |
| Yangtze Memory Technologies      | 9         | 0.18%   |
| INNOGRIT                         | 9         | 0.18%   |
| Biwin Storage Technology         | 9         | 0.18%   |
| Silicon Image                    | 8         | 0.16%   |
| Apple                            | 7         | 0.14%   |
| VIA Technologies                 | 6         | 0.12%   |
| Transcend                        | 6         | 0.12%   |
| Silicon Integrated Systems [SiS] | 6         | 0.12%   |
| Seagate Technology               | 6         | 0.12%   |
| Netac Technology                 | 4         | 0.08%   |
| Solidigm                         | 3         | 0.06%   |
| Nextorage                        | 3         | 0.06%   |
| Lite-On Technology               | 3         | 0.06%   |
| Shenzhen Shichuangyi Electronics | 2         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 433       | 7.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 305       | 5.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 189       | 3.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 162       | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 136       | 2.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 113       | 2%      |
| Intel Volume Management Device NVMe RAID Controller                            | 110       | 1.94%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 109       | 1.93%   |
| AMD 400 Series Chipset SATA Controller                                         | 106       | 1.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 98        | 1.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 86        | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 82        | 1.45%   |
| Intel Comet Lake SATA AHCI Controller                                          | 77        | 1.36%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 76        | 1.34%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 72        | 1.27%   |
| AMD 500 Series Chipset SATA Controller                                         | 72        | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 70        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 70        | 1.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 60        | 1.06%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 59        | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 55        | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 50        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 50        | 0.88%   |
| AMD 600 Series Chipset SATA Controller                                         | 50        | 0.88%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 49        | 0.87%   |
| Intel Tiger Lake-LP SATA Controller                                            | 48        | 0.85%   |
| Intel SATA Controller [RAID mode]                                              | 47        | 0.83%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 45        | 0.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 45        | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 44        | 0.78%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 44        | 0.78%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 44        | 0.78%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 43        | 0.76%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 41        | 0.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 40        | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 37        | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 36        | 0.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 36        | 0.64%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 34        | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 33        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2523      | 50.91%  |
| NVMe | 1683      | 33.96%  |
| IDE  | 351       | 7.08%   |
| RAID | 335       | 6.76%   |
| SAS  | 54        | 1.09%   |
| SCSI | 10        | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 2857      | 73.28%  |
| AMD               | 911       | 23.36%  |
| ARM               | 107       | 2.74%   |
| Unknown           | 11        | 0.28%   |
| sifive,u74-mc     | 7         | 0.18%   |
| Qualcomm          | 3         | 0.08%   |
| Loongson          | 1         | 0.03%   |
| CHRP IBM,8233-E8B | 1         | 0.03%   |
| CentaurHauls      | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 135       | 3.46%   |
| ARM Processor                                 | 94        | 2.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 54        | 1.38%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 43        | 1.1%    |
| Intel Core i3-9100 CPU @ 3.60GHz              | 37        | 0.95%   |
| Intel 12th Gen Core i5-1235U                  | 33        | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 25        | 0.64%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 24        | 0.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 23        | 0.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 22        | 0.56%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 22        | 0.56%   |
| Intel 12th Gen Core i7-12700H                 | 22        | 0.56%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 22        | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 0.54%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 21        | 0.54%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 21        | 0.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 20        | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 20        | 0.51%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 20        | 0.51%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 20        | 0.51%   |
| AMD Ryzen 5 3600 6-Core Processor             | 20        | 0.51%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 19        | 0.49%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 19        | 0.49%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 19        | 0.49%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 18        | 0.46%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 18        | 0.46%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 18        | 0.46%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 18        | 0.46%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 18        | 0.46%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 18        | 0.46%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.46%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 17        | 0.44%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 17        | 0.44%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 17        | 0.44%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 17        | 0.44%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 17        | 0.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 0.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 0.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 15        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 762       | 19.52%  |
| Intel Core i5           | 629       | 16.12%  |
| Intel Core i7           | 468       | 11.99%  |
| Intel Celeron           | 255       | 6.53%   |
| Intel Core i3           | 249       | 6.38%   |
| AMD Ryzen 5             | 240       | 6.15%   |
| AMD Ryzen 7             | 217       | 5.56%   |
| Intel Xeon              | 197       | 5.05%   |
| Intel Pentium           | 130       | 3.33%   |
| Intel Core 2 Duo        | 115       | 2.95%   |
| AMD Ryzen 9             | 89        | 2.28%   |
| Intel Atom              | 53        | 1.36%   |
| AMD Ryzen 3             | 43        | 1.1%    |
| AMD Ryzen 7 PRO         | 36        | 0.92%   |
| Intel Pentium Dual-Core | 32        | 0.82%   |
| AMD FX                  | 30        | 0.77%   |
| AMD Ryzen 5 PRO         | 27        | 0.69%   |
| Intel Core 2            | 26        | 0.67%   |
| Intel Core 2 Quad       | 23        | 0.59%   |
| Intel Pentium Silver    | 17        | 0.44%   |
| Intel Core i9           | 16        | 0.41%   |
| AMD PRO A10             | 14        | 0.36%   |
| AMD E                   | 13        | 0.33%   |
| AMD A8                  | 12        | 0.31%   |
| AMD A6                  | 11        | 0.28%   |
| AMD A10                 | 11        | 0.28%   |
| AMD EPYC                | 10        | 0.26%   |
| AMD Athlon              | 10        | 0.26%   |
| Intel Pentium Gold      | 9         | 0.23%   |
| Intel Pentium 4         | 9         | 0.23%   |
| AMD PRO A8              | 9         | 0.23%   |
| AMD Athlon 64 X2        | 9         | 0.23%   |
| Intel Genuine           | 8         | 0.2%    |
| AMD A4                  | 8         | 0.2%    |
| AMD E2                  | 7         | 0.18%   |
| AMD GX                  | 6         | 0.15%   |
| AMD E1                  | 6         | 0.15%   |
| AMD Athlon II X2        | 6         | 0.15%   |
| Intel Pentium M         | 5         | 0.13%   |
| ARM Allwinner           | 5         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1264      | 32.4%   |
| 4       | 1240      | 31.79%  |
| 6       | 388       | 9.95%   |
| 8       | 384       | 9.84%   |
| 12      | 131       | 3.36%   |
| 10      | 109       | 2.79%   |
| Unknown | 90        | 2.31%   |
| 1       | 77        | 1.97%   |
| 14      | 71        | 1.82%   |
| 16      | 61        | 1.56%   |
| 24      | 28        | 0.72%   |
| 20      | 16        | 0.41%   |
| 3       | 16        | 0.41%   |
| 28      | 6         | 0.15%   |
| 40      | 3         | 0.08%   |
| 32      | 3         | 0.08%   |
| 22      | 3         | 0.08%   |
| 5       | 3         | 0.08%   |
| 36      | 2         | 0.05%   |
| 18      | 2         | 0.05%   |
| 64      | 1         | 0.03%   |
| 52      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 44      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3723      | 95.49%  |
| Unknown | 89        | 2.28%   |
| 2       | 86        | 2.21%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2655      | 68.04%  |
| 1       | 1156      | 29.63%  |
| Unknown | 90        | 2.31%   |
| 4       | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3828      | 98.2%   |
| Unknown        | 26        | 0.67%   |
| 32-bit         | 24        | 0.62%   |
| 64-bit         | 20        | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1279      | 32.39%  |
| 0x806c1    | 195       | 4.94%   |
| 0x306c3    | 168       | 4.25%   |
| 0x306a9    | 125       | 3.17%   |
| 0x1067a    | 113       | 2.86%   |
| 0x206a7    | 102       | 2.58%   |
| 0x506e3    | 68        | 1.72%   |
| 0x0a50000d | 67        | 1.7%    |
| 0x406e3    | 60        | 1.52%   |
| 0x806e9    | 59        | 1.49%   |
| 0x08108109 | 57        | 1.44%   |
| 0x906a3    | 56        | 1.42%   |
| 0x806ec    | 56        | 1.42%   |
| 0x406c4    | 56        | 1.42%   |
| 0x906a4    | 55        | 1.39%   |
| 0x906ea    | 53        | 1.34%   |
| 0x906e9    | 52        | 1.32%   |
| 0x40651    | 52        | 1.32%   |
| 0x806ea    | 46        | 1.16%   |
| 0x906eb    | 40        | 1.01%   |
| 0x0600611a | 39        | 0.99%   |
| 0x30678    | 37        | 0.94%   |
| 0x0a50000c | 36        | 0.91%   |
| 0x306d4    | 35        | 0.89%   |
| 0x08600106 | 31        | 0.79%   |
| 0x08608103 | 29        | 0.73%   |
| 0xa0655    | 27        | 0.68%   |
| 0xb06a2    | 26        | 0.66%   |
| 0x0a601203 | 26        | 0.66%   |
| 0x20655    | 25        | 0.63%   |
| 0x706a8    | 24        | 0.61%   |
| 0x08701021 | 24        | 0.61%   |
| 0x0a404102 | 23        | 0.58%   |
| 0xb0671    | 22        | 0.56%   |
| 0x6fd      | 21        | 0.53%   |
| 0xb06a3    | 20        | 0.51%   |
| 0xa0653    | 19        | 0.48%   |
| 0x906c0    | 19        | 0.48%   |
| 0x90672    | 18        | 0.46%   |
| 0x10676    | 18        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 511       | 13.05%  |
| Unknown           | 403       | 10.29%  |
| Haswell           | 337       | 8.61%   |
| TigerLake         | 240       | 6.13%   |
| Alderlake Hybrid  | 236       | 6.03%   |
| Zen 3             | 221       | 5.64%   |
| IvyBridge         | 205       | 5.24%   |
| Skylake           | 198       | 5.06%   |
| SandyBridge       | 169       | 4.32%   |
| Penryn            | 161       | 4.11%   |
| Zen 2             | 139       | 3.55%   |
| Silvermont        | 135       | 3.45%   |
| Zen+              | 101       | 2.58%   |
| CometLake         | 97        | 2.48%   |
| Broadwell         | 89        | 2.27%   |
| Core              | 68        | 1.74%   |
| Westmere          | 66        | 1.69%   |
| Excavator         | 66        | 1.69%   |
| IceLake           | 63        | 1.61%   |
| Goldmont plus     | 58        | 1.48%   |
| Zen               | 52        | 1.33%   |
| Piledriver        | 36        | 0.92%   |
| K10               | 35        | 0.89%   |
| Nehalem           | 29        | 0.74%   |
| Tremont           | 26        | 0.66%   |
| Goldmont          | 21        | 0.54%   |
| Bonnell           | 21        | 0.54%   |
| Bobcat            | 20        | 0.51%   |
| Gracemont         | 19        | 0.49%   |
| Jaguar            | 17        | 0.43%   |
| Steamroller       | 15        | 0.38%   |
| K8 Hammer         | 13        | 0.33%   |
| NetBurst          | 11        | 0.28%   |
| Puma              | 10        | 0.26%   |
| P6                | 10        | 0.26%   |
| Bulldozer         | 6         | 0.15%   |
| K10 Llano         | 5         | 0.13%   |
| K8 & K10 hybrid   | 3         | 0.08%   |
| K6                | 2         | 0.05%   |
| Meteorlake Hybrid | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2251      | 52.37%  |
| AMD                                          | 1010      | 23.5%   |
| Nvidia                                       | 902       | 20.99%  |
| Matrox Electronics Systems                   | 85        | 1.98%   |
| ASPEED Technology                            | 43        | 1%      |
| Silicon Integrated Systems [SiS]             | 2         | 0.05%   |
| Huawei Technologies                          | 2         | 0.05%   |
| Zhaoxin                                      | 1         | 0.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Loongson Technology                          | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 223       | 5.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 119       | 2.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 109       | 2.48%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 109       | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 87        | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 81        | 1.84%   |
| Intel UHD Graphics 620                                                                   | 78        | 1.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 77        | 1.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 76        | 1.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 76        | 1.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 72        | 1.64%   |
| Intel HD Graphics 620                                                                    | 68        | 1.55%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 65        | 1.48%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 63        | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 58        | 1.32%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 55        | 1.25%   |
| Intel HD Graphics 530                                                                    | 54        | 1.23%   |
| AMD Lucienne                                                                             | 53        | 1.21%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 51        | 1.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 48        | 1.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 47        | 1.07%   |
| AMD Raphael                                                                              | 47        | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 46        | 1.05%   |
| Intel HD Graphics 630                                                                    | 45        | 1.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 45        | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 43        | 0.98%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 43        | 0.98%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 42        | 0.96%   |
| AMD Barcelo                                                                              | 40        | 0.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 39        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 35        | 0.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 34        | 0.77%   |
| AMD Rembrandt [Radeon 680M]                                                              | 34        | 0.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 33        | 0.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 33        | 0.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 33        | 0.75%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 31        | 0.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 29        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 29        | 0.66%   |
| Matrox Electronics Systems G200eR2                                                       | 27        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 1769      | 45.28%  |
| 1 x AMD                 | 811       | 20.76%  |
| 1 x Nvidia              | 467       | 11.95%  |
| Intel + Nvidia          | 338       | 8.65%   |
| Other                   | 136       | 3.48%   |
| AMD + Nvidia            | 75        | 1.92%   |
| 1 x Matrox              | 73        | 1.87%   |
| Intel + AMD             | 66        | 1.69%   |
| 2 x Intel               | 53        | 1.36%   |
| 2 x AMD                 | 48        | 1.23%   |
| 1 x ASPEED              | 32        | 0.82%   |
| Nvidia + Matrox         | 11        | 0.28%   |
| Nvidia + ASPEED         | 5         | 0.13%   |
| 2 x Nvidia              | 4         | 0.1%    |
| AMD + ASPEED            | 4         | 0.1%    |
| 3 x AMD                 | 2         | 0.05%   |
| 1 x SiS                 | 2         | 0.05%   |
| 1 x Huawei Technologies | 2         | 0.05%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.03%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.03%   |
| 1 x Zhaoxin             | 1         | 0.03%   |
| 1 x XGI                 | 1         | 0.03%   |
| 1 x Loongson Technology | 1         | 0.03%   |
| Intel + ASPEED          | 1         | 0.03%   |
| AMD + 2 x Nvidia        | 1         | 0.03%   |
| AMD + Matrox            | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2946      | 75.31%  |
| Unknown     | 641       | 16.39%  |
| Proprietary | 325       | 8.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2879      | 73.35%  |
| 0.01-0.5   | 329       | 8.38%   |
| 1.01-2.0   | 190       | 4.84%   |
| 3.01-4.0   | 166       | 4.23%   |
| 0.51-1.0   | 127       | 3.24%   |
| 7.01-8.0   | 114       | 2.9%    |
| 5.01-6.0   | 46        | 1.17%   |
| 8.01-16.0  | 38        | 0.97%   |
| 16.01-24.0 | 17        | 0.43%   |
| 2.01-3.0   | 16        | 0.41%   |
| 4.01-5.0   | 2         | 0.05%   |
| 0          | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 517       | 14.22%  |
| Samsung Electronics     | 391       | 10.75%  |
| BOE                     | 381       | 10.48%  |
| Chimei Innolux          | 311       | 8.55%   |
| LG Display              | 229       | 6.3%    |
| Dell                    | 228       | 6.27%   |
| Goldstar                | 150       | 4.13%   |
| Hewlett-Packard         | 113       | 3.11%   |
| Philips                 | 110       | 3.03%   |
| Acer                    | 91        | 2.5%    |
| Ancor Communications    | 82        | 2.26%   |
| Apple                   | 81        | 2.23%   |
| AOC                     | 81        | 2.23%   |
| BenQ                    | 78        | 2.15%   |
| Lenovo                  | 70        | 1.93%   |
| InfoVision              | 63        | 1.73%   |
| Sharp                   | 58        | 1.6%    |
| ASUSTek Computer        | 55        | 1.51%   |
| PANDA                   | 41        | 1.13%   |
| ViewSonic               | 38        | 1.05%   |
| Iiyama                  | 31        | 0.85%   |
| Chi Mei Optoelectronics | 27        | 0.74%   |
| Unknown                 | 23        | 0.63%   |
| CSO                     | 23        | 0.63%   |
| Sony                    | 18        | 0.5%    |
| Sceptre Tech            | 17        | 0.47%   |
| Unknown                 | 17        | 0.47%   |
| LG Electronics          | 16        | 0.44%   |
| LG Philips              | 14        | 0.39%   |
| NEC Computers           | 13        | 0.36%   |
| Toshiba                 | 10        | 0.28%   |
| RTK                     | 10        | 0.28%   |
| Mi                      | 10        | 0.28%   |
| MSI                     | 9         | 0.25%   |
| Vizio                   | 8         | 0.22%   |
| Fujitsu Siemens         | 8         | 0.22%   |
| Eizo                    | 8         | 0.22%   |
| Panasonic               | 7         | 0.19%   |
| HannStar                | 7         | 0.19%   |
| HKC                     | 6         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch        | 99        | 2.65%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                    | 44        | 1.18%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                  | 30        | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 28        | 0.75%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 23        | 0.62%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 22        | 0.59%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 19        | 0.51%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 17        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 17        | 0.46%   |
| Unknown                                                               | 17        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 14        | 0.37%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 14        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 13        | 0.35%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 12        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 11        | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9         | 0.24%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 9         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1387 1920x1080 293x165mm 13.2-inch      | 9         | 0.24%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 8         | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 8         | 0.21%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                  | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 8         | 0.21%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                | 7         | 0.19%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 7         | 0.19%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 509x286mm 23.0-inch          | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.19%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 7         | 0.19%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 7         | 0.19%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 7         | 0.19%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                    | 7         | 0.19%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 6         | 0.16%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 6         | 0.16%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 6         | 0.16%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 6         | 0.16%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 6         | 0.16%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x164mm 13.2-inch           | 6         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1634      | 46.78%  |
| 1366x768 (WXGA)    | 560       | 16.03%  |
| 3840x2160 (4K)     | 222       | 6.36%   |
| 2560x1440 (QHD)    | 205       | 5.87%   |
| 1920x1200 (WUXGA)  | 132       | 3.78%   |
| 1600x900 (HD+)     | 97        | 2.78%   |
| 1440x900 (WXGA+)   | 70        | 2%      |
| 1280x1024 (SXGA)   | 68        | 1.95%   |
| 1680x1050 (WSXGA+) | 62        | 1.77%   |
| 1280x800 (WXGA)    | 51        | 1.46%   |
| 2560x1600          | 43        | 1.23%   |
| 3440x1440          | 34        | 0.97%   |
| 2560x1080          | 33        | 0.94%   |
| Unknown            | 30        | 0.86%   |
| 2880x1800          | 27        | 0.77%   |
| 3840x2400          | 23        | 0.66%   |
| 2288x1287          | 19        | 0.54%   |
| 1360x768           | 18        | 0.52%   |
| 3840x1080          | 14        | 0.4%    |
| 1024x600           | 11        | 0.31%   |
| 2256x1504          | 10        | 0.29%   |
| 1024x768 (XGA)     | 10        | 0.29%   |
| 1600x1200          | 9         | 0.26%   |
| 2736x1824          | 8         | 0.23%   |
| 1920x540           | 8         | 0.23%   |
| 3840x1600          | 7         | 0.2%    |
| 2160x1440          | 7         | 0.2%    |
| 1920x1280          | 7         | 0.2%    |
| 3200x2000          | 6         | 0.17%   |
| 3200x1800 (QHD+)   | 6         | 0.17%   |
| 3072x1920          | 5         | 0.14%   |
| 3000x2000          | 5         | 0.14%   |
| 2240x1400          | 5         | 0.14%   |
| 4480x1440          | 4         | 0.11%   |
| 7680x2160          | 3         | 0.09%   |
| 5760x2160          | 3         | 0.09%   |
| 3840x1200          | 3         | 0.09%   |
| 2880x1620          | 3         | 0.09%   |
| 2520x1680          | 3         | 0.09%   |
| 1400x1050          | 3         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 747       | 20.6%   |
| 13      | 494       | 13.62%  |
| 14      | 322       | 8.88%   |
| 27      | 273       | 7.53%   |
| 24      | 269       | 7.42%   |
| 21      | 200       | 5.51%   |
| 23      | 197       | 5.43%   |
| 17      | 137       | 3.78%   |
| Unknown | 104       | 2.87%   |
| 11      | 100       | 2.76%   |
| 18      | 97        | 2.67%   |
| 12      | 83        | 2.29%   |
| 31      | 77        | 2.12%   |
| 19      | 76        | 2.1%    |
| 16      | 69        | 1.9%    |
| 34      | 47        | 1.3%    |
| 20      | 40        | 1.1%    |
| 22      | 33        | 0.91%   |
| 32      | 27        | 0.74%   |
| 84      | 23        | 0.63%   |
| 142     | 19        | 0.52%   |
| 40      | 18        | 0.5%    |
| 28      | 16        | 0.44%   |
| 10      | 15        | 0.41%   |
| 25      | 14        | 0.39%   |
| 72      | 13        | 0.36%   |
| 54      | 12        | 0.33%   |
| 48      | 11        | 0.3%    |
| 26      | 10        | 0.28%   |
| 52      | 9         | 0.25%   |
| 46      | 7         | 0.19%   |
| 37      | 7         | 0.19%   |
| 43      | 6         | 0.17%   |
| 29      | 6         | 0.17%   |
| 65      | 4         | 0.11%   |
| 49      | 4         | 0.11%   |
| 47      | 4         | 0.11%   |
| 35      | 4         | 0.11%   |
| 33      | 4         | 0.11%   |
| 8       | 4         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1329      | 37.14%  |
| 501-600        | 702       | 19.62%  |
| 201-300        | 499       | 13.95%  |
| 401-500        | 406       | 11.35%  |
| 351-400        | 167       | 4.67%   |
| 601-700        | 124       | 3.47%   |
| Unknown        | 104       | 2.91%   |
| 701-800        | 81        | 2.26%   |
| 1001-1500      | 54        | 1.51%   |
| 1501-2000      | 43        | 1.2%    |
| 801-900        | 32        | 0.89%   |
| More than 2000 | 19        | 0.53%   |
| 901-1000       | 13        | 0.36%   |
| 101-200        | 4         | 0.11%   |
| 1-100          | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2551      | 76.77%  |
| 16/10   | 437       | 13.15%  |
| Unknown | 85        | 2.56%   |
| 21/9    | 66        | 1.99%   |
| 5/4     | 62        | 1.87%   |
| 3/2     | 50        | 1.5%    |
| 4/3     | 27        | 0.81%   |
| 1.00    | 21        | 0.63%   |
| 32/9    | 10        | 0.3%    |
| 6/5     | 4         | 0.12%   |
| 0.56    | 3         | 0.09%   |
| 2.65    | 2         | 0.06%   |
| 3.40    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.58    | 1         | 0.03%   |
| 0.45    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 751       | 20.86%  |
| 81-90          | 555       | 15.42%  |
| 201-250        | 536       | 14.89%  |
| 301-350        | 282       | 7.83%   |
| 71-80          | 252       | 7%      |
| 351-500        | 170       | 4.72%   |
| 151-200        | 161       | 4.47%   |
| 251-300        | 123       | 3.42%   |
| 141-150        | 119       | 3.31%   |
| Unknown        | 104       | 2.89%   |
| 51-60          | 102       | 2.83%   |
| More than 1000 | 98        | 2.72%   |
| 121-130        | 95        | 2.64%   |
| 61-70          | 77        | 2.14%   |
| 501-1000       | 63        | 1.75%   |
| 111-120        | 62        | 1.72%   |
| 131-140        | 18        | 0.5%    |
| 41-50          | 14        | 0.39%   |
| 91-100         | 13        | 0.36%   |
| 1-40           | 5         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1076      | 30.44%  |
| 51-100        | 1024      | 28.97%  |
| 101-120       | 751       | 21.24%  |
| 161-240       | 403       | 11.4%   |
| Unknown       | 104       | 2.94%   |
| 1-50          | 91        | 2.57%   |
| More than 240 | 86        | 2.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2764      | 70.19%  |
| 0     | 674       | 17.12%  |
| 2     | 433       | 11%     |
| 3     | 64        | 1.63%   |
| 4     | 3         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1998      | 35.9%   |
| Realtek Semiconductor             | 1993      | 35.81%  |
| Qualcomm Atheros                  | 387       | 6.95%   |
| Broadcom                          | 265       | 4.76%   |
| MediaTek                          | 193       | 3.47%   |
| Broadcom Limited                  | 61        | 1.1%    |
| Marvell Technology Group          | 52        | 0.93%   |
| ASIX Electronics                  | 52        | 0.93%   |
| TP-Link                           | 44        | 0.79%   |
| Ralink Technology                 | 42        | 0.75%   |
| Nvidia                            | 40        | 0.72%   |
| Qualcomm                          | 33        | 0.59%   |
| Raspberry Pi                      | 30        | 0.54%   |
| Aquantia                          | 19        | 0.34%   |
| Xiaomi                            | 17        | 0.31%   |
| Ralink                            | 17        | 0.31%   |
| Samsung Electronics               | 16        | 0.29%   |
| Hewlett-Packard                   | 16        | 0.29%   |
| Sierra Wireless                   | 15        | 0.27%   |
| Ericsson Business Mobile Networks | 15        | 0.27%   |
| Lenovo                            | 14        | 0.25%   |
| Dell                              | 14        | 0.25%   |
| Mellanox Technologies             | 13        | 0.23%   |
| Google                            | 13        | 0.23%   |
| DisplayLink                       | 13        | 0.23%   |
| QinHeng Electronics               | 12        | 0.22%   |
| ASUSTek Computer                  | 12        | 0.22%   |
| NetGear                           | 11        | 0.2%    |
| Microsoft                         | 11        | 0.2%    |
| D-Link                            | 11        | 0.2%    |
| Qualcomm Atheros Communications   | 7         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 6         | 0.11%   |
| Microchip Technology              | 6         | 0.11%   |
| FIBOCOM                           | 6         | 0.11%   |
| Dresden Elektronik                | 6         | 0.11%   |
| American Megatrends               | 6         | 0.11%   |
| JMicron Technology                | 5         | 0.09%   |
| Insyde Software                   | 5         | 0.09%   |
| Edimax Technology                 | 5         | 0.09%   |
| VIA Technologies                  | 4         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1374      | 20.63%  |
| Intel Wi-Fi 6 AX201                                                    | 206       | 3.09%   |
| Realtek RTL8125 2.5GbE Controller                                      | 146       | 2.19%   |
| Intel Wi-Fi 6 AX200                                                    | 141       | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 127       | 1.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 124       | 1.86%   |
| Intel Wireless 8265 / 8275                                             | 123       | 1.85%   |
| Intel Ethernet Connection (13) I219-V                                  | 122       | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 116       | 1.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 110       | 1.65%   |
| Intel Wireless 7265                                                    | 107       | 1.61%   |
| Intel Ethernet Controller I225-V                                       | 93        | 1.4%    |
| Intel Wireless 7260                                                    | 84        | 1.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 80        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 75        | 1.13%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 68        | 1.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 67        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 66        | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 64        | 0.96%   |
| Intel Wireless 8260                                                    | 60        | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 58        | 0.87%   |
| Intel Ethernet Connection I217-LM                                      | 57        | 0.86%   |
| Intel I211 Gigabit Network Connection                                  | 56        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 50        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                  | 49        | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 46        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                          | 45        | 0.68%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 44        | 0.66%   |
| Intel Ethernet Connection (2) I219-V                                   | 41        | 0.62%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 40        | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 39        | 0.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 39        | 0.59%   |
| Intel I210 Gigabit Network Connection                                  | 38        | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                   | 38        | 0.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 37        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 36        | 0.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 35        | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 34        | 0.51%   |
| Intel I350 Gigabit Network Connection                                  | 34        | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 33        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1478      | 51.97%  |
| Realtek Semiconductor           | 428       | 15.05%  |
| Qualcomm Atheros                | 314       | 11.04%  |
| MediaTek                        | 187       | 6.58%   |
| Broadcom                        | 155       | 5.45%   |
| Broadcom Limited                | 50        | 1.76%   |
| Ralink Technology               | 42        | 1.48%   |
| TP-Link                         | 40        | 1.41%   |
| Qualcomm                        | 26        | 0.91%   |
| Ralink                          | 17        | 0.6%    |
| Sierra Wireless                 | 15        | 0.53%   |
| ASUSTek Computer                | 12        | 0.42%   |
| NetGear                         | 11        | 0.39%   |
| Marvell Technology Group        | 11        | 0.39%   |
| D-Link                          | 11        | 0.39%   |
| Qualcomm Atheros Communications | 7         | 0.25%   |
| Microsoft                       | 6         | 0.21%   |
| FIBOCOM                         | 6         | 0.21%   |
| Edimax Technology               | 5         | 0.18%   |
| Dell                            | 5         | 0.18%   |
| Linksys                         | 4         | 0.14%   |
| Qualcomm Technologies           | 3         | 0.11%   |
| Hewlett-Packard                 | 3         | 0.11%   |
| D-Link System                   | 2         | 0.07%   |
| AVM                             | 2         | 0.07%   |
| Wacom                           | 1         | 0.04%   |
| Quectel Wireless Solutions      | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 206       | 7.21%   |
| Intel Wi-Fi 6 AX200                                                  | 141       | 4.93%   |
| Intel Wireless 8265 / 8275                                           | 123       | 4.3%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 110       | 3.85%   |
| Intel Wireless 7265                                                  | 107       | 3.74%   |
| Intel Wireless 7260                                                  | 84        | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 80        | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 75        | 2.62%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 68        | 2.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 67        | 2.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 66        | 2.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 64        | 2.24%   |
| Intel Wireless 8260                                                  | 60        | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 58        | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 50        | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 46        | 1.61%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 44        | 1.54%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 40        | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 39        | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 39        | 1.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 37        | 1.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 36        | 1.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 35        | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 33        | 1.15%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 31        | 1.08%   |
| Realtek 802.11ac NIC                                                 | 30        | 1.05%   |
| Intel Wireless 3165                                                  | 30        | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 29        | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 28        | 0.98%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 25        | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 25        | 0.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 24        | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 24        | 0.84%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 24        | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 24        | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 23        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 23        | 0.8%    |
| Intel Gemini Lake PCH CNVi WiFi                                      | 21        | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 19        | 0.66%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 19        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1813      | 50.64%  |
| Intel                            | 1133      | 31.65%  |
| Broadcom                         | 147       | 4.11%   |
| Qualcomm Atheros                 | 105       | 2.93%   |
| ASIX Electronics                 | 52        | 1.45%   |
| Marvell Technology Group         | 41        | 1.15%   |
| Nvidia                           | 40        | 1.12%   |
| Raspberry Pi                     | 29        | 0.81%   |
| Aquantia                         | 19        | 0.53%   |
| Xiaomi                           | 17        | 0.47%   |
| Samsung Electronics              | 16        | 0.45%   |
| Lenovo                           | 14        | 0.39%   |
| Google                           | 13        | 0.36%   |
| DisplayLink                      | 13        | 0.36%   |
| Mellanox Technologies            | 12        | 0.34%   |
| Broadcom Limited                 | 11        | 0.31%   |
| Hewlett-Packard                  | 10        | 0.28%   |
| Qualcomm                         | 7         | 0.2%    |
| Silicon Integrated Systems [SiS] | 6         | 0.17%   |
| MediaTek                         | 6         | 0.17%   |
| Dell                             | 6         | 0.17%   |
| American Megatrends              | 6         | 0.17%   |
| Microsoft                        | 5         | 0.14%   |
| Microchip Technology             | 5         | 0.14%   |
| JMicron Technology               | 5         | 0.14%   |
| Insyde Software                  | 5         | 0.14%   |
| VIA Technologies                 | 4         | 0.11%   |
| TP-Link                          | 4         | 0.11%   |
| ICS Advent                       | 4         | 0.11%   |
| 3Com                             | 4         | 0.11%   |
| Spreadtrum Communications        | 2         | 0.06%   |
| QinHeng Electronics              | 2         | 0.06%   |
| OPPO Electronics                 | 2         | 0.06%   |
| IBM                              | 2         | 0.06%   |
| Huawei Technologies              | 2         | 0.06%   |
| Emulex                           | 2         | 0.06%   |
| D-Link System                    | 2         | 0.06%   |
| Cypress Semiconductor            | 2         | 0.06%   |
| Attansic Technology              | 2         | 0.06%   |
| ADMtek                           | 2         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1374      | 36.95%  |
| Realtek RTL8125 2.5GbE Controller                                      | 146       | 3.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 127       | 3.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 124       | 3.33%   |
| Intel Ethernet Connection (13) I219-V                                  | 122       | 3.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 116       | 3.12%   |
| Intel Ethernet Controller I225-V                                       | 93        | 2.5%    |
| Intel Ethernet Connection I217-LM                                      | 57        | 1.53%   |
| Intel I211 Gigabit Network Connection                                  | 56        | 1.51%   |
| Intel Ethernet Connection (4) I219-LM                                  | 49        | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                          | 45        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                   | 41        | 1.1%    |
| Intel I210 Gigabit Network Connection                                  | 38        | 1.02%   |
| Intel Ethernet Connection (4) I219-V                                   | 38        | 1.02%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 34        | 0.91%   |
| Intel I350 Gigabit Network Connection                                  | 34        | 0.91%   |
| Raspberry Pi RP1 PCIe 2.0 South Bridge                                 | 29        | 0.78%   |
| Intel Ethernet Connection I219-LM                                      | 28        | 0.75%   |
| Intel Ethernet Connection I218-LM                                      | 28        | 0.75%   |
| Intel Ethernet Controller I226-V                                       | 26        | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                                  | 25        | 0.67%   |
| Intel Ethernet Connection I217-V                                       | 22        | 0.59%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 22        | 0.59%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 21        | 0.56%   |
| Intel Ethernet Connection (16) I219-V                                  | 20        | 0.54%   |
| Intel Ethernet Connection I219-V                                       | 19        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                | 19        | 0.51%   |
| Intel 82574L Gigabit Network Connection                                | 19        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 18        | 0.48%   |
| Nvidia MCP79 Ethernet                                                  | 16        | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                                  | 16        | 0.43%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                       | 16        | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                                  | 15        | 0.4%    |
| Intel Ethernet Connection (7) I219-V                                   | 14        | 0.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 14        | 0.38%   |
| Intel 82566DM Gigabit Network Connection                               | 14        | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 13        | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 13        | 0.35%   |
| Intel Ethernet Connection (6) I219-LM                                  | 13        | 0.35%   |
| Intel Ethernet Connection (11) I219-LM                                 | 13        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3292      | 54.09%  |
| WiFi     | 2713      | 44.58%  |
| Modem    | 69        | 1.13%   |
| Unknown  | 12        | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1977      | 50.49%  |
| WiFi     | 1938      | 49.49%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1952      | 49.96%  |
| 1     | 1612      | 41.26%  |
| 0     | 118       | 3.02%   |
| 3     | 110       | 2.82%   |
| 4     | 73        | 1.87%   |
| 6     | 19        | 0.49%   |
| 5     | 9         | 0.23%   |
| 8     | 7         | 0.18%   |
| 7     | 4         | 0.1%    |
| 12    | 2         | 0.05%   |
| 9     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2914      | 74.22%  |
| Yes  | 1012      | 25.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1295      | 54.05%  |
| Realtek Semiconductor           | 238       | 9.93%   |
| Qualcomm Atheros Communications | 145       | 6.05%   |
| IMC Networks                    | 111       | 4.63%   |
| Apple                           | 89        | 3.71%   |
| Foxconn / Hon Hai               | 85        | 3.55%   |
| Broadcom                        | 80        | 3.34%   |
| Cambridge Silicon Radio         | 75        | 3.13%   |
| MediaTek                        | 56        | 2.34%   |
| Lite-On Technology              | 53        | 2.21%   |
| ASUSTek Computer                | 26        | 1.09%   |
| Hewlett-Packard                 | 21        | 0.88%   |
| Dell                            | 21        | 0.88%   |
| Realtek                         | 19        | 0.79%   |
| TP-Link                         | 15        | 0.63%   |
| USI                             | 11        | 0.46%   |
| Toshiba                         | 7         | 0.29%   |
| Edimax Technology               | 7         | 0.29%   |
| Marvell Semiconductor           | 6         | 0.25%   |
| Foxconn International           | 5         | 0.21%   |
| Actions                         | 4         | 0.17%   |
| Ralink                          | 3         | 0.13%   |
| Integrated System Solution      | 3         | 0.13%   |
| Dynex                           | 3         | 0.13%   |
| Alps Electric                   | 3         | 0.13%   |
| Ralink Technology               | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| Chicony Electronics             | 2         | 0.08%   |
| Unknown                         | 2         | 0.08%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| HTC (High Tech Computer)        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 313       | 13.05%  |
| Intel Bluetooth wireless interface                  | 228       | 9.51%   |
| Realtek Bluetooth Radio                             | 180       | 7.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 170       | 7.09%   |
| Intel Bluetooth Device                              | 168       | 7.01%   |
| Intel AX211 Bluetooth                               | 148       | 6.17%   |
| Intel AX200 Bluetooth                               | 129       | 5.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 75        | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                  | 74        | 3.09%   |
| Intel AX210 Bluetooth                               | 59        | 2.46%   |
| IMC Networks Wireless_Device                        | 58        | 2.42%   |
| MediaTek Wireless_Device                            | 56        | 2.34%   |
| Apple Bluetooth Host Controller                     | 43        | 1.79%   |
| Foxconn / Hon Hai Wireless_Device                   | 40        | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 33        | 1.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 32        | 1.33%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.17%   |
| Apple Bluetooth USB Host Controller                 | 28        | 1.17%   |
| Foxconn / Hon Hai Bluetooth Device                  | 26        | 1.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 25        | 1.04%   |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 0.88%   |
| Realtek 802.11ac WLAN Adapter                       | 20        | 0.83%   |
| Realtek Bluetooth Radio                             | 19        | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 19        | 0.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 18        | 0.75%   |
| Lite-On Wireless_Device                             | 17        | 0.71%   |
| Lite-On Bluetooth Device                            | 16        | 0.67%   |
| IMC Networks Bluetooth Device                       | 16        | 0.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 16        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.67%   |
| TP-Link UB500 Adapter                               | 15        | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.54%   |
| ASUS ASUS USB-BT500                                 | 12        | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 12        | 0.5%    |
| USI Bluetooth Device                                | 11        | 0.46%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 0.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.42%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 0.38%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 9         | 0.38%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2644      | 53.59%  |
| AMD                                          | 1049      | 21.26%  |
| Nvidia                                       | 701       | 14.21%  |
| C-Media Electronics                          | 81        | 1.64%   |
| Logitech                                     | 33        | 0.67%   |
| Lenovo                                       | 23        | 0.47%   |
| ASUSTek Computer                             | 23        | 0.47%   |
| Texas Instruments                            | 21        | 0.43%   |
| Realtek Semiconductor                        | 20        | 0.41%   |
| Zoran Co. Personal Media Division (Nogatech) | 19        | 0.39%   |
| JMTek                                        | 19        | 0.39%   |
| GN Netcom                                    | 19        | 0.39%   |
| Generalplus Technology                       | 17        | 0.34%   |
| SteelSeries ApS                              | 16        | 0.32%   |
| Micro Star International                     | 16        | 0.32%   |
| Hewlett-Packard                              | 13        | 0.26%   |
| Creative Technology                          | 13        | 0.26%   |
| Creative Labs                                | 13        | 0.26%   |
| Focusrite-Novation                           | 12        | 0.24%   |
| Corsair                                      | 8         | 0.16%   |
| BR25                                         | 8         | 0.16%   |
| VIA Technologies                             | 7         | 0.14%   |
| Razer USA                                    | 7         | 0.14%   |
| Kingston Technology                          | 7         | 0.14%   |
| Blue Microphones                             | 7         | 0.14%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.12%   |
| BEHRINGER International                      | 6         | 0.12%   |
| Tenx Technology                              | 5         | 0.1%    |
| Plantronics                                  | 5         | 0.1%    |
| Dell                                         | 5         | 0.1%    |
| Cambridge Silicon Radio                      | 5         | 0.1%    |
| Yamaha                                       | 3         | 0.06%   |
| SAVITECH                                     | 3         | 0.06%   |
| RODE Microphones                             | 3         | 0.06%   |
| PreSonus Audio Electronics                   | 3         | 0.06%   |
| Microsoft                                    | 3         | 0.06%   |
| KTMicro                                      | 3         | 0.06%   |
| DCMT Technology                              | 3         | 0.06%   |
| Conexant Systems                             | 3         | 0.06%   |
| Bose                                         | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 481       | 8.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 261       | 4.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 253       | 4.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 239       | 4.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 205       | 3.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 169       | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 161       | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 154       | 2.59%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 131       | 2.2%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 123       | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 121       | 2.03%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 103       | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 97        | 1.63%   |
| Intel 200 Series PCH HD Audio                                                                     | 92        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 88        | 1.48%   |
| AMD Kabini HDMI/DP Audio                                                                          | 75        | 1.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 73        | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 73        | 1.23%   |
| Intel 8 Series HD Audio Controller                                                                | 73        | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 71        | 1.19%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 67        | 1.12%   |
| AMD FCH Azalia Controller                                                                         | 65        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 64        | 1.07%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 63        | 1.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 61        | 1.02%   |
| Intel Comet Lake PCH cAVS                                                                         | 60        | 1.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 59        | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 58        | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 56        | 0.94%   |
| Nvidia Audio device                                                                               | 55        | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 54        | 0.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 53        | 0.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 52        | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 51        | 0.86%   |
| Intel Broadwell-U Audio Controller                                                                | 50        | 0.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 50        | 0.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 49        | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 48        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 47        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 45        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 889       | 25.71%  |
| SK hynix                                | 552       | 15.96%  |
| Kingston                                | 365       | 10.56%  |
| Micron Technology                       | 324       | 9.37%   |
| Unknown                                 | 280       | 8.1%    |
| Crucial                                 | 270       | 7.81%   |
| Corsair                                 | 123       | 3.56%   |
| G.Skill                                 | 103       | 2.98%   |
| Unknown                                 | 83        | 2.4%    |
| A-DATA Technology                       | 65        | 1.88%   |
| Ramaxel Technology                      | 51        | 1.47%   |
| Elpida                                  | 41        | 1.19%   |
| Patriot                                 | 31        | 0.9%    |
| Team                                    | 27        | 0.78%   |
| Unknown (ABCD)                          | 23        | 0.67%   |
| Nanya Technology                        | 23        | 0.67%   |
| Hewlett-Packard                         | 19        | 0.55%   |
| Hikvision                               | 18        | 0.52%   |
| Transcend                               | 12        | 0.35%   |
| 4ea5                                    | 11        | 0.32%   |
| Smart                                   | 10        | 0.29%   |
| Micro Memory Bank                       | 9         | 0.26%   |
| Timetec                                 | 8         | 0.23%   |
| ff                                      | 8         | 0.23%   |
| ASint Technology                        | 6         | 0.17%   |
| AMD                                     | 5         | 0.14%   |
| Teikon                                  | 4         | 0.12%   |
| Silicon Power Computer & Communications | 4         | 0.12%   |
| GOODRAM                                 | 4         | 0.12%   |
| Unknown (0x0E9D)                        | 3         | 0.09%   |
| Unifosa                                 | 3         | 0.09%   |
| Toshiba                                 | 3         | 0.09%   |
| PNY                                     | 3         | 0.09%   |
| Patriot Memory (PDP Systems)            | 3         | 0.09%   |
| fef5                                    | 3         | 0.09%   |
| 48spaces                                | 3         | 0.09%   |
| Wilk Elektronik                         | 2         | 0.06%   |
| Unknown (0x0B85)                        | 2         | 0.06%   |
| Unknown (000000B30000)                  | 2         | 0.06%   |
| Qimonda                                 | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 130       | 3.54%   |
| Unknown                                                          | 83        | 2.26%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 38        | 1.04%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 37        | 1.01%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 35        | 0.95%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 29        | 0.79%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 21        | 0.57%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 20        | 0.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.52%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1866MT/s         | 19        | 0.52%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 18        | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 0.49%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 18        | 0.49%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s          | 18        | 0.49%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 17        | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.44%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 16        | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.44%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s              | 16        | 0.44%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 15        | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 14        | 0.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 12        | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 0.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.33%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 12        | 0.33%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 12        | 0.33%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.33%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 12        | 0.33%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s        | 12        | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 11        | 0.3%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 11        | 0.3%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.3%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.3%    |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s              | 11        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1487      | 48.77%  |
| DDR3    | 819       | 26.86%  |
| DDR5    | 154       | 5.05%   |
| LPDDR4  | 122       | 4%      |
| DDR2    | 119       | 3.9%    |
| LPDDR3  | 95        | 3.12%   |
| LPDDR5  | 83        | 2.72%   |
| SDRAM   | 75        | 2.46%   |
| Unknown | 63        | 2.07%   |
| DDR     | 22        | 0.72%   |
| DRAM    | 7         | 0.23%   |
| EPROM   | 2         | 0.07%   |
| LPDDR2  | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1592      | 52.13%  |
| DIMM         | 1139      | 37.3%   |
| Row Of Chips | 235       | 7.69%   |
| Unknown      | 64        | 2.1%    |
| Chip         | 16        | 0.52%   |
| RIMM         | 4         | 0.13%   |
| FB-DIMM      | 4         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1217      | 37.15%  |
| 4096  | 749       | 22.86%  |
| 16384 | 535       | 16.33%  |
| 2048  | 406       | 12.39%  |
| 32768 | 223       | 6.81%   |
| 1024  | 113       | 3.45%   |
| 512   | 16        | 0.49%   |
| 65536 | 5         | 0.15%   |
| 256   | 3         | 0.09%   |
| 49152 | 2         | 0.06%   |
| 3072  | 2         | 0.06%   |
| 24576 | 1         | 0.03%   |
| 6144  | 1         | 0.03%   |
| 1536  | 1         | 0.03%   |
| 64    | 1         | 0.03%   |
| 16    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 654       | 20.25%  |
| 1600    | 490       | 15.17%  |
| 2667    | 411       | 12.72%  |
| 2400    | 233       | 7.21%   |
| 2133    | 167       | 5.17%   |
| 1333    | 167       | 5.17%   |
| 1867    | 89        | 2.76%   |
| 4800    | 80        | 2.48%   |
| 6400    | 77        | 2.38%   |
| 3600    | 76        | 2.35%   |
| Unknown | 74        | 2.29%   |
| 800     | 61        | 1.89%   |
| 667     | 60        | 1.86%   |
| 1334    | 59        | 1.83%   |
| 4267    | 48        | 1.49%   |
| 1066    | 38        | 1.18%   |
| 1866    | 37        | 1.15%   |
| 1067    | 33        | 1.02%   |
| 5600    | 28        | 0.87%   |
| 3266    | 25        | 0.77%   |
| 2666    | 25        | 0.77%   |
| 6000    | 19        | 0.59%   |
| 3733    | 17        | 0.53%   |
| 1596    | 16        | 0.5%    |
| 3800    | 13        | 0.4%    |
| 2933    | 12        | 0.37%   |
| 5200    | 11        | 0.34%   |
| 4333    | 11        | 0.34%   |
| 4266    | 11        | 0.34%   |
| 533     | 10        | 0.31%   |
| 3400    | 9         | 0.28%   |
| 3000    | 9         | 0.28%   |
| 7500    | 8         | 0.25%   |
| 4199    | 8         | 0.25%   |
| 3933    | 8         | 0.25%   |
| 1800    | 8         | 0.25%   |
| 975     | 8         | 0.25%   |
| 2048    | 7         | 0.22%   |
| 1648    | 7         | 0.22%   |
| 3866    | 6         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 19        | 30.16%  |
| Hewlett-Packard       | 16        | 25.4%   |
| Canon                 | 11        | 17.46%  |
| Dymo-CoStar           | 4         | 6.35%   |
| Seiko Epson           | 3         | 4.76%   |
| Samsung Electronics   | 2         | 3.17%   |
| QinHeng Electronics   | 2         | 3.17%   |
| Pantum                | 2         | 3.17%   |
| Lexmark International | 2         | 3.17%   |
| Zebra                 | 1         | 1.59%   |
| nemonic               | 1         | 1.59%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon LiDE 400                              | 4         | 6.25%   |
| QinHeng CH340S                              | 2         | 3.13%   |
| HP LaserJet 1018                            | 2         | 3.13%   |
| HP ENVY 5540 series                         | 2         | 3.13%   |
| Canon MF4010 series                         | 2         | 3.13%   |
| Canon MF3010                                | 2         | 3.13%   |
| Zebra Thrmal 2844                           | 1         | 1.56%   |
| Seiko Epson XP-102 103 Series               | 1         | 1.56%   |
| Seiko Epson Printer                         | 1         | 1.56%   |
| Seiko Epson ET-4850 Series                  | 1         | 1.56%   |
| Samsung M2070 Series                        | 1         | 1.56%   |
| Samsung M2020 Series                        | 1         | 1.56%   |
| Pantum P2500W series                        | 1         | 1.56%   |
| Pantum P2200 series                         | 1         | 1.56%   |
| nemonic MIP-001                             | 1         | 1.56%   |
| Lexmark International E260dn                | 1         | 1.56%   |
| Lexmark International E120                  | 1         | 1.56%   |
| HP Smart Tank 510 series                    | 1         | 1.56%   |
| HP Printing Support                         | 1         | 1.56%   |
| HP OfficeJet Pro 9020 series                | 1         | 1.56%   |
| HP OfficeJet 5200 series                    | 1         | 1.56%   |
| HP Officejet 4500 G510g-m                   | 1         | 1.56%   |
| HP Officejet 4500 G510a-f                   | 1         | 1.56%   |
| HP LaserJet Pro M404-M405                   | 1         | 1.56%   |
| HP LaserJet P2055 series                    | 1         | 1.56%   |
| HP LaserJet 1022                            | 1         | 1.56%   |
| HP Laser 107w                               | 1         | 1.56%   |
| HP HP LaserJet P2035                        | 1         | 1.56%   |
| HP DeskJet 2700 series                      | 1         | 1.56%   |
| Dymo-CoStar DYMO XTL                        | 1         | 1.56%   |
| Dymo-CoStar DYMO LabelWriter DUO            | 1         | 1.56%   |
| Dymo-CoStar DYMO LabelWriter 4XL            | 1         | 1.56%   |
| Dymo-CoStar DYMO LabelWriter 450 Twin Turbo | 1         | 1.56%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo      | 1         | 1.56%   |
| Canon TS3100 series                         | 1         | 1.56%   |
| Canon PIXMA iP4300 Printer                  | 1         | 1.56%   |
| Canon G3010 series                          | 1         | 1.56%   |
| Brother MFC-L2710DW series                  | 1         | 1.56%   |
| Brother MFC-J497DW                          | 1         | 1.56%   |
| Brother MFC-8510DN                          | 1         | 1.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 52.38%  |
| Seiko Epson     | 6         | 28.57%  |
| Hewlett-Packard | 2         | 9.52%   |
| Plustek         | 1         | 4.76%   |
| Mustek Systems  | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                           | 4         | 19.05%  |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100] | 2         | 9.52%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]     | 2         | 9.52%   |
| Canon CanoScan LiDE 110                           | 2         | 9.52%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]       | 1         | 4.76%   |
| Seiko Epson GT-7700U [Perfection 1240U]           | 1         | 4.76%   |
| Plustek 1200dpi USB Scanner                       | 1         | 4.76%   |
| Mustek Systems ScanExpress 1200 UB                | 1         | 4.76%   |
| HP ScanJet 82x0C                                  | 1         | 4.76%   |
| HP ScanJet 5300c/5370c                            | 1         | 4.76%   |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 4.76%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40            | 1         | 4.76%   |
| Canon CanoScan LIDE 25                            | 1         | 4.76%   |
| Canon CanoScan LiDE 220                           | 1         | 4.76%   |
| Canon CanoScan 1220U                              | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 514       | 23.4%   |
| Bison Electronics                      | 278       | 12.65%  |
| IMC Networks                           | 163       | 7.42%   |
| Quanta                                 | 161       | 7.33%   |
| Microdia                               | 136       | 6.19%   |
| Realtek Semiconductor                  | 132       | 6.01%   |
| Logitech                               | 109       | 4.96%   |
| Sunplus Innovation Technology          | 91        | 4.14%   |
| Luxvisions Innotech Limited            | 72        | 3.28%   |
| Cheng Uei Precision Industry (Foxlink) | 60        | 2.73%   |
| Apple                                  | 60        | 2.73%   |
| Lite-On Technology                     | 51        | 2.32%   |
| Syntek                                 | 48        | 2.18%   |
| Acer                                   | 40        | 1.82%   |
| Sonix Technology                       | 27        | 1.23%   |
| Suyin                                  | 26        | 1.18%   |
| Microsoft                              | 26        | 1.18%   |
| Silicon Motion                         | 16        | 0.73%   |
| Samsung Electronics                    | 14        | 0.64%   |
| Lenovo                                 | 12        | 0.55%   |
| Generalplus Technology                 | 12        | 0.55%   |
| Alcor Micro                            | 11        | 0.5%    |
| ShineTech                              | 10        | 0.46%   |
| Ricoh                                  | 10        | 0.46%   |
| Z-Star Microelectronics                | 8         | 0.36%   |
| SunplusIT                              | 8         | 0.36%   |
| Jieli Technology                       | 6         | 0.27%   |
| icSpring                               | 6         | 0.27%   |
| MacroSilicon                           | 5         | 0.23%   |
| KYE Systems (Mouse Systems)            | 5         | 0.23%   |
| AVerMedia Technologies                 | 5         | 0.23%   |
| Primax Electronics                     | 4         | 0.18%   |
| Importek                               | 4         | 0.18%   |
| Trust                                  | 3         | 0.14%   |
| Unknown                                | 3         | 0.14%   |
| ShineOptics                            | 2         | 0.09%   |
| Ruision                                | 2         | 0.09%   |
| Razer USA                              | 2         | 0.09%   |
| OmniVision Technologies                | 2         | 0.09%   |
| kingcome                               | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 178       | 7.91%   |
| Bison Integrated Camera                             | 107       | 4.76%   |
| Bison Integrated 5M Camera                          | 66        | 2.93%   |
| IMC Networks Integrated Camera                      | 57        | 2.53%   |
| Microdia Integrated_Webcam_HD                       | 53        | 2.36%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 52        | 2.31%   |
| Quanta Chromebook HD Camera                         | 50        | 2.22%   |
| Chicony Integrated 5M Camera                        | 42        | 1.87%   |
| Realtek Integrated_Webcam_HD                        | 41        | 1.82%   |
| Bison BisonCam, NB Pro                              | 40        | 1.78%   |
| Syntek Integrated Camera                            | 36        | 1.6%    |
| Chicony HP HD Camera                                | 35        | 1.56%   |
| Quanta HD User Facing                               | 23        | 1.02%   |
| Logitech Webcam C270                                | 22        | 0.98%   |
| Sunplus Integrated_Webcam_HD                        | 21        | 0.93%   |
| Chicony HD WebCam                                   | 21        | 0.93%   |
| Chicony HD User Facing                              | 19        | 0.84%   |
| Logitech HD Pro Webcam C920                         | 18        | 0.8%    |
| Lite-On Integrated Camera                           | 18        | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 18        | 0.8%    |
| Apple Built-in iSight                               | 18        | 0.8%    |
| Sonix USB2.0 HD UVC WebCam                          | 17        | 0.76%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 17        | 0.76%   |
| Bison SunplusIT Integrated Camera                   | 17        | 0.76%   |
| Bison Lenovo Integrated Webcam                      | 17        | 0.76%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 16        | 0.71%   |
| Quanta HP TrueVision HD Camera                      | 15        | 0.67%   |
| Chicony HP Wide Vision HD Camera                    | 15        | 0.67%   |
| Chicony HP TrueVision HD                            | 15        | 0.67%   |
| Apple FaceTime HD Camera (Built-in)                 | 15        | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)             | 14        | 0.62%   |
| Realtek USB Camera                                  | 14        | 0.62%   |
| Microdia USB 2.0 Camera                             | 14        | 0.62%   |
| Chicony Integrated Camera (1280x720@30)             | 14        | 0.62%   |
| Acer Integrated Camera                              | 14        | 0.62%   |
| Realtek Integrated Webcam                           | 13        | 0.58%   |
| Quanta HP HD Camera                                 | 13        | 0.58%   |
| Microdia Webcam Vitade AF                           | 13        | 0.58%   |
| Luxvisions Innotech Limited Integrated Camera       | 13        | 0.58%   |
| Lite-On HP HD Camera                                | 13        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 228       | 48.1%   |
| Validity Sensors                   | 124       | 26.16%  |
| Shenzhen Goodix Technology         | 50        | 10.55%  |
| Elan Microelectronics              | 21        | 4.43%   |
| AuthenTec                          | 16        | 3.38%   |
| Upek                               | 13        | 2.74%   |
| LighTuning Technology              | 7         | 1.48%   |
| STMicroelectronics                 | 4         | 0.84%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.84%   |
| Focal-systems.Corp                 | 2         | 0.42%   |
| DigitalPersona                     | 2         | 0.42%   |
| Samsung Electronics                | 1         | 0.21%   |
| Microsoft                          | 1         | 0.21%   |
| HOLTEK                             | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 153       | 32.28%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 7.38%   |
| Shenzhen Goodix  Fingerprint Device                                        | 32        | 6.75%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 4.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 4.22%   |
| Shenzhen Goodix Fingerprint Reader                                         | 14        | 2.95%   |
| Elan ELAN:ARM-M4                                                           | 14        | 2.95%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 2.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 2.53%   |
| Synaptics UWP WBDI Device                                                  | 12        | 2.53%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 2.32%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 2.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.48%   |
| AuthenTec AES2810                                                          | 7         | 1.48%   |
| Validity Sensors VFS491                                                    | 6         | 1.27%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.27%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.27%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.05%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.05%   |
| Synaptics  WBDI                                                            | 5         | 1.05%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.84%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.84%   |
| Synaptics WBDI                                                             | 4         | 0.84%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.84%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 0.84%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.84%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.84%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.84%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.63%   |
| Synaptics UWP WBDI                                                         | 3         | 0.63%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.42%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.42%   |
| DigitalPersona Fingerprint Reader                                          | 2         | 0.42%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.42%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.42%   |
| Unknown                                                                    | 2         | 0.42%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.21%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 63        | 40.13%  |
| Alcor Micro               | 59        | 37.58%  |
| Upek                      | 7         | 4.46%   |
| O2 Micro                  | 6         | 3.82%   |
| Lenovo                    | 6         | 3.82%   |
| Yubico.com                | 3         | 1.91%   |
| Gemalto (was Gemplus)     | 3         | 1.91%   |
| Realtek Semiconductor     | 2         | 1.27%   |
| Advanced Card Systems     | 2         | 1.27%   |
| SCM Microsystems          | 1         | 0.64%   |
| Reiner SCT Kartensysteme  | 1         | 0.64%   |
| OmniKey                   | 1         | 0.64%   |
| Chicony Electronics       | 1         | 0.64%   |
| CHERRY                    | 1         | 0.64%   |
| Aladdin Knowledge Systems | 1         | 0.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 58        | 36.94%  |
| Broadcom 58200                                                               | 18        | 11.46%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 10.83%  |
| Broadcom 5880                                                                | 16        | 10.19%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 7.01%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.46%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.82%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 3.18%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.27%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.27%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.27%   |
| Advanced Card Systems ACR122U                                                | 2         | 1.27%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.64%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.64%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.64%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.64%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.64%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.64%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.64%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.64%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.64%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2298      | 58.28%  |
| 1     | 1330      | 33.73%  |
| 2     | 258       | 6.54%   |
| 3     | 41        | 1.04%   |
| 4     | 10        | 0.25%   |
| 5     | 5         | 0.13%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 692       | 36.34%  |
| Fingerprint reader       | 469       | 24.63%  |
| Net/wireless             | 165       | 8.67%   |
| Chipcard                 | 136       | 7.14%   |
| Multimedia controller    | 103       | 5.41%   |
| Unassigned class         | 83        | 4.36%   |
| Camera                   | 81        | 4.25%   |
| Communication controller | 69        | 3.62%   |
| Bluetooth                | 24        | 1.26%   |
| Storage                  | 16        | 0.84%   |
| Sound                    | 15        | 0.79%   |
| Card reader              | 15        | 0.79%   |
| Modem                    | 11        | 0.58%   |
| Net/ethernet             | 7         | 0.37%   |
| Wireless                 | 5         | 0.26%   |
| Storage/raid             | 4         | 0.21%   |
| Network                  | 4         | 0.21%   |
| Storage/nvme             | 2         | 0.11%   |
| Storage/ide              | 1         | 0.05%   |
| Flash memory             | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

