Linux in Thailand - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Thailand.

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

Total: 188

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | H370 Pro4                   | [ccf085e9dc](https://linux-hardware.org/?probe=ccf085e9dc) | May 02, 2022 |
| ASRock        | B450 Steel Legend           | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| ASUSTek       | H81M-E                      | [b485d8f932](https://linux-hardware.org/?probe=b485d8f932) | Apr 28, 2022 |
| MSI           | MEG X570 UNIFY              | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [be1e468728](https://linux-hardware.org/?probe=be1e468728) | Apr 17, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| Gigabyte      | GA-970A-DS3                 | [db31622d02](https://linux-hardware.org/?probe=db31622d02) | Mar 21, 2022 |
| Gigabyte      | B450M S2H                   | [1602a60580](https://linux-hardware.org/?probe=1602a60580) | Mar 18, 2022 |
| ASRock        | B450 Steel Legend           | [db613d4f60](https://linux-hardware.org/?probe=db613d4f60) | Mar 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [7a484a0d61](https://linux-hardware.org/?probe=7a484a0d61) | Mar 11, 2022 |
| ASRock        | H410M-HDV R2.0              | [0c91f1563f](https://linux-hardware.org/?probe=0c91f1563f) | Feb 14, 2022 |
| Unknown       | Intel X79                   | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [9544722d31](https://linux-hardware.org/?probe=9544722d31) | Feb 12, 2022 |
| ASUSTek       | Z170-K                      | [ad24d41607](https://linux-hardware.org/?probe=ad24d41607) | Feb 08, 2022 |
| Unknown       | Intel X79                   | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| HP            | 1998                        | [263c4b1a93](https://linux-hardware.org/?probe=263c4b1a93) | Feb 03, 2022 |
| MSI           | MEG X570 UNIFY              | [5e8f4aba70](https://linux-hardware.org/?probe=5e8f4aba70) | Feb 03, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| ASUSTek       | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| HP            | 82B4                        | [363fec4fa2](https://linux-hardware.org/?probe=363fec4fa2) | Jan 03, 2022 |
| ASRock        | M3A770DE                    | [92b50bf0b6](https://linux-hardware.org/?probe=92b50bf0b6) | Dec 27, 2021 |
| ASRock        | M3A770DE                    | [47fa1e385d](https://linux-hardware.org/?probe=47fa1e385d) | Dec 26, 2021 |
| HP            | 82B4                        | [02f9952fa5](https://linux-hardware.org/?probe=02f9952fa5) | Dec 24, 2021 |
| ASRock        | H510M-HVS R2.0              | [99e3241324](https://linux-hardware.org/?probe=99e3241324) | Dec 18, 2021 |
| MiTAC         | PD14RI                      | [e4dc1c326a](https://linux-hardware.org/?probe=e4dc1c326a) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| MSI           | Boston                      | [760fa25b63](https://linux-hardware.org/?probe=760fa25b63) | Dec 15, 2021 |
| MSI           | Boston                      | [bc4405aa85](https://linux-hardware.org/?probe=bc4405aa85) | Dec 15, 2021 |
| ASRock        | M3A770DE                    | [15671c0dbe](https://linux-hardware.org/?probe=15671c0dbe) | Dec 14, 2021 |
| MiTAC         | PD14RI                      | [acf3343fe7](https://linux-hardware.org/?probe=acf3343fe7) | Dec 13, 2021 |
| Gigabyte      | GA-970A-DS3                 | [e22dd08488](https://linux-hardware.org/?probe=e22dd08488) | Dec 02, 2021 |
| Gigabyte      | M52L-S3                     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | [6043e86d2a](https://linux-hardware.org/?probe=6043e86d2a) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MSI           | 3666h                       | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| MSI           | 3666h                       | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| Dell          | 0YXT71 A02                  | [ff477e5a71](https://linux-hardware.org/?probe=ff477e5a71) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | [f467bc83ef](https://linux-hardware.org/?probe=f467bc83ef) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [3bf6f778dc](https://linux-hardware.org/?probe=3bf6f778dc) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [f873a240d5](https://linux-hardware.org/?probe=f873a240d5) | Oct 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [26e5760e58](https://linux-hardware.org/?probe=26e5760e58) | Oct 08, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [26b0b41886](https://linux-hardware.org/?probe=26b0b41886) | Sep 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [71820e1f85](https://linux-hardware.org/?probe=71820e1f85) | Sep 18, 2021 |
| Gigabyte      | F2A68HM-DS2                 | [8ab840927b](https://linux-hardware.org/?probe=8ab840927b) | Sep 17, 2021 |
| HP            | 1497                        | [311efc294a](https://linux-hardware.org/?probe=311efc294a) | Sep 16, 2021 |
| ASRock        | 880GM-LE FX                 | [022e5df6bd](https://linux-hardware.org/?probe=022e5df6bd) | Sep 12, 2021 |
| ASRock        | 880GM-LE FX                 | [f7706441f2](https://linux-hardware.org/?probe=f7706441f2) | Sep 12, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [04e6db02f9](https://linux-hardware.org/?probe=04e6db02f9) | Sep 02, 2021 |
| ASUSTek       | M2N68-AM Plus               | [57b648bd45](https://linux-hardware.org/?probe=57b648bd45) | Aug 23, 2021 |
| VIA Techno... | EITX-3002                   | [db8b46aea5](https://linux-hardware.org/?probe=db8b46aea5) | Aug 21, 2021 |
| ASUSTek       | H81M-A                      | [ae7b04d5d3](https://linux-hardware.org/?probe=ae7b04d5d3) | Aug 12, 2021 |
| Dell          | 0D24M8 A00                  | [c56bb51edc](https://linux-hardware.org/?probe=c56bb51edc) | Aug 03, 2021 |
| ASRock        | B450M Steel Legend          | [73a47bf698](https://linux-hardware.org/?probe=73a47bf698) | Aug 02, 2021 |
| HP            | 0AECh D                     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [71aae9e020](https://linux-hardware.org/?probe=71aae9e020) | Jul 26, 2021 |
| Dell          | 0NK5PH A00                  | [3db5dd7ea0](https://linux-hardware.org/?probe=3db5dd7ea0) | Jul 26, 2021 |
| ASRock        | B450M Steel Legend          | [b1d25f1e88](https://linux-hardware.org/?probe=b1d25f1e88) | Jul 22, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [568a71080e](https://linux-hardware.org/?probe=568a71080e) | Jul 21, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [6bf04f98f6](https://linux-hardware.org/?probe=6bf04f98f6) | Jul 21, 2021 |
| MSI           | MEG X570 UNIFY              | [c503220e78](https://linux-hardware.org/?probe=c503220e78) | Jul 19, 2021 |
| ASRock        | H81M-HDS R2.0               | [e46886ce2d](https://linux-hardware.org/?probe=e46886ce2d) | Jul 12, 2021 |
| ASRock        | B450M Steel Legend          | [c298371b89](https://linux-hardware.org/?probe=c298371b89) | Jul 12, 2021 |
| ASRock        | H81M-HDS R2.0               | [f51a4f44b2](https://linux-hardware.org/?probe=f51a4f44b2) | Jul 12, 2021 |
| ASRock        | H110M-DVS R3.0              | [2c6fd223a1](https://linux-hardware.org/?probe=2c6fd223a1) | Jul 07, 2021 |
| ASRock        | H110M-DVS R3.0              | [1270256228](https://linux-hardware.org/?probe=1270256228) | Jul 07, 2021 |
| Gigabyte      | H370M D3H-CF                | [e8c3804e26](https://linux-hardware.org/?probe=e8c3804e26) | Jun 25, 2021 |
| MSI           | B450M MORTAR MAX            | [db886610f5](https://linux-hardware.org/?probe=db886610f5) | Jun 11, 2021 |
| MSI           | A320M-A PRO MAX             | [45b8d7ca02](https://linux-hardware.org/?probe=45b8d7ca02) | Jun 08, 2021 |
| Intel         | H61M S1                     | [f60c55c8c4](https://linux-hardware.org/?probe=f60c55c8c4) | May 27, 2021 |
| Acer          | Veriton X2665G              | [f23ed8abd1](https://linux-hardware.org/?probe=f23ed8abd1) | Apr 20, 2021 |
| Huanan        | X79 249PC V2.2              | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| ASRock        | G31M-S                      | [ee71002286](https://linux-hardware.org/?probe=ee71002286) | Mar 26, 2021 |
| Huanan        | X79 V6.11                   | [85cbe2c1ed](https://linux-hardware.org/?probe=85cbe2c1ed) | Mar 16, 2021 |
| ASRock        | M3A770DE                    | [bca1dbaafd](https://linux-hardware.org/?probe=bca1dbaafd) | Mar 10, 2021 |
| ASRock        | B450M Steel Legend          | [465d5f43f1](https://linux-hardware.org/?probe=465d5f43f1) | Mar 08, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| Gigabyte      | Z490 UD                     | [ec3e24bbcc](https://linux-hardware.org/?probe=ec3e24bbcc) | Mar 02, 2021 |
| Gigabyte      | F2A75M-HD2                  | [d8037b520e](https://linux-hardware.org/?probe=d8037b520e) | Feb 26, 2021 |
| Gigabyte      | H110M-DS2-CF                | [f1e66dfcc2](https://linux-hardware.org/?probe=f1e66dfcc2) | Feb 22, 2021 |
| ASUSTek       | P7P55D EVO                  | [90a83f66fc](https://linux-hardware.org/?probe=90a83f66fc) | Feb 21, 2021 |
| ASRock        | B450M Steel Legend          | [f201f92cda](https://linux-hardware.org/?probe=f201f92cda) | Feb 17, 2021 |
| ASRock        | B450M Steel Legend          | [5fca1fb85b](https://linux-hardware.org/?probe=5fca1fb85b) | Feb 17, 2021 |
| HP            | 1998                        | [c415742b9e](https://linux-hardware.org/?probe=c415742b9e) | Feb 13, 2021 |
| Dell          | OptiPlex GX620              | [d6748871e7](https://linux-hardware.org/?probe=d6748871e7) | Feb 13, 2021 |
| Gigabyte      | H67MA-USB3-B3               | [bd0fcefe9f](https://linux-hardware.org/?probe=bd0fcefe9f) | Feb 13, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [da10acb66c](https://linux-hardware.org/?probe=da10acb66c) | Feb 07, 2021 |
| Dell          | OptiPlex GX620              | [d6ce430a08](https://linux-hardware.org/?probe=d6ce430a08) | Feb 04, 2021 |
| Gigabyte      | G41M-ES2H                   | [53c32c80a6](https://linux-hardware.org/?probe=53c32c80a6) | Feb 03, 2021 |
| Acer          | Aspire M1935                | [64d53ff0ad](https://linux-hardware.org/?probe=64d53ff0ad) | Jan 28, 2021 |
| Fujitsu       | JIM76YK3                    | [4c5225559f](https://linux-hardware.org/?probe=4c5225559f) | Jan 23, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [6ba43f198a](https://linux-hardware.org/?probe=6ba43f198a) | Jan 22, 2021 |
| Fujitsu       | JIM76YK3                    | [256f91a6de](https://linux-hardware.org/?probe=256f91a6de) | Jan 12, 2021 |
| Fujitsu       | JIM76YK3                    | [b33ad621e1](https://linux-hardware.org/?probe=b33ad621e1) | Jan 07, 2021 |
| Gigabyte      | G31M-ES2L                   | [26d33eb0de](https://linux-hardware.org/?probe=26d33eb0de) | Jan 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [9bcae82db8](https://linux-hardware.org/?probe=9bcae82db8) | Dec 16, 2020 |
| ASUSTek       | PRIME A320M-K               | [039b541097](https://linux-hardware.org/?probe=039b541097) | Dec 16, 2020 |
| ASRock        | Z390 Pro4                   | [3befcf341c](https://linux-hardware.org/?probe=3befcf341c) | Dec 14, 2020 |
| ASUSTek       | Z87-PRO                     | [a5170be239](https://linux-hardware.org/?probe=a5170be239) | Dec 11, 2020 |
| ASUSTek       | P8H61-M LE                  | [86f61c5fce](https://linux-hardware.org/?probe=86f61c5fce) | Dec 11, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [813b0a40eb](https://linux-hardware.org/?probe=813b0a40eb) | Dec 01, 2020 |
| Unknown       | Unknown                     | [65fba277e7](https://linux-hardware.org/?probe=65fba277e7) | Nov 11, 2020 |
| Unknown       | Unknown                     | [2a8118e258](https://linux-hardware.org/?probe=2a8118e258) | Nov 11, 2020 |
| ASRock        | Z270 Killer SLI             | [42e012b0e1](https://linux-hardware.org/?probe=42e012b0e1) | Oct 19, 2020 |
| Gigabyte      | F2A85XM-HD3                 | [4a8bc27a98](https://linux-hardware.org/?probe=4a8bc27a98) | Oct 06, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [924b361628](https://linux-hardware.org/?probe=924b361628) | Oct 04, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | [cce759037c](https://linux-hardware.org/?probe=cce759037c) | Oct 01, 2020 |
| ASUSTek       | P8H61-M LE                  | [93a29298d7](https://linux-hardware.org/?probe=93a29298d7) | Sep 29, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [ade24e13ac](https://linux-hardware.org/?probe=ade24e13ac) | Sep 27, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [c9ece9190b](https://linux-hardware.org/?probe=c9ece9190b) | Sep 27, 2020 |
| ASRock        | B460M Steel Legend          | [5398b2247d](https://linux-hardware.org/?probe=5398b2247d) | Sep 12, 2020 |
| ASRock        | B460M Steel Legend          | [44abe999aa](https://linux-hardware.org/?probe=44abe999aa) | Sep 12, 2020 |
| ASUSTek       | H110M-E/M.2                 | [25c77e6927](https://linux-hardware.org/?probe=25c77e6927) | Sep 11, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2b4fe70eaf](https://linux-hardware.org/?probe=2b4fe70eaf) | Sep 04, 2020 |
| ASRock        | B450M Steel Legend          | [2aa3eef6bd](https://linux-hardware.org/?probe=2aa3eef6bd) | Sep 02, 2020 |
| Dell          | 0X8DXD A01                  | [0c6362ecb0](https://linux-hardware.org/?probe=0c6362ecb0) | Aug 24, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| ASRock        | Z77 Extreme6                | [a23bd9e79b](https://linux-hardware.org/?probe=a23bd9e79b) | Aug 19, 2020 |
| Gigabyte      | 970A-DS3P                   | [211cb85a6f](https://linux-hardware.org/?probe=211cb85a6f) | Aug 08, 2020 |
| ASRock        | B450 Pro4                   | [c318976f19](https://linux-hardware.org/?probe=c318976f19) | Jul 26, 2020 |
| Gigabyte      | P67A-UD3P-B3                | [d68a3e43ab](https://linux-hardware.org/?probe=d68a3e43ab) | Jul 25, 2020 |
| ASUSTek       | H110M-E/M.2                 | [f395c86ea3](https://linux-hardware.org/?probe=f395c86ea3) | Jul 05, 2020 |
| ASUSTek       | H61M-D                      | [ef9bd4541a](https://linux-hardware.org/?probe=ef9bd4541a) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | [d9b6cb6c0b](https://linux-hardware.org/?probe=d9b6cb6c0b) | Jun 27, 2020 |
| ASUSTek       | S340MF                      | [e8b7344421](https://linux-hardware.org/?probe=e8b7344421) | Jun 24, 2020 |
| ASUSTek       | P5G41T-M LX                 | [262f40d535](https://linux-hardware.org/?probe=262f40d535) | Jun 20, 2020 |
| Gigabyte      | Z390 UD                     | [1bd38851f2](https://linux-hardware.org/?probe=1bd38851f2) | Jun 13, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [79456b5994](https://linux-hardware.org/?probe=79456b5994) | Jun 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [f839493f2c](https://linux-hardware.org/?probe=f839493f2c) | Jun 05, 2020 |
| ASUSTek       | Z170-P D3                   | [859b71baa9](https://linux-hardware.org/?probe=859b71baa9) | Jun 01, 2020 |
| ASUSTek       | Z170-P D3                   | [2c3fadf526](https://linux-hardware.org/?probe=2c3fadf526) | Jun 01, 2020 |
| ASUSTek       | M2N                         | [383651de63](https://linux-hardware.org/?probe=383651de63) | May 26, 2020 |
| ASUSTek       | Z170-P D3                   | [94ad6c90d4](https://linux-hardware.org/?probe=94ad6c90d4) | May 21, 2020 |
| Unknown       | Unknown                     | [6f211d004a](https://linux-hardware.org/?probe=6f211d004a) | May 10, 2020 |
| Unknown       | Unknown                     | [b3ddb6ef68](https://linux-hardware.org/?probe=b3ddb6ef68) | May 09, 2020 |
| Unknown       | Unknown                     | [0a74b9927c](https://linux-hardware.org/?probe=0a74b9927c) | May 09, 2020 |
| ASUSTek       | PRIME X470-PRO              | [1275e05c7b](https://linux-hardware.org/?probe=1275e05c7b) | Apr 20, 2020 |
| Pegatron      | 2A99                        | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| Gigabyte      | B250-HD3-CF                 | [8958ee3446](https://linux-hardware.org/?probe=8958ee3446) | Apr 07, 2020 |
| ASUSTek       | P5G41T-M LX                 | [4a07604dd5](https://linux-hardware.org/?probe=4a07604dd5) | Apr 06, 2020 |
| ASUSTek       | P5G41T-M LX                 | [2e22b43ab2](https://linux-hardware.org/?probe=2e22b43ab2) | Apr 06, 2020 |
| ASUSTek       | P5G41T-M LX                 | [c5b4596173](https://linux-hardware.org/?probe=c5b4596173) | Apr 06, 2020 |
| Packard Be... | imedia S3720                | [04ba71e930](https://linux-hardware.org/?probe=04ba71e930) | Feb 25, 2020 |
| Acer          | Aspire XC-330               | [168e69a32d](https://linux-hardware.org/?probe=168e69a32d) | Feb 11, 2020 |
| Acer          | Aspire XC-330               | [f1cbd72914](https://linux-hardware.org/?probe=f1cbd72914) | Feb 10, 2020 |
| Acer          | Aspire XC-330               | [0e517066e2](https://linux-hardware.org/?probe=0e517066e2) | Feb 08, 2020 |
| Acer          | Aspire XC-330               | [687cbfa242](https://linux-hardware.org/?probe=687cbfa242) | Feb 08, 2020 |
| HP            | 3048h                       | [ff1cde7e50](https://linux-hardware.org/?probe=ff1cde7e50) | Feb 04, 2020 |
| HP            | 3048h                       | [398e00244e](https://linux-hardware.org/?probe=398e00244e) | Feb 04, 2020 |
| HP            | 3048h                       | [69ac011884](https://linux-hardware.org/?probe=69ac011884) | Feb 04, 2020 |
| Gigabyte      | B250-HD3-CF                 | [a79eea9131](https://linux-hardware.org/?probe=a79eea9131) | Jan 30, 2020 |
| Gigabyte      | B250-HD3-CF                 | [d47fbd4f5c](https://linux-hardware.org/?probe=d47fbd4f5c) | Jan 30, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [00b99ed436](https://linux-hardware.org/?probe=00b99ed436) | Jan 20, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [1c91ad30fd](https://linux-hardware.org/?probe=1c91ad30fd) | Jan 19, 2020 |
| ASUSTek       | PRIME X470-PRO              | [eb0d14b4ad](https://linux-hardware.org/?probe=eb0d14b4ad) | Jan 18, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [8827da4dc1](https://linux-hardware.org/?probe=8827da4dc1) | Jan 15, 2020 |
| Gigabyte      | B250-HD3-CF                 | [c228f44226](https://linux-hardware.org/?probe=c228f44226) | Jan 14, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [dd045a2aef](https://linux-hardware.org/?probe=dd045a2aef) | Jan 13, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [3fb9d0e024](https://linux-hardware.org/?probe=3fb9d0e024) | Jan 11, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [c497f9da51](https://linux-hardware.org/?probe=c497f9da51) | Jan 10, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [4fae95f520](https://linux-hardware.org/?probe=4fae95f520) | Jan 10, 2020 |
| ASUSTek       | H110M-E/M.2                 | [f78dc97f63](https://linux-hardware.org/?probe=f78dc97f63) | Jan 07, 2020 |
| ASUSTek       | H110M-E/M.2                 | [0e11277c74](https://linux-hardware.org/?probe=0e11277c74) | Jan 06, 2020 |
| ASUSTek       | H110M-E/M.2                 | [14fcc63d5d](https://linux-hardware.org/?probe=14fcc63d5d) | Jan 06, 2020 |
| HP            | 2B15A                       | [24dd32836d](https://linux-hardware.org/?probe=24dd32836d) | Dec 14, 2019 |
| Acer          | Aspire TC-885 V:1.1         | [6d7723d13c](https://linux-hardware.org/?probe=6d7723d13c) | Dec 08, 2019 |
| MSI           | 760GM-P23                   | [bbd22621aa](https://linux-hardware.org/?probe=bbd22621aa) | Dec 05, 2019 |
| MSI           | B450M PRO-VDH PLUS          | [9f6b248a62](https://linux-hardware.org/?probe=9f6b248a62) | Nov 22, 2019 |
| ASUSTek       | H110M-E/M.2                 | [6a6a0d614e](https://linux-hardware.org/?probe=6a6a0d614e) | Oct 29, 2019 |
| ASUSTek       | H110M-E/M.2                 | [3d932d77ba](https://linux-hardware.org/?probe=3d932d77ba) | Oct 29, 2019 |
| MSI           | H110M PRO-VD PLUS           | [73bfd283e5](https://linux-hardware.org/?probe=73bfd283e5) | Oct 25, 2019 |
| ASUSTek       | PRIME Z370-A                | [7da594325d](https://linux-hardware.org/?probe=7da594325d) | Oct 07, 2019 |
| ASUSTek       | H81M-CS                     | [577f91eb8a](https://linux-hardware.org/?probe=577f91eb8a) | Aug 18, 2019 |
| ASUSTek       | H81M-E                      | [18e73b61d9](https://linux-hardware.org/?probe=18e73b61d9) | Aug 02, 2019 |
| MSI           | H170 GAMING M3              | [8b7204fcba](https://linux-hardware.org/?probe=8b7204fcba) | Jul 23, 2019 |
| Gigabyte      | F2A88XM-HD3P                | [7136ff50b4](https://linux-hardware.org/?probe=7136ff50b4) | Jul 04, 2019 |
| MSI           | 2A9C                        | [e4de30c7e4](https://linux-hardware.org/?probe=e4de30c7e4) | Jun 25, 2019 |
| Biostar       | A10N-8800E                  | [e160dec9cf](https://linux-hardware.org/?probe=e160dec9cf) | Jun 08, 2019 |
| ASUSTek       | P7P55 LX                    | [349a68f1f0](https://linux-hardware.org/?probe=349a68f1f0) | May 20, 2019 |
| ASUSTek       | P7P55 LX                    | [7c9e75ec67](https://linux-hardware.org/?probe=7c9e75ec67) | May 20, 2019 |
| MSI           | 2A9C                        | [d810098335](https://linux-hardware.org/?probe=d810098335) | May 09, 2019 |
| ASRock        | Z77 Pro4                    | [f0f2be33be](https://linux-hardware.org/?probe=f0f2be33be) | Apr 04, 2019 |
| ASRock        | Z77 Pro4                    | [04a8af85b2](https://linux-hardware.org/?probe=04a8af85b2) | Apr 03, 2019 |
| ASUSTek       | P8H61-M LE                  | [31229ee6d4](https://linux-hardware.org/?probe=31229ee6d4) | Feb 04, 2019 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [64fa4eaf5e](https://linux-hardware.org/?probe=64fa4eaf5e) | Nov 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 18.04                 | 23       | 18.4%   |
| Ubuntu 20.04                 | 22       | 17.6%   |
| OpenMandriva 4.2             | 7        | 5.6%    |
| Manjaro                      | 6        | 4.8%    |
| Arch Rolling                 | 4        | 3.2%    |
| Xubuntu 20.04                | 3        | 2.4%    |
| OpenMandriva 4.3             | 3        | 2.4%    |
| KDE neon 20.04               | 3        | 2.4%    |
| Zorin 15                     | 2        | 1.6%    |
| Xubuntu 18.04                | 2        | 1.6%    |
| Ubuntu 21.10                 | 2        | 1.6%    |
| Ubuntu 19.10                 | 2        | 1.6%    |
| Reborn OS                    | 2        | 1.6%    |
| Linux Mint 20                | 2        | 1.6%    |
| Endless 3.9.5                | 2        | 1.6%    |
| Endless 3.7.6                | 2        | 1.6%    |
| Zorin 16                     | 1        | 0.8%    |
| Xubuntu 21.10                | 1        | 0.8%    |
| Ubuntu MATE 18.04            | 1        | 0.8%    |
| Ubuntu Budgie 20.10          | 1        | 0.8%    |
| Ubuntu 22.04                 | 1        | 0.8%    |
| Ubuntu 21.04                 | 1        | 0.8%    |
| Ubuntu 19.04                 | 1        | 0.8%    |
| Ubuntu 16.04                 | 1        | 0.8%    |
| Solus 4.3                    | 1        | 0.8%    |
| Pop!_OS 22.04                | 1        | 0.8%    |
| Pop!_OS 21.10                | 1        | 0.8%    |
| Pop!_OS 21.04                | 1        | 0.8%    |
| Pop!_OS 20.10                | 1        | 0.8%    |
| Pop!_OS 20.04                | 1        | 0.8%    |
| openSUSE Tumbleweed-20211005 | 1        | 0.8%    |
| openSUSE 20200817            | 1        | 0.8%    |
| OpenMandriva 4.50            | 1        | 0.8%    |
| Manjaro 18.1.3               | 1        | 0.8%    |
| Linux Mint 20.2              | 1        | 0.8%    |
| Linux Mint 19.3              | 1        | 0.8%    |
| Linux Mint 19.2              | 1        | 0.8%    |
| Linux Mint 19.1              | 1        | 0.8%    |
| Fedora 35                    | 1        | 0.8%    |
| Fedora 33                    | 1        | 0.8%    |
| Fedora 32                    | 1        | 0.8%    |
| Fedora 29                    | 1        | 0.8%    |
| Endless 3.9.3                | 1        | 0.8%    |
| Endless 3.9.0                | 1        | 0.8%    |
| Endless 3.8.1                | 1        | 0.8%    |
| Endless 3.6.1-nexthw1        | 1        | 0.8%    |
| Elementary 6.1               | 1        | 0.8%    |
| Debian Testing               | 1        | 0.8%    |
| Clear Linux 36250            | 1        | 0.8%    |
| Clear Linux                  | 1        | 0.8%    |
| CentOS 8                     | 1        | 0.8%    |
| BlackPanther 18.1            | 1        | 0.8%    |
| ArcoLinux Rolling            | 1        | 0.8%    |
| Arch                         | 1        | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 51       | 42.5%   |
| OpenMandriva  | 11       | 9.17%   |
| Xubuntu       | 6        | 5%      |
| Manjaro       | 6        | 5%      |
| Linux Mint    | 6        | 5%      |
| Endless       | 6        | 5%      |
| Pop!_OS       | 5        | 4.17%   |
| Arch          | 5        | 4.17%   |
| Fedora        | 4        | 3.33%   |
| Zorin         | 3        | 2.5%    |
| KDE neon      | 3        | 2.5%    |
| Reborn OS     | 2        | 1.67%   |
| openSUSE      | 2        | 1.67%   |
| Clear Linux   | 2        | 1.67%   |
| Ubuntu MATE   | 1        | 0.83%   |
| Ubuntu Budgie | 1        | 0.83%   |
| Solus         | 1        | 0.83%   |
| Elementary    | 1        | 0.83%   |
| Debian        | 1        | 0.83%   |
| CentOS        | 1        | 0.83%   |
| BlackPanther  | 1        | 0.83%   |
| ArcoLinux     | 1        | 0.83%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 7        | 5.3%    |
| 5.4.0-48-generic         | 4        | 3.03%   |
| 5.8.0-14-generic         | 3        | 2.27%   |
| 5.4.0-65-generic         | 3        | 2.27%   |
| 5.4.0-42-generic         | 3        | 2.27%   |
| 5.16.7-desktop-1omv4003  | 3        | 2.27%   |
| 5.8.0-63-generic         | 2        | 1.52%   |
| 5.4.0-77-generic         | 2        | 1.52%   |
| 5.4.0-66-generic         | 2        | 1.52%   |
| 5.4.0-59-generic         | 2        | 1.52%   |
| 5.4.0-45-generic         | 2        | 1.52%   |
| 5.4.0-37-generic         | 2        | 1.52%   |
| 5.3.0-23-generic         | 2        | 1.52%   |
| 5.13.0-22-generic        | 2        | 1.52%   |
| 5.11.0-41-generic        | 2        | 1.52%   |
| 5.11.0-37-generic        | 2        | 1.52%   |
| 5.0.0-37-generic         | 2        | 1.52%   |
| 5.0.0-23-generic         | 2        | 1.52%   |
| 5.9.16-1-MANJARO         | 1        | 0.76%   |
| 5.8.1-arch1-1            | 1        | 0.76%   |
| 5.8.0-7630-generic       | 1        | 0.76%   |
| 5.8.0-59-generic         | 1        | 0.76%   |
| 5.8.0-48-generic         | 1        | 0.76%   |
| 5.8.0-43-generic         | 1        | 0.76%   |
| 5.8.0-41-generic         | 1        | 0.76%   |
| 5.8.0-2-amd64            | 1        | 0.76%   |
| 5.8.0-1-default          | 1        | 0.76%   |
| 5.7.13-975.native        | 1        | 0.76%   |
| 5.6.6-300.fc32.x86_64    | 1        | 0.76%   |
| 5.6.2-arch1-2            | 1        | 0.76%   |
| 5.6.16-300.fc32.x86_64   | 1        | 0.76%   |
| 5.6.14-desktop-2bP       | 1        | 0.76%   |
| 5.5.7-arch1-1            | 1        | 0.76%   |
| 5.5.7-1-MANJARO          | 1        | 0.76%   |
| 5.4.82-1-lts             | 1        | 0.76%   |
| 5.4.80-hiveos            | 1        | 0.76%   |
| 5.4.0-99-generic         | 1        | 0.76%   |
| 5.4.0-91-generic         | 1        | 0.76%   |
| 5.4.0-80-generic         | 1        | 0.76%   |
| 5.4.0-7642-generic       | 1        | 0.76%   |
| 5.4.0-51-generic         | 1        | 0.76%   |
| 5.4.0-39-generic         | 1        | 0.76%   |
| 5.4.0-33-generic         | 1        | 0.76%   |
| 5.4.0-29-generic         | 1        | 0.76%   |
| 5.4.0-26-generic         | 1        | 0.76%   |
| 5.4.0-19-generic         | 1        | 0.76%   |
| 5.4.0-107-generic        | 1        | 0.76%   |
| 5.3.12-1-MANJARO         | 1        | 0.76%   |
| 5.3.0-53-generic         | 1        | 0.76%   |
| 5.3.0-45-generic         | 1        | 0.76%   |
| 5.3.0-40-generic         | 1        | 0.76%   |
| 5.3.0-29-generic         | 1        | 0.76%   |
| 5.3.0-28-generic         | 1        | 0.76%   |
| 5.3.0-18-generic         | 1        | 0.76%   |
| 5.17.4-1139.native       | 1        | 0.76%   |
| 5.17.3-arch1-1           | 1        | 0.76%   |
| 5.17.1-3-MANJARO         | 1        | 0.76%   |
| 5.16.9-051609-generic    | 1        | 0.76%   |
| 5.16.2-1-MANJARO         | 1        | 0.76%   |
| 5.16.19-76051619-generic | 1        | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 29       | 22.66%  |
| 5.8.0   | 12       | 9.38%   |
| 4.15.0  | 11       | 8.59%   |
| 5.3.0   | 8        | 6.25%   |
| 5.13.0  | 7        | 5.47%   |
| 5.10.14 | 7        | 5.47%   |
| 5.0.0   | 7        | 5.47%   |
| 5.11.0  | 6        | 4.69%   |
| 4.18.0  | 5        | 3.91%   |
| 5.16.7  | 3        | 2.34%   |
| 5.5.7   | 2        | 1.56%   |
| 5.9.16  | 1        | 0.78%   |
| 5.8.1   | 1        | 0.78%   |
| 5.7.13  | 1        | 0.78%   |
| 5.6.6   | 1        | 0.78%   |
| 5.6.2   | 1        | 0.78%   |
| 5.6.16  | 1        | 0.78%   |
| 5.6.14  | 1        | 0.78%   |
| 5.4.82  | 1        | 0.78%   |
| 5.4.80  | 1        | 0.78%   |
| 5.3.12  | 1        | 0.78%   |
| 5.17.4  | 1        | 0.78%   |
| 5.17.3  | 1        | 0.78%   |
| 5.17.1  | 1        | 0.78%   |
| 5.16.9  | 1        | 0.78%   |
| 5.16.2  | 1        | 0.78%   |
| 5.16.19 | 1        | 0.78%   |
| 5.16.11 | 1        | 0.78%   |
| 5.16.0  | 1        | 0.78%   |
| 5.15.4  | 1        | 0.78%   |
| 5.15.2  | 1        | 0.78%   |
| 5.15.14 | 1        | 0.78%   |
| 5.14.6  | 1        | 0.78%   |
| 5.14.16 | 1        | 0.78%   |
| 5.13.19 | 1        | 0.78%   |
| 5.13.13 | 1        | 0.78%   |
| 5.13.1  | 1        | 0.78%   |
| 5.12.9  | 1        | 0.78%   |
| 5.10.16 | 1        | 0.78%   |
| 5.1.0   | 1        | 0.78%   |
| 5.0.17  | 1        | 0.78%   |
| 4.4.0   | 1        | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 31       | 24.41%  |
| 5.8     | 13       | 10.24%  |
| 4.15    | 11       | 8.66%   |
| 5.13    | 10       | 7.87%   |
| 5.3     | 9        | 7.09%   |
| 5.16    | 8        | 6.3%    |
| 5.10    | 8        | 6.3%    |
| 5.0     | 8        | 6.3%    |
| 5.11    | 6        | 4.72%   |
| 4.18    | 5        | 3.94%   |
| 5.6     | 3        | 2.36%   |
| 5.17    | 3        | 2.36%   |
| 5.15    | 3        | 2.36%   |
| 5.5     | 2        | 1.57%   |
| 5.14    | 2        | 1.57%   |
| 5.9     | 1        | 0.79%   |
| 5.7     | 1        | 0.79%   |
| 5.12    | 1        | 0.79%   |
| 5.1     | 1        | 0.79%   |
| 4.4     | 1        | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 114      | 99.13%  |
| i686   | 1        | 0.87%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 62       | 51.24%  |
| Unknown    | 17       | 14.05%  |
| KDE5       | 15       | 12.4%   |
| XFCE       | 9        | 7.44%   |
| X-Cinnamon | 7        | 5.79%   |
| KDE        | 3        | 2.48%   |
| MATE       | 2        | 1.65%   |
| Deepin     | 2        | 1.65%   |
| Budgie     | 2        | 1.65%   |
| Pantheon   | 1        | 0.83%   |
| Cinnamon   | 1        | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 98       | 83.76%  |
| Unknown | 12       | 10.26%  |
| Wayland | 7        | 5.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 79       | 66.95%  |
| SDDM    | 14       | 11.86%  |
| LightDM | 8        | 6.78%   |
| GDM     | 8        | 6.78%   |
| GDM3    | 6        | 5.08%   |
| TDM     | 3        | 2.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 76       | 64.41%  |
| Unknown | 16       | 13.56%  |
| th_TH   | 10       | 8.47%   |
| en_GB   | 5        | 4.24%   |
| de_DE   | 5        | 4.24%   |
| C       | 3        | 2.54%   |
| sv_SE   | 1        | 0.85%   |
| it_IT   | 1        | 0.85%   |
| de_CH   | 1        | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 78       | 65.55%  |
| EFI  | 41       | 34.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 95       | 80.51%  |
| Overlay | 12       | 10.17%  |
| Btrfs   | 4        | 3.39%   |
| Unknown | 4        | 3.39%   |
| Xfs     | 2        | 1.69%   |
| Zfs     | 1        | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 87       | 74.36%  |
| GPT     | 22       | 18.8%   |
| MBR     | 8        | 6.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 81.03%  |
| Yes       | 22       | 18.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 58.12%  |
| Yes       | 49       | 41.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 25       | 21.74%  |
| ASUSTek Computer    | 25       | 21.74%  |
| ASRock              | 20       | 17.39%  |
| MSI                 | 14       | 12.17%  |
| Hewlett-Packard     | 7        | 6.09%   |
| Acer                | 6        | 5.22%   |
| Dell                | 5        | 4.35%   |
| Unknown             | 3        | 2.61%   |
| Huanan              | 2        | 1.74%   |
| VIA Technologies    | 1        | 0.87%   |
| Pegatron            | 1        | 0.87%   |
| Packard Bell        | 1        | 0.87%   |
| MiTAC               | 1        | 0.87%   |
| Intel               | 1        | 0.87%   |
| Fujitsu             | 1        | 0.87%   |
| Biostar             | 1        | 0.87%   |
| Apple               | 1        | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 4        | 3.48%   |
| ASUS P8H61-M LE            | 3        | 2.61%   |
| Unknown                    | 3        | 2.61%   |
| HP EliteDesk 800 G1 SFF PC | 2        | 1.74%   |
| Gigabyte B250-HD3          | 2        | 1.74%   |
| ASUS H110M-E/M.2           | 2        | 1.74%   |
| ASRock B450 Steel Legend   | 2        | 1.74%   |
| Acer Aspire TC-885         | 2        | 1.74%   |
| VIA VX900                  | 1        | 0.87%   |
| Pegatron CQ3476L           | 1        | 0.87%   |
| Packard Bell imedia S3720  | 1        | 0.87%   |
| MSI Pro 3130 Microtower PC | 1        | 0.87%   |
| MSI Pro 2000/2080          | 1        | 0.87%   |
| MSI p6772l                 | 1        | 0.87%   |
| MSI MS-7C52                | 1        | 0.87%   |
| MSI MS-7C35                | 1        | 0.87%   |
| MSI MS-7B89                | 1        | 0.87%   |
| MSI MS-7B85                | 1        | 0.87%   |
| MSI MS-7A63                | 1        | 0.87%   |
| MSI MS-7A38                | 1        | 0.87%   |
| MSI MS-7A32                | 1        | 0.87%   |
| MSI MS-7A15                | 1        | 0.87%   |
| MSI MS-7978                | 1        | 0.87%   |
| MSI MS-7641                | 1        | 0.87%   |
| MSI KY779AA-AKL CQ3070L    | 1        | 0.87%   |
| MiTAC PD14RI               | 1        | 0.87%   |
| Intel H61M S1              | 1        | 0.87%   |
| Huanan X79 V6.11           | 1        | 0.87%   |
| Huanan X79 249PC V2.2      | 1        | 0.87%   |
| HP Z800 Workstation        | 1        | 0.87%   |
| HP ProDesk 600 G3 SFF      | 1        | 0.87%   |
| HP Compaq 6200 Pro SFF PC  | 1        | 0.87%   |
| HP Compaq 6000 Pro SFF PC  | 1        | 0.87%   |
| HP 20-2300x                | 1        | 0.87%   |
| Gigabyte Z97X-UD3H-BK      | 1        | 0.87%   |
| Gigabyte Z97X-UD3H         | 1        | 0.87%   |
| Gigabyte Z490 UD           | 1        | 0.87%   |
| Gigabyte Z390 UD           | 1        | 0.87%   |
| Gigabyte Z390 AORUS MASTER | 1        | 0.87%   |
| Gigabyte P67A-UD3P-B3      | 1        | 0.87%   |
| Gigabyte M52L-S3           | 1        | 0.87%   |
| Gigabyte H67MA-USB3-B3     | 1        | 0.87%   |
| Gigabyte H370M-D3H         | 1        | 0.87%   |
| Gigabyte H110M-DS2V        | 1        | 0.87%   |
| Gigabyte H110M-DS2         | 1        | 0.87%   |
| Gigabyte GA-970A-DS3       | 1        | 0.87%   |
| Gigabyte GA-78LMT-USB3 R2  | 1        | 0.87%   |
| Gigabyte GA-78LMT-USB3 6.0 | 1        | 0.87%   |
| Gigabyte G41M-ES2H         | 1        | 0.87%   |
| Gigabyte G31M-ES2L         | 1        | 0.87%   |
| Gigabyte F2A88XM-HD3P      | 1        | 0.87%   |
| Gigabyte F2A85XM-HD3       | 1        | 0.87%   |
| Gigabyte F2A75M-HD2        | 1        | 0.87%   |
| Gigabyte F2A68HM-DS2       | 1        | 0.87%   |
| Gigabyte B450M S2H         | 1        | 0.87%   |
| Gigabyte B450 AORUS ELITE  | 1        | 0.87%   |
| Gigabyte 970A-DS3P         | 1        | 0.87%   |
| Fujitsu FMVK01001          | 1        | 0.87%   |
| Dell Precision Tower 7910  | 1        | 0.87%   |
| Dell Precision 5820 Tower  | 1        | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Acer Aspire            | 5        | 4.35%   |
| ASUS All               | 4        | 3.48%   |
| Dell OptiPlex          | 3        | 2.61%   |
| ASUS PRIME             | 3        | 2.61%   |
| ASUS P8H61-M           | 3        | 2.61%   |
| ASRock B450            | 3        | 2.61%   |
| Unknown                | 3        | 2.61%   |
| MSI Pro                | 2        | 1.74%   |
| Huanan X79             | 2        | 1.74%   |
| HP EliteDesk           | 2        | 1.74%   |
| HP Compaq              | 2        | 1.74%   |
| Gigabyte Z390          | 2        | 1.74%   |
| Gigabyte GA-78LMT-USB3 | 2        | 1.74%   |
| Gigabyte B250-HD3      | 2        | 1.74%   |
| Dell Precision         | 2        | 1.74%   |
| ASUS M5A78L-M          | 2        | 1.74%   |
| ASUS H110M-E           | 2        | 1.74%   |
| ASRock Z77             | 2        | 1.74%   |
| ASRock B450M           | 2        | 1.74%   |
| VIA VX900              | 1        | 0.87%   |
| Pegatron CQ3476L       | 1        | 0.87%   |
| Packard Bell imedia    | 1        | 0.87%   |
| MSI p6772l             | 1        | 0.87%   |
| MSI MS-7C52            | 1        | 0.87%   |
| MSI MS-7C35            | 1        | 0.87%   |
| MSI MS-7B89            | 1        | 0.87%   |
| MSI MS-7B85            | 1        | 0.87%   |
| MSI MS-7A63            | 1        | 0.87%   |
| MSI MS-7A38            | 1        | 0.87%   |
| MSI MS-7A32            | 1        | 0.87%   |
| MSI MS-7A15            | 1        | 0.87%   |
| MSI MS-7978            | 1        | 0.87%   |
| MSI MS-7641            | 1        | 0.87%   |
| MSI KY779AA-AKL        | 1        | 0.87%   |
| MiTAC PD14RI           | 1        | 0.87%   |
| Intel H61M             | 1        | 0.87%   |
| HP Z800                | 1        | 0.87%   |
| HP ProDesk             | 1        | 0.87%   |
| HP 20-2300x            | 1        | 0.87%   |
| Gigabyte Z97X-UD3H-BK  | 1        | 0.87%   |
| Gigabyte Z97X-UD3H     | 1        | 0.87%   |
| Gigabyte Z490          | 1        | 0.87%   |
| Gigabyte P67A-UD3P-B3  | 1        | 0.87%   |
| Gigabyte M52L-S3       | 1        | 0.87%   |
| Gigabyte H67MA-USB3-B3 | 1        | 0.87%   |
| Gigabyte H370M-D3H     | 1        | 0.87%   |
| Gigabyte H110M-DS2V    | 1        | 0.87%   |
| Gigabyte H110M-DS2     | 1        | 0.87%   |
| Gigabyte GA-970A-DS3   | 1        | 0.87%   |
| Gigabyte G41M-ES2H     | 1        | 0.87%   |
| Gigabyte G31M-ES2L     | 1        | 0.87%   |
| Gigabyte F2A88XM-HD3P  | 1        | 0.87%   |
| Gigabyte F2A85XM-HD3   | 1        | 0.87%   |
| Gigabyte F2A75M-HD2    | 1        | 0.87%   |
| Gigabyte F2A68HM-DS2   | 1        | 0.87%   |
| Gigabyte B450M         | 1        | 0.87%   |
| Gigabyte B450          | 1        | 0.87%   |
| Gigabyte 970A-DS3P     | 1        | 0.87%   |
| Fujitsu FMVK01001      | 1        | 0.87%   |
| Biostar A10N-8800E     | 1        | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 19       | 16.52%  |
| 2012 | 10       | 8.7%    |
| 2011 | 10       | 8.7%    |
| 2020 | 9        | 7.83%   |
| 2019 | 9        | 7.83%   |
| 2017 | 9        | 7.83%   |
| 2016 | 9        | 7.83%   |
| 2009 | 9        | 7.83%   |
| 2013 | 7        | 6.09%   |
| 2014 | 6        | 5.22%   |
| 2010 | 5        | 4.35%   |
| 2008 | 4        | 3.48%   |
| 2015 | 3        | 2.61%   |
| 2006 | 3        | 2.61%   |
| 2021 | 2        | 1.74%   |
| 2007 | 1        | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 115      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 113      | 97.41%  |
| Enabled  | 3        | 2.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 115      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 29       | 24.17%  |
| 16.01-24.0      | 24       | 20%     |
| 3.01-4.0        | 22       | 18.33%  |
| 4.01-8.0        | 21       | 17.5%   |
| 32.01-64.0      | 14       | 11.67%  |
| 1.01-2.0        | 6        | 5%      |
| More than 256.0 | 1        | 0.83%   |
| 24.01-32.0      | 1        | 0.83%   |
| 64.01-256.0     | 1        | 0.83%   |
| 0.51-1.0        | 1        | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 51       | 39.84%  |
| 2.01-3.0   | 40       | 31.25%  |
| 4.01-8.0   | 12       | 9.38%   |
| 3.01-4.0   | 11       | 8.59%   |
| 0.51-1.0   | 8        | 6.25%   |
| 16.01-24.0 | 2        | 1.56%   |
| 8.01-16.0  | 2        | 1.56%   |
| 24.01-32.0 | 1        | 0.78%   |
| 0.01-0.5   | 1        | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 41.32%  |
| 2      | 35       | 28.93%  |
| 3      | 19       | 15.7%   |
| 4      | 8        | 6.61%   |
| 5      | 5        | 4.13%   |
| 0      | 3        | 2.48%   |
| 32     | 1        | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 58.12%  |
| Yes       | 49       | 41.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 111      | 96.52%  |
| No        | 4        | 3.48%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 59       | 50.43%  |
| No        | 58       | 49.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 74.58%  |
| Yes       | 30       | 25.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Thailand | 115      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Bangkok           | 43       | 35.54%  |
| Chiang Mai        | 15       | 12.4%   |
| Chon Buri         | 6        | 4.96%   |
| Phuket            | 4        | 3.31%   |
| Chiang Rai        | 4        | 3.31%   |
| Nakhon Ratchasima | 3        | 2.48%   |
| Khon Kaen         | 3        | 2.48%   |
| Phitsanulok       | 2        | 1.65%   |
| Pathum Thani      | 2        | 1.65%   |
| Nonthaburi        | 2        | 1.65%   |
| Nakhon Pathom     | 2        | 1.65%   |
| Khu Mueang        | 2        | 1.65%   |
| Bang Lamung       | 2        | 1.65%   |
| Ban Phan Don      | 2        | 1.65%   |
| Uthai Thani       | 1        | 0.83%   |
| Trang             | 1        | 0.83%   |
| Thanyaburi        | 1        | 0.83%   |
| Tak               | 1        | 0.83%   |
| Surat Thani       | 1        | 0.83%   |
| Sattahip          | 1        | 0.83%   |
| San Sai           | 1        | 0.83%   |
| Samut Prakan      | 1        | 0.83%   |
| Sadao             | 1        | 0.83%   |
| Rueso             | 1        | 0.83%   |
| Rayong            | 1        | 0.83%   |
| Ratchathewi       | 1        | 0.83%   |
| Ratchaburi        | 1        | 0.83%   |
| Phan              | 1        | 0.83%   |
| Nakhon Sawan      | 1        | 0.83%   |
| Na Di             | 1        | 0.83%   |
| Lopburi           | 1        | 0.83%   |
| Loei              | 1        | 0.83%   |
| Krasang           | 1        | 0.83%   |
| Kanchanaburi      | 1        | 0.83%   |
| Kamphaeng Phet    | 1        | 0.83%   |
| Kalasin           | 1        | 0.83%   |
| Chatuchak         | 1        | 0.83%   |
| Chana             | 1        | 0.83%   |
| Chaloem Phra Kiat | 1        | 0.83%   |
| Bang Klam         | 1        | 0.83%   |
| Ban Krabi Noi     | 1        | 0.83%   |
| Ban Ang Sila      | 1        | 0.83%   |
| Ayutthaya         | 1        | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 47       | 78     | 23.62%  |
| Seagate               | 41       | 66     | 20.6%   |
| Samsung Electronics   | 20       | 36     | 10.05%  |
| Kingston              | 13       | 13     | 6.53%   |
| Sandisk               | 8        | 9      | 4.02%   |
| Toshiba               | 6        | 8      | 3.02%   |
| Hitachi               | 6        | 6      | 3.02%   |
| Crucial               | 6        | 6      | 3.02%   |
| Unknown               | 4        | 9      | 2.01%   |
| Phison                | 4        | 9      | 2.01%   |
| KingSpec              | 3        | 5      | 1.51%   |
| JMicron               | 3        | 3      | 1.51%   |
| Intel                 | 3        | 3      | 1.51%   |
| HS-SSD-C100           | 3        | 7      | 1.51%   |
| Hikvision             | 3        | 3      | 1.51%   |
| GALAX                 | 3        | 3      | 1.51%   |
| SK Hynix              | 2        | 3      | 1.01%   |
| Silicon Motion        | 2        | 3      | 1.01%   |
| HGST                  | 2        | 5      | 1.01%   |
| External              | 2        | 2      | 1.01%   |
| Corsair               | 2        | 2      | 1.01%   |
| Colorful              | 2        | 3      | 1.01%   |
| Apacer                | 2        | 2      | 1.01%   |
| Verbatim              | 1        | 1      | 0.5%    |
| USB3.0                | 1        | 1      | 0.5%    |
| Transcend             | 1        | 1      | 0.5%    |
| TO Exter              | 1        | 1      | 0.5%    |
| SPCC                  | 1        | 1      | 0.5%    |
| Realtek Semiconductor | 1        | 1      | 0.5%    |
| PLEXTOR               | 1        | 1      | 0.5%    |
| Pioneer               | 1        | 1      | 0.5%    |
| OCZ                   | 1        | 1      | 0.5%    |
| Hewlett-Packard       | 1        | 3      | 0.5%    |
| DGM                   | 1        | 1      | 0.5%    |
| A-DATA Technology     | 1        | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB   | 6        | 2.58%   |
| Kingston SUV400S37120G 120GB SSD | 5        | 2.15%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 1.72%   |
| WDC WD10EZEX-00WN4A0 1TB         | 4        | 1.72%   |
| Seagate ST500DM002-1BD142 500GB  | 4        | 1.72%   |
| Seagate ST1000DM003-1ER162 1TB   | 4        | 1.72%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 3        | 1.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 3        | 1.29%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 1.29%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.29%   |
| Seagate ST3500418AS 500GB        | 3        | 1.29%   |
| Seagate ST2000VX008-2E3164 2TB   | 3        | 1.29%   |
| SanDisk SDSSDA120G 120GB         | 3        | 1.29%   |
| Samsung NVMe SSD Drive 250GB     | 3        | 1.29%   |
| Samsung HD103SJ 1TB              | 3        | 1.29%   |
| Phison NVMe SSD Drive 240GB      | 3        | 1.29%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.29%   |
| WDC WDS250G3X0C-00SJG0 250GB     | 2        | 0.86%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 2        | 0.86%   |
| WDC WD5000AAKX-001CA0 500GB      | 2        | 0.86%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 2        | 0.86%   |
| WDC WD10EZEX-21WN4A0 1TB         | 2        | 0.86%   |
| WDC WD10EFRX-68FYTN0 1TB         | 2        | 0.86%   |
| Unknown SD/MMC/MS PRO 128GB      | 2        | 0.86%   |
| Seagate ST500DM002-1BD14 500GB   | 2        | 0.86%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 0.86%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 0.86%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 0.86%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 0.86%   |
| Sandisk NVMe SSD Drive 500GB     | 2        | 0.86%   |
| Sandisk NVMe SSD Drive 250GB     | 2        | 0.86%   |
| Samsung SSD 850 120GB            | 2        | 0.86%   |
| Samsung SSD 830 Series 128GB     | 2        | 0.86%   |
| Samsung HD753LJ 752GB            | 2        | 0.86%   |
| Samsung HD502IJ 500GB            | 2        | 0.86%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.86%   |
| Intel SSDSC2CT060A3 64GB         | 2        | 0.86%   |
| HS-SSD-C100 240G                 | 2        | 0.86%   |
| External USB3.0 1TB              | 2        | 0.86%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 0.86%   |
| WDC WDS500G2X0C-00L350 500GB     | 1        | 0.43%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.43%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD | 1        | 0.43%   |
| WDC WDS120G1G0A-00SS50 120GB SSD | 1        | 0.43%   |
| WDC WD6400AAKS-65A7B2 640GB      | 1        | 0.43%   |
| WDC WD5003ABYX-01WERA1 500GB     | 1        | 0.43%   |
| WDC WD5000LPCX-21VHAT0 500GB     | 1        | 0.43%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 0.43%   |
| WDC WD5000AAKX-221CA1 500GB      | 1        | 0.43%   |
| WDC WD5000AAKS-00A7B0 500GB      | 1        | 0.43%   |
| WDC WD5000AADS-00S9B0 500GB      | 1        | 0.43%   |
| WDC WD40PURZ-85TTDY0 4TB         | 1        | 0.43%   |
| WDC WD40PURZ-85AKKY0 4TB         | 1        | 0.43%   |
| WDC WD40PURX-64NZ6Y0 4TB         | 1        | 0.43%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1        | 0.43%   |
| WDC WD3200AAKS-00B3A0 320GB      | 1        | 0.43%   |
| WDC WD3200AAJS-22B4A0 320GB      | 1        | 0.43%   |
| WDC WD30EFRX-68EUZN0 3TB         | 1        | 0.43%   |
| WDC WD2500JS-00MHB0 250GB        | 1        | 0.43%   |
| WDC WD20PURX-64P6ZY0 2TB         | 1        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 41       | 66     | 39.42%  |
| WDC                 | 37       | 57     | 35.58%  |
| Samsung Electronics | 7        | 12     | 6.73%   |
| Toshiba             | 6        | 8      | 5.77%   |
| Hitachi             | 6        | 6      | 5.77%   |
| Unknown             | 3        | 8      | 2.88%   |
| HGST                | 2        | 5      | 1.92%   |
| JMicron             | 1        | 1      | 0.96%   |
| Hewlett-Packard     | 1        | 3      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 17     | 18.31%  |
| Kingston            | 11       | 11     | 15.49%  |
| Samsung Electronics | 8        | 11     | 11.27%  |
| Crucial             | 6        | 6      | 8.45%   |
| SanDisk             | 4        | 5      | 5.63%   |
| KingSpec            | 3        | 5      | 4.23%   |
| Intel               | 3        | 3      | 4.23%   |
| Hikvision           | 3        | 3      | 4.23%   |
| GALAX               | 3        | 3      | 4.23%   |
| External            | 2        | 2      | 2.82%   |
| Apacer              | 2        | 2      | 2.82%   |
| Verbatim            | 1        | 1      | 1.41%   |
| USB3.0              | 1        | 1      | 1.41%   |
| TO Exter            | 1        | 1      | 1.41%   |
| SPCC                | 1        | 1      | 1.41%   |
| SK Hynix            | 1        | 2      | 1.41%   |
| PLEXTOR             | 1        | 1      | 1.41%   |
| Pioneer             | 1        | 1      | 1.41%   |
| OCZ                 | 1        | 1      | 1.41%   |
| JMicron             | 1        | 1      | 1.41%   |
| DGM                 | 1        | 1      | 1.41%   |
| Corsair             | 1        | 1      | 1.41%   |
| Colorful            | 1        | 2      | 1.41%   |
| A-DATA Technology   | 1        | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 82       | 166    | 49.7%   |
| SSD     | 57       | 83     | 34.55%  |
| NVMe    | 20       | 39     | 12.12%  |
| Unknown | 6        | 10     | 3.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 107      | 242    | 76.98%  |
| NVMe | 20       | 39     | 14.39%  |
| SAS  | 12       | 17     | 8.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 82       | 128    | 51.9%   |
| 0.51-1.0   | 49       | 69     | 31.01%  |
| 1.01-2.0   | 19       | 23     | 12.03%  |
| 3.01-4.0   | 5        | 11     | 3.16%   |
| 2.01-3.0   | 1        | 3      | 0.63%   |
| 10.01-20.0 | 1        | 6      | 0.63%   |
| 4.01-10.0  | 1        | 9      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 34       | 28.33%  |
| 501-1000       | 17       | 14.17%  |
| 251-500        | 16       | 13.33%  |
| 1-20           | 14       | 11.67%  |
| 2001-3000      | 8        | 6.67%   |
| 1001-2000      | 8        | 6.67%   |
| More than 3000 | 7        | 5.83%   |
| 21-50          | 6        | 5%      |
| 51-100         | 6        | 5%      |
| Unknown        | 4        | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 48       | 38.1%   |
| 21-50          | 21       | 16.67%  |
| 101-250        | 13       | 10.32%  |
| 51-100         | 11       | 8.73%   |
| 501-1000       | 10       | 7.94%   |
| 251-500        | 6        | 4.76%   |
| 1001-2000      | 6        | 4.76%   |
| More than 3000 | 5        | 3.97%   |
| Unknown        | 4        | 3.17%   |
| 2001-3000      | 2        | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD14 500GB           | 2        | 2      | 20%     |
| WDC WD20EARS-00MVWB0 2TB                 | 1        | 1      | 10%     |
| Toshiba HDWL110 1TB                      | 1        | 1      | 10%     |
| Seagate ST9120822AS 120GB                | 1        | 1      | 10%     |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 10%     |
| Seagate ST3500418AS 500GB                | 1        | 2      | 10%     |
| Seagate ST1000LM014-1EJ164 1TB           | 1        | 1      | 10%     |
| Samsung Electronics SSD 830 Series 128GB | 1        | 1      | 10%     |
| Samsung Electronics HD103SJ 1TB          | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 60%     |
| Samsung Electronics | 2        | 2      | 20%     |
| WDC                 | 1        | 1      | 10%     |
| Toshiba             | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 66.67%  |
| WDC                 | 1        | 1      | 11.11%  |
| Toshiba             | 1        | 1      | 11.11%  |
| Samsung Electronics | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 10     | 88.89%  |
| SSD  | 1        | 1      | 11.11%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 91       | 211    | 71.65%  |
| Works    | 27       | 75     | 21.26%  |
| Malfunc  | 8        | 11     | 6.3%    |
| Failed   | 1        | 1      | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 76       | 51.01%  |
| AMD                         | 32       | 21.48%  |
| ASMedia Technology          | 7        | 4.7%    |
| Sandisk                     | 6        | 4.03%   |
| Samsung Electronics         | 6        | 4.03%   |
| Nvidia                      | 6        | 4.03%   |
| Phison Electronics          | 5        | 3.36%   |
| VIA Technologies            | 2        | 1.34%   |
| Silicon Motion              | 2        | 1.34%   |
| Kingston Technology Company | 2        | 1.34%   |
| SK Hynix                    | 1        | 0.67%   |
| Realtek Semiconductor       | 1        | 0.67%   |
| LSI Logic / Symbios Logic   | 1        | 0.67%   |
| JMicron Technology          | 1        | 0.67%   |
| Broadcom / LSI              | 1        | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 19       | 10%     |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 5.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 4.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 4.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 3.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 3.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 3.68%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 3.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 3.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 2.63%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 2.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.63%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 2.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 2.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 2.11%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 1.58%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.58%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.58%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.58%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.58%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.05%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.05%   |
| Nvidia MCP73 IDE Controller                                                             | 2        | 1.05%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.05%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.05%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.05%   |
| AMD FCH IDE Controller                                                                  | 2        | 1.05%   |
| VIA VX900 Series Serial-ATA Controller                                                  | 1        | 0.53%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.53%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.53%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.53%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.53%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.53%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.53%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.53%   |
| Nvidia MCP73 SATA RAID Controller                                                       | 1        | 0.53%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.53%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.53%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.53%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.53%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.53%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.53%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.53%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 1        | 0.53%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 0.53%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 0.53%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 0.53%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.53%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                     | 1        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 89       | 58.17%  |
| IDE  | 34       | 22.22%  |
| NVMe | 21       | 13.73%  |
| RAID | 7        | 4.58%   |
| SAS  | 1        | 0.65%   |
| SCSI | 1        | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 78       | 67.83%  |
| AMD          | 36       | 31.3%   |
| CentaurHauls | 1        | 0.87%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 3.42%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 3.42%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 2.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 2.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.71%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 1.71%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.71%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.71%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.71%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.71%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.71%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.71%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.71%   |
| AMD Phenom II X6 1055T Processor            | 2        | 1.71%   |
| Intel Xeon W-2145 CPU @ 3.70GHz             | 1        | 0.85%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 0.85%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.85%   |
| Intel Xeon CPU E5-2698 v4 @ 2.20GHz         | 1        | 0.85%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz          | 1        | 0.85%   |
| Intel Xeon CPU E5-2640 v2 @ 2.00GHz         | 1        | 0.85%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 1        | 0.85%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.85%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 0.85%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.85%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.85%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 0.85%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1        | 0.85%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1        | 0.85%   |
| Intel Pentium CPU G4600 @ 3.60GHz           | 1        | 0.85%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.85%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.85%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.85%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.85%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.85%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 0.85%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.85%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 1        | 0.85%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.85%   |
| Intel Core i5-8600 CPU @ 3.10GHz            | 1        | 0.85%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1        | 0.85%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.85%   |
| Intel Core i5-6600T CPU @ 2.70GHz           | 1        | 0.85%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1        | 0.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 0.85%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1        | 0.85%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 0.85%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 0.85%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 0.85%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 0.85%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 0.85%   |
| Intel Core i3-2130 CPU @ 3.40GHz            | 1        | 0.85%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1        | 0.85%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 0.85%   |
| Intel Core i3 CPU 560 @ 3.33GHz             | 1        | 0.85%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 0.85%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1        | 0.85%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz       | 1        | 0.85%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 1        | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 19.83%  |
| Intel Core i3           | 17       | 14.66%  |
| Intel Core i7           | 12       | 10.34%  |
| Intel Xeon              | 7        | 6.03%   |
| AMD Ryzen 5             | 6        | 5.17%   |
| AMD Ryzen 7             | 5        | 4.31%   |
| Intel Pentium           | 4        | 3.45%   |
| Intel Core 2 Quad       | 4        | 3.45%   |
| AMD Ryzen 3             | 4        | 3.45%   |
| AMD FX                  | 4        | 3.45%   |
| AMD Athlon II X2        | 4        | 3.45%   |
| Intel Pentium Dual-Core | 3        | 2.59%   |
| Intel Core 2 Duo        | 2        | 1.72%   |
| Intel Celeron           | 2        | 1.72%   |
| AMD Phenom II X6        | 2        | 1.72%   |
| AMD Phenom II X4        | 2        | 1.72%   |
| AMD Athlon 64 X2        | 2        | 1.72%   |
| AMD A6                  | 2        | 1.72%   |
| AMD A4                  | 2        | 1.72%   |
| AMD A10                 | 2        | 1.72%   |
| Intel Pentium Dual      | 1        | 0.86%   |
| Intel Pentium 4         | 1        | 0.86%   |
| Intel Core i9           | 1        | 0.86%   |
| Intel Atom              | 1        | 0.86%   |
| CentaurHauls VIA Eden   | 1        | 0.86%   |
| AMD Ryzen 9             | 1        | 0.86%   |
| AMD Phenom II X3        | 1        | 0.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 42       | 36.21%  |
| 2      | 38       | 32.76%  |
| 6      | 17       | 14.66%  |
| 8      | 12       | 10.34%  |
| 1      | 3        | 2.59%   |
| 12     | 2        | 1.72%   |
| 40     | 1        | 0.86%   |
| 3      | 1        | 0.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 112      | 97.39%  |
| 2      | 3        | 2.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 60       | 51.72%  |
| 1      | 56       | 48.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 115      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 21.49%  |
| 0x306c3    | 8        | 6.61%   |
| 0x206a7    | 8        | 6.61%   |
| 0x506e3    | 7        | 5.79%   |
| 0x906ea    | 6        | 4.96%   |
| 0x906e9    | 6        | 4.96%   |
| 0x1067a    | 6        | 4.96%   |
| 0x306a9    | 4        | 3.31%   |
| 0x0800820d | 4        | 3.31%   |
| 0xa0655    | 3        | 2.48%   |
| 0x20655    | 3        | 2.48%   |
| 0x010000c8 | 3        | 2.48%   |
| 0x906ec    | 2        | 1.65%   |
| 0x08001138 | 2        | 1.65%   |
| 0x06003106 | 2        | 1.65%   |
| 0x06001119 | 2        | 1.65%   |
| 0x06000852 | 2        | 1.65%   |
| 0xf49      | 1        | 0.83%   |
| 0xa0653    | 1        | 0.83%   |
| 0x906ed    | 1        | 0.83%   |
| 0x6fd      | 1        | 0.83%   |
| 0x6fb      | 1        | 0.83%   |
| 0x50654    | 1        | 0.83%   |
| 0x406f1    | 1        | 0.83%   |
| 0x406c3    | 1        | 0.83%   |
| 0x306e4    | 1        | 0.83%   |
| 0x30678    | 1        | 0.83%   |
| 0x206c2    | 1        | 0.83%   |
| 0x106e5    | 1        | 0.83%   |
| 0x106ca    | 1        | 0.83%   |
| 0x10677    | 1        | 0.83%   |
| 0x10676    | 1        | 0.83%   |
| 0x08701021 | 1        | 0.83%   |
| 0x08600106 | 1        | 0.83%   |
| 0x08108109 | 1        | 0.83%   |
| 0x08101016 | 1        | 0.83%   |
| 0x0810100b | 1        | 0.83%   |
| 0x0800820b | 1        | 0.83%   |
| 0x06006704 | 1        | 0.83%   |
| 0x0600611a | 1        | 0.83%   |
| 0x06000822 | 1        | 0.83%   |
| 0x03000027 | 1        | 0.83%   |
| 0x010000db | 1        | 0.83%   |
| 0x010000b6 | 1        | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 16       | 13.79%  |
| Skylake     | 10       | 8.62%   |
| SandyBridge | 10       | 8.62%   |
| Penryn      | 9        | 7.76%   |
| Haswell     | 9        | 7.76%   |
| K10         | 8        | 6.9%    |
| IvyBridge   | 7        | 6.03%   |
| Zen+        | 6        | 5.17%   |
| Zen 2       | 5        | 4.31%   |
| Piledriver  | 5        | 4.31%   |
| CometLake   | 5        | 4.31%   |
| Zen         | 4        | 3.45%   |
| Westmere    | 4        | 3.45%   |
| Silvermont  | 3        | 2.59%   |
| Steamroller | 2        | 1.72%   |
| K8 Hammer   | 2        | 1.72%   |
| Excavator   | 2        | 1.72%   |
| Core        | 2        | 1.72%   |
| Zen 3       | 1        | 0.86%   |
| NetBurst    | 1        | 0.86%   |
| Nehalem     | 1        | 0.86%   |
| K10 Llano   | 1        | 0.86%   |
| Broadwell   | 1        | 0.86%   |
| Bonnell     | 1        | 0.86%   |
| Unknown     | 1        | 0.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 55       | 44%     |
| AMD              | 35       | 28%     |
| Intel            | 34       | 27.2%   |
| VIA Technologies | 1        | 0.8%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7        | 5.43%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 3.88%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 3.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5        | 3.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 3.88%   |
| Intel HD Graphics 530                                                                    | 4        | 3.1%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 3.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 2.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3        | 2.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3        | 2.33%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 2.33%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 1.55%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.55%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 1.55%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 1.55%   |
| Intel HD Graphics 630                                                                    | 2        | 1.55%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.55%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 1.55%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.55%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 1.55%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.55%   |
| AMD Juniper PRO [Radeon HD 6750]                                                         | 2        | 1.55%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 2        | 1.55%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 1.55%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                             | 1        | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1        | 0.78%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1        | 0.78%   |
| Nvidia NV43 [GeForce 6600]                                                               | 1        | 0.78%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.78%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.78%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.78%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 0.78%   |
| Nvidia GT200GL [Quadro FX 4800]                                                          | 1        | 0.78%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 1        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1        | 0.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.78%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.78%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1        | 0.78%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1        | 0.78%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 1        | 0.78%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1        | 0.78%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.78%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 1        | 0.78%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.78%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 0.78%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 0.78%   |
| Nvidia GF108 [GeForce GT 420]                                                            | 1        | 0.78%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1        | 0.78%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1        | 0.78%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1        | 0.78%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1        | 0.78%   |
| Nvidia G94 [GeForce 9600 GSO 512]                                                        | 1        | 0.78%   |
| Nvidia G72 [GeForce 7300 GS]                                                             | 1        | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 0.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 0.78%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| 1 x Nvidia       | 49       | 40.5%   |
| 1 x Intel        | 32       | 26.45%  |
| 1 x AMD          | 31       | 25.62%  |
| AMD + Nvidia     | 4        | 3.31%   |
| 3 x Nvidia       | 1        | 0.83%   |
| 2 x AMD          | 1        | 0.83%   |
| 1 x VIA          | 1        | 0.83%   |
| Intel + Nvidia   | 1        | 0.83%   |
| AMD + 2 x Nvidia | 1        | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 90       | 76.27%  |
| Proprietary | 22       | 18.64%  |
| Unknown     | 6        | 5.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 41.8%   |
| 1.01-2.0   | 20       | 16.39%  |
| 0.51-1.0   | 14       | 11.48%  |
| 0.01-0.5   | 12       | 9.84%   |
| 3.01-4.0   | 10       | 8.2%    |
| 7.01-8.0   | 8        | 6.56%   |
| 5.01-6.0   | 4        | 3.28%   |
| 4.01-5.0   | 1        | 0.82%   |
| 2.01-3.0   | 1        | 0.82%   |
| 16.01-24.0 | 1        | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 28       | 23.33%  |
| Goldstar             | 19       | 15.83%  |
| Acer                 | 19       | 15.83%  |
| AOC                  | 9        | 7.5%    |
| Hewlett-Packard      | 8        | 6.67%   |
| Dell                 | 7        | 5.83%   |
| BenQ                 | 5        | 4.17%   |
| LG Electronics       | 4        | 3.33%   |
| MStar                | 2        | 1.67%   |
| Lenovo               | 2        | 1.67%   |
| Ancor Communications | 2        | 1.67%   |
| ViewSonic            | 1        | 0.83%   |
| Unknown (XXX)        | 1        | 0.83%   |
| Toshiba              | 1        | 0.83%   |
| Sharp                | 1        | 0.83%   |
| SGT                  | 1        | 0.83%   |
| MIG                  | 1        | 0.83%   |
| Microstep            | 1        | 0.83%   |
| ITE                  | 1        | 0.83%   |
| HUYINIUDA            | 1        | 0.83%   |
| HPN                  | 1        | 0.83%   |
| Gateway              | 1        | 0.83%   |
| Fujitsu              | 1        | 0.83%   |
| CHI                  | 1        | 0.83%   |
| ASUSTek Computer     | 1        | 0.83%   |
| Apple                | 1        | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch    | 2        | 1.56%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch        | 2        | 1.56%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 2        | 1.56%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 2        | 1.56%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                        | 2        | 1.56%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                      | 2        | 1.56%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 2        | 1.56%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2        | 1.56%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 2        | 1.56%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                        | 2        | 1.56%   |
| Acer X193HQ ACR0067 1366x768 410x230mm 18.5-inch                        | 2        | 1.56%   |
| Acer S200HQL ACR0359 1600x900 434x236mm 19.4-inch                       | 2        | 1.56%   |
| Acer P191W ACR000C 1440x900 410x256mm 19.0-inch                         | 2        | 1.56%   |
| Acer K242HQL ACR042E 1920x1080 521x293mm 23.5-inch                      | 2        | 1.56%   |
| ViewSonic VG1655 VSCD239 1920x1080 344x194mm 15.5-inch                  | 1        | 0.78%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch              | 1        | 0.78%   |
| Toshiba TV TSB0114 1920x1080 882x498mm 39.9-inch                        | 1        | 0.78%   |
| Sharp HDMI SHP113E 1920x1080 1330x748mm 60.1-inch                       | 1        | 0.78%   |
| SGT Split SGT0156 1920x1080 346x194mm 15.6-inch                         | 1        | 0.78%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch    | 1        | 0.78%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch     | 1        | 0.78%   |
| Samsung Electronics SyncMaster SAM044F 1440x900 408x255mm 18.9-inch     | 1        | 0.78%   |
| Samsung Electronics SyncMaster SAM03BA 1680x1050                        | 1        | 0.78%   |
| Samsung Electronics SyncMaster SAM0366 1280x1024 338x270mm 17.0-inch    | 1        | 0.78%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch       | 1        | 0.78%   |
| Samsung Electronics SA300/SA350 SAM0790 1920x1080 510x287mm 23.0-inch   | 1        | 0.78%   |
| Samsung Electronics S27F350 SAM0D23 1920x1080 598x336mm 27.0-inch       | 1        | 0.78%   |
| Samsung Electronics S27D590 SAM0BE9 1920x1080 598x336mm 27.0-inch       | 1        | 0.78%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1        | 0.78%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.78%   |
| Samsung Electronics S23B370 SAM089B 1920x1080 510x290mm 23.1-inch       | 1        | 0.78%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 0.78%   |
| Samsung Electronics S22B370 SAM0898 1920x1080 477x268mm 21.5-inch       | 1        | 0.78%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch        | 1        | 0.78%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch        | 1        | 0.78%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch        | 1        | 0.78%   |
| Samsung Electronics LCD Monitor T27B350                                 | 1        | 0.78%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 1        | 0.78%   |
| Samsung Electronics LCD Monitor SME1920                                 | 1        | 0.78%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 0.78%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 700x390mm 31.5-inch   | 1        | 0.78%   |
| Samsung Electronics LCD Monitor S23B370 3840x1080                       | 1        | 0.78%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 0.78%   |
| MIG mllgo 240 MIG2380 1920x1080 520x310mm 23.8-inch                     | 1        | 0.78%   |
| Microstep LCD Monitor Optix G241VC 1920x1080                            | 1        | 0.78%   |
| LG Electronics LCD Monitor LG TV 3840x1080                              | 1        | 0.78%   |
| LG Electronics LCD Monitor LG TV 1280x720                               | 1        | 0.78%   |
| Lenovo LCD Monitor LEN0BD0 1920x1080 510x290mm 23.1-inch                | 1        | 0.78%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                    | 1        | 0.78%   |
| ITE DP2VGA V207 ITE6516 1366x768 600x340mm 27.2-inch                    | 1        | 0.78%   |
| HUYINIUDA HUYINIUDA HUY1850 1366x768 410x220mm 18.3-inch                | 1        | 0.78%   |
| HPN LCD Monitor HP 24f 1920x1080                                        | 1        | 0.78%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch           | 1        | 0.78%   |
| Hewlett-Packard x20LED HWP290F 1600x900 443x249mm 20.0-inch             | 1        | 0.78%   |
| Hewlett-Packard LE2002x HWP2964 1600x900 443x249mm 20.0-inch            | 1        | 0.78%   |
| Hewlett-Packard LCD Monitor w17e 1440x900                               | 1        | 0.78%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch             | 1        | 0.78%   |
| Hewlett-Packard Compaq W185q HWP284F 1366x768 410x230mm 18.5-inch       | 1        | 0.78%   |
| Hewlett-Packard All-in-One HWP4243 1600x900 434x236mm 19.4-inch         | 1        | 0.78%   |
| Hewlett-Packard 24f HPN3545 1920x1080 530x300mm 24.0-inch               | 1        | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 55       | 45.83%  |
| 1366x768 (WXGA)    | 11       | 9.17%   |
| 1600x900 (HD+)     | 9        | 7.5%    |
| 3840x2160 (4K)     | 8        | 6.67%   |
| 1680x1050 (WSXGA+) | 8        | 6.67%   |
| 1440x900 (WXGA+)   | 6        | 5%      |
| 1280x1024 (SXGA)   | 5        | 4.17%   |
| Unknown            | 4        | 3.33%   |
| 2560x1440 (QHD)    | 3        | 2.5%    |
| 2560x1080          | 3        | 2.5%    |
| 3840x1080          | 2        | 1.67%   |
| 3440x1440          | 1        | 0.83%   |
| 2732x768           | 1        | 0.83%   |
| 2560x1600          | 1        | 0.83%   |
| 1600x1200          | 1        | 0.83%   |
| 1360x768           | 1        | 0.83%   |
| 1280x720 (HD)      | 1        | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 22       | 18.33%  |
| Unknown | 14       | 11.67%  |
| 19      | 12       | 10%     |
| 21      | 11       | 9.17%   |
| 27      | 10       | 8.33%   |
| 24      | 10       | 8.33%   |
| 18      | 10       | 8.33%   |
| 20      | 8        | 6.67%   |
| 22      | 6        | 5%      |
| 34      | 4        | 3.33%   |
| 15      | 3        | 2.5%    |
| 52      | 2        | 1.67%   |
| 17      | 2        | 1.67%   |
| 84      | 1        | 0.83%   |
| 60      | 1        | 0.83%   |
| 47      | 1        | 0.83%   |
| 39      | 1        | 0.83%   |
| 29      | 1        | 0.83%   |
| 16      | 1        | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 45       | 38.14%  |
| 501-600     | 40       | 33.9%   |
| Unknown     | 14       | 11.86%  |
| 301-350     | 6        | 5.08%   |
| 701-800     | 4        | 3.39%   |
| 1001-1500   | 4        | 3.39%   |
| 351-400     | 2        | 1.69%   |
| 801-900     | 1        | 0.85%   |
| 601-700     | 1        | 0.85%   |
| 1501-2000   | 1        | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 76       | 66.09%  |
| 16/10   | 16       | 13.91%  |
| Unknown | 13       | 11.3%   |
| 5/4     | 5        | 4.35%   |
| 21/9    | 4        | 3.48%   |
| 4/3     | 1        | 0.87%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 43       | 36.13%  |
| 151-200        | 23       | 19.33%  |
| Unknown        | 14       | 11.76%  |
| 301-350        | 10       | 8.4%    |
| 141-150        | 10       | 8.4%    |
| 351-500        | 5        | 4.2%    |
| More than 1000 | 4        | 3.36%   |
| 251-300        | 3        | 2.52%   |
| 101-110        | 3        | 2.52%   |
| 501-1000       | 2        | 1.68%   |
| 131-140        | 1        | 0.84%   |
| 121-130        | 1        | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 69       | 62.73%  |
| 101-120 | 17       | 15.45%  |
| Unknown | 14       | 12.73%  |
| 1-50    | 4        | 3.64%   |
| 161-240 | 4        | 3.64%   |
| 121-160 | 2        | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 92       | 76.67%  |
| 2     | 18       | 15%     |
| 0     | 8        | 6.67%   |
| 3     | 2        | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 76       | 46.91%  |
| Intel                           | 34       | 20.99%  |
| Qualcomm Atheros                | 13       | 8.02%   |
| Ralink Technology               | 9        | 5.56%   |
| D-Link                          | 6        | 3.7%    |
| Nvidia                          | 5        | 3.09%   |
| Broadcom                        | 3        | 1.85%   |
| TP-Link                         | 2        | 1.23%   |
| Ralink                          | 2        | 1.23%   |
| D-Link System                   | 2        | 1.23%   |
| Xiaomi                          | 1        | 0.62%   |
| VIA Technologies                | 1        | 0.62%   |
| Samsung Electronics             | 1        | 0.62%   |
| Qualcomm Atheros Communications | 1        | 0.62%   |
| Mercucys                        | 1        | 0.62%   |
| MEDIATEK                        | 1        | 0.62%   |
| Huawei Technologies             | 1        | 0.62%   |
| Edimax Technology               | 1        | 0.62%   |
| BUFFALO                         | 1        | 0.62%   |
| ASUSTek Computer                | 1        | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 65       | 36.11%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                                   | 5        | 2.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 4        | 2.22%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 2.22%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 2.22%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 1.67%   |
| Nvidia MCP61 Ethernet                                                  | 3        | 1.67%   |
| Intel Ethernet Connection I217-V                                       | 3        | 1.67%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 1.67%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 1.67%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]          | 3        | 1.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 1.11%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 1.11%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 1.11%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 1.11%   |
| Ralink RT2501/RT2573 Wireless Adapter                                  | 2        | 1.11%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                      | 2        | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2        | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 1.11%   |
| Nvidia MCP73 Ethernet                                                  | 2        | 1.11%   |
| Intel Wireless-AC 9260                                                 | 2        | 1.11%   |
| Intel Ethernet Connection (12) I219-V                                  | 2        | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 1.11%   |
| Xiaomi 100Mbps Network Card Adapter                                    | 1        | 0.56%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                      | 1        | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 0.56%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                             | 1        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.56%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1        | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.56%   |
| Realtek 802.11ac NIC                                                   | 1        | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 0.56%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                   | 1        | 0.56%   |
| Ralink RT2561/RT61 rev B 802.11g                                       | 1        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.56%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 0.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 0.56%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 0.56%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]    | 1        | 0.56%   |
| Mercucys 802.11n NIC                                                   | 1        | 0.56%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter          | 1        | 0.56%   |
| Intel Wireless 3165                                                    | 1        | 0.56%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 0.56%   |
| Intel I210 Gigabit Unprogrammed                                        | 1        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 0.56%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 0.56%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                 | 1        | 0.56%   |
| Huawei Broadband stick                                                 | 1        | 0.56%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 1        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 16       | 26.67%  |
| Qualcomm Atheros                | 10       | 16.67%  |
| Ralink Technology               | 9        | 15%     |
| Intel                           | 8        | 13.33%  |
| D-Link                          | 6        | 10%     |
| TP-Link                         | 2        | 3.33%   |
| Ralink                          | 2        | 3.33%   |
| Qualcomm Atheros Communications | 1        | 1.67%   |
| Mercucys                        | 1        | 1.67%   |
| MEDIATEK                        | 1        | 1.67%   |
| Edimax Technology               | 1        | 1.67%   |
| D-Link System                   | 1        | 1.67%   |
| BUFFALO                         | 1        | 1.67%   |
| ASUSTek Computer                | 1        | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                        | Desktops | Percent |
|------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                          | 5        | 8.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                              | 4        | 6.67%   |
| Ralink MT7601U Wireless Adapter                                              | 4        | 6.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                              | 3        | 5%      |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                | 3        | 5%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                           | 2        | 3.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                              | 2        | 3.33%   |
| Ralink RT2501/RT2573 Wireless Adapter                                        | 2        | 3.33%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                            | 2        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                   | 2        | 3.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)               | 2        | 3.33%   |
| Intel Wireless-AC 9260                                                       | 2        | 3.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                 | 1        | 1.67%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                   | 1        | 1.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                       | 1        | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                                   | 1        | 1.67%   |
| Realtek 802.11ac NIC                                                         | 1        | 1.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                        | 1        | 1.67%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                         | 1        | 1.67%   |
| Ralink RT2561/RT61 rev B 802.11g                                             | 1        | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                                              | 1        | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 1        | 1.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                             | 1        | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)               | 1        | 1.67%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                             | 1        | 1.67%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]       | 1        | 1.67%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]          | 1        | 1.67%   |
| Mercucys 802.11n NIC                                                         | 1        | 1.67%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                | 1        | 1.67%   |
| Intel Wireless 3165                                                          | 1        | 1.67%   |
| Intel Wi-Fi 6 AX200                                                          | 1        | 1.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                             | 1        | 1.67%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]               | 1        | 1.67%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]         | 1        | 1.67%   |
| D-Link DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.B2) [Ralink RT5572] | 1        | 1.67%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                               | 1        | 1.67%   |
| D-Link 802.11 n WLAN                                                         | 1        | 1.67%   |
| BUFFALO Sony UWA-BR100 802.11abgn Wireless Adapter [Atheros AR7010+AR9280]   | 1        | 1.67%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]              | 1        | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 71       | 61.21%  |
| Intel                 | 29       | 25%     |
| Nvidia                | 5        | 4.31%   |
| Qualcomm Atheros      | 4        | 3.45%   |
| Broadcom              | 3        | 2.59%   |
| Xiaomi                | 1        | 0.86%   |
| VIA Technologies      | 1        | 0.86%   |
| Samsung Electronics   | 1        | 0.86%   |
| D-Link System         | 1        | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65       | 54.62%  |
| Intel Ethernet Connection (2) I219-V                              | 5        | 4.2%    |
| Intel I211 Gigabit Network Connection                             | 4        | 3.36%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 3.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.52%   |
| Nvidia MCP61 Ethernet                                             | 3        | 2.52%   |
| Intel Ethernet Connection I217-V                                  | 3        | 2.52%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.52%   |
| Intel Ethernet Connection (5) I219-LM                             | 3        | 2.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.68%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1.68%   |
| Nvidia MCP73 Ethernet                                             | 2        | 1.68%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.68%   |
| Xiaomi 100Mbps Network Card Adapter                               | 1        | 0.84%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.84%   |
| Intel I210 Gigabit Unprogrammed                                   | 1        | 0.84%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.84%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.84%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.84%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.84%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 0.84%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.84%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 64.91%  |
| WiFi     | 59       | 34.5%   |
| Modem    | 1        | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 86       | 64.18%  |
| WiFi     | 48       | 35.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 76       | 65.52%  |
| 2     | 34       | 29.31%  |
| 0     | 4        | 3.45%   |
| 4     | 1        | 0.86%   |
| 3     | 1        | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 98       | 81.67%  |
| Yes  | 22       | 18.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 17       | 54.84%  |
| Intel                           | 8        | 25.81%  |
| ASUSTek Computer                | 2        | 6.45%   |
| Qualcomm Atheros Communications | 1        | 3.23%   |
| MediaTek                        | 1        | 3.23%   |
| Lite-On Technology              | 1        | 3.23%   |
| Apple                           | 1        | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17       | 54.84%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 9.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 6.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 3.23%   |
| MediaTek Wireless_Device                            | 1        | 3.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.23%   |
| Intel Bluetooth wireless interface                  | 1        | 3.23%   |
| Intel AX200 Bluetooth                               | 1        | 3.23%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 3.23%   |
| ASUS Bluetooth Device                               | 1        | 3.23%   |
| Apple Bluetooth HCI                                 | 1        | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 77       | 38.89%  |
| Nvidia                      | 51       | 25.76%  |
| AMD                         | 46       | 23.23%  |
| C-Media Electronics         | 9        | 4.55%   |
| SAVITECH                    | 2        | 1.01%   |
| JMTek                       | 2        | 1.01%   |
| Elan Microelectronics       | 2        | 1.01%   |
| VIA Technologies            | 1        | 0.51%   |
| Razer USA                   | 1        | 0.51%   |
| Nordic Semiconductor ASA    | 1        | 0.51%   |
| Kingston Technology         | 1        | 0.51%   |
| Generalplus Technology      | 1        | 0.51%   |
| ESS Technology              | 1        | 0.51%   |
| Earth Computer Technologies | 1        | 0.51%   |
| Creative Labs               | 1        | 0.51%   |
| Blue Microphones            | 1        | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 200 Series PCH HD Audio                                                                     | 10       | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9        | 3.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9        | 3.88%   |
| Nvidia High Definition Audio Controller                                                           | 8        | 3.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8        | 3.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8        | 3.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7        | 3.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7        | 3.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 3.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7        | 3.02%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6        | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6        | 2.59%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 5        | 2.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 2.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5        | 2.16%   |
| AMD FCH Azalia Controller                                                                         | 5        | 2.16%   |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 1.72%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4        | 1.72%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4        | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4        | 1.72%   |
| C-Media Electronics Redragon Gaming Headset                                                       | 4        | 1.72%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 1.72%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4        | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3        | 1.29%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3        | 1.29%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3        | 1.29%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.29%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3        | 1.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 1.29%   |
| AMD Navi 10 HDMI Audio                                                                            | 3        | 1.29%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 3        | 1.29%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3        | 1.29%   |
| SAVITECH SA9023 audio controller                                                                  | 2        | 0.86%   |
| Nvidia MCP73 High Definition Audio                                                                | 2        | 0.86%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2        | 0.86%   |
| Elan Microelectronics USB Audio                                                                   | 2        | 0.86%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2        | 0.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 0.86%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2        | 0.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2        | 0.86%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1        | 0.43%   |
| VIA Technologies High Definition Audio Controller                                                 | 1        | 0.43%   |
| Razer USA Razer Kraken X USB                                                                      | 1        | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1        | 0.43%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 0.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 0.43%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 0.43%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1        | 0.43%   |
| Nordic Semiconductor ASA ZY Control Mic                                                           | 1        | 0.43%   |
| Kingston Technology HyperX Cloud II Wireless                                                      | 1        | 0.43%   |
| JMTek USB PnP Audio Device(EEPROM)                                                                | 1        | 0.43%   |
| JMTek USB PnP Audio Device                                                                        | 1        | 0.43%   |
| Intel USB PnP Sound Device                                                                        | 1        | 0.43%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.43%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 0.43%   |
| Intel Audio device                                                                                | 1        | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 19       | 43.18%  |
| Unknown             | 9        | 20.45%  |
| SK Hynix            | 6        | 13.64%  |
| Corsair             | 5        | 11.36%  |
| Samsung Electronics | 2        | 4.55%   |
| Unknown (0x02BA)    | 1        | 2.27%   |
| Transcend           | 1        | 2.27%   |
| A-DATA Technology   | 1        | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s      | 4        | 8.16%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 3        | 6.12%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 2        | 4.08%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s      | 2        | 4.08%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s       | 2        | 4.08%   |
| Kingston RAM KP223C-ELD 2048MB DIMM DDR3 1600MT/s         | 2        | 4.08%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 2        | 4.08%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s       | 2        | 4.08%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 1        | 2.04%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 2.04%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 2.04%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s               | 1        | 2.04%   |
| Unknown (0x02BA) RAM Module 2048MB FB-DIMM DDR2 800MT/s   | 1        | 2.04%   |
| Transcend RAM TS256MLQ64V8U 2GB DIMM DDR 533MT/s          | 1        | 2.04%   |
| SK Hynix RAM Module 1024MB FB-DIMM DDR2 800MT/s           | 1        | 2.04%   |
| SK Hynix RAM HMT151R7TFR4C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 2.04%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1        | 2.04%   |
| SK Hynix RAM HMA84GL7MMR4N-TF 32GB RIMM DDR4 2133MT/s     | 1        | 2.04%   |
| SK Hynix RAM HMA84GL7AMR4N-TF 32GB RIMM DDR4 2133MT/s     | 1        | 2.04%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s    | 1        | 2.04%   |
| Kingston RAM Module 2GB DIMM DDR 533MT/s                  | 1        | 2.04%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s       | 1        | 2.04%   |
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s | 1        | 2.04%   |
| Kingston RAM KHX2666C16D4/16GX 16384MB DIMM DDR4 2667MT/s | 1        | 2.04%   |
| Kingston RAM KHX2400C15D4/8G 8192MB DIMM DDR4 2400MT/s    | 1        | 2.04%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s         | 1        | 2.04%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 1        | 2.04%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1866MT/s    | 1        | 2.04%   |
| Kingston RAM 99U5474-026.A 4GB DIMM DDR3 667MT/s          | 1        | 2.04%   |
| Kingston RAM 99U5471-050.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 2.04%   |
| Kingston RAM 99U5403-002.A00G 2048MB DIMM DDR3 1333MT/s   | 1        | 2.04%   |
| Kingston RAM 9905678-041.A00G 4GB DIMM DDR4 2400MT/s      | 1        | 2.04%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s    | 1        | 2.04%   |
| Corsair RAM CMU16GX4M2C3000C15 8GB DIMM DDR4 3200MT/s     | 1        | 2.04%   |
| Corsair RAM CMK32GX4M2E3200C16 16384MB DIMM DDR4 3200MT/s | 1        | 2.04%   |
| Corsair RAM CMK16GX4M2A2400C14 8GB DIMM DDR4 2800MT/s     | 1        | 2.04%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s     | 1        | 2.04%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s               | 1        | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 19       | 47.5%   |
| DDR3    | 9        | 22.5%   |
| Unknown | 4        | 10%     |
| SDRAM   | 3        | 7.5%    |
| DDR2    | 2        | 5%      |
| DDR     | 2        | 5%      |
| LPDDR4  | 1        | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 34       | 91.89%  |
| SODIMM  | 1        | 2.7%    |
| RIMM    | 1        | 2.7%    |
| FB-DIMM | 1        | 2.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 14       | 35.9%   |
| 4096  | 12       | 30.77%  |
| 2048  | 7        | 17.95%  |
| 16384 | 3        | 7.69%   |
| 1024  | 2        | 5.13%   |
| 32768 | 1        | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 10       | 22.73%  |
| 1600    | 5        | 11.36%  |
| 3533    | 4        | 9.09%   |
| 2400    | 3        | 6.82%   |
| 3466    | 2        | 4.55%   |
| 3200    | 2        | 4.55%   |
| 3151    | 2        | 4.55%   |
| 2667    | 2        | 4.55%   |
| 2133    | 2        | 4.55%   |
| 667     | 2        | 4.55%   |
| 3600    | 1        | 2.27%   |
| 3333    | 1        | 2.27%   |
| 3000    | 1        | 2.27%   |
| 2933    | 1        | 2.27%   |
| 2800    | 1        | 2.27%   |
| 1867    | 1        | 2.27%   |
| 1866    | 1        | 2.27%   |
| 800     | 1        | 2.27%   |
| 533     | 1        | 2.27%   |
| Unknown | 1        | 2.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 33.33%  |
| STMicroelectronics | 1        | 16.67%  |
| Pantum             | 1        | 16.67%  |
| Canon              | 1        | 16.67%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| STMicroelectronics USB Printer P | 1        | 16.67%  |
| Seiko Epson LQ-310               | 1        | 16.67%  |
| Seiko Epson L222 Series          | 1        | 16.67%  |
| Pantum P2500W series             | 1        | 16.67%  |
| Canon E4200 series               | 1        | 16.67%  |
| Brother DCP-L3551CDW             | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 6        | 35.29%  |
| Microdia               | 4        | 23.53%  |
| Aveo Technology        | 3        | 17.65%  |
| Suyin                  | 1        | 5.88%   |
| Realtek Semiconductor  | 1        | 5.88%   |
| Generalplus Technology | 1        | 5.88%   |
| Apple                  | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Microdia Camera                       | 3        | 17.65%  |
| Aveo USB2.0 Camera                    | 2        | 11.76%  |
| Suyin HP Integrated Webcam            | 1        | 5.88%   |
| Realtek USB Boot                      | 1        | 5.88%   |
| Microdia Laptop_Integrated_Webcam_FHD | 1        | 5.88%   |
| Logitech Webcam C600                  | 1        | 5.88%   |
| Logitech Webcam C310                  | 1        | 5.88%   |
| Logitech Webcam C270                  | 1        | 5.88%   |
| Logitech Mic (Notebooks Pro)          | 1        | 5.88%   |
| Logitech HD Webcam C525               | 1        | 5.88%   |
| Logitech HD Webcam C510               | 1        | 5.88%   |
| Generalplus GENERAL WEBCAM            | 1        | 5.88%   |
| Aveo UVC camera (Bresser microscope)  | 1        | 5.88%   |
| Apple iPad 2 (3G; 64GB)               | 1        | 5.88%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 102      | 88.7%   |
| 1     | 10       | 8.7%    |
| 7     | 1        | 0.87%   |
| 5     | 1        | 0.87%   |
| 2     | 1        | 0.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 33.33%  |
| Sound                    | 5        | 27.78%  |
| Net/wireless             | 3        | 16.67%  |
| Communication controller | 2        | 11.11%  |
| Unassigned class         | 1        | 5.56%   |
| Network                  | 1        | 5.56%   |

