OpenMandriva 24.07 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 24.07.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 644

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | B75                         | [f2db8ec2de](https://linux-hardware.org/?probe=f2db8ec2de) | Nov 12, 2025 |
| MSI           | MPG Z490 GAMING PLUS        | [f09e9a7b63](https://linux-hardware.org/?probe=f09e9a7b63) | Oct 22, 2025 |
| Gigabyte      | nForce                      | [8ea3cf2201](https://linux-hardware.org/?probe=8ea3cf2201) | Aug 31, 2025 |
| ASUSTek       | M5A78L-M LE                 | [42af17a2b8](https://linux-hardware.org/?probe=42af17a2b8) | Aug 30, 2025 |
| Gigabyte      | X570 AORUS ULTRA            | [03a39913e3](https://linux-hardware.org/?probe=03a39913e3) | Aug 16, 2025 |
| Gigabyte      | GA-G41M-ES2L                | [837ac6f4db](https://linux-hardware.org/?probe=837ac6f4db) | Aug 12, 2025 |
| Gigabyte      | G41M-ES2L                   | [7dcedd1751](https://linux-hardware.org/?probe=7dcedd1751) | Aug 10, 2025 |
| MSI           | B550M-A PRO                 | [4c0f276180](https://linux-hardware.org/?probe=4c0f276180) | Aug 06, 2025 |
| Lenovo        | MAHOBAY NO DPK              | [bd0842b62f](https://linux-hardware.org/?probe=bd0842b62f) | Jul 25, 2025 |
| Gigabyte      | 970A-DS3P                   | [af126a92ca](https://linux-hardware.org/?probe=af126a92ca) | Jul 20, 2025 |
| AZW           | MINI S                      | [ae0563af05](https://linux-hardware.org/?probe=ae0563af05) | Jul 19, 2025 |
| Gigabyte      | B85M-D3H                    | [9dc6bf9b38](https://linux-hardware.org/?probe=9dc6bf9b38) | Jul 13, 2025 |
| Gigabyte      | B760 DS3H AX DDR4           | [2461a88a30](https://linux-hardware.org/?probe=2461a88a30) | Jul 13, 2025 |
| Ramsta        | RS-A320MP Ver:1.00          | [9a20e1a883](https://linux-hardware.org/?probe=9a20e1a883) | Jul 10, 2025 |
| ASUSTek       | M3A                         | [775e16752c](https://linux-hardware.org/?probe=775e16752c) | Jul 01, 2025 |
| ASUSTek       | B85M-G                      | [28ed8d29bb](https://linux-hardware.org/?probe=28ed8d29bb) | Jun 05, 2025 |
| Gigabyte      | GA-990XA-UD3                | [0082c0231d](https://linux-hardware.org/?probe=0082c0231d) | Jun 03, 2025 |
| Gigabyte      | B550M AORUS ELITE           | [19eb9ed495](https://linux-hardware.org/?probe=19eb9ed495) | Jun 03, 2025 |
| Unknown       | Unknown                     | [adf51a98ae](https://linux-hardware.org/?probe=adf51a98ae) | Jun 01, 2025 |
| ASUSTek       | PRIME B450M-A II            | [992927a2d8](https://linux-hardware.org/?probe=992927a2d8) | May 31, 2025 |
| MSI           | B450M PRO-VDH MAX           | [b44f3f41a0](https://linux-hardware.org/?probe=b44f3f41a0) | May 28, 2025 |
| ASRock        | AM1B-MH                     | [231846ed0e](https://linux-hardware.org/?probe=231846ed0e) | May 26, 2025 |
| HP            | 1497                        | [1aa53c4113](https://linux-hardware.org/?probe=1aa53c4113) | May 08, 2025 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [2257cd6ecd](https://linux-hardware.org/?probe=2257cd6ecd) | May 07, 2025 |
| Gigabyte      | Z68X-UD3H-B3                | [21471345fb](https://linux-hardware.org/?probe=21471345fb) | May 05, 2025 |
| ASRock        | X870E Nova WiFi             | [303deef8fc](https://linux-hardware.org/?probe=303deef8fc) | May 04, 2025 |
| Gigabyte      | B550M DS3H                  | [008cb36a15](https://linux-hardware.org/?probe=008cb36a15) | Apr 29, 2025 |
| Gigabyte      | H55M-USB3                   | [4e62ff3ea2](https://linux-hardware.org/?probe=4e62ff3ea2) | Apr 28, 2025 |
| ASUSTek       | P8H77-I                     | [ed5929ee7b](https://linux-hardware.org/?probe=ed5929ee7b) | Apr 26, 2025 |
| ASUSTek       | Rampage IV BLACK EDITION    | [43b82fc07a](https://linux-hardware.org/?probe=43b82fc07a) | Apr 25, 2025 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [06db4aa634](https://linux-hardware.org/?probe=06db4aa634) | Apr 23, 2025 |
| Gigabyte      | 990FXA-UD3 R5               | [e26e0cbcb0](https://linux-hardware.org/?probe=e26e0cbcb0) | Apr 20, 2025 |
| BESSTAR Te... | HM80                        | [099f76e1c7](https://linux-hardware.org/?probe=099f76e1c7) | Apr 16, 2025 |
| Intel         | DH55TC AAE70932-206         | [608d37fe3e](https://linux-hardware.org/?probe=608d37fe3e) | Apr 14, 2025 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ba46e9c49e](https://linux-hardware.org/?probe=ba46e9c49e) | Apr 05, 2025 |
| ASRock        | A320M Pro4                  | [923a4211f9](https://linux-hardware.org/?probe=923a4211f9) | Mar 18, 2025 |
| MSI           | Z87-G45 GAMING              | [2f5f30dd2c](https://linux-hardware.org/?probe=2f5f30dd2c) | Mar 15, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cd024baa40](https://linux-hardware.org/?probe=cd024baa40) | Mar 10, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS        | [903afa9561](https://linux-hardware.org/?probe=903afa9561) | Feb 23, 2025 |
| MSI           | A520M-A PRO                 | [b0f12bdf92](https://linux-hardware.org/?probe=b0f12bdf92) | Feb 21, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cc6b35c39b](https://linux-hardware.org/?probe=cc6b35c39b) | Feb 20, 2025 |
| Gigabyte      | B450 AORUS ELITE            | [8bf2ff9347](https://linux-hardware.org/?probe=8bf2ff9347) | Feb 19, 2025 |
| ASRock        | Z87 Extreme4                | [6df653a3a2](https://linux-hardware.org/?probe=6df653a3a2) | Feb 19, 2025 |
| MSI           | E350IA-E45                  | [f21478cbb7](https://linux-hardware.org/?probe=f21478cbb7) | Feb 08, 2025 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [ea27ad03d5](https://linux-hardware.org/?probe=ea27ad03d5) | Feb 03, 2025 |
| ASRock        | X670E PG Lightning          | [7c62104a80](https://linux-hardware.org/?probe=7c62104a80) | Feb 01, 2025 |
| ASUSTek       | P5Q3                        | [fb60fc8b28](https://linux-hardware.org/?probe=fb60fc8b28) | Jan 24, 2025 |
| Gigabyte      | X570 AORUS ULTRA            | [16eb2d304a](https://linux-hardware.org/?probe=16eb2d304a) | Jan 24, 2025 |
| MSI           | B550M-A PRO                 | [e6ae4099b5](https://linux-hardware.org/?probe=e6ae4099b5) | Jan 24, 2025 |
| HP            | 8265                        | [1a3578bed8](https://linux-hardware.org/?probe=1a3578bed8) | Jan 21, 2025 |
| HP            | 213D A01                    | [4ef5f5c77b](https://linux-hardware.org/?probe=4ef5f5c77b) | Jan 14, 2025 |
| Gigabyte      | X58A-UD3R                   | [a3139f8204](https://linux-hardware.org/?probe=a3139f8204) | Jan 14, 2025 |
| PCChips       | A45G                        | [80806534be](https://linux-hardware.org/?probe=80806534be) | Jan 12, 2025 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [e6075adfc0](https://linux-hardware.org/?probe=e6075adfc0) | Jan 02, 2025 |
| Gigabyte      | GA-MA785GT-UD3H             | [bf30d86827](https://linux-hardware.org/?probe=bf30d86827) | Jan 01, 2025 |
| Unknown       | Unknown                     | [9dc841041f](https://linux-hardware.org/?probe=9dc841041f) | Dec 25, 2024 |
| Dell          | 0GDG8Y A00                  | [0219cb33b6](https://linux-hardware.org/?probe=0219cb33b6) | Dec 20, 2024 |
| MSI           | B75MA-P45                   | [da146c44f0](https://linux-hardware.org/?probe=da146c44f0) | Dec 19, 2024 |
| Gigabyte      | B450M DS3H V2               | [0d17c2a875](https://linux-hardware.org/?probe=0d17c2a875) | Dec 15, 2024 |
| Positivo      | POS-PIB150DT 11132270       | [c3a85ea71c](https://linux-hardware.org/?probe=c3a85ea71c) | Dec 15, 2024 |
| MSI           | Z97 GAMING 5                | [e41e77f484](https://linux-hardware.org/?probe=e41e77f484) | Dec 12, 2024 |
| Dell          | 09M47G A00                  | [c3b1e4864a](https://linux-hardware.org/?probe=c3b1e4864a) | Dec 12, 2024 |
| Unknown       | Unknown                     | [ed65661387](https://linux-hardware.org/?probe=ed65661387) | Dec 12, 2024 |
| Lenovo        | MAHOBAY NO DPK              | [c5d5aaca89](https://linux-hardware.org/?probe=c5d5aaca89) | Dec 11, 2024 |
| Dell          | 0F6X5P A00                  | [680aead333](https://linux-hardware.org/?probe=680aead333) | Dec 10, 2024 |
| Lenovo        | MAHOBAY Win8 MM DPK IPG     | [e885620f20](https://linux-hardware.org/?probe=e885620f20) | Dec 06, 2024 |
| MSI           | H61M-P23                    | [4e730504db](https://linux-hardware.org/?probe=4e730504db) | Dec 06, 2024 |
| MSI           | A88XI AC V2                 | [3bd43ba035](https://linux-hardware.org/?probe=3bd43ba035) | Dec 06, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [cdb9d074c0](https://linux-hardware.org/?probe=cdb9d074c0) | Dec 06, 2024 |
| Dell          | 0CWR57 A01                  | [38bea64860](https://linux-hardware.org/?probe=38bea64860) | Dec 06, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | [dd80673855](https://linux-hardware.org/?probe=dd80673855) | Dec 05, 2024 |
| Gigabyte      | G31M-S2L                    | [a8795f3981](https://linux-hardware.org/?probe=a8795f3981) | Dec 04, 2024 |
| ASUSTek       | Z87-PRO                     | [029f1c1e1b](https://linux-hardware.org/?probe=029f1c1e1b) | Dec 03, 2024 |
| Unknown       | Unknown                     | [3405878ab6](https://linux-hardware.org/?probe=3405878ab6) | Dec 01, 2024 |
| Dell          | 088DT1 A01                  | [ba38d6b924](https://linux-hardware.org/?probe=ba38d6b924) | Dec 01, 2024 |
| Dell          | 0VNP2H A00                  | [d1a2135f92](https://linux-hardware.org/?probe=d1a2135f92) | Nov 30, 2024 |
| Gigabyte      | H61M-DS2                    | [ce0e3b2719](https://linux-hardware.org/?probe=ce0e3b2719) | Nov 29, 2024 |
| BESSTAR Te... | UM700                       | [5c18419477](https://linux-hardware.org/?probe=5c18419477) | Nov 29, 2024 |
| Dell          | 042P49 A02                  | [6c4c6577ac](https://linux-hardware.org/?probe=6c4c6577ac) | Nov 29, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [7e2cca4ada](https://linux-hardware.org/?probe=7e2cca4ada) | Nov 28, 2024 |
| Gigabyte      | H81M-D2W                    | [c0db894e36](https://linux-hardware.org/?probe=c0db894e36) | Nov 28, 2024 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [d113defbe8](https://linux-hardware.org/?probe=d113defbe8) | Nov 27, 2024 |
| HP            | 18E7                        | [6dbb855fd6](https://linux-hardware.org/?probe=6dbb855fd6) | Nov 26, 2024 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [2e121a8a35](https://linux-hardware.org/?probe=2e121a8a35) | Nov 26, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [07ef34a01f](https://linux-hardware.org/?probe=07ef34a01f) | Nov 25, 2024 |
| Intel         | B75                         | [b8e4743721](https://linux-hardware.org/?probe=b8e4743721) | Nov 24, 2024 |
| Lenovo        | 31900058 STD                | [dfea5f8644](https://linux-hardware.org/?probe=dfea5f8644) | Nov 24, 2024 |
| ASUSTek       | PRIME A520M-K               | [db71db68e5](https://linux-hardware.org/?probe=db71db68e5) | Nov 23, 2024 |
| Gigabyte      | H510M H V2                  | [a9d59f6f5f](https://linux-hardware.org/?probe=a9d59f6f5f) | Nov 23, 2024 |
| ASUSTek       | Pro B550M-C                 | [e532c8a2c5](https://linux-hardware.org/?probe=e532c8a2c5) | Nov 23, 2024 |
| ASUSTek       | B75M-A                      | [e7f193654c](https://linux-hardware.org/?probe=e7f193654c) | Nov 23, 2024 |
| Intel         | D945GCCR AAD78647-300       | [1b7eecc546](https://linux-hardware.org/?probe=1b7eecc546) | Nov 22, 2024 |
| ASUSTek       | PRIME A320M-K               | [bdad4ccabe](https://linux-hardware.org/?probe=bdad4ccabe) | Nov 22, 2024 |
| Dell          | 0FR6WH A01                  | [8ea0baf186](https://linux-hardware.org/?probe=8ea0baf186) | Nov 21, 2024 |
| HP            | 8055                        | [25559cfc60](https://linux-hardware.org/?probe=25559cfc60) | Nov 20, 2024 |
| Gigabyte      | H97M-DS3P                   | [0d1e9eec2d](https://linux-hardware.org/?probe=0d1e9eec2d) | Nov 20, 2024 |
| HP            | 8954                        | [58001c585c](https://linux-hardware.org/?probe=58001c585c) | Nov 19, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [eb0ca23199](https://linux-hardware.org/?probe=eb0ca23199) | Nov 19, 2024 |
| Shenzhen M... | F7BFC                       | [4a79811e5e](https://linux-hardware.org/?probe=4a79811e5e) | Nov 17, 2024 |
| Dell          | 0MN1TX A00                  | [bc63ab4bf3](https://linux-hardware.org/?probe=bc63ab4bf3) | Nov 15, 2024 |
| ASUSTek       | F2A85-M2                    | [b6e3dbb57a](https://linux-hardware.org/?probe=b6e3dbb57a) | Nov 15, 2024 |
| Foxconn       | 2ADA                        | [f3b302e1d7](https://linux-hardware.org/?probe=f3b302e1d7) | Nov 15, 2024 |
| Dell          | 0200DY A02                  | [7a85e1e310](https://linux-hardware.org/?probe=7a85e1e310) | Nov 15, 2024 |
| MSI           | B365M PRO-VH                | [b2796a7151](https://linux-hardware.org/?probe=b2796a7151) | Nov 14, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [280fdbebe9](https://linux-hardware.org/?probe=280fdbebe9) | Nov 13, 2024 |
| HP            | 18E7                        | [e6421394f6](https://linux-hardware.org/?probe=e6421394f6) | Nov 13, 2024 |
| Gigabyte      | B75M-HD3                    | [c594c0e00c](https://linux-hardware.org/?probe=c594c0e00c) | Nov 11, 2024 |
| HP            | 1497                        | [b4fe73ae99](https://linux-hardware.org/?probe=b4fe73ae99) | Nov 09, 2024 |
| ASUSTek       | PRIME X570-P                | [bd81a29143](https://linux-hardware.org/?probe=bd81a29143) | Nov 09, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [083567b242](https://linux-hardware.org/?probe=083567b242) | Nov 07, 2024 |
| MSI           | B450M PRO-VDH MAX           | [ce1c922dc4](https://linux-hardware.org/?probe=ce1c922dc4) | Nov 07, 2024 |
| HP            | 1495                        | [b362515be5](https://linux-hardware.org/?probe=b362515be5) | Nov 06, 2024 |
| ASRock        | Z790 Riptide WiFi           | [f7330298cd](https://linux-hardware.org/?probe=f7330298cd) | Nov 05, 2024 |
| Gigabyte      | H61M-S1                     | [4583180173](https://linux-hardware.org/?probe=4583180173) | Nov 04, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [02f10cb27c](https://linux-hardware.org/?probe=02f10cb27c) | Nov 04, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [40b8d362ea](https://linux-hardware.org/?probe=40b8d362ea) | Nov 03, 2024 |
| Dell          | 0JP3NX A01                  | [dc2c04bda9](https://linux-hardware.org/?probe=dc2c04bda9) | Nov 03, 2024 |
| Gigabyte      | P75-D3                      | [7ba3b8a5aa](https://linux-hardware.org/?probe=7ba3b8a5aa) | Nov 02, 2024 |
| Acer          | EG43M                       | [481ae677a2](https://linux-hardware.org/?probe=481ae677a2) | Nov 02, 2024 |
| Foxconn       | 2ABF                        | [bed04a9e0f](https://linux-hardware.org/?probe=bed04a9e0f) | Nov 01, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [480e9ee913](https://linux-hardware.org/?probe=480e9ee913) | Nov 01, 2024 |
| ASUSTek       | H81M-A                      | [04eef716a6](https://linux-hardware.org/?probe=04eef716a6) | Nov 01, 2024 |
| Gigabyte      | P31-ES3G                    | [cecda20fcc](https://linux-hardware.org/?probe=cecda20fcc) | Oct 31, 2024 |
| Intel         | B75                         | [c48a602eae](https://linux-hardware.org/?probe=c48a602eae) | Oct 31, 2024 |
| ASRock        | H81M-HDS                    | [aef95abb88](https://linux-hardware.org/?probe=aef95abb88) | Oct 31, 2024 |
| ASUSTek       | P5Q                         | [da83835b83](https://linux-hardware.org/?probe=da83835b83) | Oct 30, 2024 |
| MSI           | MPG X570S CARBON MAX WIF... | [67af4a9e08](https://linux-hardware.org/?probe=67af4a9e08) | Oct 29, 2024 |
| ASUSTek       | PRIME A320M-K               | [046f64be70](https://linux-hardware.org/?probe=046f64be70) | Oct 28, 2024 |
| HP            | 0B4Ch D                     | [4488b0b5e6](https://linux-hardware.org/?probe=4488b0b5e6) | Oct 28, 2024 |
| OEM           | X79G                        | [3ae4c25ee7](https://linux-hardware.org/?probe=3ae4c25ee7) | Oct 28, 2024 |
| ASUSTek       | A88X-PRO                    | [5e1dd8eae1](https://linux-hardware.org/?probe=5e1dd8eae1) | Oct 27, 2024 |
| Gigabyte      | B75M-D3H                    | [98e2047b3e](https://linux-hardware.org/?probe=98e2047b3e) | Oct 27, 2024 |
| MSI           | CSM-H81M-P32                | [375a0a6487](https://linux-hardware.org/?probe=375a0a6487) | Oct 26, 2024 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [4edc7c0869](https://linux-hardware.org/?probe=4edc7c0869) | Oct 26, 2024 |
| Biostar       | A10N-8800E                  | [5710a05f5f](https://linux-hardware.org/?probe=5710a05f5f) | Oct 26, 2024 |
| Gigabyte      | H55M-S2H                    | [08aa1a4721](https://linux-hardware.org/?probe=08aa1a4721) | Oct 25, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [61d6f4f9da](https://linux-hardware.org/?probe=61d6f4f9da) | Oct 25, 2024 |
| Intel         | DP45SG AAE27733-402         | [80022aa1fa](https://linux-hardware.org/?probe=80022aa1fa) | Oct 24, 2024 |
| Gigabyte      | F2A75M-D3H                  | [8cf1a27cdd](https://linux-hardware.org/?probe=8cf1a27cdd) | Oct 24, 2024 |
| ASUSTek       | Crosshair IV Formula        | [e459f477ce](https://linux-hardware.org/?probe=e459f477ce) | Oct 23, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | [15b278bc6b](https://linux-hardware.org/?probe=15b278bc6b) | Oct 23, 2024 |
| Intel         | DG31PR AAE58249-306         | [29d5c95cb2](https://linux-hardware.org/?probe=29d5c95cb2) | Oct 22, 2024 |
| Intel         | JSL MRD                     | [77928ce492](https://linux-hardware.org/?probe=77928ce492) | Oct 21, 2024 |
| MSI           | G41TM-P31                   | [4a0f7d5481](https://linux-hardware.org/?probe=4a0f7d5481) | Oct 21, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1c9e79aeac](https://linux-hardware.org/?probe=1c9e79aeac) | Oct 20, 2024 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | [29167809af](https://linux-hardware.org/?probe=29167809af) | Oct 20, 2024 |
| Dell          | 02YRK5 A02                  | [b1ba54be2e](https://linux-hardware.org/?probe=b1ba54be2e) | Oct 20, 2024 |
| ASUSTek       | H61M-K                      | [50de29919f](https://linux-hardware.org/?probe=50de29919f) | Oct 19, 2024 |
| HP            | 212A                        | [5af12ae426](https://linux-hardware.org/?probe=5af12ae426) | Oct 19, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [74bfaad70a](https://linux-hardware.org/?probe=74bfaad70a) | Oct 18, 2024 |
| Intel         | JSL MRD                     | [3e4834107b](https://linux-hardware.org/?probe=3e4834107b) | Oct 17, 2024 |
| Intel         | H61                         | [a4dc63e432](https://linux-hardware.org/?probe=a4dc63e432) | Oct 16, 2024 |
| MSI           | Z490-A PRO                  | [4a31262892](https://linux-hardware.org/?probe=4a31262892) | Oct 15, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [bf8a04a93c](https://linux-hardware.org/?probe=bf8a04a93c) | Oct 15, 2024 |
| Pegatron      | Benicia                     | [cd156adfd2](https://linux-hardware.org/?probe=cd156adfd2) | Oct 14, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [af7ced3aff](https://linux-hardware.org/?probe=af7ced3aff) | Oct 12, 2024 |
| ASUSTek       | M5A78L-M LX3                | [1e12bb1b07](https://linux-hardware.org/?probe=1e12bb1b07) | Oct 12, 2024 |
| AMD           | A88                         | [3442c71c38](https://linux-hardware.org/?probe=3442c71c38) | Oct 12, 2024 |
| ASUSTek       | B85M-E/BR                   | [bd4f53dc99](https://linux-hardware.org/?probe=bd4f53dc99) | Oct 12, 2024 |
| Apple         | Mac-F221BEC8                | [8126af742f](https://linux-hardware.org/?probe=8126af742f) | Oct 11, 2024 |
| Biostar       | G41D3C                      | [3301adecfb](https://linux-hardware.org/?probe=3301adecfb) | Oct 11, 2024 |
| MACHINIST     | X99 PR9-H                   | [a0ead70204](https://linux-hardware.org/?probe=a0ead70204) | Oct 09, 2024 |
| ASUSTek       | Q170M-C                     | [a8eab7ba48](https://linux-hardware.org/?probe=a8eab7ba48) | Oct 08, 2024 |
| Firebat_Co... | T8_Plus                     | [7b0c62125c](https://linux-hardware.org/?probe=7b0c62125c) | Oct 07, 2024 |
| ASUSTek       | P5K                         | [3c9825ba0b](https://linux-hardware.org/?probe=3c9825ba0b) | Oct 07, 2024 |
| ASUSTek       | A55BM-K                     | [a10e7e5307](https://linux-hardware.org/?probe=a10e7e5307) | Oct 06, 2024 |
| MACHINIST     | X99 PR9-H                   | [79d889bb1d](https://linux-hardware.org/?probe=79d889bb1d) | Oct 04, 2024 |
| Biostar       | A960D+                      | [10e003ed0a](https://linux-hardware.org/?probe=10e003ed0a) | Oct 04, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | [7258a3f215](https://linux-hardware.org/?probe=7258a3f215) | Oct 03, 2024 |
| ASRock        | X570 Phantom Gaming 4 Wi... | [b057221ffa](https://linux-hardware.org/?probe=b057221ffa) | Oct 03, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [9d076b194d](https://linux-hardware.org/?probe=9d076b194d) | Oct 02, 2024 |
| HP            | 8767 A                      | [8243a00195](https://linux-hardware.org/?probe=8243a00195) | Oct 02, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [dfea07d14a](https://linux-hardware.org/?probe=dfea07d14a) | Oct 02, 2024 |
| ASUSTek       | F2A55-M LK PLUS             | [2fdfd4a0ca](https://linux-hardware.org/?probe=2fdfd4a0ca) | Oct 01, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d9813a1e38](https://linux-hardware.org/?probe=d9813a1e38) | Oct 01, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [205dba9239](https://linux-hardware.org/?probe=205dba9239) | Sep 29, 2024 |
| Gigabyte      | B450 AORUS ELITE V2         | [d68ba4aa7a](https://linux-hardware.org/?probe=d68ba4aa7a) | Sep 29, 2024 |
| Gigabyte      | X58A-UD5                    | [a6c2b82581](https://linux-hardware.org/?probe=a6c2b82581) | Sep 27, 2024 |
| ASUSTek       | M5A88-M                     | [5725f8c2e1](https://linux-hardware.org/?probe=5725f8c2e1) | Sep 26, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [3ebe7fc112](https://linux-hardware.org/?probe=3ebe7fc112) | Sep 26, 2024 |
| Colorful T... | C.A68HM PRO V14             | [524b75af5e](https://linux-hardware.org/?probe=524b75af5e) | Sep 25, 2024 |
| Acer          | FIH57                       | [d281d08f5b](https://linux-hardware.org/?probe=d281d08f5b) | Sep 24, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1738960295](https://linux-hardware.org/?probe=1738960295) | Sep 24, 2024 |
| ASUSTek       | PRIME X370-PRO              | [262e1993ad](https://linux-hardware.org/?probe=262e1993ad) | Sep 23, 2024 |
| ASRock        | A320M-HDV R4.0              | [e9f25fa551](https://linux-hardware.org/?probe=e9f25fa551) | Sep 23, 2024 |
| Foxconn       | 2ABF                        | [ae87bd81f4](https://linux-hardware.org/?probe=ae87bd81f4) | Sep 23, 2024 |
| Gigabyte      | H55M-USB3                   | [ddffc54d59](https://linux-hardware.org/?probe=ddffc54d59) | Sep 22, 2024 |
| JGINYUE       | H81M VH PLUS V1.1           | [15128e9c08](https://linux-hardware.org/?probe=15128e9c08) | Sep 22, 2024 |
| Lenovo        | NO DPK                      | [55c567c63a](https://linux-hardware.org/?probe=55c567c63a) | Sep 20, 2024 |
| Dell          | 0D28YY A00                  | [6002c0cb97](https://linux-hardware.org/?probe=6002c0cb97) | Sep 19, 2024 |
| Gigabyte      | H310N                       | [d1452d296c](https://linux-hardware.org/?probe=d1452d296c) | Sep 19, 2024 |
| Lenovo        | SDK0E50510 WIN              | [02501a0d37](https://linux-hardware.org/?probe=02501a0d37) | Sep 18, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3bbcc1fdfa](https://linux-hardware.org/?probe=3bbcc1fdfa) | Sep 16, 2024 |
| Shenzhen M... | F7BAA                       | [0e7cb8c966](https://linux-hardware.org/?probe=0e7cb8c966) | Sep 16, 2024 |
| Dell          | 088DT1 A01                  | [4121f94162](https://linux-hardware.org/?probe=4121f94162) | Sep 15, 2024 |
| AZW           | SER V1                      | [2a711515ce](https://linux-hardware.org/?probe=2a711515ce) | Sep 15, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [833d4acd21](https://linux-hardware.org/?probe=833d4acd21) | Sep 15, 2024 |
| ZOTAC         | NM10                        | [d75d2e7290](https://linux-hardware.org/?probe=d75d2e7290) | Sep 15, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [6819a810d2](https://linux-hardware.org/?probe=6819a810d2) | Sep 14, 2024 |
| Gigabyte      | P110-D3-CF                  | [11179fcd4d](https://linux-hardware.org/?probe=11179fcd4d) | Sep 13, 2024 |
| Intel         | B75                         | [3fffe506e7](https://linux-hardware.org/?probe=3fffe506e7) | Sep 13, 2024 |
| MACHINIST     | H97M-PRO V1.1               | [e4e066a84a](https://linux-hardware.org/?probe=e4e066a84a) | Sep 12, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [6759b6dbf3](https://linux-hardware.org/?probe=6759b6dbf3) | Sep 11, 2024 |
| Gigabyte      | B360M DS3H                  | [6318508130](https://linux-hardware.org/?probe=6318508130) | Sep 11, 2024 |
| Lenovo        | Annapurna CRB NOK           | [b4e8188de1](https://linux-hardware.org/?probe=b4e8188de1) | Sep 11, 2024 |
| Dell          | 07N90W A01                  | [11eb8aa4dc](https://linux-hardware.org/?probe=11eb8aa4dc) | Sep 11, 2024 |
| Positivo      | POS-EINM70CS POSITIVO       | [f593400ff4](https://linux-hardware.org/?probe=f593400ff4) | Sep 10, 2024 |
| HP            | 8265                        | [43b7b19d0e](https://linux-hardware.org/?probe=43b7b19d0e) | Sep 09, 2024 |
| Gigabyte X... | 56547AHJ29 1167789          | [01030238e9](https://linux-hardware.org/?probe=01030238e9) | Sep 08, 2024 |
| Biostar       | B550M-SILVER                | [78c5e356b9](https://linux-hardware.org/?probe=78c5e356b9) | Sep 07, 2024 |
| ASUSTek       | H97-PLUS                    | [1c314094d5](https://linux-hardware.org/?probe=1c314094d5) | Sep 07, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e91782f4a9](https://linux-hardware.org/?probe=e91782f4a9) | Sep 07, 2024 |
| ASUSTek       | H61M-K                      | [994c8510c9](https://linux-hardware.org/?probe=994c8510c9) | Sep 06, 2024 |
| Acer          | Aspire M3970                | [5c1577174f](https://linux-hardware.org/?probe=5c1577174f) | Sep 06, 2024 |
| Foxconn       | 2ABF                        | [bc89477644](https://linux-hardware.org/?probe=bc89477644) | Sep 06, 2024 |
| ASUSTek       | TUF B450M-PRO GAMING        | [5a7048fbe0](https://linux-hardware.org/?probe=5a7048fbe0) | Sep 06, 2024 |
| ASRock        | A520M Pro4                  | [2a716a1e08](https://linux-hardware.org/?probe=2a716a1e08) | Sep 05, 2024 |
| Gigabyte      | A520I AC                    | [5351be60b3](https://linux-hardware.org/?probe=5351be60b3) | Sep 03, 2024 |
| ASRock        | H67M                        | [755733f8ee](https://linux-hardware.org/?probe=755733f8ee) | Sep 03, 2024 |
| ASUSTek       | H110M-R                     | [27131910d0](https://linux-hardware.org/?probe=27131910d0) | Sep 03, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [fd045954b3](https://linux-hardware.org/?probe=fd045954b3) | Sep 03, 2024 |
| HP            | 212B                        | [1d3fb28940](https://linux-hardware.org/?probe=1d3fb28940) | Sep 03, 2024 |
| Intel         | DH67BL AAG10189-213         | [e151ff7acf](https://linux-hardware.org/?probe=e151ff7acf) | Sep 02, 2024 |
| ASUSTek       | N3050T                      | [9c852a30a0](https://linux-hardware.org/?probe=9c852a30a0) | Sep 01, 2024 |
| ASUSTek       | H87M-E                      | [d96d545feb](https://linux-hardware.org/?probe=d96d545feb) | Aug 31, 2024 |
| Gigabyte      | M61PME-S2P                  | [4439caab2a](https://linux-hardware.org/?probe=4439caab2a) | Aug 31, 2024 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [f67aa32eca](https://linux-hardware.org/?probe=f67aa32eca) | Aug 31, 2024 |
| ASRock        | H81M-VG4                    | [5a4c31c811](https://linux-hardware.org/?probe=5a4c31c811) | Aug 30, 2024 |
| Pegatron      | JESSE                       | [1e3f996dc4](https://linux-hardware.org/?probe=1e3f996dc4) | Aug 30, 2024 |
| HP            | 8648                        | [cd449a247f](https://linux-hardware.org/?probe=cd449a247f) | Aug 29, 2024 |
| ASUSTek       | Pro H610M-C D4              | [1b20c180f0](https://linux-hardware.org/?probe=1b20c180f0) | Aug 29, 2024 |
| Dell          | 07N90W A02                  | [678eed9a97](https://linux-hardware.org/?probe=678eed9a97) | Aug 28, 2024 |
| ASUSTek       | PRIME B250M-A               | [91228a363f](https://linux-hardware.org/?probe=91228a363f) | Aug 28, 2024 |
| Intel         | H61 V1.5                    | [ca29674330](https://linux-hardware.org/?probe=ca29674330) | Aug 28, 2024 |
| MSI           | H61M-P21                    | [b492068c78](https://linux-hardware.org/?probe=b492068c78) | Aug 28, 2024 |
| ASRock        | A320M Pro4                  | [537d144744](https://linux-hardware.org/?probe=537d144744) | Aug 27, 2024 |
| ASRock        | H61M-S                      | [6f46ff8666](https://linux-hardware.org/?probe=6f46ff8666) | Aug 27, 2024 |
| Huanan        | X99-QD4 V1.0                | [c65444e5a7](https://linux-hardware.org/?probe=c65444e5a7) | Aug 27, 2024 |
| Dell          | 0WMJ54 A01                  | [be116bc4fe](https://linux-hardware.org/?probe=be116bc4fe) | Aug 27, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [bf763401f5](https://linux-hardware.org/?probe=bf763401f5) | Aug 27, 2024 |
| ASUSTek       | H110M-K                     | [7a42e68f76](https://linux-hardware.org/?probe=7a42e68f76) | Aug 26, 2024 |
| HP            | 8618                        | [6f804c5758](https://linux-hardware.org/?probe=6f804c5758) | Aug 26, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [19683c12d7](https://linux-hardware.org/?probe=19683c12d7) | Aug 26, 2024 |
| Dell          | 0M5DCD A00                  | [35eab4446f](https://linux-hardware.org/?probe=35eab4446f) | Aug 26, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [2437ded49b](https://linux-hardware.org/?probe=2437ded49b) | Aug 26, 2024 |
| ASUSTek       | P5Q SE                      | [1e40e4bbc4](https://linux-hardware.org/?probe=1e40e4bbc4) | Aug 25, 2024 |
| ASRock        | FM2A75M-HD+                 | [cc00bdf2f2](https://linux-hardware.org/?probe=cc00bdf2f2) | Aug 24, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [18c81a5d40](https://linux-hardware.org/?probe=18c81a5d40) | Aug 24, 2024 |
| Dell          | 0DR845                      | [479d25843a](https://linux-hardware.org/?probe=479d25843a) | Aug 24, 2024 |
| ASUSTek       | CM1730,CM1830               | [ceb044885e](https://linux-hardware.org/?probe=ceb044885e) | Aug 23, 2024 |
| Red Hat       | RHEL RHEL-9.4.0 PC          | [e5b92fc048](https://linux-hardware.org/?probe=e5b92fc048) | Aug 23, 2024 |
| HP            | 304Ah                       | [4d2c7bc8b2](https://linux-hardware.org/?probe=4d2c7bc8b2) | Aug 23, 2024 |
| Dell          | 0VRWRC A00                  | [1cc469a71c](https://linux-hardware.org/?probe=1cc469a71c) | Aug 22, 2024 |
| Gigabyte      | Z77X-UD5H                   | [67ebefbd7c](https://linux-hardware.org/?probe=67ebefbd7c) | Aug 22, 2024 |
| Foxconn       | 17A0                        | [34e71b0b28](https://linux-hardware.org/?probe=34e71b0b28) | Aug 22, 2024 |
| ASUSTek       | P8H67                       | [54e766f338](https://linux-hardware.org/?probe=54e766f338) | Aug 21, 2024 |
| Gigabyte      | H310M DS2 x.x               | [bb51e6272b](https://linux-hardware.org/?probe=bb51e6272b) | Aug 21, 2024 |
| Gigabyte      | A520M S2H                   | [4013b39348](https://linux-hardware.org/?probe=4013b39348) | Aug 21, 2024 |
| ASRock        | Z97 Anniversary             | [9255d13688](https://linux-hardware.org/?probe=9255d13688) | Aug 20, 2024 |
| Dell          | 0TX755 A02                  | [782d19f6d0](https://linux-hardware.org/?probe=782d19f6d0) | Aug 20, 2024 |
| HP            | 1998                        | [7884402051](https://linux-hardware.org/?probe=7884402051) | Aug 20, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [24bb07bee7](https://linux-hardware.org/?probe=24bb07bee7) | Aug 19, 2024 |
| Dell          | 0773VG A02                  | [56a9b6f7e6](https://linux-hardware.org/?probe=56a9b6f7e6) | Aug 19, 2024 |
| HP            | 1497                        | [34025b9702](https://linux-hardware.org/?probe=34025b9702) | Aug 18, 2024 |
| ZOTAC         | NM10                        | [4244e8bb97](https://linux-hardware.org/?probe=4244e8bb97) | Aug 18, 2024 |
| Acer          | F690GVM                     | [f9f5665863](https://linux-hardware.org/?probe=f9f5665863) | Aug 18, 2024 |
| HP            | 2B34                        | [e440f003bd](https://linux-hardware.org/?probe=e440f003bd) | Aug 18, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [5a2f8eb128](https://linux-hardware.org/?probe=5a2f8eb128) | Aug 18, 2024 |
| Intel         | H55                         | [31b6348c05](https://linux-hardware.org/?probe=31b6348c05) | Aug 17, 2024 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [6bf836b973](https://linux-hardware.org/?probe=6bf836b973) | Aug 17, 2024 |
| ASUSTek       | P9X79 PRO                   | [33cfb16c35](https://linux-hardware.org/?probe=33cfb16c35) | Aug 16, 2024 |
| ASRock        | X300M-STX                   | [39611ab403](https://linux-hardware.org/?probe=39611ab403) | Aug 16, 2024 |
| ASRock        | AB350M-HDV                  | [ad2f980ddf](https://linux-hardware.org/?probe=ad2f980ddf) | Aug 15, 2024 |
| ASRock        | B85M-DGS                    | [70fd24795c](https://linux-hardware.org/?probe=70fd24795c) | Aug 14, 2024 |
| Gigabyte      | B365M DS3H                  | [43968b561a](https://linux-hardware.org/?probe=43968b561a) | Aug 14, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [4b7514c640](https://linux-hardware.org/?probe=4b7514c640) | Aug 14, 2024 |
| MSI           | PRO H610M-B DDR4            | [ba18c5a60e](https://linux-hardware.org/?probe=ba18c5a60e) | Aug 14, 2024 |
| ASUSTek       | PRIME A320M-K               | [3b88a5d126](https://linux-hardware.org/?probe=3b88a5d126) | Aug 14, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [009462564a](https://linux-hardware.org/?probe=009462564a) | Aug 13, 2024 |
| ASUSTek       | PRIME B450M-A II            | [140ac24212](https://linux-hardware.org/?probe=140ac24212) | Aug 13, 2024 |
| AZW           | MINI S 10                   | [ad35290a2c](https://linux-hardware.org/?probe=ad35290a2c) | Aug 13, 2024 |
| Gigabyte      | H610M K DDR4                | [513a80a2df](https://linux-hardware.org/?probe=513a80a2df) | Aug 13, 2024 |
| ASRock        | FM2A55M-DGS                 | [a5fa87c0d6](https://linux-hardware.org/?probe=a5fa87c0d6) | Aug 13, 2024 |
| Dell          | 0N4YC8 A00                  | [065d3d77f8](https://linux-hardware.org/?probe=065d3d77f8) | Aug 12, 2024 |
| HP            | 3397                        | [da2b320cd5](https://linux-hardware.org/?probe=da2b320cd5) | Aug 12, 2024 |
| MSI           | PRO A620M-E                 | [89b83dcdb0](https://linux-hardware.org/?probe=89b83dcdb0) | Aug 12, 2024 |
| ASUSTek       | P5G41T-M LX                 | [061482f47f](https://linux-hardware.org/?probe=061482f47f) | Aug 12, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [e867eec20b](https://linux-hardware.org/?probe=e867eec20b) | Aug 12, 2024 |
| ASRock        | A320M-HDV R4.0              | [26690c5356](https://linux-hardware.org/?probe=26690c5356) | Aug 12, 2024 |
| Gigabyte      | B660M DS3H DDR4             | [d089d7d1d3](https://linux-hardware.org/?probe=d089d7d1d3) | Aug 11, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [4fb9d317dd](https://linux-hardware.org/?probe=4fb9d317dd) | Aug 11, 2024 |
| ASRock        | H81M-HDS R2.0               | [051e8de774](https://linux-hardware.org/?probe=051e8de774) | Aug 11, 2024 |
| HP            | 198E                        | [21d03f44b1](https://linux-hardware.org/?probe=21d03f44b1) | Aug 11, 2024 |
| Intel         | DZ77SL-50K AAG55115-300     | [c65f2e86cd](https://linux-hardware.org/?probe=c65f2e86cd) | Aug 11, 2024 |
| ASUSTek       | PRIME A320I-K               | [aa056d901f](https://linux-hardware.org/?probe=aa056d901f) | Aug 10, 2024 |
| Intel         | H61                         | [1fe94737e9](https://linux-hardware.org/?probe=1fe94737e9) | Aug 09, 2024 |
| MSI           | MAG B460M MORTAR            | [ae8fdae6ed](https://linux-hardware.org/?probe=ae8fdae6ed) | Aug 08, 2024 |
| ASRock        | B450M Steel Legend          | [8f925bc665](https://linux-hardware.org/?probe=8f925bc665) | Aug 08, 2024 |
| ASUSTek       | F2A85-M LE                  | [1e20eab5b3](https://linux-hardware.org/?probe=1e20eab5b3) | Aug 08, 2024 |
| Gigabyte      | B450M H                     | [4608705c1b](https://linux-hardware.org/?probe=4608705c1b) | Aug 08, 2024 |
| Unknown       | Unknown                     | [ca2d1b6863](https://linux-hardware.org/?probe=ca2d1b6863) | Aug 08, 2024 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ddc4fa1063](https://linux-hardware.org/?probe=ddc4fa1063) | Aug 07, 2024 |
| AZW           | U59                         | [086e42624a](https://linux-hardware.org/?probe=086e42624a) | Aug 07, 2024 |
| Philco        | 10D                         | [133e541e61](https://linux-hardware.org/?probe=133e541e61) | Aug 07, 2024 |
| MACHINIST     | X99 PR9-H                   | [0cdafef2f4](https://linux-hardware.org/?probe=0cdafef2f4) | Aug 07, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [9ba8f17a6e](https://linux-hardware.org/?probe=9ba8f17a6e) | Aug 06, 2024 |
| ASUSTek       | Z87M-PLUS                   | [1ed225ce94](https://linux-hardware.org/?probe=1ed225ce94) | Aug 06, 2024 |
| Supermicro    | X9DAi                       | [c3897b940a](https://linux-hardware.org/?probe=c3897b940a) | Aug 06, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [476a7f88c7](https://linux-hardware.org/?probe=476a7f88c7) | Aug 06, 2024 |
| MSI           | 760GM-P23                   | [0933c9d67f](https://linux-hardware.org/?probe=0933c9d67f) | Aug 06, 2024 |
| ASRock        | B650M Pro RS WiFi           | [0d84feef29](https://linux-hardware.org/?probe=0d84feef29) | Aug 06, 2024 |
| ASUSTek       | H87M-E                      | [4b50217825](https://linux-hardware.org/?probe=4b50217825) | Aug 06, 2024 |
| Gigabyte      | B660M DS3H DDR4             | [d9d47580bb](https://linux-hardware.org/?probe=d9d47580bb) | Aug 06, 2024 |
| ASUSTek       | PRIME A320M-K               | [e9a6c51c04](https://linux-hardware.org/?probe=e9a6c51c04) | Aug 06, 2024 |
| MSI           | X470 GAMING PLUS            | [25e07e9c51](https://linux-hardware.org/?probe=25e07e9c51) | Aug 05, 2024 |
| ASRock        | X570 Taichi                 | [70797c7bcc](https://linux-hardware.org/?probe=70797c7bcc) | Aug 05, 2024 |
| Apple         | Mac-F221BEC8                | [c5d08d410b](https://linux-hardware.org/?probe=c5d08d410b) | Aug 05, 2024 |
| HP            | 3031h                       | [aedf79b471](https://linux-hardware.org/?probe=aedf79b471) | Aug 05, 2024 |
| ASUSTek       | A68HM-PLUS                  | [308a21f570](https://linux-hardware.org/?probe=308a21f570) | Aug 05, 2024 |
| ASUSTek       | PRIME A320M-K               | [ea27aaf797](https://linux-hardware.org/?probe=ea27aaf797) | Aug 05, 2024 |
| Gigabyte      | EP43T-UD3L                  | [94df9b5c30](https://linux-hardware.org/?probe=94df9b5c30) | Aug 05, 2024 |
| Gigabyte      | B85M-D3H                    | [db311c05ec](https://linux-hardware.org/?probe=db311c05ec) | Aug 04, 2024 |
| ASRock        | H81M-HDS                    | [eb80d08b53](https://linux-hardware.org/?probe=eb80d08b53) | Aug 04, 2024 |
| HP            | 89B4 A                      | [56591c9375](https://linux-hardware.org/?probe=56591c9375) | Aug 04, 2024 |
| MSI           | B450 TOMAHAWK               | [29f5ed3f5d](https://linux-hardware.org/?probe=29f5ed3f5d) | Aug 04, 2024 |
| ASRock        | B550M Pro4                  | [ac57850733](https://linux-hardware.org/?probe=ac57850733) | Aug 04, 2024 |
| HP            | 82B4                        | [529d7bc55e](https://linux-hardware.org/?probe=529d7bc55e) | Aug 04, 2024 |
| Gigabyte      | B85M-DS3H-A                 | [e4cccb1fad](https://linux-hardware.org/?probe=e4cccb1fad) | Aug 04, 2024 |
| Acer          | Aspire XC-603               | [23210e4d9f](https://linux-hardware.org/?probe=23210e4d9f) | Aug 04, 2024 |
| MSI           | 760GM-P23                   | [f6db289464](https://linux-hardware.org/?probe=f6db289464) | Aug 04, 2024 |
| Intel         | H110 Series                 | [ba2023d022](https://linux-hardware.org/?probe=ba2023d022) | Aug 03, 2024 |
| ASUSTek       | P5G41C-M LX                 | [d4c3ba8890](https://linux-hardware.org/?probe=d4c3ba8890) | Aug 03, 2024 |
| Lenovo        | ThinkCentre M81 0267A38     | [88a07e7d3e](https://linux-hardware.org/?probe=88a07e7d3e) | Aug 03, 2024 |
| ASRock        | B450 Pro4                   | [20f39c9571](https://linux-hardware.org/?probe=20f39c9571) | Aug 03, 2024 |
| ASUSTek       | M11BB                       | [e592af72e7](https://linux-hardware.org/?probe=e592af72e7) | Aug 03, 2024 |
| ASUSTek       | P8Z77-V DELUXE              | [d203ea4b82](https://linux-hardware.org/?probe=d203ea4b82) | Aug 03, 2024 |
| Intel         | Thurley                     | [9b879619e7](https://linux-hardware.org/?probe=9b879619e7) | Aug 03, 2024 |
| Dell          | 0FDY5C A00                  | [f494d1f180](https://linux-hardware.org/?probe=f494d1f180) | Aug 03, 2024 |
| Dell          | 0YXT71 A01                  | [afd697799b](https://linux-hardware.org/?probe=afd697799b) | Aug 03, 2024 |
| ASUSTek       | CM1735                      | [4422341690](https://linux-hardware.org/?probe=4422341690) | Aug 02, 2024 |
| Lenovo        | ThinkCentre M90 3246B8G     | [876613311e](https://linux-hardware.org/?probe=876613311e) | Aug 02, 2024 |
| MSI           | J1800I                      | [2d0100f3d6](https://linux-hardware.org/?probe=2d0100f3d6) | Aug 02, 2024 |
| MSI           | PRO B760-P WIFI             | [779bbdd8d5](https://linux-hardware.org/?probe=779bbdd8d5) | Aug 02, 2024 |
| MSI           | A68HM-P33 V2                | [fb213fe215](https://linux-hardware.org/?probe=fb213fe215) | Aug 02, 2024 |
| HP            | 859B                        | [172155a762](https://linux-hardware.org/?probe=172155a762) | Aug 01, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [8c20c8ffdd](https://linux-hardware.org/?probe=8c20c8ffdd) | Aug 01, 2024 |
| Lenovo        | NO DPK                      | [6cdf96758d](https://linux-hardware.org/?probe=6cdf96758d) | Aug 01, 2024 |
| MSI           | 760GMA-P34                  | [59404bc1cb](https://linux-hardware.org/?probe=59404bc1cb) | Aug 01, 2024 |
| ASUSTek       | P8H67-M EVO                 | [3340aefac7](https://linux-hardware.org/?probe=3340aefac7) | Aug 01, 2024 |
| Lenovo        | ThinkCentre M58p 6234CL2    | [024bb5ea7e](https://linux-hardware.org/?probe=024bb5ea7e) | Aug 01, 2024 |
| Lenovo        | ThinkCentre A70z 0401B7P    | [7501905c61](https://linux-hardware.org/?probe=7501905c61) | Aug 01, 2024 |
| ASRock        | A320M-DVS R4.0              | [babb217959](https://linux-hardware.org/?probe=babb217959) | Aug 01, 2024 |
| MSI           | MAG B560M BAZOOKA           | [b48e017338](https://linux-hardware.org/?probe=b48e017338) | Aug 01, 2024 |
| Unknown       | Unknown                     | [216b38851e](https://linux-hardware.org/?probe=216b38851e) | Aug 01, 2024 |
| Acer          | F690GVM                     | [5fd27036dc](https://linux-hardware.org/?probe=5fd27036dc) | Jul 31, 2024 |
| ASUSTek       | P5S800-VM                   | [e6528399e7](https://linux-hardware.org/?probe=e6528399e7) | Jul 31, 2024 |
| HP            | 8906 SMVB                   | [8071be19f2](https://linux-hardware.org/?probe=8071be19f2) | Jul 31, 2024 |
| HP            | 843B                        | [84ed801133](https://linux-hardware.org/?probe=84ed801133) | Jul 31, 2024 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [8fa3c3f741](https://linux-hardware.org/?probe=8fa3c3f741) | Jul 31, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [20184a147c](https://linux-hardware.org/?probe=20184a147c) | Jul 31, 2024 |
| Medion        | TJ4125                      | [1322129a3e](https://linux-hardware.org/?probe=1322129a3e) | Jul 31, 2024 |
| Biostar       | H61MLB                      | [10f695fe18](https://linux-hardware.org/?probe=10f695fe18) | Jul 31, 2024 |
| Pegatron      | 2AE4                        | [db698b9ba0](https://linux-hardware.org/?probe=db698b9ba0) | Jul 31, 2024 |
| ASRock        | H97 Anniversary             | [ec56437f32](https://linux-hardware.org/?probe=ec56437f32) | Jul 31, 2024 |
| HP            | 2AF7                        | [ff064ef8a1](https://linux-hardware.org/?probe=ff064ef8a1) | Jul 30, 2024 |
| BESSTAR Te... | HM80                        | [221169cf71](https://linux-hardware.org/?probe=221169cf71) | Jul 30, 2024 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [7cae6fbf9a](https://linux-hardware.org/?probe=7cae6fbf9a) | Jul 30, 2024 |
| ASUSTek       | H81M-K                      | [6c6387e423](https://linux-hardware.org/?probe=6c6387e423) | Jul 30, 2024 |
| ASUSTek       | Z97-PRO GAMER               | [3015220143](https://linux-hardware.org/?probe=3015220143) | Jul 30, 2024 |
| MSI           | PRO Z790-P WIFI             | [9a1c33177c](https://linux-hardware.org/?probe=9a1c33177c) | Jul 29, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [7374902608](https://linux-hardware.org/?probe=7374902608) | Jul 29, 2024 |
| ASUSTek       | PRIME H510M-E               | [9c7a6479d0](https://linux-hardware.org/?probe=9c7a6479d0) | Jul 29, 2024 |
| ASUSTek       | P8H61-M LX                  | [36182a6143](https://linux-hardware.org/?probe=36182a6143) | Jul 29, 2024 |
| ASUSTek       | P5Q-E                       | [38d1f56d89](https://linux-hardware.org/?probe=38d1f56d89) | Jul 29, 2024 |
| Biostar       | H61MGC                      | [e7b535b056](https://linux-hardware.org/?probe=e7b535b056) | Jul 29, 2024 |
| Gigabyte      | B550 GAMING X V2            | [a9d4f562c5](https://linux-hardware.org/?probe=a9d4f562c5) | Jul 29, 2024 |
| ECS           | H81M-C2H                    | [12a60ad494](https://linux-hardware.org/?probe=12a60ad494) | Jul 29, 2024 |
| ASRock        | X670E Steel Legend          | [0d8fe63707](https://linux-hardware.org/?probe=0d8fe63707) | Jul 29, 2024 |
| HP            | 0AE4h C                     | [56930a37ee](https://linux-hardware.org/?probe=56930a37ee) | Jul 29, 2024 |
| ASUSTek       | PRIME A520M-A II            | [06c22e8fac](https://linux-hardware.org/?probe=06c22e8fac) | Jul 28, 2024 |
| Intel         | B75                         | [5bc0fa4295](https://linux-hardware.org/?probe=5bc0fa4295) | Jul 28, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF       | [90b84331bc](https://linux-hardware.org/?probe=90b84331bc) | Jul 28, 2024 |
| ASRock        | AB350M-HDV R3.0             | [eeb99aca23](https://linux-hardware.org/?probe=eeb99aca23) | Jul 28, 2024 |
| HP            | 829D                        | [5f82ac1818](https://linux-hardware.org/?probe=5f82ac1818) | Jul 28, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [9b0b51426a](https://linux-hardware.org/?probe=9b0b51426a) | Jul 28, 2024 |
| Pegatron      | 2AF0                        | [92b0828da2](https://linux-hardware.org/?probe=92b0828da2) | Jul 28, 2024 |
| ASUSTek       | PRIME B550M-A               | [5ccfa4d635](https://linux-hardware.org/?probe=5ccfa4d635) | Jul 28, 2024 |
| ASUSTek       | P5G41T-M LX                 | [0f18c465ca](https://linux-hardware.org/?probe=0f18c465ca) | Jul 28, 2024 |
| Dell          | 0GDG8Y A00                  | [01a7bfd3d6](https://linux-hardware.org/?probe=01a7bfd3d6) | Jul 28, 2024 |
| HP            | 18E5                        | [12198bdc99](https://linux-hardware.org/?probe=12198bdc99) | Jul 28, 2024 |
| ASUSTek       | N3050I-C                    | [2a6d292b88](https://linux-hardware.org/?probe=2a6d292b88) | Jul 28, 2024 |
| HP            | 89B4 A                      | [f64a4f1aa1](https://linux-hardware.org/?probe=f64a4f1aa1) | Jul 27, 2024 |
| Gigabyte      | Z97M-D3H                    | [490e339872](https://linux-hardware.org/?probe=490e339872) | Jul 27, 2024 |
| ASUSTek       | PRIME B550M-K               | [0d3c21b355](https://linux-hardware.org/?probe=0d3c21b355) | Jul 27, 2024 |
| Dell          | 0T10XW A01                  | [e37e6d3743](https://linux-hardware.org/?probe=e37e6d3743) | Jul 27, 2024 |
| Gigabyte      | B450M GAMING                | [c6b8951769](https://linux-hardware.org/?probe=c6b8951769) | Jul 27, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [55c7359f80](https://linux-hardware.org/?probe=55c7359f80) | Jul 27, 2024 |
| ASRock        | X300M-STX                   | [c4a916c82e](https://linux-hardware.org/?probe=c4a916c82e) | Jul 27, 2024 |
| Foxconn       | 2ABF                        | [7cc7a40e85](https://linux-hardware.org/?probe=7cc7a40e85) | Jul 27, 2024 |
| ASRock        | B250 Pro4                   | [9c5d7ededd](https://linux-hardware.org/?probe=9c5d7ededd) | Jul 27, 2024 |
| MSI           | PRO Z690-A WIFI             | [e70ef4ad50](https://linux-hardware.org/?probe=e70ef4ad50) | Jul 27, 2024 |
| MSI           | B450 TOMAHAWK               | [e8db251f9e](https://linux-hardware.org/?probe=e8db251f9e) | Jul 27, 2024 |
| ASRock        | B550 Phantom Gaming 4/ac    | [be08e81120](https://linux-hardware.org/?probe=be08e81120) | Jul 27, 2024 |
| MSI           | B85M-E45                    | [b1c5a5abb6](https://linux-hardware.org/?probe=b1c5a5abb6) | Jul 27, 2024 |
| ASRock        | B760M-C                     | [39b34fc090](https://linux-hardware.org/?probe=39b34fc090) | Jul 27, 2024 |
| ASUSTek       | P8Z77-V LE PLUS             | [846aef9e97](https://linux-hardware.org/?probe=846aef9e97) | Jul 26, 2024 |
| HP            | 18E4                        | [8e7d36557d](https://linux-hardware.org/?probe=8e7d36557d) | Jul 26, 2024 |
| Pegatron      | 3580                        | [5ddaaa65f5](https://linux-hardware.org/?probe=5ddaaa65f5) | Jul 26, 2024 |
| ASUSTek       | M5A97 R2.0                  | [eaab2b6733](https://linux-hardware.org/?probe=eaab2b6733) | Jul 26, 2024 |
| ASUSTek       | PRIME H610M-A D4            | [b7ff387235](https://linux-hardware.org/?probe=b7ff387235) | Jul 26, 2024 |
| HP            | 8653 A                      | [b320ae12d2](https://linux-hardware.org/?probe=b320ae12d2) | Jul 26, 2024 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | [93a8017aa7](https://linux-hardware.org/?probe=93a8017aa7) | Jul 26, 2024 |
| ASUSTek       | M5A88-M                     | [5d3d3f7de7](https://linux-hardware.org/?probe=5d3d3f7de7) | Jul 26, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [18bbac33d1](https://linux-hardware.org/?probe=18bbac33d1) | Jul 26, 2024 |
| Biostar       | A68MD PRO                   | [2d33bbdbd9](https://linux-hardware.org/?probe=2d33bbdbd9) | Jul 25, 2024 |
| Gigabyte      | B85M-D3PH                   | [b4cc76793d](https://linux-hardware.org/?probe=b4cc76793d) | Jul 25, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [2d1bd9d543](https://linux-hardware.org/?probe=2d1bd9d543) | Jul 25, 2024 |
| ASUSTek       | H81M-K                      | [c7efb5f986](https://linux-hardware.org/?probe=c7efb5f986) | Jul 25, 2024 |
| ASRock        | Q1900M                      | [a91507fe3f](https://linux-hardware.org/?probe=a91507fe3f) | Jul 25, 2024 |
| Gigabyte      | G41M-Combo                  | [10adb31c02](https://linux-hardware.org/?probe=10adb31c02) | Jul 25, 2024 |
| Dell          | 042P49 A02                  | [46ca46385a](https://linux-hardware.org/?probe=46ca46385a) | Jul 25, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS       | [4e32c4d0df](https://linux-hardware.org/?probe=4e32c4d0df) | Jul 25, 2024 |
| ASUSTek       | A88XM-E/USB                 | [9cc6e54448](https://linux-hardware.org/?probe=9cc6e54448) | Jul 25, 2024 |
| HP            | 8767 A                      | [6e6335bf04](https://linux-hardware.org/?probe=6e6335bf04) | Jul 25, 2024 |
| ASUSTek       | H81M-D PLUS                 | [40787275bb](https://linux-hardware.org/?probe=40787275bb) | Jul 25, 2024 |
| ASUSTek       | PRIME Z690-P D4             | [7623e32d5d](https://linux-hardware.org/?probe=7623e32d5d) | Jul 25, 2024 |
| Intel         | H61/B75                     | [316cf38c13](https://linux-hardware.org/?probe=316cf38c13) | Jul 25, 2024 |
| Dell          | 0VHWTR A02                  | [6073fdcc24](https://linux-hardware.org/?probe=6073fdcc24) | Jul 25, 2024 |
| ASRock        | B450 Pro4                   | [48e164aa4e](https://linux-hardware.org/?probe=48e164aa4e) | Jul 25, 2024 |
| Gigabyte      | F2A68HM-H                   | [b3488f2839](https://linux-hardware.org/?probe=b3488f2839) | Jul 25, 2024 |
| ASUSTek       | B85M-G                      | [e34ef3a83c](https://linux-hardware.org/?probe=e34ef3a83c) | Jul 25, 2024 |
| MSI           | B350M GAMING PRO            | [2de872ecab](https://linux-hardware.org/?probe=2de872ecab) | Jul 24, 2024 |
| Dell          | 0YJPT1 A00                  | [e704325fc3](https://linux-hardware.org/?probe=e704325fc3) | Jul 24, 2024 |
| Dell          | 0X4H68 A00                  | [b0434de75f](https://linux-hardware.org/?probe=b0434de75f) | Jul 24, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [de715b8bd7](https://linux-hardware.org/?probe=de715b8bd7) | Jul 24, 2024 |
| Gigabyte      | H55M-S2H                    | [bc9baba360](https://linux-hardware.org/?probe=bc9baba360) | Jul 24, 2024 |
| Gigabyte      | Z97M-D3H                    | [d14ff2b99b](https://linux-hardware.org/?probe=d14ff2b99b) | Jul 24, 2024 |
| HP            | 82FE 11                     | [fe0843fe27](https://linux-hardware.org/?probe=fe0843fe27) | Jul 24, 2024 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [776835c3f3](https://linux-hardware.org/?probe=776835c3f3) | Jul 24, 2024 |
| MSI           | H61M-P21                    | [4e1acb5744](https://linux-hardware.org/?probe=4e1acb5744) | Jul 24, 2024 |
| Win Elemen... | S500+                       | [3aa986ddc3](https://linux-hardware.org/?probe=3aa986ddc3) | Jul 24, 2024 |
| ASRock        | B550M Pro4                  | [4e06715a28](https://linux-hardware.org/?probe=4e06715a28) | Jul 24, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | [a8ee725733](https://linux-hardware.org/?probe=a8ee725733) | Jul 24, 2024 |
| MSI           | B350 PC MATE                | [0b80ce71a7](https://linux-hardware.org/?probe=0b80ce71a7) | Jul 24, 2024 |
| Foxconn       | G41S/G41S-K                 | [23e38e3c70](https://linux-hardware.org/?probe=23e38e3c70) | Jul 24, 2024 |
| ASUSTek       | PRIME B450M-A II            | [187ba51872](https://linux-hardware.org/?probe=187ba51872) | Jul 24, 2024 |
| AMI           | Intel                       | [3a2452931b](https://linux-hardware.org/?probe=3a2452931b) | Jul 23, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [a912787dd0](https://linux-hardware.org/?probe=a912787dd0) | Jul 23, 2024 |
| ASUSTek       | PRIME H610M-D D4            | [5952505694](https://linux-hardware.org/?probe=5952505694) | Jul 23, 2024 |
| Gateway       | DX4380G                     | [c55a9746c1](https://linux-hardware.org/?probe=c55a9746c1) | Jul 23, 2024 |
| ASUSTek       | C8HM70-I/HDMI               | [559f53d88c](https://linux-hardware.org/?probe=559f53d88c) | Jul 23, 2024 |
| HP            | 89D8 SMVB                   | [1c42d3aa40](https://linux-hardware.org/?probe=1c42d3aa40) | Jul 23, 2024 |
| Dell          | 0HN7XN A01                  | [2e8b1aeb7b](https://linux-hardware.org/?probe=2e8b1aeb7b) | Jul 23, 2024 |
| MSI           | A320M PRO-VH PLUS           | [13e48f4585](https://linux-hardware.org/?probe=13e48f4585) | Jul 23, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [06ec7cb14f](https://linux-hardware.org/?probe=06ec7cb14f) | Jul 23, 2024 |
| Lenovo        | SHARKBAY 31900058 STD       | [ef8ec22b50](https://linux-hardware.org/?probe=ef8ec22b50) | Jul 23, 2024 |
| MSI           | 3664h                       | [176f9547b9](https://linux-hardware.org/?probe=176f9547b9) | Jul 23, 2024 |
| Dell          | 0J3C2F A02                  | [f92c77dcff](https://linux-hardware.org/?probe=f92c77dcff) | Jul 23, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [bde1d0c7b3](https://linux-hardware.org/?probe=bde1d0c7b3) | Jul 23, 2024 |
| Medion        | P2A4-EM                     | [c57d57693a](https://linux-hardware.org/?probe=c57d57693a) | Jul 23, 2024 |
| Gigabyte      | B650I AX                    | [37196d5c35](https://linux-hardware.org/?probe=37196d5c35) | Jul 23, 2024 |
| ASUSTek       | M5A97 R2.0                  | [46748aee2e](https://linux-hardware.org/?probe=46748aee2e) | Jul 23, 2024 |
| ASUSTek       | M5A78L-M LX/BR              | [604aa7f1d9](https://linux-hardware.org/?probe=604aa7f1d9) | Jul 23, 2024 |
| ASRock        | Q1900B-ITX                  | [56c6b1769a](https://linux-hardware.org/?probe=56c6b1769a) | Jul 23, 2024 |
| MSI           | B550 GAMING GEN3            | [f0ac757384](https://linux-hardware.org/?probe=f0ac757384) | Jul 23, 2024 |
| ASUSTek       | PRIME Z370-P                | [7a88a3f633](https://linux-hardware.org/?probe=7a88a3f633) | Jul 23, 2024 |
| Dell          | 0Y2K8N A00                  | [0a62fbdca2](https://linux-hardware.org/?probe=0a62fbdca2) | Jul 23, 2024 |
| ASUSTek       | PRIME B450M-A II            | [bccf1b55f8](https://linux-hardware.org/?probe=bccf1b55f8) | Jul 22, 2024 |
| OEM           | B75 Ver:1.41                | [3b478b5479](https://linux-hardware.org/?probe=3b478b5479) | Jul 22, 2024 |
| Dell          | 0773VG A00                  | [73c3f015d8](https://linux-hardware.org/?probe=73c3f015d8) | Jul 22, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ad39fa2a96](https://linux-hardware.org/?probe=ad39fa2a96) | Jul 22, 2024 |
| ASUSTek       | PRIME B550M-K               | [868bbd9678](https://linux-hardware.org/?probe=868bbd9678) | Jul 22, 2024 |
| Lenovo        | 312A NOK                    | [3f3e891da0](https://linux-hardware.org/?probe=3f3e891da0) | Jul 22, 2024 |
| Intel         | D2700MUD AAG32419-600       | [56ed1997d1](https://linux-hardware.org/?probe=56ed1997d1) | Jul 22, 2024 |
| MSI           | B550-A PRO                  | [3e1c632bab](https://linux-hardware.org/?probe=3e1c632bab) | Jul 22, 2024 |
| ASUSTek       | H81M-R 2016-11-08           | [db8577580d](https://linux-hardware.org/?probe=db8577580d) | Jul 22, 2024 |
| Gigabyte      | X570S AORUS MASTER          | [20256fa6c4](https://linux-hardware.org/?probe=20256fa6c4) | Jul 22, 2024 |
| HP            | 0AECh D                     | [f621cd0765](https://linux-hardware.org/?probe=f621cd0765) | Jul 22, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [bfa171bd46](https://linux-hardware.org/?probe=bfa171bd46) | Jul 22, 2024 |
| ASRock        | Z68 Extreme4                | [965282cb72](https://linux-hardware.org/?probe=965282cb72) | Jul 22, 2024 |
| Gigabyte      | B450M DS3H-CF               | [0da31e8c61](https://linux-hardware.org/?probe=0da31e8c61) | Jul 22, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [f713639426](https://linux-hardware.org/?probe=f713639426) | Jul 22, 2024 |
| MSI           | MS-7519                     | [cff49021a4](https://linux-hardware.org/?probe=cff49021a4) | Jul 22, 2024 |
| Gigabyte      | H61M-DS2                    | [31381d6558](https://linux-hardware.org/?probe=31381d6558) | Jul 22, 2024 |
| ASRock        | H61M-VG3                    | [0a662479ce](https://linux-hardware.org/?probe=0a662479ce) | Jul 22, 2024 |
| Foxconn       | 2ADA                        | [5278510d25](https://linux-hardware.org/?probe=5278510d25) | Jul 22, 2024 |
| ASUSTek       | TUF Gaming B550-PRO         | [7fc0f4fbae](https://linux-hardware.org/?probe=7fc0f4fbae) | Jul 22, 2024 |
| Intel         | DG41TX AAE78178-304         | [f08cf67507](https://linux-hardware.org/?probe=f08cf67507) | Jul 22, 2024 |
| AZW           | MINI S                      | [df3061eaed](https://linux-hardware.org/?probe=df3061eaed) | Jul 22, 2024 |
| Lenovo        | ThinkCentre M58p 6258CN9    | [2bab096c25](https://linux-hardware.org/?probe=2bab096c25) | Jul 22, 2024 |
| MSI           | B550-A PRO                  | [0799b17230](https://linux-hardware.org/?probe=0799b17230) | Jul 22, 2024 |
| MSI           | B350 TOMAHAWK               | [5136767f26](https://linux-hardware.org/?probe=5136767f26) | Jul 22, 2024 |
| HP            | 859B                        | [2126228654](https://linux-hardware.org/?probe=2126228654) | Jul 21, 2024 |
| ASRock        | H370M-HDV                   | [dc7d8bdae5](https://linux-hardware.org/?probe=dc7d8bdae5) | Jul 21, 2024 |
| Shenzhen M... | RPFXI                       | [13c9fe508b](https://linux-hardware.org/?probe=13c9fe508b) | Jul 21, 2024 |
| Pegatron      | IPXPV_PEGA                  | [bbd13dcad8](https://linux-hardware.org/?probe=bbd13dcad8) | Jul 21, 2024 |
| Dell          | 0WMJ54 A01                  | [7d8b8843e2](https://linux-hardware.org/?probe=7d8b8843e2) | Jul 21, 2024 |
| ASRock        | FM2A85X-ITX                 | [a84b46c611](https://linux-hardware.org/?probe=a84b46c611) | Jul 21, 2024 |
| Gigabyte      | X570 AORUS PRO              | [d5fe1f0257](https://linux-hardware.org/?probe=d5fe1f0257) | Jul 21, 2024 |
| Dell          | OptiPlex 980                | [9fcf584130](https://linux-hardware.org/?probe=9fcf584130) | Jul 21, 2024 |
| Dell          | 00V62H A00                  | [d2ea46cd2d](https://linux-hardware.org/?probe=d2ea46cd2d) | Jul 21, 2024 |
| ASRock        | Q1900B-ITX                  | [e321c98393](https://linux-hardware.org/?probe=e321c98393) | Jul 21, 2024 |
| ASRock        | B650E PG Riptide WiFi       | [9147c27d4c](https://linux-hardware.org/?probe=9147c27d4c) | Jul 21, 2024 |
| MACHINIST     | E5-RS9 V1.11                | [600603a9e5](https://linux-hardware.org/?probe=600603a9e5) | Jul 21, 2024 |
| MSI           | B450M PRO-VDH MAX           | [4c48e62929](https://linux-hardware.org/?probe=4c48e62929) | Jul 21, 2024 |
| MSI           | B550-A PRO                  | [9e4cb0afcf](https://linux-hardware.org/?probe=9e4cb0afcf) | Jul 21, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0c9e996233](https://linux-hardware.org/?probe=0c9e996233) | Jul 21, 2024 |
| MSI           | B350 TOMAHAWK               | [14fa80ba00](https://linux-hardware.org/?probe=14fa80ba00) | Jul 21, 2024 |
| HP            | 339A                        | [6e1df79914](https://linux-hardware.org/?probe=6e1df79914) | Jul 21, 2024 |
| Gigabyte      | A320M-S2H-CF                | [182e4201e2](https://linux-hardware.org/?probe=182e4201e2) | Jul 21, 2024 |
| HP            | 339A                        | [6fbdecb6eb](https://linux-hardware.org/?probe=6fbdecb6eb) | Jul 21, 2024 |
| HP            | 3397                        | [6b22b37ed0](https://linux-hardware.org/?probe=6b22b37ed0) | Jul 21, 2024 |
| MSI           | A320M-A PRO                 | [5716aad561](https://linux-hardware.org/?probe=5716aad561) | Jul 21, 2024 |
| Dell          | 0XD433 A01                  | [6a6432dd8a](https://linux-hardware.org/?probe=6a6432dd8a) | Jul 21, 2024 |
| Dell          | 0F3KHR A00                  | [df6c9a60e4](https://linux-hardware.org/?probe=df6c9a60e4) | Jul 21, 2024 |
| ASUSTek       | PRIME A320M-K               | [efa7cc7397](https://linux-hardware.org/?probe=efa7cc7397) | Jul 21, 2024 |
| Shenzhen M... | F7BFC                       | [0ef7da7cc6](https://linux-hardware.org/?probe=0ef7da7cc6) | Jul 21, 2024 |
| ASUSTek       | TUF X470-PLUS GAMING        | [027ce3ae0f](https://linux-hardware.org/?probe=027ce3ae0f) | Jul 21, 2024 |
| HP            | 8169                        | [d322f46532](https://linux-hardware.org/?probe=d322f46532) | Jul 20, 2024 |
| ASUSTek       | PRIME X570-P                | [a7365d3eef](https://linux-hardware.org/?probe=a7365d3eef) | Jul 20, 2024 |
| Gigabyte      | Z77-DS3H                    | [c60bdc0e69](https://linux-hardware.org/?probe=c60bdc0e69) | Jul 20, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [cb2c5a3de3](https://linux-hardware.org/?probe=cb2c5a3de3) | Jul 20, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | [c8cfbb067d](https://linux-hardware.org/?probe=c8cfbb067d) | Jul 19, 2024 |
| ASRock        | 970M Pro3                   | [c97f6147b5](https://linux-hardware.org/?probe=c97f6147b5) | Jul 19, 2024 |
| Unknown       | Unknown                     | [d26024a270](https://linux-hardware.org/?probe=d26024a270) | Jul 19, 2024 |
| MSI           | GF615M-P33 V2               | [1fdecde171](https://linux-hardware.org/?probe=1fdecde171) | Jul 19, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [e5c0f4c416](https://linux-hardware.org/?probe=e5c0f4c416) | Jul 18, 2024 |
| ASUSTek       | PRIME B450M-A               | [dc5dd56b57](https://linux-hardware.org/?probe=dc5dd56b57) | Jul 18, 2024 |
| HP            | 1905                        | [68b921574a](https://linux-hardware.org/?probe=68b921574a) | Jul 18, 2024 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | [e30a6efeaa](https://linux-hardware.org/?probe=e30a6efeaa) | Jul 17, 2024 |
| ASUSTek       | ROG Rampage VI APEX         | [d3f5eb9d56](https://linux-hardware.org/?probe=d3f5eb9d56) | Jul 17, 2024 |
| Acer          | Veriton X6610G              | [a0d69fd57d](https://linux-hardware.org/?probe=a0d69fd57d) | Jul 17, 2024 |
| Gigabyte      | B450M H                     | [a34fe7849f](https://linux-hardware.org/?probe=a34fe7849f) | Jul 16, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e12fd1c133](https://linux-hardware.org/?probe=e12fd1c133) | Jul 16, 2024 |
| Acer          | FI946GZG                    | [d84975220f](https://linux-hardware.org/?probe=d84975220f) | Jul 16, 2024 |
| Acer          | FI946GZG                    | [de385cf02c](https://linux-hardware.org/?probe=de385cf02c) | Jul 16, 2024 |
| Sapphire      | PI-AM3RS760G2               | [c48f0cc1b2](https://linux-hardware.org/?probe=c48f0cc1b2) | Jul 15, 2024 |
| ASUSTek       | P8H61-M PLUS V2             | [a520c62778](https://linux-hardware.org/?probe=a520c62778) | Jul 15, 2024 |
| Gigabyte      | B450M S2H                   | [4a98de88bd](https://linux-hardware.org/?probe=4a98de88bd) | Jul 14, 2024 |
| Gigabyte      | H61M-S1                     | [bc294c0d92](https://linux-hardware.org/?probe=bc294c0d92) | Jul 14, 2024 |
| ASUSTek       | PRIME Z690-P                | [3f5921afcf](https://linux-hardware.org/?probe=3f5921afcf) | Jul 14, 2024 |
| Dell          | 0T7787                      | [1cb4fdcd44](https://linux-hardware.org/?probe=1cb4fdcd44) | Jul 14, 2024 |
| Pegatron      | 2AB6                        | [0671cbc932](https://linux-hardware.org/?probe=0671cbc932) | Jul 14, 2024 |
| MSI           | 760GM-P33                   | [7180781cbd](https://linux-hardware.org/?probe=7180781cbd) | Jul 14, 2024 |
| HP            | 0A98h                       | [846c63b151](https://linux-hardware.org/?probe=846c63b151) | Jul 14, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [7bf4875374](https://linux-hardware.org/?probe=7bf4875374) | Jul 13, 2024 |
| Intel         | DP55WG AAE57269-405         | [0ae059999e](https://linux-hardware.org/?probe=0ae059999e) | Jul 13, 2024 |
| HP            | 8055                        | [63c43d59ee](https://linux-hardware.org/?probe=63c43d59ee) | Jul 13, 2024 |
| Unknown       | Unknown                     | [cdba4ff0e2](https://linux-hardware.org/?probe=cdba4ff0e2) | Jul 13, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [20ad848a34](https://linux-hardware.org/?probe=20ad848a34) | Jul 13, 2024 |
| Unknown       | Unknown                     | [7f104558f2](https://linux-hardware.org/?probe=7f104558f2) | Jul 12, 2024 |
| Acer          | EQ45LM                      | [b939357aca](https://linux-hardware.org/?probe=b939357aca) | Jul 12, 2024 |
| ASUSTek       | H81M-K                      | [a87baa98b1](https://linux-hardware.org/?probe=a87baa98b1) | Jul 11, 2024 |
| Gigabyte      | B450 AORUS M                | [741e243eb8](https://linux-hardware.org/?probe=741e243eb8) | Jul 11, 2024 |
| ASRock        | AM1B-ITX                    | [44cff7dc31](https://linux-hardware.org/?probe=44cff7dc31) | Jul 11, 2024 |
| HP            | 89B5 A                      | [f87a73cfdf](https://linux-hardware.org/?probe=f87a73cfdf) | Jul 11, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1c7ebc3219](https://linux-hardware.org/?probe=1c7ebc3219) | Jul 10, 2024 |
| OEM           | PB-1900-A                   | [afd45443ed](https://linux-hardware.org/?probe=afd45443ed) | Jul 10, 2024 |
| ASRock        | 4X4-4000 Series             | [6dc19b032a](https://linux-hardware.org/?probe=6dc19b032a) | Jul 09, 2024 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | [1467b57670](https://linux-hardware.org/?probe=1467b57670) | Jul 09, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | [e968a8de3d](https://linux-hardware.org/?probe=e968a8de3d) | Jul 09, 2024 |
| HP            | 3029h                       | [dc60c2ec0f](https://linux-hardware.org/?probe=dc60c2ec0f) | Jul 09, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [26e97b5e0f](https://linux-hardware.org/?probe=26e97b5e0f) | Jul 09, 2024 |
| MSI           | PRO X670-P WIFI             | [3620911b2d](https://linux-hardware.org/?probe=3620911b2d) | Jul 09, 2024 |
| Dell          | 0HR330                      | [045ab599e4](https://linux-hardware.org/?probe=045ab599e4) | Jul 09, 2024 |
| Dell          | 0WWJRX A00                  | [8bbce4ff81](https://linux-hardware.org/?probe=8bbce4ff81) | Jul 08, 2024 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [0e58bf4f05](https://linux-hardware.org/?probe=0e58bf4f05) | Jul 08, 2024 |
| ASUSTek       | P8H61-M LE                  | [c5cd42d27b](https://linux-hardware.org/?probe=c5cd42d27b) | Jul 08, 2024 |
| HP            | 843B                        | [8ca933fc1e](https://linux-hardware.org/?probe=8ca933fc1e) | Jul 08, 2024 |
| ASUSTek       | A58M-E                      | [fd43969147](https://linux-hardware.org/?probe=fd43969147) | Jul 08, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [b209c823f3](https://linux-hardware.org/?probe=b209c823f3) | Jul 08, 2024 |
| Dell          | 0UW457 A03                  | [ec2697a49e](https://linux-hardware.org/?probe=ec2697a49e) | Jul 08, 2024 |
| AZW           | MINI S 10                   | [5b0ef1d47d](https://linux-hardware.org/?probe=5b0ef1d47d) | Jul 08, 2024 |
| MSI           | A520M-A PRO                 | [33a580ff77](https://linux-hardware.org/?probe=33a580ff77) | Jul 07, 2024 |
| ASRock        | X570 Phantom Gaming X       | [c4be133df4](https://linux-hardware.org/?probe=c4be133df4) | Jul 07, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | [e502a2dc08](https://linux-hardware.org/?probe=e502a2dc08) | Jul 07, 2024 |
| ASUSTek       | F2A55                       | [4813318ff7](https://linux-hardware.org/?probe=4813318ff7) | Jul 07, 2024 |
| Gigabyte      | B650 GAMING X AX V2         | [6212edd10d](https://linux-hardware.org/?probe=6212edd10d) | Jul 07, 2024 |
| ASUSTek       | H97-PRO GAMER               | [5cef5a4211](https://linux-hardware.org/?probe=5cef5a4211) | Jul 07, 2024 |
| HP            | 0A54h                       | [fd9a2c9f64](https://linux-hardware.org/?probe=fd9a2c9f64) | Jul 07, 2024 |
| ASRock        | Wolfdale1333-D667           | [332046a9cf](https://linux-hardware.org/?probe=332046a9cf) | Jul 07, 2024 |
| ASUSTek       | H110M-A/M.2                 | [ddec5f335f](https://linux-hardware.org/?probe=ddec5f335f) | Jul 07, 2024 |
| Unknown       | Unknown                     | [648be3a154](https://linux-hardware.org/?probe=648be3a154) | Jul 07, 2024 |
| HP            | 1791                        | [734e987228](https://linux-hardware.org/?probe=734e987228) | Jul 07, 2024 |
| Dell          | 0CJ774                      | [e16d5db87f](https://linux-hardware.org/?probe=e16d5db87f) | Jul 07, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [8951b0838b](https://linux-hardware.org/?probe=8951b0838b) | Jul 06, 2024 |
| Dell          | 0TNDVR A00                  | [09a4251d80](https://linux-hardware.org/?probe=09a4251d80) | Jul 06, 2024 |
| HP            | 8265                        | [200db29eec](https://linux-hardware.org/?probe=200db29eec) | Jul 06, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [46bfdbb56c](https://linux-hardware.org/?probe=46bfdbb56c) | Jul 06, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [d83abb4ca3](https://linux-hardware.org/?probe=d83abb4ca3) | Jul 06, 2024 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [e5ddaba813](https://linux-hardware.org/?probe=e5ddaba813) | Jul 06, 2024 |
| MSI           | 2A78h                       | [2e3e93ad88](https://linux-hardware.org/?probe=2e3e93ad88) | Jul 06, 2024 |
| ASUSTek       | B85M-G R2.0                 | [d8a883892f](https://linux-hardware.org/?probe=d8a883892f) | Jul 06, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [269ac28107](https://linux-hardware.org/?probe=269ac28107) | Jul 06, 2024 |
| Dell          | 0JP3NX A01                  | [77b0cf9fa1](https://linux-hardware.org/?probe=77b0cf9fa1) | Jul 06, 2024 |
| ASUSTek       | P5KPL-AM/PS                 | [8abaff1afd](https://linux-hardware.org/?probe=8abaff1afd) | Jul 06, 2024 |
| HP            | 3646h                       | [3a80121b77](https://linux-hardware.org/?probe=3a80121b77) | Jul 06, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [a846e8b4be](https://linux-hardware.org/?probe=a846e8b4be) | Jul 06, 2024 |
| Foxconn       | 2AB1                        | [1b6f1c3941](https://linux-hardware.org/?probe=1b6f1c3941) | Jul 06, 2024 |
| Gigabyte      | H77-DS3H                    | [a8f057d1f5](https://linux-hardware.org/?probe=a8f057d1f5) | Jul 06, 2024 |
| ASRock        | 970A-G                      | [fb27f94c89](https://linux-hardware.org/?probe=fb27f94c89) | Jul 06, 2024 |
| Unknown       | 1.0                         | [fdefe5f9dd](https://linux-hardware.org/?probe=fdefe5f9dd) | Jul 06, 2024 |
| Gigabyte      | B650M AORUS ELITE AX ICE    | [8316fd10b5](https://linux-hardware.org/?probe=8316fd10b5) | Jul 06, 2024 |
| HP            | 3397                        | [cde03d49df](https://linux-hardware.org/?probe=cde03d49df) | Jul 06, 2024 |
| Intel         | H81                         | [1589b41012](https://linux-hardware.org/?probe=1589b41012) | Jul 06, 2024 |
| Lenovo        | ThinkCentre M58p 6138DK1    | [2602a6847c](https://linux-hardware.org/?probe=2602a6847c) | Jul 05, 2024 |
| HP            | 1998                        | [c7b5d3cfad](https://linux-hardware.org/?probe=c7b5d3cfad) | Jul 05, 2024 |
| Biostar       | B650MP-E PRO                | [6b198bdbb5](https://linux-hardware.org/?probe=6b198bdbb5) | Jul 05, 2024 |
| Lenovo        | ThinkServer TS140           | [b3c5f15f82](https://linux-hardware.org/?probe=b3c5f15f82) | Jul 05, 2024 |
| ASUSTek       | B85M-G                      | [c04bf86591](https://linux-hardware.org/?probe=c04bf86591) | Jul 05, 2024 |
| Dell          | 07KY25 A01                  | [a6b436cbf9](https://linux-hardware.org/?probe=a6b436cbf9) | Jul 05, 2024 |
| ZOTAC         | AMD M1                      | [7ea01675fd](https://linux-hardware.org/?probe=7ea01675fd) | Jul 05, 2024 |
| ASUSTek       | PRIME B360M-A               | [1131cc46f1](https://linux-hardware.org/?probe=1131cc46f1) | Jul 05, 2024 |
| Gigabyte      | X79-UD3                     | [b6357657fd](https://linux-hardware.org/?probe=b6357657fd) | Jul 05, 2024 |
| ASUSTek       | CM5570                      | [f3593970d5](https://linux-hardware.org/?probe=f3593970d5) | Jul 05, 2024 |
| MSI           | MAG B460M MORTAR WIFI       | [8669e80f71](https://linux-hardware.org/?probe=8669e80f71) | Jul 05, 2024 |
| Shenzhen M... | F7BFD                       | [1ec9a79700](https://linux-hardware.org/?probe=1ec9a79700) | Jul 05, 2024 |
| ASRock        | B650M-HDV/M.2               | [04118d726e](https://linux-hardware.org/?probe=04118d726e) | Jul 05, 2024 |
| Unknown       | Unknown                     | [cb00f80e55](https://linux-hardware.org/?probe=cb00f80e55) | Jul 05, 2024 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [475fe82289](https://linux-hardware.org/?probe=475fe82289) | Jul 05, 2024 |
| Packard Be... | IMEDIA S2870                | [c1420a2fb3](https://linux-hardware.org/?probe=c1420a2fb3) | Jul 05, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [7dbdb3d98e](https://linux-hardware.org/?probe=7dbdb3d98e) | Jul 05, 2024 |
| Intel         | DH55TC AAE70932-205         | [8b01a57584](https://linux-hardware.org/?probe=8b01a57584) | Jul 05, 2024 |
| PCWare        | PW-945GCX                   | [0143058d62](https://linux-hardware.org/?probe=0143058d62) | Jul 05, 2024 |
| MACHINIST     | X99 PR8                     | [c3c3e8293e](https://linux-hardware.org/?probe=c3c3e8293e) | Jul 05, 2024 |
| MSI           | B450M GAMING PLUS           | [0f9fec0186](https://linux-hardware.org/?probe=0f9fec0186) | Jul 04, 2024 |
| Lenovo        | MAHOBAY NOK                 | [c53c40a7c9](https://linux-hardware.org/?probe=c53c40a7c9) | Jul 04, 2024 |
| Dell          | 0D6H9T A00                  | [e50ae85e77](https://linux-hardware.org/?probe=e50ae85e77) | Jul 04, 2024 |
| ASUSTek       | P5QPL-AM                    | [22b2a4f5d4](https://linux-hardware.org/?probe=22b2a4f5d4) | Jul 04, 2024 |
| Dell          | 0D9C2N A00                  | [deebbb7529](https://linux-hardware.org/?probe=deebbb7529) | Jul 04, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [c05b0b91d0](https://linux-hardware.org/?probe=c05b0b91d0) | Jul 04, 2024 |
| HP            | 1825                        | [92ff06e3a1](https://linux-hardware.org/?probe=92ff06e3a1) | Jul 04, 2024 |
| ASUSTek       | M3N78-EM                    | [a9fbc7d2c7](https://linux-hardware.org/?probe=a9fbc7d2c7) | Jul 04, 2024 |
| ASRock        | X570 Taichi                 | [6c777ef35f](https://linux-hardware.org/?probe=6c777ef35f) | Jul 04, 2024 |
| Gigabyte      | G41MT-S2                    | [d468d4f9bd](https://linux-hardware.org/?probe=d468d4f9bd) | Jul 04, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | [67ef3d1c39](https://linux-hardware.org/?probe=67ef3d1c39) | Jul 04, 2024 |
| Shenzhen M... | AHBNB OEM                   | [c8c24da42a](https://linux-hardware.org/?probe=c8c24da42a) | Jul 04, 2024 |
| Lenovo        | 376A NOK                    | [600d2ffa34](https://linux-hardware.org/?probe=600d2ffa34) | Jul 04, 2024 |
| HP            | 0AA8h                       | [d757e2f98f](https://linux-hardware.org/?probe=d757e2f98f) | Jul 04, 2024 |
| ASUSTek       | P5B-VM SE                   | [516a348cbb](https://linux-hardware.org/?probe=516a348cbb) | Jul 04, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | [24d5092933](https://linux-hardware.org/?probe=24d5092933) | Jul 04, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [2df18d9d13](https://linux-hardware.org/?probe=2df18d9d13) | Jul 04, 2024 |
| ASUSTek       | P7H55                       | [f0077f14a2](https://linux-hardware.org/?probe=f0077f14a2) | Jul 04, 2024 |
| HP            | 0B4Ch D                     | [73621caa18](https://linux-hardware.org/?probe=73621caa18) | Jul 04, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_24.07/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.10.0-desktop-1omv2490       | 467      | 73.54%  |
| 6.9.7-desktop-1omv2490        | 132      | 20.79%  |
| 6.10.1-desktop-1omv2490       | 31       | 4.88%   |
| 6.11.0-desktop-2omv2490       | 2        | 0.31%   |
| 6.12.9-desktop-1omv2490       | 1        | 0.16%   |
| 6.10.0-desktop-gcc-1omv2490   | 1        | 0.16%   |
| 6.10.0-desktop-0.rc5.1omv2490 | 1        | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.10.0  | 469      | 73.86%  |
| 6.9.7   | 132      | 20.79%  |
| 6.10.1  | 31       | 4.88%   |
| 6.11.0  | 2        | 0.31%   |
| 6.12.9  | 1        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.10    | 500      | 78.74%  |
| 6.9     | 132      | 20.79%  |
| 6.11    | 2        | 0.31%   |
| 6.12    | 1        | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 634      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 401      | 62.75%  |
| LXQt    | 93       | 14.55%  |
| KDE6    | 67       | 10.49%  |
| GNOME   | 59       | 9.23%   |
| KDE5    | 16       | 2.5%    |
| XFCE    | 2        | 0.31%   |
| Budgie  | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 357      | 56.22%  |
| Wayland | 277      | 43.62%  |
| Unknown | 1        | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 572      | 90.08%  |
| GDM     | 60       | 9.45%   |
| LightDM | 2        | 0.31%   |
| Unknown | 1        | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 336      | 52.83%  |
| de_DE | 45       | 7.08%   |
| ru_RU | 43       | 6.76%   |
| pt_BR | 26       | 4.09%   |
| pl_PL | 26       | 4.09%   |
| it_IT | 26       | 4.09%   |
| fr_FR | 24       | 3.77%   |
| en_GB | 19       | 2.99%   |
| es_AR | 13       | 2.04%   |
| es_MX | 12       | 1.89%   |
| es_ES | 8        | 1.26%   |
| en_CA | 6        | 0.94%   |
| en_AU | 5        | 0.79%   |
| hu_HU | 4        | 0.63%   |
| cs_CZ | 4        | 0.63%   |
| fr_CH | 3        | 0.47%   |
| es_PE | 3        | 0.47%   |
| nl_NL | 2        | 0.31%   |
| nl_BE | 2        | 0.31%   |
| fr_BE | 2        | 0.31%   |
| es_CO | 2        | 0.31%   |
| en_NZ | 2        | 0.31%   |
| en_IN | 2        | 0.31%   |
| en_HK | 2        | 0.31%   |
| de_CH | 2        | 0.31%   |
| de_AT | 2        | 0.31%   |
| uk_UA | 1        | 0.16%   |
| tr_TR | 1        | 0.16%   |
| ro_RO | 1        | 0.16%   |
| pt_PT | 1        | 0.16%   |
| fr_LU | 1        | 0.16%   |
| fr_CA | 1        | 0.16%   |
| es_VE | 1        | 0.16%   |
| es_US | 1        | 0.16%   |
| es_PA | 1        | 0.16%   |
| es_GT | 1        | 0.16%   |
| es_DO | 1        | 0.16%   |
| en_ZA | 1        | 0.16%   |
| en_PH | 1        | 0.16%   |
| en_AG | 1        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 352      | 55.52%  |
| BIOS | 282      | 44.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Overlay | 421      | 66.09%  |
| Ext4    | 192      | 30.14%  |
| Btrfs   | 17       | 2.67%   |
| Xfs     | 4        | 0.63%   |
| F2fs    | 2        | 0.31%   |
| Ext3    | 1        | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 486      | 76.54%  |
| MBR  | 149      | 23.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 347      | 54.56%  |
| No        | 289      | 45.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 319      | 50.24%  |
| No        | 316      | 49.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 156      | 24.61%  |
| Gigabyte Technology                  | 91       | 14.35%  |
| MSI                                  | 67       | 10.57%  |
| Hewlett-Packard                      | 58       | 9.15%   |
| ASRock                               | 54       | 8.52%   |
| Dell                                 | 50       | 7.89%   |
| Lenovo                               | 31       | 4.89%   |
| Intel                                | 24       | 3.79%   |
| Unknown                              | 12       | 1.89%   |
| Fujitsu                              | 9        | 1.42%   |
| Foxconn                              | 9        | 1.42%   |
| Acer                                 | 9        | 1.42%   |
| Biostar                              | 8        | 1.26%   |
| Pegatron                             | 7        | 1.1%    |
| Shenzhen Meigao Electronic Equipment | 6        | 0.95%   |
| MACHINIST                            | 6        | 0.95%   |
| AZW                                  | 5        | 0.79%   |
| ZOTAC                                | 3        | 0.47%   |
| OEM                                  | 3        | 0.47%   |
| Positivo                             | 2        | 0.32%   |
| Medion                               | 2        | 0.32%   |
| BESSTAR Tech                         | 2        | 0.32%   |
| Apple                                | 2        | 0.32%   |
| Win Element                          | 1        | 0.16%   |
| Supermicro                           | 1        | 0.16%   |
| Sapphire                             | 1        | 0.16%   |
| Red Hat                              | 1        | 0.16%   |
| Ramsta                               | 1        | 0.16%   |
| Philco                               | 1        | 0.16%   |
| PCWare                               | 1        | 0.16%   |
| PCChips                              | 1        | 0.16%   |
| Packard Bell                         | 1        | 0.16%   |
| JGINYUE                              | 1        | 0.16%   |
| Huanan                               | 1        | 0.16%   |
| Gigabyte XTRJ Operations             | 1        | 0.16%   |
| Gateway                              | 1        | 0.16%   |
| Firebat_Computer                     | 1        | 0.16%   |
| ECS                                  | 1        | 0.16%   |
| Colorful Technology                  | 1        | 0.16%   |
| AMI                                  | 1        | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 18       | 2.84%   |
| Unknown                                    | 12       | 1.89%   |
| ASUS TUF Gaming X570-PLUS                  | 6        | 0.95%   |
| ASUS PRIME A320M-K                         | 6        | 0.95%   |
| MSI MS-7C56                                | 5        | 0.79%   |
| Intel B75                                  | 4        | 0.63%   |
| Dell OptiPlex 7010                         | 4        | 0.63%   |
| ASUS PRIME B450M-A II                      | 4        | 0.63%   |
| MSI MS-7C96                                | 3        | 0.47%   |
| MSI MS-7C91                                | 3        | 0.47%   |
| MSI MS-7C02                                | 3        | 0.47%   |
| MSI MS-7A38                                | 3        | 0.47%   |
| MSI MS-7A34                                | 3        | 0.47%   |
| MSI MS-7680                                | 3        | 0.47%   |
| MSI MS-7641                                | 3        | 0.47%   |
| MACHINIST X99 PR9-H                        | 3        | 0.47%   |
| HP Z400 Workstation                        | 3        | 0.47%   |
| Gigabyte X570 AORUS ELITE                  | 3        | 0.47%   |
| Gigabyte B550 AORUS ELITE V2               | 3        | 0.47%   |
| Gigabyte B450 AORUS ELITE                  | 3        | 0.47%   |
| Gigabyte AB350M-DS3H V2                    | 3        | 0.47%   |
| Dell OptiPlex 3020                         | 3        | 0.47%   |
| Dell OptiPlex 3010                         | 3        | 0.47%   |
| AZW MINI S                                 | 3        | 0.47%   |
| ASUS PRIME B550-PLUS                       | 3        | 0.47%   |
| ZOTAC NM10                                 | 2        | 0.32%   |
| Shenzhen Meigao Electronic Equipment UM690 | 2        | 0.32%   |
| MSI MS-7E06                                | 2        | 0.32%   |
| MSI MS-7D25                                | 2        | 0.32%   |
| MSI MS-7C95                                | 2        | 0.32%   |
| MSI MS-7C82                                | 2        | 0.32%   |
| MSI MS-7C75                                | 2        | 0.32%   |
| MSI MS-7B86                                | 2        | 0.32%   |
| Intel Jasper Lake Client Platform          | 2        | 0.32%   |
| Intel H61                                  | 2        | 0.32%   |
| HP ProDesk 400 G6 SFF                      | 2        | 0.32%   |
| HP Pavilion Desktop 590-p0xxx              | 2        | 0.32%   |
| HP EliteDesk 800 G2 DM 35W                 | 2        | 0.32%   |
| HP EliteDesk 800 G1 SFF                    | 2        | 0.32%   |
| HP Compaq Pro 6300 SFF                     | 2        | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 34       | 5.36%   |
| Dell OptiPlex        | 32       | 5.05%   |
| Lenovo ThinkCentre   | 23       | 3.63%   |
| ASUS All             | 18       | 2.84%   |
| ASUS TUF             | 17       | 2.68%   |
| ASUS ROG             | 17       | 2.68%   |
| HP Compaq            | 15       | 2.37%   |
| Unknown              | 12       | 1.89%   |
| HP EliteDesk         | 10       | 1.58%   |
| HP ProDesk           | 8        | 1.26%   |
| Gigabyte B450        | 7        | 1.1%    |
| Dell Inspiron        | 7        | 1.1%    |
| Acer Aspire          | 7        | 1.1%    |
| HP Pavilion          | 6        | 0.95%   |
| Gigabyte X570        | 6        | 0.95%   |
| Gigabyte B450M       | 6        | 0.95%   |
| MSI MS-7C56          | 5        | 0.79%   |
| Fujitsu ESPRIMO      | 5        | 0.79%   |
| ASUS M5A78L-M        | 5        | 0.79%   |
| ASRock X570          | 5        | 0.79%   |
| MACHINIST X99        | 4        | 0.63%   |
| Intel H61            | 4        | 0.63%   |
| Intel B75            | 4        | 0.63%   |
| Gigabyte B550        | 4        | 0.63%   |
| Foxconn Pro          | 4        | 0.63%   |
| Dell Precision       | 4        | 0.63%   |
| MSI MS-7C96          | 3        | 0.47%   |
| MSI MS-7C91          | 3        | 0.47%   |
| MSI MS-7C02          | 3        | 0.47%   |
| MSI MS-7A38          | 3        | 0.47%   |
| MSI MS-7A34          | 3        | 0.47%   |
| MSI MS-7680          | 3        | 0.47%   |
| MSI MS-7641          | 3        | 0.47%   |
| Lenovo IdeaCentre    | 3        | 0.47%   |
| HP Z400              | 3        | 0.47%   |
| Gigabyte AB350M-DS3H | 3        | 0.47%   |
| Dell XPS             | 3        | 0.47%   |
| AZW MINI             | 3        | 0.47%   |
| ASUS P8H61-M         | 3        | 0.47%   |
| ASUS M5A97           | 3        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 60       | 9.46%   |
| 2020 | 56       | 8.83%   |
| 2013 | 54       | 8.52%   |
| 2014 | 50       | 7.89%   |
| 2011 | 48       | 7.57%   |
| 2019 | 43       | 6.78%   |
| 2018 | 38       | 5.99%   |
| 2017 | 38       | 5.99%   |
| 2023 | 37       | 5.84%   |
| 2022 | 37       | 5.84%   |
| 2010 | 34       | 5.36%   |
| 2021 | 29       | 4.57%   |
| 2009 | 24       | 3.79%   |
| 2015 | 20       | 3.15%   |
| 2008 | 20       | 3.15%   |
| 2024 | 14       | 2.21%   |
| 2016 | 13       | 2.05%   |
| 2007 | 13       | 2.05%   |
| 2006 | 3        | 0.47%   |
| 2025 | 1        | 0.16%   |
| 2005 | 1        | 0.16%   |
| 2003 | 1        | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 634      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 634      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 633      | 99.84%  |
| Yes  | 1        | 0.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 151      | 23.82%  |
| 4.01-8.0    | 116      | 18.3%   |
| 8.01-16.0   | 115      | 18.14%  |
| 32.01-64.0  | 95       | 14.98%  |
| 3.01-4.0    | 88       | 13.88%  |
| 24.01-32.0  | 30       | 4.73%   |
| 64.01-256.0 | 26       | 4.1%    |
| 1.01-2.0    | 9        | 1.42%   |
| 2.01-3.0    | 4        | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 388      | 61.01%  |
| 2.01-3.0  | 121      | 19.03%  |
| 0.51-1.0  | 74       | 11.64%  |
| 3.01-4.0  | 25       | 3.93%   |
| 0.01-0.5  | 15       | 2.36%   |
| 4.01-8.0  | 12       | 1.89%   |
| 8.01-16.0 | 1        | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 243      | 38.15%  |
| 2      | 169      | 26.53%  |
| 3      | 98       | 15.38%  |
| 4      | 52       | 8.16%   |
| 5      | 24       | 3.77%   |
| 6      | 18       | 2.83%   |
| 0      | 17       | 2.67%   |
| 7      | 11       | 1.73%   |
| 8      | 3        | 0.47%   |
| 9      | 2        | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 346      | 54.57%  |
| Yes       | 288      | 45.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 627      | 98.9%   |
| No        | 7        | 1.1%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 376      | 59.21%  |
| Yes       | 259      | 40.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 434      | 68.35%  |
| Yes       | 201      | 31.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 100      | 15.77%  |
| Germany      | 61       | 9.62%   |
| Russia       | 56       | 8.83%   |
| Brazil       | 48       | 7.57%   |
| Poland       | 41       | 6.47%   |
| Italy        | 37       | 5.84%   |
| France       | 27       | 4.26%   |
| UK           | 18       | 2.84%   |
| Canada       | 17       | 2.68%   |
| Spain        | 16       | 2.52%   |
| Mexico       | 14       | 2.21%   |
| Australia    | 12       | 1.89%   |
| Argentina    | 11       | 1.74%   |
| Japan        | 10       | 1.58%   |
| Czechia      | 10       | 1.58%   |
| Romania      | 9        | 1.42%   |
| India        | 9        | 1.42%   |
| Sweden       | 7        | 1.1%    |
| Netherlands  | 7        | 1.1%    |
| Peru         | 6        | 0.95%   |
| Hungary      | 6        | 0.95%   |
| Austria      | 6        | 0.95%   |
| Switzerland  | 5        | 0.79%   |
| Philippines  | 5        | 0.79%   |
| Kazakhstan   | 5        | 0.79%   |
| Ukraine      | 4        | 0.63%   |
| Turkey       | 4        | 0.63%   |
| Serbia       | 4        | 0.63%   |
| Iran         | 4        | 0.63%   |
| Indonesia    | 4        | 0.63%   |
| Greece       | 4        | 0.63%   |
| China        | 4        | 0.63%   |
| Colombia     | 3        | 0.47%   |
| Bulgaria     | 3        | 0.47%   |
| Belgium      | 3        | 0.47%   |
| Belarus      | 3        | 0.47%   |
| UAE          | 2        | 0.32%   |
| Thailand     | 2        | 0.32%   |
| South Africa | 2        | 0.32%   |
| Slovenia     | 2        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| St Petersburg       | 8        | 1.26%   |
| Moscow              | 8        | 1.26%   |
| Milan               | 8        | 1.26%   |
| Vienna              | 4        | 0.63%   |
| Melbourne           | 4        | 0.63%   |
| Hamburg             | 4        | 0.63%   |
| Berlin              | 4        | 0.63%   |
| Uberlândia         | 3        | 0.47%   |
| Turin               | 3        | 0.47%   |
| Stuttgart           | 3        | 0.47%   |
| Shiraz              | 3        | 0.47%   |
| Sao Paulo           | 3        | 0.47%   |
| Rome                | 3        | 0.47%   |
| Prague              | 3        | 0.47%   |
| Buenos Aires        | 3        | 0.47%   |
| Brasília           | 3        | 0.47%   |
| Belgrade            | 3        | 0.47%   |
| Augsburg            | 3        | 0.47%   |
| Asheville           | 3        | 0.47%   |
| Almaty              | 3        | 0.47%   |
| Yokohama            | 2        | 0.31%   |
| Warsaw              | 2        | 0.31%   |
| Wald                | 2        | 0.31%   |
| Virginia Beach      | 2        | 0.31%   |
| Venice              | 2        | 0.31%   |
| Tokyo               | 2        | 0.31%   |
| Tampa               | 2        | 0.31%   |
| Stockholm           | 2        | 0.31%   |
| Sosnowiec           | 2        | 0.31%   |
| Singapore           | 2        | 0.31%   |
| Santa Fe            | 2        | 0.31%   |
| Saarbrücken        | 2        | 0.31%   |
| Rio de Janeiro      | 2        | 0.31%   |
| Rho                 | 2        | 0.31%   |
| Québec             | 2        | 0.31%   |
| Presidente Prudente | 2        | 0.31%   |
| Pompano Beach       | 2        | 0.31%   |
| Piaseczno           | 2        | 0.31%   |
| Parma               | 2        | 0.31%   |
| Panama City         | 2        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 183      | 223    | 15.19%  |
| Seagate                      | 164      | 204    | 13.61%  |
| Samsung Electronics          | 131      | 172    | 10.87%  |
| Sandisk                      | 74       | 85     | 6.14%   |
| Kingston                     | 73       | 89     | 6.06%   |
| Toshiba                      | 58       | 68     | 4.81%   |
| Crucial                      | 35       | 45     | 2.9%    |
| Hitachi                      | 31       | 32     | 2.57%   |
| China                        | 27       | 31     | 2.24%   |
| Phison Electronics           | 25       | 29     | 2.07%   |
| A-DATA Technology            | 22       | 24     | 1.83%   |
| Micron/Crucial Technology    | 18       | 22     | 1.49%   |
| Unknown                      | 16       | 26     | 1.33%   |
| ADATA Technology             | 16       | 18     | 1.33%   |
| Patriot                      | 15       | 15     | 1.24%   |
| Kingston Technology Company  | 15       | 16     | 1.24%   |
| MAXIO Technology (Hangzhou)  | 14       | 19     | 1.16%   |
| SK hynix                     | 12       | 16     | 1%      |
| Maxtor                       | 11       | 11     | 0.91%   |
| HGST                         | 11       | 11     | 0.91%   |
| Team                         | 10       | 11     | 0.83%   |
| Silicon Motion               | 10       | 12     | 0.83%   |
| PNY                          | 10       | 13     | 0.83%   |
| Intenso                      | 10       | 14     | 0.83%   |
| GOODRAM                      | 10       | 13     | 0.83%   |
| Apacer                       | 10       | 10     | 0.83%   |
| Realtek Semiconductor        | 9        | 9      | 0.75%   |
| SPCC                         | 8        | 9      | 0.66%   |
| JMicron Technology           | 8        | 8      | 0.66%   |
| Unknown                      | 8        | 9      | 0.66%   |
| Shenzhen Longsys Electronics | 7        | 8      | 0.58%   |
| Intel                        | 7        | 7      | 0.58%   |
| Realtek                      | 6        | 6      | 0.5%    |
| Netac                        | 6        | 7      | 0.5%    |
| Micron Technology            | 6        | 6      | 0.5%    |
| Transcend                    | 5        | 6      | 0.41%   |
| Mushkin                      | 4        | 4      | 0.33%   |
| LITEON                       | 4        | 4      | 0.33%   |
| Fanxiang                     | 4        | 4      | 0.33%   |
| Corsair                      | 4        | 4      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                  | 24       | 1.77%   |
| Seagate ST500DM002-1BD142 500GB                                    | 19       | 1.4%    |
| Kingston SA400S37480G 480GB SSD                                    | 17       | 1.26%   |
| Kingston SA400S37240G 240GB SSD                                    | 15       | 1.11%   |
| Toshiba DT01ACA100 1TB                                             | 12       | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB                                     | 12       | 0.89%   |
| Kingston SA400S37120G 120GB SSD                                    | 12       | 0.89%   |
| WDC WD10EZEX-08WN4A0 1TB                                           | 10       | 0.74%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                                | 10       | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB              | 9        | 0.67%   |
| Sandisk WD Blue SN570 1TB                                          | 9        | 0.67%   |
| Phison PS5013 E13 NVMe Controller 500GB                            | 9        | 0.67%   |
| Samsung SSD 860 EVO 500GB                                          | 8        | 0.59%   |
| Phison E12 NVMe Controller 1TB                                     | 8        | 0.59%   |
| Crucial CT500MX500SSD1 500GB                                       | 8        | 0.59%   |
| Unknown                                                            | 8        | 0.59%   |
| WDC WD20EZBX-00AYRA0 2TB                                           | 7        | 0.52%   |
| Seagate ST3500418AS 500GB                                          | 7        | 0.52%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB                   | 7        | 0.52%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB                   | 7        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                                        | 7        | 0.52%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 7        | 0.52%   |
| WDC WD10EZEX-00BN5A0 1TB                                           | 6        | 0.44%   |
| Seagate ST1000DM003-1SB102 1TB                                     | 6        | 0.44%   |
| Samsung SSD 850 EVO 250GB                                          | 6        | 0.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB               | 6        | 0.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                 | 6        | 0.44%   |
| Samsung HD103SI 1TB                                                | 6        | 0.44%   |
| Kingston Company SNV2S1000G 1TB                                    | 6        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                                   | 6        | 0.44%   |
| JMicron Generic 320GB                                              | 6        | 0.44%   |
| A-DATA SU650 240GB SSD                                             | 6        | 0.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                                     | 5        | 0.37%   |
| WDC WD5000AAKX-60U6AA0 500GB                                       | 5        | 0.37%   |
| Seagate ST2000DM008-2UB102 2TB                                     | 5        | 0.37%   |
| Seagate Expansion 2TB                                              | 5        | 0.37%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                              | 5        | 0.37%   |
| SanDisk SSD PLUS 240GB                                             | 5        | 0.37%   |
| Samsung SSD 980 500GB                                              | 5        | 0.37%   |
| Samsung SSD 860 EVO 1TB                                            | 5        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 167      | 196    | 34.01%  |
| Seagate             | 160      | 196    | 32.59%  |
| Toshiba             | 52       | 62     | 10.59%  |
| Hitachi             | 31       | 32     | 6.31%   |
| Samsung Electronics | 29       | 34     | 5.91%   |
| Maxtor              | 11       | 11     | 2.24%   |
| HGST                | 11       | 11     | 2.24%   |
| JMicron Technology  | 6        | 6      | 1.22%   |
| Unknown             | 5        | 5      | 1.02%   |
| ASMT                | 3        | 4      | 0.61%   |
| USB                 | 2        | 2      | 0.41%   |
| Fujitsu             | 2        | 2      | 0.41%   |
| WD MediaMax         | 1        | 1      | 0.2%    |
| USB3.0              | 1        | 1      | 0.2%    |
| TO Exter            | 1        | 1      | 0.2%    |
| PRO-T5              | 1        | 1      | 0.2%    |
| KESU                | 1        | 1      | 0.2%    |
| Intenso             | 1        | 2      | 0.2%    |
| Inateck             | 1        | 1      | 0.2%    |
| HGST HTS            | 1        | 1      | 0.2%    |
| Fantom              | 1        | 1      | 0.2%    |
| External            | 1        | 1      | 0.2%    |
| CIRAGO              | 1        | 1      | 0.2%    |
| Apple               | 1        | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 74       | 85     | 15.98%  |
| Kingston            | 56       | 68     | 12.1%   |
| Crucial             | 35       | 45     | 7.56%   |
| SanDisk             | 33       | 35     | 7.13%   |
| China               | 27       | 31     | 5.83%   |
| WDC                 | 24       | 27     | 5.18%   |
| A-DATA Technology   | 22       | 23     | 4.75%   |
| Patriot             | 14       | 14     | 3.02%   |
| Team                | 10       | 11     | 2.16%   |
| PNY                 | 10       | 13     | 2.16%   |
| GOODRAM             | 10       | 13     | 2.16%   |
| Apacer              | 10       | 10     | 2.16%   |
| Intenso             | 9        | 12     | 1.94%   |
| SPCC                | 8        | 9      | 1.73%   |
| Unknown             | 8        | 9      | 1.73%   |
| Netac               | 6        | 7      | 1.3%    |
| Transcend           | 5        | 6      | 1.08%   |
| Toshiba             | 5        | 5      | 1.08%   |
| Intel               | 5        | 5      | 1.08%   |
| LITEON              | 4        | 4      | 0.86%   |
| Corsair             | 4        | 4      | 0.86%   |
| Verbatim            | 3        | 3      | 0.65%   |
| Seagate             | 3        | 4      | 0.65%   |
| Plextor             | 3        | 3      | 0.65%   |
| Mushkin             | 3        | 3      | 0.65%   |
| Micron Technology   | 3        | 3      | 0.65%   |
| Lexar               | 3        | 3      | 0.65%   |
| KingSpec            | 3        | 3      | 0.65%   |
| HS-SSD-E100         | 3        | 3      | 0.65%   |
| walram              | 2        | 2      | 0.43%   |
| T-FORCE             | 2        | 2      | 0.43%   |
| OCZ                 | 2        | 2      | 0.43%   |
| LITEONIT            | 2        | 2      | 0.43%   |
| Leven               | 2        | 2      | 0.43%   |
| KingFast            | 2        | 2      | 0.43%   |
| Gigabyte Technology | 2        | 2      | 0.43%   |
| Drevo               | 2        | 2      | 0.43%   |
| XrayDisk            | 1        | 1      | 0.22%   |
| XPG                 | 1        | 1      | 0.22%   |
| Win Memory          | 1        | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 375      | 574    | 39.89%  |
| SSD     | 341      | 521    | 36.28%  |
| NVMe    | 203      | 303    | 21.6%   |
| Unknown | 19       | 28     | 2.02%   |
| MMC     | 2        | 2      | 0.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 551      | 1036   | 66.47%  |
| NVMe | 201      | 294    | 24.25%  |
| SAS  | 75       | 96     | 9.05%   |
| MMC  | 2        | 2      | 0.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 405      | 627    | 51.72%  |
| 0.51-1.0   | 241      | 297    | 30.78%  |
| 1.01-2.0   | 78       | 95     | 9.96%   |
| 3.01-4.0   | 25       | 32     | 3.19%   |
| 2.01-3.0   | 15       | 17     | 1.92%   |
| 4.01-10.0  | 14       | 21     | 1.79%   |
| 10.01-20.0 | 4        | 5      | 0.51%   |
| 20.01-50.0 | 1        | 1      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 251      | 39.28%  |
| 101-250        | 107      | 16.74%  |
| 251-500        | 85       | 13.3%   |
| 501-1000       | 45       | 7.04%   |
| Unknown        | 45       | 7.04%   |
| More than 3000 | 24       | 3.76%   |
| 51-100         | 24       | 3.76%   |
| 1001-2000      | 22       | 3.44%   |
| 21-50          | 20       | 3.13%   |
| 2001-3000      | 16       | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 446      | 70.02%  |
| Unknown        | 45       | 7.06%   |
| 0              | 36       | 5.65%   |
| 21-50          | 30       | 4.71%   |
| 101-250        | 20       | 3.14%   |
| 51-100         | 20       | 3.14%   |
| 501-1000       | 18       | 2.83%   |
| 251-500        | 11       | 1.73%   |
| 1001-2000      | 7        | 1.1%    |
| More than 3000 | 4        | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 9        | 9      | 4.21%   |
| Seagate ST3500418AS 500GB         | 5        | 5      | 2.34%   |
| Samsung Electronics HD161HJ 160GB | 4        | 4      | 1.87%   |
| Samsung Electronics HD103SI 1TB   | 4        | 4      | 1.87%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 3        | 3      | 1.4%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 3        | 3      | 1.4%    |
| WDC WD5000AAKS-00A7B2 500GB       | 3        | 3      | 1.4%    |
| WDC WD10EZEX-08WN4A0 1TB          | 3        | 3      | 1.4%    |
| WDC WD10EARS-00Y5B1 1TB           | 3        | 3      | 1.4%    |
| Seagate ST3500413AS 500GB         | 3        | 3      | 1.4%    |
| Seagate ST1000DM010-2EP102 1TB    | 3        | 4      | 1.4%    |
| WDC WD5000AAKX-75U6AA0 500GB      | 2        | 2      | 0.93%   |
| WDC WD5000AAKX-083CA1 500GB       | 2        | 2      | 0.93%   |
| WDC WD10EZEX-00BN5A0 1TB          | 2        | 2      | 0.93%   |
| Seagate ST3750640NS 752GB         | 2        | 2      | 0.93%   |
| Seagate ST1000DM003-9YN162 1TB    | 2        | 2      | 0.93%   |
| Seagate ST1000DM003-1SB102 1TB    | 2        | 2      | 0.93%   |
| Samsung Electronics HD642JJ 640GB | 2        | 2      | 0.93%   |
| Maxtor 6Y080L0 81GB               | 2        | 2      | 0.93%   |
| Hitachi HTS543232A7A384 320GB     | 2        | 2      | 0.93%   |
| Hitachi HDS721050CLA362 500GB     | 2        | 2      | 0.93%   |
| Hitachi HDS721010CLA332 1TB       | 2        | 2      | 0.93%   |
| Hitachi HDS721010CLA330 1TB       | 2        | 2      | 0.93%   |
| Hitachi HDP725050GLA360 500GB     | 2        | 2      | 0.93%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 1      | 0.47%   |
| WDC WD6400AAKS-65A7B2 640GB       | 1        | 1      | 0.47%   |
| WDC WD60PURZ-85ZUFY1 6TB          | 1        | 1      | 0.47%   |
| WDC WD60EFRX-68MYMN1 6TB          | 1        | 1      | 0.47%   |
| WDC WD50EZRX-00MVLB1 5TB          | 1        | 1      | 0.47%   |
| WDC WD5000BEVT-22A0RT0 500GB      | 1        | 1      | 0.47%   |
| WDC WD5000AVCS-632DY1 500GB       | 1        | 1      | 0.47%   |
| WDC WD5000AAVS-57ZTB0 500GB       | 1        | 1      | 0.47%   |
| WDC WD5000AAKX-221CA1 500GB       | 1        | 2      | 0.47%   |
| WDC WD5000AAKX-00KJ3A0 500GB      | 1        | 1      | 0.47%   |
| WDC WD5000AAKS-00WWPA0 500GB      | 1        | 1      | 0.47%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 1      | 0.47%   |
| WDC WD3200LPVT-22G33T0 320GB      | 1        | 1      | 0.47%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 0.47%   |
| WDC WD3200AAJS-56M0A0 320GB       | 1        | 1      | 0.47%   |
| WDC WD30EZRX-00DC0B0 3TB          | 1        | 1      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 56       | 60     | 27.05%  |
| Seagate               | 55       | 61     | 26.57%  |
| Samsung Electronics   | 21       | 23     | 10.14%  |
| Hitachi               | 16       | 17     | 7.73%   |
| Toshiba               | 10       | 10     | 4.83%   |
| Maxtor                | 7        | 7      | 3.38%   |
| A-DATA Technology     | 7        | 7      | 3.38%   |
| SanDisk               | 4        | 4      | 1.93%   |
| Realtek Semiconductor | 3        | 3      | 1.45%   |
| Netac                 | 3        | 3      | 1.45%   |
| Intel                 | 3        | 3      | 1.45%   |
| HGST                  | 3        | 3      | 1.45%   |
| Kingston              | 2        | 2      | 0.97%   |
| China                 | 2        | 2      | 0.97%   |
| WD MediaMax           | 1        | 1      | 0.48%   |
| T-FORCE               | 1        | 1      | 0.48%   |
| Patriot               | 1        | 1      | 0.48%   |
| OCZ                   | 1        | 1      | 0.48%   |
| MCTECH                | 1        | 1      | 0.48%   |
| LITEONIT              | 1        | 1      | 0.48%   |
| HGST HTS              | 1        | 1      | 0.48%   |
| Fujitsu               | 1        | 1      | 0.48%   |
| faspeed               | 1        | 1      | 0.48%   |
| Drevo                 | 1        | 1      | 0.48%   |
| Crucial               | 1        | 1      | 0.48%   |
| Corsair               | 1        | 1      | 0.48%   |
| Apple                 | 1        | 1      | 0.48%   |
| ADATA Technology      | 1        | 1      | 0.48%   |
| Unknown               | 1        | 1      | 0.48%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 55       | 61     | 33.74%  |
| WDC                 | 53       | 57     | 32.52%  |
| Hitachi             | 16       | 17     | 9.82%   |
| Samsung Electronics | 15       | 16     | 9.2%    |
| Toshiba             | 10       | 10     | 6.13%   |
| Maxtor              | 7        | 7      | 4.29%   |
| HGST                | 3        | 3      | 1.84%   |
| WD MediaMax         | 1        | 1      | 0.61%   |
| HGST HTS            | 1        | 1      | 0.61%   |
| Fujitsu             | 1        | 1      | 0.61%   |
| Apple               | 1        | 1      | 0.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 145      | 175    | 77.13%  |
| SSD  | 37       | 39     | 19.68%  |
| NVMe | 6        | 6      | 3.19%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD1600AAJS-00L7A0 160GB                      | 1        | 1      | 33.33%  |
| WDC WD10EZEX-08WN4A0 1TB                         | 1        | 1      | 33.33%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 66.67%  |
| Samsung Electronics | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 538      | 1124   | 68.54%  |
| Malfunc  | 181      | 220    | 23.06%  |
| Detected | 63       | 81     | 8.03%   |
| Failed   | 3        | 3      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 375      | 40.24%  |
| AMD                              | 240      | 25.75%  |
| SanDisk                          | 44       | 4.72%   |
| Samsung Electronics              | 43       | 4.61%   |
| Kingston Technology Company      | 35       | 3.76%   |
| Phison Electronics               | 25       | 2.68%   |
| ASMedia Technology               | 23       | 2.47%   |
| Micron/Crucial Technology        | 18       | 1.93%   |
| ADATA Technology                 | 17       | 1.82%   |
| Marvell Technology Group         | 16       | 1.72%   |
| MAXIO Technology (Hangzhou)      | 14       | 1.5%    |
| SK hynix                         | 11       | 1.18%   |
| JMicron Technology               | 11       | 1.18%   |
| Silicon Motion                   | 10       | 1.07%   |
| Realtek Semiconductor            | 9        | 0.97%   |
| Shenzhen Longsys Electronics     | 7        | 0.75%   |
| Nvidia                           | 6        | 0.64%   |
| Micron Technology                | 3        | 0.32%   |
| KIOXIA                           | 3        | 0.32%   |
| INNOGRIT                         | 3        | 0.32%   |
| VIA Technologies                 | 2        | 0.21%   |
| Solidigm                         | 2        | 0.21%   |
| Hosin Global Electronics         | 2        | 0.21%   |
| Toshiba America Info Systems     | 1        | 0.11%   |
| Sony                             | 1        | 0.11%   |
| Solid State Storage Technology   | 1        | 0.11%   |
| Silicon Integrated Systems [SiS] | 1        | 0.11%   |
| Silicon Image                    | 1        | 0.11%   |
| Seagate Technology               | 1        | 0.11%   |
| LSI Logic / Symbios Logic        | 1        | 0.11%   |
| Lenovo                           | 1        | 0.11%   |
| Integrated Technology Express    | 1        | 0.11%   |
| Broadcom / LSI                   | 1        | 0.11%   |
| Biwin Storage Technology         | 1        | 0.11%   |
| Artop Electronic                 | 1        | 0.11%   |
| Unknown                          | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 116      | 10.27%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 63       | 5.58%   |
| AMD 500 Series Chipset SATA Controller                                                  | 46       | 4.07%   |
| AMD 400 Series Chipset SATA Controller                                                  | 45       | 3.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 38       | 3.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 30       | 2.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 29       | 2.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 24       | 2.12%   |
| AMD 600 Series Chipset SATA Controller                                                  | 23       | 2.04%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 22       | 1.95%   |
| Intel SATA Controller [RAID mode]                                                       | 21       | 1.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 20       | 1.77%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 19       | 1.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 19       | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17       | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 16       | 1.42%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 16       | 1.42%   |
| AMD 300 Series Chipset SATA Controller                                                  | 15       | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14       | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14       | 1.24%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13       | 1.15%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 12       | 1.06%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                    | 11       | 0.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 0.97%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 10       | 0.88%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 9        | 0.8%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 9        | 0.8%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 9        | 0.8%    |
| Phison E12 NVMe Controller                                                              | 8        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8        | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8        | 0.71%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 7        | 0.62%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                                | 7        | 0.62%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 7        | 0.62%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 7        | 0.62%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 0.62%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 7        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 523      | 58.96%  |
| NVMe | 201      | 22.66%  |
| IDE  | 123      | 13.87%  |
| RAID | 35       | 3.95%   |
| SCSI | 3        | 0.34%   |
| SAS  | 2        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 379      | 59.78%  |
| AMD    | 255      | 40.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 15       | 2.37%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 14       | 2.21%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 14       | 2.21%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 11       | 1.74%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 10       | 1.58%   |
| AMD Ryzen 5 3600 6-Core Processor           | 10       | 1.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 8        | 1.26%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 8        | 1.26%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 8        | 1.26%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 8        | 1.26%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 8        | 1.26%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 7        | 1.1%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 0.95%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 6        | 0.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 0.79%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 5        | 0.79%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 5        | 0.79%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 5        | 0.79%   |
| Intel N100                                  | 4        | 0.63%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 0.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 0.63%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 4        | 0.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 0.63%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 0.63%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 4        | 0.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 0.63%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 4        | 0.63%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 4        | 0.63%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 4        | 0.63%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 4        | 0.63%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 4        | 0.63%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 0.63%   |
| AMD Ryzen 5 5500                            | 4        | 0.63%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 4        | 0.63%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 0.63%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 3        | 0.47%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 3        | 0.47%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 0.47%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 0.47%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 3        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 103      | 16.25%  |
| AMD Ryzen 5             | 73       | 11.51%  |
| AMD Ryzen 7             | 58       | 9.15%   |
| Intel Core i3           | 52       | 8.2%    |
| Intel Core i7           | 51       | 8.04%   |
| Intel Celeron           | 34       | 5.36%   |
| Other                   | 31       | 4.89%   |
| Intel Xeon              | 27       | 4.26%   |
| AMD Ryzen 9             | 23       | 3.63%   |
| Intel Pentium           | 19       | 3%      |
| Intel Core 2 Duo        | 19       | 3%      |
| Intel Core 2 Quad       | 15       | 2.37%   |
| AMD FX                  | 14       | 2.21%   |
| AMD Ryzen 3             | 13       | 2.05%   |
| Intel Pentium Dual-Core | 10       | 1.58%   |
| AMD A10                 | 9        | 1.42%   |
| AMD Athlon II X2        | 7        | 1.1%    |
| AMD A4                  | 7        | 1.1%    |
| AMD A8                  | 6        | 0.95%   |
| Intel Pentium Gold      | 5        | 0.79%   |
| Intel Atom              | 5        | 0.79%   |
| AMD Phenom II X4        | 5        | 0.79%   |
| AMD Athlon              | 5        | 0.79%   |
| Intel Pentium Dual      | 3        | 0.47%   |
| AMD Ryzen 5 PRO         | 3        | 0.47%   |
| AMD Athlon X4           | 3        | 0.47%   |
| AMD Athlon II X3        | 3        | 0.47%   |
| AMD Athlon 64 X2        | 3        | 0.47%   |
| AMD A6                  | 3        | 0.47%   |
| Intel Pentium D         | 2        | 0.32%   |
| Intel Core 2            | 2        | 0.32%   |
| AMD Sempron             | 2        | 0.32%   |
| AMD PRO A10             | 2        | 0.32%   |
| AMD E                   | 2        | 0.32%   |
| AMD Athlon X2           | 2        | 0.32%   |
| AMD Athlon II X4        | 2        | 0.32%   |
| AMD Athlon 64           | 2        | 0.32%   |
| Intel Pentium 4         | 1        | 0.16%   |
| Intel Core i9           | 1        | 0.16%   |
| AMD Ryzen 7 PRO         | 1        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 233      | 36.75%  |
| 2      | 163      | 25.71%  |
| 6      | 102      | 16.09%  |
| 8      | 77       | 12.15%  |
| 12     | 19       | 3%      |
| 16     | 15       | 2.37%   |
| 1      | 8        | 1.26%   |
| 10     | 6        | 0.95%   |
| 24     | 5        | 0.79%   |
| 3      | 3        | 0.47%   |
| 14     | 2        | 0.32%   |
| 20     | 1        | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 623      | 98.26%  |
| 2      | 9        | 1.42%   |
| 4      | 2        | 0.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 332      | 52.37%  |
| 1      | 302      | 47.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 634      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 634      | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 82       | 12.93%  |
| Zen 3            | 69       | 10.88%  |
| IvyBridge        | 57       | 8.99%   |
| SandyBridge      | 43       | 6.78%   |
| Penryn           | 41       | 6.47%   |
| KabyLake         | 33       | 5.21%   |
| Zen+             | 31       | 4.89%   |
| Zen 2            | 31       | 4.89%   |
| Unknown          | 30       | 4.73%   |
| Alderlake Hybrid | 28       | 4.42%   |
| Piledriver       | 26       | 4.1%    |
| K10              | 21       | 3.31%   |
| Westmere         | 17       | 2.68%   |
| Zen              | 15       | 2.37%   |
| Silvermont       | 11       | 1.74%   |
| Core             | 11       | 1.74%   |
| CometLake        | 11       | 1.74%   |
| Steamroller      | 10       | 1.58%   |
| Skylake          | 8        | 1.26%   |
| Excavator        | 7        | 1.1%    |
| Nehalem          | 6        | 0.95%   |
| Gracemont        | 6        | 0.95%   |
| Goldmont plus    | 6        | 0.95%   |
| K8 Hammer        | 5        | 0.79%   |
| Bonnell          | 5        | 0.79%   |
| Tremont          | 4        | 0.63%   |
| NetBurst         | 4        | 0.63%   |
| Bobcat           | 4        | 0.63%   |
| Jaguar           | 3        | 0.47%   |
| Goldmont         | 3        | 0.47%   |
| Broadwell        | 3        | 0.47%   |
| Bulldozer        | 2        | 0.32%   |
| K10 Llano        | 1        | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| AMD                              | 239      | 35.83%  |
| Intel                            | 230      | 34.48%  |
| Nvidia                           | 196      | 29.39%  |
| Silicon Integrated Systems [SiS] | 1        | 0.15%   |
| Red Hat                          | 1        | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 41       | 5.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 30       | 4.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 29       | 4.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 20       | 2.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 17       | 2.48%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 17       | 2.48%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 15       | 2.19%   |
| AMD Raphael                                                                 | 15       | 2.19%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 13       | 1.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 1.75%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 10       | 1.46%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 10       | 1.46%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 9        | 1.31%   |
| Nvidia GK208B [GeForce GT 730]                                              | 9        | 1.31%   |
| Nvidia GK208B [GeForce GT 710]                                              | 9        | 1.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 1.31%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 8        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 8        | 1.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 8        | 1.17%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 8        | 1.17%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 1.02%   |
| Nvidia GF108 [GeForce GT 730]                                               | 7        | 1.02%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 1.02%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 7        | 1.02%   |
| AMD RS780L [Radeon 3000]                                                    | 7        | 1.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 1.02%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 7        | 1.02%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 6        | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 0.87%   |
| Nvidia GF119 [GeForce GT 610]                                               | 6        | 0.87%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 6        | 0.87%   |
| Intel Core Processor Integrated Graphics Controller                         | 6        | 0.87%   |
| AMD Phoenix1                                                                | 6        | 0.87%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 6        | 0.87%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 6        | 0.87%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 6        | 0.87%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 6        | 0.87%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 6        | 0.87%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 0.73%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 5        | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 206      | 32.49%  |
| 1 x Intel      | 187      | 29.5%   |
| 1 x Nvidia     | 173      | 27.29%  |
| 2 x AMD        | 17       | 2.68%   |
| Intel + Nvidia | 17       | 2.68%   |
| 2 x Intel      | 14       | 2.21%   |
| Intel + AMD    | 12       | 1.89%   |
| AMD + Nvidia   | 4        | 0.63%   |
| 2 x Nvidia     | 2        | 0.32%   |
| 1 x SiS        | 1        | 0.16%   |
| 1 x Red Hat    | 1        | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 584      | 92.11%  |
| Unknown     | 41       | 6.47%   |
| Proprietary | 9        | 1.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 223      | 35.17%  |
| 1.01-2.0   | 86       | 13.56%  |
| 3.01-4.0   | 73       | 11.51%  |
| 0.01-0.5   | 73       | 11.51%  |
| 0.51-1.0   | 64       | 10.09%  |
| 7.01-8.0   | 63       | 9.94%   |
| 8.01-16.0  | 28       | 4.42%   |
| 5.01-6.0   | 9        | 1.42%   |
| 16.01-24.0 | 8        | 1.26%   |
| 2.01-3.0   | 6        | 0.95%   |
| 4.01-5.0   | 1        | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 115      | 18.34%  |
| Goldstar             | 63       | 10.05%  |
| Dell                 | 52       | 8.29%   |
| Hewlett-Packard      | 50       | 7.97%   |
| Acer                 | 40       | 6.38%   |
| Philips              | 36       | 5.74%   |
| AOC                  | 35       | 5.58%   |
| Ancor Communications | 26       | 4.15%   |
| Iiyama               | 18       | 2.87%   |
| BenQ                 | 18       | 2.87%   |
| ASUSTek Computer     | 15       | 2.39%   |
| ViewSonic            | 14       | 2.23%   |
| Lenovo               | 14       | 2.23%   |
| NEC Computers        | 8        | 1.28%   |
| Sony                 | 7        | 1.12%   |
| MSI                  | 7        | 1.12%   |
| Toshiba              | 6        | 0.96%   |
| Eizo                 | 6        | 0.96%   |
| RTK                  | 5        | 0.8%    |
| Gigabyte Technology  | 4        | 0.64%   |
| Belinea              | 4        | 0.64%   |
| Unknown (XXX)        | 3        | 0.48%   |
| Unknown              | 3        | 0.48%   |
| Sharp                | 3        | 0.48%   |
| Medion               | 3        | 0.48%   |
| Hitachi              | 3        | 0.48%   |
| Fujitsu Siemens      | 3        | 0.48%   |
| VIE                  | 2        | 0.32%   |
| SKG                  | 2        | 0.32%   |
| SGT                  | 2        | 0.32%   |
| Sceptre Tech         | 2        | 0.32%   |
| OEM                  | 2        | 0.32%   |
| Mi                   | 2        | 0.32%   |
| InnoLux Display      | 2        | 0.32%   |
| HUAWEI               | 2        | 0.32%   |
| GDH                  | 2        | 0.32%   |
| AXV                  | 2        | 0.32%   |
| ___                  | 1        | 0.16%   |
| Yuraku               | 1        | 0.16%   |
| Westinghouse         | 1        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                    | 4        | 0.62%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 3        | 0.47%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch     | 3        | 0.47%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 3        | 0.47%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3        | 0.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 0.47%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                   | 3        | 0.47%   |
| Goldstar 32inch FHD GSM76F5 1920x1080 698x392mm 31.5-inch             | 3        | 0.47%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 3        | 0.47%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 3        | 0.47%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch             | 2        | 0.31%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2        | 0.31%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 2        | 0.31%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 2        | 0.31%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 2        | 0.31%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 2        | 0.31%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch  | 2        | 0.31%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 2        | 0.31%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 2        | 0.31%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 0.31%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 0.31%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 2        | 0.31%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch               | 2        | 0.31%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2        | 0.31%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 2        | 0.31%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 2        | 0.31%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 2        | 0.31%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 476x268mm 21.5-inch              | 2        | 0.31%   |
| Iiyama PLT2254 IVM5656 1920x1080 480x270mm 21.7-inch                  | 2        | 0.31%   |
| Iiyama PLT2254 IVM5655 1920x1080 476x268mm 21.5-inch                  | 2        | 0.31%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 2        | 0.31%   |
| Iiyama PL2475HD IVM6108 1920x1080 521x293mm 23.5-inch                 | 2        | 0.31%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch               | 2        | 0.31%   |
| Hewlett-Packard w2007 HWP26A6 1680x1050 433x271mm 20.1-inch           | 2        | 0.31%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 2        | 0.31%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 2        | 0.31%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 2        | 0.31%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 597x336mm 27.0-inch        | 2        | 0.31%   |
| GDH TV PHILCO GDH0030 1920x540                                        | 2        | 0.31%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 2        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 310      | 50.24%  |
| 3840x2160 (4K)     | 56       | 9.08%   |
| 2560x1440 (QHD)    | 50       | 8.1%    |
| 1280x1024 (SXGA)   | 39       | 6.32%   |
| 1680x1050 (WSXGA+) | 26       | 4.21%   |
| 1440x900 (WXGA+)   | 25       | 4.05%   |
| 1366x768 (WXGA)    | 25       | 4.05%   |
| 1920x1200 (WUXGA)  | 23       | 3.73%   |
| 1600x900 (HD+)     | 15       | 2.43%   |
| 3440x1440          | 12       | 1.94%   |
| 1360x768           | 11       | 1.78%   |
| 2560x1080          | 6        | 0.97%   |
| 1600x1200          | 4        | 0.65%   |
| 3840x1080          | 3        | 0.49%   |
| 2288x1287          | 2        | 0.32%   |
| 1920x540           | 2        | 0.32%   |
| 3840x2560          | 1        | 0.16%   |
| 3840x1200          | 1        | 0.16%   |
| 2560x1397          | 1        | 0.16%   |
| 2160x1440          | 1        | 0.16%   |
| 1920x1440          | 1        | 0.16%   |
| 1280x720 (HD)      | 1        | 0.16%   |
| 1152x864           | 1        | 0.16%   |
| 1024x768 (XGA)     | 1        | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 105      | 16.59%  |
| 24      | 90       | 14.22%  |
| 21      | 82       | 12.95%  |
| 23      | 77       | 12.16%  |
| 19      | 47       | 7.42%   |
| 31      | 32       | 5.06%   |
| 18      | 32       | 5.06%   |
| 20      | 25       | 3.95%   |
| 22      | 17       | 2.69%   |
| 17      | 16       | 2.53%   |
| 34      | 15       | 2.37%   |
| 32      | 12       | 1.9%    |
| 15      | 9        | 1.42%   |
| 72      | 8        | 1.26%   |
| 54      | 7        | 1.11%   |
| 84      | 6        | 0.95%   |
| 52      | 6        | 0.95%   |
| 29      | 5        | 0.79%   |
| 25      | 5        | 0.79%   |
| 65      | 3        | 0.47%   |
| 63      | 3        | 0.47%   |
| 40      | 3        | 0.47%   |
| 28      | 3        | 0.47%   |
| Unknown | 3        | 0.47%   |
| 142     | 2        | 0.32%   |
| 49      | 2        | 0.32%   |
| 48      | 2        | 0.32%   |
| 46      | 2        | 0.32%   |
| 42      | 2        | 0.32%   |
| 37      | 2        | 0.32%   |
| 16      | 2        | 0.32%   |
| 77      | 1        | 0.16%   |
| 74      | 1        | 0.16%   |
| 58      | 1        | 0.16%   |
| 47      | 1        | 0.16%   |
| 43      | 1        | 0.16%   |
| 36      | 1        | 0.16%   |
| 33      | 1        | 0.16%   |
| 26      | 1        | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 263      | 42.15%  |
| 401-500        | 181      | 29.01%  |
| 601-700        | 45       | 7.21%   |
| 701-800        | 29       | 4.65%   |
| 1001-1500      | 28       | 4.49%   |
| 351-400        | 25       | 4.01%   |
| 301-350        | 25       | 4.01%   |
| 1501-2000      | 16       | 2.56%   |
| 801-900        | 5        | 0.8%    |
| Unknown        | 3        | 0.48%   |
| More than 2000 | 2        | 0.32%   |
| 901-1000       | 2        | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 453      | 74.63%  |
| 16/10 | 76       | 12.52%  |
| 5/4   | 37       | 6.1%    |
| 21/9  | 18       | 2.97%   |
| 4/3   | 11       | 1.81%   |
| 32/9  | 4        | 0.66%   |
| 3/2   | 4        | 0.66%   |
| 1.00  | 2        | 0.33%   |
| 3.20  | 1        | 0.16%   |
| 2.00  | 1        | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 203      | 32.38%  |
| 301-350        | 109      | 17.38%  |
| 151-200        | 97       | 15.47%  |
| 351-500        | 62       | 9.89%   |
| 251-300        | 44       | 7.02%   |
| 141-150        | 44       | 7.02%   |
| More than 1000 | 37       | 5.9%    |
| 501-1000       | 16       | 2.55%   |
| 101-110        | 6        | 0.96%   |
| 111-120        | 3        | 0.48%   |
| Unknown        | 3        | 0.48%   |
| 131-140        | 2        | 0.32%   |
| 121-130        | 1        | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 419      | 68.35%  |
| 101-120 | 129      | 21.04%  |
| 1-50    | 33       | 5.38%   |
| 121-160 | 23       | 3.75%   |
| 161-240 | 6        | 0.98%   |
| Unknown | 3        | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 558      | 87.87%  |
| 2     | 54       | 8.5%    |
| 0     | 18       | 2.83%   |
| 3     | 5        | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 446      | 52.59%  |
| Intel                                  | 210      | 24.76%  |
| Qualcomm Atheros                       | 48       | 5.66%   |
| MediaTek                               | 24       | 2.83%   |
| Broadcom                               | 23       | 2.71%   |
| Ralink Technology                      | 19       | 2.24%   |
| TP-Link                                | 16       | 1.89%   |
| Ralink                                 | 9        | 1.06%   |
| ASIX Electronics                       | 6        | 0.71%   |
| NetGear                                | 4        | 0.47%   |
| VIA Technologies                       | 3        | 0.35%   |
| Nvidia                                 | 3        | 0.35%   |
| Broadcom Limited                       | 3        | 0.35%   |
| Belkin Components                      | 3        | 0.35%   |
| Samsung Electronics                    | 2        | 0.24%   |
| Qualcomm Atheros Communications        | 2        | 0.24%   |
| Microsoft                              | 2        | 0.24%   |
| Marvell Technology Group               | 2        | 0.24%   |
| ASUSTek Computer                       | 2        | 0.24%   |
| Accton Technology                      | 2        | 0.24%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.12%   |
| Xiaomi                                 | 1        | 0.12%   |
| Tenda                                  | 1        | 0.12%   |
| Suzhou Motorcomm Electronic Technology | 1        | 0.12%   |
| Sundance Technology Inc / IC Plus      | 1        | 0.12%   |
| STMicroelectronics                     | 1        | 0.12%   |
| OPPO Electronics                       | 1        | 0.12%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.12%   |
| Manta                                  | 1        | 0.12%   |
| JMicron Technology                     | 1        | 0.12%   |
| Innomedia                              | 1        | 0.12%   |
| IMC Networks                           | 1        | 0.12%   |
| ICS Advent                             | 1        | 0.12%   |
| Horned Cat                             | 1        | 0.12%   |
| Edimax Technology                      | 1        | 0.12%   |
| AVM                                    | 1        | 0.12%   |
| Aquantia                               | 1        | 0.12%   |
| American Future Technology             | 1        | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 1        | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 351      | 36.83%  |
| Realtek RTL8125 2.5GbE Controller                                      | 43       | 4.51%   |
| Intel I211 Gigabit Network Connection                                  | 24       | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24       | 2.52%   |
| Intel Ethernet Controller I225-V                                       | 21       | 2.2%    |
| Intel Ethernet Connection I217-LM                                      | 18       | 1.89%   |
| Intel Wi-Fi 6 AX200                                                    | 17       | 1.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16       | 1.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 14       | 1.47%   |
| Realtek 802.11ac NIC                                                   | 14       | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 12       | 1.26%   |
| Ralink MT7601U Wireless Adapter                                        | 10       | 1.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 10       | 1.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 10       | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 9        | 0.94%   |
| Intel 82579V Gigabit Network Connection                                | 9        | 0.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 7        | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7        | 0.73%   |
| Intel Wireless 7260                                                    | 7        | 0.73%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 7        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 7        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6        | 0.63%   |
| Intel Ethernet Connection I217-V                                       | 6        | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 6        | 0.63%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 6        | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6        | 0.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 5        | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5        | 0.52%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 5        | 0.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 5        | 0.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5        | 0.52%   |
| Intel Ethernet Controller I226-V                                       | 5        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5        | 0.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 4        | 0.42%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 4        | 0.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 4        | 0.42%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 4        | 0.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4        | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 4        | 0.42%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 4        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 82       | 30.48%  |
| Intel                                 | 72       | 26.77%  |
| Qualcomm Atheros                      | 23       | 8.55%   |
| MediaTek                              | 23       | 8.55%   |
| Ralink Technology                     | 19       | 7.06%   |
| TP-Link                               | 15       | 5.58%   |
| Ralink                                | 9        | 3.35%   |
| Broadcom                              | 6        | 2.23%   |
| NetGear                               | 4        | 1.49%   |
| Belkin Components                     | 3        | 1.12%   |
| Qualcomm Atheros Communications       | 2        | 0.74%   |
| Microsoft                             | 2        | 0.74%   |
| ASUSTek Computer                      | 2        | 0.74%   |
| Tenda                                 | 1        | 0.37%   |
| IMC Networks                          | 1        | 0.37%   |
| Edimax Technology                     | 1        | 0.37%   |
| Broadcom Limited                      | 1        | 0.37%   |
| AVM                                   | 1        | 0.37%   |
| Accton Technology                     | 1        | 0.37%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 17       | 6.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 14       | 5.19%   |
| Realtek 802.11ac NIC                                                 | 14       | 5.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 12       | 4.44%   |
| Ralink MT7601U Wireless Adapter                                      | 10       | 3.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 10       | 3.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 9        | 3.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 9        | 3.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 7        | 2.59%   |
| Intel Wireless 7260                                                  | 7        | 2.59%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 7        | 2.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 6        | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 5        | 1.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 5        | 1.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 5        | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 5        | 1.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 4        | 1.48%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller          | 4        | 1.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 4        | 1.48%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 4        | 1.48%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 4        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4        | 1.48%   |
| Intel Wireless 3165                                                  | 4        | 1.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3        | 1.11%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 3        | 1.11%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 3        | 1.11%   |
| Intel Wireless 7265                                                  | 3        | 1.11%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 3        | 1.11%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 3        | 1.11%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2        | 0.74%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 2        | 0.74%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 2        | 0.74%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 2        | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2        | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2        | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2        | 0.74%   |
| Ralink RT5392 PCIe Wireless Network Adapter                          | 2        | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 421      | 63.6%   |
| Intel                                  | 168      | 25.38%  |
| Qualcomm Atheros                       | 26       | 3.93%   |
| Broadcom                               | 17       | 2.57%   |
| ASIX Electronics                       | 6        | 0.91%   |
| VIA Technologies                       | 3        | 0.45%   |
| Nvidia                                 | 3        | 0.45%   |
| Samsung Electronics                    | 2        | 0.3%    |
| Marvell Technology Group               | 2        | 0.3%    |
| Broadcom Limited                       | 2        | 0.3%    |
| ZTE WCDMA Technologies MSM             | 1        | 0.15%   |
| Xiaomi                                 | 1        | 0.15%   |
| TP-Link                                | 1        | 0.15%   |
| Suzhou Motorcomm Electronic Technology | 1        | 0.15%   |
| Sundance Technology Inc / IC Plus      | 1        | 0.15%   |
| OPPO Electronics                       | 1        | 0.15%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.15%   |
| MediaTek                               | 1        | 0.15%   |
| JMicron Technology                     | 1        | 0.15%   |
| ICS Advent                             | 1        | 0.15%   |
| Aquantia                               | 1        | 0.15%   |
| Accton Technology                      | 1        | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 351      | 51.77%  |
| Realtek RTL8125 2.5GbE Controller                                      | 43       | 6.34%   |
| Intel I211 Gigabit Network Connection                                  | 24       | 3.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24       | 3.54%   |
| Intel Ethernet Controller I225-V                                       | 21       | 3.1%    |
| Intel Ethernet Connection I217-LM                                      | 18       | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16       | 2.36%   |
| Intel 82579V Gigabit Network Connection                                | 9        | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7        | 1.03%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 7        | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6        | 0.88%   |
| Intel Ethernet Connection I217-V                                       | 6        | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6        | 0.88%   |
| Intel Ethernet Controller I226-V                                       | 5        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4        | 0.59%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 4        | 0.59%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 0.59%   |
| Intel 82578DM Gigabit Network Connection                               | 4        | 0.59%   |
| Intel 82578DC Gigabit Network Connection                               | 4        | 0.59%   |
| Intel 82574L Gigabit Network Connection                                | 4        | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 4        | 0.59%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 3        | 0.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3        | 0.44%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 0.44%   |
| Intel Ethernet Connection (17) I219-V                                  | 3        | 0.44%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 3        | 0.44%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 3        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 0.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2        | 0.29%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 0.29%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 0.29%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.29%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.29%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.29%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 627      | 70.37%  |
| WiFi     | 259      | 29.07%  |
| Modem    | 3        | 0.34%   |
| Unknown  | 2        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 506      | 80.83%  |
| WiFi     | 120      | 19.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 428      | 67.51%  |
| 2     | 179      | 28.23%  |
| 3     | 20       | 3.15%   |
| 0     | 6        | 0.95%   |
| 5     | 1        | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 391      | 61.57%  |
| Yes  | 244      | 38.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 66       | 32.35%  |
| Cambridge Silicon Radio         | 41       | 20.1%   |
| Realtek Semiconductor           | 34       | 16.67%  |
| MediaTek                        | 16       | 7.84%   |
| ASUSTek Computer                | 11       | 5.39%   |
| Broadcom                        | 9        | 4.41%   |
| IMC Networks                    | 8        | 3.92%   |
| Qualcomm Atheros Communications | 4        | 1.96%   |
| TP-Link                         | 3        | 1.47%   |
| Foxconn / Hon Hai               | 3        | 1.47%   |
| Lite-On Technology              | 2        | 0.98%   |
| Apple                           | 2        | 0.98%   |
| Actions                         | 2        | 0.98%   |
| Integrated System Solution      | 1        | 0.49%   |
| Dynex                           | 1        | 0.49%   |
| Conwise Technology              | 1        | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 41       | 20%     |
| Realtek Bluetooth Radio                                  | 29       | 14.15%  |
| MediaTek Wireless_Device                                 | 16       | 7.8%    |
| Intel AX200 Bluetooth                                    | 15       | 7.32%   |
| Intel Bluetooth wireless interface                       | 14       | 6.83%   |
| Intel AX210 Bluetooth                                    | 11       | 5.37%   |
| Intel Bluetooth Device                                   | 8        | 3.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 7        | 3.41%   |
| Intel Wireless-AC 3168 Bluetooth                         | 6        | 2.93%   |
| IMC Networks Bluetooth Radio                             | 5        | 2.44%   |
| ASUS ASUS USB-BT500                                      | 5        | 2.44%   |
| Realtek  Bluetooth 4.2 Adapter                           | 4        | 1.95%   |
| Intel AX201 Bluetooth                                    | 4        | 1.95%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 4        | 1.95%   |
| TP-Link TP-T@- UB500 Adapter                             | 3        | 1.46%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 3        | 1.46%   |
| IMC Networks Wireless_Device                             | 3        | 1.46%   |
| Realtek Bluetooth 5.3 Radio                              | 2        | 0.98%   |
| Foxconn / Hon Hai Wireless_Device                        | 2        | 0.98%   |
| ASUS Bluetooth Radio                                     | 2        | 0.98%   |
| ASUS BCM20702A0                                          | 2        | 0.98%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 2        | 0.98%   |
| Actions general adapter                                  | 2        | 0.98%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 0.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1        | 0.49%   |
| Lite-On Bluetooth Device                                 | 1        | 0.49%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.49%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter             | 1        | 0.49%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.49%   |
| Conwise CW6622                                           | 1        | 0.49%   |
| Broadcom HP Portable Bumble Bee                          | 1        | 0.49%   |
| Broadcom Bluetooth 3.0 USB Dongle                        | 1        | 0.49%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 0.49%   |
| Broadcom BCM2210 Bluetooth                               | 1        | 0.49%   |
| Broadcom BCM2045 Bluetooth                               | 1        | 0.49%   |
| ASUS Bluetooth Device                                    | 1        | 0.49%   |
| ASUS Bluetooth Adapter                                   | 1        | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 371      | 37.86%  |
| AMD                                          | 304      | 31.02%  |
| Nvidia                                       | 184      | 18.78%  |
| C-Media Electronics                          | 17       | 1.73%   |
| Creative Labs                                | 15       | 1.53%   |
| Creative Technology                          | 10       | 1.02%   |
| Logitech                                     | 7        | 0.71%   |
| Zoran Co. Personal Media Division (Nogatech) | 6        | 0.61%   |
| Generalplus Technology                       | 6        | 0.61%   |
| ASUSTek Computer                             | 6        | 0.61%   |
| SteelSeries ApS                              | 4        | 0.41%   |
| JMTek                                        | 4        | 0.41%   |
| Thesycon Systemsoftware & Consulting         | 3        | 0.31%   |
| Tenx Technology                              | 3        | 0.31%   |
| Micro Star International                     | 3        | 0.31%   |
| KTMicro                                      | 3        | 0.31%   |
| Walmart                                      | 2        | 0.2%    |
| VIA Technologies                             | 2        | 0.2%    |
| Texas Instruments                            | 2        | 0.2%    |
| Kingston Technology                          | 2        | 0.2%    |
| GYROCOM C&C                                  | 2        | 0.2%    |
| XMOS                                         | 1        | 0.1%    |
| Valve Software                               | 1        | 0.1%    |
| Universal Audio                              | 1        | 0.1%    |
| Soundprese                                   | 1        | 0.1%    |
| Silicon Integrated Systems [SiS]             | 1        | 0.1%    |
| PreSonus Audio Electronics                   | 1        | 0.1%    |
| Philips (or NXP)                             | 1        | 0.1%    |
| Nordic Semiconductor ASA                     | 1        | 0.1%    |
| M-Audio                                      | 1        | 0.1%    |
| Jieli Technology                             | 1        | 0.1%    |
| Hewlett-Packard                              | 1        | 0.1%    |
| HECATE G4 TE GAMING HEADSET                  | 1        | 0.1%    |
| Goldvish                                     | 1        | 0.1%    |
| FIFINE Microphones                           | 1        | 0.1%    |
| ESI Audiotechnik                             | 1        | 0.1%    |
| Elgato Systems                               | 1        | 0.1%    |
| EDFIER                                       | 1        | 0.1%    |
| Dell                                         | 1        | 0.1%    |
| Corsair                                      | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Ryzen HD Audio Controller                                                     | 77       | 6.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 69       | 5.7%    |
| AMD Starship/Matisse HD Audio Controller                                          | 58       | 4.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 55       | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 43       | 3.55%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                       | 39       | 3.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 36       | 2.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 35       | 2.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 33       | 2.73%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 30       | 2.48%   |
| AMD FCH Azalia Controller                                                         | 29       | 2.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 29       | 2.4%    |
| AMD Radeon High Definition Audio Controller                                       | 27       | 2.23%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 19       | 1.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 18       | 1.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 18       | 1.49%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 18       | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 17       | 1.4%    |
| Intel Alder Lake-S HD Audio Controller                                            | 17       | 1.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 16       | 1.32%   |
| Intel 200 Series PCH HD Audio                                                     | 16       | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 16       | 1.32%   |
| Nvidia GP108 High Definition Audio Controller                                     | 15       | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 15       | 1.24%   |
| Intel Cannon Lake PCH cAVS                                                        | 14       | 1.16%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 12       | 0.99%   |
| Nvidia GF119 HDMI Audio Controller                                                | 11       | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                     | 11       | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11       | 0.91%   |
| AMD Navi 31 HDMI/DP Audio                                                         | 11       | 0.91%   |
| Nvidia High Definition Audio Controller                                           | 10       | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                                     | 10       | 0.83%   |
| Nvidia GM204 High Definition Audio Controller                                     | 10       | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 10       | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                          | 10       | 0.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 10       | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 9        | 0.74%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 9        | 0.74%   |
| AMD Trinity HDMI Audio Controller                                                 | 9        | 0.74%   |
| AMD Navi 10 HDMI Audio                                                            | 9        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 128      | 16.86%  |
| Unknown                      | 105      | 13.83%  |
| Samsung Electronics          | 86       | 11.33%  |
| SK hynix                     | 73       | 9.62%   |
| Corsair                      | 62       | 8.17%   |
| G.Skill                      | 58       | 7.64%   |
| Crucial                      | 48       | 6.32%   |
| Micron Technology            | 30       | 3.95%   |
| Unknown                      | 22       | 2.9%    |
| A-DATA Technology            | 16       | 2.11%   |
| Team                         | 15       | 1.98%   |
| Nanya Technology             | 15       | 1.98%   |
| Ramaxel Technology           | 12       | 1.58%   |
| Patriot                      | 8        | 1.05%   |
| Unknown (ABCD)               | 6        | 0.79%   |
| Transcend                    | 6        | 0.79%   |
| GOODRAM                      | 6        | 0.79%   |
| AMD                          | 6        | 0.79%   |
| Apacer                       | 5        | 0.66%   |
| Smart                        | 4        | 0.53%   |
| Elpida                       | 4        | 0.53%   |
| Qimonda                      | 3        | 0.4%    |
| PNY                          | 3        | 0.4%    |
| Patriot Memory               | 3        | 0.4%    |
| Timetec                      | 2        | 0.26%   |
| Thermaltake                  | 2        | 0.26%   |
| Patriot Memory (PDP Systems) | 2        | 0.26%   |
| Lexar Co Limited             | 2        | 0.26%   |
| Lexar                        | 2        | 0.26%   |
| Kllisre                      | 2        | 0.26%   |
| Kingmax                      | 2        | 0.26%   |
| Wilk                         | 1        | 0.13%   |
| Unknown (0x5846)             | 1        | 0.13%   |
| Unknown (0x0DEC)             | 1        | 0.13%   |
| Unknown (0x0DD5)             | 1        | 0.13%   |
| Teikon                       | 1        | 0.13%   |
| Super Talent                 | 1        | 0.13%   |
| Silicon Power                | 1        | 0.13%   |
| Sesame                       | 1        | 0.13%   |
| Red Hat                      | 1        | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 22       | 2.65%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 10       | 1.2%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 9        | 1.08%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 8        | 0.96%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 7        | 0.84%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3                     | 7        | 0.84%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s            | 7        | 0.84%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 6        | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 6        | 0.72%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s             | 6        | 0.72%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 6        | 0.72%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 5        | 0.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 5        | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 5        | 0.6%    |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 4        | 0.48%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 4        | 0.48%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s           | 4        | 0.48%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 4        | 0.48%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s            | 4        | 0.48%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s             | 4        | 0.48%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s             | 4        | 0.48%   |
| Kingston RAM KHX2666C16/8G 8GiB DIMM DDR4 3466MT/s             | 4        | 0.48%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s            | 4        | 0.48%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s          | 4        | 0.48%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 4        | 0.48%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s          | 4        | 0.48%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3600MT/s             | 4        | 0.48%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3800MT/s             | 4        | 0.48%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3600MT/s         | 4        | 0.48%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 3        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 3        | 0.36%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 3        | 0.36%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s             | 3        | 0.36%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3        | 0.36%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s           | 3        | 0.36%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s           | 3        | 0.36%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s           | 3        | 0.36%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s           | 3        | 0.36%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s           | 3        | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 253      | 39.41%  |
| DDR4    | 237      | 36.92%  |
| DDR5    | 40       | 6.23%   |
| DDR2    | 32       | 4.98%   |
| Unknown | 32       | 4.98%   |
| SDRAM   | 31       | 4.83%   |
| LPDDR4  | 7        | 1.09%   |
| DDR     | 6        | 0.93%   |
| LPDDR5  | 3        | 0.47%   |
| RAM     | 1        | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 575      | 92.3%   |
| SODIMM       | 44       | 7.06%   |
| Row Of Chips | 3        | 0.48%   |
| FB-DIMM      | 1        | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 236      | 33.67%  |
| 4096  | 177      | 25.25%  |
| 2048  | 117      | 16.69%  |
| 16384 | 106      | 15.12%  |
| 32768 | 38       | 5.42%   |
| 1024  | 23       | 3.28%   |
| 512   | 2        | 0.29%   |
| 12288 | 1        | 0.14%   |
| 16    | 1        | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 156      | 21.61%  |
| 1333    | 89       | 12.33%  |
| 3200    | 59       | 8.17%   |
| 3600    | 52       | 7.2%    |
| 2400    | 40       | 5.54%   |
| 2667    | 32       | 4.43%   |
| 2133    | 31       | 4.29%   |
| 800     | 22       | 3.05%   |
| 667     | 20       | 2.77%   |
| 1866    | 16       | 2.22%   |
| 3800    | 13       | 1.8%    |
| Unknown | 13       | 1.8%    |
| 4800    | 12       | 1.66%   |
| 3733    | 12       | 1.66%   |
| 1867    | 11       | 1.52%   |
| 1800    | 11       | 1.52%   |
| 2666    | 10       | 1.39%   |
| 6000    | 9        | 1.25%   |
| 3400    | 8        | 1.11%   |
| 6400    | 7        | 0.97%   |
| 4000    | 7        | 0.97%   |
| 3466    | 7        | 0.97%   |
| 1334    | 7        | 0.97%   |
| 5600    | 6        | 0.83%   |
| 1066    | 6        | 0.83%   |
| 400     | 5        | 0.69%   |
| 5200    | 4        | 0.55%   |
| 2933    | 4        | 0.55%   |
| 1067    | 4        | 0.55%   |
| 6200    | 3        | 0.42%   |
| 4333    | 3        | 0.42%   |
| 3333    | 3        | 0.42%   |
| 3151    | 3        | 0.42%   |
| 3000    | 3        | 0.42%   |
| 2200    | 3        | 0.42%   |
| 2048    | 3        | 0.42%   |
| 1648    | 3        | 0.42%   |
| 12800   | 2        | 0.28%   |
| 3866    | 2        | 0.28%   |
| 2000    | 2        | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 11       | 30.56%  |
| Hewlett-Packard     | 9        | 25%     |
| Seiko Epson         | 6        | 16.67%  |
| Canon               | 5        | 13.89%  |
| Samsung Electronics | 2        | 5.56%   |
| Prolific Technology | 2        | 5.56%   |
| Dymo-CoStar         | 1        | 2.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port          | 2        | 5.56%   |
| Seiko Epson XP-2100 Series             | 1        | 2.78%   |
| Seiko Epson Printer                    | 1        | 2.78%   |
| Seiko Epson L3560 Series               | 1        | 2.78%   |
| Seiko Epson ET-2850 Series             | 1        | 2.78%   |
| Seiko Epson ET-2710 Series             | 1        | 2.78%   |
| Seiko Epson EPSON L132 Series          | 1        | 2.78%   |
| Samsung ML-1610 Mono Laser Printer     | 1        | 2.78%   |
| Samsung C1810 Series                   | 1        | 2.78%   |
| HP Smart Tank 750 series               | 1        | 2.78%   |
| HP LaserJet 1020                       | 1        | 2.78%   |
| HP DeskJet 930c                        | 1        | 2.78%   |
| HP DeskJet 6940 series                 | 1        | 2.78%   |
| HP DeskJet 4530 series                 | 1        | 2.78%   |
| HP DeskJet 4100 series                 | 1        | 2.78%   |
| HP DeskJet 3630 series                 | 1        | 2.78%   |
| HP DeskJet 2600 series                 | 1        | 2.78%   |
| HP Deskjet 1000 J110 series            | 1        | 2.78%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 2.78%   |
| Canon TS5300 series                    | 1        | 2.78%   |
| Canon TS3100 series                    | 1        | 2.78%   |
| Canon PIXMA MX370 Series               | 1        | 2.78%   |
| Canon MF210 Series                     | 1        | 2.78%   |
| Canon G3010 series                     | 1        | 2.78%   |
| Brother MFC-L2710DW series             | 1        | 2.78%   |
| Brother MFC-L2710DN series             | 1        | 2.78%   |
| Brother MFC-J4340DW                    | 1        | 2.78%   |
| Brother MFC-J1010DW                    | 1        | 2.78%   |
| Brother HL-L2370DW series              | 1        | 2.78%   |
| Brother HL-L2305 series                | 1        | 2.78%   |
| Brother HL-B2080DW series              | 1        | 2.78%   |
| Brother HL-2270DW Laser Printer        | 1        | 2.78%   |
| Brother HL-2140 series                 | 1        | 2.78%   |
| Brother HL-1210W series                | 1        | 2.78%   |
| Brother DCP-L2530DW series             | 1        | 2.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 3        | 75%     |
| Seiko Epson | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon CanoScan LIDE 25                                  | 2        | 50%     |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1        | 25%     |
| Canon CanoScan LiDE 200                                 | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 25       | 35.21%  |
| Microsoft                     | 5        | 7.04%   |
| Microdia                      | 5        | 7.04%   |
| Z-Star Microelectronics       | 4        | 5.63%   |
| Realtek Semiconductor         | 3        | 4.23%   |
| KYE Systems (Mouse Systems)   | 3        | 4.23%   |
| WaveRider Communications      | 2        | 2.82%   |
| Samsung Electronics           | 2        | 2.82%   |
| Lenovo                        | 2        | 2.82%   |
| Jieli Technology              | 2        | 2.82%   |
| Chicony Electronics           | 2        | 2.82%   |
| Aveo Technology               | 2        | 2.82%   |
| Xiongmai                      | 1        | 1.41%   |
| Valve Software                | 1        | 1.41%   |
| Trust                         | 1        | 1.41%   |
| Tobii Technology AB           | 1        | 1.41%   |
| SunplusIT                     | 1        | 1.41%   |
| Sunplus Innovation Technology | 1        | 1.41%   |
| Sony                          | 1        | 1.41%   |
| Razer USA                     | 1        | 1.41%   |
| Hewlett-Packard               | 1        | 1.41%   |
| Generalplus Technology        | 1        | 1.41%   |
| GEMBIRD                       | 1        | 1.41%   |
| Elgato Systems                | 1        | 1.41%   |
| Apple                         | 1        | 1.41%   |
| Alcor Micro                   | 1        | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 5        | 7.04%   |
| Z-Star A4 TECH USB2.0 PC Camera E                     | 3        | 4.23%   |
| Logitech Webcam C310                                  | 3        | 4.23%   |
| Samsung Galaxy series, misc. (MTP mode)               | 2        | 2.82%   |
| Microdia Webcam Vitade AF                             | 2        | 2.82%   |
| Microdia Integrated Camera                            | 2        | 2.82%   |
| Logitech Webcam C930e                                 | 2        | 2.82%   |
| Logitech Webcam C250                                  | 2        | 2.82%   |
| Logitech Webcam C170                                  | 2        | 2.82%   |
| Logitech Logitech Webcam C925e                        | 2        | 2.82%   |
| Logitech BRIO Ultra HD Webcam                         | 2        | 2.82%   |
| KYE Systems (Mouse Systems) USB 2.0 HD1080P PC Camera | 2        | 2.82%   |
| Z-Star Venus USB2.0 Camera                            | 1        | 1.41%   |
| Xiongmai web camera                                   | 1        | 1.41%   |
| WaveRider USB Live camera                             | 1        | 1.41%   |
| WaveRider USB 2.0 Camera                              | 1        | 1.41%   |
| Valve Software 3D Camera                              | 1        | 1.41%   |
| Trust Full HD Webcam                                  | 1        | 1.41%   |
| Tobii AB EyeChip                                      | 1        | 1.41%   |
| SunplusIT USB 2.0 Camera                              | 1        | 1.41%   |
| Sunplus FULL HD webcam                                | 1        | 1.41%   |
| Sony CEVCECM                                          | 1        | 1.41%   |
| Realtek USB Camera                                    | 1        | 1.41%   |
| Realtek USB 2.0 Camera                                | 1        | 1.41%   |
| Realtek HP 1.0MP High Definition Webcam               | 1        | 1.41%   |
| Razer USA Razer Kiyo Pro                              | 1        | 1.41%   |
| Microsoft LifeCam VX-700                              | 1        | 1.41%   |
| Microsoft LifeCam VX-5000                             | 1        | 1.41%   |
| Microsoft LifeCam VX-2000                             | 1        | 1.41%   |
| Microsoft LifeCam HD-5000                             | 1        | 1.41%   |
| Microsoft LifeCam HD-3000                             | 1        | 1.41%   |
| Microdia USB 2.0 Camera                               | 1        | 1.41%   |
| Logitech Webcam C260                                  | 1        | 1.41%   |
| Logitech Webcam B500                                  | 1        | 1.41%   |
| Logitech Logitech Webcam C160                         | 1        | 1.41%   |
| Logitech HD Pro Webcam C920                           | 1        | 1.41%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 1.41%   |
| Logitech C505e HD Webcam                              | 1        | 1.41%   |
| Logitech Brio 500                                     | 1        | 1.41%   |
| Lenovo Lenovo FHD Webcam Audio                        | 1        | 1.41%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 50%     |
| Aktiv                 | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 50%     |
| Aktiv Rutoken lite                                | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 583      | 91.96%  |
| 1     | 49       | 7.73%   |
| 3     | 1        | 0.16%   |
| 2     | 1        | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 36       | 67.92%  |
| Net/wireless             | 7        | 13.21%  |
| Unassigned class         | 3        | 5.66%   |
| Communication controller | 3        | 5.66%   |
| Chipcard                 | 2        | 3.77%   |
| Net/ethernet             | 1        | 1.89%   |
| Camera                   | 1        | 1.89%   |

