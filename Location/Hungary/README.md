Linux in Hungary - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Hungary.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Hungary/Desktop/README.md) and [notebooks](/Location/Hungary/Notebook/README.md).

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

Total: 8402

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 339A                        | Desktop     | [cd104d3996](https://linux-hardware.org/?probe=cd104d3996) | Oct 01, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [fa948b8e32](https://linux-hardware.org/?probe=fa948b8e32) | Oct 01, 2023 |
| HP            | 1494                        | Desktop     | [5250e1dc1c](https://linux-hardware.org/?probe=5250e1dc1c) | Oct 01, 2023 |
| Lenovo        | ThinkCentre M55p 8811ZD4    | Desktop     | [710dea5f88](https://linux-hardware.org/?probe=710dea5f88) | Sep 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [4567599161](https://linux-hardware.org/?probe=4567599161) | Sep 29, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [526458167b](https://linux-hardware.org/?probe=526458167b) | Sep 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [b7faf1054b](https://linux-hardware.org/?probe=b7faf1054b) | Sep 29, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [9d618e345a](https://linux-hardware.org/?probe=9d618e345a) | Sep 29, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [3513d5bcf3](https://linux-hardware.org/?probe=3513d5bcf3) | Sep 28, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [a355202f8a](https://linux-hardware.org/?probe=a355202f8a) | Sep 28, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [ea6622fcde](https://linux-hardware.org/?probe=ea6622fcde) | Sep 28, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [a7e3c38a52](https://linux-hardware.org/?probe=a7e3c38a52) | Sep 28, 2023 |
| eMachines     | E725                        | Notebook    | [2c76723d59](https://linux-hardware.org/?probe=2c76723d59) | Sep 28, 2023 |
| Zebra Tech... | 10-WLAN-1                   | Notebook    | [9959efdb76](https://linux-hardware.org/?probe=9959efdb76) | Sep 27, 2023 |
| ASUSTek       | D700MD                      | Desktop     | [91740e63b9](https://linux-hardware.org/?probe=91740e63b9) | Sep 27, 2023 |
| HP            | 250 G1                      | Notebook    | [0ec87fea6c](https://linux-hardware.org/?probe=0ec87fea6c) | Sep 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [e8577ce363](https://linux-hardware.org/?probe=e8577ce363) | Sep 27, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [390c16a341](https://linux-hardware.org/?probe=390c16a341) | Sep 26, 2023 |
| Lenovo        | ThinkServer TS440           | Desktop     | [11efb68800](https://linux-hardware.org/?probe=11efb68800) | Sep 26, 2023 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [4cbe33187c](https://linux-hardware.org/?probe=4cbe33187c) | Sep 26, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [a3fc0915cd](https://linux-hardware.org/?probe=a3fc0915cd) | Sep 26, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [3ffed1f144](https://linux-hardware.org/?probe=3ffed1f144) | Sep 26, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [e6eff7d60d](https://linux-hardware.org/?probe=e6eff7d60d) | Sep 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [6b0a58d94c](https://linux-hardware.org/?probe=6b0a58d94c) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [263bf34c40](https://linux-hardware.org/?probe=263bf34c40) | Sep 25, 2023 |
| HP            | 250 G1                      | Notebook    | [1aa0ca441a](https://linux-hardware.org/?probe=1aa0ca441a) | Sep 25, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [9a2c66690c](https://linux-hardware.org/?probe=9a2c66690c) | Sep 25, 2023 |
| MSI           | B85M-E33                    | Desktop     | [1e246dda8b](https://linux-hardware.org/?probe=1e246dda8b) | Sep 25, 2023 |
| HP            | 09F8h                       | Desktop     | [3d8c4a9ace](https://linux-hardware.org/?probe=3d8c4a9ace) | Sep 25, 2023 |
| HP            | 09F8h                       | Desktop     | [f844e52238](https://linux-hardware.org/?probe=f844e52238) | Sep 25, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [137fbb8afb](https://linux-hardware.org/?probe=137fbb8afb) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [dc76c26d4e](https://linux-hardware.org/?probe=dc76c26d4e) | Sep 24, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [dc6cea804c](https://linux-hardware.org/?probe=dc6cea804c) | Sep 24, 2023 |
| HP            | 09F8h                       | Desktop     | [d2ade2ea70](https://linux-hardware.org/?probe=d2ade2ea70) | Sep 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f94c540fde](https://linux-hardware.org/?probe=f94c540fde) | Sep 24, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [fcdc931f2b](https://linux-hardware.org/?probe=fcdc931f2b) | Sep 24, 2023 |
| Toshiba       | Satellite C55-A-1NV         | Notebook    | [2d441ed803](https://linux-hardware.org/?probe=2d441ed803) | Sep 24, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [1dd60939d2](https://linux-hardware.org/?probe=1dd60939d2) | Sep 24, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [0c9651a144](https://linux-hardware.org/?probe=0c9651a144) | Sep 24, 2023 |
| HP            | Notebook                    | Notebook    | [b222ca41de](https://linux-hardware.org/?probe=b222ca41de) | Sep 24, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [b4a2e6cb0a](https://linux-hardware.org/?probe=b4a2e6cb0a) | Sep 24, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [22a7b0cc9c](https://linux-hardware.org/?probe=22a7b0cc9c) | Sep 24, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [ce1b08cdf9](https://linux-hardware.org/?probe=ce1b08cdf9) | Sep 23, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | Notebook    | [8d4bdbafa8](https://linux-hardware.org/?probe=8d4bdbafa8) | Sep 23, 2023 |
| Gigabyte      | H110N-CF                    | Desktop     | [7655a31997](https://linux-hardware.org/?probe=7655a31997) | Sep 23, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [d967e2d2a3](https://linux-hardware.org/?probe=d967e2d2a3) | Sep 23, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [477998353b](https://linux-hardware.org/?probe=477998353b) | Sep 23, 2023 |
| HP            | 1497                        | Desktop     | [cbbd6a0182](https://linux-hardware.org/?probe=cbbd6a0182) | Sep 23, 2023 |
| HP            | Compaq 6710b (KE121EA#AK... | Notebook    | [a5b9ab6a07](https://linux-hardware.org/?probe=a5b9ab6a07) | Sep 23, 2023 |
| MSI           | MS-7309                     | Desktop     | [356be353d5](https://linux-hardware.org/?probe=356be353d5) | Sep 23, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [b519a4adea](https://linux-hardware.org/?probe=b519a4adea) | Sep 23, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [8d7c00fcd2](https://linux-hardware.org/?probe=8d7c00fcd2) | Sep 23, 2023 |
| HP            | 650                         | Notebook    | [3c45902b7c](https://linux-hardware.org/?probe=3c45902b7c) | Sep 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [134cfff173](https://linux-hardware.org/?probe=134cfff173) | Sep 22, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | Notebook    | [c933242918](https://linux-hardware.org/?probe=c933242918) | Sep 22, 2023 |
| Dell          | Latitude 7390               | Notebook    | [1aab1b313f](https://linux-hardware.org/?probe=1aab1b313f) | Sep 22, 2023 |
| HP            | 250 G1                      | Notebook    | [44dde35a76](https://linux-hardware.org/?probe=44dde35a76) | Sep 22, 2023 |
| Dell          | Latitude E5520              | Notebook    | [ae034f7a6b](https://linux-hardware.org/?probe=ae034f7a6b) | Sep 22, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [18581b1af5](https://linux-hardware.org/?probe=18581b1af5) | Sep 22, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [daa9128e32](https://linux-hardware.org/?probe=daa9128e32) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [bb5eff384a](https://linux-hardware.org/?probe=bb5eff384a) | Sep 22, 2023 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [61ce9ed478](https://linux-hardware.org/?probe=61ce9ed478) | Sep 22, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [96ba82f38e](https://linux-hardware.org/?probe=96ba82f38e) | Sep 22, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [942f5325d2](https://linux-hardware.org/?probe=942f5325d2) | Sep 22, 2023 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [701abaeb8f](https://linux-hardware.org/?probe=701abaeb8f) | Sep 22, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [ff935c4dbe](https://linux-hardware.org/?probe=ff935c4dbe) | Sep 22, 2023 |
| ASRock        | B85M                        | Desktop     | [5b78620442](https://linux-hardware.org/?probe=5b78620442) | Sep 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | Notebook    | [c71bb49dcd](https://linux-hardware.org/?probe=c71bb49dcd) | Sep 21, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [60976010ac](https://linux-hardware.org/?probe=60976010ac) | Sep 21, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [25e14aaf2b](https://linux-hardware.org/?probe=25e14aaf2b) | Sep 21, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [b21f53b9e1](https://linux-hardware.org/?probe=b21f53b9e1) | Sep 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [d1b966125a](https://linux-hardware.org/?probe=d1b966125a) | Sep 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [3e8e36e3ea](https://linux-hardware.org/?probe=3e8e36e3ea) | Sep 21, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [8552d31b3c](https://linux-hardware.org/?probe=8552d31b3c) | Sep 21, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [32e2046699](https://linux-hardware.org/?probe=32e2046699) | Sep 21, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [22733fb7ba](https://linux-hardware.org/?probe=22733fb7ba) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [d348acd6c8](https://linux-hardware.org/?probe=d348acd6c8) | Sep 21, 2023 |
| Dell          | Latitude E6220              | Notebook    | [dd26ec3c45](https://linux-hardware.org/?probe=dd26ec3c45) | Sep 21, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [6b9f9348c0](https://linux-hardware.org/?probe=6b9f9348c0) | Sep 21, 2023 |
| HP            | 1495                        | Desktop     | [9c5926d73b](https://linux-hardware.org/?probe=9c5926d73b) | Sep 21, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [cff5fbdefd](https://linux-hardware.org/?probe=cff5fbdefd) | Sep 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9f1f1562ed](https://linux-hardware.org/?probe=9f1f1562ed) | Sep 21, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [f3deee7792](https://linux-hardware.org/?probe=f3deee7792) | Sep 20, 2023 |
| Lenovo        | 1730-A1G                    | Desktop     | [9f9580c81f](https://linux-hardware.org/?probe=9f9580c81f) | Sep 19, 2023 |
| Lenovo        | Aptio CRB SDK0G00599 WIN    | Mini pc     | [d7f55df5b8](https://linux-hardware.org/?probe=d7f55df5b8) | Sep 19, 2023 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [14714d058e](https://linux-hardware.org/?probe=14714d058e) | Sep 19, 2023 |
| HP            | 8298                        | Desktop     | [006592d87f](https://linux-hardware.org/?probe=006592d87f) | Sep 19, 2023 |
| Lenovo        | 1730-A1G                    | Desktop     | [e58cd05ca6](https://linux-hardware.org/?probe=e58cd05ca6) | Sep 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d83d7bbfa8](https://linux-hardware.org/?probe=d83d7bbfa8) | Sep 18, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [d00d3fed03](https://linux-hardware.org/?probe=d00d3fed03) | Sep 18, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [12a4225b04](https://linux-hardware.org/?probe=12a4225b04) | Sep 18, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [851a7301bc](https://linux-hardware.org/?probe=851a7301bc) | Sep 18, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [8ee590e888](https://linux-hardware.org/?probe=8ee590e888) | Sep 18, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [42ade99539](https://linux-hardware.org/?probe=42ade99539) | Sep 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [60e5e9a3db](https://linux-hardware.org/?probe=60e5e9a3db) | Sep 18, 2023 |
| HP            | 1494                        | Desktop     | [f7dcc5924c](https://linux-hardware.org/?probe=f7dcc5924c) | Sep 17, 2023 |
| HP            | 1494                        | Desktop     | [35c90d3fb2](https://linux-hardware.org/?probe=35c90d3fb2) | Sep 17, 2023 |
| AZW           | U59                         | Desktop     | [2bc9b4b184](https://linux-hardware.org/?probe=2bc9b4b184) | Sep 17, 2023 |
| Dell          | 0R230R A00                  | Desktop     | [92ff22e072](https://linux-hardware.org/?probe=92ff22e072) | Sep 17, 2023 |
| Dell          | 0R230R A00                  | Desktop     | [7d679bbf7f](https://linux-hardware.org/?probe=7d679bbf7f) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [3bb8e84b6b](https://linux-hardware.org/?probe=3bb8e84b6b) | Sep 17, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [c34520d1c2](https://linux-hardware.org/?probe=c34520d1c2) | Sep 16, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [15e259376e](https://linux-hardware.org/?probe=15e259376e) | Sep 16, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [fb0eee9917](https://linux-hardware.org/?probe=fb0eee9917) | Sep 16, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [ae9c2e3978](https://linux-hardware.org/?probe=ae9c2e3978) | Sep 16, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [8076be0adb](https://linux-hardware.org/?probe=8076be0adb) | Sep 16, 2023 |
| Jumper        | EZbook                      | Notebook    | [bd0a13e867](https://linux-hardware.org/?probe=bd0a13e867) | Sep 16, 2023 |
| Dell          | Latitude E6220              | Notebook    | [8a341bd0e2](https://linux-hardware.org/?probe=8a341bd0e2) | Sep 16, 2023 |
| HP            | 650                         | Notebook    | [f648ca59f3](https://linux-hardware.org/?probe=f648ca59f3) | Sep 16, 2023 |
| Lenovo        | ThinkPad T450 20BVA01QHV    | Notebook    | [4f0a2bdfdc](https://linux-hardware.org/?probe=4f0a2bdfdc) | Sep 15, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [bd5fae0639](https://linux-hardware.org/?probe=bd5fae0639) | Sep 15, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [781590255d](https://linux-hardware.org/?probe=781590255d) | Sep 15, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [601a3eed6e](https://linux-hardware.org/?probe=601a3eed6e) | Sep 15, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [382acd4186](https://linux-hardware.org/?probe=382acd4186) | Sep 15, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [ae2f1fa903](https://linux-hardware.org/?probe=ae2f1fa903) | Sep 15, 2023 |
| Dell          | Latitude 7390               | Notebook    | [c2529c08a4](https://linux-hardware.org/?probe=c2529c08a4) | Sep 14, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [04d9ccd10f](https://linux-hardware.org/?probe=04d9ccd10f) | Sep 14, 2023 |
| HP            | 250 G1                      | Notebook    | [05483d5695](https://linux-hardware.org/?probe=05483d5695) | Sep 14, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [14a4828110](https://linux-hardware.org/?probe=14a4828110) | Sep 14, 2023 |
| Insyde        | Braswell                    | Notebook    | [1fb0864056](https://linux-hardware.org/?probe=1fb0864056) | Sep 14, 2023 |
| Lenovo        | ThinkServer TS440           | Desktop     | [8ffd465a75](https://linux-hardware.org/?probe=8ffd465a75) | Sep 14, 2023 |
| HP            | 8265                        | Desktop     | [1e16a47683](https://linux-hardware.org/?probe=1e16a47683) | Sep 13, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [bc19e0cdbb](https://linux-hardware.org/?probe=bc19e0cdbb) | Sep 13, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | Notebook    | [fcac50bfba](https://linux-hardware.org/?probe=fcac50bfba) | Sep 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [8dba4d978a](https://linux-hardware.org/?probe=8dba4d978a) | Sep 13, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [9bd19e6fbf](https://linux-hardware.org/?probe=9bd19e6fbf) | Sep 12, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [ef0bc2bd79](https://linux-hardware.org/?probe=ef0bc2bd79) | Sep 12, 2023 |
| Dell          | Latitude E6430              | Notebook    | [79cf77c6ba](https://linux-hardware.org/?probe=79cf77c6ba) | Sep 12, 2023 |
| Dell          | Latitude E6220              | Notebook    | [f34fd65819](https://linux-hardware.org/?probe=f34fd65819) | Sep 12, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [ec4efd4d4d](https://linux-hardware.org/?probe=ec4efd4d4d) | Sep 11, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [e72c31a6fc](https://linux-hardware.org/?probe=e72c31a6fc) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Intel         | S5500HCV E40912-455         | Server      | [1f7dfe194c](https://linux-hardware.org/?probe=1f7dfe194c) | Sep 11, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [60b271e896](https://linux-hardware.org/?probe=60b271e896) | Sep 11, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [7835af6517](https://linux-hardware.org/?probe=7835af6517) | Sep 11, 2023 |
| HP            | 8265                        | Desktop     | [f7e98e0f58](https://linux-hardware.org/?probe=f7e98e0f58) | Sep 10, 2023 |
| HP            | 3047h                       | Desktop     | [1070c2f57a](https://linux-hardware.org/?probe=1070c2f57a) | Sep 10, 2023 |
| HP            | 3047h                       | Desktop     | [746e154eaf](https://linux-hardware.org/?probe=746e154eaf) | Sep 10, 2023 |
| ASRock        | 775i945GZ                   | Desktop     | [31f5d64453](https://linux-hardware.org/?probe=31f5d64453) | Sep 10, 2023 |
| ASRock        | 775i945GZ                   | Desktop     | [625c711748](https://linux-hardware.org/?probe=625c711748) | Sep 10, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [933a72acff](https://linux-hardware.org/?probe=933a72acff) | Sep 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9c9441fa1c](https://linux-hardware.org/?probe=9c9441fa1c) | Sep 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2706096498](https://linux-hardware.org/?probe=2706096498) | Sep 10, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [71f9c8579d](https://linux-hardware.org/?probe=71f9c8579d) | Sep 10, 2023 |
| HP            | Notebook                    | Notebook    | [231eb17318](https://linux-hardware.org/?probe=231eb17318) | Sep 10, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [5fc8984800](https://linux-hardware.org/?probe=5fc8984800) | Sep 10, 2023 |
| HP            | 339A                        | Desktop     | [f19d37b028](https://linux-hardware.org/?probe=f19d37b028) | Sep 10, 2023 |
| HP            | 339A                        | Desktop     | [794685ff75](https://linux-hardware.org/?probe=794685ff75) | Sep 10, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [06e4b83617](https://linux-hardware.org/?probe=06e4b83617) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| AZW           | U59                         | Desktop     | [e199a9df01](https://linux-hardware.org/?probe=e199a9df01) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| HP            | 1497                        | Desktop     | [e420bbd661](https://linux-hardware.org/?probe=e420bbd661) | Sep 09, 2023 |
| Intel         | S5500HCV E40912-455         | Server      | [f034939e2e](https://linux-hardware.org/?probe=f034939e2e) | Sep 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0f8249e50f](https://linux-hardware.org/?probe=0f8249e50f) | Sep 09, 2023 |
| HP            | 1497                        | Desktop     | [6de463b204](https://linux-hardware.org/?probe=6de463b204) | Sep 09, 2023 |
| Lenovo        | ThinkPad X395 20NMS0YG00    | Notebook    | [b3697e5a7e](https://linux-hardware.org/?probe=b3697e5a7e) | Sep 09, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [aa332cc883](https://linux-hardware.org/?probe=aa332cc883) | Sep 09, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [5c050dd160](https://linux-hardware.org/?probe=5c050dd160) | Sep 08, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [7f678086c3](https://linux-hardware.org/?probe=7f678086c3) | Sep 08, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8a383606e3](https://linux-hardware.org/?probe=8a383606e3) | Sep 08, 2023 |
| MSI           | FM2-A85XMA-E35              | Desktop     | [ea1d2d5910](https://linux-hardware.org/?probe=ea1d2d5910) | Sep 08, 2023 |
| Toshiba       | Satellite C55-A-1NV         | Notebook    | [d0f37c70e7](https://linux-hardware.org/?probe=d0f37c70e7) | Sep 08, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [598ed8c100](https://linux-hardware.org/?probe=598ed8c100) | Sep 08, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [49adfda956](https://linux-hardware.org/?probe=49adfda956) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [9c672d2801](https://linux-hardware.org/?probe=9c672d2801) | Sep 07, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [898930f2b1](https://linux-hardware.org/?probe=898930f2b1) | Sep 07, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [132fa17be7](https://linux-hardware.org/?probe=132fa17be7) | Sep 06, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [36e10816ea](https://linux-hardware.org/?probe=36e10816ea) | Sep 06, 2023 |
| Dell          | Latitude E6540              | Notebook    | [2832b1dd0d](https://linux-hardware.org/?probe=2832b1dd0d) | Sep 06, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [e5a99beac7](https://linux-hardware.org/?probe=e5a99beac7) | Sep 06, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [c19df6a939](https://linux-hardware.org/?probe=c19df6a939) | Sep 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4e04252ac1](https://linux-hardware.org/?probe=4e04252ac1) | Sep 06, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [86a4e0d5b8](https://linux-hardware.org/?probe=86a4e0d5b8) | Sep 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [d729a17611](https://linux-hardware.org/?probe=d729a17611) | Sep 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [857d41cc6a](https://linux-hardware.org/?probe=857d41cc6a) | Sep 06, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [65bbed09ce](https://linux-hardware.org/?probe=65bbed09ce) | Sep 06, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [b9dddc1ef8](https://linux-hardware.org/?probe=b9dddc1ef8) | Sep 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [abad0fc559](https://linux-hardware.org/?probe=abad0fc559) | Sep 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [999a713227](https://linux-hardware.org/?probe=999a713227) | Sep 05, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [8f2ba921b5](https://linux-hardware.org/?probe=8f2ba921b5) | Sep 05, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [6d7631e83a](https://linux-hardware.org/?probe=6d7631e83a) | Sep 05, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [304ccb5f7e](https://linux-hardware.org/?probe=304ccb5f7e) | Sep 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [6d1d81c7b3](https://linux-hardware.org/?probe=6d1d81c7b3) | Sep 05, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [ce571e2d16](https://linux-hardware.org/?probe=ce571e2d16) | Sep 05, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [4297e9f110](https://linux-hardware.org/?probe=4297e9f110) | Sep 05, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e6eb36b583](https://linux-hardware.org/?probe=e6eb36b583) | Sep 05, 2023 |
| Dell          | Latitude 7390               | Notebook    | [4d913a8444](https://linux-hardware.org/?probe=4d913a8444) | Sep 05, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [7647c25446](https://linux-hardware.org/?probe=7647c25446) | Sep 05, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [9051992ac5](https://linux-hardware.org/?probe=9051992ac5) | Sep 05, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [6a1b31cf59](https://linux-hardware.org/?probe=6a1b31cf59) | Sep 05, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [cafe064514](https://linux-hardware.org/?probe=cafe064514) | Sep 05, 2023 |
| Lenovo        | ThinkPad T520 4243WCR       | Notebook    | [181ef642cd](https://linux-hardware.org/?probe=181ef642cd) | Sep 05, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2fe06014b3](https://linux-hardware.org/?probe=2fe06014b3) | Sep 05, 2023 |
| HP            | 1495                        | Desktop     | [272f11edff](https://linux-hardware.org/?probe=272f11edff) | Sep 05, 2023 |
| Dell          | Latitude 7390               | Notebook    | [2c6e7f955b](https://linux-hardware.org/?probe=2c6e7f955b) | Sep 05, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [25b4eff820](https://linux-hardware.org/?probe=25b4eff820) | Sep 05, 2023 |
| HP            | Notebook                    | Notebook    | [76a4d54b3b](https://linux-hardware.org/?probe=76a4d54b3b) | Sep 04, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [8e4830d581](https://linux-hardware.org/?probe=8e4830d581) | Sep 04, 2023 |
| MSI           | H61M-P21                    | Desktop     | [9eddb8442b](https://linux-hardware.org/?probe=9eddb8442b) | Sep 04, 2023 |
| Dell          | Latitude 7390               | Notebook    | [cdee70b142](https://linux-hardware.org/?probe=cdee70b142) | Sep 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [435d20add8](https://linux-hardware.org/?probe=435d20add8) | Sep 04, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [c1a456e342](https://linux-hardware.org/?probe=c1a456e342) | Sep 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [daeb81e2f6](https://linux-hardware.org/?probe=daeb81e2f6) | Sep 04, 2023 |
| MSI           | B85M-E33                    | Desktop     | [13b7edd351](https://linux-hardware.org/?probe=13b7edd351) | Sep 04, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [6dd9f72144](https://linux-hardware.org/?probe=6dd9f72144) | Sep 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [f235f2e7ef](https://linux-hardware.org/?probe=f235f2e7ef) | Sep 04, 2023 |
| eMachines     | E725                        | Notebook    | [cb1c5bd673](https://linux-hardware.org/?probe=cb1c5bd673) | Sep 03, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [90fb74ac63](https://linux-hardware.org/?probe=90fb74ac63) | Sep 03, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [3e196c9509](https://linux-hardware.org/?probe=3e196c9509) | Sep 03, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [a6957d8672](https://linux-hardware.org/?probe=a6957d8672) | Sep 03, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [8bbf469df8](https://linux-hardware.org/?probe=8bbf469df8) | Sep 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [c450c306b1](https://linux-hardware.org/?probe=c450c306b1) | Sep 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [a9a436edee](https://linux-hardware.org/?probe=a9a436edee) | Sep 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [f56611f610](https://linux-hardware.org/?probe=f56611f610) | Sep 03, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [55bb236bde](https://linux-hardware.org/?probe=55bb236bde) | Sep 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S2KV20    | Notebook    | [248ef69016](https://linux-hardware.org/?probe=248ef69016) | Sep 03, 2023 |
| AZW           | U59                         | Desktop     | [98e1e109a5](https://linux-hardware.org/?probe=98e1e109a5) | Sep 03, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [29553c1c51](https://linux-hardware.org/?probe=29553c1c51) | Sep 03, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [87cb36af8d](https://linux-hardware.org/?probe=87cb36af8d) | Sep 03, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [289dd0308b](https://linux-hardware.org/?probe=289dd0308b) | Sep 02, 2023 |
| HP            | 255 G2                      | Notebook    | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [adaa4a1718](https://linux-hardware.org/?probe=adaa4a1718) | Sep 02, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [22c3bee6fa](https://linux-hardware.org/?probe=22c3bee6fa) | Sep 02, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [c1ad093dbb](https://linux-hardware.org/?probe=c1ad093dbb) | Sep 02, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [b6a5325068](https://linux-hardware.org/?probe=b6a5325068) | Sep 02, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [1cbc463a43](https://linux-hardware.org/?probe=1cbc463a43) | Sep 02, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [ab9746582a](https://linux-hardware.org/?probe=ab9746582a) | Sep 02, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [091c787432](https://linux-hardware.org/?probe=091c787432) | Sep 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f8bb43e243](https://linux-hardware.org/?probe=f8bb43e243) | Sep 01, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e705d0ef10](https://linux-hardware.org/?probe=e705d0ef10) | Sep 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [5e95785b8e](https://linux-hardware.org/?probe=5e95785b8e) | Sep 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c37cbe9bd9](https://linux-hardware.org/?probe=c37cbe9bd9) | Sep 01, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [e1eb9c4b56](https://linux-hardware.org/?probe=e1eb9c4b56) | Sep 01, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [d5df2de977](https://linux-hardware.org/?probe=d5df2de977) | Sep 01, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e3bd6a8273](https://linux-hardware.org/?probe=e3bd6a8273) | Aug 31, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [37523b5aa3](https://linux-hardware.org/?probe=37523b5aa3) | Aug 31, 2023 |
| MSI           | MS-7817                     | Desktop     | [badd4016f3](https://linux-hardware.org/?probe=badd4016f3) | Aug 31, 2023 |
| HP            | 339A                        | Desktop     | [4b43fa6951](https://linux-hardware.org/?probe=4b43fa6951) | Aug 31, 2023 |
| MSI           | P43i                        | Desktop     | [b7c88acd7e](https://linux-hardware.org/?probe=b7c88acd7e) | Aug 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e0c18cf228](https://linux-hardware.org/?probe=e0c18cf228) | Aug 31, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [47cb0a10f7](https://linux-hardware.org/?probe=47cb0a10f7) | Aug 31, 2023 |
| Dell          | 0TY915                      | Desktop     | [5ad1572cf2](https://linux-hardware.org/?probe=5ad1572cf2) | Aug 31, 2023 |
| Dell          | 0TY915                      | Desktop     | [e66372d79b](https://linux-hardware.org/?probe=e66372d79b) | Aug 31, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [458b3b6310](https://linux-hardware.org/?probe=458b3b6310) | Aug 31, 2023 |
| Dell          | 0XPDFK A00                  | Desktop     | [b7df67e39a](https://linux-hardware.org/?probe=b7df67e39a) | Aug 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4d1e47297b](https://linux-hardware.org/?probe=4d1e47297b) | Aug 30, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [ddcb97361b](https://linux-hardware.org/?probe=ddcb97361b) | Aug 30, 2023 |
| ASUSTek       | EB1035                      | All in one  | [ea73e26c86](https://linux-hardware.org/?probe=ea73e26c86) | Aug 30, 2023 |
| HP            | 8265                        | Desktop     | [2c26b2823c](https://linux-hardware.org/?probe=2c26b2823c) | Aug 30, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [0eddf6dfcd](https://linux-hardware.org/?probe=0eddf6dfcd) | Aug 30, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ba4d78320f](https://linux-hardware.org/?probe=ba4d78320f) | Aug 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8e595f3214](https://linux-hardware.org/?probe=8e595f3214) | Aug 30, 2023 |
| Dell          | 0DR845                      | Desktop     | [2b4ff07956](https://linux-hardware.org/?probe=2b4ff07956) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [41797b2df4](https://linux-hardware.org/?probe=41797b2df4) | Aug 30, 2023 |
| HP            | 250 G1                      | Notebook    | [6821396f96](https://linux-hardware.org/?probe=6821396f96) | Aug 29, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [ebfb32e1a8](https://linux-hardware.org/?probe=ebfb32e1a8) | Aug 29, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [cc92a730bc](https://linux-hardware.org/?probe=cc92a730bc) | Aug 29, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [33fbfa4413](https://linux-hardware.org/?probe=33fbfa4413) | Aug 29, 2023 |
| Intel         | S5500HCV E40912-455         | Server      | [d6f93cea95](https://linux-hardware.org/?probe=d6f93cea95) | Aug 29, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [8a109f7691](https://linux-hardware.org/?probe=8a109f7691) | Aug 29, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [c806d70c9d](https://linux-hardware.org/?probe=c806d70c9d) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0f7047f2c2](https://linux-hardware.org/?probe=0f7047f2c2) | Aug 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [9c733aac9d](https://linux-hardware.org/?probe=9c733aac9d) | Aug 28, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3869234a03](https://linux-hardware.org/?probe=3869234a03) | Aug 28, 2023 |
| GPD           | G1619-01                    | Notebook    | [0e12028a4d](https://linux-hardware.org/?probe=0e12028a4d) | Aug 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [ebf28922af](https://linux-hardware.org/?probe=ebf28922af) | Aug 28, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [39db55a5e2](https://linux-hardware.org/?probe=39db55a5e2) | Aug 28, 2023 |
| HP            | 339A                        | Desktop     | [56775507f8](https://linux-hardware.org/?probe=56775507f8) | Aug 28, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [21b85ec9f3](https://linux-hardware.org/?probe=21b85ec9f3) | Aug 28, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [635743c7d4](https://linux-hardware.org/?probe=635743c7d4) | Aug 28, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [9b898e43e7](https://linux-hardware.org/?probe=9b898e43e7) | Aug 28, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [43c8f5f7bd](https://linux-hardware.org/?probe=43c8f5f7bd) | Aug 28, 2023 |
| Intel         | NUC13SBBi9 M58736-303       | Mini pc     | [513140b0b6](https://linux-hardware.org/?probe=513140b0b6) | Aug 28, 2023 |
| Lenovo        | ThinkPad X220 4291C84       | Notebook    | [623b0f76d1](https://linux-hardware.org/?probe=623b0f76d1) | Aug 28, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | Notebook    | [cb57dd666e](https://linux-hardware.org/?probe=cb57dd666e) | Aug 28, 2023 |
| eMachines     | E725                        | Notebook    | [415b4166b9](https://linux-hardware.org/?probe=415b4166b9) | Aug 27, 2023 |
| eMachines     | E725                        | Notebook    | [edb02e1501](https://linux-hardware.org/?probe=edb02e1501) | Aug 27, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [c7ee25be08](https://linux-hardware.org/?probe=c7ee25be08) | Aug 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS0MN0A    | Notebook    | [4cfb3bf1b1](https://linux-hardware.org/?probe=4cfb3bf1b1) | Aug 27, 2023 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [579e64039e](https://linux-hardware.org/?probe=579e64039e) | Aug 27, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [28217feff7](https://linux-hardware.org/?probe=28217feff7) | Aug 27, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [7f67a243d7](https://linux-hardware.org/?probe=7f67a243d7) | Aug 27, 2023 |
| HP            | Compaq 6730b (NB025EA#AB... | Notebook    | [3f742c8393](https://linux-hardware.org/?probe=3f742c8393) | Aug 27, 2023 |
| HP            | Compaq 6730b (NB025EA#AB... | Notebook    | [3b462ade1a](https://linux-hardware.org/?probe=3b462ade1a) | Aug 27, 2023 |
| ASRock        | B85M                        | Desktop     | [e1030ad449](https://linux-hardware.org/?probe=e1030ad449) | Aug 27, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [bfaf77795d](https://linux-hardware.org/?probe=bfaf77795d) | Aug 27, 2023 |
| HP            | 250 G1                      | Notebook    | [27baf9b755](https://linux-hardware.org/?probe=27baf9b755) | Aug 27, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [6641de7018](https://linux-hardware.org/?probe=6641de7018) | Aug 27, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [f153f48649](https://linux-hardware.org/?probe=f153f48649) | Aug 27, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [7a3378b6eb](https://linux-hardware.org/?probe=7a3378b6eb) | Aug 27, 2023 |
| HP            | 650                         | Notebook    | [ed399f8cfb](https://linux-hardware.org/?probe=ed399f8cfb) | Aug 27, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [679808ec60](https://linux-hardware.org/?probe=679808ec60) | Aug 26, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | Notebook    | [e8e1a3d429](https://linux-hardware.org/?probe=e8e1a3d429) | Aug 26, 2023 |
| Lenovo        | ThinkPad T470 20HES58A1L    | Notebook    | [b1fe190515](https://linux-hardware.org/?probe=b1fe190515) | Aug 26, 2023 |
| HP            | 3047h                       | Desktop     | [28037f3ded](https://linux-hardware.org/?probe=28037f3ded) | Aug 26, 2023 |
| HP            | 3047h                       | Desktop     | [dd6e5ce100](https://linux-hardware.org/?probe=dd6e5ce100) | Aug 26, 2023 |
| HP            | 8265                        | Desktop     | [39f6952188](https://linux-hardware.org/?probe=39f6952188) | Aug 26, 2023 |
| ASRock        | B85M                        | Desktop     | [70af81b1a1](https://linux-hardware.org/?probe=70af81b1a1) | Aug 26, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [56f9a82624](https://linux-hardware.org/?probe=56f9a82624) | Aug 26, 2023 |
| Lenovo        | ThinkPad T470 20HES58A1L    | Notebook    | [bc1cdf2ce7](https://linux-hardware.org/?probe=bc1cdf2ce7) | Aug 26, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [855ad99ea5](https://linux-hardware.org/?probe=855ad99ea5) | Aug 26, 2023 |
| MSI           | P43i                        | Desktop     | [3f3ea5ff94](https://linux-hardware.org/?probe=3f3ea5ff94) | Aug 26, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [e226d45872](https://linux-hardware.org/?probe=e226d45872) | Aug 26, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [7db44bc8af](https://linux-hardware.org/?probe=7db44bc8af) | Aug 26, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | Notebook    | [d8b8b7565b](https://linux-hardware.org/?probe=d8b8b7565b) | Aug 26, 2023 |
| HP            | 250 G1                      | Notebook    | [d2989d3be0](https://linux-hardware.org/?probe=d2989d3be0) | Aug 26, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [b1e5815ba9](https://linux-hardware.org/?probe=b1e5815ba9) | Aug 26, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [8a59de1138](https://linux-hardware.org/?probe=8a59de1138) | Aug 26, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [55da0d1667](https://linux-hardware.org/?probe=55da0d1667) | Aug 26, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [5e884e12a0](https://linux-hardware.org/?probe=5e884e12a0) | Aug 26, 2023 |
| Dell          | Latitude E6410              | Notebook    | [20134aee31](https://linux-hardware.org/?probe=20134aee31) | Aug 25, 2023 |
| MSI           | MS-7817                     | Desktop     | [9b7cfe20df](https://linux-hardware.org/?probe=9b7cfe20df) | Aug 25, 2023 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [675c426397](https://linux-hardware.org/?probe=675c426397) | Aug 25, 2023 |
| Dell          | Latitude E5520              | Notebook    | [6e27e77275](https://linux-hardware.org/?probe=6e27e77275) | Aug 25, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [de7752b138](https://linux-hardware.org/?probe=de7752b138) | Aug 25, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [1dc34b7cc5](https://linux-hardware.org/?probe=1dc34b7cc5) | Aug 25, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [7d90deb5b1](https://linux-hardware.org/?probe=7d90deb5b1) | Aug 25, 2023 |
| Mediacom      | GTZS                        | Notebook    | [8b40b2b9fc](https://linux-hardware.org/?probe=8b40b2b9fc) | Aug 24, 2023 |
| Dell          | Latitude E6220              | Notebook    | [6afbb8e146](https://linux-hardware.org/?probe=6afbb8e146) | Aug 24, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [1bb6f8d738](https://linux-hardware.org/?probe=1bb6f8d738) | Aug 24, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [74fe0374b3](https://linux-hardware.org/?probe=74fe0374b3) | Aug 23, 2023 |
| Dell          | Precision M6600             | Notebook    | [60acc9bcb0](https://linux-hardware.org/?probe=60acc9bcb0) | Aug 23, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [9d18657882](https://linux-hardware.org/?probe=9d18657882) | Aug 22, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [4cb50f9265](https://linux-hardware.org/?probe=4cb50f9265) | Aug 22, 2023 |
| HP            | Presario CQ57               | Notebook    | [bfc59ff9cd](https://linux-hardware.org/?probe=bfc59ff9cd) | Aug 22, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [54ce83065f](https://linux-hardware.org/?probe=54ce83065f) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| ASUSTek       | K55A                        | Notebook    | [090e4d0a73](https://linux-hardware.org/?probe=090e4d0a73) | Aug 20, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [76d74daf52](https://linux-hardware.org/?probe=76d74daf52) | Aug 19, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [2f0cd6e6d3](https://linux-hardware.org/?probe=2f0cd6e6d3) | Aug 19, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [25fbe59866](https://linux-hardware.org/?probe=25fbe59866) | Aug 19, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [a6cf8bf5f2](https://linux-hardware.org/?probe=a6cf8bf5f2) | Aug 19, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [97a587e6ad](https://linux-hardware.org/?probe=97a587e6ad) | Aug 19, 2023 |
| Dell          | Latitude E6230              | Notebook    | [7888184dd0](https://linux-hardware.org/?probe=7888184dd0) | Aug 19, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1672d92536](https://linux-hardware.org/?probe=1672d92536) | Aug 19, 2023 |
| HP            | Notebook                    | Notebook    | [661cb258ef](https://linux-hardware.org/?probe=661cb258ef) | Aug 19, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [5ac356a22f](https://linux-hardware.org/?probe=5ac356a22f) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [c6f3f044c9](https://linux-hardware.org/?probe=c6f3f044c9) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [9734816ff1](https://linux-hardware.org/?probe=9734816ff1) | Aug 19, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [9f5242decc](https://linux-hardware.org/?probe=9f5242decc) | Aug 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [53a81617e7](https://linux-hardware.org/?probe=53a81617e7) | Aug 19, 2023 |
| Dell          | Precision M6600             | Notebook    | [15df8fbaaf](https://linux-hardware.org/?probe=15df8fbaaf) | Aug 18, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [68bfd376a0](https://linux-hardware.org/?probe=68bfd376a0) | Aug 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [84cbd742a1](https://linux-hardware.org/?probe=84cbd742a1) | Aug 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [0edbb9bdf1](https://linux-hardware.org/?probe=0edbb9bdf1) | Aug 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [645171b203](https://linux-hardware.org/?probe=645171b203) | Aug 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c093ae6eb5](https://linux-hardware.org/?probe=c093ae6eb5) | Aug 17, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [79d8f79efe](https://linux-hardware.org/?probe=79d8f79efe) | Aug 17, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [b48511c64c](https://linux-hardware.org/?probe=b48511c64c) | Aug 16, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [810d33b380](https://linux-hardware.org/?probe=810d33b380) | Aug 16, 2023 |
| HP            | 1495                        | Desktop     | [1d04585fac](https://linux-hardware.org/?probe=1d04585fac) | Aug 16, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [529613b5c7](https://linux-hardware.org/?probe=529613b5c7) | Aug 15, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8f1803298d](https://linux-hardware.org/?probe=8f1803298d) | Aug 15, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [7b48c318ed](https://linux-hardware.org/?probe=7b48c318ed) | Aug 15, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [0d11484b59](https://linux-hardware.org/?probe=0d11484b59) | Aug 15, 2023 |
| Dell          | Latitude E6410              | Notebook    | [9cc0b91505](https://linux-hardware.org/?probe=9cc0b91505) | Aug 14, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [aa3414ebdc](https://linux-hardware.org/?probe=aa3414ebdc) | Aug 14, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d5b2c3b80a](https://linux-hardware.org/?probe=d5b2c3b80a) | Aug 14, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [013e2fdac5](https://linux-hardware.org/?probe=013e2fdac5) | Aug 14, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [72977f6f8a](https://linux-hardware.org/?probe=72977f6f8a) | Aug 13, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [b718d1c1f8](https://linux-hardware.org/?probe=b718d1c1f8) | Aug 13, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [3e830ffabc](https://linux-hardware.org/?probe=3e830ffabc) | Aug 12, 2023 |
| HP            | 3395                        | All in one  | [1dc6b38792](https://linux-hardware.org/?probe=1dc6b38792) | Aug 12, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [84cbdf027b](https://linux-hardware.org/?probe=84cbdf027b) | Aug 12, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8037585070](https://linux-hardware.org/?probe=8037585070) | Aug 12, 2023 |
| HP            | 1495                        | Desktop     | [837afb7bfa](https://linux-hardware.org/?probe=837afb7bfa) | Aug 12, 2023 |
| ASUSTek       | K55A                        | Notebook    | [bf260cea2c](https://linux-hardware.org/?probe=bf260cea2c) | Aug 11, 2023 |
| HP            | 1495                        | Desktop     | [9e8b73f16e](https://linux-hardware.org/?probe=9e8b73f16e) | Aug 11, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [3c7140c389](https://linux-hardware.org/?probe=3c7140c389) | Aug 11, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [17e503622d](https://linux-hardware.org/?probe=17e503622d) | Aug 11, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [485a8bf15d](https://linux-hardware.org/?probe=485a8bf15d) | Aug 10, 2023 |
| HP            | 1495                        | Desktop     | [6c458bf059](https://linux-hardware.org/?probe=6c458bf059) | Aug 10, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [ae87c6938f](https://linux-hardware.org/?probe=ae87c6938f) | Aug 10, 2023 |
| HP            | 0AA4h                       | Desktop     | [e4da6a6aaf](https://linux-hardware.org/?probe=e4da6a6aaf) | Aug 09, 2023 |
| HP            | Notebook                    | Notebook    | [59e006f729](https://linux-hardware.org/?probe=59e006f729) | Aug 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [4081f7bbda](https://linux-hardware.org/?probe=4081f7bbda) | Aug 09, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [e28870563c](https://linux-hardware.org/?probe=e28870563c) | Aug 09, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [914ff5745c](https://linux-hardware.org/?probe=914ff5745c) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [6601d0d136](https://linux-hardware.org/?probe=6601d0d136) | Aug 07, 2023 |
| HP            | Notebook                    | Notebook    | [5cfbf14023](https://linux-hardware.org/?probe=5cfbf14023) | Aug 07, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [64dc45c007](https://linux-hardware.org/?probe=64dc45c007) | Aug 07, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [b62c8c40f5](https://linux-hardware.org/?probe=b62c8c40f5) | Aug 07, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [f3644b56ad](https://linux-hardware.org/?probe=f3644b56ad) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [35bb5f3e65](https://linux-hardware.org/?probe=35bb5f3e65) | Aug 06, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [9aaaaec131](https://linux-hardware.org/?probe=9aaaaec131) | Aug 05, 2023 |
| HP            | 1588h                       | Desktop     | [1e041c2365](https://linux-hardware.org/?probe=1e041c2365) | Aug 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [96b8677500](https://linux-hardware.org/?probe=96b8677500) | Aug 05, 2023 |
| HP            | 1495                        | Desktop     | [17ae98cda8](https://linux-hardware.org/?probe=17ae98cda8) | Aug 05, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [cf49ab1496](https://linux-hardware.org/?probe=cf49ab1496) | Aug 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [49e694bb22](https://linux-hardware.org/?probe=49e694bb22) | Aug 04, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [effe3c3d6d](https://linux-hardware.org/?probe=effe3c3d6d) | Aug 04, 2023 |
| Dell          | Latitude E6420              | Notebook    | [4f67a219dc](https://linux-hardware.org/?probe=4f67a219dc) | Aug 04, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [91b8e07f0d](https://linux-hardware.org/?probe=91b8e07f0d) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [30b14bc4f6](https://linux-hardware.org/?probe=30b14bc4f6) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [0e36ac41e4](https://linux-hardware.org/?probe=0e36ac41e4) | Aug 04, 2023 |
| HP            | 1495                        | Desktop     | [75dae4c3a6](https://linux-hardware.org/?probe=75dae4c3a6) | Aug 04, 2023 |
| MSI           | P43i                        | Desktop     | [683b26e344](https://linux-hardware.org/?probe=683b26e344) | Aug 03, 2023 |
| HPE           | ML10Gen9                    | Server      | [f5115c8a74](https://linux-hardware.org/?probe=f5115c8a74) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [4c45ace98b](https://linux-hardware.org/?probe=4c45ace98b) | Aug 03, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [b7ffeb681e](https://linux-hardware.org/?probe=b7ffeb681e) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [b8ece2fce1](https://linux-hardware.org/?probe=b8ece2fce1) | Aug 03, 2023 |
| Medion        | MS-7748                     | Desktop     | [413b9e74a6](https://linux-hardware.org/?probe=413b9e74a6) | Aug 03, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [e47b01848a](https://linux-hardware.org/?probe=e47b01848a) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c94a18b924](https://linux-hardware.org/?probe=c94a18b924) | Aug 02, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [7281304bf0](https://linux-hardware.org/?probe=7281304bf0) | Aug 02, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [52c54dc66e](https://linux-hardware.org/?probe=52c54dc66e) | Aug 02, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [99cae22846](https://linux-hardware.org/?probe=99cae22846) | Aug 02, 2023 |
| HP            | Notebook                    | Notebook    | [b73fa31837](https://linux-hardware.org/?probe=b73fa31837) | Aug 02, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [56573f8499](https://linux-hardware.org/?probe=56573f8499) | Aug 01, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [8aaca0803f](https://linux-hardware.org/?probe=8aaca0803f) | Jul 31, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [6202f3b97e](https://linux-hardware.org/?probe=6202f3b97e) | Jul 31, 2023 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [9ce45f234a](https://linux-hardware.org/?probe=9ce45f234a) | Jul 31, 2023 |
| HP            | Notebook                    | Notebook    | [329c725795](https://linux-hardware.org/?probe=329c725795) | Jul 31, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [908f49c376](https://linux-hardware.org/?probe=908f49c376) | Jul 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5bf8462b77](https://linux-hardware.org/?probe=5bf8462b77) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [250fc62328](https://linux-hardware.org/?probe=250fc62328) | Jul 30, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [c3b01ce24d](https://linux-hardware.org/?probe=c3b01ce24d) | Jul 30, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [8e26feba38](https://linux-hardware.org/?probe=8e26feba38) | Jul 30, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [7bcd0d7683](https://linux-hardware.org/?probe=7bcd0d7683) | Jul 30, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [6fd92e6150](https://linux-hardware.org/?probe=6fd92e6150) | Jul 29, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [471516b82e](https://linux-hardware.org/?probe=471516b82e) | Jul 29, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [3c326304ab](https://linux-hardware.org/?probe=3c326304ab) | Jul 29, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [4e19477a40](https://linux-hardware.org/?probe=4e19477a40) | Jul 29, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [404f75d04c](https://linux-hardware.org/?probe=404f75d04c) | Jul 28, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [19d341d49d](https://linux-hardware.org/?probe=19d341d49d) | Jul 28, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [a7c322fa40](https://linux-hardware.org/?probe=a7c322fa40) | Jul 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [385c97c1d3](https://linux-hardware.org/?probe=385c97c1d3) | Jul 28, 2023 |
| HP            | 1495                        | Desktop     | [b4e2031d1e](https://linux-hardware.org/?probe=b4e2031d1e) | Jul 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [ea550fb04c](https://linux-hardware.org/?probe=ea550fb04c) | Jul 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5b17937c10](https://linux-hardware.org/?probe=5b17937c10) | Jul 26, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [ebaacb8057](https://linux-hardware.org/?probe=ebaacb8057) | Jul 26, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [3988b909c7](https://linux-hardware.org/?probe=3988b909c7) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [32b57e4adb](https://linux-hardware.org/?probe=32b57e4adb) | Jul 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [de48c51732](https://linux-hardware.org/?probe=de48c51732) | Jul 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [f2bef973eb](https://linux-hardware.org/?probe=f2bef973eb) | Jul 26, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [04a75d9e0c](https://linux-hardware.org/?probe=04a75d9e0c) | Jul 26, 2023 |
| Lenovo        | ThinkPad T500 2056CL8       | Notebook    | [180a80b4fe](https://linux-hardware.org/?probe=180a80b4fe) | Jul 26, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [58d8bbebcd](https://linux-hardware.org/?probe=58d8bbebcd) | Jul 26, 2023 |
| HP            | Presario CQ56               | Notebook    | [e0e6c2bce2](https://linux-hardware.org/?probe=e0e6c2bce2) | Jul 26, 2023 |
| HP            | Presario CQ56               | Notebook    | [21c97fcc9c](https://linux-hardware.org/?probe=21c97fcc9c) | Jul 26, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [1711396786](https://linux-hardware.org/?probe=1711396786) | Jul 25, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [e367e06cac](https://linux-hardware.org/?probe=e367e06cac) | Jul 25, 2023 |
| HP            | 8265                        | Desktop     | [96a99f0e8f](https://linux-hardware.org/?probe=96a99f0e8f) | Jul 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [42ee46f6c4](https://linux-hardware.org/?probe=42ee46f6c4) | Jul 25, 2023 |
| ASUSTek       | UN45                        | Desktop     | [ea2bebc887](https://linux-hardware.org/?probe=ea2bebc887) | Jul 25, 2023 |
| Acer          | Veriton M4610G              | Desktop     | [aef65d0501](https://linux-hardware.org/?probe=aef65d0501) | Jul 25, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4c5c8def02](https://linux-hardware.org/?probe=4c5c8def02) | Jul 24, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [828f20c8bb](https://linux-hardware.org/?probe=828f20c8bb) | Jul 24, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [516f42eb27](https://linux-hardware.org/?probe=516f42eb27) | Jul 23, 2023 |
| Acer          | Veriton M4610G              | Desktop     | [57cdc7820f](https://linux-hardware.org/?probe=57cdc7820f) | Jul 23, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [91d19df4b4](https://linux-hardware.org/?probe=91d19df4b4) | Jul 23, 2023 |
| HP            | 8265                        | Desktop     | [0e5a193692](https://linux-hardware.org/?probe=0e5a193692) | Jul 23, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [441c83b694](https://linux-hardware.org/?probe=441c83b694) | Jul 23, 2023 |
| HP            | 1495                        | Desktop     | [a9bd3f59e8](https://linux-hardware.org/?probe=a9bd3f59e8) | Jul 23, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [11a6a3a607](https://linux-hardware.org/?probe=11a6a3a607) | Jul 23, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [8f2c838141](https://linux-hardware.org/?probe=8f2c838141) | Jul 22, 2023 |
| Dell          | 0PU052                      | Desktop     | [43454a5114](https://linux-hardware.org/?probe=43454a5114) | Jul 22, 2023 |
| Dell          | 0PU052                      | Desktop     | [b1ba2d4239](https://linux-hardware.org/?probe=b1ba2d4239) | Jul 22, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [c4da72acde](https://linux-hardware.org/?probe=c4da72acde) | Jul 21, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [2d8ae98d9c](https://linux-hardware.org/?probe=2d8ae98d9c) | Jul 21, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [e022b7bd64](https://linux-hardware.org/?probe=e022b7bd64) | Jul 21, 2023 |
| Dell          | Latitude E6420              | Notebook    | [35d8d85f3c](https://linux-hardware.org/?probe=35d8d85f3c) | Jul 21, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [1faafe201d](https://linux-hardware.org/?probe=1faafe201d) | Jul 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c8fa0f7219](https://linux-hardware.org/?probe=c8fa0f7219) | Jul 19, 2023 |
| ASUSTek       | ZenBook UX562IA_UM562IA     | Convertible | [08b6a97698](https://linux-hardware.org/?probe=08b6a97698) | Jul 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [4b0ce11ac5](https://linux-hardware.org/?probe=4b0ce11ac5) | Jul 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [4f7745f5de](https://linux-hardware.org/?probe=4f7745f5de) | Jul 18, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [fc1e32f937](https://linux-hardware.org/?probe=fc1e32f937) | Jul 17, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [8b9534387b](https://linux-hardware.org/?probe=8b9534387b) | Jul 17, 2023 |
| MSI           | B85M-E33                    | Desktop     | [6d2ee4521b](https://linux-hardware.org/?probe=6d2ee4521b) | Jul 17, 2023 |
| MSI           | B85M-E33                    | Desktop     | [a8bbbd8c49](https://linux-hardware.org/?probe=a8bbbd8c49) | Jul 17, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [b6925518be](https://linux-hardware.org/?probe=b6925518be) | Jul 16, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [05a330fa6c](https://linux-hardware.org/?probe=05a330fa6c) | Jul 16, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [3cc36162b8](https://linux-hardware.org/?probe=3cc36162b8) | Jul 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [60947b35a4](https://linux-hardware.org/?probe=60947b35a4) | Jul 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [856a25b9d5](https://linux-hardware.org/?probe=856a25b9d5) | Jul 16, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [1ccdf38dfa](https://linux-hardware.org/?probe=1ccdf38dfa) | Jul 16, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [71045dea53](https://linux-hardware.org/?probe=71045dea53) | Jul 16, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [f04f199334](https://linux-hardware.org/?probe=f04f199334) | Jul 16, 2023 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [b4325e403a](https://linux-hardware.org/?probe=b4325e403a) | Jul 15, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2330d7d072](https://linux-hardware.org/?probe=2330d7d072) | Jul 15, 2023 |
| Lenovo        | ThinkPad R400 7440EL1       | Notebook    | [8cc38e55a2](https://linux-hardware.org/?probe=8cc38e55a2) | Jul 15, 2023 |
| Lenovo        | ThinkPad R400 7440EL1       | Notebook    | [c0101c7ae1](https://linux-hardware.org/?probe=c0101c7ae1) | Jul 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [b5588d7209](https://linux-hardware.org/?probe=b5588d7209) | Jul 15, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [a562b6518f](https://linux-hardware.org/?probe=a562b6518f) | Jul 15, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [655cb31a8a](https://linux-hardware.org/?probe=655cb31a8a) | Jul 14, 2023 |
| DFI           | WL051                       | Desktop     | [bfe00b9eeb](https://linux-hardware.org/?probe=bfe00b9eeb) | Jul 14, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [ba12b5ff3e](https://linux-hardware.org/?probe=ba12b5ff3e) | Jul 14, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [0d773629f2](https://linux-hardware.org/?probe=0d773629f2) | Jul 14, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [e695d46a05](https://linux-hardware.org/?probe=e695d46a05) | Jul 14, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [93a455ac9b](https://linux-hardware.org/?probe=93a455ac9b) | Jul 14, 2023 |
| MSI           | B150M ECO                   | Desktop     | [84601cd9dc](https://linux-hardware.org/?probe=84601cd9dc) | Jul 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [2b75a3a2b7](https://linux-hardware.org/?probe=2b75a3a2b7) | Jul 13, 2023 |
| RM            | Mobile ONE WIDESCREEN       | Notebook    | [34e242c377](https://linux-hardware.org/?probe=34e242c377) | Jul 13, 2023 |
| RM            | Mobile ONE WIDESCREEN       | Notebook    | [bc67d71f5f](https://linux-hardware.org/?probe=bc67d71f5f) | Jul 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [5d1ed4c0a4](https://linux-hardware.org/?probe=5d1ed4c0a4) | Jul 12, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [2f3da717f3](https://linux-hardware.org/?probe=2f3da717f3) | Jul 12, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [bfe4c07a40](https://linux-hardware.org/?probe=bfe4c07a40) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [c23f2219b4](https://linux-hardware.org/?probe=c23f2219b4) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [e169b67c63](https://linux-hardware.org/?probe=e169b67c63) | Jul 12, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [1c7a630efb](https://linux-hardware.org/?probe=1c7a630efb) | Jul 12, 2023 |
| Toshiba       | Satellite C55-A-1NV         | Notebook    | [8528943b9e](https://linux-hardware.org/?probe=8528943b9e) | Jul 11, 2023 |
| Toshiba       | Satellite C55-A-1NV         | Notebook    | [1f9c336539](https://linux-hardware.org/?probe=1f9c336539) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 4730s               | Notebook    | [0b6a6c7260](https://linux-hardware.org/?probe=0b6a6c7260) | Jul 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [84088522ca](https://linux-hardware.org/?probe=84088522ca) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| eMachines     | E725                        | Notebook    | [69e7b54469](https://linux-hardware.org/?probe=69e7b54469) | Jul 10, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [08ae4ea22e](https://linux-hardware.org/?probe=08ae4ea22e) | Jul 09, 2023 |
| eMachines     | E725                        | Notebook    | [307f75ef0a](https://linux-hardware.org/?probe=307f75ef0a) | Jul 09, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [fe0bc25044](https://linux-hardware.org/?probe=fe0bc25044) | Jul 09, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [70e2ac254a](https://linux-hardware.org/?probe=70e2ac254a) | Jul 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [657750190f](https://linux-hardware.org/?probe=657750190f) | Jul 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [69c5198a22](https://linux-hardware.org/?probe=69c5198a22) | Jul 08, 2023 |
| eMachines     | E725                        | Notebook    | [c70b217933](https://linux-hardware.org/?probe=c70b217933) | Jul 08, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [81dd9a0120](https://linux-hardware.org/?probe=81dd9a0120) | Jul 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [6965fec932](https://linux-hardware.org/?probe=6965fec932) | Jul 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [4e6e8dc45b](https://linux-hardware.org/?probe=4e6e8dc45b) | Jul 08, 2023 |
| Dell          | Latitude E6220              | Notebook    | [d853b49fc7](https://linux-hardware.org/?probe=d853b49fc7) | Jul 08, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [59c2893e1a](https://linux-hardware.org/?probe=59c2893e1a) | Jul 08, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [cd368fbd36](https://linux-hardware.org/?probe=cd368fbd36) | Jul 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [393ad4fc5d](https://linux-hardware.org/?probe=393ad4fc5d) | Jul 07, 2023 |
| Lenovo        | 20RD001FHV                  | Notebook    | [79166ca12f](https://linux-hardware.org/?probe=79166ca12f) | Jul 07, 2023 |
| Lenovo        | 20RD001FHV                  | Notebook    | [de3ed49995](https://linux-hardware.org/?probe=de3ed49995) | Jul 07, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [5d03b4b2ad](https://linux-hardware.org/?probe=5d03b4b2ad) | Jul 07, 2023 |
| Sony          | VPCYB3V1E                   | Notebook    | [2dd9b76ce0](https://linux-hardware.org/?probe=2dd9b76ce0) | Jul 06, 2023 |
| Intel         | NUC7i5BNB J31144-314        | Mini pc     | [8e5fbbccbf](https://linux-hardware.org/?probe=8e5fbbccbf) | Jul 06, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [5a62a75599](https://linux-hardware.org/?probe=5a62a75599) | Jul 05, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [713b52b0c5](https://linux-hardware.org/?probe=713b52b0c5) | Jul 05, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [d992b0a60f](https://linux-hardware.org/?probe=d992b0a60f) | Jul 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [bd3b079d0d](https://linux-hardware.org/?probe=bd3b079d0d) | Jul 04, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [11537fb0f5](https://linux-hardware.org/?probe=11537fb0f5) | Jul 04, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16IAH7 8... | Notebook    | [ad57a8dd50](https://linux-hardware.org/?probe=ad57a8dd50) | Jul 04, 2023 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [7390114024](https://linux-hardware.org/?probe=7390114024) | Jul 03, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [fe616ea0ed](https://linux-hardware.org/?probe=fe616ea0ed) | Jul 03, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [84a32e1b42](https://linux-hardware.org/?probe=84a32e1b42) | Jul 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [9393d317b6](https://linux-hardware.org/?probe=9393d317b6) | Jul 03, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [22879dbc9e](https://linux-hardware.org/?probe=22879dbc9e) | Jul 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [2a7725896c](https://linux-hardware.org/?probe=2a7725896c) | Jul 03, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [496b83b6b8](https://linux-hardware.org/?probe=496b83b6b8) | Jul 03, 2023 |
| eMachines     | E725                        | Notebook    | [ca2b670023](https://linux-hardware.org/?probe=ca2b670023) | Jul 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [cac603cdf3](https://linux-hardware.org/?probe=cac603cdf3) | Jul 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [5f6fc07aaa](https://linux-hardware.org/?probe=5f6fc07aaa) | Jul 03, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [efa8ecd790](https://linux-hardware.org/?probe=efa8ecd790) | Jul 03, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [72af61849b](https://linux-hardware.org/?probe=72af61849b) | Jul 03, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [eb7ec8410d](https://linux-hardware.org/?probe=eb7ec8410d) | Jul 02, 2023 |
| eMachines     | E725                        | Notebook    | [622425a84f](https://linux-hardware.org/?probe=622425a84f) | Jul 02, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [ef1c856eb5](https://linux-hardware.org/?probe=ef1c856eb5) | Jul 02, 2023 |
| AOpen         | D1009 A1A4                  | Desktop     | [2819e086aa](https://linux-hardware.org/?probe=2819e086aa) | Jul 02, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | Notebook    | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [b27b2b3825](https://linux-hardware.org/?probe=b27b2b3825) | Jul 01, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [e50079b95e](https://linux-hardware.org/?probe=e50079b95e) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [b98b20a82c](https://linux-hardware.org/?probe=b98b20a82c) | Jul 01, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b49269ab3c](https://linux-hardware.org/?probe=b49269ab3c) | Jul 01, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [ca1817783e](https://linux-hardware.org/?probe=ca1817783e) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [6484578658](https://linux-hardware.org/?probe=6484578658) | Jul 01, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [c55a78c98a](https://linux-hardware.org/?probe=c55a78c98a) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [55bfc9f544](https://linux-hardware.org/?probe=55bfc9f544) | Jul 01, 2023 |
| HP            | 650                         | Notebook    | [279f48a7df](https://linux-hardware.org/?probe=279f48a7df) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [916b60f6f7](https://linux-hardware.org/?probe=916b60f6f7) | Jun 30, 2023 |
| HP            | Notebook                    | Notebook    | [552c6713e1](https://linux-hardware.org/?probe=552c6713e1) | Jun 30, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [908af533fc](https://linux-hardware.org/?probe=908af533fc) | Jun 30, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [a7bcb95d10](https://linux-hardware.org/?probe=a7bcb95d10) | Jun 30, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [298a4bf290](https://linux-hardware.org/?probe=298a4bf290) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | Notebook    | [9d40263129](https://linux-hardware.org/?probe=9d40263129) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | Notebook    | [4e47d108a0](https://linux-hardware.org/?probe=4e47d108a0) | Jun 29, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [76e11b36e9](https://linux-hardware.org/?probe=76e11b36e9) | Jun 28, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [344a5eda20](https://linux-hardware.org/?probe=344a5eda20) | Jun 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [565c1ea1c2](https://linux-hardware.org/?probe=565c1ea1c2) | Jun 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [545a2c4e26](https://linux-hardware.org/?probe=545a2c4e26) | Jun 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d3f7bcfb2c](https://linux-hardware.org/?probe=d3f7bcfb2c) | Jun 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1efefadbdf](https://linux-hardware.org/?probe=1efefadbdf) | Jun 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e304e9beeb](https://linux-hardware.org/?probe=e304e9beeb) | Jun 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [126187748f](https://linux-hardware.org/?probe=126187748f) | Jun 27, 2023 |
| eMachines     | E725                        | Notebook    | [e1ed487442](https://linux-hardware.org/?probe=e1ed487442) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [922c017262](https://linux-hardware.org/?probe=922c017262) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [fe211e4239](https://linux-hardware.org/?probe=fe211e4239) | Jun 26, 2023 |
| eMachines     | E725                        | Notebook    | [909f61c87a](https://linux-hardware.org/?probe=909f61c87a) | Jun 26, 2023 |
| HP            | Notebook                    | Notebook    | [ce52423528](https://linux-hardware.org/?probe=ce52423528) | Jun 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [c463ab7b16](https://linux-hardware.org/?probe=c463ab7b16) | Jun 26, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [604d6b2b6f](https://linux-hardware.org/?probe=604d6b2b6f) | Jun 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [bf911964a8](https://linux-hardware.org/?probe=bf911964a8) | Jun 26, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [e094f469bc](https://linux-hardware.org/?probe=e094f469bc) | Jun 25, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [b26a7fb008](https://linux-hardware.org/?probe=b26a7fb008) | Jun 25, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [04f61a169e](https://linux-hardware.org/?probe=04f61a169e) | Jun 25, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [839490cb5a](https://linux-hardware.org/?probe=839490cb5a) | Jun 25, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [43849169cb](https://linux-hardware.org/?probe=43849169cb) | Jun 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e8f8b7e986](https://linux-hardware.org/?probe=e8f8b7e986) | Jun 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e218b300b7](https://linux-hardware.org/?probe=e218b300b7) | Jun 25, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [2b3a2327fb](https://linux-hardware.org/?probe=2b3a2327fb) | Jun 24, 2023 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [75cab0a675](https://linux-hardware.org/?probe=75cab0a675) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [186b2c5cb7](https://linux-hardware.org/?probe=186b2c5cb7) | Jun 24, 2023 |
| HP            | 8265                        | Desktop     | [863a585141](https://linux-hardware.org/?probe=863a585141) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [84239b2594](https://linux-hardware.org/?probe=84239b2594) | Jun 23, 2023 |
| HP            | Notebook                    | Notebook    | [6710ed8c9c](https://linux-hardware.org/?probe=6710ed8c9c) | Jun 21, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d661316023](https://linux-hardware.org/?probe=d661316023) | Jun 21, 2023 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [a3f0d3cbc6](https://linux-hardware.org/?probe=a3f0d3cbc6) | Jun 21, 2023 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [8cfeb06220](https://linux-hardware.org/?probe=8cfeb06220) | Jun 21, 2023 |
| Dell          | Latitude E6410              | Notebook    | [1d89edd254](https://linux-hardware.org/?probe=1d89edd254) | Jun 20, 2023 |
| Dell          | Latitude E6410              | Notebook    | [5230b985a8](https://linux-hardware.org/?probe=5230b985a8) | Jun 20, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [a6f14223ae](https://linux-hardware.org/?probe=a6f14223ae) | Jun 20, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [076a78c151](https://linux-hardware.org/?probe=076a78c151) | Jun 20, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9dca1fab41](https://linux-hardware.org/?probe=9dca1fab41) | Jun 20, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [d09be5d97c](https://linux-hardware.org/?probe=d09be5d97c) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0a36c0985d](https://linux-hardware.org/?probe=0a36c0985d) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0ccace2cfb](https://linux-hardware.org/?probe=0ccace2cfb) | Jun 20, 2023 |
| eMachines     | E725                        | Notebook    | [4317f04272](https://linux-hardware.org/?probe=4317f04272) | Jun 19, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [320272d785](https://linux-hardware.org/?probe=320272d785) | Jun 19, 2023 |
| Dell          | Latitude E7470              | Notebook    | [645538d81e](https://linux-hardware.org/?probe=645538d81e) | Jun 19, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [0423e23a21](https://linux-hardware.org/?probe=0423e23a21) | Jun 19, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [b4c617c995](https://linux-hardware.org/?probe=b4c617c995) | Jun 19, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1f1209bd20](https://linux-hardware.org/?probe=1f1209bd20) | Jun 19, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [8ccea52f65](https://linux-hardware.org/?probe=8ccea52f65) | Jun 19, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0cbbe081c8](https://linux-hardware.org/?probe=0cbbe081c8) | Jun 19, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [41c5ad600b](https://linux-hardware.org/?probe=41c5ad600b) | Jun 19, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [3dacc56dd5](https://linux-hardware.org/?probe=3dacc56dd5) | Jun 18, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [b90840dbba](https://linux-hardware.org/?probe=b90840dbba) | Jun 18, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [6bd02aa0f2](https://linux-hardware.org/?probe=6bd02aa0f2) | Jun 18, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [e0d2c8f040](https://linux-hardware.org/?probe=e0d2c8f040) | Jun 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [bbc5301e6b](https://linux-hardware.org/?probe=bbc5301e6b) | Jun 17, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [77f7dcbc1d](https://linux-hardware.org/?probe=77f7dcbc1d) | Jun 17, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [a96d7f89ca](https://linux-hardware.org/?probe=a96d7f89ca) | Jun 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fa9508da6e](https://linux-hardware.org/?probe=fa9508da6e) | Jun 17, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [a1bb681c50](https://linux-hardware.org/?probe=a1bb681c50) | Jun 17, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [24624ec732](https://linux-hardware.org/?probe=24624ec732) | Jun 17, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [6fd4c94830](https://linux-hardware.org/?probe=6fd4c94830) | Jun 16, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [4f97748920](https://linux-hardware.org/?probe=4f97748920) | Jun 16, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [11c34f6cde](https://linux-hardware.org/?probe=11c34f6cde) | Jun 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [6d154340b0](https://linux-hardware.org/?probe=6d154340b0) | Jun 16, 2023 |
| eMachines     | E725                        | Notebook    | [c2ffc64913](https://linux-hardware.org/?probe=c2ffc64913) | Jun 15, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [6adbb0811a](https://linux-hardware.org/?probe=6adbb0811a) | Jun 15, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [bab5e06a26](https://linux-hardware.org/?probe=bab5e06a26) | Jun 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b560ba8109](https://linux-hardware.org/?probe=b560ba8109) | Jun 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9111abbf0e](https://linux-hardware.org/?probe=9111abbf0e) | Jun 14, 2023 |
| eMachines     | E725                        | Notebook    | [6a88f4f2be](https://linux-hardware.org/?probe=6a88f4f2be) | Jun 14, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [817c9acfa2](https://linux-hardware.org/?probe=817c9acfa2) | Jun 14, 2023 |
| MSI           | 970A-G46                    | Desktop     | [95a0297b20](https://linux-hardware.org/?probe=95a0297b20) | Jun 14, 2023 |
| Dell          | Latitude 7390               | Notebook    | [aad70ac5b5](https://linux-hardware.org/?probe=aad70ac5b5) | Jun 14, 2023 |
| MSI           | 970A-G46                    | Desktop     | [76441700d5](https://linux-hardware.org/?probe=76441700d5) | Jun 14, 2023 |
| Dell          | Latitude 7390               | Notebook    | [b718d8d672](https://linux-hardware.org/?probe=b718d8d672) | Jun 14, 2023 |
| MSI           | MS-7309                     | Desktop     | [fc85dd07ed](https://linux-hardware.org/?probe=fc85dd07ed) | Jun 14, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [26493eeedc](https://linux-hardware.org/?probe=26493eeedc) | Jun 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [03f59dc88a](https://linux-hardware.org/?probe=03f59dc88a) | Jun 13, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [807fe357c7](https://linux-hardware.org/?probe=807fe357c7) | Jun 13, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [e68c648de4](https://linux-hardware.org/?probe=e68c648de4) | Jun 13, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [058f5805e3](https://linux-hardware.org/?probe=058f5805e3) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8c939c89a3](https://linux-hardware.org/?probe=8c939c89a3) | Jun 13, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [6385fdf921](https://linux-hardware.org/?probe=6385fdf921) | Jun 13, 2023 |
| Dell          | Latitude E5520              | Notebook    | [a86c677685](https://linux-hardware.org/?probe=a86c677685) | Jun 13, 2023 |
| HP            | 250 G1                      | Notebook    | [f8406758e3](https://linux-hardware.org/?probe=f8406758e3) | Jun 13, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [9e5b8610e3](https://linux-hardware.org/?probe=9e5b8610e3) | Jun 13, 2023 |
| HP            | 339A                        | Desktop     | [a8e90edbdb](https://linux-hardware.org/?probe=a8e90edbdb) | Jun 13, 2023 |
| HP            | 250 G1                      | Notebook    | [477f9bbabd](https://linux-hardware.org/?probe=477f9bbabd) | Jun 13, 2023 |
| HP            | Notebook                    | Notebook    | [aa5016380c](https://linux-hardware.org/?probe=aa5016380c) | Jun 13, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [9347870cd0](https://linux-hardware.org/?probe=9347870cd0) | Jun 13, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [0c2fae415b](https://linux-hardware.org/?probe=0c2fae415b) | Jun 12, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [a6333257c7](https://linux-hardware.org/?probe=a6333257c7) | Jun 12, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [7d188dbdfa](https://linux-hardware.org/?probe=7d188dbdfa) | Jun 12, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [75b330369d](https://linux-hardware.org/?probe=75b330369d) | Jun 12, 2023 |
| Acer          | TravelMate P259-G2-M        | Notebook    | [abc5444c45](https://linux-hardware.org/?probe=abc5444c45) | Jun 12, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | Notebook    | [6d6fb0c276](https://linux-hardware.org/?probe=6d6fb0c276) | Jun 12, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [4b84ec2ade](https://linux-hardware.org/?probe=4b84ec2ade) | Jun 12, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [9e9746b2bc](https://linux-hardware.org/?probe=9e9746b2bc) | Jun 12, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [b2e6e1ed18](https://linux-hardware.org/?probe=b2e6e1ed18) | Jun 12, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [5e96ddeeac](https://linux-hardware.org/?probe=5e96ddeeac) | Jun 12, 2023 |
| HP            | Pavilion 17                 | Notebook    | [e6279cb0df](https://linux-hardware.org/?probe=e6279cb0df) | Jun 12, 2023 |
| Dell          | Latitude E6230              | Notebook    | [c46f103733](https://linux-hardware.org/?probe=c46f103733) | Jun 11, 2023 |
| Dell          | Latitude E6230              | Notebook    | [390606f3f6](https://linux-hardware.org/?probe=390606f3f6) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85902981fd](https://linux-hardware.org/?probe=85902981fd) | Jun 11, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [43d52c8efe](https://linux-hardware.org/?probe=43d52c8efe) | Jun 11, 2023 |
| HP            | 250 G1                      | Notebook    | [e229888d41](https://linux-hardware.org/?probe=e229888d41) | Jun 11, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [aee2df0fb7](https://linux-hardware.org/?probe=aee2df0fb7) | Jun 11, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c1f065966d](https://linux-hardware.org/?probe=c1f065966d) | Jun 11, 2023 |
| HP            | 8265                        | Desktop     | [fb5cbd10fa](https://linux-hardware.org/?probe=fb5cbd10fa) | Jun 11, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [eff8eec9d8](https://linux-hardware.org/?probe=eff8eec9d8) | Jun 11, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [823925da4a](https://linux-hardware.org/?probe=823925da4a) | Jun 11, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [6f58cbafdd](https://linux-hardware.org/?probe=6f58cbafdd) | Jun 10, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [068826c25b](https://linux-hardware.org/?probe=068826c25b) | Jun 10, 2023 |
| Gigabyte      | P35-S3G                     | Desktop     | [71339b40ec](https://linux-hardware.org/?probe=71339b40ec) | Jun 10, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [c74a9048c0](https://linux-hardware.org/?probe=c74a9048c0) | Jun 10, 2023 |
| HP            | 250 G1                      | Notebook    | [1b9c881cae](https://linux-hardware.org/?probe=1b9c881cae) | Jun 10, 2023 |
| HP            | 250 G1                      | Notebook    | [0591407196](https://linux-hardware.org/?probe=0591407196) | Jun 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1388a433de](https://linux-hardware.org/?probe=1388a433de) | Jun 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [d2df298764](https://linux-hardware.org/?probe=d2df298764) | Jun 10, 2023 |
| MSI           | MS-7309                     | Desktop     | [9c6db3b61d](https://linux-hardware.org/?probe=9c6db3b61d) | Jun 10, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [6eada916c0](https://linux-hardware.org/?probe=6eada916c0) | Jun 10, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [dfac11ccad](https://linux-hardware.org/?probe=dfac11ccad) | Jun 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9cb24f9445](https://linux-hardware.org/?probe=9cb24f9445) | Jun 09, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [142fc47b59](https://linux-hardware.org/?probe=142fc47b59) | Jun 09, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [22e9021ae3](https://linux-hardware.org/?probe=22e9021ae3) | Jun 09, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [f8eb3278fe](https://linux-hardware.org/?probe=f8eb3278fe) | Jun 09, 2023 |
| HP            | 18E7                        | Desktop     | [d80810b7f8](https://linux-hardware.org/?probe=d80810b7f8) | Jun 08, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a707a562b8](https://linux-hardware.org/?probe=a707a562b8) | Jun 08, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [6f7077634a](https://linux-hardware.org/?probe=6f7077634a) | Jun 08, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [9de320e96f](https://linux-hardware.org/?probe=9de320e96f) | Jun 08, 2023 |
| Google        | Edgar                       | Notebook    | [bec197cb98](https://linux-hardware.org/?probe=bec197cb98) | Jun 07, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [e563fa3fe2](https://linux-hardware.org/?probe=e563fa3fe2) | Jun 07, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [a9ca37ac88](https://linux-hardware.org/?probe=a9ca37ac88) | Jun 07, 2023 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [328aaf23c9](https://linux-hardware.org/?probe=328aaf23c9) | Jun 07, 2023 |
| Dell          | Latitude E6420              | Notebook    | [011dadb850](https://linux-hardware.org/?probe=011dadb850) | Jun 07, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a1c7c69a05](https://linux-hardware.org/?probe=a1c7c69a05) | Jun 07, 2023 |
| ASUSTek       | NARRA2                      | Desktop     | [e33a2ba9dc](https://linux-hardware.org/?probe=e33a2ba9dc) | Jun 07, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [3c89a2a6a2](https://linux-hardware.org/?probe=3c89a2a6a2) | Jun 07, 2023 |
| ASUSTek       | NARRA2                      | Desktop     | [e05fc7beed](https://linux-hardware.org/?probe=e05fc7beed) | Jun 07, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [26be42ecb8](https://linux-hardware.org/?probe=26be42ecb8) | Jun 07, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | Notebook    | [26f1962805](https://linux-hardware.org/?probe=26f1962805) | Jun 07, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [96a6ae8f4d](https://linux-hardware.org/?probe=96a6ae8f4d) | Jun 07, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8ef73cacf2](https://linux-hardware.org/?probe=8ef73cacf2) | Jun 07, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [6eeacffa3c](https://linux-hardware.org/?probe=6eeacffa3c) | Jun 07, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [6ba5aae544](https://linux-hardware.org/?probe=6ba5aae544) | Jun 07, 2023 |
| HP            | 250 G1                      | Notebook    | [f5c0548f17](https://linux-hardware.org/?probe=f5c0548f17) | Jun 07, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9afe34cdd8](https://linux-hardware.org/?probe=9afe34cdd8) | Jun 06, 2023 |
| ASUSTek       | K73SJ                       | Notebook    | [a77a12f870](https://linux-hardware.org/?probe=a77a12f870) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4c3091f9ff](https://linux-hardware.org/?probe=4c3091f9ff) | Jun 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [bb5f9c1964](https://linux-hardware.org/?probe=bb5f9c1964) | Jun 06, 2023 |
| HP            | 250 G1                      | Notebook    | [f6cab30981](https://linux-hardware.org/?probe=f6cab30981) | Jun 06, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c33a9e5ccb](https://linux-hardware.org/?probe=c33a9e5ccb) | Jun 06, 2023 |
| eMachines     | E725                        | Notebook    | [4e50fbb5a2](https://linux-hardware.org/?probe=4e50fbb5a2) | Jun 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [fa3bffbe76](https://linux-hardware.org/?probe=fa3bffbe76) | Jun 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0b48c563e5](https://linux-hardware.org/?probe=0b48c563e5) | Jun 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6f1c2a6a61](https://linux-hardware.org/?probe=6f1c2a6a61) | Jun 05, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [6f15ff21e4](https://linux-hardware.org/?probe=6f15ff21e4) | Jun 05, 2023 |
| Dell          | Latitude E5520              | Notebook    | [ab87df9910](https://linux-hardware.org/?probe=ab87df9910) | Jun 05, 2023 |
| Dell          | 0VD5HY A07                  | Desktop     | [4e11e5ab66](https://linux-hardware.org/?probe=4e11e5ab66) | Jun 05, 2023 |
| Dell          | 055H3G A01                  | Desktop     | [3fc296df33](https://linux-hardware.org/?probe=3fc296df33) | Jun 05, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e1fabecae3](https://linux-hardware.org/?probe=e1fabecae3) | Jun 04, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [66ed048f40](https://linux-hardware.org/?probe=66ed048f40) | Jun 04, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [0fb6670b07](https://linux-hardware.org/?probe=0fb6670b07) | Jun 03, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c2c0ba92d5](https://linux-hardware.org/?probe=c2c0ba92d5) | Jun 03, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bcf794dd14](https://linux-hardware.org/?probe=bcf794dd14) | Jun 03, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [746c0d0644](https://linux-hardware.org/?probe=746c0d0644) | Jun 03, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [3903b22ffd](https://linux-hardware.org/?probe=3903b22ffd) | Jun 02, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [8dce973d6b](https://linux-hardware.org/?probe=8dce973d6b) | Jun 02, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [c747f45c48](https://linux-hardware.org/?probe=c747f45c48) | Jun 02, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [c0d0a7cb50](https://linux-hardware.org/?probe=c0d0a7cb50) | Jun 01, 2023 |
| MSI           | U200                        | Notebook    | [a217267eb0](https://linux-hardware.org/?probe=a217267eb0) | Jun 01, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [f7e3bde58c](https://linux-hardware.org/?probe=f7e3bde58c) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [871cbcbb88](https://linux-hardware.org/?probe=871cbcbb88) | May 31, 2023 |
| HP            | Notebook                    | Notebook    | [7d7934f727](https://linux-hardware.org/?probe=7d7934f727) | May 31, 2023 |
| HP            | Notebook                    | Notebook    | [161aaf4150](https://linux-hardware.org/?probe=161aaf4150) | May 31, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f0d7ab6b7e](https://linux-hardware.org/?probe=f0d7ab6b7e) | May 31, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [0005e56720](https://linux-hardware.org/?probe=0005e56720) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMS1RM02    | Notebook    | [8f39bcbb17](https://linux-hardware.org/?probe=8f39bcbb17) | May 30, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [ac1e17e897](https://linux-hardware.org/?probe=ac1e17e897) | May 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [03d2cac76c](https://linux-hardware.org/?probe=03d2cac76c) | May 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [54d3fad8f3](https://linux-hardware.org/?probe=54d3fad8f3) | May 29, 2023 |
| HP            | 8265                        | Desktop     | [a554e3bddf](https://linux-hardware.org/?probe=a554e3bddf) | May 29, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [62764248cb](https://linux-hardware.org/?probe=62764248cb) | May 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8e09d71949](https://linux-hardware.org/?probe=8e09d71949) | May 29, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [e681025f33](https://linux-hardware.org/?probe=e681025f33) | May 29, 2023 |
| HP            | 8265                        | Desktop     | [66f0a2d631](https://linux-hardware.org/?probe=66f0a2d631) | May 29, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [68ec8b84a1](https://linux-hardware.org/?probe=68ec8b84a1) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [deaa4b357c](https://linux-hardware.org/?probe=deaa4b357c) | May 29, 2023 |
| ASUSTek       | VivoBook S13 X330FN         | Notebook    | [e94b6fbf06](https://linux-hardware.org/?probe=e94b6fbf06) | May 29, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [8c6f8829e2](https://linux-hardware.org/?probe=8c6f8829e2) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [af312b5e91](https://linux-hardware.org/?probe=af312b5e91) | May 29, 2023 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | Desktop     | [6729d5ffa7](https://linux-hardware.org/?probe=6729d5ffa7) | May 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [035161324d](https://linux-hardware.org/?probe=035161324d) | May 28, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8656657a77](https://linux-hardware.org/?probe=8656657a77) | May 28, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [82fa1dfa46](https://linux-hardware.org/?probe=82fa1dfa46) | May 28, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [c301857917](https://linux-hardware.org/?probe=c301857917) | May 28, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [1718d8d65e](https://linux-hardware.org/?probe=1718d8d65e) | May 28, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [f068d88c01](https://linux-hardware.org/?probe=f068d88c01) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [447ea38d26](https://linux-hardware.org/?probe=447ea38d26) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [57dcd55314](https://linux-hardware.org/?probe=57dcd55314) | May 27, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [3900a03a2c](https://linux-hardware.org/?probe=3900a03a2c) | May 27, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [0aac24410d](https://linux-hardware.org/?probe=0aac24410d) | May 27, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [fef3f47b89](https://linux-hardware.org/?probe=fef3f47b89) | May 27, 2023 |
| HP            | 8265                        | Desktop     | [33488b045e](https://linux-hardware.org/?probe=33488b045e) | May 26, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [d26d09ef64](https://linux-hardware.org/?probe=d26d09ef64) | May 26, 2023 |
| Acer          | TravelMate 6292             | Notebook    | [0a4cb3e4b3](https://linux-hardware.org/?probe=0a4cb3e4b3) | May 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [512abef14b](https://linux-hardware.org/?probe=512abef14b) | May 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d93a5e7c70](https://linux-hardware.org/?probe=d93a5e7c70) | May 25, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [575d3814e9](https://linux-hardware.org/?probe=575d3814e9) | May 25, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [d7d112d2f0](https://linux-hardware.org/?probe=d7d112d2f0) | May 25, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [6f1a19d503](https://linux-hardware.org/?probe=6f1a19d503) | May 25, 2023 |
| Toshiba       | Satellite M50D-A            | Notebook    | [9f7a16aa7b](https://linux-hardware.org/?probe=9f7a16aa7b) | May 25, 2023 |
| Toshiba       | Satellite M50D-A            | Notebook    | [bbb23b2823](https://linux-hardware.org/?probe=bbb23b2823) | May 25, 2023 |
| HP            | Pavilion 17                 | Notebook    | [792ac6919d](https://linux-hardware.org/?probe=792ac6919d) | May 24, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [920a4901d9](https://linux-hardware.org/?probe=920a4901d9) | May 24, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [43069955ee](https://linux-hardware.org/?probe=43069955ee) | May 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [da302bee4e](https://linux-hardware.org/?probe=da302bee4e) | May 23, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [431f2db1fc](https://linux-hardware.org/?probe=431f2db1fc) | May 23, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5fff4f66c1](https://linux-hardware.org/?probe=5fff4f66c1) | May 22, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [5798ed934b](https://linux-hardware.org/?probe=5798ed934b) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [44b6477648](https://linux-hardware.org/?probe=44b6477648) | May 22, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [9320baf9c8](https://linux-hardware.org/?probe=9320baf9c8) | May 22, 2023 |
| Medion        | MS-7748                     | Desktop     | [84765690f5](https://linux-hardware.org/?probe=84765690f5) | May 22, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [88ffb8b020](https://linux-hardware.org/?probe=88ffb8b020) | May 22, 2023 |
| eMachines     | E725                        | Notebook    | [c75d7eb314](https://linux-hardware.org/?probe=c75d7eb314) | May 22, 2023 |
| eMachines     | E725                        | Notebook    | [f32fb866fa](https://linux-hardware.org/?probe=f32fb866fa) | May 22, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [5f83edfb1e](https://linux-hardware.org/?probe=5f83edfb1e) | May 22, 2023 |
| HP            | 8265                        | Desktop     | [5ce02f4648](https://linux-hardware.org/?probe=5ce02f4648) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [0ab3a9817b](https://linux-hardware.org/?probe=0ab3a9817b) | May 21, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [c0330d366f](https://linux-hardware.org/?probe=c0330d366f) | May 21, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [2ab72e28d7](https://linux-hardware.org/?probe=2ab72e28d7) | May 21, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [6e859c48e1](https://linux-hardware.org/?probe=6e859c48e1) | May 21, 2023 |
| Medion        | MS-7748                     | Desktop     | [dc5431a93b](https://linux-hardware.org/?probe=dc5431a93b) | May 21, 2023 |
| MSI           | MS-7309                     | Desktop     | [0b5d330939](https://linux-hardware.org/?probe=0b5d330939) | May 21, 2023 |
| Medion        | MS-7748                     | Desktop     | [d2fa9ef11a](https://linux-hardware.org/?probe=d2fa9ef11a) | May 21, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [313fb9c88a](https://linux-hardware.org/?probe=313fb9c88a) | May 21, 2023 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [de2fc32d08](https://linux-hardware.org/?probe=de2fc32d08) | May 21, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [74122892bc](https://linux-hardware.org/?probe=74122892bc) | May 21, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [4e4024bced](https://linux-hardware.org/?probe=4e4024bced) | May 21, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [958b40f42c](https://linux-hardware.org/?probe=958b40f42c) | May 21, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [5043ac245f](https://linux-hardware.org/?probe=5043ac245f) | May 21, 2023 |
| Sony          | VGN-FW21Z                   | Notebook    | [aac218a1e0](https://linux-hardware.org/?probe=aac218a1e0) | May 20, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [562bec5076](https://linux-hardware.org/?probe=562bec5076) | May 20, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7db14b0f6f](https://linux-hardware.org/?probe=7db14b0f6f) | May 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | Notebook    | [2e78e77fef](https://linux-hardware.org/?probe=2e78e77fef) | May 19, 2023 |
| eMachines     | E725                        | Notebook    | [517ba05822](https://linux-hardware.org/?probe=517ba05822) | May 19, 2023 |
| HP            | 250 G2                      | Notebook    | [e3b94752ac](https://linux-hardware.org/?probe=e3b94752ac) | May 19, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [1d729ae4ea](https://linux-hardware.org/?probe=1d729ae4ea) | May 19, 2023 |
| Dell          | Latitude D630               | Notebook    | [9526ff1765](https://linux-hardware.org/?probe=9526ff1765) | May 19, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [c791e54f97](https://linux-hardware.org/?probe=c791e54f97) | May 19, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [edbc15eb75](https://linux-hardware.org/?probe=edbc15eb75) | May 18, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4587e40310](https://linux-hardware.org/?probe=4587e40310) | May 18, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [411344a862](https://linux-hardware.org/?probe=411344a862) | May 18, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [75c2a22eb5](https://linux-hardware.org/?probe=75c2a22eb5) | May 18, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [868d98e4f4](https://linux-hardware.org/?probe=868d98e4f4) | May 18, 2023 |
| HP            | 625                         | Notebook    | [8e34027a91](https://linux-hardware.org/?probe=8e34027a91) | May 18, 2023 |
| Dell          | Latitude D630               | Notebook    | [7a7497a4b3](https://linux-hardware.org/?probe=7a7497a4b3) | May 18, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [b3b39b07a5](https://linux-hardware.org/?probe=b3b39b07a5) | May 18, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [400b91098c](https://linux-hardware.org/?probe=400b91098c) | May 18, 2023 |
| Alcor Digi... | Snugbook N1431              | Notebook    | [a04e4c387e](https://linux-hardware.org/?probe=a04e4c387e) | May 17, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [ad477b9698](https://linux-hardware.org/?probe=ad477b9698) | May 17, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5d77e9825a](https://linux-hardware.org/?probe=5d77e9825a) | May 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [0323142e79](https://linux-hardware.org/?probe=0323142e79) | May 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [d734e52f59](https://linux-hardware.org/?probe=d734e52f59) | May 17, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [a65ace49b0](https://linux-hardware.org/?probe=a65ace49b0) | May 17, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [a7f0d5509c](https://linux-hardware.org/?probe=a7f0d5509c) | May 17, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [30c42f6f19](https://linux-hardware.org/?probe=30c42f6f19) | May 17, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [6856deb5d7](https://linux-hardware.org/?probe=6856deb5d7) | May 16, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [6b606c0c57](https://linux-hardware.org/?probe=6b606c0c57) | May 16, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [f9672e78a2](https://linux-hardware.org/?probe=f9672e78a2) | May 16, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [3699048599](https://linux-hardware.org/?probe=3699048599) | May 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e228d9926b](https://linux-hardware.org/?probe=e228d9926b) | May 16, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [e01dbddbd0](https://linux-hardware.org/?probe=e01dbddbd0) | May 16, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [72db5ccefc](https://linux-hardware.org/?probe=72db5ccefc) | May 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f977ce9be3](https://linux-hardware.org/?probe=f977ce9be3) | May 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [f286932235](https://linux-hardware.org/?probe=f286932235) | May 15, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [d3bc261952](https://linux-hardware.org/?probe=d3bc261952) | May 15, 2023 |
| Dell          | Latitude 5490               | Notebook    | [0a6ee8c111](https://linux-hardware.org/?probe=0a6ee8c111) | May 14, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8661cb20d2](https://linux-hardware.org/?probe=8661cb20d2) | May 14, 2023 |
| eMachines     | E725                        | Notebook    | [32c12bfb05](https://linux-hardware.org/?probe=32c12bfb05) | May 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ba63571489](https://linux-hardware.org/?probe=ba63571489) | May 14, 2023 |
| Acer          | Aspire A717-72G             | Notebook    | [1ab0673015](https://linux-hardware.org/?probe=1ab0673015) | May 14, 2023 |
| Acer          | Aspire A717-72G             | Notebook    | [62a46acc18](https://linux-hardware.org/?probe=62a46acc18) | May 14, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [d72abd1f09](https://linux-hardware.org/?probe=d72abd1f09) | May 14, 2023 |
| ASUSTek       | M2A-MX                      | Desktop     | [43c0de16a2](https://linux-hardware.org/?probe=43c0de16a2) | May 14, 2023 |
| eMachines     | E725                        | Notebook    | [8768af826f](https://linux-hardware.org/?probe=8768af826f) | May 14, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [f6cf41154f](https://linux-hardware.org/?probe=f6cf41154f) | May 14, 2023 |
| eMachines     | E725                        | Notebook    | [fed9273467](https://linux-hardware.org/?probe=fed9273467) | May 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [ae4ee3c43d](https://linux-hardware.org/?probe=ae4ee3c43d) | May 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [0ae54cb7c4](https://linux-hardware.org/?probe=0ae54cb7c4) | May 13, 2023 |
| Dell          | Latitude 5480               | Notebook    | [63cd615fa8](https://linux-hardware.org/?probe=63cd615fa8) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [e172257a22](https://linux-hardware.org/?probe=e172257a22) | May 13, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [60ac4f3964](https://linux-hardware.org/?probe=60ac4f3964) | May 13, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [1e8aca1c49](https://linux-hardware.org/?probe=1e8aca1c49) | May 13, 2023 |
| HP            | Notebook                    | Notebook    | [9840f334f5](https://linux-hardware.org/?probe=9840f334f5) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [d0f5ee2781](https://linux-hardware.org/?probe=d0f5ee2781) | May 13, 2023 |
| HP            | Notebook                    | Notebook    | [db9aaf4ce9](https://linux-hardware.org/?probe=db9aaf4ce9) | May 13, 2023 |
| ASRock        | B365M Pro4                  | Desktop     | [264720475a](https://linux-hardware.org/?probe=264720475a) | May 13, 2023 |
| eMachines     | E725                        | Notebook    | [52848aa6bd](https://linux-hardware.org/?probe=52848aa6bd) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1NV         | Notebook    | [d06987bfd6](https://linux-hardware.org/?probe=d06987bfd6) | May 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [a7e9891909](https://linux-hardware.org/?probe=a7e9891909) | May 12, 2023 |
| HP            | 8055                        | Desktop     | [7f692f60e6](https://linux-hardware.org/?probe=7f692f60e6) | May 12, 2023 |
| HP            | Notebook                    | Notebook    | [bc25329bce](https://linux-hardware.org/?probe=bc25329bce) | May 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [9efa5d994b](https://linux-hardware.org/?probe=9efa5d994b) | May 12, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [024b4d4f97](https://linux-hardware.org/?probe=024b4d4f97) | May 12, 2023 |
| Medion        | MS-7748                     | Desktop     | [c5b24a357f](https://linux-hardware.org/?probe=c5b24a357f) | May 12, 2023 |
| HP            | Notebook                    | Notebook    | [d527d781af](https://linux-hardware.org/?probe=d527d781af) | May 11, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [e69c9bb60f](https://linux-hardware.org/?probe=e69c9bb60f) | May 11, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [17cf022069](https://linux-hardware.org/?probe=17cf022069) | May 11, 2023 |
| eMachines     | E725                        | Notebook    | [94e51437e6](https://linux-hardware.org/?probe=94e51437e6) | May 11, 2023 |
| MSI           | A75MA-P35                   | Desktop     | [18b29879dd](https://linux-hardware.org/?probe=18b29879dd) | May 11, 2023 |
| MSI           | A75MA-P35                   | Desktop     | [abcfdbcbfc](https://linux-hardware.org/?probe=abcfdbcbfc) | May 11, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [0c8d19bdf0](https://linux-hardware.org/?probe=0c8d19bdf0) | May 10, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [dbc75c5600](https://linux-hardware.org/?probe=dbc75c5600) | May 10, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [396be908b5](https://linux-hardware.org/?probe=396be908b5) | May 10, 2023 |
| Dell          | Latitude E6440              | Notebook    | [ea902a82a4](https://linux-hardware.org/?probe=ea902a82a4) | May 10, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [56d9faa756](https://linux-hardware.org/?probe=56d9faa756) | May 10, 2023 |
| HP            | 250 G1                      | Notebook    | [09879bd463](https://linux-hardware.org/?probe=09879bd463) | May 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [bd3934d526](https://linux-hardware.org/?probe=bd3934d526) | May 10, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [543cce00c7](https://linux-hardware.org/?probe=543cce00c7) | May 09, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [7a97cdf93b](https://linux-hardware.org/?probe=7a97cdf93b) | May 09, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [78b60f4ad9](https://linux-hardware.org/?probe=78b60f4ad9) | May 09, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [6c55bc2118](https://linux-hardware.org/?probe=6c55bc2118) | May 09, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [3d378ca82d](https://linux-hardware.org/?probe=3d378ca82d) | May 09, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [4d3e8cb0e9](https://linux-hardware.org/?probe=4d3e8cb0e9) | May 09, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [fc9004551b](https://linux-hardware.org/?probe=fc9004551b) | May 09, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [f900658289](https://linux-hardware.org/?probe=f900658289) | May 09, 2023 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [90bec72fa7](https://linux-hardware.org/?probe=90bec72fa7) | May 09, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [65b039a3f5](https://linux-hardware.org/?probe=65b039a3f5) | May 08, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [e5c5cd0fcf](https://linux-hardware.org/?probe=e5c5cd0fcf) | May 08, 2023 |
| Acer          | V5-131                      | Notebook    | [d68eaead66](https://linux-hardware.org/?probe=d68eaead66) | May 08, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [bd15eaa1e6](https://linux-hardware.org/?probe=bd15eaa1e6) | May 08, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [1d06735e36](https://linux-hardware.org/?probe=1d06735e36) | May 08, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8bbe8f0a3f](https://linux-hardware.org/?probe=8bbe8f0a3f) | May 08, 2023 |
| Dell          | 0VD5HY A07                  | Desktop     | [d17791f116](https://linux-hardware.org/?probe=d17791f116) | May 08, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [ad9af07a7c](https://linux-hardware.org/?probe=ad9af07a7c) | May 08, 2023 |
| eMachines     | E725                        | Notebook    | [bb9c7992f8](https://linux-hardware.org/?probe=bb9c7992f8) | May 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [76748da9cd](https://linux-hardware.org/?probe=76748da9cd) | May 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7a1ffd8bd2](https://linux-hardware.org/?probe=7a1ffd8bd2) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [3b40b9b869](https://linux-hardware.org/?probe=3b40b9b869) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [b0200f5262](https://linux-hardware.org/?probe=b0200f5262) | May 07, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [1f677501c0](https://linux-hardware.org/?probe=1f677501c0) | May 07, 2023 |
| HP            | 650                         | Notebook    | [3ece9ca18a](https://linux-hardware.org/?probe=3ece9ca18a) | May 07, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [8c80fd3109](https://linux-hardware.org/?probe=8c80fd3109) | May 07, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [fd7a2486f2](https://linux-hardware.org/?probe=fd7a2486f2) | May 07, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b76e0e7397](https://linux-hardware.org/?probe=b76e0e7397) | May 06, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [5cad7b7e28](https://linux-hardware.org/?probe=5cad7b7e28) | May 06, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [58de65fdbd](https://linux-hardware.org/?probe=58de65fdbd) | May 06, 2023 |
| HP            | 3033h                       | Desktop     | [a322bec919](https://linux-hardware.org/?probe=a322bec919) | May 06, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [e9a4f752c5](https://linux-hardware.org/?probe=e9a4f752c5) | May 06, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [2bd846964e](https://linux-hardware.org/?probe=2bd846964e) | May 06, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [1495984c3f](https://linux-hardware.org/?probe=1495984c3f) | May 06, 2023 |
| ASUSTek       | K53BY                       | Notebook    | [6a9ae368ba](https://linux-hardware.org/?probe=6a9ae368ba) | May 06, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [78bb45767d](https://linux-hardware.org/?probe=78bb45767d) | May 06, 2023 |
| eMachines     | E725                        | Notebook    | [15807b1086](https://linux-hardware.org/?probe=15807b1086) | May 06, 2023 |
| eMachines     | E725                        | Notebook    | [290d356d4c](https://linux-hardware.org/?probe=290d356d4c) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [e409298467](https://linux-hardware.org/?probe=e409298467) | May 05, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [9640ef7fa5](https://linux-hardware.org/?probe=9640ef7fa5) | May 05, 2023 |
| HP            | 339A                        | Desktop     | [920b722009](https://linux-hardware.org/?probe=920b722009) | May 05, 2023 |
| Lenovo        | ThinkPad T500 2056CL8       | Notebook    | [df56d361ef](https://linux-hardware.org/?probe=df56d361ef) | May 05, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [0e338f138d](https://linux-hardware.org/?probe=0e338f138d) | May 04, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [4114d6e81c](https://linux-hardware.org/?probe=4114d6e81c) | May 04, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [b322652461](https://linux-hardware.org/?probe=b322652461) | May 04, 2023 |
| Dell          | Latitude 5490               | Notebook    | [c2d5f80f6e](https://linux-hardware.org/?probe=c2d5f80f6e) | May 04, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [3678c25be6](https://linux-hardware.org/?probe=3678c25be6) | May 04, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [61d04b0e4c](https://linux-hardware.org/?probe=61d04b0e4c) | May 04, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [6014477aa0](https://linux-hardware.org/?probe=6014477aa0) | May 04, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [aaad7b3a55](https://linux-hardware.org/?probe=aaad7b3a55) | May 04, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [ba51ad63e8](https://linux-hardware.org/?probe=ba51ad63e8) | May 04, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | Notebook    | [45035a5981](https://linux-hardware.org/?probe=45035a5981) | May 04, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [77cbfa62cd](https://linux-hardware.org/?probe=77cbfa62cd) | May 04, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [b7b6981f65](https://linux-hardware.org/?probe=b7b6981f65) | May 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | Notebook    | [438c1a31ea](https://linux-hardware.org/?probe=438c1a31ea) | May 04, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [182df1bb15](https://linux-hardware.org/?probe=182df1bb15) | May 04, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [6e2629de4d](https://linux-hardware.org/?probe=6e2629de4d) | May 03, 2023 |
| Lenovo        | E50-80 80J2                 | Notebook    | [c82dd5d579](https://linux-hardware.org/?probe=c82dd5d579) | May 03, 2023 |
| Lenovo        | ThinkStation C30 1097A34    | Desktop     | [0eb86a808a](https://linux-hardware.org/?probe=0eb86a808a) | May 03, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [117d914e84](https://linux-hardware.org/?probe=117d914e84) | May 03, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [3aed695405](https://linux-hardware.org/?probe=3aed695405) | May 03, 2023 |
| Dell          | Latitude E5520              | Notebook    | [0861e85947](https://linux-hardware.org/?probe=0861e85947) | May 03, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [8fab6deff5](https://linux-hardware.org/?probe=8fab6deff5) | May 03, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [7e731cb85c](https://linux-hardware.org/?probe=7e731cb85c) | May 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [43e6345cb8](https://linux-hardware.org/?probe=43e6345cb8) | May 03, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [c8a19f5567](https://linux-hardware.org/?probe=c8a19f5567) | May 02, 2023 |
| MSI           | MS-7817                     | Desktop     | [71aac2d171](https://linux-hardware.org/?probe=71aac2d171) | May 02, 2023 |
| MSI           | MS-7817                     | Desktop     | [b9689d9c27](https://linux-hardware.org/?probe=b9689d9c27) | May 02, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [bdb1e8c4a7](https://linux-hardware.org/?probe=bdb1e8c4a7) | May 02, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [735d6f53e9](https://linux-hardware.org/?probe=735d6f53e9) | May 02, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [2280876e20](https://linux-hardware.org/?probe=2280876e20) | May 02, 2023 |
| HP            | 8265                        | Desktop     | [b2c0b909f0](https://linux-hardware.org/?probe=b2c0b909f0) | May 02, 2023 |
| HP            | 8265                        | Desktop     | [05641bda97](https://linux-hardware.org/?probe=05641bda97) | May 02, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [9fcb4f708c](https://linux-hardware.org/?probe=9fcb4f708c) | May 02, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [31e13940be](https://linux-hardware.org/?probe=31e13940be) | May 01, 2023 |
| HP            | 8265                        | Desktop     | [5fca5b8edd](https://linux-hardware.org/?probe=5fca5b8edd) | May 01, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [cc784397f9](https://linux-hardware.org/?probe=cc784397f9) | May 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [07ef050535](https://linux-hardware.org/?probe=07ef050535) | May 01, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [96a8ba3062](https://linux-hardware.org/?probe=96a8ba3062) | May 01, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [856577ad04](https://linux-hardware.org/?probe=856577ad04) | May 01, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [f84a692777](https://linux-hardware.org/?probe=f84a692777) | Apr 30, 2023 |
| eMachines     | E725                        | Notebook    | [282c0c9f11](https://linux-hardware.org/?probe=282c0c9f11) | Apr 30, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [8bf9a1841e](https://linux-hardware.org/?probe=8bf9a1841e) | Apr 30, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [7afb6268da](https://linux-hardware.org/?probe=7afb6268da) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| eMachines     | E725                        | Notebook    | [25da91560d](https://linux-hardware.org/?probe=25da91560d) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [25c6042b4e](https://linux-hardware.org/?probe=25c6042b4e) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [230f3dd04b](https://linux-hardware.org/?probe=230f3dd04b) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [9d5cd21a8f](https://linux-hardware.org/?probe=9d5cd21a8f) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [9bb7a9b712](https://linux-hardware.org/?probe=9bb7a9b712) | Apr 30, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [292f489feb](https://linux-hardware.org/?probe=292f489feb) | Apr 29, 2023 |
| HP            | 8265                        | Desktop     | [5cdb9f6a93](https://linux-hardware.org/?probe=5cdb9f6a93) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [b2616ea409](https://linux-hardware.org/?probe=b2616ea409) | Apr 28, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [ada78ae33d](https://linux-hardware.org/?probe=ada78ae33d) | Apr 28, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [9c2dd52f1e](https://linux-hardware.org/?probe=9c2dd52f1e) | Apr 28, 2023 |
| HP            | 8265                        | Desktop     | [71a48b0229](https://linux-hardware.org/?probe=71a48b0229) | Apr 27, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [e9237f0d53](https://linux-hardware.org/?probe=e9237f0d53) | Apr 27, 2023 |
| eMachines     | E725                        | Notebook    | [668de483ca](https://linux-hardware.org/?probe=668de483ca) | Apr 27, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [13d7dc019c](https://linux-hardware.org/?probe=13d7dc019c) | Apr 26, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [9dd9301581](https://linux-hardware.org/?probe=9dd9301581) | Apr 26, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [e46f340908](https://linux-hardware.org/?probe=e46f340908) | Apr 25, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| Dell          | 0KYJ8C A00                  | Desktop     | [1e8226d149](https://linux-hardware.org/?probe=1e8226d149) | Apr 25, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [dd27aa0575](https://linux-hardware.org/?probe=dd27aa0575) | Apr 25, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [e0eef23b19](https://linux-hardware.org/?probe=e0eef23b19) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7d5bd7e8fa](https://linux-hardware.org/?probe=7d5bd7e8fa) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [24bf298df5](https://linux-hardware.org/?probe=24bf298df5) | Apr 25, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hungary/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| BlackPanther 18.1            | 2034      | 48.27%  |
| Ubuntu 20.04                 | 272       | 6.45%   |
| BlackPanther 16.2            | 223       | 5.29%   |
| Ubuntu 18.04                 | 156       | 3.7%    |
| Ubuntu 22.04                 | 109       | 2.59%   |
| OpenMandriva 4.2             | 59        | 1.4%    |
| Debian 11                    | 50        | 1.19%   |
| OpenMandriva 4.3             | 39        | 0.93%   |
| Arch Rolling                 | 33        | 0.78%   |
| Zorin 16                     | 32        | 0.76%   |
| Linux Mint 20.2              | 32        | 0.76%   |
| Linux Mint 21.1              | 28        | 0.66%   |
| Arch                         | 25        | 0.59%   |
| Linux Mint 19.3              | 24        | 0.57%   |
| Fedora 38                    | 24        | 0.57%   |
| Ubuntu 19.10                 | 23        | 0.55%   |
| BlackPanther 22.1            | 23        | 0.55%   |
| ArcoLinux Rolling            | 23        | 0.55%   |
| OpenMandriva 23.03           | 21        | 0.5%    |
| Linux Mint 20.3              | 21        | 0.5%    |
| Linux Mint 20                | 21        | 0.5%    |
| Debian 10                    | 21        | 0.5%    |
| Kubuntu 20.04                | 20        | 0.47%   |
| Fedora 36                    | 20        | 0.47%   |
| Xubuntu 20.04                | 19        | 0.45%   |
| Ubuntu 21.10                 | 19        | 0.45%   |
| Ubuntu 19.04                 | 19        | 0.45%   |
| KDE neon 20.04               | 19        | 0.45%   |
| Ubuntu 21.04                 | 18        | 0.43%   |
| Pop!_OS 22.04                | 18        | 0.43%   |
| Manjaro                      | 18        | 0.43%   |
| Xubuntu 18.04                | 17        | 0.4%    |
| openSUSE Tumbleweed-XXXXXXXX | 16        | 0.38%   |
| Fedora 37                    | 16        | 0.38%   |
| OpenMandriva 4.50            | 15        | 0.36%   |
| Linux Mint 20.1              | 15        | 0.36%   |
| Fedora 35                    | 15        | 0.36%   |
| OpenMandriva 23.01           | 14        | 0.33%   |
| Fedora 33                    | 14        | 0.33%   |
| Ubuntu 23.04                 | 13        | 0.31%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| BlackPanther  | 2232      | 55.45%  |
| Ubuntu        | 632       | 15.7%   |
| OpenMandriva  | 166       | 4.12%   |
| Linux Mint    | 158       | 3.93%   |
| Fedora        | 100       | 2.48%   |
| Debian        | 96        | 2.39%   |
| Endless       | 85        | 2.11%   |
| Arch          | 57        | 1.42%   |
| Manjaro       | 56        | 1.39%   |
| Kubuntu       | 50        | 1.24%   |
| Xubuntu       | 45        | 1.12%   |
| Zorin         | 44        | 1.09%   |
| Pop!_OS       | 41        | 1.02%   |
| ArcoLinux     | 27        | 0.67%   |
| KDE neon      | 26        | 0.65%   |
| openSUSE      | 23        | 0.57%   |
| ROSA          | 22        | 0.55%   |
| Ubuntu MATE   | 19        | 0.47%   |
| Lubuntu       | 18        | 0.45%   |
| Ubuntu Unity  | 15        | 0.37%   |
| Elementary    | 11        | 0.27%   |
| Kali          | 10        | 0.25%   |
| Gentoo        | 9         | 0.22%   |
| EndeavourOS   | 8         | 0.2%    |
| Ubuntu Budgie | 6         | 0.15%   |
| SteamOS       | 5         | 0.12%   |
| Raspbian      | 5         | 0.12%   |
| Xero          | 4         | 0.1%    |
| Nobara        | 4         | 0.1%    |
| MX            | 4         | 0.1%    |
| LMDE          | 4         | 0.1%    |
| Clear Linux   | 4         | 0.1%    |
| Rocky Linux   | 3         | 0.07%   |
| Q4OS          | 3         | 0.07%   |
| AlmaLinux     | 3         | 0.07%   |
| UbuntuDDE     | 2         | 0.05%   |
| NixOS         | 2         | 0.05%   |
| Garuda Linux  | 2         | 0.05%   |
| Devuan        | 2         | 0.05%   |
| CentOS        | 2         | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.18.16-desktop-1bP      | 1503      | 32.13%  |
| 5.6.14-desktop-2bP       | 658       | 14.07%  |
| 4.9.20-desktop-pae-1bP   | 206       | 4.4%    |
| 5.1.15-desktop-1bP       | 85        | 1.82%   |
| 5.10.14-desktop-1omv4002 | 55        | 1.18%   |
| 5.15.85-desktop-1bP      | 46        | 0.98%   |
| 5.4.0-42-generic         | 42        | 0.9%    |
| 5.16.7-desktop-1omv4003  | 37        | 0.79%   |
| 5.4.0-58-generic         | 27        | 0.58%   |
| 5.8.0-14-generic         | 25        | 0.53%   |
| 5.4.0-52-generic         | 21        | 0.45%   |
| 6.2.6-desktop-1omv2390   | 20        | 0.43%   |
| 5.4.0-48-generic         | 19        | 0.41%   |
| 5.11.0-27-generic        | 19        | 0.41%   |
| 5.3.0-28-generic         | 15        | 0.32%   |
| 5.15.0-58-generic        | 15        | 0.32%   |
| 5.15.0-56-generic        | 15        | 0.32%   |
| 6.1.1-desktop-1omv2290   | 14        | 0.3%    |
| 5.15.0-52-generic        | 14        | 0.3%    |
| 5.15.0-43-generic        | 14        | 0.3%    |
| 4.18.0-15-generic        | 14        | 0.3%    |
| 5.4.0-54-generic         | 13        | 0.28%   |
| 5.4.0-40-generic         | 13        | 0.28%   |
| 5.4.0-19-generic         | 13        | 0.28%   |
| 5.11.0-34-generic        | 13        | 0.28%   |
| 5.4.0-29-generic         | 12        | 0.26%   |
| 4.15.0-43-generic        | 12        | 0.26%   |
| 5.4.0-91-generic         | 11        | 0.24%   |
| 5.4.0-26-generic         | 11        | 0.24%   |
| 5.15.0-46-generic        | 11        | 0.24%   |
| 5.15.0-41-generic        | 11        | 0.24%   |
| 5.11.0-43-generic        | 11        | 0.24%   |
| 6.3.3-desktop-1bP        | 10        | 0.21%   |
| 5.8.0-43-generic         | 10        | 0.21%   |
| 5.3.0-46-generic         | 10        | 0.21%   |
| 5.15.0-47-generic        | 10        | 0.21%   |
| 5.13.0-27-generic        | 10        | 0.21%   |
| 5.0.0-37-generic         | 10        | 0.21%   |
| 6.4.11-desktop-1omv2390  | 9         | 0.19%   |
| 6.3.8-desktop-1bP        | 9         | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.16 | 1503      | 33.08%  |
| 5.6.14  | 660       | 14.52%  |
| 5.4.0   | 341       | 7.5%    |
| 4.9.20  | 217       | 4.78%   |
| 5.15.0  | 176       | 3.87%   |
| 4.15.0  | 117       | 2.57%   |
| 5.11.0  | 104       | 2.29%   |
| 5.8.0   | 103       | 2.27%   |
| 5.1.15  | 86        | 1.89%   |
| 5.3.0   | 82        | 1.8%    |
| 5.13.0  | 81        | 1.78%   |
| 5.10.0  | 61        | 1.34%   |
| 5.0.0   | 56        | 1.23%   |
| 5.10.14 | 55        | 1.21%   |
| 5.19.0  | 48        | 1.06%   |
| 5.15.85 | 47        | 1.03%   |
| 4.18.0  | 40        | 0.88%   |
| 5.16.7  | 38        | 0.84%   |
| 6.2.0   | 30        | 0.66%   |
| 6.2.6   | 26        | 0.57%   |
| 4.19.0  | 22        | 0.48%   |
| 6.1.1   | 18        | 0.4%    |
| 6.1.0   | 16        | 0.35%   |
| 5.14.0  | 12        | 0.26%   |
| 6.4.11  | 11        | 0.24%   |
| 6.3.8   | 11        | 0.24%   |
| 6.3.3   | 10        | 0.22%   |
| 6.2.9   | 10        | 0.22%   |
| 6.4.3   | 9         | 0.2%    |
| 6.0.12  | 9         | 0.2%    |
| 5.16.0  | 9         | 0.2%    |
| 5.12.4  | 9         | 0.2%    |
| 4.13.0  | 9         | 0.2%    |
| 5.18.12 | 8         | 0.18%   |
| 4.4.0   | 8         | 0.18%   |
| 5.13.13 | 7         | 0.15%   |
| 6.2.14  | 6         | 0.13%   |
| 5.9.16  | 6         | 0.13%   |
| 5.9.0   | 6         | 0.13%   |
| 6.2.15  | 5         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 1542      | 34.16%  |
| 5.6     | 675       | 14.95%  |
| 5.4     | 364       | 8.06%   |
| 5.15    | 262       | 5.8%    |
| 4.9     | 230       | 5.1%    |
| 5.10    | 143       | 3.17%   |
| 5.11    | 124       | 2.75%   |
| 5.8     | 119       | 2.64%   |
| 4.15    | 117       | 2.59%   |
| 5.13    | 93        | 2.06%   |
| 6.2     | 90        | 1.99%   |
| 5.1     | 89        | 1.97%   |
| 5.3     | 88        | 1.95%   |
| 5.19    | 71        | 1.57%   |
| 5.16    | 66        | 1.46%   |
| 6.1     | 62        | 1.37%   |
| 5.0     | 56        | 1.24%   |
| 6.4     | 41        | 0.91%   |
| 6.3     | 36        | 0.8%    |
| 6.0     | 30        | 0.66%   |
| 5.18    | 29        | 0.64%   |
| 5.14    | 28        | 0.62%   |
| 5.9     | 25        | 0.55%   |
| 4.19    | 24        | 0.53%   |
| 5.12    | 23        | 0.51%   |
| 5.17    | 17        | 0.38%   |
| 5.7     | 16        | 0.35%   |
| 4.13    | 9         | 0.2%    |
| 4.4     | 8         | 0.18%   |
| 6.5     | 7         | 0.16%   |
| 5.5     | 7         | 0.16%   |
| 4.7     | 5         | 0.11%   |
| 4.16    | 4         | 0.09%   |
| 4.5     | 2         | 0.04%   |
| 4.20    | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 4.1     | 2         | 0.04%   |
| 6       | 1         | 0.02%   |
| 5.2     | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3635      | 92.56%  |
| i686    | 281       | 7.16%   |
| armv7l  | 4         | 0.1%    |
| aarch64 | 4         | 0.1%    |
| armv6l  | 2         | 0.05%   |
| unknow  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 2487      | 61.93%  |
| GNOME           | 756       | 18.82%  |
| Unknown         | 270       | 6.72%   |
| XFCE            | 136       | 3.39%   |
| X-Cinnamon      | 121       | 3.01%   |
| MATE            | 67        | 1.67%   |
| KDE             | 39        | 0.97%   |
| Cinnamon        | 30        | 0.75%   |
| LXQt            | 29        | 0.72%   |
| Unity           | 15        | 0.37%   |
| KDE4            | 14        | 0.35%   |
| Pantheon        | 10        | 0.25%   |
| i3              | 8         | 0.2%    |
| Deepin          | 7         | 0.17%   |
| Budgie          | 7         | 0.17%   |
| LXDE            | 6         | 0.15%   |
| GNOME Flashback | 5         | 0.12%   |
| GNOME Classic   | 2         | 0.05%   |
| Trinity         | 1         | 0.02%   |
| qtile           | 1         | 0.02%   |
| ICEWM           | 1         | 0.02%   |
| Hyprland        | 1         | 0.02%   |
| Enlightenment   | 1         | 0.02%   |
| bspwm           | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3495      | 88.35%  |
| Wayland | 279       | 7.05%   |
| Unknown | 146       | 3.69%   |
| Tty     | 34        | 0.86%   |
| Web     | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2493      | 62.25%  |
| Unknown | 848       | 21.17%  |
| GDM3    | 206       | 5.14%   |
| GDM     | 189       | 4.72%   |
| LightDM | 183       | 4.57%   |
| TDM     | 64        | 1.6%    |
| KDM     | 14        | 0.35%   |
| SLiM    | 5         | 0.12%   |
| XDM     | 3         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2404      | 60.22%  |
| hu_HU      | 939       | 23.52%  |
| en_US      | 518       | 12.98%  |
| en_GB      | 55        | 1.38%   |
| C          | 31        | 0.78%   |
| de_DE      | 18        | 0.45%   |
| ru_UA      | 3         | 0.08%   |
| ru_RU      | 3         | 0.08%   |
| POSIX      | 3         | 0.08%   |
| en_AU      | 3         | 0.08%   |
| nl_NL      | 2         | 0.05%   |
| hu_HU.UTF8 | 2         | 0.05%   |
| C.UTF8     | 2         | 0.05%   |
| it_IT      | 1         | 0.03%   |
| fr_FR      | 1         | 0.03%   |
| fr_BE      | 1         | 0.03%   |
| en_ZA      | 1         | 0.03%   |
| en_IN      | 1         | 0.03%   |
| en_IL      | 1         | 0.03%   |
| en_AG      | 1         | 0.03%   |
| el_GR      | 1         | 0.03%   |
| de_AT      | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2521      | 62.11%  |
| EFI  | 1538      | 37.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2286      | 53.52%  |
| Overlay | 1689      | 39.55%  |
| Btrfs   | 136       | 3.18%   |
| Unknown | 80        | 1.87%   |
| Tmpfs   | 33        | 0.77%   |
| Xfs     | 18        | 0.42%   |
| Zfs     | 10        | 0.23%   |
| Ext2    | 9         | 0.21%   |
| Ext3    | 7         | 0.16%   |
| F2fs    | 2         | 0.05%   |
| XXXXXXX | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 1792      | 43.73%  |
| GPT     | 1397      | 34.09%  |
| Unknown | 909       | 22.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3112      | 73.95%  |
| Yes       | 1096      | 26.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2267      | 54.72%  |
| Yes       | 1876      | 45.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 652       | 16.78%  |
| Hewlett-Packard         | 591       | 15.21%  |
| Dell                    | 547       | 14.08%  |
| Lenovo                  | 542       | 13.95%  |
| Gigabyte Technology     | 326       | 8.39%   |
| Acer                    | 263       | 6.77%   |
| ASRock                  | 261       | 6.72%   |
| MSI                     | 124       | 3.19%   |
| Fujitsu                 | 86        | 2.21%   |
| Fujitsu Siemens         | 65        | 1.67%   |
| Toshiba                 | 58        | 1.49%   |
| Samsung Electronics     | 38        | 0.98%   |
| Intel                   | 32        | 0.82%   |
| Packard Bell            | 30        | 0.77%   |
| Apple                   | 24        | 0.62%   |
| Medion                  | 22        | 0.57%   |
| eMachines               | 22        | 0.57%   |
| Unknown                 | 20        | 0.51%   |
| Sony                    | 17        | 0.44%   |
| Foxconn                 | 15        | 0.39%   |
| Alcor                   | 8         | 0.21%   |
| Raspberry Pi Foundation | 7         | 0.18%   |
| Microsoft               | 7         | 0.18%   |
| Hungaro Flotta Kft      | 7         | 0.18%   |
| HUAWEI                  | 6         | 0.15%   |
| Valve                   | 5         | 0.13%   |
| Pegatron                | 5         | 0.13%   |
| Supermicro              | 4         | 0.1%    |
| Insyde                  | 4         | 0.1%    |
| Biostar                 | 4         | 0.1%    |
| ZOTAC                   | 3         | 0.08%   |
| Timi                    | 3         | 0.08%   |
| Shuttle                 | 3         | 0.08%   |
| Huanan                  | 3         | 0.08%   |
| Clevo                   | 3         | 0.08%   |
| AOpen                   | 3         | 0.08%   |
| AMI                     | 3         | 0.08%   |
| ABIT                    | 3         | 0.08%   |
| VXL                     | 2         | 0.05%   |
| TUXEDO                  | 2         | 0.05%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP 250 G1                            | 41        | 1.06%   |
| ASRock FM2A75M Pro4+                 | 33        | 0.85%   |
| Unknown                              | 30        | 0.77%   |
| ASUS All Series                      | 28        | 0.72%   |
| Dell OptiPlex 3020                   | 23        | 0.59%   |
| Dell Latitude E6410                  | 19        | 0.49%   |
| HP Notebook                          | 13        | 0.33%   |
| HP 650                               | 13        | 0.33%   |
| Gigabyte G31M-ES2L                   | 13        | 0.33%   |
| Dell OptiPlex 755                    | 13        | 0.33%   |
| ASUS P5KPL-AM EPU                    | 12        | 0.31%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 11        | 0.28%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 11        | 0.28%   |
| Lenovo G50-45 80E3                   | 11        | 0.28%   |
| Dell OptiPlex 780                    | 11        | 0.28%   |
| HP 620                               | 10        | 0.26%   |
| Dell Latitude E6400                  | 10        | 0.26%   |
| Lenovo ThinkPad T400 2768WGB         | 9         | 0.23%   |
| Gigabyte H61M-S1                     | 9         | 0.23%   |
| Dell OptiPlex 760                    | 9         | 0.23%   |
| HP Pavilion 15                       | 8         | 0.21%   |
| HP EliteBook 8460p                   | 8         | 0.21%   |
| Dell Precision WorkStation T3500     | 8         | 0.21%   |
| Dell OptiPlex 7010                   | 8         | 0.21%   |
| Dell Latitude E6530                  | 8         | 0.21%   |
| Dell Latitude E6420                  | 8         | 0.21%   |
| Dell Inspiron 15-3567                | 8         | 0.21%   |
| ASUS X541NA                          | 8         | 0.21%   |
| ASRock G41M-VS3                      | 8         | 0.21%   |
| MSI MS-7817                          | 7         | 0.18%   |
| Lenovo Z50-75 80EC                   | 7         | 0.18%   |
| Lenovo G580 20150                    | 7         | 0.18%   |
| Lenovo G550 20023                    | 7         | 0.18%   |
| HP ProDesk 600 G2 SFF                | 7         | 0.18%   |
| HP EliteBook 6930p                   | 7         | 0.18%   |
| Gigabyte 970A-DS3P                   | 7         | 0.18%   |
| Dell Latitude E6430                  | 7         | 0.18%   |
| Dell Inspiron 3542                   | 7         | 0.18%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR | 7         | 0.18%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 7         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 204       | 5.25%   |
| Dell Latitude           | 189       | 4.86%   |
| Acer Aspire             | 172       | 4.43%   |
| HP Compaq               | 139       | 3.58%   |
| Dell OptiPlex           | 133       | 3.42%   |
| Dell Inspiron           | 124       | 3.19%   |
| Lenovo IdeaPad          | 116       | 2.99%   |
| HP EliteBook            | 93        | 2.39%   |
| ASUS VivoBook           | 68        | 1.75%   |
| HP 250                  | 63        | 1.62%   |
| HP ProBook              | 59        | 1.52%   |
| Toshiba Satellite       | 52        | 1.34%   |
| Lenovo ThinkCentre      | 52        | 1.34%   |
| HP Pavilion             | 52        | 1.34%   |
| ASUS PRIME              | 46        | 1.18%   |
| Fujitsu ESPRIMO         | 38        | 0.98%   |
| Dell Vostro             | 37        | 0.95%   |
| ASRock FM2A75M          | 33        | 0.85%   |
| Fujitsu Siemens ESPRIMO | 32        | 0.82%   |
| ASUS ROG                | 32        | 0.82%   |
| Fujitsu LIFEBOOK        | 31        | 0.8%    |
| Packard Bell EasyNote   | 30        | 0.77%   |
| Unknown                 | 30        | 0.77%   |
| ASUS All                | 28        | 0.72%   |
| Dell Precision          | 27        | 0.69%   |
| ASUS TUF                | 23        | 0.59%   |
| Fujitsu Siemens AMILO   | 22        | 0.57%   |
| Acer TravelMate         | 22        | 0.57%   |
| HP Laptop               | 18        | 0.46%   |
| ASUS P5KPL-AM           | 17        | 0.44%   |
| Acer Veriton            | 16        | 0.41%   |
| Acer Swift              | 16        | 0.41%   |
| HP EliteDesk            | 15        | 0.39%   |
| Gigabyte B450           | 15        | 0.39%   |
| ASUS ASUS               | 14        | 0.36%   |
| HP Notebook             | 13        | 0.33%   |
| HP 650                  | 13        | 0.33%   |
| Gigabyte G31M-ES2L      | 13        | 0.33%   |
| ASUS ZenBook            | 12        | 0.31%   |
| Lenovo Yoga             | 11        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 356       | 9.16%   |
| 2011    | 351       | 9.03%   |
| 2010    | 332       | 8.55%   |
| 2012    | 327       | 8.42%   |
| 2018    | 292       | 7.52%   |
| 2014    | 287       | 7.39%   |
| 2008    | 267       | 6.87%   |
| 2009    | 264       | 6.8%    |
| 2017    | 218       | 5.61%   |
| 2015    | 211       | 5.43%   |
| 2007    | 193       | 4.97%   |
| 2016    | 192       | 4.94%   |
| 2019    | 164       | 4.22%   |
| 2020    | 142       | 3.66%   |
| 2021    | 94        | 2.42%   |
| 2006    | 83        | 2.14%   |
| 2022    | 55        | 1.42%   |
| 2005    | 29        | 0.75%   |
| Unknown | 13        | 0.33%   |
| 2023    | 8         | 0.21%   |
| 2004    | 4         | 0.1%    |
| 2003    | 3         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2171      | 55.88%  |
| Desktop        | 1593      | 41%     |
| Convertible    | 32        | 0.82%   |
| All in one     | 29        | 0.75%   |
| Mini pc        | 25        | 0.64%   |
| Tablet         | 13        | 0.33%   |
| Server         | 12        | 0.31%   |
| System on chip | 9         | 0.23%   |
| Phone          | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3768      | 96.57%  |
| Enabled  | 134       | 3.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3883      | 99.95%  |
| Yes  | 2         | 0.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 1236      | 30.74%  |
| 4.01-8.0    | 874       | 21.74%  |
| 8.01-16.0   | 690       | 17.16%  |
| 16.01-24.0  | 439       | 10.92%  |
| 1.01-2.0    | 374       | 9.3%    |
| 32.01-64.0  | 163       | 4.05%   |
| 2.01-3.0    | 132       | 3.28%   |
| 0.51-1.0    | 41        | 1.02%   |
| 24.01-32.0  | 37        | 0.92%   |
| 64.01-256.0 | 31        | 0.77%   |
| 0.01-0.5    | 3         | 0.07%   |
| Unknown     | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1388      | 30.2%   |
| 0.51-1.0    | 1377      | 29.96%  |
| 0.01-0.5    | 700       | 15.23%  |
| 2.01-3.0    | 544       | 11.84%  |
| 3.01-4.0    | 254       | 5.53%   |
| 4.01-8.0    | 251       | 5.46%   |
| 8.01-16.0   | 66        | 1.44%   |
| 16.01-24.0  | 11        | 0.24%   |
| 32.01-64.0  | 2         | 0.04%   |
| Unknown     | 2         | 0.04%   |
| 64.01-256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2675      | 64.64%  |
| 2       | 935       | 22.6%   |
| 3       | 287       | 6.94%   |
| 4       | 112       | 2.71%   |
| 0       | 50        | 1.21%   |
| 5       | 46        | 1.11%   |
| 6       | 14        | 0.34%   |
| 8       | 6         | 0.14%   |
| 7       | 5         | 0.12%   |
| 9       | 3         | 0.07%   |
| 10      | 2         | 0.05%   |
| 14      | 1         | 0.02%   |
| 11      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2138      | 53.88%  |
| No        | 1830      | 46.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3598      | 92.47%  |
| No        | 293       | 7.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2663      | 67.86%  |
| No        | 1261      | 32.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1997      | 50.53%  |
| Yes       | 1955      | 49.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Hungary | 3885      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Budapest          | 1534      | 33.59%  |
| Szeged            | 94        | 2.06%   |
| Pécs             | 94        | 2.06%   |
| Miskolc           | 87        | 1.9%    |
| Debrecen          | 85        | 1.86%   |
| Tatabánya        | 80        | 1.75%   |
| Győr             | 80        | 1.75%   |
| Székesfehérvár | 59        | 1.29%   |
| Szombathely       | 57        | 1.25%   |
| Kecskemét        | 54        | 1.18%   |
| Szigetszentmiklos | 49        | 1.07%   |
| Zalaegerszeg      | 48        | 1.05%   |
| Érd              | 45        | 0.99%   |
| Nyiregyhaza       | 42        | 0.92%   |
| Veszprém         | 39        | 0.85%   |
| Szekszárd        | 37        | 0.81%   |
| Szolnok           | 36        | 0.79%   |
| Karcag            | 32        | 0.7%    |
| Gödöllő        | 29        | 0.63%   |
| Oroshaza          | 27        | 0.59%   |
| Eger              | 26        | 0.57%   |
| Dunaújváros     | 26        | 0.57%   |
| Berettyóújfalu  | 25        | 0.55%   |
| Toeroekbalint     | 23        | 0.5%    |
| Nagykanizsa       | 23        | 0.5%    |
| Salgotarjan       | 22        | 0.48%   |
| Hodmezovasarhely  | 21        | 0.46%   |
| Hatvan            | 20        | 0.44%   |
| Gyomro            | 20        | 0.44%   |
| Toekoel           | 19        | 0.42%   |
| Sopron            | 19        | 0.42%   |
| Mosonmagyaróvár | 19        | 0.42%   |
| Esztergom         | 19        | 0.42%   |
| Ajka              | 19        | 0.42%   |
| Siófok           | 18        | 0.39%   |
| Pomaz             | 18        | 0.39%   |
| Cegled            | 18        | 0.39%   |
| Békéscsaba      | 17        | 0.37%   |
| Papa              | 16        | 0.35%   |
| Kazincbarcika     | 16        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 937       | 1749   | 16.56%  |
| Seagate                     | 797       | 1254   | 14.09%  |
| Samsung Electronics         | 790       | 1314   | 13.96%  |
| Kingston                    | 681       | 1145   | 12.04%  |
| Toshiba                     | 490       | 803    | 8.66%   |
| Hitachi                     | 260       | 362    | 4.6%    |
| HGST                        | 164       | 270    | 2.9%    |
| SanDisk                     | 155       | 228    | 2.74%   |
| Unknown                     | 142       | 201    | 2.51%   |
| A-DATA Technology           | 121       | 194    | 2.14%   |
| Intel                       | 96        | 149    | 1.7%    |
| SK hynix                    | 94        | 134    | 1.66%   |
| Crucial                     | 77        | 132    | 1.36%   |
| Fujitsu                     | 65        | 79     | 1.15%   |
| SPCC                        | 64        | 87     | 1.13%   |
| Micron Technology           | 61        | 83     | 1.08%   |
| Maxtor                      | 52        | 68     | 0.92%   |
| Apacer                      | 46        | 67     | 0.81%   |
| JMicron Technology          | 30        | 34     | 0.53%   |
| Intenso                     | 29        | 47     | 0.51%   |
| China                       | 29        | 49     | 0.51%   |
| OCZ                         | 27        | 33     | 0.48%   |
| Patriot                     | 25        | 48     | 0.44%   |
| LITEON                      | 25        | 31     | 0.44%   |
| PNY                         | 22        | 36     | 0.39%   |
| Kingston Technology Company | 21        | 21     | 0.37%   |
| Transcend                   | 20        | 24     | 0.35%   |
| Kingmax                     | 20        | 40     | 0.35%   |
| Gigabyte Technology         | 20        | 49     | 0.35%   |
| KIOXIA                      | 17        | 21     | 0.3%    |
| KingSpec                    | 16        | 18     | 0.28%   |
| Apple                       | 14        | 22     | 0.25%   |
| Hewlett-Packard             | 13        | 17     | 0.23%   |
| Verbatim                    | 11        | 23     | 0.19%   |
| Team                        | 11        | 17     | 0.19%   |
| Phison                      | 11        | 15     | 0.19%   |
| LITEONIT                    | 10        | 14     | 0.18%   |
| Unknown                     | 10        | 13     | 0.18%   |
| Silicon Motion              | 9         | 11     | 0.16%   |
| GOODRAM                     | 9         | 10     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 150       | 2.42%   |
| Kingston SA400S37120G 120GB SSD                     | 125       | 2.02%   |
| Kingston SV300S37A120G 120GB SSD                    | 93        | 1.5%    |
| Kingston SA400S37480G 480GB SSD                     | 73        | 1.18%   |
| Seagate ST1000LM035-1RK172 1TB                      | 61        | 0.98%   |
| Toshiba DT01ACA100 1TB                              | 54        | 0.87%   |
| Seagate ST500DM002-1BD142 500GB                     | 53        | 0.85%   |
| Toshiba MQ01ABF050 500GB                            | 52        | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 51        | 0.82%   |
| Samsung SSD 850 EVO 250GB                           | 45        | 0.73%   |
| Toshiba MQ01ABD100 1TB                              | 44        | 0.71%   |
| Seagate ST500LT012-1DG142 500GB                     | 41        | 0.66%   |
| Kingston SUV400S37120G 120GB SSD                    | 39        | 0.63%   |
| Toshiba DT01ACA050 500GB                            | 36        | 0.58%   |
| HGST HTS545032A7E380 320GB                          | 34        | 0.55%   |
| Toshiba MQ04ABF100 1TB                              | 31        | 0.5%    |
| Samsung SSD 860 EVO 500GB                           | 31        | 0.5%    |
| A-DATA SU630 240GB SSD                              | 31        | 0.5%    |
| HGST HTS545050A7E680 500GB                          | 30        | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 29        | 0.47%   |
| Samsung SSD 860 EVO 250GB                           | 27        | 0.44%   |
| Seagate ST380815AS 80GB                             | 24        | 0.39%   |
| HGST HTS721010A9E630 1TB                            | 24        | 0.39%   |
| Toshiba HDWD130 3TB                                 | 23        | 0.37%   |
| SPCC Solid State Disk 256GB                         | 23        | 0.37%   |
| Samsung HD502HJ 500GB                               | 23        | 0.37%   |
| Toshiba HDWD110 1TB                                 | 22        | 0.35%   |
| Toshiba DT01ACA200 2TB                              | 22        | 0.35%   |
| Seagate ST9320325AS 320GB                           | 22        | 0.35%   |
| A-DATA SU700 120GB SSD                              | 22        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 21        | 0.34%   |
| Kingston SHFS37A120G 120GB SSD                      | 21        | 0.34%   |
| Samsung SSD 850 EVO 500GB                           | 20        | 0.32%   |
| JMicron Generic 240GB                               | 20        | 0.32%   |
| Seagate ST9500325AS 500GB                           | 19        | 0.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 19        | 0.31%   |
| Kingston SV300S37A240G 240GB SSD                    | 19        | 0.31%   |
| Unknown MMC Card  32GB                              | 18        | 0.29%   |
| Kingston SV300S37A60G 64GB SSD                      | 18        | 0.29%   |
| HGST HTS541010A9E680 1TB                            | 18        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 832       | 1537   | 28.51%  |
| Seagate             | 782       | 1228   | 26.8%   |
| Toshiba             | 427       | 701    | 14.63%  |
| Samsung Electronics | 278       | 435    | 9.53%   |
| Hitachi             | 260       | 362    | 8.91%   |
| HGST                | 164       | 270    | 5.62%   |
| Fujitsu             | 65        | 79     | 2.23%   |
| Maxtor              | 52        | 68     | 1.78%   |
| Unknown             | 14        | 19     | 0.48%   |
| Hewlett-Packard     | 7         | 7      | 0.24%   |
| HGST HTS            | 6         | 11     | 0.21%   |
| USB3.0              | 4         | 8      | 0.14%   |
| Quantum             | 4         | 4      | 0.14%   |
| IBM/Hitachi         | 4         | 5      | 0.14%   |
| Apple               | 3         | 5      | 0.1%    |
| WD MediaMax         | 2         | 4      | 0.07%   |
| Initio              | 2         | 3      | 0.07%   |
| ICY BOX             | 2         | 4      | 0.07%   |
| USB                 | 1         | 1      | 0.03%   |
| Space ke            | 1         | 1      | 0.03%   |
| JMicron Technology  | 1         | 1      | 0.03%   |
| External            | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| Dell                | 1         | 1      | 0.03%   |
| CSD                 | 1         | 2      | 0.03%   |
| ASMT                | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 622       | 1032   | 31.05%  |
| Samsung Electronics | 358       | 578    | 17.87%  |
| A-DATA Technology   | 111       | 177    | 5.54%   |
| SanDisk             | 103       | 144    | 5.14%   |
| WDC                 | 94        | 164    | 4.69%   |
| Crucial             | 71        | 124    | 3.54%   |
| Intel               | 61        | 99     | 3.05%   |
| SPCC                | 54        | 76     | 2.7%    |
| Apacer              | 44        | 65     | 2.2%    |
| SK hynix            | 43        | 69     | 2.15%   |
| Micron Technology   | 42        | 58     | 2.1%    |
| China               | 29        | 49     | 1.45%   |
| Toshiba             | 28        | 43     | 1.4%    |
| OCZ                 | 27        | 33     | 1.35%   |
| Intenso             | 26        | 43     | 1.3%    |
| LITEON              | 24        | 30     | 1.2%    |
| PNY                 | 22        | 36     | 1.1%    |
| Patriot             | 22        | 43     | 1.1%    |
| Kingmax             | 20        | 40     | 1%      |
| JMicron Technology  | 20        | 23     | 1%      |
| Transcend           | 19        | 21     | 0.95%   |
| Gigabyte Technology | 17        | 45     | 0.85%   |
| KingSpec            | 15        | 17     | 0.75%   |
| Verbatim            | 11        | 23     | 0.55%   |
| Team                | 10        | 16     | 0.5%    |
| LITEONIT            | 10        | 14     | 0.5%    |
| GOODRAM             | 9         | 10     | 0.45%   |
| Corsair             | 8         | 10     | 0.4%    |
| ASMT                | 6         | 8      | 0.3%    |
| Apple               | 6         | 10     | 0.3%    |
| Netac               | 5         | 11     | 0.25%   |
| Hewlett-Packard     | 4         | 5      | 0.2%    |
| Unknown             | 3         | 6      | 0.15%   |
| SATAFIRM            | 3         | 3      | 0.15%   |
| Leven               | 3         | 3      | 0.15%   |
| KingDian            | 3         | 3      | 0.15%   |
| HS-SSD-C100         | 3         | 3      | 0.15%   |
| BHT                 | 3         | 3      | 0.15%   |
| AMD                 | 3         | 3      | 0.15%   |
| Unknown             | 3         | 3      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2467      | 4761   | 49.37%  |
| SSD     | 1763      | 3201   | 35.28%  |
| NVMe    | 571       | 915    | 11.43%  |
| MMC     | 139       | 207    | 2.78%   |
| Unknown | 57        | 74     | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3433      | 7768   | 79.62%  |
| NVMe | 571       | 915    | 13.24%  |
| SAS  | 169       | 268    | 3.92%   |
| MMC  | 139       | 207    | 3.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2974      | 5697   | 71.73%  |
| 0.51-1.0        | 863       | 1559   | 20.82%  |
| 1.01-2.0        | 173       | 301    | 4.17%   |
| 2.01-3.0        | 59        | 189    | 1.42%   |
| 3.01-4.0        | 47        | 135    | 1.13%   |
| 4.01-10.0       | 22        | 50     | 0.53%   |
| 10.01-20.0      | 6         | 29     | 0.14%   |
| More than 100.0 | 2         | 2      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1540      | 34.06%  |
| 101-250        | 983       | 21.74%  |
| 251-500        | 640       | 14.15%  |
| 501-1000       | 325       | 7.19%   |
| 51-100         | 325       | 7.19%   |
| 1-20           | 215       | 4.75%   |
| 21-50          | 181       | 4%      |
| 1001-2000      | 171       | 3.78%   |
| More than 3000 | 77        | 1.7%    |
| 2001-3000      | 65        | 1.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1586      | 34.58%  |
| Unknown        | 1540      | 33.58%  |
| 21-50          | 444       | 9.68%   |
| 51-100         | 328       | 7.15%   |
| 101-250        | 285       | 6.21%   |
| 251-500        | 156       | 3.4%    |
| 501-1000       | 130       | 2.83%   |
| 1001-2000      | 75        | 1.64%   |
| More than 3000 | 26        | 0.57%   |
| 2001-3000      | 16        | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB         | 31        | 48     | 2.81%   |
| Kingston SV300S37A120G 120GB SSD   | 22        | 26     | 2%      |
| HGST HTS545050A7E680 500GB         | 20        | 30     | 1.81%   |
| Seagate ST500DM002-1BD142 500GB    | 19        | 34     | 1.72%   |
| A-DATA Technology SU630 240GB SSD  | 18        | 27     | 1.63%   |
| Seagate ST500LT012-9WS142 500GB    | 13        | 15     | 1.18%   |
| Seagate ST500LT012-1DG142 500GB    | 12        | 16     | 1.09%   |
| Toshiba MQ01ABF050 500GB           | 11        | 28     | 1%      |
| Seagate ST9320325AS 320GB          | 11        | 23     | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11        | 16     | 1%      |
| Toshiba DT01ACA050 500GB           | 10        | 13     | 0.91%   |
| Samsung Electronics HD103UJ 1TB    | 10        | 21     | 0.91%   |
| Seagate ST9500325AS 500GB          | 9         | 17     | 0.82%   |
| Seagate ST9250315AS 250GB          | 9         | 14     | 0.82%   |
| Seagate ST9320423AS 320GB          | 8         | 9      | 0.73%   |
| Hitachi HTS545050B9A300 500GB      | 8         | 12     | 0.73%   |
| HGST HTS541010A9E680 1TB           | 8         | 18     | 0.73%   |
| WDC WD5000AADS-00S9B0 500GB        | 7         | 8      | 0.64%   |
| Toshiba MQ01ABD100 1TB             | 7         | 9      | 0.64%   |
| Toshiba DT01ACA100 1TB             | 7         | 13     | 0.64%   |
| Samsung Electronics HM160HI 160GB  | 7         | 8      | 0.64%   |
| WDC WD5000AAKX-001CA0 500GB        | 6         | 6      | 0.54%   |
| Samsung Electronics HD161HJ 160GB  | 6         | 6      | 0.54%   |
| Hitachi HTS545016B9A300 160GB      | 6         | 6      | 0.54%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 5         | 8      | 0.45%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 5         | 10     | 0.45%   |
| Toshiba MQ01ABD050 500GB           | 5         | 5      | 0.45%   |
| Seagate ST980811AS 80GB            | 5         | 5      | 0.45%   |
| Seagate ST3250318AS 250GB          | 5         | 9      | 0.45%   |
| Seagate ST3160815AS 160GB          | 5         | 6      | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB     | 5         | 6      | 0.45%   |
| Samsung Electronics HD502HJ 500GB  | 5         | 8      | 0.45%   |
| Samsung Electronics HD321KJ 320GB  | 5         | 5      | 0.45%   |
| Samsung Electronics HD103SI 1TB    | 5         | 5      | 0.45%   |
| Maxtor 6Y080M0 80GB                | 5         | 6      | 0.45%   |
| Hitachi HTS547550A9E384 500GB      | 5         | 19     | 0.45%   |
| Hitachi HTS545050A7E380 500GB      | 5         | 7      | 0.45%   |
| Hitachi HTS545032B9A300 320GB      | 5         | 6      | 0.45%   |
| Hitachi HTS541680J9SA00 80GB       | 5         | 5      | 0.45%   |
| HGST HTS725050A7E630 500GB         | 5         | 5      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 236       | 337    | 22.04%  |
| WDC                 | 220       | 345    | 20.54%  |
| Samsung Electronics | 120       | 182    | 11.2%   |
| Hitachi             | 113       | 168    | 10.55%  |
| Toshiba             | 108       | 166    | 10.08%  |
| HGST                | 77        | 121    | 7.19%   |
| Kingston            | 52        | 66     | 4.86%   |
| Maxtor              | 28        | 42     | 2.61%   |
| A-DATA Technology   | 26        | 40     | 2.43%   |
| Fujitsu             | 23        | 31     | 2.15%   |
| Intel               | 16        | 29     | 1.49%   |
| SK hynix            | 9         | 13     | 0.84%   |
| SanDisk             | 4         | 5      | 0.37%   |
| Intenso             | 4         | 4      | 0.37%   |
| IBM/Hitachi         | 3         | 3      | 0.28%   |
| Hewlett-Packard     | 3         | 3      | 0.28%   |
| WD MediaMax         | 2         | 4      | 0.19%   |
| LITEON              | 2         | 2      | 0.19%   |
| KingSpec            | 2         | 2      | 0.19%   |
| Kingmax             | 2         | 2      | 0.19%   |
| China               | 2         | 2      | 0.19%   |
| Apacer              | 2         | 3      | 0.19%   |
| SPCC                | 1         | 1      | 0.09%   |
| SATAFIRM            | 1         | 1      | 0.09%   |
| R580                | 1         | 1      | 0.09%   |
| QUANTUM             | 1         | 1      | 0.09%   |
| Patriot             | 1         | 1      | 0.09%   |
| OCZ-AGIL            | 1         | 1      | 0.09%   |
| OCZ                 | 1         | 3      | 0.09%   |
| Micron Technology   | 1         | 1      | 0.09%   |
| Leven               | 1         | 1      | 0.09%   |
| JMicron Technology  | 1         | 1      | 0.09%   |
| Initio              | 1         | 2      | 0.09%   |
| ICY BOX             | 1         | 2      | 0.09%   |
| ExcelStor           | 1         | 1      | 0.09%   |
| CSD                 | 1         | 2      | 0.09%   |
| Crucial             | 1         | 1      | 0.09%   |
| ASMT                | 1         | 1      | 0.09%   |
| Apple               | 1         | 5      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 236       | 337    | 25.79%  |
| WDC                 | 215       | 339    | 23.5%   |
| Hitachi             | 113       | 168    | 12.35%  |
| Samsung Electronics | 109       | 162    | 11.91%  |
| Toshiba             | 101       | 151    | 11.04%  |
| HGST                | 77        | 121    | 8.42%   |
| Maxtor              | 28        | 42     | 3.06%   |
| Fujitsu             | 23        | 31     | 2.51%   |
| IBM/Hitachi         | 3         | 3      | 0.33%   |
| WD MediaMax         | 2         | 4      | 0.22%   |
| Hewlett-Packard     | 2         | 2      | 0.22%   |
| QUANTUM             | 1         | 1      | 0.11%   |
| Initio              | 1         | 2      | 0.11%   |
| ICY BOX             | 1         | 2      | 0.11%   |
| ExcelStor           | 1         | 1      | 0.11%   |
| CSD                 | 1         | 2      | 0.11%   |
| ASMT                | 1         | 1      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 839       | 1369   | 84.49%  |
| SSD     | 146       | 218    | 14.7%   |
| NVMe    | 7         | 8      | 0.7%    |
| Unknown | 1         | 1      | 0.1%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Samsung Electronics HD502HJ 500GB  | 2         | 3      | 8.33%   |
| Samsung Electronics HD103SJ 1TB    | 2         | 3      | 8.33%   |
| Zheino CHN-NGFFNV2280-256 256GB    | 1         | 1      | 4.17%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 7      | 4.17%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 1      | 4.17%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 4.17%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 4.17%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 4.17%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 4.17%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 4.17%   |
| Toshiba MK3275GSX 320GB            | 1         | 1      | 4.17%   |
| Seagate ST9160821AS 160GB          | 1         | 1      | 4.17%   |
| Seagate ST380815AS 80GB            | 1         | 3      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 4.17%   |
| Samsung Electronics SP0802N 80GB   | 1         | 1      | 4.17%   |
| Samsung Electronics HM060HI 64GB   | 1         | 1      | 4.17%   |
| Samsung Electronics HD204UI 2TB    | 1         | 1      | 4.17%   |
| Intel SSDPEKKW256G7 256GB          | 1         | 1      | 4.17%   |
| Hitachi HTS723232A7A364 320GB      | 1         | 1      | 4.17%   |
| Hitachi HDS721075CLA332 752GB      | 1         | 1      | 4.17%   |
| Hewlett-Packard SSD EX900 250GB    | 1         | 1      | 4.17%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 29.17%  |
| WDC                 | 6         | 12     | 25%     |
| Toshiba             | 3         | 3      | 12.5%   |
| Seagate             | 3         | 5      | 12.5%   |
| Hitachi             | 2         | 2      | 8.33%   |
| Zheino              | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Hewlett-Packard     | 1         | 1      | 4.17%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2319      | 5183   | 51.67%  |
| Detected | 1183      | 2345   | 26.36%  |
| Malfunc  | 962       | 1596   | 21.43%  |
| Failed   | 24        | 34     | 0.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2893      | 63.93%  |
| AMD                              | 695       | 15.36%  |
| Samsung Electronics              | 206       | 4.55%   |
| Kingston Technology Company      | 89        | 1.97%   |
| JMicron Technology               | 81        | 1.79%   |
| SanDisk                          | 79        | 1.75%   |
| Nvidia                           | 78        | 1.72%   |
| ASMedia Technology               | 65        | 1.44%   |
| SK hynix                         | 48        | 1.06%   |
| Marvell Technology Group         | 39        | 0.86%   |
| Toshiba America Info Systems     | 33        | 0.73%   |
| Phison Electronics               | 32        | 0.71%   |
| KIOXIA                           | 22        | 0.49%   |
| VIA Technologies                 | 21        | 0.46%   |
| Silicon Motion                   | 20        | 0.44%   |
| Micron Technology                | 20        | 0.44%   |
| Silicon Integrated Systems [SiS] | 14        | 0.31%   |
| Silicon Image                    | 13        | 0.29%   |
| LSI Logic / Symbios Logic        | 12        | 0.27%   |
| ADATA Technology                 | 12        | 0.27%   |
| Micron/Crucial Technology        | 8         | 0.18%   |
| Solid State Storage Technology   | 5         | 0.11%   |
| Realtek Semiconductor            | 5         | 0.11%   |
| Integrated Technology Express    | 5         | 0.11%   |
| Broadcom / LSI                   | 4         | 0.09%   |
| Apple                            | 4         | 0.09%   |
| Seagate Technology               | 3         | 0.07%   |
| Union Memory (Shenzhen)          | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| Lite-On Technology               | 2         | 0.04%   |
| HighPoint Technologies           | 2         | 0.04%   |
| Hewlett-Packard                  | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Initio                           | 1         | 0.02%   |
| 3ware                            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 420       | 7.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 207       | 3.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 195       | 3.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 189       | 3.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 184       | 3.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 172       | 3.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 152       | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 133       | 2.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 125       | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 113       | 2%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 102       | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 99        | 1.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 97        | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 95        | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 92        | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 87        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 81        | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 79        | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 78        | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 78        | 1.38%   |
| AMD FCH IDE Controller                                                                  | 73        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 71        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 66        | 1.17%   |
| AMD 400 Series Chipset SATA Controller                                                  | 66        | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 60        | 1.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 57        | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 52        | 0.92%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 52        | 0.92%   |
| Intel SATA Controller [RAID mode]                                                       | 51        | 0.9%    |
| Samsung NVMe SSD Controller 980                                                         | 50        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 50        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 50        | 0.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 49        | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 48        | 0.85%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 48        | 0.85%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 45        | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 39        | 0.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 39        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 39        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 39        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2899      | 60.46%  |
| IDE  | 1048      | 21.86%  |
| NVMe | 572       | 11.93%  |
| RAID | 257       | 5.36%   |
| SAS  | 11        | 0.23%   |
| SCSI | 8         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3055      | 78.64%  |
| AMD          | 816       | 21%     |
| ARM          | 10        | 0.26%   |
| CentaurHauls | 4         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 49        | 1.26%   |
| Intel Celeron CPU 1000M @ 1.80GHz           | 42        | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 39        | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz           | 38        | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 36        | 0.92%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 36        | 0.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 28        | 0.72%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 27        | 0.69%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 27        | 0.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 26        | 0.67%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 25        | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 23        | 0.59%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 23        | 0.59%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 22        | 0.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 21        | 0.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 21        | 0.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 21        | 0.54%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 21        | 0.54%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 21        | 0.54%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 21        | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 20        | 0.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 18        | 0.46%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 18        | 0.46%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 18        | 0.46%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 18        | 0.46%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 18        | 0.46%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 18        | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 17        | 0.44%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 16        | 0.41%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 16        | 0.41%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16        | 0.41%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 16        | 0.41%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 16        | 0.41%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 16        | 0.41%   |
| AMD FX-8350 Eight-Core Processor            | 16        | 0.41%   |
| AMD FX-6300 Six-Core Processor              | 16        | 0.41%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 15        | 0.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 15        | 0.38%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 15        | 0.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 15        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 822       | 21.1%   |
| Intel Core i3           | 453       | 11.63%  |
| Intel Core i7           | 363       | 9.32%   |
| Intel Core 2 Duo        | 337       | 8.65%   |
| Intel Celeron           | 283       | 7.26%   |
| Intel Pentium           | 163       | 4.18%   |
| AMD Ryzen 5             | 115       | 2.95%   |
| Intel Pentium Dual-Core | 103       | 2.64%   |
| Other                   | 100       | 2.57%   |
| Intel Atom              | 97        | 2.49%   |
| AMD A8                  | 81        | 2.08%   |
| Intel Xeon              | 76        | 1.95%   |
| AMD Ryzen 7             | 68        | 1.75%   |
| AMD FX                  | 56        | 1.44%   |
| Intel Core 2 Quad       | 54        | 1.39%   |
| AMD A4                  | 51        | 1.31%   |
| Intel Pentium Dual      | 49        | 1.26%   |
| Intel Core 2            | 48        | 1.23%   |
| AMD Ryzen 3             | 40        | 1.03%   |
| AMD Athlon II X2        | 40        | 1.03%   |
| AMD Athlon 64 X2        | 33        | 0.85%   |
| AMD A6                  | 33        | 0.85%   |
| AMD A10                 | 28        | 0.72%   |
| Intel Genuine           | 22        | 0.56%   |
| Intel Pentium 4         | 21        | 0.54%   |
| AMD Phenom II X4        | 20        | 0.51%   |
| AMD E1                  | 19        | 0.49%   |
| AMD E                   | 19        | 0.49%   |
| Intel Pentium Silver    | 16        | 0.41%   |
| AMD E2                  | 15        | 0.39%   |
| AMD Ryzen 9             | 14        | 0.36%   |
| Intel Celeron M         | 13        | 0.33%   |
| Intel Celeron Dual-Core | 13        | 0.33%   |
| Intel Pentium D         | 12        | 0.31%   |
| AMD Sempron             | 11        | 0.28%   |
| AMD Athlon II X4        | 11        | 0.28%   |
| AMD Athlon Dual Core    | 11        | 0.28%   |
| AMD Athlon              | 11        | 0.28%   |
| Intel Pentium M         | 9         | 0.23%   |
| AMD Athlon X4           | 9         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2248      | 57.57%  |
| 4       | 1023      | 26.2%   |
| 1       | 236       | 6.04%   |
| 6       | 215       | 5.51%   |
| 8       | 105       | 2.69%   |
| 3       | 29        | 0.74%   |
| 12      | 17        | 0.44%   |
| 10      | 12        | 0.31%   |
| 16      | 7         | 0.18%   |
| 14      | 6         | 0.15%   |
| Unknown | 2         | 0.05%   |
| 36      | 1         | 0.03%   |
| 28      | 1         | 0.03%   |
| 24      | 1         | 0.03%   |
| 20      | 1         | 0.03%   |
| 18      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3869      | 99.54%  |
| 2       | 17        | 0.44%   |
| Unknown | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1972      | 50.49%  |
| 1       | 1932      | 49.46%  |
| Unknown | 2         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3788      | 97.18%  |
| 32-bit         | 62        | 1.59%   |
| Unknown        | 48        | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 568       | 14.06%  |
| 0x1067a    | 328       | 8.12%   |
| 0x206a7    | 306       | 7.58%   |
| 0x306a9    | 272       | 6.73%   |
| 0x306c3    | 193       | 4.78%   |
| 0x20655    | 123       | 3.05%   |
| 0x6fd      | 105       | 2.6%    |
| 0x06001119 | 91        | 2.25%   |
| 0x40651    | 89        | 2.2%    |
| 0x306d4    | 79        | 1.96%   |
| 0x10676    | 79        | 1.96%   |
| 0x406e3    | 78        | 1.93%   |
| 0x506e3    | 72        | 1.78%   |
| 0x906ea    | 68        | 1.68%   |
| 0x806e9    | 68        | 1.68%   |
| 0x010000c8 | 61        | 1.51%   |
| 0x906e9    | 59        | 1.46%   |
| 0x806ea    | 58        | 1.44%   |
| 0x406c4    | 53        | 1.31%   |
| 0x6fb      | 52        | 1.29%   |
| 0x806ec    | 44        | 1.09%   |
| 0x20652    | 44        | 1.09%   |
| 0x106ca    | 38        | 0.94%   |
| 0x30678    | 37        | 0.92%   |
| 0x706a1    | 36        | 0.89%   |
| 0x806c1    | 34        | 0.84%   |
| 0x0800820d | 32        | 0.79%   |
| 0x506c9    | 31        | 0.77%   |
| 0x05000119 | 31        | 0.77%   |
| 0x6f2      | 27        | 0.67%   |
| 0x07030105 | 26        | 0.64%   |
| 0x06000852 | 26        | 0.64%   |
| 0x406c3    | 25        | 0.62%   |
| 0x06003106 | 25        | 0.62%   |
| 0x6f6      | 24        | 0.59%   |
| 0x106c2    | 23        | 0.57%   |
| 0x0700010f | 23        | 0.57%   |
| 0x806eb    | 22        | 0.54%   |
| 0x706e5    | 22        | 0.54%   |
| 0x0a50000c | 21        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 434       | 11.16%  |
| KabyLake         | 418       | 10.75%  |
| SandyBridge      | 335       | 8.62%   |
| Haswell          | 329       | 8.46%   |
| IvyBridge        | 293       | 7.54%   |
| Core             | 243       | 6.25%   |
| Westmere         | 191       | 4.91%   |
| Skylake          | 186       | 4.78%   |
| Piledriver       | 140       | 3.6%    |
| Silvermont       | 129       | 3.32%   |
| K10              | 118       | 3.03%   |
| Broadwell        | 92        | 2.37%   |
| Zen 2            | 75        | 1.93%   |
| K8 Hammer        | 70        | 1.8%    |
| Bonnell          | 68        | 1.75%   |
| Zen+             | 64        | 1.65%   |
| Zen              | 50        | 1.29%   |
| Goldmont plus    | 50        | 1.29%   |
| Unknown          | 49        | 1.26%   |
| Zen 3            | 48        | 1.23%   |
| NetBurst         | 47        | 1.21%   |
| Bobcat           | 47        | 1.21%   |
| Puma             | 43        | 1.11%   |
| TigerLake        | 39        | 1%      |
| IceLake          | 39        | 1%      |
| Goldmont         | 38        | 0.98%   |
| Excavator        | 38        | 0.98%   |
| Steamroller      | 37        | 0.95%   |
| P6               | 33        | 0.85%   |
| Nehalem          | 32        | 0.82%   |
| Jaguar           | 28        | 0.72%   |
| CometLake        | 27        | 0.69%   |
| K10 Llano        | 19        | 0.49%   |
| Alderlake Hybrid | 19        | 0.49%   |
| Bulldozer        | 9         | 0.23%   |
| K8 & K10 hybrid  | 7         | 0.18%   |
| Tremont          | 3         | 0.08%   |
| K6               | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2313      | 51.5%   |
| Nvidia                                       | 1105      | 24.6%   |
| AMD                                          | 1040      | 23.16%  |
| VIA Technologies                             | 13        | 0.29%   |
| Silicon Integrated Systems [SiS]             | 7         | 0.16%   |
| ASPEED Technology                            | 5         | 0.11%   |
| Matrox Electronics Systems                   | 4         | 0.09%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.04%   |
| ATI Technologies                             | 2         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 245       | 5.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 179       | 3.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 154       | 3.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 114       | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 98        | 2.07%   |
| Intel HD Graphics 620                                                                    | 85        | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 84        | 1.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 84        | 1.77%   |
| Intel HD Graphics 5500                                                                   | 81        | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 81        | 1.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 77        | 1.62%   |
| Intel HD Graphics 530                                                                    | 66        | 1.39%   |
| Intel UHD Graphics 620                                                                   | 63        | 1.33%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 61        | 1.29%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 58        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 57        | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 57        | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 53        | 1.12%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 52        | 1.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 52        | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 48        | 1.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 47        | 0.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 43        | 0.91%   |
| Nvidia GT218 [GeForce 210]                                                               | 42        | 0.89%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 39        | 0.82%   |
| Intel HD Graphics 630                                                                    | 39        | 0.82%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 37        | 0.78%   |
| AMD Richland [Radeon HD 8570D]                                                           | 37        | 0.78%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 37        | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 36        | 0.76%   |
| AMD Renoir                                                                               | 36        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 34        | 0.72%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 34        | 0.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 33        | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 33        | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 31        | 0.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 31        | 0.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 31        | 0.65%   |
| Intel HD Graphics 500                                                                    | 30        | 0.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1775      | 45.1%   |
| 1 x AMD                  | 788       | 20.02%  |
| 1 x Nvidia               | 672       | 17.07%  |
| Intel + Nvidia           | 391       | 9.93%   |
| Intel + AMD              | 111       | 2.82%   |
| 2 x AMD                  | 107       | 2.72%   |
| AMD + Nvidia             | 35        | 0.89%   |
| 1 x VIA                  | 13        | 0.33%   |
| Other                    | 11        | 0.28%   |
| 2 x Intel                | 7         | 0.18%   |
| 1 x SiS                  | 7         | 0.18%   |
| 2 x Nvidia               | 5         | 0.13%   |
| 1 x Matrox               | 4         | 0.1%    |
| 1 x ASPEED               | 4         | 0.1%    |
| AMD + XGI                | 2         | 0.05%   |
| 1 x Intel + 3 x AMD      | 1         | 0.03%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |
| AMD + ASPEED             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3525      | 89.67%  |
| Proprietary | 286       | 7.28%   |
| Unknown     | 120       | 3.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2011      | 49.75%  |
| 0.01-0.5   | 694       | 17.17%  |
| 1.01-2.0   | 528       | 13.06%  |
| 0.51-1.0   | 453       | 11.21%  |
| 3.01-4.0   | 200       | 4.95%   |
| 7.01-8.0   | 74        | 1.83%   |
| 5.01-6.0   | 49        | 1.21%   |
| 2.01-3.0   | 22        | 0.54%   |
| 8.01-16.0  | 8         | 0.2%    |
| 16.01-24.0 | 3         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 710       | 17.59%  |
| LG Display              | 472       | 11.69%  |
| AU Optronics            | 444       | 11%     |
| Goldstar                | 329       | 8.15%   |
| Chimei Innolux          | 286       | 7.09%   |
| BOE                     | 251       | 6.22%   |
| Dell                    | 154       | 3.82%   |
| Chi Mei Optoelectronics | 110       | 2.73%   |
| Lenovo                  | 106       | 2.63%   |
| Philips                 | 105       | 2.6%    |
| Ancor Communications    | 101       | 2.5%    |
| BenQ                    | 100       | 2.48%   |
| Acer                    | 95        | 2.35%   |
| Hewlett-Packard         | 92        | 2.28%   |
| Fujitsu Siemens         | 49        | 1.21%   |
| AOC                     | 45        | 1.11%   |
| LG Philips              | 38        | 0.94%   |
| HannStar                | 32        | 0.79%   |
| InfoVision              | 28        | 0.69%   |
| Sony                    | 27        | 0.67%   |
| Eizo                    | 25        | 0.62%   |
| ASUSTek Computer        | 25        | 0.62%   |
| LG Electronics          | 22        | 0.55%   |
| Vestel Elektronik       | 21        | 0.52%   |
| Apple                   | 21        | 0.52%   |
| NEC Computers           | 19        | 0.47%   |
| PANDA                   | 18        | 0.45%   |
| HKC                     | 17        | 0.42%   |
| ViewSonic               | 14        | 0.35%   |
| Medion                  | 14        | 0.35%   |
| IBM                     | 14        | 0.35%   |
| CPT                     | 14        | 0.35%   |
| Unknown                 | 13        | 0.32%   |
| Toshiba                 | 13        | 0.32%   |
| Sharp                   | 12        | 0.3%    |
| Belinea                 | 12        | 0.3%    |
| Panasonic               | 10        | 0.25%   |
| InnoLux Display         | 10        | 0.25%   |
| Arnos Instruments       | 10        | 0.25%   |
| Quanta Display          | 8         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 50        | 1.21%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 39        | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 36        | 0.87%   |
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                      | 31        | 0.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 25        | 0.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 0.58%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.53%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 22        | 0.53%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch       | 21        | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 19        | 0.46%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 15        | 0.36%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 15        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 15        | 0.36%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 14        | 0.34%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 14        | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.34%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 12        | 0.29%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 12        | 0.29%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch         | 12        | 0.29%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.29%   |
| HKC '' HKC1850 1360x768 409x230mm 18.5-inch                              | 12        | 0.29%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 12        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 12        | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 12        | 0.29%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.29%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.29%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 11        | 0.27%   |
| HannStar Hanns.G HQ191 HSD0013 1280x1024 376x301mm 19.0-inch             | 11        | 0.27%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                      | 11        | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 11        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.27%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.27%   |
| Ancor Communications VW195 ACI19AB 1440x900 408x255mm 18.9-inch          | 11        | 0.27%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch    | 11        | 0.27%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 10        | 0.24%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1394      | 35.6%   |
| 1366x768 (WXGA)    | 966       | 24.67%  |
| 1280x1024 (SXGA)   | 296       | 7.56%   |
| 1280x800 (WXGA)    | 178       | 4.55%   |
| 1600x900 (HD+)     | 172       | 4.39%   |
| 1440x900 (WXGA+)   | 172       | 4.39%   |
| 1680x1050 (WSXGA+) | 158       | 4.03%   |
| 3840x2160 (4K)     | 131       | 3.35%   |
| 2560x1440 (QHD)    | 62        | 1.58%   |
| 1920x1200 (WUXGA)  | 62        | 1.58%   |
| 1360x768           | 43        | 1.1%    |
| 1024x768 (XGA)     | 40        | 1.02%   |
| 1024x600           | 40        | 1.02%   |
| 2560x1080          | 36        | 0.92%   |
| Unknown            | 22        | 0.56%   |
| 1920x540           | 18        | 0.46%   |
| 2880x1800          | 13        | 0.33%   |
| 2560x1600          | 13        | 0.33%   |
| 3840x1080          | 10        | 0.26%   |
| 1600x1200          | 10        | 0.26%   |
| 3440x1440          | 7         | 0.18%   |
| 1280x720 (HD)      | 7         | 0.18%   |
| 2288x1287          | 6         | 0.15%   |
| 1920x1280          | 5         | 0.13%   |
| 1400x1050          | 5         | 0.13%   |
| 800x1280           | 4         | 0.1%    |
| 3840x2400          | 4         | 0.1%    |
| 2880x1620          | 3         | 0.08%   |
| 2736x1824          | 3         | 0.08%   |
| 2160x1440          | 3         | 0.08%   |
| 1680x945           | 3         | 0.08%   |
| 1280x768           | 3         | 0.08%   |
| 5760x2160          | 2         | 0.05%   |
| 3840x1200          | 2         | 0.05%   |
| 3280x1080          | 2         | 0.05%   |
| 3200x2000          | 2         | 0.05%   |
| 2048x1536          | 2         | 0.05%   |
| 2048x1152          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 1152x864           | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1284      | 31.74%  |
| 14      | 292       | 7.22%   |
| 21      | 283       | 6.99%   |
| 17      | 282       | 6.97%   |
| 19      | 253       | 6.25%   |
| 23      | 215       | 5.31%   |
| 24      | 202       | 4.99%   |
| 13      | 196       | 4.84%   |
| 27      | 165       | 4.08%   |
| Unknown | 119       | 2.94%   |
| 22      | 116       | 2.87%   |
| 18      | 113       | 2.79%   |
| 12      | 99        | 2.45%   |
| 20      | 51        | 1.26%   |
| 10      | 50        | 1.24%   |
| 34      | 42        | 1.04%   |
| 11      | 42        | 1.04%   |
| 84      | 39        | 0.96%   |
| 31      | 35        | 0.87%   |
| 72      | 20        | 0.49%   |
| 40      | 19        | 0.47%   |
| 16      | 15        | 0.37%   |
| 32      | 14        | 0.35%   |
| 54      | 13        | 0.32%   |
| 65      | 11        | 0.27%   |
| 42      | 8         | 0.2%    |
| 52      | 7         | 0.17%   |
| 60      | 5         | 0.12%   |
| 46      | 5         | 0.12%   |
| 25      | 5         | 0.12%   |
| 58      | 4         | 0.1%    |
| 49      | 4         | 0.1%    |
| 48      | 4         | 0.1%    |
| 8       | 4         | 0.1%    |
| 7       | 4         | 0.1%    |
| 142     | 3         | 0.07%   |
| 64      | 3         | 0.07%   |
| 39      | 3         | 0.07%   |
| 75      | 2         | 0.05%   |
| 55      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1783      | 44.55%  |
| 401-500        | 641       | 16.02%  |
| 501-600        | 565       | 14.12%  |
| 351-400        | 346       | 8.65%   |
| 201-300        | 277       | 6.92%   |
| Unknown        | 119       | 2.97%   |
| 1501-2000      | 61        | 1.52%   |
| 1001-1500      | 61        | 1.52%   |
| 701-800        | 57        | 1.42%   |
| 601-700        | 44        | 1.1%    |
| 801-900        | 23        | 0.57%   |
| 901-1000       | 12        | 0.3%    |
| 101-200        | 6         | 0.15%   |
| 1-100          | 4         | 0.1%    |
| More than 2000 | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2650      | 70.55%  |
| 16/10   | 572       | 15.23%  |
| 5/4     | 286       | 7.61%   |
| Unknown | 88        | 2.34%   |
| 4/3     | 78        | 2.08%   |
| 21/9    | 42        | 1.12%   |
| 3/2     | 25        | 0.67%   |
| 6/5     | 5         | 0.13%   |
| 32/9    | 3         | 0.08%   |
| 1.00    | 3         | 0.08%   |
| 0.67    | 3         | 0.08%   |
| 0.63    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1267      | 31.53%  |
| 201-250        | 668       | 16.63%  |
| 81-90          | 410       | 10.2%   |
| 151-200        | 383       | 9.53%   |
| 141-150        | 234       | 5.82%   |
| 301-350        | 165       | 4.11%   |
| Unknown        | 119       | 2.96%   |
| More than 1000 | 115       | 2.86%   |
| 121-130        | 106       | 2.64%   |
| 351-500        | 92        | 2.29%   |
| 61-70          | 87        | 2.17%   |
| 71-80          | 82        | 2.04%   |
| 251-300        | 74        | 1.84%   |
| 41-50          | 47        | 1.17%   |
| 51-60          | 45        | 1.12%   |
| 501-1000       | 43        | 1.07%   |
| 131-140        | 33        | 0.82%   |
| 111-120        | 25        | 0.62%   |
| 91-100         | 13        | 0.32%   |
| 1-40           | 10        | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1536      | 39.32%  |
| 101-120       | 1203      | 30.8%   |
| 121-160       | 825       | 21.12%  |
| Unknown       | 119       | 3.05%   |
| 161-240       | 113       | 2.89%   |
| 1-50          | 81        | 2.07%   |
| More than 240 | 29        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3451      | 86.34%  |
| 2     | 403       | 10.08%  |
| 0     | 107       | 2.68%   |
| 3     | 32        | 0.8%    |
| 4     | 4         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2044      | 35.55%  |
| Intel                             | 1532      | 26.65%  |
| Qualcomm Atheros                  | 837       | 14.56%  |
| Broadcom                          | 364       | 6.33%   |
| Broadcom Limited                  | 144       | 2.5%    |
| Ralink                            | 119       | 2.07%   |
| Marvell Technology Group          | 80        | 1.39%   |
| Qualcomm Atheros Communications   | 71        | 1.23%   |
| Ralink Technology                 | 63        | 1.1%    |
| TP-Link                           | 59        | 1.03%   |
| Nvidia                            | 52        | 0.9%    |
| MediaTek                          | 51        | 0.89%   |
| Dell                              | 27        | 0.47%   |
| Samsung Electronics               | 25        | 0.43%   |
| Hewlett-Packard                   | 22        | 0.38%   |
| Huawei Technologies               | 21        | 0.37%   |
| Ericsson Business Mobile Networks | 20        | 0.35%   |
| Xiaomi                            | 17        | 0.3%    |
| VIA Technologies                  | 17        | 0.3%    |
| Sierra Wireless                   | 16        | 0.28%   |
| JMicron Technology                | 14        | 0.24%   |
| ASUSTek Computer                  | 14        | 0.24%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.21%   |
| Attansic Technology               | 11        | 0.19%   |
| Aquantia                          | 10        | 0.17%   |
| ASIX Electronics                  | 9         | 0.16%   |
| Belkin Components                 | 7         | 0.12%   |
| Lenovo                            | 6         | 0.1%    |
| Edimax Technology                 | 6         | 0.1%    |
| DisplayLink                       | 6         | 0.1%    |
| D-Link System                     | 6         | 0.1%    |
| Microsoft                         | 5         | 0.09%   |
| IMC Networks                      | 5         | 0.09%   |
| D-Link                            | 5         | 0.09%   |
| Qualcomm                          | 4         | 0.07%   |
| Accton Technology                 | 4         | 0.07%   |
| NetGear                           | 3         | 0.05%   |
| Microchip Technology              | 3         | 0.05%   |
| ZyDAS                             | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1438      | 21.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 351       | 5.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 201       | 3.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 124       | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 118       | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 117       | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 91        | 1.37%   |
| Intel Wireless 8265 / 8275                                              | 91        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 78        | 1.17%   |
| Intel Wireless 7260                                                     | 76        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 73        | 1.1%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 68        | 1.02%   |
| Intel Wireless 7265                                                     | 68        | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 65        | 0.98%   |
| Intel 82577LM Gigabit Network Connection                                | 65        | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                         | 61        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 59        | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 0.81%   |
| Intel 82567LM Gigabit Network Connection                                | 54        | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 53        | 0.8%    |
| Intel Centrino Advanced-N 6200                                          | 53        | 0.8%    |
| Intel Wireless 3165                                                     | 52        | 0.78%   |
| Intel Ethernet Connection I217-LM                                       | 52        | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                    | 50        | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 50        | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 49        | 0.74%   |
| Intel Wi-Fi 6 AX200                                                     | 47        | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 40        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 39        | 0.59%   |
| Intel Wireless 8260                                                     | 39        | 0.59%   |
| Intel Wireless 3160                                                     | 39        | 0.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 39        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                          | 38        | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 36        | 0.54%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 36        | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 34        | 0.51%   |
| Intel I211 Gigabit Network Connection                                   | 34        | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 34        | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 33        | 0.5%    |
| Intel Wi-Fi 6 AX201                                                     | 33        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1084      | 38.96%  |
| Qualcomm Atheros                | 641       | 23.04%  |
| Realtek Semiconductor           | 365       | 13.12%  |
| Broadcom                        | 194       | 6.97%   |
| Ralink                          | 119       | 4.28%   |
| Qualcomm Atheros Communications | 71        | 2.55%   |
| Ralink Technology               | 63        | 2.26%   |
| TP-Link                         | 54        | 1.94%   |
| MediaTek                        | 48        | 1.73%   |
| Broadcom Limited                | 48        | 1.73%   |
| Sierra Wireless                 | 16        | 0.58%   |
| Dell                            | 16        | 0.58%   |
| ASUSTek Computer                | 14        | 0.5%    |
| Belkin Components               | 7         | 0.25%   |
| Edimax Technology               | 6         | 0.22%   |
| Microsoft                       | 5         | 0.18%   |
| IMC Networks                    | 5         | 0.18%   |
| D-Link                          | 4         | 0.14%   |
| NetGear                         | 3         | 0.11%   |
| Marvell Technology Group        | 3         | 0.11%   |
| Hewlett-Packard                 | 3         | 0.11%   |
| ZyDAS                           | 2         | 0.07%   |
| D-Link System                   | 2         | 0.07%   |
| VIA Technologies                | 1         | 0.04%   |
| TRENDnet                        | 1         | 0.04%   |
| Texas Instruments               | 1         | 0.04%   |
| Qualcomm                        | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| Fujitsu Siemens Computers       | 1         | 0.04%   |
| Accton Technology               | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 124       | 4.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 118       | 4.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 117       | 4.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 91        | 3.26%   |
| Intel Wireless 8265 / 8275                                              | 91        | 3.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 78        | 2.79%   |
| Intel Wireless 7260                                                     | 76        | 2.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 73        | 2.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 68        | 2.43%   |
| Intel Wireless 7265                                                     | 68        | 2.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 65        | 2.33%   |
| Qualcomm Atheros AR9271 802.11n                                         | 61        | 2.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 59        | 2.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 1.93%   |
| Intel Centrino Advanced-N 6200                                          | 53        | 1.9%    |
| Intel Wireless 3165                                                     | 52        | 1.86%   |
| Intel Wi-Fi 6 AX200                                                     | 47        | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 40        | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 39        | 1.4%    |
| Intel Wireless 8260                                                     | 39        | 1.4%    |
| Intel Wireless 3160                                                     | 39        | 1.4%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 39        | 1.4%    |
| Intel Centrino Ultimate-N 6300                                          | 38        | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 36        | 1.29%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 36        | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 33        | 1.18%   |
| Intel Wi-Fi 6 AX201                                                     | 33        | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 31        | 1.11%   |
| Intel WiFi Link 5100                                                    | 31        | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 30        | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                           | 29        | 1.04%   |
| Ralink MT7601U Wireless Adapter                                         | 28        | 1%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 27        | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 25        | 0.89%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 25        | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 24        | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 23        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 0.82%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 22        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 20        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1922      | 51.25%  |
| Intel                                  | 932       | 24.85%  |
| Qualcomm Atheros                       | 285       | 7.6%    |
| Broadcom                               | 196       | 5.23%   |
| Broadcom Limited                       | 97        | 2.59%   |
| Marvell Technology Group               | 77        | 2.05%   |
| Nvidia                                 | 52        | 1.39%   |
| Samsung Electronics                    | 25        | 0.67%   |
| Huawei Technologies                    | 18        | 0.48%   |
| Xiaomi                                 | 17        | 0.45%   |
| VIA Technologies                       | 15        | 0.4%    |
| JMicron Technology                     | 14        | 0.37%   |
| Silicon Integrated Systems [SiS]       | 12        | 0.32%   |
| Attansic Technology                    | 11        | 0.29%   |
| Aquantia                               | 10        | 0.27%   |
| ASIX Electronics                       | 9         | 0.24%   |
| Lenovo                                 | 6         | 0.16%   |
| DisplayLink                            | 6         | 0.16%   |
| TP-Link                                | 5         | 0.13%   |
| D-Link System                          | 4         | 0.11%   |
| Qualcomm                               | 3         | 0.08%   |
| Microchip Technology                   | 3         | 0.08%   |
| MediaTek                               | 3         | 0.08%   |
| Hewlett-Packard                        | 3         | 0.08%   |
| Accton Technology                      | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.05%   |
| Apple                                  | 2         | 0.05%   |
| T & A Mobile Phones                    | 1         | 0.03%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| Motorola PCS                           | 1         | 0.03%   |
| LG Electronics                         | 1         | 0.03%   |
| ICS Advent                             | 1         | 0.03%   |
| HMD Global                             | 1         | 0.03%   |
| Hangzhou Silan Microelectronics        | 1         | 0.03%   |
| Google                                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1438      | 37.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 351       | 9.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 201       | 5.29%   |
| Intel 82577LM Gigabit Network Connection                          | 65        | 1.71%   |
| Intel 82567LM Gigabit Network Connection                          | 54        | 1.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 53        | 1.4%    |
| Intel Ethernet Connection I217-LM                                 | 52        | 1.37%   |
| Intel Ethernet Connection (2) I219-V                              | 50        | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 50        | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 49        | 1.29%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 34        | 0.9%    |
| Intel I211 Gigabit Network Connection                             | 34        | 0.9%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 34        | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 31        | 0.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 31        | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 29        | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 0.74%   |
| Nvidia MCP61 Ethernet                                             | 28        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 28        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 28        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 22        | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 22        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 22        | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 21        | 0.55%   |
| Intel 82566MM Gigabit Network Connection                          | 21        | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 19        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 17        | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.42%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 16        | 0.42%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 16        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15        | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.4%    |
| Huawei JKM-LX1                                                    | 15        | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 15        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3593      | 56.85%  |
| WiFi     | 2660      | 42.09%  |
| Modem    | 65        | 1.03%   |
| Unknown  | 2         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2116      | 51.48%  |
| Ethernet | 1994      | 48.52%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2168      | 55.55%  |
| 1     | 1618      | 41.46%  |
| 0     | 69        | 1.77%   |
| 3     | 41        | 1.05%   |
| 4     | 6         | 0.15%   |
| 5     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3318      | 81.7%   |
| Yes  | 743       | 18.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 686       | 34.88%  |
| Qualcomm Atheros Communications | 189       | 9.61%   |
| Broadcom                        | 162       | 8.24%   |
| Realtek Semiconductor           | 152       | 7.73%   |
| Cambridge Silicon Radio         | 134       | 6.81%   |
| Lite-On Technology              | 100       | 5.08%   |
| IMC Networks                    | 97        | 4.93%   |
| Dell                            | 83        | 4.22%   |
| Hewlett-Packard                 | 75        | 3.81%   |
| Foxconn / Hon Hai               | 72        | 3.66%   |
| Ralink                          | 68        | 3.46%   |
| ASUSTek Computer                | 27        | 1.37%   |
| Toshiba                         | 25        | 1.27%   |
| Apple                           | 18        | 0.92%   |
| Ralink Technology               | 10        | 0.51%   |
| Realtek                         | 8         | 0.41%   |
| Askey Computer                  | 8         | 0.41%   |
| Conwise Technology              | 6         | 0.31%   |
| Chicony Electronics             | 6         | 0.31%   |
| Belkin Components               | 5         | 0.25%   |
| TP-Link                         | 4         | 0.2%    |
| Taiyo Yuden                     | 4         | 0.2%    |
| MediaTek                        | 4         | 0.2%    |
| Logitech                        | 4         | 0.2%    |
| Integrated System Solution      | 4         | 0.2%    |
| Foxconn International           | 4         | 0.2%    |
| Micro Star International        | 3         | 0.15%   |
| Alps Electric                   | 3         | 0.15%   |
| Marvell Semiconductor           | 2         | 0.1%    |
| Edimax Technology               | 2         | 0.1%    |
| Opticis                         | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 370       | 18.78%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 134       | 6.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 96        | 4.87%   |
| Realtek Bluetooth Radio                             | 88        | 4.47%   |
| Qualcomm Atheros  Bluetooth Device                  | 81        | 4.11%   |
| Intel AX201 Bluetooth                               | 70        | 3.55%   |
| Ralink RT3290 Bluetooth                             | 68        | 3.45%   |
| Intel AX200 Bluetooth                               | 43        | 2.18%   |
| Dell DW375 Bluetooth Module                         | 41        | 2.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.98%   |
| HP Broadcom 2070 Bluetooth Combo                    | 36        | 1.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 35        | 1.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.78%   |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 1.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 32        | 1.62%   |
| Intel Wireless-AC 3168 Bluetooth                    | 29        | 1.47%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.42%   |
| IMC Networks Bluetooth Device                       | 28        | 1.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 26        | 1.32%   |
| Broadcom HP Portable SoftSailing                    | 24        | 1.22%   |
| IMC Networks Wireless_Device                        | 23        | 1.17%   |
| Realtek RTL8723B Bluetooth                          | 22        | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 1.07%   |
| Lite-On Bluetooth Device                            | 21        | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 1.02%   |
| Realtek RTL8821A Bluetooth                          | 19        | 0.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.96%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 16        | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.76%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 14        | 0.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 0.66%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 12        | 0.61%   |
| Toshiba Bluetooth Device                            | 11        | 0.56%   |
| Intel Bluetooth Device                              | 11        | 0.56%   |
| Broadcom BCM2070 Bluetooth Device                   | 11        | 0.56%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 10        | 0.51%   |
| Intel AX210 Bluetooth                               | 9         | 0.46%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.46%   |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2928      | 58.64%  |
| AMD                                  | 1013      | 20.29%  |
| Nvidia                               | 720       | 14.42%  |
| C-Media Electronics                  | 87        | 1.74%   |
| Creative Labs                        | 41        | 0.82%   |
| Logitech                             | 20        | 0.4%    |
| Texas Instruments                    | 17        | 0.34%   |
| VIA Technologies                     | 16        | 0.32%   |
| Silicon Integrated Systems [SiS]     | 14        | 0.28%   |
| ASUSTek Computer                     | 14        | 0.28%   |
| Generalplus Technology               | 12        | 0.24%   |
| Plantronics                          | 7         | 0.14%   |
| Kingston Technology                  | 7         | 0.14%   |
| JMTek                                | 7         | 0.14%   |
| Creative Technology                  | 7         | 0.14%   |
| BEHRINGER International              | 6         | 0.12%   |
| Lenovo                               | 5         | 0.1%    |
| SteelSeries ApS                      | 4         | 0.08%   |
| Samson Technologies                  | 4         | 0.08%   |
| GN Netcom                            | 4         | 0.08%   |
| Focusrite-Novation                   | 4         | 0.08%   |
| Realtek Semiconductor                | 3         | 0.06%   |
| Hewlett-Packard                      | 3         | 0.06%   |
| Ensoniq                              | 3         | 0.06%   |
| Apple                                | 3         | 0.06%   |
| Yamaha                               | 2         | 0.04%   |
| Tenx Technology                      | 2         | 0.04%   |
| Promethean Limited                   | 2         | 0.04%   |
| D&M Holdings (Denon/Marantz)         | 2         | 0.04%   |
| ATI Technologies                     | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.02%   |
| TEAC                                 | 1         | 0.02%   |
| Syntek                               | 1         | 0.02%   |
| Superlux digit                       | 1         | 0.02%   |
| Sunplus Technology                   | 1         | 0.02%   |
| Sony                                 | 1         | 0.02%   |
| SM950T Microphone                    | 1         | 0.02%   |
| Sennheiser Communications            | 1         | 0.02%   |
| Rotel                                | 1         | 0.02%   |
| Reloop                               | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 316       | 5.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 292       | 4.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 271       | 4.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 256       | 4.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 245       | 4.12%   |
| AMD FCH Azalia Controller                                                                         | 243       | 4.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 204       | 3.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 199       | 3.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 189       | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 152       | 2.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 145       | 2.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 117       | 1.97%   |
| Intel 8 Series HD Audio Controller                                                                | 101       | 1.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 100       | 1.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 97        | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 97        | 1.63%   |
| Intel Broadwell-U Audio Controller                                                                | 92        | 1.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 91        | 1.53%   |
| AMD Kabini HDMI/DP Audio                                                                          | 89        | 1.5%    |
| AMD Trinity HDMI Audio Controller                                                                 | 82        | 1.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 81        | 1.36%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 73        | 1.23%   |
| Nvidia High Definition Audio Controller                                                           | 69        | 1.16%   |
| Intel 200 Series PCH HD Audio                                                                     | 67        | 1.13%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 64        | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 63        | 1.06%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 59        | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 58        | 0.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 58        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 57        | 0.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 55        | 0.93%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 54        | 0.91%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 51        | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 50        | 0.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 48        | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 48        | 0.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 47        | 0.79%   |
| AMD Wrestler HDMI Audio                                                                           | 46        | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 44        | 0.74%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 44        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 727       | 19.7%   |
| SK hynix                   | 693       | 18.78%  |
| Unknown                    | 636       | 17.24%  |
| Kingston                   | 599       | 16.23%  |
| Micron Technology          | 305       | 8.27%   |
| Nanya Technology           | 107       | 2.9%    |
| Elpida                     | 87        | 2.36%   |
| Crucial                    | 79        | 2.14%   |
| Kingmax                    | 77        | 2.09%   |
| Corsair                    | 64        | 1.73%   |
| Ramaxel Technology         | 55        | 1.49%   |
| G.Skill                    | 51        | 1.38%   |
| A-DATA Technology          | 39        | 1.06%   |
| CSX                        | 18        | 0.49%   |
| Team                       | 15        | 0.41%   |
| Patriot                    | 13        | 0.35%   |
| Qimonda                    | 12        | 0.33%   |
| Transcend                  | 11        | 0.3%    |
| 48spaces                   | 10        | 0.27%   |
| Unknown (ABCD)             | 9         | 0.24%   |
| ASint Technology           | 9         | 0.24%   |
| Melco                      | 8         | 0.22%   |
| Apacer                     | 8         | 0.22%   |
| Kingmax Semiconductor      | 6         | 0.16%   |
| Unknown                    | 5         | 0.14%   |
| Toshiba                    | 4         | 0.11%   |
| OCZ                        | 4         | 0.11%   |
| GeIL                       | 4         | 0.11%   |
| Unknown (09D5)             | 2         | 0.05%   |
| Silicon Power              | 2         | 0.05%   |
| PUSKILL                    | 2         | 0.05%   |
| Intersil                   | 2         | 0.05%   |
| Infineon                   | 2         | 0.05%   |
| Hikvision                  | 2         | 0.05%   |
| H                          | 2         | 0.05%   |
| Golden Empire              | 2         | 0.05%   |
| ZION                       | 1         | 0.03%   |
| Unknown (8A5B)             | 1         | 0.03%   |
| Unknown (7F7F7F7F7F970000) | 1         | 0.03%   |
| Unigen                     | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s       | 44        | 1.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 43        | 1.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 38        | 0.93%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 37        | 0.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 36        | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 35        | 0.86%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 34        | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 34        | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 30        | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 30        | 0.73%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 26        | 0.64%   |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 25        | 0.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 23        | 0.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 23        | 0.56%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s  | 22        | 0.54%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 22        | 0.54%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s       | 22        | 0.54%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 21        | 0.51%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 21        | 0.51%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 20        | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 20        | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 20        | 0.49%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 20        | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 19        | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 19        | 0.46%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 18        | 0.44%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 18        | 0.44%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s  | 18        | 0.44%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 17        | 0.42%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 17        | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 16        | 0.39%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 16        | 0.39%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 16        | 0.39%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s     | 16        | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 15        | 0.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 15        | 0.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2                     | 15        | 0.37%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 15        | 0.37%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s    | 14        | 0.34%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 13        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1447      | 45.82%  |
| DDR4    | 712       | 22.55%  |
| DDR2    | 409       | 12.95%  |
| SDRAM   | 234       | 7.41%   |
| Unknown | 189       | 5.98%   |
| DDR     | 61        | 1.93%   |
| LPDDR4  | 53        | 1.68%   |
| LPDDR3  | 24        | 0.76%   |
| DDR5    | 13        | 0.41%   |
| DRAM    | 10        | 0.32%   |
| LPDDR5  | 6         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1713      | 56.09%  |
| DIMM         | 1274      | 41.72%  |
| Row Of Chips | 55        | 1.8%    |
| Chip         | 8         | 0.26%   |
| RIMM         | 2         | 0.07%   |
| FB-DIMM      | 1         | 0.03%   |
| Unknown      | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 1221      | 35.08%  |
| 2048    | 920       | 26.43%  |
| 8192    | 726       | 20.86%  |
| 1024    | 345       | 9.91%   |
| 16384   | 169       | 4.85%   |
| 512     | 53        | 1.52%   |
| 32768   | 41        | 1.18%   |
| 256     | 4         | 0.11%   |
| Unknown | 2         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 887       | 25.37%  |
| 1333    | 328       | 9.38%   |
| 2667    | 267       | 7.64%   |
| 667     | 232       | 6.64%   |
| 800     | 221       | 6.32%   |
| 1334    | 187       | 5.35%   |
| 2400    | 172       | 4.92%   |
| 3200    | 160       | 4.58%   |
| Unknown | 143       | 4.09%   |
| 2133    | 120       | 3.43%   |
| 1067    | 91        | 2.6%    |
| 1866    | 68        | 1.95%   |
| 1867    | 57        | 1.63%   |
| 533     | 51        | 1.46%   |
| 1066    | 50        | 1.43%   |
| 2048    | 47        | 1.34%   |
| 4199    | 44        | 1.26%   |
| 3600    | 43        | 1.23%   |
| 400     | 35        | 1%      |
| 3266    | 22        | 0.63%   |
| 975     | 21        | 0.6%    |
| 1800    | 19        | 0.54%   |
| 1639    | 18        | 0.51%   |
| 333     | 14        | 0.4%    |
| 2933    | 13        | 0.37%   |
| 3466    | 12        | 0.34%   |
| 3400    | 12        | 0.34%   |
| 2666    | 12        | 0.34%   |
| 3000    | 11        | 0.31%   |
| 4267    | 10        | 0.29%   |
| 4266    | 9         | 0.26%   |
| 2000    | 9         | 0.26%   |
| 3151    | 8         | 0.23%   |
| 49926   | 7         | 0.2%    |
| 4800    | 7         | 0.2%    |
| 1648    | 7         | 0.2%    |
| 6400    | 6         | 0.17%   |
| 3733    | 6         | 0.17%   |
| 5808    | 5         | 0.14%   |
| 1400    | 5         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 59        | 48.36%  |
| Samsung Electronics   | 25        | 20.49%  |
| Canon                 | 14        | 11.48%  |
| Brother Industries    | 9         | 7.38%   |
| Seiko Epson           | 6         | 4.92%   |
| QinHeng Electronics   | 2         | 1.64%   |
| Lexmark International | 2         | 1.64%   |
| Xerox                 | 1         | 0.82%   |
| STMicroelectronics    | 1         | 0.82%   |
| Ricoh                 | 1         | 0.82%   |
| Prolific Technology   | 1         | 0.82%   |
| Oki Data              | 1         | 0.82%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2600 series                                    | 8         | 6.45%   |
| HP LaserJet 1020                                          | 6         | 4.84%   |
| Samsung ML-2010P Mono Laser Printer                       | 5         | 4.03%   |
| Samsung M2020 Series                                      | 5         | 4.03%   |
| Samsung ML-1640 Series Laser Printer                      | 4         | 3.23%   |
| HP DeskJet 2130 series                                    | 4         | 3.23%   |
| HP LaserJet P1005                                         | 3         | 2.42%   |
| HP LaserJet 1018                                          | 3         | 2.42%   |
| HP Deskjet 2050 J510                                      | 3         | 2.42%   |
| Canon LiDE 400                                            | 3         | 2.42%   |
| Brother HL-1110 series                                    | 3         | 2.42%   |
| Samsung SCX-3400 Series                                   | 2         | 1.61%   |
| QinHeng CH340S                                            | 2         | 1.61%   |
| HP Officejet J4500 series                                 | 2         | 1.61%   |
| HP LaserJet P1102                                         | 2         | 1.61%   |
| HP LaserJet 1022                                          | 2         | 1.61%   |
| HP LaserJet 1010                                          | 2         | 1.61%   |
| HP LaserJet 1000                                          | 2         | 1.61%   |
| HP DeskJet F4100 Printer series                           | 2         | 1.61%   |
| HP Deskjet F2280 series                                   | 2         | 1.61%   |
| HP DeskJet F2100 Printer series                           | 2         | 1.61%   |
| HP DeskJet 840c                                           | 2         | 1.61%   |
| HP Deskjet 3520 series                                    | 2         | 1.61%   |
| Canon TS5100 series                                       | 2         | 1.61%   |
| Brother HL-L2300D series                                  | 2         | 1.61%   |
| Xerox WorkCentre 3119 Series                              | 1         | 0.81%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.81%   |
| Seiko Epson XP-240 Series                                 | 1         | 0.81%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.81%   |
| Seiko Epson Printer                                       | 1         | 0.81%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.81%   |
| Seiko Epson L396 Series                                   | 1         | 0.81%   |
| Seiko Epson L120 Series                                   | 1         | 0.81%   |
| Samsung Xerox Phaser 3117 Laser Printer                   | 1         | 0.81%   |
| Samsung SCX-4650 4x21S Series                             | 1         | 0.81%   |
| Samsung SCX-4623 Series                                   | 1         | 0.81%   |
| Samsung SCX-4200 series                                   | 1         | 0.81%   |
| Samsung ML-1660 Series                                    | 1         | 0.81%   |
| Samsung ML-1630 Series                                    | 1         | 0.81%   |
| Samsung Composite Device                                  | 1         | 0.81%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 15        | 60%     |
| Hewlett-Packard                                | 4         | 16%     |
| Mustek Systems                                 | 2         | 8%      |
| UMAX                                           | 1         | 4%      |
| Siemens Information and Communication Products | 1         | 4%      |
| Seiko Epson                                    | 1         | 4%      |
| KYE Systems (Mouse Systems)                    | 1         | 4%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                                              | 4         | 16%     |
| Canon CanoScan LIDE 25                                                          | 3         | 12%     |
| Canon CanoScan LiDE 110                                                         | 3         | 12%     |
| Mustek Systems SNAPSCAN e22                                                     | 2         | 8%      |
| HP Scanjet 300                                                                  | 2         | 8%      |
| Canon CanoScan LiDE 120                                                         | 2         | 8%      |
| UMAX Astra 4400/4450                                                            | 1         | 4%      |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 4%      |
| Seiko Epson Stylus Photo RX500/510                                              | 1         | 4%      |
| KYE Systems (Mouse Systems) ColorPage-SF600                                     | 1         | 4%      |
| HP ScanJet 3770                                                                 | 1         | 4%      |
| HP ScanJet 2400c                                                                | 1         | 4%      |
| Canon CanoScan N1240U/LiDE 30                                                   | 1         | 4%      |
| Canon CanoScan LiDE 100                                                         | 1         | 4%      |
| Canon CanoScan 4200F                                                            | 1         | 4%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 517       | 24.39%  |
| Microdia                               | 207       | 9.76%   |
| IMC Networks                           | 204       | 9.62%   |
| Realtek Semiconductor                  | 168       | 7.92%   |
| Sunplus Innovation Technology          | 132       | 6.23%   |
| Suyin                                  | 94        | 4.43%   |
| Quanta                                 | 81        | 3.82%   |
| Bison Electronics                      | 80        | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 70        | 3.3%    |
| Logitech                               | 60        | 2.83%   |
| Syntek                                 | 54        | 2.55%   |
| Acer                                   | 46        | 2.17%   |
| Lite-On Technology                     | 39        | 1.84%   |
| Silicon Motion                         | 36        | 1.7%    |
| Lenovo                                 | 32        | 1.51%   |
| Z-Star Microelectronics                | 27        | 1.27%   |
| Apple                                  | 26        | 1.23%   |
| Alcor Micro                            | 23        | 1.08%   |
| Ricoh                                  | 20        | 0.94%   |
| KYE Systems (Mouse Systems)            | 19        | 0.9%    |
| Microsoft                              | 18        | 0.85%   |
| Primax Electronics                     | 17        | 0.8%    |
| GEMBIRD                                | 15        | 0.71%   |
| Samsung Electronics                    | 14        | 0.66%   |
| Luxvisions Innotech Limited            | 14        | 0.66%   |
| ALi                                    | 11        | 0.52%   |
| Sonix Technology                       | 10        | 0.47%   |
| Importek                               | 9         | 0.42%   |
| OmniVision Technologies                | 7         | 0.33%   |
| Trust                                  | 6         | 0.28%   |
| Generalplus Technology                 | 5         | 0.24%   |
| Aveo Technology                        | 5         | 0.24%   |
| Arkmicro Technologies                  | 5         | 0.24%   |
| Pixart Imaging                         | 4         | 0.19%   |
| LG Electronics                         | 4         | 0.19%   |
| MacroSilicon                           | 3         | 0.14%   |
| Jieli Technology                       | 3         | 0.14%   |
| icSpring                               | 3         | 0.14%   |
| DigiTech                               | 3         | 0.14%   |
| Cubeternet                             | 3         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 61        | 2.87%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 59        | 2.77%   |
| Microdia Integrated_Webcam_HD                 | 48        | 2.25%   |
| IMC Networks USB2.0 HD UVC WebCam             | 46        | 2.16%   |
| Chicony HP Truevision HD                      | 40        | 1.88%   |
| Chicony HD WebCam                             | 38        | 1.78%   |
| Sunplus Integrated_Webcam_HD                  | 36        | 1.69%   |
| Chicony USB2.0 VGA UVC WebCam                 | 30        | 1.41%   |
| Realtek Integrated_Webcam_HD                  | 27        | 1.27%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 25        | 1.17%   |
| Microdia Integrated Webcam                    | 25        | 1.17%   |
| Sunplus HP Truevision HD                      | 24        | 1.13%   |
| Chicony Lenovo EasyCamera                     | 24        | 1.13%   |
| Sunplus HD WebCam                             | 23        | 1.08%   |
| Realtek USB Camera                            | 21        | 0.99%   |
| IMC Networks Integrated Camera                | 20        | 0.94%   |
| Chicony FJ Camera                             | 20        | 0.94%   |
| Logitech Webcam C270                          | 19        | 0.89%   |
| IMC Networks EasyCamera                       | 19        | 0.89%   |
| Chicony USB2.0 HD UVC WebCam                  | 19        | 0.89%   |
| Bison Lenovo EasyCamera                       | 19        | 0.89%   |
| Microdia Sonix USB 2.0 Camera                 | 18        | 0.85%   |
| Lenovo Integrated Webcam                      | 18        | 0.85%   |
| Chicony VGA Webcam                            | 18        | 0.85%   |
| Chicony Integrated HP HD Webcam               | 18        | 0.85%   |
| Chicony EasyCamera                            | 18        | 0.85%   |
| Acer Lenovo EasyCamera                        | 18        | 0.85%   |
| Quanta VGA Webcam                             | 17        | 0.8%    |
| Bison Integrated Camera                       | 17        | 0.8%    |
| Realtek Integrated Webcam                     | 16        | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 16        | 0.75%   |
| Syntek Integrated Camera                      | 15        | 0.7%    |
| Microdia Camera                               | 15        | 0.7%    |
| Syntek Lenovo EasyCamera                      | 14        | 0.66%   |
| Realtek Integrated Webcam HD                  | 14        | 0.66%   |
| Microdia Laptop_Integrated_Webcam_HD          | 14        | 0.66%   |
| Lite-On Integrated Camera                     | 14        | 0.66%   |
| Chicony HP Webcam [2 MP Macro]                | 14        | 0.66%   |
| Syntek EasyCamera                             | 13        | 0.61%   |
| Samsung Galaxy series, misc. (MTP mode)       | 13        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 109       | 36.21%  |
| AuthenTec                          | 56        | 18.6%   |
| Synaptics                          | 42        | 13.95%  |
| Upek                               | 28        | 9.3%    |
| Shenzhen Goodix Technology         | 23        | 7.64%   |
| LighTuning Technology              | 17        | 5.65%   |
| STMicroelectronics                 | 11        | 3.65%   |
| Elan Microelectronics              | 11        | 3.65%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 1.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 27        | 8.97%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 8.64%   |
| AuthenTec AES2810                                                          | 23        | 7.64%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 19        | 6.31%   |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 4.32%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 3.99%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 3.99%   |
| Validity Sensors VFS491                                                    | 11        | 3.65%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 3.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 3.32%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 2.99%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.99%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 2.99%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 2.66%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.66%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 2.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 1.99%   |
| LighTuning Fingerprint Reader                                              | 6         | 1.99%   |
| Elan WBF Fingerprint Sensor                                                | 6         | 1.99%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.99%   |
| Synaptics  WBDI                                                            | 5         | 1.66%   |
| AuthenTec AES1600                                                          | 5         | 1.66%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.33%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 1.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 1.33%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1%      |
| Synaptics WBDI                                                             | 3         | 1%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1%      |
| Synaptics Fingerprint scanner                                              | 3         | 1%      |
| Elan ELAN:ARM-M4                                                           | 3         | 1%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.66%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.66%   |
| Synaptics UWP WBDI                                                         | 2         | 0.66%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.66%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.33%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.33%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.33%   |
| Synaptics WBDI Device                                                      | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 123       | 54.42%  |
| Alcor Micro               | 35        | 15.49%  |
| Lenovo                    | 29        | 12.83%  |
| O2 Micro                  | 27        | 11.95%  |
| Upek                      | 3         | 1.33%   |
| Gemalto (was Gemplus)     | 3         | 1.33%   |
| Yubico.com                | 1         | 0.44%   |
| Reiner SCT Kartensysteme  | 1         | 0.44%   |
| OmniKey                   | 1         | 0.44%   |
| Chicony Electronics       | 1         | 0.44%   |
| Aladdin Knowledge Systems | 1         | 0.44%   |
| Advanced Card Systems     | 1         | 0.44%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 64        | 28.32%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 35        | 15.49%  |
| Lenovo Integrated Smart Card Reader                                          | 29        | 12.83%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 11.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 26        | 11.5%   |
| Broadcom 5880                                                                | 17        | 7.52%   |
| Broadcom 58200                                                               | 16        | 7.08%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 1.33%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.44%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.44%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.44%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.44%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.44%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.44%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.44%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.44%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.44%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.44%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2937      | 73.41%  |
| 1     | 876       | 21.89%  |
| 2     | 161       | 4.02%   |
| 3     | 19        | 0.47%   |
| 4     | 4         | 0.1%    |
| 5     | 2         | 0.05%   |
| 10    | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 328       | 26.49%  |
| Fingerprint reader       | 300       | 24.23%  |
| Chipcard                 | 209       | 16.88%  |
| Net/wireless             | 96        | 7.75%   |
| Bluetooth                | 81        | 6.54%   |
| Multimedia controller    | 51        | 4.12%   |
| Storage                  | 38        | 3.07%   |
| Communication controller | 38        | 3.07%   |
| Camera                   | 27        | 2.18%   |
| Flash memory             | 18        | 1.45%   |
| Unassigned class         | 11        | 0.89%   |
| Sound                    | 10        | 0.81%   |
| Card reader              | 9         | 0.73%   |
| Net/ethernet             | 6         | 0.48%   |
| Storage/raid             | 4         | 0.32%   |
| Network                  | 3         | 0.24%   |
| Dvb card                 | 3         | 0.24%   |
| Storage/ata              | 2         | 0.16%   |
| Modem                    | 2         | 0.16%   |
| Storage/ide              | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |

