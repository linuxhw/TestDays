Zorin - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Zorin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin/Desktop/README.md) and [notebooks](/Dist/Zorin/Notebook/README.md).

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

Total: 10382

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ProBook 650 G3              | Notebook    | [9bfb6a8afd](https://linux-hardware.org/?probe=9bfb6a8afd) | May 09, 2024 |
| HONOR         | BBR-WAX9                    | Notebook    | [be1a16a925](https://linux-hardware.org/?probe=be1a16a925) | May 09, 2024 |
| HONOR         | BBR-WAX9                    | Notebook    | [8c9db99956](https://linux-hardware.org/?probe=8c9db99956) | May 09, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [586c4844be](https://linux-hardware.org/?probe=586c4844be) | May 09, 2024 |
| Ultra         | UB42X                       | Notebook    | [b7f2dbd777](https://linux-hardware.org/?probe=b7f2dbd777) | May 09, 2024 |
| Ultra         | UB42X                       | Notebook    | [4597d0586d](https://linux-hardware.org/?probe=4597d0586d) | May 08, 2024 |
| Sony          | VPCEB1S1E                   | Notebook    | [551a1d2f64](https://linux-hardware.org/?probe=551a1d2f64) | May 08, 2024 |
| Lenovo        | 110536U ThinkServer TS13... | Desktop     | [d3196733cd](https://linux-hardware.org/?probe=d3196733cd) | May 08, 2024 |
| HP            | ProBook 6460b               | Notebook    | [14aa46f09d](https://linux-hardware.org/?probe=14aa46f09d) | May 08, 2024 |
| Infinix       | INBOOK Y1 PLUS NEO          | Notebook    | [253042bbd9](https://linux-hardware.org/?probe=253042bbd9) | May 08, 2024 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [e896127dc3](https://linux-hardware.org/?probe=e896127dc3) | May 08, 2024 |
| Sony          | VGN-CR31S_W                 | Notebook    | [7e7d96c020](https://linux-hardware.org/?probe=7e7d96c020) | May 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [b18d2c1ec2](https://linux-hardware.org/?probe=b18d2c1ec2) | May 08, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [3a9861e2be](https://linux-hardware.org/?probe=3a9861e2be) | May 08, 2024 |
| Lenovo        | ThinkPad Edge 031946U       | Notebook    | [8f8fb39c6e](https://linux-hardware.org/?probe=8f8fb39c6e) | May 08, 2024 |
| NEC Comput... | PC-LS350SSB                 | Notebook    | [530b3713dd](https://linux-hardware.org/?probe=530b3713dd) | May 08, 2024 |
| ASUSTek       | X540SA                      | Notebook    | [456909c790](https://linux-hardware.org/?probe=456909c790) | May 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [14f9a58589](https://linux-hardware.org/?probe=14f9a58589) | May 08, 2024 |
| Samsung       | 530XBB                      | Notebook    | [5c0772cde4](https://linux-hardware.org/?probe=5c0772cde4) | May 07, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [d4d583a573](https://linux-hardware.org/?probe=d4d583a573) | May 07, 2024 |
| Intel         | H55                         | Desktop     | [83c1ac4239](https://linux-hardware.org/?probe=83c1ac4239) | May 07, 2024 |
| Lenovo        | IdeaPad C340-15IML 81TL     | Convertible | [467c035ce1](https://linux-hardware.org/?probe=467c035ce1) | May 07, 2024 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [a52ed98e85](https://linux-hardware.org/?probe=a52ed98e85) | May 07, 2024 |
| Daten Tecn... | DT02-M4                     | Notebook    | [88093023ed](https://linux-hardware.org/?probe=88093023ed) | May 07, 2024 |
| SCHNEIDER     | SCL141CTP                   | Notebook    | [ce0a785c29](https://linux-hardware.org/?probe=ce0a785c29) | May 07, 2024 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | Notebook    | [1c72c07e3d](https://linux-hardware.org/?probe=1c72c07e3d) | May 07, 2024 |
| ASUSTek       | S451LA                      | Notebook    | [f3720aa6f9](https://linux-hardware.org/?probe=f3720aa6f9) | May 07, 2024 |
| Alienware     | m15 R7                      | Notebook    | [445b29da20](https://linux-hardware.org/?probe=445b29da20) | May 06, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [bf13a8edca](https://linux-hardware.org/?probe=bf13a8edca) | May 06, 2024 |
| Lenovo        | E31-80 80MX                 | Notebook    | [1c9fd17eff](https://linux-hardware.org/?probe=1c9fd17eff) | May 06, 2024 |
| Dell          | Latitude E5410              | Notebook    | [0038eadd32](https://linux-hardware.org/?probe=0038eadd32) | May 06, 2024 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [657a003a54](https://linux-hardware.org/?probe=657a003a54) | May 06, 2024 |
| HP            | Pavilion 15                 | Notebook    | [77f8425176](https://linux-hardware.org/?probe=77f8425176) | May 06, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [bf478cb069](https://linux-hardware.org/?probe=bf478cb069) | May 06, 2024 |
| ASUSTek       | P2540UA                     | Notebook    | [ea9ddf3f6e](https://linux-hardware.org/?probe=ea9ddf3f6e) | May 06, 2024 |
| HP            | 8906 SMVB                   | Desktop     | [16dcd59b91](https://linux-hardware.org/?probe=16dcd59b91) | May 06, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [0b1ac68bc9](https://linux-hardware.org/?probe=0b1ac68bc9) | May 06, 2024 |
| Medion        | MS-7366                     | Desktop     | [0c36270a48](https://linux-hardware.org/?probe=0c36270a48) | May 06, 2024 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [528dc99ca7](https://linux-hardware.org/?probe=528dc99ca7) | May 05, 2024 |
| MSI           | PRO X670-P WIFI             | Desktop     | [a411b722e3](https://linux-hardware.org/?probe=a411b722e3) | May 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [d676549abd](https://linux-hardware.org/?probe=d676549abd) | May 05, 2024 |
| Dell          | Latitude 3420               | Notebook    | [a28c6852fe](https://linux-hardware.org/?probe=a28c6852fe) | May 05, 2024 |
| Lenovo        | Flex 3-1130 80LY            | Notebook    | [3786d9e8e2](https://linux-hardware.org/?probe=3786d9e8e2) | May 05, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [fc52b48b01](https://linux-hardware.org/?probe=fc52b48b01) | May 05, 2024 |
| Panasonic     | FZM1-3                      | Tablet      | [8a7d985c38](https://linux-hardware.org/?probe=8a7d985c38) | May 05, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [eb9fc84dcf](https://linux-hardware.org/?probe=eb9fc84dcf) | May 05, 2024 |
| HP            | Notebook                    | Notebook    | [27cafe3bf5](https://linux-hardware.org/?probe=27cafe3bf5) | May 05, 2024 |
| ECS           | P45T-A                      | Desktop     | [c1f450f8a1](https://linux-hardware.org/?probe=c1f450f8a1) | May 04, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | Notebook    | [b950303950](https://linux-hardware.org/?probe=b950303950) | May 04, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | Notebook    | [f4e6daf83f](https://linux-hardware.org/?probe=f4e6daf83f) | May 04, 2024 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [1349bac413](https://linux-hardware.org/?probe=1349bac413) | May 04, 2024 |
| Gigabyte      | EP43-S3L                    | Desktop     | [96cd4e9337](https://linux-hardware.org/?probe=96cd4e9337) | May 04, 2024 |
| Gigabyte      | H61M-S2P                    | Desktop     | [157cc8b4cc](https://linux-hardware.org/?probe=157cc8b4cc) | May 04, 2024 |
| HP            | ProBook 645 G1              | Notebook    | [02d7e5f984](https://linux-hardware.org/?probe=02d7e5f984) | May 04, 2024 |
| HP            | 1000                        | Notebook    | [c2783cbe1f](https://linux-hardware.org/?probe=c2783cbe1f) | May 04, 2024 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | Notebook    | [bcb2994b33](https://linux-hardware.org/?probe=bcb2994b33) | May 04, 2024 |
| Dell          | Latitude E5520              | Notebook    | [0c2c1716be](https://linux-hardware.org/?probe=0c2c1716be) | May 04, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [81e6cf4d6e](https://linux-hardware.org/?probe=81e6cf4d6e) | May 04, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [d1264f51d1](https://linux-hardware.org/?probe=d1264f51d1) | May 03, 2024 |
| Gigabyte      | H81M-S1                     | Desktop     | [b0e189e984](https://linux-hardware.org/?probe=b0e189e984) | May 03, 2024 |
| Gigabyte      | H81M-S1                     | Desktop     | [8bc865780b](https://linux-hardware.org/?probe=8bc865780b) | May 03, 2024 |
| Toshiba       | Satellite L55t-A            | Notebook    | [9197d3146e](https://linux-hardware.org/?probe=9197d3146e) | May 03, 2024 |
| Dell          | 0773VG A02                  | Desktop     | [2eb962e78c](https://linux-hardware.org/?probe=2eb962e78c) | May 03, 2024 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [5b40331b05](https://linux-hardware.org/?probe=5b40331b05) | May 03, 2024 |
| Lenovo        | ThinkPad Edge 031946U       | Notebook    | [192d9bc00a](https://linux-hardware.org/?probe=192d9bc00a) | May 03, 2024 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [440bf944f3](https://linux-hardware.org/?probe=440bf944f3) | May 03, 2024 |
| Dell          | Latitude 3420               | Notebook    | [e0415e052f](https://linux-hardware.org/?probe=e0415e052f) | May 03, 2024 |
| HP            | Pavilion dv5                | Notebook    | [2ca3da2cdd](https://linux-hardware.org/?probe=2ca3da2cdd) | May 03, 2024 |
| HP            | Pavilion dv5                | Notebook    | [fadfece0f4](https://linux-hardware.org/?probe=fadfece0f4) | May 03, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [f390e47ea1](https://linux-hardware.org/?probe=f390e47ea1) | May 03, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [257f9cdad4](https://linux-hardware.org/?probe=257f9cdad4) | May 03, 2024 |
| Biostar       | B450MHP                     | Desktop     | [5d30a1821f](https://linux-hardware.org/?probe=5d30a1821f) | May 02, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [1a3ebd462f](https://linux-hardware.org/?probe=1a3ebd462f) | May 02, 2024 |
| Proline       | V1165C4                     | Notebook    | [b9571382ea](https://linux-hardware.org/?probe=b9571382ea) | May 02, 2024 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [49bbc3443a](https://linux-hardware.org/?probe=49bbc3443a) | May 02, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [675934d0b6](https://linux-hardware.org/?probe=675934d0b6) | May 02, 2024 |
| HP            | Pavilion 10 TS              | Notebook    | [eb83dcddc9](https://linux-hardware.org/?probe=eb83dcddc9) | May 02, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [2fc15c8d5c](https://linux-hardware.org/?probe=2fc15c8d5c) | May 02, 2024 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [fcd6ae5579](https://linux-hardware.org/?probe=fcd6ae5579) | May 02, 2024 |
| HP            | Pavilion 10 TS              | Notebook    | [e7b477dda5](https://linux-hardware.org/?probe=e7b477dda5) | May 02, 2024 |
| HP            | Pavilion 10 TS              | Notebook    | [b0b8ae831e](https://linux-hardware.org/?probe=b0b8ae831e) | May 02, 2024 |
| Dell          | 085F29 A02                  | All in one  | [2d2c667873](https://linux-hardware.org/?probe=2d2c667873) | May 02, 2024 |
| HP            | 2B0D A01                    | All in one  | [2d8d879cbe](https://linux-hardware.org/?probe=2d8d879cbe) | May 02, 2024 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [0983506014](https://linux-hardware.org/?probe=0983506014) | May 01, 2024 |
| Acer          | TravelMate Spin P414RN-5... | Convertible | [238ec54d15](https://linux-hardware.org/?probe=238ec54d15) | May 01, 2024 |
| Lenovo        | ThinkPad X200s 7469W92      | Notebook    | [687cc00e33](https://linux-hardware.org/?probe=687cc00e33) | May 01, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [890bf7c3a6](https://linux-hardware.org/?probe=890bf7c3a6) | May 01, 2024 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [d118bb6622](https://linux-hardware.org/?probe=d118bb6622) | May 01, 2024 |
| Acer          | TravelMate 4060             | Notebook    | [5bbfc69ef7](https://linux-hardware.org/?probe=5bbfc69ef7) | May 01, 2024 |
| Gigabyte      | H97-HD3                     | Desktop     | [98d2071b97](https://linux-hardware.org/?probe=98d2071b97) | May 01, 2024 |
| Dell          | Precision 3551              | Notebook    | [1dc964b6fb](https://linux-hardware.org/?probe=1dc964b6fb) | Apr 30, 2024 |
| HP            | Notebook                    | Notebook    | [1fd0f0caa7](https://linux-hardware.org/?probe=1fd0f0caa7) | Apr 30, 2024 |
| MSI           | Sword 15 A12VE              | Notebook    | [90ad4b4438](https://linux-hardware.org/?probe=90ad4b4438) | Apr 30, 2024 |
| Packard Be... | EasyNote LJ61               | Notebook    | [9d19962863](https://linux-hardware.org/?probe=9d19962863) | Apr 30, 2024 |
| Packard Be... | EasyNote LJ61               | Notebook    | [6a1a6f046a](https://linux-hardware.org/?probe=6a1a6f046a) | Apr 30, 2024 |
| Dell          | System Vostro 3450          | Notebook    | [eede1fda8a](https://linux-hardware.org/?probe=eede1fda8a) | Apr 30, 2024 |
| Lenovo        | ThinkCentre M91p 7005AK8    | Desktop     | [8eeaa81159](https://linux-hardware.org/?probe=8eeaa81159) | Apr 30, 2024 |
| Panasonic     | CF-31WFL72LM                | Notebook    | [4699837ff5](https://linux-hardware.org/?probe=4699837ff5) | Apr 30, 2024 |
| Panasonic     | CF-31WFL72LM                | Notebook    | [efe2e1be70](https://linux-hardware.org/?probe=efe2e1be70) | Apr 30, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [4067e2b325](https://linux-hardware.org/?probe=4067e2b325) | Apr 30, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [ea6fdbe20e](https://linux-hardware.org/?probe=ea6fdbe20e) | Apr 30, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [c4d5dca0ad](https://linux-hardware.org/?probe=c4d5dca0ad) | Apr 30, 2024 |
| NCR           | Pocono                      | Desktop     | [b0073723fe](https://linux-hardware.org/?probe=b0073723fe) | Apr 29, 2024 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [2e6e9ca3ee](https://linux-hardware.org/?probe=2e6e9ca3ee) | Apr 29, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fc7d5ed265](https://linux-hardware.org/?probe=fc7d5ed265) | Apr 29, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [b6a512b4fc](https://linux-hardware.org/?probe=b6a512b4fc) | Apr 29, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [a036c4124f](https://linux-hardware.org/?probe=a036c4124f) | Apr 29, 2024 |
| Lenovo        | B50-80 80EW                 | Notebook    | [5f20d3fde3](https://linux-hardware.org/?probe=5f20d3fde3) | Apr 29, 2024 |
| Dell          | Inspiron 5558               | Notebook    | [843f3962e2](https://linux-hardware.org/?probe=843f3962e2) | Apr 29, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [9b8290696d](https://linux-hardware.org/?probe=9b8290696d) | Apr 29, 2024 |
| AWOW          | AK34Pro                     | Mini pc     | [acbd739d86](https://linux-hardware.org/?probe=acbd739d86) | Apr 29, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [2663c13afc](https://linux-hardware.org/?probe=2663c13afc) | Apr 29, 2024 |
| Alienware     | m15 R7                      | Notebook    | [ab03c1cde2](https://linux-hardware.org/?probe=ab03c1cde2) | Apr 29, 2024 |
| HP            | 3398                        | Desktop     | [e412887ebc](https://linux-hardware.org/?probe=e412887ebc) | Apr 29, 2024 |
| HP            | Pavilion dm4                | Notebook    | [30eee9e9d3](https://linux-hardware.org/?probe=30eee9e9d3) | Apr 28, 2024 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6f9f3a855d](https://linux-hardware.org/?probe=6f9f3a855d) | Apr 28, 2024 |
| ASUSTek       | X202E                       | Notebook    | [f782bac9e8](https://linux-hardware.org/?probe=f782bac9e8) | Apr 28, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [87f1fc413c](https://linux-hardware.org/?probe=87f1fc413c) | Apr 28, 2024 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [1f145f5fb5](https://linux-hardware.org/?probe=1f145f5fb5) | Apr 28, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [9c5d161110](https://linux-hardware.org/?probe=9c5d161110) | Apr 28, 2024 |
| Avell High... | Avell G1513 MUV / A52 MU... | Notebook    | [2abfc3ebc0](https://linux-hardware.org/?probe=2abfc3ebc0) | Apr 28, 2024 |
| Dell          | 06D7TR A00                  | Desktop     | [43e7eeb6e7](https://linux-hardware.org/?probe=43e7eeb6e7) | Apr 28, 2024 |
| Lenovo        | ThinkPad X395 20NMS1KY02    | Notebook    | [48385039f1](https://linux-hardware.org/?probe=48385039f1) | Apr 28, 2024 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0d587f3e64](https://linux-hardware.org/?probe=0d587f3e64) | Apr 27, 2024 |
| HP            | EliteBook Folio 9470m       | Notebook    | [30d9ddd3f9](https://linux-hardware.org/?probe=30d9ddd3f9) | Apr 27, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [b4ef3a187f](https://linux-hardware.org/?probe=b4ef3a187f) | Apr 27, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c3bf425427](https://linux-hardware.org/?probe=c3bf425427) | Apr 27, 2024 |
| AOpen         | D1009 A1A4                  | Desktop     | [d8b2d00731](https://linux-hardware.org/?probe=d8b2d00731) | Apr 27, 2024 |
| AOpen         | D1009 A1A4                  | Desktop     | [f5399e68ef](https://linux-hardware.org/?probe=f5399e68ef) | Apr 27, 2024 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [a428d5e1d9](https://linux-hardware.org/?probe=a428d5e1d9) | Apr 27, 2024 |
| ACCENT        | SMART 140                   | Notebook    | [49fb07fe3f](https://linux-hardware.org/?probe=49fb07fe3f) | Apr 27, 2024 |
| MSI           | Sword 15 A12VE              | Notebook    | [54953e1bae](https://linux-hardware.org/?probe=54953e1bae) | Apr 27, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [a7b22c04c8](https://linux-hardware.org/?probe=a7b22c04c8) | Apr 27, 2024 |
| BANGHO        | Suma 1025                   | Tablet      | [343b7ee8fa](https://linux-hardware.org/?probe=343b7ee8fa) | Apr 27, 2024 |
| HP            | ProBook 440 G6              | Notebook    | [3cf105c072](https://linux-hardware.org/?probe=3cf105c072) | Apr 26, 2024 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [686e6cab2f](https://linux-hardware.org/?probe=686e6cab2f) | Apr 26, 2024 |
| BANGHO        | Suma 1025                   | Tablet      | [d056fe69ba](https://linux-hardware.org/?probe=d056fe69ba) | Apr 26, 2024 |
| Dell          | Latitude E5520              | Notebook    | [6e98bca2be](https://linux-hardware.org/?probe=6e98bca2be) | Apr 26, 2024 |
| ASUSTek       | M2R-FVM                     | Desktop     | [90232f8ff9](https://linux-hardware.org/?probe=90232f8ff9) | Apr 26, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [cbf7dfdd07](https://linux-hardware.org/?probe=cbf7dfdd07) | Apr 26, 2024 |
| ASUSTek       | M2R-FVM                     | Desktop     | [fc2624bc84](https://linux-hardware.org/?probe=fc2624bc84) | Apr 26, 2024 |
| Lenovo        | ThinkPad L460 20FVS1BK00    | Notebook    | [cc79277a36](https://linux-hardware.org/?probe=cc79277a36) | Apr 26, 2024 |
| Lenovo        | IdeaPad Flex-15IWL 81SR     | Convertible | [3a9322c013](https://linux-hardware.org/?probe=3a9322c013) | Apr 25, 2024 |
| Gigabyte      | W251U                       | Notebook    | [ae6076979a](https://linux-hardware.org/?probe=ae6076979a) | Apr 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [583ea6bc03](https://linux-hardware.org/?probe=583ea6bc03) | Apr 25, 2024 |
| Positivo      | POS-PIQ77CL                 | Desktop     | [ca5ecf0b4c](https://linux-hardware.org/?probe=ca5ecf0b4c) | Apr 25, 2024 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [4f56e23067](https://linux-hardware.org/?probe=4f56e23067) | Apr 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [c226f7eee7](https://linux-hardware.org/?probe=c226f7eee7) | Apr 25, 2024 |
| Dell          | Latitude E6540              | Notebook    | [270b868041](https://linux-hardware.org/?probe=270b868041) | Apr 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d6249f9918](https://linux-hardware.org/?probe=d6249f9918) | Apr 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [f5622b9451](https://linux-hardware.org/?probe=f5622b9451) | Apr 25, 2024 |
| Unknown       | Unknown                     | Notebook    | [849147f4a5](https://linux-hardware.org/?probe=849147f4a5) | Apr 25, 2024 |
| HP            | 1000                        | Notebook    | [dee2aa2dd9](https://linux-hardware.org/?probe=dee2aa2dd9) | Apr 25, 2024 |
| ASUSTek       | K52JU                       | Notebook    | [418274ccd0](https://linux-hardware.org/?probe=418274ccd0) | Apr 25, 2024 |
| BANGHO        | MOV                         | Notebook    | [bb71d25f54](https://linux-hardware.org/?probe=bb71d25f54) | Apr 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [d4f3102f5c](https://linux-hardware.org/?probe=d4f3102f5c) | Apr 25, 2024 |
| NEC Comput... | PC-LS350SSW                 | Notebook    | [a0abb6c6a6](https://linux-hardware.org/?probe=a0abb6c6a6) | Apr 24, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [f93253fdd3](https://linux-hardware.org/?probe=f93253fdd3) | Apr 24, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [bc2a0115a8](https://linux-hardware.org/?probe=bc2a0115a8) | Apr 24, 2024 |
| Dell          | Inspiron 17-7779            | Notebook    | [4d2fec89a1](https://linux-hardware.org/?probe=4d2fec89a1) | Apr 24, 2024 |
| Lenovo        | ThinkPad T570 20H90002RI    | Notebook    | [eeccbdaf2a](https://linux-hardware.org/?probe=eeccbdaf2a) | Apr 24, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [713bf3357d](https://linux-hardware.org/?probe=713bf3357d) | Apr 24, 2024 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [4a79911a5b](https://linux-hardware.org/?probe=4a79911a5b) | Apr 24, 2024 |
| ASUSTek       | P8H67-I                     | Desktop     | [0d76590ae1](https://linux-hardware.org/?probe=0d76590ae1) | Apr 24, 2024 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [e7bd7e1534](https://linux-hardware.org/?probe=e7bd7e1534) | Apr 24, 2024 |
| Unknown       | F42                         | Notebook    | [947c137825](https://linux-hardware.org/?probe=947c137825) | Apr 23, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e2f6ad6b51](https://linux-hardware.org/?probe=e2f6ad6b51) | Apr 23, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [12f44c7a5a](https://linux-hardware.org/?probe=12f44c7a5a) | Apr 23, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [34c23ebcd8](https://linux-hardware.org/?probe=34c23ebcd8) | Apr 23, 2024 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [6f1ba910cd](https://linux-hardware.org/?probe=6f1ba910cd) | Apr 23, 2024 |
| Dell          | 0VRWRC A00                  | Desktop     | [19c02bd31c](https://linux-hardware.org/?probe=19c02bd31c) | Apr 23, 2024 |
| Acer          | Aspire E5-575T              | Notebook    | [d91600e2a3](https://linux-hardware.org/?probe=d91600e2a3) | Apr 22, 2024 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [7e16d97409](https://linux-hardware.org/?probe=7e16d97409) | Apr 22, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [3b93c96edd](https://linux-hardware.org/?probe=3b93c96edd) | Apr 22, 2024 |
| Dell          | XPS MXC062                  | Notebook    | [3d7326b94d](https://linux-hardware.org/?probe=3d7326b94d) | Apr 22, 2024 |
| Dell          | XPS MXC062                  | Notebook    | [d217b8e5ee](https://linux-hardware.org/?probe=d217b8e5ee) | Apr 22, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e499f5d301](https://linux-hardware.org/?probe=e499f5d301) | Apr 22, 2024 |
| Unknown       | MAGNUS III                  | Tablet      | [d70dd67075](https://linux-hardware.org/?probe=d70dd67075) | Apr 21, 2024 |
| Dell          | 04HGFY A00                  | All in one  | [666912f9fa](https://linux-hardware.org/?probe=666912f9fa) | Apr 21, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [3a08b0b94e](https://linux-hardware.org/?probe=3a08b0b94e) | Apr 21, 2024 |
| Lenovo        | G470 20078                  | Notebook    | [63d40af7a3](https://linux-hardware.org/?probe=63d40af7a3) | Apr 21, 2024 |
| ASUSTek       | K75VM                       | Notebook    | [c863c3ba6b](https://linux-hardware.org/?probe=c863c3ba6b) | Apr 21, 2024 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [6dc8bf5698](https://linux-hardware.org/?probe=6dc8bf5698) | Apr 21, 2024 |
| Biostar       | H61MLV3                     | Desktop     | [a383411310](https://linux-hardware.org/?probe=a383411310) | Apr 21, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [84b68b02bf](https://linux-hardware.org/?probe=84b68b02bf) | Apr 21, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [49d3f7118d](https://linux-hardware.org/?probe=49d3f7118d) | Apr 21, 2024 |
| Lenovo        | ThinkCentre M58 7360C12     | Desktop     | [a1a3ba50dd](https://linux-hardware.org/?probe=a1a3ba50dd) | Apr 21, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [84aa58d0c4](https://linux-hardware.org/?probe=84aa58d0c4) | Apr 21, 2024 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | Notebook    | [a9c83df6f3](https://linux-hardware.org/?probe=a9c83df6f3) | Apr 20, 2024 |
| HP            | ZBook 15 G2                 | Notebook    | [af8df0069b](https://linux-hardware.org/?probe=af8df0069b) | Apr 20, 2024 |
| Teclast       | F6 Plus                     | Notebook    | [58aa179f3b](https://linux-hardware.org/?probe=58aa179f3b) | Apr 20, 2024 |
| HP            | ProBook 645 G4              | Notebook    | [5e0b981c4f](https://linux-hardware.org/?probe=5e0b981c4f) | Apr 20, 2024 |
| Dell          | Latitude E5520              | Notebook    | [1cc2969282](https://linux-hardware.org/?probe=1cc2969282) | Apr 20, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [ef45ce093c](https://linux-hardware.org/?probe=ef45ce093c) | Apr 20, 2024 |
| HP            | ProBook 4310s               | Notebook    | [9a51586fe9](https://linux-hardware.org/?probe=9a51586fe9) | Apr 20, 2024 |
| Dell          | Latitude E6430              | Notebook    | [6c19db1434](https://linux-hardware.org/?probe=6c19db1434) | Apr 20, 2024 |
| Acer          | Aspire A315-21              | Notebook    | [c05d2f5d20](https://linux-hardware.org/?probe=c05d2f5d20) | Apr 19, 2024 |
| Mediacom      | SmartBook Pro i5            | Notebook    | [fdc40cdd18](https://linux-hardware.org/?probe=fdc40cdd18) | Apr 19, 2024 |
| AXDIA Inte... | MAVEN WIN 12 PRO            | Tablet      | [963dab8edc](https://linux-hardware.org/?probe=963dab8edc) | Apr 19, 2024 |
| Tactus        | GeoBook 140                 | Notebook    | [aa4d027e01](https://linux-hardware.org/?probe=aa4d027e01) | Apr 19, 2024 |
| Dell          | Latitude E5420              | Notebook    | [f937473451](https://linux-hardware.org/?probe=f937473451) | Apr 19, 2024 |
| Lenovo        | G700 20251                  | Notebook    | [6f7a2c121a](https://linux-hardware.org/?probe=6f7a2c121a) | Apr 19, 2024 |
| HP            | 1632                        | Desktop     | [1a23bb9aba](https://linux-hardware.org/?probe=1a23bb9aba) | Apr 19, 2024 |
| HP            | 1632                        | Desktop     | [2d11bc974f](https://linux-hardware.org/?probe=2d11bc974f) | Apr 18, 2024 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [886d3b50ff](https://linux-hardware.org/?probe=886d3b50ff) | Apr 18, 2024 |
| Dynabook E... | Satellite Pro ET10-G-105    | Tablet      | [9b6b61c39a](https://linux-hardware.org/?probe=9b6b61c39a) | Apr 18, 2024 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [ae940fd7b0](https://linux-hardware.org/?probe=ae940fd7b0) | Apr 18, 2024 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [4d615a62ea](https://linux-hardware.org/?probe=4d615a62ea) | Apr 18, 2024 |
| ASRock        | A520M-HDV                   | Desktop     | [9a415b8705](https://linux-hardware.org/?probe=9a415b8705) | Apr 17, 2024 |
| Dell          | Latitude E6400              | Notebook    | [02a9b84151](https://linux-hardware.org/?probe=02a9b84151) | Apr 17, 2024 |
| Lenovo        | Yoga 720-13 IKB 80X6        | Convertible | [bbaeecc514](https://linux-hardware.org/?probe=bbaeecc514) | Apr 17, 2024 |
| ASUSTek       | M51Va                       | Notebook    | [2279fdf28b](https://linux-hardware.org/?probe=2279fdf28b) | Apr 17, 2024 |
| ASUSTek       | M51Va                       | Notebook    | [e2aa27e175](https://linux-hardware.org/?probe=e2aa27e175) | Apr 17, 2024 |
| HP            | ProBook 6560b               | Notebook    | [5ea8af85bf](https://linux-hardware.org/?probe=5ea8af85bf) | Apr 17, 2024 |
| Packard Be... | EasyNote TM86               | Notebook    | [05f38c567b](https://linux-hardware.org/?probe=05f38c567b) | Apr 17, 2024 |
| ASUSTek       | H110M-CS                    | Desktop     | [551218b127](https://linux-hardware.org/?probe=551218b127) | Apr 17, 2024 |
| HP            | ENVY Laptop 17-cw0xxx       | Notebook    | [c1ac91bae5](https://linux-hardware.org/?probe=c1ac91bae5) | Apr 16, 2024 |
| HP            | 1495                        | Desktop     | [cd403691ad](https://linux-hardware.org/?probe=cd403691ad) | Apr 16, 2024 |
| Acer          | Aspire A515-43              | Notebook    | [fcd5e8e59d](https://linux-hardware.org/?probe=fcd5e8e59d) | Apr 16, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [8973327d74](https://linux-hardware.org/?probe=8973327d74) | Apr 16, 2024 |
| Acer          | Swift SFG14-41              | Notebook    | [6fc0fc2e0c](https://linux-hardware.org/?probe=6fc0fc2e0c) | Apr 16, 2024 |
| Samsung       | 750XED                      | Notebook    | [fee3c81bf3](https://linux-hardware.org/?probe=fee3c81bf3) | Apr 16, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [9f2e93f394](https://linux-hardware.org/?probe=9f2e93f394) | Apr 16, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [528d3a590f](https://linux-hardware.org/?probe=528d3a590f) | Apr 16, 2024 |
| Medion        | E5218                       | Notebook    | [62b09e7720](https://linux-hardware.org/?probe=62b09e7720) | Apr 16, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [8ffae057e8](https://linux-hardware.org/?probe=8ffae057e8) | Apr 15, 2024 |
| HP            | 8299                        | Desktop     | [1a596e43da](https://linux-hardware.org/?probe=1a596e43da) | Apr 15, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [326bfaca84](https://linux-hardware.org/?probe=326bfaca84) | Apr 15, 2024 |
| ASRock        | A520M-HDV                   | Desktop     | [56905e2bc8](https://linux-hardware.org/?probe=56905e2bc8) | Apr 15, 2024 |
| HP            | 8299                        | Desktop     | [aa03fa8e4c](https://linux-hardware.org/?probe=aa03fa8e4c) | Apr 15, 2024 |
| ASRock        | A520M-HDV                   | Desktop     | [47e7cdb053](https://linux-hardware.org/?probe=47e7cdb053) | Apr 15, 2024 |
| HP            | Pavilion dv6                | Notebook    | [b914c1b7f6](https://linux-hardware.org/?probe=b914c1b7f6) | Apr 15, 2024 |
| MSI           | B250M BAZOOKA               | Desktop     | [b2b7ae9a04](https://linux-hardware.org/?probe=b2b7ae9a04) | Apr 15, 2024 |
| ASUSTek       | X551CA                      | Notebook    | [d050fff27d](https://linux-hardware.org/?probe=d050fff27d) | Apr 15, 2024 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [5785462109](https://linux-hardware.org/?probe=5785462109) | Apr 14, 2024 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [fb1d212b35](https://linux-hardware.org/?probe=fb1d212b35) | Apr 14, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [f65f90469b](https://linux-hardware.org/?probe=f65f90469b) | Apr 14, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [b3fc204759](https://linux-hardware.org/?probe=b3fc204759) | Apr 14, 2024 |
| Dell          | XPS 15 9550                 | Notebook    | [22d857c49c](https://linux-hardware.org/?probe=22d857c49c) | Apr 14, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [531ad46b31](https://linux-hardware.org/?probe=531ad46b31) | Apr 14, 2024 |
| Dell          | Latitude 3440               | Notebook    | [e334ba82e5](https://linux-hardware.org/?probe=e334ba82e5) | Apr 14, 2024 |
| Dell          | Latitude 3440               | Notebook    | [77e2af784e](https://linux-hardware.org/?probe=77e2af784e) | Apr 14, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [58b2e77917](https://linux-hardware.org/?probe=58b2e77917) | Apr 14, 2024 |
| Dell          | 0NK5PH A00                  | Desktop     | [f0cf8ecdba](https://linux-hardware.org/?probe=f0cf8ecdba) | Apr 14, 2024 |
| HP            | Pavilion dv6000 (GM695LA... | Notebook    | [21796df3a5](https://linux-hardware.org/?probe=21796df3a5) | Apr 14, 2024 |
| Unknown       | Unknown                     | Notebook    | [b6ce023a2a](https://linux-hardware.org/?probe=b6ce023a2a) | Apr 13, 2024 |
| Tactus        | GeoPad 220                  | Tablet      | [6e8eb0d9f3](https://linux-hardware.org/?probe=6e8eb0d9f3) | Apr 13, 2024 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [caa72afe3c](https://linux-hardware.org/?probe=caa72afe3c) | Apr 13, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [351fd4ce06](https://linux-hardware.org/?probe=351fd4ce06) | Apr 13, 2024 |
| ASUSTek       | E402SA                      | Notebook    | [5266b4e65d](https://linux-hardware.org/?probe=5266b4e65d) | Apr 13, 2024 |
| Samsung       | R519/R719                   | Notebook    | [236c296c4d](https://linux-hardware.org/?probe=236c296c4d) | Apr 13, 2024 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [62cafd8bff](https://linux-hardware.org/?probe=62cafd8bff) | Apr 13, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [07844c11ad](https://linux-hardware.org/?probe=07844c11ad) | Apr 13, 2024 |
| Dell          | Inspiron 1521               | Notebook    | [0eae25d659](https://linux-hardware.org/?probe=0eae25d659) | Apr 13, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [5b025453c2](https://linux-hardware.org/?probe=5b025453c2) | Apr 13, 2024 |
| Acer          | E1-510                      | Notebook    | [a3809aca83](https://linux-hardware.org/?probe=a3809aca83) | Apr 13, 2024 |
| Acer          | Aspire 5715Z                | Notebook    | [25a3bb97f8](https://linux-hardware.org/?probe=25a3bb97f8) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [983a566cbf](https://linux-hardware.org/?probe=983a566cbf) | Apr 13, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [e2bf219dba](https://linux-hardware.org/?probe=e2bf219dba) | Apr 13, 2024 |
| ASUSTek       | N552VW                      | Notebook    | [02c36db055](https://linux-hardware.org/?probe=02c36db055) | Apr 12, 2024 |
| Acer          | Aspire 8943G                | Notebook    | [02488e8ac4](https://linux-hardware.org/?probe=02488e8ac4) | Apr 12, 2024 |
| HP            | 829A                        | Mini pc     | [f9c3cc7bef](https://linux-hardware.org/?probe=f9c3cc7bef) | Apr 12, 2024 |
| Dell          | 0T10XW A00                  | Desktop     | [f899cbf1fc](https://linux-hardware.org/?probe=f899cbf1fc) | Apr 12, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e0ff52d20a](https://linux-hardware.org/?probe=e0ff52d20a) | Apr 12, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [580425d3b2](https://linux-hardware.org/?probe=580425d3b2) | Apr 12, 2024 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [39d3eeda79](https://linux-hardware.org/?probe=39d3eeda79) | Apr 12, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [6bdfe181ea](https://linux-hardware.org/?probe=6bdfe181ea) | Apr 12, 2024 |
| Dell          | Inspiron 5770               | Notebook    | [ae5ccdd8ac](https://linux-hardware.org/?probe=ae5ccdd8ac) | Apr 12, 2024 |
| Lenovo        | G550 2958                   | Notebook    | [2cebfc34df](https://linux-hardware.org/?probe=2cebfc34df) | Apr 12, 2024 |
| Lenovo        | ThinkPad T520 4243F53       | Notebook    | [9996ba8710](https://linux-hardware.org/?probe=9996ba8710) | Apr 12, 2024 |
| Toshiba       | Satellite S55t-A            | Notebook    | [83f4844e2a](https://linux-hardware.org/?probe=83f4844e2a) | Apr 12, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9eed5870ee](https://linux-hardware.org/?probe=9eed5870ee) | Apr 12, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [875d44f61b](https://linux-hardware.org/?probe=875d44f61b) | Apr 12, 2024 |
| HP            | 15                          | Notebook    | [4f0433464d](https://linux-hardware.org/?probe=4f0433464d) | Apr 12, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [d0eaff6eb9](https://linux-hardware.org/?probe=d0eaff6eb9) | Apr 11, 2024 |
| ASUSTek       | G752VY                      | Notebook    | [039e830652](https://linux-hardware.org/?probe=039e830652) | Apr 11, 2024 |
| Positivo      | J14KR11                     | Notebook    | [f6a61def89](https://linux-hardware.org/?probe=f6a61def89) | Apr 11, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [33e3402952](https://linux-hardware.org/?probe=33e3402952) | Apr 11, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [6fee790c89](https://linux-hardware.org/?probe=6fee790c89) | Apr 11, 2024 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [8d6c663fc1](https://linux-hardware.org/?probe=8d6c663fc1) | Apr 11, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [11e58d238c](https://linux-hardware.org/?probe=11e58d238c) | Apr 11, 2024 |
| Lenovo        | ThinkPad Helix 2nd 20CG0... | Tablet      | [b9b505fe05](https://linux-hardware.org/?probe=b9b505fe05) | Apr 11, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7ee8e88f7e](https://linux-hardware.org/?probe=7ee8e88f7e) | Apr 11, 2024 |
| Dell          | Inspiron 5770               | Notebook    | [6cb8fb3865](https://linux-hardware.org/?probe=6cb8fb3865) | Apr 11, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [e820d6337a](https://linux-hardware.org/?probe=e820d6337a) | Apr 11, 2024 |
| Avell High... | Avell G1513 MUV / A52 MU... | Notebook    | [839c6f47f8](https://linux-hardware.org/?probe=839c6f47f8) | Apr 11, 2024 |
| ASUSTek       | N552VW                      | Notebook    | [981a9ddf63](https://linux-hardware.org/?probe=981a9ddf63) | Apr 11, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [0c29f72def](https://linux-hardware.org/?probe=0c29f72def) | Apr 10, 2024 |
| Dell          | Latitude E5550              | Notebook    | [bd812fbe85](https://linux-hardware.org/?probe=bd812fbe85) | Apr 10, 2024 |
| NCR           | Pocono                      | Desktop     | [fb4ef04821](https://linux-hardware.org/?probe=fb4ef04821) | Apr 10, 2024 |
| Dell          | Vostro 2421                 | Notebook    | [0ba1cc79bc](https://linux-hardware.org/?probe=0ba1cc79bc) | Apr 10, 2024 |
| Dell          | Latitude 5500               | Notebook    | [59a70a843f](https://linux-hardware.org/?probe=59a70a843f) | Apr 10, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [fa8ded5b0e](https://linux-hardware.org/?probe=fa8ded5b0e) | Apr 10, 2024 |
| Pegatron      | 2A73h                       | Desktop     | [941a2d0e0d](https://linux-hardware.org/?probe=941a2d0e0d) | Apr 10, 2024 |
| Dell          | Vostro 2421                 | Notebook    | [905003a077](https://linux-hardware.org/?probe=905003a077) | Apr 10, 2024 |
| Microsoft     | Surface Laptop 3            | Tablet      | [bdc3fabb83](https://linux-hardware.org/?probe=bdc3fabb83) | Apr 10, 2024 |
| Lenovo        | U310                        | Notebook    | [e8e1dce51e](https://linux-hardware.org/?probe=e8e1dce51e) | Apr 10, 2024 |
| Lenovo        | U310                        | Notebook    | [fba6029f49](https://linux-hardware.org/?probe=fba6029f49) | Apr 10, 2024 |
| Microsoft     | Surface Laptop 3            | Tablet      | [01a95cb93f](https://linux-hardware.org/?probe=01a95cb93f) | Apr 10, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [32010db3bd](https://linux-hardware.org/?probe=32010db3bd) | Apr 09, 2024 |
| HP            | 339A                        | Desktop     | [e7fb50b1c8](https://linux-hardware.org/?probe=e7fb50b1c8) | Apr 09, 2024 |
| Dell          | 0XCR8D A01                  | Desktop     | [9d38e92df0](https://linux-hardware.org/?probe=9d38e92df0) | Apr 09, 2024 |
| Dell          | 0XCR8D A01                  | Desktop     | [a0b8193ba4](https://linux-hardware.org/?probe=a0b8193ba4) | Apr 09, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [7fe3c3fa19](https://linux-hardware.org/?probe=7fe3c3fa19) | Apr 09, 2024 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [b0310dc9d9](https://linux-hardware.org/?probe=b0310dc9d9) | Apr 09, 2024 |
| Intel         | H61                         | Desktop     | [cfc6e7e901](https://linux-hardware.org/?probe=cfc6e7e901) | Apr 09, 2024 |
| Dell          | 0VYXHD A00                  | Desktop     | [c0cfa74664](https://linux-hardware.org/?probe=c0cfa74664) | Apr 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [24377a30f1](https://linux-hardware.org/?probe=24377a30f1) | Apr 09, 2024 |
| Alienware     | 0T76PD A01                  | Desktop     | [79ec44cce4](https://linux-hardware.org/?probe=79ec44cce4) | Apr 09, 2024 |
| HP            | Pavilion dm4                | Notebook    | [5df83aab55](https://linux-hardware.org/?probe=5df83aab55) | Apr 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [fbf6dbe5f2](https://linux-hardware.org/?probe=fbf6dbe5f2) | Apr 09, 2024 |
| MSI           | Katana 15 B13VGK            | Notebook    | [a4a53a031a](https://linux-hardware.org/?probe=a4a53a031a) | Apr 09, 2024 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [4b373f33aa](https://linux-hardware.org/?probe=4b373f33aa) | Apr 08, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [39dff10b12](https://linux-hardware.org/?probe=39dff10b12) | Apr 08, 2024 |
| MSI           | PR600                       | Notebook    | [ae78fa3936](https://linux-hardware.org/?probe=ae78fa3936) | Apr 08, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [6f8f2695ef](https://linux-hardware.org/?probe=6f8f2695ef) | Apr 08, 2024 |
| Teclast       | F15                         | Notebook    | [fdbca364e4](https://linux-hardware.org/?probe=fdbca364e4) | Apr 08, 2024 |
| Teclast       | F15                         | Notebook    | [a36f18a41b](https://linux-hardware.org/?probe=a36f18a41b) | Apr 08, 2024 |
| Lenovo        | ThinkPad T440p 20AN006GU... | Notebook    | [eb5a1b8ef9](https://linux-hardware.org/?probe=eb5a1b8ef9) | Apr 08, 2024 |
| Lenovo        | ThinkPad T440p 20AN006GU... | Notebook    | [14bede5648](https://linux-hardware.org/?probe=14bede5648) | Apr 08, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [334edc82aa](https://linux-hardware.org/?probe=334edc82aa) | Apr 07, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [87b303490c](https://linux-hardware.org/?probe=87b303490c) | Apr 07, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [35d9b4afce](https://linux-hardware.org/?probe=35d9b4afce) | Apr 07, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [490787ceee](https://linux-hardware.org/?probe=490787ceee) | Apr 07, 2024 |
| Dell          | 0V8WGR A02                  | Desktop     | [c8eb38c52c](https://linux-hardware.org/?probe=c8eb38c52c) | Apr 07, 2024 |
| Samsung       | R530/R730                   | Notebook    | [edc9fc5a6f](https://linux-hardware.org/?probe=edc9fc5a6f) | Apr 07, 2024 |
| Apple         | Mac-F2238AC8                | All in one  | [79bfecb0bc](https://linux-hardware.org/?probe=79bfecb0bc) | Apr 07, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [42e382179c](https://linux-hardware.org/?probe=42e382179c) | Apr 07, 2024 |
| Gigabyte      | G41M-Combo                  | Desktop     | [4fa66fe035](https://linux-hardware.org/?probe=4fa66fe035) | Apr 07, 2024 |
| HP            | Pavilion dv6                | Notebook    | [bc5b62eec9](https://linux-hardware.org/?probe=bc5b62eec9) | Apr 06, 2024 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [b87b1a20b9](https://linux-hardware.org/?probe=b87b1a20b9) | Apr 06, 2024 |
| MSI           | GT70 2PE                    | Notebook    | [13f21446e0](https://linux-hardware.org/?probe=13f21446e0) | Apr 06, 2024 |
| MSI           | CX600                       | Notebook    | [a8d66c3a93](https://linux-hardware.org/?probe=a8d66c3a93) | Apr 06, 2024 |
| MSI           | CX600                       | Notebook    | [edf0e2393f](https://linux-hardware.org/?probe=edf0e2393f) | Apr 06, 2024 |
| Dell          | Latitude E7440              | Notebook    | [dbc6236ae1](https://linux-hardware.org/?probe=dbc6236ae1) | Apr 06, 2024 |
| HP            | 1905                        | Desktop     | [d55405d144](https://linux-hardware.org/?probe=d55405d144) | Apr 06, 2024 |
| Dell          | Inspiron 5770               | Notebook    | [2c6ced3f53](https://linux-hardware.org/?probe=2c6ced3f53) | Apr 06, 2024 |
| Unknown       | V00                         | Mini pc     | [0042a5ed09](https://linux-hardware.org/?probe=0042a5ed09) | Apr 06, 2024 |
| Unknown       | V00                         | Mini pc     | [5321b9d9a3](https://linux-hardware.org/?probe=5321b9d9a3) | Apr 06, 2024 |
| Lenovo        | 14w Gen 2 82N8              | Notebook    | [918db0c202](https://linux-hardware.org/?probe=918db0c202) | Apr 05, 2024 |
| Dell          | Studio 1747                 | Notebook    | [33e2d94187](https://linux-hardware.org/?probe=33e2d94187) | Apr 05, 2024 |
| STGAUBRON     | B75M4 V1.1                  | Desktop     | [243f4caa39](https://linux-hardware.org/?probe=243f4caa39) | Apr 05, 2024 |
| Lenovo        | 14w Gen 2 82N8              | Notebook    | [07d45eb08b](https://linux-hardware.org/?probe=07d45eb08b) | Apr 05, 2024 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [3d77de9e9d](https://linux-hardware.org/?probe=3d77de9e9d) | Apr 05, 2024 |
| MSI           | Katana 15 B13VGK            | Notebook    | [c5099db6ec](https://linux-hardware.org/?probe=c5099db6ec) | Apr 05, 2024 |
| Positivo      | C4128B-1                    | Convertible | [53d0a1757c](https://linux-hardware.org/?probe=53d0a1757c) | Apr 05, 2024 |
| Dell          | 08HPGT A01                  | Desktop     | [355095de09](https://linux-hardware.org/?probe=355095de09) | Apr 05, 2024 |
| Dell          | 08HPGT A01                  | Desktop     | [8d0476dbc7](https://linux-hardware.org/?probe=8d0476dbc7) | Apr 05, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [819d681431](https://linux-hardware.org/?probe=819d681431) | Apr 05, 2024 |
| ASRock        | H81M-HDS                    | Desktop     | [068539b9ec](https://linux-hardware.org/?probe=068539b9ec) | Apr 05, 2024 |
| TODOS INDU... | Aprix_2022_V1               | Notebook    | [97ae5afa87](https://linux-hardware.org/?probe=97ae5afa87) | Apr 05, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [5121a12ba5](https://linux-hardware.org/?probe=5121a12ba5) | Apr 05, 2024 |
| Lenovo        | ThinkPad T460s 20F9003GU... | Notebook    | [497b326dc9](https://linux-hardware.org/?probe=497b326dc9) | Apr 04, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [ee4bb4963a](https://linux-hardware.org/?probe=ee4bb4963a) | Apr 04, 2024 |
| HP            | G62                         | Notebook    | [1c70131cdf](https://linux-hardware.org/?probe=1c70131cdf) | Apr 04, 2024 |
| HUAWEI        | YTF-XXX                     | Notebook    | [0ca4e52c33](https://linux-hardware.org/?probe=0ca4e52c33) | Apr 04, 2024 |
| Google        | Landrid                     | Notebook    | [d4b1948b6a](https://linux-hardware.org/?probe=d4b1948b6a) | Apr 04, 2024 |
| Sony          | VPCS131FM                   | Notebook    | [6065941e59](https://linux-hardware.org/?probe=6065941e59) | Apr 04, 2024 |
| Dell          | Latitude E7470              | Notebook    | [ea70b2caa0](https://linux-hardware.org/?probe=ea70b2caa0) | Apr 04, 2024 |
| HUAWEI        | YTF-XXX                     | Notebook    | [d1703a058f](https://linux-hardware.org/?probe=d1703a058f) | Apr 04, 2024 |
| Positivo      | C14CR01                     | Notebook    | [a707fed87d](https://linux-hardware.org/?probe=a707fed87d) | Apr 03, 2024 |
| Unknown       | 1.0                         | Desktop     | [a9918419c7](https://linux-hardware.org/?probe=a9918419c7) | Apr 03, 2024 |
| Toshiba       | NB520                       | Notebook    | [d347b22da0](https://linux-hardware.org/?probe=d347b22da0) | Apr 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [eb3179b973](https://linux-hardware.org/?probe=eb3179b973) | Apr 03, 2024 |
| HUAWEI        | KLVF-XX                     | Notebook    | [16fc53e7bb](https://linux-hardware.org/?probe=16fc53e7bb) | Apr 03, 2024 |
| Foxconn       | G31MX Series                | Desktop     | [283c7c622c](https://linux-hardware.org/?probe=283c7c622c) | Apr 03, 2024 |
| HP            | Notebook                    | Notebook    | [7ed4d5435b](https://linux-hardware.org/?probe=7ed4d5435b) | Apr 03, 2024 |
| Gateway       | SX2851                      | Desktop     | [099ecc5b59](https://linux-hardware.org/?probe=099ecc5b59) | Apr 03, 2024 |
| Pegatron      | JESSE                       | Desktop     | [1f14f883ca](https://linux-hardware.org/?probe=1f14f883ca) | Apr 02, 2024 |
| MSI           | H81M-E34                    | Desktop     | [62882b5228](https://linux-hardware.org/?probe=62882b5228) | Apr 02, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [66c82e0097](https://linux-hardware.org/?probe=66c82e0097) | Apr 02, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [b11c8d5ca0](https://linux-hardware.org/?probe=b11c8d5ca0) | Apr 02, 2024 |
| Acer          | Swift SFX14-71G             | Notebook    | [c9acd12744](https://linux-hardware.org/?probe=c9acd12744) | Apr 02, 2024 |
| HP            | Notebook                    | Notebook    | [cefd396a65](https://linux-hardware.org/?probe=cefd396a65) | Apr 02, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [9c392ce1f2](https://linux-hardware.org/?probe=9c392ce1f2) | Apr 02, 2024 |
| Dell          | System XPS L502X            | Notebook    | [78f6ea571d](https://linux-hardware.org/?probe=78f6ea571d) | Apr 02, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [1d0e019001](https://linux-hardware.org/?probe=1d0e019001) | Apr 01, 2024 |
| HP            | ProBook 6570b               | Notebook    | [cf9fba8256](https://linux-hardware.org/?probe=cf9fba8256) | Apr 01, 2024 |
| HP            | ProBook 6570b               | Notebook    | [a26b2f6f54](https://linux-hardware.org/?probe=a26b2f6f54) | Apr 01, 2024 |
| Dell          | Inspiron 5448               | Notebook    | [34d0f4de88](https://linux-hardware.org/?probe=34d0f4de88) | Apr 01, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [efd659b2da](https://linux-hardware.org/?probe=efd659b2da) | Apr 01, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [cccef069f7](https://linux-hardware.org/?probe=cccef069f7) | Apr 01, 2024 |
| ASRock        | H310CM-DVS                  | Desktop     | [c543e25407](https://linux-hardware.org/?probe=c543e25407) | Mar 31, 2024 |
| ASRock        | H310CM-DVS                  | Desktop     | [39914bc3e6](https://linux-hardware.org/?probe=39914bc3e6) | Mar 31, 2024 |
| Trigkey       | S5 V2.0                     | Mini pc     | [8374427ff8](https://linux-hardware.org/?probe=8374427ff8) | Mar 31, 2024 |
| HP            | ProBook 4540s               | Notebook    | [c641dc440f](https://linux-hardware.org/?probe=c641dc440f) | Mar 31, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [774bbfd144](https://linux-hardware.org/?probe=774bbfd144) | Mar 31, 2024 |
| Dell          | Latitude 7480               | Notebook    | [0ab21a354e](https://linux-hardware.org/?probe=0ab21a354e) | Mar 31, 2024 |
| HP            | ProBook 4540s               | Notebook    | [c50c3376e9](https://linux-hardware.org/?probe=c50c3376e9) | Mar 31, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [083640b754](https://linux-hardware.org/?probe=083640b754) | Mar 31, 2024 |
| HP            | 15                          | Notebook    | [e1c7ccf97a](https://linux-hardware.org/?probe=e1c7ccf97a) | Mar 31, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [c32641d945](https://linux-hardware.org/?probe=c32641d945) | Mar 31, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [740eb90402](https://linux-hardware.org/?probe=740eb90402) | Mar 30, 2024 |
| ASRock        | 990FX Extreme3              | Desktop     | [1c846440f3](https://linux-hardware.org/?probe=1c846440f3) | Mar 30, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [2fa735d18d](https://linux-hardware.org/?probe=2fa735d18d) | Mar 30, 2024 |
| TODOS INDU... | Aprix_2022_V1               | Notebook    | [e5e980e4f5](https://linux-hardware.org/?probe=e5e980e4f5) | Mar 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [cd151074ab](https://linux-hardware.org/?probe=cd151074ab) | Mar 30, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [9577fddfae](https://linux-hardware.org/?probe=9577fddfae) | Mar 30, 2024 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [890d342e54](https://linux-hardware.org/?probe=890d342e54) | Mar 30, 2024 |
| ASUSTek       | K73SD                       | Notebook    | [4002cbf0dd](https://linux-hardware.org/?probe=4002cbf0dd) | Mar 30, 2024 |
| Lenovo        | VIWZ1                       | Notebook    | [c62b77ffa8](https://linux-hardware.org/?probe=c62b77ffa8) | Mar 30, 2024 |
| Lenovo        | VIWZ1                       | Notebook    | [8ab6be2fcb](https://linux-hardware.org/?probe=8ab6be2fcb) | Mar 30, 2024 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [91bd726aad](https://linux-hardware.org/?probe=91bd726aad) | Mar 30, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [43ed029da9](https://linux-hardware.org/?probe=43ed029da9) | Mar 30, 2024 |
| Dell          | 051FJ8 A01                  | Desktop     | [05e406828c](https://linux-hardware.org/?probe=05e406828c) | Mar 29, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [da4de8a0b3](https://linux-hardware.org/?probe=da4de8a0b3) | Mar 29, 2024 |
| ASRock        | 980DE3/U3S3 R2.0            | Desktop     | [31798dfffc](https://linux-hardware.org/?probe=31798dfffc) | Mar 29, 2024 |
| ASUSTek       | S451LA                      | Notebook    | [bc6298d214](https://linux-hardware.org/?probe=bc6298d214) | Mar 29, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [3333f04923](https://linux-hardware.org/?probe=3333f04923) | Mar 29, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [2436c8e791](https://linux-hardware.org/?probe=2436c8e791) | Mar 29, 2024 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [81603f2f58](https://linux-hardware.org/?probe=81603f2f58) | Mar 29, 2024 |
| Sony          | VPCY11S1E                   | Notebook    | [905655032f](https://linux-hardware.org/?probe=905655032f) | Mar 29, 2024 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | Notebook    | [01ec795558](https://linux-hardware.org/?probe=01ec795558) | Mar 29, 2024 |
| Lenovo        | ThinkPad X220 429137G       | Notebook    | [07863dff89](https://linux-hardware.org/?probe=07863dff89) | Mar 29, 2024 |
| HP            | EliteBook 8760w             | Notebook    | [5666dfc34e](https://linux-hardware.org/?probe=5666dfc34e) | Mar 29, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [a3d6e9239d](https://linux-hardware.org/?probe=a3d6e9239d) | Mar 29, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [00e4cbdc6e](https://linux-hardware.org/?probe=00e4cbdc6e) | Mar 29, 2024 |
| ASRock        | Z87 Extreme6                | Desktop     | [eaf00b2d47](https://linux-hardware.org/?probe=eaf00b2d47) | Mar 29, 2024 |
| Gigabyte      | G41M-Combo                  | Desktop     | [de15aa9a55](https://linux-hardware.org/?probe=de15aa9a55) | Mar 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [568697e488](https://linux-hardware.org/?probe=568697e488) | Mar 28, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [b90fd9c218](https://linux-hardware.org/?probe=b90fd9c218) | Mar 28, 2024 |
| Microsoft     | Surface Pro 9               | Tablet      | [1ae607e490](https://linux-hardware.org/?probe=1ae607e490) | Mar 28, 2024 |
| Lenovo        | ThinkPad E470 20H1006KGE    | Notebook    | [494ac5439c](https://linux-hardware.org/?probe=494ac5439c) | Mar 28, 2024 |
| Samsung       | 730U3E/740U3E               | Notebook    | [cbadd5a34d](https://linux-hardware.org/?probe=cbadd5a34d) | Mar 28, 2024 |
| HP            | 0B54h D                     | Desktop     | [e7d521b51c](https://linux-hardware.org/?probe=e7d521b51c) | Mar 28, 2024 |
| Intel         | D2700MUD AAG32419-602       | Desktop     | [52eec4d012](https://linux-hardware.org/?probe=52eec4d012) | Mar 28, 2024 |
| ASRock        | Z87 Extreme6                | Desktop     | [0980c3538e](https://linux-hardware.org/?probe=0980c3538e) | Mar 28, 2024 |
| FW00152       | Unknown                     | Notebook    | [aefa8aa487](https://linux-hardware.org/?probe=aefa8aa487) | Mar 28, 2024 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [77bf8490e6](https://linux-hardware.org/?probe=77bf8490e6) | Mar 28, 2024 |
| FW00152       | Unknown                     | Notebook    | [5ae4c0edc0](https://linux-hardware.org/?probe=5ae4c0edc0) | Mar 28, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [45dd079807](https://linux-hardware.org/?probe=45dd079807) | Mar 27, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7de05d2618](https://linux-hardware.org/?probe=7de05d2618) | Mar 27, 2024 |
| Dell          | G15 5530                    | Notebook    | [e2421ca4e6](https://linux-hardware.org/?probe=e2421ca4e6) | Mar 27, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [577e8ee500](https://linux-hardware.org/?probe=577e8ee500) | Mar 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [78e0afbb5f](https://linux-hardware.org/?probe=78e0afbb5f) | Mar 27, 2024 |
| Dell          | Inspiron 17-7779            | Notebook    | [deecf7220f](https://linux-hardware.org/?probe=deecf7220f) | Mar 27, 2024 |
| HP            | ProBook 650 G3              | Notebook    | [4f8758ae5b](https://linux-hardware.org/?probe=4f8758ae5b) | Mar 27, 2024 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [a7b3ddbaee](https://linux-hardware.org/?probe=a7b3ddbaee) | Mar 27, 2024 |
| Proline       | V1165C4                     | Notebook    | [026d6324c2](https://linux-hardware.org/?probe=026d6324c2) | Mar 27, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c5020d4c73](https://linux-hardware.org/?probe=c5020d4c73) | Mar 27, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1d78b76824](https://linux-hardware.org/?probe=1d78b76824) | Mar 27, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [87c9d49e4d](https://linux-hardware.org/?probe=87c9d49e4d) | Mar 27, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [029e810271](https://linux-hardware.org/?probe=029e810271) | Mar 27, 2024 |
| Pegatron      | 2A73h                       | Desktop     | [193e8e5cb1](https://linux-hardware.org/?probe=193e8e5cb1) | Mar 26, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [f081fc7478](https://linux-hardware.org/?probe=f081fc7478) | Mar 26, 2024 |
| HP            | 255 15.6 inch G10           | Notebook    | [4fb9cfdc6b](https://linux-hardware.org/?probe=4fb9cfdc6b) | Mar 26, 2024 |
| HP            | ProBook 650 G3              | Notebook    | [bed68c1872](https://linux-hardware.org/?probe=bed68c1872) | Mar 26, 2024 |
| MSI           | B350 TOMAHAWK               | Desktop     | [10ca4510ec](https://linux-hardware.org/?probe=10ca4510ec) | Mar 26, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [704e412f17](https://linux-hardware.org/?probe=704e412f17) | Mar 26, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [4f85864b8b](https://linux-hardware.org/?probe=4f85864b8b) | Mar 26, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [bbe46521b3](https://linux-hardware.org/?probe=bbe46521b3) | Mar 26, 2024 |
| HP            | Compaq CQ58                 | Notebook    | [bfe7fd8a2e](https://linux-hardware.org/?probe=bfe7fd8a2e) | Mar 26, 2024 |
| Acer          | Aspire X3450                | Desktop     | [5b799c7536](https://linux-hardware.org/?probe=5b799c7536) | Mar 26, 2024 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [a549e35cf7](https://linux-hardware.org/?probe=a549e35cf7) | Mar 26, 2024 |
| Dell          | Vostro 1550                 | Notebook    | [e022440d75](https://linux-hardware.org/?probe=e022440d75) | Mar 26, 2024 |
| Chuwi         | HeroBook Pro                | Notebook    | [32fa9dc29b](https://linux-hardware.org/?probe=32fa9dc29b) | Mar 26, 2024 |
| HP            | Compaq CQ58                 | Notebook    | [806d659258](https://linux-hardware.org/?probe=806d659258) | Mar 26, 2024 |
| Dell          | System XPS L502X            | Notebook    | [d5930c810f](https://linux-hardware.org/?probe=d5930c810f) | Mar 26, 2024 |
| Dell          | System XPS L502X            | Notebook    | [8ccefaf9d8](https://linux-hardware.org/?probe=8ccefaf9d8) | Mar 25, 2024 |
| Toshiba       | Satellite Pro L500          | Notebook    | [61988ef678](https://linux-hardware.org/?probe=61988ef678) | Mar 25, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [f0a5bd62b5](https://linux-hardware.org/?probe=f0a5bd62b5) | Mar 25, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [9234465ff0](https://linux-hardware.org/?probe=9234465ff0) | Mar 25, 2024 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0545e1229e](https://linux-hardware.org/?probe=0545e1229e) | Mar 25, 2024 |
| Toshiba       | Satellite L355D             | Notebook    | [fd8ddd8b99](https://linux-hardware.org/?probe=fd8ddd8b99) | Mar 25, 2024 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [feb35a6b9c](https://linux-hardware.org/?probe=feb35a6b9c) | Mar 25, 2024 |
| Dell          | 01TKCC A01                  | Desktop     | [65070b32f2](https://linux-hardware.org/?probe=65070b32f2) | Mar 25, 2024 |
| HP            | 3029h                       | Desktop     | [1913f87768](https://linux-hardware.org/?probe=1913f87768) | Mar 25, 2024 |
| ASUSTek       | P8Z77-V                     | Desktop     | [ec744f652d](https://linux-hardware.org/?probe=ec744f652d) | Mar 25, 2024 |
| ASUSTek       | P8Z77-V                     | Desktop     | [89c81c0a65](https://linux-hardware.org/?probe=89c81c0a65) | Mar 25, 2024 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [bd8b34f997](https://linux-hardware.org/?probe=bd8b34f997) | Mar 25, 2024 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [cc1081606b](https://linux-hardware.org/?probe=cc1081606b) | Mar 25, 2024 |
| HP            | 8767 A                      | Desktop     | [167796eedc](https://linux-hardware.org/?probe=167796eedc) | Mar 25, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [eebe4dd8a0](https://linux-hardware.org/?probe=eebe4dd8a0) | Mar 25, 2024 |
| Toshiba       | IS 1413G                    | Notebook    | [782f26bdde](https://linux-hardware.org/?probe=782f26bdde) | Mar 25, 2024 |
| Dell          | 0KWVT8 A00                  | Desktop     | [ae811bf4d9](https://linux-hardware.org/?probe=ae811bf4d9) | Mar 24, 2024 |
| Dynabook E... | Satellite Pro ET10-G-106    | Tablet      | [8a6419cc9a](https://linux-hardware.org/?probe=8a6419cc9a) | Mar 24, 2024 |
| Dynabook E... | Satellite Pro ET10-G-106    | Tablet      | [e749252840](https://linux-hardware.org/?probe=e749252840) | Mar 24, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [aca396f8b2](https://linux-hardware.org/?probe=aca396f8b2) | Mar 24, 2024 |
| HP            | 86F1 10100                  | All in one  | [b322e697b4](https://linux-hardware.org/?probe=b322e697b4) | Mar 24, 2024 |
| HUAWEI        | DQF-XX-PCB M1010            | All in one  | [eaa94b1235](https://linux-hardware.org/?probe=eaa94b1235) | Mar 24, 2024 |
| HP            | 1905                        | Desktop     | [ee5ca084c4](https://linux-hardware.org/?probe=ee5ca084c4) | Mar 24, 2024 |
| Lenovo        | IdeaPad C340-15IML 81TL     | Convertible | [5104e23058](https://linux-hardware.org/?probe=5104e23058) | Mar 24, 2024 |
| HUAWEI        | DQF-XX-PCB M1010            | All in one  | [60daa47169](https://linux-hardware.org/?probe=60daa47169) | Mar 24, 2024 |
| HP            | ProBook 445 G7              | Notebook    | [5586958ad8](https://linux-hardware.org/?probe=5586958ad8) | Mar 24, 2024 |
| ASUSTek       | N53SM                       | Notebook    | [bcb219bdc4](https://linux-hardware.org/?probe=bcb219bdc4) | Mar 24, 2024 |
| Positivo      | C4128B-1                    | Convertible | [78e1fa79f3](https://linux-hardware.org/?probe=78e1fa79f3) | Mar 24, 2024 |
| HP            | 1905                        | Desktop     | [05c7e6e706](https://linux-hardware.org/?probe=05c7e6e706) | Mar 24, 2024 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [ef8c9d2a46](https://linux-hardware.org/?probe=ef8c9d2a46) | Mar 24, 2024 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [91a269a388](https://linux-hardware.org/?probe=91a269a388) | Mar 24, 2024 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [9ef9218d97](https://linux-hardware.org/?probe=9ef9218d97) | Mar 24, 2024 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [526ba57aee](https://linux-hardware.org/?probe=526ba57aee) | Mar 24, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [f8ca0e66e2](https://linux-hardware.org/?probe=f8ca0e66e2) | Mar 24, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [b911c5e72d](https://linux-hardware.org/?probe=b911c5e72d) | Mar 24, 2024 |
| HP            | Pavilion dv5                | Notebook    | [72da06e33c](https://linux-hardware.org/?probe=72da06e33c) | Mar 24, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [d3025e223c](https://linux-hardware.org/?probe=d3025e223c) | Mar 24, 2024 |
| Lenovo        | ThinkPad X230 2325PB3       | Notebook    | [399c0cd75c](https://linux-hardware.org/?probe=399c0cd75c) | Mar 23, 2024 |
| HP            | 2ADC                        | Desktop     | [d94b5fa4e7](https://linux-hardware.org/?probe=d94b5fa4e7) | Mar 23, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [c52682f980](https://linux-hardware.org/?probe=c52682f980) | Mar 23, 2024 |
| HP            | 15                          | Notebook    | [139e556699](https://linux-hardware.org/?probe=139e556699) | Mar 23, 2024 |
| Positivo      | Q232A                       | Notebook    | [46c3ff72eb](https://linux-hardware.org/?probe=46c3ff72eb) | Mar 23, 2024 |
| Positivo      | Q232A                       | Notebook    | [924bb4b4ee](https://linux-hardware.org/?probe=924bb4b4ee) | Mar 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [aaafb945bc](https://linux-hardware.org/?probe=aaafb945bc) | Mar 23, 2024 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [5d0f3460a5](https://linux-hardware.org/?probe=5d0f3460a5) | Mar 23, 2024 |
| Gigabyte      | B550 UD AC-Y1               | Desktop     | [8c6f8835ea](https://linux-hardware.org/?probe=8c6f8835ea) | Mar 23, 2024 |
| Acer          | Aspire 4739                 | Notebook    | [cdcf8bfc41](https://linux-hardware.org/?probe=cdcf8bfc41) | Mar 23, 2024 |
| Lenovo        | ThinkCentre M58p 6234FB9    | Desktop     | [38a5a34e54](https://linux-hardware.org/?probe=38a5a34e54) | Mar 23, 2024 |
| AZW           | U59                         | Desktop     | [06a180e5a9](https://linux-hardware.org/?probe=06a180e5a9) | Mar 22, 2024 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | Notebook    | [3bb5d80e00](https://linux-hardware.org/?probe=3bb5d80e00) | Mar 22, 2024 |
| HP            | Pro x2 612 G2               | Tablet      | [78b3bd7efb](https://linux-hardware.org/?probe=78b3bd7efb) | Mar 22, 2024 |
| HP            | Pro x2 612 G2               | Tablet      | [b4f88bb3c8](https://linux-hardware.org/?probe=b4f88bb3c8) | Mar 22, 2024 |
| Gigabyte      | B460 HD3 se2                | Desktop     | [ac86e944ff](https://linux-hardware.org/?probe=ac86e944ff) | Mar 22, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e582f6599b](https://linux-hardware.org/?probe=e582f6599b) | Mar 22, 2024 |
| Trigkey       | S5 V2.0                     | Mini pc     | [ebcb3a9b4e](https://linux-hardware.org/?probe=ebcb3a9b4e) | Mar 22, 2024 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [dabc36a5b3](https://linux-hardware.org/?probe=dabc36a5b3) | Mar 22, 2024 |
| MSI           | H81M-E34                    | Desktop     | [5ab741f203](https://linux-hardware.org/?probe=5ab741f203) | Mar 21, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [90a25e637e](https://linux-hardware.org/?probe=90a25e637e) | Mar 21, 2024 |
| HP            | 8433 11                     | Desktop     | [5b2290d410](https://linux-hardware.org/?probe=5b2290d410) | Mar 21, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [f7f667d127](https://linux-hardware.org/?probe=f7f667d127) | Mar 21, 2024 |
| Dell          | Latitude E7240              | Notebook    | [bac4c4e0b9](https://linux-hardware.org/?probe=bac4c4e0b9) | Mar 21, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0c5fd0d8b3](https://linux-hardware.org/?probe=0c5fd0d8b3) | Mar 21, 2024 |
| Proline       | V1165C4                     | Notebook    | [757853d7fb](https://linux-hardware.org/?probe=757853d7fb) | Mar 21, 2024 |
| ECS           | A785GM-AD3                  | Desktop     | [452fc5ac26](https://linux-hardware.org/?probe=452fc5ac26) | Mar 21, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [448c5c78c2](https://linux-hardware.org/?probe=448c5c78c2) | Mar 21, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [cd5d6341fb](https://linux-hardware.org/?probe=cd5d6341fb) | Mar 21, 2024 |
| Google        | Magma                       | Notebook    | [8fe3986816](https://linux-hardware.org/?probe=8fe3986816) | Mar 20, 2024 |
| ASUSTek       | B85M-C/C/SI                 | Desktop     | [b456ba2213](https://linux-hardware.org/?probe=b456ba2213) | Mar 20, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [17d208911e](https://linux-hardware.org/?probe=17d208911e) | Mar 20, 2024 |
| Schenker      | VISION (M23)                | Notebook    | [aeb80131e2](https://linux-hardware.org/?probe=aeb80131e2) | Mar 20, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | Desktop     | [ae0e79e6da](https://linux-hardware.org/?probe=ae0e79e6da) | Mar 20, 2024 |
| AMI           | Intel                       | Desktop     | [fc4348f291](https://linux-hardware.org/?probe=fc4348f291) | Mar 20, 2024 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [969fc32897](https://linux-hardware.org/?probe=969fc32897) | Mar 20, 2024 |
| Apple         | MacBook8,1                  | Notebook    | [fa8342132f](https://linux-hardware.org/?probe=fa8342132f) | Mar 20, 2024 |
| Apple         | MacBook8,1                  | Notebook    | [ac828c20cd](https://linux-hardware.org/?probe=ac828c20cd) | Mar 20, 2024 |
| Multilaser    | UB32X                       | Notebook    | [ef0be1fa36](https://linux-hardware.org/?probe=ef0be1fa36) | Mar 20, 2024 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [779eb3b38f](https://linux-hardware.org/?probe=779eb3b38f) | Mar 20, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [de361da6e2](https://linux-hardware.org/?probe=de361da6e2) | Mar 20, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03577ae940](https://linux-hardware.org/?probe=03577ae940) | Mar 19, 2024 |
| ASUSTek       | B85M-C/C/SI                 | Desktop     | [d374aaf228](https://linux-hardware.org/?probe=d374aaf228) | Mar 19, 2024 |
| Acer          | Veriton L6610G              | Desktop     | [c5e6b0ac2a](https://linux-hardware.org/?probe=c5e6b0ac2a) | Mar 19, 2024 |
| Dell          | 0NK5PH A00                  | Desktop     | [ee2fd9c92e](https://linux-hardware.org/?probe=ee2fd9c92e) | Mar 19, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [9ce06e146a](https://linux-hardware.org/?probe=9ce06e146a) | Mar 19, 2024 |
| HP            | Pavilion HDX9000            | Notebook    | [e8aa45f301](https://linux-hardware.org/?probe=e8aa45f301) | Mar 19, 2024 |
| HP            | Pavilion HDX9000            | Notebook    | [0c3e10d249](https://linux-hardware.org/?probe=0c3e10d249) | Mar 19, 2024 |
| Dell          | 0XFWHV A00                  | Desktop     | [366d65567e](https://linux-hardware.org/?probe=366d65567e) | Mar 19, 2024 |
| HP            | ZBook Studio G4             | Notebook    | [2f191d4ac2](https://linux-hardware.org/?probe=2f191d4ac2) | Mar 19, 2024 |
| Dell          | Latitude E7240              | Notebook    | [4b2cf432cb](https://linux-hardware.org/?probe=4b2cf432cb) | Mar 19, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d9e56f3325](https://linux-hardware.org/?probe=d9e56f3325) | Mar 19, 2024 |
| Acer          | Aspire E1-422               | Notebook    | [e6ff98fb07](https://linux-hardware.org/?probe=e6ff98fb07) | Mar 19, 2024 |
| HP            | 843B                        | Desktop     | [d867363097](https://linux-hardware.org/?probe=d867363097) | Mar 19, 2024 |
| HP            | 843B                        | Desktop     | [f32e4ee209](https://linux-hardware.org/?probe=f32e4ee209) | Mar 19, 2024 |
| Apple         | Mac-F2218EA9                | All in one  | [04aea2f042](https://linux-hardware.org/?probe=04aea2f042) | Mar 19, 2024 |
| Toshiba       | Satellite C70D-A            | Notebook    | [11c353f181](https://linux-hardware.org/?probe=11c353f181) | Mar 18, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | Notebook    | [93f757d8b3](https://linux-hardware.org/?probe=93f757d8b3) | Mar 18, 2024 |
| Dell          | System XPS L502X            | Notebook    | [64b806b993](https://linux-hardware.org/?probe=64b806b993) | Mar 18, 2024 |
| Dell          | 0T656F A01                  | Desktop     | [325c5efb6e](https://linux-hardware.org/?probe=325c5efb6e) | Mar 18, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [6477033da6](https://linux-hardware.org/?probe=6477033da6) | Mar 18, 2024 |
| eMachines     | MCP61PM-GM                  | Desktop     | [c92849e391](https://linux-hardware.org/?probe=c92849e391) | Mar 18, 2024 |
| Lenovo        | ThinkPad T480s 20L8S15P0... | Notebook    | [f15cb961e4](https://linux-hardware.org/?probe=f15cb961e4) | Mar 18, 2024 |
| TUXEDO        | Aura 15 Gen3                | Notebook    | [a984970bae](https://linux-hardware.org/?probe=a984970bae) | Mar 18, 2024 |
| Unknown       | Unknown                     | Notebook    | [30e63ff201](https://linux-hardware.org/?probe=30e63ff201) | Mar 18, 2024 |
| Unknown       | Unknown                     | Notebook    | [966cd696a4](https://linux-hardware.org/?probe=966cd696a4) | Mar 18, 2024 |
| ASRock        | X570 Steel Legend           | Desktop     | [902b7d5554](https://linux-hardware.org/?probe=902b7d5554) | Mar 18, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [4774169c78](https://linux-hardware.org/?probe=4774169c78) | Mar 18, 2024 |
| Apple         | MacBookAir3,2               | Notebook    | [1e9279f941](https://linux-hardware.org/?probe=1e9279f941) | Mar 18, 2024 |
| ASUSTek       | K42F                        | Notebook    | [f36df8e399](https://linux-hardware.org/?probe=f36df8e399) | Mar 18, 2024 |
| mPTech        | ARC 11.6 64GB HD            | Notebook    | [da2be1e542](https://linux-hardware.org/?probe=da2be1e542) | Mar 17, 2024 |
| HP            | 2ADC                        | Desktop     | [8c1fc992f0](https://linux-hardware.org/?probe=8c1fc992f0) | Mar 17, 2024 |
| Chuwi         | Hi10 X                      | Tablet      | [e746a7b752](https://linux-hardware.org/?probe=e746a7b752) | Mar 17, 2024 |
| Pegatron      | IPMH61P1                    | Desktop     | [6221b2b986](https://linux-hardware.org/?probe=6221b2b986) | Mar 17, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5026966312](https://linux-hardware.org/?probe=5026966312) | Mar 17, 2024 |
| HP            | Bloog                       | Notebook    | [4f0506526f](https://linux-hardware.org/?probe=4f0506526f) | Mar 17, 2024 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [2780dec79d](https://linux-hardware.org/?probe=2780dec79d) | Mar 17, 2024 |
| Unknown       | V00                         | Mini pc     | [8a4da59027](https://linux-hardware.org/?probe=8a4da59027) | Mar 17, 2024 |
| Unknown       | V00                         | Mini pc     | [05edb023bb](https://linux-hardware.org/?probe=05edb023bb) | Mar 17, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [1de394a543](https://linux-hardware.org/?probe=1de394a543) | Mar 17, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4428cc7de0](https://linux-hardware.org/?probe=4428cc7de0) | Mar 17, 2024 |
| Gateway       | SX2851                      | Desktop     | [68e1f2c952](https://linux-hardware.org/?probe=68e1f2c952) | Mar 17, 2024 |
| Dell          | Inspiron 3443               | Notebook    | [6f40825570](https://linux-hardware.org/?probe=6f40825570) | Mar 17, 2024 |
| Toshiba       | IS 1414                     | Notebook    | [2a7e7dd16f](https://linux-hardware.org/?probe=2a7e7dd16f) | Mar 17, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [c1dbd5edb2](https://linux-hardware.org/?probe=c1dbd5edb2) | Mar 17, 2024 |
| Acer          | Nitro AN515-42              | Notebook    | [76fa1af5db](https://linux-hardware.org/?probe=76fa1af5db) | Mar 17, 2024 |
| HP            | Pavilion dv6000 (GF677EA... | Notebook    | [ecbe5ffb1f](https://linux-hardware.org/?probe=ecbe5ffb1f) | Mar 16, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [f1bb876476](https://linux-hardware.org/?probe=f1bb876476) | Mar 16, 2024 |
| MSI           | B150 GAMING M3              | Desktop     | [f8b1e50645](https://linux-hardware.org/?probe=f8b1e50645) | Mar 16, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [dfd4dd1ea4](https://linux-hardware.org/?probe=dfd4dd1ea4) | Mar 16, 2024 |
| ASUSTek       | U6Sg                        | Notebook    | [6780a94d1c](https://linux-hardware.org/?probe=6780a94d1c) | Mar 16, 2024 |
| Unknown       | Unknown                     | Notebook    | [7c385c1bef](https://linux-hardware.org/?probe=7c385c1bef) | Mar 16, 2024 |
| Medion        | E4251                       | Notebook    | [e85db20237](https://linux-hardware.org/?probe=e85db20237) | Mar 16, 2024 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [910347d978](https://linux-hardware.org/?probe=910347d978) | Mar 16, 2024 |
| Dell          | Latitude E6440              | Notebook    | [671e5faa4f](https://linux-hardware.org/?probe=671e5faa4f) | Mar 16, 2024 |
| Dell          | Latitude 7290               | Notebook    | [0f5ec462bd](https://linux-hardware.org/?probe=0f5ec462bd) | Mar 15, 2024 |
| Dell          | Latitude 7290               | Notebook    | [a06e62383a](https://linux-hardware.org/?probe=a06e62383a) | Mar 15, 2024 |
| Dell          | 0M9KCM A02                  | Desktop     | [7823cafa72](https://linux-hardware.org/?probe=7823cafa72) | Mar 15, 2024 |
| HP            | 805D                        | Desktop     | [7878b71cab](https://linux-hardware.org/?probe=7878b71cab) | Mar 15, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [1b4cf177e5](https://linux-hardware.org/?probe=1b4cf177e5) | Mar 15, 2024 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [8e592e6500](https://linux-hardware.org/?probe=8e592e6500) | Mar 15, 2024 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [7a11b99920](https://linux-hardware.org/?probe=7a11b99920) | Mar 15, 2024 |
| Lenovo        | ThinkPad T410 2537PW4       | Notebook    | [29306b301d](https://linux-hardware.org/?probe=29306b301d) | Mar 15, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [294785aaef](https://linux-hardware.org/?probe=294785aaef) | Mar 15, 2024 |
| HP            | Pavilion g6                 | Notebook    | [992ebee68f](https://linux-hardware.org/?probe=992ebee68f) | Mar 15, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [044882319b](https://linux-hardware.org/?probe=044882319b) | Mar 15, 2024 |
| Dell          | 0M9KCM A02                  | Desktop     | [6dd5b76d21](https://linux-hardware.org/?probe=6dd5b76d21) | Mar 15, 2024 |
| Samsung       | 940XFG                      | Notebook    | [b60ac199c7](https://linux-hardware.org/?probe=b60ac199c7) | Mar 15, 2024 |
| Samsung       | 940XFG                      | Notebook    | [2698d3e097](https://linux-hardware.org/?probe=2698d3e097) | Mar 15, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [e8882adc5a](https://linux-hardware.org/?probe=e8882adc5a) | Mar 14, 2024 |
| Lenovo        | 1057 SDK0T76528 WIN 3556... | Desktop     | [ff14bf45ec](https://linux-hardware.org/?probe=ff14bf45ec) | Mar 14, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [f9ea26fca5](https://linux-hardware.org/?probe=f9ea26fca5) | Mar 14, 2024 |
| Apple         | MacBook9,1                  | Notebook    | [b8bbc1b9c0](https://linux-hardware.org/?probe=b8bbc1b9c0) | Mar 14, 2024 |
| Schenker      | VISION (M23)                | Notebook    | [63d77f6e25](https://linux-hardware.org/?probe=63d77f6e25) | Mar 14, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [65b7eba2bc](https://linux-hardware.org/?probe=65b7eba2bc) | Mar 14, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b175004524](https://linux-hardware.org/?probe=b175004524) | Mar 14, 2024 |
| Dell          | Inspiron N4030              | Notebook    | [294acdea48](https://linux-hardware.org/?probe=294acdea48) | Mar 14, 2024 |
| Dell          | Inspiron N4030              | Notebook    | [d5de19c3e5](https://linux-hardware.org/?probe=d5de19c3e5) | Mar 14, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [22fa6eee3e](https://linux-hardware.org/?probe=22fa6eee3e) | Mar 14, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [9fb06fb797](https://linux-hardware.org/?probe=9fb06fb797) | Mar 13, 2024 |
| Apple         | MacBook5,2                  | Notebook    | [e482eea403](https://linux-hardware.org/?probe=e482eea403) | Mar 13, 2024 |
| Apple         | MacBook5,2                  | Notebook    | [7e0aa86d1c](https://linux-hardware.org/?probe=7e0aa86d1c) | Mar 13, 2024 |
| ASUSTek       | P8P67 EVO                   | Desktop     | [3ece14c501](https://linux-hardware.org/?probe=3ece14c501) | Mar 13, 2024 |
| Unknown       | Unknown                     | Notebook    | [385e38249f](https://linux-hardware.org/?probe=385e38249f) | Mar 13, 2024 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [4fe003a84f](https://linux-hardware.org/?probe=4fe003a84f) | Mar 13, 2024 |
| Acer          | Aspire 7740                 | Notebook    | [8d1809ffa7](https://linux-hardware.org/?probe=8d1809ffa7) | Mar 13, 2024 |
| IBM           | 8215MUC                     | Desktop     | [b6c69c2119](https://linux-hardware.org/?probe=b6c69c2119) | Mar 13, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [3a8d8640a9](https://linux-hardware.org/?probe=3a8d8640a9) | Mar 12, 2024 |
| Pegatron      | JESSE                       | Desktop     | [5602b9f4e2](https://linux-hardware.org/?probe=5602b9f4e2) | Mar 12, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [94831371a9](https://linux-hardware.org/?probe=94831371a9) | Mar 12, 2024 |
| Dell          | Precision 3551              | Notebook    | [ac0c79297b](https://linux-hardware.org/?probe=ac0c79297b) | Mar 12, 2024 |
| Chuwi         | UBook X                     | Tablet      | [bab0a4bcb7](https://linux-hardware.org/?probe=bab0a4bcb7) | Mar 12, 2024 |
| Chuwi         | UBook X                     | Tablet      | [5bc5d0dcde](https://linux-hardware.org/?probe=5bc5d0dcde) | Mar 12, 2024 |
| Gigabyte      | H410M S2H V3                | Desktop     | [0f5989dcbc](https://linux-hardware.org/?probe=0f5989dcbc) | Mar 12, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [020b8b531a](https://linux-hardware.org/?probe=020b8b531a) | Mar 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8940a52b83](https://linux-hardware.org/?probe=8940a52b83) | Mar 12, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [84502e8400](https://linux-hardware.org/?probe=84502e8400) | Mar 12, 2024 |
| DIEBOLD       | Canyon                      | Desktop     | [109f1d1d93](https://linux-hardware.org/?probe=109f1d1d93) | Mar 12, 2024 |
| DIEBOLD       | Canyon                      | Desktop     | [a92906b4f5](https://linux-hardware.org/?probe=a92906b4f5) | Mar 12, 2024 |
| Unknown       | Unknown                     | Notebook    | [abdc4ff96c](https://linux-hardware.org/?probe=abdc4ff96c) | Mar 12, 2024 |
| MSI           | 785GT-E63                   | Desktop     | [1533ab1a7c](https://linux-hardware.org/?probe=1533ab1a7c) | Mar 12, 2024 |
| HP            | Laptop 17-by3xxx            | Notebook    | [ee8e42ea8a](https://linux-hardware.org/?probe=ee8e42ea8a) | Mar 12, 2024 |
| Thomson       | N14C4SL64                   | Notebook    | [7a431d9150](https://linux-hardware.org/?probe=7a431d9150) | Mar 12, 2024 |
| HP            | Laptop 17-by3xxx            | Notebook    | [731cba5dc9](https://linux-hardware.org/?probe=731cba5dc9) | Mar 12, 2024 |
| HP            | 8653 A                      | Desktop     | [e90335d9c9](https://linux-hardware.org/?probe=e90335d9c9) | Mar 12, 2024 |
| Microsoft     | Surface Laptop              | Tablet      | [0461221742](https://linux-hardware.org/?probe=0461221742) | Mar 12, 2024 |
| SiS           | B550S Ver:1.16              | Desktop     | [97c4226745](https://linux-hardware.org/?probe=97c4226745) | Mar 12, 2024 |
| Dell          | 0D6H9T A01                  | Desktop     | [6a4e81ad5e](https://linux-hardware.org/?probe=6a4e81ad5e) | Mar 11, 2024 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [b78e24d0f3](https://linux-hardware.org/?probe=b78e24d0f3) | Mar 11, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [3e8cf17057](https://linux-hardware.org/?probe=3e8cf17057) | Mar 11, 2024 |
| ASUSTek       | T102HA                      | Tablet      | [073dcfbefd](https://linux-hardware.org/?probe=073dcfbefd) | Mar 11, 2024 |
| Microsoft     | Surface Go                  | Tablet      | [53fa2565fe](https://linux-hardware.org/?probe=53fa2565fe) | Mar 11, 2024 |
| HP            | ProBook 650 G2              | Notebook    | [532a823ad7](https://linux-hardware.org/?probe=532a823ad7) | Mar 11, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [deafbd3743](https://linux-hardware.org/?probe=deafbd3743) | Mar 11, 2024 |
| Dell          | Latitude E6520              | Notebook    | [2f62f1dde1](https://linux-hardware.org/?probe=2f62f1dde1) | Mar 11, 2024 |
| MSI           | MEG Z590 ACE GOLD EDITIO... | Desktop     | [df6500bf6b](https://linux-hardware.org/?probe=df6500bf6b) | Mar 10, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [53ca2b56ef](https://linux-hardware.org/?probe=53ca2b56ef) | Mar 10, 2024 |
| Microsoft     | Surface Go                  | Tablet      | [a5fefda0d9](https://linux-hardware.org/?probe=a5fefda0d9) | Mar 10, 2024 |
| HP            | 8265                        | Desktop     | [a805d1a4b0](https://linux-hardware.org/?probe=a805d1a4b0) | Mar 10, 2024 |
| HP            | ZBook 14u G6                | Notebook    | [ff55623014](https://linux-hardware.org/?probe=ff55623014) | Mar 10, 2024 |
| Avell High... | Avell G1513 MUV / A52 MU... | Notebook    | [e41f767d2a](https://linux-hardware.org/?probe=e41f767d2a) | Mar 10, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [6fb4193bc2](https://linux-hardware.org/?probe=6fb4193bc2) | Mar 10, 2024 |
| Sony          | VPCS131FM                   | Notebook    | [51b54e4b81](https://linux-hardware.org/?probe=51b54e4b81) | Mar 10, 2024 |
| MSI           | B450M-A PRO MAX II          | Desktop     | [e38d871b42](https://linux-hardware.org/?probe=e38d871b42) | Mar 10, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [59f5c0bcab](https://linux-hardware.org/?probe=59f5c0bcab) | Mar 10, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [eecc91d036](https://linux-hardware.org/?probe=eecc91d036) | Mar 10, 2024 |
| Toshiba       | Satellite L650              | Notebook    | [46a8d42eaa](https://linux-hardware.org/?probe=46a8d42eaa) | Mar 10, 2024 |
| Acer          | Swift SFX14-71G             | Notebook    | [fa8515090c](https://linux-hardware.org/?probe=fa8515090c) | Mar 10, 2024 |
| HP            | Elite x2 1012 G2            | Tablet      | [80e791b12b](https://linux-hardware.org/?probe=80e791b12b) | Mar 10, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [aebd0ccbc7](https://linux-hardware.org/?probe=aebd0ccbc7) | Mar 10, 2024 |
| Lenovo        | ThinkPad T560 20FJS1FB03    | Notebook    | [15c3a25881](https://linux-hardware.org/?probe=15c3a25881) | Mar 10, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [d9046242c5](https://linux-hardware.org/?probe=d9046242c5) | Mar 10, 2024 |
| QIYIDA        | ED4 V1.1                    | Desktop     | [0fcfff37bf](https://linux-hardware.org/?probe=0fcfff37bf) | Mar 10, 2024 |
| Unknown       | Unknown                     | Notebook    | [ad4e2e26c8](https://linux-hardware.org/?probe=ad4e2e26c8) | Mar 10, 2024 |
| Avell High... | Avell G1513 MUV / A52 MU... | Notebook    | [c82748fe8b](https://linux-hardware.org/?probe=c82748fe8b) | Mar 10, 2024 |
| Acer          | Aspire 9420                 | Notebook    | [ac85f8e229](https://linux-hardware.org/?probe=ac85f8e229) | Mar 09, 2024 |
| Dell          | 0KWVT8 A00                  | Desktop     | [c80fca1d72](https://linux-hardware.org/?probe=c80fca1d72) | Mar 09, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [b591cc5cfe](https://linux-hardware.org/?probe=b591cc5cfe) | Mar 09, 2024 |
| HP            | Elite x2 1012 G1            | Notebook    | [512c2aa7fe](https://linux-hardware.org/?probe=512c2aa7fe) | Mar 09, 2024 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [6b11295c31](https://linux-hardware.org/?probe=6b11295c31) | Mar 09, 2024 |
| Apple         | Mac-F2218FC8                | All in one  | [5ec193e257](https://linux-hardware.org/?probe=5ec193e257) | Mar 09, 2024 |
| Acer          | Aspire 9410                 | Notebook    | [3307f5eede](https://linux-hardware.org/?probe=3307f5eede) | Mar 09, 2024 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [4bd7a64be3](https://linux-hardware.org/?probe=4bd7a64be3) | Mar 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [2b737bd393](https://linux-hardware.org/?probe=2b737bd393) | Mar 09, 2024 |
| HP            | 1000                        | Notebook    | [12df954c4d](https://linux-hardware.org/?probe=12df954c4d) | Mar 09, 2024 |
| Foxconn       | 946 7MA Series              | Desktop     | [7453cdde18](https://linux-hardware.org/?probe=7453cdde18) | Mar 09, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | Notebook    | [bd5a3177a0](https://linux-hardware.org/?probe=bd5a3177a0) | Mar 09, 2024 |
| HP            | 3647h                       | Desktop     | [04d7f488a7](https://linux-hardware.org/?probe=04d7f488a7) | Mar 09, 2024 |
| Lenovo        | ThinkPad T440s 20ARS2QF0... | Notebook    | [fdebc30141](https://linux-hardware.org/?probe=fdebc30141) | Mar 08, 2024 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [f208bbae00](https://linux-hardware.org/?probe=f208bbae00) | Mar 08, 2024 |
| HP            | EliteBook 8540p             | Notebook    | [c9b945f402](https://linux-hardware.org/?probe=c9b945f402) | Mar 08, 2024 |
| Biostar       | G41-M7                      | Desktop     | [54836e3fbe](https://linux-hardware.org/?probe=54836e3fbe) | Mar 08, 2024 |
| Sony          | VGN-FW21E                   | Notebook    | [618cb0b126](https://linux-hardware.org/?probe=618cb0b126) | Mar 08, 2024 |
| Sony          | VGN-FW21E                   | Notebook    | [8770642321](https://linux-hardware.org/?probe=8770642321) | Mar 08, 2024 |
| HP            | 2133                        | Notebook    | [262c68f9a7](https://linux-hardware.org/?probe=262c68f9a7) | Mar 08, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [e64e10b115](https://linux-hardware.org/?probe=e64e10b115) | Mar 08, 2024 |
| Dell          | Precision M4800             | Notebook    | [a3fd644ff6](https://linux-hardware.org/?probe=a3fd644ff6) | Mar 08, 2024 |
| Dell          | Precision M4800             | Notebook    | [2a11f6f14e](https://linux-hardware.org/?probe=2a11f6f14e) | Mar 08, 2024 |
| Unknown       | Unknown                     | Notebook    | [e4a0023214](https://linux-hardware.org/?probe=e4a0023214) | Mar 08, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [cdf2cddb43](https://linux-hardware.org/?probe=cdf2cddb43) | Mar 08, 2024 |
| ASRock        | H81M-VG4                    | Desktop     | [96f9d92727](https://linux-hardware.org/?probe=96f9d92727) | Mar 08, 2024 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [d3e9bec32e](https://linux-hardware.org/?probe=d3e9bec32e) | Mar 08, 2024 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [b4f141c9da](https://linux-hardware.org/?probe=b4f141c9da) | Mar 08, 2024 |
| Apple         | MacBookPro10,2              | Notebook    | [14ec3be380](https://linux-hardware.org/?probe=14ec3be380) | Mar 08, 2024 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b18d2c6cab](https://linux-hardware.org/?probe=b18d2c6cab) | Mar 08, 2024 |
| Dell          | 0KWVT8 A03                  | Desktop     | [4ad718e45b](https://linux-hardware.org/?probe=4ad718e45b) | Mar 08, 2024 |
| Positivo B... | VJFE42F11X-B1151H           | Notebook    | [dc3d9edffb](https://linux-hardware.org/?probe=dc3d9edffb) | Mar 07, 2024 |
| MACHINIST     | X99-RS9 V1.11               | Notebook    | [52886e70b7](https://linux-hardware.org/?probe=52886e70b7) | Mar 07, 2024 |
| Gigabyte      | H410M S2H V3                | Desktop     | [f2ae26b3f5](https://linux-hardware.org/?probe=f2ae26b3f5) | Mar 07, 2024 |
| ASUSTek       | X205TAW                     | Notebook    | [6ed323ca5c](https://linux-hardware.org/?probe=6ed323ca5c) | Mar 07, 2024 |
| Acer          | TravelMate 8571             | Notebook    | [fc248fb6b6](https://linux-hardware.org/?probe=fc248fb6b6) | Mar 07, 2024 |
| ASUSTek       | X205TAW                     | Notebook    | [2dd874e62c](https://linux-hardware.org/?probe=2dd874e62c) | Mar 07, 2024 |
| ASUSTek       | K46CM                       | Notebook    | [cea6814d2b](https://linux-hardware.org/?probe=cea6814d2b) | Mar 07, 2024 |
| ASUSTek       | K46CM                       | Notebook    | [6ebd0b1dfc](https://linux-hardware.org/?probe=6ebd0b1dfc) | Mar 07, 2024 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [af2b0287ec](https://linux-hardware.org/?probe=af2b0287ec) | Mar 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e545b12914](https://linux-hardware.org/?probe=e545b12914) | Mar 07, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [6e793fa7a4](https://linux-hardware.org/?probe=6e793fa7a4) | Mar 07, 2024 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [65ea7ee4de](https://linux-hardware.org/?probe=65ea7ee4de) | Mar 07, 2024 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [6e35097ed2](https://linux-hardware.org/?probe=6e35097ed2) | Mar 07, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [0111e861f4](https://linux-hardware.org/?probe=0111e861f4) | Mar 07, 2024 |
| Apple         | Mac-F22C86C8                | Mini pc     | [523b960a7e](https://linux-hardware.org/?probe=523b960a7e) | Mar 06, 2024 |
| Samsung       | R530/R730                   | Notebook    | [4c11035f66](https://linux-hardware.org/?probe=4c11035f66) | Mar 06, 2024 |
| RuggedPC      | RuggedBookR15               | Notebook    | [1c2a04ab34](https://linux-hardware.org/?probe=1c2a04ab34) | Mar 06, 2024 |
| RuggedPC      | RuggedBookR15               | Notebook    | [bcdeba9b2d](https://linux-hardware.org/?probe=bcdeba9b2d) | Mar 06, 2024 |
| Acer          | Aspire M3-581G              | Notebook    | [7ab92d79ee](https://linux-hardware.org/?probe=7ab92d79ee) | Mar 06, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [06c5a79ab1](https://linux-hardware.org/?probe=06c5a79ab1) | Mar 06, 2024 |
| HP            | Laptop 17-cp3xxx            | Notebook    | [41c4383dd9](https://linux-hardware.org/?probe=41c4383dd9) | Mar 06, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [a9efafb13a](https://linux-hardware.org/?probe=a9efafb13a) | Mar 06, 2024 |
| TongFang      | GM7PX0N                     | Notebook    | [632d2a6962](https://linux-hardware.org/?probe=632d2a6962) | Mar 06, 2024 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [76cf4afca4](https://linux-hardware.org/?probe=76cf4afca4) | Mar 06, 2024 |
| Lenovo        | IdeaPad 5 Pro 16IAH7 82S... | Notebook    | [e2265261d3](https://linux-hardware.org/?probe=e2265261d3) | Mar 05, 2024 |
| HP            | 89B5 A                      | Desktop     | [52f3d1ebea](https://linux-hardware.org/?probe=52f3d1ebea) | Mar 05, 2024 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [5eb3213d99](https://linux-hardware.org/?probe=5eb3213d99) | Mar 05, 2024 |
| Fujitsu       | STYLISTIC Q665              | Tablet      | [9bc073f366](https://linux-hardware.org/?probe=9bc073f366) | Mar 05, 2024 |
| HP            | 89B5 A                      | Desktop     | [ada6553f38](https://linux-hardware.org/?probe=ada6553f38) | Mar 05, 2024 |
| Trigkey       | S5 V2.0                     | Mini pc     | [4a6153bfa4](https://linux-hardware.org/?probe=4a6153bfa4) | Mar 05, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [0997073605](https://linux-hardware.org/?probe=0997073605) | Mar 05, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [3c963fd772](https://linux-hardware.org/?probe=3c963fd772) | Mar 05, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [69e2309ef8](https://linux-hardware.org/?probe=69e2309ef8) | Mar 05, 2024 |
| TongFang      | GM7PX0N                     | Notebook    | [4282677961](https://linux-hardware.org/?probe=4282677961) | Mar 05, 2024 |
| Acer          | Extensa 5635ZG              | Notebook    | [736943715c](https://linux-hardware.org/?probe=736943715c) | Mar 04, 2024 |
| Acer          | Extensa 5635ZG              | Notebook    | [e32263435e](https://linux-hardware.org/?probe=e32263435e) | Mar 04, 2024 |
| Dell          | 0T10XW A00                  | Desktop     | [ef08d738fb](https://linux-hardware.org/?probe=ef08d738fb) | Mar 04, 2024 |
| HP            | ENVY m7                     | Notebook    | [deb9b0324a](https://linux-hardware.org/?probe=deb9b0324a) | Mar 04, 2024 |
| MSI           | GF63 Thin 11SC              | Notebook    | [488a665e56](https://linux-hardware.org/?probe=488a665e56) | Mar 04, 2024 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [50206aadaf](https://linux-hardware.org/?probe=50206aadaf) | Mar 04, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b3142de854](https://linux-hardware.org/?probe=b3142de854) | Mar 04, 2024 |
| Dell          | Latitude E6420              | Notebook    | [e2242d6194](https://linux-hardware.org/?probe=e2242d6194) | Mar 04, 2024 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [0560489c7e](https://linux-hardware.org/?probe=0560489c7e) | Mar 04, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [e672a38e47](https://linux-hardware.org/?probe=e672a38e47) | Mar 04, 2024 |
| Dell          | Vostro 3550                 | Notebook    | [15e459747d](https://linux-hardware.org/?probe=15e459747d) | Mar 04, 2024 |
| Acer          | Aspire 5310                 | Notebook    | [5a8aa1f2f8](https://linux-hardware.org/?probe=5a8aa1f2f8) | Mar 03, 2024 |
| Dell          | 0PU052                      | Desktop     | [d99b3dfb94](https://linux-hardware.org/?probe=d99b3dfb94) | Mar 03, 2024 |
| HP            | ProBook 6470b               | Notebook    | [db15714a99](https://linux-hardware.org/?probe=db15714a99) | Mar 03, 2024 |
| Acer          | Aspire A717-72G             | Notebook    | [2d278d552b](https://linux-hardware.org/?probe=2d278d552b) | Mar 03, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [d1cbfd27bc](https://linux-hardware.org/?probe=d1cbfd27bc) | Mar 03, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | Desktop     | [813c36f5cf](https://linux-hardware.org/?probe=813c36f5cf) | Mar 03, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [69bec2f38f](https://linux-hardware.org/?probe=69bec2f38f) | Mar 03, 2024 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [3818d7195f](https://linux-hardware.org/?probe=3818d7195f) | Mar 03, 2024 |
| Gigabyte      | A520M DS3H V2               | Desktop     | [2046b817c7](https://linux-hardware.org/?probe=2046b817c7) | Mar 03, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [77b9aa66fd](https://linux-hardware.org/?probe=77b9aa66fd) | Mar 03, 2024 |
| MSI           | B450M GAMING PLUS           | Desktop     | [8eaf2b59af](https://linux-hardware.org/?probe=8eaf2b59af) | Mar 03, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [f9efc24735](https://linux-hardware.org/?probe=f9efc24735) | Mar 03, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c31a0171ed](https://linux-hardware.org/?probe=c31a0171ed) | Mar 02, 2024 |
| ASUSTek       | X555LF                      | Notebook    | [82af3e46f1](https://linux-hardware.org/?probe=82af3e46f1) | Mar 02, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c6dbf5f3c5](https://linux-hardware.org/?probe=c6dbf5f3c5) | Mar 02, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [20e198611e](https://linux-hardware.org/?probe=20e198611e) | Mar 02, 2024 |
| ECS           | H61H2-M2                    | Desktop     | [bec82f9c2a](https://linux-hardware.org/?probe=bec82f9c2a) | Mar 02, 2024 |
| Gigabyte      | G31M-S2C                    | Desktop     | [b9ddd2512e](https://linux-hardware.org/?probe=b9ddd2512e) | Mar 02, 2024 |
| Gigabyte      | G31M-S2C                    | Desktop     | [c9ab34da1a](https://linux-hardware.org/?probe=c9ab34da1a) | Mar 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [271452e819](https://linux-hardware.org/?probe=271452e819) | Mar 01, 2024 |
| Lenovo        | G50-80 80E5                 | Notebook    | [eadb1ffe64](https://linux-hardware.org/?probe=eadb1ffe64) | Mar 01, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [beb30d1c82](https://linux-hardware.org/?probe=beb30d1c82) | Mar 01, 2024 |
| HP            | EliteBook 2530p             | Notebook    | [d4fdd36102](https://linux-hardware.org/?probe=d4fdd36102) | Mar 01, 2024 |
| ASUSTek       | E201NA                      | Notebook    | [39326f3b72](https://linux-hardware.org/?probe=39326f3b72) | Mar 01, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [6573368c36](https://linux-hardware.org/?probe=6573368c36) | Mar 01, 2024 |
| Gigabyte      | G31M-S2C                    | Desktop     | [47d6164c5a](https://linux-hardware.org/?probe=47d6164c5a) | Feb 29, 2024 |
| Medion        | E4251                       | Notebook    | [99fbdc8707](https://linux-hardware.org/?probe=99fbdc8707) | Feb 29, 2024 |
| ASUSTek       | P8H61-M PLUS2               | Desktop     | [9539fc46cc](https://linux-hardware.org/?probe=9539fc46cc) | Feb 29, 2024 |
| HP            | EliteBook 8540p             | Notebook    | [b0205f013a](https://linux-hardware.org/?probe=b0205f013a) | Feb 29, 2024 |
| ECS           | H61H2-M2                    | Desktop     | [d8ff6883f1](https://linux-hardware.org/?probe=d8ff6883f1) | Feb 29, 2024 |
| Supermicro    | C2SBC-Q                     | Desktop     | [d90714db33](https://linux-hardware.org/?probe=d90714db33) | Feb 29, 2024 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [08482c8ae5](https://linux-hardware.org/?probe=08482c8ae5) | Feb 29, 2024 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [f7550261f5](https://linux-hardware.org/?probe=f7550261f5) | Feb 29, 2024 |
| Dell          | Vostro 3360                 | Notebook    | [f981644866](https://linux-hardware.org/?probe=f981644866) | Feb 29, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [aae4ff4009](https://linux-hardware.org/?probe=aae4ff4009) | Feb 29, 2024 |
| Samsung       | 300E5M/300E5L               | Notebook    | [2ba6cdb37b](https://linux-hardware.org/?probe=2ba6cdb37b) | Feb 28, 2024 |
| Dell          | Vostro 1500                 | Notebook    | [a1e50e7852](https://linux-hardware.org/?probe=a1e50e7852) | Feb 28, 2024 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [a9c902341e](https://linux-hardware.org/?probe=a9c902341e) | Feb 28, 2024 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [445ff9dc64](https://linux-hardware.org/?probe=445ff9dc64) | Feb 28, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [6e35a5e2b0](https://linux-hardware.org/?probe=6e35a5e2b0) | Feb 28, 2024 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [636e341039](https://linux-hardware.org/?probe=636e341039) | Feb 28, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [99161beb5e](https://linux-hardware.org/?probe=99161beb5e) | Feb 28, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [84b3a163a6](https://linux-hardware.org/?probe=84b3a163a6) | Feb 28, 2024 |
| HP            | Pavilion Sleekbook 14       | Notebook    | [9727db31ca](https://linux-hardware.org/?probe=9727db31ca) | Feb 28, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [f4f2d5a42e](https://linux-hardware.org/?probe=f4f2d5a42e) | Feb 28, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [a8565459dd](https://linux-hardware.org/?probe=a8565459dd) | Feb 28, 2024 |
| Apple         | MacBookAir7,1               | Notebook    | [1c13d9c5b2](https://linux-hardware.org/?probe=1c13d9c5b2) | Feb 28, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a2af4f4a4d](https://linux-hardware.org/?probe=a2af4f4a4d) | Feb 28, 2024 |
| HP            | 83EE                        | Desktop     | [86edbf63e7](https://linux-hardware.org/?probe=86edbf63e7) | Feb 28, 2024 |
| HP            | 14                          | Notebook    | [abadaf3341](https://linux-hardware.org/?probe=abadaf3341) | Feb 27, 2024 |
| Dell          | Latitude E7470              | Notebook    | [d4890f7ed2](https://linux-hardware.org/?probe=d4890f7ed2) | Feb 27, 2024 |
| ASRock        | H81M-VG4                    | Desktop     | [031f559cf7](https://linux-hardware.org/?probe=031f559cf7) | Feb 27, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e199b6b976](https://linux-hardware.org/?probe=e199b6b976) | Feb 27, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e280f2bae0](https://linux-hardware.org/?probe=e280f2bae0) | Feb 27, 2024 |
| HP            | Pavilion 17                 | Notebook    | [9bc5ed54e4](https://linux-hardware.org/?probe=9bc5ed54e4) | Feb 27, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [d2373db1a8](https://linux-hardware.org/?probe=d2373db1a8) | Feb 27, 2024 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [a3e7bc047a](https://linux-hardware.org/?probe=a3e7bc047a) | Feb 27, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [36c04de2ce](https://linux-hardware.org/?probe=36c04de2ce) | Feb 27, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [196330861b](https://linux-hardware.org/?probe=196330861b) | Feb 27, 2024 |
| ASUSTek       | M50Vn                       | Notebook    | [65d6f947b1](https://linux-hardware.org/?probe=65d6f947b1) | Feb 26, 2024 |
| EVOO          | EV-C-125-3                  | Notebook    | [d452f3776a](https://linux-hardware.org/?probe=d452f3776a) | Feb 26, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [79b3e2b85f](https://linux-hardware.org/?probe=79b3e2b85f) | Feb 26, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [0812dc5f8e](https://linux-hardware.org/?probe=0812dc5f8e) | Feb 26, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | Desktop     | [7fe90d068b](https://linux-hardware.org/?probe=7fe90d068b) | Feb 26, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | Desktop     | [5b006b8b96](https://linux-hardware.org/?probe=5b006b8b96) | Feb 26, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [b4571bfd3b](https://linux-hardware.org/?probe=b4571bfd3b) | Feb 26, 2024 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | Notebook    | [821a30868b](https://linux-hardware.org/?probe=821a30868b) | Feb 26, 2024 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | Notebook    | [887c849b98](https://linux-hardware.org/?probe=887c849b98) | Feb 26, 2024 |
| Microsoft     | Surface Pro 2               | Tablet      | [b0a1af08b2](https://linux-hardware.org/?probe=b0a1af08b2) | Feb 26, 2024 |
| Microsoft     | Surface Pro 2               | Tablet      | [df2c0b8c2f](https://linux-hardware.org/?probe=df2c0b8c2f) | Feb 26, 2024 |
| Toshiba       | Satellite P55t-C            | Notebook    | [03e849c6a1](https://linux-hardware.org/?probe=03e849c6a1) | Feb 26, 2024 |
| Toshiba       | Satellite Pro C50-A-1EM     | Notebook    | [a0d0bf0a80](https://linux-hardware.org/?probe=a0d0bf0a80) | Feb 25, 2024 |
| Lenovo        | ThinkCentre M71z 1761E4U    | Desktop     | [07258c1d6d](https://linux-hardware.org/?probe=07258c1d6d) | Feb 25, 2024 |
| Colorful T... | C.Z77 X5 V20                | Desktop     | [c4b1274d4e](https://linux-hardware.org/?probe=c4b1274d4e) | Feb 25, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [d8df626171](https://linux-hardware.org/?probe=d8df626171) | Feb 25, 2024 |
| HP            | ENVY Notebook               | Notebook    | [d3e8ab6282](https://linux-hardware.org/?probe=d3e8ab6282) | Feb 24, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | Notebook    | [f44261baba](https://linux-hardware.org/?probe=f44261baba) | Feb 24, 2024 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [9498f74025](https://linux-hardware.org/?probe=9498f74025) | Feb 24, 2024 |
| Unknown       | E-H61                       | Desktop     | [899be10105](https://linux-hardware.org/?probe=899be10105) | Feb 24, 2024 |
| Unknown       | E-H61                       | Desktop     | [fa84a51212](https://linux-hardware.org/?probe=fa84a51212) | Feb 24, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [16a770e1ca](https://linux-hardware.org/?probe=16a770e1ca) | Feb 24, 2024 |
| Lenovo        | ThinkPad W520 42844ZG       | Notebook    | [6731541710](https://linux-hardware.org/?probe=6731541710) | Feb 24, 2024 |
| Toshiba       | Satellite Pro C50-A-1EM     | Notebook    | [c398b93c14](https://linux-hardware.org/?probe=c398b93c14) | Feb 24, 2024 |
| Positivo      | Mobile                      | Notebook    | [2fb0a42611](https://linux-hardware.org/?probe=2fb0a42611) | Feb 24, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [6c3c6d683b](https://linux-hardware.org/?probe=6c3c6d683b) | Feb 24, 2024 |
| MSI           | MS-6657                     | All in one  | [5ee9e014c8](https://linux-hardware.org/?probe=5ee9e014c8) | Feb 24, 2024 |
| Google        | Blorb                       | Notebook    | [047010ad8c](https://linux-hardware.org/?probe=047010ad8c) | Feb 23, 2024 |
| HP            | Pavilion 17                 | Notebook    | [274b953249](https://linux-hardware.org/?probe=274b953249) | Feb 23, 2024 |
| Intel         | X58                         | Desktop     | [f4526c5a1c](https://linux-hardware.org/?probe=f4526c5a1c) | Feb 23, 2024 |
| HP            | 240 14 inch G9              | Notebook    | [54ea49a49a](https://linux-hardware.org/?probe=54ea49a49a) | Feb 23, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [a20a26ce84](https://linux-hardware.org/?probe=a20a26ce84) | Feb 23, 2024 |
| Lenovo        | ThinkPad Edge 03285EG       | Notebook    | [aa07998977](https://linux-hardware.org/?probe=aa07998977) | Feb 23, 2024 |
| Lenovo        | ThinkPad X230 2325ZF9       | Notebook    | [f88c20db11](https://linux-hardware.org/?probe=f88c20db11) | Feb 23, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [eeace60b7a](https://linux-hardware.org/?probe=eeace60b7a) | Feb 23, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [f0b2b76ba7](https://linux-hardware.org/?probe=f0b2b76ba7) | Feb 23, 2024 |
| Lenovo        | G50-45 80MQ                 | Notebook    | [f45c20f5eb](https://linux-hardware.org/?probe=f45c20f5eb) | Feb 23, 2024 |
| Biostar       | A320MH                      | Desktop     | [cbd7260993](https://linux-hardware.org/?probe=cbd7260993) | Feb 23, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [e4d83b2314](https://linux-hardware.org/?probe=e4d83b2314) | Feb 22, 2024 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [86b047a480](https://linux-hardware.org/?probe=86b047a480) | Feb 22, 2024 |
| Packard Be... | EasyNote TM85               | Notebook    | [6ba78b34a3](https://linux-hardware.org/?probe=6ba78b34a3) | Feb 22, 2024 |
| Apple         | Mac-F2238AC8                | All in one  | [ae8361dd86](https://linux-hardware.org/?probe=ae8361dd86) | Feb 22, 2024 |
| Apple         | Mac-F2238AC8                | All in one  | [b6cb121342](https://linux-hardware.org/?probe=b6cb121342) | Feb 22, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [65fb12c93f](https://linux-hardware.org/?probe=65fb12c93f) | Feb 22, 2024 |
| Sony          | VPCEH2N1E                   | Notebook    | [d5772fa494](https://linux-hardware.org/?probe=d5772fa494) | Feb 22, 2024 |
| Sony          | VPCEH2N1E                   | Notebook    | [608b477d0d](https://linux-hardware.org/?probe=608b477d0d) | Feb 22, 2024 |
| HP            | ProBook 4730s               | Notebook    | [84e5bf925d](https://linux-hardware.org/?probe=84e5bf925d) | Feb 22, 2024 |
| Notebook      | NS5x_NS7xAU                 | Notebook    | [bed908e80b](https://linux-hardware.org/?probe=bed908e80b) | Feb 21, 2024 |
| Fujitsu       | LIFEBOOK E449               | Notebook    | [fa2e018267](https://linux-hardware.org/?probe=fa2e018267) | Feb 21, 2024 |
| ASUSTek       | X501U                       | Notebook    | [1ebbe09ae2](https://linux-hardware.org/?probe=1ebbe09ae2) | Feb 21, 2024 |
| HP            | 2215                        | Desktop     | [eef0673d86](https://linux-hardware.org/?probe=eef0673d86) | Feb 21, 2024 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d7f17aa5fd](https://linux-hardware.org/?probe=d7f17aa5fd) | Feb 21, 2024 |
| Toshiba       | Satellite P55t-B            | Notebook    | [a5bb579413](https://linux-hardware.org/?probe=a5bb579413) | Feb 21, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [4d913de0c0](https://linux-hardware.org/?probe=4d913de0c0) | Feb 21, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bddbc049f7](https://linux-hardware.org/?probe=bddbc049f7) | Feb 21, 2024 |
| HP            | 2215                        | Desktop     | [d23162f59f](https://linux-hardware.org/?probe=d23162f59f) | Feb 20, 2024 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [cef24e671a](https://linux-hardware.org/?probe=cef24e671a) | Feb 20, 2024 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [a39f9b2921](https://linux-hardware.org/?probe=a39f9b2921) | Feb 20, 2024 |
| Acer          | Aspire 9420                 | Notebook    | [b45701bea6](https://linux-hardware.org/?probe=b45701bea6) | Feb 20, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [1ccd345da2](https://linux-hardware.org/?probe=1ccd345da2) | Feb 20, 2024 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [cd69063157](https://linux-hardware.org/?probe=cd69063157) | Feb 20, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [6505abea2b](https://linux-hardware.org/?probe=6505abea2b) | Feb 20, 2024 |
| GEEKOM        | A5                          | Desktop     | [43d1283121](https://linux-hardware.org/?probe=43d1283121) | Feb 20, 2024 |
| ASRock        | H410M-HVS                   | Desktop     | [d07941ad3f](https://linux-hardware.org/?probe=d07941ad3f) | Feb 20, 2024 |
| Gigabyte      | EP35-DS3                    | Desktop     | [083ed26b97](https://linux-hardware.org/?probe=083ed26b97) | Feb 20, 2024 |
| Lenovo        | ThinkPad X230 2325CY4       | Notebook    | [6491a02f07](https://linux-hardware.org/?probe=6491a02f07) | Feb 20, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [9d5c5dfeb7](https://linux-hardware.org/?probe=9d5c5dfeb7) | Feb 20, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [581dd97a4d](https://linux-hardware.org/?probe=581dd97a4d) | Feb 20, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [44c6111452](https://linux-hardware.org/?probe=44c6111452) | Feb 19, 2024 |
| HP            | Unknown                     | Notebook    | [9273430bbb](https://linux-hardware.org/?probe=9273430bbb) | Feb 19, 2024 |
| Dell          | 051FJ8 A01                  | Desktop     | [0949817cb6](https://linux-hardware.org/?probe=0949817cb6) | Feb 19, 2024 |
| ASUSTek       | B85M-E                      | Desktop     | [d1bbdc0a03](https://linux-hardware.org/?probe=d1bbdc0a03) | Feb 19, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [61c8cf8cc6](https://linux-hardware.org/?probe=61c8cf8cc6) | Feb 19, 2024 |
| ALLDOCUBE     | KnoteGo                     | Tablet      | [ce5ed12e45](https://linux-hardware.org/?probe=ce5ed12e45) | Feb 19, 2024 |
| Lenovo        | ThinkPad T430s 2356LPG      | Notebook    | [7179df29bf](https://linux-hardware.org/?probe=7179df29bf) | Feb 19, 2024 |
| Dell          | 0PGKWF A00                  | Desktop     | [83c1da9c3c](https://linux-hardware.org/?probe=83c1da9c3c) | Feb 19, 2024 |
| AZW           | Gemini T45                  | Desktop     | [9a81383d10](https://linux-hardware.org/?probe=9a81383d10) | Feb 19, 2024 |
| Acer          | Aspire 5532                 | Notebook    | [8c95bb0b06](https://linux-hardware.org/?probe=8c95bb0b06) | Feb 19, 2024 |
| TB            | WTR R1                      | Desktop     | [ab65edc6c3](https://linux-hardware.org/?probe=ab65edc6c3) | Feb 19, 2024 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [55af4d803a](https://linux-hardware.org/?probe=55af4d803a) | Feb 19, 2024 |
| Dell          | Inspiron 3583               | Notebook    | [ff9b94f97c](https://linux-hardware.org/?probe=ff9b94f97c) | Feb 19, 2024 |
| ASUSTek       | B85-PLUS                    | Desktop     | [87ad4ddd6d](https://linux-hardware.org/?probe=87ad4ddd6d) | Feb 19, 2024 |
| Dell          | 0KWVT8 A03                  | Desktop     | [96c3415965](https://linux-hardware.org/?probe=96c3415965) | Feb 19, 2024 |
| Dell          | 0KWVT8 A03                  | Desktop     | [8a1cafd28d](https://linux-hardware.org/?probe=8a1cafd28d) | Feb 19, 2024 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [4edf29a65c](https://linux-hardware.org/?probe=4edf29a65c) | Feb 18, 2024 |
| Acer          | Aspire A517-53              | Notebook    | [7b128fdd48](https://linux-hardware.org/?probe=7b128fdd48) | Feb 18, 2024 |
| OEM           | B75 Ver:1.41                | Desktop     | [bdc300e725](https://linux-hardware.org/?probe=bdc300e725) | Feb 18, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f44ba8ac73](https://linux-hardware.org/?probe=f44ba8ac73) | Feb 18, 2024 |
| Toshiba       | Satellite C855-1W0          | Notebook    | [ea0ae771ec](https://linux-hardware.org/?probe=ea0ae771ec) | Feb 18, 2024 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [13adc3e2df](https://linux-hardware.org/?probe=13adc3e2df) | Feb 18, 2024 |
| Acer          | Swift SF314-54              | Notebook    | [a08666a01c](https://linux-hardware.org/?probe=a08666a01c) | Feb 18, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [74496a33f8](https://linux-hardware.org/?probe=74496a33f8) | Feb 18, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [0f64335601](https://linux-hardware.org/?probe=0f64335601) | Feb 18, 2024 |
| Dell          | Latitude E6410              | Notebook    | [89830fc67e](https://linux-hardware.org/?probe=89830fc67e) | Feb 18, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [f934645327](https://linux-hardware.org/?probe=f934645327) | Feb 17, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [eff6e16943](https://linux-hardware.org/?probe=eff6e16943) | Feb 17, 2024 |
| Dell          | Latitude E6410              | Notebook    | [a074f7ca62](https://linux-hardware.org/?probe=a074f7ca62) | Feb 17, 2024 |
| Lenovo        | Yoga 500-14IBD 80N4         | Notebook    | [c3bcfe1eee](https://linux-hardware.org/?probe=c3bcfe1eee) | Feb 17, 2024 |
| OEM           | B75 Ver:1.41                | Desktop     | [f685a6eccc](https://linux-hardware.org/?probe=f685a6eccc) | Feb 17, 2024 |
| Gigabyte      | M720-US3                    | Desktop     | [79c1cffeae](https://linux-hardware.org/?probe=79c1cffeae) | Feb 17, 2024 |
| Dell          | System XPS L502X            | Notebook    | [b5a8cb21e7](https://linux-hardware.org/?probe=b5a8cb21e7) | Feb 17, 2024 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [658984c494](https://linux-hardware.org/?probe=658984c494) | Feb 17, 2024 |
| Samsung       | 930XDB/931XDB/930XDY        | Notebook    | [223a69e99f](https://linux-hardware.org/?probe=223a69e99f) | Feb 17, 2024 |
| Gigabyte      | M720-US3                    | Desktop     | [340b590f33](https://linux-hardware.org/?probe=340b590f33) | Feb 17, 2024 |
| Dell          | Inspiron 5491 2n1           | Convertible | [26702c186d](https://linux-hardware.org/?probe=26702c186d) | Feb 17, 2024 |
| Dell          | Inspiron 5491 2n1           | Convertible | [c538693744](https://linux-hardware.org/?probe=c538693744) | Feb 17, 2024 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [4113f4c4a8](https://linux-hardware.org/?probe=4113f4c4a8) | Feb 17, 2024 |
| HP            | Madoo                       | Notebook    | [06cd6045cd](https://linux-hardware.org/?probe=06cd6045cd) | Feb 17, 2024 |
| Acer          | Aspire 9420                 | Notebook    | [13ef1e26e9](https://linux-hardware.org/?probe=13ef1e26e9) | Feb 17, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [2d74906a7d](https://linux-hardware.org/?probe=2d74906a7d) | Feb 16, 2024 |
| Packard Be... | EasyNote TM85               | Notebook    | [df1899a28b](https://linux-hardware.org/?probe=df1899a28b) | Feb 16, 2024 |
| Dell          | System XPS L502X            | Notebook    | [0e7ad1a462](https://linux-hardware.org/?probe=0e7ad1a462) | Feb 16, 2024 |
| Dell          | Vostro 1500                 | Notebook    | [c6a22855f4](https://linux-hardware.org/?probe=c6a22855f4) | Feb 16, 2024 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [b3549ef96d](https://linux-hardware.org/?probe=b3549ef96d) | Feb 16, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c325b99554](https://linux-hardware.org/?probe=c325b99554) | Feb 16, 2024 |
| HP            | Pavilion dm3 Notebook PC    | Notebook    | [3e0f898cc8](https://linux-hardware.org/?probe=3e0f898cc8) | Feb 16, 2024 |
| Dell          | Precision 5760              | Notebook    | [ef46809f82](https://linux-hardware.org/?probe=ef46809f82) | Feb 16, 2024 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [42f4db38c2](https://linux-hardware.org/?probe=42f4db38c2) | Feb 16, 2024 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [78b9324e29](https://linux-hardware.org/?probe=78b9324e29) | Feb 16, 2024 |
| Dell          | 0C522T A00                  | Desktop     | [fc865abc9f](https://linux-hardware.org/?probe=fc865abc9f) | Feb 16, 2024 |
| Dell          | Precision 5760              | Notebook    | [596105a102](https://linux-hardware.org/?probe=596105a102) | Feb 16, 2024 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [1fa513616f](https://linux-hardware.org/?probe=1fa513616f) | Feb 16, 2024 |
| Intel         | DH67GD AAG10206-205         | Desktop     | [c1b6c3c87e](https://linux-hardware.org/?probe=c1b6c3c87e) | Feb 16, 2024 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [697d384203](https://linux-hardware.org/?probe=697d384203) | Feb 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [8dcedb7dea](https://linux-hardware.org/?probe=8dcedb7dea) | Feb 16, 2024 |
| MSI           | 2AE0                        | Desktop     | [85d065236b](https://linux-hardware.org/?probe=85d065236b) | Feb 15, 2024 |
| MSI           | B450-A PRO MAX              | Desktop     | [ca82f5e8f1](https://linux-hardware.org/?probe=ca82f5e8f1) | Feb 15, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [84485c262a](https://linux-hardware.org/?probe=84485c262a) | Feb 15, 2024 |
| Dell          | Latitude 7490               | Notebook    | [65ce0de8b5](https://linux-hardware.org/?probe=65ce0de8b5) | Feb 15, 2024 |
| Dell          | Studio XPS 1640             | Notebook    | [79baf0c0bf](https://linux-hardware.org/?probe=79baf0c0bf) | Feb 15, 2024 |
| Dell          | Latitude E7440              | Notebook    | [64e8b40f82](https://linux-hardware.org/?probe=64e8b40f82) | Feb 15, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [6ea4dd15da](https://linux-hardware.org/?probe=6ea4dd15da) | Feb 15, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [e23c7132d2](https://linux-hardware.org/?probe=e23c7132d2) | Feb 15, 2024 |
| MSI           | CR61 3M                     | Notebook    | [6a7b9ef9b5](https://linux-hardware.org/?probe=6a7b9ef9b5) | Feb 15, 2024 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [e6ae670af4](https://linux-hardware.org/?probe=e6ae670af4) | Feb 15, 2024 |
| HP            | 3047h                       | Desktop     | [05f8efc7c6](https://linux-hardware.org/?probe=05f8efc7c6) | Feb 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [37f24823aa](https://linux-hardware.org/?probe=37f24823aa) | Feb 15, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [5b8e7f1992](https://linux-hardware.org/?probe=5b8e7f1992) | Feb 14, 2024 |
| Acer          | Aspire VX5-591G             | Notebook    | [ab712b6e6c](https://linux-hardware.org/?probe=ab712b6e6c) | Feb 14, 2024 |
| Acer          | v1.0                        | Desktop     | [a7ba3b84dc](https://linux-hardware.org/?probe=a7ba3b84dc) | Feb 14, 2024 |
| Acer          | Aspire TC-603               | Desktop     | [a715d81d90](https://linux-hardware.org/?probe=a715d81d90) | Feb 14, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [02bcb4fe60](https://linux-hardware.org/?probe=02bcb4fe60) | Feb 14, 2024 |
| Acer          | Predator PH315-53           | Notebook    | [3c0f830342](https://linux-hardware.org/?probe=3c0f830342) | Feb 14, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | Desktop     | [ea66a8f18a](https://linux-hardware.org/?probe=ea66a8f18a) | Feb 14, 2024 |
| HP            | Pavilion dv7                | Notebook    | [2eb4dfdcd4](https://linux-hardware.org/?probe=2eb4dfdcd4) | Feb 14, 2024 |
| Samsung       | 300E5M/300E5L               | Notebook    | [c3f528e22b](https://linux-hardware.org/?probe=c3f528e22b) | Feb 13, 2024 |
| Dell          | Latitude E6440              | Notebook    | [fa5a14dd0c](https://linux-hardware.org/?probe=fa5a14dd0c) | Feb 13, 2024 |
| Acer          | Acadia V1.34                | Desktop     | [6807342689](https://linux-hardware.org/?probe=6807342689) | Feb 13, 2024 |
| Microsoft     | Surface Pro 8               | Tablet      | [fdecfbe5c3](https://linux-hardware.org/?probe=fdecfbe5c3) | Feb 13, 2024 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [9616627427](https://linux-hardware.org/?probe=9616627427) | Feb 13, 2024 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [85e7855e2c](https://linux-hardware.org/?probe=85e7855e2c) | Feb 13, 2024 |
| MSI           | A75A-G55                    | Desktop     | [66928cfe0f](https://linux-hardware.org/?probe=66928cfe0f) | Feb 13, 2024 |
| Microsoft     | Surface Pro 8               | Tablet      | [2bede56961](https://linux-hardware.org/?probe=2bede56961) | Feb 13, 2024 |
| Unknown       | W1415A                      | Notebook    | [a0c020f290](https://linux-hardware.org/?probe=a0c020f290) | Feb 13, 2024 |
| HP            | 871A                        | Mini pc     | [90ec8dae7e](https://linux-hardware.org/?probe=90ec8dae7e) | Feb 13, 2024 |
| Acer          | Extensa 2510                | Notebook    | [06a4171f11](https://linux-hardware.org/?probe=06a4171f11) | Feb 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [79819299d1](https://linux-hardware.org/?probe=79819299d1) | Feb 13, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [60877f4bf7](https://linux-hardware.org/?probe=60877f4bf7) | Feb 12, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [23bd060420](https://linux-hardware.org/?probe=23bd060420) | Feb 12, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [71ad520752](https://linux-hardware.org/?probe=71ad520752) | Feb 12, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [7442b9508b](https://linux-hardware.org/?probe=7442b9508b) | Feb 12, 2024 |
| Lenovo        | ThinkPad T430s 2356G2U      | Notebook    | [1d52e2a841](https://linux-hardware.org/?probe=1d52e2a841) | Feb 12, 2024 |
| Lenovo        | ThinkPad T430s 2356G2U      | Notebook    | [8cd0c1b29a](https://linux-hardware.org/?probe=8cd0c1b29a) | Feb 12, 2024 |
| HP            | Notebook                    | Notebook    | [bdd85f3367](https://linux-hardware.org/?probe=bdd85f3367) | Feb 12, 2024 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [e1f108277a](https://linux-hardware.org/?probe=e1f108277a) | Feb 12, 2024 |
| AZW           | GT-R                        | Notebook    | [0d11177457](https://linux-hardware.org/?probe=0d11177457) | Feb 12, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [534eec7fca](https://linux-hardware.org/?probe=534eec7fca) | Feb 12, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [26a59a1a00](https://linux-hardware.org/?probe=26a59a1a00) | Feb 11, 2024 |
| HP            | 420                         | Notebook    | [810770c1ad](https://linux-hardware.org/?probe=810770c1ad) | Feb 11, 2024 |
| Dell          | 0VYXHD A00                  | Desktop     | [134cac2a6d](https://linux-hardware.org/?probe=134cac2a6d) | Feb 11, 2024 |
| Dell          | 0VYXHD A00                  | Desktop     | [8178dd22d5](https://linux-hardware.org/?probe=8178dd22d5) | Feb 11, 2024 |
| AMI           | Cherry Trail CR             | Desktop     | [aca9ec8d0b](https://linux-hardware.org/?probe=aca9ec8d0b) | Feb 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [a22b67cf36](https://linux-hardware.org/?probe=a22b67cf36) | Feb 11, 2024 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [eb7f318e9b](https://linux-hardware.org/?probe=eb7f318e9b) | Feb 11, 2024 |
| Dell          | Inspiron 5406 2n1           | Convertible | [5c6edac85e](https://linux-hardware.org/?probe=5c6edac85e) | Feb 11, 2024 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b77f3676c7](https://linux-hardware.org/?probe=b77f3676c7) | Feb 11, 2024 |
| Positivo      | N4350                       | Notebook    | [295e7d702b](https://linux-hardware.org/?probe=295e7d702b) | Feb 11, 2024 |
| Acer          | Nitro AN515-42              | Notebook    | [352247befa](https://linux-hardware.org/?probe=352247befa) | Feb 11, 2024 |
| Acer          | Aspire 5742G                | Notebook    | [513a3ecbf9](https://linux-hardware.org/?probe=513a3ecbf9) | Feb 10, 2024 |
| Apple         | MacBook9,1                  | Notebook    | [55780ffb72](https://linux-hardware.org/?probe=55780ffb72) | Feb 10, 2024 |
| Acer          | E1-510                      | Notebook    | [2299bd85ba](https://linux-hardware.org/?probe=2299bd85ba) | Feb 10, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | Desktop     | [0fa5fdbad2](https://linux-hardware.org/?probe=0fa5fdbad2) | Feb 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [f8f4e3c485](https://linux-hardware.org/?probe=f8f4e3c485) | Feb 10, 2024 |
| Dell          | Latitude E6400              | Notebook    | [1173395b8b](https://linux-hardware.org/?probe=1173395b8b) | Feb 10, 2024 |
| MSI           | H61M-P20                    | Desktop     | [b364c76f36](https://linux-hardware.org/?probe=b364c76f36) | Feb 10, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [4b01e8f0c4](https://linux-hardware.org/?probe=4b01e8f0c4) | Feb 10, 2024 |
| MSI           | H61M-P20                    | Desktop     | [2dd188e5d9](https://linux-hardware.org/?probe=2dd188e5d9) | Feb 10, 2024 |
| Lenovo        | ThinkPad T410 2537CF3       | Notebook    | [7be1e6e033](https://linux-hardware.org/?probe=7be1e6e033) | Feb 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [e648cf049c](https://linux-hardware.org/?probe=e648cf049c) | Feb 10, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [284bdb6d3c](https://linux-hardware.org/?probe=284bdb6d3c) | Feb 10, 2024 |
| ASUSTek       | K52Jc                       | Notebook    | [145dc41606](https://linux-hardware.org/?probe=145dc41606) | Feb 10, 2024 |
| HP            | ProBook 430 G1              | Notebook    | [191e61f6f6](https://linux-hardware.org/?probe=191e61f6f6) | Feb 09, 2024 |
| Dell          | 0VRWRC A00                  | Desktop     | [1dfe3721a8](https://linux-hardware.org/?probe=1dfe3721a8) | Feb 09, 2024 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [f5fd1fd3ae](https://linux-hardware.org/?probe=f5fd1fd3ae) | Feb 09, 2024 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [49f5211e0b](https://linux-hardware.org/?probe=49f5211e0b) | Feb 09, 2024 |
| Fujitsu       | LIFEBOOK E544               | Notebook    | [2cb0310c0f](https://linux-hardware.org/?probe=2cb0310c0f) | Feb 09, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Zorin 16 | 4033      | 58.91%  |
| Zorin 15 | 1652      | 24.13%  |
| Zorin 17 | 963       | 14.07%  |
| Zorin 12 | 198       | 2.89%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Zorin | 6793      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 235       | 3%      |
| 5.11.0-38-generic | 181       | 2.31%   |
| 6.2.0-39-generic  | 172       | 2.19%   |
| 5.11.0-27-generic | 156       | 1.99%   |
| 5.15.0-46-generic | 152       | 1.94%   |
| 5.15.0-58-generic | 151       | 1.93%   |
| 5.15.0-52-generic | 151       | 1.93%   |
| 6.5.0-26-generic  | 149       | 1.9%    |
| 5.15.0-91-generic | 146       | 1.86%   |
| 5.15.0-67-generic | 145       | 1.85%   |
| 5.15.0-69-generic | 136       | 1.73%   |
| 5.15.0-78-generic | 134       | 1.71%   |
| 5.13.0-30-generic | 126       | 1.61%   |
| 5.11.0-40-generic | 123       | 1.57%   |
| 5.13.0-39-generic | 122       | 1.56%   |
| 6.5.0-28-generic  | 120       | 1.53%   |
| 5.15.0-60-generic | 113       | 1.44%   |
| 5.3.0-40-generic  | 110       | 1.4%    |
| 5.11.0-41-generic | 109       | 1.39%   |
| 5.15.0-71-generic | 108       | 1.38%   |
| 5.15.0-76-generic | 107       | 1.36%   |
| 5.11.0-37-generic | 106       | 1.35%   |
| 5.11.0-43-generic | 100       | 1.28%   |
| 6.5.0-14-generic  | 99        | 1.26%   |
| 5.4.0-42-generic  | 99        | 1.26%   |
| 6.5.0-25-generic  | 95        | 1.21%   |
| 5.15.0-48-generic | 95        | 1.21%   |
| 5.11.0-34-generic | 95        | 1.21%   |
| 5.15.0-88-generic | 94        | 1.2%    |
| 6.5.0-21-generic  | 93        | 1.19%   |
| 6.5.0-15-generic  | 93        | 1.19%   |
| 5.13.0-40-generic | 90        | 1.15%   |
| 5.15.0-84-generic | 81        | 1.03%   |
| 5.15.0-53-generic | 81        | 1.03%   |
| 5.0.0-37-generic  | 79        | 1.01%   |
| 6.5.0-27-generic  | 78        | 0.99%   |
| 5.15.0-41-generic | 77        | 0.98%   |
| 5.13.0-44-generic | 76        | 0.97%   |
| 5.13.0-35-generic | 74        | 0.94%   |
| 5.3.0-46-generic  | 73        | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 2354      | 33.28%  |
| 5.4.0   | 978       | 13.83%  |
| 5.11.0  | 947       | 13.39%  |
| 6.5.0   | 779       | 11.01%  |
| 5.13.0  | 770       | 10.88%  |
| 5.3.0   | 487       | 6.88%   |
| 4.15.0  | 191       | 2.7%    |
| 6.2.0   | 179       | 2.53%   |
| 5.0.0   | 153       | 2.16%   |
| 4.18.0  | 76        | 1.07%   |
| 5.8.0   | 55        | 0.78%   |
| 5.14.0  | 10        | 0.14%   |
| 6.3.13  | 6         | 0.08%   |
| 4.4.0   | 6         | 0.08%   |
| 6.5.7   | 4         | 0.06%   |
| 6.2.16  | 3         | 0.04%   |
| 5.7.1   | 3         | 0.04%   |
| 6.8.7   | 2         | 0.03%   |
| 6.3.2   | 2         | 0.03%   |
| 5.7.0   | 2         | 0.03%   |
| 5.6.0   | 2         | 0.03%   |
| 5.19.12 | 2         | 0.03%   |
| 5.19.0  | 2         | 0.03%   |
| 5.18.15 | 2         | 0.03%   |
| 5.17.5  | 2         | 0.03%   |
| 5.17.1  | 2         | 0.03%   |
| 5.16.0  | 2         | 0.03%   |
| 5.10.0  | 2         | 0.03%   |
| 4.13.0  | 2         | 0.03%   |
| 6.7.7   | 1         | 0.01%   |
| 6.7.6   | 1         | 0.01%   |
| 6.7.5   | 1         | 0.01%   |
| 6.7.3   | 1         | 0.01%   |
| 6.7.2   | 1         | 0.01%   |
| 6.7.10  | 1         | 0.01%   |
| 6.6.7   | 1         | 0.01%   |
| 6.6.13  | 1         | 0.01%   |
| 6.6.11  | 1         | 0.01%   |
| 6.6.10  | 1         | 0.01%   |
| 6.6.1   | 1         | 0.01%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 2358      | 33.35%  |
| 5.4     | 980       | 13.86%  |
| 5.11    | 947       | 13.39%  |
| 6.5     | 783       | 11.07%  |
| 5.13    | 772       | 10.92%  |
| 5.3     | 487       | 6.89%   |
| 4.15    | 191       | 2.7%    |
| 6.2     | 184       | 2.6%    |
| 5.0     | 153       | 2.16%   |
| 4.18    | 76        | 1.07%   |
| 5.8     | 56        | 0.79%   |
| 6.3     | 10        | 0.14%   |
| 5.14    | 10        | 0.14%   |
| 5.19    | 9         | 0.13%   |
| 5.7     | 6         | 0.08%   |
| 4.4     | 6         | 0.08%   |
| 6.7     | 5         | 0.07%   |
| 6.6     | 5         | 0.07%   |
| 5.17    | 5         | 0.07%   |
| 5.16    | 5         | 0.07%   |
| 6.0     | 4         | 0.06%   |
| 5.18    | 4         | 0.06%   |
| 5.10    | 4         | 0.06%   |
| 6.1     | 3         | 0.04%   |
| 6.8     | 2         | 0.03%   |
| 5.9     | 2         | 0.03%   |
| 5.6     | 2         | 0.03%   |
| 4.13    | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 6392      | 94.06%  |
| i686   | 404       | 5.94%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 5251      | 76.44%  |
| XFCE            | 1270      | 18.49%  |
| Unknown         | 306       | 4.45%   |
| KDE5            | 11        | 0.16%   |
| X-Cinnamon      | 9         | 0.13%   |
| Unity           | 4         | 0.06%   |
| KDE             | 4         | 0.06%   |
| Budgie          | 4         | 0.06%   |
| Cinnamon        | 3         | 0.04%   |
| MATE            | 2         | 0.03%   |
| i3              | 2         | 0.03%   |
| LXQt            | 1         | 0.01%   |
| LXDE            | 1         | 0.01%   |
| GNOME Flashback | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5836      | 84.92%  |
| Wayland | 840       | 12.22%  |
| Unknown | 191       | 2.78%   |
| Tty     | 5         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 5497      | 79.45%  |
| GDM3    | 622       | 8.99%   |
| GDM     | 461       | 6.66%   |
| LightDM | 324       | 4.68%   |
| TDM     | 11        | 0.16%   |
| SDDM    | 3         | 0.04%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2490      | 36.42%  |
| de_DE   | 598       | 8.75%   |
| pt_BR   | 434       | 6.35%   |
| en_GB   | 403       | 5.89%   |
| it_IT   | 264       | 3.86%   |
| fr_FR   | 247       | 3.61%   |
| Unknown | 232       | 3.39%   |
| es_ES   | 195       | 2.85%   |
| en_CA   | 193       | 2.82%   |
| en_IN   | 173       | 2.53%   |
| pl_PL   | 147       | 2.15%   |
| nl_NL   | 113       | 1.65%   |
| en_AU   | 113       | 1.65%   |
| es_MX   | 95        | 1.39%   |
| ru_RU   | 82        | 1.2%    |
| pt_PT   | 74        | 1.08%   |
| es_AR   | 70        | 1.02%   |
| en_ZA   | 65        | 0.95%   |
| cs_CZ   | 57        | 0.83%   |
| hu_HU   | 50        | 0.73%   |
| tr_TR   | 43        | 0.63%   |
| sv_SE   | 41        | 0.6%    |
| es_CL   | 36        | 0.53%   |
| en_NZ   | 34        | 0.5%    |
| es_CO   | 31        | 0.45%   |
| C       | 31        | 0.45%   |
| de_AT   | 30        | 0.44%   |
| fr_CA   | 28        | 0.41%   |
| ja_JP   | 26        | 0.38%   |
| de_CH   | 26        | 0.38%   |
| nl_BE   | 25        | 0.37%   |
| da_DK   | 23        | 0.34%   |
| el_GR   | 21        | 0.31%   |
| fr_BE   | 20        | 0.29%   |
| nb_NO   | 17        | 0.25%   |
| es_PE   | 17        | 0.25%   |
| en_PH   | 17        | 0.25%   |
| fi_FI   | 16        | 0.23%   |
| bg_BG   | 15        | 0.22%   |
| sk_SK   | 14        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3923      | 56.9%   |
| EFI  | 2971      | 43.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 6212      | 90.53%  |
| Tmpfs    | 245       | 3.57%   |
| Overlay  | 136       | 1.98%   |
| Zfs      | 112       | 1.63%   |
| Btrfs    | 68        | 0.99%   |
| Ext2     | 37        | 0.54%   |
| Unknown  | 27        | 0.39%   |
| Ext3     | 12        | 0.17%   |
| Xfs      | 11        | 0.16%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 5861      | 85.13%  |
| GPT     | 782       | 11.36%  |
| MBR     | 242       | 3.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6482      | 94.89%  |
| Yes       | 349       | 5.11%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5790      | 84.51%  |
| Yes       | 1061      | 15.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 1156      | 17.02%  |
| ASUSTek Computer    | 933       | 13.73%  |
| Dell                | 876       | 12.9%   |
| Lenovo              | 820       | 12.07%  |
| Acer                | 381       | 5.61%   |
| Gigabyte Technology | 369       | 5.43%   |
| MSI                 | 286       | 4.21%   |
| Apple               | 234       | 3.44%   |
| Toshiba             | 193       | 2.84%   |
| ASRock              | 173       | 2.55%   |
| Intel               | 109       | 1.6%    |
| Unknown             | 97        | 1.43%   |
| Samsung Electronics | 86        | 1.27%   |
| Sony                | 70        | 1.03%   |
| Fujitsu             | 61        | 0.9%    |
| Microsoft           | 45        | 0.66%   |
| Positivo            | 43        | 0.63%   |
| Pegatron            | 43        | 0.63%   |
| Google              | 42        | 0.62%   |
| Packard Bell        | 40        | 0.59%   |
| HUAWEI              | 39        | 0.57%   |
| Medion              | 36        | 0.53%   |
| Biostar             | 32        | 0.47%   |
| Foxconn             | 27        | 0.4%    |
| Alienware           | 25        | 0.37%   |
| Fujitsu Siemens     | 23        | 0.34%   |
| ECS                 | 23        | 0.34%   |
| AZW                 | 23        | 0.34%   |
| AMI                 | 21        | 0.31%   |
| Notebook            | 16        | 0.24%   |
| Chuwi               | 15        | 0.22%   |
| Gateway             | 14        | 0.21%   |
| eMachines           | 13        | 0.19%   |
| Semp Toshiba        | 12        | 0.18%   |
| Panasonic           | 12        | 0.18%   |
| Multilaser          | 10        | 0.15%   |
| Shuttle             | 9         | 0.13%   |
| NEC Computers       | 9         | 0.13%   |
| IBM                 | 8         | 0.12%   |
| Itautec             | 7         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 137       | 2.02%   |
| ASUS All Series            | 47        | 0.69%   |
| HP Notebook                | 37        | 0.54%   |
| HP Pavilion Notebook       | 19        | 0.28%   |
| HP Pavilion dv6            | 19        | 0.28%   |
| HP 15                      | 19        | 0.28%   |
| Dell OptiPlex 7010         | 19        | 0.28%   |
| HP Pavilion dv7            | 16        | 0.24%   |
| HP Pavilion 15             | 14        | 0.21%   |
| MSI MS-7817                | 13        | 0.19%   |
| Microsoft Surface Pro 4    | 12        | 0.18%   |
| Dell Latitude E6400        | 12        | 0.18%   |
| Dell Inspiron 1545         | 12        | 0.18%   |
| ASUS TUF Gaming X570-PLUS  | 12        | 0.18%   |
| Lenovo MIIX 320-10ICR 80XF | 11        | 0.16%   |
| Gigabyte A320M-S2H         | 11        | 0.16%   |
| Dell OptiPlex 990          | 11        | 0.16%   |
| Dell OptiPlex 790          | 11        | 0.16%   |
| Dell OptiPlex 780          | 11        | 0.16%   |
| Dell OptiPlex 380          | 11        | 0.16%   |
| Dell Latitude D630         | 11        | 0.16%   |
| ASUS M5A97 R2.0            | 11        | 0.16%   |
| Apple MacBookPro9,2        | 11        | 0.16%   |
| Apple iMac12,1             | 11        | 0.16%   |
| Toshiba Satellite C660     | 10        | 0.15%   |
| Intel H61                  | 10        | 0.15%   |
| HP Pavilion g7             | 10        | 0.15%   |
| HP Pavilion g6             | 10        | 0.15%   |
| Dell Inspiron 15-3567      | 10        | 0.15%   |
| Apple iMac12,2             | 10        | 0.15%   |
| HP Laptop 15-bw0xx         | 9         | 0.13%   |
| HP EliteBook 840 G1        | 9         | 0.13%   |
| Gigabyte B450 AORUS M      | 9         | 0.13%   |
| Dell OptiPlex 755          | 9         | 0.13%   |
| Dell OptiPlex 3010         | 9         | 0.13%   |
| Dell Latitude E6540        | 9         | 0.13%   |
| Dell Latitude E6430        | 9         | 0.13%   |
| Dell Inspiron 1525         | 9         | 0.13%   |
| ASUS M5A78L-M/USB3         | 9         | 0.13%   |
| Apple MacBookPro8,1        | 9         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 271       | 3.99%   |
| Acer Aspire           | 250       | 3.68%   |
| HP Pavilion           | 246       | 3.62%   |
| Dell Inspiron         | 244       | 3.59%   |
| Dell Latitude         | 225       | 3.31%   |
| Lenovo IdeaPad        | 196       | 2.89%   |
| Dell OptiPlex         | 167       | 2.46%   |
| Toshiba Satellite     | 163       | 2.4%    |
| Unknown               | 137       | 2.02%   |
| HP Compaq             | 132       | 1.94%   |
| HP EliteBook          | 115       | 1.69%   |
| HP ProBook            | 101       | 1.49%   |
| HP Laptop             | 85        | 1.25%   |
| Lenovo ThinkCentre    | 79        | 1.16%   |
| ASUS ROG              | 78        | 1.15%   |
| ASUS PRIME            | 68        | 1%      |
| ASUS TUF              | 62        | 0.91%   |
| ASUS VivoBook         | 60        | 0.88%   |
| Dell Precision        | 59        | 0.87%   |
| Dell Vostro           | 55        | 0.81%   |
| Dell XPS              | 51        | 0.75%   |
| HP ENVY               | 48        | 0.71%   |
| ASUS All              | 47        | 0.69%   |
| Lenovo Yoga           | 46        | 0.68%   |
| Microsoft Surface     | 45        | 0.66%   |
| HP Notebook           | 37        | 0.54%   |
| Packard Bell EasyNote | 33        | 0.49%   |
| HP EliteDesk          | 33        | 0.49%   |
| ASUS ZenBook          | 27        | 0.4%    |
| Fujitsu LIFEBOOK      | 25        | 0.37%   |
| HP Stream             | 24        | 0.35%   |
| HP 15                 | 24        | 0.35%   |
| HP ZBook              | 23        | 0.34%   |
| Fujitsu ESPRIMO       | 21        | 0.31%   |
| Apple iMac12          | 21        | 0.31%   |
| HP ProDesk            | 19        | 0.28%   |
| Dell Studio           | 19        | 0.28%   |
| ASUS ASUS             | 19        | 0.28%   |
| Lenovo Legion         | 18        | 0.26%   |
| HP Presario           | 18        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 553       | 8.14%   |
| 2012    | 546       | 8.04%   |
| 2013    | 540       | 7.95%   |
| 2018    | 477       | 7.02%   |
| 2010    | 445       | 6.55%   |
| 2014    | 430       | 6.33%   |
| 2017    | 414       | 6.09%   |
| 2021    | 413       | 6.08%   |
| 2019    | 403       | 5.93%   |
| 2008    | 388       | 5.71%   |
| 2020    | 387       | 5.7%    |
| 2009    | 344       | 5.06%   |
| 2015    | 325       | 4.78%   |
| 2016    | 317       | 4.67%   |
| 2007    | 274       | 4.03%   |
| 2022    | 195       | 2.87%   |
| 2023    | 125       | 1.84%   |
| 2006    | 113       | 1.66%   |
| 2005    | 67        | 0.99%   |
| 2004    | 11        | 0.16%   |
| Unknown | 11        | 0.16%   |
| 2003    | 8         | 0.12%   |
| 2024    | 6         | 0.09%   |
| 2002    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 3864      | 56.88%  |
| Desktop     | 2399      | 35.32%  |
| Convertible | 152       | 2.24%   |
| All in one  | 151       | 2.22%   |
| Tablet      | 115       | 1.69%   |
| Mini pc     | 96        | 1.41%   |
| Server      | 16        | 0.24%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6221      | 91%     |
| Enabled  | 615       | 9%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6745      | 99.29%  |
| Yes  | 48        | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1753      | 25.51%  |
| 3.01-4.0        | 1609      | 23.41%  |
| 8.01-16.0       | 1055      | 15.35%  |
| 16.01-24.0      | 1014      | 14.76%  |
| 1.01-2.0        | 519       | 7.55%   |
| 32.01-64.0      | 435       | 6.33%   |
| 2.01-3.0        | 182       | 2.65%   |
| 64.01-256.0     | 118       | 1.72%   |
| 0.51-1.0        | 101       | 1.47%   |
| 24.01-32.0      | 84        | 1.22%   |
| More than 256.0 | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2831      | 38.25%  |
| 2.01-3.0   | 2204      | 29.78%  |
| 3.01-4.0   | 933       | 12.6%   |
| 4.01-8.0   | 782       | 10.56%  |
| 0.51-1.0   | 463       | 6.26%   |
| 8.01-16.0  | 122       | 1.65%   |
| 0.01-0.5   | 42        | 0.57%   |
| 16.01-24.0 | 17        | 0.23%   |
| 24.01-32.0 | 6         | 0.08%   |
| 32.01-64.0 | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4556      | 65.59%  |
| 2       | 1624      | 23.38%  |
| 3       | 401       | 5.77%   |
| 4       | 173       | 2.49%   |
| 5       | 80        | 1.15%   |
| 6       | 45        | 0.65%   |
| 0       | 25        | 0.36%   |
| 7       | 17        | 0.24%   |
| 8       | 16        | 0.23%   |
| 11      | 2         | 0.03%   |
| 10      | 2         | 0.03%   |
| 9       | 2         | 0.03%   |
| 51      | 1         | 0.01%   |
| 30      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3662      | 53.61%  |
| Yes       | 3169      | 46.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5835      | 85.75%  |
| No        | 970       | 14.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5441      | 79.76%  |
| No        | 1381      | 20.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3798      | 55.36%  |
| No        | 3062      | 44.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1508      | 22.11%  |
| Germany      | 677       | 9.93%   |
| Brazil       | 494       | 7.24%   |
| UK           | 396       | 5.81%   |
| Italy        | 290       | 4.25%   |
| Canada       | 246       | 3.61%   |
| France       | 238       | 3.49%   |
| Spain        | 208       | 3.05%   |
| Netherlands  | 191       | 2.8%    |
| India        | 184       | 2.7%    |
| Poland       | 148       | 2.17%   |
| Mexico       | 130       | 1.91%   |
| Australia    | 123       | 1.8%    |
| Portugal     | 90        | 1.32%   |
| Argentina    | 86        | 1.26%   |
| Russia       | 78        | 1.14%   |
| Sweden       | 77        | 1.13%   |
| Belgium      | 77        | 1.13%   |
| South Africa | 74        | 1.09%   |
| Czechia      | 69        | 1.01%   |
| Switzerland  | 62        | 0.91%   |
| Romania      | 62        | 0.91%   |
| Austria      | 62        | 0.91%   |
| Turkey       | 58        | 0.85%   |
| Greece       | 58        | 0.85%   |
| Hungary      | 55        | 0.81%   |
| Indonesia    | 53        | 0.78%   |
| Norway       | 46        | 0.67%   |
| Colombia     | 46        | 0.67%   |
| Egypt        | 43        | 0.63%   |
| Denmark      | 43        | 0.63%   |
| Chile        | 42        | 0.62%   |
| New Zealand  | 41        | 0.6%    |
| Japan        | 40        | 0.59%   |
| Serbia       | 37        | 0.54%   |
| Bulgaria     | 31        | 0.45%   |
| Finland      | 29        | 0.43%   |
| Philippines  | 26        | 0.38%   |
| Slovakia     | 24        | 0.35%   |
| Ukraine      | 21        | 0.31%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Berlin         | 60        | 0.84%   |
| Sao Paulo      | 50        | 0.7%    |
| Rio de Janeiro | 41        | 0.57%   |
| Milan          | 40        | 0.56%   |
| Sydney         | 38        | 0.53%   |
| Vienna         | 36        | 0.5%    |
| Munich         | 35        | 0.49%   |
| Athens         | 34        | 0.48%   |
| Rome           | 33        | 0.46%   |
| Madrid         | 32        | 0.45%   |
| Johannesburg   | 27        | 0.38%   |
| Hamburg        | 27        | 0.38%   |
| New York       | 26        | 0.36%   |
| Montreal       | 26        | 0.36%   |
| Paris          | 24        | 0.34%   |
| Cairo          | 23        | 0.32%   |
| Bogotá        | 23        | 0.32%   |
| Amsterdam      | 23        | 0.32%   |
| Toronto        | 22        | 0.31%   |
| London         | 22        | 0.31%   |
| Istanbul       | 22        | 0.31%   |
| Warsaw         | 21        | 0.29%   |
| Stockholm      | 21        | 0.29%   |
| Mexico City    | 21        | 0.29%   |
| Denver         | 21        | 0.29%   |
| Dallas         | 21        | 0.29%   |
| Belgrade       | 21        | 0.29%   |
| Auckland       | 21        | 0.29%   |
| Melbourne      | 20        | 0.28%   |
| Cape Town      | 20        | 0.28%   |
| Bucharest      | 20        | 0.28%   |
| Bengaluru      | 20        | 0.28%   |
| Perth          | 19        | 0.27%   |
| Moscow         | 19        | 0.27%   |
| Lisbon         | 19        | 0.27%   |
| Delhi          | 19        | 0.27%   |
| Calgary        | 19        | 0.27%   |
| Buenos Aires   | 19        | 0.27%   |
| Prague         | 18        | 0.25%   |
| Houston        | 18        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1383      | 1925   | 14.78%  |
| WDC                         | 1322      | 1787   | 14.13%  |
| Samsung Electronics         | 1199      | 1722   | 12.81%  |
| Toshiba                     | 680       | 837    | 7.27%   |
| Unknown                     | 535       | 750    | 5.72%   |
| SanDisk                     | 505       | 653    | 5.4%    |
| Kingston                    | 500       | 658    | 5.34%   |
| Hitachi                     | 380       | 464    | 4.06%   |
| Crucial                     | 306       | 368    | 3.27%   |
| Intel                       | 173       | 219    | 1.85%   |
| SK hynix                    | 170       | 201    | 1.82%   |
| HGST                        | 165       | 202    | 1.76%   |
| China                       | 139       | 166    | 1.49%   |
| Micron Technology           | 117       | 141    | 1.25%   |
| A-DATA Technology           | 105       | 128    | 1.12%   |
| Apple                       | 101       | 120    | 1.08%   |
| Intenso                     | 77        | 88     | 0.82%   |
| PNY                         | 65        | 84     | 0.69%   |
| Silicon Motion              | 59        | 75     | 0.63%   |
| Phison                      | 56        | 72     | 0.6%    |
| Micron/Crucial Technology   | 55        | 67     | 0.59%   |
| Maxtor                      | 51        | 70     | 0.54%   |
| KIOXIA                      | 50        | 56     | 0.53%   |
| Fujitsu                     | 50        | 53     | 0.53%   |
| Unknown                     | 49        | 55     | 0.52%   |
| SPCC                        | 48        | 63     | 0.51%   |
| Patriot                     | 40        | 58     | 0.43%   |
| Netac                       | 36        | 42     | 0.38%   |
| Phison Electronics          | 34        | 41     | 0.36%   |
| OCZ                         | 34        | 38     | 0.36%   |
| JMicron Technology          | 32        | 40     | 0.34%   |
| GOODRAM                     | 32        | 39     | 0.34%   |
| Transcend                   | 30        | 53     | 0.32%   |
| LITEON                      | 30        | 36     | 0.32%   |
| MAXIO Technology (Hangzhou) | 28        | 28     | 0.3%    |
| Kingston Technology Company | 28        | 33     | 0.3%    |
| Lexar                       | 25        | 28     | 0.27%   |
| Hewlett-Packard             | 25        | 34     | 0.27%   |
| Team                        | 24        | 27     | 0.26%   |
| LITEONIT                    | 24        | 29     | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                                | 161       | 1.59%   |
| Unknown MMC Card  64GB                                | 157       | 1.55%   |
| Kingston SA400S37240G 240GB SSD                       | 125       | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 78        | 0.77%   |
| Seagate ST500DM002-1BD142 500GB                       | 74        | 0.73%   |
| Kingston SA400S37480G 480GB SSD                       | 74        | 0.73%   |
| Seagate ST1000LM035-1RK172 1TB                        | 70        | 0.69%   |
| Unknown MMC Card  128GB                               | 65        | 0.64%   |
| Toshiba MQ01ABF050 500GB                              | 65        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                       | 63        | 0.62%   |
| Crucial CT240BX500SSD1 240GB                          | 60        | 0.59%   |
| Toshiba MQ01ABD100 1TB                                | 59        | 0.58%   |
| Samsung SSD 860 EVO 500GB                             | 57        | 0.56%   |
| Seagate ST500LT012-1DG142 500GB                       | 55        | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 54        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                        | 51        | 0.5%    |
| Samsung SSD 850 EVO 250GB                             | 49        | 0.48%   |
| Unknown                                               | 49        | 0.48%   |
| Toshiba MQ04ABF100 1TB                                | 46        | 0.45%   |
| Crucial CT500MX500SSD1 500GB                          | 45        | 0.44%   |
| Samsung SSD 850 EVO 500GB                             | 44        | 0.43%   |
| Seagate ST9500325AS 500GB                             | 43        | 0.42%   |
| Unknown SD/MMC/MS PRO 128GB                           | 39        | 0.38%   |
| Toshiba DT01ACA100 1TB                                | 36        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD                      | 36        | 0.36%   |
| Seagate ST3500418AS 500GB                             | 35        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                        | 35        | 0.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB     | 35        | 0.35%   |
| Samsung SSD 860 EVO 250GB                             | 34        | 0.34%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 34        | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 34        | 0.34%   |
| Samsung NVMe SSD Drive 512GB                          | 33        | 0.33%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 32        | 0.32%   |
| Unknown MMC Card  16GB                                | 32        | 0.32%   |
| Seagate Expansion 2TB                                 | 31        | 0.31%   |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 30        | 0.3%    |
| Samsung NVMe SSD Drive 500GB                          | 30        | 0.3%    |
| Samsung NVMe SSD Drive 1TB                            | 29        | 0.29%   |
| Crucial CT1000MX500SSD1 1TB                           | 29        | 0.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 28        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1359      | 1877   | 33.38%  |
| WDC                 | 1153      | 1545   | 28.32%  |
| Toshiba             | 562       | 698    | 13.8%   |
| Hitachi             | 380       | 464    | 9.33%   |
| Samsung Electronics | 191       | 241    | 4.69%   |
| HGST                | 165       | 202    | 4.05%   |
| Fujitsu             | 50        | 53     | 1.23%   |
| Maxtor              | 49        | 68     | 1.2%    |
| Apple               | 43        | 47     | 1.06%   |
| Unknown             | 41        | 55     | 1.01%   |
| JMicron Technology  | 22        | 27     | 0.54%   |
| SABRENT             | 18        | 22     | 0.44%   |
| IBM/Hitachi         | 5         | 6      | 0.12%   |
| Hewlett-Packard     | 5         | 11     | 0.12%   |
| TO Exter            | 4         | 5      | 0.1%    |
| Intenso             | 4         | 6      | 0.1%    |
| XrayDisk            | 3         | 3      | 0.07%   |
| USB3.0              | 2         | 3      | 0.05%   |
| Quantum             | 2         | 2      | 0.05%   |
| LaCie               | 2         | 3      | 0.05%   |
| ASMT                | 2         | 3      | 0.05%   |
| WD MediaMax         | 1         | 1      | 0.02%   |
| Unknown (CF)        | 1         | 1      | 0.02%   |
| TDAS                | 1         | 3      | 0.02%   |
| KESU                | 1         | 1      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| FC-1307             | 1         | 1      | 0.02%   |
| ExcelStor           | 1         | 1      | 0.02%   |
| ASMT109x            | 1         | 2      | 0.02%   |
| ACASIS              | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 610       | 858    | 19.86%  |
| Kingston            | 427       | 545    | 13.9%   |
| Crucial             | 293       | 353    | 9.54%   |
| SanDisk             | 270       | 343    | 8.79%   |
| WDC                 | 151       | 189    | 4.92%   |
| China               | 136       | 163    | 4.43%   |
| A-DATA Technology   | 96        | 119    | 3.13%   |
| Intel               | 78        | 89     | 2.54%   |
| PNY                 | 65        | 84     | 2.12%   |
| Toshiba             | 54        | 62     | 1.76%   |
| Intenso             | 53        | 58     | 1.73%   |
| Micron Technology   | 51        | 61     | 1.66%   |
| SK hynix            | 49        | 55     | 1.6%    |
| SPCC                | 46        | 61     | 1.5%    |
| Apple               | 45        | 49     | 1.47%   |
| Patriot             | 38        | 56     | 1.24%   |
| Netac               | 34        | 39     | 1.11%   |
| OCZ                 | 32        | 36     | 1.04%   |
| Transcend           | 30        | 53     | 0.98%   |
| LITEON              | 30        | 36     | 0.98%   |
| GOODRAM             | 30        | 37     | 0.98%   |
| Team                | 24        | 27     | 0.78%   |
| LITEONIT            | 24        | 29     | 0.78%   |
| Lexar               | 23        | 26     | 0.75%   |
| KingSpec            | 22        | 25     | 0.72%   |
| Unknown             | 20        | 26     | 0.65%   |
| Hewlett-Packard     | 18        | 21     | 0.59%   |
| Apacer              | 16        | 20     | 0.52%   |
| Gigabyte Technology | 14        | 21     | 0.46%   |
| Verbatim            | 11        | 14     | 0.36%   |
| Corsair             | 11        | 17     | 0.36%   |
| ASMT                | 11        | 11     | 0.36%   |
| Leven               | 9         | 10     | 0.29%   |
| Fanxiang            | 9         | 10     | 0.29%   |
| Plextor             | 8         | 9      | 0.26%   |
| Phison              | 8         | 12     | 0.26%   |
| Mushkin             | 8         | 8      | 0.26%   |
| KIOXIA-EXCERIA      | 8         | 13     | 0.26%   |
| Teclast             | 7         | 8      | 0.23%   |
| OWC                 | 7         | 10     | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3542      | 5353   | 41.75%  |
| SSD     | 2755      | 3902   | 32.47%  |
| NVMe    | 1488      | 2076   | 17.54%  |
| MMC     | 497       | 674    | 5.86%   |
| Unknown | 202       | 262    | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5466      | 8998   | 70.09%  |
| NVMe | 1485      | 2066   | 19.04%  |
| MMC  | 497       | 674    | 6.37%   |
| SAS  | 350       | 529    | 4.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4208      | 6007   | 64.96%  |
| 0.51-1.0   | 1626      | 2247   | 25.1%   |
| 1.01-2.0   | 395       | 557    | 6.1%    |
| 3.01-4.0   | 114       | 222    | 1.76%   |
| 4.01-10.0  | 61        | 90     | 0.94%   |
| 2.01-3.0   | 59        | 95     | 0.91%   |
| 10.01-20.0 | 14        | 35     | 0.22%   |
| 20.01-50.0 | 1         | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2340      | 33.22%  |
| 251-500        | 1713      | 24.32%  |
| 501-1000       | 977       | 13.87%  |
| 51-100         | 659       | 9.36%   |
| 1001-2000      | 370       | 5.25%   |
| 21-50          | 362       | 5.14%   |
| More than 3000 | 219       | 3.11%   |
| 1-20           | 207       | 2.94%   |
| 2001-3000      | 116       | 1.65%   |
| Unknown        | 80        | 1.14%   |
| 0              | 1         | 0.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3132      | 42.64%  |
| 21-50          | 1891      | 25.74%  |
| 51-100         | 821       | 11.18%  |
| 101-250        | 637       | 8.67%   |
| 251-500        | 363       | 4.94%   |
| 501-1000       | 198       | 2.7%    |
| 1001-2000      | 100       | 1.36%   |
| More than 3000 | 87        | 1.18%   |
| Unknown        | 80        | 1.09%   |
| 2001-3000      | 36        | 0.49%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB               | 4         | 4      | 2.7%    |
| Seagate ST9500325AS 500GB            | 4         | 4      | 2.7%    |
| HGST HTS545050A7E680 500GB           | 3         | 3      | 2.03%   |
| HGST HTS541010A9E680 1TB             | 3         | 3      | 2.03%   |
| WDC WD30EFRX-68EUZN0 3TB             | 2         | 2      | 1.35%   |
| Toshiba MQ02ABD100H 1TB              | 2         | 2      | 1.35%   |
| Toshiba MQ01ABF050 500GB             | 2         | 2      | 1.35%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 1.35%   |
| Seagate ST9500420AS 500GB            | 2         | 2      | 1.35%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 2      | 1.35%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 2      | 1.35%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 2      | 1.35%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 2      | 1.35%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 2      | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 2      | 1.35%   |
| Kingston SUV400S37240G 240GB SSD     | 2         | 2      | 1.35%   |
| HGST HTS721010A9E630 1TB             | 2         | 2      | 1.35%   |
| HGST HTS545050A7E380 500GB           | 2         | 3      | 1.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 1      | 0.68%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1      | 0.68%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 1      | 0.68%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1      | 0.68%   |
| WDC WD5000BPVT-75HXZT1 500GB         | 1         | 1      | 0.68%   |
| WDC WD5000BEVT-24A0RT0 500GB         | 1         | 1      | 0.68%   |
| WDC WD5000AAKS-00V1A0 500GB          | 1         | 1      | 0.68%   |
| WDC WD3200BPVT-55ZEST0 320GB         | 1         | 1      | 0.68%   |
| WDC WD3200AAKS-22B3A0 320GB          | 1         | 1      | 0.68%   |
| WDC WD3200AAJS-00L7A0 320GB          | 1         | 1      | 0.68%   |
| WDC WD2500BEKT-75PVMT1 250GB         | 1         | 1      | 0.68%   |
| WDC WD2500AAJS-00B4A0 250GB          | 1         | 1      | 0.68%   |
| WDC WD20EZRX-22D8PB0 2TB             | 1         | 1      | 0.68%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 1      | 0.68%   |
| WDC WD1200BEVS-60UST0 120GB          | 1         | 1      | 0.68%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 1      | 0.68%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 1      | 0.68%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1      | 0.68%   |
| WDC WD10JPVT-55A1YT0 1TB             | 1         | 1      | 0.68%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1         | 2      | 0.68%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1         | 1      | 0.68%   |
| WDC WD Green 2.5 1000GB              | 1         | 1      | 0.68%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 48     | 31.97%  |
| WDC                 | 24        | 25     | 16.33%  |
| Toshiba             | 20        | 20     | 13.61%  |
| HGST                | 12        | 13     | 8.16%   |
| Hitachi             | 9         | 9      | 6.12%   |
| Samsung Electronics | 8         | 8      | 5.44%   |
| Kingston            | 6         | 6      | 4.08%   |
| SK hynix            | 2         | 2      | 1.36%   |
| Intel               | 2         | 2      | 1.36%   |
| A-DATA Technology   | 2         | 2      | 1.36%   |
| Teclast             | 1         | 1      | 0.68%   |
| Silicon Motion      | 1         | 1      | 0.68%   |
| SanDisk             | 1         | 1      | 0.68%   |
| POLION              | 1         | 1      | 0.68%   |
| OCZ                 | 1         | 1      | 0.68%   |
| Netac               | 1         | 1      | 0.68%   |
| Micron Technology   | 1         | 1      | 0.68%   |
| Maxtor              | 1         | 1      | 0.68%   |
| LITEONIT            | 1         | 1      | 0.68%   |
| LITEON              | 1         | 1      | 0.68%   |
| Hewlett-Packard     | 1         | 1      | 0.68%   |
| Drevo               | 1         | 1      | 0.68%   |
| China               | 1         | 1      | 0.68%   |
| Apple               | 1         | 1      | 0.68%   |
| Unknown             | 1         | 1      | 0.68%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 48     | 41.59%  |
| WDC                 | 22        | 23     | 19.47%  |
| Toshiba             | 17        | 17     | 15.04%  |
| HGST                | 12        | 13     | 10.62%  |
| Hitachi             | 9         | 9      | 7.96%   |
| Samsung Electronics | 4         | 4      | 3.54%   |
| Maxtor              | 1         | 1      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 109       | 116    | 76.22%  |
| SSD  | 30        | 30     | 20.98%  |
| NVMe | 4         | 4      | 2.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 6219      | 11183  | 89.43%  |
| Works    | 591       | 931    | 8.5%    |
| Malfunc  | 141       | 150    | 2.03%   |
| Failed   | 2         | 2      | 0.03%   |
| Fixed    | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4659      | 58.38%  |
| AMD                              | 1210      | 15.16%  |
| Samsung Electronics              | 501       | 6.28%   |
| SanDisk                          | 256       | 3.21%   |
| Nvidia                           | 179       | 2.24%   |
| SK hynix                         | 115       | 1.44%   |
| Kingston Technology Company      | 106       | 1.33%   |
| ASMedia Technology               | 102       | 1.28%   |
| Phison Electronics               | 90        | 1.13%   |
| JMicron Technology               | 83        | 1.04%   |
| Micron/Crucial Technology        | 67        | 0.84%   |
| Micron Technology                | 67        | 0.84%   |
| Marvell Technology Group         | 67        | 0.84%   |
| Silicon Motion                   | 66        | 0.83%   |
| Toshiba America Info Systems     | 64        | 0.8%    |
| KIOXIA                           | 54        | 0.68%   |
| VIA Technologies                 | 42        | 0.53%   |
| Silicon Integrated Systems [SiS] | 38        | 0.48%   |
| MAXIO Technology (Hangzhou)      | 31        | 0.39%   |
| ADATA Technology                 | 30        | 0.38%   |
| Realtek Semiconductor            | 22        | 0.28%   |
| Silicon Image                    | 16        | 0.2%    |
| Seagate Technology               | 14        | 0.18%   |
| Apple                            | 12        | 0.15%   |
| Shenzhen Longsys Electronics     | 11        | 0.14%   |
| Broadcom / LSI                   | 10        | 0.13%   |
| Union Memory (Shenzhen)          | 9         | 0.11%   |
| Solid State Storage Technology   | 9         | 0.11%   |
| Lite-On Technology               | 8         | 0.1%    |
| LSI Logic / Symbios Logic        | 7         | 0.09%   |
| Netac Technology                 | 4         | 0.05%   |
| Integrated Technology Express    | 4         | 0.05%   |
| INNOGRIT                         | 4         | 0.05%   |
| OCZ Technology Group             | 3         | 0.04%   |
| Adaptec                          | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| Lenovo                           | 2         | 0.03%   |
| HighPoint Technologies           | 2         | 0.03%   |
| Unknown                          | 2         | 0.03%   |
| TenaFe                           | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 737       | 7.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 330       | 3.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 318       | 3.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 317       | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 250       | 2.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 230       | 2.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 209       | 2.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 199       | 2.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 194       | 2.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 193       | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 179       | 1.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 170       | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 161       | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 158       | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 147       | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 131       | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 123       | 1.3%    |
| AMD 400 Series Chipset SATA Controller                                                  | 121       | 1.28%   |
| Intel SATA Controller [RAID mode]                                                       | 117       | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 117       | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 113       | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 113       | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 113       | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 109       | 1.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 101       | 1.07%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 95        | 1.01%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 93        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 90        | 0.95%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 82        | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 77        | 0.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 76        | 0.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 73        | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 69        | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 64        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 63        | 0.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 62        | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 62        | 0.66%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 60        | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 58        | 0.61%   |
| Nvidia MCP61 SATA Controller                                                            | 53        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4858      | 58.85%  |
| NVMe | 1486      | 18%     |
| IDE  | 1341      | 16.24%  |
| RAID | 549       | 6.65%   |
| SAS  | 15        | 0.18%   |
| SCSI | 6         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 5321      | 78.33%  |
| AMD          | 1470      | 21.64%  |
| CentaurHauls | 2         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 83        | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 52        | 0.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 51        | 0.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 49        | 0.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 48        | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 47        | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 46        | 0.68%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 46        | 0.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 45        | 0.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 45        | 0.66%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 43        | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 39        | 0.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 36        | 0.53%   |
| AMD Ryzen 5 3600 6-Core Processor             | 36        | 0.53%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 36        | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 34        | 0.5%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 34        | 0.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 33        | 0.48%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 33        | 0.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 32        | 0.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 31        | 0.46%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 0.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 0.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 28        | 0.41%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 28        | 0.41%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 27        | 0.4%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 27        | 0.4%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 26        | 0.38%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 26        | 0.38%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 25        | 0.37%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 25        | 0.37%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 24        | 0.35%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 24        | 0.35%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 24        | 0.35%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 24        | 0.35%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 23        | 0.34%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 23        | 0.34%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 23        | 0.34%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 23        | 0.34%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 23        | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1411      | 20.75%  |
| Intel Core i7           | 893       | 13.13%  |
| Intel Core i3           | 620       | 9.12%   |
| Intel Celeron           | 467       | 6.87%   |
| Intel Core 2 Duo        | 434       | 6.38%   |
| Other                   | 338       | 4.97%   |
| AMD Ryzen 5             | 286       | 4.21%   |
| Intel Atom              | 248       | 3.65%   |
| Intel Pentium           | 196       | 2.88%   |
| AMD Ryzen 7             | 195       | 2.87%   |
| Intel Xeon              | 131       | 1.93%   |
| Intel Pentium Dual-Core | 118       | 1.74%   |
| AMD FX                  | 95        | 1.4%    |
| Intel Pentium Dual      | 87        | 1.28%   |
| AMD A6                  | 82        | 1.21%   |
| Intel Core 2 Quad       | 78        | 1.15%   |
| AMD Ryzen 9             | 77        | 1.13%   |
| AMD Ryzen 3             | 74        | 1.09%   |
| AMD A8                  | 63        | 0.93%   |
| AMD A4                  | 62        | 0.91%   |
| Intel Core 2            | 56        | 0.82%   |
| AMD A10                 | 53        | 0.78%   |
| Intel Genuine           | 49        | 0.72%   |
| AMD Athlon 64 X2        | 47        | 0.69%   |
| AMD Athlon II X2        | 45        | 0.66%   |
| Intel Pentium 4         | 44        | 0.65%   |
| AMD Phenom II X4        | 34        | 0.5%    |
| AMD E1                  | 33        | 0.49%   |
| Intel Celeron M         | 29        | 0.43%   |
| Intel Pentium M         | 27        | 0.4%    |
| AMD E                   | 26        | 0.38%   |
| AMD Athlon              | 26        | 0.38%   |
| Intel Core i9           | 23        | 0.34%   |
| AMD Sempron             | 22        | 0.32%   |
| Intel Pentium Silver    | 20        | 0.29%   |
| AMD Turion 64 X2 Mobile | 19        | 0.28%   |
| Intel Core M            | 16        | 0.24%   |
| AMD E2                  | 15        | 0.22%   |
| Intel Pentium Gold      | 14        | 0.21%   |
| Intel Celeron Dual-Core | 13        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 3376      | 49.62%  |
| 4      | 2151      | 31.61%  |
| 6      | 412       | 6.06%   |
| 1      | 317       | 4.66%   |
| 8      | 306       | 4.5%    |
| 12     | 73        | 1.07%   |
| 10     | 47        | 0.69%   |
| 3      | 44        | 0.65%   |
| 16     | 35        | 0.51%   |
| 14     | 26        | 0.38%   |
| 24     | 8         | 0.12%   |
| 20     | 4         | 0.06%   |
| 28     | 2         | 0.03%   |
| 40     | 1         | 0.01%   |
| 32     | 1         | 0.01%   |
| 18     | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 6766      | 99.6%   |
| 2      | 27        | 0.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 3837      | 56.46%  |
| 1      | 2959      | 43.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6636      | 97.67%  |
| 32-bit         | 155       | 2.28%   |
| Unknown        | 3         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1458      | 21.05%  |
| 0x206a7    | 460       | 6.64%   |
| 0x306a9    | 387       | 5.59%   |
| 0x1067a    | 358       | 5.17%   |
| 0x306c3    | 317       | 4.58%   |
| 0x40651    | 162       | 2.34%   |
| 0x6fd      | 158       | 2.28%   |
| 0x20655    | 146       | 2.11%   |
| 0x406e3    | 139       | 2.01%   |
| 0x806e9    | 126       | 1.82%   |
| 0x306d4    | 119       | 1.72%   |
| 0x406c4    | 113       | 1.63%   |
| 0x30678    | 113       | 1.63%   |
| 0x806c1    | 110       | 1.59%   |
| 0x506e3    | 105       | 1.52%   |
| 0x806ea    | 97        | 1.4%    |
| 0x906ea    | 87        | 1.26%   |
| 0x906e9    | 86        | 1.24%   |
| 0x806ec    | 86        | 1.24%   |
| 0x10676    | 78        | 1.13%   |
| 0x010000c8 | 69        | 1%      |
| 0x706a8    | 67        | 0.97%   |
| 0x506c9    | 64        | 0.92%   |
| 0x6fb      | 60        | 0.87%   |
| 0x08108109 | 60        | 0.87%   |
| 0x06000852 | 59        | 0.85%   |
| 0x20652    | 58        | 0.84%   |
| 0x06001119 | 56        | 0.81%   |
| 0x08701021 | 55        | 0.79%   |
| 0x406c3    | 54        | 0.78%   |
| 0x706e5    | 48        | 0.69%   |
| 0x6f6      | 47        | 0.68%   |
| 0x06006705 | 43        | 0.62%   |
| 0x106ca    | 39        | 0.56%   |
| 0x0800820d | 38        | 0.55%   |
| 0x0700010f | 36        | 0.52%   |
| 0x05000119 | 35        | 0.51%   |
| 0x0a50000c | 34        | 0.49%   |
| 0x6d8      | 33        | 0.48%   |
| 0x07030105 | 33        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 702       | 10.33%  |
| Haswell          | 613       | 9.02%   |
| SandyBridge      | 568       | 8.36%   |
| Penryn           | 517       | 7.61%   |
| IvyBridge        | 499       | 7.34%   |
| Core             | 350       | 5.15%   |
| Silvermont       | 338       | 4.97%   |
| Skylake          | 311       | 4.57%   |
| Westmere         | 263       | 3.87%   |
| Unknown          | 197       | 2.9%    |
| Zen 3            | 172       | 2.53%   |
| Zen 2            | 164       | 2.41%   |
| K10              | 163       | 2.4%    |
| Zen+             | 157       | 2.31%   |
| Broadwell        | 153       | 2.25%   |
| TigerLake        | 145       | 2.13%   |
| Piledriver       | 141       | 2.07%   |
| Goldmont plus    | 134       | 1.97%   |
| K8 Hammer        | 115       | 1.69%   |
| Excavator        | 100       | 1.47%   |
| CometLake        | 98        | 1.44%   |
| Zen              | 92        | 1.35%   |
| P6               | 91        | 1.34%   |
| Icelake          | 90        | 1.32%   |
| Bonnell          | 84        | 1.24%   |
| Goldmont         | 80        | 1.18%   |
| NetBurst         | 62        | 0.91%   |
| Puma             | 60        | 0.88%   |
| Nehalem          | 58        | 0.85%   |
| Bobcat           | 55        | 0.81%   |
| Alderlake Hybrid | 49        | 0.72%   |
| Jaguar           | 48        | 0.71%   |
| K10 Llano        | 33        | 0.49%   |
| Steamroller      | 30        | 0.44%   |
| Bulldozer        | 25        | 0.37%   |
| K8 & K10 hybrid  | 21        | 0.31%   |
| Tremont          | 17        | 0.25%   |
| K6               | 3         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4062      | 52.76%  |
| Nvidia                           | 1794      | 23.3%   |
| AMD                              | 1775      | 23.05%  |
| Silicon Integrated Systems [SiS] | 30        | 0.39%   |
| VIA Technologies                 | 21        | 0.27%   |
| Matrox Electronics Systems       | 9         | 0.12%   |
| ASPEED Technology                | 5         | 0.06%   |
| Trident Microsystems             | 1         | 0.01%   |
| Silicon Motion                   | 1         | 0.01%   |
| ATI Technologies                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 431       | 5.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 299       | 3.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 193       | 2.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 187       | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 173       | 2.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 171       | 2.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 152       | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 149       | 1.86%   |
| Intel HD Graphics 620                                                                    | 136       | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 135       | 1.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 119       | 1.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 115       | 1.43%   |
| Intel UHD Graphics 620                                                                   | 112       | 1.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 107       | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 104       | 1.3%    |
| Intel HD Graphics 5500                                                                   | 97        | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 94        | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 94        | 1.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 88        | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 85        | 1.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 78        | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 76        | 0.95%   |
| Intel HD Graphics 530                                                                    | 74        | 0.92%   |
| Intel HD Graphics 630                                                                    | 72        | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 70        | 0.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 69        | 0.86%   |
| Intel HD Graphics 500                                                                    | 68        | 0.85%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 67        | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 65        | 0.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 64        | 0.8%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 62        | 0.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 58        | 0.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 57        | 0.71%   |
| AMD Lucienne                                                                             | 46        | 0.57%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 44        | 0.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 42        | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 40        | 0.5%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 40        | 0.5%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 40        | 0.5%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 40        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 3264      | 47.82%  |
| 1 x AMD                  | 1418      | 20.77%  |
| 1 x Nvidia               | 1160      | 16.99%  |
| Intel + Nvidia           | 535       | 7.84%   |
| Intel + AMD              | 179       | 2.62%   |
| 2 x AMD                  | 102       | 1.49%   |
| AMD + Nvidia             | 73        | 1.07%   |
| 1 x SiS                  | 30        | 0.44%   |
| 1 x VIA                  | 21        | 0.31%   |
| 2 x Nvidia               | 16        | 0.23%   |
| Other                    | 10        | 0.15%   |
| 1 x Matrox               | 7         | 0.1%    |
| 1 x ASPEED               | 3         | 0.04%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.01%   |
| 2 x Intel                | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.01%   |
| 1 x Trident Microsystems | 1         | 0.01%   |
| Nvidia + Silicon Motion  | 1         | 0.01%   |
| Nvidia + Matrox          | 1         | 0.01%   |
| Nvidia + ASPEED          | 1         | 0.01%   |
| AMD + Matrox             | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5561      | 81.23%  |
| Proprietary | 966       | 14.11%  |
| Unknown     | 319       | 4.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4322      | 62.49%  |
| 0.01-0.5   | 906       | 13.1%   |
| 1.01-2.0   | 597       | 8.63%   |
| 0.51-1.0   | 496       | 7.17%   |
| 3.01-4.0   | 249       | 3.6%    |
| 7.01-8.0   | 172       | 2.49%   |
| 5.01-6.0   | 72        | 1.04%   |
| 8.01-16.0  | 58        | 0.84%   |
| 2.01-3.0   | 39        | 0.56%   |
| 16.01-24.0 | 4         | 0.06%   |
| 4.01-5.0   | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 938       | 13.93%  |
| AU Optronics            | 823       | 12.22%  |
| LG Display              | 593       | 8.81%   |
| BOE                     | 539       | 8%      |
| Chimei Innolux          | 521       | 7.74%   |
| Dell                    | 315       | 4.68%   |
| Goldstar                | 313       | 4.65%   |
| Hewlett-Packard         | 240       | 3.56%   |
| Apple                   | 202       | 3%      |
| Acer                    | 193       | 2.87%   |
| AOC                     | 147       | 2.18%   |
| Chi Mei Optoelectronics | 140       | 2.08%   |
| Philips                 | 130       | 1.93%   |
| Lenovo                  | 111       | 1.65%   |
| Ancor Communications    | 107       | 1.59%   |
| BenQ                    | 103       | 1.53%   |
| LG Philips              | 83        | 1.23%   |
| Sharp                   | 82        | 1.22%   |
| InfoVision              | 64        | 0.95%   |
| ViewSonic               | 61        | 0.91%   |
| Sony                    | 53        | 0.79%   |
| LG Electronics          | 46        | 0.68%   |
| PANDA                   | 45        | 0.67%   |
| Unknown                 | 42        | 0.62%   |
| ASUSTek Computer        | 35        | 0.52%   |
| Vizio                   | 33        | 0.49%   |
| Toshiba                 | 32        | 0.48%   |
| Unknown                 | 31        | 0.46%   |
| Iiyama                  | 29        | 0.43%   |
| HannStar                | 29        | 0.43%   |
| CPT                     | 25        | 0.37%   |
| Fujitsu Siemens         | 23        | 0.34%   |
| Eizo                    | 23        | 0.34%   |
| Panasonic               | 21        | 0.31%   |
| Sceptre Tech            | 20        | 0.3%    |
| NEC Computers           | 19        | 0.28%   |
| MSI                     | 18        | 0.27%   |
| Quanta Display          | 12        | 0.18%   |
| InnoLux Display         | 12        | 0.18%   |
| LGD                     | 11        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 45        | 0.65%   |
| Unknown                                                                  | 31        | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 30        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 27        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 24        | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 22        | 0.32%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 21        | 0.3%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 20        | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 20        | 0.29%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 20        | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 19        | 0.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 18        | 0.26%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 18        | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 17        | 0.25%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 17        | 0.25%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 17        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 16        | 0.23%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 16        | 0.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 16        | 0.23%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 14        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 14        | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 14        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 14        | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 13        | 0.19%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 13        | 0.19%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 13        | 0.19%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 13        | 0.19%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 13        | 0.19%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 13        | 0.19%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 12        | 0.17%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 12        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 12        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 12        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 12        | 0.17%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 11        | 0.16%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 11        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2341      | 35.53%  |
| 1366x768 (WXGA)    | 1706      | 25.9%   |
| 1600x900 (HD+)     | 344       | 5.22%   |
| 3840x2160 (4K)     | 325       | 4.93%   |
| 1280x800 (WXGA)    | 277       | 4.2%    |
| 1440x900 (WXGA+)   | 210       | 3.19%   |
| 1280x1024 (SXGA)   | 190       | 2.88%   |
| 1680x1050 (WSXGA+) | 181       | 2.75%   |
| 2560x1440 (QHD)    | 163       | 2.47%   |
| 1920x1200 (WUXGA)  | 115       | 1.75%   |
| Unknown            | 90        | 1.37%   |
| 1360x768           | 77        | 1.17%   |
| 3440x1440          | 52        | 0.79%   |
| 1024x600           | 50        | 0.76%   |
| 3840x1080          | 46        | 0.7%    |
| 2560x1600          | 46        | 0.7%    |
| 2560x1080          | 46        | 0.7%    |
| 2880x1800          | 29        | 0.44%   |
| 1024x768 (XGA)     | 28        | 0.43%   |
| 2736x1824          | 27        | 0.41%   |
| 1920x540           | 26        | 0.39%   |
| 2160x1440          | 18        | 0.27%   |
| 3200x1800 (QHD+)   | 12        | 0.18%   |
| 2256x1504          | 12        | 0.18%   |
| 3840x2400          | 10        | 0.15%   |
| 1600x1200          | 10        | 0.15%   |
| 1920x1280          | 9         | 0.14%   |
| 1280x768           | 9         | 0.14%   |
| 1280x720 (HD)      | 9         | 0.14%   |
| 5760x1080          | 8         | 0.12%   |
| 3600x1080          | 5         | 0.08%   |
| 2880x1920          | 5         | 0.08%   |
| 1400x1050          | 5         | 0.08%   |
| 5760x2160          | 4         | 0.06%   |
| 4480x1440          | 4         | 0.06%   |
| 3840x1600          | 4         | 0.06%   |
| 2304x1440          | 4         | 0.06%   |
| 2288x1287          | 4         | 0.06%   |
| 1680x945           | 4         | 0.06%   |
| 3840x1200          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1790      | 26.75%  |
| 13      | 625       | 9.34%   |
| 14      | 525       | 7.85%   |
| Unknown | 483       | 7.22%   |
| 17      | 411       | 6.14%   |
| 27      | 335       | 5.01%   |
| 24      | 309       | 4.62%   |
| 21      | 305       | 4.56%   |
| 23      | 294       | 4.39%   |
| 19      | 189       | 2.82%   |
| 18      | 165       | 2.47%   |
| 11      | 148       | 2.21%   |
| 12      | 144       | 2.15%   |
| 20      | 137       | 2.05%   |
| 31      | 135       | 2.02%   |
| 22      | 107       | 1.6%    |
| 34      | 80        | 1.2%    |
| 10      | 70        | 1.05%   |
| 16      | 54        | 0.81%   |
| 84      | 46        | 0.69%   |
| 40      | 44        | 0.66%   |
| 72      | 36        | 0.54%   |
| 54      | 34        | 0.51%   |
| 26      | 27        | 0.4%    |
| 32      | 23        | 0.34%   |
| 65      | 14        | 0.21%   |
| 49      | 13        | 0.19%   |
| 25      | 13        | 0.19%   |
| 52      | 12        | 0.18%   |
| 28      | 10        | 0.15%   |
| 48      | 9         | 0.13%   |
| 36      | 9         | 0.13%   |
| 46      | 8         | 0.12%   |
| 29      | 8         | 0.12%   |
| 42      | 7         | 0.1%    |
| 74      | 6         | 0.09%   |
| 39      | 6         | 0.09%   |
| 37      | 6         | 0.09%   |
| 33      | 5         | 0.07%   |
| 8       | 5         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2701      | 40.86%  |
| 501-600        | 889       | 13.45%  |
| 401-500        | 798       | 12.07%  |
| 201-300        | 652       | 9.86%   |
| 351-400        | 496       | 7.5%    |
| Unknown        | 483       | 7.31%   |
| 601-700        | 186       | 2.81%   |
| 701-800        | 116       | 1.75%   |
| 1001-1500      | 116       | 1.75%   |
| 1501-2000      | 93        | 1.41%   |
| 801-900        | 59        | 0.89%   |
| 901-1000       | 14        | 0.21%   |
| 101-200        | 6         | 0.09%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4522      | 72.48%  |
| 16/10   | 852       | 13.66%  |
| Unknown | 420       | 6.73%   |
| 5/4     | 172       | 2.76%   |
| 3/2     | 88        | 1.41%   |
| 21/9    | 88        | 1.41%   |
| 4/3     | 55        | 0.88%   |
| 32/9    | 21        | 0.34%   |
| 6/5     | 10        | 0.16%   |
| 3.73    | 3         | 0.05%   |
| 0.62    | 2         | 0.03%   |
| 3.20    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 1.00    | 1         | 0.02%   |
| 0.80    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.25    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1778      | 26.76%  |
| 81-90          | 934       | 14.06%  |
| 201-250        | 802       | 12.07%  |
| Unknown        | 483       | 7.27%   |
| 151-200        | 442       | 6.65%   |
| 301-350        | 346       | 5.21%   |
| 351-500        | 257       | 3.87%   |
| 121-130        | 251       | 3.78%   |
| 141-150        | 223       | 3.36%   |
| 71-80          | 220       | 3.31%   |
| More than 1000 | 185       | 2.78%   |
| 51-60          | 151       | 2.27%   |
| 61-70          | 127       | 1.91%   |
| 251-300        | 123       | 1.85%   |
| 501-1000       | 103       | 1.55%   |
| 131-140        | 77        | 1.16%   |
| 41-50          | 67        | 1.01%   |
| 111-120        | 45        | 0.68%   |
| 91-100         | 24        | 0.36%   |
| 1-40           | 6         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 2030      | 31.24%  |
| 51-100        | 2025      | 31.16%  |
| 121-160       | 1377      | 21.19%  |
| Unknown       | 484       | 7.45%   |
| 161-240       | 308       | 4.74%   |
| 1-50          | 170       | 2.62%   |
| More than 240 | 104       | 1.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5761      | 83.4%   |
| 2     | 722       | 10.45%  |
| 0     | 356       | 5.15%   |
| 3     | 62        | 0.9%    |
| 4     | 6         | 0.09%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3639      | 34.52%  |
| Intel                             | 2821      | 26.76%  |
| Qualcomm Atheros                  | 1307      | 12.4%   |
| Broadcom                          | 815       | 7.73%   |
| Broadcom Limited                  | 243       | 2.31%   |
| Marvell Technology Group          | 185       | 1.75%   |
| Ralink Technology                 | 167       | 1.58%   |
| Nvidia                            | 151       | 1.43%   |
| TP-Link                           | 135       | 1.28%   |
| Ralink                            | 132       | 1.25%   |
| MediaTek                          | 108       | 1.02%   |
| Samsung Electronics               | 72        | 0.68%   |
| ASIX Electronics                  | 46        | 0.44%   |
| NetGear                           | 40        | 0.38%   |
| D-Link                            | 36        | 0.34%   |
| Xiaomi                            | 35        | 0.33%   |
| Silicon Integrated Systems [SiS]  | 35        | 0.33%   |
| JMicron Technology                | 35        | 0.33%   |
| VIA Technologies                  | 32        | 0.3%    |
| Sierra Wireless                   | 32        | 0.3%    |
| Dell                              | 32        | 0.3%    |
| DisplayLink                       | 29        | 0.28%   |
| Qualcomm Atheros Communications   | 28        | 0.27%   |
| D-Link System                     | 26        | 0.25%   |
| Microsoft                         | 25        | 0.24%   |
| Huawei Technologies               | 25        | 0.24%   |
| Edimax Technology                 | 21        | 0.2%    |
| ASUSTek Computer                  | 21        | 0.2%    |
| Hewlett-Packard                   | 20        | 0.19%   |
| OPPO Electronics                  | 17        | 0.16%   |
| Motorola PCS                      | 14        | 0.13%   |
| Ericsson Business Mobile Networks | 14        | 0.13%   |
| Belkin Components                 | 14        | 0.13%   |
| Qualcomm                          | 13        | 0.12%   |
| Aquantia                          | 12        | 0.11%   |
| Linksys                           | 10        | 0.09%   |
| AMD                               | 8         | 0.08%   |
| Google                            | 7         | 0.07%   |
| T & A Mobile Phones               | 6         | 0.06%   |
| Attansic Technology               | 6         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 2189      | 17.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 621       | 5.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 279       | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 187       | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 179       | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 171       | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 168       | 1.37%   |
| Intel Wireless 7260                                                     | 164       | 1.33%   |
| Intel Wi-Fi 6 AX200                                                     | 161       | 1.31%   |
| Intel Wireless 7265                                                     | 155       | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 144       | 1.17%   |
| Intel Wireless 8265 / 8275                                              | 139       | 1.13%   |
| Intel Ethernet Connection I217-LM                                       | 128       | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                       | 120       | 0.98%   |
| Intel Wireless 3165                                                     | 111       | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 104       | 0.85%   |
| Intel Wi-Fi 6 AX201                                                     | 104       | 0.85%   |
| Intel Wireless 8260                                                     | 96        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 95        | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 94        | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 87        | 0.71%   |
| Intel I211 Gigabit Network Connection                                   | 82        | 0.67%   |
| Realtek 802.11ac NIC                                                    | 81        | 0.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 80        | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 80        | 0.65%   |
| Ralink MT7601U Wireless Adapter                                         | 75        | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 74        | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 74        | 0.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 74        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 72        | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 71        | 0.58%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 71        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 67        | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 65        | 0.53%   |
| Intel WiFi Link 5100                                                    | 63        | 0.51%   |
| Intel Ethernet Connection (2) I219-V                                    | 63        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 62        | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 58        | 0.47%   |
| Intel Ethernet Controller I225-V                                        | 57        | 0.46%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 57        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2113      | 36.05%  |
| Realtek Semiconductor                 | 1117      | 19.06%  |
| Qualcomm Atheros                      | 1047      | 17.86%  |
| Broadcom                              | 563       | 9.61%   |
| Ralink Technology                     | 167       | 2.85%   |
| Broadcom Limited                      | 159       | 2.71%   |
| Ralink                                | 132       | 2.25%   |
| TP-Link                               | 121       | 2.06%   |
| MediaTek                              | 91        | 1.55%   |
| NetGear                               | 39        | 0.67%   |
| D-Link                                | 36        | 0.61%   |
| Marvell Technology Group              | 34        | 0.58%   |
| Sierra Wireless                       | 32        | 0.55%   |
| Qualcomm Atheros Communications       | 28        | 0.48%   |
| D-Link System                         | 22        | 0.38%   |
| Edimax Technology                     | 21        | 0.36%   |
| Microsoft                             | 20        | 0.34%   |
| Dell                                  | 18        | 0.31%   |
| ASUSTek Computer                      | 18        | 0.31%   |
| Belkin Components                     | 14        | 0.24%   |
| Linksys                               | 9         | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5         | 0.09%   |
| ZyDAS                                 | 4         | 0.07%   |
| TRENDnet                              | 4         | 0.07%   |
| Sitecom Europe                        | 4         | 0.07%   |
| Micro Star International              | 4         | 0.07%   |
| Hewlett-Packard                       | 4         | 0.07%   |
| Gemtek                                | 4         | 0.07%   |
| ZyXEL Communications                  | 3         | 0.05%   |
| IMC Networks                          | 3         | 0.05%   |
| AVM                                   | 3         | 0.05%   |
| Xiaomi                                | 2         | 0.03%   |
| Senao                                 | 2         | 0.03%   |
| Qualcomm                              | 2         | 0.03%   |
| Philips (or NXP)                      | 2         | 0.03%   |
| FIBOCOM                               | 2         | 0.03%   |
| ZTopInc                               | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Qcom                                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 187       | 3.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 179       | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 171       | 2.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 168       | 2.84%   |
| Intel Wireless 7260                                                     | 164       | 2.77%   |
| Intel Wi-Fi 6 AX200                                                     | 161       | 2.72%   |
| Intel Wireless 7265                                                     | 155       | 2.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 144       | 2.43%   |
| Intel Wireless 8265 / 8275                                              | 139       | 2.35%   |
| Intel Wireless 3165                                                     | 111       | 1.88%   |
| Intel Wi-Fi 6 AX201                                                     | 104       | 1.76%   |
| Intel Wireless 8260                                                     | 96        | 1.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 95        | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 94        | 1.59%   |
| Broadcom BCM43142 802.11b/g/n                                           | 87        | 1.47%   |
| Realtek 802.11ac NIC                                                    | 81        | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 80        | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 80        | 1.35%   |
| Ralink MT7601U Wireless Adapter                                         | 75        | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 74        | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 74        | 1.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 74        | 1.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 71        | 1.2%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 71        | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 67        | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 65        | 1.1%    |
| Intel WiFi Link 5100                                                    | 63        | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 58        | 0.98%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 57        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 56        | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 53        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 51        | 0.86%   |
| Intel Wireless 3160                                                     | 50        | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 45        | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 44        | 0.74%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 43        | 0.73%   |
| Intel Centrino Ultimate-N 6300                                          | 43        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 40        | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 39        | 0.66%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 39        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3152      | 51.23%  |
| Intel                                  | 1420      | 23.08%  |
| Qualcomm Atheros                       | 374       | 6.08%   |
| Broadcom                               | 364       | 5.92%   |
| Nvidia                                 | 151       | 2.45%   |
| Marvell Technology Group               | 151       | 2.45%   |
| Broadcom Limited                       | 91        | 1.48%   |
| Samsung Electronics                    | 71        | 1.15%   |
| ASIX Electronics                       | 46        | 0.75%   |
| JMicron Technology                     | 35        | 0.57%   |
| Xiaomi                                 | 33        | 0.54%   |
| Silicon Integrated Systems [SiS]       | 33        | 0.54%   |
| VIA Technologies                       | 32        | 0.52%   |
| DisplayLink                            | 29        | 0.47%   |
| Huawei Technologies                    | 21        | 0.34%   |
| OPPO Electronics                       | 17        | 0.28%   |
| MediaTek                               | 16        | 0.26%   |
| TP-Link                                | 14        | 0.23%   |
| Aquantia                               | 12        | 0.2%    |
| Qualcomm                               | 11        | 0.18%   |
| Motorola PCS                           | 10        | 0.16%   |
| Google                                 | 7         | 0.11%   |
| Hewlett-Packard                        | 6         | 0.1%    |
| Attansic Technology                    | 6         | 0.1%    |
| Microsoft                              | 4         | 0.07%   |
| Lenovo                                 | 4         | 0.07%   |
| D-Link System                          | 4         | 0.07%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.05%   |
| Davicom Semiconductor                  | 3         | 0.05%   |
| ASUSTek Computer                       | 3         | 0.05%   |
| Apple                                  | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.03%   |
| T & A Mobile Phones                    | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.03%   |
| ICS Advent                             | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| vivo                                   | 1         | 0.02%   |
| Sun Microsystems                       | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2189      | 35.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 621       | 9.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 279       | 4.47%   |
| Intel Ethernet Connection I217-LM                                      | 128       | 2.05%   |
| Realtek RTL8125 2.5GbE Controller                                      | 120       | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 104       | 1.67%   |
| Intel I211 Gigabit Network Connection                                  | 82        | 1.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 72        | 1.15%   |
| Intel Ethernet Connection (2) I219-V                                   | 63        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 62        | 0.99%   |
| Intel Ethernet Controller I225-V                                       | 57        | 0.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 55        | 0.88%   |
| Nvidia MCP61 Ethernet                                                  | 50        | 0.8%    |
| Intel Ethernet Connection I218-LM                                      | 46        | 0.74%   |
| Intel 82579V Gigabit Network Connection                                | 46        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 44        | 0.71%   |
| Nvidia MCP79 Ethernet                                                  | 43        | 0.69%   |
| Intel Ethernet Connection I219-LM                                      | 43        | 0.69%   |
| Intel Ethernet Connection I217-V                                       | 41        | 0.66%   |
| Intel 82577LM Gigabit Network Connection                               | 41        | 0.66%   |
| Intel 82567LM Gigabit Network Connection                               | 39        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 37        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                                  | 36        | 0.58%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 36        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                          | 36        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 32        | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 32        | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 32        | 0.51%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 32        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 31        | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 30        | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 29        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 28        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                                   | 27        | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                                  | 27        | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 26        | 0.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 26        | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 26        | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 25        | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 25        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5825      | 51.06%  |
| WiFi     | 5442      | 47.7%   |
| Modem    | 128       | 1.12%   |
| Unknown  | 14        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4277      | 60.63%  |
| Ethernet | 2772      | 39.3%   |
| Unknown  | 3         | 0.04%   |
| Modem    | 2         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3838      | 56.33%  |
| 1     | 2663      | 39.08%  |
| 0     | 194       | 2.85%   |
| 3     | 108       | 1.58%   |
| 5     | 5         | 0.07%   |
| 4     | 5         | 0.07%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5068      | 73.56%  |
| Yes  | 1822      | 26.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1526      | 39.69%  |
| Realtek Semiconductor           | 444       | 11.55%  |
| Qualcomm Atheros Communications | 349       | 9.08%   |
| Broadcom                        | 226       | 5.88%   |
| Apple                           | 214       | 5.57%   |
| Cambridge Silicon Radio         | 209       | 5.44%   |
| IMC Networks                    | 161       | 4.19%   |
| Lite-On Technology              | 105       | 2.73%   |
| Foxconn / Hon Hai               | 105       | 2.73%   |
| Dell                            | 84        | 2.18%   |
| Hewlett-Packard                 | 80        | 2.08%   |
| ASUSTek Computer                | 56        | 1.46%   |
| Toshiba                         | 53        | 1.38%   |
| Ralink                          | 32        | 0.83%   |
| Marvell Semiconductor           | 32        | 0.83%   |
| MediaTek                        | 24        | 0.62%   |
| Realtek                         | 21        | 0.55%   |
| Alps Electric                   | 18        | 0.47%   |
| Foxconn International           | 14        | 0.36%   |
| TP-Link                         | 11        | 0.29%   |
| Dynex                           | 11        | 0.29%   |
| Integrated System Solution      | 9         | 0.23%   |
| Ralink Technology               | 8         | 0.21%   |
| Belkin Components               | 7         | 0.18%   |
| Askey Computer                  | 7         | 0.18%   |
| Actions                         | 7         | 0.18%   |
| Unknown                         | 5         | 0.13%   |
| Taiyo Yuden                     | 4         | 0.1%    |
| Micro Star International        | 4         | 0.1%    |
| Qcom                            | 3         | 0.08%   |
| Chicony Electronics             | 3         | 0.08%   |
| SiW                             | 2         | 0.05%   |
| Logitech                        | 2         | 0.05%   |
| Edimax Technology               | 2         | 0.05%   |
| Smart Modular Technologies      | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| National Semiconductor          | 1         | 0.03%   |
| Mobile Action Technology        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| D-Link System                   | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 470       | 12.21%  |
| Realtek Bluetooth Radio                             | 293       | 7.61%   |
| Intel AX201 Bluetooth                               | 219       | 5.69%   |
| Intel Bluetooth Device                              | 213       | 5.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 209       | 5.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 180       | 4.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 152       | 3.95%   |
| Intel AX200 Bluetooth                               | 143       | 3.71%   |
| Apple Bluetooth Host Controller                     | 91        | 2.36%   |
| Realtek  Bluetooth 4.2 Adapter                      | 84        | 2.18%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 66        | 1.71%   |
| Intel AX210 Bluetooth                               | 65        | 1.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 58        | 1.51%   |
| IMC Networks Bluetooth Device                       | 53        | 1.38%   |
| Intel Wireless-AC 3168 Bluetooth                    | 51        | 1.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 50        | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 48        | 1.25%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 48        | 1.25%   |
| Apple Bluetooth USB Host Controller                 | 48        | 1.25%   |
| Intel AX211 Bluetooth                               | 45        | 1.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 44        | 1.14%   |
| IMC Networks Bluetooth Radio                        | 44        | 1.14%   |
| IMC Networks Wireless_Device                        | 34        | 0.88%   |
| Ralink RT3290 Bluetooth                             | 32        | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 32        | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                    | 32        | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 32        | 0.83%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 31        | 0.81%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 31        | 0.81%   |
| Realtek 802.11ac WLAN Adapter                       | 29        | 0.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 29        | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 29        | 0.75%   |
| Marvell Bluetooth and Wireless LAN Composite        | 28        | 0.73%   |
| HP Broadcom 2070 Bluetooth Combo                    | 26        | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                         | 26        | 0.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 25        | 0.65%   |
| Apple Bluetooth HCI                                 | 25        | 0.65%   |
| Dell DW375 Bluetooth Module                         | 24        | 0.62%   |
| MediaTek Wireless_Device                            | 22        | 0.57%   |
| Lite-On Bluetooth Device                            | 22        | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4990      | 56.45%  |
| AMD                                          | 1781      | 20.15%  |
| Nvidia                                       | 1359      | 15.37%  |
| C-Media Electronics                          | 111       | 1.26%   |
| Creative Labs                                | 48        | 0.54%   |
| VIA Technologies                             | 38        | 0.43%   |
| Silicon Integrated Systems [SiS]             | 38        | 0.43%   |
| Logitech                                     | 36        | 0.41%   |
| JMTek                                        | 32        | 0.36%   |
| Generalplus Technology                       | 28        | 0.32%   |
| ASUSTek Computer                             | 25        | 0.28%   |
| Texas Instruments                            | 23        | 0.26%   |
| Kingston Technology                          | 17        | 0.19%   |
| Plantronics                                  | 16        | 0.18%   |
| GN Netcom                                    | 16        | 0.18%   |
| Realtek Semiconductor                        | 15        | 0.17%   |
| Creative Technology                          | 15        | 0.17%   |
| Tenx Technology                              | 14        | 0.16%   |
| Razer USA                                    | 14        | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 9         | 0.1%    |
| Micro Star International                     | 9         | 0.1%    |
| Lenovo                                       | 9         | 0.1%    |
| SteelSeries ApS                              | 8         | 0.09%   |
| Focusrite-Novation                           | 8         | 0.09%   |
| Corsair                                      | 8         | 0.09%   |
| Sony                                         | 7         | 0.08%   |
| Hewlett-Packard                              | 6         | 0.07%   |
| DCMT Technology                              | 5         | 0.06%   |
| BR25                                         | 5         | 0.06%   |
| Apple                                        | 5         | 0.06%   |
| Yamaha                                       | 4         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 4         | 0.05%   |
| Samsung Electronics                          | 4         | 0.05%   |
| PreSonus Audio Electronics                   | 4         | 0.05%   |
| KTMicro                                      | 4         | 0.05%   |
| DSEA A/S                                     | 4         | 0.05%   |
| BEHRINGER International                      | 4         | 0.05%   |
| Astro Gaming                                 | 4         | 0.05%   |
| AKAI Professional M.I.                       | 4         | 0.05%   |
| SAVITECH                                     | 3         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 535       | 5.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 498       | 4.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 468       | 4.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 410       | 3.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 364       | 3.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 351       | 3.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 295       | 2.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 294       | 2.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 279       | 2.66%   |
| AMD FCH Azalia Controller                                                                         | 262       | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 253       | 2.41%   |
| Intel 8 Series HD Audio Controller                                                                | 196       | 1.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 193       | 1.84%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 192       | 1.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 166       | 1.58%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 157       | 1.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 145       | 1.38%   |
| Intel Broadwell-U Audio Controller                                                                | 145       | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 145       | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 137       | 1.31%   |
| Intel Cannon Lake PCH cAVS                                                                        | 135       | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 134       | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                                          | 134       | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 131       | 1.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 119       | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 106       | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 103       | 0.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 97        | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 96        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 94        | 0.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 87        | 0.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 81        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 80        | 0.76%   |
| Nvidia High Definition Audio Controller                                                           | 79        | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 79        | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 71        | 0.68%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 68        | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 66        | 0.63%   |
| AMD High Definition Audio Controller                                                              | 65        | 0.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 63        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 320       | 22.78%  |
| SK hynix               | 260       | 18.51%  |
| Unknown                | 172       | 12.24%  |
| Micron Technology      | 143       | 10.18%  |
| Kingston               | 121       | 8.61%   |
| Crucial                | 62        | 4.41%   |
| Corsair                | 51        | 3.63%   |
| G.Skill                | 35        | 2.49%   |
| Unknown (ABCD)         | 32        | 2.28%   |
| Elpida                 | 25        | 1.78%   |
| Ramaxel Technology     | 22        | 1.57%   |
| Nanya Technology       | 20        | 1.42%   |
| A-DATA Technology      | 20        | 1.42%   |
| Team                   | 19        | 1.35%   |
| Smart                  | 10        | 0.71%   |
| Unknown                | 10        | 0.71%   |
| Patriot                | 7         | 0.5%    |
| Qimonda                | 6         | 0.43%   |
| Transcend              | 5         | 0.36%   |
| Timetec                | 4         | 0.28%   |
| Teikon                 | 3         | 0.21%   |
| Smart Brazil           | 3         | 0.21%   |
| Avant                  | 3         | 0.21%   |
| Wilk                   | 2         | 0.14%   |
| Unifosa                | 2         | 0.14%   |
| SHARETRONIC            | 2         | 0.14%   |
| PNY                    | 2         | 0.14%   |
| Lexar                  | 2         | 0.14%   |
| High Bridge            | 2         | 0.14%   |
| ff                     | 2         | 0.14%   |
| fef5                   | 2         | 0.14%   |
| CSX                    | 2         | 0.14%   |
| Apacer                 | 2         | 0.14%   |
| 4ea5                   | 2         | 0.14%   |
| Walton Chaintech       | 1         | 0.07%   |
| Unknown (0x8945)       | 1         | 0.07%   |
| Unknown (0x0B38)       | 1         | 0.07%   |
| Unknown (08B5)         | 1         | 0.07%   |
| Unknown (07F7)         | 1         | 0.07%   |
| Unknown (000080B30080) | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 28        | 1.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 1%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.74%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 11        | 0.74%   |
| Unknown                                                          | 10        | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 9         | 0.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.6%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 8         | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.54%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 8         | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.54%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 7         | 0.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 7         | 0.47%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.4%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 6         | 0.4%    |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 6         | 0.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 6         | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 5         | 0.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 5         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 5         | 0.33%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.33%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 5         | 0.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.33%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 446       | 36.74%  |
| DDR3    | 436       | 35.91%  |
| DDR2    | 99        | 8.15%   |
| LPDDR4  | 70        | 5.77%   |
| SDRAM   | 46        | 3.79%   |
| Unknown | 39        | 3.21%   |
| LPDDR3  | 34        | 2.8%    |
| DDR5    | 17        | 1.4%    |
| DDR     | 11        | 0.91%   |
| LPDDR5  | 9         | 0.74%   |
| DRAM    | 7         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 767       | 63.86%  |
| DIMM         | 318       | 26.48%  |
| Row Of Chips | 95        | 7.91%   |
| Chip         | 11        | 0.92%   |
| Unknown      | 9         | 0.75%   |
| FB-DIMM      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 445       | 33.01%  |
| 4096  | 398       | 29.53%  |
| 2048  | 238       | 17.66%  |
| 16384 | 134       | 9.94%   |
| 1024  | 84        | 6.23%   |
| 32768 | 33        | 2.45%   |
| 512   | 14        | 1.04%   |
| 256   | 2         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 275       | 21.07%  |
| 3200    | 169       | 12.95%  |
| 2667    | 152       | 11.65%  |
| 2400    | 89        | 6.82%   |
| 1333    | 89        | 6.82%   |
| Unknown | 52        | 3.98%   |
| 667     | 50        | 3.83%   |
| 2133    | 47        | 3.6%    |
| 1334    | 44        | 3.37%   |
| 800     | 34        | 2.61%   |
| 3600    | 25        | 1.92%   |
| 1066    | 25        | 1.92%   |
| 1867    | 23        | 1.76%   |
| 4267    | 20        | 1.53%   |
| 3266    | 16        | 1.23%   |
| 2048    | 12        | 0.92%   |
| 1067    | 12        | 0.92%   |
| 4800    | 11        | 0.84%   |
| 4199    | 11        | 0.84%   |
| 3733    | 11        | 0.84%   |
| 975     | 11        | 0.84%   |
| 533     | 11        | 0.84%   |
| 1866    | 9         | 0.69%   |
| 6400    | 8         | 0.61%   |
| 1800    | 8         | 0.61%   |
| 400     | 7         | 0.54%   |
| 3400    | 6         | 0.46%   |
| 3000    | 6         | 0.46%   |
| 2933    | 6         | 0.46%   |
| 3800    | 5         | 0.38%   |
| 8400    | 4         | 0.31%   |
| 4266    | 4         | 0.31%   |
| 3866    | 4         | 0.31%   |
| 2666    | 4         | 0.31%   |
| 333     | 4         | 0.31%   |
| 6000    | 3         | 0.23%   |
| 2800    | 3         | 0.23%   |
| 5600    | 2         | 0.15%   |
| 5200    | 2         | 0.15%   |
| 3666    | 2         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 63        | 32.14%  |
| Canon                 | 37        | 18.88%  |
| Brother Industries    | 32        | 16.33%  |
| Seiko Epson           | 24        | 12.24%  |
| Samsung Electronics   | 22        | 11.22%  |
| Lexmark International | 5         | 2.55%   |
| Ricoh                 | 3         | 1.53%   |
| STMicroelectronics    | 2         | 1.02%   |
| Zebra                 | 1         | 0.51%   |
| Toshiba TEC           | 1         | 0.51%   |
| QinHeng Electronics   | 1         | 0.51%   |
| Pantum                | 1         | 0.51%   |
| Kyocera               | 1         | 0.51%   |
| Konica Minolta        | 1         | 0.51%   |
| GG IMAGE              | 1         | 0.51%   |
| Dymo-CoStar           | 1         | 0.51%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 4         | 2.04%   |
| Canon TS3100 series                                       | 4         | 2.04%   |
| Seiko Epson L3110 Series                                  | 3         | 1.53%   |
| Samsung ML-216x Series Laser Printer                      | 3         | 1.53%   |
| Samsung M2070 Series                                      | 3         | 1.53%   |
| HP LaserJet 1020                                          | 3         | 1.53%   |
| HP ENVY 5000 series                                       | 3         | 1.53%   |
| HP ENVY 4520 series                                       | 3         | 1.53%   |
| Canon PIXMA MG3600 Series                                 | 3         | 1.53%   |
| Canon PIXMA MG2500 Series                                 | 3         | 1.53%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.02%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 2         | 1.02%   |
| Seiko Epson ET-2710 Series                                | 2         | 1.02%   |
| Samsung SCX-3400 Series                                   | 2         | 1.02%   |
| Samsung M2020 Series                                      | 2         | 1.02%   |
| Samsung CLX-3300 Series                                   | 2         | 1.02%   |
| Samsung C460 Series                                       | 2         | 1.02%   |
| HP OfficeJet 6950                                         | 2         | 1.02%   |
| HP LaserJet Professional P1102w                           | 2         | 1.02%   |
| HP LaserJet Professional P 1102w                          | 2         | 1.02%   |
| HP LaserJet P1102                                         | 2         | 1.02%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.02%   |
| HP DeskJet F2492 All-in-One                               | 2         | 1.02%   |
| HP DeskJet 2130 series                                    | 2         | 1.02%   |
| HP Deskjet 1510                                           | 2         | 1.02%   |
| HP DeskJet 1110 series                                    | 2         | 1.02%   |
| Canon PIXMA MX340                                         | 2         | 1.02%   |
| Canon MF4010 series                                       | 2         | 1.02%   |
| Canon LiDE 400                                            | 2         | 1.02%   |
| Brother HL-L2350DW series                                 | 2         | 1.02%   |
| Brother HL-L2340D series                                  | 2         | 1.02%   |
| Brother HL-52x0 series                                    | 2         | 1.02%   |
| Brother HL-2140 series                                    | 2         | 1.02%   |
| Brother HL-2130 series                                    | 2         | 1.02%   |
| Brother DCP-T300                                          | 2         | 1.02%   |
| Zebra ZP 450 Printer                                      | 1         | 0.51%   |
| Toshiba TEC e-STD120 USB                                  | 1         | 0.51%   |
| Seiko Epson XP-7100 Series                                | 1         | 0.51%   |
| Seiko Epson XP-235 Series                                 | 1         | 0.51%   |
| Seiko Epson XP-225 Series                                 | 1         | 0.51%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 23        | 71.88%  |
| Seiko Epson     | 5         | 15.63%  |
| Hewlett-Packard | 4         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo]       | 3         | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20                | 3         | 9.09%   |
| Canon CanoScan LiDE 90                            | 3         | 9.09%   |
| Canon CanoScan LIDE 25                            | 2         | 6.06%   |
| Canon CanoScan LiDE 220                           | 2         | 6.06%   |
| Canon CanoScan LiDE 200                           | 2         | 6.06%   |
| Canon CanoScan LiDE 110                           | 2         | 6.06%   |
| Canon CanoScan LiDE 100                           | 2         | 6.06%   |
| Canon CanoScan 8800F                              | 2         | 6.06%   |
| Seiko Epson Scanner                               | 1         | 3.03%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 3.03%   |
| HP ScanJet 5300c/5370c                            | 1         | 3.03%   |
| HP ScanJet 2400c                                  | 1         | 3.03%   |
| HP Scanjet 200                                    | 1         | 3.03%   |
| HP PSC 1200                                       | 1         | 3.03%   |
| Canon CanoScan LiDE 700F                          | 1         | 3.03%   |
| Canon CanoScan LiDE 60                            | 1         | 3.03%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40            | 1         | 3.03%   |
| Canon CanoScan LiDE 210                           | 1         | 3.03%   |
| Canon CanoScan D660U                              | 1         | 3.03%   |
| Canon CanoScan 5600F                              | 1         | 3.03%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 844       | 21.7%   |
| Microdia                               | 349       | 8.97%   |
| Realtek Semiconductor                  | 289       | 7.43%   |
| IMC Networks                           | 260       | 6.69%   |
| Sunplus Innovation Technology          | 204       | 5.25%   |
| Apple                                  | 191       | 4.91%   |
| Suyin                                  | 170       | 4.37%   |
| Bison Electronics                      | 169       | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 165       | 4.24%   |
| Quanta                                 | 160       | 4.11%   |
| Logitech                               | 137       | 3.52%   |
| Syntek                                 | 95        | 2.44%   |
| Acer                                   | 92        | 2.37%   |
| Lite-On Technology                     | 77        | 1.98%   |
| Silicon Motion                         | 71        | 1.83%   |
| Alcor Micro                            | 67        | 1.72%   |
| Ricoh                                  | 43        | 1.11%   |
| Luxvisions Innotech Limited            | 42        | 1.08%   |
| Microsoft                              | 41        | 1.05%   |
| Samsung Electronics                    | 33        | 0.85%   |
| Sonix Technology                       | 28        | 0.72%   |
| Z-Star Microelectronics                | 26        | 0.67%   |
| Importek                               | 22        | 0.57%   |
| ALi                                    | 21        | 0.54%   |
| icSpring                               | 20        | 0.51%   |
| Generalplus Technology                 | 18        | 0.46%   |
| GEMBIRD                                | 16        | 0.41%   |
| Primax Electronics                     | 15        | 0.39%   |
| Lenovo                                 | 15        | 0.39%   |
| SunplusIT                              | 14        | 0.36%   |
| OmniVision Technologies                | 13        | 0.33%   |
| ARC International                      | 12        | 0.31%   |
| Genesys Logic                          | 10        | 0.26%   |
| Y Media                                | 7         | 0.18%   |
| Cubeternet                             | 7         | 0.18%   |
| Sunplus Technology                     | 6         | 0.15%   |
| Shenzhen Kingcome Optoelectronic       | 6         | 0.15%   |
| Jieli Technology                       | 6         | 0.15%   |
| Intel                                  | 6         | 0.15%   |
| Shinetech                              | 5         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 120       | 3.07%   |
| Microdia Integrated_Webcam_HD                    | 72        | 1.84%   |
| Apple FaceTime HD Camera (Built-in)              | 61        | 1.56%   |
| Realtek Integrated_Webcam_HD                     | 60        | 1.53%   |
| IMC Networks USB2.0 HD UVC WebCam                | 60        | 1.53%   |
| Chicony HD WebCam                                | 52        | 1.33%   |
| Bison Integrated Camera                          | 50        | 1.28%   |
| Syntek Integrated Camera                         | 49        | 1.25%   |
| IMC Networks Integrated Camera                   | 49        | 1.25%   |
| Apple Built-in iSight                            | 48        | 1.23%   |
| Realtek USB Camera                               | 47        | 1.2%    |
| Chicony HP Truevision HD                         | 45        | 1.15%   |
| Sunplus Integrated_Webcam_HD                     | 41        | 1.05%   |
| Microdia Integrated Webcam                       | 41        | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 41        | 1.05%   |
| Logitech Webcam C270                             | 37        | 0.95%   |
| Chicony TOSHIBA Web Camera - HD                  | 35        | 0.89%   |
| Samsung Galaxy series, misc. (MTP mode)          | 33        | 0.84%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 32        | 0.82%   |
| Chicony USB 2.0 Camera                           | 32        | 0.82%   |
| Alcor Micro USB 2.0 PC cam                       | 32        | 0.82%   |
| Chicony HP TrueVision HD Camera                  | 29        | 0.74%   |
| Chicony EasyCamera                               | 29        | 0.74%   |
| Acer Integrated Camera                           | 29        | 0.74%   |
| Chicony Lenovo EasyCamera                        | 27        | 0.69%   |
| Apple FaceTime HD Camera                         | 27        | 0.69%   |
| Microdia USB 2.0 Camera                          | 26        | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 26        | 0.66%   |
| Realtek Integrated Webcam                        | 25        | 0.64%   |
| Lite-On HP HD Camera                             | 25        | 0.64%   |
| Chicony HP HD Webcam                             | 25        | 0.64%   |
| Bison Lenovo EasyCamera                          | 25        | 0.64%   |
| Chicony VGA WebCam                               | 24        | 0.61%   |
| Suyin HP Truevision HD                           | 23        | 0.59%   |
| Microdia Sonix USB 2.0 Camera                    | 23        | 0.59%   |
| Chicony HP HD Camera                             | 23        | 0.59%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 22        | 0.56%   |
| Sunplus HD WebCam                                | 21        | 0.54%   |
| Quanta HD User Facing                            | 21        | 0.54%   |
| Microdia Webcam Vitade AF                        | 21        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 273       | 43.13%  |
| Synaptics                          | 90        | 14.22%  |
| AuthenTec                          | 79        | 12.48%  |
| Shenzhen Goodix Technology         | 66        | 10.43%  |
| Upek                               | 39        | 6.16%   |
| Elan Microelectronics              | 35        | 5.53%   |
| STMicroelectronics                 | 19        | 3%      |
| LighTuning Technology              | 18        | 2.84%   |
| Samsung Electronics                | 4         | 0.63%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.63%   |
| HOLTEK                             | 2         | 0.32%   |
| Next Biometrics                    | 1         | 0.16%   |
| FocalTech                          | 1         | 0.16%   |
| Focal-systems.Corp                 | 1         | 0.16%   |
| Dell                               | 1         | 0.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 59        | 9.32%   |
| Shenzhen Goodix  Fingerprint Device                                        | 39        | 6.16%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 37        | 5.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 31        | 4.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 29        | 4.58%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 26        | 4.11%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 26        | 4.11%   |
| Validity Sensors VFS491                                                    | 22        | 3.48%   |
| Validity Sensors Fingerprint scanner                                       | 22        | 3.48%   |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 3.48%   |
| AuthenTec AES2810                                                          | 22        | 3.48%   |
| STMicroelectronics Fingerprint Reader                                      | 19        | 3%      |
| Elan ELAN:ARM-M4                                                           | 18        | 2.84%   |
| Elan ELAN:Fingerprint                                                      | 17        | 2.69%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 2.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 15        | 2.37%   |
| Synaptics  WBDI                                                            | 15        | 2.37%   |
| Synaptics WBDI                                                             | 14        | 2.21%   |
| Synaptics Fingerprint reader [HP G6]                                       | 14        | 2.21%   |
| AuthenTec AES1600                                                          | 13        | 2.05%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.9%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 1.74%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 1.74%   |
| Synaptics UWP WBDI                                                         | 9         | 1.42%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.26%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 1.26%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.11%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 7         | 1.11%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 0.95%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.79%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.79%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.79%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.79%   |
| LighTuning Fingerprint Sensor                                              | 5         | 0.79%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.79%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.79%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 0.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.63%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 131       | 49.43%  |
| Alcor Micro                       | 48        | 18.11%  |
| O2 Micro                          | 33        | 12.45%  |
| Upek                              | 12        | 4.53%   |
| Lenovo                            | 12        | 4.53%   |
| SCM Microsystems                  | 4         | 1.51%   |
| Realtek Semiconductor             | 4         | 1.51%   |
| VASCO Data Security International | 3         | 1.13%   |
| Gemalto (was Gemplus)             | 3         | 1.13%   |
| Yubico.com                        | 2         | 0.75%   |
| Fujitsu Siemens Computers         | 2         | 0.75%   |
| Chicony Electronics               | 2         | 0.75%   |
| Advanced Card Systems             | 2         | 0.75%   |
| Reiner SCT Kartensysteme          | 1         | 0.38%   |
| OmniKey                           | 1         | 0.38%   |
| NXP Semiconductors                | 1         | 0.38%   |
| Kobil Systems                     | 1         | 0.38%   |
| Jing-Mold Enterprise              | 1         | 0.38%   |
| Hewlett-Packard                   | 1         | 0.38%   |
| Bit4id                            | 1         | 0.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 55        | 20.68%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 47        | 17.67%  |
| Broadcom 5880                                                                | 34        | 12.78%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 31        | 11.65%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 28        | 10.53%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 12        | 4.51%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 4.14%   |
| Broadcom 58200                                                               | 10        | 3.76%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.88%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 1.5%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 1.13%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.13%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.75%   |
| VASCO Data Security International DIGIPASS 870                               | 2         | 0.75%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 0.75%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.75%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.75%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.38%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.38%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.38%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.38%   |
| NXP Semiconductors PR533                                                     | 1         | 0.38%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.38%   |
| Kobil Systems KOBIL Class 3 Reader                                           | 1         | 0.38%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.38%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.38%   |
| Bit4id miniLector EVO                                                        | 1         | 0.38%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.38%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.38%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4772      | 69.01%  |
| 1     | 1734      | 25.08%  |
| 2     | 361       | 5.22%   |
| 3     | 42        | 0.61%   |
| 4     | 4         | 0.06%   |
| 8     | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 623       | 24.86%  |
| Graphics card            | 615       | 24.54%  |
| Net/wireless             | 428       | 17.08%  |
| Chipcard                 | 247       | 9.86%   |
| Multimedia controller    | 237       | 9.46%   |
| Communication controller | 61        | 2.43%   |
| Storage                  | 59        | 2.35%   |
| Modem                    | 47        | 1.88%   |
| Bluetooth                | 46        | 1.84%   |
| Sound                    | 25        | 1%      |
| Camera                   | 23        | 0.92%   |
| Unassigned class         | 20        | 0.8%    |
| Net/ethernet             | 16        | 0.64%   |
| Flash memory             | 14        | 0.56%   |
| Card reader              | 10        | 0.4%    |
| Network                  | 9         | 0.36%   |
| Storage/raid             | 8         | 0.32%   |
| Storage/ide              | 6         | 0.24%   |
| Dvb card                 | 5         | 0.2%    |
| Storage/nvme             | 3         | 0.12%   |
| Unclassified device      | 2         | 0.08%   |
| Video                    | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |

